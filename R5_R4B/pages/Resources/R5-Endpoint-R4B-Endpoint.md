Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Endpoint |  | The technical details of an endpoint that can be used for electronic services, such as for web services providing XDS.b, a REST endpoint for another FHIR server, or a s/Mime email address. This may include any security context information. | 26 | 15 |
| Target | Endpoint |  | The technical details of an endpoint that can be used for electronic services, such as for web services providing XDS.b or a REST endpoint for another FHIR server. This may include any security context information. | 20 | 12 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 8 |
Equivalent | 4 |
RelatedTo | 14 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Endpoint | Endpoint | Equivalent | R5 `Endpoint` maps as Equivalent to R4B `Endpoint` |
| Endpoint.address | Endpoint.address | Equivalent | R5 `Endpoint.address` maps as Equivalent to R4B `Endpoint.address` |
| Endpoint.connectionType | Endpoint.connectionType | RelatedTo | R5 `Endpoint.connectionType` maps as RelatedTo to R4B `Endpoint.connectionType` - connectionType changed from array to scalar (max cardinality from * to 1); connectionType changed the binding strength from Example to Extensible; connectionType has change due to type change: R5 connectionType CodeableConcept has no equivalent or mapped type in R4B connectionType |
| Endpoint.contact | Endpoint.contact | Equivalent | R5 `Endpoint.contact` maps as Equivalent to R4B `Endpoint.contact` |
| Endpoint.contained | Endpoint.contained | Equivalent | R5 `Endpoint.contained` maps as Equivalent to R4B `Endpoint.contained` |
| Endpoint.description | - | DoesNotExistInTarget | R5 `Endpoint.description` does not appear in the target and has no mapping for `Endpoint`. |
| Endpoint.environmentType | - | DoesNotExistInTarget | R5 `Endpoint.environmentType` does not appear in the target and has no mapping for `Endpoint`. |
| Endpoint.extension | Endpoint.extension | SourceIsBroaderThanTarget | R5 `Endpoint.extension` maps as SourceIsBroaderThanTarget to R4B `Endpoint.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Endpoint.header | Endpoint.header | Equivalent | R5 `Endpoint.header` maps as Equivalent to R4B `Endpoint.header` |
| Endpoint.id | Endpoint.id | Equivalent | R5 `Endpoint.id` maps as Equivalent to R4B `Endpoint.id` |
| Endpoint.identifier | Endpoint.identifier | Equivalent | R5 `Endpoint.identifier` maps as Equivalent to R4B `Endpoint.identifier` |
| Endpoint.implicitRules | Endpoint.implicitRules | Equivalent | R5 `Endpoint.implicitRules` maps as Equivalent to R4B `Endpoint.implicitRules` |
| Endpoint.language | Endpoint.language | RelatedTo | R5 `Endpoint.language` maps as RelatedTo to R4B `Endpoint.language` - language changed the binding strength from Required to Preferred |
| Endpoint.managingOrganization | Endpoint.managingOrganization | Equivalent | R5 `Endpoint.managingOrganization` maps as Equivalent to R4B `Endpoint.managingOrganization` |
| Endpoint.meta | Endpoint.meta | Equivalent | R5 `Endpoint.meta` maps as Equivalent to R4B `Endpoint.meta` |
| Endpoint.modifierExtension | Endpoint.modifierExtension | SourceIsBroaderThanTarget | R5 `Endpoint.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Endpoint.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Endpoint.name | Endpoint.name | Equivalent | R5 `Endpoint.name` maps as Equivalent to R4B `Endpoint.name` |
| Endpoint.payload | - | DoesNotExistInTarget | R5 `Endpoint.payload` does not appear in the target and has no mapping for `Endpoint`. |
| Endpoint.payload.extension | - | DoesNotExistInTarget | R5 `Endpoint.payload.extension` does not appear in the target and has no mapping for `Endpoint`. |
| Endpoint.payload.id | - | DoesNotExistInTarget | R5 `Endpoint.payload.id` does not appear in the target and has no mapping for `Endpoint`. |
| Endpoint.payload.mimeType | - | DoesNotExistInTarget | R5 `Endpoint.payload.mimeType` does not appear in the target and has no mapping for `Endpoint`. |
| Endpoint.payload.modifierExtension | - | DoesNotExistInTarget | R5 `Endpoint.payload.modifierExtension` does not appear in the target and has no mapping for `Endpoint`. |
| Endpoint.payload.type | - | DoesNotExistInTarget | R5 `Endpoint.payload.type` does not appear in the target and has no mapping for `Endpoint`. |
| Endpoint.period | Endpoint.period | Equivalent | R5 `Endpoint.period` maps as Equivalent to R4B `Endpoint.period` |
| Endpoint.status | Endpoint.status | Equivalent | R5 `Endpoint.status` maps as Equivalent to R4B `Endpoint.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/endpoint-status|5.0.0 and http://hl7.org/fhir/ValueSet/endpoint-status|4.3.0 (Equivalent) |
| Endpoint.text | Endpoint.text | Equivalent | R5 `Endpoint.text` maps as Equivalent to R4B `Endpoint.text` |

