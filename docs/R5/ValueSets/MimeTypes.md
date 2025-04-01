Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### MimeTypes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | MimeTypes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/mimetypes` |
| Version | 5.0.0 |
| Description | This value set includes all possible codes from BCP-13 (see http://tools.ietf.org/html/bcp13) |
| Status | `Active` |
| Has Escape Valve Code | `` |
| Database Key | `4742` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Attachment` | `Attachment.contentType` | `http://hl7.org/fhir/ValueSet/mimetypes\|5.0.0` | `Required` | Mime type of the content, with charset etc. |
| `http://hl7.org/fhir/StructureDefinition/ElementDefinition` | `ElementDefinition.mapping.language` | `http://hl7.org/fhir/ValueSet/mimetypes\|5.0.0` | `Required` | Computable language of mapping |
| `http://hl7.org/fhir/StructureDefinition/Expression` | `Expression.language` | `http://hl7.org/fhir/ValueSet/mimetypes` | `Required` | text/cql \| text/fhirpath \| application/x-fhir-query \| etc. |
| `http://hl7.org/fhir/StructureDefinition/Signature` | `Signature.targetFormat` | `http://hl7.org/fhir/ValueSet/mimetypes\|5.0.0` | `Required` | The technical format of the signed resources |
| `http://hl7.org/fhir/StructureDefinition/Signature` | `Signature.sigFormat` | `http://hl7.org/fhir/ValueSet/mimetypes\|5.0.0` | `Required` | The technical format of the signature |
| `http://hl7.org/fhir/StructureDefinition/Binary` | `Binary.contentType` | `http://hl7.org/fhir/ValueSet/mimetypes\|5.0.0` | `Required` | MimeType of the binary content |
| `http://hl7.org/fhir/StructureDefinition/CapabilityStatement` | `CapabilityStatement.format` | `http://hl7.org/fhir/ValueSet/mimetypes\|5.0.0` | `Required` | formats supported (xml \| json \| ttl \| mime type) |
| `http://hl7.org/fhir/StructureDefinition/CapabilityStatement` | `CapabilityStatement.patchFormat` | `http://hl7.org/fhir/ValueSet/mimetypes\|5.0.0` | `Required` | Patch formats supported |
| `http://hl7.org/fhir/StructureDefinition/Endpoint` | `Endpoint.payload.mimeType` | `http://hl7.org/fhir/ValueSet/mimetypes\|5.0.0` | `Required` | Mimetype to send. If not specified, the content could be anything (including no payload, if the connectionType defined this) |
| `http://hl7.org/fhir/StructureDefinition/Subscription` | `Subscription.contentType` | `http://hl7.org/fhir/ValueSet/mimetypes\|5.0.0` | `Required` | MIME type to send, or omit for no payload |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.operation.accept` | `http://hl7.org/fhir/ValueSet/mimetypes\|5.0.0` | `Required` | Mime type to accept in the payload of the response, with charset etc |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.operation.contentType` | `http://hl7.org/fhir/ValueSet/mimetypes\|5.0.0` | `Required` | Mime type of the request payload contents, with charset etc |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.assert.contentType` | `http://hl7.org/fhir/ValueSet/mimetypes\|5.0.0` | `Required` | Mime type to compare against the 'Content-Type' header |

### Expansion Failure

Failed to expand this value set: Expansion is limited
