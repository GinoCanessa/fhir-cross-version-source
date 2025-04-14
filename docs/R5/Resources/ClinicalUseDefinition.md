Comparison of 
Generated at Monday, April 14, 2025 6:17:45 PM

### ClinicalUseDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | ClinicalUseDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ClinicalUseDefinition` |
| Version | 5.0.0 |
| Description | A single issue - either an indication, contraindication, interaction or an undesirable effect for a medicinal product, medication, device or procedure. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2273` |
| Database Snapshot Count | `69` |
| Database Differential Count | `40` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ClinicalUseDefinition` | `ClinicalUseDefinition` | `ClinicalUseDefinition` | ClinicalUseDefinition | A single issue - either an indication, contraindication, interaction or an undesirable effect for a medicinal product, medication, device or procedure | 0..* | ClinicalUseDefinition |  |  |
| `ClinicalUseDefinition.category` | `ClinicalUseDefinition.category` | `category` | ClinicalUseDefinition.category | A categorisation of the issue, primarily for dividing warnings into subject heading areas such as "Pregnancy", "Overdose" | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/clinical-use-definition-category` |
| `ClinicalUseDefinition.contained` | `ClinicalUseDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ClinicalUseDefinition.contraindication` | `ClinicalUseDefinition.contraindication` | `contraindication` | ClinicalUseDefinition.contraindication | Specifics for when this is a contraindication | 0..1 | BackboneElement |  |  |
| `ClinicalUseDefinition.contraindication.applicability` | `ClinicalUseDefinition.contraindication.applicability` | `applicability` | ClinicalUseDefinition.contraindication.applicability | An expression that returns true or false, indicating whether the indication is applicable or not, after having applied its other elements | 0..1 | Expression |  |  |
| `ClinicalUseDefinition.contraindication.comorbidity` | `ClinicalUseDefinition.contraindication.comorbidity` | `comorbidity` | ClinicalUseDefinition.contraindication.comorbidity | A comorbidity (concurrent condition) or coinfection | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/ObservationDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/disease-symptom-procedure` |
| `ClinicalUseDefinition.contraindication.diseaseStatus` | `ClinicalUseDefinition.contraindication.diseaseStatus` | `diseaseStatus` | ClinicalUseDefinition.contraindication.diseaseStatus | The status of the disease or symptom for the contraindication | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/ObservationDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/disease-status` |
| `ClinicalUseDefinition.contraindication.diseaseSymptomProcedure` | `ClinicalUseDefinition.contraindication.diseaseSymptomProcedure` | `diseaseSymptomProcedure` | ClinicalUseDefinition.contraindication.diseaseSymptomProcedure | The situation that is being documented as contraindicating against this item | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/ObservationDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/disease-symptom-procedure` |
| `ClinicalUseDefinition.contraindication.extension` | `ClinicalUseDefinition.contraindication.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ClinicalUseDefinition.contraindication.id` | `ClinicalUseDefinition.contraindication.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ClinicalUseDefinition.contraindication.indication` | `ClinicalUseDefinition.contraindication.indication` | `indication` | ClinicalUseDefinition.contraindication.indication | The indication which this is a contraidication for | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ClinicalUseDefinition) |  |  |
| `ClinicalUseDefinition.contraindication.modifierExtension` | `ClinicalUseDefinition.contraindication.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ClinicalUseDefinition.contraindication.otherTherapy` | `ClinicalUseDefinition.contraindication.otherTherapy` | `otherTherapy` | ClinicalUseDefinition.contraindication.otherTherapy | Information about use of the product in relation to other therapies described as part of the contraindication | 0..* | BackboneElement |  |  |
| `ClinicalUseDefinition.contraindication.otherTherapy.extension` | `ClinicalUseDefinition.contraindication.otherTherapy.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ClinicalUseDefinition.contraindication.otherTherapy.id` | `ClinicalUseDefinition.contraindication.otherTherapy.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ClinicalUseDefinition.contraindication.otherTherapy.modifierExtension` | `ClinicalUseDefinition.contraindication.otherTherapy.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ClinicalUseDefinition.contraindication.otherTherapy.relationshipType` | `ClinicalUseDefinition.contraindication.otherTherapy.relationshipType` | `relationshipType` | ClinicalUseDefinition.contraindication.otherTherapy.relationshipType | The type of relationship between the product indication/contraindication and another therapy | 1..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/therapy-relationship-type` |
| `ClinicalUseDefinition.contraindication.otherTherapy.treatment` | `ClinicalUseDefinition.contraindication.otherTherapy.treatment` | `treatment` | ClinicalUseDefinition.contraindication.otherTherapy.treatment | Reference to a specific medication, substance etc. as part of an indication or contraindication | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/ActivityDefinition), CodeableReference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct), CodeableReference(http://hl7.org/fhir/StructureDefinition/Medication), CodeableReference(http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition), CodeableReference(http://hl7.org/fhir/StructureDefinition/NutritionProduct), CodeableReference(http://hl7.org/fhir/StructureDefinition/Substance), CodeableReference(http://hl7.org/fhir/StructureDefinition/SubstanceDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/therapy` |
| `ClinicalUseDefinition.extension` | `ClinicalUseDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ClinicalUseDefinition.id` | `ClinicalUseDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ClinicalUseDefinition.identifier` | `ClinicalUseDefinition.identifier` | `identifier` | ClinicalUseDefinition.identifier | Business identifier for this issue | 0..* | Identifier |  |  |
| `ClinicalUseDefinition.implicitRules` | `ClinicalUseDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ClinicalUseDefinition.indication` | `ClinicalUseDefinition.indication` | `indication` | ClinicalUseDefinition.indication | Specifics for when this is an indication | 0..1 | BackboneElement |  |  |
| `ClinicalUseDefinition.indication.applicability` | `ClinicalUseDefinition.indication.applicability` | `applicability` | ClinicalUseDefinition.indication.applicability | An expression that returns true or false, indicating whether the indication is applicable or not, after having applied its other elements | 0..1 | Expression |  |  |
| `ClinicalUseDefinition.indication.comorbidity` | `ClinicalUseDefinition.indication.comorbidity` | `comorbidity` | ClinicalUseDefinition.indication.comorbidity | A comorbidity or coinfection as part of the indication | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/ObservationDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/disease-symptom-procedure` |
| `ClinicalUseDefinition.indication.diseaseStatus` | `ClinicalUseDefinition.indication.diseaseStatus` | `diseaseStatus` | ClinicalUseDefinition.indication.diseaseStatus | The status of the disease or symptom for the indication | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/ObservationDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/disease-status` |
| `ClinicalUseDefinition.indication.diseaseSymptomProcedure` | `ClinicalUseDefinition.indication.diseaseSymptomProcedure` | `diseaseSymptomProcedure` | ClinicalUseDefinition.indication.diseaseSymptomProcedure | The situation that is being documented as an indicaton for this item | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/ObservationDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/disease-symptom-procedure` |
| `ClinicalUseDefinition.indication.duration[x]` | `ClinicalUseDefinition.indication.duration[x]` | `duration[x]` | ClinicalUseDefinition.indication.duration[x] | Timing or duration information | 0..1 | Range, string |  |  |
| `ClinicalUseDefinition.indication.extension` | `ClinicalUseDefinition.indication.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ClinicalUseDefinition.indication.id` | `ClinicalUseDefinition.indication.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ClinicalUseDefinition.indication.intendedEffect` | `ClinicalUseDefinition.indication.intendedEffect` | `intendedEffect` | ClinicalUseDefinition.indication.intendedEffect | The intended effect, aim or strategy to be achieved | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/ObservationDefinition) | `Preferred` | `http://hl7.org/fhir/ValueSet/product-intended-use` |
| `ClinicalUseDefinition.indication.modifierExtension` | `ClinicalUseDefinition.indication.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ClinicalUseDefinition.indication.otherTherapy` | `ClinicalUseDefinition.indication.otherTherapy` | `otherTherapy` | ClinicalUseDefinition.indication.otherTherapy | The use of the medicinal product in relation to other therapies described as part of the indication | 0..* | ClinicalUseDefinition.contraindication.otherTherapy |  |  |
| `ClinicalUseDefinition.indication.undesirableEffect` | `ClinicalUseDefinition.indication.undesirableEffect` | `undesirableEffect` | ClinicalUseDefinition.indication.undesirableEffect | An unwanted side effect or negative outcome of the subject of this resource when being used for this indication | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ClinicalUseDefinition) |  |  |
| `ClinicalUseDefinition.interaction` | `ClinicalUseDefinition.interaction` | `interaction` | ClinicalUseDefinition.interaction | Specifics for when this is an interaction | 0..1 | BackboneElement |  |  |
| `ClinicalUseDefinition.interaction.effect` | `ClinicalUseDefinition.interaction.effect` | `effect` | ClinicalUseDefinition.interaction.effect | The effect of the interaction, for example "reduced gastric absorption of primary medication" | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/ObservationDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/interaction-effect` |
| `ClinicalUseDefinition.interaction.extension` | `ClinicalUseDefinition.interaction.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ClinicalUseDefinition.interaction.id` | `ClinicalUseDefinition.interaction.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ClinicalUseDefinition.interaction.incidence` | `ClinicalUseDefinition.interaction.incidence` | `incidence` | ClinicalUseDefinition.interaction.incidence | The incidence of the interaction, e.g. theoretical, observed | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/interaction-incidence` |
| `ClinicalUseDefinition.interaction.interactant` | `ClinicalUseDefinition.interaction.interactant` | `interactant` | ClinicalUseDefinition.interaction.interactant | The specific medication, product, food etc. or laboratory test that interacts | 0..* | BackboneElement |  |  |
| `ClinicalUseDefinition.interaction.interactant.extension` | `ClinicalUseDefinition.interaction.interactant.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ClinicalUseDefinition.interaction.interactant.id` | `ClinicalUseDefinition.interaction.interactant.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ClinicalUseDefinition.interaction.interactant.item[x]` | `ClinicalUseDefinition.interaction.interactant.item[x]` | `item[x]` | ClinicalUseDefinition.interaction.interactant.item[x] | The specific medication, product, food etc. or laboratory test that interacts | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct), Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition), Reference(http://hl7.org/fhir/StructureDefinition/NutritionProduct), Reference(http://hl7.org/fhir/StructureDefinition/ObservationDefinition), Reference(http://hl7.org/fhir/StructureDefinition/Substance) | `Example` | `http://hl7.org/fhir/ValueSet/interactant` |
| `ClinicalUseDefinition.interaction.interactant.modifierExtension` | `ClinicalUseDefinition.interaction.interactant.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ClinicalUseDefinition.interaction.management` | `ClinicalUseDefinition.interaction.management` | `management` | ClinicalUseDefinition.interaction.management | Actions for managing the interaction | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/interaction-management` |
| `ClinicalUseDefinition.interaction.modifierExtension` | `ClinicalUseDefinition.interaction.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ClinicalUseDefinition.interaction.type` | `ClinicalUseDefinition.interaction.type` | `type` | ClinicalUseDefinition.interaction.type | The type of the interaction e.g. drug-drug interaction, drug-lab test interaction | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/interaction-type` |
| `ClinicalUseDefinition.language` | `ClinicalUseDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `ClinicalUseDefinition.library` | `ClinicalUseDefinition.library` | `library` | ClinicalUseDefinition.library | Logic used by the clinical use definition | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/Library) |  |  |
| `ClinicalUseDefinition.meta` | `ClinicalUseDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ClinicalUseDefinition.modifierExtension` | `ClinicalUseDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ClinicalUseDefinition.population` | `ClinicalUseDefinition.population` | `population` | ClinicalUseDefinition.population | The population group to which this applies | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Group) |  |  |
| `ClinicalUseDefinition.status` | `ClinicalUseDefinition.status` | `status` | ClinicalUseDefinition.status | Whether this is a current issue or one that has been retired etc | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `ClinicalUseDefinition.subject` | `ClinicalUseDefinition.subject` | `subject` | ClinicalUseDefinition.subject | The medication, product, substance, device, procedure etc. for which this is an indication | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ActivityDefinition), Reference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition), Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition), Reference(http://hl7.org/fhir/StructureDefinition/NutritionProduct), Reference(http://hl7.org/fhir/StructureDefinition/PlanDefinition), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `ClinicalUseDefinition.text` | `ClinicalUseDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ClinicalUseDefinition.type` | `ClinicalUseDefinition.type` | `type` | ClinicalUseDefinition.type | indication \| contraindication \| interaction \| undesirable-effect \| warning | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/clinical-use-definition-type|5.0.0` |
| `ClinicalUseDefinition.undesirableEffect` | `ClinicalUseDefinition.undesirableEffect` | `undesirableEffect` | ClinicalUseDefinition.undesirableEffect | A possible negative outcome from the use of this treatment | 0..1 | BackboneElement |  |  |
| `ClinicalUseDefinition.undesirableEffect.classification` | `ClinicalUseDefinition.undesirableEffect.classification` | `classification` | ClinicalUseDefinition.undesirableEffect.classification | High level classification of the effect | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/undesirable-effect-classification` |
| `ClinicalUseDefinition.undesirableEffect.extension` | `ClinicalUseDefinition.undesirableEffect.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ClinicalUseDefinition.undesirableEffect.frequencyOfOccurrence` | `ClinicalUseDefinition.undesirableEffect.frequencyOfOccurrence` | `frequencyOfOccurrence` | ClinicalUseDefinition.undesirableEffect.frequencyOfOccurrence | How often the effect is seen | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/undesirable-effect-frequency` |
| `ClinicalUseDefinition.undesirableEffect.id` | `ClinicalUseDefinition.undesirableEffect.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ClinicalUseDefinition.undesirableEffect.modifierExtension` | `ClinicalUseDefinition.undesirableEffect.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ClinicalUseDefinition.undesirableEffect.symptomConditionEffect` | `ClinicalUseDefinition.undesirableEffect.symptomConditionEffect` | `symptomConditionEffect` | ClinicalUseDefinition.undesirableEffect.symptomConditionEffect | The situation in which the undesirable effect may manifest | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/ObservationDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/undesirable-effect-symptom` |
| `ClinicalUseDefinition.warning` | `ClinicalUseDefinition.warning` | `warning` | ClinicalUseDefinition.warning | Critical environmental, health or physical risks or hazards. For example 'Do not operate heavy machinery', 'May cause drowsiness' | 0..1 | BackboneElement |  |  |
| `ClinicalUseDefinition.warning.code` | `ClinicalUseDefinition.warning.code` | `code` | ClinicalUseDefinition.warning.code | A coded or unformatted textual definition of this warning | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/warning-type` |
| `ClinicalUseDefinition.warning.description` | `ClinicalUseDefinition.warning.description` | `description` | ClinicalUseDefinition.warning.description | A textual definition of this warning, with formatting | 0..1 | markdown |  |  |
| `ClinicalUseDefinition.warning.extension` | `ClinicalUseDefinition.warning.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ClinicalUseDefinition.warning.id` | `ClinicalUseDefinition.warning.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ClinicalUseDefinition.warning.modifierExtension` | `ClinicalUseDefinition.warning.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [ClinicalUseDefinition](/docs/R4B/Resources/ClinicalUseDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ClinicalUseDefinition\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `948`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1177`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ClinicalUseDefinition](/docs/R5/Resources/ClinicalUseDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ClinicalUseDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ClinicalUseDefinition from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B ClinicalUseDefinition](/docs/R4B/Resources/ClinicalUseDefinition.md)| Relationship | R5 ClinicalUseDefinition
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | `ClinicalUseDefinition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(38863)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(38864)| **`ClinicalUseDefinition`**
| | | | | | | `ClinicalUseDefinition.id`| _Equivalent_<br/>(38865/38866)| **`ClinicalUseDefinition.id`**
| | | | | | | `ClinicalUseDefinition.meta`| _Equivalent_<br/>(38867/38868)| **`ClinicalUseDefinition.meta`**
| | | | | | | `ClinicalUseDefinition.implicitRules`| _Equivalent_<br/>(38869/38870)| **`ClinicalUseDefinition.implicitRules`**
| | | | | | | `ClinicalUseDefinition.language`| _Equivalent_<br/>(38871/38872)| **`ClinicalUseDefinition.language`**
| | | | | | | `ClinicalUseDefinition.text`| _Equivalent_<br/>(38873/38874)| **`ClinicalUseDefinition.text`**
| | | | | | | `ClinicalUseDefinition.contained`| _Equivalent_<br/>(38875/38876)| **`ClinicalUseDefinition.contained`**
| | | | | | | `ClinicalUseDefinition.extension`| _Equivalent_<br/>(38877/38878)| **`ClinicalUseDefinition.extension`**
| | | | | | | `ClinicalUseDefinition.modifierExtension`| _Equivalent_<br/>(38879/38880)| **`ClinicalUseDefinition.modifierExtension`**
| | | | | | | `ClinicalUseDefinition.identifier`| _Equivalent_<br/>(38881/38882)| **`ClinicalUseDefinition.identifier`**
| | | | | | | `ClinicalUseDefinition.type`| _Equivalent_<br/>(38883/38884)| **`ClinicalUseDefinition.type`**
| | | | | | | `ClinicalUseDefinition.category`| _Equivalent_<br/>(38885/38886)| **`ClinicalUseDefinition.category`**
| | | | | | | `ClinicalUseDefinition.subject`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(38887)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(38888)| **`ClinicalUseDefinition.subject`**
| | | | | | | `ClinicalUseDefinition.status`| _Equivalent_<br/>(38889/38890)| **`ClinicalUseDefinition.status`**
| | | | | | | `ClinicalUseDefinition.contraindication`| _Equivalent_<br/>(38891/38892)| **`ClinicalUseDefinition.contraindication`**
| | | | | | | `ClinicalUseDefinition.contraindication.id`| _Equivalent_<br/>(38893/38894)| **`ClinicalUseDefinition.contraindication.id`**
| | | | | | | `ClinicalUseDefinition.contraindication.extension`| _Equivalent_<br/>(38895/38896)| **`ClinicalUseDefinition.contraindication.extension`**
| | | | | | | `ClinicalUseDefinition.contraindication.modifierExtension`| _Equivalent_<br/>(38897/38898)| **`ClinicalUseDefinition.contraindication.modifierExtension`**
| | | | | | | `ClinicalUseDefinition.contraindication.diseaseSymptomProcedure`| _Equivalent_<br/>(38899/38900)| **`ClinicalUseDefinition.contraindication.diseaseSymptomProcedure`**
| | | | | | | `ClinicalUseDefinition.contraindication.diseaseStatus`| _Equivalent_<br/>(38901/38902)| **`ClinicalUseDefinition.contraindication.diseaseStatus`**
| | | | | | | `ClinicalUseDefinition.contraindication.comorbidity`| _Equivalent_<br/>(38903/38904)| **`ClinicalUseDefinition.contraindication.comorbidity`**
| | | | | | | `ClinicalUseDefinition.contraindication.indication`| _Equivalent_<br/>(38905/38906)| **`ClinicalUseDefinition.contraindication.indication`**
| | | | | | | | | **`ClinicalUseDefinition.contraindication.applicability`**
| | | | | | | `ClinicalUseDefinition.contraindication.otherTherapy`| _Equivalent_<br/>(38907/38908)| **`ClinicalUseDefinition.contraindication.otherTherapy`**
| | | | | | | `ClinicalUseDefinition.contraindication.otherTherapy.id`| _Equivalent_<br/>(38909/38910)| **`ClinicalUseDefinition.contraindication.otherTherapy.id`**
| | | | | | | `ClinicalUseDefinition.contraindication.otherTherapy.extension`| _Equivalent_<br/>(38911/38912)| **`ClinicalUseDefinition.contraindication.otherTherapy.extension`**
| | | | | | | `ClinicalUseDefinition.contraindication.otherTherapy.modifierExtension`| _Equivalent_<br/>(38913/38914)| **`ClinicalUseDefinition.contraindication.otherTherapy.modifierExtension`**
| | | | | | | `ClinicalUseDefinition.contraindication.otherTherapy.relationshipType`| _Equivalent_<br/>(38915/38916)| **`ClinicalUseDefinition.contraindication.otherTherapy.relationshipType`**
| | | | | | | `ClinicalUseDefinition.contraindication.otherTherapy.therapy`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1865)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2107)| **`ClinicalUseDefinition.contraindication.otherTherapy.treatment`**
| | | | | | | `ClinicalUseDefinition.indication`| _Equivalent_<br/>(38917/38918)| **`ClinicalUseDefinition.indication`**
| | | | | | | `ClinicalUseDefinition.indication.id`| _Equivalent_<br/>(38919/38920)| **`ClinicalUseDefinition.indication.id`**
| | | | | | | `ClinicalUseDefinition.indication.extension`| _Equivalent_<br/>(38921/38922)| **`ClinicalUseDefinition.indication.extension`**
| | | | | | | `ClinicalUseDefinition.indication.modifierExtension`| _Equivalent_<br/>(38923/38924)| **`ClinicalUseDefinition.indication.modifierExtension`**
| | | | | | | `ClinicalUseDefinition.indication.diseaseSymptomProcedure`| _Equivalent_<br/>(38925/38926)| **`ClinicalUseDefinition.indication.diseaseSymptomProcedure`**
| | | | | | | `ClinicalUseDefinition.indication.diseaseStatus`| _Equivalent_<br/>(38927/38928)| **`ClinicalUseDefinition.indication.diseaseStatus`**
| | | | | | | `ClinicalUseDefinition.indication.comorbidity`| _Equivalent_<br/>(38929/38930)| **`ClinicalUseDefinition.indication.comorbidity`**
| | | | | | | `ClinicalUseDefinition.indication.intendedEffect`| _Equivalent_<br/>(38931/38932)| **`ClinicalUseDefinition.indication.intendedEffect`**
| | | | | | | `ClinicalUseDefinition.indication.duration[x]`| _Equivalent_<br/>(38933/38934)| **`ClinicalUseDefinition.indication.duration[x]`**
| | | | | | | `ClinicalUseDefinition.indication.undesirableEffect`| _Equivalent_<br/>(38935/38936)| **`ClinicalUseDefinition.indication.undesirableEffect`**
| | | | | | | | | **`ClinicalUseDefinition.indication.applicability`**
| | | | | | | `ClinicalUseDefinition.indication.otherTherapy`| _Equivalent_<br/>(38937/38938)| **`ClinicalUseDefinition.indication.otherTherapy`**
| | | | | | | `ClinicalUseDefinition.interaction`| _Equivalent_<br/>(38939/38940)| **`ClinicalUseDefinition.interaction`**
| | | | | | | `ClinicalUseDefinition.interaction.id`| _Equivalent_<br/>(38941/38942)| **`ClinicalUseDefinition.interaction.id`**
| | | | | | | `ClinicalUseDefinition.interaction.extension`| _Equivalent_<br/>(38943/38944)| **`ClinicalUseDefinition.interaction.extension`**
| | | | | | | `ClinicalUseDefinition.interaction.modifierExtension`| _Equivalent_<br/>(38945/38946)| **`ClinicalUseDefinition.interaction.modifierExtension`**
| | | | | | | `ClinicalUseDefinition.interaction.interactant`| _Equivalent_<br/>(38947/38948)| **`ClinicalUseDefinition.interaction.interactant`**
| | | | | | | `ClinicalUseDefinition.interaction.interactant.id`| _Equivalent_<br/>(38949/38950)| **`ClinicalUseDefinition.interaction.interactant.id`**
| | | | | | | `ClinicalUseDefinition.interaction.interactant.extension`| _Equivalent_<br/>(38951/38952)| **`ClinicalUseDefinition.interaction.interactant.extension`**
| | | | | | | `ClinicalUseDefinition.interaction.interactant.modifierExtension`| _Equivalent_<br/>(38953/38954)| **`ClinicalUseDefinition.interaction.interactant.modifierExtension`**
| | | | | | | `ClinicalUseDefinition.interaction.interactant.item[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(38955)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(38956)| **`ClinicalUseDefinition.interaction.interactant.item[x]`**
| | | | | | | `ClinicalUseDefinition.interaction.type`| _Equivalent_<br/>(38957/38958)| **`ClinicalUseDefinition.interaction.type`**
| | | | | | | `ClinicalUseDefinition.interaction.effect`| _Equivalent_<br/>(38959/38960)| **`ClinicalUseDefinition.interaction.effect`**
| | | | | | | `ClinicalUseDefinition.interaction.incidence`| _Equivalent_<br/>(38961/38962)| **`ClinicalUseDefinition.interaction.incidence`**
| | | | | | | `ClinicalUseDefinition.interaction.management`| _Equivalent_<br/>(38963/38964)| **`ClinicalUseDefinition.interaction.management`**
| | | | | | | `ClinicalUseDefinition.population`| _Equivalent_<br/>(38965/38966)| **`ClinicalUseDefinition.population`**
| | | | | | | | | **`ClinicalUseDefinition.library`**
| | | | | | | `ClinicalUseDefinition.undesirableEffect`| _Equivalent_<br/>(38967/38968)| **`ClinicalUseDefinition.undesirableEffect`**
| | | | | | | `ClinicalUseDefinition.undesirableEffect.id`| _Equivalent_<br/>(38969/38970)| **`ClinicalUseDefinition.undesirableEffect.id`**
| | | | | | | `ClinicalUseDefinition.undesirableEffect.extension`| _Equivalent_<br/>(38971/38972)| **`ClinicalUseDefinition.undesirableEffect.extension`**
| | | | | | | `ClinicalUseDefinition.undesirableEffect.modifierExtension`| _Equivalent_<br/>(38973/38974)| **`ClinicalUseDefinition.undesirableEffect.modifierExtension`**
| | | | | | | `ClinicalUseDefinition.undesirableEffect.symptomConditionEffect`| _Equivalent_<br/>(38975/38976)| **`ClinicalUseDefinition.undesirableEffect.symptomConditionEffect`**
| | | | | | | `ClinicalUseDefinition.undesirableEffect.classification`| _Equivalent_<br/>(38977/38978)| **`ClinicalUseDefinition.undesirableEffect.classification`**
| | | | | | | `ClinicalUseDefinition.undesirableEffect.frequencyOfOccurrence`| _Equivalent_<br/>(38979/38980)| **`ClinicalUseDefinition.undesirableEffect.frequencyOfOccurrence`**
| | | | | | | `ClinicalUseDefinition.warning`| _Equivalent_<br/>(38981/38982)| **`ClinicalUseDefinition.warning`**
| | | | | | | `ClinicalUseDefinition.warning.id`| _Equivalent_<br/>(38983/38984)| **`ClinicalUseDefinition.warning.id`**
| | | | | | | `ClinicalUseDefinition.warning.extension`| _Equivalent_<br/>(38985/38986)| **`ClinicalUseDefinition.warning.extension`**
| | | | | | | `ClinicalUseDefinition.warning.modifierExtension`| _Equivalent_<br/>(38987/38988)| **`ClinicalUseDefinition.warning.modifierExtension`**
| | | | | | | `ClinicalUseDefinition.warning.description`| _Equivalent_<br/>(38989/38990)| **`ClinicalUseDefinition.warning.description`**
| | | | | | | `ClinicalUseDefinition.warning.code`| _Equivalent_<br/>(38991/38992)| **`ClinicalUseDefinition.warning.code`**
| | | | | | | *66 of 66 elements used* | | *69 of 69 elements used* 

