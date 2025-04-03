Comparison of 
Generated at Thursday, April 3, 2025 8:18:06 AM

### MedicationStatement

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | MedicationStatement |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MedicationStatement` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for MedicationStatement Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `98` |
| Database Snapshot Count | `34` |
| Database Differential Count | `23` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MedicationStatement` | `MedicationStatement` | `MedicationStatement` | MedicationStatement | Record of medication being taken by a patient | 0..* | MedicationStatement |  |  |
| `MedicationStatement.contained` | `MedicationStatement.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MedicationStatement.dateAsserted` | `MedicationStatement.dateAsserted` | `dateAsserted` |  | When the statement was asserted? | 0..1 | dateTime |  |  |
| `MedicationStatement.dosage` | `MedicationStatement.dosage` | `dosage` |  | Details of how medication was taken | 0..* | BackboneElement |  |  |
| `MedicationStatement.dosage.asNeeded[x]` | `MedicationStatement.dosage.asNeeded[x]` | `asNeeded[x]` |  | Take "as needed" (for x) | 0..1 | boolean, CodeableConcept | `Example` |  |
| `MedicationStatement.dosage.extension` | `MedicationStatement.dosage.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `MedicationStatement.dosage.id` | `MedicationStatement.dosage.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `MedicationStatement.dosage.maxDosePerPeriod` | `MedicationStatement.dosage.maxDosePerPeriod` | `maxDosePerPeriod` |  | Maximum dose that was consumed per unit of time | 0..1 | Ratio |  |  |
| `MedicationStatement.dosage.method` | `MedicationStatement.dosage.method` | `method` |  | Technique used to administer medication | 0..1 | CodeableConcept | `Example` |  |
| `MedicationStatement.dosage.modifierExtension` | `MedicationStatement.dosage.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicationStatement.dosage.quantity[x]` | `MedicationStatement.dosage.quantity[x]` | `quantity[x]` |  | Amount administered in one dose | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity], Range |  |  |
| `MedicationStatement.dosage.rate[x]` | `MedicationStatement.dosage.rate[x]` | `rate[x]` |  | Dose quantity per unit of time | 0..1 | Range, Ratio |  |  |
| `MedicationStatement.dosage.route` | `MedicationStatement.dosage.route` | `route` |  | How the medication entered the body | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/route-codes` |
| `MedicationStatement.dosage.site[x]` | `MedicationStatement.dosage.site[x]` | `site[x]` |  | Where (on body) medication is/was administered | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/BodySite) | `Example` | `http://hl7.org/fhir/ValueSet/approach-site-codes` |
| `MedicationStatement.dosage.text` | `MedicationStatement.dosage.text` | `text` |  | Reported dosage information | 0..1 | string |  |  |
| `MedicationStatement.dosage.timing` | `MedicationStatement.dosage.timing` | `timing` |  | When/how often was medication taken | 0..1 | Timing |  |  |
| `MedicationStatement.effective[x]` | `MedicationStatement.effective[x]` | `effective[x]` |  | Over what period was medication consumed? | 0..1 | dateTime, Period |  |  |
| `MedicationStatement.extension` | `MedicationStatement.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `MedicationStatement.id` | `MedicationStatement.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MedicationStatement.identifier` | `MedicationStatement.identifier` | `identifier` |  | External identifier | 0..* | Identifier |  |  |
| `MedicationStatement.implicitRules` | `MedicationStatement.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MedicationStatement.informationSource` | `MedicationStatement.informationSource` | `informationSource` |  |  | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `MedicationStatement.language` | `MedicationStatement.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `MedicationStatement.medication[x]` | `MedicationStatement.medication[x]` | `medication[x]` |  | What medication was taken | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Medication) |  |  |
| `MedicationStatement.meta` | `MedicationStatement.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MedicationStatement.modifierExtension` | `MedicationStatement.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicationStatement.note` | `MedicationStatement.note` | `note` |  | Further information about the statement | 0..1 | string |  |  |
| `MedicationStatement.patient` | `MedicationStatement.patient` | `patient` |  | Who is/was taking  the medication | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `MedicationStatement.reasonForUse[x]` | `MedicationStatement.reasonForUse[x]` | `reasonForUse[x]` |  |  | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Condition) | `Example` | `http://hl7.org/fhir/ValueSet/condition-code` |
| `MedicationStatement.reasonNotTaken` | `MedicationStatement.reasonNotTaken` | `reasonNotTaken` |  | True if asserting medication was not given | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/reason-medication-not-given-codes` |
| `MedicationStatement.status` | `MedicationStatement.status` | `status` |  | active \| completed \| entered-in-error \| intended | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/medication-statement-status` |
| `MedicationStatement.supportingInformation` | `MedicationStatement.supportingInformation` | `supportingInformation` |  | Additional supporting information | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `MedicationStatement.text` | `MedicationStatement.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `MedicationStatement.wasNotTaken` | `MedicationStatement.wasNotTaken` | `wasNotTaken` |  | True if medication is/was not being taken | 0..1 | boolean |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [MedicationStatement](/docs/R2/Resources/MedicationStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationStatement\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `128`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `294`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationStatement](/docs/R3/Resources/MedicationStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationStatement\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `483`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `677`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationStatement](/docs/R4/Resources/MedicationStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationStatement\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1545`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1546`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationStatement](/docs/R4B/Resources/MedicationStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationStatement\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1007`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1236`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationStatement](/docs/R5/Resources/MedicationStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationStatement\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition MedicationStatement from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 MedicationStatement| Relationship | [R3 MedicationStatement](/docs/R3/Resources/MedicationStatement.md)| Relationship | [R4 MedicationStatement](/docs/R4/Resources/MedicationStatement.md)| Relationship | [R4B MedicationStatement](/docs/R4B/Resources/MedicationStatement.md)| Relationship | [R5 MedicationStatement](/docs/R5/Resources/MedicationStatement.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`MedicationStatement`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(6303)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6304)| `MedicationStatement`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(16055)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(16056)| `MedicationStatement`| _Equivalent_<br/>(30053/30054)| `MedicationStatement`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44715)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44716)| `MedicationStatement`
| **`MedicationStatement.id`**| _Equivalent_<br/>(6305/6306)| `MedicationStatement.id`| _Equivalent_<br/>(16057/16058)| `MedicationStatement.id`| _Equivalent_<br/>(30055/30056)| `MedicationStatement.id`| _Equivalent_<br/>(44717/44718)| `MedicationStatement.id`
| **`MedicationStatement.meta`**| _Equivalent_<br/>(6307/6308)| `MedicationStatement.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16059)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16060)| `MedicationStatement.meta`| _Equivalent_<br/>(30057/30058)| `MedicationStatement.meta`| _Equivalent_<br/>(44719/44720)| `MedicationStatement.meta`
| **`MedicationStatement.implicitRules`**| _Equivalent_<br/>(6309/6310)| `MedicationStatement.implicitRules`| _Equivalent_<br/>(16061/16062)| `MedicationStatement.implicitRules`| _Equivalent_<br/>(30059/30060)| `MedicationStatement.implicitRules`| _Equivalent_<br/>(44721/44722)| `MedicationStatement.implicitRules`
| **`MedicationStatement.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6311)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6312)| `MedicationStatement.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16063)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(16064)| `MedicationStatement.language`| _Equivalent_<br/>(30061/30062)| `MedicationStatement.language`| _Equivalent_<br/>(44723/44724)| `MedicationStatement.language`
| **`MedicationStatement.text`**| _Equivalent_<br/>(6313/6314)| `MedicationStatement.text`| _Equivalent_<br/>(16065/16066)| `MedicationStatement.text`| _Equivalent_<br/>(30063/30064)| `MedicationStatement.text`| _Equivalent_<br/>(44725/44726)| `MedicationStatement.text`
| **`MedicationStatement.contained`**| _Equivalent_<br/>(6315/6316)| `MedicationStatement.contained`| _Equivalent_<br/>(16067/16068)| `MedicationStatement.contained`| _Equivalent_<br/>(30065/30066)| `MedicationStatement.contained`| _Equivalent_<br/>(44727/44728)| `MedicationStatement.contained`
| **`MedicationStatement.extension`**| _Equivalent_<br/>(6317/6318)| `MedicationStatement.extension`| →→→→ _Equivalent_ →→→→ <br/>(16069)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16070)| `MedicationStatement.extension`| _Equivalent_<br/>(30067/30068)| `MedicationStatement.extension`| _Equivalent_<br/>(44729/44730)| `MedicationStatement.extension`
| **`MedicationStatement.modifierExtension`**| _Equivalent_<br/>(6319/6320)| `MedicationStatement.modifierExtension`| _Equivalent_<br/>(16071/16072)| `MedicationStatement.modifierExtension`| _Equivalent_<br/>(30069/30070)| `MedicationStatement.modifierExtension`| _Equivalent_<br/>(44731/44732)| `MedicationStatement.modifierExtension`
| **`MedicationStatement.identifier`**| _Equivalent_<br/>(6321/6322)| `MedicationStatement.identifier`| _Equivalent_<br/>(16073/16074)| `MedicationStatement.identifier`| _Equivalent_<br/>(30071/30072)| `MedicationStatement.identifier`| _Equivalent_<br/>(44733/44734)| `MedicationStatement.identifier`
| **`MedicationStatement.patient`**| →→→→ _RelatedTo_ →→→→ <br/>(291)<hr/>←←←← _RelatedTo_ ←←←← <br/>(670)| `MedicationStatement.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16092)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16093)| `MedicationStatement.subject`| _Equivalent_<br/>(30085/30086)| `MedicationStatement.subject`| _Equivalent_<br/>(44743/44744)| `MedicationStatement.subject`
| **`MedicationStatement.informationSource`**| →→→→ _RelatedTo_ →→→→ <br/>(6323)<hr/>←←←← _RelatedTo_ ←←←← <br/>(6324)| `MedicationStatement.informationSource`| →→→→ _RelatedTo_ →→→→ <br/>(16090)<hr/>←←←← _RelatedTo_ ←←←← <br/>(16091)| `MedicationStatement.informationSource`| _Equivalent_<br/>(30093/30094)| `MedicationStatement.informationSource`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44749)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44750)| `MedicationStatement.informationSource`
| **`MedicationStatement.dateAsserted`**| _Equivalent_<br/>(6325/6326)| `MedicationStatement.dateAsserted`| _Equivalent_<br/>(16088/16089)| `MedicationStatement.dateAsserted`| _Equivalent_<br/>(30091/30092)| `MedicationStatement.dateAsserted`| _Equivalent_<br/>(44747/44748)| `MedicationStatement.dateAsserted`
| **`MedicationStatement.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6327)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6328)| `MedicationStatement.status`| →→→→ _Equivalent_ →→→→ <br/>(30051)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(30050)| `MedicationStatement.extension`| _Equivalent_<br/>(30067/30068)| `MedicationStatement.extension`| _Equivalent_<br/>(44729/44730)| `MedicationStatement.extension`
| **`MedicationStatement.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6327)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6328)| `MedicationStatement.status`| →→→→ _Equivalent_ →→→→ <br/>(30051)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(30050)| `MedicationStatement.status`| _Equivalent_<br/>(30077/30078)| `MedicationStatement.status`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(44738)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(44739)| `MedicationStatement.status`
| **`MedicationStatement.wasNotTaken`**| →→→→ _Equivalent_ →→→→ <br/>(16054)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(671)| `base64Binary`| | | | | | | 
| **`MedicationStatement.wasNotTaken`**| →→→→ _Equivalent_ →→→→ <br/>(16054)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(671)| `MedicationStatement.taken`| | | | | | | 
| **`MedicationStatement.reasonNotTaken`**| _Equivalent_<br/>(6329/6330)| `MedicationStatement.reasonNotTaken`| _Equivalent_<br/>(1195/1608)| `MedicationStatement.reasonCode`| _Equivalent_<br/>(30097/30098)| `MedicationStatement.reasonCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1842)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2085)| `MedicationStatement.reason`
| **`MedicationStatement.reasonForUse[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(293)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(672)| `MedicationStatement.reasonCode`| →→→→ _Equivalent_ →→→→ <br/>(16096)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16097)| `MedicationStatement.reasonCode`| _Equivalent_<br/>(30097/30098)| `MedicationStatement.reasonCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1842)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2085)| `MedicationStatement.reason`
| **`MedicationStatement.reasonForUse[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(293)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(672)| `MedicationStatement.reasonReference`| →→→→ _RelatedTo_ →→→→ <br/>(16098)<hr/>←←←← _RelatedTo_ ←←←← <br/>(16099)| `MedicationStatement.reasonReference`| _Equivalent_<br/>(30099/30100)| `MedicationStatement.reasonReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1843)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2086)| `MedicationStatement.reason`
| **`MedicationStatement.effective[x]`**| _Equivalent_<br/>(6331/6332)| `MedicationStatement.effective[x]`| _Equivalent_<br/>(16086/16087)| `MedicationStatement.effective[x]`| _Equivalent_<br/>(30089/30090)| `MedicationStatement.effective[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44745)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44746)| `MedicationStatement.effective[x]`
| **`MedicationStatement.note`**| →→→→ _RelatedTo_ →→→→ <br/>(6333)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6334)| `MedicationStatement.note`| _Equivalent_<br/>(16100/16101)| `MedicationStatement.note`| _Equivalent_<br/>(30101/30102)| `MedicationStatement.note`| _Equivalent_<br/>(44753/44754)| `MedicationStatement.note`
| **`MedicationStatement.supportingInformation`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(294)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(668)| `MedicationStatement.derivedFrom`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16094)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16095)| `MedicationStatement.derivedFrom`| _Equivalent_<br/>(30095/30096)| `MedicationStatement.derivedFrom`| _Equivalent_<br/>(44751/44752)| `MedicationStatement.derivedFrom`
| **`MedicationStatement.medication[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(6335)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6336)| `MedicationStatement.medication[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16084)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16085)| `MedicationStatement.medication[x]`| _Equivalent_<br/>(30083/30084)| `MedicationStatement.medication[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1840)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2083)| `MedicationStatement.medication`
| **`MedicationStatement.dosage`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(6337)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6338)| `MedicationStatement.dosage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16102)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16103)| `MedicationStatement.dosage`| _Equivalent_<br/>(30103/30104)| `MedicationStatement.dosage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44755)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44756)| `MedicationStatement.dosage`
| **`MedicationStatement.dosage.id`**| | | | | | | | | 
| **`MedicationStatement.dosage.extension`**| | | | | | | | | 
| **`MedicationStatement.dosage.modifierExtension`**| | | | | | | | | 
| **`MedicationStatement.dosage.text`**| | | | | | | | | 
| **`MedicationStatement.dosage.timing`**| | | | | | | | | 
| **`MedicationStatement.dosage.asNeeded[x]`**| | | | | | | | | 
| **`MedicationStatement.dosage.site[x]`**| | | | | | | | | 
| **`MedicationStatement.dosage.route`**| | | | | | | | | 
| **`MedicationStatement.dosage.method`**| | | | | | | | | 
| **`MedicationStatement.dosage.quantity[x]`**| | | | | | | | | 
| **`MedicationStatement.dosage.rate[x]`**| | | | | | | | | 
| **`MedicationStatement.dosage.maxDosePerPeriod`**| | | | | | | | | 
| *34 of 34 elements used* | | *24 of 27 elements used* <br/>remaining elements:<br/>`MedicationStatement.basedOn`, `MedicationStatement.category`, `MedicationStatement.context`, `MedicationStatement.partOf`| | *21 of 26 elements used* <br/>remaining elements:<br/>`MedicationStatement.basedOn`, `MedicationStatement.category`, `MedicationStatement.context`, `MedicationStatement.partOf`, `MedicationStatement.statusReason`| | *21 of 26 elements used* <br/>remaining elements:<br/>`MedicationStatement.basedOn`, `MedicationStatement.category`, `MedicationStatement.context`, `MedicationStatement.partOf`, `MedicationStatement.statusReason`| | *20 of 31 elements used* <br/>remaining elements:<br/>`MedicationStatement.adherence`, `MedicationStatement.adherence.code`, `MedicationStatement.adherence.extension`, `MedicationStatement.adherence.id`, `MedicationStatement.adherence.modifierExtension`, `MedicationStatement.adherence.reason`, `MedicationStatement.category`, `MedicationStatement.encounter`, `MedicationStatement.partOf`, `MedicationStatement.relatedClinicalInformation`, `MedicationStatement.renderedDosageInstruction`

