### Lookup for FHIR R2 SupplyRequest for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| SupplyRequest.id | UseElementSameName | SupplyRequest.id |
| SupplyRequest.meta | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyRequest.meta |
| SupplyRequest.implicitRules | UseElementSameName | SupplyRequest.implicitRules |
| SupplyRequest.language | UseElementSameName | SupplyRequest.language |
| SupplyRequest.text | UseElementSameName | SupplyRequest.text |
| SupplyRequest.contained | UseElementSameName | SupplyRequest.contained |
| SupplyRequest.extension | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyRequest.extension |
| SupplyRequest.modifierExtension | UseElementSameName | SupplyRequest.modifierExtension |
| SupplyRequest.patient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyRequest.patient |
| SupplyRequest.source | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyRequest.source |
| SupplyRequest.date | UseElementRenamed | SupplyRequest.authoredOn |
| SupplyRequest.identifier | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyRequest.identifier |
| SupplyRequest.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyRequest.status |
| SupplyRequest.kind | UseElementRenamed | SupplyRequest.category |
| SupplyRequest.orderedItem | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyRequest.orderedItem |
| SupplyRequest.supplier | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyRequest.supplier |
| SupplyRequest.reason[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyRequest.reason |
| SupplyRequest.when | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyRequest.when |
| SupplyRequest.when.id | UseExtensionFromAncestor | - |
| SupplyRequest.when.extension | UseExtensionFromAncestor | - |
| SupplyRequest.when.modifierExtension | UseExtensionFromAncestor | - |
| SupplyRequest.when.code | UseExtensionFromAncestor | - |
| SupplyRequest.when.schedule | UseExtensionFromAncestor | - |
