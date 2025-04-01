Comparison of 
Generated at Tuesday, April 1, 2025 1:39:08 PM

### EligibilityRequest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | EligibilityRequest |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/EligibilityRequest` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for EligibilityRequest Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `74` |
| Database Snapshot Count | `16` |
| Database Differential Count | `8` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `EligibilityRequest` | `EligibilityRequest` | `EligibilityRequest` | EligibilityRequest | Eligibility request | 0..* | EligibilityRequest |  |  |
| `EligibilityRequest.contained` | `EligibilityRequest.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `EligibilityRequest.created` | `EligibilityRequest.created` | `created` |  | Creation date | 0..1 | dateTime |  |  |
| `EligibilityRequest.extension` | `EligibilityRequest.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `EligibilityRequest.id` | `EligibilityRequest.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `EligibilityRequest.identifier` | `EligibilityRequest.identifier` | `identifier` |  | Business Identifier | 0..* | Identifier |  |  |
| `EligibilityRequest.implicitRules` | `EligibilityRequest.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `EligibilityRequest.language` | `EligibilityRequest.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `EligibilityRequest.meta` | `EligibilityRequest.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `EligibilityRequest.modifierExtension` | `EligibilityRequest.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EligibilityRequest.organization` | `EligibilityRequest.organization` | `organization` |  | Responsible organization | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `EligibilityRequest.originalRuleset` | `EligibilityRequest.originalRuleset` | `originalRuleset` |  | Original version | 0..1 | Coding | `Example` | `http://hl7.org/fhir/ValueSet/ruleset` |
| `EligibilityRequest.provider` | `EligibilityRequest.provider` | `provider` |  | Responsible practitioner | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `EligibilityRequest.ruleset` | `EligibilityRequest.ruleset` | `ruleset` |  | Resource version | 0..1 | Coding | `Example` | `http://hl7.org/fhir/ValueSet/ruleset` |
| `EligibilityRequest.target` | `EligibilityRequest.target` | `target` |  | Insurer | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `EligibilityRequest.text` | `EligibilityRequest.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [EligibilityRequest](/docs/R2/Resources/EligibilityRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/EligibilityRequest\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `94`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `261`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EligibilityRequest](/docs/R3/Resources/EligibilityRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/EligibilityRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `444`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `639`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CoverageEligibilityRequest](/docs/R4/Resources/CoverageEligibilityRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1449`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1450`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CoverageEligibilityRequest](/docs/R4B/Resources/CoverageEligibilityRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityRequest\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `959`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1188`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CoverageEligibilityRequest](/docs/R5/Resources/CoverageEligibilityRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityRequest\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition EligibilityRequest from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 EligibilityRequest| Relationship | [R3 EligibilityRequest](/docs/R3/Resources/EligibilityRequest.md)| Relationship | [R4 CoverageEligibilityRequest](/docs/R4/Resources/CoverageEligibilityRequest.md)| Relationship | [R4B CoverageEligibilityRequest](/docs/R4B/Resources/CoverageEligibilityRequest.md)| Relationship | [R5 CoverageEligibilityRequest](/docs/R5/Resources/CoverageEligibilityRequest.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`EligibilityRequest`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4944)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4945)| `EligibilityRequest`| | | | | | | 
| **`EligibilityRequest.id`**| _Equivalent_<br/>(4946/4947)| `EligibilityRequest.id`| | | | | | | 
| **`EligibilityRequest.meta`**| _Equivalent_<br/>(4948/4949)| `EligibilityRequest.meta`| | | | | | | 
| **`EligibilityRequest.implicitRules`**| _Equivalent_<br/>(4950/4951)| `EligibilityRequest.implicitRules`| | | | | | | 
| **`EligibilityRequest.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4952)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4953)| `EligibilityRequest.language`| | | | | | | 
| **`EligibilityRequest.text`**| _Equivalent_<br/>(4954/4955)| `EligibilityRequest.text`| | | | | | | 
| **`EligibilityRequest.contained`**| _Equivalent_<br/>(4956/4957)| `EligibilityRequest.contained`| | | | | | | 
| **`EligibilityRequest.extension`**| _Equivalent_<br/>(4958/4959)| `EligibilityRequest.extension`| | | | | | | 
| **`EligibilityRequest.modifierExtension`**| _Equivalent_<br/>(4960/4961)| `EligibilityRequest.modifierExtension`| | | | | | | 
| **`EligibilityRequest.identifier`**| _Equivalent_<br/>(4962/4963)| `EligibilityRequest.identifier`| | | | | | | 
| **`EligibilityRequest.ruleset`**| | | | | | | | | 
| **`EligibilityRequest.originalRuleset`**| | | | | | | | | 
| **`EligibilityRequest.created`**| _Equivalent_<br/>(4964/4965)| `EligibilityRequest.created`| | | | | | | 
| **`EligibilityRequest.target`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(212)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(611)| `EligibilityRequest.insurer`| | | | | | | 
| **`EligibilityRequest.provider`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4966)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4967)| `EligibilityRequest.provider`| | | | | | | 
| **`EligibilityRequest.organization`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4968)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4969)| `EligibilityRequest.organization`| →→→→ _RelatedTo_ →→→→ <br/>(1020)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1453)| `CoverageEligibilityRequest.provider`| _Equivalent_<br/>(25143/25144)| `CoverageEligibilityRequest.provider`| _Equivalent_<br/>(40178/40179)| `CoverageEligibilityRequest.provider`
| *16 of 16 elements used* | | *14 of 24 elements used* | | *1 of 52 elements used* | | *1 of 52 elements used* | | *1 of 58 elements used* 

