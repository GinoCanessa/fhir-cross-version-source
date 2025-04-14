Comparison of 
Generated at Monday, April 14, 2025 6:17:27 PM

### v3.ActClassObservation

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | v3.ActClassObservation |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-ActClassObservation` |
| Version | 2014-03-26 |
| Description | Description:<br/><br/>An act that is intended to result in new information about a subject. The main difference between Observations and other Acts is that Observations have a value attribute. Thecode<br/><br/>attribute of Observation and thevalue<br/><br/>attribute of Observation must be considered in combination to determine the semantics of the observation.  Discussion:<br/><br/> Structurally, many observations are name-value-pairs, where the Observation.code (inherited from Act) is the name and the Observation.value is the value of the property. Such a construct is also known as a  variable (a named feature that can assume a value) hence, the Observation class is always used to hold generic name-value-pairs or variables, even though the variable valuation may not be the result of an elaborate observation method. It may be a simple answer to a question or it may be an assertion or setting of a parameter. As with all Act statements, Observation statements describe what was done, and in the case of Observations, this includes a description of what was actually observed (results or answers); and those results or answers are part of the observation and not split off into other objects. The method of action is asserted by the Observation classCode or its subclasses at the least granular level, by the Observation.code attribute value at the medium level of granularity, and by the attribute value of observation.methodCode when a finer level of granularity is required. The method in whole or in part may also appear in the attribute value of Observation.value when using coded data types to express the value of the attribute. Relevant aspects of methodology may also be restated in value when the results themselves imply or state a methodology. An observation may consist of component observations each having their own Observation.code and Observation.value. In this case, the composite observation may not have an Observation.value for itself. For instance, a white blood cell count consists of the sub-observations for the counts of the various granulocytes, lymphocytes and other normal or abnormal blood cells (e.g., blasts). The overall white blood cell count Observation itself may therefore not have a value by itself (even though it could have one, e.g., the sum total of white blood cells). Thus, as long as an Act is essentially an Act of recognizing and noting information about a subject, it is an Observation, regardless of whether it has a simple value by itself or whether it has sub-observations. Even though observations are professional acts (see Act) and as such are intentional actions, this does not require that every possible outcome of an observation be pondered in advance of it being actually made. For instance, differential white blood cell counts (WBC) rarely show blasts, but if they do, this is part of the WBC observation even though blasts might not be predefined in the structure of a normal WBC. Clinical documents commonly have Subjective and Objective findings, both of which are kinds of Observations. In addition, clinical documents commonly contain Assessments, which are also kinds of Observations. Thus, the establishment of a diagnosis is an Observation.  Examples:<br/><br/>   Recording the results of a Family History Assessment  Laboratory test and associated result  Physical exam test and associated result  Device temperature  Soil lead level |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `3280` |
| Database Concept Count | `39` |
| Database Active Concept Count | `36` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActClass`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `ALRT` | detected issue |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `BATTERY` | battery |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `CASE` | public health case |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `CLNTRL` | clinical trial |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `CNOD` | Condition Node |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `COND` | Condition |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `DETPOL` | determinant peptide |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `DGIMG` | diagnostic image |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `EXP` | expression level |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `GEN` | genomic observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `INVSTG` | investigation |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `LLD` | left lateral decubitus |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `LOC` | locus |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `OBS` | observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `OBSCOR` | correlated observation sequences |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `OBSSER` | observation series |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `OUTB` | outbreak |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `PHN` | phenotype |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `POL` | polypeptide |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `POS` | position |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `POSACC` | position accuracy |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `POSCOORD` | position coordinate |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `PRN` | prone |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `RLD` | right lateral decubitus |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `ROIBND` | bounded ROI |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `ROIOVL` | overlay ROI |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `RTRD` | reverse trendelenburg |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `SEQ` | bio sequence |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `SEQVAR` | bio sequence variation |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `SFWL` | Semi-Fowler's |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `SIT` | sitting |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `SPCOBS` | specimen observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `STN` | standing |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `SUP` | supine |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `TRD` | trendelenburg |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `VERIF` | Verification |
