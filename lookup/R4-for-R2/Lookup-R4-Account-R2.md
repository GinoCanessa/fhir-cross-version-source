### Lookup for FHIR R4 Account for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Account.id | UseElementSameName | Account.id |
| Account.meta | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Account.meta |
| Account.implicitRules | UseElementSameName | Account.implicitRules |
| Account.language | UseElementSameName | Account.language |
| Account.text | UseElementSameName | Account.text |
| Account.contained | UseElementSameName | Account.contained |
| Account.extension | UseElementSameName | Account.extension |
| Account.modifierExtension | UseElementSameName | Account.modifierExtension |
| Account.identifier | UseElementSameName | Account.identifier |
| Account.status | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Account.status |
| Account.type | UseElementSameName | Account.type |
| Account.name | UseElementSameName | Account.name |
| Account.subject | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Account.subject |
| Account.servicePeriod | UseElementRenamed | Account.activePeriod |
| Account.coverage | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Account.coverage |
| Account.coverage.id | UseExtensionFromAncestor | - |
| Account.coverage.extension | UseExtensionFromAncestor | - |
| Account.coverage.modifierExtension | UseExtensionFromAncestor | - |
| Account.coverage.coverage | UseExtensionFromAncestor | - |
| Account.coverage.priority | UseExtensionFromAncestor | - |
| Account.owner | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Account.owner |
| Account.description | UseElementSameName | Account.description |
| Account.guarantor | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Account.guarantor |
| Account.guarantor.id | UseExtensionFromAncestor | - |
| Account.guarantor.extension | UseExtensionFromAncestor | - |
| Account.guarantor.modifierExtension | UseExtensionFromAncestor | - |
| Account.guarantor.party | UseExtensionFromAncestor | - |
| Account.guarantor.onHold | UseExtensionFromAncestor | - |
| Account.guarantor.period | UseExtensionFromAncestor | - |
| Account.partOf | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Account.partOf |
