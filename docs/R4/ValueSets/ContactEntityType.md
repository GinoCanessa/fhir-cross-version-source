Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### ContactEntityType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ContactEntityType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/contactentity-type` |
| Version | 4.0.1 |
| Description | This example value set defines a set of codes that can be used to indicate the purpose for which you would contact a contact party. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2318` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/InsurancePlan` | `InsurancePlan.contact.purpose` | `http://hl7.org/fhir/ValueSet/contactentity-type` | `Extensible` | The type of contact |
| `http://hl7.org/fhir/StructureDefinition/Organization` | `Organization.contact.purpose` | `http://hl7.org/fhir/ValueSet/contactentity-type` | `Extensible` | The type of contact |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/contactentity-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ContactEntityType](/docs/R2/ValueSets/ContactEntityType.md)<br/> `http://hl7.org/fhir/ValueSet/contactentity-type\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `113`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `269`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ContactEntityType](/docs/R3/ValueSets/ContactEntityType.md)<br/> `http://hl7.org/fhir/ValueSet/contactentity-type\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `462`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `686`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ContactEntityType](/docs/R4/ValueSets/ContactEntityType.md)<br/> `http://hl7.org/fhir/ValueSet/contactentity-type\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set ContactEntityType from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ContactEntityType](/docs/R2/ValueSets/ContactEntityType.md)| Relationship | [R3 ContactEntityType](/docs/R3/ValueSets/ContactEntityType.md)| Relationship | R4 ContactEntityType| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/contactentity-type`
| `BILL`| _Equivalent_ <br/>(946/2314)| `BILL`| _Equivalent_ <br/>(4119/6465)| **`BILL`**| | | | | 
| `ADMIN`| _Equivalent_ <br/>(948/2316)| `ADMIN`| _Equivalent_ <br/>(4121/6467)| **`ADMIN`**| | | | | 
| `HR`| _Equivalent_ <br/>(947/2315)| `HR`| _Equivalent_ <br/>(4120/6466)| **`HR`**| | | | | 
| `PAYOR`| _Equivalent_ <br/>(949/2317)| `PAYOR`| _Equivalent_ <br/>(4122/6468)| **`PAYOR`**| | | | | 
| `PATINF`| _Equivalent_ <br/>(945/2313)| `PATINF`| _Equivalent_ <br/>(4118/6464)| **`PATINF`**| | | | | 
| `PRESS`| _Equivalent_ <br/>(950/2318)| `PRESS`| _Equivalent_ <br/>(4123/6469)| **`PRESS`**| | | | | 
| *6 of 6 codes used* | | *6 of 6 codes used* | | *6 of 6 codes used* | | | | 

