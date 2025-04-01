Comparison of 
Generated at Tuesday, April 1, 2025 1:39:20 PM

### MedicinalProductInteraction

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | MedicinalProductInteraction |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MedicinalProductInteraction` |
| Version | 4.0.1 |
| Description | The interactions of the medicinal product with other medicinal products, or other forms of interactions. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1117` |
| Database Snapshot Count | `20` |
| Database Differential Count | `9` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MedicinalProductInteraction` | `MedicinalProductInteraction` | `MedicinalProductInteraction` | MedicinalProductInteraction | MedicinalProductInteraction | 0..* | MedicinalProductInteraction |  |  |
| `MedicinalProductInteraction.contained` | `MedicinalProductInteraction.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MedicinalProductInteraction.description` | `MedicinalProductInteraction.description` | `description` | MedicinalProductInteraction.description | The interaction described | 0..1 | string |  |  |
| `MedicinalProductInteraction.effect` | `MedicinalProductInteraction.effect` | `effect` | MedicinalProductInteraction.effect | The effect of the interaction, for example "reduced gastric absorption of primary medication" | 0..1 | CodeableConcept |  |  |
| `MedicinalProductInteraction.extension` | `MedicinalProductInteraction.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductInteraction.id` | `MedicinalProductInteraction.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MedicinalProductInteraction.implicitRules` | `MedicinalProductInteraction.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MedicinalProductInteraction.incidence` | `MedicinalProductInteraction.incidence` | `incidence` | MedicinalProductInteraction.incidence | The incidence of the interaction, e.g. theoretical, observed | 0..1 | CodeableConcept |  |  |
| `MedicinalProductInteraction.interactant` | `MedicinalProductInteraction.interactant` | `interactant` | MedicinalProductInteraction.interactant | The specific medication, food or laboratory test that interacts | 0..* | BackboneElement |  |  |
| `MedicinalProductInteraction.interactant.extension` | `MedicinalProductInteraction.interactant.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductInteraction.interactant.id` | `MedicinalProductInteraction.interactant.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductInteraction.interactant.item[x]` | `MedicinalProductInteraction.interactant.item[x]` | `item[x]` | MedicinalProductInteraction.interactant.item[x] | The specific medication, food or laboratory test that interacts | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProduct), Reference(http://hl7.org/fhir/StructureDefinition/ObservationDefinition), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `MedicinalProductInteraction.interactant.modifierExtension` | `MedicinalProductInteraction.interactant.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductInteraction.language` | `MedicinalProductInteraction.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `MedicinalProductInteraction.management` | `MedicinalProductInteraction.management` | `management` | MedicinalProductInteraction.management | Actions for managing the interaction | 0..1 | CodeableConcept |  |  |
| `MedicinalProductInteraction.meta` | `MedicinalProductInteraction.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MedicinalProductInteraction.modifierExtension` | `MedicinalProductInteraction.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicinalProductInteraction.subject` | `MedicinalProductInteraction.subject` | `subject` | MedicinalProductInteraction.subject | The medication for which this is a described interaction | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProduct), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `MedicinalProductInteraction.text` | `MedicinalProductInteraction.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `MedicinalProductInteraction.type` | `MedicinalProductInteraction.type` | `type` | MedicinalProductInteraction.type | The type of the interaction e.g. drug-drug interaction, drug-food interaction, drug-lab test interaction | 0..1 | CodeableConcept |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

