Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### Condition/Problem/DiagnosisCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | Condition/Problem/DiagnosisCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/condition-code` |
| Version | 4.3.0 |
| Description | Example value set for Condition/Problem/Diagnosis codes. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `3626` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClinicalImpression` | `ClinicalImpression.finding.itemCodeableConcept` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | What was found |
| `http://hl7.org/fhir/StructureDefinition/Condition` | `Condition.code` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Identification of the condition, problem or diagnosis |
| `http://hl7.org/fhir/StructureDefinition/DeviceRequest` | `DeviceRequest.reasonCode` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Coded Reason for request |
| `http://hl7.org/fhir/StructureDefinition/FamilyMemberHistory` | `FamilyMemberHistory.condition.code` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Condition suffered by relation |
| `http://hl7.org/fhir/StructureDefinition/MedicationRequest` | `MedicationRequest.reasonCode` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Reason or indication for ordering or not ordering the medication |
| `http://hl7.org/fhir/StructureDefinition/MedicationStatement` | `MedicationStatement.reasonCode` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Reason for why the medication is being/was taken |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.goal.addresses` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | What does the goal address |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.complication` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Complication following the procedure |
| `http://hl7.org/fhir/StructureDefinition/ResearchStudy` | `ResearchStudy.condition` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Condition being studied |

### Expansion Failure

Failed to expand this value set: Expansion is limited
