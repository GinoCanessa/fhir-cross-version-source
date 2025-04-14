Comparison of 
Generated at Monday, April 14, 2025 6:17:14 PM

### SNOMED CT Body Structures

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | SNOMED CT Body Structures |
| Canonical URL | `http://hl7.org/fhir/ValueSet/body-site` |
| Version | 1.0.2 |
| Description | This value set includes all the "Anatomical Structure" SNOMED CT codes (i.e. codes with an is-a relationship with 91723000: Anatomical structure). |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `34` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/BodySite` | `BodySite.code` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Named anatomical location |
| `http://hl7.org/fhir/StructureDefinition/Condition` | `Condition.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Anatomical location, if relevant |
| `http://hl7.org/fhir/StructureDefinition/DiagnosticOrder` | `DiagnosticOrder.item.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Location of requested test (if applicable) |
| `http://hl7.org/fhir/StructureDefinition/ImagingStudy` | `ImagingStudy.series.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Body part examined |
| `http://hl7.org/fhir/StructureDefinition/Observation` | `Observation.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Observed body part |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Target body sites |
| `http://hl7.org/fhir/StructureDefinition/ProcedureRequest` | `ProcedureRequest.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | What part of body to perform on |
| `http://hl7.org/fhir/StructureDefinition/Specimen` | `Specimen.collection.bodySite` | `http://hl7.org/fhir/ValueSet/body-site` | `Example` | Anatomical collection site |
| `http://hl7.org/fhir/StructureDefinition/openEHR-location` | `Extension.valueCodeableConcept` | `http://hl7.org/fhir/ValueSet/body-site` | `Extensible` | Value of extension |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/body-site|1.0.2: Operation expand failed: creating the required expansion failed with message "Cannot find codesystem 'http://snomed.info/sct', so the defined filter(s) cannot be applied.".
