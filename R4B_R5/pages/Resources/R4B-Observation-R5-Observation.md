Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Observation |  | Measurements and simple assertions made about a patient, device or other subject. | 50 | 36 |
| Target | Observation |  | Measurements and simple assertions made about a patient, device or other subject. | 60 | 43 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 46 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Observation | Observation | Equivalent | R4B `Observation` maps as Equivalent to R5 `Observation` |
| Observation.basedOn | Observation.basedOn | Equivalent | R4B `Observation.basedOn` maps as Equivalent to R5 `Observation.basedOn` |
| Observation.bodySite | Observation.bodySite | Equivalent | R4B `Observation.bodySite` maps as Equivalent to R5 `Observation.bodySite` |
| Observation.category | Observation.category | Equivalent | R4B `Observation.category` maps as Equivalent to R5 `Observation.category` |
| Observation.code | Observation.code | Equivalent | R4B `Observation.code` maps as Equivalent to R5 `Observation.code` |
| Observation.component | Observation.component | Equivalent | R4B `Observation.component` maps as Equivalent to R5 `Observation.component` |
| Observation.component.code | Observation.component.code | Equivalent | R4B `Observation.component.code` maps as Equivalent to R5 `Observation.component.code` |
| Observation.component.dataAbsentReason | Observation.component.dataAbsentReason | Equivalent | R4B `Observation.component.dataAbsentReason` maps as Equivalent to R5 `Observation.component.dataAbsentReason` |
| Observation.component.extension | Observation.component.extension | RelatedTo | R4B `Observation.component.extension` maps as RelatedTo to R5 `Observation.component.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Observation.component.id | Observation.component.id | Equivalent | R4B `Observation.component.id` maps as Equivalent to R5 `Observation.component.id` |
| Observation.component.interpretation | Observation.component.interpretation | Equivalent | R4B `Observation.component.interpretation` maps as Equivalent to R5 `Observation.component.interpretation` |
| Observation.component.modifierExtension | Observation.component.modifierExtension | RelatedTo | R4B `Observation.component.modifierExtension` maps as RelatedTo to R5 `Observation.component.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Observation.component.referenceRange | Observation.component.referenceRange | Equivalent | R4B `Observation.component.referenceRange` maps as Equivalent to R5 `Observation.component.referenceRange` |
| Observation.component.value[x] | Observation.component.value[x] | SourceIsNarrowerThanTarget | R4B `Observation.component.value[x]` maps as SourceIsNarrowerThanTarget to R5 `Observation.component.value[x]` - value[x] has change due to type change: R4B `value[x]` `Ratio` maps as SourceIsNarrowerThanTarget for R5 `value[x]` |
| Observation.contained | Observation.contained | Equivalent | R4B `Observation.contained` maps as Equivalent to R5 `Observation.contained` |
| Observation.dataAbsentReason | Observation.dataAbsentReason | Equivalent | R4B `Observation.dataAbsentReason` maps as Equivalent to R5 `Observation.dataAbsentReason` |
| Observation.derivedFrom | Observation.derivedFrom | RelatedTo | R4B `Observation.derivedFrom` maps as RelatedTo to R5 `Observation.derivedFrom` - derivedFrom has change due to type change: R4B `derivedFrom` `Reference` maps as RelatedTo for R5 `derivedFrom` |
| Observation.device | Observation.device | Equivalent | R4B `Observation.device` maps as Equivalent to R5 `Observation.device` |
| Observation.effective[x] | Observation.effective[x] | Equivalent | R4B `Observation.effective[x]` maps as Equivalent to R5 `Observation.effective[x]` |
| Observation.encounter | Observation.encounter | Equivalent | R4B `Observation.encounter` maps as Equivalent to R5 `Observation.encounter` |
| Observation.extension | Observation.extension | RelatedTo | R4B `Observation.extension` maps as RelatedTo to R5 `Observation.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Observation.focus | Observation.focus | Equivalent | R4B `Observation.focus` maps as Equivalent to R5 `Observation.focus` |
| Observation.hasMember | Observation.hasMember | Equivalent | R4B `Observation.hasMember` maps as Equivalent to R5 `Observation.hasMember` |
| Observation.id | Observation.id | Equivalent | R4B `Observation.id` maps as Equivalent to R5 `Observation.id` |
| Observation.identifier | Observation.identifier | Equivalent | R4B `Observation.identifier` maps as Equivalent to R5 `Observation.identifier` |
| Observation.implicitRules | Observation.implicitRules | Equivalent | R4B `Observation.implicitRules` maps as Equivalent to R5 `Observation.implicitRules` |
| Observation.interpretation | Observation.interpretation | Equivalent | R4B `Observation.interpretation` maps as Equivalent to R5 `Observation.interpretation` |
| Observation.issued | Observation.issued | Equivalent | R4B `Observation.issued` maps as Equivalent to R5 `Observation.issued` |
| Observation.language | Observation.language | RelatedTo | R4B `Observation.language` maps as RelatedTo to R5 `Observation.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Observation.meta | Observation.meta | Equivalent | R4B `Observation.meta` maps as Equivalent to R5 `Observation.meta` |
| Observation.method | Observation.method | Equivalent | R4B `Observation.method` maps as Equivalent to R5 `Observation.method` |
| Observation.modifierExtension | Observation.modifierExtension | RelatedTo | R4B `Observation.modifierExtension` maps as RelatedTo to R5 `Observation.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Observation.note | Observation.note | SourceIsNarrowerThanTarget | R4B `Observation.note` maps as SourceIsNarrowerThanTarget to R5 `Observation.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Observation.partOf | Observation.partOf | SourceIsNarrowerThanTarget | R4B `Observation.partOf` maps as SourceIsNarrowerThanTarget to R5 `Observation.partOf` - partOf has change due to type change: R4B `partOf` `Reference` maps as SourceIsNarrowerThanTarget for R5 `partOf` |
| Observation.performer | Observation.performer | Equivalent | R4B `Observation.performer` maps as Equivalent to R5 `Observation.performer` |
| Observation.referenceRange | Observation.referenceRange | Equivalent | R4B `Observation.referenceRange` maps as Equivalent to R5 `Observation.referenceRange` |
| Observation.referenceRange.age | Observation.referenceRange.age | Equivalent | R4B `Observation.referenceRange.age` maps as Equivalent to R5 `Observation.referenceRange.age` |
| Observation.referenceRange.appliesTo | Observation.referenceRange.appliesTo | Equivalent | R4B `Observation.referenceRange.appliesTo` maps as Equivalent to R5 `Observation.referenceRange.appliesTo` |
| Observation.referenceRange.extension | Observation.referenceRange.extension | RelatedTo | R4B `Observation.referenceRange.extension` maps as RelatedTo to R5 `Observation.referenceRange.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Observation.referenceRange.high | Observation.referenceRange.high | Equivalent | R4B `Observation.referenceRange.high` maps as Equivalent to R5 `Observation.referenceRange.high` |
| Observation.referenceRange.id | Observation.referenceRange.id | Equivalent | R4B `Observation.referenceRange.id` maps as Equivalent to R5 `Observation.referenceRange.id` |
| Observation.referenceRange.low | Observation.referenceRange.low | Equivalent | R4B `Observation.referenceRange.low` maps as Equivalent to R5 `Observation.referenceRange.low` |
| Observation.referenceRange.modifierExtension | Observation.referenceRange.modifierExtension | RelatedTo | R4B `Observation.referenceRange.modifierExtension` maps as RelatedTo to R5 `Observation.referenceRange.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Observation.referenceRange.text | Observation.referenceRange.text | SourceIsBroaderThanTarget | R4B `Observation.referenceRange.text` maps as SourceIsBroaderThanTarget to R5 `Observation.referenceRange.text` - text has change due to type change: R4B text string has no equivalent or mapped type in R5 text |
| Observation.referenceRange.type | Observation.referenceRange.type | Equivalent | R4B `Observation.referenceRange.type` maps as Equivalent to R5 `Observation.referenceRange.type` |
| Observation.specimen | Observation.specimen | SourceIsNarrowerThanTarget | R4B `Observation.specimen` maps as SourceIsNarrowerThanTarget to R5 `Observation.specimen` - specimen has change due to type change: R4B `specimen` `Reference` maps as SourceIsNarrowerThanTarget for R5 `specimen` |
| Observation.status | Observation.status | Equivalent | R4B `Observation.status` maps as Equivalent to R5 `Observation.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/observation-status|4.3.0 and http://hl7.org/fhir/ValueSet/observation-status|5.0.0 (Equivalent) |
| Observation.subject | Observation.subject | SourceIsNarrowerThanTarget | R4B `Observation.subject` maps as SourceIsNarrowerThanTarget to R5 `Observation.subject` - subject has change due to type change: R4B `subject` `Reference` maps as SourceIsNarrowerThanTarget for R5 `subject` |
| Observation.text | Observation.text | Equivalent | R4B `Observation.text` maps as Equivalent to R5 `Observation.text` |
| Observation.value[x] | Observation.value[x] | SourceIsNarrowerThanTarget | R4B `Observation.value[x]` maps as SourceIsNarrowerThanTarget to R5 `Observation.value[x]` - value[x] has change due to type change: R4B `value[x]` `Ratio` maps as SourceIsNarrowerThanTarget for R5 `value[x]` |

