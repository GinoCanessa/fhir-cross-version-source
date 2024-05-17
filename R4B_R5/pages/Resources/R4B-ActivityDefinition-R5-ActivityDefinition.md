Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ActivityDefinition |  | This resource allows for the definition of some activity to be performed, independent of a particular patient, practitioner, or other performance context. | 65 | 51 |
| Target | ActivityDefinition |  | This resource allows for the definition of some activity to be performed, independent of a particular patient, practitioner, or other performance context. | 71 | 57 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 61 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ActivityDefinition | ActivityDefinition | Equivalent | R4B `ActivityDefinition` maps as Equivalent to R5 `ActivityDefinition` |
| ActivityDefinition.approvalDate | ActivityDefinition.approvalDate | Equivalent | R4B `ActivityDefinition.approvalDate` maps as Equivalent to R5 `ActivityDefinition.approvalDate` |
| ActivityDefinition.author | ActivityDefinition.author | Equivalent | R4B `ActivityDefinition.author` maps as Equivalent to R5 `ActivityDefinition.author` |
| ActivityDefinition.bodySite | ActivityDefinition.bodySite | Equivalent | R4B `ActivityDefinition.bodySite` maps as Equivalent to R5 `ActivityDefinition.bodySite` |
| ActivityDefinition.code | ActivityDefinition.code | Equivalent | R4B `ActivityDefinition.code` maps as Equivalent to R5 `ActivityDefinition.code` |
| ActivityDefinition.contact | ActivityDefinition.contact | Equivalent | R4B `ActivityDefinition.contact` maps as Equivalent to R5 `ActivityDefinition.contact` |
| ActivityDefinition.contained | ActivityDefinition.contained | Equivalent | R4B `ActivityDefinition.contained` maps as Equivalent to R5 `ActivityDefinition.contained` |
| ActivityDefinition.copyright | ActivityDefinition.copyright | Equivalent | R4B `ActivityDefinition.copyright` maps as Equivalent to R5 `ActivityDefinition.copyright` |
| ActivityDefinition.date | ActivityDefinition.date | Equivalent | R4B `ActivityDefinition.date` maps as Equivalent to R5 `ActivityDefinition.date` |
| ActivityDefinition.description | ActivityDefinition.description | Equivalent | R4B `ActivityDefinition.description` maps as Equivalent to R5 `ActivityDefinition.description` |
| ActivityDefinition.doNotPerform | ActivityDefinition.doNotPerform | Equivalent | R4B `ActivityDefinition.doNotPerform` maps as Equivalent to R5 `ActivityDefinition.doNotPerform` |
| ActivityDefinition.dosage | ActivityDefinition.dosage | RelatedTo | R4B `ActivityDefinition.dosage` maps as RelatedTo to R5 `ActivityDefinition.dosage` - dosage has change due to type change: R4B `dosage` `Dosage` maps as RelatedTo for R5 `dosage` |
| ActivityDefinition.dynamicValue | ActivityDefinition.dynamicValue | Equivalent | R4B `ActivityDefinition.dynamicValue` maps as Equivalent to R5 `ActivityDefinition.dynamicValue` |
| ActivityDefinition.dynamicValue.expression | ActivityDefinition.dynamicValue.expression | SourceIsBroaderThanTarget | R4B `ActivityDefinition.dynamicValue.expression` maps as SourceIsBroaderThanTarget to R5 `ActivityDefinition.dynamicValue.expression` - expression has change due to type change: R4B `expression` `Expression` maps as SourceIsBroaderThanTarget for R5 `expression` |
| ActivityDefinition.dynamicValue.extension | ActivityDefinition.dynamicValue.extension | RelatedTo | R4B `ActivityDefinition.dynamicValue.extension` maps as RelatedTo to R5 `ActivityDefinition.dynamicValue.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ActivityDefinition.dynamicValue.id | ActivityDefinition.dynamicValue.id | Equivalent | R4B `ActivityDefinition.dynamicValue.id` maps as Equivalent to R5 `ActivityDefinition.dynamicValue.id` |
| ActivityDefinition.dynamicValue.modifierExtension | ActivityDefinition.dynamicValue.modifierExtension | RelatedTo | R4B `ActivityDefinition.dynamicValue.modifierExtension` maps as RelatedTo to R5 `ActivityDefinition.dynamicValue.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ActivityDefinition.dynamicValue.path | ActivityDefinition.dynamicValue.path | Equivalent | R4B `ActivityDefinition.dynamicValue.path` maps as Equivalent to R5 `ActivityDefinition.dynamicValue.path` |
| ActivityDefinition.editor | ActivityDefinition.editor | Equivalent | R4B `ActivityDefinition.editor` maps as Equivalent to R5 `ActivityDefinition.editor` |
| ActivityDefinition.effectivePeriod | ActivityDefinition.effectivePeriod | Equivalent | R4B `ActivityDefinition.effectivePeriod` maps as Equivalent to R5 `ActivityDefinition.effectivePeriod` |
| ActivityDefinition.endorser | ActivityDefinition.endorser | Equivalent | R4B `ActivityDefinition.endorser` maps as Equivalent to R5 `ActivityDefinition.endorser` |
| ActivityDefinition.experimental | ActivityDefinition.experimental | Equivalent | R4B `ActivityDefinition.experimental` maps as Equivalent to R5 `ActivityDefinition.experimental` |
| ActivityDefinition.extension | ActivityDefinition.extension | RelatedTo | R4B `ActivityDefinition.extension` maps as RelatedTo to R5 `ActivityDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ActivityDefinition.id | ActivityDefinition.id | Equivalent | R4B `ActivityDefinition.id` maps as Equivalent to R5 `ActivityDefinition.id` |
| ActivityDefinition.identifier | ActivityDefinition.identifier | Equivalent | R4B `ActivityDefinition.identifier` maps as Equivalent to R5 `ActivityDefinition.identifier` |
| ActivityDefinition.implicitRules | ActivityDefinition.implicitRules | Equivalent | R4B `ActivityDefinition.implicitRules` maps as Equivalent to R5 `ActivityDefinition.implicitRules` |
| ActivityDefinition.intent | ActivityDefinition.intent | Equivalent | R4B `ActivityDefinition.intent` maps as Equivalent to R5 `ActivityDefinition.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-intent|4.3.0 and http://hl7.org/fhir/ValueSet/request-intent|5.0.0 (Equivalent) |
| ActivityDefinition.jurisdiction | ActivityDefinition.jurisdiction | Equivalent | R4B `ActivityDefinition.jurisdiction` maps as Equivalent to R5 `ActivityDefinition.jurisdiction` |
| ActivityDefinition.kind | ActivityDefinition.kind | Equivalent | R4B `ActivityDefinition.kind` maps as Equivalent to R5 `ActivityDefinition.kind` - kind has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-resource-types|4.3.0 and http://hl7.org/fhir/ValueSet/request-resource-types|5.0.0 (Equivalent) |
| ActivityDefinition.language | ActivityDefinition.language | RelatedTo | R4B `ActivityDefinition.language` maps as RelatedTo to R5 `ActivityDefinition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ActivityDefinition.lastReviewDate | ActivityDefinition.lastReviewDate | Equivalent | R4B `ActivityDefinition.lastReviewDate` maps as Equivalent to R5 `ActivityDefinition.lastReviewDate` |
| ActivityDefinition.library | ActivityDefinition.library | Equivalent | R4B `ActivityDefinition.library` maps as Equivalent to R5 `ActivityDefinition.library` |
| ActivityDefinition.location | ActivityDefinition.location | SourceIsBroaderThanTarget | R4B `ActivityDefinition.location` maps as SourceIsBroaderThanTarget to R5 `ActivityDefinition.location` - location has change due to type change: R4B location Reference has no equivalent or mapped type in R5 location |
| ActivityDefinition.meta | ActivityDefinition.meta | Equivalent | R4B `ActivityDefinition.meta` maps as Equivalent to R5 `ActivityDefinition.meta` |
| ActivityDefinition.modifierExtension | ActivityDefinition.modifierExtension | RelatedTo | R4B `ActivityDefinition.modifierExtension` maps as RelatedTo to R5 `ActivityDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ActivityDefinition.name | ActivityDefinition.name | Equivalent | R4B `ActivityDefinition.name` maps as Equivalent to R5 `ActivityDefinition.name` |
| ActivityDefinition.observationRequirement | ActivityDefinition.observationRequirement | SourceIsBroaderThanTarget | R4B `ActivityDefinition.observationRequirement` maps as SourceIsBroaderThanTarget to R5 `ActivityDefinition.observationRequirement` - observationRequirement has change due to type change: R4B observationRequirement Reference has no equivalent or mapped type in R5 observationRequirement |
| ActivityDefinition.observationResultRequirement | ActivityDefinition.observationResultRequirement | SourceIsBroaderThanTarget | R4B `ActivityDefinition.observationResultRequirement` maps as SourceIsBroaderThanTarget to R5 `ActivityDefinition.observationResultRequirement` - observationResultRequirement has change due to type change: R4B observationResultRequirement Reference has no equivalent or mapped type in R5 observationResultRequirement |
| ActivityDefinition.participant | ActivityDefinition.participant | Equivalent | R4B `ActivityDefinition.participant` maps as Equivalent to R5 `ActivityDefinition.participant` |
| ActivityDefinition.participant.extension | ActivityDefinition.participant.extension | RelatedTo | R4B `ActivityDefinition.participant.extension` maps as RelatedTo to R5 `ActivityDefinition.participant.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ActivityDefinition.participant.id | ActivityDefinition.participant.id | Equivalent | R4B `ActivityDefinition.participant.id` maps as Equivalent to R5 `ActivityDefinition.participant.id` |
| ActivityDefinition.participant.modifierExtension | ActivityDefinition.participant.modifierExtension | RelatedTo | R4B `ActivityDefinition.participant.modifierExtension` maps as RelatedTo to R5 `ActivityDefinition.participant.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ActivityDefinition.participant.role | ActivityDefinition.participant.role | Equivalent | R4B `ActivityDefinition.participant.role` maps as Equivalent to R5 `ActivityDefinition.participant.role` |
| ActivityDefinition.participant.type | ActivityDefinition.participant.type | Equivalent | R4B `ActivityDefinition.participant.type` maps as Equivalent to R5 `ActivityDefinition.participant.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/action-participant-type|4.3.0 and http://hl7.org/fhir/ValueSet/action-participant-type|5.0.0 (Equivalent) |
| ActivityDefinition.priority | ActivityDefinition.priority | Equivalent | R4B `ActivityDefinition.priority` maps as Equivalent to R5 `ActivityDefinition.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|4.3.0 and http://hl7.org/fhir/ValueSet/request-priority|5.0.0 (Equivalent) |
| ActivityDefinition.product[x] | ActivityDefinition.product[x] | SourceIsNarrowerThanTarget | R4B `ActivityDefinition.product[x]` maps as SourceIsNarrowerThanTarget to R5 `ActivityDefinition.product[x]` - product[x] has change due to type change: R4B `product[x]` `Reference` maps as SourceIsNarrowerThanTarget for R5 `product[x]` |
| ActivityDefinition.profile | ActivityDefinition.profile | Equivalent | R4B `ActivityDefinition.profile` maps as Equivalent to R5 `ActivityDefinition.profile` |
| ActivityDefinition.publisher | ActivityDefinition.publisher | Equivalent | R4B `ActivityDefinition.publisher` maps as Equivalent to R5 `ActivityDefinition.publisher` |
| ActivityDefinition.purpose | ActivityDefinition.purpose | Equivalent | R4B `ActivityDefinition.purpose` maps as Equivalent to R5 `ActivityDefinition.purpose` |
| ActivityDefinition.quantity | ActivityDefinition.quantity | Equivalent | R4B `ActivityDefinition.quantity` maps as Equivalent to R5 `ActivityDefinition.quantity` |
| ActivityDefinition.relatedArtifact | ActivityDefinition.relatedArtifact | Equivalent | R4B `ActivityDefinition.relatedArtifact` maps as Equivalent to R5 `ActivityDefinition.relatedArtifact` |
| ActivityDefinition.reviewer | ActivityDefinition.reviewer | Equivalent | R4B `ActivityDefinition.reviewer` maps as Equivalent to R5 `ActivityDefinition.reviewer` |
| ActivityDefinition.specimenRequirement | ActivityDefinition.specimenRequirement | SourceIsBroaderThanTarget | R4B `ActivityDefinition.specimenRequirement` maps as SourceIsBroaderThanTarget to R5 `ActivityDefinition.specimenRequirement` - specimenRequirement has change due to type change: R4B specimenRequirement Reference has no equivalent or mapped type in R5 specimenRequirement |
| ActivityDefinition.status | ActivityDefinition.status | Equivalent | R4B `ActivityDefinition.status` maps as Equivalent to R5 `ActivityDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| ActivityDefinition.subject[x] | ActivityDefinition.subject[x] | SourceIsNarrowerThanTarget | R4B `ActivityDefinition.subject[x]` maps as SourceIsNarrowerThanTarget to R5 `ActivityDefinition.subject[x]` - subject[x] has change due to type change: R4B `subject[x]` `Reference` maps as SourceIsNarrowerThanTarget for R5 `subject[x]`; subject[x] has change due to type change: R4B `subject[x]` `canonical` maps as SourceIsNarrowerThanTarget for R5 `subject[x]` |
| ActivityDefinition.subtitle | ActivityDefinition.subtitle | Equivalent | R4B `ActivityDefinition.subtitle` maps as Equivalent to R5 `ActivityDefinition.subtitle` |
| ActivityDefinition.text | ActivityDefinition.text | Equivalent | R4B `ActivityDefinition.text` maps as Equivalent to R5 `ActivityDefinition.text` |
| ActivityDefinition.timing[x] | ActivityDefinition.timing[x] | SourceIsBroaderThanTarget | R4B `ActivityDefinition.timing[x]` maps as SourceIsBroaderThanTarget to R5 `ActivityDefinition.timing[x]` - timing[x] has change due to type change: R4B timing[x] dateTime has no equivalent or mapped type in R5 timing[x]; timing[x] has change due to type change: R4B timing[x] Period has no equivalent or mapped type in R5 timing[x] |
| ActivityDefinition.title | ActivityDefinition.title | Equivalent | R4B `ActivityDefinition.title` maps as Equivalent to R5 `ActivityDefinition.title` |
| ActivityDefinition.topic | ActivityDefinition.topic | Equivalent | R4B `ActivityDefinition.topic` maps as Equivalent to R5 `ActivityDefinition.topic` |
| ActivityDefinition.transform | ActivityDefinition.transform | Equivalent | R4B `ActivityDefinition.transform` maps as Equivalent to R5 `ActivityDefinition.transform` |
| ActivityDefinition.url | ActivityDefinition.url | Equivalent | R4B `ActivityDefinition.url` maps as Equivalent to R5 `ActivityDefinition.url` |
| ActivityDefinition.usage | ActivityDefinition.usage | SourceIsBroaderThanTarget | R4B `ActivityDefinition.usage` maps as SourceIsBroaderThanTarget to R5 `ActivityDefinition.usage` - usage has change due to type change: R4B usage string has no equivalent or mapped type in R5 usage |
| ActivityDefinition.useContext | ActivityDefinition.useContext | Equivalent | R4B `ActivityDefinition.useContext` maps as Equivalent to R5 `ActivityDefinition.useContext` |
| ActivityDefinition.version | ActivityDefinition.version | Equivalent | R4B `ActivityDefinition.version` maps as Equivalent to R5 `ActivityDefinition.version` |

