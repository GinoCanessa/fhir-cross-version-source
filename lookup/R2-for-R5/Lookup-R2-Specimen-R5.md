### Lookup for FHIR R2 Specimen for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Specimen.id | UseElementSameName | Specimen.id |
| Specimen.meta | UseElementSameName | Specimen.meta |
| Specimen.implicitRules | UseElementSameName | Specimen.implicitRules |
| Specimen.language | UseElementSameName | Specimen.language |
| Specimen.text | UseElementSameName | Specimen.text |
| Specimen.contained | UseElementSameName | Specimen.contained |
| Specimen.extension | UseElementSameName | Specimen.extension |
| Specimen.modifierExtension | UseElementSameName | Specimen.modifierExtension |
| Specimen.identifier | UseElementSameName | Specimen.identifier |
| Specimen.status | UseElementSameName | Specimen.status |
| Specimen.type | UseElementSameName | Specimen.type |
| Specimen.parent | UseElementSameName | Specimen.parent |
| Specimen.subject | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Specimen.subject |
| Specimen.accessionIdentifier | UseElementSameName | Specimen.accessionIdentifier |
| Specimen.receivedTime | UseElementSameName | Specimen.receivedTime |
| Specimen.collection | UseElementSameName | Specimen.collection |
| Specimen.collection.id | UseElementSameName | Specimen.collection.id |
| Specimen.collection.extension | UseElementSameName | Specimen.collection.extension |
| Specimen.collection.modifierExtension | UseElementSameName | Specimen.collection.modifierExtension |
| Specimen.collection.collector | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Specimen.collection.collector |
| Specimen.collection.comment | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Specimen.collection.comment |
| Specimen.collection.collected[x] | UseElementSameName | Specimen.collection.collected[x] |
| Specimen.collection.quantity | UseElementSameName | Specimen.collection.quantity |
| Specimen.collection.method | UseElementSameName | Specimen.collection.method |
| Specimen.collection.bodySite | UseElementSameName | Specimen.collection.bodySite |
| Specimen.treatment | UseElementRenamed | Specimen.processing |
| Specimen.treatment.id | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Specimen.treatment.id |
| Specimen.treatment.extension | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Specimen.treatment.extension |
| Specimen.treatment.modifierExtension | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Specimen.treatment.modifierExtension |
| Specimen.treatment.description | UseElementRenamed | Specimen.processing.description |
| Specimen.treatment.procedure | UseElementRenamed | Specimen.processing.method |
| Specimen.treatment.additive | UseElementRenamed | Specimen.processing.additive |
| Specimen.container | UseElementSameName | Specimen.container |
| Specimen.container.id | UseElementSameName | Specimen.container.id |
| Specimen.container.extension | UseElementSameName | Specimen.container.extension |
| Specimen.container.modifierExtension | UseElementSameName | Specimen.container.modifierExtension |
| Specimen.container.identifier | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Specimen.container.identifier |
| Specimen.container.description | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Specimen.container.description |
| Specimen.container.type | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Specimen.container.type |
| Specimen.container.capacity | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Specimen.container.capacity |
| Specimen.container.specimenQuantity | UseElementSameName | Specimen.container.specimenQuantity |
| Specimen.container.additive[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Specimen.container.additive |
