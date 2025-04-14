Comparison of 
Generated at Monday, April 14, 2025 6:17:34 PM

### NamingSystemIdentifierType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | NamingSystemIdentifierType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/namingsystem-identifier-type` |
| Version | 4.3.0 |
| Description | Identifies the style of unique identifier used to identify a namespace. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `3948` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/NamingSystem` | `NamingSystem.uniqueId.type` | `http://hl7.org/fhir/ValueSet/namingsystem-identifier-type\|4.3.0` | `Required` | oid \| uuid \| uri \| other |

### Referenced Systems

* `http://hl7.org/fhir/namingsystem-identifier-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [NamingSystemIdentifierType](/docs/R2/ValueSets/NamingSystemIdentifierType.md)<br/> `http://hl7.org/fhir/ValueSet/namingsystem-identifier-type\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `104`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `260`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [NamingSystemIdentifierType](/docs/R3/ValueSets/NamingSystemIdentifierType.md)<br/> `http://hl7.org/fhir/ValueSet/namingsystem-identifier-type\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `455`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `679`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [NamingSystemIdentifierType](/docs/R4/ValueSets/NamingSystemIdentifierType.md)<br/> `http://hl7.org/fhir/ValueSet/namingsystem-identifier-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1627`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1628`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [NamingSystemIdentifierType](/docs/R4B/ValueSets/NamingSystemIdentifierType.md)<br/> `http://hl7.org/fhir/ValueSet/namingsystem-identifier-type\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `937`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1198`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [NamingSystemIdentifierType](/docs/R5/ValueSets/NamingSystemIdentifierType.md)<br/> `http://hl7.org/fhir/ValueSet/namingsystem-identifier-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set NamingSystemIdentifierType from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 NamingSystemIdentifierType](/docs/R2/ValueSets/NamingSystemIdentifierType.md)| Relationship | [R3 NamingSystemIdentifierType](/docs/R3/ValueSets/NamingSystemIdentifierType.md)| Relationship | [R4 NamingSystemIdentifierType](/docs/R4/ValueSets/NamingSystemIdentifierType.md)| Relationship | R4B NamingSystemIdentifierType| Relationship | [R5 NamingSystemIdentifierType](/docs/R5/ValueSets/NamingSystemIdentifierType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/namingsystem-identifier-type`
| `oid`| _Equivalent_ <br/>(844/2211)| `oid`| _Equivalent_ <br/>(4034/6368)| `oid`| _Equivalent_ <br/>(16662/16663)| **`oid`**| _Equivalent_ <br/>(9030/11339)| `oid`
| `uuid`| _Equivalent_ <br/>(845/2212)| `uuid`| _Equivalent_ <br/>(4035/6369)| `uuid`| _Equivalent_ <br/>(16664/16665)| **`uuid`**| _Equivalent_ <br/>(9031/11342)| `uuid`
| `uri`| _Equivalent_ <br/>(846/2213)| `uri`| _Equivalent_ <br/>(4036/6370)| `uri`| _Equivalent_ <br/>(16666/16667)| **`uri`**| _Equivalent_ <br/>(9032/11341)| `uri`
| `other`| _Equivalent_ <br/>(843/2210)| `other`| _Equivalent_ <br/>(4033/6367)| `other`| _Equivalent_ <br/>(16668/16669)| **`other`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9029)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11340) | `other`
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 6 codes used* <br/>remaining codes:<br/>`iri-stem`, `v2csmnemonic`

