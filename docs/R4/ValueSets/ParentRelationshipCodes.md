Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### ParentRelationshipCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ParentRelationshipCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/parent-relationship-codes` |
| Version | 4.0.1 |
| Description | The value set includes the v3 RoleCode PRN (parent), TWIN (twin) and all of their specializations.  It covers the relationships needed to establish genetic pedigree relationships between family members. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2631` |
| Database Concept Count | `21` |
| Database Active Concept Count | `21` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/family-member-history-genetics-parent` | `Extension.extension.value[x]` | `http://hl7.org/fhir/ValueSet/parent-relationship-codes\|4.0.1` | `Required` | Value of extension |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-RoleCode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `ADOPTF` | adoptive father |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `ADOPTM` | adoptive mother |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `ADOPTP` | adoptive parent |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `FTH` | father |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `FTHFOST` | foster father |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `FTWIN` | fraternal twin |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `GESTM` | gestational mother |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `ITWIN` | identical twin |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `MTH` | mother |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `MTHFOST` | foster mother |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `NFTH` | natural father |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `NFTHF` | natural father of fetus |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `NMTH` | natural mother |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `NMTHF` | natural mother of fetus |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `NPRN` | natural parent |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `PRN` | parent |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `PRNFOST` | foster parent |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `STPFTH` | stepfather |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `STPMTH` | stepmother |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `STPPRN` | step parent |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `TWIN` | twin |
