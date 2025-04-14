Comparison of 
Generated at Monday, April 14, 2025 6:17:22 PM

### PractitionerRole

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | PractitionerRole |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/PractitionerRole` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for PractitionerRole Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `562` |
| Database Snapshot Count | `35` |
| Database Differential Count | `21` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `PractitionerRole` | `PractitionerRole` | `PractitionerRole` | PractitionerRole | Roles/organizations the practitioner is associated with | 0..* | PractitionerRole |  |  |
| `PractitionerRole.active` | `PractitionerRole.active` | `active` |  | Whether this practitioner's record is in active use | 0..1 | boolean |  |  |
| `PractitionerRole.availabilityExceptions` | `PractitionerRole.availabilityExceptions` | `availabilityExceptions` |  | Description of availability exceptions | 0..1 | string |  |  |
| `PractitionerRole.availableTime` | `PractitionerRole.availableTime` | `availableTime` |  | Times the Service Site is available | 0..* | BackboneElement |  |  |
| `PractitionerRole.availableTime.allDay` | `PractitionerRole.availableTime.allDay` | `allDay` |  | Always available? e.g. 24 hour service | 0..1 | boolean |  |  |
| `PractitionerRole.availableTime.availableEndTime` | `PractitionerRole.availableTime.availableEndTime` | `availableEndTime` |  | Closing time of day (ignored if allDay = true) | 0..1 | time |  |  |
| `PractitionerRole.availableTime.availableStartTime` | `PractitionerRole.availableTime.availableStartTime` | `availableStartTime` |  | Opening time of day (ignored if allDay = true) | 0..1 | time |  |  |
| `PractitionerRole.availableTime.daysOfWeek` | `PractitionerRole.availableTime.daysOfWeek` | `daysOfWeek` |  | mon \| tue \| wed \| thu \| fri \| sat \| sun | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/days-of-week` |
| `PractitionerRole.availableTime.extension` | `PractitionerRole.availableTime.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `PractitionerRole.availableTime.id` | `PractitionerRole.availableTime.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `PractitionerRole.availableTime.modifierExtension` | `PractitionerRole.availableTime.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `PractitionerRole.code` | `PractitionerRole.code` | `code` |  | Roles which this practitioner may perform | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/practitioner-role` |
| `PractitionerRole.contained` | `PractitionerRole.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `PractitionerRole.endpoint` | `PractitionerRole.endpoint` | `endpoint` |  | Technical endpoints providing access to services operated for the practitioner with this role | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Endpoint) |  |  |
| `PractitionerRole.extension` | `PractitionerRole.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `PractitionerRole.healthcareService` | `PractitionerRole.healthcareService` | `healthcareService` |  | The list of healthcare services that this worker provides for this role's Organization/Location(s) | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService) |  |  |
| `PractitionerRole.id` | `PractitionerRole.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `PractitionerRole.identifier` | `PractitionerRole.identifier` | `identifier` |  | Business Identifiers that are specific to a role/location | 0..* | Identifier |  |  |
| `PractitionerRole.implicitRules` | `PractitionerRole.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `PractitionerRole.language` | `PractitionerRole.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `PractitionerRole.location` | `PractitionerRole.location` | `location` |  | The location(s) at which this practitioner provides care | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `PractitionerRole.meta` | `PractitionerRole.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `PractitionerRole.modifierExtension` | `PractitionerRole.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `PractitionerRole.notAvailable` | `PractitionerRole.notAvailable` | `notAvailable` |  | Not available during this time due to provided reason | 0..* | BackboneElement |  |  |
| `PractitionerRole.notAvailable.description` | `PractitionerRole.notAvailable.description` | `description` |  | Reason presented to the user explaining why time not available | 1..1 | string |  |  |
| `PractitionerRole.notAvailable.during` | `PractitionerRole.notAvailable.during` | `during` |  | Service not availablefrom this date | 0..1 | Period |  |  |
| `PractitionerRole.notAvailable.extension` | `PractitionerRole.notAvailable.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `PractitionerRole.notAvailable.id` | `PractitionerRole.notAvailable.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `PractitionerRole.notAvailable.modifierExtension` | `PractitionerRole.notAvailable.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `PractitionerRole.organization` | `PractitionerRole.organization` | `organization` |  | Organization where the roles are available | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `PractitionerRole.period` | `PractitionerRole.period` | `period` |  | The period during which the practitioner is authorized to perform in these role(s) | 0..1 | Period |  |  |
| `PractitionerRole.practitioner` | `PractitionerRole.practitioner` | `practitioner` |  | Practitioner that is able to provide the defined services for the organation | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `PractitionerRole.specialty` | `PractitionerRole.specialty` | `specialty` |  | Specific specialty of the practitioner | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` |
| `PractitionerRole.telecom` | `PractitionerRole.telecom` | `telecom` |  | Contact details that are specific to the role/location/service | 0..* | ContactPoint |  |  |
| `PractitionerRole.text` | `PractitionerRole.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [PractitionerRole](/docs/R3/Resources/PractitionerRole.md)<br/> `http://hl7.org/fhir/StructureDefinition/PractitionerRole\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `500`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `695`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [PractitionerRole](/docs/R4/Resources/PractitionerRole.md)<br/> `http://hl7.org/fhir/StructureDefinition/PractitionerRole\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1583`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1584`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [PractitionerRole](/docs/R4B/Resources/PractitionerRole.md)<br/> `http://hl7.org/fhir/StructureDefinition/PractitionerRole\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1027`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1256`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [PractitionerRole](/docs/R5/Resources/PractitionerRole.md)<br/> `http://hl7.org/fhir/StructureDefinition/PractitionerRole\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition PractitionerRole from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 PractitionerRole| Relationship | [R4 PractitionerRole](/docs/R4/Resources/PractitionerRole.md)| Relationship | [R4B PractitionerRole](/docs/R4B/Resources/PractitionerRole.md)| Relationship | [R5 PractitionerRole](/docs/R5/Resources/PractitionerRole.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`PractitionerRole`**| _Equivalent_<br/>(17285/17286)| `PractitionerRole`| _Equivalent_<br/>(31825/31826)| `PractitionerRole`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(46441)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(46442)| `PractitionerRole`
| | | **`PractitionerRole.id`**| _Equivalent_<br/>(17287/17288)| `PractitionerRole.id`| _Equivalent_<br/>(31827/31828)| `PractitionerRole.id`| _Equivalent_<br/>(46443/46444)| `PractitionerRole.id`
| | | **`PractitionerRole.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17289)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17290)| `PractitionerRole.meta`| _Equivalent_<br/>(31829/31830)| `PractitionerRole.meta`| _Equivalent_<br/>(46445/46446)| `PractitionerRole.meta`
| | | **`PractitionerRole.implicitRules`**| _Equivalent_<br/>(17291/17292)| `PractitionerRole.implicitRules`| _Equivalent_<br/>(31831/31832)| `PractitionerRole.implicitRules`| _Equivalent_<br/>(46447/46448)| `PractitionerRole.implicitRules`
| | | **`PractitionerRole.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17293)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(17294)| `PractitionerRole.language`| _Equivalent_<br/>(31833/31834)| `PractitionerRole.language`| _Equivalent_<br/>(46449/46450)| `PractitionerRole.language`
| | | **`PractitionerRole.text`**| _Equivalent_<br/>(17295/17296)| `PractitionerRole.text`| _Equivalent_<br/>(31835/31836)| `PractitionerRole.text`| _Equivalent_<br/>(46451/46452)| `PractitionerRole.text`
| | | **`PractitionerRole.contained`**| _Equivalent_<br/>(17297/17298)| `PractitionerRole.contained`| _Equivalent_<br/>(31837/31838)| `PractitionerRole.contained`| _Equivalent_<br/>(46453/46454)| `PractitionerRole.contained`
| | | **`PractitionerRole.extension`**| _Equivalent_<br/>(17299/17300)| `PractitionerRole.extension`| _Equivalent_<br/>(31839/31840)| `PractitionerRole.extension`| _Equivalent_<br/>(46455/46456)| `PractitionerRole.extension`
| | | **`PractitionerRole.modifierExtension`**| _Equivalent_<br/>(17301/17302)| `PractitionerRole.modifierExtension`| _Equivalent_<br/>(31841/31842)| `PractitionerRole.modifierExtension`| _Equivalent_<br/>(46457/46458)| `PractitionerRole.modifierExtension`
| | | **`PractitionerRole.identifier`**| _Equivalent_<br/>(17303/17304)| `PractitionerRole.identifier`| _Equivalent_<br/>(31843/31844)| `PractitionerRole.identifier`| _Equivalent_<br/>(46459/46460)| `PractitionerRole.identifier`
| | | **`PractitionerRole.active`**| _Equivalent_<br/>(17305/17306)| `PractitionerRole.active`| _Equivalent_<br/>(31845/31846)| `PractitionerRole.active`| _Equivalent_<br/>(46461/46462)| `PractitionerRole.active`
| | | **`PractitionerRole.period`**| _Equivalent_<br/>(17307/17308)| `PractitionerRole.period`| _Equivalent_<br/>(31847/31848)| `PractitionerRole.period`| _Equivalent_<br/>(46463/46464)| `PractitionerRole.period`
| | | **`PractitionerRole.practitioner`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17309)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17310)| `PractitionerRole.practitioner`| _Equivalent_<br/>(31849/31850)| `PractitionerRole.practitioner`| _Equivalent_<br/>(46465/46466)| `PractitionerRole.practitioner`
| | | **`PractitionerRole.organization`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17311)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17312)| `PractitionerRole.organization`| _Equivalent_<br/>(31851/31852)| `PractitionerRole.organization`| _Equivalent_<br/>(46467/46468)| `PractitionerRole.organization`
| | | **`PractitionerRole.code`**| _Equivalent_<br/>(17313/17314)| `PractitionerRole.code`| _Equivalent_<br/>(31853/31854)| `PractitionerRole.code`| _Equivalent_<br/>(46469/46470)| `PractitionerRole.code`
| | | **`PractitionerRole.specialty`**| _Equivalent_<br/>(17315/17316)| `PractitionerRole.specialty`| _Equivalent_<br/>(31855/31856)| `PractitionerRole.specialty`| _Equivalent_<br/>(46471/46472)| `PractitionerRole.specialty`
| | | **`PractitionerRole.location`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17317)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17318)| `PractitionerRole.location`| _Equivalent_<br/>(31857/31858)| `PractitionerRole.location`| _Equivalent_<br/>(46473/46474)| `PractitionerRole.location`
| | | **`PractitionerRole.healthcareService`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17319)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17320)| `PractitionerRole.healthcareService`| _Equivalent_<br/>(31859/31860)| `PractitionerRole.healthcareService`| _Equivalent_<br/>(46475/46476)| `PractitionerRole.healthcareService`
| | | **`PractitionerRole.telecom`**| _Equivalent_<br/>(17321/17322)| `PractitionerRole.telecom`| _Equivalent_<br/>(31861/31862)| `PractitionerRole.telecom`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1932)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(46477)| `PractitionerRole.contact`
| | | **`PractitionerRole.availableTime`**| _Equivalent_<br/>(17323/17324)| `PractitionerRole.availableTime`| _Equivalent_<br/>(31863/31864)| `PractitionerRole.availableTime`| | | 
| | | **`PractitionerRole.availableTime.id`**| _Equivalent_<br/>(17325/17326)| `PractitionerRole.availableTime.id`| _Equivalent_<br/>(31865/31866)| `PractitionerRole.availableTime.id`| | | 
| | | **`PractitionerRole.availableTime.extension`**| _Equivalent_<br/>(17327/17328)| `PractitionerRole.availableTime.extension`| _Equivalent_<br/>(31867/31868)| `PractitionerRole.availableTime.extension`| | | 
| | | **`PractitionerRole.availableTime.modifierExtension`**| _Equivalent_<br/>(17329/17330)| `PractitionerRole.availableTime.modifierExtension`| _Equivalent_<br/>(31869/31870)| `PractitionerRole.availableTime.modifierExtension`| | | 
| | | **`PractitionerRole.availableTime.daysOfWeek`**| _Equivalent_<br/>(17331/17332)| `PractitionerRole.availableTime.daysOfWeek`| _Equivalent_<br/>(31871/31872)| `PractitionerRole.availableTime.daysOfWeek`| | | 
| | | **`PractitionerRole.availableTime.allDay`**| _Equivalent_<br/>(17333/17334)| `PractitionerRole.availableTime.allDay`| _Equivalent_<br/>(31873/31874)| `PractitionerRole.availableTime.allDay`| | | 
| | | **`PractitionerRole.availableTime.availableStartTime`**| _Equivalent_<br/>(17335/17336)| `PractitionerRole.availableTime.availableStartTime`| _Equivalent_<br/>(31875/31876)| `PractitionerRole.availableTime.availableStartTime`| | | 
| | | **`PractitionerRole.availableTime.availableEndTime`**| _Equivalent_<br/>(17337/17338)| `PractitionerRole.availableTime.availableEndTime`| _Equivalent_<br/>(31877/31878)| `PractitionerRole.availableTime.availableEndTime`| | | 
| | | **`PractitionerRole.notAvailable`**| _Equivalent_<br/>(17339/17340)| `PractitionerRole.notAvailable`| _Equivalent_<br/>(31879/31880)| `PractitionerRole.notAvailable`| | | 
| | | **`PractitionerRole.notAvailable.id`**| _Equivalent_<br/>(17341/17342)| `PractitionerRole.notAvailable.id`| _Equivalent_<br/>(31881/31882)| `PractitionerRole.notAvailable.id`| | | 
| | | **`PractitionerRole.notAvailable.extension`**| _Equivalent_<br/>(17343/17344)| `PractitionerRole.notAvailable.extension`| _Equivalent_<br/>(31883/31884)| `PractitionerRole.notAvailable.extension`| | | 
| | | **`PractitionerRole.notAvailable.modifierExtension`**| _Equivalent_<br/>(17345/17346)| `PractitionerRole.notAvailable.modifierExtension`| _Equivalent_<br/>(31885/31886)| `PractitionerRole.notAvailable.modifierExtension`| | | 
| | | **`PractitionerRole.notAvailable.description`**| _Equivalent_<br/>(17347/17348)| `PractitionerRole.notAvailable.description`| _Equivalent_<br/>(31887/31888)| `PractitionerRole.notAvailable.description`| | | 
| | | **`PractitionerRole.notAvailable.during`**| _Equivalent_<br/>(17349/17350)| `PractitionerRole.notAvailable.during`| _Equivalent_<br/>(31889/31890)| `PractitionerRole.notAvailable.during`| | | 
| | | **`PractitionerRole.availabilityExceptions`**| _Equivalent_<br/>(17351/17352)| `PractitionerRole.availabilityExceptions`| _Equivalent_<br/>(31891/31892)| `PractitionerRole.availabilityExceptions`| | | 
| | | **`PractitionerRole.endpoint`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17353)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17354)| `PractitionerRole.endpoint`| _Equivalent_<br/>(31893/31894)| `PractitionerRole.endpoint`| _Equivalent_<br/>(46493/46494)| `PractitionerRole.endpoint`
| | | *35 of 35 elements used* | | *35 of 35 elements used* | | *35 of 35 elements used* | | *20 of 23 elements used* <br/>remaining elements:<br/>`PractitionerRole.availability`, `PractitionerRole.characteristic`, `PractitionerRole.communication`

