Comparison of 
Generated at Thursday, April 3, 2025 8:18:10 AM

### ObjectLifecycleEvents

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | ObjectLifecycleEvents |
| Canonical URL | `http://hl7.org/fhir/ValueSet/object-lifecycle-events` |
| Version | 1.1.0 |
| Description | This example FHIR value set is comprised of lifecycle event codes. The FHIR Actor value set is based on    DICOM Audit Message, ParticipantObjectDataLifeCycle;   ISO Standard, TS 21089-2017; |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1365` |
| Database Concept Count | `40` |
| Database Active Concept Count | `40` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.entity.lifecycle` | `http://hl7.org/fhir/ValueSet/object-lifecycle-events` | `Extensible` | Life-cycle stage for the entity |

### Referenced Systems

* `http://hl7.org/fhir/dicom-audit-lifecycle`
* `http://hl7.org/fhir/iso-21089-lifecycle`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AuditEventObjectLifecycle](/docs/R2/ValueSets/AuditEventObjectLifecycle.md)<br/> `http://hl7.org/fhir/ValueSet/object-lifecycle\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `138`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `296`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ObjectLifecycleEvents](/docs/R3/ValueSets/ObjectLifecycleEvents.md)<br/> `http://hl7.org/fhir/ValueSet/object-lifecycle-events\|1.1.0` | →→→→→→→<br/>``<br/>- DBKey: `499`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `720`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ObjectLifecycleEvents](/docs/R4/ValueSets/ObjectLifecycleEvents.md)<br/> `http://hl7.org/fhir/ValueSet/object-lifecycle-events\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set ObjectLifecycleEvents from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 AuditEventObjectLifecycle](/docs/R2/ValueSets/AuditEventObjectLifecycle.md)| Relationship | R3 ObjectLifecycleEvents| Relationship | [R4 ObjectLifecycleEvents](/docs/R4/ValueSets/ObjectLifecycleEvents.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/dicom-audit-lifecycle`
| `1`| _Equivalent_ <br/>(1195/2591)| **`1`**| _Equivalent_ <br/>(4675/7003)| `1`| | | | | 
| `1`| _Equivalent_ <br/>(1195/2591)| **`1`**| _Equivalent_ <br/>(4675/7003)| `1`| | | | | 
| `1`| _Equivalent_ <br/>(1195/2591)| **`1`**| _Equivalent_ <br/>(4675/7003)| `1`| | | | | 
| `1`| _Equivalent_ <br/>(1195/2591)| **`1`**| _Equivalent_ <br/>(4675/7003)| `1`| | | | | 
| `2`| _Equivalent_ <br/>(1191/2587)| **`2`**| _Equivalent_ <br/>(4676/6999)| `2`| | | | | 
| `2`| _Equivalent_ <br/>(1191/2587)| **`2`**| _Equivalent_ <br/>(4676/6999)| `2`| | | | | 
| `2`| _Equivalent_ <br/>(1191/2587)| **`2`**| _Equivalent_ <br/>(4676/6999)| `2`| | | | | 
| `2`| _Equivalent_ <br/>(1191/2587)| **`2`**| _Equivalent_ <br/>(4676/6999)| `2`| | | | | 
| `3`| _Equivalent_ <br/>(1187/2583)| **`3`**| _Equivalent_ <br/>(4671/6991)| `3`| | | | | 
| `3`| _Equivalent_ <br/>(1187/2583)| **`3`**| _Equivalent_ <br/>(4671/6991)| `3`| | | | | 
| `3`| _Equivalent_ <br/>(1187/2583)| **`3`**| _Equivalent_ <br/>(4671/6991)| `3`| | | | | 
| `3`| _Equivalent_ <br/>(1187/2583)| **`3`**| _Equivalent_ <br/>(4671/6991)| `3`| | | | | 
| `3`| _Equivalent_ <br/>(1187/2583)| **`3`**| _Equivalent_ <br/>(4671/6991)| `3`| | | | | 
| `3`| _Equivalent_ <br/>(1187/2583)| **`3`**| _Equivalent_ <br/>(4671/6991)| `3`| | | | | 
| `4`| _Equivalent_ <br/>(1193/2589)| **`4`**| _Equivalent_ <br/>(4669/6992)| `4`| | | | | 
| `4`| _Equivalent_ <br/>(1193/2589)| **`4`**| _Equivalent_ <br/>(4669/6992)| `4`| | | | | 
| `4`| _Equivalent_ <br/>(1193/2589)| **`4`**| _Equivalent_ <br/>(4669/6992)| `4`| | | | | 
| `4`| _Equivalent_ <br/>(1193/2589)| **`4`**| _Equivalent_ <br/>(4669/6992)| `4`| | | | | 
| `5`| _Equivalent_ <br/>(1182/2578)| **`5`**| _Equivalent_ <br/>(4668/6995)| `5`| | | | | 
| `5`| _Equivalent_ <br/>(1182/2578)| **`5`**| _Equivalent_ <br/>(4668/6995)| `5`| | | | | 
| `5`| _Equivalent_ <br/>(1182/2578)| **`5`**| _Equivalent_ <br/>(4668/6995)| `5`| | | | | 
| `5`| _Equivalent_ <br/>(1182/2578)| **`5`**| _Equivalent_ <br/>(4668/6995)| `5`| | | | | 
| `5`| _Equivalent_ <br/>(1182/2578)| **`5`**| _Equivalent_ <br/>(4668/6995)| `5`| | | | | 
| `5`| _Equivalent_ <br/>(1182/2578)| **`5`**| _Equivalent_ <br/>(4668/6995)| `5`| | | | | 
| `6`| _Equivalent_ <br/>(1185/2581)| **`6`**| _Equivalent_ <br/>(4679/7002)| `6`| | | | | 
| `6`| _Equivalent_ <br/>(1185/2581)| **`6`**| _Equivalent_ <br/>(4679/7002)| `6`| | | | | 
| `6`| _Equivalent_ <br/>(1185/2581)| **`6`**| _Equivalent_ <br/>(4679/7002)| `6`| | | | | 
| `6`| _Equivalent_ <br/>(1185/2581)| **`6`**| _Equivalent_ <br/>(4679/7002)| `6`| | | | | 
| `6`| _Equivalent_ <br/>(1185/2581)| **`6`**| _Equivalent_ <br/>(4679/7002)| `6`| | | | | 
| `6`| _Equivalent_ <br/>(1185/2581)| **`6`**| _Equivalent_ <br/>(4679/7002)| `6`| | | | | 
| `7`| _Equivalent_ <br/>(1180/2576)| **`7`**| _Equivalent_ <br/>(4670/6998)| `7`| | | | | 
| `7`| _Equivalent_ <br/>(1180/2576)| **`7`**| _Equivalent_ <br/>(4670/6998)| `7`| | | | | 
| `7`| _Equivalent_ <br/>(1180/2576)| **`7`**| _Equivalent_ <br/>(4670/6998)| `7`| | | | | 
| `7`| _Equivalent_ <br/>(1180/2576)| **`7`**| _Equivalent_ <br/>(4670/6998)| `7`| | | | | 
| `8`| _Equivalent_ <br/>(1178/2574)| **`8`**| _Equivalent_ <br/>(4680/6989)| `8`| | | | | 
| `8`| _Equivalent_ <br/>(1178/2574)| **`8`**| _Equivalent_ <br/>(4680/6989)| `8`| | | | | 
| `8`| _Equivalent_ <br/>(1178/2574)| **`8`**| _Equivalent_ <br/>(4680/6989)| `8`| | | | | 
| `8`| _Equivalent_ <br/>(1178/2574)| **`8`**| _Equivalent_ <br/>(4680/6989)| `8`| | | | | 
| `9`| _Equivalent_ <br/>(1179/2575)| **`9`**| _Equivalent_ <br/>(4674/6990)| `9`| | | | | 
| `9`| _Equivalent_ <br/>(1179/2575)| **`9`**| _Equivalent_ <br/>(4674/6990)| `9`| | | | | 
| `9`| _Equivalent_ <br/>(1179/2575)| **`9`**| _Equivalent_ <br/>(4674/6990)| `9`| | | | | 
| `9`| _Equivalent_ <br/>(1179/2575)| **`9`**| _Equivalent_ <br/>(4674/6990)| `9`| | | | | 
| `10`| _Equivalent_ <br/>(1192/2588)| **`10`**| _Equivalent_ <br/>(4678/6994)| `10`| | | | | 
| `10`| _Equivalent_ <br/>(1192/2588)| **`10`**| _Equivalent_ <br/>(4678/6994)| `10`| | | | | 
| `10`| _Equivalent_ <br/>(1192/2588)| **`10`**| _Equivalent_ <br/>(4678/6994)| `10`| | | | | 
| `10`| _Equivalent_ <br/>(1192/2588)| **`10`**| _Equivalent_ <br/>(4678/6994)| `10`| | | | | 
| `11`| _Equivalent_ <br/>(1194/2590)| **`11`**| _Equivalent_ <br/>(4677/6997)| `11`| | | | | 
| `11`| _Equivalent_ <br/>(1194/2590)| **`11`**| _Equivalent_ <br/>(4677/6997)| `11`| | | | | 
| `11`| _Equivalent_ <br/>(1194/2590)| **`11`**| _Equivalent_ <br/>(4677/6997)| `11`| | | | | 
| `11`| _Equivalent_ <br/>(1194/2590)| **`11`**| _Equivalent_ <br/>(4677/6997)| `11`| | | | | 
| `12`| _Equivalent_ <br/>(1189/2585)| **`12`**| _Equivalent_ <br/>(4682/7001)| `12`| | | | | 
| `12`| _Equivalent_ <br/>(1189/2585)| **`12`**| _Equivalent_ <br/>(4682/7001)| `12`| | | | | 
| `12`| _Equivalent_ <br/>(1189/2585)| **`12`**| _Equivalent_ <br/>(4682/7001)| `12`| | | | | 
| `12`| _Equivalent_ <br/>(1189/2585)| **`12`**| _Equivalent_ <br/>(4682/7001)| `12`| | | | | 
| `12`| _Equivalent_ <br/>(1189/2585)| **`12`**| _Equivalent_ <br/>(4682/7001)| `12`| | | | | 
| `12`| _Equivalent_ <br/>(1189/2585)| **`12`**| _Equivalent_ <br/>(4682/7001)| `12`| | | | | 
| `13`| _Equivalent_ <br/>(1177/2573)| **`13`**| _Equivalent_ <br/>(4681/6993)| `13`| | | | | 
| `13`| _Equivalent_ <br/>(1177/2573)| **`13`**| _Equivalent_ <br/>(4681/6993)| `13`| | | | | 
| `13`| _Equivalent_ <br/>(1177/2573)| **`13`**| _Equivalent_ <br/>(4681/6993)| `13`| | | | | 
| `13`| _Equivalent_ <br/>(1177/2573)| **`13`**| _Equivalent_ <br/>(4681/6993)| `13`| | | | | 
| `13`| _Equivalent_ <br/>(1177/2573)| **`13`**| _Equivalent_ <br/>(4681/6993)| `13`| | | | | 
| `13`| _Equivalent_ <br/>(1177/2573)| **`13`**| _Equivalent_ <br/>(4681/6993)| `13`| | | | | 
| `14`| _Equivalent_ <br/>(1190/2586)| **`14`**| _Equivalent_ <br/>(4673/6996)| `14`| | | | | 
| `14`| _Equivalent_ <br/>(1190/2586)| **`14`**| _Equivalent_ <br/>(4673/6996)| `14`| | | | | 
| `14`| _Equivalent_ <br/>(1190/2586)| **`14`**| _Equivalent_ <br/>(4673/6996)| `14`| | | | | 
| `14`| _Equivalent_ <br/>(1190/2586)| **`14`**| _Equivalent_ <br/>(4673/6996)| `14`| | | | | 
| `15`| _Equivalent_ <br/>(1183/2579)| **`15`**| _Equivalent_ <br/>(4672/7000)| `15`| | | | | 
| `15`| _Equivalent_ <br/>(1183/2579)| **`15`**| _Equivalent_ <br/>(4672/7000)| `15`| | | | | 
| `15`| _Equivalent_ <br/>(1183/2579)| **`15`**| _Equivalent_ <br/>(4672/7000)| `15`| | | | | 
| `15`| _Equivalent_ <br/>(1183/2579)| **`15`**| _Equivalent_ <br/>(4672/7000)| `15`| | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/iso-21089-lifecycle`
| `2`| _Equivalent_ <br/>(1196/2592)| **`2`**| _Equivalent_ <br/>(4645/6934)| `2`| | | | | 
| `14`| _Equivalent_ <br/>(1197/2593)| **`14`**| _Equivalent_ <br/>(4654/6943)| `14`| | | | | 
| `4`| _Equivalent_ <br/>(1199/2595)| **`4`**| _Equivalent_ <br/>(4651/6940)| `4`| | | | | 
| `4`| _Equivalent_ <br/>(1199/2595)| **`4`**| _Equivalent_ <br/>(4651/6940)| `4`| | | | | 
| | | **`27`**| | | | | | | 
| `10`| _Equivalent_ <br/>(1205/2601)| **`10`**| _Equivalent_ <br/>(4649/6938)| `10`| | | | | 
| `10`| _Equivalent_ <br/>(1205/2601)| **`10`**| _Equivalent_ <br/>(4649/6938)| `10`| | | | | 
| | | **`17`**| | | | | | | 
| | | **`16`**| | | | | | | 
| `7`| _Equivalent_ <br/>(1208/2604)| **`7`**| _Equivalent_ <br/>(4656/6945)| `7`| | | | | 
| | | **`26`**| | | | | | | 
| `13`| _Equivalent_ <br/>(1213/2609)| **`13`**| _Equivalent_ <br/>(4648/6937)| `13`| | | | | 
| | | **`21`**| | | | | | | 
| | | **`19`**| | | | | | | 
| `1`| _Equivalent_ <br/>(1203/2599)| **`1`**| _Equivalent_ <br/>(4653/6942)| `1`| | | | | 
| `1`| _Equivalent_ <br/>(1203/2599)| **`1`**| _Equivalent_ <br/>(4653/6942)| `1`| | | | | 
| `11`| _Equivalent_ <br/>(1201/2597)| **`11`**| _Equivalent_ <br/>(4646/6935)| `11`| | | | | 
| `11`| _Equivalent_ <br/>(1201/2597)| **`11`**| _Equivalent_ <br/>(4646/6935)| `11`| | | | | 
| | | **`18`**| | | | | | | 
| `9`| _Equivalent_ <br/>(1209/2605)| **`9`**| _Equivalent_ <br/>(4650/6939)| `9`| | | | | 
| `6`| _Equivalent_ <br/>(1210/2606)| **`6`**| _Equivalent_ <br/>(4644/6933)| `6`| | | | | 
| `12`| _Equivalent_ <br/>(1212/2608)| **`12`**| _Equivalent_ <br/>(4643/6932)| `12`| | | | | 
| | | **`24`**| | | | | | | 
| `15`| _Equivalent_ <br/>(1207/2603)| **`15`**| _Equivalent_ <br/>(4655/6944)| `15`| | | | | 
| `3`| _Equivalent_ <br/>(1211/2607)| **`3`**| _Equivalent_ <br/>(4652/6941)| `3`| | | | | 
| `8`| _Equivalent_ <br/>(1206/2602)| **`8`**| _Equivalent_ <br/>(4647/6936)| `8`| | | | | 
| | | **`22`**| | | | | | | 
| | | **`20`**| | | | | | | 
| | | **`25`**| | | | | | | 
| *15 of 15 codes used* | | *40 of 40 codes used* | | *15 of 42 codes used* <br/>remaining codes:<br/>`access`, `amend`, `archive`, `attest`, `decrypt`, `deidentify`, `deprecate`, `destroy`, `disclose`, `encrypt`, `extract`, `hold`, `link`, `merge`, `originate`, `pseudonymize`, `reactivate`, `receive`, `reidentify`, `report`, `restore`, `transform`, `transmit`, `unhold`, `unlink`, `unmerge`, `verify`| | | | 

