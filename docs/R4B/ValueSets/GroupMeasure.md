Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### GroupMeasure

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | GroupMeasure |
| Canonical URL | `http://hl7.org/fhir/ValueSet/group-measure` |
| Version | 4.3.0 |
| Description | Possible group measure aggregates (E.g. Mean, Median). |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3801` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/EvidenceVariable` | `EvidenceVariable.characteristic.groupMeasure` | `http://hl7.org/fhir/ValueSet/group-measure\|4.3.0` | `Required` | mean \| median \| mean-of-mean \| mean-of-median \| median-of-mean \| median-of-median |
| `http://hl7.org/fhir/StructureDefinition/ResearchElementDefinition` | `ResearchElementDefinition.characteristic.studyEffectiveGroupMeasure` | `http://hl7.org/fhir/ValueSet/group-measure\|4.3.0` | `Required` | mean \| median \| mean-of-mean \| mean-of-median \| median-of-mean \| median-of-median |
| `http://hl7.org/fhir/StructureDefinition/ResearchElementDefinition` | `ResearchElementDefinition.characteristic.participantEffectiveGroupMeasure` | `http://hl7.org/fhir/ValueSet/group-measure\|4.3.0` | `Required` | mean \| median \| mean-of-mean \| mean-of-median \| median-of-mean \| median-of-median |

### Referenced Systems

* `http://hl7.org/fhir/group-measure`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [GroupMeasure](/docs/R4/ValueSets/GroupMeasure.md)<br/> `http://hl7.org/fhir/ValueSet/group-measure\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1523`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1524`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [GroupMeasure](/docs/R4B/ValueSets/GroupMeasure.md)<br/> `http://hl7.org/fhir/ValueSet/group-measure\|4.3.0` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set GroupMeasure from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | [R4 GroupMeasure](/docs/R4/ValueSets/GroupMeasure.md)| Relationship | R4B GroupMeasure| Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/group-measure`
| | | | | `mean`| _Equivalent_ <br/>(16092/16093)| **`mean`**| | | 
| | | | | `median`| _Equivalent_ <br/>(16094/16095)| **`median`**| | | 
| | | | | `mean-of-mean`| _Equivalent_ <br/>(16096/16097)| **`mean-of-mean`**| | | 
| | | | | `mean-of-median`| _Equivalent_ <br/>(16098/16099)| **`mean-of-median`**| | | 
| | | | | `median-of-mean`| _Equivalent_ <br/>(16100/16101)| **`median-of-mean`**| | | 
| | | | | `median-of-median`| _Equivalent_ <br/>(16102/16103)| **`median-of-median`**| | | 
| | | | | *6 of 6 codes used* | | *6 of 6 codes used* | | 

