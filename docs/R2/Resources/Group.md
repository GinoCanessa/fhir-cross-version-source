Comparison of 
Generated at Thursday, April 3, 2025 8:18:07 AM

### Group

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Group |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Group` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Group Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `84` |
| Database Snapshot Count | `30` |
| Database Differential Count | `16` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Group` | `Group` | `Group` | Group | Group of multiple entities | 0..* | Group |  |  |
| `Group.actual` | `Group.actual` | `actual` |  | Descriptive or actual | 1..1 | boolean |  |  |
| `Group.characteristic` | `Group.characteristic` | `characteristic` |  | Trait of group members | 0..* | BackboneElement |  |  |
| `Group.characteristic.code` | `Group.characteristic.code` | `code` |  | Kind of characteristic | 1..1 | CodeableConcept | `Example` |  |
| `Group.characteristic.exclude` | `Group.characteristic.exclude` | `exclude` |  | Group includes or excludes | 1..1 | boolean |  |  |
| `Group.characteristic.extension` | `Group.characteristic.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Group.characteristic.id` | `Group.characteristic.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Group.characteristic.modifierExtension` | `Group.characteristic.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Group.characteristic.period` | `Group.characteristic.period` | `period` |  | Period over which characteristic is tested | 0..1 | Period |  |  |
| `Group.characteristic.value[x]` | `Group.characteristic.value[x]` | `value[x]` |  | Value held by characteristic | 1..1 | boolean, CodeableConcept, Quantity, Range | `Example` |  |
| `Group.code` | `Group.code` | `code` |  | Kind of Group members | 0..1 | CodeableConcept | `Example` |  |
| `Group.contained` | `Group.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Group.extension` | `Group.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Group.id` | `Group.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Group.identifier` | `Group.identifier` | `identifier` |  | Unique id | 0..* | Identifier |  |  |
| `Group.implicitRules` | `Group.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Group.language` | `Group.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Group.member` | `Group.member` | `member` |  | Who or what is in group | 0..* | BackboneElement |  |  |
| `Group.member.entity` | `Group.member.entity` | `entity` |  | Reference to the group member | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `Group.member.extension` | `Group.member.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Group.member.id` | `Group.member.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Group.member.inactive` | `Group.member.inactive` | `inactive` |  | If member is no longer in group | 0..1 | boolean |  |  |
| `Group.member.modifierExtension` | `Group.member.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Group.member.period` | `Group.member.period` | `period` |  | Period member belonged to the group | 0..1 | Period |  |  |
| `Group.meta` | `Group.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Group.modifierExtension` | `Group.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Group.name` | `Group.name` | `name` |  | Label for Group | 0..1 | string |  |  |
| `Group.quantity` | `Group.quantity` | `quantity` |  | Number of members | 0..1 | unsignedInt |  |  |
| `Group.text` | `Group.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Group.type` | `Group.type` | `type` |  | person \| animal \| practitioner \| device \| medication \| substance | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/group-type` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Group](/docs/R2/Resources/Group.md)<br/> `http://hl7.org/fhir/StructureDefinition/Group\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `114`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `280`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Group](/docs/R3/Resources/Group.md)<br/> `http://hl7.org/fhir/StructureDefinition/Group\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `465`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `659`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Group](/docs/R4/Resources/Group.md)<br/> `http://hl7.org/fhir/StructureDefinition/Group\|4.0.1` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1501`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1502`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Group](/docs/R4B/Resources/Group.md)<br/> `http://hl7.org/fhir/StructureDefinition/Group\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `984`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1213`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Group](/docs/R5/Resources/Group.md)<br/> `http://hl7.org/fhir/StructureDefinition/Group\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Group from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Group| Relationship | [R3 Group](/docs/R3/Resources/Group.md)| Relationship | [R4 Group](/docs/R4/Resources/Group.md)| Relationship | [R4B Group](/docs/R4B/Resources/Group.md)| Relationship | [R5 Group](/docs/R5/Resources/Group.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Group`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5384)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5385)| `Group`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14659)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14660)| `Group`| _Equivalent_<br/>(27691/27692)| `Group`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(42656)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(42657)| `Group`
| **`Group.id`**| _Equivalent_<br/>(5386/5387)| `Group.id`| _Equivalent_<br/>(14661/14662)| `Group.id`| _Equivalent_<br/>(27693/27694)| `Group.id`| _Equivalent_<br/>(42658/42659)| `Group.id`
| **`Group.meta`**| _Equivalent_<br/>(5388/5389)| `Group.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14663)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14664)| `Group.meta`| _Equivalent_<br/>(27695/27696)| `Group.meta`| _Equivalent_<br/>(42660/42661)| `Group.meta`
| **`Group.implicitRules`**| _Equivalent_<br/>(5390/5391)| `Group.implicitRules`| _Equivalent_<br/>(14665/14666)| `Group.implicitRules`| _Equivalent_<br/>(27697/27698)| `Group.implicitRules`| _Equivalent_<br/>(42662/42663)| `Group.implicitRules`
| **`Group.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5392)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(5393)| `Group.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14667)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(14668)| `Group.language`| _Equivalent_<br/>(27699/27700)| `Group.language`| _Equivalent_<br/>(42664/42665)| `Group.language`
| **`Group.text`**| _Equivalent_<br/>(5394/5395)| `Group.text`| _Equivalent_<br/>(14669/14670)| `Group.text`| _Equivalent_<br/>(27701/27702)| `Group.text`| _Equivalent_<br/>(42666/42667)| `Group.text`
| **`Group.contained`**| _Equivalent_<br/>(5396/5397)| `Group.contained`| _Equivalent_<br/>(14671/14672)| `Group.contained`| _Equivalent_<br/>(27703/27704)| `Group.contained`| _Equivalent_<br/>(42668/42669)| `Group.contained`
| **`Group.extension`**| _Equivalent_<br/>(5398/5399)| `Group.extension`| _Equivalent_<br/>(14673/14674)| `Group.extension`| _Equivalent_<br/>(27705/27706)| `Group.extension`| _Equivalent_<br/>(42670/42671)| `Group.extension`
| **`Group.modifierExtension`**| _Equivalent_<br/>(5400/5401)| `Group.modifierExtension`| _Equivalent_<br/>(14675/14676)| `Group.modifierExtension`| _Equivalent_<br/>(27707/27708)| `Group.modifierExtension`| _Equivalent_<br/>(42672/42673)| `Group.modifierExtension`
| **`Group.identifier`**| _Equivalent_<br/>(5402/5403)| `Group.identifier`| _Equivalent_<br/>(14677/14678)| `Group.identifier`| _Equivalent_<br/>(27709/27710)| `Group.identifier`| _Equivalent_<br/>(42674/42675)| `Group.identifier`
| **`Group.type`**| _Equivalent_<br/>(5404/5405)| `Group.type`| _Equivalent_<br/>(14681/14682)| `Group.type`| _Equivalent_<br/>(27713/27714)| `Group.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(42678)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(42679)| `Group.type`
| **`Group.actual`**| _Equivalent_<br/>(5406/5407)| `Group.actual`| _Equivalent_<br/>(14683/14684)| `Group.actual`| _Equivalent_<br/>(27715/27716)| `Group.actual`| | | 
| **`Group.code`**| _Equivalent_<br/>(5408/5409)| `Group.code`| _Equivalent_<br/>(14685/14686)| `Group.code`| _Equivalent_<br/>(27717/27718)| `Group.code`| _Equivalent_<br/>(42681/42682)| `Group.code`
| **`Group.name`**| _Equivalent_<br/>(5410/5411)| `Group.name`| _Equivalent_<br/>(14687/14688)| `Group.name`| _Equivalent_<br/>(27719/27720)| `Group.name`| _Equivalent_<br/>(42683/42684)| `Group.name`
| **`Group.quantity`**| _Equivalent_<br/>(5412/5413)| `Group.quantity`| _Equivalent_<br/>(14689/14690)| `Group.quantity`| _Equivalent_<br/>(27721/27722)| `Group.quantity`| _Equivalent_<br/>(42685/42686)| `Group.quantity`
| **`Group.characteristic`**| _Equivalent_<br/>(5414/5415)| `Group.characteristic`| _Equivalent_<br/>(14691/14692)| `Group.characteristic`| _Equivalent_<br/>(27725/27726)| `Group.characteristic`| _Equivalent_<br/>(42689/42690)| `Group.characteristic`
| **`Group.characteristic.id`**| _Equivalent_<br/>(5416/5417)| `Group.characteristic.id`| _Equivalent_<br/>(14693/14694)| `Group.characteristic.id`| _Equivalent_<br/>(27727/27728)| `Group.characteristic.id`| _Equivalent_<br/>(42691/42692)| `Group.characteristic.id`
| **`Group.characteristic.extension`**| _Equivalent_<br/>(5418/5419)| `Group.characteristic.extension`| _Equivalent_<br/>(14695/14696)| `Group.characteristic.extension`| _Equivalent_<br/>(27729/27730)| `Group.characteristic.extension`| _Equivalent_<br/>(42693/42694)| `Group.characteristic.extension`
| **`Group.characteristic.modifierExtension`**| _Equivalent_<br/>(5420/5421)| `Group.characteristic.modifierExtension`| _Equivalent_<br/>(14697/14698)| `Group.characteristic.modifierExtension`| _Equivalent_<br/>(27731/27732)| `Group.characteristic.modifierExtension`| _Equivalent_<br/>(42695/42696)| `Group.characteristic.modifierExtension`
| **`Group.characteristic.code`**| _Equivalent_<br/>(5422/5423)| `Group.characteristic.code`| _Equivalent_<br/>(14699/14700)| `Group.characteristic.code`| _Equivalent_<br/>(27733/27734)| `Group.characteristic.code`| _Equivalent_<br/>(42697/42698)| `Group.characteristic.code`
| **`Group.characteristic.value[x]`**| _Equivalent_<br/>(5424/5425)| `Group.characteristic.value[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14701)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14702)| `Group.characteristic.value[x]`| _Equivalent_<br/>(27735/27736)| `Group.characteristic.value[x]`| _Equivalent_<br/>(42699/42700)| `Group.characteristic.value[x]`
| **`Group.characteristic.exclude`**| _Equivalent_<br/>(5426/5427)| `Group.characteristic.exclude`| _Equivalent_<br/>(14703/14704)| `Group.characteristic.exclude`| _Equivalent_<br/>(27737/27738)| `Group.characteristic.exclude`| _Equivalent_<br/>(42701/42702)| `Group.characteristic.exclude`
| **`Group.characteristic.period`**| _Equivalent_<br/>(5428/5429)| `Group.characteristic.period`| _Equivalent_<br/>(14705/14706)| `Group.characteristic.period`| _Equivalent_<br/>(27739/27740)| `Group.characteristic.period`| _Equivalent_<br/>(42703/42704)| `Group.characteristic.period`
| **`Group.member`**| _Equivalent_<br/>(5430/5431)| `Group.member`| _Equivalent_<br/>(14707/14708)| `Group.member`| _Equivalent_<br/>(27741/27742)| `Group.member`| _Equivalent_<br/>(42705/42706)| `Group.member`
| **`Group.member.id`**| _Equivalent_<br/>(5432/5433)| `Group.member.id`| _Equivalent_<br/>(14709/14710)| `Group.member.id`| _Equivalent_<br/>(27743/27744)| `Group.member.id`| _Equivalent_<br/>(42707/42708)| `Group.member.id`
| **`Group.member.extension`**| _Equivalent_<br/>(5434/5435)| `Group.member.extension`| _Equivalent_<br/>(14711/14712)| `Group.member.extension`| _Equivalent_<br/>(27745/27746)| `Group.member.extension`| _Equivalent_<br/>(42709/42710)| `Group.member.extension`
| **`Group.member.modifierExtension`**| _Equivalent_<br/>(5436/5437)| `Group.member.modifierExtension`| _Equivalent_<br/>(14713/14714)| `Group.member.modifierExtension`| _Equivalent_<br/>(27747/27748)| `Group.member.modifierExtension`| _Equivalent_<br/>(42711/42712)| `Group.member.modifierExtension`
| **`Group.member.entity`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5438)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5439)| `Group.member.entity`| →→→→ _RelatedTo_ →→→→ <br/>(14715)<hr/>←←←← _RelatedTo_ ←←←← <br/>(14716)| `Group.member.entity`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(27749)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(27750)| `Group.member.entity`| →→→→ _RelatedTo_ →→→→ <br/>(42713)<hr/>←←←← _RelatedTo_ ←←←← <br/>(42714)| `Group.member.entity`
| **`Group.member.period`**| _Equivalent_<br/>(5440/5441)| `Group.member.period`| _Equivalent_<br/>(14717/14718)| `Group.member.period`| _Equivalent_<br/>(27751/27752)| `Group.member.period`| _Equivalent_<br/>(42715/42716)| `Group.member.period`
| **`Group.member.inactive`**| _Equivalent_<br/>(5442/5443)| `Group.member.inactive`| _Equivalent_<br/>(14719/14720)| `Group.member.inactive`| _Equivalent_<br/>(27753/27754)| `Group.member.inactive`| _Equivalent_<br/>(42717/42718)| `Group.member.inactive`
| *30 of 30 elements used* | | *30 of 31 elements used* <br/>remaining elements:<br/>`Group.active`| | *30 of 32 elements used* <br/>remaining elements:<br/>`Group.active`, `Group.managingEntity`| | *30 of 32 elements used* <br/>remaining elements:<br/>`Group.active`, `Group.managingEntity`| | *29 of 33 elements used* <br/>remaining elements:<br/>`Group.active`, `Group.description`, `Group.managingEntity`, `Group.membership`

