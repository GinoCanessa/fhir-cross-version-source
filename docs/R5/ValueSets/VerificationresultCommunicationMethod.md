Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### VerificationresultCommunicationMethod

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | VerificationresultCommunicationMethod |
| Canonical URL | `http://hl7.org/fhir/ValueSet/verificationresult-communication-method` |
| Version | 5.0.0 |
| Description | Attested information may be validated by process that are manual or automated. For automated processes it may accomplished by the system of record reaching out through another system's API or information may be sent to the system of record. This value set defines a set of codes to describing the process, the how, a resource or data element is validated. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `5003` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/VerificationResult` | `VerificationResult.primarySource.communicationMethod` | `http://hl7.org/fhir/ValueSet/verificationresult-communication-method` | `Example` | Method for exchanging information with the primary source |
| `http://hl7.org/fhir/StructureDefinition/VerificationResult` | `VerificationResult.attestation.communicationMethod` | `http://hl7.org/fhir/ValueSet/verificationresult-communication-method` | `Example` | The method by which attested information was submitted/retrieved |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/verificationresult-communication-method`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/verificationresult-communication-method` | `manual` | Manual |
| `http://terminology.hl7.org/CodeSystem/verificationresult-communication-method` | `portal` | Portal |
| `http://terminology.hl7.org/CodeSystem/verificationresult-communication-method` | `pull` | Pull |
| `http://terminology.hl7.org/CodeSystem/verificationresult-communication-method` | `push` | Push |
