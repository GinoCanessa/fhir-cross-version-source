Comparison of 
Generated at Tuesday, April 1, 2025 1:39:19 PM

### v3.ActCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | v3.ActCode |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-ActCode` |
| Version | 2018-08-12 |
| Description | A code specifying the particular kind of Act that the Act-instance represents within its class.  Constraints:<br/><br/>The kind of Act (e.g. physical examination, serum potassium, inpatient encounter, charge financial transaction, etc.) is specified with a code from one of several, typically external, coding systems.  The coding system will depend on the class of Act, such as LOINC for observations, etc. Conceptually, the Act.code must be a specialization of the Act.classCode. This is why the structure of ActClass domain should be reflected in the superstructure of the ActCode domain and then individual codes or externally referenced vocabularies subordinated under these domains that reflect the ActClass structure. Act.classCode and Act.code are not modifiers of each other but the Act.code concept should really imply the Act.classCode concept. For a negative example, it is not appropriate to use an Act.code "potassium" together with and Act.classCode for "laboratory observation" to somehow mean "potassium laboratory observation" and then use the same Act.code for "potassium" together with Act.classCode for "medication" to mean "substitution of potassium". This mutually modifying use of Act.code and Act.classCode is not permitted. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `3284` |
| Database Concept Count | `998` |
| Database Active Concept Count | `998` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Composition` | `Composition.event.code` | `http://terminology.hl7.org/ValueSet/v3-ActCode` | `Example` | Code(s) that apply to the event being documented |
| `http://hl7.org/fhir/StructureDefinition/DocumentManifest` | `DocumentManifest.type` | `http://terminology.hl7.org/ValueSet/v3-ActCode` | `Example` | Kind of document set |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.context.event` | `http://terminology.hl7.org/ValueSet/v3-ActCode` | `Example` | Main clinical acts documented |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActCode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `1` | Therapy Appropriate |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `10` | Provided Patient Education |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `11` | Added Concurrent Therapy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `12` | Temporarily Suspended Concurrent Therapy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `13` | Stopped Concurrent Therapy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `14` | Supply Appropriate |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `15` | Replacement |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `16` | Vacation Supply |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `17` | Weekend Supply |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `18` | Leave of Absence |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `19` | Consulted Supplier |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `2` | Assessed Patient |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `20` | additional quantity on separate dispense |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `21` | authorization confirmed |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `21611-9` | age patient qn est |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `21612-7` | age patient qn reported |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `22` | appropriate indication or diagnosis |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `23` | prior therapy documented |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `29553-5` | age patient qn calc |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `3` | Patient Explanation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `30525-0` | age patient qn definition |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `30972-4` | age at onset of adverse event |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `4` | Consulted Other Source |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `42CFRPart2` | 42 CFR Part2 |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `5` | Consulted Prescriber |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `6` | Prescriber Declined Change |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `7` | Interacting Therapy No Longer Active/Planned |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `8` | Other Action Taken |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `9` | Instituted Ongoing Monitoring Program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AA` | adjudicated with adjustments |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AALC` | accredited assisted living care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AAMC` | accredited ambulatory care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ABHC` | accredited behavioral health care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ABUSE` | commonly abused/misused alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACAC` | accredited critical access hospital care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACADR` | adverse drug reaction access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACALL` | all access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACALLG` | allergy access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACCESSCONSCHEME` | access control scheme |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACCONS` | informational consent access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACCTRECEIVABLE` | account receivable |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACDEMO` | demographics access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACDI` | diagnostic imaging access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACH` | Automated Clearing House |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACHC` | accredited hospital care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACID` | Acidification |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACIMMUN` | immunization access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACLAB` | lab test result access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACMED` | medication access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACMEDC` | medical condition access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACMEN` | mental health access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACOBS` | common observations access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACOCOMPT` | accountable care organization compartment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACPOLPRG` | policy or program information access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACPROV` | provider information access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACPSERV` | professional service access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACSUBSTAB` | substance abuse access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACU` | short term/acute |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACUTE` | inpatient acute |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADALRT` | adult alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADMDX` | admitting diagnosis |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNFPPELAT` | adjud. nullified prior-period electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNFPPELCT` | adjud. nullified prior-period electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNFPPMNAT` | adjud. nullified prior-period manual amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNFPPMNCT` | adjud. nullified prior-period manual count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNFSPELAT` | adjud. nullified same-period electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNFSPELCT` | adjud. nullified same-period electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNFSPMNAT` | adjud. nullified same-period manual amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNFSPMNCT` | adjud. nullified same-period manual count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNPPPELAT` | adjud. non-payee payable prior-period electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNPPPELCT` | adjud. non-payee payable prior-period electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNPPPMNAT` | adjud. non-payee payable prior-period manual amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNPPPMNCT` | adjud. non-payee payable prior-period manual count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNPSPELAT` | adjud. non-payee payable same-period electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNPSPELCT` | adjud. non-payee payable same-period electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNPSPMNAT` | adjud. non-payee payable same-period manual amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADNPSPMNCT` | adjud. non-payee payable same-period manual count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADOL` | adolescent information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADPPPPELAT` | adjud. payee payable prior-period electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADPPPPELCT` | adjud. payee payable prior-period electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADPPPPMNAT` | adjud. payee payable prior-period manual amout |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADPPPPMNCT` | adjud. payee payable prior-period manual count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADPPSPELAT` | adjud. payee payable same-period electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADPPSPELCT` | adjud. payee payable same-period electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADPPSPMNAT` | adjud. payee payable same-period manual amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADPPSPMNCT` | adjud. payee payable same-period manual count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADRFPPELAT` | adjud. refused prior-period electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADRFPPELCT` | adjud. refused prior-period electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADRFPPMNAT` | adjud. refused prior-period manual amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADRFPPMNCT` | adjud. refused prior-period manual count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADRFSPELAT` | adjud. refused same-period electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADRFSPELCT` | adjud. refused same-period electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADRFSPMNAT` | adjud. refused same-period manual amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADRFSPMNCT` | adjud. refused same-period manual count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADVERSE_REACTION` | Adverse Reaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AE` | American Express |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AFOOT` | pedestrian transport |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AFTHRS` | non-normal hours |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AGE` | Age Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AGGREGATE` | aggregate measure observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AHOC` | accredited home care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AIRTRNS` | airborne transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALC` | Alternative Level of Care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALEC` | alternate electronic |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALG` | Allergy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALGY` | Allergy Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALK` | Alkalization |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALLCAT` | all categories |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALLDONE` | already performed |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALLERLE` | allergy list entry |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALLERLREV` | allergy list review |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALLGCAT` | allergy category |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALRTENDLATE` | end too late alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALRTSTRTLATE` | start too late alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALTC` | accredited long term care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AMB` | ambulatory |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AMBAIR` | fixed-wing ambulance transport |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AMBGRND` | ground ambulance transport |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AMBHELO` | helicopter ambulance transport |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AMBT` | ambulance transport |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ANANTRNS` | animal to animal transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ANF` | adjudicated with adjustments and no financial impact |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ANHUMTRNS` | animal to human transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ANNDI` | diagnostic image note |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ANNGEN` | general note |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ANNIMM` | immunization note |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ANNLAB` | laboratory note |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ANNMED` | medication note |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ANNU` | annuity policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ANONY` | anonymize |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AOD` | accounting of disclosure |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AOSC` | accredited office-based surgery care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AR` | adjudicated as refused |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ARCAT` | adverse drug reaction category |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ARTBLD` | ActSpecObsArtBldCode |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AS` | adjudicated as submitted |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ASSERTION` | Assertion |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AUDIT` | audit |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AUDTR` | audit trail |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AUTH` | Authorized |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AUTHPOL` | authorization policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AUTO` | auto-repeat permission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AUTO-HIGH` | Auto-High Dilution |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AUTO-LOW` | Auto-Low Dilution |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AUTOATTCH` | auto attachment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AUTOPOL` | automobile |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AVAILABLE` | Available Volume |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `B` | business information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `BDYFLDTRNS` | body fluid contact transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `BH` | behavioral health information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `BLDTRNS` | blood borne transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `BLK` | block funding |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `BONUS` | bonus |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `BOOSTER` | Booster Immunization |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `BR` | breikost (GE) |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `BUS` | business constraint violation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `C` | corrected |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CACC` | certified anatomic pathology and clinical pathology care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CACS` | certified acute coronary syndrome care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CAIC` | certified allergy and immunology care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CAMC` | certified aerospace medicine care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CAMI` | certified acute myocardial infarction care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CANC` | certified anesthesiology care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CANCAPT` | cancelled appointment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CANPRG` | women's cancer detection program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CAP` | capitation funding |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CAPC` | certified anatomic pathology care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CARD` | Cardiology |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CARELIST` | care plan |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CASESER` | case seriousness criteria |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CASH` | Cash |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CAST` | certified asthma care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CBAR` | certified bariatric surgery care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CBGC` | certified clinical biochemical genetics care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CC` | credit card |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CCAD` | certified coronary artery disease care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CCAR` | certified cardiac care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CCCC` | certified clinical cytogenetics care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CCGC` | certified clinical genetics (M.D.) care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CCPC` | certified clinical pathology care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CCSC` | certified colon and rectal surgery care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CDEC` | certified dermatology care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CDEP` | certified depression care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CDGD` | certified digestive/gastrointestinal disorders care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CDIA` | certified diabetes care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CDIO` | case disease imported observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CDRC` | certified diagnostic radiology care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CDSREV` | clinical decision support intervention review |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CEL` | celebrity information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CEMC` | certified emergency medicine care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CEPI` | certified epilepsy care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CFEL` | certified frail elderly care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CFPC` | certified family practice care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CFWD` | carry forward adjusment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CHAR` | charity program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CHFC` | certified heart failure care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CHK` | Cheque |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CHLDCARE` | Day care - Child care Interaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CHR` | Chronic |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CHRG` | Standard Charge |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CHRO` | certified high risk obstetrics care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CHRON` | continuous/chronic |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CHYP` | certified hyperlipidemia care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CIMC` | certified internal medicine care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CIRCLE` | circle |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CLINNOTEE` | clinical note entry task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CLINNOTEREV` | clinical note review task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CLSSRM` | classroom |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CMGC` | certified clinical molecular genetics care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CMIH` | certified migraine headache care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CMPMSRMTH` | composite measure method |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CMPMSRSCRWGHT` | component measure scoring weight |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CMSC` | certified multiple sclerosis care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CNEC` | certified neurology care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CNMC` | certified nuclear medicine care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CNQC` | certified neurology with special qualifications in child neurology care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CNSC` | certified neurological surgery care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COBSCAT` | common observation category |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CODE_DEPREC` | code has been deprecated |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CODE_INVAL` | code is not valid |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COGC` | certified obstetrics and gynecology care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COGN` | cognitive disability information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COIN` | coinsurance |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COINS` | co-insurance |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COJR` | certified orthopedic joint replacement care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COL` | collision coverage policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COMC` | certified occupational medicine care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COMPLY` | Compliance Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COMPT` | compartment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CONC` | certified oncology care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COND` | Condition Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CONDLIST` | condition list |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CONSUMPTION` | Consumption Volume |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CONT` | contract |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CONTF` | contract funding |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CONVEYNC` | Common Conveyance Interaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COPAY` |  |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COPAYMENT` | patient co-pay |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COPC` | certified ophthalmology care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COPD` | certified chronic obstructive pulmonary disease care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COPY` | copyright |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CORT` | certified organ transplant care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COSC` | certified orthopaedic surgery care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COTC` | certified otolaryngology care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COVGE` | coverage problem |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COVMX` | coverage maximum |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COVPOL` | benefit policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COVPRD` | coverage period |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPAD` | certified parkinsons disease care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPEC` | certified pediatrics care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPGC` | certified Ph.D. medical genetics care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPHC` | certified public health and general preventive medicine care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPINV` | clinical product invoice |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPLYCC` | comply with confidentiality code |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPLYCD` | comply with consent directive |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPLYJPP` | comply with jurisdictional privacy policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPLYOPP` | comply with organizational privacy policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPLYOSP` | comply with organizational security policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPLYPOL` | comply with policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPND` | certified pneumonia disease care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPNDDRGING` | compound drug invoice group |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPNDINDING` | compound ingredient invoice group |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPNDSUPING` | compound supply invoice group |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPRC` | certified physical medicine and rehabilitation care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPSC` | certified plastic surgery care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPST` | certified primary stroke center care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPTM` | CPT modifier codes |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CPYC` | certified psychiatry care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CREACT` | common reaction alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CRIME` | crime victim program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CRIT` | criticality |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CROC` | certified radiation oncology care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CRPC` | certified radiological physics care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CRS` | clinical recommendation statement |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CSDM` | certified stroke disease management care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CSIC` | certified sickle cell care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CSINV` | clinical service invoice |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CSLD` | certified sleep disorders care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CSPINV` | clinical service and product |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CSPT` | certified spine treatment care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CSUC` | certified surgery care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CTBU` | certified trauma/burn center care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CTCOMPT` | care team compartment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CTLSUB` | Controlled Substance |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CTMO` | case transmission mode observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CTSC` | certified thoracic surgery care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CURC` | certified urology care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CURMEDLIST` | current medication list |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CURRENT` | Current Volume |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CVDC` | certified vascular diseases care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CVSC` | certified vascular surgery care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CWMA` | certified wound management care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CWOH` | certified women's health care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CommonRule` | Common Rule |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DACT` | drug action detected issue |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DALG` | Drug Allergy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DAY` | day |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DDP` | Direct Deposit |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DECLASSIFYLABEL` | declassify security label |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DEDUCT` |  |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DEDUCTIBLE` | deductible |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DEF` | definition |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DEFB` | Defibrination |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DEID` | deidentify |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DELAU` | delete after use |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DELEPOL` | delegation policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DEMO` | all demographic information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DEMOCAT` | demographics category |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DENEX` | denominator exclusions |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DENEXCEP` | denominator exceptions |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DENOM` | denominator |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DENTAL` | dental care policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DENTPRG` | dental program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DERMTRNS` | transdermal transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DF` | Daily Fill |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DIA` | diagnosis information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DIAGLISTE` | diagnosis list entry task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DIAGLISTREV` | diagnosis list review task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DICAT` | diagnostic image category |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DIET` | Diet |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DILUTION` | ActSpecObsDilutionCode |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DINT` | Drug Intolerance |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DIS` | disability insurance policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DISC` | disclaimer |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DISCHINSTE` | discharge instruction entry |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DISCHSUME` | discharge summary entry task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DISCHSUMREV` | discharge summary review task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DISCMEDLIST` | discharge medication list |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DISDX` | discharge diagnosis |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DISEASE` | disease specific policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DISEASEPRG` | public health program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DISPLAY` | Display |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DM` | diabetes mellitus diet |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DN` | Diner's Club |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DNAINT` | Drug Non-Allergy Intolerance |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DNTL` | Dental |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOB` | date of birth information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOCUMENT` | document |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSE` | Dosage problem |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSECOND` | dosage-condition alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEDUR` | Dose-Duration Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEDURH` | Dose-Duration High Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEDURHIND` | Dose-Duration High for Indication Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEDURL` | Dose-Duration Low Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEDURLIND` | Dose-Duration Low for Indication Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEH` | High Dose Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEHIND` | High Dose for Indication Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEHINDA` | High Dose for Age Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEHINDSA` | High Dose for Height/Surface Area Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEHINDW` | High Dose for Weight Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEIND` |  |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEIVL` | Dose-Interval Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEIVLIND` | Dose-Interval for Indication Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEL` | Low Dose Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSELIND` | Low Dose for Indication Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSELINDA` | Low Dose for Age Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSELINDSA` | Low Dose for Height/Surface Area Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSELINDW` | Low Dose for Weight Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOWNGRDLABEL` | downgrade security label |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DRG` | Drug Interaction Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DRGIS` | drug information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DRGRHB` | Drug Rehab |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DRIVLABEL` | derive security label |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DRUG` | Drug therapy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DRUGING` | drug invoice group |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DRUGPOL` | drug policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DRUGPRG` | drug program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DSC` | discount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DUPTHPCLS` | duplicate therapeutic alass alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DUPTHPGEN` | duplicate generic alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DUPTHPY` | Duplicate Therapy Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DV` | Discover Card |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DVD` | developmental disability information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DX` | ObservationDiagnosisTypes |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EALG` | Environmental Allergy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EAP` | employee assistance program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EDU` | education fees |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EFORM` | electronic form to follow |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EHCPOL` | extended healthcare |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EINT` | Environmental Intolerance |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ELG` | Eligible |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ELLIPSE` | ellipse |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EM` | Emergency Supply |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EMAUTH` | emergency authorization override |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EMER` | emergency |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EMOTDIS` | emotional disturbance information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EMP` | employee information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EMPL` | employer information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EMRGONLY` | emergency only |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ENAINT` | Environmental Non-Allergy Intolerance |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ENCRYPT` | encrypt |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ENCRYPTR` | encrypt at rest |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ENCRYPTT` | encrypt in transit |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ENCRYPTU` | encrypt in use |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ENDC` | endogenous content |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ENDLATE` | End Too Late Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ENDRENAL` | end renal program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ENVTRNS` | environmental exposure transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EPYMT` | early payment fee |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ESA` | extraordinary service assessment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ETH` | substance abuse information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ETHUD` | alcohol use disorder information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EVNFCTS` | ActSpecObsEvntfctsCode |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EWB` | employee welfare benefit plan policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `F` | final |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FALG` | Food Allergy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FALLRISK` | falls risk assessment instrument task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FAST` | fasting |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FAX` | fax to follow |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FD` | food |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FDACOATING` | coating |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FDACOLOR` | color |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FDAIMPRINTCD` | imprint code |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FDALOGO` | logo |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FDASCORING` | scoring |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FDASHAPE` | shape |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FDASIZE` | size |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FECTRNS` | fecal-oral transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FF` | First Fill |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FFC` | First Fill - Complete |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FFCS` | first fill complete, partial strength |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FFP` | First Fill - Part Fill |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FFPS` | first fill, part fill, partial strength |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FFS` | fee for service |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FFSS` | first fill, partial strength |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FFSTOP` | fee for service top off |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FIBRIN` | Fibrin |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FILT` | Filtration |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FINALDT` | finalized date/time |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FINBILL` | financial |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FININV` | financial invoice |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FINT` | Food Intolerance |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FLD` | field |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FLEXP` | flexible benefit plan policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FMCOMPT` | financial management compartment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FNAINT` | Food Non-Allergy Intolerance |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FNLFEE` | final fee |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FOMTRNS` | fomite transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FOOD` | Food Interaction Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FOODTRNS` | food-borne transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FORM` | Print on Form |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FORMAT` | invalid format |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FORMULA` | formula diet |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FRAMEING` | frame invoice group |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FRAUD` | potential fraud |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FRSTFEE` | first fee |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FS` | Floor stock |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FST` | federal sales tax |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FULFIL` | fulfillment alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GARN` | garnishee |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GDIS` | genetic disease information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GEALRT` | geriatric alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GEN` | Genetic Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GEND` | Gender Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GENDER` | gender and sexual orientation information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GENE` | gene |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GENRL` | General |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GF` | gluten free |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GFTH` | good faith indicator |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GISTIER` | GIS tier |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GOALLIST` | goal list |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GOVEMP` | government employee health program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GRADE` | grade |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GRANTORCHOICE` | grantor choice |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GTIN` | Global Trade Item Number |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GUIDE` | guidance |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HCPCSA` | HCPCS Level II and Carrier-assigned |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HEALTHREC` | health record |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HELD` | held/suspended alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HEMOLYSIS` | Hemolysis |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HGHT` |  |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HH` | home health |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HHOBS` | household situation observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HIP` | health insurance plan policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HIPAANOPP` | HIPAA notice of privacy practices |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HIPAAPsyNotes` | HIPAA psychotherapy notes |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HIPAASelfPay` | HIPAA self-pay |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HIRISK` | high risk pool program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HISTMEDLIST` | medication history |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HISTORIC` | record recorded as historical |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HIV` | HIV/AIDS information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HIVAIDS` | HIV-AIDS program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HLTHCARE` | Health Care Interaction - Not Patient Care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HMO` | health maintenance organization policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HOMECARE` | Care Giver Interaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HOSPPTNT` | Hospital Patient Interaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HOSPVSTR` | Hospital Visitor Interaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HOUSEHLD` | Household Interaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HRCOMPT` | human resource compartment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HSAPOL` | health spending account |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HST` | harmonized sales Tax |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HUAPRV` | human approval |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HUMHUMTRNS` | human to human transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `I` | Isolation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ICOL` | information collection |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ICTERUS` | Icterus |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ID` | Identified |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IDSCL` | information disclosure |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IDUR` | improvement notation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ILLEGAL` | illegal |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IMG` | image attachment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IMMLE` | immunization list entry |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IMMLREV` | immunization list review |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IMMUCAT` | immunization category |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IMMUNIZ` | Immunization |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IMP` | inpatient encounter |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IMPLIED` | implied consent |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IMPLIEDD` | implied consent with opportunity to dissent |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IND` | indigenous peoples health program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IND01` | imaging study requiring contrast |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IND02` | colonoscopy prep |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IND03` | prophylaxis |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IND04` | surgical prophylaxis |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IND05` | pregnancy prophylaxis |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INDTRNS` | indeterminate disease transmission mode |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INFA` | information access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INFAO` | access only |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INFASO` | access and save only |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INFAUT` | authorized information transfer |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INFCON` | after explicit consent |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INFCRT` | only on court order |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INFDNG` | only if danger to others |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INFEMER` | only in an emergency |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INFPWR` | only if public welfare risk |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INFREG` | regulatory information transfer |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INITIAL` | Initial Volume |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INITIMMUNIZ` | Initial Immunization |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INMATE` | Inmate Interaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INT` | Intolerance Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INTDX` | intermediate diagnosis |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INTERVAL` | outside requested time |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INTFR` | ActSpecObsInterferenceCode |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INTIMATE` | Intimate Interaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INTOLIST` | intolerance list |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INV` | investigational |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INVOICE` | submitted invoice |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INVTYPE` | invoice type |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IP` | In Position |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IPOP` | initial population |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IPPOP` | initial patient population |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IRDSCL` | information redisclosure |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ISOL` | isolation allowance |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ISSUE` | detected issue |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ITMCNT` | items counted |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `KEY` | keyword |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `KEY204` | Unknown key identifier |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `KEY205` | Duplicate key identifier |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `KEY206` | non-matching identification |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `KSUBJ` | knowledge subject |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `KSUBT` | knowledge subtopic |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `L` | Left Equipment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LAB` | Lab Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LABCAT` | lab test category |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LABEL` | assign security label |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LABOE` | laboratory test order entry task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LABRESULTS` | lab results |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LABRREV` | laboratory results review task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LACT` | Lactation Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LACTTRNS` | lactation transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LATE` | late invoice |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LAWENF` | law enforcement transport |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LDLP` | LDL Precipitation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LENSING` | lens invoice group |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LEN_LONG` | length is too long |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LEN_RANGE` | length out of range |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LEN_SHORT` | length is too short |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LF` | low fat |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LFEMX` | life time maximum |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LGPC` | licensed general physician care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LIFE` | life insurance policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LIPEMIA` | Lipemia |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LIVARG` | living arrangement information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LOAN` | Loan |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LOC` | location |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LOCIS` | location information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LP` | low protein |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LQ` | liquid |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LRCOMPT` | legitimate relationship compartment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LS` | low sodium |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LTC` | long term care policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LTRMCARE` | Long Term Care Facility Interaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LU` | limited use |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `M` | Missing |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MANDPOL` | mandatory health program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MANUAL` | manual review |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MARKUP` | markup or up-charge |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MARST` | marital status information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MARWLREV` | medication administration record work list review task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MASK` | mask |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MAXOCCURS` | repetitions above maximum |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MC` | Master Card |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MCPOL` | managed care policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MDOSE` | maximum dosage reached |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MED` | Medical |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MEDCCAT` | medical condition category |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MEDLIST` | medication list |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MEDOE` | medication order entry task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MEDT` | measurement end date |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MENCAT` | mental health category |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MENTPOL` | mental health policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MENTPRG` | mental health program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MH` | mental health information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MICROORGRREV` | microbiology organisms results review task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MICRORREV` | microbiology results review task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MICROSENSRREV` | microbiology sensitivity test results review task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MILITARY` | military health program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MINEC` | minimum necessary |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MINFREQ` | too soon within frequency based on the usage |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MINOCCURS` | repetitions below minimum |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MISSAPT` | missed appointment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MISSCOND` | conditional element missing |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MISSMAND` | mandatory element missing |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MLREV` | medication list review task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MODEL` | model |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MONTH` | month |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MS` | Manufacturer Sample |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MSD` | measurement start date |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MSRADJ` | risk adjustment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MSRAGG` | rate aggregation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MSRIMPROV` | health quality measure improvement notation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MSRJUR` | jurisdiction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MSROBS` | measure observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MSRPOPL` | measure population |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MSRPOPLEX` | measure population exclusions |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MSRRPTR` | reporter type |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MSRRPTTIME` | timeframe for reporting |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MSRSCORE` | measure scoring |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MSRSET` | health quality measure care setting |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MSRTOPIC` | health quality measure topic type |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MSRTP` | measurement period |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MSRTYPE` | measure type |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MST` | military sexual trauma information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MVA` | Motor vehicle accident |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `N` | normal diet |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NAINT` | Non-Allergy Intolerance |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NAT` | Insufficient authorization |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NAUTH` | Not Authorized |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NELG` | Not Eligible |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NETAMT` | Net Amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NEUT` | Neutralization |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NF` | no fat |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NHP` | Natural Health Product Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOAUTH` | no disclosure without subject authorization |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOCOLLECT` | no collection |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOCONSENT` | no consent |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NODSCLCD` | no disclosure without consent directive |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NODSCLCDS` | no disclosure without information subject's consent directive |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NODUPS` | duplicate values are not permitted |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOI` | nature of injury |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOINTEGRATE` | no integration |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOLIST` | no unlisted entity disclosure |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOMOU` | no disclosure without MOU |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NON` | Non-Payment Data |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NONAC` | inpatient non-acute |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NONRX` | Non-Prescription Interaction Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOORGPOL` | no disclosure without organizational authorization |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOPAT` | no disclosure to patient, family or caregivers without attending provider's authorization |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOPERSIST` | element will not be persisted |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOPERSISTP` | no collection beyond purpose of use |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOPP` | notice of privacy practices |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NORDSCLCD` | no redisclosure without consent directive |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NORDSCLCDS` | no redisclosure without information subject's consent directive |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NORDSCLW` | no disclosure without jurisdictional authorization |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NORELINK` | no relinking |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOREUSE` | no reuse beyond purpose of use |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOSTRNS` | nosocomial transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOTACTN` | no longer actionable |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOTEQUIV` | not equivalent alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOTEQUIVGEN` | not generically equivalent alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOTEQUIVTHER` | not therapeutically equivalent alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOVIP` | no unauthorized VIP disclosure |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NUMER` | numerator |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NUMEX` | numerator exclusions |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `O` | In Process |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OBS` | Obstetrics |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OBSA` | Observation Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OBSANTC` | antigen count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OBSANTV` | antigen validity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OBSENC` | observation encounter |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OBSOLETE` | obsolete record returned |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OE` | order entry task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OHSINV` | oral health service |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OINT` | intolerance |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ONC` | Oncology |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ONET` | one time |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OOJ` | out of jurisdiction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OOO` | out of office |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OPIOIDUD` | opioid use disorder information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OPTIN` | opt-in |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OPTINR` | opt-in with restrictions |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OPTOUT` | op-out |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OPTOUTE` | opt-out with exceptions |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ORCON` | no disclosure without originator authorization |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OREV` | orders review task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ORTHO` | orthodontic service |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OTC` | non prescription medicine |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ObligationPolicy` | obligation policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `P` | Private |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PACOMPT` | patient administration compartment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PAF` | phenylalanine free |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PAINV` | preferred accommodation invoice |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PALL` | Palliative |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PAPER` | paper documentation to follow |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PAR` | parenteral |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PARTRNS` | parenteral transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PATDOC` | patient documentation task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PATEDUE` | patient education entry |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PATINFO` | patient information review task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PATPREF` | violates stated preferences |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PATPREFALT` | violates stated preferences, alternate available |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PATREPE` | pathology report entry task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PATREPREV` | pathology report review task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PAT_ADV_EVNT` | patient adverse event |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PAY` | payment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PAYEE` | payee |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PAYOR` | payor |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PBILLACCT` | patient billing account |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNFPPELAT` | paid nullified prior-period electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNFPPELCT` | paid nullified prior-period electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNFPPMNAT` | paid nullified prior-period manual amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNFPPMNCT` | paid nullified prior-period manual count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNFSPELAT` | paid nullified same-period electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNFSPELCT` | paid nullified same-period electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNFSPMNAT` | paid nullified same-period manual amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNFSPMNCT` | paid nullified same-period manual count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNPPPELAT` | paid non-payee payable prior-period electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNPPPELCT` | paid non-payee payable prior-period electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNPPPMNAT` | paid non-payee payable prior-period manual amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNPPPMNCT` | paid non-payee payable prior-period manual count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNPSPELAT` | paid non-payee payable same-period electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNPSPELCT` | paid non-payee payable same-period electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNPSPMNAT` | paid non-payee payable same-period manual amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDNPSPMNCT` | paid non-payee payable same-period manual count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDPPPPELAT` | paid payee payable prior-period electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDPPPPELCT` | paid payee payable prior-period electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDPPPPMNAT` | paid payee payable prior-period manual amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDPPPPMNCT` | paid payee payable prior-period manual count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDPPSPELAT` | paid payee payable same-period electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDPPSPELCT` | paid payee payable same-period electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDPPSPMNAT` | paid payee payable same-period manual amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDPPSPMNCT` | paid payee payable same-period manual count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PDS` | patient default information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PEALRT` | pediatric alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PED` | Pediatrics |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PERFEE` | periodic fee |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PERIOD` | period |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PERMBNS` | performance bonus |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PERSISTLABEL` | persist security label |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PHAR` | Pharmaceutical |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PHY` | physician requested information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PHYRHB` | Physical Rehab |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PIE` | public insurance exhausted |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PINV` | paper invoice |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PLACE` | Common Space Interaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PLACTRNS` | transplacental transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PLYDOC` | Poly-orderer Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PLYPHRM` | Poly-supplier Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PNC` | property and casualty insurance policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `POINT` | point |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `POLY` | polyline |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `POS` | point of service policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PPO` | preferred provider organization policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PPRD` | prior period adjustment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PRA` |  |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PRDING` | product invoice group |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PRDMX` | period maximum |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PRE` | Pre-Dilution |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PREFSTRENGTH` | preference strength |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PREG` | Pregnancy Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PRENC` | pre-admission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PREVINEF` | previously ineffective |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PRIVMARK` | privacy mark |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PRLMN` | preliminary |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PRN` | as needed |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PROA` | professional association deduction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PROBLIST` | problem list |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PROBLISTE` | problem list entry task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PROBLISTREV` | problem list review task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PROV` | provider |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PRS` | patient requested information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PRVTRN` | private transport |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PSEUD` | pseudonymize |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PST` | provincial/state sales tax |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PSVCCAT` | professional service category |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PSY` | psychiatry disorder information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PSYCH` | Psychiatric |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PSYTHPN` | psychotherapy note information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PTNTCARE` | Health Care Interaction - Patient Care |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PUBLICPOL` | public healthcare |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PUBTRN` | public transport |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PYRDELAY` | delayed by a previous payor |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `R` | Process Completed |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RACE` | race information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RADREPE` | radiology report entry task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RADREPREV` | radiology report review task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RALG` | Related Allergy Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RAR` | Related Prior Reaction Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RAT` | rationale |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RD` | reduction diet |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `REACT` | Reaction Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RECA` | Recalcification |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RECOV` | recovery |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `REDACT` | redact |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `REF` | reference |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `REFLEX` | reflex permission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `REFNR` | referral not required |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `REI` | reinsurance policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `REL` | religion information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `REMLE` | reminder list entry |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `REMLREV` | reminder list review |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RENT` | Rent |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `REPRESENTATIVE_BEAT` | ECG representative beat waveforms |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `REPSERV` | repeated service |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `REP_HALF_LIFE` | representative half-life |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `REP_RANGE` | repetitions out of range |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RERUN` | Rerun Dilution |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RESCOMPT` | research project compartment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RESEARCH` | research information access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RESTOCK` | restocking fee |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RETIRE` | retiree health program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RETRO` | retro adjustment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `REV` | Standard Charge Reversal |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RF` | Refill |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RFC` | Refill - Complete |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RFCS` | refill complete partial strength |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RFF` | Refill (First fill this facility) |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RFFS` | refill partial strength (first fill this facility) |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RFP` | Refill - Part Fill |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RFPS` | refill part fill partial strength |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RFS` | refill partial strength |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RHYTHM` | ECG rhythm waveforms |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RINT` | Related Intolerance Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RISKASSESS` | risk assessment instrument task |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RISKLIST` | risk factors |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RMGTCOMPT` | records management compartment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ROIFS` | fully specified ROI |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ROIPS` | partially specified ROI |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ROST` | roster funding |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RREACT` | Related Reaction Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RSDID` | de-identified information access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RSREID` | re-identifiable information access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RX` | prescription only medicine |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RXCAT` | medication category |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RXCINV` | Rx compound invoice |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RXDINV` | Rx dispense invoice |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RefrainPolicy` | refrain policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `S` | Suite |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SA` | special authorization |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SAC` | special access |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SAFNET` | safety net clinic program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SALE` | Sale |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SBBLELAT` | submitted billed electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SBBLELCT` | submitted billed electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SBFINV` | sessional or block fee invoice |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SBNFELAT` | submitted nullified electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SBNFELCT` | submitted cancelled electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SBPDELAT` | submitted pending electronic amount |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SBPDELCT` | submitted pending electronic count |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SCA` | sickle cell anemia information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SCH` | schonkost (GE) |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SCHL` | school |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SCHLDIV` | school division |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SCHOOL` | School Accident |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SCHOOL2` | School Interaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SDE` | supplemental data elements |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SDV` | sexual assault, abuse, or domestic violence information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SECALTINTOBS` | security alteration integrity observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SECCATOBS` | security category observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SECCLASSOBS` | security classification observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SECCONOBS` | security control observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SECDATINTOBS` | security data integrity observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SECINTCONOBS` | security integrity confidence observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SECINTOBS` | security integrity observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SECINTPRVABOBS` | security integrity provenance asserted by observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SECINTPRVRBOBS` | security integrity provenance reported by observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SECINTSTOBS` | security integrity status observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SENDAPP` | sending application |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SESS` | sessional funding |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SEV` | Severity Observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SEX` | sexuality and reproductive health information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SEXTRNS` | sexual transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SICKLE` | sickle cell |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SO` | Script Owing |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SOCIAL` | social service program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SOCIAL2` | Social/Extended Family Interaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SP` | Semi-private |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SPEND` | spend down |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SPI` | specially protected information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SPLCOATING` | coating |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SPLCOLOR` | color |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SPLIMAGE` | image |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SPLIMPRINT` | imprint |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SPLSCORING` | scoring |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SPLSHAPE` | shape |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SPLSIZE` | size |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SPLSYMBOL` | symbol |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SPT` | Sporting Accident |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SREC` | specimen received |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SS` | short stay |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SSP` | sensitive service provider information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SSTOR` | specimen in storage |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `STD` | sexually transmitted disease information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `STRAN` | specimen in transit |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `STRAT` | stratification |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `STRTLATE` | Start Too Late Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SUBPOL` | substance use policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SUBPRG` | substance use program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SUBSIDFFS` | subsidized fee for service program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SUBSIDIZ` | subsidized health program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SUBSIDMC` | subsidized managed care program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SUBSTNCE` | Common Substance Interaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SUBSUPP` | subsidized supplemental health program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SUD` | substance use disorder information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SUPPLEMENT` | nutritional supplement |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SUPPRESSED` | record suppressed |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SURG` | Surgical |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SURPL` | surplus line insurance policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SecurityPolicy` | security policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `T` | tea only |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TB` | Trial Balance |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TBOO` | taboo |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TBS` | trial balance partial strength |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TEACHER` | teacher |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TF` | Trial Fill |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TFS` | trial fill partial strength |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TIME` | timing detected issue |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TIME_ABSOLUTE` | absolute time sequence |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TIME_RELATIVE` | relative time sequence |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TIMING` | event timing incorrect alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TLIFE` | term life insurance policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TOOLATE` | Refill Too Late Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TOOSOON` | Refill Too Soon Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TPROD` | Therapeutic Product Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRAN` | transaction fee |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRANF` | transmission format |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRANSFER` | Transfer |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRAVEL` | travel |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRAVINT` | Common Travel Interaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRNSFTRNS` | transfusion transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRSTACCRD` | trust accreditation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRSTACCRDOBS` | trust accreditation observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRSTAGRE` | trust agreement |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRSTAGREOBS` | trust agreement observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRSTASSUR` | trust assurance |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRSTCERT` | trust certificate |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRSTCERTOBS` | trust certificate observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRSTFWK` | trust framework |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRSTFWKOBS` | trust framework observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRSTLOAOBS` | trust assurance observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRSTMEC` | trust mechanism |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TRSTMECOBS` | trust mechanism observation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `Title38Section7332` | Title 38 Section 7332 |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `UD` | Unit Dose |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `UDE` | unit dose equivalent |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `UFIL` | Ultrafiltration |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ULIFE` | universal life insurance policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `UMBRL` | umbrella liability insurance policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `UNINSMOT` | uninsured motorist policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `UNITPRICE` | Unit Price |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `UNITQTY` | Unit Quantity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `UNRELAT` | unrelated service |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `UNSPSC` | United Nations Standard Products and Services Classification |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `UPC` | Universal Product Code |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `UPGRDLABEL` | upgrade security label |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `URGENT` | urgent |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `USE` | notice of use |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `V` | Visa |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `VAC_PROBLEM` | vaccine product problem |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `VALIDAT` | validation issue |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `VECTRNS` | vector-borne transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `VERBAUTH` | verbal authorization |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `VET` | veteran health program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `VFPAPER` | verify paper |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `VIO` | violence information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `VISPOL` | vision care policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `VLI` | low valin, leucin, isoleucin |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `VOLUME` | ActSpecObsVolumeCode |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `VR` | virtual |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `VRXINV` | vision dispense invoice |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `W` | Ward |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `WATTRNS` | water-borne transmission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `WCBPOL` | worker's compensation |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `WEEK` | week |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `WELLREMLE` | wellness reminder list entry |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `WELLREMLREV` | wellness reminder list review |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `WGHT` |  |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `WIATTCH` | work injury report attachment |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `WORK2` | Work Interaction |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `WPA` | Workplace accident |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `WRKCOMP` | (workers compensation program |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `X` | Container Unavailable |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `XRAY` | x-ray |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `YEAR` | year |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `_ActPatientAnnotationType` | ActPatientAnnotationType |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `_ActUSPrivacyLaw` | _ActUSPrivacyLaw |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `_ImmunizationObservationType` | ImmunizationObservationType |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `_ObservationQualityMeasureAttribute` | ObservationQualityMeasureAttribute |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `_PatientImmunizationRelatedObservationType` | PatientImmunizationRelatedObservationType |
