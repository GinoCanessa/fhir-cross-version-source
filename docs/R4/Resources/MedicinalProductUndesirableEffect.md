Comparison of 
Generated at Thursday, April 3, 2025 8:18:18 AM

### MedicinalProductUndesirableEffect

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | MedicinalProductUndesirableEffect |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MedicinalProductUndesirableEffect` |
| Version | 4.0.1 |
| Description | Describe the undesirable effects of the medicinal product. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1121` |
| Database Snapshot Count | `14` |
| Database Differential Count | `6` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MedicinalProductUndesirableEffect` | `MedicinalProductUndesirableEffect` | `MedicinalProductUndesirableEffect` | MedicinalProductUndesirableEffect | MedicinalProductUndesirableEffect | 0..* | MedicinalProductUndesirableEffect |  |  |
| `MedicinalProductUndesirableEffect.classification` | `MedicinalProductUndesirableEffect.classification` | `classification` | MedicinalProductUndesirableEffect.classification | Classification of the effect | 0..1 | CodeableConcept |  |  |
| `MedicinalProductUndesirableEffect.contained` | `MedicinalProductUndesirableEffect.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MedicinalProductUndesirableEffect.extension` | `MedicinalProductUndesirableEffect.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductUndesirableEffect.frequencyOfOccurrence` | `MedicinalProductUndesirableEffect.frequencyOfOccurrence` | `frequencyOfOccurrence` | MedicinalProductUndesirableEffect.frequencyOfOccurrence | The frequency of occurrence of the effect | 0..1 | CodeableConcept |  |  |
| `MedicinalProductUndesirableEffect.id` | `MedicinalProductUndesirableEffect.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MedicinalProductUndesirableEffect.implicitRules` | `MedicinalProductUndesirableEffect.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MedicinalProductUndesirableEffect.language` | `MedicinalProductUndesirableEffect.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `MedicinalProductUndesirableEffect.meta` | `MedicinalProductUndesirableEffect.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MedicinalProductUndesirableEffect.modifierExtension` | `MedicinalProductUndesirableEffect.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicinalProductUndesirableEffect.population` | `MedicinalProductUndesirableEffect.population` | `population` | MedicinalProductUndesirableEffect.population | The population group to which this applies | 0..* | Population |  |  |
| `MedicinalProductUndesirableEffect.subject` | `MedicinalProductUndesirableEffect.subject` | `subject` | MedicinalProductUndesirableEffect.subject | The medication for which this is an indication | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProduct) |  |  |
| `MedicinalProductUndesirableEffect.symptomConditionEffect` | `MedicinalProductUndesirableEffect.symptomConditionEffect` | `symptomConditionEffect` | MedicinalProductUndesirableEffect.symptomConditionEffect | The symptom, condition or undesirable effect | 0..1 | CodeableConcept |  |  |
| `MedicinalProductUndesirableEffect.text` | `MedicinalProductUndesirableEffect.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

