Comparison of 
Generated at Monday, April 14, 2025 6:17:16 PM

### ImagingObjectSelection

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | ImagingObjectSelection |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ImagingObjectSelection` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for ImagingObjectSelection Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `86` |
| Database Snapshot Count | `41` |
| Database Differential Count | `21` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ImagingObjectSelection` | `ImagingObjectSelection` | `ImagingObjectSelection` | ImagingObjectSelection | Key Object Selection | 0..* | ImagingObjectSelection |  |  |
| `ImagingObjectSelection.author` | `ImagingObjectSelection.author` | `author` |  | Author (human or machine) | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `ImagingObjectSelection.authoringTime` | `ImagingObjectSelection.authoringTime` | `authoringTime` |  | Authoring time of the selection | 0..1 | dateTime |  |  |
| `ImagingObjectSelection.contained` | `ImagingObjectSelection.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ImagingObjectSelection.description` | `ImagingObjectSelection.description` | `description` |  | Description text | 0..1 | string |  |  |
| `ImagingObjectSelection.extension` | `ImagingObjectSelection.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ImagingObjectSelection.id` | `ImagingObjectSelection.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ImagingObjectSelection.implicitRules` | `ImagingObjectSelection.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ImagingObjectSelection.language` | `ImagingObjectSelection.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `ImagingObjectSelection.meta` | `ImagingObjectSelection.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ImagingObjectSelection.modifierExtension` | `ImagingObjectSelection.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ImagingObjectSelection.patient` | `ImagingObjectSelection.patient` | `patient` |  | Patient of the selected objects | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `ImagingObjectSelection.study` | `ImagingObjectSelection.study` | `study` |  | Study identity of the selected instances | 1..* | BackboneElement |  |  |
| `ImagingObjectSelection.study.extension` | `ImagingObjectSelection.study.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ImagingObjectSelection.study.id` | `ImagingObjectSelection.study.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ImagingObjectSelection.study.imagingStudy` | `ImagingObjectSelection.study.imagingStudy` | `imagingStudy` |  | Reference to ImagingStudy | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/ImagingStudy) |  |  |
| `ImagingObjectSelection.study.modifierExtension` | `ImagingObjectSelection.study.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ImagingObjectSelection.study.series` | `ImagingObjectSelection.study.series` | `series` |  | Series identity of the selected instances | 1..* | BackboneElement |  |  |
| `ImagingObjectSelection.study.series.extension` | `ImagingObjectSelection.study.series.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ImagingObjectSelection.study.series.id` | `ImagingObjectSelection.study.series.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ImagingObjectSelection.study.series.instance` | `ImagingObjectSelection.study.series.instance` | `instance` |  | The selected instance | 1..* | BackboneElement |  |  |
| `ImagingObjectSelection.study.series.instance.extension` | `ImagingObjectSelection.study.series.instance.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ImagingObjectSelection.study.series.instance.frames` | `ImagingObjectSelection.study.series.instance.frames` | `frames` |  | The frame set | 0..* | BackboneElement |  |  |
| `ImagingObjectSelection.study.series.instance.frames.extension` | `ImagingObjectSelection.study.series.instance.frames.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ImagingObjectSelection.study.series.instance.frames.frameNumbers` | `ImagingObjectSelection.study.series.instance.frames.frameNumbers` | `frameNumbers` |  | Frame numbers | 1..* | unsignedInt |  |  |
| `ImagingObjectSelection.study.series.instance.frames.id` | `ImagingObjectSelection.study.series.instance.frames.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ImagingObjectSelection.study.series.instance.frames.modifierExtension` | `ImagingObjectSelection.study.series.instance.frames.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ImagingObjectSelection.study.series.instance.frames.url` | `ImagingObjectSelection.study.series.instance.frames.url` | `url` |  | Retrieve frame URL | 1..1 | uri |  |  |
| `ImagingObjectSelection.study.series.instance.id` | `ImagingObjectSelection.study.series.instance.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ImagingObjectSelection.study.series.instance.modifierExtension` | `ImagingObjectSelection.study.series.instance.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ImagingObjectSelection.study.series.instance.sopClass` | `ImagingObjectSelection.study.series.instance.sopClass` | `sopClass` |  | SOP class UID of instance | 1..1 | oid |  |  |
| `ImagingObjectSelection.study.series.instance.uid` | `ImagingObjectSelection.study.series.instance.uid` | `uid` |  | Selected instance UID | 1..1 | oid |  |  |
| `ImagingObjectSelection.study.series.instance.url` | `ImagingObjectSelection.study.series.instance.url` | `url` |  | Retrieve instance URL | 1..1 | uri |  |  |
| `ImagingObjectSelection.study.series.modifierExtension` | `ImagingObjectSelection.study.series.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ImagingObjectSelection.study.series.uid` | `ImagingObjectSelection.study.series.uid` | `uid` |  | Series instance UID | 0..1 | oid |  |  |
| `ImagingObjectSelection.study.series.url` | `ImagingObjectSelection.study.series.url` | `url` |  | Retrieve series URL | 0..1 | uri |  |  |
| `ImagingObjectSelection.study.uid` | `ImagingObjectSelection.study.uid` | `uid` |  | Study instance UID | 1..1 | oid |  |  |
| `ImagingObjectSelection.study.url` | `ImagingObjectSelection.study.url` | `url` |  | Retrieve study URL | 0..1 | uri |  |  |
| `ImagingObjectSelection.text` | `ImagingObjectSelection.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ImagingObjectSelection.title` | `ImagingObjectSelection.title` | `title` |  | Reason for selection | 1..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/kos-title` |
| `ImagingObjectSelection.uid` | `ImagingObjectSelection.uid` | `uid` |  | Instance UID | 1..1 | oid |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ImagingObjectSelection](/docs/R2/Resources/ImagingObjectSelection.md)<br/> `http://hl7.org/fhir/StructureDefinition/ImagingObjectSelection\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `116`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`NotRelatedTo`<br/>- DBKey: `282`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ImagingManifest](/docs/R3/Resources/ImagingManifest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ImagingManifest\|3.0.2` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | | | 
### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ImagingObjectSelection from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 ImagingObjectSelection| Relationship | [R3 ImagingManifest](/docs/R3/Resources/ImagingManifest.md)| Relationship | *No Map* | Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`ImagingObjectSelection`**| | | | | | | | | 
| **`ImagingObjectSelection.id`**| | | | | | | | | 
| **`ImagingObjectSelection.meta`**| | | | | | | | | 
| **`ImagingObjectSelection.implicitRules`**| | | | | | | | | 
| **`ImagingObjectSelection.language`**| | | | | | | | | 
| **`ImagingObjectSelection.text`**| | | | | | | | | 
| **`ImagingObjectSelection.contained`**| | | | | | | | | 
| **`ImagingObjectSelection.extension`**| | | | | | | | | 
| **`ImagingObjectSelection.modifierExtension`**| | | | | | | | | 
| **`ImagingObjectSelection.uid`**| | | | | | | | | 
| **`ImagingObjectSelection.patient`**| | | | | | | | | 
| **`ImagingObjectSelection.title`**| | | | | | | | | 
| **`ImagingObjectSelection.description`**| | | | | | | | | 
| **`ImagingObjectSelection.author`**| | | | | | | | | 
| **`ImagingObjectSelection.authoringTime`**| | | | | | | | | 
| **`ImagingObjectSelection.study`**| | | | | | | | | 
| **`ImagingObjectSelection.study.id`**| | | | | | | | | 
| **`ImagingObjectSelection.study.extension`**| | | | | | | | | 
| **`ImagingObjectSelection.study.modifierExtension`**| | | | | | | | | 
| **`ImagingObjectSelection.study.uid`**| | | | | | | | | 
| **`ImagingObjectSelection.study.url`**| | | | | | | | | 
| **`ImagingObjectSelection.study.imagingStudy`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.id`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.extension`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.modifierExtension`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.uid`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.url`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.instance`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.instance.id`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.instance.extension`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.instance.modifierExtension`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.instance.sopClass`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.instance.uid`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.instance.url`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.instance.frames`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.instance.frames.id`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.instance.frames.extension`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.instance.frames.modifierExtension`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.instance.frames.frameNumbers`**| | | | | | | | | 
| **`ImagingObjectSelection.study.series.instance.frames.url`**| | | | | | | | | 
| *41 of 41 elements used* | | *0 of 33 elements used* <br/>remaining elements:<br/>`ImagingManifest`, `ImagingManifest.author`, `ImagingManifest.authoringTime`, `ImagingManifest.contained`, `ImagingManifest.description`, `ImagingManifest.extension`, `ImagingManifest.id`, `ImagingManifest.identifier`, `ImagingManifest.implicitRules`, `ImagingManifest.language`, `ImagingManifest.meta`, `ImagingManifest.modifierExtension`, `ImagingManifest.patient`, `ImagingManifest.study`, `ImagingManifest.study.endpoint`, `ImagingManifest.study.extension`, `ImagingManifest.study.id`, `ImagingManifest.study.imagingStudy`, `ImagingManifest.study.modifierExtension`, `ImagingManifest.study.series`, `ImagingManifest.study.series.endpoint`, `ImagingManifest.study.series.extension`, `ImagingManifest.study.series.id`, `ImagingManifest.study.series.instance`, `ImagingManifest.study.series.instance.extension`, `ImagingManifest.study.series.instance.id`, `ImagingManifest.study.series.instance.modifierExtension`, `ImagingManifest.study.series.instance.sopClass`, `ImagingManifest.study.series.instance.uid`, `ImagingManifest.study.series.modifierExtension`, `ImagingManifest.study.series.uid`, `ImagingManifest.study.uid`, `ImagingManifest.text`| | | | | | 

