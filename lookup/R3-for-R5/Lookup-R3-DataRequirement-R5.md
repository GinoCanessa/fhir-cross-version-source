### Lookup for FHIR R3 DataRequirement for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DataRequirement.id | UseElementSameName | DataRequirement.id |
| DataRequirement.extension | UseElementSameName | DataRequirement.extension |
| DataRequirement.type | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DataRequirement.type |
| DataRequirement.profile | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DataRequirement.profile |
| DataRequirement.mustSupport | UseElementSameName | DataRequirement.mustSupport |
| DataRequirement.codeFilter | UseElementSameName | DataRequirement.codeFilter |
| DataRequirement.codeFilter.id | UseElementSameName | DataRequirement.codeFilter.id |
| DataRequirement.codeFilter.extension | UseElementSameName | DataRequirement.codeFilter.extension |
| DataRequirement.codeFilter.path | UseElementSameName | DataRequirement.codeFilter.path |
| DataRequirement.codeFilter.valueSet[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DataRequirement.codeFilter.valueSet |
| DataRequirement.codeFilter.valueCode | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DataRequirement.codeFilter.valueCode |
| DataRequirement.codeFilter.valueCoding | UseElementRenamed | DataRequirement.codeFilter.code |
| DataRequirement.codeFilter.valueCodeableConcept | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DataRequirement.codeFilter.valueCodeableConcept |
| DataRequirement.dateFilter | UseElementSameName | DataRequirement.dateFilter |
| DataRequirement.dateFilter.id | UseElementSameName | DataRequirement.dateFilter.id |
| DataRequirement.dateFilter.extension | UseElementSameName | DataRequirement.dateFilter.extension |
| DataRequirement.dateFilter.path | UseElementSameName | DataRequirement.dateFilter.path |
| DataRequirement.dateFilter.value[x] | UseElementSameName | DataRequirement.dateFilter.value[x] |
