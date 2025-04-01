Comparison of 
Generated at Tuesday, April 1, 2025 1:39:35 PM

### UCUMCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | UCUMCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/ucum-units` |
| Version | 5.0.0 |
| Description | Unified Code for Units of Measure (UCUM). This value set includes all UCUM codes |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4988` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SampledData` | `SampledData.intervalUnit` | `http://hl7.org/fhir/ValueSet/ucum-units\|5.0.0` | `Required` | The measurement unit of the interval between samples |
| `http://hl7.org/fhir/StructureDefinition/DeviceMetric` | `DeviceMetric.unit` | `http://hl7.org/fhir/ValueSet/ucum-units` | `Preferred` | Unit of Measure for the Metric |
| `http://hl7.org/fhir/StructureDefinition/ObservationDefinition` | `ObservationDefinition.permittedUnit` | `http://hl7.org/fhir/ValueSet/ucum-units` | `Preferred` | Unit for quantitative results |
| `http://hl7.org/fhir/StructureDefinition/ObservationDefinition` | `ObservationDefinition.component.permittedUnit` | `http://hl7.org/fhir/ValueSet/ucum-units` | `Preferred` | Unit for quantitative results |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/ucum-units|5.0.0: Operation expand failed: creating the required expansion failed with message "The ValueSet expander cannot find codesystem 'http://unitsofmeasure.org', so the expansion cannot be completed.".
