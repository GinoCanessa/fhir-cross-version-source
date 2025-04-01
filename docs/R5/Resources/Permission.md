Comparison of 
Generated at Tuesday, April 1, 2025 1:39:40 PM

### Permission

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Permission |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Permission` |
| Version | 5.0.0 |
| Description | Permission resource holds access rules for a given data and context. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2362` |
| Database Snapshot Count | `46` |
| Database Differential Count | `23` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Permission` | `Permission` | `Permission` | Permission | Access Rules | 0..* | Permission |  |  |
| `Permission.asserter` | `Permission.asserter` | `asserter` | Permission.asserter | The person or entity that asserts the permission | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Permission.combining` | `Permission.combining` | `combining` | Permission.combining | deny-overrides \| permit-overrides \| ordered-deny-overrides \| ordered-permit-overrides \| deny-unless-permit \| permit-unless-deny | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/permission-rule-combining|5.0.0` |
| `Permission.contained` | `Permission.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Permission.date` | `Permission.date` | `date` | Permission.date | The date that permission was asserted | 0..* | dateTime |  |  |
| `Permission.extension` | `Permission.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Permission.id` | `Permission.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Permission.implicitRules` | `Permission.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Permission.justification` | `Permission.justification` | `justification` | Permission.justification | The asserted justification for using the data | 0..1 | BackboneElement |  |  |
| `Permission.justification.basis` | `Permission.justification.basis` | `basis` | Permission.justification.basis | The regulatory grounds upon which this Permission builds | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/consent-policy` |
| `Permission.justification.evidence` | `Permission.justification.evidence` | `evidence` | Permission.justification.evidence | Justifing rational | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Permission.justification.extension` | `Permission.justification.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Permission.justification.id` | `Permission.justification.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Permission.justification.modifierExtension` | `Permission.justification.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Permission.language` | `Permission.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Permission.meta` | `Permission.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Permission.modifierExtension` | `Permission.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Permission.rule` | `Permission.rule` | `rule` | Permission.rule | Constraints to the Permission | 0..* | BackboneElement |  |  |
| `Permission.rule.activity` | `Permission.rule.activity` | `activity` | Permission.rule.activity | A description or definition of which activities are allowed to be done on the data | 0..* | BackboneElement |  |  |
| `Permission.rule.activity.action` | `Permission.rule.activity.action` | `action` | Permission.rule.activity.action | Actions controlled by this rule | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/consent-action` |
| `Permission.rule.activity.actor` | `Permission.rule.activity.actor` | `actor` | Permission.rule.activity.actor | Authorized actor(s) | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Permission.rule.activity.extension` | `Permission.rule.activity.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Permission.rule.activity.id` | `Permission.rule.activity.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Permission.rule.activity.modifierExtension` | `Permission.rule.activity.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Permission.rule.activity.purpose` | `Permission.rule.activity.purpose` | `purpose` | Permission.rule.activity.purpose | The purpose for which the permission is given | 0..* | CodeableConcept | `Preferred` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` |
| `Permission.rule.data` | `Permission.rule.data` | `data` | Permission.rule.data | The selection criteria to identify data that is within scope of this provision | 0..* | BackboneElement |  |  |
| `Permission.rule.data.expression` | `Permission.rule.data.expression` | `expression` | Permission.rule.data.expression | Expression identifying the data | 0..1 | Expression |  |  |
| `Permission.rule.data.extension` | `Permission.rule.data.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Permission.rule.data.id` | `Permission.rule.data.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Permission.rule.data.modifierExtension` | `Permission.rule.data.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Permission.rule.data.period` | `Permission.rule.data.period` | `period` | Permission.rule.data.period | Timeframe encompasing data create/update | 0..* | Period |  |  |
| `Permission.rule.data.resource` | `Permission.rule.data.resource` | `resource` | Permission.rule.data.resource | Explicit FHIR Resource references | 0..* | BackboneElement |  |  |
| `Permission.rule.data.resource.extension` | `Permission.rule.data.resource.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Permission.rule.data.resource.id` | `Permission.rule.data.resource.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Permission.rule.data.resource.meaning` | `Permission.rule.data.resource.meaning` | `meaning` | Permission.rule.data.resource.meaning | instance \| related \| dependents \| authoredby | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/consent-data-meaning|5.0.0` |
| `Permission.rule.data.resource.modifierExtension` | `Permission.rule.data.resource.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Permission.rule.data.resource.reference` | `Permission.rule.data.resource.reference` | `reference` | Permission.rule.data.resource.reference | The actual data reference | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Permission.rule.data.security` | `Permission.rule.data.security` | `security` | Permission.rule.data.security | Security tag code on .meta.security | 0..* | Coding |  |  |
| `Permission.rule.extension` | `Permission.rule.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Permission.rule.id` | `Permission.rule.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Permission.rule.limit` | `Permission.rule.limit` | `limit` | Permission.rule.limit | What limits apply to the use of the data | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/security-label-event-examples` |
| `Permission.rule.modifierExtension` | `Permission.rule.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Permission.rule.type` | `Permission.rule.type` | `type` | Permission.rule.type | deny \| permit | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/consent-provision-type|5.0.0` |
| `Permission.status` | `Permission.status` | `status` | Permission.status | active \| entered-in-error \| draft \| rejected | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/permission-status|5.0.0` |
| `Permission.text` | `Permission.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Permission.validity` | `Permission.validity` | `validity` | Permission.validity | The period in which the permission is active | 0..1 | Period |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

