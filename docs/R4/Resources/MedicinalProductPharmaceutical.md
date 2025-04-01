Comparison of 
Generated at Tuesday, April 1, 2025 1:39:20 PM

### MedicinalProductPharmaceutical

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | MedicinalProductPharmaceutical |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MedicinalProductPharmaceutical` |
| Version | 4.0.1 |
| Description | A pharmaceutical product described in terms of its composition and dose form. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1120` |
| Database Snapshot Count | `42` |
| Database Differential Count | `22` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MedicinalProductPharmaceutical` | `MedicinalProductPharmaceutical` | `MedicinalProductPharmaceutical` | MedicinalProductPharmaceutical | A pharmaceutical product described in terms of its composition and dose form | 0..* | MedicinalProductPharmaceutical |  |  |
| `MedicinalProductPharmaceutical.administrableDoseForm` | `MedicinalProductPharmaceutical.administrableDoseForm` | `administrableDoseForm` | MedicinalProductPharmaceutical.administrableDoseForm | The administrable dose form, after necessary reconstitution | 1..1 | CodeableConcept |  |  |
| `MedicinalProductPharmaceutical.characteristics` | `MedicinalProductPharmaceutical.characteristics` | `characteristics` | MedicinalProductPharmaceutical.characteristics | Characteristics e.g. a products onset of action | 0..* | BackboneElement |  |  |
| `MedicinalProductPharmaceutical.characteristics.code` | `MedicinalProductPharmaceutical.characteristics.code` | `code` | MedicinalProductPharmaceutical.characteristics.code | A coded characteristic | 1..1 | CodeableConcept |  |  |
| `MedicinalProductPharmaceutical.characteristics.extension` | `MedicinalProductPharmaceutical.characteristics.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductPharmaceutical.characteristics.id` | `MedicinalProductPharmaceutical.characteristics.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductPharmaceutical.characteristics.modifierExtension` | `MedicinalProductPharmaceutical.characteristics.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductPharmaceutical.characteristics.status` | `MedicinalProductPharmaceutical.characteristics.status` | `status` | MedicinalProductPharmaceutical.characteristics.status | The status of characteristic e.g. assigned or pending | 0..1 | CodeableConcept |  |  |
| `MedicinalProductPharmaceutical.contained` | `MedicinalProductPharmaceutical.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MedicinalProductPharmaceutical.device` | `MedicinalProductPharmaceutical.device` | `device` | MedicinalProductPharmaceutical.device | Accompanying device | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition) |  |  |
| `MedicinalProductPharmaceutical.extension` | `MedicinalProductPharmaceutical.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductPharmaceutical.id` | `MedicinalProductPharmaceutical.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MedicinalProductPharmaceutical.identifier` | `MedicinalProductPharmaceutical.identifier` | `identifier` | MedicinalProductPharmaceutical.identifier | An identifier for the pharmaceutical medicinal product | 0..* | Identifier |  |  |
| `MedicinalProductPharmaceutical.implicitRules` | `MedicinalProductPharmaceutical.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MedicinalProductPharmaceutical.ingredient` | `MedicinalProductPharmaceutical.ingredient` | `ingredient` | MedicinalProductPharmaceutical.ingredient | Ingredient | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductIngredient) |  |  |
| `MedicinalProductPharmaceutical.language` | `MedicinalProductPharmaceutical.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `MedicinalProductPharmaceutical.meta` | `MedicinalProductPharmaceutical.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MedicinalProductPharmaceutical.modifierExtension` | `MedicinalProductPharmaceutical.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration` | `MedicinalProductPharmaceutical.routeOfAdministration` | `routeOfAdministration` | MedicinalProductPharmaceutical.routeOfAdministration | The path by which the pharmaceutical product is taken into or makes contact with the body | 1..* | BackboneElement |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.code` | `MedicinalProductPharmaceutical.routeOfAdministration.code` | `code` | MedicinalProductPharmaceutical.routeOfAdministration.code | Coded expression for the route | 1..1 | CodeableConcept |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.extension` | `MedicinalProductPharmaceutical.routeOfAdministration.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.firstDose` | `MedicinalProductPharmaceutical.routeOfAdministration.firstDose` | `firstDose` | MedicinalProductPharmaceutical.routeOfAdministration.firstDose | The first dose (dose quantity) administered in humans can be specified, for a product under investigation, using a numerical value and its unit of measurement | 0..1 | Quantity |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.id` | `MedicinalProductPharmaceutical.routeOfAdministration.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.maxDosePerDay` | `MedicinalProductPharmaceutical.routeOfAdministration.maxDosePerDay` | `maxDosePerDay` | MedicinalProductPharmaceutical.routeOfAdministration.maxDosePerDay | The maximum dose per day (maximum dose quantity to be administered in any one 24-h period) that can be administered as per the protocol referenced in the clinical trial authorisation | 0..1 | Quantity |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.maxDosePerTreatmentPeriod` | `MedicinalProductPharmaceutical.routeOfAdministration.maxDosePerTreatmentPeriod` | `maxDosePerTreatmentPeriod` | MedicinalProductPharmaceutical.routeOfAdministration.maxDosePerTreatmentPeriod | The maximum dose per treatment period that can be administered as per the protocol referenced in the clinical trial authorisation | 0..1 | Ratio |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.maxSingleDose` | `MedicinalProductPharmaceutical.routeOfAdministration.maxSingleDose` | `maxSingleDose` | MedicinalProductPharmaceutical.routeOfAdministration.maxSingleDose | The maximum single dose that can be administered as per the protocol of a clinical trial can be specified using a numerical value and its unit of measurement | 0..1 | Quantity |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.maxTreatmentPeriod` | `MedicinalProductPharmaceutical.routeOfAdministration.maxTreatmentPeriod` | `maxTreatmentPeriod` | MedicinalProductPharmaceutical.routeOfAdministration.maxTreatmentPeriod | The maximum treatment period during which an Investigational Medicinal Product can be administered as per the protocol referenced in the clinical trial authorisation | 0..1 | Duration |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.modifierExtension` | `MedicinalProductPharmaceutical.routeOfAdministration.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies` | `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies` | `targetSpecies` | MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies | A species for which this route applies | 0..* | BackboneElement |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.code` | `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.code` | `code` | MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.code | Coded expression for the species | 1..1 | CodeableConcept |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.extension` | `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.id` | `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.modifierExtension` | `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod` | `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod` | `withdrawalPeriod` | MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod | A species specific time during which consumption of animal product is not appropriate | 0..* | BackboneElement |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod.extension` | `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod.id` | `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod.modifierExtension` | `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod.supportingInformation` | `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod.supportingInformation` | `supportingInformation` | MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod.supportingInformation | Extra information about the withdrawal period | 0..1 | string |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod.tissue` | `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod.tissue` | `tissue` | MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod.tissue | Coded expression for the type of tissue for which the withdrawal period applues, e.g. meat, milk | 1..1 | CodeableConcept |  |  |
| `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod.value` | `MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod.value` | `value` | MedicinalProductPharmaceutical.routeOfAdministration.targetSpecies.withdrawalPeriod.value | A value for the time | 1..1 | Quantity |  |  |
| `MedicinalProductPharmaceutical.text` | `MedicinalProductPharmaceutical.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `MedicinalProductPharmaceutical.unitOfPresentation` | `MedicinalProductPharmaceutical.unitOfPresentation` | `unitOfPresentation` | MedicinalProductPharmaceutical.unitOfPresentation | Todo | 0..1 | CodeableConcept |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

