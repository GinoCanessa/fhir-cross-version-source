Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### PatientRelationshipType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | PatientRelationshipType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/relatedperson-relationshiptype` |
| Version | 1.0.2 |
| Description | A set of codes that can be used to indicate the relationship between a Patient and a Related Person. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `337` |
| Database Concept Count | `121` |
| Database Active Concept Count | `120` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/RelatedPerson` | `RelatedPerson.relationship` | `http://hl7.org/fhir/ValueSet/relatedperson-relationshiptype` | `Required` | The nature of the relationship |

### Referenced Systems

* `http://hl7.org/fhir/patient-contact-relationship`
* `http://hl7.org/fhir/v3/RoleCode`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [PatientRelationshipType](/docs/R2/ValueSets/PatientRelationshipType.md)<br/> `http://hl7.org/fhir/ValueSet/relatedperson-relationshiptype\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `1303`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1304`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [PatientRelationshipType](/docs/R3/ValueSets/PatientRelationshipType.md)<br/> `http://hl7.org/fhir/ValueSet/relatedperson-relationshiptype\|3.0.2` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set PatientRelationshipType from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 PatientRelationshipType| Relationship | [R3 PatientRelationshipType](/docs/R3/ValueSets/PatientRelationshipType.md)| Relationship | *No Map* | Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/patient-contact-relationship`
| **`emergency`**| | | | | | | | | 
| **`family`**| | | | | | | | | 
| **`guardian`**| | | | | | | | | 
| **`friend`**| | | | | | | | | 
| **`partner`**| | | | | | | | | 
| **`work`**| | | | | | | | | 
| **`caregiver`**| | | | | | | | | 
| **`agent`**| | | | | | | | | 
| **`guarantor`**| | | | | | | | | 
| **`owner`**| | | | | | | | | 
| **`parent`**| | | | | | | | | 
| <td colspan="8">**R2** System: `http://hl7.org/fhir/v3/RoleCode`
| **`DAUADOPT`**| _Equivalent_ <br/>(12346/12347)| `DAUADOPT`| | | | | | | 
| **`SONADOPT`**| _Equivalent_ <br/>(12348/12349)| `SONADOPT`| | | | | | | 
| **`CHLDADOPT`**| _Equivalent_ <br/>(12350/12351)| `CHLDADOPT`| | | | | | | 
| **`DAUFOST`**| _Equivalent_ <br/>(12352/12353)| `DAUFOST`| | | | | | | 
| **`SONFOST`**| _Equivalent_ <br/>(12354/12355)| `SONFOST`| | | | | | | 
| **`CHLDFOST`**| _Equivalent_ <br/>(12356/12357)| `CHLDFOST`| | | | | | | 
| **`DAU`**| _Equivalent_ <br/>(12358/12359)| `DAU`| | | | | | | 
| **`STPDAU`**| _Equivalent_ <br/>(12360/12361)| `STPDAU`| | | | | | | 
| **`DAUC`**| _Equivalent_ <br/>(12362/12363)| `DAUC`| | | | | | | 
| **`SON`**| _Equivalent_ <br/>(12364/12365)| `SON`| | | | | | | 
| **`NCHILD`**| _Equivalent_ <br/>(12366/12367)| `NCHILD`| | | | | | | 
| **`STPSON`**| _Equivalent_ <br/>(12368/12369)| `STPSON`| | | | | | | 
| **`SONC`**| _Equivalent_ <br/>(12370/12371)| `SONC`| | | | | | | 
| **`STPCHLD`**| _Equivalent_ <br/>(12372/12373)| `STPCHLD`| | | | | | | 
| **`CHILD`**| _Equivalent_ <br/>(12374/12375)| `CHILD`| | | | | | | 
| **`MAUNT`**| _Equivalent_ <br/>(12376/12377)| `MAUNT`| | | | | | | 
| **`PAUNT`**| _Equivalent_ <br/>(12378/12379)| `PAUNT`| | | | | | | 
| **`AUNT`**| _Equivalent_ <br/>(12380/12381)| `AUNT`| | | | | | | 
| **`MCOUSN`**| _Equivalent_ <br/>(12382/12383)| `MCOUSN`| | | | | | | 
| **`PCOUSN`**| _Equivalent_ <br/>(12384/12385)| `PCOUSN`| | | | | | | 
| **`COUSN`**| _Equivalent_ <br/>(12386/12387)| `COUSN`| | | | | | | 
| **`MGGRFTH`**| _Equivalent_ <br/>(12388/12389)| `MGGRFTH`| | | | | | | 
| **`PGGRFTH`**| _Equivalent_ <br/>(12390/12391)| `PGGRFTH`| | | | | | | 
| **`GGRFTH`**| _Equivalent_ <br/>(12392/12393)| `GGRFTH`| | | | | | | 
| **`MGGRMTH`**| _Equivalent_ <br/>(12394/12395)| `MGGRMTH`| | | | | | | 
| **`PGGRMTH`**| _Equivalent_ <br/>(12396/12397)| `PGGRMTH`| | | | | | | 
| **`GGRMTH`**| _Equivalent_ <br/>(12398/12399)| `GGRMTH`| | | | | | | 
| **`MGGRPRN`**| _Equivalent_ <br/>(12400/12401)| `MGGRPRN`| | | | | | | 
| **`PGGRPRN`**| _Equivalent_ <br/>(12402/12403)| `PGGRPRN`| | | | | | | 
| **`GGRPRN`**| _Equivalent_ <br/>(12404/12405)| `GGRPRN`| | | | | | | 
| **`GRNDDAU`**| _Equivalent_ <br/>(12406/12407)| `GRNDDAU`| | | | | | | 
| **`GRNDSON`**| _Equivalent_ <br/>(12408/12409)| `GRNDSON`| | | | | | | 
| **`GRNDCHILD`**| _Equivalent_ <br/>(12410/12411)| `GRNDCHILD`| | | | | | | 
| **`MGRFTH`**| _Equivalent_ <br/>(12412/12413)| `MGRFTH`| | | | | | | 
| **`PGRFTH`**| _Equivalent_ <br/>(12414/12415)| `PGRFTH`| | | | | | | 
| **`GRFTH`**| _Equivalent_ <br/>(12416/12417)| `GRFTH`| | | | | | | 
| **`MGRMTH`**| _Equivalent_ <br/>(12418/12419)| `MGRMTH`| | | | | | | 
| **`PGRMTH`**| _Equivalent_ <br/>(12420/12421)| `PGRMTH`| | | | | | | 
| **`GRMTH`**| _Equivalent_ <br/>(12422/12423)| `GRMTH`| | | | | | | 
| **`MGRPRN`**| _Equivalent_ <br/>(12424/12425)| `MGRPRN`| | | | | | | 
| **`PGRPRN`**| _Equivalent_ <br/>(12426/12427)| `PGRPRN`| | | | | | | 
| **`GRPRN`**| _Equivalent_ <br/>(12428/12429)| `GRPRN`| | | | | | | 
| **`DAUINLAW`**| _Equivalent_ <br/>(12430/12431)| `DAUINLAW`| | | | | | | 
| **`SONINLAW`**| _Equivalent_ <br/>(12432/12433)| `SONINLAW`| | | | | | | 
| **`CHLDINLAW`**| _Equivalent_ <br/>(12434/12435)| `CHLDINLAW`| | | | | | | 
| **`FTHINLAW`**| _Equivalent_ <br/>(12436/12437)| `FTHINLAW`| | | | | | | 
| **`MTHINLAW`**| _Equivalent_ <br/>(12438/12439)| `MTHINLAW`| | | | | | | 
| **`PRNINLAW`**| _Equivalent_ <br/>(12440/12441)| `PRNINLAW`| | | | | | | 
| **`BROINLAW`**| _Equivalent_ <br/>(12442/12443)| `BROINLAW`| | | | | | | 
| **`SISINLAW`**| _Equivalent_ <br/>(12444/12445)| `SISINLAW`| | | | | | | 
| **`SIBINLAW`**| _Equivalent_ <br/>(12446/12447)| `SIBINLAW`| | | | | | | 
| **`INLAW`**| _Equivalent_ <br/>(12448/12449)| `INLAW`| | | | | | | 
| **`NEPHEW`**| _Equivalent_ <br/>(12450/12451)| `NEPHEW`| | | | | | | 
| **`NIECE`**| _Equivalent_ <br/>(12452/12453)| `NIECE`| | | | | | | 
| **`NIENEPH`**| _Equivalent_ <br/>(12454/12455)| `NIENEPH`| | | | | | | 
| **`MUNCLE`**| _Equivalent_ <br/>(12456/12457)| `MUNCLE`| | | | | | | 
| **`PUNCLE`**| _Equivalent_ <br/>(12458/12459)| `PUNCLE`| | | | | | | 
| **`UNCLE`**| _Equivalent_ <br/>(12460/12461)| `UNCLE`| | | | | | | 
| **`EXT`**| _Equivalent_ <br/>(12462/12463)| `EXT`| | | | | | | 
| **`ADOPTF`**| _Equivalent_ <br/>(12464/12465)| `ADOPTF`| | | | | | | 
| **`ADOPTM`**| _Equivalent_ <br/>(12466/12467)| `ADOPTM`| | | | | | | 
| **`ADOPTP`**| _Equivalent_ <br/>(12468/12469)| `ADOPTP`| | | | | | | 
| **`FTHFOST`**| _Equivalent_ <br/>(12470/12471)| `FTHFOST`| | | | | | | 
| **`NFTHF`**| _Equivalent_ <br/>(12472/12473)| `NFTHF`| | | | | | | 
| **`NFTH`**| _Equivalent_ <br/>(12474/12475)| `NFTH`| | | | | | | 
| **`STPFTH`**| _Equivalent_ <br/>(12476/12477)| `STPFTH`| | | | | | | 
| **`FTH`**| _Equivalent_ <br/>(12478/12479)| `FTH`| | | | | | | 
| **`GESTM`**| _Equivalent_ <br/>(12480/12481)| `GESTM`| | | | | | | 
| **`MTHFOST`**| _Equivalent_ <br/>(12482/12483)| `MTHFOST`| | | | | | | 
| **`NMTHF`**| _Equivalent_ <br/>(12484/12485)| `NMTHF`| | | | | | | 
| **`NMTH`**| _Equivalent_ <br/>(12486/12487)| `NMTH`| | | | | | | 
| **`STPMTH`**| _Equivalent_ <br/>(12488/12489)| `STPMTH`| | | | | | | 
| **`MTH`**| _Equivalent_ <br/>(12490/12491)| `MTH`| | | | | | | 
| **`NPRN`**| _Equivalent_ <br/>(12492/12493)| `NPRN`| | | | | | | 
| **`PRNFOST`**| _Equivalent_ <br/>(12494/12495)| `PRNFOST`| | | | | | | 
| **`STPPRN`**| _Equivalent_ <br/>(12496/12497)| `STPPRN`| | | | | | | 
| **`PRN`**| _Equivalent_ <br/>(12498/12499)| `PRN`| | | | | | | 
| **`HBRO`**| _Equivalent_ <br/>(12500/12501)| `HBRO`| | | | | | | 
| **`FTWINBRO`**| _Equivalent_ <br/>(12502/12503)| `FTWINBRO`| | | | | | | 
| **`ITWINBRO`**| _Equivalent_ <br/>(12504/12505)| `ITWINBRO`| | | | | | | 
| **`TWINBRO`**| _Equivalent_ <br/>(12506/12507)| `TWINBRO`| | | | | | | 
| **`NBRO`**| _Equivalent_ <br/>(12508/12509)| `NBRO`| | | | | | | 
| **`STPBRO`**| _Equivalent_ <br/>(12510/12511)| `STPBRO`| | | | | | | 
| **`BRO`**| _Equivalent_ <br/>(12512/12513)| `BRO`| | | | | | | 
| **`HSIS`**| _Equivalent_ <br/>(12514/12515)| `HSIS`| | | | | | | 
| **`HSIB`**| _Equivalent_ <br/>(12516/12517)| `HSIB`| | | | | | | 
| **`FTWINSIS`**| _Equivalent_ <br/>(12518/12519)| `FTWINSIS`| | | | | | | 
| **`ITWINSIS`**| _Equivalent_ <br/>(12520/12521)| `ITWINSIS`| | | | | | | 
| **`TWINSIS`**| _Equivalent_ <br/>(12522/12523)| `TWINSIS`| | | | | | | 
| **`NSIS`**| _Equivalent_ <br/>(12524/12525)| `NSIS`| | | | | | | 
| **`FTWIN`**| _Equivalent_ <br/>(12526/12527)| `FTWIN`| | | | | | | 
| **`ITWIN`**| _Equivalent_ <br/>(12528/12529)| `ITWIN`| | | | | | | 
| **`TWIN`**| _Equivalent_ <br/>(12530/12531)| `TWIN`| | | | | | | 
| **`NSIB`**| _Equivalent_ <br/>(12532/12533)| `NSIB`| | | | | | | 
| **`STPSIS`**| _Equivalent_ <br/>(12534/12535)| `STPSIS`| | | | | | | 
| **`SIS`**| _Equivalent_ <br/>(12536/12537)| `SIS`| | | | | | | 
| **`STPSIB`**| _Equivalent_ <br/>(12538/12539)| `STPSIB`| | | | | | | 
| **`SIB`**| _Equivalent_ <br/>(12540/12541)| `SIB`| | | | | | | 
| **`DOMPART`**| _Equivalent_ <br/>(12542/12543)| `DOMPART`| | | | | | | 
| **`FMRSPS`**| _Equivalent_ <br/>(12544/12545)| `FMRSPS`| | | | | | | 
| **`HUSB`**| _Equivalent_ <br/>(12546/12547)| `HUSB`| | | | | | | 
| **`WIFE`**| _Equivalent_ <br/>(12548/12549)| `WIFE`| | | | | | | 
| **`SPS`**| _Equivalent_ <br/>(12550/12551)| `SPS`| | | | | | | 
| **`SIGOTHR`**| _Equivalent_ <br/>(12552/12553)| `SIGOTHR`| | | | | | | 
| **`FAMMEMB`**| _Equivalent_ <br/>(12554/12555)| `FAMMEMB`| | | | | | | 
| **`FRND`**| _Equivalent_ <br/>(12556/12557)| `FRND`| | | | | | | 
| **`NBOR`**| _Equivalent_ <br/>(12558/12559)| `NBOR`| | | | | | | 
| **`ONESELF`**| _Equivalent_ <br/>(12560/12561)| `ONESELF`| | | | | | | 
| **`ROOM`**| _Equivalent_ <br/>(12562/12563)| `ROOM`| | | | | | | 
| *120 of 121 codes used* <br/>remaining codes:<br/>| | *109 of 121 codes used* <br/>remaining codes:<br/>`BP`, `C`, `CP`, `E`, `EP`, `F`, `I`, `N`, `O`, `PR`, `S`, `U`| | | | | | 

