Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ServiceRequest |  | A record of a request for service such as diagnostic investigations, treatments, or operations to be performed. | 42 | 34 |
| Target | ServiceRequest |  | A record of a request for service such as diagnostic investigations, treatments, or operations to be performed. | 56 | 39 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 34 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ServiceRequest | ServiceRequest | Equivalent | R4B `ServiceRequest` maps as Equivalent to R5 `ServiceRequest` |
| ServiceRequest.asNeeded[x] | ServiceRequest.asNeeded[x] | Equivalent | R4B `ServiceRequest.asNeeded[x]` maps as Equivalent to R5 `ServiceRequest.asNeeded[x]` |
| ServiceRequest.authoredOn | ServiceRequest.authoredOn | Equivalent | R4B `ServiceRequest.authoredOn` maps as Equivalent to R5 `ServiceRequest.authoredOn` |
| ServiceRequest.basedOn | ServiceRequest.basedOn | Equivalent | R4B `ServiceRequest.basedOn` maps as Equivalent to R5 `ServiceRequest.basedOn` |
| ServiceRequest.bodySite | ServiceRequest.bodySite | Equivalent | R4B `ServiceRequest.bodySite` maps as Equivalent to R5 `ServiceRequest.bodySite` |
| ServiceRequest.category | ServiceRequest.category | Equivalent | R4B `ServiceRequest.category` maps as Equivalent to R5 `ServiceRequest.category` |
| ServiceRequest.code | ServiceRequest.code | SourceIsBroaderThanTarget | R4B `ServiceRequest.code` maps as SourceIsBroaderThanTarget to R5 `ServiceRequest.code` - code has change due to type change: R4B code CodeableConcept has no equivalent or mapped type in R5 code |
| ServiceRequest.contained | ServiceRequest.contained | Equivalent | R4B `ServiceRequest.contained` maps as Equivalent to R5 `ServiceRequest.contained` |
| ServiceRequest.doNotPerform | ServiceRequest.doNotPerform | Equivalent | R4B `ServiceRequest.doNotPerform` maps as Equivalent to R5 `ServiceRequest.doNotPerform` |
| ServiceRequest.encounter | ServiceRequest.encounter | Equivalent | R4B `ServiceRequest.encounter` maps as Equivalent to R5 `ServiceRequest.encounter` |
| ServiceRequest.extension | ServiceRequest.extension | RelatedTo | R4B `ServiceRequest.extension` maps as RelatedTo to R5 `ServiceRequest.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ServiceRequest.id | ServiceRequest.id | Equivalent | R4B `ServiceRequest.id` maps as Equivalent to R5 `ServiceRequest.id` |
| ServiceRequest.identifier | ServiceRequest.identifier | Equivalent | R4B `ServiceRequest.identifier` maps as Equivalent to R5 `ServiceRequest.identifier` |
| ServiceRequest.implicitRules | ServiceRequest.implicitRules | Equivalent | R4B `ServiceRequest.implicitRules` maps as Equivalent to R5 `ServiceRequest.implicitRules` |
| ServiceRequest.instantiatesCanonical | ServiceRequest.instantiatesCanonical | Equivalent | R4B `ServiceRequest.instantiatesCanonical` maps as Equivalent to R5 `ServiceRequest.instantiatesCanonical` |
| ServiceRequest.instantiatesUri | ServiceRequest.instantiatesUri | Equivalent | R4B `ServiceRequest.instantiatesUri` maps as Equivalent to R5 `ServiceRequest.instantiatesUri` |
| ServiceRequest.insurance | ServiceRequest.insurance | Equivalent | R4B `ServiceRequest.insurance` maps as Equivalent to R5 `ServiceRequest.insurance` |
| ServiceRequest.intent | ServiceRequest.intent | Equivalent | R4B `ServiceRequest.intent` maps as Equivalent to R5 `ServiceRequest.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-intent|4.3.0 and http://hl7.org/fhir/ValueSet/request-intent|5.0.0 (Equivalent) |
| ServiceRequest.language | ServiceRequest.language | RelatedTo | R4B `ServiceRequest.language` maps as RelatedTo to R5 `ServiceRequest.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ServiceRequest.locationCode | - | DoesNotExistInTarget | R4B `ServiceRequest.locationCode` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.locationReference | - | DoesNotExistInTarget | R4B `ServiceRequest.locationReference` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.meta | ServiceRequest.meta | Equivalent | R4B `ServiceRequest.meta` maps as Equivalent to R5 `ServiceRequest.meta` |
| ServiceRequest.modifierExtension | ServiceRequest.modifierExtension | RelatedTo | R4B `ServiceRequest.modifierExtension` maps as RelatedTo to R5 `ServiceRequest.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ServiceRequest.note | ServiceRequest.note | SourceIsNarrowerThanTarget | R4B `ServiceRequest.note` maps as SourceIsNarrowerThanTarget to R5 `ServiceRequest.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| ServiceRequest.occurrence[x] | ServiceRequest.occurrence[x] | Equivalent | R4B `ServiceRequest.occurrence[x]` maps as Equivalent to R5 `ServiceRequest.occurrence[x]` |
| ServiceRequest.orderDetail | ServiceRequest.orderDetail | RelatedTo | R4B `ServiceRequest.orderDetail` maps as RelatedTo to R5 `ServiceRequest.orderDetail` - orderDetail removed a binding requirement - Example http://hl7.org/fhir/ValueSet/servicerequest-orderdetail; orderDetail has change due to type change: R4B orderDetail CodeableConcept has no equivalent or mapped type in R5 orderDetail |
| ServiceRequest.patientInstruction | ServiceRequest.patientInstruction | RelatedTo | R4B `ServiceRequest.patientInstruction` maps as RelatedTo to R5 `ServiceRequest.patientInstruction` - patientInstruction changed from scalar to array (max cardinality from 1 to *); patientInstruction has change due to type change: R4B patientInstruction string has no equivalent or mapped type in R5 patientInstruction |
| ServiceRequest.performer | ServiceRequest.performer | Equivalent | R4B `ServiceRequest.performer` maps as Equivalent to R5 `ServiceRequest.performer` |
| ServiceRequest.performerType | ServiceRequest.performerType | Equivalent | R4B `ServiceRequest.performerType` maps as Equivalent to R5 `ServiceRequest.performerType` |
| ServiceRequest.priority | ServiceRequest.priority | Equivalent | R4B `ServiceRequest.priority` maps as Equivalent to R5 `ServiceRequest.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|4.3.0 and http://hl7.org/fhir/ValueSet/request-priority|5.0.0 (Equivalent) |
| ServiceRequest.quantity[x] | ServiceRequest.quantity[x] | SourceIsNarrowerThanTarget | R4B `ServiceRequest.quantity[x]` maps as SourceIsNarrowerThanTarget to R5 `ServiceRequest.quantity[x]` - quantity[x] has change due to type change: R4B `quantity[x]` `Ratio` maps as SourceIsNarrowerThanTarget for R5 `quantity[x]` |
| ServiceRequest.reasonCode | - | DoesNotExistInTarget | R4B `ServiceRequest.reasonCode` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.reasonReference | - | DoesNotExistInTarget | R4B `ServiceRequest.reasonReference` does not appear in the target and has no mapping for `ServiceRequest`. |
| ServiceRequest.relevantHistory | ServiceRequest.relevantHistory | Equivalent | R4B `ServiceRequest.relevantHistory` maps as Equivalent to R5 `ServiceRequest.relevantHistory` |
| ServiceRequest.replaces | ServiceRequest.replaces | Equivalent | R4B `ServiceRequest.replaces` maps as Equivalent to R5 `ServiceRequest.replaces` |
| ServiceRequest.requester | ServiceRequest.requester | Equivalent | R4B `ServiceRequest.requester` maps as Equivalent to R5 `ServiceRequest.requester` |
| ServiceRequest.requisition | ServiceRequest.requisition | Equivalent | R4B `ServiceRequest.requisition` maps as Equivalent to R5 `ServiceRequest.requisition` |
| ServiceRequest.specimen | ServiceRequest.specimen | Equivalent | R4B `ServiceRequest.specimen` maps as Equivalent to R5 `ServiceRequest.specimen` |
| ServiceRequest.status | ServiceRequest.status | Equivalent | R4B `ServiceRequest.status` maps as Equivalent to R5 `ServiceRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-status|4.3.0 and http://hl7.org/fhir/ValueSet/request-status|5.0.0 (Equivalent) |
| ServiceRequest.subject | ServiceRequest.subject | Equivalent | R4B `ServiceRequest.subject` maps as Equivalent to R5 `ServiceRequest.subject` |
| ServiceRequest.supportingInfo | ServiceRequest.supportingInfo | SourceIsBroaderThanTarget | R4B `ServiceRequest.supportingInfo` maps as SourceIsBroaderThanTarget to R5 `ServiceRequest.supportingInfo` - supportingInfo has change due to type change: R4B supportingInfo Reference has no equivalent or mapped type in R5 supportingInfo |
| ServiceRequest.text | ServiceRequest.text | Equivalent | R4B `ServiceRequest.text` maps as Equivalent to R5 `ServiceRequest.text` |

