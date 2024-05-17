Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ResearchStudy |  | A process where a researcher or organization plans and then executes a series of steps intended to increase the field of healthcare-related knowledge.  This includes studies of safety, efficacy, comparative effectiveness and other information about medications, devices, therapies and other interventional and investigative techniques.  A ResearchStudy involves the gathering of information about human or animal subjects. | 44 | 30 |
| Target | ResearchStudy |  | A scientific study of nature that sometimes includes processes involved in health and disease. For example, clinical trials are research studies that involve people. These studies may be related to new ways to screen, prevent, diagnose, and treat disease. They may also study certain outcomes and certain groups of people by looking at data collected in the past or future. | 89 | 60 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 14 |
Equivalent | 4 |
RelatedTo | 26 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ResearchStudy | ResearchStudy | Equivalent | R4B `ResearchStudy` maps as Equivalent to R5 `ResearchStudy` |
| ResearchStudy.arm | - | DoesNotExistInTarget | R4B `ResearchStudy.arm` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.arm.description | - | DoesNotExistInTarget | R4B `ResearchStudy.arm.description` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.arm.extension | - | DoesNotExistInTarget | R4B `ResearchStudy.arm.extension` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.arm.id | - | DoesNotExistInTarget | R4B `ResearchStudy.arm.id` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.arm.modifierExtension | - | DoesNotExistInTarget | R4B `ResearchStudy.arm.modifierExtension` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.arm.name | - | DoesNotExistInTarget | R4B `ResearchStudy.arm.name` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.arm.type | - | DoesNotExistInTarget | R4B `ResearchStudy.arm.type` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.category | - | DoesNotExistInTarget | R4B `ResearchStudy.category` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.condition | ResearchStudy.condition | Equivalent | R4B `ResearchStudy.condition` maps as Equivalent to R5 `ResearchStudy.condition` |
| ResearchStudy.contact | - | DoesNotExistInTarget | R4B `ResearchStudy.contact` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.contained | ResearchStudy.contained | Equivalent | R4B `ResearchStudy.contained` maps as Equivalent to R5 `ResearchStudy.contained` |
| ResearchStudy.description | ResearchStudy.description | Equivalent | R4B `ResearchStudy.description` maps as Equivalent to R5 `ResearchStudy.description` |
| ResearchStudy.enrollment | - | DoesNotExistInTarget | R4B `ResearchStudy.enrollment` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.extension | ResearchStudy.extension | RelatedTo | R4B `ResearchStudy.extension` maps as RelatedTo to R5 `ResearchStudy.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ResearchStudy.focus | ResearchStudy.focus | SourceIsBroaderThanTarget | R4B `ResearchStudy.focus` maps as SourceIsBroaderThanTarget to R5 `ResearchStudy.focus` - focus has change due to type change: R4B focus CodeableConcept has no equivalent or mapped type in R5 focus |
| ResearchStudy.id | ResearchStudy.id | Equivalent | R4B `ResearchStudy.id` maps as Equivalent to R5 `ResearchStudy.id` |
| ResearchStudy.identifier | ResearchStudy.identifier | Equivalent | R4B `ResearchStudy.identifier` maps as Equivalent to R5 `ResearchStudy.identifier` |
| ResearchStudy.implicitRules | ResearchStudy.implicitRules | Equivalent | R4B `ResearchStudy.implicitRules` maps as Equivalent to R5 `ResearchStudy.implicitRules` |
| ResearchStudy.keyword | ResearchStudy.keyword | Equivalent | R4B `ResearchStudy.keyword` maps as Equivalent to R5 `ResearchStudy.keyword` |
| ResearchStudy.language | ResearchStudy.language | RelatedTo | R4B `ResearchStudy.language` maps as RelatedTo to R5 `ResearchStudy.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ResearchStudy.location | - | DoesNotExistInTarget | R4B `ResearchStudy.location` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.meta | ResearchStudy.meta | Equivalent | R4B `ResearchStudy.meta` maps as Equivalent to R5 `ResearchStudy.meta` |
| ResearchStudy.modifierExtension | ResearchStudy.modifierExtension | RelatedTo | R4B `ResearchStudy.modifierExtension` maps as RelatedTo to R5 `ResearchStudy.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ResearchStudy.note | ResearchStudy.note | SourceIsNarrowerThanTarget | R4B `ResearchStudy.note` maps as SourceIsNarrowerThanTarget to R5 `ResearchStudy.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| ResearchStudy.objective | ResearchStudy.objective | Equivalent | R4B `ResearchStudy.objective` maps as Equivalent to R5 `ResearchStudy.objective` |
| ResearchStudy.objective.extension | ResearchStudy.objective.extension | RelatedTo | R4B `ResearchStudy.objective.extension` maps as RelatedTo to R5 `ResearchStudy.objective.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ResearchStudy.objective.id | ResearchStudy.objective.id | Equivalent | R4B `ResearchStudy.objective.id` maps as Equivalent to R5 `ResearchStudy.objective.id` |
| ResearchStudy.objective.modifierExtension | ResearchStudy.objective.modifierExtension | RelatedTo | R4B `ResearchStudy.objective.modifierExtension` maps as RelatedTo to R5 `ResearchStudy.objective.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ResearchStudy.objective.name | ResearchStudy.objective.name | Equivalent | R4B `ResearchStudy.objective.name` maps as Equivalent to R5 `ResearchStudy.objective.name` |
| ResearchStudy.objective.type | ResearchStudy.objective.type | Equivalent | R4B `ResearchStudy.objective.type` maps as Equivalent to R5 `ResearchStudy.objective.type` |
| ResearchStudy.partOf | ResearchStudy.partOf | Equivalent | R4B `ResearchStudy.partOf` maps as Equivalent to R5 `ResearchStudy.partOf` |
| ResearchStudy.period | ResearchStudy.period | Equivalent | R4B `ResearchStudy.period` maps as Equivalent to R5 `ResearchStudy.period` |
| ResearchStudy.phase | ResearchStudy.phase | Equivalent | R4B `ResearchStudy.phase` maps as Equivalent to R5 `ResearchStudy.phase` |
| ResearchStudy.primaryPurposeType | ResearchStudy.primaryPurposeType | RelatedTo | R4B `ResearchStudy.primaryPurposeType` maps as RelatedTo to R5 `ResearchStudy.primaryPurposeType` - primaryPurposeType changed the binding strength from Extensible to Preferred |
| ResearchStudy.principalInvestigator | - | DoesNotExistInTarget | R4B `ResearchStudy.principalInvestigator` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.protocol | ResearchStudy.protocol | Equivalent | R4B `ResearchStudy.protocol` maps as Equivalent to R5 `ResearchStudy.protocol` |
| ResearchStudy.reasonStopped | - | DoesNotExistInTarget | R4B `ResearchStudy.reasonStopped` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.relatedArtifact | ResearchStudy.relatedArtifact | Equivalent | R4B `ResearchStudy.relatedArtifact` maps as Equivalent to R5 `ResearchStudy.relatedArtifact` |
| ResearchStudy.site | ResearchStudy.site | SourceIsNarrowerThanTarget | R4B `ResearchStudy.site` maps as SourceIsNarrowerThanTarget to R5 `ResearchStudy.site` - site has change due to type change: R4B `site` `Reference` maps as SourceIsNarrowerThanTarget for R5 `site` |
| ResearchStudy.sponsor | - | DoesNotExistInTarget | R4B `ResearchStudy.sponsor` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.status | ResearchStudy.status | Equivalent | R4B `ResearchStudy.status` maps as Equivalent to R5 `ResearchStudy.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/research-study-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| ResearchStudy.text | ResearchStudy.text | Equivalent | R4B `ResearchStudy.text` maps as Equivalent to R5 `ResearchStudy.text` |
| ResearchStudy.title | ResearchStudy.title | Equivalent | R4B `ResearchStudy.title` maps as Equivalent to R5 `ResearchStudy.title` |

