Comparison of 
Generated at Monday, April 14, 2025 6:17:16 PM

### Location

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Location |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Location` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Location Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `92` |
| Database Snapshot Count | `27` |
| Database Differential Count | `16` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Location` | `Location` | `Location` | Location | Details and position information for a physical place | 0..* | Location |  |  |
| `Location.address` | `Location.address` | `address` |  | Physical location | 0..1 | Address |  |  |
| `Location.contained` | `Location.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Location.description` | `Location.description` | `description` |  | Description of the location | 0..1 | string |  |  |
| `Location.extension` | `Location.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Location.id` | `Location.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Location.identifier` | `Location.identifier` | `identifier` |  | Unique code or number identifying the location to its users | 0..* | Identifier |  |  |
| `Location.implicitRules` | `Location.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Location.language` | `Location.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Location.managingOrganization` | `Location.managingOrganization` | `managingOrganization` |  | Organization responsible for provisioning and upkeep | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Location.meta` | `Location.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Location.mode` | `Location.mode` | `mode` |  | instance \| kind | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/location-mode` |
| `Location.modifierExtension` | `Location.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Location.name` | `Location.name` | `name` |  | Name of the location as used by humans | 0..1 | string |  |  |
| `Location.partOf` | `Location.partOf` | `partOf` |  | Another Location this one is physically part of | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `Location.physicalType` | `Location.physicalType` | `physicalType` |  | Physical form of the location | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/location-physical-type` |
| `Location.position` | `Location.position` | `position` |  | The absolute geographic location | 0..1 | BackboneElement |  |  |
| `Location.position.altitude` | `Location.position.altitude` | `altitude` |  | Altitude with WGS84 datum | 0..1 | decimal |  |  |
| `Location.position.extension` | `Location.position.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Location.position.id` | `Location.position.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Location.position.latitude` | `Location.position.latitude` | `latitude` |  | Latitude with WGS84 datum | 1..1 | decimal |  |  |
| `Location.position.longitude` | `Location.position.longitude` | `longitude` |  | Longitude with WGS84 datum | 1..1 | decimal |  |  |
| `Location.position.modifierExtension` | `Location.position.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Location.status` | `Location.status` | `status` |  | active \| suspended \| inactive | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/location-status` |
| `Location.telecom` | `Location.telecom` | `telecom` |  | Contact details of the location | 0..* | ContactPoint |  |  |
| `Location.text` | `Location.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Location.type` | `Location.type` | `type` |  | Type of function performed | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/v3-ServiceDeliveryLocationRoleType` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Location](/docs/R2/Resources/Location.md)<br/> `http://hl7.org/fhir/StructureDefinition/Location\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `122`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `288`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Location](/docs/R3/Resources/Location.md)<br/> `http://hl7.org/fhir/StructureDefinition/Location\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `475`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `669`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Location](/docs/R4/Resources/Location.md)<br/> `http://hl7.org/fhir/StructureDefinition/Location\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1527`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1528`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Location](/docs/R4B/Resources/Location.md)<br/> `http://hl7.org/fhir/StructureDefinition/Location\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `998`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1227`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Location](/docs/R5/Resources/Location.md)<br/> `http://hl7.org/fhir/StructureDefinition/Location\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Location from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Location| Relationship | [R3 Location](/docs/R3/Resources/Location.md)| Relationship | [R4 Location](/docs/R4/Resources/Location.md)| Relationship | [R4B Location](/docs/R4B/Resources/Location.md)| Relationship | [R5 Location](/docs/R5/Resources/Location.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Location`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5995)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5996)| `Location`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15340)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15341)| `Location`| _Equivalent_<br/>(28984/28985)| `Location`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(43846)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(43847)| `Location`
| **`Location.id`**| _Equivalent_<br/>(5997/5998)| `Location.id`| _Equivalent_<br/>(15342/15343)| `Location.id`| _Equivalent_<br/>(28986/28987)| `Location.id`| _Equivalent_<br/>(43848/43849)| `Location.id`
| **`Location.meta`**| _Equivalent_<br/>(5999/6000)| `Location.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15344)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15345)| `Location.meta`| _Equivalent_<br/>(28988/28989)| `Location.meta`| _Equivalent_<br/>(43850/43851)| `Location.meta`
| **`Location.implicitRules`**| _Equivalent_<br/>(6001/6002)| `Location.implicitRules`| _Equivalent_<br/>(15346/15347)| `Location.implicitRules`| _Equivalent_<br/>(28990/28991)| `Location.implicitRules`| _Equivalent_<br/>(43852/43853)| `Location.implicitRules`
| **`Location.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6003)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6004)| `Location.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15348)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(15349)| `Location.language`| _Equivalent_<br/>(28992/28993)| `Location.language`| _Equivalent_<br/>(43854/43855)| `Location.language`
| **`Location.text`**| _Equivalent_<br/>(6005/6006)| `Location.text`| _Equivalent_<br/>(15350/15351)| `Location.text`| _Equivalent_<br/>(28994/28995)| `Location.text`| _Equivalent_<br/>(43856/43857)| `Location.text`
| **`Location.contained`**| _Equivalent_<br/>(6007/6008)| `Location.contained`| _Equivalent_<br/>(15352/15353)| `Location.contained`| _Equivalent_<br/>(28996/28997)| `Location.contained`| _Equivalent_<br/>(43858/43859)| `Location.contained`
| **`Location.extension`**| _Equivalent_<br/>(6009/6010)| `Location.extension`| _Equivalent_<br/>(15354/15355)| `Location.extension`| _Equivalent_<br/>(28998/28999)| `Location.extension`| _Equivalent_<br/>(43860/43861)| `Location.extension`
| **`Location.modifierExtension`**| _Equivalent_<br/>(6011/6012)| `Location.modifierExtension`| _Equivalent_<br/>(15356/15357)| `Location.modifierExtension`| _Equivalent_<br/>(29000/29001)| `Location.modifierExtension`| _Equivalent_<br/>(43862/43863)| `Location.modifierExtension`
| **`Location.identifier`**| _Equivalent_<br/>(6013/6014)| `Location.identifier`| _Equivalent_<br/>(15358/15359)| `Location.identifier`| _Equivalent_<br/>(29002/29003)| `Location.identifier`| _Equivalent_<br/>(43864/43865)| `Location.identifier`
| **`Location.status`**| _Equivalent_<br/>(6015/6016)| `Location.status`| _Equivalent_<br/>(15360/15361)| `Location.status`| _Equivalent_<br/>(29004/29005)| `Location.status`| _Equivalent_<br/>(43866/43867)| `Location.status`
| **`Location.name`**| _Equivalent_<br/>(6017/6018)| `Location.name`| _Equivalent_<br/>(15364/15365)| `Location.name`| _Equivalent_<br/>(29008/29009)| `Location.name`| _Equivalent_<br/>(43870/43871)| `Location.name`
| **`Location.description`**| _Equivalent_<br/>(6019/6020)| `Location.description`| _Equivalent_<br/>(15368/15369)| `Location.description`| _Equivalent_<br/>(29012/29013)| `Location.description`| _Equivalent_<br/>(43874/43875)| `Location.description`
| **`Location.mode`**| _Equivalent_<br/>(6021/6022)| `Location.mode`| _Equivalent_<br/>(15370/15371)| `Location.mode`| _Equivalent_<br/>(29014/29015)| `Location.mode`| _Equivalent_<br/>(43876/43877)| `Location.mode`
| **`Location.type`**| _Equivalent_<br/>(6023/6024)| `Location.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15372)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15373)| `Location.type`| _Equivalent_<br/>(29016/29017)| `Location.type`| _Equivalent_<br/>(43878/43879)| `Location.type`
| **`Location.telecom`**| _Equivalent_<br/>(6025/6026)| `Location.telecom`| _Equivalent_<br/>(15374/15375)| `Location.telecom`| _Equivalent_<br/>(29018/29019)| `Location.telecom`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1814)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43880)| `Location.contact`
| **`Location.address`**| _Equivalent_<br/>(6027/6028)| `Location.address`| _Equivalent_<br/>(15376/15377)| `Location.address`| _Equivalent_<br/>(29020/29021)| `Location.address`| _Equivalent_<br/>(43881/43882)| `Location.address`
| **`Location.physicalType`**| _Equivalent_<br/>(6029/6030)| `Location.physicalType`| _Equivalent_<br/>(15378/15379)| `Location.physicalType`| _Equivalent_<br/>(29022/29023)| `Location.physicalType`| _Equivalent_<br/>(1813/2057)| `Location.form`
| **`Location.position`**| _Equivalent_<br/>(6031/6032)| `Location.position`| _Equivalent_<br/>(15380/15381)| `Location.position`| _Equivalent_<br/>(29024/29025)| `Location.position`| _Equivalent_<br/>(43883/43884)| `Location.position`
| **`Location.position.id`**| _Equivalent_<br/>(6033/6034)| `Location.position.id`| _Equivalent_<br/>(15382/15383)| `Location.position.id`| _Equivalent_<br/>(29026/29027)| `Location.position.id`| _Equivalent_<br/>(43885/43886)| `Location.position.id`
| **`Location.position.extension`**| _Equivalent_<br/>(6035/6036)| `Location.position.extension`| _Equivalent_<br/>(15384/15385)| `Location.position.extension`| _Equivalent_<br/>(29028/29029)| `Location.position.extension`| _Equivalent_<br/>(43887/43888)| `Location.position.extension`
| **`Location.position.modifierExtension`**| _Equivalent_<br/>(6037/6038)| `Location.position.modifierExtension`| _Equivalent_<br/>(15386/15387)| `Location.position.modifierExtension`| _Equivalent_<br/>(29030/29031)| `Location.position.modifierExtension`| _Equivalent_<br/>(43889/43890)| `Location.position.modifierExtension`
| **`Location.position.longitude`**| _Equivalent_<br/>(6039/6040)| `Location.position.longitude`| _Equivalent_<br/>(15388/15389)| `Location.position.longitude`| _Equivalent_<br/>(29032/29033)| `Location.position.longitude`| _Equivalent_<br/>(43891/43892)| `Location.position.longitude`
| **`Location.position.latitude`**| _Equivalent_<br/>(6041/6042)| `Location.position.latitude`| _Equivalent_<br/>(15390/15391)| `Location.position.latitude`| _Equivalent_<br/>(29034/29035)| `Location.position.latitude`| _Equivalent_<br/>(43893/43894)| `Location.position.latitude`
| **`Location.position.altitude`**| _Equivalent_<br/>(6043/6044)| `Location.position.altitude`| _Equivalent_<br/>(15392/15393)| `Location.position.altitude`| _Equivalent_<br/>(29036/29037)| `Location.position.altitude`| _Equivalent_<br/>(43895/43896)| `Location.position.altitude`
| **`Location.managingOrganization`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6045)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6046)| `Location.managingOrganization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15394)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15395)| `Location.managingOrganization`| _Equivalent_<br/>(29038/29039)| `Location.managingOrganization`| _Equivalent_<br/>(43897/43898)| `Location.managingOrganization`
| **`Location.partOf`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6047)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6048)| `Location.partOf`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15396)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15397)| `Location.partOf`| _Equivalent_<br/>(29040/29041)| `Location.partOf`| _Equivalent_<br/>(43899/43900)| `Location.partOf`
| *27 of 27 elements used* | | *27 of 30 elements used* <br/>remaining elements:<br/>`Location.alias`, `Location.endpoint`, `Location.operationalStatus`| | *27 of 39 elements used* <br/>remaining elements:<br/>`Location.alias`, `Location.availabilityExceptions`, `Location.endpoint`, `Location.hoursOfOperation`, `Location.hoursOfOperation.allDay`, `Location.hoursOfOperation.closingTime`, `Location.hoursOfOperation.daysOfWeek`, `Location.hoursOfOperation.extension`, `Location.hoursOfOperation.id`, `Location.hoursOfOperation.modifierExtension`, `Location.hoursOfOperation.openingTime`, `Location.operationalStatus`| | *27 of 39 elements used* <br/>remaining elements:<br/>`Location.alias`, `Location.availabilityExceptions`, `Location.endpoint`, `Location.hoursOfOperation`, `Location.hoursOfOperation.allDay`, `Location.hoursOfOperation.closingTime`, `Location.hoursOfOperation.daysOfWeek`, `Location.hoursOfOperation.extension`, `Location.hoursOfOperation.id`, `Location.hoursOfOperation.modifierExtension`, `Location.hoursOfOperation.openingTime`, `Location.operationalStatus`| | *27 of 33 elements used* <br/>remaining elements:<br/>`Location.alias`, `Location.characteristic`, `Location.endpoint`, `Location.hoursOfOperation`, `Location.operationalStatus`, `Location.virtualService`

