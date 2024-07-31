Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Slot |  | A slot of time on a schedule that may be available for booking appointments. | 20 | 12 |
| Target | Slot |  | A slot of time on a schedule that may be available for booking appointments. | 20 | 12 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 15 |
SourceIsBroaderThanTarget | 4 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Slot | Slot | Equivalent | R5 `Slot` maps as Equivalent to R4 `Slot` |
| Slot.appointmentType | Slot.appointmentType | SourceIsBroaderThanTarget | R5 `Slot.appointmentType` maps as SourceIsBroaderThanTarget to R4 `Slot.appointmentType` - appointmentType changed from array to scalar (max cardinality from * to 1) |
| Slot.comment | Slot.comment | Equivalent | R5 `Slot.comment` maps as Equivalent to R4 `Slot.comment` |
| Slot.contained | Slot.contained | Equivalent | R5 `Slot.contained` maps as Equivalent to R4 `Slot.contained` |
| Slot.end | Slot.end | Equivalent | R5 `Slot.end` maps as Equivalent to R4 `Slot.end` |
| Slot.extension | Slot.extension | SourceIsBroaderThanTarget | R5 `Slot.extension` maps as SourceIsBroaderThanTarget to R4 `Slot.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Slot.id | Slot.id | Equivalent | R5 `Slot.id` maps as Equivalent to R4 `Slot.id` |
| Slot.identifier | Slot.identifier | Equivalent | R5 `Slot.identifier` maps as Equivalent to R4 `Slot.identifier` |
| Slot.implicitRules | Slot.implicitRules | Equivalent | R5 `Slot.implicitRules` maps as Equivalent to R4 `Slot.implicitRules` |
| Slot.language | Slot.language | SourceIsNarrowerThanTarget | R5 `Slot.language` maps as SourceIsNarrowerThanTarget to R4 `Slot.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Slot.meta | Slot.meta | Equivalent | R5 `Slot.meta` maps as Equivalent to R4 `Slot.meta` |
| Slot.modifierExtension | Slot.modifierExtension | SourceIsBroaderThanTarget | R5 `Slot.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Slot.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Slot.overbooked | Slot.overbooked | Equivalent | R5 `Slot.overbooked` maps as Equivalent to R4 `Slot.overbooked` |
| Slot.schedule | Slot.schedule | Equivalent | R5 `Slot.schedule` maps as Equivalent to R4 `Slot.schedule` |
| Slot.serviceCategory | Slot.serviceCategory | Equivalent | R5 `Slot.serviceCategory` maps as Equivalent to R4 `Slot.serviceCategory` |
| Slot.serviceType | Slot.serviceType | SourceIsBroaderThanTarget | R5 `Slot.serviceType` maps as SourceIsBroaderThanTarget to R4 `Slot.serviceType` - serviceType has change due to type change: R5 serviceType CodeableReference has no equivalent or mapped type in R4 serviceType |
| Slot.specialty | Slot.specialty | Equivalent | R5 `Slot.specialty` maps as Equivalent to R4 `Slot.specialty` |
| Slot.start | Slot.start | Equivalent | R5 `Slot.start` maps as Equivalent to R4 `Slot.start` |
| Slot.status | Slot.status | Equivalent | R5 `Slot.status` maps as Equivalent to R4 `Slot.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/slotstatus|5.0.0 and http://hl7.org/fhir/ValueSet/slotstatus|4.0.1 (Equivalent) |
| Slot.text | Slot.text | Equivalent | R5 `Slot.text` maps as Equivalent to R4 `Slot.text` |

