Comparison of 
Generated at Tuesday, April 1, 2025 1:39:33 PM

### CompositionAttestationMode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | CompositionAttestationMode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/composition-attestation-mode` |
| Version | 5.0.0 |
| Description | The way in which a person authenticated a composition. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4386` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Composition` | `Composition.attester.mode` | `http://hl7.org/fhir/ValueSet/composition-attestation-mode` | `Preferred` | personal \| professional \| legal \| official |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.attester.mode` | `http://hl7.org/fhir/ValueSet/composition-attestation-mode` | `Preferred` | personal \| professional \| legal \| official |

### Referenced Systems

* `http://hl7.org/fhir/composition-attestation-mode`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [CompositionAttestationMode](/docs/R2/ValueSets/CompositionAttestationMode.md)<br/> `http://hl7.org/fhir/ValueSet/composition-attestation-mode\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `26`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `185`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CompositionAttestationMode](/docs/R3/ValueSets/CompositionAttestationMode.md)<br/> `http://hl7.org/fhir/ValueSet/composition-attestation-mode\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `351`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `574`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CompositionAttestationMode](/docs/R4/ValueSets/CompositionAttestationMode.md)<br/> `http://hl7.org/fhir/ValueSet/composition-attestation-mode\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1425`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1426`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CompositionAttestationMode](/docs/R4B/ValueSets/CompositionAttestationMode.md)<br/> `http://hl7.org/fhir/ValueSet/composition-attestation-mode\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `1801`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1802`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CompositionAttestationMode](/docs/R5/ValueSets/CompositionAttestationMode.md)<br/> `http://hl7.org/fhir/ValueSet/composition-attestation-mode\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set CompositionAttestationMode from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 CompositionAttestationMode](/docs/R2/ValueSets/CompositionAttestationMode.md)| Relationship | [R3 CompositionAttestationMode](/docs/R3/ValueSets/CompositionAttestationMode.md)| Relationship | [R4 CompositionAttestationMode](/docs/R4/ValueSets/CompositionAttestationMode.md)| Relationship | [R4B CompositionAttestationMode](/docs/R4B/ValueSets/CompositionAttestationMode.md)| Relationship | R5 CompositionAttestationMode
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/composition-attestation-mode`
| `personal`| _Equivalent_ <br/>(118/1490)| `personal`| _Equivalent_ <br/>(3023/5231)| `personal`| _Equivalent_ <br/>(14696/14697)| `personal`| _Equivalent_ <br/>(18467/18468)| **`personal`**
| `professional`| _Equivalent_ <br/>(119/1491)| `professional`| _Equivalent_ <br/>(3024/5232)| `professional`| _Equivalent_ <br/>(14698/14699)| `professional`| _Equivalent_ <br/>(18469/18470)| **`professional`**
| `legal`| _Equivalent_ <br/>(116/1488)| `legal`| _Equivalent_ <br/>(3021/5229)| `legal`| _Equivalent_ <br/>(14700/14701)| `legal`| _Equivalent_ <br/>(18471/18472)| **`legal`**
| `official`| _Equivalent_ <br/>(117/1489)| `official`| _Equivalent_ <br/>(3022/5230)| `official`| _Equivalent_ <br/>(14702/14703)| `official`| _Equivalent_ <br/>(18473/18474)| **`official`**
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 

