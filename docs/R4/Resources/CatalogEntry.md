Comparison of 
Generated at Thursday, April 3, 2025 8:18:23 AM

### CatalogEntry

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | CatalogEntry |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/CatalogEntry` |
| Version | 4.0.1 |
| Description | Catalog entries are wrappers that contextualize items included in a catalog. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1046` |
| Database Snapshot Count | `27` |
| Database Differential Count | `16` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `CatalogEntry` | `CatalogEntry` | `CatalogEntry` | CatalogEntry | An entry in a catalog | 0..* | CatalogEntry |  |  |
| `CatalogEntry.additionalCharacteristic` | `CatalogEntry.additionalCharacteristic` | `additionalCharacteristic` | CatalogEntry.additionalCharacteristic | Additional characteristics of the catalog entry | 0..* | CodeableConcept |  |  |
| `CatalogEntry.additionalClassification` | `CatalogEntry.additionalClassification` | `additionalClassification` | CatalogEntry.additionalClassification | Additional classification of the catalog entry | 0..* | CodeableConcept |  |  |
| `CatalogEntry.additionalIdentifier` | `CatalogEntry.additionalIdentifier` | `additionalIdentifier` | CatalogEntry.additionalIdentifier | Any additional identifier(s) for the catalog item, in the same granularity or concept | 0..* | Identifier |  |  |
| `CatalogEntry.classification` | `CatalogEntry.classification` | `classification` | CatalogEntry.classification | Classification (category or class) of the item entry | 0..* | CodeableConcept |  |  |
| `CatalogEntry.contained` | `CatalogEntry.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `CatalogEntry.extension` | `CatalogEntry.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `CatalogEntry.id` | `CatalogEntry.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `CatalogEntry.identifier` | `CatalogEntry.identifier` | `identifier` | CatalogEntry.identifier | Unique identifier of the catalog item | 0..* | Identifier |  |  |
| `CatalogEntry.implicitRules` | `CatalogEntry.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `CatalogEntry.language` | `CatalogEntry.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `CatalogEntry.lastUpdated` | `CatalogEntry.lastUpdated` | `lastUpdated` | CatalogEntry.lastUpdated | When was this catalog last updated | 0..1 | dateTime |  |  |
| `CatalogEntry.meta` | `CatalogEntry.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `CatalogEntry.modifierExtension` | `CatalogEntry.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CatalogEntry.orderable` | `CatalogEntry.orderable` | `orderable` | CatalogEntry.orderable | Whether the entry represents an orderable item | 1..1 | boolean |  |  |
| `CatalogEntry.referencedItem` | `CatalogEntry.referencedItem` | `referencedItem` | CatalogEntry.referencedItem | The item that is being defined | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/ActivityDefinition), Reference(http://hl7.org/fhir/StructureDefinition/Binary), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/ObservationDefinition), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/PlanDefinition), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/SpecimenDefinition) |  |  |
| `CatalogEntry.relatedEntry` | `CatalogEntry.relatedEntry` | `relatedEntry` | CatalogEntry.relatedEntry | An item that this catalog entry is related to | 0..* | BackboneElement |  |  |
| `CatalogEntry.relatedEntry.extension` | `CatalogEntry.relatedEntry.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `CatalogEntry.relatedEntry.id` | `CatalogEntry.relatedEntry.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `CatalogEntry.relatedEntry.item` | `CatalogEntry.relatedEntry.item` | `item` | CatalogEntry.relatedEntry.item | The reference to the related item | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/CatalogEntry) |  |  |
| `CatalogEntry.relatedEntry.modifierExtension` | `CatalogEntry.relatedEntry.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `CatalogEntry.relatedEntry.relationtype` | `CatalogEntry.relatedEntry.relationtype` | `relationtype` | CatalogEntry.relatedEntry.relationtype | triggers \| is-replaced-by | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/relation-type|4.0.1` |
| `CatalogEntry.status` | `CatalogEntry.status` | `status` | CatalogEntry.status | draft \| active \| retired \| unknown | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.0.1` |
| `CatalogEntry.text` | `CatalogEntry.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `CatalogEntry.type` | `CatalogEntry.type` | `type` | CatalogEntry.type | The type of item - medication, device, service, protocol or other | 0..1 | CodeableConcept |  |  |
| `CatalogEntry.validTo` | `CatalogEntry.validTo` | `validTo` | CatalogEntry.validTo | The date until which this catalog entry is expected to be active | 0..1 | dateTime |  |  |
| `CatalogEntry.validityPeriod` | `CatalogEntry.validityPeriod` | `validityPeriod` | CatalogEntry.validityPeriod | The time period in which this catalog entry is expected to be active | 0..1 | Period |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [CatalogEntry](/docs/R4/Resources/CatalogEntry.md)<br/> `http://hl7.org/fhir/StructureDefinition/CatalogEntry\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1417`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1418`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CatalogEntry](/docs/R4B/Resources/CatalogEntry.md)<br/> `http://hl7.org/fhir/StructureDefinition/CatalogEntry\|4.3.0` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | 
### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition CatalogEntry from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | R4 CatalogEntry| Relationship | [R4B CatalogEntry](/docs/R4B/Resources/CatalogEntry.md)| Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | **`CatalogEntry`**| _Equivalent_<br/>(22709/22710)| `CatalogEntry`| | | 
| | | | | **`CatalogEntry.id`**| _Equivalent_<br/>(22711/22712)| `CatalogEntry.id`| | | 
| | | | | **`CatalogEntry.meta`**| _Equivalent_<br/>(22713/22714)| `CatalogEntry.meta`| | | 
| | | | | **`CatalogEntry.implicitRules`**| _Equivalent_<br/>(22715/22716)| `CatalogEntry.implicitRules`| | | 
| | | | | **`CatalogEntry.language`**| _Equivalent_<br/>(22717/22718)| `CatalogEntry.language`| | | 
| | | | | **`CatalogEntry.text`**| _Equivalent_<br/>(22719/22720)| `CatalogEntry.text`| | | 
| | | | | **`CatalogEntry.contained`**| _Equivalent_<br/>(22721/22722)| `CatalogEntry.contained`| | | 
| | | | | **`CatalogEntry.extension`**| _Equivalent_<br/>(22723/22724)| `CatalogEntry.extension`| | | 
| | | | | **`CatalogEntry.modifierExtension`**| _Equivalent_<br/>(22725/22726)| `CatalogEntry.modifierExtension`| | | 
| | | | | **`CatalogEntry.identifier`**| _Equivalent_<br/>(22727/22728)| `CatalogEntry.identifier`| | | 
| | | | | **`CatalogEntry.type`**| _Equivalent_<br/>(22729/22730)| `CatalogEntry.type`| | | 
| | | | | **`CatalogEntry.orderable`**| _Equivalent_<br/>(22731/22732)| `CatalogEntry.orderable`| | | 
| | | | | **`CatalogEntry.referencedItem`**| _Equivalent_<br/>(22733/22734)| `CatalogEntry.referencedItem`| | | 
| | | | | **`CatalogEntry.additionalIdentifier`**| _Equivalent_<br/>(22735/22736)| `CatalogEntry.additionalIdentifier`| | | 
| | | | | **`CatalogEntry.classification`**| _Equivalent_<br/>(22737/22738)| `CatalogEntry.classification`| | | 
| | | | | **`CatalogEntry.status`**| _Equivalent_<br/>(22739/22740)| `CatalogEntry.status`| | | 
| | | | | **`CatalogEntry.validityPeriod`**| _Equivalent_<br/>(22741/22742)| `CatalogEntry.validityPeriod`| | | 
| | | | | **`CatalogEntry.validTo`**| _Equivalent_<br/>(22743/22744)| `CatalogEntry.validTo`| | | 
| | | | | **`CatalogEntry.lastUpdated`**| _Equivalent_<br/>(22745/22746)| `CatalogEntry.lastUpdated`| | | 
| | | | | **`CatalogEntry.additionalCharacteristic`**| _Equivalent_<br/>(22747/22748)| `CatalogEntry.additionalCharacteristic`| | | 
| | | | | **`CatalogEntry.additionalClassification`**| _Equivalent_<br/>(22749/22750)| `CatalogEntry.additionalClassification`| | | 
| | | | | **`CatalogEntry.relatedEntry`**| _Equivalent_<br/>(22751/22752)| `CatalogEntry.relatedEntry`| | | 
| | | | | **`CatalogEntry.relatedEntry.id`**| _Equivalent_<br/>(22753/22754)| `CatalogEntry.relatedEntry.id`| | | 
| | | | | **`CatalogEntry.relatedEntry.extension`**| _Equivalent_<br/>(22755/22756)| `CatalogEntry.relatedEntry.extension`| | | 
| | | | | **`CatalogEntry.relatedEntry.modifierExtension`**| _Equivalent_<br/>(22757/22758)| `CatalogEntry.relatedEntry.modifierExtension`| | | 
| | | | | **`CatalogEntry.relatedEntry.relationtype`**| _Equivalent_<br/>(22759/22760)| `CatalogEntry.relatedEntry.relationtype`| | | 
| | | | | **`CatalogEntry.relatedEntry.item`**| _Equivalent_<br/>(22761/22762)| `CatalogEntry.relatedEntry.item`| | | 
| | | | | *27 of 27 elements used* | | *27 of 27 elements used* | | 

