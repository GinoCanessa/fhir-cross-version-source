Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MedicationRequest |  | An order or request for both supply of the medication and the instructions for administration of the medication to a patient. The resource is called "MedicationRequest" rather than "MedicationPrescription" or "MedicationOrder" to generalize the use across inpatient and outpatient settings, including care plans, etc., and to harmonize with workflow patterns. | 64 | 47 |
| Target | MedicationRequest |  | An order or request for both supply of the medication and the instructions for administration of the medication to a patient. The resource is called "MedicationRequest" rather than "MedicationPrescription" or "MedicationOrder" to generalize the use across inpatient and outpatient settings, including care plans, etc., and to harmonize with workflow patterns. | 61 | 44 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 7 |
Equivalent | 40 |
RelatedTo | 2 |
SourceIsBroaderThanTarget | 11 |
SourceIsNarrowerThanTarget | 4 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MedicationRequest | MedicationRequest | Equivalent | R5 `MedicationRequest` maps as Equivalent to R4 `MedicationRequest` |
| MedicationRequest.authoredOn | MedicationRequest.authoredOn | Equivalent | R5 `MedicationRequest.authoredOn` maps as Equivalent to R4 `MedicationRequest.authoredOn` |
| MedicationRequest.basedOn | MedicationRequest.basedOn | Equivalent | R5 `MedicationRequest.basedOn` maps as Equivalent to R4 `MedicationRequest.basedOn` |
| MedicationRequest.category | MedicationRequest.category | Equivalent | R5 `MedicationRequest.category` maps as Equivalent to R4 `MedicationRequest.category` |
| MedicationRequest.contained | MedicationRequest.contained | Equivalent | R5 `MedicationRequest.contained` maps as Equivalent to R4 `MedicationRequest.contained` |
| MedicationRequest.courseOfTherapyType | MedicationRequest.courseOfTherapyType | SourceIsNarrowerThanTarget | R5 `MedicationRequest.courseOfTherapyType` maps as SourceIsNarrowerThanTarget to R4 `MedicationRequest.courseOfTherapyType` - courseOfTherapyType changed the binding strength from Extensible to Example; courseOfTherapyType has change due to type change: R5 `courseOfTherapyType` `CodeableConcept` maps as SourceIsNarrowerThanTarget for R4 `courseOfTherapyType` |
| MedicationRequest.device | - | DoesNotExistInTarget | R5 `MedicationRequest.device` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.dispenseRequest | MedicationRequest.dispenseRequest | Equivalent | R5 `MedicationRequest.dispenseRequest` maps as Equivalent to R4 `MedicationRequest.dispenseRequest` |
| MedicationRequest.dispenseRequest.dispenseInterval | MedicationRequest.dispenseRequest.dispenseInterval | Equivalent | R5 `MedicationRequest.dispenseRequest.dispenseInterval` maps as Equivalent to R4 `MedicationRequest.dispenseRequest.dispenseInterval` |
| MedicationRequest.dispenseRequest.dispenser | MedicationRequest.dispenseRequest.performer | Equivalent | R5 `MedicationRequest.dispenseRequest.dispenser` maps as Equivalent to R4 `MedicationRequest.dispenseRequest.performer` |
| MedicationRequest.dispenseRequest.dispenserInstruction | - | DoesNotExistInTarget | R5 `MedicationRequest.dispenseRequest.dispenserInstruction` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.dispenseRequest.doseAdministrationAid | - | DoesNotExistInTarget | R5 `MedicationRequest.dispenseRequest.doseAdministrationAid` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.dispenseRequest.expectedSupplyDuration | MedicationRequest.dispenseRequest.expectedSupplyDuration | Equivalent | R5 `MedicationRequest.dispenseRequest.expectedSupplyDuration` maps as Equivalent to R4 `MedicationRequest.dispenseRequest.expectedSupplyDuration` |
| MedicationRequest.dispenseRequest.extension | MedicationRequest.dispenseRequest.extension | SourceIsBroaderThanTarget | R5 `MedicationRequest.dispenseRequest.extension` maps as SourceIsBroaderThanTarget to R4 `MedicationRequest.dispenseRequest.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MedicationRequest.dispenseRequest.id | MedicationRequest.dispenseRequest.id | Equivalent | R5 `MedicationRequest.dispenseRequest.id` maps as Equivalent to R4 `MedicationRequest.dispenseRequest.id` |
| MedicationRequest.dispenseRequest.initialFill | MedicationRequest.dispenseRequest.initialFill | Equivalent | R5 `MedicationRequest.dispenseRequest.initialFill` maps as Equivalent to R4 `MedicationRequest.dispenseRequest.initialFill` |
| MedicationRequest.dispenseRequest.initialFill.duration | MedicationRequest.dispenseRequest.initialFill.duration | Equivalent | R5 `MedicationRequest.dispenseRequest.initialFill.duration` maps as Equivalent to R4 `MedicationRequest.dispenseRequest.initialFill.duration` |
| MedicationRequest.dispenseRequest.initialFill.extension | MedicationRequest.dispenseRequest.initialFill.extension | SourceIsBroaderThanTarget | R5 `MedicationRequest.dispenseRequest.initialFill.extension` maps as SourceIsBroaderThanTarget to R4 `MedicationRequest.dispenseRequest.initialFill.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MedicationRequest.dispenseRequest.initialFill.id | MedicationRequest.dispenseRequest.initialFill.id | Equivalent | R5 `MedicationRequest.dispenseRequest.initialFill.id` maps as Equivalent to R4 `MedicationRequest.dispenseRequest.initialFill.id` |
| MedicationRequest.dispenseRequest.initialFill.modifierExtension | MedicationRequest.dispenseRequest.initialFill.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationRequest.dispenseRequest.initialFill.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MedicationRequest.dispenseRequest.initialFill.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MedicationRequest.dispenseRequest.initialFill.quantity | MedicationRequest.dispenseRequest.initialFill.quantity | Equivalent | R5 `MedicationRequest.dispenseRequest.initialFill.quantity` maps as Equivalent to R4 `MedicationRequest.dispenseRequest.initialFill.quantity` |
| MedicationRequest.dispenseRequest.modifierExtension | MedicationRequest.dispenseRequest.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationRequest.dispenseRequest.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MedicationRequest.dispenseRequest.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MedicationRequest.dispenseRequest.numberOfRepeatsAllowed | MedicationRequest.dispenseRequest.numberOfRepeatsAllowed | Equivalent | R5 `MedicationRequest.dispenseRequest.numberOfRepeatsAllowed` maps as Equivalent to R4 `MedicationRequest.dispenseRequest.numberOfRepeatsAllowed` |
| MedicationRequest.dispenseRequest.quantity | MedicationRequest.dispenseRequest.quantity | Equivalent | R5 `MedicationRequest.dispenseRequest.quantity` maps as Equivalent to R4 `MedicationRequest.dispenseRequest.quantity` |
| MedicationRequest.dispenseRequest.validityPeriod | MedicationRequest.dispenseRequest.validityPeriod | Equivalent | R5 `MedicationRequest.dispenseRequest.validityPeriod` maps as Equivalent to R4 `MedicationRequest.dispenseRequest.validityPeriod` |
| MedicationRequest.doNotPerform | MedicationRequest.doNotPerform | Equivalent | R5 `MedicationRequest.doNotPerform` maps as Equivalent to R4 `MedicationRequest.doNotPerform` |
| MedicationRequest.dosageInstruction | MedicationRequest.dosageInstruction | SourceIsBroaderThanTarget | R5 `MedicationRequest.dosageInstruction` maps as SourceIsBroaderThanTarget to R4 `MedicationRequest.dosageInstruction` - dosageInstruction has change due to type change: R5 `dosageInstruction` `Dosage` maps as SourceIsBroaderThanTarget for R4 `dosageInstruction` |
| MedicationRequest.effectiveDosePeriod | - | DoesNotExistInTarget | R5 `MedicationRequest.effectiveDosePeriod` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.encounter | MedicationRequest.encounter | Equivalent | R5 `MedicationRequest.encounter` maps as Equivalent to R4 `MedicationRequest.encounter` |
| MedicationRequest.eventHistory | MedicationRequest.eventHistory | Equivalent | R5 `MedicationRequest.eventHistory` maps as Equivalent to R4 `MedicationRequest.eventHistory` |
| MedicationRequest.extension | MedicationRequest.extension | SourceIsBroaderThanTarget | R5 `MedicationRequest.extension` maps as SourceIsBroaderThanTarget to R4 `MedicationRequest.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MedicationRequest.groupIdentifier | MedicationRequest.groupIdentifier | Equivalent | R5 `MedicationRequest.groupIdentifier` maps as Equivalent to R4 `MedicationRequest.groupIdentifier` |
| MedicationRequest.id | MedicationRequest.id | Equivalent | R5 `MedicationRequest.id` maps as Equivalent to R4 `MedicationRequest.id` |
| MedicationRequest.identifier | MedicationRequest.identifier | Equivalent | R5 `MedicationRequest.identifier` maps as Equivalent to R4 `MedicationRequest.identifier` |
| MedicationRequest.implicitRules | MedicationRequest.implicitRules | Equivalent | R5 `MedicationRequest.implicitRules` maps as Equivalent to R4 `MedicationRequest.implicitRules` |
| MedicationRequest.informationSource | - | DoesNotExistInTarget | R5 `MedicationRequest.informationSource` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.insurance | MedicationRequest.insurance | Equivalent | R5 `MedicationRequest.insurance` maps as Equivalent to R4 `MedicationRequest.insurance` |
| MedicationRequest.intent | MedicationRequest.intent | Equivalent | R5 `MedicationRequest.intent` maps as Equivalent to R4 `MedicationRequest.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/medicationrequest-intent|5.0.0 and http://hl7.org/fhir/ValueSet/medicationrequest-intent|4.0.1 (Equivalent) |
| MedicationRequest.language | MedicationRequest.language | SourceIsNarrowerThanTarget | R5 `MedicationRequest.language` maps as SourceIsNarrowerThanTarget to R4 `MedicationRequest.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| MedicationRequest.medication | MedicationRequest.medication[x] | SourceIsBroaderThanTarget | R5 `MedicationRequest.medication` maps as SourceIsBroaderThanTarget to R4 `MedicationRequest.medication[x]` - medication[x] has change due to type change: R5 medication CodeableReference has no equivalent or mapped type in R4 medication[x] |
| MedicationRequest.meta | MedicationRequest.meta | Equivalent | R5 `MedicationRequest.meta` maps as Equivalent to R4 `MedicationRequest.meta` |
| MedicationRequest.modifierExtension | MedicationRequest.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationRequest.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MedicationRequest.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MedicationRequest.note | MedicationRequest.note | SourceIsBroaderThanTarget | R5 `MedicationRequest.note` maps as SourceIsBroaderThanTarget to R4 `MedicationRequest.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| MedicationRequest.performer | MedicationRequest.performer | RelatedTo | R5 `MedicationRequest.performer` maps as RelatedTo to R4 `MedicationRequest.performer` - performer changed from array to scalar (max cardinality from * to 1); performer has change due to type change: R5 `performer` `Reference` maps as RelatedTo for R4 `performer` |
| MedicationRequest.performerType | MedicationRequest.performerType | SourceIsNarrowerThanTarget | R5 `MedicationRequest.performerType` maps as SourceIsNarrowerThanTarget to R4 `MedicationRequest.performerType` - performerType changed the binding strength from Extensible to Example; performerType has change due to type change: R5 `performerType` `CodeableConcept` maps as SourceIsNarrowerThanTarget for R4 `performerType` |
| MedicationRequest.priority | MedicationRequest.priority | Equivalent | R5 `MedicationRequest.priority` maps as Equivalent to R4 `MedicationRequest.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|5.0.0 and http://hl7.org/fhir/ValueSet/request-priority|4.0.1 (Equivalent) |
| MedicationRequest.priorPrescription | MedicationRequest.priorPrescription | Equivalent | R5 `MedicationRequest.priorPrescription` maps as Equivalent to R4 `MedicationRequest.priorPrescription` |
| MedicationRequest.reason | MedicationRequest.reasonCode | SourceIsBroaderThanTarget | R5 `MedicationRequest.reason` maps as SourceIsBroaderThanTarget to R4 `MedicationRequest.reasonCode` - reasonCode has change due to type change: R5 reason CodeableReference has no equivalent or mapped type in R4 reasonCode |
| MedicationRequest.reason | MedicationRequest.reasonReference | RelatedTo | R5 `MedicationRequest.reason` maps as RelatedTo to R4 `MedicationRequest.reasonReference` - reasonReference removed a binding requirement - Example http://hl7.org/fhir/ValueSet/condition-code; reasonReference has change due to type change: R5 reason CodeableReference has no equivalent or mapped type in R4 reasonReference |
| MedicationRequest.recorder | MedicationRequest.recorder | Equivalent | R5 `MedicationRequest.recorder` maps as Equivalent to R4 `MedicationRequest.recorder` |
| MedicationRequest.renderedDosageInstruction | - | DoesNotExistInTarget | R5 `MedicationRequest.renderedDosageInstruction` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.reported | MedicationRequest.reported[x] | Equivalent | R5 `MedicationRequest.reported` maps as Equivalent to R4 `MedicationRequest.reported[x]` |
| MedicationRequest.requester | MedicationRequest.requester | Equivalent | R5 `MedicationRequest.requester` maps as Equivalent to R4 `MedicationRequest.requester` |
| MedicationRequest.status | MedicationRequest.status | Equivalent | R5 `MedicationRequest.status` maps as Equivalent to R4 `MedicationRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/medicationrequest-status|5.0.0 and http://hl7.org/fhir/ValueSet/medicationrequest-status|4.0.1 (Equivalent) |
| MedicationRequest.statusChanged | - | DoesNotExistInTarget | R5 `MedicationRequest.statusChanged` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.statusReason | MedicationRequest.statusReason | Equivalent | R5 `MedicationRequest.statusReason` maps as Equivalent to R4 `MedicationRequest.statusReason` |
| MedicationRequest.subject | MedicationRequest.subject | Equivalent | R5 `MedicationRequest.subject` maps as Equivalent to R4 `MedicationRequest.subject` |
| MedicationRequest.substitution | MedicationRequest.substitution | Equivalent | R5 `MedicationRequest.substitution` maps as Equivalent to R4 `MedicationRequest.substitution` |
| MedicationRequest.substitution.allowed[x] | MedicationRequest.substitution.allowed[x] | SourceIsNarrowerThanTarget | R5 `MedicationRequest.substitution.allowed[x]` maps as SourceIsNarrowerThanTarget to R4 `MedicationRequest.substitution.allowed[x]` - allowed[x] changed the binding strength from Preferred to Example; allowed[x] has change due to type change: R5 `allowed[x]` `boolean` maps as SourceIsNarrowerThanTarget for R4 `allowed[x]`; allowed[x] has change due to type change: R5 `allowed[x]` `CodeableConcept` maps as SourceIsNarrowerThanTarget for R4 `allowed[x]` |
| MedicationRequest.substitution.extension | MedicationRequest.substitution.extension | SourceIsBroaderThanTarget | R5 `MedicationRequest.substitution.extension` maps as SourceIsBroaderThanTarget to R4 `MedicationRequest.substitution.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MedicationRequest.substitution.id | MedicationRequest.substitution.id | Equivalent | R5 `MedicationRequest.substitution.id` maps as Equivalent to R4 `MedicationRequest.substitution.id` |
| MedicationRequest.substitution.modifierExtension | MedicationRequest.substitution.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationRequest.substitution.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MedicationRequest.substitution.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MedicationRequest.substitution.reason | MedicationRequest.substitution.reason | Equivalent | R5 `MedicationRequest.substitution.reason` maps as Equivalent to R4 `MedicationRequest.substitution.reason` |
| MedicationRequest.supportingInformation | MedicationRequest.supportingInformation | Equivalent | R5 `MedicationRequest.supportingInformation` maps as Equivalent to R4 `MedicationRequest.supportingInformation` |
| MedicationRequest.text | MedicationRequest.text | Equivalent | R5 `MedicationRequest.text` maps as Equivalent to R4 `MedicationRequest.text` |

