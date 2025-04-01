Comparison of 
Generated at Tuesday, April 1, 2025 1:39:33 PM

### SupplyDelivery

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | SupplyDelivery |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SupplyDelivery` |
| Version | 4.3.0 |
| Description | Record of delivery of what is supplied. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1772` |
| Database Snapshot Count | `25` |
| Database Differential Count | `14` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SupplyDelivery` | `SupplyDelivery` | `SupplyDelivery` | SupplyDelivery | Delivery of bulk Supplies | 0..* | SupplyDelivery |  |  |
| `SupplyDelivery.basedOn` | `SupplyDelivery.basedOn` | `basedOn` | SupplyDelivery.basedOn | Fulfills plan, proposal or order | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/SupplyRequest) |  |  |
| `SupplyDelivery.contained` | `SupplyDelivery.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `SupplyDelivery.destination` | `SupplyDelivery.destination` | `destination` | SupplyDelivery.destination | Where the Supply was sent | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `SupplyDelivery.extension` | `SupplyDelivery.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SupplyDelivery.id` | `SupplyDelivery.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `SupplyDelivery.identifier` | `SupplyDelivery.identifier` | `identifier` | SupplyDelivery.identifier | External identifier | 0..* | Identifier |  |  |
| `SupplyDelivery.implicitRules` | `SupplyDelivery.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `SupplyDelivery.language` | `SupplyDelivery.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `SupplyDelivery.meta` | `SupplyDelivery.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `SupplyDelivery.modifierExtension` | `SupplyDelivery.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SupplyDelivery.occurrence[x]` | `SupplyDelivery.occurrence[x]` | `occurrence[x]` | SupplyDelivery.occurrence[x] | When event occurred | 0..1 | dateTime, Period, Timing |  |  |
| `SupplyDelivery.partOf` | `SupplyDelivery.partOf` | `partOf` | SupplyDelivery.partOf | Part of referenced event | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Contract), Reference(http://hl7.org/fhir/StructureDefinition/SupplyDelivery) |  |  |
| `SupplyDelivery.patient` | `SupplyDelivery.patient` | `patient` | SupplyDelivery.patient | Patient for whom the item is supplied | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `SupplyDelivery.receiver` | `SupplyDelivery.receiver` | `receiver` | SupplyDelivery.receiver | Who collected the Supply | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `SupplyDelivery.status` | `SupplyDelivery.status` | `status` | SupplyDelivery.status | in-progress \| completed \| abandoned \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/supplydelivery-status|4.3.0` |
| `SupplyDelivery.suppliedItem` | `SupplyDelivery.suppliedItem` | `suppliedItem` | SupplyDelivery.suppliedItem | The item that is delivered or supplied | 0..1 | BackboneElement |  |  |
| `SupplyDelivery.suppliedItem.extension` | `SupplyDelivery.suppliedItem.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SupplyDelivery.suppliedItem.id` | `SupplyDelivery.suppliedItem.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SupplyDelivery.suppliedItem.item[x]` | `SupplyDelivery.suppliedItem.item[x]` | `item[x]` | SupplyDelivery.suppliedItem.item[x] | Medication, Substance, or Device supplied | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/Substance) | `Example` | `http://hl7.org/fhir/ValueSet/supply-item` |
| `SupplyDelivery.suppliedItem.modifierExtension` | `SupplyDelivery.suppliedItem.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SupplyDelivery.suppliedItem.quantity` | `SupplyDelivery.suppliedItem.quantity` | `quantity` | SupplyDelivery.suppliedItem.quantity | Amount dispensed | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `SupplyDelivery.supplier` | `SupplyDelivery.supplier` | `supplier` | SupplyDelivery.supplier | Dispenser | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `SupplyDelivery.text` | `SupplyDelivery.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `SupplyDelivery.type` | `SupplyDelivery.type` | `type` | SupplyDelivery.type | Category of dispense event | 0..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/supplydelivery-type|4.3.0` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [SupplyDelivery](/docs/R2/Resources/SupplyDelivery.md)<br/> `http://hl7.org/fhir/StructureDefinition/SupplyDelivery\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `161`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `328`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SupplyDelivery](/docs/R3/Resources/SupplyDelivery.md)<br/> `http://hl7.org/fhir/StructureDefinition/SupplyDelivery\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `522`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `716`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SupplyDelivery](/docs/R4/Resources/SupplyDelivery.md)<br/> `http://hl7.org/fhir/StructureDefinition/SupplyDelivery\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1629`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1630`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SupplyDelivery](/docs/R4B/Resources/SupplyDelivery.md)<br/> `http://hl7.org/fhir/StructureDefinition/SupplyDelivery\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1051`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1280`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SupplyDelivery](/docs/R5/Resources/SupplyDelivery.md)<br/> `http://hl7.org/fhir/StructureDefinition/SupplyDelivery\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition SupplyDelivery from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 SupplyDelivery](/docs/R2/Resources/SupplyDelivery.md)| Relationship | [R3 SupplyDelivery](/docs/R3/Resources/SupplyDelivery.md)| Relationship | [R4 SupplyDelivery](/docs/R4/Resources/SupplyDelivery.md)| Relationship | R4B SupplyDelivery| Relationship | [R5 SupplyDelivery](/docs/R5/Resources/SupplyDelivery.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `SupplyDelivery`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8073)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8074)| `SupplyDelivery`| _Equivalent_<br/>(18956/18957)| `SupplyDelivery`| _Equivalent_<br/>(33829/33830)| **`SupplyDelivery`**| _Equivalent_<br/>(48381/48382)| `SupplyDelivery`
| `SupplyDelivery.id`| _Equivalent_<br/>(8075/8076)| `SupplyDelivery.id`| _Equivalent_<br/>(18958/18959)| `SupplyDelivery.id`| _Equivalent_<br/>(33831/33832)| **`SupplyDelivery.id`**| _Equivalent_<br/>(48383/48384)| `SupplyDelivery.id`
| `SupplyDelivery.meta`| _Equivalent_<br/>(8077/8078)| `SupplyDelivery.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18960)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18961)| `SupplyDelivery.meta`| _Equivalent_<br/>(33833/33834)| **`SupplyDelivery.meta`**| _Equivalent_<br/>(48385/48386)| `SupplyDelivery.meta`
| `SupplyDelivery.implicitRules`| _Equivalent_<br/>(8079/8080)| `SupplyDelivery.implicitRules`| _Equivalent_<br/>(18962/18963)| `SupplyDelivery.implicitRules`| _Equivalent_<br/>(33835/33836)| **`SupplyDelivery.implicitRules`**| _Equivalent_<br/>(48387/48388)| `SupplyDelivery.implicitRules`
| `SupplyDelivery.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8081)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(8082)| `SupplyDelivery.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18964)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18965)| `SupplyDelivery.language`| _Equivalent_<br/>(33837/33838)| **`SupplyDelivery.language`**| _Equivalent_<br/>(48389/48390)| `SupplyDelivery.language`
| `SupplyDelivery.text`| _Equivalent_<br/>(8083/8084)| `SupplyDelivery.text`| _Equivalent_<br/>(18966/18967)| `SupplyDelivery.text`| _Equivalent_<br/>(33839/33840)| **`SupplyDelivery.text`**| _Equivalent_<br/>(48391/48392)| `SupplyDelivery.text`
| `SupplyDelivery.contained`| _Equivalent_<br/>(8085/8086)| `SupplyDelivery.contained`| _Equivalent_<br/>(18968/18969)| `SupplyDelivery.contained`| _Equivalent_<br/>(33841/33842)| **`SupplyDelivery.contained`**| _Equivalent_<br/>(48393/48394)| `SupplyDelivery.contained`
| `SupplyDelivery.extension`| →→→→ _Equivalent_ →→→→ <br/>(8087)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(767)| `SupplyDelivery.extension`| _Equivalent_<br/>(18970/18971)| `SupplyDelivery.extension`| _Equivalent_<br/>(33843/33844)| **`SupplyDelivery.extension`**| _Equivalent_<br/>(48395/48396)| `SupplyDelivery.extension`
| `SupplyDelivery.whenPrepared`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(425)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(767)| `SupplyDelivery.extension`| _Equivalent_<br/>(18970/18971)| `SupplyDelivery.extension`| _Equivalent_<br/>(33843/33844)| **`SupplyDelivery.extension`**| _Equivalent_<br/>(48395/48396)| `SupplyDelivery.extension`
| `SupplyDelivery.modifierExtension`| _Equivalent_<br/>(8089/8090)| `SupplyDelivery.modifierExtension`| _Equivalent_<br/>(18972/18973)| `SupplyDelivery.modifierExtension`| _Equivalent_<br/>(33845/33846)| **`SupplyDelivery.modifierExtension`**| _Equivalent_<br/>(48397/48398)| `SupplyDelivery.modifierExtension`
| `SupplyDelivery.identifier`| _Equivalent_<br/>(8091/8092)| `SupplyDelivery.identifier`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18974)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18975)| `SupplyDelivery.identifier`| _Equivalent_<br/>(33847/33848)| **`SupplyDelivery.identifier`**| _Equivalent_<br/>(48399/48400)| `SupplyDelivery.identifier`
| | | `SupplyDelivery.basedOn`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18976)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18977)| `SupplyDelivery.basedOn`| _Equivalent_<br/>(33849/33850)| **`SupplyDelivery.basedOn`**| _Equivalent_<br/>(48401/48402)| `SupplyDelivery.basedOn`
| | | `SupplyDelivery.partOf`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18978)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18979)| `SupplyDelivery.partOf`| _Equivalent_<br/>(33851/33852)| **`SupplyDelivery.partOf`**| _Equivalent_<br/>(48403/48404)| `SupplyDelivery.partOf`
| `SupplyDelivery.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8093)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8094)| `SupplyDelivery.status`| _Equivalent_<br/>(18980/18981)| `SupplyDelivery.status`| _Equivalent_<br/>(33853/33854)| **`SupplyDelivery.status`**| _Equivalent_<br/>(48405/48406)| `SupplyDelivery.status`
| `SupplyDelivery.patient`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8095)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8096)| `SupplyDelivery.patient`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18982)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18983)| `SupplyDelivery.patient`| _Equivalent_<br/>(33855/33856)| **`SupplyDelivery.patient`**| _Equivalent_<br/>(48407/48408)| `SupplyDelivery.patient`
| `SupplyDelivery.type`| _Equivalent_<br/>(8097/8098)| `SupplyDelivery.type`| _Equivalent_<br/>(18984/18985)| `SupplyDelivery.type`| _Equivalent_<br/>(33857/33858)| **`SupplyDelivery.type`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48409)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48410)| `SupplyDelivery.type`
| `SupplyDelivery.suppliedItem`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(8099)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8100)| `SupplyDelivery.suppliedItem`| _Equivalent_<br/>(18986/18987)| `SupplyDelivery.suppliedItem`| _Equivalent_<br/>(33859/33860)| **`SupplyDelivery.suppliedItem`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48411)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48412)| `SupplyDelivery.suppliedItem`
| | | `SupplyDelivery.suppliedItem.id`| _Equivalent_<br/>(18988/18989)| `SupplyDelivery.suppliedItem.id`| _Equivalent_<br/>(33861/33862)| **`SupplyDelivery.suppliedItem.id`**| _Equivalent_<br/>(48413/48414)| `SupplyDelivery.suppliedItem.id`
| | | `SupplyDelivery.suppliedItem.extension`| _Equivalent_<br/>(18990/18991)| `SupplyDelivery.suppliedItem.extension`| _Equivalent_<br/>(33863/33864)| **`SupplyDelivery.suppliedItem.extension`**| _Equivalent_<br/>(48415/48416)| `SupplyDelivery.suppliedItem.extension`
| | | `SupplyDelivery.suppliedItem.modifierExtension`| _Equivalent_<br/>(18992/18993)| `SupplyDelivery.suppliedItem.modifierExtension`| _Equivalent_<br/>(33865/33866)| **`SupplyDelivery.suppliedItem.modifierExtension`**| _Equivalent_<br/>(48417/48418)| `SupplyDelivery.suppliedItem.modifierExtension`
| `SupplyDelivery.quantity`| _Equivalent_<br/>(422/766)| `SupplyDelivery.suppliedItem.quantity`| _Equivalent_<br/>(18994/18995)| `SupplyDelivery.suppliedItem.quantity`| _Equivalent_<br/>(33867/33868)| **`SupplyDelivery.suppliedItem.quantity`**| _Equivalent_<br/>(48419/48420)| `SupplyDelivery.suppliedItem.quantity`
| | | `SupplyDelivery.suppliedItem.item[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18996)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18997)| `SupplyDelivery.suppliedItem.item[x]`| _Equivalent_<br/>(33869/33870)| **`SupplyDelivery.suppliedItem.item[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(48421)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(48422)| `SupplyDelivery.suppliedItem.item[x]`
| `SupplyDelivery.whenPrepared`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(424)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(765)| `SupplyDelivery.occurrence[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18998)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18999)| `SupplyDelivery.occurrence[x]`| _Equivalent_<br/>(33871/33872)| **`SupplyDelivery.occurrence[x]`**| _Equivalent_<br/>(48423/48424)| `SupplyDelivery.occurrence[x]`
| `SupplyDelivery.time`| →→→→ _Equivalent_ →→→→ <br/>(18955)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(765)| `SupplyDelivery.occurrence[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18998)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18999)| `SupplyDelivery.occurrence[x]`| _Equivalent_<br/>(33871/33872)| **`SupplyDelivery.occurrence[x]`**| _Equivalent_<br/>(48423/48424)| `SupplyDelivery.occurrence[x]`
| `SupplyDelivery.supplier`| →→→→ _RelatedTo_ →→→→ <br/>(8101)<hr/>←←←← _RelatedTo_ ←←←← <br/>(8102)| `SupplyDelivery.supplier`| →→→→ _RelatedTo_ →→→→ <br/>(19000)<hr/>←←←← _RelatedTo_ ←←←← <br/>(19001)| `SupplyDelivery.supplier`| _Equivalent_<br/>(33873/33874)| **`SupplyDelivery.supplier`**| _Equivalent_<br/>(48425/48426)| `SupplyDelivery.supplier`
| `SupplyDelivery.destination`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8103)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8104)| `SupplyDelivery.destination`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19002)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19003)| `SupplyDelivery.destination`| _Equivalent_<br/>(33875/33876)| **`SupplyDelivery.destination`**| _Equivalent_<br/>(48427/48428)| `SupplyDelivery.destination`
| `SupplyDelivery.receiver`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8105)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8106)| `SupplyDelivery.receiver`| →→→→ _RelatedTo_ →→→→ <br/>(19004)<hr/>←←←← _RelatedTo_ ←←←← <br/>(19005)| `SupplyDelivery.receiver`| _Equivalent_<br/>(33877/33878)| **`SupplyDelivery.receiver`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(48429)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(48430)| `SupplyDelivery.receiver`
| *20 of 20 elements used* | | *25 of 25 elements used* | | *25 of 25 elements used* | | *25 of 25 elements used* | | *25 of 25 elements used* 

