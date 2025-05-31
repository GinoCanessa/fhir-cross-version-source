### Lookup for FHIR R2 EnrollmentRequest for use in FHIR R3

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
| EnrollmentRequest.ruleset | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-EnrollmentRequest.ruleset |
| EnrollmentRequest.originalRuleset | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-EnrollmentRequest.originalRuleset |
| EnrollmentRequest.created | UseElementSameName | EnrollmentRequest.created |
| EnrollmentRequest.target | UseElementRenamed | EnrollmentRequest.insurer |
| EnrollmentRequest.provider | UseElementSameName | EnrollmentRequest.provider |
| EnrollmentRequest.organization | UseElementSameName | EnrollmentRequest.organization |
| EnrollmentRequest.subject | UseElementSameName | EnrollmentRequest.subject |
| EnrollmentRequest.coverage | UseElementSameName | EnrollmentRequest.coverage |
| EnrollmentRequest.relationship | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-EnrollmentRequest.relationship |
