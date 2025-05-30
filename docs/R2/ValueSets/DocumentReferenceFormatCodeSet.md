Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### DocumentReference Format Code Set

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | DocumentReference Format Code Set |
| Canonical URL | `http://hl7.org/fhir/ValueSet/formatcodes` |
| Version | 20150326 |
| Description | The value set is defined to be the set of format codes defined by the IHE Technical Framework, and also including additional format codes defined by the    HL7. The value set is listed in HITSP C80 Table 2-153 Format Code Value Set Definition,    with additions published later by IHE as published    at http://wiki.ihe.net/index.php?title=IHE_Format_Codes   and with additions published later by HL7 as published at http://wiki.hl7.org/index.php?title=CDA_Format_Codes_for_IHE_XDS.   This is the code specifying the technical format of the document. Along with the typeCode,    it should provide sufficient information to allow any potential document consumer to know    if it will be able to process the document. The code shall be sufficiently specific to    ensure processing/display by identifying a document encoding, structure and template. The actual list of codes here is incomplete |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `173` |
| Database Concept Count | `72` |
| Database Active Concept Count | `72` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.content.format` | `http://hl7.org/fhir/ValueSet/formatcodes` | `Preferred` | Format/content rules for the document |

### Referenced Systems

* `urn:oid:1.3.6.1.4.1.19376.1.2.3`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:hl7-org:sdwg:ccda-nonXMLBody:1.1` | For documents following C-CDA constraints using a non structured body. |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:hl7-org:sdwg:ccda-structuredBody:1.1` | For documents following C-CDA constraints using a structured body. |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:card:CRC:2012` | Cardiology CRC |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:card:EPRC-IE:2014` | Cardiology EPRC-IE |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:card:imaging:2011` | Cardiac Imaging Report |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:dent:CDA:ImagingReportStructuredHeadings:2013` | Dental CDA |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:dent:PDF` | Dental PDF |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:dent:TEXT` | Dental Text |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:iti:bppc-sd:2007` | Basic Patient Privacy Consents with Scanned Document |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:iti:bppc:2007` | Basic Patient Privacy Consents |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:iti:dsg:detached:2014` | DSG Detached Document |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:iti:dsg:enveloping:2014` | DSG Enveloping Document |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:iti:xds-sd:pdf:2008` | PDF embedded in CDA per XDS-SD profile |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:iti:xds-sd:text:2008` | Text embedded in CDA per XDS-SD profile |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:iti:xdw:2011:workflowDoc` | XDW Workflow Document |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:lab:xd-lab:2008` | CDA Laboratory Report |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:all:2010` | Anatomic Pathology Structured Report All |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:all:2010` | Anatomic Pathology Structured Report Cancer All |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:breast:2010` | Anatomic Pathology Structured Report Cancer Breast |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:cervix:2010` | Anatomic Pathology Structured Report Cancer Cervix |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:colon:2010` | Anatomic Pathology Structured Report Cancer Colon |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:endometrium:2010` | Anatomic Pathology Structured Report Cancer Endometrium |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:esophagus: 2010` | Anatomic Pathology Structured Report Cancer Esophagus |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:kidney:2010` | Anatomic Pathology Structured Report Cancer Kidney |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:larynx:2010` | Anatomic Pathology Structured Report Cancer Larynx |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:lip_oral_cavity:2010` | Anatomic Pathology Structured Report Cancer Lip Oral Cavity |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:liver:2010` | Anatomic Pathology Structured Report Cancer Liver |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:lung:2010` | Anatomic Pathology Structured Report Cancer Lung |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:ovary:2010` | Anatomic Pathology Structured Report Cancer Ovary |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:pancreas: 2010` | Anatomic Pathology Structured Report Cancer Pancreas |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:pharynx:2010` | Anatomic Pathology Structured Report Cancer Pharynx |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:prostate:2010` | Anatomic Pathology Structured Report Cancer Prostate |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:salivary_gland:2010` | Anatomic Pathology Structured Report Cancer Salivary Gland |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:skin:2010` | Anatomic Pathology Structured Report Cancer Skin |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:stomach: 2010` | Anatomic Pathology Structured Report Cancer Stomach |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:testis:2010` | Anatomic Pathology Structured Report Cancer Testis |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:thyroid:2010` | Anatomic Pathology Structured Report Cancer Thyroid |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pat:apsr:cancer:urinary_bladder:2010` | Anatomic Pathology Structured Report Cancer Urinary Bladder |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:apr:edu:2008` | Antepartum Record (APR) - Education |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:apr:handp:2008` | Antepartum Record (APR) - History and Physical |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:apr:lab:2008` | Antepartum Record (APR) - Laboratory |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:aps:2007` | IHE Antepartum Summary |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:cm:2008` | Care Management (CM) |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:crc:2008` | Cancer Registry Content (CRC) |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:ctn:2007` | PCC CTN |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:edes:2007` | Emergency Department Encounter Summary (EDES) |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:edpn:2007` | PCC EDPN |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:edr:2007` | Emergency Department Referral (EDR) |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:ets:2011` | PCC ETS |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:handp:2008` | History and Physical Specification |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:hp:2008` | PCC HP |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:ic:2009` | Immunization Content (IC) |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:irc:2008` | Immunization Registry Content (IRC) |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:its:2011` | PCC ITS |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:ldhp:2009` | PCC LDHP |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:lds:2009` | PCC LDS |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:mds:2009` | PCC MDS |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:nds:2010` | PCC NDS |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:nn:2007` | PCC NN |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:ppvs:2010` | PCC PPVS |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:tn:2007` | PCC TN |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:trs:2011` | PCC TRS |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:xds-ms:2007` | XDS Medical Summaries |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:xphr:2007` | HL7 CCD Document |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pcc:xphr:2007` | Personal Health Records |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pharm:dis:2010` | Pharmacy DIS |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pharm:padv:2010` | Pharmacy PADV |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pharm:pml:2013` | Pharmacy PML |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:pharm:pre:2010` | Pharmacy Pre |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:rad:CDA:ImagingReportStructuredHeadings:2013` | Radiology XDS-I Structured CDA |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:rad:PDF` | Radiology XDS-I PDF |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | `urn:ihe:rad:TEXT` | Radiology XDS-I Text |
