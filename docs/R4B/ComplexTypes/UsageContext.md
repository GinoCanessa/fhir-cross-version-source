Comparison of 
Generated at Thursday, April 3, 2025 8:18:25 AM

### UsageContext

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | UsageContext |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/UsageContext` |
| Version | 4.3.0 |
| Description | Base StructureDefinition for UsageContext Type: Specifies clinical/business/etc. metadata that can be used to retrieve, index and/or categorize an artifact. This metadata can either be specific to the applicable population (e.g., age category, DRG) or the specific context of care (e.g., venue, care setting, provider of care). |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `1637` |
| Database Snapshot Count | `5` |
| Database Differential Count | `3` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `UsageContext` | `UsageContext` | `UsageContext` | UsageContext | Describes the context of use for a conformance or knowledge resource | 0..* | UsageContext |  |  |
| `UsageContext.code` | `UsageContext.code` | `code` | UsageContext.code | Type of context being specified | 1..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/usage-context-type` |
| `UsageContext.extension` | `UsageContext.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `UsageContext.id` | `UsageContext.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `UsageContext.value[x]` | `UsageContext.value[x]` | `value[x]` | UsageContext.value[x] | Value that defines the context | 1..1 | CodeableConcept, Quantity, Range, Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/InsurancePlan), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/PlanDefinition), Reference(http://hl7.org/fhir/StructureDefinition/ResearchStudy) | `Example` | `http://hl7.org/fhir/ValueSet/use-context` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [UsageContext](/docs/R3/ComplexTypes/UsageContext.md)<br/> `http://hl7.org/fhir/StructureDefinition/UsageContext\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `414`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `610`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [UsageContext](/docs/R4/ComplexTypes/UsageContext.md)<br/> `http://hl7.org/fhir/StructureDefinition/UsageContext\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1385`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1386`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [UsageContext](/docs/R4B/ComplexTypes/UsageContext.md)<br/> `http://hl7.org/fhir/StructureDefinition/UsageContext\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `925`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1154`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [UsageContext](/docs/R5/ComplexTypes/UsageContext.md)<br/> `http://hl7.org/fhir/StructureDefinition/UsageContext\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition UsageContext from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 UsageContext](/docs/R3/ComplexTypes/UsageContext.md)| Relationship | [R4 UsageContext](/docs/R4/ComplexTypes/UsageContext.md)| Relationship | R4B UsageContext| Relationship | [R5 UsageContext](/docs/R5/ComplexTypes/UsageContext.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `UsageContext`| _Equivalent_<br/>(9867/9868)| `UsageContext`| _Equivalent_<br/>(21356/21357)| **`UsageContext`**| _Equivalent_<br/>(36421/36422)| `UsageContext`
| | | `UsageContext.id`| _Equivalent_<br/>(9869/9870)| `UsageContext.id`| _Equivalent_<br/>(21358/21359)| **`UsageContext.id`**| _Equivalent_<br/>(36423/36424)| `UsageContext.id`
| | | `UsageContext.extension`| _Equivalent_<br/>(9871/9872)| `UsageContext.extension`| _Equivalent_<br/>(21360/21361)| **`UsageContext.extension`**| _Equivalent_<br/>(36425/36426)| `UsageContext.extension`
| | | `UsageContext.code`| _Equivalent_<br/>(9873/9874)| `UsageContext.code`| _Equivalent_<br/>(21362/21363)| **`UsageContext.code`**| _Equivalent_<br/>(36427/36428)| `UsageContext.code`
| | | `UsageContext.value[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9875)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9876)| `UsageContext.value[x]`| _Equivalent_<br/>(21364/21365)| **`UsageContext.value[x]`**| _Equivalent_<br/>(36429/36430)| `UsageContext.value[x]`
| | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* 

