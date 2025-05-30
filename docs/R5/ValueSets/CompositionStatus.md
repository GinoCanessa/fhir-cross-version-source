Comparison of 
Generated at Monday, April 14, 2025 6:17:42 PM

### CompositionStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | CompositionStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/composition-status` |
| Version | 5.0.0 |
| Description | The workflow/clinical status of the composition. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `4387` |
| Database Concept Count | `11` |
| Database Active Concept Count | `11` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Composition` | `Composition.status` | `http://hl7.org/fhir/ValueSet/composition-status\|5.0.0` | `Required` | registered \| partial \| preliminary \| final \| amended \| corrected \| appended \| cancelled \| entered-in-error \| deprecated \| unknown |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.docStatus` | `http://hl7.org/fhir/ValueSet/composition-status\|5.0.0` | `Required` | registered \| partial \| preliminary \| final \| amended \| corrected \| appended \| cancelled \| entered-in-error \| deprecated \| unknown |

### Referenced Systems

* `http://hl7.org/fhir/composition-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [CompositionStatus](/docs/R2/ValueSets/CompositionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/composition-status\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `29`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `188`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [CompositionStatus](/docs/R3/ValueSets/CompositionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/composition-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `355`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `578`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [CompositionStatus](/docs/R4/ValueSets/CompositionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/composition-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1427`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1428`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [CompositionStatus](/docs/R4B/ValueSets/CompositionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/composition-status\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `799`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1060`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [CompositionStatus](/docs/R5/ValueSets/CompositionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/composition-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set CompositionStatus from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 CompositionStatus](/docs/R2/ValueSets/CompositionStatus.md)| Relationship | [R3 CompositionStatus](/docs/R3/ValueSets/CompositionStatus.md)| Relationship | [R4 CompositionStatus](/docs/R4/ValueSets/CompositionStatus.md)| Relationship | [R4B CompositionStatus](/docs/R4B/ValueSets/CompositionStatus.md)| Relationship | R5 CompositionStatus
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/composition-status`
| | | | | | | | | **`registered`**
| | | | | | | | | **`partial`**
| `preliminary`| _Equivalent_ <br/>(141/1503)| `preliminary`| _Equivalent_ <br/>(3040/5248)| `preliminary`| _Equivalent_ <br/>(14704/14705)| `preliminary`| _Equivalent_ <br/>(7560/9829)| **`preliminary`**
| `final`| _Equivalent_ <br/>(140/1502)| `final`| _Equivalent_ <br/>(3039/5247)| `final`| _Equivalent_ <br/>(14706/14707)| `final`| _Equivalent_ <br/>(7559/9827)| **`final`**
| `amended`| _Equivalent_ <br/>(139/1501)| `amended`| _Equivalent_ <br/>(3038/5246)| `amended`| _Equivalent_ <br/>(14708/14709)| `amended`| _Equivalent_ <br/>(7558/9821)| **`amended`**
| | | | | | | | | **`corrected`**
| | | | | | | | | **`appended`**
| | | | | | | | | **`cancelled`**
| `entered-in-error`| _Equivalent_ <br/>(142/1504)| `entered-in-error`| _Equivalent_ <br/>(3041/5249)| `entered-in-error`| _Equivalent_ <br/>(14710/14711)| `entered-in-error`| _Equivalent_ <br/>(7561/9826)| **`entered-in-error`**
| | | | | | | | | **`deprecated`**
| | | | | | | | | **`unknown`**
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *11 of 11 codes used* 

