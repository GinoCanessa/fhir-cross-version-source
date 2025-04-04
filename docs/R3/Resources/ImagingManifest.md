Comparison of 
Generated at Friday, April 4, 2025 2:58:40 PM

### ImagingManifest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | ImagingManifest |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ImagingManifest` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for ImagingManifest Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `530` |
| Database Snapshot Count | `33` |
| Database Differential Count | `16` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ImagingManifest` | `ImagingManifest` | `ImagingManifest` | ImagingManifest | Key Object Selection | 0..* | ImagingManifest |  |  |
| `ImagingManifest.author` | `ImagingManifest.author` | `author` |  | Author (human or machine) | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `ImagingManifest.authoringTime` | `ImagingManifest.authoringTime` | `authoringTime` |  | Time when the selection of instances was made | 0..1 | dateTime |  |  |
| `ImagingManifest.contained` | `ImagingManifest.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ImagingManifest.description` | `ImagingManifest.description` | `description` |  | Description text | 0..1 | string |  |  |
| `ImagingManifest.extension` | `ImagingManifest.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ImagingManifest.id` | `ImagingManifest.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ImagingManifest.identifier` | `ImagingManifest.identifier` | `identifier` |  | SOP Instance UID | 0..1 | Identifier |  |  |
| `ImagingManifest.implicitRules` | `ImagingManifest.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ImagingManifest.language` | `ImagingManifest.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `ImagingManifest.meta` | `ImagingManifest.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ImagingManifest.modifierExtension` | `ImagingManifest.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ImagingManifest.patient` | `ImagingManifest.patient` | `patient` |  | Patient of the selected objects | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `ImagingManifest.study` | `ImagingManifest.study` | `study` |  | Study identity of the selected instances | 1..* | BackboneElement |  |  |
| `ImagingManifest.study.endpoint` | `ImagingManifest.study.endpoint` | `endpoint` |  | Study access service endpoint | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Endpoint) |  |  |
| `ImagingManifest.study.extension` | `ImagingManifest.study.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ImagingManifest.study.id` | `ImagingManifest.study.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ImagingManifest.study.imagingStudy` | `ImagingManifest.study.imagingStudy` | `imagingStudy` |  | Reference to ImagingStudy | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/ImagingStudy) |  |  |
| `ImagingManifest.study.modifierExtension` | `ImagingManifest.study.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ImagingManifest.study.series` | `ImagingManifest.study.series` | `series` |  | Series identity of the selected instances | 1..* | BackboneElement |  |  |
| `ImagingManifest.study.series.endpoint` | `ImagingManifest.study.series.endpoint` | `endpoint` |  | Series access endpoint | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Endpoint) |  |  |
| `ImagingManifest.study.series.extension` | `ImagingManifest.study.series.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ImagingManifest.study.series.id` | `ImagingManifest.study.series.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ImagingManifest.study.series.instance` | `ImagingManifest.study.series.instance` | `instance` |  | The selected instance | 1..* | BackboneElement |  |  |
| `ImagingManifest.study.series.instance.extension` | `ImagingManifest.study.series.instance.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ImagingManifest.study.series.instance.id` | `ImagingManifest.study.series.instance.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ImagingManifest.study.series.instance.modifierExtension` | `ImagingManifest.study.series.instance.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ImagingManifest.study.series.instance.sopClass` | `ImagingManifest.study.series.instance.sopClass` | `sopClass` |  | SOP class UID of instance | 1..1 | oid |  |  |
| `ImagingManifest.study.series.instance.uid` | `ImagingManifest.study.series.instance.uid` | `uid` |  | Selected instance UID | 1..1 | oid |  |  |
| `ImagingManifest.study.series.modifierExtension` | `ImagingManifest.study.series.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ImagingManifest.study.series.uid` | `ImagingManifest.study.series.uid` | `uid` |  | Series instance UID | 1..1 | oid |  |  |
| `ImagingManifest.study.uid` | `ImagingManifest.study.uid` | `uid` |  | Study instance UID | 1..1 | oid |  |  |
| `ImagingManifest.text` | `ImagingManifest.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ImagingObjectSelection](/docs/R2/Resources/ImagingObjectSelection.md)<br/> `http://hl7.org/fhir/StructureDefinition/ImagingObjectSelection\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `116`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`NotRelatedTo`<br/>- DBKey: `282`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ImagingManifest](/docs/R3/Resources/ImagingManifest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ImagingManifest\|3.0.2` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | | | 
### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ImagingManifest from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 ImagingObjectSelection](/docs/R2/Resources/ImagingObjectSelection.md)| Relationship | R3 ImagingManifest| Relationship | *No Map* | Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`ImagingManifest`**| | | | | | | 
| | | **`ImagingManifest.id`**| | | | | | | 
| | | **`ImagingManifest.meta`**| | | | | | | 
| | | **`ImagingManifest.implicitRules`**| | | | | | | 
| | | **`ImagingManifest.language`**| | | | | | | 
| | | **`ImagingManifest.text`**| | | | | | | 
| | | **`ImagingManifest.contained`**| | | | | | | 
| | | **`ImagingManifest.extension`**| | | | | | | 
| | | **`ImagingManifest.modifierExtension`**| | | | | | | 
| | | **`ImagingManifest.identifier`**| | | | | | | 
| | | **`ImagingManifest.patient`**| | | | | | | 
| | | **`ImagingManifest.authoringTime`**| | | | | | | 
| | | **`ImagingManifest.author`**| | | | | | | 
| | | **`ImagingManifest.description`**| | | | | | | 
| | | **`ImagingManifest.study`**| | | | | | | 
| | | **`ImagingManifest.study.id`**| | | | | | | 
| | | **`ImagingManifest.study.extension`**| | | | | | | 
| | | **`ImagingManifest.study.modifierExtension`**| | | | | | | 
| | | **`ImagingManifest.study.uid`**| | | | | | | 
| | | **`ImagingManifest.study.imagingStudy`**| | | | | | | 
| | | **`ImagingManifest.study.endpoint`**| | | | | | | 
| | | **`ImagingManifest.study.series`**| | | | | | | 
| | | **`ImagingManifest.study.series.id`**| | | | | | | 
| | | **`ImagingManifest.study.series.extension`**| | | | | | | 
| | | **`ImagingManifest.study.series.modifierExtension`**| | | | | | | 
| | | **`ImagingManifest.study.series.uid`**| | | | | | | 
| | | **`ImagingManifest.study.series.endpoint`**| | | | | | | 
| | | **`ImagingManifest.study.series.instance`**| | | | | | | 
| | | **`ImagingManifest.study.series.instance.id`**| | | | | | | 
| | | **`ImagingManifest.study.series.instance.extension`**| | | | | | | 
| | | **`ImagingManifest.study.series.instance.modifierExtension`**| | | | | | | 
| | | **`ImagingManifest.study.series.instance.sopClass`**| | | | | | | 
| | | **`ImagingManifest.study.series.instance.uid`**| | | | | | | 
| *0 of 41 elements used* <br/>remaining elements:<br/>`ImagingObjectSelection`, `ImagingObjectSelection.author`, `ImagingObjectSelection.authoringTime`, `ImagingObjectSelection.contained`, `ImagingObjectSelection.description`, `ImagingObjectSelection.extension`, `ImagingObjectSelection.id`, `ImagingObjectSelection.implicitRules`, `ImagingObjectSelection.language`, `ImagingObjectSelection.meta`, `ImagingObjectSelection.modifierExtension`, `ImagingObjectSelection.patient`, `ImagingObjectSelection.study`, `ImagingObjectSelection.study.extension`, `ImagingObjectSelection.study.id`, `ImagingObjectSelection.study.imagingStudy`, `ImagingObjectSelection.study.modifierExtension`, `ImagingObjectSelection.study.series`, `ImagingObjectSelection.study.series.extension`, `ImagingObjectSelection.study.series.id`, `ImagingObjectSelection.study.series.instance`, `ImagingObjectSelection.study.series.instance.extension`, `ImagingObjectSelection.study.series.instance.frames`, `ImagingObjectSelection.study.series.instance.frames.extension`, `ImagingObjectSelection.study.series.instance.frames.frameNumbers`, `ImagingObjectSelection.study.series.instance.frames.id`, `ImagingObjectSelection.study.series.instance.frames.modifierExtension`, `ImagingObjectSelection.study.series.instance.frames.url`, `ImagingObjectSelection.study.series.instance.id`, `ImagingObjectSelection.study.series.instance.modifierExtension`, `ImagingObjectSelection.study.series.instance.sopClass`, `ImagingObjectSelection.study.series.instance.uid`, `ImagingObjectSelection.study.series.instance.url`, `ImagingObjectSelection.study.series.modifierExtension`, `ImagingObjectSelection.study.series.uid`, `ImagingObjectSelection.study.series.url`, `ImagingObjectSelection.study.uid`, `ImagingObjectSelection.study.url`, `ImagingObjectSelection.text`, `ImagingObjectSelection.title`, `ImagingObjectSelection.uid`| | *33 of 33 elements used* | | | | | | 

