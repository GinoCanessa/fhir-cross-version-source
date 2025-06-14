### Lookup for FHIR R2 ImagingStudy for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ImagingStudy.id | UseElementSameName | ImagingStudy.id |
| ImagingStudy.meta | UseElementSameName | ImagingStudy.meta |
| ImagingStudy.implicitRules | UseElementSameName | ImagingStudy.implicitRules |
| ImagingStudy.language | UseElementSameName | ImagingStudy.language |
| ImagingStudy.text | UseElementSameName | ImagingStudy.text |
| ImagingStudy.contained | UseElementSameName | ImagingStudy.contained |
| ImagingStudy.extension | UseElementSameName | ImagingStudy.extension |
| ImagingStudy.modifierExtension | UseElementSameName | ImagingStudy.modifierExtension |
| ImagingStudy.started | UseElementSameName | ImagingStudy.started |
| ImagingStudy.patient | UseElementSameName | ImagingStudy.patient |
| ImagingStudy.uid | UseElementSameName | ImagingStudy.uid |
| ImagingStudy.accession | UseElementSameName | ImagingStudy.accession |
| ImagingStudy.identifier | UseElementSameName | ImagingStudy.identifier |
| ImagingStudy.order | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ImagingStudy.order |
| ImagingStudy.modalityList | UseElementSameName | ImagingStudy.modalityList |
| ImagingStudy.referrer | UseElementSameName | ImagingStudy.referrer |
| ImagingStudy.availability | UseOneOfElements | ImagingStudy.availability,ImagingStudy.availability |
| ImagingStudy.url | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ImagingStudy.url |
| ImagingStudy.numberOfSeries | UseElementSameName | ImagingStudy.numberOfSeries |
| ImagingStudy.numberOfInstances | UseElementSameName | ImagingStudy.numberOfInstances |
| ImagingStudy.procedure | UseElementRenamed | ImagingStudy.procedureReference |
| ImagingStudy.interpreter | UseElementSameName | ImagingStudy.interpreter |
| ImagingStudy.description | UseElementSameName | ImagingStudy.description |
| ImagingStudy.series | UseElementSameName | ImagingStudy.series |
| ImagingStudy.series.id | UseElementSameName | ImagingStudy.series.id |
| ImagingStudy.series.extension | UseElementSameName | ImagingStudy.series.extension |
| ImagingStudy.series.modifierExtension | UseElementSameName | ImagingStudy.series.modifierExtension |
| ImagingStudy.series.number | UseElementSameName | ImagingStudy.series.number |
| ImagingStudy.series.modality | UseElementSameName | ImagingStudy.series.modality |
| ImagingStudy.series.uid | UseElementSameName | ImagingStudy.series.uid |
| ImagingStudy.series.description | UseElementSameName | ImagingStudy.series.description |
| ImagingStudy.series.numberOfInstances | UseElementSameName | ImagingStudy.series.numberOfInstances |
| ImagingStudy.series.availability | UseElementSameName | ImagingStudy.series.availability |
| ImagingStudy.series.url | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ImagingStudy.series.url |
| ImagingStudy.series.bodySite | UseElementSameName | ImagingStudy.series.bodySite |
| ImagingStudy.series.laterality | UseElementSameName | ImagingStudy.series.laterality |
| ImagingStudy.series.started | UseElementSameName | ImagingStudy.series.started |
| ImagingStudy.series.instance | UseElementSameName | ImagingStudy.series.instance |
| ImagingStudy.series.instance.id | UseElementSameName | ImagingStudy.series.instance.id |
| ImagingStudy.series.instance.extension | UseElementSameName | ImagingStudy.series.instance.extension |
| ImagingStudy.series.instance.modifierExtension | UseElementSameName | ImagingStudy.series.instance.modifierExtension |
| ImagingStudy.series.instance.number | UseElementSameName | ImagingStudy.series.instance.number |
| ImagingStudy.series.instance.uid | UseElementSameName | ImagingStudy.series.instance.uid |
| ImagingStudy.series.instance.sopClass | UseElementSameName | ImagingStudy.series.instance.sopClass |
| ImagingStudy.series.instance.type | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ImagingStudy.series.instance.type |
| ImagingStudy.series.instance.title | UseElementSameName | ImagingStudy.series.instance.title |
| ImagingStudy.series.instance.content | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ImagingStudy.series.instance.content |
