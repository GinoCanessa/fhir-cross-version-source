Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### LegalStatusOfSupply

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | LegalStatusOfSupply |
| Canonical URL | `http://hl7.org/fhir/ValueSet/legal-status-of-supply` |
| Version | 5.0.0 |
| Description | The prescription supply types appropriate to a medicinal product |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4659` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition` | `MedicinalProductDefinition.legalStatusOfSupply` | `http://hl7.org/fhir/ValueSet/legal-status-of-supply` | `Example` | The legal status of supply of the medicinal product as classified by the regulator |
| `http://hl7.org/fhir/StructureDefinition/PackagedProductDefinition` | `PackagedProductDefinition.legalStatusOfSupply.code` | `http://hl7.org/fhir/ValueSet/legal-status-of-supply` | `Example` | The actual status of supply. In what situation this package type may be supplied for use |

### Referenced Systems

* `http://hl7.org/fhir/legal-status-of-supply`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/legal-status-of-supply` | `100000072076` | Medicinal product not subject to medical prescription |
| `http://hl7.org/fhir/legal-status-of-supply` | `100000072077` | Medicinal product on medical prescription for renewable or non-renewable delivery |
| `http://hl7.org/fhir/legal-status-of-supply` | `100000072078` | Medicinal product subject to restricted medical prescription |
| `http://hl7.org/fhir/legal-status-of-supply` | `100000072079` | Medicinal product on medical prescription for non-renewable delivery |
| `http://hl7.org/fhir/legal-status-of-supply` | `100000072084` | Medicinal product subject to medical prescription |
| `http://hl7.org/fhir/legal-status-of-supply` | `100000072085` | Medicinal product subject to special medical prescription |
| `http://hl7.org/fhir/legal-status-of-supply` | `100000072086` | Medicinal product on medical prescription for renewable delivery |
| `http://hl7.org/fhir/legal-status-of-supply` | `100000157313` | Medicinal product subject to special and restricted medical prescription |
