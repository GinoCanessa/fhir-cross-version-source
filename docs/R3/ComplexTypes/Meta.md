Comparison of 
Generated at Thursday, April 3, 2025 8:18:11 AM

### Meta

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Meta |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Meta` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Meta Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `460` |
| Database Snapshot Count | `8` |
| Database Differential Count | `6` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Meta` | `Meta` | `Meta` | Meta | Metadata about a resource | 0..* | Meta |  |  |
| `Meta.extension` | `Meta.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Meta.id` | `Meta.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Meta.lastUpdated` | `Meta.lastUpdated` | `lastUpdated` |  | When the resource version last changed | 0..1 | instant |  |  |
| `Meta.profile` | `Meta.profile` | `profile` |  | Profiles this resource claims to conform to | 0..* | uri |  |  |
| `Meta.security` | `Meta.security` | `security` |  | Security Labels applied to this resource | 0..* | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/security-labels` |
| `Meta.tag` | `Meta.tag` | `tag` |  | Tags applied to this resource | 0..* | Coding | `Example` | `http://hl7.org/fhir/ValueSet/common-tags` |
| `Meta.versionId` | `Meta.versionId` | `versionId` |  | Version specific identifier | 0..1 | id |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Meta](/docs/R2/ComplexTypes/Meta.md)<br/> `http://hl7.org/fhir/StructureDefinition/Meta\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `57`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `227`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Meta](/docs/R3/ComplexTypes/Meta.md)<br/> `http://hl7.org/fhir/StructureDefinition/Meta\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `400`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `596`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Meta](/docs/R4/ComplexTypes/Meta.md)<br/> `http://hl7.org/fhir/StructureDefinition/Meta\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1351`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1352`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Meta](/docs/R4B/ComplexTypes/Meta.md)<br/> `http://hl7.org/fhir/StructureDefinition/Meta\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `909`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1138`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Meta](/docs/R5/ComplexTypes/Meta.md)<br/> `http://hl7.org/fhir/StructureDefinition/Meta\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Meta from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Meta](/docs/R2/ComplexTypes/Meta.md)| Relationship | R3 Meta| Relationship | [R4 Meta](/docs/R4/ComplexTypes/Meta.md)| Relationship | [R4B Meta](/docs/R4B/ComplexTypes/Meta.md)| Relationship | [R5 Meta](/docs/R5/ComplexTypes/Meta.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Meta`| _Equivalent_<br/>(2703/2704)| **`Meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9636)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9637)| `Meta`| _Equivalent_<br/>(21046/21047)| `Meta`| _Equivalent_<br/>(36156/36157)| `Meta`
| `Meta.id`| _Equivalent_<br/>(2705/2706)| **`Meta.id`**| _Equivalent_<br/>(9638/9639)| `Meta.id`| _Equivalent_<br/>(21048/21049)| `Meta.id`| _Equivalent_<br/>(36158/36159)| `Meta.id`
| `Meta.extension`| _Equivalent_<br/>(2707/2708)| **`Meta.extension`**| _Equivalent_<br/>(9640/9641)| `Meta.extension`| _Equivalent_<br/>(21050/21051)| `Meta.extension`| _Equivalent_<br/>(36160/36161)| `Meta.extension`
| `Meta.versionId`| _Equivalent_<br/>(2709/2710)| **`Meta.versionId`**| _Equivalent_<br/>(9642/9643)| `Meta.versionId`| _Equivalent_<br/>(21052/21053)| `Meta.versionId`| _Equivalent_<br/>(36162/36163)| `Meta.versionId`
| `Meta.lastUpdated`| _Equivalent_<br/>(2711/2712)| **`Meta.lastUpdated`**| _Equivalent_<br/>(9644/9645)| `Meta.lastUpdated`| _Equivalent_<br/>(21054/21055)| `Meta.lastUpdated`| _Equivalent_<br/>(36164/36165)| `Meta.lastUpdated`
| `Meta.profile`| _Equivalent_<br/>(2713/2714)| **`Meta.profile`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9646)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9647)| `Meta.profile`| _Equivalent_<br/>(21058/21059)| `Meta.profile`| _Equivalent_<br/>(36168/36169)| `Meta.profile`
| `Meta.security`| _Equivalent_<br/>(2715/2716)| **`Meta.security`**| _Equivalent_<br/>(9648/9649)| `Meta.security`| _Equivalent_<br/>(21060/21061)| `Meta.security`| _Equivalent_<br/>(36170/36171)| `Meta.security`
| `Meta.tag`| _Equivalent_<br/>(2717/2718)| **`Meta.tag`**| _Equivalent_<br/>(9650/9651)| `Meta.tag`| _Equivalent_<br/>(21062/21063)| `Meta.tag`| _Equivalent_<br/>(36172/36173)| `Meta.tag`
| *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 9 elements used* <br/>remaining elements:<br/>`Meta.source`| | *8 of 9 elements used* <br/>remaining elements:<br/>`Meta.source`| | *8 of 9 elements used* <br/>remaining elements:<br/>`Meta.source`

