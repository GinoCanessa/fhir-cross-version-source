Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Procedure |  | An action that is or was performed on or for a patient, practitioner, device, organization, or location. For example, this can be a physical intervention on a patient like an operation, or less invasive like long term services, counseling, or hypnotherapy.  This can be a quality or safety inspection for a location, organization, or device.  This can be an accreditation procedure on a practitioner for licensing. | 49 | 35 |
| Target | Procedure |  | An action that is or was performed on or for a patient. This can be a physical intervention like an operation, or less invasive like long term services, counseling, or hypnotherapy. | 48 | 34 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 8 |
Equivalent | 4 |
RelatedTo | 37 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Procedure | Procedure | Equivalent | R5 `Procedure` maps as Equivalent to R4B `Procedure` |
| Procedure.basedOn | Procedure.basedOn | Equivalent | R5 `Procedure.basedOn` maps as Equivalent to R4B `Procedure.basedOn` |
| Procedure.bodySite | Procedure.bodySite | Equivalent | R5 `Procedure.bodySite` maps as Equivalent to R4B `Procedure.bodySite` |
| Procedure.category | Procedure.category | RelatedTo | R5 `Procedure.category` maps as RelatedTo to R4B `Procedure.category` - category changed from array to scalar (max cardinality from * to 1) |
| Procedure.code | Procedure.code | Equivalent | R5 `Procedure.code` maps as Equivalent to R4B `Procedure.code` |
| Procedure.complication | Procedure.complication | SourceIsBroaderThanTarget | R5 `Procedure.complication` maps as SourceIsBroaderThanTarget to R4B `Procedure.complication` - complication has change due to type change: R5 complication CodeableReference has no equivalent or mapped type in R4B complication |
| Procedure.contained | Procedure.contained | Equivalent | R5 `Procedure.contained` maps as Equivalent to R4B `Procedure.contained` |
| Procedure.encounter | Procedure.encounter | Equivalent | R5 `Procedure.encounter` maps as Equivalent to R4B `Procedure.encounter` |
| Procedure.extension | Procedure.extension | SourceIsBroaderThanTarget | R5 `Procedure.extension` maps as SourceIsBroaderThanTarget to R4B `Procedure.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Procedure.focalDevice | Procedure.focalDevice | Equivalent | R5 `Procedure.focalDevice` maps as Equivalent to R4B `Procedure.focalDevice` |
| Procedure.focalDevice.action | Procedure.focalDevice.action | Equivalent | R5 `Procedure.focalDevice.action` maps as Equivalent to R4B `Procedure.focalDevice.action` |
| Procedure.focalDevice.extension | Procedure.focalDevice.extension | SourceIsBroaderThanTarget | R5 `Procedure.focalDevice.extension` maps as SourceIsBroaderThanTarget to R4B `Procedure.focalDevice.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Procedure.focalDevice.id | Procedure.focalDevice.id | Equivalent | R5 `Procedure.focalDevice.id` maps as Equivalent to R4B `Procedure.focalDevice.id` |
| Procedure.focalDevice.manipulated | Procedure.focalDevice.manipulated | Equivalent | R5 `Procedure.focalDevice.manipulated` maps as Equivalent to R4B `Procedure.focalDevice.manipulated` |
| Procedure.focalDevice.modifierExtension | Procedure.focalDevice.modifierExtension | SourceIsBroaderThanTarget | R5 `Procedure.focalDevice.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Procedure.focalDevice.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Procedure.focus | - | DoesNotExistInTarget | R5 `Procedure.focus` does not appear in the target and has no mapping for `Procedure`. |
| Procedure.followUp | Procedure.followUp | Equivalent | R5 `Procedure.followUp` maps as Equivalent to R4B `Procedure.followUp` |
| Procedure.id | Procedure.id | Equivalent | R5 `Procedure.id` maps as Equivalent to R4B `Procedure.id` |
| Procedure.identifier | Procedure.identifier | Equivalent | R5 `Procedure.identifier` maps as Equivalent to R4B `Procedure.identifier` |
| Procedure.implicitRules | Procedure.implicitRules | Equivalent | R5 `Procedure.implicitRules` maps as Equivalent to R4B `Procedure.implicitRules` |
| Procedure.instantiatesCanonical | Procedure.instantiatesCanonical | Equivalent | R5 `Procedure.instantiatesCanonical` maps as Equivalent to R4B `Procedure.instantiatesCanonical` |
| Procedure.instantiatesUri | Procedure.instantiatesUri | Equivalent | R5 `Procedure.instantiatesUri` maps as Equivalent to R4B `Procedure.instantiatesUri` |
| Procedure.language | Procedure.language | RelatedTo | R5 `Procedure.language` maps as RelatedTo to R4B `Procedure.language` - language changed the binding strength from Required to Preferred |
| Procedure.location | Procedure.location | Equivalent | R5 `Procedure.location` maps as Equivalent to R4B `Procedure.location` |
| Procedure.meta | Procedure.meta | Equivalent | R5 `Procedure.meta` maps as Equivalent to R4B `Procedure.meta` |
| Procedure.modifierExtension | Procedure.modifierExtension | SourceIsBroaderThanTarget | R5 `Procedure.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Procedure.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Procedure.note | Procedure.note | SourceIsBroaderThanTarget | R5 `Procedure.note` maps as SourceIsBroaderThanTarget to R4B `Procedure.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| Procedure.occurrence[x] | - | DoesNotExistInTarget | R5 `Procedure.occurrence[x]` does not appear in the target and has no mapping for `Procedure`. |
| Procedure.outcome | Procedure.outcome | Equivalent | R5 `Procedure.outcome` maps as Equivalent to R4B `Procedure.outcome` |
| Procedure.partOf | Procedure.partOf | Equivalent | R5 `Procedure.partOf` maps as Equivalent to R4B `Procedure.partOf` |
| Procedure.performer | Procedure.performer | Equivalent | R5 `Procedure.performer` maps as Equivalent to R4B `Procedure.performer` |
| Procedure.performer.actor | Procedure.performer.actor | SourceIsBroaderThanTarget | R5 `Procedure.performer.actor` maps as SourceIsBroaderThanTarget to R4B `Procedure.performer.actor` - actor has change due to type change: R5 `actor` `Reference` maps as SourceIsBroaderThanTarget for R4B `actor` |
| Procedure.performer.extension | Procedure.performer.extension | SourceIsBroaderThanTarget | R5 `Procedure.performer.extension` maps as SourceIsBroaderThanTarget to R4B `Procedure.performer.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Procedure.performer.function | Procedure.performer.function | Equivalent | R5 `Procedure.performer.function` maps as Equivalent to R4B `Procedure.performer.function` |
| Procedure.performer.id | Procedure.performer.id | Equivalent | R5 `Procedure.performer.id` maps as Equivalent to R4B `Procedure.performer.id` |
| Procedure.performer.modifierExtension | Procedure.performer.modifierExtension | SourceIsBroaderThanTarget | R5 `Procedure.performer.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Procedure.performer.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Procedure.performer.onBehalfOf | Procedure.performer.onBehalfOf | Equivalent | R5 `Procedure.performer.onBehalfOf` maps as Equivalent to R4B `Procedure.performer.onBehalfOf` |
| Procedure.performer.period | - | DoesNotExistInTarget | R5 `Procedure.performer.period` does not appear in the target and has no mapping for `Procedure`. |
| Procedure.reason | - | DoesNotExistInTarget | R5 `Procedure.reason` does not appear in the target and has no mapping for `Procedure`. |
| Procedure.recorded | - | DoesNotExistInTarget | R5 `Procedure.recorded` does not appear in the target and has no mapping for `Procedure`. |
| Procedure.recorder | Procedure.recorder | Equivalent | R5 `Procedure.recorder` maps as Equivalent to R4B `Procedure.recorder` |
| Procedure.report | Procedure.report | Equivalent | R5 `Procedure.report` maps as Equivalent to R4B `Procedure.report` |
| Procedure.reported[x] | - | DoesNotExistInTarget | R5 `Procedure.reported[x]` does not appear in the target and has no mapping for `Procedure`. |
| Procedure.status | Procedure.status | Equivalent | R5 `Procedure.status` maps as Equivalent to R4B `Procedure.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/event-status|5.0.0 and http://hl7.org/fhir/ValueSet/event-status|4.3.0 (Equivalent) |
| Procedure.statusReason | Procedure.statusReason | Equivalent | R5 `Procedure.statusReason` maps as Equivalent to R4B `Procedure.statusReason` |
| Procedure.subject | Procedure.subject | SourceIsBroaderThanTarget | R5 `Procedure.subject` maps as SourceIsBroaderThanTarget to R4B `Procedure.subject` - subject has change due to type change: R5 `subject` `Reference` maps as SourceIsBroaderThanTarget for R4B `subject` |
| Procedure.supportingInfo | - | DoesNotExistInTarget | R5 `Procedure.supportingInfo` does not appear in the target and has no mapping for `Procedure`. |
| Procedure.text | Procedure.text | Equivalent | R5 `Procedure.text` maps as Equivalent to R4B `Procedure.text` |
| Procedure.used | - | DoesNotExistInTarget | R5 `Procedure.used` does not appear in the target and has no mapping for `Procedure`. |

