Comparison of 
Generated at Monday, April 14, 2025 6:17:29 PM

### Organization

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | Organization |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Organization` |
| Version | 4.0.1 |
| Description | A formally or informally recognized grouping of people or organizations formed for the purpose of achieving some form of collective action.  Includes companies, institutions, corporations, departments, community groups, healthcare practice groups, payer/insurer, etc. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1131` |
| Database Snapshot Count | `26` |
| Database Differential Count | `15` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Organization` | `Organization` | `Organization` | Organization | A grouping of people or organizations with a common purpose | 0..* | Organization |  |  |
| `Organization.active` | `Organization.active` | `active` | Organization.active | Whether the organization's record is still in active use | 0..1 | boolean |  |  |
| `Organization.address` | `Organization.address` | `address` | Organization.address | An address for the organization | 0..* | Address |  |  |
| `Organization.alias` | `Organization.alias` | `alias` | Organization.alias | A list of alternate names that the organization is known as, or was known as in the past | 0..* | string |  |  |
| `Organization.contact` | `Organization.contact` | `contact` | Organization.contact | Contact for the organization for a certain purpose | 0..* | BackboneElement |  |  |
| `Organization.contact.address` | `Organization.contact.address` | `address` | Organization.contact.address | Visiting or postal addresses for the contact | 0..1 | Address |  |  |
| `Organization.contact.extension` | `Organization.contact.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Organization.contact.id` | `Organization.contact.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Organization.contact.modifierExtension` | `Organization.contact.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Organization.contact.name` | `Organization.contact.name` | `name` | Organization.contact.name | A name associated with the contact | 0..1 | HumanName |  |  |
| `Organization.contact.purpose` | `Organization.contact.purpose` | `purpose` | Organization.contact.purpose | The type of contact | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/contactentity-type` |
| `Organization.contact.telecom` | `Organization.contact.telecom` | `telecom` | Organization.contact.telecom | Contact details (telephone, email, etc.)  for a contact | 0..* | ContactPoint |  |  |
| `Organization.contained` | `Organization.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Organization.endpoint` | `Organization.endpoint` | `endpoint` | Organization.endpoint | Technical endpoints providing access to services operated for the organization | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Endpoint) |  |  |
| `Organization.extension` | `Organization.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Organization.id` | `Organization.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Organization.identifier` | `Organization.identifier` | `identifier` | Organization.identifier | Identifies this organization  across multiple systems | 0..* | Identifier |  |  |
| `Organization.implicitRules` | `Organization.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Organization.language` | `Organization.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `Organization.meta` | `Organization.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Organization.modifierExtension` | `Organization.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Organization.name` | `Organization.name` | `name` | Organization.name | Name used for the organization | 0..1 | string |  |  |
| `Organization.partOf` | `Organization.partOf` | `partOf` | Organization.partOf | The organization of which this organization forms a part | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Organization.telecom` | `Organization.telecom` | `telecom` | Organization.telecom | A contact detail for the organization | 0..* | ContactPoint |  |  |
| `Organization.text` | `Organization.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Organization.type` | `Organization.type` | `type` | Organization.type | Kind of organization | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/organization-type` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Organization](/docs/R2/Resources/Organization.md)<br/> `http://hl7.org/fhir/StructureDefinition/Organization\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `137`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `303`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Organization](/docs/R3/Resources/Organization.md)<br/> `http://hl7.org/fhir/StructureDefinition/Organization\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `492`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `686`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Organization](/docs/R4/Resources/Organization.md)<br/> `http://hl7.org/fhir/StructureDefinition/Organization\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1565`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1566`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Organization](/docs/R4B/Resources/Organization.md)<br/> `http://hl7.org/fhir/StructureDefinition/Organization\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1018`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1247`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Organization](/docs/R5/Resources/Organization.md)<br/> `http://hl7.org/fhir/StructureDefinition/Organization\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Organization from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Organization](/docs/R2/Resources/Organization.md)| Relationship | [R3 Organization](/docs/R3/Resources/Organization.md)| Relationship | R4 Organization| Relationship | [R4B Organization](/docs/R4B/Resources/Organization.md)| Relationship | [R5 Organization](/docs/R5/Resources/Organization.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Organization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6864)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6865)| `Organization`| _Equivalent_<br/>(16713/16714)| **`Organization`**| _Equivalent_<br/>(31146/31147)| `Organization`| _Equivalent_<br/>(45762/45763)| `Organization`
| `Organization.id`| _Equivalent_<br/>(6866/6867)| `Organization.id`| _Equivalent_<br/>(16715/16716)| **`Organization.id`**| _Equivalent_<br/>(31148/31149)| `Organization.id`| _Equivalent_<br/>(45764/45765)| `Organization.id`
| `Organization.meta`| _Equivalent_<br/>(6868/6869)| `Organization.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16717)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16718)| **`Organization.meta`**| _Equivalent_<br/>(31150/31151)| `Organization.meta`| _Equivalent_<br/>(45766/45767)| `Organization.meta`
| `Organization.implicitRules`| _Equivalent_<br/>(6870/6871)| `Organization.implicitRules`| _Equivalent_<br/>(16719/16720)| **`Organization.implicitRules`**| _Equivalent_<br/>(31152/31153)| `Organization.implicitRules`| _Equivalent_<br/>(45768/45769)| `Organization.implicitRules`
| `Organization.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6872)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6873)| `Organization.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16721)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(16722)| **`Organization.language`**| _Equivalent_<br/>(31154/31155)| `Organization.language`| _Equivalent_<br/>(45770/45771)| `Organization.language`
| `Organization.text`| _Equivalent_<br/>(6874/6875)| `Organization.text`| _Equivalent_<br/>(16723/16724)| **`Organization.text`**| _Equivalent_<br/>(31156/31157)| `Organization.text`| _Equivalent_<br/>(45772/45773)| `Organization.text`
| `Organization.contained`| _Equivalent_<br/>(6876/6877)| `Organization.contained`| _Equivalent_<br/>(16725/16726)| **`Organization.contained`**| _Equivalent_<br/>(31158/31159)| `Organization.contained`| _Equivalent_<br/>(45774/45775)| `Organization.contained`
| `Organization.extension`| _Equivalent_<br/>(6878/6879)| `Organization.extension`| _Equivalent_<br/>(16727/16728)| **`Organization.extension`**| _Equivalent_<br/>(31160/31161)| `Organization.extension`| _Equivalent_<br/>(45776/45777)| `Organization.extension`
| `Organization.modifierExtension`| _Equivalent_<br/>(6880/6881)| `Organization.modifierExtension`| _Equivalent_<br/>(16729/16730)| **`Organization.modifierExtension`**| _Equivalent_<br/>(31162/31163)| `Organization.modifierExtension`| _Equivalent_<br/>(45778/45779)| `Organization.modifierExtension`
| `Organization.identifier`| _Equivalent_<br/>(6882/6883)| `Organization.identifier`| _Equivalent_<br/>(16731/16732)| **`Organization.identifier`**| _Equivalent_<br/>(31164/31165)| `Organization.identifier`| _Equivalent_<br/>(45780/45781)| `Organization.identifier`
| `Organization.active`| _Equivalent_<br/>(6884/6885)| `Organization.active`| _Equivalent_<br/>(16733/16734)| **`Organization.active`**| _Equivalent_<br/>(31166/31167)| `Organization.active`| _Equivalent_<br/>(45782/45783)| `Organization.active`
| `Organization.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6886)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6887)| `Organization.type`| _Equivalent_<br/>(16735/16736)| **`Organization.type`**| _Equivalent_<br/>(31168/31169)| `Organization.type`| _Equivalent_<br/>(45784/45785)| `Organization.type`
| `Organization.name`| _Equivalent_<br/>(6888/6889)| `Organization.name`| _Equivalent_<br/>(16737/16738)| **`Organization.name`**| _Equivalent_<br/>(31170/31171)| `Organization.name`| _Equivalent_<br/>(45786/45787)| `Organization.name`
| | | `Organization.alias`| _Equivalent_<br/>(16739/16740)| **`Organization.alias`**| _Equivalent_<br/>(31172/31173)| `Organization.alias`| _Equivalent_<br/>(45788/45789)| `Organization.alias`
| `Organization.telecom`| _Equivalent_<br/>(6890/6891)| `Organization.telecom`| _Equivalent_<br/>(16741/16742)| **`Organization.telecom`**| _Equivalent_<br/>(31174/31175)| `Organization.telecom`| | | 
| `Organization.address`| _Equivalent_<br/>(6892/6893)| `Organization.address`| _Equivalent_<br/>(16743/16744)| **`Organization.address`**| _Equivalent_<br/>(31176/31177)| `Organization.address`| | | 
| `Organization.partOf`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6894)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6895)| `Organization.partOf`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16745)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16746)| **`Organization.partOf`**| _Equivalent_<br/>(31178/31179)| `Organization.partOf`| _Equivalent_<br/>(45792/45793)| `Organization.partOf`
| `Organization.contact`| _Equivalent_<br/>(6896/6897)| `Organization.contact`| _Equivalent_<br/>(16747/16748)| **`Organization.contact`**| _Equivalent_<br/>(31180/31181)| `Organization.contact`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(45794)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45795)| `Organization.contact`
| `Organization.contact.id`| _Equivalent_<br/>(6898/6899)| `Organization.contact.id`| _Equivalent_<br/>(16749/16750)| **`Organization.contact.id`**| _Equivalent_<br/>(31182/31183)| `Organization.contact.id`| | | 
| `Organization.contact.extension`| _Equivalent_<br/>(6900/6901)| `Organization.contact.extension`| _Equivalent_<br/>(16751/16752)| **`Organization.contact.extension`**| _Equivalent_<br/>(31184/31185)| `Organization.contact.extension`| | | 
| `Organization.contact.modifierExtension`| _Equivalent_<br/>(6902/6903)| `Organization.contact.modifierExtension`| _Equivalent_<br/>(16753/16754)| **`Organization.contact.modifierExtension`**| _Equivalent_<br/>(31186/31187)| `Organization.contact.modifierExtension`| | | 
| `Organization.contact.purpose`| _Equivalent_<br/>(6904/6905)| `Organization.contact.purpose`| _Equivalent_<br/>(16755/16756)| **`Organization.contact.purpose`**| _Equivalent_<br/>(31188/31189)| `Organization.contact.purpose`| | | 
| `Organization.contact.name`| _Equivalent_<br/>(6906/6907)| `Organization.contact.name`| _Equivalent_<br/>(16757/16758)| **`Organization.contact.name`**| _Equivalent_<br/>(31190/31191)| `Organization.contact.name`| | | 
| `Organization.contact.telecom`| _Equivalent_<br/>(6908/6909)| `Organization.contact.telecom`| _Equivalent_<br/>(16759/16760)| **`Organization.contact.telecom`**| _Equivalent_<br/>(31192/31193)| `Organization.contact.telecom`| | | 
| `Organization.contact.address`| _Equivalent_<br/>(6910/6911)| `Organization.contact.address`| _Equivalent_<br/>(16761/16762)| **`Organization.contact.address`**| _Equivalent_<br/>(31194/31195)| `Organization.contact.address`| | | 
| | | `Organization.endpoint`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16763)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16764)| **`Organization.endpoint`**| _Equivalent_<br/>(31196/31197)| `Organization.endpoint`| _Equivalent_<br/>(45803/45804)| `Organization.endpoint`
| *24 of 24 elements used* | | *26 of 26 elements used* | | *26 of 26 elements used* | | *26 of 26 elements used* | | *17 of 26 elements used* <br/>remaining elements:<br/>`Organization.description`, `Organization.qualification`, `Organization.qualification.code`, `Organization.qualification.extension`, `Organization.qualification.id`, `Organization.qualification.identifier`, `Organization.qualification.issuer`, `Organization.qualification.modifierExtension`, `Organization.qualification.period`

