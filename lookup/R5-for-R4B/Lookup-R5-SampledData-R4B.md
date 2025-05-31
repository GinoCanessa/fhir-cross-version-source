### Lookup for FHIR R5 SampledData for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| SampledData.id | UseElementRenamed | SampledData.id |
| SampledData.extension | UseElementRenamed | SampledData.extension |
| SampledData.origin | UseElementRenamed | SampledData.origin |
| SampledData.interval | UseElementRenamed | SampledData.period |
| SampledData.intervalUnit | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SampledData.intervalUnit |
| SampledData.factor | UseElementRenamed | SampledData.factor |
| SampledData.lowerLimit | UseElementRenamed | SampledData.lowerLimit |
| SampledData.upperLimit | UseElementRenamed | SampledData.upperLimit |
| SampledData.dimensions | UseElementRenamed | SampledData.dimensions |
| SampledData.codeMap | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SampledData.codeMap |
| SampledData.offsets | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SampledData.offsets |
| SampledData.data | UseElementRenamed | SampledData.data |
