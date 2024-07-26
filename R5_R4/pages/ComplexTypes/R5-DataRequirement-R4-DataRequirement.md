Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:50 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DataRequirement |  | DataRequirement Type: Describes a required data item for evaluation in terms of the type of data, and optional code or date-based filters of the data. | 33 | 23 |
| Target | DataRequirement |  | Base StructureDefinition for DataRequirement Type: Describes a required data item for evaluation in terms of the type of data, and optional code or date-based filters of the data. | 26 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 7 |
Equivalent | 3 |
RelatedTo | 23 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DataRequirement | DataRequirement | Equivalent | R5 `DataRequirement` maps as Equivalent to R4 `DataRequirement` |
| DataRequirement.codeFilter | DataRequirement.codeFilter | Equivalent | R5 `DataRequirement.codeFilter` maps as Equivalent to R4 `DataRequirement.codeFilter` |
| DataRequirement.codeFilter.code | DataRequirement.codeFilter.code | Equivalent | R5 `DataRequirement.codeFilter.code` maps as Equivalent to R4 `DataRequirement.codeFilter.code` |
| DataRequirement.codeFilter.extension | DataRequirement.codeFilter.extension | Equivalent | R5 `DataRequirement.codeFilter.extension` maps as Equivalent to R4 `DataRequirement.codeFilter.extension` |
| DataRequirement.codeFilter.id | DataRequirement.codeFilter.id | Equivalent | R5 `DataRequirement.codeFilter.id` maps as Equivalent to R4 `DataRequirement.codeFilter.id` |
| DataRequirement.codeFilter.path | DataRequirement.codeFilter.path | Equivalent | R5 `DataRequirement.codeFilter.path` maps as Equivalent to R4 `DataRequirement.codeFilter.path` |
| DataRequirement.codeFilter.searchParam | DataRequirement.codeFilter.searchParam | Equivalent | R5 `DataRequirement.codeFilter.searchParam` maps as Equivalent to R4 `DataRequirement.codeFilter.searchParam` |
| DataRequirement.codeFilter.valueSet | DataRequirement.codeFilter.valueSet | Equivalent | R5 `DataRequirement.codeFilter.valueSet` maps as Equivalent to R4 `DataRequirement.codeFilter.valueSet` |
| DataRequirement.dateFilter | DataRequirement.dateFilter | Equivalent | R5 `DataRequirement.dateFilter` maps as Equivalent to R4 `DataRequirement.dateFilter` |
| DataRequirement.dateFilter.extension | DataRequirement.dateFilter.extension | Equivalent | R5 `DataRequirement.dateFilter.extension` maps as Equivalent to R4 `DataRequirement.dateFilter.extension` |
| DataRequirement.dateFilter.id | DataRequirement.dateFilter.id | Equivalent | R5 `DataRequirement.dateFilter.id` maps as Equivalent to R4 `DataRequirement.dateFilter.id` |
| DataRequirement.dateFilter.path | DataRequirement.dateFilter.path | Equivalent | R5 `DataRequirement.dateFilter.path` maps as Equivalent to R4 `DataRequirement.dateFilter.path` |
| DataRequirement.dateFilter.searchParam | DataRequirement.dateFilter.searchParam | Equivalent | R5 `DataRequirement.dateFilter.searchParam` maps as Equivalent to R4 `DataRequirement.dateFilter.searchParam` |
| DataRequirement.dateFilter.value[x] | DataRequirement.dateFilter.value[x] | Equivalent | R5 `DataRequirement.dateFilter.value[x]` maps as Equivalent to R4 `DataRequirement.dateFilter.value[x]` |
| DataRequirement.extension | DataRequirement.extension | Equivalent | R5 `DataRequirement.extension` maps as Equivalent to R4 `DataRequirement.extension` |
| DataRequirement.id | DataRequirement.id | Equivalent | R5 `DataRequirement.id` maps as Equivalent to R4 `DataRequirement.id` |
| DataRequirement.limit | DataRequirement.limit | Equivalent | R5 `DataRequirement.limit` maps as Equivalent to R4 `DataRequirement.limit` |
| DataRequirement.mustSupport | DataRequirement.mustSupport | Equivalent | R5 `DataRequirement.mustSupport` maps as Equivalent to R4 `DataRequirement.mustSupport` |
| DataRequirement.profile | DataRequirement.profile | Equivalent | R5 `DataRequirement.profile` maps as Equivalent to R4 `DataRequirement.profile` |
| DataRequirement.sort | DataRequirement.sort | Equivalent | R5 `DataRequirement.sort` maps as Equivalent to R4 `DataRequirement.sort` |
| DataRequirement.sort.direction | DataRequirement.sort.direction | Equivalent | R5 `DataRequirement.sort.direction` maps as Equivalent to R4 `DataRequirement.sort.direction` - direction has compatible required binding for code type: http://hl7.org/fhir/ValueSet/sort-direction|5.0.0 and http://hl7.org/fhir/ValueSet/sort-direction|4.0.1 (Equivalent) |
| DataRequirement.sort.extension | DataRequirement.sort.extension | Equivalent | R5 `DataRequirement.sort.extension` maps as Equivalent to R4 `DataRequirement.sort.extension` |
| DataRequirement.sort.id | DataRequirement.sort.id | Equivalent | R5 `DataRequirement.sort.id` maps as Equivalent to R4 `DataRequirement.sort.id` |
| DataRequirement.sort.path | DataRequirement.sort.path | Equivalent | R5 `DataRequirement.sort.path` maps as Equivalent to R4 `DataRequirement.sort.path` |
| DataRequirement.subject[x] | DataRequirement.subject[x] | Equivalent | R5 `DataRequirement.subject[x]` maps as Equivalent to R4 `DataRequirement.subject[x]` |
| DataRequirement.type | DataRequirement.type | RelatedTo | R5 `DataRequirement.type` maps as RelatedTo to R4 `DataRequirement.type` - (type failed to compare required binding of http://hl7.org/fhir/ValueSet/fhir-types|5.0.0 and http://hl7.org/fhir/ValueSet/all-types|4.0.1) |
| DataRequirement.valueFilter | - | DoesNotExistInTarget | R5 `DataRequirement.valueFilter` does not appear in the target and has no mapping for `DataRequirement`. |
| DataRequirement.valueFilter.comparator | - | DoesNotExistInTarget | R5 `DataRequirement.valueFilter.comparator` does not appear in the target and has no mapping for `DataRequirement`. |
| DataRequirement.valueFilter.extension | - | DoesNotExistInTarget | R5 `DataRequirement.valueFilter.extension` does not appear in the target and has no mapping for `DataRequirement`. |
| DataRequirement.valueFilter.id | - | DoesNotExistInTarget | R5 `DataRequirement.valueFilter.id` does not appear in the target and has no mapping for `DataRequirement`. |
| DataRequirement.valueFilter.path | - | DoesNotExistInTarget | R5 `DataRequirement.valueFilter.path` does not appear in the target and has no mapping for `DataRequirement`. |
| DataRequirement.valueFilter.searchParam | - | DoesNotExistInTarget | R5 `DataRequirement.valueFilter.searchParam` does not appear in the target and has no mapping for `DataRequirement`. |
| DataRequirement.valueFilter.value[x] | - | DoesNotExistInTarget | R5 `DataRequirement.valueFilter.value[x]` does not appear in the target and has no mapping for `DataRequirement`. |

