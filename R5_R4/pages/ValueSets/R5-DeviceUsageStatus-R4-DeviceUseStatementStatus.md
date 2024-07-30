Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/deviceusage-status | DeviceUsageStatus | Device Usage Status | A coded concept indicating the current status of the Device Usage. |
| Target | http://hl7.org/fhir/ValueSet/device-statement-status | DeviceUseStatementStatus | DeviceUseStatementStatus | A coded concept indicating the current status of the Device Usage. |


Comparison Result: Equivalent


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 6 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| active | active | Equivalent | R5 `active` is equivalent to R4 `active`. |
| completed | completed | Equivalent | R5 `completed` is equivalent to R4 `completed`. |
| entered-in-error | entered-in-error | Equivalent | R5 `entered-in-error` is equivalent to R4 `entered-in-error`. |
| intended | intended | Equivalent | R5 `intended` is equivalent to R4 `intended`. |
| not-done | - | DoesNotExistInTarget | R5 `not-done` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/device-statement-status. |
| on-hold | on-hold | Equivalent | R5 `on-hold` is equivalent to R4 `on-hold`. |
| stopped | stopped | Equivalent | R5 `stopped` is equivalent to R4 `stopped`. |

