Comparison of 
Generated at Tuesday, April 1, 2025 1:39:33 PM

### AuditEventID

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | AuditEventID |
| Canonical URL | `http://hl7.org/fhir/ValueSet/audit-event-type` |
| Version | 5.0.0 |
| Description | Event Categories for Audit Events - defined by DICOM with some FHIR specific additions. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4313` |
| Database Concept Count | `20` |
| Database Active Concept Count | `20` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.category` | `http://hl7.org/fhir/ValueSet/audit-event-type` | `Example` | Type/identifier of event |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.entity.detail.type` | `http://hl7.org/fhir/ValueSet/audit-event-type` | `Example` | Name of the property |

### Referenced Systems

* `http://dicom.nema.org/resources/ontology/DCM`
* `http://terminology.hl7.org/CodeSystem/audit-event-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://dicom.nema.org/resources/ontology/DCM` | `110100` | Application Activity |
| `http://dicom.nema.org/resources/ontology/DCM` | `110101` | Audit Log Used |
| `http://dicom.nema.org/resources/ontology/DCM` | `110102` | Begin Transferring DICOM Instances |
| `http://dicom.nema.org/resources/ontology/DCM` | `110103` | DICOM Instances Accessed |
| `http://dicom.nema.org/resources/ontology/DCM` | `110104` | DICOM Instances Transferred |
| `http://dicom.nema.org/resources/ontology/DCM` | `110105` | DICOM Study Deleted |
| `http://dicom.nema.org/resources/ontology/DCM` | `110106` | Export |
| `http://dicom.nema.org/resources/ontology/DCM` | `110107` | Import |
| `http://dicom.nema.org/resources/ontology/DCM` | `110108` | Network Entry |
| `http://dicom.nema.org/resources/ontology/DCM` | `110109` | Order Record |
| `http://dicom.nema.org/resources/ontology/DCM` | `110110` | Patient Record |
| `http://dicom.nema.org/resources/ontology/DCM` | `110111` | Procedure Record |
| `http://dicom.nema.org/resources/ontology/DCM` | `110112` | Query |
| `http://dicom.nema.org/resources/ontology/DCM` | `110113` | Security Alert |
| `http://dicom.nema.org/resources/ontology/DCM` | `110114` | User Authentication |
| `http://terminology.hl7.org/CodeSystem/audit-event-type` | `document` | A Document Operation |
| `http://terminology.hl7.org/CodeSystem/audit-event-type` | `hl7-v2` | HL7 v2 Operation |
| `http://terminology.hl7.org/CodeSystem/audit-event-type` | `hl7-v3` | HL7 v3 Operation |
| `http://terminology.hl7.org/CodeSystem/audit-event-type` | `object` | An Operation on other Objects |
| `http://terminology.hl7.org/CodeSystem/audit-event-type` | `rest` | RESTful Operation |
