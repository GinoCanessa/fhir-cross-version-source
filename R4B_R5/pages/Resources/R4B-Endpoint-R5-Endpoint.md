Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Endpoint |  | The technical details of an endpoint that can be used for electronic services, such as for web services providing XDS.b or a REST endpoint for another FHIR server. This may include any security context information. | 20 | 12 |
| Target | Endpoint |  | The technical details of an endpoint that can be used for electronic services, such as for web services providing XDS.b, a REST endpoint for another FHIR server, or a s/Mime email address. This may include any security context information. | 26 | 15 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 14 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Endpoint | Endpoint | Equivalent | R4B `Endpoint` maps as Equivalent to R5 `Endpoint` |
| Endpoint.address | Endpoint.address | Equivalent | R4B `Endpoint.address` maps as Equivalent to R5 `Endpoint.address` |
| Endpoint.connectionType | Endpoint.connectionType | RelatedTo | R4B `Endpoint.connectionType` maps as RelatedTo to R5 `Endpoint.connectionType` - connectionType changed from scalar to array (max cardinality from 1 to *); connectionType changed the binding strength from Extensible to Example; connectionType has change due to type change: R4B connectionType Coding has no equivalent or mapped type in R5 connectionType |
| Endpoint.contact | Endpoint.contact | Equivalent | R4B `Endpoint.contact` maps as Equivalent to R5 `Endpoint.contact` |
| Endpoint.contained | Endpoint.contained | Equivalent | R4B `Endpoint.contained` maps as Equivalent to R5 `Endpoint.contained` |
| Endpoint.extension | Endpoint.extension | RelatedTo | R4B `Endpoint.extension` maps as RelatedTo to R5 `Endpoint.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Endpoint.header | Endpoint.header | Equivalent | R4B `Endpoint.header` maps as Equivalent to R5 `Endpoint.header` |
| Endpoint.id | Endpoint.id | Equivalent | R4B `Endpoint.id` maps as Equivalent to R5 `Endpoint.id` |
| Endpoint.identifier | Endpoint.identifier | Equivalent | R4B `Endpoint.identifier` maps as Equivalent to R5 `Endpoint.identifier` |
| Endpoint.implicitRules | Endpoint.implicitRules | Equivalent | R4B `Endpoint.implicitRules` maps as Equivalent to R5 `Endpoint.implicitRules` |
| Endpoint.language | Endpoint.language | RelatedTo | R4B `Endpoint.language` maps as RelatedTo to R5 `Endpoint.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Endpoint.managingOrganization | Endpoint.managingOrganization | Equivalent | R4B `Endpoint.managingOrganization` maps as Equivalent to R5 `Endpoint.managingOrganization` |
| Endpoint.meta | Endpoint.meta | Equivalent | R4B `Endpoint.meta` maps as Equivalent to R5 `Endpoint.meta` |
| Endpoint.modifierExtension | Endpoint.modifierExtension | RelatedTo | R4B `Endpoint.modifierExtension` maps as RelatedTo to R5 `Endpoint.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Endpoint.name | Endpoint.name | Equivalent | R4B `Endpoint.name` maps as Equivalent to R5 `Endpoint.name` |
| Endpoint.payloadMimeType | - | DoesNotExistInTarget | R4B `Endpoint.payloadMimeType` does not appear in the target and has no mapping for `Endpoint`. |
| Endpoint.payloadType | - | DoesNotExistInTarget | R4B `Endpoint.payloadType` does not appear in the target and has no mapping for `Endpoint`. |
| Endpoint.period | Endpoint.period | Equivalent | R4B `Endpoint.period` maps as Equivalent to R5 `Endpoint.period` |
| Endpoint.status | Endpoint.status | Equivalent | R4B `Endpoint.status` maps as Equivalent to R5 `Endpoint.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/endpoint-status|4.3.0 and http://hl7.org/fhir/ValueSet/endpoint-status|5.0.0 (Equivalent) |
| Endpoint.text | Endpoint.text | Equivalent | R4B `Endpoint.text` maps as Equivalent to R5 `Endpoint.text` |

