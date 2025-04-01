Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### ConditionProblemDiagnosisCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ConditionProblemDiagnosisCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/condition-code` |
| Version | 5.0.0 |
| Description | Example value set for Condition/Problem/Diagnosis codes. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4397` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Account` | `Account.diagnosis.condition` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | The diagnosis relevant to the account |
| `http://hl7.org/fhir/StructureDefinition/ClinicalImpression` | `ClinicalImpression.finding.item` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | What was found |
| `http://hl7.org/fhir/StructureDefinition/Condition` | `Condition.code` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Identification of the condition, problem or diagnosis |
| `http://hl7.org/fhir/StructureDefinition/ConditionDefinition` | `ConditionDefinition.code` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Identification of the condition, problem or diagnosis |
| `http://hl7.org/fhir/StructureDefinition/DeviceRequest` | `DeviceRequest.reason` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Coded/Linked Reason for request |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.diagnosis.condition` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | The diagnosis relevant to the encounter |
| `http://hl7.org/fhir/StructureDefinition/EpisodeOfCare` | `EpisodeOfCare.diagnosis.condition` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | The medical condition that was addressed during the episode of care |
| `http://hl7.org/fhir/StructureDefinition/FamilyMemberHistory` | `FamilyMemberHistory.condition.code` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Condition suffered by relation |
| `http://hl7.org/fhir/StructureDefinition/MedicationRequest` | `MedicationRequest.reason` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Reason or indication for ordering or not ordering the medication |
| `http://hl7.org/fhir/StructureDefinition/MedicationStatement` | `MedicationStatement.reason` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Reason for why the medication is being/was taken |
| `http://hl7.org/fhir/StructureDefinition/NutritionIntake` | `NutritionIntake.reason` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Reason for why the food or fluid is /was consumed |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.goal.addresses` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | What does the goal address |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.complication` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Complication following the procedure |
| `http://hl7.org/fhir/StructureDefinition/ResearchStudy` | `ResearchStudy.condition` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Condition being studied |

### Expansion Failure

Failed to expand this value set: Expansion is limited
