Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Specimen |  | A sample to be used for analysis. | 55 | 35 |
| Target | Specimen |  | A sample to be used for analysis. | 48 | 31 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 12 |
Equivalent | 30 |
SourceIsBroaderThanTarget | 12 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Specimen | Specimen | Equivalent | R5 `Specimen` maps as Equivalent to R4 `Specimen` |
| Specimen.accessionIdentifier | Specimen.accessionIdentifier | Equivalent | R5 `Specimen.accessionIdentifier` maps as Equivalent to R4 `Specimen.accessionIdentifier` |
| Specimen.collection | Specimen.collection | Equivalent | R5 `Specimen.collection` maps as Equivalent to R4 `Specimen.collection` |
| Specimen.collection.bodySite | Specimen.collection.bodySite | SourceIsBroaderThanTarget | R5 `Specimen.collection.bodySite` maps as SourceIsBroaderThanTarget to R4 `Specimen.collection.bodySite` - bodySite has change due to type change: R5 bodySite CodeableReference has no equivalent or mapped type in R4 bodySite |
| Specimen.collection.collected[x] | Specimen.collection.collected[x] | Equivalent | R5 `Specimen.collection.collected[x]` maps as Equivalent to R4 `Specimen.collection.collected[x]` |
| Specimen.collection.collector | Specimen.collection.collector | SourceIsBroaderThanTarget | R5 `Specimen.collection.collector` maps as SourceIsBroaderThanTarget to R4 `Specimen.collection.collector` - collector has change due to type change: R5 `collector` `Reference` maps as SourceIsBroaderThanTarget for R4 `collector` |
| Specimen.collection.device | - | DoesNotExistInTarget | R5 `Specimen.collection.device` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.collection.duration | Specimen.collection.duration | Equivalent | R5 `Specimen.collection.duration` maps as Equivalent to R4 `Specimen.collection.duration` |
| Specimen.collection.extension | Specimen.collection.extension | SourceIsBroaderThanTarget | R5 `Specimen.collection.extension` maps as SourceIsBroaderThanTarget to R4 `Specimen.collection.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Specimen.collection.fastingStatus[x] | Specimen.collection.fastingStatus[x] | Equivalent | R5 `Specimen.collection.fastingStatus[x]` maps as Equivalent to R4 `Specimen.collection.fastingStatus[x]` |
| Specimen.collection.id | Specimen.collection.id | Equivalent | R5 `Specimen.collection.id` maps as Equivalent to R4 `Specimen.collection.id` |
| Specimen.collection.method | Specimen.collection.method | Equivalent | R5 `Specimen.collection.method` maps as Equivalent to R4 `Specimen.collection.method` |
| Specimen.collection.modifierExtension | Specimen.collection.modifierExtension | SourceIsBroaderThanTarget | R5 `Specimen.collection.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Specimen.collection.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Specimen.collection.procedure | - | DoesNotExistInTarget | R5 `Specimen.collection.procedure` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.collection.quantity | Specimen.collection.quantity | Equivalent | R5 `Specimen.collection.quantity` maps as Equivalent to R4 `Specimen.collection.quantity` |
| Specimen.combined | - | DoesNotExistInTarget | R5 `Specimen.combined` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.condition | Specimen.condition | Equivalent | R5 `Specimen.condition` maps as Equivalent to R4 `Specimen.condition` |
| Specimen.contained | Specimen.contained | Equivalent | R5 `Specimen.contained` maps as Equivalent to R4 `Specimen.contained` |
| Specimen.container | Specimen.container | Equivalent | R5 `Specimen.container` maps as Equivalent to R4 `Specimen.container` |
| Specimen.container.device | - | DoesNotExistInTarget | R5 `Specimen.container.device` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.container.extension | Specimen.container.extension | SourceIsBroaderThanTarget | R5 `Specimen.container.extension` maps as SourceIsBroaderThanTarget to R4 `Specimen.container.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Specimen.container.id | Specimen.container.id | Equivalent | R5 `Specimen.container.id` maps as Equivalent to R4 `Specimen.container.id` |
| Specimen.container.location | - | DoesNotExistInTarget | R5 `Specimen.container.location` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.container.modifierExtension | Specimen.container.modifierExtension | SourceIsBroaderThanTarget | R5 `Specimen.container.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Specimen.container.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Specimen.container.specimenQuantity | Specimen.container.specimenQuantity | Equivalent | R5 `Specimen.container.specimenQuantity` maps as Equivalent to R4 `Specimen.container.specimenQuantity` |
| Specimen.extension | Specimen.extension | SourceIsBroaderThanTarget | R5 `Specimen.extension` maps as SourceIsBroaderThanTarget to R4 `Specimen.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Specimen.feature | - | DoesNotExistInTarget | R5 `Specimen.feature` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.feature.description | - | DoesNotExistInTarget | R5 `Specimen.feature.description` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.feature.extension | - | DoesNotExistInTarget | R5 `Specimen.feature.extension` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.feature.id | - | DoesNotExistInTarget | R5 `Specimen.feature.id` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.feature.modifierExtension | - | DoesNotExistInTarget | R5 `Specimen.feature.modifierExtension` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.feature.type | - | DoesNotExistInTarget | R5 `Specimen.feature.type` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.id | Specimen.id | Equivalent | R5 `Specimen.id` maps as Equivalent to R4 `Specimen.id` |
| Specimen.identifier | Specimen.identifier | Equivalent | R5 `Specimen.identifier` maps as Equivalent to R4 `Specimen.identifier` |
| Specimen.implicitRules | Specimen.implicitRules | Equivalent | R5 `Specimen.implicitRules` maps as Equivalent to R4 `Specimen.implicitRules` |
| Specimen.language | Specimen.language | SourceIsNarrowerThanTarget | R5 `Specimen.language` maps as SourceIsNarrowerThanTarget to R4 `Specimen.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Specimen.meta | Specimen.meta | Equivalent | R5 `Specimen.meta` maps as Equivalent to R4 `Specimen.meta` |
| Specimen.modifierExtension | Specimen.modifierExtension | SourceIsBroaderThanTarget | R5 `Specimen.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Specimen.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Specimen.note | Specimen.note | SourceIsBroaderThanTarget | R5 `Specimen.note` maps as SourceIsBroaderThanTarget to R4 `Specimen.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| Specimen.parent | Specimen.parent | Equivalent | R5 `Specimen.parent` maps as Equivalent to R4 `Specimen.parent` |
| Specimen.processing | Specimen.processing | Equivalent | R5 `Specimen.processing` maps as Equivalent to R4 `Specimen.processing` |
| Specimen.processing.additive | Specimen.processing.additive | Equivalent | R5 `Specimen.processing.additive` maps as Equivalent to R4 `Specimen.processing.additive` |
| Specimen.processing.description | Specimen.processing.description | Equivalent | R5 `Specimen.processing.description` maps as Equivalent to R4 `Specimen.processing.description` |
| Specimen.processing.extension | Specimen.processing.extension | SourceIsBroaderThanTarget | R5 `Specimen.processing.extension` maps as SourceIsBroaderThanTarget to R4 `Specimen.processing.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Specimen.processing.id | Specimen.processing.id | Equivalent | R5 `Specimen.processing.id` maps as Equivalent to R4 `Specimen.processing.id` |
| Specimen.processing.method | Specimen.processing.procedure | Equivalent | R5 `Specimen.processing.method` maps as Equivalent to R4 `Specimen.processing.procedure` |
| Specimen.processing.modifierExtension | Specimen.processing.modifierExtension | SourceIsBroaderThanTarget | R5 `Specimen.processing.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Specimen.processing.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Specimen.processing.time[x] | Specimen.processing.time[x] | Equivalent | R5 `Specimen.processing.time[x]` maps as Equivalent to R4 `Specimen.processing.time[x]` |
| Specimen.receivedTime | Specimen.receivedTime | Equivalent | R5 `Specimen.receivedTime` maps as Equivalent to R4 `Specimen.receivedTime` |
| Specimen.request | Specimen.request | Equivalent | R5 `Specimen.request` maps as Equivalent to R4 `Specimen.request` |
| Specimen.role | - | DoesNotExistInTarget | R5 `Specimen.role` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.status | Specimen.status | Equivalent | R5 `Specimen.status` maps as Equivalent to R4 `Specimen.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/specimen-status|5.0.0 and http://hl7.org/fhir/ValueSet/specimen-status|4.0.1 (Equivalent) |
| Specimen.subject | Specimen.subject | SourceIsBroaderThanTarget | R5 `Specimen.subject` maps as SourceIsBroaderThanTarget to R4 `Specimen.subject` - subject has change due to type change: R5 `subject` `Reference` maps as SourceIsBroaderThanTarget for R4 `subject` |
| Specimen.text | Specimen.text | Equivalent | R5 `Specimen.text` maps as Equivalent to R4 `Specimen.text` |
| Specimen.type | Specimen.type | Equivalent | R5 `Specimen.type` maps as Equivalent to R4 `Specimen.type` |

