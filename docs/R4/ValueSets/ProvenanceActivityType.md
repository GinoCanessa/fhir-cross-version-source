Comparison of 
Generated at Tuesday, April 1, 2025 1:39:17 PM

### ProvenanceActivityType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ProvenanceActivityType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/provenance-activity-type` |
| Version | 4.0.1 |
| Description | This value set contains representative Activity Type codes, which includes codes from the HL7 DocumentCompletion, ActStatus, and DataOperations code system, W3C PROV-DM and PROV-N concepts and display names, several HL7 Lifecycle Event codes for which there are agreed upon definitions, and non-duplicated codes from the HL7 Security and Privacy Ontology Operations codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2664` |
| Database Concept Count | `70` |
| Database Active Concept Count | `70` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Provenance` | `Provenance.activity` | `http://hl7.org/fhir/ValueSet/provenance-activity-type` | `Extensible` | Activity that occurred |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-DocumentCompletion`
* `http://terminology.hl7.org/CodeSystem/v3-ActCode`
* `http://terminology.hl7.org/CodeSystem/v3-DataOperation`
* `http://terminology.hl7.org/CodeSystem/v3-ParticipationType`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ProvenanceEventCurrentState](/docs/R2/ValueSets/ProvenanceEventCurrentState.md)<br/> `http://hl7.org/fhir/ValueSet/v3-ProvenanceEventCurrentState\|2014-08-07` | →→→→→→→<br/>``<br/>- DBKey: `121`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `279`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ProvenanceActivityType](/docs/R3/ValueSets/ProvenanceActivityType.md)<br/> `http://hl7.org/fhir/ValueSet/provenance-activity-type\|1.1.0` | →→→→→→→<br/>``<br/>- DBKey: `481`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ProvenanceActivityType](/docs/R4/ValueSets/ProvenanceActivityType.md)<br/> `http://hl7.org/fhir/ValueSet/provenance-activity-type\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set ProvenanceActivityType from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ProvenanceEventCurrentState](/docs/R2/ValueSets/ProvenanceEventCurrentState.md)| Relationship | [R3 ProvenanceActivityType](/docs/R3/ValueSets/ProvenanceActivityType.md)| Relationship | R4 ProvenanceActivityType| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v3-DocumentCompletion`
| `LA`| _Equivalent_ <br/>(1009/2419)| `LA`| _Equivalent_ <br/>(4449/6825)| **`LA`**| | | | | 
| `LA`| _Equivalent_ <br/>(1009/2419)| `LA`| _Equivalent_ <br/>(4449/6825)| **`LA`**| | | | | 
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v3-ActCode`
| | | `ANONY`| _Equivalent_ <br/>(4478/6815)| **`ANONY`**| | | | | 
| | | `ANONY`| _Equivalent_ <br/>(4478/6815)| **`ANONY`**| | | | | 
| | | `DEID`| _Equivalent_ <br/>(4481/6818)| **`DEID`**| | | | | 
| | | `DEID`| _Equivalent_ <br/>(4481/6818)| **`DEID`**| | | | | 
| | | `MASK`| _Equivalent_ <br/>(4480/6819)| **`MASK`**| | | | | 
| | | `MASK`| _Equivalent_ <br/>(4480/6819)| **`MASK`**| | | | | 
| | | `LABEL`| _Equivalent_ <br/>(4479/6816)| **`LABEL`**| | | | | 
| | | `LABEL`| _Equivalent_ <br/>(4479/6816)| **`LABEL`**| | | | | 
| | | `PSEUD`| _Equivalent_ <br/>(4482/6817)| **`PSEUD`**| | | | | 
| | | `PSEUD`| _Equivalent_ <br/>(4482/6817)| **`PSEUD`**| | | | | 
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v3-DataOperation`
| | | `CREATE`| _Equivalent_ <br/>(4458/6823)| **`CREATE`**| | | | | 
| | | `CREATE`| _Equivalent_ <br/>(4458/6823)| **`CREATE`**| | | | | 
| | | `DELETE`| _Equivalent_ <br/>(4462/6822)| **`DELETE`**| | | | | 
| | | `DELETE`| _Equivalent_ <br/>(4462/6822)| **`DELETE`**| | | | | 
| | | `UPDATE`| _Equivalent_ <br/>(4460/6821)| **`UPDATE`**| | | | | 
| | | `UPDATE`| _Equivalent_ <br/>(4460/6821)| **`UPDATE`**| | | | | 
| | | `APPEND`| _Equivalent_ <br/>(4461/6824)| **`APPEND`**| | | | | 
| | | `APPEND`| _Equivalent_ <br/>(4461/6824)| **`APPEND`**| | | | | 
| | | `NULLIFY`| _Equivalent_ <br/>(4459/6820)| **`NULLIFY`**| | | | | 
| | | `NULLIFY`| _Equivalent_ <br/>(4459/6820)| **`NULLIFY`**| | | | | 
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v3-ParticipationType`
| | | | | **`PART`**| | | | | 
| | | | | **`ADM`**| | | | | 
| | | | | **`ATND`**| | | | | 
| | | | | **`CALLBCK`**| | | | | 
| | | | | **`CON`**| | | | | 
| | | | | **`DIS`**| | | | | 
| | | | | **`ESC`**| | | | | 
| | | | | **`REF`**| | | | | 
| | | | | **`AUT`**| | | | | 
| | | | | **`INF`**| | | | | 
| | | | | **`TRANS`**| | | | | 
| | | | | **`ENT`**| | | | | 
| | | | | **`WIT`**| | | | | 
| | | | | **`CST`**| | | | | 
| | | | | **`DIR`**| | | | | 
| | | | | **`ALY`**| | | | | 
| | | | | **`BBY`**| | | | | 
| | | | | **`CAT`**| | | | | 
| | | | | **`CSM`**| | | | | 
| | | | | **`TPA`**| | | | | 
| | | | | **`DEV`**| | | | | 
| | | | | **`NRD`**| | | | | 
| | | | | **`RDV`**| | | | | 
| | | | | **`DON`**| | | | | 
| | | | | **`EXPAGNT`**| | | | | 
| | | | | **`EXPART`**| | | | | 
| | | | | **`EXPTRGT`**| | | | | 
| | | | | **`EXSRC`**| | | | | 
| | | | | **`PRD`**| | | | | 
| | | | | **`SBJ`**| | | | | 
| | | | | **`SPC`**| | | | | 
| | | | | **`IND`**| | | | | 
| | | | | **`BEN`**| | | | | 
| | | | | **`CAGNT`**| | | | | 
| | | | | **`COV`**| | | | | 
| | | | | **`GUAR`**| | | | | 
| | | | | **`HLD`**| | | | | 
| | | | | **`RCT`**| | | | | 
| | | | | **`RCV`**| | | | | 
| | | | | **`IRCP`**| | | | | 
| | | | | **`NOT`**| | | | | 
| | | | | **`PRCP`**| | | | | 
| | | | | **`REFB`**| | | | | 
| | | | | **`REFT`**| | | | | 
| | | | | **`TRC`**| | | | | 
| | | | | **`LOC`**| | | | | 
| | | | | **`DST`**| | | | | 
| | | | | **`ELOC`**| | | | | 
| | | | | **`ORG`**| | | | | 
| | | | | **`RML`**| | | | | 
| | | | | **`VIA`**| | | | | 
| | | | | **`PRF`**| | | | | 
| | | | | **`DIST`**| | | | | 
| | | | | **`PPRF`**| | | | | 
| | | | | **`SPRF`**| | | | | 
| | | | | **`RESP`**| | | | | 
| | | | | **`VRF`**| | | | | 
| | | | | **`AUTHEN`**| | | | | 
| `LA`| _Equivalent_ <br/>(1009/2419)| `LA`| _Equivalent_ <br/>(4507/6756)| **`LA`**| | | | | 
| *1 of 11 codes used* | | *11 of 83 codes used* | | *70 of 70 codes used* | | | | 

