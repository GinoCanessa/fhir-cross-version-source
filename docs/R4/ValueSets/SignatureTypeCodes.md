Comparison of 
Generated at Monday, April 14, 2025 6:17:26 PM

### SignatureTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | SignatureTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/signature-type` |
| Version | 4.0.1 |
| Description | The Digital Signature Purposes, an indication of the reason an entity signs a document. This is included in the signed information and can be used when determining accountability for various actions concerning the document. Examples include: author, transcriptionist/recorder, and witness. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2761` |
| Database Concept Count | `18` |
| Database Active Concept Count | `18` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Signature` | `Signature.type` | `http://hl7.org/fhir/ValueSet/signature-type` | `Preferred` | Indication of the reason the entity signed the object(s) |
| `http://hl7.org/fhir/StructureDefinition/questionnaire-signatureRequired` | `Extension.value[x]` | `http://hl7.org/fhir/ValueSet/signature-type` | `Preferred` | Value of extension |

### Referenced Systems

* `urn:iso-astm:E1762-95:2013`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.1` | Author's Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.10` | Identity Witness Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.11` | Consent Witness Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.12` | Interpreter Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.13` | Review Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.14` | Source Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.15` | Addendum Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.16` | Modification Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.17` | Administrative (Error/Edit) Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.18` | Timestamp Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.2` | Coauthor's Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.3` | Co-participant's Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.4` | Transcriptionist/Recorder Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.5` | Verification Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.6` | Validation Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.7` | Consent Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.8` | Signature Witness Signature |
| `urn:iso-astm:E1762-95:2013` | `1.2.840.10065.1.12.1.9` | Event Witness Signature |
