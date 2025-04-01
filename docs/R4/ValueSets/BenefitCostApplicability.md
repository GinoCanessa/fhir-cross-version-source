Comparison of 
Generated at Tuesday, April 1, 2025 1:39:17 PM

### BenefitCostApplicability

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | BenefitCostApplicability |
| Canonical URL | `http://hl7.org/fhir/ValueSet/insuranceplan-applicability` |
| Version | 4.0.1 |
| Description | Whether the cost applies to in-network or out-of-network providers. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `2519` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/InsurancePlan` | `InsurancePlan.plan.specificCost.benefit.cost.applicability` | `http://hl7.org/fhir/ValueSet/insuranceplan-applicability\|4.0.1` | `Required` | in-network \| out-of-network \| other |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/applicability`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [BenefitCostApplicability](/docs/R4/ValueSets/BenefitCostApplicability.md)<br/> `http://hl7.org/fhir/ValueSet/insuranceplan-applicability\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1549`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1550`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BenefitCostApplicability](/docs/R4B/ValueSets/BenefitCostApplicability.md)<br/> `http://hl7.org/fhir/ValueSet/insuranceplan-applicability\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `907`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1168`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BenefitCostApplicability](/docs/R5/ValueSets/BenefitCostApplicability.md)<br/> `http://hl7.org/fhir/ValueSet/insuranceplan-applicability\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set BenefitCostApplicability from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | R4 BenefitCostApplicability| Relationship | [R4B BenefitCostApplicability](/docs/R4B/ValueSets/BenefitCostApplicability.md)| Relationship | [R5 BenefitCostApplicability](/docs/R5/ValueSets/BenefitCostApplicability.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/applicability`
| | | | | **`in-network`**| _Equivalent_ <br/>(16228/16229)| `in-network`| _Equivalent_ <br/>(8726/11035)| `in-network`
| | | | | **`out-of-network`**| _Equivalent_ <br/>(16230/16231)| `out-of-network`| _Equivalent_ <br/>(8728/11037)| `out-of-network`
| | | | | **`other`**| _Equivalent_ <br/>(16232/16233)| `other`| _Equivalent_ <br/>(8727/11036)| `other`
| | | | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* 

