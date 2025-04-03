Comparison of 
Generated at Thursday, April 3, 2025 8:18:05 AM

### Audit Active Participant Role ID Code

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Audit Active Participant Role ID Code |
| Canonical URL | `http://hl7.org/fhir/ValueSet/dicm-402-roleid` |
| Version | 20100826 |
| Description | Audit Active Participant Role ID Code |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `129` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.participant.role` | `http://hl7.org/fhir/ValueSet/dicm-402-roleid` | `Extensible` | User roles (e.g. local RBAC codes) |

### Referenced Systems

* `http://nema.org/dicom/dicm`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Audit Active Participant Role ID Code](/docs/R2/ValueSets/AuditActiveParticipantRoleIDCode.md)<br/> `http://hl7.org/fhir/ValueSet/dicm-402-roleid\|20100826` | →→→→→→→<br/>``<br/>- DBKey: `142`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `295`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SecurityRoleType](/docs/R3/ValueSets/SecurityRoleType.md)<br/> `http://hl7.org/fhir/ValueSet/security-role-type\|1.8.0` | →→→→→→→<br/>``<br/>- DBKey: `475`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `699`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SecurityRoleType](/docs/R4/ValueSets/SecurityRoleType.md)<br/> `http://hl7.org/fhir/ValueSet/security-role-type\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set Audit Active Participant Role ID Code from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 Audit Active Participant Role ID Code| Relationship | [R3 SecurityRoleType](/docs/R3/ValueSets/SecurityRoleType.md)| Relationship | [R4 SecurityRoleType](/docs/R4/ValueSets/SecurityRoleType.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://nema.org/dicom/dicm`
| **`110150`**| _Equivalent_ <br/>(1257/2554)| `110150`| _Equivalent_ <br/>(4251/6593)| `110150`| | | | | 
| **`110151`**| _Equivalent_ <br/>(1258/2555)| `110151`| _Equivalent_ <br/>(4252/6594)| `110151`| | | | | 
| **`110152`**| _Equivalent_ <br/>(1256/2552)| `110152`| _Equivalent_ <br/>(4253/6595)| `110152`| | | | | 
| **`110153`**| _Equivalent_ <br/>(1254/2553)| `110153`| _Equivalent_ <br/>(4254/6596)| `110153`| | | | | 
| **`110154`**| _Equivalent_ <br/>(1259/2551)| `110154`| _Equivalent_ <br/>(4255/6597)| `110154`| | | | | 
| **`110155`**| _Equivalent_ <br/>(1255/2556)| `110155`| _Equivalent_ <br/>(4256/6598)| `110155`| | | | | 
| *6 of 6 codes used* | | *6 of 76 codes used* <br/>remaining codes:<br/>`authserver`, `datacollector`, `dataprocessor`, `datasubject`, `AUCG`, `AULR`, `AUTM`, `AUWA`, `PROMSK`, `AUT`, `CST`, `INF`, `IRCP`, `LA`, `TRC`, `WIT`, `AFFL`, `AGNT`, `ASSIGNED`, `CLAIM`, `COVPTY`, `DEPEN`, `ECON`, `EMP`, `GUARD`, `INVSBJ`, `NAMED`, `NOK`, `NOT`, `PAT`, `PROV`, `CAS`, `CASM`, `CLASSIFIER`, `CN`, `CNRP`, `CNRPM`, `CONSENTER`, `CONSWIT`, `COPART`, `CPCA`, `CRP`, `CRPM`, `DECLASSIFIER`, `DELEGATEE`, `DELEGATOR`, `DOWNGRDER`, `DPOWATT`, `EXCEST`, `GRANTEE`, `GRANTOR`, `GT`, `GUADLTM`, `HPOWATT`, `INTPRTER`, `POWATT`, `RESPRSN`, `SPOWATT`, `_CitizenRoleType`, `AMENDER`, `COAUTH`, `CONT`, `EVTWIT`, `PRIMAUTH`, `REVIEWER`, `SOURCE`, `TRANS`, `VALID`, `VERF`| | *6 of 76 codes used* <br/>remaining codes:<br/>`AMENDER`, `COAUTH`, `CONT`, `EVTWIT`, `PRIMAUTH`, `REVIEWER`, `SOURCE`, `TRANS`, `VALID`, `VERF`, `authserver`, `datacollector`, `dataprocessor`, `datasubject`, `humanuser`, `AUCG`, `AULR`, `AUTM`, `AUWA`, `PROMSK`, `AUT`, `CST`, `INF`, `IRCP`, `LA`, `TRC`, `WIT`, `AFFL`, `AGNT`, `ASSIGNED`, `CLAIM`, `COVPTY`, `DEPEN`, `ECON`, `EMP`, `GUARD`, `INVSBJ`, `NAMED`, `NOK`, `NOT`, `PAT`, `PROV`, `CAS`, `CASM`, `CLASSIFIER`, `CN`, `CNRP`, `CNRPM`, `CONSENTER`, `CONSWIT`, `COPART`, `CPCA`, `CRP`, `CRPM`, `DECLASSIFIER`, `DELEGATEE`, `DELEGATOR`, `DOWNGRDER`, `DPOWATT`, `EXCEST`, `GRANTEE`, `GRANTOR`, `GT`, `GUADLTM`, `HPOWATT`, `INTPRTER`, `POWATT`, `RESPRSN`, `SPOWATT`, `_CitizenRoleType`| | | | 

