Comparison of 
Generated at Friday, April 4, 2025 2:58:36 PM

### PayeeResourceType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | PayeeResourceType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/resource-type-link` |
| Version | 3.0.2 |
| Description | The type of payee Resource |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1452` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.payee.resourceType` | `http://hl7.org/fhir/ValueSet/resource-type-link` | `Required` | organization \| patient \| practitioner \| relatedperson |

### Referenced Systems

* `http://hl7.org/fhir/resource-type-link`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [PayeeResourceType](/docs/R3/ValueSets/PayeeResourceType.md)<br/> `http://hl7.org/fhir/ValueSet/resource-type-link\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `1327`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1328`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PayeeResourceType](/docs/R4/ValueSets/PayeeResourceType.md)<br/> `http://hl7.org/fhir/ValueSet/resource-type-link\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set PayeeResourceType from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | R3 PayeeResourceType| Relationship | [R4 PayeeResourceType](/docs/R4/ValueSets/PayeeResourceType.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/resource-type-link`
| | | **`organization`**| _Equivalent_ <br/>(13551/13552)| `organization`| | | | | 
| | | **`patient`**| _Equivalent_ <br/>(13553/13554)| `patient`| | | | | 
| | | **`practitioner`**| _Equivalent_ <br/>(13555/13556)| `practitioner`| | | | | 
| | | **`relatedperson`**| _Equivalent_ <br/>(13557/13558)| `relatedperson`| | | | | 
| | | *4 of 4 codes used* | | *4 of 4 codes used* | | | | 

