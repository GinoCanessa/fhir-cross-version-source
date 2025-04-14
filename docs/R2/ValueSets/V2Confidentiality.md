Comparison of 
Generated at Monday, April 14, 2025 6:17:14 PM

### v2 Confidentiality

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | v2 Confidentiality |
| Canonical URL | `http://hl7.org/fhir/ValueSet/v2-0907` |
| Version | 2.8.2 |
| Description | FHIR Value set/code system definition for HL7 v2 table 0907 ( Confidentiality) |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `826` |
| Database Concept Count | `14` |
| Database Active Concept Count | `14` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |

### Referenced Systems

* `http://hl7.org/fhir/v2/0907`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/v2/0907` | `B` | Business - Since the service class can represent knowledge structures that may be considered a trade or business secret, there is sometimes (though rarely) the need to flag those items as of business level confidentiality.  However, no patient related inf |
| `http://hl7.org/fhir/v2/0907` | `C` | Celebrity - Celebrities are people of public interest (VIP) including employees, whose information require special protection. |
| `http://hl7.org/fhir/v2/0907` | `D` | Clinician - Only clinicians may see this item, billing and administration persons can not access this item without special permission. |
| `http://hl7.org/fhir/v2/0907` | `ETH` | Substance abuse related - Alcohol/drug-abuse related item |
| `http://hl7.org/fhir/v2/0907` | `HIV` | HIV Related - HIV and AIDS related item |
| `http://hl7.org/fhir/v2/0907` | `I` | Individual - Access only to individual persons who are mentioned explicitly as actors of this service and whose actor type warrants that access (cf. to actor typed code). |
| `http://hl7.org/fhir/v2/0907` | `L` | Low - No patient record item can be of low confidentiality.  However, some service objects are not patient related and therefore may have low confidentiality. |
| `http://hl7.org/fhir/v2/0907` | `N` | Normal - Normal confidentiality rules (according to good health care practice) apply, that is, only authorized individuals with a legitimate medical or business need may access this item. |
| `http://hl7.org/fhir/v2/0907` | `PSY` | Psychiatry related - Psychiatry related item |
| `http://hl7.org/fhir/v2/0907` | `R` | Restricted - Restricted access, e.g. only to providers having a current care relationship to the patient. |
| `http://hl7.org/fhir/v2/0907` | `S` | Sensitive - Information for which the patient seeks heightened confidentiality.  Sensitive information is not to be shared with family members.  Information reported by the patient about family members is sensitive by default.  Flag can be set or cleared |
| `http://hl7.org/fhir/v2/0907` | `SDV` | Sexual and domestic violence related - Sexual assault / domestic violence related item |
| `http://hl7.org/fhir/v2/0907` | `T` | Taboo - Information not to be disclosed or discussed with patient except through physician assigned to patient in this case.  This is usually a temporary constraint only; example use is a new fatal diagnosis or finding, such as malignancy or HIV. |
| `http://hl7.org/fhir/v2/0907` | `V` | Very restricted - Very restricted access as declared by the Privacy Officer of the record holder. |
