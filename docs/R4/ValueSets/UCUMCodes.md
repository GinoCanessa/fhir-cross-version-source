Comparison of 
Generated at Friday, April 4, 2025 2:58:45 PM

### UCUMCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | UCUMCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/ucum-units` |
| Version | 4.0.1 |
| Description | Unified Code for Units of Measure (UCUM). This value set includes all UCUM codes |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `2816` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/EffectEvidenceSynthesis` | `EffectEvidenceSynthesis.effectEstimate.unitOfMeasure` | `http://hl7.org/fhir/ValueSet/ucum-units\|4.0.1` | `Required` | What unit is the outcome described in? |
| `http://hl7.org/fhir/StructureDefinition/ObservationDefinition` | `ObservationDefinition.quantitativeDetails.customaryUnit` | `http://hl7.org/fhir/ValueSet/ucum-units` | `Extensible` | Customary unit for quantitative results |
| `http://hl7.org/fhir/StructureDefinition/ObservationDefinition` | `ObservationDefinition.quantitativeDetails.unit` | `http://hl7.org/fhir/ValueSet/ucum-units` | `Extensible` | SI unit for quantitative results |
| `http://hl7.org/fhir/StructureDefinition/ResearchElementDefinition` | `ResearchElementDefinition.characteristic.unitOfMeasure` | `http://hl7.org/fhir/ValueSet/ucum-units\|4.0.1` | `Required` | What unit is the outcome described in? |
| `http://hl7.org/fhir/StructureDefinition/RiskEvidenceSynthesis` | `RiskEvidenceSynthesis.riskEstimate.unitOfMeasure` | `http://hl7.org/fhir/ValueSet/ucum-units\|4.0.1` | `Required` | What unit is the outcome described in? |
| `http://hl7.org/fhir/StructureDefinition/elementdefinition-allowedUnits` | `Extension.value[x]` | `http://hl7.org/fhir/ValueSet/ucum-units\|4.0.1` | `Required` | Value of extension |

### Expansion Failure

Failed to expand this value set: Expansion is limited
