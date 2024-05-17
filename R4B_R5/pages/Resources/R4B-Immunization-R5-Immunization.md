Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Immunization |  | Describes the event of a patient being administered a vaccine or a record of an immunization as reported by a patient, a clinician or another party. | 63 | 43 |
| Target | Immunization |  | Describes the event of a patient being administered a vaccine or a record of an immunization as reported by a patient, a clinician or another party. | 61 | 41 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 15 |
Equivalent | 4 |
RelatedTo | 44 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Immunization | Immunization | Equivalent | R4B `Immunization` maps as Equivalent to R5 `Immunization` |
| Immunization.contained | Immunization.contained | Equivalent | R4B `Immunization.contained` maps as Equivalent to R5 `Immunization.contained` |
| Immunization.doseQuantity | Immunization.doseQuantity | Equivalent | R4B `Immunization.doseQuantity` maps as Equivalent to R5 `Immunization.doseQuantity` |
| Immunization.education | - | DoesNotExistInTarget | R4B `Immunization.education` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.education.documentType | - | DoesNotExistInTarget | R4B `Immunization.education.documentType` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.education.extension | - | DoesNotExistInTarget | R4B `Immunization.education.extension` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.education.id | - | DoesNotExistInTarget | R4B `Immunization.education.id` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.education.modifierExtension | - | DoesNotExistInTarget | R4B `Immunization.education.modifierExtension` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.education.presentationDate | - | DoesNotExistInTarget | R4B `Immunization.education.presentationDate` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.education.publicationDate | - | DoesNotExistInTarget | R4B `Immunization.education.publicationDate` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.education.reference | - | DoesNotExistInTarget | R4B `Immunization.education.reference` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.encounter | Immunization.encounter | Equivalent | R4B `Immunization.encounter` maps as Equivalent to R5 `Immunization.encounter` |
| Immunization.expirationDate | Immunization.expirationDate | Equivalent | R4B `Immunization.expirationDate` maps as Equivalent to R5 `Immunization.expirationDate` |
| Immunization.extension | Immunization.extension | RelatedTo | R4B `Immunization.extension` maps as RelatedTo to R5 `Immunization.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Immunization.fundingSource | Immunization.fundingSource | Equivalent | R4B `Immunization.fundingSource` maps as Equivalent to R5 `Immunization.fundingSource` |
| Immunization.id | Immunization.id | Equivalent | R4B `Immunization.id` maps as Equivalent to R5 `Immunization.id` |
| Immunization.identifier | Immunization.identifier | Equivalent | R4B `Immunization.identifier` maps as Equivalent to R5 `Immunization.identifier` |
| Immunization.implicitRules | Immunization.implicitRules | Equivalent | R4B `Immunization.implicitRules` maps as Equivalent to R5 `Immunization.implicitRules` |
| Immunization.isSubpotent | Immunization.isSubpotent | Equivalent | R4B `Immunization.isSubpotent` maps as Equivalent to R5 `Immunization.isSubpotent` |
| Immunization.language | Immunization.language | RelatedTo | R4B `Immunization.language` maps as RelatedTo to R5 `Immunization.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Immunization.location | Immunization.location | Equivalent | R4B `Immunization.location` maps as Equivalent to R5 `Immunization.location` |
| Immunization.lotNumber | Immunization.lotNumber | Equivalent | R4B `Immunization.lotNumber` maps as Equivalent to R5 `Immunization.lotNumber` |
| Immunization.manufacturer | Immunization.manufacturer | SourceIsBroaderThanTarget | R4B `Immunization.manufacturer` maps as SourceIsBroaderThanTarget to R5 `Immunization.manufacturer` - manufacturer has change due to type change: R4B manufacturer Reference has no equivalent or mapped type in R5 manufacturer |
| Immunization.meta | Immunization.meta | Equivalent | R4B `Immunization.meta` maps as Equivalent to R5 `Immunization.meta` |
| Immunization.modifierExtension | Immunization.modifierExtension | RelatedTo | R4B `Immunization.modifierExtension` maps as RelatedTo to R5 `Immunization.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Immunization.note | Immunization.note | SourceIsNarrowerThanTarget | R4B `Immunization.note` maps as SourceIsNarrowerThanTarget to R5 `Immunization.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Immunization.occurrence[x] | Immunization.occurrence[x] | Equivalent | R4B `Immunization.occurrence[x]` maps as Equivalent to R5 `Immunization.occurrence[x]` |
| Immunization.patient | Immunization.patient | Equivalent | R4B `Immunization.patient` maps as Equivalent to R5 `Immunization.patient` |
| Immunization.performer | Immunization.performer | Equivalent | R4B `Immunization.performer` maps as Equivalent to R5 `Immunization.performer` |
| Immunization.performer.actor | Immunization.performer.actor | SourceIsNarrowerThanTarget | R4B `Immunization.performer.actor` maps as SourceIsNarrowerThanTarget to R5 `Immunization.performer.actor` - actor has change due to type change: R4B `actor` `Reference` maps as SourceIsNarrowerThanTarget for R5 `actor` |
| Immunization.performer.extension | Immunization.performer.extension | RelatedTo | R4B `Immunization.performer.extension` maps as RelatedTo to R5 `Immunization.performer.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Immunization.performer.function | Immunization.performer.function | Equivalent | R4B `Immunization.performer.function` maps as Equivalent to R5 `Immunization.performer.function` |
| Immunization.performer.id | Immunization.performer.id | Equivalent | R4B `Immunization.performer.id` maps as Equivalent to R5 `Immunization.performer.id` |
| Immunization.performer.modifierExtension | Immunization.performer.modifierExtension | RelatedTo | R4B `Immunization.performer.modifierExtension` maps as RelatedTo to R5 `Immunization.performer.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Immunization.primarySource | Immunization.primarySource | Equivalent | R4B `Immunization.primarySource` maps as Equivalent to R5 `Immunization.primarySource` |
| Immunization.programEligibility | Immunization.programEligibility | RelatedTo | R4B `Immunization.programEligibility` maps as RelatedTo to R5 `Immunization.programEligibility` - programEligibility removed a binding requirement - Example http://hl7.org/fhir/ValueSet/immunization-program-eligibility; programEligibility has change due to type change: R4B programEligibility CodeableConcept has no equivalent or mapped type in R5 programEligibility |
| Immunization.protocolApplied | Immunization.protocolApplied | Equivalent | R4B `Immunization.protocolApplied` maps as Equivalent to R5 `Immunization.protocolApplied` |
| Immunization.protocolApplied.authority | Immunization.protocolApplied.authority | Equivalent | R4B `Immunization.protocolApplied.authority` maps as Equivalent to R5 `Immunization.protocolApplied.authority` |
| Immunization.protocolApplied.doseNumber[x] | - | DoesNotExistInTarget | R4B `Immunization.protocolApplied.doseNumber[x]` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.protocolApplied.extension | Immunization.protocolApplied.extension | RelatedTo | R4B `Immunization.protocolApplied.extension` maps as RelatedTo to R5 `Immunization.protocolApplied.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Immunization.protocolApplied.id | Immunization.protocolApplied.id | Equivalent | R4B `Immunization.protocolApplied.id` maps as Equivalent to R5 `Immunization.protocolApplied.id` |
| Immunization.protocolApplied.modifierExtension | Immunization.protocolApplied.modifierExtension | RelatedTo | R4B `Immunization.protocolApplied.modifierExtension` maps as RelatedTo to R5 `Immunization.protocolApplied.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Immunization.protocolApplied.series | Immunization.protocolApplied.series | Equivalent | R4B `Immunization.protocolApplied.series` maps as Equivalent to R5 `Immunization.protocolApplied.series` |
| Immunization.protocolApplied.seriesDoses[x] | - | DoesNotExistInTarget | R4B `Immunization.protocolApplied.seriesDoses[x]` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.protocolApplied.targetDisease | Immunization.protocolApplied.targetDisease | Equivalent | R4B `Immunization.protocolApplied.targetDisease` maps as Equivalent to R5 `Immunization.protocolApplied.targetDisease` |
| Immunization.reaction | Immunization.reaction | Equivalent | R4B `Immunization.reaction` maps as Equivalent to R5 `Immunization.reaction` |
| Immunization.reaction.date | Immunization.reaction.date | Equivalent | R4B `Immunization.reaction.date` maps as Equivalent to R5 `Immunization.reaction.date` |
| Immunization.reaction.detail | - | DoesNotExistInTarget | R4B `Immunization.reaction.detail` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.reaction.extension | Immunization.reaction.extension | RelatedTo | R4B `Immunization.reaction.extension` maps as RelatedTo to R5 `Immunization.reaction.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Immunization.reaction.id | Immunization.reaction.id | Equivalent | R4B `Immunization.reaction.id` maps as Equivalent to R5 `Immunization.reaction.id` |
| Immunization.reaction.modifierExtension | Immunization.reaction.modifierExtension | RelatedTo | R4B `Immunization.reaction.modifierExtension` maps as RelatedTo to R5 `Immunization.reaction.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Immunization.reaction.reported | Immunization.reaction.reported | Equivalent | R4B `Immunization.reaction.reported` maps as Equivalent to R5 `Immunization.reaction.reported` |
| Immunization.reasonCode | - | DoesNotExistInTarget | R4B `Immunization.reasonCode` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.reasonReference | - | DoesNotExistInTarget | R4B `Immunization.reasonReference` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.recorded | - | DoesNotExistInTarget | R4B `Immunization.recorded` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.reportOrigin | - | DoesNotExistInTarget | R4B `Immunization.reportOrigin` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.route | Immunization.route | Equivalent | R4B `Immunization.route` maps as Equivalent to R5 `Immunization.route` |
| Immunization.site | Immunization.site | Equivalent | R4B `Immunization.site` maps as Equivalent to R5 `Immunization.site` |
| Immunization.status | Immunization.status | Equivalent | R4B `Immunization.status` maps as Equivalent to R5 `Immunization.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/immunization-status|4.3.0 and http://hl7.org/fhir/ValueSet/immunization-status|5.0.0 (Equivalent) |
| Immunization.statusReason | Immunization.statusReason | Equivalent | R4B `Immunization.statusReason` maps as Equivalent to R5 `Immunization.statusReason` |
| Immunization.subpotentReason | Immunization.subpotentReason | Equivalent | R4B `Immunization.subpotentReason` maps as Equivalent to R5 `Immunization.subpotentReason` |
| Immunization.text | Immunization.text | Equivalent | R4B `Immunization.text` maps as Equivalent to R5 `Immunization.text` |
| Immunization.vaccineCode | Immunization.vaccineCode | Equivalent | R4B `Immunization.vaccineCode` maps as Equivalent to R5 `Immunization.vaccineCode` |

