Comparison of 
Generated at Thursday, April 3, 2025 8:18:11 AM

### BodySite

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | BodySite |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/BodySite` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for BodySite Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `484` |
| Database Snapshot Count | `16` |
| Database Differential Count | `8` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `BodySite` | `BodySite` | `BodySite` | BodySite | Specific and identified anatomical location | 0..* | BodySite |  |  |
| `BodySite.active` | `BodySite.active` | `active` |  | Whether this body site record is in active use | 0..1 | boolean |  |  |
| `BodySite.code` | `BodySite.code` | `code` |  | Named anatomical location | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `BodySite.contained` | `BodySite.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `BodySite.description` | `BodySite.description` | `description` |  | Anatomical location description | 0..1 | string |  |  |
| `BodySite.extension` | `BodySite.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `BodySite.id` | `BodySite.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `BodySite.identifier` | `BodySite.identifier` | `identifier` |  | Bodysite identifier | 0..* | Identifier |  |  |
| `BodySite.image` | `BodySite.image` | `image` |  | Attached images | 0..* | Attachment |  |  |
| `BodySite.implicitRules` | `BodySite.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `BodySite.language` | `BodySite.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `BodySite.meta` | `BodySite.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `BodySite.modifierExtension` | `BodySite.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `BodySite.patient` | `BodySite.patient` | `patient` |  | Who this is about | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `BodySite.qualifier` | `BodySite.qualifier` | `qualifier` |  | Modification to location code | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/bodysite-relative-location` |
| `BodySite.text` | `BodySite.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [BodySite](/docs/R2/Resources/BodySite.md)<br/> `http://hl7.org/fhir/StructureDefinition/BodySite\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `79`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `245`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BodySite](/docs/R3/Resources/BodySite.md)<br/> `http://hl7.org/fhir/StructureDefinition/BodySite\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `424`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `620`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BodyStructure](/docs/R4/Resources/BodyStructure.md)<br/> `http://hl7.org/fhir/StructureDefinition/BodyStructure\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1407`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1408`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BodyStructure](/docs/R4B/Resources/BodyStructure.md)<br/> `http://hl7.org/fhir/StructureDefinition/BodyStructure\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `938`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1167`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BodyStructure](/docs/R5/Resources/BodyStructure.md)<br/> `http://hl7.org/fhir/StructureDefinition/BodyStructure\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition BodySite from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 BodySite](/docs/R2/Resources/BodySite.md)| Relationship | R3 BodySite| Relationship | [R4 BodyStructure](/docs/R4/Resources/BodyStructure.md)| Relationship | [R4B BodyStructure](/docs/R4B/Resources/BodyStructure.md)| Relationship | [R5 BodyStructure](/docs/R5/Resources/BodyStructure.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `BodySite`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3160)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3161)| **`BodySite`**| | | | | | | 
| `BodySite.id`| _Equivalent_<br/>(3162/3163)| **`BodySite.id`**| | | | | | | 
| `BodySite.meta`| _Equivalent_<br/>(3164/3165)| **`BodySite.meta`**| | | | | | | 
| `BodySite.implicitRules`| _Equivalent_<br/>(3166/3167)| **`BodySite.implicitRules`**| | | | | | | 
| `BodySite.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3168)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3169)| **`BodySite.language`**| | | | | | | 
| `BodySite.text`| _Equivalent_<br/>(3170/3171)| **`BodySite.text`**| | | | | | | 
| `BodySite.contained`| _Equivalent_<br/>(3172/3173)| **`BodySite.contained`**| | | | | | | 
| `BodySite.extension`| _Equivalent_<br/>(3174/3175)| **`BodySite.extension`**| | | | | | | 
| `BodySite.modifierExtension`| _Equivalent_<br/>(3176/3177)| **`BodySite.modifierExtension`**| | | | | | | 
| `BodySite.identifier`| _Equivalent_<br/>(3180/3181)| **`BodySite.identifier`**| | | | | | | 
| | | **`BodySite.active`**| | | | | | | 
| `BodySite.code`| _Equivalent_<br/>(3182/3183)| **`BodySite.code`**| _Equivalent_<br/>(821/1359)| `BodyStructure.location`| _Equivalent_<br/>(22147/22148)| `BodyStructure.location`| | | 
| `BodySite.modifier`| _Equivalent_<br/>(48/503)| **`BodySite.qualifier`**| _Equivalent_<br/>(822/1360)| `BodyStructure.locationQualifier`| _Equivalent_<br/>(22149/22150)| `BodyStructure.locationQualifier`| | | 
| `BodySite.description`| _Equivalent_<br/>(3184/3185)| **`BodySite.description`**| | | | | | | 
| `BodySite.image`| _Equivalent_<br/>(3186/3187)| **`BodySite.image`**| | | | | | | 
| `BodySite.patient`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3178)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3179)| **`BodySite.patient`**| | | | | | | 
| *15 of 15 elements used* | | *16 of 16 elements used* | | *2 of 17 elements used* <br/>remaining elements:<br/>`BodyStructure`, `BodyStructure.active`, `BodyStructure.contained`, `BodyStructure.description`, `BodyStructure.extension`, `BodyStructure.id`, `BodyStructure.identifier`, `BodyStructure.image`, `BodyStructure.implicitRules`, `BodyStructure.language`, `BodyStructure.meta`, `BodyStructure.modifierExtension`, `BodyStructure.morphology`, `BodyStructure.patient`, `BodyStructure.text`| | *2 of 17 elements used* <br/>remaining elements:<br/>`BodyStructure`, `BodyStructure.active`, `BodyStructure.contained`, `BodyStructure.description`, `BodyStructure.extension`, `BodyStructure.id`, `BodyStructure.identifier`, `BodyStructure.image`, `BodyStructure.implicitRules`, `BodyStructure.language`, `BodyStructure.meta`, `BodyStructure.modifierExtension`, `BodyStructure.morphology`, `BodyStructure.patient`, `BodyStructure.text`| | *0 of 37 elements used* <br/>remaining elements:<br/>`BodyStructure`, `BodyStructure.active`, `BodyStructure.contained`, `BodyStructure.description`, `BodyStructure.excludedStructure`, `BodyStructure.extension`, `BodyStructure.id`, `BodyStructure.identifier`, `BodyStructure.image`, `BodyStructure.implicitRules`, `BodyStructure.includedStructure`, `BodyStructure.includedStructure.bodyLandmarkOrientation`, `BodyStructure.includedStructure.bodyLandmarkOrientation.clockFacePosition`, `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark`, `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.device`, `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.extension`, `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.id`, `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.modifierExtension`, `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.value`, `BodyStructure.includedStructure.bodyLandmarkOrientation.extension`, `BodyStructure.includedStructure.bodyLandmarkOrientation.id`, `BodyStructure.includedStructure.bodyLandmarkOrientation.landmarkDescription`, `BodyStructure.includedStructure.bodyLandmarkOrientation.modifierExtension`, `BodyStructure.includedStructure.bodyLandmarkOrientation.surfaceOrientation`, `BodyStructure.includedStructure.extension`, `BodyStructure.includedStructure.id`, `BodyStructure.includedStructure.laterality`, `BodyStructure.includedStructure.modifierExtension`, `BodyStructure.includedStructure.qualifier`, `BodyStructure.includedStructure.spatialReference`, `BodyStructure.includedStructure.structure`, `BodyStructure.language`, `BodyStructure.meta`, `BodyStructure.modifierExtension`, `BodyStructure.morphology`, `BodyStructure.patient`, `BodyStructure.text`

