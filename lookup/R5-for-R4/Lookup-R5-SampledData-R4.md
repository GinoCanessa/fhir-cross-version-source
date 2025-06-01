### Lookup for FHIR R5 SampledData for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| SampledData.id | UseElementSameName | SampledData.id |
| SampledData.extension | UseElementSameName | SampledData.extension |
| SampledData.origin | UseElementSameName | SampledData.origin |
| SampledData.interval | UseElementRenamed | SampledData.period |
| SampledData.intervalUnit | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SampledData.intervalUnit |
| SampledData.factor | UseElementSameName | SampledData.factor |
| SampledData.lowerLimit | UseElementSameName | SampledData.lowerLimit |
| SampledData.upperLimit | UseElementSameName | SampledData.upperLimit |
| SampledData.dimensions | UseElementSameName | SampledData.dimensions |
| SampledData.codeMap | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SampledData.codeMap |
| SampledData.offsets | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SampledData.offsets |
| SampledData.data | UseElementSameName | SampledData.data |
