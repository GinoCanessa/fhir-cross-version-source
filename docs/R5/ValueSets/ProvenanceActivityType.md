Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### ProvenanceActivityType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ProvenanceActivityType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/provenance-activity-type` |
| Version | 5.0.0 |
| Description | Some potential code systems are:<br/>- [v3-DocumentCompletion](http://terminology.hl7.org/3.0.0/CodeSystem-v3-DocumentCompletion.html)<br/>- [v3-DataOperation](http://terminology.hl7.org/3.0.0/CodeSystem-v3-DataOperation.html)<br/>- [v3-ActCode](http://hl7.org/fhir/v3/ActCode/cs.html)<br/>- [ISO Lifecycle](http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle) |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4812` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Provenance` | `Provenance.activity` | `http://hl7.org/fhir/ValueSet/provenance-activity-type` | `Example` | Activity that occurred |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `amend` | Amend (Update) Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `deidentify` | De-Identify (Anononymize) Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `merge` | Merge Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `originate` | Originate/Retain Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `receive` | Receive/Retain Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `transform` | Transform/Translate Record Lifecycle Event |
| `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle` | `verify` | Verify Record Lifecycle Event |
