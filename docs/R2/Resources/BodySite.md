Comparison of 
Generated at Tuesday, April 1, 2025 1:39:08 PM

### BodySite

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | BodySite |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/BodySite` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for BodySite Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `48` |
| Database Snapshot Count | `15` |
| Database Differential Count | `7` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `BodySite` | `BodySite` | `BodySite` | BodySite | Specific and identified anatomical location | 0..* | BodySite |  |  |
| `BodySite.code` | `BodySite.code` | `code` |  | Named anatomical location | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `BodySite.contained` | `BodySite.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `BodySite.description` | `BodySite.description` | `description` |  | The Description of anatomical location | 0..1 | string |  |  |
| `BodySite.extension` | `BodySite.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `BodySite.id` | `BodySite.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `BodySite.identifier` | `BodySite.identifier` | `identifier` |  | Bodysite identifier | 0..* | Identifier |  |  |
| `BodySite.image` | `BodySite.image` | `image` |  | Attached images | 0..* | Attachment |  |  |
| `BodySite.implicitRules` | `BodySite.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `BodySite.language` | `BodySite.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `BodySite.meta` | `BodySite.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `BodySite.modifier` | `BodySite.modifier` | `modifier` |  | Modification to location code | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/bodysite-relative-location` |
| `BodySite.modifierExtension` | `BodySite.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `BodySite.patient` | `BodySite.patient` | `patient` |  | Patient | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `BodySite.text` | `BodySite.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [BodySite](/docs/R2/Resources/BodySite.md)<br/> `http://hl7.org/fhir/StructureDefinition/BodySite\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `79`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `245`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BodySite](/docs/R3/Resources/BodySite.md)<br/> `http://hl7.org/fhir/StructureDefinition/BodySite\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `424`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `620`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BodyStructure](/docs/R4/Resources/BodyStructure.md)<br/> `http://hl7.org/fhir/StructureDefinition/BodyStructure\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1407`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1408`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BodyStructure](/docs/R4B/Resources/BodyStructure.md)<br/> `http://hl7.org/fhir/StructureDefinition/BodyStructure\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `938`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1167`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BodyStructure](/docs/R5/Resources/BodyStructure.md)<br/> `http://hl7.org/fhir/StructureDefinition/BodyStructure\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition BodySite from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 BodySite| Relationship | [R3 BodySite](/docs/R3/Resources/BodySite.md)| Relationship | [R4 BodyStructure](/docs/R4/Resources/BodyStructure.md)| Relationship | [R4B BodyStructure](/docs/R4B/Resources/BodyStructure.md)| Relationship | [R5 BodyStructure](/docs/R5/Resources/BodyStructure.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`BodySite`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3160)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3161)| `BodySite`| | | | | | | 
| **`BodySite.id`**| _Equivalent_<br/>(3162/3163)| `BodySite.id`| | | | | | | 
| **`BodySite.meta`**| _Equivalent_<br/>(3164/3165)| `BodySite.meta`| | | | | | | 
| **`BodySite.implicitRules`**| _Equivalent_<br/>(3166/3167)| `BodySite.implicitRules`| | | | | | | 
| **`BodySite.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3168)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3169)| `BodySite.language`| | | | | | | 
| **`BodySite.text`**| _Equivalent_<br/>(3170/3171)| `BodySite.text`| | | | | | | 
| **`BodySite.contained`**| _Equivalent_<br/>(3172/3173)| `BodySite.contained`| | | | | | | 
| **`BodySite.extension`**| _Equivalent_<br/>(3174/3175)| `BodySite.extension`| | | | | | | 
| **`BodySite.modifierExtension`**| _Equivalent_<br/>(3176/3177)| `BodySite.modifierExtension`| | | | | | | 
| **`BodySite.patient`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3178)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3179)| `BodySite.patient`| | | | | | | 
| **`BodySite.identifier`**| _Equivalent_<br/>(3180/3181)| `BodySite.identifier`| | | | | | | 
| **`BodySite.code`**| _Equivalent_<br/>(3182/3183)| `BodySite.code`| _Equivalent_<br/>(821/1359)| `BodyStructure.location`| _Equivalent_<br/>(22147/22148)| `BodyStructure.location`| | | 
| **`BodySite.modifier`**| _Equivalent_<br/>(48/503)| `BodySite.qualifier`| _Equivalent_<br/>(822/1360)| `BodyStructure.locationQualifier`| _Equivalent_<br/>(22149/22150)| `BodyStructure.locationQualifier`| | | 
| **`BodySite.description`**| _Equivalent_<br/>(3184/3185)| `BodySite.description`| | | | | | | 
| **`BodySite.image`**| _Equivalent_<br/>(3186/3187)| `BodySite.image`| | | | | | | 
| *15 of 15 elements used* | | *15 of 16 elements used* | | *2 of 17 elements used* | | *2 of 17 elements used* | | *0 of 37 elements used* 

