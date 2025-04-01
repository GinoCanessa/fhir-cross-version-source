Comparison of 
Generated at Tuesday, April 1, 2025 1:39:10 PM

### InformationSensitivityPolicy

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | InformationSensitivityPolicy |
| Canonical URL | `http://hl7.org/fhir/ValueSet/v3-InformationSensitivityPolicy` |
| Version | 2014-03-26 |
| Description | Sensitivity codes are not useful for interoperability outside of a policy domain because sensitivity policies are typically localized and vary drastically across policy domains even for the same information category because of differing organizational business rules, security policies, and jurisdictional requirements.  For example, an "employee" sensitivity code would make little sense for use outside of a policy domain.   "Taboo" would rarely be useful outside of a policy domain unless there are jurisdictional requirements requiring that a provider disclose sensitive information to a patient directly. Sensitivity codes may be more appropriate in a legacy system's Master Files in order to notify those who access a patient's orders and observations about the sensitivity policies that apply.  Newer systems may have a security engine that uses a sensitivity policy's criteria directly. The specializable Sensitivity Act.code may be useful in some scenarious if used in combination with a sensitivity identifier and/or Act.title. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `2065` |
| Database Concept Count | `33` |
| Database Active Concept Count | `28` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |

### Referenced Systems

* `http://hl7.org/fhir/v3/ActCode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/v3/ActCode` | `ADOL` | adolescent information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `B` | business information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `CEL` | celebrity information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `DEMO` | all demographic information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `DIA` | diagnosis information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `DOB` | date of birth information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `DRGIS` | drug information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `EMP` | employee information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `EMPL` | employer information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `ETH` | substance abuse information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `GDIS` | genetic disease information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `GENDER` | gender and sexual orientation information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `HIV` | HIV/AIDS information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `LIVARG` | living arrangement information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `LOCIS` | location information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `MARST` | marital status information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `PDS` | patient default sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `PRS` | patient requested sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `PSY` | psychiatry information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `RACE` | race information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `REL` | religion information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `SCA` | sickle cell anemia |
| `http://hl7.org/fhir/v3/ActCode` | `SDV` | sexual assault, abuse, or domestic violence information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `SEX` | sexuality and reproductive health information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `SICKLE` | sickle cell |
| `http://hl7.org/fhir/v3/ActCode` | `SOC` | social services sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `SSP` | sensitive service provider information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `STD` | sexually transmitted disease information sensitivity |
| `http://hl7.org/fhir/v3/ActCode` | `TBOO` | taboo |
| `http://hl7.org/fhir/v3/ActCode` | `_ActInformationSensitivityPolicy` | ActInformationSensitivityPolicy |
| `http://hl7.org/fhir/v3/ActCode` | `_EntitySensitivityPolicyType` | EntityInformationSensitivityPolicy |
| `http://hl7.org/fhir/v3/ActCode` | `_InformationSensitivityPolicy` | InformationSensitivityPolicy |
| `http://hl7.org/fhir/v3/ActCode` | `_RoleInformationSensitivityPolicy` | RoleInformationSensitivityPolicy |
