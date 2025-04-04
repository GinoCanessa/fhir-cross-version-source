Comparison of 
Generated at Friday, April 4, 2025 2:58:55 PM

### Resource

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | Resource |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Resource` |
| Version | 4.3.0 |
| Description | This is the base resource type for everything. |
| Status | `Active` |
| Artifact Class | `Resource` |
| Database Key | `1757` |
| Database Snapshot Count | `5` |
| Database Differential Count | `5` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Resource` | `Resource` | `Resource` | Resource | Base Resource | 0..* | Resource |  |  |
| `Resource.id` | `Resource.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Resource.implicitRules` | `Resource.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Resource.language` | `Resource.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `Resource.meta` | `Resource.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Resource](/docs/R2/Resources/Resource.md)<br/> `http://hl7.org/fhir/StructureDefinition/Resource\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1297`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1298`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Resource](/docs/R3/Resources/Resource.md)<br/> `http://hl7.org/fhir/StructureDefinition/Resource\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1305`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1306`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Resource](/docs/R4/Resources/Resource.md)<br/> `http://hl7.org/fhir/StructureDefinition/Resource\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1605`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1606`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Resource](/docs/R4B/Resources/Resource.md)<br/> `http://hl7.org/fhir/StructureDefinition/Resource\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1657`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1658`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Resource](/docs/R5/Resources/Resource.md)<br/> `http://hl7.org/fhir/StructureDefinition/Resource\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Resource from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Resource](/docs/R2/Resources/Resource.md)| Relationship | [R3 Resource](/docs/R3/Resources/Resource.md)| Relationship | [R4 Resource](/docs/R4/Resources/Resource.md)| Relationship | R4B Resource| Relationship | [R5 Resource](/docs/R5/Resources/Resource.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Resource`| _Equivalent_<br/>(7647/7648)| `Resource`| _Equivalent_<br/>(18140/18141)| `Resource`| _Equivalent_<br/>(32780/32781)| **`Resource`**| _Equivalent_<br/>(47108/47109)| `Resource`
| `Resource.id`| _Equivalent_<br/>(7649/7650)| `Resource.id`| _Equivalent_<br/>(18142/18143)| `Resource.id`| _Equivalent_<br/>(32782/32783)| **`Resource.id`**| _Equivalent_<br/>(47110/47111)| `Resource.id`
| `Resource.meta`| _Equivalent_<br/>(7651/7652)| `Resource.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18144)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18145)| `Resource.meta`| _Equivalent_<br/>(32784/32785)| **`Resource.meta`**| _Equivalent_<br/>(47112/47113)| `Resource.meta`
| `Resource.implicitRules`| _Equivalent_<br/>(7653/7654)| `Resource.implicitRules`| _Equivalent_<br/>(18146/18147)| `Resource.implicitRules`| _Equivalent_<br/>(32786/32787)| **`Resource.implicitRules`**| _Equivalent_<br/>(47114/47115)| `Resource.implicitRules`
| `Resource.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7655)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7656)| `Resource.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18148)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18149)| `Resource.language`| _Equivalent_<br/>(32788/32789)| **`Resource.language`**| _Equivalent_<br/>(47116/47117)| `Resource.language`
| *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* 

