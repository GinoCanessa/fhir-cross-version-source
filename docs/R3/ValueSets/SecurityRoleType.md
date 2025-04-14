Comparison of 
Generated at Monday, April 14, 2025 6:17:21 PM

### SecurityRoleType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | SecurityRoleType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/security-role-type` |
| Version | 1.8.0 |
| Description | This example FHIR value set is comprised of example Actor Type codes, which can be used to value FHIR agents, actors, and other role         elements such as those specified in financial transactions. The FHIR Actor value set is based on    DICOM Audit Message, C402;   ASTM Standard, E1762-95 [2013]; selected codes and          derived actor roles from HL7 RoleClass OID 2.16.840.1.113883.5.110;    HL7 Role Code 2.16.840.1.113883.5.111, including AgentRoleType;          HL7 ParticipationType OID: 2.16.840.1.113883.5.90; and    HL7 ParticipationFunction codes OID: 2.16.840.1.113883.5.88.           This value set includes, by reference, role codes from external code systems: NUCC Health Care Provider Taxonomy OID: 2.16.840.1.113883.6.101;          North American Industry Classification System [NAICS]OID: 2.16.840.1.113883.6.85; IndustryClassificationSystem 2.16.840.1.113883.1.11.16039;          and US Census Occupation Code OID: 2.16.840.1.113883.6.243 for relevant recipient or custodian codes not included in this value set.            If no source is indicated in the definition comments, then these are example FHIR codes.          It can be extended with appropriate roles described by SNOMED as well as those described in the HL7 Role Based Access Control Catalog and the          HL7 Healthcare (Security and Privacy) Access Control Catalog.            In Role-Based Access Control (RBAC), permissions are operations on an object that a user wishes to access. Permissions are grouped into roles.          A role characterizes the functions a user is allowed to perform. Roles are assigned to users. If the user's role has the appropriate permissions          to access an object, then that user is granted access to the object. FHIR readily enables RBAC, as FHIR Resources are object types and the CRUDE          events (the FHIR equivalent to permissions in the RBAC scheme) are operations on those objects.          In Attribute-Based Access Control (ABAC), a user requests to perform operations on objects. That user's access request is granted or denied          based on a set of access control policies that are specified in terms of attributes and conditions. FHIR readily enables ABAC, as instances of          a Resource in FHIR (again, Resources are object types) can have attributes associated with them. These attributes include security tags,          environment conditions, and a host of user and object characteristics, which are the same attributes as those used in ABAC. Attributes help          define the access control policies that determine the operations a user may perform on a Resource (in FHIR) or object (in ABAC). For example,          a tag (or attribute) may specify that the identified Resource (object) is not to be further disclosed without explicit consent from the patient. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1466` |
| Database Concept Count | `76` |
| Database Active Concept Count | `76` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.agent.role` | `http://hl7.org/fhir/ValueSet/security-role-type` | `Extensible` | Agent role in the event |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.actor.role` | `http://hl7.org/fhir/ValueSet/security-role-type` | `Extensible` | How the actor is involved |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.except.actor.role` | `http://hl7.org/fhir/ValueSet/security-role-type` | `Extensible` | How the actor is involved |
| `http://hl7.org/fhir/StructureDefinition/Provenance` | `Provenance.agent.role` | `http://hl7.org/fhir/ValueSet/security-role-type` | `Extensible` | What the agents role was |

### Referenced Systems

* `http://www.hl7.org/fhir/contractsignertypecodes`
* `http://hl7.org/fhir/v3/RoleClass`
* `http://hl7.org/fhir/v3/RoleCode`
* `http://hl7.org/fhir/v3/ParticipationFunction`
* `http://hl7.org/fhir/v3/ParticipationType`
* `http://hl7.org/fhir/extra-security-role-type`
* `http://dicom.nema.org/resources/ontology/DCM`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Audit Active Participant Role ID Code](/docs/R2/ValueSets/AuditActiveParticipantRoleIDCode.md)<br/> `http://hl7.org/fhir/ValueSet/dicm-402-roleid\|20100826` | →→→→→→→<br/>``<br/>- DBKey: `142`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `295`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SecurityRoleType](/docs/R3/ValueSets/SecurityRoleType.md)<br/> `http://hl7.org/fhir/ValueSet/security-role-type\|1.8.0` | →→→→→→→<br/>``<br/>- DBKey: `475`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `699`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SecurityRoleType](/docs/R4/ValueSets/SecurityRoleType.md)<br/> `http://hl7.org/fhir/ValueSet/security-role-type\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set SecurityRoleType from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 Audit Active Participant Role ID Code](/docs/R2/ValueSets/AuditActiveParticipantRoleIDCode.md)| Relationship | R3 SecurityRoleType| Relationship | [R4 SecurityRoleType](/docs/R4/ValueSets/SecurityRoleType.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://www.hl7.org/fhir/contractsignertypecodes`
| | | **`AMENDER`**| _Equivalent_ <br/>(4316/6663)| `AMENDER`| | | | | 
| | | **`COAUTH`**| _Equivalent_ <br/>(4318/6670)| `COAUTH`| | | | | 
| | | **`CONT`**| _Equivalent_ <br/>(4317/6666)| `CONT`| | | | | 
| | | **`EVTWIT`**| _Equivalent_ <br/>(4320/6668)| `EVTWIT`| | | | | 
| | | **`PRIMAUTH`**| _Equivalent_ <br/>(4324/6671)| `PRIMAUTH`| | | | | 
| | | **`REVIEWER`**| _Equivalent_ <br/>(4319/6667)| `REVIEWER`| | | | | 
| | | **`SOURCE`**| _Equivalent_ <br/>(4315/6664)| `SOURCE`| | | | | 
| | | **`TRANS`**| _Equivalent_ <br/>(4321/6665)| `TRANS`| | | | | 
| | | **`VALID`**| _Equivalent_ <br/>(4322/6669)| `VALID`| | | | | 
| | | **`VERF`**| _Equivalent_ <br/>(4323/6672)| `VERF`| | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/RoleClass`
| | | **`AFFL`**| →→→→ _Equivalent_ →→→→ <br/>(4200)<hr/>←←←← __ ←←←← <br/>() | `AFFL`| | | | | 
| | | **`AFFL`**| _Equivalent_ <br/>(4292/6611)| `AFFL`| | | | | 
| | | **`AGNT`**| →→→→ _Equivalent_ →→→→ <br/>(4199)<hr/>←←←← __ ←←←← <br/>() | `AGNT`| | | | | 
| | | **`AGNT`**| _Equivalent_ <br/>(4293/6610)| `AGNT`| | | | | 
| | | **`ASSIGNED`**| →→→→ _Equivalent_ →→→→ <br/>(4196)<hr/>←←←← __ ←←←← <br/>() | `ASSIGNED`| | | | | 
| | | **`ASSIGNED`**| _Equivalent_ <br/>(4298/6607)| `ASSIGNED`| | | | | 
| | | **`CLAIM`**| →→→→ _Equivalent_ →→→→ <br/>(4206)<hr/>←←←← __ ←←←← <br/>() | `CLAIM`| | | | | 
| | | **`CLAIM`**| _Equivalent_ <br/>(4291/6617)| `CLAIM`| | | | | 
| | | **`COVPTY`**| →→→→ _Equivalent_ →→→→ <br/>(4203)<hr/>←←←← __ ←←←← <br/>() | `COVPTY`| | | | | 
| | | **`COVPTY`**| _Equivalent_ <br/>(4294/6614)| `COVPTY`| | | | | 
| | | **`DEPEN`**| →→→→ _Equivalent_ →→→→ <br/>(4193)<hr/>←←←← __ ←←←← <br/>() | `DEPEN`| | | | | 
| | | **`DEPEN`**| _Equivalent_ <br/>(4296/6604)| `DEPEN`| | | | | 
| | | **`ECON`**| →→→→ _Equivalent_ →→→→ <br/>(4194)<hr/>←←←← __ ←←←← <br/>() | `ECON`| | | | | 
| | | **`ECON`**| _Equivalent_ <br/>(4284/6605)| `ECON`| | | | | 
| | | **`EMP`**| →→→→ _Equivalent_ →→→→ <br/>(4195)<hr/>←←←← __ ←←←← <br/>() | `EMP`| | | | | 
| | | **`EMP`**| _Equivalent_ <br/>(4295/6606)| `EMP`| | | | | 
| | | **`GUARD`**| →→→→ _Equivalent_ →→→→ <br/>(4205)<hr/>←←←← __ ←←←← <br/>() | `GUARD`| | | | | 
| | | **`GUARD`**| _Equivalent_ <br/>(4286/6616)| `GUARD`| | | | | 
| | | **`INVSBJ`**| →→→→ _Equivalent_ →→→→ <br/>(4201)<hr/>←←←← __ ←←←← <br/>() | `INVSBJ`| | | | | 
| | | **`INVSBJ`**| _Equivalent_ <br/>(4288/6612)| `INVSBJ`| | | | | 
| | | **`NAMED`**| →→→→ _Equivalent_ →→→→ <br/>(4198)<hr/>←←←← __ ←←←← <br/>() | `NAMED`| | | | | 
| | | **`NAMED`**| _Equivalent_ <br/>(4290/6609)| `NAMED`| | | | | 
| | | **`NOK`**| →→→→ _Equivalent_ →→→→ <br/>(4207)<hr/>←←←← __ ←←←← <br/>() | `NOK`| | | | | 
| | | **`NOK`**| _Equivalent_ <br/>(4289/6618)| `NOK`| | | | | 
| | | **`PAT`**| →→→→ _Equivalent_ →→→→ <br/>(4202)<hr/>←←←← __ ←←←← <br/>() | `PAT`| | | | | 
| | | **`PAT`**| _Equivalent_ <br/>(4297/6613)| `PAT`| | | | | 
| | | **`PROV`**| →→→→ _Equivalent_ →→→→ <br/>(4204)<hr/>←←←← __ ←←←← <br/>() | `PROV`| | | | | 
| | | **`PROV`**| _Equivalent_ <br/>(4287/6615)| `PROV`| | | | | 
| | | **`NOT`**| →→→→ _Equivalent_ →→→→ <br/>(4197)<hr/>←←←← __ ←←←← <br/>() | `NOT`| | | | | 
| | | **`NOT`**| _Equivalent_ <br/>(4285/6608)| `NOT`| | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/RoleCode`
| | | **`CLASSIFIER`**| →→→→ _Equivalent_ →→→→ <br/>(4240)<hr/>←←←← __ ←←←← <br/>() | `CLASSIFIER`| | | | | 
| | | **`CLASSIFIER`**| _Equivalent_ <br/>(4271/6652)| `CLASSIFIER`| | | | | 
| | | **`CONSENTER`**| →→→→ _Equivalent_ →→→→ <br/>(4227)<hr/>←←←← __ ←←←← <br/>() | `CONSENTER`| | | | | 
| | | **`CONSENTER`**| _Equivalent_ <br/>(4277/6639)| `CONSENTER`| | | | | 
| | | **`CONSWIT`**| →→→→ _Equivalent_ →→→→ <br/>(4219)<hr/>←←←← __ ←←←← <br/>() | `CONSWIT`| | | | | 
| | | **`CONSWIT`**| _Equivalent_ <br/>(4259/6631)| `CONSWIT`| | | | | 
| | | **`COPART`**| →→→→ _Equivalent_ →→→→ <br/>(4228)<hr/>←←←← __ ←←←← <br/>() | `COPART`| | | | | 
| | | **`COPART`**| _Equivalent_ <br/>(4270/6640)| `COPART`| | | | | 
| | | **`DECLASSIFIER`**| →→→→ _Equivalent_ →→→→ <br/>(4237)<hr/>←←←← __ ←←←← <br/>() | `DECLASSIFIER`| | | | | 
| | | **`DECLASSIFIER`**| _Equivalent_ <br/>(4274/6649)| `DECLASSIFIER`| | | | | 
| | | **`DELEGATEE`**| →→→→ _Equivalent_ →→→→ <br/>(4244)<hr/>←←←← __ ←←←← <br/>() | `DELEGATEE`| | | | | 
| | | **`DELEGATEE`**| _Equivalent_ <br/>(4261/6656)| `DELEGATEE`| | | | | 
| | | **`DELEGATOR`**| →→→→ _Equivalent_ →→→→ <br/>(4242)<hr/>←←←← __ ←←←← <br/>() | `DELEGATOR`| | | | | 
| | | **`DELEGATOR`**| _Equivalent_ <br/>(4264/6654)| `DELEGATOR`| | | | | 
| | | **`DOWNGRDER`**| →→→→ _Equivalent_ →→→→ <br/>(4226)<hr/>←←←← __ ←←←← <br/>() | `DOWNGRDER`| | | | | 
| | | **`DOWNGRDER`**| _Equivalent_ <br/>(4266/6638)| `DOWNGRDER`| | | | | 
| | | **`DPOWATT`**| →→→→ _Equivalent_ →→→→ <br/>(4243)<hr/>←←←← __ ←←←← <br/>() | `DPOWATT`| | | | | 
| | | **`DPOWATT`**| _Equivalent_ <br/>(4265/6655)| `DPOWATT`| | | | | 
| | | **`EXCEST`**| →→→→ _Equivalent_ →→→→ <br/>(4220)<hr/>←←←← __ ←←←← <br/>() | `EXCEST`| | | | | 
| | | **`EXCEST`**| _Equivalent_ <br/>(4275/6632)| `EXCEST`| | | | | 
| | | **`GRANTEE`**| →→→→ _Equivalent_ →→→→ <br/>(4235)<hr/>←←←← __ ←←←← <br/>() | `GRANTEE`| | | | | 
| | | **`GRANTEE`**| _Equivalent_ <br/>(4280/6647)| `GRANTEE`| | | | | 
| | | **`GRANTOR`**| →→→→ _Equivalent_ →→→→ <br/>(4230)<hr/>←←←← __ ←←←← <br/>() | `GRANTOR`| | | | | 
| | | **`GRANTOR`**| _Equivalent_ <br/>(4267/6642)| `GRANTOR`| | | | | 
| | | **`GT`**| →→→→ _Equivalent_ →→→→ <br/>(4236)<hr/>←←←← __ ←←←← <br/>() | `GT`| | | | | 
| | | **`GT`**| _Equivalent_ <br/>(4258/6648)| `GT`| | | | | 
| | | **`GUADLTM`**| →→→→ _Equivalent_ →→→→ <br/>(4241)<hr/>←←←← __ ←←←← <br/>() | `GUADLTM`| | | | | 
| | | **`GUADLTM`**| _Equivalent_ <br/>(4273/6653)| `GUADLTM`| | | | | 
| | | **`HPOWATT`**| →→→→ _Equivalent_ →→→→ <br/>(4232)<hr/>←←←← __ ←←←← <br/>() | `HPOWATT`| | | | | 
| | | **`HPOWATT`**| _Equivalent_ <br/>(4268/6644)| `HPOWATT`| | | | | 
| | | **`INTPRTER`**| →→→→ _Equivalent_ →→→→ <br/>(4231)<hr/>←←←← __ ←←←← <br/>() | `INTPRTER`| | | | | 
| | | **`INTPRTER`**| _Equivalent_ <br/>(4279/6643)| `INTPRTER`| | | | | 
| | | **`POWATT`**| →→→→ _Equivalent_ →→→→ <br/>(4221)<hr/>←←←← __ ←←←← <br/>() | `POWATT`| | | | | 
| | | **`POWATT`**| _Equivalent_ <br/>(4283/6633)| `POWATT`| | | | | 
| | | **`RESPRSN`**| →→→→ _Equivalent_ →→→→ <br/>(4238)<hr/>←←←← __ ←←←← <br/>() | `RESPRSN`| | | | | 
| | | **`RESPRSN`**| _Equivalent_ <br/>(4278/6650)| `RESPRSN`| | | | | 
| | | **`SPOWATT`**| →→→→ _Equivalent_ →→→→ <br/>(4239)<hr/>←←←← __ ←←←← <br/>() | `SPOWATT`| | | | | 
| | | **`SPOWATT`**| _Equivalent_ <br/>(4269/6651)| `SPOWATT`| | | | | 
| | | **`CASM`**| →→→→ _Equivalent_ →→→→ <br/>(4234)<hr/>←←←← __ ←←←← <br/>() | `CASM`| | | | | 
| | | **`CASM`**| _Equivalent_ <br/>(4257/6646)| `CASM`| | | | | 
| | | **`CAS`**| →→→→ _Equivalent_ →→→→ <br/>(4222)<hr/>←←←← __ ←←←← <br/>() | `CAS`| | | | | 
| | | **`CAS`**| _Equivalent_ <br/>(4272/6634)| `CAS`| | | | | 
| | | **`CN`**| →→→→ _Equivalent_ →→→→ <br/>(4223)<hr/>←←←← __ ←←←← <br/>() | `CN`| | | | | 
| | | **`CN`**| _Equivalent_ <br/>(4276/6635)| `CN`| | | | | 
| | | **`CNRPM`**| →→→→ _Equivalent_ →→→→ <br/>(4245)<hr/>←←←← __ ←←←← <br/>() | `CNRPM`| | | | | 
| | | **`CNRPM`**| _Equivalent_ <br/>(4282/6657)| `CNRPM`| | | | | 
| | | **`CNRP`**| →→→→ _Equivalent_ →→→→ <br/>(4233)<hr/>←←←← __ ←←←← <br/>() | `CNRP`| | | | | 
| | | **`CNRP`**| _Equivalent_ <br/>(4281/6645)| `CNRP`| | | | | 
| | | **`CPCA`**| →→→→ _Equivalent_ →→→→ <br/>(4224)<hr/>←←←← __ ←←←← <br/>() | `CPCA`| | | | | 
| | | **`CPCA`**| _Equivalent_ <br/>(4260/6636)| `CPCA`| | | | | 
| | | **`CRPM`**| →→→→ _Equivalent_ →→→→ <br/>(4225)<hr/>←←←← __ ←←←← <br/>() | `CRPM`| | | | | 
| | | **`CRPM`**| _Equivalent_ <br/>(4263/6637)| `CRPM`| | | | | 
| | | **`CRP`**| →→→→ _Equivalent_ →→→→ <br/>(4229)<hr/>←←←← __ ←←←← <br/>() | `CRP`| | | | | 
| | | **`CRP`**| _Equivalent_ <br/>(4262/6641)| `CRP`| | | | | 
| | | **`_CitizenRoleType`**| | | | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/ParticipationFunction`
| | | **`AUCG`**| →→→→ _Equivalent_ →→→→ <br/>(4247)<hr/>←←←← __ ←←←← <br/>() | `AUCG`| | | | | 
| | | **`AUCG`**| _Equivalent_ <br/>(4301/6659)| `AUCG`| | | | | 
| | | **`AULR`**| →→→→ _Equivalent_ →→→→ <br/>(4250)<hr/>←←←← __ ←←←← <br/>() | `AULR`| | | | | 
| | | **`AULR`**| _Equivalent_ <br/>(4299/6662)| `AULR`| | | | | 
| | | **`AUTM`**| →→→→ _Equivalent_ →→→→ <br/>(4248)<hr/>←←←← __ ←←←← <br/>() | `AUTM`| | | | | 
| | | **`AUTM`**| _Equivalent_ <br/>(4303/6660)| `AUTM`| | | | | 
| | | **`AUWA`**| →→→→ _Equivalent_ →→→→ <br/>(4246)<hr/>←←←← __ ←←←← <br/>() | `AUWA`| | | | | 
| | | **`AUWA`**| _Equivalent_ <br/>(4302/6658)| `AUWA`| | | | | 
| | | **`PROMSK`**| →→→→ _Equivalent_ →→→→ <br/>(4249)<hr/>←←←← __ ←←←← <br/>() | `PROMSK`| | | | | 
| | | **`PROMSK`**| _Equivalent_ <br/>(4300/6661)| `PROMSK`| | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/ParticipationType`
| | | **`AUT`**| →→→→ _Equivalent_ →→→→ <br/>(4211)<hr/>←←←← __ ←←←← <br/>() | `AUT`| | | | | 
| | | **`AUT`**| _Equivalent_ <br/>(4308/6622)| `AUT`| | | | | 
| | | **`CST`**| →→→→ _Equivalent_ →→→→ <br/>(4209)<hr/>←←←← __ ←←←← <br/>() | `CST`| | | | | 
| | | **`CST`**| _Equivalent_ <br/>(4310/6620)| `CST`| | | | | 
| | | **`INF`**| →→→→ _Equivalent_ →→→→ <br/>(4212)<hr/>←←←← __ ←←←← <br/>() | `INF`| | | | | 
| | | **`INF`**| _Equivalent_ <br/>(4307/6623)| `INF`| | | | | 
| | | **`IRCP`**| →→→→ _Equivalent_ →→→→ <br/>(4210)<hr/>←←←← __ ←←←← <br/>() | `IRCP`| | | | | 
| | | **`IRCP`**| _Equivalent_ <br/>(4304/6621)| `IRCP`| | | | | 
| | | **`LA`**| →→→→ _Equivalent_ →→→→ <br/>(4214)<hr/>←←←← __ ←←←← <br/>() | `LA`| | | | | 
| | | **`LA`**| _Equivalent_ <br/>(4305/6625)| `LA`| | | | | 
| | | **`IRCP`**| | | | | | | 
| | | **`TRC`**| →→→→ _Equivalent_ →→→→ <br/>(4213)<hr/>←←←← __ ←←←← <br/>() | `TRC`| | | | | 
| | | **`TRC`**| _Equivalent_ <br/>(4309/6624)| `TRC`| | | | | 
| | | **`WIT`**| →→→→ _Equivalent_ →→→→ <br/>(4208)<hr/>←←←← __ ←←←← <br/>() | `WIT`| | | | | 
| | | **`WIT`**| _Equivalent_ <br/>(4306/6619)| `WIT`| | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/extra-security-role-type`
| | | **`authserver`**| →→→→ _Equivalent_ →→→→ <br/>(4215)<hr/>←←←← __ ←←←← <br/>() | `authserver`| | | | | 
| | | **`authserver`**| _Equivalent_ <br/>(4314/6626)| `authserver`| | | | | 
| | | **`datacollector`**| →→→→ _Equivalent_ →→→→ <br/>(4217)<hr/>←←←← __ ←←←← <br/>() | `datacollector`| | | | | 
| | | **`datacollector`**| _Equivalent_ <br/>(4311/6628)| `datacollector`| | | | | 
| | | **`dataprocessor`**| →→→→ _Equivalent_ →→→→ <br/>(4216)<hr/>←←←← __ ←←←← <br/>() | `dataprocessor`| | | | | 
| | | **`dataprocessor`**| _Equivalent_ <br/>(4313/6627)| `dataprocessor`| | | | | 
| | | **`datasubject`**| →→→→ _Equivalent_ →→→→ <br/>(4218)<hr/>←←←← __ ←←←← <br/>() | `datasubject`| | | | | 
| | | **`datasubject`**| _Equivalent_ <br/>(4312/6629)| `datasubject`| | | | | 
| <td colspan="8">**R3** System: `http://dicom.nema.org/resources/ontology/DCM`
| `110150`| _Equivalent_ <br/>(1257/2554)| **`110150`**| _Equivalent_ <br/>(4251/6593)| `110150`| | | | | 
| `110151`| _Equivalent_ <br/>(1258/2555)| **`110151`**| _Equivalent_ <br/>(4252/6594)| `110151`| | | | | 
| `110152`| _Equivalent_ <br/>(1256/2552)| **`110152`**| _Equivalent_ <br/>(4253/6595)| `110152`| | | | | 
| `110153`| _Equivalent_ <br/>(1254/2553)| **`110153`**| _Equivalent_ <br/>(4254/6596)| `110153`| | | | | 
| `110154`| _Equivalent_ <br/>(1259/2551)| **`110154`**| _Equivalent_ <br/>(4255/6597)| `110154`| | | | | 
| `110155`| _Equivalent_ <br/>(1255/2556)| **`110155`**| _Equivalent_ <br/>(4256/6598)| `110155`| | | | | 
| *6 of 6 codes used* | | *75 of 76 codes used* <br/>remaining codes:<br/>| | *74 of 76 codes used* <br/>remaining codes:<br/>`humanuser`, `_CitizenRoleType`| | | | 

