Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MedicationAdministration |  | Describes the event of a patient consuming or otherwise being administered a medication.  This may be as simple as swallowing a tablet or it may be a long running infusion.  Related resources tie this event to the authorizing prescription, and the specific encounter between patient and health care practitioner. | 42 | 28 |
| Target | MedicationAdministration |  | Describes the event of a patient consuming or otherwise being administered a medication.  This may be as simple as swallowing a tablet or it may be a long running infusion. Related resources tie this event to the authorizing prescription, and the specific encounter between patient and health care practitioner. This event can also be used to record waste using a status of not-done and the appropriate statusReason. | 44 | 30 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 6 |
Equivalent | 4 |
RelatedTo | 32 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MedicationAdministration | MedicationAdministration | Equivalent | R4B `MedicationAdministration` maps as Equivalent to R5 `MedicationAdministration` |
| MedicationAdministration.category | MedicationAdministration.category | RelatedTo | R4B `MedicationAdministration.category` maps as RelatedTo to R5 `MedicationAdministration.category` - category changed from scalar to array (max cardinality from 1 to *); category changed the binding strength from Preferred to Example |
| MedicationAdministration.contained | MedicationAdministration.contained | Equivalent | R4B `MedicationAdministration.contained` maps as Equivalent to R5 `MedicationAdministration.contained` |
| MedicationAdministration.context | - | DoesNotExistInTarget | R4B `MedicationAdministration.context` does not appear in the target and has no mapping for `MedicationAdministration`. |
| MedicationAdministration.device | MedicationAdministration.device | SourceIsBroaderThanTarget | R4B `MedicationAdministration.device` maps as SourceIsBroaderThanTarget to R5 `MedicationAdministration.device` - device has change due to type change: R4B device Reference has no equivalent or mapped type in R5 device |
| MedicationAdministration.dosage | MedicationAdministration.dosage | Equivalent | R4B `MedicationAdministration.dosage` maps as Equivalent to R5 `MedicationAdministration.dosage` |
| MedicationAdministration.dosage.dose | MedicationAdministration.dosage.dose | Equivalent | R4B `MedicationAdministration.dosage.dose` maps as Equivalent to R5 `MedicationAdministration.dosage.dose` |
| MedicationAdministration.dosage.extension | MedicationAdministration.dosage.extension | RelatedTo | R4B `MedicationAdministration.dosage.extension` maps as RelatedTo to R5 `MedicationAdministration.dosage.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicationAdministration.dosage.id | MedicationAdministration.dosage.id | Equivalent | R4B `MedicationAdministration.dosage.id` maps as Equivalent to R5 `MedicationAdministration.dosage.id` |
| MedicationAdministration.dosage.method | MedicationAdministration.dosage.method | Equivalent | R4B `MedicationAdministration.dosage.method` maps as Equivalent to R5 `MedicationAdministration.dosage.method` |
| MedicationAdministration.dosage.modifierExtension | MedicationAdministration.dosage.modifierExtension | RelatedTo | R4B `MedicationAdministration.dosage.modifierExtension` maps as RelatedTo to R5 `MedicationAdministration.dosage.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicationAdministration.dosage.rate[x] | MedicationAdministration.dosage.rate[x] | SourceIsNarrowerThanTarget | R4B `MedicationAdministration.dosage.rate[x]` maps as SourceIsNarrowerThanTarget to R5 `MedicationAdministration.dosage.rate[x]` - rate[x] has change due to type change: R4B `rate[x]` `Ratio` maps as SourceIsNarrowerThanTarget for R5 `rate[x]` |
| MedicationAdministration.dosage.route | MedicationAdministration.dosage.route | Equivalent | R4B `MedicationAdministration.dosage.route` maps as Equivalent to R5 `MedicationAdministration.dosage.route` |
| MedicationAdministration.dosage.site | MedicationAdministration.dosage.site | Equivalent | R4B `MedicationAdministration.dosage.site` maps as Equivalent to R5 `MedicationAdministration.dosage.site` |
| MedicationAdministration.dosage.text | MedicationAdministration.dosage.text | Equivalent | R4B `MedicationAdministration.dosage.text` maps as Equivalent to R5 `MedicationAdministration.dosage.text` |
| MedicationAdministration.effective[x] | - | DoesNotExistInTarget | R4B `MedicationAdministration.effective[x]` does not appear in the target and has no mapping for `MedicationAdministration`. |
| MedicationAdministration.eventHistory | MedicationAdministration.eventHistory | Equivalent | R4B `MedicationAdministration.eventHistory` maps as Equivalent to R5 `MedicationAdministration.eventHistory` |
| MedicationAdministration.extension | MedicationAdministration.extension | RelatedTo | R4B `MedicationAdministration.extension` maps as RelatedTo to R5 `MedicationAdministration.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicationAdministration.id | MedicationAdministration.id | Equivalent | R4B `MedicationAdministration.id` maps as Equivalent to R5 `MedicationAdministration.id` |
| MedicationAdministration.identifier | MedicationAdministration.identifier | Equivalent | R4B `MedicationAdministration.identifier` maps as Equivalent to R5 `MedicationAdministration.identifier` |
| MedicationAdministration.implicitRules | MedicationAdministration.implicitRules | Equivalent | R4B `MedicationAdministration.implicitRules` maps as Equivalent to R5 `MedicationAdministration.implicitRules` |
| MedicationAdministration.instantiates | - | DoesNotExistInTarget | R4B `MedicationAdministration.instantiates` does not appear in the target and has no mapping for `MedicationAdministration`. |
| MedicationAdministration.language | MedicationAdministration.language | RelatedTo | R4B `MedicationAdministration.language` maps as RelatedTo to R5 `MedicationAdministration.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| MedicationAdministration.medication[x] | - | DoesNotExistInTarget | R4B `MedicationAdministration.medication[x]` does not appear in the target and has no mapping for `MedicationAdministration`. |
| MedicationAdministration.meta | MedicationAdministration.meta | Equivalent | R4B `MedicationAdministration.meta` maps as Equivalent to R5 `MedicationAdministration.meta` |
| MedicationAdministration.modifierExtension | MedicationAdministration.modifierExtension | RelatedTo | R4B `MedicationAdministration.modifierExtension` maps as RelatedTo to R5 `MedicationAdministration.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicationAdministration.note | MedicationAdministration.note | SourceIsNarrowerThanTarget | R4B `MedicationAdministration.note` maps as SourceIsNarrowerThanTarget to R5 `MedicationAdministration.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| MedicationAdministration.partOf | MedicationAdministration.partOf | SourceIsNarrowerThanTarget | R4B `MedicationAdministration.partOf` maps as SourceIsNarrowerThanTarget to R5 `MedicationAdministration.partOf` - partOf has change due to type change: R4B `partOf` `Reference` maps as SourceIsNarrowerThanTarget for R5 `partOf` |
| MedicationAdministration.performer | MedicationAdministration.performer | Equivalent | R4B `MedicationAdministration.performer` maps as Equivalent to R5 `MedicationAdministration.performer` |
| MedicationAdministration.performer.actor | MedicationAdministration.performer.actor | SourceIsBroaderThanTarget | R4B `MedicationAdministration.performer.actor` maps as SourceIsBroaderThanTarget to R5 `MedicationAdministration.performer.actor` - actor has change due to type change: R4B actor Reference has no equivalent or mapped type in R5 actor |
| MedicationAdministration.performer.extension | MedicationAdministration.performer.extension | RelatedTo | R4B `MedicationAdministration.performer.extension` maps as RelatedTo to R5 `MedicationAdministration.performer.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicationAdministration.performer.function | MedicationAdministration.performer.function | Equivalent | R4B `MedicationAdministration.performer.function` maps as Equivalent to R5 `MedicationAdministration.performer.function` |
| MedicationAdministration.performer.id | MedicationAdministration.performer.id | Equivalent | R4B `MedicationAdministration.performer.id` maps as Equivalent to R5 `MedicationAdministration.performer.id` |
| MedicationAdministration.performer.modifierExtension | MedicationAdministration.performer.modifierExtension | RelatedTo | R4B `MedicationAdministration.performer.modifierExtension` maps as RelatedTo to R5 `MedicationAdministration.performer.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicationAdministration.reasonCode | - | DoesNotExistInTarget | R4B `MedicationAdministration.reasonCode` does not appear in the target and has no mapping for `MedicationAdministration`. |
| MedicationAdministration.reasonReference | - | DoesNotExistInTarget | R4B `MedicationAdministration.reasonReference` does not appear in the target and has no mapping for `MedicationAdministration`. |
| MedicationAdministration.request | MedicationAdministration.request | Equivalent | R4B `MedicationAdministration.request` maps as Equivalent to R5 `MedicationAdministration.request` |
| MedicationAdministration.status | MedicationAdministration.status | Equivalent | R4B `MedicationAdministration.status` maps as Equivalent to R5 `MedicationAdministration.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/medication-admin-status|4.3.0 and http://hl7.org/fhir/ValueSet/medication-admin-status|5.0.0 (Equivalent) |
| MedicationAdministration.statusReason | MedicationAdministration.statusReason | Equivalent | R4B `MedicationAdministration.statusReason` maps as Equivalent to R5 `MedicationAdministration.statusReason` |
| MedicationAdministration.subject | MedicationAdministration.subject | Equivalent | R4B `MedicationAdministration.subject` maps as Equivalent to R5 `MedicationAdministration.subject` |
| MedicationAdministration.supportingInformation | MedicationAdministration.supportingInformation | Equivalent | R4B `MedicationAdministration.supportingInformation` maps as Equivalent to R5 `MedicationAdministration.supportingInformation` |
| MedicationAdministration.text | MedicationAdministration.text | Equivalent | R4B `MedicationAdministration.text` maps as Equivalent to R5 `MedicationAdministration.text` |

