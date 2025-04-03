Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### Mime Types

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | Mime Types |
| Canonical URL | `http://hl7.org/fhir/ValueSet/mimetypes` |
| Version | 4.0.1 |
| Description | This value set includes all possible codes from BCP-13 (http://tools.ietf.org/html/bcp13) |
| Status | `Active` |
| Has Escape Valve Code | `` |
| Database Key | `2599` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Attachment` | `Attachment.contentType` | `http://hl7.org/fhir/ValueSet/mimetypes\|4.0.1` | `Required` | Mime type of the content, with charset etc. |
| `http://hl7.org/fhir/StructureDefinition/ElementDefinition` | `ElementDefinition.mapping.language` | `http://hl7.org/fhir/ValueSet/mimetypes\|4.0.1` | `Required` | Computable language of mapping |
| `http://hl7.org/fhir/StructureDefinition/Signature` | `Signature.targetFormat` | `http://hl7.org/fhir/ValueSet/mimetypes\|4.0.1` | `Required` | The technical format of the signed resources |
| `http://hl7.org/fhir/StructureDefinition/Signature` | `Signature.sigFormat` | `http://hl7.org/fhir/ValueSet/mimetypes\|4.0.1` | `Required` | The technical format of the signature |
| `http://hl7.org/fhir/StructureDefinition/Binary` | `Binary.contentType` | `http://hl7.org/fhir/ValueSet/mimetypes\|4.0.1` | `Required` | MimeType of the binary content |
| `http://hl7.org/fhir/StructureDefinition/CapabilityStatement` | `CapabilityStatement.format` | `http://hl7.org/fhir/ValueSet/mimetypes\|4.0.1` | `Required` | formats supported (xml \| json \| ttl \| mime type) |
| `http://hl7.org/fhir/StructureDefinition/CapabilityStatement` | `CapabilityStatement.patchFormat` | `http://hl7.org/fhir/ValueSet/mimetypes\|4.0.1` | `Required` | Patch formats supported |
| `http://hl7.org/fhir/StructureDefinition/Endpoint` | `Endpoint.payloadMimeType` | `http://hl7.org/fhir/ValueSet/mimetypes\|4.0.1` | `Required` | Mimetype to send. If not specified, the content could be anything (including no payload, if the connectionType defined this) |
| `http://hl7.org/fhir/StructureDefinition/Subscription` | `Subscription.channel.payload` | `http://hl7.org/fhir/ValueSet/mimetypes\|4.0.1` | `Required` | MIME type to send, or omit for no payload |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.operation.accept` | `http://hl7.org/fhir/ValueSet/mimetypes\|4.0.1` | `Required` | Mime type to accept in the payload of the response, with charset etc. |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.operation.contentType` | `http://hl7.org/fhir/ValueSet/mimetypes\|4.0.1` | `Required` | Mime type of the request payload contents, with charset etc. |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.assert.contentType` | `http://hl7.org/fhir/ValueSet/mimetypes\|4.0.1` | `Required` | Mime type to compare against the 'Content-Type' header |
| `http://hl7.org/fhir/StructureDefinition/mimeType` | `Extension.value[x]` | `http://hl7.org/fhir/ValueSet/mimetypes\|4.0.1` | `Required` | Value of extension |

### Expansion Failure

Failed to expand this value set: Expansion is limited
