Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/publication-status | PublicationStatus | PublicationStatus | The lifecycle status of an artifact. |
| Target | http://hl7.org/fhir/ValueSet/research-study-status | ResearchStudyStatus | ResearchStudyStatus | Codes that convey the current status of the research study. |


Comparison Result: Equivalent


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| active | active | Equivalent | R5 `active` is equivalent to R4B `active`. |
| draft | - | DoesNotExistInTarget | R5 `draft` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/research-study-status. |
| retired | withdrawn | SourceIsNarrowerThanTarget | R5 `retired` maps as SourceIsNarrowerThanTarget to the target R4B `withdrawn`. |
| unknown | - | DoesNotExistInTarget | R5 `unknown` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/research-study-status. |

