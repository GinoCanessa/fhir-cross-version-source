Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

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
| VisionPrescription | VisionPrescription | Equivalent | R4B `VisionPrescription` maps as Equivalent to R5 `VisionPrescription` |
| VisionPrescription.contained | VisionPrescription.contained | Equivalent | R4B `VisionPrescription.contained` maps as Equivalent to R5 `VisionPrescription.contained` |
| VisionPrescription.created | VisionPrescription.created | Equivalent | R4B `VisionPrescription.created` maps as Equivalent to R5 `VisionPrescription.created` |
| VisionPrescription.dateWritten | VisionPrescription.dateWritten | Equivalent | R4B `VisionPrescription.dateWritten` maps as Equivalent to R5 `VisionPrescription.dateWritten` |
| VisionPrescription.encounter | VisionPrescription.encounter | Equivalent | R4B `VisionPrescription.encounter` maps as Equivalent to R5 `VisionPrescription.encounter` |
| VisionPrescription.extension | VisionPrescription.extension | RelatedTo | R4B `VisionPrescription.extension` maps as RelatedTo to R5 `VisionPrescription.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| VisionPrescription.id | VisionPrescription.id | Equivalent | R4B `VisionPrescription.id` maps as Equivalent to R5 `VisionPrescription.id` |
| VisionPrescription.identifier | VisionPrescription.identifier | Equivalent | R4B `VisionPrescription.identifier` maps as Equivalent to R5 `VisionPrescription.identifier` |
| VisionPrescription.implicitRules | VisionPrescription.implicitRules | Equivalent | R4B `VisionPrescription.implicitRules` maps as Equivalent to R5 `VisionPrescription.implicitRules` |
| VisionPrescription.language | VisionPrescription.language | RelatedTo | R4B `VisionPrescription.language` maps as RelatedTo to R5 `VisionPrescription.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| VisionPrescription.lensSpecification | VisionPrescription.lensSpecification | Equivalent | R4B `VisionPrescription.lensSpecification` maps as Equivalent to R5 `VisionPrescription.lensSpecification` |
| VisionPrescription.lensSpecification.add | VisionPrescription.lensSpecification.add | Equivalent | R4B `VisionPrescription.lensSpecification.add` maps as Equivalent to R5 `VisionPrescription.lensSpecification.add` |
| VisionPrescription.lensSpecification.axis | VisionPrescription.lensSpecification.axis | Equivalent | R4B `VisionPrescription.lensSpecification.axis` maps as Equivalent to R5 `VisionPrescription.lensSpecification.axis` |
| VisionPrescription.lensSpecification.backCurve | VisionPrescription.lensSpecification.backCurve | Equivalent | R4B `VisionPrescription.lensSpecification.backCurve` maps as Equivalent to R5 `VisionPrescription.lensSpecification.backCurve` |
| VisionPrescription.lensSpecification.brand | VisionPrescription.lensSpecification.brand | Equivalent | R4B `VisionPrescription.lensSpecification.brand` maps as Equivalent to R5 `VisionPrescription.lensSpecification.brand` |
| VisionPrescription.lensSpecification.color | VisionPrescription.lensSpecification.color | Equivalent | R4B `VisionPrescription.lensSpecification.color` maps as Equivalent to R5 `VisionPrescription.lensSpecification.color` |
| VisionPrescription.lensSpecification.cylinder | VisionPrescription.lensSpecification.cylinder | Equivalent | R4B `VisionPrescription.lensSpecification.cylinder` maps as Equivalent to R5 `VisionPrescription.lensSpecification.cylinder` |
| VisionPrescription.lensSpecification.diameter | VisionPrescription.lensSpecification.diameter | Equivalent | R4B `VisionPrescription.lensSpecification.diameter` maps as Equivalent to R5 `VisionPrescription.lensSpecification.diameter` |
| VisionPrescription.lensSpecification.duration | VisionPrescription.lensSpecification.duration | Equivalent | R4B `VisionPrescription.lensSpecification.duration` maps as Equivalent to R5 `VisionPrescription.lensSpecification.duration` |
| VisionPrescription.lensSpecification.extension | VisionPrescription.lensSpecification.extension | RelatedTo | R4B `VisionPrescription.lensSpecification.extension` maps as RelatedTo to R5 `VisionPrescription.lensSpecification.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| VisionPrescription.lensSpecification.eye | VisionPrescription.lensSpecification.eye | Equivalent | R4B `VisionPrescription.lensSpecification.eye` maps as Equivalent to R5 `VisionPrescription.lensSpecification.eye` - eye has compatible required binding for code type: http://hl7.org/fhir/ValueSet/vision-eye-codes|4.3.0 and http://hl7.org/fhir/ValueSet/vision-eye-codes|5.0.0 (Equivalent) |
| VisionPrescription.lensSpecification.id | VisionPrescription.lensSpecification.id | Equivalent | R4B `VisionPrescription.lensSpecification.id` maps as Equivalent to R5 `VisionPrescription.lensSpecification.id` |
| VisionPrescription.lensSpecification.modifierExtension | VisionPrescription.lensSpecification.modifierExtension | RelatedTo | R4B `VisionPrescription.lensSpecification.modifierExtension` maps as RelatedTo to R5 `VisionPrescription.lensSpecification.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| VisionPrescription.lensSpecification.note | VisionPrescription.lensSpecification.note | SourceIsNarrowerThanTarget | R4B `VisionPrescription.lensSpecification.note` maps as SourceIsNarrowerThanTarget to R5 `VisionPrescription.lensSpecification.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| VisionPrescription.lensSpecification.power | VisionPrescription.lensSpecification.power | Equivalent | R4B `VisionPrescription.lensSpecification.power` maps as Equivalent to R5 `VisionPrescription.lensSpecification.power` |
| VisionPrescription.lensSpecification.prism | VisionPrescription.lensSpecification.prism | Equivalent | R4B `VisionPrescription.lensSpecification.prism` maps as Equivalent to R5 `VisionPrescription.lensSpecification.prism` |
| VisionPrescription.lensSpecification.prism.amount | VisionPrescription.lensSpecification.prism.amount | Equivalent | R4B `VisionPrescription.lensSpecification.prism.amount` maps as Equivalent to R5 `VisionPrescription.lensSpecification.prism.amount` |
| VisionPrescription.lensSpecification.prism.base | VisionPrescription.lensSpecification.prism.base | Equivalent | R4B `VisionPrescription.lensSpecification.prism.base` maps as Equivalent to R5 `VisionPrescription.lensSpecification.prism.base` - base has compatible required binding for code type: http://hl7.org/fhir/ValueSet/vision-base-codes|4.3.0 and http://hl7.org/fhir/ValueSet/vision-base-codes|5.0.0 (Equivalent) |
| VisionPrescription.lensSpecification.prism.extension | VisionPrescription.lensSpecification.prism.extension | RelatedTo | R4B `VisionPrescription.lensSpecification.prism.extension` maps as RelatedTo to R5 `VisionPrescription.lensSpecification.prism.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| VisionPrescription.lensSpecification.prism.id | VisionPrescription.lensSpecification.prism.id | Equivalent | R4B `VisionPrescription.lensSpecification.prism.id` maps as Equivalent to R5 `VisionPrescription.lensSpecification.prism.id` |
| VisionPrescription.lensSpecification.prism.modifierExtension | VisionPrescription.lensSpecification.prism.modifierExtension | RelatedTo | R4B `VisionPrescription.lensSpecification.prism.modifierExtension` maps as RelatedTo to R5 `VisionPrescription.lensSpecification.prism.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| VisionPrescription.lensSpecification.product | VisionPrescription.lensSpecification.product | Equivalent | R4B `VisionPrescription.lensSpecification.product` maps as Equivalent to R5 `VisionPrescription.lensSpecification.product` |
| VisionPrescription.lensSpecification.sphere | VisionPrescription.lensSpecification.sphere | Equivalent | R4B `VisionPrescription.lensSpecification.sphere` maps as Equivalent to R5 `VisionPrescription.lensSpecification.sphere` |
| VisionPrescription.meta | VisionPrescription.meta | Equivalent | R4B `VisionPrescription.meta` maps as Equivalent to R5 `VisionPrescription.meta` |
| VisionPrescription.modifierExtension | VisionPrescription.modifierExtension | RelatedTo | R4B `VisionPrescription.modifierExtension` maps as RelatedTo to R5 `VisionPrescription.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| VisionPrescription.patient | VisionPrescription.patient | Equivalent | R4B `VisionPrescription.patient` maps as Equivalent to R5 `VisionPrescription.patient` |
| VisionPrescription.prescriber | VisionPrescription.prescriber | Equivalent | R4B `VisionPrescription.prescriber` maps as Equivalent to R5 `VisionPrescription.prescriber` |
| VisionPrescription.status | VisionPrescription.status | Equivalent | R4B `VisionPrescription.status` maps as Equivalent to R5 `VisionPrescription.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|4.3.0 and http://hl7.org/fhir/ValueSet/fm-status|5.0.0 (Equivalent) |
| VisionPrescription.text | VisionPrescription.text | Equivalent | R4B `VisionPrescription.text` maps as Equivalent to R5 `VisionPrescription.text` |

