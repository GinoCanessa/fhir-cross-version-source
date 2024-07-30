Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MedicationAdministration |  | Describes the event of a patient consuming or otherwise being administered a medication.  This may be as simple as swallowing a tablet or it may be a long running infusion. Related resources tie this event to the authorizing prescription, and the specific encounter between patient and health care practitioner. This event can also be used to record waste using a status of not-done and the appropriate statusReason. | 44 | 30 |
| Target | MedicationAdministration |  | Describes the event of a patient consuming or otherwise being administered a medication.  This may be as simple as swallowing a tablet or it may be a long running infusion.  Related resources tie this event to the authorizing prescription, and the specific encounter between patient and health care practitioner. | 42 | 28 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 8 |
Equivalent | 4 |
RelatedTo | 32 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MedicationAdministration | MedicationAdministration | Equivalent | R5 `MedicationAdministration` maps as Equivalent to R4 `MedicationAdministration` |
| MedicationAdministration.basedOn | - | DoesNotExistInTarget | R5 `MedicationAdministration.basedOn` does not appear in the target and has no mapping for `MedicationAdministration`. |
| MedicationAdministration.category | MedicationAdministration.category | RelatedTo | R5 `MedicationAdministration.category` maps as RelatedTo to R4 `MedicationAdministration.category` - category changed from array to scalar (max cardinality from * to 1); category changed the binding strength from Example to Preferred |
| MedicationAdministration.contained | MedicationAdministration.contained | Equivalent | R5 `MedicationAdministration.contained` maps as Equivalent to R4 `MedicationAdministration.contained` |
| MedicationAdministration.device | MedicationAdministration.device | SourceIsBroaderThanTarget | R5 `MedicationAdministration.device` maps as SourceIsBroaderThanTarget to R4 `MedicationAdministration.device` - device has change due to type change: R5 device CodeableReference has no equivalent or mapped type in R4 device |
| MedicationAdministration.dosage | MedicationAdministration.dosage | Equivalent | R5 `MedicationAdministration.dosage` maps as Equivalent to R4 `MedicationAdministration.dosage` |
| MedicationAdministration.dosage.dose | MedicationAdministration.dosage.dose | Equivalent | R5 `MedicationAdministration.dosage.dose` maps as Equivalent to R4 `MedicationAdministration.dosage.dose` |
| MedicationAdministration.dosage.extension | MedicationAdministration.dosage.extension | SourceIsBroaderThanTarget | R5 `MedicationAdministration.dosage.extension` maps as SourceIsBroaderThanTarget to R4 `MedicationAdministration.dosage.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MedicationAdministration.dosage.id | MedicationAdministration.dosage.id | Equivalent | R5 `MedicationAdministration.dosage.id` maps as Equivalent to R4 `MedicationAdministration.dosage.id` |
| MedicationAdministration.dosage.method | MedicationAdministration.dosage.method | Equivalent | R5 `MedicationAdministration.dosage.method` maps as Equivalent to R4 `MedicationAdministration.dosage.method` |
| MedicationAdministration.dosage.modifierExtension | MedicationAdministration.dosage.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationAdministration.dosage.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MedicationAdministration.dosage.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MedicationAdministration.dosage.rate[x] | MedicationAdministration.dosage.rate[x] | SourceIsBroaderThanTarget | R5 `MedicationAdministration.dosage.rate[x]` maps as SourceIsBroaderThanTarget to R4 `MedicationAdministration.dosage.rate[x]` - rate[x] has change due to type change: R5 `rate[x]` `Ratio` maps as SourceIsBroaderThanTarget for R4 `rate[x]` |
| MedicationAdministration.dosage.route | MedicationAdministration.dosage.route | Equivalent | R5 `MedicationAdministration.dosage.route` maps as Equivalent to R4 `MedicationAdministration.dosage.route` |
| MedicationAdministration.dosage.site | MedicationAdministration.dosage.site | Equivalent | R5 `MedicationAdministration.dosage.site` maps as Equivalent to R4 `MedicationAdministration.dosage.site` |
| MedicationAdministration.dosage.text | MedicationAdministration.dosage.text | Equivalent | R5 `MedicationAdministration.dosage.text` maps as Equivalent to R4 `MedicationAdministration.dosage.text` |
| MedicationAdministration.encounter | - | DoesNotExistInTarget | R5 `MedicationAdministration.encounter` does not appear in the target and has no mapping for `MedicationAdministration`. |
| MedicationAdministration.eventHistory | MedicationAdministration.eventHistory | Equivalent | R5 `MedicationAdministration.eventHistory` maps as Equivalent to R4 `MedicationAdministration.eventHistory` |
| MedicationAdministration.extension | MedicationAdministration.extension | SourceIsBroaderThanTarget | R5 `MedicationAdministration.extension` maps as SourceIsBroaderThanTarget to R4 `MedicationAdministration.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MedicationAdministration.id | MedicationAdministration.id | Equivalent | R5 `MedicationAdministration.id` maps as Equivalent to R4 `MedicationAdministration.id` |
| MedicationAdministration.identifier | MedicationAdministration.identifier | Equivalent | R5 `MedicationAdministration.identifier` maps as Equivalent to R4 `MedicationAdministration.identifier` |
| MedicationAdministration.implicitRules | MedicationAdministration.implicitRules | Equivalent | R5 `MedicationAdministration.implicitRules` maps as Equivalent to R4 `MedicationAdministration.implicitRules` |
| MedicationAdministration.isSubPotent | - | DoesNotExistInTarget | R5 `MedicationAdministration.isSubPotent` does not appear in the target and has no mapping for `MedicationAdministration`. |
| MedicationAdministration.language | MedicationAdministration.language | RelatedTo | R5 `MedicationAdministration.language` maps as RelatedTo to R4 `MedicationAdministration.language` - language changed the binding strength from Required to Preferred |
| MedicationAdministration.medication | - | DoesNotExistInTarget | R5 `MedicationAdministration.medication` does not appear in the target and has no mapping for `MedicationAdministration`. |
| MedicationAdministration.meta | MedicationAdministration.meta | Equivalent | R5 `MedicationAdministration.meta` maps as Equivalent to R4 `MedicationAdministration.meta` |
| MedicationAdministration.modifierExtension | MedicationAdministration.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationAdministration.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MedicationAdministration.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MedicationAdministration.note | MedicationAdministration.note | SourceIsBroaderThanTarget | R5 `MedicationAdministration.note` maps as SourceIsBroaderThanTarget to R4 `MedicationAdministration.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| MedicationAdministration.occurence[x] | - | DoesNotExistInTarget | R5 `MedicationAdministration.occurence[x]` does not appear in the target and has no mapping for `MedicationAdministration`. |
| MedicationAdministration.partOf | MedicationAdministration.partOf | SourceIsBroaderThanTarget | R5 `MedicationAdministration.partOf` maps as SourceIsBroaderThanTarget to R4 `MedicationAdministration.partOf` - partOf has change due to type change: R5 `partOf` `Reference` maps as SourceIsBroaderThanTarget for R4 `partOf` |
| MedicationAdministration.performer | MedicationAdministration.performer | Equivalent | R5 `MedicationAdministration.performer` maps as Equivalent to R4 `MedicationAdministration.performer` |
| MedicationAdministration.performer.actor | MedicationAdministration.performer.actor | SourceIsBroaderThanTarget | R5 `MedicationAdministration.performer.actor` maps as SourceIsBroaderThanTarget to R4 `MedicationAdministration.performer.actor` - actor has change due to type change: R5 actor CodeableReference has no equivalent or mapped type in R4 actor |
| MedicationAdministration.performer.extension | MedicationAdministration.performer.extension | SourceIsBroaderThanTarget | R5 `MedicationAdministration.performer.extension` maps as SourceIsBroaderThanTarget to R4 `MedicationAdministration.performer.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MedicationAdministration.performer.function | MedicationAdministration.performer.function | Equivalent | R5 `MedicationAdministration.performer.function` maps as Equivalent to R4 `MedicationAdministration.performer.function` |
| MedicationAdministration.performer.id | MedicationAdministration.performer.id | Equivalent | R5 `MedicationAdministration.performer.id` maps as Equivalent to R4 `MedicationAdministration.performer.id` |
| MedicationAdministration.performer.modifierExtension | MedicationAdministration.performer.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationAdministration.performer.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MedicationAdministration.performer.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MedicationAdministration.reason | - | DoesNotExistInTarget | R5 `MedicationAdministration.reason` does not appear in the target and has no mapping for `MedicationAdministration`. |
| MedicationAdministration.recorded | - | DoesNotExistInTarget | R5 `MedicationAdministration.recorded` does not appear in the target and has no mapping for `MedicationAdministration`. |
| MedicationAdministration.request | MedicationAdministration.request | Equivalent | R5 `MedicationAdministration.request` maps as Equivalent to R4 `MedicationAdministration.request` |
| MedicationAdministration.status | MedicationAdministration.status | Equivalent | R5 `MedicationAdministration.status` maps as Equivalent to R4 `MedicationAdministration.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/medication-admin-status|5.0.0 and http://hl7.org/fhir/ValueSet/medication-admin-status|4.0.1 (Equivalent) |
| MedicationAdministration.statusReason | MedicationAdministration.statusReason | Equivalent | R5 `MedicationAdministration.statusReason` maps as Equivalent to R4 `MedicationAdministration.statusReason` |
| MedicationAdministration.subject | MedicationAdministration.subject | Equivalent | R5 `MedicationAdministration.subject` maps as Equivalent to R4 `MedicationAdministration.subject` |
| MedicationAdministration.subPotentReason | - | DoesNotExistInTarget | R5 `MedicationAdministration.subPotentReason` does not appear in the target and has no mapping for `MedicationAdministration`. |
| MedicationAdministration.supportingInformation | MedicationAdministration.supportingInformation | Equivalent | R5 `MedicationAdministration.supportingInformation` maps as Equivalent to R4 `MedicationAdministration.supportingInformation` |
| MedicationAdministration.text | MedicationAdministration.text | Equivalent | R5 `MedicationAdministration.text` maps as Equivalent to R4 `MedicationAdministration.text` |

