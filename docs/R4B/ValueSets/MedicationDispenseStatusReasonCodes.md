Comparison of 
Generated at Thursday, April 3, 2025 8:18:24 AM

### MedicationDispense Status Reason Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | MedicationDispense Status Reason Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medicationdispense-status-reason` |
| Version | 4.3.0 |
| Description | MedicationDispense Status Codes |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3911` |
| Database Concept Count | `21` |
| Database Active Concept Count | `21` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationDispense` | `MedicationDispense.statusReason[x]` | `http://hl7.org/fhir/ValueSet/medicationdispense-status-reason` | `Example` | Why a dispense was not performed |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `altchoice` | Try another treatment first |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `clarif` | Prescription/Request requires clarification |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `drughigh` | Drug level too high |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `frr01` | Order Stopped |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `frr02` | Stale-dated Order |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `frr03` | Incomplete data |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `frr04` | Product unavailable |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `frr05` | Ethical/religious |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `frr06` | Unable to provide care |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `hospadm` | Admission to hospital |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `labint` | Lab interference issues |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `non-avail` | Patient not available |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `offmarket` | Drug not available - off market |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `outofstock` | Drug not available - out of stock |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `preg` | Patient is pregnant or breastfeeding |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `saig` | Allergy |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `sddi` | Drug interacts with another drug |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `sdupther` | Duplicate therapy |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `sintol` | Suspected intolerance |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `surg` | Patient scheduled for surgery |
| `http://terminology.hl7.org/CodeSystem/medicationdispense-status-reason` | `washout` | Washout |
