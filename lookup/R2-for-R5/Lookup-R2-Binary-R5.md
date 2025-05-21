### Lookup for FHIR R2 Binary for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Binary.id | UseElementSameName | Binary.id |
| Binary.meta | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Binary.meta |
| Binary.implicitRules | UseElementSameName | Binary.implicitRules |
| Binary.language | UseElementSameName | Binary.language |
| Binary.contentType | UseElementSameName | Binary.contentType |
| Binary.content | UseElementRenamed | Binary.data |
