### Lookup for FHIR R5 Dosage for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Dosage.id | UseElementSameName | Dosage.id |
| Dosage.extension | UseElementSameName | Dosage.extension |
| Dosage.modifierExtension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Dosage.modifierExtension |
| Dosage.sequence | UseElementSameName | Dosage.sequence |
| Dosage.text | UseElementSameName | Dosage.text |
| Dosage.additionalInstruction | UseElementSameName | Dosage.additionalInstruction |
| Dosage.patientInstruction | UseElementSameName | Dosage.patientInstruction |
| Dosage.timing | UseElementSameName | Dosage.timing |
| Dosage.asNeeded | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Dosage.asNeeded |
| Dosage.asNeededFor | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Dosage.asNeededFor |
| Dosage.site | UseElementSameName | Dosage.site |
| Dosage.route | UseElementSameName | Dosage.route |
| Dosage.method | UseElementSameName | Dosage.method |
| Dosage.doseAndRate | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Dosage.doseAndRate |
| Dosage.doseAndRate.id | UseExtensionFromAncestor | - |
| Dosage.doseAndRate.extension | UseExtensionFromAncestor | - |
| Dosage.doseAndRate.type | UseExtensionFromAncestor | - |
| Dosage.doseAndRate.dose[x] | UseExtensionFromAncestor | - |
| Dosage.doseAndRate.rate[x] | UseExtensionFromAncestor | - |
| Dosage.maxDosePerPeriod | UseElementSameName | Dosage.maxDosePerPeriod |
| Dosage.maxDosePerAdministration | UseElementSameName | Dosage.maxDosePerAdministration |
| Dosage.maxDosePerLifetime | UseElementSameName | Dosage.maxDosePerLifetime |
