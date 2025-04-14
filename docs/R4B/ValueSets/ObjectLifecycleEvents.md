Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### ObjectLifecycleEvents

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ObjectLifecycleEvents |
| Canonical URL | `http://hl7.org/fhir/ValueSet/object-lifecycle-events` |
| Version | 4.3.0 |
| Description | This example FHIR value set is comprised of lifecycle event codes. The FHIR Actor value set is based on    DICOM Audit Message, ParticipantObjectDataLifeCycle;   ISO Standard, TS 21089-2017; |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3958` |
| Database Concept Count | `42` |
| Database Active Concept Count | `42` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.entity.lifecycle` | `http://hl7.org/fhir/ValueSet/object-lifecycle-events` | `Extensible` | Life-cycle stage for the entity |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle`
* `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle` | `1` | Origination / Creation |
| `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle` | `10` | Export |
| `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle` | `11` | Disclosure |
| `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle` | `12` | Receipt of disclosure |
| `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle` | `13` | Archiving |
| `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle` | `14` | Logical deletion |
| `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle` | `15` | Permanent erasure / Physical destruction |
| `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle` | `2` | Import / Copy |
| `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle` | `3` | Amendment |
| `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle` | `4` | Verification |
| `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle` | `5` | Translation |
| `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle` | `6` | Access / Use |
| `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle` | `7` | De-identification |
| `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle` | `8` | Aggregation / summarization / derivation |
| `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle` | `9` | Report |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `access` | Access/View Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `amend` | Amend (Update) Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `archive` | Archive Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `attest` | Attest Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `decrypt` | Decrypt Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `deidentify` | De-Identify (Anononymize) Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `deprecate` | Deprecate Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `destroy` | Destroy/Delete Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `disclose` | Disclose Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `encrypt` | Encrypt Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `extract` | Extract Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `hold` | Add Legal Hold Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `link` | Link Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `merge` | Merge Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `originate` | Originate/Retain Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `pseudonymize` | Pseudonymize Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `reactivate` | Re-activate Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `receive` | Receive/Retain Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `reidentify` | Re-identify Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `report` | Report (Output) Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `restore` | Restore Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `transform` | Transform/Translate Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `transmit` | Transmit Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `unhold` | Remove Legal Hold Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `unlink` | Unlink Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `unmerge` | Unmerge Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `verify` | Verify Record Lifecycle Event |
