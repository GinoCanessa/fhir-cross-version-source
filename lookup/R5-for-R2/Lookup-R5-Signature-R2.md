### Lookup for FHIR R5 Signature for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Signature.id | UseElementSameName | Signature.id |
| Signature.extension | UseElementSameName | Signature.extension |
| Signature.type | UseElementSameName | Signature.type |
| Signature.when | UseElementSameName | Signature.when |
| Signature.who | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Signature.who |
| Signature.onBehalfOf | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Signature.onBehalfOf |
| Signature.targetFormat | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Signature.targetFormat |
| Signature.sigFormat | UseElementRenamed | Signature.contentType |
| Signature.data | UseElementRenamed | Signature.blob |
