Comparison of 
Generated at Tuesday, April 1, 2025 1:39:18 PM

### DetectedIssueMitigationAction

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | DetectedIssueMitigationAction |
| Canonical URL | `http://hl7.org/fhir/ValueSet/detectedissue-mitigation-action` |
| Version | 4.0.1 |
| Description | Kinds of mitigating actions and observations that can be associated with a detected issue or contraindication, such as 'added concurrent therapy', 'prior therapy documented', etc. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2371` |
| Database Concept Count | `24` |
| Database Active Concept Count | `24` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DetectedIssue` | `DetectedIssue.mitigation.action` | `http://hl7.org/fhir/ValueSet/detectedissue-mitigation-action` | `Preferred` | What mitigation? |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActCode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `1` | Therapy Appropriate |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `10` | Provided Patient Education |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `11` | Added Concurrent Therapy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `12` | Temporarily Suspended Concurrent Therapy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `13` | Stopped Concurrent Therapy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `14` | Supply Appropriate |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `15` | Replacement |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `16` | Vacation Supply |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `17` | Weekend Supply |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `18` | Leave of Absence |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `19` | Consulted Supplier |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `2` | Assessed Patient |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `20` | additional quantity on separate dispense |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `21` | authorization confirmed |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `22` | appropriate indication or diagnosis |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `23` | prior therapy documented |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `3` | Patient Explanation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `4` | Consulted Other Source |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `5` | Consulted Prescriber |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `6` | Prescriber Declined Change |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `7` | Interacting Therapy No Longer Active/Planned |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `8` | Other Action Taken |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `9` | Instituted Ongoing Monitoring Program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EMAUTH` | emergency authorization override |
