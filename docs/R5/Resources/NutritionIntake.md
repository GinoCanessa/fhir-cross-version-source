Comparison of 
Generated at Monday, April 14, 2025 6:17:45 PM

### NutritionIntake

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | NutritionIntake |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/NutritionIntake` |
| Version | 5.0.0 |
| Description | A record of food or fluid that is being consumed by a patient.  A NutritionIntake may indicate that the patient may be consuming the food or fluid now or has consumed the food or fluid in the past.  The source of this information can be the patient, significant other (such as a family member or spouse), or a clinician.  A common scenario where this information is captured is during the history taking process during a patient visit or stay or through an app that tracks food or fluids consumed.   The consumption information may come from sources such as the patient's memory, from a nutrition label,  or from a clinician documenting observed intake. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2348` |
| Database Snapshot Count | `49` |
| Database Differential Count | `32` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `NutritionIntake` | `NutritionIntake` | `NutritionIntake` | NutritionIntake | Record of food or fluid being taken by a patient | 0..* | NutritionIntake |  |  |
| `NutritionIntake.basedOn` | `NutritionIntake.basedOn` | `basedOn` | NutritionIntake.basedOn | Fulfils plan, proposal or order | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/CarePlan), Reference(http://hl7.org/fhir/StructureDefinition/NutritionOrder), Reference(http://hl7.org/fhir/StructureDefinition/ServiceRequest) |  |  |
| `NutritionIntake.code` | `NutritionIntake.code` | `code` | NutritionIntake.code | Code representing an overall type of nutrition intake | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/diet-type` |
| `NutritionIntake.consumedItem` | `NutritionIntake.consumedItem` | `consumedItem` | NutritionIntake.consumedItem | What food or fluid product or item was consumed | 1..* | BackboneElement |  |  |
| `NutritionIntake.consumedItem.amount` | `NutritionIntake.consumedItem.amount` | `amount` | NutritionIntake.consumedItem.amount | Quantity of the specified food | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `NutritionIntake.consumedItem.extension` | `NutritionIntake.consumedItem.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `NutritionIntake.consumedItem.id` | `NutritionIntake.consumedItem.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `NutritionIntake.consumedItem.modifierExtension` | `NutritionIntake.consumedItem.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `NutritionIntake.consumedItem.notConsumed` | `NutritionIntake.consumedItem.notConsumed` | `notConsumed` | NutritionIntake.consumedItem.notConsumed | Flag to indicate if the food or fluid item was refused or otherwise not consumed | 0..1 | boolean |  |  |
| `NutritionIntake.consumedItem.notConsumedReason` | `NutritionIntake.consumedItem.notConsumedReason` | `notConsumedReason` | NutritionIntake.consumedItem.notConsumedReason | Reason food or fluid was not consumed | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/not-consumed-reason` |
| `NutritionIntake.consumedItem.nutritionProduct` | `NutritionIntake.consumedItem.nutritionProduct` | `nutritionProduct` | NutritionIntake.consumedItem.nutritionProduct | Code that identifies the food or fluid product that was consumed | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/NutritionProduct) | `Example` | `http://hl7.org/fhir/ValueSet/food-type` |
| `NutritionIntake.consumedItem.rate` | `NutritionIntake.consumedItem.rate` | `rate` | NutritionIntake.consumedItem.rate | Rate at which enteral feeding was administered | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `NutritionIntake.consumedItem.schedule` | `NutritionIntake.consumedItem.schedule` | `schedule` | NutritionIntake.consumedItem.schedule | Scheduled frequency of consumption | 0..1 | Timing |  |  |
| `NutritionIntake.consumedItem.type` | `NutritionIntake.consumedItem.type` | `type` | NutritionIntake.consumedItem.type | The type of food or fluid product | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/edible-substance-type` |
| `NutritionIntake.contained` | `NutritionIntake.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `NutritionIntake.derivedFrom` | `NutritionIntake.derivedFrom` | `derivedFrom` | NutritionIntake.derivedFrom | Additional supporting information | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `NutritionIntake.encounter` | `NutritionIntake.encounter` | `encounter` | NutritionIntake.encounter | Encounter associated with NutritionIntake | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `NutritionIntake.extension` | `NutritionIntake.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `NutritionIntake.id` | `NutritionIntake.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `NutritionIntake.identifier` | `NutritionIntake.identifier` | `identifier` | NutritionIntake.identifier | External identifier | 0..* | Identifier |  |  |
| `NutritionIntake.implicitRules` | `NutritionIntake.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `NutritionIntake.ingredientLabel` | `NutritionIntake.ingredientLabel` | `ingredientLabel` | NutritionIntake.ingredientLabel | Total nutrient for the whole meal, product, serving | 0..* | BackboneElement |  |  |
| `NutritionIntake.ingredientLabel.amount` | `NutritionIntake.ingredientLabel.amount` | `amount` | NutritionIntake.ingredientLabel.amount | Total amount of nutrient consumed | 1..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `NutritionIntake.ingredientLabel.extension` | `NutritionIntake.ingredientLabel.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `NutritionIntake.ingredientLabel.id` | `NutritionIntake.ingredientLabel.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `NutritionIntake.ingredientLabel.modifierExtension` | `NutritionIntake.ingredientLabel.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `NutritionIntake.ingredientLabel.nutrient` | `NutritionIntake.ingredientLabel.nutrient` | `nutrient` | NutritionIntake.ingredientLabel.nutrient | Total nutrient consumed | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/Substance) | `Example` | `http://hl7.org/fhir/ValueSet/nutrient-code` |
| `NutritionIntake.instantiatesCanonical` | `NutritionIntake.instantiatesCanonical` | `instantiatesCanonical` | NutritionIntake.instantiatesCanonical | Instantiates FHIR protocol or definition | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/ActivityDefinition), canonical(http://hl7.org/fhir/StructureDefinition/ChargeItemDefinition), canonical(http://hl7.org/fhir/StructureDefinition/ClinicalUseDefinition), canonical(http://hl7.org/fhir/StructureDefinition/EventDefinition), canonical(http://hl7.org/fhir/StructureDefinition/Measure), canonical(http://hl7.org/fhir/StructureDefinition/MessageDefinition), canonical(http://hl7.org/fhir/StructureDefinition/ObservationDefinition), canonical(http://hl7.org/fhir/StructureDefinition/OperationDefinition), canonical(http://hl7.org/fhir/StructureDefinition/PlanDefinition), canonical(http://hl7.org/fhir/StructureDefinition/Questionnaire), canonical(http://hl7.org/fhir/StructureDefinition/Requirements), canonical(http://hl7.org/fhir/StructureDefinition/SubscriptionTopic), canonical(http://hl7.org/fhir/StructureDefinition/TestPlan), canonical(http://hl7.org/fhir/StructureDefinition/TestScript) |  |  |
| `NutritionIntake.instantiatesUri` | `NutritionIntake.instantiatesUri` | `instantiatesUri` | NutritionIntake.instantiatesUri | Instantiates external protocol or definition | 0..* | uri |  |  |
| `NutritionIntake.language` | `NutritionIntake.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `NutritionIntake.location` | `NutritionIntake.location` | `location` | NutritionIntake.location | Where the intake occurred | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `NutritionIntake.meta` | `NutritionIntake.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `NutritionIntake.modifierExtension` | `NutritionIntake.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `NutritionIntake.note` | `NutritionIntake.note` | `note` | NutritionIntake.note | Further information about the consumption | 0..* | Annotation |  |  |
| `NutritionIntake.occurrence[x]` | `NutritionIntake.occurrence[x]` | `occurrence[x]` | NutritionIntake.occurrence[x] | The date/time or interval when the food or fluid is/was consumed | 0..1 | dateTime, Period |  |  |
| `NutritionIntake.partOf` | `NutritionIntake.partOf` | `partOf` | NutritionIntake.partOf | Part of referenced event | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/NutritionIntake), Reference(http://hl7.org/fhir/StructureDefinition/Observation), Reference(http://hl7.org/fhir/StructureDefinition/Procedure) |  |  |
| `NutritionIntake.performer` | `NutritionIntake.performer` | `performer` | NutritionIntake.performer | Who was performed in the intake | 0..* | BackboneElement |  |  |
| `NutritionIntake.performer.actor` | `NutritionIntake.performer.actor` | `actor` | NutritionIntake.performer.actor | Who performed the intake | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `NutritionIntake.performer.extension` | `NutritionIntake.performer.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `NutritionIntake.performer.function` | `NutritionIntake.performer.function` | `function` | NutritionIntake.performer.function | Type of performer | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/performer-role` |
| `NutritionIntake.performer.id` | `NutritionIntake.performer.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `NutritionIntake.performer.modifierExtension` | `NutritionIntake.performer.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `NutritionIntake.reason` | `NutritionIntake.reason` | `reason` | NutritionIntake.reason | Reason for why the food or fluid is /was consumed | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/Condition), CodeableReference(http://hl7.org/fhir/StructureDefinition/DiagnosticReport), CodeableReference(http://hl7.org/fhir/StructureDefinition/DocumentReference), CodeableReference(http://hl7.org/fhir/StructureDefinition/Observation) | `Example` | `http://hl7.org/fhir/ValueSet/condition-code` |
| `NutritionIntake.recorded` | `NutritionIntake.recorded` | `recorded` | NutritionIntake.recorded | When the intake was recorded | 0..1 | dateTime |  |  |
| `NutritionIntake.reported[x]` | `NutritionIntake.reported[x]` | `reported[x]` | NutritionIntake.reported[x] | Person or organization that provided the information about the consumption of this food or fluid | 0..1 | boolean, Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `NutritionIntake.status` | `NutritionIntake.status` | `status` | NutritionIntake.status | preparation \| in-progress \| not-done \| on-hold \| stopped \| completed \| entered-in-error \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/event-status|5.0.0` |
| `NutritionIntake.statusReason` | `NutritionIntake.statusReason` | `statusReason` | NutritionIntake.statusReason | Reason for current status | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/clinicalimpression-status-reason` |
| `NutritionIntake.subject` | `NutritionIntake.subject` | `subject` | NutritionIntake.subject | Who is/was consuming the food or fluid | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `NutritionIntake.text` | `NutritionIntake.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

