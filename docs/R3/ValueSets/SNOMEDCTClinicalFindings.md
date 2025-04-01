Comparison of 
Generated at Tuesday, April 1, 2025 1:39:11 PM

### SNOMED CT Clinical Findings

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | SNOMED CT Clinical Findings |
| Canonical URL | `http://hl7.org/fhir/ValueSet/clinical-findings` |
| Version | 3.0.2 |
| Description | This value set includes all the "Clinical finding" [SNOMED CT](http://snomed.info/sct) codes - concepts where concept is-a 404684003 (Clinical finding (finding)). |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `1112` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AllergyIntolerance` | `AllergyIntolerance.reaction.manifestation` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Clinical symptoms/signs associated with the Event |
| `http://hl7.org/fhir/StructureDefinition/CareTeam` | `CareTeam.reasonCode` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Why the care team exists |
| `http://hl7.org/fhir/StructureDefinition/Communication` | `Communication.reasonCode` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Indication for message |
| `http://hl7.org/fhir/StructureDefinition/DiagnosticReport` | `DiagnosticReport.codedDiagnosis` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Codes for the conclusion |
| `http://hl7.org/fhir/StructureDefinition/FamilyMemberHistory` | `FamilyMemberHistory.reasonCode` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Why was family member history performed? |
| `http://hl7.org/fhir/StructureDefinition/Goal` | `Goal.description` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Code or text describing goal |
| `http://hl7.org/fhir/StructureDefinition/Goal` | `Goal.outcomeCode` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | What result was achieved regarding the goal? |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.goal.description` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Code or text describing the goal |
| `http://hl7.org/fhir/StructureDefinition/ReferralRequest` | `ReferralRequest.reasonCode` | `http://hl7.org/fhir/ValueSet/clinical-findings` | `Example` | Reason for referral / transfer of care request |

### Expansion Failure

Failed to expand this value set: Expansion is limited
