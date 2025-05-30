### Lookup for FHIR R3 Encounter for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Encounter.id | UseElementSameName | Encounter.id |
| Encounter.meta | UseElementSameName | Encounter.meta |
| Encounter.implicitRules | UseElementSameName | Encounter.implicitRules |
| Encounter.language | UseElementSameName | Encounter.language |
| Encounter.text | UseElementSameName | Encounter.text |
| Encounter.contained | UseElementSameName | Encounter.contained |
| Encounter.extension | UseElementSameName | Encounter.extension |
| Encounter.modifierExtension | UseElementSameName | Encounter.modifierExtension |
| Encounter.identifier | UseElementSameName | Encounter.identifier |
| Encounter.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.status |
| Encounter.statusHistory | UseElementSameName | Encounter.statusHistory |
| Encounter.statusHistory.id | UseElementSameName | Encounter.statusHistory.id |
| Encounter.statusHistory.extension | UseElementSameName | Encounter.statusHistory.extension |
| Encounter.statusHistory.modifierExtension | UseElementSameName | Encounter.statusHistory.modifierExtension |
| Encounter.statusHistory.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.statusHistory.status |
| Encounter.statusHistory.period | UseElementSameName | Encounter.statusHistory.period |
| Encounter.class | UseElementSameName | Encounter.class |
| Encounter.classHistory | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.classHistory |
| Encounter.classHistory.id | UseExtensionFromAncestor | - |
| Encounter.classHistory.extension | UseExtensionFromAncestor | - |
| Encounter.classHistory.modifierExtension | UseExtensionFromAncestor | - |
| Encounter.classHistory.class | UseExtensionFromAncestor | - |
| Encounter.classHistory.period | UseExtensionFromAncestor | - |
| Encounter.type | UseElementSameName | Encounter.type |
| Encounter.priority | UseElementSameName | Encounter.priority |
| Encounter.subject | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.subject |
| Encounter.episodeOfCare | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.episodeOfCare |
| Encounter.incomingReferral | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.incomingReferral |
| Encounter.participant | UseElementSameName | Encounter.participant |
| Encounter.participant.id | UseElementSameName | Encounter.participant.id |
| Encounter.participant.extension | UseElementSameName | Encounter.participant.extension |
| Encounter.participant.modifierExtension | UseElementSameName | Encounter.participant.modifierExtension |
| Encounter.participant.type | UseElementSameName | Encounter.participant.type |
| Encounter.participant.period | UseElementSameName | Encounter.participant.period |
| Encounter.participant.individual | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.participant.individual |
| Encounter.appointment | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.appointment |
| Encounter.period | UseElementSameName | Encounter.period |
| Encounter.length | UseElementSameName | Encounter.length |
| Encounter.reason | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.reason |
| Encounter.diagnosis | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.diagnosis |
| Encounter.diagnosis.id | UseExtensionFromAncestor | - |
| Encounter.diagnosis.extension | UseExtensionFromAncestor | - |
| Encounter.diagnosis.modifierExtension | UseExtensionFromAncestor | - |
| Encounter.diagnosis.condition | UseExtensionFromAncestor | - |
| Encounter.diagnosis.role | UseExtensionFromAncestor | - |
| Encounter.diagnosis.rank | UseExtensionFromAncestor | - |
| Encounter.account | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.account |
| Encounter.hospitalization | UseElementSameName | Encounter.hospitalization |
| Encounter.hospitalization.id | UseElementSameName | Encounter.hospitalization.id |
| Encounter.hospitalization.extension | UseElementSameName | Encounter.hospitalization.extension |
| Encounter.hospitalization.modifierExtension | UseElementSameName | Encounter.hospitalization.modifierExtension |
| Encounter.hospitalization.preAdmissionIdentifier | UseElementSameName | Encounter.hospitalization.preAdmissionIdentifier |
| Encounter.hospitalization.origin | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.hospitalization.origin |
| Encounter.hospitalization.admitSource | UseElementSameName | Encounter.hospitalization.admitSource |
| Encounter.hospitalization.reAdmission | UseElementSameName | Encounter.hospitalization.reAdmission |
| Encounter.hospitalization.dietPreference | UseElementSameName | Encounter.hospitalization.dietPreference |
| Encounter.hospitalization.specialCourtesy | UseElementSameName | Encounter.hospitalization.specialCourtesy |
| Encounter.hospitalization.specialArrangement | UseElementSameName | Encounter.hospitalization.specialArrangement |
| Encounter.hospitalization.destination | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.hospitalization.destination |
| Encounter.hospitalization.dischargeDisposition | UseElementSameName | Encounter.hospitalization.dischargeDisposition |
| Encounter.location | UseElementSameName | Encounter.location |
| Encounter.location.id | UseElementSameName | Encounter.location.id |
| Encounter.location.extension | UseElementSameName | Encounter.location.extension |
| Encounter.location.modifierExtension | UseElementSameName | Encounter.location.modifierExtension |
| Encounter.location.location | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.location.location |
| Encounter.location.status | UseElementSameName | Encounter.location.status |
| Encounter.location.period | UseElementSameName | Encounter.location.period |
| Encounter.serviceProvider | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.serviceProvider |
| Encounter.partOf | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Encounter.partOf |
