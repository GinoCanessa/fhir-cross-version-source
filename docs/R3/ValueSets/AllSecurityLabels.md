Comparison of 
Generated at Thursday, April 3, 2025 8:18:10 AM

### All Security Labels

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | All Security Labels |
| Canonical URL | `http://hl7.org/fhir/ValueSet/security-labels` |
| Version | 3.0.2 |
| Description | A single value set for all security labels defined by FHIR. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1465` |
| Database Concept Count | `170` |
| Database Active Concept Count | `170` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Meta` | `Meta.security` | `http://hl7.org/fhir/ValueSet/security-labels` | `Extensible` | Security Labels applied to this resource |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.entity.securityLabel` | `http://hl7.org/fhir/ValueSet/security-labels` | `Extensible` | Security labels on the entity |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.securityLabel` | `http://hl7.org/fhir/ValueSet/security-labels` | `Extensible` | Security Labels that define affected resources |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.except.securityLabel` | `http://hl7.org/fhir/ValueSet/security-labels` | `Extensible` | Security Labels that define affected resources |
| `http://hl7.org/fhir/StructureDefinition/Contract` | `Contract.securityLabel` | `http://hl7.org/fhir/ValueSet/security-labels` | `Extensible` | Security Labels that define affected resources |
| `http://hl7.org/fhir/StructureDefinition/Contract` | `Contract.term.securityLabel` | `http://hl7.org/fhir/ValueSet/security-labels` | `Extensible` | Security Labels that define affected terms |
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
| [All Security Labels](/docs/R2/ValueSets/AllSecurityLabels.md)<br/> `http://hl7.org/fhir/ValueSet/security-labels\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `53`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `212`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [All Security Labels](/docs/R3/ValueSets/AllSecurityLabels.md)<br/> `http://hl7.org/fhir/ValueSet/security-labels\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `389`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `612`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [All Security Labels](/docs/R4/ValueSets/AllSecurityLabels.md)<br/> `http://hl7.org/fhir/ValueSet/security-labels\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set All Security Labels from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 All Security Labels](/docs/R2/ValueSets/AllSecurityLabels.md)| Relationship | R3 All Security Labels| Relationship | [R4 All Security Labels](/docs/R4/ValueSets/AllSecurityLabels.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/Confidentiality`
| `U`| _Equivalent_ <br/>(298/1747)| **`U`**| _Equivalent_ <br/>(3425/5670)| `U`| | | | | 
| `U`| _Equivalent_ <br/>(298/1747)| **`U`**| _Equivalent_ <br/>(3425/5670)| `U`| | | | | 
| `L`| _Equivalent_ <br/>(292/1743)| **`L`**| _Equivalent_ <br/>(3422/5675)| `L`| | | | | 
| `L`| _Equivalent_ <br/>(292/1743)| **`L`**| _Equivalent_ <br/>(3422/5675)| `L`| | | | | 
| `M`| _Equivalent_ <br/>(293/1744)| **`M`**| _Equivalent_ <br/>(3426/5673)| `M`| | | | | 
| `M`| _Equivalent_ <br/>(293/1744)| **`M`**| _Equivalent_ <br/>(3426/5673)| `M`| | | | | 
| `N`| _Equivalent_ <br/>(294/1745)| **`N`**| _Equivalent_ <br/>(3424/5672)| `N`| | | | | 
| `N`| _Equivalent_ <br/>(294/1745)| **`N`**| _Equivalent_ <br/>(3424/5672)| `N`| | | | | 
| `R`| _Equivalent_ <br/>(295/1746)| **`R`**| _Equivalent_ <br/>(3421/5674)| `R`| | | | | 
| `R`| _Equivalent_ <br/>(295/1746)| **`R`**| _Equivalent_ <br/>(3421/5674)| `R`| | | | | 
| `V`| _Equivalent_ <br/>(299/1748)| **`V`**| _Equivalent_ <br/>(3423/5671)| `V`| | | | | 
| `V`| _Equivalent_ <br/>(299/1748)| **`V`**| _Equivalent_ <br/>(3423/5671)| `V`| | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/ActCode`
| `ETH`| _Equivalent_ <br/>(331/1691)| **`ETH`**| _Equivalent_ <br/>(3505/5756)| `ETH`| | | | | 
| `ETH`| _Equivalent_ <br/>(331/1691)| **`ETH`**| _Equivalent_ <br/>(3505/5756)| `ETH`| | | | | 
| `GDIS`| _Equivalent_ <br/>(332/1692)| **`GDIS`**| _Equivalent_ <br/>(3492/5765)| `GDIS`| | | | | 
| `GDIS`| _Equivalent_ <br/>(332/1692)| **`GDIS`**| _Equivalent_ <br/>(3492/5765)| `GDIS`| | | | | 
| `HIV`| _Equivalent_ <br/>(334/1694)| **`HIV`**| _Equivalent_ <br/>(3500/5779)| `HIV`| | | | | 
| `HIV`| _Equivalent_ <br/>(334/1694)| **`HIV`**| _Equivalent_ <br/>(3500/5779)| `HIV`| | | | | 
| `PSY`| _Equivalent_ <br/>(364/1726)| **`PSY`**| _Equivalent_ <br/>(3515/5772)| `PSY`| | | | | 
| `PSY`| _Equivalent_ <br/>(364/1726)| **`PSY`**| _Equivalent_ <br/>(3515/5772)| `PSY`| | | | | 
| `SCA`| _Equivalent_ <br/>(371/1733)| **`SCA`**| _Equivalent_ <br/>(3480/5809)| `SCA`| | | | | 
| `SCA`| _Equivalent_ <br/>(371/1733)| **`SCA`**| _Equivalent_ <br/>(3480/5809)| `SCA`| | | | | 
| | | **`SOC`**| →→→→ __ →→→→ <br/>(3550)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| | | **`SOC`**| →→→→ __ →→→→ <br/>(3550)<hr/>←←←← __ ←←←← <br/>() | `active`| | | | | 
| `SDV`| _Equivalent_ <br/>(372/1734)| **`SDV`**| _Equivalent_ <br/>(3503/5789)| `SDV`| | | | | 
| `SDV`| _Equivalent_ <br/>(372/1734)| **`SDV`**| _Equivalent_ <br/>(3503/5789)| `SDV`| | | | | 
| `SEX`| _Equivalent_ <br/>(373/1735)| **`SEX`**| _Equivalent_ <br/>(3490/5748)| `SEX`| | | | | 
| `SEX`| _Equivalent_ <br/>(373/1735)| **`SEX`**| _Equivalent_ <br/>(3490/5748)| `SEX`| | | | | 
| `STD`| _Equivalent_ <br/>(376/1739)| **`STD`**| _Equivalent_ <br/>(3499/5813)| `STD`| | | | | 
| `STD`| _Equivalent_ <br/>(376/1739)| **`STD`**| _Equivalent_ <br/>(3499/5813)| `STD`| | | | | 
| `TBOO`| _Equivalent_ <br/>(378/1741)| **`TBOO`**| _Equivalent_ <br/>(3477/5800)| `TBOO`| | | | | 
| `TBOO`| _Equivalent_ <br/>(378/1741)| **`TBOO`**| _Equivalent_ <br/>(3477/5800)| `TBOO`| | | | | 
| `SICKLE`| _Equivalent_ <br/>(374/1736)| **`SICKLE`**| _Equivalent_ <br/>(3475/5804)| `SICKLE`| | | | | 
| `SICKLE`| _Equivalent_ <br/>(374/1736)| **`SICKLE`**| _Equivalent_ <br/>(3475/5804)| `SICKLE`| | | | | 
| `DEMO`| _Equivalent_ <br/>(321/1679)| **`DEMO`**| _Equivalent_ <br/>(3537/5778)| `DEMO`| | | | | 
| `DEMO`| _Equivalent_ <br/>(321/1679)| **`DEMO`**| _Equivalent_ <br/>(3537/5778)| `DEMO`| | | | | 
| `DOB`| _Equivalent_ <br/>(323/1681)| **`DOB`**| _Equivalent_ <br/>(3542/5785)| `DOB`| | | | | 
| `DOB`| _Equivalent_ <br/>(323/1681)| **`DOB`**| _Equivalent_ <br/>(3542/5785)| `DOB`| | | | | 
| `GENDER`| _Equivalent_ <br/>(333/1693)| **`GENDER`**| _Equivalent_ <br/>(3510/5786)| `GENDER`| | | | | 
| `GENDER`| _Equivalent_ <br/>(333/1693)| **`GENDER`**| _Equivalent_ <br/>(3510/5786)| `GENDER`| | | | | 
| `LIVARG`| _Equivalent_ <br/>(337/1698)| **`LIVARG`**| _Equivalent_ <br/>(3508/5746)| `LIVARG`| | | | | 
| `LIVARG`| _Equivalent_ <br/>(337/1698)| **`LIVARG`**| _Equivalent_ <br/>(3508/5746)| `LIVARG`| | | | | 
| `MARST`| _Equivalent_ <br/>(339/1700)| **`MARST`**| _Equivalent_ <br/>(3530/5814)| `MARST`| | | | | 
| `MARST`| _Equivalent_ <br/>(339/1700)| **`MARST`**| _Equivalent_ <br/>(3530/5814)| `MARST`| | | | | 
| `RACE`| _Equivalent_ <br/>(365/1727)| **`RACE`**| _Equivalent_ <br/>(3523/5761)| `RACE`| | | | | 
| `RACE`| _Equivalent_ <br/>(365/1727)| **`RACE`**| _Equivalent_ <br/>(3523/5761)| `RACE`| | | | | 
| `REL`| _Equivalent_ <br/>(367/1729)| **`REL`**| _Equivalent_ <br/>(3545/5751)| `REL`| | | | | 
| `REL`| _Equivalent_ <br/>(367/1729)| **`REL`**| _Equivalent_ <br/>(3545/5751)| `REL`| | | | | 
| `B`| _Equivalent_ <br/>(310/1667)| **`B`**| _Equivalent_ <br/>(3534/5806)| `B`| | | | | 
| `B`| _Equivalent_ <br/>(310/1667)| **`B`**| _Equivalent_ <br/>(3534/5806)| `B`| | | | | 
| `EMPL`| _Equivalent_ <br/>(326/1686)| **`EMPL`**| _Equivalent_ <br/>(3509/5815)| `EMPL`| | | | | 
| `EMPL`| _Equivalent_ <br/>(326/1686)| **`EMPL`**| _Equivalent_ <br/>(3509/5815)| `EMPL`| | | | | 
| `LOCIS`| _Equivalent_ <br/>(338/1699)| **`LOCIS`**| _Equivalent_ <br/>(3483/5811)| `LOCIS`| | | | | 
| `LOCIS`| _Equivalent_ <br/>(338/1699)| **`LOCIS`**| _Equivalent_ <br/>(3483/5811)| `LOCIS`| | | | | 
| `SSP`| _Equivalent_ <br/>(375/1738)| **`SSP`**| _Equivalent_ <br/>(3513/5759)| `SSP`| | | | | 
| `SSP`| _Equivalent_ <br/>(375/1738)| **`SSP`**| _Equivalent_ <br/>(3513/5759)| `SSP`| | | | | 
| `ADOL`| _Equivalent_ <br/>(305/1662)| **`ADOL`**| _Equivalent_ <br/>(3504/5783)| `ADOL`| | | | | 
| `ADOL`| _Equivalent_ <br/>(305/1662)| **`ADOL`**| _Equivalent_ <br/>(3504/5783)| `ADOL`| | | | | 
| `CEL`| _Equivalent_ <br/>(311/1668)| **`CEL`**| _Equivalent_ <br/>(3518/5767)| `CEL`| | | | | 
| `CEL`| _Equivalent_ <br/>(311/1668)| **`CEL`**| _Equivalent_ <br/>(3518/5767)| `CEL`| | | | | 
| `DIA`| _Equivalent_ <br/>(322/1680)| **`DIA`**| _Equivalent_ <br/>(3495/5741)| `DIA`| | | | | 
| `DIA`| _Equivalent_ <br/>(322/1680)| **`DIA`**| _Equivalent_ <br/>(3495/5741)| `DIA`| | | | | 
| `DRGIS`| _Equivalent_ <br/>(324/1683)| **`DRGIS`**| _Equivalent_ <br/>(3493/5739)| `DRGIS`| | | | | 
| `DRGIS`| _Equivalent_ <br/>(324/1683)| **`DRGIS`**| _Equivalent_ <br/>(3493/5739)| `DRGIS`| | | | | 
| `EMP`| _Equivalent_ <br/>(325/1685)| **`EMP`**| _Equivalent_ <br/>(3516/5792)| `EMP`| | | | | 
| `EMP`| _Equivalent_ <br/>(325/1685)| **`EMP`**| _Equivalent_ <br/>(3516/5792)| `EMP`| | | | | 
| `PDS`| _Equivalent_ <br/>(360/1721)| **`PDS`**| _Equivalent_ <br/>(3549/5752)| `PDS`| | | | | 
| `PDS`| _Equivalent_ <br/>(360/1721)| **`PDS`**| _Equivalent_ <br/>(3549/5752)| `PDS`| | | | | 
| `PRS`| _Equivalent_ <br/>(362/1724)| **`PRS`**| _Equivalent_ <br/>(3543/5784)| `PRS`| | | | | 
| `PRS`| _Equivalent_ <br/>(362/1724)| **`PRS`**| _Equivalent_ <br/>(3543/5784)| `PRS`| | | | | 
| `COMPT`| _Equivalent_ <br/>(312/1669)| **`COMPT`**| _Equivalent_ <br/>(3502/5810)| `COMPT`| | | | | 
| `COMPT`| _Equivalent_ <br/>(312/1669)| **`COMPT`**| _Equivalent_ <br/>(3502/5810)| `COMPT`| | | | | 
| `HRCOMPT`| _Equivalent_ <br/>(335/1695)| **`HRCOMPT`**| _Equivalent_ <br/>(3485/5736)| `HRCOMPT`| | | | | 
| `HRCOMPT`| _Equivalent_ <br/>(335/1695)| **`HRCOMPT`**| _Equivalent_ <br/>(3485/5736)| `HRCOMPT`| | | | | 
| `RESCOMPT`| _Equivalent_ <br/>(368/1730)| **`RESCOMPT`**| _Equivalent_ <br/>(3497/5774)| `RESCOMPT`| | | | | 
| `RESCOMPT`| _Equivalent_ <br/>(368/1730)| **`RESCOMPT`**| _Equivalent_ <br/>(3497/5774)| `RESCOMPT`| | | | | 
| `RMGTCOMPT`| _Equivalent_ <br/>(369/1731)| **`RMGTCOMPT`**| _Equivalent_ <br/>(3527/5764)| `RMGTCOMPT`| | | | | 
| `RMGTCOMPT`| _Equivalent_ <br/>(369/1731)| **`RMGTCOMPT`**| _Equivalent_ <br/>(3527/5764)| `RMGTCOMPT`| | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/ObservationValue`
| `ABSTRED`| _Equivalent_ <br/>(250/1623)| **`ABSTRED`**| _Equivalent_ <br/>(3409/5652)| `ABSTRED`| | | | | 
| `ABSTRED`| _Equivalent_ <br/>(250/1623)| **`ABSTRED`**| _Equivalent_ <br/>(3409/5652)| `ABSTRED`| | | | | 
| `AGGRED`| _Equivalent_ <br/>(251/1624)| **`AGGRED`**| _Equivalent_ <br/>(3404/5655)| `AGGRED`| | | | | 
| `AGGRED`| _Equivalent_ <br/>(251/1624)| **`AGGRED`**| _Equivalent_ <br/>(3404/5655)| `AGGRED`| | | | | 
| `ANONYED`| _Equivalent_ <br/>(252/1625)| **`ANONYED`**| _Equivalent_ <br/>(3417/5648)| `ANONYED`| | | | | 
| `ANONYED`| _Equivalent_ <br/>(252/1625)| **`ANONYED`**| _Equivalent_ <br/>(3417/5648)| `ANONYED`| | | | | 
| `MAPPED`| _Equivalent_ <br/>(262/1635)| **`MAPPED`**| _Equivalent_ <br/>(3413/5642)| `MAPPED`| | | | | 
| `MAPPED`| _Equivalent_ <br/>(262/1635)| **`MAPPED`**| _Equivalent_ <br/>(3413/5642)| `MAPPED`| | | | | 
| `MASKED`| _Equivalent_ <br/>(263/1636)| **`MASKED`**| _Equivalent_ <br/>(3415/5636)| `MASKED`| | | | | 
| `MASKED`| _Equivalent_ <br/>(263/1636)| **`MASKED`**| _Equivalent_ <br/>(3415/5636)| `MASKED`| | | | | 
| `PSEUDED`| _Equivalent_ <br/>(272/1645)| **`PSEUDED`**| _Equivalent_ <br/>(3388/5661)| `PSEUDED`| | | | | 
| `PSEUDED`| _Equivalent_ <br/>(272/1645)| **`PSEUDED`**| _Equivalent_ <br/>(3388/5661)| `PSEUDED`| | | | | 
| `REDACTED`| _Equivalent_ <br/>(273/1646)| **`REDACTED`**| _Equivalent_ <br/>(3397/5649)| `REDACTED`| | | | | 
| `REDACTED`| _Equivalent_ <br/>(273/1646)| **`REDACTED`**| _Equivalent_ <br/>(3397/5649)| `REDACTED`| | | | | 
| `SUBSETTED`| _Equivalent_ <br/>(277/1650)| **`SUBSETTED`**| _Equivalent_ <br/>(3399/5635)| `SUBSETTED`| | | | | 
| `SUBSETTED`| _Equivalent_ <br/>(277/1650)| **`SUBSETTED`**| _Equivalent_ <br/>(3399/5635)| `SUBSETTED`| | | | | 
| `SYNTAC`| _Equivalent_ <br/>(278/1651)| **`SYNTAC`**| _Equivalent_ <br/>(3390/5653)| `SYNTAC`| | | | | 
| `SYNTAC`| _Equivalent_ <br/>(278/1651)| **`SYNTAC`**| _Equivalent_ <br/>(3390/5653)| `SYNTAC`| | | | | 
| `TRSLT`| _Equivalent_ <br/>(279/1652)| **`TRSLT`**| _Equivalent_ <br/>(3401/5640)| `TRSLT`| | | | | 
| `TRSLT`| _Equivalent_ <br/>(279/1652)| **`TRSLT`**| _Equivalent_ <br/>(3401/5640)| `TRSLT`| | | | | 
| `VERSIONED`| _Equivalent_ <br/>(282/1655)| **`VERSIONED`**| _Equivalent_ <br/>(3403/5657)| `VERSIONED`| | | | | 
| `VERSIONED`| _Equivalent_ <br/>(282/1655)| **`VERSIONED`**| _Equivalent_ <br/>(3403/5657)| `VERSIONED`| | | | | 
| `CRYTOHASH`| _Equivalent_ <br/>(255/1628)| **`CRYTOHASH`**| _Equivalent_ <br/>(3418/5659)| `CRYTOHASH`| | | | | 
| `CRYTOHASH`| _Equivalent_ <br/>(255/1628)| **`CRYTOHASH`**| _Equivalent_ <br/>(3418/5659)| `CRYTOHASH`| | | | | 
| `DIGSIG`| _Equivalent_ <br/>(258/1631)| **`DIGSIG`**| _Equivalent_ <br/>(3394/5631)| `DIGSIG`| | | | | 
| `DIGSIG`| _Equivalent_ <br/>(258/1631)| **`DIGSIG`**| _Equivalent_ <br/>(3394/5631)| `DIGSIG`| | | | | 
| `HRELIABLE`| _Equivalent_ <br/>(261/1634)| **`HRELIABLE`**| _Equivalent_ <br/>(3396/5633)| `HRELIABLE`| | | | | 
| `HRELIABLE`| _Equivalent_ <br/>(261/1634)| **`HRELIABLE`**| _Equivalent_ <br/>(3396/5633)| `HRELIABLE`| | | | | 
| `RELIABLE`| _Equivalent_ <br/>(274/1647)| **`RELIABLE`**| _Equivalent_ <br/>(3419/5643)| `RELIABLE`| | | | | 
| `RELIABLE`| _Equivalent_ <br/>(274/1647)| **`RELIABLE`**| _Equivalent_ <br/>(3419/5643)| `RELIABLE`| | | | | 
| `UNCERTREL`| _Equivalent_ <br/>(280/1653)| **`UNCERTREL`**| _Equivalent_ <br/>(3389/5658)| `UNCERTREL`| | | | | 
| `UNCERTREL`| _Equivalent_ <br/>(280/1653)| **`UNCERTREL`**| _Equivalent_ <br/>(3389/5658)| `UNCERTREL`| | | | | 
| `UNRELIABLE`| _Equivalent_ <br/>(281/1654)| **`UNRELIABLE`**| _Equivalent_ <br/>(3395/5639)| `UNRELIABLE`| | | | | 
| `UNRELIABLE`| _Equivalent_ <br/>(281/1654)| **`UNRELIABLE`**| _Equivalent_ <br/>(3395/5639)| `UNRELIABLE`| | | | | 
| `CLINAST`| _Equivalent_ <br/>(253/1626)| **`CLINAST`**| _Equivalent_ <br/>(3416/5634)| `CLINAST`| | | | | 
| `CLINAST`| _Equivalent_ <br/>(253/1626)| **`CLINAST`**| _Equivalent_ <br/>(3416/5634)| `CLINAST`| | | | | 
| `DEVAST`| _Equivalent_ <br/>(256/1629)| **`DEVAST`**| _Equivalent_ <br/>(3391/5638)| `DEVAST`| | | | | 
| `DEVAST`| _Equivalent_ <br/>(256/1629)| **`DEVAST`**| _Equivalent_ <br/>(3391/5638)| `DEVAST`| | | | | 
| `HCPAST`| _Equivalent_ <br/>(259/1632)| **`HCPAST`**| _Equivalent_ <br/>(3414/5632)| `HCPAST`| | | | | 
| `HCPAST`| _Equivalent_ <br/>(259/1632)| **`HCPAST`**| _Equivalent_ <br/>(3414/5632)| `HCPAST`| | | | | 
| `PACQAST`| _Equivalent_ <br/>(264/1637)| **`PACQAST`**| _Equivalent_ <br/>(3407/5641)| `PACQAST`| | | | | 
| `PACQAST`| _Equivalent_ <br/>(264/1637)| **`PACQAST`**| _Equivalent_ <br/>(3407/5641)| `PACQAST`| | | | | 
| `PATAST`| _Equivalent_ <br/>(266/1639)| **`PATAST`**| _Equivalent_ <br/>(3392/5646)| `PATAST`| | | | | 
| `PATAST`| _Equivalent_ <br/>(266/1639)| **`PATAST`**| _Equivalent_ <br/>(3392/5646)| `PATAST`| | | | | 
| `PAYAST`| _Equivalent_ <br/>(268/1641)| **`PAYAST`**| _Equivalent_ <br/>(3411/5663)| `PAYAST`| | | | | 
| `PAYAST`| _Equivalent_ <br/>(268/1641)| **`PAYAST`**| _Equivalent_ <br/>(3411/5663)| `PAYAST`| | | | | 
| `PROAST`| _Equivalent_ <br/>(270/1643)| **`PROAST`**| _Equivalent_ <br/>(3410/5647)| `PROAST`| | | | | 
| `PROAST`| _Equivalent_ <br/>(270/1643)| **`PROAST`**| _Equivalent_ <br/>(3410/5647)| `PROAST`| | | | | 
| `SDMAST`| _Equivalent_ <br/>(275/1648)| **`SDMAST`**| _Equivalent_ <br/>(3398/5656)| `SDMAST`| | | | | 
| `SDMAST`| _Equivalent_ <br/>(275/1648)| **`SDMAST`**| _Equivalent_ <br/>(3398/5656)| `SDMAST`| | | | | 
| `CLINRPT`| _Equivalent_ <br/>(254/1627)| **`CLINRPT`**| _Equivalent_ <br/>(3402/5651)| `CLINRPT`| | | | | 
| `CLINRPT`| _Equivalent_ <br/>(254/1627)| **`CLINRPT`**| _Equivalent_ <br/>(3402/5651)| `CLINRPT`| | | | | 
| `DEVRPT`| _Equivalent_ <br/>(257/1630)| **`DEVRPT`**| _Equivalent_ <br/>(3412/5645)| `DEVRPT`| | | | | 
| `DEVRPT`| _Equivalent_ <br/>(257/1630)| **`DEVRPT`**| _Equivalent_ <br/>(3412/5645)| `DEVRPT`| | | | | 
| `HCPRPT`| _Equivalent_ <br/>(260/1633)| **`HCPRPT`**| _Equivalent_ <br/>(3405/5662)| `HCPRPT`| | | | | 
| `HCPRPT`| _Equivalent_ <br/>(260/1633)| **`HCPRPT`**| _Equivalent_ <br/>(3405/5662)| `HCPRPT`| | | | | 
| `PACQRPT`| _Equivalent_ <br/>(265/1638)| **`PACQRPT`**| _Equivalent_ <br/>(3408/5654)| `PACQRPT`| | | | | 
| `PACQRPT`| _Equivalent_ <br/>(265/1638)| **`PACQRPT`**| _Equivalent_ <br/>(3408/5654)| `PACQRPT`| | | | | 
| `PATRPT`| _Equivalent_ <br/>(267/1640)| **`PATRPT`**| _Equivalent_ <br/>(3420/5660)| `PATRPT`| | | | | 
| `PATRPT`| _Equivalent_ <br/>(267/1640)| **`PATRPT`**| _Equivalent_ <br/>(3420/5660)| `PATRPT`| | | | | 
| `PAYRPT`| _Equivalent_ <br/>(269/1642)| **`PAYRPT`**| _Equivalent_ <br/>(3406/5637)| `PAYRPT`| | | | | 
| `PAYRPT`| _Equivalent_ <br/>(269/1642)| **`PAYRPT`**| _Equivalent_ <br/>(3406/5637)| `PAYRPT`| | | | | 
| `PRORPT`| _Equivalent_ <br/>(271/1644)| **`PRORPT`**| _Equivalent_ <br/>(3400/5644)| `PRORPT`| | | | | 
| `PRORPT`| _Equivalent_ <br/>(271/1644)| **`PRORPT`**| _Equivalent_ <br/>(3400/5644)| `PRORPT`| | | | | 
| `SDMRPT`| _Equivalent_ <br/>(276/1649)| **`SDMRPT`**| _Equivalent_ <br/>(3393/5650)| `SDMRPT`| | | | | 
| `SDMRPT`| _Equivalent_ <br/>(276/1649)| **`SDMRPT`**| _Equivalent_ <br/>(3393/5650)| `SDMRPT`| | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/ActCode`
| `SecurityPolicy`| _Equivalent_ <br/>(377/1740)| **`SecurityPolicy`**| _Equivalent_ <br/>(3476/5749)| `SecurityPolicy`| | | | | 
| `SecurityPolicy`| _Equivalent_ <br/>(377/1740)| **`SecurityPolicy`**| _Equivalent_ <br/>(3476/5749)| `SecurityPolicy`| | | | | 
| `ObligationPolicy`| _Equivalent_ <br/>(359/1720)| **`ObligationPolicy`**| _Equivalent_ <br/>(3540/5754)| `ObligationPolicy`| | | | | 
| `ObligationPolicy`| _Equivalent_ <br/>(359/1720)| **`ObligationPolicy`**| _Equivalent_ <br/>(3540/5754)| `ObligationPolicy`| | | | | 
| `ANONY`| _Equivalent_ <br/>(306/1663)| **`ANONY`**| _Equivalent_ <br/>(3496/5768)| `ANONY`| | | | | 
| `ANONY`| _Equivalent_ <br/>(306/1663)| **`ANONY`**| _Equivalent_ <br/>(3496/5768)| `ANONY`| | | | | 
| `AOD`| _Equivalent_ <br/>(307/1664)| **`AOD`**| _Equivalent_ <br/>(3529/5791)| `AOD`| | | | | 
| `AOD`| _Equivalent_ <br/>(307/1664)| **`AOD`**| _Equivalent_ <br/>(3529/5791)| `AOD`| | | | | 
| `AUDIT`| _Equivalent_ <br/>(308/1665)| **`AUDIT`**| _Equivalent_ <br/>(3484/5796)| `AUDIT`| | | | | 
| `AUDIT`| _Equivalent_ <br/>(308/1665)| **`AUDIT`**| _Equivalent_ <br/>(3484/5796)| `AUDIT`| | | | | 
| `AUDTR`| _Equivalent_ <br/>(309/1666)| **`AUDTR`**| _Equivalent_ <br/>(3472/5776)| `AUDTR`| | | | | 
| `AUDTR`| _Equivalent_ <br/>(309/1666)| **`AUDTR`**| _Equivalent_ <br/>(3472/5776)| `AUDTR`| | | | | 
| `CPLYCC`| _Equivalent_ <br/>(313/1670)| **`CPLYCC`**| _Equivalent_ <br/>(3541/5744)| `CPLYCC`| | | | | 
| `CPLYCC`| _Equivalent_ <br/>(313/1670)| **`CPLYCC`**| _Equivalent_ <br/>(3541/5744)| `CPLYCC`| | | | | 
| `CPLYCD`| _Equivalent_ <br/>(314/1671)| **`CPLYCD`**| _Equivalent_ <br/>(3471/5750)| `CPLYCD`| | | | | 
| `CPLYCD`| _Equivalent_ <br/>(314/1671)| **`CPLYCD`**| _Equivalent_ <br/>(3471/5750)| `CPLYCD`| | | | | 
| `CPLYJPP`| _Equivalent_ <br/>(315/1672)| **`CPLYJPP`**| _Equivalent_ <br/>(3478/5777)| `CPLYJPP`| | | | | 
| `CPLYJPP`| _Equivalent_ <br/>(315/1672)| **`CPLYJPP`**| _Equivalent_ <br/>(3478/5777)| `CPLYJPP`| | | | | 
| `CPLYOPP`| _Equivalent_ <br/>(316/1673)| **`CPLYOPP`**| _Equivalent_ <br/>(3528/5781)| `CPLYOPP`| | | | | 
| `CPLYOPP`| _Equivalent_ <br/>(316/1673)| **`CPLYOPP`**| _Equivalent_ <br/>(3528/5781)| `CPLYOPP`| | | | | 
| `CPLYOSP`| _Equivalent_ <br/>(317/1674)| **`CPLYOSP`**| _Equivalent_ <br/>(3525/5742)| `CPLYOSP`| | | | | 
| `CPLYOSP`| _Equivalent_ <br/>(317/1674)| **`CPLYOSP`**| _Equivalent_ <br/>(3525/5742)| `CPLYOSP`| | | | | 
| `CPLYPOL`| _Equivalent_ <br/>(318/1675)| **`CPLYPOL`**| _Equivalent_ <br/>(3494/5769)| `CPLYPOL`| | | | | 
| `CPLYPOL`| _Equivalent_ <br/>(318/1675)| **`CPLYPOL`**| _Equivalent_ <br/>(3494/5769)| `CPLYPOL`| | | | | 
| | | **`DECLASSIFYLABEL`**| _Equivalent_ <br/>(3548/5799)| `DECLASSIFYLABEL`| | | | | 
| | | **`DECLASSIFYLABEL`**| _Equivalent_ <br/>(3548/5799)| `DECLASSIFYLABEL`| | | | | 
| `DEID`| _Equivalent_ <br/>(319/1677)| **`DEID`**| _Equivalent_ <br/>(3517/5788)| `DEID`| | | | | 
| `DEID`| _Equivalent_ <br/>(319/1677)| **`DEID`**| _Equivalent_ <br/>(3517/5788)| `DEID`| | | | | 
| `DELAU`| _Equivalent_ <br/>(320/1678)| **`DELAU`**| _Equivalent_ <br/>(3526/5807)| `DELAU`| | | | | 
| `DELAU`| _Equivalent_ <br/>(320/1678)| **`DELAU`**| _Equivalent_ <br/>(3526/5807)| `DELAU`| | | | | 
| | | **`DOWNGRDLABEL`**| _Equivalent_ <br/>(3514/5775)| `DOWNGRDLABEL`| | | | | 
| | | **`DOWNGRDLABEL`**| _Equivalent_ <br/>(3514/5775)| `DOWNGRDLABEL`| | | | | 
| | | **`DRIVLABEL`**| _Equivalent_ <br/>(3519/5757)| `DRIVLABEL`| | | | | 
| | | **`DRIVLABEL`**| _Equivalent_ <br/>(3519/5757)| `DRIVLABEL`| | | | | 
| `ENCRYPT`| _Equivalent_ <br/>(327/1687)| **`ENCRYPT`**| _Equivalent_ <br/>(3524/5763)| `ENCRYPT`| | | | | 
| `ENCRYPT`| _Equivalent_ <br/>(327/1687)| **`ENCRYPT`**| _Equivalent_ <br/>(3524/5763)| `ENCRYPT`| | | | | 
| `ENCRYPTR`| _Equivalent_ <br/>(328/1688)| **`ENCRYPTR`**| _Equivalent_ <br/>(3506/5770)| `ENCRYPTR`| | | | | 
| `ENCRYPTR`| _Equivalent_ <br/>(328/1688)| **`ENCRYPTR`**| _Equivalent_ <br/>(3506/5770)| `ENCRYPTR`| | | | | 
| `ENCRYPTT`| _Equivalent_ <br/>(329/1689)| **`ENCRYPTT`**| _Equivalent_ <br/>(3507/5801)| `ENCRYPTT`| | | | | 
| `ENCRYPTT`| _Equivalent_ <br/>(329/1689)| **`ENCRYPTT`**| _Equivalent_ <br/>(3507/5801)| `ENCRYPTT`| | | | | 
| `ENCRYPTU`| _Equivalent_ <br/>(330/1690)| **`ENCRYPTU`**| _Equivalent_ <br/>(3486/5738)| `ENCRYPTU`| | | | | 
| `ENCRYPTU`| _Equivalent_ <br/>(330/1690)| **`ENCRYPTU`**| _Equivalent_ <br/>(3486/5738)| `ENCRYPTU`| | | | | 
| `HUAPRV`| _Equivalent_ <br/>(336/1696)| **`HUAPRV`**| _Equivalent_ <br/>(3479/5793)| `HUAPRV`| | | | | 
| `HUAPRV`| _Equivalent_ <br/>(336/1696)| **`HUAPRV`**| _Equivalent_ <br/>(3479/5793)| `HUAPRV`| | | | | 
| | | **`LABEL`**| _Equivalent_ <br/>(3531/5795)| `LABEL`| | | | | 
| | | **`LABEL`**| _Equivalent_ <br/>(3531/5795)| `LABEL`| | | | | 
| `MASK`| _Equivalent_ <br/>(340/1701)| **`MASK`**| _Equivalent_ <br/>(3474/5762)| `MASK`| | | | | 
| `MASK`| _Equivalent_ <br/>(340/1701)| **`MASK`**| _Equivalent_ <br/>(3474/5762)| `MASK`| | | | | 
| `MINEC`| _Equivalent_ <br/>(341/1702)| **`MINEC`**| _Equivalent_ <br/>(3535/5760)| `MINEC`| | | | | 
| `MINEC`| _Equivalent_ <br/>(341/1702)| **`MINEC`**| _Equivalent_ <br/>(3535/5760)| `MINEC`| | | | | 
| | | **`PERSISTLABEL`**| _Equivalent_ <br/>(3512/5790)| `PERSISTLABEL`| | | | | 
| | | **`PERSISTLABEL`**| _Equivalent_ <br/>(3512/5790)| `PERSISTLABEL`| | | | | 
| `PRIVMARK`| _Equivalent_ <br/>(361/1723)| **`PRIVMARK`**| _Equivalent_ <br/>(3521/5747)| `PRIVMARK`| | | | | 
| `PRIVMARK`| _Equivalent_ <br/>(361/1723)| **`PRIVMARK`**| _Equivalent_ <br/>(3521/5747)| `PRIVMARK`| | | | | 
| `PSEUD`| _Equivalent_ <br/>(363/1725)| **`PSEUD`**| _Equivalent_ <br/>(3520/5745)| `PSEUD`| | | | | 
| `PSEUD`| _Equivalent_ <br/>(363/1725)| **`PSEUD`**| _Equivalent_ <br/>(3520/5745)| `PSEUD`| | | | | 
| `REDACT`| _Equivalent_ <br/>(366/1728)| **`REDACT`**| _Equivalent_ <br/>(3501/5740)| `REDACT`| | | | | 
| `REDACT`| _Equivalent_ <br/>(366/1728)| **`REDACT`**| _Equivalent_ <br/>(3501/5740)| `REDACT`| | | | | 
| | | **`UPGRDLABEL`**| _Equivalent_ <br/>(3481/5780)| `UPGRDLABEL`| | | | | 
| | | **`UPGRDLABEL`**| _Equivalent_ <br/>(3481/5780)| `UPGRDLABEL`| | | | | 
| `RefrainPolicy`| _Equivalent_ <br/>(370/1732)| **`RefrainPolicy`**| _Equivalent_ <br/>(3473/5805)| `RefrainPolicy`| | | | | 
| `RefrainPolicy`| _Equivalent_ <br/>(370/1732)| **`RefrainPolicy`**| _Equivalent_ <br/>(3473/5805)| `RefrainPolicy`| | | | | 
| `NOAUTH`| _Equivalent_ <br/>(342/1703)| **`NOAUTH`**| _Equivalent_ <br/>(3470/5771)| `NOAUTH`| | | | | 
| `NOAUTH`| _Equivalent_ <br/>(342/1703)| **`NOAUTH`**| _Equivalent_ <br/>(3470/5771)| `NOAUTH`| | | | | 
| `NOCOLLECT`| _Equivalent_ <br/>(343/1704)| **`NOCOLLECT`**| _Equivalent_ <br/>(3533/5758)| `NOCOLLECT`| | | | | 
| `NOCOLLECT`| _Equivalent_ <br/>(343/1704)| **`NOCOLLECT`**| _Equivalent_ <br/>(3533/5758)| `NOCOLLECT`| | | | | 
| `NODSCLCD`| _Equivalent_ <br/>(344/1705)| **`NODSCLCD`**| _Equivalent_ <br/>(3511/5766)| `NODSCLCD`| | | | | 
| `NODSCLCD`| _Equivalent_ <br/>(344/1705)| **`NODSCLCD`**| _Equivalent_ <br/>(3511/5766)| `NODSCLCD`| | | | | 
| `NODSCLCDS`| _Equivalent_ <br/>(345/1706)| **`NODSCLCDS`**| _Equivalent_ <br/>(3547/5787)| `NODSCLCDS`| | | | | 
| `NODSCLCDS`| _Equivalent_ <br/>(345/1706)| **`NODSCLCDS`**| _Equivalent_ <br/>(3547/5787)| `NODSCLCDS`| | | | | 
| `NOINTEGRATE`| _Equivalent_ <br/>(346/1707)| **`NOINTEGRATE`**| _Equivalent_ <br/>(3532/5794)| `NOINTEGRATE`| | | | | 
| `NOINTEGRATE`| _Equivalent_ <br/>(346/1707)| **`NOINTEGRATE`**| _Equivalent_ <br/>(3532/5794)| `NOINTEGRATE`| | | | | 
| `NOLIST`| _Equivalent_ <br/>(347/1708)| **`NOLIST`**| _Equivalent_ <br/>(3488/5808)| `NOLIST`| | | | | 
| `NOLIST`| _Equivalent_ <br/>(347/1708)| **`NOLIST`**| _Equivalent_ <br/>(3488/5808)| `NOLIST`| | | | | 
| `NOMOU`| _Equivalent_ <br/>(348/1709)| **`NOMOU`**| _Equivalent_ <br/>(3498/5753)| `NOMOU`| | | | | 
| `NOMOU`| _Equivalent_ <br/>(348/1709)| **`NOMOU`**| _Equivalent_ <br/>(3498/5753)| `NOMOU`| | | | | 
| `NOORGPOL`| _Equivalent_ <br/>(349/1710)| **`NOORGPOL`**| _Equivalent_ <br/>(3522/5812)| `NOORGPOL`| | | | | 
| `NOORGPOL`| _Equivalent_ <br/>(349/1710)| **`NOORGPOL`**| _Equivalent_ <br/>(3522/5812)| `NOORGPOL`| | | | | 
| `NOPAT`| _Equivalent_ <br/>(350/1711)| **`NOPAT`**| _Equivalent_ <br/>(3482/5803)| `NOPAT`| | | | | 
| `NOPAT`| _Equivalent_ <br/>(350/1711)| **`NOPAT`**| _Equivalent_ <br/>(3482/5803)| `NOPAT`| | | | | 
| `NOPERSISTP`| _Equivalent_ <br/>(351/1712)| **`NOPERSISTP`**| _Equivalent_ <br/>(3539/5773)| `NOPERSISTP`| | | | | 
| `NOPERSISTP`| _Equivalent_ <br/>(351/1712)| **`NOPERSISTP`**| _Equivalent_ <br/>(3539/5773)| `NOPERSISTP`| | | | | 
| `NORDSCLCD`| _Equivalent_ <br/>(352/1713)| **`NORDSCLCD`**| _Equivalent_ <br/>(3544/5782)| `NORDSCLCD`| | | | | 
| `NORDSCLCD`| _Equivalent_ <br/>(352/1713)| **`NORDSCLCD`**| _Equivalent_ <br/>(3544/5782)| `NORDSCLCD`| | | | | 
| `NORDSCLCDS`| _Equivalent_ <br/>(353/1714)| **`NORDSCLCDS`**| _Equivalent_ <br/>(3538/5737)| `NORDSCLCDS`| | | | | 
| `NORDSCLCDS`| _Equivalent_ <br/>(353/1714)| **`NORDSCLCDS`**| _Equivalent_ <br/>(3538/5737)| `NORDSCLCDS`| | | | | 
| `NORDSCLW`| _Equivalent_ <br/>(354/1715)| **`NORDSCLW`**| _Equivalent_ <br/>(3487/5743)| `NORDSCLW`| | | | | 
| `NORDSCLW`| _Equivalent_ <br/>(354/1715)| **`NORDSCLW`**| _Equivalent_ <br/>(3487/5743)| `NORDSCLW`| | | | | 
| `NORELINK`| _Equivalent_ <br/>(355/1716)| **`NORELINK`**| _Equivalent_ <br/>(3491/5802)| `NORELINK`| | | | | 
| `NORELINK`| _Equivalent_ <br/>(355/1716)| **`NORELINK`**| _Equivalent_ <br/>(3491/5802)| `NORELINK`| | | | | 
| `NOREUSE`| _Equivalent_ <br/>(356/1717)| **`NOREUSE`**| _Equivalent_ <br/>(3489/5798)| `NOREUSE`| | | | | 
| `NOREUSE`| _Equivalent_ <br/>(356/1717)| **`NOREUSE`**| _Equivalent_ <br/>(3489/5798)| `NOREUSE`| | | | | 
| `NOVIP`| _Equivalent_ <br/>(357/1718)| **`NOVIP`**| _Equivalent_ <br/>(3546/5755)| `NOVIP`| | | | | 
| `NOVIP`| _Equivalent_ <br/>(357/1718)| **`NOVIP`**| _Equivalent_ <br/>(3546/5755)| `NOVIP`| | | | | 
| `ORCON`| _Equivalent_ <br/>(358/1719)| **`ORCON`**| _Equivalent_ <br/>(3536/5797)| `ORCON`| | | | | 
| `ORCON`| _Equivalent_ <br/>(358/1719)| **`ORCON`**| _Equivalent_ <br/>(3536/5797)| `ORCON`| | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/ActReason`
| `PurposeOfUse`| _Equivalent_ <br/>(415/1785)| **`PurposeOfUse`**| _Equivalent_ <br/>(3462/5715)| `PurposeOfUse`| | | | | 
| `PurposeOfUse`| _Equivalent_ <br/>(415/1785)| **`PurposeOfUse`**| _Equivalent_ <br/>(3462/5715)| `PurposeOfUse`| | | | | 
| `HMARKT`| _Equivalent_ <br/>(399/1769)| **`HMARKT`**| _Equivalent_ <br/>(3449/5713)| `HMARKT`| | | | | 
| `HMARKT`| _Equivalent_ <br/>(399/1769)| **`HMARKT`**| _Equivalent_ <br/>(3449/5713)| `HMARKT`| | | | | 
| `HOPERAT`| _Equivalent_ <br/>(400/1770)| **`HOPERAT`**| _Equivalent_ <br/>(3460/5696)| `HOPERAT`| | | | | 
| `HOPERAT`| _Equivalent_ <br/>(400/1770)| **`HOPERAT`**| _Equivalent_ <br/>(3460/5696)| `HOPERAT`| | | | | 
| `DONAT`| _Equivalent_ <br/>(386/1756)| **`DONAT`**| _Equivalent_ <br/>(3457/5693)| `DONAT`| | | | | 
| `DONAT`| _Equivalent_ <br/>(386/1756)| **`DONAT`**| _Equivalent_ <br/>(3457/5693)| `DONAT`| | | | | 
| `FRAUD`| _Equivalent_ <br/>(392/1762)| **`FRAUD`**| _Equivalent_ <br/>(3465/5681)| `FRAUD`| | | | | 
| `FRAUD`| _Equivalent_ <br/>(392/1762)| **`FRAUD`**| _Equivalent_ <br/>(3465/5681)| `FRAUD`| | | | | 
| `GOV`| _Equivalent_ <br/>(393/1763)| **`GOV`**| _Equivalent_ <br/>(3458/5685)| `GOV`| | | | | 
| `GOV`| _Equivalent_ <br/>(393/1763)| **`GOV`**| _Equivalent_ <br/>(3458/5685)| `GOV`| | | | | 
| `HACCRED`| _Equivalent_ <br/>(394/1764)| **`HACCRED`**| _Equivalent_ <br/>(3427/5692)| `HACCRED`| | | | | 
| `HACCRED`| _Equivalent_ <br/>(394/1764)| **`HACCRED`**| _Equivalent_ <br/>(3427/5692)| `HACCRED`| | | | | 
| `HCOMPL`| _Equivalent_ <br/>(395/1765)| **`HCOMPL`**| _Equivalent_ <br/>(3466/5698)| `HCOMPL`| | | | | 
| `HCOMPL`| _Equivalent_ <br/>(395/1765)| **`HCOMPL`**| _Equivalent_ <br/>(3466/5698)| `HCOMPL`| | | | | 
| `HDECD`| _Equivalent_ <br/>(396/1766)| **`HDECD`**| _Equivalent_ <br/>(3447/5701)| `HDECD`| | | | | 
| `HDECD`| _Equivalent_ <br/>(396/1766)| **`HDECD`**| _Equivalent_ <br/>(3447/5701)| `HDECD`| | | | | 
| `HDIRECT`| _Equivalent_ <br/>(397/1767)| **`HDIRECT`**| _Equivalent_ <br/>(3453/5689)| `HDIRECT`| | | | | 
| `HDIRECT`| _Equivalent_ <br/>(397/1767)| **`HDIRECT`**| _Equivalent_ <br/>(3453/5689)| `HDIRECT`| | | | | 
| `HLEGAL`| _Equivalent_ <br/>(398/1768)| **`HLEGAL`**| _Equivalent_ <br/>(3448/5694)| `HLEGAL`| | | | | 
| `HLEGAL`| _Equivalent_ <br/>(398/1768)| **`HLEGAL`**| _Equivalent_ <br/>(3448/5694)| `HLEGAL`| | | | | 
| `HOUTCOMS`| _Equivalent_ <br/>(401/1771)| **`HOUTCOMS`**| _Equivalent_ <br/>(3452/5711)| `HOUTCOMS`| | | | | 
| `HOUTCOMS`| _Equivalent_ <br/>(401/1771)| **`HOUTCOMS`**| _Equivalent_ <br/>(3452/5711)| `HOUTCOMS`| | | | | 
| `HPRGRP`| _Equivalent_ <br/>(403/1773)| **`HPRGRP`**| _Equivalent_ <br/>(3438/5708)| `HPRGRP`| | | | | 
| `HPRGRP`| _Equivalent_ <br/>(403/1773)| **`HPRGRP`**| _Equivalent_ <br/>(3438/5708)| `HPRGRP`| | | | | 
| `HQUALIMP`| _Equivalent_ <br/>(404/1774)| **`HQUALIMP`**| _Equivalent_ <br/>(3442/5700)| `HQUALIMP`| | | | | 
| `HQUALIMP`| _Equivalent_ <br/>(404/1774)| **`HQUALIMP`**| _Equivalent_ <br/>(3442/5700)| `HQUALIMP`| | | | | 
| `HSYSADMIN`| _Equivalent_ <br/>(406/1776)| **`HSYSADMIN`**| _Equivalent_ <br/>(3445/5677)| `HSYSADMIN`| | | | | 
| `HSYSADMIN`| _Equivalent_ <br/>(406/1776)| **`HSYSADMIN`**| _Equivalent_ <br/>(3445/5677)| `HSYSADMIN`| | | | | 
| `MEMADMIN`| _Equivalent_ <br/>(407/1777)| **`MEMADMIN`**| _Equivalent_ <br/>(3461/5678)| `MEMADMIN`| | | | | 
| `MEMADMIN`| _Equivalent_ <br/>(407/1777)| **`MEMADMIN`**| _Equivalent_ <br/>(3461/5678)| `MEMADMIN`| | | | | 
| `PATADMIN`| _Equivalent_ <br/>(408/1778)| **`PATADMIN`**| _Equivalent_ <br/>(3435/5684)| `PATADMIN`| | | | | 
| `PATADMIN`| _Equivalent_ <br/>(408/1778)| **`PATADMIN`**| _Equivalent_ <br/>(3435/5684)| `PATADMIN`| | | | | 
| `PATSFTY`| _Equivalent_ <br/>(410/1780)| **`PATSFTY`**| _Equivalent_ <br/>(3446/5682)| `PATSFTY`| | | | | 
| `PATSFTY`| _Equivalent_ <br/>(410/1780)| **`PATSFTY`**| _Equivalent_ <br/>(3446/5682)| `PATSFTY`| | | | | 
| `PERFMSR`| _Equivalent_ <br/>(411/1781)| **`PERFMSR`**| _Equivalent_ <br/>(3432/5707)| `PERFMSR`| | | | | 
| `PERFMSR`| _Equivalent_ <br/>(411/1781)| **`PERFMSR`**| _Equivalent_ <br/>(3432/5707)| `PERFMSR`| | | | | 
| `RECORDMGT`| _Equivalent_ <br/>(416/1786)| **`RECORDMGT`**| _Equivalent_ <br/>(3443/5683)| `RECORDMGT`| | | | | 
| `RECORDMGT`| _Equivalent_ <br/>(416/1786)| **`RECORDMGT`**| _Equivalent_ <br/>(3443/5683)| `RECORDMGT`| | | | | 
| `TRAIN`| _Equivalent_ <br/>(420/1790)| **`TRAIN`**| _Equivalent_ <br/>(3439/5695)| `TRAIN`| | | | | 
| `TRAIN`| _Equivalent_ <br/>(420/1790)| **`TRAIN`**| _Equivalent_ <br/>(3439/5695)| `TRAIN`| | | | | 
| `HPAYMT`| _Equivalent_ <br/>(402/1772)| **`HPAYMT`**| _Equivalent_ <br/>(3456/5687)| `HPAYMT`| | | | | 
| `HPAYMT`| _Equivalent_ <br/>(402/1772)| **`HPAYMT`**| _Equivalent_ <br/>(3456/5687)| `HPAYMT`| | | | | 
| `CLMATTCH`| _Equivalent_ <br/>(382/1752)| **`CLMATTCH`**| _Equivalent_ <br/>(3464/5691)| `CLMATTCH`| | | | | 
| `CLMATTCH`| _Equivalent_ <br/>(382/1752)| **`CLMATTCH`**| _Equivalent_ <br/>(3464/5691)| `CLMATTCH`| | | | | 
| `COVAUTH`| _Equivalent_ <br/>(383/1753)| **`COVAUTH`**| _Equivalent_ <br/>(3459/5688)| `COVAUTH`| | | | | 
| `COVAUTH`| _Equivalent_ <br/>(383/1753)| **`COVAUTH`**| _Equivalent_ <br/>(3459/5688)| `COVAUTH`| | | | | 
| `COVERAGE`| _Equivalent_ <br/>(384/1754)| **`COVERAGE`**| _Equivalent_ <br/>(3467/5706)| `COVERAGE`| | | | | 
| `COVERAGE`| _Equivalent_ <br/>(384/1754)| **`COVERAGE`**| _Equivalent_ <br/>(3467/5706)| `COVERAGE`| | | | | 
| `ELIGDTRM`| _Equivalent_ <br/>(387/1757)| **`ELIGDTRM`**| _Equivalent_ <br/>(3428/5704)| `ELIGDTRM`| | | | | 
| `ELIGDTRM`| _Equivalent_ <br/>(387/1757)| **`ELIGDTRM`**| _Equivalent_ <br/>(3428/5704)| `ELIGDTRM`| | | | | 
| `ELIGVER`| _Equivalent_ <br/>(388/1758)| **`ELIGVER`**| _Equivalent_ <br/>(3468/5709)| `ELIGVER`| | | | | 
| `ELIGVER`| _Equivalent_ <br/>(388/1758)| **`ELIGVER`**| _Equivalent_ <br/>(3468/5709)| `ELIGVER`| | | | | 
| `ENROLLM`| _Equivalent_ <br/>(389/1759)| **`ENROLLM`**| _Equivalent_ <br/>(3437/5705)| `ENROLLM`| | | | | 
| `ENROLLM`| _Equivalent_ <br/>(389/1759)| **`ENROLLM`**| _Equivalent_ <br/>(3437/5705)| `ENROLLM`| | | | | 
| `REMITADV`| _Equivalent_ <br/>(417/1787)| **`REMITADV`**| _Equivalent_ <br/>(3441/5699)| `REMITADV`| | | | | 
| `REMITADV`| _Equivalent_ <br/>(417/1787)| **`REMITADV`**| _Equivalent_ <br/>(3441/5699)| `REMITADV`| | | | | 
| `HRESCH`| _Equivalent_ <br/>(405/1775)| **`HRESCH`**| _Equivalent_ <br/>(3436/5676)| `HRESCH`| | | | | 
| `HRESCH`| _Equivalent_ <br/>(405/1775)| **`HRESCH`**| _Equivalent_ <br/>(3436/5676)| `HRESCH`| | | | | 
| `CLINTRCH`| _Equivalent_ <br/>(380/1750)| **`CLINTRCH`**| _Equivalent_ <br/>(3430/5702)| `CLINTRCH`| | | | | 
| `CLINTRCH`| _Equivalent_ <br/>(380/1750)| **`CLINTRCH`**| _Equivalent_ <br/>(3430/5702)| `CLINTRCH`| | | | | 
| `PATRQT`| _Equivalent_ <br/>(409/1779)| **`PATRQT`**| _Equivalent_ <br/>(3463/5716)| `PATRQT`| | | | | 
| `PATRQT`| _Equivalent_ <br/>(409/1779)| **`PATRQT`**| _Equivalent_ <br/>(3463/5716)| `PATRQT`| | | | | 
| `FAMRQT`| _Equivalent_ <br/>(391/1761)| **`FAMRQT`**| _Equivalent_ <br/>(3451/5703)| `FAMRQT`| | | | | 
| `FAMRQT`| _Equivalent_ <br/>(391/1761)| **`FAMRQT`**| _Equivalent_ <br/>(3451/5703)| `FAMRQT`| | | | | 
| `PWATRNY`| _Equivalent_ <br/>(414/1784)| **`PWATRNY`**| _Equivalent_ <br/>(3431/5686)| `PWATRNY`| | | | | 
| `PWATRNY`| _Equivalent_ <br/>(414/1784)| **`PWATRNY`**| _Equivalent_ <br/>(3431/5686)| `PWATRNY`| | | | | 
| `SUPNWK`| _Equivalent_ <br/>(418/1788)| **`SUPNWK`**| _Equivalent_ <br/>(3450/5697)| `SUPNWK`| | | | | 
| `SUPNWK`| _Equivalent_ <br/>(418/1788)| **`SUPNWK`**| _Equivalent_ <br/>(3450/5697)| `SUPNWK`| | | | | 
| `PUBHLTH`| _Equivalent_ <br/>(413/1783)| **`PUBHLTH`**| _Equivalent_ <br/>(3434/5712)| `PUBHLTH`| | | | | 
| `PUBHLTH`| _Equivalent_ <br/>(413/1783)| **`PUBHLTH`**| _Equivalent_ <br/>(3434/5712)| `PUBHLTH`| | | | | 
| `DISASTER`| _Equivalent_ <br/>(385/1755)| **`DISASTER`**| _Equivalent_ <br/>(3455/5717)| `DISASTER`| | | | | 
| `DISASTER`| _Equivalent_ <br/>(385/1755)| **`DISASTER`**| _Equivalent_ <br/>(3455/5717)| `DISASTER`| | | | | 
| `THREAT`| _Equivalent_ <br/>(419/1789)| **`THREAT`**| _Equivalent_ <br/>(3469/5714)| `THREAT`| | | | | 
| `THREAT`| _Equivalent_ <br/>(419/1789)| **`THREAT`**| _Equivalent_ <br/>(3469/5714)| `THREAT`| | | | | 
| `TREAT`| _Equivalent_ <br/>(421/1791)| **`TREAT`**| _Equivalent_ <br/>(3433/5710)| `TREAT`| | | | | 
| `TREAT`| _Equivalent_ <br/>(421/1791)| **`TREAT`**| _Equivalent_ <br/>(3433/5710)| `TREAT`| | | | | 
| `CAREMGT`| _Equivalent_ <br/>(379/1749)| **`CAREMGT`**| _Equivalent_ <br/>(3444/5679)| `CAREMGT`| | | | | 
| `CAREMGT`| _Equivalent_ <br/>(379/1749)| **`CAREMGT`**| _Equivalent_ <br/>(3444/5679)| `CAREMGT`| | | | | 
| `CLINTRL`| _Equivalent_ <br/>(381/1751)| **`CLINTRL`**| _Equivalent_ <br/>(3440/5690)| `CLINTRL`| | | | | 
| `CLINTRL`| _Equivalent_ <br/>(381/1751)| **`CLINTRL`**| _Equivalent_ <br/>(3440/5690)| `CLINTRL`| | | | | 
| `ETREAT`| _Equivalent_ <br/>(390/1760)| **`ETREAT`**| _Equivalent_ <br/>(3454/5718)| `ETREAT`| | | | | 
| `ETREAT`| _Equivalent_ <br/>(390/1760)| **`ETREAT`**| _Equivalent_ <br/>(3454/5718)| `ETREAT`| | | | | 
| `POPHLTH`| _Equivalent_ <br/>(412/1782)| **`POPHLTH`**| _Equivalent_ <br/>(3429/5680)| `POPHLTH`| | | | | 
| `POPHLTH`| _Equivalent_ <br/>(412/1782)| **`POPHLTH`**| _Equivalent_ <br/>(3429/5680)| `POPHLTH`| | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/ActUSPrivacyLaw`
| | | **`_ActUSPrivacyLaw`**| | | | | | | 
| `42CFRPart2`| _Equivalent_ <br/>(283/1656)| **`42CFRPart2`**| _Equivalent_ <br/>(3385/5665)| `42CFRPart2`| | | | | 
| `42CFRPart2`| _Equivalent_ <br/>(283/1656)| **`42CFRPart2`**| _Equivalent_ <br/>(3385/5665)| `42CFRPart2`| | | | | 
| `CommonRule`| _Equivalent_ <br/>(284/1657)| **`CommonRule`**| _Equivalent_ <br/>(3383/5667)| `CommonRule`| | | | | 
| `CommonRule`| _Equivalent_ <br/>(284/1657)| **`CommonRule`**| _Equivalent_ <br/>(3383/5667)| `CommonRule`| | | | | 
| `HIPAANOPP`| _Equivalent_ <br/>(285/1658)| **`HIPAANOPP`**| _Equivalent_ <br/>(3382/5666)| `HIPAANOPP`| | | | | 
| `HIPAANOPP`| _Equivalent_ <br/>(285/1658)| **`HIPAANOPP`**| _Equivalent_ <br/>(3382/5666)| `HIPAANOPP`| | | | | 
| `HIPAAPsyNotes`| _Equivalent_ <br/>(286/1659)| **`HIPAAPsyNotes`**| _Equivalent_ <br/>(3386/5669)| `HIPAAPsyNotes`| | | | | 
| `HIPAAPsyNotes`| _Equivalent_ <br/>(286/1659)| **`HIPAAPsyNotes`**| _Equivalent_ <br/>(3386/5669)| `HIPAAPsyNotes`| | | | | 
| `HIPAASelfPay`| _Equivalent_ <br/>(287/1660)| **`HIPAASelfPay`**| _Equivalent_ <br/>(3384/5664)| `HIPAASelfPay`| | | | | 
| `HIPAASelfPay`| _Equivalent_ <br/>(287/1660)| **`HIPAASelfPay`**| _Equivalent_ <br/>(3384/5664)| `HIPAASelfPay`| | | | | 
| `Title38Section7332`| _Equivalent_ <br/>(288/1661)| **`Title38Section7332`**| _Equivalent_ <br/>(3387/5668)| `Title38Section7332`| | | | | 
| `Title38Section7332`| _Equivalent_ <br/>(288/1661)| **`Title38Section7332`**| _Equivalent_ <br/>(3387/5668)| `Title38Section7332`| | | | | 
| *162 of 237 codes used* <br/>remaining codes:<br/>`_ActInformationSensitivityPolicy`, `_EntitySensitivityPolicyType`, `_InformationSensitivityPolicy`, `_RoleInformationSensitivityPolicy`, `_ActUSPrivacyLaw`, `B`, `C`, `D`, `ETH`, `HIV`, `I`, `PSY`, `S`, `SDV`, `T`, `_Confidentiality`, `_ConfidentialityByAccessKind`, `_ConfidentialityByInfoType`, `_ConfidentialityModifiers`, `_SECALTINTOBV`, `_SECDATINTOBV`, `_SECINTCONOBV`, `_SECINTPRVABOBV`, `_SECINTPRVOBV`, `_SECINTPRVRBOBV`| | *170 of 170 codes used* | | *169 of 273 codes used* <br/>remaining codes:<br/>`ACCESSCONSCHEME`, `ACOCOMPT`, `AUTHPOL`, `BH`, `COGN`, `CTCOMPT`, `DELEPOL`, `DVD`, `EMOTDIS`, `ETHUD`, `FMCOMPT`, `LRCOMPT`, `MH`, `MST`, `OPIOIDUD`, `PACOMPT`, `PHY`, `PSYTHPN`, `SPI`, `SUD`, `VIO`, `_ActInformationSensitivityPolicy`, `_EntitySensitivityPolicyType`, `_InformationSensitivityPolicy`, `_RoleInformationSensitivityPolicy`, `BIORCH`, `BTG`, `CLINTRCHNPC`, `CLINTRCHPC`, `COC`, `DSRCH`, `ERTREAT`, `HDM`, `HTEST`, `LABELING`, `METAMGT`, `MILCDM`, `MILDCRG`, `POARCH`, `PRECLINTRCH`, `SYSDEV`, `TRANSRCH`, `_ActUSPrivacyLaw`, `_SECALTINTOBV`, `_SECDATINTOBV`, `_SECINTCONOBV`, `_SECINTPRVABOBV`, `_SECINTPRVOBV`, `_SECINTPRVRBOBV`| | | | 

