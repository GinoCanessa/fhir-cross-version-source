### Lookup for FHIR R3 Provenance for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Provenance.id | UseElementSameName | Provenance.id |
| Provenance.meta | UseElementSameName | Provenance.meta |
| Provenance.implicitRules | UseElementSameName | Provenance.implicitRules |
| Provenance.language | UseElementSameName | Provenance.language |
| Provenance.text | UseElementSameName | Provenance.text |
| Provenance.contained | UseElementSameName | Provenance.contained |
| Provenance.extension | UseElementSameName | Provenance.extension |
| Provenance.modifierExtension | UseElementSameName | Provenance.modifierExtension |
| Provenance.target | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.target |
| Provenance.period | UseElementRenamed | Provenance.period |
| Provenance.recorded | UseElementSameName | Provenance.recorded |
| Provenance.policy | UseElementSameName | Provenance.policy |
| Provenance.location | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.location |
| Provenance.reason | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.reason |
| Provenance.activity | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.activity |
| Provenance.agent | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.agent |
| Provenance.agent.id | UseExtensionFromAncestor | - |
| Provenance.agent.extension | UseExtensionFromAncestor | - |
| Provenance.agent.modifierExtension | UseExtensionFromAncestor | - |
| Provenance.agent.role | UseExtensionFromAncestor | - |
| Provenance.agent.who[x] | UseExtensionFromAncestor | - |
| Provenance.agent.onBehalfOf[x] | UseExtensionFromAncestor | - |
| Provenance.agent.relatedAgentType | UseExtensionFromAncestor | - |
| Provenance.entity | UseElementSameName | Provenance.entity |
| Provenance.entity.id | UseElementSameName | Provenance.entity.id |
| Provenance.entity.extension | UseElementSameName | Provenance.entity.extension |
| Provenance.entity.modifierExtension | UseElementSameName | Provenance.entity.modifierExtension |
| Provenance.entity.role | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.entity.role |
| Provenance.entity.what[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.entity.what |
| Provenance.entity.agent | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.entity.agent |
| Provenance.signature | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.signature |
