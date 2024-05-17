Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | AuditEvent |  | A record of an event made for purposes of maintaining a security log. Typical uses include detection of intrusion attempts and monitoring for inappropriate usage. | 62 | 39 |
| Target | AuditEvent |  | A record of an event relevant for purposes such as operations, privacy, security, maintenance, and performance analysis. | 59 | 36 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 19 |
Equivalent | 4 |
RelatedTo | 39 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| AuditEvent | AuditEvent | Equivalent | R4B `AuditEvent` maps as Equivalent to R5 `AuditEvent` |
| AuditEvent.action | AuditEvent.action | Equivalent | R4B `AuditEvent.action` maps as Equivalent to R5 `AuditEvent.action` - action has compatible required binding for code type: http://hl7.org/fhir/ValueSet/audit-event-action|4.3.0 and http://hl7.org/fhir/ValueSet/audit-event-action|5.0.0 (Equivalent) |
| AuditEvent.agent | AuditEvent.agent | Equivalent | R4B `AuditEvent.agent` maps as Equivalent to R5 `AuditEvent.agent` |
| AuditEvent.agent.altId | - | DoesNotExistInTarget | R4B `AuditEvent.agent.altId` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.agent.extension | AuditEvent.agent.extension | RelatedTo | R4B `AuditEvent.agent.extension` maps as RelatedTo to R5 `AuditEvent.agent.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| AuditEvent.agent.id | AuditEvent.agent.id | Equivalent | R4B `AuditEvent.agent.id` maps as Equivalent to R5 `AuditEvent.agent.id` |
| AuditEvent.agent.location | AuditEvent.agent.location | Equivalent | R4B `AuditEvent.agent.location` maps as Equivalent to R5 `AuditEvent.agent.location` |
| AuditEvent.agent.media | - | DoesNotExistInTarget | R4B `AuditEvent.agent.media` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.agent.modifierExtension | AuditEvent.agent.modifierExtension | RelatedTo | R4B `AuditEvent.agent.modifierExtension` maps as RelatedTo to R5 `AuditEvent.agent.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| AuditEvent.agent.name | - | DoesNotExistInTarget | R4B `AuditEvent.agent.name` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.agent.network | - | DoesNotExistInTarget | R4B `AuditEvent.agent.network` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.agent.network.address | - | DoesNotExistInTarget | R4B `AuditEvent.agent.network.address` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.agent.network.extension | - | DoesNotExistInTarget | R4B `AuditEvent.agent.network.extension` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.agent.network.id | - | DoesNotExistInTarget | R4B `AuditEvent.agent.network.id` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.agent.network.modifierExtension | - | DoesNotExistInTarget | R4B `AuditEvent.agent.network.modifierExtension` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.agent.network.type | - | DoesNotExistInTarget | R4B `AuditEvent.agent.network.type` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.agent.policy | AuditEvent.agent.policy | Equivalent | R4B `AuditEvent.agent.policy` maps as Equivalent to R5 `AuditEvent.agent.policy` |
| AuditEvent.agent.purposeOfUse | - | DoesNotExistInTarget | R4B `AuditEvent.agent.purposeOfUse` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.agent.requestor | AuditEvent.agent.requestor | Equivalent | R4B `AuditEvent.agent.requestor` maps as Equivalent to R5 `AuditEvent.agent.requestor` |
| AuditEvent.agent.role | AuditEvent.agent.role | Equivalent | R4B `AuditEvent.agent.role` maps as Equivalent to R5 `AuditEvent.agent.role` |
| AuditEvent.agent.type | AuditEvent.agent.type | RelatedTo | R4B `AuditEvent.agent.type` maps as RelatedTo to R5 `AuditEvent.agent.type` - type changed the binding strength from Extensible to Preferred |
| AuditEvent.agent.who | AuditEvent.agent.who | RelatedTo | R4B `AuditEvent.agent.who` maps as RelatedTo to R5 `AuditEvent.agent.who` - who made the element mandatory; who increased the minimum cardinality from 0 to 1; who has change due to type change: R4B `who` `Reference` maps as SourceIsNarrowerThanTarget for R5 `who` |
| AuditEvent.contained | AuditEvent.contained | Equivalent | R4B `AuditEvent.contained` maps as Equivalent to R5 `AuditEvent.contained` |
| AuditEvent.entity | AuditEvent.entity | Equivalent | R4B `AuditEvent.entity` maps as Equivalent to R5 `AuditEvent.entity` |
| AuditEvent.entity.description | - | DoesNotExistInTarget | R4B `AuditEvent.entity.description` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.entity.detail | AuditEvent.entity.detail | Equivalent | R4B `AuditEvent.entity.detail` maps as Equivalent to R5 `AuditEvent.entity.detail` |
| AuditEvent.entity.detail.extension | AuditEvent.entity.detail.extension | RelatedTo | R4B `AuditEvent.entity.detail.extension` maps as RelatedTo to R5 `AuditEvent.entity.detail.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| AuditEvent.entity.detail.id | AuditEvent.entity.detail.id | Equivalent | R4B `AuditEvent.entity.detail.id` maps as Equivalent to R5 `AuditEvent.entity.detail.id` |
| AuditEvent.entity.detail.modifierExtension | AuditEvent.entity.detail.modifierExtension | RelatedTo | R4B `AuditEvent.entity.detail.modifierExtension` maps as RelatedTo to R5 `AuditEvent.entity.detail.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| AuditEvent.entity.detail.type | AuditEvent.entity.detail.type | RelatedTo | R4B `AuditEvent.entity.detail.type` maps as RelatedTo to R5 `AuditEvent.entity.detail.type` - type added a binding requirement - Example http://hl7.org/fhir/ValueSet/audit-event-type; type has change due to type change: R4B type string has no equivalent or mapped type in R5 type |
| AuditEvent.entity.detail.value[x] | AuditEvent.entity.detail.value[x] | Equivalent | R4B `AuditEvent.entity.detail.value[x]` maps as Equivalent to R5 `AuditEvent.entity.detail.value[x]` |
| AuditEvent.entity.extension | AuditEvent.entity.extension | RelatedTo | R4B `AuditEvent.entity.extension` maps as RelatedTo to R5 `AuditEvent.entity.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| AuditEvent.entity.id | AuditEvent.entity.id | Equivalent | R4B `AuditEvent.entity.id` maps as Equivalent to R5 `AuditEvent.entity.id` |
| AuditEvent.entity.lifecycle | - | DoesNotExistInTarget | R4B `AuditEvent.entity.lifecycle` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.entity.modifierExtension | AuditEvent.entity.modifierExtension | RelatedTo | R4B `AuditEvent.entity.modifierExtension` maps as RelatedTo to R5 `AuditEvent.entity.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| AuditEvent.entity.name | - | DoesNotExistInTarget | R4B `AuditEvent.entity.name` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.entity.query | AuditEvent.entity.query | Equivalent | R4B `AuditEvent.entity.query` maps as Equivalent to R5 `AuditEvent.entity.query` |
| AuditEvent.entity.role | AuditEvent.entity.role | RelatedTo | R4B `AuditEvent.entity.role` maps as RelatedTo to R5 `AuditEvent.entity.role` - role changed the binding strength from Extensible to Example; role has change due to type change: R4B role Coding has no equivalent or mapped type in R5 role |
| AuditEvent.entity.securityLabel | AuditEvent.entity.securityLabel | RelatedTo | R4B `AuditEvent.entity.securityLabel` maps as RelatedTo to R5 `AuditEvent.entity.securityLabel` - securityLabel changed the binding strength from Extensible to Example; securityLabel has change due to type change: R4B securityLabel Coding has no equivalent or mapped type in R5 securityLabel |
| AuditEvent.entity.type | - | DoesNotExistInTarget | R4B `AuditEvent.entity.type` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.entity.what | AuditEvent.entity.what | Equivalent | R4B `AuditEvent.entity.what` maps as Equivalent to R5 `AuditEvent.entity.what` |
| AuditEvent.extension | AuditEvent.extension | RelatedTo | R4B `AuditEvent.extension` maps as RelatedTo to R5 `AuditEvent.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| AuditEvent.id | AuditEvent.id | Equivalent | R4B `AuditEvent.id` maps as Equivalent to R5 `AuditEvent.id` |
| AuditEvent.implicitRules | AuditEvent.implicitRules | Equivalent | R4B `AuditEvent.implicitRules` maps as Equivalent to R5 `AuditEvent.implicitRules` |
| AuditEvent.language | AuditEvent.language | RelatedTo | R4B `AuditEvent.language` maps as RelatedTo to R5 `AuditEvent.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| AuditEvent.meta | AuditEvent.meta | Equivalent | R4B `AuditEvent.meta` maps as Equivalent to R5 `AuditEvent.meta` |
| AuditEvent.modifierExtension | AuditEvent.modifierExtension | RelatedTo | R4B `AuditEvent.modifierExtension` maps as RelatedTo to R5 `AuditEvent.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| AuditEvent.outcome | AuditEvent.outcome | RelatedTo | R4B `AuditEvent.outcome` maps as RelatedTo to R5 `AuditEvent.outcome` - outcome removed a binding requirement - Required http://hl7.org/fhir/ValueSet/audit-event-outcome|4.3.0; outcome has change due to type change: R4B outcome code has no equivalent or mapped type in R5 outcome |
| AuditEvent.outcomeDesc | - | DoesNotExistInTarget | R4B `AuditEvent.outcomeDesc` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.period | - | DoesNotExistInTarget | R4B `AuditEvent.period` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.purposeOfEvent | - | DoesNotExistInTarget | R4B `AuditEvent.purposeOfEvent` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.recorded | AuditEvent.recorded | Equivalent | R4B `AuditEvent.recorded` maps as Equivalent to R5 `AuditEvent.recorded` |
| AuditEvent.source | AuditEvent.source | Equivalent | R4B `AuditEvent.source` maps as Equivalent to R5 `AuditEvent.source` |
| AuditEvent.source.extension | AuditEvent.source.extension | RelatedTo | R4B `AuditEvent.source.extension` maps as RelatedTo to R5 `AuditEvent.source.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| AuditEvent.source.id | AuditEvent.source.id | Equivalent | R4B `AuditEvent.source.id` maps as Equivalent to R5 `AuditEvent.source.id` |
| AuditEvent.source.modifierExtension | AuditEvent.source.modifierExtension | RelatedTo | R4B `AuditEvent.source.modifierExtension` maps as RelatedTo to R5 `AuditEvent.source.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| AuditEvent.source.observer | AuditEvent.source.observer | SourceIsNarrowerThanTarget | R4B `AuditEvent.source.observer` maps as SourceIsNarrowerThanTarget to R5 `AuditEvent.source.observer` - observer has change due to type change: R4B `observer` `Reference` maps as SourceIsNarrowerThanTarget for R5 `observer` |
| AuditEvent.source.site | AuditEvent.source.site | SourceIsBroaderThanTarget | R4B `AuditEvent.source.site` maps as SourceIsBroaderThanTarget to R5 `AuditEvent.source.site` - site has change due to type change: R4B site string has no equivalent or mapped type in R5 site |
| AuditEvent.source.type | AuditEvent.source.type | RelatedTo | R4B `AuditEvent.source.type` maps as RelatedTo to R5 `AuditEvent.source.type` - type changed the binding strength from Extensible to Preferred; type has change due to type change: R4B type Coding has no equivalent or mapped type in R5 type |
| AuditEvent.subtype | - | DoesNotExistInTarget | R4B `AuditEvent.subtype` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.text | AuditEvent.text | Equivalent | R4B `AuditEvent.text` maps as Equivalent to R5 `AuditEvent.text` |
| AuditEvent.type | - | DoesNotExistInTarget | R4B `AuditEvent.type` does not appear in the target and has no mapping for `AuditEvent`. |

