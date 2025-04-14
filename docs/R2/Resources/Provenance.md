Comparison of 
Generated at Monday, April 14, 2025 6:17:17 PM

### Provenance

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Provenance |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Provenance` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Provenance Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `118` |
| Database Snapshot Count | `39` |
| Database Differential Count | `22` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Provenance` | `Provenance` | `Provenance` | Provenance | Who, What, When for a set of resources | 0..* | Provenance |  |  |
| `Provenance.activity` | `Provenance.activity` | `activity` |  | Activity that occurred | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/v3-ProvenanceEventCurrentState` |
| `Provenance.agent` | `Provenance.agent` | `agent` |  | Agents involved in creating resource | 0..* | BackboneElement |  |  |
| `Provenance.agent.actor` | `Provenance.agent.actor` | `actor` |  | Individual, device or organization playing role | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Provenance.agent.extension` | `Provenance.agent.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Provenance.agent.id` | `Provenance.agent.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Provenance.agent.modifierExtension` | `Provenance.agent.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Provenance.agent.relatedAgent` | `Provenance.agent.relatedAgent` | `relatedAgent` |  | Track delegation between agents | 0..* | BackboneElement |  |  |
| `Provenance.agent.relatedAgent.extension` | `Provenance.agent.relatedAgent.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Provenance.agent.relatedAgent.id` | `Provenance.agent.relatedAgent.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Provenance.agent.relatedAgent.modifierExtension` | `Provenance.agent.relatedAgent.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Provenance.agent.relatedAgent.target` | `Provenance.agent.relatedAgent.target` | `target` |  | Reference to other agent in this resource by identifier | 1..1 | uri |  |  |
| `Provenance.agent.relatedAgent.type` | `Provenance.agent.relatedAgent.type` | `type` |  | Type of relationship between agents | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/v3-RoleLinkType` |
| `Provenance.agent.role` | `Provenance.agent.role` | `role` |  | What the agents involvement was | 1..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/provenance-agent-role` |
| `Provenance.agent.userId` | `Provenance.agent.userId` | `userId` |  | Authorization-system identifier for the agent | 0..1 | Identifier |  |  |
| `Provenance.contained` | `Provenance.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Provenance.entity` | `Provenance.entity` | `entity` |  | An entity used in this activity | 0..* | BackboneElement |  |  |
| `Provenance.entity.agent` | `Provenance.entity.agent` | `agent` |  | Entity is attributed to this agent | 0..1 | Provenance.agent |  |  |
| `Provenance.entity.display` | `Provenance.entity.display` | `display` |  | Human description of entity | 0..1 | string |  |  |
| `Provenance.entity.extension` | `Provenance.entity.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Provenance.entity.id` | `Provenance.entity.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Provenance.entity.modifierExtension` | `Provenance.entity.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Provenance.entity.reference` | `Provenance.entity.reference` | `reference` |  | Identity of entity | 1..1 | uri |  |  |
| `Provenance.entity.role` | `Provenance.entity.role` | `role` |  | derivation \| revision \| quotation \| source | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/provenance-entity-role` |
| `Provenance.entity.type` | `Provenance.entity.type` | `type` |  | The type of resource in this entity | 1..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/resource-types` |
| `Provenance.extension` | `Provenance.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Provenance.id` | `Provenance.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Provenance.implicitRules` | `Provenance.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Provenance.language` | `Provenance.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Provenance.location` | `Provenance.location` | `location` |  | Where the activity occurred, if relevant | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `Provenance.meta` | `Provenance.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Provenance.modifierExtension` | `Provenance.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Provenance.period` | `Provenance.period` | `period` |  | When the activity occurred | 0..1 | Period |  |  |
| `Provenance.policy` | `Provenance.policy` | `policy` |  | Policy or plan the activity was defined by | 0..* | uri |  |  |
| `Provenance.reason` | `Provenance.reason` | `reason` |  | Reason the activity is occurring | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse` |
| `Provenance.recorded` | `Provenance.recorded` | `recorded` |  | When the activity was recorded / updated | 1..1 | instant |  |  |
| `Provenance.signature` | `Provenance.signature` | `signature` |  | Signature on target | 0..* | Signature |  |  |
| `Provenance.target` | `Provenance.target` | `target` |  | Target Reference(s) (usually version specific) | 1..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Provenance.text` | `Provenance.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Provenance](/docs/R2/Resources/Provenance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Provenance\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `147`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `313`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Provenance](/docs/R3/Resources/Provenance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Provenance\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `504`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `697`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Provenance](/docs/R4/Resources/Provenance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Provenance\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1587`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1588`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Provenance](/docs/R4B/Resources/Provenance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Provenance\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1029`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1258`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Provenance](/docs/R5/Resources/Provenance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Provenance\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Provenance from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Provenance| Relationship | [R3 Provenance](/docs/R3/Resources/Provenance.md)| Relationship | [R4 Provenance](/docs/R4/Resources/Provenance.md)| Relationship | [R4B Provenance](/docs/R4B/Resources/Provenance.md)| Relationship | [R5 Provenance](/docs/R5/Resources/Provenance.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Provenance`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7437)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7438)| `Provenance`| _Equivalent_<br/>(17591/17592)| `Provenance`| _Equivalent_<br/>(31997/31998)| `Provenance`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(46579)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(46580)| `Provenance`
| **`Provenance.id`**| _Equivalent_<br/>(7439/7440)| `Provenance.id`| _Equivalent_<br/>(17593/17594)| `Provenance.id`| _Equivalent_<br/>(31999/32000)| `Provenance.id`| _Equivalent_<br/>(46581/46582)| `Provenance.id`
| **`Provenance.meta`**| _Equivalent_<br/>(7441/7442)| `Provenance.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17595)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17596)| `Provenance.meta`| _Equivalent_<br/>(32001/32002)| `Provenance.meta`| _Equivalent_<br/>(46583/46584)| `Provenance.meta`
| **`Provenance.implicitRules`**| _Equivalent_<br/>(7443/7444)| `Provenance.implicitRules`| _Equivalent_<br/>(17597/17598)| `Provenance.implicitRules`| _Equivalent_<br/>(32003/32004)| `Provenance.implicitRules`| _Equivalent_<br/>(46585/46586)| `Provenance.implicitRules`
| **`Provenance.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7445)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7446)| `Provenance.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17599)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(17600)| `Provenance.language`| _Equivalent_<br/>(32005/32006)| `Provenance.language`| _Equivalent_<br/>(46587/46588)| `Provenance.language`
| **`Provenance.text`**| _Equivalent_<br/>(7447/7448)| `Provenance.text`| _Equivalent_<br/>(17601/17602)| `Provenance.text`| _Equivalent_<br/>(32007/32008)| `Provenance.text`| _Equivalent_<br/>(46589/46590)| `Provenance.text`
| **`Provenance.contained`**| _Equivalent_<br/>(7449/7450)| `Provenance.contained`| _Equivalent_<br/>(17603/17604)| `Provenance.contained`| _Equivalent_<br/>(32009/32010)| `Provenance.contained`| _Equivalent_<br/>(46591/46592)| `Provenance.contained`
| **`Provenance.extension`**| _Equivalent_<br/>(7451/7452)| `Provenance.extension`| _Equivalent_<br/>(17605/17606)| `Provenance.extension`| _Equivalent_<br/>(32011/32012)| `Provenance.extension`| _Equivalent_<br/>(46593/46594)| `Provenance.extension`
| **`Provenance.modifierExtension`**| _Equivalent_<br/>(7453/7454)| `Provenance.modifierExtension`| _Equivalent_<br/>(17607/17608)| `Provenance.modifierExtension`| _Equivalent_<br/>(32013/32014)| `Provenance.modifierExtension`| _Equivalent_<br/>(46595/46596)| `Provenance.modifierExtension`
| **`Provenance.target`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7455)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7456)| `Provenance.target`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17609)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17610)| `Provenance.target`| _Equivalent_<br/>(32015/32016)| `Provenance.target`| _Equivalent_<br/>(46597/46598)| `Provenance.target`
| **`Provenance.period`**| _Equivalent_<br/>(7457/7458)| `Provenance.period`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1245)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1643)| `Provenance.occurred[x]`| _Equivalent_<br/>(32017/32018)| `Provenance.occurred[x]`| _Equivalent_<br/>(46599/46600)| `Provenance.occurred[x]`
| **`Provenance.recorded`**| _Equivalent_<br/>(7459/7460)| `Provenance.recorded`| _Equivalent_<br/>(17611/17612)| `Provenance.recorded`| _Equivalent_<br/>(32019/32020)| `Provenance.recorded`| →→→→ _Equivalent_ →→→→ <br/>(46601)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(46602)| `Provenance.recorded`
| **`Provenance.reason`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7461)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7462)| `Provenance.reason`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(17617)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17618)| `Provenance.reason`| _Equivalent_<br/>(32025/32026)| `Provenance.reason`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1847)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2090)| `Provenance.authorization`
| **`Provenance.activity`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7463)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7464)| `Provenance.activity`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(17619)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17620)| `Provenance.activity`| _Equivalent_<br/>(32027/32028)| `Provenance.activity`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(46607)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(46608)| `Provenance.activity`
| **`Provenance.location`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7465)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7466)| `Provenance.location`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17615)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17616)| `Provenance.location`| _Equivalent_<br/>(32023/32024)| `Provenance.location`| _Equivalent_<br/>(46605/46606)| `Provenance.location`
| **`Provenance.policy`**| _Equivalent_<br/>(7467/7468)| `Provenance.policy`| _Equivalent_<br/>(17613/17614)| `Provenance.policy`| _Equivalent_<br/>(32021/32022)| `Provenance.policy`| _Equivalent_<br/>(46603/46604)| `Provenance.policy`
| **`Provenance.agent`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7469)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7470)| `Provenance.agent`| _Equivalent_<br/>(17621/17622)| `Provenance.agent`| _Equivalent_<br/>(32029/32030)| `Provenance.agent`| _Equivalent_<br/>(46609/46610)| `Provenance.agent`
| **`Provenance.agent.id`**| _Equivalent_<br/>(7471/7472)| `Provenance.agent.id`| _Equivalent_<br/>(17623/17624)| `Provenance.agent.id`| _Equivalent_<br/>(32031/32032)| `Provenance.agent.id`| _Equivalent_<br/>(46611/46612)| `Provenance.agent.id`
| **`Provenance.agent.extension`**| _Equivalent_<br/>(7473/7474)| `Provenance.agent.extension`| _Equivalent_<br/>(17625/17626)| `Provenance.agent.extension`| _Equivalent_<br/>(32033/32034)| `Provenance.agent.extension`| _Equivalent_<br/>(46613/46614)| `Provenance.agent.extension`
| **`Provenance.agent.modifierExtension`**| _Equivalent_<br/>(7475/7476)| `Provenance.agent.modifierExtension`| _Equivalent_<br/>(17627/17628)| `Provenance.agent.modifierExtension`| _Equivalent_<br/>(32035/32036)| `Provenance.agent.modifierExtension`| _Equivalent_<br/>(46615/46616)| `Provenance.agent.modifierExtension`
| **`Provenance.agent.role`**| →→→→ _RelatedTo_ →→→→ <br/>(7477)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7478)| `Provenance.agent.role`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17629)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17630)| `Provenance.agent.role`| _Equivalent_<br/>(32039/32040)| `Provenance.agent.role`| _Equivalent_<br/>(46619/46620)| `Provenance.agent.role`
| **`Provenance.agent.actor`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(354)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(706)| `Provenance.agent.who[x]`| →→→→ _RelatedTo_ →→→→ <br/>(1243)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1641)| `Provenance.agent.who`| _Equivalent_<br/>(32041/32042)| `Provenance.agent.who`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(46621)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(46622)| `Provenance.agent.who`
| **`Provenance.agent.userId`**| | | | | | | | | 
| **`Provenance.agent.relatedAgent`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(355)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(704)| `Provenance.agent`| _Equivalent_<br/>(17621/17622)| `Provenance.agent`| _Equivalent_<br/>(32029/32030)| `Provenance.agent`| _Equivalent_<br/>(46609/46610)| `Provenance.agent`
| **`Provenance.agent.relatedAgent.id`**| | | | | | | | | 
| **`Provenance.agent.relatedAgent.extension`**| | | | | | | | | 
| **`Provenance.agent.relatedAgent.modifierExtension`**| | | | | | | | | 
| **`Provenance.agent.relatedAgent.type`**| →→→→ _Equivalent_ →→→→ <br/>(357)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(705)| `Provenance.agent.relatedAgentType`| →→→→ __ →→→→ <br/>(1242)<hr/>←←←← __ ←←←← <br/>()| `base64Binary`| | | | | 
| **`Provenance.agent.relatedAgent.type`**| →→→→ _Equivalent_ →→→→ <br/>(357)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(705)| `Provenance.agent.relatedAgentType`| →→→→ _Equivalent_ →→→→ <br/>(31996)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1644)| `Provenance.agent.type`| _Equivalent_<br/>(32037/32038)| `Provenance.agent.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(46617)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(46618)| `Provenance.agent.type`
| **`Provenance.agent.relatedAgent.target`**| | | | | | | | | 
| **`Provenance.entity`**| _Equivalent_<br/>(7482/7483)| `Provenance.entity`| _Equivalent_<br/>(17631/17632)| `Provenance.entity`| _Equivalent_<br/>(32045/32046)| `Provenance.entity`| _Equivalent_<br/>(46625/46626)| `Provenance.entity`
| **`Provenance.entity.id`**| _Equivalent_<br/>(7484/7485)| `Provenance.entity.id`| _Equivalent_<br/>(17633/17634)| `Provenance.entity.id`| _Equivalent_<br/>(32047/32048)| `Provenance.entity.id`| _Equivalent_<br/>(46627/46628)| `Provenance.entity.id`
| **`Provenance.entity.extension`**| _Equivalent_<br/>(7486/7487)| `Provenance.entity.extension`| _Equivalent_<br/>(17635/17636)| `Provenance.entity.extension`| _Equivalent_<br/>(32049/32050)| `Provenance.entity.extension`| _Equivalent_<br/>(46629/46630)| `Provenance.entity.extension`
| **`Provenance.entity.modifierExtension`**| _Equivalent_<br/>(7488/7489)| `Provenance.entity.modifierExtension`| _Equivalent_<br/>(17637/17638)| `Provenance.entity.modifierExtension`| _Equivalent_<br/>(32051/32052)| `Provenance.entity.modifierExtension`| _Equivalent_<br/>(46631/46632)| `Provenance.entity.modifierExtension`
| **`Provenance.entity.role`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7490)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7491)| `Provenance.entity.role`| _Equivalent_<br/>(17639/17640)| `Provenance.entity.role`| _Equivalent_<br/>(32053/32054)| `Provenance.entity.role`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(46633)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(46634)| `Provenance.entity.role`
| **`Provenance.entity.type`**| | | | | | | | | 
| **`Provenance.entity.reference`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(360)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(707)| `Provenance.entity.what[x]`| →→→→ _RelatedTo_ →→→→ <br/>(1244)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1642)| `Provenance.entity.what`| _Equivalent_<br/>(32055/32056)| `Provenance.entity.what`| _Equivalent_<br/>(46635/46636)| `Provenance.entity.what`
| **`Provenance.entity.display`**| | | | | | | | | 
| **`Provenance.entity.agent`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7492)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7493)| `Provenance.entity.agent`| _Equivalent_<br/>(17641/17642)| `Provenance.entity.agent`| _Equivalent_<br/>(32057/32058)| `Provenance.entity.agent`| _Equivalent_<br/>(46637/46638)| `Provenance.entity.agent`
| **`Provenance.signature`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7494)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7495)| `Provenance.signature`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17643)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17644)| `Provenance.signature`| _Equivalent_<br/>(32059/32060)| `Provenance.signature`| _Equivalent_<br/>(46639/46640)| `Provenance.signature`
| *39 of 39 elements used* | | *31 of 32 elements used* <br/>remaining elements:<br/>`Provenance.agent.onBehalfOf[x]`| | *32 of 32 elements used* | | *31 of 32 elements used* <br/>remaining elements:<br/>`Provenance.agent.onBehalfOf`| | *31 of 35 elements used* <br/>remaining elements:<br/>`Provenance.agent.onBehalfOf`, `Provenance.basedOn`, `Provenance.encounter`, `Provenance.patient`

