Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### ParticipationRoleType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ParticipationRoleType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/participation-role-type` |
| Version | 4.3.0 |
| Description | This FHIR value set is comprised of Actor participation Type codes, which can be used to value FHIR agents, actors, and other role         elements. The FHIR Actor participation type value set is based on    DICOM Audit Message, C402;   ASTM Standard, E1762-95 [2013]; selected codes and          derived actor roles from HL7 RoleClass OID 2.16.840.1.113883.5.110;    HL7 Role Code 2.16.840.1.113883.5.111, including AgentRoleType;          HL7 ParticipationType OID: 2.16.840.1.113883.5.90; and    HL7 ParticipationFunction codes OID: 2.16.840.1.113883.5.88.           This value set includes, by reference, role codes from external code systems: NUCC Health Care Provider Taxonomy OID: 2.16.840.1.113883.6.101;          North American Industry Classification System [NAICS]OID: 2.16.840.1.113883.6.85; IndustryClassificationSystem 2.16.840.1.113883.1.11.16039;          and US Census Occupation Code OID: 2.16.840.1.113883.6.243 for relevant recipient or custodian codes not included in this value set.            If no source is indicated in the definition comments, then these are example FHIR codes. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `3979` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.agent.type` | `http://hl7.org/fhir/ValueSet/participation-role-type` | `Extensible` | How agent participated |

### Expansion Failure

Failed to expand this value set: Expansion is limited
