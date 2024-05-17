Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Expression |  | Expression Type: A expression that is evaluated in a specified context and returns a value. The context of use of the expression must specify the context in which the expression is evaluated, and how the result of the expression is used. | 8 | 6 |
| Target | Expression |  | Base StructureDefinition for Expression Type: A expression that is evaluated in a specified context and returns a value. The context of use of the expression must specify the context in which the expression is evaluated, and how the result of the expression is used. | 8 | 6 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 3 |
SourceIsBroaderThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Expression | Expression | Equivalent | R5 `Expression` maps as Equivalent to R4B `Expression` |
| Expression.description | Expression.description | Equivalent | R5 `Expression.description` maps as Equivalent to R4B `Expression.description` |
| Expression.expression | Expression.expression | Equivalent | R5 `Expression.expression` maps as Equivalent to R4B `Expression.expression` |
| Expression.extension | Expression.extension | Equivalent | R5 `Expression.extension` maps as Equivalent to R4B `Expression.extension` |
| Expression.id | Expression.id | Equivalent | R5 `Expression.id` maps as Equivalent to R4B `Expression.id` |
| Expression.language | Expression.language | RelatedTo | R5 `Expression.language` maps as RelatedTo to R4B `Expression.language` - language made the element mandatory; language increased the minimum cardinality from 0 to 1 |
| Expression.name | Expression.name | SourceIsBroaderThanTarget | R5 `Expression.name` maps as SourceIsBroaderThanTarget to R4B `Expression.name` - name has change due to type change: R5 name code has no equivalent or mapped type in R4B name |
| Expression.reference | Expression.reference | Equivalent | R5 `Expression.reference` maps as Equivalent to R4B `Expression.reference` |

