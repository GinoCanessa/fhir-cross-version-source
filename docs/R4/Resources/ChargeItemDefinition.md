Comparison of 
Generated at Thursday, April 3, 2025 8:18:19 AM

### ChargeItemDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | ChargeItemDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ChargeItemDefinition` |
| Version | 4.0.1 |
| Description | The ChargeItemDefinition resource provides the properties that apply to the (billing) codes necessary to calculate costs and prices. The properties may differ largely depending on type and realm, therefore this resource gives only a rough structure and requires profiling for each type of billing code system. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1048` |
| Database Snapshot Count | `50` |
| Database Differential Count | `33` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ChargeItemDefinition` | `ChargeItemDefinition` | `ChargeItemDefinition` | ChargeItemDefinition | Definition of properties and rules about how the price and the applicability of a ChargeItem can be determined | 0..* | ChargeItemDefinition |  |  |
| `ChargeItemDefinition.applicability` | `ChargeItemDefinition.applicability` | `applicability` | ChargeItemDefinition.applicability | Whether or not the billing code is applicable | 0..* | BackboneElement |  |  |
| `ChargeItemDefinition.applicability.description` | `ChargeItemDefinition.applicability.description` | `description` | ChargeItemDefinition.applicability.description | Natural language description of the condition | 0..1 | string |  |  |
| `ChargeItemDefinition.applicability.expression` | `ChargeItemDefinition.applicability.expression` | `expression` | ChargeItemDefinition.applicability.expression | Boolean-valued expression | 0..1 | string |  |  |
| `ChargeItemDefinition.applicability.extension` | `ChargeItemDefinition.applicability.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ChargeItemDefinition.applicability.id` | `ChargeItemDefinition.applicability.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ChargeItemDefinition.applicability.language` | `ChargeItemDefinition.applicability.language` | `language` | ChargeItemDefinition.applicability.language | Language of the expression | 0..1 | string |  |  |
| `ChargeItemDefinition.applicability.modifierExtension` | `ChargeItemDefinition.applicability.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ChargeItemDefinition.approvalDate` | `ChargeItemDefinition.approvalDate` | `approvalDate` | ChargeItemDefinition.approvalDate | When the charge item definition was approved by publisher | 0..1 | date |  |  |
| `ChargeItemDefinition.code` | `ChargeItemDefinition.code` | `code` | ChargeItemDefinition.code | Billing codes or product types this definition applies to | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/chargeitem-billingcodes` |
| `ChargeItemDefinition.contact` | `ChargeItemDefinition.contact` | `contact` | ChargeItemDefinition.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `ChargeItemDefinition.contained` | `ChargeItemDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ChargeItemDefinition.copyright` | `ChargeItemDefinition.copyright` | `copyright` | ChargeItemDefinition.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `ChargeItemDefinition.date` | `ChargeItemDefinition.date` | `date` | ChargeItemDefinition.date | Date last changed | 0..1 | dateTime |  |  |
| `ChargeItemDefinition.derivedFromUri` | `ChargeItemDefinition.derivedFromUri` | `derivedFromUri` | ChargeItemDefinition.derivedFromUri | Underlying externally-defined charge item definition | 0..* | uri |  |  |
| `ChargeItemDefinition.description` | `ChargeItemDefinition.description` | `description` | ChargeItemDefinition.description | Natural language description of the charge item definition | 0..1 | markdown |  |  |
| `ChargeItemDefinition.effectivePeriod` | `ChargeItemDefinition.effectivePeriod` | `effectivePeriod` | ChargeItemDefinition.effectivePeriod | When the charge item definition is expected to be used | 0..1 | Period |  |  |
| `ChargeItemDefinition.experimental` | `ChargeItemDefinition.experimental` | `experimental` | ChargeItemDefinition.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `ChargeItemDefinition.extension` | `ChargeItemDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ChargeItemDefinition.id` | `ChargeItemDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ChargeItemDefinition.identifier` | `ChargeItemDefinition.identifier` | `identifier` | ChargeItemDefinition.identifier | Additional identifier for the charge item definition | 0..* | Identifier |  |  |
| `ChargeItemDefinition.implicitRules` | `ChargeItemDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ChargeItemDefinition.instance` | `ChargeItemDefinition.instance` | `instance` | ChargeItemDefinition.instance | Instances this definition applies to | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `ChargeItemDefinition.jurisdiction` | `ChargeItemDefinition.jurisdiction` | `jurisdiction` | ChargeItemDefinition.jurisdiction | Intended jurisdiction for charge item definition (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `ChargeItemDefinition.language` | `ChargeItemDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `ChargeItemDefinition.lastReviewDate` | `ChargeItemDefinition.lastReviewDate` | `lastReviewDate` | ChargeItemDefinition.lastReviewDate | When the charge item definition was last reviewed | 0..1 | date |  |  |
| `ChargeItemDefinition.meta` | `ChargeItemDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ChargeItemDefinition.modifierExtension` | `ChargeItemDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ChargeItemDefinition.partOf` | `ChargeItemDefinition.partOf` | `partOf` | ChargeItemDefinition.partOf | A larger definition of which this particular definition is a component or step | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/ChargeItemDefinition) |  |  |
| `ChargeItemDefinition.propertyGroup` | `ChargeItemDefinition.propertyGroup` | `propertyGroup` | ChargeItemDefinition.propertyGroup | Group of properties which are applicable under the same conditions | 0..* | BackboneElement |  |  |
| `ChargeItemDefinition.propertyGroup.applicability` | `ChargeItemDefinition.propertyGroup.applicability` | `applicability` | ChargeItemDefinition.propertyGroup.applicability | Conditions under which the priceComponent is applicable | 0..* | ChargeItemDefinition.applicability |  |  |
| `ChargeItemDefinition.propertyGroup.extension` | `ChargeItemDefinition.propertyGroup.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ChargeItemDefinition.propertyGroup.id` | `ChargeItemDefinition.propertyGroup.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ChargeItemDefinition.propertyGroup.modifierExtension` | `ChargeItemDefinition.propertyGroup.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ChargeItemDefinition.propertyGroup.priceComponent` | `ChargeItemDefinition.propertyGroup.priceComponent` | `priceComponent` | ChargeItemDefinition.propertyGroup.priceComponent | Components of total line item price | 0..* | BackboneElement |  |  |
| `ChargeItemDefinition.propertyGroup.priceComponent.amount` | `ChargeItemDefinition.propertyGroup.priceComponent.amount` | `amount` | ChargeItemDefinition.propertyGroup.priceComponent.amount | Monetary amount associated with this component | 0..1 | Money |  |  |
| `ChargeItemDefinition.propertyGroup.priceComponent.code` | `ChargeItemDefinition.propertyGroup.priceComponent.code` | `code` | ChargeItemDefinition.propertyGroup.priceComponent.code | Code identifying the specific component | 0..1 | CodeableConcept |  |  |
| `ChargeItemDefinition.propertyGroup.priceComponent.extension` | `ChargeItemDefinition.propertyGroup.priceComponent.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ChargeItemDefinition.propertyGroup.priceComponent.factor` | `ChargeItemDefinition.propertyGroup.priceComponent.factor` | `factor` | ChargeItemDefinition.propertyGroup.priceComponent.factor | Factor used for calculating this component | 0..1 | decimal |  |  |
| `ChargeItemDefinition.propertyGroup.priceComponent.id` | `ChargeItemDefinition.propertyGroup.priceComponent.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ChargeItemDefinition.propertyGroup.priceComponent.modifierExtension` | `ChargeItemDefinition.propertyGroup.priceComponent.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ChargeItemDefinition.propertyGroup.priceComponent.type` | `ChargeItemDefinition.propertyGroup.priceComponent.type` | `type` | ChargeItemDefinition.propertyGroup.priceComponent.type | base \| surcharge \| deduction \| discount \| tax \| informational | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/invoice-priceComponentType|4.0.1` |
| `ChargeItemDefinition.publisher` | `ChargeItemDefinition.publisher` | `publisher` | ChargeItemDefinition.publisher | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `ChargeItemDefinition.replaces` | `ChargeItemDefinition.replaces` | `replaces` | ChargeItemDefinition.replaces | Completed or terminated request(s) whose function is taken by this new request | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/ChargeItemDefinition) |  |  |
| `ChargeItemDefinition.status` | `ChargeItemDefinition.status` | `status` | ChargeItemDefinition.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.0.1` |
| `ChargeItemDefinition.text` | `ChargeItemDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ChargeItemDefinition.title` | `ChargeItemDefinition.title` | `title` | ChargeItemDefinition.title | Name for this charge item definition (human friendly) | 0..1 | string |  |  |
| `ChargeItemDefinition.url` | `ChargeItemDefinition.url` | `url` | ChargeItemDefinition.url | Canonical identifier for this charge item definition, represented as a URI (globally unique) | 1..1 | uri |  |  |
| `ChargeItemDefinition.useContext` | `ChargeItemDefinition.useContext` | `useContext` | ChargeItemDefinition.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `ChargeItemDefinition.version` | `ChargeItemDefinition.version` | `version` | ChargeItemDefinition.version | Business version of the charge item definition | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [ChargeItemDefinition](/docs/R4/Resources/ChargeItemDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ChargeItemDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1421`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1422`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ChargeItemDefinition](/docs/R4B/Resources/ChargeItemDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ChargeItemDefinition\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `943`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1172`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ChargeItemDefinition](/docs/R5/Resources/ChargeItemDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ChargeItemDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ChargeItemDefinition from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | R4 ChargeItemDefinition| Relationship | [R4B ChargeItemDefinition](/docs/R4B/Resources/ChargeItemDefinition.md)| Relationship | [R5 ChargeItemDefinition](/docs/R5/Resources/ChargeItemDefinition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | **`ChargeItemDefinition`**| _Equivalent_<br/>(22849/22850)| `ChargeItemDefinition`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37765)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37766)| `ChargeItemDefinition`
| | | | | **`ChargeItemDefinition.id`**| _Equivalent_<br/>(22851/22852)| `ChargeItemDefinition.id`| _Equivalent_<br/>(37767/37768)| `ChargeItemDefinition.id`
| | | | | **`ChargeItemDefinition.meta`**| _Equivalent_<br/>(22853/22854)| `ChargeItemDefinition.meta`| _Equivalent_<br/>(37769/37770)| `ChargeItemDefinition.meta`
| | | | | **`ChargeItemDefinition.implicitRules`**| _Equivalent_<br/>(22855/22856)| `ChargeItemDefinition.implicitRules`| _Equivalent_<br/>(37771/37772)| `ChargeItemDefinition.implicitRules`
| | | | | **`ChargeItemDefinition.language`**| _Equivalent_<br/>(22857/22858)| `ChargeItemDefinition.language`| _Equivalent_<br/>(37773/37774)| `ChargeItemDefinition.language`
| | | | | **`ChargeItemDefinition.text`**| _Equivalent_<br/>(22859/22860)| `ChargeItemDefinition.text`| _Equivalent_<br/>(37775/37776)| `ChargeItemDefinition.text`
| | | | | **`ChargeItemDefinition.contained`**| _Equivalent_<br/>(22861/22862)| `ChargeItemDefinition.contained`| _Equivalent_<br/>(37777/37778)| `ChargeItemDefinition.contained`
| | | | | **`ChargeItemDefinition.extension`**| _Equivalent_<br/>(22863/22864)| `ChargeItemDefinition.extension`| _Equivalent_<br/>(37779/37780)| `ChargeItemDefinition.extension`
| | | | | **`ChargeItemDefinition.modifierExtension`**| _Equivalent_<br/>(22865/22866)| `ChargeItemDefinition.modifierExtension`| _Equivalent_<br/>(37781/37782)| `ChargeItemDefinition.modifierExtension`
| | | | | **`ChargeItemDefinition.url`**| _Equivalent_<br/>(22867/22868)| `ChargeItemDefinition.url`| →→→→ _Equivalent_ →→→→ <br/>(37783)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37784)| `ChargeItemDefinition.url`
| | | | | **`ChargeItemDefinition.identifier`**| _Equivalent_<br/>(22869/22870)| `ChargeItemDefinition.identifier`| _Equivalent_<br/>(37785/37786)| `ChargeItemDefinition.identifier`
| | | | | **`ChargeItemDefinition.version`**| _Equivalent_<br/>(22871/22872)| `ChargeItemDefinition.version`| _Equivalent_<br/>(37787/37788)| `ChargeItemDefinition.version`
| | | | | **`ChargeItemDefinition.title`**| _Equivalent_<br/>(22873/22874)| `ChargeItemDefinition.title`| _Equivalent_<br/>(37789/37790)| `ChargeItemDefinition.title`
| | | | | **`ChargeItemDefinition.derivedFromUri`**| _Equivalent_<br/>(22875/22876)| `ChargeItemDefinition.derivedFromUri`| _Equivalent_<br/>(37791/37792)| `ChargeItemDefinition.derivedFromUri`
| | | | | **`ChargeItemDefinition.partOf`**| _Equivalent_<br/>(22877/22878)| `ChargeItemDefinition.partOf`| _Equivalent_<br/>(37793/37794)| `ChargeItemDefinition.partOf`
| | | | | **`ChargeItemDefinition.replaces`**| _Equivalent_<br/>(22879/22880)| `ChargeItemDefinition.replaces`| _Equivalent_<br/>(37795/37796)| `ChargeItemDefinition.replaces`
| | | | | **`ChargeItemDefinition.status`**| _Equivalent_<br/>(22881/22882)| `ChargeItemDefinition.status`| _Equivalent_<br/>(37797/37798)| `ChargeItemDefinition.status`
| | | | | **`ChargeItemDefinition.experimental`**| _Equivalent_<br/>(22883/22884)| `ChargeItemDefinition.experimental`| _Equivalent_<br/>(37799/37800)| `ChargeItemDefinition.experimental`
| | | | | **`ChargeItemDefinition.date`**| _Equivalent_<br/>(22885/22886)| `ChargeItemDefinition.date`| _Equivalent_<br/>(37801/37802)| `ChargeItemDefinition.date`
| | | | | **`ChargeItemDefinition.publisher`**| _Equivalent_<br/>(22887/22888)| `ChargeItemDefinition.publisher`| _Equivalent_<br/>(37803/37804)| `ChargeItemDefinition.publisher`
| | | | | **`ChargeItemDefinition.contact`**| _Equivalent_<br/>(22889/22890)| `ChargeItemDefinition.contact`| _Equivalent_<br/>(37805/37806)| `ChargeItemDefinition.contact`
| | | | | **`ChargeItemDefinition.description`**| _Equivalent_<br/>(22891/22892)| `ChargeItemDefinition.description`| _Equivalent_<br/>(37807/37808)| `ChargeItemDefinition.description`
| | | | | **`ChargeItemDefinition.useContext`**| _Equivalent_<br/>(22893/22894)| `ChargeItemDefinition.useContext`| _Equivalent_<br/>(37809/37810)| `ChargeItemDefinition.useContext`
| | | | | **`ChargeItemDefinition.jurisdiction`**| _Equivalent_<br/>(22895/22896)| `ChargeItemDefinition.jurisdiction`| _Equivalent_<br/>(37811/37812)| `ChargeItemDefinition.jurisdiction`
| | | | | **`ChargeItemDefinition.copyright`**| _Equivalent_<br/>(22897/22898)| `ChargeItemDefinition.copyright`| _Equivalent_<br/>(37813/37814)| `ChargeItemDefinition.copyright`
| | | | | **`ChargeItemDefinition.approvalDate`**| _Equivalent_<br/>(22899/22900)| `ChargeItemDefinition.approvalDate`| _Equivalent_<br/>(37815/37816)| `ChargeItemDefinition.approvalDate`
| | | | | **`ChargeItemDefinition.lastReviewDate`**| _Equivalent_<br/>(22901/22902)| `ChargeItemDefinition.lastReviewDate`| _Equivalent_<br/>(37817/37818)| `ChargeItemDefinition.lastReviewDate`
| | | | | **`ChargeItemDefinition.effectivePeriod`**| _Equivalent_<br/>(22903/22904)| `ChargeItemDefinition.effectivePeriod`| | | 
| | | | | **`ChargeItemDefinition.code`**| _Equivalent_<br/>(22905/22906)| `ChargeItemDefinition.code`| _Equivalent_<br/>(37820/37821)| `ChargeItemDefinition.code`
| | | | | **`ChargeItemDefinition.instance`**| _Equivalent_<br/>(22907/22908)| `ChargeItemDefinition.instance`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37822)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37823)| `ChargeItemDefinition.instance`
| | | | | **`ChargeItemDefinition.applicability`**| _Equivalent_<br/>(22909/22910)| `ChargeItemDefinition.applicability`| _Equivalent_<br/>(37824/37825)| `ChargeItemDefinition.applicability`
| | | | | **`ChargeItemDefinition.applicability.id`**| _Equivalent_<br/>(22911/22912)| `ChargeItemDefinition.applicability.id`| _Equivalent_<br/>(37826/37827)| `ChargeItemDefinition.applicability.id`
| | | | | **`ChargeItemDefinition.applicability.extension`**| _Equivalent_<br/>(22913/22914)| `ChargeItemDefinition.applicability.extension`| _Equivalent_<br/>(37828/37829)| `ChargeItemDefinition.applicability.extension`
| | | | | **`ChargeItemDefinition.applicability.modifierExtension`**| _Equivalent_<br/>(22915/22916)| `ChargeItemDefinition.applicability.modifierExtension`| _Equivalent_<br/>(37830/37831)| `ChargeItemDefinition.applicability.modifierExtension`
| | | | | **`ChargeItemDefinition.applicability.description`**| _Equivalent_<br/>(22917/22918)| `ChargeItemDefinition.applicability.description`| | | 
| | | | | **`ChargeItemDefinition.applicability.language`**| _Equivalent_<br/>(22919/22920)| `ChargeItemDefinition.applicability.language`| | | 
| | | | | **`ChargeItemDefinition.applicability.expression`**| _Equivalent_<br/>(22921/22922)| `ChargeItemDefinition.applicability.expression`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1857)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37834)| `ChargeItemDefinition.applicability.condition`
| | | | | **`ChargeItemDefinition.propertyGroup`**| _Equivalent_<br/>(22923/22924)| `ChargeItemDefinition.propertyGroup`| _Equivalent_<br/>(37835/37836)| `ChargeItemDefinition.propertyGroup`
| | | | | **`ChargeItemDefinition.propertyGroup.id`**| _Equivalent_<br/>(22925/22926)| `ChargeItemDefinition.propertyGroup.id`| _Equivalent_<br/>(37837/37838)| `ChargeItemDefinition.propertyGroup.id`
| | | | | **`ChargeItemDefinition.propertyGroup.extension`**| _Equivalent_<br/>(22927/22928)| `ChargeItemDefinition.propertyGroup.extension`| _Equivalent_<br/>(37839/37840)| `ChargeItemDefinition.propertyGroup.extension`
| | | | | **`ChargeItemDefinition.propertyGroup.modifierExtension`**| _Equivalent_<br/>(22929/22930)| `ChargeItemDefinition.propertyGroup.modifierExtension`| _Equivalent_<br/>(37841/37842)| `ChargeItemDefinition.propertyGroup.modifierExtension`
| | | | | **`ChargeItemDefinition.propertyGroup.applicability`**| _Equivalent_<br/>(22931/22932)| `ChargeItemDefinition.propertyGroup.applicability`| _Equivalent_<br/>(37843/37844)| `ChargeItemDefinition.propertyGroup.applicability`
| | | | | **`ChargeItemDefinition.propertyGroup.priceComponent`**| _Equivalent_<br/>(22933/22934)| `ChargeItemDefinition.propertyGroup.priceComponent`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37845)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37846)| `ChargeItemDefinition.propertyGroup.priceComponent`
| | | | | **`ChargeItemDefinition.propertyGroup.priceComponent.id`**| _Equivalent_<br/>(22935/22936)| `ChargeItemDefinition.propertyGroup.priceComponent.id`| | | 
| | | | | **`ChargeItemDefinition.propertyGroup.priceComponent.extension`**| _Equivalent_<br/>(22937/22938)| `ChargeItemDefinition.propertyGroup.priceComponent.extension`| | | 
| | | | | **`ChargeItemDefinition.propertyGroup.priceComponent.modifierExtension`**| _Equivalent_<br/>(22939/22940)| `ChargeItemDefinition.propertyGroup.priceComponent.modifierExtension`| | | 
| | | | | **`ChargeItemDefinition.propertyGroup.priceComponent.type`**| _Equivalent_<br/>(22941/22942)| `ChargeItemDefinition.propertyGroup.priceComponent.type`| | | 
| | | | | **`ChargeItemDefinition.propertyGroup.priceComponent.code`**| _Equivalent_<br/>(22943/22944)| `ChargeItemDefinition.propertyGroup.priceComponent.code`| | | 
| | | | | **`ChargeItemDefinition.propertyGroup.priceComponent.factor`**| _Equivalent_<br/>(22945/22946)| `ChargeItemDefinition.propertyGroup.priceComponent.factor`| | | 
| | | | | **`ChargeItemDefinition.propertyGroup.priceComponent.amount`**| _Equivalent_<br/>(22947/22948)| `ChargeItemDefinition.propertyGroup.priceComponent.amount`| | | 
| | | | | *50 of 50 elements used* | | *50 of 50 elements used* | | *40 of 46 elements used* <br/>remaining elements:<br/>`ChargeItemDefinition.applicability.effectivePeriod`, `ChargeItemDefinition.applicability.relatedArtifact`, `ChargeItemDefinition.copyrightLabel`, `ChargeItemDefinition.name`, `ChargeItemDefinition.purpose`, `ChargeItemDefinition.versionAlgorithm[x]`

