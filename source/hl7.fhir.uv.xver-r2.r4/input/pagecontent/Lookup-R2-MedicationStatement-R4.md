### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [MedicationStatement](https://hl7.org/fhir/DSTU2/MedicationStatement.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [MedicationStatement.meta](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseElementSameName` | [MedicationStatement.meta](https://hl7.org/fhir/R4/MedicationStatement.html#resource) |
| [MedicationStatement.implicitRules](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseElementSameName` | [MedicationStatement.implicitRules](https://hl7.org/fhir/R4/MedicationStatement.html#resource) |
| [MedicationStatement.language](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseElementSameName` | [MedicationStatement.language](https://hl7.org/fhir/R4/MedicationStatement.html#resource) |
| [MedicationStatement.text](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseElementSameName` | [MedicationStatement.text](https://hl7.org/fhir/R4/MedicationStatement.html#resource) |
| [MedicationStatement.contained](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseElementSameName` | [MedicationStatement.contained](https://hl7.org/fhir/R4/MedicationStatement.html#resource) |
| [MedicationStatement.identifier](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseElementSameName` | [MedicationStatement.identifier](https://hl7.org/fhir/R4/MedicationStatement.html#resource) |
| [MedicationStatement.patient](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseElementRenamed` | [MedicationStatement.subject](https://hl7.org/fhir/R4/MedicationStatement.html#resource) |
| [MedicationStatement.informationSource](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseElementSameName` | [MedicationStatement.informationSource](https://hl7.org/fhir/R4/MedicationStatement.html#resource) |
| [MedicationStatement.dateAsserted](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseElementSameName` | [MedicationStatement.dateAsserted](https://hl7.org/fhir/R4/MedicationStatement.html#resource) |
| [MedicationStatement.status](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseElementSameName` | [MedicationStatement.status](https://hl7.org/fhir/R4/MedicationStatement.html#resource) |
| [MedicationStatement.wasNotTaken](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.wasNotTaken](StructureDefinition-ext-R2-MedicationStatement.wasNotTaken.html) |
| [MedicationStatement.reasonNotTaken](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseElementRenamed` | [MedicationStatement.reasonCode](https://hl7.org/fhir/R4/MedicationStatement.html#resource) |
| [MedicationStatement.reasonForUse[x]](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.reasonForUse](StructureDefinition-ext-R2-MedicationStatement.reasonForUse.html) |
| [MedicationStatement.effective[x]](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseElementSameName` | [MedicationStatement.effective[x]](https://hl7.org/fhir/R4/MedicationStatement.html#resource) |
| [MedicationStatement.note](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.note](StructureDefinition-ext-R2-MedicationStatement.note.html) |
| [MedicationStatement.supportingInformation](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseElementRenamed` | [MedicationStatement.derivedFrom](https://hl7.org/fhir/R4/MedicationStatement.html#resource) |
| [MedicationStatement.medication[x]](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseElementSameName` | [MedicationStatement.medication[x]](https://hl7.org/fhir/R4/MedicationStatement.html#resource) |
| [MedicationStatement.dosage](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.dosage](StructureDefinition-ext-R2-MedicationStatement.dosage.html) |
| [MedicationStatement.dosage.id](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseExtensionFromAncestor` | - |
| [MedicationStatement.dosage.text](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseExtensionFromAncestor` | - |
| [MedicationStatement.dosage.timing](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseExtensionFromAncestor` | - |
| [MedicationStatement.dosage.asNeeded[x]](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseExtensionFromAncestor` | - |
| [MedicationStatement.dosage.site[x]](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseExtensionFromAncestor` | - |
| [MedicationStatement.dosage.route](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseExtensionFromAncestor` | - |
| [MedicationStatement.dosage.method](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseExtensionFromAncestor` | - |
| [MedicationStatement.dosage.quantity[x]](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseExtensionFromAncestor` | - |
| [MedicationStatement.dosage.rate[x]](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseExtensionFromAncestor` | - |
| [MedicationStatement.dosage.maxDosePerPeriod](https://hl7.org/fhir/DSTU2/MedicationStatement.html#resource) | `UseExtensionFromAncestor` | - |
