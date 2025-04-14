Comparison of 
Generated at Monday, April 14, 2025 6:17:27 PM

### ConceptMapEquivalence

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ConceptMapEquivalence |
| Canonical URL | `http://hl7.org/fhir/ValueSet/concept-map-equivalence` |
| Version | 4.0.1 |
| Description | The degree of equivalence between concepts. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2286` |
| Database Concept Count | `10` |
| Database Active Concept Count | `10` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ConceptMap` | `ConceptMap.group.element.target.equivalence` | `http://hl7.org/fhir/ValueSet/concept-map-equivalence\|4.0.1` | `Required` | relatedto \| equivalent \| equal \| wider \| subsumes \| narrower \| specializes \| inexact \| unmatched \| disjoint |
| `http://hl7.org/fhir/StructureDefinition/elementdefinition-equivalence` | `Extension.value[x]` | `http://hl7.org/fhir/ValueSet/concept-map-equivalence\|4.0.1` | `Required` | Value of extension |

### Referenced Systems

* `http://hl7.org/fhir/concept-map-equivalence`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ConceptMapEquivalence](/docs/R2/ValueSets/ConceptMapEquivalence.md)<br/> `http://hl7.org/fhir/ValueSet/concept-map-equivalence\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `23`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `182`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ConceptMapEquivalence](/docs/R3/ValueSets/ConceptMapEquivalence.md)<br/> `http://hl7.org/fhir/ValueSet/concept-map-equivalence\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `349`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `572`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [ConceptMapEquivalence](/docs/R4/ValueSets/ConceptMapEquivalence.md)<br/> `http://hl7.org/fhir/ValueSet/concept-map-equivalence\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1429`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1430`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ConceptMapEquivalence](/docs/R4B/ValueSets/ConceptMapEquivalence.md)<br/> `http://hl7.org/fhir/ValueSet/concept-map-equivalence\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `797`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1058`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ConceptMapRelationship](/docs/R5/ValueSets/ConceptMapRelationship.md)<br/> `http://hl7.org/fhir/ValueSet/concept-map-relationship\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ConceptMapEquivalence from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ConceptMapEquivalence](/docs/R2/ValueSets/ConceptMapEquivalence.md)| Relationship | [R3 ConceptMapEquivalence](/docs/R3/ValueSets/ConceptMapEquivalence.md)| Relationship | R4 ConceptMapEquivalence| Relationship | [R4B ConceptMapEquivalence](/docs/R4B/ValueSets/ConceptMapEquivalence.md)| Relationship | [R5 ConceptMapRelationship](/docs/R5/ValueSets/ConceptMapRelationship.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/concept-map-equivalence`
| | | `relatedto`| _Equivalent_ <br/>(3016/5224)| **`relatedto`**| _Equivalent_ <br/>(14712/14713)| `relatedto`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7552)<hr/>←←←← __ ←←←← <br/>() | `related-to`
| `equivalent`| _Equivalent_ <br/>(106/1476)| `equivalent`| _Equivalent_ <br/>(3010/5218)| **`equivalent`**| _Equivalent_ <br/>(14714/14715)| `equivalent`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7546)<hr/>←←←← _Equivalent_ ←←←← <br/>(9813) | `equivalent`
| `equal`| _Equivalent_ <br/>(104/1475)| `equal`| _Equivalent_ <br/>(3008/5216)| **`equal`**| _Equivalent_ <br/>(14716/14717)| `equal`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7544)<hr/>←←←← __ ←←←← <br/>() | `equivalent`
| `wider`| _Equivalent_ <br/>(107/1483)| `wider`| _Equivalent_ <br/>(3011/5219)| **`wider`**| _Equivalent_ <br/>(14718/14719)| `wider`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7547)<hr/>←←←← _Equivalent_ ←←←← <br/>(9816) | `source-is-narrower-than-target`
| `subsumes`| _Equivalent_ <br/>(112/1481)| `subsumes`| _Equivalent_ <br/>(3017/5225)| **`subsumes`**| _Equivalent_ <br/>(14720/14721)| `subsumes`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7553)<hr/>←←←← __ ←←←← <br/>() | `source-is-broader-than-target`
| `narrower`| _Equivalent_ <br/>(110/1478)| `narrower`| _Equivalent_ <br/>(3014/5222)| **`narrower`**| _Equivalent_ <br/>(14722/14723)| `narrower`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7550)<hr/>←←←← _Equivalent_ ←←←← <br/>(9817) | `source-is-broader-than-target`
| `specializes`| _Equivalent_ <br/>(108/1480)| `specializes`| _Equivalent_ <br/>(3012/5220)| **`specializes`**| _Equivalent_ <br/>(14724/14725)| `specializes`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7548)<hr/>←←←← __ ←←←← <br/>() | `source-is-narrower-than-target`
| `inexact`| _Equivalent_ <br/>(105/1477)| `inexact`| _Equivalent_ <br/>(3009/5217)| **`inexact`**| _Equivalent_ <br/>(14726/14727)| `inexact`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7545)<hr/>←←←← _Equivalent_ ←←←← <br/>(9814) | `related-to`
| `unmatched`| _Equivalent_ <br/>(111/1482)| `unmatched`| _Equivalent_ <br/>(3015/5223)| **`unmatched`**| _Equivalent_ <br/>(14728/14729)| `unmatched`| | | 
| `disjoint`| _Equivalent_ <br/>(109/1474)| `disjoint`| _Equivalent_ <br/>(3013/5221)| **`disjoint`**| _Equivalent_ <br/>(14730/14731)| `disjoint`| _Equivalent_ <br/>(7549/9815)| `not-related-to`
| *9 of 9 codes used* | | *10 of 10 codes used* | | *10 of 10 codes used* | | *10 of 10 codes used* | | *5 of 5 codes used* 

