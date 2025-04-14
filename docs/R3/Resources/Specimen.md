Comparison of 
Generated at Monday, April 14, 2025 6:17:24 PM

### Specimen

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Specimen |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Specimen` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Specimen Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `582` |
| Database Snapshot Count | `45` |
| Database Differential Count | `28` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Specimen` | `Specimen` | `Specimen` | Specimen | Sample for analysis | 0..* | Specimen |  |  |
| `Specimen.accessionIdentifier` | `Specimen.accessionIdentifier` | `accessionIdentifier` |  | Identifier assigned by the lab | 0..1 | Identifier |  |  |
| `Specimen.collection` | `Specimen.collection` | `collection` |  | Collection details | 0..1 | BackboneElement |  |  |
| `Specimen.collection.bodySite` | `Specimen.collection.bodySite` | `bodySite` |  | Anatomical collection site | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `Specimen.collection.collected[x]` | `Specimen.collection.collected[x]` | `collected[x]` |  | Collection time | 0..1 | dateTime, Period |  |  |
| `Specimen.collection.collector` | `Specimen.collection.collector` | `collector` |  | Who collected the specimen | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `Specimen.collection.extension` | `Specimen.collection.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Specimen.collection.id` | `Specimen.collection.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Specimen.collection.method` | `Specimen.collection.method` | `method` |  | Technique used to perform collection | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/specimen-collection-method` |
| `Specimen.collection.modifierExtension` | `Specimen.collection.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Specimen.collection.quantity` | `Specimen.collection.quantity` | `quantity` |  | The quantity of specimen collected | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `Specimen.contained` | `Specimen.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Specimen.container` | `Specimen.container` | `container` |  | Direct container of specimen (tube/slide, etc.) | 0..* | BackboneElement |  |  |
| `Specimen.container.additive[x]` | `Specimen.container.additive[x]` | `additive[x]` |  | Additive associated with container | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Substance) | `Example` | `http://hl7.org/fhir/ValueSet/v2-0371` |
| `Specimen.container.capacity` | `Specimen.container.capacity` | `capacity` |  | Container volume or size | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `Specimen.container.description` | `Specimen.container.description` | `description` |  | Textual description of the container | 0..1 | string |  |  |
| `Specimen.container.extension` | `Specimen.container.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Specimen.container.id` | `Specimen.container.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Specimen.container.identifier` | `Specimen.container.identifier` | `identifier` |  | Id for the container | 0..* | Identifier |  |  |
| `Specimen.container.modifierExtension` | `Specimen.container.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Specimen.container.specimenQuantity` | `Specimen.container.specimenQuantity` | `specimenQuantity` |  | Quantity of specimen within container | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `Specimen.container.type` | `Specimen.container.type` | `type` |  | Kind of container directly associated with specimen | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/specimen-container-type` |
| `Specimen.extension` | `Specimen.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Specimen.id` | `Specimen.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Specimen.identifier` | `Specimen.identifier` | `identifier` |  | External Identifier | 0..* | Identifier |  |  |
| `Specimen.implicitRules` | `Specimen.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Specimen.language` | `Specimen.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `Specimen.meta` | `Specimen.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Specimen.modifierExtension` | `Specimen.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Specimen.note` | `Specimen.note` | `note` |  | Comments | 0..* | Annotation |  |  |
| `Specimen.parent` | `Specimen.parent` | `parent` |  | Specimen from which this specimen originated | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Specimen) |  |  |
| `Specimen.processing` | `Specimen.processing` | `processing` |  | Processing and processing step details | 0..* | BackboneElement |  |  |
| `Specimen.processing.additive` | `Specimen.processing.additive` | `additive` |  | Material used in the processing step | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `Specimen.processing.description` | `Specimen.processing.description` | `description` |  | Textual description of procedure | 0..1 | string |  |  |
| `Specimen.processing.extension` | `Specimen.processing.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Specimen.processing.id` | `Specimen.processing.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Specimen.processing.modifierExtension` | `Specimen.processing.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Specimen.processing.procedure` | `Specimen.processing.procedure` | `procedure` |  | Indicates the treatment step  applied to the specimen | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/specimen-processing-procedure` |
| `Specimen.processing.time[x]` | `Specimen.processing.time[x]` | `time[x]` |  | Date and time of specimen processing | 0..1 | dateTime, Period |  |  |
| `Specimen.receivedTime` | `Specimen.receivedTime` | `receivedTime` |  | The time when specimen was received for processing | 0..1 | dateTime |  |  |
| `Specimen.request` | `Specimen.request` | `request` |  | Why the specimen was collected | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ProcedureRequest) |  |  |
| `Specimen.status` | `Specimen.status` | `status` |  | available \| unavailable \| unsatisfactory \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/specimen-status` |
| `Specimen.subject` | `Specimen.subject` | `subject` |  | Where the specimen came from. This may be from the patient(s) or from the environment or a device | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `Specimen.text` | `Specimen.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Specimen.type` | `Specimen.type` | `type` |  | Kind of material that forms the specimen | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/v2-0487` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Specimen](/docs/R2/Resources/Specimen.md)<br/> `http://hl7.org/fhir/StructureDefinition/Specimen\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `157`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `324`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Specimen](/docs/R3/Resources/Specimen.md)<br/> `http://hl7.org/fhir/StructureDefinition/Specimen\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `517`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `710`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Specimen](/docs/R4/Resources/Specimen.md)<br/> `http://hl7.org/fhir/StructureDefinition/Specimen\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1617`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1618`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Specimen](/docs/R4B/Resources/Specimen.md)<br/> `http://hl7.org/fhir/StructureDefinition/Specimen\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1042`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1271`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Specimen](/docs/R5/Resources/Specimen.md)<br/> `http://hl7.org/fhir/StructureDefinition/Specimen\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Specimen from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Specimen](/docs/R2/Resources/Specimen.md)| Relationship | R3 Specimen| Relationship | [R4 Specimen](/docs/R4/Resources/Specimen.md)| Relationship | [R4B Specimen](/docs/R4B/Resources/Specimen.md)| Relationship | [R5 Specimen](/docs/R5/Resources/Specimen.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Specimen`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7814)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7815)| **`Specimen`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18465)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18466)| `Specimen`| _Equivalent_<br/>(33179/33180)| `Specimen`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47411)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47412)| `Specimen`
| `Specimen.id`| _Equivalent_<br/>(7816/7817)| **`Specimen.id`**| _Equivalent_<br/>(18467/18468)| `Specimen.id`| _Equivalent_<br/>(33181/33182)| `Specimen.id`| _Equivalent_<br/>(47413/47414)| `Specimen.id`
| `Specimen.meta`| _Equivalent_<br/>(7818/7819)| **`Specimen.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18469)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18470)| `Specimen.meta`| _Equivalent_<br/>(33183/33184)| `Specimen.meta`| _Equivalent_<br/>(47415/47416)| `Specimen.meta`
| `Specimen.implicitRules`| _Equivalent_<br/>(7820/7821)| **`Specimen.implicitRules`**| _Equivalent_<br/>(18471/18472)| `Specimen.implicitRules`| _Equivalent_<br/>(33185/33186)| `Specimen.implicitRules`| _Equivalent_<br/>(47417/47418)| `Specimen.implicitRules`
| `Specimen.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7822)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7823)| **`Specimen.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18473)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18474)| `Specimen.language`| _Equivalent_<br/>(33187/33188)| `Specimen.language`| _Equivalent_<br/>(47419/47420)| `Specimen.language`
| `Specimen.text`| _Equivalent_<br/>(7824/7825)| **`Specimen.text`**| _Equivalent_<br/>(18475/18476)| `Specimen.text`| _Equivalent_<br/>(33189/33190)| `Specimen.text`| _Equivalent_<br/>(47421/47422)| `Specimen.text`
| `Specimen.contained`| _Equivalent_<br/>(7826/7827)| **`Specimen.contained`**| _Equivalent_<br/>(18477/18478)| `Specimen.contained`| _Equivalent_<br/>(33191/33192)| `Specimen.contained`| _Equivalent_<br/>(47423/47424)| `Specimen.contained`
| `Specimen.extension`| _Equivalent_<br/>(7828/7829)| **`Specimen.extension`**| _Equivalent_<br/>(18479/18480)| `Specimen.extension`| _Equivalent_<br/>(33193/33194)| `Specimen.extension`| _Equivalent_<br/>(47425/47426)| `Specimen.extension`
| `Specimen.modifierExtension`| _Equivalent_<br/>(7830/7831)| **`Specimen.modifierExtension`**| _Equivalent_<br/>(18481/18482)| `Specimen.modifierExtension`| _Equivalent_<br/>(33195/33196)| `Specimen.modifierExtension`| _Equivalent_<br/>(47427/47428)| `Specimen.modifierExtension`
| `Specimen.identifier`| _Equivalent_<br/>(7832/7833)| **`Specimen.identifier`**| _Equivalent_<br/>(18483/18484)| `Specimen.identifier`| _Equivalent_<br/>(33197/33198)| `Specimen.identifier`| _Equivalent_<br/>(47429/47430)| `Specimen.identifier`
| `Specimen.accessionIdentifier`| _Equivalent_<br/>(7842/7843)| **`Specimen.accessionIdentifier`**| _Equivalent_<br/>(18485/18486)| `Specimen.accessionIdentifier`| _Equivalent_<br/>(33199/33200)| `Specimen.accessionIdentifier`| _Equivalent_<br/>(47431/47432)| `Specimen.accessionIdentifier`
| `Specimen.status`| _Equivalent_<br/>(7834/7835)| **`Specimen.status`**| _Equivalent_<br/>(18487/18488)| `Specimen.status`| _Equivalent_<br/>(33201/33202)| `Specimen.status`| _Equivalent_<br/>(47433/47434)| `Specimen.status`
| `Specimen.type`| _Equivalent_<br/>(7836/7837)| **`Specimen.type`**| _Equivalent_<br/>(18489/18490)| `Specimen.type`| _Equivalent_<br/>(33203/33204)| `Specimen.type`| _Equivalent_<br/>(47435/47436)| `Specimen.type`
| `Specimen.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7840)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7841)| **`Specimen.subject`**| →→→→ _RelatedTo_ →→→→ <br/>(18491)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18492)| `Specimen.subject`| _Equivalent_<br/>(33205/33206)| `Specimen.subject`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47437)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47438)| `Specimen.subject`
| `Specimen.receivedTime`| _Equivalent_<br/>(7844/7845)| **`Specimen.receivedTime`**| _Equivalent_<br/>(18493/18494)| `Specimen.receivedTime`| _Equivalent_<br/>(33207/33208)| `Specimen.receivedTime`| _Equivalent_<br/>(47439/47440)| `Specimen.receivedTime`
| `Specimen.parent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7838)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7839)| **`Specimen.parent`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18495)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18496)| `Specimen.parent`| _Equivalent_<br/>(33209/33210)| `Specimen.parent`| _Equivalent_<br/>(47441/47442)| `Specimen.parent`
| | | **`Specimen.request`**| →→→→ _RelatedTo_ →→→→ <br/>(18497)<hr/>←←←← _RelatedTo_ ←←←← <br/>(18498)| `Specimen.request`| _Equivalent_<br/>(33211/33212)| `Specimen.request`| _Equivalent_<br/>(47443/47444)| `Specimen.request`
| `Specimen.collection`| _Equivalent_<br/>(7846/7847)| **`Specimen.collection`**| _Equivalent_<br/>(18499/18500)| `Specimen.collection`| _Equivalent_<br/>(33213/33214)| `Specimen.collection`| _Equivalent_<br/>(47445/47446)| `Specimen.collection`
| `Specimen.collection.id`| _Equivalent_<br/>(7848/7849)| **`Specimen.collection.id`**| _Equivalent_<br/>(18501/18502)| `Specimen.collection.id`| _Equivalent_<br/>(33215/33216)| `Specimen.collection.id`| _Equivalent_<br/>(47447/47448)| `Specimen.collection.id`
| `Specimen.collection.extension`| _Equivalent_<br/>(7850/7851)| **`Specimen.collection.extension`**| _Equivalent_<br/>(18503/18504)| `Specimen.collection.extension`| _Equivalent_<br/>(33217/33218)| `Specimen.collection.extension`| _Equivalent_<br/>(47449/47450)| `Specimen.collection.extension`
| `Specimen.collection.modifierExtension`| _Equivalent_<br/>(7852/7853)| **`Specimen.collection.modifierExtension`**| _Equivalent_<br/>(18505/18506)| `Specimen.collection.modifierExtension`| _Equivalent_<br/>(33219/33220)| `Specimen.collection.modifierExtension`| _Equivalent_<br/>(47451/47452)| `Specimen.collection.modifierExtension`
| `Specimen.collection.collector`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7854)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7855)| **`Specimen.collection.collector`**| →→→→ _RelatedTo_ →→→→ <br/>(18507)<hr/>←←←← _RelatedTo_ ←←←← <br/>(18508)| `Specimen.collection.collector`| _Equivalent_<br/>(33221/33222)| `Specimen.collection.collector`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47453)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47454)| `Specimen.collection.collector`
| `Specimen.collection.collected[x]`| _Equivalent_<br/>(7856/7857)| **`Specimen.collection.collected[x]`**| _Equivalent_<br/>(18509/18510)| `Specimen.collection.collected[x]`| _Equivalent_<br/>(33223/33224)| `Specimen.collection.collected[x]`| _Equivalent_<br/>(47455/47456)| `Specimen.collection.collected[x]`
| `Specimen.collection.quantity`| _Equivalent_<br/>(7858/7859)| **`Specimen.collection.quantity`**| _Equivalent_<br/>(18511/18512)| `Specimen.collection.quantity`| _Equivalent_<br/>(33227/33228)| `Specimen.collection.quantity`| _Equivalent_<br/>(47459/47460)| `Specimen.collection.quantity`
| `Specimen.collection.method`| _Equivalent_<br/>(7860/7861)| **`Specimen.collection.method`**| _Equivalent_<br/>(18513/18514)| `Specimen.collection.method`| _Equivalent_<br/>(33229/33230)| `Specimen.collection.method`| _Equivalent_<br/>(47461/47462)| `Specimen.collection.method`
| `Specimen.collection.bodySite`| _Equivalent_<br/>(7862/7863)| **`Specimen.collection.bodySite`**| _Equivalent_<br/>(18515/18516)| `Specimen.collection.bodySite`| _Equivalent_<br/>(33231/33232)| `Specimen.collection.bodySite`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47463)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47464)| `Specimen.collection.bodySite`
| `Specimen.treatment`| _Equivalent_<br/>(409/752)| **`Specimen.processing`**| _Equivalent_<br/>(18517/18518)| `Specimen.processing`| _Equivalent_<br/>(33235/33236)| `Specimen.processing`| _Equivalent_<br/>(47467/47468)| `Specimen.processing`
| | | **`Specimen.processing.id`**| _Equivalent_<br/>(18519/18520)| `Specimen.processing.id`| _Equivalent_<br/>(33237/33238)| `Specimen.processing.id`| _Equivalent_<br/>(47469/47470)| `Specimen.processing.id`
| | | **`Specimen.processing.extension`**| _Equivalent_<br/>(18521/18522)| `Specimen.processing.extension`| _Equivalent_<br/>(33239/33240)| `Specimen.processing.extension`| _Equivalent_<br/>(47471/47472)| `Specimen.processing.extension`
| | | **`Specimen.processing.modifierExtension`**| _Equivalent_<br/>(18523/18524)| `Specimen.processing.modifierExtension`| _Equivalent_<br/>(33241/33242)| `Specimen.processing.modifierExtension`| _Equivalent_<br/>(47473/47474)| `Specimen.processing.modifierExtension`
| `Specimen.treatment.description`| _Equivalent_<br/>(411/754)| **`Specimen.processing.description`**| _Equivalent_<br/>(18525/18526)| `Specimen.processing.description`| _Equivalent_<br/>(33243/33244)| `Specimen.processing.description`| _Equivalent_<br/>(47475/47476)| `Specimen.processing.description`
| `Specimen.treatment.procedure`| _Equivalent_<br/>(412/755)| **`Specimen.processing.procedure`**| _Equivalent_<br/>(18527/18528)| `Specimen.processing.procedure`| _Equivalent_<br/>(33245/33246)| `Specimen.processing.procedure`| _Equivalent_<br/>(1953/2189)| `Specimen.processing.method`
| `Specimen.treatment.additive`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(410)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(753)| **`Specimen.processing.additive`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18529)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18530)| `Specimen.processing.additive`| _Equivalent_<br/>(33247/33248)| `Specimen.processing.additive`| _Equivalent_<br/>(47477/47478)| `Specimen.processing.additive`
| | | **`Specimen.processing.time[x]`**| _Equivalent_<br/>(18531/18532)| `Specimen.processing.time[x]`| _Equivalent_<br/>(33249/33250)| `Specimen.processing.time[x]`| _Equivalent_<br/>(47479/47480)| `Specimen.processing.time[x]`
| `Specimen.container`| _Equivalent_<br/>(7867/7868)| **`Specimen.container`**| _Equivalent_<br/>(18533/18534)| `Specimen.container`| _Equivalent_<br/>(33251/33252)| `Specimen.container`| _Equivalent_<br/>(47481/47482)| `Specimen.container`
| `Specimen.container.id`| _Equivalent_<br/>(7869/7870)| **`Specimen.container.id`**| _Equivalent_<br/>(18535/18536)| `Specimen.container.id`| _Equivalent_<br/>(33253/33254)| `Specimen.container.id`| _Equivalent_<br/>(47483/47484)| `Specimen.container.id`
| `Specimen.container.extension`| _Equivalent_<br/>(7871/7872)| **`Specimen.container.extension`**| _Equivalent_<br/>(18537/18538)| `Specimen.container.extension`| _Equivalent_<br/>(33255/33256)| `Specimen.container.extension`| _Equivalent_<br/>(47485/47486)| `Specimen.container.extension`
| `Specimen.container.modifierExtension`| _Equivalent_<br/>(7873/7874)| **`Specimen.container.modifierExtension`**| _Equivalent_<br/>(18539/18540)| `Specimen.container.modifierExtension`| _Equivalent_<br/>(33257/33258)| `Specimen.container.modifierExtension`| _Equivalent_<br/>(47487/47488)| `Specimen.container.modifierExtension`
| `Specimen.container.identifier`| _Equivalent_<br/>(7875/7876)| **`Specimen.container.identifier`**| _Equivalent_<br/>(18541/18542)| `Specimen.container.identifier`| _Equivalent_<br/>(33259/33260)| `Specimen.container.identifier`| | | 
| `Specimen.container.description`| _Equivalent_<br/>(7877/7878)| **`Specimen.container.description`**| _Equivalent_<br/>(18543/18544)| `Specimen.container.description`| _Equivalent_<br/>(33261/33262)| `Specimen.container.description`| | | 
| `Specimen.container.type`| _Equivalent_<br/>(7879/7880)| **`Specimen.container.type`**| _Equivalent_<br/>(18545/18546)| `Specimen.container.type`| _Equivalent_<br/>(33263/33264)| `Specimen.container.type`| | | 
| `Specimen.container.capacity`| _Equivalent_<br/>(7881/7882)| **`Specimen.container.capacity`**| _Equivalent_<br/>(18547/18548)| `Specimen.container.capacity`| _Equivalent_<br/>(33265/33266)| `Specimen.container.capacity`| | | 
| `Specimen.container.specimenQuantity`| _Equivalent_<br/>(7883/7884)| **`Specimen.container.specimenQuantity`**| _Equivalent_<br/>(18549/18550)| `Specimen.container.specimenQuantity`| _Equivalent_<br/>(33267/33268)| `Specimen.container.specimenQuantity`| _Equivalent_<br/>(47493/47494)| `Specimen.container.specimenQuantity`
| `Specimen.container.additive[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7885)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7886)| **`Specimen.container.additive[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18551)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18552)| `Specimen.container.additive[x]`| _Equivalent_<br/>(33269/33270)| `Specimen.container.additive[x]`| | | 
| | | **`Specimen.note`**| _Equivalent_<br/>(18553/18554)| `Specimen.note`| _Equivalent_<br/>(33273/33274)| `Specimen.note`| _Equivalent_<br/>(47498/47499)| `Specimen.note`
| *39 of 43 elements used* <br/>remaining elements:<br/>`Specimen.collection.comment`, `Specimen.treatment.extension`, `Specimen.treatment.id`, `Specimen.treatment.modifierExtension`| | *45 of 45 elements used* | | *45 of 48 elements used* <br/>remaining elements:<br/>`Specimen.collection.duration`, `Specimen.collection.fastingStatus[x]`, `Specimen.condition`| | *45 of 48 elements used* <br/>remaining elements:<br/>`Specimen.collection.duration`, `Specimen.collection.fastingStatus[x]`, `Specimen.condition`| | *40 of 55 elements used* <br/>remaining elements:<br/>`Specimen.collection.device`, `Specimen.collection.duration`, `Specimen.collection.fastingStatus[x]`, `Specimen.collection.procedure`, `Specimen.combined`, `Specimen.condition`, `Specimen.container.device`, `Specimen.container.location`, `Specimen.feature`, `Specimen.feature.description`, `Specimen.feature.extension`, `Specimen.feature.id`, `Specimen.feature.modifierExtension`, `Specimen.feature.type`, `Specimen.role`

