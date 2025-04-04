Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### DocumentReferenceFormatCodeSet

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | DocumentReferenceFormatCodeSet |
| Canonical URL | `http://hl7.org/fhir/ValueSet/formatcodes` |
| Version | 4.3.0 |
| Description | The value set is defined to be the set of format codes defined by the IHE Technical Framework, and also including additional format codes defined by the    HL7. The value set is listed in HITSP C80 Table 2-153 Format Code Value Set Definition,    with additions published later by IHE as published    at http://wiki.ihe.net/index.php?title=IHE_Format_Codes   and with additions published later by HL7 as published at https://confluence.hl7.org/display/SD/Format+Codes+for+IHE+XDS.   This is the code specifying the technical format of the document. Along with the typeCode,    it should provide sufficient information to allow any potential document consumer to know    if it will be able to process the document. The code shall be sufficiently specific to    ensure processing/display by identifying a document encoding, structure and template. The actual list of codes here is incomplete |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `3789` |
| Database Concept Count | `74` |
| Database Active Concept Count | `74` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.content.format` | `http://hl7.org/fhir/ValueSet/formatcodes` | `Preferred` | Format/content rules for the document |

### Referenced Systems

* `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:hl7-org:sdwg:ccda-nonXMLBody:1.1` | For documents following C-CDA 1.1 constraints using a non structured body. |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:hl7-org:sdwg:ccda-nonXMLBody:2.1` | For documents following C-CDA 2.1 constraints using a non structured body. |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:hl7-org:sdwg:ccda-structuredBody:1.1` | For documents following C-CDA 1.1 constraints using a structured body. |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:hl7-org:sdwg:ccda-structuredBody:2.1` | For documents following C-CDA 2.1 constraints using a structured body. |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:card:CRC:2012` | Cardiology CRC |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:card:EPRC-IE:2014` | Cardiology EPRC-IE |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:card:imaging:2011` | Cardiac Imaging Report |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:dent:CDA:ImagingReportStructuredHeadings:2013` | Dental CDA |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:dent:PDF` | Dental PDF |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:dent:TEXT` | Dental Text |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:iti:appc:2016:consent` | Advanced Patient Privacy Consents |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:iti:bppc-sd:2007` | Basic Patient Privacy Consents with Scanned Document |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:iti:bppc:2007` | Basic Patient Privacy Consents |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:iti:dsg:detached:2014` | DSG Detached Document |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:iti:dsg:enveloping:2014` | DSG Enveloping Document |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:iti:xds-sd:pdf:2008` | PDF embedded in CDA per XDS-SD profile |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:iti:xds-sd:text:2008` | Text embedded in CDA per XDS-SD profile |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:iti:xds:2017:mimeTypeSufficient` | mimeType Sufficient |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:iti:xdw:2011:workflowDoc` | XDW Workflow Document |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:lab:xd-lab:2008` | CDA Laboratory Report |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:all:2010` | Anatomic Pathology Structured Report All |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:all:2010` | Anatomic Pathology Structured Report Cancer All |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:breast:2010` | Anatomic Pathology Structured Report Cancer Breast |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:cervix:2010` | Anatomic Pathology Structured Report Cancer Cervix |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:colon:2010` | Anatomic Pathology Structured Report Cancer Colon |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:endometrium:2010` | Anatomic Pathology Structured Report Cancer Endometrium |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:esophagus:2010` | Anatomic Pathology Structured Report Cancer Esophagus |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:kidney:2010` | Anatomic Pathology Structured Report Cancer Kidney |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:larynx:2010` | Anatomic Pathology Structured Report Cancer Larynx |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:lip_oral_cavity:2010` | Anatomic Pathology Structured Report Cancer Lip Oral Cavity |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:liver:2010` | Anatomic Pathology Structured Report Cancer Liver |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:lung:2010` | Anatomic Pathology Structured Report Cancer Lung |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:ovary:2010` | Anatomic Pathology Structured Report Cancer Ovary |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:pancreas:2010` | Anatomic Pathology Structured Report Cancer Pancreas |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:pharynx:2010` | Anatomic Pathology Structured Report Cancer Pharynx |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:prostate:2010` | Anatomic Pathology Structured Report Cancer Prostate |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:salivary_gland:2010` | Anatomic Pathology Structured Report Cancer Salivary Gland |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:skin:2010` | Anatomic Pathology Structured Report Cancer Skin |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:stomach:2010` | Anatomic Pathology Structured Report Cancer Stomach |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:testis:2010` | Anatomic Pathology Structured Report Cancer Testis |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:thyroid:2010` | Anatomic Pathology Structured Report Cancer Thyroid |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pat:apsr:cancer:urinary_bladder:2010` | Anatomic Pathology Structured Report Cancer Urinary Bladder |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:apr:edu:2008` | Antepartum Record (APR) - Education |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:apr:handp:2008` | Antepartum Record (APR) - History and Physical |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:apr:lab:2008` | Antepartum Record (APR) - Laboratory |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:aps:2007` | IHE Antepartum Summary |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:cm:2008` | Care Management (CM) |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:crc:2008` | Cancer Registry Content (CRC) |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:ctn:2007` | PCC CTN |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:edes:2007` | Emergency Department Encounter Summary (EDES) |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:edpn:2007` | PCC EDPN |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:edr:2007` | Emergency Department Referral (EDR) |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:ets:2011` | PCC ETS |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:hp:2008` | PCC HP |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:ic:2008` | Immunization Content (IC) |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:its:2011` | PCC ITS |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:ldhp:2009` | PCC LDHP |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:lds:2009` | PCC LDS |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:mds:2009` | PCC MDS |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:nds:2010` | PCC NDS |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:nn:2007` | PCC NN |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:ppvs:2010` | PCC PPVS |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:ript:2017` | Routine Interfacility Patient Transport (RIPT) |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:tn:2007` | PCC TN |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:trs:2011` | PCC TRS |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:xds-ms:2007` | XDS Medical Summaries |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pcc:xphr:2007` | Personal Health Records. Also known as HL7 CCD and HITSP C32 |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pharm:dis:2010` | Pharmacy DIS |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pharm:padv:2010` | Pharmacy PADV |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pharm:pml:2013` | Pharmacy PML |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:pharm:pre:2010` | Pharmacy Pre |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:rad:CDA:ImagingReportStructuredHeadings:2013` | Radiology XDS-I Structured CDA |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:rad:PDF` | Radiology XDS-I PDF |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | `urn:ihe:rad:TEXT` | Radiology XDS-I Text |
