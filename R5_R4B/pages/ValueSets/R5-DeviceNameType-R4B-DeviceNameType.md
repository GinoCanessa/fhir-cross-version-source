Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/device-nametype | DeviceNameType | Device Name Type | The type of name the device is referred by. |
| Target | http://hl7.org/fhir/ValueSet/device-nametype | DeviceNameType | DeviceNameType | The type of name the device is referred by. |


Comparison Result: SourceIsBroaderThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 2 |
SourceIsBroaderThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| patient-reported-name | patient-reported-name | Equivalent | R5 `patient-reported-name` is equivalent to R4B `patient-reported-name`. |
| registered-name | manufacturer-name | SourceIsBroaderThanTarget | R5 `registered-name` is broader than R4B manufacturer-name and requires mapping choice. `registered-name` maps to `manufacturer-name` and `model-name` and `other` and `udi-label-name`. |
| registered-name | model-name | SourceIsBroaderThanTarget | R5 `registered-name` is broader than R4B model-name and requires mapping choice. `registered-name` maps to `manufacturer-name` and `model-name` and `other` and `udi-label-name`. |
| registered-name | other | SourceIsBroaderThanTarget | R5 `registered-name` is broader than R4B other and requires mapping choice. `registered-name` maps to `manufacturer-name` and `model-name` and `other` and `udi-label-name`. |
| registered-name | udi-label-name | SourceIsBroaderThanTarget | R5 `registered-name` is broader than R4B udi-label-name and requires mapping choice. `registered-name` maps to `manufacturer-name` and `model-name` and `other` and `udi-label-name`. |
| user-friendly-name | user-friendly-name | Equivalent | R5 `user-friendly-name` is equivalent to R4B `user-friendly-name`. |

