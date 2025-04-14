Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### Detected Issue Mitigation Action

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Detected Issue Mitigation Action |
| Canonical URL | `http://hl7.org/fhir/ValueSet/detectedissue-mitigation-action` |
| Version | 1.0.2 |
| Description | Kinds of mitigating actions and observations that can be associated with a detected issue or contraindication, such as 'added concurrent therapy', 'prior therapy documented', etc. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `117` |
| Database Concept Count | `27` |
| Database Active Concept Count | `24` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DetectedIssue` | `DetectedIssue.mitigation.action` | `http://hl7.org/fhir/ValueSet/detectedissue-mitigation-action` | `Preferred` | What mitigation? |

### Referenced Systems

* `http://hl7.org/fhir/v3/ActCode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/v3/ActCode` | `1` | Therapy Appropriate |
| `http://hl7.org/fhir/v3/ActCode` | `10` | Provided Patient Education |
| `http://hl7.org/fhir/v3/ActCode` | `11` | Added Concurrent Therapy |
| `http://hl7.org/fhir/v3/ActCode` | `12` | Temporarily Suspended Concurrent Therapy |
| `http://hl7.org/fhir/v3/ActCode` | `13` | Stopped Concurrent Therapy |
| `http://hl7.org/fhir/v3/ActCode` | `14` | Supply Appropriate |
| `http://hl7.org/fhir/v3/ActCode` | `15` | Replacement |
| `http://hl7.org/fhir/v3/ActCode` | `16` | Vacation Supply |
| `http://hl7.org/fhir/v3/ActCode` | `17` | Weekend Supply |
| `http://hl7.org/fhir/v3/ActCode` | `18` | Leave of Absence |
| `http://hl7.org/fhir/v3/ActCode` | `19` | Consulted Supplier |
| `http://hl7.org/fhir/v3/ActCode` | `2` | Assessed Patient |
| `http://hl7.org/fhir/v3/ActCode` | `20` | additional quantity on separate dispense |
| `http://hl7.org/fhir/v3/ActCode` | `21` | authorization confirmed |
| `http://hl7.org/fhir/v3/ActCode` | `22` | appropriate indication or diagnosis |
| `http://hl7.org/fhir/v3/ActCode` | `23` | prior therapy documented |
| `http://hl7.org/fhir/v3/ActCode` | `3` | Patient Explanation |
| `http://hl7.org/fhir/v3/ActCode` | `4` | Consulted Other Source |
| `http://hl7.org/fhir/v3/ActCode` | `5` | Consulted Prescriber |
| `http://hl7.org/fhir/v3/ActCode` | `6` | Prescriber Declined Change |
| `http://hl7.org/fhir/v3/ActCode` | `7` | Interacting Therapy No Longer Active/Planned |
| `http://hl7.org/fhir/v3/ActCode` | `8` | Other Action Taken |
| `http://hl7.org/fhir/v3/ActCode` | `9` | Instituted Ongoing Monitoring Program |
| `http://hl7.org/fhir/v3/ActCode` | `EMAUTH` | emergency authorization override |
