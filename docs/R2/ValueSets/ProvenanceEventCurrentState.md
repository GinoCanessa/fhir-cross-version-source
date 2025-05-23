Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### ProvenanceEventCurrentState

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | ProvenanceEventCurrentState |
| Canonical URL | `http://hl7.org/fhir/ValueSet/v3-ProvenanceEventCurrentState` |
| Version | 2014-08-07 |
| Description | Specifies the state change of a target  Act, such as a document or an entry, from its previous state as a predecessor Act. For example, if the target Act is the result of a predecessor Act being "obsoleted" and replaced with the target Act, the source ProvenanceEventCurrentState Act code would be  "obsoleted". |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `959` |
| Database Concept Count | `11` |
| Database Active Concept Count | `11` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Provenance` | `Provenance.activity` | `http://hl7.org/fhir/ValueSet/v3-ProvenanceEventCurrentState` | `Extensible` | Activity that occurred |

### Referenced Systems

* `http://hl7.org/fhir/v3/ActStatus`
* `http://hl7.org/fhir/v3/DocumentCompletion`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ProvenanceEventCurrentState](/docs/R2/ValueSets/ProvenanceEventCurrentState.md)<br/> `http://hl7.org/fhir/ValueSet/v3-ProvenanceEventCurrentState\|2014-08-07` | →→→→→→→<br/>``<br/>- DBKey: `121`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `279`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ProvenanceActivityType](/docs/R3/ValueSets/ProvenanceActivityType.md)<br/> `http://hl7.org/fhir/ValueSet/provenance-activity-type\|1.1.0` | →→→→→→→<br/>``<br/>- DBKey: `481`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ProvenanceActivityType](/docs/R4/ValueSets/ProvenanceActivityType.md)<br/> `http://hl7.org/fhir/ValueSet/provenance-activity-type\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set ProvenanceEventCurrentState from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 ProvenanceEventCurrentState| Relationship | [R3 ProvenanceActivityType](/docs/R3/ValueSets/ProvenanceActivityType.md)| Relationship | [R4 ProvenanceActivityType](/docs/R4/ValueSets/ProvenanceActivityType.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/v3/ActStatus`
| **`aborted`**| _Equivalent_ <br/>(1000/2404)| `aborted`| | | | | | | 
| **`cancelled`**| _Equivalent_ <br/>(1001/2406)| `cancelled`| | | | | | | 
| **`completed`**| _Equivalent_ <br/>(1002/2407)| `completed`| | | | | | | 
| **`new`**| _Equivalent_ <br/>(1003/2409)| `new`| | | | | | | 
| **`nullified`**| _Equivalent_ <br/>(1004/2411)| `nullified`| | | | | | | 
| **`obsolete`**| _Equivalent_ <br/>(1005/2412)| `obsolete`| | | | | | | 
| <td colspan="8">**R2** System: `http://hl7.org/fhir/v3/DocumentCompletion`
| **`AU`**| _Equivalent_ <br/>(1006/2414)| `AU`| →→→→ __ →→→→ <br/>(4443)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| **`AU`**| _Equivalent_ <br/>(1006/2414)| `AU`| →→→→ __ →→→→ <br/>(4452)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| **`AU`**| _Equivalent_ <br/>(1006/2414)| `AU`| →→→→ __ →→→→ <br/>(4510)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| **`DI`**| _Equivalent_ <br/>(1007/2415)| `DI`| →→→→ __ →→→→ <br/>(4444)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| **`DI`**| _Equivalent_ <br/>(1007/2415)| `DI`| →→→→ __ →→→→ <br/>(4453)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| **`DI`**| _Equivalent_ <br/>(1007/2415)| `DI`| →→→→ __ →→→→ <br/>(4511)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| **`DO`**| _Equivalent_ <br/>(1008/2416)| `DO`| →→→→ __ →→→→ <br/>(4447)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| **`DO`**| _Equivalent_ <br/>(1008/2416)| `DO`| →→→→ __ →→→→ <br/>(4456)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| **`DO`**| _Equivalent_ <br/>(1008/2416)| `DO`| →→→→ __ →→→→ <br/>(4514)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| **`LA`**| _Equivalent_ <br/>(1009/2419)| `LA`| →→→→ _Equivalent_ →→→→ <br/>(4440)<hr/>←←←← __ ←←←← <br/>() | `LA`| | | | | 
| **`LA`**| _Equivalent_ <br/>(1009/2419)| `LA`| _Equivalent_ <br/>(4449/6825)| `LA`| | | | | 
| **`LA`**| _Equivalent_ <br/>(1009/2419)| `LA`| _Equivalent_ <br/>(4507/6756)| `LA`| | | | | 
| **`UC`**| _Equivalent_ <br/>(1010/2422)| `UC`| →→→→ __ →→→→ <br/>(4448)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| **`UC`**| _Equivalent_ <br/>(1010/2422)| `UC`| →→→→ __ →→→→ <br/>(4457)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| **`UC`**| _Equivalent_ <br/>(1010/2422)| `UC`| →→→→ __ →→→→ <br/>(4515)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| *11 of 11 codes used* | | *11 of 83 codes used* <br/>remaining codes:<br/>`aggregate`, `compose`, `label`, `ANONY`, `AOD`, `AUDIT`, `AUDTR`, `CPLYCC`, `CPLYCD`, `CPLYJPP`, `CPLYOPP`, `CPLYOSP`, `CPLYPOL`, `DECLASSIFYLABEL`, `DEID`, `DELAU`, `DOWNGRDLABEL`, `DRIVLABEL`, `ENCRYPT`, `ENCRYPTR`, `ENCRYPTT`, `ENCRYPTU`, `HUAPRV`, `LABEL`, `MASK`, `MINEC`, `ObligationPolicy`, `PERSISTLABEL`, `PRIVMARK`, `PSEUD`, `REDACT`, `UPGRDLABEL`, `active`, `held`, `normal`, `suspended`, `ABORT`, `ACTIVATE`, `APPEND`, `CANCEL`, `COMPLETE`, `CREATE`, `DELETE`, `EXECUTE`, `HOLD`, `JUMP`, `MODIFYSTATUS`, `NULLIFY`, `OBSOLETE`, `OPERATE`, `REACTIVATE`, `READ`, `RELEASE`, `RESUME`, `SUSPEND`, `UPDATE`, `IN`, `IP`, `NU`, `PA`, `Attribution`, `Collection`, `Communication`, `Derivation`, `End`, `Generation`, `Invalidation`, `Primary-Source`, `Quotation`, `Revision`, `Start`, `Usage`| | *3 of 70 codes used* <br/>remaining codes:<br/>`ANONY`, `DEID`, `LABEL`, `MASK`, `PSEUD`, `APPEND`, `CREATE`, `DELETE`, `NULLIFY`, `UPDATE`, `ADM`, `ALY`, `ATND`, `AUT`, `AUTHEN`, `BBY`, `BEN`, `CAGNT`, `CALLBCK`, `CAT`, `CON`, `COV`, `CSM`, `CST`, `DEV`, `DIR`, `DIS`, `DIST`, `DON`, `DST`, `ELOC`, `ENT`, `ESC`, `EXPAGNT`, `EXPART`, `EXPTRGT`, `EXSRC`, `GUAR`, `HLD`, `IND`, `INF`, `IRCP`, `LOC`, `NOT`, `NRD`, `ORG`, `PART`, `PPRF`, `PRCP`, `PRD`, `PRF`, `RCT`, `RCV`, `RDV`, `REF`, `REFB`, `REFT`, `RESP`, `RML`, `SBJ`, `SPC`, `SPRF`, `TPA`, `TRANS`, `TRC`, `VIA`, `VRF`, `WIT`| | | | 

