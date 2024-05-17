Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DiagnosticReport |  | The findings and interpretation of diagnostic  tests performed on patients, groups of patients, devices, and locations, and/or specimens derived from these. The report includes clinical context such as requesting and provider information, and some mix of atomic results, images, textual and coded interpretations, and formatted representation of diagnostic reports. | 32 | 21 |
| Target | DiagnosticReport |  | The findings and interpretation of diagnostic tests performed on patients, groups of patients, products, substances, devices, and locations, and/or specimens derived from these. The report includes clinical context such as requesting provider information, and some mix of atomic results, images, textual and coded interpretations, and formatted representation of diagnostic reports. The report also includes non-clinical context such as batch analysis and stability reporting of products and substances. | 40 | 26 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 27 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DiagnosticReport | DiagnosticReport | Equivalent | R4B `DiagnosticReport` maps as Equivalent to R5 `DiagnosticReport` |
| DiagnosticReport.basedOn | DiagnosticReport.basedOn | Equivalent | R4B `DiagnosticReport.basedOn` maps as Equivalent to R5 `DiagnosticReport.basedOn` |
| DiagnosticReport.category | DiagnosticReport.category | Equivalent | R4B `DiagnosticReport.category` maps as Equivalent to R5 `DiagnosticReport.category` |
| DiagnosticReport.code | DiagnosticReport.code | Equivalent | R4B `DiagnosticReport.code` maps as Equivalent to R5 `DiagnosticReport.code` |
| DiagnosticReport.conclusion | DiagnosticReport.conclusion | SourceIsBroaderThanTarget | R4B `DiagnosticReport.conclusion` maps as SourceIsBroaderThanTarget to R5 `DiagnosticReport.conclusion` - conclusion has change due to type change: R4B conclusion string has no equivalent or mapped type in R5 conclusion |
| DiagnosticReport.conclusionCode | DiagnosticReport.conclusionCode | Equivalent | R4B `DiagnosticReport.conclusionCode` maps as Equivalent to R5 `DiagnosticReport.conclusionCode` |
| DiagnosticReport.contained | DiagnosticReport.contained | Equivalent | R4B `DiagnosticReport.contained` maps as Equivalent to R5 `DiagnosticReport.contained` |
| DiagnosticReport.effective[x] | DiagnosticReport.effective[x] | Equivalent | R4B `DiagnosticReport.effective[x]` maps as Equivalent to R5 `DiagnosticReport.effective[x]` |
| DiagnosticReport.encounter | DiagnosticReport.encounter | Equivalent | R4B `DiagnosticReport.encounter` maps as Equivalent to R5 `DiagnosticReport.encounter` |
| DiagnosticReport.extension | DiagnosticReport.extension | RelatedTo | R4B `DiagnosticReport.extension` maps as RelatedTo to R5 `DiagnosticReport.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DiagnosticReport.id | DiagnosticReport.id | Equivalent | R4B `DiagnosticReport.id` maps as Equivalent to R5 `DiagnosticReport.id` |
| DiagnosticReport.identifier | DiagnosticReport.identifier | Equivalent | R4B `DiagnosticReport.identifier` maps as Equivalent to R5 `DiagnosticReport.identifier` |
| DiagnosticReport.imagingStudy | - | DoesNotExistInTarget | R4B `DiagnosticReport.imagingStudy` does not appear in the target and has no mapping for `DiagnosticReport`. |
| DiagnosticReport.implicitRules | DiagnosticReport.implicitRules | Equivalent | R4B `DiagnosticReport.implicitRules` maps as Equivalent to R5 `DiagnosticReport.implicitRules` |
| DiagnosticReport.issued | DiagnosticReport.issued | Equivalent | R4B `DiagnosticReport.issued` maps as Equivalent to R5 `DiagnosticReport.issued` |
| DiagnosticReport.language | DiagnosticReport.language | RelatedTo | R4B `DiagnosticReport.language` maps as RelatedTo to R5 `DiagnosticReport.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| DiagnosticReport.media | DiagnosticReport.media | Equivalent | R4B `DiagnosticReport.media` maps as Equivalent to R5 `DiagnosticReport.media` |
| DiagnosticReport.media.comment | DiagnosticReport.media.comment | Equivalent | R4B `DiagnosticReport.media.comment` maps as Equivalent to R5 `DiagnosticReport.media.comment` |
| DiagnosticReport.media.extension | DiagnosticReport.media.extension | RelatedTo | R4B `DiagnosticReport.media.extension` maps as RelatedTo to R5 `DiagnosticReport.media.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DiagnosticReport.media.id | DiagnosticReport.media.id | Equivalent | R4B `DiagnosticReport.media.id` maps as Equivalent to R5 `DiagnosticReport.media.id` |
| DiagnosticReport.media.link | DiagnosticReport.media.link | RelatedTo | R4B `DiagnosticReport.media.link` maps as RelatedTo to R5 `DiagnosticReport.media.link` - link has change due to type change: R4B `link` `Reference` maps as RelatedTo for R5 `link` |
| DiagnosticReport.media.modifierExtension | DiagnosticReport.media.modifierExtension | RelatedTo | R4B `DiagnosticReport.media.modifierExtension` maps as RelatedTo to R5 `DiagnosticReport.media.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DiagnosticReport.meta | DiagnosticReport.meta | Equivalent | R4B `DiagnosticReport.meta` maps as Equivalent to R5 `DiagnosticReport.meta` |
| DiagnosticReport.modifierExtension | DiagnosticReport.modifierExtension | RelatedTo | R4B `DiagnosticReport.modifierExtension` maps as RelatedTo to R5 `DiagnosticReport.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DiagnosticReport.performer | DiagnosticReport.performer | Equivalent | R4B `DiagnosticReport.performer` maps as Equivalent to R5 `DiagnosticReport.performer` |
| DiagnosticReport.presentedForm | DiagnosticReport.presentedForm | RelatedTo | R4B `DiagnosticReport.presentedForm` maps as RelatedTo to R5 `DiagnosticReport.presentedForm` - presentedForm has change due to type change: R4B `presentedForm` `Attachment` maps as RelatedTo for R5 `presentedForm` |
| DiagnosticReport.result | DiagnosticReport.result | Equivalent | R4B `DiagnosticReport.result` maps as Equivalent to R5 `DiagnosticReport.result` |
| DiagnosticReport.resultsInterpreter | DiagnosticReport.resultsInterpreter | Equivalent | R4B `DiagnosticReport.resultsInterpreter` maps as Equivalent to R5 `DiagnosticReport.resultsInterpreter` |
| DiagnosticReport.specimen | DiagnosticReport.specimen | Equivalent | R4B `DiagnosticReport.specimen` maps as Equivalent to R5 `DiagnosticReport.specimen` |
| DiagnosticReport.status | DiagnosticReport.status | Equivalent | R4B `DiagnosticReport.status` maps as Equivalent to R5 `DiagnosticReport.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/diagnostic-report-status|4.3.0 and http://hl7.org/fhir/ValueSet/diagnostic-report-status|5.0.0 (codes match, though systems are different) |
| DiagnosticReport.subject | DiagnosticReport.subject | RelatedTo | R4B `DiagnosticReport.subject` maps as RelatedTo to R5 `DiagnosticReport.subject` - subject has change due to type change: R4B `subject` `Reference` maps as RelatedTo for R5 `subject` |
| DiagnosticReport.text | DiagnosticReport.text | Equivalent | R4B `DiagnosticReport.text` maps as Equivalent to R5 `DiagnosticReport.text` |

