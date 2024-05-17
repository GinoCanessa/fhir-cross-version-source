Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Procedure |  | An action that is or was performed on or for a patient. This can be a physical intervention like an operation, or less invasive like long term services, counseling, or hypnotherapy. | 48 | 34 |
| Target | Procedure |  | An action that is or was performed on or for a patient, practitioner, device, organization, or location. For example, this can be a physical intervention on a patient like an operation, or less invasive like long term services, counseling, or hypnotherapy.  This can be a quality or safety inspection for a location, organization, or device.  This can be an accreditation procedure on a practitioner for licensing. | 49 | 35 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 7 |
Equivalent | 4 |
RelatedTo | 37 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Procedure | Procedure | Equivalent | R4B `Procedure` maps as Equivalent to R5 `Procedure` |
| Procedure.asserter | - | DoesNotExistInTarget | R4B `Procedure.asserter` does not appear in the target and has no mapping for `Procedure`. |
| Procedure.basedOn | Procedure.basedOn | Equivalent | R4B `Procedure.basedOn` maps as Equivalent to R5 `Procedure.basedOn` |
| Procedure.bodySite | Procedure.bodySite | Equivalent | R4B `Procedure.bodySite` maps as Equivalent to R5 `Procedure.bodySite` |
| Procedure.category | Procedure.category | RelatedTo | R4B `Procedure.category` maps as RelatedTo to R5 `Procedure.category` - category changed from scalar to array (max cardinality from 1 to *) |
| Procedure.code | Procedure.code | Equivalent | R4B `Procedure.code` maps as Equivalent to R5 `Procedure.code` |
| Procedure.complication | Procedure.complication | SourceIsBroaderThanTarget | R4B `Procedure.complication` maps as SourceIsBroaderThanTarget to R5 `Procedure.complication` - complication has change due to type change: R4B complication CodeableConcept has no equivalent or mapped type in R5 complication |
| Procedure.complicationDetail | - | DoesNotExistInTarget | R4B `Procedure.complicationDetail` does not appear in the target and has no mapping for `Procedure`. |
| Procedure.contained | Procedure.contained | Equivalent | R4B `Procedure.contained` maps as Equivalent to R5 `Procedure.contained` |
| Procedure.encounter | Procedure.encounter | Equivalent | R4B `Procedure.encounter` maps as Equivalent to R5 `Procedure.encounter` |
| Procedure.extension | Procedure.extension | RelatedTo | R4B `Procedure.extension` maps as RelatedTo to R5 `Procedure.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Procedure.focalDevice | Procedure.focalDevice | Equivalent | R4B `Procedure.focalDevice` maps as Equivalent to R5 `Procedure.focalDevice` |
| Procedure.focalDevice.action | Procedure.focalDevice.action | Equivalent | R4B `Procedure.focalDevice.action` maps as Equivalent to R5 `Procedure.focalDevice.action` |
| Procedure.focalDevice.extension | Procedure.focalDevice.extension | RelatedTo | R4B `Procedure.focalDevice.extension` maps as RelatedTo to R5 `Procedure.focalDevice.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Procedure.focalDevice.id | Procedure.focalDevice.id | Equivalent | R4B `Procedure.focalDevice.id` maps as Equivalent to R5 `Procedure.focalDevice.id` |
| Procedure.focalDevice.manipulated | Procedure.focalDevice.manipulated | Equivalent | R4B `Procedure.focalDevice.manipulated` maps as Equivalent to R5 `Procedure.focalDevice.manipulated` |
| Procedure.focalDevice.modifierExtension | Procedure.focalDevice.modifierExtension | RelatedTo | R4B `Procedure.focalDevice.modifierExtension` maps as RelatedTo to R5 `Procedure.focalDevice.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Procedure.followUp | Procedure.followUp | Equivalent | R4B `Procedure.followUp` maps as Equivalent to R5 `Procedure.followUp` |
| Procedure.id | Procedure.id | Equivalent | R4B `Procedure.id` maps as Equivalent to R5 `Procedure.id` |
| Procedure.identifier | Procedure.identifier | Equivalent | R4B `Procedure.identifier` maps as Equivalent to R5 `Procedure.identifier` |
| Procedure.implicitRules | Procedure.implicitRules | Equivalent | R4B `Procedure.implicitRules` maps as Equivalent to R5 `Procedure.implicitRules` |
| Procedure.instantiatesCanonical | Procedure.instantiatesCanonical | Equivalent | R4B `Procedure.instantiatesCanonical` maps as Equivalent to R5 `Procedure.instantiatesCanonical` |
| Procedure.instantiatesUri | Procedure.instantiatesUri | Equivalent | R4B `Procedure.instantiatesUri` maps as Equivalent to R5 `Procedure.instantiatesUri` |
| Procedure.language | Procedure.language | RelatedTo | R4B `Procedure.language` maps as RelatedTo to R5 `Procedure.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Procedure.location | Procedure.location | Equivalent | R4B `Procedure.location` maps as Equivalent to R5 `Procedure.location` |
| Procedure.meta | Procedure.meta | Equivalent | R4B `Procedure.meta` maps as Equivalent to R5 `Procedure.meta` |
| Procedure.modifierExtension | Procedure.modifierExtension | RelatedTo | R4B `Procedure.modifierExtension` maps as RelatedTo to R5 `Procedure.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Procedure.note | Procedure.note | SourceIsNarrowerThanTarget | R4B `Procedure.note` maps as SourceIsNarrowerThanTarget to R5 `Procedure.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Procedure.outcome | Procedure.outcome | Equivalent | R4B `Procedure.outcome` maps as Equivalent to R5 `Procedure.outcome` |
| Procedure.partOf | Procedure.partOf | Equivalent | R4B `Procedure.partOf` maps as Equivalent to R5 `Procedure.partOf` |
| Procedure.performed[x] | - | DoesNotExistInTarget | R4B `Procedure.performed[x]` does not appear in the target and has no mapping for `Procedure`. |
| Procedure.performer | Procedure.performer | Equivalent | R4B `Procedure.performer` maps as Equivalent to R5 `Procedure.performer` |
| Procedure.performer.actor | Procedure.performer.actor | SourceIsNarrowerThanTarget | R4B `Procedure.performer.actor` maps as SourceIsNarrowerThanTarget to R5 `Procedure.performer.actor` - actor has change due to type change: R4B `actor` `Reference` maps as SourceIsNarrowerThanTarget for R5 `actor` |
| Procedure.performer.extension | Procedure.performer.extension | RelatedTo | R4B `Procedure.performer.extension` maps as RelatedTo to R5 `Procedure.performer.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Procedure.performer.function | Procedure.performer.function | Equivalent | R4B `Procedure.performer.function` maps as Equivalent to R5 `Procedure.performer.function` |
| Procedure.performer.id | Procedure.performer.id | Equivalent | R4B `Procedure.performer.id` maps as Equivalent to R5 `Procedure.performer.id` |
| Procedure.performer.modifierExtension | Procedure.performer.modifierExtension | RelatedTo | R4B `Procedure.performer.modifierExtension` maps as RelatedTo to R5 `Procedure.performer.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Procedure.performer.onBehalfOf | Procedure.performer.onBehalfOf | Equivalent | R4B `Procedure.performer.onBehalfOf` maps as Equivalent to R5 `Procedure.performer.onBehalfOf` |
| Procedure.reasonCode | - | DoesNotExistInTarget | R4B `Procedure.reasonCode` does not appear in the target and has no mapping for `Procedure`. |
| Procedure.reasonReference | - | DoesNotExistInTarget | R4B `Procedure.reasonReference` does not appear in the target and has no mapping for `Procedure`. |
| Procedure.recorder | Procedure.recorder | Equivalent | R4B `Procedure.recorder` maps as Equivalent to R5 `Procedure.recorder` |
| Procedure.report | Procedure.report | Equivalent | R4B `Procedure.report` maps as Equivalent to R5 `Procedure.report` |
| Procedure.status | Procedure.status | Equivalent | R4B `Procedure.status` maps as Equivalent to R5 `Procedure.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/event-status|4.3.0 and http://hl7.org/fhir/ValueSet/event-status|5.0.0 (Equivalent) |
| Procedure.statusReason | Procedure.statusReason | Equivalent | R4B `Procedure.statusReason` maps as Equivalent to R5 `Procedure.statusReason` |
| Procedure.subject | Procedure.subject | SourceIsNarrowerThanTarget | R4B `Procedure.subject` maps as SourceIsNarrowerThanTarget to R5 `Procedure.subject` - subject has change due to type change: R4B `subject` `Reference` maps as SourceIsNarrowerThanTarget for R5 `subject` |
| Procedure.text | Procedure.text | Equivalent | R4B `Procedure.text` maps as Equivalent to R5 `Procedure.text` |
| Procedure.usedCode | - | DoesNotExistInTarget | R4B `Procedure.usedCode` does not appear in the target and has no mapping for `Procedure`. |
| Procedure.usedReference | - | DoesNotExistInTarget | R4B `Procedure.usedReference` does not appear in the target and has no mapping for `Procedure`. |

