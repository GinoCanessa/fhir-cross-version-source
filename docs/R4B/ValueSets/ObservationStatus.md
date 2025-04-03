Comparison of 
Generated at Thursday, April 3, 2025 8:18:24 AM

### ObservationStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ObservationStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/observation-status` |
| Version | 4.3.0 |
| Description | Codes providing the status of an observation. |
| Status | `Active` |
| Has Escape Valve Code | `True` |
| Database Key | `3966` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DetectedIssue` | `DetectedIssue.status` | `http://hl7.org/fhir/ValueSet/observation-status\|4.3.0` | `Required` | registered \| preliminary \| final \| amended + |
| `http://hl7.org/fhir/StructureDefinition/Observation` | `Observation.status` | `http://hl7.org/fhir/ValueSet/observation-status\|4.3.0` | `Required` | registered \| preliminary \| final \| amended + |
| `http://hl7.org/fhir/StructureDefinition/RiskAssessment` | `RiskAssessment.status` | `http://hl7.org/fhir/ValueSet/observation-status\|4.3.0` | `Required` | registered \| preliminary \| final \| amended + |

### Referenced Systems

* `http://hl7.org/fhir/observation-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ObservationStatus](/docs/R2/ValueSets/ObservationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/observation-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `108`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `264`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ObservationStatus](/docs/R3/ValueSets/ObservationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/observation-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `394`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `617`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ObservationStatus](/docs/R4/ValueSets/ObservationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/observation-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1639`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1640`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ObservationStatus](/docs/R4B/ValueSets/ObservationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/observation-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `943`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1204`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DetectedIssueStatus](/docs/R5/ValueSets/DetectedIssueStatus.md)<br/> `http://hl7.org/fhir/ValueSet/detectedissue-status\|5.0.0` 
| [ObservationStatus](/docs/R2/ValueSets/ObservationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/observation-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `108`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `264`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ObservationStatus](/docs/R3/ValueSets/ObservationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/observation-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `394`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `617`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ObservationStatus](/docs/R4/ValueSets/ObservationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/observation-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1639`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1640`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ObservationStatus](/docs/R4B/ValueSets/ObservationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/observation-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `943`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1204`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ObservationStatus](/docs/R5/ValueSets/ObservationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/observation-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ObservationStatus from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ObservationStatus](/docs/R2/ValueSets/ObservationStatus.md)| Relationship | [R3 ObservationStatus](/docs/R3/ValueSets/ObservationStatus.md)| Relationship | [R4 ObservationStatus](/docs/R4/ValueSets/ObservationStatus.md)| Relationship | R4B ObservationStatus| Relationship | [R5 DetectedIssueStatus](/docs/R5/ValueSets/DetectedIssueStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/observation-status`
| `registered`| _Equivalent_ <br/>(903/2274)| `registered`| _Equivalent_ <br/>(3576/5862)| `registered`| _Equivalent_ <br/>(16706/16707)| **`registered`**| _Equivalent_ <br/>(9106/11417)| `registered`
| `preliminary`| _Equivalent_ <br/>(905/2273)| `preliminary`| _Equivalent_ <br/>(3578/5864)| `preliminary`| _Equivalent_ <br/>(16708/16709)| **`preliminary`**| _Equivalent_ <br/>(9108/11419)| `preliminary`
| `final`| _Equivalent_ <br/>(902/2272)| `final`| _Equivalent_ <br/>(3575/5861)| `final`| _Equivalent_ <br/>(16710/16711)| **`final`**| _Equivalent_ <br/>(9105/11416)| `final`
| `amended`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(900)<hr/>←←←← _Equivalent_ ←←←← <br/>(2268) | `amended`| _Equivalent_ <br/>(3574/5860)| `amended`| _Equivalent_ <br/>(16712/16713)| **`amended`**| _Equivalent_ <br/>(9104/11415)| `amended`
| `amended`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(901)<hr/>←←←← _Equivalent_ ←←←← <br/>(2270) | `corrected`| _Equivalent_ <br/>(3580/5866)| `corrected`| _Equivalent_ <br/>(16714/16715)| **`corrected`**| _Equivalent_ <br/>(9110/11421)| `corrected`
| `cancelled`| _Equivalent_ <br/>(904/2269)| `cancelled`| _Equivalent_ <br/>(3577/5863)| `cancelled`| _Equivalent_ <br/>(16716/16717)| **`cancelled`**| _Equivalent_ <br/>(9107/11418)| `cancelled`
| `entered-in-error`| _Equivalent_ <br/>(906/2271)| `entered-in-error`| _Equivalent_ <br/>(3579/5865)| `entered-in-error`| _Equivalent_ <br/>(16718/16719)| **`entered-in-error`**| _Equivalent_ <br/>(9109/11420)| `entered-in-error`
| `unknown`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(907)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2275) | `unknown`| _Equivalent_ <br/>(3581/5867)| `unknown`| _Equivalent_ <br/>(16720/16721)| **`unknown`**| _Equivalent_ <br/>(9111/11422)| `unknown`
| *7 of 7 codes used* | | *8 of 8 codes used* | | *8 of 8 codes used* | | *8 of 8 codes used* | | *8 of 4 codes used* 


#### Map Group 1

This group is centered on the Value Set ObservationStatus from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ObservationStatus](/docs/R2/ValueSets/ObservationStatus.md)| Relationship | [R3 ObservationStatus](/docs/R3/ValueSets/ObservationStatus.md)| Relationship | [R4 ObservationStatus](/docs/R4/ValueSets/ObservationStatus.md)| Relationship | R4B ObservationStatus| Relationship | [R5 ObservationStatus](/docs/R5/ValueSets/ObservationStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/observation-status`
| `registered`| _Equivalent_ <br/>(903/2274)| `registered`| _Equivalent_ <br/>(3576/5862)| `registered`| _Equivalent_ <br/>(16706/16707)| **`registered`**| _Equivalent_ <br/>(9106/11417)| `registered`
| `preliminary`| _Equivalent_ <br/>(905/2273)| `preliminary`| _Equivalent_ <br/>(3578/5864)| `preliminary`| _Equivalent_ <br/>(16708/16709)| **`preliminary`**| _Equivalent_ <br/>(9108/11419)| `preliminary`
| `final`| _Equivalent_ <br/>(902/2272)| `final`| _Equivalent_ <br/>(3575/5861)| `final`| _Equivalent_ <br/>(16710/16711)| **`final`**| _Equivalent_ <br/>(9105/11416)| `final`
| `amended`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(900)<hr/>←←←← _Equivalent_ ←←←← <br/>(2268) | `amended`| _Equivalent_ <br/>(3574/5860)| `amended`| _Equivalent_ <br/>(16712/16713)| **`amended`**| _Equivalent_ <br/>(9104/11415)| `amended`
| `amended`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(901)<hr/>←←←← _Equivalent_ ←←←← <br/>(2270) | `corrected`| _Equivalent_ <br/>(3580/5866)| `corrected`| _Equivalent_ <br/>(16714/16715)| **`corrected`**| _Equivalent_ <br/>(9110/11421)| `corrected`
| `cancelled`| _Equivalent_ <br/>(904/2269)| `cancelled`| _Equivalent_ <br/>(3577/5863)| `cancelled`| _Equivalent_ <br/>(16716/16717)| **`cancelled`**| _Equivalent_ <br/>(9107/11418)| `cancelled`
| `entered-in-error`| _Equivalent_ <br/>(906/2271)| `entered-in-error`| _Equivalent_ <br/>(3579/5865)| `entered-in-error`| _Equivalent_ <br/>(16718/16719)| **`entered-in-error`**| _Equivalent_ <br/>(9109/11420)| `entered-in-error`
| `unknown`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(907)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2275) | `unknown`| _Equivalent_ <br/>(3581/5867)| `unknown`| _Equivalent_ <br/>(16720/16721)| **`unknown`**| _Equivalent_ <br/>(9111/11422)| `unknown`
| *7 of 7 codes used* | | *8 of 8 codes used* | | *8 of 8 codes used* | | *8 of 8 codes used* | | *8 of 8 codes used* 

