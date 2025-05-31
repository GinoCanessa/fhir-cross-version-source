### Lookup for FHIR R3 VisionPrescription for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| VisionPrescription.id | UseElementSameName | VisionPrescription.id |
| VisionPrescription.meta | UseElementSameName | VisionPrescription.meta |
| VisionPrescription.implicitRules | UseElementSameName | VisionPrescription.implicitRules |
| VisionPrescription.language | UseElementSameName | VisionPrescription.language |
| VisionPrescription.text | UseElementSameName | VisionPrescription.text |
| VisionPrescription.contained | UseElementSameName | VisionPrescription.contained |
| VisionPrescription.extension | UseElementSameName | VisionPrescription.extension |
| VisionPrescription.modifierExtension | UseElementSameName | VisionPrescription.modifierExtension |
| VisionPrescription.identifier | UseElementSameName | VisionPrescription.identifier |
| VisionPrescription.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.status |
| VisionPrescription.patient | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.patient |
| VisionPrescription.encounter | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.encounter |
| VisionPrescription.dateWritten | UseElementSameName | VisionPrescription.dateWritten |
| VisionPrescription.prescriber | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.prescriber |
| VisionPrescription.reason[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.reason |
| VisionPrescription.dispense | UseElementRenamed | VisionPrescription.dispense |
| VisionPrescription.dispense.id | UseElementRenamed | VisionPrescription.dispense.id |
| VisionPrescription.dispense.extension | UseElementRenamed | VisionPrescription.dispense.extension |
| VisionPrescription.dispense.modifierExtension | UseElementRenamed | VisionPrescription.dispense.modifierExtension |
| VisionPrescription.dispense.product | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.dispense.product |
| VisionPrescription.dispense.eye | UseElementRenamed | VisionPrescription.dispense.eye |
| VisionPrescription.dispense.sphere | UseElementRenamed | VisionPrescription.dispense.sphere |
| VisionPrescription.dispense.cylinder | UseElementRenamed | VisionPrescription.dispense.cylinder |
| VisionPrescription.dispense.axis | UseElementRenamed | VisionPrescription.dispense.axis |
| VisionPrescription.dispense.prism | UseElementRenamed | VisionPrescription.dispense.prism |
| VisionPrescription.dispense.base | UseElementRenamed | VisionPrescription.dispense.base |
| VisionPrescription.dispense.add | UseElementRenamed | VisionPrescription.dispense.add |
| VisionPrescription.dispense.power | UseElementRenamed | VisionPrescription.dispense.power |
| VisionPrescription.dispense.backCurve | UseElementRenamed | VisionPrescription.dispense.backCurve |
| VisionPrescription.dispense.diameter | UseElementRenamed | VisionPrescription.dispense.diameter |
| VisionPrescription.dispense.duration | UseElementRenamed | VisionPrescription.dispense.duration |
| VisionPrescription.dispense.color | UseElementRenamed | VisionPrescription.dispense.color |
| VisionPrescription.dispense.brand | UseElementRenamed | VisionPrescription.dispense.brand |
| VisionPrescription.dispense.note | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-VisionPrescription.dispense.note |
