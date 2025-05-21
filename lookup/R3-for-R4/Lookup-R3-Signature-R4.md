### Lookup for FHIR R3 Signature for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Signature.id | UseElementSameName | Signature.id |
| Signature.extension | UseElementSameName | Signature.extension |
| Signature.type | UseElementSameName | Signature.type |
| Signature.when | UseElementSameName | Signature.when |
| Signature.who[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Signature.who |
| Signature.onBehalfOf[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Signature.onBehalfOf |
| Signature.contentType | UseElementRenamed | Signature.sigFormat |
| Signature.blob | UseElementRenamed | Signature.data |
