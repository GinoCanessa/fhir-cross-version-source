Comparison of 
Generated at Friday, April 4, 2025 2:58:44 PM

### ObjectLifecycleEvents

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ObjectLifecycleEvents |
| Canonical URL | `http://hl7.org/fhir/ValueSet/object-lifecycle-events` |
| Version | 4.0.1 |
| Description | This example FHIR value set is comprised of lifecycle event codes. The FHIR Actor value set is based on    DICOM Audit Message, ParticipantObjectDataLifeCycle;   ISO Standard, TS 21089-2017; |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2613` |
| Database Concept Count | `42` |
| Database Active Concept Count | `42` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.entity.lifecycle` | `http://hl7.org/fhir/ValueSet/object-lifecycle-events` | `Extensible` | Life-cycle stage for the entity |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle`
* `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AuditEventObjectLifecycle](/docs/R2/ValueSets/AuditEventObjectLifecycle.md)<br/> `http://hl7.org/fhir/ValueSet/object-lifecycle\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `138`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `296`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ObjectLifecycleEvents](/docs/R3/ValueSets/ObjectLifecycleEvents.md)<br/> `http://hl7.org/fhir/ValueSet/object-lifecycle-events\|1.1.0` | →→→→→→→<br/>``<br/>- DBKey: `499`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `720`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ObjectLifecycleEvents](/docs/R4/ValueSets/ObjectLifecycleEvents.md)<br/> `http://hl7.org/fhir/ValueSet/object-lifecycle-events\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set ObjectLifecycleEvents from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 AuditEventObjectLifecycle](/docs/R2/ValueSets/AuditEventObjectLifecycle.md)| Relationship | [R3 ObjectLifecycleEvents](/docs/R3/ValueSets/ObjectLifecycleEvents.md)| Relationship | R4 ObjectLifecycleEvents| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/dicom-audit-lifecycle`
| `1`| →→→→ _Equivalent_ →→→→ <br/>(1195)<hr/>←←←← __ ←←←← <br/>() | `1`| →→→→ _Equivalent_ →→→→ <br/>(4675)<hr/>←←←← __ ←←←← <br/>() | **`1`**| | | | | 
| `1`| →→→→ _Equivalent_ →→→→ <br/>(1195)<hr/>←←←← __ ←←←← <br/>() | `1`| →→→→ _Equivalent_ →→→→ <br/>(4675)<hr/>←←←← __ ←←←← <br/>() | **`1`**| | | | | 
| `1`| →→→→ _Equivalent_ →→→→ <br/>(1195)<hr/>←←←← __ ←←←← <br/>() | `1`| →→→→ _Equivalent_ →→→→ <br/>(4675)<hr/>←←←← __ ←←←← <br/>() | **`1`**| | | | | 
| `1`| →→→→ _Equivalent_ →→→→ <br/>(1195)<hr/>←←←← __ ←←←← <br/>() | `1`| →→→→ _Equivalent_ →→→→ <br/>(4675)<hr/>←←←← __ ←←←← <br/>() | **`1`**| | | | | 
| `1`| →→→→ _Equivalent_ →→→→ <br/>(1203)<hr/>←←←← __ ←←←← <br/>() | `1`| →→→→ _Equivalent_ →→→→ <br/>(4653)<hr/>←←←← __ ←←←← <br/>() | **`1`**| | | | | 
| `1`| →→→→ _Equivalent_ →→→→ <br/>(1203)<hr/>←←←← __ ←←←← <br/>() | `1`| →→→→ _Equivalent_ →→→→ <br/>(4653)<hr/>←←←← __ ←←←← <br/>() | **`1`**| | | | | 
| `2`| →→→→ _Equivalent_ →→→→ <br/>(1191)<hr/>←←←← __ ←←←← <br/>() | `2`| →→→→ _Equivalent_ →→→→ <br/>(4676)<hr/>←←←← __ ←←←← <br/>() | **`2`**| | | | | 
| `2`| →→→→ _Equivalent_ →→→→ <br/>(1191)<hr/>←←←← __ ←←←← <br/>() | `2`| →→→→ _Equivalent_ →→→→ <br/>(4676)<hr/>←←←← __ ←←←← <br/>() | **`2`**| | | | | 
| `2`| →→→→ _Equivalent_ →→→→ <br/>(1191)<hr/>←←←← __ ←←←← <br/>() | `2`| →→→→ _Equivalent_ →→→→ <br/>(4676)<hr/>←←←← __ ←←←← <br/>() | **`2`**| | | | | 
| `2`| →→→→ _Equivalent_ →→→→ <br/>(1191)<hr/>←←←← __ ←←←← <br/>() | `2`| →→→→ _Equivalent_ →→→→ <br/>(4676)<hr/>←←←← __ ←←←← <br/>() | **`2`**| | | | | 
| `2`| _Equivalent_ <br/>(1196/2592)| `2`| →→→→ _Equivalent_ →→→→ <br/>(4645)<hr/>←←←← __ ←←←← <br/>() | **`2`**| | | | | 
| `3`| →→→→ _Equivalent_ →→→→ <br/>(1187)<hr/>←←←← __ ←←←← <br/>() | `3`| →→→→ _Equivalent_ →→→→ <br/>(4671)<hr/>←←←← __ ←←←← <br/>() | **`3`**| | | | | 
| `3`| →→→→ _Equivalent_ →→→→ <br/>(1187)<hr/>←←←← __ ←←←← <br/>() | `3`| →→→→ _Equivalent_ →→→→ <br/>(4671)<hr/>←←←← __ ←←←← <br/>() | **`3`**| | | | | 
| `3`| →→→→ _Equivalent_ →→→→ <br/>(1187)<hr/>←←←← __ ←←←← <br/>() | `3`| →→→→ _Equivalent_ →→→→ <br/>(4671)<hr/>←←←← __ ←←←← <br/>() | **`3`**| | | | | 
| `3`| →→→→ _Equivalent_ →→→→ <br/>(1187)<hr/>←←←← __ ←←←← <br/>() | `3`| →→→→ _Equivalent_ →→→→ <br/>(4671)<hr/>←←←← __ ←←←← <br/>() | **`3`**| | | | | 
| `3`| →→→→ _Equivalent_ →→→→ <br/>(1187)<hr/>←←←← __ ←←←← <br/>() | `3`| →→→→ _Equivalent_ →→→→ <br/>(4671)<hr/>←←←← __ ←←←← <br/>() | **`3`**| | | | | 
| `3`| →→→→ _Equivalent_ →→→→ <br/>(1187)<hr/>←←←← __ ←←←← <br/>() | `3`| →→→→ _Equivalent_ →→→→ <br/>(4671)<hr/>←←←← __ ←←←← <br/>() | **`3`**| | | | | 
| `3`| _Equivalent_ <br/>(1211/2607)| `3`| →→→→ _Equivalent_ →→→→ <br/>(4652)<hr/>←←←← __ ←←←← <br/>() | **`3`**| | | | | 
| `4`| →→→→ _Equivalent_ →→→→ <br/>(1193)<hr/>←←←← __ ←←←← <br/>() | `4`| →→→→ _Equivalent_ →→→→ <br/>(4669)<hr/>←←←← __ ←←←← <br/>() | **`4`**| | | | | 
| `4`| →→→→ _Equivalent_ →→→→ <br/>(1193)<hr/>←←←← __ ←←←← <br/>() | `4`| →→→→ _Equivalent_ →→→→ <br/>(4669)<hr/>←←←← __ ←←←← <br/>() | **`4`**| | | | | 
| `4`| →→→→ _Equivalent_ →→→→ <br/>(1193)<hr/>←←←← __ ←←←← <br/>() | `4`| →→→→ _Equivalent_ →→→→ <br/>(4669)<hr/>←←←← __ ←←←← <br/>() | **`4`**| | | | | 
| `4`| →→→→ _Equivalent_ →→→→ <br/>(1193)<hr/>←←←← __ ←←←← <br/>() | `4`| →→→→ _Equivalent_ →→→→ <br/>(4669)<hr/>←←←← __ ←←←← <br/>() | **`4`**| | | | | 
| `4`| →→→→ _Equivalent_ →→→→ <br/>(1199)<hr/>←←←← __ ←←←← <br/>() | `4`| →→→→ _Equivalent_ →→→→ <br/>(4651)<hr/>←←←← __ ←←←← <br/>() | **`4`**| | | | | 
| `4`| →→→→ _Equivalent_ →→→→ <br/>(1199)<hr/>←←←← __ ←←←← <br/>() | `4`| →→→→ _Equivalent_ →→→→ <br/>(4651)<hr/>←←←← __ ←←←← <br/>() | **`4`**| | | | | 
| | | `active`| | **`5`**| | | | | 
| `5`| →→→→ _Equivalent_ →→→→ <br/>(1182)<hr/>←←←← __ ←←←← <br/>() | `5`| →→→→ _Equivalent_ →→→→ <br/>(4668)<hr/>←←←← __ ←←←← <br/>() | **`5`**| | | | | 
| `5`| →→→→ _Equivalent_ →→→→ <br/>(1182)<hr/>←←←← __ ←←←← <br/>() | `5`| →→→→ _Equivalent_ →→→→ <br/>(4668)<hr/>←←←← __ ←←←← <br/>() | **`5`**| | | | | 
| `5`| →→→→ _Equivalent_ →→→→ <br/>(1182)<hr/>←←←← __ ←←←← <br/>() | `5`| →→→→ _Equivalent_ →→→→ <br/>(4668)<hr/>←←←← __ ←←←← <br/>() | **`5`**| | | | | 
| `5`| →→→→ _Equivalent_ →→→→ <br/>(1182)<hr/>←←←← __ ←←←← <br/>() | `5`| →→→→ _Equivalent_ →→→→ <br/>(4668)<hr/>←←←← __ ←←←← <br/>() | **`5`**| | | | | 
| `5`| →→→→ _Equivalent_ →→→→ <br/>(1182)<hr/>←←←← __ ←←←← <br/>() | `5`| →→→→ _Equivalent_ →→→→ <br/>(4668)<hr/>←←←← __ ←←←← <br/>() | **`5`**| | | | | 
| `5`| →→→→ _Equivalent_ →→→→ <br/>(1182)<hr/>←←←← __ ←←←← <br/>() | `5`| →→→→ _Equivalent_ →→→→ <br/>(4668)<hr/>←←←← __ ←←←← <br/>() | **`5`**| | | | | 
| `6`| →→→→ _Equivalent_ →→→→ <br/>(1185)<hr/>←←←← __ ←←←← <br/>() | `6`| →→→→ _Equivalent_ →→→→ <br/>(4679)<hr/>←←←← __ ←←←← <br/>() | **`6`**| | | | | 
| `6`| →→→→ _Equivalent_ →→→→ <br/>(1185)<hr/>←←←← __ ←←←← <br/>() | `6`| →→→→ _Equivalent_ →→→→ <br/>(4679)<hr/>←←←← __ ←←←← <br/>() | **`6`**| | | | | 
| `6`| →→→→ _Equivalent_ →→→→ <br/>(1185)<hr/>←←←← __ ←←←← <br/>() | `6`| →→→→ _Equivalent_ →→→→ <br/>(4679)<hr/>←←←← __ ←←←← <br/>() | **`6`**| | | | | 
| `6`| →→→→ _Equivalent_ →→→→ <br/>(1185)<hr/>←←←← __ ←←←← <br/>() | `6`| →→→→ _Equivalent_ →→→→ <br/>(4679)<hr/>←←←← __ ←←←← <br/>() | **`6`**| | | | | 
| `6`| →→→→ _Equivalent_ →→→→ <br/>(1185)<hr/>←←←← __ ←←←← <br/>() | `6`| →→→→ _Equivalent_ →→→→ <br/>(4679)<hr/>←←←← __ ←←←← <br/>() | **`6`**| | | | | 
| `6`| →→→→ _Equivalent_ →→→→ <br/>(1185)<hr/>←←←← __ ←←←← <br/>() | `6`| →→→→ _Equivalent_ →→→→ <br/>(4679)<hr/>←←←← __ ←←←← <br/>() | **`6`**| | | | | 
| `6`| _Equivalent_ <br/>(1210/2606)| `6`| →→→→ _Equivalent_ →→→→ <br/>(4644)<hr/>←←←← __ ←←←← <br/>() | **`6`**| | | | | 
| `7`| →→→→ _Equivalent_ →→→→ <br/>(1180)<hr/>←←←← __ ←←←← <br/>() | `7`| →→→→ _Equivalent_ →→→→ <br/>(4670)<hr/>←←←← __ ←←←← <br/>() | **`7`**| | | | | 
| `7`| →→→→ _Equivalent_ →→→→ <br/>(1180)<hr/>←←←← __ ←←←← <br/>() | `7`| →→→→ _Equivalent_ →→→→ <br/>(4670)<hr/>←←←← __ ←←←← <br/>() | **`7`**| | | | | 
| `7`| →→→→ _Equivalent_ →→→→ <br/>(1180)<hr/>←←←← __ ←←←← <br/>() | `7`| →→→→ _Equivalent_ →→→→ <br/>(4670)<hr/>←←←← __ ←←←← <br/>() | **`7`**| | | | | 
| `7`| →→→→ _Equivalent_ →→→→ <br/>(1180)<hr/>←←←← __ ←←←← <br/>() | `7`| →→→→ _Equivalent_ →→→→ <br/>(4670)<hr/>←←←← __ ←←←← <br/>() | **`7`**| | | | | 
| `7`| _Equivalent_ <br/>(1208/2604)| `7`| →→→→ _Equivalent_ →→→→ <br/>(4656)<hr/>←←←← __ ←←←← <br/>() | **`7`**| | | | | 
| `8`| →→→→ _Equivalent_ →→→→ <br/>(1178)<hr/>←←←← __ ←←←← <br/>() | `8`| →→→→ _Equivalent_ →→→→ <br/>(4680)<hr/>←←←← __ ←←←← <br/>() | **`8`**| | | | | 
| `8`| →→→→ _Equivalent_ →→→→ <br/>(1178)<hr/>←←←← __ ←←←← <br/>() | `8`| →→→→ _Equivalent_ →→→→ <br/>(4680)<hr/>←←←← __ ←←←← <br/>() | **`8`**| | | | | 
| `8`| →→→→ _Equivalent_ →→→→ <br/>(1178)<hr/>←←←← __ ←←←← <br/>() | `8`| →→→→ _Equivalent_ →→→→ <br/>(4680)<hr/>←←←← __ ←←←← <br/>() | **`8`**| | | | | 
| `8`| →→→→ _Equivalent_ →→→→ <br/>(1178)<hr/>←←←← __ ←←←← <br/>() | `8`| →→→→ _Equivalent_ →→→→ <br/>(4680)<hr/>←←←← __ ←←←← <br/>() | **`8`**| | | | | 
| `8`| _Equivalent_ <br/>(1206/2602)| `8`| →→→→ _Equivalent_ →→→→ <br/>(4647)<hr/>←←←← __ ←←←← <br/>() | **`8`**| | | | | 
| `9`| →→→→ _Equivalent_ →→→→ <br/>(1179)<hr/>←←←← __ ←←←← <br/>() | `9`| →→→→ _Equivalent_ →→→→ <br/>(4674)<hr/>←←←← __ ←←←← <br/>() | **`9`**| | | | | 
| `9`| →→→→ _Equivalent_ →→→→ <br/>(1179)<hr/>←←←← __ ←←←← <br/>() | `9`| →→→→ _Equivalent_ →→→→ <br/>(4674)<hr/>←←←← __ ←←←← <br/>() | **`9`**| | | | | 
| `9`| →→→→ _Equivalent_ →→→→ <br/>(1179)<hr/>←←←← __ ←←←← <br/>() | `9`| →→→→ _Equivalent_ →→→→ <br/>(4674)<hr/>←←←← __ ←←←← <br/>() | **`9`**| | | | | 
| `9`| →→→→ _Equivalent_ →→→→ <br/>(1179)<hr/>←←←← __ ←←←← <br/>() | `9`| →→→→ _Equivalent_ →→→→ <br/>(4674)<hr/>←←←← __ ←←←← <br/>() | **`9`**| | | | | 
| `9`| _Equivalent_ <br/>(1209/2605)| `9`| →→→→ _Equivalent_ →→→→ <br/>(4650)<hr/>←←←← __ ←←←← <br/>() | **`9`**| | | | | 
| `10`| →→→→ _Equivalent_ →→→→ <br/>(1192)<hr/>←←←← __ ←←←← <br/>() | `10`| →→→→ _Equivalent_ →→→→ <br/>(4678)<hr/>←←←← __ ←←←← <br/>() | **`10`**| | | | | 
| `10`| →→→→ _Equivalent_ →→→→ <br/>(1192)<hr/>←←←← __ ←←←← <br/>() | `10`| →→→→ _Equivalent_ →→→→ <br/>(4678)<hr/>←←←← __ ←←←← <br/>() | **`10`**| | | | | 
| `10`| →→→→ _Equivalent_ →→→→ <br/>(1192)<hr/>←←←← __ ←←←← <br/>() | `10`| →→→→ _Equivalent_ →→→→ <br/>(4678)<hr/>←←←← __ ←←←← <br/>() | **`10`**| | | | | 
| `10`| →→→→ _Equivalent_ →→→→ <br/>(1192)<hr/>←←←← __ ←←←← <br/>() | `10`| →→→→ _Equivalent_ →→→→ <br/>(4678)<hr/>←←←← __ ←←←← <br/>() | **`10`**| | | | | 
| `10`| →→→→ _Equivalent_ →→→→ <br/>(1205)<hr/>←←←← __ ←←←← <br/>() | `10`| →→→→ _Equivalent_ →→→→ <br/>(4649)<hr/>←←←← __ ←←←← <br/>() | **`10`**| | | | | 
| `10`| →→→→ _Equivalent_ →→→→ <br/>(1205)<hr/>←←←← __ ←←←← <br/>() | `10`| →→→→ _Equivalent_ →→→→ <br/>(4649)<hr/>←←←← __ ←←←← <br/>() | **`10`**| | | | | 
| `11`| →→→→ _Equivalent_ →→→→ <br/>(1194)<hr/>←←←← __ ←←←← <br/>() | `11`| →→→→ _Equivalent_ →→→→ <br/>(4677)<hr/>←←←← __ ←←←← <br/>() | **`11`**| | | | | 
| `11`| →→→→ _Equivalent_ →→→→ <br/>(1194)<hr/>←←←← __ ←←←← <br/>() | `11`| →→→→ _Equivalent_ →→→→ <br/>(4677)<hr/>←←←← __ ←←←← <br/>() | **`11`**| | | | | 
| `11`| →→→→ _Equivalent_ →→→→ <br/>(1194)<hr/>←←←← __ ←←←← <br/>() | `11`| →→→→ _Equivalent_ →→→→ <br/>(4677)<hr/>←←←← __ ←←←← <br/>() | **`11`**| | | | | 
| `11`| →→→→ _Equivalent_ →→→→ <br/>(1194)<hr/>←←←← __ ←←←← <br/>() | `11`| →→→→ _Equivalent_ →→→→ <br/>(4677)<hr/>←←←← __ ←←←← <br/>() | **`11`**| | | | | 
| `11`| →→→→ _Equivalent_ →→→→ <br/>(1201)<hr/>←←←← __ ←←←← <br/>() | `11`| →→→→ _Equivalent_ →→→→ <br/>(4646)<hr/>←←←← __ ←←←← <br/>() | **`11`**| | | | | 
| `11`| →→→→ _Equivalent_ →→→→ <br/>(1201)<hr/>←←←← __ ←←←← <br/>() | `11`| →→→→ _Equivalent_ →→→→ <br/>(4646)<hr/>←←←← __ ←←←← <br/>() | **`11`**| | | | | 
| `12`| →→→→ _Equivalent_ →→→→ <br/>(1189)<hr/>←←←← __ ←←←← <br/>() | `12`| →→→→ _Equivalent_ →→→→ <br/>(4682)<hr/>←←←← __ ←←←← <br/>() | **`12`**| | | | | 
| `12`| →→→→ _Equivalent_ →→→→ <br/>(1189)<hr/>←←←← __ ←←←← <br/>() | `12`| →→→→ _Equivalent_ →→→→ <br/>(4682)<hr/>←←←← __ ←←←← <br/>() | **`12`**| | | | | 
| `12`| →→→→ _Equivalent_ →→→→ <br/>(1189)<hr/>←←←← __ ←←←← <br/>() | `12`| →→→→ _Equivalent_ →→→→ <br/>(4682)<hr/>←←←← __ ←←←← <br/>() | **`12`**| | | | | 
| `12`| →→→→ _Equivalent_ →→→→ <br/>(1189)<hr/>←←←← __ ←←←← <br/>() | `12`| →→→→ _Equivalent_ →→→→ <br/>(4682)<hr/>←←←← __ ←←←← <br/>() | **`12`**| | | | | 
| `12`| →→→→ _Equivalent_ →→→→ <br/>(1189)<hr/>←←←← __ ←←←← <br/>() | `12`| →→→→ _Equivalent_ →→→→ <br/>(4682)<hr/>←←←← __ ←←←← <br/>() | **`12`**| | | | | 
| `12`| →→→→ _Equivalent_ →→→→ <br/>(1189)<hr/>←←←← __ ←←←← <br/>() | `12`| →→→→ _Equivalent_ →→→→ <br/>(4682)<hr/>←←←← __ ←←←← <br/>() | **`12`**| | | | | 
| `12`| _Equivalent_ <br/>(1212/2608)| `12`| →→→→ _Equivalent_ →→→→ <br/>(4643)<hr/>←←←← __ ←←←← <br/>() | **`12`**| | | | | 
| `13`| →→→→ _Equivalent_ →→→→ <br/>(1177)<hr/>←←←← __ ←←←← <br/>() | `13`| →→→→ _Equivalent_ →→→→ <br/>(4681)<hr/>←←←← __ ←←←← <br/>() | **`13`**| | | | | 
| `13`| →→→→ _Equivalent_ →→→→ <br/>(1177)<hr/>←←←← __ ←←←← <br/>() | `13`| →→→→ _Equivalent_ →→→→ <br/>(4681)<hr/>←←←← __ ←←←← <br/>() | **`13`**| | | | | 
| `13`| →→→→ _Equivalent_ →→→→ <br/>(1177)<hr/>←←←← __ ←←←← <br/>() | `13`| →→→→ _Equivalent_ →→→→ <br/>(4681)<hr/>←←←← __ ←←←← <br/>() | **`13`**| | | | | 
| `13`| →→→→ _Equivalent_ →→→→ <br/>(1177)<hr/>←←←← __ ←←←← <br/>() | `13`| →→→→ _Equivalent_ →→→→ <br/>(4681)<hr/>←←←← __ ←←←← <br/>() | **`13`**| | | | | 
| `13`| →→→→ _Equivalent_ →→→→ <br/>(1177)<hr/>←←←← __ ←←←← <br/>() | `13`| →→→→ _Equivalent_ →→→→ <br/>(4681)<hr/>←←←← __ ←←←← <br/>() | **`13`**| | | | | 
| `13`| →→→→ _Equivalent_ →→→→ <br/>(1177)<hr/>←←←← __ ←←←← <br/>() | `13`| →→→→ _Equivalent_ →→→→ <br/>(4681)<hr/>←←←← __ ←←←← <br/>() | **`13`**| | | | | 
| `13`| _Equivalent_ <br/>(1213/2609)| `13`| →→→→ _Equivalent_ →→→→ <br/>(4648)<hr/>←←←← __ ←←←← <br/>() | **`13`**| | | | | 
| `14`| →→→→ _Equivalent_ →→→→ <br/>(1190)<hr/>←←←← __ ←←←← <br/>() | `14`| →→→→ _Equivalent_ →→→→ <br/>(4673)<hr/>←←←← __ ←←←← <br/>() | **`14`**| | | | | 
| `14`| →→→→ _Equivalent_ →→→→ <br/>(1190)<hr/>←←←← __ ←←←← <br/>() | `14`| →→→→ _Equivalent_ →→→→ <br/>(4673)<hr/>←←←← __ ←←←← <br/>() | **`14`**| | | | | 
| `14`| →→→→ _Equivalent_ →→→→ <br/>(1190)<hr/>←←←← __ ←←←← <br/>() | `14`| →→→→ _Equivalent_ →→→→ <br/>(4673)<hr/>←←←← __ ←←←← <br/>() | **`14`**| | | | | 
| `14`| →→→→ _Equivalent_ →→→→ <br/>(1190)<hr/>←←←← __ ←←←← <br/>() | `14`| →→→→ _Equivalent_ →→→→ <br/>(4673)<hr/>←←←← __ ←←←← <br/>() | **`14`**| | | | | 
| `14`| _Equivalent_ <br/>(1197/2593)| `14`| →→→→ _Equivalent_ →→→→ <br/>(4654)<hr/>←←←← __ ←←←← <br/>() | **`14`**| | | | | 
| `15`| →→→→ _Equivalent_ →→→→ <br/>(1183)<hr/>←←←← __ ←←←← <br/>() | `15`| →→→→ _Equivalent_ →→→→ <br/>(4672)<hr/>←←←← __ ←←←← <br/>() | **`15`**| | | | | 
| `15`| →→→→ _Equivalent_ →→→→ <br/>(1183)<hr/>←←←← __ ←←←← <br/>() | `15`| →→→→ _Equivalent_ →→→→ <br/>(4672)<hr/>←←←← __ ←←←← <br/>() | **`15`**| | | | | 
| `15`| →→→→ _Equivalent_ →→→→ <br/>(1183)<hr/>←←←← __ ←←←← <br/>() | `15`| →→→→ _Equivalent_ →→→→ <br/>(4672)<hr/>←←←← __ ←←←← <br/>() | **`15`**| | | | | 
| `15`| →→→→ _Equivalent_ →→→→ <br/>(1183)<hr/>←←←← __ ←←←← <br/>() | `15`| →→→→ _Equivalent_ →→→→ <br/>(4672)<hr/>←←←← __ ←←←← <br/>() | **`15`**| | | | | 
| `15`| _Equivalent_ <br/>(1207/2603)| `15`| →→→→ _Equivalent_ →→→→ <br/>(4655)<hr/>←←←← __ ←←←← <br/>() | **`15`**| | | | | 
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/iso-21089-lifecycle`
| | | | | **`access`**| | | | | 
| | | | | **`hold`**| | | | | 
| | | | | **`amend`**| | | | | 
| | | | | **`archive`**| | | | | 
| | | | | **`attest`**| | | | | 
| | | | | **`decrypt`**| | | | | 
| | | | | **`deidentify`**| | | | | 
| | | | | **`deprecate`**| | | | | 
| | | | | **`destroy`**| | | | | 
| | | | | **`disclose`**| | | | | 
| | | | | **`encrypt`**| | | | | 
| | | | | **`extract`**| | | | | 
| | | | | **`link`**| | | | | 
| | | | | **`merge`**| | | | | 
| | | | | **`originate`**| | | | | 
| | | | | **`pseudonymize`**| | | | | 
| | | | | **`reactivate`**| | | | | 
| | | | | **`receive`**| | | | | 
| | | | | **`reidentify`**| | | | | 
| | | | | **`unhold`**| | | | | 
| | | | | **`report`**| | | | | 
| | | | | **`restore`**| | | | | 
| | | | | **`transform`**| | | | | 
| | | | | **`transmit`**| | | | | 
| | | | | **`unlink`**| | | | | 
| | | | | **`unmerge`**| | | | | 
| | | | | **`verify`**| | | | | 
| *15 of 15 codes used* | | *30 of 40 codes used* <br/>remaining codes:<br/>`16`, `17`, `18`, `19`, `20`, `21`, `22`, `24`, `25`, `26`, `27`| | *42 of 42 codes used* | | | | 

