Comparison of 
Generated at Thursday, April 3, 2025 8:18:19 AM

### MedicinalProductAuthorization

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | MedicinalProductAuthorization |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MedicinalProductAuthorization` |
| Version | 4.0.1 |
| Description | The regulatory authorization of a medicinal product. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1113` |
| Database Snapshot Count | `40` |
| Database Differential Count | `26` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MedicinalProductAuthorization` | `MedicinalProductAuthorization` | `MedicinalProductAuthorization` | MedicinalProductAuthorization | The regulatory authorization of a medicinal product | 0..* | MedicinalProductAuthorization |  |  |
| `MedicinalProductAuthorization.contained` | `MedicinalProductAuthorization.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MedicinalProductAuthorization.country` | `MedicinalProductAuthorization.country` | `country` | MedicinalProductAuthorization.country | The country in which the marketing authorization has been granted | 0..* | CodeableConcept |  |  |
| `MedicinalProductAuthorization.dataExclusivityPeriod` | `MedicinalProductAuthorization.dataExclusivityPeriod` | `dataExclusivityPeriod` | MedicinalProductAuthorization.dataExclusivityPeriod | A period of time after authorization before generic product applicatiosn can be submitted | 0..1 | Period |  |  |
| `MedicinalProductAuthorization.dateOfFirstAuthorization` | `MedicinalProductAuthorization.dateOfFirstAuthorization` | `dateOfFirstAuthorization` | MedicinalProductAuthorization.dateOfFirstAuthorization | The date when the first authorization was granted by a Medicines Regulatory Agency | 0..1 | dateTime |  |  |
| `MedicinalProductAuthorization.extension` | `MedicinalProductAuthorization.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductAuthorization.holder` | `MedicinalProductAuthorization.holder` | `holder` | MedicinalProductAuthorization.holder | Marketing Authorization Holder | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `MedicinalProductAuthorization.id` | `MedicinalProductAuthorization.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MedicinalProductAuthorization.identifier` | `MedicinalProductAuthorization.identifier` | `identifier` | MedicinalProductAuthorization.identifier | Business identifier for the marketing authorization, as assigned by a regulator | 0..* | Identifier |  |  |
| `MedicinalProductAuthorization.implicitRules` | `MedicinalProductAuthorization.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MedicinalProductAuthorization.internationalBirthDate` | `MedicinalProductAuthorization.internationalBirthDate` | `internationalBirthDate` | MedicinalProductAuthorization.internationalBirthDate | Date of first marketing authorization for a company's new medicinal product in any country in the World | 0..1 | dateTime |  |  |
| `MedicinalProductAuthorization.jurisdiction` | `MedicinalProductAuthorization.jurisdiction` | `jurisdiction` | MedicinalProductAuthorization.jurisdiction | Jurisdiction within a country | 0..* | CodeableConcept |  |  |
| `MedicinalProductAuthorization.jurisdictionalAuthorization` | `MedicinalProductAuthorization.jurisdictionalAuthorization` | `jurisdictionalAuthorization` | MedicinalProductAuthorization.jurisdictionalAuthorization | Authorization in areas within a country | 0..* | BackboneElement |  |  |
| `MedicinalProductAuthorization.jurisdictionalAuthorization.country` | `MedicinalProductAuthorization.jurisdictionalAuthorization.country` | `country` | MedicinalProductAuthorization.jurisdictionalAuthorization.country | Country of authorization | 0..1 | CodeableConcept |  |  |
| `MedicinalProductAuthorization.jurisdictionalAuthorization.extension` | `MedicinalProductAuthorization.jurisdictionalAuthorization.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductAuthorization.jurisdictionalAuthorization.id` | `MedicinalProductAuthorization.jurisdictionalAuthorization.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductAuthorization.jurisdictionalAuthorization.identifier` | `MedicinalProductAuthorization.jurisdictionalAuthorization.identifier` | `identifier` | MedicinalProductAuthorization.jurisdictionalAuthorization.identifier | The assigned number for the marketing authorization | 0..* | Identifier |  |  |
| `MedicinalProductAuthorization.jurisdictionalAuthorization.jurisdiction` | `MedicinalProductAuthorization.jurisdictionalAuthorization.jurisdiction` | `jurisdiction` | MedicinalProductAuthorization.jurisdictionalAuthorization.jurisdiction | Jurisdiction within a country | 0..* | CodeableConcept |  |  |
| `MedicinalProductAuthorization.jurisdictionalAuthorization.legalStatusOfSupply` | `MedicinalProductAuthorization.jurisdictionalAuthorization.legalStatusOfSupply` | `legalStatusOfSupply` | MedicinalProductAuthorization.jurisdictionalAuthorization.legalStatusOfSupply | The legal status of supply in a jurisdiction or region | 0..1 | CodeableConcept |  |  |
| `MedicinalProductAuthorization.jurisdictionalAuthorization.modifierExtension` | `MedicinalProductAuthorization.jurisdictionalAuthorization.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductAuthorization.jurisdictionalAuthorization.validityPeriod` | `MedicinalProductAuthorization.jurisdictionalAuthorization.validityPeriod` | `validityPeriod` | MedicinalProductAuthorization.jurisdictionalAuthorization.validityPeriod | The start and expected end date of the authorization | 0..1 | Period |  |  |
| `MedicinalProductAuthorization.language` | `MedicinalProductAuthorization.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `MedicinalProductAuthorization.legalBasis` | `MedicinalProductAuthorization.legalBasis` | `legalBasis` | MedicinalProductAuthorization.legalBasis | The legal framework against which this authorization is granted | 0..1 | CodeableConcept |  |  |
| `MedicinalProductAuthorization.meta` | `MedicinalProductAuthorization.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MedicinalProductAuthorization.modifierExtension` | `MedicinalProductAuthorization.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicinalProductAuthorization.procedure` | `MedicinalProductAuthorization.procedure` | `procedure` | MedicinalProductAuthorization.procedure | The regulatory procedure for granting or amending a marketing authorization | 0..1 | BackboneElement |  |  |
| `MedicinalProductAuthorization.procedure.application` | `MedicinalProductAuthorization.procedure.application` | `application` | MedicinalProductAuthorization.procedure.application | Applcations submitted to obtain a marketing authorization | 0..* | MedicinalProductAuthorization.procedure |  |  |
| `MedicinalProductAuthorization.procedure.date[x]` | `MedicinalProductAuthorization.procedure.date[x]` | `date[x]` | MedicinalProductAuthorization.procedure.date[x] | Date of procedure | 0..1 | dateTime, Period |  |  |
| `MedicinalProductAuthorization.procedure.extension` | `MedicinalProductAuthorization.procedure.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductAuthorization.procedure.id` | `MedicinalProductAuthorization.procedure.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductAuthorization.procedure.identifier` | `MedicinalProductAuthorization.procedure.identifier` | `identifier` | MedicinalProductAuthorization.procedure.identifier | Identifier for this procedure | 0..1 | Identifier |  |  |
| `MedicinalProductAuthorization.procedure.modifierExtension` | `MedicinalProductAuthorization.procedure.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductAuthorization.procedure.type` | `MedicinalProductAuthorization.procedure.type` | `type` | MedicinalProductAuthorization.procedure.type | Type of procedure | 1..1 | CodeableConcept |  |  |
| `MedicinalProductAuthorization.regulator` | `MedicinalProductAuthorization.regulator` | `regulator` | MedicinalProductAuthorization.regulator | Medicines Regulatory Agency | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `MedicinalProductAuthorization.restoreDate` | `MedicinalProductAuthorization.restoreDate` | `restoreDate` | MedicinalProductAuthorization.restoreDate | The date when a suspended the marketing or the marketing authorization of the product is anticipated to be restored | 0..1 | dateTime |  |  |
| `MedicinalProductAuthorization.status` | `MedicinalProductAuthorization.status` | `status` | MedicinalProductAuthorization.status | The status of the marketing authorization | 0..1 | CodeableConcept |  |  |
| `MedicinalProductAuthorization.statusDate` | `MedicinalProductAuthorization.statusDate` | `statusDate` | MedicinalProductAuthorization.statusDate | The date at which the given status has become applicable | 0..1 | dateTime |  |  |
| `MedicinalProductAuthorization.subject` | `MedicinalProductAuthorization.subject` | `subject` | MedicinalProductAuthorization.subject | The medicinal product that is being authorized | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProduct), Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductPackaged) |  |  |
| `MedicinalProductAuthorization.text` | `MedicinalProductAuthorization.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `MedicinalProductAuthorization.validityPeriod` | `MedicinalProductAuthorization.validityPeriod` | `validityPeriod` | MedicinalProductAuthorization.validityPeriod | The beginning of the time period in which the marketing authorization is in the specific status shall be specified A complete date consisting of day, month and year shall be specified using the ISO 8601 date format | 0..1 | Period |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

