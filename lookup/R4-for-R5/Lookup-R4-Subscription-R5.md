### Lookup for FHIR R4 Subscription for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Subscription.id | UseElementSameName | Subscription.id |
| Subscription.meta | UseElementSameName | Subscription.meta |
| Subscription.implicitRules | UseElementSameName | Subscription.implicitRules |
| Subscription.language | UseElementSameName | Subscription.language |
| Subscription.text | UseElementSameName | Subscription.text |
| Subscription.contained | UseElementSameName | Subscription.contained |
| Subscription.extension | UseElementSameName | Subscription.extension |
| Subscription.modifierExtension | UseElementSameName | Subscription.modifierExtension |
| Subscription.status | UseElementSameName | Subscription.status |
| Subscription.contact | UseElementSameName | Subscription.contact |
| Subscription.end | UseElementSameName | Subscription.end |
| Subscription.reason | UseElementSameName | Subscription.reason |
| Subscription.criteria | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Subscription.criteria |
| Subscription.error | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Subscription.error |
| Subscription.channel | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Subscription.channel |
| Subscription.channel.id | UseExtensionFromAncestor | - |
| Subscription.channel.extension | UseExtensionFromAncestor | - |
| Subscription.channel.modifierExtension | UseExtensionFromAncestor | - |
| Subscription.channel.type | UseExtensionFromAncestor | - |
| Subscription.channel.endpoint | UseExtensionFromAncestor | - |
| Subscription.channel.payload | UseExtensionFromAncestor | - |
| Subscription.channel.header | UseExtensionFromAncestor | - |
