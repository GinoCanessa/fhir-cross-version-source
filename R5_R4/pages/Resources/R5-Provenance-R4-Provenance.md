Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Provenance |  | Provenance of a resource is a record that describes entities and processes involved in producing and delivering or otherwise influencing that resource. Provenance provides a critical foundation for assessing authenticity, enabling trust, and allowing reproducibility. Provenance assertions are a form of contextual metadata and can themselves become important records with their own provenance. Provenance statement indicates clinical significance in terms of confidence in authenticity, reliability, and trustworthiness, integrity, and stage in lifecycle (e.g. Document Completion - has the artifact been legally authenticated), all of which may impact security, privacy, and trust policies. | 35 | 21 |
| Target | Provenance |  | Provenance of a resource is a record that describes entities and processes involved in producing and delivering or otherwise influencing that resource. Provenance provides a critical foundation for assessing authenticity, enabling trust, and allowing reproducibility. Provenance assertions are a form of contextual metadata and can themselves become important records with their own provenance. Provenance statement indicates clinical significance in terms of confidence in authenticity, reliability, and trustworthiness, integrity, and stage in lifecycle (e.g. Document Completion - has the artifact been legally authenticated), all of which may impact security, privacy, and trust policies. | 32 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 18 |
RelatedTo | 3 |
SourceIsBroaderThanTarget | 10 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Provenance | Provenance | Equivalent | R5 `Provenance` maps as Equivalent to R4 `Provenance` |
| Provenance.activity | Provenance.activity | SourceIsBroaderThanTarget | R5 `Provenance.activity` maps as SourceIsBroaderThanTarget to R4 `Provenance.activity` - activity changed the binding strength from Example to Extensible; activity has change due to type change: R5 `activity` `CodeableConcept` maps as SourceIsBroaderThanTarget for R4 `activity` |
| Provenance.agent | Provenance.agent | Equivalent | R5 `Provenance.agent` maps as Equivalent to R4 `Provenance.agent` |
| Provenance.agent.extension | Provenance.agent.extension | SourceIsBroaderThanTarget | R5 `Provenance.agent.extension` maps as SourceIsBroaderThanTarget to R4 `Provenance.agent.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Provenance.agent.id | Provenance.agent.id | Equivalent | R5 `Provenance.agent.id` maps as Equivalent to R4 `Provenance.agent.id` |
| Provenance.agent.modifierExtension | Provenance.agent.modifierExtension | SourceIsBroaderThanTarget | R5 `Provenance.agent.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Provenance.agent.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Provenance.agent.onBehalfOf | Provenance.agent.onBehalfOf | RelatedTo | R5 `Provenance.agent.onBehalfOf` maps as RelatedTo to R4 `Provenance.agent.onBehalfOf` - onBehalfOf has change due to type change: R5 `onBehalfOf` `Reference` maps as RelatedTo for R4 `onBehalfOf` |
| Provenance.agent.role | Provenance.agent.role | Equivalent | R5 `Provenance.agent.role` maps as Equivalent to R4 `Provenance.agent.role` |
| Provenance.agent.type | Provenance.agent.type | SourceIsBroaderThanTarget | R5 `Provenance.agent.type` maps as SourceIsBroaderThanTarget to R4 `Provenance.agent.type` - type changed the binding strength from Example to Extensible; type has change due to type change: R5 `type` `CodeableConcept` maps as SourceIsBroaderThanTarget for R4 `type` |
| Provenance.agent.who | Provenance.agent.who | SourceIsBroaderThanTarget | R5 `Provenance.agent.who` maps as SourceIsBroaderThanTarget to R4 `Provenance.agent.who` - who has change due to type change: R5 `who` `Reference` maps as SourceIsBroaderThanTarget for R4 `who` |
| Provenance.authorization | Provenance.reason | SourceIsBroaderThanTarget | R5 `Provenance.authorization` maps as SourceIsBroaderThanTarget to R4 `Provenance.reason` - reason changed the binding strength from Example to Extensible; reason has change due to type change: R5 authorization CodeableReference has no equivalent or mapped type in R4 reason |
| Provenance.basedOn | - | DoesNotExistInTarget | R5 `Provenance.basedOn` does not appear in the target and has no mapping for `Provenance`. |
| Provenance.contained | Provenance.contained | Equivalent | R5 `Provenance.contained` maps as Equivalent to R4 `Provenance.contained` |
| Provenance.encounter | - | DoesNotExistInTarget | R5 `Provenance.encounter` does not appear in the target and has no mapping for `Provenance`. |
| Provenance.entity | Provenance.entity | Equivalent | R5 `Provenance.entity` maps as Equivalent to R4 `Provenance.entity` |
| Provenance.entity.agent | Provenance.entity.agent | Equivalent | R5 `Provenance.entity.agent` maps as Equivalent to R4 `Provenance.entity.agent` |
| Provenance.entity.extension | Provenance.entity.extension | SourceIsBroaderThanTarget | R5 `Provenance.entity.extension` maps as SourceIsBroaderThanTarget to R4 `Provenance.entity.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Provenance.entity.id | Provenance.entity.id | Equivalent | R5 `Provenance.entity.id` maps as Equivalent to R4 `Provenance.entity.id` |
| Provenance.entity.modifierExtension | Provenance.entity.modifierExtension | SourceIsBroaderThanTarget | R5 `Provenance.entity.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Provenance.entity.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Provenance.entity.role | Provenance.entity.role | Equivalent | R5 `Provenance.entity.role` maps as Equivalent to R4 `Provenance.entity.role` - role has compatible required binding for code type: http://hl7.org/fhir/ValueSet/provenance-entity-role|5.0.0 and http://hl7.org/fhir/ValueSet/provenance-entity-role|4.0.1 (Equivalent) |
| Provenance.entity.what | Provenance.entity.what | Equivalent | R5 `Provenance.entity.what` maps as Equivalent to R4 `Provenance.entity.what` |
| Provenance.extension | Provenance.extension | SourceIsBroaderThanTarget | R5 `Provenance.extension` maps as SourceIsBroaderThanTarget to R4 `Provenance.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Provenance.id | Provenance.id | Equivalent | R5 `Provenance.id` maps as Equivalent to R4 `Provenance.id` |
| Provenance.implicitRules | Provenance.implicitRules | Equivalent | R5 `Provenance.implicitRules` maps as Equivalent to R4 `Provenance.implicitRules` |
| Provenance.language | Provenance.language | SourceIsNarrowerThanTarget | R5 `Provenance.language` maps as SourceIsNarrowerThanTarget to R4 `Provenance.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Provenance.location | Provenance.location | Equivalent | R5 `Provenance.location` maps as Equivalent to R4 `Provenance.location` |
| Provenance.meta | Provenance.meta | Equivalent | R5 `Provenance.meta` maps as Equivalent to R4 `Provenance.meta` |
| Provenance.modifierExtension | Provenance.modifierExtension | SourceIsBroaderThanTarget | R5 `Provenance.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Provenance.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Provenance.occurred[x] | Provenance.occurred[x] | Equivalent | R5 `Provenance.occurred[x]` maps as Equivalent to R4 `Provenance.occurred[x]` |
| Provenance.patient | - | DoesNotExistInTarget | R5 `Provenance.patient` does not appear in the target and has no mapping for `Provenance`. |
| Provenance.policy | Provenance.policy | Equivalent | R5 `Provenance.policy` maps as Equivalent to R4 `Provenance.policy` |
| Provenance.recorded | Provenance.recorded | RelatedTo | R5 `Provenance.recorded` maps as RelatedTo to R4 `Provenance.recorded` - recorded made the element mandatory; recorded increased the minimum cardinality from 0 to 1 |
| Provenance.signature | Provenance.signature | RelatedTo | R5 `Provenance.signature` maps as RelatedTo to R4 `Provenance.signature` - signature has change due to type change: R5 `signature` `Signature` maps as RelatedTo for R4 `signature` |
| Provenance.target | Provenance.target | Equivalent | R5 `Provenance.target` maps as Equivalent to R4 `Provenance.target` |
| Provenance.text | Provenance.text | Equivalent | R5 `Provenance.text` maps as Equivalent to R4 `Provenance.text` |

