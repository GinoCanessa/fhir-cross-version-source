Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DiagnosticReport |  | The findings and interpretation of diagnostic tests performed on patients, groups of patients, products, substances, devices, and locations, and/or specimens derived from these. The report includes clinical context such as requesting provider information, and some mix of atomic results, images, textual and coded interpretations, and formatted representation of diagnostic reports. The report also includes non-clinical context such as batch analysis and stability reporting of products and substances. | 40 | 26 |
| Target | DiagnosticReport |  | The findings and interpretation of diagnostic  tests performed on patients, groups of patients, devices, and locations, and/or specimens derived from these. The report includes clinical context such as requesting and provider information, and some mix of atomic results, images, textual and coded interpretations, and formatted representation of diagnostic reports. | 32 | 21 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 9 |
Equivalent | 4 |
RelatedTo | 27 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DiagnosticReport | DiagnosticReport | Equivalent | R5 `DiagnosticReport` maps as Equivalent to R4B `DiagnosticReport` |
| DiagnosticReport.basedOn | DiagnosticReport.basedOn | Equivalent | R5 `DiagnosticReport.basedOn` maps as Equivalent to R4B `DiagnosticReport.basedOn` |
| DiagnosticReport.category | DiagnosticReport.category | Equivalent | R5 `DiagnosticReport.category` maps as Equivalent to R4B `DiagnosticReport.category` |
| DiagnosticReport.code | DiagnosticReport.code | Equivalent | R5 `DiagnosticReport.code` maps as Equivalent to R4B `DiagnosticReport.code` |
| DiagnosticReport.composition | - | DoesNotExistInTarget | R5 `DiagnosticReport.composition` does not appear in the target and has no mapping for `DiagnosticReport`. |
| DiagnosticReport.conclusion | DiagnosticReport.conclusion | SourceIsBroaderThanTarget | R5 `DiagnosticReport.conclusion` maps as SourceIsBroaderThanTarget to R4B `DiagnosticReport.conclusion` - conclusion has change due to type change: R5 conclusion markdown has no equivalent or mapped type in R4B conclusion |
| DiagnosticReport.conclusionCode | DiagnosticReport.conclusionCode | Equivalent | R5 `DiagnosticReport.conclusionCode` maps as Equivalent to R4B `DiagnosticReport.conclusionCode` |
| DiagnosticReport.contained | DiagnosticReport.contained | Equivalent | R5 `DiagnosticReport.contained` maps as Equivalent to R4B `DiagnosticReport.contained` |
| DiagnosticReport.effective[x] | DiagnosticReport.effective[x] | Equivalent | R5 `DiagnosticReport.effective[x]` maps as Equivalent to R4B `DiagnosticReport.effective[x]` |
| DiagnosticReport.encounter | DiagnosticReport.encounter | Equivalent | R5 `DiagnosticReport.encounter` maps as Equivalent to R4B `DiagnosticReport.encounter` |
| DiagnosticReport.extension | DiagnosticReport.extension | SourceIsBroaderThanTarget | R5 `DiagnosticReport.extension` maps as SourceIsBroaderThanTarget to R4B `DiagnosticReport.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| DiagnosticReport.id | DiagnosticReport.id | Equivalent | R5 `DiagnosticReport.id` maps as Equivalent to R4B `DiagnosticReport.id` |
| DiagnosticReport.identifier | DiagnosticReport.identifier | Equivalent | R5 `DiagnosticReport.identifier` maps as Equivalent to R4B `DiagnosticReport.identifier` |
| DiagnosticReport.implicitRules | DiagnosticReport.implicitRules | Equivalent | R5 `DiagnosticReport.implicitRules` maps as Equivalent to R4B `DiagnosticReport.implicitRules` |
| DiagnosticReport.issued | DiagnosticReport.issued | Equivalent | R5 `DiagnosticReport.issued` maps as Equivalent to R4B `DiagnosticReport.issued` |
| DiagnosticReport.language | DiagnosticReport.language | RelatedTo | R5 `DiagnosticReport.language` maps as RelatedTo to R4B `DiagnosticReport.language` - language changed the binding strength from Required to Preferred |
| DiagnosticReport.media | DiagnosticReport.media | Equivalent | R5 `DiagnosticReport.media` maps as Equivalent to R4B `DiagnosticReport.media` |
| DiagnosticReport.media.comment | DiagnosticReport.media.comment | Equivalent | R5 `DiagnosticReport.media.comment` maps as Equivalent to R4B `DiagnosticReport.media.comment` |
| DiagnosticReport.media.extension | DiagnosticReport.media.extension | SourceIsBroaderThanTarget | R5 `DiagnosticReport.media.extension` maps as SourceIsBroaderThanTarget to R4B `DiagnosticReport.media.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| DiagnosticReport.media.id | DiagnosticReport.media.id | Equivalent | R5 `DiagnosticReport.media.id` maps as Equivalent to R4B `DiagnosticReport.media.id` |
| DiagnosticReport.media.link | DiagnosticReport.media.link | RelatedTo | R5 `DiagnosticReport.media.link` maps as RelatedTo to R4B `DiagnosticReport.media.link` - link has change due to type change: R5 `link` `Reference` maps as RelatedTo for R4B `link` |
| DiagnosticReport.media.modifierExtension | DiagnosticReport.media.modifierExtension | SourceIsBroaderThanTarget | R5 `DiagnosticReport.media.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `DiagnosticReport.media.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| DiagnosticReport.meta | DiagnosticReport.meta | Equivalent | R5 `DiagnosticReport.meta` maps as Equivalent to R4B `DiagnosticReport.meta` |
| DiagnosticReport.modifierExtension | DiagnosticReport.modifierExtension | SourceIsBroaderThanTarget | R5 `DiagnosticReport.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `DiagnosticReport.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| DiagnosticReport.note | - | DoesNotExistInTarget | R5 `DiagnosticReport.note` does not appear in the target and has no mapping for `DiagnosticReport`. |
| DiagnosticReport.performer | DiagnosticReport.performer | Equivalent | R5 `DiagnosticReport.performer` maps as Equivalent to R4B `DiagnosticReport.performer` |
| DiagnosticReport.presentedForm | DiagnosticReport.presentedForm | RelatedTo | R5 `DiagnosticReport.presentedForm` maps as RelatedTo to R4B `DiagnosticReport.presentedForm` - presentedForm has change due to type change: R5 `presentedForm` `Attachment` maps as RelatedTo for R4B `presentedForm` |
| DiagnosticReport.result | DiagnosticReport.result | Equivalent | R5 `DiagnosticReport.result` maps as Equivalent to R4B `DiagnosticReport.result` |
| DiagnosticReport.resultsInterpreter | DiagnosticReport.resultsInterpreter | Equivalent | R5 `DiagnosticReport.resultsInterpreter` maps as Equivalent to R4B `DiagnosticReport.resultsInterpreter` |
| DiagnosticReport.specimen | DiagnosticReport.specimen | Equivalent | R5 `DiagnosticReport.specimen` maps as Equivalent to R4B `DiagnosticReport.specimen` |
| DiagnosticReport.status | DiagnosticReport.status | SourceIsNarrowerThanTarget | R5 `DiagnosticReport.status` maps as SourceIsNarrowerThanTarget to R4B `DiagnosticReport.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/diagnostic-report-status|5.0.0 and http://hl7.org/fhir/ValueSet/diagnostic-report-status|4.3.0 (SourceIsNarrowerThanTarget) |
| DiagnosticReport.study | - | DoesNotExistInTarget | R5 `DiagnosticReport.study` does not appear in the target and has no mapping for `DiagnosticReport`. |
| DiagnosticReport.subject | DiagnosticReport.subject | RelatedTo | R5 `DiagnosticReport.subject` maps as RelatedTo to R4B `DiagnosticReport.subject` - subject has change due to type change: R5 `subject` `Reference` maps as RelatedTo for R4B `subject` |
| DiagnosticReport.supportingInfo | - | DoesNotExistInTarget | R5 `DiagnosticReport.supportingInfo` does not appear in the target and has no mapping for `DiagnosticReport`. |
| DiagnosticReport.supportingInfo.extension | - | DoesNotExistInTarget | R5 `DiagnosticReport.supportingInfo.extension` does not appear in the target and has no mapping for `DiagnosticReport`. |
| DiagnosticReport.supportingInfo.id | - | DoesNotExistInTarget | R5 `DiagnosticReport.supportingInfo.id` does not appear in the target and has no mapping for `DiagnosticReport`. |
| DiagnosticReport.supportingInfo.modifierExtension | - | DoesNotExistInTarget | R5 `DiagnosticReport.supportingInfo.modifierExtension` does not appear in the target and has no mapping for `DiagnosticReport`. |
| DiagnosticReport.supportingInfo.reference | - | DoesNotExistInTarget | R5 `DiagnosticReport.supportingInfo.reference` does not appear in the target and has no mapping for `DiagnosticReport`. |
| DiagnosticReport.supportingInfo.type | - | DoesNotExistInTarget | R5 `DiagnosticReport.supportingInfo.type` does not appear in the target and has no mapping for `DiagnosticReport`. |
| DiagnosticReport.text | DiagnosticReport.text | Equivalent | R5 `DiagnosticReport.text` maps as Equivalent to R4B `DiagnosticReport.text` |

