Comparison of 
Generated at Tuesday, April 1, 2025 1:39:10 PM

### PurposeOfUse

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | PurposeOfUse |
| Canonical URL | `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse` |
| Version | 2014-03-26 |
| Description | Supports communication of purpose of use at a general level. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `2107` |
| Database Concept Count | `43` |
| Database Active Concept Count | `43` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.purposeOfEvent` | `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse` | `Extensible` | The purposeOfUse of the event |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.agent.purposeOfUse` | `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse` | `Extensible` | Reason given for this user |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.purpose` | `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse` | `Extensible` | Context of activities for which the agreement is made |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.except.purpose` | `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse` | `Extensible` | Context of activities covered by this exception |
| `http://hl7.org/fhir/StructureDefinition/Contract` | `Contract.actionReason` | `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse` | `Example` | Rationale for the stiplulated action |
| `http://hl7.org/fhir/StructureDefinition/Contract` | `Contract.term.actionReason` | `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse` | `Example` | Purpose for the Contract Term Action |
| `http://hl7.org/fhir/StructureDefinition/Provenance` | `Provenance.reason` | `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse` | `Extensible` | Reason the activity is occurring |

### Referenced Systems

* `http://hl7.org/fhir/v3/ActReason`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [PurposeOfUse](/docs/R2/ValueSets/PurposeOfUse.md)<br/> `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse\|2014-03-26` | →→→→→→→<br/>``<br/>- DBKey: `123`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `281`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PurposeOfUse](/docs/R3/ValueSets/PurposeOfUse.md)<br/> `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse\|2014-03-26` | →→→→→→→<br/>``<br/>- DBKey: `477`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `701`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [v3.PurposeOfUse](/docs/R4/ValueSets/V3PurposeOfUse.md)<br/> `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse\|2014-03-26` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set PurposeOfUse from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 PurposeOfUse](/docs/R2/ValueSets/PurposeOfUse.md)| Relationship | R3 PurposeOfUse| Relationship | [R4 v3.PurposeOfUse](/docs/R4/ValueSets/V3PurposeOfUse.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/ActReason`
| `PurposeOfUse`| _Equivalent_ <br/>(1022/2435)| **`PurposeOfUse`**| _Equivalent_ <br/>(4336/6728)| `PurposeOfUse`| | | | | 
| `HMARKT`| _Equivalent_ <br/>(1033/2446)| **`HMARKT`**| _Equivalent_ <br/>(4347/6705)| `HMARKT`| | | | | 
| `HOPERAT`| _Equivalent_ <br/>(1045/2458)| **`HOPERAT`**| _Equivalent_ <br/>(4359/6706)| `HOPERAT`| | | | | 
| `DONAT`| _Equivalent_ <br/>(1049/2462)| **`DONAT`**| _Equivalent_ <br/>(4363/6689)| `DONAT`| | | | | 
| `FRAUD`| _Equivalent_ <br/>(1018/2431)| **`FRAUD`**| _Equivalent_ <br/>(4332/6697)| `FRAUD`| | | | | 
| `GOV`| _Equivalent_ <br/>(1024/2437)| **`GOV`**| _Equivalent_ <br/>(4338/6698)| `GOV`| | | | | 
| `HACCRED`| _Equivalent_ <br/>(1055/2468)| **`HACCRED`**| _Equivalent_ <br/>(4369/6699)| `HACCRED`| | | | | 
| `HCOMPL`| _Equivalent_ <br/>(1047/2460)| **`HCOMPL`**| _Equivalent_ <br/>(4361/6700)| `HCOMPL`| | | | | 
| `HDECD`| _Equivalent_ <br/>(1037/2450)| **`HDECD`**| _Equivalent_ <br/>(4351/6701)| `HDECD`| | | | | 
| `HDIRECT`| _Equivalent_ <br/>(1032/2445)| **`HDIRECT`**| _Equivalent_ <br/>(4346/6702)| `HDIRECT`| | | | | 
| `HLEGAL`| _Equivalent_ <br/>(1025/2438)| **`HLEGAL`**| _Equivalent_ <br/>(4339/6704)| `HLEGAL`| | | | | 
| `HOUTCOMS`| _Equivalent_ <br/>(1056/2469)| **`HOUTCOMS`**| _Equivalent_ <br/>(4370/6707)| `HOUTCOMS`| | | | | 
| `HPRGRP`| _Equivalent_ <br/>(1042/2455)| **`HPRGRP`**| _Equivalent_ <br/>(4356/6709)| `HPRGRP`| | | | | 
| `HQUALIMP`| _Equivalent_ <br/>(1019/2432)| **`HQUALIMP`**| _Equivalent_ <br/>(4333/6710)| `HQUALIMP`| | | | | 
| `HSYSADMIN`| _Equivalent_ <br/>(1021/2434)| **`HSYSADMIN`**| _Equivalent_ <br/>(4335/6712)| `HSYSADMIN`| | | | | 
| `MEMADMIN`| _Equivalent_ <br/>(1050/2463)| **`MEMADMIN`**| _Equivalent_ <br/>(4364/6715)| `MEMADMIN`| | | | | 
| `PATADMIN`| _Equivalent_ <br/>(1043/2456)| **`PATADMIN`**| _Equivalent_ <br/>(4357/6719)| `PATADMIN`| | | | | 
| `PATSFTY`| _Equivalent_ <br/>(1029/2442)| **`PATSFTY`**| _Equivalent_ <br/>(4343/6721)| `PATSFTY`| | | | | 
| `PERFMSR`| _Equivalent_ <br/>(1053/2466)| **`PERFMSR`**| _Equivalent_ <br/>(4367/6722)| `PERFMSR`| | | | | 
| `RECORDMGT`| _Equivalent_ <br/>(1044/2457)| **`RECORDMGT`**| _Equivalent_ <br/>(4358/6729)| `RECORDMGT`| | | | | 
| `TRAIN`| _Equivalent_ <br/>(1039/2452)| **`TRAIN`**| _Equivalent_ <br/>(4353/6734)| `TRAIN`| | | | | 
| `HPAYMT`| _Equivalent_ <br/>(1051/2464)| **`HPAYMT`**| _Equivalent_ <br/>(4365/6708)| `HPAYMT`| | | | | 
| `CLMATTCH`| _Equivalent_ <br/>(1041/2454)| **`CLMATTCH`**| _Equivalent_ <br/>(4355/6684)| `CLMATTCH`| | | | | 
| `COVAUTH`| _Equivalent_ <br/>(1057/2470)| **`COVAUTH`**| _Equivalent_ <br/>(4371/6686)| `COVAUTH`| | | | | 
| `COVERAGE`| _Equivalent_ <br/>(1020/2433)| **`COVERAGE`**| _Equivalent_ <br/>(4334/6687)| `COVERAGE`| | | | | 
| `ELIGDTRM`| _Equivalent_ <br/>(1036/2449)| **`ELIGDTRM`**| _Equivalent_ <br/>(4350/6691)| `ELIGDTRM`| | | | | 
| `ELIGVER`| _Equivalent_ <br/>(1028/2441)| **`ELIGVER`**| _Equivalent_ <br/>(4342/6692)| `ELIGVER`| | | | | 
| `ENROLLM`| _Equivalent_ <br/>(1054/2467)| **`ENROLLM`**| _Equivalent_ <br/>(4368/6693)| `ENROLLM`| | | | | 
| `REMITADV`| _Equivalent_ <br/>(1035/2448)| **`REMITADV`**| _Equivalent_ <br/>(4349/6730)| `REMITADV`| | | | | 
| `HRESCH`| _Equivalent_ <br/>(1016/2429)| **`HRESCH`**| _Equivalent_ <br/>(4330/6711)| `HRESCH`| | | | | 
| `CLINTRCH`| _Equivalent_ <br/>(1038/2451)| **`CLINTRCH`**| _Equivalent_ <br/>(4352/6680)| `CLINTRCH`| | | | | 
| `PATRQT`| _Equivalent_ <br/>(1027/2440)| **`PATRQT`**| _Equivalent_ <br/>(4341/6720)| `PATRQT`| | | | | 
| `FAMRQT`| _Equivalent_ <br/>(1034/2447)| **`FAMRQT`**| _Equivalent_ <br/>(4348/6696)| `FAMRQT`| | | | | 
| `PWATRNY`| _Equivalent_ <br/>(1030/2443)| **`PWATRNY`**| _Equivalent_ <br/>(4344/6727)| `PWATRNY`| | | | | 
| `SUPNWK`| _Equivalent_ <br/>(1031/2444)| **`SUPNWK`**| _Equivalent_ <br/>(4345/6731)| `SUPNWK`| | | | | 
| `PUBHLTH`| _Equivalent_ <br/>(1015/2428)| **`PUBHLTH`**| _Equivalent_ <br/>(4329/6726)| `PUBHLTH`| | | | | 
| `DISASTER`| _Equivalent_ <br/>(1017/2430)| **`DISASTER`**| _Equivalent_ <br/>(4331/6688)| `DISASTER`| | | | | 
| `THREAT`| _Equivalent_ <br/>(1048/2461)| **`THREAT`**| _Equivalent_ <br/>(4362/6733)| `THREAT`| | | | | 
| `TREAT`| _Equivalent_ <br/>(1040/2453)| **`TREAT`**| _Equivalent_ <br/>(4354/6736)| `TREAT`| | | | | 
| `CAREMGT`| _Equivalent_ <br/>(1026/2439)| **`CAREMGT`**| _Equivalent_ <br/>(4340/6679)| `CAREMGT`| | | | | 
| `CLINTRL`| _Equivalent_ <br/>(1052/2465)| **`CLINTRL`**| _Equivalent_ <br/>(4366/6683)| `CLINTRL`| | | | | 
| `ETREAT`| _Equivalent_ <br/>(1023/2436)| **`ETREAT`**| _Equivalent_ <br/>(4337/6695)| `ETREAT`| | | | | 
| `POPHLTH`| _Equivalent_ <br/>(1046/2459)| **`POPHLTH`**| _Equivalent_ <br/>(4360/6724)| `POPHLTH`| | | | | 
| *43 of 43 codes used* | | *43 of 43 codes used* | | *43 of 60 codes used* | | | | 

