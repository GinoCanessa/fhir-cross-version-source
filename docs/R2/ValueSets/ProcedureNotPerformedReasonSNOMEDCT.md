Comparison of 
Generated at Thursday, April 3, 2025 8:18:04 AM

### Procedure Not Performed Reason (SNOMED-CT)

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Procedure Not Performed Reason (SNOMED-CT) |
| Canonical URL | `http://hl7.org/fhir/ValueSet/procedure-not-performed-reason` |
| Version | 1.0.2 |
| Description | Situation codes describing the reason that a procedure, which might otherwise be expected, was not performed, or a procedure that was started and was not completed. Consists of SNOMED CT codes, children of procedure contraindicated (183932001), procedure discontinued (416406003), procedure not done (416237000), procedure not indicated (428119001), procedure not offered (416064006), procedure not wanted (416432009), procedure refused (183944003), and procedure stopped (394908001). |
| Status | `Active` |
| Has Escape Valve Code | `` |
| Database Key | `285` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.reasonNotPerformed` | `http://hl7.org/fhir/ValueSet/procedure-not-performed-reason` | `Example` | Reason procedure was not performed |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/procedure-not-performed-reason|1.0.2: Operation expand failed: creating the required expansion failed with message "Cannot find codesystem 'http://snomed.info/sct', so the defined filter(s) cannot be applied.".
