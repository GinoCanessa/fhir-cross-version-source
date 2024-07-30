Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ActivityDefinition |  | This resource allows for the definition of some activity to be performed, independent of a particular patient, practitioner, or other performance context. | 71 | 57 |
| Target | ActivityDefinition |  | This resource allows for the definition of some activity to be performed, independent of a particular patient, practitioner, or other performance context. | 65 | 51 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 6 |
Equivalent | 4 |
RelatedTo | 61 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ActivityDefinition | ActivityDefinition | Equivalent | R5 `ActivityDefinition` maps as Equivalent to R4 `ActivityDefinition` |
| ActivityDefinition.approvalDate | ActivityDefinition.approvalDate | Equivalent | R5 `ActivityDefinition.approvalDate` maps as Equivalent to R4 `ActivityDefinition.approvalDate` |
| ActivityDefinition.asNeeded[x] | - | DoesNotExistInTarget | R5 `ActivityDefinition.asNeeded[x]` does not appear in the target and has no mapping for `ActivityDefinition`. |
| ActivityDefinition.author | ActivityDefinition.author | Equivalent | R5 `ActivityDefinition.author` maps as Equivalent to R4 `ActivityDefinition.author` |
| ActivityDefinition.bodySite | ActivityDefinition.bodySite | Equivalent | R5 `ActivityDefinition.bodySite` maps as Equivalent to R4 `ActivityDefinition.bodySite` |
| ActivityDefinition.code | ActivityDefinition.code | Equivalent | R5 `ActivityDefinition.code` maps as Equivalent to R4 `ActivityDefinition.code` |
| ActivityDefinition.contact | ActivityDefinition.contact | Equivalent | R5 `ActivityDefinition.contact` maps as Equivalent to R4 `ActivityDefinition.contact` |
| ActivityDefinition.contained | ActivityDefinition.contained | Equivalent | R5 `ActivityDefinition.contained` maps as Equivalent to R4 `ActivityDefinition.contained` |
| ActivityDefinition.copyright | ActivityDefinition.copyright | Equivalent | R5 `ActivityDefinition.copyright` maps as Equivalent to R4 `ActivityDefinition.copyright` |
| ActivityDefinition.copyrightLabel | - | DoesNotExistInTarget | R5 `ActivityDefinition.copyrightLabel` does not appear in the target and has no mapping for `ActivityDefinition`. |
| ActivityDefinition.date | ActivityDefinition.date | Equivalent | R5 `ActivityDefinition.date` maps as Equivalent to R4 `ActivityDefinition.date` |
| ActivityDefinition.description | ActivityDefinition.description | Equivalent | R5 `ActivityDefinition.description` maps as Equivalent to R4 `ActivityDefinition.description` |
| ActivityDefinition.doNotPerform | ActivityDefinition.doNotPerform | Equivalent | R5 `ActivityDefinition.doNotPerform` maps as Equivalent to R4 `ActivityDefinition.doNotPerform` |
| ActivityDefinition.dosage | ActivityDefinition.dosage | RelatedTo | R5 `ActivityDefinition.dosage` maps as RelatedTo to R4 `ActivityDefinition.dosage` - dosage has change due to type change: R5 `dosage` `Dosage` maps as RelatedTo for R4 `dosage` |
| ActivityDefinition.dynamicValue | ActivityDefinition.dynamicValue | Equivalent | R5 `ActivityDefinition.dynamicValue` maps as Equivalent to R4 `ActivityDefinition.dynamicValue` |
| ActivityDefinition.dynamicValue.expression | ActivityDefinition.dynamicValue.expression | RelatedTo | R5 `ActivityDefinition.dynamicValue.expression` maps as RelatedTo to R4 `ActivityDefinition.dynamicValue.expression` - expression has change due to type change: R5 `expression` `Expression` maps as RelatedTo for R4 `expression` |
| ActivityDefinition.dynamicValue.extension | ActivityDefinition.dynamicValue.extension | SourceIsBroaderThanTarget | R5 `ActivityDefinition.dynamicValue.extension` maps as SourceIsBroaderThanTarget to R4 `ActivityDefinition.dynamicValue.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ActivityDefinition.dynamicValue.id | ActivityDefinition.dynamicValue.id | Equivalent | R5 `ActivityDefinition.dynamicValue.id` maps as Equivalent to R4 `ActivityDefinition.dynamicValue.id` |
| ActivityDefinition.dynamicValue.modifierExtension | ActivityDefinition.dynamicValue.modifierExtension | SourceIsBroaderThanTarget | R5 `ActivityDefinition.dynamicValue.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ActivityDefinition.dynamicValue.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ActivityDefinition.dynamicValue.path | ActivityDefinition.dynamicValue.path | Equivalent | R5 `ActivityDefinition.dynamicValue.path` maps as Equivalent to R4 `ActivityDefinition.dynamicValue.path` |
| ActivityDefinition.editor | ActivityDefinition.editor | Equivalent | R5 `ActivityDefinition.editor` maps as Equivalent to R4 `ActivityDefinition.editor` |
| ActivityDefinition.effectivePeriod | ActivityDefinition.effectivePeriod | Equivalent | R5 `ActivityDefinition.effectivePeriod` maps as Equivalent to R4 `ActivityDefinition.effectivePeriod` |
| ActivityDefinition.endorser | ActivityDefinition.endorser | Equivalent | R5 `ActivityDefinition.endorser` maps as Equivalent to R4 `ActivityDefinition.endorser` |
| ActivityDefinition.experimental | ActivityDefinition.experimental | Equivalent | R5 `ActivityDefinition.experimental` maps as Equivalent to R4 `ActivityDefinition.experimental` |
| ActivityDefinition.extension | ActivityDefinition.extension | SourceIsBroaderThanTarget | R5 `ActivityDefinition.extension` maps as SourceIsBroaderThanTarget to R4 `ActivityDefinition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ActivityDefinition.id | ActivityDefinition.id | Equivalent | R5 `ActivityDefinition.id` maps as Equivalent to R4 `ActivityDefinition.id` |
| ActivityDefinition.identifier | ActivityDefinition.identifier | Equivalent | R5 `ActivityDefinition.identifier` maps as Equivalent to R4 `ActivityDefinition.identifier` |
| ActivityDefinition.implicitRules | ActivityDefinition.implicitRules | Equivalent | R5 `ActivityDefinition.implicitRules` maps as Equivalent to R4 `ActivityDefinition.implicitRules` |
| ActivityDefinition.intent | ActivityDefinition.intent | Equivalent | R5 `ActivityDefinition.intent` maps as Equivalent to R4 `ActivityDefinition.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-intent|5.0.0 and http://hl7.org/fhir/ValueSet/request-intent|4.0.1 (Equivalent) |
| ActivityDefinition.jurisdiction | ActivityDefinition.jurisdiction | Equivalent | R5 `ActivityDefinition.jurisdiction` maps as Equivalent to R4 `ActivityDefinition.jurisdiction` |
| ActivityDefinition.kind | ActivityDefinition.kind | Equivalent | R5 `ActivityDefinition.kind` maps as Equivalent to R4 `ActivityDefinition.kind` - kind has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-resource-types|5.0.0 and http://hl7.org/fhir/ValueSet/request-resource-types|4.0.1 (Equivalent) |
| ActivityDefinition.language | ActivityDefinition.language | RelatedTo | R5 `ActivityDefinition.language` maps as RelatedTo to R4 `ActivityDefinition.language` - language changed the binding strength from Required to Preferred |
| ActivityDefinition.lastReviewDate | ActivityDefinition.lastReviewDate | Equivalent | R5 `ActivityDefinition.lastReviewDate` maps as Equivalent to R4 `ActivityDefinition.lastReviewDate` |
| ActivityDefinition.library | ActivityDefinition.library | Equivalent | R5 `ActivityDefinition.library` maps as Equivalent to R4 `ActivityDefinition.library` |
| ActivityDefinition.location | ActivityDefinition.location | SourceIsBroaderThanTarget | R5 `ActivityDefinition.location` maps as SourceIsBroaderThanTarget to R4 `ActivityDefinition.location` - location has change due to type change: R5 location CodeableReference has no equivalent or mapped type in R4 location |
| ActivityDefinition.meta | ActivityDefinition.meta | Equivalent | R5 `ActivityDefinition.meta` maps as Equivalent to R4 `ActivityDefinition.meta` |
| ActivityDefinition.modifierExtension | ActivityDefinition.modifierExtension | SourceIsBroaderThanTarget | R5 `ActivityDefinition.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ActivityDefinition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ActivityDefinition.name | ActivityDefinition.name | Equivalent | R5 `ActivityDefinition.name` maps as Equivalent to R4 `ActivityDefinition.name` |
| ActivityDefinition.observationRequirement | ActivityDefinition.observationRequirement | SourceIsBroaderThanTarget | R5 `ActivityDefinition.observationRequirement` maps as SourceIsBroaderThanTarget to R4 `ActivityDefinition.observationRequirement` - observationRequirement has change due to type change: R5 observationRequirement canonical has no equivalent or mapped type in R4 observationRequirement |
| ActivityDefinition.observationResultRequirement | ActivityDefinition.observationResultRequirement | SourceIsBroaderThanTarget | R5 `ActivityDefinition.observationResultRequirement` maps as SourceIsBroaderThanTarget to R4 `ActivityDefinition.observationResultRequirement` - observationResultRequirement has change due to type change: R5 observationResultRequirement canonical has no equivalent or mapped type in R4 observationResultRequirement |
| ActivityDefinition.participant | ActivityDefinition.participant | Equivalent | R5 `ActivityDefinition.participant` maps as Equivalent to R4 `ActivityDefinition.participant` |
| ActivityDefinition.participant.extension | ActivityDefinition.participant.extension | SourceIsBroaderThanTarget | R5 `ActivityDefinition.participant.extension` maps as SourceIsBroaderThanTarget to R4 `ActivityDefinition.participant.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ActivityDefinition.participant.function | - | DoesNotExistInTarget | R5 `ActivityDefinition.participant.function` does not appear in the target and has no mapping for `ActivityDefinition`. |
| ActivityDefinition.participant.id | ActivityDefinition.participant.id | Equivalent | R5 `ActivityDefinition.participant.id` maps as Equivalent to R4 `ActivityDefinition.participant.id` |
| ActivityDefinition.participant.modifierExtension | ActivityDefinition.participant.modifierExtension | SourceIsBroaderThanTarget | R5 `ActivityDefinition.participant.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ActivityDefinition.participant.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ActivityDefinition.participant.role | ActivityDefinition.participant.role | Equivalent | R5 `ActivityDefinition.participant.role` maps as Equivalent to R4 `ActivityDefinition.participant.role` |
| ActivityDefinition.participant.type | ActivityDefinition.participant.type | RelatedTo | R5 `ActivityDefinition.participant.type` maps as RelatedTo to R4 `ActivityDefinition.participant.type` - type made the element mandatory; type increased the minimum cardinality from 0 to 1; type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/action-participant-type|5.0.0 and http://hl7.org/fhir/ValueSet/action-participant-type|4.0.1 (Equivalent) |
| ActivityDefinition.participant.typeCanonical | - | DoesNotExistInTarget | R5 `ActivityDefinition.participant.typeCanonical` does not appear in the target and has no mapping for `ActivityDefinition`. |
| ActivityDefinition.participant.typeReference | - | DoesNotExistInTarget | R5 `ActivityDefinition.participant.typeReference` does not appear in the target and has no mapping for `ActivityDefinition`. |
| ActivityDefinition.priority | ActivityDefinition.priority | Equivalent | R5 `ActivityDefinition.priority` maps as Equivalent to R4 `ActivityDefinition.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|5.0.0 and http://hl7.org/fhir/ValueSet/request-priority|4.0.1 (Equivalent) |
| ActivityDefinition.product[x] | ActivityDefinition.product[x] | SourceIsBroaderThanTarget | R5 `ActivityDefinition.product[x]` maps as SourceIsBroaderThanTarget to R4 `ActivityDefinition.product[x]` - product[x] has change due to type change: R5 `product[x]` `Reference` maps as SourceIsBroaderThanTarget for R4 `product[x]` |
| ActivityDefinition.profile | ActivityDefinition.profile | Equivalent | R5 `ActivityDefinition.profile` maps as Equivalent to R4 `ActivityDefinition.profile` |
| ActivityDefinition.publisher | ActivityDefinition.publisher | Equivalent | R5 `ActivityDefinition.publisher` maps as Equivalent to R4 `ActivityDefinition.publisher` |
| ActivityDefinition.purpose | ActivityDefinition.purpose | Equivalent | R5 `ActivityDefinition.purpose` maps as Equivalent to R4 `ActivityDefinition.purpose` |
| ActivityDefinition.quantity | ActivityDefinition.quantity | Equivalent | R5 `ActivityDefinition.quantity` maps as Equivalent to R4 `ActivityDefinition.quantity` |
| ActivityDefinition.relatedArtifact | ActivityDefinition.relatedArtifact | Equivalent | R5 `ActivityDefinition.relatedArtifact` maps as Equivalent to R4 `ActivityDefinition.relatedArtifact` |
| ActivityDefinition.reviewer | ActivityDefinition.reviewer | Equivalent | R5 `ActivityDefinition.reviewer` maps as Equivalent to R4 `ActivityDefinition.reviewer` |
| ActivityDefinition.specimenRequirement | ActivityDefinition.specimenRequirement | SourceIsBroaderThanTarget | R5 `ActivityDefinition.specimenRequirement` maps as SourceIsBroaderThanTarget to R4 `ActivityDefinition.specimenRequirement` - specimenRequirement has change due to type change: R5 specimenRequirement canonical has no equivalent or mapped type in R4 specimenRequirement |
| ActivityDefinition.status | ActivityDefinition.status | Equivalent | R5 `ActivityDefinition.status` maps as Equivalent to R4 `ActivityDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| ActivityDefinition.subject[x] | ActivityDefinition.subject[x] | SourceIsBroaderThanTarget | R5 `ActivityDefinition.subject[x]` maps as SourceIsBroaderThanTarget to R4 `ActivityDefinition.subject[x]` - subject[x] has change due to type change: R5 `subject[x]` `Reference` maps as SourceIsBroaderThanTarget for R4 `subject[x]`; subject[x] has change due to type change: R5 subject[x] canonical has no equivalent or mapped type in R4 subject[x] |
| ActivityDefinition.subtitle | ActivityDefinition.subtitle | Equivalent | R5 `ActivityDefinition.subtitle` maps as Equivalent to R4 `ActivityDefinition.subtitle` |
| ActivityDefinition.text | ActivityDefinition.text | Equivalent | R5 `ActivityDefinition.text` maps as Equivalent to R4 `ActivityDefinition.text` |
| ActivityDefinition.timing[x] | ActivityDefinition.timing[x] | Equivalent | R5 `ActivityDefinition.timing[x]` maps as Equivalent to R4 `ActivityDefinition.timing[x]` |
| ActivityDefinition.title | ActivityDefinition.title | Equivalent | R5 `ActivityDefinition.title` maps as Equivalent to R4 `ActivityDefinition.title` |
| ActivityDefinition.topic | ActivityDefinition.topic | Equivalent | R5 `ActivityDefinition.topic` maps as Equivalent to R4 `ActivityDefinition.topic` |
| ActivityDefinition.transform | ActivityDefinition.transform | Equivalent | R5 `ActivityDefinition.transform` maps as Equivalent to R4 `ActivityDefinition.transform` |
| ActivityDefinition.url | ActivityDefinition.url | Equivalent | R5 `ActivityDefinition.url` maps as Equivalent to R4 `ActivityDefinition.url` |
| ActivityDefinition.usage | ActivityDefinition.usage | SourceIsBroaderThanTarget | R5 `ActivityDefinition.usage` maps as SourceIsBroaderThanTarget to R4 `ActivityDefinition.usage` - usage has change due to type change: R5 usage markdown has no equivalent or mapped type in R4 usage |
| ActivityDefinition.useContext | ActivityDefinition.useContext | Equivalent | R5 `ActivityDefinition.useContext` maps as Equivalent to R4 `ActivityDefinition.useContext` |
| ActivityDefinition.version | ActivityDefinition.version | Equivalent | R5 `ActivityDefinition.version` maps as Equivalent to R4 `ActivityDefinition.version` |
| ActivityDefinition.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `ActivityDefinition.versionAlgorithm[x]` does not appear in the target and has no mapping for `ActivityDefinition`. |

