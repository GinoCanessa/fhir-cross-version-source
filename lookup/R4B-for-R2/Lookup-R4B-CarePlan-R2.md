### Lookup for FHIR R4B CarePlan for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| CarePlan.id | UseElementSameName | CarePlan.id |
| CarePlan.meta | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.meta |
| CarePlan.implicitRules | UseElementSameName | CarePlan.implicitRules |
| CarePlan.language | UseElementSameName | CarePlan.language |
| CarePlan.text | UseElementSameName | CarePlan.text |
| CarePlan.contained | UseElementSameName | CarePlan.contained |
| CarePlan.extension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.extension |
| CarePlan.modifierExtension | UseElementSameName | CarePlan.modifierExtension |
| CarePlan.identifier | UseElementSameName | CarePlan.identifier |
| CarePlan.instantiatesCanonical | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.instantiatesCanonical |
| CarePlan.instantiatesUri | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.instantiatesUri |
| CarePlan.basedOn | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.basedOn |
| CarePlan.replaces | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.replaces |
| CarePlan.partOf | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.partOf |
| CarePlan.status | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.status |
| CarePlan.intent | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.intent |
| CarePlan.category | UseElementSameName | CarePlan.category |
| CarePlan.title | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.title |
| CarePlan.description | UseElementSameName | CarePlan.description |
| CarePlan.subject | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.subject |
| CarePlan.encounter | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.encounter |
| CarePlan.period | UseElementSameName | CarePlan.period |
| CarePlan.created | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.created |
| CarePlan.author | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.author |
| CarePlan.contributor | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.contributor |
| CarePlan.careTeam | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.careTeam |
| CarePlan.addresses | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.addresses |
| CarePlan.supportingInfo | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.supportingInfo |
| CarePlan.goal | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.goal |
| CarePlan.activity | UseElementSameName | CarePlan.activity |
| CarePlan.activity.id | UseElementSameName | CarePlan.activity.id |
| CarePlan.activity.extension | UseElementSameName | CarePlan.activity.extension |
| CarePlan.activity.modifierExtension | UseElementSameName | CarePlan.activity.modifierExtension |
| CarePlan.activity.outcomeCodeableConcept | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.activity.outcomeCodeableConcept |
| CarePlan.activity.outcomeReference | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.activity.outcomeReference |
| CarePlan.activity.progress | UseElementSameName | CarePlan.activity.progress |
| CarePlan.activity.reference | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.activity.reference |
| CarePlan.activity.detail | UseElementSameName | CarePlan.activity.detail |
| CarePlan.activity.detail.id | UseElementSameName | CarePlan.activity.detail.id |
| CarePlan.activity.detail.extension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.activity.detail.extension |
| CarePlan.activity.detail.modifierExtension | UseElementSameName | CarePlan.activity.detail.modifierExtension |
| CarePlan.activity.detail.kind | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.activity.detail.kind |
| CarePlan.activity.detail.instantiatesCanonical | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.activity.detail.instantiatesCanonical |
| CarePlan.activity.detail.instantiatesUri | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.activity.detail.instantiatesUri |
| CarePlan.activity.detail.code | UseElementSameName | CarePlan.activity.detail.code |
| CarePlan.activity.detail.reasonCode | UseElementSameName | CarePlan.activity.detail.reasonCode |
| CarePlan.activity.detail.reasonReference | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.activity.detail.reasonReference |
| CarePlan.activity.detail.goal | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.activity.detail.goal |
| CarePlan.activity.detail.status | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.activity.detail.status |
| CarePlan.activity.detail.statusReason | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.activity.detail.statusReason |
| CarePlan.activity.detail.doNotPerform | UseElementRenamed | CarePlan.activity.detail.prohibited |
| CarePlan.activity.detail.scheduled[x] | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.activity.detail.scheduled |
| CarePlan.activity.detail.location | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.activity.detail.location |
| CarePlan.activity.detail.performer | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.activity.detail.performer |
| CarePlan.activity.detail.product[x] | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.activity.detail.product |
| CarePlan.activity.detail.dailyAmount | UseElementSameName | CarePlan.activity.detail.dailyAmount |
| CarePlan.activity.detail.quantity | UseElementSameName | CarePlan.activity.detail.quantity |
| CarePlan.activity.detail.description | UseElementSameName | CarePlan.activity.detail.description |
| CarePlan.note | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CarePlan.note |
