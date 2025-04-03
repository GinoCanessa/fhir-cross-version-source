Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### v3.PurposeOfUse

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | v3.PurposeOfUse |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` |
| Version | 2014-03-26 |
| Description | Supports communication of purpose of use at a general level. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `3430` |
| Database Concept Count | `60` |
| Database Active Concept Count | `60` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.purposeOfEvent` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` | `Extensible` | The purposeOfUse of the event |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.agent.purposeOfUse` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` | `Extensible` | Reason given for this user |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.provision.purpose` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` | `Extensible` | Context of activities covered by this rule |
| `http://hl7.org/fhir/StructureDefinition/Contract` | `Contract.term.action.intent` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` | `Example` | Purpose for the Contract Term Action |
| `http://hl7.org/fhir/StructureDefinition/Contract` | `Contract.term.action.reasonCode` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` | `Example` | Why is action (not) needed? |
| `http://hl7.org/fhir/StructureDefinition/Provenance` | `Provenance.reason` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` | `Extensible` | Reason the activity is occurring |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActReason`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [PurposeOfUse](/docs/R2/ValueSets/PurposeOfUse.md)<br/> `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse\|2014-03-26` | →→→→→→→<br/>``<br/>- DBKey: `123`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `281`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PurposeOfUse](/docs/R3/ValueSets/PurposeOfUse.md)<br/> `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse\|2014-03-26` | →→→→→→→<br/>``<br/>- DBKey: `477`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `701`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [v3.PurposeOfUse](/docs/R4/ValueSets/V3PurposeOfUse.md)<br/> `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse\|2014-03-26` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set v3.PurposeOfUse from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 PurposeOfUse](/docs/R2/ValueSets/PurposeOfUse.md)| Relationship | [R3 PurposeOfUse](/docs/R3/ValueSets/PurposeOfUse.md)| Relationship | R4 v3.PurposeOfUse| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v3-ActReason`
| `PurposeOfUse`| _Equivalent_ <br/>(1022/2435)| `PurposeOfUse`| _Equivalent_ <br/>(4336/6728)| **`PurposeOfUse`**| | | | | 
| `HMARKT`| _Equivalent_ <br/>(1033/2446)| `HMARKT`| _Equivalent_ <br/>(4347/6705)| **`HMARKT`**| | | | | 
| `HOPERAT`| _Equivalent_ <br/>(1045/2458)| `HOPERAT`| _Equivalent_ <br/>(4359/6706)| **`HOPERAT`**| | | | | 
| `CAREMGT`| _Equivalent_ <br/>(1026/2439)| `CAREMGT`| _Equivalent_ <br/>(4340/6679)| **`CAREMGT`**| | | | | 
| `DONAT`| _Equivalent_ <br/>(1049/2462)| `DONAT`| _Equivalent_ <br/>(4363/6689)| **`DONAT`**| | | | | 
| `FRAUD`| _Equivalent_ <br/>(1018/2431)| `FRAUD`| _Equivalent_ <br/>(4332/6697)| **`FRAUD`**| | | | | 
| `GOV`| _Equivalent_ <br/>(1024/2437)| `GOV`| _Equivalent_ <br/>(4338/6698)| **`GOV`**| | | | | 
| `HACCRED`| _Equivalent_ <br/>(1055/2468)| `HACCRED`| _Equivalent_ <br/>(4369/6699)| **`HACCRED`**| | | | | 
| `HCOMPL`| _Equivalent_ <br/>(1047/2460)| `HCOMPL`| _Equivalent_ <br/>(4361/6700)| **`HCOMPL`**| | | | | 
| `HDECD`| _Equivalent_ <br/>(1037/2450)| `HDECD`| _Equivalent_ <br/>(4351/6701)| **`HDECD`**| | | | | 
| `HDIRECT`| _Equivalent_ <br/>(1032/2445)| `HDIRECT`| _Equivalent_ <br/>(4346/6702)| **`HDIRECT`**| | | | | 
| | | | | **`HDM`**| | | | | 
| `HLEGAL`| _Equivalent_ <br/>(1025/2438)| `HLEGAL`| _Equivalent_ <br/>(4339/6704)| **`HLEGAL`**| | | | | 
| `HOUTCOMS`| _Equivalent_ <br/>(1056/2469)| `HOUTCOMS`| _Equivalent_ <br/>(4370/6707)| **`HOUTCOMS`**| | | | | 
| `HPRGRP`| _Equivalent_ <br/>(1042/2455)| `HPRGRP`| _Equivalent_ <br/>(4356/6709)| **`HPRGRP`**| | | | | 
| `HQUALIMP`| _Equivalent_ <br/>(1019/2432)| `HQUALIMP`| _Equivalent_ <br/>(4333/6710)| **`HQUALIMP`**| | | | | 
| `HSYSADMIN`| _Equivalent_ <br/>(1021/2434)| `HSYSADMIN`| _Equivalent_ <br/>(4335/6712)| **`HSYSADMIN`**| | | | | 
| | | | | **`LABELING`**| | | | | 
| | | | | **`METAMGT`**| | | | | 
| `MEMADMIN`| _Equivalent_ <br/>(1050/2463)| `MEMADMIN`| _Equivalent_ <br/>(4364/6715)| **`MEMADMIN`**| | | | | 
| | | | | **`MILCDM`**| | | | | 
| `PATADMIN`| _Equivalent_ <br/>(1043/2456)| `PATADMIN`| _Equivalent_ <br/>(4357/6719)| **`PATADMIN`**| | | | | 
| `PATSFTY`| _Equivalent_ <br/>(1029/2442)| `PATSFTY`| _Equivalent_ <br/>(4343/6721)| **`PATSFTY`**| | | | | 
| `PERFMSR`| _Equivalent_ <br/>(1053/2466)| `PERFMSR`| _Equivalent_ <br/>(4367/6722)| **`PERFMSR`**| | | | | 
| `RECORDMGT`| _Equivalent_ <br/>(1044/2457)| `RECORDMGT`| _Equivalent_ <br/>(4358/6729)| **`RECORDMGT`**| | | | | 
| | | | | **`SYSDEV`**| | | | | 
| | | | | **`HTEST`**| | | | | 
| `TRAIN`| _Equivalent_ <br/>(1039/2452)| `TRAIN`| _Equivalent_ <br/>(4353/6734)| **`TRAIN`**| | | | | 
| `HPAYMT`| _Equivalent_ <br/>(1051/2464)| `HPAYMT`| _Equivalent_ <br/>(4365/6708)| **`HPAYMT`**| | | | | 
| `CLMATTCH`| _Equivalent_ <br/>(1041/2454)| `CLMATTCH`| _Equivalent_ <br/>(4355/6684)| **`CLMATTCH`**| | | | | 
| `COVAUTH`| _Equivalent_ <br/>(1057/2470)| `COVAUTH`| _Equivalent_ <br/>(4371/6686)| **`COVAUTH`**| | | | | 
| `COVERAGE`| _Equivalent_ <br/>(1020/2433)| `COVERAGE`| _Equivalent_ <br/>(4334/6687)| **`COVERAGE`**| | | | | 
| `ELIGDTRM`| _Equivalent_ <br/>(1036/2449)| `ELIGDTRM`| _Equivalent_ <br/>(4350/6691)| **`ELIGDTRM`**| | | | | 
| `ELIGVER`| _Equivalent_ <br/>(1028/2441)| `ELIGVER`| _Equivalent_ <br/>(4342/6692)| **`ELIGVER`**| | | | | 
| `ENROLLM`| _Equivalent_ <br/>(1054/2467)| `ENROLLM`| _Equivalent_ <br/>(4368/6693)| **`ENROLLM`**| | | | | 
| | | | | **`MILDCRG`**| | | | | 
| `REMITADV`| _Equivalent_ <br/>(1035/2448)| `REMITADV`| _Equivalent_ <br/>(4349/6730)| **`REMITADV`**| | | | | 
| `HRESCH`| _Equivalent_ <br/>(1016/2429)| `HRESCH`| _Equivalent_ <br/>(4330/6711)| **`HRESCH`**| | | | | 
| | | | | **`BIORCH`**| | | | | 
| `CLINTRCH`| _Equivalent_ <br/>(1038/2451)| `CLINTRCH`| _Equivalent_ <br/>(4352/6680)| **`CLINTRCH`**| | | | | 
| | | | | **`CLINTRCHNPC`**| | | | | 
| | | | | **`CLINTRCHPC`**| | | | | 
| | | | | **`PRECLINTRCH`**| | | | | 
| | | | | **`DSRCH`**| | | | | 
| | | | | **`POARCH`**| | | | | 
| | | | | **`TRANSRCH`**| | | | | 
| `PATRQT`| _Equivalent_ <br/>(1027/2440)| `PATRQT`| _Equivalent_ <br/>(4341/6720)| **`PATRQT`**| | | | | 
| `FAMRQT`| _Equivalent_ <br/>(1034/2447)| `FAMRQT`| _Equivalent_ <br/>(4348/6696)| **`FAMRQT`**| | | | | 
| `PWATRNY`| _Equivalent_ <br/>(1030/2443)| `PWATRNY`| _Equivalent_ <br/>(4344/6727)| **`PWATRNY`**| | | | | 
| `SUPNWK`| _Equivalent_ <br/>(1031/2444)| `SUPNWK`| _Equivalent_ <br/>(4345/6731)| **`SUPNWK`**| | | | | 
| `PUBHLTH`| _Equivalent_ <br/>(1015/2428)| `PUBHLTH`| _Equivalent_ <br/>(4329/6726)| **`PUBHLTH`**| | | | | 
| `DISASTER`| _Equivalent_ <br/>(1017/2430)| `DISASTER`| _Equivalent_ <br/>(4331/6688)| **`DISASTER`**| | | | | 
| `THREAT`| _Equivalent_ <br/>(1048/2461)| `THREAT`| _Equivalent_ <br/>(4362/6733)| **`THREAT`**| | | | | 
| `TREAT`| _Equivalent_ <br/>(1040/2453)| `TREAT`| _Equivalent_ <br/>(4354/6736)| **`TREAT`**| | | | | 
| `CLINTRL`| _Equivalent_ <br/>(1052/2465)| `CLINTRL`| _Equivalent_ <br/>(4366/6683)| **`CLINTRL`**| | | | | 
| | | | | **`COC`**| | | | | 
| `ETREAT`| _Equivalent_ <br/>(1023/2436)| `ETREAT`| _Equivalent_ <br/>(4337/6695)| **`ETREAT`**| | | | | 
| | | | | **`BTG`**| | | | | 
| | | | | **`ERTREAT`**| | | | | 
| `POPHLTH`| _Equivalent_ <br/>(1046/2459)| `POPHLTH`| _Equivalent_ <br/>(4360/6724)| **`POPHLTH`**| | | | | 
| *43 of 43 codes used* | | *43 of 43 codes used* | | *60 of 60 codes used* | | | | 

