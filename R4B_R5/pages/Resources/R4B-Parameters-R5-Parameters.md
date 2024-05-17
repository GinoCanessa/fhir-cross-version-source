Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Parameters |  | This resource is a non-persisted resource used to pass information into and back from an [operation](operations.html). It has no other use, and there is no RESTful endpoint associated with it. | 13 | 6 |
| Target | Parameters |  | This resource is used to pass information into and back from an operation (whether invoked directly from REST or within a messaging environment).  It is not persisted or allowed to be referenced by other resources except as described in the definition of the Parameters resource. | 13 | 6 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 9 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Parameters | Parameters | Equivalent | R4B `Parameters` maps as Equivalent to R5 `Parameters` |
| Parameters.id | Parameters.id | Equivalent | R4B `Parameters.id` maps as Equivalent to R5 `Parameters.id` |
| Parameters.implicitRules | Parameters.implicitRules | Equivalent | R4B `Parameters.implicitRules` maps as Equivalent to R5 `Parameters.implicitRules` |
| Parameters.language | Parameters.language | RelatedTo | R4B `Parameters.language` maps as RelatedTo to R5 `Parameters.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Parameters.meta | Parameters.meta | Equivalent | R4B `Parameters.meta` maps as Equivalent to R5 `Parameters.meta` |
| Parameters.parameter | Parameters.parameter | Equivalent | R4B `Parameters.parameter` maps as Equivalent to R5 `Parameters.parameter` |
| Parameters.parameter.extension | Parameters.parameter.extension | RelatedTo | R4B `Parameters.parameter.extension` maps as RelatedTo to R5 `Parameters.parameter.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Parameters.parameter.id | Parameters.parameter.id | Equivalent | R4B `Parameters.parameter.id` maps as Equivalent to R5 `Parameters.parameter.id` |
| Parameters.parameter.modifierExtension | Parameters.parameter.modifierExtension | RelatedTo | R4B `Parameters.parameter.modifierExtension` maps as RelatedTo to R5 `Parameters.parameter.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Parameters.parameter.name | Parameters.parameter.name | Equivalent | R4B `Parameters.parameter.name` maps as Equivalent to R5 `Parameters.parameter.name` |
| Parameters.parameter.part | Parameters.parameter.part | Equivalent | R4B `Parameters.parameter.part` maps as Equivalent to R5 `Parameters.parameter.part` |
| Parameters.parameter.resource | Parameters.parameter.resource | Equivalent | R4B `Parameters.parameter.resource` maps as Equivalent to R5 `Parameters.parameter.resource` |
| Parameters.parameter.value[x] | Parameters.parameter.value[x] | RelatedTo | R4B `Parameters.parameter.value[x]` maps as RelatedTo to R5 `Parameters.parameter.value[x]` - value[x] has change due to type change: R4B `value[x]` `integer` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `positiveInt` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `unsignedInt` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Attachment` maps as RelatedTo for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Money` maps as RelatedTo for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Ratio` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B value[x] Contributor has no equivalent or mapped type in R5 value[x]; value[x] has change due to type change: R4B `value[x]` `DataRequirement` maps as RelatedTo for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Expression` maps as SourceIsBroaderThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `ParameterDefinition` maps as RelatedTo for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Dosage` maps as RelatedTo for R5 `value[x]` |

