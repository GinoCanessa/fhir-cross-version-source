Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### AppointmentStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | AppointmentStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/appointmentstatus` |
| Version | 5.0.0 |
| Description | The free/busy status of an appointment. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4294` |
| Database Concept Count | `10` |
| Database Active Concept Count | `10` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Appointment` | `Appointment.status` | `http://hl7.org/fhir/ValueSet/appointmentstatus\|5.0.0` | `Required` | proposed \| pending \| booked \| arrived \| fulfilled \| cancelled \| noshow \| entered-in-error \| checked-in \| waitlist |

### Referenced Systems

* `http://hl7.org/fhir/appointmentstatus`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AppointmentStatus](/docs/R2/ValueSets/AppointmentStatus.md)<br/> `http://hl7.org/fhir/ValueSet/appointmentstatus\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `13`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `172`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AppointmentStatus](/docs/R3/ValueSets/AppointmentStatus.md)<br/> `http://hl7.org/fhir/ValueSet/appointmentstatus\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `338`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `560`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AppointmentStatus](/docs/R4/ValueSets/AppointmentStatus.md)<br/> `http://hl7.org/fhir/ValueSet/appointmentstatus\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1385`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1386`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AppointmentStatus](/docs/R4B/ValueSets/AppointmentStatus.md)<br/> `http://hl7.org/fhir/ValueSet/appointmentstatus\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `782`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1043`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AppointmentStatus](/docs/R5/ValueSets/AppointmentStatus.md)<br/> `http://hl7.org/fhir/ValueSet/appointmentstatus\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set AppointmentStatus from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 AppointmentStatus](/docs/R2/ValueSets/AppointmentStatus.md)| Relationship | [R3 AppointmentStatus](/docs/R3/ValueSets/AppointmentStatus.md)| Relationship | [R4 AppointmentStatus](/docs/R4/ValueSets/AppointmentStatus.md)| Relationship | [R4B AppointmentStatus](/docs/R4B/ValueSets/AppointmentStatus.md)| Relationship | R5 AppointmentStatus
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/appointmentstatus`
| `proposed`| _Equivalent_ <br/>(58/1433)| `proposed`| _Equivalent_ <br/>(2956/5163)| `proposed`| _Equivalent_ <br/>(14466/14467)| `proposed`| _Equivalent_ <br/>(7473/9735)| **`proposed`**
| `pending`| _Equivalent_ <br/>(59/1432)| `pending`| _Equivalent_ <br/>(2957/5162)| `pending`| _Equivalent_ <br/>(14468/14469)| `pending`| _Equivalent_ <br/>(7474/9736)| **`pending`**
| `booked`| _Equivalent_ <br/>(57/1427)| `booked`| _Equivalent_ <br/>(2955/5156)| `booked`| _Equivalent_ <br/>(14470/14471)| `booked`| _Equivalent_ <br/>(7472/9734)| **`booked`**
| `arrived`| _Equivalent_ <br/>(56/1426)| `arrived`| _Equivalent_ <br/>(2954/5155)| `arrived`| _Equivalent_ <br/>(14472/14473)| `arrived`| _Equivalent_ <br/>(7471/9733)| **`arrived`**
| `fulfilled`| _Equivalent_ <br/>(60/1430)| `fulfilled`| _Equivalent_ <br/>(2958/5160)| `fulfilled`| _Equivalent_ <br/>(14474/14475)| `fulfilled`| _Equivalent_ <br/>(7475/9737)| **`fulfilled`**
| `cancelled`| _Equivalent_ <br/>(61/1428)| `cancelled`| _Equivalent_ <br/>(2959/5157)| `cancelled`| _Equivalent_ <br/>(14476/14477)| `cancelled`| _Equivalent_ <br/>(7476/9738)| **`cancelled`**
| `noshow`| _Equivalent_ <br/>(62/1431)| `noshow`| _Equivalent_ <br/>(2960/5161)| `noshow`| _Equivalent_ <br/>(14478/14479)| `noshow`| _Equivalent_ <br/>(7477/9739)| **`noshow`**
| | | `entered-in-error`| _Equivalent_ <br/>(2961/5159)| `entered-in-error`| _Equivalent_ <br/>(14480/14481)| `entered-in-error`| _Equivalent_ <br/>(7479/9741)| **`entered-in-error`**
| | | | | `checked-in`| _Equivalent_ <br/>(14482/14483)| `checked-in`| _Equivalent_ <br/>(7480/9742)| **`checked-in`**
| | | | | `waitlist`| _Equivalent_ <br/>(14484/14485)| `waitlist`| _Equivalent_ <br/>(7478/9740)| **`waitlist`**
| *7 of 7 codes used* | | *8 of 8 codes used* | | *10 of 10 codes used* | | *10 of 10 codes used* | | *10 of 10 codes used* 

