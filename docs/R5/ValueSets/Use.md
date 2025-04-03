Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### Use

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | Use |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-use` |
| Version | 5.0.0 |
| Description | The purpose of the Claim: predetermination, preauthorization, claim. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4367` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.use` | `http://hl7.org/fhir/ValueSet/claim-use\|5.0.0` | `Required` | claim \| preauthorization \| predetermination |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.use` | `http://hl7.org/fhir/ValueSet/claim-use\|5.0.0` | `Required` | claim \| preauthorization \| predetermination |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.use` | `http://hl7.org/fhir/ValueSet/claim-use\|5.0.0` | `Required` | claim \| preauthorization \| predetermination |

### Referenced Systems

* `http://hl7.org/fhir/claim-use`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Use](/docs/R2/ValueSets/Use.md)<br/> `http://hl7.org/fhir/ValueSet/claim-use-link\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `21`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `180`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Use](/docs/R3/ValueSets/Use.md)<br/> `http://hl7.org/fhir/ValueSet/claim-use\|3.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `347`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `570`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Use](/docs/R4/ValueSets/Use.md)<br/> `http://hl7.org/fhir/ValueSet/claim-use\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1413`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1414`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Use](/docs/R4B/ValueSets/Use.md)<br/> `http://hl7.org/fhir/ValueSet/claim-use\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `794`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1055`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Use](/docs/R5/ValueSets/Use.md)<br/> `http://hl7.org/fhir/ValueSet/claim-use\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set Use from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 Use](/docs/R2/ValueSets/Use.md)| Relationship | [R3 Use](/docs/R3/ValueSets/Use.md)| Relationship | [R4 Use](/docs/R4/ValueSets/Use.md)| Relationship | [R4B Use](/docs/R4B/ValueSets/Use.md)| Relationship | R5 Use
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/claim-use`
| `complete`| _Equivalent_ <br/>(100/1470)| `complete`| _Equivalent_ <br/>(3001/5210)| `claim`| _Equivalent_ <br/>(14652/14653)| `claim`| _Equivalent_ <br/>(7536/9805)| **`claim`**
| `proposed`| _Equivalent_ <br/>(99/1469)| `proposed`| _Equivalent_ <br/>(3004/5211)| `preauthorization`| _Equivalent_ <br/>(14654/14655)| `preauthorization`| _Equivalent_ <br/>(7535/9804)| **`preauthorization`**
| `exploratory`| _Equivalent_ <br/>(97/1467)| `exploratory`| _Equivalent_ <br/>(3002/5212)| `predetermination`| _Equivalent_ <br/>(14656/14657)| `predetermination`| _Equivalent_ <br/>(7534/9803)| **`predetermination`**
| *3 of 4 codes used* <br/>remaining codes:<br/>`other`| | *3 of 4 codes used* <br/>remaining codes:<br/>`other`| | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* 

