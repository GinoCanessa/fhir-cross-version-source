Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ImagingStudy |  | Representation of the content produced in a DICOM imaging study. A study comprises a set of series, each of which includes a set of Service-Object Pair Instances (SOP Instances - images or other data) acquired or produced in a common context.  A series is of only one modality (e.g. X-ray, CT, MR, ultrasound), but a study may have multiple series of different modalities. | 56 | 39 |
| Target | ImagingStudy |  | Representation of the content produced in a DICOM imaging study. A study comprises a set of series, each of which includes a set of Service-Object Pair Instances (SOP Instances - images or other data) acquired or produced in a common context.  A series is of only one modality (e.g. X-ray, CT, MR, ultrasound), but a study may have multiple series of different modalities. | 54 | 37 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 5 |
Equivalent | 4 |
RelatedTo | 47 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ImagingStudy | ImagingStudy | Equivalent | R4B `ImagingStudy` maps as Equivalent to R5 `ImagingStudy` |
| ImagingStudy.basedOn | ImagingStudy.basedOn | Equivalent | R4B `ImagingStudy.basedOn` maps as Equivalent to R5 `ImagingStudy.basedOn` |
| ImagingStudy.contained | ImagingStudy.contained | Equivalent | R4B `ImagingStudy.contained` maps as Equivalent to R5 `ImagingStudy.contained` |
| ImagingStudy.description | ImagingStudy.description | Equivalent | R4B `ImagingStudy.description` maps as Equivalent to R5 `ImagingStudy.description` |
| ImagingStudy.encounter | ImagingStudy.encounter | Equivalent | R4B `ImagingStudy.encounter` maps as Equivalent to R5 `ImagingStudy.encounter` |
| ImagingStudy.endpoint | ImagingStudy.endpoint | Equivalent | R4B `ImagingStudy.endpoint` maps as Equivalent to R5 `ImagingStudy.endpoint` |
| ImagingStudy.extension | ImagingStudy.extension | RelatedTo | R4B `ImagingStudy.extension` maps as RelatedTo to R5 `ImagingStudy.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ImagingStudy.id | ImagingStudy.id | Equivalent | R4B `ImagingStudy.id` maps as Equivalent to R5 `ImagingStudy.id` |
| ImagingStudy.identifier | ImagingStudy.identifier | Equivalent | R4B `ImagingStudy.identifier` maps as Equivalent to R5 `ImagingStudy.identifier` |
| ImagingStudy.implicitRules | ImagingStudy.implicitRules | Equivalent | R4B `ImagingStudy.implicitRules` maps as Equivalent to R5 `ImagingStudy.implicitRules` |
| ImagingStudy.interpreter | - | DoesNotExistInTarget | R4B `ImagingStudy.interpreter` does not appear in the target and has no mapping for `ImagingStudy`. |
| ImagingStudy.language | ImagingStudy.language | RelatedTo | R4B `ImagingStudy.language` maps as RelatedTo to R5 `ImagingStudy.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ImagingStudy.location | ImagingStudy.location | Equivalent | R4B `ImagingStudy.location` maps as Equivalent to R5 `ImagingStudy.location` |
| ImagingStudy.meta | ImagingStudy.meta | Equivalent | R4B `ImagingStudy.meta` maps as Equivalent to R5 `ImagingStudy.meta` |
| ImagingStudy.modality | ImagingStudy.modality | SourceIsBroaderThanTarget | R4B `ImagingStudy.modality` maps as SourceIsBroaderThanTarget to R5 `ImagingStudy.modality` - modality has change due to type change: R4B modality Coding has no equivalent or mapped type in R5 modality |
| ImagingStudy.modifierExtension | ImagingStudy.modifierExtension | RelatedTo | R4B `ImagingStudy.modifierExtension` maps as RelatedTo to R5 `ImagingStudy.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ImagingStudy.note | ImagingStudy.note | SourceIsNarrowerThanTarget | R4B `ImagingStudy.note` maps as SourceIsNarrowerThanTarget to R5 `ImagingStudy.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| ImagingStudy.numberOfInstances | ImagingStudy.numberOfInstances | Equivalent | R4B `ImagingStudy.numberOfInstances` maps as Equivalent to R5 `ImagingStudy.numberOfInstances` |
| ImagingStudy.numberOfSeries | ImagingStudy.numberOfSeries | Equivalent | R4B `ImagingStudy.numberOfSeries` maps as Equivalent to R5 `ImagingStudy.numberOfSeries` |
| ImagingStudy.procedureCode | - | DoesNotExistInTarget | R4B `ImagingStudy.procedureCode` does not appear in the target and has no mapping for `ImagingStudy`. |
| ImagingStudy.procedureReference | - | DoesNotExistInTarget | R4B `ImagingStudy.procedureReference` does not appear in the target and has no mapping for `ImagingStudy`. |
| ImagingStudy.reasonCode | - | DoesNotExistInTarget | R4B `ImagingStudy.reasonCode` does not appear in the target and has no mapping for `ImagingStudy`. |
| ImagingStudy.reasonReference | - | DoesNotExistInTarget | R4B `ImagingStudy.reasonReference` does not appear in the target and has no mapping for `ImagingStudy`. |
| ImagingStudy.referrer | ImagingStudy.referrer | Equivalent | R4B `ImagingStudy.referrer` maps as Equivalent to R5 `ImagingStudy.referrer` |
| ImagingStudy.series | ImagingStudy.series | Equivalent | R4B `ImagingStudy.series` maps as Equivalent to R5 `ImagingStudy.series` |
| ImagingStudy.series.bodySite | ImagingStudy.series.bodySite | SourceIsBroaderThanTarget | R4B `ImagingStudy.series.bodySite` maps as SourceIsBroaderThanTarget to R5 `ImagingStudy.series.bodySite` - bodySite has change due to type change: R4B bodySite Coding has no equivalent or mapped type in R5 bodySite |
| ImagingStudy.series.description | ImagingStudy.series.description | Equivalent | R4B `ImagingStudy.series.description` maps as Equivalent to R5 `ImagingStudy.series.description` |
| ImagingStudy.series.endpoint | ImagingStudy.series.endpoint | Equivalent | R4B `ImagingStudy.series.endpoint` maps as Equivalent to R5 `ImagingStudy.series.endpoint` |
| ImagingStudy.series.extension | ImagingStudy.series.extension | RelatedTo | R4B `ImagingStudy.series.extension` maps as RelatedTo to R5 `ImagingStudy.series.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ImagingStudy.series.id | ImagingStudy.series.id | Equivalent | R4B `ImagingStudy.series.id` maps as Equivalent to R5 `ImagingStudy.series.id` |
| ImagingStudy.series.instance | ImagingStudy.series.instance | Equivalent | R4B `ImagingStudy.series.instance` maps as Equivalent to R5 `ImagingStudy.series.instance` |
| ImagingStudy.series.instance.extension | ImagingStudy.series.instance.extension | RelatedTo | R4B `ImagingStudy.series.instance.extension` maps as RelatedTo to R5 `ImagingStudy.series.instance.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ImagingStudy.series.instance.id | ImagingStudy.series.instance.id | Equivalent | R4B `ImagingStudy.series.instance.id` maps as Equivalent to R5 `ImagingStudy.series.instance.id` |
| ImagingStudy.series.instance.modifierExtension | ImagingStudy.series.instance.modifierExtension | RelatedTo | R4B `ImagingStudy.series.instance.modifierExtension` maps as RelatedTo to R5 `ImagingStudy.series.instance.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ImagingStudy.series.instance.number | ImagingStudy.series.instance.number | Equivalent | R4B `ImagingStudy.series.instance.number` maps as Equivalent to R5 `ImagingStudy.series.instance.number` |
| ImagingStudy.series.instance.sopClass | ImagingStudy.series.instance.sopClass | Equivalent | R4B `ImagingStudy.series.instance.sopClass` maps as Equivalent to R5 `ImagingStudy.series.instance.sopClass` |
| ImagingStudy.series.instance.title | ImagingStudy.series.instance.title | Equivalent | R4B `ImagingStudy.series.instance.title` maps as Equivalent to R5 `ImagingStudy.series.instance.title` |
| ImagingStudy.series.instance.uid | ImagingStudy.series.instance.uid | Equivalent | R4B `ImagingStudy.series.instance.uid` maps as Equivalent to R5 `ImagingStudy.series.instance.uid` |
| ImagingStudy.series.laterality | ImagingStudy.series.laterality | SourceIsBroaderThanTarget | R4B `ImagingStudy.series.laterality` maps as SourceIsBroaderThanTarget to R5 `ImagingStudy.series.laterality` - laterality has change due to type change: R4B laterality Coding has no equivalent or mapped type in R5 laterality |
| ImagingStudy.series.modality | ImagingStudy.series.modality | SourceIsBroaderThanTarget | R4B `ImagingStudy.series.modality` maps as SourceIsBroaderThanTarget to R5 `ImagingStudy.series.modality` - modality has change due to type change: R4B modality Coding has no equivalent or mapped type in R5 modality |
| ImagingStudy.series.modifierExtension | ImagingStudy.series.modifierExtension | RelatedTo | R4B `ImagingStudy.series.modifierExtension` maps as RelatedTo to R5 `ImagingStudy.series.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ImagingStudy.series.number | ImagingStudy.series.number | Equivalent | R4B `ImagingStudy.series.number` maps as Equivalent to R5 `ImagingStudy.series.number` |
| ImagingStudy.series.numberOfInstances | ImagingStudy.series.numberOfInstances | Equivalent | R4B `ImagingStudy.series.numberOfInstances` maps as Equivalent to R5 `ImagingStudy.series.numberOfInstances` |
| ImagingStudy.series.performer | ImagingStudy.series.performer | Equivalent | R4B `ImagingStudy.series.performer` maps as Equivalent to R5 `ImagingStudy.series.performer` |
| ImagingStudy.series.performer.actor | ImagingStudy.series.performer.actor | SourceIsNarrowerThanTarget | R4B `ImagingStudy.series.performer.actor` maps as SourceIsNarrowerThanTarget to R5 `ImagingStudy.series.performer.actor` - actor has change due to type change: R4B `actor` `Reference` maps as SourceIsNarrowerThanTarget for R5 `actor` |
| ImagingStudy.series.performer.extension | ImagingStudy.series.performer.extension | RelatedTo | R4B `ImagingStudy.series.performer.extension` maps as RelatedTo to R5 `ImagingStudy.series.performer.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ImagingStudy.series.performer.function | ImagingStudy.series.performer.function | Equivalent | R4B `ImagingStudy.series.performer.function` maps as Equivalent to R5 `ImagingStudy.series.performer.function` |
| ImagingStudy.series.performer.id | ImagingStudy.series.performer.id | Equivalent | R4B `ImagingStudy.series.performer.id` maps as Equivalent to R5 `ImagingStudy.series.performer.id` |
| ImagingStudy.series.performer.modifierExtension | ImagingStudy.series.performer.modifierExtension | RelatedTo | R4B `ImagingStudy.series.performer.modifierExtension` maps as RelatedTo to R5 `ImagingStudy.series.performer.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ImagingStudy.series.specimen | ImagingStudy.series.specimen | Equivalent | R4B `ImagingStudy.series.specimen` maps as Equivalent to R5 `ImagingStudy.series.specimen` |
| ImagingStudy.series.started | ImagingStudy.series.started | Equivalent | R4B `ImagingStudy.series.started` maps as Equivalent to R5 `ImagingStudy.series.started` |
| ImagingStudy.series.uid | ImagingStudy.series.uid | Equivalent | R4B `ImagingStudy.series.uid` maps as Equivalent to R5 `ImagingStudy.series.uid` |
| ImagingStudy.started | ImagingStudy.started | Equivalent | R4B `ImagingStudy.started` maps as Equivalent to R5 `ImagingStudy.started` |
| ImagingStudy.status | ImagingStudy.status | Equivalent | R4B `ImagingStudy.status` maps as Equivalent to R5 `ImagingStudy.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/imagingstudy-status|4.3.0 and http://hl7.org/fhir/ValueSet/imagingstudy-status|5.0.0 (Equivalent) |
| ImagingStudy.subject | ImagingStudy.subject | Equivalent | R4B `ImagingStudy.subject` maps as Equivalent to R5 `ImagingStudy.subject` |
| ImagingStudy.text | ImagingStudy.text | Equivalent | R4B `ImagingStudy.text` maps as Equivalent to R5 `ImagingStudy.text` |

