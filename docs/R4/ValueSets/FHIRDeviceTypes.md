Comparison of 
Generated at Monday, April 14, 2025 6:17:26 PM

### FHIRDeviceTypes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | FHIRDeviceTypes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/device-kind` |
| Version | 4.0.1 |
| Description | Codes used to identify medical devices. Includes concepts from SNOMED CT (http://www.snomed.org/) where concept is-a 49062001 (Device)  and is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `2376` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ChargeItem` | `ChargeItem.product[x]` | `http://hl7.org/fhir/ValueSet/device-kind` | `Example` | Product charged |
| `http://hl7.org/fhir/StructureDefinition/DeviceDefinition` | `DeviceDefinition.type` | `http://hl7.org/fhir/ValueSet/device-kind` | `Example` | What kind of device or device system this is |
| `http://hl7.org/fhir/StructureDefinition/DeviceRequest` | `DeviceRequest.code[x]` | `http://hl7.org/fhir/ValueSet/device-kind` | `Example` | Device requested |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.usedCode` | `http://hl7.org/fhir/ValueSet/device-kind` | `Example` | Coded items used during the procedure |
| `http://hl7.org/fhir/StructureDefinition/observation-deviceCode` | `Extension.value[x]` | `http://hl7.org/fhir/ValueSet/device-kind` | `Example` | Value of extension |

### Expansion Failure

Failed to expand this value set: Expansion is limited
