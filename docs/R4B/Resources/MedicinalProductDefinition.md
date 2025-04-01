Comparison of 
Generated at Tuesday, April 1, 2025 1:39:30 PM

### MedicinalProductDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | MedicinalProductDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition` |
| Version | 4.3.0 |
| Description | Detailed definition of a medicinal product, typically for uses other than direct patient care (e.g. regulatory use, drug catalogs, to support prescribing, adverse events management etc.). |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1724` |
| Database Snapshot Count | `77` |
| Database Differential Count | `48` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MedicinalProductDefinition` | `MedicinalProductDefinition` | `MedicinalProductDefinition` | MedicinalProductDefinition | Detailed definition of a medicinal product | 0..* | MedicinalProductDefinition |  |  |
| `MedicinalProductDefinition.additionalMonitoringIndicator` | `MedicinalProductDefinition.additionalMonitoringIndicator` | `additionalMonitoringIndicator` | MedicinalProductDefinition.additionalMonitoringIndicator | Whether the Medicinal Product is subject to additional monitoring for regulatory reasons | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medicinal-product-additional-monitoring` |
| `MedicinalProductDefinition.attachedDocument` | `MedicinalProductDefinition.attachedDocument` | `attachedDocument` | MedicinalProductDefinition.attachedDocument | Additional documentation about the medicinal product | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `MedicinalProductDefinition.characteristic` | `MedicinalProductDefinition.characteristic` | `characteristic` | MedicinalProductDefinition.characteristic | Key product features such as "sugar free", "modified release" | 0..* | BackboneElement |  |  |
| `MedicinalProductDefinition.characteristic.extension` | `MedicinalProductDefinition.characteristic.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductDefinition.characteristic.id` | `MedicinalProductDefinition.characteristic.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductDefinition.characteristic.modifierExtension` | `MedicinalProductDefinition.characteristic.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductDefinition.characteristic.type` | `MedicinalProductDefinition.characteristic.type` | `type` | MedicinalProductDefinition.characteristic.type | A code expressing the type of characteristic | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/product-characteristic-codes` |
| `MedicinalProductDefinition.characteristic.value[x]` | `MedicinalProductDefinition.characteristic.value[x]` | `value[x]` | MedicinalProductDefinition.characteristic.value[x] | A value for the characteristic | 0..1 | Attachment, boolean, CodeableConcept, date, Quantity |  |  |
| `MedicinalProductDefinition.classification` | `MedicinalProductDefinition.classification` | `classification` | MedicinalProductDefinition.classification | Allows the product to be classified by various systems | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/product-classification-codes` |
| `MedicinalProductDefinition.clinicalTrial` | `MedicinalProductDefinition.clinicalTrial` | `clinicalTrial` | MedicinalProductDefinition.clinicalTrial | Clinical trials or studies that this product is involved in | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ResearchStudy) |  |  |
| `MedicinalProductDefinition.code` | `MedicinalProductDefinition.code` | `code` | MedicinalProductDefinition.code | A code that this product is known by, within some formal terminology | 0..* | Coding | `Example` | `http://hl7.org/fhir/ValueSet/medication-codes` |
| `MedicinalProductDefinition.combinedPharmaceuticalDoseForm` | `MedicinalProductDefinition.combinedPharmaceuticalDoseForm` | `combinedPharmaceuticalDoseForm` | MedicinalProductDefinition.combinedPharmaceuticalDoseForm | The dose form for a single part product, or combined form of a multiple part product | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/combined-dose-form` |
| `MedicinalProductDefinition.contact` | `MedicinalProductDefinition.contact` | `contact` | MedicinalProductDefinition.contact | A product specific contact, person (in a role), or an organization | 0..* | BackboneElement |  |  |
| `MedicinalProductDefinition.contact.contact` | `MedicinalProductDefinition.contact.contact` | `contact` | MedicinalProductDefinition.contact.contact | A product specific contact, person (in a role), or an organization | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `MedicinalProductDefinition.contact.extension` | `MedicinalProductDefinition.contact.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductDefinition.contact.id` | `MedicinalProductDefinition.contact.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductDefinition.contact.modifierExtension` | `MedicinalProductDefinition.contact.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductDefinition.contact.type` | `MedicinalProductDefinition.contact.type` | `type` | MedicinalProductDefinition.contact.type | Allows the contact to be classified, for example QPPV, Pharmacovigilance Enquiry Information | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medicinal-product-contact-type` |
| `MedicinalProductDefinition.contained` | `MedicinalProductDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MedicinalProductDefinition.crossReference` | `MedicinalProductDefinition.crossReference` | `crossReference` | MedicinalProductDefinition.crossReference | Reference to another product, e.g. for linking authorised to investigational product | 0..* | BackboneElement |  |  |
| `MedicinalProductDefinition.crossReference.extension` | `MedicinalProductDefinition.crossReference.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductDefinition.crossReference.id` | `MedicinalProductDefinition.crossReference.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductDefinition.crossReference.modifierExtension` | `MedicinalProductDefinition.crossReference.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductDefinition.crossReference.product` | `MedicinalProductDefinition.crossReference.product` | `product` | MedicinalProductDefinition.crossReference.product | Reference to another product, e.g. for linking authorised to investigational product | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition) |  |  |
| `MedicinalProductDefinition.crossReference.type` | `MedicinalProductDefinition.crossReference.type` | `type` | MedicinalProductDefinition.crossReference.type | The type of relationship, for instance branded to generic or virtual to actual product | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medicinal-product-cross-reference-type` |
| `MedicinalProductDefinition.description` | `MedicinalProductDefinition.description` | `description` | MedicinalProductDefinition.description | General description of this product | 0..1 | markdown |  |  |
| `MedicinalProductDefinition.domain` | `MedicinalProductDefinition.domain` | `domain` | MedicinalProductDefinition.domain | If this medicine applies to human or veterinary uses | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medicinal-product-domain` |
| `MedicinalProductDefinition.extension` | `MedicinalProductDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductDefinition.id` | `MedicinalProductDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MedicinalProductDefinition.identifier` | `MedicinalProductDefinition.identifier` | `identifier` | MedicinalProductDefinition.identifier | Business identifier for this product. Could be an MPID | 0..* | Identifier |  |  |
| `MedicinalProductDefinition.implicitRules` | `MedicinalProductDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MedicinalProductDefinition.impurity` | `MedicinalProductDefinition.impurity` | `impurity` | MedicinalProductDefinition.impurity | Any component of the drug product which is not the chemical entity defined as the drug substance, or an excipient in the drug product | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/SubstanceDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/substance-codes` |
| `MedicinalProductDefinition.indication` | `MedicinalProductDefinition.indication` | `indication` | MedicinalProductDefinition.indication | Description of indication(s) for this product, used when structured indications are not required | 0..1 | markdown |  |  |
| `MedicinalProductDefinition.ingredient` | `MedicinalProductDefinition.ingredient` | `ingredient` | MedicinalProductDefinition.ingredient | The ingredients of this medicinal product - when not detailed in other resources | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-codes` |
| `MedicinalProductDefinition.language` | `MedicinalProductDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `MedicinalProductDefinition.legalStatusOfSupply` | `MedicinalProductDefinition.legalStatusOfSupply` | `legalStatusOfSupply` | MedicinalProductDefinition.legalStatusOfSupply | The legal status of supply of the medicinal product as classified by the regulator | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/legal-status-of-supply` |
| `MedicinalProductDefinition.marketingStatus` | `MedicinalProductDefinition.marketingStatus` | `marketingStatus` | MedicinalProductDefinition.marketingStatus | Marketing status of the medicinal product, in contrast to marketing authorization | 0..* | MarketingStatus |  |  |
| `MedicinalProductDefinition.masterFile` | `MedicinalProductDefinition.masterFile` | `masterFile` | MedicinalProductDefinition.masterFile | A master file for the medicinal product (e.g. Pharmacovigilance System Master File) | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `MedicinalProductDefinition.meta` | `MedicinalProductDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MedicinalProductDefinition.modifierExtension` | `MedicinalProductDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicinalProductDefinition.name` | `MedicinalProductDefinition.name` | `name` | MedicinalProductDefinition.name | The product's name, including full name and possibly coded parts | 1..* | BackboneElement |  |  |
| `MedicinalProductDefinition.name.countryLanguage` | `MedicinalProductDefinition.name.countryLanguage` | `countryLanguage` | MedicinalProductDefinition.name.countryLanguage | Country and jurisdiction where the name applies | 0..* | BackboneElement |  |  |
| `MedicinalProductDefinition.name.countryLanguage.country` | `MedicinalProductDefinition.name.countryLanguage.country` | `country` | MedicinalProductDefinition.name.countryLanguage.country | Country code for where this name applies | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/country` |
| `MedicinalProductDefinition.name.countryLanguage.extension` | `MedicinalProductDefinition.name.countryLanguage.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductDefinition.name.countryLanguage.id` | `MedicinalProductDefinition.name.countryLanguage.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductDefinition.name.countryLanguage.jurisdiction` | `MedicinalProductDefinition.name.countryLanguage.jurisdiction` | `jurisdiction` | MedicinalProductDefinition.name.countryLanguage.jurisdiction | Jurisdiction code for where this name applies | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `MedicinalProductDefinition.name.countryLanguage.language` | `MedicinalProductDefinition.name.countryLanguage.language` | `language` | MedicinalProductDefinition.name.countryLanguage.language | Language code for this name | 1..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `MedicinalProductDefinition.name.countryLanguage.modifierExtension` | `MedicinalProductDefinition.name.countryLanguage.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductDefinition.name.extension` | `MedicinalProductDefinition.name.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductDefinition.name.id` | `MedicinalProductDefinition.name.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductDefinition.name.modifierExtension` | `MedicinalProductDefinition.name.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductDefinition.name.namePart` | `MedicinalProductDefinition.name.namePart` | `namePart` | MedicinalProductDefinition.name.namePart | Coding words or phrases of the name | 0..* | BackboneElement |  |  |
| `MedicinalProductDefinition.name.namePart.extension` | `MedicinalProductDefinition.name.namePart.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductDefinition.name.namePart.id` | `MedicinalProductDefinition.name.namePart.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductDefinition.name.namePart.modifierExtension` | `MedicinalProductDefinition.name.namePart.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductDefinition.name.namePart.part` | `MedicinalProductDefinition.name.namePart.part` | `part` | MedicinalProductDefinition.name.namePart.part | A fragment of a product name | 1..1 | string |  |  |
| `MedicinalProductDefinition.name.namePart.type` | `MedicinalProductDefinition.name.namePart.type` | `type` | MedicinalProductDefinition.name.namePart.type | Identifying type for this part of the name (e.g. strength part) | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medicinal-product-name-part-type` |
| `MedicinalProductDefinition.name.productName` | `MedicinalProductDefinition.name.productName` | `productName` | MedicinalProductDefinition.name.productName | The full product name | 1..1 | string |  |  |
| `MedicinalProductDefinition.name.type` | `MedicinalProductDefinition.name.type` | `type` | MedicinalProductDefinition.name.type | Type of product name, such as rINN, BAN, Proprietary, Non-Proprietary | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medicinal-product-name-type` |
| `MedicinalProductDefinition.operation` | `MedicinalProductDefinition.operation` | `operation` | MedicinalProductDefinition.operation | A manufacturing or administrative process for the medicinal product | 0..* | BackboneElement |  |  |
| `MedicinalProductDefinition.operation.confidentialityIndicator` | `MedicinalProductDefinition.operation.confidentialityIndicator` | `confidentialityIndicator` | MedicinalProductDefinition.operation.confidentialityIndicator | Specifies whether this process is considered proprietary or confidential | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medicinal-product-confidentiality` |
| `MedicinalProductDefinition.operation.effectiveDate` | `MedicinalProductDefinition.operation.effectiveDate` | `effectiveDate` | MedicinalProductDefinition.operation.effectiveDate | Date range of applicability | 0..1 | Period |  |  |
| `MedicinalProductDefinition.operation.extension` | `MedicinalProductDefinition.operation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductDefinition.operation.id` | `MedicinalProductDefinition.operation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductDefinition.operation.modifierExtension` | `MedicinalProductDefinition.operation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductDefinition.operation.organization` | `MedicinalProductDefinition.operation.organization` | `organization` | MedicinalProductDefinition.operation.organization | The organization responsible for the particular process, e.g. the manufacturer or importer | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `MedicinalProductDefinition.operation.type` | `MedicinalProductDefinition.operation.type` | `type` | MedicinalProductDefinition.operation.type | The type of manufacturing operation e.g. manufacturing itself, re-packaging | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/ActivityDefinition), CodeableReference(http://hl7.org/fhir/StructureDefinition/PlanDefinition) |  |  |
| `MedicinalProductDefinition.packagedMedicinalProduct` | `MedicinalProductDefinition.packagedMedicinalProduct` | `packagedMedicinalProduct` | MedicinalProductDefinition.packagedMedicinalProduct | Package type for the product | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medicinal-product-package-type` |
| `MedicinalProductDefinition.pediatricUseIndicator` | `MedicinalProductDefinition.pediatricUseIndicator` | `pediatricUseIndicator` | MedicinalProductDefinition.pediatricUseIndicator | If authorised for use in children | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medicinal-product-pediatric-use` |
| `MedicinalProductDefinition.route` | `MedicinalProductDefinition.route` | `route` | MedicinalProductDefinition.route | The path by which the product is taken into or makes contact with the body | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/route-codes` |
| `MedicinalProductDefinition.specialMeasures` | `MedicinalProductDefinition.specialMeasures` | `specialMeasures` | MedicinalProductDefinition.specialMeasures | Whether the Medicinal Product is subject to special measures for regulatory reasons | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medicinal-product-special-measures` |
| `MedicinalProductDefinition.status` | `MedicinalProductDefinition.status` | `status` | MedicinalProductDefinition.status | The status within the lifecycle of this product record | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `MedicinalProductDefinition.statusDate` | `MedicinalProductDefinition.statusDate` | `statusDate` | MedicinalProductDefinition.statusDate | The date at which the given status became applicable | 0..1 | dateTime |  |  |
| `MedicinalProductDefinition.text` | `MedicinalProductDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `MedicinalProductDefinition.type` | `MedicinalProductDefinition.type` | `type` | MedicinalProductDefinition.type | Regulatory type, e.g. Investigational or Authorized | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medicinal-product-type` |
| `MedicinalProductDefinition.version` | `MedicinalProductDefinition.version` | `version` | MedicinalProductDefinition.version | A business identifier relating to a specific version of the product | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [MedicinalProductDefinition](/docs/R4B/Resources/MedicinalProductDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1008`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1237`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicinalProductDefinition](/docs/R5/Resources/MedicinalProductDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition MedicinalProductDefinition from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B MedicinalProductDefinition| Relationship | [R5 MedicinalProductDefinition](/docs/R5/Resources/MedicinalProductDefinition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | **`MedicinalProductDefinition`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44757)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44758)| `MedicinalProductDefinition`
| | | | | | | **`MedicinalProductDefinition.id`**| _Equivalent_<br/>(44759/44760)| `MedicinalProductDefinition.id`
| | | | | | | **`MedicinalProductDefinition.meta`**| _Equivalent_<br/>(44761/44762)| `MedicinalProductDefinition.meta`
| | | | | | | **`MedicinalProductDefinition.implicitRules`**| _Equivalent_<br/>(44763/44764)| `MedicinalProductDefinition.implicitRules`
| | | | | | | **`MedicinalProductDefinition.language`**| _Equivalent_<br/>(44765/44766)| `MedicinalProductDefinition.language`
| | | | | | | **`MedicinalProductDefinition.text`**| _Equivalent_<br/>(44767/44768)| `MedicinalProductDefinition.text`
| | | | | | | **`MedicinalProductDefinition.contained`**| _Equivalent_<br/>(44769/44770)| `MedicinalProductDefinition.contained`
| | | | | | | **`MedicinalProductDefinition.extension`**| _Equivalent_<br/>(44771/44772)| `MedicinalProductDefinition.extension`
| | | | | | | **`MedicinalProductDefinition.modifierExtension`**| _Equivalent_<br/>(44773/44774)| `MedicinalProductDefinition.modifierExtension`
| | | | | | | **`MedicinalProductDefinition.identifier`**| _Equivalent_<br/>(44775/44776)| `MedicinalProductDefinition.identifier`
| | | | | | | **`MedicinalProductDefinition.type`**| _Equivalent_<br/>(44777/44778)| `MedicinalProductDefinition.type`
| | | | | | | **`MedicinalProductDefinition.domain`**| _Equivalent_<br/>(44779/44780)| `MedicinalProductDefinition.domain`
| | | | | | | **`MedicinalProductDefinition.version`**| _Equivalent_<br/>(44781/44782)| `MedicinalProductDefinition.version`
| | | | | | | **`MedicinalProductDefinition.status`**| _Equivalent_<br/>(44783/44784)| `MedicinalProductDefinition.status`
| | | | | | | **`MedicinalProductDefinition.statusDate`**| _Equivalent_<br/>(44785/44786)| `MedicinalProductDefinition.statusDate`
| | | | | | | **`MedicinalProductDefinition.description`**| _Equivalent_<br/>(44787/44788)| `MedicinalProductDefinition.description`
| | | | | | | **`MedicinalProductDefinition.combinedPharmaceuticalDoseForm`**| _Equivalent_<br/>(44789/44790)| `MedicinalProductDefinition.combinedPharmaceuticalDoseForm`
| | | | | | | **`MedicinalProductDefinition.route`**| _Equivalent_<br/>(44791/44792)| `MedicinalProductDefinition.route`
| | | | | | | **`MedicinalProductDefinition.indication`**| _Equivalent_<br/>(44793/44794)| `MedicinalProductDefinition.indication`
| | | | | | | **`MedicinalProductDefinition.legalStatusOfSupply`**| _Equivalent_<br/>(44795/44796)| `MedicinalProductDefinition.legalStatusOfSupply`
| | | | | | | **`MedicinalProductDefinition.additionalMonitoringIndicator`**| _Equivalent_<br/>(44797/44798)| `MedicinalProductDefinition.additionalMonitoringIndicator`
| | | | | | | **`MedicinalProductDefinition.specialMeasures`**| _Equivalent_<br/>(44799/44800)| `MedicinalProductDefinition.specialMeasures`
| | | | | | | **`MedicinalProductDefinition.pediatricUseIndicator`**| _Equivalent_<br/>(44801/44802)| `MedicinalProductDefinition.pediatricUseIndicator`
| | | | | | | **`MedicinalProductDefinition.classification`**| _Equivalent_<br/>(44803/44804)| `MedicinalProductDefinition.classification`
| | | | | | | **`MedicinalProductDefinition.marketingStatus`**| _Equivalent_<br/>(44805/44806)| `MedicinalProductDefinition.marketingStatus`
| | | | | | | **`MedicinalProductDefinition.packagedMedicinalProduct`**| _Equivalent_<br/>(44807/44808)| `MedicinalProductDefinition.packagedMedicinalProduct`
| | | | | | | **`MedicinalProductDefinition.ingredient`**| _Equivalent_<br/>(44809/44810)| `MedicinalProductDefinition.ingredient`
| | | | | | | **`MedicinalProductDefinition.impurity`**| _Equivalent_<br/>(44811/44812)| `MedicinalProductDefinition.impurity`
| | | | | | | **`MedicinalProductDefinition.attachedDocument`**| _Equivalent_<br/>(44813/44814)| `MedicinalProductDefinition.attachedDocument`
| | | | | | | **`MedicinalProductDefinition.masterFile`**| _Equivalent_<br/>(44815/44816)| `MedicinalProductDefinition.masterFile`
| | | | | | | **`MedicinalProductDefinition.contact`**| _Equivalent_<br/>(44817/44818)| `MedicinalProductDefinition.contact`
| | | | | | | **`MedicinalProductDefinition.contact.id`**| _Equivalent_<br/>(44819/44820)| `MedicinalProductDefinition.contact.id`
| | | | | | | **`MedicinalProductDefinition.contact.extension`**| _Equivalent_<br/>(44821/44822)| `MedicinalProductDefinition.contact.extension`
| | | | | | | **`MedicinalProductDefinition.contact.modifierExtension`**| _Equivalent_<br/>(44823/44824)| `MedicinalProductDefinition.contact.modifierExtension`
| | | | | | | **`MedicinalProductDefinition.contact.type`**| _Equivalent_<br/>(44825/44826)| `MedicinalProductDefinition.contact.type`
| | | | | | | **`MedicinalProductDefinition.contact.contact`**| _Equivalent_<br/>(44827/44828)| `MedicinalProductDefinition.contact.contact`
| | | | | | | **`MedicinalProductDefinition.clinicalTrial`**| _Equivalent_<br/>(44829/44830)| `MedicinalProductDefinition.clinicalTrial`
| | | | | | | **`MedicinalProductDefinition.code`**| _Equivalent_<br/>(44831/44832)| `MedicinalProductDefinition.code`
| | | | | | | **`MedicinalProductDefinition.name`**| _Equivalent_<br/>(44833/44834)| `MedicinalProductDefinition.name`
| | | | | | | **`MedicinalProductDefinition.name.id`**| _Equivalent_<br/>(44835/44836)| `MedicinalProductDefinition.name.id`
| | | | | | | **`MedicinalProductDefinition.name.extension`**| _Equivalent_<br/>(44837/44838)| `MedicinalProductDefinition.name.extension`
| | | | | | | **`MedicinalProductDefinition.name.modifierExtension`**| _Equivalent_<br/>(44839/44840)| `MedicinalProductDefinition.name.modifierExtension`
| | | | | | | **`MedicinalProductDefinition.name.productName`**| _Equivalent_<br/>(44841/44842)| `MedicinalProductDefinition.name.productName`
| | | | | | | **`MedicinalProductDefinition.name.type`**| _Equivalent_<br/>(44843/44844)| `MedicinalProductDefinition.name.type`
| | | | | | | **`MedicinalProductDefinition.name.namePart`**| | | 
| | | | | | | **`MedicinalProductDefinition.name.namePart.id`**| | | 
| | | | | | | **`MedicinalProductDefinition.name.namePart.extension`**| | | 
| | | | | | | **`MedicinalProductDefinition.name.namePart.modifierExtension`**| | | 
| | | | | | | **`MedicinalProductDefinition.name.namePart.part`**| _Equivalent_<br/>(1889/2130)| `MedicinalProductDefinition.name.part.part`
| | | | | | | **`MedicinalProductDefinition.name.namePart.type`**| _Equivalent_<br/>(1890/2131)| `MedicinalProductDefinition.name.part.type`
| | | | | | | **`MedicinalProductDefinition.name.countryLanguage`**| | | 
| | | | | | | **`MedicinalProductDefinition.name.countryLanguage.id`**| | | 
| | | | | | | **`MedicinalProductDefinition.name.countryLanguage.extension`**| | | 
| | | | | | | **`MedicinalProductDefinition.name.countryLanguage.modifierExtension`**| | | 
| | | | | | | **`MedicinalProductDefinition.name.countryLanguage.country`**| _Equivalent_<br/>(1891/2132)| `MedicinalProductDefinition.name.usage.country`
| | | | | | | **`MedicinalProductDefinition.name.countryLanguage.jurisdiction`**| _Equivalent_<br/>(1892/2133)| `MedicinalProductDefinition.name.usage.jurisdiction`
| | | | | | | **`MedicinalProductDefinition.name.countryLanguage.language`**| _Equivalent_<br/>(1893/2134)| `MedicinalProductDefinition.name.usage.language`
| | | | | | | **`MedicinalProductDefinition.crossReference`**| _Equivalent_<br/>(44853/44854)| `MedicinalProductDefinition.crossReference`
| | | | | | | **`MedicinalProductDefinition.crossReference.id`**| _Equivalent_<br/>(44855/44856)| `MedicinalProductDefinition.crossReference.id`
| | | | | | | **`MedicinalProductDefinition.crossReference.extension`**| _Equivalent_<br/>(44857/44858)| `MedicinalProductDefinition.crossReference.extension`
| | | | | | | **`MedicinalProductDefinition.crossReference.modifierExtension`**| _Equivalent_<br/>(44859/44860)| `MedicinalProductDefinition.crossReference.modifierExtension`
| | | | | | | **`MedicinalProductDefinition.crossReference.product`**| _Equivalent_<br/>(44861/44862)| `MedicinalProductDefinition.crossReference.product`
| | | | | | | **`MedicinalProductDefinition.crossReference.type`**| _Equivalent_<br/>(44863/44864)| `MedicinalProductDefinition.crossReference.type`
| | | | | | | **`MedicinalProductDefinition.operation`**| _Equivalent_<br/>(44865/44866)| `MedicinalProductDefinition.operation`
| | | | | | | **`MedicinalProductDefinition.operation.id`**| _Equivalent_<br/>(44867/44868)| `MedicinalProductDefinition.operation.id`
| | | | | | | **`MedicinalProductDefinition.operation.extension`**| _Equivalent_<br/>(44869/44870)| `MedicinalProductDefinition.operation.extension`
| | | | | | | **`MedicinalProductDefinition.operation.modifierExtension`**| _Equivalent_<br/>(44871/44872)| `MedicinalProductDefinition.operation.modifierExtension`
| | | | | | | **`MedicinalProductDefinition.operation.type`**| _Equivalent_<br/>(44873/44874)| `MedicinalProductDefinition.operation.type`
| | | | | | | **`MedicinalProductDefinition.operation.effectiveDate`**| _Equivalent_<br/>(44875/44876)| `MedicinalProductDefinition.operation.effectiveDate`
| | | | | | | **`MedicinalProductDefinition.operation.organization`**| _Equivalent_<br/>(44877/44878)| `MedicinalProductDefinition.operation.organization`
| | | | | | | **`MedicinalProductDefinition.operation.confidentialityIndicator`**| _Equivalent_<br/>(44879/44880)| `MedicinalProductDefinition.operation.confidentialityIndicator`
| | | | | | | **`MedicinalProductDefinition.characteristic`**| _Equivalent_<br/>(44881/44882)| `MedicinalProductDefinition.characteristic`
| | | | | | | **`MedicinalProductDefinition.characteristic.id`**| _Equivalent_<br/>(44883/44884)| `MedicinalProductDefinition.characteristic.id`
| | | | | | | **`MedicinalProductDefinition.characteristic.extension`**| _Equivalent_<br/>(44885/44886)| `MedicinalProductDefinition.characteristic.extension`
| | | | | | | **`MedicinalProductDefinition.characteristic.modifierExtension`**| _Equivalent_<br/>(44887/44888)| `MedicinalProductDefinition.characteristic.modifierExtension`
| | | | | | | **`MedicinalProductDefinition.characteristic.type`**| _Equivalent_<br/>(44889/44890)| `MedicinalProductDefinition.characteristic.type`
| | | | | | | **`MedicinalProductDefinition.characteristic.value[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44891)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44892)| `MedicinalProductDefinition.characteristic.value[x]`
| | | | | | | *77 of 77 elements used* | | *69 of 78 elements used* 

