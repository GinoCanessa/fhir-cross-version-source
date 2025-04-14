Comparison of 
Generated at Monday, April 14, 2025 6:17:26 PM

### DeviceNameType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | DeviceNameType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/device-nametype` |
| Version | 4.0.1 |
| Description | The type of name the device is referred by. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `2377` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Device` | `Device.deviceName.type` | `http://hl7.org/fhir/ValueSet/device-nametype\|4.0.1` | `Required` | udi-label-name \| user-friendly-name \| patient-reported-name \| manufacturer-name \| model-name \| other |
| `http://hl7.org/fhir/StructureDefinition/DeviceDefinition` | `DeviceDefinition.deviceName.type` | `http://hl7.org/fhir/ValueSet/device-nametype\|4.0.1` | `Required` | udi-label-name \| user-friendly-name \| patient-reported-name \| manufacturer-name \| model-name \| other |

### Referenced Systems

* `http://hl7.org/fhir/device-nametype`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [DeviceNameType](/docs/R4/ValueSets/DeviceNameType.md)<br/> `http://hl7.org/fhir/ValueSet/device-nametype\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1469`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1470`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DeviceNameType](/docs/R4B/ValueSets/DeviceNameType.md)<br/> `http://hl7.org/fhir/ValueSet/device-nametype\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `852`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1113`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DeviceNameType](/docs/R5/ValueSets/DeviceNameType.md)<br/> `http://hl7.org/fhir/ValueSet/device-nametype\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set DeviceNameType from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | R4 DeviceNameType| Relationship | [R4B DeviceNameType](/docs/R4B/ValueSets/DeviceNameType.md)| Relationship | [R5 DeviceNameType](/docs/R5/ValueSets/DeviceNameType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/device-nametype`
| | | | | **`udi-label-name`**| _Equivalent_ <br/>(15748/15749)| `udi-label-name`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7946)<hr/>←←←← _Equivalent_ ←←←← <br/>(10252) | `registered-name`
| | | | | **`user-friendly-name`**| _Equivalent_ <br/>(15750/15751)| `user-friendly-name`| _Equivalent_ <br/>(7947/10253)| `user-friendly-name`
| | | | | **`patient-reported-name`**| _Equivalent_ <br/>(15752/15753)| `patient-reported-name`| _Equivalent_ <br/>(7945/10254)| `patient-reported-name`
| | | | | **`manufacturer-name`**| _Equivalent_ <br/>(15754/15755)| `manufacturer-name`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7942)<hr/>←←←← _Equivalent_ ←←←← <br/>(10249) | `registered-name`
| | | | | **`model-name`**| _Equivalent_ <br/>(15756/15757)| `model-name`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7943)<hr/>←←←← _Equivalent_ ←←←← <br/>(10250) | `registered-name`
| | | | | **`other`**| _Equivalent_ <br/>(15758/15759)| `other`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7944)<hr/>←←←← _Equivalent_ ←←←← <br/>(10251) | `registered-name`
| | | | | *6 of 6 codes used* | | *6 of 6 codes used* | | *3 of 3 codes used* 

