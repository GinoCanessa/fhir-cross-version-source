Comparison of 
Generated at Monday, April 14, 2025 6:17:21 PM

### FHIRDeviceStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | FHIRDeviceStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/device-status` |
| Version | 3.0.2 |
| Description | The availability status of the device. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `1187` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Device` | `Device.status` | `http://hl7.org/fhir/ValueSet/device-status` | `Required` | active \| inactive \| entered-in-error \| unknown |

### Referenced Systems

* `http://hl7.org/fhir/device-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DeviceStatus](/docs/R2/ValueSets/DeviceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/devicestatus\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `54`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `213`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [FHIRDeviceStatus](/docs/R3/ValueSets/FHIRDeviceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/device-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `390`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `613`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [FHIRDeviceStatus](/docs/R4/ValueSets/FHIRDeviceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/device-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1473`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1474`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [FHIRDeviceStatus](/docs/R4B/ValueSets/FHIRDeviceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/device-status\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `853`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1114`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [FHIRDeviceStatus](/docs/R5/ValueSets/FHIRDeviceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/device-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set FHIRDeviceStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 DeviceStatus](/docs/R2/ValueSets/DeviceStatus.md)| Relationship | R3 FHIRDeviceStatus| Relationship | [R4 FHIRDeviceStatus](/docs/R4/ValueSets/FHIRDeviceStatus.md)| Relationship | [R4B FHIRDeviceStatus](/docs/R4B/ValueSets/FHIRDeviceStatus.md)| Relationship | [R5 FHIRDeviceStatus](/docs/R5/ValueSets/FHIRDeviceStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/device-status`
| `available`| _Equivalent_ <br/>(422/1792)| **`active`**| _Equivalent_ <br/>(3552/5838)| `active`| _Equivalent_ <br/>(15772/15773)| `active`| _Equivalent_ <br/>(7948/10256)| `active`
| `not-available`| _Equivalent_ <br/>(424/1794)| **`inactive`**| _Equivalent_ <br/>(3551/5837)| `inactive`| _Equivalent_ <br/>(15774/15775)| `inactive`| _Equivalent_ <br/>(7950/10255)| `inactive`
| `entered-in-error`| _Equivalent_ <br/>(423/1793)| **`entered-in-error`**| _Equivalent_ <br/>(3553/5839)| `entered-in-error`| _Equivalent_ <br/>(15776/15777)| `entered-in-error`| _Equivalent_ <br/>(7949/10257)| `entered-in-error`
| | | **`unknown`**| _Equivalent_ <br/>(3554/5840)| `unknown`| _Equivalent_ <br/>(15778/15779)| `unknown`| | | 
| *3 of 3 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *3 of 3 codes used* 

