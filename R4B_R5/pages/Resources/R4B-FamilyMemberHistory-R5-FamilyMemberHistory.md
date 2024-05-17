Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | FamilyMemberHistory |  | Significant health conditions for a person related to the patient relevant in the context of care for the patient. | 35 | 24 |
| Target | FamilyMemberHistory |  | Significant health conditions for a person related to the patient relevant in the context of care for the patient. | 49 | 32 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 29 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| FamilyMemberHistory | FamilyMemberHistory | Equivalent | R4B `FamilyMemberHistory` maps as Equivalent to R5 `FamilyMemberHistory` |
| FamilyMemberHistory.age[x] | FamilyMemberHistory.age[x] | Equivalent | R4B `FamilyMemberHistory.age[x]` maps as Equivalent to R5 `FamilyMemberHistory.age[x]` |
| FamilyMemberHistory.born[x] | FamilyMemberHistory.born[x] | Equivalent | R4B `FamilyMemberHistory.born[x]` maps as Equivalent to R5 `FamilyMemberHistory.born[x]` |
| FamilyMemberHistory.condition | FamilyMemberHistory.condition | Equivalent | R4B `FamilyMemberHistory.condition` maps as Equivalent to R5 `FamilyMemberHistory.condition` |
| FamilyMemberHistory.condition.code | FamilyMemberHistory.condition.code | Equivalent | R4B `FamilyMemberHistory.condition.code` maps as Equivalent to R5 `FamilyMemberHistory.condition.code` |
| FamilyMemberHistory.condition.contributedToDeath | FamilyMemberHistory.condition.contributedToDeath | Equivalent | R4B `FamilyMemberHistory.condition.contributedToDeath` maps as Equivalent to R5 `FamilyMemberHistory.condition.contributedToDeath` |
| FamilyMemberHistory.condition.extension | FamilyMemberHistory.condition.extension | RelatedTo | R4B `FamilyMemberHistory.condition.extension` maps as RelatedTo to R5 `FamilyMemberHistory.condition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| FamilyMemberHistory.condition.id | FamilyMemberHistory.condition.id | Equivalent | R4B `FamilyMemberHistory.condition.id` maps as Equivalent to R5 `FamilyMemberHistory.condition.id` |
| FamilyMemberHistory.condition.modifierExtension | FamilyMemberHistory.condition.modifierExtension | RelatedTo | R4B `FamilyMemberHistory.condition.modifierExtension` maps as RelatedTo to R5 `FamilyMemberHistory.condition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| FamilyMemberHistory.condition.note | FamilyMemberHistory.condition.note | SourceIsNarrowerThanTarget | R4B `FamilyMemberHistory.condition.note` maps as SourceIsNarrowerThanTarget to R5 `FamilyMemberHistory.condition.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| FamilyMemberHistory.condition.onset[x] | FamilyMemberHistory.condition.onset[x] | Equivalent | R4B `FamilyMemberHistory.condition.onset[x]` maps as Equivalent to R5 `FamilyMemberHistory.condition.onset[x]` |
| FamilyMemberHistory.condition.outcome | FamilyMemberHistory.condition.outcome | Equivalent | R4B `FamilyMemberHistory.condition.outcome` maps as Equivalent to R5 `FamilyMemberHistory.condition.outcome` |
| FamilyMemberHistory.contained | FamilyMemberHistory.contained | Equivalent | R4B `FamilyMemberHistory.contained` maps as Equivalent to R5 `FamilyMemberHistory.contained` |
| FamilyMemberHistory.dataAbsentReason | FamilyMemberHistory.dataAbsentReason | Equivalent | R4B `FamilyMemberHistory.dataAbsentReason` maps as Equivalent to R5 `FamilyMemberHistory.dataAbsentReason` |
| FamilyMemberHistory.date | FamilyMemberHistory.date | Equivalent | R4B `FamilyMemberHistory.date` maps as Equivalent to R5 `FamilyMemberHistory.date` |
| FamilyMemberHistory.deceased[x] | FamilyMemberHistory.deceased[x] | Equivalent | R4B `FamilyMemberHistory.deceased[x]` maps as Equivalent to R5 `FamilyMemberHistory.deceased[x]` |
| FamilyMemberHistory.estimatedAge | FamilyMemberHistory.estimatedAge | Equivalent | R4B `FamilyMemberHistory.estimatedAge` maps as Equivalent to R5 `FamilyMemberHistory.estimatedAge` |
| FamilyMemberHistory.extension | FamilyMemberHistory.extension | RelatedTo | R4B `FamilyMemberHistory.extension` maps as RelatedTo to R5 `FamilyMemberHistory.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| FamilyMemberHistory.id | FamilyMemberHistory.id | Equivalent | R4B `FamilyMemberHistory.id` maps as Equivalent to R5 `FamilyMemberHistory.id` |
| FamilyMemberHistory.identifier | FamilyMemberHistory.identifier | Equivalent | R4B `FamilyMemberHistory.identifier` maps as Equivalent to R5 `FamilyMemberHistory.identifier` |
| FamilyMemberHistory.implicitRules | FamilyMemberHistory.implicitRules | Equivalent | R4B `FamilyMemberHistory.implicitRules` maps as Equivalent to R5 `FamilyMemberHistory.implicitRules` |
| FamilyMemberHistory.instantiatesCanonical | FamilyMemberHistory.instantiatesCanonical | Equivalent | R4B `FamilyMemberHistory.instantiatesCanonical` maps as Equivalent to R5 `FamilyMemberHistory.instantiatesCanonical` |
| FamilyMemberHistory.instantiatesUri | FamilyMemberHistory.instantiatesUri | Equivalent | R4B `FamilyMemberHistory.instantiatesUri` maps as Equivalent to R5 `FamilyMemberHistory.instantiatesUri` |
| FamilyMemberHistory.language | FamilyMemberHistory.language | RelatedTo | R4B `FamilyMemberHistory.language` maps as RelatedTo to R5 `FamilyMemberHistory.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| FamilyMemberHistory.meta | FamilyMemberHistory.meta | Equivalent | R4B `FamilyMemberHistory.meta` maps as Equivalent to R5 `FamilyMemberHistory.meta` |
| FamilyMemberHistory.modifierExtension | FamilyMemberHistory.modifierExtension | RelatedTo | R4B `FamilyMemberHistory.modifierExtension` maps as RelatedTo to R5 `FamilyMemberHistory.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| FamilyMemberHistory.name | FamilyMemberHistory.name | Equivalent | R4B `FamilyMemberHistory.name` maps as Equivalent to R5 `FamilyMemberHistory.name` |
| FamilyMemberHistory.note | FamilyMemberHistory.note | SourceIsNarrowerThanTarget | R4B `FamilyMemberHistory.note` maps as SourceIsNarrowerThanTarget to R5 `FamilyMemberHistory.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| FamilyMemberHistory.patient | FamilyMemberHistory.patient | Equivalent | R4B `FamilyMemberHistory.patient` maps as Equivalent to R5 `FamilyMemberHistory.patient` |
| FamilyMemberHistory.reasonCode | - | DoesNotExistInTarget | R4B `FamilyMemberHistory.reasonCode` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.reasonReference | - | DoesNotExistInTarget | R4B `FamilyMemberHistory.reasonReference` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.relationship | FamilyMemberHistory.relationship | Equivalent | R4B `FamilyMemberHistory.relationship` maps as Equivalent to R5 `FamilyMemberHistory.relationship` |
| FamilyMemberHistory.sex | FamilyMemberHistory.sex | Equivalent | R4B `FamilyMemberHistory.sex` maps as Equivalent to R5 `FamilyMemberHistory.sex` |
| FamilyMemberHistory.status | FamilyMemberHistory.status | Equivalent | R4B `FamilyMemberHistory.status` maps as Equivalent to R5 `FamilyMemberHistory.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/history-status|4.3.0 and http://hl7.org/fhir/ValueSet/history-status|5.0.0 (Equivalent) |
| FamilyMemberHistory.text | FamilyMemberHistory.text | Equivalent | R4B `FamilyMemberHistory.text` maps as Equivalent to R5 `FamilyMemberHistory.text` |

