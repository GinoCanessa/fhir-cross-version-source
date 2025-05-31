### Lookup for FHIR R2 Timing for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Timing.id | UseElementSameName | Timing.id |
| Timing.extension | UseElementSameName | Timing.extension |
| Timing.event | UseElementSameName | Timing.event |
| Timing.repeat | UseElementSameName | Timing.repeat |
| Timing.repeat.id | UseElementSameName | Timing.repeat.id |
| Timing.repeat.extension | UseElementSameName | Timing.repeat.extension |
| Timing.repeat.bounds[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Timing.repeat.bounds |
| Timing.repeat.count | UseElementSameName | Timing.repeat.count |
| Timing.repeat.duration | UseElementSameName | Timing.repeat.duration |
| Timing.repeat.durationMax | UseElementSameName | Timing.repeat.durationMax |
| Timing.repeat.durationUnits | UseElementRenamed | Timing.repeat.durationUnit |
| Timing.repeat.frequency | UseElementSameName | Timing.repeat.frequency |
| Timing.repeat.frequencyMax | UseElementSameName | Timing.repeat.frequencyMax |
| Timing.repeat.period | UseElementSameName | Timing.repeat.period |
| Timing.repeat.periodMax | UseElementSameName | Timing.repeat.periodMax |
| Timing.repeat.periodUnits | UseElementRenamed | Timing.repeat.periodUnit |
| Timing.repeat.when | UseElementSameName | Timing.repeat.when |
| Timing.code | UseElementSameName | Timing.code |
