### Lookup for FHIR R5 CoverageEligibilityResponse for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| CoverageEligibilityResponse.id | UseElementRenamed | EligibilityResponse.id |
| CoverageEligibilityResponse.meta | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.meta |
| CoverageEligibilityResponse.implicitRules | UseElementRenamed | EligibilityResponse.implicitRules |
| CoverageEligibilityResponse.language | UseElementRenamed | EligibilityResponse.language |
| CoverageEligibilityResponse.text | UseElementRenamed | EligibilityResponse.text |
| CoverageEligibilityResponse.contained | UseElementRenamed | EligibilityResponse.contained |
| CoverageEligibilityResponse.extension | UseElementRenamed | EligibilityResponse.extension |
| CoverageEligibilityResponse.modifierExtension | UseElementRenamed | EligibilityResponse.modifierExtension |
| CoverageEligibilityResponse.identifier | UseElementRenamed | EligibilityResponse.identifier |
| CoverageEligibilityResponse.status | UseElementRenamed | EligibilityResponse.status |
| CoverageEligibilityResponse.purpose | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.purpose |
| CoverageEligibilityResponse.patient | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.patient |
| CoverageEligibilityResponse.event | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.event |
| CoverageEligibilityResponse.event.id | UseExtensionFromAncestor | - |
| CoverageEligibilityResponse.event.extension | UseExtensionFromAncestor | - |
| CoverageEligibilityResponse.event.modifierExtension | UseExtensionFromAncestor | - |
| CoverageEligibilityResponse.event.type | UseExtensionFromAncestor | - |
| CoverageEligibilityResponse.event.when[x] | UseExtensionFromAncestor | - |
| CoverageEligibilityResponse.serviced[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.serviced |
| CoverageEligibilityResponse.created | UseElementRenamed | EligibilityResponse.created |
| CoverageEligibilityResponse.requestor | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.requestor |
| CoverageEligibilityResponse.request | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.request |
| CoverageEligibilityResponse.outcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.outcome |
| CoverageEligibilityResponse.disposition | UseElementRenamed | EligibilityResponse.disposition |
| CoverageEligibilityResponse.insurer | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.insurer |
| CoverageEligibilityResponse.insurance | UseElementRenamed | EligibilityResponse.insurance |
| CoverageEligibilityResponse.insurance.id | UseElementRenamed | EligibilityResponse.insurance.id |
| CoverageEligibilityResponse.insurance.extension | UseElementRenamed | EligibilityResponse.insurance.extension |
| CoverageEligibilityResponse.insurance.modifierExtension | UseElementRenamed | EligibilityResponse.insurance.modifierExtension |
| CoverageEligibilityResponse.insurance.coverage | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.insurance.coverage |
| CoverageEligibilityResponse.insurance.inforce | UseElementRenamed | EligibilityResponse.inforce |
| CoverageEligibilityResponse.insurance.benefitPeriod | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.insurance.benefitPeriod |
| CoverageEligibilityResponse.insurance.item | UseElementRenamed | EligibilityResponse.insurance.benefitBalance |
| CoverageEligibilityResponse.insurance.item.id | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.insurance.item.id |
| CoverageEligibilityResponse.insurance.item.extension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.insurance.item.extension |
| CoverageEligibilityResponse.insurance.item.modifierExtension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.insurance.item.modifierExtension |
| CoverageEligibilityResponse.insurance.item.category | UseElementRenamed | EligibilityResponse.insurance.benefitBalance.category |
| CoverageEligibilityResponse.insurance.item.productOrService | UseElementRenamed | EligibilityResponse.insurance.benefitBalance.subCategory |
| CoverageEligibilityResponse.insurance.item.modifier | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.insurance.item.modifier |
| CoverageEligibilityResponse.insurance.item.provider | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.insurance.item.provider |
| CoverageEligibilityResponse.insurance.item.excluded | UseElementRenamed | EligibilityResponse.insurance.benefitBalance.excluded |
| CoverageEligibilityResponse.insurance.item.name | UseElementRenamed | EligibilityResponse.insurance.benefitBalance.name |
| CoverageEligibilityResponse.insurance.item.description | UseElementRenamed | EligibilityResponse.insurance.benefitBalance.description |
| CoverageEligibilityResponse.insurance.item.network | UseElementRenamed | EligibilityResponse.insurance.benefitBalance.network |
| CoverageEligibilityResponse.insurance.item.unit | UseElementRenamed | EligibilityResponse.insurance.benefitBalance.unit |
| CoverageEligibilityResponse.insurance.item.term | UseElementRenamed | EligibilityResponse.insurance.benefitBalance.term |
| CoverageEligibilityResponse.insurance.item.benefit | UseElementRenamed | EligibilityResponse.insurance.benefitBalance.financial |
| CoverageEligibilityResponse.insurance.item.benefit.id | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.insurance.item.benefit.id |
| CoverageEligibilityResponse.insurance.item.benefit.extension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.insurance.item.benefit.extension |
| CoverageEligibilityResponse.insurance.item.benefit.modifierExtension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.insurance.item.benefit.modifierExtension |
| CoverageEligibilityResponse.insurance.item.benefit.type | UseElementRenamed | EligibilityResponse.insurance.benefitBalance.financial.type |
| CoverageEligibilityResponse.insurance.item.benefit.allowed[x] | UseElementRenamed | EligibilityResponse.insurance.benefitBalance.financial.allowed[x] |
| CoverageEligibilityResponse.insurance.item.benefit.used[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.insurance.item.benefit.used |
| CoverageEligibilityResponse.insurance.item.authorizationRequired | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.insurance.item.authorizationRequired |
| CoverageEligibilityResponse.insurance.item.authorizationSupporting | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.insurance.item.authorizationSupporting |
| CoverageEligibilityResponse.insurance.item.authorizationUrl | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.insurance.item.authorizationUrl |
| CoverageEligibilityResponse.preAuthRef | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.preAuthRef |
| CoverageEligibilityResponse.form | UseElementRenamed | EligibilityResponse.form |
| CoverageEligibilityResponse.error | UseElementRenamed | EligibilityResponse.error |
| CoverageEligibilityResponse.error.id | UseElementRenamed | EligibilityResponse.error.id |
| CoverageEligibilityResponse.error.extension | UseElementRenamed | EligibilityResponse.error.extension |
| CoverageEligibilityResponse.error.modifierExtension | UseElementRenamed | EligibilityResponse.error.modifierExtension |
| CoverageEligibilityResponse.error.code | UseElementRenamed | EligibilityResponse.error.code |
| CoverageEligibilityResponse.error.expression | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-CoverageEligibilityResponse.error.expression |
