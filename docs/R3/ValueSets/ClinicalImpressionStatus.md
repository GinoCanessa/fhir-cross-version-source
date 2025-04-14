Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### ClinicalImpressionStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | ClinicalImpressionStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/clinical-impression-status` |
| Version | 3.0.2 |
| Description | The workflow state of a clinical impression. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1113` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClinicalImpression` | `ClinicalImpression.status` | `http://hl7.org/fhir/ValueSet/clinical-impression-status` | `Required` | draft \| completed \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/clinical-impression-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ClinicalImpressionStatus](/docs/R2/ValueSets/ClinicalImpressionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/clinical-impression-status\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `18`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `177`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ClinicalImpressionStatus](/docs/R3/ValueSets/ClinicalImpressionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/clinical-impression-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `343`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `567`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ClinicalImpressionStatus](/docs/R4/ValueSets/ClinicalImpressionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/clinicalimpression-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1415`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1416`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ClinicalImpressionStatus](/docs/R4B/ValueSets/ClinicalImpressionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/clinicalimpression-status\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `792`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1053`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [EventStatus](/docs/R5/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ClinicalImpressionStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ClinicalImpressionStatus](/docs/R2/ValueSets/ClinicalImpressionStatus.md)| Relationship | R3 ClinicalImpressionStatus| Relationship | [R4 ClinicalImpressionStatus](/docs/R4/ValueSets/ClinicalImpressionStatus.md)| Relationship | [R4B ClinicalImpressionStatus](/docs/R4B/ValueSets/ClinicalImpressionStatus.md)| Relationship | [R5 EventStatus](/docs/R5/ValueSets/EventStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/clinical-impression-status`
| `in-progress`| _Equivalent_ <br/>(87/1456)| **`draft`**| _Equivalent_ <br/>(2985/5200)| `in-progress`| _Equivalent_ <br/>(14658/14659)| `in-progress`| _Equivalent_ <br/>(7528/9794)| `in-progress`
| `completed`| _Equivalent_ <br/>(85/1455)| **`completed`**| _Equivalent_ <br/>(2986/5198)| `completed`| _Equivalent_ <br/>(14660/14661)| `completed`| _Equivalent_ <br/>(7526/9791)| `completed`
| `entered-in-error`| _Equivalent_ <br/>(86/1457)| **`entered-in-error`**| _Equivalent_ <br/>(2987/5199)| `entered-in-error`| _Equivalent_ <br/>(14662/14663)| `entered-in-error`| _Equivalent_ <br/>(7527/9793)| `entered-in-error`
| *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 8 codes used* <br/>remaining codes:<br/>`not-done`, `on-hold`, `preparation`, `stopped`, `unknown`

