### Lookup for FHIR R2 Signature for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Signature.id | UseElementSameName | Signature.id |
| Signature.extension | UseElementSameName | Signature.extension |
| Signature.type | UseElementSameName | Signature.type |
| Signature.when | UseElementSameName | Signature.when |
| Signature.who[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Signature.who |
| Signature.contentType | UseElementRenamed | Signature.sigFormat |
| Signature.blob | UseElementRenamed | Signature.data |
