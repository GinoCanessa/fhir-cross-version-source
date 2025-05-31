### Lookup for FHIR R5 Dosage for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Dosage.id | UseElementSameName | Dosage.id |
| Dosage.extension | UseElementSameName | Dosage.extension |
| Dosage.modifierExtension | UseElementSameName | Dosage.modifierExtension |
| Dosage.sequence | UseElementSameName | Dosage.sequence |
| Dosage.text | UseElementSameName | Dosage.text |
| Dosage.additionalInstruction | UseElementSameName | Dosage.additionalInstruction |
| Dosage.patientInstruction | UseElementSameName | Dosage.patientInstruction |
| Dosage.timing | UseElementSameName | Dosage.timing |
| Dosage.asNeeded | UseElementSameName | Dosage.asNeeded[x] |
| Dosage.asNeededFor | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Dosage.asNeededFor |
| Dosage.site | UseElementSameName | Dosage.site |
| Dosage.route | UseElementSameName | Dosage.route |
| Dosage.method | UseElementSameName | Dosage.method |
| Dosage.doseAndRate | UseElementSameName | Dosage.doseAndRate |
| Dosage.doseAndRate.id | UseElementSameName | Dosage.doseAndRate.id |
| Dosage.doseAndRate.extension | UseElementSameName | Dosage.doseAndRate.extension |
| Dosage.doseAndRate.type | UseElementSameName | Dosage.doseAndRate.type |
| Dosage.doseAndRate.dose[x] | UseElementSameName | Dosage.doseAndRate.dose[x] |
| Dosage.doseAndRate.rate[x] | UseElementSameName | Dosage.doseAndRate.rate[x] |
| Dosage.maxDosePerPeriod | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Dosage.maxDosePerPeriod |
| Dosage.maxDosePerAdministration | UseElementSameName | Dosage.maxDosePerAdministration |
| Dosage.maxDosePerLifetime | UseElementSameName | Dosage.maxDosePerLifetime |
