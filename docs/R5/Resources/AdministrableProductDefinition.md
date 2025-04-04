Comparison of 
Generated at Friday, April 4, 2025 2:59:01 PM

### AdministrableProductDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | AdministrableProductDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/AdministrableProductDefinition` |
| Version | 5.0.0 |
| Description | A medicinal product in the final form which is suitable for administering to a patient (after any mixing of multiple components, dissolution etc. has been performed). |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2251` |
| Database Snapshot Count | `47` |
| Database Differential Count | `27` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `AdministrableProductDefinition` | `AdministrableProductDefinition` | `AdministrableProductDefinition` | AdministrableProductDefinition | A medicinal product in the final form, suitable for administration - after any mixing of multiple components | 0..* | AdministrableProductDefinition |  |  |
| `AdministrableProductDefinition.administrableDoseForm` | `AdministrableProductDefinition.administrableDoseForm` | `administrableDoseForm` | AdministrableProductDefinition.administrableDoseForm | The dose form of the final product after necessary reconstitution or processing | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/administrable-dose-form` |
| `AdministrableProductDefinition.contained` | `AdministrableProductDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `AdministrableProductDefinition.description` | `AdministrableProductDefinition.description` | `description` | AdministrableProductDefinition.description | A general description of the product, when in its final form, suitable for administration e.g. effervescent blue liquid, to be swallowed | 0..1 | markdown |  |  |
| `AdministrableProductDefinition.device` | `AdministrableProductDefinition.device` | `device` | AdministrableProductDefinition.device | A device that is integral to the medicinal product, in effect being considered as an "ingredient" of the medicinal product | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition) |  |  |
| `AdministrableProductDefinition.extension` | `AdministrableProductDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AdministrableProductDefinition.formOf` | `AdministrableProductDefinition.formOf` | `formOf` | AdministrableProductDefinition.formOf | References a product from which one or more of the constituent parts of that product can be prepared and used as described by this administrable product | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition) |  |  |
| `AdministrableProductDefinition.id` | `AdministrableProductDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `AdministrableProductDefinition.identifier` | `AdministrableProductDefinition.identifier` | `identifier` | AdministrableProductDefinition.identifier | An identifier for the administrable product | 0..* | Identifier |  |  |
| `AdministrableProductDefinition.implicitRules` | `AdministrableProductDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `AdministrableProductDefinition.ingredient` | `AdministrableProductDefinition.ingredient` | `ingredient` | AdministrableProductDefinition.ingredient | The ingredients of this administrable medicinal product. This is only needed if the ingredients are not specified either using ManufacturedItemDefiniton, or using by incoming references from the Ingredient resource | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-codes` |
| `AdministrableProductDefinition.language` | `AdministrableProductDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `AdministrableProductDefinition.meta` | `AdministrableProductDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `AdministrableProductDefinition.modifierExtension` | `AdministrableProductDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `AdministrableProductDefinition.producedFrom` | `AdministrableProductDefinition.producedFrom` | `producedFrom` | AdministrableProductDefinition.producedFrom | Indicates the specific manufactured items that are part of the 'formOf' product that are used in the preparation of this specific administrable form | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ManufacturedItemDefinition) |  |  |
| `AdministrableProductDefinition.property` | `AdministrableProductDefinition.property` | `property` | AdministrableProductDefinition.property | Characteristics e.g. a product's onset of action | 0..* | BackboneElement |  |  |
| `AdministrableProductDefinition.property.extension` | `AdministrableProductDefinition.property.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AdministrableProductDefinition.property.id` | `AdministrableProductDefinition.property.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AdministrableProductDefinition.property.modifierExtension` | `AdministrableProductDefinition.property.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AdministrableProductDefinition.property.status` | `AdministrableProductDefinition.property.status` | `status` | AdministrableProductDefinition.property.status | The status of characteristic e.g. assigned or pending | 0..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `AdministrableProductDefinition.property.type` | `AdministrableProductDefinition.property.type` | `type` | AdministrableProductDefinition.property.type | A code expressing the type of characteristic | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/product-characteristic-codes` |
| `AdministrableProductDefinition.property.value[x]` | `AdministrableProductDefinition.property.value[x]` | `value[x]` | AdministrableProductDefinition.property.value[x] | A value for the characteristic | 0..1 | Attachment, boolean, CodeableConcept, date, markdown, Quantity, Reference(http://hl7.org/fhir/StructureDefinition/Binary) |  |  |
| `AdministrableProductDefinition.routeOfAdministration` | `AdministrableProductDefinition.routeOfAdministration` | `routeOfAdministration` | AdministrableProductDefinition.routeOfAdministration | The path by which the product is taken into or makes contact with the body | 1..* | BackboneElement |  |  |
| `AdministrableProductDefinition.routeOfAdministration.code` | `AdministrableProductDefinition.routeOfAdministration.code` | `code` | AdministrableProductDefinition.routeOfAdministration.code | Coded expression for the route | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/route-codes` |
| `AdministrableProductDefinition.routeOfAdministration.extension` | `AdministrableProductDefinition.routeOfAdministration.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AdministrableProductDefinition.routeOfAdministration.firstDose` | `AdministrableProductDefinition.routeOfAdministration.firstDose` | `firstDose` | AdministrableProductDefinition.routeOfAdministration.firstDose | The first dose (dose quantity) administered can be specified for the product | 0..1 | Quantity |  |  |
| `AdministrableProductDefinition.routeOfAdministration.id` | `AdministrableProductDefinition.routeOfAdministration.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AdministrableProductDefinition.routeOfAdministration.maxDosePerDay` | `AdministrableProductDefinition.routeOfAdministration.maxDosePerDay` | `maxDosePerDay` | AdministrableProductDefinition.routeOfAdministration.maxDosePerDay | The maximum dose quantity to be administered in any one 24-h period | 0..1 | Quantity |  |  |
| `AdministrableProductDefinition.routeOfAdministration.maxDosePerTreatmentPeriod` | `AdministrableProductDefinition.routeOfAdministration.maxDosePerTreatmentPeriod` | `maxDosePerTreatmentPeriod` | AdministrableProductDefinition.routeOfAdministration.maxDosePerTreatmentPeriod | The maximum dose per treatment period that can be administered | 0..1 | Ratio |  |  |
| `AdministrableProductDefinition.routeOfAdministration.maxSingleDose` | `AdministrableProductDefinition.routeOfAdministration.maxSingleDose` | `maxSingleDose` | AdministrableProductDefinition.routeOfAdministration.maxSingleDose | The maximum single dose that can be administered | 0..1 | Quantity |  |  |
| `AdministrableProductDefinition.routeOfAdministration.maxTreatmentPeriod` | `AdministrableProductDefinition.routeOfAdministration.maxTreatmentPeriod` | `maxTreatmentPeriod` | AdministrableProductDefinition.routeOfAdministration.maxTreatmentPeriod | The maximum treatment period during which the product can be administered | 0..1 | Duration |  |  |
| `AdministrableProductDefinition.routeOfAdministration.modifierExtension` | `AdministrableProductDefinition.routeOfAdministration.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AdministrableProductDefinition.routeOfAdministration.targetSpecies` | `AdministrableProductDefinition.routeOfAdministration.targetSpecies` | `targetSpecies` | AdministrableProductDefinition.routeOfAdministration.targetSpecies | A species for which this route applies | 0..* | BackboneElement |  |  |
| `AdministrableProductDefinition.routeOfAdministration.targetSpecies.code` | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.code` | `code` | AdministrableProductDefinition.routeOfAdministration.targetSpecies.code | Coded expression for the species | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/target-species` |
| `AdministrableProductDefinition.routeOfAdministration.targetSpecies.extension` | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AdministrableProductDefinition.routeOfAdministration.targetSpecies.id` | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AdministrableProductDefinition.routeOfAdministration.targetSpecies.modifierExtension` | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod` | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod` | `withdrawalPeriod` | AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod | A species specific time during which consumption of animal product is not appropriate | 0..* | BackboneElement |  |  |
| `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.extension` | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.id` | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.modifierExtension` | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.supportingInformation` | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.supportingInformation` | `supportingInformation` | AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.supportingInformation | Extra information about the withdrawal period | 0..1 | string |  |  |
| `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.tissue` | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.tissue` | `tissue` | AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.tissue | The type of tissue for which the withdrawal period applies, e.g. meat, milk | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/animal-tissue-type` |
| `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.value` | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.value` | `value` | AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.value | A value for the time | 1..1 | Quantity |  |  |
| `AdministrableProductDefinition.status` | `AdministrableProductDefinition.status` | `status` | AdministrableProductDefinition.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `AdministrableProductDefinition.text` | `AdministrableProductDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `AdministrableProductDefinition.unitOfPresentation` | `AdministrableProductDefinition.unitOfPresentation` | `unitOfPresentation` | AdministrableProductDefinition.unitOfPresentation | The presentation type in which this item is given to a patient. e.g. for a spray - 'puff' | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/unit-of-presentation` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [AdministrableProductDefinition](/docs/R4B/Resources/AdministrableProductDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/AdministrableProductDefinition\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `930`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1159`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AdministrableProductDefinition](/docs/R5/Resources/AdministrableProductDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/AdministrableProductDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition AdministrableProductDefinition from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B AdministrableProductDefinition](/docs/R4B/Resources/AdministrableProductDefinition.md)| Relationship | R5 AdministrableProductDefinition
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | `AdministrableProductDefinition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36621)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36622)| **`AdministrableProductDefinition`**
| | | | | | | `AdministrableProductDefinition.id`| _Equivalent_<br/>(36623/36624)| **`AdministrableProductDefinition.id`**
| | | | | | | `AdministrableProductDefinition.meta`| _Equivalent_<br/>(36625/36626)| **`AdministrableProductDefinition.meta`**
| | | | | | | `AdministrableProductDefinition.implicitRules`| _Equivalent_<br/>(36627/36628)| **`AdministrableProductDefinition.implicitRules`**
| | | | | | | `AdministrableProductDefinition.language`| _Equivalent_<br/>(36629/36630)| **`AdministrableProductDefinition.language`**
| | | | | | | `AdministrableProductDefinition.text`| _Equivalent_<br/>(36631/36632)| **`AdministrableProductDefinition.text`**
| | | | | | | `AdministrableProductDefinition.contained`| _Equivalent_<br/>(36633/36634)| **`AdministrableProductDefinition.contained`**
| | | | | | | `AdministrableProductDefinition.extension`| _Equivalent_<br/>(36635/36636)| **`AdministrableProductDefinition.extension`**
| | | | | | | `AdministrableProductDefinition.modifierExtension`| _Equivalent_<br/>(36637/36638)| **`AdministrableProductDefinition.modifierExtension`**
| | | | | | | `AdministrableProductDefinition.identifier`| _Equivalent_<br/>(36639/36640)| **`AdministrableProductDefinition.identifier`**
| | | | | | | `AdministrableProductDefinition.status`| _Equivalent_<br/>(36641/36642)| **`AdministrableProductDefinition.status`**
| | | | | | | `AdministrableProductDefinition.formOf`| _Equivalent_<br/>(36643/36644)| **`AdministrableProductDefinition.formOf`**
| | | | | | | `AdministrableProductDefinition.administrableDoseForm`| _Equivalent_<br/>(36645/36646)| **`AdministrableProductDefinition.administrableDoseForm`**
| | | | | | | `AdministrableProductDefinition.unitOfPresentation`| _Equivalent_<br/>(36647/36648)| **`AdministrableProductDefinition.unitOfPresentation`**
| | | | | | | `AdministrableProductDefinition.producedFrom`| _Equivalent_<br/>(36649/36650)| **`AdministrableProductDefinition.producedFrom`**
| | | | | | | `AdministrableProductDefinition.ingredient`| _Equivalent_<br/>(36651/36652)| **`AdministrableProductDefinition.ingredient`**
| | | | | | | `AdministrableProductDefinition.device`| _Equivalent_<br/>(36653/36654)| **`AdministrableProductDefinition.device`**
| | | | | | | | | **`AdministrableProductDefinition.description`**
| | | | | | | `AdministrableProductDefinition.property`| _Equivalent_<br/>(36655/36656)| **`AdministrableProductDefinition.property`**
| | | | | | | `AdministrableProductDefinition.property.id`| _Equivalent_<br/>(36657/36658)| **`AdministrableProductDefinition.property.id`**
| | | | | | | `AdministrableProductDefinition.property.extension`| _Equivalent_<br/>(36659/36660)| **`AdministrableProductDefinition.property.extension`**
| | | | | | | `AdministrableProductDefinition.property.modifierExtension`| _Equivalent_<br/>(36661/36662)| **`AdministrableProductDefinition.property.modifierExtension`**
| | | | | | | `AdministrableProductDefinition.property.type`| _Equivalent_<br/>(36663/36664)| **`AdministrableProductDefinition.property.type`**
| | | | | | | `AdministrableProductDefinition.property.value[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36665)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36666)| **`AdministrableProductDefinition.property.value[x]`**
| | | | | | | `AdministrableProductDefinition.property.status`| _Equivalent_<br/>(36667/36668)| **`AdministrableProductDefinition.property.status`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration`| _Equivalent_<br/>(36669/36670)| **`AdministrableProductDefinition.routeOfAdministration`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.id`| _Equivalent_<br/>(36671/36672)| **`AdministrableProductDefinition.routeOfAdministration.id`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.extension`| _Equivalent_<br/>(36673/36674)| **`AdministrableProductDefinition.routeOfAdministration.extension`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.modifierExtension`| _Equivalent_<br/>(36675/36676)| **`AdministrableProductDefinition.routeOfAdministration.modifierExtension`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.code`| _Equivalent_<br/>(36677/36678)| **`AdministrableProductDefinition.routeOfAdministration.code`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.firstDose`| _Equivalent_<br/>(36679/36680)| **`AdministrableProductDefinition.routeOfAdministration.firstDose`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.maxSingleDose`| _Equivalent_<br/>(36681/36682)| **`AdministrableProductDefinition.routeOfAdministration.maxSingleDose`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.maxDosePerDay`| _Equivalent_<br/>(36683/36684)| **`AdministrableProductDefinition.routeOfAdministration.maxDosePerDay`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.maxDosePerTreatmentPeriod`| _Equivalent_<br/>(36685/36686)| **`AdministrableProductDefinition.routeOfAdministration.maxDosePerTreatmentPeriod`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.maxTreatmentPeriod`| _Equivalent_<br/>(36687/36688)| **`AdministrableProductDefinition.routeOfAdministration.maxTreatmentPeriod`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.targetSpecies`| _Equivalent_<br/>(36689/36690)| **`AdministrableProductDefinition.routeOfAdministration.targetSpecies`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.id`| _Equivalent_<br/>(36691/36692)| **`AdministrableProductDefinition.routeOfAdministration.targetSpecies.id`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.extension`| _Equivalent_<br/>(36693/36694)| **`AdministrableProductDefinition.routeOfAdministration.targetSpecies.extension`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.modifierExtension`| _Equivalent_<br/>(36695/36696)| **`AdministrableProductDefinition.routeOfAdministration.targetSpecies.modifierExtension`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.code`| _Equivalent_<br/>(36697/36698)| **`AdministrableProductDefinition.routeOfAdministration.targetSpecies.code`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod`| _Equivalent_<br/>(36699/36700)| **`AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.id`| _Equivalent_<br/>(36701/36702)| **`AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.id`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.extension`| _Equivalent_<br/>(36703/36704)| **`AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.extension`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.modifierExtension`| _Equivalent_<br/>(36705/36706)| **`AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.modifierExtension`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.tissue`| _Equivalent_<br/>(36707/36708)| **`AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.tissue`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.value`| _Equivalent_<br/>(36709/36710)| **`AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.value`**
| | | | | | | `AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.supportingInformation`| _Equivalent_<br/>(36711/36712)| **`AdministrableProductDefinition.routeOfAdministration.targetSpecies.withdrawalPeriod.supportingInformation`**
| | | | | | | *46 of 46 elements used* | | *47 of 47 elements used* 

