Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### ConceptMapRelationship

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ConceptMapRelationship |
| Canonical URL | `http://hl7.org/fhir/ValueSet/concept-map-relationship` |
| Version | 5.0.0 |
| Description | The relationship between concepts. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4388` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ConceptMap` | `ConceptMap.group.element.target.relationship` | `http://hl7.org/fhir/ValueSet/concept-map-relationship\|5.0.0` | `Required` | related-to \| equivalent \| source-is-narrower-than-target \| source-is-broader-than-target \| not-related-to |
| `http://hl7.org/fhir/StructureDefinition/ConceptMap` | `ConceptMap.group.unmapped.relationship` | `http://hl7.org/fhir/ValueSet/concept-map-relationship\|5.0.0` | `Required` | related-to \| equivalent \| source-is-narrower-than-target \| source-is-broader-than-target \| not-related-to |

### Referenced Systems

* `http://hl7.org/fhir/concept-map-relationship`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ConceptMapEquivalence](/docs/R2/ValueSets/ConceptMapEquivalence.md)<br/> `http://hl7.org/fhir/ValueSet/concept-map-equivalence\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `23`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `182`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ConceptMapEquivalence](/docs/R3/ValueSets/ConceptMapEquivalence.md)<br/> `http://hl7.org/fhir/ValueSet/concept-map-equivalence\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `349`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `572`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ConceptMapEquivalence](/docs/R4/ValueSets/ConceptMapEquivalence.md)<br/> `http://hl7.org/fhir/ValueSet/concept-map-equivalence\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1429`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1430`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ConceptMapEquivalence](/docs/R4B/ValueSets/ConceptMapEquivalence.md)<br/> `http://hl7.org/fhir/ValueSet/concept-map-equivalence\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `797`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1058`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ConceptMapRelationship](/docs/R5/ValueSets/ConceptMapRelationship.md)<br/> `http://hl7.org/fhir/ValueSet/concept-map-relationship\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ConceptMapRelationship from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ConceptMapEquivalence](/docs/R2/ValueSets/ConceptMapEquivalence.md)| Relationship | [R3 ConceptMapEquivalence](/docs/R3/ValueSets/ConceptMapEquivalence.md)| Relationship | [R4 ConceptMapEquivalence](/docs/R4/ValueSets/ConceptMapEquivalence.md)| Relationship | [R4B ConceptMapEquivalence](/docs/R4B/ValueSets/ConceptMapEquivalence.md)| Relationship | R5 ConceptMapRelationship
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/concept-map-relationship`
| `inexact`| _Equivalent_ <br/>(105/1477)| `inexact`| _Equivalent_ <br/>(3009/5217)| `inexact`| _Equivalent_ <br/>(14726/14727)| `inexact`| _Equivalent_ <br/>(7545/9814)| **`related-to`**
| `equivalent`| _Equivalent_ <br/>(106/1476)| `equivalent`| _Equivalent_ <br/>(3010/5218)| `equivalent`| _Equivalent_ <br/>(14714/14715)| `equivalent`| _Equivalent_ <br/>(7546/9813)| **`equivalent`**
| `wider`| _Equivalent_ <br/>(107/1483)| `wider`| _Equivalent_ <br/>(3011/5219)| `wider`| _Equivalent_ <br/>(14718/14719)| `wider`| _Equivalent_ <br/>(7547/9816)| **`source-is-narrower-than-target`**
| `narrower`| _Equivalent_ <br/>(110/1478)| `narrower`| _Equivalent_ <br/>(3014/5222)| `narrower`| _Equivalent_ <br/>(14722/14723)| `narrower`| _Equivalent_ <br/>(7550/9817)| **`source-is-broader-than-target`**
| `disjoint`| _Equivalent_ <br/>(109/1474)| `disjoint`| _Equivalent_ <br/>(3013/5221)| `disjoint`| _Equivalent_ <br/>(14730/14731)| `disjoint`| _Equivalent_ <br/>(7549/9815)| **`not-related-to`**
| *5 of 9 codes used* <br/>remaining codes:<br/>`equal`, `specializes`, `subsumes`, `unmatched`| | *5 of 10 codes used* <br/>remaining codes:<br/>`equal`, `relatedto`, `specializes`, `subsumes`, `unmatched`| | *5 of 10 codes used* <br/>remaining codes:<br/>`equal`, `relatedto`, `specializes`, `subsumes`, `unmatched`| | *5 of 10 codes used* <br/>remaining codes:<br/>`equal`, `relatedto`, `specializes`, `subsumes`, `unmatched`| | *5 of 5 codes used* 

