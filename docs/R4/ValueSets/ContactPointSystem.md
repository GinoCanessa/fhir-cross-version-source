Comparison of 
Generated at Tuesday, April 1, 2025 1:39:18 PM

### ContactPointSystem

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ContactPointSystem |
| Canonical URL | `http://hl7.org/fhir/ValueSet/contact-point-system` |
| Version | 4.0.1 |
| Description | Telecommunications form for contact point. |
| Status | `Active` |
| Has Escape Valve Code | `True` |
| Database Key | `2316` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ContactPoint` | `ContactPoint.system` | `http://hl7.org/fhir/ValueSet/contact-point-system\|4.0.1` | `Required` | phone \| fax \| email \| pager \| url \| sms \| other |

### Referenced Systems

* `http://hl7.org/fhir/contact-point-system`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ContactPointSystem](/docs/R2/ValueSets/ContactPointSystem.md)<br/> `http://hl7.org/fhir/ValueSet/contact-point-system\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `48`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `207`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ContactPointSystem](/docs/R3/ValueSets/ContactPointSystem.md)<br/> `http://hl7.org/fhir/ValueSet/contact-point-system\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `378`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `601`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ContactPointSystem](/docs/R4/ValueSets/ContactPointSystem.md)<br/> `http://hl7.org/fhir/ValueSet/contact-point-system\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1451`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1452`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ContactPointSystem](/docs/R4B/ValueSets/ContactPointSystem.md)<br/> `http://hl7.org/fhir/ValueSet/contact-point-system\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `823`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1084`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ContactPointSystem](/docs/R5/ValueSets/ContactPointSystem.md)<br/> `http://hl7.org/fhir/ValueSet/contact-point-system\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ContactPointSystem from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ContactPointSystem](/docs/R2/ValueSets/ContactPointSystem.md)| Relationship | [R3 ContactPointSystem](/docs/R3/ValueSets/ContactPointSystem.md)| Relationship | R4 ContactPointSystem| Relationship | [R4B ContactPointSystem](/docs/R4B/ValueSets/ContactPointSystem.md)| Relationship | [R5 ContactPointSystem](/docs/R5/ValueSets/ContactPointSystem.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/contact-point-system`
| `phone`| _Equivalent_ <br/>(229/1602)| `phone`| _Equivalent_ <br/>(3153/5363)| **`phone`**| _Equivalent_ <br/>(14818/14819)| `phone`| _Equivalent_ <br/>(7710/10012)| `phone`
| `fax`| _Equivalent_ <br/>(230/1599)| `fax`| _Equivalent_ <br/>(3155/5365)| **`fax`**| _Equivalent_ <br/>(14820/14821)| `fax`| _Equivalent_ <br/>(7712/10014)| `fax`
| `email`| _Equivalent_ <br/>(231/1598)| `email`| _Equivalent_ <br/>(3156/5366)| **`email`**| _Equivalent_ <br/>(14822/14823)| `email`| _Equivalent_ <br/>(7713/10015)| `email`
| `pager`| _Equivalent_ <br/>(228/1601)| `pager`| _Equivalent_ <br/>(3152/5362)| **`pager`**| _Equivalent_ <br/>(14824/14825)| `pager`| _Equivalent_ <br/>(7709/10011)| `pager`
| | | `url`| _Equivalent_ <br/>(3157/5367)| **`url`**| _Equivalent_ <br/>(14826/14827)| `url`| _Equivalent_ <br/>(7714/10016)| `url`
| | | `sms`| _Equivalent_ <br/>(3154/5364)| **`sms`**| _Equivalent_ <br/>(14828/14829)| `sms`| _Equivalent_ <br/>(7711/10013)| `sms`
| `other`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(227)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1600) | `other`| _Equivalent_ <br/>(3151/5361)| **`other`**| _Equivalent_ <br/>(14830/14831)| `other`| _Equivalent_ <br/>(7708/10010)| `other`
| *5 of 5 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 

