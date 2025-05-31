### Lookup for FHIR R2 Coverage for use in FHIR R4

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
| Coverage.bin | UseElementRenamed | Coverage.identifier |
| Coverage.period | UseElementSameName | Coverage.period |
| Coverage.type | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Coverage.type |
| Coverage.subscriberId | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Coverage.subscriberId |
| Coverage.identifier | UseElementSameName | Coverage.identifier |
| Coverage.group | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Coverage.group |
| Coverage.plan | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Coverage.plan |
| Coverage.subPlan | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Coverage.subPlan |
| Coverage.dependent | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Coverage.dependent |
| Coverage.sequence | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Coverage.sequence |
| Coverage.subscriber | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Coverage.subscriber |
| Coverage.network | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Coverage.network |
| Coverage.contract | UseElementSameName | Coverage.contract |
