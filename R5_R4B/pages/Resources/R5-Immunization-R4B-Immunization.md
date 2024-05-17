Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Immunization |  | Describes the event of a patient being administered a vaccine or a record of an immunization as reported by a patient, a clinician or another party. | 61 | 41 |
| Target | Immunization |  | Describes the event of a patient being administered a vaccine or a record of an immunization as reported by a patient, a clinician or another party. | 63 | 43 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 13 |
Equivalent | 4 |
RelatedTo | 44 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Immunization | Immunization | Equivalent | R5 `Immunization` maps as Equivalent to R4B `Immunization` |
| Immunization.administeredProduct | - | DoesNotExistInTarget | R5 `Immunization.administeredProduct` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.basedOn | - | DoesNotExistInTarget | R5 `Immunization.basedOn` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.contained | Immunization.contained | Equivalent | R5 `Immunization.contained` maps as Equivalent to R4B `Immunization.contained` |
| Immunization.doseQuantity | Immunization.doseQuantity | Equivalent | R5 `Immunization.doseQuantity` maps as Equivalent to R4B `Immunization.doseQuantity` |
| Immunization.encounter | Immunization.encounter | Equivalent | R5 `Immunization.encounter` maps as Equivalent to R4B `Immunization.encounter` |
| Immunization.expirationDate | Immunization.expirationDate | Equivalent | R5 `Immunization.expirationDate` maps as Equivalent to R4B `Immunization.expirationDate` |
| Immunization.extension | Immunization.extension | SourceIsBroaderThanTarget | R5 `Immunization.extension` maps as SourceIsBroaderThanTarget to R4B `Immunization.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Immunization.fundingSource | Immunization.fundingSource | Equivalent | R5 `Immunization.fundingSource` maps as Equivalent to R4B `Immunization.fundingSource` |
| Immunization.id | Immunization.id | Equivalent | R5 `Immunization.id` maps as Equivalent to R4B `Immunization.id` |
| Immunization.identifier | Immunization.identifier | Equivalent | R5 `Immunization.identifier` maps as Equivalent to R4B `Immunization.identifier` |
| Immunization.implicitRules | Immunization.implicitRules | Equivalent | R5 `Immunization.implicitRules` maps as Equivalent to R4B `Immunization.implicitRules` |
| Immunization.informationSource | - | DoesNotExistInTarget | R5 `Immunization.informationSource` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.isSubpotent | Immunization.isSubpotent | Equivalent | R5 `Immunization.isSubpotent` maps as Equivalent to R4B `Immunization.isSubpotent` |
| Immunization.language | Immunization.language | RelatedTo | R5 `Immunization.language` maps as RelatedTo to R4B `Immunization.language` - language changed the binding strength from Required to Preferred |
| Immunization.location | Immunization.location | Equivalent | R5 `Immunization.location` maps as Equivalent to R4B `Immunization.location` |
| Immunization.lotNumber | Immunization.lotNumber | Equivalent | R5 `Immunization.lotNumber` maps as Equivalent to R4B `Immunization.lotNumber` |
| Immunization.manufacturer | Immunization.manufacturer | SourceIsBroaderThanTarget | R5 `Immunization.manufacturer` maps as SourceIsBroaderThanTarget to R4B `Immunization.manufacturer` - manufacturer has change due to type change: R5 manufacturer CodeableReference has no equivalent or mapped type in R4B manufacturer |
| Immunization.meta | Immunization.meta | Equivalent | R5 `Immunization.meta` maps as Equivalent to R4B `Immunization.meta` |
| Immunization.modifierExtension | Immunization.modifierExtension | SourceIsBroaderThanTarget | R5 `Immunization.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Immunization.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Immunization.note | Immunization.note | SourceIsBroaderThanTarget | R5 `Immunization.note` maps as SourceIsBroaderThanTarget to R4B `Immunization.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| Immunization.occurrence[x] | Immunization.occurrence[x] | Equivalent | R5 `Immunization.occurrence[x]` maps as Equivalent to R4B `Immunization.occurrence[x]` |
| Immunization.patient | Immunization.patient | Equivalent | R5 `Immunization.patient` maps as Equivalent to R4B `Immunization.patient` |
| Immunization.performer | Immunization.performer | Equivalent | R5 `Immunization.performer` maps as Equivalent to R4B `Immunization.performer` |
| Immunization.performer.actor | Immunization.performer.actor | SourceIsBroaderThanTarget | R5 `Immunization.performer.actor` maps as SourceIsBroaderThanTarget to R4B `Immunization.performer.actor` - actor has change due to type change: R5 `actor` `Reference` maps as SourceIsBroaderThanTarget for R4B `actor` |
| Immunization.performer.extension | Immunization.performer.extension | SourceIsBroaderThanTarget | R5 `Immunization.performer.extension` maps as SourceIsBroaderThanTarget to R4B `Immunization.performer.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Immunization.performer.function | Immunization.performer.function | Equivalent | R5 `Immunization.performer.function` maps as Equivalent to R4B `Immunization.performer.function` |
| Immunization.performer.id | Immunization.performer.id | Equivalent | R5 `Immunization.performer.id` maps as Equivalent to R4B `Immunization.performer.id` |
| Immunization.performer.modifierExtension | Immunization.performer.modifierExtension | SourceIsBroaderThanTarget | R5 `Immunization.performer.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Immunization.performer.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Immunization.primarySource | Immunization.primarySource | Equivalent | R5 `Immunization.primarySource` maps as Equivalent to R4B `Immunization.primarySource` |
| Immunization.programEligibility | Immunization.programEligibility | RelatedTo | R5 `Immunization.programEligibility` maps as RelatedTo to R4B `Immunization.programEligibility` - programEligibility added a binding requirement - Example http://hl7.org/fhir/ValueSet/immunization-program-eligibility; programEligibility has change due to type change: R5 programEligibility BackboneElement has no equivalent or mapped type in R4B programEligibility |
| Immunization.programEligibility.extension | - | DoesNotExistInTarget | R5 `Immunization.programEligibility.extension` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.programEligibility.id | - | DoesNotExistInTarget | R5 `Immunization.programEligibility.id` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.programEligibility.modifierExtension | - | DoesNotExistInTarget | R5 `Immunization.programEligibility.modifierExtension` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.programEligibility.program | - | DoesNotExistInTarget | R5 `Immunization.programEligibility.program` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.programEligibility.programStatus | - | DoesNotExistInTarget | R5 `Immunization.programEligibility.programStatus` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.protocolApplied | Immunization.protocolApplied | Equivalent | R5 `Immunization.protocolApplied` maps as Equivalent to R4B `Immunization.protocolApplied` |
| Immunization.protocolApplied.authority | Immunization.protocolApplied.authority | Equivalent | R5 `Immunization.protocolApplied.authority` maps as Equivalent to R4B `Immunization.protocolApplied.authority` |
| Immunization.protocolApplied.doseNumber | - | DoesNotExistInTarget | R5 `Immunization.protocolApplied.doseNumber` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.protocolApplied.extension | Immunization.protocolApplied.extension | SourceIsBroaderThanTarget | R5 `Immunization.protocolApplied.extension` maps as SourceIsBroaderThanTarget to R4B `Immunization.protocolApplied.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Immunization.protocolApplied.id | Immunization.protocolApplied.id | Equivalent | R5 `Immunization.protocolApplied.id` maps as Equivalent to R4B `Immunization.protocolApplied.id` |
| Immunization.protocolApplied.modifierExtension | Immunization.protocolApplied.modifierExtension | SourceIsBroaderThanTarget | R5 `Immunization.protocolApplied.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Immunization.protocolApplied.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Immunization.protocolApplied.series | Immunization.protocolApplied.series | Equivalent | R5 `Immunization.protocolApplied.series` maps as Equivalent to R4B `Immunization.protocolApplied.series` |
| Immunization.protocolApplied.seriesDoses | - | DoesNotExistInTarget | R5 `Immunization.protocolApplied.seriesDoses` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.protocolApplied.targetDisease | Immunization.protocolApplied.targetDisease | Equivalent | R5 `Immunization.protocolApplied.targetDisease` maps as Equivalent to R4B `Immunization.protocolApplied.targetDisease` |
| Immunization.reaction | Immunization.reaction | Equivalent | R5 `Immunization.reaction` maps as Equivalent to R4B `Immunization.reaction` |
| Immunization.reaction.date | Immunization.reaction.date | Equivalent | R5 `Immunization.reaction.date` maps as Equivalent to R4B `Immunization.reaction.date` |
| Immunization.reaction.extension | Immunization.reaction.extension | SourceIsBroaderThanTarget | R5 `Immunization.reaction.extension` maps as SourceIsBroaderThanTarget to R4B `Immunization.reaction.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Immunization.reaction.id | Immunization.reaction.id | Equivalent | R5 `Immunization.reaction.id` maps as Equivalent to R4B `Immunization.reaction.id` |
| Immunization.reaction.manifestation | - | DoesNotExistInTarget | R5 `Immunization.reaction.manifestation` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.reaction.modifierExtension | Immunization.reaction.modifierExtension | SourceIsBroaderThanTarget | R5 `Immunization.reaction.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Immunization.reaction.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Immunization.reaction.reported | Immunization.reaction.reported | Equivalent | R5 `Immunization.reaction.reported` maps as Equivalent to R4B `Immunization.reaction.reported` |
| Immunization.reason | - | DoesNotExistInTarget | R5 `Immunization.reason` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.route | Immunization.route | Equivalent | R5 `Immunization.route` maps as Equivalent to R4B `Immunization.route` |
| Immunization.site | Immunization.site | Equivalent | R5 `Immunization.site` maps as Equivalent to R4B `Immunization.site` |
| Immunization.status | Immunization.status | Equivalent | R5 `Immunization.status` maps as Equivalent to R4B `Immunization.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/immunization-status|5.0.0 and http://hl7.org/fhir/ValueSet/immunization-status|4.3.0 (Equivalent) |
| Immunization.statusReason | Immunization.statusReason | Equivalent | R5 `Immunization.statusReason` maps as Equivalent to R4B `Immunization.statusReason` |
| Immunization.subpotentReason | Immunization.subpotentReason | Equivalent | R5 `Immunization.subpotentReason` maps as Equivalent to R4B `Immunization.subpotentReason` |
| Immunization.supportingInformation | - | DoesNotExistInTarget | R5 `Immunization.supportingInformation` does not appear in the target and has no mapping for `Immunization`. |
| Immunization.text | Immunization.text | Equivalent | R5 `Immunization.text` maps as Equivalent to R4B `Immunization.text` |
| Immunization.vaccineCode | Immunization.vaccineCode | Equivalent | R5 `Immunization.vaccineCode` maps as Equivalent to R4B `Immunization.vaccineCode` |

