Comparison of 
Generated at Friday, April 4, 2025 2:58:37 PM

### Audit Event ID

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Audit Event ID |
| Canonical URL | `http://hl7.org/fhir/ValueSet/audit-event-type` |
| Version | 20150326 |
| Description | Event Types for Audit Events - defined by DICOM with some FHIR specific additions. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `1072` |
| Database Concept Count | `16` |
| Database Active Concept Count | `16` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.type` | `http://hl7.org/fhir/ValueSet/audit-event-type` | `Extensible` | Type/identifier of event |

### Referenced Systems

* `http://dicom.nema.org/resources/ontology/DCM`
* `http://hl7.org/fhir/audit-event-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Audit Event ID](/docs/R2/ValueSets/AuditEventID.md)<br/> `http://hl7.org/fhir/ValueSet/audit-event-type\|20150326` | →→→→→→→<br/>``<br/>- DBKey: `137`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `301`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Audit Event ID](/docs/R3/ValueSets/AuditEventID.md)<br/> `http://hl7.org/fhir/ValueSet/audit-event-type\|20150326` | →→→→→→→<br/>``<br/>- DBKey: `504`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `725`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AuditEventID](/docs/R4/ValueSets/AuditEventID.md)<br/> `http://hl7.org/fhir/ValueSet/audit-event-type\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set Audit Event ID from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 Audit Event ID](/docs/R2/ValueSets/AuditEventID.md)| Relationship | R3 Audit Event ID| Relationship | [R4 AuditEventID](/docs/R4/ValueSets/AuditEventID.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://dicom.nema.org/resources/ontology/DCM`
| `110100`| _Equivalent_ <br/>(1165/2707)| **`110100`**| _Equivalent_ <br/>(4761/7082)| `110100`| | | | | 
| `110101`| _Equivalent_ <br/>(1163/2705)| **`110101`**| _Equivalent_ <br/>(4762/7083)| `110101`| | | | | 
| `110102`| _Equivalent_ <br/>(1172/2700)| **`110102`**| _Equivalent_ <br/>(4763/7084)| `110102`| | | | | 
| `110103`| _Equivalent_ <br/>(1160/2701)| **`110103`**| _Equivalent_ <br/>(4764/7085)| `110103`| | | | | 
| `110104`| _Equivalent_ <br/>(1173/2706)| **`110104`**| _Equivalent_ <br/>(4765/7086)| `110104`| | | | | 
| `110105`| _Equivalent_ <br/>(1171/2699)| **`110105`**| _Equivalent_ <br/>(4766/7087)| `110105`| | | | | 
| `110106`| _Equivalent_ <br/>(1164/2703)| **`110106`**| _Equivalent_ <br/>(4767/7088)| `110106`| | | | | 
| `110107`| _Equivalent_ <br/>(1167/2712)| **`110107`**| _Equivalent_ <br/>(4768/7089)| `110107`| | | | | 
| `110108`| _Equivalent_ <br/>(1168/2702)| **`110108`**| _Equivalent_ <br/>(4769/7090)| `110108`| | | | | 
| `110109`| _Equivalent_ <br/>(1162/2708)| **`110109`**| _Equivalent_ <br/>(4770/7091)| `110109`| | | | | 
| `110110`| _Equivalent_ <br/>(1174/2711)| **`110110`**| _Equivalent_ <br/>(4771/7092)| `110110`| | | | | 
| `110111`| _Equivalent_ <br/>(1161/2709)| **`110111`**| _Equivalent_ <br/>(4772/7093)| `110111`| | | | | 
| `110112`| _Equivalent_ <br/>(1170/2713)| **`110112`**| _Equivalent_ <br/>(4773/7094)| `110112`| | | | | 
| `110113`| _Equivalent_ <br/>(1166/2704)| **`110113`**| _Equivalent_ <br/>(4774/7095)| `110113`| | | | | 
| `110114`| _Equivalent_ <br/>(1169/2710)| **`110114`**| _Equivalent_ <br/>(4775/7096)| `110114`| | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/audit-event-type`
| `rest`| _Equivalent_ <br/>(1175/2698)| **`rest`**| →→→→ _Equivalent_ →→→→ <br/>(4760)<hr/>←←←← __ ←←←← <br/>() | `rest`| | | | | 
| `rest`| _Equivalent_ <br/>(1175/2698)| **`rest`**| _Equivalent_ <br/>(4776/7097)| `rest`| | | | | 
| *16 of 16 codes used* | | *16 of 16 codes used* | | *16 of 43 codes used* <br/>remaining codes:<br/>`access`, `amend`, `archive`, `attest`, `decrypt`, `deidentify`, `deprecate`, `destroy`, `disclose`, `encrypt`, `extract`, `hold`, `link`, `merge`, `originate`, `pseudonymize`, `reactivate`, `receive`, `reidentify`, `report`, `restore`, `transform`, `transmit`, `unhold`, `unlink`, `unmerge`, `verify`| | | | 

