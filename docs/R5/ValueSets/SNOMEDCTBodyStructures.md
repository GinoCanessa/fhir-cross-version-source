Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### SNOMEDCTBodyStructures

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SNOMEDCTBodyStructures |
| Canonical URL | `http://hl7.org/fhir/ValueSet/body-site` |
| Version | 5.0.0 |
| Description | This value set includes all codes from [SNOMED CT](http://snomed.info/sct) where concept is-a 442083009 (Anatomical or acquired body site (body structure)). |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4327` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ActivityDefinition` | `ActivityDefinition.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | What part of body to perform on |
| `http://hl7.org/fhir/StructureDefinition/BodyStructure` | `BodyStructure.includedStructure.structure` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Code that represents the included structure |
| `http://hl7.org/fhir/StructureDefinition/BodyStructure` | `BodyStructure.includedStructure.bodyLandmarkOrientation.landmarkDescription` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Body ]andmark description |
| `http://hl7.org/fhir/StructureDefinition/ChargeItem` | `ChargeItem.bodysite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Anatomical location, if relevant |
| `http://hl7.org/fhir/StructureDefinition/Condition` | `Condition.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Anatomical location, if relevant |
| `http://hl7.org/fhir/StructureDefinition/ConditionDefinition` | `ConditionDefinition.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Anatomical location, if relevant |
| `http://hl7.org/fhir/StructureDefinition/DeviceUsage` | `DeviceUsage.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Target body site |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Body part included |
| `http://hl7.org/fhir/StructureDefinition/ImagingSelection` | `ImagingSelection.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Body part examined |
| `http://hl7.org/fhir/StructureDefinition/ImagingStudy` | `ImagingStudy.series.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Body part examined |
| `http://hl7.org/fhir/StructureDefinition/Observation` | `Observation.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Observed body part |
| `http://hl7.org/fhir/StructureDefinition/ObservationDefinition` | `ObservationDefinition.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Body part to be observed |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Target body sites |
| `http://hl7.org/fhir/StructureDefinition/ServiceRequest` | `ServiceRequest.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Coded location on Body |
| `http://hl7.org/fhir/StructureDefinition/Specimen` | `Specimen.feature.type` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Highlighted feature |
| `http://hl7.org/fhir/StructureDefinition/Specimen` | `Specimen.collection.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Anatomical collection site |

### Expansion Failure

Failed to expand this value set: Expansion is limited
