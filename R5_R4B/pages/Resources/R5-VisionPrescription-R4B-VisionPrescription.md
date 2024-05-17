Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | VisionPrescription |  | An authorization for the provision of glasses and/or contact lenses to a patient. | 39 | 25 |
| Target | VisionPrescription |  | An authorization for the provision of glasses and/or contact lenses to a patient. | 39 | 25 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 35 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| VisionPrescription | VisionPrescription | Equivalent | R5 `VisionPrescription` maps as Equivalent to R4B `VisionPrescription` |
| VisionPrescription.contained | VisionPrescription.contained | Equivalent | R5 `VisionPrescription.contained` maps as Equivalent to R4B `VisionPrescription.contained` |
| VisionPrescription.created | VisionPrescription.created | Equivalent | R5 `VisionPrescription.created` maps as Equivalent to R4B `VisionPrescription.created` |
| VisionPrescription.dateWritten | VisionPrescription.dateWritten | Equivalent | R5 `VisionPrescription.dateWritten` maps as Equivalent to R4B `VisionPrescription.dateWritten` |
| VisionPrescription.encounter | VisionPrescription.encounter | Equivalent | R5 `VisionPrescription.encounter` maps as Equivalent to R4B `VisionPrescription.encounter` |
| VisionPrescription.extension | VisionPrescription.extension | SourceIsBroaderThanTarget | R5 `VisionPrescription.extension` maps as SourceIsBroaderThanTarget to R4B `VisionPrescription.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| VisionPrescription.id | VisionPrescription.id | Equivalent | R5 `VisionPrescription.id` maps as Equivalent to R4B `VisionPrescription.id` |
| VisionPrescription.identifier | VisionPrescription.identifier | Equivalent | R5 `VisionPrescription.identifier` maps as Equivalent to R4B `VisionPrescription.identifier` |
| VisionPrescription.implicitRules | VisionPrescription.implicitRules | Equivalent | R5 `VisionPrescription.implicitRules` maps as Equivalent to R4B `VisionPrescription.implicitRules` |
| VisionPrescription.language | VisionPrescription.language | RelatedTo | R5 `VisionPrescription.language` maps as RelatedTo to R4B `VisionPrescription.language` - language changed the binding strength from Required to Preferred |
| VisionPrescription.lensSpecification | VisionPrescription.lensSpecification | Equivalent | R5 `VisionPrescription.lensSpecification` maps as Equivalent to R4B `VisionPrescription.lensSpecification` |
| VisionPrescription.lensSpecification.add | VisionPrescription.lensSpecification.add | Equivalent | R5 `VisionPrescription.lensSpecification.add` maps as Equivalent to R4B `VisionPrescription.lensSpecification.add` |
| VisionPrescription.lensSpecification.axis | VisionPrescription.lensSpecification.axis | Equivalent | R5 `VisionPrescription.lensSpecification.axis` maps as Equivalent to R4B `VisionPrescription.lensSpecification.axis` |
| VisionPrescription.lensSpecification.backCurve | VisionPrescription.lensSpecification.backCurve | Equivalent | R5 `VisionPrescription.lensSpecification.backCurve` maps as Equivalent to R4B `VisionPrescription.lensSpecification.backCurve` |
| VisionPrescription.lensSpecification.brand | VisionPrescription.lensSpecification.brand | Equivalent | R5 `VisionPrescription.lensSpecification.brand` maps as Equivalent to R4B `VisionPrescription.lensSpecification.brand` |
| VisionPrescription.lensSpecification.color | VisionPrescription.lensSpecification.color | Equivalent | R5 `VisionPrescription.lensSpecification.color` maps as Equivalent to R4B `VisionPrescription.lensSpecification.color` |
| VisionPrescription.lensSpecification.cylinder | VisionPrescription.lensSpecification.cylinder | Equivalent | R5 `VisionPrescription.lensSpecification.cylinder` maps as Equivalent to R4B `VisionPrescription.lensSpecification.cylinder` |
| VisionPrescription.lensSpecification.diameter | VisionPrescription.lensSpecification.diameter | Equivalent | R5 `VisionPrescription.lensSpecification.diameter` maps as Equivalent to R4B `VisionPrescription.lensSpecification.diameter` |
| VisionPrescription.lensSpecification.duration | VisionPrescription.lensSpecification.duration | Equivalent | R5 `VisionPrescription.lensSpecification.duration` maps as Equivalent to R4B `VisionPrescription.lensSpecification.duration` |
| VisionPrescription.lensSpecification.extension | VisionPrescription.lensSpecification.extension | SourceIsBroaderThanTarget | R5 `VisionPrescription.lensSpecification.extension` maps as SourceIsBroaderThanTarget to R4B `VisionPrescription.lensSpecification.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| VisionPrescription.lensSpecification.eye | VisionPrescription.lensSpecification.eye | Equivalent | R5 `VisionPrescription.lensSpecification.eye` maps as Equivalent to R4B `VisionPrescription.lensSpecification.eye` - eye has compatible required binding for code type: http://hl7.org/fhir/ValueSet/vision-eye-codes|5.0.0 and http://hl7.org/fhir/ValueSet/vision-eye-codes|4.3.0 (Equivalent) |
| VisionPrescription.lensSpecification.id | VisionPrescription.lensSpecification.id | Equivalent | R5 `VisionPrescription.lensSpecification.id` maps as Equivalent to R4B `VisionPrescription.lensSpecification.id` |
| VisionPrescription.lensSpecification.modifierExtension | VisionPrescription.lensSpecification.modifierExtension | SourceIsBroaderThanTarget | R5 `VisionPrescription.lensSpecification.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `VisionPrescription.lensSpecification.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| VisionPrescription.lensSpecification.note | VisionPrescription.lensSpecification.note | SourceIsBroaderThanTarget | R5 `VisionPrescription.lensSpecification.note` maps as SourceIsBroaderThanTarget to R4B `VisionPrescription.lensSpecification.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| VisionPrescription.lensSpecification.power | VisionPrescription.lensSpecification.power | Equivalent | R5 `VisionPrescription.lensSpecification.power` maps as Equivalent to R4B `VisionPrescription.lensSpecification.power` |
| VisionPrescription.lensSpecification.prism | VisionPrescription.lensSpecification.prism | Equivalent | R5 `VisionPrescription.lensSpecification.prism` maps as Equivalent to R4B `VisionPrescription.lensSpecification.prism` |
| VisionPrescription.lensSpecification.prism.amount | VisionPrescription.lensSpecification.prism.amount | Equivalent | R5 `VisionPrescription.lensSpecification.prism.amount` maps as Equivalent to R4B `VisionPrescription.lensSpecification.prism.amount` |
| VisionPrescription.lensSpecification.prism.base | VisionPrescription.lensSpecification.prism.base | Equivalent | R5 `VisionPrescription.lensSpecification.prism.base` maps as Equivalent to R4B `VisionPrescription.lensSpecification.prism.base` - base has compatible required binding for code type: http://hl7.org/fhir/ValueSet/vision-base-codes|5.0.0 and http://hl7.org/fhir/ValueSet/vision-base-codes|4.3.0 (Equivalent) |
| VisionPrescription.lensSpecification.prism.extension | VisionPrescription.lensSpecification.prism.extension | SourceIsBroaderThanTarget | R5 `VisionPrescription.lensSpecification.prism.extension` maps as SourceIsBroaderThanTarget to R4B `VisionPrescription.lensSpecification.prism.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| VisionPrescription.lensSpecification.prism.id | VisionPrescription.lensSpecification.prism.id | Equivalent | R5 `VisionPrescription.lensSpecification.prism.id` maps as Equivalent to R4B `VisionPrescription.lensSpecification.prism.id` |
| VisionPrescription.lensSpecification.prism.modifierExtension | VisionPrescription.lensSpecification.prism.modifierExtension | SourceIsBroaderThanTarget | R5 `VisionPrescription.lensSpecification.prism.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `VisionPrescription.lensSpecification.prism.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| VisionPrescription.lensSpecification.product | VisionPrescription.lensSpecification.product | Equivalent | R5 `VisionPrescription.lensSpecification.product` maps as Equivalent to R4B `VisionPrescription.lensSpecification.product` |
| VisionPrescription.lensSpecification.sphere | VisionPrescription.lensSpecification.sphere | Equivalent | R5 `VisionPrescription.lensSpecification.sphere` maps as Equivalent to R4B `VisionPrescription.lensSpecification.sphere` |
| VisionPrescription.meta | VisionPrescription.meta | Equivalent | R5 `VisionPrescription.meta` maps as Equivalent to R4B `VisionPrescription.meta` |
| VisionPrescription.modifierExtension | VisionPrescription.modifierExtension | SourceIsBroaderThanTarget | R5 `VisionPrescription.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `VisionPrescription.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| VisionPrescription.patient | VisionPrescription.patient | Equivalent | R5 `VisionPrescription.patient` maps as Equivalent to R4B `VisionPrescription.patient` |
| VisionPrescription.prescriber | VisionPrescription.prescriber | Equivalent | R5 `VisionPrescription.prescriber` maps as Equivalent to R4B `VisionPrescription.prescriber` |
| VisionPrescription.status | VisionPrescription.status | Equivalent | R5 `VisionPrescription.status` maps as Equivalent to R4B `VisionPrescription.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|5.0.0 and http://hl7.org/fhir/ValueSet/fm-status|4.3.0 (Equivalent) |
| VisionPrescription.text | VisionPrescription.text | Equivalent | R5 `VisionPrescription.text` maps as Equivalent to R4B `VisionPrescription.text` |

