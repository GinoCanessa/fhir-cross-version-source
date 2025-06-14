### Lookup for FHIR R3 Contract for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Contract.id | UseElementSameName | Contract.id |
| Contract.meta | UseElementSameName | Contract.meta |
| Contract.implicitRules | UseElementSameName | Contract.implicitRules |
| Contract.language | UseElementSameName | Contract.language |
| Contract.text | UseElementSameName | Contract.text |
| Contract.contained | UseElementSameName | Contract.contained |
| Contract.extension | UseElementSameName | Contract.extension |
| Contract.modifierExtension | UseElementSameName | Contract.modifierExtension |
| Contract.identifier | UseElementSameName | Contract.identifier |
| Contract.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.status |
| Contract.issued | UseElementSameName | Contract.issued |
| Contract.applies | UseElementSameName | Contract.applies |
| Contract.subject | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.subject |
| Contract.topic | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.topic |
| Contract.authority | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.authority |
| Contract.domain | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.domain |
| Contract.type | UseElementSameName | Contract.type |
| Contract.subType | UseElementSameName | Contract.subType |
| Contract.action | UseElementSameName | Contract.action |
| Contract.actionReason | UseElementSameName | Contract.actionReason |
| Contract.decisionType | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.decisionType |
| Contract.contentDerivative | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.contentDerivative |
| Contract.securityLabel | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.securityLabel |
| Contract.agent | UseElementRenamed | Contract.actor |
| Contract.agent.id | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.agent.id |
| Contract.agent.extension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.agent.extension |
| Contract.agent.modifierExtension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.agent.modifierExtension |
| Contract.agent.actor | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.agent.actor |
| Contract.agent.role | UseElementRenamed | Contract.actor.role |
| Contract.signer | UseElementSameName | Contract.signer |
| Contract.signer.id | UseElementSameName | Contract.signer.id |
| Contract.signer.extension | UseElementSameName | Contract.signer.extension |
| Contract.signer.modifierExtension | UseElementSameName | Contract.signer.modifierExtension |
| Contract.signer.type | UseElementSameName | Contract.signer.type |
| Contract.signer.party | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.signer.party |
| Contract.signer.signature | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.signer.signature |
| Contract.valuedItem | UseElementSameName | Contract.valuedItem |
| Contract.valuedItem.id | UseElementSameName | Contract.valuedItem.id |
| Contract.valuedItem.extension | UseElementSameName | Contract.valuedItem.extension |
| Contract.valuedItem.modifierExtension | UseElementSameName | Contract.valuedItem.modifierExtension |
| Contract.valuedItem.entity[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.valuedItem.entity |
| Contract.valuedItem.identifier | UseElementSameName | Contract.valuedItem.identifier |
| Contract.valuedItem.effectiveTime | UseElementSameName | Contract.valuedItem.effectiveTime |
| Contract.valuedItem.quantity | UseElementSameName | Contract.valuedItem.quantity |
| Contract.valuedItem.unitPrice | UseElementSameName | Contract.valuedItem.unitPrice |
| Contract.valuedItem.factor | UseElementSameName | Contract.valuedItem.factor |
| Contract.valuedItem.points | UseElementSameName | Contract.valuedItem.points |
| Contract.valuedItem.net | UseElementSameName | Contract.valuedItem.net |
| Contract.term | UseElementSameName | Contract.term |
| Contract.term.id | UseElementSameName | Contract.term.id |
| Contract.term.extension | UseElementSameName | Contract.term.extension |
| Contract.term.modifierExtension | UseElementSameName | Contract.term.modifierExtension |
| Contract.term.identifier | UseElementSameName | Contract.term.identifier |
| Contract.term.issued | UseElementSameName | Contract.term.issued |
| Contract.term.applies | UseElementSameName | Contract.term.applies |
| Contract.term.type | UseElementSameName | Contract.term.type |
| Contract.term.subType | UseElementSameName | Contract.term.subType |
| Contract.term.topic | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.term.topic |
| Contract.term.action | UseElementSameName | Contract.term.action |
| Contract.term.actionReason | UseElementSameName | Contract.term.actionReason |
| Contract.term.securityLabel | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.term.securityLabel |
| Contract.term.agent | UseElementRenamed | Contract.term.actor |
| Contract.term.agent.id | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.term.agent.id |
| Contract.term.agent.extension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.term.agent.extension |
| Contract.term.agent.modifierExtension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.term.agent.modifierExtension |
| Contract.term.agent.actor | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.term.agent.actor |
| Contract.term.agent.role | UseElementRenamed | Contract.term.actor.role |
| Contract.term.text | UseElementSameName | Contract.term.text |
| Contract.term.valuedItem | UseElementSameName | Contract.term.valuedItem |
| Contract.term.valuedItem.id | UseElementSameName | Contract.term.valuedItem.id |
| Contract.term.valuedItem.extension | UseElementSameName | Contract.term.valuedItem.extension |
| Contract.term.valuedItem.modifierExtension | UseElementSameName | Contract.term.valuedItem.modifierExtension |
| Contract.term.valuedItem.entity[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.term.valuedItem.entity |
| Contract.term.valuedItem.identifier | UseElementSameName | Contract.term.valuedItem.identifier |
| Contract.term.valuedItem.effectiveTime | UseElementSameName | Contract.term.valuedItem.effectiveTime |
| Contract.term.valuedItem.quantity | UseElementSameName | Contract.term.valuedItem.quantity |
| Contract.term.valuedItem.unitPrice | UseElementSameName | Contract.term.valuedItem.unitPrice |
| Contract.term.valuedItem.factor | UseElementSameName | Contract.term.valuedItem.factor |
| Contract.term.valuedItem.points | UseElementSameName | Contract.term.valuedItem.points |
| Contract.term.valuedItem.net | UseElementSameName | Contract.term.valuedItem.net |
| Contract.term.group | UseElementSameName | Contract.term.group |
| Contract.binding[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.binding |
| Contract.friendly | UseElementSameName | Contract.friendly |
| Contract.friendly.id | UseElementSameName | Contract.friendly.id |
| Contract.friendly.extension | UseElementSameName | Contract.friendly.extension |
| Contract.friendly.modifierExtension | UseElementSameName | Contract.friendly.modifierExtension |
| Contract.friendly.content[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.friendly.content |
| Contract.legal | UseElementSameName | Contract.legal |
| Contract.legal.id | UseElementSameName | Contract.legal.id |
| Contract.legal.extension | UseElementSameName | Contract.legal.extension |
| Contract.legal.modifierExtension | UseElementSameName | Contract.legal.modifierExtension |
| Contract.legal.content[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.legal.content |
| Contract.rule | UseElementSameName | Contract.rule |
| Contract.rule.id | UseElementSameName | Contract.rule.id |
| Contract.rule.extension | UseElementSameName | Contract.rule.extension |
| Contract.rule.modifierExtension | UseElementSameName | Contract.rule.modifierExtension |
| Contract.rule.content[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Contract.rule.content |
