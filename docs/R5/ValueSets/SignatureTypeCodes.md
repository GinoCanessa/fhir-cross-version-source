Comparison of 
Generated at Monday, April 14, 2025 6:17:42 PM

### SignatureTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SignatureTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/signature-type` |
| Version | 5.0.0 |
| Description | The Digital Signature Purposes, an indication of the reason an entity signs a document. This is included in the signed information and can be used when determining accountability for various actions concerning the document. Examples include: author, transcriptionist/recorder, and witness. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4903` |
| Database Concept Count | `24` |
| Database Active Concept Count | `24` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Signature` | `Signature.type` | `http://hl7.org/fhir/ValueSet/signature-type` | `Preferred` | Indication of the reason the entity signed the object(s) |

### Referenced Systems

* `http://uri.etsi.org/01903/v1.2.2`
* `urn:iso-astm:E1762-95:2013`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://uri.etsi.org/01903/v1.2.2` | `ProofOfCreation` | Proof of creation |
| `http://uri.etsi.org/01903/v1.2.2` | `ProofOfDelivery` | Proof of delivery |
| `http://uri.etsi.org/01903/v1.2.2` | `ProofOfOrigin` | Proof of origin |
| `http://uri.etsi.org/01903/v1.2.2` | `ProofOfReceipt` | Proof of receipt |
| `http://uri.etsi.org/01903/v1.2.2` | `ProofOfSender` | Proof of sender |
| `http://uri.etsi.org/01903/v1.2.2` | `ProofOfapproval` | Proof of approval |
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
