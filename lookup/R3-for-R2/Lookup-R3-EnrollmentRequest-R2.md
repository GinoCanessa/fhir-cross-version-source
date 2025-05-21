### Lookup for FHIR R3 EnrollmentRequest for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| EnrollmentRequest.id | UseElementSameName | EnrollmentRequest.id |
| EnrollmentRequest.meta | UseElementSameName | EnrollmentRequest.meta |
| EnrollmentRequest.implicitRules | UseElementSameName | EnrollmentRequest.implicitRules |
| EnrollmentRequest.language | UseElementSameName | EnrollmentRequest.language |
| EnrollmentRequest.text | UseElementSameName | EnrollmentRequest.text |
| EnrollmentRequest.contained | UseElementSameName | EnrollmentRequest.contained |
| EnrollmentRequest.extension | UseElementSameName | EnrollmentRequest.extension |
| EnrollmentRequest.modifierExtension | UseElementSameName | EnrollmentRequest.modifierExtension |
| EnrollmentRequest.identifier | UseElementSameName | EnrollmentRequest.identifier |
| EnrollmentRequest.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-EnrollmentRequest.status |
| EnrollmentRequest.created | UseElementSameName | EnrollmentRequest.created |
| EnrollmentRequest.insurer | UseElementSameName | EnrollmentRequest.target |
| EnrollmentRequest.provider | UseElementSameName | EnrollmentRequest.provider |
| EnrollmentRequest.organization | UseElementRenamed | EnrollmentRequest.organization |
| EnrollmentRequest.subject | UseElementRenamed | EnrollmentRequest.subject |
| EnrollmentRequest.coverage | UseElementSameName | EnrollmentRequest.coverage |
