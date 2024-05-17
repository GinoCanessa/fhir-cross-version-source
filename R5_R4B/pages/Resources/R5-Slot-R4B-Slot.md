Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Slot |  | A slot of time on a schedule that may be available for booking appointments. | 20 | 12 |
| Target | Slot |  | A slot of time on a schedule that may be available for booking appointments. | 20 | 12 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 16 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Slot | Slot | Equivalent | R5 `Slot` maps as Equivalent to R4B `Slot` |
| Slot.appointmentType | Slot.appointmentType | RelatedTo | R5 `Slot.appointmentType` maps as RelatedTo to R4B `Slot.appointmentType` - appointmentType changed from array to scalar (max cardinality from * to 1) |
| Slot.comment | Slot.comment | Equivalent | R5 `Slot.comment` maps as Equivalent to R4B `Slot.comment` |
| Slot.contained | Slot.contained | Equivalent | R5 `Slot.contained` maps as Equivalent to R4B `Slot.contained` |
| Slot.end | Slot.end | Equivalent | R5 `Slot.end` maps as Equivalent to R4B `Slot.end` |
| Slot.extension | Slot.extension | SourceIsBroaderThanTarget | R5 `Slot.extension` maps as SourceIsBroaderThanTarget to R4B `Slot.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Slot.id | Slot.id | Equivalent | R5 `Slot.id` maps as Equivalent to R4B `Slot.id` |
| Slot.identifier | Slot.identifier | Equivalent | R5 `Slot.identifier` maps as Equivalent to R4B `Slot.identifier` |
| Slot.implicitRules | Slot.implicitRules | Equivalent | R5 `Slot.implicitRules` maps as Equivalent to R4B `Slot.implicitRules` |
| Slot.language | Slot.language | RelatedTo | R5 `Slot.language` maps as RelatedTo to R4B `Slot.language` - language changed the binding strength from Required to Preferred |
| Slot.meta | Slot.meta | Equivalent | R5 `Slot.meta` maps as Equivalent to R4B `Slot.meta` |
| Slot.modifierExtension | Slot.modifierExtension | SourceIsBroaderThanTarget | R5 `Slot.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Slot.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Slot.overbooked | Slot.overbooked | Equivalent | R5 `Slot.overbooked` maps as Equivalent to R4B `Slot.overbooked` |
| Slot.schedule | Slot.schedule | Equivalent | R5 `Slot.schedule` maps as Equivalent to R4B `Slot.schedule` |
| Slot.serviceCategory | Slot.serviceCategory | Equivalent | R5 `Slot.serviceCategory` maps as Equivalent to R4B `Slot.serviceCategory` |
| Slot.serviceType | Slot.serviceType | SourceIsBroaderThanTarget | R5 `Slot.serviceType` maps as SourceIsBroaderThanTarget to R4B `Slot.serviceType` - serviceType has change due to type change: R5 serviceType CodeableReference has no equivalent or mapped type in R4B serviceType |
| Slot.specialty | Slot.specialty | Equivalent | R5 `Slot.specialty` maps as Equivalent to R4B `Slot.specialty` |
| Slot.start | Slot.start | Equivalent | R5 `Slot.start` maps as Equivalent to R4B `Slot.start` |
| Slot.status | Slot.status | Equivalent | R5 `Slot.status` maps as Equivalent to R4B `Slot.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/slotstatus|5.0.0 and http://hl7.org/fhir/ValueSet/slotstatus|4.3.0 (Equivalent) |
| Slot.text | Slot.text | Equivalent | R5 `Slot.text` maps as Equivalent to R4B `Slot.text` |

