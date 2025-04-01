Comparison of 
Generated at Tuesday, April 1, 2025 1:39:12 PM

### Device Metric and Component Types

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Device Metric and Component Types |
| Canonical URL | `http://hl7.org/fhir/ValueSet/devicemetric-type` |
| Version | 3.0.2 |
| Description | Codes used to identify health care device metric types and units and component types as part of the ISO/IEEE 11073-10101 Medical Device Communication Nomenclature. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `1188` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DeviceMetric` | `DeviceMetric.type` | `http://hl7.org/fhir/ValueSet/devicemetric-type` | `Preferred` | Identity of metric, for example Heart Rate or PEEP Setting |
| `http://hl7.org/fhir/StructureDefinition/DeviceMetric` | `DeviceMetric.unit` | `http://hl7.org/fhir/ValueSet/devicemetric-type` | `Preferred` | Unit of Measure for the Metric |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/devicemetric-type|3.0.2: Operation expand failed: creating the required expansion failed with message "The ValueSet expander cannot find codesystem 'urn:iso:std:iso:11073:10101', so the expansion cannot be completed.".
