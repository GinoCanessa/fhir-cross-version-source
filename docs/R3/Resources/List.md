Comparison of 
Generated at Friday, April 4, 2025 2:58:40 PM

### List

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | List |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/List` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for List Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `537` |
| Database Snapshot Count | `29` |
| Database Differential Count | `18` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `List` | `List` | `List` | List | Information summarized from a list of other resources | 0..* | List |  |  |
| `List.code` | `List.code` | `code` |  | What the purpose of this list is | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/list-example-codes` |
| `List.contained` | `List.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `List.date` | `List.date` | `date` |  | When the list was prepared | 0..1 | dateTime |  |  |
| `List.emptyReason` | `List.emptyReason` | `emptyReason` |  | Why list is empty | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/list-empty-reason` |
| `List.encounter` | `List.encounter` | `encounter` |  | Context in which list created | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `List.entry` | `List.entry` | `entry` |  | Entries in the list | 0..* | BackboneElement |  |  |
| `List.entry.date` | `List.entry.date` | `date` |  | When item added to list | 0..1 | dateTime |  |  |
| `List.entry.deleted` | `List.entry.deleted` | `deleted` |  | If this item is actually marked as deleted | 0..1 | boolean |  |  |
| `List.entry.extension` | `List.entry.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `List.entry.flag` | `List.entry.flag` | `flag` |  | Status/Workflow information about this item | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/list-item-flag` |
| `List.entry.id` | `List.entry.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `List.entry.item` | `List.entry.item` | `item` |  | Actual entry | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `List.entry.modifierExtension` | `List.entry.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `List.extension` | `List.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `List.id` | `List.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `List.identifier` | `List.identifier` | `identifier` |  | Business identifier | 0..* | Identifier |  |  |
| `List.implicitRules` | `List.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `List.language` | `List.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `List.meta` | `List.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `List.mode` | `List.mode` | `mode` |  | working \| snapshot \| changes | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/list-mode` |
| `List.modifierExtension` | `List.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `List.note` | `List.note` | `note` |  | Comments about the list | 0..* | Annotation |  |  |
| `List.orderedBy` | `List.orderedBy` | `orderedBy` |  | What order the list has | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/list-order` |
| `List.source` | `List.source` | `source` |  | Who and/or what defined the list contents (aka Author) | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `List.status` | `List.status` | `status` |  | current \| retired \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/list-status` |
| `List.subject` | `List.subject` | `subject` |  | If all resources have the same subject | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `List.text` | `List.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `List.title` | `List.title` | `title` |  | Descriptive name for the list | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [List](/docs/R2/Resources/List.md)<br/> `http://hl7.org/fhir/StructureDefinition/List\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `121`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `287`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [List](/docs/R3/Resources/List.md)<br/> `http://hl7.org/fhir/StructureDefinition/List\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `474`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `668`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [List](/docs/R4/Resources/List.md)<br/> `http://hl7.org/fhir/StructureDefinition/List\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1525`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1526`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [List](/docs/R4B/Resources/List.md)<br/> `http://hl7.org/fhir/StructureDefinition/List\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `997`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1226`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [List](/docs/R5/Resources/List.md)<br/> `http://hl7.org/fhir/StructureDefinition/List\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition List from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 List](/docs/R2/Resources/List.md)| Relationship | R3 List| Relationship | [R4 List](/docs/R4/Resources/List.md)| Relationship | [R4B List](/docs/R4B/Resources/List.md)| Relationship | [R5 List](/docs/R5/Resources/List.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `List`| _Equivalent_<br/>(5937/5938)| **`List`**| _Equivalent_<br/>(15279/15280)| `List`| _Equivalent_<br/>(28917/28918)| `List`| _Equivalent_<br/>(43788/43789)| `List`
| `List.id`| _Equivalent_<br/>(5939/5940)| **`List.id`**| _Equivalent_<br/>(15281/15282)| `List.id`| _Equivalent_<br/>(28919/28920)| `List.id`| _Equivalent_<br/>(43790/43791)| `List.id`
| `List.meta`| _Equivalent_<br/>(5941/5942)| **`List.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15283)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15284)| `List.meta`| _Equivalent_<br/>(28921/28922)| `List.meta`| _Equivalent_<br/>(43792/43793)| `List.meta`
| `List.implicitRules`| _Equivalent_<br/>(5943/5944)| **`List.implicitRules`**| _Equivalent_<br/>(15285/15286)| `List.implicitRules`| _Equivalent_<br/>(28923/28924)| `List.implicitRules`| _Equivalent_<br/>(43794/43795)| `List.implicitRules`
| `List.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5945)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(5946)| **`List.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15287)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(15288)| `List.language`| _Equivalent_<br/>(28925/28926)| `List.language`| _Equivalent_<br/>(43796/43797)| `List.language`
| `List.text`| _Equivalent_<br/>(5947/5948)| **`List.text`**| _Equivalent_<br/>(15289/15290)| `List.text`| _Equivalent_<br/>(28927/28928)| `List.text`| _Equivalent_<br/>(43798/43799)| `List.text`
| `List.contained`| _Equivalent_<br/>(5949/5950)| **`List.contained`**| _Equivalent_<br/>(15291/15292)| `List.contained`| _Equivalent_<br/>(28929/28930)| `List.contained`| _Equivalent_<br/>(43800/43801)| `List.contained`
| `List.extension`| _Equivalent_<br/>(5951/5952)| **`List.extension`**| _Equivalent_<br/>(15293/15294)| `List.extension`| _Equivalent_<br/>(28931/28932)| `List.extension`| _Equivalent_<br/>(43802/43803)| `List.extension`
| `List.modifierExtension`| _Equivalent_<br/>(5953/5954)| **`List.modifierExtension`**| _Equivalent_<br/>(15295/15296)| `List.modifierExtension`| _Equivalent_<br/>(28933/28934)| `List.modifierExtension`| _Equivalent_<br/>(43804/43805)| `List.modifierExtension`
| `List.identifier`| _Equivalent_<br/>(5955/5956)| **`List.identifier`**| _Equivalent_<br/>(15297/15298)| `List.identifier`| _Equivalent_<br/>(28935/28936)| `List.identifier`| _Equivalent_<br/>(43806/43807)| `List.identifier`
| `List.status`| _Equivalent_<br/>(5967/5968)| **`List.status`**| _Equivalent_<br/>(15299/15300)| `List.status`| _Equivalent_<br/>(28937/28938)| `List.status`| _Equivalent_<br/>(43808/43809)| `List.status`
| `List.mode`| _Equivalent_<br/>(5973/5974)| **`List.mode`**| _Equivalent_<br/>(15301/15302)| `List.mode`| _Equivalent_<br/>(28939/28940)| `List.mode`| _Equivalent_<br/>(43810/43811)| `List.mode`
| `List.title`| _Equivalent_<br/>(5957/5958)| **`List.title`**| _Equivalent_<br/>(15303/15304)| `List.title`| _Equivalent_<br/>(28941/28942)| `List.title`| _Equivalent_<br/>(43812/43813)| `List.title`
| `List.code`| _Equivalent_<br/>(5959/5960)| **`List.code`**| _Equivalent_<br/>(15305/15306)| `List.code`| _Equivalent_<br/>(28943/28944)| `List.code`| _Equivalent_<br/>(43814/43815)| `List.code`
| `List.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5961)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5962)| **`List.subject`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15307)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15308)| `List.subject`| _Equivalent_<br/>(28945/28946)| `List.subject`| →→→→ _RelatedTo_ →→→→ <br/>(43816)<hr/>←←←← _RelatedTo_ ←←←← <br/>(43817)| `List.subject`
| `List.encounter`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5965)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5966)| **`List.encounter`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15309)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15310)| `List.encounter`| _Equivalent_<br/>(28947/28948)| `List.encounter`| _Equivalent_<br/>(43818/43819)| `List.encounter`
| `List.date`| _Equivalent_<br/>(5969/5970)| **`List.date`**| _Equivalent_<br/>(15311/15312)| `List.date`| _Equivalent_<br/>(28949/28950)| `List.date`| _Equivalent_<br/>(43820/43821)| `List.date`
| `List.source`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5963)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5964)| **`List.source`**| →→→→ _RelatedTo_ →→→→ <br/>(15313)<hr/>←←←← _RelatedTo_ ←←←← <br/>(15314)| `List.source`| _Equivalent_<br/>(28951/28952)| `List.source`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(43822)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(43823)| `List.source`
| `List.orderedBy`| _Equivalent_<br/>(5971/5972)| **`List.orderedBy`**| _Equivalent_<br/>(15315/15316)| `List.orderedBy`| _Equivalent_<br/>(28953/28954)| `List.orderedBy`| _Equivalent_<br/>(43824/43825)| `List.orderedBy`
| `List.note`| →→→→ _RelatedTo_ →→→→ <br/>(5975)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5976)| **`List.note`**| _Equivalent_<br/>(15317/15318)| `List.note`| _Equivalent_<br/>(28955/28956)| `List.note`| _Equivalent_<br/>(43826/43827)| `List.note`
| `List.entry`| _Equivalent_<br/>(5977/5978)| **`List.entry`**| _Equivalent_<br/>(15319/15320)| `List.entry`| _Equivalent_<br/>(28957/28958)| `List.entry`| _Equivalent_<br/>(43828/43829)| `List.entry`
| `List.entry.id`| _Equivalent_<br/>(5979/5980)| **`List.entry.id`**| _Equivalent_<br/>(15321/15322)| `List.entry.id`| _Equivalent_<br/>(28959/28960)| `List.entry.id`| _Equivalent_<br/>(43830/43831)| `List.entry.id`
| `List.entry.extension`| _Equivalent_<br/>(5981/5982)| **`List.entry.extension`**| _Equivalent_<br/>(15323/15324)| `List.entry.extension`| _Equivalent_<br/>(28961/28962)| `List.entry.extension`| _Equivalent_<br/>(43832/43833)| `List.entry.extension`
| `List.entry.modifierExtension`| _Equivalent_<br/>(5983/5984)| **`List.entry.modifierExtension`**| _Equivalent_<br/>(15325/15326)| `List.entry.modifierExtension`| _Equivalent_<br/>(28963/28964)| `List.entry.modifierExtension`| _Equivalent_<br/>(43834/43835)| `List.entry.modifierExtension`
| `List.entry.flag`| _Equivalent_<br/>(5985/5986)| **`List.entry.flag`**| _Equivalent_<br/>(15327/15328)| `List.entry.flag`| _Equivalent_<br/>(28965/28966)| `List.entry.flag`| _Equivalent_<br/>(43836/43837)| `List.entry.flag`
| `List.entry.deleted`| _Equivalent_<br/>(5987/5988)| **`List.entry.deleted`**| _Equivalent_<br/>(15329/15330)| `List.entry.deleted`| _Equivalent_<br/>(28967/28968)| `List.entry.deleted`| _Equivalent_<br/>(43838/43839)| `List.entry.deleted`
| `List.entry.date`| _Equivalent_<br/>(5989/5990)| **`List.entry.date`**| _Equivalent_<br/>(15331/15332)| `List.entry.date`| _Equivalent_<br/>(28969/28970)| `List.entry.date`| _Equivalent_<br/>(43840/43841)| `List.entry.date`
| `List.entry.item`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5991)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5992)| **`List.entry.item`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15333)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15334)| `List.entry.item`| _Equivalent_<br/>(28971/28972)| `List.entry.item`| _Equivalent_<br/>(43842/43843)| `List.entry.item`
| `List.emptyReason`| _Equivalent_<br/>(5993/5994)| **`List.emptyReason`**| _Equivalent_<br/>(15335/15336)| `List.emptyReason`| _Equivalent_<br/>(28973/28974)| `List.emptyReason`| _Equivalent_<br/>(43844/43845)| `List.emptyReason`
| *29 of 29 elements used* | | *29 of 29 elements used* | | *29 of 29 elements used* | | *29 of 29 elements used* | | *29 of 29 elements used* 

