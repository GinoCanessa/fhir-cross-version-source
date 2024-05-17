Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ServiceRequest |  | A record of a request for service such as diagnostic investigations, treatments, or operations to be performed. | 56 | 39 |
| Target | ServiceRequest |  | A record of a request for service such as diagnostic investigations, treatments, or operations to be performed. | 42 | 34 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 18 |
Equivalent | 4 |
RelatedTo | 34 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ServiceRequest | ServiceRequest | Equivalent | R5 `ServiceRequest` maps as Equivalent to R4B `ServiceRequest` |
| ServiceRequest.asNeeded[x] | ServiceRequest.asNeeded[x] | Equivalent | R5 `ServiceRequest.asNeeded[x]` maps as Equivalent to R4B `ServiceRequest.asNeeded[x]` |
| ServiceRequest.authoredOn | ServiceRequest.authoredOn | Equivalent | R5 `ServiceRequest.authoredOn` maps as Equivalent to R4B `ServiceRequest.authoredOn` |
| ServiceRequest.basedOn | ServiceRequest.basedOn | Equivalent | R5 `ServiceRequest.basedOn` maps as Equivalent to R4B `ServiceRequest.basedOn` |
| ServiceRequest.bodySite | ServiceRequest.bodySite | Equivalent | R5 `ServiceRequest.bodySite` maps as Equivalent to R4B `ServiceRequest.bodySite` |
| ServiceRequest.bodyStructure | - | DoesNotExistInTarget | R5 `ServiceRequest.bodyStructure` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.category | ServiceRequest.category | Equivalent | R5 `ServiceRequest.category` maps as Equivalent to R4B `ServiceRequest.category` |
| ServiceRequest.code | ServiceRequest.code | SourceIsBroaderThanTarget | R5 `ServiceRequest.code` maps as SourceIsBroaderThanTarget to R4B `ServiceRequest.code` - code has change due to type change: R5 code CodeableReference has no equivalent or mapped type in R4B code |
| ServiceRequest.contained | ServiceRequest.contained | Equivalent | R5 `ServiceRequest.contained` maps as Equivalent to R4B `ServiceRequest.contained` |
| ServiceRequest.doNotPerform | ServiceRequest.doNotPerform | Equivalent | R5 `ServiceRequest.doNotPerform` maps as Equivalent to R4B `ServiceRequest.doNotPerform` |
| ServiceRequest.encounter | ServiceRequest.encounter | Equivalent | R5 `ServiceRequest.encounter` maps as Equivalent to R4B `ServiceRequest.encounter` |
| ServiceRequest.extension | ServiceRequest.extension | SourceIsBroaderThanTarget | R5 `ServiceRequest.extension` maps as SourceIsBroaderThanTarget to R4B `ServiceRequest.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| ServiceRequest.focus | - | DoesNotExistInTarget | R5 `ServiceRequest.focus` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.id | ServiceRequest.id | Equivalent | R5 `ServiceRequest.id` maps as Equivalent to R4B `ServiceRequest.id` |
| ServiceRequest.identifier | ServiceRequest.identifier | Equivalent | R5 `ServiceRequest.identifier` maps as Equivalent to R4B `ServiceRequest.identifier` |
| ServiceRequest.implicitRules | ServiceRequest.implicitRules | Equivalent | R5 `ServiceRequest.implicitRules` maps as Equivalent to R4B `ServiceRequest.implicitRules` |
| ServiceRequest.instantiatesCanonical | ServiceRequest.instantiatesCanonical | Equivalent | R5 `ServiceRequest.instantiatesCanonical` maps as Equivalent to R4B `ServiceRequest.instantiatesCanonical` |
| ServiceRequest.instantiatesUri | ServiceRequest.instantiatesUri | Equivalent | R5 `ServiceRequest.instantiatesUri` maps as Equivalent to R4B `ServiceRequest.instantiatesUri` |
| ServiceRequest.insurance | ServiceRequest.insurance | Equivalent | R5 `ServiceRequest.insurance` maps as Equivalent to R4B `ServiceRequest.insurance` |
| ServiceRequest.intent | ServiceRequest.intent | Equivalent | R5 `ServiceRequest.intent` maps as Equivalent to R4B `ServiceRequest.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-intent|5.0.0 and http://hl7.org/fhir/ValueSet/request-intent|4.3.0 (Equivalent) |
| ServiceRequest.language | ServiceRequest.language | RelatedTo | R5 `ServiceRequest.language` maps as RelatedTo to R4B `ServiceRequest.language` - language changed the binding strength from Required to Preferred |
| ServiceRequest.location | - | DoesNotExistInTarget | R5 `ServiceRequest.location` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.meta | ServiceRequest.meta | Equivalent | R5 `ServiceRequest.meta` maps as Equivalent to R4B `ServiceRequest.meta` |
| ServiceRequest.modifierExtension | ServiceRequest.modifierExtension | SourceIsBroaderThanTarget | R5 `ServiceRequest.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `ServiceRequest.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| ServiceRequest.note | ServiceRequest.note | SourceIsBroaderThanTarget | R5 `ServiceRequest.note` maps as SourceIsBroaderThanTarget to R4B `ServiceRequest.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| ServiceRequest.occurrence[x] | ServiceRequest.occurrence[x] | Equivalent | R5 `ServiceRequest.occurrence[x]` maps as Equivalent to R4B `ServiceRequest.occurrence[x]` |
| ServiceRequest.orderDetail | ServiceRequest.orderDetail | RelatedTo | R5 `ServiceRequest.orderDetail` maps as RelatedTo to R4B `ServiceRequest.orderDetail` - orderDetail added a binding requirement - Example http://hl7.org/fhir/ValueSet/servicerequest-orderdetail; orderDetail has change due to type change: R5 orderDetail BackboneElement has no equivalent or mapped type in R4B orderDetail |
| ServiceRequest.orderDetail.extension | - | DoesNotExistInTarget | R5 `ServiceRequest.orderDetail.extension` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.orderDetail.id | - | DoesNotExistInTarget | R5 `ServiceRequest.orderDetail.id` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.orderDetail.modifierExtension | - | DoesNotExistInTarget | R5 `ServiceRequest.orderDetail.modifierExtension` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.orderDetail.parameter | - | DoesNotExistInTarget | R5 `ServiceRequest.orderDetail.parameter` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.orderDetail.parameter.code | - | DoesNotExistInTarget | R5 `ServiceRequest.orderDetail.parameter.code` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.orderDetail.parameter.extension | - | DoesNotExistInTarget | R5 `ServiceRequest.orderDetail.parameter.extension` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.orderDetail.parameter.id | - | DoesNotExistInTarget | R5 `ServiceRequest.orderDetail.parameter.id` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.orderDetail.parameter.modifierExtension | - | DoesNotExistInTarget | R5 `ServiceRequest.orderDetail.parameter.modifierExtension` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.orderDetail.parameter.value[x] | - | DoesNotExistInTarget | R5 `ServiceRequest.orderDetail.parameter.value[x]` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.orderDetail.parameterFocus | - | DoesNotExistInTarget | R5 `ServiceRequest.orderDetail.parameterFocus` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.patientInstruction | ServiceRequest.patientInstruction | RelatedTo | R5 `ServiceRequest.patientInstruction` maps as RelatedTo to R4B `ServiceRequest.patientInstruction` - patientInstruction changed from array to scalar (max cardinality from * to 1); patientInstruction has change due to type change: R5 patientInstruction BackboneElement has no equivalent or mapped type in R4B patientInstruction |
| ServiceRequest.patientInstruction.extension | - | DoesNotExistInTarget | R5 `ServiceRequest.patientInstruction.extension` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.patientInstruction.id | - | DoesNotExistInTarget | R5 `ServiceRequest.patientInstruction.id` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.patientInstruction.instruction[x] | - | DoesNotExistInTarget | R5 `ServiceRequest.patientInstruction.instruction[x]` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.patientInstruction.modifierExtension | - | DoesNotExistInTarget | R5 `ServiceRequest.patientInstruction.modifierExtension` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.performer | ServiceRequest.performer | Equivalent | R5 `ServiceRequest.performer` maps as Equivalent to R4B `ServiceRequest.performer` |
| ServiceRequest.performerType | ServiceRequest.performerType | Equivalent | R5 `ServiceRequest.performerType` maps as Equivalent to R4B `ServiceRequest.performerType` |
| ServiceRequest.priority | ServiceRequest.priority | Equivalent | R5 `ServiceRequest.priority` maps as Equivalent to R4B `ServiceRequest.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|5.0.0 and http://hl7.org/fhir/ValueSet/request-priority|4.3.0 (Equivalent) |
| ServiceRequest.quantity[x] | ServiceRequest.quantity[x] | SourceIsBroaderThanTarget | R5 `ServiceRequest.quantity[x]` maps as SourceIsBroaderThanTarget to R4B `ServiceRequest.quantity[x]` - quantity[x] has change due to type change: R5 `quantity[x]` `Ratio` maps as SourceIsBroaderThanTarget for R4B `quantity[x]` |
| ServiceRequest.reason | - | DoesNotExistInTarget | R5 `ServiceRequest.reason` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.relevantHistory | ServiceRequest.relevantHistory | Equivalent | R5 `ServiceRequest.relevantHistory` maps as Equivalent to R4B `ServiceRequest.relevantHistory` |
| ServiceRequest.replaces | ServiceRequest.replaces | Equivalent | R5 `ServiceRequest.replaces` maps as Equivalent to R4B `ServiceRequest.replaces` |
| ServiceRequest.requester | ServiceRequest.requester | Equivalent | R5 `ServiceRequest.requester` maps as Equivalent to R4B `ServiceRequest.requester` |
| ServiceRequest.requisition | ServiceRequest.requisition | Equivalent | R5 `ServiceRequest.requisition` maps as Equivalent to R4B `ServiceRequest.requisition` |
| ServiceRequest.specimen | ServiceRequest.specimen | Equivalent | R5 `ServiceRequest.specimen` maps as Equivalent to R4B `ServiceRequest.specimen` |
| ServiceRequest.status | ServiceRequest.status | Equivalent | R5 `ServiceRequest.status` maps as Equivalent to R4B `ServiceRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-status|5.0.0 and http://hl7.org/fhir/ValueSet/request-status|4.3.0 (Equivalent) |
| ServiceRequest.subject | ServiceRequest.subject | Equivalent | R5 `ServiceRequest.subject` maps as Equivalent to R4B `ServiceRequest.subject` |
| ServiceRequest.supportingInfo | ServiceRequest.supportingInfo | SourceIsBroaderThanTarget | R5 `ServiceRequest.supportingInfo` maps as SourceIsBroaderThanTarget to R4B `ServiceRequest.supportingInfo` - supportingInfo has change due to type change: R5 supportingInfo CodeableReference has no equivalent or mapped type in R4B supportingInfo |
| ServiceRequest.text | ServiceRequest.text | Equivalent | R5 `ServiceRequest.text` maps as Equivalent to R4B `ServiceRequest.text` |

