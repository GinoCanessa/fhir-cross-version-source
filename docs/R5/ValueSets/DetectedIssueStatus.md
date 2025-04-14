Comparison of 
Generated at Monday, April 14, 2025 6:17:44 PM

### DetectedIssueStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | DetectedIssueStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/detectedissue-status` |
| Version | 5.0.0 |
| Description | Indicates the status of a detected issue |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4473` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DetectedIssue` | `DetectedIssue.status` | `http://hl7.org/fhir/ValueSet/detectedissue-status\|5.0.0` | `Required` | preliminary \| final \| entered-in-error \| mitigated |

### Referenced Systems

* `http://hl7.org/fhir/observation-status`
* `http://hl7.org/fhir/detectedissue-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ObservationStatus](/docs/R2/ValueSets/ObservationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/observation-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `108`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `264`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ObservationStatus](/docs/R3/ValueSets/ObservationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/observation-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `394`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `617`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [ObservationStatus](/docs/R4/ValueSets/ObservationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/observation-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1639`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1640`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ObservationStatus](/docs/R4B/ValueSets/ObservationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/observation-status\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `859`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1120`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DetectedIssueStatus](/docs/R5/ValueSets/DetectedIssueStatus.md)<br/> `http://hl7.org/fhir/ValueSet/detectedissue-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set DetectedIssueStatus from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ObservationStatus](/docs/R2/ValueSets/ObservationStatus.md)| Relationship | [R3 ObservationStatus](/docs/R3/ValueSets/ObservationStatus.md)| Relationship | [R4 ObservationStatus](/docs/R4/ValueSets/ObservationStatus.md)| Relationship | [R4B ObservationStatus](/docs/R4B/ValueSets/ObservationStatus.md)| Relationship | R5 DetectedIssueStatus
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/observation-status`
| `preliminary`| _Equivalent_ <br/>(905/2273)| `preliminary`| _Equivalent_ <br/>(3578/5864)| `preliminary`| _Equivalent_ <br/>(16708/16709)| `preliminary`| _Equivalent_ <br/>(7979/10283)| **`preliminary`**
| `final`| _Equivalent_ <br/>(902/2272)| `final`| _Equivalent_ <br/>(3575/5861)| `final`| _Equivalent_ <br/>(16710/16711)| `final`| _Equivalent_ <br/>(7978/10282)| **`final`**
| `entered-in-error`| _Equivalent_ <br/>(906/2271)| `entered-in-error`| _Equivalent_ <br/>(3579/5865)| `entered-in-error`| _Equivalent_ <br/>(16718/16719)| `entered-in-error`| _Equivalent_ <br/>(7977/10281)| **`entered-in-error`**
| <td colspan="8">**R5** System: `http://hl7.org/fhir/detectedissue-status`
| | | | | | | | | **`mitigated`**
| *3 of 7 codes used* <br/>remaining codes:<br/>`amended`, `cancelled`, `registered`, `unknown`| | *3 of 8 codes used* <br/>remaining codes:<br/>`amended`, `cancelled`, `corrected`, `registered`, `unknown`| | *3 of 8 codes used* <br/>remaining codes:<br/>`amended`, `cancelled`, `corrected`, `registered`, `unknown`| | *3 of 8 codes used* <br/>remaining codes:<br/>`amended`, `cancelled`, `corrected`, `registered`, `unknown`| | *4 of 4 codes used* 

