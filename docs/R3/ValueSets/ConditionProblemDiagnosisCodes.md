Comparison of 
Generated at Thursday, April 3, 2025 8:18:09 AM

### Condition/Problem/Diagnosis Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Condition/Problem/Diagnosis Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/condition-code` |
| Version | 3.0.2 |
| Description | Example value set for Condition/Problem/Diagnosis codes |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `1130` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClinicalImpression` | `ClinicalImpression.finding.item[x]` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | What was found |
| `http://hl7.org/fhir/StructureDefinition/Condition` | `Condition.code` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Identification of the condition, problem or diagnosis |
| `http://hl7.org/fhir/StructureDefinition/DeviceRequest` | `DeviceRequest.reasonCode` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Coded Reason for request |
| `http://hl7.org/fhir/StructureDefinition/FamilyMemberHistory` | `FamilyMemberHistory.condition.code` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Condition suffered by relation |
| `http://hl7.org/fhir/StructureDefinition/MedicationRequest` | `MedicationRequest.reasonCode` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Reason or indication for writing the prescription |
| `http://hl7.org/fhir/StructureDefinition/MedicationStatement` | `MedicationStatement.reasonCode` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Reason for why the medication is being/was taken |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.goal.addresses` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | What does the goal address |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.complication` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Complication following the procedure |

### Expansion Failure

Failed to expand this value set: Expansion is limited
