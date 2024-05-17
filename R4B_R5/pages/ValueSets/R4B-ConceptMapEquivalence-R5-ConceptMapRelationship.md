Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:03 AM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/concept-map-equivalence | ConceptMapEquivalence | ConceptMapEquivalence | The degree of equivalence between concepts. |
| Target | http://hl7.org/fhir/ValueSet/concept-map-relationship | ConceptMapRelationship | ConceptMapRelationship | The relationship between concepts. |


Comparison Result: SourceIsNarrowerThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 1 |
SourceIsNarrowerThanTarget | 8 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| disjoint | not-related-to | Equivalent | R4B `disjoint` is equivalent to R5 `not-related-to`. |
| equal | equivalent | SourceIsNarrowerThanTarget | R4B `equal` is narrower than R5 `equivalent` and is compatible. `equivalent` is mapped from `equal` and `equivalent`. |
| equivalent | equivalent | SourceIsNarrowerThanTarget | R4B `equivalent` is narrower than R5 `equivalent` and is compatible. `equivalent` is mapped from `equal` and `equivalent`. |
| inexact | related-to | SourceIsNarrowerThanTarget | R4B `inexact` is narrower than R5 `related-to` and is compatible. `related-to` is mapped from `inexact` and `relatedto`. |
| narrower | source-is-broader-than-target | SourceIsNarrowerThanTarget | R4B `narrower` is narrower than R5 `source-is-broader-than-target` and is compatible. `source-is-broader-than-target` is mapped from `narrower` and `subsumes`. |
| relatedto | related-to | SourceIsNarrowerThanTarget | R4B `relatedto` is narrower than R5 `related-to` and is compatible. `related-to` is mapped from `inexact` and `relatedto`. |
| specializes | source-is-narrower-than-target | SourceIsNarrowerThanTarget | R4B `specializes` is narrower than R5 `source-is-narrower-than-target` and is compatible. `source-is-narrower-than-target` is mapped from `specializes` and `wider`. |
| subsumes | source-is-broader-than-target | SourceIsNarrowerThanTarget | R4B `subsumes` is narrower than R5 `source-is-broader-than-target` and is compatible. `source-is-broader-than-target` is mapped from `narrower` and `subsumes`. |
| unmatched | - | DoesNotExistInTarget | R4B `unmatched` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/concept-map-relationship. |
| wider | source-is-narrower-than-target | SourceIsNarrowerThanTarget | R4B `wider` is narrower than R5 `source-is-narrower-than-target` and is compatible. `source-is-narrower-than-target` is mapped from `specializes` and `wider`. |

