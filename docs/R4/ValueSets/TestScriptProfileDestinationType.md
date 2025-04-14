Comparison of 
Generated at Monday, April 14, 2025 6:17:28 PM

### TestScriptProfileDestinationType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | TestScriptProfileDestinationType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/testscript-profile-destination-types` |
| Version | 4.0.1 |
| Description | This value set defines a set of codes that are used to indicate the profile type of a test system when acting as the destination within a TestScript. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2802` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.destination.profile` | `http://hl7.org/fhir/ValueSet/testscript-profile-destination-types` | `Extensible` | FHIR-Server \| FHIR-SDC-FormManager \| FHIR-SDC-FormReceiver \| FHIR-SDC-FormProcessor |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/testscript-profile-destination-types`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [TestScriptProfileDestinationType](/docs/R3/ValueSets/TestScriptProfileDestinationType.md)<br/> `http://hl7.org/fhir/ValueSet/testscript-profile-destination-types\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `531`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `753`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [TestScriptProfileDestinationType](/docs/R4/ValueSets/TestScriptProfileDestinationType.md)<br/> `http://hl7.org/fhir/ValueSet/testscript-profile-destination-types\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set TestScriptProfileDestinationType from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 TestScriptProfileDestinationType](/docs/R3/ValueSets/TestScriptProfileDestinationType.md)| Relationship | R4 TestScriptProfileDestinationType| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/testscript-profile-destination-types`
| | | `FHIR-Server`| _Equivalent_ <br/>(4953/7297)| **`FHIR-Server`**| | | | | 
| | | `FHIR-SDC-FormManager`| _Equivalent_ <br/>(4956/7300)| **`FHIR-SDC-FormManager`**| | | | | 
| | | `FHIR-SDC-FormProcessor`| _Equivalent_ <br/>(4955/7299)| **`FHIR-SDC-FormProcessor`**| | | | | 
| | | `FHIR-SDC-FormReceiver`| _Equivalent_ <br/>(4954/7298)| **`FHIR-SDC-FormReceiver`**| | | | | 
| | | *4 of 4 codes used* | | *4 of 4 codes used* | | | | 

