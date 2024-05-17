Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ResearchSubject |  | A physical entity which is the primary unit of operational and/or administrative interest in a study. | 17 | 9 |
| Target | ResearchSubject |  | A ResearchSubject is a participant or object which is the recipient of investigative activities in a research study. | 27 | 16 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 4 |
RelatedTo | 10 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ResearchSubject | ResearchSubject | Equivalent | R4B `ResearchSubject` maps as Equivalent to R5 `ResearchSubject` |
| ResearchSubject.actualArm | - | DoesNotExistInTarget | R4B `ResearchSubject.actualArm` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.assignedArm | - | DoesNotExistInTarget | R4B `ResearchSubject.assignedArm` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.consent | ResearchSubject.consent | RelatedTo | R4B `ResearchSubject.consent` maps as RelatedTo to R5 `ResearchSubject.consent` - consent changed from scalar to array (max cardinality from 1 to *) |
| ResearchSubject.contained | ResearchSubject.contained | Equivalent | R4B `ResearchSubject.contained` maps as Equivalent to R5 `ResearchSubject.contained` |
| ResearchSubject.extension | ResearchSubject.extension | RelatedTo | R4B `ResearchSubject.extension` maps as RelatedTo to R5 `ResearchSubject.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ResearchSubject.id | ResearchSubject.id | Equivalent | R4B `ResearchSubject.id` maps as Equivalent to R5 `ResearchSubject.id` |
| ResearchSubject.identifier | ResearchSubject.identifier | Equivalent | R4B `ResearchSubject.identifier` maps as Equivalent to R5 `ResearchSubject.identifier` |
| ResearchSubject.implicitRules | ResearchSubject.implicitRules | Equivalent | R4B `ResearchSubject.implicitRules` maps as Equivalent to R5 `ResearchSubject.implicitRules` |
| ResearchSubject.individual | - | DoesNotExistInTarget | R4B `ResearchSubject.individual` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.language | ResearchSubject.language | RelatedTo | R4B `ResearchSubject.language` maps as RelatedTo to R5 `ResearchSubject.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ResearchSubject.meta | ResearchSubject.meta | Equivalent | R4B `ResearchSubject.meta` maps as Equivalent to R5 `ResearchSubject.meta` |
| ResearchSubject.modifierExtension | ResearchSubject.modifierExtension | RelatedTo | R4B `ResearchSubject.modifierExtension` maps as RelatedTo to R5 `ResearchSubject.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ResearchSubject.period | ResearchSubject.period | Equivalent | R4B `ResearchSubject.period` maps as Equivalent to R5 `ResearchSubject.period` |
| ResearchSubject.status | ResearchSubject.status | Equivalent | R4B `ResearchSubject.status` maps as Equivalent to R5 `ResearchSubject.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/research-subject-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| ResearchSubject.study | ResearchSubject.study | Equivalent | R4B `ResearchSubject.study` maps as Equivalent to R5 `ResearchSubject.study` |
| ResearchSubject.text | ResearchSubject.text | Equivalent | R4B `ResearchSubject.text` maps as Equivalent to R5 `ResearchSubject.text` |

