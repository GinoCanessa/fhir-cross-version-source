Comparison of 
Generated at Friday, April 4, 2025 2:59:03 PM

### OrganizationAffiliation

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | OrganizationAffiliation |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/OrganizationAffiliation` |
| Version | 5.0.0 |
| Description | Defines an affiliation/assotiation/relationship between 2 distinct organizations, that is not a part-of relationship/sub-division relationship. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2356` |
| Database Snapshot Count | `21` |
| Database Differential Count | `13` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `OrganizationAffiliation` | `OrganizationAffiliation` | `OrganizationAffiliation` | OrganizationAffiliation | Defines an affiliation/association/relationship between 2 distinct organizations, that is not a part-of relationship/sub-division relationship | 0..* | OrganizationAffiliation |  |  |
| `OrganizationAffiliation.active` | `OrganizationAffiliation.active` | `active` | OrganizationAffiliation.active | Whether this organization affiliation record is in active use | 0..1 | boolean |  |  |
| `OrganizationAffiliation.code` | `OrganizationAffiliation.code` | `code` | OrganizationAffiliation.code | Definition of the role the participatingOrganization plays | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/organization-role` |
| `OrganizationAffiliation.contact` | `OrganizationAffiliation.contact` | `contact` | OrganizationAffiliation.contact | Official contact details at the participatingOrganization relevant to this Affiliation | 0..* | ExtendedContactDetail |  |  |
| `OrganizationAffiliation.contained` | `OrganizationAffiliation.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `OrganizationAffiliation.endpoint` | `OrganizationAffiliation.endpoint` | `endpoint` | OrganizationAffiliation.endpoint | Technical endpoints providing access to services operated for this role | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Endpoint) |  |  |
| `OrganizationAffiliation.extension` | `OrganizationAffiliation.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `OrganizationAffiliation.healthcareService` | `OrganizationAffiliation.healthcareService` | `healthcareService` | OrganizationAffiliation.healthcareService | Healthcare services provided through the role | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService) |  |  |
| `OrganizationAffiliation.id` | `OrganizationAffiliation.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `OrganizationAffiliation.identifier` | `OrganizationAffiliation.identifier` | `identifier` | OrganizationAffiliation.identifier | Business identifiers that are specific to this role | 0..* | Identifier |  |  |
| `OrganizationAffiliation.implicitRules` | `OrganizationAffiliation.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `OrganizationAffiliation.language` | `OrganizationAffiliation.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `OrganizationAffiliation.location` | `OrganizationAffiliation.location` | `location` | OrganizationAffiliation.location | The location(s) at which the role occurs | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `OrganizationAffiliation.meta` | `OrganizationAffiliation.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `OrganizationAffiliation.modifierExtension` | `OrganizationAffiliation.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `OrganizationAffiliation.network` | `OrganizationAffiliation.network` | `network` | OrganizationAffiliation.network | The network in which the participatingOrganization provides the role's services (if defined) at the indicated locations (if defined) | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `OrganizationAffiliation.organization` | `OrganizationAffiliation.organization` | `organization` | OrganizationAffiliation.organization | Organization where the role is available | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `OrganizationAffiliation.participatingOrganization` | `OrganizationAffiliation.participatingOrganization` | `participatingOrganization` | OrganizationAffiliation.participatingOrganization | Organization that provides/performs the role (e.g. providing services or is a member of) | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `OrganizationAffiliation.period` | `OrganizationAffiliation.period` | `period` | OrganizationAffiliation.period | The period during which the participatingOrganization is affiliated with the primary organization | 0..1 | Period |  |  |
| `OrganizationAffiliation.specialty` | `OrganizationAffiliation.specialty` | `specialty` | OrganizationAffiliation.specialty | Specific specialty of the participatingOrganization in the context of the role | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` |
| `OrganizationAffiliation.text` | `OrganizationAffiliation.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [OrganizationAffiliation](/docs/R4/Resources/OrganizationAffiliation.md)<br/> `http://hl7.org/fhir/StructureDefinition/OrganizationAffiliation\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1567`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1568`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [OrganizationAffiliation](/docs/R4B/Resources/OrganizationAffiliation.md)<br/> `http://hl7.org/fhir/StructureDefinition/OrganizationAffiliation\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1019`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1248`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [OrganizationAffiliation](/docs/R5/Resources/OrganizationAffiliation.md)<br/> `http://hl7.org/fhir/StructureDefinition/OrganizationAffiliation\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition OrganizationAffiliation from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 OrganizationAffiliation](/docs/R4/Resources/OrganizationAffiliation.md)| Relationship | [R4B OrganizationAffiliation](/docs/R4B/Resources/OrganizationAffiliation.md)| Relationship | R5 OrganizationAffiliation
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `OrganizationAffiliation`| _Equivalent_<br/>(31198/31199)| `OrganizationAffiliation`| _Equivalent_<br/>(45805/45806)| **`OrganizationAffiliation`**
| | | | | `OrganizationAffiliation.id`| _Equivalent_<br/>(31200/31201)| `OrganizationAffiliation.id`| _Equivalent_<br/>(45807/45808)| **`OrganizationAffiliation.id`**
| | | | | `OrganizationAffiliation.meta`| _Equivalent_<br/>(31202/31203)| `OrganizationAffiliation.meta`| _Equivalent_<br/>(45809/45810)| **`OrganizationAffiliation.meta`**
| | | | | `OrganizationAffiliation.implicitRules`| _Equivalent_<br/>(31204/31205)| `OrganizationAffiliation.implicitRules`| _Equivalent_<br/>(45811/45812)| **`OrganizationAffiliation.implicitRules`**
| | | | | `OrganizationAffiliation.language`| _Equivalent_<br/>(31206/31207)| `OrganizationAffiliation.language`| _Equivalent_<br/>(45813/45814)| **`OrganizationAffiliation.language`**
| | | | | `OrganizationAffiliation.text`| _Equivalent_<br/>(31208/31209)| `OrganizationAffiliation.text`| _Equivalent_<br/>(45815/45816)| **`OrganizationAffiliation.text`**
| | | | | `OrganizationAffiliation.contained`| _Equivalent_<br/>(31210/31211)| `OrganizationAffiliation.contained`| _Equivalent_<br/>(45817/45818)| **`OrganizationAffiliation.contained`**
| | | | | `OrganizationAffiliation.extension`| _Equivalent_<br/>(31212/31213)| `OrganizationAffiliation.extension`| _Equivalent_<br/>(45819/45820)| **`OrganizationAffiliation.extension`**
| | | | | `OrganizationAffiliation.modifierExtension`| _Equivalent_<br/>(31214/31215)| `OrganizationAffiliation.modifierExtension`| _Equivalent_<br/>(45821/45822)| **`OrganizationAffiliation.modifierExtension`**
| | | | | `OrganizationAffiliation.identifier`| _Equivalent_<br/>(31216/31217)| `OrganizationAffiliation.identifier`| _Equivalent_<br/>(45823/45824)| **`OrganizationAffiliation.identifier`**
| | | | | `OrganizationAffiliation.active`| _Equivalent_<br/>(31218/31219)| `OrganizationAffiliation.active`| _Equivalent_<br/>(45825/45826)| **`OrganizationAffiliation.active`**
| | | | | `OrganizationAffiliation.period`| _Equivalent_<br/>(31220/31221)| `OrganizationAffiliation.period`| _Equivalent_<br/>(45827/45828)| **`OrganizationAffiliation.period`**
| | | | | `OrganizationAffiliation.organization`| _Equivalent_<br/>(31222/31223)| `OrganizationAffiliation.organization`| _Equivalent_<br/>(45829/45830)| **`OrganizationAffiliation.organization`**
| | | | | `OrganizationAffiliation.participatingOrganization`| _Equivalent_<br/>(31224/31225)| `OrganizationAffiliation.participatingOrganization`| _Equivalent_<br/>(45831/45832)| **`OrganizationAffiliation.participatingOrganization`**
| | | | | `OrganizationAffiliation.network`| _Equivalent_<br/>(31226/31227)| `OrganizationAffiliation.network`| _Equivalent_<br/>(45833/45834)| **`OrganizationAffiliation.network`**
| | | | | `OrganizationAffiliation.code`| _Equivalent_<br/>(31228/31229)| `OrganizationAffiliation.code`| _Equivalent_<br/>(45835/45836)| **`OrganizationAffiliation.code`**
| | | | | `OrganizationAffiliation.specialty`| _Equivalent_<br/>(31230/31231)| `OrganizationAffiliation.specialty`| _Equivalent_<br/>(45837/45838)| **`OrganizationAffiliation.specialty`**
| | | | | `OrganizationAffiliation.location`| _Equivalent_<br/>(31232/31233)| `OrganizationAffiliation.location`| _Equivalent_<br/>(45839/45840)| **`OrganizationAffiliation.location`**
| | | | | `OrganizationAffiliation.healthcareService`| _Equivalent_<br/>(31234/31235)| `OrganizationAffiliation.healthcareService`| _Equivalent_<br/>(45841/45842)| **`OrganizationAffiliation.healthcareService`**
| | | | | `OrganizationAffiliation.telecom`| _Equivalent_<br/>(31236/31237)| `OrganizationAffiliation.telecom`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1906)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45843)| **`OrganizationAffiliation.contact`**
| | | | | `OrganizationAffiliation.endpoint`| _Equivalent_<br/>(31238/31239)| `OrganizationAffiliation.endpoint`| _Equivalent_<br/>(45844/45845)| **`OrganizationAffiliation.endpoint`**
| | | | | *21 of 21 elements used* | | *21 of 21 elements used* | | *21 of 21 elements used* 

