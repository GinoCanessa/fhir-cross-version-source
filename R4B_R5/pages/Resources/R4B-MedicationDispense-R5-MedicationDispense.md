Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MedicationDispense |  | Indicates that a medication product is to be or has been dispensed for a named person/patient.  This includes a description of the medication product (supply) provided and the instructions for administering the medication.  The medication dispense is the result of a pharmacy system responding to a medication order. | 45 | 31 |
| Target | MedicationDispense |  | Indicates that a medication product is to be or has been dispensed for a named person/patient.  This includes a description of the medication product (supply) provided and the instructions for administering the medication.  The medication dispense is the result of a pharmacy system responding to a medication order. | 48 | 34 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 37 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MedicationDispense | MedicationDispense | Equivalent | R4B `MedicationDispense` maps as Equivalent to R5 `MedicationDispense` |
| MedicationDispense.authorizingPrescription | MedicationDispense.authorizingPrescription | Equivalent | R4B `MedicationDispense.authorizingPrescription` maps as Equivalent to R5 `MedicationDispense.authorizingPrescription` |
| MedicationDispense.category | MedicationDispense.category | RelatedTo | R4B `MedicationDispense.category` maps as RelatedTo to R5 `MedicationDispense.category` - category changed from scalar to array (max cardinality from 1 to *); category changed the binding strength from Preferred to Example |
| MedicationDispense.contained | MedicationDispense.contained | Equivalent | R4B `MedicationDispense.contained` maps as Equivalent to R5 `MedicationDispense.contained` |
| MedicationDispense.context | - | DoesNotExistInTarget | R4B `MedicationDispense.context` does not appear in the target and has no mapping for `MedicationDispense`. |
| MedicationDispense.daysSupply | MedicationDispense.daysSupply | Equivalent | R4B `MedicationDispense.daysSupply` maps as Equivalent to R5 `MedicationDispense.daysSupply` |
| MedicationDispense.destination | MedicationDispense.destination | Equivalent | R4B `MedicationDispense.destination` maps as Equivalent to R5 `MedicationDispense.destination` |
| MedicationDispense.detectedIssue | - | DoesNotExistInTarget | R4B `MedicationDispense.detectedIssue` does not appear in the target and has no mapping for `MedicationDispense`. |
| MedicationDispense.dosageInstruction | MedicationDispense.dosageInstruction | RelatedTo | R4B `MedicationDispense.dosageInstruction` maps as RelatedTo to R5 `MedicationDispense.dosageInstruction` - dosageInstruction has change due to type change: R4B `dosageInstruction` `Dosage` maps as RelatedTo for R5 `dosageInstruction` |
| MedicationDispense.eventHistory | MedicationDispense.eventHistory | Equivalent | R4B `MedicationDispense.eventHistory` maps as Equivalent to R5 `MedicationDispense.eventHistory` |
| MedicationDispense.extension | MedicationDispense.extension | RelatedTo | R4B `MedicationDispense.extension` maps as RelatedTo to R5 `MedicationDispense.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicationDispense.id | MedicationDispense.id | Equivalent | R4B `MedicationDispense.id` maps as Equivalent to R5 `MedicationDispense.id` |
| MedicationDispense.identifier | MedicationDispense.identifier | Equivalent | R4B `MedicationDispense.identifier` maps as Equivalent to R5 `MedicationDispense.identifier` |
| MedicationDispense.implicitRules | MedicationDispense.implicitRules | Equivalent | R4B `MedicationDispense.implicitRules` maps as Equivalent to R5 `MedicationDispense.implicitRules` |
| MedicationDispense.language | MedicationDispense.language | RelatedTo | R4B `MedicationDispense.language` maps as RelatedTo to R5 `MedicationDispense.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| MedicationDispense.location | MedicationDispense.location | Equivalent | R4B `MedicationDispense.location` maps as Equivalent to R5 `MedicationDispense.location` |
| MedicationDispense.medication[x] | - | DoesNotExistInTarget | R4B `MedicationDispense.medication[x]` does not appear in the target and has no mapping for `MedicationDispense`. |
| MedicationDispense.meta | MedicationDispense.meta | Equivalent | R4B `MedicationDispense.meta` maps as Equivalent to R5 `MedicationDispense.meta` |
| MedicationDispense.modifierExtension | MedicationDispense.modifierExtension | RelatedTo | R4B `MedicationDispense.modifierExtension` maps as RelatedTo to R5 `MedicationDispense.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicationDispense.note | MedicationDispense.note | SourceIsNarrowerThanTarget | R4B `MedicationDispense.note` maps as SourceIsNarrowerThanTarget to R5 `MedicationDispense.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| MedicationDispense.partOf | MedicationDispense.partOf | SourceIsNarrowerThanTarget | R4B `MedicationDispense.partOf` maps as SourceIsNarrowerThanTarget to R5 `MedicationDispense.partOf` - partOf has change due to type change: R4B `partOf` `Reference` maps as SourceIsNarrowerThanTarget for R5 `partOf` |
| MedicationDispense.performer | MedicationDispense.performer | Equivalent | R4B `MedicationDispense.performer` maps as Equivalent to R5 `MedicationDispense.performer` |
| MedicationDispense.performer.actor | MedicationDispense.performer.actor | SourceIsNarrowerThanTarget | R4B `MedicationDispense.performer.actor` maps as SourceIsNarrowerThanTarget to R5 `MedicationDispense.performer.actor` - actor has change due to type change: R4B `actor` `Reference` maps as SourceIsNarrowerThanTarget for R5 `actor` |
| MedicationDispense.performer.extension | MedicationDispense.performer.extension | RelatedTo | R4B `MedicationDispense.performer.extension` maps as RelatedTo to R5 `MedicationDispense.performer.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicationDispense.performer.function | MedicationDispense.performer.function | Equivalent | R4B `MedicationDispense.performer.function` maps as Equivalent to R5 `MedicationDispense.performer.function` |
| MedicationDispense.performer.id | MedicationDispense.performer.id | Equivalent | R4B `MedicationDispense.performer.id` maps as Equivalent to R5 `MedicationDispense.performer.id` |
| MedicationDispense.performer.modifierExtension | MedicationDispense.performer.modifierExtension | RelatedTo | R4B `MedicationDispense.performer.modifierExtension` maps as RelatedTo to R5 `MedicationDispense.performer.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicationDispense.quantity | MedicationDispense.quantity | Equivalent | R4B `MedicationDispense.quantity` maps as Equivalent to R5 `MedicationDispense.quantity` |
| MedicationDispense.receiver | MedicationDispense.receiver | SourceIsNarrowerThanTarget | R4B `MedicationDispense.receiver` maps as SourceIsNarrowerThanTarget to R5 `MedicationDispense.receiver` - receiver has change due to type change: R4B `receiver` `Reference` maps as SourceIsNarrowerThanTarget for R5 `receiver` |
| MedicationDispense.status | MedicationDispense.status | Equivalent | R4B `MedicationDispense.status` maps as Equivalent to R5 `MedicationDispense.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/medicationdispense-status|4.3.0 and http://hl7.org/fhir/ValueSet/medicationdispense-status|5.0.0 (Equivalent) |
| MedicationDispense.statusReason[x] | - | DoesNotExistInTarget | R4B `MedicationDispense.statusReason[x]` does not appear in the target and has no mapping for `MedicationDispense`. |
| MedicationDispense.subject | MedicationDispense.subject | RelatedTo | R4B `MedicationDispense.subject` maps as RelatedTo to R5 `MedicationDispense.subject` - subject made the element mandatory; subject increased the minimum cardinality from 0 to 1 |
| MedicationDispense.substitution | MedicationDispense.substitution | Equivalent | R4B `MedicationDispense.substitution` maps as Equivalent to R5 `MedicationDispense.substitution` |
| MedicationDispense.substitution.extension | MedicationDispense.substitution.extension | RelatedTo | R4B `MedicationDispense.substitution.extension` maps as RelatedTo to R5 `MedicationDispense.substitution.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicationDispense.substitution.id | MedicationDispense.substitution.id | Equivalent | R4B `MedicationDispense.substitution.id` maps as Equivalent to R5 `MedicationDispense.substitution.id` |
| MedicationDispense.substitution.modifierExtension | MedicationDispense.substitution.modifierExtension | RelatedTo | R4B `MedicationDispense.substitution.modifierExtension` maps as RelatedTo to R5 `MedicationDispense.substitution.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicationDispense.substitution.reason | MedicationDispense.substitution.reason | Equivalent | R4B `MedicationDispense.substitution.reason` maps as Equivalent to R5 `MedicationDispense.substitution.reason` |
| MedicationDispense.substitution.responsibleParty | MedicationDispense.substitution.responsibleParty | RelatedTo | R4B `MedicationDispense.substitution.responsibleParty` maps as RelatedTo to R5 `MedicationDispense.substitution.responsibleParty` - responsibleParty changed from array to scalar (max cardinality from * to 1); responsibleParty has change due to type change: R4B `responsibleParty` `Reference` maps as SourceIsNarrowerThanTarget for R5 `responsibleParty` |
| MedicationDispense.substitution.type | MedicationDispense.substitution.type | Equivalent | R4B `MedicationDispense.substitution.type` maps as Equivalent to R5 `MedicationDispense.substitution.type` |
| MedicationDispense.substitution.wasSubstituted | MedicationDispense.substitution.wasSubstituted | Equivalent | R4B `MedicationDispense.substitution.wasSubstituted` maps as Equivalent to R5 `MedicationDispense.substitution.wasSubstituted` |
| MedicationDispense.supportingInformation | MedicationDispense.supportingInformation | Equivalent | R4B `MedicationDispense.supportingInformation` maps as Equivalent to R5 `MedicationDispense.supportingInformation` |
| MedicationDispense.text | MedicationDispense.text | Equivalent | R4B `MedicationDispense.text` maps as Equivalent to R5 `MedicationDispense.text` |
| MedicationDispense.type | MedicationDispense.type | Equivalent | R4B `MedicationDispense.type` maps as Equivalent to R5 `MedicationDispense.type` |
| MedicationDispense.whenHandedOver | MedicationDispense.whenHandedOver | Equivalent | R4B `MedicationDispense.whenHandedOver` maps as Equivalent to R5 `MedicationDispense.whenHandedOver` |
| MedicationDispense.whenPrepared | MedicationDispense.whenPrepared | Equivalent | R4B `MedicationDispense.whenPrepared` maps as Equivalent to R5 `MedicationDispense.whenPrepared` |

