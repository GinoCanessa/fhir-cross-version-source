Comparison of 
Generated at Tuesday, April 1, 2025 1:39:36 PM

### VirtualServiceDetail

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | VirtualServiceDetail |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/VirtualServiceDetail` |
| Version | 5.0.0 |
| Description | VirtualServiceDetail Type: Virtual Service Contact Details. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `2247` |
| Database Snapshot Count | `8` |
| Database Differential Count | `6` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `VirtualServiceDetail` | `VirtualServiceDetail` | `VirtualServiceDetail` | VirtualServiceDetail | Virtual Service Contact Details | 0..* | VirtualServiceDetail |  |  |
| `VirtualServiceDetail.additionalInfo` | `VirtualServiceDetail.additionalInfo` | `additionalInfo` | VirtualServiceDetail.additionalInfo | Address to see alternative connection details | 0..* | url |  |  |
| `VirtualServiceDetail.address[x]` | `VirtualServiceDetail.address[x]` | `address[x]` | VirtualServiceDetail.address[x] | Contact address/number | 0..1 | ContactPoint, ExtendedContactDetail, string, url |  |  |
| `VirtualServiceDetail.channelType` | `VirtualServiceDetail.channelType` | `channelType` | VirtualServiceDetail.channelType | Channel Type | 0..1 | Coding | `Example` | `http://hl7.org/fhir/ValueSet/virtual-service-type` |
| `VirtualServiceDetail.extension` | `VirtualServiceDetail.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `VirtualServiceDetail.id` | `VirtualServiceDetail.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `VirtualServiceDetail.maxParticipants` | `VirtualServiceDetail.maxParticipants` | `maxParticipants` | VirtualServiceDetail.maxParticipants | Maximum number of participants supported by the virtual service | 0..1 | positiveInt |  |  |
| `VirtualServiceDetail.sessionKey` | `VirtualServiceDetail.sessionKey` | `sessionKey` | VirtualServiceDetail.sessionKey | Session Key required by the virtual service | 0..1 | string |  |  |
### Empty Projection

This Structure (ComplexType) resulted in no projection (no mappings to other packages).

