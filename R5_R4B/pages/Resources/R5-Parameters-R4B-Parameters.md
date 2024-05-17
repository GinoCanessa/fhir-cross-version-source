Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Parameters |  | This resource is used to pass information into and back from an operation (whether invoked directly from REST or within a messaging environment).  It is not persisted or allowed to be referenced by other resources except as described in the definition of the Parameters resource. | 13 | 6 |
| Target | Parameters |  | This resource is a non-persisted resource used to pass information into and back from an [operation](operations.html). It has no other use, and there is no RESTful endpoint associated with it. | 13 | 6 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 9 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Parameters | Parameters | Equivalent | R5 `Parameters` maps as Equivalent to R4B `Parameters` |
| Parameters.id | Parameters.id | Equivalent | R5 `Parameters.id` maps as Equivalent to R4B `Parameters.id` |
| Parameters.implicitRules | Parameters.implicitRules | Equivalent | R5 `Parameters.implicitRules` maps as Equivalent to R4B `Parameters.implicitRules` |
| Parameters.language | Parameters.language | RelatedTo | R5 `Parameters.language` maps as RelatedTo to R4B `Parameters.language` - language changed the binding strength from Required to Preferred |
| Parameters.meta | Parameters.meta | Equivalent | R5 `Parameters.meta` maps as Equivalent to R4B `Parameters.meta` |
| Parameters.parameter | Parameters.parameter | Equivalent | R5 `Parameters.parameter` maps as Equivalent to R4B `Parameters.parameter` |
| Parameters.parameter.extension | Parameters.parameter.extension | SourceIsBroaderThanTarget | R5 `Parameters.parameter.extension` maps as SourceIsBroaderThanTarget to R4B `Parameters.parameter.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Parameters.parameter.id | Parameters.parameter.id | Equivalent | R5 `Parameters.parameter.id` maps as Equivalent to R4B `Parameters.parameter.id` |
| Parameters.parameter.modifierExtension | Parameters.parameter.modifierExtension | SourceIsBroaderThanTarget | R5 `Parameters.parameter.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Parameters.parameter.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Parameters.parameter.name | Parameters.parameter.name | Equivalent | R5 `Parameters.parameter.name` maps as Equivalent to R4B `Parameters.parameter.name` |
| Parameters.parameter.part | Parameters.parameter.part | Equivalent | R5 `Parameters.parameter.part` maps as Equivalent to R4B `Parameters.parameter.part` |
| Parameters.parameter.resource | Parameters.parameter.resource | Equivalent | R5 `Parameters.parameter.resource` maps as Equivalent to R4B `Parameters.parameter.resource` |
| Parameters.parameter.value[x] | Parameters.parameter.value[x] | RelatedTo | R5 `Parameters.parameter.value[x]` maps as RelatedTo to R4B `Parameters.parameter.value[x]` - value[x] has change due to type change: R5 value[x] integer64 has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 `value[x]` `Annotation` maps as SourceIsBroaderThanTarget for R4B `value[x]`; value[x] has change due to type change: R5 `value[x]` `Attachment` maps as RelatedTo for R4B `value[x]`; value[x] has change due to type change: R5 value[x] CodeableReference has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 `value[x]` `Money` maps as RelatedTo for R4B `value[x]`; value[x] has change due to type change: R5 `value[x]` `Ratio` maps as SourceIsBroaderThanTarget for R4B `value[x]`; value[x] has change due to type change: R5 value[x] RatioRange has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 `value[x]` `Signature` maps as RelatedTo for R4B `value[x]`; value[x] has change due to type change: R5 `value[x]` `DataRequirement` maps as RelatedTo for R4B `value[x]`; value[x] has change due to type change: R5 `value[x]` `Expression` maps as RelatedTo for R4B `value[x]`; value[x] has change due to type change: R5 `value[x]` `ParameterDefinition` maps as RelatedTo for R4B `value[x]`; value[x] has change due to type change: R5 type Availability does not exist in R4B; value[x] has change due to type change: R5 type ExtendedContactDetail does not exist in R4B; value[x] has change due to type change: R5 `value[x]` `Dosage` maps as RelatedTo for R4B `value[x]` |

