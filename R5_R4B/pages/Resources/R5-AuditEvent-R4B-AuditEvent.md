Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | AuditEvent |  | A record of an event relevant for purposes such as operations, privacy, security, maintenance, and performance analysis. | 59 | 36 |
| Target | AuditEvent |  | A record of an event made for purposes of maintaining a security log. Typical uses include detection of intrusion attempts and monitoring for inappropriate usage. | 62 | 39 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 16 |
Equivalent | 4 |
RelatedTo | 39 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| AuditEvent | AuditEvent | Equivalent | R5 `AuditEvent` maps as Equivalent to R4B `AuditEvent` |
| AuditEvent.action | AuditEvent.action | Equivalent | R5 `AuditEvent.action` maps as Equivalent to R4B `AuditEvent.action` - action has compatible required binding for code type: http://hl7.org/fhir/ValueSet/audit-event-action|5.0.0 and http://hl7.org/fhir/ValueSet/audit-event-action|4.3.0 (Equivalent) |
| AuditEvent.agent | AuditEvent.agent | Equivalent | R5 `AuditEvent.agent` maps as Equivalent to R4B `AuditEvent.agent` |
| AuditEvent.agent.authorization | - | DoesNotExistInTarget | R5 `AuditEvent.agent.authorization` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.agent.extension | AuditEvent.agent.extension | SourceIsBroaderThanTarget | R5 `AuditEvent.agent.extension` maps as SourceIsBroaderThanTarget to R4B `AuditEvent.agent.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| AuditEvent.agent.id | AuditEvent.agent.id | Equivalent | R5 `AuditEvent.agent.id` maps as Equivalent to R4B `AuditEvent.agent.id` |
| AuditEvent.agent.location | AuditEvent.agent.location | Equivalent | R5 `AuditEvent.agent.location` maps as Equivalent to R4B `AuditEvent.agent.location` |
| AuditEvent.agent.modifierExtension | AuditEvent.agent.modifierExtension | SourceIsBroaderThanTarget | R5 `AuditEvent.agent.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `AuditEvent.agent.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| AuditEvent.agent.network[x] | - | DoesNotExistInTarget | R5 `AuditEvent.agent.network[x]` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.agent.policy | AuditEvent.agent.policy | Equivalent | R5 `AuditEvent.agent.policy` maps as Equivalent to R4B `AuditEvent.agent.policy` |
| AuditEvent.agent.requestor | AuditEvent.agent.requestor | RelatedTo | R5 `AuditEvent.agent.requestor` maps as RelatedTo to R4B `AuditEvent.agent.requestor` - requestor made the element mandatory; requestor increased the minimum cardinality from 0 to 1 |
| AuditEvent.agent.role | AuditEvent.agent.role | Equivalent | R5 `AuditEvent.agent.role` maps as Equivalent to R4B `AuditEvent.agent.role` |
| AuditEvent.agent.type | AuditEvent.agent.type | RelatedTo | R5 `AuditEvent.agent.type` maps as RelatedTo to R4B `AuditEvent.agent.type` - type changed the binding strength from Preferred to Extensible |
| AuditEvent.agent.who | AuditEvent.agent.who | SourceIsBroaderThanTarget | R5 `AuditEvent.agent.who` maps as SourceIsBroaderThanTarget to R4B `AuditEvent.agent.who` - who has change due to type change: R5 `who` `Reference` maps as SourceIsBroaderThanTarget for R4B `who` |
| AuditEvent.authorization | - | DoesNotExistInTarget | R5 `AuditEvent.authorization` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.basedOn | - | DoesNotExistInTarget | R5 `AuditEvent.basedOn` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.category | - | DoesNotExistInTarget | R5 `AuditEvent.category` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.code | - | DoesNotExistInTarget | R5 `AuditEvent.code` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.contained | AuditEvent.contained | Equivalent | R5 `AuditEvent.contained` maps as Equivalent to R4B `AuditEvent.contained` |
| AuditEvent.encounter | - | DoesNotExistInTarget | R5 `AuditEvent.encounter` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.entity | AuditEvent.entity | Equivalent | R5 `AuditEvent.entity` maps as Equivalent to R4B `AuditEvent.entity` |
| AuditEvent.entity.agent | - | DoesNotExistInTarget | R5 `AuditEvent.entity.agent` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.entity.detail | AuditEvent.entity.detail | Equivalent | R5 `AuditEvent.entity.detail` maps as Equivalent to R4B `AuditEvent.entity.detail` |
| AuditEvent.entity.detail.extension | AuditEvent.entity.detail.extension | SourceIsBroaderThanTarget | R5 `AuditEvent.entity.detail.extension` maps as SourceIsBroaderThanTarget to R4B `AuditEvent.entity.detail.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| AuditEvent.entity.detail.id | AuditEvent.entity.detail.id | Equivalent | R5 `AuditEvent.entity.detail.id` maps as Equivalent to R4B `AuditEvent.entity.detail.id` |
| AuditEvent.entity.detail.modifierExtension | AuditEvent.entity.detail.modifierExtension | SourceIsBroaderThanTarget | R5 `AuditEvent.entity.detail.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `AuditEvent.entity.detail.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| AuditEvent.entity.detail.type | AuditEvent.entity.detail.type | RelatedTo | R5 `AuditEvent.entity.detail.type` maps as RelatedTo to R4B `AuditEvent.entity.detail.type` - type removed a binding requirement - Example http://hl7.org/fhir/ValueSet/audit-event-type; type has change due to type change: R5 type CodeableConcept has no equivalent or mapped type in R4B type |
| AuditEvent.entity.detail.value[x] | AuditEvent.entity.detail.value[x] | SourceIsBroaderThanTarget | R5 `AuditEvent.entity.detail.value[x]` maps as SourceIsBroaderThanTarget to R4B `AuditEvent.entity.detail.value[x]` - value[x] has change due to type change: R5 value[x] Quantity has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 value[x] CodeableConcept has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 value[x] boolean has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 value[x] integer has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 value[x] Range has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 value[x] Ratio has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 value[x] time has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 value[x] dateTime has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 value[x] Period has no equivalent or mapped type in R4B value[x] |
| AuditEvent.entity.extension | AuditEvent.entity.extension | SourceIsBroaderThanTarget | R5 `AuditEvent.entity.extension` maps as SourceIsBroaderThanTarget to R4B `AuditEvent.entity.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| AuditEvent.entity.id | AuditEvent.entity.id | Equivalent | R5 `AuditEvent.entity.id` maps as Equivalent to R4B `AuditEvent.entity.id` |
| AuditEvent.entity.modifierExtension | AuditEvent.entity.modifierExtension | SourceIsBroaderThanTarget | R5 `AuditEvent.entity.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `AuditEvent.entity.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| AuditEvent.entity.query | AuditEvent.entity.query | Equivalent | R5 `AuditEvent.entity.query` maps as Equivalent to R4B `AuditEvent.entity.query` |
| AuditEvent.entity.role | AuditEvent.entity.role | RelatedTo | R5 `AuditEvent.entity.role` maps as RelatedTo to R4B `AuditEvent.entity.role` - role changed the binding strength from Example to Extensible; role has change due to type change: R5 role CodeableConcept has no equivalent or mapped type in R4B role |
| AuditEvent.entity.securityLabel | AuditEvent.entity.securityLabel | RelatedTo | R5 `AuditEvent.entity.securityLabel` maps as RelatedTo to R4B `AuditEvent.entity.securityLabel` - securityLabel changed the binding strength from Example to Extensible; securityLabel has change due to type change: R5 securityLabel CodeableConcept has no equivalent or mapped type in R4B securityLabel |
| AuditEvent.entity.what | AuditEvent.entity.what | Equivalent | R5 `AuditEvent.entity.what` maps as Equivalent to R4B `AuditEvent.entity.what` |
| AuditEvent.extension | AuditEvent.extension | SourceIsBroaderThanTarget | R5 `AuditEvent.extension` maps as SourceIsBroaderThanTarget to R4B `AuditEvent.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| AuditEvent.id | AuditEvent.id | Equivalent | R5 `AuditEvent.id` maps as Equivalent to R4B `AuditEvent.id` |
| AuditEvent.implicitRules | AuditEvent.implicitRules | Equivalent | R5 `AuditEvent.implicitRules` maps as Equivalent to R4B `AuditEvent.implicitRules` |
| AuditEvent.language | AuditEvent.language | RelatedTo | R5 `AuditEvent.language` maps as RelatedTo to R4B `AuditEvent.language` - language changed the binding strength from Required to Preferred |
| AuditEvent.meta | AuditEvent.meta | Equivalent | R5 `AuditEvent.meta` maps as Equivalent to R4B `AuditEvent.meta` |
| AuditEvent.modifierExtension | AuditEvent.modifierExtension | SourceIsBroaderThanTarget | R5 `AuditEvent.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `AuditEvent.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| AuditEvent.occurred[x] | - | DoesNotExistInTarget | R5 `AuditEvent.occurred[x]` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.outcome | AuditEvent.outcome | RelatedTo | R5 `AuditEvent.outcome` maps as RelatedTo to R4B `AuditEvent.outcome` - outcome added a required binding to http://hl7.org/fhir/ValueSet/audit-event-outcome|4.3.0; outcome has change due to type change: R5 outcome BackboneElement has no equivalent or mapped type in R4B outcome |
| AuditEvent.outcome.code | - | DoesNotExistInTarget | R5 `AuditEvent.outcome.code` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.outcome.detail | - | DoesNotExistInTarget | R5 `AuditEvent.outcome.detail` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.outcome.extension | - | DoesNotExistInTarget | R5 `AuditEvent.outcome.extension` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.outcome.id | - | DoesNotExistInTarget | R5 `AuditEvent.outcome.id` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.outcome.modifierExtension | - | DoesNotExistInTarget | R5 `AuditEvent.outcome.modifierExtension` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.patient | - | DoesNotExistInTarget | R5 `AuditEvent.patient` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.recorded | AuditEvent.recorded | Equivalent | R5 `AuditEvent.recorded` maps as Equivalent to R4B `AuditEvent.recorded` |
| AuditEvent.severity | - | DoesNotExistInTarget | R5 `AuditEvent.severity` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.source | AuditEvent.source | Equivalent | R5 `AuditEvent.source` maps as Equivalent to R4B `AuditEvent.source` |
| AuditEvent.source.extension | AuditEvent.source.extension | SourceIsBroaderThanTarget | R5 `AuditEvent.source.extension` maps as SourceIsBroaderThanTarget to R4B `AuditEvent.source.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| AuditEvent.source.id | AuditEvent.source.id | Equivalent | R5 `AuditEvent.source.id` maps as Equivalent to R4B `AuditEvent.source.id` |
| AuditEvent.source.modifierExtension | AuditEvent.source.modifierExtension | SourceIsBroaderThanTarget | R5 `AuditEvent.source.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `AuditEvent.source.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| AuditEvent.source.observer | AuditEvent.source.observer | SourceIsBroaderThanTarget | R5 `AuditEvent.source.observer` maps as SourceIsBroaderThanTarget to R4B `AuditEvent.source.observer` - observer has change due to type change: R5 `observer` `Reference` maps as SourceIsBroaderThanTarget for R4B `observer` |
| AuditEvent.source.site | AuditEvent.source.site | SourceIsBroaderThanTarget | R5 `AuditEvent.source.site` maps as SourceIsBroaderThanTarget to R4B `AuditEvent.source.site` - site has change due to type change: R5 site Reference has no equivalent or mapped type in R4B site |
| AuditEvent.source.type | AuditEvent.source.type | RelatedTo | R5 `AuditEvent.source.type` maps as RelatedTo to R4B `AuditEvent.source.type` - type changed the binding strength from Preferred to Extensible; type has change due to type change: R5 type CodeableConcept has no equivalent or mapped type in R4B type |
| AuditEvent.text | AuditEvent.text | Equivalent | R5 `AuditEvent.text` maps as Equivalent to R4B `AuditEvent.text` |

