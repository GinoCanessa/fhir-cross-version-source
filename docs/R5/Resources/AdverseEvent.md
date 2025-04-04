Comparison of 
Generated at Friday, April 4, 2025 2:59:02 PM

### AdverseEvent

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | AdverseEvent |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/AdverseEvent` |
| Version | 5.0.0 |
| Description | An event (i.e. any change to current patient status) that may be related to unintended effects on a patient or research participant. The unintended effects may require additional monitoring, treatment, hospitalization, or may result in death. The AdverseEvent resource also extends to potential or avoided events that could have had such effects. There are two major domains where the AdverseEvent resource is expected to be used. One is in clinical care reported adverse events and the other is in reporting adverse events in clinical  research trial management.  Adverse events can be reported by healthcare providers, patients, caregivers or by medical products manufacturers.  Given the differences between these two concepts, we recommend consulting the domain specific implementation guides when implementing the AdverseEvent Resource. The implementation guides include specific extensions, value sets and constraints. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2252` |
| Database Snapshot Count | `65` |
| Database Differential Count | `36` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `AdverseEvent` | `AdverseEvent` | `AdverseEvent` | AdverseEvent | An event that may be related to unintended effects on a patient or research participant | 0..* | AdverseEvent |  |  |
| `AdverseEvent.actuality` | `AdverseEvent.actuality` | `actuality` | AdverseEvent.actuality | actual \| potential | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/adverse-event-actuality|5.0.0` |
| `AdverseEvent.category` | `AdverseEvent.category` | `category` | AdverseEvent.category | wrong-patient \| procedure-mishap \| medication-mishap \| device \| unsafe-physical-environment \| hospital-aquired-infection \| wrong-body-site | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/adverse-event-category` |
| `AdverseEvent.code` | `AdverseEvent.code` | `code` | AdverseEvent.code | Event or incident that occurred or was averted | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/adverse-event-type` |
| `AdverseEvent.contained` | `AdverseEvent.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `AdverseEvent.contributingFactor` | `AdverseEvent.contributingFactor` | `contributingFactor` | AdverseEvent.contributingFactor | Contributing factors suspected to have increased the probability or severity of the adverse event | 0..* | BackboneElement |  |  |
| `AdverseEvent.contributingFactor.extension` | `AdverseEvent.contributingFactor.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AdverseEvent.contributingFactor.id` | `AdverseEvent.contributingFactor.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AdverseEvent.contributingFactor.item[x]` | `AdverseEvent.contributingFactor.item[x]` | `item[x]` | AdverseEvent.contributingFactor.item[x] | Item suspected to have increased the probability or severity of the adverse event | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/AllergyIntolerance), Reference(http://hl7.org/fhir/StructureDefinition/Condition), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/DeviceUsage), Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/FamilyMemberHistory), Reference(http://hl7.org/fhir/StructureDefinition/Immunization), Reference(http://hl7.org/fhir/StructureDefinition/MedicationAdministration), Reference(http://hl7.org/fhir/StructureDefinition/MedicationStatement), Reference(http://hl7.org/fhir/StructureDefinition/Observation), Reference(http://hl7.org/fhir/StructureDefinition/Procedure) | `Example` | `http://hl7.org/fhir/ValueSet/adverse-event-contributing-factor` |
| `AdverseEvent.contributingFactor.modifierExtension` | `AdverseEvent.contributingFactor.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AdverseEvent.detected` | `AdverseEvent.detected` | `detected` | AdverseEvent.detected | When the event was detected | 0..1 | dateTime |  |  |
| `AdverseEvent.encounter` | `AdverseEvent.encounter` | `encounter` | AdverseEvent.encounter | The Encounter associated with the start of the AdverseEvent | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `AdverseEvent.expectedInResearchStudy` | `AdverseEvent.expectedInResearchStudy` | `expectedInResearchStudy` | AdverseEvent.expectedInResearchStudy | Considered likely or probable or anticipated in the research study | 0..1 | boolean |  |  |
| `AdverseEvent.extension` | `AdverseEvent.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AdverseEvent.id` | `AdverseEvent.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `AdverseEvent.identifier` | `AdverseEvent.identifier` | `identifier` | AdverseEvent.identifier | Business identifier for the event | 0..* | Identifier |  |  |
| `AdverseEvent.implicitRules` | `AdverseEvent.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `AdverseEvent.language` | `AdverseEvent.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `AdverseEvent.location` | `AdverseEvent.location` | `location` | AdverseEvent.location | Location where adverse event occurred | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `AdverseEvent.meta` | `AdverseEvent.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `AdverseEvent.mitigatingAction` | `AdverseEvent.mitigatingAction` | `mitigatingAction` | AdverseEvent.mitigatingAction | Ameliorating actions taken after the adverse event occured in order to reduce the extent of harm | 0..* | BackboneElement |  |  |
| `AdverseEvent.mitigatingAction.extension` | `AdverseEvent.mitigatingAction.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AdverseEvent.mitigatingAction.id` | `AdverseEvent.mitigatingAction.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AdverseEvent.mitigatingAction.item[x]` | `AdverseEvent.mitigatingAction.item[x]` | `item[x]` | AdverseEvent.mitigatingAction.item[x] | Ameliorating action taken after the adverse event occured in order to reduce the extent of harm | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/MedicationAdministration), Reference(http://hl7.org/fhir/StructureDefinition/MedicationRequest), Reference(http://hl7.org/fhir/StructureDefinition/Procedure) | `Example` | `http://hl7.org/fhir/ValueSet/adverse-event-mitigating-action` |
| `AdverseEvent.mitigatingAction.modifierExtension` | `AdverseEvent.mitigatingAction.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AdverseEvent.modifierExtension` | `AdverseEvent.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `AdverseEvent.note` | `AdverseEvent.note` | `note` | AdverseEvent.note | Comment on adverse event | 0..* | Annotation |  |  |
| `AdverseEvent.occurrence[x]` | `AdverseEvent.occurrence[x]` | `occurrence[x]` | AdverseEvent.occurrence[x] | When the event occurred | 0..1 | dateTime, Period, Timing |  |  |
| `AdverseEvent.outcome` | `AdverseEvent.outcome` | `outcome` | AdverseEvent.outcome | Type of outcome from the adverse event | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/adverse-event-outcome` |
| `AdverseEvent.participant` | `AdverseEvent.participant` | `participant` | AdverseEvent.participant | Who was involved in the adverse event or the potential adverse event and what they did | 0..* | BackboneElement |  |  |
| `AdverseEvent.participant.actor` | `AdverseEvent.participant.actor` | `actor` | AdverseEvent.participant.actor | Who was involved in the adverse event or the potential adverse event | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson), Reference(http://hl7.org/fhir/StructureDefinition/ResearchSubject) |  |  |
| `AdverseEvent.participant.extension` | `AdverseEvent.participant.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AdverseEvent.participant.function` | `AdverseEvent.participant.function` | `function` | AdverseEvent.participant.function | Type of involvement | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/adverse-event-participant-function` |
| `AdverseEvent.participant.id` | `AdverseEvent.participant.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AdverseEvent.participant.modifierExtension` | `AdverseEvent.participant.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AdverseEvent.preventiveAction` | `AdverseEvent.preventiveAction` | `preventiveAction` | AdverseEvent.preventiveAction | Preventive actions that contributed to avoiding the adverse event | 0..* | BackboneElement |  |  |
| `AdverseEvent.preventiveAction.extension` | `AdverseEvent.preventiveAction.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AdverseEvent.preventiveAction.id` | `AdverseEvent.preventiveAction.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AdverseEvent.preventiveAction.item[x]` | `AdverseEvent.preventiveAction.item[x]` | `item[x]` | AdverseEvent.preventiveAction.item[x] | Action that contributed to avoiding the adverse event | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/Immunization), Reference(http://hl7.org/fhir/StructureDefinition/MedicationAdministration), Reference(http://hl7.org/fhir/StructureDefinition/MedicationRequest), Reference(http://hl7.org/fhir/StructureDefinition/Procedure) | `Example` | `http://hl7.org/fhir/ValueSet/adverse-event-preventive-action` |
| `AdverseEvent.preventiveAction.modifierExtension` | `AdverseEvent.preventiveAction.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AdverseEvent.recordedDate` | `AdverseEvent.recordedDate` | `recordedDate` | AdverseEvent.recordedDate | When the event was recorded | 0..1 | dateTime |  |  |
| `AdverseEvent.recorder` | `AdverseEvent.recorder` | `recorder` | AdverseEvent.recorder | Who recorded the adverse event | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson), Reference(http://hl7.org/fhir/StructureDefinition/ResearchSubject) |  |  |
| `AdverseEvent.resultingEffect` | `AdverseEvent.resultingEffect` | `resultingEffect` | AdverseEvent.resultingEffect | Effect on the subject due to this event | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Condition), Reference(http://hl7.org/fhir/StructureDefinition/Observation) |  |  |
| `AdverseEvent.seriousness` | `AdverseEvent.seriousness` | `seriousness` | AdverseEvent.seriousness | Seriousness or gravity of the event | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/adverse-event-seriousness` |
| `AdverseEvent.status` | `AdverseEvent.status` | `status` | AdverseEvent.status | in-progress \| completed \| entered-in-error \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/adverse-event-status|5.0.0` |
| `AdverseEvent.study` | `AdverseEvent.study` | `study` | AdverseEvent.study | Research study that the subject is enrolled in | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ResearchStudy) |  |  |
| `AdverseEvent.subject` | `AdverseEvent.subject` | `subject` | AdverseEvent.subject | Subject impacted by event | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson), Reference(http://hl7.org/fhir/StructureDefinition/ResearchSubject) |  |  |
| `AdverseEvent.supportingInfo` | `AdverseEvent.supportingInfo` | `supportingInfo` | AdverseEvent.supportingInfo | Supporting information relevant to the event | 0..* | BackboneElement |  |  |
| `AdverseEvent.supportingInfo.extension` | `AdverseEvent.supportingInfo.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AdverseEvent.supportingInfo.id` | `AdverseEvent.supportingInfo.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AdverseEvent.supportingInfo.item[x]` | `AdverseEvent.supportingInfo.item[x]` | `item[x]` | AdverseEvent.supportingInfo.item[x] | Subject medical history or document relevant to this adverse event | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/AllergyIntolerance), Reference(http://hl7.org/fhir/StructureDefinition/Condition), Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/FamilyMemberHistory), Reference(http://hl7.org/fhir/StructureDefinition/Immunization), Reference(http://hl7.org/fhir/StructureDefinition/MedicationAdministration), Reference(http://hl7.org/fhir/StructureDefinition/MedicationStatement), Reference(http://hl7.org/fhir/StructureDefinition/Observation), Reference(http://hl7.org/fhir/StructureDefinition/Procedure), Reference(http://hl7.org/fhir/StructureDefinition/QuestionnaireResponse) | `Example` | `http://hl7.org/fhir/ValueSet/adverse-event-supporting-info` |
| `AdverseEvent.supportingInfo.modifierExtension` | `AdverseEvent.supportingInfo.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AdverseEvent.suspectEntity` | `AdverseEvent.suspectEntity` | `suspectEntity` | AdverseEvent.suspectEntity | The suspected agent causing the adverse event | 0..* | BackboneElement |  |  |
| `AdverseEvent.suspectEntity.causality` | `AdverseEvent.suspectEntity.causality` | `causality` | AdverseEvent.suspectEntity.causality | Information on the possible cause of the event | 0..1 | BackboneElement |  |  |
| `AdverseEvent.suspectEntity.causality.assessmentMethod` | `AdverseEvent.suspectEntity.causality.assessmentMethod` | `assessmentMethod` | AdverseEvent.suspectEntity.causality.assessmentMethod | Method of evaluating the relatedness of the suspected entity to the event | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/adverse-event-causality-method` |
| `AdverseEvent.suspectEntity.causality.author` | `AdverseEvent.suspectEntity.causality.author` | `author` | AdverseEvent.suspectEntity.causality.author | Author of the information on the possible cause of the event | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson), Reference(http://hl7.org/fhir/StructureDefinition/ResearchSubject) |  |  |
| `AdverseEvent.suspectEntity.causality.entityRelatedness` | `AdverseEvent.suspectEntity.causality.entityRelatedness` | `entityRelatedness` | AdverseEvent.suspectEntity.causality.entityRelatedness | Result of the assessment regarding the relatedness of the suspected entity to the event | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/adverse-event-causality-assess` |
| `AdverseEvent.suspectEntity.causality.extension` | `AdverseEvent.suspectEntity.causality.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AdverseEvent.suspectEntity.causality.id` | `AdverseEvent.suspectEntity.causality.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AdverseEvent.suspectEntity.causality.modifierExtension` | `AdverseEvent.suspectEntity.causality.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AdverseEvent.suspectEntity.extension` | `AdverseEvent.suspectEntity.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AdverseEvent.suspectEntity.id` | `AdverseEvent.suspectEntity.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AdverseEvent.suspectEntity.instance[x]` | `AdverseEvent.suspectEntity.instance[x]` | `instance[x]` | AdverseEvent.suspectEntity.instance[x] | Refers to the specific entity that caused the adverse event | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Immunization), Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/MedicationAdministration), Reference(http://hl7.org/fhir/StructureDefinition/MedicationStatement), Reference(http://hl7.org/fhir/StructureDefinition/Procedure), Reference(http://hl7.org/fhir/StructureDefinition/ResearchStudy), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `AdverseEvent.suspectEntity.modifierExtension` | `AdverseEvent.suspectEntity.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AdverseEvent.text` | `AdverseEvent.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [AdverseEvent](/docs/R3/Resources/AdverseEvent.md)<br/> `http://hl7.org/fhir/StructureDefinition/AdverseEvent\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `417`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `613`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AdverseEvent](/docs/R4/Resources/AdverseEvent.md)<br/> `http://hl7.org/fhir/StructureDefinition/AdverseEvent\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1391`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1392`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AdverseEvent](/docs/R4B/Resources/AdverseEvent.md)<br/> `http://hl7.org/fhir/StructureDefinition/AdverseEvent\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `931`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1160`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AdverseEvent](/docs/R5/Resources/AdverseEvent.md)<br/> `http://hl7.org/fhir/StructureDefinition/AdverseEvent\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition AdverseEvent from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 AdverseEvent](/docs/R3/Resources/AdverseEvent.md)| Relationship | [R4 AdverseEvent](/docs/R4/Resources/AdverseEvent.md)| Relationship | [R4B AdverseEvent](/docs/R4B/Resources/AdverseEvent.md)| Relationship | R5 AdverseEvent
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `AdverseEvent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10054)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10055)| `AdverseEvent`| _Equivalent_<br/>(21579/21580)| `AdverseEvent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36713)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36714)| **`AdverseEvent`**
| | | `AdverseEvent.id`| _Equivalent_<br/>(10056/10057)| `AdverseEvent.id`| _Equivalent_<br/>(21581/21582)| `AdverseEvent.id`| _Equivalent_<br/>(36715/36716)| **`AdverseEvent.id`**
| | | `AdverseEvent.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10058)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10059)| `AdverseEvent.meta`| _Equivalent_<br/>(21583/21584)| `AdverseEvent.meta`| _Equivalent_<br/>(36717/36718)| **`AdverseEvent.meta`**
| | | `AdverseEvent.implicitRules`| _Equivalent_<br/>(10060/10061)| `AdverseEvent.implicitRules`| _Equivalent_<br/>(21585/21586)| `AdverseEvent.implicitRules`| _Equivalent_<br/>(36719/36720)| **`AdverseEvent.implicitRules`**
| | | `AdverseEvent.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10062)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(10063)| `AdverseEvent.language`| _Equivalent_<br/>(21587/21588)| `AdverseEvent.language`| _Equivalent_<br/>(36721/36722)| **`AdverseEvent.language`**
| | | `AdverseEvent.text`| _Equivalent_<br/>(10064/10065)| `AdverseEvent.text`| _Equivalent_<br/>(21589/21590)| `AdverseEvent.text`| _Equivalent_<br/>(36723/36724)| **`AdverseEvent.text`**
| | | `AdverseEvent.contained`| _Equivalent_<br/>(10066/10067)| `AdverseEvent.contained`| _Equivalent_<br/>(21591/21592)| `AdverseEvent.contained`| _Equivalent_<br/>(36725/36726)| **`AdverseEvent.contained`**
| | | `AdverseEvent.extension`| _Equivalent_<br/>(10068/10069)| `AdverseEvent.extension`| _Equivalent_<br/>(21593/21594)| `AdverseEvent.extension`| _Equivalent_<br/>(36727/36728)| **`AdverseEvent.extension`**
| | | `AdverseEvent.modifierExtension`| _Equivalent_<br/>(10070/10071)| `AdverseEvent.modifierExtension`| _Equivalent_<br/>(21595/21596)| `AdverseEvent.modifierExtension`| _Equivalent_<br/>(36729/36730)| **`AdverseEvent.modifierExtension`**
| | | `AdverseEvent.identifier`| _Equivalent_<br/>(10072/10073)| `AdverseEvent.identifier`| _Equivalent_<br/>(21597/21598)| `AdverseEvent.identifier`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36731)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36732)| **`AdverseEvent.identifier`**
| | | | | | | | | **`AdverseEvent.status`**
| | | `AdverseEvent.type`| →→→→ _RelatedTo_ →→→→ <br/>(808)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1340)| `AdverseEvent.actuality`| _Equivalent_<br/>(21599/21600)| `AdverseEvent.actuality`| _Equivalent_<br/>(36733/36734)| **`AdverseEvent.actuality`**
| | | `AdverseEvent.category`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10074)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(10075)| `AdverseEvent.category`| _Equivalent_<br/>(21601/21602)| `AdverseEvent.category`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36735)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36736)| **`AdverseEvent.category`**
| | | `AdverseEvent.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(809)<hr/>←←←← _Equivalent_ ←←←← <br/>(1347)| `AdverseEvent.event`| _Equivalent_<br/>(21603/21604)| `AdverseEvent.event`| _Equivalent_<br/>(1715/1959)| **`AdverseEvent.code`**
| | | `AdverseEvent.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10076)<hr/>←←←← _RelatedTo_ ←←←← <br/>(10077)| `AdverseEvent.subject`| _Equivalent_<br/>(21605/21606)| `AdverseEvent.subject`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36737)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36738)| **`AdverseEvent.subject`**
| | | | | `AdverseEvent.encounter`| _Equivalent_<br/>(21607/21608)| `AdverseEvent.encounter`| _Equivalent_<br/>(36739/36740)| **`AdverseEvent.encounter`**
| | | `AdverseEvent.date`| _Equivalent_<br/>(10078/10079)| `AdverseEvent.date`| _Equivalent_<br/>(21609/21610)| `AdverseEvent.date`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1719)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1963)| **`AdverseEvent.occurrence[x]`**
| | | | | `AdverseEvent.detected`| _Equivalent_<br/>(21611/21612)| `AdverseEvent.detected`| _Equivalent_<br/>(36741/36742)| **`AdverseEvent.detected`**
| | | | | `AdverseEvent.recordedDate`| _Equivalent_<br/>(21613/21614)| `AdverseEvent.recordedDate`| _Equivalent_<br/>(36743/36744)| **`AdverseEvent.recordedDate`**
| | | `AdverseEvent.reaction`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(802)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1342)| `AdverseEvent.resultingCondition`| _Equivalent_<br/>(21615/21616)| `AdverseEvent.resultingCondition`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1716)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1960)| **`AdverseEvent.resultingEffect`**
| | | `AdverseEvent.location`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10080)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10081)| `AdverseEvent.location`| _Equivalent_<br/>(21617/21618)| `AdverseEvent.location`| _Equivalent_<br/>(36745/36746)| **`AdverseEvent.location`**
| | | `AdverseEvent.seriousness`| _Equivalent_<br/>(10082/10083)| `AdverseEvent.seriousness`| _Equivalent_<br/>(21619/21620)| `AdverseEvent.seriousness`| _Equivalent_<br/>(36747/36748)| **`AdverseEvent.seriousness`**
| | | `AdverseEvent.outcome`| _Equivalent_<br/>(10084/10085)| `AdverseEvent.outcome`| _Equivalent_<br/>(21623/21624)| `AdverseEvent.outcome`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36750)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36751)| **`AdverseEvent.outcome`**
| | | `AdverseEvent.recorder`| →→→→ _RelatedTo_ →→→→ <br/>(10086)<hr/>←←←← _RelatedTo_ ←←←← <br/>(10087)| `AdverseEvent.recorder`| _Equivalent_<br/>(21625/21626)| `AdverseEvent.recorder`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36752)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36753)| **`AdverseEvent.recorder`**
| | | | | | | | | **`AdverseEvent.participant`**
| | | | | | | | | **`AdverseEvent.participant.id`**
| | | | | | | | | **`AdverseEvent.participant.extension`**
| | | | | | | | | **`AdverseEvent.participant.modifierExtension`**
| | | | | | | | | **`AdverseEvent.participant.function`**
| | | | | | | | | **`AdverseEvent.participant.actor`**
| | | `AdverseEvent.study`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10104)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10105)| `AdverseEvent.study`| _Equivalent_<br/>(21659/21660)| `AdverseEvent.study`| _Equivalent_<br/>(36776/36777)| **`AdverseEvent.study`**
| | | | | | | | | **`AdverseEvent.expectedInResearchStudy`**
| | | `AdverseEvent.suspectEntity`| _Equivalent_<br/>(10088/10089)| `AdverseEvent.suspectEntity`| _Equivalent_<br/>(21629/21630)| `AdverseEvent.suspectEntity`| _Equivalent_<br/>(36755/36756)| **`AdverseEvent.suspectEntity`**
| | | `AdverseEvent.suspectEntity.id`| _Equivalent_<br/>(10090/10091)| `AdverseEvent.suspectEntity.id`| _Equivalent_<br/>(21631/21632)| `AdverseEvent.suspectEntity.id`| _Equivalent_<br/>(36757/36758)| **`AdverseEvent.suspectEntity.id`**
| | | `AdverseEvent.suspectEntity.extension`| _Equivalent_<br/>(10092/10093)| `AdverseEvent.suspectEntity.extension`| _Equivalent_<br/>(21633/21634)| `AdverseEvent.suspectEntity.extension`| _Equivalent_<br/>(36759/36760)| **`AdverseEvent.suspectEntity.extension`**
| | | `AdverseEvent.suspectEntity.modifierExtension`| _Equivalent_<br/>(10094/10095)| `AdverseEvent.suspectEntity.modifierExtension`| _Equivalent_<br/>(21635/21636)| `AdverseEvent.suspectEntity.modifierExtension`| _Equivalent_<br/>(36761/36762)| **`AdverseEvent.suspectEntity.modifierExtension`**
| | | `AdverseEvent.suspectEntity.instance`| →→→→ _RelatedTo_ →→→→ <br/>(10096)<hr/>←←←← _RelatedTo_ ←←←← <br/>(10097)| `AdverseEvent.suspectEntity.instance`| _Equivalent_<br/>(21637/21638)| `AdverseEvent.suspectEntity.instance`| →→→→ _RelatedTo_ →→→→ <br/>(1717)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1961)| **`AdverseEvent.suspectEntity.instance[x]`**
| | | `AdverseEvent.suspectEntity.causality`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10098)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(10099)| `AdverseEvent.suspectEntity.causality`| _Equivalent_<br/>(21639/21640)| `AdverseEvent.suspectEntity.causality`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36763)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36764)| **`AdverseEvent.suspectEntity.causality`**
| | | | | `AdverseEvent.suspectEntity.causality.id`| _Equivalent_<br/>(21641/21642)| `AdverseEvent.suspectEntity.causality.id`| _Equivalent_<br/>(36765/36766)| **`AdverseEvent.suspectEntity.causality.id`**
| | | | | `AdverseEvent.suspectEntity.causality.extension`| _Equivalent_<br/>(21643/21644)| `AdverseEvent.suspectEntity.causality.extension`| _Equivalent_<br/>(36767/36768)| **`AdverseEvent.suspectEntity.causality.extension`**
| | | | | `AdverseEvent.suspectEntity.causality.modifierExtension`| _Equivalent_<br/>(21645/21646)| `AdverseEvent.suspectEntity.causality.modifierExtension`| _Equivalent_<br/>(36769/36770)| **`AdverseEvent.suspectEntity.causality.modifierExtension`**
| | | `AdverseEvent.suspectEntity.causalityAssessment`| _Equivalent_<br/>(803/1343)| `AdverseEvent.suspectEntity.causality.assessment`| _Equivalent_<br/>(21647/21648)| `AdverseEvent.suspectEntity.causality.assessment`| _Equivalent_<br/>(1720/1964)| **`AdverseEvent.suspectEntity.causality.assessmentMethod`**
| | | `AdverseEvent.suspectEntity.causalityProductRelatedness`| _Equivalent_<br/>(806/1346)| `AdverseEvent.suspectEntity.causality.productRelatedness`| _Equivalent_<br/>(21649/21650)| `AdverseEvent.suspectEntity.causality.productRelatedness`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1718)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1962)| **`AdverseEvent.suspectEntity.causality.entityRelatedness`**
| | | `AdverseEvent.suspectEntity.causalityAuthor`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(804)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1344)| `AdverseEvent.suspectEntity.causality.author`| _Equivalent_<br/>(21651/21652)| `AdverseEvent.suspectEntity.causality.author`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36771)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36772)| **`AdverseEvent.suspectEntity.causality.author`**
| | | | | | | | | **`AdverseEvent.contributingFactor`**
| | | | | | | | | **`AdverseEvent.contributingFactor.id`**
| | | | | | | | | **`AdverseEvent.contributingFactor.extension`**
| | | | | | | | | **`AdverseEvent.contributingFactor.modifierExtension`**
| | | | | | | | | **`AdverseEvent.contributingFactor.item[x]`**
| | | | | | | | | **`AdverseEvent.preventiveAction`**
| | | | | | | | | **`AdverseEvent.preventiveAction.id`**
| | | | | | | | | **`AdverseEvent.preventiveAction.extension`**
| | | | | | | | | **`AdverseEvent.preventiveAction.modifierExtension`**
| | | | | | | | | **`AdverseEvent.preventiveAction.item[x]`**
| | | | | | | | | **`AdverseEvent.mitigatingAction`**
| | | | | | | | | **`AdverseEvent.mitigatingAction.id`**
| | | | | | | | | **`AdverseEvent.mitigatingAction.extension`**
| | | | | | | | | **`AdverseEvent.mitigatingAction.modifierExtension`**
| | | | | | | | | **`AdverseEvent.mitigatingAction.item[x]`**
| | | | | | | | | **`AdverseEvent.supportingInfo`**
| | | | | | | | | **`AdverseEvent.supportingInfo.id`**
| | | | | | | | | **`AdverseEvent.supportingInfo.extension`**
| | | | | | | | | **`AdverseEvent.supportingInfo.modifierExtension`**
| | | | | | | | | **`AdverseEvent.supportingInfo.item[x]`**
| | | | | | | | | **`AdverseEvent.note`**
| | | *29 of 35 elements used* <br/>remaining elements:<br/>`AdverseEvent.description`, `AdverseEvent.eventParticipant`, `AdverseEvent.referenceDocument`, `AdverseEvent.subjectMedicalHistory`, `AdverseEvent.suspectEntity.causalityMethod`, `AdverseEvent.suspectEntity.causalityResult`| | *36 of 41 elements used* <br/>remaining elements:<br/>`AdverseEvent.contributor`, `AdverseEvent.referenceDocument`, `AdverseEvent.severity`, `AdverseEvent.subjectMedicalHistory`, `AdverseEvent.suspectEntity.causality.method`| | *36 of 41 elements used* <br/>remaining elements:<br/>`AdverseEvent.contributor`, `AdverseEvent.referenceDocument`, `AdverseEvent.severity`, `AdverseEvent.subjectMedicalHistory`, `AdverseEvent.suspectEntity.causality.method`| | *65 of 65 elements used* 

