Comparison of 
Generated at Friday, April 4, 2025 2:58:59 PM

### TestScriptScopePhaseType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | TestScriptScopePhaseType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/testscript-scope-phase-codes` |
| Version | 5.0.0 |
| Description | The phase of testing for this artifact. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4969` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/TestPlan` | `TestPlan.category` | `http://hl7.org/fhir/ValueSet/testscript-scope-phase-codes` | `Example` | The category of the Test Plan - can be acceptance, unit, performance |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.scope.phase` | `http://hl7.org/fhir/ValueSet/testscript-scope-phase-codes` | `Extensible` | unit \| integration \| production |

### Referenced Systems

* `http://hl7.org/fhir/testscript-scope-phase-codes`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/testscript-scope-phase-codes` | `integration` | Integration |
| `http://hl7.org/fhir/testscript-scope-phase-codes` | `production` | Production |
| `http://hl7.org/fhir/testscript-scope-phase-codes` | `unit` | Unit |
