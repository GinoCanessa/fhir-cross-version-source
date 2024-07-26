Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:50 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Bundle |  | A container for a collection of resources. | 49 | 30 |
| Target | Bundle |  | A container for a collection of resources. | 48 | 29 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 44 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Bundle | Bundle | Equivalent | R5 `Bundle` maps as Equivalent to R4 `Bundle` |
| Bundle.entry | Bundle.entry | Equivalent | R5 `Bundle.entry` maps as Equivalent to R4 `Bundle.entry` |
| Bundle.entry.extension | Bundle.entry.extension | SourceIsBroaderThanTarget | R5 `Bundle.entry.extension` maps as SourceIsBroaderThanTarget to R4 `Bundle.entry.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Bundle.entry.fullUrl | Bundle.entry.fullUrl | Equivalent | R5 `Bundle.entry.fullUrl` maps as Equivalent to R4 `Bundle.entry.fullUrl` |
| Bundle.entry.id | Bundle.entry.id | Equivalent | R5 `Bundle.entry.id` maps as Equivalent to R4 `Bundle.entry.id` |
| Bundle.entry.link | Bundle.entry.link | Equivalent | R5 `Bundle.entry.link` maps as Equivalent to R4 `Bundle.entry.link` |
| Bundle.entry.modifierExtension | Bundle.entry.modifierExtension | SourceIsBroaderThanTarget | R5 `Bundle.entry.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Bundle.entry.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Bundle.entry.request | Bundle.entry.request | Equivalent | R5 `Bundle.entry.request` maps as Equivalent to R4 `Bundle.entry.request` |
| Bundle.entry.request.extension | Bundle.entry.request.extension | SourceIsBroaderThanTarget | R5 `Bundle.entry.request.extension` maps as SourceIsBroaderThanTarget to R4 `Bundle.entry.request.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Bundle.entry.request.id | Bundle.entry.request.id | Equivalent | R5 `Bundle.entry.request.id` maps as Equivalent to R4 `Bundle.entry.request.id` |
| Bundle.entry.request.ifMatch | Bundle.entry.request.ifMatch | Equivalent | R5 `Bundle.entry.request.ifMatch` maps as Equivalent to R4 `Bundle.entry.request.ifMatch` |
| Bundle.entry.request.ifModifiedSince | Bundle.entry.request.ifModifiedSince | Equivalent | R5 `Bundle.entry.request.ifModifiedSince` maps as Equivalent to R4 `Bundle.entry.request.ifModifiedSince` |
| Bundle.entry.request.ifNoneExist | Bundle.entry.request.ifNoneExist | Equivalent | R5 `Bundle.entry.request.ifNoneExist` maps as Equivalent to R4 `Bundle.entry.request.ifNoneExist` |
| Bundle.entry.request.ifNoneMatch | Bundle.entry.request.ifNoneMatch | Equivalent | R5 `Bundle.entry.request.ifNoneMatch` maps as Equivalent to R4 `Bundle.entry.request.ifNoneMatch` |
| Bundle.entry.request.method | Bundle.entry.request.method | Equivalent | R5 `Bundle.entry.request.method` maps as Equivalent to R4 `Bundle.entry.request.method` - method has compatible required binding for code type: http://hl7.org/fhir/ValueSet/http-verb|5.0.0 and http://hl7.org/fhir/ValueSet/http-verb|4.0.1 (Equivalent) |
| Bundle.entry.request.modifierExtension | Bundle.entry.request.modifierExtension | SourceIsBroaderThanTarget | R5 `Bundle.entry.request.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Bundle.entry.request.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Bundle.entry.request.url | Bundle.entry.request.url | Equivalent | R5 `Bundle.entry.request.url` maps as Equivalent to R4 `Bundle.entry.request.url` |
| Bundle.entry.resource | Bundle.entry.resource | Equivalent | R5 `Bundle.entry.resource` maps as Equivalent to R4 `Bundle.entry.resource` |
| Bundle.entry.response | Bundle.entry.response | Equivalent | R5 `Bundle.entry.response` maps as Equivalent to R4 `Bundle.entry.response` |
| Bundle.entry.response.etag | Bundle.entry.response.etag | Equivalent | R5 `Bundle.entry.response.etag` maps as Equivalent to R4 `Bundle.entry.response.etag` |
| Bundle.entry.response.extension | Bundle.entry.response.extension | SourceIsBroaderThanTarget | R5 `Bundle.entry.response.extension` maps as SourceIsBroaderThanTarget to R4 `Bundle.entry.response.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Bundle.entry.response.id | Bundle.entry.response.id | Equivalent | R5 `Bundle.entry.response.id` maps as Equivalent to R4 `Bundle.entry.response.id` |
| Bundle.entry.response.lastModified | Bundle.entry.response.lastModified | Equivalent | R5 `Bundle.entry.response.lastModified` maps as Equivalent to R4 `Bundle.entry.response.lastModified` |
| Bundle.entry.response.location | Bundle.entry.response.location | Equivalent | R5 `Bundle.entry.response.location` maps as Equivalent to R4 `Bundle.entry.response.location` |
| Bundle.entry.response.modifierExtension | Bundle.entry.response.modifierExtension | SourceIsBroaderThanTarget | R5 `Bundle.entry.response.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Bundle.entry.response.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Bundle.entry.response.outcome | Bundle.entry.response.outcome | Equivalent | R5 `Bundle.entry.response.outcome` maps as Equivalent to R4 `Bundle.entry.response.outcome` |
| Bundle.entry.response.status | Bundle.entry.response.status | Equivalent | R5 `Bundle.entry.response.status` maps as Equivalent to R4 `Bundle.entry.response.status` |
| Bundle.entry.search | Bundle.entry.search | Equivalent | R5 `Bundle.entry.search` maps as Equivalent to R4 `Bundle.entry.search` |
| Bundle.entry.search.extension | Bundle.entry.search.extension | SourceIsBroaderThanTarget | R5 `Bundle.entry.search.extension` maps as SourceIsBroaderThanTarget to R4 `Bundle.entry.search.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Bundle.entry.search.id | Bundle.entry.search.id | Equivalent | R5 `Bundle.entry.search.id` maps as Equivalent to R4 `Bundle.entry.search.id` |
| Bundle.entry.search.mode | Bundle.entry.search.mode | Equivalent | R5 `Bundle.entry.search.mode` maps as Equivalent to R4 `Bundle.entry.search.mode` - mode has compatible required binding for code type: http://hl7.org/fhir/ValueSet/search-entry-mode|5.0.0 and http://hl7.org/fhir/ValueSet/search-entry-mode|4.0.1 (Equivalent) |
| Bundle.entry.search.modifierExtension | Bundle.entry.search.modifierExtension | SourceIsBroaderThanTarget | R5 `Bundle.entry.search.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Bundle.entry.search.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Bundle.entry.search.score | Bundle.entry.search.score | Equivalent | R5 `Bundle.entry.search.score` maps as Equivalent to R4 `Bundle.entry.search.score` |
| Bundle.id | Bundle.id | Equivalent | R5 `Bundle.id` maps as Equivalent to R4 `Bundle.id` |
| Bundle.identifier | Bundle.identifier | Equivalent | R5 `Bundle.identifier` maps as Equivalent to R4 `Bundle.identifier` |
| Bundle.implicitRules | Bundle.implicitRules | Equivalent | R5 `Bundle.implicitRules` maps as Equivalent to R4 `Bundle.implicitRules` |
| Bundle.issues | - | DoesNotExistInTarget | R5 `Bundle.issues` does not appear in the target and has no mapping for `Bundle`. |
| Bundle.language | Bundle.language | RelatedTo | R5 `Bundle.language` maps as RelatedTo to R4 `Bundle.language` - language changed the binding strength from Required to Preferred |
| Bundle.link | Bundle.link | Equivalent | R5 `Bundle.link` maps as Equivalent to R4 `Bundle.link` |
| Bundle.link.extension | Bundle.link.extension | SourceIsBroaderThanTarget | R5 `Bundle.link.extension` maps as SourceIsBroaderThanTarget to R4 `Bundle.link.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Bundle.link.id | Bundle.link.id | Equivalent | R5 `Bundle.link.id` maps as Equivalent to R4 `Bundle.link.id` |
| Bundle.link.modifierExtension | Bundle.link.modifierExtension | SourceIsBroaderThanTarget | R5 `Bundle.link.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Bundle.link.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Bundle.link.relation | Bundle.link.relation | RelatedTo | R5 `Bundle.link.relation` maps as RelatedTo to R4 `Bundle.link.relation` - relation removed a binding requirement - Required http://hl7.org/fhir/ValueSet/iana-link-relations|5.0.0; relation has change due to type change: R5 relation code has no equivalent or mapped type in R4 relation |
| Bundle.link.url | Bundle.link.url | Equivalent | R5 `Bundle.link.url` maps as Equivalent to R4 `Bundle.link.url` |
| Bundle.meta | Bundle.meta | Equivalent | R5 `Bundle.meta` maps as Equivalent to R4 `Bundle.meta` |
| Bundle.signature | Bundle.signature | RelatedTo | R5 `Bundle.signature` maps as RelatedTo to R4 `Bundle.signature` - signature has change due to type change: R5 `signature` `Signature` maps as RelatedTo for R4 `signature` |
| Bundle.timestamp | Bundle.timestamp | Equivalent | R5 `Bundle.timestamp` maps as Equivalent to R4 `Bundle.timestamp` |
| Bundle.total | Bundle.total | Equivalent | R5 `Bundle.total` maps as Equivalent to R4 `Bundle.total` |
| Bundle.type | Bundle.type | Equivalent | R5 `Bundle.type` maps as Equivalent to R4 `Bundle.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/bundle-type|5.0.0 and http://hl7.org/fhir/ValueSet/bundle-type|4.0.1 (Equivalent) |

