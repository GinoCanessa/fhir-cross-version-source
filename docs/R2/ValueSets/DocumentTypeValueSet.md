Comparison of 
Generated at Thursday, April 3, 2025 8:18:06 AM

### Document Type Value Set

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Document Type Value Set |
| Canonical URL | `http://hl7.org/fhir/ValueSet/c80-doc-typecodes` |
| Version | 20091109 |
| Description | This is the code specifying the precise type of document (e.g. Pulmonary History and  Physical, Discharge Summary, Ultrasound Report, etc.). The Document Type value set includes all LOINC  values listed in HITSP C80 Table 2-144 Document Class Value Set Definition above used for Document Class,  and all LOINC values whose SCALE is DOC in the LOINC database. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `39` |
| Database Concept Count | `6401` |
| Database Active Concept Count | `6401` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DocumentManifest` | `DocumentManifest.type` | `http://hl7.org/fhir/ValueSet/c80-doc-typecodes` | `Preferred` | Kind of document set |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.type` | `http://hl7.org/fhir/ValueSet/c80-doc-typecodes` | `Preferred` | Kind of document (LOINC if possible) |

### Referenced Systems

* `http://loinc.org`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://loinc.org` | `11206-0` | 18-Hydroxydeoxycorticosterone [Mass/volume] in Serum or Plasma |
| `http://loinc.org` | `11485-0` | Anesthesia records |
| `http://loinc.org` | `11486-8` | Chemotherapy records |
| `http://loinc.org` | `11488-4` | Consult note |
| `http://loinc.org` | `11490-0` | Physician Discharge summary |
| `http://loinc.org` | `11492-6` | Provider-unspecifed, History and physical note |
| `http://loinc.org` | `11494-2` | Physician Initial assessment note at First encounter |
| `http://loinc.org` | `11495-9` | Physical therapy Initial assessment note at First encounter |
| `http://loinc.org` | `11496-7` | Podiatry Initial assessment note at First encounter |
| `http://loinc.org` | `11497-5` | Psychology Initial assessment note at First encounter |
| `http://loinc.org` | `11498-3` | Social work Initial assessment note at First encounter |
| `http://loinc.org` | `11500-6` | Occupational therapy Initial assessment note at First encounter |
| `http://loinc.org` | `11502-2` | Laboratory report |
| `http://loinc.org` | `11503-0` | Medical records |
| `http://loinc.org` | `11504-8` | Provider-unspecified Operation note |
| `http://loinc.org` | `11505-5` | Physician procedure note |
| `http://loinc.org` | `11506-3` | Provider-unspecified Progress note |
| `http://loinc.org` | `11507-1` | Occupational therapy Progress note |
| `http://loinc.org` | `11508-9` | Physical therapy Progress note |
| `http://loinc.org` | `11509-7` | Podiatry Progress note |
| `http://loinc.org` | `11510-5` | Psychology Progress note |
| `http://loinc.org` | `11512-1` | Speech-language pathology Progress note |
| `http://loinc.org` | `11514-7` | Chiropractic Records total Encounter |
| `http://loinc.org` | `11515-4` | Physical therapy Records total Encounter |
| `http://loinc.org` | `11516-2` | Physician Records total Encounter |
| `http://loinc.org` | `11517-0` | Podiatry Records total Encounter |
| `http://loinc.org` | `11518-8` | Psychology Records total Encounter |
| `http://loinc.org` | `11519-6` | Social service Records total Encounter |
| `http://loinc.org` | `11520-4` | Speech therapy Records total Encounter |
| `http://loinc.org` | `11521-2` | Occupational therapy Records total Encounter |
| `http://loinc.org` | `11523-8` | EEG study |
| `http://loinc.org` | `11524-6` | EKG study |
| `http://loinc.org` | `11525-3` | US Pelvis and Fetus for pregnancy |
| `http://loinc.org` | `11526-1` | Pathology study |
| `http://loinc.org` | `11527-9` | Psychiatry study |
| `http://loinc.org` | `11529-5` | Surgical pathology study |
| `http://loinc.org` | `11534-5` | Temperature charts |
| `http://loinc.org` | `11536-0` | Nurse Notes |
| `http://loinc.org` | `11541-0` | MRI Brain study |
| `http://loinc.org` | `11543-6` | Nursery records |
| `http://loinc.org` | `13480-9` | 18-Hydroxydeoxycortisol/Creatinine [Mass Ratio] in Urine |
| `http://loinc.org` | `15507-7` | Provider-unspecified ED Progress note |
| `http://loinc.org` | `15508-5` | Labor and delivery records |
| `http://loinc.org` | `16110-9` | 11-Deoxycorticosterone [Mass/time] in 24 hour Urine |
| `http://loinc.org` | `16294-1` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --post XXX challenge |
| `http://loinc.org` | `1656-8` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma |
| `http://loinc.org` | `17787-3` | Thyroid Scan Study report |
| `http://loinc.org` | `18594-2` | Psychiatric service attachment |
| `http://loinc.org` | `18733-6` | Physician attending Progress note |
| `http://loinc.org` | `18734-4` | Occupational therapy Initial assessment note |
| `http://loinc.org` | `18735-1` | Physical therapy Initial assessment note |
| `http://loinc.org` | `18736-9` | Physician Initial assessment note |
| `http://loinc.org` | `18737-7` | Podiatry Initial assessment note |
| `http://loinc.org` | `18738-5` | Psychology Initial assessment note |
| `http://loinc.org` | `18739-3` | Social work Initial assessment note |
| `http://loinc.org` | `18740-1` | Speech-language pathology Initial assessment note |
| `http://loinc.org` | `18742-7` | Arthroscopy study |
| `http://loinc.org` | `18743-5` | Autopsy report |
| `http://loinc.org` | `18744-3` | Bronchoscopy study |
| `http://loinc.org` | `18745-0` | Cardiac catheterization study |
| `http://loinc.org` | `18746-8` | Colonoscopy study |
| `http://loinc.org` | `18748-4` | Diagnostic imaging study |
| `http://loinc.org` | `18749-2` | Electromyogram study |
| `http://loinc.org` | `18750-0` | Electrophysiology study |
| `http://loinc.org` | `18751-8` | Endoscopy study |
| `http://loinc.org` | `18752-6` | Exercise stress test study |
| `http://loinc.org` | `18753-4` | Flexible sigmoidoscopy study |
| `http://loinc.org` | `18754-2` | Holter monitor study |
| `http://loinc.org` | `18756-7` | MRI Spine study |
| `http://loinc.org` | `18759-1` | Spirometry study |
| `http://loinc.org` | `18761-7` | Provider-unspecified Transfer summary |
| `http://loinc.org` | `18763-3` | Physician consulting Initial assessment note |
| `http://loinc.org` | `18823-5` | Alcohol and/or substance abuse service attachment |
| `http://loinc.org` | `18824-3` | Cardiac service attachment |
| `http://loinc.org` | `18825-0` | Medical social services attachment |
| `http://loinc.org` | `18826-8` | Occupational therapy service attachment |
| `http://loinc.org` | `18836-7` | Cardiac stress study Procedure |
| `http://loinc.org` | `18841-7` | Hospital consultations Document |
| `http://loinc.org` | `18842-5` | Discharge summary |
| `http://loinc.org` | `19002-5` | Physical therapy service attachment |
| `http://loinc.org` | `19003-3` | Respiratory therapy service attachment |
| `http://loinc.org` | `19004-1` | Skilled nursing service attachment |
| `http://loinc.org` | `21862-8` | Source of document used to abstract Cancer |
| `http://loinc.org` | `24531-6` | Abdomen retroperitoneum US |
| `http://loinc.org` | `24532-4` | Abdomen RUQ US |
| `http://loinc.org` | `24533-2` | Abdominal vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `24534-0` | Abdominal vessels US.doppler |
| `http://loinc.org` | `24535-7` | Acetabulum X-ray |
| `http://loinc.org` | `24536-5` | Acromioclavicular Joint X-ray |
| `http://loinc.org` | `24537-3` | US Guidance for removal of amniotic fluid from Uterus |
| `http://loinc.org` | `24538-1` | Ankle MRI |
| `http://loinc.org` | `24539-9` | Ankle MRI W and WO contrast IV |
| `http://loinc.org` | `24540-7` | Ankle X-ray 2 views |
| `http://loinc.org` | `24541-5` | Ankle X-ray |
| `http://loinc.org` | `24542-3` | Anus US |
| `http://loinc.org` | `24543-1` | Aorta Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `24544-9` | Aorta thoracic CT |
| `http://loinc.org` | `24545-6` | Aorta thoracic CT W contrast IV |
| `http://loinc.org` | `24546-4` | Aorta arch and Neck Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `24547-2` | Aorta US |
| `http://loinc.org` | `24548-0` | Appendix US |
| `http://loinc.org` | `24549-8` | Upper extremity vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `24550-6` | Upper extremity veins Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `24551-4` | AV fistula Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `24552-2` | Stent Fluoroscopy W contrast intra stent |
| `http://loinc.org` | `24553-0` | Vessel intracranial Fluoroscopic angiogram Embolectomy W contrast IV |
| `http://loinc.org` | `24554-8` | Artery Fluoroscopic angiogram Embolization W contrast IA |
| `http://loinc.org` | `24555-5` | Fluoroscopic angiogram Guidance for placement of stent in Artery |
| `http://loinc.org` | `24556-3` | Abdomen MRI |
| `http://loinc.org` | `24557-1` | Abdomen MRI W and WO contrast IV |
| `http://loinc.org` | `24558-9` | Abdomen US |
| `http://loinc.org` | `24559-7` | US Guidance for removal of fluid from Abdomen |
| `http://loinc.org` | `24560-5` | Abdomen X-ray AP left lateral-decubitus portable |
| `http://loinc.org` | `24561-3` | Abdomen X-ray AP left lateral-decubitus |
| `http://loinc.org` | `24562-1` | Abdomen X-ray AP (left lateral-decubitus and right lateral-decubitus) |
| `http://loinc.org` | `24563-9` | Abdomen X-ray AP right lateral-decubitus |
| `http://loinc.org` | `24564-7` | Abdomen X-ray AP upright portable |
| `http://loinc.org` | `24566-2` | Abdomen retroperitoneum CT |
| `http://loinc.org` | `24567-0` | Abdomen retroperitoneum CT W contrast |
| `http://loinc.org` | `24568-8` | AV fistula Fluoroscopic angiogram Atherectomy W contrast IV |
| `http://loinc.org` | `24569-6` | AV shunt Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `24570-4` | Fluoroscopy Guidance for stone removal of Biliary duct common-- W contrast intra biliary duct |
| `http://loinc.org` | `24571-2` | Biliary ducts and Gallbladder Scan for patency of biliary structures and ejection fraction W sincalide and W radionuclide IV |
| `http://loinc.org` | `24572-0` | Biliary ducts and Gallbladder Scan for patency of biliary structures W Tc-99m IV |
| `http://loinc.org` | `24573-8` | Biliary ducts and Gallbladder X-ray W contrast IV |
| `http://loinc.org` | `24574-6` | Biliary ducts and Gallbladder Fluoroscopy during surgery W contrast biliary duct |
| `http://loinc.org` | `24575-3` | Biliary ducts and Gallbladder Fluoroscopy W contrast percutaneous transhepatic |
| `http://loinc.org` | `24576-1` | Urinary bladder arteries Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `24577-9` | Bone X-ray during surgery |
| `http://loinc.org` | `24578-7` | Bones SPECT |
| `http://loinc.org` | `24579-5` | Bones long X-ray survey |
| `http://loinc.org` | `24580-3` | Brachiocephalic artery Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `24581-1` | Brachial artery and Subclavian artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `24582-9` | Thoracic outlet MRI |
| `http://loinc.org` | `24583-7` | Thoracic outlet MRI W and WO contrast IV |
| `http://loinc.org` | `24584-5` | Thoracic outlet vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `24585-2` | CT Guidance.stereotactic for biopsy of Head-- W contrast IV |
| `http://loinc.org` | `24586-0` | Brain MRI W anesthesia |
| `http://loinc.org` | `24587-8` | Brain MRI W and WO contrast IV |
| `http://loinc.org` | `24588-6` | Brain MRI W and WO contrast IV and W anesthesia |
| `http://loinc.org` | `24589-4` | Brain MRI W contrast IV |
| `http://loinc.org` | `24590-2` | Brain MRI |
| `http://loinc.org` | `24591-0` | Brain Scan brain death protocol W Tc-99m HMPAO IV |
| `http://loinc.org` | `24593-6` | Head vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `24594-4` | Mammogram Guidance for aspiration of cyst of Breast |
| `http://loinc.org` | `24595-1` | Mammogram Guidance for needle localization of mass of Breast |
| `http://loinc.org` | `24596-9` | Breast specimen US |
| `http://loinc.org` | `24597-7` | Breast specimen Mammogram |
| `http://loinc.org` | `24598-5` | Mammogram Guidance for aspiration of Breast |
| `http://loinc.org` | `24599-3` | Breast US limited |
| `http://loinc.org` | `24600-9` | US Guidance for needle localization of Breast |
| `http://loinc.org` | `24601-7` | Breast US |
| `http://loinc.org` | `24602-5` | Mammogram Guidance for biopsy of Breast |
| `http://loinc.org` | `24603-3` | Mammogram Guidance.stereotactic for biopsy of Breast |
| `http://loinc.org` | `24604-1` | Breast Mammogram diagnostic limited |
| `http://loinc.org` | `24605-8` | Breast Mammogram diagnostic |
| `http://loinc.org` | `24606-6` | Breast Mammogram screening |
| `http://loinc.org` | `24609-0` | Mammogram Guidance for core needle percutaneous biopsy of Breast |
| `http://loinc.org` | `24610-8` | Breast Mammogram limited |
| `http://loinc.org` | `24611-6` | Outpatient Consultation 2nd opinion |
| `http://loinc.org` | `24612-4` | Calcaneus X-ray |
| `http://loinc.org` | `24613-2` | Fluoroscopic angiogram Guidance for placement of catheter in artery in Central cardiovascular artery |
| `http://loinc.org` | `24614-0` | Carotid artery extracranial Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `24615-7` | Carotid artery intracranial Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `24616-5` | Carotid artery US |
| `http://loinc.org` | `24617-3` | Carotid artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `24619-9` | Wrist X-ray |
| `http://loinc.org` | `24620-7` | Catheter Fluoroscopy Patency check W contrast via catheter |
| `http://loinc.org` | `24621-5` | Fluoroscopy Guidance for percutaneous drainage of Cavity |
| `http://loinc.org` | `24622-3` | Celiac artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `24623-1` | CT Guidance for anesthetic block injection of Celiac plexus |
| `http://loinc.org` | `24624-9` | Fluoroscopic angiogram Guidance for change of central catheter in Central vein-- W contrast IV |
| `http://loinc.org` | `24625-6` | Fluoroscopic angiogram Guidance for placement of catheter in Central vein-- W contrast IV |
| `http://loinc.org` | `24626-4` | Fluoroscopic angiogram Guidance for reposition of catheter in Central vein-- W contrast IV |
| `http://loinc.org` | `24627-2` | Chest CT |
| `http://loinc.org` | `24628-0` | Chest CT W contrast IV |
| `http://loinc.org` | `24629-8` | Chest MRI |
| `http://loinc.org` | `24630-6` | Chest US |
| `http://loinc.org` | `24631-4` | Unspecified body region Fluoroscopy Central vein catheter placement check |
| `http://loinc.org` | `24632-2` | Chest X-ray AP portable |
| `http://loinc.org` | `24634-8` | Chest X-ray portable W inspiration and expiration |
| `http://loinc.org` | `24635-5` | Chest X-ray PA upright W inspiration and expiration |
| `http://loinc.org` | `24636-3` | Chest X-ray AP left lateral-decubitus portable |
| `http://loinc.org` | `24637-1` | Chest X-ray AP left lateral-decubitus |
| `http://loinc.org` | `24638-9` | Chest X-ray left lateral upright portable |
| `http://loinc.org` | `24639-7` | Chest X-ray left lateral upright |
| `http://loinc.org` | `24640-5` | Chest X-ray lordotic |
| `http://loinc.org` | `24641-3` | Chest X-ray left oblique portable |
| `http://loinc.org` | `24642-1` | Chest X-ray AP and PA upright |
| `http://loinc.org` | `24643-9` | Chest X-ray PA and lateral and right or-left oblique upright |
| `http://loinc.org` | `24644-7` | Chest X-ray PA and lateral upright portable |
| `http://loinc.org` | `24645-4` | Chest X-ray PA and right lateral and right oblique and left oblique upright portable |
| `http://loinc.org` | `24646-2` | Chest X-ray PA and right lateral and right oblique and left oblique upright |
| `http://loinc.org` | `24647-0` | Chest X-ray PA and lateral upright |
| `http://loinc.org` | `24648-8` | Chest X-ray PA upright |
| `http://loinc.org` | `24649-6` | Chest X-ray AP (right lateral-decubitus and left lateral-decubitus) portable |
| `http://loinc.org` | `24650-4` | Chest X-ray AP (right lateral-decubitus and left lateral-decubitus) |
| `http://loinc.org` | `24651-2` | Chest X-ray right oblique and left oblique upright |
| `http://loinc.org` | `24652-0` | Chest X-ray AP right lateral-decubitus portable |
| `http://loinc.org` | `24653-8` | Chest X-ray AP and AP right lateral-decubitus |
| `http://loinc.org` | `24654-6` | Chest X-ray AP and AP right lateral-decubitus portable |
| `http://loinc.org` | `24655-3` | Chest Fluoroscopy Image intensifier during surgery |
| `http://loinc.org` | `24656-1` | Chest Fluoroscopy during surgery |
| `http://loinc.org` | `24657-9` | Chest X-ray tomograph |
| `http://loinc.org` | `24658-7` | Aorta Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `24659-5` | Chest vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `24660-3` | Aorta thoracic MRI angiogram |
| `http://loinc.org` | `24661-1` | Pleural space Fluoroscopy W contrast intra pleural space |
| `http://loinc.org` | `24662-9` | US Guidance for aspiration of Pleural space |
| `http://loinc.org` | `24663-7` | Head Cistern Scan W radionuclide IT |
| `http://loinc.org` | `24664-5` | Clavicle X-ray |
| `http://loinc.org` | `24665-2` | Sacrum and Coccyx X-ray |
| `http://loinc.org` | `24666-0` | Colon Fluoroscopy W air and barium contrast PR |
| `http://loinc.org` | `24667-8` | Colon Fluoroscopy W contrast PR |
| `http://loinc.org` | `24668-6` | Colon Fluoroscopy transit Post solid contrast |
| `http://loinc.org` | `24669-4` | Colon Fluoroscopy W water soluble contrast PR |
| `http://loinc.org` | `24670-2` | US Guidance for biopsy of cyst of Unspecified body region |
| `http://loinc.org` | `24671-0` | Fluoroscopy Guidance for aspiration of cyst of Unspecified body region |
| `http://loinc.org` | `24672-8` | Diaphragm US Motion |
| `http://loinc.org` | `24673-6` | Duodenum Fluoroscopy W contrast PO and hypotonic agent per ng |
| `http://loinc.org` | `24674-4` | Elbow MRI |
| `http://loinc.org` | `24675-1` | Elbow MRI W and WO contrast IV |
| `http://loinc.org` | `24676-9` | Elbow X-ray |
| `http://loinc.org` | `24677-7` | Pelvis US transvaginal |
| `http://loinc.org` | `24678-5` | Esophagus Fluoroscopy W contrast PO |
| `http://loinc.org` | `24679-3` | Esophagus Fluoroscopy W gastrografin PO |
| `http://loinc.org` | `24680-1` | Fluoroscopy Guidance for dilation of Esophagus |
| `http://loinc.org` | `24681-9` | Esophagus and Hypopharynx Fluoroscopy video W contrast PO during swallowing |
| `http://loinc.org` | `24682-7` | Esophagus and Hypopharynx Fluoroscopy video W liquid and paste contrast PO during swallowing |
| `http://loinc.org` | `24683-5` | Esophagus and Stomach Scan W Tc-99m SC PO |
| `http://loinc.org` | `24684-3` | Extracranial vessels Fluoroscopic angiogram Embolectomy W contrast IA |
| `http://loinc.org` | `24685-0` | Peripheral veins Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `24686-8` | Lower extremity X-ray |
| `http://loinc.org` | `24687-6` | Lower Extremity Joint MRI |
| `http://loinc.org` | `24688-4` | Upper extremity MRI |
| `http://loinc.org` | `24689-2` | Upper extremity X-ray |
| `http://loinc.org` | `24690-0` | Extremity CT |
| `http://loinc.org` | `24691-8` | Extremity CT W contrast IV |
| `http://loinc.org` | `24692-6` | US Guidance for drainage of Extremity |
| `http://loinc.org` | `24693-4` | Extremity US |
| `http://loinc.org` | `24694-2` | Face MRI W and WO contrast IV |
| `http://loinc.org` | `24695-9` | Facial bones X-ray |
| `http://loinc.org` | `24696-7` | Facial bones and Sinuses CT |
| `http://loinc.org` | `24697-5` | Facial bones and Sinuses CT W contrast IV |
| `http://loinc.org` | `24698-3` | Femoral artery Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `24699-1` | Femoral artery Fluoroscopic angiogram runoff W contrast IA |
| `http://loinc.org` | `24700-7` | Femur and Tibia X-ray for leg length |
| `http://loinc.org` | `24702-3` | Thigh MRI |
| `http://loinc.org` | `24703-1` | Thigh MRI W and WO contrast IV |
| `http://loinc.org` | `24704-9` | Femur X-ray |
| `http://loinc.org` | `24705-6` | Finger MRI |
| `http://loinc.org` | `24706-4` | Finger X-ray |
| `http://loinc.org` | `24707-2` | Foot MRI |
| `http://loinc.org` | `24708-0` | Foot X-ray standing |
| `http://loinc.org` | `24709-8` | Foot X-ray |
| `http://loinc.org` | `24710-6` | Forearm MRI |
| `http://loinc.org` | `24711-4` | Gallbladder US |
| `http://loinc.org` | `24712-2` | Gallbladder X-ray W contrast PO |
| `http://loinc.org` | `24713-0` | Gallbladder X-ray 48 hours post contrast PO |
| `http://loinc.org` | `24714-8` | Gastrointestine Scan W Tc-99m tagged RBC IV |
| `http://loinc.org` | `24715-5` | Gastrointestine upper Fluoroscopy Single view W contrast PO |
| `http://loinc.org` | `24716-3` | Fluoroscopy Guidance for placement of decompression tube in Gastrointestine |
| `http://loinc.org` | `24717-1` | Ileal conduit X-ray Loopogram |
| `http://loinc.org` | `24718-9` | Fluoroscopy Guidance for transjugular biopsy of Liver-- W contrast IV |
| `http://loinc.org` | `24719-7` | Groin US |
| `http://loinc.org` | `24720-5` | Hand MRI |
| `http://loinc.org` | `24721-3` | Hand X-ray 2 views |
| `http://loinc.org` | `24722-1` | Hand X-ray 3 views |
| `http://loinc.org` | `24723-9` | Hand X-ray arthritis |
| `http://loinc.org` | `24724-7` | Wrist and Hand X-ray bone age |
| `http://loinc.org` | `24725-4` | Head CT |
| `http://loinc.org` | `24726-2` | Head CT W and WO contrast IV |
| `http://loinc.org` | `24727-0` | Head CT W contrast IV |
| `http://loinc.org` | `24728-8` | Head CT cine |
| `http://loinc.org` | `24729-6` | Head CT cine W and WO contrast IV |
| `http://loinc.org` | `24730-4` | Brain Scan |
| `http://loinc.org` | `24731-2` | Head US |
| `http://loinc.org` | `24732-0` | Head US during surgery |
| `http://loinc.org` | `24733-8` | Head vessels US.doppler |
| `http://loinc.org` | `24734-6` | Head Cistern CT W contrast IT |
| `http://loinc.org` | `24735-3` | Internal auditory canal and Posterior fossa MRI |
| `http://loinc.org` | `24740-3` | Internal auditory canal and Posterior fossa MRI W and WO contrast IV |
| `http://loinc.org` | `24745-2` | Petrous bone X-ray |
| `http://loinc.org` | `24746-0` | Head Sagittal Sinus MRI |
| `http://loinc.org` | `24747-8` | Head Sagittal Sinus MRI angiogram W contrast IV |
| `http://loinc.org` | `24748-6` | Heart MRI |
| `http://loinc.org` | `24750-2` | Heart Scan at rest and W Tl-201 IV |
| `http://loinc.org` | `24751-0` | Parathyroid Scan W TI-201 subtraction Tc-99m IV |
| `http://loinc.org` | `24752-8` | Heart Fluoroscopy video |
| `http://loinc.org` | `24753-6` | Unspecified body region CT W contrast IV |
| `http://loinc.org` | `24754-4` | Administration of vasodilator into catheter of Vein |
| `http://loinc.org` | `24755-1` | Fluoroscopic angiogram Guidance for atherectomy of Vein-- W contrast IV |
| `http://loinc.org` | `24756-9` | Fluoroscopic angiogram Guidance for placement of stent in Vein |
| `http://loinc.org` | `24757-7` | Coronary arteries CT fast |
| `http://loinc.org` | `24760-1` | Hip US |
| `http://loinc.org` | `24761-9` | Hip X-ray Single view |
| `http://loinc.org` | `24762-7` | Hip X-ray |
| `http://loinc.org` | `24764-3` | Hip Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `24765-0` | Humerus X-ray 2 views |
| `http://loinc.org` | `24766-8` | Iliac artery Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `24767-6` | Internal auditory canal X-ray tomograph |
| `http://loinc.org` | `24769-2` | CT Guidance for injection of Joint space |
| `http://loinc.org` | `24770-0` | Joint Scan W In-111 intrajoint |
| `http://loinc.org` | `24771-8` | Fluoroscopy Guidance for aspiration of Joint space |
| `http://loinc.org` | `24772-6` | US Guidance for biopsy of Kidney |
| `http://loinc.org` | `24773-4` | Kidney - bilateral Scan W radionuclide transplant scan |
| `http://loinc.org` | `24776-7` | Kidney - bilateral Scan |
| `http://loinc.org` | `24778-3` | Kidney - bilateral X-ray 3 views serial W and WO contrast IV |
| `http://loinc.org` | `24779-1` | Fluoroscopy Guidance for placement of percutaneous nephrostomy in Kidney - bilateral-- W contrast via tube |
| `http://loinc.org` | `24780-9` | Kidney - bilateral Fluoroscopy W contrast via nephrostomy tube |
| `http://loinc.org` | `24781-7` | Fluoroscopy Guidance for change of percutaneous nephrostomy tube in Kidney - bilateral-- W contrast |
| `http://loinc.org` | `24782-5` | Fluoroscopy Guidance for placement of percutaneous nephroureteral stent in Kidney - bilateral |
| `http://loinc.org` | `24783-3` | Kidney - bilateral Fluoroscopy Urodynamics |
| `http://loinc.org` | `24784-1` | Kidney - bilateral X-ray tomograph W and WO contrast IV |
| `http://loinc.org` | `24787-4` | Kidney - bilateral X-ray tomograph WO contrast and 10M post contrast IV |
| `http://loinc.org` | `24788-2` | Kidney - bilateral X-ray W contrast IV |
| `http://loinc.org` | `24789-0` | Kidney - bilateral X-ray tomograph |
| `http://loinc.org` | `24790-8` | Kidney - bilateral X-ray tomograph W contrast IV |
| `http://loinc.org` | `24792-4` | Abdomen X-ray AP and AP left lateral-decubitus portable |
| `http://loinc.org` | `24793-2` | Abdomen X-ray AP and lateral portable |
| `http://loinc.org` | `24794-0` | Abdomen X-ray AP and lateral |
| `http://loinc.org` | `24795-7` | Abdomen X-ray AP (supine and upright) portable |
| `http://loinc.org` | `24796-5` | Abdomen X-ray AP and AP left lateral-decubitus |
| `http://loinc.org` | `24797-3` | Abdomen X-ray AP and oblique prone |
| `http://loinc.org` | `24798-1` | Abdomen X-ray AP (supine and upright) |
| `http://loinc.org` | `24799-9` | Abdomen X-ray AP single view |
| `http://loinc.org` | `24800-5` | Knee Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `24801-3` | Knee X-ray Merchants |
| `http://loinc.org` | `24802-1` | Knee MRI |
| `http://loinc.org` | `24803-9` | Knee MRI W and WO contrast IV |
| `http://loinc.org` | `24804-7` | Knee Scan |
| `http://loinc.org` | `24805-4` | Knee X-ray AP and lateral standing |
| `http://loinc.org` | `24806-2` | Knee X-ray 2 views |
| `http://loinc.org` | `24807-0` | Knee X-ray AP single view standing |
| `http://loinc.org` | `24808-8` | Knee X-ray AP and PA standing |
| `http://loinc.org` | `24809-6` | Knee X-ray standing |
| `http://loinc.org` | `24811-2` | CT Guidance for aspiration of Liver |
| `http://loinc.org` | `24812-0` | CT Guidance for biopsy of Liver |
| `http://loinc.org` | `24813-8` | CT Guidance for core needle biopsy of Liver |
| `http://loinc.org` | `24814-6` | Liver CT |
| `http://loinc.org` | `24815-3` | Liver CT W contrast IV |
| `http://loinc.org` | `24816-1` | US Guidance for biopsy of Liver |
| `http://loinc.org` | `24817-9` | Liver SPECT W Tc-99m IV |
| `http://loinc.org` | `24818-7` | Liver and Diaphragm US |
| `http://loinc.org` | `24819-5` | Liver and Spleen Scan W Tc-99m calcium colloid IV |
| `http://loinc.org` | `24820-3` | Lower leg vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `24821-1` | Lower leg MRI |
| `http://loinc.org` | `24822-9` | CT Guidance for aspiration of Lung |
| `http://loinc.org` | `24823-7` | CT Guidance for biopsy of Lung |
| `http://loinc.org` | `24824-5` | Lung Scan portable |
| `http://loinc.org` | `24825-2` | Lung X-ray W contrast intrabronchial |
| `http://loinc.org` | `24826-0` | Lymphatics Scan W radionuclide intra lymphatic |
| `http://loinc.org` | `24827-8` | Lymphatics Fluoroscopy W contrast intra lymphatic |
| `http://loinc.org` | `24828-6` | Mandible X-ray panorex |
| `http://loinc.org` | `24829-4` | Mandible X-ray |
| `http://loinc.org` | `24830-2` | Mastoid X-ray |
| `http://loinc.org` | `24831-0` | Meckels diverticulum Scan W Tc-99m M04 IV |
| `http://loinc.org` | `24832-8` | Mesenteric artery Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `24833-6` | Mesenteric artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `24834-4` | Nasal bones X-ray |
| `http://loinc.org` | `24835-1` | Nasopharynx and Neck CT |
| `http://loinc.org` | `24836-9` | Nasopharynx and Neck CT W contrast IV |
| `http://loinc.org` | `24837-7` | CT Guidance for aspiration of Neck |
| `http://loinc.org` | `24838-5` | CT Guidance for biopsy of Neck |
| `http://loinc.org` | `24839-3` | Neck MRI |
| `http://loinc.org` | `24840-1` | Neck MRI W and WO contrast IV |
| `http://loinc.org` | `24841-9` | Neck MRI W contrast IV |
| `http://loinc.org` | `24842-7` | Neck US |
| `http://loinc.org` | `24843-5` | Neck X-ray lateral |
| `http://loinc.org` | `24844-3` | Neck vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `24845-0` | Neck Fluoroscopy W contrast intra larynx |
| `http://loinc.org` | `24846-8` | Optic foramen X-ray |
| `http://loinc.org` | `24848-4` | Orbit - bilateral CT |
| `http://loinc.org` | `24849-2` | Orbit - bilateral CT W and WO contrast IV |
| `http://loinc.org` | `24850-0` | Orbit - bilateral CT W contrast IV |
| `http://loinc.org` | `24851-8` | Orbit - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `24852-6` | Orbit - bilateral MRI W contrast IV |
| `http://loinc.org` | `24853-4` | Eye+Orbit - bilateral US |
| `http://loinc.org` | `24854-2` | Orbit - bilateral X-ray |
| `http://loinc.org` | `24855-9` | Oropharynx Fluoroscopy video |
| `http://loinc.org` | `24856-7` | CT Guidance for aspiration of Pancreas |
| `http://loinc.org` | `24857-5` | Pancreas CT |
| `http://loinc.org` | `24858-3` | Pancreas CT W contrast IV |
| `http://loinc.org` | `24859-1` | Pancreas US |
| `http://loinc.org` | `24860-9` | Pancreatic artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `24861-7` | Patella X-ray 2 views |
| `http://loinc.org` | `24862-5` | Iliac artery Internal Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `24863-3` | CT Guidance for aspiration of Pelvis |
| `http://loinc.org` | `24864-1` | CT Guidance for biopsy of Pelvis |
| `http://loinc.org` | `24865-8` | Pelvis CT |
| `http://loinc.org` | `24866-6` | Pelvis CT W contrast IV |
| `http://loinc.org` | `24867-4` | Pelvis MRI |
| `http://loinc.org` | `24868-2` | US Guidance for drainage of Pelvis |
| `http://loinc.org` | `24869-0` | Pelvis US |
| `http://loinc.org` | `24870-8` | Pelvis vessels US.doppler |
| `http://loinc.org` | `24871-6` | Pelvis X-ray pelvimetry |
| `http://loinc.org` | `24872-4` | Pelvis and Hip MRI |
| `http://loinc.org` | `24873-2` | Pelvis vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `24874-0` | Peripheral arteries Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `24875-7` | Peripheral vessel US.doppler Peripheral plane |
| `http://loinc.org` | `24876-5` | Peritoneovenous shunt Scan for patency W Tc-99m DTPA IT |
| `http://loinc.org` | `24877-3` | Petrous bone CT |
| `http://loinc.org` | `24878-1` | Petrous bone CT W contrast IV |
| `http://loinc.org` | `24879-9` | Pituitary and Sella turcica MRI W and WO contrast IV |
| `http://loinc.org` | `24880-7` | Pituitary and Sella turcica MRI |
| `http://loinc.org` | `24881-5` | Popliteal space US |
| `http://loinc.org` | `24882-3` | Popliteal artery Fluoroscopic angiogram Percutaneous transluminal angioplasty of vessel W contrast IA |
| `http://loinc.org` | `24883-1` | US Guidance for biopsy of Prostate |
| `http://loinc.org` | `24884-9` | Prostate US |
| `http://loinc.org` | `24885-6` | US Guidance for repair of Pseudoaneurysm/AV fistula |
| `http://loinc.org` | `24887-2` | Pulmonary artery Fluoroscopic angiogram Embolectomy W contrast IA |
| `http://loinc.org` | `24888-0` | Pulmonary system Scan ventilation and perfusion W Xe-133 inhaled and W Tc-99m MAA IV |
| `http://loinc.org` | `24889-8` | Pylorus US for pyloric stenosis |
| `http://loinc.org` | `24891-4` | Radius and Ulna X-ray |
| `http://loinc.org` | `24892-2` | Rectum US |
| `http://loinc.org` | `24893-0` | Rectum Fluoroscopy post contrast PR during defecation |
| `http://loinc.org` | `24894-8` | Rectum and Urinary bladder Fluoroscopy W contrast PR and intra bladder during defecation and voiding |
| `http://loinc.org` | `24896-3` | US Guidance for drainage of Kidney |
| `http://loinc.org` | `24899-7` | Ribs X-ray |
| `http://loinc.org` | `24900-3` | Sacroiliac Joint X-ray |
| `http://loinc.org` | `24901-1` | CT Guidance for injection of Sacroiliac Joint |
| `http://loinc.org` | `24902-9` | Salivary gland Fluoroscopy W contrast intra salivary duct |
| `http://loinc.org` | `24903-7` | Scapula X-ray |
| `http://loinc.org` | `24904-5` | Pituitary and Sella turcica CT W and WO contrast IV |
| `http://loinc.org` | `24905-2` | Shoulder MRI |
| `http://loinc.org` | `24906-0` | Shoulder MRI W and WO contrast IV |
| `http://loinc.org` | `24907-8` | Shoulder US |
| `http://loinc.org` | `24908-6` | Shoulder X-ray 3 views |
| `http://loinc.org` | `24909-4` | Shoulder X-ray |
| `http://loinc.org` | `24910-2` | Shoulder Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `24911-0` | Shunt Fluoroscopy |
| `http://loinc.org` | `24912-8` | Sinus tract Fluoroscopy W contrast intra sinus tract |
| `http://loinc.org` | `24913-6` | Sinuses CT limited |
| `http://loinc.org` | `24914-4` | Sinuses MRI |
| `http://loinc.org` | `24915-1` | Sinuses MRI W contrast IV |
| `http://loinc.org` | `24916-9` | Sinuses X-ray |
| `http://loinc.org` | `24917-7` | Skull X-ray Single view |
| `http://loinc.org` | `24918-5` | Skull X-ray 3 views |
| `http://loinc.org` | `24919-3` | Skull X-ray AP and lateral |
| `http://loinc.org` | `24920-1` | Skull X-ray lateral |
| `http://loinc.org` | `24921-9` | Skull X-ray Waters |
| `http://loinc.org` | `24922-7` | Skull X-ray 5 views |
| `http://loinc.org` | `24923-5` | Small bowel Fluoroscopy Views Enteroclysis W contrast PO via duodenal intubation |
| `http://loinc.org` | `24924-3` | Small bowel Fluoroscopy W contrast PO |
| `http://loinc.org` | `24925-0` | Spinal artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `24926-8` | Spine US |
| `http://loinc.org` | `24927-6` | Spine Fluoroscopy W contrast intradisc |
| `http://loinc.org` | `24928-4` | Spine X-ray AP and lateral |
| `http://loinc.org` | `24929-2` | Spine Thoracic and Lumbar X-ray scoliosis W flexion and W extension |
| `http://loinc.org` | `24930-0` | Spine Thoracic and Lumbar X-ray scoliosis |
| `http://loinc.org` | `24931-8` | Fluoroscopy Guidance for injection of Spine facet joint |
| `http://loinc.org` | `24932-6` | Spine Cervical CT |
| `http://loinc.org` | `24933-4` | Spine Cervical CT W contrast IV |
| `http://loinc.org` | `24934-2` | Spine Cervical CT W contrast IT |
| `http://loinc.org` | `24935-9` | Spine Cervical MRI |
| `http://loinc.org` | `24936-7` | Spine Cervical MRI W anesthesia |
| `http://loinc.org` | `24937-5` | Spine Cervical MRI W and WO contrast IV |
| `http://loinc.org` | `24938-3` | Spine Cervical MRI W contrast IV |
| `http://loinc.org` | `24939-1` | Spine Cervical X-ray 5 views |
| `http://loinc.org` | `24940-9` | Spine Cervical X-ray Single view |
| `http://loinc.org` | `24941-7` | Spine Cervical X-ray 3 views |
| `http://loinc.org` | `24942-5` | Spine Cervical X-ray AP and lateral |
| `http://loinc.org` | `24943-3` | Spine Cervical X-ray lateral |
| `http://loinc.org` | `24944-1` | Spine Cervical X-ray Swimmers |
| `http://loinc.org` | `24945-8` | Spine Cervical X-ray W flexion and W extension |
| `http://loinc.org` | `24946-6` | Spine Cervical X-ray |
| `http://loinc.org` | `24947-4` | Spine Cervical Fluoroscopy W contrast IT |
| `http://loinc.org` | `24948-2` | Spine Cervical Odontoid and Cervical axis X-ray AP single view |
| `http://loinc.org` | `24963-1` | Spine Lumbar CT |
| `http://loinc.org` | `24964-9` | Spine Lumbar CT W contrast IV |
| `http://loinc.org` | `24965-6` | Spine Lumbar CT W contrast IT |
| `http://loinc.org` | `24967-2` | Spine Lumbar MRI W and WO contrast IV |
| `http://loinc.org` | `24968-0` | Spine Lumbar MRI |
| `http://loinc.org` | `24969-8` | Spine Lumbar X-ray lateral |
| `http://loinc.org` | `24970-6` | Spine Lumbar X-ray AP and lateral |
| `http://loinc.org` | `24971-4` | Spine Lumbar X-ray W flexion and W extension |
| `http://loinc.org` | `24972-2` | Spine Lumbar X-ray |
| `http://loinc.org` | `24973-0` | Fluoroscopy Guidance for aspiration of Spine Lumbar Space |
| `http://loinc.org` | `24974-8` | Spine Lumbar Fluoroscopy W contrast IT |
| `http://loinc.org` | `24975-5` | Spine.lumbar and Sacroiliac joint - bilateral X-ray |
| `http://loinc.org` | `24977-1` | Spine Lumbar MRI W anesthesia |
| `http://loinc.org` | `24978-9` | Spine Thoracic CT |
| `http://loinc.org` | `24979-7` | Spine Thoracic CT W contrast IV |
| `http://loinc.org` | `24980-5` | Spine Thoracic MRI |
| `http://loinc.org` | `24981-3` | Spine Thoracic MRI W and WO contrast IV |
| `http://loinc.org` | `24982-1` | Spine Thoracic MRI W contrast IV |
| `http://loinc.org` | `24983-9` | Spine Thoracic X-ray |
| `http://loinc.org` | `24984-7` | Spine Thoracic and Lumbar X-ray 2 views |
| `http://loinc.org` | `24985-4` | Spine Thoracic Fluoroscopy W contrast IT |
| `http://loinc.org` | `24986-2` | CT Guidance for biopsy of Spine |
| `http://loinc.org` | `24987-0` | Spine CT W contrast IV |
| `http://loinc.org` | `24988-8` | Spleen CT |
| `http://loinc.org` | `24989-6` | Spleen CT W and WO contrast IV |
| `http://loinc.org` | `24990-4` | Spleen US |
| `http://loinc.org` | `24991-2` | Splenic vein and Portal vein Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `24992-0` | Splenic artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `24993-8` | Sternoclavicular Joints X-ray |
| `http://loinc.org` | `24994-6` | Sternum X-ray |
| `http://loinc.org` | `24995-3` | Fluoroscopy Guidance for placement of tube in Stomach |
| `http://loinc.org` | `24996-1` | Fluoroscopy Guidance for replacement of percutaneous gastrostomy in Stomach |
| `http://loinc.org` | `24997-9` | Stomach Scan for gastric emptying solid phase W Tc-99m SC PO |
| `http://loinc.org` | `24998-7` | Placement check of gastrostomy tube W contrast via GI tube |
| `http://loinc.org` | `24999-5` | Temporomandibular joint MRI |
| `http://loinc.org` | `25000-1` | Temporomandibular joint X-ray |
| `http://loinc.org` | `25001-9` | Scrotum and Testicle Scan W Tc-99m pertechnetate IV |
| `http://loinc.org` | `25002-7` | Scrotum and Testicle US |
| `http://loinc.org` | `25003-5` | Thigh vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `25005-0` | Three vessels Fluoroscopic angiogram W contrast |
| `http://loinc.org` | `25006-8` | Thumb X-ray |
| `http://loinc.org` | `25007-6` | Thyroid Scan W I-131 IV |
| `http://loinc.org` | `25008-4` | Thyroid Scan and uptake W I-131 IV |
| `http://loinc.org` | `25009-2` | US Guidance for biopsy of Thyroid |
| `http://loinc.org` | `25010-0` | Thyroid US |
| `http://loinc.org` | `25011-8` | Tibia and Fibula X-ray |
| `http://loinc.org` | `25012-6` | Tibial artery Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `25013-4` | Toes X-ray |
| `http://loinc.org` | `25014-2` | Two vessels Fluoroscopic angiogram W contrast |
| `http://loinc.org` | `25015-9` | Upper GI tract Replacement of percutaneous gastrojejunostomy |
| `http://loinc.org` | `25016-7` | Urethra Fluoroscopy W contrast intra urethra |
| `http://loinc.org` | `25017-5` | Urinary Bladder and Urethra Fluoroscopy W contrast intra bladder |
| `http://loinc.org` | `25018-3` | Urinary bladder Scan |
| `http://loinc.org` | `25019-1` | Urinary bladder US |
| `http://loinc.org` | `25020-9` | Urinary Bladder and Urethra Fluoroscopy W contrast retrograde via urethra |
| `http://loinc.org` | `25022-5` | Uterus and Fallopian tubes Fluoroscopy W contrast intrauterine |
| `http://loinc.org` | `25023-3` | Vein Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `25024-1` | Fluoroscopic angiogram Guidance for placement of longterm peripheral catheter in Central vein |
| `http://loinc.org` | `25025-8` | Vena cava Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `25026-6` | Fluoroscopic angiogram Guidance for placement of IVC filter in Inferior vena cava-- W contrast IV |
| `http://loinc.org` | `25027-4` | Guidance for placement of large bore catheter into vessel in Central vein |
| `http://loinc.org` | `25028-2` | Fluoroscopic angiogram Guidance for placement of catheter for adminstration of thrombolytic in Vessel |
| `http://loinc.org` | `25029-0` | Fluoroscopic angiogram Guidance for placement of catheter for vasoconstrictor infusion in Vessels |
| `http://loinc.org` | `25030-8` | Abdominal Arteries Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `25031-6` | Bone Scan |
| `http://loinc.org` | `25032-4` | Bone Scan W In-111 tagged WBC IV |
| `http://loinc.org` | `25033-2` | Wrist MRI |
| `http://loinc.org` | `25034-0` | Wrist Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `25035-7` | Wrist MRI W and WO contrast IV |
| `http://loinc.org` | `25036-5` | Wrist US |
| `http://loinc.org` | `25038-1` | Unspecified body region Courtesy consultation |
| `http://loinc.org` | `25039-9` | Unspecified body region CT limited |
| `http://loinc.org` | `25040-7` | Unspecified body region CT 3D |
| `http://loinc.org` | `25041-5` | CT Guidance for aspiration or biopsy of Unspecified body region-- W contrast IV |
| `http://loinc.org` | `25042-3` | CT Guidance for aspiration or biopsy of Unspecified body region |
| `http://loinc.org` | `25043-1` | CT Guidance for aspiration of Unspecified body region |
| `http://loinc.org` | `25044-9` | CT Guidance for biopsy of Unspecified body region |
| `http://loinc.org` | `25045-6` | Unspecified body region CT |
| `http://loinc.org` | `25046-4` | Unspecified body region CT W anesthesia |
| `http://loinc.org` | `25047-2` | Unspecified body region CT W conscious sedation |
| `http://loinc.org` | `25050-6` | Unspecified body region CT 3D sagittal and coronal disarticulation |
| `http://loinc.org` | `25051-4` | Unspecified body region CT Multisectional sagittal |
| `http://loinc.org` | `25052-2` | Unspecified body region CT sagittal and coronal |
| `http://loinc.org` | `25053-0` | CT Guidance for radiosurgery of Unspecified body region |
| `http://loinc.org` | `25054-8` | CT Guidance for radiosurgery of Unspecified body region-- W contrast IV |
| `http://loinc.org` | `25055-5` | Unspecified body region MRI additional sequence |
| `http://loinc.org` | `25056-3` | Unspecified body region MRI |
| `http://loinc.org` | `25057-1` | Unspecified body region MRI W conscious sedation |
| `http://loinc.org` | `25058-9` | Unspecified body region MRI angiogram W contrast IV |
| `http://loinc.org` | `25059-7` | US Guidance for biopsy of Unspecified body region |
| `http://loinc.org` | `25060-5` | Unspecified body region US No charge |
| `http://loinc.org` | `25061-3` | Unspecified body region US |
| `http://loinc.org` | `25062-1` | Unspecified body region X-ray Comparison view |
| `http://loinc.org` | `25063-9` | Vessel Fluoroscopic angiogram Single view W contrast IA |
| `http://loinc.org` | `25064-7` | Vessel Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `25065-4` | Unspecified body region Fluoroscopy 15 minutes |
| `http://loinc.org` | `25066-2` | Unspecified body region Fluoroscopy 30 minutes |
| `http://loinc.org` | `25067-0` | Unspecified body region Fluoroscopy 45 minutes |
| `http://loinc.org` | `25068-8` | Unspecified body region Fluoroscopy 1 hour |
| `http://loinc.org` | `25069-6` | Fluoroscopy Guidance for biopsy of Unspecified body region |
| `http://loinc.org` | `25070-4` | Unspecified body region Fluoroscopy during surgery |
| `http://loinc.org` | `25071-2` | Unspecified body region X-ray tomograph |
| `http://loinc.org` | `25072-0` | Guidance for placement of infusion port in Unspecified body region |
| `http://loinc.org` | `25073-8` | Vessel Fluoroscopic angiogram Removal of foreign body from vascular space |
| `http://loinc.org` | `25074-6` | Zygomatic arch X-ray |
| `http://loinc.org` | `25076-1` | Hepatic artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `25077-9` | Fluoroscopic angiogram Guidance for placement of catheter in Hepatic artery-- W contrast IA |
| `http://loinc.org` | `25078-7` | Fluoroscopy Guidance for placement of stent in Intrahepatic portal system |
| `http://loinc.org` | `25079-5` | Kidney arteries Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `25080-3` | Renal vein - bilateral Fluoroscopic angiogram W contrast IV and W renin sampling |
| `http://loinc.org` | `25081-1` | Renal vessel Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `25561-2` | 11-Deoxycorticosterone [Moles/volume] in Serum or Plasma |
| `http://loinc.org` | `26064-6` | Vein - bilateral Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `26065-3` | Vein - left Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `26066-1` | Vein - right Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `26067-9` | Salivary gland - bilateral Fluoroscopy W contrast intra salivary duct |
| `http://loinc.org` | `26068-7` | Salivary gland - left Fluoroscopy W contrast intra salivary duct |
| `http://loinc.org` | `26069-5` | Salivary gland - right Fluoroscopy W contrast intra salivary duct |
| `http://loinc.org` | `26070-3` | Hip - bilateral Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `26071-1` | Hip - left Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `26072-9` | Hip - right Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `26073-7` | Knee - bilateral Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `26074-5` | Knee - left Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `26075-2` | Knee - right Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `26076-0` | Shoulder - bilateral Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `26077-8` | Shoulder - left Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `26078-6` | Shoulder - right Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `26079-4` | Carotid artery - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `26080-2` | Carotid artery - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `26081-0` | Carotid artery - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `26082-8` | Spinal artery - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `26083-6` | Spinal artery - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `26084-4` | Spinal artery - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `26085-1` | Knee - bilateral X-ray standing |
| `http://loinc.org` | `26086-9` | Knee - left X-ray standing |
| `http://loinc.org` | `26087-7` | Knee - right X-ray standing |
| `http://loinc.org` | `26088-5` | Knee - bilateral Scan |
| `http://loinc.org` | `26089-3` | Knee - left Scan |
| `http://loinc.org` | `26090-1` | Knee - right Scan |
| `http://loinc.org` | `26091-9` | Scrotum and Testicle - bilateral Scan W Tc-99m pertechnetate IV |
| `http://loinc.org` | `26092-7` | Scrotum and Testicle - left Scan W Tc-99m pertechnetate IV |
| `http://loinc.org` | `26093-5` | Scrotum and Testicle - right Scan W Tc-99m pertechnetate IV |
| `http://loinc.org` | `26094-3` | Foot - bilateral X-ray standing |
| `http://loinc.org` | `26095-0` | Foot - left X-ray standing |
| `http://loinc.org` | `26096-8` | Foot - right X-ray standing |
| `http://loinc.org` | `26097-6` | Ankle - bilateral X-ray |
| `http://loinc.org` | `26098-4` | Ankle - left X-ray |
| `http://loinc.org` | `26099-2` | Ankle - right X-ray |
| `http://loinc.org` | `26100-8` | Calcaneus - bilateral X-ray |
| `http://loinc.org` | `26101-6` | Calcaneus - left X-ray |
| `http://loinc.org` | `26102-4` | Calcaneus - right X-ray |
| `http://loinc.org` | `26106-5` | Clavicle - bilateral X-ray |
| `http://loinc.org` | `26107-3` | Clavicle - left X-ray |
| `http://loinc.org` | `26108-1` | Clavicle - right X-ray |
| `http://loinc.org` | `26109-9` | Elbow - bilateral X-ray |
| `http://loinc.org` | `26110-7` | Elbow - left X-ray |
| `http://loinc.org` | `26111-5` | Elbow - right X-ray |
| `http://loinc.org` | `26112-3` | Lower extremity - bilateral X-ray |
| `http://loinc.org` | `26113-1` | Lower extremity - left X-ray |
| `http://loinc.org` | `26114-9` | Lower extremity - right X-ray |
| `http://loinc.org` | `26115-6` | Upper extremity - bilateral X-ray |
| `http://loinc.org` | `26116-4` | Upper extremity - left X-ray |
| `http://loinc.org` | `26117-2` | Upper extremity - right X-ray |
| `http://loinc.org` | `26118-0` | Femur - bilateral X-ray |
| `http://loinc.org` | `26120-6` | Femur - left X-ray |
| `http://loinc.org` | `26122-2` | Femur - right X-ray |
| `http://loinc.org` | `26124-8` | Finger - bilateral X-ray |
| `http://loinc.org` | `26125-5` | Finger - left X-ray |
| `http://loinc.org` | `26126-3` | Finger - right X-ray |
| `http://loinc.org` | `26127-1` | Foot - bilateral X-ray |
| `http://loinc.org` | `26128-9` | Foot - left X-ray |
| `http://loinc.org` | `26129-7` | Foot - right X-ray |
| `http://loinc.org` | `26130-5` | Hip - bilateral X-ray |
| `http://loinc.org` | `26131-3` | Hip - left X-ray |
| `http://loinc.org` | `26132-1` | Hip - right X-ray |
| `http://loinc.org` | `26133-9` | Acetabulum - bilateral X-ray |
| `http://loinc.org` | `26134-7` | Acetabulum - left X-ray |
| `http://loinc.org` | `26135-4` | Acetabulum - right X-ray |
| `http://loinc.org` | `26136-2` | Acromioclavicular joint - bilateral X-ray |
| `http://loinc.org` | `26137-0` | Acromioclavicular joint - left X-ray |
| `http://loinc.org` | `26138-8` | Acromioclavicular joint - right X-ray |
| `http://loinc.org` | `26139-6` | Mastoid - bilateral X-ray |
| `http://loinc.org` | `26140-4` | Mastoid - left X-ray |
| `http://loinc.org` | `26141-2` | Mastoid - right X-ray |
| `http://loinc.org` | `26142-0` | Optic foramen - bilateral X-ray |
| `http://loinc.org` | `26143-8` | Optic foramen - left X-ray |
| `http://loinc.org` | `26144-6` | Optic foramen - right X-ray |
| `http://loinc.org` | `26146-1` | Radius - bilateral and Ulna - bilateral X-ray |
| `http://loinc.org` | `26148-7` | Radius - left and Ulna.left X-ray |
| `http://loinc.org` | `26150-3` | Radius - right and Ulna - right X-ray |
| `http://loinc.org` | `26151-1` | Ribs - bilateral X-ray |
| `http://loinc.org` | `26152-9` | Ribs - left X-ray |
| `http://loinc.org` | `26153-7` | Ribs - right X-ray |
| `http://loinc.org` | `26154-5` | Scapula - bilateral X-ray |
| `http://loinc.org` | `26155-2` | Scapula - left X-ray |
| `http://loinc.org` | `26156-0` | Scapula - right X-ray |
| `http://loinc.org` | `26157-8` | Shoulder - bilateral X-ray |
| `http://loinc.org` | `26158-6` | Shoulder - left X-ray |
| `http://loinc.org` | `26159-4` | Shoulder - right X-ray |
| `http://loinc.org` | `26160-2` | Thumb - bilateral X-ray |
| `http://loinc.org` | `26161-0` | Thumb - left X-ray |
| `http://loinc.org` | `26162-8` | Thumb - right X-ray |
| `http://loinc.org` | `26163-6` | Tibia - bilateral and Fibula - bilateral X-ray |
| `http://loinc.org` | `26164-4` | Tibia - left and Fibula - left X-ray |
| `http://loinc.org` | `26165-1` | Tibia - right and Fibula - right X-ray |
| `http://loinc.org` | `26166-9` | Toes - bilateral X-ray |
| `http://loinc.org` | `26167-7` | Toes - left X-ray |
| `http://loinc.org` | `26168-5` | Toes - right X-ray |
| `http://loinc.org` | `26169-3` | Wrist - bilateral X-ray |
| `http://loinc.org` | `26170-1` | Wrist - left X-ray |
| `http://loinc.org` | `26171-9` | Wrist - right X-ray |
| `http://loinc.org` | `26172-7` | Zygomatic arch - bilateral X-ray |
| `http://loinc.org` | `26173-5` | Zygomatic arch - left X-ray |
| `http://loinc.org` | `26174-3` | Zygomatic arch - right X-ray |
| `http://loinc.org` | `26175-0` | Breast - bilateral Mammogram screening |
| `http://loinc.org` | `26176-8` | Breast - left Mammogram screening |
| `http://loinc.org` | `26177-6` | Breast - right Mammogram screening |
| `http://loinc.org` | `26178-4` | Femoral artery - bilateral Fluoroscopic angiogram runoff W contrast IA |
| `http://loinc.org` | `26179-2` | Femoral artery - left Fluoroscopic angiogram runoff W contrast IA |
| `http://loinc.org` | `26180-0` | Femoral artery - right Fluoroscopic angiogram runoff W contrast IA |
| `http://loinc.org` | `26181-8` | Thoracic outlet vessels - bilateral MRI angiogram W contrast IV |
| `http://loinc.org` | `26182-6` | Thoracic outlet vessels - left MRI angiogram W contrast IV |
| `http://loinc.org` | `26183-4` | Thoracic outlet vessels - right MRI angiogram W contrast IV |
| `http://loinc.org` | `26184-2` | Extremity - bilateral CT W contrast IV |
| `http://loinc.org` | `26185-9` | Extremity - left CT W contrast IV |
| `http://loinc.org` | `26186-7` | Extremity - right CT W contrast IV |
| `http://loinc.org` | `26187-5` | Ankle - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `26188-3` | Ankle - left MRI W and WO contrast IV |
| `http://loinc.org` | `26189-1` | Ankle - right MRI W and WO contrast IV |
| `http://loinc.org` | `26190-9` | Thoracic outlet - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `26191-7` | Thoracic outlet - left MRI W and WO contrast IV |
| `http://loinc.org` | `26192-5` | Thoracic outlet - right MRI W and WO contrast IV |
| `http://loinc.org` | `26193-3` | Elbow - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `26194-1` | Elbow - left MRI W and WO contrast IV |
| `http://loinc.org` | `26195-8` | Elbow - right MRI W and WO contrast IV |
| `http://loinc.org` | `26196-6` | Thigh - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `26197-4` | Thigh - left MRI W and WO contrast IV |
| `http://loinc.org` | `26198-2` | Thigh - right MRI W and WO contrast IV |
| `http://loinc.org` | `26199-0` | Knee - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `26200-6` | Knee - left MRI W and WO contrast IV |
| `http://loinc.org` | `26201-4` | Knee - right MRI W and WO contrast IV |
| `http://loinc.org` | `26202-2` | Shoulder - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `26203-0` | Shoulder - left MRI W and WO contrast IV |
| `http://loinc.org` | `26204-8` | Shoulder - right MRI W and WO contrast IV |
| `http://loinc.org` | `26205-5` | Wrist - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `26206-3` | Wrist - left MRI W and WO contrast IV |
| `http://loinc.org` | `26207-1` | Wrist - right MRI W and WO contrast IV |
| `http://loinc.org` | `26208-9` | Ankle - bilateral MRI |
| `http://loinc.org` | `26209-7` | Ankle - left MRI |
| `http://loinc.org` | `26210-5` | Ankle - right MRI |
| `http://loinc.org` | `26211-3` | Thoracic outlet - bilateral MRI |
| `http://loinc.org` | `26212-1` | Thoracic outlet - left MRI |
| `http://loinc.org` | `26213-9` | Thoracic outlet - right MRI |
| `http://loinc.org` | `26214-7` | Breast - bilateral US |
| `http://loinc.org` | `26215-4` | Breast - left US |
| `http://loinc.org` | `26216-2` | Breast - right US |
| `http://loinc.org` | `26217-0` | Carotid artery - bilateral US |
| `http://loinc.org` | `26218-8` | Carotid artery - left US |
| `http://loinc.org` | `26219-6` | Carotid artery - right US |
| `http://loinc.org` | `26220-4` | Elbow - bilateral MRI |
| `http://loinc.org` | `26221-2` | Elbow - left MRI |
| `http://loinc.org` | `26222-0` | Elbow - right MRI |
| `http://loinc.org` | `26223-8` | Extremity - bilateral US |
| `http://loinc.org` | `26224-6` | Extremity - bilateral CT |
| `http://loinc.org` | `26225-3` | Extremity - left US |
| `http://loinc.org` | `26226-1` | Extremity - left CT |
| `http://loinc.org` | `26227-9` | Lower extremity joint - bilateral MRI |
| `http://loinc.org` | `26228-7` | Lower extremity joint - left MRI |
| `http://loinc.org` | `26229-5` | Lower extremity joint - right MRI |
| `http://loinc.org` | `26230-3` | Extremity - right US |
| `http://loinc.org` | `26231-1` | Extremity - right CT |
| `http://loinc.org` | `26232-9` | Upper extremity - bilateral MRI |
| `http://loinc.org` | `26233-7` | Upper extremity - left MRI |
| `http://loinc.org` | `26234-5` | Upper extremity - right MRI |
| `http://loinc.org` | `26235-2` | Thigh - bilateral MRI |
| `http://loinc.org` | `26236-0` | Thigh - left MRI |
| `http://loinc.org` | `26237-8` | Thigh - right MRI |
| `http://loinc.org` | `26238-6` | Finger - bilateral MRI |
| `http://loinc.org` | `26239-4` | Finger - left MRI |
| `http://loinc.org` | `26240-2` | Finger - right MRI |
| `http://loinc.org` | `26241-0` | Foot - bilateral MRI |
| `http://loinc.org` | `26242-8` | Foot - left MRI |
| `http://loinc.org` | `26243-6` | Foot - right MRI |
| `http://loinc.org` | `26244-4` | Forearm - bilateral MRI |
| `http://loinc.org` | `26245-1` | Forearm - left MRI |
| `http://loinc.org` | `26246-9` | Forearm - right MRI |
| `http://loinc.org` | `26247-7` | Hand - bilateral MRI |
| `http://loinc.org` | `26248-5` | Hand - left MRI |
| `http://loinc.org` | `26249-3` | Hand - right MRI |
| `http://loinc.org` | `26250-1` | Hip - bilateral US |
| `http://loinc.org` | `26251-9` | Hip - left US |
| `http://loinc.org` | `26252-7` | Hip - right US |
| `http://loinc.org` | `26253-5` | Internal auditory canal - bilateral X-ray tomograph |
| `http://loinc.org` | `26254-3` | Internal auditory canal - left X-ray tomograph |
| `http://loinc.org` | `26255-0` | Internal auditory canal - right X-ray tomograph |
| `http://loinc.org` | `26256-8` | Knee - bilateral MRI |
| `http://loinc.org` | `26257-6` | Knee - left MRI |
| `http://loinc.org` | `26258-4` | Knee - right MRI |
| `http://loinc.org` | `26259-2` | Pelvis and Hip - bilateral MRI |
| `http://loinc.org` | `26260-0` | Pelvis and Hip - left MRI |
| `http://loinc.org` | `26261-8` | Pelvis and Hip - right MRI |
| `http://loinc.org` | `26262-6` | Popliteal space - bilateral US |
| `http://loinc.org` | `26263-4` | Popliteal space - left US |
| `http://loinc.org` | `26264-2` | Popliteal space - right US |
| `http://loinc.org` | `26265-9` | Shoulder - bilateral US |
| `http://loinc.org` | `26266-7` | Shoulder - bilateral MRI |
| `http://loinc.org` | `26267-5` | Shoulder - left US |
| `http://loinc.org` | `26268-3` | Shoulder - left MRI |
| `http://loinc.org` | `26269-1` | Shoulder - right US |
| `http://loinc.org` | `26270-9` | Shoulder - right MRI |
| `http://loinc.org` | `26271-7` | Scrotum and Testicle - bilateral US |
| `http://loinc.org` | `26272-5` | Scrotum and Testicle - left US |
| `http://loinc.org` | `26273-3` | Scrotum and Testicle - right US |
| `http://loinc.org` | `26277-4` | Wrist - bilateral MRI |
| `http://loinc.org` | `26278-2` | Wrist - bilateral US |
| `http://loinc.org` | `26279-0` | Wrist - left MRI |
| `http://loinc.org` | `26280-8` | Wrist - left US |
| `http://loinc.org` | `26281-6` | Wrist - right MRI |
| `http://loinc.org` | `26282-4` | Wrist - right US |
| `http://loinc.org` | `26283-2` | Knee - bilateral X-ray Merchants |
| `http://loinc.org` | `26284-0` | Knee - left X-ray Merchants |
| `http://loinc.org` | `26285-7` | Knee - right X-ray Merchants |
| `http://loinc.org` | `26286-5` | Breast - bilateral US limited |
| `http://loinc.org` | `26287-3` | Breast - bilateral Mammogram limited |
| `http://loinc.org` | `26288-1` | Breast - left US limited |
| `http://loinc.org` | `26289-9` | Breast - left Mammogram limited |
| `http://loinc.org` | `26290-7` | Breast - right US limited |
| `http://loinc.org` | `26291-5` | Breast - right Mammogram limited |
| `http://loinc.org` | `26292-3` | Mammogram Guidance.stereotactic for biopsy of Breast - bilateral |
| `http://loinc.org` | `26293-1` | Mammogram Guidance.stereotactic for biopsy of Breast - left |
| `http://loinc.org` | `26294-9` | Mammogram Guidance.stereotactic for biopsy of Breast - right |
| `http://loinc.org` | `26295-6` | Fluoroscopic angiogram Guidance for reposition of catheter in Central vein - bilateral-- W contrast IV |
| `http://loinc.org` | `26296-4` | Fluoroscopic angiogram Guidance for reposition of catheter in Central vein - left-- W contrast IV |
| `http://loinc.org` | `26297-2` | Fluoroscopic angiogram Guidance for reposition of catheter in Central vein - right-- W contrast IV |
| `http://loinc.org` | `26298-0` | Fluoroscopic angiogram Guidance for atherectomy of Vein - bilateral-- W contrast IV |
| `http://loinc.org` | `26299-8` | Fluoroscopic angiogram Guidance for atherectomy of Vein - left-- W contrast IV |
| `http://loinc.org` | `26300-4` | Fluoroscopic angiogram Guidance for atherectomy of Vein - right-- W contrast IV |
| `http://loinc.org` | `26301-2` | Fluoroscopic angiogram Guidance for placement of stent in Vein - bilateral |
| `http://loinc.org` | `26302-0` | Fluoroscopic angiogram Guidance for placement of stent in Vein - left |
| `http://loinc.org` | `26303-8` | Fluoroscopic angiogram Guidance for placement of stent in Vein - right |
| `http://loinc.org` | `26304-6` | Fluoroscopic angiogram Guidance for placement of longterm peripheral catheter in Central vein - bilateral |
| `http://loinc.org` | `26305-3` | Fluoroscopic angiogram Guidance for placement of longterm peripheral catheter in Central vein - left |
| `http://loinc.org` | `26306-1` | Fluoroscopic angiogram Guidance for placement of longterm peripheral catheter in Central vein - right |
| `http://loinc.org` | `26307-9` | Guidance for placement of large bore catheter into vessel in Central vein - bilateral |
| `http://loinc.org` | `26308-7` | Guidance for placement of large bore catheter into vessel in Central vein - left |
| `http://loinc.org` | `26309-5` | Guidance for placement of large bore catheter into vessel in Central vein - right |
| `http://loinc.org` | `26310-3` | Fluoroscopic angiogram Guidance for placement of catheter in Central vein - bilateral-- W contrast IV |
| `http://loinc.org` | `26311-1` | Fluoroscopic angiogram Guidance for placement of catheter in Central vein - left-- W contrast IV |
| `http://loinc.org` | `26312-9` | Fluoroscopic angiogram Guidance for placement of catheter in Central vein - right-- W contrast IV |
| `http://loinc.org` | `26313-7` | US Guidance for needle localization of Breast - bilateral |
| `http://loinc.org` | `26314-5` | US Guidance for needle localization of Breast - left |
| `http://loinc.org` | `26315-2` | Mammogram Guidance for needle localization of mass of Breast - bilateral |
| `http://loinc.org` | `26316-0` | Mammogram Guidance for needle localization of mass of Breast - left |
| `http://loinc.org` | `26317-8` | Mammogram Guidance for needle localization of mass of Breast - right |
| `http://loinc.org` | `26318-6` | US Guidance for needle localization of Breast - right |
| `http://loinc.org` | `26319-4` | CT Guidance for injection of Sacroiliac joint - bilateral |
| `http://loinc.org` | `26320-2` | CT Guidance for injection of Sacroiliac joint - left |
| `http://loinc.org` | `26321-0` | CT Guidance for injection of Sacroiliac joint - right |
| `http://loinc.org` | `26322-8` | Fluoroscopy Guidance for injection of Spine facet joint - bilateral |
| `http://loinc.org` | `26323-6` | Fluoroscopy Guidance for injection of Spine facet joint - left |
| `http://loinc.org` | `26324-4` | Fluoroscopy Guidance for injection of Spine facet joint - right |
| `http://loinc.org` | `26325-1` | US Guidance for drainage of Extremity - bilateral |
| `http://loinc.org` | `26326-9` | US Guidance for drainage of Extremity - left |
| `http://loinc.org` | `26327-7` | US Guidance for drainage of Extremity - right |
| `http://loinc.org` | `26328-5` | US Guidance for drainage of Kidney - bilateral |
| `http://loinc.org` | `26329-3` | US Guidance for drainage of Kidney - left |
| `http://loinc.org` | `26330-1` | US Guidance for drainage of Kidney - right |
| `http://loinc.org` | `26331-9` | Fluoroscopic angiogram Guidance for change of central catheter in Central vein - bilateral-- W contrast IV |
| `http://loinc.org` | `26332-7` | Fluoroscopic angiogram Guidance for change of central catheter in Central vein - left-- W contrast IV |
| `http://loinc.org` | `26333-5` | Fluoroscopic angiogram Guidance for change of central catheter in Central vein - right-- W contrast IV |
| `http://loinc.org` | `26334-3` | Mammogram Guidance for core needle percutaneous biopsy of Breast - bilateral |
| `http://loinc.org` | `26335-0` | Mammogram Guidance for core needle percutaneous biopsy of Breast - left |
| `http://loinc.org` | `26336-8` | Mammogram Guidance for core needle percutaneous biopsy of Breast - right |
| `http://loinc.org` | `26337-6` | Mammogram Guidance for biopsy of Breast - bilateral |
| `http://loinc.org` | `26338-4` | Mammogram Guidance for biopsy of Breast - left |
| `http://loinc.org` | `26339-2` | Mammogram Guidance for biopsy of Breast - right |
| `http://loinc.org` | `26340-0` | US Guidance for biopsy of Kidney - bilateral |
| `http://loinc.org` | `26341-8` | US Guidance for biopsy of Kidney - left |
| `http://loinc.org` | `26342-6` | US Guidance for biopsy of Kidney - right |
| `http://loinc.org` | `26343-4` | Mammogram Guidance for aspiration of cyst of Breast - bilateral |
| `http://loinc.org` | `26344-2` | Mammogram Guidance for aspiration of cyst of Breast - left |
| `http://loinc.org` | `26345-9` | Mammogram Guidance for aspiration of cyst of Breast - right |
| `http://loinc.org` | `26346-7` | Breast - bilateral Mammogram diagnostic |
| `http://loinc.org` | `26347-5` | Breast - left Mammogram diagnostic |
| `http://loinc.org` | `26348-3` | Breast - right Mammogram diagnostic |
| `http://loinc.org` | `26349-1` | Breast - bilateral Mammogram diagnostic limited |
| `http://loinc.org` | `26350-9` | Breast - left Mammogram diagnostic limited |
| `http://loinc.org` | `26351-7` | Breast - right Mammogram diagnostic limited |
| `http://loinc.org` | `26352-5` | Wrist - bilateral and Hand - bilateral X-ray bone age |
| `http://loinc.org` | `26353-3` | Wrist - left and Hand - left X-ray bone age |
| `http://loinc.org` | `26354-1` | Wrist - right and Hand - right X-ray bone age |
| `http://loinc.org` | `26355-8` | Hand - bilateral X-ray arthritis |
| `http://loinc.org` | `26356-6` | Hand - left X-ray arthritis |
| `http://loinc.org` | `26357-4` | Hand - right X-ray arthritis |
| `http://loinc.org` | `26358-2` | Knee - bilateral X-ray AP single view standing |
| `http://loinc.org` | `26359-0` | Knee - left X-ray AP single view standing |
| `http://loinc.org` | `26360-8` | Knee - right X-ray AP single view standing |
| `http://loinc.org` | `26361-6` | Knee - bilateral X-ray AP and PA standing |
| `http://loinc.org` | `26362-4` | Knee - left X-ray AP and PA standing |
| `http://loinc.org` | `26363-2` | Knee - right X-ray AP and PA standing |
| `http://loinc.org` | `26364-0` | Knee - bilateral X-ray AP and lateral standing |
| `http://loinc.org` | `26365-7` | Knee - left X-ray AP and lateral standing |
| `http://loinc.org` | `26366-5` | Knee - right X-ray AP and lateral standing |
| `http://loinc.org` | `26368-1` | Brachiocephalic artery - left Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `26369-9` | Brachiocephalic artery - right Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `26370-7` | Iliac artery - bilateral Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `26371-5` | Iliac artery - left Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `26372-3` | Iliac artery - right Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `26373-1` | Tibial artery - bilateral Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `26374-9` | Tibial artery - left Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `26375-6` | Tibial artery - right Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `26376-4` | Administration of vasodilator into catheter of Vein - bilateral |
| `http://loinc.org` | `26377-2` | Administration of vasodilator into catheter of Vein - left |
| `http://loinc.org` | `26378-0` | Administration of vasodilator into catheter of Vein - right |
| `http://loinc.org` | `26379-8` | Hand - bilateral X-ray 3 views |
| `http://loinc.org` | `26380-6` | Hand - left X-ray 3 views |
| `http://loinc.org` | `26381-4` | Hand - right X-ray 3 views |
| `http://loinc.org` | `26382-2` | Shoulder - bilateral X-ray 3 views |
| `http://loinc.org` | `26383-0` | Shoulder - left X-ray 3 views |
| `http://loinc.org` | `26384-8` | Shoulder - right X-ray 3 views |
| `http://loinc.org` | `26385-5` | Ankle - bilateral X-ray 2 views |
| `http://loinc.org` | `26386-3` | Ankle - left X-ray 2 views |
| `http://loinc.org` | `26387-1` | Ankle - right X-ray 2 views |
| `http://loinc.org` | `26388-9` | Hand - bilateral X-ray 2 views |
| `http://loinc.org` | `26389-7` | Hand - left X-ray 2 views |
| `http://loinc.org` | `26390-5` | Hand - right X-ray 2 views |
| `http://loinc.org` | `26391-3` | Humerus - bilateral X-ray 2 views |
| `http://loinc.org` | `26392-1` | Humerus - left X-ray 2 views |
| `http://loinc.org` | `26393-9` | Humerus - right X-ray 2 views |
| `http://loinc.org` | `26394-7` | Knee - bilateral X-ray 2 views |
| `http://loinc.org` | `26395-4` | Knee - left X-ray 2 views |
| `http://loinc.org` | `26396-2` | Knee - right X-ray 2 views |
| `http://loinc.org` | `26397-0` | Patella - bilateral X-ray 2 views |
| `http://loinc.org` | `26398-8` | Patella - left X-ray 2 views |
| `http://loinc.org` | `26399-6` | Patella - right X-ray 2 views |
| `http://loinc.org` | `26400-2` | Hip - bilateral X-ray Single view |
| `http://loinc.org` | `26401-0` | Hip - left X-ray Single view |
| `http://loinc.org` | `26402-8` | Hip - right X-ray Single view |
| `http://loinc.org` | `26988-6` | 18-Hydroxydeoxycorticosterone [Mass/time] in 24 hour Urine |
| `http://loinc.org` | `28561-9` | Pelvis X-ray |
| `http://loinc.org` | `28564-3` | Skull X-ray |
| `http://loinc.org` | `28565-0` | Knee X-ray |
| `http://loinc.org` | `28566-8` | Spine CT |
| `http://loinc.org` | `28567-6` | Humerus X-ray |
| `http://loinc.org` | `28568-4` | Physician Emergency department Note |
| `http://loinc.org` | `28569-2` | Physician consulting Progress note |
| `http://loinc.org` | `28570-0` | Provider-unspecified Procedure note |
| `http://loinc.org` | `28571-8` | Speech-language pathology Note |
| `http://loinc.org` | `28572-6` | Dentist Initial assessment note |
| `http://loinc.org` | `28573-4` | Physician, Operation note |
| `http://loinc.org` | `28574-2` | Discharge note |
| `http://loinc.org` | `28575-9` | Nurse practitioner Progress note |
| `http://loinc.org` | `28576-7` | Joint MRI |
| `http://loinc.org` | `28577-5` | Dentist procedure note |
| `http://loinc.org` | `28578-3` | Occupational therapy Note |
| `http://loinc.org` | `28579-1` | Physical therapy Note |
| `http://loinc.org` | `28580-9` | Chiropractic medicine Progress note |
| `http://loinc.org` | `28581-7` | Chiropractic medicine Initial assessment note |
| `http://loinc.org` | `28582-5` | Hand X-ray |
| `http://loinc.org` | `28583-3` | Dentist Operation note |
| `http://loinc.org` | `28613-8` | Spine X-ray |
| `http://loinc.org` | `28614-6` | Liver US |
| `http://loinc.org` | `28615-3` | Audiology study |
| `http://loinc.org` | `28616-1` | Physician Transfer note |
| `http://loinc.org` | `28617-9` | Dentistry Progress note |
| `http://loinc.org` | `28618-7` | Dentistry Note |
| `http://loinc.org` | `28621-1` | Nurse practitioner Initial assessment note |
| `http://loinc.org` | `28622-9` | Nurse Discharge assessment |
| `http://loinc.org` | `28623-7` | Nurse Progress note |
| `http://loinc.org` | `28624-5` | Podiatry Operation note |
| `http://loinc.org` | `28625-2` | Podiatry procedure note |
| `http://loinc.org` | `28626-0` | Physician History and physical note |
| `http://loinc.org` | `28627-8` | Psychiatry Progress note |
| `http://loinc.org` | `28628-6` | Psychiatry Note |
| `http://loinc.org` | `28629-4` | Perimetry study |
| `http://loinc.org` | `28630-2` | Tonometry study |
| `http://loinc.org` | `28631-0` | Visual acuity study |
| `http://loinc.org` | `28632-8` | Heterophoria study |
| `http://loinc.org` | `28633-6` | Polysomnography (sleep) study |
| `http://loinc.org` | `28635-1` | Psychiatry Initial assessment note |
| `http://loinc.org` | `28636-9` | Provider-unspecified Initial assessment |
| `http://loinc.org` | `28651-8` | Nurse Transfer note |
| `http://loinc.org` | `28653-4` | Social work Note |
| `http://loinc.org` | `28654-2` | Physician attending Initial assessment note |
| `http://loinc.org` | `28655-9` | Physician attending Discharge summary |
| `http://loinc.org` | `28656-7` | Social work Progress note |
| `http://loinc.org` | `29111-2` | Photo documentation Eye - right |
| `http://loinc.org` | `29112-0` | Photo documentation Eye - left |
| `http://loinc.org` | `29206-0` | Speech therapy service attachment |
| `http://loinc.org` | `29252-4` | Chest CT WO contrast |
| `http://loinc.org` | `29272-2` | Eye ultrasound study |
| `http://loinc.org` | `29749-9` | Dialysis records |
| `http://loinc.org` | `29750-7` | Neonatal intensive care records |
| `http://loinc.org` | `29751-5` | Critical care records |
| `http://loinc.org` | `29752-3` | Perioperative records |
| `http://loinc.org` | `29753-1` | Nurse Initial assessment note |
| `http://loinc.org` | `29754-9` | Nystagmogram study |
| `http://loinc.org` | `29755-6` | Nerve conduction study |
| `http://loinc.org` | `29756-4` | Peritoneoscopy study |
| `http://loinc.org` | `29757-2` | Colposcopy study |
| `http://loinc.org` | `29761-4` | Dentist Discharge summary |
| `http://loinc.org` | `30578-9` | CT Guidance for abscess drainage of Unspecified body region |
| `http://loinc.org` | `30579-7` | CT Guidance for injection of Spine facet joint |
| `http://loinc.org` | `30580-5` | CT Guidance for fine needle aspiration of Unspecified body region |
| `http://loinc.org` | `30581-3` | CT Guidance for radiation treatment of Unspecified body region-- W contrast IV |
| `http://loinc.org` | `30582-1` | CT Guidance for radiation treatment of Unspecified body region-- WO contrast |
| `http://loinc.org` | `30583-9` | Internal auditory canal CT W contrast IV |
| `http://loinc.org` | `30584-7` | Internal auditory canal CT WO contrast |
| `http://loinc.org` | `30585-4` | Nasopharynx and Neck CT WO contrast |
| `http://loinc.org` | `30586-2` | Neck CT W and WO contrast IV |
| `http://loinc.org` | `30587-0` | Orbit - bilateral CT WO contrast |
| `http://loinc.org` | `30588-8` | Sinuses CT |
| `http://loinc.org` | `30589-6` | Petrous bone CT WO contrast |
| `http://loinc.org` | `30590-4` | Pituitary and Sella turcica CT W contrast IV |
| `http://loinc.org` | `30591-2` | Pituitary and Sella turcica CT WO contrast |
| `http://loinc.org` | `30592-0` | Spine Cervical CT WO contrast |
| `http://loinc.org` | `30593-8` | Head vessels CT angiogram W and WO contrast IV |
| `http://loinc.org` | `30594-6` | Neck vessels CT angiogram W and WO contrast IV |
| `http://loinc.org` | `30595-3` | CT Guidance for fine needle aspiration of Lung |
| `http://loinc.org` | `30596-1` | Spine Thoracic CT W contrast IT |
| `http://loinc.org` | `30597-9` | Spine Thoracic CT WO contrast |
| `http://loinc.org` | `30598-7` | Chest CT W and WO contrast IV |
| `http://loinc.org` | `30599-5` | Abdomen CT W contrast |
| `http://loinc.org` | `30600-1` | Small bowel CT Views Enteroclysis W contrast PO via duodenal intubation |
| `http://loinc.org` | `30601-9` | CT Guidance for biopsy of Abdomen |
| `http://loinc.org` | `30602-7` | CT Guidance for fine needle aspiration of Abdomen |
| `http://loinc.org` | `30603-5` | CT Guidance for fine needle aspiration of Liver |
| `http://loinc.org` | `30604-3` | CT Guidance for biopsy of Pancreas |
| `http://loinc.org` | `30605-0` | CT Guidance for fine needle aspiration of Pancreas |
| `http://loinc.org` | `30606-8` | CT Guidance for fine needle aspiration of Pelvis |
| `http://loinc.org` | `30607-6` | CT Guidance for biopsy of Kidney - bilateral |
| `http://loinc.org` | `30608-4` | CT Guidance for fine needle aspiration of Kidney - bilateral |
| `http://loinc.org` | `30609-2` | CT Guidance for biopsy of Spleen |
| `http://loinc.org` | `30610-0` | CT Guidance for fine needle aspiration of Spleen |
| `http://loinc.org` | `30611-8` | Liver CT WO contrast |
| `http://loinc.org` | `30612-6` | Liver CT W and WO contrast IV |
| `http://loinc.org` | `30613-4` | Pancreas CT WO contrast |
| `http://loinc.org` | `30614-2` | Pancreas CT W and WO contrast IV |
| `http://loinc.org` | `30615-9` | Pelvis CT WO contrast |
| `http://loinc.org` | `30616-7` | Pelvis CT W and WO contrast IV |
| `http://loinc.org` | `30619-1` | Sacroiliac Joint CT |
| `http://loinc.org` | `30620-9` | Spine Lumbar CT WO contrast |
| `http://loinc.org` | `30621-7` | Spleen CT WO contrast |
| `http://loinc.org` | `30622-5` | Spleen CT W contrast IV |
| `http://loinc.org` | `30623-3` | Pelvis vessels CT angiogram W and WO contrast IV |
| `http://loinc.org` | `30624-1` | Lower extremity CT W contrast IV |
| `http://loinc.org` | `30625-8` | Lower extremity CT WO contrast |
| `http://loinc.org` | `30626-6` | Upper extremity CT W contrast IV |
| `http://loinc.org` | `30627-4` | Upper extremity CT WO contrast |
| `http://loinc.org` | `30628-2` | Fluoroscopy Guidance for removal of foreign body from Unspecified body region |
| `http://loinc.org` | `30629-0` | Fluoroscopy Guidance for procedure of Unspecified body region |
| `http://loinc.org` | `30630-8` | Head Cistern Fluoroscopy video W contrast |
| `http://loinc.org` | `30631-6` | Chest Fluoroscopy |
| `http://loinc.org` | `30632-4` | Diaphragm Fluoroscopy Motion |
| `http://loinc.org` | `30633-2` | Esophagus Fluoroscopy W barium contrast PO |
| `http://loinc.org` | `30634-0` | Fluoroscopy Guidance for biopsy of Lung |
| `http://loinc.org` | `30635-7` | Gastrointestine upper Fluoroscopy and AP W contrast PO |
| `http://loinc.org` | `30636-5` | Colon Fluoroscopy Reduction W views W contrast PR |
| `http://loinc.org` | `30637-3` | Fluoroscopy Guidance for placement of tube in Gastrointestine |
| `http://loinc.org` | `30638-1` | Fluoroscopy Guidance for injection of Hip |
| `http://loinc.org` | `30639-9` | Vessel Fluoroscopic angiogram W contrast |
| `http://loinc.org` | `30640-7` | Vein Fluoroscopic angiogram Angioplasty W contrast IV |
| `http://loinc.org` | `30641-5` | Vein Fluoroscopic angiogram Additional angioplasty W contrast IV |
| `http://loinc.org` | `30642-3` | Unspecified body region Fluoroscopy Single view |
| `http://loinc.org` | `30643-1` | US Guidance for placement of catheter in Central vein |
| `http://loinc.org` | `30644-9` | US Guidance for placement of catheter in Central vein-- Tunneled |
| `http://loinc.org` | `30645-6` | Superior vena cava Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `30646-4` | Fluoroscopy Guidance for change of tube in Sinus tract-- W contrast |
| `http://loinc.org` | `30647-2` | Biliary ducts and Gallbladder Fluoroscopy W contrast via T-tube |
| `http://loinc.org` | `30648-0` | Peripheral artery Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `30649-8` | Peripheral artery Fluoroscopic angiogram Additional angioplasty W contrast IA |
| `http://loinc.org` | `30650-6` | Unspecified body region Fluoroscopy for shunt |
| `http://loinc.org` | `30651-4` | US Guidance for core needle biopsy of Breast |
| `http://loinc.org` | `30652-2` | US Guidance for fine needle biopsy of Breast |
| `http://loinc.org` | `30653-0` | US Guidance for aspiration of cyst of Breast |
| `http://loinc.org` | `30654-8` | Thoracic outlet MRI WO contrast |
| `http://loinc.org` | `30655-5` | Head Cistern MRI |
| `http://loinc.org` | `30656-3` | MRI Guidance.stereotactic for localization in Brain-- W contrast IV |
| `http://loinc.org` | `30657-1` | Brain MRI WO contrast |
| `http://loinc.org` | `30658-9` | Internal auditory canal MRI WO contrast |
| `http://loinc.org` | `30659-7` | Internal auditory canal MRI W and WO contrast IV |
| `http://loinc.org` | `30660-5` | Neck MRI WO contrast |
| `http://loinc.org` | `30661-3` | Orbit - bilateral MRI WO contrast |
| `http://loinc.org` | `30662-1` | Sinuses MRI WO contrast |
| `http://loinc.org` | `30663-9` | Sinuses MRI W and WO contrast IV |
| `http://loinc.org` | `30664-7` | MRI Guidance for radiation treatment of Unspecified body region-- W contrast IV |
| `http://loinc.org` | `30665-4` | MRI Guidance for radiation treatment of Unspecified body region-- WO contrast |
| `http://loinc.org` | `30666-2` | Pituitary and Sella turcica MRI WO contrast |
| `http://loinc.org` | `30667-0` | Spine Cervical MRI WO contrast |
| `http://loinc.org` | `30668-8` | Abdomen MRI WO contrast |
| `http://loinc.org` | `30669-6` | Liver MRI WO contrast |
| `http://loinc.org` | `30670-4` | Liver MRI W and WO contrast IV |
| `http://loinc.org` | `30671-2` | Pelvis and Hip MRI WO contrast |
| `http://loinc.org` | `30672-0` | Pelvis and Hip MRI W and WO contrast IV |
| `http://loinc.org` | `30673-8` | Pelvis MRI WO contrast |
| `http://loinc.org` | `30674-6` | Pelvis MRI W and WO contrast IV |
| `http://loinc.org` | `30675-3` | Prostate MRI |
| `http://loinc.org` | `30678-7` | Spine Lumbar MRI W contrast IV |
| `http://loinc.org` | `30679-5` | Spine Lumbar MRI WO contrast |
| `http://loinc.org` | `30680-3` | Ankle MRI WO contrast |
| `http://loinc.org` | `30681-1` | Foot MRI WO contrast |
| `http://loinc.org` | `30682-9` | Foot MRI W and WO contrast IV |
| `http://loinc.org` | `30683-7` | Forearm MRI WO contrast |
| `http://loinc.org` | `30684-5` | Forearm MRI W and WO contrast IV |
| `http://loinc.org` | `30685-2` | Hand MRI WO contrast |
| `http://loinc.org` | `30686-0` | Hand MRI W and WO contrast IV |
| `http://loinc.org` | `30687-8` | Hip MRI WO contrast |
| `http://loinc.org` | `30688-6` | Hip MRI W and WO contrast IV |
| `http://loinc.org` | `30689-4` | Upper arm MRI WO contrast |
| `http://loinc.org` | `30690-2` | Upper arm MRI W and WO contrast IV |
| `http://loinc.org` | `30691-0` | Knee MRI WO contrast |
| `http://loinc.org` | `30692-8` | Lower extremity MRI |
| `http://loinc.org` | `30693-6` | Shoulder MRI WO contrast |
| `http://loinc.org` | `30694-4` | Thyroid Scan and uptake.single |
| `http://loinc.org` | `30695-1` | Thyroid Scan |
| `http://loinc.org` | `30696-9` | Scrotum and Testicle Scan |
| `http://loinc.org` | `30697-7` | Pulmonary system Scan ventilation and perfusion W radionuclide inhaled and W radionuclide IV |
| `http://loinc.org` | `30698-5` | US Guidance for aspiration of cyst of Unspecified body region |
| `http://loinc.org` | `30699-3` | US Guidance for drainage of Unspecified body region |
| `http://loinc.org` | `30700-9` | US Guidance for needle biopsy of Unspecified body region |
| `http://loinc.org` | `30701-7` | Unspecified body region US during surgery |
| `http://loinc.org` | `30702-5` | US Guidance for injection of Thyroid |
| `http://loinc.org` | `30703-3` | US Guidance for aspiration of Pericardial space |
| `http://loinc.org` | `30704-1` | Abdomen US limited |
| `http://loinc.org` | `30705-8` | Uterus and Fallopian tubes US |
| `http://loinc.org` | `30706-6` | Liver US during surgery |
| `http://loinc.org` | `30709-0` | Lower extremity US |
| `http://loinc.org` | `30710-8` | Upper extremity US |
| `http://loinc.org` | `30711-6` | Hip US developmental joint assessment |
| `http://loinc.org` | `30712-4` | Hip US WO developmental joint assessment |
| `http://loinc.org` | `30713-2` | Spine X-ray W right bending and W left bending |
| `http://loinc.org` | `30714-0` | Spine Thoracic and Lumbar X-ray scoliosis AP |
| `http://loinc.org` | `30715-7` | Spine Thoracic and Lumbar X-ray scoliosis AP and lateral |
| `http://loinc.org` | `30716-5` | Spine Thoracic and Lumbar X-ray scoliosis lateral |
| `http://loinc.org` | `30717-3` | Spine Thoracic and Lumbar X-ray scoliosis standing |
| `http://loinc.org` | `30719-9` | Temporomandibular joint X-ray tomograph |
| `http://loinc.org` | `30720-7` | Orbit - bilateral X-ray for foreign body |
| `http://loinc.org` | `30721-5` | Sinuses X-ray PA and lateral |
| `http://loinc.org` | `30722-3` | Skull X-ray Single view portable |
| `http://loinc.org` | `30723-1` | Skull X-ray portable |
| `http://loinc.org` | `30724-9` | Spine Cervical X-ray Single view portable |
| `http://loinc.org` | `30725-6` | Spine Cervical X-ray AP single view |
| `http://loinc.org` | `30726-4` | Spine Cervical X-ray AP and lateral portable |
| `http://loinc.org` | `30727-2` | Spine Cervical X-ray AP portable single view |
| `http://loinc.org` | `30729-8` | Spine Cervical Odontoid and Cervical axis X-ray AP portable single view |
| `http://loinc.org` | `30730-6` | Zygomatic arch - bilateral X-ray portable |
| `http://loinc.org` | `30731-4` | Zygomatic arch X-ray portable |
| `http://loinc.org` | `30733-0` | Chest X-ray right and left oblique portable |
| `http://loinc.org` | `30734-8` | Chest X-ray AP lateral-decubitus |
| `http://loinc.org` | `30735-5` | Chest X-ray AP lateral-decubitus portable |
| `http://loinc.org` | `30736-3` | Chest X-ray W inspiration and expiration |
| `http://loinc.org` | `30737-1` | Chest X-ray left lateral |
| `http://loinc.org` | `30738-9` | Chest X-ray left lateral portable |
| `http://loinc.org` | `30739-7` | Chest X-ray right or-left oblique portable |
| `http://loinc.org` | `30740-5` | Chest X-ray right or-left oblique |
| `http://loinc.org` | `30741-3` | Chest X-ray PA and lateral and lordotic upright |
| `http://loinc.org` | `30742-1` | Chest X-ray PA and lateral and right oblique and left oblique |
| `http://loinc.org` | `30743-9` | Chest X-ray PA and lateral and right oblique and left oblique portable |
| `http://loinc.org` | `30744-7` | Chest X-ray PA and lateral and right or-left oblique |
| `http://loinc.org` | `30745-4` | Chest X-ray |
| `http://loinc.org` | `30746-2` | Chest X-ray portable |
| `http://loinc.org` | `30747-0` | Ribs X-ray portable |
| `http://loinc.org` | `30748-8` | Shoulder X-ray Single view |
| `http://loinc.org` | `30749-6` | Shoulder X-ray Single view portable |
| `http://loinc.org` | `30750-4` | Shoulder X-ray 5 views |
| `http://loinc.org` | `30751-2` | Shoulder X-ray West Point |
| `http://loinc.org` | `30752-0` | Spine Thoracic X-ray AP single view |
| `http://loinc.org` | `30753-8` | Spine Thoracic X-ray AP and lateral |
| `http://loinc.org` | `30754-6` | Spine Thoracic X-ray AP and lateral portable |
| `http://loinc.org` | `30755-3` | Spine Thoracic X-ray AP portable single view |
| `http://loinc.org` | `30756-1` | Spine Thoracic X-ray lateral |
| `http://loinc.org` | `30757-9` | Spine Thoracic X-ray lateral portable |
| `http://loinc.org` | `30758-7` | Spine Thoracic X-ray oblique single view |
| `http://loinc.org` | `30759-5` | Spine Thoracic X-ray oblique portable |
| `http://loinc.org` | `30760-3` | Kidney - bilateral X-ray tomograph 3 views W contrast IV |
| `http://loinc.org` | `30761-1` | Kidney - bilateral Fluoroscopy W contrast retrograde via urethra |
| `http://loinc.org` | `30762-9` | Abdomen X-ray tomograph |
| `http://loinc.org` | `30763-7` | Abdomen X-ray AP and lateral crosstable portable |
| `http://loinc.org` | `30764-5` | Acetabulum - bilateral X-ray portable |
| `http://loinc.org` | `30765-2` | Acetabulum X-ray portable |
| `http://loinc.org` | `30766-0` | Pelvis X-ray 3 views |
| `http://loinc.org` | `30767-8` | Pelvis and Hip X-ray |
| `http://loinc.org` | `30768-6` | Pelvis and Hip - bilateral X-ray |
| `http://loinc.org` | `30769-4` | Pelvis and Hip - bilateral X-ray max abduction |
| `http://loinc.org` | `30770-2` | Pelvis and Hip X-ray AP and lateral frog |
| `http://loinc.org` | `30771-0` | Pelvis X-ray inlet and outlet |
| `http://loinc.org` | `30772-8` | Pelvis X-ray portable |
| `http://loinc.org` | `30773-6` | Spine Lumbar X-ray Single view |
| `http://loinc.org` | `30774-4` | Spine Lumbar X-ray Single view portable |
| `http://loinc.org` | `30775-1` | Spine Lumbar X-ray 3 views |
| `http://loinc.org` | `30776-9` | Spine Lumbar X-ray 3 views portable |
| `http://loinc.org` | `30777-7` | Spine Lumbar X-ray AP single view |
| `http://loinc.org` | `30778-5` | Spine Lumbar X-ray oblique single view |
| `http://loinc.org` | `30779-3` | Ankle X-ray AP and lateral |
| `http://loinc.org` | `30780-1` | Finger second X-ray |
| `http://loinc.org` | `30781-9` | Finger third X-ray |
| `http://loinc.org` | `30782-7` | Finger fourth X-ray |
| `http://loinc.org` | `30783-5` | Finger fifth X-ray |
| `http://loinc.org` | `30784-3` | Foot X-ray 2 views |
| `http://loinc.org` | `30785-0` | Foot X-ray W forced dorsiflexion |
| `http://loinc.org` | `30786-8` | Hip X-ray lateral frog |
| `http://loinc.org` | `30787-6` | Joint X-ray Single view |
| `http://loinc.org` | `30788-4` | Knee X-ray 3 views |
| `http://loinc.org` | `30789-2` | Knee X-ray 4 views |
| `http://loinc.org` | `30790-0` | Knee X-ray tunnel |
| `http://loinc.org` | `30791-8` | Patella X-ray |
| `http://loinc.org` | `30792-6` | Patella X-ray portable |
| `http://loinc.org` | `30793-4` | Wrist X-ray AP and lateral |
| `http://loinc.org` | `30794-2` | Breast MRI |
| `http://loinc.org` | `30795-9` | Breast - bilateral MRI |
| `http://loinc.org` | `30796-7` | Elbow MRI WO contrast |
| `http://loinc.org` | `30797-5` | Spine Lumbar X-ray 5 views |
| `http://loinc.org` | `30799-1` | Head CT WO contrast |
| `http://loinc.org` | `30800-7` | MRI Guidance.stereotactic for localization in Brain-- WO contrast |
| `http://loinc.org` | `30801-5` | Facial bones and Maxilla CT W contrast IV |
| `http://loinc.org` | `30802-3` | Facial bones and Maxilla CT WO contrast |
| `http://loinc.org` | `30803-1` | Facial bones and Maxilla CT W and WO contrast IV |
| `http://loinc.org` | `30804-9` | Chest vessels CT angiogram W and WO contrast IV |
| `http://loinc.org` | `30805-6` | Abdominal vessels CT angiogram W and WO contrast IV |
| `http://loinc.org` | `30806-4` | Aorta and Femoral artery - bilateral CT angiogram W and WO contrast IV |
| `http://loinc.org` | `30807-2` | Lower extremity vessels CT angiogram W and WO contrast IV |
| `http://loinc.org` | `30808-0` | Spine Cervical and Thoracic and Lumbar Fluoroscopy W contrast IT |
| `http://loinc.org` | `30809-8` | Upper Gastrointestine and Small bowel Fluoroscopy W contrast PO |
| `http://loinc.org` | `30810-6` | Lacrimal duct Fluoroscopy W contrast intra lacrimal duct |
| `http://loinc.org` | `30811-4` | Posterior fossa Fluoroscopy W contrast IT |
| `http://loinc.org` | `30812-2` | Fluoroscopy Guidance for injection of Spine Cervical Facet Joint |
| `http://loinc.org` | `30813-0` | Lung - bilateral X-ray W contrast intrabronchial |
| `http://loinc.org` | `30814-8` | Fluoroscopy Guidance for injection of Spine Thoracic Facet Joint |
| `http://loinc.org` | `30815-5` | Fluoroscopy Guidance for endoscopy of Biliary ducts and Pancreatic duct-- W contrast retrograde |
| `http://loinc.org` | `30816-3` | Peritoneum Fluoroscopic angiogram W contrast percutaneous |
| `http://loinc.org` | `30817-1` | Fluoroscopy Guidance for injection of Spine Lumbar Facet Joint |
| `http://loinc.org` | `30818-9` | Fluoroscopy Guidance for catheterization of Fallopian tubes-- transcervical |
| `http://loinc.org` | `30819-7` | Epidural veins Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `30820-5` | Carotid artery.external - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `30821-3` | Carotid artery.external Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `30822-1` | Head artery - bilateral and Neck artery - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `30823-9` | Head artery and Neck artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `30824-7` | Intercranial vessel and Neck Vessel Fluoroscopic angiogram W contrast |
| `http://loinc.org` | `30825-4` | Orbit veins Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `30826-2` | Sagittal sinus and Jugular veins Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `30827-0` | Sagittal sinus vein Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `30828-8` | Brachial artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `30829-6` | Internal mammary artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `30830-4` | Pulmonary artery - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `30831-2` | Adrenal artery - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `30832-0` | Adrenal artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `30833-8` | Pelvis arteries Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `30834-6` | Renal artery - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `30836-1` | Visceral artery Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `30837-9` | Aorta abdominal Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `30838-7` | Aorta and Femoral artery - bilateral Fluoroscopic angiogram runoff W contrast IA |
| `http://loinc.org` | `30839-5` | Lymphatics abdominal Fluoroscopy W contrast intra lymphatic |
| `http://loinc.org` | `30840-3` | Lymphatics abdominal - bilateral Fluoroscopy W contrast intra lymphatic |
| `http://loinc.org` | `30841-1` | Portal vein Fluoroscopic angiogram W contrast transhepatic |
| `http://loinc.org` | `30842-9` | Portal vein Fluoroscopic angiogram W contrast transhepatic and W hemodynamics |
| `http://loinc.org` | `30843-7` | Adrenal vein Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `30844-5` | Adrenal vein - bilateral Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `30845-2` | Inferior vena cava Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `30846-0` | Renal vein - bilateral Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `30847-8` | Renal vein Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `30848-6` | Extremity arteries Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `30849-4` | Extremity arteries - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `30850-2` | Extremity lymphatics Fluoroscopy W contrast intra lymphatic |
| `http://loinc.org` | `30851-0` | Extremity lymphatics - bilateral Fluoroscopy W contrast intra lymphatic |
| `http://loinc.org` | `30852-8` | Peripheral veins - bilateral Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `30853-6` | Breast duct US W contrast intra duct |
| `http://loinc.org` | `30854-4` | Spine Cervical and Thoracic and Lumbar MRI WO contrast |
| `http://loinc.org` | `30855-1` | Spine Cervical and Thoracic and Lumbar MRI W and WO contrast IV |
| `http://loinc.org` | `30856-9` | Head vessels MRI angiogram |
| `http://loinc.org` | `30857-7` | Nerves cranial MRI |
| `http://loinc.org` | `30858-5` | Head veins MRI angiogram |
| `http://loinc.org` | `30859-3` | Carotid vessels and Neck Vessels MRI angiogram |
| `http://loinc.org` | `30860-1` | Nasopharynx MRI |
| `http://loinc.org` | `30861-9` | Aortic arch and Neck vessels MRI angiogram |
| `http://loinc.org` | `30862-7` | Chest vessels MRI angiogram |
| `http://loinc.org` | `30863-5` | Abdominal Aorta and Arteries MRI angiogram |
| `http://loinc.org` | `30864-3` | Abdominal veins and IVC MRI angiogram |
| `http://loinc.org` | `30865-0` | Celiac vessels and Superior mesenteric Vessels MRI angiogram |
| `http://loinc.org` | `30866-8` | Lumbar plexus MRI |
| `http://loinc.org` | `30867-6` | Pelvis vessels MRI angiogram |
| `http://loinc.org` | `30868-4` | Renal vessels MRI angiogram |
| `http://loinc.org` | `30869-2` | Lower leg MRI WO contrast |
| `http://loinc.org` | `30870-0` | Lower leg MRI W and WO contrast IV |
| `http://loinc.org` | `30871-8` | Femoral vessels MRI angiogram |
| `http://loinc.org` | `30872-6` | Foot vessels MRI angiogram |
| `http://loinc.org` | `30873-4` | Forearm vessels MRI angiogram |
| `http://loinc.org` | `30874-2` | Lower extremity vessels MRI angiogram |
| `http://loinc.org` | `30875-9` | Upper extremity .joint MRI |
| `http://loinc.org` | `30876-7` | Extremity veins MRI angiogram |
| `http://loinc.org` | `30877-5` | Kidney - bilateral and Renal vessels Scan |
| `http://loinc.org` | `30878-3` | US Guidance for aspiration of Unspecified body region |
| `http://loinc.org` | `30880-9` | Head vessels and Neck vessels US.doppler |
| `http://loinc.org` | `30881-7` | Lower extremity vein US.doppler |
| `http://loinc.org` | `30882-5` | Upper extremity vein US.doppler |
| `http://loinc.org` | `30883-3` | Coccyx X-ray |
| `http://loinc.org` | `30884-1` | Sacrum X-ray |
| `http://loinc.org` | `30885-8` | Pelvis symphysis pubis X-ray |
| `http://loinc.org` | `30887-4` | Renal vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `30888-2` | Tibioperoneal vessels MRI angiogram |
| `http://loinc.org` | `30889-0` | Temporomandibular joint - left X-ray |
| `http://loinc.org` | `30890-8` | Temporomandibular joint - right X-ray |
| `http://loinc.org` | `30891-6` | Cervicocerebral artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `30892-4` | Fluoroscopy Guidance for catheterization of Biliary ducts and Pancreatic duct-- W contrast retrograde |
| `http://loinc.org` | `33716-2` | Non-gynecological cytology method study |
| `http://loinc.org` | `33717-0` | Cytology Cervical or vaginal smear or scraping study |
| `http://loinc.org` | `33718-8` | Cytology report of Tissue fine needle aspirate Cyto stain |
| `http://loinc.org` | `33719-6` | Flow cytometry study |
| `http://loinc.org` | `33720-4` | Blood bank consult |
| `http://loinc.org` | `33721-2` | Bone marrow Pathology biopsy report |
| `http://loinc.org` | `34066-1` | FDA package insert Boxed warning section |
| `http://loinc.org` | `34067-9` | FDA package insert Indications and usage section |
| `http://loinc.org` | `34068-7` | FDA package insert Dosage and administration section |
| `http://loinc.org` | `34069-5` | FDA package insert How supplied section |
| `http://loinc.org` | `34070-3` | FDA package insert Contraindications section |
| `http://loinc.org` | `34071-1` | FDA package insert Warnings section |
| `http://loinc.org` | `34072-9` | FDA package insert General precautions section |
| `http://loinc.org` | `34073-7` | FDA package insert Drug interactions section |
| `http://loinc.org` | `34074-5` | FDA package insert Drug/laboratory test interactions section |
| `http://loinc.org` | `34075-2` | FDA package insert Laboratory tests section |
| `http://loinc.org` | `34076-0` | FDA package insert Information for patients section |
| `http://loinc.org` | `34077-8` | FDA package insert Teratogenic effects section |
| `http://loinc.org` | `34078-6` | FDA package insert Nonteratogenic effects section |
| `http://loinc.org` | `34079-4` | FDA package insert Labor and delivery section |
| `http://loinc.org` | `34080-2` | FDA package insert Nursing mothers section |
| `http://loinc.org` | `34081-0` | FDA package insert Pediatric use section |
| `http://loinc.org` | `34082-8` | FDA package insert Geriatric use section |
| `http://loinc.org` | `34083-6` | FDA package insert Carcinogenesis and mutagenesis and impairment of fertility section |
| `http://loinc.org` | `34084-4` | FDA package insert Adverse reactions section |
| `http://loinc.org` | `34085-1` | FDA package insert Controlled substance section |
| `http://loinc.org` | `34086-9` | FDA package insert Abuse section |
| `http://loinc.org` | `34087-7` | FDA package insert Dependence section |
| `http://loinc.org` | `34088-5` | FDA package insert Overdosage section |
| `http://loinc.org` | `34089-3` | FDA package insert Description section |
| `http://loinc.org` | `34090-1` | FDA package insert Clinical pharmacology section |
| `http://loinc.org` | `34091-9` | FDA package insert Animal pharmacology/toxicology section |
| `http://loinc.org` | `34092-7` | FDA package insert Clinical studies section |
| `http://loinc.org` | `34093-5` | FDA package insert References section |
| `http://loinc.org` | `34094-3` | Cardiology Hospital Admission history and physical note |
| `http://loinc.org` | `34095-0` | Comprehensive history and physical note |
| `http://loinc.org` | `34096-8` | Nursing facility Comprehensive history and physical note |
| `http://loinc.org` | `34097-6` | Nursing facility Conference note |
| `http://loinc.org` | `34098-4` | Conference note |
| `http://loinc.org` | `34099-2` | Cardiology Consult note |
| `http://loinc.org` | `34100-8` | Intensive care unit Consult note |
| `http://loinc.org` | `34101-6` | General medicine Outpatient Consult note |
| `http://loinc.org` | `34102-4` | Psychiatry Hospital Consult note |
| `http://loinc.org` | `34103-2` | Pulmonary Consult note |
| `http://loinc.org` | `34104-0` | Hospital Consult note |
| `http://loinc.org` | `34105-7` | Hospital Discharge summary |
| `http://loinc.org` | `34106-5` | Physician Hospital Discharge summary |
| `http://loinc.org` | `34107-3` | Patient's home Education note |
| `http://loinc.org` | `34108-1` | Outpatient Note |
| `http://loinc.org` | `34109-9` | Note |
| `http://loinc.org` | `34110-7` | Diabetology Outpatient Note |
| `http://loinc.org` | `34111-5` | Emergency department Note |
| `http://loinc.org` | `34112-3` | Hospital Note |
| `http://loinc.org` | `34113-1` | Nursing facility Note |
| `http://loinc.org` | `34114-9` | Hospital Group counseling note |
| `http://loinc.org` | `34115-6` | Medical student Hospital History and physical note |
| `http://loinc.org` | `34116-4` | Physician Nursing facility History and physical note |
| `http://loinc.org` | `34117-2` | History and physical note |
| `http://loinc.org` | `34118-0` | Patient's home Initial assessment note |
| `http://loinc.org` | `34119-8` | Nursing facility Initial assessment note |
| `http://loinc.org` | `34120-6` | Outpatient Initial assessment note |
| `http://loinc.org` | `34121-4` | Interventional procedure note |
| `http://loinc.org` | `34122-2` | Pathology procedure note |
| `http://loinc.org` | `34123-0` | Anesthesiology Hospital Preoperative evaluation and management note |
| `http://loinc.org` | `34124-8` | Cardiology Outpatient Progress note |
| `http://loinc.org` | `34125-5` | Case manager Patient's home Progress note |
| `http://loinc.org` | `34126-3` | Intensive care unit Progress note |
| `http://loinc.org` | `34127-1` | Dentistry Hygienist Outpatient Progress note |
| `http://loinc.org` | `34128-9` | Dentistry Outpatient Progress note |
| `http://loinc.org` | `34129-7` | Patient's home Progress note |
| `http://loinc.org` | `34130-5` | Hospital Progress note |
| `http://loinc.org` | `34131-3` | Outpatient Progress note |
| `http://loinc.org` | `34132-1` | Pharmacy Outpatient Progress note |
| `http://loinc.org` | `34133-9` | Summary of episode note |
| `http://loinc.org` | `34134-7` | Physician attending Outpatient Supervisory note |
| `http://loinc.org` | `34135-4` | Cardiology Physician attending Outpatient Supervisory note |
| `http://loinc.org` | `34136-2` | Gastroenterology Physician attending Outpatient Supervisory note |
| `http://loinc.org` | `34137-0` | Outpatient Surgical operation note |
| `http://loinc.org` | `34138-8` | Targeted history and physical note |
| `http://loinc.org` | `34139-6` | Nurse Telephone encounter Note |
| `http://loinc.org` | `34744-3` | Nurse Admission evaluation note |
| `http://loinc.org` | `34745-0` | Nurse Discharge summary |
| `http://loinc.org` | `34746-8` | Nurse Note |
| `http://loinc.org` | `34747-6` | Nurse Preoperative evaluation and management note |
| `http://loinc.org` | `34748-4` | Telephone encounter Note |
| `http://loinc.org` | `34749-2` | Anesthesiology Outpatient Consult note |
| `http://loinc.org` | `34750-0` | Anesthesiology Note |
| `http://loinc.org` | `34751-8` | Anesthesiology Preoperative evaluation and management note |
| `http://loinc.org` | `34752-6` | Cardiology Note |
| `http://loinc.org` | `34753-4` | Cardiology Outpatient Note |
| `http://loinc.org` | `34754-2` | Critical Care Medicine Note |
| `http://loinc.org` | `34755-9` | Critical care medicine Transfer summary note |
| `http://loinc.org` | `34756-7` | Dentistry Consult note |
| `http://loinc.org` | `34758-3` | Dermatology Consult note |
| `http://loinc.org` | `34759-1` | Dermatology Note |
| `http://loinc.org` | `34760-9` | Diabetology Consult note |
| `http://loinc.org` | `34761-7` | Gastroenterology Consult note |
| `http://loinc.org` | `34762-5` | Gastroenterology Note |
| `http://loinc.org` | `34763-3` | General medicine Admission history and physical note |
| `http://loinc.org` | `34764-1` | General medicine Consult note |
| `http://loinc.org` | `34765-8` | General medicine Note |
| `http://loinc.org` | `34766-6` | General medicine Outpatient Note |
| `http://loinc.org` | `34767-4` | General medicine Medical student Note |
| `http://loinc.org` | `34768-2` | General medicine Nurse Note |
| `http://loinc.org` | `34769-0` | General medicine Physician attending Note |
| `http://loinc.org` | `34770-8` | General medicine Transfer summary note |
| `http://loinc.org` | `34773-2` | Surgery Physician attending Note |
| `http://loinc.org` | `34774-0` | Surgery History and physical note |
| `http://loinc.org` | `34776-5` | Geriatric medicine Consult note |
| `http://loinc.org` | `34777-3` | Obstetrics and Gynecology Consult note |
| `http://loinc.org` | `34778-1` | Obstetrics and Gynecology Note |
| `http://loinc.org` | `34779-9` | Hematology+Medical Oncology Consult note |
| `http://loinc.org` | `34780-7` | Hematology+Medical Oncology Note |
| `http://loinc.org` | `34781-5` | Infectious disease Consult note |
| `http://loinc.org` | `34782-3` | Infectious disease Note |
| `http://loinc.org` | `34783-1` | Kinesiotherapy Consult note |
| `http://loinc.org` | `34784-9` | Kinesiotherapy Note |
| `http://loinc.org` | `34785-6` | Mental health Consult note |
| `http://loinc.org` | `34786-4` | Mental health Note |
| `http://loinc.org` | `34787-2` | Mental health Group counseling note |
| `http://loinc.org` | `34788-0` | Psychiatry Consult note |
| `http://loinc.org` | `34790-6` | Psychiatry Group counseling note |
| `http://loinc.org` | `34791-4` | Psychology Consult note |
| `http://loinc.org` | `34792-2` | Psychology Note |
| `http://loinc.org` | `34793-0` | Psychology Group counseling note |
| `http://loinc.org` | `34794-8` | Interdisciplinary Note |
| `http://loinc.org` | `34795-5` | Nephrology Consult note |
| `http://loinc.org` | `34796-3` | Nephrology Note |
| `http://loinc.org` | `34797-1` | Neurology Consult note |
| `http://loinc.org` | `34798-9` | Neurological surgery Consult note |
| `http://loinc.org` | `34799-7` | Neurological surgery Note |
| `http://loinc.org` | `34800-3` | Nutrition and dietetics Consult note |
| `http://loinc.org` | `34801-1` | Nutrition and dietetics Note |
| `http://loinc.org` | `34802-9` | Occupational medicine Note |
| `http://loinc.org` | `34803-7` | Occupational medicine Consult note |
| `http://loinc.org` | `34805-2` | Oncology Consult note |
| `http://loinc.org` | `34806-0` | Oncology Note |
| `http://loinc.org` | `34807-8` | Ophthalmology Consult note |
| `http://loinc.org` | `34808-6` | Ophthalmology Note |
| `http://loinc.org` | `34809-4` | Ophthalmology Preoperative evaluation and management note |
| `http://loinc.org` | `34810-2` | Optometry Consult note |
| `http://loinc.org` | `34811-0` | Optometry Note |
| `http://loinc.org` | `34812-8` | Oral and Maxillofacial Surgery Consult note |
| `http://loinc.org` | `34813-6` | Oral and Maxillofacial Surgery Note |
| `http://loinc.org` | `34814-4` | Orthopaedic surgery Consult note |
| `http://loinc.org` | `34815-1` | Orthopaedic surgery Note |
| `http://loinc.org` | `34816-9` | Otolaryngology Consult note |
| `http://loinc.org` | `34817-7` | Otolaryngology Note |
| `http://loinc.org` | `34818-5` | Otolaryngology Surgical operation note |
| `http://loinc.org` | `34819-3` | Pathology Evaluation and management note |
| `http://loinc.org` | `34820-1` | Pharmacy Consult note |
| `http://loinc.org` | `34821-9` | Pharmacy Note |
| `http://loinc.org` | `34822-7` | Physical medicine and rehabilitation Consult note |
| `http://loinc.org` | `34823-5` | Physical medicine and rehabilitation Note |
| `http://loinc.org` | `34824-3` | Physical therapy Consult note |
| `http://loinc.org` | `34826-8` | Plastic surgery Consult note |
| `http://loinc.org` | `34827-6` | Plastic surgery Note |
| `http://loinc.org` | `34828-4` | Podiatry Consult note |
| `http://loinc.org` | `34829-2` | Podiatry Note |
| `http://loinc.org` | `34830-0` | Pulmonary Note |
| `http://loinc.org` | `34831-8` | Radiation oncology Consult note |
| `http://loinc.org` | `34832-6` | Radiation oncology Note |
| `http://loinc.org` | `34833-4` | Recreational therapy Consult note |
| `http://loinc.org` | `34834-2` | Recreational therapy Note |
| `http://loinc.org` | `34837-5` | Respiratory therapy Consult note |
| `http://loinc.org` | `34838-3` | Respiratory therapy Note |
| `http://loinc.org` | `34839-1` | Rheumatology Consult note |
| `http://loinc.org` | `34840-9` | Rheumatology Note |
| `http://loinc.org` | `34841-7` | Social work Consult note |
| `http://loinc.org` | `34843-3` | Social work Group counseling note |
| `http://loinc.org` | `34844-1` | Social work Telephone encounter Note |
| `http://loinc.org` | `34845-8` | Speech-language pathology+Audiology Consult note |
| `http://loinc.org` | `34846-6` | Speech-language pathology+Audiology Note |
| `http://loinc.org` | `34847-4` | Surgery Consult note |
| `http://loinc.org` | `34848-2` | Surgery Note |
| `http://loinc.org` | `34849-0` | Thoracic surgery Consult note |
| `http://loinc.org` | `34850-8` | Thoracic surgery Outpatient Note |
| `http://loinc.org` | `34851-6` | Urology Consult note |
| `http://loinc.org` | `34852-4` | Urology Note |
| `http://loinc.org` | `34853-2` | Vascular surgery Consult note |
| `http://loinc.org` | `34854-0` | Vascular surgery Outpatient Note |
| `http://loinc.org` | `34855-7` | Occupational therapy Consult note |
| `http://loinc.org` | `34856-5` | Evaluation and management of anticoagulation note |
| `http://loinc.org` | `34857-3` | Evaluation and management of substance abuse note |
| `http://loinc.org` | `34858-1` | Pain medicine Note |
| `http://loinc.org` | `34859-9` | Evaluation and management of hyperlipidemia |
| `http://loinc.org` | `34860-7` | Evaluation and management of hypertension |
| `http://loinc.org` | `34861-5` | Diabetology Note |
| `http://loinc.org` | `34862-3` | General medicine Physician attending Hospital Admission evaluation note |
| `http://loinc.org` | `34864-9` | Mental health Counseling note |
| `http://loinc.org` | `34865-6` | Psychiatry Counseling note |
| `http://loinc.org` | `34866-4` | Psychology Counseling note |
| `http://loinc.org` | `34867-2` | Ophthalmology Outpatient Postoperative evaluation and management note |
| `http://loinc.org` | `34868-0` | Orthopaedic surgery Surgical operation note |
| `http://loinc.org` | `34869-8` | Pharmacy Counseling note |
| `http://loinc.org` | `34870-6` | Plastic surgery Surgical operation note |
| `http://loinc.org` | `34872-2` | Social work Counseling note |
| `http://loinc.org` | `34873-0` | Surgery Admission evaluation note |
| `http://loinc.org` | `34874-8` | Surgery Surgical operation note |
| `http://loinc.org` | `34875-5` | Surgery Postoperative evaluation and management note |
| `http://loinc.org` | `34876-3` | Surgery Preoperative evaluation and management note |
| `http://loinc.org` | `34877-1` | Urology Surgical operation note |
| `http://loinc.org` | `34878-9` | Emergency medicine Note |
| `http://loinc.org` | `34879-7` | Endocrinology Consult note |
| `http://loinc.org` | `34880-5` | Surgery Nurse Postoperative evaluation and management note |
| `http://loinc.org` | `34881-3` | Surgery Nurse Preoperative evaluation and management note |
| `http://loinc.org` | `34895-3` | Education note |
| `http://loinc.org` | `34896-1` | Cardiology Interventional procedure note |
| `http://loinc.org` | `34897-9` | Diabetology Education note |
| `http://loinc.org` | `34898-7` | Endocrinology Note |
| `http://loinc.org` | `34899-5` | Gastroenterology Interventional procedure note |
| `http://loinc.org` | `34900-1` | General medicine Progress note |
| `http://loinc.org` | `34901-9` | General medicine Outpatient Progress note |
| `http://loinc.org` | `34902-7` | Geriatric medicine Outpatient Education note |
| `http://loinc.org` | `34904-3` | Mental health Progress note |
| `http://loinc.org` | `34905-0` | Neurology Note |
| `http://loinc.org` | `34906-8` | Pastoral care Note |
| `http://loinc.org` | `35510-7` | Clinical trial protocol General information section |
| `http://loinc.org` | `35511-5` | Clinical trial protocol Background information section |
| `http://loinc.org` | `35512-3` | Clinical trial protocol Trial objectives and purpose section |
| `http://loinc.org` | `35513-1` | Clinical trial protocol Trial design section |
| `http://loinc.org` | `35514-9` | Clinical trial protocol Subject selection and withdrawal section |
| `http://loinc.org` | `35515-6` | Clinical trial protocol Subject participation + epochs section |
| `http://loinc.org` | `35516-4` | Clinical trial protocol Treatment of subjects + epochs section |
| `http://loinc.org` | `35517-2` | Clinical trial protocol Assessment section |
| `http://loinc.org` | `35518-0` | Clinical trial protocol Efficacy assessment section |
| `http://loinc.org` | `35519-8` | Clinical trial protocol Assessment of safety section |
| `http://loinc.org` | `35520-6` | Clinical trial protocol Statistics section |
| `http://loinc.org` | `35521-4` | Clinical trial protocol Direct access to source data+documents section |
| `http://loinc.org` | `35522-2` | Clinical trial protocol Quality control and quality assurance section |
| `http://loinc.org` | `35523-0` | Clinical trial protocol Ethics section |
| `http://loinc.org` | `35524-8` | Clinical trial protocol Data handling and record keeping section |
| `http://loinc.org` | `35525-5` | Clinical trial protocol Financing and insurance section |
| `http://loinc.org` | `35526-3` | Clinical trial protocol Publication policy section |
| `http://loinc.org` | `35527-1` | Clinical trial protocol Supplements section |
| `http://loinc.org` | `35528-9` | Clinical trial protocol Clinical trial protocol |
| `http://loinc.org` | `35881-2` | Extremity artery Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `35882-0` | Inferior vena cava Fluoroscopic angiogram Angioplasty W contrast IV |
| `http://loinc.org` | `35883-8` | Aorta Fluoroscopic angiogram Atherectomy W contrast IA |
| `http://loinc.org` | `35884-6` | CT Guidance for abscess drainage of Abdomen |
| `http://loinc.org` | `35885-3` | Fluoroscopy Guidance for abscess drainage of Unspecified body region |
| `http://loinc.org` | `35886-1` | CT Guidance for aspiration of Breast |
| `http://loinc.org` | `35887-9` | CT Guidance for aspiration of cyst of Unspecified body region |
| `http://loinc.org` | `35888-7` | Fluoroscopy Guidance for aspiration of Hip |
| `http://loinc.org` | `35889-5` | Fluoroscopy Guidance for bronchoscopy of Chest |
| `http://loinc.org` | `35890-3` | Fluoroscopy Guidance for biopsy of Abdomen |
| `http://loinc.org` | `35891-1` | CT Guidance for biopsy of Bone |
| `http://loinc.org` | `35892-9` | CT Guidance for biopsy of Head |
| `http://loinc.org` | `35893-7` | CT Guidance for biopsy of Breast |
| `http://loinc.org` | `35894-5` | Fluoroscopy Guidance for biopsy of Chest |
| `http://loinc.org` | `35895-2` | CT Guidance for biopsy of Chest |
| `http://loinc.org` | `35896-0` | CT Guidance for biopsy of Lower extremity |
| `http://loinc.org` | `35897-8` | CT Guidance for biopsy of Upper extremity |
| `http://loinc.org` | `35898-6` | CT Guidance for biopsy of Salivary gland |
| `http://loinc.org` | `35899-4` | Fluoroscopy Guidance for biopsy of Kidney |
| `http://loinc.org` | `35900-0` | Fluoroscopy Guidance for biopsy of Liver |
| `http://loinc.org` | `35901-8` | CT Guidance for biopsy of Lymph node |
| `http://loinc.org` | `35902-6` | Fluoroscopy Guidance for biopsy of Pancreas |
| `http://loinc.org` | `35903-4` | CT Guidance for biopsy of Prostate |
| `http://loinc.org` | `35904-2` | CT Guidance for biopsy of Spine Cervical |
| `http://loinc.org` | `35905-9` | CT Guidance for biopsy of Spine Lumbar |
| `http://loinc.org` | `35906-7` | CT Guidance for biopsy of Spine Thoracic |
| `http://loinc.org` | `35907-5` | Fluoroscopy Guidance for biopsy of Spleen |
| `http://loinc.org` | `35908-3` | CT Guidance for biopsy of Thyroid |
| `http://loinc.org` | `35909-1` | CT Guidance for biopsy of Chest-- W contrast IV |
| `http://loinc.org` | `35910-9` | CT Guidance for biopsy of Chest-- W and WO contrast IV |
| `http://loinc.org` | `35911-7` | CT Guidance for biopsy of Chest-- WO contrast |
| `http://loinc.org` | `35912-5` | Fluoroscopy Guidance for placement of catheter in Unspecified body region |
| `http://loinc.org` | `35913-3` | CT Guidance for drainage of Abdomen |
| `http://loinc.org` | `35914-1` | CT Guidance for drainage of Anus |
| `http://loinc.org` | `35915-8` | CT Guidance for drainage of Appendix |
| `http://loinc.org` | `35916-6` | CT Guidance for drainage of Chest |
| `http://loinc.org` | `35917-4` | CT Guidance for drainage of Gallbladder |
| `http://loinc.org` | `35918-2` | CT Guidance for drainage of Kidney |
| `http://loinc.org` | `35919-0` | CT Guidance for drainage of Liver |
| `http://loinc.org` | `35920-8` | CT Guidance for drainage of Lymph node |
| `http://loinc.org` | `35921-6` | CT Guidance for drainage of Pelvis |
| `http://loinc.org` | `35922-4` | CT Guidance for drainage of Unspecified body region |
| `http://loinc.org` | `35923-2` | CT Guidance for drainage of Chest-- W contrast IV |
| `http://loinc.org` | `35924-0` | CT Guidance for drainage of Chest-- WO contrast |
| `http://loinc.org` | `35925-7` | Fluoroscopy Guidance for endoscopy of Stomach |
| `http://loinc.org` | `35926-5` | Fluoroscopy Guidance for gastrostomy of Stomach |
| `http://loinc.org` | `35927-3` | Fluoroscopy Guidance for injection of Sacroiliac Joint |
| `http://loinc.org` | `35928-1` | CT Guidance for localization of Breast - left |
| `http://loinc.org` | `35929-9` | CT Guidance for localization of Breast - right |
| `http://loinc.org` | `35930-7` | CT Guidance for nerve block of Abdomen |
| `http://loinc.org` | `35931-5` | CT Guidance for nerve block of Pelvis |
| `http://loinc.org` | `35932-3` | CT Guidance for nerve block of Spine Lumbar |
| `http://loinc.org` | `35933-1` | CT Guidance for percutaneous vertebroplasty of Spine |
| `http://loinc.org` | `35934-9` | CT Guidance for percutaneous vertebroplasty of Spine Lumbar |
| `http://loinc.org` | `35935-6` | CT Guidance for percutaneous vertebroplasty of Spine Thoracic |
| `http://loinc.org` | `35936-4` | Fluoroscopy Guidance for percutaneous vertebroplasty of Spine |
| `http://loinc.org` | `35937-2` | CT Guidance for placement of radiation therapy fields in Unspecified body region |
| `http://loinc.org` | `35938-0` | CT Guidance for placement of tube in Chest |
| `http://loinc.org` | `35939-8` | Ankle X-ray tomograph |
| `http://loinc.org` | `35940-6` | Ankle CT |
| `http://loinc.org` | `35941-4` | Ankle - bilateral CT |
| `http://loinc.org` | `35942-2` | Ankle - left CT |
| `http://loinc.org` | `35943-0` | Ankle - left X-ray tomograph |
| `http://loinc.org` | `35944-8` | Ankle - right CT |
| `http://loinc.org` | `35945-5` | Aorta CT |
| `http://loinc.org` | `35946-3` | Aorta MRI angiogram |
| `http://loinc.org` | `35947-1` | Aorta MRI |
| `http://loinc.org` | `35948-9` | Aorta abdominal CT |
| `http://loinc.org` | `35949-7` | Aorta abdominal MRI |
| `http://loinc.org` | `35950-5` | Aorta thoracic MRI |
| `http://loinc.org` | `35951-3` | Aortic arch MRI angiogram |
| `http://loinc.org` | `35952-1` | Appendix CT |
| `http://loinc.org` | `35953-9` | Face MRI |
| `http://loinc.org` | `35954-7` | Breast - left MRI |
| `http://loinc.org` | `35955-4` | Breast - right MRI |
| `http://loinc.org` | `35956-2` | Internal auditory canal MRI |
| `http://loinc.org` | `35957-0` | Internal auditory canal - left CT |
| `http://loinc.org` | `35958-8` | Internal auditory canal CT |
| `http://loinc.org` | `35959-6` | Clavicle X-ray tomograph |
| `http://loinc.org` | `35960-4` | Clavicle CT |
| `http://loinc.org` | `35961-2` | Clavicle MRI |
| `http://loinc.org` | `35962-0` | Elbow CT |
| `http://loinc.org` | `35963-8` | Elbow X-ray tomograph |
| `http://loinc.org` | `35964-6` | Elbow - bilateral X-ray tomograph |
| `http://loinc.org` | `35965-3` | Elbow - bilateral CT |
| `http://loinc.org` | `35966-1` | Elbow - left CT |
| `http://loinc.org` | `35967-9` | Elbow - left X-ray tomograph |
| `http://loinc.org` | `35968-7` | Elbow - right CT |
| `http://loinc.org` | `35969-5` | Esophagus CT |
| `http://loinc.org` | `35970-3` | Extremity X-ray tomograph |
| `http://loinc.org` | `35971-1` | Lower extremity CT |
| `http://loinc.org` | `35972-9` | Lower extremity X-ray tomograph |
| `http://loinc.org` | `35973-7` | Lower extremity - bilateral CT |
| `http://loinc.org` | `35974-5` | Lower extremity vessels - bilateral MRI angiogram |
| `http://loinc.org` | `35975-2` | Lower extremity - bilateral MRI |
| `http://loinc.org` | `35976-0` | Lower extremity - left CT |
| `http://loinc.org` | `35977-8` | Lower extremity - left X-ray tomograph |
| `http://loinc.org` | `35978-6` | Lower extremity - left MRI |
| `http://loinc.org` | `35979-4` | Lower extremity - right CT |
| `http://loinc.org` | `35980-2` | Lower extremity - right MRI |
| `http://loinc.org` | `35981-0` | Upper extremity CT |
| `http://loinc.org` | `35982-8` | Upper extremity - left CT |
| `http://loinc.org` | `35983-6` | Upper extremity - right CT |
| `http://loinc.org` | `35984-4` | Femur CT |
| `http://loinc.org` | `35985-1` | Femur X-ray tomograph |
| `http://loinc.org` | `35986-9` | Femur - bilateral X-ray tomograph |
| `http://loinc.org` | `35987-7` | Femur - left CT |
| `http://loinc.org` | `35988-5` | Femur - left X-ray tomograph |
| `http://loinc.org` | `35989-3` | Femur - right CT |
| `http://loinc.org` | `35990-1` | Fetal MRI |
| `http://loinc.org` | `35991-9` | Foot CT |
| `http://loinc.org` | `35992-7` | Foot X-ray tomograph |
| `http://loinc.org` | `35993-5` | Foot - bilateral CT |
| `http://loinc.org` | `35994-3` | Foot - left CT |
| `http://loinc.org` | `35995-0` | Foot - left X-ray tomograph |
| `http://loinc.org` | `35996-8` | Foot - right CT |
| `http://loinc.org` | `35997-6` | Forearm CT |
| `http://loinc.org` | `35998-4` | Forearm - bilateral CT |
| `http://loinc.org` | `35999-2` | Forearm - left CT |
| `http://loinc.org` | `36000-8` | Forearm - right CT |
| `http://loinc.org` | `36001-6` | Gallbladder X-ray tomograph |
| `http://loinc.org` | `36002-4` | Hand CT |
| `http://loinc.org` | `36003-2` | Hand X-ray tomograph |
| `http://loinc.org` | `36004-0` | Hand - bilateral CT |
| `http://loinc.org` | `36005-7` | Hand - left CT |
| `http://loinc.org` | `36006-5` | Hand - left X-ray tomograph |
| `http://loinc.org` | `36007-3` | Hand - right CT |
| `http://loinc.org` | `36008-1` | Wrist and Hand MRI |
| `http://loinc.org` | `36009-9` | Heart MRI angiogram |
| `http://loinc.org` | `36010-7` | Calcaneus CT |
| `http://loinc.org` | `36011-5` | Calcaneus X-ray tomograph |
| `http://loinc.org` | `36012-3` | Hip X-ray tomograph |
| `http://loinc.org` | `36013-1` | Hip MRI |
| `http://loinc.org` | `36014-9` | Hip CT |
| `http://loinc.org` | `36015-6` | Hip - bilateral X-ray tomograph |
| `http://loinc.org` | `36016-4` | Hip - bilateral CT |
| `http://loinc.org` | `36017-2` | Hip - bilateral MRI |
| `http://loinc.org` | `36018-0` | Hip - left CT |
| `http://loinc.org` | `36019-8` | Hip - left X-ray tomograph |
| `http://loinc.org` | `36020-6` | Hip - left MRI |
| `http://loinc.org` | `36021-4` | Hip - right CT |
| `http://loinc.org` | `36022-2` | Hip - right MRI |
| `http://loinc.org` | `36023-0` | Upper arm CT |
| `http://loinc.org` | `36024-8` | Humerus X-ray tomograph |
| `http://loinc.org` | `36025-5` | Upper arm MRI |
| `http://loinc.org` | `36026-3` | Upper arm - bilateral CT |
| `http://loinc.org` | `36027-1` | Upper arm - left CT |
| `http://loinc.org` | `36028-9` | Upper arm - left MRI |
| `http://loinc.org` | `36029-7` | Upper arm - right CT |
| `http://loinc.org` | `36030-5` | Upper arm - right MRI |
| `http://loinc.org` | `36031-3` | Sacroiliac Joint MRI |
| `http://loinc.org` | `36032-1` | Kidney X-ray tomograph |
| `http://loinc.org` | `36033-9` | Kidney MRI |
| `http://loinc.org` | `36034-7` | Kidney - bilateral MRI |
| `http://loinc.org` | `36035-4` | Kidney - left MRI |
| `http://loinc.org` | `36036-2` | Kidney - right MRI |
| `http://loinc.org` | `36037-0` | Knee CT |
| `http://loinc.org` | `36038-8` | Knee X-ray tomograph |
| `http://loinc.org` | `36039-6` | Knee - bilateral X-ray tomograph |
| `http://loinc.org` | `36040-4` | Knee - bilateral CT |
| `http://loinc.org` | `36041-2` | Knee - left CT |
| `http://loinc.org` | `36042-0` | Knee - left X-ray tomograph |
| `http://loinc.org` | `36043-8` | Knee - right CT |
| `http://loinc.org` | `36044-6` | Larynx X-ray tomograph |
| `http://loinc.org` | `36045-3` | Larynx MRI |
| `http://loinc.org` | `36046-1` | Liver MRI |
| `http://loinc.org` | `36047-9` | Mandible CT |
| `http://loinc.org` | `36048-7` | Mandible X-ray tomograph |
| `http://loinc.org` | `36049-5` | Maxilla and Mandible CT |
| `http://loinc.org` | `36050-3` | Maxilla CT |
| `http://loinc.org` | `36051-1` | Neck CT |
| `http://loinc.org` | `36052-9` | Pancreas MRI |
| `http://loinc.org` | `36053-7` | Parathyroid MRI |
| `http://loinc.org` | `36054-5` | Thoracic outlet CT |
| `http://loinc.org` | `36055-2` | Posterior fossa CT |
| `http://loinc.org` | `36056-0` | Posterior fossa MRI |
| `http://loinc.org` | `36057-8` | Prostate CT |
| `http://loinc.org` | `36058-6` | Sacrum CT |
| `http://loinc.org` | `36059-4` | Sacrum MRI |
| `http://loinc.org` | `36060-2` | Sacrum and Coccyx MRI |
| `http://loinc.org` | `36061-0` | Scapula MRI |
| `http://loinc.org` | `36062-8` | Shoulder CT |
| `http://loinc.org` | `36063-6` | Shoulder - bilateral CT |
| `http://loinc.org` | `36064-4` | Shoulder - left CT |
| `http://loinc.org` | `36065-1` | Shoulder - left X-ray tomograph |
| `http://loinc.org` | `36066-9` | Shoulder - right CT |
| `http://loinc.org` | `36067-7` | Spine MRI |
| `http://loinc.org` | `36068-5` | Spine Cervical X-ray tomograph |
| `http://loinc.org` | `36069-3` | Spine Lumbar X-ray tomograph |
| `http://loinc.org` | `36070-1` | Spleen MRI |
| `http://loinc.org` | `36071-9` | Sternum CT |
| `http://loinc.org` | `36072-7` | Sternum MRI |
| `http://loinc.org` | `36073-5` | Scrotum and Testicle MRI |
| `http://loinc.org` | `36074-3` | Lower leg CT |
| `http://loinc.org` | `36075-0` | Lower leg - left MRI |
| `http://loinc.org` | `36076-8` | Lower leg - right MRI |
| `http://loinc.org` | `36077-6` | Portal vein MRI angiogram |
| `http://loinc.org` | `36078-4` | Renal vein MRI angiogram |
| `http://loinc.org` | `36079-2` | Lower extremity veins MRI angiogram |
| `http://loinc.org` | `36080-0` | Upper extremity veins MRI angiogram |
| `http://loinc.org` | `36081-8` | Vena cava MRI angiogram |
| `http://loinc.org` | `36082-6` | Inferior vena cava MRI angiogram |
| `http://loinc.org` | `36083-4` | Inferior vena cava MRI |
| `http://loinc.org` | `36084-2` | Upper extremity vessels MRI angiogram |
| `http://loinc.org` | `36085-9` | Neck vessels MRI angiogram |
| `http://loinc.org` | `36086-7` | Abdomen CT limited |
| `http://loinc.org` | `36087-5` | Head CT limited |
| `http://loinc.org` | `36088-3` | Internal auditory canal MRI limited |
| `http://loinc.org` | `36089-1` | Chest CT limited |
| `http://loinc.org` | `36090-9` | Extremity CT limited |
| `http://loinc.org` | `36091-7` | Heart MRI limited |
| `http://loinc.org` | `36092-5` | Hip CT limited |
| `http://loinc.org` | `36093-3` | Lower Extremity Joint MRI limited |
| `http://loinc.org` | `36094-1` | Upper extremity .joint MRI limited |
| `http://loinc.org` | `36095-8` | Abdomen CT limited W contrast IV |
| `http://loinc.org` | `36096-6` | Brain MRI limited W contrast IV |
| `http://loinc.org` | `36097-4` | Upper extremity CT limited W contrast IV |
| `http://loinc.org` | `36098-2` | Pelvis CT limited W contrast IV |
| `http://loinc.org` | `36099-0` | Spine Cervical CT limited W contrast IV |
| `http://loinc.org` | `36100-6` | Spine Lumbar MRI limited W contrast IV |
| `http://loinc.org` | `36101-4` | Spine Thoracic MRI limited W contrast IV |
| `http://loinc.org` | `36102-2` | Abdomen CT limited W and WO contrast IV |
| `http://loinc.org` | `36103-0` | Abdomen CT limited WO contrast |
| `http://loinc.org` | `36104-8` | Head CT limited WO contrast |
| `http://loinc.org` | `36105-5` | Brain MRI limited WO contrast |
| `http://loinc.org` | `36106-3` | Lower extremity CT limited WO contrast |
| `http://loinc.org` | `36107-1` | Lower extremity joint - left MRI limited WO contrast |
| `http://loinc.org` | `36108-9` | Pelvis CT limited WO contrast |
| `http://loinc.org` | `36109-7` | Spine Cervical CT limited WO contrast |
| `http://loinc.org` | `36110-5` | Spine Lumbar CT limited WO contrast |
| `http://loinc.org` | `36111-3` | Spine Lumbar MRI limited WO contrast |
| `http://loinc.org` | `36112-1` | Spine Thoracic MRI limited WO contrast |
| `http://loinc.org` | `36113-9` | Kidney MRI W contrast IV |
| `http://loinc.org` | `36114-7` | Breast - bilateral MRI dynamic W contrast IV |
| `http://loinc.org` | `36115-4` | Ankle MRI W contrast intraarticular |
| `http://loinc.org` | `36116-2` | Ankle - left MRI W contrast intraarticular |
| `http://loinc.org` | `36117-0` | Ankle - right MRI W contrast intraarticular |
| `http://loinc.org` | `36118-8` | Elbow - left MRI W contrast intraarticular |
| `http://loinc.org` | `36119-6` | Elbow - right MRI W contrast intraarticular |
| `http://loinc.org` | `36120-4` | Hip MRI W contrast intraarticular |
| `http://loinc.org` | `36121-2` | Hip - left MRI W contrast intraarticular |
| `http://loinc.org` | `36122-0` | Hip - right MRI W contrast intraarticular |
| `http://loinc.org` | `36123-8` | Sacroiliac Joint CT W contrast intraarticular |
| `http://loinc.org` | `36124-6` | Knee CT W contrast intraarticular |
| `http://loinc.org` | `36125-3` | Knee MRI W contrast intraarticular |
| `http://loinc.org` | `36126-1` | Knee - left MRI W contrast intraarticular |
| `http://loinc.org` | `36127-9` | Knee - right MRI W contrast intraarticular |
| `http://loinc.org` | `36128-7` | Shoulder CT W contrast intraarticular |
| `http://loinc.org` | `36129-5` | Shoulder MRI W contrast intraarticular |
| `http://loinc.org` | `36130-3` | Shoulder - left MRI W contrast intraarticular |
| `http://loinc.org` | `36131-1` | Shoulder - right CT W contrast intraarticular |
| `http://loinc.org` | `36132-9` | Shoulder - right MRI W contrast intraarticular |
| `http://loinc.org` | `36134-5` | Abdomen MRI W contrast IV |
| `http://loinc.org` | `36135-2` | Ankle CT W contrast IV |
| `http://loinc.org` | `36136-0` | Ankle MRI W contrast IV |
| `http://loinc.org` | `36137-8` | Ankle - left CT W contrast IV |
| `http://loinc.org` | `36138-6` | Ankle - left MRI W contrast IV |
| `http://loinc.org` | `36139-4` | Ankle - right CT W contrast IV |
| `http://loinc.org` | `36140-2` | Ankle - right MRI W contrast IV |
| `http://loinc.org` | `36141-0` | Aorta CT angiogram W contrast IV |
| `http://loinc.org` | `36142-8` | Aorta CT W contrast IV |
| `http://loinc.org` | `36143-6` | Aorta abdominal CT W contrast IV |
| `http://loinc.org` | `36144-4` | Aortic arch CT angiogram W contrast IV |
| `http://loinc.org` | `36145-1` | Appendix CT W contrast IV |
| `http://loinc.org` | `36146-9` | Carotid artery CT angiogram W contrast IV |
| `http://loinc.org` | `36147-7` | Pulmonary artery CT angiogram W contrast IV |
| `http://loinc.org` | `36148-5` | Face MRI W contrast IV |
| `http://loinc.org` | `36149-3` | Breast MRI W contrast IV |
| `http://loinc.org` | `36150-1` | Breast - bilateral MRI W contrast IV |
| `http://loinc.org` | `36151-9` | Breast - left MRI W contrast IV |
| `http://loinc.org` | `36152-7` | Breast - right MRI W contrast IV |
| `http://loinc.org` | `36153-5` | Calcaneus - left CT W contrast IV |
| `http://loinc.org` | `36154-3` | Calcaneus - right CT W contrast IV |
| `http://loinc.org` | `36155-0` | Internal auditory canal MRI W contrast IV |
| `http://loinc.org` | `36156-8` | Chest MRI W contrast IV |
| `http://loinc.org` | `36157-6` | Elbow CT W contrast IV |
| `http://loinc.org` | `36158-4` | Elbow MRI W contrast IV |
| `http://loinc.org` | `36159-2` | Elbow - left CT W contrast IV |
| `http://loinc.org` | `36160-0` | Elbow - left MRI W contrast IV |
| `http://loinc.org` | `36161-8` | Elbow - right CT W contrast IV |
| `http://loinc.org` | `36162-6` | Elbow - right MRI W contrast IV |
| `http://loinc.org` | `36163-4` | Lower extremity - bilateral MRI W contrast IV |
| `http://loinc.org` | `36164-2` | Lower extremity - left CT W contrast IV |
| `http://loinc.org` | `36165-9` | Lower extremity - left MRI W contrast IV |
| `http://loinc.org` | `36166-7` | Lower extremity - right CT W contrast IV |
| `http://loinc.org` | `36167-5` | Lower extremity - right MRI W contrast IV |
| `http://loinc.org` | `36168-3` | Upper extremity - bilateral CT W contrast IV |
| `http://loinc.org` | `36169-1` | Upper extremity - left CT W contrast IV |
| `http://loinc.org` | `36170-9` | Upper extremity - right CT W contrast IV |
| `http://loinc.org` | `36171-7` | Upper extremity - right MRI W contrast IV |
| `http://loinc.org` | `36172-5` | Femur CT W contrast IV |
| `http://loinc.org` | `36173-3` | Thigh MRI W contrast IV |
| `http://loinc.org` | `36174-1` | Femur - left CT W contrast IV |
| `http://loinc.org` | `36175-8` | Thigh - left MRI W contrast IV |
| `http://loinc.org` | `36176-6` | Femur - right CT W contrast IV |
| `http://loinc.org` | `36177-4` | Thigh - right MRI W contrast IV |
| `http://loinc.org` | `36178-2` | Foot CT W contrast IV |
| `http://loinc.org` | `36179-0` | Foot MRI W contrast IV |
| `http://loinc.org` | `36180-8` | Foot - bilateral MRI W contrast IV |
| `http://loinc.org` | `36181-6` | Foot - left CT W contrast IV |
| `http://loinc.org` | `36182-4` | Foot - left MRI W contrast IV |
| `http://loinc.org` | `36183-2` | Foot - right CT W contrast IV |
| `http://loinc.org` | `36184-0` | Foot - right MRI W contrast IV |
| `http://loinc.org` | `36185-7` | Forearm CT W contrast IV |
| `http://loinc.org` | `36186-5` | Forearm MRI W contrast IV |
| `http://loinc.org` | `36187-3` | Forearm - left CT W contrast IV |
| `http://loinc.org` | `36188-1` | Forearm - left MRI W contrast IV |
| `http://loinc.org` | `36189-9` | Forearm - right CT W contrast IV |
| `http://loinc.org` | `36190-7` | Forearm - right MRI W contrast IV |
| `http://loinc.org` | `36191-5` | Hand CT W contrast IV |
| `http://loinc.org` | `36192-3` | Hand MRI W contrast IV |
| `http://loinc.org` | `36193-1` | Hand - left CT W contrast IV |
| `http://loinc.org` | `36194-9` | Hand - left MRI W contrast IV |
| `http://loinc.org` | `36195-6` | Hand - right CT W contrast IV |
| `http://loinc.org` | `36196-4` | Hand - right MRI W contrast IV |
| `http://loinc.org` | `36197-2` | Heart MRI W contrast IV |
| `http://loinc.org` | `36198-0` | Calcaneus CT W contrast IV |
| `http://loinc.org` | `36199-8` | Hip MRI W contrast IV |
| `http://loinc.org` | `36200-4` | Hip CT W contrast IV |
| `http://loinc.org` | `36201-2` | Hip - bilateral CT W contrast IV |
| `http://loinc.org` | `36202-0` | Hip - bilateral MRI W contrast IV |
| `http://loinc.org` | `36203-8` | Hip - left CT W contrast IV |
| `http://loinc.org` | `36204-6` | Hip - left MRI W contrast IV |
| `http://loinc.org` | `36205-3` | Hip - right CT W contrast IV |
| `http://loinc.org` | `36206-1` | Hip - right MRI W contrast IV |
| `http://loinc.org` | `36207-9` | Upper arm CT W contrast IV |
| `http://loinc.org` | `36208-7` | Upper arm MRI W contrast IV |
| `http://loinc.org` | `36209-5` | Upper arm - left CT W contrast IV |
| `http://loinc.org` | `36210-3` | Upper arm - left MRI W contrast IV |
| `http://loinc.org` | `36211-1` | Upper arm - right CT W contrast IV |
| `http://loinc.org` | `36212-9` | Upper arm - right MRI W contrast IV |
| `http://loinc.org` | `36213-7` | Lower Extremity Joint MRI W contrast IV |
| `http://loinc.org` | `36214-5` | Lower extremity joint - left MRI W contrast IV |
| `http://loinc.org` | `36215-2` | Lower extremity joint - right MRI W contrast IV |
| `http://loinc.org` | `36216-0` | Upper extremity .joint MRI W contrast IV |
| `http://loinc.org` | `36217-8` | Sacroiliac Joint CT W contrast IV |
| `http://loinc.org` | `36218-6` | Sacroiliac Joint MRI W contrast IV |
| `http://loinc.org` | `36219-4` | Kidney - bilateral MRI W contrast IV |
| `http://loinc.org` | `36220-2` | Kidney - left MRI W contrast IV |
| `http://loinc.org` | `36221-0` | Kidney - right MRI W contrast IV |
| `http://loinc.org` | `36222-8` | Knee CT W contrast IV |
| `http://loinc.org` | `36223-6` | Knee MRI W contrast IV |
| `http://loinc.org` | `36224-4` | Knee - bilateral MRI W contrast IV |
| `http://loinc.org` | `36225-1` | Knee - left CT W contrast IV |
| `http://loinc.org` | `36226-9` | Knee - left MRI W contrast IV |
| `http://loinc.org` | `36227-7` | Knee - right CT W contrast IV |
| `http://loinc.org` | `36228-5` | Knee - right MRI W contrast IV |
| `http://loinc.org` | `36229-3` | Larynx CT W contrast IV |
| `http://loinc.org` | `36230-1` | Larynx MRI W contrast IV |
| `http://loinc.org` | `36231-9` | Liver MRI W contrast IV |
| `http://loinc.org` | `36232-7` | Mandible CT W contrast IV |
| `http://loinc.org` | `36233-5` | Nasopharynx MRI W contrast IV |
| `http://loinc.org` | `36234-3` | Neck vessels CT angiogram W contrast IV |
| `http://loinc.org` | `36235-0` | Neck CT W contrast IV |
| `http://loinc.org` | `36236-8` | Pancreas MRI W contrast IV |
| `http://loinc.org` | `36237-6` | Pelvis MRI W contrast IV |
| `http://loinc.org` | `36238-4` | Pituitary and Sella turcica MRI W contrast IV |
| `http://loinc.org` | `36239-2` | Thoracic outlet MRI W contrast IV |
| `http://loinc.org` | `36240-0` | Thoracic outlet - left MRI W contrast IV |
| `http://loinc.org` | `36241-8` | Thoracic outlet - right MRI W contrast IV |
| `http://loinc.org` | `36242-6` | Posterior fossa CT W contrast IV |
| `http://loinc.org` | `36243-4` | Posterior fossa MRI W contrast IV |
| `http://loinc.org` | `36244-2` | Prostate MRI W contrast IV |
| `http://loinc.org` | `36245-9` | Sacrum CT W contrast IV |
| `http://loinc.org` | `36246-7` | Sacrum MRI W contrast IV |
| `http://loinc.org` | `36247-5` | Sacrum and Coccyx MRI W contrast IV |
| `http://loinc.org` | `36248-3` | Scapula - left MRI W contrast IV |
| `http://loinc.org` | `36249-1` | Scapula - right MRI W contrast IV |
| `http://loinc.org` | `36250-9` | Shoulder CT W contrast IV |
| `http://loinc.org` | `36251-7` | Shoulder MRI W contrast IV |
| `http://loinc.org` | `36252-5` | Shoulder - left CT W contrast IV |
| `http://loinc.org` | `36253-3` | Shoulder - right CT W contrast IV |
| `http://loinc.org` | `36254-1` | Shoulder - right MRI W contrast IV |
| `http://loinc.org` | `36255-8` | Sinuses CT W contrast IV |
| `http://loinc.org` | `36256-6` | Spine MRI W contrast IV |
| `http://loinc.org` | `36257-4` | Sternum CT W contrast IV |
| `http://loinc.org` | `36258-2` | Lower leg CT W contrast IV |
| `http://loinc.org` | `36259-0` | Lower leg MRI W contrast IV |
| `http://loinc.org` | `36260-8` | Lower leg - left CT W contrast IV |
| `http://loinc.org` | `36261-6` | Lower leg - left MRI W contrast IV |
| `http://loinc.org` | `36262-4` | Lower leg - right CT W contrast IV |
| `http://loinc.org` | `36263-2` | Lower leg - right MRI W contrast IV |
| `http://loinc.org` | `36264-0` | Uterus CT W contrast IV |
| `http://loinc.org` | `36265-7` | Uterus MRI W contrast IV |
| `http://loinc.org` | `36266-5` | Chest vessels CT angiogram W contrast IV |
| `http://loinc.org` | `36267-3` | Abdomen CT W and WO contrast IV |
| `http://loinc.org` | `36268-1` | Ankle CT W and WO contrast IV |
| `http://loinc.org` | `36269-9` | Ankle - left CT W and WO contrast IV |
| `http://loinc.org` | `36270-7` | Ankle - right CT W and WO contrast IV |
| `http://loinc.org` | `36271-5` | Aorta abdominal CT W and WO contrast IV |
| `http://loinc.org` | `36272-3` | Aorta abdominal MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36273-1` | Aorta abdominal MRI W and WO contrast IV |
| `http://loinc.org` | `36274-9` | Aorta thoracic MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36275-6` | Renal artery MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36276-4` | Breast MRI W and WO contrast IV |
| `http://loinc.org` | `36277-2` | Breast - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `36278-0` | Breast - left MRI W and WO contrast IV |
| `http://loinc.org` | `36279-8` | Breast - right MRI W and WO contrast IV |
| `http://loinc.org` | `36280-6` | Calcaneus - left CT W and WO contrast IV |
| `http://loinc.org` | `36281-4` | Calcaneus - right CT W and WO contrast IV |
| `http://loinc.org` | `36282-2` | Internal auditory canal CT W and WO contrast IV |
| `http://loinc.org` | `36283-0` | Chest MRI W and WO contrast IV |
| `http://loinc.org` | `36284-8` | Chest and Abdomen MRI W and WO contrast IV |
| `http://loinc.org` | `36285-5` | Elbow CT W and WO contrast IV |
| `http://loinc.org` | `36286-3` | Elbow - left CT W and WO contrast IV |
| `http://loinc.org` | `36287-1` | Elbow - right CT W and WO contrast IV |
| `http://loinc.org` | `36288-9` | Lower extremity CT W and WO contrast IV |
| `http://loinc.org` | `36289-7` | Lower extremity - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `36290-5` | Lower extremity - left CT W and WO contrast IV |
| `http://loinc.org` | `36291-3` | Lower extremity - left MRI W and WO contrast IV |
| `http://loinc.org` | `36292-1` | Lower extremity - right CT W and WO contrast IV |
| `http://loinc.org` | `36293-9` | Abdomen X-ray 3 views |
| `http://loinc.org` | `36294-7` | Ankle X-ray 3 views |
| `http://loinc.org` | `36295-4` | Ankle - bilateral X-ray 3 views |
| `http://loinc.org` | `36296-2` | Ankle - left X-ray 3 views |
| `http://loinc.org` | `36297-0` | Facial bones X-ray 3 views |
| `http://loinc.org` | `36298-8` | Chest X-ray 3 views |
| `http://loinc.org` | `36299-6` | Elbow X-ray 3 views |
| `http://loinc.org` | `36300-2` | Elbow - bilateral X-ray 3 views |
| `http://loinc.org` | `36301-0` | Elbow - left X-ray 3 views |
| `http://loinc.org` | `36302-8` | Femur X-ray 3 views |
| `http://loinc.org` | `36303-6` | Finger X-ray 3 views |
| `http://loinc.org` | `36304-4` | Finger - left X-ray 3 views |
| `http://loinc.org` | `36305-1` | Foot X-ray 3 views |
| `http://loinc.org` | `36306-9` | Foot - bilateral X-ray 3 views |
| `http://loinc.org` | `36307-7` | Foot - left X-ray 3 views |
| `http://loinc.org` | `36308-5` | Hip - bilateral X-ray 3 views |
| `http://loinc.org` | `36309-3` | Hip - left X-ray 3 views |
| `http://loinc.org` | `36310-1` | Knee - bilateral X-ray 3 views |
| `http://loinc.org` | `36311-9` | Knee - left X-ray 3 views |
| `http://loinc.org` | `36312-7` | Mandible X-ray 3 views |
| `http://loinc.org` | `36313-5` | Ribs - bilateral X-ray 3 views |
| `http://loinc.org` | `36314-3` | Ribs - left X-ray 3 views |
| `http://loinc.org` | `36315-0` | Thumb - left X-ray 3 views |
| `http://loinc.org` | `36316-8` | Toes - left X-ray 3 views |
| `http://loinc.org` | `36317-6` | Ankle X-ray 4 views |
| `http://loinc.org` | `36318-4` | Facial bones X-ray 4 views |
| `http://loinc.org` | `36319-2` | Breast Mammogram 4 views |
| `http://loinc.org` | `36320-0` | Chest X-ray 4 views |
| `http://loinc.org` | `36321-8` | Chest Fluoroscopy 4 views |
| `http://loinc.org` | `36322-6` | Elbow - bilateral X-ray 4 views |
| `http://loinc.org` | `36323-4` | Elbow - left X-ray 4 views |
| `http://loinc.org` | `36324-2` | Femur - left X-ray 4 views |
| `http://loinc.org` | `36325-9` | Knee - bilateral X-ray 4 views |
| `http://loinc.org` | `36326-7` | Knee - left X-ray 4 views |
| `http://loinc.org` | `36327-5` | Mandible X-ray 4 views |
| `http://loinc.org` | `36328-3` | Ribs - bilateral X-ray 4 views |
| `http://loinc.org` | `36329-1` | Shoulder - bilateral X-ray 4 views |
| `http://loinc.org` | `36330-9` | Shoulder - left X-ray 4 views |
| `http://loinc.org` | `36331-7` | Spine Cervical X-ray 4 views |
| `http://loinc.org` | `36332-5` | Spine Lumbar X-ray 4 views |
| `http://loinc.org` | `36333-3` | Lower extremity - right MRI W and WO contrast IV |
| `http://loinc.org` | `36334-1` | Upper extremity CT W and WO contrast IV |
| `http://loinc.org` | `36335-8` | Upper extremity - left CT W and WO contrast IV |
| `http://loinc.org` | `36336-6` | Upper extremity - right CT W and WO contrast IV |
| `http://loinc.org` | `36337-4` | Upper extremity - right MRI W and WO contrast IV |
| `http://loinc.org` | `36338-2` | Femur CT W and WO contrast IV |
| `http://loinc.org` | `36339-0` | Femur - left CT W and WO contrast IV |
| `http://loinc.org` | `36340-8` | Femur - right CT W and WO contrast IV |
| `http://loinc.org` | `36341-6` | Foot CT W and WO contrast IV |
| `http://loinc.org` | `36342-4` | Foot - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `36343-2` | Foot - left CT W and WO contrast IV |
| `http://loinc.org` | `36344-0` | Foot - left MRI W and WO contrast IV |
| `http://loinc.org` | `36345-7` | Foot - right CT W and WO contrast IV |
| `http://loinc.org` | `36346-5` | Foot - right MRI W and WO contrast IV |
| `http://loinc.org` | `36347-3` | Forearm CT W and WO contrast IV |
| `http://loinc.org` | `36348-1` | Forearm - left CT W and WO contrast IV |
| `http://loinc.org` | `36349-9` | Forearm - left MRI W and WO contrast IV |
| `http://loinc.org` | `36350-7` | Forearm - right CT W and WO contrast IV |
| `http://loinc.org` | `36351-5` | Forearm - right MRI W and WO contrast IV |
| `http://loinc.org` | `36352-3` | Hand CT W and WO contrast IV |
| `http://loinc.org` | `36353-1` | Hand - left CT W and WO contrast IV |
| `http://loinc.org` | `36354-9` | Hand - left MRI W and WO contrast IV |
| `http://loinc.org` | `36355-6` | Hand - right CT W and WO contrast IV |
| `http://loinc.org` | `36356-4` | Hand - right MRI W and WO contrast IV |
| `http://loinc.org` | `36357-2` | Heart MRI W and WO contrast IV |
| `http://loinc.org` | `36358-0` | Calcaneus CT W and WO contrast IV |
| `http://loinc.org` | `36359-8` | Hip CT W and WO contrast IV |
| `http://loinc.org` | `36360-6` | Hip - bilateral CT W and WO contrast IV |
| `http://loinc.org` | `36361-4` | Hip - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `36362-2` | Hip - left CT W and WO contrast IV |
| `http://loinc.org` | `36363-0` | Hip - left MRI W and WO contrast IV |
| `http://loinc.org` | `36364-8` | Hip - right CT W and WO contrast IV |
| `http://loinc.org` | `36365-5` | Hip - right MRI W and WO contrast IV |
| `http://loinc.org` | `36366-3` | Upper arm CT W and WO contrast IV |
| `http://loinc.org` | `36367-1` | Upper arm - left CT W and WO contrast IV |
| `http://loinc.org` | `36368-9` | Upper arm - left MRI W and WO contrast IV |
| `http://loinc.org` | `36369-7` | Upper arm - right CT W and WO contrast IV |
| `http://loinc.org` | `36370-5` | Upper arm - right MRI W and WO contrast IV |
| `http://loinc.org` | `36371-3` | Lower Extremity Joint MRI W and WO contrast IV |
| `http://loinc.org` | `36372-1` | Lower extremity joint - left MRI W and WO contrast IV |
| `http://loinc.org` | `36373-9` | Lower extremity joint - right MRI W and WO contrast IV |
| `http://loinc.org` | `36374-7` | Upper extremity .joint MRI W and WO contrast IV |
| `http://loinc.org` | `36375-4` | Sacroiliac Joint CT W and WO contrast IV |
| `http://loinc.org` | `36376-2` | Sacroiliac Joint MRI W and WO contrast IV |
| `http://loinc.org` | `36377-0` | Kidney - bilateral CT W and WO contrast IV |
| `http://loinc.org` | `36378-8` | Kidney - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `36379-6` | Knee CT W and WO contrast IV |
| `http://loinc.org` | `36380-4` | Knee - left CT W and WO contrast IV |
| `http://loinc.org` | `36381-2` | Knee - right CT W and WO contrast IV |
| `http://loinc.org` | `36382-0` | Larynx MRI W and WO contrast IV |
| `http://loinc.org` | `36383-8` | Mandible CT W and WO contrast IV |
| `http://loinc.org` | `36384-6` | Nasopharynx MRI W and WO contrast IV |
| `http://loinc.org` | `36385-3` | Pancreas MRI W and WO contrast IV |
| `http://loinc.org` | `36387-9` | Posterior fossa CT W and WO contrast IV |
| `http://loinc.org` | `36388-7` | Posterior fossa MRI W and WO contrast IV |
| `http://loinc.org` | `36389-5` | Prostate MRI W and WO contrast IV |
| `http://loinc.org` | `36390-3` | Sacrum CT W and WO contrast IV |
| `http://loinc.org` | `36391-1` | Sacrum MRI W and WO contrast IV |
| `http://loinc.org` | `36392-9` | Sacrum and Coccyx MRI W and WO contrast IV |
| `http://loinc.org` | `36393-7` | Scapula - left MRI W and WO contrast IV |
| `http://loinc.org` | `36394-5` | Scapula - right MRI W and WO contrast IV |
| `http://loinc.org` | `36395-2` | Shoulder CT W and WO contrast IV |
| `http://loinc.org` | `36396-0` | Shoulder - left CT W and WO contrast IV |
| `http://loinc.org` | `36397-8` | Shoulder - right CT W and WO contrast IV |
| `http://loinc.org` | `36398-6` | Sinuses CT W and WO contrast IV |
| `http://loinc.org` | `36399-4` | Spine CT W and WO contrast IV |
| `http://loinc.org` | `36400-0` | Spine MRI W and WO contrast IV |
| `http://loinc.org` | `36401-8` | Spine Cervical CT W and WO contrast IV |
| `http://loinc.org` | `36402-6` | Spine Lumbar CT W and WO contrast IV |
| `http://loinc.org` | `36403-4` | Spine Thoracic CT W and WO contrast IV |
| `http://loinc.org` | `36404-2` | Spleen MRI W and WO contrast IV |
| `http://loinc.org` | `36405-9` | Sternum CT W and WO contrast IV |
| `http://loinc.org` | `36406-7` | Scrotum and Testicle MRI W and WO contrast IV |
| `http://loinc.org` | `36407-5` | Thyroid MRI W and WO contrast IV |
| `http://loinc.org` | `36408-3` | Lower leg CT W and WO contrast IV |
| `http://loinc.org` | `36409-1` | Lower leg - left CT W and WO contrast IV |
| `http://loinc.org` | `36410-9` | Lower leg - left MRI W and WO contrast IV |
| `http://loinc.org` | `36411-7` | Lower leg - right CT W and WO contrast IV |
| `http://loinc.org` | `36412-5` | Lower leg - right MRI W and WO contrast IV |
| `http://loinc.org` | `36413-3` | Uterus MRI W and WO contrast IV |
| `http://loinc.org` | `36414-1` | Portal vein MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36415-8` | Renal vein MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36416-6` | Lower extremity veins MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36417-4` | Upper extremity veins MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36418-2` | Inferior vena cava MRI W and WO contrast IV |
| `http://loinc.org` | `36419-0` | Superior vena cava MRI W and WO contrast IV |
| `http://loinc.org` | `36420-8` | Chest vessels MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36421-6` | Upper extremity vessels CT angiogram W and WO contrast IV |
| `http://loinc.org` | `36422-4` | Upper extremity vessels MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36423-2` | Neck vessels MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36424-0` | Abdomen CT WO contrast |
| `http://loinc.org` | `36425-7` | Ankle CT WO contrast |
| `http://loinc.org` | `36426-5` | Ankle - left CT WO contrast |
| `http://loinc.org` | `36427-3` | Ankle - left MRI WO contrast |
| `http://loinc.org` | `36428-1` | Ankle - right CT WO contrast |
| `http://loinc.org` | `36429-9` | Ankle - right MRI WO contrast |
| `http://loinc.org` | `36430-7` | Aorta CT WO contrast |
| `http://loinc.org` | `36431-5` | Aorta abdominal CT WO contrast |
| `http://loinc.org` | `36432-3` | Aorta abdominal MRI angiogram WO contrast |
| `http://loinc.org` | `36433-1` | Aorta thoracic MRI angiogram WO contrast |
| `http://loinc.org` | `36434-9` | Appendix CT WO contrast |
| `http://loinc.org` | `36435-6` | Face MRI WO contrast |
| `http://loinc.org` | `36436-4` | Breast MRI WO contrast |
| `http://loinc.org` | `36437-2` | Breast - bilateral MRI WO contrast |
| `http://loinc.org` | `36438-0` | Breast - left MRI WO contrast |
| `http://loinc.org` | `36439-8` | Breast - right MRI WO contrast |
| `http://loinc.org` | `36440-6` | Calcaneus - left CT WO contrast |
| `http://loinc.org` | `36441-4` | Calcaneus - right CT WO contrast |
| `http://loinc.org` | `36442-2` | Chest MRI WO contrast |
| `http://loinc.org` | `36443-0` | Elbow CT WO contrast |
| `http://loinc.org` | `36444-8` | Elbow - bilateral CT WO contrast |
| `http://loinc.org` | `36445-5` | Elbow - left CT WO contrast |
| `http://loinc.org` | `36446-3` | Elbow - left MRI WO contrast |
| `http://loinc.org` | `36447-1` | Elbow - right CT WO contrast |
| `http://loinc.org` | `36448-9` | Elbow - right MRI WO contrast |
| `http://loinc.org` | `36449-7` | Lower extremity - bilateral CT WO contrast |
| `http://loinc.org` | `36450-5` | Lower extremity vessels - bilateral MRI angiogram WO contrast |
| `http://loinc.org` | `36451-3` | Lower extremity - bilateral MRI WO contrast |
| `http://loinc.org` | `36452-1` | Lower extremity - left CT WO contrast |
| `http://loinc.org` | `36453-9` | Lower extremity - left MRI WO contrast |
| `http://loinc.org` | `36454-7` | Lower extremity - right CT WO contrast |
| `http://loinc.org` | `36455-4` | Lower extremity - right MRI WO contrast |
| `http://loinc.org` | `36456-2` | Upper extremity - bilateral CT WO contrast |
| `http://loinc.org` | `36457-0` | Upper extremity - left CT WO contrast |
| `http://loinc.org` | `36458-8` | Upper extremity - right CT WO contrast |
| `http://loinc.org` | `36459-6` | Upper extremity - right MRI WO contrast |
| `http://loinc.org` | `36460-4` | Femur CT WO contrast |
| `http://loinc.org` | `36461-2` | Thigh MRI WO contrast |
| `http://loinc.org` | `36462-0` | Femur - left CT WO contrast |
| `http://loinc.org` | `36463-8` | Thigh - left MRI WO contrast |
| `http://loinc.org` | `36464-6` | Femur - right CT WO contrast |
| `http://loinc.org` | `36465-3` | Thigh - right MRI WO contrast |
| `http://loinc.org` | `36466-1` | Foot CT WO contrast |
| `http://loinc.org` | `36467-9` | Foot - bilateral MRI WO contrast |
| `http://loinc.org` | `36468-7` | Foot - left CT WO contrast |
| `http://loinc.org` | `36469-5` | Foot - left MRI WO contrast |
| `http://loinc.org` | `36470-3` | Foot - right CT WO contrast |
| `http://loinc.org` | `36471-1` | Foot - right MRI WO contrast |
| `http://loinc.org` | `36472-9` | Forearm CT WO contrast |
| `http://loinc.org` | `36473-7` | Forearm - left CT WO contrast |
| `http://loinc.org` | `36474-5` | Forearm - left MRI WO contrast |
| `http://loinc.org` | `36475-2` | Forearm - right CT WO contrast |
| `http://loinc.org` | `36476-0` | Forearm - right MRI WO contrast |
| `http://loinc.org` | `36477-8` | Hand CT WO contrast |
| `http://loinc.org` | `36478-6` | Hand - left CT WO contrast |
| `http://loinc.org` | `36479-4` | Hand - left MRI WO contrast |
| `http://loinc.org` | `36480-2` | Hand - right CT WO contrast |
| `http://loinc.org` | `36481-0` | Hand - right MRI WO contrast |
| `http://loinc.org` | `36482-8` | Heart MRI WO contrast |
| `http://loinc.org` | `36483-6` | Calcaneus CT WO contrast |
| `http://loinc.org` | `36484-4` | Hip CT WO contrast |
| `http://loinc.org` | `36485-1` | Hip - bilateral CT WO contrast |
| `http://loinc.org` | `36486-9` | Hip - bilateral MRI WO contrast |
| `http://loinc.org` | `36487-7` | Hip - left CT WO contrast |
| `http://loinc.org` | `36488-5` | Hip - left MRI WO contrast |
| `http://loinc.org` | `36489-3` | Hip - right CT WO contrast |
| `http://loinc.org` | `36490-1` | Hip - right MRI WO contrast |
| `http://loinc.org` | `36491-9` | Upper arm CT WO contrast |
| `http://loinc.org` | `36492-7` | Upper arm - left CT WO contrast |
| `http://loinc.org` | `36493-5` | Upper arm - left MRI WO contrast |
| `http://loinc.org` | `36494-3` | Upper arm - right CT WO contrast |
| `http://loinc.org` | `36495-0` | Upper arm - right MRI WO contrast |
| `http://loinc.org` | `36496-8` | Acromioclavicular Joint MRI WO contrast |
| `http://loinc.org` | `36497-6` | Lower Extremity Joint MRI WO contrast |
| `http://loinc.org` | `36498-4` | Lower extremity joint - left MRI WO contrast |
| `http://loinc.org` | `36499-2` | Lower extremity joint - right MRI WO contrast |
| `http://loinc.org` | `36500-7` | Upper extremity .joint MRI WO contrast |
| `http://loinc.org` | `36501-5` | Sacroiliac Joint CT WO contrast |
| `http://loinc.org` | `36502-3` | Sacroiliac Joint MRI WO contrast |
| `http://loinc.org` | `36503-1` | Kidney - bilateral CT WO contrast |
| `http://loinc.org` | `36504-9` | Kidney - bilateral MRI WO contrast |
| `http://loinc.org` | `36505-6` | Knee CT WO contrast |
| `http://loinc.org` | `36506-4` | Knee - bilateral MRI WO contrast |
| `http://loinc.org` | `36507-2` | Knee - left CT WO contrast |
| `http://loinc.org` | `36508-0` | Knee - left MRI WO contrast |
| `http://loinc.org` | `36509-8` | Knee - right CT WO contrast |
| `http://loinc.org` | `36510-6` | Knee - right MRI WO contrast |
| `http://loinc.org` | `36511-4` | Larynx CT WO contrast |
| `http://loinc.org` | `36512-2` | Mandible CT WO contrast |
| `http://loinc.org` | `36513-0` | Nasopharynx MRI WO contrast |
| `http://loinc.org` | `36514-8` | Neck CT WO contrast |
| `http://loinc.org` | `36515-5` | Pancreas MRI WO contrast |
| `http://loinc.org` | `36516-3` | Thoracic outlet - right MRI WO contrast |
| `http://loinc.org` | `36517-1` | Posterior fossa CT WO contrast |
| `http://loinc.org` | `36518-9` | Posterior fossa MRI WO contrast |
| `http://loinc.org` | `36519-7` | Prostate MRI WO contrast |
| `http://loinc.org` | `36520-5` | Sacrum CT WO contrast |
| `http://loinc.org` | `36521-3` | Sacrum MRI WO contrast |
| `http://loinc.org` | `36522-1` | Sacrum and Coccyx MRI WO contrast |
| `http://loinc.org` | `36523-9` | Scapula - left MRI WO contrast |
| `http://loinc.org` | `36524-7` | Shoulder CT WO contrast |
| `http://loinc.org` | `36525-4` | Shoulder - bilateral MRI WO contrast |
| `http://loinc.org` | `36526-2` | Shoulder - left CT WO contrast |
| `http://loinc.org` | `36527-0` | Shoulder - right CT WO contrast |
| `http://loinc.org` | `36528-8` | Shoulder - right MRI WO contrast |
| `http://loinc.org` | `36529-6` | Sinuses CT WO contrast |
| `http://loinc.org` | `36530-4` | Spine CT WO contrast |
| `http://loinc.org` | `36531-2` | Spine MRI WO contrast |
| `http://loinc.org` | `36532-0` | Spine Thoracic MRI WO contrast |
| `http://loinc.org` | `36533-8` | Spleen MRI WO contrast |
| `http://loinc.org` | `36534-6` | Sternum CT WO contrast |
| `http://loinc.org` | `36535-3` | Scrotum and Testicle MRI WO contrast |
| `http://loinc.org` | `36536-1` | Thyroid MRI WO contrast |
| `http://loinc.org` | `36537-9` | Lower leg CT WO contrast |
| `http://loinc.org` | `36538-7` | Lower leg - left CT WO contrast |
| `http://loinc.org` | `36539-5` | Lower leg - left MRI WO contrast |
| `http://loinc.org` | `36540-3` | Lower leg - right CT WO contrast |
| `http://loinc.org` | `36541-1` | Lower leg - right MRI WO contrast |
| `http://loinc.org` | `36542-9` | Uterus MRI WO contrast |
| `http://loinc.org` | `36543-7` | Portal vein MRI angiogram WO contrast |
| `http://loinc.org` | `36544-5` | Renal vein MRI angiogram WO contrast |
| `http://loinc.org` | `36545-2` | Inferior vena cava MRI WO contrast |
| `http://loinc.org` | `36546-0` | Superior vena cava MRI WO contrast |
| `http://loinc.org` | `36547-8` | Chest vessels MRI angiogram WO contrast |
| `http://loinc.org` | `36548-6` | Upper extremity vessels MRI angiogram WO contrast |
| `http://loinc.org` | `36549-4` | Neck vessels MRI angiogram WO contrast |
| `http://loinc.org` | `36550-2` | Abdomen X-ray Single view |
| `http://loinc.org` | `36551-0` | Ankle X-ray Single view |
| `http://loinc.org` | `36554-4` | Chest X-ray Single view |
| `http://loinc.org` | `36555-1` | Clavicle X-ray Single view |
| `http://loinc.org` | `36556-9` | Elbow X-ray Single view |
| `http://loinc.org` | `36557-7` | Lower extremity - bilateral X-ray Single view |
| `http://loinc.org` | `36558-5` | Lower extremity - left X-ray Single view |
| `http://loinc.org` | `36559-3` | Femur X-ray Single view |
| `http://loinc.org` | `36560-1` | Femur - left X-ray Single view |
| `http://loinc.org` | `36561-9` | Foot X-ray Single view |
| `http://loinc.org` | `36563-5` | Hand X-ray Single view |
| `http://loinc.org` | `36564-3` | Calcaneus X-ray Single view |
| `http://loinc.org` | `36565-0` | Humerus X-ray Single view |
| `http://loinc.org` | `36566-8` | Knee - bilateral X-ray Single view |
| `http://loinc.org` | `36567-6` | Knee - left X-ray Single view |
| `http://loinc.org` | `36568-4` | Shoulder - bilateral X-ray Single view |
| `http://loinc.org` | `36569-2` | Shoulder - left X-ray Single view |
| `http://loinc.org` | `36570-0` | Wrist - left X-ray Single view |
| `http://loinc.org` | `36571-8` | Ankle X-ray AP single view |
| `http://loinc.org` | `36572-6` | Chest X-ray AP single view |
| `http://loinc.org` | `36573-4` | Clavicle X-ray AP single view |
| `http://loinc.org` | `36574-2` | Lower extremity X-ray AP single view |
| `http://loinc.org` | `36575-9` | Femur X-ray AP single view |
| `http://loinc.org` | `36576-7` | Finger fifth X-ray AP single view |
| `http://loinc.org` | `36577-5` | Finger fourth X-ray AP single view |
| `http://loinc.org` | `36578-3` | Finger third X-ray AP single view |
| `http://loinc.org` | `36579-1` | Foot X-ray AP single view |
| `http://loinc.org` | `36580-9` | Foot - bilateral X-ray AP single view |
| `http://loinc.org` | `36581-7` | Hip X-ray AP single view |
| `http://loinc.org` | `36582-5` | Hip - left X-ray AP single view |
| `http://loinc.org` | `36583-3` | Acromioclavicular joint - left X-ray AP single view |
| `http://loinc.org` | `36584-1` | Knee X-ray AP single view |
| `http://loinc.org` | `36585-8` | Knee - bilateral X-ray AP single view |
| `http://loinc.org` | `36586-6` | Shoulder - bilateral X-ray AP single view |
| `http://loinc.org` | `36587-4` | Shoulder - left X-ray AP single view |
| `http://loinc.org` | `36588-2` | Abdomen X-ray AP portable single view |
| `http://loinc.org` | `36589-0` | Chest X-ray AP portable single view |
| `http://loinc.org` | `36590-8` | Knee - bilateral X-ray AP and lateral |
| `http://loinc.org` | `36591-6` | Abdomen X-ray lateral |
| `http://loinc.org` | `36592-4` | Ankle X-ray lateral |
| `http://loinc.org` | `36593-2` | Femur X-ray lateral |
| `http://loinc.org` | `36594-0` | Finger fifth X-ray lateral |
| `http://loinc.org` | `36595-7` | Finger fourth X-ray lateral |
| `http://loinc.org` | `36596-5` | Finger second X-ray lateral |
| `http://loinc.org` | `36597-3` | Finger third X-ray lateral |
| `http://loinc.org` | `36598-1` | Foot - left X-ray lateral |
| `http://loinc.org` | `36599-9` | Hand X-ray lateral |
| `http://loinc.org` | `36600-5` | Hand - bilateral X-ray lateral |
| `http://loinc.org` | `36601-3` | Hand - left X-ray lateral |
| `http://loinc.org` | `36602-1` | Hip X-ray lateral |
| `http://loinc.org` | `36603-9` | Hip - left X-ray lateral |
| `http://loinc.org` | `36604-7` | Knee X-ray lateral |
| `http://loinc.org` | `36605-4` | Knee - bilateral X-ray lateral |
| `http://loinc.org` | `36606-2` | Knee - left X-ray lateral |
| `http://loinc.org` | `36607-0` | Abdomen X-ray oblique single view |
| `http://loinc.org` | `36608-8` | Elbow X-ray oblique |
| `http://loinc.org` | `36609-6` | Femur X-ray oblique single view |
| `http://loinc.org` | `36610-4` | Finger fifth X-ray oblique single view |
| `http://loinc.org` | `36611-2` | Finger fourth X-ray oblique single view |
| `http://loinc.org` | `36612-0` | Finger second X-ray oblique single view |
| `http://loinc.org` | `36613-8` | Finger third X-ray oblique single view |
| `http://loinc.org` | `36614-6` | Foot X-ray oblique single view |
| `http://loinc.org` | `36615-3` | Foot - left X-ray oblique single view |
| `http://loinc.org` | `36616-1` | Hand X-ray oblique single view |
| `http://loinc.org` | `36617-9` | Hip X-ray oblique single view |
| `http://loinc.org` | `36618-7` | Hip - bilateral X-ray oblique single view |
| `http://loinc.org` | `36619-5` | Knee X-ray oblique |
| `http://loinc.org` | `36620-3` | Chest X-ray left anterior oblique |
| `http://loinc.org` | `36621-1` | Hand X-ray PA |
| `http://loinc.org` | `36622-9` | Hand - bilateral X-ray PA |
| `http://loinc.org` | `36623-7` | Hand - left X-ray PA |
| `http://loinc.org` | `36624-5` | Wrist - bilateral X-ray PA |
| `http://loinc.org` | `36625-2` | Breast Mammogram |
| `http://loinc.org` | `36626-0` | Breast - bilateral Mammogram |
| `http://loinc.org` | `36627-8` | Breast - left Mammogram |
| `http://loinc.org` | `36628-6` | Internal auditory canal X-ray |
| `http://loinc.org` | `36629-4` | Hand - bilateral X-ray |
| `http://loinc.org` | `36630-2` | Hand - left X-ray |
| `http://loinc.org` | `36631-0` | Pelvis and Hip - left X-ray |
| `http://loinc.org` | `36632-8` | Humerus - left X-ray |
| `http://loinc.org` | `36633-6` | Sacroiliac joint - bilateral X-ray |
| `http://loinc.org` | `36634-4` | Sacroiliac joint - left X-ray |
| `http://loinc.org` | `36635-1` | Knee - bilateral X-ray |
| `http://loinc.org` | `36636-9` | Knee - left X-ray |
| `http://loinc.org` | `36637-7` | Maxilla X-ray |
| `http://loinc.org` | `36638-5` | Patella - bilateral X-ray |
| `http://loinc.org` | `36639-3` | Patella - left X-ray |
| `http://loinc.org` | `36640-1` | Spine Cervical Fluoroscopy |
| `http://loinc.org` | `36641-9` | Abdomen X-ray 2 views |
| `http://loinc.org` | `36642-7` | Breast - left Mammogram 2 views |
| `http://loinc.org` | `36643-5` | Chest X-ray 2 views |
| `http://loinc.org` | `36644-3` | Chest Fluoroscopy 2 views |
| `http://loinc.org` | `36645-0` | Clavicle X-ray 2 views |
| `http://loinc.org` | `36646-8` | Clavicle - left X-ray 2 views |
| `http://loinc.org` | `36647-6` | Coccyx X-ray 2 views |
| `http://loinc.org` | `36648-4` | Elbow X-ray 2 views |
| `http://loinc.org` | `36649-2` | Elbow - bilateral X-ray 2 views |
| `http://loinc.org` | `36650-0` | Elbow - left X-ray 2 views |
| `http://loinc.org` | `36651-8` | Lower extremity X-ray 2 views |
| `http://loinc.org` | `36652-6` | Femur X-ray 2 views |
| `http://loinc.org` | `36653-4` | Femur - bilateral X-ray 2 views |
| `http://loinc.org` | `36654-2` | Femur - left X-ray 2 views |
| `http://loinc.org` | `36655-9` | Finger X-ray 2 views |
| `http://loinc.org` | `36656-7` | Finger - left X-ray 2 views |
| `http://loinc.org` | `36657-5` | Foot - bilateral X-ray 2 views |
| `http://loinc.org` | `36658-3` | Radius and Ulna X-ray 2 views |
| `http://loinc.org` | `36659-1` | Radius - bilateral and Ulna - bilateral X-ray 2 views |
| `http://loinc.org` | `36660-9` | Radius - left and Ulna.left X-ray 2 views |
| `http://loinc.org` | `36661-7` | Calcaneus X-ray 2 views |
| `http://loinc.org` | `36662-5` | Calcaneus - left X-ray 2 views |
| `http://loinc.org` | `36663-3` | Hip X-ray 2 views |
| `http://loinc.org` | `36664-1` | Hip - left X-ray 2 views |
| `http://loinc.org` | `36665-8` | Acromioclavicular joint - left X-ray 2 views |
| `http://loinc.org` | `36666-6` | Scapula - left X-ray 2 views |
| `http://loinc.org` | `36667-4` | Shoulder - bilateral X-ray 2 views |
| `http://loinc.org` | `36668-2` | Shoulder - left X-ray 2 views |
| `http://loinc.org` | `36669-0` | Spine Cervical X-ray 2 views |
| `http://loinc.org` | `36670-8` | Spine Lumbar X-ray 2 views |
| `http://loinc.org` | `36671-6` | Tibia - bilateral and Fibula - bilateral X-ray 2 views |
| `http://loinc.org` | `36672-4` | Tibia - left and Fibula - left X-ray 2 views |
| `http://loinc.org` | `36673-2` | Toes - left X-ray 2 views |
| `http://loinc.org` | `36674-0` | Spine Lumbar X-ray 2 views portable |
| `http://loinc.org` | `36675-7` | Facial bones X-ray 5 views |
| `http://loinc.org` | `36676-5` | Knee - left X-ray 5 views |
| `http://loinc.org` | `36677-3` | Shoulder - left X-ray 5 views |
| `http://loinc.org` | `36678-1` | Knee - bilateral X-ray 6 views |
| `http://loinc.org` | `36679-9` | Shoulder - left X-ray 6 views |
| `http://loinc.org` | `36680-7` | Spine Cervical X-ray 7 views |
| `http://loinc.org` | `36681-5` | Spine Lumbar X-ray 7 views |
| `http://loinc.org` | `36682-3` | Knee - bilateral X-ray 8 views |
| `http://loinc.org` | `36683-1` | Wrist - left X-ray 8 views |
| `http://loinc.org` | `36684-9` | Ankle - bilateral X-ray AP and lateral |
| `http://loinc.org` | `36685-6` | Ankle - left X-ray AP and lateral |
| `http://loinc.org` | `36686-4` | Calcaneus - bilateral X-ray AP and lateral |
| `http://loinc.org` | `36687-2` | Chest X-ray AP and lateral |
| `http://loinc.org` | `36688-0` | Coccyx X-ray AP and lateral |
| `http://loinc.org` | `36689-8` | Elbow X-ray AP and lateral |
| `http://loinc.org` | `36690-6` | Elbow - bilateral X-ray AP and lateral |
| `http://loinc.org` | `36691-4` | Elbow - left X-ray AP and lateral |
| `http://loinc.org` | `36692-2` | Lower extremity X-ray AP and lateral |
| `http://loinc.org` | `36693-0` | Femur X-ray AP and lateral |
| `http://loinc.org` | `36694-8` | Femur - bilateral X-ray AP and lateral |
| `http://loinc.org` | `36695-5` | Femur - left X-ray AP and lateral |
| `http://loinc.org` | `36696-3` | Foot - bilateral X-ray AP and lateral |
| `http://loinc.org` | `36697-1` | Foot - left X-ray AP and lateral |
| `http://loinc.org` | `36698-9` | Radius and Ulna X-ray AP and lateral |
| `http://loinc.org` | `36699-7` | Radius - bilateral and Ulna - bilateral X-ray AP and lateral |
| `http://loinc.org` | `36700-3` | Radius - left and Ulna.left X-ray AP and lateral |
| `http://loinc.org` | `36701-1` | Calcaneus - left X-ray AP and lateral |
| `http://loinc.org` | `36702-9` | Hip X-ray AP and lateral |
| `http://loinc.org` | `36703-7` | Hip - bilateral X-ray AP and lateral |
| `http://loinc.org` | `36704-5` | Hip - left X-ray AP and lateral |
| `http://loinc.org` | `36705-2` | Pelvis and Hip X-ray AP and lateral |
| `http://loinc.org` | `36706-0` | Humerus X-ray AP and lateral |
| `http://loinc.org` | `36707-8` | Humerus - bilateral X-ray AP and lateral |
| `http://loinc.org` | `36708-6` | Humerus - left X-ray AP and lateral |
| `http://loinc.org` | `36709-4` | Knee X-ray AP and lateral |
| `http://loinc.org` | `36710-2` | Knee - left X-ray AP and lateral |
| `http://loinc.org` | `36711-0` | Mandible X-ray AP and lateral |
| `http://loinc.org` | `36712-8` | Patella - bilateral X-ray AP and lateral |
| `http://loinc.org` | `36713-6` | Patella - left X-ray AP and lateral |
| `http://loinc.org` | `36714-4` | Scapula - bilateral X-ray AP and lateral |
| `http://loinc.org` | `36715-1` | Scapula - left X-ray AP and lateral |
| `http://loinc.org` | `36716-9` | Shoulder - bilateral X-ray AP and lateral |
| `http://loinc.org` | `36717-7` | Tibia - bilateral and Fibula - bilateral X-ray AP and lateral |
| `http://loinc.org` | `36718-5` | Tibia - left and Fibula - left X-ray AP and lateral |
| `http://loinc.org` | `36719-3` | Toes - left X-ray AP and lateral |
| `http://loinc.org` | `36720-1` | Ankle - bilateral X-ray AP and lateral and oblique |
| `http://loinc.org` | `36721-9` | Ankle - left X-ray AP and lateral and oblique |
| `http://loinc.org` | `36722-7` | Elbow X-ray AP and lateral and oblique |
| `http://loinc.org` | `36723-5` | Elbow - bilateral X-ray AP and lateral and oblique |
| `http://loinc.org` | `36724-3` | Elbow - left X-ray AP and lateral and oblique |
| `http://loinc.org` | `36725-0` | Finger X-ray AP and lateral and oblique |
| `http://loinc.org` | `36726-8` | Finger - bilateral X-ray AP and lateral and oblique |
| `http://loinc.org` | `36727-6` | Finger - left X-ray AP and lateral and oblique |
| `http://loinc.org` | `36728-4` | Foot X-ray AP and lateral and oblique |
| `http://loinc.org` | `36729-2` | Foot - bilateral X-ray AP and lateral and oblique |
| `http://loinc.org` | `36730-0` | Foot - left X-ray AP and lateral and oblique |
| `http://loinc.org` | `36731-8` | Calcaneus X-ray AP and lateral and oblique |
| `http://loinc.org` | `36732-6` | Knee - bilateral X-ray AP and lateral and oblique |
| `http://loinc.org` | `36733-4` | Knee - left X-ray AP and lateral and oblique |
| `http://loinc.org` | `36734-2` | Spine Cervical X-ray AP and lateral and oblique |
| `http://loinc.org` | `36735-9` | Spine Lumbar X-ray AP and lateral and oblique |
| `http://loinc.org` | `36736-7` | Thumb - left X-ray AP and lateral and oblique |
| `http://loinc.org` | `36737-5` | Facial bones X-ray limited |
| `http://loinc.org` | `36738-3` | Mandible X-ray limited |
| `http://loinc.org` | `36739-1` | Wrist - bilateral X-ray limited |
| `http://loinc.org` | `36740-9` | Elbow - bilateral X-ray oblique |
| `http://loinc.org` | `36741-7` | Elbow - left X-ray oblique |
| `http://loinc.org` | `36742-5` | Radius - bilateral and Ulna - bilateral X-ray oblique |
| `http://loinc.org` | `36743-3` | Radius - left and Ulna.left X-ray oblique |
| `http://loinc.org` | `36744-1` | Humerus - left X-ray oblique |
| `http://loinc.org` | `36745-8` | Knee - bilateral X-ray oblique |
| `http://loinc.org` | `36746-6` | Knee - left X-ray oblique |
| `http://loinc.org` | `36747-4` | Mandible X-ray oblique |
| `http://loinc.org` | `36748-2` | Spine Cervical X-ray oblique |
| `http://loinc.org` | `36749-0` | Tibia - left and Fibula - left X-ray oblique |
| `http://loinc.org` | `36750-8` | Chest X-ray PA and AP lateral-decubitus |
| `http://loinc.org` | `36751-6` | Chest Fluoroscopy PA and lateral |
| `http://loinc.org` | `36752-4` | Hand - bilateral X-ray PA and lateral |
| `http://loinc.org` | `36753-2` | Hand - left X-ray PA and lateral |
| `http://loinc.org` | `36754-0` | Mandible X-ray PA and lateral |
| `http://loinc.org` | `36755-7` | Hand X-ray PA and lateral and oblique |
| `http://loinc.org` | `36756-5` | Hand - bilateral X-ray PA and lateral and oblique |
| `http://loinc.org` | `36757-3` | Hand - left X-ray PA and lateral and oblique |
| `http://loinc.org` | `36758-1` | Chest X-ray PA and lateral and oblique and lordotic |
| `http://loinc.org` | `36759-9` | Chest X-ray PA and lordotic |
| `http://loinc.org` | `36760-7` | AV shunt Fluoroscopic angiogram Angioplasty W contrast |
| `http://loinc.org` | `36761-5` | Biliary ducts Fluoroscopy Balloon dilatation W contrast |
| `http://loinc.org` | `36762-3` | Extremity vessel Fluoroscopic angiogram Angioplasty W contrast |
| `http://loinc.org` | `36763-1` | Femoral artery and Popliteal artery Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `36764-9` | Femoral vessel and Popliteal artery Fluoroscopic angiogram Atherectomy W contrast |
| `http://loinc.org` | `36765-6` | Vessel Fluoroscopic angiogram Atherectomy W contrast |
| `http://loinc.org` | `36766-4` | Coronary arteries Fluoroscopic angiogram Atherectomy W contrast IA |
| `http://loinc.org` | `36767-2` | CT Guidance for biopsy of Adrenal gland |
| `http://loinc.org` | `36768-0` | CT Guidance for biopsy of Muscle |
| `http://loinc.org` | `36769-8` | CT Guidance for change of nephrostomy tube in Kidney |
| `http://loinc.org` | `36770-6` | CT Guidance for drainage of Biliary ducts and Gallbladder |
| `http://loinc.org` | `36771-4` | Fluoroscopy Guidance for injection of Joint |
| `http://loinc.org` | `36772-2` | CT Guidance for placement of nephrostomy tube in Kidney |
| `http://loinc.org` | `36773-0` | Temporal bone CT |
| `http://loinc.org` | `36774-8` | Upper extremity joint - left MRI |
| `http://loinc.org` | `36775-5` | Upper extremity joint - right MRI |
| `http://loinc.org` | `36776-3` | Mastoid X-ray tomograph |
| `http://loinc.org` | `36777-1` | Orbit MRI |
| `http://loinc.org` | `36778-9` | Orbit - right MRI |
| `http://loinc.org` | `36779-7` | Ovary MRI |
| `http://loinc.org` | `36780-5` | Toe MRI |
| `http://loinc.org` | `36781-3` | Abdominal veins MRI angiogram |
| `http://loinc.org` | `36782-1` | Subclavian artery MRI angiogram |
| `http://loinc.org` | `36783-9` | Veins MRI angiogram |
| `http://loinc.org` | `36784-7` | Lower extremity veins - left MRI angiogram |
| `http://loinc.org` | `36785-4` | Lower extremity veins - right MRI angiogram |
| `http://loinc.org` | `36786-2` | Upper extremity veins - left MRI angiogram |
| `http://loinc.org` | `36787-0` | Upper extremity veins - right MRI angiogram |
| `http://loinc.org` | `36788-8` | Neck veins MRI angiogram |
| `http://loinc.org` | `36789-6` | Pelvis veins MRI angiogram |
| `http://loinc.org` | `36790-4` | Vena cava.inferior and Lower extremity veins MRI angiogram |
| `http://loinc.org` | `36791-2` | Abdominal vessels MRI angiogram |
| `http://loinc.org` | `36792-0` | Adrenal vessels MRI angiogram |
| `http://loinc.org` | `36793-8` | Carotid vessel MRI angiogram |
| `http://loinc.org` | `36794-6` | Extremity vessels MRI angiogram |
| `http://loinc.org` | `36795-3` | Lower extremity vessels - left MRI angiogram |
| `http://loinc.org` | `36796-1` | Lower extremity vessels - right MRI angiogram |
| `http://loinc.org` | `36797-9` | Upper extremity vessels - left MRI angiogram |
| `http://loinc.org` | `36798-7` | Upper extremity vessels - right MRI angiogram |
| `http://loinc.org` | `36799-5` | Knee vessels MRI angiogram |
| `http://loinc.org` | `36800-1` | Knee vessels - left MRI angiogram |
| `http://loinc.org` | `36801-9` | Knee vessels - right MRI angiogram |
| `http://loinc.org` | `36802-7` | Orbit vessels MRI angiogram |
| `http://loinc.org` | `36803-5` | Pulmonary vessels MRI angiogram |
| `http://loinc.org` | `36804-3` | Renal vessels - bilateral MRI angiogram |
| `http://loinc.org` | `36805-0` | Shoulder vessels MRI angiogram |
| `http://loinc.org` | `36806-8` | Shoulder vessels - left MRI angiogram |
| `http://loinc.org` | `36807-6` | Shoulder vessels - right MRI angiogram |
| `http://loinc.org` | `36808-4` | Head vessels MRI angiogram limited |
| `http://loinc.org` | `36809-2` | Hepatic artery CT angiogram W contrast IA |
| `http://loinc.org` | `36810-0` | Upper Joint CT W contrast intraarticular |
| `http://loinc.org` | `36811-8` | Joint CT W contrast intraarticular |
| `http://loinc.org` | `36812-6` | Joint MRI W contrast intraarticular |
| `http://loinc.org` | `36813-4` | Abdomen and Pelvis CT W contrast IV |
| `http://loinc.org` | `36814-2` | Head arteries CT angiogram W contrast IV |
| `http://loinc.org` | `36815-9` | Temporal bone CT W contrast IV |
| `http://loinc.org` | `36816-7` | Temporal bone - right CT W contrast IV |
| `http://loinc.org` | `36817-5` | Upper extremity joint - bilateral MRI W contrast IV |
| `http://loinc.org` | `36818-3` | Upper extremity joint - left MRI W contrast IV |
| `http://loinc.org` | `36819-1` | Upper extremity joint - right MRI W contrast IV |
| `http://loinc.org` | `36820-9` | Orbit MRI W contrast IV |
| `http://loinc.org` | `36821-7` | Orbit - left MRI W contrast IV |
| `http://loinc.org` | `36822-5` | Orbit - right MRI W contrast IV |
| `http://loinc.org` | `36823-3` | Ovary MRI W contrast IV |
| `http://loinc.org` | `36824-1` | Lower extremity veins - left CT W contrast IV |
| `http://loinc.org` | `36825-8` | Lower extremity veins - right CT W contrast IV |
| `http://loinc.org` | `36826-6` | Head veins MRI angiogram W contrast IV |
| `http://loinc.org` | `36827-4` | Neck veins MRI angiogram W contrast IV |
| `http://loinc.org` | `36828-2` | Abdominal vessels CT angiogram W contrast IV |
| `http://loinc.org` | `36829-0` | Carotid vessel MRI angiogram W contrast IV |
| `http://loinc.org` | `36830-8` | Head vessels CT angiogram W contrast IV |
| `http://loinc.org` | `36831-6` | Lower extremity vessels CT angiogram W contrast IV |
| `http://loinc.org` | `36832-4` | Orbit vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `36833-2` | Renal vessels CT angiogram W contrast IV |
| `http://loinc.org` | `36834-0` | Vessel CT angiogram W contrast IV |
| `http://loinc.org` | `36835-7` | Petrous bone CT W and WO contrast IV |
| `http://loinc.org` | `36837-3` | Temporal bone CT W and WO contrast IV |
| `http://loinc.org` | `36838-1` | Mastoid X-ray 3 views |
| `http://loinc.org` | `36839-9` | Mastoid X-ray 4 views |
| `http://loinc.org` | `36840-7` | Upper extremity joint - left MRI W and WO contrast IV |
| `http://loinc.org` | `36841-5` | Upper extremity joint - right MRI W and WO contrast IV |
| `http://loinc.org` | `36842-3` | Orbit MRI W and WO contrast IV |
| `http://loinc.org` | `36843-1` | Orbit - left MRI W and WO contrast IV |
| `http://loinc.org` | `36844-9` | Orbit - right MRI W and WO contrast IV |
| `http://loinc.org` | `36845-6` | Ovary MRI W and WO contrast IV |
| `http://loinc.org` | `36846-4` | Abdominal veins MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36847-2` | Head veins MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36848-0` | Chest veins MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36849-8` | Lower extremity veins - left MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36850-6` | Lower extremity veins - right MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36851-4` | Upper extremity veins - left MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36852-2` | Upper extremity veins - right MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36853-0` | Neck veins MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36854-8` | Pelvis veins MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36855-5` | Abdominal vessels MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36856-3` | Carotid vessel MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36857-1` | Head vessels MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36858-9` | Lower extremity vessels - left MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36859-7` | Lower extremity vessels - right MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36860-5` | Upper extremity vessels - left MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36861-3` | Upper extremity vessels - right MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36862-1` | Knee vessels - right MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36863-9` | Pelvis vessels MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36864-7` | Shoulder vessels - left MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36865-4` | Shoulder vessels - right MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `36866-2` | Temporal bone CT WO contrast |
| `http://loinc.org` | `36867-0` | Temporal bone - left CT WO contrast |
| `http://loinc.org` | `36868-8` | Temporal bone - right CT WO contrast |
| `http://loinc.org` | `36869-6` | Upper extremity joint - left MRI WO contrast |
| `http://loinc.org` | `36870-4` | Upper extremity joint - right MRI WO contrast |
| `http://loinc.org` | `36871-2` | Joint MRI WO contrast |
| `http://loinc.org` | `36872-0` | Orbit MRI WO contrast |
| `http://loinc.org` | `36873-8` | Orbit - left MRI WO contrast |
| `http://loinc.org` | `36874-6` | Orbit - right MRI WO contrast |
| `http://loinc.org` | `36875-3` | Ovary MRI WO contrast |
| `http://loinc.org` | `36876-1` | Head veins MRI angiogram WO contrast |
| `http://loinc.org` | `36877-9` | Neck veins MRI angiogram WO contrast |
| `http://loinc.org` | `36878-7` | Abdominal vessels MRI angiogram WO contrast |
| `http://loinc.org` | `36879-5` | Ankle vessels MRI angiogram WO contrast |
| `http://loinc.org` | `36880-3` | Carotid vessel MRI angiogram WO contrast |
| `http://loinc.org` | `36881-1` | Head vessels MRI angiogram WO contrast |
| `http://loinc.org` | `36882-9` | Lower extremity vessels - left MRI angiogram WO contrast |
| `http://loinc.org` | `36883-7` | Pelvis vessels MRI angiogram WO contrast |
| `http://loinc.org` | `36886-0` | Orbit X-ray |
| `http://loinc.org` | `36887-8` | Orbit - left X-ray |
| `http://loinc.org` | `36890-2` | Mastoid X-ray 5 views |
| `http://loinc.org` | `36893-6` | Mastoid X-ray limited |
| `http://loinc.org` | `36894-4` | Tibia and Fibula X-ray oblique |
| `http://loinc.org` | `36926-4` | CT Guidance for aspiration and placement of drainage tube of Abdomen |
| `http://loinc.org` | `36927-2` | CT Guidance for biopsy of Facial bones and Maxilla |
| `http://loinc.org` | `36928-0` | CT Guidance.stereotactic for biopsy of Head |
| `http://loinc.org` | `36929-8` | CT Guidance.stereotactic for biopsy of Head-- WO contrast |
| `http://loinc.org` | `36930-6` | Adrenal gland CT |
| `http://loinc.org` | `36931-4` | Adrenal gland MRI |
| `http://loinc.org` | `36932-2` | Pituitary and Sella turcica CT |
| `http://loinc.org` | `36933-0` | Salivary gland MRI |
| `http://loinc.org` | `36934-8` | Heart CT for scoring |
| `http://loinc.org` | `36935-5` | Heart CT for scoring W contrast IV |
| `http://loinc.org` | `36936-3` | MRI Guidance.stereotactic for biopsy of Brain |
| `http://loinc.org` | `36937-1` | Facial bones and Maxilla CT limited |
| `http://loinc.org` | `36938-9` | Facial bones and Maxilla CT limited WO contrast |
| `http://loinc.org` | `36939-7` | Spine CT stereotactic |
| `http://loinc.org` | `36940-5` | Unspecified body region CT stereotactic |
| `http://loinc.org` | `36941-3` | Salivary gland CT W contrast intra salivary duct |
| `http://loinc.org` | `36942-1` | Chest and Abdomen MRI W contrast IV |
| `http://loinc.org` | `36943-9` | Adrenal gland CT W contrast IV |
| `http://loinc.org` | `36944-7` | Biliary ducts and Pancreatic duct MRI W and WO contrast IV |
| `http://loinc.org` | `36945-4` | Knee - bilateral X-ray 2 views standing |
| `http://loinc.org` | `36946-2` | Spine Lumbar X-ray 2 views standing |
| `http://loinc.org` | `36947-0` | Foot - bilateral X-ray 3 views standing |
| `http://loinc.org` | `36948-8` | Foot - left X-ray 3 views standing |
| `http://loinc.org` | `36949-6` | Spine Lumbar X-ray 3 views standing |
| `http://loinc.org` | `36950-4` | Adrenal gland CT W and WO contrast IV |
| `http://loinc.org` | `36951-2` | Adrenal gland MRI W and WO contrast IV |
| `http://loinc.org` | `36952-0` | Abdomen and Pelvis CT WO contrast |
| `http://loinc.org` | `36953-8` | Adrenal gland CT WO contrast |
| `http://loinc.org` | `36954-6` | Adrenal gland MRI WO contrast |
| `http://loinc.org` | `36955-3` | Thyroid CT WO contrast |
| `http://loinc.org` | `36956-1` | Orbit and Face MRI WO contrast |
| `http://loinc.org` | `36957-9` | Facial bones and Maxilla CT and 3D reconstruction |
| `http://loinc.org` | `36958-7` | Ribs - bilateral X-ray AP single view |
| `http://loinc.org` | `36959-5` | Ribs - left X-ray AP single view |
| `http://loinc.org` | `36960-3` | Chest X-ray AP upright portable |
| `http://loinc.org` | `36961-1` | Shoulder - left X-ray AP and West Point and outlet |
| `http://loinc.org` | `36962-9` | Breast Mammogram axillary |
| `http://loinc.org` | `36963-7` | Shoulder - bilateral X-ray axillary |
| `http://loinc.org` | `36964-5` | Shoulder - left X-ray axillary |
| `http://loinc.org` | `36965-2` | Hand X-ray Ball Catcher |
| `http://loinc.org` | `36966-0` | Hand - bilateral X-ray Brewerton |
| `http://loinc.org` | `36967-8` | Hand - left X-ray Brewerton |
| `http://loinc.org` | `36968-6` | Wrist - bilateral X-ray W clenched fist |
| `http://loinc.org` | `36971-0` | Wrist - left X-ray lateral W extension |
| `http://loinc.org` | `36972-8` | Wrist - left X-ray lateral W flexion |
| `http://loinc.org` | `36973-6` | Hip X-ray Friedman |
| `http://loinc.org` | `36974-4` | Shoulder - left X-ray Garth |
| `http://loinc.org` | `36975-1` | Calcaneus - bilateral X-ray Harris |
| `http://loinc.org` | `36976-9` | Foot X-ray Harris |
| `http://loinc.org` | `36977-7` | Calcaneus - left X-ray Harris |
| `http://loinc.org` | `36978-5` | Knee X-ray Holmblad |
| `http://loinc.org` | `36979-3` | Elbow X-ray Jones |
| `http://loinc.org` | `36980-1` | Elbow - left X-ray Jones |
| `http://loinc.org` | `36981-9` | Hip X-ray Judet |
| `http://loinc.org` | `36982-7` | Hip - bilateral X-ray Judet |
| `http://loinc.org` | `36983-5` | Hip - left X-ray Judet |
| `http://loinc.org` | `36984-3` | Abdomen X-ray lateral crosstable |
| `http://loinc.org` | `36985-0` | Hip X-ray lateral crosstable |
| `http://loinc.org` | `36986-8` | Hip - bilateral X-ray lateral crosstable |
| `http://loinc.org` | `36987-6` | Hip - left X-ray lateral crosstable |
| `http://loinc.org` | `36988-4` | Knee X-ray lateral crosstable |
| `http://loinc.org` | `36989-2` | Spine Cervical X-ray lateral crosstable |
| `http://loinc.org` | `36990-0` | Spine Lumbar X-ray lateral crosstable |
| `http://loinc.org` | `36991-8` | Spine Cervical X-ray lateral crosstable portable |
| `http://loinc.org` | `36992-6` | Spine Lumbar X-ray lateral crosstable portable |
| `http://loinc.org` | `36993-4` | Hip - bilateral X-ray lateral frog |
| `http://loinc.org` | `36994-2` | Hip - left X-ray lateral frog |
| `http://loinc.org` | `36995-9` | Abdomen X-ray left lateral |
| `http://loinc.org` | `36996-7` | Abdomen X-ray right lateral |
| `http://loinc.org` | `36997-5` | Spine Cervical X-ray lateral W extension |
| `http://loinc.org` | `36998-3` | Spine Cervical X-ray lateral W flexion |
| `http://loinc.org` | `36999-1` | Knee - bilateral X-ray lateral hyperextension |
| `http://loinc.org` | `37000-7` | Knee - left X-ray lateral hyperextension |
| `http://loinc.org` | `37001-5` | Foot X-ray lateral standing |
| `http://loinc.org` | `37002-3` | Knee - left X-ray lateral standing |
| `http://loinc.org` | `37003-1` | Spine Lumbar X-ray lateral standing |
| `http://loinc.org` | `37004-9` | Knee X-ray Laurin |
| `http://loinc.org` | `37005-6` | Breast - left Mammogram magnification |
| `http://loinc.org` | `37006-4` | Breast - bilateral Mammogram MLO |
| `http://loinc.org` | `37007-2` | Ankle X-ray Mortise |
| `http://loinc.org` | `37008-0` | Chest X-ray left oblique |
| `http://loinc.org` | `37009-8` | Spine Lumbar X-ray left oblique |
| `http://loinc.org` | `37010-6` | Chest X-ray right oblique |
| `http://loinc.org` | `37011-4` | Spine Lumbar X-ray right oblique |
| `http://loinc.org` | `37012-2` | Shoulder - bilateral X-ray outlet |
| `http://loinc.org` | `37013-0` | Shoulder - left X-ray outlet |
| `http://loinc.org` | `37014-8` | Knee - left X-ray PA standing |
| `http://loinc.org` | `37015-5` | Abdomen X-ray PA prone |
| `http://loinc.org` | `37016-3` | Breast - bilateral Mammogram roll |
| `http://loinc.org` | `37017-1` | Breast - left Mammogram roll |
| `http://loinc.org` | `37018-9` | Knee X-ray Rosenberg standing |
| `http://loinc.org` | `37019-7` | Knee - left X-ray Rosenberg standing |
| `http://loinc.org` | `37020-5` | Knee - bilateral X-ray Rosenberg standing |
| `http://loinc.org` | `37021-3` | Calcaneus - bilateral X-ray ski jump |
| `http://loinc.org` | `37022-1` | Calcaneus X-ray ski jump |
| `http://loinc.org` | `37023-9` | Calcaneus - left X-ray ski jump |
| `http://loinc.org` | `37024-7` | Shoulder - bilateral X-ray Stryker Notch |
| `http://loinc.org` | `37025-4` | Shoulder - left X-ray Stryker Notch |
| `http://loinc.org` | `37026-2` | Skull X-ray submentovertex |
| `http://loinc.org` | `37027-0` | Knee - bilateral X-ray Sunrise |
| `http://loinc.org` | `37028-8` | Breast Mammogram tangential |
| `http://loinc.org` | `37029-6` | Breast - bilateral Mammogram tangential |
| `http://loinc.org` | `37030-4` | Breast - left Mammogram tangential |
| `http://loinc.org` | `37031-2` | Humerus X-ray transthoracic |
| `http://loinc.org` | `37032-0` | Humerus - bilateral X-ray transthoracic |
| `http://loinc.org` | `37033-8` | Humerus - left X-ray transthoracic |
| `http://loinc.org` | `37034-6` | Shoulder - left X-ray transthoracic |
| `http://loinc.org` | `37035-3` | Shoulder - bilateral X-ray Grashey |
| `http://loinc.org` | `37037-9` | Breast Mammogram true lateral |
| `http://loinc.org` | `37038-7` | Breast - bilateral Mammogram true lateral |
| `http://loinc.org` | `37039-5` | Hip X-ray true lateral |
| `http://loinc.org` | `37040-3` | Hip - left X-ray true lateral |
| `http://loinc.org` | `37041-1` | Knee - bilateral X-ray tunnel |
| `http://loinc.org` | `37042-9` | Knee - left X-ray tunnel |
| `http://loinc.org` | `37043-7` | Knee - left X-ray tunnel standing |
| `http://loinc.org` | `37044-5` | Wrist - left X-ray ulnar deviation |
| `http://loinc.org` | `37045-2` | Wrist - bilateral X-ray ulnar variance |
| `http://loinc.org` | `37046-0` | Abdomen X-ray upright |
| `http://loinc.org` | `37047-8` | Shoulder - bilateral X-ray Velpeau axillary |
| `http://loinc.org` | `37048-6` | Shoulder - left X-ray Velpeau axillary |
| `http://loinc.org` | `37049-4` | Hip X-ray Von rossen |
| `http://loinc.org` | `37050-2` | Shoulder - bilateral X-ray West Point |
| `http://loinc.org` | `37051-0` | Shoulder - left X-ray West Point |
| `http://loinc.org` | `37052-8` | Breast - bilateral Mammogram XCCL |
| `http://loinc.org` | `37053-6` | Breast - left Mammogram XCCL |
| `http://loinc.org` | `37054-4` | Scapula - left X-ray Y |
| `http://loinc.org` | `37055-1` | Scapula - bilateral X-ray Y |
| `http://loinc.org` | `37056-9` | Acromioclavicular joint - bilateral X-ray Zanca |
| `http://loinc.org` | `37057-7` | Acromioclavicular joint - left X-ray Zanca |
| `http://loinc.org` | `37058-5` | Calcaneus - bilateral X-ray standing |
| `http://loinc.org` | `37059-3` | Hip - bilateral X-ray standing |
| `http://loinc.org` | `37060-1` | Fetal X-ray |
| `http://loinc.org` | `37062-7` | Humerus - bilateral X-ray |
| `http://loinc.org` | `37063-5` | Unspecified body region Fluoroscopy of foreign body |
| `http://loinc.org` | `37064-3` | Acetabulum - left X-ray 2 views |
| `http://loinc.org` | `37066-8` | Ribs - left X-ray 2 views |
| `http://loinc.org` | `37067-6` | Chest X-ray 2 views W nipple markers |
| `http://loinc.org` | `37068-4` | Foot - bilateral X-ray 2 views standing |
| `http://loinc.org` | `37069-2` | Foot - left X-ray 2 views standing |
| `http://loinc.org` | `37070-0` | Wrist - bilateral X-ray 4 views |
| `http://loinc.org` | `37071-8` | Wrist - left X-ray 4 views |
| `http://loinc.org` | `37072-6` | Wrist - left X-ray 5 views |
| `http://loinc.org` | `37073-4` | Spine Lumbar X-ray 5 views standing |
| `http://loinc.org` | `37074-2` | Wrist - left X-ray 6 views |
| `http://loinc.org` | `37075-9` | Hip X-ray AP portable |
| `http://loinc.org` | `37076-7` | Abdomen X-ray AP (supine and lateral-decubitus) portable |
| `http://loinc.org` | `37077-5` | Hip X-ray AP and lateral crosstable portable |
| `http://loinc.org` | `37078-3` | Spine Lumbar X-ray AP and lateral portable |
| `http://loinc.org` | `37079-1` | Spine Cervical X-ray AP and lateral and odontoid portable |
| `http://loinc.org` | `37080-9` | Shoulder - bilateral X-ray AP and axillary |
| `http://loinc.org` | `37081-7` | Shoulder - bilateral X-ray AP and axillary and outlet |
| `http://loinc.org` | `37082-5` | Shoulder - left X-ray AP and axillary and outlet |
| `http://loinc.org` | `37083-3` | Shoulder - left X-ray AP and axillary and outlet and Zanca |
| `http://loinc.org` | `37084-1` | Shoulder - left X-ray AP and axillary and Y |
| `http://loinc.org` | `37085-8` | Abdomen X-ray AP (supine and lateral-decubitus) |
| `http://loinc.org` | `37086-6` | Hip X-ray AP and lateral crosstable |
| `http://loinc.org` | `37087-4` | Hip - left X-ray AP and lateral crosstable |
| `http://loinc.org` | `37088-2` | Pelvis and Hip - left X-ray AP and lateral crosstable |
| `http://loinc.org` | `37089-0` | Pelvis and Hip X-ray AP and lateral crosstable |
| `http://loinc.org` | `37090-8` | Knee X-ray AP and lateral crosstable |
| `http://loinc.org` | `37091-6` | Hip X-ray AP and lateral frog |
| `http://loinc.org` | `37092-4` | Hip - bilateral X-ray AP and lateral frog |
| `http://loinc.org` | `37093-2` | Hip - left X-ray AP and lateral frog |
| `http://loinc.org` | `37094-0` | Pelvis and Hip - left X-ray AP and lateral frog |
| `http://loinc.org` | `37095-7` | Ankle X-ray AP and lateral and Mortise |
| `http://loinc.org` | `37096-5` | Ankle - bilateral X-ray AP and lateral and Mortise |
| `http://loinc.org` | `37097-3` | Ankle - left X-ray AP and lateral and Mortise |
| `http://loinc.org` | `37098-1` | Spine Cervical X-ray AP and oblique and lateral W flexion and W extension |
| `http://loinc.org` | `37099-9` | Spine Cervical X-ray AP and lateral and oblique and odontoid |
| `http://loinc.org` | `37100-5` | Spine Cervical X-ray AP and oblique and odontoid and lateral W flexion and W extension |
| `http://loinc.org` | `37101-3` | Spine Lumbar X-ray AP and lateral and oblique and spot |
| `http://loinc.org` | `37102-1` | Knee - bilateral X-ray AP and lateral and oblique and Sunrise |
| `http://loinc.org` | `37103-9` | Spine Cervical X-ray AP and lateral and odontoid |
| `http://loinc.org` | `37104-7` | Spine Cervical X-ray AP and odontoid and lateral W flexion and W extension |
| `http://loinc.org` | `37105-4` | Spine Lumbar X-ray AP and lateral and spot |
| `http://loinc.org` | `37106-2` | Knee X-ray AP and lateral and Sunrise |
| `http://loinc.org` | `37107-0` | Knee - bilateral X-ray AP and lateral and Sunrise |
| `http://loinc.org` | `37108-8` | Knee - left X-ray AP and lateral and Sunrise |
| `http://loinc.org` | `37109-6` | Patella - bilateral X-ray AP and lateral and Sunrise |
| `http://loinc.org` | `37110-4` | Patella - left X-ray AP and lateral and Sunrise |
| `http://loinc.org` | `37111-2` | Knee X-ray AP and lateral and Sunrise and tunnel |
| `http://loinc.org` | `37112-0` | Knee X-ray AP and lateral and tunnel |
| `http://loinc.org` | `37113-8` | Knee - bilateral X-ray AP and lateral and tunnel |
| `http://loinc.org` | `37114-6` | Knee - left X-ray AP and lateral and tunnel |
| `http://loinc.org` | `37115-3` | Knee X-ray AP and lateral and oblique and tunnel |
| `http://loinc.org` | `37116-1` | Knee - bilateral X-ray AP and lateral and Sunrise and tunnel |
| `http://loinc.org` | `37117-9` | Knee - left X-ray AP and lateral and Sunrise and tunnel |
| `http://loinc.org` | `37118-7` | Knee - bilateral X-ray AP and lateral and oblique and Sunrise and tunnel |
| `http://loinc.org` | `37119-5` | Abdomen X-ray AP and oblique |
| `http://loinc.org` | `37120-3` | Spine Cervical X-ray AP and odontoid and lateral crosstable |
| `http://loinc.org` | `37121-1` | Clavicle - left X-ray AP and Serendipity |
| `http://loinc.org` | `37122-9` | Shoulder - left X-ray AP and Stryker Notch |
| `http://loinc.org` | `37123-7` | Shoulder - left X-ray AP and West Point |
| `http://loinc.org` | `37124-5` | Scapula - left X-ray AP and Y |
| `http://loinc.org` | `37125-2` | Shoulder - left X-ray AP and Y |
| `http://loinc.org` | `37126-0` | Shoulder - bilateral X-ray AP and axillary and Y |
| `http://loinc.org` | `37127-8` | Shoulder - bilateral X-ray axillary and Y |
| `http://loinc.org` | `37128-6` | Shoulder - left X-ray axillary and Y |
| `http://loinc.org` | `37131-0` | Abdomen X-ray right lateral and left lateral |
| `http://loinc.org` | `37132-8` | Spine Lumbar X-ray lateral W flexion and W extension |
| `http://loinc.org` | `37133-6` | Spine Cervical X-ray lateral W flexion and W extension |
| `http://loinc.org` | `37134-4` | Ankle - bilateral X-ray lateral and Mortise |
| `http://loinc.org` | `37135-1` | Ankle - left X-ray lateral and Mortise |
| `http://loinc.org` | `37136-9` | Shoulder - left X-ray lateral and Y |
| `http://loinc.org` | `37137-7` | Kidney X-ray limited W contrast IV |
| `http://loinc.org` | `37138-5` | Abdomen X-ray right oblique and left oblique |
| `http://loinc.org` | `37139-3` | Spine Cervical X-ray oblique and lateral W flexion and W extension |
| `http://loinc.org` | `37140-1` | Shoulder - left X-ray outlet and Y |
| `http://loinc.org` | `37141-9` | Chest X-ray PA and right lateral |
| `http://loinc.org` | `37142-7` | Hand - bilateral X-ray PA and lateral and Ball Catcher |
| `http://loinc.org` | `37143-5` | Chest X-ray PA and lateral and AP lateral-decubitus |
| `http://loinc.org` | `37144-3` | Chest X-ray PA and lateral and AP left lateral-decubitus |
| `http://loinc.org` | `37145-0` | Chest X-ray PA and lateral and AP right lateral-decubitus |
| `http://loinc.org` | `37146-8` | Chest X-ray PA and lateral and left oblique |
| `http://loinc.org` | `37147-6` | Chest X-ray PA and lateral and right oblique |
| `http://loinc.org` | `37148-4` | Mandible X-ray PA and lateral and oblique and Towne |
| `http://loinc.org` | `37149-2` | Patella - left X-ray PA and lateral and Sunrise |
| `http://loinc.org` | `37150-0` | Chest X-ray PA and right oblique and left oblique |
| `http://loinc.org` | `37151-8` | Unspecified body region Fluoroscopy portable |
| `http://loinc.org` | `37152-6` | Shoulder - bilateral X-ray outlet and Y |
| `http://loinc.org` | `37153-4` | Mastoid X-ray Stenver and Arcelin |
| `http://loinc.org` | `37154-2` | Knee X-ray oblique and Sunrise |
| `http://loinc.org` | `37155-9` | Knee X-ray oblique and Sunrise and tunnel |
| `http://loinc.org` | `37156-7` | Knee - left X-ray Sunrise and tunnel |
| `http://loinc.org` | `37157-5` | Shoulder - left X-ray Grashey and outlet |
| `http://loinc.org` | `37158-3` | Shoulder - left X-ray Grashey and axillary and outlet |
| `http://loinc.org` | `37159-1` | Foot - left X-ray tarsal |
| `http://loinc.org` | `37160-9` | Shoulder - left X-ray Grashey and axillary |
| `http://loinc.org` | `37161-7` | Shoulder - bilateral X-ray Grashey and axillary and outlet and Zanca |
| `http://loinc.org` | `37162-5` | Shoulder - left X-ray Grashey and outlet and Serendipity |
| `http://loinc.org` | `37163-3` | Knee - bilateral X-ray Sunrise and tunnel |
| `http://loinc.org` | `37164-1` | Facial bones X-ray lateral and Caldwell and Waters |
| `http://loinc.org` | `37165-8` | Facial bones X-ray lateral and Caldwell and Waters and submentovertex |
| `http://loinc.org` | `37166-6` | Facial bones X-ray lateral and Caldwell and Waters and submentovertex and Towne |
| `http://loinc.org` | `37167-4` | Shoulder - left X-ray Grashey and West Point |
| `http://loinc.org` | `37168-2` | Hip X-ray portable |
| `http://loinc.org` | `37169-0` | Hip - left X-ray portable |
| `http://loinc.org` | `37170-8` | Humerus X-ray portable |
| `http://loinc.org` | `37171-6` | Spine Cervical X-ray portable |
| `http://loinc.org` | `37172-4` | Spine Lumbar X-ray portable |
| `http://loinc.org` | `37173-2` | Cerebral artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37174-0` | Coronary arteries Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37175-7` | Femoral artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37176-5` | Femoral artery and Popliteal artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37177-3` | Iliac artery - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37178-1` | Iliac artery - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37179-9` | Inferior mesenteric artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37180-7` | Superior mesenteric artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37181-5` | Popliteal artery - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37182-3` | Pulmonary artery - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37183-1` | Ankle Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37184-9` | Ankle - bilateral Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37185-6` | Ankle - left Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37186-4` | Elbow Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37187-2` | Elbow - bilateral Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37188-0` | Elbow - left Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37189-8` | Sacroiliac joint - bilateral Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37190-6` | Sacroiliac joint - left Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37191-4` | Joint Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37192-2` | Spine Cervical Fluoroscopy W contrast intradisc |
| `http://loinc.org` | `37193-0` | Spine Lumbar Fluoroscopy W contrast intradisc |
| `http://loinc.org` | `37195-5` | Cerebral vein Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37196-3` | Lower extremity veins - left Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37197-1` | Jugular vein Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37198-9` | Esophagus X-ray W contrast PO |
| `http://loinc.org` | `37199-7` | Chest Fluoroscopy W contrast PO |
| `http://loinc.org` | `37200-3` | Chest X-ray W contrast PO |
| `http://loinc.org` | `37201-1` | Ankle X-ray standing |
| `http://loinc.org` | `37202-9` | Ankle - bilateral X-ray standing |
| `http://loinc.org` | `37203-7` | Ankle - left X-ray standing |
| `http://loinc.org` | `37204-5` | Lower extremity X-ray standing |
| `http://loinc.org` | `37205-2` | Calcaneus X-ray standing |
| `http://loinc.org` | `37206-0` | Calcaneus - left X-ray standing |
| `http://loinc.org` | `37207-8` | Hip - left X-ray standing |
| `http://loinc.org` | `37208-6` | Spine Lumbar X-ray standing |
| `http://loinc.org` | `37209-4` | Toes - left X-ray standing |
| `http://loinc.org` | `37210-2` | CT Guidance for aspiration of cyst of Abdomen |
| `http://loinc.org` | `37211-0` | CT Guidance for biopsy of Bone marrow |
| `http://loinc.org` | `37212-8` | CT Guidance for biopsy of Epididymis |
| `http://loinc.org` | `37213-6` | CT Guidance for biopsy of Mediastinum |
| `http://loinc.org` | `37214-4` | CT Guidance for biopsy of Superficial tissue |
| `http://loinc.org` | `37215-1` | Brain and Larynx MRI W contrast IV |
| `http://loinc.org` | `37216-9` | Aorta.endograft CT |
| `http://loinc.org` | `37217-7` | Brain Stem and Nerves.cranial MRI |
| `http://loinc.org` | `37218-5` | Brain.temporal MRI |
| `http://loinc.org` | `37219-3` | Biliary ducts MRI |
| `http://loinc.org` | `37220-1` | Biliary ducts and Pancreatic duct MRI |
| `http://loinc.org` | `37221-9` | Fistula CT |
| `http://loinc.org` | `37222-7` | Ankle and Foot MRI |
| `http://loinc.org` | `37223-5` | Parotid gland CT |
| `http://loinc.org` | `37224-3` | Parotid gland MRI |
| `http://loinc.org` | `37225-0` | Sternoclavicular Joint CT |
| `http://loinc.org` | `37226-8` | Temporomandibular joint CT |
| `http://loinc.org` | `37227-6` | Temporomandibular joint - bilateral X-ray tomograph |
| `http://loinc.org` | `37228-4` | Temporomandibular joint - bilateral MRI |
| `http://loinc.org` | `37229-2` | Temporomandibular joint - left X-ray tomograph |
| `http://loinc.org` | `37230-0` | Temporomandibular joint - left MRI |
| `http://loinc.org` | `37231-8` | Temporomandibular joint - right MRI |
| `http://loinc.org` | `37232-6` | Spine Lumbosacral Junction CT |
| `http://loinc.org` | `37233-4` | Mediastinum X-ray tomograph |
| `http://loinc.org` | `37234-2` | Mediastinum MRI |
| `http://loinc.org` | `37235-9` | Circle of Willis MRI angiogram |
| `http://loinc.org` | `37236-7` | Great vessel MRI |
| `http://loinc.org` | `37237-5` | Sinus tract CT W contrast intra sinus tract |
| `http://loinc.org` | `37238-3` | Lower Extremity Joint CT W contrast intraarticular |
| `http://loinc.org` | `37239-1` | Brain and Internal auditory canal MRI W contrast IV |
| `http://loinc.org` | `37240-9` | Parotid gland CT W contrast IV |
| `http://loinc.org` | `37241-7` | Parotid gland MRI W contrast IV |
| `http://loinc.org` | `37242-5` | Sternoclavicular Joint CT W contrast IV |
| `http://loinc.org` | `37243-3` | Temporomandibular joint CT W contrast IV |
| `http://loinc.org` | `37244-1` | Temporomandibular joint MRI W contrast IV |
| `http://loinc.org` | `37245-8` | Temporomandibular joint - bilateral MRI W contrast IV |
| `http://loinc.org` | `37246-6` | Temporomandibular joint - left CT W contrast IV |
| `http://loinc.org` | `37247-4` | Temporomandibular joint - left MRI W contrast IV |
| `http://loinc.org` | `37248-2` | Temporomandibular joint - right CT W contrast IV |
| `http://loinc.org` | `37249-0` | Temporomandibular joint - right MRI W contrast IV |
| `http://loinc.org` | `37253-2` | Soft tissue MRI W contrast IV |
| `http://loinc.org` | `37254-0` | Circle of Willis MRI angiogram W contrast IV |
| `http://loinc.org` | `37256-5` | Pelvis and Spine Lumbar X-ray 3 views |
| `http://loinc.org` | `37257-3` | Spine Lumbar and Sacroiliac Joint X-ray 3 views |
| `http://loinc.org` | `37259-9` | Spine Lumbar and Sacrum X-ray 3 views |
| `http://loinc.org` | `37260-7` | Spine Lumbar and Sacrum and Coccyx X-ray 3 views |
| `http://loinc.org` | `37261-5` | Spine Lumbar and Sacrum and Sacroiliac Joint and Coccyx X-ray 3 views |
| `http://loinc.org` | `37265-6` | Parotid gland MRI W and WO contrast IV |
| `http://loinc.org` | `37266-4` | Sternoclavicular Joint CT W and WO contrast IV |
| `http://loinc.org` | `37267-2` | Temporomandibular joint CT W and WO contrast IV |
| `http://loinc.org` | `37268-0` | Temporomandibular joint MRI W and WO contrast IV |
| `http://loinc.org` | `37269-8` | Temporomandibular joint - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `37270-6` | Temporomandibular joint - left MRI W and WO contrast IV |
| `http://loinc.org` | `37271-4` | Temporomandibular joint - right MRI W and WO contrast IV |
| `http://loinc.org` | `37272-2` | Mediastinum MRI W and WO contrast IV |
| `http://loinc.org` | `37277-1` | Spinal vein MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `37278-9` | Brain and Internal auditory canal MRI WO contrast |
| `http://loinc.org` | `37279-7` | Brain and Larynx MRI WO contrast |
| `http://loinc.org` | `37280-5` | Parotid gland CT WO contrast |
| `http://loinc.org` | `37281-3` | Parotid gland MRI WO contrast |
| `http://loinc.org` | `37282-1` | Sternoclavicular Joint CT WO contrast |
| `http://loinc.org` | `37283-9` | Temporomandibular joint CT WO contrast |
| `http://loinc.org` | `37284-7` | Temporomandibular joint MRI WO contrast |
| `http://loinc.org` | `37285-4` | Temporomandibular joint - bilateral MRI WO contrast |
| `http://loinc.org` | `37286-2` | Temporomandibular joint - left MRI WO contrast |
| `http://loinc.org` | `37287-0` | Temporomandibular joint - right MRI WO contrast |
| `http://loinc.org` | `37288-8` | Spine Lumbosacral Junction CT WO contrast |
| `http://loinc.org` | `37293-8` | Soft tissue MRI WO contrast |
| `http://loinc.org` | `37294-6` | Head CT and 3D reconstruction |
| `http://loinc.org` | `37295-3` | Femur and Hip CT and anteversion measurement |
| `http://loinc.org` | `37297-9` | Abdomen and Fetus X-ray View for fetal age |
| `http://loinc.org` | `37298-7` | Sternoclavicular joint - bilateral X-ray Serendipity |
| `http://loinc.org` | `37299-5` | Sternoclavicular joint - left X-ray Serendipity |
| `http://loinc.org` | `37300-1` | Spine Lumbosacral Junction X-ray true AP |
| `http://loinc.org` | `37302-7` | Wrist - left X-ray scaphoid |
| `http://loinc.org` | `37303-5` | Facial bones and Zygomatic arch X-ray |
| `http://loinc.org` | `37304-3` | Wrist - bilateral X-ray scaphoid |
| `http://loinc.org` | `37319-1` | Humerus bicipital groove X-ray |
| `http://loinc.org` | `37320-9` | Humerus bicipital groove - left X-ray |
| `http://loinc.org` | `37321-7` | Humerus bicipital groove - bilateral X-ray |
| `http://loinc.org` | `37323-3` | Sternoclavicular joint - bilateral X-ray |
| `http://loinc.org` | `37324-1` | Sternoclavicular joint - left X-ray |
| `http://loinc.org` | `37325-8` | Temporomandibular joint - bilateral X-ray |
| `http://loinc.org` | `37332-4` | Olecranon - left X-ray |
| `http://loinc.org` | `37338-1` | Skull and Facial bones and Mandible X-ray |
| `http://loinc.org` | `37340-7` | Spine Lumbar and Sacrum X-ray |
| `http://loinc.org` | `37341-5` | Spine Lumbar and Sacrum and Coccyx X-ray |
| `http://loinc.org` | `37342-3` | Spine Lumbar and Sacrum and Sacroiliac Joint and Coccyx X-ray |
| `http://loinc.org` | `37348-0` | Toes - bilateral X-ray 2 views |
| `http://loinc.org` | `37350-6` | Temporomandibular joint - bilateral X-ray 5 views |
| `http://loinc.org` | `37351-4` | Pelvis and Spine Lumbar X-ray 5 views |
| `http://loinc.org` | `37353-0` | Spine Lumbar and Sacroiliac Joint X-ray 5 views |
| `http://loinc.org` | `37355-5` | Spine Lumbar and Sacrum X-ray 5 views |
| `http://loinc.org` | `37356-3` | Spine Lumbar and Sacrum and Coccyx X-ray 5 views |
| `http://loinc.org` | `37357-1` | Spine Lumbar and Sacrum and Sacroiliac Joint and Coccyx X-ray 5 views |
| `http://loinc.org` | `37361-3` | Spine Cervical and Spine Thoracic X-ray AP and lateral |
| `http://loinc.org` | `37362-1` | Bones X-ray bone age |
| `http://loinc.org` | `37364-7` | Aorta and Femoral artery - left Fluoroscopic angiogram runoff W contrast IA |
| `http://loinc.org` | `37365-4` | Bones X-ray survey for metastasis |
| `http://loinc.org` | `37366-2` | Abdominal Aorta and Arteries Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37379-5` | Aortic arch and Upper Extremity artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37380-3` | Aortic arch and Brachial artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37381-1` | Aortic arch and Carotid artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37382-9` | Aortic arch and Subclavian artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37383-7` | Aortic arch and Subclavian artery - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37384-5` | Aortic arch and Vertebral artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37385-2` | Aortic arch and Vertebral artery - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37386-0` | Aortic arch and Vertebral artery - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37387-8` | Adrenal artery - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37388-6` | Brachial artery - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37389-4` | Bronchial artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37390-2` | Carotid artery.external - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37391-0` | Carotid artery and Vertebral artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37392-8` | Carotid artery and Vertebral artery - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37393-6` | Carotid artery+Vertebral artery - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37394-4` | Celiac artery and Superior mesenteric artery and Inferior mesenteric artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37395-1` | Extremity arteries - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37396-9` | Upper extremity arteries - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37397-7` | Gastric artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37398-5` | Gastric artery - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37399-3` | Gastroduodenal artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37401-7` | Maxillary artery.internal Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37402-5` | Superior mesenteric artery and Inferior mesenteric artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37403-3` | Celiac artery and Gastric artery - left and Superior mesenteric artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37404-1` | Pudendal artery.internal Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37405-8` | Subclavian artery - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37406-6` | Subclavian artery - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37407-4` | Vertebral artery - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37409-0` | Temporomandibular joint - bilateral Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37410-8` | Temporomandibular joint - left Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37411-6` | Azygos vein Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37412-4` | Extremity veins - bilateral Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37413-2` | Extremity veins - left Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37414-0` | Lower extremity veins - bilateral Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37415-7` | Upper extremity veins - bilateral Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37416-5` | Femoral vein Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37419-9` | Intraosseous veins Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37420-7` | Jugular vein - left Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37421-5` | Inferior mesenteric vein Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37422-3` | Orbit veins - left Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37423-1` | Renal vein - left Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37426-4` | Lower extremity vein Fluoroscopic angiogram Angioplasty W contrast IV |
| `http://loinc.org` | `37427-2` | Fluoroscopy Guidance for injection of Spine |
| `http://loinc.org` | `37428-0` | Wrist CT |
| `http://loinc.org` | `37429-8` | Wrist - bilateral X-ray tomograph |
| `http://loinc.org` | `37430-6` | Wrist - bilateral CT |
| `http://loinc.org` | `37431-4` | Wrist - left CT |
| `http://loinc.org` | `37432-2` | Wrist - left X-ray tomograph |
| `http://loinc.org` | `37433-0` | Wrist - right CT |
| `http://loinc.org` | `37434-8` | Heart MRI cine for function |
| `http://loinc.org` | `37435-5` | Temporomandibular joint MRI cine |
| `http://loinc.org` | `37436-3` | Brain MRI diffusion weighted |
| `http://loinc.org` | `37437-1` | Breast MRI dynamic W contrast IV |
| `http://loinc.org` | `37438-9` | Pituitary and Sella turcica CT dynamic W contrast IV |
| `http://loinc.org` | `37439-7` | Chest CT high resolution |
| `http://loinc.org` | `37440-5` | Chest CT high resolution W contrast IV |
| `http://loinc.org` | `37441-3` | Chest CT high resolution WO contrast |
| `http://loinc.org` | `37442-1` | Brain MRI spectroscopy |
| `http://loinc.org` | `37443-9` | Unspecified body region MRI spectroscopy |
| `http://loinc.org` | `37444-7` | Wrist MRI W contrast intraarticular |
| `http://loinc.org` | `37445-4` | Wrist - left MRI W contrast intraarticular |
| `http://loinc.org` | `37446-2` | Wrist - right MRI W contrast intraarticular |
| `http://loinc.org` | `37447-0` | Wrist CT W contrast IV |
| `http://loinc.org` | `37448-8` | Wrist MRI W contrast IV |
| `http://loinc.org` | `37449-6` | Wrist - bilateral MRI W contrast IV |
| `http://loinc.org` | `37450-4` | Wrist - left CT W contrast IV |
| `http://loinc.org` | `37451-2` | Wrist - left MRI W contrast IV |
| `http://loinc.org` | `37452-0` | Wrist - right CT W contrast IV |
| `http://loinc.org` | `37453-8` | Wrist - right MRI W contrast IV |
| `http://loinc.org` | `37454-6` | Wrist - bilateral X-ray 3 views |
| `http://loinc.org` | `37455-3` | Wrist - left X-ray 3 views |
| `http://loinc.org` | `37457-9` | Wrist CT W and WO contrast IV |
| `http://loinc.org` | `37458-7` | Wrist - left CT W and WO contrast IV |
| `http://loinc.org` | `37459-5` | Wrist CT WO contrast |
| `http://loinc.org` | `37460-3` | Wrist MRI WO contrast |
| `http://loinc.org` | `37461-1` | Wrist - bilateral CT WO contrast |
| `http://loinc.org` | `37462-9` | Wrist - bilateral MRI WO contrast |
| `http://loinc.org` | `37463-7` | Wrist - left CT WO contrast |
| `http://loinc.org` | `37464-5` | Wrist - left MRI WO contrast |
| `http://loinc.org` | `37465-2` | Wrist - right CT WO contrast |
| `http://loinc.org` | `37466-0` | Wrist - right MRI WO contrast |
| `http://loinc.org` | `37467-8` | Acromioclavicular Joint X-ray 10 degree cephalic angle |
| `http://loinc.org` | `37468-6` | Shoulder - bilateral X-ray 30 degree caudal angle |
| `http://loinc.org` | `37469-4` | Clavicle - bilateral X-ray 45 degree cephalic angle |
| `http://loinc.org` | `37470-2` | Clavicle - left X-ray 45 degree cephalic angle |
| `http://loinc.org` | `37471-0` | Hand - bilateral X-ray Bora |
| `http://loinc.org` | `37472-8` | Hand - left X-ray Bora |
| `http://loinc.org` | `37473-6` | Shoulder - left X-ray Grashey |
| `http://loinc.org` | `37474-4` | Ankle - left X-ray lateral W manual stress |
| `http://loinc.org` | `37475-1` | Ankle - left X-ray Mortise W manual stress |
| `http://loinc.org` | `37476-9` | Knee X-ray PA W 45 degree flexion |
| `http://loinc.org` | `37477-7` | Knee X-ray PA standing and W 45 degree flexion |
| `http://loinc.org` | `37481-9` | Spine Cervical and Spine Thoracic X-ray |
| `http://loinc.org` | `37482-7` | Wrist - bilateral X-ray 2 views |
| `http://loinc.org` | `37483-5` | Wrist - left X-ray 2 views |
| `http://loinc.org` | `37484-3` | Knee - left X-ray AP W manual stress |
| `http://loinc.org` | `37485-0` | Humerus X-ray AP and transthoracic |
| `http://loinc.org` | `37486-8` | Ankle X-ray Broden W manual stress |
| `http://loinc.org` | `37487-6` | Lower extremity arteries Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37488-4` | Upper extremity arteries - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37489-2` | Tibioperoneal arteries Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37490-0` | Vertebral artery - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37491-8` | CT Guidance for aspiration of Pleural space |
| `http://loinc.org` | `37492-6` | CT Guidance for biopsy of Chest.pleura |
| `http://loinc.org` | `37493-4` | CT Guidance for injection of Spine.disc.cervical |
| `http://loinc.org` | `37494-2` | Fluoroscopy Guidance for injection of Tendon |
| `http://loinc.org` | `37495-9` | Skull.base CT |
| `http://loinc.org` | `37496-7` | Spine Cervical CT W contrast intradisc |
| `http://loinc.org` | `37497-5` | Spine vessels MRI angiogram |
| `http://loinc.org` | `37498-3` | Head vessels and Neck vessels CT angiogram W contrast IV |
| `http://loinc.org` | `37499-1` | Aortic stent CT angiogram W contrast IV |
| `http://loinc.org` | `37500-6` | Spine vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `37501-4` | Cervical Spine vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `37502-2` | Lumbar Spine vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `37503-0` | Thoracic Spine vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `37505-5` | Spine vessels MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `37506-3` | Cervical Spine vessels MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `37507-1` | Lumbar Spine vessels MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `37508-9` | Thoracic Spine vessels MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `37509-7` | Spine Lumbar CT W contrast intradisc |
| `http://loinc.org` | `37510-5` | Spine vessels MRI angiogram WO contrast |
| `http://loinc.org` | `37511-3` | Cervical Spine vessels MRI angiogram WO contrast |
| `http://loinc.org` | `37512-1` | Thoracic Spine vessels MRI angiogram WO contrast |
| `http://loinc.org` | `37513-9` | Tibia - bilateral X-ray 10 degree caudal angle |
| `http://loinc.org` | `37514-7` | Tibia - left X-ray 10 degree caudal angle |
| `http://loinc.org` | `37515-4` | Spine Lumbosacral Junction X-ray lateral spot |
| `http://loinc.org` | `37516-2` | Spine Lumbosacral Junction X-ray lateral spot standing |
| `http://loinc.org` | `37517-0` | Finger fifth - bilateral X-ray |
| `http://loinc.org` | `37518-8` | Finger fifth - left X-ray |
| `http://loinc.org` | `37519-6` | Finger fourth - bilateral X-ray |
| `http://loinc.org` | `37520-4` | Finger fourth - left X-ray |
| `http://loinc.org` | `37521-2` | Finger second - bilateral X-ray |
| `http://loinc.org` | `37522-0` | Finger second - left X-ray |
| `http://loinc.org` | `37523-8` | Finger third - bilateral X-ray |
| `http://loinc.org` | `37524-6` | Finger third - left X-ray |
| `http://loinc.org` | `37530-3` | Toe fifth - left X-ray |
| `http://loinc.org` | `37531-1` | Toe fourth - left X-ray |
| `http://loinc.org` | `37532-9` | Great toe - bilateral X-ray |
| `http://loinc.org` | `37533-7` | Great toe - left X-ray |
| `http://loinc.org` | `37534-5` | Toe second - left X-ray |
| `http://loinc.org` | `37535-2` | Toe third - left X-ray |
| `http://loinc.org` | `37538-6` | Shoulder - left X-ray Grashey and axillary and Y |
| `http://loinc.org` | `37539-4` | Breast Mammogram grid |
| `http://loinc.org` | `37540-2` | Knee - bilateral X-ray Holmblad standing |
| `http://loinc.org` | `37541-0` | Mastoid - bilateral X-ray law and Mayer and Stenver and Towne |
| `http://loinc.org` | `37542-8` | Breast Mammogram magnification |
| `http://loinc.org` | `37543-6` | Breast - bilateral Mammogram magnification |
| `http://loinc.org` | `37544-4` | Wrist - bilateral X-ray oblique |
| `http://loinc.org` | `37545-1` | Hip - left X-ray oblique crosstable |
| `http://loinc.org` | `37546-9` | Temporomandibular joint - bilateral X-ray open and closed mouth |
| `http://loinc.org` | `37547-7` | Wrist - bilateral X-ray PA and lateral |
| `http://loinc.org` | `37548-5` | Wrist - left X-ray PA and lateral |
| `http://loinc.org` | `37549-3` | Wrist - bilateral X-ray PA and lateral and oblique |
| `http://loinc.org` | `37550-1` | Wrist - left X-ray PA and lateral and oblique |
| `http://loinc.org` | `37551-9` | Breast Mammogram spot |
| `http://loinc.org` | `37552-7` | Breast - bilateral Mammogram spot |
| `http://loinc.org` | `37553-5` | Breast - left Mammogram spot compression |
| `http://loinc.org` | `37554-3` | Breast - bilateral Mammogram magnification and spot |
| `http://loinc.org` | `37555-0` | Wrist - left X-ray ulnar deviation and radial deviation |
| `http://loinc.org` | `37556-8` | Ankle X-ray W manual stress |
| `http://loinc.org` | `37557-6` | Ankle - bilateral X-ray W manual stress |
| `http://loinc.org` | `37558-4` | Ankle - left X-ray W manual stress |
| `http://loinc.org` | `37559-2` | Foot - left X-ray W manual stress |
| `http://loinc.org` | `37560-0` | Knee X-ray W manual stress |
| `http://loinc.org` | `37561-8` | Knee - bilateral X-ray W manual stress |
| `http://loinc.org` | `37562-6` | Knee - left X-ray W manual stress |
| `http://loinc.org` | `37563-4` | Thumb - bilateral X-ray W manual stress |
| `http://loinc.org` | `37564-2` | Thumb - left X-ray W manual stress |
| `http://loinc.org` | `37565-9` | Unspecified body region Fluoroscopy W barium contrast via fistula |
| `http://loinc.org` | `37566-7` | Unspecified body region Fluoroscopy W contrast via catheter |
| `http://loinc.org` | `37567-5` | Colon Fluoroscopy W contrast via colostomy |
| `http://loinc.org` | `37568-3` | Unspecified body region Fluoroscopy W contrast via fistula |
| `http://loinc.org` | `37569-1` | Urinary bladder Fluoroscopy W contrast via suprapubic tube |
| `http://loinc.org` | `37570-9` | Wrist - bilateral Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37571-7` | Wrist - left Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37572-5` | Spine Fluoroscopy W contrast IT |
| `http://loinc.org` | `37574-1` | Lower extremity vessels Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37575-8` | Gallbladder X-ray W contrast and fatty meal PO |
| `http://loinc.org` | `37576-6` | Unspecified body region Fluoroscopy W gastrografin via fistula |
| `http://loinc.org` | `37577-4` | Acromioclavicular Joint X-ray W weight |
| `http://loinc.org` | `37578-2` | Acromioclavicular joint - bilateral X-ray W weight |
| `http://loinc.org` | `37579-0` | Acromioclavicular Joint X-ray W and WO weight |
| `http://loinc.org` | `37580-8` | Acromioclavicular joint - bilateral X-ray W and WO weight |
| `http://loinc.org` | `37581-6` | Acromioclavicular joint - left X-ray W and WO weight |
| `http://loinc.org` | `37582-4` | Acromioclavicular Joint X-ray WO weight |
| `http://loinc.org` | `37583-2` | Pelvis and Hip - bilateral X-ray and lateral frog |
| `http://loinc.org` | `37584-0` | Great toe - left X-ray standing |
| `http://loinc.org` | `37585-7` | Jejunum Fluoroscopy W contrast |
| `http://loinc.org` | `37586-5` | Penis Fluoroscopy W contrast intra corpus cavernosum |
| `http://loinc.org` | `37587-3` | Aortic arch and Carotid artery - bilateral and Vertebral artery - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37588-1` | Aortic arch and Carotid artery.common - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37589-9` | Aortic arch and Carotid artery.common - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37590-7` | Aortic arch and Carotid artery.common - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37591-5` | Aortic arch and Carotid artery.external - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37592-3` | Aortic arch and Carotid artery.external - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37593-1` | Aortic arch and Carotid artery.external - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37594-9` | Aortic arch and Carotid artery and Vertebral artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37595-6` | Coronary graft Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37596-4` | Lymphatics abdominal and Lymphatics pelvic - left Fluoroscopy W contrast intra lymphatic |
| `http://loinc.org` | `37597-2` | Lymphatics abdominal and Lymphatics pelvic Fluoroscopy W contrast intra lymphatic |
| `http://loinc.org` | `37598-0` | Lymphatics abdominal and Lymphatics pelvic - bilateral Fluoroscopy W contrast intra lymphatic |
| `http://loinc.org` | `37599-8` | Extremity lymphatics - left Fluoroscopy W contrast intra lymphatic |
| `http://loinc.org` | `37600-4` | Lymphatics - left Fluoroscopy W contrast intra lymphatic |
| `http://loinc.org` | `37601-2` | Lymphatics pelvic - bilateral Fluoroscopy W contrast intra lymphatic |
| `http://loinc.org` | `37602-0` | Adrenal vein left Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37603-8` | Ribs - left and Chest X-ray lateral and PA chest |
| `http://loinc.org` | `37604-6` | Nasal bones X-ray 3 views |
| `http://loinc.org` | `37605-3` | Nasal bones X-ray lateral and Waters |
| `http://loinc.org` | `37606-1` | Nasal bones X-ray tomograph |
| `http://loinc.org` | `37607-9` | Kidney X-ray W contrast IV |
| `http://loinc.org` | `37608-7` | US Guidance for localization of foreign body of Eye |
| `http://loinc.org` | `37609-5` | Optic foramen X-ray 4 views |
| `http://loinc.org` | `37611-1` | Orbit - bilateral X-ray tomograph |
| `http://loinc.org` | `37612-9` | Orbit - bilateral X-ray 4 views |
| `http://loinc.org` | `37613-7` | Orbit - bilateral X-ray Waters |
| `http://loinc.org` | `37614-5` | Patella X-ray Single view |
| `http://loinc.org` | `37615-2` | Pelvis vessels Fluoroscopic angiogram W contrast |
| `http://loinc.org` | `37616-0` | Pelvis X-ray Single view |
| `http://loinc.org` | `37617-8` | Pelvis X-ray 2 views |
| `http://loinc.org` | `37618-6` | Pelvis X-ray AP and inlet |
| `http://loinc.org` | `37619-4` | Pelvis X-ray AP and Judet |
| `http://loinc.org` | `37620-2` | Pelvis X-ray AP and lateral |
| `http://loinc.org` | `37621-0` | Pelvis X-ray AP and oblique |
| `http://loinc.org` | `37622-8` | Pelvis X-ray AP single view |
| `http://loinc.org` | `37623-6` | Pelvis X-ray AP and inlet and outlet |
| `http://loinc.org` | `37624-4` | Pelvis X-ray AP and lateral and oblique |
| `http://loinc.org` | `37625-1` | Pelvis X-ray Ferguson |
| `http://loinc.org` | `37626-9` | Pelvis X-ray lateral frog |
| `http://loinc.org` | `37627-7` | Pelvis X-ray inlet and outlet and oblique |
| `http://loinc.org` | `37628-5` | Pelvis X-ray inlet |
| `http://loinc.org` | `37629-3` | Pelvis X-ray lateral |
| `http://loinc.org` | `37630-1` | Pelvis X-ray oblique |
| `http://loinc.org` | `37631-9` | Pelvis X-ray outlet |
| `http://loinc.org` | `37632-7` | Pelvis X-ray tomograph |
| `http://loinc.org` | `37633-5` | Pelvis X-ray standing |
| `http://loinc.org` | `37634-3` | Pelvis X-ray AP 20 degree cephalic angle |
| `http://loinc.org` | `37635-0` | Acetabulum X-ray 3 views |
| `http://loinc.org` | `37636-8` | Abdomen X-ray |
| `http://loinc.org` | `37637-6` | Extremity X-ray |
| `http://loinc.org` | `37639-2` | Neck X-ray |
| `http://loinc.org` | `37640-0` | Renal vessels Fluoroscopic angiogram W contrast |
| `http://loinc.org` | `37641-8` | Wrist - right Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37642-6` | Wrist - right X-ray limited |
| `http://loinc.org` | `37643-4` | Wrist - right X-ray oblique |
| `http://loinc.org` | `37644-2` | Wrist - right X-ray tomograph |
| `http://loinc.org` | `37645-9` | Wrist - right X-ray ulnar deviation |
| `http://loinc.org` | `37646-7` | Sacroiliac Joint X-ray limited |
| `http://loinc.org` | `37647-5` | Sacroiliac Joint Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37648-3` | Sacroiliac Joint X-ray 3 views |
| `http://loinc.org` | `37649-1` | Sacroiliac Joint X-ray AP and oblique |
| `http://loinc.org` | `37650-9` | Sacroiliac Joint X-ray Ferguson |
| `http://loinc.org` | `37651-7` | Sacrum X-ray 2 views |
| `http://loinc.org` | `37652-5` | Sacrum X-ray AP and lateral |
| `http://loinc.org` | `37653-3` | Sacrum X-ray tomograph |
| `http://loinc.org` | `37654-1` | Scapula X-ray Single view |
| `http://loinc.org` | `37655-8` | Scapula X-ray 2 views |
| `http://loinc.org` | `37656-6` | Scapula X-ray Y |
| `http://loinc.org` | `37658-2` | Spine Thoracic and Lumbar X-ray 2 views scoliosis |
| `http://loinc.org` | `37659-0` | Spine Thoracic and Lumbar X-ray scoliosis AP standing |
| `http://loinc.org` | `37660-8` | Spine Thoracic and Lumbar X-ray scoliosis lateral standing |
| `http://loinc.org` | `37661-6` | Acromioclavicular joint - right X-ray 2 views |
| `http://loinc.org` | `37662-4` | Acromioclavicular joint - right X-ray AP single view |
| `http://loinc.org` | `37663-2` | Acromioclavicular joint - right X-ray W and WO weight |
| `http://loinc.org` | `37664-0` | Acetabulum - right X-ray 2 views |
| `http://loinc.org` | `37665-7` | Ankle - right X-ray 3 views |
| `http://loinc.org` | `37666-5` | Ankle - right X-ray AP and lateral and Mortise |
| `http://loinc.org` | `37667-3` | Ankle - right X-ray AP and lateral |
| `http://loinc.org` | `37668-1` | Ankle - right X-ray AP and lateral and oblique |
| `http://loinc.org` | `37669-9` | Ankle - right X-ray lateral W manual stress |
| `http://loinc.org` | `37670-7` | Ankle - right X-ray lateral and Mortise |
| `http://loinc.org` | `37671-5` | Ankle - right X-ray Mortise W manual stress |
| `http://loinc.org` | `37672-3` | Ankle - right X-ray 2 views W manual stress |
| `http://loinc.org` | `37673-1` | Ankle - right X-ray W manual stress |
| `http://loinc.org` | `37674-9` | Ankle - right X-ray tomograph |
| `http://loinc.org` | `37675-6` | Ankle - right X-ray 2 views standing |
| `http://loinc.org` | `37676-4` | Ankle - right X-ray standing |
| `http://loinc.org` | `37677-2` | Wrist - right X-ray tunnel.carpal |
| `http://loinc.org` | `37678-0` | Wrist - right X-ray 2 views tunnel.carpal |
| `http://loinc.org` | `37679-8` | Clavicle - right X-ray 2 views |
| `http://loinc.org` | `37680-6` | Clavicle - right X-ray AP and Serendipity |
| `http://loinc.org` | `37681-4` | Elbow - right X-ray 2 views |
| `http://loinc.org` | `37682-2` | Elbow - right X-ray 3 views |
| `http://loinc.org` | `37683-0` | Elbow - right X-ray 4 views |
| `http://loinc.org` | `37684-8` | Elbow - right X-ray AP and lateral |
| `http://loinc.org` | `37685-5` | Elbow - right X-ray AP and lateral and oblique |
| `http://loinc.org` | `37686-3` | Elbow - right X-ray 2 views Oblique |
| `http://loinc.org` | `37687-1` | Elbow - right X-ray oblique |
| `http://loinc.org` | `37688-9` | Elbow - right X-ray tomograph |
| `http://loinc.org` | `37689-7` | Femur - right X-ray Single view |
| `http://loinc.org` | `37690-5` | Femur - right X-ray 2 views |
| `http://loinc.org` | `37691-3` | Femur - right X-ray 4 views |
| `http://loinc.org` | `37692-1` | Femur - right X-ray AP and lateral |
| `http://loinc.org` | `37693-9` | Femur - right X-ray standing |
| `http://loinc.org` | `37694-7` | Finger - right X-ray 2 views |
| `http://loinc.org` | `37695-4` | Finger - right X-ray 3 views |
| `http://loinc.org` | `37696-2` | Finger - right X-ray AP and lateral and oblique |
| `http://loinc.org` | `37697-0` | Foot - right X-ray 2 views |
| `http://loinc.org` | `37698-8` | Foot - right X-ray 2 views standing |
| `http://loinc.org` | `37699-6` | Foot - right X-ray 3 views |
| `http://loinc.org` | `37700-2` | Foot - right X-ray 3 views standing |
| `http://loinc.org` | `37701-0` | Foot - right X-ray AP and lateral |
| `http://loinc.org` | `37702-8` | Foot - right X-ray AP and lateral and oblique |
| `http://loinc.org` | `37703-6` | Foot - right X-ray lateral |
| `http://loinc.org` | `37704-4` | Foot - right X-ray oblique single view |
| `http://loinc.org` | `37705-1` | Foot - right X-ray W manual stress |
| `http://loinc.org` | `37706-9` | Foot - right X-ray tomograph |
| `http://loinc.org` | `37707-7` | Radius - right and Ulna - right X-ray 2 views |
| `http://loinc.org` | `37708-5` | Radius - right and Ulna - right X-ray AP and lateral |
| `http://loinc.org` | `37709-3` | Radius - right and Ulna - right X-ray oblique |
| `http://loinc.org` | `37710-1` | Hand - right X-ray AP and lateral |
| `http://loinc.org` | `37711-9` | Hand - right X-ray AP and lateral and oblique |
| `http://loinc.org` | `37712-7` | Hand - right X-ray lateral |
| `http://loinc.org` | `37713-5` | Hand - right X-ray PA and lateral |
| `http://loinc.org` | `37714-3` | Hand - right X-ray PA |
| `http://loinc.org` | `37715-0` | Hand - right X-ray PA and lateral and oblique |
| `http://loinc.org` | `37716-8` | Hand - right X-ray |
| `http://loinc.org` | `37717-6` | Hand - right X-ray tomograph |
| `http://loinc.org` | `37718-4` | Calcaneus - right X-ray 2 views |
| `http://loinc.org` | `37719-2` | Calcaneus - right X-ray AP and lateral |
| `http://loinc.org` | `37720-0` | Calcaneus - right X-ray standing |
| `http://loinc.org` | `37721-8` | Hip - right X-ray 2 views |
| `http://loinc.org` | `37722-6` | Hip - right X-ray 3 views |
| `http://loinc.org` | `37723-4` | Hip - right X-ray AP and lateral crosstable |
| `http://loinc.org` | `37724-2` | Hip - right X-ray AP and lateral frog |
| `http://loinc.org` | `37725-9` | Hip - right X-ray AP and lateral |
| `http://loinc.org` | `37726-7` | Hip - right X-ray AP single view |
| `http://loinc.org` | `37727-5` | Hip - right X-ray lateral crosstable |
| `http://loinc.org` | `37728-3` | Hip - right X-ray oblique crosstable |
| `http://loinc.org` | `37729-1` | Hip - right X-ray lateral frog |
| `http://loinc.org` | `37730-9` | Hip - right X-ray lateral |
| `http://loinc.org` | `37731-7` | Hip - right X-ray standing |
| `http://loinc.org` | `37732-5` | Hip - right X-ray Judet |
| `http://loinc.org` | `37733-3` | Lower extremity - right X-ray AP single view standing |
| `http://loinc.org` | `37734-1` | Lower extremity - right X-ray standing |
| `http://loinc.org` | `37735-8` | Hip - right X-ray tomograph |
| `http://loinc.org` | `37736-6` | Humerus - right X-ray AP and lateral |
| `http://loinc.org` | `37737-4` | Humerus - right X-ray oblique |
| `http://loinc.org` | `37738-2` | Humerus - right X-ray |
| `http://loinc.org` | `37739-0` | Iliac artery - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37740-8` | Knee - right X-ray AP and lateral and Sunrise and tunnel |
| `http://loinc.org` | `37741-6` | Knee - right X-ray Single view |
| `http://loinc.org` | `37742-4` | Knee - right X-ray 3 views |
| `http://loinc.org` | `37743-2` | Knee - right X-ray 4 views |
| `http://loinc.org` | `37744-0` | Knee - right X-ray 5 views |
| `http://loinc.org` | `37745-7` | Knee - right X-ray AP and lateral |
| `http://loinc.org` | `37746-5` | Knee - right X-ray AP W manual stress |
| `http://loinc.org` | `37747-3` | Knee - right X-ray AP and lateral and tunnel |
| `http://loinc.org` | `37748-1` | Knee - right X-ray AP and lateral and oblique |
| `http://loinc.org` | `37749-9` | Knee - right X-ray AP and lateral and Sunrise |
| `http://loinc.org` | `37750-7` | Knee - right X-ray lateral hyperextension |
| `http://loinc.org` | `37751-5` | Knee - right X-ray lateral |
| `http://loinc.org` | `37752-3` | Knee - right X-ray Rosenberg standing |
| `http://loinc.org` | `37753-1` | Knee - right X-ray W manual stress |
| `http://loinc.org` | `37754-9` | Knee - right X-ray lateral standing |
| `http://loinc.org` | `37755-6` | Knee - right X-ray PA standing |
| `http://loinc.org` | `37756-4` | Knee - right X-ray tunnel standing |
| `http://loinc.org` | `37757-2` | Knee - right X-ray oblique |
| `http://loinc.org` | `37758-0` | Knee - right X-ray |
| `http://loinc.org` | `37759-8` | Knee - right X-ray Sunrise and tunnel |
| `http://loinc.org` | `37760-6` | Knee - right X-ray tomograph |
| `http://loinc.org` | `37761-4` | Knee - right X-ray tunnel |
| `http://loinc.org` | `37762-2` | Knee - right X-ray 2 views standing |
| `http://loinc.org` | `37763-0` | Knee - right X-ray 4 views standing |
| `http://loinc.org` | `37764-8` | Lower extremity - right X-ray Single view |
| `http://loinc.org` | `37765-5` | Lower extremity vessels - right Fluoroscopic angiogram W contrast |
| `http://loinc.org` | `37766-3` | Lower extremity - right X-ray tomograph |
| `http://loinc.org` | `37767-1` | Lower extremity veins - right Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37768-9` | Breast - right Mammogram 2 views |
| `http://loinc.org` | `37769-7` | Breast - right Mammogram magnification and spot |
| `http://loinc.org` | `37770-5` | Breast - right Mammogram tangential |
| `http://loinc.org` | `37771-3` | Breast - right Mammogram true lateral |
| `http://loinc.org` | `37772-1` | Breast - right Mammogram XCCL |
| `http://loinc.org` | `37773-9` | Breast - right Mammogram magnification |
| `http://loinc.org` | `37774-7` | Breast - right Mammogram |
| `http://loinc.org` | `37775-4` | Breast - right Mammogram roll |
| `http://loinc.org` | `37776-2` | Patella - right X-ray AP and lateral |
| `http://loinc.org` | `37777-0` | Patella - right X-ray |
| `http://loinc.org` | `37778-8` | Popliteal artery - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37779-6` | Pulmonary artery - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37780-4` | Ribs - right X-ray 2 views |
| `http://loinc.org` | `37781-2` | Ribs - right X-ray 3 views |
| `http://loinc.org` | `37782-0` | Ribs - right X-ray anterior and lateral |
| `http://loinc.org` | `37783-8` | Ribs - right X-ray AP single view |
| `http://loinc.org` | `37784-6` | Ribs - right X-ray lateral |
| `http://loinc.org` | `37785-3` | Sacroiliac joint - right Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37786-1` | Sacroiliac joint - right X-ray |
| `http://loinc.org` | `37787-9` | Scapula - right X-ray 2 views |
| `http://loinc.org` | `37788-7` | Scapula - right X-ray AP and lateral |
| `http://loinc.org` | `37789-5` | Scapula - right X-ray AP and Y |
| `http://loinc.org` | `37790-3` | Scapula - right X-ray Y |
| `http://loinc.org` | `37791-1` | Shoulder - right X-ray Stryker Notch |
| `http://loinc.org` | `37792-9` | Shoulder - right X-ray Single view |
| `http://loinc.org` | `37793-7` | Shoulder - right X-ray 2 views |
| `http://loinc.org` | `37794-5` | Shoulder - right X-ray 4 views |
| `http://loinc.org` | `37795-2` | Shoulder - right X-ray 5 views |
| `http://loinc.org` | `37796-0` | Shoulder - right X-ray 6 views |
| `http://loinc.org` | `37797-8` | Shoulder - right X-ray AP and Stryker Notch |
| `http://loinc.org` | `37798-6` | Shoulder - right X-ray AP single view |
| `http://loinc.org` | `37799-4` | Shoulder - right X-ray AP and West Point and outlet |
| `http://loinc.org` | `37800-0` | Shoulder - right X-ray axillary |
| `http://loinc.org` | `37801-8` | Shoulder - right X-ray Garth |
| `http://loinc.org` | `37802-6` | Shoulder - right X-ray outlet |
| `http://loinc.org` | `37803-4` | Shoulder - right X-ray lateral and Y |
| `http://loinc.org` | `37804-2` | Shoulder - right X-ray outlet and Y |
| `http://loinc.org` | `37805-9` | Shoulder - right X-ray Y |
| `http://loinc.org` | `37806-7` | Shoulder - right X-ray Grashey and axillary and outlet |
| `http://loinc.org` | `37807-5` | Shoulder - right X-ray axillary and Y |
| `http://loinc.org` | `37808-3` | Sternoclavicular joint - right X-ray Serendipity |
| `http://loinc.org` | `37809-1` | Shoulder - right X-ray West Point |
| `http://loinc.org` | `37810-9` | Acromioclavicular joint - right X-ray Zanca |
| `http://loinc.org` | `37811-7` | Shoulder - right X-ray tomograph |
| `http://loinc.org` | `37812-5` | Thumb - right X-ray 3 views |
| `http://loinc.org` | `37813-3` | Thumb - right X-ray AP and lateral and oblique |
| `http://loinc.org` | `37814-1` | Thumb - right X-ray W manual stress |
| `http://loinc.org` | `37815-8` | Tibia - right and Fibula - right X-ray 2 views |
| `http://loinc.org` | `37816-6` | Tibia - right and Fibula - right X-ray AP and lateral |
| `http://loinc.org` | `37817-4` | Tibia - right and Fibula - right X-ray oblique |
| `http://loinc.org` | `37818-2` | Temporomandibular joint - right Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37819-0` | Temporomandibular joint - right X-ray tomograph |
| `http://loinc.org` | `37820-8` | Toes - right X-ray 3 views |
| `http://loinc.org` | `37821-6` | Toes - right X-ray 2 views |
| `http://loinc.org` | `37822-4` | Toes - right X-ray AP and lateral |
| `http://loinc.org` | `37823-2` | Toes - right X-ray standing |
| `http://loinc.org` | `37824-0` | Upper extremity veins - right Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37825-7` | Wrist - right X-ray Single view |
| `http://loinc.org` | `37826-5` | Wrist - right X-ray 2 views |
| `http://loinc.org` | `37827-3` | Wrist - right X-ray 3 views |
| `http://loinc.org` | `37828-1` | Wrist - right X-ray 4 views |
| `http://loinc.org` | `37829-9` | Wrist - right X-ray 5 views |
| `http://loinc.org` | `37830-7` | Wrist - right X-ray 6 views |
| `http://loinc.org` | `37831-5` | Wrist - right X-ray 8 views |
| `http://loinc.org` | `37832-3` | Wrist - right X-ray AP and lateral |
| `http://loinc.org` | `37833-1` | Wrist - right X-ray lateral W extension |
| `http://loinc.org` | `37834-9` | Wrist - right X-ray lateral W flexion |
| `http://loinc.org` | `37835-6` | Wrist - right X-ray PA and lateral |
| `http://loinc.org` | `37836-4` | Wrist - right X-ray PA and lateral and oblique |
| `http://loinc.org` | `37839-8` | Shoulder X-ray AP and lateral and axillary |
| `http://loinc.org` | `37840-6` | Shoulder X-ray 2 views |
| `http://loinc.org` | `37841-4` | Shoulder X-ray AP and lateral |
| `http://loinc.org` | `37842-2` | Shoulder X-ray AP single view |
| `http://loinc.org` | `37843-0` | Shoulder X-ray Garth |
| `http://loinc.org` | `37844-8` | Shoulder X-ray Grashey |
| `http://loinc.org` | `37845-5` | Shoulder X-ray outlet |
| `http://loinc.org` | `37846-3` | Sternoclavicular Joint X-ray Serendipity |
| `http://loinc.org` | `37847-1` | Shoulder X-ray Y |
| `http://loinc.org` | `37848-9` | Acromioclavicular Joint X-ray Zanca |
| `http://loinc.org` | `37849-7` | Shoulder X-ray axillary |
| `http://loinc.org` | `37850-5` | Shoulder X-ray tomograph |
| `http://loinc.org` | `37851-3` | Sinuses X-ray Single view |
| `http://loinc.org` | `37852-1` | Sinuses X-ray Caldwell and Waters |
| `http://loinc.org` | `37853-9` | Sinuses X-ray 2 views |
| `http://loinc.org` | `37854-7` | Sinuses X-ray 3 views |
| `http://loinc.org` | `37855-4` | Sinuses X-ray 4 views |
| `http://loinc.org` | `37856-2` | Sinuses X-ray 5 views |
| `http://loinc.org` | `37857-0` | Sinuses X-ray Caldwell |
| `http://loinc.org` | `37858-8` | Sinuses X-ray lateral |
| `http://loinc.org` | `37859-6` | Sinuses X-ray PA and lateral and Waters |
| `http://loinc.org` | `37860-4` | Sinuses X-ray PA and lateral and Caldwell and Waters |
| `http://loinc.org` | `37861-2` | Sinuses X-ray submentovertex |
| `http://loinc.org` | `37862-0` | Sinuses X-ray lateral and Waters |
| `http://loinc.org` | `37863-8` | Sinuses X-ray Waters |
| `http://loinc.org` | `37864-6` | Sinuses X-ray lateral and Caldwell and Waters |
| `http://loinc.org` | `37866-1` | Sinuses X-ray tomograph |
| `http://loinc.org` | `37867-9` | Skull X-ray 2 views |
| `http://loinc.org` | `37868-7` | Skull X-ray 4 views |
| `http://loinc.org` | `37869-5` | Skull X-ray lateral and Towne |
| `http://loinc.org` | `37870-3` | Skull X-ray Towne |
| `http://loinc.org` | `37871-1` | Skull X-ray lateral and Caldwell and Waters and Towne |
| `http://loinc.org` | `37872-9` | Skull X-ray lateral crosstable |
| `http://loinc.org` | `37874-5` | Skull X-ray tomograph |
| `http://loinc.org` | `37875-2` | Spine X-ray Single view |
| `http://loinc.org` | `37876-0` | Spine X-ray 4 views |
| `http://loinc.org` | `37877-8` | Spine X-ray AP single view |
| `http://loinc.org` | `37878-6` | Spine X-ray lateral crosstable |
| `http://loinc.org` | `37879-4` | Spine X-ray 2 views |
| `http://loinc.org` | `37880-2` | Sternoclavicular Joint X-ray AP single view |
| `http://loinc.org` | `37881-0` | Sternoclavicular Joint X-ray 3 views |
| `http://loinc.org` | `37882-8` | Sternoclavicular Joint X-ray 4 views |
| `http://loinc.org` | `37883-6` | Sternum X-ray 2 views |
| `http://loinc.org` | `37884-4` | Sternum X-ray PA and lateral and oblique |
| `http://loinc.org` | `37885-1` | Sternum X-ray tomograph |
| `http://loinc.org` | `37886-9` | Subclavian artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37887-7` | Fluoroscopy Guidance for aspiration of Pleural space |
| `http://loinc.org` | `37888-5` | Thumb X-ray 3 views |
| `http://loinc.org` | `37889-3` | Thumb X-ray AP and lateral |
| `http://loinc.org` | `37890-1` | Thumb X-ray AP single view |
| `http://loinc.org` | `37891-9` | Thumb X-ray lateral |
| `http://loinc.org` | `37892-7` | Thumb X-ray oblique single view |
| `http://loinc.org` | `37893-5` | Tibia and Fibula X-ray lateral |
| `http://loinc.org` | `37894-3` | Tibia and Fibula X-ray Single view |
| `http://loinc.org` | `37895-0` | Tibia and Fibula X-ray 2 views |
| `http://loinc.org` | `37896-8` | Tibia and Fibula X-ray AP and lateral |
| `http://loinc.org` | `37897-6` | Tibia and Fibula X-ray AP single view |
| `http://loinc.org` | `37898-4` | Tibia and Fibula X-ray tomograph |
| `http://loinc.org` | `37899-2` | Tibia and Fibula X-ray standing |
| `http://loinc.org` | `37900-8` | Tibial artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37901-6` | Temporomandibular joint Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37902-4` | Toes X-ray 2 views |
| `http://loinc.org` | `37903-2` | Spine Thoracic X-ray lateral crosstable |
| `http://loinc.org` | `37904-0` | Spine Thoracic X-ray Single view |
| `http://loinc.org` | `37905-7` | Spine Thoracic X-ray 2 views |
| `http://loinc.org` | `37906-5` | Spine Thoracic X-ray 3 views |
| `http://loinc.org` | `37907-3` | Spine Thoracic X-ray 4 views |
| `http://loinc.org` | `37908-1` | Spine Thoracic X-ray AP and lateral and oblique |
| `http://loinc.org` | `37909-9` | Spine Thoracic X-ray lateral hyperextension |
| `http://loinc.org` | `37910-7` | Spine Thoracic X-ray lateral standing |
| `http://loinc.org` | `37911-5` | Spine Thoracic X-ray tomograph |
| `http://loinc.org` | `37912-3` | US Guidance for biopsy of Breast - bilateral |
| `http://loinc.org` | `37913-1` | US Guidance for biopsy of Abdomen |
| `http://loinc.org` | `37914-9` | US Guidance for biopsy of Breast |
| `http://loinc.org` | `37915-6` | US Guidance for biopsy of Chest |
| `http://loinc.org` | `37916-4` | US Guidance for needle biopsy of Lymph node |
| `http://loinc.org` | `37917-2` | US Guidance for biopsy of Muscle |
| `http://loinc.org` | `37918-0` | US Guidance for biopsy of Neck |
| `http://loinc.org` | `37919-8` | US Guidance for biopsy of Pancreas |
| `http://loinc.org` | `37920-6` | US Guidance for biopsy of Salivary gland |
| `http://loinc.org` | `37921-4` | US Guidance for needle localization of Chest |
| `http://loinc.org` | `37922-2` | Upper extremity X-ray 2 views |
| `http://loinc.org` | `37923-0` | Upper extremity X-ray tomograph |
| `http://loinc.org` | `37924-8` | Wrist X-ray Single view |
| `http://loinc.org` | `37925-5` | Wrist X-ray 2 views |
| `http://loinc.org` | `37926-3` | Wrist X-ray 3 views |
| `http://loinc.org` | `37927-1` | Wrist X-ray AP and lateral and oblique |
| `http://loinc.org` | `37928-9` | Wrist X-ray Brewerton |
| `http://loinc.org` | `37929-7` | Wrist X-ray lateral W flexion and W extension |
| `http://loinc.org` | `37930-5` | Wrist X-ray lateral |
| `http://loinc.org` | `37931-3` | Wrist X-ray PA |
| `http://loinc.org` | `37932-1` | Wrist X-ray tomograph |
| `http://loinc.org` | `37933-9` | Zygomatic arch X-ray 3 views |
| `http://loinc.org` | `37934-7` | Zygomatic arch X-ray 4 views |
| `http://loinc.org` | `37935-4` | Pelvis arteries and Lower extremity arteries - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37936-2` | Peripheral vessels Fluoroscopic angiogram W contrast |
| `http://loinc.org` | `37937-0` | Ribs anterior X-ray |
| `http://loinc.org` | `37938-8` | Ribs posterior X-ray |
| `http://loinc.org` | `37939-6` | Adrenal artery - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37940-4` | Adrenal vein - right Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37941-2` | Ankle arteries - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37942-0` | Ankle - right Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37943-8` | Carotid artery+Vertebral artery - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37944-6` | Carotid artery and Cerebral artery - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37945-3` | Carotid artery.cervical - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37947-9` | Elbow - right Fluoroscopy W contrast intraarticular |
| `http://loinc.org` | `37948-7` | Carotid artery.external - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37949-5` | Extremity arteries - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37950-3` | Extremity veins - right Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37952-9` | Carotid artery.internal - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37953-7` | Carotid artery and Cerebral artery internal - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37954-5` | Jugular vein - right Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37958-6` | Orbit veins - right Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37959-4` | Renal vein - right Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37960-2` | Ribs lower - right X-ray |
| `http://loinc.org` | `37961-0` | Ribs upper - right X-ray |
| `http://loinc.org` | `37962-8` | Ribs anterior and posterior - right X-ray |
| `http://loinc.org` | `37963-6` | Ribs anterior - right X-ray |
| `http://loinc.org` | `37964-4` | Ribs posterior - right X-ray |
| `http://loinc.org` | `37965-1` | Sternoclavicular joint - right X-ray |
| `http://loinc.org` | `37966-9` | Subclavian artery - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37967-7` | Upper extremity arteries - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37968-5` | Vertebral artery - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37969-3` | Sinus vein Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37970-1` | Splenic vein Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37971-9` | Subclavian vein Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37972-7` | Superior mesenteric vein Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `37973-5` | Testicle vessels Fluoroscopy W contrast |
| `http://loinc.org` | `37974-3` | Spine Thoracolumbar Junction X-ray AP and lateral |
| `http://loinc.org` | `37975-0` | Spine Thoracolumbar Junction X-ray |
| `http://loinc.org` | `37976-8` | Upper extremity vessels Fluoroscopic angiogram W contrast |
| `http://loinc.org` | `37977-6` | Upper extremity arteries Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37979-2` | Uterine artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `37980-0` | Vertebral vessels Fluoroscopic angiogram W contrast |
| `http://loinc.org` | `37981-8` | Visceral vessels Fluoroscopic angiogram W contrast |
| `http://loinc.org` | `37994-1` | Lumbar Spine vessels MRI angiogram WO contrast |
| `http://loinc.org` | `37995-8` | Calcaneus - bilateral X-ray Broden |
| `http://loinc.org` | `37996-6` | Calcaneus X-ray Broden |
| `http://loinc.org` | `37997-4` | Calcaneus - left X-ray Broden |
| `http://loinc.org` | `37998-2` | Elbow X-ray radial head capitellar |
| `http://loinc.org` | `37999-0` | Elbow - bilateral X-ray radial head capitellar |
| `http://loinc.org` | `38000-6` | Elbow - left X-ray radial head capitellar |
| `http://loinc.org` | `38001-4` | Chest X-ray W expiration |
| `http://loinc.org` | `38002-2` | Chest X-ray W inspiration |
| `http://loinc.org` | `38003-0` | Foot - left X-ray AP standing |
| `http://loinc.org` | `38004-8` | Shoulder - left X-ray Grashey W and WO weight |
| `http://loinc.org` | `38006-3` | Elbow - right X-ray radial head capitellar |
| `http://loinc.org` | `38007-1` | Humerus - right X-ray transthoracic |
| `http://loinc.org` | `38008-9` | Spine Cervical and Thoracic and Lumbar X-ray |
| `http://loinc.org` | `38009-7` | Spine Thoracic X-ray AP and lateral and Swimmers |
| `http://loinc.org` | `38010-5` | Spine Thoracic X-ray lateral W flexion and W extension |
| `http://loinc.org` | `38011-3` | Aorta US limited |
| `http://loinc.org` | `38012-1` | US Guidance for aspiration of cyst of Breast - bilateral |
| `http://loinc.org` | `38013-9` | Lower extremity - bilateral US |
| `http://loinc.org` | `38014-7` | Upper extremity artery - bilateral US |
| `http://loinc.org` | `38015-4` | Carotid artery US limited |
| `http://loinc.org` | `38016-2` | Chest wall US |
| `http://loinc.org` | `38017-0` | US Guidance for fine needle aspiration of Prostate |
| `http://loinc.org` | `38018-8` | US Guidance for fine needle aspiration of Unspecified body region |
| `http://loinc.org` | `38019-6` | US Guidance for fine needle aspiration of Thyroid |
| `http://loinc.org` | `38020-4` | Gallbladder US limited |
| `http://loinc.org` | `38021-2` | Biliary ducts and Gallbladder US |
| `http://loinc.org` | `38022-0` | Gallbladder US W cholecystokinin |
| `http://loinc.org` | `38023-8` | US Guidance for core needle percutaneous biopsy of Breast - left |
| `http://loinc.org` | `38024-6` | US Guidance for core needle biopsy of Unspecified body region |
| `http://loinc.org` | `38025-3` | US Guidance for core needle percutaneous biopsy of Breast - right |
| `http://loinc.org` | `38026-1` | US Guidance for fine needle aspiration of Breast - left |
| `http://loinc.org` | `38027-9` | US Guidance for needle biopsy of Kidney - bilateral |
| `http://loinc.org` | `38028-7` | US Guidance for needle biopsy of Breast |
| `http://loinc.org` | `38029-5` | US Guidance for needle biopsy of Chest |
| `http://loinc.org` | `38030-3` | US Guidance for needle biopsy of Spleen |
| `http://loinc.org` | `38031-1` | US Guidance for needle biopsy of Thyroid |
| `http://loinc.org` | `38032-9` | US Guidance for needle localization of Unspecified body region |
| `http://loinc.org` | `38033-7` | US Guidance for fine needle aspiration of Breast - right |
| `http://loinc.org` | `38034-5` | Head US limited |
| `http://loinc.org` | `38035-2` | Kidney US limited |
| `http://loinc.org` | `38036-0` | Kidney US |
| `http://loinc.org` | `38037-8` | Femur - left US |
| `http://loinc.org` | `38038-6` | Kidney - left US |
| `http://loinc.org` | `38039-4` | Lower extremity - left US limited |
| `http://loinc.org` | `38040-2` | Lower extremity - left US |
| `http://loinc.org` | `38041-0` | Upper extremity - left US |
| `http://loinc.org` | `38042-8` | Lower extremity artery US.doppler limited |
| `http://loinc.org` | `38043-6` | Mastoid US |
| `http://loinc.org` | `38044-4` | Mediastinum US |
| `http://loinc.org` | `38045-1` | Parathyroid US |
| `http://loinc.org` | `38046-9` | Pelvis US limited |
| `http://loinc.org` | `38047-7` | Abdomen retroperitoneum US limited |
| `http://loinc.org` | `38048-5` | Femur - right US |
| `http://loinc.org` | `38049-3` | Kidney - right US |
| `http://loinc.org` | `38050-1` | Lower extremity - right US limited |
| `http://loinc.org` | `38051-9` | Lower extremity - right US |
| `http://loinc.org` | `38052-7` | Upper extremity - right US |
| `http://loinc.org` | `38053-5` | Sacrum US |
| `http://loinc.org` | `38054-3` | Visceral artery US |
| `http://loinc.org` | `38055-0` | Unspecified body region US W contrast |
| `http://loinc.org` | `38056-8` | FDA package insert Structured product laballing supplemental patient material |
| `http://loinc.org` | `38057-6` | Breast implant - left MRI |
| `http://loinc.org` | `38058-4` | Breast implant - right MRI |
| `http://loinc.org` | `38059-2` | Talus CT |
| `http://loinc.org` | `38060-0` | Spine.lumbosacral+Cervical+Thoracic MRI sagittal |
| `http://loinc.org` | `38061-8` | Spine Cervical and Spine Thoracic and Spine Lumbar and Sacrum MRI W contrast IV |
| `http://loinc.org` | `38062-6` | Breast implant - right MRI W and WO contrast IV |
| `http://loinc.org` | `38064-2` | Breast implant - left MRI WO contrast |
| `http://loinc.org` | `38065-9` | Hip - left X-ray during surgery |
| `http://loinc.org` | `38066-7` | Hip - left X-ray lateral during surgery |
| `http://loinc.org` | `38067-5` | Breast - bilateral Mammogram nipple profile |
| `http://loinc.org` | `38068-3` | Chest X-ray right anterior oblique |
| `http://loinc.org` | `38069-1` | Abdomen X-ray left posterior oblique |
| `http://loinc.org` | `38070-9` | Breast implant Mammogram |
| `http://loinc.org` | `38071-7` | Breast implant - bilateral Mammogram |
| `http://loinc.org` | `38072-5` | Breast implant - left Mammogram |
| `http://loinc.org` | `38073-3` | Ribs anterior - bilateral X-ray |
| `http://loinc.org` | `38074-1` | Ribs anterior - left X-ray |
| `http://loinc.org` | `38079-0` | Breast specimen - bilateral Mammogram |
| `http://loinc.org` | `38080-8` | Breast specimen - left Mammogram |
| `http://loinc.org` | `38082-4` | Shoulder - left X-ray AP and transthoracic |
| `http://loinc.org` | `38083-2` | Spine Cervical X-ray AP and lateral and oblique and odontoid and swimmer |
| `http://loinc.org` | `38084-0` | Abdomen X-ray AP and left posterior oblique |
| `http://loinc.org` | `38086-5` | Knee X-ray Merchants 30 and 45 and 60 degrees |
| `http://loinc.org` | `38087-3` | Knee - left X-ray Sunrise 20 and 40 and 60 degrees |
| `http://loinc.org` | `38088-1` | Knee - bilateral X-ray Sunrise 20 and 40 and 60 degrees |
| `http://loinc.org` | `38089-9` | Bones X-ray survey limited for metastasis |
| `http://loinc.org` | `38090-7` | Breast - bilateral Mammogram W air |
| `http://loinc.org` | `38091-5` | Breast - left Mammogram W air |
| `http://loinc.org` | `38092-3` | Urinary bladder Fluoroscopy W chain and contrast intra bladder |
| `http://loinc.org` | `38093-1` | Chest X-ray W nipple markers |
| `http://loinc.org` | `38094-9` | Spine.cavity Fluoroscopy W contrast |
| `http://loinc.org` | `38095-6` | Breast duct - bilateral Mammogram W contrast intra duct |
| `http://loinc.org` | `38096-4` | Breast duct - left Mammogram W contrast intra duct |
| `http://loinc.org` | `38097-2` | Parotid gland - left Fluoroscopy W contrast intra salivary duct |
| `http://loinc.org` | `38098-0` | Lacrimal duct - bilateral Fluoroscopy W contrast intra lacrimal duct |
| `http://loinc.org` | `38099-8` | Lacrimal duct - left Fluoroscopy W contrast intra lacrimal duct |
| `http://loinc.org` | `38100-4` | Urinary Bladder and Urethra Fluoroscopy W contrast antegrade |
| `http://loinc.org` | `38101-2` | Kidney X-ray W contrast antegrade |
| `http://loinc.org` | `38102-0` | Kidney X-ray W contrast antegrade via pyelostomy |
| `http://loinc.org` | `38103-8` | Spine Cervical and Spine Lumbar Fluoroscopy W contrast IT |
| `http://loinc.org` | `38104-6` | Spine.epidural space Fluoroscopy W contrast IT |
| `http://loinc.org` | `38105-3` | Kidney X-ray W contrast retrograde |
| `http://loinc.org` | `38107-9` | Wrist X-ray scaphoid |
| `http://loinc.org` | `38108-7` | Knee - right X-ray 2 views Oblique |
| `http://loinc.org` | `38112-9` | Kidney - right and Collecting system Fluoroscopy W contrast via nephrostomy tube |
| `http://loinc.org` | `38113-7` | Kidney - right and Collecting system Fluoroscopy W contrast retrograde via urethra |
| `http://loinc.org` | `38114-5` | Tibia - right and Fibula - right X-ray 2 views Oblique |
| `http://loinc.org` | `38115-2` | Wrist - right X-ray scaphoid |
| `http://loinc.org` | `38116-0` | Parotid gland Fluoroscopy W contrast intra salivary duct |
| `http://loinc.org` | `38117-8` | Sinuses X-ray Waters upright |
| `http://loinc.org` | `38118-6` | Neck X-ray 2 views lateral |
| `http://loinc.org` | `38119-4` | Thoracic artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `38120-2` | Spine Thoracic Fluoroscopy limited W contrast IT |
| `http://loinc.org` | `38121-0` | Spine Thoracic and Lumbar X-ray Single view |
| `http://loinc.org` | `38123-6` | Spine Thoracic and Lumbar X-ray AP and lateral |
| `http://loinc.org` | `38124-4` | Spine Thoracic and Lumbar X-ray standing |
| `http://loinc.org` | `38125-1` | Spine Cervical and Thoracic and Lumbar Fluoroscopy limited W contrast IT |
| `http://loinc.org` | `38126-9` | US Guidance for aspiration of cyst of Kidney |
| `http://loinc.org` | `38127-7` | US Guidance for CSF aspiration of Spine |
| `http://loinc.org` | `38128-5` | Femoral vessels - bilateral US |
| `http://loinc.org` | `38129-3` | Iliac vessels - bilateral US |
| `http://loinc.org` | `38130-1` | Lower extremity artery - bilateral US |
| `http://loinc.org` | `38131-9` | Subclavian vessels - bilateral US |
| `http://loinc.org` | `38132-7` | US Guidance for biopsy of Scrotum and Testicle |
| `http://loinc.org` | `38133-5` | US Guidance for aspiration of cyst of Pancreas |
| `http://loinc.org` | `38134-3` | Femoral vessels US |
| `http://loinc.org` | `38135-0` | US Guidance for fine needle aspiration of Deep tissue |
| `http://loinc.org` | `38136-8` | US Guidance for fine needle aspiration of Superficial tissue |
| `http://loinc.org` | `38137-6` | Iliac vessels - left US |
| `http://loinc.org` | `38138-4` | Parotid gland US |
| `http://loinc.org` | `38139-2` | Penis vessels US |
| `http://loinc.org` | `38140-0` | Penis US |
| `http://loinc.org` | `38141-8` | Iliac vessels - right US |
| `http://loinc.org` | `38142-6` | US Guidance for removal of fluid from Chest |
| `http://loinc.org` | `38143-4` | Upper extremity artery US.doppler limited |
| `http://loinc.org` | `38144-2` | Finger second - right X-ray |
| `http://loinc.org` | `38145-9` | Finger third - right X-ray |
| `http://loinc.org` | `38146-7` | Finger fourth - right X-ray |
| `http://loinc.org` | `38147-5` | Finger fifth - right X-ray |
| `http://loinc.org` | `38148-3` | Toe second - right X-ray |
| `http://loinc.org` | `38149-1` | Toe third - right X-ray |
| `http://loinc.org` | `38150-9` | Toe fourth - right X-ray |
| `http://loinc.org` | `38151-7` | Toe fifth - right X-ray |
| `http://loinc.org` | `38152-5` | Great toe - right X-ray |
| `http://loinc.org` | `38153-3` | Submandibular gland Fluoroscopy W contrast intra salivary duct |
| `http://loinc.org` | `38154-1` | Fluoroscopy Guidance for biopsy of Superficial bone |
| `http://loinc.org` | `38155-8` | Wrist X-ray 4 views |
| `http://loinc.org` | `38156-6` | Wrist X-ray 6 views |
| `http://loinc.org` | `38268-9` | Skeletal system DXA Bone density |
| `http://loinc.org` | `38269-7` | Study report Skeletal system DXA |
| `http://loinc.org` | `38765-4` | US Guidance for biopsy of Liver transplant |
| `http://loinc.org` | `38766-2` | US Guidance for biopsy of Kidney transplant |
| `http://loinc.org` | `38767-0` | Internal auditory canal - right CT |
| `http://loinc.org` | `38768-8` | Femur - right X-ray tomograph |
| `http://loinc.org` | `38769-6` | Lower extremity joint - right MRI limited WO contrast |
| `http://loinc.org` | `38770-4` | Scapula - right MRI WO contrast |
| `http://loinc.org` | `38771-2` | Pelvis and Hip - right X-ray |
| `http://loinc.org` | `38772-0` | Hip - right X-ray true lateral |
| `http://loinc.org` | `38773-8` | Lower extremity vessels - right MRI angiogram WO contrast |
| `http://loinc.org` | `38774-6` | Orbit - right X-ray |
| `http://loinc.org` | `38775-3` | Hand - right X-ray Brewerton |
| `http://loinc.org` | `38776-1` | Calcaneus - right X-ray Harris |
| `http://loinc.org` | `38777-9` | Elbow - right X-ray Jones |
| `http://loinc.org` | `38778-7` | Calcaneus - right X-ray ski jump |
| `http://loinc.org` | `38779-5` | Shoulder - right X-ray transthoracic |
| `http://loinc.org` | `38780-3` | Shoulder - right X-ray Velpeau axillary |
| `http://loinc.org` | `38781-1` | Shoulder - right X-ray AP and axillary and outlet |
| `http://loinc.org` | `38782-9` | Shoulder - right X-ray AP and axillary and outlet and Zanca |
| `http://loinc.org` | `38783-7` | Shoulder - right X-ray AP and axillary and Y |
| `http://loinc.org` | `38784-5` | Pelvis and Hip - right X-ray AP and lateral crosstable |
| `http://loinc.org` | `38785-2` | Pelvis and Hip - right X-ray AP and lateral frog |
| `http://loinc.org` | `38786-0` | Patella - right X-ray AP and lateral and Sunrise |
| `http://loinc.org` | `38787-8` | Shoulder - right X-ray AP and West Point |
| `http://loinc.org` | `38788-6` | Shoulder - right X-ray AP and Y |
| `http://loinc.org` | `38789-4` | Shoulder - right X-ray Grashey and axillary and Y |
| `http://loinc.org` | `38790-2` | Patella - right X-ray PA and lateral and Sunrise |
| `http://loinc.org` | `38791-0` | Shoulder - right X-ray Grashey and outlet |
| `http://loinc.org` | `38792-8` | Foot - right X-ray tarsal |
| `http://loinc.org` | `38793-6` | Shoulder - right X-ray Grashey and axillary |
| `http://loinc.org` | `38794-4` | Shoulder - right X-ray Grashey and outlet and Serendipity |
| `http://loinc.org` | `38795-1` | Shoulder - right X-ray Grashey and West Point |
| `http://loinc.org` | `38796-9` | Hip - right X-ray portable |
| `http://loinc.org` | `38797-7` | Humerus bicipital groove - right X-ray |
| `http://loinc.org` | `38798-5` | Olecranon - right X-ray |
| `http://loinc.org` | `38799-3` | Aorta and Femoral artery - right Fluoroscopic angiogram runoff W contrast IA |
| `http://loinc.org` | `38800-9` | Aortic arch and Subclavian artery - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `38801-7` | Gastric artery - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `38802-5` | Wrist - right CT W and WO contrast IV |
| `http://loinc.org` | `38803-3` | Clavicle - right X-ray 45 degree cephalic angle |
| `http://loinc.org` | `38804-1` | Hand - right X-ray Bora |
| `http://loinc.org` | `38805-8` | Shoulder - right X-ray Grashey |
| `http://loinc.org` | `38806-6` | Tibia - right X-ray 10 degree caudal angle |
| `http://loinc.org` | `38807-4` | Breast - right Mammogram spot |
| `http://loinc.org` | `38808-2` | Wrist - right X-ray ulnar deviation and radial deviation |
| `http://loinc.org` | `38810-8` | Great toe - right X-ray standing |
| `http://loinc.org` | `38811-6` | Lymphatics abdominal and Lymphatics pelvic - right Fluoroscopy W contrast intra lymphatic |
| `http://loinc.org` | `38812-4` | Extremity lymphatics - right Fluoroscopy W contrast intra lymphatic |
| `http://loinc.org` | `38813-2` | Lymphatics - right Fluoroscopy W contrast intra lymphatic |
| `http://loinc.org` | `38814-0` | Calcaneus - right X-ray Broden |
| `http://loinc.org` | `38815-7` | Foot - right X-ray AP standing |
| `http://loinc.org` | `38816-5` | Shoulder - right X-ray Grashey W and WO weight |
| `http://loinc.org` | `38817-3` | Breast implant - right MRI WO contrast |
| `http://loinc.org` | `38818-1` | Hip - right X-ray during surgery |
| `http://loinc.org` | `38819-9` | Hip - right X-ray lateral during surgery |
| `http://loinc.org` | `38820-7` | Breast implant - right Mammogram |
| `http://loinc.org` | `38821-5` | Breast specimen - right Mammogram |
| `http://loinc.org` | `38822-3` | Shoulder - right X-ray AP and transthoracic |
| `http://loinc.org` | `38824-9` | Knee - right X-ray Sunrise 20 and 40 and 60 degrees |
| `http://loinc.org` | `38825-6` | Breast duct - right Mammogram W contrast intra duct |
| `http://loinc.org` | `38826-4` | Parotid gland - right Fluoroscopy W contrast intra salivary duct |
| `http://loinc.org` | `38827-2` | Lacrimal duct - right Fluoroscopy W contrast intra lacrimal duct |
| `http://loinc.org` | `38828-0` | Shoulder - left CT W contrast intraarticular |
| `http://loinc.org` | `38829-8` | Upper extremity - left MRI W contrast IV |
| `http://loinc.org` | `38830-6` | Shoulder - left MRI W contrast IV |
| `http://loinc.org` | `38831-4` | Upper extremity - left MRI W and WO contrast IV |
| `http://loinc.org` | `38832-2` | Upper extremity - left MRI WO contrast |
| `http://loinc.org` | `38833-0` | Thoracic outlet - left MRI WO contrast |
| `http://loinc.org` | `38834-8` | Shoulder - left MRI WO contrast |
| `http://loinc.org` | `38835-5` | Temporal bone - left CT W contrast IV |
| `http://loinc.org` | `38836-3` | Orbit - left MRI |
| `http://loinc.org` | `38837-1` | Knee vessels - left MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `38838-9` | Wrist - left X-ray limited |
| `http://loinc.org` | `38839-7` | Wrist - left X-ray oblique |
| `http://loinc.org` | `38840-5` | Ankle - left X-ray 2 views W manual stress |
| `http://loinc.org` | `38841-3` | Ankle - left X-ray 2 views standing |
| `http://loinc.org` | `38842-1` | Wrist - left X-ray tunnel.carpal |
| `http://loinc.org` | `38843-9` | Wrist - left X-ray 2 views tunnel.carpal |
| `http://loinc.org` | `38844-7` | Elbow - left X-ray 2 views Oblique |
| `http://loinc.org` | `38845-4` | Femur - left X-ray standing |
| `http://loinc.org` | `38846-2` | Foot - left X-ray 2 views |
| `http://loinc.org` | `38847-0` | Hand - left X-ray AP and lateral |
| `http://loinc.org` | `38848-8` | Hand - left X-ray AP and lateral and oblique |
| `http://loinc.org` | `38849-6` | Lower extremity - left X-ray AP single view standing |
| `http://loinc.org` | `38850-4` | Lower extremity - left X-ray standing |
| `http://loinc.org` | `38851-2` | Knee - left X-ray 2 views standing |
| `http://loinc.org` | `38852-0` | Knee - left X-ray 4 views standing |
| `http://loinc.org` | `38853-8` | Lower extremity vessels - left Fluoroscopic angiogram W contrast |
| `http://loinc.org` | `38854-6` | Breast - left Mammogram magnification and spot |
| `http://loinc.org` | `38855-3` | Breast - left Mammogram true lateral |
| `http://loinc.org` | `38856-1` | Ribs - left X-ray anterior and lateral |
| `http://loinc.org` | `38857-9` | Ribs - left X-ray lateral |
| `http://loinc.org` | `38858-7` | Shoulder - left X-ray Y |
| `http://loinc.org` | `38859-5` | Upper extremity veins - left Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `38860-3` | Wrist - left X-ray AP and lateral |
| `http://loinc.org` | `38861-1` | Ankle arteries - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `38862-9` | Carotid artery and Cerebral artery - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `38863-7` | Carotid artery.cervical - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `38864-5` | Carotid artery.internal - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `38865-2` | Carotid artery and Cerebral artery internal - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `38866-0` | Ribs lower - left X-ray |
| `http://loinc.org` | `38867-8` | Ribs upper - left X-ray |
| `http://loinc.org` | `38868-6` | Ribs anterior and posterior - left X-ray |
| `http://loinc.org` | `38869-4` | Ribs posterior - left X-ray |
| `http://loinc.org` | `38870-2` | Breast implant - left MRI W and WO contrast IV |
| `http://loinc.org` | `38871-0` | Knee - left X-ray 2 views Oblique |
| `http://loinc.org` | `38872-8` | Kidney - left and Collecting system Fluoroscopy W contrast via nephrostomy tube |
| `http://loinc.org` | `38873-6` | Kidney - left and Collecting system Fluoroscopy W contrast retrograde via urethra |
| `http://loinc.org` | `38874-4` | Tibia - left and Fibula - left X-ray 2 views Oblique |
| `http://loinc.org` | `38932-0` | VA Compensation and Pension (C and P) examination acromegaly |
| `http://loinc.org` | `38933-8` | VA Compensation and Pension (C and P) examination aid and attendance/housebound |
| `http://loinc.org` | `38934-6` | VA Compensation and Pension (C and P) examination arrhythmias |
| `http://loinc.org` | `38935-3` | VA Compensation and Pension (C and P) examination miscellaneous arteries/veins |
| `http://loinc.org` | `38936-1` | VA Compensation and Pension (C and P) examination audio |
| `http://loinc.org` | `38937-9` | VA Compensation and Pension (C and P) examination bones fractures/bone disease |
| `http://loinc.org` | `38938-7` | VA Compensation and Pension (C and P) examination brain/spinal cord |
| `http://loinc.org` | `38939-5` | VA Compensation and Pension (C and P) examination chronic fatigue syndrome |
| `http://loinc.org` | `38940-3` | VA Compensation and Pension (C and P) examination cold injury protocol |
| `http://loinc.org` | `38941-1` | VA Compensation and Pension (C and P) examination cranial nerves |
| `http://loinc.org` | `38942-9` | VA Compensation and Pension (C and P) examination Cushings syndrome |
| `http://loinc.org` | `38943-7` | VA Compensation and Pension (C and P) examination dental/oral |
| `http://loinc.org` | `38944-5` | VA Compensation and Pension (C and P) examination diabetes mellitus |
| `http://loinc.org` | `38945-2` | VA Compensation and Pension (C and P) examination miscellaneous digestive conditions |
| `http://loinc.org` | `38946-0` | VA Compensation and Pension (C and P) examination ear disease |
| `http://loinc.org` | `38947-8` | VA Compensation and Pension (C and P) examination mental health eating disorders |
| `http://loinc.org` | `38948-6` | VA Compensation and Pension (C and P) examination miscellaneous endocrine diseases |
| `http://loinc.org` | `38949-4` | VA Compensation and Pension (C and P) examination epilepsy/narcolepsy |
| `http://loinc.org` | `38950-2` | VA Compensation and Pension (C and P) examination esophagus/hiatal hernia |
| `http://loinc.org` | `38951-0` | VA Compensation and Pension (C and P) examination eye |
| `http://loinc.org` | `38952-8` | VA Compensation and Pension (C and P) examination feet |
| `http://loinc.org` | `38953-6` | VA Compensation and Pension (C and P) examination fibromyalgia |
| `http://loinc.org` | `38954-4` | VA Compensation and Pension (C and P) examination general medical |
| `http://loinc.org` | `38955-1` | VA Compensation and Pension (C and P) examination genitourinary |
| `http://loinc.org` | `38956-9` | VA Compensation and Pension (C and P) examination disability in gulf war veterans |
| `http://loinc.org` | `38957-7` | VA Compensation and Pension (C and P) examination gynecological conditions/disorders of the breast |
| `http://loinc.org` | `38958-5` | VA Compensation and Pension (C and P) examination hand/thumb/fingers |
| `http://loinc.org` | `38959-3` | VA Compensation and Pension (C and P) examination heart |
| `http://loinc.org` | `38960-1` | VA Compensation and Pension (C and P) examination hemic disorders |
| `http://loinc.org` | `38961-9` | VA Compensation and Pension (C and P) examination HIV-related illness |
| `http://loinc.org` | `38962-7` | VA Compensation and Pension (C and P) examination hypertension |
| `http://loinc.org` | `38963-5` | VA Compensation and Pension (C and P) examination infectious/immune/nutritional disabilities |
| `http://loinc.org` | `38964-3` | VA Compensation and Pension (C and P) examination initial evaluation post-traumatic stress disorder |
| `http://loinc.org` | `38965-0` | VA Compensation and Pension (C and P) examination large/small intestines |
| `http://loinc.org` | `38966-8` | VA Compensation and Pension (C and P) examination extremity joints |
| `http://loinc.org` | `38967-6` | VA Compensation and Pension (C and P) examination liver/gall bladder/pancreas |
| `http://loinc.org` | `38968-4` | VA Compensation and Pension (C and P) examination lymphatic disorders |
| `http://loinc.org` | `38969-2` | VA Compensation and Pension (C and P) examination general mental disorders |
| `http://loinc.org` | `38970-0` | VA Compensation and Pension (C and P) examination mouth/lips/tongue |
| `http://loinc.org` | `38971-8` | VA Compensation and Pension (C and P) examination muscles |
| `http://loinc.org` | `38972-6` | VA Compensation and Pension (C and P) examination miscellaneous neurological disorders |
| `http://loinc.org` | `38973-4` | VA Compensation and Pension (C and P) examination nose/sinus/larynx/pharynx |
| `http://loinc.org` | `38974-2` | VA Compensation and Pension (C and P) examination peripheral nerves |
| `http://loinc.org` | `38975-9` | VA Compensation and Pension (C and P) examination prisoner of war protocol |
| `http://loinc.org` | `38976-7` | VA Compensation and Pension (C and P) examination pulmonary tuberculosis/mycobacterial diseases |
| `http://loinc.org` | `38977-5` | VA Compensation and Pension (C and P) examination rectum/anus |
| `http://loinc.org` | `38978-3` | VA Compensation and Pension (C and P) examination residuals of amputations |
| `http://loinc.org` | `38979-1` | VA Compensation and Pension (C and P) examination obstructive/restrictive/interstitial respiratory diseases |
| `http://loinc.org` | `38980-9` | VA Compensation and Pension (C and P) examination miscellaneous respiratory diseases |
| `http://loinc.org` | `38981-7` | VA Compensation and Pension (C and P) examination review evaluation post-traumatic stress disorder |
| `http://loinc.org` | `38982-5` | VA Compensation and Pension (C and P) examination scars |
| `http://loinc.org` | `38983-3` | VA Compensation and Pension (C and P) examination sense of smell/taste |
| `http://loinc.org` | `38984-1` | VA Compensation and Pension (C and P) examination skin diseases other than scars |
| `http://loinc.org` | `38985-8` | VA Compensation and Pension (C and P) examination social/industrial survey |
| `http://loinc.org` | `38986-6` | VA Compensation and Pension (C and P) examination spine |
| `http://loinc.org` | `38987-4` | VA Compensation and Pension (C and P) examination stomach/duodenum/peritoneal adhesions |
| `http://loinc.org` | `38988-2` | VA Compensation and Pension (C and P) examination thyroid/parathyroid diseases |
| `http://loinc.org` | `39026-0` | CT Guidance for needle localization of Unspecified body region |
| `http://loinc.org` | `39027-8` | Fluoroscopy Guidance for needle localization of Unspecified body region |
| `http://loinc.org` | `39028-6` | MRI Guidance for needle localization of Unspecified body region |
| `http://loinc.org` | `39029-4` | Orbit and Face MRI W and WO contrast IV |
| `http://loinc.org` | `39030-2` | Vein - bilateral US |
| `http://loinc.org` | `39031-0` | Extremity artery - bilateral US.doppler |
| `http://loinc.org` | `39032-8` | Kidney transplant US |
| `http://loinc.org` | `39033-6` | Upper extremity MRI WO contrast |
| `http://loinc.org` | `39034-4` | Upper extremity MRI W and WO contrast IV |
| `http://loinc.org` | `39036-9` | Vein US |
| `http://loinc.org` | `39037-7` | Upper extremity MRI W contrast IV |
| `http://loinc.org` | `39038-5` | Orbit and Face MRI W contrast IV |
| `http://loinc.org` | `39039-3` | Brachiocephalic artery US.doppler |
| `http://loinc.org` | `39040-1` | AV fistula US |
| `http://loinc.org` | `39042-7` | Extremity artery US.doppler |
| `http://loinc.org` | `39043-5` | Unspecified body region MRI and 3D reconstruction |
| `http://loinc.org` | `39044-3` | Head vessels US.doppler limited |
| `http://loinc.org` | `39045-0` | Vein US limited |
| `http://loinc.org` | `39046-8` | Pelvis CT limited pelvimetry WO contrast |
| `http://loinc.org` | `39047-6` | Hip Fluoroscopy during surgery |
| `http://loinc.org` | `39048-4` | Scapula X-ray AP single view |
| `http://loinc.org` | `39049-2` | Spine Thoracic and Lumbar X-ray AP single view |
| `http://loinc.org` | `39050-0` | Ribs X-ray AP single view |
| `http://loinc.org` | `39051-8` | Chest X-ray lateral |
| `http://loinc.org` | `39052-6` | Spine X-ray lateral |
| `http://loinc.org` | `39053-4` | Ribs X-ray lateral |
| `http://loinc.org` | `39054-2` | Breast duct Mammogram W contrast intra duct |
| `http://loinc.org` | `39055-9` | Extremity veins Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `39056-7` | Unspecified body region X-ray W manual stress |
| `http://loinc.org` | `39057-5` | Pulmonary artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `39058-3` | Salivary gland X-ray |
| `http://loinc.org` | `39059-1` | Gastrointestine upper Fluoroscopy W air and barium contrast PO |
| `http://loinc.org` | `39060-9` | Ribs X-ray 2 views |
| `http://loinc.org` | `39061-7` | Sacrum and Coccyx X-ray 3 views |
| `http://loinc.org` | `39062-5` | Ribs X-ray 3 views |
| `http://loinc.org` | `39063-3` | Spine Lumbar X-ray 5 views W flexion and W extension |
| `http://loinc.org` | `39064-1` | Ribs X-ray anterior and lateral |
| `http://loinc.org` | `39065-8` | Pelvis X-ray AP and inlet and outlet and oblique |
| `http://loinc.org` | `39066-6` | Chest Fluoroscopy AP and lateral |
| `http://loinc.org` | `39067-4` | Spine Cervical and Thoracic and Lumbar X-ray AP and lateral |
| `http://loinc.org` | `39068-2` | Foot X-ray AP and lateral standing |
| `http://loinc.org` | `39069-0` | Foot X-ray AP and lateral |
| `http://loinc.org` | `39070-8` | Chest X-ray AP and lateral and lordotic |
| `http://loinc.org` | `39071-6` | Knee X-ray AP and lateral and Merchants |
| `http://loinc.org` | `39072-4` | Ankle X-ray AP and lateral and oblique |
| `http://loinc.org` | `39073-2` | Knee X-ray AP and lateral and right oblique and left oblique |
| `http://loinc.org` | `39074-0` | Chest X-ray AP and lateral and right oblique and left oblique |
| `http://loinc.org` | `39075-7` | Toes X-ray AP and oblique |
| `http://loinc.org` | `39076-5` | Foot X-ray AP and oblique |
| `http://loinc.org` | `39077-3` | Shoulder X-ray AP and transthoracic |
| `http://loinc.org` | `39078-1` | Finger X-ray PA and lateral and oblique |
| `http://loinc.org` | `39079-9` | Hand X-ray PA and oblique |
| `http://loinc.org` | `39093-0` | Hepatic veins Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `39094-8` | Carotid artery.cervical Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `39095-5` | Carotid artery and Cerebral artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `39096-3` | Hepatic veins Fluoroscopic angiogram W contrast IV and W hemodynamics |
| `http://loinc.org` | `39097-1` | Carotid artery - bilateral and Cerebral artery - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `39098-9` | Carotid artery.cervical - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `39099-7` | Ribs - bilateral and Chest X-ray 4 views and PA chest |
| `http://loinc.org` | `39100-3` | Ribs - right and Chest X-ray lateral and PA chest |
| `http://loinc.org` | `39101-1` | Ribs and Chest X-ray lateral and PA chest |
| `http://loinc.org` | `39138-3` | Fluoroscopic angiogram Guidance for vascular access of Vessel |
| `http://loinc.org` | `39139-1` | US Guidance for vascular access of Unspecified body region |
| `http://loinc.org` | `39140-9` | Heart MRI cine for blood flow velocity mapping |
| `http://loinc.org` | `39141-7` | Bone marrow MRI for blood flow |
| `http://loinc.org` | `39142-5` | Head CT perfusion W contrast IV |
| `http://loinc.org` | `39144-1` | Gastrointestine upper Fluoroscopy W air contrast PO |
| `http://loinc.org` | `39145-8` | Breast duct - left Mammogram W contrast intra multiple ducts |
| `http://loinc.org` | `39146-6` | Breast duct - bilateral Mammogram W contrast intra multiple ducts |
| `http://loinc.org` | `39147-4` | Breast duct - right Mammogram W contrast intra multiple ducts |
| `http://loinc.org` | `39148-2` | Breast duct Mammogram W contrast intra multiple ducts |
| `http://loinc.org` | `39149-0` | Gastrointestinal system and Respiratory system X-ray for foreign body |
| `http://loinc.org` | `39150-8` | Breast FFD mammogram Post Localization |
| `http://loinc.org` | `39151-6` | Vas deferens Fluoroscopy W contrast intra vas deferens |
| `http://loinc.org` | `39152-4` | Breast FFD mammogram diagnostic |
| `http://loinc.org` | `39153-2` | Breast FFD mammogram screening |
| `http://loinc.org` | `39154-0` | Breast - bilateral FFD mammogram diagnostic |
| `http://loinc.org` | `39291-0` | Lower extremity MRI W and WO contrast IV |
| `http://loinc.org` | `39292-8` | Lower extremity MRI WO contrast |
| `http://loinc.org` | `39293-6` | Lower extremity MRI W contrast IV |
| `http://loinc.org` | `39321-5` | Shoulder X-ray AP (W internal rotation and W external rotation) and axillary |
| `http://loinc.org` | `39322-3` | Spine CT W contrast intradisc |
| `http://loinc.org` | `39323-1` | Abdomen X-ray right posterior oblique |
| `http://loinc.org` | `39324-9` | Wrist - left X-ray PA W clenched fist |
| `http://loinc.org` | `39325-6` | Shoulder - left X-ray AP (W internal rotation) and Grashey and axillary and outlet |
| `http://loinc.org` | `39326-4` | Ribs - left and Chest X-ray |
| `http://loinc.org` | `39327-2` | Abdomen and Fetus X-ray for fetal age |
| `http://loinc.org` | `39328-0` | Shoulder - left X-ray AP (W internal rotation and W external rotation) |
| `http://loinc.org` | `39329-8` | Shoulder - bilateral X-ray AP (W internal rotation and W external rotation) |
| `http://loinc.org` | `39330-6` | Ankle - bilateral X-ray AP and lateral standing |
| `http://loinc.org` | `39331-4` | Foot - bilateral X-ray AP and lateral standing |
| `http://loinc.org` | `39332-2` | Foot - left X-ray AP and lateral standing |
| `http://loinc.org` | `39333-0` | Spine Lumbar X-ray AP and lateral standing |
| `http://loinc.org` | `39334-8` | Foot - left X-ray AP and lateral and oblique standing |
| `http://loinc.org` | `39335-5` | Shoulder - left X-ray AP (W internal rotation and W external rotation) and axillary |
| `http://loinc.org` | `39336-3` | Shoulder - bilateral X-ray AP (W internal rotation and W external rotation) and axillary |
| `http://loinc.org` | `39337-1` | Shoulder - bilateral X-ray AP (W internal rotation and W external rotation) and axillary and outlet |
| `http://loinc.org` | `39338-9` | Shoulder - left X-ray AP (W internal rotation and W external rotation) and axillary and Y |
| `http://loinc.org` | `39339-7` | Shoulder - bilateral X-ray AP and axillary and outlet and 30 degree caudal angle |
| `http://loinc.org` | `39340-5` | Spine Lumbar X-ray lateral standing and W flexion and W extension |
| `http://loinc.org` | `39341-3` | Chest X-ray lateral and PA W inspiration and expiration |
| `http://loinc.org` | `39343-9` | Shoulder - bilateral X-ray AP (W internal rotation and W external rotation) and Y |
| `http://loinc.org` | `39344-7` | Shoulder - bilateral X-ray AP (W internal rotation and W external rotation) and axillary and Y |
| `http://loinc.org` | `39345-4` | Knee - left X-ray Sunrise and tunnel standing |
| `http://loinc.org` | `39346-2` | Shoulder - bilateral X-ray AP (W internal rotation) and West Point |
| `http://loinc.org` | `39347-0` | Shoulder - left X-ray AP (W internal rotation) and West Point |
| `http://loinc.org` | `39348-8` | Shoulder - left X-ray AP (W internal rotation and W external rotation) and Y |
| `http://loinc.org` | `39349-6` | Kidney - bilateral Fluoroscopy W contrast retrograde |
| `http://loinc.org` | `39350-4` | Shoulder - bilateral X-ray Grashey and outlet and Serendipity |
| `http://loinc.org` | `39351-2` | Ribs upper anterior and posterior - left X-ray |
| `http://loinc.org` | `39352-0` | Ribs posterior - bilateral X-ray |
| `http://loinc.org` | `39353-8` | Ribs upper posterior - left X-ray |
| `http://loinc.org` | `39359-5` | Kidney - bilateral X-ray tomograph WO contrast |
| `http://loinc.org` | `39360-3` | Pelvis X-ray and inlet and outlet |
| `http://loinc.org` | `39361-1` | Fluoroscopy Guidance for abscess drainage of Liver |
| `http://loinc.org` | `39362-9` | Fluoroscopy Guidance for placement of tube in Chest |
| `http://loinc.org` | `39363-7` | Fistula Fluoroscopy W contrast retrograde |
| `http://loinc.org` | `39364-5` | Wrist - right X-ray 3 views and radial deviation |
| `http://loinc.org` | `39365-2` | Wrist - right X-ray 3 views and ulnar deviation |
| `http://loinc.org` | `39366-0` | Scapula X-ray lateral and outlet |
| `http://loinc.org` | `39367-8` | Spine Thoracic and Lumbar X-ray scoliosis AP and lateral standing |
| `http://loinc.org` | `39368-6` | Ankle - right X-ray AP and lateral standing |
| `http://loinc.org` | `39369-4` | Ankle - right X-ray AP and lateral and oblique W manual stress |
| `http://loinc.org` | `39370-2` | Ankle - right X-ray and (view W manual stress) |
| `http://loinc.org` | `39371-0` | Ankle - right X-ray AP and lateral and oblique standing |
| `http://loinc.org` | `39372-8` | Ankle - right X-ray and Mortise |
| `http://loinc.org` | `39373-6` | Elbow - right X-ray and oblique |
| `http://loinc.org` | `39374-4` | Foot - right X-ray AP and lateral standing |
| `http://loinc.org` | `39375-1` | Foot - right X-ray AP and lateral and oblique standing |
| `http://loinc.org` | `39376-9` | Radius - right and Ulna - right X-ray and oblique |
| `http://loinc.org` | `39377-7` | Hip - right X-ray and lateral crosstable |
| `http://loinc.org` | `39378-5` | Knee - right X-ray 2 views and oblique |
| `http://loinc.org` | `39379-3` | Knee - right X-ray 2 views and Sunrise |
| `http://loinc.org` | `39380-1` | Knee - right X-ray 2 views and Sunrise and tunnel |
| `http://loinc.org` | `39381-9` | Knee - right X-ray 2 views and tunnel |
| `http://loinc.org` | `39382-7` | Knee - right X-ray 2 views and tunnel standing |
| `http://loinc.org` | `39383-5` | Knee - right X-ray 3 views and Sunrise |
| `http://loinc.org` | `39384-3` | Knee - right X-ray 4 views and AP standing |
| `http://loinc.org` | `39385-0` | Knee - right X-ray 4 views and oblique |
| `http://loinc.org` | `39386-8` | Knee - right X-ray 4 views and tunnel |
| `http://loinc.org` | `39387-6` | Knee - right X-ray 4 views and Sunrise and tunnel |
| `http://loinc.org` | `39388-4` | Knee - right X-ray AP and lateral and right oblique and left oblique |
| `http://loinc.org` | `39389-2` | Knee - right X-ray and tunnel |
| `http://loinc.org` | `39390-0` | Knee - right X-ray and oblique |
| `http://loinc.org` | `39391-8` | Knee - right X-ray and Sunrise |
| `http://loinc.org` | `39392-6` | Shoulder - right X-ray (W internal rotation and W external rotation) and axillary |
| `http://loinc.org` | `39393-4` | Shoulder - right X-ray 3 views and axillary |
| `http://loinc.org` | `39394-2` | Shoulder - right X-ray 3 views and Y |
| `http://loinc.org` | `39395-9` | Shoulder - right X-ray AP (W internal rotation and W external rotation) |
| `http://loinc.org` | `39396-7` | Shoulder - right X-ray AP (W internal rotation) and West Point |
| `http://loinc.org` | `39397-5` | Shoulder - right X-ray AP (W internal rotation and W external rotation) and West Point |
| `http://loinc.org` | `39398-3` | Tibia - right and Fibula - right X-ray and oblique |
| `http://loinc.org` | `39399-1` | Wrist - right X-ray 3 views and carpal tunnel |
| `http://loinc.org` | `39400-7` | Wrist - right X-ray and carpal tunnel |
| `http://loinc.org` | `39401-5` | Shoulder X-ray AP and Grashey and axillary |
| `http://loinc.org` | `39402-3` | Shoulder X-ray AP (W internal rotation and W external rotation) |
| `http://loinc.org` | `39403-1` | Shoulder X-ray axillary and transcapular |
| `http://loinc.org` | `39404-9` | Sinuses X-ray 3 views and submentovertex |
| `http://loinc.org` | `39405-6` | Sternum X-ray lateral and right oblique and left oblique |
| `http://loinc.org` | `39406-4` | Sternum X-ray lateral and right anterior oblique |
| `http://loinc.org` | `39407-2` | Spine Thoracic X-ray 5 views and oblique |
| `http://loinc.org` | `39408-0` | Spine Thoracic X-ray tomograph AP |
| `http://loinc.org` | `39409-8` | Spine Thoracic X-ray tomograph lateral |
| `http://loinc.org` | `39410-6` | Spine Thoracic X-ray AP single view W left bending |
| `http://loinc.org` | `39411-4` | Spine Thoracic X-ray AP single view W right bending |
| `http://loinc.org` | `39412-2` | Spine Thoracic X-ray and Swimmers |
| `http://loinc.org` | `39413-0` | Spine Thoracic X-ray 4 views and oblique |
| `http://loinc.org` | `39414-8` | Spine Thoracic X-ray and oblique |
| `http://loinc.org` | `39415-5` | Gastrointestine US |
| `http://loinc.org` | `39416-3` | Genitourinary system US |
| `http://loinc.org` | `39418-9` | Extremity vein - bilateral US.doppler |
| `http://loinc.org` | `39419-7` | Renal vessels - bilateral US.doppler |
| `http://loinc.org` | `39420-5` | Lower extremity vein - bilateral US.doppler |
| `http://loinc.org` | `39421-3` | Lower extremity artery - bilateral US.doppler |
| `http://loinc.org` | `39422-1` | Lower extremity vessels - bilateral US.doppler |
| `http://loinc.org` | `39423-9` | Upper extremity artery - bilateral US.doppler |
| `http://loinc.org` | `39424-7` | Extremity vessels US.doppler limited |
| `http://loinc.org` | `39425-4` | Iliac artery US.doppler |
| `http://loinc.org` | `39426-2` | Renal vessels US.doppler |
| `http://loinc.org` | `39427-0` | Carotid artery - left US.doppler |
| `http://loinc.org` | `39428-8` | Extremity artery - left US.doppler |
| `http://loinc.org` | `39429-6` | Extremity vein - left US.doppler |
| `http://loinc.org` | `39430-4` | Lower extremity vessels - left US.doppler limited |
| `http://loinc.org` | `39431-2` | Lower extremity vessels - left US.doppler |
| `http://loinc.org` | `39432-0` | Lower extremity vein - left US.doppler |
| `http://loinc.org` | `39433-8` | Upper extremity vessels - left US.doppler |
| `http://loinc.org` | `39434-6` | Lower extremity artery US.doppler |
| `http://loinc.org` | `39435-3` | Renal artery US.doppler |
| `http://loinc.org` | `39436-1` | Renal vessels US.doppler limited |
| `http://loinc.org` | `39437-9` | Carotid artery - right US.doppler |
| `http://loinc.org` | `39439-5` | Extremity artery - right US.doppler |
| `http://loinc.org` | `39440-3` | Extremity vein - right US.doppler |
| `http://loinc.org` | `39441-1` | Lower extremity vessels - right US.doppler limited |
| `http://loinc.org` | `39442-9` | Lower extremity vessels - right US.doppler |
| `http://loinc.org` | `39443-7` | Lower extremity vein - right US.doppler |
| `http://loinc.org` | `39444-5` | Upper extremity vessels - right US.doppler |
| `http://loinc.org` | `39445-2` | Vessels US.doppler |
| `http://loinc.org` | `39446-0` | Testicle vessels US.doppler |
| `http://loinc.org` | `39447-8` | Upper extremity artery US.doppler |
| `http://loinc.org` | `39448-6` | Upper extremity vessels US.doppler |
| `http://loinc.org` | `39449-4` | Extremity vein US.doppler |
| `http://loinc.org` | `39450-2` | Gastrointestine US W contrast PO |
| `http://loinc.org` | `39451-0` | US Guidance for abscess drainage of Unspecified body region |
| `http://loinc.org` | `39452-8` | US Guidance for aspiration of Ovary |
| `http://loinc.org` | `39453-6` | Tendon US |
| `http://loinc.org` | `39454-4` | Liver transplant US |
| `http://loinc.org` | `39489-0` | Ribs lower posterior X-ray |
| `http://loinc.org` | `39490-8` | Femur - right and Tibia - right X-ray for leg length |
| `http://loinc.org` | `39491-6` | Ribs upper anterior and posterior - right X-ray |
| `http://loinc.org` | `39492-4` | Ribs upper posterior - right X-ray |
| `http://loinc.org` | `39493-2` | Ribs lower posterior - right X-ray |
| `http://loinc.org` | `39494-0` | Abdominal wall US |
| `http://loinc.org` | `39495-7` | Extremity vessels - bilateral US.doppler |
| `http://loinc.org` | `39496-5` | Upper extremity vein - bilateral US.doppler |
| `http://loinc.org` | `39497-3` | Iliac vessels US.doppler |
| `http://loinc.org` | `39498-1` | Femoral vessels - left US.doppler |
| `http://loinc.org` | `39499-9` | Lower extremity artery - left US.doppler |
| `http://loinc.org` | `39500-4` | Upper extremity artery - left US.doppler |
| `http://loinc.org` | `39501-2` | Upper extremity vein - left US.doppler |
| `http://loinc.org` | `39502-0` | Ovarian vessels US.doppler |
| `http://loinc.org` | `39503-8` | Extremity vessels - right US.doppler |
| `http://loinc.org` | `39504-6` | Femoral vessels - right US.doppler |
| `http://loinc.org` | `39505-3` | Lower extremity artery - right US.doppler |
| `http://loinc.org` | `39506-1` | Upper extremity artery - right US.doppler |
| `http://loinc.org` | `39507-9` | Upper extremity vein - right US.doppler |
| `http://loinc.org` | `39508-7` | Umbilical vessels US.doppler |
| `http://loinc.org` | `39509-5` | Pancreas transplant US |
| `http://loinc.org` | `39510-3` | Lymphatics pelvic Fluoroscopy W contrast intra lymphatic |
| `http://loinc.org` | `39511-1` | Pelvis X-ray and oblique |
| `http://loinc.org` | `39512-9` | Hip - right X-ray AP and Danelius Miller |
| `http://loinc.org` | `39513-7` | Hip - right X-ray and Danelius Miller |
| `http://loinc.org` | `39514-5` | Hip - right X-ray Danelius Miller |
| `http://loinc.org` | `39515-2` | Wrist - right X-ray lateral W flexion and W extension |
| `http://loinc.org` | `39516-0` | Shoulder X-ray Stryker Notch |
| `http://loinc.org` | `39517-8` | Shoulder X-ray Stryker Notch and West Point |
| `http://loinc.org` | `39518-6` | Bones long X-ray survey limited |
| `http://loinc.org` | `39519-4` | Skull X-ray PA and right lateral and left lateral |
| `http://loinc.org` | `39520-2` | Skull X-ray PA and right lateral and left lateral and Towne |
| `http://loinc.org` | `39521-0` | Skull X-ray PA and right lateral and left lateral and Caldwell and Towne |
| `http://loinc.org` | `39522-8` | US Guidance for biopsy of Lymph node |
| `http://loinc.org` | `39523-6` | Artery US.doppler |
| `http://loinc.org` | `39524-4` | Vein US.doppler limited |
| `http://loinc.org` | `39525-1` | Vein US.doppler |
| `http://loinc.org` | `39526-9` | Extremity US limited |
| `http://loinc.org` | `39527-7` | Unspecified body region US of foreign body |
| `http://loinc.org` | `39619-2` | Pulmonary system Scan |
| `http://loinc.org` | `39620-0` | Scan Guidance for abscess localization limited |
| `http://loinc.org` | `39621-8` | SPECT Guidance for abscess localization |
| `http://loinc.org` | `39622-6` | SPECT Guidance for abscess localization whole body |
| `http://loinc.org` | `39623-4` | Scan Guidance for abscess localization whole body |
| `http://loinc.org` | `39624-2` | Adrenal gland Scan W I-131 NP59 IV |
| `http://loinc.org` | `39625-9` | Artery Scan W Tc-99m DTPA IA |
| `http://loinc.org` | `39626-7` | Vein - bilateral Scan |
| `http://loinc.org` | `39627-5` | Bone Scan limited |
| `http://loinc.org` | `39628-3` | Meckels diverticulum SPECT |
| `http://loinc.org` | `39629-1` | Meckels diverticulum Scan |
| `http://loinc.org` | `39630-9` | Brain Scan W Tc-99m HMPAO IV |
| `http://loinc.org` | `39631-7` | Brain SPECT W Tc-99m HMPAO IV |
| `http://loinc.org` | `39632-5` | Brain SPECT |
| `http://loinc.org` | `39633-3` | Brain Scan static |
| `http://loinc.org` | `39634-1` | Brain Scan static limited |
| `http://loinc.org` | `39635-8` | Brain Scan W Tl-201 IV |
| `http://loinc.org` | `39636-6` | Brain Scan flow |
| `http://loinc.org` | `39637-4` | Brain SPECT flow |
| `http://loinc.org` | `39638-2` | Brain SPECT W I-123 IV |
| `http://loinc.org` | `39639-0` | Brain SPECT W Tl-201 IV |
| `http://loinc.org` | `39640-8` | Brain SPECT W Tc-99m DTPA IV |
| `http://loinc.org` | `39641-6` | Brain SPECT W Tc-99m glucoheptonate IV |
| `http://loinc.org` | `39642-4` | Brain Scan W Tc-99m glucoheptonate IV |
| `http://loinc.org` | `39643-2` | Brain veins Scan |
| `http://loinc.org` | `39644-0` | Breast SPECT |
| `http://loinc.org` | `39645-7` | Breast Scan limited |
| `http://loinc.org` | `39646-5` | Breast Scan |
| `http://loinc.org` | `39647-3` | Heart SPECT W Tc-99m Tetrofosmin IV |
| `http://loinc.org` | `39648-1` | Heart SPECT W dipyridamole and W radionuclide IV |
| `http://loinc.org` | `39649-9` | Heart SPECT |
| `http://loinc.org` | `39650-7` | Heart Scan |
| `http://loinc.org` | `39651-5` | Heart Scan W adenosine and W Tl-201 IV |
| `http://loinc.org` | `39652-3` | Heart Scan W dobutamine and W Tl-201 IV |
| `http://loinc.org` | `39653-1` | Heart Scan for infarct |
| `http://loinc.org` | `39654-9` | Heart SPECT for infarct W Tc-99m PYP IV |
| `http://loinc.org` | `39655-6` | Heart SPECT for infarct W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39656-4` | Heart SPECT for infarct |
| `http://loinc.org` | `39657-2` | Heart Scan for infarct W Tc-99m PYP IV |
| `http://loinc.org` | `39658-0` | Heart SPECT at rest and W radionuclide IV |
| `http://loinc.org` | `39660-6` | Heart Scan at rest and W dipyridamole and W radionuclide IV |
| `http://loinc.org` | `39661-4` | Heart Scan at rest and W dobutamine and W radionuclide IV |
| `http://loinc.org` | `39662-2` | Heart SPECT at rest and W stress and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39663-0` | Heart Scan at rest and W stress and W radionuclide IV |
| `http://loinc.org` | `39664-8` | Heart Scan for shunt detection W Tc-99m MAA IV |
| `http://loinc.org` | `39665-5` | Heart Scan for shunt detection |
| `http://loinc.org` | `39666-3` | Heart Scan W stress and W 201 Th IV |
| `http://loinc.org` | `39667-1` | Heart Scan W stress and W radionuclide IV |
| `http://loinc.org` | `39668-9` | Heart SPECT W stress and W radionuclide IV |
| `http://loinc.org` | `39669-7` | Scan whole body W Tc-99m Arcitumomab IV |
| `http://loinc.org` | `39670-5` | Lacrimal duct Scan W radionuclide intra lacrimal duct |
| `http://loinc.org` | `39671-3` | Rectum Scan W radionuclide PO |
| `http://loinc.org` | `39672-1` | Esophagus Scan for motility W radionuclide PO |
| `http://loinc.org` | `39673-9` | Esophagus Scan for reflux W radionuclide PO |
| `http://loinc.org` | `39674-7` | Gallbladder Scan W Tc-99m DISIDA IV |
| `http://loinc.org` | `39675-4` | SPECT for infection W GA-67 IV |
| `http://loinc.org` | `39676-2` | Scan static for infection W GA-67 IV |
| `http://loinc.org` | `39677-0` | Scan for infection W GA-67 IV |
| `http://loinc.org` | `39678-8` | SPECT for tumor W GA-67 IV |
| `http://loinc.org` | `39679-6` | Scan for tumor W GA-67 IV |
| `http://loinc.org` | `39680-4` | SPECT whole body W GA-67 IV |
| `http://loinc.org` | `39681-2` | SPECT limited W GA-67 IV |
| `http://loinc.org` | `39682-0` | SPECT W GA-67 IV |
| `http://loinc.org` | `39683-8` | Scan whole body W GA-67 IV |
| `http://loinc.org` | `39684-6` | SPECT for abscess W GA-67 IV |
| `http://loinc.org` | `39685-3` | Scan for abscess W GA-67 IV |
| `http://loinc.org` | `39686-1` | Scan for lymphoma W GA-67 IV |
| `http://loinc.org` | `39687-9` | Scan limited W GA-67 IV |
| `http://loinc.org` | `39688-7` | Scan W GA-67 IV |
| `http://loinc.org` | `39689-5` | Gastrointestine Scan W Tc-99m SC IV |
| `http://loinc.org` | `39690-3` | Liver Scan W Tc-99m tagged RBC IV |
| `http://loinc.org` | `39691-1` | Liver SPECT W Tc-99m tagged RBC IV |
| `http://loinc.org` | `39692-9` | Liver SPECT |
| `http://loinc.org` | `39693-7` | Liver Scan |
| `http://loinc.org` | `39694-5` | Liver transplant Scan |
| `http://loinc.org` | `39695-2` | Lung Scan limited |
| `http://loinc.org` | `39696-0` | Lung Scan W depreotide and W radionuclide IV |
| `http://loinc.org` | `39697-8` | Lung Scan perfusion |
| `http://loinc.org` | `39698-6` | Scan whole body W I-131 MIBG IV |
| `http://loinc.org` | `39699-4` | Heart Scan perfusion at rest and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39700-0` | Heart SPECT perfusion W adenosine and W radionuclide IV |
| `http://loinc.org` | `39701-8` | Heart Scan perfusion W adenosine and W radionuclide IV |
| `http://loinc.org` | `39702-6` | Heart Scan perfusion W dobutamine and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39703-4` | Heart Scan perfusion W dobutamine and W radionuclide IV |
| `http://loinc.org` | `39704-2` | Heart Scan perfusion W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39705-9` | Heart Scan perfusion W dipyridamole and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39707-5` | Heart Scan perfusion W dipyridamole and W Tl-201 IV |
| `http://loinc.org` | `39708-3` | Heart Scan perfusion W dipyridamole and W radionuclide IV |
| `http://loinc.org` | `39709-1` | Heart Scan perfusion W dipyridamole and W Tc-99m IV |
| `http://loinc.org` | `39710-9` | Heart SPECT perfusion W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39711-7` | Heart SPECT perfusion W Tl-201 IV |
| `http://loinc.org` | `39712-5` | Heart SPECT perfusion |
| `http://loinc.org` | `39713-3` | Heart Scan perfusion W Tl-201 IV and Tc-99m Tetrofosmin IV |
| `http://loinc.org` | `39714-1` | Heart Scan perfusion W Tl-201 IV |
| `http://loinc.org` | `39715-8` | Heart Scan perfusion W stress and W Tl-201 IV |
| `http://loinc.org` | `39716-6` | Heart Scan perfusion |
| `http://loinc.org` | `39718-2` | Heart SPECT perfusion at rest and W radionuclide IV |
| `http://loinc.org` | `39719-0` | Heart Scan perfusion at rest and W adenosine and W radionuclide IV |
| `http://loinc.org` | `39720-8` | Heart Scan perfusion at rest and W dipyridamole and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39722-4` | Heart Scan perfusion at rest and W dipyridamole and W radionuclide IV |
| `http://loinc.org` | `39723-2` | Heart SPECT perfusion at rest and W stress and W Tl-201 IV |
| `http://loinc.org` | `39724-0` | Heart SPECT perfusion at rest and W stress and W radionuclide IV |
| `http://loinc.org` | `39725-7` | Heart SPECT perfusion at rest and W adenosine and W Tl-201 IV |
| `http://loinc.org` | `39726-5` | Heart Scan perfusion at rest and W stress and W radionuclide IV |
| `http://loinc.org` | `39727-3` | Heart Scan perfusion at rest and W stress and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39728-1` | Heart Scan perfusion at rest and W radionuclide IV |
| `http://loinc.org` | `39729-9` | Heart SPECT perfusion at rest and W Tl-201 IV |
| `http://loinc.org` | `39730-7` | Heart Scan perfusion W stress and W radionuclide IV |
| `http://loinc.org` | `39731-5` | Heart Scan perfusion W adenosine and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39732-3` | Heart Scan perfusion W stress and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39733-1` | Heart Scan perfusion W dobutamine and W Tl-201 IV |
| `http://loinc.org` | `39734-9` | Heart SPECT perfusion W stress and W radionuclide IV |
| `http://loinc.org` | `39735-6` | Heart Scan perfusion W adenosine and W Tl-201 IV |
| `http://loinc.org` | `39736-4` | Heart SPECT perfusion W stress and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39737-2` | Neck Scan |
| `http://loinc.org` | `39738-0` | Abdomen Scan W In-111 Satumomab IV |
| `http://loinc.org` | `39739-8` | Pancreas Scan |
| `http://loinc.org` | `39740-6` | Parathyroid SPECT |
| `http://loinc.org` | `39741-4` | Parathyroid Scan delayed |
| `http://loinc.org` | `39742-2` | Parathyroid Scan |
| `http://loinc.org` | `39743-0` | Prostate SPECT W Tc-99m capromab pendatide IV |
| `http://loinc.org` | `39744-8` | Prostate Scan W Tc-99m capromab pendatide IV |
| `http://loinc.org` | `39745-5` | Kidney - bilateral Scan W Tc-99m DTPA IV |
| `http://loinc.org` | `39746-3` | Kidney - bilateral Scan W Tc-99m Mertiatide IV |
| `http://loinc.org` | `39747-1` | Salivary gland Scan |
| `http://loinc.org` | `39748-9` | SPECT for tumor W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39749-7` | Scan for tumor whole body W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39750-5` | Scan for tumor W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39751-3` | Spleen Scan |
| `http://loinc.org` | `39752-1` | Spleen Scan W radionuclide tagged heat damaged RBC IV |
| `http://loinc.org` | `39753-9` | Scrotum and Testicle Scan W Tc-99m DTPA IV |
| `http://loinc.org` | `39754-7` | Thyroid Scan limited W I-131 IV |
| `http://loinc.org` | `39755-4` | Thyroid SPECT W I-131 IV |
| `http://loinc.org` | `39756-2` | Thyroid Scan W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39757-0` | Thyroid Scan W Tc-99m IV |
| `http://loinc.org` | `39758-8` | Scan Guidance for localization of tumor of Breast |
| `http://loinc.org` | `39759-6` | SPECT Guidance for localization of tumor limited |
| `http://loinc.org` | `39760-4` | Scan Guidance for localization of tumor limited |
| `http://loinc.org` | `39761-2` | Scan Guidance for localization of tumor limited-- W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39762-0` | SPECT Guidance for localization of tumor |
| `http://loinc.org` | `39763-8` | Scan Guidance for localization of tumor |
| `http://loinc.org` | `39764-6` | Vein Scan W Tc-99m SC IV |
| `http://loinc.org` | `39765-3` | Vein Scan W Tc-99m DTPA IV |
| `http://loinc.org` | `39766-1` | Vein Scan W Tc-99m HDP IV |
| `http://loinc.org` | `39767-9` | Stomach Scan for gastric emptying liquid phase W radionuclide PO |
| `http://loinc.org` | `39768-7` | Stomach Scan for gastric emptying W Tc-99m SC PO |
| `http://loinc.org` | `39769-5` | Stomach Scan for gastric emptying W radionuclide PO |
| `http://loinc.org` | `39770-3` | Gastrointestine SPECT |
| `http://loinc.org` | `39811-5` | SPECT for abscess |
| `http://loinc.org` | `39812-3` | Bone Scan W Tc-99m HMPAO IV |
| `http://loinc.org` | `39813-1` | Bone SPECT limited |
| `http://loinc.org` | `39814-9` | Bone Scan static limited |
| `http://loinc.org` | `39815-6` | Bone Scan static |
| `http://loinc.org` | `39816-4` | Bone SPECT whole body |
| `http://loinc.org` | `39817-2` | Bone Scan static whole body |
| `http://loinc.org` | `39818-0` | Bone Scan whole body |
| `http://loinc.org` | `39819-8` | Bone Scan delayed |
| `http://loinc.org` | `39820-6` | Bone Scan W SM153 IV |
| `http://loinc.org` | `39821-4` | Bone marrow SPECT limited |
| `http://loinc.org` | `39822-2` | Bone marrow Scan limited |
| `http://loinc.org` | `39823-0` | Bone marrow SPECT |
| `http://loinc.org` | `39824-8` | Bone marrow Scan static |
| `http://loinc.org` | `39825-5` | Bone marrow SPECT whole body |
| `http://loinc.org` | `39826-3` | Bone marrow Scan whole body |
| `http://loinc.org` | `39827-1` | Scan for endocrine tumor whole body W I-131 MIBG IV |
| `http://loinc.org` | `39828-9` | Scan for endocrine tumor whole body W In-111 pentetreotide IV |
| `http://loinc.org` | `39829-7` | Scan for tumor whole body W GA-67 IV |
| `http://loinc.org` | `39830-5` | Scan for infection whole body W GA-67 IV |
| `http://loinc.org` | `39831-3` | Scan for tumor limited W GA-67 IV |
| `http://loinc.org` | `39832-1` | Liver Scan static |
| `http://loinc.org` | `39833-9` | Lung Scan perfusion W radionuclide gaseous inhaled |
| `http://loinc.org` | `39834-7` | Lung Scan ventilation W Tc-99m DTPA aerosol inhaled |
| `http://loinc.org` | `39835-4` | Lung Scan ventilation W radionuclide aerosol inhaled |
| `http://loinc.org` | `39836-2` | Lung Scan ventilation W radionuclide gaseous inhaled |
| `http://loinc.org` | `39837-0` | Lung Scan ventilation W radionuclide inhaled |
| `http://loinc.org` | `39838-8` | Lung SPECT ventilation and perfusion W radionuclide inhaled and W radionuclide IV |
| `http://loinc.org` | `39839-6` | SPECT W I-131 MIBG IV |
| `http://loinc.org` | `39840-4` | Scan delayed W I-131 MIBG IV |
| `http://loinc.org` | `39841-2` | Scan W I-131 MIBG IV |
| `http://loinc.org` | `39842-0` | Scan delayed W In-111 Satumomab IV |
| `http://loinc.org` | `39843-8` | Scan limited W In-111 Satumomab IV |
| `http://loinc.org` | `39844-6` | SPECT W In-111 Satumomab IV |
| `http://loinc.org` | `39845-3` | Scan whole body W In-111 Satumomab IV |
| `http://loinc.org` | `39846-1` | Scan W In-111 Satumomab IV |
| `http://loinc.org` | `39847-9` | Parotid gland Scan flow |
| `http://loinc.org` | `39848-7` | Peritoneovenous shunt Scan for patency W In-111 IT |
| `http://loinc.org` | `39849-5` | Peritoneovenous shunt Scan for patency W radionuclide IT |
| `http://loinc.org` | `39850-3` | Kidney - bilateral Scan W I-131 IV |
| `http://loinc.org` | `39851-1` | Kidney - bilateral SPECT W Tc-99m Mertiatide IV |
| `http://loinc.org` | `39852-9` | Kidney - bilateral SPECT |
| `http://loinc.org` | `39853-7` | Kidney - bilateral Scan static |
| `http://loinc.org` | `39854-5` | Kidney - bilateral Scan static W Tc-99m DMSA IV |
| `http://loinc.org` | `39855-2` | Scrotum and Testicle Scan static |
| `http://loinc.org` | `39856-0` | Thyroid Scan flow |
| `http://loinc.org` | `39857-8` | Adrenal gland Scan W I-131 MIBG IV |
| `http://loinc.org` | `39858-6` | Bone Scan flow |
| `http://loinc.org` | `39859-4` | Brain Scan delayed static |
| `http://loinc.org` | `39860-2` | Heart Scan blood pool W stress and W radionuclide IV |
| `http://loinc.org` | `39861-0` | Heart Scan blood pool |
| `http://loinc.org` | `39862-8` | Heart SPECT blood pool at rest and W radionuclide IV |
| `http://loinc.org` | `39863-6` | Heart Scan first pass at rest and W stress and W radionuclide IV |
| `http://loinc.org` | `39864-4` | Heart Scan first pass |
| `http://loinc.org` | `39865-1` | Left ventricle Scan first pass |
| `http://loinc.org` | `39866-9` | Heart Scan first pass at rest and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39867-7` | Heart Scan first pass at rest and W radionuclide IV |
| `http://loinc.org` | `39868-5` | Heart Scan first pass W stress and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39869-3` | Heart Scan first pass W stress and W radionuclide IV |
| `http://loinc.org` | `39870-1` | Heart Scan flow W Tc-99m pertechnetate IV |
| `http://loinc.org` | `39871-9` | Heart Scan flow |
| `http://loinc.org` | `39872-7` | Heart SPECT wall motion |
| `http://loinc.org` | `39873-5` | Heart Scan wall motion |
| `http://loinc.org` | `39874-3` | Head Cistern Scan delayed W radionuclide IT |
| `http://loinc.org` | `39875-0` | Scan delayed W GA-67 IV |
| `http://loinc.org` | `39876-8` | Liver and Spleen SPECT |
| `http://loinc.org` | `39877-6` | Liver and Spleen Scan |
| `http://loinc.org` | `39878-4` | Liver and Spleen Scan static |
| `http://loinc.org` | `39879-2` | Bone SPECT 1 phase |
| `http://loinc.org` | `39880-0` | Bone Scan 2 views phase |
| `http://loinc.org` | `39881-8` | Bone SPECT 3 phase whole body |
| `http://loinc.org` | `39882-6` | Bone Scan 3 views phase whole body |
| `http://loinc.org` | `39883-4` | Bone Scan 3 views phase |
| `http://loinc.org` | `39884-2` | Bone Scan blood pool |
| `http://loinc.org` | `39885-9` | Heart Scan first pass and ventricular volume |
| `http://loinc.org` | `39886-7` | Heart Scan first pass and wall motion at rest and W radionuclide IV |
| `http://loinc.org` | `39887-5` | Heart Scan first pass and ejection fraction at rest and W radionuclide IV |
| `http://loinc.org` | `39888-3` | Heart Scan first pass and wall motion W stress and W radionuclide IV |
| `http://loinc.org` | `39889-1` | Heart Scan first pass and ejection fraction |
| `http://loinc.org` | `39890-9` | Heart Scan first pass and wall motion |
| `http://loinc.org` | `39891-7` | Heart Scan for infarct and first pass W Tc-99m PYP IV |
| `http://loinc.org` | `39892-5` | Heart Scan for infarct and first pass |
| `http://loinc.org` | `39893-3` | Heart Scan flow for shunt detection |
| `http://loinc.org` | `39894-1` | Heart Scan static for shunt detection |
| `http://loinc.org` | `39895-8` | Gallbladder Scan ejection fraction W Tc-99m DISIDA IV |
| `http://loinc.org` | `39896-6` | Scan static for tumor W GA-67 IV |
| `http://loinc.org` | `39897-4` | Liver and Lung Scan |
| `http://loinc.org` | `39898-2` | Lung SPECT ventilation W radionuclide aerosol inhaled |
| `http://loinc.org` | `39899-0` | Salivary gland Scan flow |
| `http://loinc.org` | `39900-6` | Salivary gland Scan static |
| `http://loinc.org` | `39901-4` | Bone Scan 3 views phase multiple areas |
| `http://loinc.org` | `39902-2` | Bone Scan 3 views phase single area |
| `http://loinc.org` | `39903-0` | Bone Scan static multiple areas |
| `http://loinc.org` | `39904-8` | Bone Scan multiple areas |
| `http://loinc.org` | `39905-5` | Bone SPECT multiple areas |
| `http://loinc.org` | `39906-3` | Bone marrow SPECT multiple areas |
| `http://loinc.org` | `39907-1` | Bone marrow Scan multiple areas |
| `http://loinc.org` | `39908-9` | Heart Scan first pass and wall motion and ventricular volume W stress and W radionuclide IV |
| `http://loinc.org` | `39909-7` | Heart Scan first pass and wall motion and ventricular volume and ejection fraction W stress and W radionuclide IV |
| `http://loinc.org` | `39910-5` | Heart Scan first pass and wall motion and ejection fraction |
| `http://loinc.org` | `39912-1` | Heart Scan first pass and wall motion and ventricular volume and ejection fraction |
| `http://loinc.org` | `39913-9` | Heart SPECT gated and ejection fraction |
| `http://loinc.org` | `39914-7` | Heart Scan gated W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39915-4` | Heart Scan gated |
| `http://loinc.org` | `39916-2` | Heart SPECT gated |
| `http://loinc.org` | `39917-0` | Heart Scan gated and ejection fraction |
| `http://loinc.org` | `39918-8` | Heart SPECT gated and wall motion |
| `http://loinc.org` | `39919-6` | Heart Scan gated and first pass |
| `http://loinc.org` | `39920-4` | Heart Scan gated at rest and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39921-2` | Heart Scan gated at rest and W radionuclide IV |
| `http://loinc.org` | `39922-0` | Heart Scan gated at rest and W Tc-99m pertechnetate IV |
| `http://loinc.org` | `39923-8` | Heart Scan gated and ejection fraction at rest and W radionuclide IV |
| `http://loinc.org` | `39924-6` | Heart Scan gated at rest and W stress and W radionuclide IV |
| `http://loinc.org` | `39925-3` | Heart Scan gated and wall motion and ejection fraction at rest and W radionuclide IV |
| `http://loinc.org` | `39927-9` | Heart Scan gated W stress and W Tc-99m pertechnetate IV |
| `http://loinc.org` | `39928-7` | Heart Scan gated W stress and W radionuclide IV |
| `http://loinc.org` | `39929-5` | Heart Scan gated and wall motion W stress and W radionuclide IV |
| `http://loinc.org` | `39930-3` | Heart SPECT gated W stress and W radionuclide IV |
| `http://loinc.org` | `39931-1` | Heart Scan gated and wall motion and ejection fraction |
| `http://loinc.org` | `39932-9` | Heart Scan wall motion and ejection fraction |
| `http://loinc.org` | `39933-7` | Scan for infection multiple areas W GA-67 IV |
| `http://loinc.org` | `39934-5` | Scan for tumor multiple areas W GA-67 IV |
| `http://loinc.org` | `39935-2` | Scan multiple areas W GA-67 IV |
| `http://loinc.org` | `39936-0` | Joint Scan limited |
| `http://loinc.org` | `39937-8` | Joint Scan multiple areas |
| `http://loinc.org` | `39938-6` | Joint SPECT |
| `http://loinc.org` | `39939-4` | Joint Scan |
| `http://loinc.org` | `39940-2` | Lung Scan Clearance W Tc-99m DTPA aerosol inhaled |
| `http://loinc.org` | `39941-0` | Lung Scan perfusion W particulate radionuclide IV |
| `http://loinc.org` | `39942-8` | Lung Scan ventilation and perfusion W radionuclide inhaled single breath and W particulate radionuclide IV |
| `http://loinc.org` | `39943-6` | Lung Scan ventilation and perfusion W radionuclide inhaled and W particulate radionuclide IV |
| `http://loinc.org` | `39944-4` | Lung Scan ventilation and equilibrium and washout W radionuclide inhaled |
| `http://loinc.org` | `39945-1` | Lung Scan ventilation W radionuclide gaseous inhaled single breath |
| `http://loinc.org` | `39946-9` | Lung Scan ventilation and perfusion and differential W radionuclide inhaled and W radionuclide IV |
| `http://loinc.org` | `39947-7` | Lung Scan ventilation and equilibrium W radionuclide inhaled single breath |
| `http://loinc.org` | `39948-5` | Lung Scan ventilation and equilibrium and washout W radionuclide inhaled single breath |
| `http://loinc.org` | `39949-3` | Scan multiple areas W In-111 Satumomab IV |
| `http://loinc.org` | `39950-1` | Prostate Scan multiple areas W Tc-99m capromab pendatide IV |
| `http://loinc.org` | `39951-9` | Scan for tumor multiple area W Tc-99m Sestamibi IV |
| `http://loinc.org` | `39952-7` | Scrotum and Testicle Scan static and flow |
| `http://loinc.org` | `39953-5` | Scan Guidance for localization of tumor multiple areas |
| `http://loinc.org` | `39954-3` | Vein Scan for thrombosis |
| `http://loinc.org` | `40811-2` | 11-Deoxycorticosterone [Presence] in Serum or Plasma |
| `http://loinc.org` | `40816-1` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --1 hour post XXX challenge |
| `http://loinc.org` | `40818-7` | 11-Deoxycorticosterone [Moles/volume] in 24 hour Urine |
| `http://loinc.org` | `41770-9` | Gallbladder Scan W cholecystokinin and W radionuclide IV |
| `http://loinc.org` | `41771-7` | Kidney - bilateral Scan W Tc-99m DMSA IV |
| `http://loinc.org` | `41772-5` | Bone SPECT W In-111 tagged WBC IV |
| `http://loinc.org` | `41773-3` | Facial bones X-ray portable |
| `http://loinc.org` | `41774-1` | Neck X-ray lateral portable |
| `http://loinc.org` | `41775-8` | Pelvis X-ray Single view portable |
| `http://loinc.org` | `41776-6` | Pelvis and Hip - right X-ray AP and lateral frog portable |
| `http://loinc.org` | `41777-4` | Hip - right X-ray AP and lateral portable |
| `http://loinc.org` | `41778-2` | Femur - right X-ray portable |
| `http://loinc.org` | `41779-0` | Knee - right X-ray portable |
| `http://loinc.org` | `41782-4` | Ankle - right X-ray portable |
| `http://loinc.org` | `41783-2` | Shoulder - right X-ray portable |
| `http://loinc.org` | `41784-0` | Humerus - right X-ray portable |
| `http://loinc.org` | `41785-7` | Elbow - right X-ray limited |
| `http://loinc.org` | `41786-5` | Elbow - right X-ray portable |
| `http://loinc.org` | `41787-3` | Wrist - right X-ray portable |
| `http://loinc.org` | `41788-1` | Hand - right X-ray portable |
| `http://loinc.org` | `41789-9` | Hand - right X-ray limited |
| `http://loinc.org` | `41790-7` | Chest X-ray during surgery |
| `http://loinc.org` | `41791-5` | Ribs - right X-ray portable |
| `http://loinc.org` | `41792-3` | Chest X-ray right oblique and left oblique |
| `http://loinc.org` | `41793-1` | Abdomen X-ray during surgery |
| `http://loinc.org` | `41795-6` | Upper Gastrointestine and Small bowel Fluoroscopy W air contrast PO |
| `http://loinc.org` | `41797-2` | Colon Fluoroscopy limited W air and barium contrast PR |
| `http://loinc.org` | `41798-0` | US Guidance for drainage of Prostate |
| `http://loinc.org` | `41799-8` | Fluoroscopy Guidance for placement of tube in Liver |
| `http://loinc.org` | `41800-4` | Fluoroscopy Guidance for drainage of Pharynx |
| `http://loinc.org` | `41801-2` | Fluoroscopic angiogram Guidance for placement of catheter in Portal vein-- W contrast IV |
| `http://loinc.org` | `41802-0` | Fluoroscopy Guidance for biopsy of Prostate |
| `http://loinc.org` | `41803-8` | Fluoroscopy Guidance for needle biopsy of Breast |
| `http://loinc.org` | `41804-6` | Unspecified body region CT and 3D reconstruction |
| `http://loinc.org` | `41806-1` | Abdomen CT |
| `http://loinc.org` | `41807-9` | Orbit CT |
| `http://loinc.org` | `41808-7` | Facial bones and Maxilla CT |
| `http://loinc.org` | `41809-5` | US Guidance for drainage of Abdomen retroperitoneum |
| `http://loinc.org` | `41810-3` | CT Guidance for removal of fluid from Abdomen |
| `http://loinc.org` | `41811-1` | Ribs - bilateral and Chest X-ray and PA chest |
| `http://loinc.org` | `41812-9` | Lower extremity artery US limited |
| `http://loinc.org` | `41813-7` | Upper extremity artery US limited |
| `http://loinc.org` | `41814-5` | Upper extremity artery - right US |
| `http://loinc.org` | `41815-2` | Lower extremity artery - right US |
| `http://loinc.org` | `41816-0` | Extremity veins - right US |
| `http://loinc.org` | `41817-8` | Hip - left X-ray AP and lateral portable |
| `http://loinc.org` | `41818-6` | Femur - left X-ray portable |
| `http://loinc.org` | `41819-4` | Knee - left X-ray 2 views and tunnel |
| `http://loinc.org` | `41820-2` | Knee - left X-ray portable |
| `http://loinc.org` | `41823-6` | Ankle - left X-ray portable |
| `http://loinc.org` | `41824-4` | Shoulder - left X-ray portable |
| `http://loinc.org` | `41825-1` | Humerus - left X-ray portable |
| `http://loinc.org` | `41826-9` | Elbow - left X-ray limited |
| `http://loinc.org` | `41827-7` | Elbow - left X-ray portable |
| `http://loinc.org` | `41828-5` | Wrist - left X-ray portable |
| `http://loinc.org` | `41829-3` | Hand - left X-ray portable |
| `http://loinc.org` | `41830-1` | Hand - left X-ray limited |
| `http://loinc.org` | `41831-9` | Ribs - left X-ray portable |
| `http://loinc.org` | `41832-7` | Ribs - left and Chest X-ray and PA chest |
| `http://loinc.org` | `41833-5` | Upper extremity artery - left US |
| `http://loinc.org` | `41834-3` | Lower extremity artery - left US |
| `http://loinc.org` | `41835-0` | Extremity veins - left US |
| `http://loinc.org` | `41836-8` | Bone Scan limited W In-111 tagged WBC IV |
| `http://loinc.org` | `41837-6` | SPECT whole body W Tc-99m Arcitumomab IV |
| `http://loinc.org` | `41838-4` | Prostate SPECT W In-111 Satumomab IV |
| `http://loinc.org` | `42007-5` | Mastoid - bilateral X-ray limited |
| `http://loinc.org` | `42008-3` | Humerus X-ray during surgery |
| `http://loinc.org` | `42009-1` | Chest X-ray 2 views and apical |
| `http://loinc.org` | `42010-9` | Ribs - right and Chest X-ray and PA chest |
| `http://loinc.org` | `42011-7` | Chest and Abdomen X-ray AP and PA chest |
| `http://loinc.org` | `42012-5` | Gastrointestine upper Fluoroscopy W water soluble contrast PO |
| `http://loinc.org` | `42014-1` | Urinary Bladder and Urethra Fluoroscopy W contrast |
| `http://loinc.org` | `42017-4` | Fluoroscopy Guidance for replacement of percutaneous cholecystostomy in Abdomen |
| `http://loinc.org` | `42018-2` | Vein Fluoroscopic angiogram Percutaneous transluminal angioplasty of vessel W contrast IA |
| `http://loinc.org` | `42019-0` | Abdomen X-ray AP (upright and left lateral decubitus) |
| `http://loinc.org` | `42020-8` | CT Guidance for needle localization of Spine Lumbar |
| `http://loinc.org` | `42021-6` | CT Guidance for needle localization of Spine Cervical |
| `http://loinc.org` | `42132-1` | Breast US screening |
| `http://loinc.org` | `42133-9` | US Guidance for abscess drainage of Liver |
| `http://loinc.org` | `42134-7` | US Guidance for aspiration of Thyroid |
| `http://loinc.org` | `42135-4` | US Guidance for biopsy of Superficial bone |
| `http://loinc.org` | `42136-2` | CT Guidance for biopsy of Heart |
| `http://loinc.org` | `42137-0` | US Guidance for biopsy of Mediastinum |
| `http://loinc.org` | `42139-6` | US Guidance for percutaneous biopsy of Muscle |
| `http://loinc.org` | `42140-4` | US Guidance for placement of tube in Chest |
| `http://loinc.org` | `42141-2` | US Guidance for removal of catheter from Central vein-- Tunneled |
| `http://loinc.org` | `42143-8` | Uterus and Fallopian tubes US W saline intrauterine |
| `http://loinc.org` | `42144-6` | Extremity vein - right US |
| `http://loinc.org` | `42145-3` | Extremity vein - left US |
| `http://loinc.org` | `42146-1` | Carotid artery US.doppler |
| `http://loinc.org` | `42147-9` | Iliac graft US.doppler |
| `http://loinc.org` | `42148-7` | Heart US |
| `http://loinc.org` | `42149-5` | Carotid artery - left US limited |
| `http://loinc.org` | `42150-3` | Iliac graft US.doppler limited |
| `http://loinc.org` | `42151-1` | Carotid artery - right US limited |
| `http://loinc.org` | `42152-9` | Pelvis vessels US.doppler limited |
| `http://loinc.org` | `42153-7` | Extremity X-ray Single view |
| `http://loinc.org` | `42156-0` | Vessels Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `42157-8` | Extremity vessels Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `42158-6` | Adrenal gland Scan |
| `http://loinc.org` | `42159-4` | Sella turcica X-ray |
| `http://loinc.org` | `42160-2` | Shunt X-ray |
| `http://loinc.org` | `42161-0` | Heart Scan W dobutamine and W radionuclide IV |
| `http://loinc.org` | `42162-8` | Gastrointestine upper Fluoroscopy and AP W water soluble contrast PO |
| `http://loinc.org` | `42163-6` | Spine Lumbar X-ray and oblique |
| `http://loinc.org` | `42164-4` | Spine Cervical X-ray and oblique |
| `http://loinc.org` | `42165-1` | Ribs and Chest X-ray and PA chest |
| `http://loinc.org` | `42166-9` | Heart Scan 2 views at rest and W Tl-201 IV |
| `http://loinc.org` | `42167-7` | Pelvis and Hip - bilateral X-ray AP and lateral frog |
| `http://loinc.org` | `42168-5` | Breast - right FFD mammogram diagnostic |
| `http://loinc.org` | `42169-3` | Breast - left FFD mammogram diagnostic |
| `http://loinc.org` | `42170-1` | Scan for lymphoma |
| `http://loinc.org` | `42171-9` | Scan for tumor whole body |
| `http://loinc.org` | `42174-3` | Breast - bilateral FFD mammogram screening |
| `http://loinc.org` | `42175-0` | Scan whole body |
| `http://loinc.org` | `42227-9` | FDA package insert Drug abuse and dependence section |
| `http://loinc.org` | `42228-7` | FDA package insert Pregnancy section |
| `http://loinc.org` | `42229-5` | FDA package insert Structured patient labelling unclassified section |
| `http://loinc.org` | `42230-3` | FDA package insert Structured product laballing patient package insert section |
| `http://loinc.org` | `42231-1` | FDA package insert Structured product labelling medguide section |
| `http://loinc.org` | `42232-9` | FDA package insert Precautions section |
| `http://loinc.org` | `42260-0` | CT Guidance for biopsy of Unspecified body region-- W contrast IV |
| `http://loinc.org` | `42261-8` | Kidney - bilateral Scan flow |
| `http://loinc.org` | `42262-6` | Liver Scan flow |
| `http://loinc.org` | `42263-4` | Spleen Scan flow |
| `http://loinc.org` | `42265-9` | CT Guidance for biopsy of Superficial bone |
| `http://loinc.org` | `42266-7` | CT Guidance for needle biopsy of Superficial bone |
| `http://loinc.org` | `42267-5` | CT Guidance for needle biopsy of Lymph node |
| `http://loinc.org` | `42268-3` | Extremity CT W and WO contrast IV |
| `http://loinc.org` | `42269-1` | Chest and Abdomen X-ray |
| `http://loinc.org` | `42270-9` | Spine Cervical MRI W flexion and W extension |
| `http://loinc.org` | `42271-7` | Thyroid Scan and uptake W I-123 IV |
| `http://loinc.org` | `42272-5` | Chest X-ray PA and lateral |
| `http://loinc.org` | `42273-3` | Ankle - bilateral X-ray 6 views |
| `http://loinc.org` | `42274-1` | Abdomen and Pelvis CT W and WO contrast IV |
| `http://loinc.org` | `42275-8` | Chest and Abdomen CT W contrast IV |
| `http://loinc.org` | `42276-6` | Chest and Abdomen CT WO contrast |
| `http://loinc.org` | `42277-4` | Chest and Abdomen CT W and WO contrast IV |
| `http://loinc.org` | `42278-2` | Extremity CT WO contrast |
| `http://loinc.org` | `42279-0` | CT Guidance for biopsy of Kidney |
| `http://loinc.org` | `42280-8` | CT Guidance for abscess drainage of Appendix |
| `http://loinc.org` | `42281-6` | CT Guidance for abscess drainage of Chest |
| `http://loinc.org` | `42282-4` | CT Guidance for abscess drainage of Liver |
| `http://loinc.org` | `42283-2` | CT Guidance for drainage of Pancreas |
| `http://loinc.org` | `42284-0` | CT Guidance for abscess drainage of Pleural space |
| `http://loinc.org` | `42285-7` | CT Guidance for abscess drainage of Kidney |
| `http://loinc.org` | `42286-5` | CT Guidance for abscess drainage of Pelvis |
| `http://loinc.org` | `42287-3` | CT Guidance for drainage of Abdomen retroperitoneum |
| `http://loinc.org` | `42288-1` | CT Guidance for needle biopsy of Abdomen |
| `http://loinc.org` | `42289-9` | CT Guidance for needle biopsy of Kidney |
| `http://loinc.org` | `42290-7` | CT Guidance for needle biopsy of Pancreas |
| `http://loinc.org` | `42291-5` | Abdomen retroperitoneum CT WO contrast |
| `http://loinc.org` | `42292-3` | SPECT for tumor W Tl-201 IV |
| `http://loinc.org` | `42293-1` | Head vessels CT angiogram WO contrast |
| `http://loinc.org` | `42294-9` | Pelvis vessels CT angiogram W contrast IV |
| `http://loinc.org` | `42295-6` | Upper extremity vessels CT angiogram W contrast IV |
| `http://loinc.org` | `42296-4` | Mammogram Guidance for localization of Breast - left |
| `http://loinc.org` | `42297-2` | Mammogram Guidance for localization of Breast - right |
| `http://loinc.org` | `42298-0` | Unspecified body region MRI W and WO contrast IV |
| `http://loinc.org` | `42299-8` | Clavicle MRI W and WO contrast IV |
| `http://loinc.org` | `42300-4` | Thyroid MRI |
| `http://loinc.org` | `42301-2` | Uterus MRI |
| `http://loinc.org` | `42302-0` | Clavicle MRI WO contrast |
| `http://loinc.org` | `42303-8` | Orbit and Face MRI |
| `http://loinc.org` | `42304-6` | Head vessels and Neck vessels MRI angiogram |
| `http://loinc.org` | `42305-3` | Scan for tumor W Tl-201 IV |
| `http://loinc.org` | `42306-1` | Heart Scan gated and wall motion |
| `http://loinc.org` | `42308-7` | Scrotum and Testicle Scan flow |
| `http://loinc.org` | `42309-5` | Heart Scan at rest and W stress and W Tl-201 IV |
| `http://loinc.org` | `42310-3` | Kidney SPECT |
| `http://loinc.org` | `42311-1` | Orbit - left X-ray for foreign body |
| `http://loinc.org` | `42312-9` | Orbit - right X-ray for foreign body |
| `http://loinc.org` | `42313-7` | Ribs - left X-ray Single view |
| `http://loinc.org` | `42314-5` | Ribs - right X-ray Single view |
| `http://loinc.org` | `42333-5` | US Guidance for biopsy of Chest.pleura |
| `http://loinc.org` | `42334-3` | Fluoroscopy Guidance for injection of Mammary artery.internal - left |
| `http://loinc.org` | `42335-0` | Spine Cervical Fluoroscopy limited W contrast IT |
| `http://loinc.org` | `42377-2` | Brain CT W Xe-133 inhaled |
| `http://loinc.org` | `42378-0` | Spine Lumbar X-ray AP single view W left bending |
| `http://loinc.org` | `42379-8` | Spine Lumbar X-ray AP single view W right bending |
| `http://loinc.org` | `42380-6` | Ankle - left X-ray AP and lateral standing |
| `http://loinc.org` | `42381-4` | Ribs lower posterior - left X-ray |
| `http://loinc.org` | `42382-2` | Ankle - left X-ray lateral and Mortise and Broden W manual stress |
| `http://loinc.org` | `42383-0` | Gallbladder X-ray W double dose contrast PO |
| `http://loinc.org` | `42385-5` | Brain and Pituitary and Sella turcica MRI |
| `http://loinc.org` | `42386-3` | Brain MRI cine for CSF flow |
| `http://loinc.org` | `42387-1` | Unspecified body region MRI cine for CSF flow |
| `http://loinc.org` | `42388-9` | Prostate MRI W endorectal coil |
| `http://loinc.org` | `42389-7` | Pelvis MRI W endorectal coil |
| `http://loinc.org` | `42390-5` | Transvaginal MRI |
| `http://loinc.org` | `42391-3` | Brain and Pituitary and Sella turcica MRI W contrast IV |
| `http://loinc.org` | `42392-1` | Brain and Pituitary and Sella turcica MRI W and WO contrast IV |
| `http://loinc.org` | `42393-9` | Brain and Pituitary and Sella turcica MRI WO contrast |
| `http://loinc.org` | `42394-7` | Pulmonary system CT W Xe-133 inhaled |
| `http://loinc.org` | `42395-4` | Foot sesamoid bones - bilateral X-ray axial |
| `http://loinc.org` | `42396-2` | Foot sesamoid bones - left X-ray axial |
| `http://loinc.org` | `42397-0` | Chest X-ray frontal stereo |
| `http://loinc.org` | `42398-8` | Foot X-ray oblique and (AP and lateral) standing |
| `http://loinc.org` | `42399-6` | Foot sesamoid bones X-ray |
| `http://loinc.org` | `42400-2` | Foot sesamoid bones - bilateral X-ray |
| `http://loinc.org` | `42401-0` | Spine Lumbar X-ray (AP W R-bending and W L-bending and WO bending) and Lateral |
| `http://loinc.org` | `42402-8` | Unspecified body region X-ray post mortem |
| `http://loinc.org` | `42403-6` | Spine Lumbar X-ray AP W right bending and W left bending |
| `http://loinc.org` | `42404-4` | Hip - left X-ray AP and lateral and measurement |
| `http://loinc.org` | `42405-1` | Knee X-ray (AP^standing) and (lateral^W hyperextension) |
| `http://loinc.org` | `42406-9` | Spine Lumbar X-ray AP W and WO left bending |
| `http://loinc.org` | `42407-7` | Spine Lumbar X-ray AP W and WO right bending |
| `http://loinc.org` | `42408-5` | Spine Lumbar X-ray AP W right bending and W left bending and WO bending |
| `http://loinc.org` | `42409-3` | Foot sesamoid bones X-ray AP and lateral |
| `http://loinc.org` | `42410-1` | Spine Lumbar X-ray AP and lateral and oblique and spot standing |
| `http://loinc.org` | `42411-9` | Spine Lumbar X-ray (AP^W R-bending and W L-bending) and (lateral^W flexion and W extension) |
| `http://loinc.org` | `42412-7` | Shoulder - left X-ray 90 degree abduction |
| `http://loinc.org` | `42413-5` | Spine Lumbar X-ray W right bending and W left bending |
| `http://loinc.org` | `42414-3` | Chest X-ray right oblique and left oblique W nipple markers |
| `http://loinc.org` | `42415-0` | Breast - bilateral Mammogram Post Wire Placement |
| `http://loinc.org` | `42416-8` | Breast - left Mammogram Post Wire Placement |
| `http://loinc.org` | `42417-6` | Ankle - bilateral X-ray AP and lateral and oblique W manual stress |
| `http://loinc.org` | `42418-4` | Ankle - left X-ray AP and lateral and oblique W manual stress |
| `http://loinc.org` | `42419-2` | Wrist - bilateral X-ray Single view |
| `http://loinc.org` | `42420-0` | Pelvis X-ray AP single view standing |
| `http://loinc.org` | `42421-8` | Fluoroscopy Guidance for percutaneous drainage of abscess of Unspecified body region |
| `http://loinc.org` | `42422-6` | Fluoroscopy Guidance for percutaneous drainage of abscess of Breast |
| `http://loinc.org` | `42423-4` | Fluoroscopy Guidance for percutaneous drainage of abscess of Chest |
| `http://loinc.org` | `42424-2` | Spine Thoracic and Lumbar X-ray scoliosis AP and lateral sitting |
| `http://loinc.org` | `42425-9` | Spine Thoracic and Lumbar X-ray scoliosis AP standing and W right bending and W left bending and WO bending |
| `http://loinc.org` | `42426-7` | Spine Thoracic and Lumbar X-ray scoliosis AP sitting |
| `http://loinc.org` | `42427-5` | Spine Thoracic and Lumbar X-ray scoliosis lateral sitting |
| `http://loinc.org` | `42428-3` | Spine Thoracic and Lumbar X-ray scoliosis AP standing and in brace |
| `http://loinc.org` | `42429-1` | Spine Thoracic and Lumbar X-ray scoliosis AP standing and W right bending |
| `http://loinc.org` | `42430-9` | Knee - right X-ray 2 views and (views standing) |
| `http://loinc.org` | `42431-7` | Knee - right X-ray 30 degree standing |
| `http://loinc.org` | `42432-5` | Knee - right X-ray Sunrise and (views standing) |
| `http://loinc.org` | `42433-3` | Mammogram Guidance.stereotactic for core needle biopsy of Breast - right |
| `http://loinc.org` | `42434-1` | Foot sesamoid bones - right X-ray |
| `http://loinc.org` | `42435-8` | Sella turcica X-ray 2 views |
| `http://loinc.org` | `42436-6` | Sella turcica X-ray lateral and Towne |
| `http://loinc.org` | `42437-4` | Sella turcica X-ray tomograph |
| `http://loinc.org` | `42438-2` | Neck X-ray AP and lateral |
| `http://loinc.org` | `42439-0` | Neck X-ray AP single view |
| `http://loinc.org` | `42441-6` | Neck X-ray magnification |
| `http://loinc.org` | `42442-4` | Spine X-ray lateral standing |
| `http://loinc.org` | `42443-2` | Spine Thoracic X-ray 3 views standing |
| `http://loinc.org` | `42444-0` | Spine Thoracic X-ray AP W right bending and W left bending and WO bending |
| `http://loinc.org` | `42445-7` | Spine Thoracic X-ray AP W left bending and WO bending |
| `http://loinc.org` | `42446-5` | Spine Thoracic X-ray AP W right bending and WO bending |
| `http://loinc.org` | `42447-3` | US Guidance for aspiration of cyst of Thyroid |
| `http://loinc.org` | `42448-1` | US Guidance for excisional biopsy of Breast |
| `http://loinc.org` | `42449-9` | US Guidance for biopsy of Breast - left |
| `http://loinc.org` | `42450-7` | US Guidance for aspiration of cyst of Breast - left |
| `http://loinc.org` | `42455-6` | Pelvis US transabdominal and transvaginal |
| `http://loinc.org` | `42456-4` | US Guidance for placement of needle wire in Breast |
| `http://loinc.org` | `42457-2` | US Guidance for biopsy of Breast - right |
| `http://loinc.org` | `42458-0` | US Guidance for aspiration of cyst of Breast - right |
| `http://loinc.org` | `42459-8` | Gastrointestine upper Fluoroscopy W contrast PO |
| `http://loinc.org` | `42460-6` | Submandibular gland - left Fluoroscopy W contrast intra salivary duct |
| `http://loinc.org` | `42461-4` | Lower extremity vessel graft - left US.doppler |
| `http://loinc.org` | `42462-2` | Lower extremity vessel graft - right US.doppler |
| `http://loinc.org` | `42463-0` | US Guidance for biopsy of Endomyocardium |
| `http://loinc.org` | `42468-9` | Surgical specimen US |
| `http://loinc.org` | `42469-7` | Gastrointestine upper and Small bowel and Gallbladder Fluoroscopy W contrast PO |
| `http://loinc.org` | `42470-5` | Gastrointestine upper and Gallbladder Fluoroscopy W contrast PO |
| `http://loinc.org` | `42471-3` | Pelvis X-ray stereo |
| `http://loinc.org` | `42472-1` | Spine Thoracic and Lumbar X-ray scoliosis AP in traction |
| `http://loinc.org` | `42473-9` | Sinuses X-ray Waters stereo |
| `http://loinc.org` | `42474-7` | Skull X-ray stereo |
| `http://loinc.org` | `42475-4` | Upper extremity vessel graft - left US.doppler |
| `http://loinc.org` | `42476-2` | Upper extremity vessel graft - right US.doppler |
| `http://loinc.org` | `42477-0` | Kidney vessels transplant US.doppler |
| `http://loinc.org` | `42478-8` | US Guidance for drainage of cyst of Kidney |
| `http://loinc.org` | `42566-0` | Contributing Factor communication/Documentation MERSTH |
| `http://loinc.org` | `42680-9` | Breast Mammogram XCCL |
| `http://loinc.org` | `42681-7` | Colon Fluoroscopy W gastrografin PR |
| `http://loinc.org` | `42683-3` | Gastrointestine upper Fluoroscopy W barium contrast PO |
| `http://loinc.org` | `42684-1` | Gastrointestine upper Fluoroscopy W gastrografin PO |
| `http://loinc.org` | `42685-8` | Pelvis and Hip - left X-ray 2 views |
| `http://loinc.org` | `42686-6` | Pelvis and Hip - right X-ray 2 views |
| `http://loinc.org` | `42687-4` | Ribs - bilateral X-ray 2 views |
| `http://loinc.org` | `42688-2` | CT Guidance for anesthetic block injection of Spine |
| `http://loinc.org` | `42689-0` | Spine X-ray oblique single view |
| `http://loinc.org` | `42690-8` | Spine X-ray W flexion and W extension |
| `http://loinc.org` | `42691-6` | Spine Cervical X-ray 6 views |
| `http://loinc.org` | `42692-4` | Spine Thoracic and Lumbar X-ray |
| `http://loinc.org` | `42693-2` | Urinary Bladder and Urethra MRI cine |
| `http://loinc.org` | `42694-0` | Clavicle MRI W contrast IV |
| `http://loinc.org` | `42695-7` | Lower leg - bilateral MRI W contrast IV |
| `http://loinc.org` | `42696-5` | Lower leg - bilateral MRI |
| `http://loinc.org` | `42697-3` | Lower leg - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `42698-1` | Spine Cervical and Thoracic and Lumbar MRI |
| `http://loinc.org` | `42699-9` | Chest and Abdomen X-ray Single view |
| `http://loinc.org` | `42700-5` | Bone Scan W Tc-99m tagged WBC IV |
| `http://loinc.org` | `42701-3` | CT Guidance for localization of placenta of Uterus |
| `http://loinc.org` | `42702-1` | Unspecified body region Fluoroscopy Greater than 1 hour |
| `http://loinc.org` | `42703-9` | Unspecified body region Fluoroscopy Less than 1 hour |
| `http://loinc.org` | `42705-4` | US Guidance for abscess drainage of Appendix |
| `http://loinc.org` | `42706-2` | US Guidance for injection of Pleural space |
| `http://loinc.org` | `42707-0` | Heart US limited |
| `http://loinc.org` | `42708-8` | Scan W In-111 tiuxetan IV |
| `http://loinc.org` | `42709-6` | Liver Scan blood pool |
| `http://loinc.org` | `42710-4` | Spine Cervical X-ray limited |
| `http://loinc.org` | `42711-2` | Scan whole body W In-111 tagged WBC IV |
| `http://loinc.org` | `42776-5` | AV shunt Scan |
| `http://loinc.org` | `42796-3` | Clinical trial protocol Trial name |
| `http://loinc.org` | `42811-0` | Wrist - right X-ray scaphoid single view |
| `http://loinc.org` | `42812-8` | Wrist X-ray scaphoid single view |
| `http://loinc.org` | `42813-6` | Wrist - bilateral X-ray scaphoid single view |
| `http://loinc.org` | `42814-4` | Wrist - left X-ray scaphoid single view |
| `http://loinc.org` | `42855-7` | 11-Deoxycorticosterone [Mass/volume] in Urine |
| `http://loinc.org` | `43444-9` | CT Guidance for percutaneous drainage of abscess of Cavity |
| `http://loinc.org` | `43445-6` | Pulmonary system CT |
| `http://loinc.org` | `43446-4` | CT for tumor whole body |
| `http://loinc.org` | `43447-2` | Mammogram Guidance for needle biopsy of Breast - right |
| `http://loinc.org` | `43448-0` | Liver MRI W and WO ferumoxides IV |
| `http://loinc.org` | `43449-8` | Ankle - right MRI dynamic W contrast IV |
| `http://loinc.org` | `43450-6` | Elbow - left MRI dynamic W contrast IV |
| `http://loinc.org` | `43451-4` | Elbow - right MRI dynamic W contrast IV |
| `http://loinc.org` | `43452-2` | Knee - left MRI dynamic W contrast IV |
| `http://loinc.org` | `43453-0` | Knee - right MRI dynamic W contrast IV |
| `http://loinc.org` | `43454-8` | Pulmonary system MRI |
| `http://loinc.org` | `43455-5` | Oropharynx MRI |
| `http://loinc.org` | `43456-3` | Spine Cervical and Spine Thoracic MRI W and WO contrast IV |
| `http://loinc.org` | `43457-1` | Spine Cervical and Spine Thoracic MRI |
| `http://loinc.org` | `43458-9` | Orbit vessels MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `43459-7` | Brain Scan during electroconvulsive shock treatment |
| `http://loinc.org` | `43461-3` | Kidney - bilateral Scan W furosemide and W radionuclide IV |
| `http://loinc.org` | `43462-1` | US Guidance for needle biopsy of Breast - left |
| `http://loinc.org` | `43463-9` | Chest and Abdomen X-ray AP (supine and upright) and PA chest |
| `http://loinc.org` | `43464-7` | Ribs - bilateral and Chest X-ray lateral and PA chest |
| `http://loinc.org` | `43466-2` | Chest X-ray AP right lateral-decubitus |
| `http://loinc.org` | `43467-0` | Chest X-ray 2 views and right oblique and left oblique |
| `http://loinc.org` | `43468-8` | Unspecified body region X-ray |
| `http://loinc.org` | `43469-6` | Unspecified body region X-ray of foreign body |
| `http://loinc.org` | `43470-4` | Skull X-ray LE 3 views |
| `http://loinc.org` | `43471-2` | Unspecified body region Fluoroscopy 2 hour |
| `http://loinc.org` | `43472-0` | Unspecified body region Fluoroscopy 90 minutes |
| `http://loinc.org` | `43473-8` | Fluoroscopy Guidance for endoscopy of Biliary ducts and Pancreatic duct-- 2 hours post contrast retrograde |
| `http://loinc.org` | `43474-6` | Fluoroscopy Guidance for endoscopy of Biliary ducts and Pancreatic duct-- 15 minutes post contrast retrograde |
| `http://loinc.org` | `43475-3` | Fluoroscopy Guidance for endoscopy of Biliary ducts and Pancreatic duct-- 30 minutes post contrast retrograde |
| `http://loinc.org` | `43476-1` | Fluoroscopy Guidance for endoscopy of Biliary ducts and Pancreatic duct-- 45 minutes post contrast retrograde |
| `http://loinc.org` | `43477-9` | Fluoroscopy Guidance for endoscopy of Biliary ducts and Pancreatic duct-- 1 hour post contrast retrograde |
| `http://loinc.org` | `43478-7` | Fluoroscopy Guidance for endoscopy of Biliary ducts and Pancreatic duct-- 1.5 hours post contrast retrograde |
| `http://loinc.org` | `43479-5` | Aorta abdominal Fluoroscopic angiogram runoff W contrast IA |
| `http://loinc.org` | `43480-3` | Joint X-ray lateral W manual stress |
| `http://loinc.org` | `43481-1` | Joint X-ray W flexion and W extension |
| `http://loinc.org` | `43482-9` | Knee - right X-ray GE 3 views |
| `http://loinc.org` | `43483-7` | Foot - right X-ray 3 or 4 views |
| `http://loinc.org` | `43485-2` | Kidney X-ray during surgery W contrast retrograde |
| `http://loinc.org` | `43486-0` | Sinuses X-ray GE 3 views |
| `http://loinc.org` | `43487-8` | US Guidance for placement of radiation therapy fields in Unspecified body region |
| `http://loinc.org` | `43488-6` | Thumb - left X-ray GE 3 views |
| `http://loinc.org` | `43489-4` | Finger second - left X-ray GE 3 views |
| `http://loinc.org` | `43490-2` | Finger third - left X-ray GE 3 views |
| `http://loinc.org` | `43491-0` | Finger fourth - left X-ray GE 3 views |
| `http://loinc.org` | `43492-8` | Finger fifth - left X-ray GE 3 views |
| `http://loinc.org` | `43493-6` | Thumb - right X-ray GE 3 views |
| `http://loinc.org` | `43494-4` | Finger second - right X-ray GE 3 views |
| `http://loinc.org` | `43495-1` | Finger third - right X-ray GE 3 views |
| `http://loinc.org` | `43496-9` | Finger fourth - right X-ray GE 3 views |
| `http://loinc.org` | `43497-7` | Finger fifth - right X-ray GE 3 views |
| `http://loinc.org` | `43498-5` | Knee - left X-ray GE 3 views |
| `http://loinc.org` | `43499-3` | Foot - left X-ray 3 or 4 views |
| `http://loinc.org` | `43500-8` | Vessel Scan flow |
| `http://loinc.org` | `43501-6` | Vessel Scan static |
| `http://loinc.org` | `43502-4` | CT Guidance for abscess drainage of Subphrenic space |
| `http://loinc.org` | `43503-2` | Aorta and Lower extremity vessels CT angiogram W contrast IV |
| `http://loinc.org` | `43504-0` | Axilla - left MRI W contrast IV |
| `http://loinc.org` | `43505-7` | Axilla - right MRI W contrast IV |
| `http://loinc.org` | `43506-5` | Ovary - bilateral MRI |
| `http://loinc.org` | `43507-3` | Thymus gland MRI |
| `http://loinc.org` | `43508-1` | Axilla - left MRI |
| `http://loinc.org` | `43509-9` | Axilla - left MRI W and WO contrast IV |
| `http://loinc.org` | `43510-7` | Axilla - right MRI |
| `http://loinc.org` | `43511-5` | Axilla - right MRI W and WO contrast IV |
| `http://loinc.org` | `43512-3` | Lower leg vessels - bilateral MRI angiogram W contrast IV |
| `http://loinc.org` | `43513-1` | Lower leg vessels - left MRI angiogram |
| `http://loinc.org` | `43514-9` | Thigh vessels - left MRI angiogram WO contrast |
| `http://loinc.org` | `43515-6` | Thigh vessels - right MRI angiogram WO contrast |
| `http://loinc.org` | `43516-4` | Wrist vessels - left MRI angiogram WO contrast |
| `http://loinc.org` | `43517-2` | Wrist vessels - right MRI angiogram WO contrast |
| `http://loinc.org` | `43518-0` | Bones X-ray survey |
| `http://loinc.org` | `43519-8` | Bones X-ray survey limited |
| `http://loinc.org` | `43521-4` | Mandible X-ray 1 or 2 views |
| `http://loinc.org` | `43522-2` | Pelvis X-ray 1 or 2 views |
| `http://loinc.org` | `43523-0` | Sinuses X-ray 1 or 2 views |
| `http://loinc.org` | `43524-8` | Skull X-ray GE 5 views |
| `http://loinc.org` | `43525-5` | Unspecified body region CT WO contrast |
| `http://loinc.org` | `43526-3` | Unspecified body region SPECT |
| `http://loinc.org` | `43527-1` | Unspecified body region CT dynamic W contrast IV |
| `http://loinc.org` | `43528-9` | Breast - unilateral MRI W and WO contrast IV |
| `http://loinc.org` | `43529-7` | Orbit + Facial bones X-ray |
| `http://loinc.org` | `43530-5` | Orbit and Face and Neck MRI |
| `http://loinc.org` | `43532-1` | Chest and Abdomen X-ray upright and PA chest |
| `http://loinc.org` | `43533-9` | Mandible - right X-ray |
| `http://loinc.org` | `43534-7` | Mandible - left X-ray 4 views |
| `http://loinc.org` | `43535-4` | Mandible - right X-ray 4 views |
| `http://loinc.org` | `43536-2` | Spine Lumbar Fluoroscopy video |
| `http://loinc.org` | `43537-0` | Fluoroscopy Guidance for drainage of Unspecified body region |
| `http://loinc.org` | `43538-8` | Spine Cervical Fluoroscopy video |
| `http://loinc.org` | `43539-6` | Spine Cervical X-ray 2 or 3 views |
| `http://loinc.org` | `43543-8` | Pelvis X-ray GE 3 views |
| `http://loinc.org` | `43550-3` | Brain Scan static and flow |
| `http://loinc.org` | `43552-9` | Carotid artery - unilateral US |
| `http://loinc.org` | `43554-5` | vessels - left Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `43555-2` | Ankle - left MRI dynamic W contrast IV |
| `http://loinc.org` | `43556-0` | Lower leg vessels - right MRI angiogram |
| `http://loinc.org` | `43557-8` | Liver and Biliary ducts and Gallbladder Scan |
| `http://loinc.org` | `43558-6` | Fluoroscopy Guidance for change of dialysis catheter in Unspecified body region-- W contrast IV |
| `http://loinc.org` | `43559-4` | Urinary Bladder and Urethra Fluoroscopy W contrast intra bladder during voiding |
| `http://loinc.org` | `43561-0` | Chest and Abdomen X-ray AP upright and AP chest |
| `http://loinc.org` | `43562-8` | Skeletal system.axial Scan Bone density |
| `http://loinc.org` | `43563-6` | Skeletal system.peripheral Scan Bone density |
| `http://loinc.org` | `43564-4` | US Guidance for biopsy of Superficial muscle |
| `http://loinc.org` | `43565-1` | US Guidance for biopsy of Deep bone |
| `http://loinc.org` | `43566-9` | Hip and Thigh US |
| `http://loinc.org` | `43567-7` | CT Guidance for biopsy of Deep bone |
| `http://loinc.org` | `43568-5` | CT Guidance for needle biopsy of Deep bone |
| `http://loinc.org` | `43569-3` | Spine Thoracic and Lumbar X-ray scoliosis AP upright and supine |
| `http://loinc.org` | `43570-1` | Hand X-ray portable |
| `http://loinc.org` | `43571-9` | CT Guidance for needle biopsy of Soft bone |
| `http://loinc.org` | `43572-7` | Abdominal vessels US.doppler limited |
| `http://loinc.org` | `43574-3` | Upper Gastrointestine and Small bowel Fluoroscopy W barium contrast PO |
| `http://loinc.org` | `43641-0` | Foot sesamoid bones - left X-ray |
| `http://loinc.org` | `43642-8` | Brain Scan flow W Tc-99m DTPA IV |
| `http://loinc.org` | `43643-6` | Brain Scan flow W Tc-99m glucoheptonate IV |
| `http://loinc.org` | `43644-4` | Brain Scan flow limited |
| `http://loinc.org` | `43645-1` | Heart Scan for infarct qualitative |
| `http://loinc.org` | `43646-9` | Heart Scan for infarct qualitative and quantitative |
| `http://loinc.org` | `43647-7` | Heart Scan for infarct quantitative |
| `http://loinc.org` | `43648-5` | Scan for endocrine tumor multiple areas W I-131 MIBG IV |
| `http://loinc.org` | `43649-3` | Scan for endocrine tumor multiple areas W In-111 pentetreotide IV |
| `http://loinc.org` | `43650-1` | Liver and Biliary ducts and Gallbladder Scan W cholecystokinin and W radionuclide IV |
| `http://loinc.org` | `43651-9` | Liver and Biliary ducts and Gallbladder Scan W sincalide and W radionuclide IV |
| `http://loinc.org` | `43652-7` | Liver and Spleen SPECT flow |
| `http://loinc.org` | `43653-5` | Liver and Spleen Scan flow |
| `http://loinc.org` | `43654-3` | Liver Scan flow W Tc-99m tagged RBC IV |
| `http://loinc.org` | `43655-0` | Liver SPECT flow |
| `http://loinc.org` | `43656-8` | Lung Scan perfusion quantitative |
| `http://loinc.org` | `43657-6` | Lung Scan quantitative |
| `http://loinc.org` | `43658-4` | Heart Scan perfusion quantitative |
| `http://loinc.org` | `43659-2` | Heart SPECT perfusion qualitative at rest and W radionuclide IV |
| `http://loinc.org` | `43660-0` | Heart Scan perfusion qualitative at rest and W radionuclide IV |
| `http://loinc.org` | `43661-8` | Heart Scan perfusion quantitative at rest and W radionuclide IV |
| `http://loinc.org` | `43662-6` | Renal vessels SPECT flow W Tc-99m glucoheptonate IV |
| `http://loinc.org` | `43663-4` | Renal vessels Scan flow W Tc-99m glucoheptonate IV |
| `http://loinc.org` | `43664-2` | Renal vessels Scan flow W Tc-99m DTPA IV |
| `http://loinc.org` | `43665-9` | Renal vessels Scan flow W Tc-99m Mertiatide IV |
| `http://loinc.org` | `43666-7` | Kidney - bilateral and Renal vessels Scan flow W Tc-99m glucoheptonate IV |
| `http://loinc.org` | `43667-5` | Kidney - bilateral and Renal vessels Scan W Tc-99m DTPA IV |
| `http://loinc.org` | `43669-1` | Renal vessels Scan |
| `http://loinc.org` | `43670-9` | Spleen SPECT flow |
| `http://loinc.org` | `43671-7` | Thyroid Scan spot |
| `http://loinc.org` | `43672-5` | Thyroid Scan and uptake |
| `http://loinc.org` | `43673-3` | Thyroid SPECT flow |
| `http://loinc.org` | `43678-2` | FDA package insert Dosage forms and strengths section |
| `http://loinc.org` | `43679-0` | FDA package insert Mechanism of action section |
| `http://loinc.org` | `43680-8` | FDA package insert Nonclinical toxicology section |
| `http://loinc.org` | `43681-6` | FDA package insert Pharmacodynamics section |
| `http://loinc.org` | `43682-4` | FDA package insert Pharmacokinetics section |
| `http://loinc.org` | `43683-2` | FDA package insert Recent major changes section |
| `http://loinc.org` | `43684-0` | FDA package insert Use in specific populations section |
| `http://loinc.org` | `43685-7` | FDA package insert Warnings and precautions section |
| `http://loinc.org` | `43756-6` | US Guidance for aspiration of Breast |
| `http://loinc.org` | `43757-4` | CT Guidance for fine needle aspiration of Kidney |
| `http://loinc.org` | `43758-2` | US Guidance for localization of Breast - left |
| `http://loinc.org` | `43759-0` | US Guidance for localization of Breast - bilateral |
| `http://loinc.org` | `43760-8` | US Guidance for localization of Breast - right |
| `http://loinc.org` | `43761-6` | Fluoroscopic angiogram Guidance for thrombectomy of Vein - bilateral-- W contrast IV |
| `http://loinc.org` | `43762-4` | Fluoroscopic angiogram Guidance for thrombectomy of Vein - left-- W contrast IV |
| `http://loinc.org` | `43763-2` | Fluoroscopic angiogram Guidance for thrombectomy of Vein-- W contrast IV |
| `http://loinc.org` | `43764-0` | Fluoroscopic angiogram Guidance for thrombectomy of Vein - right-- W contrast IV |
| `http://loinc.org` | `43765-7` | Carotid artery - bilateral US.doppler |
| `http://loinc.org` | `43766-5` | Kidney - bilateral CT W contrast IV |
| `http://loinc.org` | `43767-3` | Kidney - bilateral CT |
| `http://loinc.org` | `43768-1` | Kidney CT W and WO contrast IV |
| `http://loinc.org` | `43769-9` | Brain and Internal auditory canal MRI W and WO contrast IV |
| `http://loinc.org` | `43770-7` | Kidney CT WO contrast |
| `http://loinc.org` | `43771-5` | Extremity vessels US.doppler |
| `http://loinc.org` | `43772-3` | Brain and Internal auditory canal MRI |
| `http://loinc.org` | `43773-1` | Kidney MRI WO contrast |
| `http://loinc.org` | `43774-9` | Kidney - bilateral US |
| `http://loinc.org` | `43775-6` | Kidney MRI W and WO contrast IV |
| `http://loinc.org` | `43776-4` | Iliac artery US.doppler limited |
| `http://loinc.org` | `43777-2` | Heart Scan perfusion at rest and W adenosine and W Tl-201 IV |
| `http://loinc.org` | `43778-0` | Chest X-ray AP supine portable |
| `http://loinc.org` | `43779-8` | Knee - left X-ray Sunrise |
| `http://loinc.org` | `43780-6` | Knee X-ray Sunrise |
| `http://loinc.org` | `43781-4` | Spine Cervicothoracic Junction X-ray |
| `http://loinc.org` | `43782-2` | Iliac artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `43783-0` | Renal vein Fluoroscopic angiogram W contrast IV and W renin sampling |
| `http://loinc.org` | `43784-8` | Spine Cervical and Thoracic and Lumbar X-ray 2 views |
| `http://loinc.org` | `43785-5` | Spine Cervicothoracic Junction X-ray AP and lateral |
| `http://loinc.org` | `43787-1` | Skull and Facial bones and Mandible X-ray for dental measurement |
| `http://loinc.org` | `43788-9` | Tube Fluoroscopy for patency W contrast via tube |
| `http://loinc.org` | `43789-7` | Liver and Biliary ducts and Gallbladder Scan for patency W Tc-99m IV |
| `http://loinc.org` | `43790-5` | Shoulder - right X-ray Grashey and Y |
| `http://loinc.org` | `43791-3` | Spine Lumbar X-ray oblique |
| `http://loinc.org` | `43792-1` | Tibioperoneal arteries - right Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `43793-9` | Tibioperoneal arteries Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `43794-7` | Tibioperoneal arteries - bilateral Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `43795-4` | Tibioperoneal arteries - left Fluoroscopic angiogram Angioplasty W contrast IA |
| `http://loinc.org` | `43796-2` | Wrist - bilateral X-ray tunnel.carpal |
| `http://loinc.org` | `43797-0` | US Guidance for biopsy of Superficial lymph node |
| `http://loinc.org` | `44101-4` | CT Guidance for ablation of tissue of Liver |
| `http://loinc.org` | `44102-2` | CT Guidance for procedure of Joint space |
| `http://loinc.org` | `44103-0` | CT Guidance for fine needle aspiration of Lymph node |
| `http://loinc.org` | `44104-8` | CT Guidance for fine needle aspiration of Mediastinum |
| `http://loinc.org` | `44105-5` | CT Guidance for fine needle aspiration of Muscle |
| `http://loinc.org` | `44106-3` | CT Guidance for fine needle aspiration of Prostate |
| `http://loinc.org` | `44107-1` | CT Guidance for fine needle aspiration of Abdomen retroperitoneum |
| `http://loinc.org` | `44108-9` | CT Guidance for fine needle aspiration of Adrenal gland |
| `http://loinc.org` | `44109-7` | CT Guidance for biopsy of Deep muscle |
| `http://loinc.org` | `44110-5` | CT Guidance for needle localization of Breast |
| `http://loinc.org` | `44111-3` | Skull.base CT W and WO contrast IV |
| `http://loinc.org` | `44112-1` | Skull.base CT WO contrast |
| `http://loinc.org` | `44113-9` | Spine Thoracic CT W and WO contrast IT |
| `http://loinc.org` | `44114-7` | Spine Lumbar CT W and WO contrast IT |
| `http://loinc.org` | `44115-4` | Abdomen and Pelvis CT |
| `http://loinc.org` | `44116-2` | Mandible CT limited |
| `http://loinc.org` | `44117-0` | CT Guidance for biopsy of Abdomen retroperitoneum |
| `http://loinc.org` | `44118-8` | CT Guidance for needle localization of Breast-- W and WO contrast IV |
| `http://loinc.org` | `44119-6` | Breast - bilateral CT WO contrast |
| `http://loinc.org` | `44120-4` | Colon CT |
| `http://loinc.org` | `44121-2` | Mammogram Guidance for percutaneous needle biopsy of Breast |
| `http://loinc.org` | `44122-0` | MRI Guidance.stereotactic for localization in Brain-- W and WO contrast IV |
| `http://loinc.org` | `44123-8` | Biliary ducts and Pancreatic duct MRI WO contrast |
| `http://loinc.org` | `44124-6` | Adrenal gland MRI W contrast IV |
| `http://loinc.org` | `44125-3` | Biliary ducts and Pancreatic duct MRI W contrast IV |
| `http://loinc.org` | `44126-1` | Heart MRI cine for blood flow velocity mapping W contrast IV |
| `http://loinc.org` | `44127-9` | Heart MRI limited cine for function |
| `http://loinc.org` | `44128-7` | Lower extremity vessels MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `44129-5` | Lower extremity vessels MRI angiogram WO contrast |
| `http://loinc.org` | `44130-3` | Aortic arch MRI angiogram WO contrast |
| `http://loinc.org` | `44131-1` | Aorta MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `44132-9` | Aorta MRI angiogram WO contrast |
| `http://loinc.org` | `44133-7` | Renal vessels MRI angiogram WO contrast |
| `http://loinc.org` | `44134-5` | Renal vessels MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `44135-2` | Lower extremity vessels - bilateral MRI angiogram W contrast IV |
| `http://loinc.org` | `44136-0` | Unspecified body region PET |
| `http://loinc.org` | `44137-8` | Heart PET |
| `http://loinc.org` | `44138-6` | Brain PET |
| `http://loinc.org` | `44139-4` | PET whole body |
| `http://loinc.org` | `44140-2` | Abdomen and Pelvis Scan for tumor |
| `http://loinc.org` | `44141-0` | Liver and Spleen Scan W Tc-99m MAA IV |
| `http://loinc.org` | `44142-8` | Bone Scan W Tc-99m medronate IV |
| `http://loinc.org` | `44143-6` | Heart Scan W Tc-99m tagged RBC IV |
| `http://loinc.org` | `44144-4` | Liver Scan W Xe-133 inhaled |
| `http://loinc.org` | `44145-1` | Parathyroid Scan W Tc-99m Sestamibi IV |
| `http://loinc.org` | `44146-9` | Bone marrow Scan W Tc-99m SC IV |
| `http://loinc.org` | `44147-7` | Thyroid Scan and uptake W Tc-99m pertechnetate IV |
| `http://loinc.org` | `44148-5` | Brain Scan flow W Tc-99m bicisate IV |
| `http://loinc.org` | `44149-3` | Peritoneovenous shunt Scan for patency W Tc-99m MAA inj |
| `http://loinc.org` | `44150-1` | Brain Scan static W Tc-99m bicisate IV |
| `http://loinc.org` | `44151-9` | Heart SPECT W Tc-99m Sestamibi IV |
| `http://loinc.org` | `44152-7` | Brain SPECT W Tc-99m bicisate IV |
| `http://loinc.org` | `44153-5` | Kidney SPECT W Tc-99m glucoheptonate IV |
| `http://loinc.org` | `44154-3` | Heart SPECT W dipyridamole and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `44155-0` | US Guidance for ablation of tissue of Liver |
| `http://loinc.org` | `44156-8` | US Guidance for ablation of tissue of Kidney |
| `http://loinc.org` | `44157-6` | US Guidance for fine needle aspiration of Pancreas |
| `http://loinc.org` | `44158-4` | US Guidance for fine needle aspiration of Liver |
| `http://loinc.org` | `44159-2` | US Guidance for fine needle aspiration of Kidney |
| `http://loinc.org` | `44160-0` | US Guidance for fine needle aspiration of Breast |
| `http://loinc.org` | `44161-8` | US Guidance for biopsy of Lung |
| `http://loinc.org` | `44162-6` | US Guidance for biopsy of Abdomen retroperitoneum |
| `http://loinc.org` | `44163-4` | Thoracic outlet US |
| `http://loinc.org` | `44164-2` | Head and Neck US |
| `http://loinc.org` | `44165-9` | Unspecified body region US and 3D reconstruction |
| `http://loinc.org` | `44166-7` | US Guidance for abscess drainage of Subphrenic space |
| `http://loinc.org` | `44167-5` | US Guidance for abscess drainage of Kidney |
| `http://loinc.org` | `44168-3` | US Guidance for abscess drainage of Pelvis |
| `http://loinc.org` | `44169-1` | US Guidance for abscess drainage of Peritoneal space |
| `http://loinc.org` | `44170-9` | US Guidance for needle biopsy of Liver |
| `http://loinc.org` | `44171-7` | US Guidance for needle biopsy of Chest.pleura |
| `http://loinc.org` | `44172-5` | US Guidance for drainage of Pancreas |
| `http://loinc.org` | `44173-3` | Peripheral artery US limited |
| `http://loinc.org` | `44174-1` | Lower extremity vessels US.doppler |
| `http://loinc.org` | `44175-8` | Neck vessels US.doppler |
| `http://loinc.org` | `44176-6` | Hip X-ray Single view portable |
| `http://loinc.org` | `44177-4` | Lower extremity - bilateral X-ray AP single view standing |
| `http://loinc.org` | `44178-2` | Spine Lumbar X-ray oblique view and (views W right bending and W left bending) |
| `http://loinc.org` | `44179-0` | Sacrum and Coccyx X-ray 2 views |
| `http://loinc.org` | `44181-6` | Sacroiliac Joint X-ray 2 or 3 views |
| `http://loinc.org` | `44182-4` | Hand X-ray 2 views portable |
| `http://loinc.org` | `44183-2` | Radius and Ulna X-ray 2 views portable |
| `http://loinc.org` | `44184-0` | Elbow X-ray 2 views portable |
| `http://loinc.org` | `44185-7` | Femur X-ray AP and lateral portable |
| `http://loinc.org` | `44186-5` | Foot X-ray AP and lateral portable |
| `http://loinc.org` | `44187-3` | Spine Cervical X-ray AP and oblique and odontoid and lateral portable W flexion and W extension |
| `http://loinc.org` | `44188-1` | Foot X-ray GE 3 views |
| `http://loinc.org` | `44189-9` | Sacroiliac Joint X-ray GE 3 views |
| `http://loinc.org` | `44190-7` | Wrist X-ray GE 3 views |
| `http://loinc.org` | `44191-5` | Ribs and Chest X-ray GE 3 and PA Chest views |
| `http://loinc.org` | `44192-3` | Pelvis X-ray GE 3 Portable views |
| `http://loinc.org` | `44193-1` | Hand X-ray GE 3 Portable views |
| `http://loinc.org` | `44194-9` | Spine X-ray GE 4 views W right bending and W left bending |
| `http://loinc.org` | `44195-6` | Knee X-ray GE 5 views |
| `http://loinc.org` | `44196-4` | Spine Lumbar X-ray GE 5 views W right bending and W left bending |
| `http://loinc.org` | `44197-2` | Knee - bilateral X-ray GE 5 views standing |
| `http://loinc.org` | `44198-0` | Knee X-ray 1 or 2 views |
| `http://loinc.org` | `44199-8` | Facial bones X-ray 1 or 2 views |
| `http://loinc.org` | `44201-2` | Pelvis X-ray 1 or 2 views portable |
| `http://loinc.org` | `44202-0` | Knee X-ray 1 or 2 views portable |
| `http://loinc.org` | `44203-8` | Spine Cervical and Thoracic and Lumbar X-ray portable |
| `http://loinc.org` | `44204-6` | Fluoroscopy Guidance for percutaneous needle biopsy of Lung |
| `http://loinc.org` | `44205-3` | Lower extremity - bilateral X-ray standing |
| `http://loinc.org` | `44206-1` | Spine Thoracic and Lumbar X-ray scoliosis single view |
| `http://loinc.org` | `44208-7` | Orbit X-ray for foreign body |
| `http://loinc.org` | `44209-5` | Sinuses X-ray limited |
| `http://loinc.org` | `44210-3` | Ankle X-ray GE 3 views |
| `http://loinc.org` | `44211-1` | Chest X-ray GE 4 views |
| `http://loinc.org` | `44212-9` | Spine Cervical X-ray GE 4 views |
| `http://loinc.org` | `44213-7` | Fluoroscopy Guidance for endoscopy of Pancreatic duct-- W contrast retrograde |
| `http://loinc.org` | `44214-5` | Fluoroscopy Guidance for endoscopy of Biliary ducts-- W contrast retrograde |
| `http://loinc.org` | `44215-2` | Fluoroscopy Guidance for fine needle aspiration of Unspecified body region |
| `http://loinc.org` | `44216-0` | Fluoroscopy Guidance for fine needle aspiration of Thyroid |
| `http://loinc.org` | `44217-8` | Fluoroscopy Guidance for fine needle aspiration of Kidney |
| `http://loinc.org` | `44218-6` | Fluoroscopy Guidance for fine needle aspiration of Pancreas |
| `http://loinc.org` | `44219-4` | Fluoroscopy Guidance for fine needle aspiration of Lymph node |
| `http://loinc.org` | `44220-2` | Fluoroscopy Guidance for fine needle aspiration of Liver |
| `http://loinc.org` | `44221-0` | Fluoroscopy Guidance for fine needle aspiration of Deep tissue |
| `http://loinc.org` | `44222-8` | Fluoroscopy Guidance for procedure of Joint space |
| `http://loinc.org` | `44223-6` | Fluoroscopy Guidance for percutaneous drainage of abscess of Ovary |
| `http://loinc.org` | `44224-4` | Fluoroscopy Guidance for placement of tube in Unspecified body region |
| `http://loinc.org` | `44225-1` | Fluoroscopy Guidance for needle biopsy of Liver-- W contrast IV |
| `http://loinc.org` | `44226-9` | Colon Fluoroscopy Reduction W views W barium contrast PR |
| `http://loinc.org` | `44227-7` | Colon Fluoroscopy W barium contrast PR |
| `http://loinc.org` | `44228-5` | CT Guidance for ablation of tissue of Kidney |
| `http://loinc.org` | `44229-3` | Bones CT |
| `http://loinc.org` | `44230-1` | Superior mesenteric vessels MRI angiogram WO contrast |
| `http://loinc.org` | `44231-9` | Superior mesenteric vessels MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `44232-7` | Kidney - bilateral Scan W and WO Tc-99m Mertiatide IV |
| `http://loinc.org` | `44233-5` | Kidney - bilateral Scan W and WO Tc-99m DTPA IV |
| `http://loinc.org` | `44234-3` | Kidney - bilateral Scan W Tc-99m glucoheptonate IV |
| `http://loinc.org` | `44235-0` | Superior mesenteric vessels US.doppler |
| `http://loinc.org` | `44236-8` | Upper extremity vessel graft - bilateral US.doppler |
| `http://loinc.org` | `44237-6` | Upper extremity vessel graft - bilateral US.doppler limited |
| `http://loinc.org` | `44238-4` | Trachea X-ray |
| `http://loinc.org` | `44239-2` | Ribs - unilateral and Chest X-ray Ge 3 and PA Chest Portable views |
| `http://loinc.org` | `44240-0` | Peripheral arteries - bilateral Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `44425-7` | FDA package insert Storage and handling section |
| `http://loinc.org` | `44729-2` | Progesterone/11-Deoxycorticosterone [Mass Ratio] in Serum or Plasma |
| `http://loinc.org` | `44943-9` | Self management |
| `http://loinc.org` | `46208-5` | Nursing notes |
| `http://loinc.org` | `46209-3` | Provider orders |
| `http://loinc.org` | `46210-1` | Case manager Note |
| `http://loinc.org` | `46213-5` | Tilt table study |
| `http://loinc.org` | `46214-3` | Intracardiac ablation study |
| `http://loinc.org` | `46215-0` | Wound care management Note |
| `http://loinc.org` | `46242-4` | Fetal Document Vital signs measurements |
| `http://loinc.org` | `46264-8` | History of medical device use |
| `http://loinc.org` | `46281-2` | CT Guidance for aspiration or injection of cyst of Unspecified body region |
| `http://loinc.org` | `46282-0` | US Guidance for aspiration or injection of cyst of Unspecified body region |
| `http://loinc.org` | `46283-8` | Mammogram Guidance for fine needle aspiration of Breast - right |
| `http://loinc.org` | `46284-6` | Mammogram Guidance for fine needle aspiration of Breast - left |
| `http://loinc.org` | `46285-3` | US Guidance for core needle biopsy of Thyroid |
| `http://loinc.org` | `46286-1` | Mammogram Guidance for needle biopsy of Breast |
| `http://loinc.org` | `46287-9` | CT Guidance for needle biopsy of Unspecified body region |
| `http://loinc.org` | `46288-7` | US Guidance for needle biopsy of Prostate |
| `http://loinc.org` | `46289-5` | CT Guidance for biopsy of Unspecified body region-- W and WO contrast IV |
| `http://loinc.org` | `46290-3` | CT Guidance for biopsy of Unspecified body region-- WO contrast |
| `http://loinc.org` | `46291-1` | CT Guidance for drainage of Unspecified body region-- W and WO contrast IV |
| `http://loinc.org` | `46292-9` | CT Guidance for drainage of Unspecified body region-- W contrast IV |
| `http://loinc.org` | `46293-7` | CT Guidance for drainage of Unspecified body region-- WO contrast |
| `http://loinc.org` | `46294-5` | Fluoroscopy Guidance for replacement of percutaneous drainage tube in Stomach |
| `http://loinc.org` | `46295-2` | Mammogram Guidance.stereotactic for core needle biopsy of Breast - left |
| `http://loinc.org` | `46296-0` | Mammogram Guidance.stereotactic for core needle biopsy of Breast |
| `http://loinc.org` | `46297-8` | SPECT |
| `http://loinc.org` | `46298-6` | Mastoid - bilateral CT |
| `http://loinc.org` | `46299-4` | Breast - unilateral MRI |
| `http://loinc.org` | `46300-0` | Sinuses CT coronal |
| `http://loinc.org` | `46301-8` | Extremity vein - bilateral US.doppler limited |
| `http://loinc.org` | `46302-6` | Upper extremity artery - bilateral US.doppler limited |
| `http://loinc.org` | `46303-4` | Upper extremity vessels US.doppler limited |
| `http://loinc.org` | `46304-2` | Sinuses CT limited WO contrast |
| `http://loinc.org` | `46305-9` | CT whole body |
| `http://loinc.org` | `46306-7` | CT whole body W contrast IV |
| `http://loinc.org` | `46307-5` | Lower extremity vessels - right CT angiogram W and WO contrast IV |
| `http://loinc.org` | `46308-3` | Lower extremity vessels - left CT angiogram W and WO contrast IV |
| `http://loinc.org` | `46309-1` | Upper extremity vessels - right CT angiogram W and WO contrast IV |
| `http://loinc.org` | `46310-9` | Orbit and Face and Neck MRI W and WO contrast IV |
| `http://loinc.org` | `46311-7` | Parotid gland CT W and WO contrast IV |
| `http://loinc.org` | `46312-5` | Upper extremity vessels - left CT angiogram W and WO contrast IV |
| `http://loinc.org` | `46313-3` | Pelvis CT W and WO reduced contrast volume IV |
| `http://loinc.org` | `46314-1` | Internal auditory canal CT W and WO reduced contrast volume IV |
| `http://loinc.org` | `46315-8` | Facial bones and Maxilla CT W and WO reduced contrast volume IV |
| `http://loinc.org` | `46316-6` | Head CT W and WO reduced contrast volume IV |
| `http://loinc.org` | `46317-4` | Chest CT W and WO reduced contrast volume IV |
| `http://loinc.org` | `46318-2` | Abdomen CT W and WO reduced contrast volume IV |
| `http://loinc.org` | `46319-0` | Elbow MRI W contrast intraarticular |
| `http://loinc.org` | `46320-8` | Orbit and Face CT W contrast IV |
| `http://loinc.org` | `46321-6` | Orbit and Face and Neck MRI W contrast IV |
| `http://loinc.org` | `46322-4` | Kidney CT W contrast IV |
| `http://loinc.org` | `46323-2` | Breast - unilateral MRI W contrast IV |
| `http://loinc.org` | `46324-0` | Lower extremity vessels MRI angiogram W contrast IV |
| `http://loinc.org` | `46325-7` | Internal auditory canal CT W reduced contrast volume IV |
| `http://loinc.org` | `46326-5` | Facial bones and Maxilla CT W reduced contrast volume IV |
| `http://loinc.org` | `46327-3` | Chest CT W reduced contrast volume IV |
| `http://loinc.org` | `46328-1` | Head CT W reduced contrast volume IV |
| `http://loinc.org` | `46329-9` | Pelvis CT W reduced contrast volume IV |
| `http://loinc.org` | `46330-7` | Abdomen CT W reduced contrast volume IV |
| `http://loinc.org` | `46331-5` | Orbit CT WO contrast |
| `http://loinc.org` | `46332-3` | Orbit and Face and Neck MRI WO contrast |
| `http://loinc.org` | `46333-1` | Breast - unilateral MRI WO contrast |
| `http://loinc.org` | `46335-6` | Breast - bilateral Mammogram Single view |
| `http://loinc.org` | `46336-4` | Breast - left Mammogram Single view |
| `http://loinc.org` | `46337-2` | Breast - right Mammogram Single view |
| `http://loinc.org` | `46338-0` | Breast - unilateral Mammogram Single view |
| `http://loinc.org` | `46339-8` | Breast - unilateral Mammogram |
| `http://loinc.org` | `46340-6` | Spine Lumbosacral Junction X-ray |
| `http://loinc.org` | `46341-4` | Abdomen Fluoroscopy |
| `http://loinc.org` | `46342-2` | Breast FFD mammogram |
| `http://loinc.org` | `46343-0` | Wrist - right X-ray GE 3 views |
| `http://loinc.org` | `46344-8` | Elbow - left X-ray GE 3 views |
| `http://loinc.org` | `46345-5` | Elbow - right X-ray GE 3 views |
| `http://loinc.org` | `46346-3` | Wrist - left X-ray GE 3 views |
| `http://loinc.org` | `46347-1` | Ankle - right X-ray GE 3 views |
| `http://loinc.org` | `46348-9` | Chest X-ray GE 2 and PA and Lateral views |
| `http://loinc.org` | `46349-7` | Shoulder - bilateral X-ray AP and transthoracic |
| `http://loinc.org` | `46350-5` | Breast - unilateral Mammogram diagnostic |
| `http://loinc.org` | `46351-3` | Breast implant - bilateral Mammogram displacement |
| `http://loinc.org` | `46352-1` | Breast duct Mammogram during surgery W contrast intra duct |
| `http://loinc.org` | `46354-7` | Breast - right FFD mammogram screening |
| `http://loinc.org` | `46355-4` | Breast - left FFD mammogram screening |
| `http://loinc.org` | `46356-2` | Breast - unilateral Mammogram screening |
| `http://loinc.org` | `46357-0` | Colon Fluoroscopy W air contrast PR |
| `http://loinc.org` | `46358-8` | MRI whole body |
| `http://loinc.org` | `46359-6` | Superior mesenteric vessels MRI angiogram |
| `http://loinc.org` | `46360-4` | Aortic arch MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `46361-2` | Lung Scan ventilation W Xe-133 inhaled |
| `http://loinc.org` | `46362-0` | Foot vessels US.doppler |
| `http://loinc.org` | `46363-8` | Lower extremity vein US |
| `http://loinc.org` | `46364-6` | Lower extremity vein - bilateral US |
| `http://loinc.org` | `46365-3` | CT Guidance for ablation of tissue of Celiac plexus |
| `http://loinc.org` | `46366-1` | SPECT Guidance for biopsy of Bone |
| `http://loinc.org` | `46367-9` | CT Guidance for needle biopsy of Adrenal gland |
| `http://loinc.org` | `46368-7` | CT Guidance for needle biopsy of Breast |
| `http://loinc.org` | `46369-5` | US Guidance for needle biopsy of Ovary |
| `http://loinc.org` | `46370-3` | US Guidance for needle biopsy of Pelvis |
| `http://loinc.org` | `46371-1` | X-ray Guidance for change of percutaneous tube in Unspecified body region-- W contrast |
| `http://loinc.org` | `46372-9` | Fluoroscopy Guidance for percutaneous drainage of Biliary ducts |
| `http://loinc.org` | `46373-7` | SPECT Guidance for placement of tube in Chest |
| `http://loinc.org` | `46374-5` | Cerebral artery US |
| `http://loinc.org` | `46375-2` | Artery US |
| `http://loinc.org` | `46376-0` | Kidney - bilateral Fluoroscopy W contrast antegrade |
| `http://loinc.org` | `46377-8` | Skull X-ray GE 3 views |
| `http://loinc.org` | `46378-6` | Knee - bilateral X-ray PA standing and W flexion |
| `http://loinc.org` | `46379-4` | Upper extremity vessels - bilateral US.doppler |
| `http://loinc.org` | `46380-2` | Breast Implant - unilateral Mammogram |
| `http://loinc.org` | `46381-0` | Elbow+Radius+Ulna X-ray |
| `http://loinc.org` | `46382-8` | Hand vessels US.doppler |
| `http://loinc.org` | `46384-4` | SPECT Guidance for biopsy of Superficial bone |
| `http://loinc.org` | `46385-1` | Upper extremity vessel graft US.doppler |
| `http://loinc.org` | `46386-9` | Teeth X-ray bitewing |
| `http://loinc.org` | `46387-7` | Mammogram Guidance for fine needle aspiration of Breast |
| `http://loinc.org` | `46388-5` | Aorta US.doppler |
| `http://loinc.org` | `46389-3` | Elbow - bilateral X-ray and radial head capitellar |
| `http://loinc.org` | `46390-1` | Ankle - left X-ray GE 3 views |
| `http://loinc.org` | `46391-9` | Shoulder X-ray portable |
| `http://loinc.org` | `46392-7` | Fluoroscopy Guidance for injection of Sinuses |
| `http://loinc.org` | `46393-5` | Liver CT W Xe-133 inhaled |
| `http://loinc.org` | `46394-3` | Head CT dynamic W contrast IV |
| `http://loinc.org` | `46395-0` | Heart SPECT gated and ejection fraction at rest and W stress and W radionuclide IV |
| `http://loinc.org` | `46396-8` | Heart SPECT gated at rest and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `47039-3` | Hospital Admission history and physical note |
| `http://loinc.org` | `47040-1` | Consultation 2nd opinion |
| `http://loinc.org` | `47041-9` | Hospital Consultation 2nd opinion |
| `http://loinc.org` | `47042-7` | Counseling note |
| `http://loinc.org` | `47043-5` | Group counseling note |
| `http://loinc.org` | `47044-3` | Hospital Initial assessment note |
| `http://loinc.org` | `47045-0` | Study report |
| `http://loinc.org` | `47046-8` | Summary of death note |
| `http://loinc.org` | `47047-6` | Supervisory note |
| `http://loinc.org` | `47048-4` | Diagnostic interventional study report Interventional radiology |
| `http://loinc.org` | `47245-6` | HIV treatment form Document |
| `http://loinc.org` | `47366-0` | Chest CT limited WO contrast |
| `http://loinc.org` | `47367-8` | Chest Fluoroscopy GE 4 views |
| `http://loinc.org` | `47368-6` | Chest X-ray GE 4 and Pa and Lateral views |
| `http://loinc.org` | `47370-2` | Hand - left X-ray GE 3 views |
| `http://loinc.org` | `47371-0` | Hand - right X-ray GE 3 views |
| `http://loinc.org` | `47372-8` | Hip X-ray during surgery |
| `http://loinc.org` | `47373-6` | Knee - left X-ray 1 or 2 views |
| `http://loinc.org` | `47374-4` | Knee - left X-ray GE 4 views |
| `http://loinc.org` | `47375-1` | Knee - right X-ray 1 or 2 views |
| `http://loinc.org` | `47376-9` | Knee - right X-ray GE 4 views |
| `http://loinc.org` | `47377-7` | Knee - right X-ray LE 4 views |
| `http://loinc.org` | `47378-5` | Liver SPECT blood pool |
| `http://loinc.org` | `47379-3` | Mandible X-ray GE 4 views |
| `http://loinc.org` | `47380-1` | Mandible X-ray LE 3 views |
| `http://loinc.org` | `47381-9` | Mastoid X-ray GE 3 views |
| `http://loinc.org` | `47382-7` | Spine Lumbar X-ray GE 4 views |
| `http://loinc.org` | `47420-5` | Functional status assessment note |
| `http://loinc.org` | `47519-4` | History of Procedures Document |
| `http://loinc.org` | `47520-2` | Cytology report of Sputum Cyto stain |
| `http://loinc.org` | `47521-0` | Cytology report of Breast fine needle aspirate Cyto stain |
| `http://loinc.org` | `47522-8` | Cytology report of Nipple discharge Cyto stain |
| `http://loinc.org` | `47523-6` | Cytology report of Body fluid Cyto stain |
| `http://loinc.org` | `47524-4` | Cytology report of Thyroid fine needle aspirate Cyto stain |
| `http://loinc.org` | `47525-1` | Cytology report of Urine Cyto stain |
| `http://loinc.org` | `47526-9` | Cytology report of Unspecified specimen Cyto stain |
| `http://loinc.org` | `47527-7` | Cytology report of Cervical or vaginal smear or scraping Cyto stain.thin prep |
| `http://loinc.org` | `47528-5` | Cytology report of Cervical or vaginal smear or scraping Cyto stain |
| `http://loinc.org` | `47529-3` | Cytology report of Tissue Other stain |
| `http://loinc.org` | `47530-1` | Cytology report of Breast ductal lavage Cyto stain |
| `http://loinc.org` | `47983-2` | Mastoid - bilateral X-ray 1 or 2 views |
| `http://loinc.org` | `47984-0` | Pelvis and Spine Lumbar X-ray |
| `http://loinc.org` | `47985-7` | Spine CT W contrast IT |
| `http://loinc.org` | `47986-5` | Lower extremity arteries - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `47987-3` | Lower extremity arteries - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `48433-7` | Calcaneus - bilateral X-ray 2 views |
| `http://loinc.org` | `48434-5` | US Guidance for aspiration of Kidney |
| `http://loinc.org` | `48435-2` | Fluoroscopy Guidance for injection of Salivary gland - bilateral |
| `http://loinc.org` | `48436-0` | Spine Lumbar MRI W contrast IT |
| `http://loinc.org` | `48439-4` | Spine Thoracic MRI W contrast IT |
| `http://loinc.org` | `48440-2` | Skull.base MRI W contrast IV |
| `http://loinc.org` | `48441-0` | Spine Thoracic MRI W and WO contrast IT |
| `http://loinc.org` | `48442-8` | Spine CT W and WO contrast IT |
| `http://loinc.org` | `48443-6` | Nasopharynx CT W and WO contrast IV |
| `http://loinc.org` | `48444-4` | Brain.temporal MRI W contrast IV |
| `http://loinc.org` | `48445-1` | Larynx MRI WO contrast |
| `http://loinc.org` | `48446-9` | Nasopharynx CT W contrast IV |
| `http://loinc.org` | `48447-7` | Spine Cervical MRI W contrast IT |
| `http://loinc.org` | `48448-5` | Upper extremity artery US |
| `http://loinc.org` | `48449-3` | Orbit CT W contrast IV |
| `http://loinc.org` | `48450-1` | Spine Cervical MRI W and WO contrast IT |
| `http://loinc.org` | `48451-9` | Orbit CT W and WO contrast IV |
| `http://loinc.org` | `48452-7` | Spine Lumbar MRI W and WO contrast IT |
| `http://loinc.org` | `48453-5` | Brain.temporal MRI WO contrast |
| `http://loinc.org` | `48454-3` | Clavicle - right MRI W and WO contrast IV |
| `http://loinc.org` | `48455-0` | Clavicle - left MRI W and WO contrast IV |
| `http://loinc.org` | `48456-8` | Clavicle - right MRI W contrast IV |
| `http://loinc.org` | `48457-6` | Clavicle - left MRI W contrast IV |
| `http://loinc.org` | `48458-4` | Clavicle - right MRI WO contrast |
| `http://loinc.org` | `48459-2` | Clavicle - left MRI WO contrast |
| `http://loinc.org` | `48460-0` | Unspecified body region MRI limited |
| `http://loinc.org` | `48461-8` | Neck MRI limited |
| `http://loinc.org` | `48462-6` | Knee - left X-ray AP single view |
| `http://loinc.org` | `48463-4` | Knee - right X-ray AP single view |
| `http://loinc.org` | `48464-2` | Trachea Fluoroscopy |
| `http://loinc.org` | `48465-9` | Larynx Fluoroscopy |
| `http://loinc.org` | `48466-7` | Skull X-ray limited |
| `http://loinc.org` | `48467-5` | Sacroiliac Joint X-ray 1 or 2 views |
| `http://loinc.org` | `48468-3` | Ribs - bilateral and Chest X-ray 2 views and PA chest |
| `http://loinc.org` | `48469-1` | Spine Lumbar X-ray 2 or 3 views |
| `http://loinc.org` | `48470-9` | Mastoid - left X-ray 3 views |
| `http://loinc.org` | `48471-7` | Mastoid - right X-ray 3 views |
| `http://loinc.org` | `48472-5` | Spine Thoracic X-ray 3 views and Swimmers |
| `http://loinc.org` | `48473-3` | Spine Lumbar and Sacrum X-ray 4 views |
| `http://loinc.org` | `48474-1` | Hand - bilateral X-ray AP and lateral |
| `http://loinc.org` | `48475-8` | Breast implant - bilateral Mammogram diagnostic |
| `http://loinc.org` | `48476-6` | Foot - right X-ray GE 3 views |
| `http://loinc.org` | `48477-4` | Foot - left X-ray GE 3 views |
| `http://loinc.org` | `48478-2` | Foot - bilateral X-ray GE 3 views |
| `http://loinc.org` | `48479-0` | Facial bones X-ray GE 3 views |
| `http://loinc.org` | `48480-8` | Ankle - bilateral X-ray GE 3 views |
| `http://loinc.org` | `48481-6` | Elbow - bilateral X-ray GE 3 views |
| `http://loinc.org` | `48482-4` | Sternoclavicular Joints X-ray GE 3 views |
| `http://loinc.org` | `48483-2` | Wrist - bilateral X-ray GE 3 views |
| `http://loinc.org` | `48484-0` | Ribs - right and Chest X-ray GE 3 and PA Chest views |
| `http://loinc.org` | `48485-7` | Ribs - bilateral and Chest X-ray GE 3 and PA Chest views |
| `http://loinc.org` | `48486-5` | Ribs - left and Chest X-ray GE 3 and PA Chest views |
| `http://loinc.org` | `48487-3` | Skull X-ray GE 4 views |
| `http://loinc.org` | `48488-1` | Mastoid - right X-ray 1 or 2 views |
| `http://loinc.org` | `48489-9` | Mastoid - left X-ray 1 or 2 views |
| `http://loinc.org` | `48490-7` | Temporomandibular joint - right X-ray open and closed mouth |
| `http://loinc.org` | `48491-5` | Temporomandibular joint - left X-ray open and closed mouth |
| `http://loinc.org` | `48492-3` | Breast implant - bilateral Mammogram screening |
| `http://loinc.org` | `48687-8` | Skull.base MRI WO contrast |
| `http://loinc.org` | `48688-6` | Upper extremity vein - right US |
| `http://loinc.org` | `48689-4` | Upper extremity vein - left US |
| `http://loinc.org` | `48690-2` | Upper extremity vein - bilateral US |
| `http://loinc.org` | `48691-0` | Lower extremity vein - right US |
| `http://loinc.org` | `48692-8` | Lower extremity vein - left US |
| `http://loinc.org` | `48693-6` | Lower extremity artery US |
| `http://loinc.org` | `48694-4` | Brain.temporal MRI W and WO contrast IV |
| `http://loinc.org` | `48695-1` | Skull.base X-ray Single view |
| `http://loinc.org` | `48696-9` | Submandibular gland - right Fluoroscopy W contrast intra salivary duct |
| `http://loinc.org` | `48697-7` | Skull.base X-ray |
| `http://loinc.org` | `48698-5` | Submandibular gland - bilateral Fluoroscopy W contrast intra salivary duct |
| `http://loinc.org` | `48699-3` | Temporomandibular Joint - unilateral X-ray open and closed mouth |
| `http://loinc.org` | `48735-5` | Mammogram Guidance for localization of Breast |
| `http://loinc.org` | `48736-3` | Mammogram Guidance for sentinel lymph node injection of Breast - left |
| `http://loinc.org` | `48737-1` | Wrist and Hand X-ray 3 views |
| `http://loinc.org` | `48738-9` | Wrist - bilateral and Hand - bilateral X-ray 3 views |
| `http://loinc.org` | `48739-7` | Mammogram Guidance for sentinel lymph node injection of Breast - right |
| `http://loinc.org` | `48740-5` | Mammogram Guidance for sentinel lymph node injection of Breast |
| `http://loinc.org` | `48742-1` | Scrotum and Testicle US.doppler |
| `http://loinc.org` | `48743-9` | Abdomen retroperitoneum CT W and WO contrast IV |
| `http://loinc.org` | `48745-4` | Mandible - left X-ray |
| `http://loinc.org` | `48746-2` | Sacroiliac joint - bilateral X-ray GE 3 views |
| `http://loinc.org` | `48747-0` | Orbit - bilateral X-ray GE 4 views |
| `http://loinc.org` | `48748-8` | Spine X-ray oblique |
| `http://loinc.org` | `48749-6` | Spine Thoracic X-ray oblique |
| `http://loinc.org` | `48764-5` | Summary purpose CCD Document |
| `http://loinc.org` | `48765-2` | Allergies and adverse reactions Document |
| `http://loinc.org` | `48766-0` | Information source |
| `http://loinc.org` | `48767-8` | Annotation comment Narrative |
| `http://loinc.org` | `48768-6` | Payment sources Document |
| `http://loinc.org` | `48779-3` | FDA package insert Structured product labelling indexing data elements section |
| `http://loinc.org` | `48780-1` | FDA package insert Structured product labelling listing data elements section |
| `http://loinc.org` | `48807-2` | Bone marrow aspiration report |
| `http://loinc.org` | `49118-3` | Unspecified body region Scan |
| `http://loinc.org` | `49489-8` | FDA package insert Microbiology section |
| `http://loinc.org` | `49507-7` | Unspecified body region MRI W contrast IV |
| `http://loinc.org` | `49509-3` | Breast duct - right Mammogram Single view W contrast intra duct |
| `http://loinc.org` | `49510-1` | Breast duct - left Mammogram Single view W contrast intra duct |
| `http://loinc.org` | `49511-9` | Femoral artery Fluoroscopic angiogram runoff W and WO contrast IA |
| `http://loinc.org` | `49512-7` | Unspecified body region Fluoroscopy |
| `http://loinc.org` | `49565-5` | Thoracic Spine vessels MRI angiogram |
| `http://loinc.org` | `49566-3` | Heart SPECT at rest and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `49567-1` | Heart SPECT perfusion W adenosine and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `49568-9` | Heart SPECT perfusion at rest and W stress and W Tl-201 IV and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `49569-7` | Heart SPECT perfusion and wall motion at rest and W stress and W Tl-201 IV and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `49570-5` | Ankle - bilateral X-ray GE 6 views |
| `http://loinc.org` | `49571-3` | Scan limited W I-131 MIBG IV |
| `http://loinc.org` | `50007-4` | Cytology report of Bronchoalveolar lavage Cyto stain |
| `http://loinc.org` | `50081-9` | 18-Hydroxydeoxycorticosterone [Moles/volume] in Serum or Plasma |
| `http://loinc.org` | `50755-8` | Lower extremity - bilateral CT W contrast IV |
| `http://loinc.org` | `50971-1` | Cytology report of Bronchial brush Cyto stain |
| `http://loinc.org` | `51387-9` | Knee - bilateral X-ray and (AP view standing) |
| `http://loinc.org` | `51388-7` | Wrist - right and Hand - right X-ray |
| `http://loinc.org` | `51389-5` | Breast Scan W Tl-201 IV |
| `http://loinc.org` | `51391-1` | Fluoroscopic angiogram Guidance for placement of transjugular intrahepatic portosystemic shunt in Portal vein and Hepatic vein |
| `http://loinc.org` | `51392-9` | Wrist - left and Hand - left X-ray |
| `http://loinc.org` | `51394-5` | Ankle - right and Foot - right X-ray |
| `http://loinc.org` | `51395-2` | Ankle - left and Foot.left X-ray |
| `http://loinc.org` | `51845-6` | Outpatient Consult note |
| `http://loinc.org` | `51846-4` | Emergency department Consult note |
| `http://loinc.org` | `51847-2` | Assessment + Plan note |
| `http://loinc.org` | `51848-0` | Assessment note |
| `http://loinc.org` | `51849-8` | Admission history and physical note |
| `http://loinc.org` | `51850-6` | Physical findings of Head and Ears and Eyes and Nose and Throat |
| `http://loinc.org` | `51851-4` | Administrative note |
| `http://loinc.org` | `51852-2` | Letter |
| `http://loinc.org` | `51854-8` | Long term care facility Consult note |
| `http://loinc.org` | `51855-5` | Patient Note |
| `http://loinc.org` | `51897-7` | Healthcare Associated Infection report Document |
| `http://loinc.org` | `51898-5` | Risk factors Document |
| `http://loinc.org` | `51899-3` | Details Document |
| `http://loinc.org` | `51900-9` | Population Summary note |
| `http://loinc.org` | `51941-3` | FDA product label Back panel of package |
| `http://loinc.org` | `51942-1` | FDA product label Side panel of package Right |
| `http://loinc.org` | `51943-9` | FDA product label Side panel of package Left |
| `http://loinc.org` | `51944-7` | FDA product label Side panel of package |
| `http://loinc.org` | `51945-4` | FDA product label Principal display panel of package |
| `http://loinc.org` | `51946-2` | FDA product label Top panel of package |
| `http://loinc.org` | `51947-0` | FDA product label Bottom panel of package |
| `http://loinc.org` | `51948-8` | FDA product label Flap panel of package |
| `http://loinc.org` | `51965-2` | Pharmacogenetic analysis report in Blood or Tissue Document by Molecular genetics method |
| `http://loinc.org` | `51969-4` | Genetic analysis summary report in Blood or Tissue Document by Molecular genetics method |
| `http://loinc.org` | `52027-0` | Abortion consent |
| `http://loinc.org` | `52028-8` | Hysterectomy consent |
| `http://loinc.org` | `52029-6` | Sterilization consent |
| `http://loinc.org` | `52030-4` | Explanation of benefits |
| `http://loinc.org` | `52031-2` | Explanation of benefits to subscriber |
| `http://loinc.org` | `52032-0` | Appeal denial letter |
| `http://loinc.org` | `52033-8` | General correspondence |
| `http://loinc.org` | `52034-6` | Payer letter |
| `http://loinc.org` | `52035-3` | Home health claims |
| `http://loinc.org` | `52036-1` | Home health prior authorization |
| `http://loinc.org` | `52037-9` | Member ID card copy |
| `http://loinc.org` | `52038-7` | Subscriber Information including retroactive and presumptive eligibility |
| `http://loinc.org` | `52039-5` | Skilled Nursing Facility (SNF) record |
| `http://loinc.org` | `52040-3` | Dental X-rays and other images (not DICOM) |
| `http://loinc.org` | `52041-1` | Blood glucose monitors |
| `http://loinc.org` | `52042-9` | Continuous positive airway pressure (CPAP) |
| `http://loinc.org` | `52043-7` | Enteral nutrition |
| `http://loinc.org` | `52044-5` | External infusion pump |
| `http://loinc.org` | `52045-2` | Gait trainers |
| `http://loinc.org` | `52046-0` | Hospital beds |
| `http://loinc.org` | `52047-8` | Immunosuppressive drugs |
| `http://loinc.org` | `52048-6` | Lymphedema pumps |
| `http://loinc.org` | `52049-4` | Manual wheelchair |
| `http://loinc.org` | `52050-2` | Motorized wheelchair |
| `http://loinc.org` | `52051-0` | Orthotics/Prosthetics |
| `http://loinc.org` | `52052-8` | Osteogenesis stimulators |
| `http://loinc.org` | `52053-6` | Oxygen |
| `http://loinc.org` | `52054-4` | Parenteral |
| `http://loinc.org` | `52055-1` | Power operated vehicles |
| `http://loinc.org` | `52056-9` | Repair of durable medical equipment |
| `http://loinc.org` | `52057-7` | Seat lift mechanism |
| `http://loinc.org` | `52058-5` | Seating systems |
| `http://loinc.org` | `52059-3` | Speech generating device |
| `http://loinc.org` | `52060-1` | Standers/standing frames |
| `http://loinc.org` | `52061-9` | Support surfaces |
| `http://loinc.org` | `52062-7` | Transcutaneous electrical neural stimulation (TENS) |
| `http://loinc.org` | `52063-5` | Prescription for durable medical equipment (DME) |
| `http://loinc.org` | `52064-3` | First report of injury |
| `http://loinc.org` | `52065-0` | Automobile liability |
| `http://loinc.org` | `52066-8` | Notice of Discharge Medicare Appeal Rights (NODMAR) form |
| `http://loinc.org` | `52067-6` | Past filing limit justification |
| `http://loinc.org` | `52068-4` | Property and casualty state mandated forms |
| `http://loinc.org` | `52069-2` | Tax ID number - IRS form W9 |
| `http://loinc.org` | `52070-0` | Workers compensation |
| `http://loinc.org` | `52071-8` | Employee assistance program |
| `http://loinc.org` | `52072-6` | Non-emergency transportation |
| `http://loinc.org` | `52073-4` | Vision attachment |
| `http://loinc.org` | `52075-9` | Purchase invoice |
| `http://loinc.org` | `52184-9` | Pulmonary therapy service attachment |
| `http://loinc.org` | `52790-3` | CT Guidance for replacement of percutaneous drainage tube in Abdomen |
| `http://loinc.org` | `52791-1` | CT Guidance for replacement of percutaneous drainage tube in Pelvis |
| `http://loinc.org` | `53242-4` | Charge ticket or encounter form |
| `http://loinc.org` | `53243-2` | Advanced beneficiary notice |
| `http://loinc.org` | `53244-0` | Notice of privacy practices receipt |
| `http://loinc.org` | `53245-7` | Driver license image |
| `http://loinc.org` | `53246-5` | Non-medical services |
| `http://loinc.org` | `53247-3` | Eligibility acknowledgement |
| `http://loinc.org` | `53347-1` | 11-Deoxycorticosterone [Mass/volume] in Dried blood spot |
| `http://loinc.org` | `53348-9` | 11-Deoxycorticosterone [Moles/volume] in Dried blood spot |
| `http://loinc.org` | `53576-5` | Personal health monitoring report Document |
| `http://loinc.org` | `54094-8` | Emergency department Triage note |
| `http://loinc.org` | `54095-5` | Chemotherapy effectiveness panel [Identifier] - Blood or Tissue |
| `http://loinc.org` | `54433-8` | FDA package insert User safety warnings section |
| `http://loinc.org` | `55107-7` | Addendum Document |
| `http://loinc.org` | `55108-5` | Clinical presentation Document |
| `http://loinc.org` | `55109-3` | Complications Document |
| `http://loinc.org` | `55110-1` | Conclusions Document |
| `http://loinc.org` | `55111-9` | Current imaging procedure descriptions Document |
| `http://loinc.org` | `55112-7` | Document summary |
| `http://loinc.org` | `55113-5` | Key images Document Radiology |
| `http://loinc.org` | `55114-3` | Prior imaging procedure descriptions Document |
| `http://loinc.org` | `55115-0` | Requested imaging studies information Document |
| `http://loinc.org` | `55122-6` | Surgical operation note implants Narrative |
| `http://loinc.org` | `55182-0` | Quality Reporting Document Architecture incidence report Document |
| `http://loinc.org` | `55183-8` | Quality Reporting Document Architecture patient list report population Document |
| `http://loinc.org` | `55184-6` | Quality Reporting Document Architecture calculated summary report population Document |
| `http://loinc.org` | `55185-3` | Measure set Document |
| `http://loinc.org` | `55186-1` | Measure Document |
| `http://loinc.org` | `55187-9` | Reporting parameters Document |
| `http://loinc.org` | `55188-7` | Patient data Document |
| `http://loinc.org` | `55228-1` | Cytogenetics study |
| `http://loinc.org` | `55229-9` | Immune stain study |
| `http://loinc.org` | `55230-7` | Immunophenotyping study |
| `http://loinc.org` | `55750-4` | Patient safety report Event Document |
| `http://loinc.org` | `55751-2` | Public health case report Document |
| `http://loinc.org` | `55808-0` | 11-Deoxycorticosterone [Moles/time] in 24 hour Urine |
| `http://loinc.org` | `56444-3` | Healthcare communication Document |
| `http://loinc.org` | `56445-0` | Medication summary Document |
| `http://loinc.org` | `56446-8` | Appointment summary Document |
| `http://loinc.org` | `56447-6` | Plan of care note |
| `http://loinc.org` | `56555-6` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --baseline |
| `http://loinc.org` | `56556-4` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --30 minutes post XXX challenge |
| `http://loinc.org` | `56602-6` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --1st specimen post XXX challenge |
| `http://loinc.org` | `56603-4` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --2nd specimen post XXX challenge |
| `http://loinc.org` | `56604-2` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --3rd specimen post XXX challenge |
| `http://loinc.org` | `56605-9` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --4th specimen post XXX challenge |
| `http://loinc.org` | `56606-7` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --pre XXX challenge |
| `http://loinc.org` | `56608-3` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --15 minutes post XXX challenge |
| `http://loinc.org` | `56609-1` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --20 minutes post XXX challenge |
| `http://loinc.org` | `56610-9` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --40 minutes post XXX challenge |
| `http://loinc.org` | `56611-7` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --1.5 hours post XXX challenge |
| `http://loinc.org` | `56612-5` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --2 hours post XXX challenge |
| `http://loinc.org` | `56613-3` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --2.5 hours post XXX challenge |
| `http://loinc.org` | `57016-8` | Privacy policy acknowledgment Document |
| `http://loinc.org` | `57017-6` | Privacy policy Organization Document |
| `http://loinc.org` | `57024-2` | Health Quality Measure document |
| `http://loinc.org` | `57025-9` | Data criteria Narrative |
| `http://loinc.org` | `57026-7` | Population criteria Narrative |
| `http://loinc.org` | `57027-5` | Measure observations Narrative |
| `http://loinc.org` | `57053-1` | Nurse Emergency department Note |
| `http://loinc.org` | `57054-9` | Nurse Emergency department Triage+care note |
| `http://loinc.org` | `57055-6` | Antepartum summary note |
| `http://loinc.org` | `57056-4` | Labor and delivery admission history and physical note |
| `http://loinc.org` | `57057-2` | Labor and delivery summary note |
| `http://loinc.org` | `57058-0` | Maternal discharge summary note |
| `http://loinc.org` | `57059-8` | Pregnancy visit summary note Narrative |
| `http://loinc.org` | `57129-9` | Full newborn screening summary report for display or printing |
| `http://loinc.org` | `57133-1` | Referral note |
| `http://loinc.org` | `57134-9` | Dentistry Referral note |
| `http://loinc.org` | `57135-6` | Dermatology Referral note |
| `http://loinc.org` | `57136-4` | Diabetology Referral note |
| `http://loinc.org` | `57137-2` | Endocrinology Referral note |
| `http://loinc.org` | `57138-0` | Gastroenterology Referral note |
| `http://loinc.org` | `57139-8` | General medicine Referral note |
| `http://loinc.org` | `57141-4` | Infectious disease Referral note |
| `http://loinc.org` | `57142-2` | Kinesiotherapy Referral note |
| `http://loinc.org` | `57143-0` | Mental health Referral note |
| `http://loinc.org` | `57144-8` | Nephrology Referral note |
| `http://loinc.org` | `57145-5` | Neurology Referral note |
| `http://loinc.org` | `57146-3` | Neurological surgery Referral note |
| `http://loinc.org` | `57147-1` | Occupational medicine Referral note |
| `http://loinc.org` | `57148-9` | Occupational therapy Referral note |
| `http://loinc.org` | `57149-7` | Oncology Referral note |
| `http://loinc.org` | `57150-5` | Ophthalmology Referral note |
| `http://loinc.org` | `57151-3` | Optometry Referral note |
| `http://loinc.org` | `57152-1` | Pharmacy Referral note |
| `http://loinc.org` | `57153-9` | Physical medicine and rehabilitation Referral note |
| `http://loinc.org` | `57154-7` | Physical therapy Referral note |
| `http://loinc.org` | `57155-4` | Plastic surgery Referral note |
| `http://loinc.org` | `57156-2` | Podiatry Referral note |
| `http://loinc.org` | `57157-0` | Psychiatry Referral note |
| `http://loinc.org` | `57158-8` | Psychology Referral note |
| `http://loinc.org` | `57159-6` | Radiation oncology Referral note |
| `http://loinc.org` | `57160-4` | Recreational therapy Referral note |
| `http://loinc.org` | `57162-0` | Respiratory therapy Referral note |
| `http://loinc.org` | `57163-8` | Rheumatology Referral note |
| `http://loinc.org` | `57164-6` | Social work Referral note |
| `http://loinc.org` | `57165-3` | Speech-language pathology Referral note |
| `http://loinc.org` | `57166-1` | Surgery Referral note |
| `http://loinc.org` | `57167-9` | Thoracic surgery Referral note |
| `http://loinc.org` | `57168-7` | Urology Referral note |
| `http://loinc.org` | `57169-5` | Vascular surgery Referral note |
| `http://loinc.org` | `57170-3` | Cardiology Referral note |
| `http://loinc.org` | `57171-1` | Geriatric medicine Referral note |
| `http://loinc.org` | `57172-9` | Hematology+Medical Oncology Referral note |
| `http://loinc.org` | `57173-7` | Nutrition and dietetics Referral note |
| `http://loinc.org` | `57174-5` | Oral and Maxillofacial Surgery Referral note |
| `http://loinc.org` | `57175-2` | Orthopaedic surgery Referral note |
| `http://loinc.org` | `57176-0` | Otolaryngology Referral note |
| `http://loinc.org` | `57177-8` | Pulmonary Referral note |
| `http://loinc.org` | `57178-6` | Critical Care Medicine Referral note |
| `http://loinc.org` | `57179-4` | Obstetrics and Gynecology Referral note |
| `http://loinc.org` | `57491-3` | 11-Deoxycorticosterone [Moles/volume] in Serum or Plasma --pre 250 ug corticotropin |
| `http://loinc.org` | `57492-1` | 11-Deoxycorticosterone [Moles/volume] in Serum or Plasma --30 minutes post 250 ug corticotropin |
| `http://loinc.org` | `57493-9` | 11-Deoxycorticosterone [Moles/volume] in Serum or Plasma --1 hour post 250 ug corticotropin |
| `http://loinc.org` | `57551-4` | 18-Hydroxydeoxycorticosterone [Moles/volume] in Serum or Plasma --pre dose corticotropin |
| `http://loinc.org` | `57552-2` | 18-Hydroxydeoxycorticosterone [Moles/volume] in Serum or Plasma --30 minutes post dose corticotropin |
| `http://loinc.org` | `57553-0` | 18-Hydroxydeoxycorticosterone [Moles/volume] in Serum or Plasma --1 hour post dose corticotropin |
| `http://loinc.org` | `57560-5` | 21-Deoxycorticosterone [Moles/volume] in Serum or Plasma --pre dose corticotropin |
| `http://loinc.org` | `57561-3` | 21-Deoxycorticosterone [Moles/volume] in Serum or Plasma --30 minutes post dose corticotropin |
| `http://loinc.org` | `57562-1` | 21-Deoxycorticosterone [Moles/volume] in Serum or Plasma --1 hour post dose corticotropin |
| `http://loinc.org` | `57822-9` | Lung PET |
| `http://loinc.org` | `57823-7` | Esophagus PET |
| `http://loinc.org` | `57826-0` | Co-payment amount Narrative |
| `http://loinc.org` | `57827-8` | Reason for co-payment exemption Narrative |
| `http://loinc.org` | `57828-6` | Prescription list Document |
| `http://loinc.org` | `57829-4` | Prescription for medical equipment or product Document |
| `http://loinc.org` | `57830-2` | Admission request Document |
| `http://loinc.org` | `57831-0` | Prescription for rehabilitation Document |
| `http://loinc.org` | `57832-8` | Prescription for diagnostic or specialist care Document |
| `http://loinc.org` | `57833-6` | Prescription for medication Document |
| `http://loinc.org` | `57834-4` | Patient transportation request Document |
| `http://loinc.org` | `58477-1` | Pulmonary function report |
| `http://loinc.org` | `58740-2` | Abdomen MRCP WO contrast |
| `http://loinc.org` | `58741-0` | Head to thigh PET |
| `http://loinc.org` | `58742-8` | Head and Neck PET |
| `http://loinc.org` | `58743-6` | US Guidance for ablation of tissue of Unspecified body region |
| `http://loinc.org` | `58744-4` | Heart CT |
| `http://loinc.org` | `58745-1` | Coronary arteries CT angiogram and 3D reconstruction W contrast IV |
| `http://loinc.org` | `58746-9` | AV fistula Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `58747-7` | CT Guidance for ablation of tissue of Unspecified body region |
| `http://loinc.org` | `58748-5` | Brain Functional MRI |
| `http://loinc.org` | `58749-3` | Heart MRI W stress and W and WO contrast IV |
| `http://loinc.org` | `58750-1` | Heart MRI W stress |
| `http://loinc.org` | `59255-0` | Left atrium and Pulmonary veins CT angiogram and 3D reconstruction W contrast IV |
| `http://loinc.org` | `59258-4` | Emergency department Discharge summary |
| `http://loinc.org` | `59259-2` | Psychiatry Discharge summary |
| `http://loinc.org` | `59268-3` | Neonatal care report |
| `http://loinc.org` | `59281-6` | Transthoracic cardiac echo study report US |
| `http://loinc.org` | `59282-4` | Stress cardiac echo study report US |
| `http://loinc.org` | `59283-2` | Well child visit note |
| `http://loinc.org` | `59284-0` | Patient Consent |
| `http://loinc.org` | `59768-2` | Procedure indications Narrative |
| `http://loinc.org` | `59769-0` | Postprocedure diagnosis Narrative |
| `http://loinc.org` | `59770-8` | Procedure estimated blood loss Narrative |
| `http://loinc.org` | `59771-6` | Procedure implants Narrative |
| `http://loinc.org` | `59772-4` | Planned procedure Narrative |
| `http://loinc.org` | `59773-2` | Procedure specimens taken Narrative |
| `http://loinc.org` | `59774-0` | Procedure anesthesia Narrative |
| `http://loinc.org` | `59775-7` | Procedure disposition Narrative |
| `http://loinc.org` | `59776-5` | Procedure findings Narrative |
| `http://loinc.org` | `59845-8` | FDA package insert Instructions for use section |
| `http://loinc.org` | `59984-5` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --8th specimen post XXX challenge |
| `http://loinc.org` | `59985-2` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --7th specimen post XXX challenge |
| `http://loinc.org` | `59986-0` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --6th specimen post XXX challenge |
| `http://loinc.org` | `59987-8` | 11-Deoxycorticosterone [Mass/volume] in Serum or Plasma --5th specimen post XXX challenge |
| `http://loinc.org` | `60280-5` | Emergency department Discharge instructions |
| `http://loinc.org` | `60515-4` | Rectum and Colon CT 3D W air contrast PR |
| `http://loinc.org` | `60527-9` | Thyroid Scan and uptake W I-123 PO |
| `http://loinc.org` | `60555-0` | FDA package insert Accessories |
| `http://loinc.org` | `60556-8` | FDA package insert Assembly or installation instructions |
| `http://loinc.org` | `60557-6` | FDA package insert Calibration instructions |
| `http://loinc.org` | `60558-4` | FDA package insert Cleaning, disinfecting, and sterilization instructions |
| `http://loinc.org` | `60559-2` | FDA package insert Components |
| `http://loinc.org` | `60560-0` | FDA package insert Intended use of the device |
| `http://loinc.org` | `60561-8` | FDA package insert Other safety information |
| `http://loinc.org` | `60568-3` | Synoptic report |
| `http://loinc.org` | `60569-1` | Report addendum.synoptic Document |
| `http://loinc.org` | `60570-9` | Pathology Consult note |
| `http://loinc.org` | `60571-7` | Pathology Consult note.synoptic |
| `http://loinc.org` | `60572-5` | Report template ID |
| `http://loinc.org` | `60573-3` | Report template source |
| `http://loinc.org` | `60574-1` | Report template version ID |
| `http://loinc.org` | `60590-7` | Medication dispensed.brief Document |
| `http://loinc.org` | `60591-5` | Patient summary Document |
| `http://loinc.org` | `60592-3` | Patient summary.unexpected contact Document |
| `http://loinc.org` | `60593-1` | Medication dispensed.extended Document |
| `http://loinc.org` | `60683-0` | FDA product label Plasma derivative |
| `http://loinc.org` | `60684-8` | FDA product label Cellular therapy |
| `http://loinc.org` | `60685-5` | FDA package insert Indexing - pharmacologic class |
| `http://loinc.org` | `61143-4` | Nurse Summary note |
| `http://loinc.org` | `61146-7` | Goals Narrative |
| `http://loinc.org` | `61147-5` | Expected outcomes Narrative |
| `http://loinc.org` | `61149-1` | Objective Narrative |
| `http://loinc.org` | `61150-9` | Subjective Narrative |
| `http://loinc.org` | `61356-2` | Medication pharmaceutical advice.extended Document |
| `http://loinc.org` | `61357-0` | Medication pharmaceutical advice.brief Document |
| `http://loinc.org` | `61358-8` | Patient Surgical operation consent |
| `http://loinc.org` | `61359-6` | Patient Anesthesia consent |
| `http://loinc.org` | `62385-0` | Recommendation [interpretation] Document |
| `http://loinc.org` | `62387-6` | Interventions Narrative |
| `http://loinc.org` | `62446-0` | Renal artery - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `62447-8` | Renal artery - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `62448-6` | Head artery.left+Neck artery.left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `62449-4` | Head artery.right+Neck artery.right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `62450-2` | Fluoroscopic angiogram Guidance for placement of intraperitoneal catheter in Abdomen |
| `http://loinc.org` | `62451-0` | Extremity - left US limited |
| `http://loinc.org` | `62452-8` | Extremity - right US limited |
| `http://loinc.org` | `62491-6` | Fluoroscopic angiogram Guidance for placement of ilio-iliac tube endoprosthesis in Iliac artery - left-- W contrast IA |
| `http://loinc.org` | `62492-4` | Fluoroscopic angiogram Guidance for placement of ilio-iliac tube endoprosthesis in Iliac artery - right-- W contrast IA |
| `http://loinc.org` | `62494-0` | US Guidance for percutaneous drainage of Cavity |
| `http://loinc.org` | `63485-7` | Computer generated recommendation Document |
| `http://loinc.org` | `64051-6` | Breast lymphatics - left Scan W radionuclide intra lymphatic |
| `http://loinc.org` | `64052-4` | Breast lymphatics - right Scan W radionuclide intra lymphatic |
| `http://loinc.org` | `64053-2` | General medicine Hospital Admission evaluation note |
| `http://loinc.org` | `64054-0` | General medicine Medical student Hospital Admission evaluation note |
| `http://loinc.org` | `64055-7` | General medicine Medical student Hospital Progress note |
| `http://loinc.org` | `64056-5` | General medicine Medical student Hospital Consult note |
| `http://loinc.org` | `64057-3` | Surgery Hospital Progress note |
| `http://loinc.org` | `64058-1` | Critical Care Medicine Hospital Admission evaluation note |
| `http://loinc.org` | `64059-9` | Critical Care Medicine Hospital Progress note |
| `http://loinc.org` | `64060-7` | Thoracic surgery Hospital Admission evaluation note |
| `http://loinc.org` | `64061-5` | Thoracic surgery Hospital Progress note |
| `http://loinc.org` | `64062-3` | Pulmonary Hospital Admission evaluation note |
| `http://loinc.org` | `64063-1` | Pulmonary Hospital Progress note |
| `http://loinc.org` | `64064-9` | Pastoral care Hospital Assessment note |
| `http://loinc.org` | `64065-6` | Case manager Hospital Initial assessment note |
| `http://loinc.org` | `64066-4` | Surgery Medical student Hospital Admission evaluation note |
| `http://loinc.org` | `64067-2` | Surgery Medical student Hospital Progress note |
| `http://loinc.org` | `64068-0` | Surgery Medical student Hospital Consult note |
| `http://loinc.org` | `64069-8` | Critical care medicine Physician attending Hospital Note |
| `http://loinc.org` | `64070-6` | Critical care medicine Medical student Hospital Admission evaluation note |
| `http://loinc.org` | `64071-4` | Critical care medicine Medical student Hospital Progress note |
| `http://loinc.org` | `64072-2` | Critical care medicine Medical student Hospital Consult note |
| `http://loinc.org` | `64073-0` | Thoracic surgery Physician attending Hospital Note |
| `http://loinc.org` | `64074-8` | Thoracic surgery Medical student Hospital Admission evaluation note |
| `http://loinc.org` | `64075-5` | Thoracic surgery Medical student Hospital Progress note |
| `http://loinc.org` | `64076-3` | Thoracic surgery Medical student Hospital Consult note |
| `http://loinc.org` | `64077-1` | Pulmonary Physician attending Hospital Note |
| `http://loinc.org` | `64078-9` | Pulmonary Medical student Hospital Admission evaluation note |
| `http://loinc.org` | `64079-7` | Pulmonary Medical student Hospital Progress note |
| `http://loinc.org` | `64080-5` | Pulmonary Medical student Hospital Consult note |
| `http://loinc.org` | `64123-3` | FDA package insert Indexing - adverse reaction |
| `http://loinc.org` | `64124-1` | FDA package insert Indexing - substance |
| `http://loinc.org` | `64140-7` | Renal vessels - left Fluoroscopic angiogram W contrast |
| `http://loinc.org` | `64141-5` | Renal vessels - right Fluoroscopic angiogram W contrast |
| `http://loinc.org` | `64142-3` | Hospital Evaluation and management of smoking cessation |
| `http://loinc.org` | `64284-3` | Readiness for duty assessment |
| `http://loinc.org` | `64285-0` | Medical history screening form |
| `http://loinc.org` | `64288-4` | Prescription for eyewear |
| `http://loinc.org` | `64289-2` | Health record cover sheet |
| `http://loinc.org` | `64290-0` | Health insurance card |
| `http://loinc.org` | `64291-8` | Health insurance-related form |
| `http://loinc.org` | `64292-6` | Release of information consent |
| `http://loinc.org` | `64293-4` | Procedure consent |
| `http://loinc.org` | `64294-2` | Readiness for duty letter |
| `http://loinc.org` | `64295-9` | Nurse Plan of care note |
| `http://loinc.org` | `64296-7` | Personal health monitoring report Automated |
| `http://loinc.org` | `64297-5` | Death certificate |
| `http://loinc.org` | `64298-3` | Power of attorney |
| `http://loinc.org` | `64299-1` | Legal document |
| `http://loinc.org` | `64300-7` | Organ donation consent |
| `http://loinc.org` | `64993-9` | US Guidance for placement of needle in Unspecified body region |
| `http://loinc.org` | `64995-4` | Mammary artery.internal - left Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `64996-2` | Lung - left X-ray W contrast intrabronchial |
| `http://loinc.org` | `64997-0` | Lung - right X-ray W contrast intrabronchial |
| `http://loinc.org` | `64998-8` | Fluoroscopy Guidance for catheterization of Fallopian tube - left-- transcervical |
| `http://loinc.org` | `64999-6` | Fluoroscopy Guidance for catheterization of Fallopian tube -right-- transcervical |
| `http://loinc.org` | `65000-2` | Mammary artery.internal - right Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `65797-3` | Fluoroscopic angiogram Guidance for placement of stent in Artery - left |
| `http://loinc.org` | `65798-1` | Fluoroscopic angiogram Guidance for placement of stent in Artery - right |
| `http://loinc.org` | `65799-9` | Kidney - bilateral Fluoroscopy View for cyst examination |
| `http://loinc.org` | `65800-5` | Kidney - left Fluoroscopy View for cyst examination |
| `http://loinc.org` | `65801-3` | Kidney - right Fluoroscopy View for cyst examination |
| `http://loinc.org` | `65802-1` | Sagittal sinus and Jugular veins - left Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `65803-9` | Sagittal sinus vein - left Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `65804-7` | Sagittal sinus vein - right Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `65805-4` | Sagittal sinus and Jugular veins - right Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `65806-2` | Inhalation challenge test report Document --W methacholine inhaled |
| `http://loinc.org` | `66105-8` | FDA package insert Lot distribution data |
| `http://loinc.org` | `66106-6` | FDA package insert Pharmacogenomics section |
| `http://loinc.org` | `67796-3` | EMS patient care report - version 3.1 Document NEMSIS |
| `http://loinc.org` | `67851-6` | Admission evaluation note |
| `http://loinc.org` | `67852-4` | Hospital Admission evaluation note |
| `http://loinc.org` | `67854-0` | Geriatric medicine Education note |
| `http://loinc.org` | `67855-7` | Outpatient Education note |
| `http://loinc.org` | `67856-5` | Nursing facility History and physical note |
| `http://loinc.org` | `67860-7` | Postoperative evaluation and management note |
| `http://loinc.org` | `67861-5` | Ophthalmology Postoperative evaluation and management note |
| `http://loinc.org` | `67862-3` | Preoperative evaluation and management note |
| `http://loinc.org` | `67865-6` | Outpatient Supervisory note |
| `http://loinc.org` | `68469-6` | Pastoral care Hospital Consult note |
| `http://loinc.org` | `68470-4` | Respiratory therapy Hospital Initial assessment note |
| `http://loinc.org` | `68471-2` | Cardiology Hospital Admission evaluation note |
| `http://loinc.org` | `68472-0` | Cardiology Hospital Progress note |
| `http://loinc.org` | `68473-8` | Critical care medicine Physician attending Hospital Progress note |
| `http://loinc.org` | `68474-6` | Physician Hospital Restraint note |
| `http://loinc.org` | `68475-3` | General medicine Physician attending Hospital Progress note |
| `http://loinc.org` | `68476-1` | Nurse Hospital Restraint note |
| `http://loinc.org` | `68477-9` | Nurse Hospital Education note |
| `http://loinc.org` | `68478-7` | Pulmonary Physician attending Hospital Progress note |
| `http://loinc.org` | `68479-5` | Respiratory therapy Hospital Progress note |
| `http://loinc.org` | `68480-3` | Surgery Physician attending Hospital Progress note |
| `http://loinc.org` | `68481-1` | Thoracic surgery Physician attending Hospital Progress note |
| `http://loinc.org` | `68482-9` | Nurse Hospital Transfer summary note |
| `http://loinc.org` | `68483-7` | Cardiology Medical student Hospital Admission evaluation note |
| `http://loinc.org` | `68484-5` | Cardiology Physician attending Hospital Progress note |
| `http://loinc.org` | `68485-2` | Cardiology Medical student Hospital Progress note |
| `http://loinc.org` | `68486-0` | Cardiology Medical student Hospital Consult note |
| `http://loinc.org` | `68550-3` | Dermatology Preoperative evaluation and management note |
| `http://loinc.org` | `68551-1` | Dermatology Hospital Consult note |
| `http://loinc.org` | `68552-9` | Emergency medicine Emergency department Admission evaluation note |
| `http://loinc.org` | `68553-7` | Hematology+Medical Oncology Initial assessment note |
| `http://loinc.org` | `68554-5` | Hematology+Medical Oncology Progress note |
| `http://loinc.org` | `68555-2` | Hematology+Medical Oncology Hospital Letter |
| `http://loinc.org` | `68556-0` | Neurology Diagnostic study note |
| `http://loinc.org` | `68557-8` | Obstetrics and Gynecology Diagnostic study note |
| `http://loinc.org` | `68558-6` | Obstetrics and Gynecology Discharge summary |
| `http://loinc.org` | `68560-2` | Obstetrics and Gynecology History and physical note |
| `http://loinc.org` | `68562-8` | Obstetrics and Gynecology Preoperative evaluation and management note |
| `http://loinc.org` | `68563-6` | Obstetrics and Gynecology procedure note |
| `http://loinc.org` | `68564-4` | Obstetrics and Gynecology Progress note |
| `http://loinc.org` | `68565-1` | Obstetrics and Gynecology Transfer summary note |
| `http://loinc.org` | `68566-9` | Obstetrics and Gynecology Hospital Consult note |
| `http://loinc.org` | `68567-7` | Obstetrics and Gynecology Hospital Letter |
| `http://loinc.org` | `68569-3` | Occupational therapy Transfer summary note |
| `http://loinc.org` | `68570-1` | Occupational therapy Hospital Consult note |
| `http://loinc.org` | `68571-9` | Occupational therapy Hospital Letter |
| `http://loinc.org` | `68572-7` | Ophthalmology Discharge summary |
| `http://loinc.org` | `68573-5` | Ophthalmology History and physical note |
| `http://loinc.org` | `68574-3` | Ophthalmology Progress note |
| `http://loinc.org` | `68575-0` | Ophthalmology Hospital Consult note |
| `http://loinc.org` | `68576-8` | Ophthalmology Hospital Letter |
| `http://loinc.org` | `68577-6` | Orthopaedic surgery Diagnostic study note |
| `http://loinc.org` | `68578-4` | Orthopaedic surgery Discharge summary |
| `http://loinc.org` | `68580-0` | Orthopaedic surgery History and physical note |
| `http://loinc.org` | `68581-8` | Orthopaedic surgery Preoperative evaluation and management note |
| `http://loinc.org` | `68582-6` | Orthopaedic surgery Progress note |
| `http://loinc.org` | `68583-4` | Orthopaedic surgery Transfer summary note |
| `http://loinc.org` | `68585-9` | Orthopaedic surgery Hospital Letter |
| `http://loinc.org` | `68586-7` | Pharmacy Hospital Consult note |
| `http://loinc.org` | `68587-5` | Pharmacy Hospital Medication management note |
| `http://loinc.org` | `68590-9` | Physical therapy Hospital Consult note |
| `http://loinc.org` | `68591-7` | Plastic surgery Discharge summary |
| `http://loinc.org` | `68592-5` | Plastic surgery History and physical note |
| `http://loinc.org` | `68593-3` | Plastic surgery Letter |
| `http://loinc.org` | `68594-1` | Plastic surgery Preoperative evaluation and management note |
| `http://loinc.org` | `68595-8` | Plastic surgery Progress note |
| `http://loinc.org` | `68596-6` | Plastic surgery Transfer summary note |
| `http://loinc.org` | `68597-4` | Plastic surgery Hospital Consult note |
| `http://loinc.org` | `68598-2` | Plastic surgery Hospital Letter |
| `http://loinc.org` | `68599-0` | Psychiatry History and physical note |
| `http://loinc.org` | `68601-4` | Psychiatry Outpatient Note |
| `http://loinc.org` | `68602-2` | Radiation oncology Summary note |
| `http://loinc.org` | `68603-0` | Radiation oncology Hospital Summary note |
| `http://loinc.org` | `68604-8` | Radiology Diagnostic study note |
| `http://loinc.org` | `68605-5` | Recreational therapy Hospital Education note |
| `http://loinc.org` | `68606-3` | Surgery Hospital Postoperative evaluation and management note |
| `http://loinc.org` | `68607-1` | Progress letter |
| `http://loinc.org` | `68608-9` | Summary note |
| `http://loinc.org` | `68609-7` | Hospital Letter |
| `http://loinc.org` | `68610-5` | Hospital Postoperative evaluation and management note |
| `http://loinc.org` | `68611-3` | Adolescent medicine Diagnostic study note |
| `http://loinc.org` | `68612-1` | Adolescent medicine Discharge summary |
| `http://loinc.org` | `68614-7` | Adolescent medicine History and physical note |
| `http://loinc.org` | `68615-4` | Adolescent medicine Note |
| `http://loinc.org` | `68616-2` | Adolescent medicine Preoperative evaluation and management note |
| `http://loinc.org` | `68617-0` | Adolescent medicine Progress note |
| `http://loinc.org` | `68618-8` | Adolescent medicine Transfer summary note |
| `http://loinc.org` | `68619-6` | Adolescent medicine Hospital Consult note |
| `http://loinc.org` | `68620-4` | Adolescent medicine Hospital Letter |
| `http://loinc.org` | `68621-2` | Advanced heart failure and transplant cardiology Note |
| `http://loinc.org` | `68622-0` | Advanced heart failure and transplant cardiology History and physical note |
| `http://loinc.org` | `68623-8` | Advanced heart failure and transplant cardiology Preoperative evaluation and management note |
| `http://loinc.org` | `68624-6` | Advanced heart failure and transplant cardiology Hospital Letter |
| `http://loinc.org` | `68625-3` | Allergy and immunology Diagnostic study note |
| `http://loinc.org` | `68626-1` | Allergy and immunology Discharge summary |
| `http://loinc.org` | `68628-7` | Allergy and immunology History and physical note |
| `http://loinc.org` | `68629-5` | Allergy and immunology Note |
| `http://loinc.org` | `68630-3` | Allergy and immunology procedure note |
| `http://loinc.org` | `68631-1` | Allergy and immunology Progress note |
| `http://loinc.org` | `68632-9` | Allergy and immunology Transfer summary note |
| `http://loinc.org` | `68633-7` | Allergy and immunology Hospital Consult note |
| `http://loinc.org` | `68634-5` | Allergy and immunology Hospital Letter |
| `http://loinc.org` | `68635-2` | Audiology Diagnostic study note |
| `http://loinc.org` | `68636-0` | Audiology Note |
| `http://loinc.org` | `68637-8` | Audiology History and physical note |
| `http://loinc.org` | `68638-6` | Audiology Preoperative evaluation and management note |
| `http://loinc.org` | `68639-4` | Audiology Hospital Consult note |
| `http://loinc.org` | `68640-2` | Audiology Hospital Diagnostic study note |
| `http://loinc.org` | `68641-0` | Child and adolescent psychiatry Diagnostic study note |
| `http://loinc.org` | `68642-8` | Child and adolescent psychiatry Discharge summary |
| `http://loinc.org` | `68644-4` | Child and adolescent psychiatry History and physical note |
| `http://loinc.org` | `68645-1` | Child and adolescent psychiatry Note |
| `http://loinc.org` | `68646-9` | Child and adolescent psychiatry Progress note |
| `http://loinc.org` | `68647-7` | Child and adolescent psychiatry Transfer summary note |
| `http://loinc.org` | `68648-5` | Child and adolescent psychiatry Hospital Consult note |
| `http://loinc.org` | `68649-3` | Child and adolescent psychiatry Hospital Letter |
| `http://loinc.org` | `68650-1` | Clinical biochemical genetics Note |
| `http://loinc.org` | `68651-9` | Clinical biochemical genetics Hospital Consult note |
| `http://loinc.org` | `68652-7` | Clinical genetics Diagnostic study note |
| `http://loinc.org` | `68653-5` | Clinical genetics Discharge summary |
| `http://loinc.org` | `68655-0` | Clinical genetics History and physical note |
| `http://loinc.org` | `68656-8` | Clinical genetics Note |
| `http://loinc.org` | `68657-6` | Clinical genetics Preoperative evaluation and management note |
| `http://loinc.org` | `68658-4` | Clinical genetics procedure note |
| `http://loinc.org` | `68659-2` | Clinical genetics Progress note |
| `http://loinc.org` | `68660-0` | Clinical genetics Transfer summary note |
| `http://loinc.org` | `68661-8` | Clinical genetics Hospital Consult note |
| `http://loinc.org` | `68662-6` | Clinical genetics Hospital Letter |
| `http://loinc.org` | `68663-4` | Developmental-behavioral pediatrics Discharge summary |
| `http://loinc.org` | `68665-9` | Developmental-behavioral pediatrics History and physical note |
| `http://loinc.org` | `68666-7` | Developmental-behavioral pediatrics Note |
| `http://loinc.org` | `68667-5` | Developmental-behavioral pediatrics procedure note |
| `http://loinc.org` | `68668-3` | Developmental-behavioral pediatrics Progress note |
| `http://loinc.org` | `68669-1` | Developmental-behavioral pediatrics Transfer summary note |
| `http://loinc.org` | `68670-9` | Developmental-behavioral pediatrics Hospital Consult note |
| `http://loinc.org` | `68671-7` | Developmental-behavioral pediatrics Hospital Letter |
| `http://loinc.org` | `68672-5` | Geriatric medicine Skilled nursing facility Note |
| `http://loinc.org` | `68673-3` | Multi-specialty program Diagnostic study note |
| `http://loinc.org` | `68674-1` | Multi-specialty program Discharge summary |
| `http://loinc.org` | `68676-6` | Multi-specialty program History and physical note |
| `http://loinc.org` | `68677-4` | Multi-specialty program Note |
| `http://loinc.org` | `68678-2` | Multi-specialty program Preoperative evaluation and management note |
| `http://loinc.org` | `68679-0` | Multi-specialty program Progress note |
| `http://loinc.org` | `68680-8` | Multi-specialty program Transfer summary note |
| `http://loinc.org` | `68681-6` | Multi-specialty program Hospital Consult note |
| `http://loinc.org` | `68682-4` | Multi-specialty program Hospital Letter |
| `http://loinc.org` | `68683-2` | Neonatal perinatal medicine History and physical note |
| `http://loinc.org` | `68684-0` | Neonatal perinatal medicine Letter |
| `http://loinc.org` | `68685-7` | Neonatal perinatal medicine Hospital Consult note |
| `http://loinc.org` | `68686-5` | Neonatal perinatal medicine Hospital Letter |
| `http://loinc.org` | `68687-3` | Neurological surgery Diagnostic study note |
| `http://loinc.org` | `68688-1` | Neurological surgery Discharge summary |
| `http://loinc.org` | `68690-7` | Neurological surgery History and physical note |
| `http://loinc.org` | `68691-5` | Neurological surgery Preoperative evaluation and management note |
| `http://loinc.org` | `68692-3` | Neurological surgery procedure note |
| `http://loinc.org` | `68693-1` | Neurological surgery Progress note |
| `http://loinc.org` | `68694-9` | Neurological surgery Hospital Consult note |
| `http://loinc.org` | `68695-6` | Neurological surgery Hospital Letter |
| `http://loinc.org` | `68696-4` | Neurology with special qualifications in child neurology Diagnostic study note |
| `http://loinc.org` | `68697-2` | Neurology with special qualifications in child neurology Discharge summary |
| `http://loinc.org` | `68699-8` | Neurology with special qualifications in child neurology History and physical note |
| `http://loinc.org` | `68700-4` | Neurology with special qualifications in child neurology Note |
| `http://loinc.org` | `68701-2` | Neurology with special qualifications in child neurology Preoperative evaluation and management note |
| `http://loinc.org` | `68702-0` | Neurology with special qualifications in child neurology procedure note |
| `http://loinc.org` | `68703-8` | Neurology with special qualifications in child neurology Progress note |
| `http://loinc.org` | `68704-6` | Neurology with special qualifications in child neurology Transfer summary note |
| `http://loinc.org` | `68705-3` | Neurology with special qualifications in child neurology Hospital Consult note |
| `http://loinc.org` | `68706-1` | Neurology with special qualifications in child neurology Hospital Diagnostic study note |
| `http://loinc.org` | `68707-9` | Neurology with special qualifications in child neurology Hospital Letter |
| `http://loinc.org` | `68708-7` | Pain medicine Diagnostic study note |
| `http://loinc.org` | `68709-5` | Pain medicine Discharge summary |
| `http://loinc.org` | `68711-1` | Pain medicine History and physical note |
| `http://loinc.org` | `68713-7` | Pain medicine Preoperative evaluation and management note |
| `http://loinc.org` | `68714-5` | Pain medicine procedure note |
| `http://loinc.org` | `68715-2` | Pain medicine Transfer summary note |
| `http://loinc.org` | `68716-0` | Pain medicine Hospital Consult note |
| `http://loinc.org` | `68717-8` | Pain medicine Hospital Letter |
| `http://loinc.org` | `68718-6` | Pediatric cardiology Diagnostic study note |
| `http://loinc.org` | `68719-4` | Pediatric cardiology Discharge summary |
| `http://loinc.org` | `68721-0` | Pediatric cardiology History and physical note |
| `http://loinc.org` | `68722-8` | Pediatric cardiology Note |
| `http://loinc.org` | `68723-6` | Pediatric cardiology Preoperative evaluation and management note |
| `http://loinc.org` | `68724-4` | Pediatric cardiology procedure note |
| `http://loinc.org` | `68725-1` | Pediatric cardiology Progress note |
| `http://loinc.org` | `68726-9` | Pediatric cardiology Transfer summary note |
| `http://loinc.org` | `68727-7` | Pediatric cardiology Hospital Consult note |
| `http://loinc.org` | `68728-5` | Pediatric cardiology Hospital Letter |
| `http://loinc.org` | `68729-3` | Pediatric critical care medicine Hospital procedure note |
| `http://loinc.org` | `68731-9` | Pediatric dermatology History and physical note |
| `http://loinc.org` | `68732-7` | Pediatric dermatology Preoperative evaluation and management note |
| `http://loinc.org` | `68733-5` | Pediatric endocrinology Discharge summary |
| `http://loinc.org` | `68735-0` | Pediatric endocrinology History and physical note |
| `http://loinc.org` | `68736-8` | Pediatric endocrinology Preoperative evaluation and management note |
| `http://loinc.org` | `68737-6` | Pediatric endocrinology Transfer summary note |
| `http://loinc.org` | `68738-4` | Pediatric gastroenterology Discharge summary |
| `http://loinc.org` | `68740-0` | Pediatric gastroenterology History and physical note |
| `http://loinc.org` | `68741-8` | Pediatric gastroenterology Note |
| `http://loinc.org` | `68742-6` | Pediatric gastroenterology Preoperative evaluation and management note |
| `http://loinc.org` | `68743-4` | Pediatric gastroenterology procedure note |
| `http://loinc.org` | `68744-2` | Pediatric gastroenterology Progress note |
| `http://loinc.org` | `68745-9` | Pediatric gastroenterology Transfer summary note |
| `http://loinc.org` | `68746-7` | Pediatric gastroenterology Hospital Consult note |
| `http://loinc.org` | `68747-5` | Pediatric gastroenterology Hospital Letter |
| `http://loinc.org` | `68748-3` | Pediatric hematology-oncology Diagnostic study note |
| `http://loinc.org` | `68749-1` | Pediatric hematology-oncology Discharge summary |
| `http://loinc.org` | `68751-7` | Pediatric hematology-oncology History and physical note |
| `http://loinc.org` | `68752-5` | Pediatric hematology-oncology Note |
| `http://loinc.org` | `68753-3` | Pediatric hematology-oncology Preoperative evaluation and management note |
| `http://loinc.org` | `68754-1` | Pediatric hematology-oncology procedure note |
| `http://loinc.org` | `68755-8` | Pediatric hematology-oncology Progress note |
| `http://loinc.org` | `68756-6` | Pediatric hematology-oncology Transfer summary note |
| `http://loinc.org` | `68757-4` | Pediatric hematology-oncology Hospital Consult note |
| `http://loinc.org` | `68758-2` | Pediatric hematology-oncology Hospital Letter |
| `http://loinc.org` | `68760-8` | Pediatric infectious diseases History and physical note |
| `http://loinc.org` | `68761-6` | Pediatric infectious diseases Note |
| `http://loinc.org` | `68762-4` | Pediatric infectious diseases Preoperative evaluation and management note |
| `http://loinc.org` | `68763-2` | Pediatric infectious diseases Progress note |
| `http://loinc.org` | `68764-0` | Pediatric infectious diseases Transfer summary note |
| `http://loinc.org` | `68765-7` | Pediatric infectious diseases Hospital Consult note |
| `http://loinc.org` | `68766-5` | Pediatric infectious diseases Hospital Letter |
| `http://loinc.org` | `68767-3` | Pediatric nephrology Diagnostic study note |
| `http://loinc.org` | `68768-1` | Pediatric nephrology Discharge summary |
| `http://loinc.org` | `68770-7` | Pediatric nephrology History and physical note |
| `http://loinc.org` | `68771-5` | Pediatric nephrology Preoperative evaluation and management note |
| `http://loinc.org` | `68772-3` | Pediatric nephrology Transfer summary note |
| `http://loinc.org` | `68773-1` | Pediatric otolaryngology Discharge summary |
| `http://loinc.org` | `68775-6` | Pediatric otolaryngology History and physical note |
| `http://loinc.org` | `68776-4` | Pediatric otolaryngology Preoperative evaluation and management note |
| `http://loinc.org` | `68777-2` | Pediatric otolaryngology Transfer summary note |
| `http://loinc.org` | `68778-0` | Pediatric pulmonology Diagnostic study note |
| `http://loinc.org` | `68779-8` | Pediatric pulmonology Discharge summary |
| `http://loinc.org` | `68781-4` | Pediatric pulmonology History and physical note |
| `http://loinc.org` | `68782-2` | Pediatric pulmonology Note |
| `http://loinc.org` | `68783-0` | Pediatric pulmonology Preoperative evaluation and management note |
| `http://loinc.org` | `68784-8` | Pediatric pulmonology procedure note |
| `http://loinc.org` | `68785-5` | Pediatric pulmonology Progress note |
| `http://loinc.org` | `68786-3` | Pediatric pulmonology Transfer summary note |
| `http://loinc.org` | `68787-1` | Pediatric pulmonology Hospital Consult note |
| `http://loinc.org` | `68788-9` | Pediatric pulmonology Hospital Diagnostic study note |
| `http://loinc.org` | `68789-7` | Pediatric pulmonology Hospital Letter |
| `http://loinc.org` | `68791-3` | Pediatric rheumatology History and physical note |
| `http://loinc.org` | `68792-1` | Pediatric rheumatology Preoperative evaluation and management note |
| `http://loinc.org` | `68793-9` | Pediatric rheumatology Transfer summary note |
| `http://loinc.org` | `68794-7` | Pediatric surgery Diagnostic study note |
| `http://loinc.org` | `68795-4` | Pediatric surgery Discharge summary |
| `http://loinc.org` | `68797-0` | Pediatric surgery History and physical note |
| `http://loinc.org` | `68798-8` | Pediatric surgery Preoperative evaluation and management note |
| `http://loinc.org` | `68799-6` | Pediatric surgery procedure note |
| `http://loinc.org` | `68800-2` | Pediatric surgery Progress note |
| `http://loinc.org` | `68801-0` | Pediatric surgery Transfer summary note |
| `http://loinc.org` | `68802-8` | Pediatric surgery Hospital Consult note |
| `http://loinc.org` | `68803-6` | Pediatric surgery Hospital Letter |
| `http://loinc.org` | `68804-4` | Pediatric urology Diagnostic study note |
| `http://loinc.org` | `68805-1` | Pediatric urology Discharge summary |
| `http://loinc.org` | `68807-7` | Pediatric urology History and physical note |
| `http://loinc.org` | `68808-5` | Pediatric urology Preoperative evaluation and management note |
| `http://loinc.org` | `68809-3` | Pediatric urology procedure note |
| `http://loinc.org` | `68810-1` | Pediatric urology Progress note |
| `http://loinc.org` | `68811-9` | Pediatric urology Transfer summary note |
| `http://loinc.org` | `68812-7` | Pediatric urology Hospital Consult note |
| `http://loinc.org` | `68813-5` | Pediatric urology Hospital Letter |
| `http://loinc.org` | `68814-3` | Pediatrics Assessment note |
| `http://loinc.org` | `68815-0` | Pediatrics Discharge summary |
| `http://loinc.org` | `68817-6` | Pediatrics History and physical note |
| `http://loinc.org` | `68818-4` | Pediatrics Note |
| `http://loinc.org` | `68819-2` | Pediatrics Preoperative evaluation and management note |
| `http://loinc.org` | `68820-0` | Pediatrics procedure note |
| `http://loinc.org` | `68821-8` | Pediatrics Hospital Consult note |
| `http://loinc.org` | `68822-6` | Pediatrics Hospital Diagnostic study note |
| `http://loinc.org` | `68823-4` | Pediatrics Hospital Discharge summary |
| `http://loinc.org` | `68825-9` | Pediatrics Hospital History and physical note |
| `http://loinc.org` | `68826-7` | Pediatrics Hospital Letter |
| `http://loinc.org` | `68827-5` | Pediatrics Hospital Note |
| `http://loinc.org` | `68828-3` | Pediatrics Hospital Preoperative evaluation and management note |
| `http://loinc.org` | `68829-1` | Pediatrics Hospital procedure note |
| `http://loinc.org` | `68830-9` | Pediatrics Hospital Progress note |
| `http://loinc.org` | `68831-7` | Primary care Discharge summary |
| `http://loinc.org` | `68833-3` | Primary care History and physical note |
| `http://loinc.org` | `68834-1` | Primary care Note |
| `http://loinc.org` | `68835-8` | Primary care Preoperative evaluation and management note |
| `http://loinc.org` | `68836-6` | Primary care procedure note |
| `http://loinc.org` | `68837-4` | Primary care Hospital Consult note |
| `http://loinc.org` | `68838-2` | Primary care Hospital Letter |
| `http://loinc.org` | `68839-0` | Research Note |
| `http://loinc.org` | `68840-8` | Research Progress note |
| `http://loinc.org` | `68841-6` | Speech-language pathology Discharge summary |
| `http://loinc.org` | `68843-2` | Speech-language pathology History and physical note |
| `http://loinc.org` | `68844-0` | Speech-language pathology Preoperative evaluation and management note |
| `http://loinc.org` | `68846-5` | Speech-language pathology Hospital Consult note |
| `http://loinc.org` | `68847-3` | Speech-language pathology Hospital Letter |
| `http://loinc.org` | `68848-1` | Transplant surgery Note |
| `http://loinc.org` | `68849-9` | Transplant surgery History and physical note |
| `http://loinc.org` | `68850-7` | Transplant surgery Preoperative evaluation and management note |
| `http://loinc.org` | `68851-5` | Transplant surgery procedure note |
| `http://loinc.org` | `68852-3` | Transplant surgery Hospital Consult note |
| `http://loinc.org` | `68853-1` | Transplant surgery Hospital Letter |
| `http://loinc.org` | `68854-9` | Pediatric rehabilitation medicine Note |
| `http://loinc.org` | `68855-6` | Pediatric transplant hepatology Diagnostic study note |
| `http://loinc.org` | `68856-4` | Pediatric transplant hepatology Discharge summary |
| `http://loinc.org` | `68858-0` | Pediatric transplant hepatology History and physical note |
| `http://loinc.org` | `68859-8` | Pediatric transplant hepatology Note |
| `http://loinc.org` | `68860-6` | Pediatric transplant hepatology Preoperative evaluation and management note |
| `http://loinc.org` | `68861-4` | Pediatric transplant hepatology procedure note |
| `http://loinc.org` | `68862-2` | Pediatric transplant hepatology Progress note |
| `http://loinc.org` | `68863-0` | Pediatric transplant hepatology Transfer summary note |
| `http://loinc.org` | `68864-8` | Pediatric transplant hepatology Hospital Consult note |
| `http://loinc.org` | `68865-5` | Pediatric transplant hepatology Hospital Letter |
| `http://loinc.org` | `68866-3` | Pediatric nephrology Letter |
| `http://loinc.org` | `68867-1` | Pediatric nephrology Note |
| `http://loinc.org` | `68868-9` | Pediatric nephrology procedure note |
| `http://loinc.org` | `68869-7` | Pediatric nephrology Hospital Consult note |
| `http://loinc.org` | `68870-5` | Pediatric nephrology Hospital Letter |
| `http://loinc.org` | `68871-3` | Pediatric otolaryngology Note |
| `http://loinc.org` | `68872-1` | Pediatric otolaryngology procedure note |
| `http://loinc.org` | `68873-9` | Pediatric otolaryngology Progress note |
| `http://loinc.org` | `68874-7` | Pediatric otolaryngology Hospital Consult note |
| `http://loinc.org` | `68875-4` | Pediatric otolaryngology Hospital Letter |
| `http://loinc.org` | `68876-2` | Pediatric rheumatology Note |
| `http://loinc.org` | `68877-0` | Pediatric rheumatology procedure note |
| `http://loinc.org` | `68878-8` | Pediatric rheumatology Progress note |
| `http://loinc.org` | `68879-6` | Pediatric rheumatology Hospital Consult note |
| `http://loinc.org` | `68880-4` | Pediatric rheumatology Hospital Letter |
| `http://loinc.org` | `68881-2` | Pediatric surgery Note |
| `http://loinc.org` | `68882-0` | Pediatric urology Note |
| `http://loinc.org` | `68883-8` | Pediatrics Transfer summary note |
| `http://loinc.org` | `68884-6` | Pediatrics Hospital Transfer summary note |
| `http://loinc.org` | `68887-9` | Ophthalmology Transfer summary note |
| `http://loinc.org` | `68889-5` | Pediatric dermatology Note |
| `http://loinc.org` | `68890-3` | Pediatric dermatology procedure note |
| `http://loinc.org` | `68891-1` | Pediatric dermatology Progress note |
| `http://loinc.org` | `68892-9` | Pediatric dermatology Hospital Consult note |
| `http://loinc.org` | `68893-7` | Pediatric dermatology Hospital Letter |
| `http://loinc.org` | `68894-5` | Pediatric endocrinology Note |
| `http://loinc.org` | `68895-2` | Pediatric endocrinology procedure note |
| `http://loinc.org` | `68896-0` | Pediatric endocrinology Progress note |
| `http://loinc.org` | `68897-8` | Pediatric endocrinology Hospital Consult note |
| `http://loinc.org` | `68898-6` | Pediatric endocrinology Hospital Letter |
| `http://loinc.org` | `69054-5` | Aortic arch Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `69055-2` | Acromioclavicular joint - bilateral X-ray WO weight |
| `http://loinc.org` | `69056-0` | Elbow - bilateral X-ray and obliques |
| `http://loinc.org` | `69057-8` | Hand - bilateral X-ray AP and lateral and oblique |
| `http://loinc.org` | `69058-6` | Hip - bilateral X-ray 2 views |
| `http://loinc.org` | `69059-4` | Hip - bilateral X-ray and lateral crosstable |
| `http://loinc.org` | `69060-2` | Knee - bilateral X-ray 2 views and Sunrise |
| `http://loinc.org` | `69061-0` | Knee - bilateral X-ray 2 views and tunnel |
| `http://loinc.org` | `69062-8` | Knee - bilateral X-ray 4 views standing |
| `http://loinc.org` | `69063-6` | Knee - bilateral X-ray 4 views and Sunrise and tunnel |
| `http://loinc.org` | `69064-4` | Knee - bilateral X-ray Sunrise and (views standing) |
| `http://loinc.org` | `69065-1` | Abdomen X-ray AP and lateral crosstable |
| `http://loinc.org` | `69066-9` | Abdominal vessels Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `69067-7` | Unspecified body region Fluoroscopic angiogram Angioplasty W contrast |
| `http://loinc.org` | `69068-5` | Mammogram Guidance for needle localization of Breast - bilateral |
| `http://loinc.org` | `69069-3` | Patella - bilateral X-ray Sunrise |
| `http://loinc.org` | `69070-1` | Ribs - bilateral X-ray anterior and lateral |
| `http://loinc.org` | `69071-9` | Ribs - bilateral and Chest X-ray |
| `http://loinc.org` | `69072-7` | Wrist - bilateral X-ray ulnar deviation and radial deviation |
| `http://loinc.org` | `69073-5` | Fluoroscopy Guidance for core needle biopsy of Unspecified body region |
| `http://loinc.org` | `69074-3` | Fluoroscopy Guidance for biopsy of Pelvis |
| `http://loinc.org` | `69075-0` | Fluoroscopy Guidance for biopsy of Salivary gland |
| `http://loinc.org` | `69076-8` | Fluoroscopy Guidance for biopsy of Bone |
| `http://loinc.org` | `69077-6` | Brachiocephalic artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `69078-4` | Fluoroscopy Guidance for drainage of Chest |
| `http://loinc.org` | `69079-2` | Clavicle X-ray 45 degree cephalic angle |
| `http://loinc.org` | `69080-0` | Spine Cervical X-ray 5 views W flexion and W extension |
| `http://loinc.org` | `69081-8` | Spine Cervical X-ray 5 views and Swimmers |
| `http://loinc.org` | `69082-6` | Head CT and 3D reconstruction WO contrast |
| `http://loinc.org` | `69083-4` | CT Guidance for biopsy of Abdomen-- WO contrast |
| `http://loinc.org` | `69084-2` | Chest vessels CT angiogram WO contrast |
| `http://loinc.org` | `69085-9` | Renal vessels CT angiogram W and WO contrast |
| `http://loinc.org` | `69086-7` | Aorta CT W and WO contrast |
| `http://loinc.org` | `69087-5` | Ankle - bilateral CT WO contrast |
| `http://loinc.org` | `69088-3` | Knee - bilateral CT W contrast IV |
| `http://loinc.org` | `69089-1` | Knee - bilateral CT WO contrast |
| `http://loinc.org` | `69090-9` | Shoulder - bilateral CT WO contrast |
| `http://loinc.org` | `69091-7` | Wrist - bilateral CT W contrast IV |
| `http://loinc.org` | `69092-5` | CT Guidance for biopsy of Liver-- WO contrast |
| `http://loinc.org` | `69093-3` | CT Guidance for biopsy of Pelvis-- W contrast IV |
| `http://loinc.org` | `69094-1` | CT Guidance for biopsy of Pelvis-- WO contrast |
| `http://loinc.org` | `69095-8` | Bladder CT W contrast IV |
| `http://loinc.org` | `69096-6` | Chest CT limited W contrast IV |
| `http://loinc.org` | `69097-4` | CT Guidance for needle biopsy of Liver |
| `http://loinc.org` | `69098-2` | CT Guidance for needle biopsy of Muscle |
| `http://loinc.org` | `69099-0` | CT Guidance for needle biopsy of Chest.pleura |
| `http://loinc.org` | `69100-6` | CT Guidance for needle biopsy of Salivary gland |
| `http://loinc.org` | `69101-4` | CT Guidance for needle biopsy of Thyroid |
| `http://loinc.org` | `69102-2` | Ankle - left CT W contrast intraarticular |
| `http://loinc.org` | `69103-0` | Elbow - left CT W contrast intraarticular |
| `http://loinc.org` | `69104-8` | Extremity - left CT WO contrast |
| `http://loinc.org` | `69105-5` | Hip - left CT W contrast intraarticular |
| `http://loinc.org` | `69106-3` | Knee - left CT W contrast intraarticular |
| `http://loinc.org` | `69107-1` | Wrist - left CT W contrast intraarticular |
| `http://loinc.org` | `69108-9` | Pulmonary vessels CT angiogram W and WO contrast |
| `http://loinc.org` | `69109-7` | Ankle - right CT W contrast intraarticular |
| `http://loinc.org` | `69110-5` | Elbow - right CT W contrast intraarticular |
| `http://loinc.org` | `69111-3` | Extremity - right CT WO contrast |
| `http://loinc.org` | `69112-1` | Hip - right CT W contrast intraarticular |
| `http://loinc.org` | `69113-9` | Kidney - right CT |
| `http://loinc.org` | `69114-7` | Knee - right CT W contrast intraarticular |
| `http://loinc.org` | `69115-4` | Wrist - right CT W contrast intraarticular |
| `http://loinc.org` | `69116-2` | Sacrum and Coccyx CT |
| `http://loinc.org` | `69117-0` | Scapula CT |
| `http://loinc.org` | `69118-8` | Scapula CT WO contrast |
| `http://loinc.org` | `69119-6` | Aorta thoracic CT angiogram WO contrast |
| `http://loinc.org` | `69120-4` | Fluoroscopy Guidance for abscess drainage of Neck |
| `http://loinc.org` | `69121-2` | Fluoroscopy Guidance for aspiration of cyst of Ovary |
| `http://loinc.org` | `69122-0` | Fluoroscopy Guidance for abscess drainage of Pancreas |
| `http://loinc.org` | `69123-8` | Fluoroscopy Guidance for abscess drainage of Pleural space |
| `http://loinc.org` | `69124-6` | Fluoroscopy Guidance for fine needle aspiration of Superficial tissue |
| `http://loinc.org` | `69125-3` | Fluoroscopy Guidance for needle biopsy of Liver |
| `http://loinc.org` | `69126-1` | Fluoroscopy Guidance for needle biopsy of Pancreas |
| `http://loinc.org` | `69127-9` | Fluoroscopy Guidance for needle biopsy of Chest.pleura |
| `http://loinc.org` | `69128-7` | Fluoroscopy Guidance for needle biopsy of Salivary gland |
| `http://loinc.org` | `69129-5` | Fluoroscopy Guidance for needle biopsy of Thyroid |
| `http://loinc.org` | `69130-3` | Hand X-ray AP and lateral |
| `http://loinc.org` | `69131-1` | Hip X-ray and Danelius Miller |
| `http://loinc.org` | `69132-9` | Hip X-ray Danelius Miller |
| `http://loinc.org` | `69133-7` | Fluoroscopy Guidance for drainage of Hip |
| `http://loinc.org` | `69134-5` | Fluoroscopic angiogram Guidance for placement of stent in Iliac artery |
| `http://loinc.org` | `69135-2` | Iliac artery Fluoroscopic angiogram Atherectomy W contrast |
| `http://loinc.org` | `69136-0` | Knee X-ray Sunrise and tunnel |
| `http://loinc.org` | `69137-8` | Ankle - left X-ray AP and lateral and oblique standing |
| `http://loinc.org` | `69138-6` | Ankle - left X-ray 3 views standing |
| `http://loinc.org` | `69139-4` | Hip - left X-ray and lateral crosstable |
| `http://loinc.org` | `69140-2` | Hip - left X-ray and Danelius Miller |
| `http://loinc.org` | `69141-0` | Hip - left X-ray Danelius Miller |
| `http://loinc.org` | `69142-8` | Knee - left X-ray 2 views and Sunrise |
| `http://loinc.org` | `69143-6` | Knee - left X-ray 2 views and tunnel standing |
| `http://loinc.org` | `69144-4` | Knee - left X-ray 4 views and AP standing |
| `http://loinc.org` | `69145-1` | Knee - left X-ray 4 views and tunnel |
| `http://loinc.org` | `69146-9` | Knee - left X-ray AP and lateral crosstable |
| `http://loinc.org` | `69147-7` | Knee - left X-ray AP and lateral and right oblique and left oblique |
| `http://loinc.org` | `69148-5` | Knee - left X-ray and tunnel |
| `http://loinc.org` | `69149-3` | Knee - left X-ray Sunrise and (views standing) |
| `http://loinc.org` | `69150-1` | Breast implant - left Mammogram diagnostic |
| `http://loinc.org` | `69151-9` | Wrist - left X-ray 3 views scaphoid |
| `http://loinc.org` | `69152-7` | Patella - left X-ray Single view |
| `http://loinc.org` | `69153-5` | Shoulder - left X-ray AP and Grashey and axillary |
| `http://loinc.org` | `69154-3` | Shoulder - left X-ray 3 views and axillary |
| `http://loinc.org` | `69155-0` | Shoulder - left X-ray 3 views and Y |
| `http://loinc.org` | `69156-8` | Shoulder - left X-ray Grashey and Y |
| `http://loinc.org` | `69157-6` | Wrist - left X-ray lateral W flexion and W extension |
| `http://loinc.org` | `69158-4` | Breast implant X-ray diagnostic |
| `http://loinc.org` | `69159-2` | Breast implant X-ray screening |
| `http://loinc.org` | `69160-0` | Mammogram Guidance.stereotactic for needle biopsy of Breast |
| `http://loinc.org` | `69161-8` | Circle of Willis MRI angiogram W and WO contrast IV |
| `http://loinc.org` | `69162-6` | Pulmonary artery - bilateral MRI angiogram W contrast IA |
| `http://loinc.org` | `69163-4` | Ankle - bilateral MRI W contrast IV |
| `http://loinc.org` | `69164-2` | Ankle - bilateral MRI WO contrast |
| `http://loinc.org` | `69165-9` | Breast implant - bilateral MRI |
| `http://loinc.org` | `69166-7` | Breast implant - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `69167-5` | Breast implant - bilateral MRI W contrast IV |
| `http://loinc.org` | `69168-3` | Breast implant - bilateral MRI WO contrast |
| `http://loinc.org` | `69169-1` | MRI Guidance for biopsy of Breast - bilateral |
| `http://loinc.org` | `69170-9` | Elbow - bilateral MRI W contrast IV |
| `http://loinc.org` | `69171-7` | Elbow - bilateral MRI WO contrast |
| `http://loinc.org` | `69172-5` | Femur - bilateral MRI W contrast IV |
| `http://loinc.org` | `69173-3` | Femur - bilateral MRI WO contrast |
| `http://loinc.org` | `69174-1` | Forearm - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `69175-8` | Forearm - bilateral MRI W contrast IV |
| `http://loinc.org` | `69176-6` | Forearm - bilateral MRI WO contrast |
| `http://loinc.org` | `69177-4` | Hand - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `69178-2` | Hand - bilateral MRI W contrast IV |
| `http://loinc.org` | `69179-0` | Hand - bilateral MRI WO contrast |
| `http://loinc.org` | `69180-8` | Upper arm - bilateral MRI |
| `http://loinc.org` | `69181-6` | Upper arm - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `69182-4` | Upper arm - bilateral MRI W contrast IV |
| `http://loinc.org` | `69183-2` | Upper arm - bilateral MRI WO contrast |
| `http://loinc.org` | `69184-0` | Shoulder - bilateral MRI W contrast IV |
| `http://loinc.org` | `69185-7` | Lower leg - bilateral MRI WO contrast |
| `http://loinc.org` | `69186-5` | Upper extremity - bilateral MRI W and WO contrast IV |
| `http://loinc.org` | `69187-3` | Upper extremity - bilateral MRI W contrast IV |
| `http://loinc.org` | `69188-1` | Upper extremity - bilateral MRI WO contrast |
| `http://loinc.org` | `69189-9` | Breast implant MRI W and WO contrast IV |
| `http://loinc.org` | `69190-7` | Breast implant MRI W contrast IV |
| `http://loinc.org` | `69191-5` | Breast implant MRI WO contrast |
| `http://loinc.org` | `69192-3` | MRI Guidance for aspiration of cyst of Breast |
| `http://loinc.org` | `69193-1` | Extremity MRI |
| `http://loinc.org` | `69194-9` | Finger MRI W and WO contrast IV |
| `http://loinc.org` | `69195-6` | Finger MRI W contrast IV |
| `http://loinc.org` | `69196-4` | Finger MRI WO contrast |
| `http://loinc.org` | `69197-2` | MRI Guidance for needle biopsy of Liver |
| `http://loinc.org` | `69198-0` | MRI Guidance for needle biopsy of Muscle |
| `http://loinc.org` | `69199-8` | MRI Guidance for needle biopsy of Pancreas |
| `http://loinc.org` | `69200-4` | MRI Guidance for needle biopsy of Pleura |
| `http://loinc.org` | `69201-2` | MRI Guidance for needle biopsy of Salivary gland |
| `http://loinc.org` | `69202-0` | MRI Guidance for needle biopsy of Thyroid |
| `http://loinc.org` | `69203-8` | MRI Guidance for biopsy of Breast - left |
| `http://loinc.org` | `69204-6` | Finger - left MRI W and WO contrast IV |
| `http://loinc.org` | `69205-3` | Finger - left MRI W contrast IV |
| `http://loinc.org` | `69206-1` | Finger - left MRI WO contrast |
| `http://loinc.org` | `69207-9` | Hip - left MRI W and WO contrast intraarticular |
| `http://loinc.org` | `69208-7` | Shoulder - left MRI W and WO contrast intraarticular |
| `http://loinc.org` | `69209-5` | Wrist - left and Hand - left MRI |
| `http://loinc.org` | `69210-3` | Lower Extremity Joint MRI W contrast intraarticular |
| `http://loinc.org` | `69211-1` | Nasal bones MRI |
| `http://loinc.org` | `69212-9` | Pelvis MRI limited |
| `http://loinc.org` | `69213-7` | MRI Guidance for biopsy of Breast - right |
| `http://loinc.org` | `69214-5` | Finger - right MRI W and WO contrast IV |
| `http://loinc.org` | `69215-2` | Finger - right MRI W contrast IV |
| `http://loinc.org` | `69216-0` | Finger - right MRI WO contrast |
| `http://loinc.org` | `69217-8` | Hip - right MRI W and WO contrast intraarticular |
| `http://loinc.org` | `69218-6` | Shoulder - right MRI W and WO contrast intraarticular |
| `http://loinc.org` | `69219-4` | Wrist - right and Hand - right MRI |
| `http://loinc.org` | `69220-2` | Skull.base MRI W and WO contrast IV |
| `http://loinc.org` | `69221-0` | Scrotum and Testicle MRI W contrast IV |
| `http://loinc.org` | `69222-8` | Vena cava MRI |
| `http://loinc.org` | `69223-6` | Unspecified body region MRI WO contrast |
| `http://loinc.org` | `69224-4` | Fluoroscopy Guidance for needle biopsy of Abdomen |
| `http://loinc.org` | `69225-1` | Fluoroscopy Guidance for needle biopsy of Chest |
| `http://loinc.org` | `69226-9` | Fluoroscopy Guidance for needle biopsy of Muscle |
| `http://loinc.org` | `69227-7` | Fluoroscopy Guidance for needle biopsy of Pleura |
| `http://loinc.org` | `69228-5` | Fluoroscopy Guidance for needle biopsy of Prostate |
| `http://loinc.org` | `69229-3` | Liver SPECT W Tc-99m SC IV |
| `http://loinc.org` | `69230-1` | Liver Scan W Tc-99m SC IV |
| `http://loinc.org` | `69231-9` | Heart Scan W stress and W Tc-99m IV |
| `http://loinc.org` | `69232-7` | Heart Scan W stress and W Tc-99m Sestamibi IV |
| `http://loinc.org` | `69233-5` | Parotid gland Scan W Tc-99m pertechnetate IV |
| `http://loinc.org` | `69234-3` | Spleen SPECT W Tc-99m tagged RBC IV |
| `http://loinc.org` | `69235-0` | Scrotum and Testicle SPECT flow |
| `http://loinc.org` | `69236-8` | Thyroid Scan and uptake W I-131 PO |
| `http://loinc.org` | `69237-6` | SPECT for tumor whole body |
| `http://loinc.org` | `69238-4` | Urinary Bladder and Urethra SPECT W contrast intra bladder during voiding |
| `http://loinc.org` | `69239-2` | Patella X-ray Sunrise |
| `http://loinc.org` | `69240-0` | Fluoroscopy Guidance for percutaneous biopsy of Abdomen |
| `http://loinc.org` | `69241-8` | Fluoroscopy Guidance for percutaneous drainage of abscess of Abdomen |
| `http://loinc.org` | `69242-6` | Fluoroscopy Guidance for percutaneous drainage of abscess of Appendix |
| `http://loinc.org` | `69243-4` | Fluoroscopy Guidance for percutaneous drainage of abscess of Lung |
| `http://loinc.org` | `69244-2` | Fluoroscopy Guidance for percutaneous drainage of abscess of Pelvis |
| `http://loinc.org` | `69245-9` | Fluoroscopy Guidance for percutaneous needle biopsy of Kidney |
| `http://loinc.org` | `69246-7` | Fluoroscopy Guidance for percutaneous needle biopsy of Liver |
| `http://loinc.org` | `69247-5` | Fluoroscopy Guidance for percutaneous needle biopsy of Salivary gland |
| `http://loinc.org` | `69248-3` | Renal artery Fluoroscopic angiogram Percutaneous transluminal angioplasty of vessel W contrast IA |
| `http://loinc.org` | `69249-1` | Popliteal artery Fluoroscopic angiogram W contrast IA |
| `http://loinc.org` | `69250-9` | Portal vein Fluoroscopic angiogram W contrast IV |
| `http://loinc.org` | `69251-7` | Breast Mammogram Post Wire Placement |
| `http://loinc.org` | `69252-5` | Pulmonary artery Fluoroscopic angiogram Percutaneous transluminal angioplasty of vessel W contrast IA |
| `http://loinc.org` | `69253-3` | Renal vessels Fluoroscopic angiogram Atherectomy W contrast |
| `http://loinc.org` | `69254-1` | Ankle - right X-ray 3 views standing |
| `http://loinc.org` | `69255-8` | Knee - right X-ray Sunrise and tunnel standing |
| `http://loinc.org` | `69256-6` | Knee - right X-ray Sunrise |
| `http://loinc.org` | `69257-4` | Lower extremity - right X-ray 2 views |
| `http://loinc.org` | `69258-2` | Lower extremity - right X-ray AP and lateral |
| `http://loinc.org` | `69259-0` | Breast implant - right Mammogram diagnostic |
| `http://loinc.org` | `69260-8` | Patella - right X-ray Single view |
| `http://loinc.org` | `69261-6` | Patella - right X-ray 3 views |
| `http://loinc.org` | `69262-4` | Shoulder - right X-ray AP and Grashey and axillary |
| `http://loinc.org` | `69263-2` | Wrist - right X-ray PA W clenched fist |
| `http://loinc.org` | `69264-0` | Sacrum X-ray standing |
| `http://loinc.org` | `69265-7` | Shoulder X-ray 4 views |
| `http://loinc.org` | `69266-5` | Shoulder X-ray AP and Y |
| `http://loinc.org` | `69267-3` | Shoulder X-ray Grashey and axillary and Y |
| `http://loinc.org` | `69268-1` | Breast duct Mammogram Single view W contrast intra duct |
| `http://loinc.org` | `69269-9` | Skull X-ray AP single view |
| `http://loinc.org` | `69270-7` | Skull X-ray PA |
| `http://loinc.org` | `69271-5` | Skull X-ray PA and lateral and Waters and Towne |
| `http://loinc.org` | `69272-3` | Small bowel Fluoroscopy W contrast via ileostomy |
| `http://loinc.org` | `69273-1` | Spine Thoracolumbar Junction X-ray 2 views |
| `http://loinc.org` | `69274-9` | Spine Thoracic X-ray 2 views standing |
| `http://loinc.org` | `69275-6` | Spine Thoracic X-ray standing |
| `http://loinc.org` | `69276-4` | Aorta abdominal US |
| `http://loinc.org` | `69277-2` | Adrenal gland US |
| `http://loinc.org` | `69278-0` | US Guidance for aspiration of Breast - bilateral |
| `http://loinc.org` | `69279-8` | US Guidance for core needle biopsy of Lymph node |
| `http://loinc.org` | `69280-6` | Bladder US limited |
| `http://loinc.org` | `69281-4` | Chest US limited |
| `http://loinc.org` | `69282-2` | Unspecified body region US.doppler limited |
| `http://loinc.org` | `69283-0` | Extremity veins - bilateral US.doppler |
| `http://loinc.org` | `69284-8` | Portal vein and Hepatic vein US.doppler |
| `http://loinc.org` | `69285-5` | Umbilical artery US.doppler |
| `http://loinc.org` | `69286-3` | Eye US limited |
| `http://loinc.org` | `69287-1` | US Guidance for aspiration of Lymph node |
| `http://loinc.org` | `69288-9` | US Guidance for needle biopsy of Muscle |
| `http://loinc.org` | `69289-7` | US Guidance for needle biopsy of Pancreas |
| `http://loinc.org` | `69290-5` | US Guidance for needle biopsy of Breast - right |
| `http://loinc.org` | `69291-3` | US Guidance for needle biopsy of Salivary gland |
| `http://loinc.org` | `69292-1` | US Guidance for aspiration of Breast - left |
| `http://loinc.org` | `69293-9` | Extremity artery - left US |
| `http://loinc.org` | `69294-7` | Renal artery US |
| `http://loinc.org` | `69295-4` | Renal vessels US |
| `http://loinc.org` | `69296-2` | US Guidance for aspiration of Breast - right |
| `http://loinc.org` | `69297-0` | Extremity artery - right US |
| `http://loinc.org` | `69298-8` | Salivary gland US |
| `http://loinc.org` | `69299-6` | Scrotum and Testicle US limited |
| `http://loinc.org` | `69300-2` | Kidney transplant US limited |
| `http://loinc.org` | `69301-0` | Upper extremity vein Fluoroscopic angiogram Percutaneous transluminal angioplasty of vessel W contrast IV |
| `http://loinc.org` | `69302-8` | Wrist X-ray W clenched fist |
| `http://loinc.org` | `69303-6` | Wrist X-ray ulnar deviation and radial deviation |
| `http://loinc.org` | `69304-4` | Wrist X-ray ulnar deviation |
| `http://loinc.org` | `69305-1` | Zygomatic arch X-ray 2 views |
| `http://loinc.org` | `69306-9` | Fluoroscopy Guidance for aspiration of cyst of Bone |
| `http://loinc.org` | `69307-7` | Ankle - left X-ray Single view |
| `http://loinc.org` | `69308-5` | Elbow - left X-ray Single view |
| `http://loinc.org` | `69309-3` | Foot - left X-ray Single view |
| `http://loinc.org` | `69310-1` | Hand - left X-ray Single view |
| `http://loinc.org` | `69311-9` | Calcaneus - left X-ray Single view |
| `http://loinc.org` | `69312-7` | Humerus - left X-ray Single view |
| `http://loinc.org` | `69313-5` | Tibia - left and Fibula - left X-ray Single view |
| `http://loinc.org` | `69314-3` | Ankle - right X-ray Single view |
| `http://loinc.org` | `69315-0` | Elbow - right X-ray Single view |
| `http://loinc.org` | `69316-8` | Foot - right X-ray Single view |
| `http://loinc.org` | `69317-6` | Radius - right and Ulna - right X-ray Single view |
| `http://loinc.org` | `69318-4` | Hand - right X-ray Single view |
| `http://loinc.org` | `69319-2` | Calcaneus - right X-ray Single view |
| `http://loinc.org` | `69320-0` | Humerus - right X-ray Single view |
| `http://loinc.org` | `69321-8` | Tibia - right and Fibula - right X-ray Single view |
| `http://loinc.org` | `69385-3` | Lower extremity veins - bilateral US |
| `http://loinc.org` | `69387-9` | US Guidance for biopsy of Epididymis |
| `http://loinc.org` | `69388-7` | Urinary bladder US post void |
| `http://loinc.org` | `69389-5` | Femoral artery and Popliteal artery US |
| `http://loinc.org` | `69390-3` | Ovary US |
| `http://loinc.org` | `69391-1` | US Guidance for cordocentesis |
| `http://loinc.org` | `69392-9` | Lower extremity veins - left US |
| `http://loinc.org` | `69393-7` | Spine Lumbar US |
| `http://loinc.org` | `69394-5` | Mesenteric artery US |
| `http://loinc.org` | `69395-2` | Upper extremity veins US |
| `http://loinc.org` | `69396-0` | US Guidance for biopsy of Spinal cord |
| `http://loinc.org` | `69397-8` | Breast vessels US.doppler |
| `http://loinc.org` | `69398-6` | Extremity vessels Left US.doppler |
| `http://loinc.org` | `69399-4` | Femoral vein and Popliteal vein US |
| `http://loinc.org` | `69400-0` | US Guidance for chorionic villus sampling |
| `http://loinc.org` | `69401-8` | US Guidance for needle biopsy of Spinal cord |
| `http://loinc.org` | `69402-6` | Kidney Bilateral and Bladder US |
| `http://loinc.org` | `69409-1` | U.S. standard certificate of death - 2003 revision |
| `http://loinc.org` | `69438-0` | Referral note Forensic medicine |
| `http://loinc.org` | `69669-0` | Population stratification description Narrative |
| `http://loinc.org` | `69670-8` | Health quality measure supplemental data Narrative |
| `http://loinc.org` | `69718-5` | FDA product label Statement of identity section |
| `http://loinc.org` | `69719-3` | FDA product label Health claim section |
| `http://loinc.org` | `69730-0` | Instructions [Text] Narrative |
| `http://loinc.org` | `69758-1` | FDA package insert Diagram of device |
| `http://loinc.org` | `69759-9` | FDA package insert Risks |
| `http://loinc.org` | `69760-7` | FDA package insert Compatible accessories |
| `http://loinc.org` | `69761-5` | FDA package insert Alarms |
| `http://loinc.org` | `69762-3` | FDA package insert Troubleshooting |
| `http://loinc.org` | `69763-1` | FDA package insert Disposal and waste handling |
| `http://loinc.org` | `69764-9` | Document type |
| `http://loinc.org` | `69799-5` | 21-Deoxycorticosterone [Moles/volume] in Serum or Plasma |
| `http://loinc.org` | `69908-2` | Abdominal vessels and Pelvis vessels CT angiogram W contrast IV |
| `http://loinc.org` | `69981-9` | Asthma action plan |
| `http://loinc.org` | `70004-7` | Diagnostic study note |
| `http://loinc.org` | `70005-4` | Evaluation and management of smoking cessation |
| `http://loinc.org` | `70006-2` | Medication management note |
| `http://loinc.org` | `70007-0` | Restraint note |
| `http://loinc.org` | `70238-1` | Transplant surgery Hospital Progress note |
| `http://loinc.org` | `70915-4` | US Guidance for CSF aspiration of Spine Cervical |
| `http://loinc.org` | `70916-2` | US Guidance for CSF aspiration of Spine Lumbar |
| `http://loinc.org` | `70917-0` | US Guidance for CSF aspiration of Spine Thoracic |
| `http://loinc.org` | `70918-8` | Fluoroscopy Guidance for injection of Spine Cervical |
| `http://loinc.org` | `70919-6` | Fluoroscopy Guidance for injection of Spine Lumbar |
| `http://loinc.org` | `70920-4` | Fluoroscopy Guidance for injection of Spine Thoracic |
| `http://loinc.org` | `70921-2` | CT Guidance for nerve block of Spine Cervical |
| `http://loinc.org` | `70922-0` | CT Guidance for nerve block of Spine Thoracic |
| `http://loinc.org` | `70923-8` | Fluoroscopy Guidance for percutaneous vertebroplasty of Spine Cervical |
| `http://loinc.org` | `70924-6` | Fluoroscopy Guidance for percutaneous vertebroplasty of Spine Lumbar |
| `http://loinc.org` | `70925-3` | Fluoroscopy Guidance for percutaneous vertebroplasty of Spine Thoracic |
| `http://loinc.org` | `70926-1` | Spine Cervical US |
| `http://loinc.org` | `70927-9` | Spine Thoracic US |
| `http://loinc.org` | `70928-7` | Spine Lumbar CT stereotactic |
| `http://loinc.org` | `70929-5` | Spine Cervical CT stereotactic |
| `http://loinc.org` | `70930-3` | Spine Thoracic CT stereotactic |
| `http://loinc.org` | `70931-1` | Spine Thoracic CT W contrast intradisc |
| `http://loinc.org` | `70932-9` | Spine Thoracic X-ray Single view portable |
| `http://loinc.org` | `70933-7` | Spine Thoracic Fluoroscopy W contrast intradisc |
| `http://loinc.org` | `70934-5` | Ocular history Narrative |
| `http://loinc.org` | `70935-2` | Ophthalmic medications Narrative |
| `http://loinc.org` | `70936-0` | Vision testing Narrative |
| `http://loinc.org` | `70938-6` | Refractive measurements Narrative |
| `http://loinc.org` | `70939-4` | Lensometry measurements Narrative |
| `http://loinc.org` | `70940-2` | Confrontation visual field Narrative |
| `http://loinc.org` | `70941-0` | Eye external Narrative |
| `http://loinc.org` | `70942-8` | Ocular alignment and motility Narrative |
| `http://loinc.org` | `70943-6` | Eye anterior segment Narrative |
| `http://loinc.org` | `70944-4` | Eye posterior segment Narrative |
| `http://loinc.org` | `70945-1` | Lacrimal Narrative |
| `http://loinc.org` | `70946-9` | Ancillary eye tests Narrative |
| `http://loinc.org` | `70948-5` | Ocular physical exam Narrative |
| `http://loinc.org` | `70949-3` | Pathology report.section heading |
| `http://loinc.org` | `71230-7` | Birth certificate Document |
| `http://loinc.org` | `71388-3` | CMS - physical exam panel |
| `http://loinc.org` | `71406-3` | CMS - review of systems panel |
| `http://loinc.org` | `71421-2` | CMS - past family - social history panel |
| `http://loinc.org` | `71428-7` | CMS - history of present illness panel |
| `http://loinc.org` | `71446-9` | FDA package insert Indexing - billing unit |
| `http://loinc.org` | `71482-4` | Risk assessment Document |
| `http://loinc.org` | `71681-1` | FDA package insert PMI - Common side effects section |
| `http://loinc.org` | `71682-9` | FDA package insert PMI - Get emergency medical help section |
| `http://loinc.org` | `71683-7` | FDA package insert PMI - Stop taking and call your doctor section |
| `http://loinc.org` | `71684-5` | FDA package insert PMI - Directions for use section |
| `http://loinc.org` | `71685-2` | FDA package insert PMI - Tell your doctor before taking section |
| `http://loinc.org` | `71686-0` | FDA package insert PMI - Do not take section |
| `http://loinc.org` | `71687-8` | FDA package insert PMI - Important information section |
| `http://loinc.org` | `71688-6` | FDA package insert PMI - Uses section |
| `http://loinc.org` | `71743-9` | FDA product label Generic drug facility identification submission |
| `http://loinc.org` | `71744-7` | FDA package insert Health care provider letter |
| `http://loinc.org` | `72090-4` | FDA product label Identification of CBER-regulated generic drug facility |
| `http://loinc.org` | `72134-0` | Cancer event report |
| `http://loinc.org` | `72135-7` | Cancer diagnosis Narrative |
| `http://loinc.org` | `72137-3` | Breast - right FFD mammogram-tomosynthesis diagnostic |
| `http://loinc.org` | `72138-1` | Breast - left FFD mammogram-tomosynthesis diagnostic |
| `http://loinc.org` | `72139-9` | Breast - bilateral FFD mammogram-tomosynthesis diagnostic |
| `http://loinc.org` | `72140-7` | Breast - right FFD mammogram-tomosynthesis screening |
| `http://loinc.org` | `72141-5` | Breast - left FFD mammogram-tomosynthesis screening |
| `http://loinc.org` | `72142-3` | Breast - bilateral FFD mammogram-tomosynthesis screening |
| `http://loinc.org` | `72169-6` | Permission to release immunization data from school record |
| `http://loinc.org` | `72170-4` | Photographic image Unspecified body region Document |
| `http://loinc.org` | `72238-9` | Toes - right MRI W and WO contrast IV |
| `http://loinc.org` | `72239-7` | Toes - right MRI WO contrast |
| `http://loinc.org` | `72240-5` | Toes - right MRI W contrast IV |
| `http://loinc.org` | `72241-3` | Toes - left MRI W and WO contrast IV |
| `http://loinc.org` | `72242-1` | Toes - left MRI WO contrast |
| `http://loinc.org` | `72243-9` | Toes - left MRI W contrast IV |
| `http://loinc.org` | `72244-7` | Pelvis MRI W and WO contrast IV and W endorectal coil |
| `http://loinc.org` | `72245-4` | Pelvis MRI W contrast PR at rest and maxmal sphincter contraction during straining and defecation |
| `http://loinc.org` | `72246-2` | Abdomen and Pelvis MRI W contrast PO and W and WO contrast IV |
| `http://loinc.org` | `72247-0` | Abdomen and Pelvis MRI W contrast PO and WO contrast IV |
| `http://loinc.org` | `72248-8` | Abdomen MRCP with and without contrast IV |
| `http://loinc.org` | `72249-6` | Facial bones and Sinuses CT WO contrast |
| `http://loinc.org` | `72250-4` | Abdomen and Pelvis CT W contrast PO and W contrast IV |
| `http://loinc.org` | `72251-2` | Chest vessels CT Multisection for pulmonary embolus |
| `http://loinc.org` | `72252-0` | Chest and Abdomen and Pelvis CT W and WO contrast IV |
| `http://loinc.org` | `72253-8` | Chest and Abdomen and Pelvis CT WO contrast |
| `http://loinc.org` | `72254-6` | Chest and Abdomen and Pelvis CT W contrast IV |
| `http://loinc.org` | `72255-3` | Aorta and Femoral artery - bilateral CT angiogram W contrast IV |
| `http://loinc.org` | `72256-1` | Abdomen X-ray for motility with radioopaque markers |
| `http://loinc.org` | `72267-8` | Evaluation of mental and physical incapacity certificate Document |
| `http://loinc.org` | `72509-3` | Reporting rate Reporting period population Calculated |
| `http://loinc.org` | `72510-1` | Performance rate Reporting period population Calculated |
| `http://loinc.org` | `72528-3` | Axilla - right US |
| `http://loinc.org` | `72529-1` | Axilla - left US |
| `http://loinc.org` | `72530-9` | US Guidance for injection of Joint |
| `http://loinc.org` | `72531-7` | Rectum and Colon CT 3D W contrast IV and W air contrast PR |
| `http://loinc.org` | `72532-5` | US Guidance for ambulatory phlebectomy of Extremity vein - right |
| `http://loinc.org` | `72533-3` | US Guidance for ambulatory phlebectomy of Extremity vein - left |
| `http://loinc.org` | `72534-1` | US Guidance for laser ablation of vein(s) of Extremity vein - right |
| `http://loinc.org` | `72535-8` | US Guidance for laser ablation of vein(s) of Extremity vein - left |
| `http://loinc.org` | `72536-6` | US Guidance for injection of sclerosing agent of Extremity veins - bilateral |
| `http://loinc.org` | `72537-4` | US Guidance for injection of sclerosing agent of Extremity vein - bilateral |
| `http://loinc.org` | `72538-2` | Fluoroscopic angiogram Guidance for removal of longterm peripheral catheter from Central vein |
| `http://loinc.org` | `72539-0` | Fluoroscopy Guidance for peripheral nerve denervation of Unspecified body region |
| `http://loinc.org` | `72540-8` | Fluoroscopy Guidance for facet joint denervation of Spine |
| `http://loinc.org` | `72541-6` | Fluoroscopy Guidance for facet joint denervation of Spine Cervical |
| `http://loinc.org` | `72542-4` | Fluoroscopy Guidance for facet joint denervation of Spine Lumbar |
| `http://loinc.org` | `72543-2` | Fluoroscopy Guidance for intercostal nerve devervation of Spine Thoracic |
| `http://loinc.org` | `72544-0` | Fluoroscopy Guidance for removal of percutaneous nephrostomy tube from Kidney - bilateral-- W contrast |
| `http://loinc.org` | `72545-7` | Fluoroscopy Guidance for replacement of percutaneous drainage tube in Biliary ducts and Gallbladder |
| `http://loinc.org` | `72546-5` | Fluoroscopy Guidance for removal of CVA lumen obstruction from Central vein |
| `http://loinc.org` | `72547-3` | Fluoroscopy Guidance for removal of CVA device obstruction from Central vein |
| `http://loinc.org` | `72548-1` | Fluoroscopic angiogram Guidance for removal of catheter from Central vein-- W contrast IV |
| `http://loinc.org` | `72549-9` | Fluoroscopy Guidance for removal of catheter from Central vein-- Tunneled |
| `http://loinc.org` | `72550-7` | Fluoroscopy Guidance for repair of CVA catheter with port or pump of Central vein |
| `http://loinc.org` | `72551-5` | Fluoroscopy Guidance for repair of CVA catheter without port or pump of Central vein |
| `http://loinc.org` | `72552-3` | Fluoroscopy Guidance for kyphoplasty of Spine Lumbar |
| `http://loinc.org` | `72553-1` | Fluoroscopy Guidance for kyphoplasty of Spine Thoracic |
| `http://loinc.org` | `72554-9` | Fluoroscopy Guidance for trigger point injection of Muscle |
| `http://loinc.org` | `72555-6` | Interventional radiology Consult note |
| `http://loinc.org` | `72556-4` | Interventional radiology Progress note |
| `http://loinc.org` | `72642-2` | US Guidance for injection of sclerosing agent of Extremity veins - right |
| `http://loinc.org` | `72643-0` | US Guidance for injection of sclerosing agent of Extremity veins - left |
| `http://loinc.org` | `72644-8` | US Guidance for injection of sclerosing agent of Extremity vein - right |
| `http://loinc.org` | `72645-5` | US Guidance for injection of sclerosing agent of Extremity vein - left |
| `http://loinc.org` | `72830-3` | Extremity arteries - bilateral US.doppler Multisection and physiologic artery study |
| `http://loinc.org` | `72831-1` | Extremity arteries - bilateral US.doppler Multisection limited and physiologic artery study |
| `http://loinc.org` | `72832-9` | Extremity arteries - bilateral US.doppler Multisection and physiologic artery study at rest and with exercise |
| `http://loinc.org` | `72876-6` | Surgical specimen X-ray |
| `http://loinc.org` | `73568-8` | Communication of critical results [Description] Document |
| `http://loinc.org` | `73569-6` | Radiation exposure and protection information [Description] Document Diagnostic imaging |
| `http://loinc.org` | `73575-3` | Radiology Consult note |
| `http://loinc.org` | `73709-8` | Prescription request Pharmacy Document from Pharmacist |
| `http://loinc.org` | `73815-3` | FDA package insert Indexing - product concept |
| `http://loinc.org` | `73983-9` | Report.section heading Unspecified body region |
| `http://loinc.org` | `74030-8` | Periodontal service attachment |
| `http://loinc.org` | `74045-6` | Measure description Narrative |
| `http://loinc.org` | `74144-7` | Complex medical conditions action plan |
| `http://loinc.org` | `74145-4` | Multiple sclerosis action plan |
| `http://loinc.org` | `74146-2` | Heart disease action plan |
| `http://loinc.org` | `74147-0` | Muscular dystrophy action plan |
| `http://loinc.org` | `74148-8` | Cystic fibrosis action plan |
| `http://loinc.org` | `74149-6` | Inflammatory bowel disease action plan |
| `http://loinc.org` | `74150-4` | Diabetes type I action plan |
| `http://loinc.org` | `74151-2` | Diabetes type II action plan |
| `http://loinc.org` | `74152-0` | Anaphylaxis action plan |
| `http://loinc.org` | `74153-8` | Seizure disorder action plan |
| `http://loinc.org` | `74154-6` | Autism action plan |
| `http://loinc.org` | `74155-3` | ADHD action plan |
| `http://loinc.org` | `74156-1` | Oncology treatment plan and summary Document |
| `http://loinc.org` | `74166-0` | Occupational summary note |
| `http://loinc.org` | `74187-6` | InterRAI Emergency Screener for Psychiatry (ESP) Document |
| `http://loinc.org` | `74188-4` | InterRAI Acute Care (AC) Hospital Document |
| `http://loinc.org` | `74189-2` | InterRAI Palliative Care (PC) Document |
| `http://loinc.org` | `74190-0` | InterRAI Community Health Assessment - Deafblind Supplement (CHA-Db) Document |
| `http://loinc.org` | `74191-8` | InterRAI Community Health Assessment - Assisted Living Supplement (CHA-AL) Document |
| `http://loinc.org` | `74192-6` | InterRAI Community Health Assessment - Mental Health Supplement (CHA-MH) Document |
| `http://loinc.org` | `74193-4` | InterRAI Community Health Assessment - Functional Supplement (CHA-FS) Document |
| `http://loinc.org` | `74194-2` | InterRAI Community Health Assessment (CHA) Document |
| `http://loinc.org` | `74195-9` | InterRAI Long Term Care Facility (LTCF) Document |
| `http://loinc.org` | `74196-7` | InterRAI Home Care (HC) Document |
| `http://loinc.org` | `74197-5` | InterRAI Contact Assessment (CA) Document |
| `http://loinc.org` | `74198-3` | Trauma summary registry report Document |
| `http://loinc.org` | `74207-2` | Prehospital summary Document |
| `http://loinc.org` | `74208-0` | Demographic information + History of occupation Document |
| `http://loinc.org` | `74209-8` | Injury event summary Document |
| `http://loinc.org` | `74211-4` | Summary of episode note Emergency department+Hospital |
| `http://loinc.org` | `74213-0` | Discharge instructions |
| `http://loinc.org` | `74264-3` | HIV summary registry report Document |
| `http://loinc.org` | `74282-5` | Individual counseling note |
| `http://loinc.org` | `74465-6` | Questionnaire response section Document |
| `http://loinc.org` | `74468-0` | Questionnaire form definition section Document |
| `http://loinc.org` | `74476-3` | Clinical document Setting from LOINC Document Ontology |
| `http://loinc.org` | `74477-1` | Clinical document Kind of document from LOINC Document Ontology |
| `http://loinc.org` | `74478-9` | Clinical document Type of service from LOINC Document Ontology |
| `http://loinc.org` | `74479-7` | Clinical document Role from LOINC Document Ontology |
| `http://loinc.org` | `74480-5` | Clinical document Subject matter domain from LOINC Document Ontology |
| `http://loinc.org` | `8653-8` | Hospital Discharge instructions |
