Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | AllergyIntolerance |  | Risk of harmful or undesirable, physiological response which is unique to an individual and associated with exposure to a substance. | 35 | 24 |
| Target | AllergyIntolerance |  | Risk of harmful or undesirable, physiological response which is unique to an individual and associated with exposure to a substance. | 39 | 25 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 29 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| AllergyIntolerance | AllergyIntolerance | Equivalent | R4B `AllergyIntolerance` maps as Equivalent to R5 `AllergyIntolerance` |
| AllergyIntolerance.asserter | - | DoesNotExistInTarget | R4B `AllergyIntolerance.asserter` does not appear in the target and has no mapping for `AllergyIntolerance`. |
| AllergyIntolerance.category | AllergyIntolerance.category | Equivalent | R4B `AllergyIntolerance.category` maps as Equivalent to R5 `AllergyIntolerance.category` - category has compatible required binding for code type: http://hl7.org/fhir/ValueSet/allergy-intolerance-category|4.3.0 and http://hl7.org/fhir/ValueSet/allergy-intolerance-category|5.0.0 (Equivalent) |
| AllergyIntolerance.clinicalStatus | AllergyIntolerance.clinicalStatus | Equivalent | R4B `AllergyIntolerance.clinicalStatus` maps as Equivalent to R5 `AllergyIntolerance.clinicalStatus` - clinicalStatus has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/allergyintolerance-clinical|4.3.0 and http://hl7.org/fhir/ValueSet/allergyintolerance-clinical|5.0.0 (Equivalent) |
| AllergyIntolerance.code | AllergyIntolerance.code | Equivalent | R4B `AllergyIntolerance.code` maps as Equivalent to R5 `AllergyIntolerance.code` |
| AllergyIntolerance.contained | AllergyIntolerance.contained | Equivalent | R4B `AllergyIntolerance.contained` maps as Equivalent to R5 `AllergyIntolerance.contained` |
| AllergyIntolerance.criticality | AllergyIntolerance.criticality | Equivalent | R4B `AllergyIntolerance.criticality` maps as Equivalent to R5 `AllergyIntolerance.criticality` - criticality has compatible required binding for code type: http://hl7.org/fhir/ValueSet/allergy-intolerance-criticality|4.3.0 and http://hl7.org/fhir/ValueSet/allergy-intolerance-criticality|5.0.0 (Equivalent) |
| AllergyIntolerance.encounter | AllergyIntolerance.encounter | Equivalent | R4B `AllergyIntolerance.encounter` maps as Equivalent to R5 `AllergyIntolerance.encounter` |
| AllergyIntolerance.extension | AllergyIntolerance.extension | RelatedTo | R4B `AllergyIntolerance.extension` maps as RelatedTo to R5 `AllergyIntolerance.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| AllergyIntolerance.id | AllergyIntolerance.id | Equivalent | R4B `AllergyIntolerance.id` maps as Equivalent to R5 `AllergyIntolerance.id` |
| AllergyIntolerance.identifier | AllergyIntolerance.identifier | Equivalent | R4B `AllergyIntolerance.identifier` maps as Equivalent to R5 `AllergyIntolerance.identifier` |
| AllergyIntolerance.implicitRules | AllergyIntolerance.implicitRules | Equivalent | R4B `AllergyIntolerance.implicitRules` maps as Equivalent to R5 `AllergyIntolerance.implicitRules` |
| AllergyIntolerance.language | AllergyIntolerance.language | RelatedTo | R4B `AllergyIntolerance.language` maps as RelatedTo to R5 `AllergyIntolerance.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| AllergyIntolerance.lastOccurrence | AllergyIntolerance.lastOccurrence | Equivalent | R4B `AllergyIntolerance.lastOccurrence` maps as Equivalent to R5 `AllergyIntolerance.lastOccurrence` |
| AllergyIntolerance.meta | AllergyIntolerance.meta | Equivalent | R4B `AllergyIntolerance.meta` maps as Equivalent to R5 `AllergyIntolerance.meta` |
| AllergyIntolerance.modifierExtension | AllergyIntolerance.modifierExtension | RelatedTo | R4B `AllergyIntolerance.modifierExtension` maps as RelatedTo to R5 `AllergyIntolerance.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| AllergyIntolerance.note | AllergyIntolerance.note | SourceIsNarrowerThanTarget | R4B `AllergyIntolerance.note` maps as SourceIsNarrowerThanTarget to R5 `AllergyIntolerance.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| AllergyIntolerance.onset[x] | AllergyIntolerance.onset[x] | Equivalent | R4B `AllergyIntolerance.onset[x]` maps as Equivalent to R5 `AllergyIntolerance.onset[x]` |
| AllergyIntolerance.patient | AllergyIntolerance.patient | Equivalent | R4B `AllergyIntolerance.patient` maps as Equivalent to R5 `AllergyIntolerance.patient` |
| AllergyIntolerance.reaction | AllergyIntolerance.reaction | Equivalent | R4B `AllergyIntolerance.reaction` maps as Equivalent to R5 `AllergyIntolerance.reaction` |
| AllergyIntolerance.reaction.description | AllergyIntolerance.reaction.description | Equivalent | R4B `AllergyIntolerance.reaction.description` maps as Equivalent to R5 `AllergyIntolerance.reaction.description` |
| AllergyIntolerance.reaction.exposureRoute | AllergyIntolerance.reaction.exposureRoute | Equivalent | R4B `AllergyIntolerance.reaction.exposureRoute` maps as Equivalent to R5 `AllergyIntolerance.reaction.exposureRoute` |
| AllergyIntolerance.reaction.extension | AllergyIntolerance.reaction.extension | RelatedTo | R4B `AllergyIntolerance.reaction.extension` maps as RelatedTo to R5 `AllergyIntolerance.reaction.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| AllergyIntolerance.reaction.id | AllergyIntolerance.reaction.id | Equivalent | R4B `AllergyIntolerance.reaction.id` maps as Equivalent to R5 `AllergyIntolerance.reaction.id` |
| AllergyIntolerance.reaction.manifestation | AllergyIntolerance.reaction.manifestation | SourceIsBroaderThanTarget | R4B `AllergyIntolerance.reaction.manifestation` maps as SourceIsBroaderThanTarget to R5 `AllergyIntolerance.reaction.manifestation` - manifestation has change due to type change: R4B manifestation CodeableConcept has no equivalent or mapped type in R5 manifestation |
| AllergyIntolerance.reaction.modifierExtension | AllergyIntolerance.reaction.modifierExtension | RelatedTo | R4B `AllergyIntolerance.reaction.modifierExtension` maps as RelatedTo to R5 `AllergyIntolerance.reaction.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| AllergyIntolerance.reaction.note | AllergyIntolerance.reaction.note | SourceIsNarrowerThanTarget | R4B `AllergyIntolerance.reaction.note` maps as SourceIsNarrowerThanTarget to R5 `AllergyIntolerance.reaction.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| AllergyIntolerance.reaction.onset | AllergyIntolerance.reaction.onset | Equivalent | R4B `AllergyIntolerance.reaction.onset` maps as Equivalent to R5 `AllergyIntolerance.reaction.onset` |
| AllergyIntolerance.reaction.severity | AllergyIntolerance.reaction.severity | Equivalent | R4B `AllergyIntolerance.reaction.severity` maps as Equivalent to R5 `AllergyIntolerance.reaction.severity` - severity has compatible required binding for code type: http://hl7.org/fhir/ValueSet/reaction-event-severity|4.3.0 and http://hl7.org/fhir/ValueSet/reaction-event-severity|5.0.0 (Equivalent) |
| AllergyIntolerance.reaction.substance | AllergyIntolerance.reaction.substance | Equivalent | R4B `AllergyIntolerance.reaction.substance` maps as Equivalent to R5 `AllergyIntolerance.reaction.substance` |
| AllergyIntolerance.recordedDate | AllergyIntolerance.recordedDate | Equivalent | R4B `AllergyIntolerance.recordedDate` maps as Equivalent to R5 `AllergyIntolerance.recordedDate` |
| AllergyIntolerance.recorder | - | DoesNotExistInTarget | R4B `AllergyIntolerance.recorder` does not appear in the target and has no mapping for `AllergyIntolerance`. |
| AllergyIntolerance.text | AllergyIntolerance.text | Equivalent | R4B `AllergyIntolerance.text` maps as Equivalent to R5 `AllergyIntolerance.text` |
| AllergyIntolerance.type | AllergyIntolerance.type | RelatedTo | R4B `AllergyIntolerance.type` maps as RelatedTo to R5 `AllergyIntolerance.type` - type changed the binding strength from Required to Preferred; type has change due to type change: R4B type code has no equivalent or mapped type in R5 type |
| AllergyIntolerance.verificationStatus | AllergyIntolerance.verificationStatus | Equivalent | R4B `AllergyIntolerance.verificationStatus` maps as Equivalent to R5 `AllergyIntolerance.verificationStatus` - verificationStatus has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/allergyintolerance-verification|4.3.0 and http://hl7.org/fhir/ValueSet/allergyintolerance-verification|5.0.0 (Equivalent) |

