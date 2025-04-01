Comparison of 
Generated at Tuesday, April 1, 2025 1:39:14 PM

### DeviceComponent

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | DeviceComponent |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DeviceComponent` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for DeviceComponent Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `506` |
| Database Snapshot Count | `25` |
| Database Differential Count | `14` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DeviceComponent` | `DeviceComponent` | `DeviceComponent` | DeviceComponent | An instance of a medical-related component of a medical device | 0..* | DeviceComponent |  |  |
| `DeviceComponent.contained` | `DeviceComponent.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DeviceComponent.extension` | `DeviceComponent.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DeviceComponent.id` | `DeviceComponent.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DeviceComponent.identifier` | `DeviceComponent.identifier` | `identifier` |  | Instance id assigned by the software stack | 1..1 | Identifier |  |  |
| `DeviceComponent.implicitRules` | `DeviceComponent.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DeviceComponent.language` | `DeviceComponent.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `DeviceComponent.languageCode` | `DeviceComponent.languageCode` | `languageCode` |  | Language code for the human-readable text strings produced by the device | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `DeviceComponent.lastSystemChange` | `DeviceComponent.lastSystemChange` | `lastSystemChange` |  | Recent system change timestamp | 0..1 | instant |  |  |
| `DeviceComponent.measurementPrinciple` | `DeviceComponent.measurementPrinciple` | `measurementPrinciple` |  | other \| chemical \| electrical \| impedance \| nuclear \| optical \| thermal \| biological \| mechanical \| acoustical \| manual+ | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/measurement-principle` |
| `DeviceComponent.meta` | `DeviceComponent.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DeviceComponent.modifierExtension` | `DeviceComponent.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DeviceComponent.operationalStatus` | `DeviceComponent.operationalStatus` | `operationalStatus` |  | Current operational status of the component, for example On, Off or Standby | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/operational-status` |
| `DeviceComponent.parameterGroup` | `DeviceComponent.parameterGroup` | `parameterGroup` |  | Current supported parameter group | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/parameter-group` |
| `DeviceComponent.parent` | `DeviceComponent.parent` | `parent` |  | Parent resource link | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/DeviceComponent) |  |  |
| `DeviceComponent.productionSpecification` | `DeviceComponent.productionSpecification` | `productionSpecification` |  | Specification details such as Component Revisions, or Serial Numbers | 0..* | BackboneElement |  |  |
| `DeviceComponent.productionSpecification.componentId` | `DeviceComponent.productionSpecification.componentId` | `componentId` |  | Internal component unique identification | 0..1 | Identifier |  |  |
| `DeviceComponent.productionSpecification.extension` | `DeviceComponent.productionSpecification.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DeviceComponent.productionSpecification.id` | `DeviceComponent.productionSpecification.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `DeviceComponent.productionSpecification.modifierExtension` | `DeviceComponent.productionSpecification.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DeviceComponent.productionSpecification.productionSpec` | `DeviceComponent.productionSpecification.productionSpec` | `productionSpec` |  | A printable string defining the component | 0..1 | string |  |  |
| `DeviceComponent.productionSpecification.specType` | `DeviceComponent.productionSpecification.specType` | `specType` |  | Type or kind of production specification, for example serial number or software revision | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/specification-type` |
| `DeviceComponent.source` | `DeviceComponent.source` | `source` |  | Top-level device resource link | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device) |  |  |
| `DeviceComponent.text` | `DeviceComponent.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `DeviceComponent.type` | `DeviceComponent.type` | `type` |  | What kind of component it is | 1..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/device-kind` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DeviceComponent](/docs/R2/Resources/DeviceComponent.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceComponent\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `98`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `265`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceComponent](/docs/R3/Resources/DeviceComponent.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceComponent\|3.0.2` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | | | 
### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DeviceComponent from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 DeviceComponent](/docs/R2/Resources/DeviceComponent.md)| Relationship | R3 DeviceComponent| Relationship | *No Map* | Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `DeviceComponent`| _Equivalent_<br/>(4538/4539)| **`DeviceComponent`**| | | | | | | 
| `DeviceComponent.id`| _Equivalent_<br/>(4540/4541)| **`DeviceComponent.id`**| | | | | | | 
| `DeviceComponent.meta`| _Equivalent_<br/>(4542/4543)| **`DeviceComponent.meta`**| | | | | | | 
| `DeviceComponent.implicitRules`| _Equivalent_<br/>(4544/4545)| **`DeviceComponent.implicitRules`**| | | | | | | 
| `DeviceComponent.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4546)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4547)| **`DeviceComponent.language`**| | | | | | | 
| `DeviceComponent.text`| _Equivalent_<br/>(4548/4549)| **`DeviceComponent.text`**| | | | | | | 
| `DeviceComponent.contained`| _Equivalent_<br/>(4550/4551)| **`DeviceComponent.contained`**| | | | | | | 
| `DeviceComponent.extension`| _Equivalent_<br/>(4552/4553)| **`DeviceComponent.extension`**| | | | | | | 
| `DeviceComponent.modifierExtension`| _Equivalent_<br/>(4554/4555)| **`DeviceComponent.modifierExtension`**| | | | | | | 
| `DeviceComponent.identifier`| _Equivalent_<br/>(4558/4559)| **`DeviceComponent.identifier`**| | | | | | | 
| `DeviceComponent.type`| _Equivalent_<br/>(4556/4557)| **`DeviceComponent.type`**| | | | | | | 
| `DeviceComponent.lastSystemChange`| →→→→ _Equivalent_ →→→→ <br/>(4560)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4561)| **`DeviceComponent.lastSystemChange`**| | | | | | | 
| `DeviceComponent.source`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4562)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4563)| **`DeviceComponent.source`**| | | | | | | 
| `DeviceComponent.parent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4564)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4565)| **`DeviceComponent.parent`**| | | | | | | 
| `DeviceComponent.operationalStatus`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4566)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4567)| **`DeviceComponent.operationalStatus`**| | | | | | | 
| `DeviceComponent.parameterGroup`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4568)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4569)| **`DeviceComponent.parameterGroup`**| | | | | | | 
| `DeviceComponent.measurementPrinciple`| _Equivalent_<br/>(4570/4571)| **`DeviceComponent.measurementPrinciple`**| | | | | | | 
| `DeviceComponent.productionSpecification`| _Equivalent_<br/>(4572/4573)| **`DeviceComponent.productionSpecification`**| | | | | | | 
| `DeviceComponent.productionSpecification.id`| _Equivalent_<br/>(4574/4575)| **`DeviceComponent.productionSpecification.id`**| | | | | | | 
| `DeviceComponent.productionSpecification.extension`| _Equivalent_<br/>(4576/4577)| **`DeviceComponent.productionSpecification.extension`**| | | | | | | 
| `DeviceComponent.productionSpecification.modifierExtension`| _Equivalent_<br/>(4578/4579)| **`DeviceComponent.productionSpecification.modifierExtension`**| | | | | | | 
| `DeviceComponent.productionSpecification.specType`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4580)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4581)| **`DeviceComponent.productionSpecification.specType`**| | | | | | | 
| `DeviceComponent.productionSpecification.componentId`| _Equivalent_<br/>(4582/4583)| **`DeviceComponent.productionSpecification.componentId`**| | | | | | | 
| `DeviceComponent.productionSpecification.productionSpec`| _Equivalent_<br/>(4584/4585)| **`DeviceComponent.productionSpecification.productionSpec`**| | | | | | | 
| `DeviceComponent.languageCode`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4586)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4587)| **`DeviceComponent.languageCode`**| | | | | | | 
| *25 of 25 elements used* | | *25 of 25 elements used* | | | | | | 

