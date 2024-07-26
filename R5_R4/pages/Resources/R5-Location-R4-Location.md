Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Location |  | Details and position information for a place where services are provided and resources and participants may be stored, found, contained, or accommodated. | 33 | 22 |
| Target | Location |  | Details and position information for a physical place where services are provided and resources and participants may be stored, found, contained, or accommodated. | 39 | 25 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 25 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Location | Location | Equivalent | R5 `Location` maps as Equivalent to R4 `Location` |
| Location.address | Location.address | Equivalent | R5 `Location.address` maps as Equivalent to R4 `Location.address` |
| Location.alias | Location.alias | Equivalent | R5 `Location.alias` maps as Equivalent to R4 `Location.alias` |
| Location.characteristic | - | DoesNotExistInTarget | R5 `Location.characteristic` does not appear in the target and has no mapping for `Location`. |
| Location.contact | - | DoesNotExistInTarget | R5 `Location.contact` does not appear in the target and has no mapping for `Location`. |
| Location.contained | Location.contained | Equivalent | R5 `Location.contained` maps as Equivalent to R4 `Location.contained` |
| Location.description | Location.description | SourceIsBroaderThanTarget | R5 `Location.description` maps as SourceIsBroaderThanTarget to R4 `Location.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4 description |
| Location.endpoint | Location.endpoint | Equivalent | R5 `Location.endpoint` maps as Equivalent to R4 `Location.endpoint` |
| Location.extension | Location.extension | SourceIsBroaderThanTarget | R5 `Location.extension` maps as SourceIsBroaderThanTarget to R4 `Location.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Location.form | - | DoesNotExistInTarget | R5 `Location.form` does not appear in the target and has no mapping for `Location`. |
| Location.hoursOfOperation | Location.hoursOfOperation | SourceIsBroaderThanTarget | R5 `Location.hoursOfOperation` maps as SourceIsBroaderThanTarget to R4 `Location.hoursOfOperation` - hoursOfOperation has change due to type change: R5 hoursOfOperation Availability has no equivalent or mapped type in R4 hoursOfOperation |
| Location.id | Location.id | Equivalent | R5 `Location.id` maps as Equivalent to R4 `Location.id` |
| Location.identifier | Location.identifier | Equivalent | R5 `Location.identifier` maps as Equivalent to R4 `Location.identifier` |
| Location.implicitRules | Location.implicitRules | Equivalent | R5 `Location.implicitRules` maps as Equivalent to R4 `Location.implicitRules` |
| Location.language | Location.language | RelatedTo | R5 `Location.language` maps as RelatedTo to R4 `Location.language` - language changed the binding strength from Required to Preferred |
| Location.managingOrganization | Location.managingOrganization | Equivalent | R5 `Location.managingOrganization` maps as Equivalent to R4 `Location.managingOrganization` |
| Location.meta | Location.meta | Equivalent | R5 `Location.meta` maps as Equivalent to R4 `Location.meta` |
| Location.mode | Location.mode | Equivalent | R5 `Location.mode` maps as Equivalent to R4 `Location.mode` - mode has compatible required binding for code type: http://hl7.org/fhir/ValueSet/location-mode|5.0.0 and http://hl7.org/fhir/ValueSet/location-mode|4.0.1 (Equivalent) |
| Location.modifierExtension | Location.modifierExtension | SourceIsBroaderThanTarget | R5 `Location.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Location.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Location.name | Location.name | Equivalent | R5 `Location.name` maps as Equivalent to R4 `Location.name` |
| Location.operationalStatus | Location.operationalStatus | Equivalent | R5 `Location.operationalStatus` maps as Equivalent to R4 `Location.operationalStatus` |
| Location.partOf | Location.partOf | Equivalent | R5 `Location.partOf` maps as Equivalent to R4 `Location.partOf` |
| Location.position | Location.position | Equivalent | R5 `Location.position` maps as Equivalent to R4 `Location.position` |
| Location.position.altitude | Location.position.altitude | Equivalent | R5 `Location.position.altitude` maps as Equivalent to R4 `Location.position.altitude` |
| Location.position.extension | Location.position.extension | SourceIsBroaderThanTarget | R5 `Location.position.extension` maps as SourceIsBroaderThanTarget to R4 `Location.position.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Location.position.id | Location.position.id | Equivalent | R5 `Location.position.id` maps as Equivalent to R4 `Location.position.id` |
| Location.position.latitude | Location.position.latitude | Equivalent | R5 `Location.position.latitude` maps as Equivalent to R4 `Location.position.latitude` |
| Location.position.longitude | Location.position.longitude | Equivalent | R5 `Location.position.longitude` maps as Equivalent to R4 `Location.position.longitude` |
| Location.position.modifierExtension | Location.position.modifierExtension | SourceIsBroaderThanTarget | R5 `Location.position.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Location.position.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Location.status | Location.status | Equivalent | R5 `Location.status` maps as Equivalent to R4 `Location.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/location-status|5.0.0 and http://hl7.org/fhir/ValueSet/location-status|4.0.1 (Equivalent) |
| Location.text | Location.text | Equivalent | R5 `Location.text` maps as Equivalent to R4 `Location.text` |
| Location.type | Location.type | Equivalent | R5 `Location.type` maps as Equivalent to R4 `Location.type` |
| Location.virtualService | - | DoesNotExistInTarget | R5 `Location.virtualService` does not appear in the target and has no mapping for `Location`. |

