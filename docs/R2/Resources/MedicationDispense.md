Comparison of 
Generated at Tuesday, April 1, 2025 1:39:09 PM

### MedicationDispense

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | MedicationDispense |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MedicationDispense` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for MedicationDispense Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `96` |
| Database Snapshot Count | `44` |
| Database Differential Count | `30` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MedicationDispense` | `MedicationDispense` | `MedicationDispense` | MedicationDispense | Dispensing a medication to a named patient | 0..* | MedicationDispense |  |  |
| `MedicationDispense.authorizingPrescription` | `MedicationDispense.authorizingPrescription` | `authorizingPrescription` |  | Medication order that authorizes the dispense | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/MedicationOrder) |  |  |
| `MedicationDispense.contained` | `MedicationDispense.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MedicationDispense.daysSupply` | `MedicationDispense.daysSupply` | `daysSupply` |  | Days Supply | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `MedicationDispense.destination` | `MedicationDispense.destination` | `destination` |  | Where the medication was sent | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `MedicationDispense.dispenser` | `MedicationDispense.dispenser` | `dispenser` |  | Practitioner responsible for dispensing medication | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `MedicationDispense.dosageInstruction` | `MedicationDispense.dosageInstruction` | `dosageInstruction` |  | Medicine administration instructions to the patient/caregiver | 0..* | BackboneElement |  |  |
| `MedicationDispense.dosageInstruction.additionalInstructions` | `MedicationDispense.dosageInstruction.additionalInstructions` | `additionalInstructions` |  | E.g. "Take with food" | 0..1 | CodeableConcept | `Example` |  |
| `MedicationDispense.dosageInstruction.asNeeded[x]` | `MedicationDispense.dosageInstruction.asNeeded[x]` | `asNeeded[x]` |  | Take "as needed" f(or x) | 0..1 | boolean, CodeableConcept | `Example` |  |
| `MedicationDispense.dosageInstruction.dose[x]` | `MedicationDispense.dosageInstruction.dose[x]` | `dose[x]` |  | Amount of medication per dose | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity], Range |  |  |
| `MedicationDispense.dosageInstruction.extension` | `MedicationDispense.dosageInstruction.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `MedicationDispense.dosageInstruction.id` | `MedicationDispense.dosageInstruction.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `MedicationDispense.dosageInstruction.maxDosePerPeriod` | `MedicationDispense.dosageInstruction.maxDosePerPeriod` | `maxDosePerPeriod` |  | Upper limit on medication per unit of time | 0..1 | Ratio |  |  |
| `MedicationDispense.dosageInstruction.method` | `MedicationDispense.dosageInstruction.method` | `method` |  | Technique for administering medication | 0..1 | CodeableConcept | `Example` |  |
| `MedicationDispense.dosageInstruction.modifierExtension` | `MedicationDispense.dosageInstruction.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicationDispense.dosageInstruction.rate[x]` | `MedicationDispense.dosageInstruction.rate[x]` | `rate[x]` |  | Amount of medication per unit of time | 0..1 | Range, Ratio |  |  |
| `MedicationDispense.dosageInstruction.route` | `MedicationDispense.dosageInstruction.route` | `route` |  | How drug should enter body | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/route-codes` |
| `MedicationDispense.dosageInstruction.site[x]` | `MedicationDispense.dosageInstruction.site[x]` | `site[x]` |  | Body site to administer to | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/BodySite) | `Example` | `http://hl7.org/fhir/ValueSet/approach-site-codes` |
| `MedicationDispense.dosageInstruction.text` | `MedicationDispense.dosageInstruction.text` | `text` |  | Dosage Instructions | 0..1 | string |  |  |
| `MedicationDispense.dosageInstruction.timing` | `MedicationDispense.dosageInstruction.timing` | `timing` |  | When medication should be administered | 0..1 | Timing |  |  |
| `MedicationDispense.extension` | `MedicationDispense.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `MedicationDispense.id` | `MedicationDispense.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MedicationDispense.identifier` | `MedicationDispense.identifier` | `identifier` |  | External identifier | 0..1 | Identifier |  |  |
| `MedicationDispense.implicitRules` | `MedicationDispense.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MedicationDispense.language` | `MedicationDispense.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `MedicationDispense.medication[x]` | `MedicationDispense.medication[x]` | `medication[x]` |  | What medication was supplied | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Medication) |  |  |
| `MedicationDispense.meta` | `MedicationDispense.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MedicationDispense.modifierExtension` | `MedicationDispense.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicationDispense.note` | `MedicationDispense.note` | `note` |  | Information about the dispense | 0..1 | string |  |  |
| `MedicationDispense.patient` | `MedicationDispense.patient` | `patient` |  | Who the dispense is for | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `MedicationDispense.quantity` | `MedicationDispense.quantity` | `quantity` |  | Amount dispensed | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `MedicationDispense.receiver` | `MedicationDispense.receiver` | `receiver` |  | Who collected the medication | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `MedicationDispense.status` | `MedicationDispense.status` | `status` |  | in-progress \| on-hold \| completed \| entered-in-error \| stopped | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/medication-dispense-status` |
| `MedicationDispense.substitution` | `MedicationDispense.substitution` | `substitution` |  | Deals with substitution of one medicine for another | 0..1 | BackboneElement |  |  |
| `MedicationDispense.substitution.extension` | `MedicationDispense.substitution.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `MedicationDispense.substitution.id` | `MedicationDispense.substitution.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `MedicationDispense.substitution.modifierExtension` | `MedicationDispense.substitution.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicationDispense.substitution.reason` | `MedicationDispense.substitution.reason` | `reason` |  | Why was substitution made | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/v3-SubstanceAdminSubstitutionReason` |
| `MedicationDispense.substitution.responsibleParty` | `MedicationDispense.substitution.responsibleParty` | `responsibleParty` |  | Who is responsible for the substitution | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `MedicationDispense.substitution.type` | `MedicationDispense.substitution.type` | `type` |  | Type of substitution | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/v3-ActSubstanceAdminSubstitutionCode` |
| `MedicationDispense.text` | `MedicationDispense.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `MedicationDispense.type` | `MedicationDispense.type` | `type` |  | Trial fill, partial fill, emergency fill, etc. | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/v3-ActPharmacySupplyType` |
| `MedicationDispense.whenHandedOver` | `MedicationDispense.whenHandedOver` | `whenHandedOver` |  | When product was given out | 0..1 | dateTime |  |  |
| `MedicationDispense.whenPrepared` | `MedicationDispense.whenPrepared` | `whenPrepared` |  | Dispense processing time | 0..1 | dateTime |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [MedicationDispense](/docs/R2/Resources/MedicationDispense.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationDispense\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `126`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `292`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationDispense](/docs/R3/Resources/MedicationDispense.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationDispense\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `481`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `675`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationDispense](/docs/R4/Resources/MedicationDispense.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationDispense\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1539`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1540`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationDispense](/docs/R4B/Resources/MedicationDispense.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationDispense\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1004`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1233`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationDispense](/docs/R5/Resources/MedicationDispense.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationDispense\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition MedicationDispense from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 MedicationDispense| Relationship | [R3 MedicationDispense](/docs/R3/Resources/MedicationDispense.md)| Relationship | [R4 MedicationDispense](/docs/R4/Resources/MedicationDispense.md)| Relationship | [R4B MedicationDispense](/docs/R4B/Resources/MedicationDispense.md)| Relationship | [R5 MedicationDispense](/docs/R5/Resources/MedicationDispense.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`MedicationDispense`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6191)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6192)| `MedicationDispense`| _Equivalent_<br/>(15831/15832)| `MedicationDispense`| _Equivalent_<br/>(29590/29591)| `MedicationDispense`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44344)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44345)| `MedicationDispense`
| **`MedicationDispense.id`**| _Equivalent_<br/>(6193/6194)| `MedicationDispense.id`| _Equivalent_<br/>(15833/15834)| `MedicationDispense.id`| _Equivalent_<br/>(29592/29593)| `MedicationDispense.id`| _Equivalent_<br/>(44346/44347)| `MedicationDispense.id`
| **`MedicationDispense.meta`**| _Equivalent_<br/>(6195/6196)| `MedicationDispense.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15835)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15836)| `MedicationDispense.meta`| _Equivalent_<br/>(29594/29595)| `MedicationDispense.meta`| _Equivalent_<br/>(44348/44349)| `MedicationDispense.meta`
| **`MedicationDispense.implicitRules`**| _Equivalent_<br/>(6197/6198)| `MedicationDispense.implicitRules`| _Equivalent_<br/>(15837/15838)| `MedicationDispense.implicitRules`| _Equivalent_<br/>(29596/29597)| `MedicationDispense.implicitRules`| _Equivalent_<br/>(44350/44351)| `MedicationDispense.implicitRules`
| **`MedicationDispense.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6199)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6200)| `MedicationDispense.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15839)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(15840)| `MedicationDispense.language`| _Equivalent_<br/>(29598/29599)| `MedicationDispense.language`| _Equivalent_<br/>(44352/44353)| `MedicationDispense.language`
| **`MedicationDispense.text`**| _Equivalent_<br/>(6201/6202)| `MedicationDispense.text`| _Equivalent_<br/>(15841/15842)| `MedicationDispense.text`| _Equivalent_<br/>(29600/29601)| `MedicationDispense.text`| _Equivalent_<br/>(44354/44355)| `MedicationDispense.text`
| **`MedicationDispense.contained`**| _Equivalent_<br/>(6203/6204)| `MedicationDispense.contained`| _Equivalent_<br/>(15843/15844)| `MedicationDispense.contained`| _Equivalent_<br/>(29602/29603)| `MedicationDispense.contained`| _Equivalent_<br/>(44356/44357)| `MedicationDispense.contained`
| **`MedicationDispense.extension`**| _Equivalent_<br/>(6205/6206)| `MedicationDispense.extension`| →→→→ _Equivalent_ →→→→ <br/>(15845)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15846)| `MedicationDispense.extension`| _Equivalent_<br/>(29604/29605)| `MedicationDispense.extension`| _Equivalent_<br/>(44358/44359)| `MedicationDispense.extension`
| **`MedicationDispense.modifierExtension`**| _Equivalent_<br/>(6207/6208)| `MedicationDispense.modifierExtension`| _Equivalent_<br/>(15847/15848)| `MedicationDispense.modifierExtension`| _Equivalent_<br/>(29606/29607)| `MedicationDispense.modifierExtension`| _Equivalent_<br/>(44360/44361)| `MedicationDispense.modifierExtension`
| **`MedicationDispense.identifier`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6209)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6210)| `MedicationDispense.identifier`| _Equivalent_<br/>(15849/15850)| `MedicationDispense.identifier`| _Equivalent_<br/>(29608/29609)| `MedicationDispense.identifier`| _Equivalent_<br/>(44362/44363)| `MedicationDispense.identifier`
| **`MedicationDispense.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6211)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6212)| `MedicationDispense.status`| →→→→ _RelatedTo_ →→→→ <br/>(15853)<hr/>←←←← _RelatedTo_ ←←←← <br/>(15854)| `MedicationDispense.status`| _Equivalent_<br/>(29612/29613)| `MedicationDispense.status`| _Equivalent_<br/>(44366/44367)| `MedicationDispense.status`
| **`MedicationDispense.patient`**| →→→→ _RelatedTo_ →→→→ <br/>(280)<hr/>←←←← _RelatedTo_ ←←←← <br/>(661)| `MedicationDispense.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15859)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15860)| `MedicationDispense.subject`| _Equivalent_<br/>(29620/29621)| `MedicationDispense.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44370)<hr/>←←←← _Equivalent_ ←←←← <br/>(44371)| `MedicationDispense.subject`
| **`MedicationDispense.dispenser`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(279)<hr/>←←←← _RelatedTo_ ←←←← <br/>(660)| `MedicationDispense.performer.actor`| →→→→ _RelatedTo_ →→→→ <br/>(15873)<hr/>←←←← _RelatedTo_ ←←←← <br/>(15874)| `MedicationDispense.performer.actor`| _Equivalent_<br/>(29636/29637)| `MedicationDispense.performer.actor`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(44384)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(44385)| `MedicationDispense.performer.actor`
| **`MedicationDispense.authorizingPrescription`**| →→→→ _RelatedTo_ →→→→ <br/>(6213)<hr/>←←←← _RelatedTo_ ←←←← <br/>(6214)| `MedicationDispense.authorizingPrescription`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15875)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15876)| `MedicationDispense.authorizingPrescription`| _Equivalent_<br/>(29640/29641)| `MedicationDispense.authorizingPrescription`| _Equivalent_<br/>(44388/44389)| `MedicationDispense.authorizingPrescription`
| **`MedicationDispense.type`**| _Equivalent_<br/>(6215/6216)| `MedicationDispense.type`| _Equivalent_<br/>(15877/15878)| `MedicationDispense.type`| _Equivalent_<br/>(29642/29643)| `MedicationDispense.type`| _Equivalent_<br/>(44390/44391)| `MedicationDispense.type`
| **`MedicationDispense.quantity`**| _Equivalent_<br/>(6217/6218)| `MedicationDispense.quantity`| _Equivalent_<br/>(15879/15880)| `MedicationDispense.quantity`| _Equivalent_<br/>(29644/29645)| `MedicationDispense.quantity`| _Equivalent_<br/>(44392/44393)| `MedicationDispense.quantity`
| **`MedicationDispense.daysSupply`**| _Equivalent_<br/>(6219/6220)| `MedicationDispense.daysSupply`| _Equivalent_<br/>(15881/15882)| `MedicationDispense.daysSupply`| _Equivalent_<br/>(29646/29647)| `MedicationDispense.daysSupply`| _Equivalent_<br/>(44394/44395)| `MedicationDispense.daysSupply`
| **`MedicationDispense.medication[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(6221)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6222)| `MedicationDispense.medication[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15857)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15858)| `MedicationDispense.medication[x]`| _Equivalent_<br/>(29618/29619)| `MedicationDispense.medication[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1829)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2072)| `MedicationDispense.medication`
| **`MedicationDispense.whenPrepared`**| _Equivalent_<br/>(6223/6224)| `MedicationDispense.whenPrepared`| _Equivalent_<br/>(15883/15884)| `MedicationDispense.whenPrepared`| _Equivalent_<br/>(29648/29649)| `MedicationDispense.whenPrepared`| _Equivalent_<br/>(44396/44397)| `MedicationDispense.whenPrepared`
| **`MedicationDispense.whenHandedOver`**| _Equivalent_<br/>(6225/6226)| `MedicationDispense.whenHandedOver`| _Equivalent_<br/>(15885/15886)| `MedicationDispense.whenHandedOver`| _Equivalent_<br/>(29650/29651)| `MedicationDispense.whenHandedOver`| _Equivalent_<br/>(44398/44399)| `MedicationDispense.whenHandedOver`
| **`MedicationDispense.destination`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6227)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6228)| `MedicationDispense.destination`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15887)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15888)| `MedicationDispense.destination`| _Equivalent_<br/>(29652/29653)| `MedicationDispense.destination`| _Equivalent_<br/>(44400/44401)| `MedicationDispense.destination`
| **`MedicationDispense.receiver`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6229)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6230)| `MedicationDispense.receiver`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15889)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15890)| `MedicationDispense.receiver`| _Equivalent_<br/>(29654/29655)| `MedicationDispense.receiver`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(44402)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(44403)| `MedicationDispense.receiver`
| **`MedicationDispense.note`**| →→→→ _RelatedTo_ →→→→ <br/>(6231)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6232)| `MedicationDispense.note`| _Equivalent_<br/>(15891/15892)| `MedicationDispense.note`| _Equivalent_<br/>(29656/29657)| `MedicationDispense.note`| _Equivalent_<br/>(44404/44405)| `MedicationDispense.note`
| **`MedicationDispense.dosageInstruction`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(6233)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6234)| `MedicationDispense.dosageInstruction`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15893)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15894)| `MedicationDispense.dosageInstruction`| _Equivalent_<br/>(29658/29659)| `MedicationDispense.dosageInstruction`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44406)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44407)| `MedicationDispense.dosageInstruction`
| **`MedicationDispense.dosageInstruction.id`**| | | | | | | | | 
| **`MedicationDispense.dosageInstruction.extension`**| | | | | | | | | 
| **`MedicationDispense.dosageInstruction.modifierExtension`**| | | | | | | | | 
| **`MedicationDispense.dosageInstruction.text`**| | | | | | | | | 
| **`MedicationDispense.dosageInstruction.additionalInstructions`**| | | | | | | | | 
| **`MedicationDispense.dosageInstruction.timing`**| | | | | | | | | 
| **`MedicationDispense.dosageInstruction.asNeeded[x]`**| | | | | | | | | 
| **`MedicationDispense.dosageInstruction.site[x]`**| | | | | | | | | 
| **`MedicationDispense.dosageInstruction.route`**| | | | | | | | | 
| **`MedicationDispense.dosageInstruction.method`**| | | | | | | | | 
| **`MedicationDispense.dosageInstruction.dose[x]`**| | | | | | | | | 
| **`MedicationDispense.dosageInstruction.rate[x]`**| | | | | | | | | 
| **`MedicationDispense.dosageInstruction.maxDosePerPeriod`**| | | | | | | | | 
| **`MedicationDispense.substitution`**| _Equivalent_<br/>(6248/6249)| `MedicationDispense.substitution`| _Equivalent_<br/>(15895/15896)| `MedicationDispense.substitution`| _Equivalent_<br/>(29660/29661)| `MedicationDispense.substitution`| _Equivalent_<br/>(44408/44409)| `MedicationDispense.substitution`
| **`MedicationDispense.substitution.id`**| _Equivalent_<br/>(6250/6251)| `MedicationDispense.substitution.id`| _Equivalent_<br/>(15897/15898)| `MedicationDispense.substitution.id`| _Equivalent_<br/>(29662/29663)| `MedicationDispense.substitution.id`| _Equivalent_<br/>(44410/44411)| `MedicationDispense.substitution.id`
| **`MedicationDispense.substitution.extension`**| _Equivalent_<br/>(6252/6253)| `MedicationDispense.substitution.extension`| _Equivalent_<br/>(15899/15900)| `MedicationDispense.substitution.extension`| _Equivalent_<br/>(29664/29665)| `MedicationDispense.substitution.extension`| _Equivalent_<br/>(44412/44413)| `MedicationDispense.substitution.extension`
| **`MedicationDispense.substitution.modifierExtension`**| _Equivalent_<br/>(6254/6255)| `MedicationDispense.substitution.modifierExtension`| _Equivalent_<br/>(15901/15902)| `MedicationDispense.substitution.modifierExtension`| _Equivalent_<br/>(29666/29667)| `MedicationDispense.substitution.modifierExtension`| _Equivalent_<br/>(44414/44415)| `MedicationDispense.substitution.modifierExtension`
| **`MedicationDispense.substitution.type`**| →→→→ _Equivalent_ →→→→ <br/>(6256)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6257)| `MedicationDispense.substitution.type`| _Equivalent_<br/>(15905/15906)| `MedicationDispense.substitution.type`| _Equivalent_<br/>(29670/29671)| `MedicationDispense.substitution.type`| _Equivalent_<br/>(44418/44419)| `MedicationDispense.substitution.type`
| **`MedicationDispense.substitution.reason`**| _Equivalent_<br/>(6258/6259)| `MedicationDispense.substitution.reason`| _Equivalent_<br/>(15907/15908)| `MedicationDispense.substitution.reason`| _Equivalent_<br/>(29672/29673)| `MedicationDispense.substitution.reason`| _Equivalent_<br/>(44420/44421)| `MedicationDispense.substitution.reason`
| **`MedicationDispense.substitution.responsibleParty`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6260)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6261)| `MedicationDispense.substitution.responsibleParty`| →→→→ _RelatedTo_ →→→→ <br/>(15909)<hr/>←←←← _RelatedTo_ ←←←← <br/>(15910)| `MedicationDispense.substitution.responsibleParty`| _Equivalent_<br/>(29674/29675)| `MedicationDispense.substitution.responsibleParty`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(44422)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(44423)| `MedicationDispense.substitution.responsibleParty`
| *44 of 44 elements used* | | *31 of 45 elements used* | | *31 of 45 elements used* | | *31 of 45 elements used* | | *31 of 48 elements used* 

