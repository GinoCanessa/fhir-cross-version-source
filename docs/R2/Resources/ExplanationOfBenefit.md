Comparison of 
Generated at Tuesday, April 1, 2025 1:39:09 PM

### ExplanationOfBenefit

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | ExplanationOfBenefit |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for ExplanationOfBenefit Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `80` |
| Database Snapshot Count | `19` |
| Database Differential Count | `11` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ExplanationOfBenefit` | `ExplanationOfBenefit` | `ExplanationOfBenefit` | ExplanationOfBenefit | Remittance resource | 0..* | ExplanationOfBenefit |  |  |
| `ExplanationOfBenefit.contained` | `ExplanationOfBenefit.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ExplanationOfBenefit.created` | `ExplanationOfBenefit.created` | `created` |  | Creation date | 0..1 | dateTime |  |  |
| `ExplanationOfBenefit.disposition` | `ExplanationOfBenefit.disposition` | `disposition` |  | Disposition Message | 0..1 | string |  |  |
| `ExplanationOfBenefit.extension` | `ExplanationOfBenefit.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ExplanationOfBenefit.id` | `ExplanationOfBenefit.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ExplanationOfBenefit.identifier` | `ExplanationOfBenefit.identifier` | `identifier` |  | Business Identifier | 0..* | Identifier |  |  |
| `ExplanationOfBenefit.implicitRules` | `ExplanationOfBenefit.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ExplanationOfBenefit.language` | `ExplanationOfBenefit.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `ExplanationOfBenefit.meta` | `ExplanationOfBenefit.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ExplanationOfBenefit.modifierExtension` | `ExplanationOfBenefit.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ExplanationOfBenefit.organization` | `ExplanationOfBenefit.organization` | `organization` |  | Insurer | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `ExplanationOfBenefit.originalRuleset` | `ExplanationOfBenefit.originalRuleset` | `originalRuleset` |  | Original version | 0..1 | Coding | `Example` | `http://hl7.org/fhir/ValueSet/ruleset` |
| `ExplanationOfBenefit.outcome` | `ExplanationOfBenefit.outcome` | `outcome` |  | complete \| error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/remittance-outcome` |
| `ExplanationOfBenefit.request` | `ExplanationOfBenefit.request` | `request` |  | Claim reference | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Claim) |  |  |
| `ExplanationOfBenefit.requestOrganization` | `ExplanationOfBenefit.requestOrganization` | `requestOrganization` |  | Responsible organization | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `ExplanationOfBenefit.requestProvider` | `ExplanationOfBenefit.requestProvider` | `requestProvider` |  | Responsible practitioner | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `ExplanationOfBenefit.ruleset` | `ExplanationOfBenefit.ruleset` | `ruleset` |  | Resource version | 0..1 | Coding | `Example` | `http://hl7.org/fhir/ValueSet/ruleset` |
| `ExplanationOfBenefit.text` | `ExplanationOfBenefit.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ExplanationOfBenefit](/docs/R2/Resources/ExplanationOfBenefit.md)<br/> `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `110`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `276`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ExplanationOfBenefit](/docs/R3/Resources/ExplanationOfBenefit.md)<br/> `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `460`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `654`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ExplanationOfBenefit](/docs/R4/Resources/ExplanationOfBenefit.md)<br/> `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1491`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1492`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ExplanationOfBenefit](/docs/R4B/Resources/ExplanationOfBenefit.md)<br/> `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `979`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1208`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ExplanationOfBenefit](/docs/R5/Resources/ExplanationOfBenefit.md)<br/> `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ExplanationOfBenefit from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 ExplanationOfBenefit| Relationship | [R3 ExplanationOfBenefit](/docs/R3/Resources/ExplanationOfBenefit.md)| Relationship | [R4 ExplanationOfBenefit](/docs/R4/Resources/ExplanationOfBenefit.md)| Relationship | [R4B ExplanationOfBenefit](/docs/R4B/Resources/ExplanationOfBenefit.md)| Relationship | [R5 ExplanationOfBenefit](/docs/R5/Resources/ExplanationOfBenefit.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`ExplanationOfBenefit`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5223)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5224)| `ExplanationOfBenefit`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14022)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14023)| `ExplanationOfBenefit`| _Equivalent_<br/>(26907/26908)| `ExplanationOfBenefit`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41914)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41915)| `ExplanationOfBenefit`
| **`ExplanationOfBenefit.id`**| _Equivalent_<br/>(5225/5226)| `ExplanationOfBenefit.id`| _Equivalent_<br/>(14024/14025)| `ExplanationOfBenefit.id`| _Equivalent_<br/>(26909/26910)| `ExplanationOfBenefit.id`| _Equivalent_<br/>(41916/41917)| `ExplanationOfBenefit.id`
| **`ExplanationOfBenefit.meta`**| _Equivalent_<br/>(5227/5228)| `ExplanationOfBenefit.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14026)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14027)| `ExplanationOfBenefit.meta`| _Equivalent_<br/>(26911/26912)| `ExplanationOfBenefit.meta`| _Equivalent_<br/>(41918/41919)| `ExplanationOfBenefit.meta`
| **`ExplanationOfBenefit.implicitRules`**| _Equivalent_<br/>(5229/5230)| `ExplanationOfBenefit.implicitRules`| _Equivalent_<br/>(14028/14029)| `ExplanationOfBenefit.implicitRules`| _Equivalent_<br/>(26913/26914)| `ExplanationOfBenefit.implicitRules`| _Equivalent_<br/>(41920/41921)| `ExplanationOfBenefit.implicitRules`
| **`ExplanationOfBenefit.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5231)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(5232)| `ExplanationOfBenefit.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14030)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(14031)| `ExplanationOfBenefit.language`| _Equivalent_<br/>(26915/26916)| `ExplanationOfBenefit.language`| _Equivalent_<br/>(41922/41923)| `ExplanationOfBenefit.language`
| **`ExplanationOfBenefit.text`**| _Equivalent_<br/>(5233/5234)| `ExplanationOfBenefit.text`| _Equivalent_<br/>(14032/14033)| `ExplanationOfBenefit.text`| _Equivalent_<br/>(26917/26918)| `ExplanationOfBenefit.text`| _Equivalent_<br/>(41924/41925)| `ExplanationOfBenefit.text`
| **`ExplanationOfBenefit.contained`**| _Equivalent_<br/>(5235/5236)| `ExplanationOfBenefit.contained`| _Equivalent_<br/>(14034/14035)| `ExplanationOfBenefit.contained`| _Equivalent_<br/>(26919/26920)| `ExplanationOfBenefit.contained`| _Equivalent_<br/>(41926/41927)| `ExplanationOfBenefit.contained`
| **`ExplanationOfBenefit.extension`**| _Equivalent_<br/>(5237/5238)| `ExplanationOfBenefit.extension`| _Equivalent_<br/>(14036/14037)| `ExplanationOfBenefit.extension`| _Equivalent_<br/>(26921/26922)| `ExplanationOfBenefit.extension`| _Equivalent_<br/>(41928/41929)| `ExplanationOfBenefit.extension`
| **`ExplanationOfBenefit.modifierExtension`**| _Equivalent_<br/>(5239/5240)| `ExplanationOfBenefit.modifierExtension`| _Equivalent_<br/>(14038/14039)| `ExplanationOfBenefit.modifierExtension`| _Equivalent_<br/>(26923/26924)| `ExplanationOfBenefit.modifierExtension`| _Equivalent_<br/>(41930/41931)| `ExplanationOfBenefit.modifierExtension`
| **`ExplanationOfBenefit.identifier`**| _Equivalent_<br/>(5241/5242)| `ExplanationOfBenefit.identifier`| _Equivalent_<br/>(14040/14041)| `ExplanationOfBenefit.identifier`| _Equivalent_<br/>(26925/26926)| `ExplanationOfBenefit.identifier`| _Equivalent_<br/>(41932/41933)| `ExplanationOfBenefit.identifier`
| **`ExplanationOfBenefit.request`**| | | | | | | | | 
| **`ExplanationOfBenefit.outcome`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5243)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(5244)| `ExplanationOfBenefit.outcome`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14068)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(14069)| `ExplanationOfBenefit.outcome`| _Equivalent_<br/>(26991/26992)| `ExplanationOfBenefit.outcome`| _Equivalent_<br/>(41998/41999)| `ExplanationOfBenefit.outcome`
| **`ExplanationOfBenefit.disposition`**| _Equivalent_<br/>(5245/5246)| `ExplanationOfBenefit.disposition`| _Equivalent_<br/>(14070/14071)| `ExplanationOfBenefit.disposition`| _Equivalent_<br/>(26993/26994)| `ExplanationOfBenefit.disposition`| _Equivalent_<br/>(42000/42001)| `ExplanationOfBenefit.disposition`
| **`ExplanationOfBenefit.ruleset`**| | | | | | | | | 
| **`ExplanationOfBenefit.originalRuleset`**| | | | | | | | | 
| **`ExplanationOfBenefit.created`**| _Equivalent_<br/>(5247/5248)| `ExplanationOfBenefit.created`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14052)<hr/>←←←← _Equivalent_ ←←←← <br/>(14053)| `ExplanationOfBenefit.created`| _Equivalent_<br/>(26939/26940)| `ExplanationOfBenefit.created`| _Equivalent_<br/>(41946/41947)| `ExplanationOfBenefit.created`
| **`ExplanationOfBenefit.organization`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5249)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5250)| `ExplanationOfBenefit.organization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1072)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1516)| `ExplanationOfBenefit.provider`| _Equivalent_<br/>(26945/26946)| `ExplanationOfBenefit.provider`| →→→→ _Equivalent_ →→→→ <br/>(41952)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(41953)| `ExplanationOfBenefit.provider`
| **`ExplanationOfBenefit.requestProvider`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(235)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(621)| `ExplanationOfBenefit.provider`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14058)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14059)| `ExplanationOfBenefit.provider`| _Equivalent_<br/>(26945/26946)| `ExplanationOfBenefit.provider`| →→→→ _Equivalent_ →→→→ <br/>(41952)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(41953)| `ExplanationOfBenefit.provider`
| **`ExplanationOfBenefit.requestOrganization`**| | | | | | | | | 
| *19 of 19 elements used* | | *15 of 225 elements used* | | *14 of 256 elements used* | | *14 of 256 elements used* | | *14 of 316 elements used* 

