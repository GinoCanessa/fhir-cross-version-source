Comparison of 
Generated at Monday, April 14, 2025 6:17:50 PM

### VerificationResult

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | VerificationResult |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/VerificationResult` |
| Version | 5.0.0 |
| Description | Describes validation requirements, source(s), status and dates for one or more elements. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2406` |
| Database Snapshot Count | `50` |
| Database Differential Count | `33` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `VerificationResult` | `VerificationResult` | `VerificationResult` | VerificationResult | Describes validation requirements, source(s), status and dates for one or more elements | 0..* | VerificationResult |  |  |
| `VerificationResult.attestation` | `VerificationResult.attestation` | `attestation` | VerificationResult.attestation | Information about the entity attesting to information | 0..1 | BackboneElement |  |  |
| `VerificationResult.attestation.communicationMethod` | `VerificationResult.attestation.communicationMethod` | `communicationMethod` | VerificationResult.attestation.communicationMethod | The method by which attested information was submitted/retrieved | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/verificationresult-communication-method` |
| `VerificationResult.attestation.date` | `VerificationResult.attestation.date` | `date` | VerificationResult.attestation.date | The date the information was attested to | 0..1 | date |  |  |
| `VerificationResult.attestation.extension` | `VerificationResult.attestation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `VerificationResult.attestation.id` | `VerificationResult.attestation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `VerificationResult.attestation.modifierExtension` | `VerificationResult.attestation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `VerificationResult.attestation.onBehalfOf` | `VerificationResult.attestation.onBehalfOf` | `onBehalfOf` | VerificationResult.attestation.onBehalfOf | When the who is asserting on behalf of another (organization or individual) | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `VerificationResult.attestation.proxyIdentityCertificate` | `VerificationResult.attestation.proxyIdentityCertificate` | `proxyIdentityCertificate` | VerificationResult.attestation.proxyIdentityCertificate | A digital identity certificate associated with the proxy entity submitting attested information on behalf of the attestation source | 0..1 | string |  |  |
| `VerificationResult.attestation.proxySignature` | `VerificationResult.attestation.proxySignature` | `proxySignature` | VerificationResult.attestation.proxySignature | Proxy signature (digital or image) | 0..1 | Signature |  |  |
| `VerificationResult.attestation.sourceIdentityCertificate` | `VerificationResult.attestation.sourceIdentityCertificate` | `sourceIdentityCertificate` | VerificationResult.attestation.sourceIdentityCertificate | A digital identity certificate associated with the attestation source | 0..1 | string |  |  |
| `VerificationResult.attestation.sourceSignature` | `VerificationResult.attestation.sourceSignature` | `sourceSignature` | VerificationResult.attestation.sourceSignature | Attester signature (digital or image) | 0..1 | Signature |  |  |
| `VerificationResult.attestation.who` | `VerificationResult.attestation.who` | `who` | VerificationResult.attestation.who | The individual or organization attesting to information | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `VerificationResult.contained` | `VerificationResult.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `VerificationResult.extension` | `VerificationResult.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `VerificationResult.failureAction` | `VerificationResult.failureAction` | `failureAction` | VerificationResult.failureAction | fatal \| warn \| rec-only \| none | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/verificationresult-failure-action` |
| `VerificationResult.frequency` | `VerificationResult.frequency` | `frequency` | VerificationResult.frequency | Frequency of revalidation | 0..1 | Timing |  |  |
| `VerificationResult.id` | `VerificationResult.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `VerificationResult.implicitRules` | `VerificationResult.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `VerificationResult.language` | `VerificationResult.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `VerificationResult.lastPerformed` | `VerificationResult.lastPerformed` | `lastPerformed` | VerificationResult.lastPerformed | The date/time validation was last completed (including failed validations) | 0..1 | dateTime |  |  |
| `VerificationResult.meta` | `VerificationResult.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `VerificationResult.modifierExtension` | `VerificationResult.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `VerificationResult.need` | `VerificationResult.need` | `need` | VerificationResult.need | none \| initial \| periodic | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/verificationresult-need` |
| `VerificationResult.nextScheduled` | `VerificationResult.nextScheduled` | `nextScheduled` | VerificationResult.nextScheduled | The date when target is next validated, if appropriate | 0..1 | date |  |  |
| `VerificationResult.primarySource` | `VerificationResult.primarySource` | `primarySource` | VerificationResult.primarySource | Information about the primary source(s) involved in validation | 0..* | BackboneElement |  |  |
| `VerificationResult.primarySource.canPushUpdates` | `VerificationResult.primarySource.canPushUpdates` | `canPushUpdates` | VerificationResult.primarySource.canPushUpdates | yes \| no \| undetermined | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/verificationresult-can-push-updates` |
| `VerificationResult.primarySource.communicationMethod` | `VerificationResult.primarySource.communicationMethod` | `communicationMethod` | VerificationResult.primarySource.communicationMethod | Method for exchanging information with the primary source | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/verificationresult-communication-method` |
| `VerificationResult.primarySource.extension` | `VerificationResult.primarySource.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `VerificationResult.primarySource.id` | `VerificationResult.primarySource.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `VerificationResult.primarySource.modifierExtension` | `VerificationResult.primarySource.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `VerificationResult.primarySource.pushTypeAvailable` | `VerificationResult.primarySource.pushTypeAvailable` | `pushTypeAvailable` | VerificationResult.primarySource.pushTypeAvailable | specific \| any \| source | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/verificationresult-push-type-available` |
| `VerificationResult.primarySource.type` | `VerificationResult.primarySource.type` | `type` | VerificationResult.primarySource.type | Type of primary source (License Board; Primary Education; Continuing Education; Postal Service; Relationship owner; Registration Authority; legal source; issuing source; authoritative source) | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/verificationresult-primary-source-type` |
| `VerificationResult.primarySource.validationDate` | `VerificationResult.primarySource.validationDate` | `validationDate` | VerificationResult.primarySource.validationDate | When the target was validated against the primary source | 0..1 | dateTime |  |  |
| `VerificationResult.primarySource.validationStatus` | `VerificationResult.primarySource.validationStatus` | `validationStatus` | VerificationResult.primarySource.validationStatus | successful \| failed \| unknown | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/verificationresult-validation-status` |
| `VerificationResult.primarySource.who` | `VerificationResult.primarySource.who` | `who` | VerificationResult.primarySource.who | Reference to the primary source | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `VerificationResult.status` | `VerificationResult.status` | `status` | VerificationResult.status | attested \| validated \| in-process \| req-revalid \| val-fail \| reval-fail \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/verificationresult-status|5.0.0` |
| `VerificationResult.statusDate` | `VerificationResult.statusDate` | `statusDate` | VerificationResult.statusDate | When the validation status was updated | 0..1 | dateTime |  |  |
| `VerificationResult.target` | `VerificationResult.target` | `target` | VerificationResult.target | A resource that was validated | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `VerificationResult.targetLocation` | `VerificationResult.targetLocation` | `targetLocation` | VerificationResult.targetLocation | The fhirpath location(s) within the resource that was validated | 0..* | string |  |  |
| `VerificationResult.text` | `VerificationResult.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `VerificationResult.validationProcess` | `VerificationResult.validationProcess` | `validationProcess` | VerificationResult.validationProcess | The primary process by which the target is validated (edit check; value set; primary source; multiple sources; standalone; in context) | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/verificationresult-validation-process` |
| `VerificationResult.validationType` | `VerificationResult.validationType` | `validationType` | VerificationResult.validationType | nothing \| primary \| multiple | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/verificationresult-validation-type` |
| `VerificationResult.validator` | `VerificationResult.validator` | `validator` | VerificationResult.validator | Information about the entity validating information | 0..* | BackboneElement |  |  |
| `VerificationResult.validator.attestationSignature` | `VerificationResult.validator.attestationSignature` | `attestationSignature` | VerificationResult.validator.attestationSignature | Validator signature (digital or image) | 0..1 | Signature |  |  |
| `VerificationResult.validator.extension` | `VerificationResult.validator.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `VerificationResult.validator.id` | `VerificationResult.validator.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `VerificationResult.validator.identityCertificate` | `VerificationResult.validator.identityCertificate` | `identityCertificate` | VerificationResult.validator.identityCertificate | A digital identity certificate associated with the validator | 0..1 | string |  |  |
| `VerificationResult.validator.modifierExtension` | `VerificationResult.validator.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `VerificationResult.validator.organization` | `VerificationResult.validator.organization` | `organization` | VerificationResult.validator.organization | Reference to the organization validating information | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [VerificationResult](/docs/R4/Resources/VerificationResult.md)<br/> `http://hl7.org/fhir/StructureDefinition/VerificationResult\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1643`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1644`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [VerificationResult](/docs/R4B/Resources/VerificationResult.md)<br/> `http://hl7.org/fhir/StructureDefinition/VerificationResult\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1058`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1287`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [VerificationResult](/docs/R5/Resources/VerificationResult.md)<br/> `http://hl7.org/fhir/StructureDefinition/VerificationResult\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition VerificationResult from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 VerificationResult](/docs/R4/Resources/VerificationResult.md)| Relationship | [R4B VerificationResult](/docs/R4B/Resources/VerificationResult.md)| Relationship | R5 VerificationResult
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `VerificationResult`| _Equivalent_<br/>(34969/34970)| `VerificationResult`| _Equivalent_<br/>(49387/49388)| **`VerificationResult`**
| | | | | `VerificationResult.id`| _Equivalent_<br/>(34971/34972)| `VerificationResult.id`| _Equivalent_<br/>(49389/49390)| **`VerificationResult.id`**
| | | | | `VerificationResult.meta`| _Equivalent_<br/>(34973/34974)| `VerificationResult.meta`| _Equivalent_<br/>(49391/49392)| **`VerificationResult.meta`**
| | | | | `VerificationResult.implicitRules`| _Equivalent_<br/>(34975/34976)| `VerificationResult.implicitRules`| _Equivalent_<br/>(49393/49394)| **`VerificationResult.implicitRules`**
| | | | | `VerificationResult.language`| _Equivalent_<br/>(34977/34978)| `VerificationResult.language`| _Equivalent_<br/>(49395/49396)| **`VerificationResult.language`**
| | | | | `VerificationResult.text`| _Equivalent_<br/>(34979/34980)| `VerificationResult.text`| _Equivalent_<br/>(49397/49398)| **`VerificationResult.text`**
| | | | | `VerificationResult.contained`| _Equivalent_<br/>(34981/34982)| `VerificationResult.contained`| _Equivalent_<br/>(49399/49400)| **`VerificationResult.contained`**
| | | | | `VerificationResult.extension`| _Equivalent_<br/>(34983/34984)| `VerificationResult.extension`| _Equivalent_<br/>(49401/49402)| **`VerificationResult.extension`**
| | | | | `VerificationResult.modifierExtension`| _Equivalent_<br/>(34985/34986)| `VerificationResult.modifierExtension`| _Equivalent_<br/>(49403/49404)| **`VerificationResult.modifierExtension`**
| | | | | `VerificationResult.target`| _Equivalent_<br/>(34987/34988)| `VerificationResult.target`| _Equivalent_<br/>(49405/49406)| **`VerificationResult.target`**
| | | | | `VerificationResult.targetLocation`| _Equivalent_<br/>(34989/34990)| `VerificationResult.targetLocation`| _Equivalent_<br/>(49407/49408)| **`VerificationResult.targetLocation`**
| | | | | `VerificationResult.need`| _Equivalent_<br/>(34991/34992)| `VerificationResult.need`| _Equivalent_<br/>(49409/49410)| **`VerificationResult.need`**
| | | | | `VerificationResult.status`| _Equivalent_<br/>(34993/34994)| `VerificationResult.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(49411)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(49412)| **`VerificationResult.status`**
| | | | | `VerificationResult.statusDate`| _Equivalent_<br/>(34995/34996)| `VerificationResult.statusDate`| _Equivalent_<br/>(49413/49414)| **`VerificationResult.statusDate`**
| | | | | `VerificationResult.validationType`| _Equivalent_<br/>(34997/34998)| `VerificationResult.validationType`| _Equivalent_<br/>(49415/49416)| **`VerificationResult.validationType`**
| | | | | `VerificationResult.validationProcess`| _Equivalent_<br/>(34999/35000)| `VerificationResult.validationProcess`| _Equivalent_<br/>(49417/49418)| **`VerificationResult.validationProcess`**
| | | | | `VerificationResult.frequency`| _Equivalent_<br/>(35001/35002)| `VerificationResult.frequency`| _Equivalent_<br/>(49419/49420)| **`VerificationResult.frequency`**
| | | | | `VerificationResult.lastPerformed`| _Equivalent_<br/>(35003/35004)| `VerificationResult.lastPerformed`| _Equivalent_<br/>(49421/49422)| **`VerificationResult.lastPerformed`**
| | | | | `VerificationResult.nextScheduled`| _Equivalent_<br/>(35005/35006)| `VerificationResult.nextScheduled`| _Equivalent_<br/>(49423/49424)| **`VerificationResult.nextScheduled`**
| | | | | `VerificationResult.failureAction`| _Equivalent_<br/>(35007/35008)| `VerificationResult.failureAction`| _Equivalent_<br/>(49425/49426)| **`VerificationResult.failureAction`**
| | | | | `VerificationResult.primarySource`| _Equivalent_<br/>(35009/35010)| `VerificationResult.primarySource`| _Equivalent_<br/>(49427/49428)| **`VerificationResult.primarySource`**
| | | | | `VerificationResult.primarySource.id`| _Equivalent_<br/>(35011/35012)| `VerificationResult.primarySource.id`| _Equivalent_<br/>(49429/49430)| **`VerificationResult.primarySource.id`**
| | | | | `VerificationResult.primarySource.extension`| _Equivalent_<br/>(35013/35014)| `VerificationResult.primarySource.extension`| _Equivalent_<br/>(49431/49432)| **`VerificationResult.primarySource.extension`**
| | | | | `VerificationResult.primarySource.modifierExtension`| _Equivalent_<br/>(35015/35016)| `VerificationResult.primarySource.modifierExtension`| _Equivalent_<br/>(49433/49434)| **`VerificationResult.primarySource.modifierExtension`**
| | | | | `VerificationResult.primarySource.who`| _Equivalent_<br/>(35017/35018)| `VerificationResult.primarySource.who`| _Equivalent_<br/>(49435/49436)| **`VerificationResult.primarySource.who`**
| | | | | `VerificationResult.primarySource.type`| _Equivalent_<br/>(35019/35020)| `VerificationResult.primarySource.type`| _Equivalent_<br/>(49437/49438)| **`VerificationResult.primarySource.type`**
| | | | | `VerificationResult.primarySource.communicationMethod`| _Equivalent_<br/>(35021/35022)| `VerificationResult.primarySource.communicationMethod`| _Equivalent_<br/>(49439/49440)| **`VerificationResult.primarySource.communicationMethod`**
| | | | | `VerificationResult.primarySource.validationStatus`| _Equivalent_<br/>(35023/35024)| `VerificationResult.primarySource.validationStatus`| _Equivalent_<br/>(49441/49442)| **`VerificationResult.primarySource.validationStatus`**
| | | | | `VerificationResult.primarySource.validationDate`| _Equivalent_<br/>(35025/35026)| `VerificationResult.primarySource.validationDate`| _Equivalent_<br/>(49443/49444)| **`VerificationResult.primarySource.validationDate`**
| | | | | `VerificationResult.primarySource.canPushUpdates`| _Equivalent_<br/>(35027/35028)| `VerificationResult.primarySource.canPushUpdates`| _Equivalent_<br/>(49445/49446)| **`VerificationResult.primarySource.canPushUpdates`**
| | | | | `VerificationResult.primarySource.pushTypeAvailable`| _Equivalent_<br/>(35029/35030)| `VerificationResult.primarySource.pushTypeAvailable`| _Equivalent_<br/>(49447/49448)| **`VerificationResult.primarySource.pushTypeAvailable`**
| | | | | `VerificationResult.attestation`| _Equivalent_<br/>(35031/35032)| `VerificationResult.attestation`| _Equivalent_<br/>(49449/49450)| **`VerificationResult.attestation`**
| | | | | `VerificationResult.attestation.id`| _Equivalent_<br/>(35033/35034)| `VerificationResult.attestation.id`| _Equivalent_<br/>(49451/49452)| **`VerificationResult.attestation.id`**
| | | | | `VerificationResult.attestation.extension`| _Equivalent_<br/>(35035/35036)| `VerificationResult.attestation.extension`| _Equivalent_<br/>(49453/49454)| **`VerificationResult.attestation.extension`**
| | | | | `VerificationResult.attestation.modifierExtension`| _Equivalent_<br/>(35037/35038)| `VerificationResult.attestation.modifierExtension`| _Equivalent_<br/>(49455/49456)| **`VerificationResult.attestation.modifierExtension`**
| | | | | `VerificationResult.attestation.who`| _Equivalent_<br/>(35039/35040)| `VerificationResult.attestation.who`| _Equivalent_<br/>(49457/49458)| **`VerificationResult.attestation.who`**
| | | | | `VerificationResult.attestation.onBehalfOf`| _Equivalent_<br/>(35041/35042)| `VerificationResult.attestation.onBehalfOf`| _Equivalent_<br/>(49459/49460)| **`VerificationResult.attestation.onBehalfOf`**
| | | | | `VerificationResult.attestation.communicationMethod`| _Equivalent_<br/>(35043/35044)| `VerificationResult.attestation.communicationMethod`| _Equivalent_<br/>(49461/49462)| **`VerificationResult.attestation.communicationMethod`**
| | | | | `VerificationResult.attestation.date`| _Equivalent_<br/>(35045/35046)| `VerificationResult.attestation.date`| _Equivalent_<br/>(49463/49464)| **`VerificationResult.attestation.date`**
| | | | | `VerificationResult.attestation.sourceIdentityCertificate`| _Equivalent_<br/>(35047/35048)| `VerificationResult.attestation.sourceIdentityCertificate`| _Equivalent_<br/>(49465/49466)| **`VerificationResult.attestation.sourceIdentityCertificate`**
| | | | | `VerificationResult.attestation.proxyIdentityCertificate`| _Equivalent_<br/>(35049/35050)| `VerificationResult.attestation.proxyIdentityCertificate`| _Equivalent_<br/>(49467/49468)| **`VerificationResult.attestation.proxyIdentityCertificate`**
| | | | | `VerificationResult.attestation.proxySignature`| _Equivalent_<br/>(35051/35052)| `VerificationResult.attestation.proxySignature`| _Equivalent_<br/>(49469/49470)| **`VerificationResult.attestation.proxySignature`**
| | | | | `VerificationResult.attestation.sourceSignature`| _Equivalent_<br/>(35053/35054)| `VerificationResult.attestation.sourceSignature`| _Equivalent_<br/>(49471/49472)| **`VerificationResult.attestation.sourceSignature`**
| | | | | `VerificationResult.validator`| _Equivalent_<br/>(35055/35056)| `VerificationResult.validator`| _Equivalent_<br/>(49473/49474)| **`VerificationResult.validator`**
| | | | | `VerificationResult.validator.id`| _Equivalent_<br/>(35057/35058)| `VerificationResult.validator.id`| _Equivalent_<br/>(49475/49476)| **`VerificationResult.validator.id`**
| | | | | `VerificationResult.validator.extension`| _Equivalent_<br/>(35059/35060)| `VerificationResult.validator.extension`| _Equivalent_<br/>(49477/49478)| **`VerificationResult.validator.extension`**
| | | | | `VerificationResult.validator.modifierExtension`| _Equivalent_<br/>(35061/35062)| `VerificationResult.validator.modifierExtension`| _Equivalent_<br/>(49479/49480)| **`VerificationResult.validator.modifierExtension`**
| | | | | `VerificationResult.validator.organization`| _Equivalent_<br/>(35063/35064)| `VerificationResult.validator.organization`| _Equivalent_<br/>(49481/49482)| **`VerificationResult.validator.organization`**
| | | | | `VerificationResult.validator.identityCertificate`| _Equivalent_<br/>(35065/35066)| `VerificationResult.validator.identityCertificate`| _Equivalent_<br/>(49483/49484)| **`VerificationResult.validator.identityCertificate`**
| | | | | `VerificationResult.validator.attestationSignature`| _Equivalent_<br/>(35067/35068)| `VerificationResult.validator.attestationSignature`| _Equivalent_<br/>(49485/49486)| **`VerificationResult.validator.attestationSignature`**
| | | | | *50 of 50 elements used* | | *50 of 50 elements used* | | *50 of 50 elements used* 

