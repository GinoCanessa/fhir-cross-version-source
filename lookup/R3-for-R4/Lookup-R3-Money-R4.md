### Lookup for FHIR R3 Money for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Money.id | UseElementSameName | Money.id |
| Money.extension | UseElementSameName | Money.extension |
| Money.value | UseElementSameName | Money.value |
| Money.comparator | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Money.comparator |
| Money.unit | UseElementRenamed | Money.currency |
| Money.system | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Money.system |
| Money.code | UseElementRenamed | Money.currency |
