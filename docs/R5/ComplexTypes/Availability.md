Comparison of 
Generated at Monday, April 14, 2025 6:17:44 PM

### Availability

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Availability |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Availability` |
| Version | 5.0.0 |
| Description | Availability Type: Availability data for an {item}. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `2204` |
| Database Snapshot Count | `15` |
| Database Differential Count | `9` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Availability` | `Availability` | `Availability` | Availability | Availability data for an {item} | 0..* | Availability |  |  |
| `Availability.availableTime` | `Availability.availableTime` | `availableTime` | Availability.availableTime | Times the {item} is available | 0..* | Element |  |  |
| `Availability.availableTime.allDay` | `Availability.availableTime.allDay` | `allDay` | Availability.availableTime.allDay | Always available? i.e. 24 hour service | 0..1 | boolean |  |  |
| `Availability.availableTime.availableEndTime` | `Availability.availableTime.availableEndTime` | `availableEndTime` | Availability.availableTime.availableEndTime | Closing time of day (ignored if allDay = true) | 0..1 | time |  |  |
| `Availability.availableTime.availableStartTime` | `Availability.availableTime.availableStartTime` | `availableStartTime` | Availability.availableTime.availableStartTime | Opening time of day (ignored if allDay = true) | 0..1 | time |  |  |
| `Availability.availableTime.daysOfWeek` | `Availability.availableTime.daysOfWeek` | `daysOfWeek` | Availability.availableTime.daysOfWeek | mon \| tue \| wed \| thu \| fri \| sat \| sun | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/days-of-week|5.0.0` |
| `Availability.availableTime.extension` | `Availability.availableTime.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Availability.availableTime.id` | `Availability.availableTime.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Availability.extension` | `Availability.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Availability.id` | `Availability.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Availability.notAvailableTime` | `Availability.notAvailableTime` | `notAvailableTime` | Availability.notAvailableTime | Not available during this time due to provided reason | 0..* | Element |  |  |
| `Availability.notAvailableTime.description` | `Availability.notAvailableTime.description` | `description` | Availability.notAvailableTime.description | Reason presented to the user explaining why time not available | 0..1 | string |  |  |
| `Availability.notAvailableTime.during` | `Availability.notAvailableTime.during` | `during` | Availability.notAvailableTime.during | Service not available during this period | 0..1 | Period |  |  |
| `Availability.notAvailableTime.extension` | `Availability.notAvailableTime.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Availability.notAvailableTime.id` | `Availability.notAvailableTime.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
### Empty Projection

This Structure (ComplexType) resulted in no projection (no mappings to other packages).

