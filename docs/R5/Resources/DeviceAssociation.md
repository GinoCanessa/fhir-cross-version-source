Comparison of 
Generated at Friday, April 4, 2025 2:59:01 PM

### DeviceAssociation

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | DeviceAssociation |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DeviceAssociation` |
| Version | 5.0.0 |
| Description | A record of association of a device. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2289` |
| Database Snapshot Count | `24` |
| Database Differential Count | `13` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DeviceAssociation` | `DeviceAssociation` | `DeviceAssociation` | DeviceAssociation | A record of association or dissociation of a device with a patient | 0..* | DeviceAssociation |  |  |
| `DeviceAssociation.bodyStructure` | `DeviceAssociation.bodyStructure` | `bodyStructure` | DeviceAssociation.bodyStructure | Current anatomical location of the device in/on subject | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/BodyStructure) |  |  |
| `DeviceAssociation.category` | `DeviceAssociation.category` | `category` | DeviceAssociation.category | Describes the relationship between the device and subject | 0..* | CodeableConcept |  |  |
| `DeviceAssociation.contained` | `DeviceAssociation.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DeviceAssociation.device` | `DeviceAssociation.device` | `device` | DeviceAssociation.device | Reference to the devices associated with the patient or group | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device) |  |  |
| `DeviceAssociation.extension` | `DeviceAssociation.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceAssociation.id` | `DeviceAssociation.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DeviceAssociation.identifier` | `DeviceAssociation.identifier` | `identifier` | DeviceAssociation.identifier | Instance identifier | 0..* | Identifier |  |  |
| `DeviceAssociation.implicitRules` | `DeviceAssociation.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DeviceAssociation.language` | `DeviceAssociation.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `DeviceAssociation.meta` | `DeviceAssociation.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DeviceAssociation.modifierExtension` | `DeviceAssociation.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DeviceAssociation.operation` | `DeviceAssociation.operation` | `operation` | DeviceAssociation.operation | The details about the device when it is in use to describe its operation | 0..* | BackboneElement |  |  |
| `DeviceAssociation.operation.extension` | `DeviceAssociation.operation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceAssociation.operation.id` | `DeviceAssociation.operation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceAssociation.operation.modifierExtension` | `DeviceAssociation.operation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceAssociation.operation.operator` | `DeviceAssociation.operation.operator` | `operator` | DeviceAssociation.operation.operator | The individual performing the action enabled by the device | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `DeviceAssociation.operation.period` | `DeviceAssociation.operation.period` | `period` | DeviceAssociation.operation.period | Begin and end dates and times for the device's operation | 0..1 | Period |  |  |
| `DeviceAssociation.operation.status` | `DeviceAssociation.operation.status` | `status` | DeviceAssociation.operation.status | Device operational condition | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/deviceassociation-operationstatus` |
| `DeviceAssociation.period` | `DeviceAssociation.period` | `period` | DeviceAssociation.period | Begin and end dates and times for the device association | 0..1 | Period |  |  |
| `DeviceAssociation.status` | `DeviceAssociation.status` | `status` | DeviceAssociation.status | implanted \| explanted \| attached \| entered-in-error \| unknown | 1..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/deviceassociation-status|5.0.0` |
| `DeviceAssociation.statusReason` | `DeviceAssociation.statusReason` | `statusReason` | DeviceAssociation.statusReason | The reasons given for the current association status | 0..* | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/deviceassociation-status-reason|5.0.0` |
| `DeviceAssociation.subject` | `DeviceAssociation.subject` | `subject` | DeviceAssociation.subject | The individual, group of individuals or device that the device is on or associated with | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `DeviceAssociation.text` | `DeviceAssociation.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

