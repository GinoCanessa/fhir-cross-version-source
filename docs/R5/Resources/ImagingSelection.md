Comparison of 
Generated at Thursday, April 3, 2025 8:18:35 AM

### ImagingSelection

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | ImagingSelection |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ImagingSelection` |
| Version | 5.0.0 |
| Description | A selection of DICOM SOP instances and/or frames within a single Study and Series. This might include additional specifics such as an image region, an Observation UID or a Segmentation Number, allowing linkage to an Observation Resource or transferring this information along with the ImagingStudy Resource. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2319` |
| Database Snapshot Count | `50` |
| Database Differential Count | `30` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ImagingSelection` | `ImagingSelection` | `ImagingSelection` | ImagingSelection | A selection of DICOM SOP instances and/or frames | 0..* | ImagingSelection |  |  |
| `ImagingSelection.basedOn` | `ImagingSelection.basedOn` | `basedOn` | ImagingSelection.basedOn | Associated request | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Appointment), Reference(http://hl7.org/fhir/StructureDefinition/AppointmentResponse), Reference(http://hl7.org/fhir/StructureDefinition/CarePlan), Reference(http://hl7.org/fhir/StructureDefinition/ServiceRequest), Reference(http://hl7.org/fhir/StructureDefinition/Task) |  |  |
| `ImagingSelection.bodySite` | `ImagingSelection.bodySite` | `bodySite` | ImagingSelection.bodySite | Body part examined | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/BodyStructure) | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `ImagingSelection.category` | `ImagingSelection.category` | `category` | ImagingSelection.category | Classifies the imaging selection | 0..* | CodeableConcept | `Example` | `http://dicom.nema.org/medical/dicom/current/output/chtml/part16/sect_CID_7010.html` |
| `ImagingSelection.code` | `ImagingSelection.code` | `code` | ImagingSelection.code | Imaging Selection purpose text or code | 1..1 | CodeableConcept | `Example` | `http://dicom.nema.org/medical/dicom/current/output/chtml/part16/sect_CID_7010.html` |
| `ImagingSelection.contained` | `ImagingSelection.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ImagingSelection.derivedFrom` | `ImagingSelection.derivedFrom` | `derivedFrom` | ImagingSelection.derivedFrom | The imaging study from which the imaging selection is derived | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/ImagingStudy) |  |  |
| `ImagingSelection.endpoint` | `ImagingSelection.endpoint` | `endpoint` | ImagingSelection.endpoint | The network service providing retrieval for the images referenced in the imaging selection | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Endpoint) |  |  |
| `ImagingSelection.extension` | `ImagingSelection.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ImagingSelection.focus` | `ImagingSelection.focus` | `focus` | ImagingSelection.focus | Related resource that is the focus for the imaging selection | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ImagingSelection) |  |  |
| `ImagingSelection.frameOfReferenceUid` | `ImagingSelection.frameOfReferenceUid` | `frameOfReferenceUid` | ImagingSelection.frameOfReferenceUid | The Frame of Reference UID for the selected images | 0..1 | id |  |  |
| `ImagingSelection.id` | `ImagingSelection.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ImagingSelection.identifier` | `ImagingSelection.identifier` | `identifier` | ImagingSelection.identifier | Business Identifier for Imaging Selection | 0..* | Identifier |  |  |
| `ImagingSelection.implicitRules` | `ImagingSelection.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ImagingSelection.instance` | `ImagingSelection.instance` | `instance` | ImagingSelection.instance | The selected instances | 0..* | BackboneElement |  |  |
| `ImagingSelection.instance.extension` | `ImagingSelection.instance.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ImagingSelection.instance.id` | `ImagingSelection.instance.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ImagingSelection.instance.imageRegion2D` | `ImagingSelection.instance.imageRegion2D` | `imageRegion2D` | ImagingSelection.instance.imageRegion2D | A specific 2D region in a DICOM image / frame | 0..* | BackboneElement |  |  |
| `ImagingSelection.instance.imageRegion2D.coordinate` | `ImagingSelection.instance.imageRegion2D.coordinate` | `coordinate` | ImagingSelection.instance.imageRegion2D.coordinate | Specifies the coordinates that define the image region | 1..* | decimal |  |  |
| `ImagingSelection.instance.imageRegion2D.extension` | `ImagingSelection.instance.imageRegion2D.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ImagingSelection.instance.imageRegion2D.id` | `ImagingSelection.instance.imageRegion2D.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ImagingSelection.instance.imageRegion2D.modifierExtension` | `ImagingSelection.instance.imageRegion2D.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ImagingSelection.instance.imageRegion2D.regionType` | `ImagingSelection.instance.imageRegion2D.regionType` | `regionType` | ImagingSelection.instance.imageRegion2D.regionType | point \| polyline \| interpolated \| circle \| ellipse | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/imagingselection-2dgraphictype|5.0.0` |
| `ImagingSelection.instance.imageRegion3D` | `ImagingSelection.instance.imageRegion3D` | `imageRegion3D` | ImagingSelection.instance.imageRegion3D | A specific 3D region in a DICOM frame of reference | 0..* | BackboneElement |  |  |
| `ImagingSelection.instance.imageRegion3D.coordinate` | `ImagingSelection.instance.imageRegion3D.coordinate` | `coordinate` | ImagingSelection.instance.imageRegion3D.coordinate | Specifies the coordinates that define the image region | 1..* | decimal |  |  |
| `ImagingSelection.instance.imageRegion3D.extension` | `ImagingSelection.instance.imageRegion3D.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ImagingSelection.instance.imageRegion3D.id` | `ImagingSelection.instance.imageRegion3D.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ImagingSelection.instance.imageRegion3D.modifierExtension` | `ImagingSelection.instance.imageRegion3D.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ImagingSelection.instance.imageRegion3D.regionType` | `ImagingSelection.instance.imageRegion3D.regionType` | `regionType` | ImagingSelection.instance.imageRegion3D.regionType | point \| multipoint \| polyline \| polygon \| ellipse \| ellipsoid | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/imagingselection-3dgraphictype|5.0.0` |
| `ImagingSelection.instance.modifierExtension` | `ImagingSelection.instance.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ImagingSelection.instance.number` | `ImagingSelection.instance.number` | `number` | ImagingSelection.instance.number | DICOM Instance Number | 0..1 | unsignedInt |  |  |
| `ImagingSelection.instance.sopClass` | `ImagingSelection.instance.sopClass` | `sopClass` | ImagingSelection.instance.sopClass | DICOM SOP Class UID | 0..1 | Coding | `Extensible` | `http://dicom.nema.org/medical/dicom/current/output/chtml/part04/sect_B.5.html#table_B.5-1` |
| `ImagingSelection.instance.subset` | `ImagingSelection.instance.subset` | `subset` | ImagingSelection.instance.subset | The selected subset of the SOP Instance | 0..* | string |  |  |
| `ImagingSelection.instance.uid` | `ImagingSelection.instance.uid` | `uid` | ImagingSelection.instance.uid | DICOM SOP Instance UID | 1..1 | id |  |  |
| `ImagingSelection.issued` | `ImagingSelection.issued` | `issued` | ImagingSelection.issued | Date / Time when this imaging selection was created | 0..1 | instant |  |  |
| `ImagingSelection.language` | `ImagingSelection.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `ImagingSelection.meta` | `ImagingSelection.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ImagingSelection.modifierExtension` | `ImagingSelection.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ImagingSelection.performer` | `ImagingSelection.performer` | `performer` | ImagingSelection.performer | Selector of the instances (human or machine) | 0..* | BackboneElement |  |  |
| `ImagingSelection.performer.actor` | `ImagingSelection.performer.actor` | `actor` | ImagingSelection.performer.actor | Author (human or machine) | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `ImagingSelection.performer.extension` | `ImagingSelection.performer.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ImagingSelection.performer.function` | `ImagingSelection.performer.function` | `function` | ImagingSelection.performer.function | Type of performer | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/series-performer-function` |
| `ImagingSelection.performer.id` | `ImagingSelection.performer.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ImagingSelection.performer.modifierExtension` | `ImagingSelection.performer.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ImagingSelection.seriesNumber` | `ImagingSelection.seriesNumber` | `seriesNumber` | ImagingSelection.seriesNumber | DICOM Series Number | 0..1 | unsignedInt |  |  |
| `ImagingSelection.seriesUid` | `ImagingSelection.seriesUid` | `seriesUid` | ImagingSelection.seriesUid | DICOM Series Instance UID | 0..1 | id |  |  |
| `ImagingSelection.status` | `ImagingSelection.status` | `status` | ImagingSelection.status | available \| entered-in-error \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/imagingselection-status|5.0.0` |
| `ImagingSelection.studyUid` | `ImagingSelection.studyUid` | `studyUid` | ImagingSelection.studyUid | DICOM Study Instance UID | 0..1 | id |  |  |
| `ImagingSelection.subject` | `ImagingSelection.subject` | `subject` | ImagingSelection.subject | Subject of the selected instances | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/Procedure), Reference(http://hl7.org/fhir/StructureDefinition/Specimen), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `ImagingSelection.text` | `ImagingSelection.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

