Comparison of 
Generated at Tuesday, April 1, 2025 1:39:11 PM

### PatientRelationshipType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | PatientRelationshipType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/relatedperson-relationshiptype` |
| Version | 3.0.2 |
| Description | A set of codes that can be used to indicate the relationship between a Patient and a Related Person. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1436` |
| Database Concept Count | `121` |
| Database Active Concept Count | `121` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/RelatedPerson` | `RelatedPerson.relationship` | `http://hl7.org/fhir/ValueSet/relatedperson-relationshiptype` | `Preferred` | The nature of the relationship |

### Referenced Systems

* `http://hl7.org/fhir/v2/0131`
* `http://hl7.org/fhir/v3/RoleCode`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [PatientRelationshipType](/docs/R2/ValueSets/PatientRelationshipType.md)<br/> `http://hl7.org/fhir/ValueSet/relatedperson-relationshiptype\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `1303`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1304`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PatientRelationshipType](/docs/R3/ValueSets/PatientRelationshipType.md)<br/> `http://hl7.org/fhir/ValueSet/relatedperson-relationshiptype\|3.0.2` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set PatientRelationshipType from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 PatientRelationshipType](/docs/R2/ValueSets/PatientRelationshipType.md)| Relationship | R3 PatientRelationshipType| Relationship | *No Map* | Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v2/0131`
| | | **`BP`**| | | | | | | 
| | | **`C`**| | | | | | | 
| | | **`CP`**| | | | | | | 
| | | **`E`**| | | | | | | 
| | | **`EP`**| | | | | | | 
| | | **`F`**| | | | | | | 
| | | **`I`**| | | | | | | 
| | | **`N`**| | | | | | | 
| | | **`O`**| | | | | | | 
| | | **`PR`**| | | | | | | 
| | | **`S`**| | | | | | | 
| | | **`U`**| | | | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/RoleCode`
| `FAMMEMB`| _Equivalent_ <br/>(12554/12555)| **`FAMMEMB`**| | | | | | | 
| `CHILD`| _Equivalent_ <br/>(12374/12375)| **`CHILD`**| | | | | | | 
| `CHLDADOPT`| _Equivalent_ <br/>(12350/12351)| **`CHLDADOPT`**| | | | | | | 
| `DAUADOPT`| _Equivalent_ <br/>(12346/12347)| **`DAUADOPT`**| | | | | | | 
| `SONADOPT`| _Equivalent_ <br/>(12348/12349)| **`SONADOPT`**| | | | | | | 
| `CHLDFOST`| _Equivalent_ <br/>(12356/12357)| **`CHLDFOST`**| | | | | | | 
| `DAUFOST`| _Equivalent_ <br/>(12352/12353)| **`DAUFOST`**| | | | | | | 
| `SONFOST`| _Equivalent_ <br/>(12354/12355)| **`SONFOST`**| | | | | | | 
| `DAUC`| _Equivalent_ <br/>(12362/12363)| **`DAUC`**| | | | | | | 
| `DAU`| _Equivalent_ <br/>(12358/12359)| **`DAU`**| | | | | | | 
| `STPDAU`| _Equivalent_ <br/>(12360/12361)| **`STPDAU`**| | | | | | | 
| `NCHILD`| _Equivalent_ <br/>(12366/12367)| **`NCHILD`**| | | | | | | 
| `SON`| _Equivalent_ <br/>(12364/12365)| **`SON`**| | | | | | | 
| `SONC`| _Equivalent_ <br/>(12370/12371)| **`SONC`**| | | | | | | 
| `STPSON`| _Equivalent_ <br/>(12368/12369)| **`STPSON`**| | | | | | | 
| `STPCHLD`| _Equivalent_ <br/>(12372/12373)| **`STPCHLD`**| | | | | | | 
| `EXT`| _Equivalent_ <br/>(12462/12463)| **`EXT`**| | | | | | | 
| `AUNT`| _Equivalent_ <br/>(12380/12381)| **`AUNT`**| | | | | | | 
| `MAUNT`| _Equivalent_ <br/>(12376/12377)| **`MAUNT`**| | | | | | | 
| `PAUNT`| _Equivalent_ <br/>(12378/12379)| **`PAUNT`**| | | | | | | 
| `COUSN`| _Equivalent_ <br/>(12386/12387)| **`COUSN`**| | | | | | | 
| `MCOUSN`| _Equivalent_ <br/>(12382/12383)| **`MCOUSN`**| | | | | | | 
| `PCOUSN`| _Equivalent_ <br/>(12384/12385)| **`PCOUSN`**| | | | | | | 
| `GGRPRN`| _Equivalent_ <br/>(12404/12405)| **`GGRPRN`**| | | | | | | 
| `GGRFTH`| _Equivalent_ <br/>(12392/12393)| **`GGRFTH`**| | | | | | | 
| `MGGRFTH`| _Equivalent_ <br/>(12388/12389)| **`MGGRFTH`**| | | | | | | 
| `PGGRFTH`| _Equivalent_ <br/>(12390/12391)| **`PGGRFTH`**| | | | | | | 
| `GGRMTH`| _Equivalent_ <br/>(12398/12399)| **`GGRMTH`**| | | | | | | 
| `MGGRMTH`| _Equivalent_ <br/>(12394/12395)| **`MGGRMTH`**| | | | | | | 
| `PGGRMTH`| _Equivalent_ <br/>(12396/12397)| **`PGGRMTH`**| | | | | | | 
| `MGGRPRN`| _Equivalent_ <br/>(12400/12401)| **`MGGRPRN`**| | | | | | | 
| `PGGRPRN`| _Equivalent_ <br/>(12402/12403)| **`PGGRPRN`**| | | | | | | 
| `GRNDCHILD`| _Equivalent_ <br/>(12410/12411)| **`GRNDCHILD`**| | | | | | | 
| `GRNDDAU`| _Equivalent_ <br/>(12406/12407)| **`GRNDDAU`**| | | | | | | 
| `GRNDSON`| _Equivalent_ <br/>(12408/12409)| **`GRNDSON`**| | | | | | | 
| `GRPRN`| _Equivalent_ <br/>(12428/12429)| **`GRPRN`**| | | | | | | 
| `GRFTH`| _Equivalent_ <br/>(12416/12417)| **`GRFTH`**| | | | | | | 
| `MGRFTH`| _Equivalent_ <br/>(12412/12413)| **`MGRFTH`**| | | | | | | 
| `PGRFTH`| _Equivalent_ <br/>(12414/12415)| **`PGRFTH`**| | | | | | | 
| `GRMTH`| _Equivalent_ <br/>(12422/12423)| **`GRMTH`**| | | | | | | 
| `MGRMTH`| _Equivalent_ <br/>(12418/12419)| **`MGRMTH`**| | | | | | | 
| `PGRMTH`| _Equivalent_ <br/>(12420/12421)| **`PGRMTH`**| | | | | | | 
| `MGRPRN`| _Equivalent_ <br/>(12424/12425)| **`MGRPRN`**| | | | | | | 
| `PGRPRN`| _Equivalent_ <br/>(12426/12427)| **`PGRPRN`**| | | | | | | 
| `INLAW`| _Equivalent_ <br/>(12448/12449)| **`INLAW`**| | | | | | | 
| `CHLDINLAW`| _Equivalent_ <br/>(12434/12435)| **`CHLDINLAW`**| | | | | | | 
| `DAUINLAW`| _Equivalent_ <br/>(12430/12431)| **`DAUINLAW`**| | | | | | | 
| `SONINLAW`| _Equivalent_ <br/>(12432/12433)| **`SONINLAW`**| | | | | | | 
| `PRNINLAW`| _Equivalent_ <br/>(12440/12441)| **`PRNINLAW`**| | | | | | | 
| `FTHINLAW`| _Equivalent_ <br/>(12436/12437)| **`FTHINLAW`**| | | | | | | 
| `MTHINLAW`| _Equivalent_ <br/>(12438/12439)| **`MTHINLAW`**| | | | | | | 
| `SIBINLAW`| _Equivalent_ <br/>(12446/12447)| **`SIBINLAW`**| | | | | | | 
| `BROINLAW`| _Equivalent_ <br/>(12442/12443)| **`BROINLAW`**| | | | | | | 
| `SISINLAW`| _Equivalent_ <br/>(12444/12445)| **`SISINLAW`**| | | | | | | 
| `NIENEPH`| _Equivalent_ <br/>(12454/12455)| **`NIENEPH`**| | | | | | | 
| `NEPHEW`| _Equivalent_ <br/>(12450/12451)| **`NEPHEW`**| | | | | | | 
| `NIECE`| _Equivalent_ <br/>(12452/12453)| **`NIECE`**| | | | | | | 
| `UNCLE`| _Equivalent_ <br/>(12460/12461)| **`UNCLE`**| | | | | | | 
| `MUNCLE`| _Equivalent_ <br/>(12456/12457)| **`MUNCLE`**| | | | | | | 
| `PUNCLE`| _Equivalent_ <br/>(12458/12459)| **`PUNCLE`**| | | | | | | 
| `PRN`| _Equivalent_ <br/>(12498/12499)| **`PRN`**| | | | | | | 
| `ADOPTP`| _Equivalent_ <br/>(12468/12469)| **`ADOPTP`**| | | | | | | 
| `ADOPTF`| _Equivalent_ <br/>(12464/12465)| **`ADOPTF`**| | | | | | | 
| `ADOPTM`| _Equivalent_ <br/>(12466/12467)| **`ADOPTM`**| | | | | | | 
| `FTH`| _Equivalent_ <br/>(12478/12479)| **`FTH`**| | | | | | | 
| `FTHFOST`| _Equivalent_ <br/>(12470/12471)| **`FTHFOST`**| | | | | | | 
| `NFTH`| _Equivalent_ <br/>(12474/12475)| **`NFTH`**| | | | | | | 
| `NFTHF`| _Equivalent_ <br/>(12472/12473)| **`NFTHF`**| | | | | | | 
| `STPFTH`| _Equivalent_ <br/>(12476/12477)| **`STPFTH`**| | | | | | | 
| `MTH`| _Equivalent_ <br/>(12490/12491)| **`MTH`**| | | | | | | 
| `GESTM`| _Equivalent_ <br/>(12480/12481)| **`GESTM`**| | | | | | | 
| `MTHFOST`| _Equivalent_ <br/>(12482/12483)| **`MTHFOST`**| | | | | | | 
| `NMTH`| _Equivalent_ <br/>(12486/12487)| **`NMTH`**| | | | | | | 
| `NMTHF`| _Equivalent_ <br/>(12484/12485)| **`NMTHF`**| | | | | | | 
| `STPMTH`| _Equivalent_ <br/>(12488/12489)| **`STPMTH`**| | | | | | | 
| `NPRN`| _Equivalent_ <br/>(12492/12493)| **`NPRN`**| | | | | | | 
| `PRNFOST`| _Equivalent_ <br/>(12494/12495)| **`PRNFOST`**| | | | | | | 
| `STPPRN`| _Equivalent_ <br/>(12496/12497)| **`STPPRN`**| | | | | | | 
| `SIB`| _Equivalent_ <br/>(12540/12541)| **`SIB`**| | | | | | | 
| `BRO`| _Equivalent_ <br/>(12512/12513)| **`BRO`**| | | | | | | 
| `HBRO`| _Equivalent_ <br/>(12500/12501)| **`HBRO`**| | | | | | | 
| `NBRO`| _Equivalent_ <br/>(12508/12509)| **`NBRO`**| | | | | | | 
| `TWINBRO`| _Equivalent_ <br/>(12506/12507)| **`TWINBRO`**| | | | | | | 
| `FTWINBRO`| _Equivalent_ <br/>(12502/12503)| **`FTWINBRO`**| | | | | | | 
| `ITWINBRO`| _Equivalent_ <br/>(12504/12505)| **`ITWINBRO`**| | | | | | | 
| `STPBRO`| _Equivalent_ <br/>(12510/12511)| **`STPBRO`**| | | | | | | 
| `HSIB`| _Equivalent_ <br/>(12516/12517)| **`HSIB`**| | | | | | | 
| `HSIS`| _Equivalent_ <br/>(12514/12515)| **`HSIS`**| | | | | | | 
| `NSIB`| _Equivalent_ <br/>(12532/12533)| **`NSIB`**| | | | | | | 
| `NSIS`| _Equivalent_ <br/>(12524/12525)| **`NSIS`**| | | | | | | 
| `TWINSIS`| _Equivalent_ <br/>(12522/12523)| **`TWINSIS`**| | | | | | | 
| `FTWINSIS`| _Equivalent_ <br/>(12518/12519)| **`FTWINSIS`**| | | | | | | 
| `ITWINSIS`| _Equivalent_ <br/>(12520/12521)| **`ITWINSIS`**| | | | | | | 
| `TWIN`| _Equivalent_ <br/>(12530/12531)| **`TWIN`**| | | | | | | 
| `FTWIN`| _Equivalent_ <br/>(12526/12527)| **`FTWIN`**| | | | | | | 
| `ITWIN`| _Equivalent_ <br/>(12528/12529)| **`ITWIN`**| | | | | | | 
| `SIS`| _Equivalent_ <br/>(12536/12537)| **`SIS`**| | | | | | | 
| `STPSIS`| _Equivalent_ <br/>(12534/12535)| **`STPSIS`**| | | | | | | 
| `STPSIB`| _Equivalent_ <br/>(12538/12539)| **`STPSIB`**| | | | | | | 
| `SIGOTHR`| _Equivalent_ <br/>(12552/12553)| **`SIGOTHR`**| | | | | | | 
| `DOMPART`| _Equivalent_ <br/>(12542/12543)| **`DOMPART`**| | | | | | | 
| `FMRSPS`| _Equivalent_ <br/>(12544/12545)| **`FMRSPS`**| | | | | | | 
| `SPS`| _Equivalent_ <br/>(12550/12551)| **`SPS`**| | | | | | | 
| `HUSB`| _Equivalent_ <br/>(12546/12547)| **`HUSB`**| | | | | | | 
| `WIFE`| _Equivalent_ <br/>(12548/12549)| **`WIFE`**| | | | | | | 
| `FRND`| _Equivalent_ <br/>(12556/12557)| **`FRND`**| | | | | | | 
| `NBOR`| _Equivalent_ <br/>(12558/12559)| **`NBOR`**| | | | | | | 
| `ONESELF`| _Equivalent_ <br/>(12560/12561)| **`ONESELF`**| | | | | | | 
| `ROOM`| _Equivalent_ <br/>(12562/12563)| **`ROOM`**| | | | | | | 
| *109 of 121 codes used* | | *121 of 121 codes used* | | | | | | 

