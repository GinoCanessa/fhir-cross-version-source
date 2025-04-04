Comparison of 
Generated at Friday, April 4, 2025 2:58:45 PM

### All Security Labels

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | All Security Labels |
| Canonical URL | `http://hl7.org/fhir/ValueSet/security-labels` |
| Version | 4.0.1 |
| Description | A single value set for all security labels defined by FHIR. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `2740` |
| Database Concept Count | `273` |
| Database Active Concept Count | `263` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Meta` | `Meta.security` | `http://hl7.org/fhir/ValueSet/security-labels` | `Extensible` | Security Labels applied to this resource |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.entity.securityLabel` | `http://hl7.org/fhir/ValueSet/security-labels` | `Extensible` | Security labels on the entity |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.provision.securityLabel` | `http://hl7.org/fhir/ValueSet/security-labels` | `Extensible` | Security Labels that define affected resources |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.securityLabel` | `http://hl7.org/fhir/ValueSet/security-labels` | `Extensible` | Document security-tags |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-Confidentiality`
* `http://terminology.hl7.org/CodeSystem/v3-ActCode`
* `http://terminology.hl7.org/CodeSystem/v3-ObservationValue`
* `http://terminology.hl7.org/CodeSystem/v3-ActReason`
* `http://terminology.hl7.org/CodeSystem/v3-ActUSPrivacyLaw`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [All Security Labels](/docs/R2/ValueSets/AllSecurityLabels.md)<br/> `http://hl7.org/fhir/ValueSet/security-labels\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `53`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `212`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [All Security Labels](/docs/R3/ValueSets/AllSecurityLabels.md)<br/> `http://hl7.org/fhir/ValueSet/security-labels\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `389`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `612`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [All Security Labels](/docs/R4/ValueSets/AllSecurityLabels.md)<br/> `http://hl7.org/fhir/ValueSet/security-labels\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set All Security Labels from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 All Security Labels](/docs/R2/ValueSets/AllSecurityLabels.md)| Relationship | [R3 All Security Labels](/docs/R3/ValueSets/AllSecurityLabels.md)| Relationship | R4 All Security Labels| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v3-Confidentiality`
| `U`| _Equivalent_ <br/>(298/1747)| `U`| →→→→ _Equivalent_ →→→→ <br/>(3425)<hr/>←←←← __ ←←←← <br/>() | **`U`**| | | | | 
| `U`| _Equivalent_ <br/>(298/1747)| `U`| →→→→ _Equivalent_ →→→→ <br/>(3425)<hr/>←←←← __ ←←←← <br/>() | **`U`**| | | | | 
| `L`| _Equivalent_ <br/>(292/1743)| `L`| →→→→ _Equivalent_ →→→→ <br/>(3422)<hr/>←←←← __ ←←←← <br/>() | **`L`**| | | | | 
| `L`| _Equivalent_ <br/>(292/1743)| `L`| →→→→ _Equivalent_ →→→→ <br/>(3422)<hr/>←←←← __ ←←←← <br/>() | **`L`**| | | | | 
| `M`| _Equivalent_ <br/>(293/1744)| `M`| →→→→ _Equivalent_ →→→→ <br/>(3426)<hr/>←←←← __ ←←←← <br/>() | **`M`**| | | | | 
| `M`| _Equivalent_ <br/>(293/1744)| `M`| →→→→ _Equivalent_ →→→→ <br/>(3426)<hr/>←←←← __ ←←←← <br/>() | **`M`**| | | | | 
| `N`| _Equivalent_ <br/>(294/1745)| `N`| →→→→ _Equivalent_ →→→→ <br/>(3424)<hr/>←←←← __ ←←←← <br/>() | **`N`**| | | | | 
| `N`| _Equivalent_ <br/>(294/1745)| `N`| →→→→ _Equivalent_ →→→→ <br/>(3424)<hr/>←←←← __ ←←←← <br/>() | **`N`**| | | | | 
| `R`| _Equivalent_ <br/>(295/1746)| `R`| →→→→ _Equivalent_ →→→→ <br/>(3421)<hr/>←←←← __ ←←←← <br/>() | **`R`**| | | | | 
| `R`| _Equivalent_ <br/>(295/1746)| `R`| →→→→ _Equivalent_ →→→→ <br/>(3421)<hr/>←←←← __ ←←←← <br/>() | **`R`**| | | | | 
| `V`| _Equivalent_ <br/>(299/1748)| `V`| →→→→ _Equivalent_ →→→→ <br/>(3423)<hr/>←←←← __ ←←←← <br/>() | **`V`**| | | | | 
| `V`| _Equivalent_ <br/>(299/1748)| `V`| →→→→ _Equivalent_ →→→→ <br/>(3423)<hr/>←←←← __ ←←←← <br/>() | **`V`**| | | | | 
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v3-ActCode`
| `ETH`| _Equivalent_ <br/>(331/1691)| `ETH`| →→→→ _Equivalent_ →→→→ <br/>(3505)<hr/>←←←← __ ←←←← <br/>() | **`ETH`**| | | | | 
| `ETH`| _Equivalent_ <br/>(331/1691)| `ETH`| →→→→ _Equivalent_ →→→→ <br/>(3505)<hr/>←←←← __ ←←←← <br/>() | **`ETH`**| | | | | 
| `GDIS`| _Equivalent_ <br/>(332/1692)| `GDIS`| →→→→ _Equivalent_ →→→→ <br/>(3492)<hr/>←←←← __ ←←←← <br/>() | **`GDIS`**| | | | | 
| `GDIS`| _Equivalent_ <br/>(332/1692)| `GDIS`| →→→→ _Equivalent_ →→→→ <br/>(3492)<hr/>←←←← __ ←←←← <br/>() | **`GDIS`**| | | | | 
| `HIV`| _Equivalent_ <br/>(334/1694)| `HIV`| →→→→ _Equivalent_ →→→→ <br/>(3500)<hr/>←←←← __ ←←←← <br/>() | **`HIV`**| | | | | 
| `HIV`| _Equivalent_ <br/>(334/1694)| `HIV`| →→→→ _Equivalent_ →→→→ <br/>(3500)<hr/>←←←← __ ←←←← <br/>() | **`HIV`**| | | | | 
| | | `active`| | **`MST`**| | | | | 
| | | `active`| | **`MST`**| | | | | 
| `SCA`| _Equivalent_ <br/>(371/1733)| `SCA`| →→→→ _Equivalent_ →→→→ <br/>(3480)<hr/>←←←← __ ←←←← <br/>() | **`SCA`**| | | | | 
| `SCA`| _Equivalent_ <br/>(371/1733)| `SCA`| →→→→ _Equivalent_ →→→→ <br/>(3480)<hr/>←←←← __ ←←←← <br/>() | **`SCA`**| | | | | 
| `SDV`| _Equivalent_ <br/>(372/1734)| `SDV`| →→→→ _Equivalent_ →→→→ <br/>(3503)<hr/>←←←← __ ←←←← <br/>() | **`SDV`**| | | | | 
| `SDV`| _Equivalent_ <br/>(372/1734)| `SDV`| →→→→ _Equivalent_ →→→→ <br/>(3503)<hr/>←←←← __ ←←←← <br/>() | **`SDV`**| | | | | 
| `SEX`| _Equivalent_ <br/>(373/1735)| `SEX`| →→→→ _Equivalent_ →→→→ <br/>(3490)<hr/>←←←← __ ←←←← <br/>() | **`SEX`**| | | | | 
| `SEX`| _Equivalent_ <br/>(373/1735)| `SEX`| →→→→ _Equivalent_ →→→→ <br/>(3490)<hr/>←←←← __ ←←←← <br/>() | **`SEX`**| | | | | 
| | | `active`| | **`COGN`**| | | | | 
| | | `active`| | **`COGN`**| | | | | 
| | | `active`| | **`DVD`**| | | | | 
| | | `active`| | **`DVD`**| | | | | 
| | | `active`| | **`EMOTDIS`**| | | | | 
| | | `active`| | **`EMOTDIS`**| | | | | 
| | | `active`| | **`BH`**| | | | | 
| | | `active`| | **`BH`**| | | | | 
| | | `active`| | **`MH`**| | | | | 
| | | `active`| | **`MH`**| | | | | 
| `PSY`| _Equivalent_ <br/>(364/1726)| `PSY`| →→→→ _Equivalent_ →→→→ <br/>(3515)<hr/>←←←← __ ←←←← <br/>() | **`PSY`**| | | | | 
| `PSY`| _Equivalent_ <br/>(364/1726)| `PSY`| →→→→ _Equivalent_ →→→→ <br/>(3515)<hr/>←←←← __ ←←←← <br/>() | **`PSY`**| | | | | 
| | | `active`| | **`PSYTHPN`**| | | | | 
| | | `active`| | **`PSYTHPN`**| | | | | 
| | | `active`| | **`ETHUD`**| | | | | 
| | | `active`| | **`ETHUD`**| | | | | 
| | | `active`| | **`OPIOIDUD`**| | | | | 
| | | `active`| | **`OPIOIDUD`**| | | | | 
| | | `active`| | **`SUD`**| | | | | 
| | | `active`| | **`SUD`**| | | | | 
| | | `active`| | **`SPI`**| | | | | 
| | | `active`| | **`SPI`**| | | | | 
| `STD`| _Equivalent_ <br/>(376/1739)| `STD`| →→→→ _Equivalent_ →→→→ <br/>(3499)<hr/>←←←← __ ←←←← <br/>() | **`STD`**| | | | | 
| `STD`| _Equivalent_ <br/>(376/1739)| `STD`| →→→→ _Equivalent_ →→→→ <br/>(3499)<hr/>←←←← __ ←←←← <br/>() | **`STD`**| | | | | 
| `TBOO`| _Equivalent_ <br/>(378/1741)| `TBOO`| →→→→ _Equivalent_ →→→→ <br/>(3477)<hr/>←←←← __ ←←←← <br/>() | **`TBOO`**| | | | | 
| `TBOO`| _Equivalent_ <br/>(378/1741)| `TBOO`| →→→→ _Equivalent_ →→→→ <br/>(3477)<hr/>←←←← __ ←←←← <br/>() | **`TBOO`**| | | | | 
| | | `active`| | **`VIO`**| | | | | 
| | | `active`| | **`VIO`**| | | | | 
| `SICKLE`| _Equivalent_ <br/>(374/1736)| `SICKLE`| →→→→ _Equivalent_ →→→→ <br/>(3475)<hr/>←←←← __ ←←←← <br/>() | **`SICKLE`**| | | | | 
| `SICKLE`| _Equivalent_ <br/>(374/1736)| `SICKLE`| →→→→ _Equivalent_ →→→→ <br/>(3475)<hr/>←←←← __ ←←←← <br/>() | **`SICKLE`**| | | | | 
| `DEMO`| _Equivalent_ <br/>(321/1679)| `DEMO`| →→→→ _Equivalent_ →→→→ <br/>(3537)<hr/>←←←← __ ←←←← <br/>() | **`DEMO`**| | | | | 
| `DEMO`| _Equivalent_ <br/>(321/1679)| `DEMO`| →→→→ _Equivalent_ →→→→ <br/>(3537)<hr/>←←←← __ ←←←← <br/>() | **`DEMO`**| | | | | 
| `DOB`| _Equivalent_ <br/>(323/1681)| `DOB`| →→→→ _Equivalent_ →→→→ <br/>(3542)<hr/>←←←← __ ←←←← <br/>() | **`DOB`**| | | | | 
| `DOB`| _Equivalent_ <br/>(323/1681)| `DOB`| →→→→ _Equivalent_ →→→→ <br/>(3542)<hr/>←←←← __ ←←←← <br/>() | **`DOB`**| | | | | 
| `GENDER`| _Equivalent_ <br/>(333/1693)| `GENDER`| →→→→ _Equivalent_ →→→→ <br/>(3510)<hr/>←←←← __ ←←←← <br/>() | **`GENDER`**| | | | | 
| `GENDER`| _Equivalent_ <br/>(333/1693)| `GENDER`| →→→→ _Equivalent_ →→→→ <br/>(3510)<hr/>←←←← __ ←←←← <br/>() | **`GENDER`**| | | | | 
| `LIVARG`| _Equivalent_ <br/>(337/1698)| `LIVARG`| →→→→ _Equivalent_ →→→→ <br/>(3508)<hr/>←←←← __ ←←←← <br/>() | **`LIVARG`**| | | | | 
| `LIVARG`| _Equivalent_ <br/>(337/1698)| `LIVARG`| →→→→ _Equivalent_ →→→→ <br/>(3508)<hr/>←←←← __ ←←←← <br/>() | **`LIVARG`**| | | | | 
| `MARST`| _Equivalent_ <br/>(339/1700)| `MARST`| →→→→ _Equivalent_ →→→→ <br/>(3530)<hr/>←←←← __ ←←←← <br/>() | **`MARST`**| | | | | 
| `MARST`| _Equivalent_ <br/>(339/1700)| `MARST`| →→→→ _Equivalent_ →→→→ <br/>(3530)<hr/>←←←← __ ←←←← <br/>() | **`MARST`**| | | | | 
| `RACE`| _Equivalent_ <br/>(365/1727)| `RACE`| →→→→ _Equivalent_ →→→→ <br/>(3523)<hr/>←←←← __ ←←←← <br/>() | **`RACE`**| | | | | 
| `RACE`| _Equivalent_ <br/>(365/1727)| `RACE`| →→→→ _Equivalent_ →→→→ <br/>(3523)<hr/>←←←← __ ←←←← <br/>() | **`RACE`**| | | | | 
| `REL`| _Equivalent_ <br/>(367/1729)| `REL`| →→→→ _Equivalent_ →→→→ <br/>(3545)<hr/>←←←← __ ←←←← <br/>() | **`REL`**| | | | | 
| `REL`| _Equivalent_ <br/>(367/1729)| `REL`| →→→→ _Equivalent_ →→→→ <br/>(3545)<hr/>←←←← __ ←←←← <br/>() | **`REL`**| | | | | 
| `B`| _Equivalent_ <br/>(310/1667)| `B`| →→→→ _Equivalent_ →→→→ <br/>(3534)<hr/>←←←← __ ←←←← <br/>() | **`B`**| | | | | 
| `B`| _Equivalent_ <br/>(310/1667)| `B`| →→→→ _Equivalent_ →→→→ <br/>(3534)<hr/>←←←← __ ←←←← <br/>() | **`B`**| | | | | 
| `EMPL`| _Equivalent_ <br/>(326/1686)| `EMPL`| →→→→ _Equivalent_ →→→→ <br/>(3509)<hr/>←←←← __ ←←←← <br/>() | **`EMPL`**| | | | | 
| `EMPL`| _Equivalent_ <br/>(326/1686)| `EMPL`| →→→→ _Equivalent_ →→→→ <br/>(3509)<hr/>←←←← __ ←←←← <br/>() | **`EMPL`**| | | | | 
| `LOCIS`| _Equivalent_ <br/>(338/1699)| `LOCIS`| →→→→ _Equivalent_ →→→→ <br/>(3483)<hr/>←←←← __ ←←←← <br/>() | **`LOCIS`**| | | | | 
| `LOCIS`| _Equivalent_ <br/>(338/1699)| `LOCIS`| →→→→ _Equivalent_ →→→→ <br/>(3483)<hr/>←←←← __ ←←←← <br/>() | **`LOCIS`**| | | | | 
| `SSP`| _Equivalent_ <br/>(375/1738)| `SSP`| →→→→ _Equivalent_ →→→→ <br/>(3513)<hr/>←←←← __ ←←←← <br/>() | **`SSP`**| | | | | 
| `SSP`| _Equivalent_ <br/>(375/1738)| `SSP`| →→→→ _Equivalent_ →→→→ <br/>(3513)<hr/>←←←← __ ←←←← <br/>() | **`SSP`**| | | | | 
| `ADOL`| _Equivalent_ <br/>(305/1662)| `ADOL`| →→→→ _Equivalent_ →→→→ <br/>(3504)<hr/>←←←← __ ←←←← <br/>() | **`ADOL`**| | | | | 
| `ADOL`| _Equivalent_ <br/>(305/1662)| `ADOL`| →→→→ _Equivalent_ →→→→ <br/>(3504)<hr/>←←←← __ ←←←← <br/>() | **`ADOL`**| | | | | 
| `CEL`| _Equivalent_ <br/>(311/1668)| `CEL`| →→→→ _Equivalent_ →→→→ <br/>(3518)<hr/>←←←← __ ←←←← <br/>() | **`CEL`**| | | | | 
| `CEL`| _Equivalent_ <br/>(311/1668)| `CEL`| →→→→ _Equivalent_ →→→→ <br/>(3518)<hr/>←←←← __ ←←←← <br/>() | **`CEL`**| | | | | 
| `DIA`| _Equivalent_ <br/>(322/1680)| `DIA`| →→→→ _Equivalent_ →→→→ <br/>(3495)<hr/>←←←← __ ←←←← <br/>() | **`DIA`**| | | | | 
| `DIA`| _Equivalent_ <br/>(322/1680)| `DIA`| →→→→ _Equivalent_ →→→→ <br/>(3495)<hr/>←←←← __ ←←←← <br/>() | **`DIA`**| | | | | 
| `DRGIS`| _Equivalent_ <br/>(324/1683)| `DRGIS`| →→→→ _Equivalent_ →→→→ <br/>(3493)<hr/>←←←← __ ←←←← <br/>() | **`DRGIS`**| | | | | 
| `DRGIS`| _Equivalent_ <br/>(324/1683)| `DRGIS`| →→→→ _Equivalent_ →→→→ <br/>(3493)<hr/>←←←← __ ←←←← <br/>() | **`DRGIS`**| | | | | 
| `EMP`| _Equivalent_ <br/>(325/1685)| `EMP`| →→→→ _Equivalent_ →→→→ <br/>(3516)<hr/>←←←← __ ←←←← <br/>() | **`EMP`**| | | | | 
| `EMP`| _Equivalent_ <br/>(325/1685)| `EMP`| →→→→ _Equivalent_ →→→→ <br/>(3516)<hr/>←←←← __ ←←←← <br/>() | **`EMP`**| | | | | 
| `PDS`| _Equivalent_ <br/>(360/1721)| `PDS`| →→→→ _Equivalent_ →→→→ <br/>(3549)<hr/>←←←← __ ←←←← <br/>() | **`PDS`**| | | | | 
| `PDS`| _Equivalent_ <br/>(360/1721)| `PDS`| →→→→ _Equivalent_ →→→→ <br/>(3549)<hr/>←←←← __ ←←←← <br/>() | **`PDS`**| | | | | 
| | | `active`| | **`PHY`**| | | | | 
| | | `active`| | **`PHY`**| | | | | 
| `PRS`| _Equivalent_ <br/>(362/1724)| `PRS`| →→→→ _Equivalent_ →→→→ <br/>(3543)<hr/>←←←← __ ←←←← <br/>() | **`PRS`**| | | | | 
| `PRS`| _Equivalent_ <br/>(362/1724)| `PRS`| →→→→ _Equivalent_ →→→→ <br/>(3543)<hr/>←←←← __ ←←←← <br/>() | **`PRS`**| | | | | 
| | | `active`| | **`ACOCOMPT`**| | | | | 
| | | `active`| | **`ACOCOMPT`**| | | | | 
| | | `active`| | **`CTCOMPT`**| | | | | 
| | | `active`| | **`CTCOMPT`**| | | | | 
| | | `active`| | **`FMCOMPT`**| | | | | 
| | | `active`| | **`FMCOMPT`**| | | | | 
| `HRCOMPT`| _Equivalent_ <br/>(335/1695)| `HRCOMPT`| →→→→ _Equivalent_ →→→→ <br/>(3485)<hr/>←←←← __ ←←←← <br/>() | **`HRCOMPT`**| | | | | 
| `HRCOMPT`| _Equivalent_ <br/>(335/1695)| `HRCOMPT`| →→→→ _Equivalent_ →→→→ <br/>(3485)<hr/>←←←← __ ←←←← <br/>() | **`HRCOMPT`**| | | | | 
| | | `active`| | **`LRCOMPT`**| | | | | 
| | | `active`| | **`LRCOMPT`**| | | | | 
| | | `active`| | **`PACOMPT`**| | | | | 
| | | `active`| | **`PACOMPT`**| | | | | 
| `RESCOMPT`| _Equivalent_ <br/>(368/1730)| `RESCOMPT`| →→→→ _Equivalent_ →→→→ <br/>(3497)<hr/>←←←← __ ←←←← <br/>() | **`RESCOMPT`**| | | | | 
| `RESCOMPT`| _Equivalent_ <br/>(368/1730)| `RESCOMPT`| →→→→ _Equivalent_ →→→→ <br/>(3497)<hr/>←←←← __ ←←←← <br/>() | **`RESCOMPT`**| | | | | 
| `RMGTCOMPT`| _Equivalent_ <br/>(369/1731)| `RMGTCOMPT`| →→→→ _Equivalent_ →→→→ <br/>(3527)<hr/>←←←← __ ←←←← <br/>() | **`RMGTCOMPT`**| | | | | 
| `RMGTCOMPT`| _Equivalent_ <br/>(369/1731)| `RMGTCOMPT`| →→→→ _Equivalent_ →→→→ <br/>(3527)<hr/>←←←← __ ←←←← <br/>() | **`RMGTCOMPT`**| | | | | 
| `COMPT`| _Equivalent_ <br/>(312/1669)| `COMPT`| →→→→ _Equivalent_ →→→→ <br/>(3502)<hr/>←←←← __ ←←←← <br/>() | **`COMPT`**| | | | | 
| `COMPT`| _Equivalent_ <br/>(312/1669)| `COMPT`| →→→→ _Equivalent_ →→→→ <br/>(3502)<hr/>←←←← __ ←←←← <br/>() | **`COMPT`**| | | | | 
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v3-ObservationValue`
| `ABSTRED`| _Equivalent_ <br/>(250/1623)| `ABSTRED`| →→→→ _Equivalent_ →→→→ <br/>(3409)<hr/>←←←← __ ←←←← <br/>() | **`ABSTRED`**| | | | | 
| `ABSTRED`| _Equivalent_ <br/>(250/1623)| `ABSTRED`| →→→→ _Equivalent_ →→→→ <br/>(3409)<hr/>←←←← __ ←←←← <br/>() | **`ABSTRED`**| | | | | 
| `AGGRED`| _Equivalent_ <br/>(251/1624)| `AGGRED`| →→→→ _Equivalent_ →→→→ <br/>(3404)<hr/>←←←← __ ←←←← <br/>() | **`AGGRED`**| | | | | 
| `AGGRED`| _Equivalent_ <br/>(251/1624)| `AGGRED`| →→→→ _Equivalent_ →→→→ <br/>(3404)<hr/>←←←← __ ←←←← <br/>() | **`AGGRED`**| | | | | 
| `ANONYED`| _Equivalent_ <br/>(252/1625)| `ANONYED`| →→→→ _Equivalent_ →→→→ <br/>(3417)<hr/>←←←← __ ←←←← <br/>() | **`ANONYED`**| | | | | 
| `ANONYED`| _Equivalent_ <br/>(252/1625)| `ANONYED`| →→→→ _Equivalent_ →→→→ <br/>(3417)<hr/>←←←← __ ←←←← <br/>() | **`ANONYED`**| | | | | 
| `MAPPED`| _Equivalent_ <br/>(262/1635)| `MAPPED`| →→→→ _Equivalent_ →→→→ <br/>(3413)<hr/>←←←← __ ←←←← <br/>() | **`MAPPED`**| | | | | 
| `MAPPED`| _Equivalent_ <br/>(262/1635)| `MAPPED`| →→→→ _Equivalent_ →→→→ <br/>(3413)<hr/>←←←← __ ←←←← <br/>() | **`MAPPED`**| | | | | 
| `MASKED`| _Equivalent_ <br/>(263/1636)| `MASKED`| →→→→ _Equivalent_ →→→→ <br/>(3415)<hr/>←←←← __ ←←←← <br/>() | **`MASKED`**| | | | | 
| `MASKED`| _Equivalent_ <br/>(263/1636)| `MASKED`| →→→→ _Equivalent_ →→→→ <br/>(3415)<hr/>←←←← __ ←←←← <br/>() | **`MASKED`**| | | | | 
| `PSEUDED`| _Equivalent_ <br/>(272/1645)| `PSEUDED`| →→→→ _Equivalent_ →→→→ <br/>(3388)<hr/>←←←← __ ←←←← <br/>() | **`PSEUDED`**| | | | | 
| `PSEUDED`| _Equivalent_ <br/>(272/1645)| `PSEUDED`| →→→→ _Equivalent_ →→→→ <br/>(3388)<hr/>←←←← __ ←←←← <br/>() | **`PSEUDED`**| | | | | 
| `REDACTED`| _Equivalent_ <br/>(273/1646)| `REDACTED`| →→→→ _Equivalent_ →→→→ <br/>(3397)<hr/>←←←← __ ←←←← <br/>() | **`REDACTED`**| | | | | 
| `REDACTED`| _Equivalent_ <br/>(273/1646)| `REDACTED`| →→→→ _Equivalent_ →→→→ <br/>(3397)<hr/>←←←← __ ←←←← <br/>() | **`REDACTED`**| | | | | 
| `SUBSETTED`| _Equivalent_ <br/>(277/1650)| `SUBSETTED`| →→→→ _Equivalent_ →→→→ <br/>(3399)<hr/>←←←← __ ←←←← <br/>() | **`SUBSETTED`**| | | | | 
| `SUBSETTED`| _Equivalent_ <br/>(277/1650)| `SUBSETTED`| →→→→ _Equivalent_ →→→→ <br/>(3399)<hr/>←←←← __ ←←←← <br/>() | **`SUBSETTED`**| | | | | 
| `SYNTAC`| _Equivalent_ <br/>(278/1651)| `SYNTAC`| →→→→ _Equivalent_ →→→→ <br/>(3390)<hr/>←←←← __ ←←←← <br/>() | **`SYNTAC`**| | | | | 
| `SYNTAC`| _Equivalent_ <br/>(278/1651)| `SYNTAC`| →→→→ _Equivalent_ →→→→ <br/>(3390)<hr/>←←←← __ ←←←← <br/>() | **`SYNTAC`**| | | | | 
| `TRSLT`| _Equivalent_ <br/>(279/1652)| `TRSLT`| →→→→ _Equivalent_ →→→→ <br/>(3401)<hr/>←←←← __ ←←←← <br/>() | **`TRSLT`**| | | | | 
| `TRSLT`| _Equivalent_ <br/>(279/1652)| `TRSLT`| →→→→ _Equivalent_ →→→→ <br/>(3401)<hr/>←←←← __ ←←←← <br/>() | **`TRSLT`**| | | | | 
| `VERSIONED`| _Equivalent_ <br/>(282/1655)| `VERSIONED`| →→→→ _Equivalent_ →→→→ <br/>(3403)<hr/>←←←← __ ←←←← <br/>() | **`VERSIONED`**| | | | | 
| `VERSIONED`| _Equivalent_ <br/>(282/1655)| `VERSIONED`| →→→→ _Equivalent_ →→→→ <br/>(3403)<hr/>←←←← __ ←←←← <br/>() | **`VERSIONED`**| | | | | 
| `CRYTOHASH`| _Equivalent_ <br/>(255/1628)| `CRYTOHASH`| →→→→ _Equivalent_ →→→→ <br/>(3418)<hr/>←←←← __ ←←←← <br/>() | **`CRYTOHASH`**| | | | | 
| `CRYTOHASH`| _Equivalent_ <br/>(255/1628)| `CRYTOHASH`| →→→→ _Equivalent_ →→→→ <br/>(3418)<hr/>←←←← __ ←←←← <br/>() | **`CRYTOHASH`**| | | | | 
| `DIGSIG`| _Equivalent_ <br/>(258/1631)| `DIGSIG`| →→→→ _Equivalent_ →→→→ <br/>(3394)<hr/>←←←← __ ←←←← <br/>() | **`DIGSIG`**| | | | | 
| `DIGSIG`| _Equivalent_ <br/>(258/1631)| `DIGSIG`| →→→→ _Equivalent_ →→→→ <br/>(3394)<hr/>←←←← __ ←←←← <br/>() | **`DIGSIG`**| | | | | 
| `HRELIABLE`| _Equivalent_ <br/>(261/1634)| `HRELIABLE`| →→→→ _Equivalent_ →→→→ <br/>(3396)<hr/>←←←← __ ←←←← <br/>() | **`HRELIABLE`**| | | | | 
| `HRELIABLE`| _Equivalent_ <br/>(261/1634)| `HRELIABLE`| →→→→ _Equivalent_ →→→→ <br/>(3396)<hr/>←←←← __ ←←←← <br/>() | **`HRELIABLE`**| | | | | 
| `RELIABLE`| _Equivalent_ <br/>(274/1647)| `RELIABLE`| →→→→ _Equivalent_ →→→→ <br/>(3419)<hr/>←←←← __ ←←←← <br/>() | **`RELIABLE`**| | | | | 
| `RELIABLE`| _Equivalent_ <br/>(274/1647)| `RELIABLE`| →→→→ _Equivalent_ →→→→ <br/>(3419)<hr/>←←←← __ ←←←← <br/>() | **`RELIABLE`**| | | | | 
| `UNCERTREL`| _Equivalent_ <br/>(280/1653)| `UNCERTREL`| →→→→ _Equivalent_ →→→→ <br/>(3389)<hr/>←←←← __ ←←←← <br/>() | **`UNCERTREL`**| | | | | 
| `UNCERTREL`| _Equivalent_ <br/>(280/1653)| `UNCERTREL`| →→→→ _Equivalent_ →→→→ <br/>(3389)<hr/>←←←← __ ←←←← <br/>() | **`UNCERTREL`**| | | | | 
| `UNRELIABLE`| _Equivalent_ <br/>(281/1654)| `UNRELIABLE`| →→→→ _Equivalent_ →→→→ <br/>(3395)<hr/>←←←← __ ←←←← <br/>() | **`UNRELIABLE`**| | | | | 
| `UNRELIABLE`| _Equivalent_ <br/>(281/1654)| `UNRELIABLE`| →→→→ _Equivalent_ →→→→ <br/>(3395)<hr/>←←←← __ ←←←← <br/>() | **`UNRELIABLE`**| | | | | 
| `CLINAST`| _Equivalent_ <br/>(253/1626)| `CLINAST`| →→→→ _Equivalent_ →→→→ <br/>(3416)<hr/>←←←← __ ←←←← <br/>() | **`CLINAST`**| | | | | 
| `CLINAST`| _Equivalent_ <br/>(253/1626)| `CLINAST`| →→→→ _Equivalent_ →→→→ <br/>(3416)<hr/>←←←← __ ←←←← <br/>() | **`CLINAST`**| | | | | 
| `DEVAST`| _Equivalent_ <br/>(256/1629)| `DEVAST`| →→→→ _Equivalent_ →→→→ <br/>(3391)<hr/>←←←← __ ←←←← <br/>() | **`DEVAST`**| | | | | 
| `DEVAST`| _Equivalent_ <br/>(256/1629)| `DEVAST`| →→→→ _Equivalent_ →→→→ <br/>(3391)<hr/>←←←← __ ←←←← <br/>() | **`DEVAST`**| | | | | 
| `HCPAST`| _Equivalent_ <br/>(259/1632)| `HCPAST`| →→→→ _Equivalent_ →→→→ <br/>(3414)<hr/>←←←← __ ←←←← <br/>() | **`HCPAST`**| | | | | 
| `HCPAST`| _Equivalent_ <br/>(259/1632)| `HCPAST`| →→→→ _Equivalent_ →→→→ <br/>(3414)<hr/>←←←← __ ←←←← <br/>() | **`HCPAST`**| | | | | 
| `PACQAST`| _Equivalent_ <br/>(264/1637)| `PACQAST`| →→→→ _Equivalent_ →→→→ <br/>(3407)<hr/>←←←← __ ←←←← <br/>() | **`PACQAST`**| | | | | 
| `PACQAST`| _Equivalent_ <br/>(264/1637)| `PACQAST`| →→→→ _Equivalent_ →→→→ <br/>(3407)<hr/>←←←← __ ←←←← <br/>() | **`PACQAST`**| | | | | 
| `PATAST`| _Equivalent_ <br/>(266/1639)| `PATAST`| →→→→ _Equivalent_ →→→→ <br/>(3392)<hr/>←←←← __ ←←←← <br/>() | **`PATAST`**| | | | | 
| `PATAST`| _Equivalent_ <br/>(266/1639)| `PATAST`| →→→→ _Equivalent_ →→→→ <br/>(3392)<hr/>←←←← __ ←←←← <br/>() | **`PATAST`**| | | | | 
| `PAYAST`| _Equivalent_ <br/>(268/1641)| `PAYAST`| →→→→ _Equivalent_ →→→→ <br/>(3411)<hr/>←←←← __ ←←←← <br/>() | **`PAYAST`**| | | | | 
| `PAYAST`| _Equivalent_ <br/>(268/1641)| `PAYAST`| →→→→ _Equivalent_ →→→→ <br/>(3411)<hr/>←←←← __ ←←←← <br/>() | **`PAYAST`**| | | | | 
| `PROAST`| _Equivalent_ <br/>(270/1643)| `PROAST`| →→→→ _Equivalent_ →→→→ <br/>(3410)<hr/>←←←← __ ←←←← <br/>() | **`PROAST`**| | | | | 
| `PROAST`| _Equivalent_ <br/>(270/1643)| `PROAST`| →→→→ _Equivalent_ →→→→ <br/>(3410)<hr/>←←←← __ ←←←← <br/>() | **`PROAST`**| | | | | 
| `SDMAST`| _Equivalent_ <br/>(275/1648)| `SDMAST`| →→→→ _Equivalent_ →→→→ <br/>(3398)<hr/>←←←← __ ←←←← <br/>() | **`SDMAST`**| | | | | 
| `SDMAST`| _Equivalent_ <br/>(275/1648)| `SDMAST`| →→→→ _Equivalent_ →→→→ <br/>(3398)<hr/>←←←← __ ←←←← <br/>() | **`SDMAST`**| | | | | 
| `CLINRPT`| _Equivalent_ <br/>(254/1627)| `CLINRPT`| →→→→ _Equivalent_ →→→→ <br/>(3402)<hr/>←←←← __ ←←←← <br/>() | **`CLINRPT`**| | | | | 
| `CLINRPT`| _Equivalent_ <br/>(254/1627)| `CLINRPT`| →→→→ _Equivalent_ →→→→ <br/>(3402)<hr/>←←←← __ ←←←← <br/>() | **`CLINRPT`**| | | | | 
| `DEVRPT`| _Equivalent_ <br/>(257/1630)| `DEVRPT`| →→→→ _Equivalent_ →→→→ <br/>(3412)<hr/>←←←← __ ←←←← <br/>() | **`DEVRPT`**| | | | | 
| `DEVRPT`| _Equivalent_ <br/>(257/1630)| `DEVRPT`| →→→→ _Equivalent_ →→→→ <br/>(3412)<hr/>←←←← __ ←←←← <br/>() | **`DEVRPT`**| | | | | 
| `HCPRPT`| _Equivalent_ <br/>(260/1633)| `HCPRPT`| →→→→ _Equivalent_ →→→→ <br/>(3405)<hr/>←←←← __ ←←←← <br/>() | **`HCPRPT`**| | | | | 
| `HCPRPT`| _Equivalent_ <br/>(260/1633)| `HCPRPT`| →→→→ _Equivalent_ →→→→ <br/>(3405)<hr/>←←←← __ ←←←← <br/>() | **`HCPRPT`**| | | | | 
| `PACQRPT`| _Equivalent_ <br/>(265/1638)| `PACQRPT`| →→→→ _Equivalent_ →→→→ <br/>(3408)<hr/>←←←← __ ←←←← <br/>() | **`PACQRPT`**| | | | | 
| `PACQRPT`| _Equivalent_ <br/>(265/1638)| `PACQRPT`| →→→→ _Equivalent_ →→→→ <br/>(3408)<hr/>←←←← __ ←←←← <br/>() | **`PACQRPT`**| | | | | 
| `PATRPT`| _Equivalent_ <br/>(267/1640)| `PATRPT`| →→→→ _Equivalent_ →→→→ <br/>(3420)<hr/>←←←← __ ←←←← <br/>() | **`PATRPT`**| | | | | 
| `PATRPT`| _Equivalent_ <br/>(267/1640)| `PATRPT`| →→→→ _Equivalent_ →→→→ <br/>(3420)<hr/>←←←← __ ←←←← <br/>() | **`PATRPT`**| | | | | 
| `PAYRPT`| _Equivalent_ <br/>(269/1642)| `PAYRPT`| →→→→ _Equivalent_ →→→→ <br/>(3406)<hr/>←←←← __ ←←←← <br/>() | **`PAYRPT`**| | | | | 
| `PAYRPT`| _Equivalent_ <br/>(269/1642)| `PAYRPT`| →→→→ _Equivalent_ →→→→ <br/>(3406)<hr/>←←←← __ ←←←← <br/>() | **`PAYRPT`**| | | | | 
| `PRORPT`| _Equivalent_ <br/>(271/1644)| `PRORPT`| →→→→ _Equivalent_ →→→→ <br/>(3400)<hr/>←←←← __ ←←←← <br/>() | **`PRORPT`**| | | | | 
| `PRORPT`| _Equivalent_ <br/>(271/1644)| `PRORPT`| →→→→ _Equivalent_ →→→→ <br/>(3400)<hr/>←←←← __ ←←←← <br/>() | **`PRORPT`**| | | | | 
| `SDMRPT`| _Equivalent_ <br/>(276/1649)| `SDMRPT`| →→→→ _Equivalent_ →→→→ <br/>(3393)<hr/>←←←← __ ←←←← <br/>() | **`SDMRPT`**| | | | | 
| `SDMRPT`| _Equivalent_ <br/>(276/1649)| `SDMRPT`| →→→→ _Equivalent_ →→→→ <br/>(3393)<hr/>←←←← __ ←←←← <br/>() | **`SDMRPT`**| | | | | 
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v3-ActCode`
| | | `active`| | **`ACCESSCONSCHEME`**| | | | | 
| | | `active`| | **`ACCESSCONSCHEME`**| | | | | 
| | | `active`| | **`AUTHPOL`**| | | | | 
| | | `active`| | **`AUTHPOL`**| | | | | 
| | | `active`| | **`DELEPOL`**| | | | | 
| | | `active`| | **`DELEPOL`**| | | | | 
| `ANONY`| _Equivalent_ <br/>(306/1663)| `ANONY`| →→→→ _Equivalent_ →→→→ <br/>(3496)<hr/>←←←← __ ←←←← <br/>() | **`ANONY`**| | | | | 
| `ANONY`| _Equivalent_ <br/>(306/1663)| `ANONY`| →→→→ _Equivalent_ →→→→ <br/>(3496)<hr/>←←←← __ ←←←← <br/>() | **`ANONY`**| | | | | 
| `AOD`| _Equivalent_ <br/>(307/1664)| `AOD`| →→→→ _Equivalent_ →→→→ <br/>(3529)<hr/>←←←← __ ←←←← <br/>() | **`AOD`**| | | | | 
| `AOD`| _Equivalent_ <br/>(307/1664)| `AOD`| →→→→ _Equivalent_ →→→→ <br/>(3529)<hr/>←←←← __ ←←←← <br/>() | **`AOD`**| | | | | 
| `AUDIT`| _Equivalent_ <br/>(308/1665)| `AUDIT`| →→→→ _Equivalent_ →→→→ <br/>(3484)<hr/>←←←← __ ←←←← <br/>() | **`AUDIT`**| | | | | 
| `AUDIT`| _Equivalent_ <br/>(308/1665)| `AUDIT`| →→→→ _Equivalent_ →→→→ <br/>(3484)<hr/>←←←← __ ←←←← <br/>() | **`AUDIT`**| | | | | 
| `AUDTR`| _Equivalent_ <br/>(309/1666)| `AUDTR`| →→→→ _Equivalent_ →→→→ <br/>(3472)<hr/>←←←← __ ←←←← <br/>() | **`AUDTR`**| | | | | 
| `AUDTR`| _Equivalent_ <br/>(309/1666)| `AUDTR`| →→→→ _Equivalent_ →→→→ <br/>(3472)<hr/>←←←← __ ←←←← <br/>() | **`AUDTR`**| | | | | 
| `CPLYCC`| _Equivalent_ <br/>(313/1670)| `CPLYCC`| →→→→ _Equivalent_ →→→→ <br/>(3541)<hr/>←←←← __ ←←←← <br/>() | **`CPLYCC`**| | | | | 
| `CPLYCC`| _Equivalent_ <br/>(313/1670)| `CPLYCC`| →→→→ _Equivalent_ →→→→ <br/>(3541)<hr/>←←←← __ ←←←← <br/>() | **`CPLYCC`**| | | | | 
| `CPLYCD`| _Equivalent_ <br/>(314/1671)| `CPLYCD`| →→→→ _Equivalent_ →→→→ <br/>(3471)<hr/>←←←← __ ←←←← <br/>() | **`CPLYCD`**| | | | | 
| `CPLYCD`| _Equivalent_ <br/>(314/1671)| `CPLYCD`| →→→→ _Equivalent_ →→→→ <br/>(3471)<hr/>←←←← __ ←←←← <br/>() | **`CPLYCD`**| | | | | 
| `CPLYJPP`| _Equivalent_ <br/>(315/1672)| `CPLYJPP`| →→→→ _Equivalent_ →→→→ <br/>(3478)<hr/>←←←← __ ←←←← <br/>() | **`CPLYJPP`**| | | | | 
| `CPLYJPP`| _Equivalent_ <br/>(315/1672)| `CPLYJPP`| →→→→ _Equivalent_ →→→→ <br/>(3478)<hr/>←←←← __ ←←←← <br/>() | **`CPLYJPP`**| | | | | 
| `CPLYOPP`| _Equivalent_ <br/>(316/1673)| `CPLYOPP`| →→→→ _Equivalent_ →→→→ <br/>(3528)<hr/>←←←← __ ←←←← <br/>() | **`CPLYOPP`**| | | | | 
| `CPLYOPP`| _Equivalent_ <br/>(316/1673)| `CPLYOPP`| →→→→ _Equivalent_ →→→→ <br/>(3528)<hr/>←←←← __ ←←←← <br/>() | **`CPLYOPP`**| | | | | 
| `CPLYOSP`| _Equivalent_ <br/>(317/1674)| `CPLYOSP`| →→→→ _Equivalent_ →→→→ <br/>(3525)<hr/>←←←← __ ←←←← <br/>() | **`CPLYOSP`**| | | | | 
| `CPLYOSP`| _Equivalent_ <br/>(317/1674)| `CPLYOSP`| →→→→ _Equivalent_ →→→→ <br/>(3525)<hr/>←←←← __ ←←←← <br/>() | **`CPLYOSP`**| | | | | 
| `CPLYPOL`| _Equivalent_ <br/>(318/1675)| `CPLYPOL`| →→→→ _Equivalent_ →→→→ <br/>(3494)<hr/>←←←← __ ←←←← <br/>() | **`CPLYPOL`**| | | | | 
| `CPLYPOL`| _Equivalent_ <br/>(318/1675)| `CPLYPOL`| →→→→ _Equivalent_ →→→→ <br/>(3494)<hr/>←←←← __ ←←←← <br/>() | **`CPLYPOL`**| | | | | 
| | | `DECLASSIFYLABEL`| →→→→ _Equivalent_ →→→→ <br/>(3548)<hr/>←←←← __ ←←←← <br/>() | **`DECLASSIFYLABEL`**| | | | | 
| | | `DECLASSIFYLABEL`| →→→→ _Equivalent_ →→→→ <br/>(3548)<hr/>←←←← __ ←←←← <br/>() | **`DECLASSIFYLABEL`**| | | | | 
| `DEID`| _Equivalent_ <br/>(319/1677)| `DEID`| →→→→ _Equivalent_ →→→→ <br/>(3517)<hr/>←←←← __ ←←←← <br/>() | **`DEID`**| | | | | 
| `DEID`| _Equivalent_ <br/>(319/1677)| `DEID`| →→→→ _Equivalent_ →→→→ <br/>(3517)<hr/>←←←← __ ←←←← <br/>() | **`DEID`**| | | | | 
| `DELAU`| _Equivalent_ <br/>(320/1678)| `DELAU`| →→→→ _Equivalent_ →→→→ <br/>(3526)<hr/>←←←← __ ←←←← <br/>() | **`DELAU`**| | | | | 
| `DELAU`| _Equivalent_ <br/>(320/1678)| `DELAU`| →→→→ _Equivalent_ →→→→ <br/>(3526)<hr/>←←←← __ ←←←← <br/>() | **`DELAU`**| | | | | 
| | | `DOWNGRDLABEL`| →→→→ _Equivalent_ →→→→ <br/>(3514)<hr/>←←←← __ ←←←← <br/>() | **`DOWNGRDLABEL`**| | | | | 
| | | `DOWNGRDLABEL`| →→→→ _Equivalent_ →→→→ <br/>(3514)<hr/>←←←← __ ←←←← <br/>() | **`DOWNGRDLABEL`**| | | | | 
| | | `DRIVLABEL`| →→→→ _Equivalent_ →→→→ <br/>(3519)<hr/>←←←← __ ←←←← <br/>() | **`DRIVLABEL`**| | | | | 
| | | `DRIVLABEL`| →→→→ _Equivalent_ →→→→ <br/>(3519)<hr/>←←←← __ ←←←← <br/>() | **`DRIVLABEL`**| | | | | 
| `ENCRYPTR`| _Equivalent_ <br/>(328/1688)| `ENCRYPTR`| →→→→ _Equivalent_ →→→→ <br/>(3506)<hr/>←←←← __ ←←←← <br/>() | **`ENCRYPTR`**| | | | | 
| `ENCRYPTR`| _Equivalent_ <br/>(328/1688)| `ENCRYPTR`| →→→→ _Equivalent_ →→→→ <br/>(3506)<hr/>←←←← __ ←←←← <br/>() | **`ENCRYPTR`**| | | | | 
| `ENCRYPTT`| _Equivalent_ <br/>(329/1689)| `ENCRYPTT`| →→→→ _Equivalent_ →→→→ <br/>(3507)<hr/>←←←← __ ←←←← <br/>() | **`ENCRYPTT`**| | | | | 
| `ENCRYPTT`| _Equivalent_ <br/>(329/1689)| `ENCRYPTT`| →→→→ _Equivalent_ →→→→ <br/>(3507)<hr/>←←←← __ ←←←← <br/>() | **`ENCRYPTT`**| | | | | 
| `ENCRYPTU`| _Equivalent_ <br/>(330/1690)| `ENCRYPTU`| →→→→ _Equivalent_ →→→→ <br/>(3486)<hr/>←←←← __ ←←←← <br/>() | **`ENCRYPTU`**| | | | | 
| `ENCRYPTU`| _Equivalent_ <br/>(330/1690)| `ENCRYPTU`| →→→→ _Equivalent_ →→→→ <br/>(3486)<hr/>←←←← __ ←←←← <br/>() | **`ENCRYPTU`**| | | | | 
| `ENCRYPT`| _Equivalent_ <br/>(327/1687)| `ENCRYPT`| →→→→ _Equivalent_ →→→→ <br/>(3524)<hr/>←←←← __ ←←←← <br/>() | **`ENCRYPT`**| | | | | 
| `ENCRYPT`| _Equivalent_ <br/>(327/1687)| `ENCRYPT`| →→→→ _Equivalent_ →→→→ <br/>(3524)<hr/>←←←← __ ←←←← <br/>() | **`ENCRYPT`**| | | | | 
| `HUAPRV`| _Equivalent_ <br/>(336/1696)| `HUAPRV`| →→→→ _Equivalent_ →→→→ <br/>(3479)<hr/>←←←← __ ←←←← <br/>() | **`HUAPRV`**| | | | | 
| `HUAPRV`| _Equivalent_ <br/>(336/1696)| `HUAPRV`| →→→→ _Equivalent_ →→→→ <br/>(3479)<hr/>←←←← __ ←←←← <br/>() | **`HUAPRV`**| | | | | 
| | | `LABEL`| →→→→ _Equivalent_ →→→→ <br/>(3531)<hr/>←←←← __ ←←←← <br/>() | **`LABEL`**| | | | | 
| | | `LABEL`| →→→→ _Equivalent_ →→→→ <br/>(3531)<hr/>←←←← __ ←←←← <br/>() | **`LABEL`**| | | | | 
| `MASK`| _Equivalent_ <br/>(340/1701)| `MASK`| →→→→ _Equivalent_ →→→→ <br/>(3474)<hr/>←←←← __ ←←←← <br/>() | **`MASK`**| | | | | 
| `MASK`| _Equivalent_ <br/>(340/1701)| `MASK`| →→→→ _Equivalent_ →→→→ <br/>(3474)<hr/>←←←← __ ←←←← <br/>() | **`MASK`**| | | | | 
| `MINEC`| _Equivalent_ <br/>(341/1702)| `MINEC`| →→→→ _Equivalent_ →→→→ <br/>(3535)<hr/>←←←← __ ←←←← <br/>() | **`MINEC`**| | | | | 
| `MINEC`| _Equivalent_ <br/>(341/1702)| `MINEC`| →→→→ _Equivalent_ →→→→ <br/>(3535)<hr/>←←←← __ ←←←← <br/>() | **`MINEC`**| | | | | 
| | | `PERSISTLABEL`| →→→→ _Equivalent_ →→→→ <br/>(3512)<hr/>←←←← __ ←←←← <br/>() | **`PERSISTLABEL`**| | | | | 
| | | `PERSISTLABEL`| →→→→ _Equivalent_ →→→→ <br/>(3512)<hr/>←←←← __ ←←←← <br/>() | **`PERSISTLABEL`**| | | | | 
| `PRIVMARK`| _Equivalent_ <br/>(361/1723)| `PRIVMARK`| →→→→ _Equivalent_ →→→→ <br/>(3521)<hr/>←←←← __ ←←←← <br/>() | **`PRIVMARK`**| | | | | 
| `PRIVMARK`| _Equivalent_ <br/>(361/1723)| `PRIVMARK`| →→→→ _Equivalent_ →→→→ <br/>(3521)<hr/>←←←← __ ←←←← <br/>() | **`PRIVMARK`**| | | | | 
| `PSEUD`| _Equivalent_ <br/>(363/1725)| `PSEUD`| →→→→ _Equivalent_ →→→→ <br/>(3520)<hr/>←←←← __ ←←←← <br/>() | **`PSEUD`**| | | | | 
| `PSEUD`| _Equivalent_ <br/>(363/1725)| `PSEUD`| →→→→ _Equivalent_ →→→→ <br/>(3520)<hr/>←←←← __ ←←←← <br/>() | **`PSEUD`**| | | | | 
| `REDACT`| _Equivalent_ <br/>(366/1728)| `REDACT`| →→→→ _Equivalent_ →→→→ <br/>(3501)<hr/>←←←← __ ←←←← <br/>() | **`REDACT`**| | | | | 
| `REDACT`| _Equivalent_ <br/>(366/1728)| `REDACT`| →→→→ _Equivalent_ →→→→ <br/>(3501)<hr/>←←←← __ ←←←← <br/>() | **`REDACT`**| | | | | 
| | | `UPGRDLABEL`| →→→→ _Equivalent_ →→→→ <br/>(3481)<hr/>←←←← __ ←←←← <br/>() | **`UPGRDLABEL`**| | | | | 
| | | `UPGRDLABEL`| →→→→ _Equivalent_ →→→→ <br/>(3481)<hr/>←←←← __ ←←←← <br/>() | **`UPGRDLABEL`**| | | | | 
| `ObligationPolicy`| _Equivalent_ <br/>(359/1720)| `ObligationPolicy`| →→→→ _Equivalent_ →→→→ <br/>(3540)<hr/>←←←← __ ←←←← <br/>() | **`ObligationPolicy`**| | | | | 
| `ObligationPolicy`| _Equivalent_ <br/>(359/1720)| `ObligationPolicy`| →→→→ _Equivalent_ →→→→ <br/>(3540)<hr/>←←←← __ ←←←← <br/>() | **`ObligationPolicy`**| | | | | 
| `NOAUTH`| _Equivalent_ <br/>(342/1703)| `NOAUTH`| →→→→ _Equivalent_ →→→→ <br/>(3470)<hr/>←←←← __ ←←←← <br/>() | **`NOAUTH`**| | | | | 
| `NOAUTH`| _Equivalent_ <br/>(342/1703)| `NOAUTH`| →→→→ _Equivalent_ →→→→ <br/>(3470)<hr/>←←←← __ ←←←← <br/>() | **`NOAUTH`**| | | | | 
| `NOCOLLECT`| _Equivalent_ <br/>(343/1704)| `NOCOLLECT`| →→→→ _Equivalent_ →→→→ <br/>(3533)<hr/>←←←← __ ←←←← <br/>() | **`NOCOLLECT`**| | | | | 
| `NOCOLLECT`| _Equivalent_ <br/>(343/1704)| `NOCOLLECT`| →→→→ _Equivalent_ →→→→ <br/>(3533)<hr/>←←←← __ ←←←← <br/>() | **`NOCOLLECT`**| | | | | 
| `NODSCLCD`| _Equivalent_ <br/>(344/1705)| `NODSCLCD`| →→→→ _Equivalent_ →→→→ <br/>(3511)<hr/>←←←← __ ←←←← <br/>() | **`NODSCLCD`**| | | | | 
| `NODSCLCD`| _Equivalent_ <br/>(344/1705)| `NODSCLCD`| →→→→ _Equivalent_ →→→→ <br/>(3511)<hr/>←←←← __ ←←←← <br/>() | **`NODSCLCD`**| | | | | 
| `NODSCLCDS`| _Equivalent_ <br/>(345/1706)| `NODSCLCDS`| →→→→ _Equivalent_ →→→→ <br/>(3547)<hr/>←←←← __ ←←←← <br/>() | **`NODSCLCDS`**| | | | | 
| `NODSCLCDS`| _Equivalent_ <br/>(345/1706)| `NODSCLCDS`| →→→→ _Equivalent_ →→→→ <br/>(3547)<hr/>←←←← __ ←←←← <br/>() | **`NODSCLCDS`**| | | | | 
| `NOINTEGRATE`| _Equivalent_ <br/>(346/1707)| `NOINTEGRATE`| →→→→ _Equivalent_ →→→→ <br/>(3532)<hr/>←←←← __ ←←←← <br/>() | **`NOINTEGRATE`**| | | | | 
| `NOINTEGRATE`| _Equivalent_ <br/>(346/1707)| `NOINTEGRATE`| →→→→ _Equivalent_ →→→→ <br/>(3532)<hr/>←←←← __ ←←←← <br/>() | **`NOINTEGRATE`**| | | | | 
| `NOLIST`| _Equivalent_ <br/>(347/1708)| `NOLIST`| →→→→ _Equivalent_ →→→→ <br/>(3488)<hr/>←←←← __ ←←←← <br/>() | **`NOLIST`**| | | | | 
| `NOLIST`| _Equivalent_ <br/>(347/1708)| `NOLIST`| →→→→ _Equivalent_ →→→→ <br/>(3488)<hr/>←←←← __ ←←←← <br/>() | **`NOLIST`**| | | | | 
| `NOMOU`| _Equivalent_ <br/>(348/1709)| `NOMOU`| →→→→ _Equivalent_ →→→→ <br/>(3498)<hr/>←←←← __ ←←←← <br/>() | **`NOMOU`**| | | | | 
| `NOMOU`| _Equivalent_ <br/>(348/1709)| `NOMOU`| →→→→ _Equivalent_ →→→→ <br/>(3498)<hr/>←←←← __ ←←←← <br/>() | **`NOMOU`**| | | | | 
| `NOORGPOL`| _Equivalent_ <br/>(349/1710)| `NOORGPOL`| →→→→ _Equivalent_ →→→→ <br/>(3522)<hr/>←←←← __ ←←←← <br/>() | **`NOORGPOL`**| | | | | 
| `NOORGPOL`| _Equivalent_ <br/>(349/1710)| `NOORGPOL`| →→→→ _Equivalent_ →→→→ <br/>(3522)<hr/>←←←← __ ←←←← <br/>() | **`NOORGPOL`**| | | | | 
| `NOPAT`| _Equivalent_ <br/>(350/1711)| `NOPAT`| →→→→ _Equivalent_ →→→→ <br/>(3482)<hr/>←←←← __ ←←←← <br/>() | **`NOPAT`**| | | | | 
| `NOPAT`| _Equivalent_ <br/>(350/1711)| `NOPAT`| →→→→ _Equivalent_ →→→→ <br/>(3482)<hr/>←←←← __ ←←←← <br/>() | **`NOPAT`**| | | | | 
| `NOPERSISTP`| _Equivalent_ <br/>(351/1712)| `NOPERSISTP`| →→→→ _Equivalent_ →→→→ <br/>(3539)<hr/>←←←← __ ←←←← <br/>() | **`NOPERSISTP`**| | | | | 
| `NOPERSISTP`| _Equivalent_ <br/>(351/1712)| `NOPERSISTP`| →→→→ _Equivalent_ →→→→ <br/>(3539)<hr/>←←←← __ ←←←← <br/>() | **`NOPERSISTP`**| | | | | 
| `NORDSCLCD`| _Equivalent_ <br/>(352/1713)| `NORDSCLCD`| →→→→ _Equivalent_ →→→→ <br/>(3544)<hr/>←←←← __ ←←←← <br/>() | **`NORDSCLCD`**| | | | | 
| `NORDSCLCD`| _Equivalent_ <br/>(352/1713)| `NORDSCLCD`| →→→→ _Equivalent_ →→→→ <br/>(3544)<hr/>←←←← __ ←←←← <br/>() | **`NORDSCLCD`**| | | | | 
| `NORDSCLCDS`| _Equivalent_ <br/>(353/1714)| `NORDSCLCDS`| →→→→ _Equivalent_ →→→→ <br/>(3538)<hr/>←←←← __ ←←←← <br/>() | **`NORDSCLCDS`**| | | | | 
| `NORDSCLCDS`| _Equivalent_ <br/>(353/1714)| `NORDSCLCDS`| →→→→ _Equivalent_ →→→→ <br/>(3538)<hr/>←←←← __ ←←←← <br/>() | **`NORDSCLCDS`**| | | | | 
| `NORDSCLW`| _Equivalent_ <br/>(354/1715)| `NORDSCLW`| →→→→ _Equivalent_ →→→→ <br/>(3487)<hr/>←←←← __ ←←←← <br/>() | **`NORDSCLW`**| | | | | 
| `NORDSCLW`| _Equivalent_ <br/>(354/1715)| `NORDSCLW`| →→→→ _Equivalent_ →→→→ <br/>(3487)<hr/>←←←← __ ←←←← <br/>() | **`NORDSCLW`**| | | | | 
| `NORELINK`| _Equivalent_ <br/>(355/1716)| `NORELINK`| →→→→ _Equivalent_ →→→→ <br/>(3491)<hr/>←←←← __ ←←←← <br/>() | **`NORELINK`**| | | | | 
| `NORELINK`| _Equivalent_ <br/>(355/1716)| `NORELINK`| →→→→ _Equivalent_ →→→→ <br/>(3491)<hr/>←←←← __ ←←←← <br/>() | **`NORELINK`**| | | | | 
| `NOREUSE`| _Equivalent_ <br/>(356/1717)| `NOREUSE`| →→→→ _Equivalent_ →→→→ <br/>(3489)<hr/>←←←← __ ←←←← <br/>() | **`NOREUSE`**| | | | | 
| `NOREUSE`| _Equivalent_ <br/>(356/1717)| `NOREUSE`| →→→→ _Equivalent_ →→→→ <br/>(3489)<hr/>←←←← __ ←←←← <br/>() | **`NOREUSE`**| | | | | 
| `NOVIP`| _Equivalent_ <br/>(357/1718)| `NOVIP`| →→→→ _Equivalent_ →→→→ <br/>(3546)<hr/>←←←← __ ←←←← <br/>() | **`NOVIP`**| | | | | 
| `NOVIP`| _Equivalent_ <br/>(357/1718)| `NOVIP`| →→→→ _Equivalent_ →→→→ <br/>(3546)<hr/>←←←← __ ←←←← <br/>() | **`NOVIP`**| | | | | 
| `ORCON`| _Equivalent_ <br/>(358/1719)| `ORCON`| →→→→ _Equivalent_ →→→→ <br/>(3536)<hr/>←←←← __ ←←←← <br/>() | **`ORCON`**| | | | | 
| `ORCON`| _Equivalent_ <br/>(358/1719)| `ORCON`| →→→→ _Equivalent_ →→→→ <br/>(3536)<hr/>←←←← __ ←←←← <br/>() | **`ORCON`**| | | | | 
| `RefrainPolicy`| _Equivalent_ <br/>(370/1732)| `RefrainPolicy`| →→→→ _Equivalent_ →→→→ <br/>(3473)<hr/>←←←← __ ←←←← <br/>() | **`RefrainPolicy`**| | | | | 
| `RefrainPolicy`| _Equivalent_ <br/>(370/1732)| `RefrainPolicy`| →→→→ _Equivalent_ →→→→ <br/>(3473)<hr/>←←←← __ ←←←← <br/>() | **`RefrainPolicy`**| | | | | 
| `SecurityPolicy`| _Equivalent_ <br/>(377/1740)| `SecurityPolicy`| →→→→ _Equivalent_ →→→→ <br/>(3476)<hr/>←←←← __ ←←←← <br/>() | **`SecurityPolicy`**| | | | | 
| `SecurityPolicy`| _Equivalent_ <br/>(377/1740)| `SecurityPolicy`| →→→→ _Equivalent_ →→→→ <br/>(3476)<hr/>←←←← __ ←←←← <br/>() | **`SecurityPolicy`**| | | | | 
| | | | | **`ANONY`**| | | | | 
| | | | | **`AOD`**| | | | | 
| | | | | **`AUDIT`**| | | | | 
| | | | | **`AUDTR`**| | | | | 
| | | | | **`CPLYCC`**| | | | | 
| | | | | **`CPLYCD`**| | | | | 
| | | | | **`CPLYJPP`**| | | | | 
| | | | | **`CPLYOPP`**| | | | | 
| | | | | **`CPLYOSP`**| | | | | 
| | | | | **`CPLYPOL`**| | | | | 
| | | | | **`DECLASSIFYLABEL`**| | | | | 
| | | | | **`DEID`**| | | | | 
| | | | | **`DELAU`**| | | | | 
| | | | | **`DOWNGRDLABEL`**| | | | | 
| | | | | **`DRIVLABEL`**| | | | | 
| | | | | **`ENCRYPTR`**| | | | | 
| | | | | **`ENCRYPTT`**| | | | | 
| | | | | **`ENCRYPTU`**| | | | | 
| | | | | **`ENCRYPT`**| | | | | 
| | | | | **`HUAPRV`**| | | | | 
| | | | | **`LABEL`**| | | | | 
| | | | | **`MASK`**| | | | | 
| | | | | **`MINEC`**| | | | | 
| | | | | **`PERSISTLABEL`**| | | | | 
| | | | | **`PRIVMARK`**| | | | | 
| | | | | **`PSEUD`**| | | | | 
| | | | | **`REDACT`**| | | | | 
| | | | | **`UPGRDLABEL`**| | | | | 
| | | | | **`ObligationPolicy`**| | | | | 
| | | | | **`NOAUTH`**| | | | | 
| | | | | **`NOCOLLECT`**| | | | | 
| | | | | **`NODSCLCD`**| | | | | 
| | | | | **`NODSCLCDS`**| | | | | 
| | | | | **`NOINTEGRATE`**| | | | | 
| | | | | **`NOLIST`**| | | | | 
| | | | | **`NOMOU`**| | | | | 
| | | | | **`NOORGPOL`**| | | | | 
| | | | | **`NOPAT`**| | | | | 
| | | | | **`NOPERSISTP`**| | | | | 
| | | | | **`NORDSCLCD`**| | | | | 
| | | | | **`NORDSCLCDS`**| | | | | 
| | | | | **`NORDSCLW`**| | | | | 
| | | | | **`NORELINK`**| | | | | 
| | | | | **`NOREUSE`**| | | | | 
| | | | | **`NOVIP`**| | | | | 
| | | | | **`ORCON`**| | | | | 
| | | | | **`RefrainPolicy`**| | | | | 
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v3-ActReason`
| `PurposeOfUse`| _Equivalent_ <br/>(415/1785)| `PurposeOfUse`| →→→→ _Equivalent_ →→→→ <br/>(3462)<hr/>←←←← __ ←←←← <br/>() | **`PurposeOfUse`**| | | | | 
| `PurposeOfUse`| _Equivalent_ <br/>(415/1785)| `PurposeOfUse`| →→→→ _Equivalent_ →→→→ <br/>(3462)<hr/>←←←← __ ←←←← <br/>() | **`PurposeOfUse`**| | | | | 
| `HMARKT`| _Equivalent_ <br/>(399/1769)| `HMARKT`| →→→→ _Equivalent_ →→→→ <br/>(3449)<hr/>←←←← __ ←←←← <br/>() | **`HMARKT`**| | | | | 
| `HMARKT`| _Equivalent_ <br/>(399/1769)| `HMARKT`| →→→→ _Equivalent_ →→→→ <br/>(3449)<hr/>←←←← __ ←←←← <br/>() | **`HMARKT`**| | | | | 
| `HOPERAT`| _Equivalent_ <br/>(400/1770)| `HOPERAT`| →→→→ _Equivalent_ →→→→ <br/>(3460)<hr/>←←←← __ ←←←← <br/>() | **`HOPERAT`**| | | | | 
| `HOPERAT`| _Equivalent_ <br/>(400/1770)| `HOPERAT`| →→→→ _Equivalent_ →→→→ <br/>(3460)<hr/>←←←← __ ←←←← <br/>() | **`HOPERAT`**| | | | | 
| `CAREMGT`| _Equivalent_ <br/>(379/1749)| `CAREMGT`| →→→→ _Equivalent_ →→→→ <br/>(3444)<hr/>←←←← __ ←←←← <br/>() | **`CAREMGT`**| | | | | 
| `CAREMGT`| _Equivalent_ <br/>(379/1749)| `CAREMGT`| →→→→ _Equivalent_ →→→→ <br/>(3444)<hr/>←←←← __ ←←←← <br/>() | **`CAREMGT`**| | | | | 
| `DONAT`| _Equivalent_ <br/>(386/1756)| `DONAT`| →→→→ _Equivalent_ →→→→ <br/>(3457)<hr/>←←←← __ ←←←← <br/>() | **`DONAT`**| | | | | 
| `DONAT`| _Equivalent_ <br/>(386/1756)| `DONAT`| →→→→ _Equivalent_ →→→→ <br/>(3457)<hr/>←←←← __ ←←←← <br/>() | **`DONAT`**| | | | | 
| `FRAUD`| _Equivalent_ <br/>(392/1762)| `FRAUD`| →→→→ _Equivalent_ →→→→ <br/>(3465)<hr/>←←←← __ ←←←← <br/>() | **`FRAUD`**| | | | | 
| `FRAUD`| _Equivalent_ <br/>(392/1762)| `FRAUD`| →→→→ _Equivalent_ →→→→ <br/>(3465)<hr/>←←←← __ ←←←← <br/>() | **`FRAUD`**| | | | | 
| `GOV`| _Equivalent_ <br/>(393/1763)| `GOV`| →→→→ _Equivalent_ →→→→ <br/>(3458)<hr/>←←←← __ ←←←← <br/>() | **`GOV`**| | | | | 
| `GOV`| _Equivalent_ <br/>(393/1763)| `GOV`| →→→→ _Equivalent_ →→→→ <br/>(3458)<hr/>←←←← __ ←←←← <br/>() | **`GOV`**| | | | | 
| `HACCRED`| _Equivalent_ <br/>(394/1764)| `HACCRED`| →→→→ _Equivalent_ →→→→ <br/>(3427)<hr/>←←←← __ ←←←← <br/>() | **`HACCRED`**| | | | | 
| `HACCRED`| _Equivalent_ <br/>(394/1764)| `HACCRED`| →→→→ _Equivalent_ →→→→ <br/>(3427)<hr/>←←←← __ ←←←← <br/>() | **`HACCRED`**| | | | | 
| `HCOMPL`| _Equivalent_ <br/>(395/1765)| `HCOMPL`| →→→→ _Equivalent_ →→→→ <br/>(3466)<hr/>←←←← __ ←←←← <br/>() | **`HCOMPL`**| | | | | 
| `HCOMPL`| _Equivalent_ <br/>(395/1765)| `HCOMPL`| →→→→ _Equivalent_ →→→→ <br/>(3466)<hr/>←←←← __ ←←←← <br/>() | **`HCOMPL`**| | | | | 
| `HDECD`| _Equivalent_ <br/>(396/1766)| `HDECD`| →→→→ _Equivalent_ →→→→ <br/>(3447)<hr/>←←←← __ ←←←← <br/>() | **`HDECD`**| | | | | 
| `HDECD`| _Equivalent_ <br/>(396/1766)| `HDECD`| →→→→ _Equivalent_ →→→→ <br/>(3447)<hr/>←←←← __ ←←←← <br/>() | **`HDECD`**| | | | | 
| `HDIRECT`| _Equivalent_ <br/>(397/1767)| `HDIRECT`| →→→→ _Equivalent_ →→→→ <br/>(3453)<hr/>←←←← __ ←←←← <br/>() | **`HDIRECT`**| | | | | 
| `HDIRECT`| _Equivalent_ <br/>(397/1767)| `HDIRECT`| →→→→ _Equivalent_ →→→→ <br/>(3453)<hr/>←←←← __ ←←←← <br/>() | **`HDIRECT`**| | | | | 
| | | `active`| | **`HDM`**| | | | | 
| | | `active`| | **`HDM`**| | | | | 
| `HLEGAL`| _Equivalent_ <br/>(398/1768)| `HLEGAL`| →→→→ _Equivalent_ →→→→ <br/>(3448)<hr/>←←←← __ ←←←← <br/>() | **`HLEGAL`**| | | | | 
| `HLEGAL`| _Equivalent_ <br/>(398/1768)| `HLEGAL`| →→→→ _Equivalent_ →→→→ <br/>(3448)<hr/>←←←← __ ←←←← <br/>() | **`HLEGAL`**| | | | | 
| `HOUTCOMS`| _Equivalent_ <br/>(401/1771)| `HOUTCOMS`| →→→→ _Equivalent_ →→→→ <br/>(3452)<hr/>←←←← __ ←←←← <br/>() | **`HOUTCOMS`**| | | | | 
| `HOUTCOMS`| _Equivalent_ <br/>(401/1771)| `HOUTCOMS`| →→→→ _Equivalent_ →→→→ <br/>(3452)<hr/>←←←← __ ←←←← <br/>() | **`HOUTCOMS`**| | | | | 
| `HPRGRP`| _Equivalent_ <br/>(403/1773)| `HPRGRP`| →→→→ _Equivalent_ →→→→ <br/>(3438)<hr/>←←←← __ ←←←← <br/>() | **`HPRGRP`**| | | | | 
| `HPRGRP`| _Equivalent_ <br/>(403/1773)| `HPRGRP`| →→→→ _Equivalent_ →→→→ <br/>(3438)<hr/>←←←← __ ←←←← <br/>() | **`HPRGRP`**| | | | | 
| `HQUALIMP`| _Equivalent_ <br/>(404/1774)| `HQUALIMP`| →→→→ _Equivalent_ →→→→ <br/>(3442)<hr/>←←←← __ ←←←← <br/>() | **`HQUALIMP`**| | | | | 
| `HQUALIMP`| _Equivalent_ <br/>(404/1774)| `HQUALIMP`| →→→→ _Equivalent_ →→→→ <br/>(3442)<hr/>←←←← __ ←←←← <br/>() | **`HQUALIMP`**| | | | | 
| `HSYSADMIN`| _Equivalent_ <br/>(406/1776)| `HSYSADMIN`| →→→→ _Equivalent_ →→→→ <br/>(3445)<hr/>←←←← __ ←←←← <br/>() | **`HSYSADMIN`**| | | | | 
| `HSYSADMIN`| _Equivalent_ <br/>(406/1776)| `HSYSADMIN`| →→→→ _Equivalent_ →→→→ <br/>(3445)<hr/>←←←← __ ←←←← <br/>() | **`HSYSADMIN`**| | | | | 
| | | `active`| | **`LABELING`**| | | | | 
| | | `active`| | **`LABELING`**| | | | | 
| | | `active`| | **`METAMGT`**| | | | | 
| | | `active`| | **`METAMGT`**| | | | | 
| `MEMADMIN`| _Equivalent_ <br/>(407/1777)| `MEMADMIN`| →→→→ _Equivalent_ →→→→ <br/>(3461)<hr/>←←←← __ ←←←← <br/>() | **`MEMADMIN`**| | | | | 
| `MEMADMIN`| _Equivalent_ <br/>(407/1777)| `MEMADMIN`| →→→→ _Equivalent_ →→→→ <br/>(3461)<hr/>←←←← __ ←←←← <br/>() | **`MEMADMIN`**| | | | | 
| | | `active`| | **`MILCDM`**| | | | | 
| | | `active`| | **`MILCDM`**| | | | | 
| `PATADMIN`| _Equivalent_ <br/>(408/1778)| `PATADMIN`| →→→→ _Equivalent_ →→→→ <br/>(3435)<hr/>←←←← __ ←←←← <br/>() | **`PATADMIN`**| | | | | 
| `PATADMIN`| _Equivalent_ <br/>(408/1778)| `PATADMIN`| →→→→ _Equivalent_ →→→→ <br/>(3435)<hr/>←←←← __ ←←←← <br/>() | **`PATADMIN`**| | | | | 
| `PATSFTY`| _Equivalent_ <br/>(410/1780)| `PATSFTY`| →→→→ _Equivalent_ →→→→ <br/>(3446)<hr/>←←←← __ ←←←← <br/>() | **`PATSFTY`**| | | | | 
| `PATSFTY`| _Equivalent_ <br/>(410/1780)| `PATSFTY`| →→→→ _Equivalent_ →→→→ <br/>(3446)<hr/>←←←← __ ←←←← <br/>() | **`PATSFTY`**| | | | | 
| `PERFMSR`| _Equivalent_ <br/>(411/1781)| `PERFMSR`| →→→→ _Equivalent_ →→→→ <br/>(3432)<hr/>←←←← __ ←←←← <br/>() | **`PERFMSR`**| | | | | 
| `PERFMSR`| _Equivalent_ <br/>(411/1781)| `PERFMSR`| →→→→ _Equivalent_ →→→→ <br/>(3432)<hr/>←←←← __ ←←←← <br/>() | **`PERFMSR`**| | | | | 
| `RECORDMGT`| _Equivalent_ <br/>(416/1786)| `RECORDMGT`| →→→→ _Equivalent_ →→→→ <br/>(3443)<hr/>←←←← __ ←←←← <br/>() | **`RECORDMGT`**| | | | | 
| `RECORDMGT`| _Equivalent_ <br/>(416/1786)| `RECORDMGT`| →→→→ _Equivalent_ →→→→ <br/>(3443)<hr/>←←←← __ ←←←← <br/>() | **`RECORDMGT`**| | | | | 
| | | `active`| | **`SYSDEV`**| | | | | 
| | | `active`| | **`SYSDEV`**| | | | | 
| | | `active`| | **`HTEST`**| | | | | 
| | | `active`| | **`HTEST`**| | | | | 
| `TRAIN`| _Equivalent_ <br/>(420/1790)| `TRAIN`| →→→→ _Equivalent_ →→→→ <br/>(3439)<hr/>←←←← __ ←←←← <br/>() | **`TRAIN`**| | | | | 
| `TRAIN`| _Equivalent_ <br/>(420/1790)| `TRAIN`| →→→→ _Equivalent_ →→→→ <br/>(3439)<hr/>←←←← __ ←←←← <br/>() | **`TRAIN`**| | | | | 
| `HPAYMT`| _Equivalent_ <br/>(402/1772)| `HPAYMT`| →→→→ _Equivalent_ →→→→ <br/>(3456)<hr/>←←←← __ ←←←← <br/>() | **`HPAYMT`**| | | | | 
| `HPAYMT`| _Equivalent_ <br/>(402/1772)| `HPAYMT`| →→→→ _Equivalent_ →→→→ <br/>(3456)<hr/>←←←← __ ←←←← <br/>() | **`HPAYMT`**| | | | | 
| `CLMATTCH`| _Equivalent_ <br/>(382/1752)| `CLMATTCH`| →→→→ _Equivalent_ →→→→ <br/>(3464)<hr/>←←←← __ ←←←← <br/>() | **`CLMATTCH`**| | | | | 
| `CLMATTCH`| _Equivalent_ <br/>(382/1752)| `CLMATTCH`| →→→→ _Equivalent_ →→→→ <br/>(3464)<hr/>←←←← __ ←←←← <br/>() | **`CLMATTCH`**| | | | | 
| `COVAUTH`| _Equivalent_ <br/>(383/1753)| `COVAUTH`| →→→→ _Equivalent_ →→→→ <br/>(3459)<hr/>←←←← __ ←←←← <br/>() | **`COVAUTH`**| | | | | 
| `COVAUTH`| _Equivalent_ <br/>(383/1753)| `COVAUTH`| →→→→ _Equivalent_ →→→→ <br/>(3459)<hr/>←←←← __ ←←←← <br/>() | **`COVAUTH`**| | | | | 
| `COVERAGE`| _Equivalent_ <br/>(384/1754)| `COVERAGE`| →→→→ _Equivalent_ →→→→ <br/>(3467)<hr/>←←←← __ ←←←← <br/>() | **`COVERAGE`**| | | | | 
| `COVERAGE`| _Equivalent_ <br/>(384/1754)| `COVERAGE`| →→→→ _Equivalent_ →→→→ <br/>(3467)<hr/>←←←← __ ←←←← <br/>() | **`COVERAGE`**| | | | | 
| `ELIGDTRM`| _Equivalent_ <br/>(387/1757)| `ELIGDTRM`| →→→→ _Equivalent_ →→→→ <br/>(3428)<hr/>←←←← __ ←←←← <br/>() | **`ELIGDTRM`**| | | | | 
| `ELIGDTRM`| _Equivalent_ <br/>(387/1757)| `ELIGDTRM`| →→→→ _Equivalent_ →→→→ <br/>(3428)<hr/>←←←← __ ←←←← <br/>() | **`ELIGDTRM`**| | | | | 
| `ELIGVER`| _Equivalent_ <br/>(388/1758)| `ELIGVER`| →→→→ _Equivalent_ →→→→ <br/>(3468)<hr/>←←←← __ ←←←← <br/>() | **`ELIGVER`**| | | | | 
| `ELIGVER`| _Equivalent_ <br/>(388/1758)| `ELIGVER`| →→→→ _Equivalent_ →→→→ <br/>(3468)<hr/>←←←← __ ←←←← <br/>() | **`ELIGVER`**| | | | | 
| `ENROLLM`| _Equivalent_ <br/>(389/1759)| `ENROLLM`| →→→→ _Equivalent_ →→→→ <br/>(3437)<hr/>←←←← __ ←←←← <br/>() | **`ENROLLM`**| | | | | 
| `ENROLLM`| _Equivalent_ <br/>(389/1759)| `ENROLLM`| →→→→ _Equivalent_ →→→→ <br/>(3437)<hr/>←←←← __ ←←←← <br/>() | **`ENROLLM`**| | | | | 
| | | `active`| | **`MILDCRG`**| | | | | 
| | | `active`| | **`MILDCRG`**| | | | | 
| `REMITADV`| _Equivalent_ <br/>(417/1787)| `REMITADV`| →→→→ _Equivalent_ →→→→ <br/>(3441)<hr/>←←←← __ ←←←← <br/>() | **`REMITADV`**| | | | | 
| `REMITADV`| _Equivalent_ <br/>(417/1787)| `REMITADV`| →→→→ _Equivalent_ →→→→ <br/>(3441)<hr/>←←←← __ ←←←← <br/>() | **`REMITADV`**| | | | | 
| `HRESCH`| _Equivalent_ <br/>(405/1775)| `HRESCH`| →→→→ _Equivalent_ →→→→ <br/>(3436)<hr/>←←←← __ ←←←← <br/>() | **`HRESCH`**| | | | | 
| `HRESCH`| _Equivalent_ <br/>(405/1775)| `HRESCH`| →→→→ _Equivalent_ →→→→ <br/>(3436)<hr/>←←←← __ ←←←← <br/>() | **`HRESCH`**| | | | | 
| | | `active`| | **`BIORCH`**| | | | | 
| | | `active`| | **`BIORCH`**| | | | | 
| `CLINTRCH`| _Equivalent_ <br/>(380/1750)| `CLINTRCH`| →→→→ _Equivalent_ →→→→ <br/>(3430)<hr/>←←←← __ ←←←← <br/>() | **`CLINTRCH`**| | | | | 
| `CLINTRCH`| _Equivalent_ <br/>(380/1750)| `CLINTRCH`| →→→→ _Equivalent_ →→→→ <br/>(3430)<hr/>←←←← __ ←←←← <br/>() | **`CLINTRCH`**| | | | | 
| | | `active`| | **`CLINTRCHNPC`**| | | | | 
| | | `active`| | **`CLINTRCHNPC`**| | | | | 
| | | `active`| | **`CLINTRCHPC`**| | | | | 
| | | `active`| | **`CLINTRCHPC`**| | | | | 
| | | `active`| | **`PRECLINTRCH`**| | | | | 
| | | `active`| | **`PRECLINTRCH`**| | | | | 
| | | `active`| | **`DSRCH`**| | | | | 
| | | `active`| | **`DSRCH`**| | | | | 
| | | `active`| | **`POARCH`**| | | | | 
| | | `active`| | **`POARCH`**| | | | | 
| | | `active`| | **`TRANSRCH`**| | | | | 
| | | `active`| | **`TRANSRCH`**| | | | | 
| `PATRQT`| _Equivalent_ <br/>(409/1779)| `PATRQT`| →→→→ _Equivalent_ →→→→ <br/>(3463)<hr/>←←←← __ ←←←← <br/>() | **`PATRQT`**| | | | | 
| `PATRQT`| _Equivalent_ <br/>(409/1779)| `PATRQT`| →→→→ _Equivalent_ →→→→ <br/>(3463)<hr/>←←←← __ ←←←← <br/>() | **`PATRQT`**| | | | | 
| `FAMRQT`| _Equivalent_ <br/>(391/1761)| `FAMRQT`| →→→→ _Equivalent_ →→→→ <br/>(3451)<hr/>←←←← __ ←←←← <br/>() | **`FAMRQT`**| | | | | 
| `FAMRQT`| _Equivalent_ <br/>(391/1761)| `FAMRQT`| →→→→ _Equivalent_ →→→→ <br/>(3451)<hr/>←←←← __ ←←←← <br/>() | **`FAMRQT`**| | | | | 
| `PWATRNY`| _Equivalent_ <br/>(414/1784)| `PWATRNY`| →→→→ _Equivalent_ →→→→ <br/>(3431)<hr/>←←←← __ ←←←← <br/>() | **`PWATRNY`**| | | | | 
| `PWATRNY`| _Equivalent_ <br/>(414/1784)| `PWATRNY`| →→→→ _Equivalent_ →→→→ <br/>(3431)<hr/>←←←← __ ←←←← <br/>() | **`PWATRNY`**| | | | | 
| `SUPNWK`| _Equivalent_ <br/>(418/1788)| `SUPNWK`| →→→→ _Equivalent_ →→→→ <br/>(3450)<hr/>←←←← __ ←←←← <br/>() | **`SUPNWK`**| | | | | 
| `SUPNWK`| _Equivalent_ <br/>(418/1788)| `SUPNWK`| →→→→ _Equivalent_ →→→→ <br/>(3450)<hr/>←←←← __ ←←←← <br/>() | **`SUPNWK`**| | | | | 
| `PUBHLTH`| _Equivalent_ <br/>(413/1783)| `PUBHLTH`| →→→→ _Equivalent_ →→→→ <br/>(3434)<hr/>←←←← __ ←←←← <br/>() | **`PUBHLTH`**| | | | | 
| `PUBHLTH`| _Equivalent_ <br/>(413/1783)| `PUBHLTH`| →→→→ _Equivalent_ →→→→ <br/>(3434)<hr/>←←←← __ ←←←← <br/>() | **`PUBHLTH`**| | | | | 
| `DISASTER`| _Equivalent_ <br/>(385/1755)| `DISASTER`| →→→→ _Equivalent_ →→→→ <br/>(3455)<hr/>←←←← __ ←←←← <br/>() | **`DISASTER`**| | | | | 
| `DISASTER`| _Equivalent_ <br/>(385/1755)| `DISASTER`| →→→→ _Equivalent_ →→→→ <br/>(3455)<hr/>←←←← __ ←←←← <br/>() | **`DISASTER`**| | | | | 
| `THREAT`| _Equivalent_ <br/>(419/1789)| `THREAT`| →→→→ _Equivalent_ →→→→ <br/>(3469)<hr/>←←←← __ ←←←← <br/>() | **`THREAT`**| | | | | 
| `THREAT`| _Equivalent_ <br/>(419/1789)| `THREAT`| →→→→ _Equivalent_ →→→→ <br/>(3469)<hr/>←←←← __ ←←←← <br/>() | **`THREAT`**| | | | | 
| `TREAT`| _Equivalent_ <br/>(421/1791)| `TREAT`| →→→→ _Equivalent_ →→→→ <br/>(3433)<hr/>←←←← __ ←←←← <br/>() | **`TREAT`**| | | | | 
| `TREAT`| _Equivalent_ <br/>(421/1791)| `TREAT`| →→→→ _Equivalent_ →→→→ <br/>(3433)<hr/>←←←← __ ←←←← <br/>() | **`TREAT`**| | | | | 
| `CLINTRL`| _Equivalent_ <br/>(381/1751)| `CLINTRL`| →→→→ _Equivalent_ →→→→ <br/>(3440)<hr/>←←←← __ ←←←← <br/>() | **`CLINTRL`**| | | | | 
| `CLINTRL`| _Equivalent_ <br/>(381/1751)| `CLINTRL`| →→→→ _Equivalent_ →→→→ <br/>(3440)<hr/>←←←← __ ←←←← <br/>() | **`CLINTRL`**| | | | | 
| | | `active`| | **`COC`**| | | | | 
| | | `active`| | **`COC`**| | | | | 
| `ETREAT`| _Equivalent_ <br/>(390/1760)| `ETREAT`| →→→→ _Equivalent_ →→→→ <br/>(3454)<hr/>←←←← __ ←←←← <br/>() | **`ETREAT`**| | | | | 
| `ETREAT`| _Equivalent_ <br/>(390/1760)| `ETREAT`| →→→→ _Equivalent_ →→→→ <br/>(3454)<hr/>←←←← __ ←←←← <br/>() | **`ETREAT`**| | | | | 
| | | `active`| | **`BTG`**| | | | | 
| | | `active`| | **`BTG`**| | | | | 
| | | `active`| | **`ERTREAT`**| | | | | 
| | | `active`| | **`ERTREAT`**| | | | | 
| `POPHLTH`| _Equivalent_ <br/>(412/1782)| `POPHLTH`| →→→→ _Equivalent_ →→→→ <br/>(3429)<hr/>←←←← __ ←←←← <br/>() | **`POPHLTH`**| | | | | 
| `POPHLTH`| _Equivalent_ <br/>(412/1782)| `POPHLTH`| →→→→ _Equivalent_ →→→→ <br/>(3429)<hr/>←←←← __ ←←←← <br/>() | **`POPHLTH`**| | | | | 
| | | | | **`COVERAGE`**| | | | | 
| | | | | **`ETREAT`**| | | | | 
| | | | | **`HMARKT`**| | | | | 
| | | | | **`HOPERAT`**| | | | | 
| | | | | **`HPAYMT`**| | | | | 
| | | | | **`HRESCH`**| | | | | 
| | | | | **`PATRQT`**| | | | | 
| | | | | **`PUBHLTH`**| | | | | 
| | | | | **`TREAT`**| | | | | 
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v3-ActUSPrivacyLaw`
| `42CFRPart2`| _Equivalent_ <br/>(283/1656)| `42CFRPart2`| →→→→ _Equivalent_ →→→→ <br/>(3385)<hr/>←←←← __ ←←←← <br/>() | **`42CFRPart2`**| | | | | 
| `42CFRPart2`| _Equivalent_ <br/>(283/1656)| `42CFRPart2`| →→→→ _Equivalent_ →→→→ <br/>(3385)<hr/>←←←← __ ←←←← <br/>() | **`42CFRPart2`**| | | | | 
| `CommonRule`| _Equivalent_ <br/>(284/1657)| `CommonRule`| →→→→ _Equivalent_ →→→→ <br/>(3383)<hr/>←←←← __ ←←←← <br/>() | **`CommonRule`**| | | | | 
| `CommonRule`| _Equivalent_ <br/>(284/1657)| `CommonRule`| →→→→ _Equivalent_ →→→→ <br/>(3383)<hr/>←←←← __ ←←←← <br/>() | **`CommonRule`**| | | | | 
| `HIPAANOPP`| _Equivalent_ <br/>(285/1658)| `HIPAANOPP`| →→→→ _Equivalent_ →→→→ <br/>(3382)<hr/>←←←← __ ←←←← <br/>() | **`HIPAANOPP`**| | | | | 
| `HIPAANOPP`| _Equivalent_ <br/>(285/1658)| `HIPAANOPP`| →→→→ _Equivalent_ →→→→ <br/>(3382)<hr/>←←←← __ ←←←← <br/>() | **`HIPAANOPP`**| | | | | 
| `HIPAAPsyNotes`| _Equivalent_ <br/>(286/1659)| `HIPAAPsyNotes`| →→→→ _Equivalent_ →→→→ <br/>(3386)<hr/>←←←← __ ←←←← <br/>() | **`HIPAAPsyNotes`**| | | | | 
| `HIPAAPsyNotes`| _Equivalent_ <br/>(286/1659)| `HIPAAPsyNotes`| →→→→ _Equivalent_ →→→→ <br/>(3386)<hr/>←←←← __ ←←←← <br/>() | **`HIPAAPsyNotes`**| | | | | 
| `HIPAASelfPay`| _Equivalent_ <br/>(287/1660)| `HIPAASelfPay`| →→→→ _Equivalent_ →→→→ <br/>(3384)<hr/>←←←← __ ←←←← <br/>() | **`HIPAASelfPay`**| | | | | 
| `HIPAASelfPay`| _Equivalent_ <br/>(287/1660)| `HIPAASelfPay`| →→→→ _Equivalent_ →→→→ <br/>(3384)<hr/>←←←← __ ←←←← <br/>() | **`HIPAASelfPay`**| | | | | 
| `Title38Section7332`| _Equivalent_ <br/>(288/1661)| `Title38Section7332`| →→→→ _Equivalent_ →→→→ <br/>(3387)<hr/>←←←← __ ←←←← <br/>() | **`Title38Section7332`**| | | | | 
| `Title38Section7332`| _Equivalent_ <br/>(288/1661)| `Title38Section7332`| →→→→ _Equivalent_ →→→→ <br/>(3387)<hr/>←←←← __ ←←←← <br/>() | **`Title38Section7332`**| | | | | 
| | | | | **`_ActUSPrivacyLaw`**| | | | | 
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v3-ActCode`
| | | | | **`_ActInformationSensitivityPolicy`**| | | | | 
| | | | | **`_EntitySensitivityPolicyType`**| | | | | 
| | | | | **`_RoleInformationSensitivityPolicy`**| | | | | 
| | | | | **`_InformationSensitivityPolicy`**| | | | | 
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v3-ObservationValue`
| | | | | **`_SECALTINTOBV`**| | | | | 
| | | | | **`_SECDATINTOBV`**| | | | | 
| | | | | **`_SECINTCONOBV`**| | | | | 
| | | | | **`_SECINTPRVABOBV`**| | | | | 
| | | | | **`_SECINTPRVRBOBV`**| | | | | 
| | | | | **`_SECINTPRVOBV`**| | | | | 
| *162 of 237 codes used* <br/>remaining codes:<br/>`_ActInformationSensitivityPolicy`, `_EntitySensitivityPolicyType`, `_InformationSensitivityPolicy`, `_RoleInformationSensitivityPolicy`, `_ActUSPrivacyLaw`, `B`, `C`, `D`, `ETH`, `HIV`, `I`, `PSY`, `S`, `SDV`, `T`, `_Confidentiality`, `_ConfidentialityByAccessKind`, `_ConfidentialityByInfoType`, `_ConfidentialityModifiers`, `_SECALTINTOBV`, `_SECDATINTOBV`, `_SECINTCONOBV`, `_SECINTPRVABOBV`, `_SECINTPRVOBV`, `_SECINTPRVRBOBV`| | *169 of 170 codes used* <br/>remaining codes:<br/>`SOC`, `_ActUSPrivacyLaw`| | *217 of 273 codes used* <br/>remaining codes:<br/>| | | | 

