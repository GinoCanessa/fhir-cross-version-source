### Lookup for FHIR R5 RequestOrchestration for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| RequestOrchestration.id | UseElementRenamed | RequestGroup.id |
| RequestOrchestration.meta | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.meta |
| RequestOrchestration.implicitRules | UseElementRenamed | RequestGroup.implicitRules |
| RequestOrchestration.language | UseElementRenamed | RequestGroup.language |
| RequestOrchestration.text | UseElementRenamed | RequestGroup.text |
| RequestOrchestration.contained | UseElementRenamed | RequestGroup.contained |
| RequestOrchestration.extension | UseElementRenamed | RequestGroup.extension |
| RequestOrchestration.modifierExtension | UseElementRenamed | RequestGroup.modifierExtension |
| RequestOrchestration.identifier | UseElementRenamed | RequestGroup.identifier |
| RequestOrchestration.instantiatesCanonical | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.instantiatesCanonical |
| RequestOrchestration.instantiatesUri | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.instantiatesUri |
| RequestOrchestration.basedOn | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.basedOn |
| RequestOrchestration.replaces | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.replaces |
| RequestOrchestration.groupIdentifier | UseElementRenamed | RequestGroup.groupIdentifier |
| RequestOrchestration.status | UseElementRenamed | RequestGroup.status |
| RequestOrchestration.intent | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.intent |
| RequestOrchestration.priority | UseElementRenamed | RequestGroup.priority |
| RequestOrchestration.code | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.code |
| RequestOrchestration.subject | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.subject |
| RequestOrchestration.encounter | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.encounter |
| RequestOrchestration.authoredOn | UseElementRenamed | RequestGroup.authoredOn |
| RequestOrchestration.author | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.author |
| RequestOrchestration.reason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.reason |
| RequestOrchestration.goal | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.goal |
| RequestOrchestration.note | UseElementRenamed | RequestGroup.note |
| RequestOrchestration.action | UseElementRenamed | RequestGroup.action |
| RequestOrchestration.action.id | UseElementRenamed | RequestGroup.action.id |
| RequestOrchestration.action.extension | UseElementRenamed | RequestGroup.action.extension |
| RequestOrchestration.action.modifierExtension | UseElementRenamed | RequestGroup.action.modifierExtension |
| RequestOrchestration.action.linkId | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.linkId |
| RequestOrchestration.action.prefix | UseElementRenamed | RequestGroup.action.label |
| RequestOrchestration.action.title | UseElementRenamed | RequestGroup.action.title |
| RequestOrchestration.action.description | UseElementRenamed | RequestGroup.action.description |
| RequestOrchestration.action.textEquivalent | UseElementRenamed | RequestGroup.action.textEquivalent |
| RequestOrchestration.action.priority | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.priority |
| RequestOrchestration.action.code | UseElementRenamed | RequestGroup.action.code |
| RequestOrchestration.action.documentation | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.documentation |
| RequestOrchestration.action.goal | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.goal |
| RequestOrchestration.action.condition | UseElementRenamed | RequestGroup.action.condition |
| RequestOrchestration.action.condition.id | UseElementRenamed | RequestGroup.action.condition.id |
| RequestOrchestration.action.condition.extension | UseElementRenamed | RequestGroup.action.condition.extension |
| RequestOrchestration.action.condition.modifierExtension | UseElementRenamed | RequestGroup.action.condition.modifierExtension |
| RequestOrchestration.action.condition.kind | UseElementRenamed | RequestGroup.action.condition.kind |
| RequestOrchestration.action.condition.expression | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.condition.expression |
| RequestOrchestration.action.input | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.input |
| RequestOrchestration.action.input.id | UseExtensionFromAncestor | - |
| RequestOrchestration.action.input.extension | UseExtensionFromAncestor | - |
| RequestOrchestration.action.input.modifierExtension | UseExtensionFromAncestor | - |
| RequestOrchestration.action.input.title | UseExtensionFromAncestor | - |
| RequestOrchestration.action.input.requirement | UseExtensionFromAncestor | - |
| RequestOrchestration.action.input.relatedData | UseExtensionFromAncestor | - |
| RequestOrchestration.action.output | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.output |
| RequestOrchestration.action.output.id | UseExtensionFromAncestor | - |
| RequestOrchestration.action.output.extension | UseExtensionFromAncestor | - |
| RequestOrchestration.action.output.modifierExtension | UseExtensionFromAncestor | - |
| RequestOrchestration.action.output.title | UseExtensionFromAncestor | - |
| RequestOrchestration.action.output.requirement | UseExtensionFromAncestor | - |
| RequestOrchestration.action.output.relatedData | UseExtensionFromAncestor | - |
| RequestOrchestration.action.relatedAction | UseElementRenamed | RequestGroup.action.relatedAction |
| RequestOrchestration.action.relatedAction.id | UseElementRenamed | RequestGroup.action.relatedAction.id |
| RequestOrchestration.action.relatedAction.extension | UseElementRenamed | RequestGroup.action.relatedAction.extension |
| RequestOrchestration.action.relatedAction.modifierExtension | UseElementRenamed | RequestGroup.action.relatedAction.modifierExtension |
| RequestOrchestration.action.relatedAction.targetId | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.relatedAction.targetId |
| RequestOrchestration.action.relatedAction.relationship | UseElementRenamed | RequestGroup.action.relatedAction.relationship |
| RequestOrchestration.action.relatedAction.endRelationship | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.relatedAction.endRelationship |
| RequestOrchestration.action.relatedAction.offset[x] | UseElementRenamed | RequestGroup.action.relatedAction.offset[x] |
| RequestOrchestration.action.timing[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.timing |
| RequestOrchestration.action.location | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.location |
| RequestOrchestration.action.participant | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.participant |
| RequestOrchestration.action.participant.id | UseExtensionFromAncestor | - |
| RequestOrchestration.action.participant.extension | UseExtensionFromAncestor | - |
| RequestOrchestration.action.participant.modifierExtension | UseExtensionFromAncestor | - |
| RequestOrchestration.action.participant.type | UseExtensionFromAncestor | - |
| RequestOrchestration.action.participant.typeCanonical | UseExtensionFromAncestor | - |
| RequestOrchestration.action.participant.typeReference | UseExtensionFromAncestor | - |
| RequestOrchestration.action.participant.role | UseExtensionFromAncestor | - |
| RequestOrchestration.action.participant.function | UseExtensionFromAncestor | - |
| RequestOrchestration.action.participant.actor[x] | UseExtensionFromAncestor | - |
| RequestOrchestration.action.type | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.type |
| RequestOrchestration.action.groupingBehavior | UseElementRenamed | RequestGroup.action.groupingBehavior |
| RequestOrchestration.action.selectionBehavior | UseElementRenamed | RequestGroup.action.selectionBehavior |
| RequestOrchestration.action.requiredBehavior | UseElementRenamed | RequestGroup.action.requiredBehavior |
| RequestOrchestration.action.precheckBehavior | UseElementRenamed | RequestGroup.action.precheckBehavior |
| RequestOrchestration.action.cardinalityBehavior | UseElementRenamed | RequestGroup.action.cardinalityBehavior |
| RequestOrchestration.action.resource | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.resource |
| RequestOrchestration.action.definition[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.definition |
| RequestOrchestration.action.transform | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.transform |
| RequestOrchestration.action.dynamicValue | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.dynamicValue |
| RequestOrchestration.action.dynamicValue.id | UseExtensionFromAncestor | - |
| RequestOrchestration.action.dynamicValue.extension | UseExtensionFromAncestor | - |
| RequestOrchestration.action.dynamicValue.modifierExtension | UseExtensionFromAncestor | - |
| RequestOrchestration.action.dynamicValue.path | UseExtensionFromAncestor | - |
| RequestOrchestration.action.dynamicValue.expression | UseExtensionFromAncestor | - |
| RequestOrchestration.action.action | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-RequestOrchestration.action.action |
