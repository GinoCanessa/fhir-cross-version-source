Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:50 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | BodyStructure |  | Record details about an anatomical structure.  This resource may be used when a coded concept does not provide the necessary detail needed for the use case. | 37 | 20 |
| Target | BodyStructure |  | Record details about an anatomical structure.  This resource may be used when a coded concept does not provide the necessary detail needed for the use case. | 17 | 9 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 22 |
Equivalent | 4 |
RelatedTo | 11 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| BodyStructure | BodyStructure | Equivalent | R5 `BodyStructure` maps as Equivalent to R4 `BodyStructure` |
| BodyStructure.active | BodyStructure.active | Equivalent | R5 `BodyStructure.active` maps as Equivalent to R4 `BodyStructure.active` |
| BodyStructure.contained | BodyStructure.contained | Equivalent | R5 `BodyStructure.contained` maps as Equivalent to R4 `BodyStructure.contained` |
| BodyStructure.description | BodyStructure.description | SourceIsBroaderThanTarget | R5 `BodyStructure.description` maps as SourceIsBroaderThanTarget to R4 `BodyStructure.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4 description |
| BodyStructure.excludedStructure | - | DoesNotExistInTarget | R5 `BodyStructure.excludedStructure` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.extension | BodyStructure.extension | SourceIsBroaderThanTarget | R5 `BodyStructure.extension` maps as SourceIsBroaderThanTarget to R4 `BodyStructure.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| BodyStructure.id | BodyStructure.id | Equivalent | R5 `BodyStructure.id` maps as Equivalent to R4 `BodyStructure.id` |
| BodyStructure.identifier | BodyStructure.identifier | Equivalent | R5 `BodyStructure.identifier` maps as Equivalent to R4 `BodyStructure.identifier` |
| BodyStructure.image | BodyStructure.image | RelatedTo | R5 `BodyStructure.image` maps as RelatedTo to R4 `BodyStructure.image` - image has change due to type change: R5 `image` `Attachment` maps as RelatedTo for R4 `image` |
| BodyStructure.implicitRules | BodyStructure.implicitRules | Equivalent | R5 `BodyStructure.implicitRules` maps as Equivalent to R4 `BodyStructure.implicitRules` |
| BodyStructure.includedStructure | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.bodyLandmarkOrientation | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.bodyLandmarkOrientation` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.bodyLandmarkOrientation.clockFacePosition | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.bodyLandmarkOrientation.clockFacePosition` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.device | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.device` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.extension | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.extension` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.id | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.id` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.modifierExtension | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.modifierExtension` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.value | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.bodyLandmarkOrientation.distanceFromLandmark.value` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.bodyLandmarkOrientation.extension | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.bodyLandmarkOrientation.extension` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.bodyLandmarkOrientation.id | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.bodyLandmarkOrientation.id` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.bodyLandmarkOrientation.landmarkDescription | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.bodyLandmarkOrientation.landmarkDescription` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.bodyLandmarkOrientation.modifierExtension | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.bodyLandmarkOrientation.modifierExtension` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.bodyLandmarkOrientation.surfaceOrientation | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.bodyLandmarkOrientation.surfaceOrientation` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.extension | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.extension` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.id | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.id` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.laterality | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.laterality` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.modifierExtension | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.modifierExtension` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.qualifier | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.qualifier` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.spatialReference | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.spatialReference` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.includedStructure.structure | - | DoesNotExistInTarget | R5 `BodyStructure.includedStructure.structure` does not appear in the target and has no mapping for `BodyStructure`. |
| BodyStructure.language | BodyStructure.language | RelatedTo | R5 `BodyStructure.language` maps as RelatedTo to R4 `BodyStructure.language` - language changed the binding strength from Required to Preferred |
| BodyStructure.meta | BodyStructure.meta | Equivalent | R5 `BodyStructure.meta` maps as Equivalent to R4 `BodyStructure.meta` |
| BodyStructure.modifierExtension | BodyStructure.modifierExtension | SourceIsBroaderThanTarget | R5 `BodyStructure.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `BodyStructure.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| BodyStructure.morphology | BodyStructure.morphology | Equivalent | R5 `BodyStructure.morphology` maps as Equivalent to R4 `BodyStructure.morphology` |
| BodyStructure.patient | BodyStructure.patient | Equivalent | R5 `BodyStructure.patient` maps as Equivalent to R4 `BodyStructure.patient` |
| BodyStructure.text | BodyStructure.text | Equivalent | R5 `BodyStructure.text` maps as Equivalent to R4 `BodyStructure.text` |

