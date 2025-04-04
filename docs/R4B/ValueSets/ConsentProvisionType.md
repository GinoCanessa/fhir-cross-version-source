Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### ConsentProvisionType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ConsentProvisionType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/consent-provision-type` |
| Version | 4.3.0 |
| Description | How a rule statement is applied, such as adding additional consent or removing consent. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3641` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.provision.type` | `http://hl7.org/fhir/ValueSet/consent-provision-type\|4.3.0` | `Required` | deny \| permit |

### Referenced Systems

* `http://hl7.org/fhir/consent-provision-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ConsentExceptType](/docs/R3/ValueSets/ConsentExceptType.md)<br/> `http://hl7.org/fhir/ValueSet/consent-except-type\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `478`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `702`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ConsentProvisionType](/docs/R4/ValueSets/ConsentProvisionType.md)<br/> `http://hl7.org/fhir/ValueSet/consent-provision-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1445`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1446`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ConsentProvisionType](/docs/R4B/ValueSets/ConsentProvisionType.md)<br/> `http://hl7.org/fhir/ValueSet/consent-provision-type\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1803`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1804`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ConsentProvisionType](/docs/R5/ValueSets/ConsentProvisionType.md)<br/> `http://hl7.org/fhir/ValueSet/consent-provision-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ConsentProvisionType from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 ConsentExceptType](/docs/R3/ValueSets/ConsentExceptType.md)| Relationship | [R4 ConsentProvisionType](/docs/R4/ValueSets/ConsentProvisionType.md)| Relationship | R4B ConsentProvisionType| Relationship | [R5 ConsentProvisionType](/docs/R5/ValueSets/ConsentProvisionType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/consent-provision-type`
| | | `deny`| _Equivalent_ <br/>(4372/6737)| `deny`| _Equivalent_ <br/>(14798/14799)| **`deny`**| _Equivalent_ <br/>(18475/18476)| `deny`
| | | `permit`| _Equivalent_ <br/>(4373/6738)| `permit`| _Equivalent_ <br/>(14800/14801)| **`permit`**| _Equivalent_ <br/>(18477/18478)| `permit`
| | | *2 of 2 codes used* | | *2 of 2 codes used* | | *2 of 2 codes used* | | *2 of 2 codes used* 

