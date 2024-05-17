Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | AllergyIntolerance |  | Risk of harmful or undesirable, physiological response which is unique to an individual and associated with exposure to a substance. | 39 | 25 |
| Target | AllergyIntolerance |  | Risk of harmful or undesirable, physiological response which is unique to an individual and associated with exposure to a substance. | 35 | 24 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 6 |
Equivalent | 4 |
RelatedTo | 29 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| AllergyIntolerance | AllergyIntolerance | Equivalent | R5 `AllergyIntolerance` maps as Equivalent to R4B `AllergyIntolerance` |
| AllergyIntolerance.category | AllergyIntolerance.category | Equivalent | R5 `AllergyIntolerance.category` maps as Equivalent to R4B `AllergyIntolerance.category` - category has compatible required binding for code type: http://hl7.org/fhir/ValueSet/allergy-intolerance-category|5.0.0 and http://hl7.org/fhir/ValueSet/allergy-intolerance-category|4.3.0 (Equivalent) |
| AllergyIntolerance.clinicalStatus | AllergyIntolerance.clinicalStatus | Equivalent | R5 `AllergyIntolerance.clinicalStatus` maps as Equivalent to R4B `AllergyIntolerance.clinicalStatus` - clinicalStatus has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/allergyintolerance-clinical|5.0.0 and http://hl7.org/fhir/ValueSet/allergyintolerance-clinical|4.3.0 (Equivalent) |
| AllergyIntolerance.code | AllergyIntolerance.code | Equivalent | R5 `AllergyIntolerance.code` maps as Equivalent to R4B `AllergyIntolerance.code` |
| AllergyIntolerance.contained | AllergyIntolerance.contained | Equivalent | R5 `AllergyIntolerance.contained` maps as Equivalent to R4B `AllergyIntolerance.contained` |
| AllergyIntolerance.criticality | AllergyIntolerance.criticality | Equivalent | R5 `AllergyIntolerance.criticality` maps as Equivalent to R4B `AllergyIntolerance.criticality` - criticality has compatible required binding for code type: http://hl7.org/fhir/ValueSet/allergy-intolerance-criticality|5.0.0 and http://hl7.org/fhir/ValueSet/allergy-intolerance-criticality|4.3.0 (Equivalent) |
| AllergyIntolerance.encounter | AllergyIntolerance.encounter | Equivalent | R5 `AllergyIntolerance.encounter` maps as Equivalent to R4B `AllergyIntolerance.encounter` |
| AllergyIntolerance.extension | AllergyIntolerance.extension | SourceIsBroaderThanTarget | R5 `AllergyIntolerance.extension` maps as SourceIsBroaderThanTarget to R4B `AllergyIntolerance.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| AllergyIntolerance.id | AllergyIntolerance.id | Equivalent | R5 `AllergyIntolerance.id` maps as Equivalent to R4B `AllergyIntolerance.id` |
| AllergyIntolerance.identifier | AllergyIntolerance.identifier | Equivalent | R5 `AllergyIntolerance.identifier` maps as Equivalent to R4B `AllergyIntolerance.identifier` |
| AllergyIntolerance.implicitRules | AllergyIntolerance.implicitRules | Equivalent | R5 `AllergyIntolerance.implicitRules` maps as Equivalent to R4B `AllergyIntolerance.implicitRules` |
| AllergyIntolerance.language | AllergyIntolerance.language | RelatedTo | R5 `AllergyIntolerance.language` maps as RelatedTo to R4B `AllergyIntolerance.language` - language changed the binding strength from Required to Preferred |
| AllergyIntolerance.lastOccurrence | AllergyIntolerance.lastOccurrence | Equivalent | R5 `AllergyIntolerance.lastOccurrence` maps as Equivalent to R4B `AllergyIntolerance.lastOccurrence` |
| AllergyIntolerance.meta | AllergyIntolerance.meta | Equivalent | R5 `AllergyIntolerance.meta` maps as Equivalent to R4B `AllergyIntolerance.meta` |
| AllergyIntolerance.modifierExtension | AllergyIntolerance.modifierExtension | SourceIsBroaderThanTarget | R5 `AllergyIntolerance.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `AllergyIntolerance.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| AllergyIntolerance.note | AllergyIntolerance.note | SourceIsBroaderThanTarget | R5 `AllergyIntolerance.note` maps as SourceIsBroaderThanTarget to R4B `AllergyIntolerance.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| AllergyIntolerance.onset[x] | AllergyIntolerance.onset[x] | Equivalent | R5 `AllergyIntolerance.onset[x]` maps as Equivalent to R4B `AllergyIntolerance.onset[x]` |
| AllergyIntolerance.participant | - | DoesNotExistInTarget | R5 `AllergyIntolerance.participant` does not appear in the target and has no mapping for `AllergyIntolerance`. |
| AllergyIntolerance.participant.actor | - | DoesNotExistInTarget | R5 `AllergyIntolerance.participant.actor` does not appear in the target and has no mapping for `AllergyIntolerance`. |
| AllergyIntolerance.participant.extension | - | DoesNotExistInTarget | R5 `AllergyIntolerance.participant.extension` does not appear in the target and has no mapping for `AllergyIntolerance`. |
| AllergyIntolerance.participant.function | - | DoesNotExistInTarget | R5 `AllergyIntolerance.participant.function` does not appear in the target and has no mapping for `AllergyIntolerance`. |
| AllergyIntolerance.participant.id | - | DoesNotExistInTarget | R5 `AllergyIntolerance.participant.id` does not appear in the target and has no mapping for `AllergyIntolerance`. |
| AllergyIntolerance.participant.modifierExtension | - | DoesNotExistInTarget | R5 `AllergyIntolerance.participant.modifierExtension` does not appear in the target and has no mapping for `AllergyIntolerance`. |
| AllergyIntolerance.patient | AllergyIntolerance.patient | Equivalent | R5 `AllergyIntolerance.patient` maps as Equivalent to R4B `AllergyIntolerance.patient` |
| AllergyIntolerance.reaction | AllergyIntolerance.reaction | Equivalent | R5 `AllergyIntolerance.reaction` maps as Equivalent to R4B `AllergyIntolerance.reaction` |
| AllergyIntolerance.reaction.description | AllergyIntolerance.reaction.description | Equivalent | R5 `AllergyIntolerance.reaction.description` maps as Equivalent to R4B `AllergyIntolerance.reaction.description` |
| AllergyIntolerance.reaction.exposureRoute | AllergyIntolerance.reaction.exposureRoute | Equivalent | R5 `AllergyIntolerance.reaction.exposureRoute` maps as Equivalent to R4B `AllergyIntolerance.reaction.exposureRoute` |
| AllergyIntolerance.reaction.extension | AllergyIntolerance.reaction.extension | SourceIsBroaderThanTarget | R5 `AllergyIntolerance.reaction.extension` maps as SourceIsBroaderThanTarget to R4B `AllergyIntolerance.reaction.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| AllergyIntolerance.reaction.id | AllergyIntolerance.reaction.id | Equivalent | R5 `AllergyIntolerance.reaction.id` maps as Equivalent to R4B `AllergyIntolerance.reaction.id` |
| AllergyIntolerance.reaction.manifestation | AllergyIntolerance.reaction.manifestation | SourceIsBroaderThanTarget | R5 `AllergyIntolerance.reaction.manifestation` maps as SourceIsBroaderThanTarget to R4B `AllergyIntolerance.reaction.manifestation` - manifestation has change due to type change: R5 manifestation CodeableReference has no equivalent or mapped type in R4B manifestation |
| AllergyIntolerance.reaction.modifierExtension | AllergyIntolerance.reaction.modifierExtension | SourceIsBroaderThanTarget | R5 `AllergyIntolerance.reaction.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `AllergyIntolerance.reaction.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| AllergyIntolerance.reaction.note | AllergyIntolerance.reaction.note | SourceIsBroaderThanTarget | R5 `AllergyIntolerance.reaction.note` maps as SourceIsBroaderThanTarget to R4B `AllergyIntolerance.reaction.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| AllergyIntolerance.reaction.onset | AllergyIntolerance.reaction.onset | Equivalent | R5 `AllergyIntolerance.reaction.onset` maps as Equivalent to R4B `AllergyIntolerance.reaction.onset` |
| AllergyIntolerance.reaction.severity | AllergyIntolerance.reaction.severity | Equivalent | R5 `AllergyIntolerance.reaction.severity` maps as Equivalent to R4B `AllergyIntolerance.reaction.severity` - severity has compatible required binding for code type: http://hl7.org/fhir/ValueSet/reaction-event-severity|5.0.0 and http://hl7.org/fhir/ValueSet/reaction-event-severity|4.3.0 (Equivalent) |
| AllergyIntolerance.reaction.substance | AllergyIntolerance.reaction.substance | Equivalent | R5 `AllergyIntolerance.reaction.substance` maps as Equivalent to R4B `AllergyIntolerance.reaction.substance` |
| AllergyIntolerance.recordedDate | AllergyIntolerance.recordedDate | Equivalent | R5 `AllergyIntolerance.recordedDate` maps as Equivalent to R4B `AllergyIntolerance.recordedDate` |
| AllergyIntolerance.text | AllergyIntolerance.text | Equivalent | R5 `AllergyIntolerance.text` maps as Equivalent to R4B `AllergyIntolerance.text` |
| AllergyIntolerance.type | AllergyIntolerance.type | RelatedTo | R5 `AllergyIntolerance.type` maps as RelatedTo to R4B `AllergyIntolerance.type` - type made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/allergy-intolerance-type|4.3.0; type has change due to type change: R5 type CodeableConcept has no equivalent or mapped type in R4B type |
| AllergyIntolerance.verificationStatus | AllergyIntolerance.verificationStatus | Equivalent | R5 `AllergyIntolerance.verificationStatus` maps as Equivalent to R4B `AllergyIntolerance.verificationStatus` - verificationStatus has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/allergyintolerance-verification|5.0.0 and http://hl7.org/fhir/ValueSet/allergyintolerance-verification|4.3.0 (Equivalent) |

