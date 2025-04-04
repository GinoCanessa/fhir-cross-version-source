Comparison of 
Generated at Friday, April 4, 2025 2:59:04 PM

### InsurancePlan

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | InsurancePlan |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/InsurancePlan` |
| Version | 5.0.0 |
| Description | Details of a Health Insurance product/plan provided by an organization. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2326` |
| Database Snapshot Count | `73` |
| Database Differential Count | `41` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `InsurancePlan` | `InsurancePlan` | `InsurancePlan` | InsurancePlan | Details of a Health Insurance product/plan provided by an organization | 0..* | InsurancePlan |  |  |
| `InsurancePlan.administeredBy` | `InsurancePlan.administeredBy` | `administeredBy` | InsurancePlan.administeredBy | Product administrator | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `InsurancePlan.alias` | `InsurancePlan.alias` | `alias` | InsurancePlan.alias | Alternate names | 0..* | string |  |  |
| `InsurancePlan.contact` | `InsurancePlan.contact` | `contact` | InsurancePlan.contact | Official contact details relevant to the health insurance plan/product | 0..* | ExtendedContactDetail |  |  |
| `InsurancePlan.contained` | `InsurancePlan.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `InsurancePlan.coverage` | `InsurancePlan.coverage` | `coverage` | InsurancePlan.coverage | Coverage details | 0..* | BackboneElement |  |  |
| `InsurancePlan.coverage.benefit` | `InsurancePlan.coverage.benefit` | `benefit` | InsurancePlan.coverage.benefit | List of benefits | 1..* | BackboneElement |  |  |
| `InsurancePlan.coverage.benefit.extension` | `InsurancePlan.coverage.benefit.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InsurancePlan.coverage.benefit.id` | `InsurancePlan.coverage.benefit.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InsurancePlan.coverage.benefit.limit` | `InsurancePlan.coverage.benefit.limit` | `limit` | InsurancePlan.coverage.benefit.limit | Benefit limits | 0..* | BackboneElement |  |  |
| `InsurancePlan.coverage.benefit.limit.code` | `InsurancePlan.coverage.benefit.limit.code` | `code` | InsurancePlan.coverage.benefit.limit.code | Benefit limit details | 0..1 | CodeableConcept |  |  |
| `InsurancePlan.coverage.benefit.limit.extension` | `InsurancePlan.coverage.benefit.limit.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InsurancePlan.coverage.benefit.limit.id` | `InsurancePlan.coverage.benefit.limit.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InsurancePlan.coverage.benefit.limit.modifierExtension` | `InsurancePlan.coverage.benefit.limit.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InsurancePlan.coverage.benefit.limit.value` | `InsurancePlan.coverage.benefit.limit.value` | `value` | InsurancePlan.coverage.benefit.limit.value | Maximum value allowed | 0..1 | Quantity |  |  |
| `InsurancePlan.coverage.benefit.modifierExtension` | `InsurancePlan.coverage.benefit.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InsurancePlan.coverage.benefit.requirement` | `InsurancePlan.coverage.benefit.requirement` | `requirement` | InsurancePlan.coverage.benefit.requirement | Referral requirements | 0..1 | string |  |  |
| `InsurancePlan.coverage.benefit.type` | `InsurancePlan.coverage.benefit.type` | `type` | InsurancePlan.coverage.benefit.type | Type of benefit | 1..1 | CodeableConcept |  |  |
| `InsurancePlan.coverage.extension` | `InsurancePlan.coverage.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InsurancePlan.coverage.id` | `InsurancePlan.coverage.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InsurancePlan.coverage.modifierExtension` | `InsurancePlan.coverage.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InsurancePlan.coverage.network` | `InsurancePlan.coverage.network` | `network` | InsurancePlan.coverage.network | What networks provide coverage | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `InsurancePlan.coverage.type` | `InsurancePlan.coverage.type` | `type` | InsurancePlan.coverage.type | Type of coverage | 1..1 | CodeableConcept |  |  |
| `InsurancePlan.coverageArea` | `InsurancePlan.coverageArea` | `coverageArea` | InsurancePlan.coverageArea | Where product applies | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `InsurancePlan.endpoint` | `InsurancePlan.endpoint` | `endpoint` | InsurancePlan.endpoint | Technical endpoint | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Endpoint) |  |  |
| `InsurancePlan.extension` | `InsurancePlan.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InsurancePlan.id` | `InsurancePlan.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `InsurancePlan.identifier` | `InsurancePlan.identifier` | `identifier` | InsurancePlan.identifier | Business Identifier for Product | 0..* | Identifier |  |  |
| `InsurancePlan.implicitRules` | `InsurancePlan.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `InsurancePlan.language` | `InsurancePlan.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `InsurancePlan.meta` | `InsurancePlan.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `InsurancePlan.modifierExtension` | `InsurancePlan.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `InsurancePlan.name` | `InsurancePlan.name` | `name` | InsurancePlan.name | Official name | 0..1 | string |  |  |
| `InsurancePlan.network` | `InsurancePlan.network` | `network` | InsurancePlan.network | What networks are Included | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `InsurancePlan.ownedBy` | `InsurancePlan.ownedBy` | `ownedBy` | InsurancePlan.ownedBy | Product issuer | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `InsurancePlan.period` | `InsurancePlan.period` | `period` | InsurancePlan.period | When the product is available | 0..1 | Period |  |  |
| `InsurancePlan.plan` | `InsurancePlan.plan` | `plan` | InsurancePlan.plan | Plan details | 0..* | BackboneElement |  |  |
| `InsurancePlan.plan.coverageArea` | `InsurancePlan.plan.coverageArea` | `coverageArea` | InsurancePlan.plan.coverageArea | Where product applies | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `InsurancePlan.plan.extension` | `InsurancePlan.plan.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InsurancePlan.plan.generalCost` | `InsurancePlan.plan.generalCost` | `generalCost` | InsurancePlan.plan.generalCost | Overall costs | 0..* | BackboneElement |  |  |
| `InsurancePlan.plan.generalCost.comment` | `InsurancePlan.plan.generalCost.comment` | `comment` | InsurancePlan.plan.generalCost.comment | Additional cost information | 0..1 | string |  |  |
| `InsurancePlan.plan.generalCost.cost` | `InsurancePlan.plan.generalCost.cost` | `cost` | InsurancePlan.plan.generalCost.cost | Cost value | 0..1 | Money |  |  |
| `InsurancePlan.plan.generalCost.extension` | `InsurancePlan.plan.generalCost.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InsurancePlan.plan.generalCost.groupSize` | `InsurancePlan.plan.generalCost.groupSize` | `groupSize` | InsurancePlan.plan.generalCost.groupSize | Number of enrollees | 0..1 | positiveInt |  |  |
| `InsurancePlan.plan.generalCost.id` | `InsurancePlan.plan.generalCost.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InsurancePlan.plan.generalCost.modifierExtension` | `InsurancePlan.plan.generalCost.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InsurancePlan.plan.generalCost.type` | `InsurancePlan.plan.generalCost.type` | `type` | InsurancePlan.plan.generalCost.type | Type of cost | 0..1 | CodeableConcept |  |  |
| `InsurancePlan.plan.id` | `InsurancePlan.plan.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InsurancePlan.plan.identifier` | `InsurancePlan.plan.identifier` | `identifier` | InsurancePlan.plan.identifier | Business Identifier for Product | 0..* | Identifier |  |  |
| `InsurancePlan.plan.modifierExtension` | `InsurancePlan.plan.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InsurancePlan.plan.network` | `InsurancePlan.plan.network` | `network` | InsurancePlan.plan.network | What networks provide coverage | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `InsurancePlan.plan.specificCost` | `InsurancePlan.plan.specificCost` | `specificCost` | InsurancePlan.plan.specificCost | Specific costs | 0..* | BackboneElement |  |  |
| `InsurancePlan.plan.specificCost.benefit` | `InsurancePlan.plan.specificCost.benefit` | `benefit` | InsurancePlan.plan.specificCost.benefit | Benefits list | 0..* | BackboneElement |  |  |
| `InsurancePlan.plan.specificCost.benefit.cost` | `InsurancePlan.plan.specificCost.benefit.cost` | `cost` | InsurancePlan.plan.specificCost.benefit.cost | List of the costs | 0..* | BackboneElement |  |  |
| `InsurancePlan.plan.specificCost.benefit.cost.applicability` | `InsurancePlan.plan.specificCost.benefit.cost.applicability` | `applicability` | InsurancePlan.plan.specificCost.benefit.cost.applicability | in-network \| out-of-network \| other | 0..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/insuranceplan-applicability|5.0.0` |
| `InsurancePlan.plan.specificCost.benefit.cost.extension` | `InsurancePlan.plan.specificCost.benefit.cost.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InsurancePlan.plan.specificCost.benefit.cost.id` | `InsurancePlan.plan.specificCost.benefit.cost.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InsurancePlan.plan.specificCost.benefit.cost.modifierExtension` | `InsurancePlan.plan.specificCost.benefit.cost.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InsurancePlan.plan.specificCost.benefit.cost.qualifiers` | `InsurancePlan.plan.specificCost.benefit.cost.qualifiers` | `qualifiers` | InsurancePlan.plan.specificCost.benefit.cost.qualifiers | Additional information about the cost | 0..* | CodeableConcept |  |  |
| `InsurancePlan.plan.specificCost.benefit.cost.type` | `InsurancePlan.plan.specificCost.benefit.cost.type` | `type` | InsurancePlan.plan.specificCost.benefit.cost.type | Type of cost | 1..1 | CodeableConcept |  |  |
| `InsurancePlan.plan.specificCost.benefit.cost.value` | `InsurancePlan.plan.specificCost.benefit.cost.value` | `value` | InsurancePlan.plan.specificCost.benefit.cost.value | The actual cost value | 0..1 | Quantity |  |  |
| `InsurancePlan.plan.specificCost.benefit.extension` | `InsurancePlan.plan.specificCost.benefit.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InsurancePlan.plan.specificCost.benefit.id` | `InsurancePlan.plan.specificCost.benefit.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InsurancePlan.plan.specificCost.benefit.modifierExtension` | `InsurancePlan.plan.specificCost.benefit.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InsurancePlan.plan.specificCost.benefit.type` | `InsurancePlan.plan.specificCost.benefit.type` | `type` | InsurancePlan.plan.specificCost.benefit.type | Type of specific benefit | 1..1 | CodeableConcept |  |  |
| `InsurancePlan.plan.specificCost.category` | `InsurancePlan.plan.specificCost.category` | `category` | InsurancePlan.plan.specificCost.category | General category of benefit | 1..1 | CodeableConcept |  |  |
| `InsurancePlan.plan.specificCost.extension` | `InsurancePlan.plan.specificCost.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InsurancePlan.plan.specificCost.id` | `InsurancePlan.plan.specificCost.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InsurancePlan.plan.specificCost.modifierExtension` | `InsurancePlan.plan.specificCost.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InsurancePlan.plan.type` | `InsurancePlan.plan.type` | `type` | InsurancePlan.plan.type | Type of plan | 0..1 | CodeableConcept |  |  |
| `InsurancePlan.status` | `InsurancePlan.status` | `status` | InsurancePlan.status | draft \| active \| retired \| unknown | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `InsurancePlan.text` | `InsurancePlan.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `InsurancePlan.type` | `InsurancePlan.type` | `type` | InsurancePlan.type | Kind of product | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/insuranceplan-type` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [InsurancePlan](/docs/R4/Resources/InsurancePlan.md)<br/> `http://hl7.org/fhir/StructureDefinition/InsurancePlan\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1517`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1518`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [InsurancePlan](/docs/R4B/Resources/InsurancePlan.md)<br/> `http://hl7.org/fhir/StructureDefinition/InsurancePlan\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `993`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1222`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [InsurancePlan](/docs/R5/Resources/InsurancePlan.md)<br/> `http://hl7.org/fhir/StructureDefinition/InsurancePlan\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition InsurancePlan from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 InsurancePlan](/docs/R4/Resources/InsurancePlan.md)| Relationship | [R4B InsurancePlan](/docs/R4B/Resources/InsurancePlan.md)| Relationship | R5 InsurancePlan
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `InsurancePlan`| _Equivalent_<br/>(28551/28552)| `InsurancePlan`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(43442)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(43443)| **`InsurancePlan`**
| | | | | `InsurancePlan.id`| _Equivalent_<br/>(28553/28554)| `InsurancePlan.id`| _Equivalent_<br/>(43444/43445)| **`InsurancePlan.id`**
| | | | | `InsurancePlan.meta`| _Equivalent_<br/>(28555/28556)| `InsurancePlan.meta`| _Equivalent_<br/>(43446/43447)| **`InsurancePlan.meta`**
| | | | | `InsurancePlan.implicitRules`| _Equivalent_<br/>(28557/28558)| `InsurancePlan.implicitRules`| _Equivalent_<br/>(43448/43449)| **`InsurancePlan.implicitRules`**
| | | | | `InsurancePlan.language`| _Equivalent_<br/>(28559/28560)| `InsurancePlan.language`| _Equivalent_<br/>(43450/43451)| **`InsurancePlan.language`**
| | | | | `InsurancePlan.text`| _Equivalent_<br/>(28561/28562)| `InsurancePlan.text`| _Equivalent_<br/>(43452/43453)| **`InsurancePlan.text`**
| | | | | `InsurancePlan.contained`| _Equivalent_<br/>(28563/28564)| `InsurancePlan.contained`| _Equivalent_<br/>(43454/43455)| **`InsurancePlan.contained`**
| | | | | `InsurancePlan.extension`| _Equivalent_<br/>(28565/28566)| `InsurancePlan.extension`| _Equivalent_<br/>(43456/43457)| **`InsurancePlan.extension`**
| | | | | `InsurancePlan.modifierExtension`| _Equivalent_<br/>(28567/28568)| `InsurancePlan.modifierExtension`| _Equivalent_<br/>(43458/43459)| **`InsurancePlan.modifierExtension`**
| | | | | `InsurancePlan.identifier`| _Equivalent_<br/>(28569/28570)| `InsurancePlan.identifier`| _Equivalent_<br/>(43460/43461)| **`InsurancePlan.identifier`**
| | | | | `InsurancePlan.status`| _Equivalent_<br/>(28571/28572)| `InsurancePlan.status`| _Equivalent_<br/>(43462/43463)| **`InsurancePlan.status`**
| | | | | `InsurancePlan.type`| _Equivalent_<br/>(28573/28574)| `InsurancePlan.type`| _Equivalent_<br/>(43464/43465)| **`InsurancePlan.type`**
| | | | | `InsurancePlan.name`| _Equivalent_<br/>(28575/28576)| `InsurancePlan.name`| _Equivalent_<br/>(43466/43467)| **`InsurancePlan.name`**
| | | | | `InsurancePlan.alias`| _Equivalent_<br/>(28577/28578)| `InsurancePlan.alias`| _Equivalent_<br/>(43468/43469)| **`InsurancePlan.alias`**
| | | | | `InsurancePlan.period`| _Equivalent_<br/>(28579/28580)| `InsurancePlan.period`| _Equivalent_<br/>(43470/43471)| **`InsurancePlan.period`**
| | | | | `InsurancePlan.ownedBy`| _Equivalent_<br/>(28581/28582)| `InsurancePlan.ownedBy`| _Equivalent_<br/>(43472/43473)| **`InsurancePlan.ownedBy`**
| | | | | `InsurancePlan.administeredBy`| _Equivalent_<br/>(28583/28584)| `InsurancePlan.administeredBy`| _Equivalent_<br/>(43474/43475)| **`InsurancePlan.administeredBy`**
| | | | | `InsurancePlan.coverageArea`| _Equivalent_<br/>(28585/28586)| `InsurancePlan.coverageArea`| _Equivalent_<br/>(43476/43477)| **`InsurancePlan.coverageArea`**
| | | | | `InsurancePlan.contact`| _Equivalent_<br/>(28587/28588)| `InsurancePlan.contact`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(43478)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43479)| **`InsurancePlan.contact`**
| | | | | `InsurancePlan.endpoint`| _Equivalent_<br/>(28603/28604)| `InsurancePlan.endpoint`| _Equivalent_<br/>(43487/43488)| **`InsurancePlan.endpoint`**
| | | | | `InsurancePlan.network`| _Equivalent_<br/>(28605/28606)| `InsurancePlan.network`| _Equivalent_<br/>(43489/43490)| **`InsurancePlan.network`**
| | | | | `InsurancePlan.coverage`| _Equivalent_<br/>(28607/28608)| `InsurancePlan.coverage`| _Equivalent_<br/>(43491/43492)| **`InsurancePlan.coverage`**
| | | | | `InsurancePlan.coverage.id`| _Equivalent_<br/>(28609/28610)| `InsurancePlan.coverage.id`| _Equivalent_<br/>(43493/43494)| **`InsurancePlan.coverage.id`**
| | | | | `InsurancePlan.coverage.extension`| _Equivalent_<br/>(28611/28612)| `InsurancePlan.coverage.extension`| _Equivalent_<br/>(43495/43496)| **`InsurancePlan.coverage.extension`**
| | | | | `InsurancePlan.coverage.modifierExtension`| _Equivalent_<br/>(28613/28614)| `InsurancePlan.coverage.modifierExtension`| _Equivalent_<br/>(43497/43498)| **`InsurancePlan.coverage.modifierExtension`**
| | | | | `InsurancePlan.coverage.type`| _Equivalent_<br/>(28615/28616)| `InsurancePlan.coverage.type`| _Equivalent_<br/>(43499/43500)| **`InsurancePlan.coverage.type`**
| | | | | `InsurancePlan.coverage.network`| _Equivalent_<br/>(28617/28618)| `InsurancePlan.coverage.network`| _Equivalent_<br/>(43501/43502)| **`InsurancePlan.coverage.network`**
| | | | | `InsurancePlan.coverage.benefit`| _Equivalent_<br/>(28619/28620)| `InsurancePlan.coverage.benefit`| _Equivalent_<br/>(43503/43504)| **`InsurancePlan.coverage.benefit`**
| | | | | `InsurancePlan.coverage.benefit.id`| _Equivalent_<br/>(28621/28622)| `InsurancePlan.coverage.benefit.id`| _Equivalent_<br/>(43505/43506)| **`InsurancePlan.coverage.benefit.id`**
| | | | | `InsurancePlan.coverage.benefit.extension`| _Equivalent_<br/>(28623/28624)| `InsurancePlan.coverage.benefit.extension`| _Equivalent_<br/>(43507/43508)| **`InsurancePlan.coverage.benefit.extension`**
| | | | | `InsurancePlan.coverage.benefit.modifierExtension`| _Equivalent_<br/>(28625/28626)| `InsurancePlan.coverage.benefit.modifierExtension`| _Equivalent_<br/>(43509/43510)| **`InsurancePlan.coverage.benefit.modifierExtension`**
| | | | | `InsurancePlan.coverage.benefit.type`| _Equivalent_<br/>(28627/28628)| `InsurancePlan.coverage.benefit.type`| _Equivalent_<br/>(43511/43512)| **`InsurancePlan.coverage.benefit.type`**
| | | | | `InsurancePlan.coverage.benefit.requirement`| _Equivalent_<br/>(28629/28630)| `InsurancePlan.coverage.benefit.requirement`| _Equivalent_<br/>(43513/43514)| **`InsurancePlan.coverage.benefit.requirement`**
| | | | | `InsurancePlan.coverage.benefit.limit`| _Equivalent_<br/>(28631/28632)| `InsurancePlan.coverage.benefit.limit`| _Equivalent_<br/>(43515/43516)| **`InsurancePlan.coverage.benefit.limit`**
| | | | | `InsurancePlan.coverage.benefit.limit.id`| _Equivalent_<br/>(28633/28634)| `InsurancePlan.coverage.benefit.limit.id`| _Equivalent_<br/>(43517/43518)| **`InsurancePlan.coverage.benefit.limit.id`**
| | | | | `InsurancePlan.coverage.benefit.limit.extension`| _Equivalent_<br/>(28635/28636)| `InsurancePlan.coverage.benefit.limit.extension`| _Equivalent_<br/>(43519/43520)| **`InsurancePlan.coverage.benefit.limit.extension`**
| | | | | `InsurancePlan.coverage.benefit.limit.modifierExtension`| _Equivalent_<br/>(28637/28638)| `InsurancePlan.coverage.benefit.limit.modifierExtension`| _Equivalent_<br/>(43521/43522)| **`InsurancePlan.coverage.benefit.limit.modifierExtension`**
| | | | | `InsurancePlan.coverage.benefit.limit.value`| _Equivalent_<br/>(28639/28640)| `InsurancePlan.coverage.benefit.limit.value`| _Equivalent_<br/>(43523/43524)| **`InsurancePlan.coverage.benefit.limit.value`**
| | | | | `InsurancePlan.coverage.benefit.limit.code`| _Equivalent_<br/>(28641/28642)| `InsurancePlan.coverage.benefit.limit.code`| _Equivalent_<br/>(43525/43526)| **`InsurancePlan.coverage.benefit.limit.code`**
| | | | | `InsurancePlan.plan`| _Equivalent_<br/>(28643/28644)| `InsurancePlan.plan`| _Equivalent_<br/>(43527/43528)| **`InsurancePlan.plan`**
| | | | | `InsurancePlan.plan.id`| _Equivalent_<br/>(28645/28646)| `InsurancePlan.plan.id`| _Equivalent_<br/>(43529/43530)| **`InsurancePlan.plan.id`**
| | | | | `InsurancePlan.plan.extension`| _Equivalent_<br/>(28647/28648)| `InsurancePlan.plan.extension`| _Equivalent_<br/>(43531/43532)| **`InsurancePlan.plan.extension`**
| | | | | `InsurancePlan.plan.modifierExtension`| _Equivalent_<br/>(28649/28650)| `InsurancePlan.plan.modifierExtension`| _Equivalent_<br/>(43533/43534)| **`InsurancePlan.plan.modifierExtension`**
| | | | | `InsurancePlan.plan.identifier`| _Equivalent_<br/>(28651/28652)| `InsurancePlan.plan.identifier`| _Equivalent_<br/>(43535/43536)| **`InsurancePlan.plan.identifier`**
| | | | | `InsurancePlan.plan.type`| _Equivalent_<br/>(28653/28654)| `InsurancePlan.plan.type`| _Equivalent_<br/>(43537/43538)| **`InsurancePlan.plan.type`**
| | | | | `InsurancePlan.plan.coverageArea`| _Equivalent_<br/>(28655/28656)| `InsurancePlan.plan.coverageArea`| _Equivalent_<br/>(43539/43540)| **`InsurancePlan.plan.coverageArea`**
| | | | | `InsurancePlan.plan.network`| _Equivalent_<br/>(28657/28658)| `InsurancePlan.plan.network`| _Equivalent_<br/>(43541/43542)| **`InsurancePlan.plan.network`**
| | | | | `InsurancePlan.plan.generalCost`| _Equivalent_<br/>(28659/28660)| `InsurancePlan.plan.generalCost`| _Equivalent_<br/>(43543/43544)| **`InsurancePlan.plan.generalCost`**
| | | | | `InsurancePlan.plan.generalCost.id`| _Equivalent_<br/>(28661/28662)| `InsurancePlan.plan.generalCost.id`| _Equivalent_<br/>(43545/43546)| **`InsurancePlan.plan.generalCost.id`**
| | | | | `InsurancePlan.plan.generalCost.extension`| _Equivalent_<br/>(28663/28664)| `InsurancePlan.plan.generalCost.extension`| _Equivalent_<br/>(43547/43548)| **`InsurancePlan.plan.generalCost.extension`**
| | | | | `InsurancePlan.plan.generalCost.modifierExtension`| _Equivalent_<br/>(28665/28666)| `InsurancePlan.plan.generalCost.modifierExtension`| _Equivalent_<br/>(43549/43550)| **`InsurancePlan.plan.generalCost.modifierExtension`**
| | | | | `InsurancePlan.plan.generalCost.type`| _Equivalent_<br/>(28667/28668)| `InsurancePlan.plan.generalCost.type`| _Equivalent_<br/>(43551/43552)| **`InsurancePlan.plan.generalCost.type`**
| | | | | `InsurancePlan.plan.generalCost.groupSize`| _Equivalent_<br/>(28669/28670)| `InsurancePlan.plan.generalCost.groupSize`| _Equivalent_<br/>(43553/43554)| **`InsurancePlan.plan.generalCost.groupSize`**
| | | | | `InsurancePlan.plan.generalCost.cost`| _Equivalent_<br/>(28671/28672)| `InsurancePlan.plan.generalCost.cost`| _Equivalent_<br/>(43555/43556)| **`InsurancePlan.plan.generalCost.cost`**
| | | | | `InsurancePlan.plan.generalCost.comment`| _Equivalent_<br/>(28673/28674)| `InsurancePlan.plan.generalCost.comment`| _Equivalent_<br/>(43557/43558)| **`InsurancePlan.plan.generalCost.comment`**
| | | | | `InsurancePlan.plan.specificCost`| _Equivalent_<br/>(28675/28676)| `InsurancePlan.plan.specificCost`| _Equivalent_<br/>(43559/43560)| **`InsurancePlan.plan.specificCost`**
| | | | | `InsurancePlan.plan.specificCost.id`| _Equivalent_<br/>(28677/28678)| `InsurancePlan.plan.specificCost.id`| _Equivalent_<br/>(43561/43562)| **`InsurancePlan.plan.specificCost.id`**
| | | | | `InsurancePlan.plan.specificCost.extension`| _Equivalent_<br/>(28679/28680)| `InsurancePlan.plan.specificCost.extension`| _Equivalent_<br/>(43563/43564)| **`InsurancePlan.plan.specificCost.extension`**
| | | | | `InsurancePlan.plan.specificCost.modifierExtension`| _Equivalent_<br/>(28681/28682)| `InsurancePlan.plan.specificCost.modifierExtension`| _Equivalent_<br/>(43565/43566)| **`InsurancePlan.plan.specificCost.modifierExtension`**
| | | | | `InsurancePlan.plan.specificCost.category`| _Equivalent_<br/>(28683/28684)| `InsurancePlan.plan.specificCost.category`| _Equivalent_<br/>(43567/43568)| **`InsurancePlan.plan.specificCost.category`**
| | | | | `InsurancePlan.plan.specificCost.benefit`| _Equivalent_<br/>(28685/28686)| `InsurancePlan.plan.specificCost.benefit`| _Equivalent_<br/>(43569/43570)| **`InsurancePlan.plan.specificCost.benefit`**
| | | | | `InsurancePlan.plan.specificCost.benefit.id`| _Equivalent_<br/>(28687/28688)| `InsurancePlan.plan.specificCost.benefit.id`| _Equivalent_<br/>(43571/43572)| **`InsurancePlan.plan.specificCost.benefit.id`**
| | | | | `InsurancePlan.plan.specificCost.benefit.extension`| _Equivalent_<br/>(28689/28690)| `InsurancePlan.plan.specificCost.benefit.extension`| _Equivalent_<br/>(43573/43574)| **`InsurancePlan.plan.specificCost.benefit.extension`**
| | | | | `InsurancePlan.plan.specificCost.benefit.modifierExtension`| _Equivalent_<br/>(28691/28692)| `InsurancePlan.plan.specificCost.benefit.modifierExtension`| _Equivalent_<br/>(43575/43576)| **`InsurancePlan.plan.specificCost.benefit.modifierExtension`**
| | | | | `InsurancePlan.plan.specificCost.benefit.type`| _Equivalent_<br/>(28693/28694)| `InsurancePlan.plan.specificCost.benefit.type`| _Equivalent_<br/>(43577/43578)| **`InsurancePlan.plan.specificCost.benefit.type`**
| | | | | `InsurancePlan.plan.specificCost.benefit.cost`| _Equivalent_<br/>(28695/28696)| `InsurancePlan.plan.specificCost.benefit.cost`| _Equivalent_<br/>(43579/43580)| **`InsurancePlan.plan.specificCost.benefit.cost`**
| | | | | `InsurancePlan.plan.specificCost.benefit.cost.id`| _Equivalent_<br/>(28697/28698)| `InsurancePlan.plan.specificCost.benefit.cost.id`| _Equivalent_<br/>(43581/43582)| **`InsurancePlan.plan.specificCost.benefit.cost.id`**
| | | | | `InsurancePlan.plan.specificCost.benefit.cost.extension`| _Equivalent_<br/>(28699/28700)| `InsurancePlan.plan.specificCost.benefit.cost.extension`| _Equivalent_<br/>(43583/43584)| **`InsurancePlan.plan.specificCost.benefit.cost.extension`**
| | | | | `InsurancePlan.plan.specificCost.benefit.cost.modifierExtension`| _Equivalent_<br/>(28701/28702)| `InsurancePlan.plan.specificCost.benefit.cost.modifierExtension`| _Equivalent_<br/>(43585/43586)| **`InsurancePlan.plan.specificCost.benefit.cost.modifierExtension`**
| | | | | `InsurancePlan.plan.specificCost.benefit.cost.type`| _Equivalent_<br/>(28703/28704)| `InsurancePlan.plan.specificCost.benefit.cost.type`| _Equivalent_<br/>(43587/43588)| **`InsurancePlan.plan.specificCost.benefit.cost.type`**
| | | | | `InsurancePlan.plan.specificCost.benefit.cost.applicability`| _Equivalent_<br/>(28705/28706)| `InsurancePlan.plan.specificCost.benefit.cost.applicability`| _Equivalent_<br/>(43589/43590)| **`InsurancePlan.plan.specificCost.benefit.cost.applicability`**
| | | | | `InsurancePlan.plan.specificCost.benefit.cost.qualifiers`| _Equivalent_<br/>(28707/28708)| `InsurancePlan.plan.specificCost.benefit.cost.qualifiers`| _Equivalent_<br/>(43591/43592)| **`InsurancePlan.plan.specificCost.benefit.cost.qualifiers`**
| | | | | `InsurancePlan.plan.specificCost.benefit.cost.value`| _Equivalent_<br/>(28709/28710)| `InsurancePlan.plan.specificCost.benefit.cost.value`| _Equivalent_<br/>(43593/43594)| **`InsurancePlan.plan.specificCost.benefit.cost.value`**
| | | | | *73 of 80 elements used* <br/>remaining elements:<br/>`InsurancePlan.contact.address`, `InsurancePlan.contact.extension`, `InsurancePlan.contact.id`, `InsurancePlan.contact.modifierExtension`, `InsurancePlan.contact.name`, `InsurancePlan.contact.purpose`, `InsurancePlan.contact.telecom`| | *73 of 80 elements used* <br/>remaining elements:<br/>`InsurancePlan.contact.address`, `InsurancePlan.contact.extension`, `InsurancePlan.contact.id`, `InsurancePlan.contact.modifierExtension`, `InsurancePlan.contact.name`, `InsurancePlan.contact.purpose`, `InsurancePlan.contact.telecom`| | *73 of 73 elements used* 

