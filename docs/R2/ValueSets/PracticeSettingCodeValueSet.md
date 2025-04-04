Comparison of 
Generated at Friday, April 4, 2025 2:58:33 PM

### Practice Setting Code Value Set

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Practice Setting Code Value Set |
| Canonical URL | `http://hl7.org/fhir/ValueSet/c80-practice-codes` |
| Version | 20091109 |
| Description | This is the code representing the clinical specialty of the clinician or provider who interacted with, treated, or provided a service to/for the patient. The value set used for clinical specialty has been limited by HITSP to the value set reproduced from HITSP C80 Table 2-149 Clinical Specialty Value Set Definition. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `41` |
| Database Concept Count | `117` |
| Database Active Concept Count | `117` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Appointment` | `Appointment.type` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` | `Preferred` | The type of appointment that is being booked |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.context.practiceSetting` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` | `Example` | Additional details about where the content was created (e.g. clinical specialty) |
| `http://hl7.org/fhir/StructureDefinition/HealthcareService` | `HealthcareService.serviceType.type` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` | `Preferred` | Type of service delivered or performed |
| `http://hl7.org/fhir/StructureDefinition/ReferralRequest` | `ReferralRequest.serviceRequested` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` | `Example` | Actions requested as part of the referral |
| `http://hl7.org/fhir/StructureDefinition/Schedule` | `Schedule.type` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` | `Preferred` | The schedule type can be used for the categorization of healthcare services or other appointment types |
| `http://hl7.org/fhir/StructureDefinition/Slot` | `Slot.type` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` | `Preferred` | The type of appointments that can be booked into this slot (ideally this would be an identifiable service - which is at a location, rather than the location itself). If provided then this overrides the value provided on the availability resource |

### Referenced Systems

* `http://snomed.info/sct`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://snomed.info/sct` | `394539006` | Pediatric surgery |
| `http://snomed.info/sct` | `394576009` | Surgical-Accident & emergency |
| `http://snomed.info/sct` | `394577000` | Anesthetics |
| `http://snomed.info/sct` | `394578005` | Audiological medicine |
| `http://snomed.info/sct` | `394579002` | Cardiology |
| `http://snomed.info/sct` | `394580004` | Clinical genetics |
| `http://snomed.info/sct` | `394581000` | Community medicine |
| `http://snomed.info/sct` | `394582007` | Dermatology |
| `http://snomed.info/sct` | `394583002` | Endocrinology |
| `http://snomed.info/sct` | `394584008` | Gastroenterology |
| `http://snomed.info/sct` | `394585009` | Obstetrics and gynecology |
| `http://snomed.info/sct` | `394586005` | Gynecology |
| `http://snomed.info/sct` | `394587001` | Psychiatry |
| `http://snomed.info/sct` | `394588006` | Pediatric (Child and adolescent) psychiatry |
| `http://snomed.info/sct` | `394589003` | Nephrology |
| `http://snomed.info/sct` | `394590007` | Thoracic medicine |
| `http://snomed.info/sct` | `394591006` | Neurology |
| `http://snomed.info/sct` | `394592004` | Clinical oncology |
| `http://snomed.info/sct` | `394593009` | Medical oncology |
| `http://snomed.info/sct` | `394594003` | Ophthalmology |
| `http://snomed.info/sct` | `394597005` | Histopathology |
| `http://snomed.info/sct` | `394598000` | Immunopathology |
| `http://snomed.info/sct` | `394599008` | Neuropathology |
| `http://snomed.info/sct` | `394600006` | Clinical pharmacology |
| `http://snomed.info/sct` | `394601005` | Clinical physiology |
| `http://snomed.info/sct` | `394602003` | Rehabilitation |
| `http://snomed.info/sct` | `394604002` | Surgery-Ear, nose and throat surgery |
| `http://snomed.info/sct` | `394605001` | Surgery-Dental-Oral surgery |
| `http://snomed.info/sct` | `394606000` | Surgery-Dentistry-Restorative dentistry |
| `http://snomed.info/sct` | `394607009` | Pediatric dentistry |
| `http://snomed.info/sct` | `394608004` | Surgery-Dental-Orthodontics |
| `http://snomed.info/sct` | `394608004` | Surgery-Dentistry-surgical-Orthodontics |
| `http://snomed.info/sct` | `394609007` | Surgery-general |
| `http://snomed.info/sct` | `394610002` | Surgery-Neurosurgery |
| `http://snomed.info/sct` | `394611003` | Surgery-Plastic surgery |
| `http://snomed.info/sct` | `394612005` | Urology |
| `http://snomed.info/sct` | `394649004` | Nuclear medicine |
| `http://snomed.info/sct` | `394732004` | Surgical specialty--OTHER-NOT LISTED |
| `http://snomed.info/sct` | `394733009` | Medical specialty--OTHER--NOT LISTED |
| `http://snomed.info/sct` | `394801008` | Surgery-Trauma and orthopedics |
| `http://snomed.info/sct` | `394802001` | General medicine |
| `http://snomed.info/sct` | `394803006` | Clinical hematology |
| `http://snomed.info/sct` | `394804000` | Clinical cytogenetics and molecular genetics |
| `http://snomed.info/sct` | `394806003` | Palliative medicine |
| `http://snomed.info/sct` | `394807007` | Infectious diseases |
| `http://snomed.info/sct` | `394808002` | Genito-urinary medicine |
| `http://snomed.info/sct` | `394809005` | Clinical neuro-physiology |
| `http://snomed.info/sct` | `394810000` | Rheumatology |
| `http://snomed.info/sct` | `394811001` | Geriatric medicine |
| `http://snomed.info/sct` | `394812008` | Dental medicine specialties |
| `http://snomed.info/sct` | `394813003` | Medical ophthalmology |
| `http://snomed.info/sct` | `394814009` | General practice |
| `http://snomed.info/sct` | `394821009` | Occupational medicine |
| `http://snomed.info/sct` | `394882004` | Pain management |
| `http://snomed.info/sct` | `394913002` | Psychotherapy |
| `http://snomed.info/sct` | `394914008` | Radiology |
| `http://snomed.info/sct` | `394915009` | General pathology |
| `http://snomed.info/sct` | `394916005` | Hematopathology |
| `http://snomed.info/sct` | `408440000` | Public health medicine |
| `http://snomed.info/sct` | `408441001` | Surgery-Dental-Endodontics |
| `http://snomed.info/sct` | `408443003` | General medical practice |
| `http://snomed.info/sct` | `408444009` | Dental-General dental practice |
| `http://snomed.info/sct` | `408446006` | Gynecological oncology |
| `http://snomed.info/sct` | `408447002` | Respite care |
| `http://snomed.info/sct` | `408448007` | Tropical medicine |
| `http://snomed.info/sct` | `408449004` | Surgery-Dentistry--surgical |
| `http://snomed.info/sct` | `408450004` | Sleep studies |
| `http://snomed.info/sct` | `408454008` | Clinical microbiology |
| `http://snomed.info/sct` | `408455009` | Radiology-Interventional radiology |
| `http://snomed.info/sct` | `408459003` | Pediatric cardiology |
| `http://snomed.info/sct` | `408460008` | Surgery-Dental-Prosthetic dentistry (Prosthodontics) |
| `http://snomed.info/sct` | `408460008` | Surgery-Dental-surgical-Prosthodontics |
| `http://snomed.info/sct` | `408461007` | Surgery-Dental-Periodontal surgery |
| `http://snomed.info/sct` | `408462000` | Burns care |
| `http://snomed.info/sct` | `408463005` | Surgery-Vascular |
| `http://snomed.info/sct` | `408464004` | Surgery-Colorectal surgery |
| `http://snomed.info/sct` | `408465003` | Surgery-Dental-Oral and maxillofacial surgery |
| `http://snomed.info/sct` | `408466002` | Surgery-Cardiac surgery |
| `http://snomed.info/sct` | `408467006` | Adult mental illness |
| `http://snomed.info/sct` | `408468001` | Learning disability |
| `http://snomed.info/sct` | `408469009` | Surgery-Breast surgery |
| `http://snomed.info/sct` | `408470005` | Obstetrics |
| `http://snomed.info/sct` | `408471009` | Surgery-Cardiothoracic transplantation |
| `http://snomed.info/sct` | `408472002` | Hepatology |
| `http://snomed.info/sct` | `408474001` | Surgery-Hepatobiliary and pancreatic surgery |
| `http://snomed.info/sct` | `408475000` | Diabetic medicine |
| `http://snomed.info/sct` | `408476004` | Surgery-Bone and marrow transplantation |
| `http://snomed.info/sct` | `408477008` | Surgery-Transplantation surgery |
| `http://snomed.info/sct` | `408478003` | Critical care medicine |
| `http://snomed.info/sct` | `408480009` | Clinical immunology |
| `http://snomed.info/sct` | `409967009` | Toxicology |
| `http://snomed.info/sct` | `409968004` | Preventive medicine |
| `http://snomed.info/sct` | `410001006` | Military medicine |
| `http://snomed.info/sct` | `410005002` | Dive medicine |
| `http://snomed.info/sct` | `416304004` | Osteopathic manipulative medicine |
| `http://snomed.info/sct` | `418002000` | Pediatric oncology |
| `http://snomed.info/sct` | `418018006` | Surgery-Dermatologic surgery |
| `http://snomed.info/sct` | `418058008` | Pediatric gastroenterology |
| `http://snomed.info/sct` | `418112009` | Pulmonary medicine |
| `http://snomed.info/sct` | `418535003` | Pediatric immunology |
| `http://snomed.info/sct` | `418652005` | Pediatric hematology |
| `http://snomed.info/sct` | `418862001` | Pediatric infectious diseases |
| `http://snomed.info/sct` | `418960008` | Otolaryngology |
| `http://snomed.info/sct` | `419043006` | Urological oncology |
| `http://snomed.info/sct` | `419170002` | Pediatric pulmonology |
| `http://snomed.info/sct` | `419192003` | Internal medicine |
| `http://snomed.info/sct` | `419321007` | Surgical oncology |
| `http://snomed.info/sct` | `419365004` | Pediatric nephrology |
| `http://snomed.info/sct` | `419472004` | Pediatric rheumatology |
| `http://snomed.info/sct` | `419610006` | Pediatric endocrinology |
| `http://snomed.info/sct` | `419772000` | Family practice |
| `http://snomed.info/sct` | `419815003` | Radiation oncology |
| `http://snomed.info/sct` | `419983000` | Pediatric ophthalmology |
| `http://snomed.info/sct` | `420112009` | Pediatric surgery-bone marrow transplantation |
| `http://snomed.info/sct` | `420208008` | Pediatric genetics |
| `http://snomed.info/sct` | `421661004` | Blood banking and transfusion medicine |
| `http://snomed.info/sct` | `422191005` | Ophthalmic surgery |
