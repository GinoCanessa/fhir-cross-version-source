### Lookup for FHIR R5 Dosage for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Dosage.id | UseElementRenamed | Dosage.id |
| Dosage.extension | UseElementRenamed | Dosage.extension |
| Dosage.modifierExtension | UseElementRenamed | Dosage.modifierExtension |
| Dosage.sequence | UseElementRenamed | Dosage.sequence |
| Dosage.text | UseElementRenamed | Dosage.text |
| Dosage.additionalInstruction | UseElementRenamed | Dosage.additionalInstruction |
| Dosage.patientInstruction | UseElementRenamed | Dosage.patientInstruction |
| Dosage.timing | UseElementRenamed | Dosage.timing |
| Dosage.asNeeded | UseElementRenamed | Dosage.asNeeded[x] |
| Dosage.asNeededFor | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Dosage.asNeededFor |
| Dosage.site | UseElementRenamed | Dosage.site |
| Dosage.route | UseElementRenamed | Dosage.route |
| Dosage.method | UseElementRenamed | Dosage.method |
| Dosage.doseAndRate | UseElementRenamed | Dosage.doseAndRate |
| Dosage.doseAndRate.id | UseElementRenamed | Dosage.doseAndRate.id |
| Dosage.doseAndRate.extension | UseElementRenamed | Dosage.doseAndRate.extension |
| Dosage.doseAndRate.type | UseElementRenamed | Dosage.doseAndRate.type |
| Dosage.doseAndRate.dose[x] | UseElementRenamed | Dosage.doseAndRate.dose[x] |
| Dosage.doseAndRate.rate[x] | UseElementRenamed | Dosage.doseAndRate.rate[x] |
| Dosage.maxDosePerPeriod | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Dosage.maxDosePerPeriod |
| Dosage.maxDosePerAdministration | UseElementRenamed | Dosage.maxDosePerAdministration |
| Dosage.maxDosePerLifetime | UseElementRenamed | Dosage.maxDosePerLifetime |
