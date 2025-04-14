Comparison of 
Generated at Monday, April 14, 2025 6:17:21 PM

### Count

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Count |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Count` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Count Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `450` |
| Database Snapshot Count | `8` |
| Database Differential Count | `1` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Count` | `Count` | `Count` | Count | A measured or measurable amount | 0..* | Count |  |  |
| `Count.code` | `Count.code` | `code` | Quantity.code | Coded form of the unit | 0..1 | code |  |  |
| `Count.comparator` | `Count.comparator` | `comparator` | Quantity.comparator | < \| <= \| >= \| > - how to understand the value | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/quantity-comparator` |
| `Count.extension` | `Count.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Count.id` | `Count.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Count.system` | `Count.system` | `system` | Quantity.system | System that defines coded unit form | 0..1 | uri |  |  |
| `Count.unit` | `Count.unit` | `unit` | Quantity.unit | Unit representation | 0..1 | string |  |  |
| `Count.value` | `Count.value` | `value` | Quantity.value | Numerical value (with implicit precision) | 0..1 | decimal |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Quantity](/docs/R2/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `62`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `220`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Count](/docs/R3/ComplexTypes/Count.md)<br/> `http://hl7.org/fhir/StructureDefinition/Count\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `391`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `587`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Count](/docs/R4/ComplexTypes/Count.md)<br/> `http://hl7.org/fhir/StructureDefinition/Count\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1327`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1328`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Count](/docs/R4B/ComplexTypes/Count.md)<br/> `http://hl7.org/fhir/StructureDefinition/Count\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `899`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1128`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Count](/docs/R5/ComplexTypes/Count.md)<br/> `http://hl7.org/fhir/StructureDefinition/Count\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Count from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Quantity](/docs/R2/ComplexTypes/Quantity.md)| Relationship | R3 Count| Relationship | [R4 Count](/docs/R4/ComplexTypes/Count.md)| Relationship | [R4B Count](/docs/R4B/ComplexTypes/Count.md)| Relationship | [R5 Count](/docs/R5/ComplexTypes/Count.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`Count`**| _Equivalent_<br/>(9283/9284)| `Count`| _Equivalent_<br/>(20628/20629)| `Count`| _Equivalent_<br/>(35753/35754)| `Count`
| | | **`Count.id`**| _Equivalent_<br/>(9285/9286)| `Count.id`| _Equivalent_<br/>(20630/20631)| `Count.id`| _Equivalent_<br/>(35755/35756)| `Count.id`
| | | **`Count.extension`**| _Equivalent_<br/>(9287/9288)| `Count.extension`| _Equivalent_<br/>(20632/20633)| `Count.extension`| _Equivalent_<br/>(35757/35758)| `Count.extension`
| | | **`Count.value`**| _Equivalent_<br/>(9289/9290)| `Count.value`| _Equivalent_<br/>(20634/20635)| `Count.value`| _Equivalent_<br/>(35759/35760)| `Count.value`
| | | **`Count.comparator`**| _Equivalent_<br/>(9291/9292)| `Count.comparator`| _Equivalent_<br/>(20636/20637)| `Count.comparator`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(35761)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(35762)| `Count.comparator`
| | | **`Count.unit`**| _Equivalent_<br/>(9293/9294)| `Count.unit`| _Equivalent_<br/>(20638/20639)| `Count.unit`| _Equivalent_<br/>(35763/35764)| `Count.unit`
| | | **`Count.system`**| _Equivalent_<br/>(9295/9296)| `Count.system`| _Equivalent_<br/>(20640/20641)| `Count.system`| _Equivalent_<br/>(35765/35766)| `Count.system`
| | | **`Count.code`**| _Equivalent_<br/>(9297/9298)| `Count.code`| _Equivalent_<br/>(20642/20643)| `Count.code`| _Equivalent_<br/>(35767/35768)| `Count.code`
| *0 of 8 elements used* <br/>remaining elements:<br/>`Quantity`, `Quantity.code`, `Quantity.comparator`, `Quantity.extension`, `Quantity.id`, `Quantity.system`, `Quantity.unit`, `Quantity.value`| | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* 

