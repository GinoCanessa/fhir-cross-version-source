Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:03 AM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/device-nametype | DeviceNameType | DeviceNameType | The type of name the device is referred by. |
| Target | http://hl7.org/fhir/ValueSet/device-nametype | DeviceNameType | Device Name Type | The type of name the device is referred by. |


Comparison Result: SourceIsNarrowerThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 2 |
SourceIsNarrowerThanTarget | 4 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| manufacturer-name | registered-name | SourceIsNarrowerThanTarget | R4B `manufacturer-name` is narrower than R5 `registered-name` and is compatible. `registered-name` is mapped from `manufacturer-name` and `model-name` and `other` and `udi-label-name`. |
| model-name | registered-name | SourceIsNarrowerThanTarget | R4B `model-name` is narrower than R5 `registered-name` and is compatible. `registered-name` is mapped from `manufacturer-name` and `model-name` and `other` and `udi-label-name`. |
| other | registered-name | SourceIsNarrowerThanTarget | R4B `other` is narrower than R5 `registered-name` and is compatible. `registered-name` is mapped from `manufacturer-name` and `model-name` and `other` and `udi-label-name`. |
| patient-reported-name | patient-reported-name | Equivalent | R4B `patient-reported-name` is equivalent to R5 `patient-reported-name`. |
| udi-label-name | registered-name | SourceIsNarrowerThanTarget | R4B `udi-label-name` is narrower than R5 `registered-name` and is compatible. `registered-name` is mapped from `manufacturer-name` and `model-name` and `other` and `udi-label-name`. |
| user-friendly-name | user-friendly-name | Equivalent | R4B `user-friendly-name` is equivalent to R5 `user-friendly-name`. |

