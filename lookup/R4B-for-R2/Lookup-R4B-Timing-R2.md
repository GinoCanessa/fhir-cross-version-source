### Lookup for FHIR R4B Timing for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Timing.id | UseElementSameName | Timing.id |
| Timing.extension | UseElementSameName | Timing.extension |
| Timing.modifierExtension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Timing.modifierExtension |
| Timing.event | UseElementSameName | Timing.event |
| Timing.repeat | UseElementSameName | Timing.repeat |
| Timing.repeat.id | UseElementSameName | Timing.repeat.id |
| Timing.repeat.extension | UseElementSameName | Timing.repeat.extension |
| Timing.repeat.bounds[x] | UseElementSameName | Timing.repeat.bounds[x] |
| Timing.repeat.count | UseElementSameName | Timing.repeat.count |
| Timing.repeat.countMax | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Timing.repeat.countMax |
| Timing.repeat.duration | UseElementSameName | Timing.repeat.duration |
| Timing.repeat.durationMax | UseElementSameName | Timing.repeat.durationMax |
| Timing.repeat.durationUnit | UseElementRenamed | Timing.repeat.durationUnits |
| Timing.repeat.frequency | UseElementSameName | Timing.repeat.frequency |
| Timing.repeat.frequencyMax | UseElementSameName | Timing.repeat.frequencyMax |
| Timing.repeat.period | UseElementSameName | Timing.repeat.period |
| Timing.repeat.periodMax | UseElementSameName | Timing.repeat.periodMax |
| Timing.repeat.periodUnit | UseElementRenamed | Timing.repeat.periodUnits |
| Timing.repeat.dayOfWeek | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Timing.repeat.dayOfWeek |
| Timing.repeat.timeOfDay | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Timing.repeat.timeOfDay |
| Timing.repeat.when | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Timing.repeat.when |
| Timing.repeat.offset | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Timing.repeat.offset |
| Timing.code | UseElementSameName | Timing.code |
