Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### ClinVar

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ClinVar |
| Canonical URL | `http://hl7.org/fhir/ValueSet/clinvar` |
| Version | 4.3.0 |
| Description | NCBI central repository for curating pathogenicity of potentially clinically relevant variants |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `3606` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/observation-geneticsAminoAcidChange` | `Extension.extension.value[x]` | `http://hl7.org/fhir/ValueSet/clinvar` | `Preferred` | Value of extension |
| `http://hl7.org/fhir/StructureDefinition/observation-geneticsVariant` | `Extension.extension.value[x]` | `http://hl7.org/fhir/ValueSet/clinvar` | `Preferred` | Value of extension |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/clinvar|4.3.0: Operation expand failed: creating the required expansion failed with message "The ValueSet expander cannot find codesystem 'http://www.ncbi.nlm.nih.gov/clinvar', so the expansion cannot be completed.".
