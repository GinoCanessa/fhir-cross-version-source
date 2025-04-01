Comparison of 
Generated at Tuesday, April 1, 2025 1:39:10 PM

### AccountStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | AccountStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/account-status` |
| Version | 3.0.2 |
| Description | Indicates whether the account is available to be used. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1018` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Account` | `Account.status` | `http://hl7.org/fhir/ValueSet/account-status` | `Required` | active \| inactive \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/account-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AccountStatus](/docs/R2/ValueSets/AccountStatus.md)<br/> `http://hl7.org/fhir/ValueSet/account-status\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `1316`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1315`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AccountStatus](/docs/R3/ValueSets/AccountStatus.md)<br/> `http://hl7.org/fhir/ValueSet/account-status\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `320`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `542`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AccountStatus](/docs/R4/ValueSets/AccountStatus.md)<br/> `http://hl7.org/fhir/ValueSet/account-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1335`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1336`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AccountStatus](/docs/R4B/ValueSets/AccountStatus.md)<br/> `http://hl7.org/fhir/ValueSet/account-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `764`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1025`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AccountStatus](/docs/R5/ValueSets/AccountStatus.md)<br/> `http://hl7.org/fhir/ValueSet/account-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set AccountStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 AccountStatus](/docs/R2/ValueSets/AccountStatus.md)| Relationship | R3 AccountStatus| Relationship | [R4 AccountStatus](/docs/R4/ValueSets/AccountStatus.md)| Relationship | [R4B AccountStatus](/docs/R4B/ValueSets/AccountStatus.md)| Relationship | [R5 AccountStatus](/docs/R5/ValueSets/AccountStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/account-status`
| `active`| _Equivalent_ <br/>(12817/12816)| **`active`**| _Equivalent_ <br/>(2877/5061)| `active`| _Equivalent_ <br/>(13856/13857)| `active`| _Equivalent_ <br/>(7400/9659)| `active`
| `inactive`| _Equivalent_ <br/>(12819/12818)| **`inactive`**| _Equivalent_ <br/>(2876/5063)| `inactive`| _Equivalent_ <br/>(13858/13859)| `inactive`| _Equivalent_ <br/>(7399/9658)| `inactive`
| | | **`entered-in-error`**| _Equivalent_ <br/>(2878/5062)| `entered-in-error`| _Equivalent_ <br/>(13860/13861)| `entered-in-error`| _Equivalent_ <br/>(7401/9660)| `entered-in-error`
| *2 of 2 codes used* | | *3 of 3 codes used* | | *3 of 5 codes used* | | *3 of 5 codes used* | | *3 of 5 codes used* 

