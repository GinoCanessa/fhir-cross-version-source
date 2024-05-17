Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Timing |  | Timing Type: Specifies an event that may occur multiple times. Timing schedules are used to record when things are planned, expected or requested to occur. The most common usage is in dosage instructions for medications. They are also used when planning care of various kinds, and may be used for reporting the schedule to which past regular activities were carried out. | 24 | 19 |
| Target | Timing |  | Base StructureDefinition for Timing Type: Specifies an event that may occur multiple times. Timing schedules are used to record when things are planned, expected or requested to occur. The most common usage is in dosage instructions for medications. They are also used when planning care of various kinds, and may be used for reporting the schedule to which past regular activities were carried out. | 24 | 19 |


Comparison Result: Equivalent


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 24 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Timing | Timing | Equivalent | R5 `Timing` maps as Equivalent to R4B `Timing` |
| Timing.code | Timing.code | Equivalent | R5 `Timing.code` maps as Equivalent to R4B `Timing.code` |
| Timing.event | Timing.event | Equivalent | R5 `Timing.event` maps as Equivalent to R4B `Timing.event` |
| Timing.extension | Timing.extension | Equivalent | R5 `Timing.extension` maps as Equivalent to R4B `Timing.extension` |
| Timing.id | Timing.id | Equivalent | R5 `Timing.id` maps as Equivalent to R4B `Timing.id` |
| Timing.modifierExtension | Timing.modifierExtension | Equivalent | R5 `Timing.modifierExtension` maps as Equivalent to R4B `Timing.modifierExtension` |
| Timing.repeat | Timing.repeat | Equivalent | R5 `Timing.repeat` maps as Equivalent to R4B `Timing.repeat` |
| Timing.repeat.bounds[x] | Timing.repeat.bounds[x] | Equivalent | R5 `Timing.repeat.bounds[x]` maps as Equivalent to R4B `Timing.repeat.bounds[x]` |
| Timing.repeat.count | Timing.repeat.count | Equivalent | R5 `Timing.repeat.count` maps as Equivalent to R4B `Timing.repeat.count` |
| Timing.repeat.countMax | Timing.repeat.countMax | Equivalent | R5 `Timing.repeat.countMax` maps as Equivalent to R4B `Timing.repeat.countMax` |
| Timing.repeat.dayOfWeek | Timing.repeat.dayOfWeek | Equivalent | R5 `Timing.repeat.dayOfWeek` maps as Equivalent to R4B `Timing.repeat.dayOfWeek` - dayOfWeek has compatible required binding for code type: http://hl7.org/fhir/ValueSet/days-of-week|5.0.0 and http://hl7.org/fhir/ValueSet/days-of-week|4.3.0 (Equivalent) |
| Timing.repeat.duration | Timing.repeat.duration | Equivalent | R5 `Timing.repeat.duration` maps as Equivalent to R4B `Timing.repeat.duration` |
| Timing.repeat.durationMax | Timing.repeat.durationMax | Equivalent | R5 `Timing.repeat.durationMax` maps as Equivalent to R4B `Timing.repeat.durationMax` |
| Timing.repeat.durationUnit | Timing.repeat.durationUnit | Equivalent | R5 `Timing.repeat.durationUnit` maps as Equivalent to R4B `Timing.repeat.durationUnit` - durationUnit has compatible required binding for code type: http://hl7.org/fhir/ValueSet/units-of-time|5.0.0 and http://hl7.org/fhir/ValueSet/units-of-time|4.3.0 (Equivalent) |
| Timing.repeat.extension | Timing.repeat.extension | Equivalent | R5 `Timing.repeat.extension` maps as Equivalent to R4B `Timing.repeat.extension` |
| Timing.repeat.frequency | Timing.repeat.frequency | Equivalent | R5 `Timing.repeat.frequency` maps as Equivalent to R4B `Timing.repeat.frequency` |
| Timing.repeat.frequencyMax | Timing.repeat.frequencyMax | Equivalent | R5 `Timing.repeat.frequencyMax` maps as Equivalent to R4B `Timing.repeat.frequencyMax` |
| Timing.repeat.id | Timing.repeat.id | Equivalent | R5 `Timing.repeat.id` maps as Equivalent to R4B `Timing.repeat.id` |
| Timing.repeat.offset | Timing.repeat.offset | Equivalent | R5 `Timing.repeat.offset` maps as Equivalent to R4B `Timing.repeat.offset` |
| Timing.repeat.period | Timing.repeat.period | Equivalent | R5 `Timing.repeat.period` maps as Equivalent to R4B `Timing.repeat.period` |
| Timing.repeat.periodMax | Timing.repeat.periodMax | Equivalent | R5 `Timing.repeat.periodMax` maps as Equivalent to R4B `Timing.repeat.periodMax` |
| Timing.repeat.periodUnit | Timing.repeat.periodUnit | Equivalent | R5 `Timing.repeat.periodUnit` maps as Equivalent to R4B `Timing.repeat.periodUnit` - periodUnit has compatible required binding for code type: http://hl7.org/fhir/ValueSet/units-of-time|5.0.0 and http://hl7.org/fhir/ValueSet/units-of-time|4.3.0 (Equivalent) |
| Timing.repeat.timeOfDay | Timing.repeat.timeOfDay | Equivalent | R5 `Timing.repeat.timeOfDay` maps as Equivalent to R4B `Timing.repeat.timeOfDay` |
| Timing.repeat.when | Timing.repeat.when | Equivalent | R5 `Timing.repeat.when` maps as Equivalent to R4B `Timing.repeat.when` - when has compatible required binding for code type: http://hl7.org/fhir/ValueSet/event-timing|5.0.0 and http://hl7.org/fhir/ValueSet/event-timing|4.3.0 (Equivalent) |

