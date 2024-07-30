Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ParameterDefinition |  | ParameterDefinition Type: The parameters to the module. This collection specifies both the input and output parameters. Input parameters are provided by the caller as part of the $evaluate operation. Output parameters are included in the GuidanceResponse. | 10 | 8 |
| Target | ParameterDefinition |  | Base StructureDefinition for ParameterDefinition Type: The parameters to the module. This collection specifies both the input and output parameters. Input parameters are provided by the caller as part of the $evaluate operation. Output parameters are included in the GuidanceResponse. | 10 | 8 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 8 |
RelatedTo | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ParameterDefinition | ParameterDefinition | Equivalent | R5 `ParameterDefinition` maps as Equivalent to R4 `ParameterDefinition` |
| ParameterDefinition.documentation | ParameterDefinition.documentation | Equivalent | R5 `ParameterDefinition.documentation` maps as Equivalent to R4 `ParameterDefinition.documentation` |
| ParameterDefinition.extension | ParameterDefinition.extension | Equivalent | R5 `ParameterDefinition.extension` maps as Equivalent to R4 `ParameterDefinition.extension` |
| ParameterDefinition.id | ParameterDefinition.id | Equivalent | R5 `ParameterDefinition.id` maps as Equivalent to R4 `ParameterDefinition.id` |
| ParameterDefinition.max | ParameterDefinition.max | Equivalent | R5 `ParameterDefinition.max` maps as Equivalent to R4 `ParameterDefinition.max` |
| ParameterDefinition.min | ParameterDefinition.min | Equivalent | R5 `ParameterDefinition.min` maps as Equivalent to R4 `ParameterDefinition.min` |
| ParameterDefinition.name | ParameterDefinition.name | Equivalent | R5 `ParameterDefinition.name` maps as Equivalent to R4 `ParameterDefinition.name` |
| ParameterDefinition.profile | ParameterDefinition.profile | Equivalent | R5 `ParameterDefinition.profile` maps as Equivalent to R4 `ParameterDefinition.profile` |
| ParameterDefinition.type | ParameterDefinition.type | RelatedTo | R5 `ParameterDefinition.type` maps as RelatedTo to R4 `ParameterDefinition.type` - (type failed to compare required binding of http://hl7.org/fhir/ValueSet/fhir-types|5.0.0 and http://hl7.org/fhir/ValueSet/all-types|4.0.1) |
| ParameterDefinition.use | ParameterDefinition.use | Equivalent | R5 `ParameterDefinition.use` maps as Equivalent to R4 `ParameterDefinition.use` - use has compatible required binding for code type: http://hl7.org/fhir/ValueSet/operation-parameter-use|5.0.0 and http://hl7.org/fhir/ValueSet/operation-parameter-use|4.0.1 (Equivalent) |

