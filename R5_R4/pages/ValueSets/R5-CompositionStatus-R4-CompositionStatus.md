Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/composition-status | CompositionStatus | Composition Status | The workflow/clinical status of the composition. |
| Target | http://hl7.org/fhir/ValueSet/composition-status | CompositionStatus | CompositionStatus | The workflow/clinical status of the composition. |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 2 |
SourceIsNarrowerThanTarget | 5 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| amended | amended | SourceIsNarrowerThanTarget | R5 `amended` is narrower than R4 `amended` and is compatible. `amended` is mapped from `amended` and `appended` and `corrected`. |
| appended | amended | SourceIsNarrowerThanTarget | R5 `appended` is narrower than R4 `amended` and is compatible. `amended` is mapped from `amended` and `appended` and `corrected`. |
| cancelled | - | DoesNotExistInTarget | R5 `cancelled` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/composition-status. |
| corrected | amended | SourceIsNarrowerThanTarget | R5 `corrected` is narrower than R4 `amended` and is compatible. `amended` is mapped from `amended` and `appended` and `corrected`. |
| deprecated | - | DoesNotExistInTarget | R5 `deprecated` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/composition-status. |
| entered-in-error | entered-in-error | Equivalent | R5 `entered-in-error` is equivalent to R4 `entered-in-error`. |
| final | final | Equivalent | R5 `final` is equivalent to R4 `final`. |
| partial | preliminary | SourceIsNarrowerThanTarget | R5 `partial` is narrower than R4 `preliminary` and is compatible. `preliminary` is mapped from `partial` and `preliminary`. |
| preliminary | preliminary | SourceIsNarrowerThanTarget | R5 `preliminary` is narrower than R4 `preliminary` and is compatible. `preliminary` is mapped from `partial` and `preliminary`. |
| registered | - | DoesNotExistInTarget | R5 `registered` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/composition-status. |
| unknown | - | DoesNotExistInTarget | R5 `unknown` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/composition-status. |

