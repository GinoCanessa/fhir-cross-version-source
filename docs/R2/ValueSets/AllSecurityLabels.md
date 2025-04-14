Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### All Security Labels

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | All Security Labels |
| Canonical URL | `http://hl7.org/fhir/ValueSet/security-labels` |
| Version | 1.0.2 |
| Description | A single value set for all security labels defined by FHIR. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `359` |
| Database Concept Count | `237` |
| Database Active Concept Count | `224` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Meta` | `Meta.security` | `http://hl7.org/fhir/ValueSet/security-labels` | `Extensible` | Security Labels applied to this resource |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.object.securityLabel` | `http://hl7.org/fhir/ValueSet/security-labels` | `Extensible` | Security labels applied to the object |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.securityLabel` | `http://hl7.org/fhir/ValueSet/security-labels` | `Extensible` | Document security-tags |

### Referenced Systems

* `http://hl7.org/fhir/v3/Confidentiality`
* `http://hl7.org/fhir/v3/ActCode`
* `http://hl7.org/fhir/v3/ObservationValue`
* `http://hl7.org/fhir/v3/ActReason`
* `http://hl7.org/fhir/v3/ActUSPrivacyLaw`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [All Security Labels](/docs/R2/ValueSets/AllSecurityLabels.md)<br/> `http://hl7.org/fhir/ValueSet/security-labels\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `53`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `212`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [All Security Labels](/docs/R3/ValueSets/AllSecurityLabels.md)<br/> `http://hl7.org/fhir/ValueSet/security-labels\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `389`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `612`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [All Security Labels](/docs/R4/ValueSets/AllSecurityLabels.md)<br/> `http://hl7.org/fhir/ValueSet/security-labels\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set All Security Labels from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 All Security Labels| Relationship | [R3 All Security Labels](/docs/R3/ValueSets/AllSecurityLabels.md)| Relationship | [R4 All Security Labels](/docs/R4/ValueSets/AllSecurityLabels.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/v3/Confidentiality`
| **`L`**| _Equivalent_ <br/>(292/1743)| `L`| →→→→ _Equivalent_ →→→→ <br/>(3257)<hr/>←←←← __ ←←←← <br/>() | `L`| | | | | 
| **`L`**| _Equivalent_ <br/>(292/1743)| `L`| _Equivalent_ <br/>(3422/5675)| `L`| | | | | 
| **`M`**| _Equivalent_ <br/>(293/1744)| `M`| →→→→ _Equivalent_ →→→→ <br/>(3255)<hr/>←←←← __ ←←←← <br/>() | `M`| | | | | 
| **`M`**| _Equivalent_ <br/>(293/1744)| `M`| _Equivalent_ <br/>(3426/5673)| `M`| | | | | 
| **`N`**| _Equivalent_ <br/>(294/1745)| `N`| →→→→ _Equivalent_ →→→→ <br/>(3254)<hr/>←←←← __ ←←←← <br/>() | `N`| | | | | 
| **`N`**| _Equivalent_ <br/>(294/1745)| `N`| _Equivalent_ <br/>(3424/5672)| `N`| | | | | 
| **`R`**| _Equivalent_ <br/>(295/1746)| `R`| →→→→ _Equivalent_ →→→→ <br/>(3256)<hr/>←←←← __ ←←←← <br/>() | `R`| | | | | 
| **`R`**| _Equivalent_ <br/>(295/1746)| `R`| _Equivalent_ <br/>(3421/5674)| `R`| | | | | 
| **`U`**| _Equivalent_ <br/>(298/1747)| `U`| →→→→ _Equivalent_ →→→→ <br/>(3252)<hr/>←←←← __ ←←←← <br/>() | `U`| | | | | 
| **`U`**| _Equivalent_ <br/>(298/1747)| `U`| _Equivalent_ <br/>(3425/5670)| `U`| | | | | 
| **`V`**| _Equivalent_ <br/>(299/1748)| `V`| →→→→ _Equivalent_ →→→→ <br/>(3253)<hr/>←←←← __ ←←←← <br/>() | `V`| | | | | 
| **`V`**| _Equivalent_ <br/>(299/1748)| `V`| _Equivalent_ <br/>(3423/5671)| `V`| | | | | 
| **`_Confidentiality`**| | | | | | | | | 
| **`B`**| | | | | | | | | 
| **`D`**| | | | | | | | | 
| **`I`**| | | | | | | | | 
| **`ETH`**| | | | | | | | | 
| **`HIV`**| | | | | | | | | 
| **`PSY`**| | | | | | | | | 
| **`SDV`**| | | | | | | | | 
| **`C`**| | | | | | | | | 
| **`S`**| | | | | | | | | 
| **`T`**| | | | | | | | | 
| <td colspan="8">**R2** System: `http://hl7.org/fhir/v3/ActCode`
| **`ETH`**| _Equivalent_ <br/>(331/1691)| `ETH`| →→→→ _Equivalent_ →→→→ <br/>(3321)<hr/>←←←← __ ←←←← <br/>() | `ETH`| | | | | 
| **`ETH`**| _Equivalent_ <br/>(331/1691)| `ETH`| _Equivalent_ <br/>(3505/5756)| `ETH`| | | | | 
| **`GDIS`**| _Equivalent_ <br/>(332/1692)| `GDIS`| →→→→ _Equivalent_ →→→→ <br/>(3330)<hr/>←←←← __ ←←←← <br/>() | `GDIS`| | | | | 
| **`GDIS`**| _Equivalent_ <br/>(332/1692)| `GDIS`| _Equivalent_ <br/>(3492/5765)| `GDIS`| | | | | 
| **`HIV`**| _Equivalent_ <br/>(334/1694)| `HIV`| →→→→ _Equivalent_ →→→→ <br/>(3344)<hr/>←←←← __ ←←←← <br/>() | `HIV`| | | | | 
| **`HIV`**| _Equivalent_ <br/>(334/1694)| `HIV`| _Equivalent_ <br/>(3500/5779)| `HIV`| | | | | 
| **`PSY`**| _Equivalent_ <br/>(364/1726)| `PSY`| →→→→ _Equivalent_ →→→→ <br/>(3337)<hr/>←←←← __ ←←←← <br/>() | `PSY`| | | | | 
| **`PSY`**| _Equivalent_ <br/>(364/1726)| `PSY`| _Equivalent_ <br/>(3515/5772)| `PSY`| | | | | 
| **`SCA`**| _Equivalent_ <br/>(371/1733)| `SCA`| →→→→ _Equivalent_ →→→→ <br/>(3374)<hr/>←←←← __ ←←←← <br/>() | `SCA`| | | | | 
| **`SCA`**| _Equivalent_ <br/>(371/1733)| `SCA`| _Equivalent_ <br/>(3480/5809)| `SCA`| | | | | 
| **`SDV`**| _Equivalent_ <br/>(372/1734)| `SDV`| →→→→ _Equivalent_ →→→→ <br/>(3354)<hr/>←←←← __ ←←←← <br/>() | `SDV`| | | | | 
| **`SDV`**| _Equivalent_ <br/>(372/1734)| `SDV`| _Equivalent_ <br/>(3503/5789)| `SDV`| | | | | 
| **`SEX`**| _Equivalent_ <br/>(373/1735)| `SEX`| →→→→ _Equivalent_ →→→→ <br/>(3313)<hr/>←←←← __ ←←←← <br/>() | `SEX`| | | | | 
| **`SEX`**| _Equivalent_ <br/>(373/1735)| `SEX`| _Equivalent_ <br/>(3490/5748)| `SEX`| | | | | 
| **`STD`**| _Equivalent_ <br/>(376/1739)| `STD`| →→→→ _Equivalent_ →→→→ <br/>(3378)<hr/>←←←← __ ←←←← <br/>() | `STD`| | | | | 
| **`STD`**| _Equivalent_ <br/>(376/1739)| `STD`| _Equivalent_ <br/>(3499/5813)| `STD`| | | | | 
| **`TBOO`**| _Equivalent_ <br/>(378/1741)| `TBOO`| →→→→ _Equivalent_ →→→→ <br/>(3365)<hr/>←←←← __ ←←←← <br/>() | `TBOO`| | | | | 
| **`TBOO`**| _Equivalent_ <br/>(378/1741)| `TBOO`| _Equivalent_ <br/>(3477/5800)| `TBOO`| | | | | 
| **`SICKLE`**| _Equivalent_ <br/>(374/1736)| `SICKLE`| →→→→ _Equivalent_ →→→→ <br/>(3369)<hr/>←←←← __ ←←←← <br/>() | `SICKLE`| | | | | 
| **`SICKLE`**| _Equivalent_ <br/>(374/1736)| `SICKLE`| _Equivalent_ <br/>(3475/5804)| `SICKLE`| | | | | 
| **`DEMO`**| _Equivalent_ <br/>(321/1679)| `DEMO`| →→→→ _Equivalent_ →→→→ <br/>(3343)<hr/>←←←← __ ←←←← <br/>() | `DEMO`| | | | | 
| **`DEMO`**| _Equivalent_ <br/>(321/1679)| `DEMO`| _Equivalent_ <br/>(3537/5778)| `DEMO`| | | | | 
| **`DOB`**| _Equivalent_ <br/>(323/1681)| `DOB`| →→→→ _Equivalent_ →→→→ <br/>(3350)<hr/>←←←← __ ←←←← <br/>() | `DOB`| | | | | 
| **`DOB`**| _Equivalent_ <br/>(323/1681)| `DOB`| _Equivalent_ <br/>(3542/5785)| `DOB`| | | | | 
| **`GENDER`**| _Equivalent_ <br/>(333/1693)| `GENDER`| →→→→ _Equivalent_ →→→→ <br/>(3351)<hr/>←←←← __ ←←←← <br/>() | `GENDER`| | | | | 
| **`GENDER`**| _Equivalent_ <br/>(333/1693)| `GENDER`| _Equivalent_ <br/>(3510/5786)| `GENDER`| | | | | 
| **`LIVARG`**| _Equivalent_ <br/>(337/1698)| `LIVARG`| →→→→ _Equivalent_ →→→→ <br/>(3311)<hr/>←←←← __ ←←←← <br/>() | `LIVARG`| | | | | 
| **`LIVARG`**| _Equivalent_ <br/>(337/1698)| `LIVARG`| _Equivalent_ <br/>(3508/5746)| `LIVARG`| | | | | 
| **`MARST`**| _Equivalent_ <br/>(339/1700)| `MARST`| →→→→ _Equivalent_ →→→→ <br/>(3379)<hr/>←←←← __ ←←←← <br/>() | `MARST`| | | | | 
| **`MARST`**| _Equivalent_ <br/>(339/1700)| `MARST`| _Equivalent_ <br/>(3530/5814)| `MARST`| | | | | 
| **`RACE`**| _Equivalent_ <br/>(365/1727)| `RACE`| →→→→ _Equivalent_ →→→→ <br/>(3326)<hr/>←←←← __ ←←←← <br/>() | `RACE`| | | | | 
| **`RACE`**| _Equivalent_ <br/>(365/1727)| `RACE`| _Equivalent_ <br/>(3523/5761)| `RACE`| | | | | 
| **`REL`**| _Equivalent_ <br/>(367/1729)| `REL`| →→→→ _Equivalent_ →→→→ <br/>(3316)<hr/>←←←← __ ←←←← <br/>() | `REL`| | | | | 
| **`REL`**| _Equivalent_ <br/>(367/1729)| `REL`| _Equivalent_ <br/>(3545/5751)| `REL`| | | | | 
| **`B`**| _Equivalent_ <br/>(310/1667)| `B`| →→→→ _Equivalent_ →→→→ <br/>(3371)<hr/>←←←← __ ←←←← <br/>() | `B`| | | | | 
| **`B`**| _Equivalent_ <br/>(310/1667)| `B`| _Equivalent_ <br/>(3534/5806)| `B`| | | | | 
| **`EMPL`**| _Equivalent_ <br/>(326/1686)| `EMPL`| →→→→ _Equivalent_ →→→→ <br/>(3380)<hr/>←←←← __ ←←←← <br/>() | `EMPL`| | | | | 
| **`EMPL`**| _Equivalent_ <br/>(326/1686)| `EMPL`| _Equivalent_ <br/>(3509/5815)| `EMPL`| | | | | 
| **`LOCIS`**| _Equivalent_ <br/>(338/1699)| `LOCIS`| →→→→ _Equivalent_ →→→→ <br/>(3376)<hr/>←←←← __ ←←←← <br/>() | `LOCIS`| | | | | 
| **`LOCIS`**| _Equivalent_ <br/>(338/1699)| `LOCIS`| _Equivalent_ <br/>(3483/5811)| `LOCIS`| | | | | 
| **`SSP`**| _Equivalent_ <br/>(375/1738)| `SSP`| →→→→ _Equivalent_ →→→→ <br/>(3324)<hr/>←←←← __ ←←←← <br/>() | `SSP`| | | | | 
| **`SSP`**| _Equivalent_ <br/>(375/1738)| `SSP`| _Equivalent_ <br/>(3513/5759)| `SSP`| | | | | 
| **`ADOL`**| _Equivalent_ <br/>(305/1662)| `ADOL`| →→→→ _Equivalent_ →→→→ <br/>(3348)<hr/>←←←← __ ←←←← <br/>() | `ADOL`| | | | | 
| **`ADOL`**| _Equivalent_ <br/>(305/1662)| `ADOL`| _Equivalent_ <br/>(3504/5783)| `ADOL`| | | | | 
| **`CEL`**| _Equivalent_ <br/>(311/1668)| `CEL`| →→→→ _Equivalent_ →→→→ <br/>(3332)<hr/>←←←← __ ←←←← <br/>() | `CEL`| | | | | 
| **`CEL`**| _Equivalent_ <br/>(311/1668)| `CEL`| _Equivalent_ <br/>(3518/5767)| `CEL`| | | | | 
| **`DIA`**| _Equivalent_ <br/>(322/1680)| `DIA`| →→→→ _Equivalent_ →→→→ <br/>(3306)<hr/>←←←← __ ←←←← <br/>() | `DIA`| | | | | 
| **`DIA`**| _Equivalent_ <br/>(322/1680)| `DIA`| _Equivalent_ <br/>(3495/5741)| `DIA`| | | | | 
| **`DRGIS`**| _Equivalent_ <br/>(324/1683)| `DRGIS`| →→→→ _Equivalent_ →→→→ <br/>(3304)<hr/>←←←← __ ←←←← <br/>() | `DRGIS`| | | | | 
| **`DRGIS`**| _Equivalent_ <br/>(324/1683)| `DRGIS`| _Equivalent_ <br/>(3493/5739)| `DRGIS`| | | | | 
| **`EMP`**| _Equivalent_ <br/>(325/1685)| `EMP`| →→→→ _Equivalent_ →→→→ <br/>(3357)<hr/>←←←← __ ←←←← <br/>() | `EMP`| | | | | 
| **`EMP`**| _Equivalent_ <br/>(325/1685)| `EMP`| _Equivalent_ <br/>(3516/5792)| `EMP`| | | | | 
| **`PDS`**| _Equivalent_ <br/>(360/1721)| `PDS`| →→→→ _Equivalent_ →→→→ <br/>(3317)<hr/>←←←← __ ←←←← <br/>() | `PDS`| | | | | 
| **`PDS`**| _Equivalent_ <br/>(360/1721)| `PDS`| _Equivalent_ <br/>(3549/5752)| `PDS`| | | | | 
| **`PRS`**| _Equivalent_ <br/>(362/1724)| `PRS`| →→→→ _Equivalent_ →→→→ <br/>(3349)<hr/>←←←← __ ←←←← <br/>() | `PRS`| | | | | 
| **`PRS`**| _Equivalent_ <br/>(362/1724)| `PRS`| _Equivalent_ <br/>(3543/5784)| `PRS`| | | | | 
| **`HRCOMPT`**| _Equivalent_ <br/>(335/1695)| `HRCOMPT`| →→→→ _Equivalent_ →→→→ <br/>(3301)<hr/>←←←← __ ←←←← <br/>() | `HRCOMPT`| | | | | 
| **`HRCOMPT`**| _Equivalent_ <br/>(335/1695)| `HRCOMPT`| _Equivalent_ <br/>(3485/5736)| `HRCOMPT`| | | | | 
| **`RESCOMPT`**| _Equivalent_ <br/>(368/1730)| `RESCOMPT`| →→→→ _Equivalent_ →→→→ <br/>(3339)<hr/>←←←← __ ←←←← <br/>() | `RESCOMPT`| | | | | 
| **`RESCOMPT`**| _Equivalent_ <br/>(368/1730)| `RESCOMPT`| _Equivalent_ <br/>(3497/5774)| `RESCOMPT`| | | | | 
| **`RMGTCOMPT`**| _Equivalent_ <br/>(369/1731)| `RMGTCOMPT`| →→→→ _Equivalent_ →→→→ <br/>(3329)<hr/>←←←← __ ←←←← <br/>() | `RMGTCOMPT`| | | | | 
| **`RMGTCOMPT`**| _Equivalent_ <br/>(369/1731)| `RMGTCOMPT`| _Equivalent_ <br/>(3527/5764)| `RMGTCOMPT`| | | | | 
| **`COMPT`**| _Equivalent_ <br/>(312/1669)| `COMPT`| →→→→ _Equivalent_ →→→→ <br/>(3375)<hr/>←←←← __ ←←←← <br/>() | `COMPT`| | | | | 
| **`COMPT`**| _Equivalent_ <br/>(312/1669)| `COMPT`| _Equivalent_ <br/>(3502/5810)| `COMPT`| | | | | 
| <td colspan="8">**R2** System: `http://hl7.org/fhir/v3/ObservationValue`
| **`ABSTRED`**| _Equivalent_ <br/>(250/1623)| `ABSTRED`| →→→→ _Equivalent_ →→→→ <br/>(3234)<hr/>←←←← __ ←←←← <br/>() | `ABSTRED`| | | | | 
| **`ABSTRED`**| _Equivalent_ <br/>(250/1623)| `ABSTRED`| _Equivalent_ <br/>(3409/5652)| `ABSTRED`| | | | | 
| **`AGGRED`**| _Equivalent_ <br/>(251/1624)| `AGGRED`| →→→→ _Equivalent_ →→→→ <br/>(3237)<hr/>←←←← __ ←←←← <br/>() | `AGGRED`| | | | | 
| **`AGGRED`**| _Equivalent_ <br/>(251/1624)| `AGGRED`| _Equivalent_ <br/>(3404/5655)| `AGGRED`| | | | | 
| **`ANONYED`**| _Equivalent_ <br/>(252/1625)| `ANONYED`| →→→→ _Equivalent_ →→→→ <br/>(3230)<hr/>←←←← __ ←←←← <br/>() | `ANONYED`| | | | | 
| **`ANONYED`**| _Equivalent_ <br/>(252/1625)| `ANONYED`| _Equivalent_ <br/>(3417/5648)| `ANONYED`| | | | | 
| **`MAPPED`**| _Equivalent_ <br/>(262/1635)| `MAPPED`| →→→→ _Equivalent_ →→→→ <br/>(3224)<hr/>←←←← __ ←←←← <br/>() | `MAPPED`| | | | | 
| **`MAPPED`**| _Equivalent_ <br/>(262/1635)| `MAPPED`| _Equivalent_ <br/>(3413/5642)| `MAPPED`| | | | | 
| **`MASKED`**| _Equivalent_ <br/>(263/1636)| `MASKED`| →→→→ _Equivalent_ →→→→ <br/>(3218)<hr/>←←←← __ ←←←← <br/>() | `MASKED`| | | | | 
| **`MASKED`**| _Equivalent_ <br/>(263/1636)| `MASKED`| _Equivalent_ <br/>(3415/5636)| `MASKED`| | | | | 
| **`PSEUDED`**| _Equivalent_ <br/>(272/1645)| `PSEUDED`| →→→→ _Equivalent_ →→→→ <br/>(3243)<hr/>←←←← __ ←←←← <br/>() | `PSEUDED`| | | | | 
| **`PSEUDED`**| _Equivalent_ <br/>(272/1645)| `PSEUDED`| _Equivalent_ <br/>(3388/5661)| `PSEUDED`| | | | | 
| **`REDACTED`**| _Equivalent_ <br/>(273/1646)| `REDACTED`| →→→→ _Equivalent_ →→→→ <br/>(3231)<hr/>←←←← __ ←←←← <br/>() | `REDACTED`| | | | | 
| **`REDACTED`**| _Equivalent_ <br/>(273/1646)| `REDACTED`| _Equivalent_ <br/>(3397/5649)| `REDACTED`| | | | | 
| **`SUBSETTED`**| _Equivalent_ <br/>(277/1650)| `SUBSETTED`| →→→→ _Equivalent_ →→→→ <br/>(3217)<hr/>←←←← __ ←←←← <br/>() | `SUBSETTED`| | | | | 
| **`SUBSETTED`**| _Equivalent_ <br/>(277/1650)| `SUBSETTED`| _Equivalent_ <br/>(3399/5635)| `SUBSETTED`| | | | | 
| **`SYNTAC`**| _Equivalent_ <br/>(278/1651)| `SYNTAC`| →→→→ _Equivalent_ →→→→ <br/>(3235)<hr/>←←←← __ ←←←← <br/>() | `SYNTAC`| | | | | 
| **`SYNTAC`**| _Equivalent_ <br/>(278/1651)| `SYNTAC`| _Equivalent_ <br/>(3390/5653)| `SYNTAC`| | | | | 
| **`TRSLT`**| _Equivalent_ <br/>(279/1652)| `TRSLT`| →→→→ _Equivalent_ →→→→ <br/>(3222)<hr/>←←←← __ ←←←← <br/>() | `TRSLT`| | | | | 
| **`TRSLT`**| _Equivalent_ <br/>(279/1652)| `TRSLT`| _Equivalent_ <br/>(3401/5640)| `TRSLT`| | | | | 
| **`VERSIONED`**| _Equivalent_ <br/>(282/1655)| `VERSIONED`| →→→→ _Equivalent_ →→→→ <br/>(3239)<hr/>←←←← __ ←←←← <br/>() | `VERSIONED`| | | | | 
| **`VERSIONED`**| _Equivalent_ <br/>(282/1655)| `VERSIONED`| _Equivalent_ <br/>(3403/5657)| `VERSIONED`| | | | | 
| **`CRYTOHASH`**| _Equivalent_ <br/>(255/1628)| `CRYTOHASH`| →→→→ _Equivalent_ →→→→ <br/>(3241)<hr/>←←←← __ ←←←← <br/>() | `CRYTOHASH`| | | | | 
| **`CRYTOHASH`**| _Equivalent_ <br/>(255/1628)| `CRYTOHASH`| _Equivalent_ <br/>(3418/5659)| `CRYTOHASH`| | | | | 
| **`DIGSIG`**| _Equivalent_ <br/>(258/1631)| `DIGSIG`| →→→→ _Equivalent_ →→→→ <br/>(3213)<hr/>←←←← __ ←←←← <br/>() | `DIGSIG`| | | | | 
| **`DIGSIG`**| _Equivalent_ <br/>(258/1631)| `DIGSIG`| _Equivalent_ <br/>(3394/5631)| `DIGSIG`| | | | | 
| **`HRELIABLE`**| _Equivalent_ <br/>(261/1634)| `HRELIABLE`| →→→→ _Equivalent_ →→→→ <br/>(3215)<hr/>←←←← __ ←←←← <br/>() | `HRELIABLE`| | | | | 
| **`HRELIABLE`**| _Equivalent_ <br/>(261/1634)| `HRELIABLE`| _Equivalent_ <br/>(3396/5633)| `HRELIABLE`| | | | | 
| **`RELIABLE`**| _Equivalent_ <br/>(274/1647)| `RELIABLE`| →→→→ _Equivalent_ →→→→ <br/>(3225)<hr/>←←←← __ ←←←← <br/>() | `RELIABLE`| | | | | 
| **`RELIABLE`**| _Equivalent_ <br/>(274/1647)| `RELIABLE`| _Equivalent_ <br/>(3419/5643)| `RELIABLE`| | | | | 
| **`UNCERTREL`**| _Equivalent_ <br/>(280/1653)| `UNCERTREL`| →→→→ _Equivalent_ →→→→ <br/>(3240)<hr/>←←←← __ ←←←← <br/>() | `UNCERTREL`| | | | | 
| **`UNCERTREL`**| _Equivalent_ <br/>(280/1653)| `UNCERTREL`| _Equivalent_ <br/>(3389/5658)| `UNCERTREL`| | | | | 
| **`UNRELIABLE`**| _Equivalent_ <br/>(281/1654)| `UNRELIABLE`| →→→→ _Equivalent_ →→→→ <br/>(3221)<hr/>←←←← __ ←←←← <br/>() | `UNRELIABLE`| | | | | 
| **`UNRELIABLE`**| _Equivalent_ <br/>(281/1654)| `UNRELIABLE`| _Equivalent_ <br/>(3395/5639)| `UNRELIABLE`| | | | | 
| **`CLINAST`**| _Equivalent_ <br/>(253/1626)| `CLINAST`| →→→→ _Equivalent_ →→→→ <br/>(3216)<hr/>←←←← __ ←←←← <br/>() | `CLINAST`| | | | | 
| **`CLINAST`**| _Equivalent_ <br/>(253/1626)| `CLINAST`| _Equivalent_ <br/>(3416/5634)| `CLINAST`| | | | | 
| **`DEVAST`**| _Equivalent_ <br/>(256/1629)| `DEVAST`| →→→→ _Equivalent_ →→→→ <br/>(3220)<hr/>←←←← __ ←←←← <br/>() | `DEVAST`| | | | | 
| **`DEVAST`**| _Equivalent_ <br/>(256/1629)| `DEVAST`| _Equivalent_ <br/>(3391/5638)| `DEVAST`| | | | | 
| **`HCPAST`**| _Equivalent_ <br/>(259/1632)| `HCPAST`| →→→→ _Equivalent_ →→→→ <br/>(3214)<hr/>←←←← __ ←←←← <br/>() | `HCPAST`| | | | | 
| **`HCPAST`**| _Equivalent_ <br/>(259/1632)| `HCPAST`| _Equivalent_ <br/>(3414/5632)| `HCPAST`| | | | | 
| **`PACQAST`**| _Equivalent_ <br/>(264/1637)| `PACQAST`| →→→→ _Equivalent_ →→→→ <br/>(3223)<hr/>←←←← __ ←←←← <br/>() | `PACQAST`| | | | | 
| **`PACQAST`**| _Equivalent_ <br/>(264/1637)| `PACQAST`| _Equivalent_ <br/>(3407/5641)| `PACQAST`| | | | | 
| **`PATAST`**| _Equivalent_ <br/>(266/1639)| `PATAST`| →→→→ _Equivalent_ →→→→ <br/>(3228)<hr/>←←←← __ ←←←← <br/>() | `PATAST`| | | | | 
| **`PATAST`**| _Equivalent_ <br/>(266/1639)| `PATAST`| _Equivalent_ <br/>(3392/5646)| `PATAST`| | | | | 
| **`PAYAST`**| _Equivalent_ <br/>(268/1641)| `PAYAST`| →→→→ _Equivalent_ →→→→ <br/>(3245)<hr/>←←←← __ ←←←← <br/>() | `PAYAST`| | | | | 
| **`PAYAST`**| _Equivalent_ <br/>(268/1641)| `PAYAST`| _Equivalent_ <br/>(3411/5663)| `PAYAST`| | | | | 
| **`PROAST`**| _Equivalent_ <br/>(270/1643)| `PROAST`| →→→→ _Equivalent_ →→→→ <br/>(3229)<hr/>←←←← __ ←←←← <br/>() | `PROAST`| | | | | 
| **`PROAST`**| _Equivalent_ <br/>(270/1643)| `PROAST`| _Equivalent_ <br/>(3410/5647)| `PROAST`| | | | | 
| **`SDMAST`**| _Equivalent_ <br/>(275/1648)| `SDMAST`| →→→→ _Equivalent_ →→→→ <br/>(3238)<hr/>←←←← __ ←←←← <br/>() | `SDMAST`| | | | | 
| **`SDMAST`**| _Equivalent_ <br/>(275/1648)| `SDMAST`| _Equivalent_ <br/>(3398/5656)| `SDMAST`| | | | | 
| **`CLINRPT`**| _Equivalent_ <br/>(254/1627)| `CLINRPT`| →→→→ _Equivalent_ →→→→ <br/>(3233)<hr/>←←←← __ ←←←← <br/>() | `CLINRPT`| | | | | 
| **`CLINRPT`**| _Equivalent_ <br/>(254/1627)| `CLINRPT`| _Equivalent_ <br/>(3402/5651)| `CLINRPT`| | | | | 
| **`DEVRPT`**| _Equivalent_ <br/>(257/1630)| `DEVRPT`| →→→→ _Equivalent_ →→→→ <br/>(3227)<hr/>←←←← __ ←←←← <br/>() | `DEVRPT`| | | | | 
| **`DEVRPT`**| _Equivalent_ <br/>(257/1630)| `DEVRPT`| _Equivalent_ <br/>(3412/5645)| `DEVRPT`| | | | | 
| **`HCPRPT`**| _Equivalent_ <br/>(260/1633)| `HCPRPT`| →→→→ _Equivalent_ →→→→ <br/>(3244)<hr/>←←←← __ ←←←← <br/>() | `HCPRPT`| | | | | 
| **`HCPRPT`**| _Equivalent_ <br/>(260/1633)| `HCPRPT`| _Equivalent_ <br/>(3405/5662)| `HCPRPT`| | | | | 
| **`PACQRPT`**| _Equivalent_ <br/>(265/1638)| `PACQRPT`| →→→→ _Equivalent_ →→→→ <br/>(3236)<hr/>←←←← __ ←←←← <br/>() | `PACQRPT`| | | | | 
| **`PACQRPT`**| _Equivalent_ <br/>(265/1638)| `PACQRPT`| _Equivalent_ <br/>(3408/5654)| `PACQRPT`| | | | | 
| **`PATRPT`**| _Equivalent_ <br/>(267/1640)| `PATRPT`| →→→→ _Equivalent_ →→→→ <br/>(3242)<hr/>←←←← __ ←←←← <br/>() | `PATRPT`| | | | | 
| **`PATRPT`**| _Equivalent_ <br/>(267/1640)| `PATRPT`| _Equivalent_ <br/>(3420/5660)| `PATRPT`| | | | | 
| **`PAYRPT`**| _Equivalent_ <br/>(269/1642)| `PAYRPT`| →→→→ _Equivalent_ →→→→ <br/>(3219)<hr/>←←←← __ ←←←← <br/>() | `PAYRPT`| | | | | 
| **`PAYRPT`**| _Equivalent_ <br/>(269/1642)| `PAYRPT`| _Equivalent_ <br/>(3406/5637)| `PAYRPT`| | | | | 
| **`PRORPT`**| _Equivalent_ <br/>(271/1644)| `PRORPT`| →→→→ _Equivalent_ →→→→ <br/>(3226)<hr/>←←←← __ ←←←← <br/>() | `PRORPT`| | | | | 
| **`PRORPT`**| _Equivalent_ <br/>(271/1644)| `PRORPT`| _Equivalent_ <br/>(3400/5644)| `PRORPT`| | | | | 
| **`SDMRPT`**| _Equivalent_ <br/>(276/1649)| `SDMRPT`| →→→→ _Equivalent_ →→→→ <br/>(3232)<hr/>←←←← __ ←←←← <br/>() | `SDMRPT`| | | | | 
| **`SDMRPT`**| _Equivalent_ <br/>(276/1649)| `SDMRPT`| _Equivalent_ <br/>(3393/5650)| `SDMRPT`| | | | | 
| <td colspan="8">**R2** System: `http://hl7.org/fhir/v3/ActCode`
| **`ANONY`**| _Equivalent_ <br/>(306/1663)| `ANONY`| →→→→ _Equivalent_ →→→→ <br/>(3333)<hr/>←←←← __ ←←←← <br/>() | `ANONY`| | | | | 
| **`ANONY`**| _Equivalent_ <br/>(306/1663)| `ANONY`| _Equivalent_ <br/>(3496/5768)| `ANONY`| | | | | 
| **`AOD`**| _Equivalent_ <br/>(307/1664)| `AOD`| →→→→ _Equivalent_ →→→→ <br/>(3356)<hr/>←←←← __ ←←←← <br/>() | `AOD`| | | | | 
| **`AOD`**| _Equivalent_ <br/>(307/1664)| `AOD`| _Equivalent_ <br/>(3529/5791)| `AOD`| | | | | 
| **`AUDIT`**| _Equivalent_ <br/>(308/1665)| `AUDIT`| →→→→ _Equivalent_ →→→→ <br/>(3361)<hr/>←←←← __ ←←←← <br/>() | `AUDIT`| | | | | 
| **`AUDIT`**| _Equivalent_ <br/>(308/1665)| `AUDIT`| _Equivalent_ <br/>(3484/5796)| `AUDIT`| | | | | 
| **`AUDTR`**| _Equivalent_ <br/>(309/1666)| `AUDTR`| →→→→ _Equivalent_ →→→→ <br/>(3341)<hr/>←←←← __ ←←←← <br/>() | `AUDTR`| | | | | 
| **`AUDTR`**| _Equivalent_ <br/>(309/1666)| `AUDTR`| _Equivalent_ <br/>(3472/5776)| `AUDTR`| | | | | 
| **`CPLYCC`**| _Equivalent_ <br/>(313/1670)| `CPLYCC`| →→→→ _Equivalent_ →→→→ <br/>(3309)<hr/>←←←← __ ←←←← <br/>() | `CPLYCC`| | | | | 
| **`CPLYCC`**| _Equivalent_ <br/>(313/1670)| `CPLYCC`| _Equivalent_ <br/>(3541/5744)| `CPLYCC`| | | | | 
| **`CPLYCD`**| _Equivalent_ <br/>(314/1671)| `CPLYCD`| →→→→ _Equivalent_ →→→→ <br/>(3315)<hr/>←←←← __ ←←←← <br/>() | `CPLYCD`| | | | | 
| **`CPLYCD`**| _Equivalent_ <br/>(314/1671)| `CPLYCD`| _Equivalent_ <br/>(3471/5750)| `CPLYCD`| | | | | 
| **`CPLYJPP`**| _Equivalent_ <br/>(315/1672)| `CPLYJPP`| →→→→ _Equivalent_ →→→→ <br/>(3342)<hr/>←←←← __ ←←←← <br/>() | `CPLYJPP`| | | | | 
| **`CPLYJPP`**| _Equivalent_ <br/>(315/1672)| `CPLYJPP`| _Equivalent_ <br/>(3478/5777)| `CPLYJPP`| | | | | 
| **`CPLYOPP`**| _Equivalent_ <br/>(316/1673)| `CPLYOPP`| →→→→ _Equivalent_ →→→→ <br/>(3346)<hr/>←←←← __ ←←←← <br/>() | `CPLYOPP`| | | | | 
| **`CPLYOPP`**| _Equivalent_ <br/>(316/1673)| `CPLYOPP`| _Equivalent_ <br/>(3528/5781)| `CPLYOPP`| | | | | 
| **`CPLYOSP`**| _Equivalent_ <br/>(317/1674)| `CPLYOSP`| →→→→ _Equivalent_ →→→→ <br/>(3307)<hr/>←←←← __ ←←←← <br/>() | `CPLYOSP`| | | | | 
| **`CPLYOSP`**| _Equivalent_ <br/>(317/1674)| `CPLYOSP`| _Equivalent_ <br/>(3525/5742)| `CPLYOSP`| | | | | 
| **`CPLYPOL`**| _Equivalent_ <br/>(318/1675)| `CPLYPOL`| →→→→ _Equivalent_ →→→→ <br/>(3334)<hr/>←←←← __ ←←←← <br/>() | `CPLYPOL`| | | | | 
| **`CPLYPOL`**| _Equivalent_ <br/>(318/1675)| `CPLYPOL`| _Equivalent_ <br/>(3494/5769)| `CPLYPOL`| | | | | 
| **`DEID`**| _Equivalent_ <br/>(319/1677)| `DEID`| →→→→ _Equivalent_ →→→→ <br/>(3353)<hr/>←←←← __ ←←←← <br/>() | `DEID`| | | | | 
| **`DEID`**| _Equivalent_ <br/>(319/1677)| `DEID`| _Equivalent_ <br/>(3517/5788)| `DEID`| | | | | 
| **`DELAU`**| _Equivalent_ <br/>(320/1678)| `DELAU`| →→→→ _Equivalent_ →→→→ <br/>(3372)<hr/>←←←← __ ←←←← <br/>() | `DELAU`| | | | | 
| **`DELAU`**| _Equivalent_ <br/>(320/1678)| `DELAU`| _Equivalent_ <br/>(3526/5807)| `DELAU`| | | | | 
| **`ENCRYPTR`**| _Equivalent_ <br/>(328/1688)| `ENCRYPTR`| →→→→ _Equivalent_ →→→→ <br/>(3335)<hr/>←←←← __ ←←←← <br/>() | `ENCRYPTR`| | | | | 
| **`ENCRYPTR`**| _Equivalent_ <br/>(328/1688)| `ENCRYPTR`| _Equivalent_ <br/>(3506/5770)| `ENCRYPTR`| | | | | 
| **`ENCRYPTT`**| _Equivalent_ <br/>(329/1689)| `ENCRYPTT`| →→→→ _Equivalent_ →→→→ <br/>(3366)<hr/>←←←← __ ←←←← <br/>() | `ENCRYPTT`| | | | | 
| **`ENCRYPTT`**| _Equivalent_ <br/>(329/1689)| `ENCRYPTT`| _Equivalent_ <br/>(3507/5801)| `ENCRYPTT`| | | | | 
| **`ENCRYPTU`**| _Equivalent_ <br/>(330/1690)| `ENCRYPTU`| →→→→ _Equivalent_ →→→→ <br/>(3303)<hr/>←←←← __ ←←←← <br/>() | `ENCRYPTU`| | | | | 
| **`ENCRYPTU`**| _Equivalent_ <br/>(330/1690)| `ENCRYPTU`| _Equivalent_ <br/>(3486/5738)| `ENCRYPTU`| | | | | 
| **`ENCRYPT`**| _Equivalent_ <br/>(327/1687)| `ENCRYPT`| →→→→ _Equivalent_ →→→→ <br/>(3328)<hr/>←←←← __ ←←←← <br/>() | `ENCRYPT`| | | | | 
| **`ENCRYPT`**| _Equivalent_ <br/>(327/1687)| `ENCRYPT`| _Equivalent_ <br/>(3524/5763)| `ENCRYPT`| | | | | 
| **`HUAPRV`**| _Equivalent_ <br/>(336/1696)| `HUAPRV`| →→→→ _Equivalent_ →→→→ <br/>(3358)<hr/>←←←← __ ←←←← <br/>() | `HUAPRV`| | | | | 
| **`HUAPRV`**| _Equivalent_ <br/>(336/1696)| `HUAPRV`| _Equivalent_ <br/>(3479/5793)| `HUAPRV`| | | | | 
| **`MASK`**| _Equivalent_ <br/>(340/1701)| `MASK`| →→→→ _Equivalent_ →→→→ <br/>(3327)<hr/>←←←← __ ←←←← <br/>() | `MASK`| | | | | 
| **`MASK`**| _Equivalent_ <br/>(340/1701)| `MASK`| _Equivalent_ <br/>(3474/5762)| `MASK`| | | | | 
| **`MINEC`**| _Equivalent_ <br/>(341/1702)| `MINEC`| →→→→ _Equivalent_ →→→→ <br/>(3325)<hr/>←←←← __ ←←←← <br/>() | `MINEC`| | | | | 
| **`MINEC`**| _Equivalent_ <br/>(341/1702)| `MINEC`| _Equivalent_ <br/>(3535/5760)| `MINEC`| | | | | 
| **`PRIVMARK`**| _Equivalent_ <br/>(361/1723)| `PRIVMARK`| →→→→ _Equivalent_ →→→→ <br/>(3312)<hr/>←←←← __ ←←←← <br/>() | `PRIVMARK`| | | | | 
| **`PRIVMARK`**| _Equivalent_ <br/>(361/1723)| `PRIVMARK`| _Equivalent_ <br/>(3521/5747)| `PRIVMARK`| | | | | 
| **`PSEUD`**| _Equivalent_ <br/>(363/1725)| `PSEUD`| →→→→ _Equivalent_ →→→→ <br/>(3310)<hr/>←←←← __ ←←←← <br/>() | `PSEUD`| | | | | 
| **`PSEUD`**| _Equivalent_ <br/>(363/1725)| `PSEUD`| _Equivalent_ <br/>(3520/5745)| `PSEUD`| | | | | 
| **`REDACT`**| _Equivalent_ <br/>(366/1728)| `REDACT`| →→→→ _Equivalent_ →→→→ <br/>(3305)<hr/>←←←← __ ←←←← <br/>() | `REDACT`| | | | | 
| **`REDACT`**| _Equivalent_ <br/>(366/1728)| `REDACT`| _Equivalent_ <br/>(3501/5740)| `REDACT`| | | | | 
| **`ObligationPolicy`**| _Equivalent_ <br/>(359/1720)| `ObligationPolicy`| →→→→ _Equivalent_ →→→→ <br/>(3319)<hr/>←←←← __ ←←←← <br/>() | `ObligationPolicy`| | | | | 
| **`ObligationPolicy`**| _Equivalent_ <br/>(359/1720)| `ObligationPolicy`| _Equivalent_ <br/>(3540/5754)| `ObligationPolicy`| | | | | 
| **`NOAUTH`**| _Equivalent_ <br/>(342/1703)| `NOAUTH`| →→→→ _Equivalent_ →→→→ <br/>(3336)<hr/>←←←← __ ←←←← <br/>() | `NOAUTH`| | | | | 
| **`NOAUTH`**| _Equivalent_ <br/>(342/1703)| `NOAUTH`| _Equivalent_ <br/>(3470/5771)| `NOAUTH`| | | | | 
| **`NOCOLLECT`**| _Equivalent_ <br/>(343/1704)| `NOCOLLECT`| →→→→ _Equivalent_ →→→→ <br/>(3323)<hr/>←←←← __ ←←←← <br/>() | `NOCOLLECT`| | | | | 
| **`NOCOLLECT`**| _Equivalent_ <br/>(343/1704)| `NOCOLLECT`| _Equivalent_ <br/>(3533/5758)| `NOCOLLECT`| | | | | 
| **`NODSCLCD`**| _Equivalent_ <br/>(344/1705)| `NODSCLCD`| →→→→ _Equivalent_ →→→→ <br/>(3331)<hr/>←←←← __ ←←←← <br/>() | `NODSCLCD`| | | | | 
| **`NODSCLCD`**| _Equivalent_ <br/>(344/1705)| `NODSCLCD`| _Equivalent_ <br/>(3511/5766)| `NODSCLCD`| | | | | 
| **`NODSCLCDS`**| _Equivalent_ <br/>(345/1706)| `NODSCLCDS`| →→→→ _Equivalent_ →→→→ <br/>(3352)<hr/>←←←← __ ←←←← <br/>() | `NODSCLCDS`| | | | | 
| **`NODSCLCDS`**| _Equivalent_ <br/>(345/1706)| `NODSCLCDS`| _Equivalent_ <br/>(3547/5787)| `NODSCLCDS`| | | | | 
| **`NOINTEGRATE`**| _Equivalent_ <br/>(346/1707)| `NOINTEGRATE`| →→→→ _Equivalent_ →→→→ <br/>(3359)<hr/>←←←← __ ←←←← <br/>() | `NOINTEGRATE`| | | | | 
| **`NOINTEGRATE`**| _Equivalent_ <br/>(346/1707)| `NOINTEGRATE`| _Equivalent_ <br/>(3532/5794)| `NOINTEGRATE`| | | | | 
| **`NOLIST`**| _Equivalent_ <br/>(347/1708)| `NOLIST`| →→→→ _Equivalent_ →→→→ <br/>(3373)<hr/>←←←← __ ←←←← <br/>() | `NOLIST`| | | | | 
| **`NOLIST`**| _Equivalent_ <br/>(347/1708)| `NOLIST`| _Equivalent_ <br/>(3488/5808)| `NOLIST`| | | | | 
| **`NOMOU`**| _Equivalent_ <br/>(348/1709)| `NOMOU`| →→→→ _Equivalent_ →→→→ <br/>(3318)<hr/>←←←← __ ←←←← <br/>() | `NOMOU`| | | | | 
| **`NOMOU`**| _Equivalent_ <br/>(348/1709)| `NOMOU`| _Equivalent_ <br/>(3498/5753)| `NOMOU`| | | | | 
| **`NOORGPOL`**| _Equivalent_ <br/>(349/1710)| `NOORGPOL`| →→→→ _Equivalent_ →→→→ <br/>(3377)<hr/>←←←← __ ←←←← <br/>() | `NOORGPOL`| | | | | 
| **`NOORGPOL`**| _Equivalent_ <br/>(349/1710)| `NOORGPOL`| _Equivalent_ <br/>(3522/5812)| `NOORGPOL`| | | | | 
| **`NOPAT`**| _Equivalent_ <br/>(350/1711)| `NOPAT`| →→→→ _Equivalent_ →→→→ <br/>(3368)<hr/>←←←← __ ←←←← <br/>() | `NOPAT`| | | | | 
| **`NOPAT`**| _Equivalent_ <br/>(350/1711)| `NOPAT`| _Equivalent_ <br/>(3482/5803)| `NOPAT`| | | | | 
| **`NOPERSISTP`**| _Equivalent_ <br/>(351/1712)| `NOPERSISTP`| →→→→ _Equivalent_ →→→→ <br/>(3338)<hr/>←←←← __ ←←←← <br/>() | `NOPERSISTP`| | | | | 
| **`NOPERSISTP`**| _Equivalent_ <br/>(351/1712)| `NOPERSISTP`| _Equivalent_ <br/>(3539/5773)| `NOPERSISTP`| | | | | 
| **`NORDSCLCD`**| _Equivalent_ <br/>(352/1713)| `NORDSCLCD`| →→→→ _Equivalent_ →→→→ <br/>(3347)<hr/>←←←← __ ←←←← <br/>() | `NORDSCLCD`| | | | | 
| **`NORDSCLCD`**| _Equivalent_ <br/>(352/1713)| `NORDSCLCD`| _Equivalent_ <br/>(3544/5782)| `NORDSCLCD`| | | | | 
| **`NORDSCLCDS`**| _Equivalent_ <br/>(353/1714)| `NORDSCLCDS`| →→→→ _Equivalent_ →→→→ <br/>(3302)<hr/>←←←← __ ←←←← <br/>() | `NORDSCLCDS`| | | | | 
| **`NORDSCLCDS`**| _Equivalent_ <br/>(353/1714)| `NORDSCLCDS`| _Equivalent_ <br/>(3538/5737)| `NORDSCLCDS`| | | | | 
| **`NORDSCLW`**| _Equivalent_ <br/>(354/1715)| `NORDSCLW`| →→→→ _Equivalent_ →→→→ <br/>(3308)<hr/>←←←← __ ←←←← <br/>() | `NORDSCLW`| | | | | 
| **`NORDSCLW`**| _Equivalent_ <br/>(354/1715)| `NORDSCLW`| _Equivalent_ <br/>(3487/5743)| `NORDSCLW`| | | | | 
| **`NORELINK`**| _Equivalent_ <br/>(355/1716)| `NORELINK`| →→→→ _Equivalent_ →→→→ <br/>(3367)<hr/>←←←← __ ←←←← <br/>() | `NORELINK`| | | | | 
| **`NORELINK`**| _Equivalent_ <br/>(355/1716)| `NORELINK`| _Equivalent_ <br/>(3491/5802)| `NORELINK`| | | | | 
| **`NOREUSE`**| _Equivalent_ <br/>(356/1717)| `NOREUSE`| →→→→ _Equivalent_ →→→→ <br/>(3363)<hr/>←←←← __ ←←←← <br/>() | `NOREUSE`| | | | | 
| **`NOREUSE`**| _Equivalent_ <br/>(356/1717)| `NOREUSE`| _Equivalent_ <br/>(3489/5798)| `NOREUSE`| | | | | 
| **`NOVIP`**| _Equivalent_ <br/>(357/1718)| `NOVIP`| →→→→ _Equivalent_ →→→→ <br/>(3320)<hr/>←←←← __ ←←←← <br/>() | `NOVIP`| | | | | 
| **`NOVIP`**| _Equivalent_ <br/>(357/1718)| `NOVIP`| _Equivalent_ <br/>(3546/5755)| `NOVIP`| | | | | 
| **`ORCON`**| _Equivalent_ <br/>(358/1719)| `ORCON`| →→→→ _Equivalent_ →→→→ <br/>(3362)<hr/>←←←← __ ←←←← <br/>() | `ORCON`| | | | | 
| **`ORCON`**| _Equivalent_ <br/>(358/1719)| `ORCON`| _Equivalent_ <br/>(3536/5797)| `ORCON`| | | | | 
| **`RefrainPolicy`**| _Equivalent_ <br/>(370/1732)| `RefrainPolicy`| →→→→ _Equivalent_ →→→→ <br/>(3370)<hr/>←←←← __ ←←←← <br/>() | `RefrainPolicy`| | | | | 
| **`RefrainPolicy`**| _Equivalent_ <br/>(370/1732)| `RefrainPolicy`| _Equivalent_ <br/>(3473/5805)| `RefrainPolicy`| | | | | 
| **`SecurityPolicy`**| _Equivalent_ <br/>(377/1740)| `SecurityPolicy`| →→→→ _Equivalent_ →→→→ <br/>(3314)<hr/>←←←← __ ←←←← <br/>() | `SecurityPolicy`| | | | | 
| **`SecurityPolicy`**| _Equivalent_ <br/>(377/1740)| `SecurityPolicy`| _Equivalent_ <br/>(3476/5749)| `SecurityPolicy`| | | | | 
| **`ANONY`**| | | | | | | | | 
| **`AOD`**| | | | | | | | | 
| **`AUDIT`**| | | | | | | | | 
| **`AUDTR`**| | | | | | | | | 
| **`CPLYCC`**| | | | | | | | | 
| **`CPLYCD`**| | | | | | | | | 
| **`CPLYJPP`**| | | | | | | | | 
| **`CPLYOPP`**| | | | | | | | | 
| **`CPLYOSP`**| | | | | | | | | 
| **`CPLYPOL`**| | | | | | | | | 
| **`DEID`**| | | | | | | | | 
| **`DELAU`**| | | | | | | | | 
| **`ENCRYPTR`**| | | | | | | | | 
| **`ENCRYPTT`**| | | | | | | | | 
| **`ENCRYPTU`**| | | | | | | | | 
| **`ENCRYPT`**| | | | | | | | | 
| **`HUAPRV`**| | | | | | | | | 
| **`MASK`**| | | | | | | | | 
| **`MINEC`**| | | | | | | | | 
| **`PRIVMARK`**| | | | | | | | | 
| **`PSEUD`**| | | | | | | | | 
| **`REDACT`**| | | | | | | | | 
| **`ObligationPolicy`**| | | | | | | | | 
| **`NOAUTH`**| | | | | | | | | 
| **`NOCOLLECT`**| | | | | | | | | 
| **`NODSCLCD`**| | | | | | | | | 
| **`NODSCLCDS`**| | | | | | | | | 
| **`NOINTEGRATE`**| | | | | | | | | 
| **`NOLIST`**| | | | | | | | | 
| **`NOMOU`**| | | | | | | | | 
| **`NOORGPOL`**| | | | | | | | | 
| **`NOPAT`**| | | | | | | | | 
| **`NOPERSISTP`**| | | | | | | | | 
| **`NORDSCLCD`**| | | | | | | | | 
| **`NORDSCLCDS`**| | | | | | | | | 
| **`NORDSCLW`**| | | | | | | | | 
| **`NORELINK`**| | | | | | | | | 
| **`NOREUSE`**| | | | | | | | | 
| **`NOVIP`**| | | | | | | | | 
| **`ORCON`**| | | | | | | | | 
| **`RefrainPolicy`**| | | | | | | | | 
| <td colspan="8">**R2** System: `http://hl7.org/fhir/v3/ActReason`
| **`HMARKT`**| _Equivalent_ <br/>(399/1769)| `HMARKT`| →→→→ _Equivalent_ →→→→ <br/>(3295)<hr/>←←←← __ ←←←← <br/>() | `HMARKT`| | | | | 
| **`HMARKT`**| _Equivalent_ <br/>(399/1769)| `HMARKT`| _Equivalent_ <br/>(3449/5713)| `HMARKT`| | | | | 
| **`DONAT`**| _Equivalent_ <br/>(386/1756)| `DONAT`| →→→→ _Equivalent_ →→→→ <br/>(3275)<hr/>←←←← __ ←←←← <br/>() | `DONAT`| | | | | 
| **`DONAT`**| _Equivalent_ <br/>(386/1756)| `DONAT`| _Equivalent_ <br/>(3457/5693)| `DONAT`| | | | | 
| **`FRAUD`**| _Equivalent_ <br/>(392/1762)| `FRAUD`| →→→→ _Equivalent_ →→→→ <br/>(3263)<hr/>←←←← __ ←←←← <br/>() | `FRAUD`| | | | | 
| **`FRAUD`**| _Equivalent_ <br/>(392/1762)| `FRAUD`| _Equivalent_ <br/>(3465/5681)| `FRAUD`| | | | | 
| **`GOV`**| _Equivalent_ <br/>(393/1763)| `GOV`| →→→→ _Equivalent_ →→→→ <br/>(3267)<hr/>←←←← __ ←←←← <br/>() | `GOV`| | | | | 
| **`GOV`**| _Equivalent_ <br/>(393/1763)| `GOV`| _Equivalent_ <br/>(3458/5685)| `GOV`| | | | | 
| **`HACCRED`**| _Equivalent_ <br/>(394/1764)| `HACCRED`| →→→→ _Equivalent_ →→→→ <br/>(3274)<hr/>←←←← __ ←←←← <br/>() | `HACCRED`| | | | | 
| **`HACCRED`**| _Equivalent_ <br/>(394/1764)| `HACCRED`| _Equivalent_ <br/>(3427/5692)| `HACCRED`| | | | | 
| **`HCOMPL`**| _Equivalent_ <br/>(395/1765)| `HCOMPL`| →→→→ _Equivalent_ →→→→ <br/>(3280)<hr/>←←←← __ ←←←← <br/>() | `HCOMPL`| | | | | 
| **`HCOMPL`**| _Equivalent_ <br/>(395/1765)| `HCOMPL`| _Equivalent_ <br/>(3466/5698)| `HCOMPL`| | | | | 
| **`HDECD`**| _Equivalent_ <br/>(396/1766)| `HDECD`| →→→→ _Equivalent_ →→→→ <br/>(3283)<hr/>←←←← __ ←←←← <br/>() | `HDECD`| | | | | 
| **`HDECD`**| _Equivalent_ <br/>(396/1766)| `HDECD`| _Equivalent_ <br/>(3447/5701)| `HDECD`| | | | | 
| **`HDIRECT`**| _Equivalent_ <br/>(397/1767)| `HDIRECT`| →→→→ _Equivalent_ →→→→ <br/>(3271)<hr/>←←←← __ ←←←← <br/>() | `HDIRECT`| | | | | 
| **`HDIRECT`**| _Equivalent_ <br/>(397/1767)| `HDIRECT`| _Equivalent_ <br/>(3453/5689)| `HDIRECT`| | | | | 
| **`HLEGAL`**| _Equivalent_ <br/>(398/1768)| `HLEGAL`| →→→→ _Equivalent_ →→→→ <br/>(3276)<hr/>←←←← __ ←←←← <br/>() | `HLEGAL`| | | | | 
| **`HLEGAL`**| _Equivalent_ <br/>(398/1768)| `HLEGAL`| _Equivalent_ <br/>(3448/5694)| `HLEGAL`| | | | | 
| **`HOUTCOMS`**| _Equivalent_ <br/>(401/1771)| `HOUTCOMS`| →→→→ _Equivalent_ →→→→ <br/>(3293)<hr/>←←←← __ ←←←← <br/>() | `HOUTCOMS`| | | | | 
| **`HOUTCOMS`**| _Equivalent_ <br/>(401/1771)| `HOUTCOMS`| _Equivalent_ <br/>(3452/5711)| `HOUTCOMS`| | | | | 
| **`HPRGRP`**| _Equivalent_ <br/>(403/1773)| `HPRGRP`| →→→→ _Equivalent_ →→→→ <br/>(3290)<hr/>←←←← __ ←←←← <br/>() | `HPRGRP`| | | | | 
| **`HPRGRP`**| _Equivalent_ <br/>(403/1773)| `HPRGRP`| _Equivalent_ <br/>(3438/5708)| `HPRGRP`| | | | | 
| **`HQUALIMP`**| _Equivalent_ <br/>(404/1774)| `HQUALIMP`| →→→→ _Equivalent_ →→→→ <br/>(3282)<hr/>←←←← __ ←←←← <br/>() | `HQUALIMP`| | | | | 
| **`HQUALIMP`**| _Equivalent_ <br/>(404/1774)| `HQUALIMP`| _Equivalent_ <br/>(3442/5700)| `HQUALIMP`| | | | | 
| **`HSYSADMIN`**| _Equivalent_ <br/>(406/1776)| `HSYSADMIN`| →→→→ _Equivalent_ →→→→ <br/>(3259)<hr/>←←←← __ ←←←← <br/>() | `HSYSADMIN`| | | | | 
| **`HSYSADMIN`**| _Equivalent_ <br/>(406/1776)| `HSYSADMIN`| _Equivalent_ <br/>(3445/5677)| `HSYSADMIN`| | | | | 
| **`MEMADMIN`**| _Equivalent_ <br/>(407/1777)| `MEMADMIN`| →→→→ _Equivalent_ →→→→ <br/>(3260)<hr/>←←←← __ ←←←← <br/>() | `MEMADMIN`| | | | | 
| **`MEMADMIN`**| _Equivalent_ <br/>(407/1777)| `MEMADMIN`| _Equivalent_ <br/>(3461/5678)| `MEMADMIN`| | | | | 
| **`PATADMIN`**| _Equivalent_ <br/>(408/1778)| `PATADMIN`| →→→→ _Equivalent_ →→→→ <br/>(3266)<hr/>←←←← __ ←←←← <br/>() | `PATADMIN`| | | | | 
| **`PATADMIN`**| _Equivalent_ <br/>(408/1778)| `PATADMIN`| _Equivalent_ <br/>(3435/5684)| `PATADMIN`| | | | | 
| **`PATSFTY`**| _Equivalent_ <br/>(410/1780)| `PATSFTY`| →→→→ _Equivalent_ →→→→ <br/>(3264)<hr/>←←←← __ ←←←← <br/>() | `PATSFTY`| | | | | 
| **`PATSFTY`**| _Equivalent_ <br/>(410/1780)| `PATSFTY`| _Equivalent_ <br/>(3446/5682)| `PATSFTY`| | | | | 
| **`PERFMSR`**| _Equivalent_ <br/>(411/1781)| `PERFMSR`| →→→→ _Equivalent_ →→→→ <br/>(3289)<hr/>←←←← __ ←←←← <br/>() | `PERFMSR`| | | | | 
| **`PERFMSR`**| _Equivalent_ <br/>(411/1781)| `PERFMSR`| _Equivalent_ <br/>(3432/5707)| `PERFMSR`| | | | | 
| **`RECORDMGT`**| _Equivalent_ <br/>(416/1786)| `RECORDMGT`| →→→→ _Equivalent_ →→→→ <br/>(3265)<hr/>←←←← __ ←←←← <br/>() | `RECORDMGT`| | | | | 
| **`RECORDMGT`**| _Equivalent_ <br/>(416/1786)| `RECORDMGT`| _Equivalent_ <br/>(3443/5683)| `RECORDMGT`| | | | | 
| **`TRAIN`**| _Equivalent_ <br/>(420/1790)| `TRAIN`| →→→→ _Equivalent_ →→→→ <br/>(3277)<hr/>←←←← __ ←←←← <br/>() | `TRAIN`| | | | | 
| **`TRAIN`**| _Equivalent_ <br/>(420/1790)| `TRAIN`| _Equivalent_ <br/>(3439/5695)| `TRAIN`| | | | | 
| **`HOPERAT`**| _Equivalent_ <br/>(400/1770)| `HOPERAT`| →→→→ _Equivalent_ →→→→ <br/>(3278)<hr/>←←←← __ ←←←← <br/>() | `HOPERAT`| | | | | 
| **`HOPERAT`**| _Equivalent_ <br/>(400/1770)| `HOPERAT`| _Equivalent_ <br/>(3460/5696)| `HOPERAT`| | | | | 
| **`CLMATTCH`**| _Equivalent_ <br/>(382/1752)| `CLMATTCH`| →→→→ _Equivalent_ →→→→ <br/>(3273)<hr/>←←←← __ ←←←← <br/>() | `CLMATTCH`| | | | | 
| **`CLMATTCH`**| _Equivalent_ <br/>(382/1752)| `CLMATTCH`| _Equivalent_ <br/>(3464/5691)| `CLMATTCH`| | | | | 
| **`COVAUTH`**| _Equivalent_ <br/>(383/1753)| `COVAUTH`| →→→→ _Equivalent_ →→→→ <br/>(3270)<hr/>←←←← __ ←←←← <br/>() | `COVAUTH`| | | | | 
| **`COVAUTH`**| _Equivalent_ <br/>(383/1753)| `COVAUTH`| _Equivalent_ <br/>(3459/5688)| `COVAUTH`| | | | | 
| **`ELIGDTRM`**| _Equivalent_ <br/>(387/1757)| `ELIGDTRM`| →→→→ _Equivalent_ →→→→ <br/>(3286)<hr/>←←←← __ ←←←← <br/>() | `ELIGDTRM`| | | | | 
| **`ELIGDTRM`**| _Equivalent_ <br/>(387/1757)| `ELIGDTRM`| _Equivalent_ <br/>(3428/5704)| `ELIGDTRM`| | | | | 
| **`ELIGVER`**| _Equivalent_ <br/>(388/1758)| `ELIGVER`| →→→→ _Equivalent_ →→→→ <br/>(3291)<hr/>←←←← __ ←←←← <br/>() | `ELIGVER`| | | | | 
| **`ELIGVER`**| _Equivalent_ <br/>(388/1758)| `ELIGVER`| _Equivalent_ <br/>(3468/5709)| `ELIGVER`| | | | | 
| **`ENROLLM`**| _Equivalent_ <br/>(389/1759)| `ENROLLM`| →→→→ _Equivalent_ →→→→ <br/>(3287)<hr/>←←←← __ ←←←← <br/>() | `ENROLLM`| | | | | 
| **`ENROLLM`**| _Equivalent_ <br/>(389/1759)| `ENROLLM`| _Equivalent_ <br/>(3437/5705)| `ENROLLM`| | | | | 
| **`COVERAGE`**| _Equivalent_ <br/>(384/1754)| `COVERAGE`| →→→→ _Equivalent_ →→→→ <br/>(3288)<hr/>←←←← __ ←←←← <br/>() | `COVERAGE`| | | | | 
| **`COVERAGE`**| _Equivalent_ <br/>(384/1754)| `COVERAGE`| _Equivalent_ <br/>(3467/5706)| `COVERAGE`| | | | | 
| **`REMITADV`**| _Equivalent_ <br/>(417/1787)| `REMITADV`| →→→→ _Equivalent_ →→→→ <br/>(3281)<hr/>←←←← __ ←←←← <br/>() | `REMITADV`| | | | | 
| **`REMITADV`**| _Equivalent_ <br/>(417/1787)| `REMITADV`| _Equivalent_ <br/>(3441/5699)| `REMITADV`| | | | | 
| **`HPAYMT`**| _Equivalent_ <br/>(402/1772)| `HPAYMT`| →→→→ _Equivalent_ →→→→ <br/>(3269)<hr/>←←←← __ ←←←← <br/>() | `HPAYMT`| | | | | 
| **`HPAYMT`**| _Equivalent_ <br/>(402/1772)| `HPAYMT`| _Equivalent_ <br/>(3456/5687)| `HPAYMT`| | | | | 
| **`CLINTRCH`**| _Equivalent_ <br/>(380/1750)| `CLINTRCH`| →→→→ _Equivalent_ →→→→ <br/>(3284)<hr/>←←←← __ ←←←← <br/>() | `CLINTRCH`| | | | | 
| **`CLINTRCH`**| _Equivalent_ <br/>(380/1750)| `CLINTRCH`| _Equivalent_ <br/>(3430/5702)| `CLINTRCH`| | | | | 
| **`HRESCH`**| _Equivalent_ <br/>(405/1775)| `HRESCH`| →→→→ _Equivalent_ →→→→ <br/>(3258)<hr/>←←←← __ ←←←← <br/>() | `HRESCH`| | | | | 
| **`HRESCH`**| _Equivalent_ <br/>(405/1775)| `HRESCH`| _Equivalent_ <br/>(3436/5676)| `HRESCH`| | | | | 
| **`FAMRQT`**| _Equivalent_ <br/>(391/1761)| `FAMRQT`| →→→→ _Equivalent_ →→→→ <br/>(3285)<hr/>←←←← __ ←←←← <br/>() | `FAMRQT`| | | | | 
| **`FAMRQT`**| _Equivalent_ <br/>(391/1761)| `FAMRQT`| _Equivalent_ <br/>(3451/5703)| `FAMRQT`| | | | | 
| **`PWATRNY`**| _Equivalent_ <br/>(414/1784)| `PWATRNY`| →→→→ _Equivalent_ →→→→ <br/>(3268)<hr/>←←←← __ ←←←← <br/>() | `PWATRNY`| | | | | 
| **`PWATRNY`**| _Equivalent_ <br/>(414/1784)| `PWATRNY`| _Equivalent_ <br/>(3431/5686)| `PWATRNY`| | | | | 
| **`SUPNWK`**| _Equivalent_ <br/>(418/1788)| `SUPNWK`| →→→→ _Equivalent_ →→→→ <br/>(3279)<hr/>←←←← __ ←←←← <br/>() | `SUPNWK`| | | | | 
| **`SUPNWK`**| _Equivalent_ <br/>(418/1788)| `SUPNWK`| _Equivalent_ <br/>(3450/5697)| `SUPNWK`| | | | | 
| **`PATRQT`**| _Equivalent_ <br/>(409/1779)| `PATRQT`| →→→→ _Equivalent_ →→→→ <br/>(3298)<hr/>←←←← __ ←←←← <br/>() | `PATRQT`| | | | | 
| **`PATRQT`**| _Equivalent_ <br/>(409/1779)| `PATRQT`| _Equivalent_ <br/>(3463/5716)| `PATRQT`| | | | | 
| **`DISASTER`**| _Equivalent_ <br/>(385/1755)| `DISASTER`| →→→→ _Equivalent_ →→→→ <br/>(3299)<hr/>←←←← __ ←←←← <br/>() | `DISASTER`| | | | | 
| **`DISASTER`**| _Equivalent_ <br/>(385/1755)| `DISASTER`| _Equivalent_ <br/>(3455/5717)| `DISASTER`| | | | | 
| **`THREAT`**| _Equivalent_ <br/>(419/1789)| `THREAT`| →→→→ _Equivalent_ →→→→ <br/>(3296)<hr/>←←←← __ ←←←← <br/>() | `THREAT`| | | | | 
| **`THREAT`**| _Equivalent_ <br/>(419/1789)| `THREAT`| _Equivalent_ <br/>(3469/5714)| `THREAT`| | | | | 
| **`PUBHLTH`**| _Equivalent_ <br/>(413/1783)| `PUBHLTH`| →→→→ _Equivalent_ →→→→ <br/>(3294)<hr/>←←←← __ ←←←← <br/>() | `PUBHLTH`| | | | | 
| **`PUBHLTH`**| _Equivalent_ <br/>(413/1783)| `PUBHLTH`| _Equivalent_ <br/>(3434/5712)| `PUBHLTH`| | | | | 
| **`CAREMGT`**| _Equivalent_ <br/>(379/1749)| `CAREMGT`| →→→→ _Equivalent_ →→→→ <br/>(3261)<hr/>←←←← __ ←←←← <br/>() | `CAREMGT`| | | | | 
| **`CAREMGT`**| _Equivalent_ <br/>(379/1749)| `CAREMGT`| _Equivalent_ <br/>(3444/5679)| `CAREMGT`| | | | | 
| **`CLINTRL`**| _Equivalent_ <br/>(381/1751)| `CLINTRL`| →→→→ _Equivalent_ →→→→ <br/>(3272)<hr/>←←←← __ ←←←← <br/>() | `CLINTRL`| | | | | 
| **`CLINTRL`**| _Equivalent_ <br/>(381/1751)| `CLINTRL`| _Equivalent_ <br/>(3440/5690)| `CLINTRL`| | | | | 
| **`ETREAT`**| _Equivalent_ <br/>(390/1760)| `ETREAT`| →→→→ _Equivalent_ →→→→ <br/>(3300)<hr/>←←←← __ ←←←← <br/>() | `ETREAT`| | | | | 
| **`ETREAT`**| _Equivalent_ <br/>(390/1760)| `ETREAT`| _Equivalent_ <br/>(3454/5718)| `ETREAT`| | | | | 
| **`POPHLTH`**| _Equivalent_ <br/>(412/1782)| `POPHLTH`| →→→→ _Equivalent_ →→→→ <br/>(3262)<hr/>←←←← __ ←←←← <br/>() | `POPHLTH`| | | | | 
| **`POPHLTH`**| _Equivalent_ <br/>(412/1782)| `POPHLTH`| _Equivalent_ <br/>(3429/5680)| `POPHLTH`| | | | | 
| **`TREAT`**| _Equivalent_ <br/>(421/1791)| `TREAT`| →→→→ _Equivalent_ →→→→ <br/>(3292)<hr/>←←←← __ ←←←← <br/>() | `TREAT`| | | | | 
| **`TREAT`**| _Equivalent_ <br/>(421/1791)| `TREAT`| _Equivalent_ <br/>(3433/5710)| `TREAT`| | | | | 
| **`PurposeOfUse`**| _Equivalent_ <br/>(415/1785)| `PurposeOfUse`| →→→→ _Equivalent_ →→→→ <br/>(3297)<hr/>←←←← __ ←←←← <br/>() | `PurposeOfUse`| | | | | 
| **`PurposeOfUse`**| _Equivalent_ <br/>(415/1785)| `PurposeOfUse`| _Equivalent_ <br/>(3462/5715)| `PurposeOfUse`| | | | | 
| **`COVERAGE`**| | | | | | | | | 
| **`ETREAT`**| | | | | | | | | 
| **`HMARKT`**| | | | | | | | | 
| **`HOPERAT`**| | | | | | | | | 
| **`HPAYMT`**| | | | | | | | | 
| **`HRESCH`**| | | | | | | | | 
| **`PATRQT`**| | | | | | | | | 
| **`PUBHLTH`**| | | | | | | | | 
| **`TREAT`**| | | | | | | | | 
| <td colspan="8">**R2** System: `http://hl7.org/fhir/v3/ActUSPrivacyLaw`
| **`42CFRPart2`**| _Equivalent_ <br/>(283/1656)| `42CFRPart2`| →→→→ _Equivalent_ →→→→ <br/>(3247)<hr/>←←←← __ ←←←← <br/>() | `42CFRPart2`| | | | | 
| **`42CFRPart2`**| _Equivalent_ <br/>(283/1656)| `42CFRPart2`| _Equivalent_ <br/>(3385/5665)| `42CFRPart2`| | | | | 
| **`CommonRule`**| _Equivalent_ <br/>(284/1657)| `CommonRule`| →→→→ _Equivalent_ →→→→ <br/>(3249)<hr/>←←←← __ ←←←← <br/>() | `CommonRule`| | | | | 
| **`CommonRule`**| _Equivalent_ <br/>(284/1657)| `CommonRule`| _Equivalent_ <br/>(3383/5667)| `CommonRule`| | | | | 
| **`HIPAANOPP`**| _Equivalent_ <br/>(285/1658)| `HIPAANOPP`| →→→→ _Equivalent_ →→→→ <br/>(3248)<hr/>←←←← __ ←←←← <br/>() | `HIPAANOPP`| | | | | 
| **`HIPAANOPP`**| _Equivalent_ <br/>(285/1658)| `HIPAANOPP`| _Equivalent_ <br/>(3382/5666)| `HIPAANOPP`| | | | | 
| **`HIPAAPsyNotes`**| _Equivalent_ <br/>(286/1659)| `HIPAAPsyNotes`| →→→→ _Equivalent_ →→→→ <br/>(3251)<hr/>←←←← __ ←←←← <br/>() | `HIPAAPsyNotes`| | | | | 
| **`HIPAAPsyNotes`**| _Equivalent_ <br/>(286/1659)| `HIPAAPsyNotes`| _Equivalent_ <br/>(3386/5669)| `HIPAAPsyNotes`| | | | | 
| **`HIPAASelfPay`**| _Equivalent_ <br/>(287/1660)| `HIPAASelfPay`| →→→→ _Equivalent_ →→→→ <br/>(3246)<hr/>←←←← __ ←←←← <br/>() | `HIPAASelfPay`| | | | | 
| **`HIPAASelfPay`**| _Equivalent_ <br/>(287/1660)| `HIPAASelfPay`| _Equivalent_ <br/>(3384/5664)| `HIPAASelfPay`| | | | | 
| **`Title38Section7332`**| _Equivalent_ <br/>(288/1661)| `Title38Section7332`| →→→→ _Equivalent_ →→→→ <br/>(3250)<hr/>←←←← __ ←←←← <br/>() | `Title38Section7332`| | | | | 
| **`Title38Section7332`**| _Equivalent_ <br/>(288/1661)| `Title38Section7332`| _Equivalent_ <br/>(3387/5668)| `Title38Section7332`| | | | | 
| **`_ActUSPrivacyLaw`**| | | | | | | | | 
| *174 of 237 codes used* <br/>remaining codes:<br/>| | *162 of 170 codes used* <br/>remaining codes:<br/>`DECLASSIFYLABEL`, `DOWNGRDLABEL`, `DRIVLABEL`, `LABEL`, `PERSISTLABEL`, `SOC`, `UPGRDLABEL`, `_ActUSPrivacyLaw`| | *162 of 273 codes used* <br/>remaining codes:<br/>`ACCESSCONSCHEME`, `ACOCOMPT`, `AUTHPOL`, `BH`, `COGN`, `CTCOMPT`, `DECLASSIFYLABEL`, `DELEPOL`, `DOWNGRDLABEL`, `DRIVLABEL`, `DVD`, `EMOTDIS`, `ETHUD`, `FMCOMPT`, `LABEL`, `LRCOMPT`, `MH`, `MST`, `OPIOIDUD`, `PACOMPT`, `PERSISTLABEL`, `PHY`, `PSYTHPN`, `SPI`, `SUD`, `UPGRDLABEL`, `VIO`, `BIORCH`, `BTG`, `CLINTRCHNPC`, `CLINTRCHPC`, `COC`, `DSRCH`, `ERTREAT`, `HDM`, `HTEST`, `LABELING`, `METAMGT`, `MILCDM`, `MILDCRG`, `POARCH`, `PRECLINTRCH`, `SYSDEV`, `TRANSRCH`, `_ActUSPrivacyLaw`| | | | 

