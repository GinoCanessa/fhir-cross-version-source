Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Immunization |  | Describes the event of a patient being administered a vaccine or a record of an immunization as reported by a patient, a clinician or another party. | 61 | 41 |
| Target | Immunization |  | Describes the event of a patient being administered a vaccine or a record of an immunization as reported by a patient, a clinician or another party. | 63 | 43 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 9 |
Equivalent | 37 |
RelatedTo | 1 |
SourceIsBroaderThanTarget | 13 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Immunization | Immunization | Equivalent | R5 `Immunization` maps as Equivalent to R4 `Immunization` |
| Immunization.administeredProduct | - | DoesNotExistInTarget | R5 `Immunization.administeredProduct` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.basedOn | - | DoesNotExistInTarget | R5 `Immunization.basedOn` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.contained | Immunization.contained | Equivalent | R5 `Immunization.contained` maps as Equivalent to R4 `Immunization.contained` |
| Immunization.doseQuantity | Immunization.doseQuantity | Equivalent | R5 `Immunization.doseQuantity` maps as Equivalent to R4 `Immunization.doseQuantity` |
| Immunization.encounter | Immunization.encounter | Equivalent | R5 `Immunization.encounter` maps as Equivalent to R4 `Immunization.encounter` |
| Immunization.expirationDate | Immunization.expirationDate | Equivalent | R5 `Immunization.expirationDate` maps as Equivalent to R4 `Immunization.expirationDate` |
| Immunization.extension | Immunization.extension | SourceIsBroaderThanTarget | R5 `Immunization.extension` maps as SourceIsBroaderThanTarget to R4 `Immunization.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Immunization.fundingSource | Immunization.fundingSource | Equivalent | R5 `Immunization.fundingSource` maps as Equivalent to R4 `Immunization.fundingSource` |
| Immunization.id | Immunization.id | Equivalent | R5 `Immunization.id` maps as Equivalent to R4 `Immunization.id` |
| Immunization.identifier | Immunization.identifier | Equivalent | R5 `Immunization.identifier` maps as Equivalent to R4 `Immunization.identifier` |
| Immunization.implicitRules | Immunization.implicitRules | Equivalent | R5 `Immunization.implicitRules` maps as Equivalent to R4 `Immunization.implicitRules` |
| Immunization.informationSource | - | DoesNotExistInTarget | R5 `Immunization.informationSource` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.isSubpotent | Immunization.isSubpotent | Equivalent | R5 `Immunization.isSubpotent` maps as Equivalent to R4 `Immunization.isSubpotent` |
| Immunization.language | Immunization.language | SourceIsNarrowerThanTarget | R5 `Immunization.language` maps as SourceIsNarrowerThanTarget to R4 `Immunization.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Immunization.location | Immunization.location | Equivalent | R5 `Immunization.location` maps as Equivalent to R4 `Immunization.location` |
| Immunization.lotNumber | Immunization.lotNumber | Equivalent | R5 `Immunization.lotNumber` maps as Equivalent to R4 `Immunization.lotNumber` |
| Immunization.manufacturer | Immunization.manufacturer | SourceIsBroaderThanTarget | R5 `Immunization.manufacturer` maps as SourceIsBroaderThanTarget to R4 `Immunization.manufacturer` - manufacturer has change due to type change: R5 manufacturer CodeableReference has no equivalent or mapped type in R4 manufacturer |
| Immunization.meta | Immunization.meta | Equivalent | R5 `Immunization.meta` maps as Equivalent to R4 `Immunization.meta` |
| Immunization.modifierExtension | Immunization.modifierExtension | SourceIsBroaderThanTarget | R5 `Immunization.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Immunization.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Immunization.note | Immunization.note | SourceIsBroaderThanTarget | R5 `Immunization.note` maps as SourceIsBroaderThanTarget to R4 `Immunization.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| Immunization.occurrence[x] | Immunization.occurrence[x] | Equivalent | R5 `Immunization.occurrence[x]` maps as Equivalent to R4 `Immunization.occurrence[x]` |
| Immunization.patient | Immunization.patient | Equivalent | R5 `Immunization.patient` maps as Equivalent to R4 `Immunization.patient` |
| Immunization.performer | Immunization.performer | Equivalent | R5 `Immunization.performer` maps as Equivalent to R4 `Immunization.performer` |
| Immunization.performer.actor | Immunization.performer.actor | SourceIsBroaderThanTarget | R5 `Immunization.performer.actor` maps as SourceIsBroaderThanTarget to R4 `Immunization.performer.actor` - actor has change due to type change: R5 `actor` `Reference` maps as SourceIsBroaderThanTarget for R4 `actor` |
| Immunization.performer.extension | Immunization.performer.extension | SourceIsBroaderThanTarget | R5 `Immunization.performer.extension` maps as SourceIsBroaderThanTarget to R4 `Immunization.performer.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Immunization.performer.function | Immunization.performer.function | Equivalent | R5 `Immunization.performer.function` maps as Equivalent to R4 `Immunization.performer.function` |
| Immunization.performer.id | Immunization.performer.id | Equivalent | R5 `Immunization.performer.id` maps as Equivalent to R4 `Immunization.performer.id` |
| Immunization.performer.modifierExtension | Immunization.performer.modifierExtension | SourceIsBroaderThanTarget | R5 `Immunization.performer.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Immunization.performer.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Immunization.primarySource | Immunization.primarySource | Equivalent | R5 `Immunization.primarySource` maps as Equivalent to R4 `Immunization.primarySource` |
| Immunization.programEligibility | Immunization.programEligibility | SourceIsBroaderThanTarget | R5 `Immunization.programEligibility` maps as SourceIsBroaderThanTarget to R4 `Immunization.programEligibility` - programEligibility added a binding requirement - Example http://hl7.org/fhir/ValueSet/immunization-program-eligibility; programEligibility has change due to type change: R5 programEligibility BackboneElement has no equivalent or mapped type in R4 programEligibility |
| Immunization.programEligibility.extension | - | DoesNotExistInTarget | R5 `Immunization.programEligibility.extension` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.programEligibility.id | - | DoesNotExistInTarget | R5 `Immunization.programEligibility.id` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.programEligibility.modifierExtension | - | DoesNotExistInTarget | R5 `Immunization.programEligibility.modifierExtension` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.programEligibility.program | - | DoesNotExistInTarget | R5 `Immunization.programEligibility.program` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.programEligibility.programStatus | - | DoesNotExistInTarget | R5 `Immunization.programEligibility.programStatus` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.protocolApplied | Immunization.protocolApplied | Equivalent | R5 `Immunization.protocolApplied` maps as Equivalent to R4 `Immunization.protocolApplied` |
| Immunization.protocolApplied.authority | Immunization.protocolApplied.authority | Equivalent | R5 `Immunization.protocolApplied.authority` maps as Equivalent to R4 `Immunization.protocolApplied.authority` |
| Immunization.protocolApplied.doseNumber | Immunization.protocolApplied.doseNumber[x] | Equivalent | R5 `Immunization.protocolApplied.doseNumber` maps as Equivalent to R4 `Immunization.protocolApplied.doseNumber[x]` |
| Immunization.protocolApplied.extension | Immunization.protocolApplied.extension | SourceIsBroaderThanTarget | R5 `Immunization.protocolApplied.extension` maps as SourceIsBroaderThanTarget to R4 `Immunization.protocolApplied.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Immunization.protocolApplied.id | Immunization.protocolApplied.id | Equivalent | R5 `Immunization.protocolApplied.id` maps as Equivalent to R4 `Immunization.protocolApplied.id` |
| Immunization.protocolApplied.modifierExtension | Immunization.protocolApplied.modifierExtension | SourceIsBroaderThanTarget | R5 `Immunization.protocolApplied.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Immunization.protocolApplied.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Immunization.protocolApplied.series | Immunization.protocolApplied.series | Equivalent | R5 `Immunization.protocolApplied.series` maps as Equivalent to R4 `Immunization.protocolApplied.series` |
| Immunization.protocolApplied.seriesDoses | Immunization.protocolApplied.seriesDoses[x] | Equivalent | R5 `Immunization.protocolApplied.seriesDoses` maps as Equivalent to R4 `Immunization.protocolApplied.seriesDoses[x]` |
| Immunization.protocolApplied.targetDisease | Immunization.protocolApplied.targetDisease | Equivalent | R5 `Immunization.protocolApplied.targetDisease` maps as Equivalent to R4 `Immunization.protocolApplied.targetDisease` |
| Immunization.reaction | Immunization.reaction | Equivalent | R5 `Immunization.reaction` maps as Equivalent to R4 `Immunization.reaction` |
| Immunization.reaction.date | Immunization.reaction.date | Equivalent | R5 `Immunization.reaction.date` maps as Equivalent to R4 `Immunization.reaction.date` |
| Immunization.reaction.extension | Immunization.reaction.extension | SourceIsBroaderThanTarget | R5 `Immunization.reaction.extension` maps as SourceIsBroaderThanTarget to R4 `Immunization.reaction.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Immunization.reaction.id | Immunization.reaction.id | Equivalent | R5 `Immunization.reaction.id` maps as Equivalent to R4 `Immunization.reaction.id` |
| Immunization.reaction.manifestation | Immunization.reaction.detail | SourceIsBroaderThanTarget | R5 `Immunization.reaction.manifestation` maps as SourceIsBroaderThanTarget to R4 `Immunization.reaction.detail` - detail has change due to type change: R5 manifestation CodeableReference has no equivalent or mapped type in R4 detail |
| Immunization.reaction.modifierExtension | Immunization.reaction.modifierExtension | SourceIsBroaderThanTarget | R5 `Immunization.reaction.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Immunization.reaction.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Immunization.reaction.reported | Immunization.reaction.reported | Equivalent | R5 `Immunization.reaction.reported` maps as Equivalent to R4 `Immunization.reaction.reported` |
| Immunization.reason | Immunization.reasonCode | SourceIsBroaderThanTarget | R5 `Immunization.reason` maps as SourceIsBroaderThanTarget to R4 `Immunization.reasonCode` - reasonCode has change due to type change: R5 reason CodeableReference has no equivalent or mapped type in R4 reasonCode |
| Immunization.reason | Immunization.reasonReference | RelatedTo | R5 `Immunization.reason` maps as RelatedTo to R4 `Immunization.reasonReference` - reasonReference removed a binding requirement - Example http://hl7.org/fhir/ValueSet/immunization-reason; reasonReference has change due to type change: R5 reason CodeableReference has no equivalent or mapped type in R4 reasonReference |
| Immunization.route | Immunization.route | Equivalent | R5 `Immunization.route` maps as Equivalent to R4 `Immunization.route` |
| Immunization.site | Immunization.site | Equivalent | R5 `Immunization.site` maps as Equivalent to R4 `Immunization.site` |
| Immunization.status | Immunization.status | Equivalent | R5 `Immunization.status` maps as Equivalent to R4 `Immunization.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/immunization-status|5.0.0 and http://hl7.org/fhir/ValueSet/immunization-status|4.0.1 (Equivalent) |
| Immunization.statusReason | Immunization.statusReason | Equivalent | R5 `Immunization.statusReason` maps as Equivalent to R4 `Immunization.statusReason` |
| Immunization.subpotentReason | Immunization.subpotentReason | Equivalent | R5 `Immunization.subpotentReason` maps as Equivalent to R4 `Immunization.subpotentReason` |
| Immunization.supportingInformation | - | DoesNotExistInTarget | R5 `Immunization.supportingInformation` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.text | Immunization.text | Equivalent | R5 `Immunization.text` maps as Equivalent to R4 `Immunization.text` |
| Immunization.vaccineCode | Immunization.vaccineCode | Equivalent | R5 `Immunization.vaccineCode` maps as Equivalent to R4 `Immunization.vaccineCode` |

