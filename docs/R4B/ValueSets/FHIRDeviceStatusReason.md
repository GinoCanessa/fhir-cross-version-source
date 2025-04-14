Comparison of 
Generated at Monday, April 14, 2025 6:17:36 PM

### FHIRDeviceStatusReason

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | FHIRDeviceStatusReason |
| Canonical URL | `http://hl7.org/fhir/ValueSet/device-status-reason` |
| Version | 4.3.0 |
| Description | The availability status reason of the device. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3708` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Device` | `Device.statusReason` | `http://hl7.org/fhir/ValueSet/device-status-reason` | `Extensible` | online \| paused \| standby \| offline \| not-ready \| transduc-discon \| hw-discon \| off |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/device-status-reason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/device-status-reason` | `hw-discon` | Hardware Disconnected |
| `http://terminology.hl7.org/CodeSystem/device-status-reason` | `not-ready` | Not Ready |
| `http://terminology.hl7.org/CodeSystem/device-status-reason` | `off` | Off |
| `http://terminology.hl7.org/CodeSystem/device-status-reason` | `offline` | Offline |
| `http://terminology.hl7.org/CodeSystem/device-status-reason` | `online` | Online |
| `http://terminology.hl7.org/CodeSystem/device-status-reason` | `paused` | Paused |
| `http://terminology.hl7.org/CodeSystem/device-status-reason` | `standby` | Standby |
| `http://terminology.hl7.org/CodeSystem/device-status-reason` | `transduc-discon` | Transducer Disconnected |
