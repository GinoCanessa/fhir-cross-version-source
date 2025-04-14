Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### AdmitSource

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | AdmitSource |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-admit-source` |
| Version | 1.0.2 |
| Description | This value set defines a set of codes that can be used to indicate from where the patient came in. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `142` |
| Database Concept Count | `10` |
| Database Active Concept Count | `10` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.hospitalization.admitSource` | `http://hl7.org/fhir/ValueSet/encounter-admit-source` | `Preferred` | From where patient was admitted (physician referral, transfer) |

### Referenced Systems

* `http://hl7.org/fhir/admit-source`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/admit-source` | `born` | Born in hospital |
| `http://hl7.org/fhir/admit-source` | `emd` | From accident/emergency department |
| `http://hl7.org/fhir/admit-source` | `gp` | General Practitioner referral |
| `http://hl7.org/fhir/admit-source` | `hosp-trans` | Transferred from other hospital |
| `http://hl7.org/fhir/admit-source` | `mp` | Medical Practitioner/physician referral |
| `http://hl7.org/fhir/admit-source` | `nursing` | From nursing home |
| `http://hl7.org/fhir/admit-source` | `other` | Other |
| `http://hl7.org/fhir/admit-source` | `outp` | From outpatient department |
| `http://hl7.org/fhir/admit-source` | `psych` | From psychiatric hospital |
| `http://hl7.org/fhir/admit-source` | `rehab` | From rehabilitation facility |
