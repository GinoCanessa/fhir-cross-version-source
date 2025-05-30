Comparison of 
Generated at Monday, April 14, 2025 6:17:44 PM

### UsageContextType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | UsageContextType |
| Canonical URL | `http://terminology.hl7.org/ValueSet/usage-context-type` |
| Version | 0.5.0 |
| Description | A code that specifies a type of context being specified by a usage context. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `5033` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/UsageContext` | `UsageContext.code` | `http://terminology.hl7.org/ValueSet/usage-context-type` | `Extensible` | Type of context being specified |
| `http://hl7.org/fhir/StructureDefinition/EvidenceVariable` | `EvidenceVariable.characteristic.definitionByTypeAndValue.type` | `http://terminology.hl7.org/ValueSet/usage-context-type` | `Example` | Expresses the type of characteristic |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/usage-context-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/usage-context-type` | `age` | Age Range |
| `http://terminology.hl7.org/CodeSystem/usage-context-type` | `focus` | Clinical Focus |
| `http://terminology.hl7.org/CodeSystem/usage-context-type` | `gender` | Gender |
| `http://terminology.hl7.org/CodeSystem/usage-context-type` | `program` | Program |
| `http://terminology.hl7.org/CodeSystem/usage-context-type` | `species` | Species |
| `http://terminology.hl7.org/CodeSystem/usage-context-type` | `task` | Workflow Task |
| `http://terminology.hl7.org/CodeSystem/usage-context-type` | `user` | User Type |
| `http://terminology.hl7.org/CodeSystem/usage-context-type` | `venue` | Clinical Venue |
| `http://terminology.hl7.org/CodeSystem/usage-context-type` | `workflow` | Workflow Setting |
