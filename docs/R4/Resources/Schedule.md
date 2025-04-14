Comparison of 
Generated at Monday, April 14, 2025 6:17:30 PM

### Schedule

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | Schedule |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Schedule` |
| Version | 4.0.1 |
| Description | A container for slots of time that may be available for booking appointments. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1154` |
| Database Snapshot Count | `17` |
| Database Differential Count | `9` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Schedule` | `Schedule` | `Schedule` | Schedule | A container for slots of time that may be available for booking appointments | 0..* | Schedule |  |  |
| `Schedule.active` | `Schedule.active` | `active` | Schedule.active | Whether this schedule is in active use | 0..1 | boolean |  |  |
| `Schedule.actor` | `Schedule.actor` | `actor` | Schedule.actor | Resource(s) that availability information is being provided for | 1..* | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Schedule.comment` | `Schedule.comment` | `comment` | Schedule.comment | Comments on availability | 0..1 | string |  |  |
| `Schedule.contained` | `Schedule.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Schedule.extension` | `Schedule.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Schedule.id` | `Schedule.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Schedule.identifier` | `Schedule.identifier` | `identifier` | Schedule.identifier | External Ids for this item | 0..* | Identifier |  |  |
| `Schedule.implicitRules` | `Schedule.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Schedule.language` | `Schedule.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `Schedule.meta` | `Schedule.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Schedule.modifierExtension` | `Schedule.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Schedule.planningHorizon` | `Schedule.planningHorizon` | `planningHorizon` | Schedule.planningHorizon | Period of time covered by schedule | 0..1 | Period |  |  |
| `Schedule.serviceCategory` | `Schedule.serviceCategory` | `serviceCategory` | Schedule.serviceCategory | High-level category | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/service-category` |
| `Schedule.serviceType` | `Schedule.serviceType` | `serviceType` | Schedule.serviceType | Specific service | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/service-type` |
| `Schedule.specialty` | `Schedule.specialty` | `specialty` | Schedule.specialty | Type of specialty needed | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` |
| `Schedule.text` | `Schedule.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Schedule](/docs/R2/Resources/Schedule.md)<br/> `http://hl7.org/fhir/StructureDefinition/Schedule\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `153`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `319`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Schedule](/docs/R3/Resources/Schedule.md)<br/> `http://hl7.org/fhir/StructureDefinition/Schedule\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `513`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `705`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Schedule](/docs/R4/Resources/Schedule.md)<br/> `http://hl7.org/fhir/StructureDefinition/Schedule\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1609`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1610`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Schedule](/docs/R4B/Resources/Schedule.md)<br/> `http://hl7.org/fhir/StructureDefinition/Schedule\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1038`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1267`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Schedule](/docs/R5/Resources/Schedule.md)<br/> `http://hl7.org/fhir/StructureDefinition/Schedule\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Schedule from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Schedule](/docs/R2/Resources/Schedule.md)| Relationship | [R3 Schedule](/docs/R3/Resources/Schedule.md)| Relationship | R4 Schedule| Relationship | [R4B Schedule](/docs/R4B/Resources/Schedule.md)| Relationship | [R5 Schedule](/docs/R5/Resources/Schedule.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Schedule`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7707)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7708)| `Schedule`| _Equivalent_<br/>(18222/18223)| **`Schedule`**| _Equivalent_<br/>(32860/32861)| `Schedule`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47184)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47185)| `Schedule`
| `Schedule.id`| _Equivalent_<br/>(7709/7710)| `Schedule.id`| _Equivalent_<br/>(18224/18225)| **`Schedule.id`**| _Equivalent_<br/>(32862/32863)| `Schedule.id`| _Equivalent_<br/>(47186/47187)| `Schedule.id`
| `Schedule.meta`| _Equivalent_<br/>(7711/7712)| `Schedule.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18226)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18227)| **`Schedule.meta`**| _Equivalent_<br/>(32864/32865)| `Schedule.meta`| _Equivalent_<br/>(47188/47189)| `Schedule.meta`
| `Schedule.implicitRules`| _Equivalent_<br/>(7713/7714)| `Schedule.implicitRules`| _Equivalent_<br/>(18228/18229)| **`Schedule.implicitRules`**| _Equivalent_<br/>(32866/32867)| `Schedule.implicitRules`| _Equivalent_<br/>(47190/47191)| `Schedule.implicitRules`
| `Schedule.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7715)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7716)| `Schedule.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18230)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18231)| **`Schedule.language`**| _Equivalent_<br/>(32868/32869)| `Schedule.language`| _Equivalent_<br/>(47192/47193)| `Schedule.language`
| `Schedule.text`| _Equivalent_<br/>(7717/7718)| `Schedule.text`| _Equivalent_<br/>(18232/18233)| **`Schedule.text`**| _Equivalent_<br/>(32870/32871)| `Schedule.text`| _Equivalent_<br/>(47194/47195)| `Schedule.text`
| `Schedule.contained`| _Equivalent_<br/>(7719/7720)| `Schedule.contained`| _Equivalent_<br/>(18234/18235)| **`Schedule.contained`**| _Equivalent_<br/>(32872/32873)| `Schedule.contained`| _Equivalent_<br/>(47196/47197)| `Schedule.contained`
| `Schedule.extension`| _Equivalent_<br/>(7721/7722)| `Schedule.extension`| _Equivalent_<br/>(18236/18237)| **`Schedule.extension`**| _Equivalent_<br/>(32874/32875)| `Schedule.extension`| _Equivalent_<br/>(47198/47199)| `Schedule.extension`
| `Schedule.modifierExtension`| _Equivalent_<br/>(7723/7724)| `Schedule.modifierExtension`| _Equivalent_<br/>(18238/18239)| **`Schedule.modifierExtension`**| _Equivalent_<br/>(32876/32877)| `Schedule.modifierExtension`| _Equivalent_<br/>(47200/47201)| `Schedule.modifierExtension`
| `Schedule.identifier`| _Equivalent_<br/>(7725/7726)| `Schedule.identifier`| _Equivalent_<br/>(18240/18241)| **`Schedule.identifier`**| _Equivalent_<br/>(32878/32879)| `Schedule.identifier`| _Equivalent_<br/>(47202/47203)| `Schedule.identifier`
| | | `Schedule.active`| _Equivalent_<br/>(18242/18243)| **`Schedule.active`**| _Equivalent_<br/>(32880/32881)| `Schedule.active`| _Equivalent_<br/>(47204/47205)| `Schedule.active`
| | | `Schedule.serviceCategory`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18244)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18245)| **`Schedule.serviceCategory`**| _Equivalent_<br/>(32882/32883)| `Schedule.serviceCategory`| _Equivalent_<br/>(47206/47207)| `Schedule.serviceCategory`
| `Schedule.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(404)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(748)| `Schedule.serviceType`| _Equivalent_<br/>(18246/18247)| **`Schedule.serviceType`**| _Equivalent_<br/>(32884/32885)| `Schedule.serviceType`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47208)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47209)| `Schedule.serviceType`
| | | `Schedule.specialty`| _Equivalent_<br/>(18248/18249)| **`Schedule.specialty`**| _Equivalent_<br/>(32886/32887)| `Schedule.specialty`| _Equivalent_<br/>(47210/47211)| `Schedule.specialty`
| `Schedule.actor`| →→→→ _RelatedTo_ →→→→ <br/>(7727)<hr/>←←←← _RelatedTo_ ←←←← <br/>(7728)| `Schedule.actor`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18250)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18251)| **`Schedule.actor`**| _Equivalent_<br/>(32888/32889)| `Schedule.actor`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47212)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47213)| `Schedule.actor`
| `Schedule.planningHorizon`| _Equivalent_<br/>(7729/7730)| `Schedule.planningHorizon`| _Equivalent_<br/>(18252/18253)| **`Schedule.planningHorizon`**| _Equivalent_<br/>(32890/32891)| `Schedule.planningHorizon`| _Equivalent_<br/>(47214/47215)| `Schedule.planningHorizon`
| `Schedule.comment`| _Equivalent_<br/>(7731/7732)| `Schedule.comment`| _Equivalent_<br/>(18254/18255)| **`Schedule.comment`**| _Equivalent_<br/>(32892/32893)| `Schedule.comment`| _Equivalent_<br/>(47216/47217)| `Schedule.comment`
| *14 of 14 elements used* | | *17 of 17 elements used* | | *17 of 17 elements used* | | *17 of 17 elements used* | | *17 of 18 elements used* <br/>remaining elements:<br/>`Schedule.name`

