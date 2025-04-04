Comparison of 
Generated at Friday, April 4, 2025 2:58:44 PM

### DocumentTypeValueSet

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | DocumentTypeValueSet |
| Canonical URL | `http://hl7.org/fhir/ValueSet/c80-doc-typecodes` |
| Version | 4.0.1 |
| Description | This is the code specifying the precise type of document (e.g. Pulmonary History and  Physical, Discharge Summary, Ultrasound Report, etc.). The Document Type value set includes all LOINC  values listed in HITSP C80 Table 2-144 Document Class Value Set Definition above used for Document Class,  and all LOINC values whose SCALE is DOC in the LOINC database. |
| Status | `Active` |
| Has Escape Valve Code | `` |
| Database Key | `2243` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.type` | `http://hl7.org/fhir/ValueSet/c80-doc-typecodes` | `Preferred` | Kind of document (LOINC if possible) |

### Expansion Failure

Failed to expand this value set: Expansion is limited
