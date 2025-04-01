Comparison of 
Generated at Tuesday, April 1, 2025 1:39:09 PM

### MedicationOrder

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | MedicationOrder |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MedicationOrder` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for MedicationOrder Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `97` |
| Database Snapshot Count | `50` |
| Database Differential Count | `33` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MedicationOrder` | `MedicationOrder` | `MedicationOrder` | MedicationOrder | Prescription of medication to for patient | 0..* | MedicationOrder |  |  |
| `MedicationOrder.contained` | `MedicationOrder.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MedicationOrder.dateEnded` | `MedicationOrder.dateEnded` | `dateEnded` |  | When prescription was stopped | 0..1 | dateTime |  |  |
| `MedicationOrder.dateWritten` | `MedicationOrder.dateWritten` | `dateWritten` |  | When prescription was authorized | 0..1 | dateTime |  |  |
| `MedicationOrder.dispenseRequest` | `MedicationOrder.dispenseRequest` | `dispenseRequest` |  | Medication supply authorization | 0..1 | BackboneElement |  |  |
| `MedicationOrder.dispenseRequest.expectedSupplyDuration` | `MedicationOrder.dispenseRequest.expectedSupplyDuration` | `expectedSupplyDuration` |  | Number of days supply per dispense | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/Duration] |  |  |
| `MedicationOrder.dispenseRequest.extension` | `MedicationOrder.dispenseRequest.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `MedicationOrder.dispenseRequest.id` | `MedicationOrder.dispenseRequest.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `MedicationOrder.dispenseRequest.medication[x]` | `MedicationOrder.dispenseRequest.medication[x]` | `medication[x]` |  | Product to be supplied | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Medication) |  |  |
| `MedicationOrder.dispenseRequest.modifierExtension` | `MedicationOrder.dispenseRequest.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicationOrder.dispenseRequest.numberOfRepeatsAllowed` | `MedicationOrder.dispenseRequest.numberOfRepeatsAllowed` | `numberOfRepeatsAllowed` |  | Number of refills authorized | 0..1 | positiveInt |  |  |
| `MedicationOrder.dispenseRequest.quantity` | `MedicationOrder.dispenseRequest.quantity` | `quantity` |  | Amount of medication to supply per dispense | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `MedicationOrder.dispenseRequest.validityPeriod` | `MedicationOrder.dispenseRequest.validityPeriod` | `validityPeriod` |  | Time period supply is authorized for | 0..1 | Period |  |  |
| `MedicationOrder.dosageInstruction` | `MedicationOrder.dosageInstruction` | `dosageInstruction` |  | How medication should be taken | 0..* | BackboneElement |  |  |
| `MedicationOrder.dosageInstruction.additionalInstructions` | `MedicationOrder.dosageInstruction.additionalInstructions` | `additionalInstructions` |  | Supplemental instructions - e.g. "with meals" | 0..1 | CodeableConcept | `Example` |  |
| `MedicationOrder.dosageInstruction.asNeeded[x]` | `MedicationOrder.dosageInstruction.asNeeded[x]` | `asNeeded[x]` |  | Take "as needed" (for x) | 0..1 | boolean, CodeableConcept | `Example` |  |
| `MedicationOrder.dosageInstruction.dose[x]` | `MedicationOrder.dosageInstruction.dose[x]` | `dose[x]` |  | Amount of medication per dose | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity], Range |  |  |
| `MedicationOrder.dosageInstruction.extension` | `MedicationOrder.dosageInstruction.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `MedicationOrder.dosageInstruction.id` | `MedicationOrder.dosageInstruction.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `MedicationOrder.dosageInstruction.maxDosePerPeriod` | `MedicationOrder.dosageInstruction.maxDosePerPeriod` | `maxDosePerPeriod` |  | Upper limit on medication per unit of time | 0..1 | Ratio |  |  |
| `MedicationOrder.dosageInstruction.method` | `MedicationOrder.dosageInstruction.method` | `method` |  | Technique for administering medication | 0..1 | CodeableConcept | `Example` |  |
| `MedicationOrder.dosageInstruction.modifierExtension` | `MedicationOrder.dosageInstruction.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicationOrder.dosageInstruction.rate[x]` | `MedicationOrder.dosageInstruction.rate[x]` | `rate[x]` |  | Amount of medication per unit of time | 0..1 | Range, Ratio |  |  |
| `MedicationOrder.dosageInstruction.route` | `MedicationOrder.dosageInstruction.route` | `route` |  | How drug should enter body | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/route-codes` |
| `MedicationOrder.dosageInstruction.site[x]` | `MedicationOrder.dosageInstruction.site[x]` | `site[x]` |  | Body site to administer to | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/BodySite) | `Example` | `http://hl7.org/fhir/ValueSet/approach-site-codes` |
| `MedicationOrder.dosageInstruction.text` | `MedicationOrder.dosageInstruction.text` | `text` |  | Dosage instructions expressed as text | 0..1 | string |  |  |
| `MedicationOrder.dosageInstruction.timing` | `MedicationOrder.dosageInstruction.timing` | `timing` |  | When medication should be administered | 0..1 | Timing |  |  |
| `MedicationOrder.encounter` | `MedicationOrder.encounter` | `encounter` |  | Created during encounter/admission/stay | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `MedicationOrder.extension` | `MedicationOrder.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `MedicationOrder.id` | `MedicationOrder.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MedicationOrder.identifier` | `MedicationOrder.identifier` | `identifier` |  | External identifier | 0..* | Identifier |  |  |
| `MedicationOrder.implicitRules` | `MedicationOrder.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MedicationOrder.language` | `MedicationOrder.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `MedicationOrder.medication[x]` | `MedicationOrder.medication[x]` | `medication[x]` |  | Medication to be taken | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Medication) |  |  |
| `MedicationOrder.meta` | `MedicationOrder.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MedicationOrder.modifierExtension` | `MedicationOrder.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicationOrder.note` | `MedicationOrder.note` | `note` |  | Information about the prescription | 0..1 | string |  |  |
| `MedicationOrder.patient` | `MedicationOrder.patient` | `patient` |  | Who prescription is for | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `MedicationOrder.prescriber` | `MedicationOrder.prescriber` | `prescriber` |  | Who ordered the medication(s) | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `MedicationOrder.priorPrescription` | `MedicationOrder.priorPrescription` | `priorPrescription` |  | An order/prescription that this supersedes | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/MedicationOrder) |  |  |
| `MedicationOrder.reasonEnded` | `MedicationOrder.reasonEnded` | `reasonEnded` |  | Why prescription was stopped | 0..1 | CodeableConcept | `Example` |  |
| `MedicationOrder.reason[x]` | `MedicationOrder.reason[x]` | `reason[x]` |  | Reason or indication for writing the prescription | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Condition) | `Example` | `http://hl7.org/fhir/ValueSet/condition-code` |
| `MedicationOrder.status` | `MedicationOrder.status` | `status` |  | active \| on-hold \| completed \| entered-in-error \| stopped \| draft | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/medication-order-status` |
| `MedicationOrder.substitution` | `MedicationOrder.substitution` | `substitution` |  | Any restrictions on medication substitution | 0..1 | BackboneElement |  |  |
| `MedicationOrder.substitution.extension` | `MedicationOrder.substitution.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `MedicationOrder.substitution.id` | `MedicationOrder.substitution.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `MedicationOrder.substitution.modifierExtension` | `MedicationOrder.substitution.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicationOrder.substitution.reason` | `MedicationOrder.substitution.reason` | `reason` |  | Why should (not) substitution be made | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/v3-SubstanceAdminSubstitutionReason` |
| `MedicationOrder.substitution.type` | `MedicationOrder.substitution.type` | `type` |  | generic \| formulary + | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/v3-ActSubstanceAdminSubstitutionCode` |
| `MedicationOrder.text` | `MedicationOrder.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [MedicationOrder](/docs/R2/Resources/MedicationOrder.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationOrder\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `127`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `293`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationRequest](/docs/R3/Resources/MedicationRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `482`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `676`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationRequest](/docs/R4/Resources/MedicationRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1543`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1544`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationRequest](/docs/R4B/Resources/MedicationRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationRequest\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1006`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1235`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationRequest](/docs/R5/Resources/MedicationRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationRequest\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition MedicationOrder from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 MedicationOrder| Relationship | [R3 MedicationRequest](/docs/R3/Resources/MedicationRequest.md)| Relationship | [R4 MedicationRequest](/docs/R4/Resources/MedicationRequest.md)| Relationship | [R4B MedicationRequest](/docs/R4B/Resources/MedicationRequest.md)| Relationship | [R5 MedicationRequest](/docs/R5/Resources/MedicationRequest.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`MedicationOrder`**| | | | | | | | | 
| **`MedicationOrder.id`**| | | | | | | | | 
| **`MedicationOrder.meta`**| | | | | | | | | 
| **`MedicationOrder.implicitRules`**| | | | | | | | | 
| **`MedicationOrder.language`**| | | | | | | | | 
| **`MedicationOrder.text`**| | | | | | | | | 
| **`MedicationOrder.contained`**| | | | | | | | | 
| **`MedicationOrder.extension`**| | | | | | | | | 
| **`MedicationOrder.modifierExtension`**| | | | | | | | | 
| **`MedicationOrder.identifier`**| | | | | | | | | 
| **`MedicationOrder.dateWritten`**| _Equivalent_<br/>(282/662)| `MedicationRequest.authoredOn`| _Equivalent_<br/>(15999/16000)| `MedicationRequest.authoredOn`| _Equivalent_<br/>(29970/29971)| `MedicationRequest.authoredOn`| _Equivalent_<br/>(44644/44645)| `MedicationRequest.authoredOn`
| **`MedicationOrder.status`**| | | | | | | | | 
| **`MedicationOrder.dateEnded`**| | | | | | | | | 
| **`MedicationOrder.reasonEnded`**| | | | | | | | | 
| **`MedicationOrder.patient`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(285)<hr/>←←←← _RelatedTo_ ←←←← <br/>(667)| `MedicationRequest.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15995)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15996)| `MedicationRequest.subject`| _Equivalent_<br/>(29964/29965)| `MedicationRequest.subject`| _Equivalent_<br/>(44638/44639)| `MedicationRequest.subject`
| **`MedicationOrder.prescriber`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(286)<hr/>←←←← _RelatedTo_ ←←←← <br/>(666)| `MedicationRequest.requester.agent`| →→→→ _RelatedTo_ →→→→ <br/>(1192)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1605)| `MedicationRequest.requester`| _Equivalent_<br/>(29972/29973)| `MedicationRequest.requester`| _Equivalent_<br/>(44646/44647)| `MedicationRequest.requester`
| **`MedicationOrder.encounter`**| →→→→ _RelatedTo_ →→→→ <br/>(284)<hr/>←←←← _RelatedTo_ ←←←← <br/>(663)| `MedicationRequest.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1190)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1604)| `MedicationRequest.encounter`| _Equivalent_<br/>(29966/29967)| `MedicationRequest.encounter`| _Equivalent_<br/>(44640/44641)| `MedicationRequest.encounter`
| **`MedicationOrder.reason[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(289)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(665)| `MedicationRequest.reasonCode`| _Equivalent_<br/>(16008/16009)| `MedicationRequest.reasonCode`| _Equivalent_<br/>(29980/29981)| `MedicationRequest.reasonCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1837)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2080)| `MedicationRequest.reason`
| **`MedicationOrder.reason[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(289)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(665)| `MedicationRequest.reasonReference`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16010)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16011)| `MedicationRequest.reasonReference`| _Equivalent_<br/>(29982/29983)| `MedicationRequest.reasonReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1838)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2081)| `MedicationRequest.reason`
| **`MedicationOrder.note`**| | | | | | | | | 
| **`MedicationOrder.medication[x]`**| | | | | | | | | 
| **`MedicationOrder.dosageInstruction`**| | | | | | | | | 
| **`MedicationOrder.dosageInstruction.id`**| | | | | | | | | 
| **`MedicationOrder.dosageInstruction.extension`**| | | | | | | | | 
| **`MedicationOrder.dosageInstruction.modifierExtension`**| | | | | | | | | 
| **`MedicationOrder.dosageInstruction.text`**| | | | | | | | | 
| **`MedicationOrder.dosageInstruction.additionalInstructions`**| | | | | | | | | 
| **`MedicationOrder.dosageInstruction.timing`**| | | | | | | | | 
| **`MedicationOrder.dosageInstruction.asNeeded[x]`**| | | | | | | | | 
| **`MedicationOrder.dosageInstruction.site[x]`**| | | | | | | | | 
| **`MedicationOrder.dosageInstruction.route`**| | | | | | | | | 
| **`MedicationOrder.dosageInstruction.method`**| | | | | | | | | 
| **`MedicationOrder.dosageInstruction.dose[x]`**| | | | | | | | | 
| **`MedicationOrder.dosageInstruction.rate[x]`**| | | | | | | | | 
| **`MedicationOrder.dosageInstruction.maxDosePerPeriod`**| | | | | | | | | 
| **`MedicationOrder.dispenseRequest`**| | | | | | | | | 
| **`MedicationOrder.dispenseRequest.id`**| | | | | | | | | 
| **`MedicationOrder.dispenseRequest.extension`**| | | | | | | | | 
| **`MedicationOrder.dispenseRequest.modifierExtension`**| | | | | | | | | 
| **`MedicationOrder.dispenseRequest.medication[x]`**| | | | | | | | | 
| **`MedicationOrder.dispenseRequest.validityPeriod`**| | | | | | | | | 
| **`MedicationOrder.dispenseRequest.numberOfRepeatsAllowed`**| | | | | | | | | 
| **`MedicationOrder.dispenseRequest.quantity`**| | | | | | | | | 
| **`MedicationOrder.dispenseRequest.expectedSupplyDuration`**| | | | | | | | | 
| **`MedicationOrder.substitution`**| | | | | | | | | 
| **`MedicationOrder.substitution.id`**| | | | | | | | | 
| **`MedicationOrder.substitution.extension`**| | | | | | | | | 
| **`MedicationOrder.substitution.modifierExtension`**| | | | | | | | | 
| **`MedicationOrder.substitution.type`**| | | | | | | | | 
| **`MedicationOrder.substitution.reason`**| | | | | | | | | 
| **`MedicationOrder.priorPrescription`**| | | | | | | | | 
| *50 of 50 elements used* | | *6 of 51 elements used* | | *6 of 61 elements used* | | *6 of 61 elements used* | | *5 of 64 elements used* 

