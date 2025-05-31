### Lookup for FHIR R3 EligibilityRequest for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| EligibilityRequest.id | UseElementRenamed | CoverageEligibilityRequest.id |
| EligibilityRequest.meta | UseElementRenamed | CoverageEligibilityRequest.meta |
| EligibilityRequest.implicitRules | UseElementRenamed | CoverageEligibilityRequest.implicitRules |
| EligibilityRequest.language | UseElementRenamed | CoverageEligibilityRequest.language |
| EligibilityRequest.text | UseElementRenamed | CoverageEligibilityRequest.text |
| EligibilityRequest.contained | UseElementRenamed | CoverageEligibilityRequest.contained |
| EligibilityRequest.extension | UseElementRenamed | CoverageEligibilityRequest.extension |
| EligibilityRequest.modifierExtension | UseElementRenamed | CoverageEligibilityRequest.modifierExtension |
| EligibilityRequest.identifier | UseElementRenamed | CoverageEligibilityRequest.identifier |
| EligibilityRequest.status | UseElementRenamed | CoverageEligibilityRequest.status |
| EligibilityRequest.priority | UseElementRenamed | CoverageEligibilityRequest.priority |
| EligibilityRequest.patient | UseElementRenamed | CoverageEligibilityRequest.patient |
| EligibilityRequest.serviced[x] | UseElementRenamed | CoverageEligibilityRequest.serviced[x] |
| EligibilityRequest.created | UseElementRenamed | CoverageEligibilityRequest.created |
| EligibilityRequest.enterer | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-EligibilityRequest.enterer |
| EligibilityRequest.provider | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-EligibilityRequest.provider |
| EligibilityRequest.organization | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-EligibilityRequest.organization |
| EligibilityRequest.insurer | UseElementRenamed | CoverageEligibilityRequest.insurer |
| EligibilityRequest.facility | UseElementRenamed | CoverageEligibilityRequest.facility |
| EligibilityRequest.coverage | UseElementRenamed | CoverageEligibilityRequest.insurance.coverage |
| EligibilityRequest.businessArrangement | UseElementRenamed | CoverageEligibilityRequest.insurance.businessArrangement |
| EligibilityRequest.benefitCategory | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-EligibilityRequest.benefitCategory |
| EligibilityRequest.benefitSubCategory | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-EligibilityRequest.benefitSubCategory |
