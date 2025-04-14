Comparison of 
Generated at Monday, April 14, 2025 6:17:48 PM

### Transport

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Transport |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Transport` |
| Version | 5.0.0 |
| Description | Record of transport. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2404` |
| Database Snapshot Count | `57` |
| Database Differential Count | `40` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Transport` | `Transport` | `Transport` | Transport | Delivery of item | 0..* | Transport |  |  |
| `Transport.authoredOn` | `Transport.authoredOn` | `authoredOn` | Transport.authoredOn | Transport Creation Date | 0..1 | dateTime |  |  |
| `Transport.basedOn` | `Transport.basedOn` | `basedOn` | Transport.basedOn | Request fulfilled by this transport | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Transport.code` | `Transport.code` | `code` | Transport.code | Transport Type | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/transport-code` |
| `Transport.completionTime` | `Transport.completionTime` | `completionTime` | Transport.completionTime | Completion time of the event (the occurrence) | 0..1 | dateTime |  |  |
| `Transport.contained` | `Transport.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Transport.currentLocation` | `Transport.currentLocation` | `currentLocation` | Transport.currentLocation | The entity current location | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `Transport.description` | `Transport.description` | `description` | Transport.description | Human-readable explanation of transport | 0..1 | string |  |  |
| `Transport.encounter` | `Transport.encounter` | `encounter` | Transport.encounter | Healthcare event during which this transport originated | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `Transport.extension` | `Transport.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Transport.focus` | `Transport.focus` | `focus` | Transport.focus | What transport is acting on | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Transport.for` | `Transport.for` | `for` | Transport.for | Beneficiary of the Transport | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Transport.groupIdentifier` | `Transport.groupIdentifier` | `groupIdentifier` | Transport.groupIdentifier | Requisition or grouper id | 0..1 | Identifier |  |  |
| `Transport.history` | `Transport.history` | `history` | Transport.history | Parent (or preceding) transport | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Transport) |  |  |
| `Transport.id` | `Transport.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Transport.identifier` | `Transport.identifier` | `identifier` | Transport.identifier | External identifier | 0..* | Identifier |  |  |
| `Transport.implicitRules` | `Transport.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Transport.input` | `Transport.input` | `input` | Transport.input | Information used to perform transport | 0..* | BackboneElement |  |  |
| `Transport.input.extension` | `Transport.input.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Transport.input.id` | `Transport.input.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Transport.input.modifierExtension` | `Transport.input.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Transport.input.type` | `Transport.input.type` | `type` | Transport.input.type | Label for the input | 1..1 | CodeableConcept | `Example` |  |
| `Transport.input.value[x]` | `Transport.input.value[x]` | `value[x]` | Transport.input.value[x] | Content to use in performing the transport | 1..1 | Address, Age, Annotation, Attachment, Availability, base64Binary, boolean, canonical, code, CodeableConcept, CodeableReference, Coding, ContactDetail, ContactPoint, Count, DataRequirement, date, dateTime, decimal, Distance, Dosage, Duration, Expression, ExtendedContactDetail, HumanName, id, Identifier, instant, integer, integer64, markdown, Meta, Money, oid, ParameterDefinition, Period, positiveInt, Quantity, Range, Ratio, RatioRange, Reference, RelatedArtifact, SampledData, Signature, string, time, Timing, TriggerDefinition, unsignedInt, uri, url, UsageContext, uuid |  |  |
| `Transport.instantiatesCanonical` | `Transport.instantiatesCanonical` | `instantiatesCanonical` | Transport.instantiatesCanonical | Formal definition of transport | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/ActivityDefinition) |  |  |
| `Transport.instantiatesUri` | `Transport.instantiatesUri` | `instantiatesUri` | Transport.instantiatesUri | Formal definition of transport | 0..1 | uri |  |  |
| `Transport.insurance` | `Transport.insurance` | `insurance` | Transport.insurance | Associated insurance coverage | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ClaimResponse), Reference(http://hl7.org/fhir/StructureDefinition/Coverage) |  |  |
| `Transport.intent` | `Transport.intent` | `intent` | Transport.intent | unknown \| proposal \| plan \| order \| original-order \| reflex-order \| filler-order \| instance-order \| option | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/transport-intent|5.0.0` |
| `Transport.language` | `Transport.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Transport.lastModified` | `Transport.lastModified` | `lastModified` | Transport.lastModified | Transport Last Modified Date | 0..1 | dateTime |  |  |
| `Transport.location` | `Transport.location` | `location` | Transport.location | Where transport occurs | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `Transport.meta` | `Transport.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Transport.modifierExtension` | `Transport.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Transport.note` | `Transport.note` | `note` | Transport.note | Comments made about the transport | 0..* | Annotation |  |  |
| `Transport.output` | `Transport.output` | `output` | Transport.output | Information produced as part of transport | 0..* | BackboneElement |  |  |
| `Transport.output.extension` | `Transport.output.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Transport.output.id` | `Transport.output.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Transport.output.modifierExtension` | `Transport.output.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Transport.output.type` | `Transport.output.type` | `type` | Transport.output.type | Label for output | 1..1 | CodeableConcept | `Example` |  |
| `Transport.output.value[x]` | `Transport.output.value[x]` | `value[x]` | Transport.output.value[x] | Result of output | 1..1 | Address, Age, Annotation, Attachment, Availability, base64Binary, boolean, canonical, code, CodeableConcept, CodeableReference, Coding, ContactDetail, ContactPoint, Count, DataRequirement, date, dateTime, decimal, Distance, Dosage, Duration, Expression, ExtendedContactDetail, HumanName, id, Identifier, instant, integer, integer64, markdown, Meta, Money, oid, ParameterDefinition, Period, positiveInt, Quantity, Range, Ratio, RatioRange, Reference, RelatedArtifact, SampledData, Signature, string, time, Timing, TriggerDefinition, unsignedInt, uri, url, UsageContext, uuid |  |  |
| `Transport.owner` | `Transport.owner` | `owner` | Transport.owner | Responsible individual | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Transport.partOf` | `Transport.partOf` | `partOf` | Transport.partOf | Part of referenced event | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Transport) |  |  |
| `Transport.performerType` | `Transport.performerType` | `performerType` | Transport.performerType | Requested performer | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/performer-role` |
| `Transport.priority` | `Transport.priority` | `priority` | Transport.priority | routine \| urgent \| asap \| stat | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-priority|5.0.0` |
| `Transport.reason` | `Transport.reason` | `reason` | Transport.reason | Why transport is needed | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/Resource) | `Example` |  |
| `Transport.relevantHistory` | `Transport.relevantHistory` | `relevantHistory` | Transport.relevantHistory | Key events in history of the Transport | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Provenance) |  |  |
| `Transport.requestedLocation` | `Transport.requestedLocation` | `requestedLocation` | Transport.requestedLocation | The desired location | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `Transport.requester` | `Transport.requester` | `requester` | Transport.requester | Who is asking for transport to be done | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Transport.restriction` | `Transport.restriction` | `restriction` | Transport.restriction | Constraints on fulfillment transports | 0..1 | BackboneElement |  |  |
| `Transport.restriction.extension` | `Transport.restriction.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Transport.restriction.id` | `Transport.restriction.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Transport.restriction.modifierExtension` | `Transport.restriction.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Transport.restriction.period` | `Transport.restriction.period` | `period` | Transport.restriction.period | When fulfillment sought | 0..1 | Period |  |  |
| `Transport.restriction.recipient` | `Transport.restriction.recipient` | `recipient` | Transport.restriction.recipient | For whom is fulfillment sought? | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Transport.restriction.repetitions` | `Transport.restriction.repetitions` | `repetitions` | Transport.restriction.repetitions | How many times to repeat | 0..1 | positiveInt |  |  |
| `Transport.status` | `Transport.status` | `status` | Transport.status | in-progress \| completed \| abandoned \| cancelled \| planned \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/transport-status|5.0.0` |
| `Transport.statusReason` | `Transport.statusReason` | `statusReason` | Transport.statusReason | Reason for current status | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/transport-status-reason` |
| `Transport.text` | `Transport.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

