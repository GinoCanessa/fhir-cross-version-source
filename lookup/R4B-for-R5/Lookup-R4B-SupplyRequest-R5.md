### Lookup for FHIR R4B SupplyRequest for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| SupplyRequest.id | UseElementSameName | SupplyRequest.id |
| SupplyRequest.meta | UseElementSameName | SupplyRequest.meta |
| SupplyRequest.implicitRules | UseElementSameName | SupplyRequest.implicitRules |
| SupplyRequest.language | UseElementSameName | SupplyRequest.language |
| SupplyRequest.text | UseElementSameName | SupplyRequest.text |
| SupplyRequest.contained | UseElementSameName | SupplyRequest.contained |
| SupplyRequest.extension | UseElementSameName | SupplyRequest.extension |
| SupplyRequest.modifierExtension | UseElementSameName | SupplyRequest.modifierExtension |
| SupplyRequest.identifier | UseElementSameName | SupplyRequest.identifier |
| SupplyRequest.status | UseElementSameName | SupplyRequest.status |
| SupplyRequest.category | UseElementSameName | SupplyRequest.category |
| SupplyRequest.priority | UseElementSameName | SupplyRequest.priority |
| SupplyRequest.item[x] | UseElementRenamed | SupplyRequest.item |
| SupplyRequest.quantity | UseElementSameName | SupplyRequest.quantity |
| SupplyRequest.parameter | UseElementSameName | SupplyRequest.parameter |
| SupplyRequest.parameter.id | UseElementSameName | SupplyRequest.parameter.id |
| SupplyRequest.parameter.extension | UseElementSameName | SupplyRequest.parameter.extension |
| SupplyRequest.parameter.modifierExtension | UseElementSameName | SupplyRequest.parameter.modifierExtension |
| SupplyRequest.parameter.code | UseElementSameName | SupplyRequest.parameter.code |
| SupplyRequest.parameter.value[x] | UseElementSameName | SupplyRequest.parameter.value[x] |
| SupplyRequest.occurrence[x] | UseElementSameName | SupplyRequest.occurrence[x] |
| SupplyRequest.authoredOn | UseElementSameName | SupplyRequest.authoredOn |
| SupplyRequest.requester | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyRequest.requester |
| SupplyRequest.supplier | UseElementSameName | SupplyRequest.supplier |
| SupplyRequest.reasonCode | UseElementRenamed | SupplyRequest.reason |
| SupplyRequest.reasonReference | UseElementRenamed | SupplyRequest.reason |
| SupplyRequest.deliverFrom | UseElementSameName | SupplyRequest.deliverFrom |
| SupplyRequest.deliverTo | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyRequest.deliverTo |
