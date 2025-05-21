### Lookup for FHIR R3 VisionPrescription for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| VisionPrescription.id | UseElementSameName | VisionPrescription.id |
| VisionPrescription.meta | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.meta |
| VisionPrescription.implicitRules | UseElementSameName | VisionPrescription.implicitRules |
| VisionPrescription.language | UseElementSameName | VisionPrescription.language |
| VisionPrescription.text | UseElementSameName | VisionPrescription.text |
| VisionPrescription.contained | UseElementSameName | VisionPrescription.contained |
| VisionPrescription.extension | UseElementSameName | VisionPrescription.extension |
| VisionPrescription.modifierExtension | UseElementSameName | VisionPrescription.modifierExtension |
| VisionPrescription.identifier | UseElementSameName | VisionPrescription.identifier |
| VisionPrescription.status | UseElementSameName | VisionPrescription.status |
| VisionPrescription.patient | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.patient |
| VisionPrescription.encounter | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.encounter |
| VisionPrescription.dateWritten | UseElementSameName | VisionPrescription.dateWritten |
| VisionPrescription.prescriber | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.prescriber |
| VisionPrescription.reason[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.reason |
| VisionPrescription.dispense | UseElementRenamed | VisionPrescription.lensSpecification |
| VisionPrescription.dispense.id | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.dispense.id |
| VisionPrescription.dispense.extension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.dispense.extension |
| VisionPrescription.dispense.modifierExtension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.dispense.modifierExtension |
| VisionPrescription.dispense.product | UseElementRenamed | VisionPrescription.lensSpecification.product |
| VisionPrescription.dispense.eye | UseElementRenamed | VisionPrescription.lensSpecification.eye |
| VisionPrescription.dispense.sphere | UseElementRenamed | VisionPrescription.lensSpecification.sphere |
| VisionPrescription.dispense.cylinder | UseElementRenamed | VisionPrescription.lensSpecification.cylinder |
| VisionPrescription.dispense.axis | UseElementRenamed | VisionPrescription.lensSpecification.axis |
| VisionPrescription.dispense.prism | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.dispense.prism |
| VisionPrescription.dispense.base | UseElementRenamed | VisionPrescription.lensSpecification.prism.base |
| VisionPrescription.dispense.add | UseElementRenamed | VisionPrescription.lensSpecification.add |
| VisionPrescription.dispense.power | UseElementRenamed | VisionPrescription.lensSpecification.power |
| VisionPrescription.dispense.backCurve | UseElementRenamed | VisionPrescription.lensSpecification.backCurve |
| VisionPrescription.dispense.diameter | UseElementRenamed | VisionPrescription.lensSpecification.diameter |
| VisionPrescription.dispense.duration | UseElementRenamed | VisionPrescription.lensSpecification.duration |
| VisionPrescription.dispense.color | UseElementRenamed | VisionPrescription.lensSpecification.color |
| VisionPrescription.dispense.brand | UseElementRenamed | VisionPrescription.lensSpecification.brand |
| VisionPrescription.dispense.note | UseElementRenamed | VisionPrescription.lensSpecification.note |
