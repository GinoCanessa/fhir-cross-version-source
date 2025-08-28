### Lookup for [FHIR R4](https://hl7.org/fhir/R4/) [DocumentReference](https://hl7.org/fhir/R4/DocumentReference.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R4) | Usage | Target |
| -------------- | ----- | ------ |
| [DocumentReference.meta](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.meta](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.implicitRules](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.implicitRules](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.language](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.language](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.text](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.text](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.contained](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.contained](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.masterIdentifier](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementRenamed` | [DocumentReference.identifier](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.identifier](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.identifier](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.status](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.status](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.docStatus](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.docStatus](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.type](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.type](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.category](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.category](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.subject](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.0/StructureDefinition/extension-DocumentReference.subject](StructureDefinition-ext-R4-DocumentReference.subject.html) |
| [DocumentReference.date](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.date](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.author](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.author](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.authenticator](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.0/StructureDefinition/extension-DocumentReference.authenticator](StructureDefinition-ext-R4-DocumentReference.authenticator.html) |
| [DocumentReference.custodian](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.custodian](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.relatesTo](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.relatesTo](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.relatesTo.code](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.0/StructureDefinition/extension-DocumentReference.relatesTo.code](StructureDefinition-ext-R4-DocumentReference.re.code.html) |
| [DocumentReference.relatesTo.target](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.relatesTo.target](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.description](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.description](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.securityLabel](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.securityLabel](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.content](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.content](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.content.attachment](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseElementSameName` | [DocumentReference.content.attachment](https://hl7.org/fhir/R5/DocumentReference.html#resource) |
| [DocumentReference.content.format](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.0/StructureDefinition/extension-DocumentReference.content.format](StructureDefinition-ext-R4-DocumentReference.co.format.html) |
| [DocumentReference.context](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.0/StructureDefinition/extension-DocumentReference.context](StructureDefinition-ext-R4-DocumentReference.context.html) |
| [DocumentReference.context.encounter](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseExtensionFromAncestor` | - |
| [DocumentReference.context.event](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseExtensionFromAncestor` | - |
| [DocumentReference.context.period](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseExtensionFromAncestor` | - |
| [DocumentReference.context.facilityType](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseExtensionFromAncestor` | - |
| [DocumentReference.context.practiceSetting](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseExtensionFromAncestor` | - |
| [DocumentReference.context.sourcePatientInfo](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseExtensionFromAncestor` | - |
| [DocumentReference.context.related](https://hl7.org/fhir/R4/DocumentReference.html#resource) | `UseExtensionFromAncestor` | - |
