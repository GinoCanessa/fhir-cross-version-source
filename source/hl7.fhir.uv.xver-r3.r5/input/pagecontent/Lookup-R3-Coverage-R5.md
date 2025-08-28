### Lookup for [FHIR R3](https://hl7.org/fhir/STU3/) [Coverage](https://hl7.org/fhir/STU3/Coverage.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R3) | Usage | Target |
| -------------- | ----- | ------ |
| [Coverage.meta](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.meta](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.implicitRules](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.implicitRules](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.language](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.language](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.text](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.text](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.contained](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.contained](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.identifier](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseOneOf` | [Coverage.identifier](https://hl7.org/fhir/R5/Coverage.html#resource)<br />[Coverage.identifier](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.status](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.status](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.type](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.type](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.policyHolder](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.policyHolder](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.subscriber](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.subscriber](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.subscriberId](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Coverage.subscriberId](StructureDefinition-ext-R3-Coverage.subscriberId.html) |
| [Coverage.beneficiary](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.beneficiary](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.relationship](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.relationship](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.period](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.period](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.payor](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Coverage.payor](StructureDefinition-ext-R3-Coverage.payor.html) |
| [Coverage.grouping](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementRenamed` | [Coverage.class](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.grouping.group](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Coverage.grouping.group](StructureDefinition-ext-R3-Coverage.gr.group.html) |
| [Coverage.grouping.groupDisplay](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Coverage.grouping.groupDisplay](StructureDefinition-ext-R3-Coverage.gr.groupDisplay.html) |
| [Coverage.grouping.subGroup](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Coverage.grouping.subGroup](StructureDefinition-ext-R3-Coverage.gr.subGroup.html) |
| [Coverage.grouping.subGroupDisplay](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Coverage.grouping.subGroupDisplay](StructureDefinition-ext-R3-Coverage.gr.subGroupDisplay.html) |
| [Coverage.grouping.plan](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Coverage.grouping.plan](StructureDefinition-ext-R3-Coverage.gr.plan.html) |
| [Coverage.grouping.planDisplay](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Coverage.grouping.planDisplay](StructureDefinition-ext-R3-Coverage.gr.planDisplay.html) |
| [Coverage.grouping.subPlan](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Coverage.grouping.subPlan](StructureDefinition-ext-R3-Coverage.gr.subPlan.html) |
| [Coverage.grouping.subPlanDisplay](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Coverage.grouping.subPlanDisplay](StructureDefinition-ext-R3-Coverage.gr.subPlanDisplay.html) |
| [Coverage.grouping.class](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Coverage.grouping.class](StructureDefinition-ext-R3-Coverage.gr.class.html) |
| [Coverage.grouping.classDisplay](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Coverage.grouping.classDisplay](StructureDefinition-ext-R3-Coverage.gr.classDisplay.html) |
| [Coverage.grouping.subClass](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Coverage.grouping.subClass](StructureDefinition-ext-R3-Coverage.gr.subClass.html) |
| [Coverage.grouping.subClassDisplay](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Coverage.grouping.subClassDisplay](StructureDefinition-ext-R3-Coverage.gr.subClassDisplay.html) |
| [Coverage.dependent](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.dependent](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.sequence](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Coverage.sequence](StructureDefinition-ext-R3-Coverage.sequence.html) |
| [Coverage.order](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.order](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.network](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.network](https://hl7.org/fhir/R5/Coverage.html#resource) |
| [Coverage.contract](https://hl7.org/fhir/STU3/Coverage.html#resource) | `UseElementSameName` | [Coverage.contract](https://hl7.org/fhir/R5/Coverage.html#resource) |
