Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | SpecimenDefinition |  | A kind of specimen with associated set of requirements. | 48 | 28 |
| Target | SpecimenDefinition |  | A kind of specimen with associated set of requirements. | 72 | 52 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 44 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| SpecimenDefinition | SpecimenDefinition | Equivalent | R4B `SpecimenDefinition` maps as Equivalent to R5 `SpecimenDefinition` |
| SpecimenDefinition.collection | SpecimenDefinition.collection | Equivalent | R4B `SpecimenDefinition.collection` maps as Equivalent to R5 `SpecimenDefinition.collection` |
| SpecimenDefinition.contained | SpecimenDefinition.contained | Equivalent | R4B `SpecimenDefinition.contained` maps as Equivalent to R5 `SpecimenDefinition.contained` |
| SpecimenDefinition.extension | SpecimenDefinition.extension | RelatedTo | R4B `SpecimenDefinition.extension` maps as RelatedTo to R5 `SpecimenDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SpecimenDefinition.id | SpecimenDefinition.id | Equivalent | R4B `SpecimenDefinition.id` maps as Equivalent to R5 `SpecimenDefinition.id` |
| SpecimenDefinition.identifier | SpecimenDefinition.identifier | Equivalent | R4B `SpecimenDefinition.identifier` maps as Equivalent to R5 `SpecimenDefinition.identifier` |
| SpecimenDefinition.implicitRules | SpecimenDefinition.implicitRules | Equivalent | R4B `SpecimenDefinition.implicitRules` maps as Equivalent to R5 `SpecimenDefinition.implicitRules` |
| SpecimenDefinition.language | SpecimenDefinition.language | RelatedTo | R4B `SpecimenDefinition.language` maps as RelatedTo to R5 `SpecimenDefinition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| SpecimenDefinition.meta | SpecimenDefinition.meta | Equivalent | R4B `SpecimenDefinition.meta` maps as Equivalent to R5 `SpecimenDefinition.meta` |
| SpecimenDefinition.modifierExtension | SpecimenDefinition.modifierExtension | RelatedTo | R4B `SpecimenDefinition.modifierExtension` maps as RelatedTo to R5 `SpecimenDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SpecimenDefinition.patientPreparation | SpecimenDefinition.patientPreparation | Equivalent | R4B `SpecimenDefinition.patientPreparation` maps as Equivalent to R5 `SpecimenDefinition.patientPreparation` |
| SpecimenDefinition.text | SpecimenDefinition.text | Equivalent | R4B `SpecimenDefinition.text` maps as Equivalent to R5 `SpecimenDefinition.text` |
| SpecimenDefinition.timeAspect | SpecimenDefinition.timeAspect | Equivalent | R4B `SpecimenDefinition.timeAspect` maps as Equivalent to R5 `SpecimenDefinition.timeAspect` |
| SpecimenDefinition.typeCollected | SpecimenDefinition.typeCollected | Equivalent | R4B `SpecimenDefinition.typeCollected` maps as Equivalent to R5 `SpecimenDefinition.typeCollected` |
| SpecimenDefinition.typeTested | SpecimenDefinition.typeTested | Equivalent | R4B `SpecimenDefinition.typeTested` maps as Equivalent to R5 `SpecimenDefinition.typeTested` |
| SpecimenDefinition.typeTested.container | SpecimenDefinition.typeTested.container | Equivalent | R4B `SpecimenDefinition.typeTested.container` maps as Equivalent to R5 `SpecimenDefinition.typeTested.container` |
| SpecimenDefinition.typeTested.container.additive | SpecimenDefinition.typeTested.container.additive | Equivalent | R4B `SpecimenDefinition.typeTested.container.additive` maps as Equivalent to R5 `SpecimenDefinition.typeTested.container.additive` |
| SpecimenDefinition.typeTested.container.additive.additive[x] | SpecimenDefinition.typeTested.container.additive.additive[x] | RelatedTo | R4B `SpecimenDefinition.typeTested.container.additive.additive[x]` maps as RelatedTo to R5 `SpecimenDefinition.typeTested.container.additive.additive[x]` - additive[x] has change due to type change: R4B `additive[x]` `Reference` maps as RelatedTo for R5 `additive[x]` |
| SpecimenDefinition.typeTested.container.additive.extension | SpecimenDefinition.typeTested.container.additive.extension | RelatedTo | R4B `SpecimenDefinition.typeTested.container.additive.extension` maps as RelatedTo to R5 `SpecimenDefinition.typeTested.container.additive.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SpecimenDefinition.typeTested.container.additive.id | SpecimenDefinition.typeTested.container.additive.id | Equivalent | R4B `SpecimenDefinition.typeTested.container.additive.id` maps as Equivalent to R5 `SpecimenDefinition.typeTested.container.additive.id` |
| SpecimenDefinition.typeTested.container.additive.modifierExtension | SpecimenDefinition.typeTested.container.additive.modifierExtension | RelatedTo | R4B `SpecimenDefinition.typeTested.container.additive.modifierExtension` maps as RelatedTo to R5 `SpecimenDefinition.typeTested.container.additive.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SpecimenDefinition.typeTested.container.cap | SpecimenDefinition.typeTested.container.cap | Equivalent | R4B `SpecimenDefinition.typeTested.container.cap` maps as Equivalent to R5 `SpecimenDefinition.typeTested.container.cap` |
| SpecimenDefinition.typeTested.container.capacity | SpecimenDefinition.typeTested.container.capacity | Equivalent | R4B `SpecimenDefinition.typeTested.container.capacity` maps as Equivalent to R5 `SpecimenDefinition.typeTested.container.capacity` |
| SpecimenDefinition.typeTested.container.description | SpecimenDefinition.typeTested.container.description | SourceIsBroaderThanTarget | R4B `SpecimenDefinition.typeTested.container.description` maps as SourceIsBroaderThanTarget to R5 `SpecimenDefinition.typeTested.container.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| SpecimenDefinition.typeTested.container.extension | SpecimenDefinition.typeTested.container.extension | RelatedTo | R4B `SpecimenDefinition.typeTested.container.extension` maps as RelatedTo to R5 `SpecimenDefinition.typeTested.container.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SpecimenDefinition.typeTested.container.id | SpecimenDefinition.typeTested.container.id | Equivalent | R4B `SpecimenDefinition.typeTested.container.id` maps as Equivalent to R5 `SpecimenDefinition.typeTested.container.id` |
| SpecimenDefinition.typeTested.container.material | SpecimenDefinition.typeTested.container.material | Equivalent | R4B `SpecimenDefinition.typeTested.container.material` maps as Equivalent to R5 `SpecimenDefinition.typeTested.container.material` |
| SpecimenDefinition.typeTested.container.minimumVolume[x] | SpecimenDefinition.typeTested.container.minimumVolume[x] | Equivalent | R4B `SpecimenDefinition.typeTested.container.minimumVolume[x]` maps as Equivalent to R5 `SpecimenDefinition.typeTested.container.minimumVolume[x]` |
| SpecimenDefinition.typeTested.container.modifierExtension | SpecimenDefinition.typeTested.container.modifierExtension | RelatedTo | R4B `SpecimenDefinition.typeTested.container.modifierExtension` maps as RelatedTo to R5 `SpecimenDefinition.typeTested.container.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SpecimenDefinition.typeTested.container.preparation | SpecimenDefinition.typeTested.container.preparation | SourceIsBroaderThanTarget | R4B `SpecimenDefinition.typeTested.container.preparation` maps as SourceIsBroaderThanTarget to R5 `SpecimenDefinition.typeTested.container.preparation` - preparation has change due to type change: R4B preparation string has no equivalent or mapped type in R5 preparation |
| SpecimenDefinition.typeTested.container.type | SpecimenDefinition.typeTested.container.type | Equivalent | R4B `SpecimenDefinition.typeTested.container.type` maps as Equivalent to R5 `SpecimenDefinition.typeTested.container.type` |
| SpecimenDefinition.typeTested.extension | SpecimenDefinition.typeTested.extension | RelatedTo | R4B `SpecimenDefinition.typeTested.extension` maps as RelatedTo to R5 `SpecimenDefinition.typeTested.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SpecimenDefinition.typeTested.handling | SpecimenDefinition.typeTested.handling | Equivalent | R4B `SpecimenDefinition.typeTested.handling` maps as Equivalent to R5 `SpecimenDefinition.typeTested.handling` |
| SpecimenDefinition.typeTested.handling.extension | SpecimenDefinition.typeTested.handling.extension | RelatedTo | R4B `SpecimenDefinition.typeTested.handling.extension` maps as RelatedTo to R5 `SpecimenDefinition.typeTested.handling.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SpecimenDefinition.typeTested.handling.id | SpecimenDefinition.typeTested.handling.id | Equivalent | R4B `SpecimenDefinition.typeTested.handling.id` maps as Equivalent to R5 `SpecimenDefinition.typeTested.handling.id` |
| SpecimenDefinition.typeTested.handling.instruction | SpecimenDefinition.typeTested.handling.instruction | SourceIsBroaderThanTarget | R4B `SpecimenDefinition.typeTested.handling.instruction` maps as SourceIsBroaderThanTarget to R5 `SpecimenDefinition.typeTested.handling.instruction` - instruction has change due to type change: R4B instruction string has no equivalent or mapped type in R5 instruction |
| SpecimenDefinition.typeTested.handling.maxDuration | SpecimenDefinition.typeTested.handling.maxDuration | Equivalent | R4B `SpecimenDefinition.typeTested.handling.maxDuration` maps as Equivalent to R5 `SpecimenDefinition.typeTested.handling.maxDuration` |
| SpecimenDefinition.typeTested.handling.modifierExtension | SpecimenDefinition.typeTested.handling.modifierExtension | RelatedTo | R4B `SpecimenDefinition.typeTested.handling.modifierExtension` maps as RelatedTo to R5 `SpecimenDefinition.typeTested.handling.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SpecimenDefinition.typeTested.handling.temperatureQualifier | SpecimenDefinition.typeTested.handling.temperatureQualifier | Equivalent | R4B `SpecimenDefinition.typeTested.handling.temperatureQualifier` maps as Equivalent to R5 `SpecimenDefinition.typeTested.handling.temperatureQualifier` |
| SpecimenDefinition.typeTested.handling.temperatureRange | SpecimenDefinition.typeTested.handling.temperatureRange | Equivalent | R4B `SpecimenDefinition.typeTested.handling.temperatureRange` maps as Equivalent to R5 `SpecimenDefinition.typeTested.handling.temperatureRange` |
| SpecimenDefinition.typeTested.id | SpecimenDefinition.typeTested.id | Equivalent | R4B `SpecimenDefinition.typeTested.id` maps as Equivalent to R5 `SpecimenDefinition.typeTested.id` |
| SpecimenDefinition.typeTested.isDerived | SpecimenDefinition.typeTested.isDerived | Equivalent | R4B `SpecimenDefinition.typeTested.isDerived` maps as Equivalent to R5 `SpecimenDefinition.typeTested.isDerived` |
| SpecimenDefinition.typeTested.modifierExtension | SpecimenDefinition.typeTested.modifierExtension | RelatedTo | R4B `SpecimenDefinition.typeTested.modifierExtension` maps as RelatedTo to R5 `SpecimenDefinition.typeTested.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SpecimenDefinition.typeTested.preference | SpecimenDefinition.typeTested.preference | Equivalent | R4B `SpecimenDefinition.typeTested.preference` maps as Equivalent to R5 `SpecimenDefinition.typeTested.preference` - preference has compatible required binding for code type: http://hl7.org/fhir/ValueSet/specimen-contained-preference|4.3.0 and http://hl7.org/fhir/ValueSet/specimen-contained-preference|5.0.0 (Equivalent) |
| SpecimenDefinition.typeTested.rejectionCriterion | SpecimenDefinition.typeTested.rejectionCriterion | Equivalent | R4B `SpecimenDefinition.typeTested.rejectionCriterion` maps as Equivalent to R5 `SpecimenDefinition.typeTested.rejectionCriterion` |
| SpecimenDefinition.typeTested.requirement | SpecimenDefinition.typeTested.requirement | SourceIsBroaderThanTarget | R4B `SpecimenDefinition.typeTested.requirement` maps as SourceIsBroaderThanTarget to R5 `SpecimenDefinition.typeTested.requirement` - requirement has change due to type change: R4B requirement string has no equivalent or mapped type in R5 requirement |
| SpecimenDefinition.typeTested.retentionTime | SpecimenDefinition.typeTested.retentionTime | Equivalent | R4B `SpecimenDefinition.typeTested.retentionTime` maps as Equivalent to R5 `SpecimenDefinition.typeTested.retentionTime` |
| SpecimenDefinition.typeTested.type | SpecimenDefinition.typeTested.type | Equivalent | R4B `SpecimenDefinition.typeTested.type` maps as Equivalent to R5 `SpecimenDefinition.typeTested.type` |

