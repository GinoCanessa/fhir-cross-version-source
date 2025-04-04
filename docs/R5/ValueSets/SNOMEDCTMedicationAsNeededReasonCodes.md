Comparison of 
Generated at Friday, April 4, 2025 2:58:59 PM

### SNOMEDCTMedicationAsNeededReasonCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SNOMEDCTMedicationAsNeededReasonCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medication-as-needed-reason` |
| Version | 5.0.0 |
| Description | This value set includes all clinical findings from SNOMED CT - provided as an exemplar value set. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4700` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Dosage` | `Dosage.asNeededFor` | `http://hl7.org/fhir/ValueSet/medication-as-needed-reason` | `Example` | Take "as needed" (for x) |
| `http://hl7.org/fhir/StructureDefinition/ActivityDefinition` | `ActivityDefinition.asNeeded[x]` | `http://hl7.org/fhir/ValueSet/medication-as-needed-reason` | `Example` | Preconditions for service |
| `http://hl7.org/fhir/StructureDefinition/NutritionOrder` | `NutritionOrder.oralDiet.schedule.asNeededFor` | `http://hl7.org/fhir/ValueSet/medication-as-needed-reason` | `Example` | Take 'as needed' for x |
| `http://hl7.org/fhir/StructureDefinition/NutritionOrder` | `NutritionOrder.supplement.schedule.asNeededFor` | `http://hl7.org/fhir/ValueSet/medication-as-needed-reason` | `Example` | Take 'as needed' for x |
| `http://hl7.org/fhir/StructureDefinition/NutritionOrder` | `NutritionOrder.enteralFormula.administration.schedule.asNeededFor` | `http://hl7.org/fhir/ValueSet/medication-as-needed-reason` | `Example` | Take 'as needed' for x |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.asNeeded[x]` | `http://hl7.org/fhir/ValueSet/medication-as-needed-reason` | `Example` | Preconditions for service |
| `http://hl7.org/fhir/StructureDefinition/ServiceRequest` | `ServiceRequest.asNeeded[x]` | `http://hl7.org/fhir/ValueSet/medication-as-needed-reason` | `Example` | Preconditions for service |

### Expansion Failure

Failed to expand this value set: Expansion is limited
