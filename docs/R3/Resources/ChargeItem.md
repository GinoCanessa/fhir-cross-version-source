Comparison of 
Generated at Monday, April 14, 2025 6:17:24 PM

### ChargeItem

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | ChargeItem |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ChargeItem` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for ChargeItem Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `489` |
| Database Snapshot Count | `37` |
| Database Differential Count | `26` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ChargeItem` | `ChargeItem` | `ChargeItem` | ChargeItem | Item containing charge code(s) associated with the provision of healthcare provider products | 0..* | ChargeItem |  |  |
| `ChargeItem.account` | `ChargeItem.account` | `account` |  | Account to place this charge | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Account) |  |  |
| `ChargeItem.bodysite` | `ChargeItem.bodysite` | `bodysite` |  | Anatomical location, if relevant | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `ChargeItem.code` | `ChargeItem.code` | `code` |  | A code that identifies the charge, like a billing code | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/chargeitem-billingcodes` |
| `ChargeItem.contained` | `ChargeItem.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ChargeItem.context` | `ChargeItem.context` | `context` |  | Encounter / Episode associated with event | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter), Reference(http://hl7.org/fhir/StructureDefinition/EpisodeOfCare) |  |  |
| `ChargeItem.definition` | `ChargeItem.definition` | `definition` |  | Defining information about the code of this charge item | 0..* | uri |  |  |
| `ChargeItem.enteredDate` | `ChargeItem.enteredDate` | `enteredDate` |  | Date the charge item was entered | 0..1 | dateTime |  |  |
| `ChargeItem.enterer` | `ChargeItem.enterer` | `enterer` |  | Individual who was entering | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `ChargeItem.extension` | `ChargeItem.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ChargeItem.factorOverride` | `ChargeItem.factorOverride` | `factorOverride` |  | Factor overriding the associated rules | 0..1 | decimal |  |  |
| `ChargeItem.id` | `ChargeItem.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ChargeItem.identifier` | `ChargeItem.identifier` | `identifier` |  | Business Identifier for item | 0..1 | Identifier |  |  |
| `ChargeItem.implicitRules` | `ChargeItem.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ChargeItem.language` | `ChargeItem.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `ChargeItem.meta` | `ChargeItem.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ChargeItem.modifierExtension` | `ChargeItem.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ChargeItem.note` | `ChargeItem.note` | `note` |  | Comments made about the ChargeItem | 0..* | Annotation |  |  |
| `ChargeItem.occurrence[x]` | `ChargeItem.occurrence[x]` | `occurrence[x]` |  | When the charged service was applied | 0..1 | dateTime, Period, Timing |  |  |
| `ChargeItem.overrideReason` | `ChargeItem.overrideReason` | `overrideReason` |  | Reason for overriding the list price/factor | 0..1 | string |  |  |
| `ChargeItem.partOf` | `ChargeItem.partOf` | `partOf` |  | Part of referenced ChargeItem | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ChargeItem) |  |  |
| `ChargeItem.participant` | `ChargeItem.participant` | `participant` |  | Who performed charged service | 0..* | BackboneElement |  |  |
| `ChargeItem.participant.actor` | `ChargeItem.participant.actor` | `actor` |  | Individual who was performing | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `ChargeItem.participant.extension` | `ChargeItem.participant.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ChargeItem.participant.id` | `ChargeItem.participant.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ChargeItem.participant.modifierExtension` | `ChargeItem.participant.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ChargeItem.participant.role` | `ChargeItem.participant.role` | `role` |  | What type of performance was done | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/performer-role` |
| `ChargeItem.performingOrganization` | `ChargeItem.performingOrganization` | `performingOrganization` |  | Organization providing the charged sevice | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `ChargeItem.priceOverride` | `ChargeItem.priceOverride` | `priceOverride` |  | Price overriding the associated rules | 0..1 | Money |  |  |
| `ChargeItem.quantity` | `ChargeItem.quantity` | `quantity` |  | Quantity of which the charge item has been serviced | 0..1 | Quantity |  |  |
| `ChargeItem.reason` | `ChargeItem.reason` | `reason` |  | Why was the charged  service rendered? | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/icd-10` |
| `ChargeItem.requestingOrganization` | `ChargeItem.requestingOrganization` | `requestingOrganization` |  | Organization requesting the charged service | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `ChargeItem.service` | `ChargeItem.service` | `service` |  | Which rendered service is being charged? | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DiagnosticReport), Reference(http://hl7.org/fhir/StructureDefinition/ImagingStudy), Reference(http://hl7.org/fhir/StructureDefinition/Immunization), Reference(http://hl7.org/fhir/StructureDefinition/MedicationAdministration), Reference(http://hl7.org/fhir/StructureDefinition/MedicationDispense), Reference(http://hl7.org/fhir/StructureDefinition/Observation), Reference(http://hl7.org/fhir/StructureDefinition/Procedure), Reference(http://hl7.org/fhir/StructureDefinition/SupplyDelivery) |  |  |
| `ChargeItem.status` | `ChargeItem.status` | `status` |  | planned \| billable \| not-billable \| aborted \| billed \| entered-in-error \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/chargeitem-status` |
| `ChargeItem.subject` | `ChargeItem.subject` | `subject` |  | Individual service was done for/to | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `ChargeItem.supportingInformation` | `ChargeItem.supportingInformation` | `supportingInformation` |  | Further information supporting the this charge | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `ChargeItem.text` | `ChargeItem.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ChargeItem](/docs/R3/Resources/ChargeItem.md)<br/> `http://hl7.org/fhir/StructureDefinition/ChargeItem\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `429`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `625`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ChargeItem](/docs/R4/Resources/ChargeItem.md)<br/> `http://hl7.org/fhir/StructureDefinition/ChargeItem\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1419`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1420`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ChargeItem](/docs/R4B/Resources/ChargeItem.md)<br/> `http://hl7.org/fhir/StructureDefinition/ChargeItem\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `942`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1171`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ChargeItem](/docs/R5/Resources/ChargeItem.md)<br/> `http://hl7.org/fhir/StructureDefinition/ChargeItem\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ChargeItem from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 ChargeItem| Relationship | [R4 ChargeItem](/docs/R4/Resources/ChargeItem.md)| Relationship | [R4B ChargeItem](/docs/R4B/Resources/ChargeItem.md)| Relationship | [R5 ChargeItem](/docs/R5/Resources/ChargeItem.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`ChargeItem`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11119)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11120)| `ChargeItem`| _Equivalent_<br/>(22769/22770)| `ChargeItem`| _Equivalent_<br/>(37691/37692)| `ChargeItem`
| | | **`ChargeItem`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11119)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11120)| `ChargeItem`| _Equivalent_<br/>(22769/22770)| `ChargeItem`| →→→→ _Equivalent_ →→→→ <br/>(49921)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1979)| `ChargeItem.totalPriceComponent`
| | | **`ChargeItem.id`**| _Equivalent_<br/>(11121/11122)| `ChargeItem.id`| _Equivalent_<br/>(22771/22772)| `ChargeItem.id`| _Equivalent_<br/>(37693/37694)| `ChargeItem.id`
| | | **`ChargeItem.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11123)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11124)| `ChargeItem.meta`| _Equivalent_<br/>(22773/22774)| `ChargeItem.meta`| _Equivalent_<br/>(37695/37696)| `ChargeItem.meta`
| | | **`ChargeItem.implicitRules`**| _Equivalent_<br/>(11125/11126)| `ChargeItem.implicitRules`| _Equivalent_<br/>(22775/22776)| `ChargeItem.implicitRules`| _Equivalent_<br/>(37697/37698)| `ChargeItem.implicitRules`
| | | **`ChargeItem.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11127)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11128)| `ChargeItem.language`| _Equivalent_<br/>(22777/22778)| `ChargeItem.language`| _Equivalent_<br/>(37699/37700)| `ChargeItem.language`
| | | **`ChargeItem.text`**| _Equivalent_<br/>(11129/11130)| `ChargeItem.text`| _Equivalent_<br/>(22779/22780)| `ChargeItem.text`| _Equivalent_<br/>(37701/37702)| `ChargeItem.text`
| | | **`ChargeItem.contained`**| _Equivalent_<br/>(11131/11132)| `ChargeItem.contained`| _Equivalent_<br/>(22781/22782)| `ChargeItem.contained`| _Equivalent_<br/>(37703/37704)| `ChargeItem.contained`
| | | **`ChargeItem.extension`**| _Equivalent_<br/>(11133/11134)| `ChargeItem.extension`| _Equivalent_<br/>(22783/22784)| `ChargeItem.extension`| _Equivalent_<br/>(37705/37706)| `ChargeItem.extension`
| | | **`ChargeItem.modifierExtension`**| _Equivalent_<br/>(11135/11136)| `ChargeItem.modifierExtension`| _Equivalent_<br/>(22785/22786)| `ChargeItem.modifierExtension`| _Equivalent_<br/>(37707/37708)| `ChargeItem.modifierExtension`
| | | **`ChargeItem.identifier`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11137)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11138)| `ChargeItem.identifier`| _Equivalent_<br/>(22787/22788)| `ChargeItem.identifier`| _Equivalent_<br/>(37709/37710)| `ChargeItem.identifier`
| | | **`ChargeItem.definition`**| _Equivalent_<br/>(845/1372)| `ChargeItem.definitionUri`| _Equivalent_<br/>(22789/22790)| `ChargeItem.definitionUri`| _Equivalent_<br/>(37711/37712)| `ChargeItem.definitionUri`
| | | **`ChargeItem.status`**| _Equivalent_<br/>(11139/11140)| `ChargeItem.status`| _Equivalent_<br/>(22793/22794)| `ChargeItem.status`| _Equivalent_<br/>(37715/37716)| `ChargeItem.status`
| | | **`ChargeItem.partOf`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11141)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11142)| `ChargeItem.partOf`| _Equivalent_<br/>(22795/22796)| `ChargeItem.partOf`| _Equivalent_<br/>(37717/37718)| `ChargeItem.partOf`
| | | **`ChargeItem.code`**| _Equivalent_<br/>(11143/11144)| `ChargeItem.code`| _Equivalent_<br/>(22797/22798)| `ChargeItem.code`| _Equivalent_<br/>(37719/37720)| `ChargeItem.code`
| | | **`ChargeItem.subject`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11145)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11146)| `ChargeItem.subject`| _Equivalent_<br/>(22799/22800)| `ChargeItem.subject`| _Equivalent_<br/>(37721/37722)| `ChargeItem.subject`
| | | **`ChargeItem.context`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11147)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11148)| `ChargeItem.context`| _Equivalent_<br/>(22801/22802)| `ChargeItem.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1734)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1978)| `ChargeItem.encounter`
| | | **`ChargeItem.occurrence[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11149)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11150)| `ChargeItem.occurrence[x]`| _Equivalent_<br/>(22803/22804)| `ChargeItem.occurrence[x]`| _Equivalent_<br/>(37723/37724)| `ChargeItem.occurrence[x]`
| | | **`ChargeItem.participant`**| _Equivalent_<br/>(846/1373)| `ChargeItem.performer`| _Equivalent_<br/>(22805/22806)| `ChargeItem.performer`| _Equivalent_<br/>(37725/37726)| `ChargeItem.performer`
| | | **`ChargeItem.participant.id`**| | | | | | | 
| | | **`ChargeItem.participant.extension`**| | | | | | | 
| | | **`ChargeItem.participant.modifierExtension`**| | | | | | | 
| | | **`ChargeItem.participant.role`**| _Equivalent_<br/>(848/1375)| `ChargeItem.performer.function`| _Equivalent_<br/>(22813/22814)| `ChargeItem.performer.function`| _Equivalent_<br/>(37733/37734)| `ChargeItem.performer.function`
| | | **`ChargeItem.participant.actor`**| →→→→ _RelatedTo_ →→→→ <br/>(847)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1374)| `ChargeItem.performer.actor`| _Equivalent_<br/>(22815/22816)| `ChargeItem.performer.actor`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37735)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37736)| `ChargeItem.performer.actor`
| | | **`ChargeItem.performingOrganization`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11154)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11155)| `ChargeItem.performingOrganization`| _Equivalent_<br/>(22817/22818)| `ChargeItem.performingOrganization`| _Equivalent_<br/>(37737/37738)| `ChargeItem.performingOrganization`
| | | **`ChargeItem.requestingOrganization`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11156)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11157)| `ChargeItem.requestingOrganization`| _Equivalent_<br/>(22819/22820)| `ChargeItem.requestingOrganization`| _Equivalent_<br/>(37739/37740)| `ChargeItem.requestingOrganization`
| | | **`ChargeItem.quantity`**| _Equivalent_<br/>(11158/11159)| `ChargeItem.quantity`| _Equivalent_<br/>(22823/22824)| `ChargeItem.quantity`| _Equivalent_<br/>(37743/37744)| `ChargeItem.quantity`
| | | **`ChargeItem.bodysite`**| _Equivalent_<br/>(11160/11161)| `ChargeItem.bodysite`| _Equivalent_<br/>(22825/22826)| `ChargeItem.bodysite`| _Equivalent_<br/>(37745/37746)| `ChargeItem.bodysite`
| | | **`ChargeItem.factorOverride`**| _Equivalent_<br/>(11162/11163)| `ChargeItem.factorOverride`| _Equivalent_<br/>(22827/22828)| `ChargeItem.factorOverride`| | | 
| | | **`ChargeItem.priceOverride`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(11164)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11165)| `ChargeItem.priceOverride`| _Equivalent_<br/>(22829/22830)| `ChargeItem.priceOverride`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1735)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37748)| `ChargeItem.totalPriceComponent`
| | | **`ChargeItem.overrideReason`**| _Equivalent_<br/>(11166/11167)| `ChargeItem.overrideReason`| _Equivalent_<br/>(22831/22832)| `ChargeItem.overrideReason`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37749)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37750)| `ChargeItem.overrideReason`
| | | **`ChargeItem.enterer`**| →→→→ _RelatedTo_ →→→→ <br/>(11168)<hr/>←←←← _RelatedTo_ ←←←← <br/>(11169)| `ChargeItem.enterer`| _Equivalent_<br/>(22833/22834)| `ChargeItem.enterer`| _Equivalent_<br/>(37751/37752)| `ChargeItem.enterer`
| | | **`ChargeItem.enteredDate`**| _Equivalent_<br/>(11170/11171)| `ChargeItem.enteredDate`| _Equivalent_<br/>(22835/22836)| `ChargeItem.enteredDate`| _Equivalent_<br/>(37753/37754)| `ChargeItem.enteredDate`
| | | **`ChargeItem.reason`**| _Equivalent_<br/>(11172/11173)| `ChargeItem.reason`| _Equivalent_<br/>(22837/22838)| `ChargeItem.reason`| _Equivalent_<br/>(37755/37756)| `ChargeItem.reason`
| | | **`ChargeItem.service`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11174)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11175)| `ChargeItem.service`| _Equivalent_<br/>(22839/22840)| `ChargeItem.service`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37757)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37758)| `ChargeItem.service`
| | | **`ChargeItem.account`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11176)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11177)| `ChargeItem.account`| _Equivalent_<br/>(22843/22844)| `ChargeItem.account`| _Equivalent_<br/>(37759/37760)| `ChargeItem.account`
| | | **`ChargeItem.note`**| _Equivalent_<br/>(11178/11179)| `ChargeItem.note`| _Equivalent_<br/>(22845/22846)| `ChargeItem.note`| _Equivalent_<br/>(37761/37762)| `ChargeItem.note`
| | | **`ChargeItem.supportingInformation`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11180)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11181)| `ChargeItem.supportingInformation`| _Equivalent_<br/>(22847/22848)| `ChargeItem.supportingInformation`| _Equivalent_<br/>(37763/37764)| `ChargeItem.supportingInformation`
| | | *37 of 37 elements used* | | *34 of 40 elements used* <br/>remaining elements:<br/>`ChargeItem.costCenter`, `ChargeItem.definitionCanonical`, `ChargeItem.performer.extension`, `ChargeItem.performer.id`, `ChargeItem.performer.modifierExtension`, `ChargeItem.product[x]`| | *34 of 40 elements used* <br/>remaining elements:<br/>`ChargeItem.costCenter`, `ChargeItem.definitionCanonical`, `ChargeItem.performer.extension`, `ChargeItem.performer.id`, `ChargeItem.performer.modifierExtension`, `ChargeItem.product[x]`| | *33 of 40 elements used* <br/>remaining elements:<br/>`ChargeItem.costCenter`, `ChargeItem.definitionCanonical`, `ChargeItem.performer.extension`, `ChargeItem.performer.id`, `ChargeItem.performer.modifierExtension`, `ChargeItem.product`, `ChargeItem.unitPriceComponent`

