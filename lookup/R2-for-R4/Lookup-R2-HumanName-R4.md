### Lookup for FHIR R2 HumanName for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| HumanName.id | UseElementSameName | HumanName.id |
| HumanName.extension | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-HumanName.extension |
| HumanName.use | UseElementSameName | HumanName.use |
| HumanName.text | UseElementSameName | HumanName.text |
| HumanName.family | UseElementRenamed | HumanName.extension |
| HumanName.given | UseElementSameName | HumanName.given |
| HumanName.prefix | UseElementSameName | HumanName.prefix |
| HumanName.suffix | UseElementSameName | HumanName.suffix |
| HumanName.period | UseElementSameName | HumanName.period |
