Comparison of 
Generated at Thursday, April 3, 2025 8:18:11 AM

### Dosage

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Dosage |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Dosage` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Dosage Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `453` |
| Database Snapshot Count | `17` |
| Database Differential Count | `15` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Dosage` | `Dosage` | `Dosage` | Dosage | How the medication is/was taken or should be taken | 0..* | Dosage |  |  |
| `Dosage.additionalInstruction` | `Dosage.additionalInstruction` | `additionalInstruction` |  | Supplemental instruction - e.g. "with meals" | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/additional-instruction-codes` |
| `Dosage.asNeeded[x]` | `Dosage.asNeeded[x]` | `asNeeded[x]` |  | Take "as needed" (for x) | 0..1 | boolean, CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medication-as-needed-reason` |
| `Dosage.dose[x]` | `Dosage.dose[x]` | `dose[x]` |  | Amount of medication per dose | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity], Range |  |  |
| `Dosage.extension` | `Dosage.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Dosage.id` | `Dosage.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Dosage.maxDosePerAdministration` | `Dosage.maxDosePerAdministration` | `maxDosePerAdministration` |  | Upper limit on medication per administration | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `Dosage.maxDosePerLifetime` | `Dosage.maxDosePerLifetime` | `maxDosePerLifetime` |  | Upper limit on medication per lifetime of the patient | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `Dosage.maxDosePerPeriod` | `Dosage.maxDosePerPeriod` | `maxDosePerPeriod` |  | Upper limit on medication per unit of time | 0..1 | Ratio |  |  |
| `Dosage.method` | `Dosage.method` | `method` |  | Technique for administering medication | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/administration-method-codes` |
| `Dosage.patientInstruction` | `Dosage.patientInstruction` | `patientInstruction` |  | Patient or consumer oriented instructions | 0..1 | string |  |  |
| `Dosage.rate[x]` | `Dosage.rate[x]` | `rate[x]` |  | Amount of medication per unit of time | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity], Range, Ratio |  |  |
| `Dosage.route` | `Dosage.route` | `route` |  | How drug should enter body | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/route-codes` |
| `Dosage.sequence` | `Dosage.sequence` | `sequence` |  | The order of the dosage instructions | 0..1 | integer |  |  |
| `Dosage.site` | `Dosage.site` | `site` |  | Body site to administer to | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/approach-site-codes` |
| `Dosage.text` | `Dosage.text` | `text` |  | Free text dosage instructions e.g. SIG | 0..1 | string |  |  |
| `Dosage.timing` | `Dosage.timing` | `timing` |  | When medication should be administered | 0..1 | Timing |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Dosage](/docs/R3/ComplexTypes/Dosage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Dosage\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `394`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `590`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Dosage](/docs/R4/ComplexTypes/Dosage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Dosage\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1333`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1334`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Dosage](/docs/R4B/ComplexTypes/Dosage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Dosage\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `902`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1131`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Dosage](/docs/R5/ComplexTypes/Dosage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Dosage\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Dosage from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 Dosage| Relationship | [R4 Dosage](/docs/R4/ComplexTypes/Dosage.md)| Relationship | [R4B Dosage](/docs/R4B/ComplexTypes/Dosage.md)| Relationship | [R5 Dosage](/docs/R5/ComplexTypes/Dosage.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`Dosage`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9353)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9354)| `Dosage`| _Equivalent_<br/>(20726/20727)| `Dosage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(35843)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(35844)| `Dosage`
| | | **`Dosage.id`**| _Equivalent_<br/>(9355/9356)| `Dosage.id`| _Equivalent_<br/>(20728/20729)| `Dosage.id`| _Equivalent_<br/>(35845/35846)| `Dosage.id`
| | | **`Dosage.extension`**| _Equivalent_<br/>(9357/9358)| `Dosage.extension`| _Equivalent_<br/>(20730/20731)| `Dosage.extension`| _Equivalent_<br/>(35847/35848)| `Dosage.extension`
| | | **`Dosage.sequence`**| _Equivalent_<br/>(9359/9360)| `Dosage.sequence`| _Equivalent_<br/>(20734/20735)| `Dosage.sequence`| _Equivalent_<br/>(35851/35852)| `Dosage.sequence`
| | | **`Dosage.text`**| _Equivalent_<br/>(9361/9362)| `Dosage.text`| _Equivalent_<br/>(20736/20737)| `Dosage.text`| _Equivalent_<br/>(35853/35854)| `Dosage.text`
| | | **`Dosage.additionalInstruction`**| _Equivalent_<br/>(9363/9364)| `Dosage.additionalInstruction`| _Equivalent_<br/>(20738/20739)| `Dosage.additionalInstruction`| _Equivalent_<br/>(35855/35856)| `Dosage.additionalInstruction`
| | | **`Dosage.patientInstruction`**| _Equivalent_<br/>(9365/9366)| `Dosage.patientInstruction`| _Equivalent_<br/>(20740/20741)| `Dosage.patientInstruction`| _Equivalent_<br/>(35857/35858)| `Dosage.patientInstruction`
| | | **`Dosage.timing`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9367)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9368)| `Dosage.timing`| _Equivalent_<br/>(20742/20743)| `Dosage.timing`| _Equivalent_<br/>(35859/35860)| `Dosage.timing`
| | | **`Dosage.asNeeded[x]`**| _Equivalent_<br/>(9369/9370)| `Dosage.asNeeded[x]`| _Equivalent_<br/>(20744/20745)| `Dosage.asNeeded[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1712)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1956)| `Dosage.asNeeded`
| | | **`Dosage.asNeeded[x]`**| _Equivalent_<br/>(9369/9370)| `Dosage.asNeeded[x]`| _Equivalent_<br/>(20744/20745)| `Dosage.asNeeded[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1712)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1956)| `Dosage.asNeededFor`
| | | **`Dosage.site`**| _Equivalent_<br/>(9371/9372)| `Dosage.site`| _Equivalent_<br/>(20746/20747)| `Dosage.site`| _Equivalent_<br/>(35861/35862)| `Dosage.site`
| | | **`Dosage.route`**| _Equivalent_<br/>(9373/9374)| `Dosage.route`| _Equivalent_<br/>(20748/20749)| `Dosage.route`| _Equivalent_<br/>(35863/35864)| `Dosage.route`
| | | **`Dosage.method`**| _Equivalent_<br/>(9375/9376)| `Dosage.method`| _Equivalent_<br/>(20750/20751)| `Dosage.method`| _Equivalent_<br/>(35865/35866)| `Dosage.method`
| | | **`Dosage.dose[x]`**| _Equivalent_<br/>(1013/1495)| `Dosage.doseAndRate.dose[x]`| _Equivalent_<br/>(20760/20761)| `Dosage.doseAndRate.dose[x]`| _Equivalent_<br/>(35875/35876)| `Dosage.doseAndRate.dose[x]`
| | | **`Dosage.maxDosePerPeriod`**| _Equivalent_<br/>(9377/9378)| `Dosage.maxDosePerPeriod`| _Equivalent_<br/>(20764/20765)| `Dosage.maxDosePerPeriod`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(35879)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(35880)| `Dosage.maxDosePerPeriod`
| | | **`Dosage.maxDosePerAdministration`**| _Equivalent_<br/>(9379/9380)| `Dosage.maxDosePerAdministration`| _Equivalent_<br/>(20766/20767)| `Dosage.maxDosePerAdministration`| _Equivalent_<br/>(35881/35882)| `Dosage.maxDosePerAdministration`
| | | **`Dosage.maxDosePerLifetime`**| _Equivalent_<br/>(9381/9382)| `Dosage.maxDosePerLifetime`| _Equivalent_<br/>(20768/20769)| `Dosage.maxDosePerLifetime`| _Equivalent_<br/>(35883/35884)| `Dosage.maxDosePerLifetime`
| | | **`Dosage.rate[x]`**| _Equivalent_<br/>(1014/1496)| `Dosage.doseAndRate.rate[x]`| _Equivalent_<br/>(20762/20763)| `Dosage.doseAndRate.rate[x]`| _Equivalent_<br/>(35877/35878)| `Dosage.doseAndRate.rate[x]`
| | | *17 of 17 elements used* | | *17 of 22 elements used* <br/>remaining elements:<br/>`Dosage.doseAndRate`, `Dosage.doseAndRate.extension`, `Dosage.doseAndRate.id`, `Dosage.doseAndRate.type`, `Dosage.modifierExtension`| | *17 of 22 elements used* <br/>remaining elements:<br/>`Dosage.doseAndRate`, `Dosage.doseAndRate.extension`, `Dosage.doseAndRate.id`, `Dosage.doseAndRate.type`, `Dosage.modifierExtension`| | *18 of 23 elements used* <br/>remaining elements:<br/>`Dosage.doseAndRate`, `Dosage.doseAndRate.extension`, `Dosage.doseAndRate.id`, `Dosage.doseAndRate.type`, `Dosage.modifierExtension`

