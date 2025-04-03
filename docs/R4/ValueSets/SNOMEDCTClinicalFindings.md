Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### SNOMEDCTClinicalFindings

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | SNOMEDCTClinicalFindings |
| Canonical URL | `http://hl7.org/fhir/ValueSet/clinical-findings` |
| Version | 4.0.1 |
| Description | This value set includes all the "Clinical finding" [SNOMED CT](http://snomed.info/sct) codes - concepts where concept is-a 404684003 (Clinical finding (finding)). |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `2269` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AllergyIntolerance` | `AllergyIntolerance.reaction.manifestation` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Clinical symptoms/signs associated with the Event |
| `http://hl7.org/fhir/StructureDefinition/CarePlan` | `CarePlan.activity.detail.reasonCode` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Why activity should be done or why activity was prohibited |
| `http://hl7.org/fhir/StructureDefinition/CareTeam` | `CareTeam.reasonCode` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Why the care team exists |
| `http://hl7.org/fhir/StructureDefinition/Communication` | `Communication.reasonCode` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Indication for message |
| `http://hl7.org/fhir/StructureDefinition/DiagnosticReport` | `DiagnosticReport.conclusionCode` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Codes for the clinical conclusion of test results |
| `http://hl7.org/fhir/StructureDefinition/FamilyMemberHistory` | `FamilyMemberHistory.reasonCode` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Why was family member history performed? |
| `http://hl7.org/fhir/StructureDefinition/Goal` | `Goal.description` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Code or text describing goal |
| `http://hl7.org/fhir/StructureDefinition/Goal` | `Goal.outcomeCode` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | What result was achieved regarding the goal? |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.goal.description` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Code or text describing the goal |

### Expansion Failure

Failed to expand this value set: Expansion is limited
