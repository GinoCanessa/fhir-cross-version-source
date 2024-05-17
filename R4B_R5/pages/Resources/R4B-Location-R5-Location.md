Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Location |  | Details and position information for a physical place where services are provided and resources and participants may be stored, found, contained, or accommodated. | 39 | 25 |
| Target | Location |  | Details and position information for a place where services are provided and resources and participants may be stored, found, contained, or accommodated. | 33 | 22 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 10 |
Equivalent | 4 |
RelatedTo | 25 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Location | Location | Equivalent | R4B `Location` maps as Equivalent to R5 `Location` |
| Location.address | Location.address | Equivalent | R4B `Location.address` maps as Equivalent to R5 `Location.address` |
| Location.alias | Location.alias | Equivalent | R4B `Location.alias` maps as Equivalent to R5 `Location.alias` |
| Location.availabilityExceptions | - | DoesNotExistInTarget | R4B `Location.availabilityExceptions` does not appear in the target and has no mapping for `Location`. |
| Location.contained | Location.contained | Equivalent | R4B `Location.contained` maps as Equivalent to R5 `Location.contained` |
| Location.description | Location.description | SourceIsBroaderThanTarget | R4B `Location.description` maps as SourceIsBroaderThanTarget to R5 `Location.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| Location.endpoint | Location.endpoint | Equivalent | R4B `Location.endpoint` maps as Equivalent to R5 `Location.endpoint` |
| Location.extension | Location.extension | RelatedTo | R4B `Location.extension` maps as RelatedTo to R5 `Location.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Location.hoursOfOperation | Location.hoursOfOperation | SourceIsBroaderThanTarget | R4B `Location.hoursOfOperation` maps as SourceIsBroaderThanTarget to R5 `Location.hoursOfOperation` - hoursOfOperation has change due to type change: R4B hoursOfOperation BackboneElement has no equivalent or mapped type in R5 hoursOfOperation |
| Location.hoursOfOperation.allDay | - | DoesNotExistInTarget | R4B `Location.hoursOfOperation.allDay` does not appear in the target and has no mapping for `Location`. |
| Location.hoursOfOperation.closingTime | - | DoesNotExistInTarget | R4B `Location.hoursOfOperation.closingTime` does not appear in the target and has no mapping for `Location`. |
| Location.hoursOfOperation.daysOfWeek | - | DoesNotExistInTarget | R4B `Location.hoursOfOperation.daysOfWeek` does not appear in the target and has no mapping for `Location`. |
| Location.hoursOfOperation.extension | - | DoesNotExistInTarget | R4B `Location.hoursOfOperation.extension` does not appear in the target and has no mapping for `Location`. |
| Location.hoursOfOperation.id | - | DoesNotExistInTarget | R4B `Location.hoursOfOperation.id` does not appear in the target and has no mapping for `Location`. |
| Location.hoursOfOperation.modifierExtension | - | DoesNotExistInTarget | R4B `Location.hoursOfOperation.modifierExtension` does not appear in the target and has no mapping for `Location`. |
| Location.hoursOfOperation.openingTime | - | DoesNotExistInTarget | R4B `Location.hoursOfOperation.openingTime` does not appear in the target and has no mapping for `Location`. |
| Location.id | Location.id | Equivalent | R4B `Location.id` maps as Equivalent to R5 `Location.id` |
| Location.identifier | Location.identifier | Equivalent | R4B `Location.identifier` maps as Equivalent to R5 `Location.identifier` |
| Location.implicitRules | Location.implicitRules | Equivalent | R4B `Location.implicitRules` maps as Equivalent to R5 `Location.implicitRules` |
| Location.language | Location.language | RelatedTo | R4B `Location.language` maps as RelatedTo to R5 `Location.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Location.managingOrganization | Location.managingOrganization | Equivalent | R4B `Location.managingOrganization` maps as Equivalent to R5 `Location.managingOrganization` |
| Location.meta | Location.meta | Equivalent | R4B `Location.meta` maps as Equivalent to R5 `Location.meta` |
| Location.mode | Location.mode | Equivalent | R4B `Location.mode` maps as Equivalent to R5 `Location.mode` - mode has compatible required binding for code type: http://hl7.org/fhir/ValueSet/location-mode|4.3.0 and http://hl7.org/fhir/ValueSet/location-mode|5.0.0 (Equivalent) |
| Location.modifierExtension | Location.modifierExtension | RelatedTo | R4B `Location.modifierExtension` maps as RelatedTo to R5 `Location.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Location.name | Location.name | Equivalent | R4B `Location.name` maps as Equivalent to R5 `Location.name` |
| Location.operationalStatus | Location.operationalStatus | Equivalent | R4B `Location.operationalStatus` maps as Equivalent to R5 `Location.operationalStatus` |
| Location.partOf | Location.partOf | Equivalent | R4B `Location.partOf` maps as Equivalent to R5 `Location.partOf` |
| Location.physicalType | - | DoesNotExistInTarget | R4B `Location.physicalType` does not appear in the target and has no mapping for `Location`. |
| Location.position | Location.position | Equivalent | R4B `Location.position` maps as Equivalent to R5 `Location.position` |
| Location.position.altitude | Location.position.altitude | Equivalent | R4B `Location.position.altitude` maps as Equivalent to R5 `Location.position.altitude` |
| Location.position.extension | Location.position.extension | RelatedTo | R4B `Location.position.extension` maps as RelatedTo to R5 `Location.position.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Location.position.id | Location.position.id | Equivalent | R4B `Location.position.id` maps as Equivalent to R5 `Location.position.id` |
| Location.position.latitude | Location.position.latitude | Equivalent | R4B `Location.position.latitude` maps as Equivalent to R5 `Location.position.latitude` |
| Location.position.longitude | Location.position.longitude | Equivalent | R4B `Location.position.longitude` maps as Equivalent to R5 `Location.position.longitude` |
| Location.position.modifierExtension | Location.position.modifierExtension | RelatedTo | R4B `Location.position.modifierExtension` maps as RelatedTo to R5 `Location.position.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Location.status | Location.status | Equivalent | R4B `Location.status` maps as Equivalent to R5 `Location.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/location-status|4.3.0 and http://hl7.org/fhir/ValueSet/location-status|5.0.0 (Equivalent) |
| Location.telecom | - | DoesNotExistInTarget | R4B `Location.telecom` does not appear in the target and has no mapping for `Location`. |
| Location.text | Location.text | Equivalent | R4B `Location.text` maps as Equivalent to R5 `Location.text` |
| Location.type | Location.type | Equivalent | R4B `Location.type` maps as Equivalent to R5 `Location.type` |

