### Lookup for [FHIR R3](https://hl7.org/fhir/STU3/) [Immunization](https://hl7.org/fhir/STU3/Immunization.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R3) | Usage | Target |
| -------------- | ----- | ------ |
| [Immunization.meta](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.meta](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.implicitRules](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.implicitRules](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.language](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.language](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.text](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.text](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.contained](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.contained](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.identifier](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.identifier](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.status](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.status](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.notGiven](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Immunization.notGiven](StructureDefinition-ext-R3-Immunization.notGiven.html) |
| [Immunization.vaccineCode](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.vaccineCode](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.patient](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.patient](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.encounter](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.encounter](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.date](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementRenamed` | [Immunization.occurrence[x]](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.primarySource](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.primarySource](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.reportOrigin](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Immunization.reportOrigin](StructureDefinition-ext-R3-Immunization.reportOrigin.html) |
| [Immunization.location](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.location](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.manufacturer](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Immunization.manufacturer](StructureDefinition-ext-R3-Immunization.manufacturer.html) |
| [Immunization.lotNumber](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.lotNumber](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.expirationDate](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.expirationDate](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.site](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.site](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.route](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.route](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.doseQuantity](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.doseQuantity](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.practitioner](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementRenamed` | [Immunization.performer](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.practitioner.role](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementRenamed` | [Immunization.performer.function](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.practitioner.actor](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseOneOf` | [Immunization.performer.actor](https://hl7.org/fhir/R5/Immunization.html#resource)<br />[Immunization.performer.actor](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.note](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.note](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.explanation](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Immunization.explanation](StructureDefinition-ext-R3-Immunization.explanation.html) |
| [Immunization.explanation.reason](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseExtensionFromAncestor` | - |
| [Immunization.explanation.reasonNotGiven](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseExtensionFromAncestor` | - |
| [Immunization.reaction](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.reaction](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.reaction.date](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.reaction.date](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.reaction.detail](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Immunization.reaction.detail](StructureDefinition-ext-R3-Immunization.re.detail.html) |
| [Immunization.reaction.reported](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementSameName` | [Immunization.reaction.reported](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.vaccinationProtocol](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementRenamed` | [Immunization.protocolApplied](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.vaccinationProtocol.doseSequence](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Immunization.vaccinationProtocol.doseSequence](StructureDefinition-ext-R3-Immunization.va.doseSequence.html) |
| [Immunization.vaccinationProtocol.description](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Immunization.vaccinationProtocol.description](StructureDefinition-ext-R3-Immunization.va.description.html) |
| [Immunization.vaccinationProtocol.authority](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementRenamed` | [Immunization.protocolApplied.authority](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.vaccinationProtocol.series](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementRenamed` | [Immunization.protocolApplied.series](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.vaccinationProtocol.seriesDoses](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Immunization.vaccinationProtocol.seriesDoses](StructureDefinition-ext-R3-Immunization.va.seriesDoses.html) |
| [Immunization.vaccinationProtocol.targetDisease](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseElementRenamed` | [Immunization.protocolApplied.targetDisease](https://hl7.org/fhir/R5/Immunization.html#resource) |
| [Immunization.vaccinationProtocol.doseStatus](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Immunization.vaccinationProtocol.doseStatus](StructureDefinition-ext-R3-Immunization.va.doseStatus.html) |
| [Immunization.vaccinationProtocol.doseStatusReason](https://hl7.org/fhir/STU3/Immunization.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Immunization.vaccinationProtocol.doseStatusReason](StructureDefinition-ext-R3-Immunization.va.doseStatusReason.html) |
