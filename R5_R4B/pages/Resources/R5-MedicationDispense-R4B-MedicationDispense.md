Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MedicationDispense |  | Indicates that a medication product is to be or has been dispensed for a named person/patient.  This includes a description of the medication product (supply) provided and the instructions for administering the medication.  The medication dispense is the result of a pharmacy system responding to a medication order. | 48 | 34 |
| Target | MedicationDispense |  | Indicates that a medication product is to be or has been dispensed for a named person/patient.  This includes a description of the medication product (supply) provided and the instructions for administering the medication.  The medication dispense is the result of a pharmacy system responding to a medication order. | 45 | 31 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 7 |
Equivalent | 4 |
RelatedTo | 37 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MedicationDispense | MedicationDispense | Equivalent | R5 `MedicationDispense` maps as Equivalent to R4B `MedicationDispense` |
| MedicationDispense.authorizingPrescription | MedicationDispense.authorizingPrescription | Equivalent | R5 `MedicationDispense.authorizingPrescription` maps as Equivalent to R4B `MedicationDispense.authorizingPrescription` |
| MedicationDispense.basedOn | - | DoesNotExistInTarget | R5 `MedicationDispense.basedOn` does not appear in the target and has no mapping for `MedicationDispense`. |
| MedicationDispense.category | MedicationDispense.category | RelatedTo | R5 `MedicationDispense.category` maps as RelatedTo to R4B `MedicationDispense.category` - category changed from array to scalar (max cardinality from * to 1); category changed the binding strength from Example to Preferred |
| MedicationDispense.contained | MedicationDispense.contained | Equivalent | R5 `MedicationDispense.contained` maps as Equivalent to R4B `MedicationDispense.contained` |
| MedicationDispense.daysSupply | MedicationDispense.daysSupply | Equivalent | R5 `MedicationDispense.daysSupply` maps as Equivalent to R4B `MedicationDispense.daysSupply` |
| MedicationDispense.destination | MedicationDispense.destination | Equivalent | R5 `MedicationDispense.destination` maps as Equivalent to R4B `MedicationDispense.destination` |
| MedicationDispense.dosageInstruction | MedicationDispense.dosageInstruction | RelatedTo | R5 `MedicationDispense.dosageInstruction` maps as RelatedTo to R4B `MedicationDispense.dosageInstruction` - dosageInstruction has change due to type change: R5 `dosageInstruction` `Dosage` maps as RelatedTo for R4B `dosageInstruction` |
| MedicationDispense.encounter | - | DoesNotExistInTarget | R5 `MedicationDispense.encounter` does not appear in the target and has no mapping for `MedicationDispense`. |
| MedicationDispense.eventHistory | MedicationDispense.eventHistory | Equivalent | R5 `MedicationDispense.eventHistory` maps as Equivalent to R4B `MedicationDispense.eventHistory` |
| MedicationDispense.extension | MedicationDispense.extension | SourceIsBroaderThanTarget | R5 `MedicationDispense.extension` maps as SourceIsBroaderThanTarget to R4B `MedicationDispense.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| MedicationDispense.id | MedicationDispense.id | Equivalent | R5 `MedicationDispense.id` maps as Equivalent to R4B `MedicationDispense.id` |
| MedicationDispense.identifier | MedicationDispense.identifier | Equivalent | R5 `MedicationDispense.identifier` maps as Equivalent to R4B `MedicationDispense.identifier` |
| MedicationDispense.implicitRules | MedicationDispense.implicitRules | Equivalent | R5 `MedicationDispense.implicitRules` maps as Equivalent to R4B `MedicationDispense.implicitRules` |
| MedicationDispense.language | MedicationDispense.language | RelatedTo | R5 `MedicationDispense.language` maps as RelatedTo to R4B `MedicationDispense.language` - language changed the binding strength from Required to Preferred |
| MedicationDispense.location | MedicationDispense.location | Equivalent | R5 `MedicationDispense.location` maps as Equivalent to R4B `MedicationDispense.location` |
| MedicationDispense.medication | - | DoesNotExistInTarget | R5 `MedicationDispense.medication` does not appear in the target and has no mapping for `MedicationDispense`. |
| MedicationDispense.meta | MedicationDispense.meta | Equivalent | R5 `MedicationDispense.meta` maps as Equivalent to R4B `MedicationDispense.meta` |
| MedicationDispense.modifierExtension | MedicationDispense.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationDispense.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `MedicationDispense.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| MedicationDispense.note | MedicationDispense.note | SourceIsBroaderThanTarget | R5 `MedicationDispense.note` maps as SourceIsBroaderThanTarget to R4B `MedicationDispense.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| MedicationDispense.notPerformedReason | - | DoesNotExistInTarget | R5 `MedicationDispense.notPerformedReason` does not appear in the target and has no mapping for `MedicationDispense`. |
| MedicationDispense.partOf | MedicationDispense.partOf | SourceIsBroaderThanTarget | R5 `MedicationDispense.partOf` maps as SourceIsBroaderThanTarget to R4B `MedicationDispense.partOf` - partOf has change due to type change: R5 `partOf` `Reference` maps as SourceIsBroaderThanTarget for R4B `partOf` |
| MedicationDispense.performer | MedicationDispense.performer | Equivalent | R5 `MedicationDispense.performer` maps as Equivalent to R4B `MedicationDispense.performer` |
| MedicationDispense.performer.actor | MedicationDispense.performer.actor | SourceIsBroaderThanTarget | R5 `MedicationDispense.performer.actor` maps as SourceIsBroaderThanTarget to R4B `MedicationDispense.performer.actor` - actor has change due to type change: R5 `actor` `Reference` maps as SourceIsBroaderThanTarget for R4B `actor` |
| MedicationDispense.performer.extension | MedicationDispense.performer.extension | SourceIsBroaderThanTarget | R5 `MedicationDispense.performer.extension` maps as SourceIsBroaderThanTarget to R4B `MedicationDispense.performer.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| MedicationDispense.performer.function | MedicationDispense.performer.function | Equivalent | R5 `MedicationDispense.performer.function` maps as Equivalent to R4B `MedicationDispense.performer.function` |
| MedicationDispense.performer.id | MedicationDispense.performer.id | Equivalent | R5 `MedicationDispense.performer.id` maps as Equivalent to R4B `MedicationDispense.performer.id` |
| MedicationDispense.performer.modifierExtension | MedicationDispense.performer.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationDispense.performer.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `MedicationDispense.performer.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| MedicationDispense.quantity | MedicationDispense.quantity | Equivalent | R5 `MedicationDispense.quantity` maps as Equivalent to R4B `MedicationDispense.quantity` |
| MedicationDispense.receiver | MedicationDispense.receiver | SourceIsBroaderThanTarget | R5 `MedicationDispense.receiver` maps as SourceIsBroaderThanTarget to R4B `MedicationDispense.receiver` - receiver has change due to type change: R5 `receiver` `Reference` maps as SourceIsBroaderThanTarget for R4B `receiver` |
| MedicationDispense.recorded | - | DoesNotExistInTarget | R5 `MedicationDispense.recorded` does not appear in the target and has no mapping for `MedicationDispense`. |
| MedicationDispense.renderedDosageInstruction | - | DoesNotExistInTarget | R5 `MedicationDispense.renderedDosageInstruction` does not appear in the target and has no mapping for `MedicationDispense`. |
| MedicationDispense.status | MedicationDispense.status | Equivalent | R5 `MedicationDispense.status` maps as Equivalent to R4B `MedicationDispense.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/medicationdispense-status|5.0.0 and http://hl7.org/fhir/ValueSet/medicationdispense-status|4.3.0 (Equivalent) |
| MedicationDispense.statusChanged | - | DoesNotExistInTarget | R5 `MedicationDispense.statusChanged` does not appear in the target and has no mapping for `MedicationDispense`. |
| MedicationDispense.subject | MedicationDispense.subject | Equivalent | R5 `MedicationDispense.subject` maps as Equivalent to R4B `MedicationDispense.subject` |
| MedicationDispense.substitution | MedicationDispense.substitution | Equivalent | R5 `MedicationDispense.substitution` maps as Equivalent to R4B `MedicationDispense.substitution` |
| MedicationDispense.substitution.extension | MedicationDispense.substitution.extension | SourceIsBroaderThanTarget | R5 `MedicationDispense.substitution.extension` maps as SourceIsBroaderThanTarget to R4B `MedicationDispense.substitution.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| MedicationDispense.substitution.id | MedicationDispense.substitution.id | Equivalent | R5 `MedicationDispense.substitution.id` maps as Equivalent to R4B `MedicationDispense.substitution.id` |
| MedicationDispense.substitution.modifierExtension | MedicationDispense.substitution.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationDispense.substitution.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `MedicationDispense.substitution.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| MedicationDispense.substitution.reason | MedicationDispense.substitution.reason | Equivalent | R5 `MedicationDispense.substitution.reason` maps as Equivalent to R4B `MedicationDispense.substitution.reason` |
| MedicationDispense.substitution.responsibleParty | MedicationDispense.substitution.responsibleParty | RelatedTo | R5 `MedicationDispense.substitution.responsibleParty` maps as RelatedTo to R4B `MedicationDispense.substitution.responsibleParty` - responsibleParty changed from scalar to array (max cardinality from 1 to *); responsibleParty has change due to type change: R5 `responsibleParty` `Reference` maps as SourceIsBroaderThanTarget for R4B `responsibleParty` |
| MedicationDispense.substitution.type | MedicationDispense.substitution.type | Equivalent | R5 `MedicationDispense.substitution.type` maps as Equivalent to R4B `MedicationDispense.substitution.type` |
| MedicationDispense.substitution.wasSubstituted | MedicationDispense.substitution.wasSubstituted | Equivalent | R5 `MedicationDispense.substitution.wasSubstituted` maps as Equivalent to R4B `MedicationDispense.substitution.wasSubstituted` |
| MedicationDispense.supportingInformation | MedicationDispense.supportingInformation | Equivalent | R5 `MedicationDispense.supportingInformation` maps as Equivalent to R4B `MedicationDispense.supportingInformation` |
| MedicationDispense.text | MedicationDispense.text | Equivalent | R5 `MedicationDispense.text` maps as Equivalent to R4B `MedicationDispense.text` |
| MedicationDispense.type | MedicationDispense.type | Equivalent | R5 `MedicationDispense.type` maps as Equivalent to R4B `MedicationDispense.type` |
| MedicationDispense.whenHandedOver | MedicationDispense.whenHandedOver | Equivalent | R5 `MedicationDispense.whenHandedOver` maps as Equivalent to R4B `MedicationDispense.whenHandedOver` |
| MedicationDispense.whenPrepared | MedicationDispense.whenPrepared | Equivalent | R5 `MedicationDispense.whenPrepared` maps as Equivalent to R4B `MedicationDispense.whenPrepared` |

