### Lookup for FHIR R4 Binary for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Binary.id | UseElementSameName | Binary.id |
| Binary.meta | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Binary.meta |
| Binary.implicitRules | UseElementSameName | Binary.implicitRules |
| Binary.language | UseElementSameName | Binary.language |
| Binary.contentType | UseElementSameName | Binary.contentType |
| Binary.securityContext | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Binary.securityContext |
| Binary.data | UseElementRenamed | Binary.content |
