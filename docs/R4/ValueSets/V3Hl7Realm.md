Comparison of 
Generated at Thursday, April 3, 2025 8:18:17 AM

### v3.hl7Realm

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | v3.hl7Realm |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-hl7Realm` |
| Version | 2018-08-12 |
| Description | Description:<br/><br/>Coded concepts representing Binding Realms (used for Context Binding of terminology in HL7 models)  and/or Namespace Realms (used to help ensure unique identification of HL7 artifacts). This code system is partitioned into three sections: Affiliate realms, Binding realms and Namespace realms.  All affiliate realm codes may automatically be used as both binding realms and namespace realms.  Furthermore, affiliate realms are the only realms that have authority over the creation of binding realms.  (Note that 'affiliate' includes the idea of both international affiliates and the HL7 International organization.)  All other codes must be associated with an owning affiliate realm and must appear as a specialization of _BindingRealm or _NamespaceRealm.  For affiliates whose concepts align with nations, the country codes from ISO 3166-1 2-character alpha are used for the code when possible so these codes should not be used for other realm types.  It is recommended that binding realm and namespace codes submitted by affiliates use the realm code as a prefix to avoid possible collisions with ISO codes.  However, tooling does not currently support namepace realm codes greater than 2 characters.  Open Issue:<br/><br/>The name of the concept property "owningAffiliate" should be changed to better reflect that the property value is the human readable name of the organizational entity that manages the Realm identified by the Realm Code.  Open Issue:<br/><br/>In spite of the inability of tooling to process codes longer than 2 characters, there is at least one realm codes ('SOA') that was added that is 3 characters in length. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `3377` |
| Database Concept Count | `45` |
| Database Active Concept Count | `42` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-hl7Realm`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `AR` | Argentina |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `AT` | Austria |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `AU` | Australia |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `AffiliateRealms` | Affiliate Realms |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `BR` | Brazil |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `BindingRealms` | binding realms |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `C1` | Unclassified Realm |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `CA` | Canada |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `CH` | Switzerland |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `CL` | Chile |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `CN` | China |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `CO` | Columbia |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `CZ` | Czech Republic |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `DE` | Germany |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `DK` | Denmark |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `ES` | Spain |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `FI` | Finland |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `FR` | France |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `GB` | Great Britain |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `GR` | Greece |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `HR` | Croatia |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `IE` | Ireland |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `IN` | India |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `IT` | Italy |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `JP` | Japan |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `KR` | Korea |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `LT` | Lithuania |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `MX` | Mexico |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `NL` | The Netherlands |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `NZ` | New Zealand |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `NamespaceRealms` | namespace realms |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `R1` | Representative Realm |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `RO` | Romania |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `RU` | Russian Federation |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `SE` | Sweden |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `SG` | Singapore |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `SOA` | Southern Africa |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `TR` | Turkey |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `TW` | Taiwan |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `UK` | United Kingdom |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `US` | United States of America |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `UV` | Universal |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `UY` | Uruguay |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `X1` | Example Realm |
| `http://terminology.hl7.org/CodeSystem/v3-hl7Realm` | `ZZ` | Localized Version |
