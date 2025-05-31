### Lookup for FHIR R2 Subscription for use in FHIR R5

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
| Subscription.criteria | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Subscription.criteria |
| Subscription.contact | UseElementSameName | Subscription.contact |
| Subscription.reason | UseElementSameName | Subscription.reason |
| Subscription.status | UseElementSameName | Subscription.status |
| Subscription.error | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Subscription.error |
| Subscription.channel | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Subscription.channel |
| Subscription.channel.id | UseExtensionFromAncestor | - |
| Subscription.channel.extension | UseExtensionFromAncestor | - |
| Subscription.channel.modifierExtension | UseExtensionFromAncestor | - |
| Subscription.channel.type | UseExtensionFromAncestor | - |
| Subscription.channel.endpoint | UseExtensionFromAncestor | - |
| Subscription.channel.payload | UseExtensionFromAncestor | - |
| Subscription.channel.header | UseExtensionFromAncestor | - |
| Subscription.end | UseElementSameName | Subscription.end |
| Subscription.tag | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Subscription.tag |
