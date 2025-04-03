Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### DeviceMetricAndComponentTypes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | DeviceMetricAndComponentTypes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/devicemetric-type` |
| Version | 4.0.1 |
| Description | Codes used to identify health care device metric types and units and component types as part of the ISO/IEEE 11073-10101 Medical Device Communication Nomenclature. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `2383` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DeviceMetric` | `DeviceMetric.type` | `http://hl7.org/fhir/ValueSet/devicemetric-type` | `Preferred` | Identity of metric, for example Heart Rate or PEEP Setting |
| `http://hl7.org/fhir/StructureDefinition/DeviceMetric` | `DeviceMetric.unit` | `http://hl7.org/fhir/ValueSet/devicemetric-type` | `Preferred` | Unit of Measure for the Metric |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/devicemetric-type|4.0.1: Operation expand failed: creating the required expansion failed with message "The ValueSet expander cannot find codesystem 'urn:iso:std:iso:11073:10101', so the expansion cannot be completed.".
