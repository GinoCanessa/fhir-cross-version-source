Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### Condition/Problem/Diagnosis Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Condition/Problem/Diagnosis Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/condition-code` |
| Version | 1.0.2 |
| Description | Example value set for Condition/Problem/Diagnosis codes |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `64` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClinicalImpression` | `ClinicalImpression.finding.item` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Specific text or code for finding |
| `http://hl7.org/fhir/StructureDefinition/ClinicalImpression` | `ClinicalImpression.resolved` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Diagnoses/conditions resolved since previous assessment |
| `http://hl7.org/fhir/StructureDefinition/ClinicalImpression` | `ClinicalImpression.ruledOut.item` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Specific text of code for diagnosis |
| `http://hl7.org/fhir/StructureDefinition/Condition` | `Condition.code` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Identification of the condition, problem or diagnosis |
| `http://hl7.org/fhir/StructureDefinition/DiagnosticOrder` | `DiagnosticOrder.reason` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Explanation/Justification for test |
| `http://hl7.org/fhir/StructureDefinition/FamilyMemberHistory` | `FamilyMemberHistory.condition.code` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Condition suffered by relation |
| `http://hl7.org/fhir/StructureDefinition/MedicationOrder` | `MedicationOrder.reason[x]` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Reason or indication for writing the prescription |
| `http://hl7.org/fhir/StructureDefinition/MedicationStatement` | `MedicationStatement.reasonForUse[x]` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` |  |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.complication` | `http://hl7.org/fhir/ValueSet/condition-code` | `Example` | Complication following the procedure |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/condition-code|1.0.2: Operation expand failed: creating the required expansion failed with message "Cannot find codesystem 'http://snomed.info/sct', so the defined filter(s) cannot be applied.".
