Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

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
| Slot | Slot | Equivalent | R4B `Slot` maps as Equivalent to R5 `Slot` |
| Slot.appointmentType | Slot.appointmentType | RelatedTo | R4B `Slot.appointmentType` maps as RelatedTo to R5 `Slot.appointmentType` - appointmentType changed from scalar to array (max cardinality from 1 to *) |
| Slot.comment | Slot.comment | Equivalent | R4B `Slot.comment` maps as Equivalent to R5 `Slot.comment` |
| Slot.contained | Slot.contained | Equivalent | R4B `Slot.contained` maps as Equivalent to R5 `Slot.contained` |
| Slot.end | Slot.end | Equivalent | R4B `Slot.end` maps as Equivalent to R5 `Slot.end` |
| Slot.extension | Slot.extension | RelatedTo | R4B `Slot.extension` maps as RelatedTo to R5 `Slot.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Slot.id | Slot.id | Equivalent | R4B `Slot.id` maps as Equivalent to R5 `Slot.id` |
| Slot.identifier | Slot.identifier | Equivalent | R4B `Slot.identifier` maps as Equivalent to R5 `Slot.identifier` |
| Slot.implicitRules | Slot.implicitRules | Equivalent | R4B `Slot.implicitRules` maps as Equivalent to R5 `Slot.implicitRules` |
| Slot.language | Slot.language | RelatedTo | R4B `Slot.language` maps as RelatedTo to R5 `Slot.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Slot.meta | Slot.meta | Equivalent | R4B `Slot.meta` maps as Equivalent to R5 `Slot.meta` |
| Slot.modifierExtension | Slot.modifierExtension | RelatedTo | R4B `Slot.modifierExtension` maps as RelatedTo to R5 `Slot.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Slot.overbooked | Slot.overbooked | Equivalent | R4B `Slot.overbooked` maps as Equivalent to R5 `Slot.overbooked` |
| Slot.schedule | Slot.schedule | Equivalent | R4B `Slot.schedule` maps as Equivalent to R5 `Slot.schedule` |
| Slot.serviceCategory | Slot.serviceCategory | Equivalent | R4B `Slot.serviceCategory` maps as Equivalent to R5 `Slot.serviceCategory` |
| Slot.serviceType | Slot.serviceType | SourceIsBroaderThanTarget | R4B `Slot.serviceType` maps as SourceIsBroaderThanTarget to R5 `Slot.serviceType` - serviceType has change due to type change: R4B serviceType CodeableConcept has no equivalent or mapped type in R5 serviceType |
| Slot.specialty | Slot.specialty | Equivalent | R4B `Slot.specialty` maps as Equivalent to R5 `Slot.specialty` |
| Slot.start | Slot.start | Equivalent | R4B `Slot.start` maps as Equivalent to R5 `Slot.start` |
| Slot.status | Slot.status | Equivalent | R4B `Slot.status` maps as Equivalent to R5 `Slot.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/slotstatus|4.3.0 and http://hl7.org/fhir/ValueSet/slotstatus|5.0.0 (Equivalent) |
| Slot.text | Slot.text | Equivalent | R4B `Slot.text` maps as Equivalent to R5 `Slot.text` |

