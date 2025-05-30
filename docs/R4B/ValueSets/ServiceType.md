Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### ServiceType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ServiceType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/service-type` |
| Version | 4.3.0 |
| Description | This value set defines an example set of codes of service-types. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4094` |
| Database Concept Count | `596` |
| Database Active Concept Count | `596` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Appointment` | `Appointment.serviceType` | `http://hl7.org/fhir/ValueSet/service-type` | `Example` | The specific service that is to be performed during this appointment |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.serviceType` | `http://hl7.org/fhir/ValueSet/service-type` | `Example` | Specific type of service |
| `http://hl7.org/fhir/StructureDefinition/HealthcareService` | `HealthcareService.type` | `http://hl7.org/fhir/ValueSet/service-type` | `Example` | Type of service that may be delivered or performed |
| `http://hl7.org/fhir/StructureDefinition/Schedule` | `Schedule.serviceType` | `http://hl7.org/fhir/ValueSet/service-type` | `Example` | Specific service |
| `http://hl7.org/fhir/StructureDefinition/Slot` | `Slot.serviceType` | `http://hl7.org/fhir/ValueSet/service-type` | `Example` | The type of appointments that can be booked into this slot (ideally this would be an identifiable service - which is at a location, rather than the location itself). If provided then this overrides the value provided on the availability resource |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/service-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/service-type` | `1` | Adoption/Permanent Care Info/Support |
| `http://terminology.hl7.org/CodeSystem/service-type` | `10` | Personal Alarms/Alerts |
| `http://terminology.hl7.org/CodeSystem/service-type` | `100` | Disability Information/Referral |
| `http://terminology.hl7.org/CodeSystem/service-type` | `101` | Disability Support Packages |
| `http://terminology.hl7.org/CodeSystem/service-type` | `102` | Disability Supported Accommodation |
| `http://terminology.hl7.org/CodeSystem/service-type` | `103` | Early Childhood Intervention |
| `http://terminology.hl7.org/CodeSystem/service-type` | `104` | Hearing Aids & Equipment |
| `http://terminology.hl7.org/CodeSystem/service-type` | `105` | Drug and/or Alcohol Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `106` | Drug/Alcohol Information/Referral |
| `http://terminology.hl7.org/CodeSystem/service-type` | `107` | Needle & Syringe Exchange |
| `http://terminology.hl7.org/CodeSystem/service-type` | `108` | Non-resid. Alcohol/Drug Treatment |
| `http://terminology.hl7.org/CodeSystem/service-type` | `109` | Pharmacotherapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `11` | Personal Care for Older Persons |
| `http://terminology.hl7.org/CodeSystem/service-type` | `110` | Quit Program |
| `http://terminology.hl7.org/CodeSystem/service-type` | `111` | Residential Alcohol/Drug Treatment |
| `http://terminology.hl7.org/CodeSystem/service-type` | `112` | Adult/Community Education |
| `http://terminology.hl7.org/CodeSystem/service-type` | `113` | Higher Education |
| `http://terminology.hl7.org/CodeSystem/service-type` | `114` | Primary Education |
| `http://terminology.hl7.org/CodeSystem/service-type` | `115` | Secondary Education |
| `http://terminology.hl7.org/CodeSystem/service-type` | `116` | Training & Vocational Education |
| `http://terminology.hl7.org/CodeSystem/service-type` | `117` | Emergency Medical |
| `http://terminology.hl7.org/CodeSystem/service-type` | `118` | Employment Placement and/or Support |
| `http://terminology.hl7.org/CodeSystem/service-type` | `119` | Vocational Rehabilitation |
| `http://terminology.hl7.org/CodeSystem/service-type` | `12` | Planned Activity Groups |
| `http://terminology.hl7.org/CodeSystem/service-type` | `120` | Work Safety/Accident Prevention |
| `http://terminology.hl7.org/CodeSystem/service-type` | `121` | Financial Assistance |
| `http://terminology.hl7.org/CodeSystem/service-type` | `122` | Financial Information/Advice |
| `http://terminology.hl7.org/CodeSystem/service-type` | `123` | Material Aid |
| `http://terminology.hl7.org/CodeSystem/service-type` | `124` | General Practice |
| `http://terminology.hl7.org/CodeSystem/service-type` | `125` | Accommodation Placement/Support |
| `http://terminology.hl7.org/CodeSystem/service-type` | `126` | Crisis/Emergency Accommodation |
| `http://terminology.hl7.org/CodeSystem/service-type` | `127` | Homelessness Support |
| `http://terminology.hl7.org/CodeSystem/service-type` | `128` | Housing Information/Referral |
| `http://terminology.hl7.org/CodeSystem/service-type` | `129` | Public Rental Housing |
| `http://terminology.hl7.org/CodeSystem/service-type` | `13` | Acupuncture |
| `http://terminology.hl7.org/CodeSystem/service-type` | `130` | Interpreting/Multilingual Service |
| `http://terminology.hl7.org/CodeSystem/service-type` | `131` | Juvenile Justice |
| `http://terminology.hl7.org/CodeSystem/service-type` | `132` | Legal Advocacy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `133` | Legal Information/Advice/Referral |
| `http://terminology.hl7.org/CodeSystem/service-type` | `134` | Mental Health Advocacy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `135` | Mental Health Assess/Triage/Crisis Response |
| `http://terminology.hl7.org/CodeSystem/service-type` | `136` | Mental Health Case Management |
| `http://terminology.hl7.org/CodeSystem/service-type` | `137` | Mental Health Information/Referral |
| `http://terminology.hl7.org/CodeSystem/service-type` | `138` | Mental Health Inpatient Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `139` | Mental Health Non-residential Rehab |
| `http://terminology.hl7.org/CodeSystem/service-type` | `14` | Alexander Technique Therapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `140` | Mental Health Residential Rehab/CCU |
| `http://terminology.hl7.org/CodeSystem/service-type` | `141` | Psychiatry (Requires Referral) |
| `http://terminology.hl7.org/CodeSystem/service-type` | `142` | Psychology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `143` | Martial Arts |
| `http://terminology.hl7.org/CodeSystem/service-type` | `144` | Personal Fitness Training |
| `http://terminology.hl7.org/CodeSystem/service-type` | `145` | Physical Activity Group |
| `http://terminology.hl7.org/CodeSystem/service-type` | `146` | Physical Activity Programs |
| `http://terminology.hl7.org/CodeSystem/service-type` | `147` | Physical Fitness Testing |
| `http://terminology.hl7.org/CodeSystem/service-type` | `148` | Pilates |
| `http://terminology.hl7.org/CodeSystem/service-type` | `149` | Self-Defence |
| `http://terminology.hl7.org/CodeSystem/service-type` | `15` | Aromatherapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `150` | Sporting Club |
| `http://terminology.hl7.org/CodeSystem/service-type` | `151` | Yoga |
| `http://terminology.hl7.org/CodeSystem/service-type` | `152` | Food Safety |
| `http://terminology.hl7.org/CodeSystem/service-type` | `153` | Health Regulatory /Inspection /Cert. |
| `http://terminology.hl7.org/CodeSystem/service-type` | `154` | Work Health/Safety Inspection/Cert. |
| `http://terminology.hl7.org/CodeSystem/service-type` | `155` | Carer Support |
| `http://terminology.hl7.org/CodeSystem/service-type` | `156` | Respite Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `157` | Anatomical Pathology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `158` | Pathology - Clinical Chemistry |
| `http://terminology.hl7.org/CodeSystem/service-type` | `159` | Pathology - General |
| `http://terminology.hl7.org/CodeSystem/service-type` | `16` | Biorhythm Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `160` | Pathology - Genetics |
| `http://terminology.hl7.org/CodeSystem/service-type` | `161` | Pathology - Haematology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `162` | Pathology - Immunology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `163` | Pathology - Microbiology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `164` | Anaesthesiology - Pain Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `165` | Cardiology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `166` | Clinical Genetics |
| `http://terminology.hl7.org/CodeSystem/service-type` | `167` | Clinical Pharmacology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `168` | Dermatology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `169` | Endocrinology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `17` | Bowen Therapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `170` | Gastroenterology & Hepatology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `171` | Geriatric Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `172` | Immunology & Allergy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `173` | Infectious Diseases |
| `http://terminology.hl7.org/CodeSystem/service-type` | `174` | Intensive Care Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `175` | Medical Oncology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `176` | Nephrology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `177` | Neurology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `178` | Occupational Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `179` | Palliative Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `18` | Chinese Herbal Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `180` | Public Health Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `181` | Rehabilitation Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `182` | Rheumatology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `183` | Sleep Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `184` | Thoracic Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `185` | Gynaecological Oncology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `186` | Obstetrics & Gynaecology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `187` | Reproductive Endocrinology/Infertility |
| `http://terminology.hl7.org/CodeSystem/service-type` | `188` | Urogynaecology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `189` | Neonatology & Perinatology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `19` | Feldenkrais |
| `http://terminology.hl7.org/CodeSystem/service-type` | `190` | Paediatric Cardiology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `191` | Paediatric Clinical Genetics |
| `http://terminology.hl7.org/CodeSystem/service-type` | `192` | Paediatric Clinical Pharmacology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `193` | Paediatric Endocrinology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `194` | Paed. Gastroenterology/Hepatology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `195` | Paediatric Haematology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `196` | Paediatric Immunology & Allergy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `197` | Paediatric Infectious Diseases |
| `http://terminology.hl7.org/CodeSystem/service-type` | `198` | Paediatric Intensive Care Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `199` | Paediatric Medical Oncology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `2` | Aged Care Assessment |
| `http://terminology.hl7.org/CodeSystem/service-type` | `20` | Homoeopathy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `200` | Paediatric Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `201` | Paediatric Nephrology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `202` | Paediatric Neurology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `203` | Paediatric Nuclear Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `204` | Paediatric Rehabilitation Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `205` | Paediatric Rheumatology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `206` | Paediatric Sleep Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `207` | Paediatric Surgery |
| `http://terminology.hl7.org/CodeSystem/service-type` | `208` | Paediatric Thoracic Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `209` | Diag. Radiology /Xray /CT /Fluoroscopy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `21` | Hydrotherapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `210` | Diagnostic Ultrasound |
| `http://terminology.hl7.org/CodeSystem/service-type` | `211` | Magnetic Resonance Imaging (MRI) |
| `http://terminology.hl7.org/CodeSystem/service-type` | `212` | Nuclear Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `213` | Obstetric/Gynaecological Ultrasound |
| `http://terminology.hl7.org/CodeSystem/service-type` | `214` | Radiation Oncology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `215` | Cardiothoracic Surgery |
| `http://terminology.hl7.org/CodeSystem/service-type` | `216` | Neurosurgery |
| `http://terminology.hl7.org/CodeSystem/service-type` | `217` | Ophthalmology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `218` | Orthopaedic Surgery |
| `http://terminology.hl7.org/CodeSystem/service-type` | `219` | Otolaryngology/Head & Neck Surgery |
| `http://terminology.hl7.org/CodeSystem/service-type` | `22` | Hypnotherapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `220` | Plastic & Reconstructive Surgery |
| `http://terminology.hl7.org/CodeSystem/service-type` | `221` | Surgery - General |
| `http://terminology.hl7.org/CodeSystem/service-type` | `222` | Urology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `223` | Vascular Surgery |
| `http://terminology.hl7.org/CodeSystem/service-type` | `224` | Support Groups |
| `http://terminology.hl7.org/CodeSystem/service-type` | `225` | Air ambulance |
| `http://terminology.hl7.org/CodeSystem/service-type` | `226` | Ambulance |
| `http://terminology.hl7.org/CodeSystem/service-type` | `227` | Blood Transport |
| `http://terminology.hl7.org/CodeSystem/service-type` | `228` | Community Bus |
| `http://terminology.hl7.org/CodeSystem/service-type` | `229` | Flying Doctor Service |
| `http://terminology.hl7.org/CodeSystem/service-type` | `23` | Kinesiology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `230` | Patient Transport |
| `http://terminology.hl7.org/CodeSystem/service-type` | `231` | A&E |
| `http://terminology.hl7.org/CodeSystem/service-type` | `232` | A&EP |
| `http://terminology.hl7.org/CodeSystem/service-type` | `233` | Abuse |
| `http://terminology.hl7.org/CodeSystem/service-type` | `234` | ACAS |
| `http://terminology.hl7.org/CodeSystem/service-type` | `235` | Access |
| `http://terminology.hl7.org/CodeSystem/service-type` | `236` | Accident |
| `http://terminology.hl7.org/CodeSystem/service-type` | `237` | Acute Inpatient Serv |
| `http://terminology.hl7.org/CodeSystem/service-type` | `238` | Adult Day Programs |
| `http://terminology.hl7.org/CodeSystem/service-type` | `239` | Adult Mental Health Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `24` | Magnetic Therapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `240` | Advice |
| `http://terminology.hl7.org/CodeSystem/service-type` | `241` | Advocacy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `242` | Aged Persons Mental |
| `http://terminology.hl7.org/CodeSystem/service-type` | `243` | Aged Persons Mental |
| `http://terminology.hl7.org/CodeSystem/service-type` | `244` | Aged Persons Mental |
| `http://terminology.hl7.org/CodeSystem/service-type` | `245` | Aids |
| `http://terminology.hl7.org/CodeSystem/service-type` | `246` | Al-Anon |
| `http://terminology.hl7.org/CodeSystem/service-type` | `247` | Alcohol |
| `http://terminology.hl7.org/CodeSystem/service-type` | `248` | Al-Teen |
| `http://terminology.hl7.org/CodeSystem/service-type` | `249` | Antenatal |
| `http://terminology.hl7.org/CodeSystem/service-type` | `25` | Massage Therapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `250` | Anxiety |
| `http://terminology.hl7.org/CodeSystem/service-type` | `251` | Arthritis |
| `http://terminology.hl7.org/CodeSystem/service-type` | `252` | Assessment |
| `http://terminology.hl7.org/CodeSystem/service-type` | `253` | Assistance |
| `http://terminology.hl7.org/CodeSystem/service-type` | `254` | Asthma |
| `http://terminology.hl7.org/CodeSystem/service-type` | `255` | ATSS |
| `http://terminology.hl7.org/CodeSystem/service-type` | `256` | Attendant Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `257` | Babies |
| `http://terminology.hl7.org/CodeSystem/service-type` | `258` | Bathroom Modificatio |
| `http://terminology.hl7.org/CodeSystem/service-type` | `259` | Behavior |
| `http://terminology.hl7.org/CodeSystem/service-type` | `26` | Meditation |
| `http://terminology.hl7.org/CodeSystem/service-type` | `260` | Behavior Interventi |
| `http://terminology.hl7.org/CodeSystem/service-type` | `261` | Bereavement |
| `http://terminology.hl7.org/CodeSystem/service-type` | `262` | Bipolar |
| `http://terminology.hl7.org/CodeSystem/service-type` | `263` | Birth |
| `http://terminology.hl7.org/CodeSystem/service-type` | `264` | Birth Control |
| `http://terminology.hl7.org/CodeSystem/service-type` | `265` | Birthing Options |
| `http://terminology.hl7.org/CodeSystem/service-type` | `266` | BIST |
| `http://terminology.hl7.org/CodeSystem/service-type` | `267` | Blood |
| `http://terminology.hl7.org/CodeSystem/service-type` | `268` | Bone |
| `http://terminology.hl7.org/CodeSystem/service-type` | `269` | Bowel |
| `http://terminology.hl7.org/CodeSystem/service-type` | `27` | Myotherapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `270` | Brain |
| `http://terminology.hl7.org/CodeSystem/service-type` | `271` | Breast Feeding |
| `http://terminology.hl7.org/CodeSystem/service-type` | `272` | Breast Screen |
| `http://terminology.hl7.org/CodeSystem/service-type` | `273` | Brokerage |
| `http://terminology.hl7.org/CodeSystem/service-type` | `274` | Cancer |
| `http://terminology.hl7.org/CodeSystem/service-type` | `275` | Cancer Support |
| `http://terminology.hl7.org/CodeSystem/service-type` | `276` | Cardiovascular Disea |
| `http://terminology.hl7.org/CodeSystem/service-type` | `277` | Care Packages |
| `http://terminology.hl7.org/CodeSystem/service-type` | `278` | Carer |
| `http://terminology.hl7.org/CodeSystem/service-type` | `279` | Case Management |
| `http://terminology.hl7.org/CodeSystem/service-type` | `28` | Naturopathy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `280` | Casualty |
| `http://terminology.hl7.org/CodeSystem/service-type` | `281` | Centrelink |
| `http://terminology.hl7.org/CodeSystem/service-type` | `282` | Chemists |
| `http://terminology.hl7.org/CodeSystem/service-type` | `283` | Child And Adolescent |
| `http://terminology.hl7.org/CodeSystem/service-type` | `284` | Child Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `285` | Child Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `286` | Children |
| `http://terminology.hl7.org/CodeSystem/service-type` | `287` | Children's Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `288` | Cholesterol |
| `http://terminology.hl7.org/CodeSystem/service-type` | `289` | Clothing |
| `http://terminology.hl7.org/CodeSystem/service-type` | `29` | Reflexology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `290` | Community Based Acco |
| `http://terminology.hl7.org/CodeSystem/service-type` | `291` | Community Care Unit |
| `http://terminology.hl7.org/CodeSystem/service-type` | `292` | Community Child And |
| `http://terminology.hl7.org/CodeSystem/service-type` | `293` | Community Health |
| `http://terminology.hl7.org/CodeSystem/service-type` | `294` | Community Residentia |
| `http://terminology.hl7.org/CodeSystem/service-type` | `295` | Community Transport |
| `http://terminology.hl7.org/CodeSystem/service-type` | `296` | Companion Visiting |
| `http://terminology.hl7.org/CodeSystem/service-type` | `297` | Companionship |
| `http://terminology.hl7.org/CodeSystem/service-type` | `298` | Consumer Advice |
| `http://terminology.hl7.org/CodeSystem/service-type` | `299` | Consumer Issues |
| `http://terminology.hl7.org/CodeSystem/service-type` | `3` | Aged Care Information/Referral |
| `http://terminology.hl7.org/CodeSystem/service-type` | `30` | Reiki |
| `http://terminology.hl7.org/CodeSystem/service-type` | `300` | Continuing Care Serv |
| `http://terminology.hl7.org/CodeSystem/service-type` | `301` | Contraception Inform |
| `http://terminology.hl7.org/CodeSystem/service-type` | `302` | Coordinating Bodies |
| `http://terminology.hl7.org/CodeSystem/service-type` | `303` | Correctional Service |
| `http://terminology.hl7.org/CodeSystem/service-type` | `304` | Council Environmenta |
| `http://terminology.hl7.org/CodeSystem/service-type` | `305` | Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `306` | Criminal |
| `http://terminology.hl7.org/CodeSystem/service-type` | `307` | Crises |
| `http://terminology.hl7.org/CodeSystem/service-type` | `308` | Crisis Assessment An |
| `http://terminology.hl7.org/CodeSystem/service-type` | `309` | Crisis Assistance |
| `http://terminology.hl7.org/CodeSystem/service-type` | `31` | Relaxation Therapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `310` | Crisis Refuge |
| `http://terminology.hl7.org/CodeSystem/service-type` | `311` | Day Program |
| `http://terminology.hl7.org/CodeSystem/service-type` | `312` | Deaf |
| `http://terminology.hl7.org/CodeSystem/service-type` | `313` | Dental Hygiene |
| `http://terminology.hl7.org/CodeSystem/service-type` | `314` | Dentistry |
| `http://terminology.hl7.org/CodeSystem/service-type` | `315` | Dentures |
| `http://terminology.hl7.org/CodeSystem/service-type` | `316` | Depression |
| `http://terminology.hl7.org/CodeSystem/service-type` | `317` | Detoxification |
| `http://terminology.hl7.org/CodeSystem/service-type` | `318` | Diabetes |
| `http://terminology.hl7.org/CodeSystem/service-type` | `319` | Diaphragm Fitting |
| `http://terminology.hl7.org/CodeSystem/service-type` | `32` | Shiatsu |
| `http://terminology.hl7.org/CodeSystem/service-type` | `320` | Dieticians |
| `http://terminology.hl7.org/CodeSystem/service-type` | `321` | Disabled Parking |
| `http://terminology.hl7.org/CodeSystem/service-type` | `322` | District Nursing |
| `http://terminology.hl7.org/CodeSystem/service-type` | `323` | Divorce |
| `http://terminology.hl7.org/CodeSystem/service-type` | `324` | Doctors |
| `http://terminology.hl7.org/CodeSystem/service-type` | `325` | Drink-Drive |
| `http://terminology.hl7.org/CodeSystem/service-type` | `326` | Dual Diagnosis Servi |
| `http://terminology.hl7.org/CodeSystem/service-type` | `327` | Early Choice |
| `http://terminology.hl7.org/CodeSystem/service-type` | `328` | Eating Disorder |
| `http://terminology.hl7.org/CodeSystem/service-type` | `33` | Western Herbal Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `330` | Emergency Relief |
| `http://terminology.hl7.org/CodeSystem/service-type` | `331` | Employment And Train |
| `http://terminology.hl7.org/CodeSystem/service-type` | `332` | Environment |
| `http://terminology.hl7.org/CodeSystem/service-type` | `333` | Equipment |
| `http://terminology.hl7.org/CodeSystem/service-type` | `334` | Exercise |
| `http://terminology.hl7.org/CodeSystem/service-type` | `335` | Facility |
| `http://terminology.hl7.org/CodeSystem/service-type` | `336` | Family Choice |
| `http://terminology.hl7.org/CodeSystem/service-type` | `337` | Family Law |
| `http://terminology.hl7.org/CodeSystem/service-type` | `338` | Family Options |
| `http://terminology.hl7.org/CodeSystem/service-type` | `339` | Family Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `34` | Family Day care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `340` | FFYA |
| `http://terminology.hl7.org/CodeSystem/service-type` | `341` | Financial Aid |
| `http://terminology.hl7.org/CodeSystem/service-type` | `342` | Fitness |
| `http://terminology.hl7.org/CodeSystem/service-type` | `343` | Flexible Care Packag |
| `http://terminology.hl7.org/CodeSystem/service-type` | `344` | Food |
| `http://terminology.hl7.org/CodeSystem/service-type` | `345` | Food Vouchers |
| `http://terminology.hl7.org/CodeSystem/service-type` | `346` | Forensic Mental Heal |
| `http://terminology.hl7.org/CodeSystem/service-type` | `347` | Futures |
| `http://terminology.hl7.org/CodeSystem/service-type` | `348` | Futures For Young Ad |
| `http://terminology.hl7.org/CodeSystem/service-type` | `349` | General Practitioner |
| `http://terminology.hl7.org/CodeSystem/service-type` | `35` | Holiday Programs |
| `http://terminology.hl7.org/CodeSystem/service-type` | `350` | Grants |
| `http://terminology.hl7.org/CodeSystem/service-type` | `351` | Grief |
| `http://terminology.hl7.org/CodeSystem/service-type` | `352` | Grief Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `353` | HACC |
| `http://terminology.hl7.org/CodeSystem/service-type` | `354` | Heart Disease |
| `http://terminology.hl7.org/CodeSystem/service-type` | `355` | Help |
| `http://terminology.hl7.org/CodeSystem/service-type` | `356` | High Blood Pressure |
| `http://terminology.hl7.org/CodeSystem/service-type` | `357` | Home Help |
| `http://terminology.hl7.org/CodeSystem/service-type` | `358` | Home Nursing |
| `http://terminology.hl7.org/CodeSystem/service-type` | `359` | Homefirst |
| `http://terminology.hl7.org/CodeSystem/service-type` | `36` | Kindergarten Inclusion Support |
| `http://terminology.hl7.org/CodeSystem/service-type` | `360` | Hospice Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `361` | Hospital Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `362` | Hospital To Home |
| `http://terminology.hl7.org/CodeSystem/service-type` | `364` | Hostel |
| `http://terminology.hl7.org/CodeSystem/service-type` | `365` | Hostel Accommodation |
| `http://terminology.hl7.org/CodeSystem/service-type` | `366` | Household Items |
| `http://terminology.hl7.org/CodeSystem/service-type` | `367` | Hypertension |
| `http://terminology.hl7.org/CodeSystem/service-type` | `368` | Illness |
| `http://terminology.hl7.org/CodeSystem/service-type` | `369` | Independent Living |
| `http://terminology.hl7.org/CodeSystem/service-type` | `37` | Kindergarten/Preschool |
| `http://terminology.hl7.org/CodeSystem/service-type` | `370` | Information |
| `http://terminology.hl7.org/CodeSystem/service-type` | `371` | Injury |
| `http://terminology.hl7.org/CodeSystem/service-type` | `372` | Intake |
| `http://terminology.hl7.org/CodeSystem/service-type` | `373` | Intensive Mobile You |
| `http://terminology.hl7.org/CodeSystem/service-type` | `374` | Intervention |
| `http://terminology.hl7.org/CodeSystem/service-type` | `375` | Job Searching |
| `http://terminology.hl7.org/CodeSystem/service-type` | `376` | Justice |
| `http://terminology.hl7.org/CodeSystem/service-type` | `377` | Leisure |
| `http://terminology.hl7.org/CodeSystem/service-type` | `378` | Loans |
| `http://terminology.hl7.org/CodeSystem/service-type` | `379` | Low Income Earners |
| `http://terminology.hl7.org/CodeSystem/service-type` | `38` | Long Day Child Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `380` | Lung |
| `http://terminology.hl7.org/CodeSystem/service-type` | `381` | Making A Difference |
| `http://terminology.hl7.org/CodeSystem/service-type` | `382` | Medical Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `383` | Medical Specialists |
| `http://terminology.hl7.org/CodeSystem/service-type` | `384` | Medication Administr |
| `http://terminology.hl7.org/CodeSystem/service-type` | `385` | Menstrual Informatio |
| `http://terminology.hl7.org/CodeSystem/service-type` | `386` | Methadone |
| `http://terminology.hl7.org/CodeSystem/service-type` | `387` | Mobile Support And T |
| `http://terminology.hl7.org/CodeSystem/service-type` | `388` | Motor Neurone |
| `http://terminology.hl7.org/CodeSystem/service-type` | `389` | Multiple Sclerosis |
| `http://terminology.hl7.org/CodeSystem/service-type` | `39` | Occasional Child Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `390` | Neighbourhood House |
| `http://terminology.hl7.org/CodeSystem/service-type` | `391` | Nursing Home |
| `http://terminology.hl7.org/CodeSystem/service-type` | `392` | Nursing Mothers |
| `http://terminology.hl7.org/CodeSystem/service-type` | `393` | Obesity |
| `http://terminology.hl7.org/CodeSystem/service-type` | `394` | Occupational Health |
| `http://terminology.hl7.org/CodeSystem/service-type` | `395` | Optometrist |
| `http://terminology.hl7.org/CodeSystem/service-type` | `396` | Oral Hygiene |
| `http://terminology.hl7.org/CodeSystem/service-type` | `397` | Outpatients |
| `http://terminology.hl7.org/CodeSystem/service-type` | `398` | Outreach Service |
| `http://terminology.hl7.org/CodeSystem/service-type` | `399` | PADP |
| `http://terminology.hl7.org/CodeSystem/service-type` | `4` | Aged Residential Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `40` | Outside School Hours Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `400` | Pain |
| `http://terminology.hl7.org/CodeSystem/service-type` | `401` | Pap Smear |
| `http://terminology.hl7.org/CodeSystem/service-type` | `402` | Parenting |
| `http://terminology.hl7.org/CodeSystem/service-type` | `403` | Peak Organizations |
| `http://terminology.hl7.org/CodeSystem/service-type` | `404` | Personal Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `405` | Pharmacies |
| `http://terminology.hl7.org/CodeSystem/service-type` | `406` | Phobias |
| `http://terminology.hl7.org/CodeSystem/service-type` | `407` | Physical |
| `http://terminology.hl7.org/CodeSystem/service-type` | `408` | Physical Activity |
| `http://terminology.hl7.org/CodeSystem/service-type` | `409` | Postnatal |
| `http://terminology.hl7.org/CodeSystem/service-type` | `41` | Children's Play Programs |
| `http://terminology.hl7.org/CodeSystem/service-type` | `410` | Pregnancy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `411` | Pregnancy Tests |
| `http://terminology.hl7.org/CodeSystem/service-type` | `412` | Preschool |
| `http://terminology.hl7.org/CodeSystem/service-type` | `413` | Prescriptions |
| `http://terminology.hl7.org/CodeSystem/service-type` | `414` | Primary Mental Healt |
| `http://terminology.hl7.org/CodeSystem/service-type` | `415` | Property Maintenance |
| `http://terminology.hl7.org/CodeSystem/service-type` | `416` | Prostate |
| `http://terminology.hl7.org/CodeSystem/service-type` | `417` | Psychiatric |
| `http://terminology.hl7.org/CodeSystem/service-type` | `418` | Psychiatric Disabili |
| `http://terminology.hl7.org/CodeSystem/service-type` | `419` | Psychiatric Disabili |
| `http://terminology.hl7.org/CodeSystem/service-type` | `42` | Parenting/Family Support/Education |
| `http://terminology.hl7.org/CodeSystem/service-type` | `420` | Psychiatric Disabili |
| `http://terminology.hl7.org/CodeSystem/service-type` | `421` | Psychiatric Disabili |
| `http://terminology.hl7.org/CodeSystem/service-type` | `422` | Psychiatric Disabili |
| `http://terminology.hl7.org/CodeSystem/service-type` | `423` | Psychiatric Support |
| `http://terminology.hl7.org/CodeSystem/service-type` | `424` | Recreation |
| `http://terminology.hl7.org/CodeSystem/service-type` | `425` | Referral |
| `http://terminology.hl7.org/CodeSystem/service-type` | `426` | Refuge |
| `http://terminology.hl7.org/CodeSystem/service-type` | `427` | Rent Assistance |
| `http://terminology.hl7.org/CodeSystem/service-type` | `428` | Residential Faciliti |
| `http://terminology.hl7.org/CodeSystem/service-type` | `429` | Residential Respite |
| `http://terminology.hl7.org/CodeSystem/service-type` | `43` | Playgroup |
| `http://terminology.hl7.org/CodeSystem/service-type` | `430` | Respiratory |
| `http://terminology.hl7.org/CodeSystem/service-type` | `431` | Response |
| `http://terminology.hl7.org/CodeSystem/service-type` | `432` | Rooming Houses |
| `http://terminology.hl7.org/CodeSystem/service-type` | `433` | Safe Sex |
| `http://terminology.hl7.org/CodeSystem/service-type` | `434` | Secure Extended Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `435` | Self Help |
| `http://terminology.hl7.org/CodeSystem/service-type` | `436` | Separation |
| `http://terminology.hl7.org/CodeSystem/service-type` | `437` | Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `438` | Sex Education |
| `http://terminology.hl7.org/CodeSystem/service-type` | `439` | Sexual Abuse |
| `http://terminology.hl7.org/CodeSystem/service-type` | `44` | School Nursing |
| `http://terminology.hl7.org/CodeSystem/service-type` | `440` | Sexual Issues |
| `http://terminology.hl7.org/CodeSystem/service-type` | `441` | Sexually Transmitted |
| `http://terminology.hl7.org/CodeSystem/service-type` | `442` | SIDS |
| `http://terminology.hl7.org/CodeSystem/service-type` | `443` | Social Support |
| `http://terminology.hl7.org/CodeSystem/service-type` | `444` | Socialisation |
| `http://terminology.hl7.org/CodeSystem/service-type` | `445` | Special Needs |
| `http://terminology.hl7.org/CodeSystem/service-type` | `446` | Speech Therapist |
| `http://terminology.hl7.org/CodeSystem/service-type` | `447` | Splinting |
| `http://terminology.hl7.org/CodeSystem/service-type` | `448` | Sport |
| `http://terminology.hl7.org/CodeSystem/service-type` | `449` | Statewide And Specia |
| `http://terminology.hl7.org/CodeSystem/service-type` | `45` | Toy Library |
| `http://terminology.hl7.org/CodeSystem/service-type` | `450` | STD |
| `http://terminology.hl7.org/CodeSystem/service-type` | `451` | STI |
| `http://terminology.hl7.org/CodeSystem/service-type` | `452` | Stillbirth |
| `http://terminology.hl7.org/CodeSystem/service-type` | `453` | Stomal Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `454` | Stroke |
| `http://terminology.hl7.org/CodeSystem/service-type` | `455` | Substance Abuse |
| `http://terminology.hl7.org/CodeSystem/service-type` | `456` | Support |
| `http://terminology.hl7.org/CodeSystem/service-type` | `457` | Syringes |
| `http://terminology.hl7.org/CodeSystem/service-type` | `458` | Teeth |
| `http://terminology.hl7.org/CodeSystem/service-type` | `459` | Tenancy Advice |
| `http://terminology.hl7.org/CodeSystem/service-type` | `46` | Child Protection/Child Abuse Report |
| `http://terminology.hl7.org/CodeSystem/service-type` | `460` | Terminal Illness |
| `http://terminology.hl7.org/CodeSystem/service-type` | `461` | Therapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `462` | Transcription |
| `http://terminology.hl7.org/CodeSystem/service-type` | `463` | Translating Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `464` | Translator |
| `http://terminology.hl7.org/CodeSystem/service-type` | `465` | Transport |
| `http://terminology.hl7.org/CodeSystem/service-type` | `466` | Vertebrae |
| `http://terminology.hl7.org/CodeSystem/service-type` | `467` | Violence |
| `http://terminology.hl7.org/CodeSystem/service-type` | `468` | Vocational Guidance |
| `http://terminology.hl7.org/CodeSystem/service-type` | `469` | Weight |
| `http://terminology.hl7.org/CodeSystem/service-type` | `47` | Foster Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `470` | Welfare Assistance |
| `http://terminology.hl7.org/CodeSystem/service-type` | `471` | Welfare Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `472` | Wheelchairs |
| `http://terminology.hl7.org/CodeSystem/service-type` | `473` | Wound Management |
| `http://terminology.hl7.org/CodeSystem/service-type` | `474` | Young People At Risk |
| `http://terminology.hl7.org/CodeSystem/service-type` | `475` | Further Desc. - Community Health Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `476` | Library |
| `http://terminology.hl7.org/CodeSystem/service-type` | `477` | Community Hours |
| `http://terminology.hl7.org/CodeSystem/service-type` | `478` | Further Desc. - Specialist Medical |
| `http://terminology.hl7.org/CodeSystem/service-type` | `479` | Hepatology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `48` | Residential/Out-of-Home Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `480` | Gastroenterology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `481` | Gynaecology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `482` | Obstetrics |
| `http://terminology.hl7.org/CodeSystem/service-type` | `483` | Further Desc. - Specialist Surgical |
| `http://terminology.hl7.org/CodeSystem/service-type` | `484` | Placement Protection |
| `http://terminology.hl7.org/CodeSystem/service-type` | `485` | Family Violence |
| `http://terminology.hl7.org/CodeSystem/service-type` | `486` | Integrated Family Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `488` | Diabetes Educator |
| `http://terminology.hl7.org/CodeSystem/service-type` | `489` | Kinship Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `49` | Support - Young People Leaving Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `490` | General Mental Health Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `491` | Exercise Physiology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `492` | Medical Research |
| `http://terminology.hl7.org/CodeSystem/service-type` | `493` | Youth |
| `http://terminology.hl7.org/CodeSystem/service-type` | `494` | Youth Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `495` | Youth Health |
| `http://terminology.hl7.org/CodeSystem/service-type` | `496` | Child and Family Ser |
| `http://terminology.hl7.org/CodeSystem/service-type` | `497` | Home Visits |
| `http://terminology.hl7.org/CodeSystem/service-type` | `498` | Mobile Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `5` | Case Management for Older Persons |
| `http://terminology.hl7.org/CodeSystem/service-type` | `50` | Audiology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `500` | Before and/or After |
| `http://terminology.hl7.org/CodeSystem/service-type` | `501` | Cancer Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `502` | Integrated Cancer Se |
| `http://terminology.hl7.org/CodeSystem/service-type` | `503` | Multidisciplinary Se |
| `http://terminology.hl7.org/CodeSystem/service-type` | `504` | Multidisciplinary Ca |
| `http://terminology.hl7.org/CodeSystem/service-type` | `505` | Meetings |
| `http://terminology.hl7.org/CodeSystem/service-type` | `506` | Blood pressure monit |
| `http://terminology.hl7.org/CodeSystem/service-type` | `507` | Dose administration |
| `http://terminology.hl7.org/CodeSystem/service-type` | `508` | Medical Equipment Hi |
| `http://terminology.hl7.org/CodeSystem/service-type` | `509` | Parenting/Family Support/Education |
| `http://terminology.hl7.org/CodeSystem/service-type` | `51` | Blood Donation |
| `http://terminology.hl7.org/CodeSystem/service-type` | `510` | Deputising Service |
| `http://terminology.hl7.org/CodeSystem/service-type` | `513` | Cancer Support Groups |
| `http://terminology.hl7.org/CodeSystem/service-type` | `514` | Community Cancer Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `52` | Chiropractic |
| `http://terminology.hl7.org/CodeSystem/service-type` | `53` | Dietetics |
| `http://terminology.hl7.org/CodeSystem/service-type` | `530` | Disability Care Transport |
| `http://terminology.hl7.org/CodeSystem/service-type` | `531` | Aged Care Transport |
| `http://terminology.hl7.org/CodeSystem/service-type` | `532` | Diabetes Education s |
| `http://terminology.hl7.org/CodeSystem/service-type` | `533` | Cardiac Rehabilitati |
| `http://terminology.hl7.org/CodeSystem/service-type` | `534` | Young Adult Diabetes |
| `http://terminology.hl7.org/CodeSystem/service-type` | `535` | Pulmonary Rehabilita |
| `http://terminology.hl7.org/CodeSystem/service-type` | `536` | Art therapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `537` | Medication Reviews |
| `http://terminology.hl7.org/CodeSystem/service-type` | `538` | Telephone Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `539` | Telephone Help Line |
| `http://terminology.hl7.org/CodeSystem/service-type` | `54` | Family Planning |
| `http://terminology.hl7.org/CodeSystem/service-type` | `540` | Online Service |
| `http://terminology.hl7.org/CodeSystem/service-type` | `541` | Crisis - Mental Health |
| `http://terminology.hl7.org/CodeSystem/service-type` | `542` | Youth Crisis |
| `http://terminology.hl7.org/CodeSystem/service-type` | `543` | Sexual Assault |
| `http://terminology.hl7.org/CodeSystem/service-type` | `544` | GPAH Other |
| `http://terminology.hl7.org/CodeSystem/service-type` | `545` | Paediatric Dermatology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `546` | Veterans Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `547` | Veterans |
| `http://terminology.hl7.org/CodeSystem/service-type` | `548` | Food Relief/Food/Meals |
| `http://terminology.hl7.org/CodeSystem/service-type` | `55` | Health Advocacy/Liaison Service |
| `http://terminology.hl7.org/CodeSystem/service-type` | `550` | Dementia Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `551` | Alzheimer |
| `http://terminology.hl7.org/CodeSystem/service-type` | `552` | Drug and/or Alcohol Support Groups |
| `http://terminology.hl7.org/CodeSystem/service-type` | `553` | 1-on-1 Support /Mentoring /Coaching |
| `http://terminology.hl7.org/CodeSystem/service-type` | `554` | Chronic Disease Management |
| `http://terminology.hl7.org/CodeSystem/service-type` | `555` | Liaison Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `556` | Walk-in Centre /Non-Emergency |
| `http://terminology.hl7.org/CodeSystem/service-type` | `557` | Inpatients |
| `http://terminology.hl7.org/CodeSystem/service-type` | `558` | Spiritual Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `559` | Women's Health |
| `http://terminology.hl7.org/CodeSystem/service-type` | `56` | Health Information/Referral |
| `http://terminology.hl7.org/CodeSystem/service-type` | `560` | Men's Health |
| `http://terminology.hl7.org/CodeSystem/service-type` | `561` | Health Education/Awareness Program |
| `http://terminology.hl7.org/CodeSystem/service-type` | `562` | Test Message |
| `http://terminology.hl7.org/CodeSystem/service-type` | `563` | Remedial Massage |
| `http://terminology.hl7.org/CodeSystem/service-type` | `564` | Adolescent Mental Health Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `565` | Youth Drop In/Assistance/Support |
| `http://terminology.hl7.org/CodeSystem/service-type` | `566` | Aboriginal Health Worker |
| `http://terminology.hl7.org/CodeSystem/service-type` | `567` | Women's Health Clinic |
| `http://terminology.hl7.org/CodeSystem/service-type` | `568` | Men's Health Clinic |
| `http://terminology.hl7.org/CodeSystem/service-type` | `569` | Migrant Health Clinic |
| `http://terminology.hl7.org/CodeSystem/service-type` | `57` | Immunization |
| `http://terminology.hl7.org/CodeSystem/service-type` | `570` | Refugee Health Clinic |
| `http://terminology.hl7.org/CodeSystem/service-type` | `571` | Aboriginal Health Clinic |
| `http://terminology.hl7.org/CodeSystem/service-type` | `572` | Nurse Practitioner Lead Clinic/s |
| `http://terminology.hl7.org/CodeSystem/service-type` | `573` | Nurse Lead Clinic/s |
| `http://terminology.hl7.org/CodeSystem/service-type` | `574` | Culturally Tailored Support Groups |
| `http://terminology.hl7.org/CodeSystem/service-type` | `575` | Culturally Tailored Health Promotion |
| `http://terminology.hl7.org/CodeSystem/service-type` | `576` | Rehabilitation |
| `http://terminology.hl7.org/CodeSystem/service-type` | `577` | Education Information/Referral |
| `http://terminology.hl7.org/CodeSystem/service-type` | `58` | Maternal & Child Health |
| `http://terminology.hl7.org/CodeSystem/service-type` | `580` | Social Work |
| `http://terminology.hl7.org/CodeSystem/service-type` | `581` | Haematology |
| `http://terminology.hl7.org/CodeSystem/service-type` | `582` | Maternity Shared Car |
| `http://terminology.hl7.org/CodeSystem/service-type` | `583` | Rehabilitation Servi |
| `http://terminology.hl7.org/CodeSystem/service-type` | `584` | Cranio-sacral Therapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `585` | Prosthetics & Orthotics |
| `http://terminology.hl7.org/CodeSystem/service-type` | `589` | Home Medicine Review |
| `http://terminology.hl7.org/CodeSystem/service-type` | `59` | Nursing |
| `http://terminology.hl7.org/CodeSystem/service-type` | `590` | GPAH - Medical |
| `http://terminology.hl7.org/CodeSystem/service-type` | `591` | Music Therapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `593` | Falls Prevention |
| `http://terminology.hl7.org/CodeSystem/service-type` | `599` | Accommodation/Tenancy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `6` | Delivered Meals (Meals On Wheels) |
| `http://terminology.hl7.org/CodeSystem/service-type` | `60` | Nutrition |
| `http://terminology.hl7.org/CodeSystem/service-type` | `600` | Assess-Skill, Ability, Needs |
| `http://terminology.hl7.org/CodeSystem/service-type` | `601` | Assist Access/Maintain Employ |
| `http://terminology.hl7.org/CodeSystem/service-type` | `602` | Assist Prod-Pers Care/Safety |
| `http://terminology.hl7.org/CodeSystem/service-type` | `603` | Assist-Integrate School/Ed |
| `http://terminology.hl7.org/CodeSystem/service-type` | `604` | Assist-Life Stage, Transition |
| `http://terminology.hl7.org/CodeSystem/service-type` | `605` | Assist-Personal Activities |
| `http://terminology.hl7.org/CodeSystem/service-type` | `606` | Assist-Travel/Transport |
| `http://terminology.hl7.org/CodeSystem/service-type` | `607` | Assistive Equip-General Tasks |
| `http://terminology.hl7.org/CodeSystem/service-type` | `608` | Assistive Equip-Recreation |
| `http://terminology.hl7.org/CodeSystem/service-type` | `609` | Assistive Prod-Household Task |
| `http://terminology.hl7.org/CodeSystem/service-type` | `61` | Occupational Therapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `610` | Behavior Support |
| `http://terminology.hl7.org/CodeSystem/service-type` | `611` | Comms & Info Equipment |
| `http://terminology.hl7.org/CodeSystem/service-type` | `612` | Community Nursing Care |
| `http://terminology.hl7.org/CodeSystem/service-type` | `613` | Daily Tasks/Shared Living |
| `http://terminology.hl7.org/CodeSystem/service-type` | `614` | Development-Life Skills |
| `http://terminology.hl7.org/CodeSystem/service-type` | `615` | Early Childhood Supports |
| `http://terminology.hl7.org/CodeSystem/service-type` | `616` | Equipment Special Assess Setup |
| `http://terminology.hl7.org/CodeSystem/service-type` | `617` | Hearing Equipment |
| `http://terminology.hl7.org/CodeSystem/service-type` | `618` | Home Modification |
| `http://terminology.hl7.org/CodeSystem/service-type` | `619` | Household Tasks |
| `http://terminology.hl7.org/CodeSystem/service-type` | `62` | Optometry |
| `http://terminology.hl7.org/CodeSystem/service-type` | `620` | Interpret/Translate |
| `http://terminology.hl7.org/CodeSystem/service-type` | `621` | Other Innovative Supports |
| `http://terminology.hl7.org/CodeSystem/service-type` | `622` | Participate Community |
| `http://terminology.hl7.org/CodeSystem/service-type` | `623` | Personal Mobility Equipment |
| `http://terminology.hl7.org/CodeSystem/service-type` | `624` | Physical Wellbeing |
| `http://terminology.hl7.org/CodeSystem/service-type` | `625` | Plan Management |
| `http://terminology.hl7.org/CodeSystem/service-type` | `626` | Therapeutic Supports |
| `http://terminology.hl7.org/CodeSystem/service-type` | `627` | Training-Travel Independence |
| `http://terminology.hl7.org/CodeSystem/service-type` | `628` | Vehicle modifications |
| `http://terminology.hl7.org/CodeSystem/service-type` | `629` | Vision Equipment |
| `http://terminology.hl7.org/CodeSystem/service-type` | `63` | Osteopathy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `64` | Pharmacy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `65` | Physiotherapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `66` | Podiatry |
| `http://terminology.hl7.org/CodeSystem/service-type` | `67` | Sexual Health |
| `http://terminology.hl7.org/CodeSystem/service-type` | `68` | Speech Pathology/Therapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `69` | Bereavement Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `7` | Friendly Visiting |
| `http://terminology.hl7.org/CodeSystem/service-type` | `70` | Crisis Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `71` | Family Counselling/Therapy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `72` | Family Violence Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `73` | Financial Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `74` | Generalist Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `75` | Genetic Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `76` | Health Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `77` | Mediation |
| `http://terminology.hl7.org/CodeSystem/service-type` | `78` | Problem Gambling Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `79` | Relationship Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `8` | Home Care/Housekeeping Assistance |
| `http://terminology.hl7.org/CodeSystem/service-type` | `80` | Sexual Assault Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `81` | Trauma Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `82` | Victims of Crime Counselling |
| `http://terminology.hl7.org/CodeSystem/service-type` | `83` | Cemetery Operation |
| `http://terminology.hl7.org/CodeSystem/service-type` | `84` | Cremation |
| `http://terminology.hl7.org/CodeSystem/service-type` | `85` | Death Service Information |
| `http://terminology.hl7.org/CodeSystem/service-type` | `86` | Funeral Services |
| `http://terminology.hl7.org/CodeSystem/service-type` | `87` | Endodontic |
| `http://terminology.hl7.org/CodeSystem/service-type` | `88` | General Dental |
| `http://terminology.hl7.org/CodeSystem/service-type` | `89` | Oral Medicine |
| `http://terminology.hl7.org/CodeSystem/service-type` | `9` | Home Maintenance and Repair |
| `http://terminology.hl7.org/CodeSystem/service-type` | `90` | Oral Surgery |
| `http://terminology.hl7.org/CodeSystem/service-type` | `91` | Orthodontic |
| `http://terminology.hl7.org/CodeSystem/service-type` | `92` | Paediatric Dentistry |
| `http://terminology.hl7.org/CodeSystem/service-type` | `93` | Periodontic |
| `http://terminology.hl7.org/CodeSystem/service-type` | `94` | Prosthodontic |
| `http://terminology.hl7.org/CodeSystem/service-type` | `95` | Acquired Brain Injury Info/Referral |
| `http://terminology.hl7.org/CodeSystem/service-type` | `96` | Disability Advocacy |
| `http://terminology.hl7.org/CodeSystem/service-type` | `97` | Disability Aids & Equipment |
| `http://terminology.hl7.org/CodeSystem/service-type` | `98` | Disability Case Management |
| `http://terminology.hl7.org/CodeSystem/service-type` | `99` | Disability Day Programs/Activities |
