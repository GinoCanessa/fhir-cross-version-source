Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DocumentReference |  | A reference to a document of any kind for any purpose. Provides metadata about the document so that the document can be discovered and managed. The scope of a document is any seralized object with a mime-type, so includes formal patient centric documents (CDA), cliical notes, scanned paper, and non-patient specific documents like policy text. | 45 | 28 |
| Target | DocumentReference |  | A reference to a document of any kind for any purpose. While the term “document” implies a more narrow focus, for this resource this “document” encompasses *any* serialized object with a mime-type, it includes formal patient-centric documents (CDA), clinical notes, scanned paper, non-patient specific documents like policy text, as well as a photo, video, or audio recording acquired or used in healthcare.  The DocumentReference resource provides metadata about the document so that the document can be discovered and managed.  The actual content may be inline base64 encoded data or provided by direct reference. | 52 | 32 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 13 |
Equivalent | 4 |
RelatedTo | 28 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DocumentReference | DocumentReference | Equivalent | R4B `DocumentReference` maps as Equivalent to R5 `DocumentReference` |
| DocumentReference.authenticator | - | DoesNotExistInTarget | R4B `DocumentReference.authenticator` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.author | DocumentReference.author | SourceIsNarrowerThanTarget | R4B `DocumentReference.author` maps as SourceIsNarrowerThanTarget to R5 `DocumentReference.author` - author has change due to type change: R4B `author` `Reference` maps as SourceIsNarrowerThanTarget for R5 `author` |
| DocumentReference.category | DocumentReference.category | Equivalent | R4B `DocumentReference.category` maps as Equivalent to R5 `DocumentReference.category` |
| DocumentReference.contained | DocumentReference.contained | Equivalent | R4B `DocumentReference.contained` maps as Equivalent to R5 `DocumentReference.contained` |
| DocumentReference.content | DocumentReference.content | Equivalent | R4B `DocumentReference.content` maps as Equivalent to R5 `DocumentReference.content` |
| DocumentReference.content.attachment | DocumentReference.content.attachment | RelatedTo | R4B `DocumentReference.content.attachment` maps as RelatedTo to R5 `DocumentReference.content.attachment` - attachment has change due to type change: R4B `attachment` `Attachment` maps as RelatedTo for R5 `attachment` |
| DocumentReference.content.extension | DocumentReference.content.extension | RelatedTo | R4B `DocumentReference.content.extension` maps as RelatedTo to R5 `DocumentReference.content.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DocumentReference.content.format | - | DoesNotExistInTarget | R4B `DocumentReference.content.format` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.content.id | DocumentReference.content.id | Equivalent | R4B `DocumentReference.content.id` maps as Equivalent to R5 `DocumentReference.content.id` |
| DocumentReference.content.modifierExtension | DocumentReference.content.modifierExtension | RelatedTo | R4B `DocumentReference.content.modifierExtension` maps as RelatedTo to R5 `DocumentReference.content.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DocumentReference.context | DocumentReference.context | RelatedTo | R4B `DocumentReference.context` maps as RelatedTo to R5 `DocumentReference.context` - context changed from scalar to array (max cardinality from 1 to *); context has change due to type change: R4B context BackboneElement has no equivalent or mapped type in R5 context |
| DocumentReference.context.encounter | - | DoesNotExistInTarget | R4B `DocumentReference.context.encounter` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.context.event | - | DoesNotExistInTarget | R4B `DocumentReference.context.event` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.context.extension | - | DoesNotExistInTarget | R4B `DocumentReference.context.extension` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.context.facilityType | - | DoesNotExistInTarget | R4B `DocumentReference.context.facilityType` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.context.id | - | DoesNotExistInTarget | R4B `DocumentReference.context.id` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.context.modifierExtension | - | DoesNotExistInTarget | R4B `DocumentReference.context.modifierExtension` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.context.period | - | DoesNotExistInTarget | R4B `DocumentReference.context.period` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.context.practiceSetting | - | DoesNotExistInTarget | R4B `DocumentReference.context.practiceSetting` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.context.related | - | DoesNotExistInTarget | R4B `DocumentReference.context.related` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.context.sourcePatientInfo | - | DoesNotExistInTarget | R4B `DocumentReference.context.sourcePatientInfo` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.custodian | DocumentReference.custodian | Equivalent | R4B `DocumentReference.custodian` maps as Equivalent to R5 `DocumentReference.custodian` |
| DocumentReference.date | DocumentReference.date | Equivalent | R4B `DocumentReference.date` maps as Equivalent to R5 `DocumentReference.date` |
| DocumentReference.description | DocumentReference.description | SourceIsBroaderThanTarget | R4B `DocumentReference.description` maps as SourceIsBroaderThanTarget to R5 `DocumentReference.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| DocumentReference.docStatus | DocumentReference.docStatus | Equivalent | R4B `DocumentReference.docStatus` maps as Equivalent to R5 `DocumentReference.docStatus` - docStatus has compatible required binding for code type: http://hl7.org/fhir/ValueSet/composition-status|4.3.0 and http://hl7.org/fhir/ValueSet/composition-status|5.0.0 (Equivalent) |
| DocumentReference.extension | DocumentReference.extension | RelatedTo | R4B `DocumentReference.extension` maps as RelatedTo to R5 `DocumentReference.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DocumentReference.id | DocumentReference.id | Equivalent | R4B `DocumentReference.id` maps as Equivalent to R5 `DocumentReference.id` |
| DocumentReference.identifier | DocumentReference.identifier | Equivalent | R4B `DocumentReference.identifier` maps as Equivalent to R5 `DocumentReference.identifier` |
| DocumentReference.implicitRules | DocumentReference.implicitRules | Equivalent | R4B `DocumentReference.implicitRules` maps as Equivalent to R5 `DocumentReference.implicitRules` |
| DocumentReference.language | DocumentReference.language | RelatedTo | R4B `DocumentReference.language` maps as RelatedTo to R5 `DocumentReference.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| DocumentReference.masterIdentifier | - | DoesNotExistInTarget | R4B `DocumentReference.masterIdentifier` does not appear in the target and has no mapping for `DocumentReference`. |
| DocumentReference.meta | DocumentReference.meta | Equivalent | R4B `DocumentReference.meta` maps as Equivalent to R5 `DocumentReference.meta` |
| DocumentReference.modifierExtension | DocumentReference.modifierExtension | RelatedTo | R4B `DocumentReference.modifierExtension` maps as RelatedTo to R5 `DocumentReference.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DocumentReference.relatesTo | DocumentReference.relatesTo | Equivalent | R4B `DocumentReference.relatesTo` maps as Equivalent to R5 `DocumentReference.relatesTo` |
| DocumentReference.relatesTo.code | DocumentReference.relatesTo.code | RelatedTo | R4B `DocumentReference.relatesTo.code` maps as RelatedTo to R5 `DocumentReference.relatesTo.code` - code changed the binding strength from Required to Extensible; code has change due to type change: R4B code code has no equivalent or mapped type in R5 code |
| DocumentReference.relatesTo.extension | DocumentReference.relatesTo.extension | RelatedTo | R4B `DocumentReference.relatesTo.extension` maps as RelatedTo to R5 `DocumentReference.relatesTo.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DocumentReference.relatesTo.id | DocumentReference.relatesTo.id | Equivalent | R4B `DocumentReference.relatesTo.id` maps as Equivalent to R5 `DocumentReference.relatesTo.id` |
| DocumentReference.relatesTo.modifierExtension | DocumentReference.relatesTo.modifierExtension | RelatedTo | R4B `DocumentReference.relatesTo.modifierExtension` maps as RelatedTo to R5 `DocumentReference.relatesTo.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DocumentReference.relatesTo.target | DocumentReference.relatesTo.target | Equivalent | R4B `DocumentReference.relatesTo.target` maps as Equivalent to R5 `DocumentReference.relatesTo.target` |
| DocumentReference.securityLabel | DocumentReference.securityLabel | RelatedTo | R4B `DocumentReference.securityLabel` maps as RelatedTo to R5 `DocumentReference.securityLabel` - securityLabel changed the binding strength from Extensible to Example |
| DocumentReference.status | DocumentReference.status | Equivalent | R4B `DocumentReference.status` maps as Equivalent to R5 `DocumentReference.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/document-reference-status|4.3.0 and http://hl7.org/fhir/ValueSet/document-reference-status|5.0.0 (Equivalent) |
| DocumentReference.subject | DocumentReference.subject | RelatedTo | R4B `DocumentReference.subject` maps as RelatedTo to R5 `DocumentReference.subject` - subject has change due to type change: R4B `subject` `Reference` maps as RelatedTo for R5 `subject` |
| DocumentReference.text | DocumentReference.text | Equivalent | R4B `DocumentReference.text` maps as Equivalent to R5 `DocumentReference.text` |
| DocumentReference.type | DocumentReference.type | Equivalent | R4B `DocumentReference.type` maps as Equivalent to R5 `DocumentReference.type` |

