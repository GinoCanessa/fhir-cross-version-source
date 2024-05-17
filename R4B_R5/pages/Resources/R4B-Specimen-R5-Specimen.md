Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Specimen |  | A sample to be used for analysis. | 48 | 31 |
| Target | Specimen |  | A sample to be used for analysis. | 55 | 35 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 6 |
Equivalent | 4 |
RelatedTo | 38 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Specimen | Specimen | Equivalent | R4B `Specimen` maps as Equivalent to R5 `Specimen` |
| Specimen.accessionIdentifier | Specimen.accessionIdentifier | Equivalent | R4B `Specimen.accessionIdentifier` maps as Equivalent to R5 `Specimen.accessionIdentifier` |
| Specimen.collection | Specimen.collection | Equivalent | R4B `Specimen.collection` maps as Equivalent to R5 `Specimen.collection` |
| Specimen.collection.bodySite | Specimen.collection.bodySite | SourceIsBroaderThanTarget | R4B `Specimen.collection.bodySite` maps as SourceIsBroaderThanTarget to R5 `Specimen.collection.bodySite` - bodySite has change due to type change: R4B bodySite CodeableConcept has no equivalent or mapped type in R5 bodySite |
| Specimen.collection.collected[x] | Specimen.collection.collected[x] | Equivalent | R4B `Specimen.collection.collected[x]` maps as Equivalent to R5 `Specimen.collection.collected[x]` |
| Specimen.collection.collector | Specimen.collection.collector | SourceIsNarrowerThanTarget | R4B `Specimen.collection.collector` maps as SourceIsNarrowerThanTarget to R5 `Specimen.collection.collector` - collector has change due to type change: R4B `collector` `Reference` maps as SourceIsNarrowerThanTarget for R5 `collector` |
| Specimen.collection.duration | Specimen.collection.duration | Equivalent | R4B `Specimen.collection.duration` maps as Equivalent to R5 `Specimen.collection.duration` |
| Specimen.collection.extension | Specimen.collection.extension | RelatedTo | R4B `Specimen.collection.extension` maps as RelatedTo to R5 `Specimen.collection.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Specimen.collection.fastingStatus[x] | Specimen.collection.fastingStatus[x] | Equivalent | R4B `Specimen.collection.fastingStatus[x]` maps as Equivalent to R5 `Specimen.collection.fastingStatus[x]` |
| Specimen.collection.id | Specimen.collection.id | Equivalent | R4B `Specimen.collection.id` maps as Equivalent to R5 `Specimen.collection.id` |
| Specimen.collection.method | Specimen.collection.method | Equivalent | R4B `Specimen.collection.method` maps as Equivalent to R5 `Specimen.collection.method` |
| Specimen.collection.modifierExtension | Specimen.collection.modifierExtension | RelatedTo | R4B `Specimen.collection.modifierExtension` maps as RelatedTo to R5 `Specimen.collection.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Specimen.collection.quantity | Specimen.collection.quantity | Equivalent | R4B `Specimen.collection.quantity` maps as Equivalent to R5 `Specimen.collection.quantity` |
| Specimen.condition | Specimen.condition | Equivalent | R4B `Specimen.condition` maps as Equivalent to R5 `Specimen.condition` |
| Specimen.contained | Specimen.contained | Equivalent | R4B `Specimen.contained` maps as Equivalent to R5 `Specimen.contained` |
| Specimen.container | Specimen.container | Equivalent | R4B `Specimen.container` maps as Equivalent to R5 `Specimen.container` |
| Specimen.container.additive[x] | - | DoesNotExistInTarget | R4B `Specimen.container.additive[x]` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.container.capacity | - | DoesNotExistInTarget | R4B `Specimen.container.capacity` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.container.description | - | DoesNotExistInTarget | R4B `Specimen.container.description` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.container.extension | Specimen.container.extension | RelatedTo | R4B `Specimen.container.extension` maps as RelatedTo to R5 `Specimen.container.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Specimen.container.id | Specimen.container.id | Equivalent | R4B `Specimen.container.id` maps as Equivalent to R5 `Specimen.container.id` |
| Specimen.container.identifier | - | DoesNotExistInTarget | R4B `Specimen.container.identifier` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.container.modifierExtension | Specimen.container.modifierExtension | RelatedTo | R4B `Specimen.container.modifierExtension` maps as RelatedTo to R5 `Specimen.container.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Specimen.container.specimenQuantity | Specimen.container.specimenQuantity | Equivalent | R4B `Specimen.container.specimenQuantity` maps as Equivalent to R5 `Specimen.container.specimenQuantity` |
| Specimen.container.type | - | DoesNotExistInTarget | R4B `Specimen.container.type` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.extension | Specimen.extension | RelatedTo | R4B `Specimen.extension` maps as RelatedTo to R5 `Specimen.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Specimen.id | Specimen.id | Equivalent | R4B `Specimen.id` maps as Equivalent to R5 `Specimen.id` |
| Specimen.identifier | Specimen.identifier | Equivalent | R4B `Specimen.identifier` maps as Equivalent to R5 `Specimen.identifier` |
| Specimen.implicitRules | Specimen.implicitRules | Equivalent | R4B `Specimen.implicitRules` maps as Equivalent to R5 `Specimen.implicitRules` |
| Specimen.language | Specimen.language | RelatedTo | R4B `Specimen.language` maps as RelatedTo to R5 `Specimen.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Specimen.meta | Specimen.meta | Equivalent | R4B `Specimen.meta` maps as Equivalent to R5 `Specimen.meta` |
| Specimen.modifierExtension | Specimen.modifierExtension | RelatedTo | R4B `Specimen.modifierExtension` maps as RelatedTo to R5 `Specimen.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Specimen.note | Specimen.note | SourceIsNarrowerThanTarget | R4B `Specimen.note` maps as SourceIsNarrowerThanTarget to R5 `Specimen.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Specimen.parent | Specimen.parent | Equivalent | R4B `Specimen.parent` maps as Equivalent to R5 `Specimen.parent` |
| Specimen.processing | Specimen.processing | Equivalent | R4B `Specimen.processing` maps as Equivalent to R5 `Specimen.processing` |
| Specimen.processing.additive | Specimen.processing.additive | Equivalent | R4B `Specimen.processing.additive` maps as Equivalent to R5 `Specimen.processing.additive` |
| Specimen.processing.description | Specimen.processing.description | Equivalent | R4B `Specimen.processing.description` maps as Equivalent to R5 `Specimen.processing.description` |
| Specimen.processing.extension | Specimen.processing.extension | RelatedTo | R4B `Specimen.processing.extension` maps as RelatedTo to R5 `Specimen.processing.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Specimen.processing.id | Specimen.processing.id | Equivalent | R4B `Specimen.processing.id` maps as Equivalent to R5 `Specimen.processing.id` |
| Specimen.processing.modifierExtension | Specimen.processing.modifierExtension | RelatedTo | R4B `Specimen.processing.modifierExtension` maps as RelatedTo to R5 `Specimen.processing.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Specimen.processing.procedure | - | DoesNotExistInTarget | R4B `Specimen.processing.procedure` does not appear in the target and has no mapping for `Specimen`. |
| Specimen.processing.time[x] | Specimen.processing.time[x] | Equivalent | R4B `Specimen.processing.time[x]` maps as Equivalent to R5 `Specimen.processing.time[x]` |
| Specimen.receivedTime | Specimen.receivedTime | Equivalent | R4B `Specimen.receivedTime` maps as Equivalent to R5 `Specimen.receivedTime` |
| Specimen.request | Specimen.request | Equivalent | R4B `Specimen.request` maps as Equivalent to R5 `Specimen.request` |
| Specimen.status | Specimen.status | Equivalent | R4B `Specimen.status` maps as Equivalent to R5 `Specimen.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/specimen-status|4.3.0 and http://hl7.org/fhir/ValueSet/specimen-status|5.0.0 (Equivalent) |
| Specimen.subject | Specimen.subject | SourceIsNarrowerThanTarget | R4B `Specimen.subject` maps as SourceIsNarrowerThanTarget to R5 `Specimen.subject` - subject has change due to type change: R4B `subject` `Reference` maps as SourceIsNarrowerThanTarget for R5 `subject` |
| Specimen.text | Specimen.text | Equivalent | R4B `Specimen.text` maps as Equivalent to R5 `Specimen.text` |
| Specimen.type | Specimen.type | Equivalent | R4B `Specimen.type` maps as Equivalent to R5 `Specimen.type` |

