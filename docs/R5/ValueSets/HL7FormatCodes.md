Comparison of 
Generated at Friday, April 4, 2025 2:59:00 PM

### HL7FormatCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | HL7FormatCodes |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-HL7FormatCodes` |
| Version | 1.0.0 |
| Description | The HL7-FormatCodes value set is defined to be the set of FormatCode(s) defined by implementation guides published by HL7 and other SDOs. The use of a formatCode from the FormatCodes value set specifies the technical format that a document conforms to. The formatCode is a further specialization more detailed than the mime-type. The formatCode provides sufficient information to allow any potential document content consumer to know if it can process and/or display the content of the document based on the document encoding, structure and template conformance indicated by the formatCode. The set of formatCodes is intended to be extensible. The Content Logical Description is defined intentionally to permit formatCodes defined by other Standards Development Organizations to be added by inclusion of additional formatCode Code Systems. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `5054` |
| Database Concept Count | `104` |
| Database Active Concept Count | `104` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.content.profile.value[x]` | `http://terminology.hl7.org/ValueSet/v3-HL7FormatCodes` | `Preferred` | Code\|uri\|canonical |

### Referenced Systems

* `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode`
* `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:hl7-org:sdwg:ccda-nonXMLBody:1.1` | For documents following C-CDA 1.1 constraints using a non structured body. |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:hl7-org:sdwg:ccda-nonXMLBody:2.1` | For documents following C-CDA 2.1 constraints using a non structured body. |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:hl7-org:sdwg:ccda-structuredBody:1.1` | For documents following C-CDA 1.1 constraints using a structured body. |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:hl7-org:sdwg:ccda-structuredBody:2.1` | For documents following C-CDA 2.1 constraints using a structured body. |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe.palm:apsr:2016` | PALM APSR |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:card:CPN:2017` | CARD CPN |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:card:CRC:2012` | CARD CRC |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:card:EPRC-IE:2014` | CARD EPRC-IE |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:card:imaging:2011` | CARD Imaging |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:dent:CDA:ImagingReportStructuredHeadings:2013` | DENT CDA |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:dent:PDF` | DENT PDF |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:dent:TEXT` | DENT TEXT |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:iti:appc:2016:consent` | ITI APPC |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:iti:bppc-sd:2007` | ITI BPPC-SD |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:iti:bppc:2007` | ITI BPPC |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:iti:dsg:detached:2014` | ITI DSG Detached |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:iti:dsg:enveloping:2014` | ITI DSG Enveloping |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:iti:xds-sd:pdf:2008` | ITI XDS-SD PDF |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:iti:xds-sd:text:2008` | ITI XDS-SD TEXT |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:iti:xds:2017:mimeTypeSufficient` | mimeType Sufficient |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:iti:xdw:2011:workflowDoc` | ITI XDW |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:lab:xd-lab:2008` | LAB XD-LAB |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:360x:hl7:OMG:O19:2017` | PCC 360X Referral Request |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:360x:hl7:OSU:O51:2017` | PCC 360X Referral Status Update |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:360x:hl7:SIU:S12:2017` | PCC 360X Appointment Notification |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:360x:hl7:SIU:S13:2017` | PCC 360X Appointment Reschedule Notification |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:360x:hl7:SIU:S15:2017` | PCC 360X Appointment Cancel Notification |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:360x:hl7:SIU:S26:2017` | PCC 360X Appointment No-show Notification |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:apr:edu:2008` | PCC APR EDU |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:apr:handp:2008` | PCC APR HANDP |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:apr:lab:2008` | PCC APR LAB |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:aps:2007` | PCC APS |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:cm:2008` | Care Management (CM) |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:crc:2008` | PCC CRC |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:ctn:2007` | PCC CTN |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:edes:2007` | PCC EDES |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:edpn:2007` | PCC EDPN |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:edr:2007` | PCC EDR |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:ets:2011` | PCC ETS |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:hp:2008` | PCC HP |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:ic:2008` | Immunization Registry Content (IRC) |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:ips:2020` | PCC IPS |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:its:2011` | PCC ITS |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:ldhp:2009` | PCC LDHP |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:lds:2009` | PCC LDS |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:mds:2009` | PCC MDS |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:nds:2010` | PCC NDS |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:nn:2007` | PCC NN |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:pcs-cr:2018` | PCC PCS-CR |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:pcs-cs:2018` | PCC PCS-CS |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:ppvs:2010` | PCC PPVS |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:ript:2017` | PCC RIPT |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:tn:2007` | PCC TN |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:trs:2011` | PCC TRS |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:xds-ms:2007` | PCC XDS-MS |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pcc:xphr:2007` | PCC XPHR |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pharm:cma:2017` | Pharmacy CMA |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pharm:dis:2010` | Pharmacy DIS |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pharm:mtp:2015` | Pharmacy MTP |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pharm:padv:2010` | Pharmacy PADV |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pharm:pml:2013` | Pharmacy PML |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:pharm:pre:2010` | Pharmacy PRE |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:BFDR-Birth:2014` | QRPH BFDR Birth CDA document |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:BFDR-FDeath:2014` | QRPH BFDR Death CDA document |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:HPoCUS:2014` | QRPH HPoC US |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:HPoCUV:2014` | QRPH HPoC UV |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:LDS-VR:2013` | QRPH LDS-VR |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:NHS-CatIII-UV:2015` | QRPH EHDI NHS Cat III |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:NHS-Catl-UV:2015` | QRPH EHDI NHS Cat I |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:bfdr:2011` | QRPH BFDR |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:crd:2008` | QRPH CRD |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:crpc:2012` | QRPH CRPC |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:dsc:2008` | QRPH DSC |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:ehcp:2010` | QRPH EHCP |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:ehdi:2014` | QRPH EHDI |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:ehdiwd:2013` | QRPH EHDI-WD |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:fp:2014` | QRPH FP |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:fp:2017` | QRPH FP V2 |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:hbs:2009` | QRPH HBS |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:hw:2013` | QRPH HW |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:mch:2009` | QRPH MCH |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:ms-vrdr:2013` | QRPH MS-VRDR |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:prph:2009` | QRPH PRPH-Ca |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:prq:2019` | QRPH PRQ |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:qmd-eh:2010` | QRPH QMD-EH |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:qme-eh:2010` | QRPH QME-EH |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:qrph:vrdr:2013` | QRPH VRDR |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:rad:CDA:ImagingReportStructuredHeadings:2013` | RAD CDA |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:rad:PDF` | RAD PDF |
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | `urn:ihe:rad:TEXT` | RAD TEXT |
| `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes` | `urn:hl7-org:sdwg:ccda-nonXMLBody:1.1` | ccda-nonXMLBody:1.1 |
| `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes` | `urn:hl7-org:sdwg:ccda-nonXMLBody:2.1` | ccda-nonXMLBody:2.1 |
| `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes` | `urn:hl7-org:sdwg:ccda-nonXMLBody:2.2` | ccda-nonXMLBody:2.2 |
| `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes` | `urn:hl7-org:sdwg:ccda-structuredBody:1.1` | ccda-structuredBody:1.1 |
| `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes` | `urn:hl7-org:sdwg:ccda-structuredBody:2.1` | ccda-structuredBody:2.1 |
| `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes` | `urn:hl7-org:sdwg:ccda-structuredBody:2.2` | ccda-structuredBody:2.2 |
| `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes` | `urn:hl7-org:sdwg:pacp-nonXMLBody:1.0` | pacp-nonXMLBody:1.0 |
| `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes` | `urn:hl7-org:sdwg:pacp-nonXMLBody:1.1` | pacp-nonXMLBody:1.1 |
| `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes` | `urn:hl7-org:sdwg:pacp-nonXMLBody:1.2` | pacp-nonXMLBody:1.2 |
| `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes` | `urn:hl7-org:sdwg:pacp-nonXMLBody:1.3` | pacp-nonXMLBody:1.3 |
| `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes` | `urn:hl7-org:sdwg:pacp-structuredBody:1.0` | pacp-structuredBody:1.0 |
| `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes` | `urn:hl7-org:sdwg:pacp-structuredBody:1.1` | pacp-structuredBody:1.1 |
| `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes` | `urn:hl7-org:sdwg:pacp-structuredBody:1.2` | pacp-structuredBody:1.2 |
| `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes` | `urn:hl7-org:sdwg:pacp-structuredBody:1.3` | pacp-structuredBody:1.3 |
