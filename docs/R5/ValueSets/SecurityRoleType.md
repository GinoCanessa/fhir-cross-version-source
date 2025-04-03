Comparison of 
Generated at Thursday, April 3, 2025 8:18:32 AM

### SecurityRoleType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SecurityRoleType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/security-role-type` |
| Version | 5.0.0 |
| Description | This value set contains example structural roles. In general, two types of roles can be distinguished: structural roles and functional roles. Structural Roles reflect human or organizational categories (hierarchies), and describe prerequisites, feasibilities, or competences for actions. Functional roles are bound to the realization or performance of actions. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4890` |
| Database Concept Count | `13` |
| Database Active Concept Count | `13` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.agent.role` | `http://hl7.org/fhir/ValueSet/security-role-type` | `Example` | Agent role in the event |
| `http://hl7.org/fhir/StructureDefinition/Contract` | `Contract.term.action.performerRole` | `http://hl7.org/fhir/ValueSet/security-role-type` | `Example` | Competency of the performer |
| `http://hl7.org/fhir/StructureDefinition/Provenance` | `Provenance.agent.role` | `http://hl7.org/fhir/ValueSet/security-role-type` | `Example` | What the agents role was |

### Referenced Systems

* `sample-security-structural-roles`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `sample-security-structural-roles` | `business-manager` | Business Manager |
| `sample-security-structural-roles` | `claims-adjudicator` | Claims Adjudicator |
| `sample-security-structural-roles` | `dentist` | Dentist |
| `sample-security-structural-roles` | `dietician` | Dietician |
| `sample-security-structural-roles` | `general-medicine` | General Medicine |
| `sample-security-structural-roles` | `general-nursing` | General Nursing |
| `sample-security-structural-roles` | `non-regulated-health-professionals` | Non-Regulated health Professionals |
| `sample-security-structural-roles` | `pediatrics` | Pediatrics |
| `sample-security-structural-roles` | `pharmacy` | Pharmacy |
| `sample-security-structural-roles` | `receptionist` | Receptionist |
| `sample-security-structural-roles` | `regulated-health-professionals` | Regulated Health Professionals |
| `sample-security-structural-roles` | `transcriptionist` | Transcriptionist |
| `sample-security-structural-roles` | `veterinarian` | Veterinarian |
