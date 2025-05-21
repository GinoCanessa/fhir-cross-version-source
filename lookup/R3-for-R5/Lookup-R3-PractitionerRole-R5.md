### Lookup for FHIR R3 PractitionerRole for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| PractitionerRole.id | UseElementSameName | PractitionerRole.id |
| PractitionerRole.meta | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-PractitionerRole.meta |
| PractitionerRole.implicitRules | UseElementSameName | PractitionerRole.implicitRules |
| PractitionerRole.language | UseElementSameName | PractitionerRole.language |
| PractitionerRole.text | UseElementSameName | PractitionerRole.text |
| PractitionerRole.contained | UseElementSameName | PractitionerRole.contained |
| PractitionerRole.extension | UseElementSameName | PractitionerRole.extension |
| PractitionerRole.modifierExtension | UseElementSameName | PractitionerRole.modifierExtension |
| PractitionerRole.identifier | UseElementSameName | PractitionerRole.identifier |
| PractitionerRole.active | UseElementSameName | PractitionerRole.active |
| PractitionerRole.period | UseElementSameName | PractitionerRole.period |
| PractitionerRole.practitioner | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-PractitionerRole.practitioner |
| PractitionerRole.organization | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-PractitionerRole.organization |
| PractitionerRole.code | UseElementSameName | PractitionerRole.code |
| PractitionerRole.specialty | UseElementSameName | PractitionerRole.specialty |
| PractitionerRole.location | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-PractitionerRole.location |
| PractitionerRole.healthcareService | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-PractitionerRole.healthcareService |
| PractitionerRole.telecom | UseElementRenamed | PractitionerRole.contact |
| PractitionerRole.availableTime | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-PractitionerRole.availableTime |
| PractitionerRole.availableTime.id | UseExtensionFromAncestor | - |
| PractitionerRole.availableTime.extension | UseExtensionFromAncestor | - |
| PractitionerRole.availableTime.modifierExtension | UseExtensionFromAncestor | - |
| PractitionerRole.availableTime.daysOfWeek | UseExtensionFromAncestor | - |
| PractitionerRole.availableTime.allDay | UseExtensionFromAncestor | - |
| PractitionerRole.availableTime.availableStartTime | UseExtensionFromAncestor | - |
| PractitionerRole.availableTime.availableEndTime | UseExtensionFromAncestor | - |
| PractitionerRole.notAvailable | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-PractitionerRole.notAvailable |
| PractitionerRole.notAvailable.id | UseExtensionFromAncestor | - |
| PractitionerRole.notAvailable.extension | UseExtensionFromAncestor | - |
| PractitionerRole.notAvailable.modifierExtension | UseExtensionFromAncestor | - |
| PractitionerRole.notAvailable.description | UseExtensionFromAncestor | - |
| PractitionerRole.notAvailable.during | UseExtensionFromAncestor | - |
| PractitionerRole.availabilityExceptions | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-PractitionerRole.availabilityExceptions |
| PractitionerRole.endpoint | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-PractitionerRole.endpoint |
