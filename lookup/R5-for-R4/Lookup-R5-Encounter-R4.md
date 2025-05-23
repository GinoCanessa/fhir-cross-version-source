### Lookup for FHIR R5 Encounter for use in FHIR R4

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
| Encounter.status | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.status |
| Encounter.class | UseElementSameName | Encounter |
| Encounter.priority | UseElementSameName | Encounter.priority |
| Encounter.type | UseElementSameName | Encounter.type |
| Encounter.serviceType | UseElementSameName | Encounter.serviceType |
| Encounter.subject | UseElementSameName | Encounter.subject |
| Encounter.subjectStatus | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.subjectStatus |
| Encounter.episodeOfCare | UseElementSameName | Encounter.episodeOfCare |
| Encounter.basedOn | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.basedOn |
| Encounter.careTeam | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.careTeam |
| Encounter.partOf | UseElementSameName | Encounter.partOf |
| Encounter.serviceProvider | UseElementSameName | Encounter.serviceProvider |
| Encounter.participant | UseElementSameName | Encounter.participant |
| Encounter.participant.id | UseElementSameName | Encounter.participant.id |
| Encounter.participant.extension | UseElementSameName | Encounter.participant.extension |
| Encounter.participant.modifierExtension | UseElementSameName | Encounter.participant.modifierExtension |
| Encounter.participant.type | UseElementSameName | Encounter.participant.type |
| Encounter.participant.period | UseElementSameName | Encounter.participant.period |
| Encounter.participant.actor | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.participant.actor |
| Encounter.appointment | UseElementSameName | Encounter.appointment |
| Encounter.virtualService | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.virtualService |
| Encounter.actualPeriod | UseElementSameName | Encounter.period |
| Encounter.plannedStartDate | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.plannedStartDate |
| Encounter.plannedEndDate | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.plannedEndDate |
| Encounter.length | UseElementSameName | Encounter.length |
| Encounter.reason | UseElementSameName | Encounter.reasonCode |
| Encounter.reason.id | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.reason.id |
| Encounter.reason.extension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.reason.extension |
| Encounter.reason.modifierExtension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.reason.modifierExtension |
| Encounter.reason.use | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.reason.use |
| Encounter.reason.value | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.reason.value |
| Encounter.diagnosis | UseElementSameName | Encounter.diagnosis |
| Encounter.diagnosis.id | UseElementSameName | Encounter.diagnosis.id |
| Encounter.diagnosis.extension | UseElementSameName | Encounter.diagnosis.extension |
| Encounter.diagnosis.modifierExtension | UseElementSameName | Encounter.diagnosis.modifierExtension |
| Encounter.diagnosis.condition | UseElementSameName | Encounter.diagnosis.condition |
| Encounter.diagnosis.use | UseElementSameName | Encounter.diagnosis.use |
| Encounter.account | UseElementSameName | Encounter.account |
| Encounter.dietPreference | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.dietPreference |
| Encounter.specialArrangement | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.specialArrangement |
| Encounter.specialCourtesy | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.specialCourtesy |
| Encounter.admission | UseElementSameName | Encounter.hospitalization |
| Encounter.admission.id | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.admission.id |
| Encounter.admission.extension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.admission.extension |
| Encounter.admission.modifierExtension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Encounter.admission.modifierExtension |
| Encounter.admission.preAdmissionIdentifier | UseElementSameName | Encounter.hospitalization.preAdmissionIdentifier |
| Encounter.admission.origin | UseElementSameName | Encounter.hospitalization.origin |
| Encounter.admission.admitSource | UseElementSameName | Encounter.hospitalization.admitSource |
| Encounter.admission.reAdmission | UseElementSameName | Encounter.hospitalization.reAdmission |
| Encounter.admission.destination | UseElementSameName | Encounter.hospitalization.destination |
| Encounter.admission.dischargeDisposition | UseElementSameName | Encounter.hospitalization.dischargeDisposition |
| Encounter.location | UseElementSameName | Encounter.location |
| Encounter.location.id | UseElementSameName | Encounter.location.id |
| Encounter.location.extension | UseElementSameName | Encounter.location.extension |
| Encounter.location.modifierExtension | UseElementSameName | Encounter.location.modifierExtension |
| Encounter.location.location | UseElementSameName | Encounter.location.location |
| Encounter.location.status | UseElementSameName | Encounter.location.status |
| Encounter.location.form | UseElementSameName | Encounter.location.physicalType |
| Encounter.location.period | UseElementSameName | Encounter.location.period |
