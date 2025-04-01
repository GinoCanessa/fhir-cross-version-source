Comparison of 
Generated at Tuesday, April 1, 2025 1:39:37 PM

### BodyStructure

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | BodyStructure |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/BodyStructure` |
| Version | 5.0.0 |
| Description | Record details about an anatomical structure.  This resource may be used when a coded concept does not provide the necessary detail needed for the use case. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2262` |
| Database Snapshot Count | `37` |
| Database Differential Count | `20` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `BodyStructure` | `BodyStructure` | `BodyStructure` | BodyStructure | Specific and identified anatomical structure | 0..* | BodyStructure |  |  |
| `BodyStructure.active` | `BodyStructure.active` | `active` | BodyStructure.active | Whether this record is in active use | 0..1 | boolean |  |  |
| `BodyStructure.contained` | `BodyStructure.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `BodyStructure.description` | `BodyStructure.description` | `description` | BodyStructure.description | Text description | 0..1 | markdown |  |  |
| `BodyStructure.excludedStructure` | `BodyStructure.excludedStructure` | `excludedStructure` | BodyStructure.excludedStructure | Excluded anatomic locations(s) | 0..* | BodyStructure.includedStructure |  |  |
| `BodyStructure.extension` | `BodyStructure.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `BodyStructure.id` | `BodyStructure.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `BodyStructure.identifier` | `BodyStructure.identifier` | `identifier` | BodyStructure.identifier | Bodystructure identifier | 0..* | Identifier |  |  |
| `BodyStructure.image` | `BodyStructure.image` | `image` | BodyStructure.image | Attached images | 0..* | Attachment |  |  |
| `BodyStructure.implicitRules` | `BodyStructure.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `BodyStructure.includedStructure` | `BodyStructure.includedStructure` | `includedStructure` | BodyStructure.includedStructure | Included anatomic location(s) | 1..* | BackboneElement |  |  |
| `BodyStructure.includedStructure.bodyLandmarkOrientation` | `BodyStructure.includedStructure.bodyLandmarkOrientation` | `bodyLandmarkOrientation` | BodyStructure.includedStructure.bodyLandmarkOrientation | Landmark relative location | 0..* | BackboneElement |  |  |
| `BodyStructure.includedStructure.bodyLandmarkOrientation.clockFacePosition` | `BodyStructure.includedStructure.bodyLandmarkOrientation.clockFacePosition` | `clockFacePosition` | BodyStructure.includedStructure.bodyLandmarkOrientation.clockFacePosition | Clockface orientation | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/bodystructure-bodylandmarkorientation-clockface-position` |
| `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark` | `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark` | `distanceFromLandmark` | BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark | Landmark relative location | 0..* | BackboneElement |  |  |
| `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.device` | `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.device` | `device` | BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.device | Measurement device | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/Device) | `Example` | `http://hl7.org/fhir/ValueSet/device-type` |
| `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.extension` | `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.id` | `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.modifierExtension` | `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.value` | `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.value` | `value` | BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.value | Measured distance from body landmark | 0..* | Quantity |  |  |
| `BodyStructure.includedStructure.bodyLandmarkOrientation.extension` | `BodyStructure.includedStructure.bodyLandmarkOrientation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `BodyStructure.includedStructure.bodyLandmarkOrientation.id` | `BodyStructure.includedStructure.bodyLandmarkOrientation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `BodyStructure.includedStructure.bodyLandmarkOrientation.landmarkDescription` | `BodyStructure.includedStructure.bodyLandmarkOrientation.landmarkDescription` | `landmarkDescription` | BodyStructure.includedStructure.bodyLandmarkOrientation.landmarkDescription | Body ]andmark description | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `BodyStructure.includedStructure.bodyLandmarkOrientation.modifierExtension` | `BodyStructure.includedStructure.bodyLandmarkOrientation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `BodyStructure.includedStructure.bodyLandmarkOrientation.surfaceOrientation` | `BodyStructure.includedStructure.bodyLandmarkOrientation.surfaceOrientation` | `surfaceOrientation` | BodyStructure.includedStructure.bodyLandmarkOrientation.surfaceOrientation | Relative landmark surface orientation | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/bodystructure-relative-location` |
| `BodyStructure.includedStructure.extension` | `BodyStructure.includedStructure.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `BodyStructure.includedStructure.id` | `BodyStructure.includedStructure.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `BodyStructure.includedStructure.laterality` | `BodyStructure.includedStructure.laterality` | `laterality` | BodyStructure.includedStructure.laterality | Code that represents the included structure laterality | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/bodystructure-relative-location` |
| `BodyStructure.includedStructure.modifierExtension` | `BodyStructure.includedStructure.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `BodyStructure.includedStructure.qualifier` | `BodyStructure.includedStructure.qualifier` | `qualifier` | BodyStructure.includedStructure.qualifier | Code that represents the included structure qualifier | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/bodystructure-relative-location` |
| `BodyStructure.includedStructure.spatialReference` | `BodyStructure.includedStructure.spatialReference` | `spatialReference` | BodyStructure.includedStructure.spatialReference | Cartesian reference for structure | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ImagingSelection) |  |  |
| `BodyStructure.includedStructure.structure` | `BodyStructure.includedStructure.structure` | `structure` | BodyStructure.includedStructure.structure | Code that represents the included structure | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `BodyStructure.language` | `BodyStructure.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `BodyStructure.meta` | `BodyStructure.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `BodyStructure.modifierExtension` | `BodyStructure.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `BodyStructure.morphology` | `BodyStructure.morphology` | `morphology` | BodyStructure.morphology | Kind of Structure | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/bodystructure-code` |
| `BodyStructure.patient` | `BodyStructure.patient` | `patient` | BodyStructure.patient | Who this is about | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `BodyStructure.text` | `BodyStructure.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [BodySite](/docs/R2/Resources/BodySite.md)<br/> `http://hl7.org/fhir/StructureDefinition/BodySite\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `79`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `245`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BodySite](/docs/R3/Resources/BodySite.md)<br/> `http://hl7.org/fhir/StructureDefinition/BodySite\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `424`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `620`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BodyStructure](/docs/R4/Resources/BodyStructure.md)<br/> `http://hl7.org/fhir/StructureDefinition/BodyStructure\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1407`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1408`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BodyStructure](/docs/R4B/Resources/BodyStructure.md)<br/> `http://hl7.org/fhir/StructureDefinition/BodyStructure\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `938`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1167`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BodyStructure](/docs/R5/Resources/BodyStructure.md)<br/> `http://hl7.org/fhir/StructureDefinition/BodyStructure\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition BodyStructure from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 BodySite](/docs/R2/Resources/BodySite.md)| Relationship | [R3 BodySite](/docs/R3/Resources/BodySite.md)| Relationship | [R4 BodyStructure](/docs/R4/Resources/BodyStructure.md)| Relationship | [R4B BodyStructure](/docs/R4B/Resources/BodyStructure.md)| Relationship | R5 BodyStructure
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `BodyStructure`| _Equivalent_<br/>(22123/22124)| `BodyStructure`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37161)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37162)| **`BodyStructure`**
| | | | | `BodyStructure.id`| _Equivalent_<br/>(22125/22126)| `BodyStructure.id`| _Equivalent_<br/>(37163/37164)| **`BodyStructure.id`**
| | | | | `BodyStructure.meta`| _Equivalent_<br/>(22127/22128)| `BodyStructure.meta`| _Equivalent_<br/>(37165/37166)| **`BodyStructure.meta`**
| | | | | `BodyStructure.implicitRules`| _Equivalent_<br/>(22129/22130)| `BodyStructure.implicitRules`| _Equivalent_<br/>(37167/37168)| **`BodyStructure.implicitRules`**
| | | | | `BodyStructure.language`| _Equivalent_<br/>(22131/22132)| `BodyStructure.language`| _Equivalent_<br/>(37169/37170)| **`BodyStructure.language`**
| | | | | `BodyStructure.text`| _Equivalent_<br/>(22133/22134)| `BodyStructure.text`| _Equivalent_<br/>(37171/37172)| **`BodyStructure.text`**
| | | | | `BodyStructure.contained`| _Equivalent_<br/>(22135/22136)| `BodyStructure.contained`| _Equivalent_<br/>(37173/37174)| **`BodyStructure.contained`**
| | | | | `BodyStructure.extension`| _Equivalent_<br/>(22137/22138)| `BodyStructure.extension`| _Equivalent_<br/>(37175/37176)| **`BodyStructure.extension`**
| | | | | `BodyStructure.modifierExtension`| _Equivalent_<br/>(22139/22140)| `BodyStructure.modifierExtension`| _Equivalent_<br/>(37177/37178)| **`BodyStructure.modifierExtension`**
| | | | | `BodyStructure.identifier`| _Equivalent_<br/>(22141/22142)| `BodyStructure.identifier`| _Equivalent_<br/>(37179/37180)| **`BodyStructure.identifier`**
| | | | | `BodyStructure.active`| _Equivalent_<br/>(22143/22144)| `BodyStructure.active`| _Equivalent_<br/>(37181/37182)| **`BodyStructure.active`**
| | | | | `BodyStructure.morphology`| _Equivalent_<br/>(22145/22146)| `BodyStructure.morphology`| _Equivalent_<br/>(37183/37184)| **`BodyStructure.morphology`**
| | | | | | | | | **`BodyStructure.includedStructure`**
| | | | | | | | | **`BodyStructure.includedStructure.id`**
| | | | | | | | | **`BodyStructure.includedStructure.extension`**
| | | | | | | | | **`BodyStructure.includedStructure.modifierExtension`**
| | | | | | | | | **`BodyStructure.includedStructure.structure`**
| | | | | | | | | **`BodyStructure.includedStructure.laterality`**
| | | | | | | | | **`BodyStructure.includedStructure.bodyLandmarkOrientation`**
| | | | | | | | | **`BodyStructure.includedStructure.bodyLandmarkOrientation.id`**
| | | | | | | | | **`BodyStructure.includedStructure.bodyLandmarkOrientation.extension`**
| | | | | | | | | **`BodyStructure.includedStructure.bodyLandmarkOrientation.modifierExtension`**
| | | | | | | | | **`BodyStructure.includedStructure.bodyLandmarkOrientation.landmarkDescription`**
| | | | | | | | | **`BodyStructure.includedStructure.bodyLandmarkOrientation.clockFacePosition`**
| | | | | | | | | **`BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark`**
| | | | | | | | | **`BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.id`**
| | | | | | | | | **`BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.extension`**
| | | | | | | | | **`BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.modifierExtension`**
| | | | | | | | | **`BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.device`**
| | | | | | | | | **`BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.value`**
| | | | | | | | | **`BodyStructure.includedStructure.bodyLandmarkOrientation.surfaceOrientation`**
| | | | | | | | | **`BodyStructure.includedStructure.spatialReference`**
| | | | | | | | | **`BodyStructure.includedStructure.qualifier`**
| | | | | | | | | **`BodyStructure.excludedStructure`**
| | | | | `BodyStructure.description`| _Equivalent_<br/>(22151/22152)| `BodyStructure.description`| _Equivalent_<br/>(37187/37188)| **`BodyStructure.description`**
| | | | | `BodyStructure.image`| _Equivalent_<br/>(22153/22154)| `BodyStructure.image`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37189)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37190)| **`BodyStructure.image`**
| | | | | `BodyStructure.patient`| _Equivalent_<br/>(22155/22156)| `BodyStructure.patient`| _Equivalent_<br/>(37191/37192)| **`BodyStructure.patient`**
| *0 of 15 elements used* | | *0 of 16 elements used* | | *15 of 17 elements used* | | *15 of 17 elements used* | | *37 of 37 elements used* 

