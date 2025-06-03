### Lookup for FHIR R4B Dosage for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Dosage.id | UseElementSameName | Dosage.id |
| Dosage.extension | UseElementSameName | Dosage.extension |
| Dosage.modifierExtension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Dosage.modifierExtension |
| Dosage.sequence | UseElementSameName | Dosage.sequence |
| Dosage.text | UseElementSameName | Dosage.text |
| Dosage.additionalInstruction | UseElementSameName | Dosage.additionalInstruction |
| Dosage.patientInstruction | UseElementSameName | Dosage.patientInstruction |
| Dosage.timing | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Dosage.timing |
| Dosage.asNeeded[x] | UseOneOfElements | Dosage.asNeeded[x],Dosage.asNeeded[x] |
| Dosage.site | UseElementSameName | Dosage.site |
| Dosage.route | UseElementSameName | Dosage.route |
| Dosage.method | UseElementSameName | Dosage.method |
| Dosage.doseAndRate | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Dosage.doseAndRate |
| Dosage.doseAndRate.id | UseExtensionFromAncestor | - |
| Dosage.doseAndRate.extension | UseExtensionFromAncestor | - |
| Dosage.doseAndRate.type | UseExtensionFromAncestor | - |
| Dosage.doseAndRate.dose[x] | UseExtensionFromAncestor | - |
| Dosage.doseAndRate.rate[x] | UseExtensionFromAncestor | - |
| Dosage.maxDosePerPeriod | UseElementSameName | Dosage.maxDosePerPeriod |
| Dosage.maxDosePerAdministration | UseElementSameName | Dosage.maxDosePerAdministration |
| Dosage.maxDosePerLifetime | UseElementSameName | Dosage.maxDosePerLifetime |
