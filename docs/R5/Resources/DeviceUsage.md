Comparison of 
Generated at Thursday, April 3, 2025 8:18:35 AM

### DeviceUsage

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | DeviceUsage |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DeviceUsage` |
| Version | 5.0.0 |
| Description | A record of a device being used by a patient where the record is the result of a report from the patient or a clinician. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2294` |
| Database Snapshot Count | `31` |
| Database Differential Count | `20` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DeviceUsage` | `DeviceUsage` | `DeviceUsage` | DeviceUsage | Record of use of a device | 0..* | DeviceUsage |  |  |
| `DeviceUsage.adherence` | `DeviceUsage.adherence` | `adherence` | DeviceUsage.adherence | How device is being used | 0..1 | BackboneElement |  |  |
| `DeviceUsage.adherence.code` | `DeviceUsage.adherence.code` | `code` | DeviceUsage.adherence.code | always \| never \| sometimes | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/deviceusage-adherence-code` |
| `DeviceUsage.adherence.extension` | `DeviceUsage.adherence.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceUsage.adherence.id` | `DeviceUsage.adherence.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceUsage.adherence.modifierExtension` | `DeviceUsage.adherence.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceUsage.adherence.reason` | `DeviceUsage.adherence.reason` | `reason` | DeviceUsage.adherence.reason | lost \| stolen \| prescribed \| broken \| burned \| forgot | 1..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/deviceusage-adherence-reason` |
| `DeviceUsage.basedOn` | `DeviceUsage.basedOn` | `basedOn` | DeviceUsage.basedOn | Fulfills plan, proposal or order | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ServiceRequest) |  |  |
| `DeviceUsage.bodySite` | `DeviceUsage.bodySite` | `bodySite` | DeviceUsage.bodySite | Target body site | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/BodyStructure) | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `DeviceUsage.category` | `DeviceUsage.category` | `category` | DeviceUsage.category | The category of the statement - classifying how the statement is made | 0..* | CodeableConcept |  |  |
| `DeviceUsage.contained` | `DeviceUsage.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DeviceUsage.context` | `DeviceUsage.context` | `context` | DeviceUsage.context | The encounter or episode of care that establishes the context for this device use statement | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter), Reference(http://hl7.org/fhir/StructureDefinition/EpisodeOfCare) |  |  |
| `DeviceUsage.dateAsserted` | `DeviceUsage.dateAsserted` | `dateAsserted` | DeviceUsage.dateAsserted | When the statement was made (and recorded) | 0..1 | dateTime |  |  |
| `DeviceUsage.derivedFrom` | `DeviceUsage.derivedFrom` | `derivedFrom` | DeviceUsage.derivedFrom | Supporting information | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Claim), Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/Observation), Reference(http://hl7.org/fhir/StructureDefinition/Procedure), Reference(http://hl7.org/fhir/StructureDefinition/QuestionnaireResponse), Reference(http://hl7.org/fhir/StructureDefinition/ServiceRequest) |  |  |
| `DeviceUsage.device` | `DeviceUsage.device` | `device` | DeviceUsage.device | Code or Reference to device used | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/Device), CodeableReference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition) |  |  |
| `DeviceUsage.extension` | `DeviceUsage.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceUsage.id` | `DeviceUsage.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DeviceUsage.identifier` | `DeviceUsage.identifier` | `identifier` | DeviceUsage.identifier | External identifier for this record | 0..* | Identifier |  |  |
| `DeviceUsage.implicitRules` | `DeviceUsage.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DeviceUsage.informationSource` | `DeviceUsage.informationSource` | `informationSource` | DeviceUsage.informationSource | Who made the statement | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `DeviceUsage.language` | `DeviceUsage.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `DeviceUsage.meta` | `DeviceUsage.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DeviceUsage.modifierExtension` | `DeviceUsage.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DeviceUsage.note` | `DeviceUsage.note` | `note` | DeviceUsage.note | Addition details (comments, instructions) | 0..* | Annotation |  |  |
| `DeviceUsage.patient` | `DeviceUsage.patient` | `patient` | DeviceUsage.patient | Patient using device | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `DeviceUsage.reason` | `DeviceUsage.reason` | `reason` | DeviceUsage.reason | Why device was used | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/Condition), CodeableReference(http://hl7.org/fhir/StructureDefinition/DiagnosticReport), CodeableReference(http://hl7.org/fhir/StructureDefinition/DocumentReference), CodeableReference(http://hl7.org/fhir/StructureDefinition/Observation), CodeableReference(http://hl7.org/fhir/StructureDefinition/Procedure) |  |  |
| `DeviceUsage.status` | `DeviceUsage.status` | `status` | DeviceUsage.status | active \| completed \| not-done \| entered-in-error + | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/deviceusage-status|5.0.0` |
| `DeviceUsage.text` | `DeviceUsage.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `DeviceUsage.timing[x]` | `DeviceUsage.timing[x]` | `timing[x]` | DeviceUsage.timing[x] | How often  the device was used | 0..1 | dateTime, Period, Timing |  |  |
| `DeviceUsage.usageReason` | `DeviceUsage.usageReason` | `usageReason` | DeviceUsage.usageReason | The reason for asserting the usage status - for example forgot, lost, stolen, broken | 0..* | CodeableConcept |  |  |
| `DeviceUsage.usageStatus` | `DeviceUsage.usageStatus` | `usageStatus` | DeviceUsage.usageStatus | The status of the device usage, for example always, sometimes, never. This is not the same as the status of the statement | 0..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/deviceusage-status|5.0.0` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DeviceUseStatement](/docs/R2/Resources/DeviceUseStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUseStatement\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `101`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `268`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceUseStatement](/docs/R3/Resources/DeviceUseStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUseStatement\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `450`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `645`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceUseStatement](/docs/R4/Resources/DeviceUseStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUseStatement\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1463`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1464`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceUseStatement](/docs/R4B/Resources/DeviceUseStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUseStatement\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `966`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1195`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceUsage](/docs/R5/Resources/DeviceUsage.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUsage\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DeviceUsage from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 DeviceUseStatement](/docs/R2/Resources/DeviceUseStatement.md)| Relationship | [R3 DeviceUseStatement](/docs/R3/Resources/DeviceUseStatement.md)| Relationship | [R4 DeviceUseStatement](/docs/R4/Resources/DeviceUseStatement.md)| Relationship | [R4B DeviceUseStatement](/docs/R4B/Resources/DeviceUseStatement.md)| Relationship | R5 DeviceUsage
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | | | **`DeviceUsage`**
| | | | | | | | | **`DeviceUsage.id`**
| | | | | | | | | **`DeviceUsage.meta`**
| | | | | | | | | **`DeviceUsage.implicitRules`**
| | | | | | | | | **`DeviceUsage.language`**
| | | | | | | | | **`DeviceUsage.text`**
| | | | | | | | | **`DeviceUsage.contained`**
| | | | | | | | | **`DeviceUsage.extension`**
| | | | | | | | | **`DeviceUsage.modifierExtension`**
| | | | | | | | | **`DeviceUsage.identifier`**
| | | | | | | | | **`DeviceUsage.basedOn`**
| | | | | | | | | **`DeviceUsage.status`**
| | | | | | | | | **`DeviceUsage.category`**
| | | | | | | | | **`DeviceUsage.patient`**
| | | | | | | | | **`DeviceUsage.derivedFrom`**
| | | | | | | | | **`DeviceUsage.context`**
| | | | | | | | | **`DeviceUsage.timing[x]`**
| | | | | | | | | **`DeviceUsage.dateAsserted`**
| | | | | | | | | **`DeviceUsage.usageStatus`**
| | | | | | | | | **`DeviceUsage.usageReason`**
| | | | | | | | | **`DeviceUsage.adherence`**
| | | | | | | | | **`DeviceUsage.adherence.id`**
| | | | | | | | | **`DeviceUsage.adherence.extension`**
| | | | | | | | | **`DeviceUsage.adherence.modifierExtension`**
| | | | | | | | | **`DeviceUsage.adherence.code`**
| | | | | | | | | **`DeviceUsage.adherence.reason`**
| | | | | | | | | **`DeviceUsage.informationSource`**
| | | | | | | | | **`DeviceUsage.device`**
| | | | | | | | | **`DeviceUsage.reason`**
| | | | | | | | | **`DeviceUsage.bodySite`**
| | | | | | | | | **`DeviceUsage.note`**
| *0 of 18 elements used* <br/>remaining elements:<br/>`DeviceUseStatement`, `DeviceUseStatement.bodySite[x]`, `DeviceUseStatement.contained`, `DeviceUseStatement.device`, `DeviceUseStatement.extension`, `DeviceUseStatement.id`, `DeviceUseStatement.identifier`, `DeviceUseStatement.implicitRules`, `DeviceUseStatement.indication`, `DeviceUseStatement.language`, `DeviceUseStatement.meta`, `DeviceUseStatement.modifierExtension`, `DeviceUseStatement.notes`, `DeviceUseStatement.recordedOn`, `DeviceUseStatement.subject`, `DeviceUseStatement.text`, `DeviceUseStatement.timing[x]`, `DeviceUseStatement.whenUsed`| | *0 of 20 elements used* <br/>remaining elements:<br/>`DeviceUseStatement`, `DeviceUseStatement.bodySite`, `DeviceUseStatement.contained`, `DeviceUseStatement.device`, `DeviceUseStatement.extension`, `DeviceUseStatement.id`, `DeviceUseStatement.identifier`, `DeviceUseStatement.implicitRules`, `DeviceUseStatement.indication`, `DeviceUseStatement.language`, `DeviceUseStatement.meta`, `DeviceUseStatement.modifierExtension`, `DeviceUseStatement.note`, `DeviceUseStatement.recordedOn`, `DeviceUseStatement.source`, `DeviceUseStatement.status`, `DeviceUseStatement.subject`, `DeviceUseStatement.text`, `DeviceUseStatement.timing[x]`, `DeviceUseStatement.whenUsed`| | *0 of 22 elements used* <br/>remaining elements:<br/>`DeviceUseStatement`, `DeviceUseStatement.basedOn`, `DeviceUseStatement.bodySite`, `DeviceUseStatement.contained`, `DeviceUseStatement.derivedFrom`, `DeviceUseStatement.device`, `DeviceUseStatement.extension`, `DeviceUseStatement.id`, `DeviceUseStatement.identifier`, `DeviceUseStatement.implicitRules`, `DeviceUseStatement.language`, `DeviceUseStatement.meta`, `DeviceUseStatement.modifierExtension`, `DeviceUseStatement.note`, `DeviceUseStatement.reasonCode`, `DeviceUseStatement.reasonReference`, `DeviceUseStatement.recordedOn`, `DeviceUseStatement.source`, `DeviceUseStatement.status`, `DeviceUseStatement.subject`, `DeviceUseStatement.text`, `DeviceUseStatement.timing[x]`| | *0 of 22 elements used* <br/>remaining elements:<br/>`DeviceUseStatement`, `DeviceUseStatement.basedOn`, `DeviceUseStatement.bodySite`, `DeviceUseStatement.contained`, `DeviceUseStatement.derivedFrom`, `DeviceUseStatement.device`, `DeviceUseStatement.extension`, `DeviceUseStatement.id`, `DeviceUseStatement.identifier`, `DeviceUseStatement.implicitRules`, `DeviceUseStatement.language`, `DeviceUseStatement.meta`, `DeviceUseStatement.modifierExtension`, `DeviceUseStatement.note`, `DeviceUseStatement.reasonCode`, `DeviceUseStatement.reasonReference`, `DeviceUseStatement.recordedOn`, `DeviceUseStatement.source`, `DeviceUseStatement.status`, `DeviceUseStatement.subject`, `DeviceUseStatement.text`, `DeviceUseStatement.timing[x]`| | *31 of 31 elements used* 

