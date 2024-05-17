Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MedicationRequest |  | An order or request for both supply of the medication and the instructions for administration of the medication to a patient. The resource is called "MedicationRequest" rather than "MedicationPrescription" or "MedicationOrder" to generalize the use across inpatient and outpatient settings, including care plans, etc., and to harmonize with workflow patterns. | 61 | 44 |
| Target | MedicationRequest |  | An order or request for both supply of the medication and the instructions for administration of the medication to a patient. The resource is called "MedicationRequest" rather than "MedicationPrescription" or "MedicationOrder" to generalize the use across inpatient and outpatient settings, including care plans, etc., and to harmonize with workflow patterns. | 64 | 47 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 8 |
Equivalent | 4 |
RelatedTo | 49 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MedicationRequest | MedicationRequest | Equivalent | R4B `MedicationRequest` maps as Equivalent to R5 `MedicationRequest` |
| MedicationRequest.authoredOn | MedicationRequest.authoredOn | Equivalent | R4B `MedicationRequest.authoredOn` maps as Equivalent to R5 `MedicationRequest.authoredOn` |
| MedicationRequest.basedOn | MedicationRequest.basedOn | Equivalent | R4B `MedicationRequest.basedOn` maps as Equivalent to R5 `MedicationRequest.basedOn` |
| MedicationRequest.category | MedicationRequest.category | Equivalent | R4B `MedicationRequest.category` maps as Equivalent to R5 `MedicationRequest.category` |
| MedicationRequest.contained | MedicationRequest.contained | Equivalent | R4B `MedicationRequest.contained` maps as Equivalent to R5 `MedicationRequest.contained` |
| MedicationRequest.courseOfTherapyType | MedicationRequest.courseOfTherapyType | RelatedTo | R4B `MedicationRequest.courseOfTherapyType` maps as RelatedTo to R5 `MedicationRequest.courseOfTherapyType` - courseOfTherapyType changed the binding strength from Example to Extensible |
| MedicationRequest.detectedIssue | - | DoesNotExistInTarget | R4B `MedicationRequest.detectedIssue` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.dispenseRequest | MedicationRequest.dispenseRequest | Equivalent | R4B `MedicationRequest.dispenseRequest` maps as Equivalent to R5 `MedicationRequest.dispenseRequest` |
| MedicationRequest.dispenseRequest.dispenseInterval | MedicationRequest.dispenseRequest.dispenseInterval | Equivalent | R4B `MedicationRequest.dispenseRequest.dispenseInterval` maps as Equivalent to R5 `MedicationRequest.dispenseRequest.dispenseInterval` |
| MedicationRequest.dispenseRequest.expectedSupplyDuration | MedicationRequest.dispenseRequest.expectedSupplyDuration | Equivalent | R4B `MedicationRequest.dispenseRequest.expectedSupplyDuration` maps as Equivalent to R5 `MedicationRequest.dispenseRequest.expectedSupplyDuration` |
| MedicationRequest.dispenseRequest.extension | MedicationRequest.dispenseRequest.extension | RelatedTo | R4B `MedicationRequest.dispenseRequest.extension` maps as RelatedTo to R5 `MedicationRequest.dispenseRequest.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicationRequest.dispenseRequest.id | MedicationRequest.dispenseRequest.id | Equivalent | R4B `MedicationRequest.dispenseRequest.id` maps as Equivalent to R5 `MedicationRequest.dispenseRequest.id` |
| MedicationRequest.dispenseRequest.initialFill | MedicationRequest.dispenseRequest.initialFill | Equivalent | R4B `MedicationRequest.dispenseRequest.initialFill` maps as Equivalent to R5 `MedicationRequest.dispenseRequest.initialFill` |
| MedicationRequest.dispenseRequest.initialFill.duration | MedicationRequest.dispenseRequest.initialFill.duration | Equivalent | R4B `MedicationRequest.dispenseRequest.initialFill.duration` maps as Equivalent to R5 `MedicationRequest.dispenseRequest.initialFill.duration` |
| MedicationRequest.dispenseRequest.initialFill.extension | MedicationRequest.dispenseRequest.initialFill.extension | RelatedTo | R4B `MedicationRequest.dispenseRequest.initialFill.extension` maps as RelatedTo to R5 `MedicationRequest.dispenseRequest.initialFill.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicationRequest.dispenseRequest.initialFill.id | MedicationRequest.dispenseRequest.initialFill.id | Equivalent | R4B `MedicationRequest.dispenseRequest.initialFill.id` maps as Equivalent to R5 `MedicationRequest.dispenseRequest.initialFill.id` |
| MedicationRequest.dispenseRequest.initialFill.modifierExtension | MedicationRequest.dispenseRequest.initialFill.modifierExtension | RelatedTo | R4B `MedicationRequest.dispenseRequest.initialFill.modifierExtension` maps as RelatedTo to R5 `MedicationRequest.dispenseRequest.initialFill.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicationRequest.dispenseRequest.initialFill.quantity | MedicationRequest.dispenseRequest.initialFill.quantity | Equivalent | R4B `MedicationRequest.dispenseRequest.initialFill.quantity` maps as Equivalent to R5 `MedicationRequest.dispenseRequest.initialFill.quantity` |
| MedicationRequest.dispenseRequest.modifierExtension | MedicationRequest.dispenseRequest.modifierExtension | RelatedTo | R4B `MedicationRequest.dispenseRequest.modifierExtension` maps as RelatedTo to R5 `MedicationRequest.dispenseRequest.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicationRequest.dispenseRequest.numberOfRepeatsAllowed | MedicationRequest.dispenseRequest.numberOfRepeatsAllowed | Equivalent | R4B `MedicationRequest.dispenseRequest.numberOfRepeatsAllowed` maps as Equivalent to R5 `MedicationRequest.dispenseRequest.numberOfRepeatsAllowed` |
| MedicationRequest.dispenseRequest.performer | - | DoesNotExistInTarget | R4B `MedicationRequest.dispenseRequest.performer` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.dispenseRequest.quantity | MedicationRequest.dispenseRequest.quantity | Equivalent | R4B `MedicationRequest.dispenseRequest.quantity` maps as Equivalent to R5 `MedicationRequest.dispenseRequest.quantity` |
| MedicationRequest.dispenseRequest.validityPeriod | MedicationRequest.dispenseRequest.validityPeriod | Equivalent | R4B `MedicationRequest.dispenseRequest.validityPeriod` maps as Equivalent to R5 `MedicationRequest.dispenseRequest.validityPeriod` |
| MedicationRequest.doNotPerform | MedicationRequest.doNotPerform | Equivalent | R4B `MedicationRequest.doNotPerform` maps as Equivalent to R5 `MedicationRequest.doNotPerform` |
| MedicationRequest.dosageInstruction | MedicationRequest.dosageInstruction | RelatedTo | R4B `MedicationRequest.dosageInstruction` maps as RelatedTo to R5 `MedicationRequest.dosageInstruction` - dosageInstruction has change due to type change: R4B `dosageInstruction` `Dosage` maps as RelatedTo for R5 `dosageInstruction` |
| MedicationRequest.encounter | MedicationRequest.encounter | Equivalent | R4B `MedicationRequest.encounter` maps as Equivalent to R5 `MedicationRequest.encounter` |
| MedicationRequest.eventHistory | MedicationRequest.eventHistory | Equivalent | R4B `MedicationRequest.eventHistory` maps as Equivalent to R5 `MedicationRequest.eventHistory` |
| MedicationRequest.extension | MedicationRequest.extension | RelatedTo | R4B `MedicationRequest.extension` maps as RelatedTo to R5 `MedicationRequest.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicationRequest.groupIdentifier | MedicationRequest.groupIdentifier | Equivalent | R4B `MedicationRequest.groupIdentifier` maps as Equivalent to R5 `MedicationRequest.groupIdentifier` |
| MedicationRequest.id | MedicationRequest.id | Equivalent | R4B `MedicationRequest.id` maps as Equivalent to R5 `MedicationRequest.id` |
| MedicationRequest.identifier | MedicationRequest.identifier | Equivalent | R4B `MedicationRequest.identifier` maps as Equivalent to R5 `MedicationRequest.identifier` |
| MedicationRequest.implicitRules | MedicationRequest.implicitRules | Equivalent | R4B `MedicationRequest.implicitRules` maps as Equivalent to R5 `MedicationRequest.implicitRules` |
| MedicationRequest.instantiatesCanonical | - | DoesNotExistInTarget | R4B `MedicationRequest.instantiatesCanonical` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.instantiatesUri | - | DoesNotExistInTarget | R4B `MedicationRequest.instantiatesUri` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.insurance | MedicationRequest.insurance | Equivalent | R4B `MedicationRequest.insurance` maps as Equivalent to R5 `MedicationRequest.insurance` |
| MedicationRequest.intent | MedicationRequest.intent | Equivalent | R4B `MedicationRequest.intent` maps as Equivalent to R5 `MedicationRequest.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/medicationrequest-intent|4.3.0 and http://hl7.org/fhir/ValueSet/medicationrequest-intent|5.0.0 (Equivalent) |
| MedicationRequest.language | MedicationRequest.language | RelatedTo | R4B `MedicationRequest.language` maps as RelatedTo to R5 `MedicationRequest.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| MedicationRequest.medication[x] | - | DoesNotExistInTarget | R4B `MedicationRequest.medication[x]` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.meta | MedicationRequest.meta | Equivalent | R4B `MedicationRequest.meta` maps as Equivalent to R5 `MedicationRequest.meta` |
| MedicationRequest.modifierExtension | MedicationRequest.modifierExtension | RelatedTo | R4B `MedicationRequest.modifierExtension` maps as RelatedTo to R5 `MedicationRequest.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicationRequest.note | MedicationRequest.note | SourceIsNarrowerThanTarget | R4B `MedicationRequest.note` maps as SourceIsNarrowerThanTarget to R5 `MedicationRequest.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| MedicationRequest.performer | MedicationRequest.performer | RelatedTo | R4B `MedicationRequest.performer` maps as RelatedTo to R5 `MedicationRequest.performer` - performer changed from scalar to array (max cardinality from 1 to *); performer has change due to type change: R4B `performer` `Reference` maps as RelatedTo for R5 `performer` |
| MedicationRequest.performerType | MedicationRequest.performerType | RelatedTo | R4B `MedicationRequest.performerType` maps as RelatedTo to R5 `MedicationRequest.performerType` - performerType changed the binding strength from Example to Extensible |
| MedicationRequest.priority | MedicationRequest.priority | Equivalent | R4B `MedicationRequest.priority` maps as Equivalent to R5 `MedicationRequest.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|4.3.0 and http://hl7.org/fhir/ValueSet/request-priority|5.0.0 (Equivalent) |
| MedicationRequest.priorPrescription | MedicationRequest.priorPrescription | Equivalent | R4B `MedicationRequest.priorPrescription` maps as Equivalent to R5 `MedicationRequest.priorPrescription` |
| MedicationRequest.reasonCode | - | DoesNotExistInTarget | R4B `MedicationRequest.reasonCode` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.reasonReference | - | DoesNotExistInTarget | R4B `MedicationRequest.reasonReference` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.recorder | MedicationRequest.recorder | Equivalent | R4B `MedicationRequest.recorder` maps as Equivalent to R5 `MedicationRequest.recorder` |
| MedicationRequest.reported[x] | - | DoesNotExistInTarget | R4B `MedicationRequest.reported[x]` does not appear in the target and has no mapping for `MedicationRequest`. |
| MedicationRequest.requester | MedicationRequest.requester | Equivalent | R4B `MedicationRequest.requester` maps as Equivalent to R5 `MedicationRequest.requester` |
| MedicationRequest.status | MedicationRequest.status | Equivalent | R4B `MedicationRequest.status` maps as Equivalent to R5 `MedicationRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/medicationrequest-status|4.3.0 and http://hl7.org/fhir/ValueSet/medicationrequest-status|5.0.0 (codes match, though systems are different) |
| MedicationRequest.statusReason | MedicationRequest.statusReason | Equivalent | R4B `MedicationRequest.statusReason` maps as Equivalent to R5 `MedicationRequest.statusReason` |
| MedicationRequest.subject | MedicationRequest.subject | Equivalent | R4B `MedicationRequest.subject` maps as Equivalent to R5 `MedicationRequest.subject` |
| MedicationRequest.substitution | MedicationRequest.substitution | Equivalent | R4B `MedicationRequest.substitution` maps as Equivalent to R5 `MedicationRequest.substitution` |
| MedicationRequest.substitution.allowed[x] | MedicationRequest.substitution.allowed[x] | RelatedTo | R4B `MedicationRequest.substitution.allowed[x]` maps as RelatedTo to R5 `MedicationRequest.substitution.allowed[x]` - allowed[x] changed the binding strength from Example to Preferred |
| MedicationRequest.substitution.extension | MedicationRequest.substitution.extension | RelatedTo | R4B `MedicationRequest.substitution.extension` maps as RelatedTo to R5 `MedicationRequest.substitution.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicationRequest.substitution.id | MedicationRequest.substitution.id | Equivalent | R4B `MedicationRequest.substitution.id` maps as Equivalent to R5 `MedicationRequest.substitution.id` |
| MedicationRequest.substitution.modifierExtension | MedicationRequest.substitution.modifierExtension | RelatedTo | R4B `MedicationRequest.substitution.modifierExtension` maps as RelatedTo to R5 `MedicationRequest.substitution.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicationRequest.substitution.reason | MedicationRequest.substitution.reason | Equivalent | R4B `MedicationRequest.substitution.reason` maps as Equivalent to R5 `MedicationRequest.substitution.reason` |
| MedicationRequest.supportingInformation | MedicationRequest.supportingInformation | Equivalent | R4B `MedicationRequest.supportingInformation` maps as Equivalent to R5 `MedicationRequest.supportingInformation` |
| MedicationRequest.text | MedicationRequest.text | Equivalent | R4B `MedicationRequest.text` maps as Equivalent to R5 `MedicationRequest.text` |

