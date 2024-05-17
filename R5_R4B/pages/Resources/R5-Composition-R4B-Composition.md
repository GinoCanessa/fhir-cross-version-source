Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Composition |  | A set of healthcare-related information that is assembled together into a single logical package that provides a single coherent statement of meaning, establishes its own context and that has clinical attestation with regard to who is making the statement. A Composition defines the structure and narrative content necessary for a document. However, a Composition alone does not constitute a document. Rather, the Composition must be the first entry in a Bundle where Bundle.type=document, and any other resources referenced from Composition must be included as subsequent entries in the Bundle (for example Patient, Practitioner, Encounter, etc.). | 51 | 34 |
| Target | Composition |  | A set of healthcare-related information that is assembled together into a single logical package that provides a single coherent statement of meaning, establishes its own context and that has clinical attestation with regard to who is making the statement. A Composition defines the structure and narrative content necessary for a document. However, a Composition alone does not constitute a document. Rather, the Composition must be the first entry in a Bundle where Bundle.type=document, and any other resources referenced from Composition must be included as subsequent entries in the Bundle (for example Patient, Practitioner, Encounter, etc.). | 54 | 34 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 5 |
Equivalent | 4 |
RelatedTo | 42 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Composition | Composition | Equivalent | R5 `Composition` maps as Equivalent to R4B `Composition` |
| Composition.attester | Composition.attester | Equivalent | R5 `Composition.attester` maps as Equivalent to R4B `Composition.attester` |
| Composition.attester.extension | Composition.attester.extension | SourceIsBroaderThanTarget | R5 `Composition.attester.extension` maps as SourceIsBroaderThanTarget to R4B `Composition.attester.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Composition.attester.id | Composition.attester.id | Equivalent | R5 `Composition.attester.id` maps as Equivalent to R4B `Composition.attester.id` |
| Composition.attester.mode | Composition.attester.mode | RelatedTo | R5 `Composition.attester.mode` maps as RelatedTo to R4B `Composition.attester.mode` - mode made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/composition-attestation-mode|4.3.0; mode has change due to type change: R5 mode CodeableConcept has no equivalent or mapped type in R4B mode |
| Composition.attester.modifierExtension | Composition.attester.modifierExtension | SourceIsBroaderThanTarget | R5 `Composition.attester.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Composition.attester.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Composition.attester.party | Composition.attester.party | Equivalent | R5 `Composition.attester.party` maps as Equivalent to R4B `Composition.attester.party` |
| Composition.attester.time | Composition.attester.time | Equivalent | R5 `Composition.attester.time` maps as Equivalent to R4B `Composition.attester.time` |
| Composition.author | Composition.author | Equivalent | R5 `Composition.author` maps as Equivalent to R4B `Composition.author` |
| Composition.category | Composition.category | Equivalent | R5 `Composition.category` maps as Equivalent to R4B `Composition.category` |
| Composition.contained | Composition.contained | Equivalent | R5 `Composition.contained` maps as Equivalent to R4B `Composition.contained` |
| Composition.custodian | Composition.custodian | Equivalent | R5 `Composition.custodian` maps as Equivalent to R4B `Composition.custodian` |
| Composition.date | Composition.date | Equivalent | R5 `Composition.date` maps as Equivalent to R4B `Composition.date` |
| Composition.encounter | Composition.encounter | Equivalent | R5 `Composition.encounter` maps as Equivalent to R4B `Composition.encounter` |
| Composition.event | Composition.event | Equivalent | R5 `Composition.event` maps as Equivalent to R4B `Composition.event` |
| Composition.event.detail | Composition.event.detail | RelatedTo | R5 `Composition.event.detail` maps as RelatedTo to R4B `Composition.event.detail` - detail removed a binding requirement - Example http://terminology.hl7.org/ValueSet/v3-ActCode; detail has change due to type change: R5 detail CodeableReference has no equivalent or mapped type in R4B detail |
| Composition.event.extension | Composition.event.extension | SourceIsBroaderThanTarget | R5 `Composition.event.extension` maps as SourceIsBroaderThanTarget to R4B `Composition.event.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Composition.event.id | Composition.event.id | Equivalent | R5 `Composition.event.id` maps as Equivalent to R4B `Composition.event.id` |
| Composition.event.modifierExtension | Composition.event.modifierExtension | SourceIsBroaderThanTarget | R5 `Composition.event.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Composition.event.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Composition.event.period | Composition.event.period | Equivalent | R5 `Composition.event.period` maps as Equivalent to R4B `Composition.event.period` |
| Composition.extension | Composition.extension | SourceIsBroaderThanTarget | R5 `Composition.extension` maps as SourceIsBroaderThanTarget to R4B `Composition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Composition.id | Composition.id | Equivalent | R5 `Composition.id` maps as Equivalent to R4B `Composition.id` |
| Composition.identifier | Composition.identifier | RelatedTo | R5 `Composition.identifier` maps as RelatedTo to R4B `Composition.identifier` - identifier changed from array to scalar (max cardinality from * to 1) |
| Composition.implicitRules | Composition.implicitRules | Equivalent | R5 `Composition.implicitRules` maps as Equivalent to R4B `Composition.implicitRules` |
| Composition.language | Composition.language | RelatedTo | R5 `Composition.language` maps as RelatedTo to R4B `Composition.language` - language changed the binding strength from Required to Preferred |
| Composition.meta | Composition.meta | Equivalent | R5 `Composition.meta` maps as Equivalent to R4B `Composition.meta` |
| Composition.modifierExtension | Composition.modifierExtension | SourceIsBroaderThanTarget | R5 `Composition.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Composition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Composition.name | - | DoesNotExistInTarget | R5 `Composition.name` does not appear in the target and has no mapping for `Composition`. |
| Composition.note | - | DoesNotExistInTarget | R5 `Composition.note` does not appear in the target and has no mapping for `Composition`. |
| Composition.relatesTo | Composition.relatesTo | SourceIsBroaderThanTarget | R5 `Composition.relatesTo` maps as SourceIsBroaderThanTarget to R4B `Composition.relatesTo` - relatesTo has change due to type change: R5 relatesTo RelatedArtifact has no equivalent or mapped type in R4B relatesTo |
| Composition.section | Composition.section | Equivalent | R5 `Composition.section` maps as Equivalent to R4B `Composition.section` |
| Composition.section.author | Composition.section.author | Equivalent | R5 `Composition.section.author` maps as Equivalent to R4B `Composition.section.author` |
| Composition.section.code | Composition.section.code | Equivalent | R5 `Composition.section.code` maps as Equivalent to R4B `Composition.section.code` |
| Composition.section.emptyReason | Composition.section.emptyReason | Equivalent | R5 `Composition.section.emptyReason` maps as Equivalent to R4B `Composition.section.emptyReason` |
| Composition.section.entry | Composition.section.entry | Equivalent | R5 `Composition.section.entry` maps as Equivalent to R4B `Composition.section.entry` |
| Composition.section.extension | Composition.section.extension | SourceIsBroaderThanTarget | R5 `Composition.section.extension` maps as SourceIsBroaderThanTarget to R4B `Composition.section.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Composition.section.focus | Composition.section.focus | Equivalent | R5 `Composition.section.focus` maps as Equivalent to R4B `Composition.section.focus` |
| Composition.section.id | Composition.section.id | Equivalent | R5 `Composition.section.id` maps as Equivalent to R4B `Composition.section.id` |
| Composition.section.modifierExtension | Composition.section.modifierExtension | SourceIsBroaderThanTarget | R5 `Composition.section.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Composition.section.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Composition.section.orderedBy | Composition.section.orderedBy | Equivalent | R5 `Composition.section.orderedBy` maps as Equivalent to R4B `Composition.section.orderedBy` |
| Composition.section.section | Composition.section.section | Equivalent | R5 `Composition.section.section` maps as Equivalent to R4B `Composition.section.section` |
| Composition.section.text | Composition.section.text | Equivalent | R5 `Composition.section.text` maps as Equivalent to R4B `Composition.section.text` |
| Composition.section.title | Composition.section.title | Equivalent | R5 `Composition.section.title` maps as Equivalent to R4B `Composition.section.title` |
| Composition.status | Composition.status | Equivalent | R5 `Composition.status` maps as Equivalent to R4B `Composition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/composition-status|5.0.0 and http://hl7.org/fhir/ValueSet/composition-status|4.3.0 (Equivalent) |
| Composition.subject | Composition.subject | RelatedTo | R5 `Composition.subject` maps as RelatedTo to R4B `Composition.subject` - subject changed from array to scalar (max cardinality from * to 1) |
| Composition.text | Composition.text | Equivalent | R5 `Composition.text` maps as Equivalent to R4B `Composition.text` |
| Composition.title | Composition.title | Equivalent | R5 `Composition.title` maps as Equivalent to R4B `Composition.title` |
| Composition.type | Composition.type | Equivalent | R5 `Composition.type` maps as Equivalent to R4B `Composition.type` |
| Composition.url | - | DoesNotExistInTarget | R5 `Composition.url` does not appear in the target and has no mapping for `Composition`. |
| Composition.useContext | - | DoesNotExistInTarget | R5 `Composition.useContext` does not appear in the target and has no mapping for `Composition`. |
| Composition.version | - | DoesNotExistInTarget | R5 `Composition.version` does not appear in the target and has no mapping for `Composition`. |

