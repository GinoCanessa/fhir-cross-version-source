Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Provenance |  | Provenance of a resource is a record that describes entities and processes involved in producing and delivering or otherwise influencing that resource. Provenance provides a critical foundation for assessing authenticity, enabling trust, and allowing reproducibility. Provenance assertions are a form of contextual metadata and can themselves become important records with their own provenance. Provenance statement indicates clinical significance in terms of confidence in authenticity, reliability, and trustworthiness, integrity, and stage in lifecycle (e.g. Document Completion - has the artifact been legally authenticated), all of which may impact security, privacy, and trust policies. | 35 | 21 |
| Target | Provenance |  | Provenance of a resource is a record that describes entities and processes involved in producing and delivering or otherwise influencing that resource. Provenance provides a critical foundation for assessing authenticity, enabling trust, and allowing reproducibility. Provenance assertions are a form of contextual metadata and can themselves become important records with their own provenance. Provenance statement indicates clinical significance in terms of confidence in authenticity, reliability, and trustworthiness, integrity, and stage in lifecycle (e.g. Document Completion - has the artifact been legally authenticated), all of which may impact security, privacy, and trust policies. | 32 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 27 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Provenance | Provenance | Equivalent | R5 `Provenance` maps as Equivalent to R4B `Provenance` |
| Provenance.activity | Provenance.activity | RelatedTo | R5 `Provenance.activity` maps as RelatedTo to R4B `Provenance.activity` - activity changed the binding strength from Example to Extensible |
| Provenance.agent | Provenance.agent | Equivalent | R5 `Provenance.agent` maps as Equivalent to R4B `Provenance.agent` |
| Provenance.agent.extension | Provenance.agent.extension | SourceIsBroaderThanTarget | R5 `Provenance.agent.extension` maps as SourceIsBroaderThanTarget to R4B `Provenance.agent.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Provenance.agent.id | Provenance.agent.id | Equivalent | R5 `Provenance.agent.id` maps as Equivalent to R4B `Provenance.agent.id` |
| Provenance.agent.modifierExtension | Provenance.agent.modifierExtension | SourceIsBroaderThanTarget | R5 `Provenance.agent.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Provenance.agent.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Provenance.agent.onBehalfOf | Provenance.agent.onBehalfOf | RelatedTo | R5 `Provenance.agent.onBehalfOf` maps as RelatedTo to R4B `Provenance.agent.onBehalfOf` - onBehalfOf has change due to type change: R5 `onBehalfOf` `Reference` maps as RelatedTo for R4B `onBehalfOf` |
| Provenance.agent.role | Provenance.agent.role | Equivalent | R5 `Provenance.agent.role` maps as Equivalent to R4B `Provenance.agent.role` |
| Provenance.agent.type | Provenance.agent.type | RelatedTo | R5 `Provenance.agent.type` maps as RelatedTo to R4B `Provenance.agent.type` - type changed the binding strength from Example to Extensible |
| Provenance.agent.who | Provenance.agent.who | SourceIsBroaderThanTarget | R5 `Provenance.agent.who` maps as SourceIsBroaderThanTarget to R4B `Provenance.agent.who` - who has change due to type change: R5 `who` `Reference` maps as SourceIsBroaderThanTarget for R4B `who` |
| Provenance.authorization | - | DoesNotExistInTarget | R5 `Provenance.authorization` does not appear in the target and has no mapping for `Provenance`. |
| Provenance.basedOn | - | DoesNotExistInTarget | R5 `Provenance.basedOn` does not appear in the target and has no mapping for `Provenance`. |
| Provenance.contained | Provenance.contained | Equivalent | R5 `Provenance.contained` maps as Equivalent to R4B `Provenance.contained` |
| Provenance.encounter | - | DoesNotExistInTarget | R5 `Provenance.encounter` does not appear in the target and has no mapping for `Provenance`. |
| Provenance.entity | Provenance.entity | Equivalent | R5 `Provenance.entity` maps as Equivalent to R4B `Provenance.entity` |
| Provenance.entity.agent | Provenance.entity.agent | Equivalent | R5 `Provenance.entity.agent` maps as Equivalent to R4B `Provenance.entity.agent` |
| Provenance.entity.extension | Provenance.entity.extension | SourceIsBroaderThanTarget | R5 `Provenance.entity.extension` maps as SourceIsBroaderThanTarget to R4B `Provenance.entity.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Provenance.entity.id | Provenance.entity.id | Equivalent | R5 `Provenance.entity.id` maps as Equivalent to R4B `Provenance.entity.id` |
| Provenance.entity.modifierExtension | Provenance.entity.modifierExtension | SourceIsBroaderThanTarget | R5 `Provenance.entity.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Provenance.entity.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Provenance.entity.role | Provenance.entity.role | Equivalent | R5 `Provenance.entity.role` maps as Equivalent to R4B `Provenance.entity.role` - role has compatible required binding for code type: http://hl7.org/fhir/ValueSet/provenance-entity-role|5.0.0 and http://hl7.org/fhir/ValueSet/provenance-entity-role|4.3.0 (Equivalent) |
| Provenance.entity.what | Provenance.entity.what | Equivalent | R5 `Provenance.entity.what` maps as Equivalent to R4B `Provenance.entity.what` |
| Provenance.extension | Provenance.extension | SourceIsBroaderThanTarget | R5 `Provenance.extension` maps as SourceIsBroaderThanTarget to R4B `Provenance.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Provenance.id | Provenance.id | Equivalent | R5 `Provenance.id` maps as Equivalent to R4B `Provenance.id` |
| Provenance.implicitRules | Provenance.implicitRules | Equivalent | R5 `Provenance.implicitRules` maps as Equivalent to R4B `Provenance.implicitRules` |
| Provenance.language | Provenance.language | RelatedTo | R5 `Provenance.language` maps as RelatedTo to R4B `Provenance.language` - language changed the binding strength from Required to Preferred |
| Provenance.location | Provenance.location | Equivalent | R5 `Provenance.location` maps as Equivalent to R4B `Provenance.location` |
| Provenance.meta | Provenance.meta | Equivalent | R5 `Provenance.meta` maps as Equivalent to R4B `Provenance.meta` |
| Provenance.modifierExtension | Provenance.modifierExtension | SourceIsBroaderThanTarget | R5 `Provenance.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Provenance.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Provenance.occurred[x] | Provenance.occurred[x] | Equivalent | R5 `Provenance.occurred[x]` maps as Equivalent to R4B `Provenance.occurred[x]` |
| Provenance.patient | - | DoesNotExistInTarget | R5 `Provenance.patient` does not appear in the target and has no mapping for `Provenance`. |
| Provenance.policy | Provenance.policy | Equivalent | R5 `Provenance.policy` maps as Equivalent to R4B `Provenance.policy` |
| Provenance.recorded | Provenance.recorded | RelatedTo | R5 `Provenance.recorded` maps as RelatedTo to R4B `Provenance.recorded` - recorded made the element mandatory; recorded increased the minimum cardinality from 0 to 1 |
| Provenance.signature | Provenance.signature | RelatedTo | R5 `Provenance.signature` maps as RelatedTo to R4B `Provenance.signature` - signature has change due to type change: R5 `signature` `Signature` maps as RelatedTo for R4B `signature` |
| Provenance.target | Provenance.target | Equivalent | R5 `Provenance.target` maps as Equivalent to R4B `Provenance.target` |
| Provenance.text | Provenance.text | Equivalent | R5 `Provenance.text` maps as Equivalent to R4B `Provenance.text` |

