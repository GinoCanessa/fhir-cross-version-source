Comparison of 
Generated at Tuesday, April 1, 2025 1:39:12 PM

### SNOMED CT Body Structures

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | SNOMED CT Body Structures |
| Canonical URL | `http://hl7.org/fhir/ValueSet/body-site` |
| Version | 3.0.2 |
| Description | This value set includes all codes from [SNOMED CT](http://snomed.info/sct) where concept is-a 442083009 (Anatomical or acquired body site (body structure)). |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `1082` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ActivityDefinition` | `ActivityDefinition.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | What part of body to perform on |
| `http://hl7.org/fhir/StructureDefinition/BodySite` | `BodySite.code` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Named anatomical location |
| `http://hl7.org/fhir/StructureDefinition/ChargeItem` | `ChargeItem.bodysite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Anatomical location, if relevant |
| `http://hl7.org/fhir/StructureDefinition/Condition` | `Condition.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Anatomical location, if relevant |
| `http://hl7.org/fhir/StructureDefinition/DeviceUseStatement` | `DeviceUseStatement.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Target body site |
| `http://hl7.org/fhir/StructureDefinition/ImagingStudy` | `ImagingStudy.series.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Body part examined |
| `http://hl7.org/fhir/StructureDefinition/Media` | `Media.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Body part in media |
| `http://hl7.org/fhir/StructureDefinition/Observation` | `Observation.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Observed body part |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Target body sites |
| `http://hl7.org/fhir/StructureDefinition/ProcedureRequest` | `ProcedureRequest.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Location on Body |
| `http://hl7.org/fhir/StructureDefinition/Specimen` | `Specimen.collection.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Anatomical collection site |
| `http://hl7.org/fhir/StructureDefinition/openEHR-location` | `Extension.valueCodeableConcept` | `http://hl7.org/fhir/ValueSet/body-site` | `Extensible` | Value of extension |

### Expansion Failure

Failed to expand this value set: Expansion is limited
