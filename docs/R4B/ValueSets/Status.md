Comparison of 
Generated at Monday, April 14, 2025 6:17:36 PM

### status

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | status |
| Canonical URL | `http://hl7.org/fhir/ValueSet/verificationresult-status` |
| Version | 4.3.0 |
| Description | The validation status of the target |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4198` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/VerificationResult` | `VerificationResult.status` | `http://hl7.org/fhir/ValueSet/verificationresult-status\|4.3.0` | `Required` | attested \| validated \| in-process \| req-revalid \| val-fail \| reval-fail |

### Referenced Systems

* `http://hl7.org/fhir/verificationresult-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [status](/docs/R4/ValueSets/Status.md)<br/> `http://hl7.org/fhir/ValueSet/verificationresult-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1783`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1784`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [status](/docs/R4B/ValueSets/Status.md)<br/> `http://hl7.org/fhir/ValueSet/verificationresult-status\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1024`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1285`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [VerificationResultStatus](/docs/R5/ValueSets/VerificationResultStatus.md)<br/> `http://hl7.org/fhir/ValueSet/verificationresult-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set status from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | [R4 status](/docs/R4/ValueSets/Status.md)| Relationship | R4B status| Relationship | [R5 VerificationResultStatus](/docs/R5/ValueSets/VerificationResultStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/verificationresult-status`
| | | | | `attested`| _Equivalent_ <br/>(18406/18407)| **`attested`**| _Equivalent_ <br/>(9654/11976)| `attested`
| | | | | `validated`| _Equivalent_ <br/>(18408/18409)| **`validated`**| _Equivalent_ <br/>(9652/11982)| `validated`
| | | | | `in-process`| _Equivalent_ <br/>(18410/18411)| **`in-process`**| _Equivalent_ <br/>(9657/11978)| `in-process`
| | | | | `req-revalid`| _Equivalent_ <br/>(18412/18413)| **`req-revalid`**| _Equivalent_ <br/>(9655/11979)| `req-revalid`
| | | | | `val-fail`| _Equivalent_ <br/>(18414/18415)| **`val-fail`**| _Equivalent_ <br/>(9653/11981)| `val-fail`
| | | | | `reval-fail`| _Equivalent_ <br/>(18416/18417)| **`reval-fail`**| _Equivalent_ <br/>(9656/11980)| `reval-fail`
| | | | | *6 of 6 codes used* | | *6 of 6 codes used* | | *6 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`

