Comparison of 
Generated at Tuesday, April 1, 2025 1:39:11 PM

### ProvenanceActivityType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | ProvenanceActivityType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/provenance-activity-type` |
| Version | 1.1.0 |
| Description | This value set contains representative Activity Type codes, which includes codes from the HL7 DocumentCompletion, ActStatus, and DataOperations code system, W3C PROV-DM and PROV-N concepts and display names, several HL7 Lifecycle Event codes for which there are agreed upon definitions, and non-duplicated codes from the HL7 Security and Privacy Ontology Operations codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1409` |
| Database Concept Count | `83` |
| Database Active Concept Count | `83` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Provenance` | `Provenance.activity` | `http://hl7.org/fhir/ValueSet/provenance-activity-type` | `Extensible` | Activity that occurred |

### Referenced Systems

* `http://hl7.org/fhir/v3/DocumentCompletion`
* `http://hl7.org/fhir/v3/ActStatus`
* `http://hl7.org/fhir/v3/DataOperation`
* `http://hl7.org/fhir/v3/ActCode`
* `http://hl7.org/fhir/w3c-provenance-activity-type`
* `http://hl7.org/fhir/extra-activity-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ProvenanceEventCurrentState](/docs/R2/ValueSets/ProvenanceEventCurrentState.md)<br/> `http://hl7.org/fhir/ValueSet/v3-ProvenanceEventCurrentState\|2014-08-07` | →→→→→→→<br/>``<br/>- DBKey: `121`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `279`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ProvenanceActivityType](/docs/R3/ValueSets/ProvenanceActivityType.md)<br/> `http://hl7.org/fhir/ValueSet/provenance-activity-type\|1.1.0` | →→→→→→→<br/>``<br/>- DBKey: `481`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ProvenanceActivityType](/docs/R4/ValueSets/ProvenanceActivityType.md)<br/> `http://hl7.org/fhir/ValueSet/provenance-activity-type\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set ProvenanceActivityType from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ProvenanceEventCurrentState](/docs/R2/ValueSets/ProvenanceEventCurrentState.md)| Relationship | R3 ProvenanceActivityType| Relationship | [R4 ProvenanceActivityType](/docs/R4/ValueSets/ProvenanceActivityType.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/DocumentCompletion`
| `AU`| _Equivalent_ <br/>(1006/2414)| **`AU`**| →→→→ __ →→→→ <br/>(4510)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| `AU`| _Equivalent_ <br/>(1006/2414)| **`AU`**| →→→→ __ →→→→ <br/>(4510)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| `AU`| _Equivalent_ <br/>(1006/2414)| **`AU`**| →→→→ __ →→→→ <br/>(4510)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| `DI`| _Equivalent_ <br/>(1007/2415)| **`DI`**| →→→→ __ →→→→ <br/>(4511)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| `DI`| _Equivalent_ <br/>(1007/2415)| **`DI`**| →→→→ __ →→→→ <br/>(4511)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| `DI`| _Equivalent_ <br/>(1007/2415)| **`DI`**| →→→→ __ →→→→ <br/>(4511)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| `DO`| _Equivalent_ <br/>(1008/2416)| **`DO`**| →→→→ __ →→→→ <br/>(4514)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| `DO`| _Equivalent_ <br/>(1008/2416)| **`DO`**| →→→→ __ →→→→ <br/>(4514)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| `DO`| _Equivalent_ <br/>(1008/2416)| **`DO`**| →→→→ __ →→→→ <br/>(4514)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`IN`**| →→→→ __ →→→→ <br/>(4512)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`IN`**| →→→→ __ →→→→ <br/>(4512)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`IN`**| →→→→ __ →→→→ <br/>(4512)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`IP`**| →→→→ __ →→→→ <br/>(4509)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`IP`**| →→→→ __ →→→→ <br/>(4509)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`IP`**| →→→→ __ →→→→ <br/>(4509)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| `LA`| _Equivalent_ <br/>(1009/2419)| **`LA`**| _Equivalent_ <br/>(4507/6756)| `LA`| | | | | 
| `LA`| _Equivalent_ <br/>(1009/2419)| **`LA`**| _Equivalent_ <br/>(4507/6756)| `LA`| | | | | 
| `LA`| _Equivalent_ <br/>(1009/2419)| **`LA`**| _Equivalent_ <br/>(4507/6756)| `LA`| | | | | 
| | | **`NU`**| →→→→ __ →→→→ <br/>(4508)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`NU`**| →→→→ __ →→→→ <br/>(4508)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`NU`**| →→→→ __ →→→→ <br/>(4508)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`PA`**| →→→→ __ →→→→ <br/>(4513)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`PA`**| →→→→ __ →→→→ <br/>(4513)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`PA`**| →→→→ __ →→→→ <br/>(4513)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| `UC`| _Equivalent_ <br/>(1010/2422)| **`UC`**| →→→→ __ →→→→ <br/>(4515)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| `UC`| _Equivalent_ <br/>(1010/2422)| **`UC`**| →→→→ __ →→→→ <br/>(4515)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| `UC`| _Equivalent_ <br/>(1010/2422)| **`UC`**| →→→→ __ →→→→ <br/>(4515)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/ActStatus`
| | | **`normal`**| | | | | | | 
| `aborted`| _Equivalent_ <br/>(1000/2404)| **`aborted`**| | | | | | | 
| | | **`active`**| | | | | | | 
| `cancelled`| _Equivalent_ <br/>(1001/2406)| **`cancelled`**| | | | | | | 
| `completed`| _Equivalent_ <br/>(1002/2407)| **`completed`**| | | | | | | 
| | | **`held`**| | | | | | | 
| `new`| _Equivalent_ <br/>(1003/2409)| **`new`**| | | | | | | 
| | | **`suspended`**| | | | | | | 
| `nullified`| _Equivalent_ <br/>(1004/2411)| **`nullified`**| | | | | | | 
| `obsolete`| _Equivalent_ <br/>(1005/2412)| **`obsolete`**| | | | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/DataOperation`
| | | **`OPERATE`**| →→→→ __ →→→→ <br/>(4477)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`OPERATE`**| →→→→ __ →→→→ <br/>(4477)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`CREATE`**| _Equivalent_ <br/>(4458/6823)| `CREATE`| | | | | 
| | | **`CREATE`**| _Equivalent_ <br/>(4458/6823)| `CREATE`| | | | | 
| | | **`DELETE`**| _Equivalent_ <br/>(4462/6822)| `DELETE`| | | | | 
| | | **`DELETE`**| _Equivalent_ <br/>(4462/6822)| `DELETE`| | | | | 
| | | **`EXECUTE`**| →→→→ __ →→→→ <br/>(4466)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`EXECUTE`**| →→→→ __ →→→→ <br/>(4466)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`READ`**| →→→→ __ →→→→ <br/>(4472)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`READ`**| →→→→ __ →→→→ <br/>(4472)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`UPDATE`**| _Equivalent_ <br/>(4460/6821)| `UPDATE`| | | | | 
| | | **`UPDATE`**| _Equivalent_ <br/>(4460/6821)| `UPDATE`| | | | | 
| | | **`APPEND`**| _Equivalent_ <br/>(4461/6824)| `APPEND`| | | | | 
| | | **`APPEND`**| _Equivalent_ <br/>(4461/6824)| `APPEND`| | | | | 
| | | **`MODIFYSTATUS`**| →→→→ __ →→→→ <br/>(4468)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`MODIFYSTATUS`**| →→→→ __ →→→→ <br/>(4468)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`ABORT`**| →→→→ __ →→→→ <br/>(4470)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`ABORT`**| →→→→ __ →→→→ <br/>(4470)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`ACTIVATE`**| →→→→ __ →→→→ <br/>(4469)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`ACTIVATE`**| →→→→ __ →→→→ <br/>(4469)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`CANCEL`**| →→→→ __ →→→→ <br/>(4471)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`CANCEL`**| →→→→ __ →→→→ <br/>(4471)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`COMPLETE`**| →→→→ __ →→→→ <br/>(4467)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`COMPLETE`**| →→→→ __ →→→→ <br/>(4467)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`HOLD`**| →→→→ __ →→→→ <br/>(4474)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`HOLD`**| →→→→ __ →→→→ <br/>(4474)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`JUMP`**| →→→→ __ →→→→ <br/>(4473)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`JUMP`**| →→→→ __ →→→→ <br/>(4473)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`NULLIFY`**| _Equivalent_ <br/>(4459/6820)| `NULLIFY`| | | | | 
| | | **`NULLIFY`**| _Equivalent_ <br/>(4459/6820)| `NULLIFY`| | | | | 
| | | **`OBSOLETE`**| →→→→ __ →→→→ <br/>(4475)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`OBSOLETE`**| →→→→ __ →→→→ <br/>(4475)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`REACTIVATE`**| →→→→ __ →→→→ <br/>(4465)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`REACTIVATE`**| →→→→ __ →→→→ <br/>(4465)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`RELEASE`**| →→→→ __ →→→→ <br/>(4464)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`RELEASE`**| →→→→ __ →→→→ <br/>(4464)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`RESUME`**| →→→→ __ →→→→ <br/>(4476)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`RESUME`**| →→→→ __ →→→→ <br/>(4476)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`SUSPEND`**| →→→→ __ →→→→ <br/>(4463)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`SUSPEND`**| →→→→ __ →→→→ <br/>(4463)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/ActCode`
| | | **`ObligationPolicy`**| →→→→ __ →→→→ <br/>(4483)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`ObligationPolicy`**| →→→→ __ →→→→ <br/>(4483)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`ANONY`**| _Equivalent_ <br/>(4478/6815)| `ANONY`| | | | | 
| | | **`ANONY`**| _Equivalent_ <br/>(4478/6815)| `ANONY`| | | | | 
| | | **`AOD`**| →→→→ __ →→→→ <br/>(4493)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`AOD`**| →→→→ __ →→→→ <br/>(4493)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`AUDIT`**| →→→→ __ →→→→ <br/>(4491)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`AUDIT`**| →→→→ __ →→→→ <br/>(4491)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`AUDTR`**| →→→→ __ →→→→ <br/>(4487)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`AUDTR`**| →→→→ __ →→→→ <br/>(4487)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`CPLYCC`**| →→→→ __ →→→→ <br/>(4492)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`CPLYCC`**| →→→→ __ →→→→ <br/>(4492)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`CPLYCD`**| →→→→ __ →→→→ <br/>(4490)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`CPLYCD`**| →→→→ __ →→→→ <br/>(4490)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`CPLYJPP`**| →→→→ __ →→→→ <br/>(4502)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`CPLYJPP`**| →→→→ __ →→→→ <br/>(4502)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`CPLYOPP`**| →→→→ __ →→→→ <br/>(4500)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`CPLYOPP`**| →→→→ __ →→→→ <br/>(4500)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`CPLYOSP`**| →→→→ __ →→→→ <br/>(4505)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`CPLYOSP`**| →→→→ __ →→→→ <br/>(4505)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`CPLYPOL`**| →→→→ __ →→→→ <br/>(4497)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`CPLYPOL`**| →→→→ __ →→→→ <br/>(4497)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`DECLASSIFYLABEL`**| →→→→ __ →→→→ <br/>(4506)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`DECLASSIFYLABEL`**| →→→→ __ →→→→ <br/>(4506)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`DEID`**| _Equivalent_ <br/>(4481/6818)| `DEID`| | | | | 
| | | **`DEID`**| _Equivalent_ <br/>(4481/6818)| `DEID`| | | | | 
| | | **`DELAU`**| →→→→ __ →→→→ <br/>(4499)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`DELAU`**| →→→→ __ →→→→ <br/>(4499)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`DOWNGRDLABEL`**| →→→→ __ →→→→ <br/>(4498)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`DOWNGRDLABEL`**| →→→→ __ →→→→ <br/>(4498)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`DRIVLABEL`**| →→→→ __ →→→→ <br/>(4495)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`DRIVLABEL`**| →→→→ __ →→→→ <br/>(4495)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`ENCRYPT`**| →→→→ __ →→→→ <br/>(4485)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`ENCRYPT`**| →→→→ __ →→→→ <br/>(4485)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`ENCRYPTR`**| →→→→ __ →→→→ <br/>(4486)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`ENCRYPTR`**| →→→→ __ →→→→ <br/>(4486)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`ENCRYPTT`**| →→→→ __ →→→→ <br/>(4496)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`ENCRYPTT`**| →→→→ __ →→→→ <br/>(4496)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`ENCRYPTU`**| →→→→ __ →→→→ <br/>(4503)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`ENCRYPTU`**| →→→→ __ →→→→ <br/>(4503)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`HUAPRV`**| →→→→ __ →→→→ <br/>(4501)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`HUAPRV`**| →→→→ __ →→→→ <br/>(4501)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`LABEL`**| _Equivalent_ <br/>(4479/6816)| `LABEL`| | | | | 
| | | **`LABEL`**| _Equivalent_ <br/>(4479/6816)| `LABEL`| | | | | 
| | | **`MASK`**| _Equivalent_ <br/>(4480/6819)| `MASK`| | | | | 
| | | **`MASK`**| _Equivalent_ <br/>(4480/6819)| `MASK`| | | | | 
| | | **`MINEC`**| →→→→ __ →→→→ <br/>(4504)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`MINEC`**| →→→→ __ →→→→ <br/>(4504)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`PERSISTLABEL`**| →→→→ __ →→→→ <br/>(4484)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`PERSISTLABEL`**| →→→→ __ →→→→ <br/>(4484)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`PRIVMARK`**| →→→→ __ →→→→ <br/>(4489)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`PRIVMARK`**| →→→→ __ →→→→ <br/>(4489)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`PSEUD`**| _Equivalent_ <br/>(4482/6817)| `PSEUD`| | | | | 
| | | **`PSEUD`**| _Equivalent_ <br/>(4482/6817)| `PSEUD`| | | | | 
| | | **`REDACT`**| →→→→ __ →→→→ <br/>(4494)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`REDACT`**| →→→→ __ →→→→ <br/>(4494)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`UPGRDLABEL`**| →→→→ __ →→→→ <br/>(4488)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`UPGRDLABEL`**| →→→→ __ →→→→ <br/>(4488)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/w3c-provenance-activity-type`
| | | **`Generation`**| | | | | | | 
| | | **`Usage`**| | | | | | | 
| | | **`Communication`**| | | | | | | 
| | | **`Start`**| | | | | | | 
| | | **`End`**| | | | | | | 
| | | **`Invalidation`**| | | | | | | 
| | | **`Derivation`**| | | | | | | 
| | | **`Revision`**| | | | | | | 
| | | **`Quotation`**| | | | | | | 
| | | **`Primary-Source`**| | | | | | | 
| | | **`Attribution`**| | | | | | | 
| | | **`Collection`**| | | | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/extra-activity-type`
| | | **`aggregate`**| | | | | | | 
| | | **`compose`**| | | | | | | 
| | | **`label`**| | | | | | | 
| *11 of 11 codes used* | | *83 of 83 codes used* | | *13 of 70 codes used* | | | | 

