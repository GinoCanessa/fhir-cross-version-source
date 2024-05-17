Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | BodyStructure |  | Record details about an anatomical structure.  This resource may be used when a coded concept does not provide the necessary detail needed for the use case. | 17 | 9 |
| Target | BodyStructure |  | Record details about an anatomical structure.  This resource may be used when a coded concept does not provide the necessary detail needed for the use case. | 37 | 20 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 11 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| BodyStructure | BodyStructure | Equivalent | R4B `BodyStructure` maps as Equivalent to R5 `BodyStructure` |
| BodyStructure.active | BodyStructure.active | Equivalent | R4B `BodyStructure.active` maps as Equivalent to R5 `BodyStructure.active` |
| BodyStructure.contained | BodyStructure.contained | Equivalent | R4B `BodyStructure.contained` maps as Equivalent to R5 `BodyStructure.contained` |
| BodyStructure.description | BodyStructure.description | SourceIsBroaderThanTarget | R4B `BodyStructure.description` maps as SourceIsBroaderThanTarget to R5 `BodyStructure.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| BodyStructure.extension | BodyStructure.extension | RelatedTo | R4B `BodyStructure.extension` maps as RelatedTo to R5 `BodyStructure.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| BodyStructure.id | BodyStructure.id | Equivalent | R4B `BodyStructure.id` maps as Equivalent to R5 `BodyStructure.id` |
| BodyStructure.identifier | BodyStructure.identifier | Equivalent | R4B `BodyStructure.identifier` maps as Equivalent to R5 `BodyStructure.identifier` |
| BodyStructure.image | BodyStructure.image | RelatedTo | R4B `BodyStructure.image` maps as RelatedTo to R5 `BodyStructure.image` - image has change due to type change: R4B `image` `Attachment` maps as RelatedTo for R5 `image` |
| BodyStructure.implicitRules | BodyStructure.implicitRules | Equivalent | R4B `BodyStructure.implicitRules` maps as Equivalent to R5 `BodyStructure.implicitRules` |
| BodyStructure.language | BodyStructure.language | RelatedTo | R4B `BodyStructure.language` maps as RelatedTo to R5 `BodyStructure.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| BodyStructure.location | - | DoesNotExistInTarget | R4B `BodyStructure.location` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.locationQualifier | - | DoesNotExistInTarget | R4B `BodyStructure.locationQualifier` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.meta | BodyStructure.meta | Equivalent | R4B `BodyStructure.meta` maps as Equivalent to R5 `BodyStructure.meta` |
| BodyStructure.modifierExtension | BodyStructure.modifierExtension | RelatedTo | R4B `BodyStructure.modifierExtension` maps as RelatedTo to R5 `BodyStructure.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| BodyStructure.morphology | BodyStructure.morphology | Equivalent | R4B `BodyStructure.morphology` maps as Equivalent to R5 `BodyStructure.morphology` |
| BodyStructure.patient | BodyStructure.patient | Equivalent | R4B `BodyStructure.patient` maps as Equivalent to R5 `BodyStructure.patient` |
| BodyStructure.text | BodyStructure.text | Equivalent | R4B `BodyStructure.text` maps as Equivalent to R5 `BodyStructure.text` |

