Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | AuditEvent |  | A record of an event relevant for purposes such as operations, privacy, security, maintenance, and performance analysis. | 59 | 36 |
| Target | AuditEvent |  | A record of an event made for purposes of maintaining a security log. Typical uses include detection of intrusion attempts and monitoring for inappropriate usage. | 62 | 39 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 9 |
Equivalent | 21 |
RelatedTo | 6 |
SourceIsBroaderThanTarget | 22 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| AuditEvent | AuditEvent | Equivalent | R5 `AuditEvent` maps as Equivalent to R4 `AuditEvent` |
| AuditEvent.action | AuditEvent.action | Equivalent | R5 `AuditEvent.action` maps as Equivalent to R4 `AuditEvent.action` - action has compatible required binding for code type: http://hl7.org/fhir/ValueSet/audit-event-action|5.0.0 and http://hl7.org/fhir/ValueSet/audit-event-action|4.0.1 (Equivalent) |
| AuditEvent.agent | AuditEvent.agent | Equivalent | R5 `AuditEvent.agent` maps as Equivalent to R4 `AuditEvent.agent` |
| AuditEvent.agent.authorization | AuditEvent.agent.purposeOfUse | SourceIsBroaderThanTarget | R5 `AuditEvent.agent.authorization` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.agent.purposeOfUse` - purposeOfUse changed the binding strength from Example to Extensible; purposeOfUse has change due to type change: R5 `authorization` `CodeableConcept` maps as SourceIsBroaderThanTarget for R4 `purposeOfUse` |
| AuditEvent.agent.extension | AuditEvent.agent.extension | SourceIsBroaderThanTarget | R5 `AuditEvent.agent.extension` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.agent.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| AuditEvent.agent.id | AuditEvent.agent.id | Equivalent | R5 `AuditEvent.agent.id` maps as Equivalent to R4 `AuditEvent.agent.id` |
| AuditEvent.agent.location | AuditEvent.agent.location | Equivalent | R5 `AuditEvent.agent.location` maps as Equivalent to R4 `AuditEvent.agent.location` |
| AuditEvent.agent.modifierExtension | AuditEvent.agent.modifierExtension | SourceIsBroaderThanTarget | R5 `AuditEvent.agent.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.agent.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| AuditEvent.agent.network[x] | AuditEvent.agent.network | SourceIsBroaderThanTarget | R5 `AuditEvent.agent.network[x]` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.agent.network` - network has change due to type change: R5 network[x] Reference has no equivalent or mapped type in R4 network; network has change due to type change: R5 network[x] uri has no equivalent or mapped type in R4 network; network has change due to type change: R5 network[x] string has no equivalent or mapped type in R4 network |
| AuditEvent.agent.network[x] | AuditEvent.agent.network | SourceIsBroaderThanTarget | R5 `AuditEvent.agent.network[x]` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.agent.network` - network has change due to type change: R5 network[x] Reference has no equivalent or mapped type in R4 network; network has change due to type change: R5 network[x] uri has no equivalent or mapped type in R4 network; network has change due to type change: R5 network[x] string has no equivalent or mapped type in R4 network |
| AuditEvent.agent.policy | AuditEvent.agent.policy | Equivalent | R5 `AuditEvent.agent.policy` maps as Equivalent to R4 `AuditEvent.agent.policy` |
| AuditEvent.agent.requestor | AuditEvent.agent.requestor | RelatedTo | R5 `AuditEvent.agent.requestor` maps as RelatedTo to R4 `AuditEvent.agent.requestor` - requestor made the element mandatory; requestor increased the minimum cardinality from 0 to 1 |
| AuditEvent.agent.role | AuditEvent.agent.role | Equivalent | R5 `AuditEvent.agent.role` maps as Equivalent to R4 `AuditEvent.agent.role` |
| AuditEvent.agent.type | AuditEvent.agent.type | SourceIsBroaderThanTarget | R5 `AuditEvent.agent.type` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.agent.type` - type changed the binding strength from Preferred to Extensible; type has change due to type change: R5 `type` `CodeableConcept` maps as SourceIsBroaderThanTarget for R4 `type` |
| AuditEvent.agent.who | AuditEvent.agent.who | SourceIsBroaderThanTarget | R5 `AuditEvent.agent.who` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.agent.who` - who has change due to type change: R5 `who` `Reference` maps as SourceIsBroaderThanTarget for R4 `who` |
| AuditEvent.authorization | AuditEvent.purposeOfEvent | SourceIsBroaderThanTarget | R5 `AuditEvent.authorization` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.purposeOfEvent` - purposeOfEvent changed the binding strength from Example to Extensible; purposeOfEvent has change due to type change: R5 `authorization` `CodeableConcept` maps as SourceIsBroaderThanTarget for R4 `purposeOfEvent` |
| AuditEvent.basedOn | - | DoesNotExistInTarget | R5 `AuditEvent.basedOn` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.category | AuditEvent.type | RelatedTo | R5 `AuditEvent.category` maps as RelatedTo to R4 `AuditEvent.type` - type made the element mandatory; type increased the minimum cardinality from 0 to 1; type changed from array to scalar (max cardinality from * to 1); type changed the binding strength from Example to Extensible; type has change due to type change: R5 category CodeableConcept has no equivalent or mapped type in R4 type |
| AuditEvent.code | AuditEvent.subtype | RelatedTo | R5 `AuditEvent.code` maps as RelatedTo to R4 `AuditEvent.subtype` - subtype changed from scalar to array (max cardinality from 1 to *); subtype changed the binding strength from Example to Extensible; subtype has change due to type change: R5 code CodeableConcept has no equivalent or mapped type in R4 subtype |
| AuditEvent.contained | AuditEvent.contained | Equivalent | R5 `AuditEvent.contained` maps as Equivalent to R4 `AuditEvent.contained` |
| AuditEvent.encounter | - | DoesNotExistInTarget | R5 `AuditEvent.encounter` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.entity | AuditEvent.entity | Equivalent | R5 `AuditEvent.entity` maps as Equivalent to R4 `AuditEvent.entity` |
| AuditEvent.entity.agent | - | DoesNotExistInTarget | R5 `AuditEvent.entity.agent` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.entity.detail | AuditEvent.entity.detail | Equivalent | R5 `AuditEvent.entity.detail` maps as Equivalent to R4 `AuditEvent.entity.detail` |
| AuditEvent.entity.detail.extension | AuditEvent.entity.detail.extension | SourceIsBroaderThanTarget | R5 `AuditEvent.entity.detail.extension` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.entity.detail.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| AuditEvent.entity.detail.id | AuditEvent.entity.detail.id | Equivalent | R5 `AuditEvent.entity.detail.id` maps as Equivalent to R4 `AuditEvent.entity.detail.id` |
| AuditEvent.entity.detail.modifierExtension | AuditEvent.entity.detail.modifierExtension | SourceIsBroaderThanTarget | R5 `AuditEvent.entity.detail.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.entity.detail.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| AuditEvent.entity.detail.type | AuditEvent.entity.detail.type | RelatedTo | R5 `AuditEvent.entity.detail.type` maps as RelatedTo to R4 `AuditEvent.entity.detail.type` - type removed a binding requirement - Example http://hl7.org/fhir/ValueSet/audit-event-type; type has change due to type change: R5 type CodeableConcept has no equivalent or mapped type in R4 type |
| AuditEvent.entity.detail.value[x] | AuditEvent.entity.detail.value[x] | SourceIsBroaderThanTarget | R5 `AuditEvent.entity.detail.value[x]` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.entity.detail.value[x]` - value[x] has change due to type change: R5 value[x] Quantity has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 value[x] CodeableConcept has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 value[x] boolean has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 value[x] integer has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 value[x] Range has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 value[x] Ratio has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 value[x] time has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 value[x] dateTime has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 value[x] Period has no equivalent or mapped type in R4 value[x] |
| AuditEvent.entity.extension | AuditEvent.entity.extension | SourceIsBroaderThanTarget | R5 `AuditEvent.entity.extension` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.entity.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| AuditEvent.entity.id | AuditEvent.entity.id | Equivalent | R5 `AuditEvent.entity.id` maps as Equivalent to R4 `AuditEvent.entity.id` |
| AuditEvent.entity.modifierExtension | AuditEvent.entity.modifierExtension | SourceIsBroaderThanTarget | R5 `AuditEvent.entity.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.entity.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| AuditEvent.entity.query | AuditEvent.entity.query | Equivalent | R5 `AuditEvent.entity.query` maps as Equivalent to R4 `AuditEvent.entity.query` |
| AuditEvent.entity.role | AuditEvent.entity.role | SourceIsBroaderThanTarget | R5 `AuditEvent.entity.role` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.entity.role` - role changed the binding strength from Example to Extensible; role has change due to type change: R5 role CodeableConcept has no equivalent or mapped type in R4 role |
| AuditEvent.entity.securityLabel | AuditEvent.entity.securityLabel | SourceIsBroaderThanTarget | R5 `AuditEvent.entity.securityLabel` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.entity.securityLabel` - securityLabel changed the binding strength from Example to Extensible; securityLabel has change due to type change: R5 securityLabel CodeableConcept has no equivalent or mapped type in R4 securityLabel |
| AuditEvent.entity.what | AuditEvent.entity.what | Equivalent | R5 `AuditEvent.entity.what` maps as Equivalent to R4 `AuditEvent.entity.what` |
| AuditEvent.extension | AuditEvent.extension | SourceIsBroaderThanTarget | R5 `AuditEvent.extension` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| AuditEvent.id | AuditEvent.id | Equivalent | R5 `AuditEvent.id` maps as Equivalent to R4 `AuditEvent.id` |
| AuditEvent.implicitRules | AuditEvent.implicitRules | Equivalent | R5 `AuditEvent.implicitRules` maps as Equivalent to R4 `AuditEvent.implicitRules` |
| AuditEvent.language | AuditEvent.language | SourceIsNarrowerThanTarget | R5 `AuditEvent.language` maps as SourceIsNarrowerThanTarget to R4 `AuditEvent.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| AuditEvent.meta | AuditEvent.meta | Equivalent | R5 `AuditEvent.meta` maps as Equivalent to R4 `AuditEvent.meta` |
| AuditEvent.modifierExtension | AuditEvent.modifierExtension | SourceIsBroaderThanTarget | R5 `AuditEvent.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| AuditEvent.occurred[x] | AuditEvent.period | SourceIsBroaderThanTarget | R5 `AuditEvent.occurred[x]` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.period` - period has change due to type change: R5 occurred[x] dateTime has no equivalent or mapped type in R4 period |
| AuditEvent.outcome | AuditEvent.outcome | RelatedTo | R5 `AuditEvent.outcome` maps as RelatedTo to R4 `AuditEvent.outcome` - outcome added a required binding to http://hl7.org/fhir/ValueSet/audit-event-outcome|4.0.1; outcome has change due to type change: R5 outcome BackboneElement has no equivalent or mapped type in R4 outcome |
| AuditEvent.outcome.code | AuditEvent.outcome | RelatedTo | R5 `AuditEvent.outcome.code` maps as RelatedTo to R4 `AuditEvent.outcome` - outcome made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/audit-event-outcome|4.0.1; outcome has change due to type change: R5 code Coding has no equivalent or mapped type in R4 outcome |
| AuditEvent.outcome.code | AuditEvent.outcomeDesc | RelatedTo | R5 `AuditEvent.outcome.code` maps as RelatedTo to R4 `AuditEvent.outcomeDesc` - outcomeDesc removed a binding requirement - Preferred http://hl7.org/fhir/ValueSet/audit-event-outcome; outcomeDesc has change due to type change: R5 code Coding has no equivalent or mapped type in R4 outcomeDesc |
| AuditEvent.outcome.detail | - | DoesNotExistInTarget | R5 `AuditEvent.outcome.detail` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.outcome.extension | - | DoesNotExistInTarget | R5 `AuditEvent.outcome.extension` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.outcome.id | - | DoesNotExistInTarget | R5 `AuditEvent.outcome.id` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.outcome.modifierExtension | - | DoesNotExistInTarget | R5 `AuditEvent.outcome.modifierExtension` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.patient | - | DoesNotExistInTarget | R5 `AuditEvent.patient` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.recorded | AuditEvent.recorded | Equivalent | R5 `AuditEvent.recorded` maps as Equivalent to R4 `AuditEvent.recorded` |
| AuditEvent.severity | - | DoesNotExistInTarget | R5 `AuditEvent.severity` does not appear in the target and has no mapping for `AuditEvent`. |
| AuditEvent.source | AuditEvent.source | Equivalent | R5 `AuditEvent.source` maps as Equivalent to R4 `AuditEvent.source` |
| AuditEvent.source.extension | AuditEvent.source.extension | SourceIsBroaderThanTarget | R5 `AuditEvent.source.extension` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.source.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| AuditEvent.source.id | AuditEvent.source.id | Equivalent | R5 `AuditEvent.source.id` maps as Equivalent to R4 `AuditEvent.source.id` |
| AuditEvent.source.modifierExtension | AuditEvent.source.modifierExtension | SourceIsBroaderThanTarget | R5 `AuditEvent.source.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.source.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| AuditEvent.source.observer | AuditEvent.source.observer | SourceIsBroaderThanTarget | R5 `AuditEvent.source.observer` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.source.observer` - observer has change due to type change: R5 `observer` `Reference` maps as SourceIsBroaderThanTarget for R4 `observer` |
| AuditEvent.source.site | AuditEvent.source.site | SourceIsBroaderThanTarget | R5 `AuditEvent.source.site` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.source.site` - site has change due to type change: R5 site Reference has no equivalent or mapped type in R4 site |
| AuditEvent.source.type | AuditEvent.source.type | SourceIsBroaderThanTarget | R5 `AuditEvent.source.type` maps as SourceIsBroaderThanTarget to R4 `AuditEvent.source.type` - type changed the binding strength from Preferred to Extensible; type has change due to type change: R5 type CodeableConcept has no equivalent or mapped type in R4 type |
| AuditEvent.text | AuditEvent.text | Equivalent | R5 `AuditEvent.text` maps as Equivalent to R4 `AuditEvent.text` |

