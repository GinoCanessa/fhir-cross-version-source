Comparison of 
Generated at Monday, April 14, 2025 6:17:48 PM

### FormularyItem

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | FormularyItem |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/FormularyItem` |
| Version | 5.0.0 |
| Description | This resource describes a product or service that is available through a program and includes the conditions and constraints of availability.  All of the information in this resource is specific to the inclusion of the item in the formulary and is not inherent to the item itself. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2312` |
| Database Snapshot Count | `12` |
| Database Differential Count | `4` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `FormularyItem` | `FormularyItem` | `FormularyItem` | FormularyItem | Definition of a FormularyItem | 0..* | FormularyItem |  |  |
| `FormularyItem.code` | `FormularyItem.code` | `code` | FormularyItem.code | Codes that identify this formulary item | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medication-codes` |
| `FormularyItem.contained` | `FormularyItem.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `FormularyItem.extension` | `FormularyItem.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `FormularyItem.id` | `FormularyItem.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `FormularyItem.identifier` | `FormularyItem.identifier` | `identifier` | FormularyItem.identifier | Business identifier for this formulary item | 0..* | Identifier |  |  |
| `FormularyItem.implicitRules` | `FormularyItem.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `FormularyItem.language` | `FormularyItem.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `FormularyItem.meta` | `FormularyItem.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `FormularyItem.modifierExtension` | `FormularyItem.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `FormularyItem.status` | `FormularyItem.status` | `status` | FormularyItem.status | active \| entered-in-error \| inactive | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/formularyitem-status|5.0.0` |
| `FormularyItem.text` | `FormularyItem.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

