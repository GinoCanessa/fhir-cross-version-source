Comparison of 
Generated at Friday, April 4, 2025 2:58:31 PM

### Document Class Value Set

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Document Class Value Set |
| Canonical URL | `http://hl7.org/fhir/ValueSet/c80-doc-classcodes` |
| Version | 20091109 |
| Description | This is the code specifying the high-level kind of document (e.g. Prescription, Discharge Summary, Report, etc.). The Document Class value set is reproduced from HITSP C80 Table 2-144 Document Class Value Set Definition. Note: Class code for documents comes from LOINC, and is based upon one of the following:The type of service described by the document. It is described at a very high level in Section 7.3 of the LOINC Manual. The type study performed. It was determined by identifying modalities for study reports. The section of the chart where the document is placed. It was determined from the SETs created for Claims Attachment requests. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `38` |
| Database Concept Count | `45` |
| Database Active Concept Count | `45` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.class` | `http://hl7.org/fhir/ValueSet/c80-doc-classcodes` | `Example` | Categorization of document |

### Referenced Systems

* `http://loinc.org`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://loinc.org` | `11369-6` | History of Immunization |
| `http://loinc.org` | `11485-0` | Anesthesia records |
| `http://loinc.org` | `11486-8` | Chemotherapy records |
| `http://loinc.org` | `11488-4` | Consult Note |
| `http://loinc.org` | `11504-8` | Surgical operation note |
| `http://loinc.org` | `11506-3` | Provider-unspecified progress note |
| `http://loinc.org` | `11543-6` | Nursery records |
| `http://loinc.org` | `15508-5` | Labor and delivery records |
| `http://loinc.org` | `18726-0` | Radiology studies (set) |
| `http://loinc.org` | `18748-4` | Diagnostic imaging study |
| `http://loinc.org` | `18761-7` | Provider-unspecified transfer summary |
| `http://loinc.org` | `18842-5` | Discharge summary |
| `http://loinc.org` | `26436-6` | Laboratory Studies (set) |
| `http://loinc.org` | `26441-6` | Cardiology studies (set) |
| `http://loinc.org` | `26442-4` | Obstetrical studies (set) |
| `http://loinc.org` | `27895-2` | Gastroenterology endoscopy studies (set) |
| `http://loinc.org` | `27896-0` | Pulmonary studies (set) |
| `http://loinc.org` | `27897-8` | Neuromuscular electrophysiology studies (set) |
| `http://loinc.org` | `27898-6` | Pathology studies (set) |
| `http://loinc.org` | `28570-0` | Provider-unspecified procedure note |
| `http://loinc.org` | `28619-5` | Ophthalmology/optometry studies (set) |
| `http://loinc.org` | `28634-4` | Miscellaneous studies (set) |
| `http://loinc.org` | `29749-9` | Dialysis records |
| `http://loinc.org` | `29750-7` | Neonatal intensive care records |
| `http://loinc.org` | `29751-5` | Critical care records |
| `http://loinc.org` | `29752-3` | Perioperative records |
| `http://loinc.org` | `34109-9` | Evaluation and management note |
| `http://loinc.org` | `34117-2` | Provider-unspecified, History and physical note |
| `http://loinc.org` | `34121-4` | Interventional procedure note |
| `http://loinc.org` | `34122-2` | Pathology procedure note |
| `http://loinc.org` | `34133-9` | Summarization of episode note |
| `http://loinc.org` | `34140-4` | Transfer of care referral note |
| `http://loinc.org` | `34748-4` | Telephone encounter note |
| `http://loinc.org` | `34775-7` | General surgery Pre-operative evaluation and management note |
| `http://loinc.org` | `47039-3` | Inpatient Admission history and physical note |
| `http://loinc.org` | `47042-7` | Counseling note |
| `http://loinc.org` | `47045-0` | Study report Document |
| `http://loinc.org` | `47046-8` | Summary of death |
| `http://loinc.org` | `47049-2` | Non-patient Communication |
| `http://loinc.org` | `53576-5` | Personal health monitoring report Document |
| `http://loinc.org` | `56445-0` | Medication Summary Document |
| `http://loinc.org` | `56447-6` | Plan of care note |
| `http://loinc.org` | `57016-8` | Privacy Policy Acknowledgment Document |
| `http://loinc.org` | `57017-6` | Privacy Policy Organization Document |
| `http://loinc.org` | `57133-1` | Referral note |
