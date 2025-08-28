### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [Condition](https://hl7.org/fhir/DSTU2/Condition.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [Condition.meta](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.meta](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.implicitRules](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.implicitRules](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.language](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.language](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.text](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.text](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.contained](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.contained](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.identifier](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.identifier](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.patient](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementRenamed` | [Condition.subject](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.encounter](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.encounter](StructureDefinition-ext-R2-Condition.encounter.html) |
| [Condition.asserter](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.asserter](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.dateRecorded](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementRenamed` | [Condition.recordedDate](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.code](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.code](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.category](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.category](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.clinicalStatus](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.clinicalStatus](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.verificationStatus](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.verificationStatus](StructureDefinition-ext-R2-Condition.verificationStatus.html) |
| [Condition.severity](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.severity](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.onset[x]](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.onset](StructureDefinition-ext-R2-Condition.onset.html) |
| [Condition.abatement[x]](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.abatement](StructureDefinition-ext-R2-Condition.abatement.html) |
| [Condition.stage](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.stage](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.stage.id](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.stage.id](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.stage.summary](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.stage.summary](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.stage.assessment](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.stage.assessment](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.evidence](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.evidence](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.evidence.id](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.evidence.id](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.evidence.code](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.evidence.code](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.evidence.detail](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.evidence.detail](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.bodySite](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseElementSameName` | [Condition.bodySite](https://hl7.org/fhir/R4/Condition.html#resource) |
| [Condition.notes](https://hl7.org/fhir/DSTU2/Condition.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.notes](StructureDefinition-ext-R2-Condition.notes.html) |
