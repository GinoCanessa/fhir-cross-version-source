Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### DeviceMetricOperationalStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | DeviceMetricOperationalStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/metric-operational-status` |
| Version | 1.0.2 |
| Description | Describes the operational status of the DeviceMetric. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `236` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DeviceMetric` | `DeviceMetric.operationalStatus` | `http://hl7.org/fhir/ValueSet/metric-operational-status` | `Required` | on \| off \| standby |

### Referenced Systems

* `http://hl7.org/fhir/metric-operational-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DeviceMetricOperationalStatus](/docs/R2/ValueSets/DeviceMetricOperationalStatus.md)<br/> `http://hl7.org/fhir/ValueSet/metric-operational-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `67`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `223`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DeviceMetricOperationalStatus](/docs/R3/ValueSets/DeviceMetricOperationalStatus.md)<br/> `http://hl7.org/fhir/ValueSet/metric-operational-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `401`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `624`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [DeviceMetricOperationalStatus](/docs/R4/ValueSets/DeviceMetricOperationalStatus.md)<br/> `http://hl7.org/fhir/ValueSet/metric-operational-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1621`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1622`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DeviceMetricOperationalStatus](/docs/R4B/ValueSets/DeviceMetricOperationalStatus.md)<br/> `http://hl7.org/fhir/ValueSet/metric-operational-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `864`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1125`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [DeviceMetricOperationalStatus](/docs/R5/ValueSets/DeviceMetricOperationalStatus.md)<br/> `http://hl7.org/fhir/ValueSet/metric-operational-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set DeviceMetricOperationalStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 DeviceMetricOperationalStatus| Relationship | [R3 DeviceMetricOperationalStatus](/docs/R3/ValueSets/DeviceMetricOperationalStatus.md)| Relationship | [R4 DeviceMetricOperationalStatus](/docs/R4/ValueSets/DeviceMetricOperationalStatus.md)| Relationship | [R4B DeviceMetricOperationalStatus](/docs/R4B/ValueSets/DeviceMetricOperationalStatus.md)| Relationship | [R5 DeviceMetricOperationalStatus](/docs/R5/ValueSets/DeviceMetricOperationalStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/metric-operational-status`
| **`on`**| _Equivalent_ <br/>(513/1858)| `on`| _Equivalent_ <br/>(3619/5906)| `on`| _Equivalent_ <br/>(16640/16641)| `on`| _Equivalent_ <br/>(8003/10307)| `on`
| **`off`**| _Equivalent_ <br/>(512/1857)| `off`| _Equivalent_ <br/>(3618/5905)| `off`| _Equivalent_ <br/>(16642/16643)| `off`| _Equivalent_ <br/>(8002/10306)| `off`
| **`standby`**| _Equivalent_ <br/>(511/1859)| `standby`| _Equivalent_ <br/>(3616/5903)| `standby`| _Equivalent_ <br/>(16644/16645)| `standby`| _Equivalent_ <br/>(8000/10304)| `standby`
| *3 of 3 codes used* | | *3 of 4 codes used* <br/>remaining codes:<br/>`entered-in-error`| | *3 of 4 codes used* <br/>remaining codes:<br/>`entered-in-error`| | *3 of 4 codes used* <br/>remaining codes:<br/>`entered-in-error`| | *3 of 4 codes used* <br/>remaining codes:<br/>`entered-in-error`

