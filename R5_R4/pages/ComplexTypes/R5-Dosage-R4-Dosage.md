Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Dosage |  | Dosage Type: Indicates how the medication is/was taken or should be taken by the patient. | 23 | 18 |
| Target | Dosage |  | Base StructureDefinition for Dosage Type: Indicates how the medication is/was taken or should be taken by the patient. | 22 | 17 |


Comparison Result: SourceIsBroaderThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 20 |
SourceIsBroaderThanTarget | 3 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Dosage | Dosage | Equivalent | R5 `Dosage` maps as Equivalent to R4 `Dosage` |
| Dosage.additionalInstruction | Dosage.additionalInstruction | Equivalent | R5 `Dosage.additionalInstruction` maps as Equivalent to R4 `Dosage.additionalInstruction` |
| Dosage.asNeeded | Dosage.asNeeded[x] | SourceIsBroaderThanTarget | R5 `Dosage.asNeeded` maps as SourceIsBroaderThanTarget to R4 `Dosage.asNeeded[x]` - asNeeded[x] added a binding requirement - Example http://hl7.org/fhir/ValueSet/medication-as-needed-reason; asNeeded[x] has change due to type change: R5 `asNeeded` `boolean` maps as SourceIsBroaderThanTarget for R4 `asNeeded[x]` |
| Dosage.asNeededFor | Dosage.asNeeded[x] | SourceIsBroaderThanTarget | R5 `Dosage.asNeededFor` maps as SourceIsBroaderThanTarget to R4 `Dosage.asNeeded[x]` - asNeeded[x] changed from array to scalar (max cardinality from * to 1) |
| Dosage.doseAndRate | Dosage.doseAndRate | Equivalent | R5 `Dosage.doseAndRate` maps as Equivalent to R4 `Dosage.doseAndRate` |
| Dosage.doseAndRate.dose[x] | Dosage.doseAndRate.dose[x] | Equivalent | R5 `Dosage.doseAndRate.dose[x]` maps as Equivalent to R4 `Dosage.doseAndRate.dose[x]` |
| Dosage.doseAndRate.extension | Dosage.doseAndRate.extension | Equivalent | R5 `Dosage.doseAndRate.extension` maps as Equivalent to R4 `Dosage.doseAndRate.extension` |
| Dosage.doseAndRate.id | Dosage.doseAndRate.id | Equivalent | R5 `Dosage.doseAndRate.id` maps as Equivalent to R4 `Dosage.doseAndRate.id` |
| Dosage.doseAndRate.rate[x] | Dosage.doseAndRate.rate[x] | Equivalent | R5 `Dosage.doseAndRate.rate[x]` maps as Equivalent to R4 `Dosage.doseAndRate.rate[x]` |
| Dosage.doseAndRate.type | Dosage.doseAndRate.type | Equivalent | R5 `Dosage.doseAndRate.type` maps as Equivalent to R4 `Dosage.doseAndRate.type` |
| Dosage.extension | Dosage.extension | Equivalent | R5 `Dosage.extension` maps as Equivalent to R4 `Dosage.extension` |
| Dosage.id | Dosage.id | Equivalent | R5 `Dosage.id` maps as Equivalent to R4 `Dosage.id` |
| Dosage.maxDosePerAdministration | Dosage.maxDosePerAdministration | Equivalent | R5 `Dosage.maxDosePerAdministration` maps as Equivalent to R4 `Dosage.maxDosePerAdministration` |
| Dosage.maxDosePerLifetime | Dosage.maxDosePerLifetime | Equivalent | R5 `Dosage.maxDosePerLifetime` maps as Equivalent to R4 `Dosage.maxDosePerLifetime` |
| Dosage.maxDosePerPeriod | Dosage.maxDosePerPeriod | SourceIsBroaderThanTarget | R5 `Dosage.maxDosePerPeriod` maps as SourceIsBroaderThanTarget to R4 `Dosage.maxDosePerPeriod` - maxDosePerPeriod changed from array to scalar (max cardinality from * to 1) |
| Dosage.method | Dosage.method | Equivalent | R5 `Dosage.method` maps as Equivalent to R4 `Dosage.method` |
| Dosage.modifierExtension | Dosage.modifierExtension | Equivalent | R5 `Dosage.modifierExtension` maps as Equivalent to R4 `Dosage.modifierExtension` |
| Dosage.patientInstruction | Dosage.patientInstruction | Equivalent | R5 `Dosage.patientInstruction` maps as Equivalent to R4 `Dosage.patientInstruction` |
| Dosage.route | Dosage.route | Equivalent | R5 `Dosage.route` maps as Equivalent to R4 `Dosage.route` |
| Dosage.sequence | Dosage.sequence | Equivalent | R5 `Dosage.sequence` maps as Equivalent to R4 `Dosage.sequence` |
| Dosage.site | Dosage.site | Equivalent | R5 `Dosage.site` maps as Equivalent to R4 `Dosage.site` |
| Dosage.text | Dosage.text | Equivalent | R5 `Dosage.text` maps as Equivalent to R4 `Dosage.text` |
| Dosage.timing | Dosage.timing | Equivalent | R5 `Dosage.timing` maps as Equivalent to R4 `Dosage.timing` |

