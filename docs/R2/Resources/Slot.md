Comparison of 
Generated at Thursday, April 3, 2025 8:18:07 AM

### Slot

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Slot |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Slot` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Slot Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `127` |
| Database Snapshot Count | `17` |
| Database Differential Count | `9` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Slot` | `Slot` | `Slot` | Slot | A slot of time on a schedule that may be available for booking appointments | 0..* | Slot |  |  |
| `Slot.comment` | `Slot.comment` | `comment` |  | Comments on the slot to describe any extended information. Such as custom constraints on the slot | 0..1 | string |  |  |
| `Slot.contained` | `Slot.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Slot.end` | `Slot.end` | `end` |  | Date/Time that the slot is to conclude | 1..1 | instant |  |  |
| `Slot.extension` | `Slot.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Slot.freeBusyType` | `Slot.freeBusyType` | `freeBusyType` |  | busy \| free \| busy-unavailable \| busy-tentative | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/slotstatus` |
| `Slot.id` | `Slot.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Slot.identifier` | `Slot.identifier` | `identifier` |  | External Ids for this item | 0..* | Identifier |  |  |
| `Slot.implicitRules` | `Slot.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Slot.language` | `Slot.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Slot.meta` | `Slot.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Slot.modifierExtension` | `Slot.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Slot.overbooked` | `Slot.overbooked` | `overbooked` |  | This slot has already been overbooked, appointments are unlikely to be accepted for this time | 0..1 | boolean |  |  |
| `Slot.schedule` | `Slot.schedule` | `schedule` |  | The schedule resource that this slot defines an interval of status information | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Schedule) |  |  |
| `Slot.start` | `Slot.start` | `start` |  | Date/Time that the slot is to begin | 1..1 | instant |  |  |
| `Slot.text` | `Slot.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Slot.type` | `Slot.type` | `type` |  | The type of appointments that can be booked into this slot (ideally this would be an identifiable service - which is at a location, rather than the location itself). If provided then this overrides the value provided on the availability resource | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Slot](/docs/R2/Resources/Slot.md)<br/> `http://hl7.org/fhir/StructureDefinition/Slot\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `156`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `323`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Slot](/docs/R3/Resources/Slot.md)<br/> `http://hl7.org/fhir/StructureDefinition/Slot\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `516`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `709`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Slot](/docs/R4/Resources/Slot.md)<br/> `http://hl7.org/fhir/StructureDefinition/Slot\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1615`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1616`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Slot](/docs/R4B/Resources/Slot.md)<br/> `http://hl7.org/fhir/StructureDefinition/Slot\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1041`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1270`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Slot](/docs/R5/Resources/Slot.md)<br/> `http://hl7.org/fhir/StructureDefinition/Slot\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Slot from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Slot| Relationship | [R3 Slot](/docs/R3/Resources/Slot.md)| Relationship | [R4 Slot](/docs/R4/Resources/Slot.md)| Relationship | [R4B Slot](/docs/R4B/Resources/Slot.md)| Relationship | [R5 Slot](/docs/R5/Resources/Slot.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Slot`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7784)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7785)| `Slot`| _Equivalent_<br/>(18419/18420)| `Slot`| _Equivalent_<br/>(33136/33137)| `Slot`| _Equivalent_<br/>(47371/47372)| `Slot`
| **`Slot.id`**| _Equivalent_<br/>(7786/7787)| `Slot.id`| _Equivalent_<br/>(18421/18422)| `Slot.id`| _Equivalent_<br/>(33138/33139)| `Slot.id`| _Equivalent_<br/>(47373/47374)| `Slot.id`
| **`Slot.meta`**| _Equivalent_<br/>(7788/7789)| `Slot.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18423)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18424)| `Slot.meta`| _Equivalent_<br/>(33140/33141)| `Slot.meta`| _Equivalent_<br/>(47375/47376)| `Slot.meta`
| **`Slot.implicitRules`**| _Equivalent_<br/>(7790/7791)| `Slot.implicitRules`| _Equivalent_<br/>(18425/18426)| `Slot.implicitRules`| _Equivalent_<br/>(33142/33143)| `Slot.implicitRules`| _Equivalent_<br/>(47377/47378)| `Slot.implicitRules`
| **`Slot.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7792)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7793)| `Slot.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18427)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18428)| `Slot.language`| _Equivalent_<br/>(33144/33145)| `Slot.language`| _Equivalent_<br/>(47379/47380)| `Slot.language`
| **`Slot.text`**| _Equivalent_<br/>(7794/7795)| `Slot.text`| _Equivalent_<br/>(18429/18430)| `Slot.text`| _Equivalent_<br/>(33146/33147)| `Slot.text`| _Equivalent_<br/>(47381/47382)| `Slot.text`
| **`Slot.contained`**| _Equivalent_<br/>(7796/7797)| `Slot.contained`| _Equivalent_<br/>(18431/18432)| `Slot.contained`| _Equivalent_<br/>(33148/33149)| `Slot.contained`| _Equivalent_<br/>(47383/47384)| `Slot.contained`
| **`Slot.extension`**| _Equivalent_<br/>(7798/7799)| `Slot.extension`| _Equivalent_<br/>(18433/18434)| `Slot.extension`| _Equivalent_<br/>(33150/33151)| `Slot.extension`| _Equivalent_<br/>(47385/47386)| `Slot.extension`
| **`Slot.modifierExtension`**| _Equivalent_<br/>(7800/7801)| `Slot.modifierExtension`| _Equivalent_<br/>(18435/18436)| `Slot.modifierExtension`| _Equivalent_<br/>(33152/33153)| `Slot.modifierExtension`| _Equivalent_<br/>(47387/47388)| `Slot.modifierExtension`
| **`Slot.identifier`**| _Equivalent_<br/>(7802/7803)| `Slot.identifier`| _Equivalent_<br/>(18437/18438)| `Slot.identifier`| _Equivalent_<br/>(33154/33155)| `Slot.identifier`| _Equivalent_<br/>(47389/47390)| `Slot.identifier`
| **`Slot.type`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(407)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(750)| `Slot.serviceType`| _Equivalent_<br/>(18441/18442)| `Slot.serviceType`| _Equivalent_<br/>(33158/33159)| `Slot.serviceType`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47393)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47394)| `Slot.serviceType`
| **`Slot.schedule`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7804)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7805)| `Slot.schedule`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18447)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18448)| `Slot.schedule`| _Equivalent_<br/>(33164/33165)| `Slot.schedule`| _Equivalent_<br/>(47399/47400)| `Slot.schedule`
| **`Slot.freeBusyType`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(406)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(751)| `Slot.status`| _Equivalent_<br/>(18449/18450)| `Slot.status`| _Equivalent_<br/>(33166/33167)| `Slot.status`| _Equivalent_<br/>(47401/47402)| `Slot.status`
| **`Slot.start`**| _Equivalent_<br/>(7806/7807)| `Slot.start`| _Equivalent_<br/>(18451/18452)| `Slot.start`| _Equivalent_<br/>(33168/33169)| `Slot.start`| _Equivalent_<br/>(47403/47404)| `Slot.start`
| **`Slot.end`**| _Equivalent_<br/>(7808/7809)| `Slot.end`| _Equivalent_<br/>(18453/18454)| `Slot.end`| _Equivalent_<br/>(33170/33171)| `Slot.end`| _Equivalent_<br/>(47405/47406)| `Slot.end`
| **`Slot.overbooked`**| _Equivalent_<br/>(7810/7811)| `Slot.overbooked`| _Equivalent_<br/>(18455/18456)| `Slot.overbooked`| _Equivalent_<br/>(33172/33173)| `Slot.overbooked`| _Equivalent_<br/>(47407/47408)| `Slot.overbooked`
| **`Slot.comment`**| _Equivalent_<br/>(7812/7813)| `Slot.comment`| _Equivalent_<br/>(18457/18458)| `Slot.comment`| _Equivalent_<br/>(33174/33175)| `Slot.comment`| _Equivalent_<br/>(47409/47410)| `Slot.comment`
| *17 of 17 elements used* | | *17 of 20 elements used* <br/>remaining elements:<br/>`Slot.appointmentType`, `Slot.serviceCategory`, `Slot.specialty`| | *17 of 20 elements used* <br/>remaining elements:<br/>`Slot.appointmentType`, `Slot.serviceCategory`, `Slot.specialty`| | *17 of 20 elements used* <br/>remaining elements:<br/>`Slot.appointmentType`, `Slot.serviceCategory`, `Slot.specialty`| | *17 of 20 elements used* <br/>remaining elements:<br/>`Slot.appointmentType`, `Slot.serviceCategory`, `Slot.specialty`

