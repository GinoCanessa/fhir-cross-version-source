Comparison of 
Generated at Monday, April 14, 2025 6:17:46 PM

### Substance

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Substance |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Substance` |
| Version | 5.0.0 |
| Description | A homogeneous material with a definite composition. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2390` |
| Database Snapshot Count | `23` |
| Database Differential Count | `12` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Substance` | `Substance` | `Substance` | Substance | A homogeneous material with a definite composition | 0..* | Substance |  |  |
| `Substance.category` | `Substance.category` | `category` | Substance.category | What class/type of substance this is | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/substance-category` |
| `Substance.code` | `Substance.code` | `code` | Substance.code | What substance this is | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/SubstanceDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/substance-code` |
| `Substance.contained` | `Substance.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Substance.description` | `Substance.description` | `description` | Substance.description | Textual description of the substance, comments | 0..1 | markdown |  |  |
| `Substance.expiry` | `Substance.expiry` | `expiry` | Substance.expiry | When no longer valid to use | 0..1 | dateTime |  |  |
| `Substance.extension` | `Substance.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Substance.id` | `Substance.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Substance.identifier` | `Substance.identifier` | `identifier` | Substance.identifier | Unique identifier | 0..* | Identifier |  |  |
| `Substance.implicitRules` | `Substance.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Substance.ingredient` | `Substance.ingredient` | `ingredient` | Substance.ingredient | Composition information about the substance | 0..* | BackboneElement |  |  |
| `Substance.ingredient.extension` | `Substance.ingredient.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Substance.ingredient.id` | `Substance.ingredient.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Substance.ingredient.modifierExtension` | `Substance.ingredient.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Substance.ingredient.quantity` | `Substance.ingredient.quantity` | `quantity` | Substance.ingredient.quantity | Optional amount (concentration) | 0..1 | Ratio |  |  |
| `Substance.ingredient.substance[x]` | `Substance.ingredient.substance[x]` | `substance[x]` | Substance.ingredient.substance[x] | A component of the substance | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Substance) | `Example` | `http://hl7.org/fhir/ValueSet/substance-code` |
| `Substance.instance` | `Substance.instance` | `instance` | Substance.instance | Is this an instance of a substance or a kind of one | 1..1 | boolean |  |  |
| `Substance.language` | `Substance.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Substance.meta` | `Substance.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Substance.modifierExtension` | `Substance.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Substance.quantity` | `Substance.quantity` | `quantity` | Substance.quantity | Amount of substance in the package | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `Substance.status` | `Substance.status` | `status` | Substance.status | active \| inactive \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/substance-status|5.0.0` |
| `Substance.text` | `Substance.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Substance](/docs/R2/Resources/Substance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Substance\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `160`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `327`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Substance](/docs/R3/Resources/Substance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Substance\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `521`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `715`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Substance](/docs/R4/Resources/Substance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Substance\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1627`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1628`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Substance](/docs/R4B/Resources/Substance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Substance\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1049`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1278`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Substance](/docs/R5/Resources/Substance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Substance\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Substance from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Substance](/docs/R2/Resources/Substance.md)| Relationship | [R3 Substance](/docs/R3/Resources/Substance.md)| Relationship | [R4 Substance](/docs/R4/Resources/Substance.md)| Relationship | [R4B Substance](/docs/R4B/Resources/Substance.md)| Relationship | R5 Substance
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Substance`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8023)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8024)| `Substance`| _Equivalent_<br/>(18895/18896)| `Substance`| _Equivalent_<br/>(33775/33776)| `Substance`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(48105)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(48106)| **`Substance`**
| `Substance.id`| _Equivalent_<br/>(8025/8026)| `Substance.id`| _Equivalent_<br/>(18897/18898)| `Substance.id`| _Equivalent_<br/>(33777/33778)| `Substance.id`| _Equivalent_<br/>(48107/48108)| **`Substance.id`**
| `Substance.meta`| _Equivalent_<br/>(8027/8028)| `Substance.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18899)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18900)| `Substance.meta`| _Equivalent_<br/>(33779/33780)| `Substance.meta`| _Equivalent_<br/>(48109/48110)| **`Substance.meta`**
| `Substance.implicitRules`| _Equivalent_<br/>(8029/8030)| `Substance.implicitRules`| _Equivalent_<br/>(18901/18902)| `Substance.implicitRules`| _Equivalent_<br/>(33781/33782)| `Substance.implicitRules`| _Equivalent_<br/>(48111/48112)| **`Substance.implicitRules`**
| `Substance.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8031)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(8032)| `Substance.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18903)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18904)| `Substance.language`| _Equivalent_<br/>(33783/33784)| `Substance.language`| _Equivalent_<br/>(48113/48114)| **`Substance.language`**
| `Substance.text`| _Equivalent_<br/>(8033/8034)| `Substance.text`| _Equivalent_<br/>(18905/18906)| `Substance.text`| _Equivalent_<br/>(33785/33786)| `Substance.text`| _Equivalent_<br/>(48115/48116)| **`Substance.text`**
| `Substance.contained`| _Equivalent_<br/>(8035/8036)| `Substance.contained`| _Equivalent_<br/>(18907/18908)| `Substance.contained`| _Equivalent_<br/>(33787/33788)| `Substance.contained`| _Equivalent_<br/>(48117/48118)| **`Substance.contained`**
| `Substance.extension`| _Equivalent_<br/>(8037/8038)| `Substance.extension`| _Equivalent_<br/>(18909/18910)| `Substance.extension`| _Equivalent_<br/>(33789/33790)| `Substance.extension`| _Equivalent_<br/>(48119/48120)| **`Substance.extension`**
| `Substance.modifierExtension`| _Equivalent_<br/>(8039/8040)| `Substance.modifierExtension`| _Equivalent_<br/>(18911/18912)| `Substance.modifierExtension`| _Equivalent_<br/>(33791/33792)| `Substance.modifierExtension`| _Equivalent_<br/>(48121/48122)| **`Substance.modifierExtension`**
| `Substance.identifier`| _Equivalent_<br/>(8041/8042)| `Substance.identifier`| _Equivalent_<br/>(18913/18914)| `Substance.identifier`| _Equivalent_<br/>(33793/33794)| `Substance.identifier`| _Equivalent_<br/>(48123/48124)| **`Substance.identifier`**
| `Substance.instance`| _Equivalent_<br/>(8049/8050)| `Substance.instance`| _Equivalent_<br/>(18923/18924)| `Substance.instance`| _Equivalent_<br/>(33803/33804)| `Substance.instance`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48133)<hr/>←←←← _RelatedTo_ ←←←← <br/>(48134)| **`Substance.instance`**
| | | `Substance.status`| _Equivalent_<br/>(18915/18916)| `Substance.status`| _Equivalent_<br/>(33795/33796)| `Substance.status`| _Equivalent_<br/>(48125/48126)| **`Substance.status`**
| `Substance.category`| _Equivalent_<br/>(8043/8044)| `Substance.category`| _Equivalent_<br/>(18917/18918)| `Substance.category`| _Equivalent_<br/>(33797/33798)| `Substance.category`| _Equivalent_<br/>(48127/48128)| **`Substance.category`**
| `Substance.code`| _Equivalent_<br/>(8045/8046)| `Substance.code`| _Equivalent_<br/>(18919/18920)| `Substance.code`| _Equivalent_<br/>(33799/33800)| `Substance.code`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(48129)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48130)| **`Substance.code`**
| `Substance.description`| _Equivalent_<br/>(8047/8048)| `Substance.description`| _Equivalent_<br/>(18921/18922)| `Substance.description`| _Equivalent_<br/>(33801/33802)| `Substance.description`| _Equivalent_<br/>(48131/48132)| **`Substance.description`**
| | | | | | | | | **`Substance.expiry`**
| | | | | | | | | **`Substance.quantity`**
| `Substance.ingredient`| _Equivalent_<br/>(8063/8064)| `Substance.ingredient`| _Equivalent_<br/>(18937/18938)| `Substance.ingredient`| _Equivalent_<br/>(33817/33818)| `Substance.ingredient`| _Equivalent_<br/>(48141/48142)| **`Substance.ingredient`**
| `Substance.ingredient.id`| _Equivalent_<br/>(8065/8066)| `Substance.ingredient.id`| _Equivalent_<br/>(18939/18940)| `Substance.ingredient.id`| _Equivalent_<br/>(33819/33820)| `Substance.ingredient.id`| _Equivalent_<br/>(48143/48144)| **`Substance.ingredient.id`**
| `Substance.ingredient.extension`| _Equivalent_<br/>(8067/8068)| `Substance.ingredient.extension`| _Equivalent_<br/>(18941/18942)| `Substance.ingredient.extension`| _Equivalent_<br/>(33821/33822)| `Substance.ingredient.extension`| _Equivalent_<br/>(48145/48146)| **`Substance.ingredient.extension`**
| `Substance.ingredient.modifierExtension`| _Equivalent_<br/>(8069/8070)| `Substance.ingredient.modifierExtension`| _Equivalent_<br/>(18943/18944)| `Substance.ingredient.modifierExtension`| _Equivalent_<br/>(33823/33824)| `Substance.ingredient.modifierExtension`| _Equivalent_<br/>(48147/48148)| **`Substance.ingredient.modifierExtension`**
| `Substance.ingredient.quantity`| _Equivalent_<br/>(8071/8072)| `Substance.ingredient.quantity`| _Equivalent_<br/>(18945/18946)| `Substance.ingredient.quantity`| _Equivalent_<br/>(33825/33826)| `Substance.ingredient.quantity`| _Equivalent_<br/>(48149/48150)| **`Substance.ingredient.quantity`**
| `Substance.ingredient.substance`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(421)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(763)| `Substance.ingredient.substance[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18947)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18948)| `Substance.ingredient.substance[x]`| _Equivalent_<br/>(33827/33828)| `Substance.ingredient.substance[x]`| _Equivalent_<br/>(48151/48152)| **`Substance.ingredient.substance[x]`**
| *20 of 26 elements used* <br/>remaining elements:<br/>`Substance.instance.expiry`, `Substance.instance.extension`, `Substance.instance.id`, `Substance.instance.identifier`, `Substance.instance.modifierExtension`, `Substance.instance.quantity`| | *21 of 27 elements used* <br/>remaining elements:<br/>`Substance.instance.expiry`, `Substance.instance.extension`, `Substance.instance.id`, `Substance.instance.identifier`, `Substance.instance.modifierExtension`, `Substance.instance.quantity`| | *21 of 27 elements used* <br/>remaining elements:<br/>`Substance.instance.expiry`, `Substance.instance.extension`, `Substance.instance.id`, `Substance.instance.identifier`, `Substance.instance.modifierExtension`, `Substance.instance.quantity`| | *21 of 27 elements used* <br/>remaining elements:<br/>`Substance.instance.expiry`, `Substance.instance.extension`, `Substance.instance.id`, `Substance.instance.identifier`, `Substance.instance.modifierExtension`, `Substance.instance.quantity`| | *23 of 23 elements used* 

