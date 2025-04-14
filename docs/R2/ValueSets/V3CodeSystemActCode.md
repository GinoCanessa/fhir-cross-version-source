Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### v3 Code System ActCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | v3 Code System ActCode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/v3-ActCode` |
| Version | 2015-07-31 |
| Description | A code specifying the particular kind of Act that the Act-instance represents within its class.  Constraints: The kind of Act (e.g. physical examination, serum potassium, inpatient encounter, charge financial transaction, etc.) is specified with a code from one of several, typically external, coding systems.  The coding system will depend on the class of Act, such as LOINC for observations, etc. Conceptually, the Act.code must be a specialization of the Act.classCode. This is why the structure of ActClass domain should be reflected in the superstructure of the ActCode domain and then individual codes or externally referenced vocabularies subordinated under these domains that reflect the ActClass structure. Act.classCode and Act.code are not modifiers of each other but the Act.code concept should really imply the Act.classCode concept. For a negative example, it is not appropriate to use an Act.code "potassium" together with and Act.classCode for "laboratory observation" to somehow mean "potassium laboratory observation" and then use the same Act.code for "potassium" together with Act.classCode for "medication" to mean "substitution of potassium". This mutually modifying use of Act.code and Act.classCode is not permitted. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `857` |
| Database Concept Count | `1071` |
| Database Active Concept Count | `955` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Composition` | `Composition.event.code` | `http://hl7.org/fhir/ValueSet/v3-ActCode` | `Example` | Code(s) that apply to the event being documented |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.context.event` | `http://hl7.org/fhir/ValueSet/v3-ActCode` | `Example` | Main Clinical Acts Documented |

### Referenced Systems

* `http://hl7.org/fhir/v3/ActCode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/v3/ActCode` | `1` | Therapy Appropriate |
| `http://hl7.org/fhir/v3/ActCode` | `10` | Provided Patient Education |
| `http://hl7.org/fhir/v3/ActCode` | `11` | Added Concurrent Therapy |
| `http://hl7.org/fhir/v3/ActCode` | `12` | Temporarily Suspended Concurrent Therapy |
| `http://hl7.org/fhir/v3/ActCode` | `13` | Stopped Concurrent Therapy |
| `http://hl7.org/fhir/v3/ActCode` | `14` | Supply Appropriate |
| `http://hl7.org/fhir/v3/ActCode` | `15` | Replacement |
| `http://hl7.org/fhir/v3/ActCode` | `16` | Vacation Supply |
| `http://hl7.org/fhir/v3/ActCode` | `17` | Weekend Supply |
| `http://hl7.org/fhir/v3/ActCode` | `18` | Leave of Absence |
| `http://hl7.org/fhir/v3/ActCode` | `19` | Consulted Supplier |
| `http://hl7.org/fhir/v3/ActCode` | `2` | Assessed Patient |
| `http://hl7.org/fhir/v3/ActCode` | `20` | additional quantity on separate dispense |
| `http://hl7.org/fhir/v3/ActCode` | `21` | authorization confirmed |
| `http://hl7.org/fhir/v3/ActCode` | `21611-9` | age patient qn est |
| `http://hl7.org/fhir/v3/ActCode` | `21612-7` | age patient qn reported |
| `http://hl7.org/fhir/v3/ActCode` | `22` | appropriate indication or diagnosis |
| `http://hl7.org/fhir/v3/ActCode` | `23` | prior therapy documented |
| `http://hl7.org/fhir/v3/ActCode` | `29553-5` | age patient qn calc |
| `http://hl7.org/fhir/v3/ActCode` | `3` | Patient Explanation |
| `http://hl7.org/fhir/v3/ActCode` | `30525-0` | age patient qn definition |
| `http://hl7.org/fhir/v3/ActCode` | `30972-4` | age at onset of adverse event |
| `http://hl7.org/fhir/v3/ActCode` | `4` | Consulted Other Source |
| `http://hl7.org/fhir/v3/ActCode` | `5` | Consulted Prescriber |
| `http://hl7.org/fhir/v3/ActCode` | `6` | Prescriber Declined Change |
| `http://hl7.org/fhir/v3/ActCode` | `7` | Interacting Therapy No Longer Active/Planned |
| `http://hl7.org/fhir/v3/ActCode` | `8` | Other Action Taken |
| `http://hl7.org/fhir/v3/ActCode` | `9` | Instituted Ongoing Monitoring Program |
| `http://hl7.org/fhir/v3/ActCode` | `AA` | adjudicated with adjustments |
| `http://hl7.org/fhir/v3/ActCode` | `AALC` | accredited assisted living care |
| `http://hl7.org/fhir/v3/ActCode` | `AAMC` | accredited ambulatory care |
| `http://hl7.org/fhir/v3/ActCode` | `ABHC` | accredited behavioral health care |
| `http://hl7.org/fhir/v3/ActCode` | `ABUSE` | commonly abused/misused alert |
| `http://hl7.org/fhir/v3/ActCode` | `ACAC` | accredited critical access hospital care |
| `http://hl7.org/fhir/v3/ActCode` | `ACADR` | adverse drug reaction access |
| `http://hl7.org/fhir/v3/ActCode` | `ACALL` | all access |
| `http://hl7.org/fhir/v3/ActCode` | `ACALLG` | allergy access |
| `http://hl7.org/fhir/v3/ActCode` | `ACCONS` | informational consent access |
| `http://hl7.org/fhir/v3/ActCode` | `ACCTRECEIVABLE` | account receivable |
| `http://hl7.org/fhir/v3/ActCode` | `ACDEMO` | demographics access |
| `http://hl7.org/fhir/v3/ActCode` | `ACDI` | diagnostic imaging access |
| `http://hl7.org/fhir/v3/ActCode` | `ACH` | Automated Clearing House |
| `http://hl7.org/fhir/v3/ActCode` | `ACHC` | accredited hospital care |
| `http://hl7.org/fhir/v3/ActCode` | `ACID` | Acidification |
| `http://hl7.org/fhir/v3/ActCode` | `ACIMMUN` | immunization access |
| `http://hl7.org/fhir/v3/ActCode` | `ACLAB` | lab test result access |
| `http://hl7.org/fhir/v3/ActCode` | `ACMED` | medication access |
| `http://hl7.org/fhir/v3/ActCode` | `ACMEDC` | medical condition access |
| `http://hl7.org/fhir/v3/ActCode` | `ACMEN` | mental health access |
| `http://hl7.org/fhir/v3/ActCode` | `ACOBS` | common observations access |
| `http://hl7.org/fhir/v3/ActCode` | `ACPOLPRG` | policy or program information access |
| `http://hl7.org/fhir/v3/ActCode` | `ACPROV` | provider information access |
| `http://hl7.org/fhir/v3/ActCode` | `ACPSERV` | professional service access |
| `http://hl7.org/fhir/v3/ActCode` | `ACSUBSTAB` | substance abuse access |
| `http://hl7.org/fhir/v3/ActCode` | `ACU` | short term/acute |
| `http://hl7.org/fhir/v3/ActCode` | `ACUTE` | inpatient acute |
| `http://hl7.org/fhir/v3/ActCode` | `ADALRT` | adult alert |
| `http://hl7.org/fhir/v3/ActCode` | `ADMDX` | admitting diagnosis |
| `http://hl7.org/fhir/v3/ActCode` | `ADNFPPELAT` | adjud. nullified prior-period electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `ADNFPPELCT` | adjud. nullified prior-period electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `ADNFPPMNAT` | adjud. nullified prior-period manual amount |
| `http://hl7.org/fhir/v3/ActCode` | `ADNFPPMNCT` | adjud. nullified prior-period manual count |
| `http://hl7.org/fhir/v3/ActCode` | `ADNFSPELAT` | adjud. nullified same-period electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `ADNFSPELCT` | adjud. nullified same-period electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `ADNFSPMNAT` | adjud. nullified same-period manual amount |
| `http://hl7.org/fhir/v3/ActCode` | `ADNFSPMNCT` | adjud. nullified same-period manual count |
| `http://hl7.org/fhir/v3/ActCode` | `ADNPPPELAT` | adjud. non-payee payable prior-period electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `ADNPPPELCT` | adjud. non-payee payable prior-period electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `ADNPPPMNAT` | adjud. non-payee payable prior-period manual amount |
| `http://hl7.org/fhir/v3/ActCode` | `ADNPPPMNCT` | adjud. non-payee payable prior-period manual count |
| `http://hl7.org/fhir/v3/ActCode` | `ADNPSPELAT` | adjud. non-payee payable same-period electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `ADNPSPELCT` | adjud. non-payee payable same-period electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `ADNPSPMNAT` | adjud. non-payee payable same-period manual amount |
| `http://hl7.org/fhir/v3/ActCode` | `ADNPSPMNCT` | adjud. non-payee payable same-period manual count |
| `http://hl7.org/fhir/v3/ActCode` | `ADOL` | adolescent information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `ADPPPPELAT` | adjud. payee payable prior-period electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `ADPPPPELCT` | adjud. payee payable prior-period electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `ADPPPPMNAT` | adjud. payee payable prior-period manual amout |
| `http://hl7.org/fhir/v3/ActCode` | `ADPPPPMNCT` | adjud. payee payable prior-period manual count |
| `http://hl7.org/fhir/v3/ActCode` | `ADPPSPELAT` | adjud. payee payable same-period electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `ADPPSPELCT` | adjud. payee payable same-period electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `ADPPSPMNAT` | adjud. payee payable same-period manual amount |
| `http://hl7.org/fhir/v3/ActCode` | `ADPPSPMNCT` | adjud. payee payable same-period manual count |
| `http://hl7.org/fhir/v3/ActCode` | `ADRFPPELAT` | adjud. refused prior-period electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `ADRFPPELCT` | adjud. refused prior-period electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `ADRFPPMNAT` | adjud. refused prior-period manual amount |
| `http://hl7.org/fhir/v3/ActCode` | `ADRFPPMNCT` | adjud. refused prior-period manual count |
| `http://hl7.org/fhir/v3/ActCode` | `ADRFSPELAT` | adjud. refused same-period electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `ADRFSPELCT` | adjud. refused same-period electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `ADRFSPMNAT` | adjud. refused same-period manual amount |
| `http://hl7.org/fhir/v3/ActCode` | `ADRFSPMNCT` | adjud. refused same-period manual count |
| `http://hl7.org/fhir/v3/ActCode` | `ADVERSE_REACTION` | Adverse Reaction |
| `http://hl7.org/fhir/v3/ActCode` | `AE` | American Express |
| `http://hl7.org/fhir/v3/ActCode` | `AFOOT` | pedestrian transport |
| `http://hl7.org/fhir/v3/ActCode` | `AFTHRS` | non-normal hours |
| `http://hl7.org/fhir/v3/ActCode` | `AGE` | Age Alert |
| `http://hl7.org/fhir/v3/ActCode` | `AGGREGATE` | aggregate measure observation |
| `http://hl7.org/fhir/v3/ActCode` | `AHOC` | accredited home care |
| `http://hl7.org/fhir/v3/ActCode` | `AIRTRNS` | airborne transmission |
| `http://hl7.org/fhir/v3/ActCode` | `ALC` | Alternative Level of Care |
| `http://hl7.org/fhir/v3/ActCode` | `ALEC` | alternate electronic |
| `http://hl7.org/fhir/v3/ActCode` | `ALG` | Allergy |
| `http://hl7.org/fhir/v3/ActCode` | `ALGY` | Allergy Alert |
| `http://hl7.org/fhir/v3/ActCode` | `ALK` | Alkalization |
| `http://hl7.org/fhir/v3/ActCode` | `ALLCAT` | all categories |
| `http://hl7.org/fhir/v3/ActCode` | `ALLDONE` | already performed |
| `http://hl7.org/fhir/v3/ActCode` | `ALLERLE` | allergy list entry |
| `http://hl7.org/fhir/v3/ActCode` | `ALLERLREV` | allergy list review |
| `http://hl7.org/fhir/v3/ActCode` | `ALLGCAT` | allergy category |
| `http://hl7.org/fhir/v3/ActCode` | `ALRTENDLATE` | end too late alert |
| `http://hl7.org/fhir/v3/ActCode` | `ALRTSTRTLATE` | start too late alert |
| `http://hl7.org/fhir/v3/ActCode` | `ALTC` | accredited long term care |
| `http://hl7.org/fhir/v3/ActCode` | `AMB` | ambulatory |
| `http://hl7.org/fhir/v3/ActCode` | `AMBAIR` | fixed-wing ambulance transport |
| `http://hl7.org/fhir/v3/ActCode` | `AMBGRND` | ground ambulance transport |
| `http://hl7.org/fhir/v3/ActCode` | `AMBHELO` | helicopter ambulance transport |
| `http://hl7.org/fhir/v3/ActCode` | `AMBT` | ambulance transport |
| `http://hl7.org/fhir/v3/ActCode` | `ANANTRNS` | animal to animal transmission |
| `http://hl7.org/fhir/v3/ActCode` | `ANF` | adjudicated with adjustments and no financial impact |
| `http://hl7.org/fhir/v3/ActCode` | `ANHUMTRNS` | animal to human transmission |
| `http://hl7.org/fhir/v3/ActCode` | `ANNDI` | diagnostic image note |
| `http://hl7.org/fhir/v3/ActCode` | `ANNGEN` | general note |
| `http://hl7.org/fhir/v3/ActCode` | `ANNIMM` | immunization note |
| `http://hl7.org/fhir/v3/ActCode` | `ANNLAB` | laboratory note |
| `http://hl7.org/fhir/v3/ActCode` | `ANNMED` | medication note |
| `http://hl7.org/fhir/v3/ActCode` | `ANNU` | annuity policy |
| `http://hl7.org/fhir/v3/ActCode` | `ANONY` | anonymize |
| `http://hl7.org/fhir/v3/ActCode` | `AOD` | accounting of disclosure |
| `http://hl7.org/fhir/v3/ActCode` | `AOSC` | accredited office-based surgery care |
| `http://hl7.org/fhir/v3/ActCode` | `AR` | adjudicated as refused |
| `http://hl7.org/fhir/v3/ActCode` | `ARCAT` | adverse drug reaction category |
| `http://hl7.org/fhir/v3/ActCode` | `ARTBLD` | ActSpecObsArtBldCode |
| `http://hl7.org/fhir/v3/ActCode` | `AS` | adjudicated as submitted |
| `http://hl7.org/fhir/v3/ActCode` | `ASSERTION` | Assertion |
| `http://hl7.org/fhir/v3/ActCode` | `AUDIT` | audit |
| `http://hl7.org/fhir/v3/ActCode` | `AUDTR` | audit trail |
| `http://hl7.org/fhir/v3/ActCode` | `AUTH` | Authorized |
| `http://hl7.org/fhir/v3/ActCode` | `AUTO` | auto-repeat permission |
| `http://hl7.org/fhir/v3/ActCode` | `AUTO-HIGH` | Auto-High Dilution |
| `http://hl7.org/fhir/v3/ActCode` | `AUTO-LOW` | Auto-Low Dilution |
| `http://hl7.org/fhir/v3/ActCode` | `AUTOATTCH` | auto attachment |
| `http://hl7.org/fhir/v3/ActCode` | `AUTOPOL` | automobile |
| `http://hl7.org/fhir/v3/ActCode` | `AVAILABLE` | Available Volume |
| `http://hl7.org/fhir/v3/ActCode` | `B` | business information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `BDYFLDTRNS` | body fluid contact transmission |
| `http://hl7.org/fhir/v3/ActCode` | `BLDTRNS` | blood borne transmission |
| `http://hl7.org/fhir/v3/ActCode` | `BLK` | block funding |
| `http://hl7.org/fhir/v3/ActCode` | `BONUS` | bonus |
| `http://hl7.org/fhir/v3/ActCode` | `BOOSTER` | Booster Immunization |
| `http://hl7.org/fhir/v3/ActCode` | `BR` | breikost (GE) |
| `http://hl7.org/fhir/v3/ActCode` | `BUS` | business constraint violation |
| `http://hl7.org/fhir/v3/ActCode` | `C` | corrected |
| `http://hl7.org/fhir/v3/ActCode` | `CACC` | certified anatomic pathology and clinical pathology care |
| `http://hl7.org/fhir/v3/ActCode` | `CACS` | certified acute coronary syndrome care |
| `http://hl7.org/fhir/v3/ActCode` | `CAIC` | certified allergy and immunology care |
| `http://hl7.org/fhir/v3/ActCode` | `CAMC` | certified aerospace medicine care |
| `http://hl7.org/fhir/v3/ActCode` | `CAMI` | certified acute myocardial infarction care |
| `http://hl7.org/fhir/v3/ActCode` | `CANC` | certified anesthesiology care |
| `http://hl7.org/fhir/v3/ActCode` | `CANCAPT` | cancelled appointment |
| `http://hl7.org/fhir/v3/ActCode` | `CANPRG` | women's cancer detection program |
| `http://hl7.org/fhir/v3/ActCode` | `CAP` | capitation funding |
| `http://hl7.org/fhir/v3/ActCode` | `CAPC` | certified anatomic pathology care |
| `http://hl7.org/fhir/v3/ActCode` | `CARD` | Cardiology |
| `http://hl7.org/fhir/v3/ActCode` | `CARELIST` | care plan |
| `http://hl7.org/fhir/v3/ActCode` | `CASESER` | case seriousness criteria |
| `http://hl7.org/fhir/v3/ActCode` | `CASH` | Cash |
| `http://hl7.org/fhir/v3/ActCode` | `CAST` | certified asthma care |
| `http://hl7.org/fhir/v3/ActCode` | `CBAR` | certified bariatric surgery care |
| `http://hl7.org/fhir/v3/ActCode` | `CBGC` | certified clinical biochemical genetics care |
| `http://hl7.org/fhir/v3/ActCode` | `CC` | credit card |
| `http://hl7.org/fhir/v3/ActCode` | `CCAD` | certified coronary artery disease care |
| `http://hl7.org/fhir/v3/ActCode` | `CCAR` | certified cardiac care |
| `http://hl7.org/fhir/v3/ActCode` | `CCCC` | certified clinical cytogenetics care |
| `http://hl7.org/fhir/v3/ActCode` | `CCGC` | certified clinical genetics (M.D.) care |
| `http://hl7.org/fhir/v3/ActCode` | `CCPC` | certified clinical pathology care |
| `http://hl7.org/fhir/v3/ActCode` | `CCSC` | certified colon and rectal surgery care |
| `http://hl7.org/fhir/v3/ActCode` | `CDEC` | certified dermatology care |
| `http://hl7.org/fhir/v3/ActCode` | `CDEP` | certified depression care |
| `http://hl7.org/fhir/v3/ActCode` | `CDGD` | certified digestive/gastrointestinal disorders care |
| `http://hl7.org/fhir/v3/ActCode` | `CDIA` | certified diabetes care |
| `http://hl7.org/fhir/v3/ActCode` | `CDIO` | case disease imported observation |
| `http://hl7.org/fhir/v3/ActCode` | `CDRC` | certified diagnostic radiology care |
| `http://hl7.org/fhir/v3/ActCode` | `CDSREV` | clinical decision support intervention review |
| `http://hl7.org/fhir/v3/ActCode` | `CEL` | celebrity information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `CEMC` | certified emergency medicine care |
| `http://hl7.org/fhir/v3/ActCode` | `CEPI` | certified epilepsy care |
| `http://hl7.org/fhir/v3/ActCode` | `CFEL` | certified frail elderly care |
| `http://hl7.org/fhir/v3/ActCode` | `CFPC` | certified family practice care |
| `http://hl7.org/fhir/v3/ActCode` | `CFWD` | carry forward adjusment |
| `http://hl7.org/fhir/v3/ActCode` | `CHAR` | charity program |
| `http://hl7.org/fhir/v3/ActCode` | `CHFC` | certified heart failure care |
| `http://hl7.org/fhir/v3/ActCode` | `CHK` | Cheque |
| `http://hl7.org/fhir/v3/ActCode` | `CHLDCARE` | Day care - Child care Interaction |
| `http://hl7.org/fhir/v3/ActCode` | `CHR` | Chronic |
| `http://hl7.org/fhir/v3/ActCode` | `CHRG` | Standard Charge |
| `http://hl7.org/fhir/v3/ActCode` | `CHRO` | certified high risk obstetrics care |
| `http://hl7.org/fhir/v3/ActCode` | `CHRON` | continuous/chronic |
| `http://hl7.org/fhir/v3/ActCode` | `CHYP` | certified hyperlipidemia care |
| `http://hl7.org/fhir/v3/ActCode` | `CIMC` | certified internal medicine care |
| `http://hl7.org/fhir/v3/ActCode` | `CIRCLE` | circle |
| `http://hl7.org/fhir/v3/ActCode` | `CLINNOTEE` | clinical note entry task |
| `http://hl7.org/fhir/v3/ActCode` | `CLINNOTEREV` | clinical note review task |
| `http://hl7.org/fhir/v3/ActCode` | `CLSSRM` | classroom |
| `http://hl7.org/fhir/v3/ActCode` | `CMGC` | certified clinical molecular genetics care |
| `http://hl7.org/fhir/v3/ActCode` | `CMIH` | certified migraine headache care |
| `http://hl7.org/fhir/v3/ActCode` | `CMSC` | certified multiple sclerosis care |
| `http://hl7.org/fhir/v3/ActCode` | `CNEC` | certified neurology care |
| `http://hl7.org/fhir/v3/ActCode` | `CNMC` | certified nuclear medicine care |
| `http://hl7.org/fhir/v3/ActCode` | `CNQC` | certified neurology with special qualifications in child neurology care |
| `http://hl7.org/fhir/v3/ActCode` | `CNSC` | certified neurological surgery care |
| `http://hl7.org/fhir/v3/ActCode` | `COBSCAT` | common observation category |
| `http://hl7.org/fhir/v3/ActCode` | `CODE_DEPREC` | code has been deprecated |
| `http://hl7.org/fhir/v3/ActCode` | `CODE_INVAL` | code is not valid |
| `http://hl7.org/fhir/v3/ActCode` | `COGC` | certified obstetrics and gynecology care |
| `http://hl7.org/fhir/v3/ActCode` | `COIN` | coinsurance |
| `http://hl7.org/fhir/v3/ActCode` | `COINS` | co-insurance |
| `http://hl7.org/fhir/v3/ActCode` | `COJR` | certified orthopedic joint replacement care |
| `http://hl7.org/fhir/v3/ActCode` | `COL` | collision coverage policy |
| `http://hl7.org/fhir/v3/ActCode` | `COMC` | certified occupational medicine care |
| `http://hl7.org/fhir/v3/ActCode` | `COMPLY` | Compliance Alert |
| `http://hl7.org/fhir/v3/ActCode` | `COMPT` | compartment |
| `http://hl7.org/fhir/v3/ActCode` | `CONC` | certified oncology care |
| `http://hl7.org/fhir/v3/ActCode` | `COND` | Condition Alert |
| `http://hl7.org/fhir/v3/ActCode` | `CONDLIST` | condition list |
| `http://hl7.org/fhir/v3/ActCode` | `CONSUMPTION` | Consumption Volume |
| `http://hl7.org/fhir/v3/ActCode` | `CONT` | contract |
| `http://hl7.org/fhir/v3/ActCode` | `CONTF` | contract funding |
| `http://hl7.org/fhir/v3/ActCode` | `CONVEYNC` | Common Conveyance Interaction |
| `http://hl7.org/fhir/v3/ActCode` | `COPAY` |  |
| `http://hl7.org/fhir/v3/ActCode` | `COPAYMENT` | patient co-pay |
| `http://hl7.org/fhir/v3/ActCode` | `COPC` | certified ophthalmology care |
| `http://hl7.org/fhir/v3/ActCode` | `COPD` | certified chronic obstructive pulmonary disease care |
| `http://hl7.org/fhir/v3/ActCode` | `COPY` | copyright |
| `http://hl7.org/fhir/v3/ActCode` | `CORT` | certified organ transplant care |
| `http://hl7.org/fhir/v3/ActCode` | `COSC` | certified orthopaedic surgery care |
| `http://hl7.org/fhir/v3/ActCode` | `COTC` | certified otolaryngology care |
| `http://hl7.org/fhir/v3/ActCode` | `COVGE` | coverage problem |
| `http://hl7.org/fhir/v3/ActCode` | `COVMX` | coverage maximum |
| `http://hl7.org/fhir/v3/ActCode` | `COVPOL` | benefit policy |
| `http://hl7.org/fhir/v3/ActCode` | `COVPRD` | coverage period |
| `http://hl7.org/fhir/v3/ActCode` | `CPAD` | certified parkinsons disease care |
| `http://hl7.org/fhir/v3/ActCode` | `CPEC` | certified pediatrics care |
| `http://hl7.org/fhir/v3/ActCode` | `CPGC` | certified Ph.D. medical genetics care |
| `http://hl7.org/fhir/v3/ActCode` | `CPHC` | certified public health and general preventive medicine care |
| `http://hl7.org/fhir/v3/ActCode` | `CPINV` | clinical product invoice |
| `http://hl7.org/fhir/v3/ActCode` | `CPLYCC` | comply with confidentiality code |
| `http://hl7.org/fhir/v3/ActCode` | `CPLYCD` | comply with consent directive |
| `http://hl7.org/fhir/v3/ActCode` | `CPLYJPP` | comply with jurisdictional privacy policy |
| `http://hl7.org/fhir/v3/ActCode` | `CPLYOPP` | comply with organizational privacy policy |
| `http://hl7.org/fhir/v3/ActCode` | `CPLYOSP` | comply with organizational security policy |
| `http://hl7.org/fhir/v3/ActCode` | `CPLYPOL` | comply with policy |
| `http://hl7.org/fhir/v3/ActCode` | `CPND` | certified pneumonia disease care |
| `http://hl7.org/fhir/v3/ActCode` | `CPNDDRGING` | compound drug invoice group |
| `http://hl7.org/fhir/v3/ActCode` | `CPNDINDING` | compound ingredient invoice group |
| `http://hl7.org/fhir/v3/ActCode` | `CPNDSUPING` | compound supply invoice group |
| `http://hl7.org/fhir/v3/ActCode` | `CPRC` | certified physical medicine and rehabilitation care |
| `http://hl7.org/fhir/v3/ActCode` | `CPSC` | certified plastic surgery care |
| `http://hl7.org/fhir/v3/ActCode` | `CPST` | certified primary stroke center care |
| `http://hl7.org/fhir/v3/ActCode` | `CPTM` | CPT modifier codes |
| `http://hl7.org/fhir/v3/ActCode` | `CPYC` | certified psychiatry care |
| `http://hl7.org/fhir/v3/ActCode` | `CREACT` | common reaction alert |
| `http://hl7.org/fhir/v3/ActCode` | `CRIME` | crime victim program |
| `http://hl7.org/fhir/v3/ActCode` | `CRIT` | criticality |
| `http://hl7.org/fhir/v3/ActCode` | `CROC` | certified radiation oncology care |
| `http://hl7.org/fhir/v3/ActCode` | `CRPC` | certified radiological physics care |
| `http://hl7.org/fhir/v3/ActCode` | `CRS` | clinical recommendation statement |
| `http://hl7.org/fhir/v3/ActCode` | `CSDM` | certified stroke disease management care |
| `http://hl7.org/fhir/v3/ActCode` | `CSIC` | certified sickle cell care |
| `http://hl7.org/fhir/v3/ActCode` | `CSINV` | clinical service invoice |
| `http://hl7.org/fhir/v3/ActCode` | `CSLD` | certified sleep disorders care |
| `http://hl7.org/fhir/v3/ActCode` | `CSPINV` | clinical service and product |
| `http://hl7.org/fhir/v3/ActCode` | `CSPT` | certified spine treatment care |
| `http://hl7.org/fhir/v3/ActCode` | `CSUC` | certified surgery care |
| `http://hl7.org/fhir/v3/ActCode` | `CTBU` | certified trauma/burn center care |
| `http://hl7.org/fhir/v3/ActCode` | `CTLSUB` | Controlled Substance |
| `http://hl7.org/fhir/v3/ActCode` | `CTMO` | case transmission mode observation |
| `http://hl7.org/fhir/v3/ActCode` | `CTSC` | certified thoracic surgery care |
| `http://hl7.org/fhir/v3/ActCode` | `CURC` | certified urology care |
| `http://hl7.org/fhir/v3/ActCode` | `CURMEDLIST` | current medication list |
| `http://hl7.org/fhir/v3/ActCode` | `CURRENT` | Current Volume |
| `http://hl7.org/fhir/v3/ActCode` | `CVDC` | certified vascular diseases care |
| `http://hl7.org/fhir/v3/ActCode` | `CVSC` | certified vascular surgery care |
| `http://hl7.org/fhir/v3/ActCode` | `CWMA` | certified wound management care |
| `http://hl7.org/fhir/v3/ActCode` | `CWOH` | certified women's health care |
| `http://hl7.org/fhir/v3/ActCode` | `DACT` | drug action detected issue |
| `http://hl7.org/fhir/v3/ActCode` | `DALG` | Drug Allergy |
| `http://hl7.org/fhir/v3/ActCode` | `DAY` | day |
| `http://hl7.org/fhir/v3/ActCode` | `DDP` | Direct Deposit |
| `http://hl7.org/fhir/v3/ActCode` | `DEDUCT` |  |
| `http://hl7.org/fhir/v3/ActCode` | `DEDUCTIBLE` | deductible |
| `http://hl7.org/fhir/v3/ActCode` | `DEF` | definition |
| `http://hl7.org/fhir/v3/ActCode` | `DEFB` | Defibrination |
| `http://hl7.org/fhir/v3/ActCode` | `DEID` | deidentify |
| `http://hl7.org/fhir/v3/ActCode` | `DELAU` | delete after use |
| `http://hl7.org/fhir/v3/ActCode` | `DEMO` | all demographic information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `DEMOCAT` | demographics category |
| `http://hl7.org/fhir/v3/ActCode` | `DENEX` | denominator exclusions |
| `http://hl7.org/fhir/v3/ActCode` | `DENEXCEP` | denominator exceptions |
| `http://hl7.org/fhir/v3/ActCode` | `DENOM` | denominator |
| `http://hl7.org/fhir/v3/ActCode` | `DENTAL` | dental care policy |
| `http://hl7.org/fhir/v3/ActCode` | `DENTPRG` | dental program |
| `http://hl7.org/fhir/v3/ActCode` | `DERMTRNS` | transdermal transmission |
| `http://hl7.org/fhir/v3/ActCode` | `DF` | Daily Fill |
| `http://hl7.org/fhir/v3/ActCode` | `DIA` | diagnosis information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `DIAGLISTE` | diagnosis list entry task |
| `http://hl7.org/fhir/v3/ActCode` | `DIAGLISTREV` | diagnosis list review task |
| `http://hl7.org/fhir/v3/ActCode` | `DICAT` | diagnostic image category |
| `http://hl7.org/fhir/v3/ActCode` | `DIET` | Diet |
| `http://hl7.org/fhir/v3/ActCode` | `DILUTION` | ActSpecObsDilutionCode |
| `http://hl7.org/fhir/v3/ActCode` | `DINT` | Drug Intolerance |
| `http://hl7.org/fhir/v3/ActCode` | `DIS` | disability insurance policy |
| `http://hl7.org/fhir/v3/ActCode` | `DISC` | disclaimer |
| `http://hl7.org/fhir/v3/ActCode` | `DISCHINSTE` | discharge instruction entry |
| `http://hl7.org/fhir/v3/ActCode` | `DISCHSUME` | discharge summary entry task |
| `http://hl7.org/fhir/v3/ActCode` | `DISCHSUMREV` | discharge summary review task |
| `http://hl7.org/fhir/v3/ActCode` | `DISCMEDLIST` | discharge medication list |
| `http://hl7.org/fhir/v3/ActCode` | `DISDX` | discharge diagnosis |
| `http://hl7.org/fhir/v3/ActCode` | `DISEASE` | disease specific policy |
| `http://hl7.org/fhir/v3/ActCode` | `DISEASEPRG` | public health program |
| `http://hl7.org/fhir/v3/ActCode` | `DISPLAY` | Display |
| `http://hl7.org/fhir/v3/ActCode` | `DM` | diabetes mellitus diet |
| `http://hl7.org/fhir/v3/ActCode` | `DN` | Diner's Club |
| `http://hl7.org/fhir/v3/ActCode` | `DNAINT` | Drug Non-Allergy Intolerance |
| `http://hl7.org/fhir/v3/ActCode` | `DNTL` | Dental |
| `http://hl7.org/fhir/v3/ActCode` | `DOB` | date of birth information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `DOCUMENT` | document |
| `http://hl7.org/fhir/v3/ActCode` | `DOSE` | Dosage problem |
| `http://hl7.org/fhir/v3/ActCode` | `DOSECOND` | dosage-condition alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSEDUR` | Dose-Duration Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSEDURH` | Dose-Duration High Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSEDURHIND` | Dose-Duration High for Indication Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSEDURL` | Dose-Duration Low Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSEDURLIND` | Dose-Duration Low for Indication Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSEH` | High Dose Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSEHIND` | High Dose for Indication Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSEHINDA` | High Dose for Age Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSEHINDSA` | High Dose for Height/Surface Area Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSEHINDW` | High Dose for Weight Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSEIND` |  |
| `http://hl7.org/fhir/v3/ActCode` | `DOSEIVL` | Dose-Interval Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSEIVLIND` | Dose-Interval for Indication Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSEL` | Low Dose Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSELIND` | Low Dose for Indication Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSELINDA` | Low Dose for Age Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSELINDSA` | Low Dose for Height/Surface Area Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DOSELINDW` | Low Dose for Weight Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DRG` | Drug Interaction Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DRGIS` | drug information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `DRGRHB` | Drug Rehab |
| `http://hl7.org/fhir/v3/ActCode` | `DRUG` | Drug therapy |
| `http://hl7.org/fhir/v3/ActCode` | `DRUGING` | drug invoice group |
| `http://hl7.org/fhir/v3/ActCode` | `DRUGPOL` | drug policy |
| `http://hl7.org/fhir/v3/ActCode` | `DRUGPRG` | drug program |
| `http://hl7.org/fhir/v3/ActCode` | `DSC` | discount |
| `http://hl7.org/fhir/v3/ActCode` | `DUPTHPCLS` | duplicate therapeutic alass alert |
| `http://hl7.org/fhir/v3/ActCode` | `DUPTHPGEN` | duplicate generic alert |
| `http://hl7.org/fhir/v3/ActCode` | `DUPTHPY` | Duplicate Therapy Alert |
| `http://hl7.org/fhir/v3/ActCode` | `DV` | Discover Card |
| `http://hl7.org/fhir/v3/ActCode` | `DX` | ObservationDiagnosisTypes |
| `http://hl7.org/fhir/v3/ActCode` | `EALG` | Environmental Allergy |
| `http://hl7.org/fhir/v3/ActCode` | `EAP` | employee assistance program |
| `http://hl7.org/fhir/v3/ActCode` | `EDU` | education fees |
| `http://hl7.org/fhir/v3/ActCode` | `EFORM` | electronic form to follow |
| `http://hl7.org/fhir/v3/ActCode` | `EHCPOL` | extended healthcare |
| `http://hl7.org/fhir/v3/ActCode` | `EINT` | Environmental Intolerance |
| `http://hl7.org/fhir/v3/ActCode` | `ELG` | Eligible |
| `http://hl7.org/fhir/v3/ActCode` | `ELLIPSE` | ellipse |
| `http://hl7.org/fhir/v3/ActCode` | `EM` | Emergency Supply |
| `http://hl7.org/fhir/v3/ActCode` | `EMAUTH` | emergency authorization override |
| `http://hl7.org/fhir/v3/ActCode` | `EMER` | emergency |
| `http://hl7.org/fhir/v3/ActCode` | `EMP` | employee information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `EMPL` | employer information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `EMRGONLY` | emergency only |
| `http://hl7.org/fhir/v3/ActCode` | `ENAINT` | Environmental Non-Allergy Intolerance |
| `http://hl7.org/fhir/v3/ActCode` | `ENCRYPT` | encrypt |
| `http://hl7.org/fhir/v3/ActCode` | `ENCRYPTR` | encrypt at rest |
| `http://hl7.org/fhir/v3/ActCode` | `ENCRYPTT` | encrypt in transit |
| `http://hl7.org/fhir/v3/ActCode` | `ENCRYPTU` | encrypt in use |
| `http://hl7.org/fhir/v3/ActCode` | `ENDC` | endogenous content |
| `http://hl7.org/fhir/v3/ActCode` | `ENDLATE` | End Too Late Alert |
| `http://hl7.org/fhir/v3/ActCode` | `ENDRENAL` | end renal program |
| `http://hl7.org/fhir/v3/ActCode` | `ENVTRNS` | environmental exposure transmission |
| `http://hl7.org/fhir/v3/ActCode` | `EPYMT` | early payment fee |
| `http://hl7.org/fhir/v3/ActCode` | `ESA` | extraordinary service assessment |
| `http://hl7.org/fhir/v3/ActCode` | `ETH` | substance abuse information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `EVNFCTS` | ActSpecObsEvntfctsCode |
| `http://hl7.org/fhir/v3/ActCode` | `EWB` | employee welfare benefit plan policy |
| `http://hl7.org/fhir/v3/ActCode` | `F` | final |
| `http://hl7.org/fhir/v3/ActCode` | `FALG` | Food Allergy |
| `http://hl7.org/fhir/v3/ActCode` | `FALLRISK` | falls risk assessment instrument task |
| `http://hl7.org/fhir/v3/ActCode` | `FAST` | fasting |
| `http://hl7.org/fhir/v3/ActCode` | `FAX` | fax to follow |
| `http://hl7.org/fhir/v3/ActCode` | `FD` | food |
| `http://hl7.org/fhir/v3/ActCode` | `FDACOATING` | coating |
| `http://hl7.org/fhir/v3/ActCode` | `FDACOLOR` | color |
| `http://hl7.org/fhir/v3/ActCode` | `FDAIMPRINTCD` | imprint code |
| `http://hl7.org/fhir/v3/ActCode` | `FDALOGO` | logo |
| `http://hl7.org/fhir/v3/ActCode` | `FDASCORING` | scoring |
| `http://hl7.org/fhir/v3/ActCode` | `FDASHAPE` | shape |
| `http://hl7.org/fhir/v3/ActCode` | `FDASIZE` | size |
| `http://hl7.org/fhir/v3/ActCode` | `FECTRNS` | fecal-oral transmission |
| `http://hl7.org/fhir/v3/ActCode` | `FF` | First Fill |
| `http://hl7.org/fhir/v3/ActCode` | `FFC` | First Fill - Complete |
| `http://hl7.org/fhir/v3/ActCode` | `FFCS` | first fill complete, partial strength |
| `http://hl7.org/fhir/v3/ActCode` | `FFP` | First Fill - Part Fill |
| `http://hl7.org/fhir/v3/ActCode` | `FFPS` | first fill, part fill, partial strength |
| `http://hl7.org/fhir/v3/ActCode` | `FFS` | fee for service |
| `http://hl7.org/fhir/v3/ActCode` | `FFSS` | first fill, partial strength |
| `http://hl7.org/fhir/v3/ActCode` | `FFSTOP` | fee for service top off |
| `http://hl7.org/fhir/v3/ActCode` | `FIBRIN` | Fibrin |
| `http://hl7.org/fhir/v3/ActCode` | `FILT` | Filtration |
| `http://hl7.org/fhir/v3/ActCode` | `FINALDT` | finalized date/time |
| `http://hl7.org/fhir/v3/ActCode` | `FINBILL` | financial |
| `http://hl7.org/fhir/v3/ActCode` | `FININV` | financial invoice |
| `http://hl7.org/fhir/v3/ActCode` | `FINT` | Food Intolerance |
| `http://hl7.org/fhir/v3/ActCode` | `FLD` | field |
| `http://hl7.org/fhir/v3/ActCode` | `FLEXP` | flexible benefit plan policy |
| `http://hl7.org/fhir/v3/ActCode` | `FNAINT` | Food Non-Allergy Intolerance |
| `http://hl7.org/fhir/v3/ActCode` | `FNLFEE` | final fee |
| `http://hl7.org/fhir/v3/ActCode` | `FOMTRNS` | fomite transmission |
| `http://hl7.org/fhir/v3/ActCode` | `FOOD` | Food Interaction Alert |
| `http://hl7.org/fhir/v3/ActCode` | `FOODTRNS` | food-borne transmission |
| `http://hl7.org/fhir/v3/ActCode` | `FORM` | Print on Form |
| `http://hl7.org/fhir/v3/ActCode` | `FORMAT` | invalid format |
| `http://hl7.org/fhir/v3/ActCode` | `FORMULA` | formula diet |
| `http://hl7.org/fhir/v3/ActCode` | `FRAMEING` | frame invoice group |
| `http://hl7.org/fhir/v3/ActCode` | `FRAUD` | potential fraud |
| `http://hl7.org/fhir/v3/ActCode` | `FRSTFEE` | first fee |
| `http://hl7.org/fhir/v3/ActCode` | `FS` | Floor stock |
| `http://hl7.org/fhir/v3/ActCode` | `FST` | federal sales tax |
| `http://hl7.org/fhir/v3/ActCode` | `FULFIL` | fulfillment alert |
| `http://hl7.org/fhir/v3/ActCode` | `GARN` | garnishee |
| `http://hl7.org/fhir/v3/ActCode` | `GDIS` | genetic disease information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `GEALRT` | geriatric alert |
| `http://hl7.org/fhir/v3/ActCode` | `GEN` | Genetic Alert |
| `http://hl7.org/fhir/v3/ActCode` | `GEND` | Gender Alert |
| `http://hl7.org/fhir/v3/ActCode` | `GENDER` | gender and sexual orientation information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `GENE` | gene |
| `http://hl7.org/fhir/v3/ActCode` | `GENRL` | General |
| `http://hl7.org/fhir/v3/ActCode` | `GF` | gluten free |
| `http://hl7.org/fhir/v3/ActCode` | `GFTH` | good faith indicator |
| `http://hl7.org/fhir/v3/ActCode` | `GISTIER` | GIS tier |
| `http://hl7.org/fhir/v3/ActCode` | `GOALLIST` | goal list |
| `http://hl7.org/fhir/v3/ActCode` | `GOVEMP` | government employee health program |
| `http://hl7.org/fhir/v3/ActCode` | `GRADE` | grade |
| `http://hl7.org/fhir/v3/ActCode` | `GTIN` | Global Trade Item Number |
| `http://hl7.org/fhir/v3/ActCode` | `GUIDE` | guidance |
| `http://hl7.org/fhir/v3/ActCode` | `HCPCSA` | HCPCS Level II and Carrier-assigned |
| `http://hl7.org/fhir/v3/ActCode` | `HEALTHREC` | health record |
| `http://hl7.org/fhir/v3/ActCode` | `HELD` | held/suspended alert |
| `http://hl7.org/fhir/v3/ActCode` | `HEMOLYSIS` | Hemolysis |
| `http://hl7.org/fhir/v3/ActCode` | `HGHT` |  |
| `http://hl7.org/fhir/v3/ActCode` | `HH` | home health |
| `http://hl7.org/fhir/v3/ActCode` | `HHOBS` | household situation observation |
| `http://hl7.org/fhir/v3/ActCode` | `HIP` | health insurance plan policy |
| `http://hl7.org/fhir/v3/ActCode` | `HIRISK` | high risk pool program |
| `http://hl7.org/fhir/v3/ActCode` | `HISTMEDLIST` | medication history |
| `http://hl7.org/fhir/v3/ActCode` | `HISTORIC` | record recorded as historical |
| `http://hl7.org/fhir/v3/ActCode` | `HIV` | HIV/AIDS information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `HIVAIDS` | HIV-AIDS program |
| `http://hl7.org/fhir/v3/ActCode` | `HLTHCARE` | Health Care Interaction - Not Patient Care |
| `http://hl7.org/fhir/v3/ActCode` | `HMO` | health maintenance organization policy |
| `http://hl7.org/fhir/v3/ActCode` | `HOMECARE` | Care Giver Interaction |
| `http://hl7.org/fhir/v3/ActCode` | `HOSPPTNT` | Hospital Patient Interaction |
| `http://hl7.org/fhir/v3/ActCode` | `HOSPVSTR` | Hospital Visitor Interaction |
| `http://hl7.org/fhir/v3/ActCode` | `HOUSEHLD` | Household Interaction |
| `http://hl7.org/fhir/v3/ActCode` | `HRCOMPT` | human resource compartment |
| `http://hl7.org/fhir/v3/ActCode` | `HSAPOL` | health spending account |
| `http://hl7.org/fhir/v3/ActCode` | `HST` | harmonized sales Tax |
| `http://hl7.org/fhir/v3/ActCode` | `HUAPRV` | human approval |
| `http://hl7.org/fhir/v3/ActCode` | `HUMHUMTRNS` | human to human transmission |
| `http://hl7.org/fhir/v3/ActCode` | `I` | Isolation |
| `http://hl7.org/fhir/v3/ActCode` | `ICOL` | information collection |
| `http://hl7.org/fhir/v3/ActCode` | `ICTERUS` | Icterus |
| `http://hl7.org/fhir/v3/ActCode` | `ID` | Identified |
| `http://hl7.org/fhir/v3/ActCode` | `IDSCL` | information disclosure |
| `http://hl7.org/fhir/v3/ActCode` | `IDUR` | improvement notation |
| `http://hl7.org/fhir/v3/ActCode` | `ILLEGAL` | illegal |
| `http://hl7.org/fhir/v3/ActCode` | `IMG` | image attachment |
| `http://hl7.org/fhir/v3/ActCode` | `IMMLE` | immunization list entry |
| `http://hl7.org/fhir/v3/ActCode` | `IMMLREV` | immunization list review |
| `http://hl7.org/fhir/v3/ActCode` | `IMMUCAT` | immunization category |
| `http://hl7.org/fhir/v3/ActCode` | `IMMUNIZ` | Immunization |
| `http://hl7.org/fhir/v3/ActCode` | `IMP` | inpatient encounter |
| `http://hl7.org/fhir/v3/ActCode` | `IND` | indigenous peoples health program |
| `http://hl7.org/fhir/v3/ActCode` | `IND01` | imaging study requiring contrast |
| `http://hl7.org/fhir/v3/ActCode` | `IND02` | colonoscopy prep |
| `http://hl7.org/fhir/v3/ActCode` | `IND03` | prophylaxis |
| `http://hl7.org/fhir/v3/ActCode` | `IND04` | surgical prophylaxis |
| `http://hl7.org/fhir/v3/ActCode` | `IND05` | pregnancy prophylaxis |
| `http://hl7.org/fhir/v3/ActCode` | `INDTRNS` | indeterminate disease transmission mode |
| `http://hl7.org/fhir/v3/ActCode` | `INFA` | information access |
| `http://hl7.org/fhir/v3/ActCode` | `INFAO` | access only |
| `http://hl7.org/fhir/v3/ActCode` | `INFASO` | access and save only |
| `http://hl7.org/fhir/v3/ActCode` | `INFAUT` | authorized information transfer |
| `http://hl7.org/fhir/v3/ActCode` | `INFCON` | after explicit consent |
| `http://hl7.org/fhir/v3/ActCode` | `INFCRT` | only on court order |
| `http://hl7.org/fhir/v3/ActCode` | `INFDNG` | only if danger to others |
| `http://hl7.org/fhir/v3/ActCode` | `INFEMER` | only in an emergency |
| `http://hl7.org/fhir/v3/ActCode` | `INFPWR` | only if public welfare risk |
| `http://hl7.org/fhir/v3/ActCode` | `INFREG` | regulatory information transfer |
| `http://hl7.org/fhir/v3/ActCode` | `INITIAL` | Initial Volume |
| `http://hl7.org/fhir/v3/ActCode` | `INITIMMUNIZ` | Initial Immunization |
| `http://hl7.org/fhir/v3/ActCode` | `INMATE` | Inmate Interaction |
| `http://hl7.org/fhir/v3/ActCode` | `INT` | Intolerance Alert |
| `http://hl7.org/fhir/v3/ActCode` | `INTDX` | intermediate diagnosis |
| `http://hl7.org/fhir/v3/ActCode` | `INTERVAL` | outside requested time |
| `http://hl7.org/fhir/v3/ActCode` | `INTFR` | ActSpecObsInterferenceCode |
| `http://hl7.org/fhir/v3/ActCode` | `INTIMATE` | Intimate Interaction |
| `http://hl7.org/fhir/v3/ActCode` | `INTOLIST` | intolerance list |
| `http://hl7.org/fhir/v3/ActCode` | `INV` | investigational |
| `http://hl7.org/fhir/v3/ActCode` | `INVOICE` | submitted invoice |
| `http://hl7.org/fhir/v3/ActCode` | `INVTYPE` | invoice type |
| `http://hl7.org/fhir/v3/ActCode` | `IP` | In Position |
| `http://hl7.org/fhir/v3/ActCode` | `IPOP` | initial population |
| `http://hl7.org/fhir/v3/ActCode` | `IPPOP` | initial patient population |
| `http://hl7.org/fhir/v3/ActCode` | `IRDSCL` | information redisclosure |
| `http://hl7.org/fhir/v3/ActCode` | `ISOL` | isolation allowance |
| `http://hl7.org/fhir/v3/ActCode` | `ISSUE` | detected issue |
| `http://hl7.org/fhir/v3/ActCode` | `ITMCNT` | items counted |
| `http://hl7.org/fhir/v3/ActCode` | `KEY` | keyword |
| `http://hl7.org/fhir/v3/ActCode` | `KEY204` | Unknown key identifier |
| `http://hl7.org/fhir/v3/ActCode` | `KEY205` | Duplicate key identifier |
| `http://hl7.org/fhir/v3/ActCode` | `KEY206` | non-matching identification |
| `http://hl7.org/fhir/v3/ActCode` | `KSUBJ` | knowledge subject |
| `http://hl7.org/fhir/v3/ActCode` | `KSUBT` | knowledge subtopic |
| `http://hl7.org/fhir/v3/ActCode` | `L` | Left Equipment |
| `http://hl7.org/fhir/v3/ActCode` | `LAB` | Lab Alert |
| `http://hl7.org/fhir/v3/ActCode` | `LABCAT` | lab test category |
| `http://hl7.org/fhir/v3/ActCode` | `LABOE` | laboratory test order entry task |
| `http://hl7.org/fhir/v3/ActCode` | `LABRESULTS` | lab results |
| `http://hl7.org/fhir/v3/ActCode` | `LABRREV` | laboratory results review task |
| `http://hl7.org/fhir/v3/ActCode` | `LACT` | Lactation Alert |
| `http://hl7.org/fhir/v3/ActCode` | `LACTTRNS` | lactation transmission |
| `http://hl7.org/fhir/v3/ActCode` | `LATE` | late invoice |
| `http://hl7.org/fhir/v3/ActCode` | `LAWENF` | law enforcement transport |
| `http://hl7.org/fhir/v3/ActCode` | `LDLP` | LDL Precipitation |
| `http://hl7.org/fhir/v3/ActCode` | `LENSING` | lens invoice group |
| `http://hl7.org/fhir/v3/ActCode` | `LEN_LONG` | length is too long |
| `http://hl7.org/fhir/v3/ActCode` | `LEN_RANGE` | length out of range |
| `http://hl7.org/fhir/v3/ActCode` | `LEN_SHORT` | length is too short |
| `http://hl7.org/fhir/v3/ActCode` | `LF` | low fat |
| `http://hl7.org/fhir/v3/ActCode` | `LFEMX` | life time maximum |
| `http://hl7.org/fhir/v3/ActCode` | `LGPC` | licensed general physician care |
| `http://hl7.org/fhir/v3/ActCode` | `LIFE` | life insurance policy |
| `http://hl7.org/fhir/v3/ActCode` | `LIPEMIA` | Lipemia |
| `http://hl7.org/fhir/v3/ActCode` | `LIVARG` | living arrangement information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `LOAN` | Loan |
| `http://hl7.org/fhir/v3/ActCode` | `LOC` | location |
| `http://hl7.org/fhir/v3/ActCode` | `LOCIS` | location information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `LP` | low protein |
| `http://hl7.org/fhir/v3/ActCode` | `LQ` | liquid |
| `http://hl7.org/fhir/v3/ActCode` | `LS` | low sodium |
| `http://hl7.org/fhir/v3/ActCode` | `LTC` | long term care policy |
| `http://hl7.org/fhir/v3/ActCode` | `LTRMCARE` | Long Term Care Facility Interaction |
| `http://hl7.org/fhir/v3/ActCode` | `LU` | limited use |
| `http://hl7.org/fhir/v3/ActCode` | `M` | Missing |
| `http://hl7.org/fhir/v3/ActCode` | `MANDPOL` | mandatory health program |
| `http://hl7.org/fhir/v3/ActCode` | `MANUAL` | manual review |
| `http://hl7.org/fhir/v3/ActCode` | `MARKUP` | markup or up-charge |
| `http://hl7.org/fhir/v3/ActCode` | `MARST` | marital status information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `MARWLREV` | medication administration record work list review task |
| `http://hl7.org/fhir/v3/ActCode` | `MASK` | mask |
| `http://hl7.org/fhir/v3/ActCode` | `MAXOCCURS` | repetitions above maximum |
| `http://hl7.org/fhir/v3/ActCode` | `MC` | Master Card |
| `http://hl7.org/fhir/v3/ActCode` | `MCPOL` | managed care policy |
| `http://hl7.org/fhir/v3/ActCode` | `MDOSE` | maximum dosage reached |
| `http://hl7.org/fhir/v3/ActCode` | `MED` | Medical |
| `http://hl7.org/fhir/v3/ActCode` | `MEDCCAT` | medical condition category |
| `http://hl7.org/fhir/v3/ActCode` | `MEDLIST` | medication list |
| `http://hl7.org/fhir/v3/ActCode` | `MEDOE` | medication order entry task |
| `http://hl7.org/fhir/v3/ActCode` | `MEDT` | measurement end date |
| `http://hl7.org/fhir/v3/ActCode` | `MENCAT` | mental health category |
| `http://hl7.org/fhir/v3/ActCode` | `MENTPOL` | mental health policy |
| `http://hl7.org/fhir/v3/ActCode` | `MENTPRG` | mental health program |
| `http://hl7.org/fhir/v3/ActCode` | `MICROORGRREV` | microbiology organisms results review task |
| `http://hl7.org/fhir/v3/ActCode` | `MICRORREV` | microbiology results review task |
| `http://hl7.org/fhir/v3/ActCode` | `MICROSENSRREV` | microbiology sensitivity test results review task |
| `http://hl7.org/fhir/v3/ActCode` | `MILITARY` | military health program |
| `http://hl7.org/fhir/v3/ActCode` | `MINEC` | minimum necessary |
| `http://hl7.org/fhir/v3/ActCode` | `MINFREQ` | too soon within frequency based on the usage |
| `http://hl7.org/fhir/v3/ActCode` | `MINOCCURS` | repetitions below minimum |
| `http://hl7.org/fhir/v3/ActCode` | `MISSAPT` | missed appointment |
| `http://hl7.org/fhir/v3/ActCode` | `MISSCOND` | conditional element missing |
| `http://hl7.org/fhir/v3/ActCode` | `MISSMAND` | mandatory element missing |
| `http://hl7.org/fhir/v3/ActCode` | `MLREV` | medication list review task |
| `http://hl7.org/fhir/v3/ActCode` | `MODEL` | model |
| `http://hl7.org/fhir/v3/ActCode` | `MONTH` | month |
| `http://hl7.org/fhir/v3/ActCode` | `MS` | Manufacturer Sample |
| `http://hl7.org/fhir/v3/ActCode` | `MSD` | measurement start date |
| `http://hl7.org/fhir/v3/ActCode` | `MSRADJ` | risk adjustment |
| `http://hl7.org/fhir/v3/ActCode` | `MSRAGG` | rate aggregation |
| `http://hl7.org/fhir/v3/ActCode` | `MSRIMPROV` | health quality measure improvement notation |
| `http://hl7.org/fhir/v3/ActCode` | `MSRJUR` | jurisdiction |
| `http://hl7.org/fhir/v3/ActCode` | `MSRPOPL` | measure population |
| `http://hl7.org/fhir/v3/ActCode` | `MSRPOPLEX` | measure population exclusions |
| `http://hl7.org/fhir/v3/ActCode` | `MSRRPTR` | reporter type |
| `http://hl7.org/fhir/v3/ActCode` | `MSRRPTTIME` | timeframe for reporting |
| `http://hl7.org/fhir/v3/ActCode` | `MSRSCORE` | measure scoring |
| `http://hl7.org/fhir/v3/ActCode` | `MSRSET` | health quality measure care setting |
| `http://hl7.org/fhir/v3/ActCode` | `MSRTOPIC` | health quality measure topic type |
| `http://hl7.org/fhir/v3/ActCode` | `MSRTP` | measurement period |
| `http://hl7.org/fhir/v3/ActCode` | `MSRTYPE` | measure type |
| `http://hl7.org/fhir/v3/ActCode` | `MVA` | Motor vehicle accident |
| `http://hl7.org/fhir/v3/ActCode` | `N` | normal diet |
| `http://hl7.org/fhir/v3/ActCode` | `NAINT` | Non-Allergy Intolerance |
| `http://hl7.org/fhir/v3/ActCode` | `NAT` | Insufficient authorization |
| `http://hl7.org/fhir/v3/ActCode` | `NAUTH` | Not Authorized |
| `http://hl7.org/fhir/v3/ActCode` | `NELG` | Not Eligible |
| `http://hl7.org/fhir/v3/ActCode` | `NETAMT` | Net Amount |
| `http://hl7.org/fhir/v3/ActCode` | `NEUT` | Neutralization |
| `http://hl7.org/fhir/v3/ActCode` | `NF` | no fat |
| `http://hl7.org/fhir/v3/ActCode` | `NHP` | Natural Health Product Alert |
| `http://hl7.org/fhir/v3/ActCode` | `NOAUTH` | no disclosure without subject authorization |
| `http://hl7.org/fhir/v3/ActCode` | `NOCOLLECT` | no collection |
| `http://hl7.org/fhir/v3/ActCode` | `NODSCLCD` | no disclosure without consent directive |
| `http://hl7.org/fhir/v3/ActCode` | `NODSCLCDS` | no disclosure without information subject's consent directive |
| `http://hl7.org/fhir/v3/ActCode` | `NODUPS` | duplicate values are not permitted |
| `http://hl7.org/fhir/v3/ActCode` | `NOI` | nature of injury |
| `http://hl7.org/fhir/v3/ActCode` | `NOINTEGRATE` | no integration |
| `http://hl7.org/fhir/v3/ActCode` | `NOLIST` | no unlisted entity disclosure |
| `http://hl7.org/fhir/v3/ActCode` | `NOMOU` | no disclosure without MOU |
| `http://hl7.org/fhir/v3/ActCode` | `NON` | Non-Payment Data |
| `http://hl7.org/fhir/v3/ActCode` | `NONAC` | inpatient non-acute |
| `http://hl7.org/fhir/v3/ActCode` | `NONRX` | Non-Prescription Interaction Alert |
| `http://hl7.org/fhir/v3/ActCode` | `NOORGPOL` | no disclosure without organizational authorization |
| `http://hl7.org/fhir/v3/ActCode` | `NOPAT` | no disclosure to patient, family or caregivers without attending provider's authorization |
| `http://hl7.org/fhir/v3/ActCode` | `NOPERSIST` | element will not be persisted |
| `http://hl7.org/fhir/v3/ActCode` | `NOPERSISTP` | no collection beyond purpose of use |
| `http://hl7.org/fhir/v3/ActCode` | `NOPP` | notice of privacy practices |
| `http://hl7.org/fhir/v3/ActCode` | `NORDSCLCD` | no redisclosure without consent directive |
| `http://hl7.org/fhir/v3/ActCode` | `NORDSCLCDS` | no redisclosure without information subject's consent directive |
| `http://hl7.org/fhir/v3/ActCode` | `NORDSCLW` | no disclosure without jurisdictional authorization |
| `http://hl7.org/fhir/v3/ActCode` | `NORELINK` | no relinking |
| `http://hl7.org/fhir/v3/ActCode` | `NOREUSE` | no reuse beyond purpose of use |
| `http://hl7.org/fhir/v3/ActCode` | `NOSTRNS` | nosocomial transmission |
| `http://hl7.org/fhir/v3/ActCode` | `NOTACTN` | no longer actionable |
| `http://hl7.org/fhir/v3/ActCode` | `NOTEQUIV` | not equivalent alert |
| `http://hl7.org/fhir/v3/ActCode` | `NOTEQUIVGEN` | not generically equivalent alert |
| `http://hl7.org/fhir/v3/ActCode` | `NOTEQUIVTHER` | not therapeutically equivalent alert |
| `http://hl7.org/fhir/v3/ActCode` | `NOVIP` | no unauthorized VIP disclosure |
| `http://hl7.org/fhir/v3/ActCode` | `NUMER` | numerator |
| `http://hl7.org/fhir/v3/ActCode` | `NUMEX` | numerator exclusions |
| `http://hl7.org/fhir/v3/ActCode` | `O` | In Process |
| `http://hl7.org/fhir/v3/ActCode` | `OBS` | Obstetrics |
| `http://hl7.org/fhir/v3/ActCode` | `OBSA` | Observation Alert |
| `http://hl7.org/fhir/v3/ActCode` | `OBSANTC` | antigen count |
| `http://hl7.org/fhir/v3/ActCode` | `OBSANTV` | antigen validity |
| `http://hl7.org/fhir/v3/ActCode` | `OBSOLETE` | obsolete record returned |
| `http://hl7.org/fhir/v3/ActCode` | `OE` | order entry task |
| `http://hl7.org/fhir/v3/ActCode` | `OHSINV` | oral health service |
| `http://hl7.org/fhir/v3/ActCode` | `OINT` | intolerance |
| `http://hl7.org/fhir/v3/ActCode` | `ONC` | Oncology |
| `http://hl7.org/fhir/v3/ActCode` | `ONET` | one time |
| `http://hl7.org/fhir/v3/ActCode` | `OOJ` | out of jurisdiction |
| `http://hl7.org/fhir/v3/ActCode` | `OOO` | out of office |
| `http://hl7.org/fhir/v3/ActCode` | `OPTIN` | opt-in |
| `http://hl7.org/fhir/v3/ActCode` | `OPTOUT` | op-out |
| `http://hl7.org/fhir/v3/ActCode` | `ORCON` | no disclosure without originator authorization |
| `http://hl7.org/fhir/v3/ActCode` | `OREV` | orders review task |
| `http://hl7.org/fhir/v3/ActCode` | `ORTHO` | orthodontic service |
| `http://hl7.org/fhir/v3/ActCode` | `OTC` | non prescription medicine |
| `http://hl7.org/fhir/v3/ActCode` | `ObligationPolicy` | obligation policy |
| `http://hl7.org/fhir/v3/ActCode` | `P` | Private |
| `http://hl7.org/fhir/v3/ActCode` | `PAF` | phenylalanine free |
| `http://hl7.org/fhir/v3/ActCode` | `PAINV` | preferred accommodation invoice |
| `http://hl7.org/fhir/v3/ActCode` | `PALL` | Palliative |
| `http://hl7.org/fhir/v3/ActCode` | `PAPER` | paper documentation to follow |
| `http://hl7.org/fhir/v3/ActCode` | `PAR` | parenteral |
| `http://hl7.org/fhir/v3/ActCode` | `PARTRNS` | parenteral transmission |
| `http://hl7.org/fhir/v3/ActCode` | `PATDOC` | patient documentation task |
| `http://hl7.org/fhir/v3/ActCode` | `PATEDUE` | patient education entry |
| `http://hl7.org/fhir/v3/ActCode` | `PATINFO` | patient information review task |
| `http://hl7.org/fhir/v3/ActCode` | `PATPREF` | violates stated preferences |
| `http://hl7.org/fhir/v3/ActCode` | `PATPREFALT` | violates stated preferences, alternate available |
| `http://hl7.org/fhir/v3/ActCode` | `PATREPE` | pathology report entry task |
| `http://hl7.org/fhir/v3/ActCode` | `PATREPREV` | pathology report review task |
| `http://hl7.org/fhir/v3/ActCode` | `PAT_ADV_EVNT` | patient adverse event |
| `http://hl7.org/fhir/v3/ActCode` | `PAY` | payment |
| `http://hl7.org/fhir/v3/ActCode` | `PAYEE` | payee |
| `http://hl7.org/fhir/v3/ActCode` | `PAYOR` | payor |
| `http://hl7.org/fhir/v3/ActCode` | `PBILLACCT` | patient billing account |
| `http://hl7.org/fhir/v3/ActCode` | `PDNFPPELAT` | paid nullified prior-period electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `PDNFPPELCT` | paid nullified prior-period electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `PDNFPPMNAT` | paid nullified prior-period manual amount |
| `http://hl7.org/fhir/v3/ActCode` | `PDNFPPMNCT` | paid nullified prior-period manual count |
| `http://hl7.org/fhir/v3/ActCode` | `PDNFSPELAT` | paid nullified same-period electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `PDNFSPELCT` | paid nullified same-period electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `PDNFSPMNAT` | paid nullified same-period manual amount |
| `http://hl7.org/fhir/v3/ActCode` | `PDNFSPMNCT` | paid nullified same-period manual count |
| `http://hl7.org/fhir/v3/ActCode` | `PDNPPPELAT` | paid non-payee payable prior-period electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `PDNPPPELCT` | paid non-payee payable prior-period electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `PDNPPPMNAT` | paid non-payee payable prior-period manual amount |
| `http://hl7.org/fhir/v3/ActCode` | `PDNPPPMNCT` | paid non-payee payable prior-period manual count |
| `http://hl7.org/fhir/v3/ActCode` | `PDNPSPELAT` | paid non-payee payable same-period electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `PDNPSPELCT` | paid non-payee payable same-period electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `PDNPSPMNAT` | paid non-payee payable same-period manual amount |
| `http://hl7.org/fhir/v3/ActCode` | `PDNPSPMNCT` | paid non-payee payable same-period manual count |
| `http://hl7.org/fhir/v3/ActCode` | `PDPPPPELAT` | paid payee payable prior-period electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `PDPPPPELCT` | paid payee payable prior-period electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `PDPPPPMNAT` | paid payee payable prior-period manual amount |
| `http://hl7.org/fhir/v3/ActCode` | `PDPPPPMNCT` | paid payee payable prior-period manual count |
| `http://hl7.org/fhir/v3/ActCode` | `PDPPSPELAT` | paid payee payable same-period electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `PDPPSPELCT` | paid payee payable same-period electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `PDPPSPMNAT` | paid payee payable same-period manual amount |
| `http://hl7.org/fhir/v3/ActCode` | `PDPPSPMNCT` | paid payee payable same-period manual count |
| `http://hl7.org/fhir/v3/ActCode` | `PDS` | patient default sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `PEALRT` | pediatric alert |
| `http://hl7.org/fhir/v3/ActCode` | `PED` | Pediatrics |
| `http://hl7.org/fhir/v3/ActCode` | `PERFEE` | periodic fee |
| `http://hl7.org/fhir/v3/ActCode` | `PERIOD` | period |
| `http://hl7.org/fhir/v3/ActCode` | `PERMBNS` | performance bonus |
| `http://hl7.org/fhir/v3/ActCode` | `PHAR` | Pharmaceutical |
| `http://hl7.org/fhir/v3/ActCode` | `PHYRHB` | Physical Rehab |
| `http://hl7.org/fhir/v3/ActCode` | `PIE` | public insurance exhausted |
| `http://hl7.org/fhir/v3/ActCode` | `PINV` | paper invoice |
| `http://hl7.org/fhir/v3/ActCode` | `PLACE` | Common Space Interaction |
| `http://hl7.org/fhir/v3/ActCode` | `PLACTRNS` | transplacental transmission |
| `http://hl7.org/fhir/v3/ActCode` | `PLYDOC` | Poly-orderer Alert |
| `http://hl7.org/fhir/v3/ActCode` | `PLYPHRM` | Poly-supplier Alert |
| `http://hl7.org/fhir/v3/ActCode` | `PNC` | property and casualty insurance policy |
| `http://hl7.org/fhir/v3/ActCode` | `POINT` | point |
| `http://hl7.org/fhir/v3/ActCode` | `POLY` | polyline |
| `http://hl7.org/fhir/v3/ActCode` | `POS` | point of service policy |
| `http://hl7.org/fhir/v3/ActCode` | `PPO` | preferred provider organization policy |
| `http://hl7.org/fhir/v3/ActCode` | `PPRD` | prior period adjustment |
| `http://hl7.org/fhir/v3/ActCode` | `PRA` |  |
| `http://hl7.org/fhir/v3/ActCode` | `PRDING` | product invoice group |
| `http://hl7.org/fhir/v3/ActCode` | `PRDMX` | period maximum |
| `http://hl7.org/fhir/v3/ActCode` | `PRE` | Pre-Dilution |
| `http://hl7.org/fhir/v3/ActCode` | `PREFSTRENGTH` | preference strength |
| `http://hl7.org/fhir/v3/ActCode` | `PREG` | Pregnancy Alert |
| `http://hl7.org/fhir/v3/ActCode` | `PRENC` | pre-admission |
| `http://hl7.org/fhir/v3/ActCode` | `PREVINEF` | previously ineffective |
| `http://hl7.org/fhir/v3/ActCode` | `PRIVMARK` | privacy mark |
| `http://hl7.org/fhir/v3/ActCode` | `PRLMN` | preliminary |
| `http://hl7.org/fhir/v3/ActCode` | `PRN` | as needed |
| `http://hl7.org/fhir/v3/ActCode` | `PROA` | professional association deduction |
| `http://hl7.org/fhir/v3/ActCode` | `PROBLIST` | problem list |
| `http://hl7.org/fhir/v3/ActCode` | `PROBLISTE` | problem list entry task |
| `http://hl7.org/fhir/v3/ActCode` | `PROBLISTREV` | problem list review task |
| `http://hl7.org/fhir/v3/ActCode` | `PROV` | provider |
| `http://hl7.org/fhir/v3/ActCode` | `PRS` | patient requested sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `PRVTRN` | private transport |
| `http://hl7.org/fhir/v3/ActCode` | `PSEUD` | pseudonymize |
| `http://hl7.org/fhir/v3/ActCode` | `PST` | provincial/state sales tax |
| `http://hl7.org/fhir/v3/ActCode` | `PSVCCAT` | professional service category |
| `http://hl7.org/fhir/v3/ActCode` | `PSY` | psychiatry information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `PSYCH` | Psychiatric |
| `http://hl7.org/fhir/v3/ActCode` | `PTNTCARE` | Health Care Interaction - Patient Care |
| `http://hl7.org/fhir/v3/ActCode` | `PUBLICPOL` | public healthcare |
| `http://hl7.org/fhir/v3/ActCode` | `PUBTRN` | public transport |
| `http://hl7.org/fhir/v3/ActCode` | `PYRDELAY` | delayed by a previous payor |
| `http://hl7.org/fhir/v3/ActCode` | `R` | Process Completed |
| `http://hl7.org/fhir/v3/ActCode` | `RACE` | race information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `RADREPE` | radiology report entry task |
| `http://hl7.org/fhir/v3/ActCode` | `RADREPREV` | radiology report review task |
| `http://hl7.org/fhir/v3/ActCode` | `RALG` | Related Allergy Alert |
| `http://hl7.org/fhir/v3/ActCode` | `RAR` | Related Prior Reaction Alert |
| `http://hl7.org/fhir/v3/ActCode` | `RAT` | rationale |
| `http://hl7.org/fhir/v3/ActCode` | `RD` | reduction diet |
| `http://hl7.org/fhir/v3/ActCode` | `REACT` | Reaction Alert |
| `http://hl7.org/fhir/v3/ActCode` | `RECA` | Recalcification |
| `http://hl7.org/fhir/v3/ActCode` | `RECOV` | recovery |
| `http://hl7.org/fhir/v3/ActCode` | `REDACT` | redact |
| `http://hl7.org/fhir/v3/ActCode` | `REF` | reference |
| `http://hl7.org/fhir/v3/ActCode` | `REFLEX` | reflex permission |
| `http://hl7.org/fhir/v3/ActCode` | `REFNR` | referral not required |
| `http://hl7.org/fhir/v3/ActCode` | `REI` | reinsurance policy |
| `http://hl7.org/fhir/v3/ActCode` | `REL` | religion information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `REMLE` | reminder list entry |
| `http://hl7.org/fhir/v3/ActCode` | `REMLREV` | reminder list review |
| `http://hl7.org/fhir/v3/ActCode` | `RENT` | Rent |
| `http://hl7.org/fhir/v3/ActCode` | `REPRESENTATIVE_BEAT` | ECG representative beat waveforms |
| `http://hl7.org/fhir/v3/ActCode` | `REPSERV` | repeated service |
| `http://hl7.org/fhir/v3/ActCode` | `REP_HALF_LIFE` | representative half-life |
| `http://hl7.org/fhir/v3/ActCode` | `REP_RANGE` | repetitions out of range |
| `http://hl7.org/fhir/v3/ActCode` | `RERUN` | Rerun Dilution |
| `http://hl7.org/fhir/v3/ActCode` | `RESCOMPT` | research project compartment |
| `http://hl7.org/fhir/v3/ActCode` | `RESEARCH` | research information access |
| `http://hl7.org/fhir/v3/ActCode` | `RESTOCK` | restocking fee |
| `http://hl7.org/fhir/v3/ActCode` | `RETIRE` | retiree health program |
| `http://hl7.org/fhir/v3/ActCode` | `RETRO` | retro adjustment |
| `http://hl7.org/fhir/v3/ActCode` | `REV` | Standard Charge Reversal |
| `http://hl7.org/fhir/v3/ActCode` | `RF` | Refill |
| `http://hl7.org/fhir/v3/ActCode` | `RFC` | Refill - Complete |
| `http://hl7.org/fhir/v3/ActCode` | `RFCS` | refill complete partial strength |
| `http://hl7.org/fhir/v3/ActCode` | `RFF` | Refill (First fill this facility) |
| `http://hl7.org/fhir/v3/ActCode` | `RFFS` | refill partial strength (first fill this facility) |
| `http://hl7.org/fhir/v3/ActCode` | `RFP` | Refill - Part Fill |
| `http://hl7.org/fhir/v3/ActCode` | `RFPS` | refill part fill partial strength |
| `http://hl7.org/fhir/v3/ActCode` | `RFS` | refill partial strength |
| `http://hl7.org/fhir/v3/ActCode` | `RHYTHM` | ECG rhythm waveforms |
| `http://hl7.org/fhir/v3/ActCode` | `RINT` | Related Intolerance Alert |
| `http://hl7.org/fhir/v3/ActCode` | `RISKASSESS` | risk assessment instrument task |
| `http://hl7.org/fhir/v3/ActCode` | `RISKLIST` | risk factors |
| `http://hl7.org/fhir/v3/ActCode` | `RMGTCOMPT` | records management compartment |
| `http://hl7.org/fhir/v3/ActCode` | `ROIFS` | fully specified ROI |
| `http://hl7.org/fhir/v3/ActCode` | `ROIPS` | partially specified ROI |
| `http://hl7.org/fhir/v3/ActCode` | `ROST` | roster funding |
| `http://hl7.org/fhir/v3/ActCode` | `RREACT` | Related Reaction Alert |
| `http://hl7.org/fhir/v3/ActCode` | `RSDID` | de-identified information access |
| `http://hl7.org/fhir/v3/ActCode` | `RSREID` | re-identifiable information access |
| `http://hl7.org/fhir/v3/ActCode` | `RX` | prescription only medicine |
| `http://hl7.org/fhir/v3/ActCode` | `RXCAT` | medication category |
| `http://hl7.org/fhir/v3/ActCode` | `RXCINV` | Rx compound invoice |
| `http://hl7.org/fhir/v3/ActCode` | `RXDINV` | Rx dispense invoice |
| `http://hl7.org/fhir/v3/ActCode` | `RefrainPolicy` | refrain policy |
| `http://hl7.org/fhir/v3/ActCode` | `S` | Suite |
| `http://hl7.org/fhir/v3/ActCode` | `SA` | special authorization |
| `http://hl7.org/fhir/v3/ActCode` | `SAC` | special access |
| `http://hl7.org/fhir/v3/ActCode` | `SAFNET` | safety net clinic program |
| `http://hl7.org/fhir/v3/ActCode` | `SALE` | Sale |
| `http://hl7.org/fhir/v3/ActCode` | `SBBLELAT` | submitted billed electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `SBBLELCT` | submitted billed electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `SBFINV` | sessional or block fee invoice |
| `http://hl7.org/fhir/v3/ActCode` | `SBNFELAT` | submitted nullified electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `SBNFELCT` | submitted cancelled electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `SBPDELAT` | submitted pending electronic amount |
| `http://hl7.org/fhir/v3/ActCode` | `SBPDELCT` | submitted pending electronic count |
| `http://hl7.org/fhir/v3/ActCode` | `SCA` | sickle cell anemia |
| `http://hl7.org/fhir/v3/ActCode` | `SCH` | schonkost (GE) |
| `http://hl7.org/fhir/v3/ActCode` | `SCHL` | school |
| `http://hl7.org/fhir/v3/ActCode` | `SCHLDIV` | school division |
| `http://hl7.org/fhir/v3/ActCode` | `SCHOOL` | School Accident |
| `http://hl7.org/fhir/v3/ActCode` | `SCHOOL2` | School Interaction |
| `http://hl7.org/fhir/v3/ActCode` | `SDE` | supplemental data elements |
| `http://hl7.org/fhir/v3/ActCode` | `SDV` | sexual assault, abuse, or domestic violence information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `SECALTINTOBS` | security alteration integrity observation |
| `http://hl7.org/fhir/v3/ActCode` | `SECCATOBS` | security category observation |
| `http://hl7.org/fhir/v3/ActCode` | `SECCLASSOBS` | security classification observation |
| `http://hl7.org/fhir/v3/ActCode` | `SECCONOBS` | security control observation |
| `http://hl7.org/fhir/v3/ActCode` | `SECDATINTOBS` | security data integrity observation |
| `http://hl7.org/fhir/v3/ActCode` | `SECINTCONOBS` | security integrity confidence observation |
| `http://hl7.org/fhir/v3/ActCode` | `SECINTOBS` | security integrity observation |
| `http://hl7.org/fhir/v3/ActCode` | `SECINTPRVABOBS` | security integrity provenance asserted by observation |
| `http://hl7.org/fhir/v3/ActCode` | `SECINTPRVRBOBS` | security integrity provenance reported by observation |
| `http://hl7.org/fhir/v3/ActCode` | `SECINTSTOBS` | security integrity status observation |
| `http://hl7.org/fhir/v3/ActCode` | `SENDAPP` | sending application |
| `http://hl7.org/fhir/v3/ActCode` | `SESS` | sessional funding |
| `http://hl7.org/fhir/v3/ActCode` | `SEV` | Severity Observation |
| `http://hl7.org/fhir/v3/ActCode` | `SEX` | sexuality and reproductive health information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `SEXTRNS` | sexual transmission |
| `http://hl7.org/fhir/v3/ActCode` | `SICKLE` | sickle cell |
| `http://hl7.org/fhir/v3/ActCode` | `SO` | Script Owing |
| `http://hl7.org/fhir/v3/ActCode` | `SOCIAL` | social service program |
| `http://hl7.org/fhir/v3/ActCode` | `SOCIAL2` | Social/Extended Family Interaction |
| `http://hl7.org/fhir/v3/ActCode` | `SP` | Semi-private |
| `http://hl7.org/fhir/v3/ActCode` | `SPEND` | spend down |
| `http://hl7.org/fhir/v3/ActCode` | `SPLCOATING` | coating |
| `http://hl7.org/fhir/v3/ActCode` | `SPLCOLOR` | color |
| `http://hl7.org/fhir/v3/ActCode` | `SPLIMAGE` | image |
| `http://hl7.org/fhir/v3/ActCode` | `SPLIMPRINT` | imprint |
| `http://hl7.org/fhir/v3/ActCode` | `SPLSCORING` | scoring |
| `http://hl7.org/fhir/v3/ActCode` | `SPLSHAPE` | shape |
| `http://hl7.org/fhir/v3/ActCode` | `SPLSIZE` | size |
| `http://hl7.org/fhir/v3/ActCode` | `SPLSYMBOL` | symbol |
| `http://hl7.org/fhir/v3/ActCode` | `SPT` | Sporting Accident |
| `http://hl7.org/fhir/v3/ActCode` | `SREC` | specimen received |
| `http://hl7.org/fhir/v3/ActCode` | `SS` | short stay |
| `http://hl7.org/fhir/v3/ActCode` | `SSP` | sensitive service provider information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `SSTOR` | specimen in storage |
| `http://hl7.org/fhir/v3/ActCode` | `STD` | sexually transmitted disease information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `STORE` | Storage |
| `http://hl7.org/fhir/v3/ActCode` | `STRAN` | specimen in transit |
| `http://hl7.org/fhir/v3/ActCode` | `STRAT` | stratification |
| `http://hl7.org/fhir/v3/ActCode` | `STRTLATE` | Start Too Late Alert |
| `http://hl7.org/fhir/v3/ActCode` | `SUBPOL` | substance use policy |
| `http://hl7.org/fhir/v3/ActCode` | `SUBPRG` | substance use program |
| `http://hl7.org/fhir/v3/ActCode` | `SUBSIDFFS` | subsidized fee for service program |
| `http://hl7.org/fhir/v3/ActCode` | `SUBSIDIZ` | subsidized health program |
| `http://hl7.org/fhir/v3/ActCode` | `SUBSIDMC` | subsidized managed care program |
| `http://hl7.org/fhir/v3/ActCode` | `SUBSTNCE` | Common Substance Interaction |
| `http://hl7.org/fhir/v3/ActCode` | `SUBSUPP` | subsidized supplemental health program |
| `http://hl7.org/fhir/v3/ActCode` | `SUPPLEMENT` | nutritional supplement |
| `http://hl7.org/fhir/v3/ActCode` | `SUPPRESSED` | record suppressed |
| `http://hl7.org/fhir/v3/ActCode` | `SURG` | Surgical |
| `http://hl7.org/fhir/v3/ActCode` | `SURPL` | surplus line insurance policy |
| `http://hl7.org/fhir/v3/ActCode` | `SecurityPolicy` | security policy |
| `http://hl7.org/fhir/v3/ActCode` | `T` | tea only |
| `http://hl7.org/fhir/v3/ActCode` | `TB` | Trial Balance |
| `http://hl7.org/fhir/v3/ActCode` | `TBOO` | taboo |
| `http://hl7.org/fhir/v3/ActCode` | `TBS` | trial balance partial strength |
| `http://hl7.org/fhir/v3/ActCode` | `TEACHER` | teacher |
| `http://hl7.org/fhir/v3/ActCode` | `TF` | Trial Fill |
| `http://hl7.org/fhir/v3/ActCode` | `TFS` | trial fill partial strength |
| `http://hl7.org/fhir/v3/ActCode` | `TIME` | timing detected issue |
| `http://hl7.org/fhir/v3/ActCode` | `TIME_ABSOLUTE` | absolute time sequence |
| `http://hl7.org/fhir/v3/ActCode` | `TIME_RELATIVE` | relative time sequence |
| `http://hl7.org/fhir/v3/ActCode` | `TIMING` | event timing incorrect alert |
| `http://hl7.org/fhir/v3/ActCode` | `TLIFE` | term life insurance policy |
| `http://hl7.org/fhir/v3/ActCode` | `TOOLATE` | Refill Too Late Alert |
| `http://hl7.org/fhir/v3/ActCode` | `TOOSOON` | Refill Too Soon Alert |
| `http://hl7.org/fhir/v3/ActCode` | `TPROD` | Therapeutic Product Alert |
| `http://hl7.org/fhir/v3/ActCode` | `TRAN` | transaction fee |
| `http://hl7.org/fhir/v3/ActCode` | `TRANF` | transmission format |
| `http://hl7.org/fhir/v3/ActCode` | `TRANSFER` | Transfer |
| `http://hl7.org/fhir/v3/ActCode` | `TRAVEL` | travel |
| `http://hl7.org/fhir/v3/ActCode` | `TRAVINT` | Common Travel Interaction |
| `http://hl7.org/fhir/v3/ActCode` | `TRNSFTRNS` | transfusion transmission |
| `http://hl7.org/fhir/v3/ActCode` | `TRSTACCRD` | trust accreditation |
| `http://hl7.org/fhir/v3/ActCode` | `TRSTACCRDOBS` | trust accreditation observation |
| `http://hl7.org/fhir/v3/ActCode` | `TRSTAGRE` | trust agreement |
| `http://hl7.org/fhir/v3/ActCode` | `TRSTAGREOBS` | trust agreement observation |
| `http://hl7.org/fhir/v3/ActCode` | `TRSTASSUR` | trust assurance |
| `http://hl7.org/fhir/v3/ActCode` | `TRSTCERT` | trust certificate |
| `http://hl7.org/fhir/v3/ActCode` | `TRSTCERTOBS` | trust certificate observation |
| `http://hl7.org/fhir/v3/ActCode` | `TRSTFWK` | trust framework |
| `http://hl7.org/fhir/v3/ActCode` | `TRSTFWKOBS` | trust framework observation |
| `http://hl7.org/fhir/v3/ActCode` | `TRSTLOAOBS` | trust assurance observation |
| `http://hl7.org/fhir/v3/ActCode` | `TRSTMEC` | trust mechanism |
| `http://hl7.org/fhir/v3/ActCode` | `TRSTMECOBS` | trust mechanism observation |
| `http://hl7.org/fhir/v3/ActCode` | `UD` | Unit Dose |
| `http://hl7.org/fhir/v3/ActCode` | `UDE` | unit dose equivalent |
| `http://hl7.org/fhir/v3/ActCode` | `UFIL` | Ultrafiltration |
| `http://hl7.org/fhir/v3/ActCode` | `ULIFE` | universal life insurance policy |
| `http://hl7.org/fhir/v3/ActCode` | `UMBRL` | umbrella liability insurance policy |
| `http://hl7.org/fhir/v3/ActCode` | `UNINSMOT` | uninsured motorist policy |
| `http://hl7.org/fhir/v3/ActCode` | `UNITPRICE` | Unit Price |
| `http://hl7.org/fhir/v3/ActCode` | `UNITQTY` | Unit Quantity |
| `http://hl7.org/fhir/v3/ActCode` | `UNRELAT` | unrelated service |
| `http://hl7.org/fhir/v3/ActCode` | `UNSPSC` | United Nations Standard Products and Services Classification |
| `http://hl7.org/fhir/v3/ActCode` | `UPC` | Universal Product Code |
| `http://hl7.org/fhir/v3/ActCode` | `URGENT` | urgent |
| `http://hl7.org/fhir/v3/ActCode` | `USE` | notice of use |
| `http://hl7.org/fhir/v3/ActCode` | `V` | Visa |
| `http://hl7.org/fhir/v3/ActCode` | `VAC_PROBLEM` | vaccine product problem |
| `http://hl7.org/fhir/v3/ActCode` | `VALIDAT` | validation issue |
| `http://hl7.org/fhir/v3/ActCode` | `VECTRNS` | vector-borne transmission |
| `http://hl7.org/fhir/v3/ActCode` | `VERBAUTH` | verbal authorization |
| `http://hl7.org/fhir/v3/ActCode` | `VET` | veteran health program |
| `http://hl7.org/fhir/v3/ActCode` | `VFPAPER` | verify paper |
| `http://hl7.org/fhir/v3/ActCode` | `VISPOL` | vision care policy |
| `http://hl7.org/fhir/v3/ActCode` | `VLI` | low valin, leucin, isoleucin |
| `http://hl7.org/fhir/v3/ActCode` | `VOLUME` | ActSpecObsVolumeCode |
| `http://hl7.org/fhir/v3/ActCode` | `VR` | virtual |
| `http://hl7.org/fhir/v3/ActCode` | `VRXINV` | vision dispense invoice |
| `http://hl7.org/fhir/v3/ActCode` | `W` | Ward |
| `http://hl7.org/fhir/v3/ActCode` | `WATTRNS` | water-borne transmission |
| `http://hl7.org/fhir/v3/ActCode` | `WCBPOL` | worker's compensation |
| `http://hl7.org/fhir/v3/ActCode` | `WEEK` | week |
| `http://hl7.org/fhir/v3/ActCode` | `WELLREMLE` | wellness reminder list entry |
| `http://hl7.org/fhir/v3/ActCode` | `WELLREMLREV` | wellness reminder list review |
| `http://hl7.org/fhir/v3/ActCode` | `WGHT` |  |
| `http://hl7.org/fhir/v3/ActCode` | `WIATTCH` | work injury report attachment |
| `http://hl7.org/fhir/v3/ActCode` | `WORK2` | Work Interaction |
| `http://hl7.org/fhir/v3/ActCode` | `WPA` | Workplace accident |
| `http://hl7.org/fhir/v3/ActCode` | `WRKCOMP` | (workers compensation program |
| `http://hl7.org/fhir/v3/ActCode` | `X` | Container Unavailable |
| `http://hl7.org/fhir/v3/ActCode` | `XRAY` | x-ray |
| `http://hl7.org/fhir/v3/ActCode` | `YEAR` | year |
| `http://hl7.org/fhir/v3/ActCode` | `_ActPatientAnnotationType` | ActPatientAnnotationType |
| `http://hl7.org/fhir/v3/ActCode` | `_ImmunizationObservationType` | ImmunizationObservationType |
| `http://hl7.org/fhir/v3/ActCode` | `_ObservationQualityMeasureAttribute` | ObservationQualityMeasureAttribute |
| `http://hl7.org/fhir/v3/ActCode` | `_PatientImmunizationRelatedObservationType` | PatientImmunizationRelatedObservationType |
