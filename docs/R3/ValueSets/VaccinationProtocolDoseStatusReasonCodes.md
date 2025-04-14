Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### Vaccination Protocol Dose Status Reason codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Vaccination Protocol Dose Status Reason codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/vaccination-protocol-dose-status-reason` |
| Version | 3.0.2 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support describing the reason why an administered dose has been assigned a particular status. Often, this reason describes why a dose is considered invalid. This value set is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2162` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Immunization` | `Immunization.vaccinationProtocol.doseStatusReason` | `http://hl7.org/fhir/ValueSet/vaccination-protocol-dose-status-reason` | `Example` | Why dose does (not) count |

### Referenced Systems

* `http://hl7.org/fhir/vaccination-protocol-dose-status-reason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/vaccination-protocol-dose-status-reason` | `advstorage` | Adverse storage condition |
| `http://hl7.org/fhir/vaccination-protocol-dose-status-reason` | `coldchbrk` | Cold chain break |
| `http://hl7.org/fhir/vaccination-protocol-dose-status-reason` | `explot` | Expired lot |
| `http://hl7.org/fhir/vaccination-protocol-dose-status-reason` | `outsidesched` | Administered outside recommended schedule |
| `http://hl7.org/fhir/vaccination-protocol-dose-status-reason` | `prodrecall` | Product recall |
