Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:03 AM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/encounter-status | EncounterStatus | EncounterStatus | Current state of the encounter. |
| Target | http://hl7.org/fhir/ValueSet/encounter-status | EncounterStatus | Encounter Status | Current state of the encounter. |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
SourceIsBroaderThanTarget | 1 |
SourceIsNarrowerThanTarget | 4 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| arrived | planned | SourceIsNarrowerThanTarget | R4B `arrived` is narrower than R5 `planned` and is compatible. `planned` is mapped from `arrived` and `planned`. |
| cancelled | cancelled | Equivalent | R4B `cancelled` is equivalent to R5 `cancelled`. |
| entered-in-error | entered-in-error | Equivalent | R4B `entered-in-error` is equivalent to R5 `entered-in-error`. |
| finished | completed | Equivalent | R4B `finished` is equivalent to R5 `completed`. |
| finished | discharged | Equivalent | R4B `finished` is equivalent to R5 `discharged`. |
| in-progress | in-progress | SourceIsNarrowerThanTarget | R4B `in-progress` is narrower than R5 `in-progress` and is compatible. `in-progress` is mapped from `in-progress` and `triaged`. |
| onleave | on-hold | Equivalent | R4B `onleave` is equivalent to R5 `on-hold`. |
| planned | planned | SourceIsNarrowerThanTarget | R4B `planned` is narrower than R5 `planned` and is compatible. `planned` is mapped from `arrived` and `planned`. |
| triaged | in-progress | SourceIsNarrowerThanTarget | R4B `triaged` is narrower than R5 `in-progress` and is compatible. `in-progress` is mapped from `in-progress` and `triaged`. |
| unknown | unknown | Equivalent | R4B `unknown` is equivalent to R5 `unknown`. |

