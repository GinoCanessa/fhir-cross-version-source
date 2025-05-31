### Lookup for FHIR R2 OrderResponse for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| OrderResponse.id | UseElementRenamed | Task.id |
| OrderResponse.meta | UseElementRenamed | Task.meta |
| OrderResponse.implicitRules | UseElementRenamed | Task.implicitRules |
| OrderResponse.language | UseElementRenamed | Task.language |
| OrderResponse.text | UseElementRenamed | Task.text |
| OrderResponse.contained | UseElementRenamed | Task.contained |
| OrderResponse.extension | UseElementRenamed | Task.extension |
| OrderResponse.modifierExtension | UseElementRenamed | Task.modifierExtension |
| OrderResponse.identifier | UseElementRenamed | Task.identifier |
| OrderResponse.request | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-OrderResponse.request |
| OrderResponse.date | UseElementRenamed | Task.authoredOn |
| OrderResponse.who | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-OrderResponse.who |
| OrderResponse.orderStatus | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-OrderResponse.orderStatus |
| OrderResponse.description | UseElementRenamed | Task.description |
| OrderResponse.fulfillment | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-OrderResponse.fulfillment |
