### Lookup for FHIR R4B Account for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Account.id | UseElementSameName | Account.id |
| Account.meta | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Account.meta |
| Account.implicitRules | UseElementSameName | Account.implicitRules |
| Account.language | UseElementSameName | Account.language |
| Account.text | UseElementSameName | Account.text |
| Account.contained | UseElementSameName | Account.contained |
| Account.extension | UseElementSameName | Account.extension |
| Account.modifierExtension | UseElementSameName | Account.modifierExtension |
| Account.identifier | UseElementSameName | Account.identifier |
| Account.status | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Account.status |
| Account.type | UseElementSameName | Account.type |
| Account.name | UseElementSameName | Account.name |
| Account.subject | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Account.subject |
| Account.servicePeriod | UseElementRenamed | Account.period |
| Account.coverage | UseElementSameName | Account.coverage |
| Account.coverage.id | UseElementSameName | Account.coverage.id |
| Account.coverage.extension | UseElementSameName | Account.coverage.extension |
| Account.coverage.modifierExtension | UseElementSameName | Account.coverage.modifierExtension |
| Account.coverage.coverage | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Account.coverage.coverage |
| Account.coverage.priority | UseElementSameName | Account.coverage.priority |
| Account.owner | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Account.owner |
| Account.description | UseElementSameName | Account.description |
| Account.guarantor | UseElementSameName | Account.guarantor |
| Account.guarantor.id | UseElementSameName | Account.guarantor.id |
| Account.guarantor.extension | UseElementSameName | Account.guarantor.extension |
| Account.guarantor.modifierExtension | UseElementSameName | Account.guarantor.modifierExtension |
| Account.guarantor.party | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Account.guarantor.party |
| Account.guarantor.onHold | UseElementSameName | Account.guarantor.onHold |
| Account.guarantor.period | UseElementSameName | Account.guarantor.period |
| Account.partOf | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Account.partOf |
