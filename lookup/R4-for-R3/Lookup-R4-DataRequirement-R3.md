### Lookup for FHIR R4 DataRequirement for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DataRequirement.id | UseElementSameName | DataRequirement.id |
| DataRequirement.extension | UseElementSameName | DataRequirement.extension |
| DataRequirement.type | UseElementSameName | DataRequirement.type |
| DataRequirement.profile | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-DataRequirement.profile |
| DataRequirement.subject[x] | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-DataRequirement.subject |
| DataRequirement.mustSupport | UseElementSameName | DataRequirement.mustSupport |
| DataRequirement.codeFilter | UseElementSameName | DataRequirement.codeFilter |
| DataRequirement.codeFilter.id | UseElementSameName | DataRequirement.codeFilter.id |
| DataRequirement.codeFilter.extension | UseElementSameName | DataRequirement.codeFilter.extension |
| DataRequirement.codeFilter.path | UseElementSameName | DataRequirement.codeFilter.path |
| DataRequirement.codeFilter.searchParam | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-DataRequirement.codeFilter.searchParam |
| DataRequirement.codeFilter.valueSet | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-DataRequirement.codeFilter.valueSet |
| DataRequirement.codeFilter.code | UseElementSameName | DataRequirement.codeFilter.valueCoding |
| DataRequirement.dateFilter | UseElementSameName | DataRequirement.dateFilter |
| DataRequirement.dateFilter.id | UseElementSameName | DataRequirement.dateFilter.id |
| DataRequirement.dateFilter.extension | UseElementSameName | DataRequirement.dateFilter.extension |
| DataRequirement.dateFilter.path | UseElementSameName | DataRequirement.dateFilter.path |
| DataRequirement.dateFilter.searchParam | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-DataRequirement.dateFilter.searchParam |
| DataRequirement.dateFilter.value[x] | UseElementSameName | DataRequirement.dateFilter.value[x] |
| DataRequirement.limit | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-DataRequirement.limit |
| DataRequirement.sort | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-DataRequirement.sort |
| DataRequirement.sort.id | UseExtensionFromAncestor | - |
| DataRequirement.sort.extension | UseExtensionFromAncestor | - |
| DataRequirement.sort.path | UseExtensionFromAncestor | - |
| DataRequirement.sort.direction | UseExtensionFromAncestor | - |
