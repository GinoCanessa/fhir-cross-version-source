Comparison of 
Generated at Monday, April 14, 2025 6:17:45 PM

### Specimen

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Specimen |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Specimen` |
| Version | 5.0.0 |
| Description | A sample to be used for analysis. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2383` |
| Database Snapshot Count | `55` |
| Database Differential Count | `35` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Specimen` | `Specimen` | `Specimen` | Specimen | Sample for analysis | 0..* | Specimen |  |  |
| `Specimen.accessionIdentifier` | `Specimen.accessionIdentifier` | `accessionIdentifier` | Specimen.accessionIdentifier | Identifier assigned by the lab | 0..1 | Identifier |  |  |
| `Specimen.collection` | `Specimen.collection` | `collection` | Specimen.collection | Collection details | 0..1 | BackboneElement |  |  |
| `Specimen.collection.bodySite` | `Specimen.collection.bodySite` | `bodySite` | Specimen.collection.bodySite | Anatomical collection site | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/BodyStructure) | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `Specimen.collection.collected[x]` | `Specimen.collection.collected[x]` | `collected[x]` | Specimen.collection.collected[x] | Collection time | 0..1 | dateTime, Period |  |  |
| `Specimen.collection.collector` | `Specimen.collection.collector` | `collector` | Specimen.collection.collector | Who collected the specimen | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Specimen.collection.device` | `Specimen.collection.device` | `device` | Specimen.collection.device | Device used to perform collection | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/Device) | `Example` |  |
| `Specimen.collection.duration` | `Specimen.collection.duration` | `duration` | Specimen.collection.duration | How long it took to collect specimen | 0..1 | Duration |  |  |
| `Specimen.collection.extension` | `Specimen.collection.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Specimen.collection.fastingStatus[x]` | `Specimen.collection.fastingStatus[x]` | `fastingStatus[x]` | Specimen.collection.fastingStatus[x] | Whether or how long patient abstained from food and/or drink | 0..1 | CodeableConcept, Duration | `Extensible` | `http://terminology.hl7.org/ValueSet/v2-0916` |
| `Specimen.collection.id` | `Specimen.collection.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Specimen.collection.method` | `Specimen.collection.method` | `method` | Specimen.collection.method | Technique used to perform collection | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/specimen-collection-method` |
| `Specimen.collection.modifierExtension` | `Specimen.collection.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Specimen.collection.procedure` | `Specimen.collection.procedure` | `procedure` | Specimen.collection.procedure | The procedure that collects the specimen | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Procedure) |  |  |
| `Specimen.collection.quantity` | `Specimen.collection.quantity` | `quantity` | Specimen.collection.quantity | The quantity of specimen collected | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `Specimen.combined` | `Specimen.combined` | `combined` | Specimen.combined | grouped \| pooled | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/specimen-combined|5.0.0` |
| `Specimen.condition` | `Specimen.condition` | `condition` | Specimen.condition | State of the specimen | 0..* | CodeableConcept | `Extensible` | `http://terminology.hl7.org/ValueSet/v2-0493` |
| `Specimen.contained` | `Specimen.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Specimen.container` | `Specimen.container` | `container` | Specimen.container | Direct container of specimen (tube/slide, etc.) | 0..* | BackboneElement |  |  |
| `Specimen.container.device` | `Specimen.container.device` | `device` | Specimen.container.device | Device resource for the container | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device) |  |  |
| `Specimen.container.extension` | `Specimen.container.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Specimen.container.id` | `Specimen.container.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Specimen.container.location` | `Specimen.container.location` | `location` | Specimen.container.location | Where the container is | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `Specimen.container.modifierExtension` | `Specimen.container.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Specimen.container.specimenQuantity` | `Specimen.container.specimenQuantity` | `specimenQuantity` | Specimen.container.specimenQuantity | Quantity of specimen within container | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `Specimen.extension` | `Specimen.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Specimen.feature` | `Specimen.feature` | `feature` | Specimen.feature | The physical feature of a specimen | 0..* | BackboneElement |  |  |
| `Specimen.feature.description` | `Specimen.feature.description` | `description` | Specimen.feature.description | Information about the feature | 1..1 | string |  |  |
| `Specimen.feature.extension` | `Specimen.feature.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Specimen.feature.id` | `Specimen.feature.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Specimen.feature.modifierExtension` | `Specimen.feature.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Specimen.feature.type` | `Specimen.feature.type` | `type` | Specimen.feature.type | Highlighted feature | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `Specimen.id` | `Specimen.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Specimen.identifier` | `Specimen.identifier` | `identifier` | Specimen.identifier | External Identifier | 0..* | Identifier |  |  |
| `Specimen.implicitRules` | `Specimen.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Specimen.language` | `Specimen.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Specimen.meta` | `Specimen.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Specimen.modifierExtension` | `Specimen.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Specimen.note` | `Specimen.note` | `note` | Specimen.note | Comments | 0..* | Annotation |  |  |
| `Specimen.parent` | `Specimen.parent` | `parent` | Specimen.parent | Specimen from which this specimen originated | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Specimen) |  |  |
| `Specimen.processing` | `Specimen.processing` | `processing` | Specimen.processing | Processing and processing step details | 0..* | BackboneElement |  |  |
| `Specimen.processing.additive` | `Specimen.processing.additive` | `additive` | Specimen.processing.additive | Material used in the processing step | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `Specimen.processing.description` | `Specimen.processing.description` | `description` | Specimen.processing.description | Textual description of procedure | 0..1 | string |  |  |
| `Specimen.processing.extension` | `Specimen.processing.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Specimen.processing.id` | `Specimen.processing.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Specimen.processing.method` | `Specimen.processing.method` | `method` | Specimen.processing.method | Indicates the treatment step  applied to the specimen | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/specimen-processing-method` |
| `Specimen.processing.modifierExtension` | `Specimen.processing.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Specimen.processing.time[x]` | `Specimen.processing.time[x]` | `time[x]` | Specimen.processing.time[x] | Date and time of specimen processing | 0..1 | dateTime, Period |  |  |
| `Specimen.receivedTime` | `Specimen.receivedTime` | `receivedTime` | Specimen.receivedTime | The time when specimen is received by the testing laboratory | 0..1 | dateTime |  |  |
| `Specimen.request` | `Specimen.request` | `request` | Specimen.request | Why the specimen was collected | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ServiceRequest) |  |  |
| `Specimen.role` | `Specimen.role` | `role` | Specimen.role | The role the specimen serves | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/specimen-role` |
| `Specimen.status` | `Specimen.status` | `status` | Specimen.status | available \| unavailable \| unsatisfactory \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/specimen-status|5.0.0` |
| `Specimen.subject` | `Specimen.subject` | `subject` | Specimen.subject | Where the specimen came from. This may be from patient(s), from a location (e.g., the source of an environmental sample), or a sampling of a substance, a biologically-derived product, or a device | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `Specimen.text` | `Specimen.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Specimen.type` | `Specimen.type` | `type` | Specimen.type | Kind of material that forms the specimen | 0..1 | CodeableConcept | `Example` | `http://terminology.hl7.org/ValueSet/v2-0487` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Specimen](/docs/R2/Resources/Specimen.md)<br/> `http://hl7.org/fhir/StructureDefinition/Specimen\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `157`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `324`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Specimen](/docs/R3/Resources/Specimen.md)<br/> `http://hl7.org/fhir/StructureDefinition/Specimen\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `517`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `710`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Specimen](/docs/R4/Resources/Specimen.md)<br/> `http://hl7.org/fhir/StructureDefinition/Specimen\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1617`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1618`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Specimen](/docs/R4B/Resources/Specimen.md)<br/> `http://hl7.org/fhir/StructureDefinition/Specimen\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1042`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1271`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Specimen](/docs/R5/Resources/Specimen.md)<br/> `http://hl7.org/fhir/StructureDefinition/Specimen\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Specimen from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Specimen](/docs/R2/Resources/Specimen.md)| Relationship | [R3 Specimen](/docs/R3/Resources/Specimen.md)| Relationship | [R4 Specimen](/docs/R4/Resources/Specimen.md)| Relationship | [R4B Specimen](/docs/R4B/Resources/Specimen.md)| Relationship | R5 Specimen
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Specimen`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7814)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7815)| `Specimen`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18465)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18466)| `Specimen`| _Equivalent_<br/>(33179/33180)| `Specimen`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47411)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47412)| **`Specimen`**
| `Specimen.id`| _Equivalent_<br/>(7816/7817)| `Specimen.id`| _Equivalent_<br/>(18467/18468)| `Specimen.id`| _Equivalent_<br/>(33181/33182)| `Specimen.id`| _Equivalent_<br/>(47413/47414)| **`Specimen.id`**
| `Specimen.meta`| _Equivalent_<br/>(7818/7819)| `Specimen.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18469)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18470)| `Specimen.meta`| _Equivalent_<br/>(33183/33184)| `Specimen.meta`| _Equivalent_<br/>(47415/47416)| **`Specimen.meta`**
| `Specimen.implicitRules`| _Equivalent_<br/>(7820/7821)| `Specimen.implicitRules`| _Equivalent_<br/>(18471/18472)| `Specimen.implicitRules`| _Equivalent_<br/>(33185/33186)| `Specimen.implicitRules`| _Equivalent_<br/>(47417/47418)| **`Specimen.implicitRules`**
| `Specimen.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7822)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7823)| `Specimen.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18473)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18474)| `Specimen.language`| _Equivalent_<br/>(33187/33188)| `Specimen.language`| _Equivalent_<br/>(47419/47420)| **`Specimen.language`**
| `Specimen.text`| _Equivalent_<br/>(7824/7825)| `Specimen.text`| _Equivalent_<br/>(18475/18476)| `Specimen.text`| _Equivalent_<br/>(33189/33190)| `Specimen.text`| _Equivalent_<br/>(47421/47422)| **`Specimen.text`**
| `Specimen.contained`| _Equivalent_<br/>(7826/7827)| `Specimen.contained`| _Equivalent_<br/>(18477/18478)| `Specimen.contained`| _Equivalent_<br/>(33191/33192)| `Specimen.contained`| _Equivalent_<br/>(47423/47424)| **`Specimen.contained`**
| `Specimen.extension`| _Equivalent_<br/>(7828/7829)| `Specimen.extension`| _Equivalent_<br/>(18479/18480)| `Specimen.extension`| _Equivalent_<br/>(33193/33194)| `Specimen.extension`| _Equivalent_<br/>(47425/47426)| **`Specimen.extension`**
| `Specimen.modifierExtension`| _Equivalent_<br/>(7830/7831)| `Specimen.modifierExtension`| _Equivalent_<br/>(18481/18482)| `Specimen.modifierExtension`| _Equivalent_<br/>(33195/33196)| `Specimen.modifierExtension`| _Equivalent_<br/>(47427/47428)| **`Specimen.modifierExtension`**
| `Specimen.identifier`| _Equivalent_<br/>(7832/7833)| `Specimen.identifier`| _Equivalent_<br/>(18483/18484)| `Specimen.identifier`| _Equivalent_<br/>(33197/33198)| `Specimen.identifier`| _Equivalent_<br/>(47429/47430)| **`Specimen.identifier`**
| `Specimen.accessionIdentifier`| _Equivalent_<br/>(7842/7843)| `Specimen.accessionIdentifier`| _Equivalent_<br/>(18485/18486)| `Specimen.accessionIdentifier`| _Equivalent_<br/>(33199/33200)| `Specimen.accessionIdentifier`| _Equivalent_<br/>(47431/47432)| **`Specimen.accessionIdentifier`**
| `Specimen.status`| _Equivalent_<br/>(7834/7835)| `Specimen.status`| _Equivalent_<br/>(18487/18488)| `Specimen.status`| _Equivalent_<br/>(33201/33202)| `Specimen.status`| _Equivalent_<br/>(47433/47434)| **`Specimen.status`**
| `Specimen.type`| _Equivalent_<br/>(7836/7837)| `Specimen.type`| _Equivalent_<br/>(18489/18490)| `Specimen.type`| _Equivalent_<br/>(33203/33204)| `Specimen.type`| _Equivalent_<br/>(47435/47436)| **`Specimen.type`**
| `Specimen.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7840)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7841)| `Specimen.subject`| →→→→ _RelatedTo_ →→→→ <br/>(18491)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18492)| `Specimen.subject`| _Equivalent_<br/>(33205/33206)| `Specimen.subject`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47437)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47438)| **`Specimen.subject`**
| `Specimen.receivedTime`| _Equivalent_<br/>(7844/7845)| `Specimen.receivedTime`| _Equivalent_<br/>(18493/18494)| `Specimen.receivedTime`| _Equivalent_<br/>(33207/33208)| `Specimen.receivedTime`| _Equivalent_<br/>(47439/47440)| **`Specimen.receivedTime`**
| `Specimen.parent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7838)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7839)| `Specimen.parent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18495)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18496)| `Specimen.parent`| _Equivalent_<br/>(33209/33210)| `Specimen.parent`| _Equivalent_<br/>(47441/47442)| **`Specimen.parent`**
| | | `Specimen.request`| →→→→ _RelatedTo_ →→→→ <br/>(18497)<hr/>←←←← _RelatedTo_ ←←←← <br/>(18498)| `Specimen.request`| _Equivalent_<br/>(33211/33212)| `Specimen.request`| _Equivalent_<br/>(47443/47444)| **`Specimen.request`**
| | | | | | | | | **`Specimen.combined`**
| | | | | | | | | **`Specimen.role`**
| | | | | | | | | **`Specimen.feature`**
| | | | | | | | | **`Specimen.feature.id`**
| | | | | | | | | **`Specimen.feature.extension`**
| | | | | | | | | **`Specimen.feature.modifierExtension`**
| | | | | | | | | **`Specimen.feature.type`**
| | | | | | | | | **`Specimen.feature.description`**
| `Specimen.collection`| _Equivalent_<br/>(7846/7847)| `Specimen.collection`| _Equivalent_<br/>(18499/18500)| `Specimen.collection`| _Equivalent_<br/>(33213/33214)| `Specimen.collection`| _Equivalent_<br/>(47445/47446)| **`Specimen.collection`**
| `Specimen.collection.id`| _Equivalent_<br/>(7848/7849)| `Specimen.collection.id`| _Equivalent_<br/>(18501/18502)| `Specimen.collection.id`| _Equivalent_<br/>(33215/33216)| `Specimen.collection.id`| _Equivalent_<br/>(47447/47448)| **`Specimen.collection.id`**
| `Specimen.collection.extension`| _Equivalent_<br/>(7850/7851)| `Specimen.collection.extension`| _Equivalent_<br/>(18503/18504)| `Specimen.collection.extension`| _Equivalent_<br/>(33217/33218)| `Specimen.collection.extension`| _Equivalent_<br/>(47449/47450)| **`Specimen.collection.extension`**
| `Specimen.collection.modifierExtension`| _Equivalent_<br/>(7852/7853)| `Specimen.collection.modifierExtension`| _Equivalent_<br/>(18505/18506)| `Specimen.collection.modifierExtension`| _Equivalent_<br/>(33219/33220)| `Specimen.collection.modifierExtension`| _Equivalent_<br/>(47451/47452)| **`Specimen.collection.modifierExtension`**
| `Specimen.collection.collector`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7854)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7855)| `Specimen.collection.collector`| →→→→ _RelatedTo_ →→→→ <br/>(18507)<hr/>←←←← _RelatedTo_ ←←←← <br/>(18508)| `Specimen.collection.collector`| _Equivalent_<br/>(33221/33222)| `Specimen.collection.collector`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47453)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47454)| **`Specimen.collection.collector`**
| `Specimen.collection.collected[x]`| _Equivalent_<br/>(7856/7857)| `Specimen.collection.collected[x]`| _Equivalent_<br/>(18509/18510)| `Specimen.collection.collected[x]`| _Equivalent_<br/>(33223/33224)| `Specimen.collection.collected[x]`| _Equivalent_<br/>(47455/47456)| **`Specimen.collection.collected[x]`**
| | | | | `Specimen.collection.duration`| _Equivalent_<br/>(33225/33226)| `Specimen.collection.duration`| _Equivalent_<br/>(47457/47458)| **`Specimen.collection.duration`**
| `Specimen.collection.quantity`| _Equivalent_<br/>(7858/7859)| `Specimen.collection.quantity`| _Equivalent_<br/>(18511/18512)| `Specimen.collection.quantity`| _Equivalent_<br/>(33227/33228)| `Specimen.collection.quantity`| _Equivalent_<br/>(47459/47460)| **`Specimen.collection.quantity`**
| `Specimen.collection.method`| _Equivalent_<br/>(7860/7861)| `Specimen.collection.method`| _Equivalent_<br/>(18513/18514)| `Specimen.collection.method`| _Equivalent_<br/>(33229/33230)| `Specimen.collection.method`| _Equivalent_<br/>(47461/47462)| **`Specimen.collection.method`**
| | | | | | | | | **`Specimen.collection.device`**
| | | | | | | | | **`Specimen.collection.procedure`**
| `Specimen.collection.bodySite`| _Equivalent_<br/>(7862/7863)| `Specimen.collection.bodySite`| _Equivalent_<br/>(18515/18516)| `Specimen.collection.bodySite`| _Equivalent_<br/>(33231/33232)| `Specimen.collection.bodySite`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47463)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47464)| **`Specimen.collection.bodySite`**
| | | | | `Specimen.collection.fastingStatus[x]`| _Equivalent_<br/>(33233/33234)| `Specimen.collection.fastingStatus[x]`| _Equivalent_<br/>(47465/47466)| **`Specimen.collection.fastingStatus[x]`**
| `Specimen.treatment`| _Equivalent_<br/>(409/752)| `Specimen.processing`| _Equivalent_<br/>(18517/18518)| `Specimen.processing`| _Equivalent_<br/>(33235/33236)| `Specimen.processing`| _Equivalent_<br/>(47467/47468)| **`Specimen.processing`**
| | | `Specimen.processing.id`| _Equivalent_<br/>(18519/18520)| `Specimen.processing.id`| _Equivalent_<br/>(33237/33238)| `Specimen.processing.id`| _Equivalent_<br/>(47469/47470)| **`Specimen.processing.id`**
| | | `Specimen.processing.extension`| _Equivalent_<br/>(18521/18522)| `Specimen.processing.extension`| _Equivalent_<br/>(33239/33240)| `Specimen.processing.extension`| _Equivalent_<br/>(47471/47472)| **`Specimen.processing.extension`**
| | | `Specimen.processing.modifierExtension`| _Equivalent_<br/>(18523/18524)| `Specimen.processing.modifierExtension`| _Equivalent_<br/>(33241/33242)| `Specimen.processing.modifierExtension`| _Equivalent_<br/>(47473/47474)| **`Specimen.processing.modifierExtension`**
| `Specimen.treatment.description`| _Equivalent_<br/>(411/754)| `Specimen.processing.description`| _Equivalent_<br/>(18525/18526)| `Specimen.processing.description`| _Equivalent_<br/>(33243/33244)| `Specimen.processing.description`| _Equivalent_<br/>(47475/47476)| **`Specimen.processing.description`**
| `Specimen.treatment.procedure`| _Equivalent_<br/>(412/755)| `Specimen.processing.procedure`| _Equivalent_<br/>(18527/18528)| `Specimen.processing.procedure`| _Equivalent_<br/>(33245/33246)| `Specimen.processing.procedure`| _Equivalent_<br/>(1953/2189)| **`Specimen.processing.method`**
| `Specimen.treatment.additive`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(410)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(753)| `Specimen.processing.additive`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18529)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18530)| `Specimen.processing.additive`| _Equivalent_<br/>(33247/33248)| `Specimen.processing.additive`| _Equivalent_<br/>(47477/47478)| **`Specimen.processing.additive`**
| | | `Specimen.processing.time[x]`| _Equivalent_<br/>(18531/18532)| `Specimen.processing.time[x]`| _Equivalent_<br/>(33249/33250)| `Specimen.processing.time[x]`| _Equivalent_<br/>(47479/47480)| **`Specimen.processing.time[x]`**
| `Specimen.container`| _Equivalent_<br/>(7867/7868)| `Specimen.container`| _Equivalent_<br/>(18533/18534)| `Specimen.container`| _Equivalent_<br/>(33251/33252)| `Specimen.container`| _Equivalent_<br/>(47481/47482)| **`Specimen.container`**
| `Specimen.container.id`| _Equivalent_<br/>(7869/7870)| `Specimen.container.id`| _Equivalent_<br/>(18535/18536)| `Specimen.container.id`| _Equivalent_<br/>(33253/33254)| `Specimen.container.id`| _Equivalent_<br/>(47483/47484)| **`Specimen.container.id`**
| `Specimen.container.extension`| _Equivalent_<br/>(7871/7872)| `Specimen.container.extension`| _Equivalent_<br/>(18537/18538)| `Specimen.container.extension`| _Equivalent_<br/>(33255/33256)| `Specimen.container.extension`| _Equivalent_<br/>(47485/47486)| **`Specimen.container.extension`**
| `Specimen.container.modifierExtension`| _Equivalent_<br/>(7873/7874)| `Specimen.container.modifierExtension`| _Equivalent_<br/>(18539/18540)| `Specimen.container.modifierExtension`| _Equivalent_<br/>(33257/33258)| `Specimen.container.modifierExtension`| _Equivalent_<br/>(47487/47488)| **`Specimen.container.modifierExtension`**
| | | | | | | | | **`Specimen.container.device`**
| | | | | | | | | **`Specimen.container.location`**
| `Specimen.container.specimenQuantity`| _Equivalent_<br/>(7883/7884)| `Specimen.container.specimenQuantity`| _Equivalent_<br/>(18549/18550)| `Specimen.container.specimenQuantity`| _Equivalent_<br/>(33267/33268)| `Specimen.container.specimenQuantity`| _Equivalent_<br/>(47493/47494)| **`Specimen.container.specimenQuantity`**
| | | | | `Specimen.condition`| _Equivalent_<br/>(33271/33272)| `Specimen.condition`| _Equivalent_<br/>(47496/47497)| **`Specimen.condition`**
| | | `Specimen.note`| _Equivalent_<br/>(18553/18554)| `Specimen.note`| _Equivalent_<br/>(33273/33274)| `Specimen.note`| _Equivalent_<br/>(47498/47499)| **`Specimen.note`**
| *34 of 43 elements used* <br/>remaining elements:<br/>`Specimen.collection.comment`, `Specimen.container.additive[x]`, `Specimen.container.capacity`, `Specimen.container.description`, `Specimen.container.identifier`, `Specimen.container.type`, `Specimen.treatment.extension`, `Specimen.treatment.id`, `Specimen.treatment.modifierExtension`| | *40 of 45 elements used* <br/>remaining elements:<br/>`Specimen.container.additive[x]`, `Specimen.container.capacity`, `Specimen.container.description`, `Specimen.container.identifier`, `Specimen.container.type`| | *43 of 48 elements used* <br/>remaining elements:<br/>`Specimen.container.additive[x]`, `Specimen.container.capacity`, `Specimen.container.description`, `Specimen.container.identifier`, `Specimen.container.type`| | *43 of 48 elements used* <br/>remaining elements:<br/>`Specimen.container.additive[x]`, `Specimen.container.capacity`, `Specimen.container.description`, `Specimen.container.identifier`, `Specimen.container.type`| | *55 of 55 elements used* 

