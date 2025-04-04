Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### ParticipationRoleType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ParticipationRoleType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/participation-role-type` |
| Version | 5.0.0 |
| Description | This FHIR value set is comprised of Actor participation Type codes, which can be used to value FHIR agents, actors, and other role elements. The codes are intended to express how the agent participated in some activity. Sometimes refered to the agent functional-role relative to the activity. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4780` |
| Database Concept Count | `21` |
| Database Active Concept Count | `21` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AllergyIntolerance` | `AllergyIntolerance.participant.function` | `http://hl7.org/fhir/ValueSet/participation-role-type` | `Extensible` | Type of involvement |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.agent.type` | `http://hl7.org/fhir/ValueSet/participation-role-type` | `Preferred` | How agent participated |
| `http://hl7.org/fhir/StructureDefinition/Condition` | `Condition.participant.function` | `http://hl7.org/fhir/ValueSet/participation-role-type` | `Extensible` | Type of involvement |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.provision.actor.role` | `http://hl7.org/fhir/ValueSet/participation-role-type` | `Extensible` | How the actor is involved |
| `http://hl7.org/fhir/StructureDefinition/Contract` | `Contract.term.action.performerType` | `http://hl7.org/fhir/ValueSet/participation-role-type` | `Example` | Kind of service performer |
| `http://hl7.org/fhir/StructureDefinition/FamilyMemberHistory` | `FamilyMemberHistory.participant.function` | `http://hl7.org/fhir/ValueSet/participation-role-type` | `Extensible` | Type of involvement |
| `http://hl7.org/fhir/StructureDefinition/Provenance` | `Provenance.agent.type` | `http://hl7.org/fhir/ValueSet/participation-role-type` | `Example` | How the agent participated |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/provenance-participant-type`
* `http://dicom.nema.org/resources/ontology/DCM`
* `http://terminology.hl7.org/CodeSystem/extra-security-role-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [SecurityRoleType](/docs/R4B/ValueSets/SecurityRoleType.md)<br/> `http://hl7.org/fhir/ValueSet/security-role-type\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `961`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1222`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipationRoleType](/docs/R5/ValueSets/ParticipationRoleType.md)<br/> `http://hl7.org/fhir/ValueSet/participation-role-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ParticipationRoleType from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B SecurityRoleType](/docs/R4B/ValueSets/SecurityRoleType.md)| Relationship | R5 ParticipationRoleType
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://terminology.hl7.org/CodeSystem/provenance-participant-type`
| | | | | | | | | **`enterer`**
| | | | | | | | | **`performer`**
| | | | | | | | | **`author`**
| | | | | | | | | **`verifier`**
| | | | | | | | | **`legal`**
| | | | | | | | | **`attester`**
| | | | | | | | | **`informant`**
| | | | | | | | | **`custodian`**
| | | | | | | | | **`assembler`**
| | | | | | | | | **`composer`**
| <td colspan="8">**R5** System: `http://dicom.nema.org/resources/ontology/DCM`
| | | | | | | | | **`110150`**
| | | | | | | | | **`110151`**
| | | | | | | | | **`110152`**
| | | | | | | | | **`110153`**
| | | | | | | | | **`110154`**
| | | | | | | | | **`110155`**
| <td colspan="8">**R5** System: `http://terminology.hl7.org/CodeSystem/extra-security-role-type`
| | | | | | | | | **`authserver`**
| | | | | | | | | **`datacollector`**
| | | | | | | | | **`dataprocessor`**
| | | | | | | | | **`datasubject`**
| | | | | | | | | **`humanuser`**
| | | | | | | *0 of 0 codes used* | | *21 of 21 codes used* 

