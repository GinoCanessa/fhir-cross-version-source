Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/encounter-status | EncounterStatus | Encounter Status | Current state of the encounter. |
| Target | http://hl7.org/fhir/ValueSet/encounter-status | EncounterStatus | EncounterStatus | Current state of the encounter. |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 6 |
SourceIsNarrowerThanTarget | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| cancelled | cancelled | Equivalent | R5 `cancelled` is equivalent to R4 `cancelled`. |
| completed | finished | SourceIsNarrowerThanTarget | R5 `completed` is narrower than R4 `finished` and is compatible. `finished` is mapped from `completed` and `discharged`. |
| discharged | finished | SourceIsNarrowerThanTarget | R5 `discharged` is narrower than R4 `finished` and is compatible. `finished` is mapped from `completed` and `discharged`. |
| discontinued | - | DoesNotExistInTarget | R5 `discontinued` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/encounter-status. |
| entered-in-error | entered-in-error | Equivalent | R5 `entered-in-error` is equivalent to R4 `entered-in-error`. |
| in-progress | in-progress | Equivalent | R5 `in-progress` is equivalent to R4 `in-progress`. |
| on-hold | onleave | Equivalent | R5 `on-hold` is equivalent to R4 `onleave`. |
| planned | planned | Equivalent | R5 `planned` is equivalent to R4 `planned`. |
| unknown | unknown | Equivalent | R5 `unknown` is equivalent to R4 `unknown`. |

