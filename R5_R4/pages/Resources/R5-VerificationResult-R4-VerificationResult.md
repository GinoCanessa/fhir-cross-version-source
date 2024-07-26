Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | VerificationResult |  | Describes validation requirements, source(s), status and dates for one or more elements. | 50 | 33 |
| Target | VerificationResult |  | Describes validation requirements, source(s), status and dates for one or more elements. | 50 | 33 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 46 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| VerificationResult | VerificationResult | Equivalent | R5 `VerificationResult` maps as Equivalent to R4 `VerificationResult` |
| VerificationResult.attestation | VerificationResult.attestation | Equivalent | R5 `VerificationResult.attestation` maps as Equivalent to R4 `VerificationResult.attestation` |
| VerificationResult.attestation.communicationMethod | VerificationResult.attestation.communicationMethod | Equivalent | R5 `VerificationResult.attestation.communicationMethod` maps as Equivalent to R4 `VerificationResult.attestation.communicationMethod` |
| VerificationResult.attestation.date | VerificationResult.attestation.date | Equivalent | R5 `VerificationResult.attestation.date` maps as Equivalent to R4 `VerificationResult.attestation.date` |
| VerificationResult.attestation.extension | VerificationResult.attestation.extension | SourceIsBroaderThanTarget | R5 `VerificationResult.attestation.extension` maps as SourceIsBroaderThanTarget to R4 `VerificationResult.attestation.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| VerificationResult.attestation.id | VerificationResult.attestation.id | Equivalent | R5 `VerificationResult.attestation.id` maps as Equivalent to R4 `VerificationResult.attestation.id` |
| VerificationResult.attestation.modifierExtension | VerificationResult.attestation.modifierExtension | SourceIsBroaderThanTarget | R5 `VerificationResult.attestation.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `VerificationResult.attestation.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| VerificationResult.attestation.onBehalfOf | VerificationResult.attestation.onBehalfOf | Equivalent | R5 `VerificationResult.attestation.onBehalfOf` maps as Equivalent to R4 `VerificationResult.attestation.onBehalfOf` |
| VerificationResult.attestation.proxyIdentityCertificate | VerificationResult.attestation.proxyIdentityCertificate | Equivalent | R5 `VerificationResult.attestation.proxyIdentityCertificate` maps as Equivalent to R4 `VerificationResult.attestation.proxyIdentityCertificate` |
| VerificationResult.attestation.proxySignature | VerificationResult.attestation.proxySignature | RelatedTo | R5 `VerificationResult.attestation.proxySignature` maps as RelatedTo to R4 `VerificationResult.attestation.proxySignature` - proxySignature has change due to type change: R5 `proxySignature` `Signature` maps as RelatedTo for R4 `proxySignature` |
| VerificationResult.attestation.sourceIdentityCertificate | VerificationResult.attestation.sourceIdentityCertificate | Equivalent | R5 `VerificationResult.attestation.sourceIdentityCertificate` maps as Equivalent to R4 `VerificationResult.attestation.sourceIdentityCertificate` |
| VerificationResult.attestation.sourceSignature | VerificationResult.attestation.sourceSignature | RelatedTo | R5 `VerificationResult.attestation.sourceSignature` maps as RelatedTo to R4 `VerificationResult.attestation.sourceSignature` - sourceSignature has change due to type change: R5 `sourceSignature` `Signature` maps as RelatedTo for R4 `sourceSignature` |
| VerificationResult.attestation.who | VerificationResult.attestation.who | Equivalent | R5 `VerificationResult.attestation.who` maps as Equivalent to R4 `VerificationResult.attestation.who` |
| VerificationResult.contained | VerificationResult.contained | Equivalent | R5 `VerificationResult.contained` maps as Equivalent to R4 `VerificationResult.contained` |
| VerificationResult.extension | VerificationResult.extension | SourceIsBroaderThanTarget | R5 `VerificationResult.extension` maps as SourceIsBroaderThanTarget to R4 `VerificationResult.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| VerificationResult.failureAction | VerificationResult.failureAction | Equivalent | R5 `VerificationResult.failureAction` maps as Equivalent to R4 `VerificationResult.failureAction` |
| VerificationResult.frequency | VerificationResult.frequency | Equivalent | R5 `VerificationResult.frequency` maps as Equivalent to R4 `VerificationResult.frequency` |
| VerificationResult.id | VerificationResult.id | Equivalent | R5 `VerificationResult.id` maps as Equivalent to R4 `VerificationResult.id` |
| VerificationResult.implicitRules | VerificationResult.implicitRules | Equivalent | R5 `VerificationResult.implicitRules` maps as Equivalent to R4 `VerificationResult.implicitRules` |
| VerificationResult.language | VerificationResult.language | RelatedTo | R5 `VerificationResult.language` maps as RelatedTo to R4 `VerificationResult.language` - language changed the binding strength from Required to Preferred |
| VerificationResult.lastPerformed | VerificationResult.lastPerformed | Equivalent | R5 `VerificationResult.lastPerformed` maps as Equivalent to R4 `VerificationResult.lastPerformed` |
| VerificationResult.meta | VerificationResult.meta | Equivalent | R5 `VerificationResult.meta` maps as Equivalent to R4 `VerificationResult.meta` |
| VerificationResult.modifierExtension | VerificationResult.modifierExtension | SourceIsBroaderThanTarget | R5 `VerificationResult.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `VerificationResult.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| VerificationResult.need | VerificationResult.need | Equivalent | R5 `VerificationResult.need` maps as Equivalent to R4 `VerificationResult.need` |
| VerificationResult.nextScheduled | VerificationResult.nextScheduled | Equivalent | R5 `VerificationResult.nextScheduled` maps as Equivalent to R4 `VerificationResult.nextScheduled` |
| VerificationResult.primarySource | VerificationResult.primarySource | Equivalent | R5 `VerificationResult.primarySource` maps as Equivalent to R4 `VerificationResult.primarySource` |
| VerificationResult.primarySource.canPushUpdates | VerificationResult.primarySource.canPushUpdates | Equivalent | R5 `VerificationResult.primarySource.canPushUpdates` maps as Equivalent to R4 `VerificationResult.primarySource.canPushUpdates` |
| VerificationResult.primarySource.communicationMethod | VerificationResult.primarySource.communicationMethod | Equivalent | R5 `VerificationResult.primarySource.communicationMethod` maps as Equivalent to R4 `VerificationResult.primarySource.communicationMethod` |
| VerificationResult.primarySource.extension | VerificationResult.primarySource.extension | SourceIsBroaderThanTarget | R5 `VerificationResult.primarySource.extension` maps as SourceIsBroaderThanTarget to R4 `VerificationResult.primarySource.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| VerificationResult.primarySource.id | VerificationResult.primarySource.id | Equivalent | R5 `VerificationResult.primarySource.id` maps as Equivalent to R4 `VerificationResult.primarySource.id` |
| VerificationResult.primarySource.modifierExtension | VerificationResult.primarySource.modifierExtension | SourceIsBroaderThanTarget | R5 `VerificationResult.primarySource.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `VerificationResult.primarySource.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| VerificationResult.primarySource.pushTypeAvailable | VerificationResult.primarySource.pushTypeAvailable | Equivalent | R5 `VerificationResult.primarySource.pushTypeAvailable` maps as Equivalent to R4 `VerificationResult.primarySource.pushTypeAvailable` |
| VerificationResult.primarySource.type | VerificationResult.primarySource.type | Equivalent | R5 `VerificationResult.primarySource.type` maps as Equivalent to R4 `VerificationResult.primarySource.type` |
| VerificationResult.primarySource.validationDate | VerificationResult.primarySource.validationDate | Equivalent | R5 `VerificationResult.primarySource.validationDate` maps as Equivalent to R4 `VerificationResult.primarySource.validationDate` |
| VerificationResult.primarySource.validationStatus | VerificationResult.primarySource.validationStatus | Equivalent | R5 `VerificationResult.primarySource.validationStatus` maps as Equivalent to R4 `VerificationResult.primarySource.validationStatus` |
| VerificationResult.primarySource.who | VerificationResult.primarySource.who | Equivalent | R5 `VerificationResult.primarySource.who` maps as Equivalent to R4 `VerificationResult.primarySource.who` |
| VerificationResult.status | VerificationResult.status | Equivalent | R5 `VerificationResult.status` maps as Equivalent to R4 `VerificationResult.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/verificationresult-status|5.0.0 and http://hl7.org/fhir/ValueSet/verificationresult-status|4.0.1 (Equivalent) |
| VerificationResult.statusDate | VerificationResult.statusDate | Equivalent | R5 `VerificationResult.statusDate` maps as Equivalent to R4 `VerificationResult.statusDate` |
| VerificationResult.target | VerificationResult.target | Equivalent | R5 `VerificationResult.target` maps as Equivalent to R4 `VerificationResult.target` |
| VerificationResult.targetLocation | VerificationResult.targetLocation | Equivalent | R5 `VerificationResult.targetLocation` maps as Equivalent to R4 `VerificationResult.targetLocation` |
| VerificationResult.text | VerificationResult.text | Equivalent | R5 `VerificationResult.text` maps as Equivalent to R4 `VerificationResult.text` |
| VerificationResult.validationProcess | VerificationResult.validationProcess | Equivalent | R5 `VerificationResult.validationProcess` maps as Equivalent to R4 `VerificationResult.validationProcess` |
| VerificationResult.validationType | VerificationResult.validationType | Equivalent | R5 `VerificationResult.validationType` maps as Equivalent to R4 `VerificationResult.validationType` |
| VerificationResult.validator | VerificationResult.validator | Equivalent | R5 `VerificationResult.validator` maps as Equivalent to R4 `VerificationResult.validator` |
| VerificationResult.validator.attestationSignature | VerificationResult.validator.attestationSignature | RelatedTo | R5 `VerificationResult.validator.attestationSignature` maps as RelatedTo to R4 `VerificationResult.validator.attestationSignature` - attestationSignature has change due to type change: R5 `attestationSignature` `Signature` maps as RelatedTo for R4 `attestationSignature` |
| VerificationResult.validator.extension | VerificationResult.validator.extension | SourceIsBroaderThanTarget | R5 `VerificationResult.validator.extension` maps as SourceIsBroaderThanTarget to R4 `VerificationResult.validator.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| VerificationResult.validator.id | VerificationResult.validator.id | Equivalent | R5 `VerificationResult.validator.id` maps as Equivalent to R4 `VerificationResult.validator.id` |
| VerificationResult.validator.identityCertificate | VerificationResult.validator.identityCertificate | Equivalent | R5 `VerificationResult.validator.identityCertificate` maps as Equivalent to R4 `VerificationResult.validator.identityCertificate` |
| VerificationResult.validator.modifierExtension | VerificationResult.validator.modifierExtension | SourceIsBroaderThanTarget | R5 `VerificationResult.validator.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `VerificationResult.validator.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| VerificationResult.validator.organization | VerificationResult.validator.organization | Equivalent | R5 `VerificationResult.validator.organization` maps as Equivalent to R4 `VerificationResult.validator.organization` |

