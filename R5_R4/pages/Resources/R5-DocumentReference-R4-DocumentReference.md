Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DocumentReference |  | A reference to a document of any kind for any purpose. While the term “document” implies a more narrow focus, for this resource this “document” encompasses *any* serialized object with a mime-type, it includes formal patient-centric documents (CDA), clinical notes, scanned paper, non-patient specific documents like policy text, as well as a photo, video, or audio recording acquired or used in healthcare.  The DocumentReference resource provides metadata about the document so that the document can be discovered and managed.  The actual content may be inline base64 encoded data or provided by direct reference. | 52 | 32 |
| Target | DocumentReference |  | A reference to a document of any kind for any purpose. Provides metadata about the document so that the document can be discovered and managed. The scope of a document is any seralized object with a mime-type, so includes formal patient centric documents (CDA), cliical notes, scanned paper, and non-patient specific documents like policy text. | 45 | 28 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 17 |
Equivalent | 20 |
RelatedTo | 4 |
SourceIsBroaderThanTarget | 10 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DocumentReference | DocumentReference | Equivalent | R5 `DocumentReference` maps as Equivalent to R4 `DocumentReference` |
| DocumentReference.attester | - | DoesNotExistInTarget | R5 `DocumentReference.attester` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.attester.extension | - | DoesNotExistInTarget | R5 `DocumentReference.attester.extension` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.attester.id | - | DoesNotExistInTarget | R5 `DocumentReference.attester.id` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.attester.mode | - | DoesNotExistInTarget | R5 `DocumentReference.attester.mode` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.attester.modifierExtension | - | DoesNotExistInTarget | R5 `DocumentReference.attester.modifierExtension` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.attester.party | - | DoesNotExistInTarget | R5 `DocumentReference.attester.party` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.attester.time | - | DoesNotExistInTarget | R5 `DocumentReference.attester.time` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.author | DocumentReference.author | SourceIsBroaderThanTarget | R5 `DocumentReference.author` maps as SourceIsBroaderThanTarget to R4 `DocumentReference.author` - author has change due to type change: R5 `author` `Reference` maps as SourceIsBroaderThanTarget for R4 `author` |
| DocumentReference.basedOn | - | DoesNotExistInTarget | R5 `DocumentReference.basedOn` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.bodySite | - | DoesNotExistInTarget | R5 `DocumentReference.bodySite` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.category | DocumentReference.category | Equivalent | R5 `DocumentReference.category` maps as Equivalent to R4 `DocumentReference.category` |
| DocumentReference.contained | DocumentReference.contained | Equivalent | R5 `DocumentReference.contained` maps as Equivalent to R4 `DocumentReference.contained` |
| DocumentReference.content | DocumentReference.content | Equivalent | R5 `DocumentReference.content` maps as Equivalent to R4 `DocumentReference.content` |
| DocumentReference.content.attachment | DocumentReference.content.attachment | RelatedTo | R5 `DocumentReference.content.attachment` maps as RelatedTo to R4 `DocumentReference.content.attachment` - attachment has change due to type change: R5 `attachment` `Attachment` maps as RelatedTo for R4 `attachment` |
| DocumentReference.content.extension | DocumentReference.content.extension | SourceIsBroaderThanTarget | R5 `DocumentReference.content.extension` maps as SourceIsBroaderThanTarget to R4 `DocumentReference.content.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DocumentReference.content.id | DocumentReference.content.id | Equivalent | R5 `DocumentReference.content.id` maps as Equivalent to R4 `DocumentReference.content.id` |
| DocumentReference.content.modifierExtension | DocumentReference.content.modifierExtension | SourceIsBroaderThanTarget | R5 `DocumentReference.content.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DocumentReference.content.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DocumentReference.content.profile | - | DoesNotExistInTarget | R5 `DocumentReference.content.profile` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.content.profile.extension | - | DoesNotExistInTarget | R5 `DocumentReference.content.profile.extension` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.content.profile.id | - | DoesNotExistInTarget | R5 `DocumentReference.content.profile.id` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.content.profile.modifierExtension | - | DoesNotExistInTarget | R5 `DocumentReference.content.profile.modifierExtension` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.content.profile.value[x] | - | DoesNotExistInTarget | R5 `DocumentReference.content.profile.value[x]` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.context | DocumentReference.context | SourceIsBroaderThanTarget | R5 `DocumentReference.context` maps as SourceIsBroaderThanTarget to R4 `DocumentReference.context` - context changed from array to scalar (max cardinality from * to 1); context has change due to type change: R5 context Reference has no equivalent or mapped type in R4 context |
| DocumentReference.custodian | DocumentReference.custodian | Equivalent | R5 `DocumentReference.custodian` maps as Equivalent to R4 `DocumentReference.custodian` |
| DocumentReference.date | DocumentReference.date | Equivalent | R5 `DocumentReference.date` maps as Equivalent to R4 `DocumentReference.date` |
| DocumentReference.description | DocumentReference.description | SourceIsBroaderThanTarget | R5 `DocumentReference.description` maps as SourceIsBroaderThanTarget to R4 `DocumentReference.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4 description |
| DocumentReference.docStatus | DocumentReference.docStatus | RelatedTo | R5 `DocumentReference.docStatus` maps as RelatedTo to R4 `DocumentReference.docStatus` - docStatus has INCOMPATIBLE required binding for code type: http://hl7.org/fhir/ValueSet/composition-status|5.0.0 and http://hl7.org/fhir/ValueSet/composition-status|4.0.1; docStatus has change due to type change: R5 `docStatus` `code` maps as RelatedTo for R4 `docStatus` |
| DocumentReference.event | - | DoesNotExistInTarget | R5 `DocumentReference.event` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.extension | DocumentReference.extension | SourceIsBroaderThanTarget | R5 `DocumentReference.extension` maps as SourceIsBroaderThanTarget to R4 `DocumentReference.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DocumentReference.facilityType | DocumentReference.context.facilityType | Equivalent | R5 `DocumentReference.facilityType` maps as Equivalent to R4 `DocumentReference.context.facilityType` |
| DocumentReference.id | DocumentReference.id | Equivalent | R5 `DocumentReference.id` maps as Equivalent to R4 `DocumentReference.id` |
| DocumentReference.identifier | DocumentReference.identifier | Equivalent | R5 `DocumentReference.identifier` maps as Equivalent to R4 `DocumentReference.identifier` |
| DocumentReference.implicitRules | DocumentReference.implicitRules | Equivalent | R5 `DocumentReference.implicitRules` maps as Equivalent to R4 `DocumentReference.implicitRules` |
| DocumentReference.language | DocumentReference.language | SourceIsNarrowerThanTarget | R5 `DocumentReference.language` maps as SourceIsNarrowerThanTarget to R4 `DocumentReference.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| DocumentReference.meta | DocumentReference.meta | Equivalent | R5 `DocumentReference.meta` maps as Equivalent to R4 `DocumentReference.meta` |
| DocumentReference.modality | - | DoesNotExistInTarget | R5 `DocumentReference.modality` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.modifierExtension | DocumentReference.modifierExtension | SourceIsBroaderThanTarget | R5 `DocumentReference.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DocumentReference.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DocumentReference.period | DocumentReference.context.period | Equivalent | R5 `DocumentReference.period` maps as Equivalent to R4 `DocumentReference.context.period` |
| DocumentReference.practiceSetting | DocumentReference.context.practiceSetting | Equivalent | R5 `DocumentReference.practiceSetting` maps as Equivalent to R4 `DocumentReference.context.practiceSetting` |
| DocumentReference.relatesTo | DocumentReference.relatesTo | Equivalent | R5 `DocumentReference.relatesTo` maps as Equivalent to R4 `DocumentReference.relatesTo` |
| DocumentReference.relatesTo.code | DocumentReference.relatesTo.code | RelatedTo | R5 `DocumentReference.relatesTo.code` maps as RelatedTo to R4 `DocumentReference.relatesTo.code` - code made the binding required (from Extensible) for http://hl7.org/fhir/ValueSet/document-relationship-type|4.0.1; code has change due to type change: R5 code CodeableConcept has no equivalent or mapped type in R4 code |
| DocumentReference.relatesTo.extension | DocumentReference.relatesTo.extension | SourceIsBroaderThanTarget | R5 `DocumentReference.relatesTo.extension` maps as SourceIsBroaderThanTarget to R4 `DocumentReference.relatesTo.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DocumentReference.relatesTo.id | DocumentReference.relatesTo.id | Equivalent | R5 `DocumentReference.relatesTo.id` maps as Equivalent to R4 `DocumentReference.relatesTo.id` |
| DocumentReference.relatesTo.modifierExtension | DocumentReference.relatesTo.modifierExtension | SourceIsBroaderThanTarget | R5 `DocumentReference.relatesTo.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DocumentReference.relatesTo.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DocumentReference.relatesTo.target | DocumentReference.relatesTo.target | Equivalent | R5 `DocumentReference.relatesTo.target` maps as Equivalent to R4 `DocumentReference.relatesTo.target` |
| DocumentReference.securityLabel | DocumentReference.securityLabel | SourceIsBroaderThanTarget | R5 `DocumentReference.securityLabel` maps as SourceIsBroaderThanTarget to R4 `DocumentReference.securityLabel` - securityLabel changed the binding strength from Example to Extensible; securityLabel has change due to type change: R5 `securityLabel` `CodeableConcept` maps as SourceIsBroaderThanTarget for R4 `securityLabel` |
| DocumentReference.status | DocumentReference.status | Equivalent | R5 `DocumentReference.status` maps as Equivalent to R4 `DocumentReference.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/document-reference-status|5.0.0 and http://hl7.org/fhir/ValueSet/document-reference-status|4.0.1 (Equivalent) |
| DocumentReference.subject | DocumentReference.subject | RelatedTo | R5 `DocumentReference.subject` maps as RelatedTo to R4 `DocumentReference.subject` - subject has change due to type change: R5 `subject` `Reference` maps as RelatedTo for R4 `subject` |
| DocumentReference.text | DocumentReference.text | Equivalent | R5 `DocumentReference.text` maps as Equivalent to R4 `DocumentReference.text` |
| DocumentReference.type | DocumentReference.type | Equivalent | R5 `DocumentReference.type` maps as Equivalent to R4 `DocumentReference.type` |
| DocumentReference.version | - | DoesNotExistInTarget | R5 `DocumentReference.version` does not appear in the target and has no mapping for `DocumentReference`. |

