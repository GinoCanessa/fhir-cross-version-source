Comparison of 
Generated at Monday, April 14, 2025 6:17:49 PM

### PractitionerRole

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | PractitionerRole |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/PractitionerRole` |
| Version | 5.0.0 |
| Description | A specific set of Roles/Locations/specialties/services that a practitioner may perform, or has performed at an organization during a period of time. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2366` |
| Database Snapshot Count | `23` |
| Database Differential Count | `15` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `PractitionerRole` | `PractitionerRole` | `PractitionerRole` | PractitionerRole | Roles/organizations the practitioner is associated with | 0..* | PractitionerRole |  |  |
| `PractitionerRole.active` | `PractitionerRole.active` | `active` | PractitionerRole.active | Whether this practitioner role record is in active use | 0..1 | boolean |  |  |
| `PractitionerRole.availability` | `PractitionerRole.availability` | `availability` | PractitionerRole.availability | Times the Practitioner is available at this location and/or healthcare service (including exceptions) | 0..* | Availability |  |  |
| `PractitionerRole.characteristic` | `PractitionerRole.characteristic` | `characteristic` | PractitionerRole.characteristic | Collection of characteristics (attributes) | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/service-mode` |
| `PractitionerRole.code` | `PractitionerRole.code` | `code` | PractitionerRole.code | Roles which this practitioner may perform | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/practitioner-role` |
| `PractitionerRole.communication` | `PractitionerRole.communication` | `communication` | PractitionerRole.communication | A language the practitioner (in this role) can use in patient communication | 0..* | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `PractitionerRole.contact` | `PractitionerRole.contact` | `contact` | PractitionerRole.contact | Official contact details relating to this PractitionerRole | 0..* | ExtendedContactDetail |  |  |
| `PractitionerRole.contained` | `PractitionerRole.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `PractitionerRole.endpoint` | `PractitionerRole.endpoint` | `endpoint` | PractitionerRole.endpoint | Endpoints for interacting with the practitioner in this role | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Endpoint) |  |  |
| `PractitionerRole.extension` | `PractitionerRole.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `PractitionerRole.healthcareService` | `PractitionerRole.healthcareService` | `healthcareService` | PractitionerRole.healthcareService | Healthcare services provided for this role's Organization/Location(s) | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService) |  |  |
| `PractitionerRole.id` | `PractitionerRole.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `PractitionerRole.identifier` | `PractitionerRole.identifier` | `identifier` | PractitionerRole.identifier | Identifiers for a role/location | 0..* | Identifier |  |  |
| `PractitionerRole.implicitRules` | `PractitionerRole.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `PractitionerRole.language` | `PractitionerRole.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `PractitionerRole.location` | `PractitionerRole.location` | `location` | PractitionerRole.location | Location(s) where the practitioner provides care | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `PractitionerRole.meta` | `PractitionerRole.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `PractitionerRole.modifierExtension` | `PractitionerRole.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `PractitionerRole.organization` | `PractitionerRole.organization` | `organization` | PractitionerRole.organization | Organization where the roles are available | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `PractitionerRole.period` | `PractitionerRole.period` | `period` | PractitionerRole.period | The period during which the practitioner is authorized to perform in these role(s) | 0..1 | Period |  |  |
| `PractitionerRole.practitioner` | `PractitionerRole.practitioner` | `practitioner` | PractitionerRole.practitioner | Practitioner that provides services for the organization | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `PractitionerRole.specialty` | `PractitionerRole.specialty` | `specialty` | PractitionerRole.specialty | Specific specialty of the practitioner | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` |
| `PractitionerRole.text` | `PractitionerRole.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [PractitionerRole](/docs/R3/Resources/PractitionerRole.md)<br/> `http://hl7.org/fhir/StructureDefinition/PractitionerRole\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `500`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `695`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [PractitionerRole](/docs/R4/Resources/PractitionerRole.md)<br/> `http://hl7.org/fhir/StructureDefinition/PractitionerRole\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1583`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1584`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [PractitionerRole](/docs/R4B/Resources/PractitionerRole.md)<br/> `http://hl7.org/fhir/StructureDefinition/PractitionerRole\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1027`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1256`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [PractitionerRole](/docs/R5/Resources/PractitionerRole.md)<br/> `http://hl7.org/fhir/StructureDefinition/PractitionerRole\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition PractitionerRole from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 PractitionerRole](/docs/R3/Resources/PractitionerRole.md)| Relationship | [R4 PractitionerRole](/docs/R4/Resources/PractitionerRole.md)| Relationship | [R4B PractitionerRole](/docs/R4B/Resources/PractitionerRole.md)| Relationship | R5 PractitionerRole
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `PractitionerRole`| _Equivalent_<br/>(17285/17286)| `PractitionerRole`| _Equivalent_<br/>(31825/31826)| `PractitionerRole`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(46441)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(46442)| **`PractitionerRole`**
| | | `PractitionerRole.id`| _Equivalent_<br/>(17287/17288)| `PractitionerRole.id`| _Equivalent_<br/>(31827/31828)| `PractitionerRole.id`| _Equivalent_<br/>(46443/46444)| **`PractitionerRole.id`**
| | | `PractitionerRole.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17289)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17290)| `PractitionerRole.meta`| _Equivalent_<br/>(31829/31830)| `PractitionerRole.meta`| _Equivalent_<br/>(46445/46446)| **`PractitionerRole.meta`**
| | | `PractitionerRole.implicitRules`| _Equivalent_<br/>(17291/17292)| `PractitionerRole.implicitRules`| _Equivalent_<br/>(31831/31832)| `PractitionerRole.implicitRules`| _Equivalent_<br/>(46447/46448)| **`PractitionerRole.implicitRules`**
| | | `PractitionerRole.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17293)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(17294)| `PractitionerRole.language`| _Equivalent_<br/>(31833/31834)| `PractitionerRole.language`| _Equivalent_<br/>(46449/46450)| **`PractitionerRole.language`**
| | | `PractitionerRole.text`| _Equivalent_<br/>(17295/17296)| `PractitionerRole.text`| _Equivalent_<br/>(31835/31836)| `PractitionerRole.text`| _Equivalent_<br/>(46451/46452)| **`PractitionerRole.text`**
| | | `PractitionerRole.contained`| _Equivalent_<br/>(17297/17298)| `PractitionerRole.contained`| _Equivalent_<br/>(31837/31838)| `PractitionerRole.contained`| _Equivalent_<br/>(46453/46454)| **`PractitionerRole.contained`**
| | | `PractitionerRole.extension`| _Equivalent_<br/>(17299/17300)| `PractitionerRole.extension`| _Equivalent_<br/>(31839/31840)| `PractitionerRole.extension`| _Equivalent_<br/>(46455/46456)| **`PractitionerRole.extension`**
| | | `PractitionerRole.modifierExtension`| _Equivalent_<br/>(17301/17302)| `PractitionerRole.modifierExtension`| _Equivalent_<br/>(31841/31842)| `PractitionerRole.modifierExtension`| _Equivalent_<br/>(46457/46458)| **`PractitionerRole.modifierExtension`**
| | | `PractitionerRole.identifier`| _Equivalent_<br/>(17303/17304)| `PractitionerRole.identifier`| _Equivalent_<br/>(31843/31844)| `PractitionerRole.identifier`| _Equivalent_<br/>(46459/46460)| **`PractitionerRole.identifier`**
| | | `PractitionerRole.active`| _Equivalent_<br/>(17305/17306)| `PractitionerRole.active`| _Equivalent_<br/>(31845/31846)| `PractitionerRole.active`| _Equivalent_<br/>(46461/46462)| **`PractitionerRole.active`**
| | | `PractitionerRole.period`| _Equivalent_<br/>(17307/17308)| `PractitionerRole.period`| _Equivalent_<br/>(31847/31848)| `PractitionerRole.period`| _Equivalent_<br/>(46463/46464)| **`PractitionerRole.period`**
| | | `PractitionerRole.practitioner`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17309)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17310)| `PractitionerRole.practitioner`| _Equivalent_<br/>(31849/31850)| `PractitionerRole.practitioner`| _Equivalent_<br/>(46465/46466)| **`PractitionerRole.practitioner`**
| | | `PractitionerRole.organization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17311)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17312)| `PractitionerRole.organization`| _Equivalent_<br/>(31851/31852)| `PractitionerRole.organization`| _Equivalent_<br/>(46467/46468)| **`PractitionerRole.organization`**
| | | `PractitionerRole.code`| _Equivalent_<br/>(17313/17314)| `PractitionerRole.code`| _Equivalent_<br/>(31853/31854)| `PractitionerRole.code`| _Equivalent_<br/>(46469/46470)| **`PractitionerRole.code`**
| | | `PractitionerRole.specialty`| _Equivalent_<br/>(17315/17316)| `PractitionerRole.specialty`| _Equivalent_<br/>(31855/31856)| `PractitionerRole.specialty`| _Equivalent_<br/>(46471/46472)| **`PractitionerRole.specialty`**
| | | `PractitionerRole.location`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17317)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17318)| `PractitionerRole.location`| _Equivalent_<br/>(31857/31858)| `PractitionerRole.location`| _Equivalent_<br/>(46473/46474)| **`PractitionerRole.location`**
| | | `PractitionerRole.healthcareService`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17319)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17320)| `PractitionerRole.healthcareService`| _Equivalent_<br/>(31859/31860)| `PractitionerRole.healthcareService`| _Equivalent_<br/>(46475/46476)| **`PractitionerRole.healthcareService`**
| | | `PractitionerRole.telecom`| _Equivalent_<br/>(17321/17322)| `PractitionerRole.telecom`| _Equivalent_<br/>(31861/31862)| `PractitionerRole.telecom`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1932)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(46477)| **`PractitionerRole.contact`**
| | | | | | | | | **`PractitionerRole.characteristic`**
| | | | | | | | | **`PractitionerRole.communication`**
| | | | | | | | | **`PractitionerRole.availability`**
| | | `PractitionerRole.endpoint`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17353)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17354)| `PractitionerRole.endpoint`| _Equivalent_<br/>(31893/31894)| `PractitionerRole.endpoint`| _Equivalent_<br/>(46493/46494)| **`PractitionerRole.endpoint`**
| | | *20 of 35 elements used* <br/>remaining elements:<br/>`PractitionerRole.availabilityExceptions`, `PractitionerRole.availableTime`, `PractitionerRole.availableTime.allDay`, `PractitionerRole.availableTime.availableEndTime`, `PractitionerRole.availableTime.availableStartTime`, `PractitionerRole.availableTime.daysOfWeek`, `PractitionerRole.availableTime.extension`, `PractitionerRole.availableTime.id`, `PractitionerRole.availableTime.modifierExtension`, `PractitionerRole.notAvailable`, `PractitionerRole.notAvailable.description`, `PractitionerRole.notAvailable.during`, `PractitionerRole.notAvailable.extension`, `PractitionerRole.notAvailable.id`, `PractitionerRole.notAvailable.modifierExtension`| | *20 of 35 elements used* <br/>remaining elements:<br/>`PractitionerRole.availabilityExceptions`, `PractitionerRole.availableTime`, `PractitionerRole.availableTime.allDay`, `PractitionerRole.availableTime.availableEndTime`, `PractitionerRole.availableTime.availableStartTime`, `PractitionerRole.availableTime.daysOfWeek`, `PractitionerRole.availableTime.extension`, `PractitionerRole.availableTime.id`, `PractitionerRole.availableTime.modifierExtension`, `PractitionerRole.notAvailable`, `PractitionerRole.notAvailable.description`, `PractitionerRole.notAvailable.during`, `PractitionerRole.notAvailable.extension`, `PractitionerRole.notAvailable.id`, `PractitionerRole.notAvailable.modifierExtension`| | *20 of 35 elements used* <br/>remaining elements:<br/>`PractitionerRole.availabilityExceptions`, `PractitionerRole.availableTime`, `PractitionerRole.availableTime.allDay`, `PractitionerRole.availableTime.availableEndTime`, `PractitionerRole.availableTime.availableStartTime`, `PractitionerRole.availableTime.daysOfWeek`, `PractitionerRole.availableTime.extension`, `PractitionerRole.availableTime.id`, `PractitionerRole.availableTime.modifierExtension`, `PractitionerRole.notAvailable`, `PractitionerRole.notAvailable.description`, `PractitionerRole.notAvailable.during`, `PractitionerRole.notAvailable.extension`, `PractitionerRole.notAvailable.id`, `PractitionerRole.notAvailable.modifierExtension`| | *23 of 23 elements used* 

