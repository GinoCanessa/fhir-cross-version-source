Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ImagingStudy |  | Representation of the content produced in a DICOM imaging study. A study comprises a set of series, each of which includes a set of Service-Object Pair Instances (SOP Instances - images or other data) acquired or produced in a common context.  A series is of only one modality (e.g. X-ray, CT, MR, ultrasound), but a study may have multiple series of different modalities. | 54 | 37 |
| Target | ImagingStudy |  | Representation of the content produced in a DICOM imaging study. A study comprises a set of series, each of which includes a set of Service-Object Pair Instances (SOP Instances - images or other data) acquired or produced in a common context.  A series is of only one modality (e.g. X-ray, CT, MR, ultrasound), but a study may have multiple series of different modalities. | 56 | 39 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 4 |
RelatedTo | 47 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ImagingStudy | ImagingStudy | Equivalent | R5 `ImagingStudy` maps as Equivalent to R4B `ImagingStudy` |
| ImagingStudy.basedOn | ImagingStudy.basedOn | Equivalent | R5 `ImagingStudy.basedOn` maps as Equivalent to R4B `ImagingStudy.basedOn` |
| ImagingStudy.contained | ImagingStudy.contained | Equivalent | R5 `ImagingStudy.contained` maps as Equivalent to R4B `ImagingStudy.contained` |
| ImagingStudy.description | ImagingStudy.description | Equivalent | R5 `ImagingStudy.description` maps as Equivalent to R4B `ImagingStudy.description` |
| ImagingStudy.encounter | ImagingStudy.encounter | Equivalent | R5 `ImagingStudy.encounter` maps as Equivalent to R4B `ImagingStudy.encounter` |
| ImagingStudy.endpoint | ImagingStudy.endpoint | Equivalent | R5 `ImagingStudy.endpoint` maps as Equivalent to R4B `ImagingStudy.endpoint` |
| ImagingStudy.extension | ImagingStudy.extension | SourceIsBroaderThanTarget | R5 `ImagingStudy.extension` maps as SourceIsBroaderThanTarget to R4B `ImagingStudy.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| ImagingStudy.id | ImagingStudy.id | Equivalent | R5 `ImagingStudy.id` maps as Equivalent to R4B `ImagingStudy.id` |
| ImagingStudy.identifier | ImagingStudy.identifier | Equivalent | R5 `ImagingStudy.identifier` maps as Equivalent to R4B `ImagingStudy.identifier` |
| ImagingStudy.implicitRules | ImagingStudy.implicitRules | Equivalent | R5 `ImagingStudy.implicitRules` maps as Equivalent to R4B `ImagingStudy.implicitRules` |
| ImagingStudy.language | ImagingStudy.language | RelatedTo | R5 `ImagingStudy.language` maps as RelatedTo to R4B `ImagingStudy.language` - language changed the binding strength from Required to Preferred |
| ImagingStudy.location | ImagingStudy.location | Equivalent | R5 `ImagingStudy.location` maps as Equivalent to R4B `ImagingStudy.location` |
| ImagingStudy.meta | ImagingStudy.meta | Equivalent | R5 `ImagingStudy.meta` maps as Equivalent to R4B `ImagingStudy.meta` |
| ImagingStudy.modality | ImagingStudy.modality | SourceIsBroaderThanTarget | R5 `ImagingStudy.modality` maps as SourceIsBroaderThanTarget to R4B `ImagingStudy.modality` - modality has change due to type change: R5 modality CodeableConcept has no equivalent or mapped type in R4B modality |
| ImagingStudy.modifierExtension | ImagingStudy.modifierExtension | SourceIsBroaderThanTarget | R5 `ImagingStudy.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `ImagingStudy.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| ImagingStudy.note | ImagingStudy.note | SourceIsBroaderThanTarget | R5 `ImagingStudy.note` maps as SourceIsBroaderThanTarget to R4B `ImagingStudy.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| ImagingStudy.numberOfInstances | ImagingStudy.numberOfInstances | Equivalent | R5 `ImagingStudy.numberOfInstances` maps as Equivalent to R4B `ImagingStudy.numberOfInstances` |
| ImagingStudy.numberOfSeries | ImagingStudy.numberOfSeries | Equivalent | R5 `ImagingStudy.numberOfSeries` maps as Equivalent to R4B `ImagingStudy.numberOfSeries` |
| ImagingStudy.partOf | - | DoesNotExistInTarget | R5 `ImagingStudy.partOf` does not appear in the target and has no mapping for `ImagingStudy`. |
| ImagingStudy.procedure | - | DoesNotExistInTarget | R5 `ImagingStudy.procedure` does not appear in the target and has no mapping for `ImagingStudy`. |
| ImagingStudy.reason | - | DoesNotExistInTarget | R5 `ImagingStudy.reason` does not appear in the target and has no mapping for `ImagingStudy`. |
| ImagingStudy.referrer | ImagingStudy.referrer | Equivalent | R5 `ImagingStudy.referrer` maps as Equivalent to R4B `ImagingStudy.referrer` |
| ImagingStudy.series | ImagingStudy.series | Equivalent | R5 `ImagingStudy.series` maps as Equivalent to R4B `ImagingStudy.series` |
| ImagingStudy.series.bodySite | ImagingStudy.series.bodySite | SourceIsBroaderThanTarget | R5 `ImagingStudy.series.bodySite` maps as SourceIsBroaderThanTarget to R4B `ImagingStudy.series.bodySite` - bodySite has change due to type change: R5 bodySite CodeableReference has no equivalent or mapped type in R4B bodySite |
| ImagingStudy.series.description | ImagingStudy.series.description | Equivalent | R5 `ImagingStudy.series.description` maps as Equivalent to R4B `ImagingStudy.series.description` |
| ImagingStudy.series.endpoint | ImagingStudy.series.endpoint | Equivalent | R5 `ImagingStudy.series.endpoint` maps as Equivalent to R4B `ImagingStudy.series.endpoint` |
| ImagingStudy.series.extension | ImagingStudy.series.extension | SourceIsBroaderThanTarget | R5 `ImagingStudy.series.extension` maps as SourceIsBroaderThanTarget to R4B `ImagingStudy.series.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| ImagingStudy.series.id | ImagingStudy.series.id | Equivalent | R5 `ImagingStudy.series.id` maps as Equivalent to R4B `ImagingStudy.series.id` |
| ImagingStudy.series.instance | ImagingStudy.series.instance | Equivalent | R5 `ImagingStudy.series.instance` maps as Equivalent to R4B `ImagingStudy.series.instance` |
| ImagingStudy.series.instance.extension | ImagingStudy.series.instance.extension | SourceIsBroaderThanTarget | R5 `ImagingStudy.series.instance.extension` maps as SourceIsBroaderThanTarget to R4B `ImagingStudy.series.instance.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| ImagingStudy.series.instance.id | ImagingStudy.series.instance.id | Equivalent | R5 `ImagingStudy.series.instance.id` maps as Equivalent to R4B `ImagingStudy.series.instance.id` |
| ImagingStudy.series.instance.modifierExtension | ImagingStudy.series.instance.modifierExtension | SourceIsBroaderThanTarget | R5 `ImagingStudy.series.instance.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `ImagingStudy.series.instance.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| ImagingStudy.series.instance.number | ImagingStudy.series.instance.number | Equivalent | R5 `ImagingStudy.series.instance.number` maps as Equivalent to R4B `ImagingStudy.series.instance.number` |
| ImagingStudy.series.instance.sopClass | ImagingStudy.series.instance.sopClass | Equivalent | R5 `ImagingStudy.series.instance.sopClass` maps as Equivalent to R4B `ImagingStudy.series.instance.sopClass` |
| ImagingStudy.series.instance.title | ImagingStudy.series.instance.title | Equivalent | R5 `ImagingStudy.series.instance.title` maps as Equivalent to R4B `ImagingStudy.series.instance.title` |
| ImagingStudy.series.instance.uid | ImagingStudy.series.instance.uid | Equivalent | R5 `ImagingStudy.series.instance.uid` maps as Equivalent to R4B `ImagingStudy.series.instance.uid` |
| ImagingStudy.series.laterality | ImagingStudy.series.laterality | SourceIsBroaderThanTarget | R5 `ImagingStudy.series.laterality` maps as SourceIsBroaderThanTarget to R4B `ImagingStudy.series.laterality` - laterality has change due to type change: R5 laterality CodeableConcept has no equivalent or mapped type in R4B laterality |
| ImagingStudy.series.modality | ImagingStudy.series.modality | SourceIsBroaderThanTarget | R5 `ImagingStudy.series.modality` maps as SourceIsBroaderThanTarget to R4B `ImagingStudy.series.modality` - modality has change due to type change: R5 modality CodeableConcept has no equivalent or mapped type in R4B modality |
| ImagingStudy.series.modifierExtension | ImagingStudy.series.modifierExtension | SourceIsBroaderThanTarget | R5 `ImagingStudy.series.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `ImagingStudy.series.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| ImagingStudy.series.number | ImagingStudy.series.number | Equivalent | R5 `ImagingStudy.series.number` maps as Equivalent to R4B `ImagingStudy.series.number` |
| ImagingStudy.series.numberOfInstances | ImagingStudy.series.numberOfInstances | Equivalent | R5 `ImagingStudy.series.numberOfInstances` maps as Equivalent to R4B `ImagingStudy.series.numberOfInstances` |
| ImagingStudy.series.performer | ImagingStudy.series.performer | Equivalent | R5 `ImagingStudy.series.performer` maps as Equivalent to R4B `ImagingStudy.series.performer` |
| ImagingStudy.series.performer.actor | ImagingStudy.series.performer.actor | SourceIsBroaderThanTarget | R5 `ImagingStudy.series.performer.actor` maps as SourceIsBroaderThanTarget to R4B `ImagingStudy.series.performer.actor` - actor has change due to type change: R5 `actor` `Reference` maps as SourceIsBroaderThanTarget for R4B `actor` |
| ImagingStudy.series.performer.extension | ImagingStudy.series.performer.extension | SourceIsBroaderThanTarget | R5 `ImagingStudy.series.performer.extension` maps as SourceIsBroaderThanTarget to R4B `ImagingStudy.series.performer.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| ImagingStudy.series.performer.function | ImagingStudy.series.performer.function | Equivalent | R5 `ImagingStudy.series.performer.function` maps as Equivalent to R4B `ImagingStudy.series.performer.function` |
| ImagingStudy.series.performer.id | ImagingStudy.series.performer.id | Equivalent | R5 `ImagingStudy.series.performer.id` maps as Equivalent to R4B `ImagingStudy.series.performer.id` |
| ImagingStudy.series.performer.modifierExtension | ImagingStudy.series.performer.modifierExtension | SourceIsBroaderThanTarget | R5 `ImagingStudy.series.performer.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `ImagingStudy.series.performer.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| ImagingStudy.series.specimen | ImagingStudy.series.specimen | Equivalent | R5 `ImagingStudy.series.specimen` maps as Equivalent to R4B `ImagingStudy.series.specimen` |
| ImagingStudy.series.started | ImagingStudy.series.started | Equivalent | R5 `ImagingStudy.series.started` maps as Equivalent to R4B `ImagingStudy.series.started` |
| ImagingStudy.series.uid | ImagingStudy.series.uid | Equivalent | R5 `ImagingStudy.series.uid` maps as Equivalent to R4B `ImagingStudy.series.uid` |
| ImagingStudy.started | ImagingStudy.started | Equivalent | R5 `ImagingStudy.started` maps as Equivalent to R4B `ImagingStudy.started` |
| ImagingStudy.status | ImagingStudy.status | Equivalent | R5 `ImagingStudy.status` maps as Equivalent to R4B `ImagingStudy.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/imagingstudy-status|5.0.0 and http://hl7.org/fhir/ValueSet/imagingstudy-status|4.3.0 (Equivalent) |
| ImagingStudy.subject | ImagingStudy.subject | Equivalent | R5 `ImagingStudy.subject` maps as Equivalent to R4B `ImagingStudy.subject` |
| ImagingStudy.text | ImagingStudy.text | Equivalent | R5 `ImagingStudy.text` maps as Equivalent to R4B `ImagingStudy.text` |

