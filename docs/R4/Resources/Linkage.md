Comparison of 
Generated at Friday, April 4, 2025 2:58:46 PM

### Linkage

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | Linkage |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Linkage` |
| Version | 4.0.1 |
| Description | Identifies two or more records (resource instances) that refer to the same real-world "occurrence". |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1100` |
| Database Snapshot Count | `17` |
| Database Differential Count | `6` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Linkage` | `Linkage` | `Linkage` | Linkage | Links records for 'same' item | 0..* | Linkage |  |  |
| `Linkage.active` | `Linkage.active` | `active` | Linkage.active | Whether this linkage assertion is active or not | 0..1 | boolean |  |  |
| `Linkage.author` | `Linkage.author` | `author` | Linkage.author | Who is responsible for linkages | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `Linkage.contained` | `Linkage.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Linkage.extension` | `Linkage.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Linkage.id` | `Linkage.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Linkage.implicitRules` | `Linkage.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Linkage.item` | `Linkage.item` | `item` | Linkage.item | Item to be linked | 1..* | BackboneElement |  |  |
| `Linkage.item.extension` | `Linkage.item.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Linkage.item.id` | `Linkage.item.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Linkage.item.modifierExtension` | `Linkage.item.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Linkage.item.resource` | `Linkage.item.resource` | `resource` | Linkage.item.resource | Resource being linked | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Linkage.item.type` | `Linkage.item.type` | `type` | Linkage.item.type | source \| alternate \| historical | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/linkage-type|4.0.1` |
| `Linkage.language` | `Linkage.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `Linkage.meta` | `Linkage.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Linkage.modifierExtension` | `Linkage.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Linkage.text` | `Linkage.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Linkage](/docs/R3/Resources/Linkage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Linkage\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `473`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `667`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Linkage](/docs/R4/Resources/Linkage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Linkage\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1523`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1524`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Linkage](/docs/R4B/Resources/Linkage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Linkage\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `996`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1225`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Linkage](/docs/R5/Resources/Linkage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Linkage\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Linkage from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 Linkage](/docs/R3/Resources/Linkage.md)| Relationship | R4 Linkage| Relationship | [R4B Linkage](/docs/R4B/Resources/Linkage.md)| Relationship | [R5 Linkage](/docs/R5/Resources/Linkage.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `Linkage`| _Equivalent_<br/>(15245/15246)| **`Linkage`**| _Equivalent_<br/>(28883/28884)| `Linkage`| _Equivalent_<br/>(43754/43755)| `Linkage`
| | | `Linkage.id`| _Equivalent_<br/>(15247/15248)| **`Linkage.id`**| _Equivalent_<br/>(28885/28886)| `Linkage.id`| _Equivalent_<br/>(43756/43757)| `Linkage.id`
| | | `Linkage.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15249)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15250)| **`Linkage.meta`**| _Equivalent_<br/>(28887/28888)| `Linkage.meta`| _Equivalent_<br/>(43758/43759)| `Linkage.meta`
| | | `Linkage.implicitRules`| _Equivalent_<br/>(15251/15252)| **`Linkage.implicitRules`**| _Equivalent_<br/>(28889/28890)| `Linkage.implicitRules`| _Equivalent_<br/>(43760/43761)| `Linkage.implicitRules`
| | | `Linkage.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15253)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(15254)| **`Linkage.language`**| _Equivalent_<br/>(28891/28892)| `Linkage.language`| _Equivalent_<br/>(43762/43763)| `Linkage.language`
| | | `Linkage.text`| _Equivalent_<br/>(15255/15256)| **`Linkage.text`**| _Equivalent_<br/>(28893/28894)| `Linkage.text`| _Equivalent_<br/>(43764/43765)| `Linkage.text`
| | | `Linkage.contained`| _Equivalent_<br/>(15257/15258)| **`Linkage.contained`**| _Equivalent_<br/>(28895/28896)| `Linkage.contained`| _Equivalent_<br/>(43766/43767)| `Linkage.contained`
| | | `Linkage.extension`| _Equivalent_<br/>(15259/15260)| **`Linkage.extension`**| _Equivalent_<br/>(28897/28898)| `Linkage.extension`| _Equivalent_<br/>(43768/43769)| `Linkage.extension`
| | | `Linkage.modifierExtension`| _Equivalent_<br/>(15261/15262)| **`Linkage.modifierExtension`**| _Equivalent_<br/>(28899/28900)| `Linkage.modifierExtension`| _Equivalent_<br/>(43770/43771)| `Linkage.modifierExtension`
| | | `Linkage.active`| _Equivalent_<br/>(15263/15264)| **`Linkage.active`**| _Equivalent_<br/>(28901/28902)| `Linkage.active`| _Equivalent_<br/>(43772/43773)| `Linkage.active`
| | | `Linkage.author`| →→→→ _RelatedTo_ →→→→ <br/>(15265)<hr/>←←←← _RelatedTo_ ←←←← <br/>(15266)| **`Linkage.author`**| _Equivalent_<br/>(28903/28904)| `Linkage.author`| _Equivalent_<br/>(43774/43775)| `Linkage.author`
| | | `Linkage.item`| _Equivalent_<br/>(15267/15268)| **`Linkage.item`**| _Equivalent_<br/>(28905/28906)| `Linkage.item`| _Equivalent_<br/>(43776/43777)| `Linkage.item`
| | | `Linkage.item.id`| _Equivalent_<br/>(15269/15270)| **`Linkage.item.id`**| _Equivalent_<br/>(28907/28908)| `Linkage.item.id`| _Equivalent_<br/>(43778/43779)| `Linkage.item.id`
| | | `Linkage.item.extension`| _Equivalent_<br/>(15271/15272)| **`Linkage.item.extension`**| _Equivalent_<br/>(28909/28910)| `Linkage.item.extension`| _Equivalent_<br/>(43780/43781)| `Linkage.item.extension`
| | | `Linkage.item.modifierExtension`| _Equivalent_<br/>(15273/15274)| **`Linkage.item.modifierExtension`**| _Equivalent_<br/>(28911/28912)| `Linkage.item.modifierExtension`| _Equivalent_<br/>(43782/43783)| `Linkage.item.modifierExtension`
| | | `Linkage.item.type`| _Equivalent_<br/>(15275/15276)| **`Linkage.item.type`**| _Equivalent_<br/>(28913/28914)| `Linkage.item.type`| _Equivalent_<br/>(43784/43785)| `Linkage.item.type`
| | | `Linkage.item.resource`| →→→→ _RelatedTo_ →→→→ <br/>(15277)<hr/>←←←← _RelatedTo_ ←←←← <br/>(15278)| **`Linkage.item.resource`**| _Equivalent_<br/>(28915/28916)| `Linkage.item.resource`| _Equivalent_<br/>(43786/43787)| `Linkage.item.resource`
| | | *17 of 17 elements used* | | *17 of 17 elements used* | | *17 of 17 elements used* | | *17 of 17 elements used* 

