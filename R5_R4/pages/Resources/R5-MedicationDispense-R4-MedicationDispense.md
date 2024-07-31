Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MedicationDispense |  | Indicates that a medication product is to be or has been dispensed for a named person/patient.  This includes a description of the medication product (supply) provided and the instructions for administering the medication.  The medication dispense is the result of a pharmacy system responding to a medication order. | 48 | 34 |
| Target | MedicationDispense |  | Indicates that a medication product is to be or has been dispensed for a named person/patient.  This includes a description of the medication product (supply) provided and the instructions for administering the medication.  The medication dispense is the result of a pharmacy system responding to a medication order. | 45 | 31 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 27 |
RelatedTo | 1 |
SourceIsBroaderThanTarget | 14 |
SourceIsNarrowerThanTarget | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MedicationDispense | MedicationDispense | Equivalent | R5 `MedicationDispense` maps as Equivalent to R4 `MedicationDispense` |
| MedicationDispense.authorizingPrescription | MedicationDispense.authorizingPrescription | Equivalent | R5 `MedicationDispense.authorizingPrescription` maps as Equivalent to R4 `MedicationDispense.authorizingPrescription` |
| MedicationDispense.basedOn | - | DoesNotExistInTarget | R5 `MedicationDispense.basedOn` does not appear in the target and has no mapping for `MedicationDispense`. |
| MedicationDispense.category | MedicationDispense.category | SourceIsBroaderThanTarget | R5 `MedicationDispense.category` maps as SourceIsBroaderThanTarget to R4 `MedicationDispense.category` - category changed from array to scalar (max cardinality from * to 1); category changed the binding strength from Example to Preferred; category has change due to type change: R5 `category` `CodeableConcept` maps as SourceIsBroaderThanTarget for R4 `category` |
| MedicationDispense.contained | MedicationDispense.contained | Equivalent | R5 `MedicationDispense.contained` maps as Equivalent to R4 `MedicationDispense.contained` |
| MedicationDispense.daysSupply | MedicationDispense.daysSupply | Equivalent | R5 `MedicationDispense.daysSupply` maps as Equivalent to R4 `MedicationDispense.daysSupply` |
| MedicationDispense.destination | MedicationDispense.destination | Equivalent | R5 `MedicationDispense.destination` maps as Equivalent to R4 `MedicationDispense.destination` |
| MedicationDispense.dosageInstruction | MedicationDispense.dosageInstruction | SourceIsBroaderThanTarget | R5 `MedicationDispense.dosageInstruction` maps as SourceIsBroaderThanTarget to R4 `MedicationDispense.dosageInstruction` - dosageInstruction has change due to type change: R5 `dosageInstruction` `Dosage` maps as SourceIsBroaderThanTarget for R4 `dosageInstruction` |
| MedicationDispense.encounter | MedicationDispense.context | SourceIsNarrowerThanTarget | R5 `MedicationDispense.encounter` maps as SourceIsNarrowerThanTarget to R4 `MedicationDispense.context` - context has change due to type change: R5 `encounter` `Reference` maps as SourceIsNarrowerThanTarget for R4 `context` |
| MedicationDispense.eventHistory | MedicationDispense.eventHistory | Equivalent | R5 `MedicationDispense.eventHistory` maps as Equivalent to R4 `MedicationDispense.eventHistory` |
| MedicationDispense.extension | MedicationDispense.extension | SourceIsBroaderThanTarget | R5 `MedicationDispense.extension` maps as SourceIsBroaderThanTarget to R4 `MedicationDispense.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MedicationDispense.id | MedicationDispense.id | Equivalent | R5 `MedicationDispense.id` maps as Equivalent to R4 `MedicationDispense.id` |
| MedicationDispense.identifier | MedicationDispense.identifier | Equivalent | R5 `MedicationDispense.identifier` maps as Equivalent to R4 `MedicationDispense.identifier` |
| MedicationDispense.implicitRules | MedicationDispense.implicitRules | Equivalent | R5 `MedicationDispense.implicitRules` maps as Equivalent to R4 `MedicationDispense.implicitRules` |
| MedicationDispense.language | MedicationDispense.language | SourceIsNarrowerThanTarget | R5 `MedicationDispense.language` maps as SourceIsNarrowerThanTarget to R4 `MedicationDispense.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| MedicationDispense.location | MedicationDispense.location | Equivalent | R5 `MedicationDispense.location` maps as Equivalent to R4 `MedicationDispense.location` |
| MedicationDispense.medication | MedicationDispense.medication[x] | SourceIsBroaderThanTarget | R5 `MedicationDispense.medication` maps as SourceIsBroaderThanTarget to R4 `MedicationDispense.medication[x]` - medication[x] has change due to type change: R5 medication CodeableReference has no equivalent or mapped type in R4 medication[x] |
| MedicationDispense.meta | MedicationDispense.meta | Equivalent | R5 `MedicationDispense.meta` maps as Equivalent to R4 `MedicationDispense.meta` |
| MedicationDispense.modifierExtension | MedicationDispense.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationDispense.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MedicationDispense.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MedicationDispense.note | MedicationDispense.note | SourceIsBroaderThanTarget | R5 `MedicationDispense.note` maps as SourceIsBroaderThanTarget to R4 `MedicationDispense.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| MedicationDispense.notPerformedReason | MedicationDispense.statusReason[x] | SourceIsBroaderThanTarget | R5 `MedicationDispense.notPerformedReason` maps as SourceIsBroaderThanTarget to R4 `MedicationDispense.statusReason[x]` - statusReason[x] has change due to type change: R5 notPerformedReason CodeableReference has no equivalent or mapped type in R4 statusReason[x] |
| MedicationDispense.partOf | MedicationDispense.partOf | SourceIsBroaderThanTarget | R5 `MedicationDispense.partOf` maps as SourceIsBroaderThanTarget to R4 `MedicationDispense.partOf` - partOf has change due to type change: R5 `partOf` `Reference` maps as SourceIsBroaderThanTarget for R4 `partOf` |
| MedicationDispense.performer | MedicationDispense.performer | Equivalent | R5 `MedicationDispense.performer` maps as Equivalent to R4 `MedicationDispense.performer` |
| MedicationDispense.performer.actor | MedicationDispense.performer.actor | SourceIsBroaderThanTarget | R5 `MedicationDispense.performer.actor` maps as SourceIsBroaderThanTarget to R4 `MedicationDispense.performer.actor` - actor has change due to type change: R5 `actor` `Reference` maps as SourceIsBroaderThanTarget for R4 `actor` |
| MedicationDispense.performer.extension | MedicationDispense.performer.extension | SourceIsBroaderThanTarget | R5 `MedicationDispense.performer.extension` maps as SourceIsBroaderThanTarget to R4 `MedicationDispense.performer.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MedicationDispense.performer.function | MedicationDispense.performer.function | Equivalent | R5 `MedicationDispense.performer.function` maps as Equivalent to R4 `MedicationDispense.performer.function` |
| MedicationDispense.performer.id | MedicationDispense.performer.id | Equivalent | R5 `MedicationDispense.performer.id` maps as Equivalent to R4 `MedicationDispense.performer.id` |
| MedicationDispense.performer.modifierExtension | MedicationDispense.performer.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationDispense.performer.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MedicationDispense.performer.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MedicationDispense.quantity | MedicationDispense.quantity | Equivalent | R5 `MedicationDispense.quantity` maps as Equivalent to R4 `MedicationDispense.quantity` |
| MedicationDispense.receiver | MedicationDispense.receiver | SourceIsBroaderThanTarget | R5 `MedicationDispense.receiver` maps as SourceIsBroaderThanTarget to R4 `MedicationDispense.receiver` - receiver has change due to type change: R5 `receiver` `Reference` maps as SourceIsBroaderThanTarget for R4 `receiver` |
| MedicationDispense.recorded | - | DoesNotExistInTarget | R5 `MedicationDispense.recorded` does not appear in the target and has no mapping for `MedicationDispense`. |
| MedicationDispense.renderedDosageInstruction | - | DoesNotExistInTarget | R5 `MedicationDispense.renderedDosageInstruction` does not appear in the target and has no mapping for `MedicationDispense`. |
| MedicationDispense.status | MedicationDispense.status | Equivalent | R5 `MedicationDispense.status` maps as Equivalent to R4 `MedicationDispense.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/medicationdispense-status|5.0.0 and http://hl7.org/fhir/ValueSet/medicationdispense-status|4.0.1 (Equivalent) |
| MedicationDispense.statusChanged | - | DoesNotExistInTarget | R5 `MedicationDispense.statusChanged` does not appear in the target and has no mapping for `MedicationDispense`. |
| MedicationDispense.subject | MedicationDispense.subject | Equivalent | R5 `MedicationDispense.subject` maps as Equivalent to R4 `MedicationDispense.subject` |
| MedicationDispense.substitution | MedicationDispense.substitution | Equivalent | R5 `MedicationDispense.substitution` maps as Equivalent to R4 `MedicationDispense.substitution` |
| MedicationDispense.substitution.extension | MedicationDispense.substitution.extension | SourceIsBroaderThanTarget | R5 `MedicationDispense.substitution.extension` maps as SourceIsBroaderThanTarget to R4 `MedicationDispense.substitution.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MedicationDispense.substitution.id | MedicationDispense.substitution.id | Equivalent | R5 `MedicationDispense.substitution.id` maps as Equivalent to R4 `MedicationDispense.substitution.id` |
| MedicationDispense.substitution.modifierExtension | MedicationDispense.substitution.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationDispense.substitution.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MedicationDispense.substitution.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MedicationDispense.substitution.reason | MedicationDispense.substitution.reason | Equivalent | R5 `MedicationDispense.substitution.reason` maps as Equivalent to R4 `MedicationDispense.substitution.reason` |
| MedicationDispense.substitution.responsibleParty | MedicationDispense.substitution.responsibleParty | RelatedTo | R5 `MedicationDispense.substitution.responsibleParty` maps as RelatedTo to R4 `MedicationDispense.substitution.responsibleParty` - responsibleParty changed from scalar to array (max cardinality from 1 to *); responsibleParty has change due to type change: R5 `responsibleParty` `Reference` maps as SourceIsBroaderThanTarget for R4 `responsibleParty` |
| MedicationDispense.substitution.type | MedicationDispense.substitution.type | Equivalent | R5 `MedicationDispense.substitution.type` maps as Equivalent to R4 `MedicationDispense.substitution.type` |
| MedicationDispense.substitution.wasSubstituted | MedicationDispense.substitution.wasSubstituted | Equivalent | R5 `MedicationDispense.substitution.wasSubstituted` maps as Equivalent to R4 `MedicationDispense.substitution.wasSubstituted` |
| MedicationDispense.supportingInformation | MedicationDispense.supportingInformation | Equivalent | R5 `MedicationDispense.supportingInformation` maps as Equivalent to R4 `MedicationDispense.supportingInformation` |
| MedicationDispense.text | MedicationDispense.text | Equivalent | R5 `MedicationDispense.text` maps as Equivalent to R4 `MedicationDispense.text` |
| MedicationDispense.type | MedicationDispense.type | Equivalent | R5 `MedicationDispense.type` maps as Equivalent to R4 `MedicationDispense.type` |
| MedicationDispense.whenHandedOver | MedicationDispense.whenHandedOver | Equivalent | R5 `MedicationDispense.whenHandedOver` maps as Equivalent to R4 `MedicationDispense.whenHandedOver` |
| MedicationDispense.whenPrepared | MedicationDispense.whenPrepared | Equivalent | R5 `MedicationDispense.whenPrepared` maps as Equivalent to R4 `MedicationDispense.whenPrepared` |

