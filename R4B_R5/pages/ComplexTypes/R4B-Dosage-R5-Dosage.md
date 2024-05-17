Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:03 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Dosage |  | Base StructureDefinition for Dosage Type: Indicates how the medication is/was taken or should be taken by the patient. | 22 | 17 |
| Target | Dosage |  | Dosage Type: Indicates how the medication is/was taken or should be taken by the patient. | 23 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 18 |
RelatedTo | 3 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Dosage | Dosage | Equivalent | R4B `Dosage` maps as Equivalent to R5 `Dosage` |
| Dosage.additionalInstruction | Dosage.additionalInstruction | Equivalent | R4B `Dosage.additionalInstruction` maps as Equivalent to R5 `Dosage.additionalInstruction` |
| Dosage.asNeeded[x] | - | DoesNotExistInTarget | R4B `Dosage.asNeeded[x]` does not appear in the target and has no mapping for `Dosage`. |
| Dosage.doseAndRate | Dosage.doseAndRate | Equivalent | R4B `Dosage.doseAndRate` maps as Equivalent to R5 `Dosage.doseAndRate` |
| Dosage.doseAndRate.dose[x] | Dosage.doseAndRate.dose[x] | Equivalent | R4B `Dosage.doseAndRate.dose[x]` maps as Equivalent to R5 `Dosage.doseAndRate.dose[x]` |
| Dosage.doseAndRate.extension | Dosage.doseAndRate.extension | Equivalent | R4B `Dosage.doseAndRate.extension` maps as Equivalent to R5 `Dosage.doseAndRate.extension` |
| Dosage.doseAndRate.id | Dosage.doseAndRate.id | Equivalent | R4B `Dosage.doseAndRate.id` maps as Equivalent to R5 `Dosage.doseAndRate.id` |
| Dosage.doseAndRate.rate[x] | Dosage.doseAndRate.rate[x] | Equivalent | R4B `Dosage.doseAndRate.rate[x]` maps as Equivalent to R5 `Dosage.doseAndRate.rate[x]` |
| Dosage.doseAndRate.type | Dosage.doseAndRate.type | Equivalent | R4B `Dosage.doseAndRate.type` maps as Equivalent to R5 `Dosage.doseAndRate.type` |
| Dosage.extension | Dosage.extension | Equivalent | R4B `Dosage.extension` maps as Equivalent to R5 `Dosage.extension` |
| Dosage.id | Dosage.id | Equivalent | R4B `Dosage.id` maps as Equivalent to R5 `Dosage.id` |
| Dosage.maxDosePerAdministration | Dosage.maxDosePerAdministration | Equivalent | R4B `Dosage.maxDosePerAdministration` maps as Equivalent to R5 `Dosage.maxDosePerAdministration` |
| Dosage.maxDosePerLifetime | Dosage.maxDosePerLifetime | Equivalent | R4B `Dosage.maxDosePerLifetime` maps as Equivalent to R5 `Dosage.maxDosePerLifetime` |
| Dosage.maxDosePerPeriod | Dosage.maxDosePerPeriod | RelatedTo | R4B `Dosage.maxDosePerPeriod` maps as RelatedTo to R5 `Dosage.maxDosePerPeriod` - maxDosePerPeriod changed from scalar to array (max cardinality from 1 to *) |
| Dosage.method | Dosage.method | Equivalent | R4B `Dosage.method` maps as Equivalent to R5 `Dosage.method` |
| Dosage.modifierExtension | Dosage.modifierExtension | Equivalent | R4B `Dosage.modifierExtension` maps as Equivalent to R5 `Dosage.modifierExtension` |
| Dosage.patientInstruction | Dosage.patientInstruction | Equivalent | R4B `Dosage.patientInstruction` maps as Equivalent to R5 `Dosage.patientInstruction` |
| Dosage.route | Dosage.route | Equivalent | R4B `Dosage.route` maps as Equivalent to R5 `Dosage.route` |
| Dosage.sequence | Dosage.sequence | Equivalent | R4B `Dosage.sequence` maps as Equivalent to R5 `Dosage.sequence` |
| Dosage.site | Dosage.site | Equivalent | R4B `Dosage.site` maps as Equivalent to R5 `Dosage.site` |
| Dosage.text | Dosage.text | Equivalent | R4B `Dosage.text` maps as Equivalent to R5 `Dosage.text` |
| Dosage.timing | Dosage.timing | Equivalent | R4B `Dosage.timing` maps as Equivalent to R5 `Dosage.timing` |

