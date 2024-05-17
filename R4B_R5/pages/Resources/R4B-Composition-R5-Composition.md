Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Composition |  | A set of healthcare-related information that is assembled together into a single logical package that provides a single coherent statement of meaning, establishes its own context and that has clinical attestation with regard to who is making the statement. A Composition defines the structure and narrative content necessary for a document. However, a Composition alone does not constitute a document. Rather, the Composition must be the first entry in a Bundle where Bundle.type=document, and any other resources referenced from Composition must be included as subsequent entries in the Bundle (for example Patient, Practitioner, Encounter, etc.). | 54 | 34 |
| Target | Composition |  | A set of healthcare-related information that is assembled together into a single logical package that provides a single coherent statement of meaning, establishes its own context and that has clinical attestation with regard to who is making the statement. A Composition defines the structure and narrative content necessary for a document. However, a Composition alone does not constitute a document. Rather, the Composition must be the first entry in a Bundle where Bundle.type=document, and any other resources referenced from Composition must be included as subsequent entries in the Bundle (for example Patient, Practitioner, Encounter, etc.). | 51 | 34 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 8 |
Equivalent | 4 |
RelatedTo | 42 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Composition | Composition | Equivalent | R4B `Composition` maps as Equivalent to R5 `Composition` |
| Composition.attester | Composition.attester | Equivalent | R4B `Composition.attester` maps as Equivalent to R5 `Composition.attester` |
| Composition.attester.extension | Composition.attester.extension | RelatedTo | R4B `Composition.attester.extension` maps as RelatedTo to R5 `Composition.attester.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Composition.attester.id | Composition.attester.id | Equivalent | R4B `Composition.attester.id` maps as Equivalent to R5 `Composition.attester.id` |
| Composition.attester.mode | Composition.attester.mode | RelatedTo | R4B `Composition.attester.mode` maps as RelatedTo to R5 `Composition.attester.mode` - mode changed the binding strength from Required to Preferred; mode has change due to type change: R4B mode code has no equivalent or mapped type in R5 mode |
| Composition.attester.modifierExtension | Composition.attester.modifierExtension | RelatedTo | R4B `Composition.attester.modifierExtension` maps as RelatedTo to R5 `Composition.attester.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Composition.attester.party | Composition.attester.party | Equivalent | R4B `Composition.attester.party` maps as Equivalent to R5 `Composition.attester.party` |
| Composition.attester.time | Composition.attester.time | Equivalent | R4B `Composition.attester.time` maps as Equivalent to R5 `Composition.attester.time` |
| Composition.author | Composition.author | Equivalent | R4B `Composition.author` maps as Equivalent to R5 `Composition.author` |
| Composition.category | Composition.category | Equivalent | R4B `Composition.category` maps as Equivalent to R5 `Composition.category` |
| Composition.confidentiality | - | DoesNotExistInTarget | R4B `Composition.confidentiality` does not appear in the target and has no mapping for `Composition`. |
| Composition.contained | Composition.contained | Equivalent | R4B `Composition.contained` maps as Equivalent to R5 `Composition.contained` |
| Composition.custodian | Composition.custodian | Equivalent | R4B `Composition.custodian` maps as Equivalent to R5 `Composition.custodian` |
| Composition.date | Composition.date | Equivalent | R4B `Composition.date` maps as Equivalent to R5 `Composition.date` |
| Composition.encounter | Composition.encounter | Equivalent | R4B `Composition.encounter` maps as Equivalent to R5 `Composition.encounter` |
| Composition.event | Composition.event | Equivalent | R4B `Composition.event` maps as Equivalent to R5 `Composition.event` |
| Composition.event.code | - | DoesNotExistInTarget | R4B `Composition.event.code` does not appear in the target and has no mapping for `Composition`. |
| Composition.event.detail | Composition.event.detail | RelatedTo | R4B `Composition.event.detail` maps as RelatedTo to R5 `Composition.event.detail` - detail added a binding requirement - Example http://terminology.hl7.org/ValueSet/v3-ActCode; detail has change due to type change: R4B detail Reference has no equivalent or mapped type in R5 detail |
| Composition.event.extension | Composition.event.extension | RelatedTo | R4B `Composition.event.extension` maps as RelatedTo to R5 `Composition.event.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Composition.event.id | Composition.event.id | Equivalent | R4B `Composition.event.id` maps as Equivalent to R5 `Composition.event.id` |
| Composition.event.modifierExtension | Composition.event.modifierExtension | RelatedTo | R4B `Composition.event.modifierExtension` maps as RelatedTo to R5 `Composition.event.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Composition.event.period | Composition.event.period | Equivalent | R4B `Composition.event.period` maps as Equivalent to R5 `Composition.event.period` |
| Composition.extension | Composition.extension | RelatedTo | R4B `Composition.extension` maps as RelatedTo to R5 `Composition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Composition.id | Composition.id | Equivalent | R4B `Composition.id` maps as Equivalent to R5 `Composition.id` |
| Composition.identifier | Composition.identifier | RelatedTo | R4B `Composition.identifier` maps as RelatedTo to R5 `Composition.identifier` - identifier changed from scalar to array (max cardinality from 1 to *) |
| Composition.implicitRules | Composition.implicitRules | Equivalent | R4B `Composition.implicitRules` maps as Equivalent to R5 `Composition.implicitRules` |
| Composition.language | Composition.language | RelatedTo | R4B `Composition.language` maps as RelatedTo to R5 `Composition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Composition.meta | Composition.meta | Equivalent | R4B `Composition.meta` maps as Equivalent to R5 `Composition.meta` |
| Composition.modifierExtension | Composition.modifierExtension | RelatedTo | R4B `Composition.modifierExtension` maps as RelatedTo to R5 `Composition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Composition.relatesTo | Composition.relatesTo | SourceIsBroaderThanTarget | R4B `Composition.relatesTo` maps as SourceIsBroaderThanTarget to R5 `Composition.relatesTo` - relatesTo has change due to type change: R4B relatesTo BackboneElement has no equivalent or mapped type in R5 relatesTo |
| Composition.relatesTo.code | - | DoesNotExistInTarget | R4B `Composition.relatesTo.code` does not appear in the target and has no mapping for `Composition`. |
| Composition.relatesTo.extension | - | DoesNotExistInTarget | R4B `Composition.relatesTo.extension` does not appear in the target and has no mapping for `Composition`. |
| Composition.relatesTo.id | - | DoesNotExistInTarget | R4B `Composition.relatesTo.id` does not appear in the target and has no mapping for `Composition`. |
| Composition.relatesTo.modifierExtension | - | DoesNotExistInTarget | R4B `Composition.relatesTo.modifierExtension` does not appear in the target and has no mapping for `Composition`. |
| Composition.relatesTo.target[x] | - | DoesNotExistInTarget | R4B `Composition.relatesTo.target[x]` does not appear in the target and has no mapping for `Composition`. |
| Composition.section | Composition.section | Equivalent | R4B `Composition.section` maps as Equivalent to R5 `Composition.section` |
| Composition.section.author | Composition.section.author | Equivalent | R4B `Composition.section.author` maps as Equivalent to R5 `Composition.section.author` |
| Composition.section.code | Composition.section.code | Equivalent | R4B `Composition.section.code` maps as Equivalent to R5 `Composition.section.code` |
| Composition.section.emptyReason | Composition.section.emptyReason | Equivalent | R4B `Composition.section.emptyReason` maps as Equivalent to R5 `Composition.section.emptyReason` |
| Composition.section.entry | Composition.section.entry | Equivalent | R4B `Composition.section.entry` maps as Equivalent to R5 `Composition.section.entry` |
| Composition.section.extension | Composition.section.extension | RelatedTo | R4B `Composition.section.extension` maps as RelatedTo to R5 `Composition.section.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Composition.section.focus | Composition.section.focus | Equivalent | R4B `Composition.section.focus` maps as Equivalent to R5 `Composition.section.focus` |
| Composition.section.id | Composition.section.id | Equivalent | R4B `Composition.section.id` maps as Equivalent to R5 `Composition.section.id` |
| Composition.section.mode | - | DoesNotExistInTarget | R4B `Composition.section.mode` does not appear in the target and has no mapping for `Composition`. |
| Composition.section.modifierExtension | Composition.section.modifierExtension | RelatedTo | R4B `Composition.section.modifierExtension` maps as RelatedTo to R5 `Composition.section.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Composition.section.orderedBy | Composition.section.orderedBy | Equivalent | R4B `Composition.section.orderedBy` maps as Equivalent to R5 `Composition.section.orderedBy` |
| Composition.section.section | Composition.section.section | Equivalent | R4B `Composition.section.section` maps as Equivalent to R5 `Composition.section.section` |
| Composition.section.text | Composition.section.text | Equivalent | R4B `Composition.section.text` maps as Equivalent to R5 `Composition.section.text` |
| Composition.section.title | Composition.section.title | Equivalent | R4B `Composition.section.title` maps as Equivalent to R5 `Composition.section.title` |
| Composition.status | Composition.status | Equivalent | R4B `Composition.status` maps as Equivalent to R5 `Composition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/composition-status|4.3.0 and http://hl7.org/fhir/ValueSet/composition-status|5.0.0 (Equivalent) |
| Composition.subject | Composition.subject | RelatedTo | R4B `Composition.subject` maps as RelatedTo to R5 `Composition.subject` - subject changed from scalar to array (max cardinality from 1 to *) |
| Composition.text | Composition.text | Equivalent | R4B `Composition.text` maps as Equivalent to R5 `Composition.text` |
| Composition.title | Composition.title | Equivalent | R4B `Composition.title` maps as Equivalent to R5 `Composition.title` |
| Composition.type | Composition.type | Equivalent | R4B `Composition.type` maps as Equivalent to R5 `Composition.type` |

