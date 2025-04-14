Comparison of 
Generated at Monday, April 14, 2025 6:17:37 PM

### Basic

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | Basic |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Basic` |
| Version | 4.3.0 |
| Description | Basic is used for handling concepts not yet defined in FHIR, narrative-only resources that don't map to an existing resource, and custom resources not appropriate for inclusion in the FHIR specification. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1646` |
| Database Snapshot Count | `14` |
| Database Differential Count | `6` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Basic` | `Basic` | `Basic` | Basic | Resource for non-supported content | 0..* | Basic |  |  |
| `Basic.author` | `Basic.author` | `author` | Basic.author | Who created | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Basic.code` | `Basic.code` | `code` | Basic.code | Kind of Resource | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/basic-resource-type` |
| `Basic.contained` | `Basic.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Basic.created` | `Basic.created` | `created` | Basic.created | When created | 0..1 | date |  |  |
| `Basic.extension` | `Basic.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Basic.id` | `Basic.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Basic.identifier` | `Basic.identifier` | `identifier` | Basic.identifier | Business identifier | 0..* | Identifier |  |  |
| `Basic.implicitRules` | `Basic.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Basic.language` | `Basic.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `Basic.meta` | `Basic.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Basic.modifierExtension` | `Basic.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Basic.subject` | `Basic.subject` | `subject` | Basic.subject | Identifies the focus of this resource | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Basic.text` | `Basic.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Basic](/docs/R2/Resources/Basic.md)<br/> `http://hl7.org/fhir/StructureDefinition/Basic\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `77`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `243`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Basic](/docs/R3/Resources/Basic.md)<br/> `http://hl7.org/fhir/StructureDefinition/Basic\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `422`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `618`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Basic](/docs/R4/Resources/Basic.md)<br/> `http://hl7.org/fhir/StructureDefinition/Basic\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1401`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1402`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Basic](/docs/R4B/Resources/Basic.md)<br/> `http://hl7.org/fhir/StructureDefinition/Basic\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `936`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1165`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Basic](/docs/R5/Resources/Basic.md)<br/> `http://hl7.org/fhir/StructureDefinition/Basic\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Basic from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Basic](/docs/R2/Resources/Basic.md)| Relationship | [R3 Basic](/docs/R3/Resources/Basic.md)| Relationship | [R4 Basic](/docs/R4/Resources/Basic.md)| Relationship | R4B Basic| Relationship | [R5 Basic](/docs/R5/Resources/Basic.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Basic`| _Equivalent_<br/>(3118/3119)| `Basic`| _Equivalent_<br/>(10408/10409)| `Basic`| _Equivalent_<br/>(21974/21975)| **`Basic`**| _Equivalent_<br/>(37051/37052)| `Basic`
| `Basic.id`| _Equivalent_<br/>(3120/3121)| `Basic.id`| _Equivalent_<br/>(10410/10411)| `Basic.id`| _Equivalent_<br/>(21976/21977)| **`Basic.id`**| _Equivalent_<br/>(37053/37054)| `Basic.id`
| `Basic.meta`| _Equivalent_<br/>(3122/3123)| `Basic.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10412)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10413)| `Basic.meta`| _Equivalent_<br/>(21978/21979)| **`Basic.meta`**| _Equivalent_<br/>(37055/37056)| `Basic.meta`
| `Basic.implicitRules`| _Equivalent_<br/>(3124/3125)| `Basic.implicitRules`| _Equivalent_<br/>(10414/10415)| `Basic.implicitRules`| _Equivalent_<br/>(21980/21981)| **`Basic.implicitRules`**| _Equivalent_<br/>(37057/37058)| `Basic.implicitRules`
| `Basic.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3126)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3127)| `Basic.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10416)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(10417)| `Basic.language`| _Equivalent_<br/>(21982/21983)| **`Basic.language`**| _Equivalent_<br/>(37059/37060)| `Basic.language`
| `Basic.text`| _Equivalent_<br/>(3128/3129)| `Basic.text`| _Equivalent_<br/>(10418/10419)| `Basic.text`| _Equivalent_<br/>(21984/21985)| **`Basic.text`**| _Equivalent_<br/>(37061/37062)| `Basic.text`
| `Basic.contained`| _Equivalent_<br/>(3130/3131)| `Basic.contained`| _Equivalent_<br/>(10420/10421)| `Basic.contained`| _Equivalent_<br/>(21986/21987)| **`Basic.contained`**| _Equivalent_<br/>(37063/37064)| `Basic.contained`
| `Basic.extension`| _Equivalent_<br/>(3132/3133)| `Basic.extension`| _Equivalent_<br/>(10422/10423)| `Basic.extension`| _Equivalent_<br/>(21988/21989)| **`Basic.extension`**| _Equivalent_<br/>(37065/37066)| `Basic.extension`
| `Basic.modifierExtension`| _Equivalent_<br/>(3134/3135)| `Basic.modifierExtension`| _Equivalent_<br/>(10424/10425)| `Basic.modifierExtension`| _Equivalent_<br/>(21990/21991)| **`Basic.modifierExtension`**| _Equivalent_<br/>(37067/37068)| `Basic.modifierExtension`
| `Basic.identifier`| _Equivalent_<br/>(3136/3137)| `Basic.identifier`| _Equivalent_<br/>(10426/10427)| `Basic.identifier`| _Equivalent_<br/>(21992/21993)| **`Basic.identifier`**| _Equivalent_<br/>(37069/37070)| `Basic.identifier`
| `Basic.code`| _Equivalent_<br/>(3138/3139)| `Basic.code`| _Equivalent_<br/>(10428/10429)| `Basic.code`| _Equivalent_<br/>(21994/21995)| **`Basic.code`**| _Equivalent_<br/>(37071/37072)| `Basic.code`
| `Basic.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3140)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3141)| `Basic.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10430)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10431)| `Basic.subject`| _Equivalent_<br/>(21996/21997)| **`Basic.subject`**| _Equivalent_<br/>(37073/37074)| `Basic.subject`
| `Basic.created`| _Equivalent_<br/>(3144/3145)| `Basic.created`| _Equivalent_<br/>(10432/10433)| `Basic.created`| _Equivalent_<br/>(21998/21999)| **`Basic.created`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37075)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37076)| `Basic.created`
| `Basic.author`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3142)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3143)| `Basic.author`| →→→→ _RelatedTo_ →→→→ <br/>(10434)<hr/>←←←← _RelatedTo_ ←←←← <br/>(10435)| `Basic.author`| _Equivalent_<br/>(22000/22001)| **`Basic.author`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37077)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37078)| `Basic.author`
| *14 of 14 elements used* | | *14 of 14 elements used* | | *14 of 14 elements used* | | *14 of 14 elements used* | | *14 of 14 elements used* 

