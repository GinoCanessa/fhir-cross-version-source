Comparison of 
Generated at Thursday, April 3, 2025 8:18:23 AM

### DaysOfWeek

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | DaysOfWeek |
| Canonical URL | `http://hl7.org/fhir/ValueSet/days-of-week` |
| Version | 4.3.0 |
| Description | The days of the week. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `3693` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Timing` | `Timing.repeat.dayOfWeek` | `http://hl7.org/fhir/ValueSet/days-of-week\|4.3.0` | `Required` | mon \| tue \| wed \| thu \| fri \| sat \| sun |
| `http://hl7.org/fhir/StructureDefinition/HealthcareService` | `HealthcareService.availableTime.daysOfWeek` | `http://hl7.org/fhir/ValueSet/days-of-week\|4.3.0` | `Required` | mon \| tue \| wed \| thu \| fri \| sat \| sun |
| `http://hl7.org/fhir/StructureDefinition/Location` | `Location.hoursOfOperation.daysOfWeek` | `http://hl7.org/fhir/ValueSet/days-of-week\|4.3.0` | `Required` | mon \| tue \| wed \| thu \| fri \| sat \| sun |
| `http://hl7.org/fhir/StructureDefinition/PractitionerRole` | `PractitionerRole.availableTime.daysOfWeek` | `http://hl7.org/fhir/ValueSet/days-of-week\|4.3.0` | `Required` | mon \| tue \| wed \| thu \| fri \| sat \| sun |

### Referenced Systems

* `http://hl7.org/fhir/days-of-week`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DaysOfWeek](/docs/R2/ValueSets/DaysOfWeek.md)<br/> `http://hl7.org/fhir/ValueSet/days-of-week\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `82`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `238`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DaysOfWeek](/docs/R3/ValueSets/DaysOfWeek.md)<br/> `http://hl7.org/fhir/ValueSet/days-of-week\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `423`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `645`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DaysOfWeek](/docs/R4/ValueSets/DaysOfWeek.md)<br/> `http://hl7.org/fhir/ValueSet/days-of-week\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1463`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1464`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DaysOfWeek](/docs/R4B/ValueSets/DaysOfWeek.md)<br/> `http://hl7.org/fhir/ValueSet/days-of-week\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1003`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1264`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DaysOfWeek](/docs/R5/ValueSets/DaysOfWeek.md)<br/> `http://hl7.org/fhir/ValueSet/days-of-week\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set DaysOfWeek from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 DaysOfWeek](/docs/R2/ValueSets/DaysOfWeek.md)| Relationship | [R3 DaysOfWeek](/docs/R3/ValueSets/DaysOfWeek.md)| Relationship | [R4 DaysOfWeek](/docs/R4/ValueSets/DaysOfWeek.md)| Relationship | R4B DaysOfWeek| Relationship | [R5 DaysOfWeek](/docs/R5/ValueSets/DaysOfWeek.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/days-of-week`
| `mon`| _Equivalent_ <br/>(582/1943)| `mon`| _Equivalent_ <br/>(3744/6028)| `mon`| _Equivalent_ <br/>(15274/15275)| **`mon`**| _Equivalent_ <br/>(9455/11793)| `mon`
| `tue`| _Equivalent_ <br/>(578/1939)| `tue`| _Equivalent_ <br/>(3740/6024)| `tue`| _Equivalent_ <br/>(15276/15277)| **`tue`**| _Equivalent_ <br/>(9451/11789)| `tue`
| `wed`| _Equivalent_ <br/>(579/1940)| `wed`| _Equivalent_ <br/>(3741/6025)| `wed`| _Equivalent_ <br/>(15278/15279)| **`wed`**| _Equivalent_ <br/>(9452/11790)| `wed`
| `thu`| _Equivalent_ <br/>(577/1938)| `thu`| _Equivalent_ <br/>(3739/6023)| `thu`| _Equivalent_ <br/>(15280/15281)| **`thu`**| _Equivalent_ <br/>(9450/11788)| `thu`
| `fri`| _Equivalent_ <br/>(581/1942)| `fri`| _Equivalent_ <br/>(3743/6027)| `fri`| _Equivalent_ <br/>(15282/15283)| **`fri`**| _Equivalent_ <br/>(9454/11792)| `fri`
| `sat`| _Equivalent_ <br/>(580/1941)| `sat`| _Equivalent_ <br/>(3742/6026)| `sat`| _Equivalent_ <br/>(15284/15285)| **`sat`**| _Equivalent_ <br/>(9453/11791)| `sat`
| `sun`| _Equivalent_ <br/>(583/1944)| `sun`| _Equivalent_ <br/>(3745/6029)| `sun`| _Equivalent_ <br/>(15286/15287)| **`sun`**| _Equivalent_ <br/>(9456/11794)| `sun`
| *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 

