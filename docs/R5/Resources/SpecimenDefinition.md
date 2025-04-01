Comparison of 
Generated at Tuesday, April 1, 2025 1:39:37 PM

### SpecimenDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | SpecimenDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SpecimenDefinition` |
| Version | 5.0.0 |
| Description | A kind of specimen with associated set of requirements. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2384` |
| Database Snapshot Count | `72` |
| Database Differential Count | `52` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SpecimenDefinition` | `SpecimenDefinition` | `SpecimenDefinition` | SpecimenDefinition | Kind of specimen | 0..* | SpecimenDefinition |  |  |
| `SpecimenDefinition.approvalDate` | `SpecimenDefinition.approvalDate` | `approvalDate` | SpecimenDefinition.approvalDate | When SpecimenDefinition was approved by publisher | 0..1 | date |  |  |
| `SpecimenDefinition.collection` | `SpecimenDefinition.collection` | `collection` | SpecimenDefinition.collection | Specimen collection procedure | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/specimen-collection` |
| `SpecimenDefinition.contact` | `SpecimenDefinition.contact` | `contact` | SpecimenDefinition.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `SpecimenDefinition.contained` | `SpecimenDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `SpecimenDefinition.copyright` | `SpecimenDefinition.copyright` | `copyright` | SpecimenDefinition.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `SpecimenDefinition.copyrightLabel` | `SpecimenDefinition.copyrightLabel` | `copyrightLabel` | SpecimenDefinition.copyrightLabel | Copyright holder and year(s) | 0..1 | string |  |  |
| `SpecimenDefinition.date` | `SpecimenDefinition.date` | `date` | SpecimenDefinition.date | Date status first applied | 0..1 | dateTime |  |  |
| `SpecimenDefinition.derivedFromCanonical` | `SpecimenDefinition.derivedFromCanonical` | `derivedFromCanonical` | SpecimenDefinition.derivedFromCanonical | Based on FHIR definition of another SpecimenDefinition | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/SpecimenDefinition) |  |  |
| `SpecimenDefinition.derivedFromUri` | `SpecimenDefinition.derivedFromUri` | `derivedFromUri` | SpecimenDefinition.derivedFromUri | Based on external definition | 0..* | uri |  |  |
| `SpecimenDefinition.description` | `SpecimenDefinition.description` | `description` | SpecimenDefinition.description | Natural language description of the SpecimenDefinition | 0..1 | markdown |  |  |
| `SpecimenDefinition.effectivePeriod` | `SpecimenDefinition.effectivePeriod` | `effectivePeriod` | SpecimenDefinition.effectivePeriod | The effective date range for the SpecimenDefinition | 0..1 | Period |  |  |
| `SpecimenDefinition.experimental` | `SpecimenDefinition.experimental` | `experimental` | SpecimenDefinition.experimental | If this SpecimenDefinition is not for real usage | 0..1 | boolean |  |  |
| `SpecimenDefinition.extension` | `SpecimenDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SpecimenDefinition.id` | `SpecimenDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `SpecimenDefinition.identifier` | `SpecimenDefinition.identifier` | `identifier` | SpecimenDefinition.identifier | Business identifier | 0..1 | Identifier |  |  |
| `SpecimenDefinition.implicitRules` | `SpecimenDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `SpecimenDefinition.jurisdiction` | `SpecimenDefinition.jurisdiction` | `jurisdiction` | SpecimenDefinition.jurisdiction | Intended jurisdiction for this SpecimenDefinition (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `SpecimenDefinition.language` | `SpecimenDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `SpecimenDefinition.lastReviewDate` | `SpecimenDefinition.lastReviewDate` | `lastReviewDate` | SpecimenDefinition.lastReviewDate | The date on which the asset content was last reviewed by the publisher | 0..1 | date |  |  |
| `SpecimenDefinition.meta` | `SpecimenDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `SpecimenDefinition.modifierExtension` | `SpecimenDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SpecimenDefinition.name` | `SpecimenDefinition.name` | `name` | SpecimenDefinition.name | Name for this {{title}} (computer friendly) | 0..1 | string |  |  |
| `SpecimenDefinition.patientPreparation` | `SpecimenDefinition.patientPreparation` | `patientPreparation` | SpecimenDefinition.patientPreparation | Patient preparation for collection | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/prepare-patient-prior-specimen-collection` |
| `SpecimenDefinition.publisher` | `SpecimenDefinition.publisher` | `publisher` | SpecimenDefinition.publisher | The name of the individual or organization that published the SpecimenDefinition | 0..1 | string |  |  |
| `SpecimenDefinition.purpose` | `SpecimenDefinition.purpose` | `purpose` | SpecimenDefinition.purpose | Why this SpecimenDefinition is defined | 0..1 | markdown |  |  |
| `SpecimenDefinition.status` | `SpecimenDefinition.status` | `status` | SpecimenDefinition.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `SpecimenDefinition.subject[x]` | `SpecimenDefinition.subject[x]` | `subject[x]` | SpecimenDefinition.subject[x] | Type of subject for specimen collection | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Group) |  |  |
| `SpecimenDefinition.text` | `SpecimenDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `SpecimenDefinition.timeAspect` | `SpecimenDefinition.timeAspect` | `timeAspect` | SpecimenDefinition.timeAspect | Time aspect for collection | 0..1 | string |  |  |
| `SpecimenDefinition.title` | `SpecimenDefinition.title` | `title` | SpecimenDefinition.title | Name for this SpecimenDefinition (Human friendly) | 0..1 | string |  |  |
| `SpecimenDefinition.typeCollected` | `SpecimenDefinition.typeCollected` | `typeCollected` | SpecimenDefinition.typeCollected | Kind of material to collect | 0..1 | CodeableConcept | `Example` | `http://terminology.hl7.org/ValueSet/v2-0487` |
| `SpecimenDefinition.typeTested` | `SpecimenDefinition.typeTested` | `typeTested` | SpecimenDefinition.typeTested | Specimen in container intended for testing by lab | 0..* | BackboneElement |  |  |
| `SpecimenDefinition.typeTested.container` | `SpecimenDefinition.typeTested.container` | `container` | SpecimenDefinition.typeTested.container | The specimen's container | 0..1 | BackboneElement |  |  |
| `SpecimenDefinition.typeTested.container.additive` | `SpecimenDefinition.typeTested.container.additive` | `additive` | SpecimenDefinition.typeTested.container.additive | Additive associated with container | 0..* | BackboneElement |  |  |
| `SpecimenDefinition.typeTested.container.additive.additive[x]` | `SpecimenDefinition.typeTested.container.additive.additive[x]` | `additive[x]` | SpecimenDefinition.typeTested.container.additive.additive[x] | Additive associated with container | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/SubstanceDefinition) | `Example` | `http://terminology.hl7.org/ValueSet/v2-0371` |
| `SpecimenDefinition.typeTested.container.additive.extension` | `SpecimenDefinition.typeTested.container.additive.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SpecimenDefinition.typeTested.container.additive.id` | `SpecimenDefinition.typeTested.container.additive.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SpecimenDefinition.typeTested.container.additive.modifierExtension` | `SpecimenDefinition.typeTested.container.additive.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SpecimenDefinition.typeTested.container.cap` | `SpecimenDefinition.typeTested.container.cap` | `cap` | SpecimenDefinition.typeTested.container.cap | Color of container cap | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/container-cap` |
| `SpecimenDefinition.typeTested.container.capacity` | `SpecimenDefinition.typeTested.container.capacity` | `capacity` | SpecimenDefinition.typeTested.container.capacity | The capacity of this kind of container | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `SpecimenDefinition.typeTested.container.description` | `SpecimenDefinition.typeTested.container.description` | `description` | SpecimenDefinition.typeTested.container.description | The description of the kind of container | 0..1 | markdown |  |  |
| `SpecimenDefinition.typeTested.container.extension` | `SpecimenDefinition.typeTested.container.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SpecimenDefinition.typeTested.container.id` | `SpecimenDefinition.typeTested.container.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SpecimenDefinition.typeTested.container.material` | `SpecimenDefinition.typeTested.container.material` | `material` | SpecimenDefinition.typeTested.container.material | The material type used for the container | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/container-material` |
| `SpecimenDefinition.typeTested.container.minimumVolume[x]` | `SpecimenDefinition.typeTested.container.minimumVolume[x]` | `minimumVolume[x]` | SpecimenDefinition.typeTested.container.minimumVolume[x] | Minimum volume | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity], string |  |  |
| `SpecimenDefinition.typeTested.container.modifierExtension` | `SpecimenDefinition.typeTested.container.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SpecimenDefinition.typeTested.container.preparation` | `SpecimenDefinition.typeTested.container.preparation` | `preparation` | SpecimenDefinition.typeTested.container.preparation | Special processing applied to the container for this specimen type | 0..1 | markdown |  |  |
| `SpecimenDefinition.typeTested.container.type` | `SpecimenDefinition.typeTested.container.type` | `type` | SpecimenDefinition.typeTested.container.type | Kind of container associated with the kind of specimen | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/specimen-container-type` |
| `SpecimenDefinition.typeTested.extension` | `SpecimenDefinition.typeTested.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SpecimenDefinition.typeTested.handling` | `SpecimenDefinition.typeTested.handling` | `handling` | SpecimenDefinition.typeTested.handling | Specimen handling before testing | 0..* | BackboneElement |  |  |
| `SpecimenDefinition.typeTested.handling.extension` | `SpecimenDefinition.typeTested.handling.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SpecimenDefinition.typeTested.handling.id` | `SpecimenDefinition.typeTested.handling.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SpecimenDefinition.typeTested.handling.instruction` | `SpecimenDefinition.typeTested.handling.instruction` | `instruction` | SpecimenDefinition.typeTested.handling.instruction | Preservation instruction | 0..1 | markdown |  |  |
| `SpecimenDefinition.typeTested.handling.maxDuration` | `SpecimenDefinition.typeTested.handling.maxDuration` | `maxDuration` | SpecimenDefinition.typeTested.handling.maxDuration | Maximum preservation time | 0..1 | Duration |  |  |
| `SpecimenDefinition.typeTested.handling.modifierExtension` | `SpecimenDefinition.typeTested.handling.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SpecimenDefinition.typeTested.handling.temperatureQualifier` | `SpecimenDefinition.typeTested.handling.temperatureQualifier` | `temperatureQualifier` | SpecimenDefinition.typeTested.handling.temperatureQualifier | Qualifies the interval of temperature | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/handling-condition` |
| `SpecimenDefinition.typeTested.handling.temperatureRange` | `SpecimenDefinition.typeTested.handling.temperatureRange` | `temperatureRange` | SpecimenDefinition.typeTested.handling.temperatureRange | Temperature range for these handling instructions | 0..1 | Range |  |  |
| `SpecimenDefinition.typeTested.id` | `SpecimenDefinition.typeTested.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SpecimenDefinition.typeTested.isDerived` | `SpecimenDefinition.typeTested.isDerived` | `isDerived` | SpecimenDefinition.typeTested.isDerived | Primary or secondary specimen | 0..1 | boolean |  |  |
| `SpecimenDefinition.typeTested.modifierExtension` | `SpecimenDefinition.typeTested.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SpecimenDefinition.typeTested.preference` | `SpecimenDefinition.typeTested.preference` | `preference` | SpecimenDefinition.typeTested.preference | preferred \| alternate | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/specimen-contained-preference|5.0.0` |
| `SpecimenDefinition.typeTested.rejectionCriterion` | `SpecimenDefinition.typeTested.rejectionCriterion` | `rejectionCriterion` | SpecimenDefinition.typeTested.rejectionCriterion | Criterion specified for specimen rejection | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/rejection-criteria` |
| `SpecimenDefinition.typeTested.requirement` | `SpecimenDefinition.typeTested.requirement` | `requirement` | SpecimenDefinition.typeTested.requirement | Requirements for specimen delivery and special handling | 0..1 | markdown |  |  |
| `SpecimenDefinition.typeTested.retentionTime` | `SpecimenDefinition.typeTested.retentionTime` | `retentionTime` | SpecimenDefinition.typeTested.retentionTime | The usual time for retaining this kind of specimen | 0..1 | Duration |  |  |
| `SpecimenDefinition.typeTested.singleUse` | `SpecimenDefinition.typeTested.singleUse` | `singleUse` | SpecimenDefinition.typeTested.singleUse | Specimen for single use only | 0..1 | boolean |  |  |
| `SpecimenDefinition.typeTested.testingDestination` | `SpecimenDefinition.typeTested.testingDestination` | `testingDestination` | SpecimenDefinition.typeTested.testingDestination | Where the specimen will be tested | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/diagnostic-service-sections` |
| `SpecimenDefinition.typeTested.type` | `SpecimenDefinition.typeTested.type` | `type` | SpecimenDefinition.typeTested.type | Type of intended specimen | 0..1 | CodeableConcept | `Example` | `http://terminology.hl7.org/ValueSet/v2-0487` |
| `SpecimenDefinition.url` | `SpecimenDefinition.url` | `url` | SpecimenDefinition.url | Logical canonical URL to reference this SpecimenDefinition (globally unique) | 0..1 | uri |  |  |
| `SpecimenDefinition.useContext` | `SpecimenDefinition.useContext` | `useContext` | SpecimenDefinition.useContext | Content intends to support these contexts | 0..* | UsageContext |  |  |
| `SpecimenDefinition.version` | `SpecimenDefinition.version` | `version` | SpecimenDefinition.version | Business version of the SpecimenDefinition | 0..1 | string |  |  |
| `SpecimenDefinition.versionAlgorithm[x]` | `SpecimenDefinition.versionAlgorithm[x]` | `versionAlgorithm[x]` | SpecimenDefinition.versionAlgorithm[x] | How to compare versions | 0..1 | Coding, string | `Extensible` | `http://hl7.org/fhir/ValueSet/version-algorithm` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [SpecimenDefinition](/docs/R4/Resources/SpecimenDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/SpecimenDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1619`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1620`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SpecimenDefinition](/docs/R4B/Resources/SpecimenDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/SpecimenDefinition\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1043`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1272`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SpecimenDefinition](/docs/R5/Resources/SpecimenDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/SpecimenDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition SpecimenDefinition from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 SpecimenDefinition](/docs/R4/Resources/SpecimenDefinition.md)| Relationship | [R4B SpecimenDefinition](/docs/R4B/Resources/SpecimenDefinition.md)| Relationship | R5 SpecimenDefinition
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `SpecimenDefinition`| _Equivalent_<br/>(33275/33276)| `SpecimenDefinition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47500)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47501)| **`SpecimenDefinition`**
| | | | | `SpecimenDefinition.id`| _Equivalent_<br/>(33277/33278)| `SpecimenDefinition.id`| _Equivalent_<br/>(47502/47503)| **`SpecimenDefinition.id`**
| | | | | `SpecimenDefinition.meta`| _Equivalent_<br/>(33279/33280)| `SpecimenDefinition.meta`| _Equivalent_<br/>(47504/47505)| **`SpecimenDefinition.meta`**
| | | | | `SpecimenDefinition.implicitRules`| _Equivalent_<br/>(33281/33282)| `SpecimenDefinition.implicitRules`| _Equivalent_<br/>(47506/47507)| **`SpecimenDefinition.implicitRules`**
| | | | | `SpecimenDefinition.language`| _Equivalent_<br/>(33283/33284)| `SpecimenDefinition.language`| _Equivalent_<br/>(47508/47509)| **`SpecimenDefinition.language`**
| | | | | `SpecimenDefinition.text`| _Equivalent_<br/>(33285/33286)| `SpecimenDefinition.text`| _Equivalent_<br/>(47510/47511)| **`SpecimenDefinition.text`**
| | | | | `SpecimenDefinition.contained`| _Equivalent_<br/>(33287/33288)| `SpecimenDefinition.contained`| _Equivalent_<br/>(47512/47513)| **`SpecimenDefinition.contained`**
| | | | | `SpecimenDefinition.extension`| _Equivalent_<br/>(33289/33290)| `SpecimenDefinition.extension`| _Equivalent_<br/>(47514/47515)| **`SpecimenDefinition.extension`**
| | | | | `SpecimenDefinition.modifierExtension`| _Equivalent_<br/>(33291/33292)| `SpecimenDefinition.modifierExtension`| _Equivalent_<br/>(47516/47517)| **`SpecimenDefinition.modifierExtension`**
| | | | | | | | | **`SpecimenDefinition.url`**
| | | | | `SpecimenDefinition.identifier`| _Equivalent_<br/>(33293/33294)| `SpecimenDefinition.identifier`| _Equivalent_<br/>(47518/47519)| **`SpecimenDefinition.identifier`**
| | | | | | | | | **`SpecimenDefinition.version`**
| | | | | | | | | **`SpecimenDefinition.versionAlgorithm[x]`**
| | | | | | | | | **`SpecimenDefinition.name`**
| | | | | | | | | **`SpecimenDefinition.title`**
| | | | | | | | | **`SpecimenDefinition.derivedFromCanonical`**
| | | | | | | | | **`SpecimenDefinition.derivedFromUri`**
| | | | | | | | | **`SpecimenDefinition.status`**
| | | | | | | | | **`SpecimenDefinition.experimental`**
| | | | | | | | | **`SpecimenDefinition.subject[x]`**
| | | | | | | | | **`SpecimenDefinition.date`**
| | | | | | | | | **`SpecimenDefinition.publisher`**
| | | | | | | | | **`SpecimenDefinition.contact`**
| | | | | | | | | **`SpecimenDefinition.description`**
| | | | | | | | | **`SpecimenDefinition.useContext`**
| | | | | | | | | **`SpecimenDefinition.jurisdiction`**
| | | | | | | | | **`SpecimenDefinition.purpose`**
| | | | | | | | | **`SpecimenDefinition.copyright`**
| | | | | | | | | **`SpecimenDefinition.copyrightLabel`**
| | | | | | | | | **`SpecimenDefinition.approvalDate`**
| | | | | | | | | **`SpecimenDefinition.lastReviewDate`**
| | | | | | | | | **`SpecimenDefinition.effectivePeriod`**
| | | | | `SpecimenDefinition.typeCollected`| _Equivalent_<br/>(33295/33296)| `SpecimenDefinition.typeCollected`| _Equivalent_<br/>(47520/47521)| **`SpecimenDefinition.typeCollected`**
| | | | | `SpecimenDefinition.patientPreparation`| _Equivalent_<br/>(33297/33298)| `SpecimenDefinition.patientPreparation`| _Equivalent_<br/>(47522/47523)| **`SpecimenDefinition.patientPreparation`**
| | | | | `SpecimenDefinition.timeAspect`| _Equivalent_<br/>(33299/33300)| `SpecimenDefinition.timeAspect`| _Equivalent_<br/>(47524/47525)| **`SpecimenDefinition.timeAspect`**
| | | | | `SpecimenDefinition.collection`| _Equivalent_<br/>(33301/33302)| `SpecimenDefinition.collection`| _Equivalent_<br/>(47526/47527)| **`SpecimenDefinition.collection`**
| | | | | `SpecimenDefinition.typeTested`| _Equivalent_<br/>(33303/33304)| `SpecimenDefinition.typeTested`| _Equivalent_<br/>(47528/47529)| **`SpecimenDefinition.typeTested`**
| | | | | `SpecimenDefinition.typeTested.id`| _Equivalent_<br/>(33305/33306)| `SpecimenDefinition.typeTested.id`| _Equivalent_<br/>(47530/47531)| **`SpecimenDefinition.typeTested.id`**
| | | | | `SpecimenDefinition.typeTested.extension`| _Equivalent_<br/>(33307/33308)| `SpecimenDefinition.typeTested.extension`| _Equivalent_<br/>(47532/47533)| **`SpecimenDefinition.typeTested.extension`**
| | | | | `SpecimenDefinition.typeTested.modifierExtension`| _Equivalent_<br/>(33309/33310)| `SpecimenDefinition.typeTested.modifierExtension`| _Equivalent_<br/>(47534/47535)| **`SpecimenDefinition.typeTested.modifierExtension`**
| | | | | `SpecimenDefinition.typeTested.isDerived`| _Equivalent_<br/>(33311/33312)| `SpecimenDefinition.typeTested.isDerived`| _Equivalent_<br/>(47536/47537)| **`SpecimenDefinition.typeTested.isDerived`**
| | | | | `SpecimenDefinition.typeTested.type`| _Equivalent_<br/>(33313/33314)| `SpecimenDefinition.typeTested.type`| _Equivalent_<br/>(47538/47539)| **`SpecimenDefinition.typeTested.type`**
| | | | | `SpecimenDefinition.typeTested.preference`| _Equivalent_<br/>(33315/33316)| `SpecimenDefinition.typeTested.preference`| _Equivalent_<br/>(47540/47541)| **`SpecimenDefinition.typeTested.preference`**
| | | | | `SpecimenDefinition.typeTested.container`| _Equivalent_<br/>(33317/33318)| `SpecimenDefinition.typeTested.container`| _Equivalent_<br/>(47542/47543)| **`SpecimenDefinition.typeTested.container`**
| | | | | `SpecimenDefinition.typeTested.container.id`| _Equivalent_<br/>(33319/33320)| `SpecimenDefinition.typeTested.container.id`| _Equivalent_<br/>(47544/47545)| **`SpecimenDefinition.typeTested.container.id`**
| | | | | `SpecimenDefinition.typeTested.container.extension`| _Equivalent_<br/>(33321/33322)| `SpecimenDefinition.typeTested.container.extension`| _Equivalent_<br/>(47546/47547)| **`SpecimenDefinition.typeTested.container.extension`**
| | | | | `SpecimenDefinition.typeTested.container.modifierExtension`| _Equivalent_<br/>(33323/33324)| `SpecimenDefinition.typeTested.container.modifierExtension`| _Equivalent_<br/>(47548/47549)| **`SpecimenDefinition.typeTested.container.modifierExtension`**
| | | | | `SpecimenDefinition.typeTested.container.material`| _Equivalent_<br/>(33325/33326)| `SpecimenDefinition.typeTested.container.material`| _Equivalent_<br/>(47550/47551)| **`SpecimenDefinition.typeTested.container.material`**
| | | | | `SpecimenDefinition.typeTested.container.type`| _Equivalent_<br/>(33327/33328)| `SpecimenDefinition.typeTested.container.type`| _Equivalent_<br/>(47552/47553)| **`SpecimenDefinition.typeTested.container.type`**
| | | | | `SpecimenDefinition.typeTested.container.cap`| _Equivalent_<br/>(33329/33330)| `SpecimenDefinition.typeTested.container.cap`| _Equivalent_<br/>(47554/47555)| **`SpecimenDefinition.typeTested.container.cap`**
| | | | | `SpecimenDefinition.typeTested.container.description`| _Equivalent_<br/>(33331/33332)| `SpecimenDefinition.typeTested.container.description`| _Equivalent_<br/>(47556/47557)| **`SpecimenDefinition.typeTested.container.description`**
| | | | | `SpecimenDefinition.typeTested.container.capacity`| _Equivalent_<br/>(33333/33334)| `SpecimenDefinition.typeTested.container.capacity`| _Equivalent_<br/>(47558/47559)| **`SpecimenDefinition.typeTested.container.capacity`**
| | | | | `SpecimenDefinition.typeTested.container.minimumVolume[x]`| _Equivalent_<br/>(33335/33336)| `SpecimenDefinition.typeTested.container.minimumVolume[x]`| _Equivalent_<br/>(47560/47561)| **`SpecimenDefinition.typeTested.container.minimumVolume[x]`**
| | | | | `SpecimenDefinition.typeTested.container.additive`| _Equivalent_<br/>(33337/33338)| `SpecimenDefinition.typeTested.container.additive`| _Equivalent_<br/>(47562/47563)| **`SpecimenDefinition.typeTested.container.additive`**
| | | | | `SpecimenDefinition.typeTested.container.additive.id`| _Equivalent_<br/>(33339/33340)| `SpecimenDefinition.typeTested.container.additive.id`| _Equivalent_<br/>(47564/47565)| **`SpecimenDefinition.typeTested.container.additive.id`**
| | | | | `SpecimenDefinition.typeTested.container.additive.extension`| _Equivalent_<br/>(33341/33342)| `SpecimenDefinition.typeTested.container.additive.extension`| _Equivalent_<br/>(47566/47567)| **`SpecimenDefinition.typeTested.container.additive.extension`**
| | | | | `SpecimenDefinition.typeTested.container.additive.modifierExtension`| _Equivalent_<br/>(33343/33344)| `SpecimenDefinition.typeTested.container.additive.modifierExtension`| _Equivalent_<br/>(47568/47569)| **`SpecimenDefinition.typeTested.container.additive.modifierExtension`**
| | | | | `SpecimenDefinition.typeTested.container.additive.additive[x]`| _Equivalent_<br/>(33345/33346)| `SpecimenDefinition.typeTested.container.additive.additive[x]`| →→→→ _RelatedTo_ →→→→ <br/>(47570)<hr/>←←←← _RelatedTo_ ←←←← <br/>(47571)| **`SpecimenDefinition.typeTested.container.additive.additive[x]`**
| | | | | `SpecimenDefinition.typeTested.container.preparation`| _Equivalent_<br/>(33347/33348)| `SpecimenDefinition.typeTested.container.preparation`| _Equivalent_<br/>(47572/47573)| **`SpecimenDefinition.typeTested.container.preparation`**
| | | | | `SpecimenDefinition.typeTested.requirement`| _Equivalent_<br/>(33349/33350)| `SpecimenDefinition.typeTested.requirement`| _Equivalent_<br/>(47574/47575)| **`SpecimenDefinition.typeTested.requirement`**
| | | | | `SpecimenDefinition.typeTested.retentionTime`| _Equivalent_<br/>(33351/33352)| `SpecimenDefinition.typeTested.retentionTime`| _Equivalent_<br/>(47576/47577)| **`SpecimenDefinition.typeTested.retentionTime`**
| | | | | | | | | **`SpecimenDefinition.typeTested.singleUse`**
| | | | | `SpecimenDefinition.typeTested.rejectionCriterion`| _Equivalent_<br/>(33353/33354)| `SpecimenDefinition.typeTested.rejectionCriterion`| _Equivalent_<br/>(47578/47579)| **`SpecimenDefinition.typeTested.rejectionCriterion`**
| | | | | `SpecimenDefinition.typeTested.handling`| _Equivalent_<br/>(33355/33356)| `SpecimenDefinition.typeTested.handling`| _Equivalent_<br/>(47580/47581)| **`SpecimenDefinition.typeTested.handling`**
| | | | | `SpecimenDefinition.typeTested.handling.id`| _Equivalent_<br/>(33357/33358)| `SpecimenDefinition.typeTested.handling.id`| _Equivalent_<br/>(47582/47583)| **`SpecimenDefinition.typeTested.handling.id`**
| | | | | `SpecimenDefinition.typeTested.handling.extension`| _Equivalent_<br/>(33359/33360)| `SpecimenDefinition.typeTested.handling.extension`| _Equivalent_<br/>(47584/47585)| **`SpecimenDefinition.typeTested.handling.extension`**
| | | | | `SpecimenDefinition.typeTested.handling.modifierExtension`| _Equivalent_<br/>(33361/33362)| `SpecimenDefinition.typeTested.handling.modifierExtension`| _Equivalent_<br/>(47586/47587)| **`SpecimenDefinition.typeTested.handling.modifierExtension`**
| | | | | `SpecimenDefinition.typeTested.handling.temperatureQualifier`| _Equivalent_<br/>(33363/33364)| `SpecimenDefinition.typeTested.handling.temperatureQualifier`| _Equivalent_<br/>(47588/47589)| **`SpecimenDefinition.typeTested.handling.temperatureQualifier`**
| | | | | `SpecimenDefinition.typeTested.handling.temperatureRange`| _Equivalent_<br/>(33365/33366)| `SpecimenDefinition.typeTested.handling.temperatureRange`| _Equivalent_<br/>(47590/47591)| **`SpecimenDefinition.typeTested.handling.temperatureRange`**
| | | | | `SpecimenDefinition.typeTested.handling.maxDuration`| _Equivalent_<br/>(33367/33368)| `SpecimenDefinition.typeTested.handling.maxDuration`| _Equivalent_<br/>(47592/47593)| **`SpecimenDefinition.typeTested.handling.maxDuration`**
| | | | | `SpecimenDefinition.typeTested.handling.instruction`| _Equivalent_<br/>(33369/33370)| `SpecimenDefinition.typeTested.handling.instruction`| _Equivalent_<br/>(47594/47595)| **`SpecimenDefinition.typeTested.handling.instruction`**
| | | | | | | | | **`SpecimenDefinition.typeTested.testingDestination`**
| | | | | *48 of 48 elements used* | | *48 of 48 elements used* | | *72 of 72 elements used* 

