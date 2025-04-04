Comparison of 
Generated at Friday, April 4, 2025 2:58:38 PM

### FHIR Device Types

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | FHIR Device Types |
| Canonical URL | `http://hl7.org/fhir/ValueSet/device-kind` |
| Version | 3.0.2 |
| Description | Codes used to identify medical devices. Include codes from [SNOMED CT](http://snomed.info/sct) where concept is-a 49062001 (Device)  and is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `1184` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Device` | `Device.type` | `http://hl7.org/fhir/ValueSet/device-kind` | `Example` | What kind of device this is |
| `http://hl7.org/fhir/StructureDefinition/DeviceComponent` | `DeviceComponent.type` | `http://hl7.org/fhir/ValueSet/device-kind` | `Preferred` | What kind of component it is |
| `http://hl7.org/fhir/StructureDefinition/DeviceRequest` | `DeviceRequest.code[x]` | `http://hl7.org/fhir/ValueSet/device-kind` | `Example` | Device requested |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.usedCode` | `http://hl7.org/fhir/ValueSet/device-kind` | `Example` | Coded items used during the procedure |

### Expansion Failure

Failed to expand this value set: Expansion is limited
