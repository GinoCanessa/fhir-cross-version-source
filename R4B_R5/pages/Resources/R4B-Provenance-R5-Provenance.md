Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Provenance |  | Provenance of a resource is a record that describes entities and processes involved in producing and delivering or otherwise influencing that resource. Provenance provides a critical foundation for assessing authenticity, enabling trust, and allowing reproducibility. Provenance assertions are a form of contextual metadata and can themselves become important records with their own provenance. Provenance statement indicates clinical significance in terms of confidence in authenticity, reliability, and trustworthiness, integrity, and stage in lifecycle (e.g. Document Completion - has the artifact been legally authenticated), all of which may impact security, privacy, and trust policies. | 32 | 18 |
| Target | Provenance |  | Provenance of a resource is a record that describes entities and processes involved in producing and delivering or otherwise influencing that resource. Provenance provides a critical foundation for assessing authenticity, enabling trust, and allowing reproducibility. Provenance assertions are a form of contextual metadata and can themselves become important records with their own provenance. Provenance statement indicates clinical significance in terms of confidence in authenticity, reliability, and trustworthiness, integrity, and stage in lifecycle (e.g. Document Completion - has the artifact been legally authenticated), all of which may impact security, privacy, and trust policies. | 35 | 21 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 27 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Provenance | Provenance | Equivalent | R4B `Provenance` maps as Equivalent to R5 `Provenance` |
| Provenance.activity | Provenance.activity | RelatedTo | R4B `Provenance.activity` maps as RelatedTo to R5 `Provenance.activity` - activity changed the binding strength from Extensible to Example |
| Provenance.agent | Provenance.agent | Equivalent | R4B `Provenance.agent` maps as Equivalent to R5 `Provenance.agent` |
| Provenance.agent.extension | Provenance.agent.extension | RelatedTo | R4B `Provenance.agent.extension` maps as RelatedTo to R5 `Provenance.agent.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Provenance.agent.id | Provenance.agent.id | Equivalent | R4B `Provenance.agent.id` maps as Equivalent to R5 `Provenance.agent.id` |
| Provenance.agent.modifierExtension | Provenance.agent.modifierExtension | RelatedTo | R4B `Provenance.agent.modifierExtension` maps as RelatedTo to R5 `Provenance.agent.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Provenance.agent.onBehalfOf | Provenance.agent.onBehalfOf | RelatedTo | R4B `Provenance.agent.onBehalfOf` maps as RelatedTo to R5 `Provenance.agent.onBehalfOf` - onBehalfOf has change due to type change: R4B `onBehalfOf` `Reference` maps as RelatedTo for R5 `onBehalfOf` |
| Provenance.agent.role | Provenance.agent.role | Equivalent | R4B `Provenance.agent.role` maps as Equivalent to R5 `Provenance.agent.role` |
| Provenance.agent.type | Provenance.agent.type | RelatedTo | R4B `Provenance.agent.type` maps as RelatedTo to R5 `Provenance.agent.type` - type changed the binding strength from Extensible to Example |
| Provenance.agent.who | Provenance.agent.who | SourceIsNarrowerThanTarget | R4B `Provenance.agent.who` maps as SourceIsNarrowerThanTarget to R5 `Provenance.agent.who` - who has change due to type change: R4B `who` `Reference` maps as SourceIsNarrowerThanTarget for R5 `who` |
| Provenance.contained | Provenance.contained | Equivalent | R4B `Provenance.contained` maps as Equivalent to R5 `Provenance.contained` |
| Provenance.entity | Provenance.entity | Equivalent | R4B `Provenance.entity` maps as Equivalent to R5 `Provenance.entity` |
| Provenance.entity.agent | Provenance.entity.agent | Equivalent | R4B `Provenance.entity.agent` maps as Equivalent to R5 `Provenance.entity.agent` |
| Provenance.entity.extension | Provenance.entity.extension | RelatedTo | R4B `Provenance.entity.extension` maps as RelatedTo to R5 `Provenance.entity.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Provenance.entity.id | Provenance.entity.id | Equivalent | R4B `Provenance.entity.id` maps as Equivalent to R5 `Provenance.entity.id` |
| Provenance.entity.modifierExtension | Provenance.entity.modifierExtension | RelatedTo | R4B `Provenance.entity.modifierExtension` maps as RelatedTo to R5 `Provenance.entity.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Provenance.entity.role | Provenance.entity.role | Equivalent | R4B `Provenance.entity.role` maps as Equivalent to R5 `Provenance.entity.role` - role has compatible required binding for code type: http://hl7.org/fhir/ValueSet/provenance-entity-role|4.3.0 and http://hl7.org/fhir/ValueSet/provenance-entity-role|5.0.0 (Equivalent) |
| Provenance.entity.what | Provenance.entity.what | Equivalent | R4B `Provenance.entity.what` maps as Equivalent to R5 `Provenance.entity.what` |
| Provenance.extension | Provenance.extension | RelatedTo | R4B `Provenance.extension` maps as RelatedTo to R5 `Provenance.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Provenance.id | Provenance.id | Equivalent | R4B `Provenance.id` maps as Equivalent to R5 `Provenance.id` |
| Provenance.implicitRules | Provenance.implicitRules | Equivalent | R4B `Provenance.implicitRules` maps as Equivalent to R5 `Provenance.implicitRules` |
| Provenance.language | Provenance.language | RelatedTo | R4B `Provenance.language` maps as RelatedTo to R5 `Provenance.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Provenance.location | Provenance.location | Equivalent | R4B `Provenance.location` maps as Equivalent to R5 `Provenance.location` |
| Provenance.meta | Provenance.meta | Equivalent | R4B `Provenance.meta` maps as Equivalent to R5 `Provenance.meta` |
| Provenance.modifierExtension | Provenance.modifierExtension | RelatedTo | R4B `Provenance.modifierExtension` maps as RelatedTo to R5 `Provenance.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Provenance.occurred[x] | Provenance.occurred[x] | Equivalent | R4B `Provenance.occurred[x]` maps as Equivalent to R5 `Provenance.occurred[x]` |
| Provenance.policy | Provenance.policy | Equivalent | R4B `Provenance.policy` maps as Equivalent to R5 `Provenance.policy` |
| Provenance.reason | - | DoesNotExistInTarget | R4B `Provenance.reason` does not appear in the target and has no mapping for `Provenance`. |
| Provenance.recorded | Provenance.recorded | Equivalent | R4B `Provenance.recorded` maps as Equivalent to R5 `Provenance.recorded` |
| Provenance.signature | Provenance.signature | Equivalent | R4B `Provenance.signature` maps as Equivalent to R5 `Provenance.signature` |
| Provenance.target | Provenance.target | Equivalent | R4B `Provenance.target` maps as Equivalent to R5 `Provenance.target` |
| Provenance.text | Provenance.text | Equivalent | R4B `Provenance.text` maps as Equivalent to R5 `Provenance.text` |

