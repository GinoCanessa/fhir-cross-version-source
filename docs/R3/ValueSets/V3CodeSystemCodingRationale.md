Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### v3 Code System CodingRationale

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | v3 Code System CodingRationale |
| Canonical URL | `http://hl7.org/fhir/ValueSet/v3-CodingRationale` |
| Version | 2016-11-11 |
| Description | Identifies how to interpret the instance of the code, codeSystem value in a set of translations.  Since HL7 (or a government body) may mandate that codes from certain code systems be sent in conformant messages, other synonyms that are sent in the translation set need to be distinguished among the originally captured source, the HL7 specified code, or some future role.  When this code is NULL, it indicates that the translation is an undefined type.  When valued, this property must contain one of the following values: SRC - Source (or original) code HL7 - HL7 Specified or Mandated SH - both HL7 mandated and the original code (precoordination) There may be additional values added to this value set as we work through the use of codes in messages and determine other Use Cases requiring special interpretation of the translations. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `2013` |
| Database Concept Count | `8` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |

### Referenced Systems

* `http://hl7.org/fhir/v3/CodingRationale`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/v3/CodingRationale` | `O` | originally produced code |
| `http://hl7.org/fhir/v3/CodingRationale` | `OR` | original and required |
| `http://hl7.org/fhir/v3/CodingRationale` | `P` | post-coded |
| `http://hl7.org/fhir/v3/CodingRationale` | `PR` | post-coded and required |
| `http://hl7.org/fhir/v3/CodingRationale` | `R` | required |
