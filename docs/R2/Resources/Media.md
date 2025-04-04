Comparison of 
Generated at Friday, April 4, 2025 2:58:34 PM

### Media

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Media |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Media` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Media Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `93` |
| Database Snapshot Count | `21` |
| Database Differential Count | `13` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Media` | `Media` | `Media` | Media | A photo, video, or audio recording acquired or used in healthcare. The actual content may be inline or provided by direct reference | 0..* | Media |  |  |
| `Media.contained` | `Media.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Media.content` | `Media.content` | `content` |  | Actual Media - reference or data | 1..1 | Attachment |  |  |
| `Media.deviceName` | `Media.deviceName` | `deviceName` |  | Name of the device/manufacturer | 0..1 | string |  |  |
| `Media.duration` | `Media.duration` | `duration` |  | Length in seconds (audio / video) | 0..1 | unsignedInt |  |  |
| `Media.extension` | `Media.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Media.frames` | `Media.frames` | `frames` |  | Number of frames if > 1 (photo) | 0..1 | positiveInt |  |  |
| `Media.height` | `Media.height` | `height` |  | Height of the image in pixels (photo/video) | 0..1 | positiveInt |  |  |
| `Media.id` | `Media.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Media.identifier` | `Media.identifier` | `identifier` |  | Identifier(s) for the image | 0..* | Identifier |  |  |
| `Media.implicitRules` | `Media.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Media.language` | `Media.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Media.meta` | `Media.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Media.modifierExtension` | `Media.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Media.operator` | `Media.operator` | `operator` |  | The person who generated the image | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `Media.subject` | `Media.subject` | `subject` |  | Who/What this Media is a record of | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/Specimen) |  |  |
| `Media.subtype` | `Media.subtype` | `subtype` |  | The type of acquisition equipment/process | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/digital-media-subtype` |
| `Media.text` | `Media.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Media.type` | `Media.type` | `type` |  | photo \| video \| audio | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/digital-media-type` |
| `Media.view` | `Media.view` | `view` |  | Imaging view, e.g. Lateral or Antero-posterior | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/media-view` |
| `Media.width` | `Media.width` | `width` |  | Width of the image in pixels (photo/video) | 0..1 | positiveInt |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Media](/docs/R2/Resources/Media.md)<br/> `http://hl7.org/fhir/StructureDefinition/Media\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `123`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `289`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Media](/docs/R3/Resources/Media.md)<br/> `http://hl7.org/fhir/StructureDefinition/Media\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `478`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `672`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Media](/docs/R4/Resources/Media.md)<br/> `http://hl7.org/fhir/StructureDefinition/Media\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1533`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1534`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Media](/docs/R4B/Resources/Media.md)<br/> `http://hl7.org/fhir/StructureDefinition/Media\|4.3.0` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | 
### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Media from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Media| Relationship | [R3 Media](/docs/R3/Resources/Media.md)| Relationship | [R4 Media](/docs/R4/Resources/Media.md)| Relationship | [R4B Media](/docs/R4B/Resources/Media.md)| Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Media`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6049)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6050)| `Media`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15623)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15624)| `Media`| _Equivalent_<br/>(29371/29372)| `Media`| | | 
| **`Media.id`**| _Equivalent_<br/>(6051/6052)| `Media.id`| _Equivalent_<br/>(15625/15626)| `Media.id`| _Equivalent_<br/>(29373/29374)| `Media.id`| | | 
| **`Media.meta`**| _Equivalent_<br/>(6053/6054)| `Media.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15627)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15628)| `Media.meta`| _Equivalent_<br/>(29375/29376)| `Media.meta`| | | 
| **`Media.implicitRules`**| _Equivalent_<br/>(6055/6056)| `Media.implicitRules`| _Equivalent_<br/>(15629/15630)| `Media.implicitRules`| _Equivalent_<br/>(29377/29378)| `Media.implicitRules`| | | 
| **`Media.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6057)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6058)| `Media.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15631)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(15632)| `Media.language`| _Equivalent_<br/>(29379/29380)| `Media.language`| | | 
| **`Media.text`**| _Equivalent_<br/>(6059/6060)| `Media.text`| _Equivalent_<br/>(15633/15634)| `Media.text`| _Equivalent_<br/>(29381/29382)| `Media.text`| | | 
| **`Media.contained`**| _Equivalent_<br/>(6061/6062)| `Media.contained`| _Equivalent_<br/>(15635/15636)| `Media.contained`| _Equivalent_<br/>(29383/29384)| `Media.contained`| | | 
| **`Media.extension`**| _Equivalent_<br/>(6063/6064)| `Media.extension`| _Equivalent_<br/>(15637/15638)| `Media.extension`| _Equivalent_<br/>(29385/29386)| `Media.extension`| | | 
| **`Media.modifierExtension`**| _Equivalent_<br/>(6065/6066)| `Media.modifierExtension`| _Equivalent_<br/>(15639/15640)| `Media.modifierExtension`| _Equivalent_<br/>(29387/29388)| `Media.modifierExtension`| | | 
| **`Media.type`**| _Equivalent_<br/>(6067/6068)| `Media.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15645)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(15646)| `Media.type`| _Equivalent_<br/>(29397/29398)| `Media.type`| | | 
| **`Media.subtype`**| _Equivalent_<br/>(6069/6070)| `Media.subtype`| _Equivalent_<br/>(1169/1598)| `Media.modality`| _Equivalent_<br/>(29399/29400)| `Media.modality`| | | 
| **`Media.identifier`**| _Equivalent_<br/>(6071/6072)| `Media.identifier`| _Equivalent_<br/>(15641/15642)| `Media.identifier`| _Equivalent_<br/>(29389/29390)| `Media.identifier`| | | 
| **`Media.subject`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6073)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6074)| `Media.subject`| →→→→ _RelatedTo_ →→→→ <br/>(15649)<hr/>←←←← _RelatedTo_ ←←←← <br/>(15650)| `Media.subject`| _Equivalent_<br/>(29403/29404)| `Media.subject`| | | 
| **`Media.operator`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6075)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6076)| `Media.operator`| →→→→ _RelatedTo_ →→→→ <br/>(15651)<hr/>←←←← _RelatedTo_ ←←←← <br/>(15652)| `Media.operator`| _Equivalent_<br/>(29411/29412)| `Media.operator`| | | 
| **`Media.view`**| _Equivalent_<br/>(6077/6078)| `Media.view`| _Equivalent_<br/>(15647/15648)| `Media.view`| _Equivalent_<br/>(29401/29402)| `Media.view`| | | 
| **`Media.deviceName`**| | | | | | | | | 
| **`Media.height`**| _Equivalent_<br/>(6079/6080)| `Media.height`| _Equivalent_<br/>(15659/15660)| `Media.height`| _Equivalent_<br/>(29421/29422)| `Media.height`| | | 
| **`Media.width`**| _Equivalent_<br/>(6081/6082)| `Media.width`| _Equivalent_<br/>(15661/15662)| `Media.width`| _Equivalent_<br/>(29423/29424)| `Media.width`| | | 
| **`Media.frames`**| _Equivalent_<br/>(6083/6084)| `Media.frames`| _Equivalent_<br/>(15663/15664)| `Media.frames`| _Equivalent_<br/>(29425/29426)| `Media.frames`| | | 
| **`Media.duration`**| _Equivalent_<br/>(6085/6086)| `Media.duration`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15665)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15666)| `Media.duration`| _Equivalent_<br/>(29427/29428)| `Media.duration`| | | 
| **`Media.content`**| _Equivalent_<br/>(6087/6088)| `Media.content`| _Equivalent_<br/>(15667/15668)| `Media.content`| _Equivalent_<br/>(29429/29430)| `Media.content`| | | 
| *21 of 21 elements used* | | *20 of 27 elements used* <br/>remaining elements:<br/>`Media.basedOn`, `Media.bodySite`, `Media.context`, `Media.device`, `Media.note`, `Media.occurrence[x]`, `Media.reasonCode`| | *20 of 31 elements used* <br/>remaining elements:<br/>`Media.basedOn`, `Media.bodySite`, `Media.created[x]`, `Media.device`, `Media.deviceName`, `Media.encounter`, `Media.issued`, `Media.note`, `Media.partOf`, `Media.reasonCode`, `Media.status`| | *20 of 31 elements used* <br/>remaining elements:<br/>`Media.basedOn`, `Media.bodySite`, `Media.created[x]`, `Media.device`, `Media.deviceName`, `Media.encounter`, `Media.issued`, `Media.note`, `Media.partOf`, `Media.reasonCode`, `Media.status`| | 

