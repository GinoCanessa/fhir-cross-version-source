Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Signature |  | Signature Type: A signature along with supporting context. The signature may be a digital signature that is cryptographic in nature, or some other signature acceptable to the domain. This other signature may be as simple as a graphical image representing a hand-written signature, or a signature ceremony Different signature approaches have different utilities. | 10 | 8 |
| Target | Signature |  | Base StructureDefinition for Signature Type: A signature along with supporting context. The signature may be a digital signature that is cryptographic in nature, or some other signature acceptable to the domain. This other signature may be as simple as a graphical image representing a hand-written signature, or a signature ceremony Different signature approaches have different utilities. | 10 | 8 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 7 |
RelatedTo | 3 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Signature | Signature | Equivalent | R5 `Signature` maps as Equivalent to R4 `Signature` |
| Signature.data | Signature.data | Equivalent | R5 `Signature.data` maps as Equivalent to R4 `Signature.data` |
| Signature.extension | Signature.extension | Equivalent | R5 `Signature.extension` maps as Equivalent to R4 `Signature.extension` |
| Signature.id | Signature.id | Equivalent | R5 `Signature.id` maps as Equivalent to R4 `Signature.id` |
| Signature.onBehalfOf | Signature.onBehalfOf | Equivalent | R5 `Signature.onBehalfOf` maps as Equivalent to R4 `Signature.onBehalfOf` |
| Signature.sigFormat | Signature.sigFormat | Equivalent | R5 `Signature.sigFormat` maps as Equivalent to R4 `Signature.sigFormat` - sigFormat using http://hl7.org/fhir/ValueSet/mimetypes is exempted and assumed equivalent |
| Signature.targetFormat | Signature.targetFormat | Equivalent | R5 `Signature.targetFormat` maps as Equivalent to R4 `Signature.targetFormat` - targetFormat using http://hl7.org/fhir/ValueSet/mimetypes is exempted and assumed equivalent |
| Signature.type | Signature.type | RelatedTo | R5 `Signature.type` maps as RelatedTo to R4 `Signature.type` - type made the element mandatory; type increased the minimum cardinality from 0 to 1 |
| Signature.when | Signature.when | RelatedTo | R5 `Signature.when` maps as RelatedTo to R4 `Signature.when` - when made the element mandatory; when increased the minimum cardinality from 0 to 1 |
| Signature.who | Signature.who | RelatedTo | R5 `Signature.who` maps as RelatedTo to R4 `Signature.who` - who made the element mandatory; who increased the minimum cardinality from 0 to 1 |

