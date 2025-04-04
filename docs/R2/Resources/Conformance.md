Comparison of 
Generated at Friday, April 4, 2025 2:58:34 PM

### Conformance

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Conformance |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Conformance` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Conformance Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `59` |
| Database Snapshot Count | `138` |
| Database Differential Count | `85` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Conformance` | `Conformance` | `Conformance` | Conformance | A conformance statement | 1..1 | Conformance |  |  |
| `Conformance.acceptUnknown` | `Conformance.acceptUnknown` | `acceptUnknown` |  | no \| extensions \| elements \| both | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/unknown-content-code` |
| `Conformance.contact` | `Conformance.contact` | `contact` |  | Contact details of the publisher | 0..* | BackboneElement |  |  |
| `Conformance.contact.extension` | `Conformance.contact.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.contact.id` | `Conformance.contact.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Conformance.contact.modifierExtension` | `Conformance.contact.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.contact.name` | `Conformance.contact.name` | `name` |  | Name of a individual to contact | 0..1 | string |  |  |
| `Conformance.contact.telecom` | `Conformance.contact.telecom` | `telecom` |  | Contact details for individual or publisher | 0..* | ContactPoint |  |  |
| `Conformance.contained` | `Conformance.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Conformance.copyright` | `Conformance.copyright` | `copyright` |  | Use and/or publishing restrictions | 0..1 | string |  |  |
| `Conformance.date` | `Conformance.date` | `date` |  | Publication Date(/time) | 1..1 | dateTime |  |  |
| `Conformance.description` | `Conformance.description` | `description` |  | Human description of the conformance statement | 0..1 | string |  |  |
| `Conformance.document` | `Conformance.document` | `document` |  | Document definition | 0..* | BackboneElement |  |  |
| `Conformance.document.documentation` | `Conformance.document.documentation` | `documentation` |  | Description of document support | 0..1 | string |  |  |
| `Conformance.document.extension` | `Conformance.document.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.document.id` | `Conformance.document.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Conformance.document.mode` | `Conformance.document.mode` | `mode` |  | producer \| consumer | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/document-mode` |
| `Conformance.document.modifierExtension` | `Conformance.document.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.document.profile` | `Conformance.document.profile` | `profile` |  | Constraint on a resource used in the document | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/StructureDefinition) |  |  |
| `Conformance.experimental` | `Conformance.experimental` | `experimental` |  | If for testing purposes, not real usage | 0..1 | boolean |  |  |
| `Conformance.extension` | `Conformance.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.fhirVersion` | `Conformance.fhirVersion` | `fhirVersion` |  | FHIR Version the system uses | 1..1 | id |  |  |
| `Conformance.format` | `Conformance.format` | `format` |  | formats supported (xml \| json \| mime type) | 1..* | code | `Required` | `http://www.rfc-editor.org/bcp/bcp13.txt` |
| `Conformance.id` | `Conformance.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Conformance.implementation` | `Conformance.implementation` | `implementation` |  | If this describes a specific instance | 0..1 | BackboneElement |  |  |
| `Conformance.implementation.description` | `Conformance.implementation.description` | `description` |  | Describes this specific instance | 1..1 | string |  |  |
| `Conformance.implementation.extension` | `Conformance.implementation.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.implementation.id` | `Conformance.implementation.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Conformance.implementation.modifierExtension` | `Conformance.implementation.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.implementation.url` | `Conformance.implementation.url` | `url` |  | Base URL for the installation | 0..1 | uri |  |  |
| `Conformance.implicitRules` | `Conformance.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Conformance.kind` | `Conformance.kind` | `kind` |  | instance \| capability \| requirements | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/conformance-statement-kind` |
| `Conformance.language` | `Conformance.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Conformance.messaging` | `Conformance.messaging` | `messaging` |  | If messaging is supported | 0..* | BackboneElement |  |  |
| `Conformance.messaging.documentation` | `Conformance.messaging.documentation` | `documentation` |  | Messaging interface behavior details | 0..1 | string |  |  |
| `Conformance.messaging.endpoint` | `Conformance.messaging.endpoint` | `endpoint` |  | A messaging service end-point | 0..* | BackboneElement |  |  |
| `Conformance.messaging.endpoint.address` | `Conformance.messaging.endpoint.address` | `address` |  | Address of end-point | 1..1 | uri |  |  |
| `Conformance.messaging.endpoint.extension` | `Conformance.messaging.endpoint.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.messaging.endpoint.id` | `Conformance.messaging.endpoint.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Conformance.messaging.endpoint.modifierExtension` | `Conformance.messaging.endpoint.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.messaging.endpoint.protocol` | `Conformance.messaging.endpoint.protocol` | `protocol` |  | http \| ftp \| mllp + | 1..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/message-transport` |
| `Conformance.messaging.event` | `Conformance.messaging.event` | `event` |  | Declare support for this event | 1..* | BackboneElement |  |  |
| `Conformance.messaging.event.category` | `Conformance.messaging.event.category` | `category` |  | Consequence \| Currency \| Notification | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/message-significance-category` |
| `Conformance.messaging.event.code` | `Conformance.messaging.event.code` | `code` |  | Event type | 1..1 | Coding | `Preferred` | `http://hl7.org/fhir/ValueSet/message-events` |
| `Conformance.messaging.event.documentation` | `Conformance.messaging.event.documentation` | `documentation` |  | Endpoint-specific event documentation | 0..1 | string |  |  |
| `Conformance.messaging.event.extension` | `Conformance.messaging.event.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.messaging.event.focus` | `Conformance.messaging.event.focus` | `focus` |  | Resource that's focus of message | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/resource-types` |
| `Conformance.messaging.event.id` | `Conformance.messaging.event.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Conformance.messaging.event.mode` | `Conformance.messaging.event.mode` | `mode` |  | sender \| receiver | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/message-conformance-event-mode` |
| `Conformance.messaging.event.modifierExtension` | `Conformance.messaging.event.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.messaging.event.request` | `Conformance.messaging.event.request` | `request` |  | Profile that describes the request | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/StructureDefinition) |  |  |
| `Conformance.messaging.event.response` | `Conformance.messaging.event.response` | `response` |  | Profile that describes the response | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/StructureDefinition) |  |  |
| `Conformance.messaging.extension` | `Conformance.messaging.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.messaging.id` | `Conformance.messaging.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Conformance.messaging.modifierExtension` | `Conformance.messaging.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.messaging.reliableCache` | `Conformance.messaging.reliableCache` | `reliableCache` |  | Reliable Message Cache Length (min) | 0..1 | unsignedInt |  |  |
| `Conformance.meta` | `Conformance.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Conformance.modifierExtension` | `Conformance.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.name` | `Conformance.name` | `name` |  | Informal name for this conformance statement | 0..1 | string |  |  |
| `Conformance.profile` | `Conformance.profile` | `profile` |  | Profiles for use cases supported | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/StructureDefinition) |  |  |
| `Conformance.publisher` | `Conformance.publisher` | `publisher` |  | Name of the publisher (Organization or individual) | 0..1 | string |  |  |
| `Conformance.requirements` | `Conformance.requirements` | `requirements` |  | Why is this needed? | 0..1 | string |  |  |
| `Conformance.rest` | `Conformance.rest` | `rest` |  | If the endpoint is a RESTful one | 0..* | BackboneElement |  |  |
| `Conformance.rest.compartment` | `Conformance.rest.compartment` | `compartment` |  | Compartments served/used by system | 0..* | uri |  |  |
| `Conformance.rest.documentation` | `Conformance.rest.documentation` | `documentation` |  | General description of implementation | 0..1 | string |  |  |
| `Conformance.rest.extension` | `Conformance.rest.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.rest.id` | `Conformance.rest.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Conformance.rest.interaction` | `Conformance.rest.interaction` | `interaction` |  | What operations are supported? | 0..* | BackboneElement |  |  |
| `Conformance.rest.interaction.code` | `Conformance.rest.interaction.code` | `code` |  | transaction \| search-system \| history-system | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/system-restful-interaction` |
| `Conformance.rest.interaction.documentation` | `Conformance.rest.interaction.documentation` | `documentation` |  | Anything special about operation behavior | 0..1 | string |  |  |
| `Conformance.rest.interaction.extension` | `Conformance.rest.interaction.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.rest.interaction.id` | `Conformance.rest.interaction.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Conformance.rest.interaction.modifierExtension` | `Conformance.rest.interaction.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.rest.mode` | `Conformance.rest.mode` | `mode` |  | client \| server | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/restful-conformance-mode` |
| `Conformance.rest.modifierExtension` | `Conformance.rest.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.rest.operation` | `Conformance.rest.operation` | `operation` |  | Definition of an operation or a custom query | 0..* | BackboneElement |  |  |
| `Conformance.rest.operation.definition` | `Conformance.rest.operation.definition` | `definition` |  | The defined operation/query | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/OperationDefinition) |  |  |
| `Conformance.rest.operation.extension` | `Conformance.rest.operation.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.rest.operation.id` | `Conformance.rest.operation.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Conformance.rest.operation.modifierExtension` | `Conformance.rest.operation.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.rest.operation.name` | `Conformance.rest.operation.name` | `name` |  | Name by which the operation/query is invoked | 1..1 | string |  |  |
| `Conformance.rest.resource` | `Conformance.rest.resource` | `resource` |  | Resource served on the REST interface | 1..* | BackboneElement |  |  |
| `Conformance.rest.resource.conditionalCreate` | `Conformance.rest.resource.conditionalCreate` | `conditionalCreate` |  | If allows/uses conditional create | 0..1 | boolean |  |  |
| `Conformance.rest.resource.conditionalDelete` | `Conformance.rest.resource.conditionalDelete` | `conditionalDelete` |  | not-supported \| single \| multiple - how conditional delete is supported | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/conditional-delete-status` |
| `Conformance.rest.resource.conditionalUpdate` | `Conformance.rest.resource.conditionalUpdate` | `conditionalUpdate` |  | If allows/uses conditional update | 0..1 | boolean |  |  |
| `Conformance.rest.resource.extension` | `Conformance.rest.resource.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.rest.resource.id` | `Conformance.rest.resource.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Conformance.rest.resource.interaction` | `Conformance.rest.resource.interaction` | `interaction` |  | What operations are supported? | 1..* | BackboneElement |  |  |
| `Conformance.rest.resource.interaction.code` | `Conformance.rest.resource.interaction.code` | `code` |  | read \| vread \| update \| delete \| history-instance \| validate \| history-type \| create \| search-type | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/type-restful-interaction` |
| `Conformance.rest.resource.interaction.documentation` | `Conformance.rest.resource.interaction.documentation` | `documentation` |  | Anything special about operation behavior | 0..1 | string |  |  |
| `Conformance.rest.resource.interaction.extension` | `Conformance.rest.resource.interaction.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.rest.resource.interaction.id` | `Conformance.rest.resource.interaction.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Conformance.rest.resource.interaction.modifierExtension` | `Conformance.rest.resource.interaction.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.rest.resource.modifierExtension` | `Conformance.rest.resource.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.rest.resource.profile` | `Conformance.rest.resource.profile` | `profile` |  | Base System profile for all uses of resource | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/StructureDefinition) |  |  |
| `Conformance.rest.resource.readHistory` | `Conformance.rest.resource.readHistory` | `readHistory` |  | Whether vRead can return past versions | 0..1 | boolean |  |  |
| `Conformance.rest.resource.searchInclude` | `Conformance.rest.resource.searchInclude` | `searchInclude` |  | _include values supported by the server | 0..* | string |  |  |
| `Conformance.rest.resource.searchParam` | `Conformance.rest.resource.searchParam` | `searchParam` |  | Search params supported by implementation | 0..* | BackboneElement |  |  |
| `Conformance.rest.resource.searchParam.chain` | `Conformance.rest.resource.searchParam.chain` | `chain` |  | Chained names supported | 0..* | string |  |  |
| `Conformance.rest.resource.searchParam.definition` | `Conformance.rest.resource.searchParam.definition` | `definition` |  | Source of definition for parameter | 0..1 | uri |  |  |
| `Conformance.rest.resource.searchParam.documentation` | `Conformance.rest.resource.searchParam.documentation` | `documentation` |  | Server-specific usage | 0..1 | string |  |  |
| `Conformance.rest.resource.searchParam.extension` | `Conformance.rest.resource.searchParam.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.rest.resource.searchParam.id` | `Conformance.rest.resource.searchParam.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Conformance.rest.resource.searchParam.modifier` | `Conformance.rest.resource.searchParam.modifier` | `modifier` |  | missing \| exact \| contains \| not \| text \| in \| not-in \| below \| above \| type | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/search-modifier-code` |
| `Conformance.rest.resource.searchParam.modifierExtension` | `Conformance.rest.resource.searchParam.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.rest.resource.searchParam.name` | `Conformance.rest.resource.searchParam.name` | `name` |  | Name of search parameter | 1..1 | string |  |  |
| `Conformance.rest.resource.searchParam.target` | `Conformance.rest.resource.searchParam.target` | `target` |  | Types of resource (if a resource reference) | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/resource-types` |
| `Conformance.rest.resource.searchParam.type` | `Conformance.rest.resource.searchParam.type` | `type` |  | number \| date \| string \| token \| reference \| composite \| quantity \| uri | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/search-param-type` |
| `Conformance.rest.resource.searchRevInclude` | `Conformance.rest.resource.searchRevInclude` | `searchRevInclude` |  | _revinclude values supported by the server | 0..* | string |  |  |
| `Conformance.rest.resource.type` | `Conformance.rest.resource.type` | `type` |  | A resource type that is supported | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/resource-types` |
| `Conformance.rest.resource.updateCreate` | `Conformance.rest.resource.updateCreate` | `updateCreate` |  | If update can commit to a new identity | 0..1 | boolean |  |  |
| `Conformance.rest.resource.versioning` | `Conformance.rest.resource.versioning` | `versioning` |  | no-version \| versioned \| versioned-update | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/versioning-policy` |
| `Conformance.rest.searchParam` | `Conformance.rest.searchParam` | `searchParam` |  | Search params for searching all resources | 0..* | Conformance.rest.resource.searchParam |  |  |
| `Conformance.rest.security` | `Conformance.rest.security` | `security` |  | Information about security of implementation | 0..1 | BackboneElement |  |  |
| `Conformance.rest.security.certificate` | `Conformance.rest.security.certificate` | `certificate` |  | Certificates associated with security profiles | 0..* | BackboneElement |  |  |
| `Conformance.rest.security.certificate.blob` | `Conformance.rest.security.certificate.blob` | `blob` |  | Actual certificate | 0..1 | base64Binary |  |  |
| `Conformance.rest.security.certificate.extension` | `Conformance.rest.security.certificate.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.rest.security.certificate.id` | `Conformance.rest.security.certificate.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Conformance.rest.security.certificate.modifierExtension` | `Conformance.rest.security.certificate.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.rest.security.certificate.type` | `Conformance.rest.security.certificate.type` | `type` |  | Mime type for certificate | 0..1 | code | `Required` | `http://www.rfc-editor.org/bcp/bcp13.txt` |
| `Conformance.rest.security.cors` | `Conformance.rest.security.cors` | `cors` |  | Adds CORS Headers (http://enable-cors.org/) | 0..1 | boolean |  |  |
| `Conformance.rest.security.description` | `Conformance.rest.security.description` | `description` |  | General description of how security works | 0..1 | string |  |  |
| `Conformance.rest.security.extension` | `Conformance.rest.security.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.rest.security.id` | `Conformance.rest.security.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Conformance.rest.security.modifierExtension` | `Conformance.rest.security.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.rest.security.service` | `Conformance.rest.security.service` | `service` |  | OAuth \| SMART-on-FHIR \| NTLM \| Basic \| Kerberos \| Certificates | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/restful-security-service` |
| `Conformance.rest.transactionMode` | `Conformance.rest.transactionMode` | `transactionMode` |  | not-supported \| batch \| transaction \| both | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/transaction-mode` |
| `Conformance.software` | `Conformance.software` | `software` |  | Software that is covered by this conformance statement | 0..1 | BackboneElement |  |  |
| `Conformance.software.extension` | `Conformance.software.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Conformance.software.id` | `Conformance.software.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Conformance.software.modifierExtension` | `Conformance.software.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Conformance.software.name` | `Conformance.software.name` | `name` |  | A name the software is known by | 1..1 | string |  |  |
| `Conformance.software.releaseDate` | `Conformance.software.releaseDate` | `releaseDate` |  | Date this version released | 0..1 | dateTime |  |  |
| `Conformance.software.version` | `Conformance.software.version` | `version` |  | Version covered by this statement | 0..1 | string |  |  |
| `Conformance.status` | `Conformance.status` | `status` |  | draft \| active \| retired | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/conformance-resource-status` |
| `Conformance.text` | `Conformance.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Conformance.url` | `Conformance.url` | `url` |  | Logical uri to reference this statement | 0..1 | uri |  |  |
| `Conformance.version` | `Conformance.version` | `version` |  | Logical id for this version of the statement | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Conformance](/docs/R2/Resources/Conformance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Conformance\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `81`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `247`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CapabilityStatement](/docs/R3/Resources/CapabilityStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/CapabilityStatement\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `426`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `622`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CapabilityStatement](/docs/R4/Resources/CapabilityStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/CapabilityStatement\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1411`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1412`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CapabilityStatement](/docs/R4B/Resources/CapabilityStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/CapabilityStatement\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `939`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1168`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CapabilityStatement](/docs/R5/Resources/CapabilityStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/CapabilityStatement\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Conformance from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Conformance| Relationship | [R3 CapabilityStatement](/docs/R3/Resources/CapabilityStatement.md)| Relationship | [R4 CapabilityStatement](/docs/R4/Resources/CapabilityStatement.md)| Relationship | [R4B CapabilityStatement](/docs/R4B/Resources/CapabilityStatement.md)| Relationship | [R5 CapabilityStatement](/docs/R5/Resources/CapabilityStatement.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Conformance`**| | | | | | | | | 
| **`Conformance.id`**| | | | | | | | | 
| **`Conformance.meta`**| | | | | | | | | 
| **`Conformance.implicitRules`**| | | | | | | | | 
| **`Conformance.language`**| | | | | | | | | 
| **`Conformance.text`**| | | | | | | | | 
| **`Conformance.contained`**| | | | | | | | | 
| **`Conformance.extension`**| | | | | | | | | 
| **`Conformance.modifierExtension`**| | | | | | | | | 
| **`Conformance.url`**| | | | | | | | | 
| **`Conformance.version`**| | | | | | | | | 
| **`Conformance.name`**| | | | | | | | | 
| **`Conformance.status`**| | | | | | | | | 
| **`Conformance.experimental`**| | | | | | | | | 
| **`Conformance.publisher`**| | | | | | | | | 
| **`Conformance.contact`**| | | | | | | | | 
| **`Conformance.contact.id`**| | | | | | | | | 
| **`Conformance.contact.extension`**| | | | | | | | | 
| **`Conformance.contact.modifierExtension`**| | | | | | | | | 
| **`Conformance.contact.name`**| | | | | | | | | 
| **`Conformance.contact.telecom`**| | | | | | | | | 
| **`Conformance.date`**| | | | | | | | | 
| **`Conformance.description`**| | | | | | | | | 
| **`Conformance.requirements`**| _Equivalent_<br/>(161/504)| `CapabilityStatement.purpose`| _Equivalent_<br/>(10747/10748)| `CapabilityStatement.purpose`| _Equivalent_<br/>(22306/22307)| `CapabilityStatement.purpose`| _Equivalent_<br/>(37331/37332)| `CapabilityStatement.purpose`
| **`Conformance.copyright`**| | | | | | | | | 
| **`Conformance.kind`**| | | | | | | | | 
| **`Conformance.software`**| | | | | | | | | 
| **`Conformance.software.id`**| | | | | | | | | 
| **`Conformance.software.extension`**| | | | | | | | | 
| **`Conformance.software.modifierExtension`**| | | | | | | | | 
| **`Conformance.software.name`**| | | | | | | | | 
| **`Conformance.software.version`**| | | | | | | | | 
| **`Conformance.software.releaseDate`**| | | | | | | | | 
| **`Conformance.implementation`**| | | | | | | | | 
| **`Conformance.implementation.id`**| | | | | | | | | 
| **`Conformance.implementation.extension`**| | | | | | | | | 
| **`Conformance.implementation.modifierExtension`**| | | | | | | | | 
| **`Conformance.implementation.description`**| | | | | | | | | 
| **`Conformance.implementation.url`**| | | | | | | | | 
| **`Conformance.fhirVersion`**| | | | | | | | | 
| **`Conformance.acceptUnknown`**| | | | | | | | | 
| **`Conformance.format`**| | | | | | | | | 
| **`Conformance.profile`**| | | | | | | | | 
| **`Conformance.rest`**| | | | | | | | | 
| **`Conformance.rest.id`**| | | | | | | | | 
| **`Conformance.rest.extension`**| | | | | | | | | 
| **`Conformance.rest.modifierExtension`**| | | | | | | | | 
| **`Conformance.rest.mode`**| | | | | | | | | 
| **`Conformance.rest.documentation`**| | | | | | | | | 
| **`Conformance.rest.security`**| | | | | | | | | 
| **`Conformance.rest.security.id`**| | | | | | | | | 
| **`Conformance.rest.security.extension`**| | | | | | | | | 
| **`Conformance.rest.security.modifierExtension`**| | | | | | | | | 
| **`Conformance.rest.security.cors`**| | | | | | | | | 
| **`Conformance.rest.security.service`**| | | | | | | | | 
| **`Conformance.rest.security.description`**| | | | | | | | | 
| **`Conformance.rest.security.certificate`**| | | | | | | | | 
| **`Conformance.rest.security.certificate.id`**| | | | | | | | | 
| **`Conformance.rest.security.certificate.extension`**| | | | | | | | | 
| **`Conformance.rest.security.certificate.modifierExtension`**| | | | | | | | | 
| **`Conformance.rest.security.certificate.type`**| | | | | | | | | 
| **`Conformance.rest.security.certificate.blob`**| | | | | | | | | 
| **`Conformance.rest.resource`**| | | | | | | | | 
| **`Conformance.rest.resource.id`**| | | | | | | | | 
| **`Conformance.rest.resource.extension`**| | | | | | | | | 
| **`Conformance.rest.resource.modifierExtension`**| | | | | | | | | 
| **`Conformance.rest.resource.type`**| | | | | | | | | 
| **`Conformance.rest.resource.profile`**| | | | | | | | | 
| **`Conformance.rest.resource.interaction`**| | | | | | | | | 
| **`Conformance.rest.resource.interaction.id`**| | | | | | | | | 
| **`Conformance.rest.resource.interaction.extension`**| | | | | | | | | 
| **`Conformance.rest.resource.interaction.modifierExtension`**| | | | | | | | | 
| **`Conformance.rest.resource.interaction.code`**| | | | | | | | | 
| **`Conformance.rest.resource.interaction.documentation`**| | | | | | | | | 
| **`Conformance.rest.resource.versioning`**| | | | | | | | | 
| **`Conformance.rest.resource.readHistory`**| | | | | | | | | 
| **`Conformance.rest.resource.updateCreate`**| | | | | | | | | 
| **`Conformance.rest.resource.conditionalCreate`**| | | | | | | | | 
| **`Conformance.rest.resource.conditionalUpdate`**| | | | | | | | | 
| **`Conformance.rest.resource.conditionalDelete`**| | | | | | | | | 
| **`Conformance.rest.resource.searchInclude`**| | | | | | | | | 
| **`Conformance.rest.resource.searchRevInclude`**| | | | | | | | | 
| **`Conformance.rest.resource.searchParam`**| | | | | | | | | 
| **`Conformance.rest.resource.searchParam.id`**| | | | | | | | | 
| **`Conformance.rest.resource.searchParam.extension`**| | | | | | | | | 
| **`Conformance.rest.resource.searchParam.modifierExtension`**| | | | | | | | | 
| **`Conformance.rest.resource.searchParam.name`**| | | | | | | | | 
| **`Conformance.rest.resource.searchParam.definition`**| | | | | | | | | 
| **`Conformance.rest.resource.searchParam.type`**| | | | | | | | | 
| **`Conformance.rest.resource.searchParam.documentation`**| | | | | | | | | 
| **`Conformance.rest.resource.searchParam.target`**| | | | | | | | | 
| **`Conformance.rest.resource.searchParam.modifier`**| | | | | | | | | 
| **`Conformance.rest.resource.searchParam.chain`**| | | | | | | | | 
| **`Conformance.rest.interaction`**| | | | | | | | | 
| **`Conformance.rest.interaction.id`**| | | | | | | | | 
| **`Conformance.rest.interaction.extension`**| | | | | | | | | 
| **`Conformance.rest.interaction.modifierExtension`**| | | | | | | | | 
| **`Conformance.rest.interaction.code`**| | | | | | | | | 
| **`Conformance.rest.interaction.documentation`**| | | | | | | | | 
| **`Conformance.rest.transactionMode`**| | | | | | | | | 
| **`Conformance.rest.searchParam`**| | | | | | | | | 
| **`Conformance.rest.operation`**| | | | | | | | | 
| **`Conformance.rest.operation.id`**| | | | | | | | | 
| **`Conformance.rest.operation.extension`**| | | | | | | | | 
| **`Conformance.rest.operation.modifierExtension`**| | | | | | | | | 
| **`Conformance.rest.operation.name`**| | | | | | | | | 
| **`Conformance.rest.operation.definition`**| | | | | | | | | 
| **`Conformance.rest.compartment`**| | | | | | | | | 
| **`Conformance.messaging`**| | | | | | | | | 
| **`Conformance.messaging.id`**| | | | | | | | | 
| **`Conformance.messaging.extension`**| | | | | | | | | 
| **`Conformance.messaging.modifierExtension`**| | | | | | | | | 
| **`Conformance.messaging.endpoint`**| | | | | | | | | 
| **`Conformance.messaging.endpoint.id`**| | | | | | | | | 
| **`Conformance.messaging.endpoint.extension`**| | | | | | | | | 
| **`Conformance.messaging.endpoint.modifierExtension`**| | | | | | | | | 
| **`Conformance.messaging.endpoint.protocol`**| | | | | | | | | 
| **`Conformance.messaging.endpoint.address`**| | | | | | | | | 
| **`Conformance.messaging.reliableCache`**| | | | | | | | | 
| **`Conformance.messaging.documentation`**| | | | | | | | | 
| **`Conformance.messaging.event`**| | | | | | | | | 
| **`Conformance.messaging.event.id`**| | | | | | | | | 
| **`Conformance.messaging.event.extension`**| | | | | | | | | 
| **`Conformance.messaging.event.modifierExtension`**| | | | | | | | | 
| **`Conformance.messaging.event.code`**| | | | | | | | | 
| **`Conformance.messaging.event.category`**| | | | | | | | | 
| **`Conformance.messaging.event.mode`**| | | | | | | | | 
| **`Conformance.messaging.event.focus`**| | | | | | | | | 
| **`Conformance.messaging.event.request`**| | | | | | | | | 
| **`Conformance.messaging.event.response`**| | | | | | | | | 
| **`Conformance.messaging.event.documentation`**| | | | | | | | | 
| **`Conformance.document`**| | | | | | | | | 
| **`Conformance.document.id`**| | | | | | | | | 
| **`Conformance.document.extension`**| | | | | | | | | 
| **`Conformance.document.modifierExtension`**| | | | | | | | | 
| **`Conformance.document.mode`**| | | | | | | | | 
| **`Conformance.document.documentation`**| | | | | | | | | 
| **`Conformance.document.profile`**| | | | | | | | | 
| *138 of 138 elements used* | | *1 of 144 elements used* <br/>remaining elements:<br/>`CapabilityStatement`, `CapabilityStatement.acceptUnknown`, `CapabilityStatement.contact`, `CapabilityStatement.contained`, `CapabilityStatement.copyright`, `CapabilityStatement.date`, `CapabilityStatement.description`, `CapabilityStatement.document`, `CapabilityStatement.document.documentation`, `CapabilityStatement.document.extension`, `CapabilityStatement.document.id`, `CapabilityStatement.document.mode`, `CapabilityStatement.document.modifierExtension`, `CapabilityStatement.document.profile`, `CapabilityStatement.experimental`, `CapabilityStatement.extension`, `CapabilityStatement.fhirVersion`, `CapabilityStatement.format`, `CapabilityStatement.id`, `CapabilityStatement.implementation`, `CapabilityStatement.implementation.description`, `CapabilityStatement.implementation.extension`, `CapabilityStatement.implementation.id`, `CapabilityStatement.implementation.modifierExtension`, `CapabilityStatement.implementation.url`, `CapabilityStatement.implementationGuide`, `CapabilityStatement.implicitRules`, `CapabilityStatement.instantiates`, `CapabilityStatement.jurisdiction`, `CapabilityStatement.kind`, `CapabilityStatement.language`, `CapabilityStatement.messaging`, `CapabilityStatement.messaging.documentation`, `CapabilityStatement.messaging.endpoint`, `CapabilityStatement.messaging.endpoint.address`, `CapabilityStatement.messaging.endpoint.extension`, `CapabilityStatement.messaging.endpoint.id`, `CapabilityStatement.messaging.endpoint.modifierExtension`, `CapabilityStatement.messaging.endpoint.protocol`, `CapabilityStatement.messaging.event`, `CapabilityStatement.messaging.event.category`, `CapabilityStatement.messaging.event.code`, `CapabilityStatement.messaging.event.documentation`, `CapabilityStatement.messaging.event.extension`, `CapabilityStatement.messaging.event.focus`, `CapabilityStatement.messaging.event.id`, `CapabilityStatement.messaging.event.mode`, `CapabilityStatement.messaging.event.modifierExtension`, `CapabilityStatement.messaging.event.request`, `CapabilityStatement.messaging.event.response`, `CapabilityStatement.messaging.extension`, `CapabilityStatement.messaging.id`, `CapabilityStatement.messaging.modifierExtension`, `CapabilityStatement.messaging.reliableCache`, `CapabilityStatement.messaging.supportedMessage`, `CapabilityStatement.messaging.supportedMessage.definition`, `CapabilityStatement.messaging.supportedMessage.extension`, `CapabilityStatement.messaging.supportedMessage.id`, `CapabilityStatement.messaging.supportedMessage.mode`, `CapabilityStatement.messaging.supportedMessage.modifierExtension`, `CapabilityStatement.meta`, `CapabilityStatement.modifierExtension`, `CapabilityStatement.name`, `CapabilityStatement.patchFormat`, `CapabilityStatement.profile`, `CapabilityStatement.publisher`, `CapabilityStatement.rest`, `CapabilityStatement.rest.compartment`, `CapabilityStatement.rest.documentation`, `CapabilityStatement.rest.extension`, `CapabilityStatement.rest.id`, `CapabilityStatement.rest.interaction`, `CapabilityStatement.rest.interaction.code`, `CapabilityStatement.rest.interaction.documentation`, `CapabilityStatement.rest.interaction.extension`, `CapabilityStatement.rest.interaction.id`, `CapabilityStatement.rest.interaction.modifierExtension`, `CapabilityStatement.rest.mode`, `CapabilityStatement.rest.modifierExtension`, `CapabilityStatement.rest.operation`, `CapabilityStatement.rest.operation.definition`, `CapabilityStatement.rest.operation.extension`, `CapabilityStatement.rest.operation.id`, `CapabilityStatement.rest.operation.modifierExtension`, `CapabilityStatement.rest.operation.name`, `CapabilityStatement.rest.resource`, `CapabilityStatement.rest.resource.conditionalCreate`, `CapabilityStatement.rest.resource.conditionalDelete`, `CapabilityStatement.rest.resource.conditionalRead`, `CapabilityStatement.rest.resource.conditionalUpdate`, `CapabilityStatement.rest.resource.documentation`, `CapabilityStatement.rest.resource.extension`, `CapabilityStatement.rest.resource.id`, `CapabilityStatement.rest.resource.interaction`, `CapabilityStatement.rest.resource.interaction.code`, `CapabilityStatement.rest.resource.interaction.documentation`, `CapabilityStatement.rest.resource.interaction.extension`, `CapabilityStatement.rest.resource.interaction.id`, `CapabilityStatement.rest.resource.interaction.modifierExtension`, `CapabilityStatement.rest.resource.modifierExtension`, `CapabilityStatement.rest.resource.profile`, `CapabilityStatement.rest.resource.readHistory`, `CapabilityStatement.rest.resource.referencePolicy`, `CapabilityStatement.rest.resource.searchInclude`, `CapabilityStatement.rest.resource.searchParam`, `CapabilityStatement.rest.resource.searchParam.definition`, `CapabilityStatement.rest.resource.searchParam.documentation`, `CapabilityStatement.rest.resource.searchParam.extension`, `CapabilityStatement.rest.resource.searchParam.id`, `CapabilityStatement.rest.resource.searchParam.modifierExtension`, `CapabilityStatement.rest.resource.searchParam.name`, `CapabilityStatement.rest.resource.searchParam.type`, `CapabilityStatement.rest.resource.searchRevInclude`, `CapabilityStatement.rest.resource.type`, `CapabilityStatement.rest.resource.updateCreate`, `CapabilityStatement.rest.resource.versioning`, `CapabilityStatement.rest.searchParam`, `CapabilityStatement.rest.security`, `CapabilityStatement.rest.security.certificate`, `CapabilityStatement.rest.security.certificate.blob`, `CapabilityStatement.rest.security.certificate.extension`, `CapabilityStatement.rest.security.certificate.id`, `CapabilityStatement.rest.security.certificate.modifierExtension`, `CapabilityStatement.rest.security.certificate.type`, `CapabilityStatement.rest.security.cors`, `CapabilityStatement.rest.security.description`, `CapabilityStatement.rest.security.extension`, `CapabilityStatement.rest.security.id`, `CapabilityStatement.rest.security.modifierExtension`, `CapabilityStatement.rest.security.service`, `CapabilityStatement.software`, `CapabilityStatement.software.extension`, `CapabilityStatement.software.id`, `CapabilityStatement.software.modifierExtension`, `CapabilityStatement.software.name`, `CapabilityStatement.software.releaseDate`, `CapabilityStatement.software.version`, `CapabilityStatement.status`, `CapabilityStatement.text`, `CapabilityStatement.title`, `CapabilityStatement.url`, `CapabilityStatement.useContext`, `CapabilityStatement.version`| | *1 of 130 elements used* <br/>remaining elements:<br/>`CapabilityStatement`, `CapabilityStatement.contact`, `CapabilityStatement.contained`, `CapabilityStatement.copyright`, `CapabilityStatement.date`, `CapabilityStatement.description`, `CapabilityStatement.document`, `CapabilityStatement.document.documentation`, `CapabilityStatement.document.extension`, `CapabilityStatement.document.id`, `CapabilityStatement.document.mode`, `CapabilityStatement.document.modifierExtension`, `CapabilityStatement.document.profile`, `CapabilityStatement.experimental`, `CapabilityStatement.extension`, `CapabilityStatement.fhirVersion`, `CapabilityStatement.format`, `CapabilityStatement.id`, `CapabilityStatement.implementation`, `CapabilityStatement.implementation.custodian`, `CapabilityStatement.implementation.description`, `CapabilityStatement.implementation.extension`, `CapabilityStatement.implementation.id`, `CapabilityStatement.implementation.modifierExtension`, `CapabilityStatement.implementation.url`, `CapabilityStatement.implementationGuide`, `CapabilityStatement.implicitRules`, `CapabilityStatement.imports`, `CapabilityStatement.instantiates`, `CapabilityStatement.jurisdiction`, `CapabilityStatement.kind`, `CapabilityStatement.language`, `CapabilityStatement.messaging`, `CapabilityStatement.messaging.documentation`, `CapabilityStatement.messaging.endpoint`, `CapabilityStatement.messaging.endpoint.address`, `CapabilityStatement.messaging.endpoint.extension`, `CapabilityStatement.messaging.endpoint.id`, `CapabilityStatement.messaging.endpoint.modifierExtension`, `CapabilityStatement.messaging.endpoint.protocol`, `CapabilityStatement.messaging.extension`, `CapabilityStatement.messaging.id`, `CapabilityStatement.messaging.modifierExtension`, `CapabilityStatement.messaging.reliableCache`, `CapabilityStatement.messaging.supportedMessage`, `CapabilityStatement.messaging.supportedMessage.definition`, `CapabilityStatement.messaging.supportedMessage.extension`, `CapabilityStatement.messaging.supportedMessage.id`, `CapabilityStatement.messaging.supportedMessage.mode`, `CapabilityStatement.messaging.supportedMessage.modifierExtension`, `CapabilityStatement.meta`, `CapabilityStatement.modifierExtension`, `CapabilityStatement.name`, `CapabilityStatement.patchFormat`, `CapabilityStatement.publisher`, `CapabilityStatement.rest`, `CapabilityStatement.rest.compartment`, `CapabilityStatement.rest.documentation`, `CapabilityStatement.rest.extension`, `CapabilityStatement.rest.id`, `CapabilityStatement.rest.interaction`, `CapabilityStatement.rest.interaction.code`, `CapabilityStatement.rest.interaction.documentation`, `CapabilityStatement.rest.interaction.extension`, `CapabilityStatement.rest.interaction.id`, `CapabilityStatement.rest.interaction.modifierExtension`, `CapabilityStatement.rest.mode`, `CapabilityStatement.rest.modifierExtension`, `CapabilityStatement.rest.operation`, `CapabilityStatement.rest.resource`, `CapabilityStatement.rest.resource.conditionalCreate`, `CapabilityStatement.rest.resource.conditionalDelete`, `CapabilityStatement.rest.resource.conditionalRead`, `CapabilityStatement.rest.resource.conditionalUpdate`, `CapabilityStatement.rest.resource.documentation`, `CapabilityStatement.rest.resource.extension`, `CapabilityStatement.rest.resource.id`, `CapabilityStatement.rest.resource.interaction`, `CapabilityStatement.rest.resource.interaction.code`, `CapabilityStatement.rest.resource.interaction.documentation`, `CapabilityStatement.rest.resource.interaction.extension`, `CapabilityStatement.rest.resource.interaction.id`, `CapabilityStatement.rest.resource.interaction.modifierExtension`, `CapabilityStatement.rest.resource.modifierExtension`, `CapabilityStatement.rest.resource.operation`, `CapabilityStatement.rest.resource.operation.definition`, `CapabilityStatement.rest.resource.operation.documentation`, `CapabilityStatement.rest.resource.operation.extension`, `CapabilityStatement.rest.resource.operation.id`, `CapabilityStatement.rest.resource.operation.modifierExtension`, `CapabilityStatement.rest.resource.operation.name`, `CapabilityStatement.rest.resource.profile`, `CapabilityStatement.rest.resource.readHistory`, `CapabilityStatement.rest.resource.referencePolicy`, `CapabilityStatement.rest.resource.searchInclude`, `CapabilityStatement.rest.resource.searchParam`, `CapabilityStatement.rest.resource.searchParam.definition`, `CapabilityStatement.rest.resource.searchParam.documentation`, `CapabilityStatement.rest.resource.searchParam.extension`, `CapabilityStatement.rest.resource.searchParam.id`, `CapabilityStatement.rest.resource.searchParam.modifierExtension`, `CapabilityStatement.rest.resource.searchParam.name`, `CapabilityStatement.rest.resource.searchParam.type`, `CapabilityStatement.rest.resource.searchRevInclude`, `CapabilityStatement.rest.resource.supportedProfile`, `CapabilityStatement.rest.resource.type`, `CapabilityStatement.rest.resource.updateCreate`, `CapabilityStatement.rest.resource.versioning`, `CapabilityStatement.rest.searchParam`, `CapabilityStatement.rest.security`, `CapabilityStatement.rest.security.cors`, `CapabilityStatement.rest.security.description`, `CapabilityStatement.rest.security.extension`, `CapabilityStatement.rest.security.id`, `CapabilityStatement.rest.security.modifierExtension`, `CapabilityStatement.rest.security.service`, `CapabilityStatement.software`, `CapabilityStatement.software.extension`, `CapabilityStatement.software.id`, `CapabilityStatement.software.modifierExtension`, `CapabilityStatement.software.name`, `CapabilityStatement.software.releaseDate`, `CapabilityStatement.software.version`, `CapabilityStatement.status`, `CapabilityStatement.text`, `CapabilityStatement.title`, `CapabilityStatement.url`, `CapabilityStatement.useContext`, `CapabilityStatement.version`| | *1 of 130 elements used* <br/>remaining elements:<br/>`CapabilityStatement`, `CapabilityStatement.contact`, `CapabilityStatement.contained`, `CapabilityStatement.copyright`, `CapabilityStatement.date`, `CapabilityStatement.description`, `CapabilityStatement.document`, `CapabilityStatement.document.documentation`, `CapabilityStatement.document.extension`, `CapabilityStatement.document.id`, `CapabilityStatement.document.mode`, `CapabilityStatement.document.modifierExtension`, `CapabilityStatement.document.profile`, `CapabilityStatement.experimental`, `CapabilityStatement.extension`, `CapabilityStatement.fhirVersion`, `CapabilityStatement.format`, `CapabilityStatement.id`, `CapabilityStatement.implementation`, `CapabilityStatement.implementation.custodian`, `CapabilityStatement.implementation.description`, `CapabilityStatement.implementation.extension`, `CapabilityStatement.implementation.id`, `CapabilityStatement.implementation.modifierExtension`, `CapabilityStatement.implementation.url`, `CapabilityStatement.implementationGuide`, `CapabilityStatement.implicitRules`, `CapabilityStatement.imports`, `CapabilityStatement.instantiates`, `CapabilityStatement.jurisdiction`, `CapabilityStatement.kind`, `CapabilityStatement.language`, `CapabilityStatement.messaging`, `CapabilityStatement.messaging.documentation`, `CapabilityStatement.messaging.endpoint`, `CapabilityStatement.messaging.endpoint.address`, `CapabilityStatement.messaging.endpoint.extension`, `CapabilityStatement.messaging.endpoint.id`, `CapabilityStatement.messaging.endpoint.modifierExtension`, `CapabilityStatement.messaging.endpoint.protocol`, `CapabilityStatement.messaging.extension`, `CapabilityStatement.messaging.id`, `CapabilityStatement.messaging.modifierExtension`, `CapabilityStatement.messaging.reliableCache`, `CapabilityStatement.messaging.supportedMessage`, `CapabilityStatement.messaging.supportedMessage.definition`, `CapabilityStatement.messaging.supportedMessage.extension`, `CapabilityStatement.messaging.supportedMessage.id`, `CapabilityStatement.messaging.supportedMessage.mode`, `CapabilityStatement.messaging.supportedMessage.modifierExtension`, `CapabilityStatement.meta`, `CapabilityStatement.modifierExtension`, `CapabilityStatement.name`, `CapabilityStatement.patchFormat`, `CapabilityStatement.publisher`, `CapabilityStatement.rest`, `CapabilityStatement.rest.compartment`, `CapabilityStatement.rest.documentation`, `CapabilityStatement.rest.extension`, `CapabilityStatement.rest.id`, `CapabilityStatement.rest.interaction`, `CapabilityStatement.rest.interaction.code`, `CapabilityStatement.rest.interaction.documentation`, `CapabilityStatement.rest.interaction.extension`, `CapabilityStatement.rest.interaction.id`, `CapabilityStatement.rest.interaction.modifierExtension`, `CapabilityStatement.rest.mode`, `CapabilityStatement.rest.modifierExtension`, `CapabilityStatement.rest.operation`, `CapabilityStatement.rest.resource`, `CapabilityStatement.rest.resource.conditionalCreate`, `CapabilityStatement.rest.resource.conditionalDelete`, `CapabilityStatement.rest.resource.conditionalRead`, `CapabilityStatement.rest.resource.conditionalUpdate`, `CapabilityStatement.rest.resource.documentation`, `CapabilityStatement.rest.resource.extension`, `CapabilityStatement.rest.resource.id`, `CapabilityStatement.rest.resource.interaction`, `CapabilityStatement.rest.resource.interaction.code`, `CapabilityStatement.rest.resource.interaction.documentation`, `CapabilityStatement.rest.resource.interaction.extension`, `CapabilityStatement.rest.resource.interaction.id`, `CapabilityStatement.rest.resource.interaction.modifierExtension`, `CapabilityStatement.rest.resource.modifierExtension`, `CapabilityStatement.rest.resource.operation`, `CapabilityStatement.rest.resource.operation.definition`, `CapabilityStatement.rest.resource.operation.documentation`, `CapabilityStatement.rest.resource.operation.extension`, `CapabilityStatement.rest.resource.operation.id`, `CapabilityStatement.rest.resource.operation.modifierExtension`, `CapabilityStatement.rest.resource.operation.name`, `CapabilityStatement.rest.resource.profile`, `CapabilityStatement.rest.resource.readHistory`, `CapabilityStatement.rest.resource.referencePolicy`, `CapabilityStatement.rest.resource.searchInclude`, `CapabilityStatement.rest.resource.searchParam`, `CapabilityStatement.rest.resource.searchParam.definition`, `CapabilityStatement.rest.resource.searchParam.documentation`, `CapabilityStatement.rest.resource.searchParam.extension`, `CapabilityStatement.rest.resource.searchParam.id`, `CapabilityStatement.rest.resource.searchParam.modifierExtension`, `CapabilityStatement.rest.resource.searchParam.name`, `CapabilityStatement.rest.resource.searchParam.type`, `CapabilityStatement.rest.resource.searchRevInclude`, `CapabilityStatement.rest.resource.supportedProfile`, `CapabilityStatement.rest.resource.type`, `CapabilityStatement.rest.resource.updateCreate`, `CapabilityStatement.rest.resource.versioning`, `CapabilityStatement.rest.searchParam`, `CapabilityStatement.rest.security`, `CapabilityStatement.rest.security.cors`, `CapabilityStatement.rest.security.description`, `CapabilityStatement.rest.security.extension`, `CapabilityStatement.rest.security.id`, `CapabilityStatement.rest.security.modifierExtension`, `CapabilityStatement.rest.security.service`, `CapabilityStatement.software`, `CapabilityStatement.software.extension`, `CapabilityStatement.software.id`, `CapabilityStatement.software.modifierExtension`, `CapabilityStatement.software.name`, `CapabilityStatement.software.releaseDate`, `CapabilityStatement.software.version`, `CapabilityStatement.status`, `CapabilityStatement.text`, `CapabilityStatement.title`, `CapabilityStatement.url`, `CapabilityStatement.useContext`, `CapabilityStatement.version`| | *1 of 135 elements used* <br/>remaining elements:<br/>`CapabilityStatement`, `CapabilityStatement.acceptLanguage`, `CapabilityStatement.contact`, `CapabilityStatement.contained`, `CapabilityStatement.copyright`, `CapabilityStatement.copyrightLabel`, `CapabilityStatement.date`, `CapabilityStatement.description`, `CapabilityStatement.document`, `CapabilityStatement.document.documentation`, `CapabilityStatement.document.extension`, `CapabilityStatement.document.id`, `CapabilityStatement.document.mode`, `CapabilityStatement.document.modifierExtension`, `CapabilityStatement.document.profile`, `CapabilityStatement.experimental`, `CapabilityStatement.extension`, `CapabilityStatement.fhirVersion`, `CapabilityStatement.format`, `CapabilityStatement.id`, `CapabilityStatement.identifier`, `CapabilityStatement.implementation`, `CapabilityStatement.implementation.custodian`, `CapabilityStatement.implementation.description`, `CapabilityStatement.implementation.extension`, `CapabilityStatement.implementation.id`, `CapabilityStatement.implementation.modifierExtension`, `CapabilityStatement.implementation.url`, `CapabilityStatement.implementationGuide`, `CapabilityStatement.implicitRules`, `CapabilityStatement.imports`, `CapabilityStatement.instantiates`, `CapabilityStatement.jurisdiction`, `CapabilityStatement.kind`, `CapabilityStatement.language`, `CapabilityStatement.messaging`, `CapabilityStatement.messaging.documentation`, `CapabilityStatement.messaging.endpoint`, `CapabilityStatement.messaging.endpoint.address`, `CapabilityStatement.messaging.endpoint.extension`, `CapabilityStatement.messaging.endpoint.id`, `CapabilityStatement.messaging.endpoint.modifierExtension`, `CapabilityStatement.messaging.endpoint.protocol`, `CapabilityStatement.messaging.extension`, `CapabilityStatement.messaging.id`, `CapabilityStatement.messaging.modifierExtension`, `CapabilityStatement.messaging.reliableCache`, `CapabilityStatement.messaging.supportedMessage`, `CapabilityStatement.messaging.supportedMessage.definition`, `CapabilityStatement.messaging.supportedMessage.extension`, `CapabilityStatement.messaging.supportedMessage.id`, `CapabilityStatement.messaging.supportedMessage.mode`, `CapabilityStatement.messaging.supportedMessage.modifierExtension`, `CapabilityStatement.meta`, `CapabilityStatement.modifierExtension`, `CapabilityStatement.name`, `CapabilityStatement.patchFormat`, `CapabilityStatement.publisher`, `CapabilityStatement.rest`, `CapabilityStatement.rest.compartment`, `CapabilityStatement.rest.documentation`, `CapabilityStatement.rest.extension`, `CapabilityStatement.rest.id`, `CapabilityStatement.rest.interaction`, `CapabilityStatement.rest.interaction.code`, `CapabilityStatement.rest.interaction.documentation`, `CapabilityStatement.rest.interaction.extension`, `CapabilityStatement.rest.interaction.id`, `CapabilityStatement.rest.interaction.modifierExtension`, `CapabilityStatement.rest.mode`, `CapabilityStatement.rest.modifierExtension`, `CapabilityStatement.rest.operation`, `CapabilityStatement.rest.resource`, `CapabilityStatement.rest.resource.conditionalCreate`, `CapabilityStatement.rest.resource.conditionalDelete`, `CapabilityStatement.rest.resource.conditionalPatch`, `CapabilityStatement.rest.resource.conditionalRead`, `CapabilityStatement.rest.resource.conditionalUpdate`, `CapabilityStatement.rest.resource.documentation`, `CapabilityStatement.rest.resource.extension`, `CapabilityStatement.rest.resource.id`, `CapabilityStatement.rest.resource.interaction`, `CapabilityStatement.rest.resource.interaction.code`, `CapabilityStatement.rest.resource.interaction.documentation`, `CapabilityStatement.rest.resource.interaction.extension`, `CapabilityStatement.rest.resource.interaction.id`, `CapabilityStatement.rest.resource.interaction.modifierExtension`, `CapabilityStatement.rest.resource.modifierExtension`, `CapabilityStatement.rest.resource.operation`, `CapabilityStatement.rest.resource.operation.definition`, `CapabilityStatement.rest.resource.operation.documentation`, `CapabilityStatement.rest.resource.operation.extension`, `CapabilityStatement.rest.resource.operation.id`, `CapabilityStatement.rest.resource.operation.modifierExtension`, `CapabilityStatement.rest.resource.operation.name`, `CapabilityStatement.rest.resource.profile`, `CapabilityStatement.rest.resource.readHistory`, `CapabilityStatement.rest.resource.referencePolicy`, `CapabilityStatement.rest.resource.searchInclude`, `CapabilityStatement.rest.resource.searchParam`, `CapabilityStatement.rest.resource.searchParam.definition`, `CapabilityStatement.rest.resource.searchParam.documentation`, `CapabilityStatement.rest.resource.searchParam.extension`, `CapabilityStatement.rest.resource.searchParam.id`, `CapabilityStatement.rest.resource.searchParam.modifierExtension`, `CapabilityStatement.rest.resource.searchParam.name`, `CapabilityStatement.rest.resource.searchParam.type`, `CapabilityStatement.rest.resource.searchRevInclude`, `CapabilityStatement.rest.resource.supportedProfile`, `CapabilityStatement.rest.resource.type`, `CapabilityStatement.rest.resource.updateCreate`, `CapabilityStatement.rest.resource.versioning`, `CapabilityStatement.rest.searchParam`, `CapabilityStatement.rest.security`, `CapabilityStatement.rest.security.cors`, `CapabilityStatement.rest.security.description`, `CapabilityStatement.rest.security.extension`, `CapabilityStatement.rest.security.id`, `CapabilityStatement.rest.security.modifierExtension`, `CapabilityStatement.rest.security.service`, `CapabilityStatement.software`, `CapabilityStatement.software.extension`, `CapabilityStatement.software.id`, `CapabilityStatement.software.modifierExtension`, `CapabilityStatement.software.name`, `CapabilityStatement.software.releaseDate`, `CapabilityStatement.software.version`, `CapabilityStatement.status`, `CapabilityStatement.text`, `CapabilityStatement.title`, `CapabilityStatement.url`, `CapabilityStatement.useContext`, `CapabilityStatement.version`, `CapabilityStatement.versionAlgorithm[x]`

