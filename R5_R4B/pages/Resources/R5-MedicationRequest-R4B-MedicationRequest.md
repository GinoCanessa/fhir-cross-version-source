Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MedicationRequest |  | An order or request for both supply of the medication and the instructions for administration of the medication to a patient. The resource is called "MedicationRequest" rather than "MedicationPrescription" or "MedicationOrder" to generalize the use across inpatient and outpatient settings, including care plans, etc., and to harmonize with workflow patterns. | 64 | 47 |
| Target | MedicationRequest |  | An order or request for both supply of the medication and the instructions for administration of the medication to a patient. The resource is called "MedicationRequest" rather than "MedicationPrescription" or "MedicationOrder" to generalize the use across inpatient and outpatient settings, including care plans, etc., and to harmonize with workflow patterns. | 61 | 44 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 11 |
Equivalent | 4 |
RelatedTo | 49 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MedicationRequest | MedicationRequest | Equivalent | R5 `MedicationRequest` maps as Equivalent to R4B `MedicationRequest` |
| MedicationRequest.authoredOn | MedicationRequest.authoredOn | Equivalent | R5 `MedicationRequest.authoredOn` maps as Equivalent to R4B `MedicationRequest.authoredOn` |
| MedicationRequest.basedOn | MedicationRequest.basedOn | Equivalent | R5 `MedicationRequest.basedOn` maps as Equivalent to R4B `MedicationRequest.basedOn` |
| MedicationRequest.category | MedicationRequest.category | Equivalent | R5 `MedicationRequest.category` maps as Equivalent to R4B `MedicationRequest.category` |
| MedicationRequest.contained | MedicationRequest.contained | Equivalent | R5 `MedicationRequest.contained` maps as Equivalent to R4B `MedicationRequest.contained` |
| MedicationRequest.courseOfTherapyType | MedicationRequest.courseOfTherapyType | RelatedTo | R5 `MedicationRequest.courseOfTherapyType` maps as RelatedTo to R4B `MedicationRequest.courseOfTherapyType` - courseOfTherapyType changed the binding strength from Extensible to Example |
| MedicationRequest.device | - | DoesNotExistInTarget | R5 `MedicationRequest.device` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.dispenseRequest | MedicationRequest.dispenseRequest | Equivalent | R5 `MedicationRequest.dispenseRequest` maps as Equivalent to R4B `MedicationRequest.dispenseRequest` |
| MedicationRequest.dispenseRequest.dispenseInterval | MedicationRequest.dispenseRequest.dispenseInterval | Equivalent | R5 `MedicationRequest.dispenseRequest.dispenseInterval` maps as Equivalent to R4B `MedicationRequest.dispenseRequest.dispenseInterval` |
| MedicationRequest.dispenseRequest.dispenser | - | DoesNotExistInTarget | R5 `MedicationRequest.dispenseRequest.dispenser` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.dispenseRequest.dispenserInstruction | - | DoesNotExistInTarget | R5 `MedicationRequest.dispenseRequest.dispenserInstruction` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.dispenseRequest.doseAdministrationAid | - | DoesNotExistInTarget | R5 `MedicationRequest.dispenseRequest.doseAdministrationAid` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.dispenseRequest.expectedSupplyDuration | MedicationRequest.dispenseRequest.expectedSupplyDuration | Equivalent | R5 `MedicationRequest.dispenseRequest.expectedSupplyDuration` maps as Equivalent to R4B `MedicationRequest.dispenseRequest.expectedSupplyDuration` |
| MedicationRequest.dispenseRequest.extension | MedicationRequest.dispenseRequest.extension | SourceIsBroaderThanTarget | R5 `MedicationRequest.dispenseRequest.extension` maps as SourceIsBroaderThanTarget to R4B `MedicationRequest.dispenseRequest.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| MedicationRequest.dispenseRequest.id | MedicationRequest.dispenseRequest.id | Equivalent | R5 `MedicationRequest.dispenseRequest.id` maps as Equivalent to R4B `MedicationRequest.dispenseRequest.id` |
| MedicationRequest.dispenseRequest.initialFill | MedicationRequest.dispenseRequest.initialFill | Equivalent | R5 `MedicationRequest.dispenseRequest.initialFill` maps as Equivalent to R4B `MedicationRequest.dispenseRequest.initialFill` |
| MedicationRequest.dispenseRequest.initialFill.duration | MedicationRequest.dispenseRequest.initialFill.duration | Equivalent | R5 `MedicationRequest.dispenseRequest.initialFill.duration` maps as Equivalent to R4B `MedicationRequest.dispenseRequest.initialFill.duration` |
| MedicationRequest.dispenseRequest.initialFill.extension | MedicationRequest.dispenseRequest.initialFill.extension | SourceIsBroaderThanTarget | R5 `MedicationRequest.dispenseRequest.initialFill.extension` maps as SourceIsBroaderThanTarget to R4B `MedicationRequest.dispenseRequest.initialFill.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| MedicationRequest.dispenseRequest.initialFill.id | MedicationRequest.dispenseRequest.initialFill.id | Equivalent | R5 `MedicationRequest.dispenseRequest.initialFill.id` maps as Equivalent to R4B `MedicationRequest.dispenseRequest.initialFill.id` |
| MedicationRequest.dispenseRequest.initialFill.modifierExtension | MedicationRequest.dispenseRequest.initialFill.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationRequest.dispenseRequest.initialFill.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `MedicationRequest.dispenseRequest.initialFill.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| MedicationRequest.dispenseRequest.initialFill.quantity | MedicationRequest.dispenseRequest.initialFill.quantity | Equivalent | R5 `MedicationRequest.dispenseRequest.initialFill.quantity` maps as Equivalent to R4B `MedicationRequest.dispenseRequest.initialFill.quantity` |
| MedicationRequest.dispenseRequest.modifierExtension | MedicationRequest.dispenseRequest.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationRequest.dispenseRequest.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `MedicationRequest.dispenseRequest.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| MedicationRequest.dispenseRequest.numberOfRepeatsAllowed | MedicationRequest.dispenseRequest.numberOfRepeatsAllowed | Equivalent | R5 `MedicationRequest.dispenseRequest.numberOfRepeatsAllowed` maps as Equivalent to R4B `MedicationRequest.dispenseRequest.numberOfRepeatsAllowed` |
| MedicationRequest.dispenseRequest.quantity | MedicationRequest.dispenseRequest.quantity | Equivalent | R5 `MedicationRequest.dispenseRequest.quantity` maps as Equivalent to R4B `MedicationRequest.dispenseRequest.quantity` |
| MedicationRequest.dispenseRequest.validityPeriod | MedicationRequest.dispenseRequest.validityPeriod | Equivalent | R5 `MedicationRequest.dispenseRequest.validityPeriod` maps as Equivalent to R4B `MedicationRequest.dispenseRequest.validityPeriod` |
| MedicationRequest.doNotPerform | MedicationRequest.doNotPerform | Equivalent | R5 `MedicationRequest.doNotPerform` maps as Equivalent to R4B `MedicationRequest.doNotPerform` |
| MedicationRequest.dosageInstruction | MedicationRequest.dosageInstruction | RelatedTo | R5 `MedicationRequest.dosageInstruction` maps as RelatedTo to R4B `MedicationRequest.dosageInstruction` - dosageInstruction has change due to type change: R5 `dosageInstruction` `Dosage` maps as RelatedTo for R4B `dosageInstruction` |
| MedicationRequest.effectiveDosePeriod | - | DoesNotExistInTarget | R5 `MedicationRequest.effectiveDosePeriod` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.encounter | MedicationRequest.encounter | Equivalent | R5 `MedicationRequest.encounter` maps as Equivalent to R4B `MedicationRequest.encounter` |
| MedicationRequest.eventHistory | MedicationRequest.eventHistory | Equivalent | R5 `MedicationRequest.eventHistory` maps as Equivalent to R4B `MedicationRequest.eventHistory` |
| MedicationRequest.extension | MedicationRequest.extension | SourceIsBroaderThanTarget | R5 `MedicationRequest.extension` maps as SourceIsBroaderThanTarget to R4B `MedicationRequest.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| MedicationRequest.groupIdentifier | MedicationRequest.groupIdentifier | Equivalent | R5 `MedicationRequest.groupIdentifier` maps as Equivalent to R4B `MedicationRequest.groupIdentifier` |
| MedicationRequest.id | MedicationRequest.id | Equivalent | R5 `MedicationRequest.id` maps as Equivalent to R4B `MedicationRequest.id` |
| MedicationRequest.identifier | MedicationRequest.identifier | Equivalent | R5 `MedicationRequest.identifier` maps as Equivalent to R4B `MedicationRequest.identifier` |
| MedicationRequest.implicitRules | MedicationRequest.implicitRules | Equivalent | R5 `MedicationRequest.implicitRules` maps as Equivalent to R4B `MedicationRequest.implicitRules` |
| MedicationRequest.informationSource | - | DoesNotExistInTarget | R5 `MedicationRequest.informationSource` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.insurance | MedicationRequest.insurance | Equivalent | R5 `MedicationRequest.insurance` maps as Equivalent to R4B `MedicationRequest.insurance` |
| MedicationRequest.intent | MedicationRequest.intent | Equivalent | R5 `MedicationRequest.intent` maps as Equivalent to R4B `MedicationRequest.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/medicationrequest-intent|5.0.0 and http://hl7.org/fhir/ValueSet/medicationrequest-intent|4.3.0 (Equivalent) |
| MedicationRequest.language | MedicationRequest.language | RelatedTo | R5 `MedicationRequest.language` maps as RelatedTo to R4B `MedicationRequest.language` - language changed the binding strength from Required to Preferred |
| MedicationRequest.medication | - | DoesNotExistInTarget | R5 `MedicationRequest.medication` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.meta | MedicationRequest.meta | Equivalent | R5 `MedicationRequest.meta` maps as Equivalent to R4B `MedicationRequest.meta` |
| MedicationRequest.modifierExtension | MedicationRequest.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationRequest.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `MedicationRequest.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| MedicationRequest.note | MedicationRequest.note | SourceIsBroaderThanTarget | R5 `MedicationRequest.note` maps as SourceIsBroaderThanTarget to R4B `MedicationRequest.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| MedicationRequest.performer | MedicationRequest.performer | RelatedTo | R5 `MedicationRequest.performer` maps as RelatedTo to R4B `MedicationRequest.performer` - performer changed from array to scalar (max cardinality from * to 1); performer has change due to type change: R5 `performer` `Reference` maps as RelatedTo for R4B `performer` |
| MedicationRequest.performerType | MedicationRequest.performerType | RelatedTo | R5 `MedicationRequest.performerType` maps as RelatedTo to R4B `MedicationRequest.performerType` - performerType changed the binding strength from Extensible to Example |
| MedicationRequest.priority | MedicationRequest.priority | Equivalent | R5 `MedicationRequest.priority` maps as Equivalent to R4B `MedicationRequest.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|5.0.0 and http://hl7.org/fhir/ValueSet/request-priority|4.3.0 (Equivalent) |
| MedicationRequest.priorPrescription | MedicationRequest.priorPrescription | Equivalent | R5 `MedicationRequest.priorPrescription` maps as Equivalent to R4B `MedicationRequest.priorPrescription` |
| MedicationRequest.reason | - | DoesNotExistInTarget | R5 `MedicationRequest.reason` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.recorder | MedicationRequest.recorder | Equivalent | R5 `MedicationRequest.recorder` maps as Equivalent to R4B `MedicationRequest.recorder` |
| MedicationRequest.renderedDosageInstruction | - | DoesNotExistInTarget | R5 `MedicationRequest.renderedDosageInstruction` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.reported | - | DoesNotExistInTarget | R5 `MedicationRequest.reported` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.requester | MedicationRequest.requester | Equivalent | R5 `MedicationRequest.requester` maps as Equivalent to R4B `MedicationRequest.requester` |
| MedicationRequest.status | MedicationRequest.status | SourceIsNarrowerThanTarget | R5 `MedicationRequest.status` maps as SourceIsNarrowerThanTarget to R4B `MedicationRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/medicationrequest-status|5.0.0 and http://hl7.org/fhir/ValueSet/medicationrequest-status|4.3.0 (SourceIsNarrowerThanTarget) |
| MedicationRequest.statusChanged | - | DoesNotExistInTarget | R5 `MedicationRequest.statusChanged` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.statusReason | MedicationRequest.statusReason | Equivalent | R5 `MedicationRequest.statusReason` maps as Equivalent to R4B `MedicationRequest.statusReason` |
| MedicationRequest.subject | MedicationRequest.subject | Equivalent | R5 `MedicationRequest.subject` maps as Equivalent to R4B `MedicationRequest.subject` |
| MedicationRequest.substitution | MedicationRequest.substitution | Equivalent | R5 `MedicationRequest.substitution` maps as Equivalent to R4B `MedicationRequest.substitution` |
| MedicationRequest.substitution.allowed[x] | MedicationRequest.substitution.allowed[x] | RelatedTo | R5 `MedicationRequest.substitution.allowed[x]` maps as RelatedTo to R4B `MedicationRequest.substitution.allowed[x]` - allowed[x] changed the binding strength from Preferred to Example |
| MedicationRequest.substitution.extension | MedicationRequest.substitution.extension | SourceIsBroaderThanTarget | R5 `MedicationRequest.substitution.extension` maps as SourceIsBroaderThanTarget to R4B `MedicationRequest.substitution.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| MedicationRequest.substitution.id | MedicationRequest.substitution.id | Equivalent | R5 `MedicationRequest.substitution.id` maps as Equivalent to R4B `MedicationRequest.substitution.id` |
| MedicationRequest.substitution.modifierExtension | MedicationRequest.substitution.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationRequest.substitution.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `MedicationRequest.substitution.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| MedicationRequest.substitution.reason | MedicationRequest.substitution.reason | Equivalent | R5 `MedicationRequest.substitution.reason` maps as Equivalent to R4B `MedicationRequest.substitution.reason` |
| MedicationRequest.supportingInformation | MedicationRequest.supportingInformation | Equivalent | R5 `MedicationRequest.supportingInformation` maps as Equivalent to R4B `MedicationRequest.supportingInformation` |
| MedicationRequest.text | MedicationRequest.text | Equivalent | R5 `MedicationRequest.text` maps as Equivalent to R4B `MedicationRequest.text` |

