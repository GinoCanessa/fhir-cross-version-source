### Lookup for FHIR R2 Coverage for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Coverage.id | UseElementSameName | Coverage.id |
| Coverage.meta | UseElementSameName | Coverage.meta |
| Coverage.implicitRules | UseElementSameName | Coverage.implicitRules |
| Coverage.language | UseElementSameName | Coverage.language |
| Coverage.text | UseElementSameName | Coverage.text |
| Coverage.contained | UseElementSameName | Coverage.contained |
| Coverage.extension | UseElementSameName | Coverage.extension |
| Coverage.modifierExtension | UseElementSameName | Coverage.modifierExtension |
| Coverage.issuer | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Coverage.issuer |
| Coverage.bin | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Coverage.bin |
| Coverage.period | UseElementSameName | Coverage.period |
| Coverage.type | UseElementSameName | Coverage.type |
| Coverage.subscriberId | UseElementSameName | Coverage.subscriberId |
| Coverage.identifier | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Coverage.identifier |
| Coverage.group | UseElementRenamed | Coverage.grouping.group |
| Coverage.plan | UseElementRenamed | Coverage.grouping.plan |
| Coverage.subPlan | UseElementRenamed | Coverage.grouping.subPlan |
| Coverage.dependent | UseElementSameName | Coverage.dependent |
| Coverage.sequence | UseElementSameName | Coverage.sequence |
| Coverage.subscriber | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Coverage.subscriber |
| Coverage.network | UseElementSameName | Coverage.network |
| Coverage.contract | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Coverage.contract |
