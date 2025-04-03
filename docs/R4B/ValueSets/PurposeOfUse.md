Comparison of 
Generated at Thursday, April 3, 2025 8:18:24 AM

### PurposeOfUse

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | PurposeOfUse |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` |
| Version | 2.0.0 |
| Description | Supports communication of purpose of use at a general level. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4230` |
| Database Concept Count | `59` |
| Database Active Concept Count | `59` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.purposeOfEvent` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` | `Extensible` | The purposeOfUse of the event |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.agent.purposeOfUse` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` | `Extensible` | Reason given for this user |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.provision.purpose` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` | `Extensible` | Context of activities covered by this rule |
| `http://hl7.org/fhir/StructureDefinition/Contract` | `Contract.term.action.intent` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` | `Example` | Purpose for the Contract Term Action |
| `http://hl7.org/fhir/StructureDefinition/Contract` | `Contract.term.action.reasonCode` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` | `Example` | Why is action (not) needed? |
| `http://hl7.org/fhir/StructureDefinition/Provenance` | `Provenance.reason` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` | `Extensible` | Reason the activity is occurring |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActReason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `BIORCH` | biomedical research |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `BTG` | break the glass |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `CAREMGT` | care management |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `CLINTRCH` | clinical trial research |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `CLINTRCHNPC` | clinical trial research without patient care |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `CLINTRCHPC` | clinical trial research with patient care |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `CLINTRL` | clinical trial |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `CLMATTCH` | claim attachment |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `COC` | coordination of care |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `COVAUTH` | coverage authorization |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `COVERAGE` | coverage under policy or program |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `DISASTER` | disaster |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `DONAT` | donation |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `DSRCH` | disease specific healthcare research |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `ELIGDTRM` | eligibility determination |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `ELIGVER` | eligibility verification |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `ENROLLM` | enrollment |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `ERTREAT` | emergency room treatment |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `ETREAT` | Emergency Treatment |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `FAMRQT` | family requested |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `FRAUD` | fraud |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `GOV` | government |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HACCRED` | health accreditation |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HCOMPL` | health compliance |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HDECD` | decedent |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HDIRECT` | directory |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HDM` | healthcare delivery management |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HLEGAL` | legal |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HMARKT` | healthcare marketing |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HOPERAT` | healthcare operations |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HOUTCOMS` | health outcome measure |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HPAYMT` | healthcare payment |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HPRGRP` | health program reporting |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HQUALIMP` | health quality improvement |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HRESCH` | healthcare research |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HSYSADMIN` | health system administration |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HTEST` | test health data |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `LABELING` | labeling |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `MEMADMIN` | member administration |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `METAMGT` | metadata management |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `MILCDM` | military command |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `MILDCRG` | military discharge |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `PATADMIN` | patient administration |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `PATRQT` | patient requested |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `PATSFTY` | patient safety |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `PERFMSR` | performance measure |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `POARCH` | population origins or ancestry healthcare research |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `POPHLTH` | population health |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `PRECLINTRCH` | preclinical trial research |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `PUBHLTH` | public health |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `PWATRNY` | power of attorney |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `RECORDMGT` | records management |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `REMITADV` | remittance advice |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `SUPNWK` | support network |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `SYSDEV` | system development |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `THREAT` | threat |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `TRAIN` | training |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `TRANSRCH` | translational healthcare research |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `TREAT` | treatment |
