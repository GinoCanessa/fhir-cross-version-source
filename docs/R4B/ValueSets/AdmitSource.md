Comparison of 
Generated at Thursday, April 3, 2025 8:18:24 AM

### AdmitSource

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | AdmitSource |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-admit-source` |
| Version | 4.3.0 |
| Description | This value set defines a set of codes that can be used to indicate from where the patient came in. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `3732` |
| Database Concept Count | `10` |
| Database Active Concept Count | `10` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.hospitalization.admitSource` | `http://hl7.org/fhir/ValueSet/encounter-admit-source` | `Preferred` | From where patient was admitted (physician referral, transfer) |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/admit-source`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/admit-source` | `born` | Born in hospital |
| `http://terminology.hl7.org/CodeSystem/admit-source` | `emd` | From accident/emergency department |
| `http://terminology.hl7.org/CodeSystem/admit-source` | `gp` | General Practitioner referral |
| `http://terminology.hl7.org/CodeSystem/admit-source` | `hosp-trans` | Transferred from other hospital |
| `http://terminology.hl7.org/CodeSystem/admit-source` | `mp` | Medical Practitioner/physician referral |
| `http://terminology.hl7.org/CodeSystem/admit-source` | `nursing` | From nursing home |
| `http://terminology.hl7.org/CodeSystem/admit-source` | `other` | Other |
| `http://terminology.hl7.org/CodeSystem/admit-source` | `outp` | From outpatient department |
| `http://terminology.hl7.org/CodeSystem/admit-source` | `psych` | From psychiatric hospital |
| `http://terminology.hl7.org/CodeSystem/admit-source` | `rehab` | From rehabilitation facility |
