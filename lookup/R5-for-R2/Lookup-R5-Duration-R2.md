### Lookup for FHIR R5 Duration for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Duration.id | UseElementSameName | Quantity.id |
| Duration.extension | UseElementSameName | Quantity.extension |
| Duration.value | UseElementSameName | Quantity.value |
| Duration.comparator | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Duration.comparator |
| Duration.unit | UseElementSameName | Quantity.unit |
| Duration.system | UseElementSameName | Quantity.system |
| Duration.code | UseElementSameName | Quantity.code |
