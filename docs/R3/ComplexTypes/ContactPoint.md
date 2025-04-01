Comparison of 
Generated at Tuesday, April 1, 2025 1:39:12 PM

### ContactPoint

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | ContactPoint |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ContactPoint` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for ContactPoint Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `448` |
| Database Snapshot Count | `8` |
| Database Differential Count | `6` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ContactPoint` | `ContactPoint` | `ContactPoint` | ContactPoint | Details of a Technology mediated contact point (phone, fax, email, etc.) | 0..* | ContactPoint |  |  |
| `ContactPoint.extension` | `ContactPoint.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ContactPoint.id` | `ContactPoint.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ContactPoint.period` | `ContactPoint.period` | `period` |  | Time period when the contact point was/is in use | 0..1 | Period |  |  |
| `ContactPoint.rank` | `ContactPoint.rank` | `rank` |  | Specify preferred order of use (1 = highest) | 0..1 | positiveInt |  |  |
| `ContactPoint.system` | `ContactPoint.system` | `system` |  | phone \| fax \| email \| pager \| url \| sms \| other | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/contact-point-system` |
| `ContactPoint.use` | `ContactPoint.use` | `use` |  | home \| work \| temp \| old \| mobile - purpose of this contact point | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/contact-point-use` |
| `ContactPoint.value` | `ContactPoint.value` | `value` |  | The actual contact point details | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ContactPoint](/docs/R2/ComplexTypes/ContactPoint.md)<br/> `http://hl7.org/fhir/StructureDefinition/ContactPoint\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `52`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `219`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ContactPoint](/docs/R3/ComplexTypes/ContactPoint.md)<br/> `http://hl7.org/fhir/StructureDefinition/ContactPoint\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `389`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `585`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ContactPoint](/docs/R4/ComplexTypes/ContactPoint.md)<br/> `http://hl7.org/fhir/StructureDefinition/ContactPoint\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1323`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1324`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ContactPoint](/docs/R4B/ComplexTypes/ContactPoint.md)<br/> `http://hl7.org/fhir/StructureDefinition/ContactPoint\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `897`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1126`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ContactPoint](/docs/R5/ComplexTypes/ContactPoint.md)<br/> `http://hl7.org/fhir/StructureDefinition/ContactPoint\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ContactPoint from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 ContactPoint](/docs/R2/ComplexTypes/ContactPoint.md)| Relationship | R3 ContactPoint| Relationship | [R4 ContactPoint](/docs/R4/ComplexTypes/ContactPoint.md)| Relationship | [R4B ContactPoint](/docs/R4B/ComplexTypes/ContactPoint.md)| Relationship | [R5 ContactPoint](/docs/R5/ComplexTypes/ContactPoint.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `ContactPoint`| _Equivalent_<br/>(2509/2510)| **`ContactPoint`**| _Equivalent_<br/>(9248/9249)| `ContactPoint`| _Equivalent_<br/>(20598/20599)| `ContactPoint`| _Equivalent_<br/>(35725/35726)| `ContactPoint`
| `ContactPoint.id`| _Equivalent_<br/>(2511/2512)| **`ContactPoint.id`**| _Equivalent_<br/>(9250/9251)| `ContactPoint.id`| _Equivalent_<br/>(20600/20601)| `ContactPoint.id`| _Equivalent_<br/>(35727/35728)| `ContactPoint.id`
| `ContactPoint.extension`| _Equivalent_<br/>(2513/2514)| **`ContactPoint.extension`**| _Equivalent_<br/>(9252/9253)| `ContactPoint.extension`| _Equivalent_<br/>(20602/20603)| `ContactPoint.extension`| _Equivalent_<br/>(35729/35730)| `ContactPoint.extension`
| `ContactPoint.system`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2515)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2516)| **`ContactPoint.system`**| _Equivalent_<br/>(9254/9255)| `ContactPoint.system`| _Equivalent_<br/>(20604/20605)| `ContactPoint.system`| _Equivalent_<br/>(35731/35732)| `ContactPoint.system`
| `ContactPoint.value`| _Equivalent_<br/>(2517/2518)| **`ContactPoint.value`**| _Equivalent_<br/>(9256/9257)| `ContactPoint.value`| _Equivalent_<br/>(20606/20607)| `ContactPoint.value`| _Equivalent_<br/>(35733/35734)| `ContactPoint.value`
| `ContactPoint.use`| _Equivalent_<br/>(2519/2520)| **`ContactPoint.use`**| _Equivalent_<br/>(9258/9259)| `ContactPoint.use`| _Equivalent_<br/>(20608/20609)| `ContactPoint.use`| _Equivalent_<br/>(35735/35736)| `ContactPoint.use`
| `ContactPoint.rank`| _Equivalent_<br/>(2521/2522)| **`ContactPoint.rank`**| _Equivalent_<br/>(9260/9261)| `ContactPoint.rank`| _Equivalent_<br/>(20610/20611)| `ContactPoint.rank`| _Equivalent_<br/>(35737/35738)| `ContactPoint.rank`
| `ContactPoint.period`| _Equivalent_<br/>(2523/2524)| **`ContactPoint.period`**| _Equivalent_<br/>(9262/9263)| `ContactPoint.period`| _Equivalent_<br/>(20612/20613)| `ContactPoint.period`| _Equivalent_<br/>(35739/35740)| `ContactPoint.period`
| *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* 

