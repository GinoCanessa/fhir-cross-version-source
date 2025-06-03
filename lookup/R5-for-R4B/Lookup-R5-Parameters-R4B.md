### Lookup for FHIR R5 Parameters for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Parameters.id | UseOneOfElements | Parameters.id,Parameters.id |
| Parameters.meta | UseOneOfElements | Parameters.meta,Parameters.meta |
| Parameters.implicitRules | UseOneOfElements | Parameters.implicitRules,Parameters.implicitRules |
| Parameters.language | UseOneOfElements | Parameters.language,Parameters.language |
| Parameters.parameter | UseOneOfElements | Parameters.parameter,Parameters.parameter |
| Parameters.parameter.id | UseOneOfElements | Parameters.parameter.id,Parameters.parameter.id |
| Parameters.parameter.extension | UseOneOfElements | Parameters.parameter.extension,Parameters.parameter.extension |
| Parameters.parameter.modifierExtension | UseOneOfElements | Parameters.parameter.modifierExtension,Parameters.parameter.modifierExtension |
| Parameters.parameter.name | UseOneOfElements | Parameters.parameter.name,Parameters.parameter.name |
| Parameters.parameter.value[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Parameters.parameter.value |
| Parameters.parameter.resource | UseOneOfElements | Parameters.parameter.resource,Parameters.parameter.resource |
| Parameters.parameter.part | UseOneOfElements | Parameters.parameter.part,Parameters.parameter.part |
