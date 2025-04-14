Comparison of 
Generated at Monday, April 14, 2025 6:17:27 PM

### ParticipationRoleType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ParticipationRoleType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/participation-role-type` |
| Version | 4.0.1 |
| Description | This FHIR value set is comprised of Actor participation Type codes, which can be used to value FHIR agents, actors, and other role         elements. The FHIR Actor participation type value set is based on    DICOM Audit Message, C402;   ASTM Standard, E1762-95 [2013]; selected codes and          derived actor roles from HL7 RoleClass OID 2.16.840.1.113883.5.110;    HL7 Role Code 2.16.840.1.113883.5.111, including AgentRoleType;          HL7 ParticipationType OID: 2.16.840.1.113883.5.90; and    HL7 ParticipationFunction codes OID: 2.16.840.1.113883.5.88.           This value set includes, by reference, role codes from external code systems: NUCC Health Care Provider Taxonomy OID: 2.16.840.1.113883.6.101;          North American Industry Classification System [NAICS]OID: 2.16.840.1.113883.6.85; IndustryClassificationSystem 2.16.840.1.113883.1.11.16039;          and US Census Occupation Code OID: 2.16.840.1.113883.6.243 for relevant recipient or custodian codes not included in this value set.            If no source is indicated in the definition comments, then these are example FHIR codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2634` |
| Database Concept Count | `76` |
| Database Active Concept Count | `76` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.agent.type` | `http://hl7.org/fhir/ValueSet/participation-role-type` | `Extensible` | How agent participated |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/contractsignertypecodes`
* `http://terminology.hl7.org/CodeSystem/v3-RoleClass`
* `http://terminology.hl7.org/CodeSystem/v3-RoleCode`
* `http://terminology.hl7.org/CodeSystem/v3-ParticipationFunction`
* `http://terminology.hl7.org/CodeSystem/v3-ParticipationType`
* `http://terminology.hl7.org/CodeSystem/extra-security-role-type`
* `http://dicom.nema.org/resources/ontology/DCM`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://dicom.nema.org/resources/ontology/DCM` | `110150` | Application |
| `http://dicom.nema.org/resources/ontology/DCM` | `110151` | Application Launcher |
| `http://dicom.nema.org/resources/ontology/DCM` | `110152` | Destination Role ID |
| `http://dicom.nema.org/resources/ontology/DCM` | `110153` | Source Role ID |
| `http://dicom.nema.org/resources/ontology/DCM` | `110154` | Destination Media |
| `http://dicom.nema.org/resources/ontology/DCM` | `110155` | Source Media |
| `http://terminology.hl7.org/CodeSystem/contractsignertypecodes` | `AMENDER` | Amender |
| `http://terminology.hl7.org/CodeSystem/contractsignertypecodes` | `COAUTH` | Co-Author |
| `http://terminology.hl7.org/CodeSystem/contractsignertypecodes` | `CONT` | Contact |
| `http://terminology.hl7.org/CodeSystem/contractsignertypecodes` | `EVTWIT` | Event Witness |
| `http://terminology.hl7.org/CodeSystem/contractsignertypecodes` | `PRIMAUTH` | Primary Author |
| `http://terminology.hl7.org/CodeSystem/contractsignertypecodes` | `REVIEWER` | Reviewer |
| `http://terminology.hl7.org/CodeSystem/contractsignertypecodes` | `SOURCE` | Source |
| `http://terminology.hl7.org/CodeSystem/contractsignertypecodes` | `TRANS` | Transcriber |
| `http://terminology.hl7.org/CodeSystem/contractsignertypecodes` | `VALID` | Validator |
| `http://terminology.hl7.org/CodeSystem/contractsignertypecodes` | `VERF` | Verifier |
| `http://terminology.hl7.org/CodeSystem/extra-security-role-type` | `authserver` | authorization server |
| `http://terminology.hl7.org/CodeSystem/extra-security-role-type` | `datacollector` | data collector |
| `http://terminology.hl7.org/CodeSystem/extra-security-role-type` | `dataprocessor` | data processor |
| `http://terminology.hl7.org/CodeSystem/extra-security-role-type` | `datasubject` | data subject |
| `http://terminology.hl7.org/CodeSystem/extra-security-role-type` | `humanuser` | human user |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationFunction` | `AUCG` | caregiver information receiver |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationFunction` | `AULR` | legitimate relationship information receiver |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationFunction` | `AUTM` | care team information receiver |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationFunction` | `AUWA` | work area information receiver |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationFunction` | `PROMSK` | authorized provider masking author |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `AUT` | author (originator) |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `CST` | custodian |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `INF` | informant |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `IRCP` | information recipient |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `LA` | legal authenticator |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `TRC` | tracker |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `WIT` | witness |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `AFFL` | affiliate |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `AGNT` | agent |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `ASSIGNED` | assigned entity |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `CLAIM` | claimant |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `COVPTY` | covered party |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `DEPEN` | dependent |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `ECON` | emergency contact |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `EMP` | employee |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `GUARD` | guardian |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `INVSBJ` | Investigation Subject |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `NAMED` | named insured |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `NOK` | next of kin |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `NOT` | notary public |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `PAT` | patient |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `PROV` | healthcare provider |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `CAS` | asylum seeker |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `CASM` | single minor asylum seeker |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `CLASSIFIER` | classifier |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `CN` | national |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `CNRP` | non-country member without residence permit |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `CNRPM` | non-country member minor without residence permit |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `CONSENTER` | consenter |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `CONSWIT` | consent witness |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `COPART` | co-participant |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `CPCA` | permit card applicant |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `CRP` | non-country member with residence permit |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `CRPM` | non-country member minor with residence permit |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `DECLASSIFIER` | declassifier |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `DELEGATEE` | delegatee |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `DELEGATOR` | delegator |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `DOWNGRDER` | downgrader |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `DPOWATT` | durable power of attorney |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `EXCEST` | executor of estate |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `GRANTEE` | grantee |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `GRANTOR` | grantor |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `GT` | Guarantor |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `GUADLTM` | guardian ad lidem |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `HPOWATT` | healthcare power of attorney |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `INTPRTER` | interpreter |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `POWATT` | power of attorney |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `RESPRSN` | responsible party |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `SPOWATT` | special power of attorney |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `_CitizenRoleType` | CitizenRoleType |
