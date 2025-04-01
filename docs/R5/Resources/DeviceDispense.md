Comparison of 
Generated at Tuesday, April 1, 2025 1:39:39 PM

### DeviceDispense

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | DeviceDispense |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DeviceDispense` |
| Version | 5.0.0 |
| Description | Indicates that a device is to be or has been dispensed for a named person/patient.  This includes a description of the product (supply) provided and the instructions for using the device. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2291` |
| Database Snapshot Count | `35` |
| Database Differential Count | `24` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DeviceDispense` | `DeviceDispense` | `DeviceDispense` | DeviceDispense | A record of dispensation of a device | 0..* | DeviceDispense |  |  |
| `DeviceDispense.basedOn` | `DeviceDispense.basedOn` | `basedOn` | DeviceDispense.basedOn | The order or request that this dispense is fulfilling | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/CarePlan), Reference(http://hl7.org/fhir/StructureDefinition/DeviceRequest) |  |  |
| `DeviceDispense.category` | `DeviceDispense.category` | `category` | DeviceDispense.category | Type of device dispense | 0..* | CodeableConcept |  |  |
| `DeviceDispense.contained` | `DeviceDispense.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DeviceDispense.destination` | `DeviceDispense.destination` | `destination` | DeviceDispense.destination | Where the device was sent or should be sent | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `DeviceDispense.device` | `DeviceDispense.device` | `device` | DeviceDispense.device | What device was supplied | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/Device), CodeableReference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition) |  |  |
| `DeviceDispense.encounter` | `DeviceDispense.encounter` | `encounter` | DeviceDispense.encounter | Encounter associated with event | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `DeviceDispense.eventHistory` | `DeviceDispense.eventHistory` | `eventHistory` | DeviceDispense.eventHistory | A list of relevant lifecycle events | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Provenance) |  |  |
| `DeviceDispense.extension` | `DeviceDispense.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDispense.id` | `DeviceDispense.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DeviceDispense.identifier` | `DeviceDispense.identifier` | `identifier` | DeviceDispense.identifier | Business identifier for this dispensation | 0..* | Identifier |  |  |
| `DeviceDispense.implicitRules` | `DeviceDispense.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DeviceDispense.language` | `DeviceDispense.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `DeviceDispense.location` | `DeviceDispense.location` | `location` | DeviceDispense.location | Where the dispense occurred | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `DeviceDispense.meta` | `DeviceDispense.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DeviceDispense.modifierExtension` | `DeviceDispense.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DeviceDispense.note` | `DeviceDispense.note` | `note` | DeviceDispense.note | Information about the dispense | 0..* | Annotation |  |  |
| `DeviceDispense.partOf` | `DeviceDispense.partOf` | `partOf` | DeviceDispense.partOf | The bigger event that this dispense is a part of | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Procedure) |  |  |
| `DeviceDispense.performer` | `DeviceDispense.performer` | `performer` | DeviceDispense.performer | Who performed event | 0..* | BackboneElement |  |  |
| `DeviceDispense.performer.actor` | `DeviceDispense.performer.actor` | `actor` | DeviceDispense.performer.actor | Individual who was performing | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `DeviceDispense.performer.extension` | `DeviceDispense.performer.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDispense.performer.function` | `DeviceDispense.performer.function` | `function` | DeviceDispense.performer.function | Who performed the dispense and what they did | 0..1 | CodeableConcept |  |  |
| `DeviceDispense.performer.id` | `DeviceDispense.performer.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDispense.performer.modifierExtension` | `DeviceDispense.performer.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDispense.preparedDate` | `DeviceDispense.preparedDate` | `preparedDate` | DeviceDispense.preparedDate | When product was packaged and reviewed | 0..1 | dateTime |  |  |
| `DeviceDispense.quantity` | `DeviceDispense.quantity` | `quantity` | DeviceDispense.quantity | Amount dispensed | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `DeviceDispense.receiver` | `DeviceDispense.receiver` | `receiver` | DeviceDispense.receiver | Who collected the device or where the medication was delivered | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `DeviceDispense.status` | `DeviceDispense.status` | `status` | DeviceDispense.status | preparation \| in-progress \| cancelled \| on-hold \| completed \| entered-in-error \| stopped \| declined \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/devicedispense-status|5.0.0` |
| `DeviceDispense.statusReason` | `DeviceDispense.statusReason` | `statusReason` | DeviceDispense.statusReason | Why a dispense was or was not performed | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/DetectedIssue) | `Example` | `http://hl7.org/fhir/ValueSet/devicedispense-status-reason` |
| `DeviceDispense.subject` | `DeviceDispense.subject` | `subject` | DeviceDispense.subject | Who the dispense is for | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `DeviceDispense.supportingInformation` | `DeviceDispense.supportingInformation` | `supportingInformation` | DeviceDispense.supportingInformation | Information that supports the dispensing of the device | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `DeviceDispense.text` | `DeviceDispense.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `DeviceDispense.type` | `DeviceDispense.type` | `type` | DeviceDispense.type | Trial fill, partial fill, emergency fill, etc | 0..1 | CodeableConcept |  |  |
| `DeviceDispense.usageInstruction` | `DeviceDispense.usageInstruction` | `usageInstruction` | DeviceDispense.usageInstruction | Full representation of the usage instructions | 0..1 | markdown |  |  |
| `DeviceDispense.whenHandedOver` | `DeviceDispense.whenHandedOver` | `whenHandedOver` | DeviceDispense.whenHandedOver | When product was given out | 0..1 | dateTime |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

