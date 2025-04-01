Comparison of 
Generated at Tuesday, April 1, 2025 1:39:37 PM

### EncounterHistory

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | EncounterHistory |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/EncounterHistory` |
| Version | 5.0.0 |
| Description | A record of significant events/milestones key data throughout the history of an Encounter |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2299` |
| Database Snapshot Count | `27` |
| Database Differential Count | `16` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `EncounterHistory` | `EncounterHistory` | `EncounterHistory` | EncounterHistory | A record of significant events/milestones key data throughout the history of an Encounter | 0..* | EncounterHistory |  |  |
| `EncounterHistory.actualPeriod` | `EncounterHistory.actualPeriod` | `actualPeriod` | EncounterHistory.actualPeriod | The actual start and end time associated with this set of values associated with the encounter | 0..1 | Period |  |  |
| `EncounterHistory.class` | `EncounterHistory.class` | `class` | EncounterHistory.class | Classification of patient encounter | 1..1 | CodeableConcept | `Extensible` | `http://terminology.hl7.org/ValueSet/v3-ActEncounterCode` |
| `EncounterHistory.contained` | `EncounterHistory.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `EncounterHistory.encounter` | `EncounterHistory.encounter` | `encounter` | EncounterHistory.encounter | The Encounter associated with this set of historic values | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `EncounterHistory.extension` | `EncounterHistory.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EncounterHistory.id` | `EncounterHistory.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `EncounterHistory.identifier` | `EncounterHistory.identifier` | `identifier` | EncounterHistory.identifier | Identifier(s) by which this encounter is known | 0..* | Identifier |  |  |
| `EncounterHistory.implicitRules` | `EncounterHistory.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `EncounterHistory.language` | `EncounterHistory.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `EncounterHistory.length` | `EncounterHistory.length` | `length` | EncounterHistory.length | Actual quantity of time the encounter lasted (less time absent) | 0..1 | Duration |  |  |
| `EncounterHistory.location` | `EncounterHistory.location` | `location` | EncounterHistory.location | Location of the patient at this point in the encounter | 0..* | BackboneElement |  |  |
| `EncounterHistory.location.extension` | `EncounterHistory.location.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EncounterHistory.location.form` | `EncounterHistory.location.form` | `form` | EncounterHistory.location.form | The physical type of the location (usually the level in the location hierarchy - bed, room, ward, virtual etc.) | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/location-form` |
| `EncounterHistory.location.id` | `EncounterHistory.location.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EncounterHistory.location.location` | `EncounterHistory.location.location` | `location` | EncounterHistory.location.location | Location the encounter takes place | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `EncounterHistory.location.modifierExtension` | `EncounterHistory.location.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EncounterHistory.meta` | `EncounterHistory.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `EncounterHistory.modifierExtension` | `EncounterHistory.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EncounterHistory.plannedEndDate` | `EncounterHistory.plannedEndDate` | `plannedEndDate` | EncounterHistory.plannedEndDate | The planned end date/time (or discharge date) of the encounter | 0..1 | dateTime |  |  |
| `EncounterHistory.plannedStartDate` | `EncounterHistory.plannedStartDate` | `plannedStartDate` | EncounterHistory.plannedStartDate | The planned start date/time (or admission date) of the encounter | 0..1 | dateTime |  |  |
| `EncounterHistory.serviceType` | `EncounterHistory.serviceType` | `serviceType` | EncounterHistory.serviceType | Specific type of service | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/HealthcareService) | `Example` | `http://hl7.org/fhir/ValueSet/service-type` |
| `EncounterHistory.status` | `EncounterHistory.status` | `status` | EncounterHistory.status | planned \| in-progress \| on-hold \| discharged \| completed \| cancelled \| discontinued \| entered-in-error \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/encounter-status|5.0.0` |
| `EncounterHistory.subject` | `EncounterHistory.subject` | `subject` | EncounterHistory.subject | The patient or group related to this encounter | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `EncounterHistory.subjectStatus` | `EncounterHistory.subjectStatus` | `subjectStatus` | EncounterHistory.subjectStatus | The current status of the subject in relation to the Encounter | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/encounter-subject-status` |
| `EncounterHistory.text` | `EncounterHistory.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `EncounterHistory.type` | `EncounterHistory.type` | `type` | EncounterHistory.type | Specific type of encounter | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/encounter-type` |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

