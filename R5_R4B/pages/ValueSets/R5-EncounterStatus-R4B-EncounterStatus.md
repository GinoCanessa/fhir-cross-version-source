Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/encounter-status | EncounterStatus | Encounter Status | Current state of the encounter. |
| Target | http://hl7.org/fhir/ValueSet/encounter-status | EncounterStatus | EncounterStatus | Current state of the encounter. |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
SourceIsBroaderThanTarget | 2 |
SourceIsNarrowerThanTarget | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| cancelled | cancelled | Equivalent | R5 `cancelled` is equivalent to R4B `cancelled`. |
| completed | finished | SourceIsNarrowerThanTarget | R5 `completed` is narrower than R4B `finished` and is compatible. `finished` is mapped from `completed` and `discharged`. |
| discharged | finished | SourceIsNarrowerThanTarget | R5 `discharged` is narrower than R4B `finished` and is compatible. `finished` is mapped from `completed` and `discharged`. |
| discontinued | - | DoesNotExistInTarget | R5 `discontinued` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/encounter-status. |
| entered-in-error | entered-in-error | Equivalent | R5 `entered-in-error` is equivalent to R4B `entered-in-error`. |
| in-progress | in-progress | SourceIsBroaderThanTarget | R5 `in-progress` is broader than R4B in-progress and requires mapping choice. `in-progress` maps to `in-progress` and `triaged`. |
| in-progress | triaged | SourceIsBroaderThanTarget | R5 `in-progress` is broader than R4B triaged and requires mapping choice. `in-progress` maps to `in-progress` and `triaged`. |
| on-hold | onleave | Equivalent | R5 `on-hold` is equivalent to R4B `onleave`. |
| planned | planned | SourceIsBroaderThanTarget | R5 `planned` is broader than R4B planned and requires mapping choice. `planned` maps to `planned` and `arrived`. |
| planned | arrived | SourceIsBroaderThanTarget | R5 `planned` is broader than R4B arrived and requires mapping choice. `planned` maps to `planned` and `arrived`. |
| unknown | unknown | Equivalent | R5 `unknown` is equivalent to R4B `unknown`. |

