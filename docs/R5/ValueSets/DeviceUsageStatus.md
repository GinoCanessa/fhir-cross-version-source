Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### DeviceUsageStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | DeviceUsageStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/deviceusage-status` |
| Version | 5.0.0 |
| Description | A coded concept indicating the current status of the Device Usage. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4498` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DeviceUsage` | `DeviceUsage.status` | `http://hl7.org/fhir/ValueSet/deviceusage-status\|5.0.0` | `Required` | active \| completed \| not-done \| entered-in-error + |
| `http://hl7.org/fhir/StructureDefinition/DeviceUsage` | `DeviceUsage.usageStatus` | `http://hl7.org/fhir/ValueSet/deviceusage-status\|5.0.0` | `Required` | The status of the device usage, for example always, sometimes, never. This is not the same as the status of the statement |

### Referenced Systems

* `http://hl7.org/fhir/deviceusage-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [DeviceUseStatementStatus](/docs/R3/ValueSets/DeviceUseStatementStatus.md)<br/> `http://hl7.org/fhir/ValueSet/device-statement-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `396`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `619`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceUseStatementStatus](/docs/R4/ValueSets/DeviceUseStatementStatus.md)<br/> `http://hl7.org/fhir/ValueSet/device-statement-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1471`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1472`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceUseStatementStatus](/docs/R4B/ValueSets/DeviceUseStatementStatus.md)<br/> `http://hl7.org/fhir/ValueSet/device-statement-status\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `860`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1121`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceUsageStatus](/docs/R5/ValueSets/DeviceUsageStatus.md)<br/> `http://hl7.org/fhir/ValueSet/deviceusage-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set DeviceUsageStatus from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 DeviceUseStatementStatus](/docs/R3/ValueSets/DeviceUseStatementStatus.md)| Relationship | [R4 DeviceUseStatementStatus](/docs/R4/ValueSets/DeviceUseStatementStatus.md)| Relationship | [R4B DeviceUseStatementStatus](/docs/R4B/ValueSets/DeviceUseStatementStatus.md)| Relationship | R5 DeviceUsageStatus
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/deviceusage-status`
| | | `active`| _Equivalent_ <br/>(3592/5879)| `active`| _Equivalent_ <br/>(15760/15761)| `active`| _Equivalent_ <br/>(7984/10285)| **`active`**
| | | `completed`| _Equivalent_ <br/>(3593/5880)| `completed`| _Equivalent_ <br/>(15762/15763)| `completed`| _Equivalent_ <br/>(7985/10286)| **`completed`**
| | | | | | | | | **`not-done`**
| | | `entered-in-error`| _Equivalent_ <br/>(3594/5881)| `entered-in-error`| _Equivalent_ <br/>(15764/15765)| `entered-in-error`| _Equivalent_ <br/>(7986/10287)| **`entered-in-error`**
| | | `intended`| _Equivalent_ <br/>(3591/5878)| `intended`| _Equivalent_ <br/>(15766/15767)| `intended`| _Equivalent_ <br/>(7983/10288)| **`intended`**
| | | `stopped`| _Equivalent_ <br/>(3590/5877)| `stopped`| _Equivalent_ <br/>(15768/15769)| `stopped`| _Equivalent_ <br/>(7982/10291)| **`stopped`**
| | | `on-hold`| _Equivalent_ <br/>(3595/5882)| `on-hold`| _Equivalent_ <br/>(15770/15771)| `on-hold`| _Equivalent_ <br/>(7987/10290)| **`on-hold`**
| | | *6 of 6 codes used* | | *6 of 6 codes used* | | *6 of 6 codes used* | | *7 of 7 codes used* 

