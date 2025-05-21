### Lookup for FHIR R4B ProductShelfLife for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ProductShelfLife.id | UseElementSameName | ProductShelfLife.id |
| ProductShelfLife.extension | UseElementSameName | ProductShelfLife.extension |
| ProductShelfLife.modifierExtension | UseElementSameName | ProductShelfLife.modifierExtension |
| ProductShelfLife.identifier | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-ProductShelfLife.identifier |
| ProductShelfLife.type | UseElementSameName | ProductShelfLife.type |
| ProductShelfLife.period | UseElementRenamed | ProductShelfLife.period[x] |
| ProductShelfLife.specialPrecautionsForStorage | UseElementSameName | ProductShelfLife.specialPrecautionsForStorage |
