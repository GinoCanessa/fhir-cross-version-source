Comparison of 
Generated at Monday, April 14, 2025 6:17:50 PM

### Slot

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Slot |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Slot` |
| Version | 5.0.0 |
| Description | A slot of time on a schedule that may be available for booking appointments. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2382` |
| Database Snapshot Count | `20` |
| Database Differential Count | `12` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Slot` | `Slot` | `Slot` | Slot | A slot of time on a schedule that may be available for booking appointments | 0..* | Slot |  |  |
| `Slot.appointmentType` | `Slot.appointmentType` | `appointmentType` | Slot.appointmentType | The style of appointment or patient that may be booked in the slot (not service type) | 0..* | CodeableConcept | `Preferred` | `http://terminology.hl7.org/ValueSet/v2-0276` |
| `Slot.comment` | `Slot.comment` | `comment` | Slot.comment | Comments on the slot to describe any extended information. Such as custom constraints on the slot | 0..1 | string |  |  |
| `Slot.contained` | `Slot.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Slot.end` | `Slot.end` | `end` | Slot.end | Date/Time that the slot is to conclude | 1..1 | instant |  |  |
| `Slot.extension` | `Slot.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Slot.id` | `Slot.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Slot.identifier` | `Slot.identifier` | `identifier` | Slot.identifier | External Ids for this item | 0..* | Identifier |  |  |
| `Slot.implicitRules` | `Slot.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Slot.language` | `Slot.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Slot.meta` | `Slot.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Slot.modifierExtension` | `Slot.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Slot.overbooked` | `Slot.overbooked` | `overbooked` | Slot.overbooked | This slot has already been overbooked, appointments are unlikely to be accepted for this time | 0..1 | boolean |  |  |
| `Slot.schedule` | `Slot.schedule` | `schedule` | Slot.schedule | The schedule resource that this slot defines an interval of status information | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Schedule) |  |  |
| `Slot.serviceCategory` | `Slot.serviceCategory` | `serviceCategory` | Slot.serviceCategory | A broad categorization of the service that is to be performed during this appointment | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/service-category` |
| `Slot.serviceType` | `Slot.serviceType` | `serviceType` | Slot.serviceType | The type of appointments that can be booked into this slot (ideally this would be an identifiable service - which is at a location, rather than the location itself). If provided then this overrides the value provided on the Schedule resource | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/HealthcareService) | `Example` | `http://hl7.org/fhir/ValueSet/service-type` |
| `Slot.specialty` | `Slot.specialty` | `specialty` | Slot.specialty | The specialty of a practitioner that would be required to perform the service requested in this appointment | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` |
| `Slot.start` | `Slot.start` | `start` | Slot.start | Date/Time that the slot is to begin | 1..1 | instant |  |  |
| `Slot.status` | `Slot.status` | `status` | Slot.status | busy \| free \| busy-unavailable \| busy-tentative \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/slotstatus|5.0.0` |
| `Slot.text` | `Slot.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Slot](/docs/R2/Resources/Slot.md)<br/> `http://hl7.org/fhir/StructureDefinition/Slot\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `156`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `323`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Slot](/docs/R3/Resources/Slot.md)<br/> `http://hl7.org/fhir/StructureDefinition/Slot\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `516`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `709`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Slot](/docs/R4/Resources/Slot.md)<br/> `http://hl7.org/fhir/StructureDefinition/Slot\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1615`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1616`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Slot](/docs/R4B/Resources/Slot.md)<br/> `http://hl7.org/fhir/StructureDefinition/Slot\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1041`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1270`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Slot](/docs/R5/Resources/Slot.md)<br/> `http://hl7.org/fhir/StructureDefinition/Slot\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Slot from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Slot](/docs/R2/Resources/Slot.md)| Relationship | [R3 Slot](/docs/R3/Resources/Slot.md)| Relationship | [R4 Slot](/docs/R4/Resources/Slot.md)| Relationship | [R4B Slot](/docs/R4B/Resources/Slot.md)| Relationship | R5 Slot
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Slot`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7784)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7785)| `Slot`| _Equivalent_<br/>(18419/18420)| `Slot`| _Equivalent_<br/>(33136/33137)| `Slot`| _Equivalent_<br/>(47371/47372)| **`Slot`**
| `Slot.id`| _Equivalent_<br/>(7786/7787)| `Slot.id`| _Equivalent_<br/>(18421/18422)| `Slot.id`| _Equivalent_<br/>(33138/33139)| `Slot.id`| _Equivalent_<br/>(47373/47374)| **`Slot.id`**
| `Slot.meta`| _Equivalent_<br/>(7788/7789)| `Slot.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18423)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18424)| `Slot.meta`| _Equivalent_<br/>(33140/33141)| `Slot.meta`| _Equivalent_<br/>(47375/47376)| **`Slot.meta`**
| `Slot.implicitRules`| _Equivalent_<br/>(7790/7791)| `Slot.implicitRules`| _Equivalent_<br/>(18425/18426)| `Slot.implicitRules`| _Equivalent_<br/>(33142/33143)| `Slot.implicitRules`| _Equivalent_<br/>(47377/47378)| **`Slot.implicitRules`**
| `Slot.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7792)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7793)| `Slot.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18427)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18428)| `Slot.language`| _Equivalent_<br/>(33144/33145)| `Slot.language`| _Equivalent_<br/>(47379/47380)| **`Slot.language`**
| `Slot.text`| _Equivalent_<br/>(7794/7795)| `Slot.text`| _Equivalent_<br/>(18429/18430)| `Slot.text`| _Equivalent_<br/>(33146/33147)| `Slot.text`| _Equivalent_<br/>(47381/47382)| **`Slot.text`**
| `Slot.contained`| _Equivalent_<br/>(7796/7797)| `Slot.contained`| _Equivalent_<br/>(18431/18432)| `Slot.contained`| _Equivalent_<br/>(33148/33149)| `Slot.contained`| _Equivalent_<br/>(47383/47384)| **`Slot.contained`**
| `Slot.extension`| _Equivalent_<br/>(7798/7799)| `Slot.extension`| _Equivalent_<br/>(18433/18434)| `Slot.extension`| _Equivalent_<br/>(33150/33151)| `Slot.extension`| _Equivalent_<br/>(47385/47386)| **`Slot.extension`**
| `Slot.modifierExtension`| _Equivalent_<br/>(7800/7801)| `Slot.modifierExtension`| _Equivalent_<br/>(18435/18436)| `Slot.modifierExtension`| _Equivalent_<br/>(33152/33153)| `Slot.modifierExtension`| _Equivalent_<br/>(47387/47388)| **`Slot.modifierExtension`**
| `Slot.identifier`| _Equivalent_<br/>(7802/7803)| `Slot.identifier`| _Equivalent_<br/>(18437/18438)| `Slot.identifier`| _Equivalent_<br/>(33154/33155)| `Slot.identifier`| _Equivalent_<br/>(47389/47390)| **`Slot.identifier`**
| | | `Slot.serviceCategory`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18439)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18440)| `Slot.serviceCategory`| _Equivalent_<br/>(33156/33157)| `Slot.serviceCategory`| _Equivalent_<br/>(47391/47392)| **`Slot.serviceCategory`**
| `Slot.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(407)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(750)| `Slot.serviceType`| _Equivalent_<br/>(18441/18442)| `Slot.serviceType`| _Equivalent_<br/>(33158/33159)| `Slot.serviceType`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47393)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47394)| **`Slot.serviceType`**
| | | `Slot.specialty`| _Equivalent_<br/>(18443/18444)| `Slot.specialty`| _Equivalent_<br/>(33160/33161)| `Slot.specialty`| _Equivalent_<br/>(47395/47396)| **`Slot.specialty`**
| | | `Slot.appointmentType`| _Equivalent_<br/>(18445/18446)| `Slot.appointmentType`| _Equivalent_<br/>(33162/33163)| `Slot.appointmentType`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47397)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47398)| **`Slot.appointmentType`**
| `Slot.schedule`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7804)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7805)| `Slot.schedule`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18447)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18448)| `Slot.schedule`| _Equivalent_<br/>(33164/33165)| `Slot.schedule`| _Equivalent_<br/>(47399/47400)| **`Slot.schedule`**
| `Slot.freeBusyType`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(406)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(751)| `Slot.status`| _Equivalent_<br/>(18449/18450)| `Slot.status`| _Equivalent_<br/>(33166/33167)| `Slot.status`| _Equivalent_<br/>(47401/47402)| **`Slot.status`**
| `Slot.start`| _Equivalent_<br/>(7806/7807)| `Slot.start`| _Equivalent_<br/>(18451/18452)| `Slot.start`| _Equivalent_<br/>(33168/33169)| `Slot.start`| _Equivalent_<br/>(47403/47404)| **`Slot.start`**
| `Slot.end`| _Equivalent_<br/>(7808/7809)| `Slot.end`| _Equivalent_<br/>(18453/18454)| `Slot.end`| _Equivalent_<br/>(33170/33171)| `Slot.end`| _Equivalent_<br/>(47405/47406)| **`Slot.end`**
| `Slot.overbooked`| _Equivalent_<br/>(7810/7811)| `Slot.overbooked`| _Equivalent_<br/>(18455/18456)| `Slot.overbooked`| _Equivalent_<br/>(33172/33173)| `Slot.overbooked`| _Equivalent_<br/>(47407/47408)| **`Slot.overbooked`**
| `Slot.comment`| _Equivalent_<br/>(7812/7813)| `Slot.comment`| _Equivalent_<br/>(18457/18458)| `Slot.comment`| _Equivalent_<br/>(33174/33175)| `Slot.comment`| _Equivalent_<br/>(47409/47410)| **`Slot.comment`**
| *17 of 17 elements used* | | *20 of 20 elements used* | | *20 of 20 elements used* | | *20 of 20 elements used* | | *20 of 20 elements used* 

