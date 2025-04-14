Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### ObservationReferenceRangeMeaningCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ObservationReferenceRangeMeaningCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/referencerange-meaning` |
| Version | 5.0.0 |
| Description | This value set defines a set of codes that can be used to indicate the meaning/use of a reference range for a particular target population. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4836` |
| Database Concept Count | `13` |
| Database Active Concept Count | `13` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Observation` | `Observation.referenceRange.type` | `http://hl7.org/fhir/ValueSet/referencerange-meaning` | `Preferred` | Reference range qualifier |
| `http://hl7.org/fhir/StructureDefinition/ObservationDefinition` | `ObservationDefinition.qualifiedValue.context` | `http://hl7.org/fhir/ValueSet/referencerange-meaning` | `Extensible` | Context qualifier for the set of qualified values |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/referencerange-meaning`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/referencerange-meaning` | `endocrine` | Endocrine |
| `http://terminology.hl7.org/CodeSystem/referencerange-meaning` | `follicular` | Follicular Stage |
| `http://terminology.hl7.org/CodeSystem/referencerange-meaning` | `luteal` | Luteal |
| `http://terminology.hl7.org/CodeSystem/referencerange-meaning` | `midcycle` | MidCycle |
| `http://terminology.hl7.org/CodeSystem/referencerange-meaning` | `normal` | Normal Range |
| `http://terminology.hl7.org/CodeSystem/referencerange-meaning` | `post` | Post Therapeutic Desired Level |
| `http://terminology.hl7.org/CodeSystem/referencerange-meaning` | `postmenopausal` | Post-Menopause |
| `http://terminology.hl7.org/CodeSystem/referencerange-meaning` | `pre` | Pre Therapeutic Desired Level |
| `http://terminology.hl7.org/CodeSystem/referencerange-meaning` | `pre-puberty` | Pre-Puberty |
| `http://terminology.hl7.org/CodeSystem/referencerange-meaning` | `recommended` | Recommended Range |
| `http://terminology.hl7.org/CodeSystem/referencerange-meaning` | `therapeutic` | Therapeutic Desired Level |
| `http://terminology.hl7.org/CodeSystem/referencerange-meaning` | `treatment` | Treatment Range |
| `http://terminology.hl7.org/CodeSystem/referencerange-meaning` | `type` | Type |
