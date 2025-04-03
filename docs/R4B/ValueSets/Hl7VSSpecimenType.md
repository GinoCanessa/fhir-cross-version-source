Comparison of 
Generated at Thursday, April 3, 2025 8:18:25 AM

### Hl7VSSpecimenType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | Hl7VSSpecimenType |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v2-0487` |
| Version | 2.0.0 |
| Description | Concepts that describe the precise nature of an entity that may be used as the source material for an observation.  This is one of two code systems that are used instead of table 0070 (code system xxxx) which conflated specimen types and specimen collection methods.   Used in Version 2 messaging in the SPM segment. |
| Status | `Active` |
| Has Escape Valve Code | `True` |
| Database Key | `4215` |
| Database Concept Count | `315` |
| Database Active Concept Count | `315` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Specimen` | `Specimen.type` | `http://terminology.hl7.org/ValueSet/v2-0487` | `Example` | Kind of material that forms the specimen |
| `http://hl7.org/fhir/StructureDefinition/SpecimenDefinition` | `SpecimenDefinition.typeCollected` | `http://terminology.hl7.org/ValueSet/v2-0487` | `Example` | Kind of material to collect |
| `http://hl7.org/fhir/StructureDefinition/SpecimenDefinition` | `SpecimenDefinition.typeTested.type` | `http://terminology.hl7.org/ValueSet/v2-0487` | `Example` | Type of intended specimen |
| `http://hl7.org/fhir/StructureDefinition/observation-specimenCode` | `Extension.value[x]` | `http://terminology.hl7.org/ValueSet/v2-0487` | `Example` | Value of extension |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v2-0487`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `...` | No suggested values |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ABS` | Abscess |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ACNE` | Tissue, Acne |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ACNFLD` | Fluid, Acne |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `AIRS` | Air Sample |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ALL` | Allograft |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `AMN` | Amniotic fluid |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `AMP` | Amputation |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ANGI` | Catheter Tip, Angio |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ARTC` | Catheter Tip, Arterial |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ASERU` | Serum, Acute |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ASP` | Aspirate |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ATTE` | Environment, Attest |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `AUTOA` | Environmental, Autoclave Ampule |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `AUTOC` | Environmental, Autoclave Capsule |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `AUTP` | Autopsy |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BBL` | Blood bag |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BCYST` | Cyst, Baker's |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BDY` | Whole body |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BIFL` | Bile Fluid |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BITE` | Bite |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BLD` | Whole blood |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BLDA` | Blood arterial |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BLDCO` | Cord blood |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BLDV` | Blood venous |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BLEB` | Bleb |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BLIST` | Blister |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BOIL` | Boil |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BON` | Bone |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BONE` | Bone |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BOWL` | Bowel contents |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BPH` | Basophils |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BPU` | Blood product unit |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BRN` | Burn |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BRSH` | Brush |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BRTH` | Breath (use EXHLD) |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BRUS` | Brushing |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BUB` | Bubo |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BULLA` | Bulla/Bullae |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `BX` | Biopsy |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CALC` | Calculus (=Stone) |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CARBU` | Carbuncle |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CAT` | Catheter |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CBITE` | Bite, Cat |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CDM` | Cardiac muscle |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CLIPP` | Clippings |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CNJT` | Conjunctiva |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CNL` | Cannula |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `COL` | Colostrum |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CONE` | Biospy, Cone |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CSCR` | Scratch, Cat |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CSERU` | Serum, Convalescent |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CSF` | Cerebral spinal fluid |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CSITE` | Catheter Insertion Site |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CSMY` | Fluid,  Cystostomy Tube |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CST` | Fluid, Cyst |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CSVR` | Blood, Cell Saver |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CTP` | Catheter tip |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CUR` | Curretage |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CVM` | Cervical Mucus |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CVPS` | Site, CVP |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CVPT` | Catheter Tip, CVP |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CYN` | Nodule, Cystic |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `CYST` | Cyst |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `DBITE` | Bite, Dog |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `DCS` | Sputum, Deep Cough |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `DEC` | Ulcer, Decubitus |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `DEION` | Environmental, Water  (Deionized) |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `DIA` | Dialysate |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `DIAF` | Dialysis Fluid |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `DISCHG` | Discharge |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `DIV` | Diverticulum |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `DRN` | Drain |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `DRNG` | Drainage, Tube |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `DRNGP` | Drainage, Penrose |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `DUFL` | Duodenal fluid |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `EARW` | Ear wax (cerumen) |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `EBRUSH` | Brush, Esophageal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `EEYE` | Environmental, Eye Wash |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `EFF` | Environmental, Effluent |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `EFFUS` | Effusion |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `EFOD` | Environmental, Food |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `EISO` | Environmental, Isolette |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ELT` | Electrode |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ENVIR` | Environmental, Unidentified Substance |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `EOS` | Eosinophils |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `EOTH` | Environmental, Other Substance |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ESOI` | Environmental, Soil |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ESOS` | Environmental, Solution (Sterile) |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ETA` | Aspirate,  Endotrach |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ETTP` | Catheter Tip, Endotracheal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ETTUB` | Tube, Endotracheal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `EWHI` | Environmental, Whirlpool |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `EXG` | Gas, exhaled (=breath) |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `EXS` | Shunt, External |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `EXUDTE` | Exudate |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `FAW` | Environmental, Water  (Well) |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `FBLOOD` | Blood, Fetal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `FGA` | Fluid,  Abdomen |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `FIB` | Fibroblasts |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `FIST` | Fistula |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `FLD` | Fluid, Other |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `FLT` | Filter |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `FLU` | Fluid, Body unsp |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `FLUID` | Fluid |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `FOLEY` | Catheter Tip, Foley |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `FRS` | Fluid, Respiratory |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `FSCLP` | Scalp, Fetal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `FUR` | Furuncle |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GAS` | Gas |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GASA` | Aspirate, Gastric |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GASAN` | Antrum, Gastric |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GASBR` | Brushing, Gastric |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GASD` | Drainage, Gastric |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GAST` | Fluid/contents, Gastric |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GENL` | Genital lochia |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GENV` | Genital vaginal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GRAFT` | Graft |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GRAFTS` | Graft Site |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GRANU` | Granuloma |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GROSH` | Catheter, Groshong |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GSOL` | Solution, Gastrostomy |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GSPEC` | Biopsy, Gastric |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GT` | Tube, Gastric |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `GTUBE` | Drainage Tube, Drainage (Gastrostomy) |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `HAR` | Hair |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `HBITE` | Bite, Human |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `HBLUD` | Blood, Autopsy |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `HEMAQ` | Catheter Tip, Hemaquit |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `HEMO` | Catheter Tip, Hemovac |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `HERNI` | Tissue, Herniated |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `HEV` | Drain, Hemovac |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `HIC` | Catheter, Hickman |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `HYDC` | Fluid, Hydrocele |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `IBITE` | Bite, Insect |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ICYST` | Cyst, Inclusion |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `IDC` | Catheter Tip, Indwelling |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `IHG` | Gas, Inhaled |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ILEO` | Drainage, Ileostomy |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ILLEG` | Source of Specimen Is Illegible |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `IMP` | Implant |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `INCI` | Site, Incision/Surgical |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `INFIL` | Infiltrate |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `INS` | Insect |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `INTRD` | Catheter Tip, Introducer |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ISLT` | Isolate |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `IT` | Intubation tube |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `IUD` | Intrauterine Device |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `IVCAT` | Catheter Tip, IV |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `IVFLD` | Fluid, IV |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `IVTIP` | Tubing Tip, IV |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `JEJU` | Drainage, Jejunal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `JNTFLD` | Fluid, Joint |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `JP` | Drainage, Jackson Pratt |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `KELOI` | Lavage |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `KIDFLD` | Fluid, Kidney |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `LAVG` | Lavage, Bronhial |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `LAVGG` | Lavage, Gastric |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `LAVGP` | Lavage, Peritoneal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `LAVPG` | Lavage, Pre-Bronch |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `LENS1` | Contact Lens |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `LENS2` | Contact Lens Case |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `LESN` | Lesion |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `LIQ` | Liquid, Unspecified |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `LIQO` | Liquid, Other |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `LNA` | Line arterial |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `LNV` | Line venous |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `LSAC` | Fluid, Lumbar Sac |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `LYM` | Lymphocytes |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `MAC` | Macrophages |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `MAHUR` | Catheter Tip, Makurkour |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `MAR` | Marrow |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `MASS` | Mass |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `MBLD` | Blood, Menstrual |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `MEC` | Meconium |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `MILK` | Breast milk |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `MLK` | Milk |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `MUCOS` | Mucosa |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `MUCUS` | Mucus |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `NAIL` | Nail |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `NASDR` | Drainage, Nasal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `NEDL` | Needle |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `NEPH` | Site, Nephrostomy |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `NGASP` | Aspirate, Nasogastric |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `NGAST` | Drainage, Nasogastric |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `NGS` | Site, Naso/Gastric |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `NODUL` | Nodule(s) |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `NSECR` | Secretion, Nasal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ORH` | Other |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `ORL` | Lesion, Oral |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `OTH` | Source, Other |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PACEM` | Pacemaker |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PAFL` | Pancreatic fluid |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PCFL` | Fluid, Pericardial |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PDSIT` | Site, Peritoneal Dialysis |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PDTS` | Site, Peritoneal Dialysis Tunnel |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PELVA` | Abscess, Pelvic |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PENIL` | Lesion, Penile |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PERIA` | Abscess, Perianal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PILOC` | Cyst, Pilonidal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PINS` | Site, Pin |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PIS` | Site, Pacemaker Insetion |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PLAN` | Plant Material |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PLAS` | Plasma |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PLB` | Plasma bag |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PLC` | Placenta |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PLEVS` | Serum, Peak Level |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PLR` | Pleural fluid (thoracentesis fluid) |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PMN` | Polymorphonuclear neutrophils |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PND` | Drainage, Penile |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `POL` | Polyps |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `POPGS` | Graft Site, Popliteal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `POPLG` | Graft, Popliteal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `POPLV` | Site, Popliteal Vein |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PORTA` | Catheter, Porta |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PPP` | Plasma, Platelet poor |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PROST` | Prosthetic Device |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PRP` | Plasma, Platelet rich |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PSC` | Pseudocyst |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PUNCT` | Wound, Puncture |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PUS` | Pus |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PUSFR` | Pustule |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `PUST` | Pus |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `QC3` | Quality Control |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `RANDU` | Urine, Random |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `RBC` | Erythrocytes |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `RBITE` | Bite, Reptile |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `RECT` | Drainage, Rectal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `RECTA` | Abscess, Rectal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `RENALC` | Cyst, Renal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `RENC` | Fluid, Renal Cyst |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `RES` | Respiratory |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SAL` | Saliva |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SCAR` | Tissue, Keloid (Scar) |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SCLV` | Catheter Tip, Subclavian |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SCROA` | Abscess, Scrotal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SECRE` | Secretion(s) |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SER` | Serum |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SHU` | Site, Shunt |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SHUNF` | Fluid, Shunt |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SHUNT` | Shunt |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SITE` | Site |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SKBP` | Biopsy, Skin |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SKN` | Skin |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SMM` | Mass, Sub-Mandibular |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SMN` | Seminal fluid |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SNV` | Fluid, synovial (Joint fluid) |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SPRM` | Spermatozoa |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SPRP` | Catheter Tip, Suprapubic |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SPRPB` | Cathether Tip, Suprapubic |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SPS` | Environmental, Spore Strip |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SPT` | Sputum |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SPTC` | Sputum - coughed |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SPTT` | Sputum - tracheal aspirate |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SPUT1` | Sputum, Simulated |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SPUTIN` | Sputum, Inducted |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SPUTSP` | Sputum, Spontaneous |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `STER` | Environmental, Sterrad |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `STL` | Stool = Fecal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `STONE` | Stone, Kidney |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SUBMA` | Abscess, Submandibular |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SUBMX` | Abscess, Submaxillary |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SUMP` | Drainage, Sump |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SUP` | Suprapubic Tap |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SUTUR` | Suture |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SWGZ` | Catheter Tip, Swan Gantz |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `SWT` | Sweat |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `TASP` | Aspirate, Tracheal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `TEAR` | Tears |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `THRB` | Thrombocyte (platelet) |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `TISS` | Tissue |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `TISU` | Tissue ulcer |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `TLC` | Cathether Tip, Triple Lumen |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `TRAC` | Site, Tracheostomy |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `TRANS` | Transudate |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `TSERU` | Serum, Trough |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `TSTES` | Abscess, Testicular |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `TTRA` | Aspirate, Transtracheal |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `TUBES` | Tubes |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `TUMOR` | Tumor |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `TZANC` | Smear, Tzanck |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `UDENT` | Source, Unidentified |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `UMED` | Unknown Medicine |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `UR` | Urine |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `URC` | Urine clean catch |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `URINB` | Urine, Bladder Washings |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `URINC` | Urine, Catheterized |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `URINM` | Urine, Midstream |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `URINN` | Urine, Nephrostomy |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `URINP` | Urine, Pedibag |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `URNS` | Urine sediment |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `URT` | Urine catheter |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `USCOP` | Urine, Cystoscopy |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `USPEC` | Source, Unspecified |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `USUB` | Unkown substance |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `VASTIP` | Catheter Tip, Vas |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `VENT` | Catheter Tip, Ventricular |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `VITF` | Vitreous Fluid |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `VOM` | Vomitus |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WASH` | Wash |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WASI` | Washing, e.g. bronchial washing |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WAT` | Water |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WB` | Blood, Whole |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WBC` | Leukocytes |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WEN` | Wen |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WICK` | Wick |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WND` | Wound |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WNDA` | Wound abscess |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WNDD` | Wound drainage |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WNDE` | Wound exudate |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WORM` | Worm |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WRT` | Wart |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WWA` | Environmental, Water |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WWO` | Environmental, Water (Ocean) |
| `http://terminology.hl7.org/CodeSystem/v2-0487` | `WWT` | Environmental, Water  (Tap) |
