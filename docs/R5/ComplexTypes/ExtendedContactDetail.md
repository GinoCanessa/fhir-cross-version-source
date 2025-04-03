Comparison of 
Generated at Thursday, April 3, 2025 8:18:33 AM

### ExtendedContactDetail

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | ExtendedContactDetail |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ExtendedContactDetail` |
| Version | 5.0.0 |
| Description | ExtendedContactDetail Type: Specifies contact information for a specific purpose over a period of time, might be handled/monitored by a specific named person or organization. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `2223` |
| Database Snapshot Count | `9` |
| Database Differential Count | `7` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ExtendedContactDetail` | `ExtendedContactDetail` | `ExtendedContactDetail` | ExtendedContactDetail | Contact information | 0..* | ExtendedContactDetail |  |  |
| `ExtendedContactDetail.address` | `ExtendedContactDetail.address` | `address` | ExtendedContactDetail.address | Address for the contact | 0..1 | Address |  |  |
| `ExtendedContactDetail.extension` | `ExtendedContactDetail.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ExtendedContactDetail.id` | `ExtendedContactDetail.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ExtendedContactDetail.name` | `ExtendedContactDetail.name` | `name` | ExtendedContactDetail.name | Name of an individual to contact | 0..* | HumanName |  |  |
| `ExtendedContactDetail.organization` | `ExtendedContactDetail.organization` | `organization` | ExtendedContactDetail.organization | This contact detail is handled/monitored by a specific organization | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `ExtendedContactDetail.period` | `ExtendedContactDetail.period` | `period` | ExtendedContactDetail.period | Period that this contact was valid for usage | 0..1 | Period |  |  |
| `ExtendedContactDetail.purpose` | `ExtendedContactDetail.purpose` | `purpose` | ExtendedContactDetail.purpose | The type of contact | 0..1 | CodeableConcept | `Preferred` | `http://terminology.hl7.org/ValueSet/contactentity-type` |
| `ExtendedContactDetail.telecom` | `ExtendedContactDetail.telecom` | `telecom` | ExtendedContactDetail.telecom | Contact details (e.g.phone/fax/url) | 0..* | ContactPoint |  |  |
### Empty Projection

This Structure (ComplexType) resulted in no projection (no mappings to other packages).

