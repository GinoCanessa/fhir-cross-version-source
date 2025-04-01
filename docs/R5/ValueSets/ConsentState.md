Comparison of 
Generated at Tuesday, April 1, 2025 1:39:33 PM

### ConsentState

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ConsentState |
| Canonical URL | `http://hl7.org/fhir/ValueSet/consent-state-codes` |
| Version | 5.0.0 |
| Description | Indicates the state of the consent. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `4415` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.status` | `http://hl7.org/fhir/ValueSet/consent-state-codes\|5.0.0` | `Required` | draft \| active \| inactive \| not-done \| entered-in-error \| unknown |

### Referenced Systems

* `http://hl7.org/fhir/consent-state-codes`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ConsentState](/docs/R3/ValueSets/ConsentState.md)<br/> `http://hl7.org/fhir/ValueSet/consent-state-codes\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `479`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ConsentState](/docs/R4/ValueSets/ConsentState.md)<br/> `http://hl7.org/fhir/ValueSet/consent-state-codes\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1447`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1448`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ConsentState](/docs/R4B/ValueSets/ConsentState.md)<br/> `http://hl7.org/fhir/ValueSet/consent-state-codes\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `963`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1224`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ConsentState](/docs/R5/ValueSets/ConsentState.md)<br/> `http://hl7.org/fhir/ValueSet/consent-state-codes\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ConsentState from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 ConsentState](/docs/R3/ValueSets/ConsentState.md)| Relationship | [R4 ConsentState](/docs/R4/ValueSets/ConsentState.md)| Relationship | [R4B ConsentState](/docs/R4B/ValueSets/ConsentState.md)| Relationship | R5 ConsentState
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/consent-state-codes`
| | | `draft`| _Equivalent_ <br/>(4377/6742)| `draft`| _Equivalent_ <br/>(14802/14803)| `draft`| _Equivalent_ <br/>(9224/11546)| **`draft`**
| | | `active`| _Equivalent_ <br/>(4378/6743)| `active`| _Equivalent_ <br/>(14806/14807)| `active`| _Equivalent_ <br/>(9225/11545)| **`active`**
| | | `inactive`| _Equivalent_ <br/>(4374/6739)| `inactive`| _Equivalent_ <br/>(14810/14811)| `inactive`| _Equivalent_ <br/>(9221/11548)| **`inactive`**
| | | `rejected`| _Equivalent_ <br/>(4376/6741)| `rejected`| _Equivalent_ <br/>(14808/14809)| `rejected`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9223)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11549) | **`not-done`**
| | | `entered-in-error`| _Equivalent_ <br/>(4379/6744)| `entered-in-error`| _Equivalent_ <br/>(14812/14813)| `entered-in-error`| _Equivalent_ <br/>(9226/11547)| **`entered-in-error`**
| | | `proposed`| _Equivalent_ <br/>(4375/6740)| `proposed`| _Equivalent_ <br/>(14804/14805)| `proposed`| _Equivalent_ <br/>(9222/11550)| **`unknown`**
| | | *6 of 6 codes used* | | *6 of 6 codes used* | | *6 of 6 codes used* | | *6 of 6 codes used* 

