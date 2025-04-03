Comparison of 
Generated at Thursday, April 3, 2025 8:18:05 AM

### IssueSeverity

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | IssueSeverity |
| Canonical URL | `http://hl7.org/fhir/ValueSet/issue-severity` |
| Version | 1.0.2 |
| Description | How the issue affects the success of the action. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `201` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/OperationOutcome` | `OperationOutcome.issue.severity` | `http://hl7.org/fhir/ValueSet/issue-severity` | `Required` | fatal \| error \| warning \| information |

### Referenced Systems

* `http://hl7.org/fhir/issue-severity`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [IssueSeverity](/docs/R2/ValueSets/IssueSeverity.md)<br/> `http://hl7.org/fhir/ValueSet/issue-severity\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `112`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `268`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [IssueSeverity](/docs/R3/ValueSets/IssueSeverity.md)<br/> `http://hl7.org/fhir/ValueSet/issue-severity\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `461`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `685`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [IssueSeverity](/docs/R4/ValueSets/IssueSeverity.md)<br/> `http://hl7.org/fhir/ValueSet/issue-severity\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1555`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1556`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [IssueSeverity](/docs/R4B/ValueSets/IssueSeverity.md)<br/> `http://hl7.org/fhir/ValueSet/issue-severity\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `947`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1208`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [IssueSeverity](/docs/R5/ValueSets/IssueSeverity.md)<br/> `http://hl7.org/fhir/ValueSet/issue-severity\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set IssueSeverity from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 IssueSeverity| Relationship | [R3 IssueSeverity](/docs/R3/ValueSets/IssueSeverity.md)| Relationship | [R4 IssueSeverity](/docs/R4/ValueSets/IssueSeverity.md)| Relationship | [R4B IssueSeverity](/docs/R4B/ValueSets/IssueSeverity.md)| Relationship | [R5 IssueSeverity](/docs/R5/ValueSets/IssueSeverity.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/issue-severity`
| **`fatal`**| _Equivalent_ <br/>(944/2312)| `fatal`| _Equivalent_ <br/>(4117/6463)| `fatal`| _Equivalent_ <br/>(16256/16257)| `fatal`| _Equivalent_ <br/>(9150/11461)| `fatal`
| **`error`**| _Equivalent_ <br/>(943/2311)| `error`| _Equivalent_ <br/>(4116/6462)| `error`| _Equivalent_ <br/>(16258/16259)| `error`| _Equivalent_ <br/>(9149/11460)| `error`
| **`warning`**| _Equivalent_ <br/>(941/2309)| `warning`| _Equivalent_ <br/>(4114/6460)| `warning`| _Equivalent_ <br/>(16260/16261)| `warning`| _Equivalent_ <br/>(9147/11464)| `warning`
| **`information`**| _Equivalent_ <br/>(942/2310)| `information`| _Equivalent_ <br/>(4115/6461)| `information`| _Equivalent_ <br/>(16262/16263)| `information`| _Equivalent_ <br/>(9148/11462)| `information`
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 5 codes used* <br/>remaining codes:<br/>`success`

