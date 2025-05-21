### Lookup for FHIR R3 Dosage for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Dosage.id | UseElementSameName | Dosage.id |
| Dosage.extension | UseElementSameName | Dosage.extension |
| Dosage.sequence | UseElementSameName | Dosage.sequence |
| Dosage.text | UseElementSameName | Dosage.text |
| Dosage.additionalInstruction | UseElementSameName | Dosage.additionalInstruction |
| Dosage.patientInstruction | UseElementSameName | Dosage.patientInstruction |
| Dosage.timing | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Dosage.timing |
| Dosage.asNeeded[x] | UseElementSameName | Dosage.asNeeded[x] |
| Dosage.site | UseElementSameName | Dosage.site |
| Dosage.route | UseElementSameName | Dosage.route |
| Dosage.method | UseElementSameName | Dosage.method |
| Dosage.dose[x] | UseElementRenamed | Dosage.doseAndRate.dose[x] |
| Dosage.maxDosePerPeriod | UseElementSameName | Dosage.maxDosePerPeriod |
| Dosage.maxDosePerAdministration | UseElementSameName | Dosage.maxDosePerAdministration |
| Dosage.maxDosePerLifetime | UseElementSameName | Dosage.maxDosePerLifetime |
| Dosage.rate[x] | UseElementRenamed | Dosage.doseAndRate.rate[x] |
