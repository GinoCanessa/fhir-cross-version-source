### Lookup for FHIR R4B Parameters for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Parameters.id | UseOneOfElements | ExpansionProfile.id,Parameters.id |
| Parameters.meta | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Parameters.meta |
| Parameters.implicitRules | UseOneOfElements | ExpansionProfile.implicitRules,Parameters.implicitRules |
| Parameters.language | UseOneOfElements | ExpansionProfile.language,Parameters.language |
| Parameters.parameter | UseElementSameName | Parameters.parameter |
| Parameters.parameter.id | UseElementSameName | Parameters.parameter.id |
| Parameters.parameter.extension | UseElementSameName | Parameters.parameter.extension |
| Parameters.parameter.modifierExtension | UseElementSameName | Parameters.parameter.modifierExtension |
| Parameters.parameter.name | UseElementSameName | Parameters.parameter.name |
| Parameters.parameter.value[x] | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Parameters.parameter.value |
| Parameters.parameter.resource | UseElementSameName | Parameters.parameter.resource |
| Parameters.parameter.part | UseElementSameName | Parameters.parameter.part |
