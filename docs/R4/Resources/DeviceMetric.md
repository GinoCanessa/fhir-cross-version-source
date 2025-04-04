Comparison of 
Generated at Friday, April 4, 2025 2:58:46 PM

### DeviceMetric

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | DeviceMetric |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DeviceMetric` |
| Version | 4.0.1 |
| Description | Describes a measurement, calculation or setting capability of a medical device. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1067` |
| Database Snapshot Count | `25` |
| Database Differential Count | `14` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DeviceMetric` | `DeviceMetric` | `DeviceMetric` | DeviceMetric | Measurement, calculation or setting capability of a medical device | 0..* | DeviceMetric |  |  |
| `DeviceMetric.calibration` | `DeviceMetric.calibration` | `calibration` | DeviceMetric.calibration | Describes the calibrations that have been performed or that are required to be performed | 0..* | BackboneElement |  |  |
| `DeviceMetric.calibration.extension` | `DeviceMetric.calibration.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceMetric.calibration.id` | `DeviceMetric.calibration.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceMetric.calibration.modifierExtension` | `DeviceMetric.calibration.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceMetric.calibration.state` | `DeviceMetric.calibration.state` | `state` | DeviceMetric.calibration.state | not-calibrated \| calibration-required \| calibrated \| unspecified | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/metric-calibration-state|4.0.1` |
| `DeviceMetric.calibration.time` | `DeviceMetric.calibration.time` | `time` | DeviceMetric.calibration.time | Describes the time last calibration has been performed | 0..1 | instant |  |  |
| `DeviceMetric.calibration.type` | `DeviceMetric.calibration.type` | `type` | DeviceMetric.calibration.type | unspecified \| offset \| gain \| two-point | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/metric-calibration-type|4.0.1` |
| `DeviceMetric.category` | `DeviceMetric.category` | `category` | DeviceMetric.category | measurement \| setting \| calculation \| unspecified | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/metric-category|4.0.1` |
| `DeviceMetric.color` | `DeviceMetric.color` | `color` | DeviceMetric.color | black \| red \| green \| yellow \| blue \| magenta \| cyan \| white | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/metric-color|4.0.1` |
| `DeviceMetric.contained` | `DeviceMetric.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DeviceMetric.extension` | `DeviceMetric.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceMetric.id` | `DeviceMetric.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DeviceMetric.identifier` | `DeviceMetric.identifier` | `identifier` | DeviceMetric.identifier | Instance identifier | 0..* | Identifier |  |  |
| `DeviceMetric.implicitRules` | `DeviceMetric.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DeviceMetric.language` | `DeviceMetric.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `DeviceMetric.measurementPeriod` | `DeviceMetric.measurementPeriod` | `measurementPeriod` | DeviceMetric.measurementPeriod | Describes the measurement repetition time | 0..1 | Timing |  |  |
| `DeviceMetric.meta` | `DeviceMetric.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DeviceMetric.modifierExtension` | `DeviceMetric.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DeviceMetric.operationalStatus` | `DeviceMetric.operationalStatus` | `operationalStatus` | DeviceMetric.operationalStatus | on \| off \| standby \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/metric-operational-status|4.0.1` |
| `DeviceMetric.parent` | `DeviceMetric.parent` | `parent` | DeviceMetric.parent | Describes the link to the parent Device | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device) |  |  |
| `DeviceMetric.source` | `DeviceMetric.source` | `source` | DeviceMetric.source | Describes the link to the source Device | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device) |  |  |
| `DeviceMetric.text` | `DeviceMetric.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `DeviceMetric.type` | `DeviceMetric.type` | `type` | DeviceMetric.type | Identity of metric, for example Heart Rate or PEEP Setting | 1..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/devicemetric-type` |
| `DeviceMetric.unit` | `DeviceMetric.unit` | `unit` | DeviceMetric.unit | Unit of Measure for the Metric | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/devicemetric-type` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DeviceMetric](/docs/R2/Resources/DeviceMetric.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceMetric\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `99`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `266`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceMetric](/docs/R3/Resources/DeviceMetric.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceMetric\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `448`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `643`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceMetric](/docs/R4/Resources/DeviceMetric.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceMetric\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1459`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1460`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceMetric](/docs/R4B/Resources/DeviceMetric.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceMetric\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `964`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1193`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceMetric](/docs/R5/Resources/DeviceMetric.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceMetric\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DeviceMetric from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 DeviceMetric](/docs/R2/Resources/DeviceMetric.md)| Relationship | [R3 DeviceMetric](/docs/R3/Resources/DeviceMetric.md)| Relationship | R4 DeviceMetric| Relationship | [R4B DeviceMetric](/docs/R4B/Resources/DeviceMetric.md)| Relationship | [R5 DeviceMetric](/docs/R5/Resources/DeviceMetric.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `DeviceMetric`| _Equivalent_<br/>(4588/4589)| `DeviceMetric`| _Equivalent_<br/>(12929/12930)| **`DeviceMetric`**| _Equivalent_<br/>(25736/25737)| `DeviceMetric`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40637)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(40638)| `DeviceMetric`
| `DeviceMetric.id`| _Equivalent_<br/>(4590/4591)| `DeviceMetric.id`| _Equivalent_<br/>(12931/12932)| **`DeviceMetric.id`**| _Equivalent_<br/>(25738/25739)| `DeviceMetric.id`| _Equivalent_<br/>(40639/40640)| `DeviceMetric.id`
| `DeviceMetric.meta`| _Equivalent_<br/>(4592/4593)| `DeviceMetric.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12933)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12934)| **`DeviceMetric.meta`**| _Equivalent_<br/>(25740/25741)| `DeviceMetric.meta`| _Equivalent_<br/>(40641/40642)| `DeviceMetric.meta`
| `DeviceMetric.implicitRules`| _Equivalent_<br/>(4594/4595)| `DeviceMetric.implicitRules`| _Equivalent_<br/>(12935/12936)| **`DeviceMetric.implicitRules`**| _Equivalent_<br/>(25742/25743)| `DeviceMetric.implicitRules`| _Equivalent_<br/>(40643/40644)| `DeviceMetric.implicitRules`
| `DeviceMetric.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4596)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4597)| `DeviceMetric.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12937)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12938)| **`DeviceMetric.language`**| _Equivalent_<br/>(25744/25745)| `DeviceMetric.language`| _Equivalent_<br/>(40645/40646)| `DeviceMetric.language`
| `DeviceMetric.text`| _Equivalent_<br/>(4598/4599)| `DeviceMetric.text`| _Equivalent_<br/>(12939/12940)| **`DeviceMetric.text`**| _Equivalent_<br/>(25746/25747)| `DeviceMetric.text`| _Equivalent_<br/>(40647/40648)| `DeviceMetric.text`
| `DeviceMetric.contained`| _Equivalent_<br/>(4600/4601)| `DeviceMetric.contained`| _Equivalent_<br/>(12941/12942)| **`DeviceMetric.contained`**| _Equivalent_<br/>(25748/25749)| `DeviceMetric.contained`| _Equivalent_<br/>(40649/40650)| `DeviceMetric.contained`
| `DeviceMetric.extension`| _Equivalent_<br/>(4602/4603)| `DeviceMetric.extension`| _Equivalent_<br/>(12943/12944)| **`DeviceMetric.extension`**| _Equivalent_<br/>(25750/25751)| `DeviceMetric.extension`| _Equivalent_<br/>(40651/40652)| `DeviceMetric.extension`
| `DeviceMetric.modifierExtension`| _Equivalent_<br/>(4604/4605)| `DeviceMetric.modifierExtension`| _Equivalent_<br/>(12945/12946)| **`DeviceMetric.modifierExtension`**| _Equivalent_<br/>(25752/25753)| `DeviceMetric.modifierExtension`| _Equivalent_<br/>(40653/40654)| `DeviceMetric.modifierExtension`
| `DeviceMetric.identifier`| _Equivalent_<br/>(4608/4609)| `DeviceMetric.identifier`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12947)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12948)| **`DeviceMetric.identifier`**| _Equivalent_<br/>(25754/25755)| `DeviceMetric.identifier`| _Equivalent_<br/>(40655/40656)| `DeviceMetric.identifier`
| `DeviceMetric.type`| _Equivalent_<br/>(4606/4607)| `DeviceMetric.type`| _Equivalent_<br/>(12949/12950)| **`DeviceMetric.type`**| _Equivalent_<br/>(25756/25757)| `DeviceMetric.type`| _Equivalent_<br/>(40657/40658)| `DeviceMetric.type`
| `DeviceMetric.unit`| _Equivalent_<br/>(4610/4611)| `DeviceMetric.unit`| _Equivalent_<br/>(12951/12952)| **`DeviceMetric.unit`**| _Equivalent_<br/>(25758/25759)| `DeviceMetric.unit`| _Equivalent_<br/>(40659/40660)| `DeviceMetric.unit`
| `DeviceMetric.source`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4612)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4613)| `DeviceMetric.source`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12953)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12954)| **`DeviceMetric.source`**| _Equivalent_<br/>(25760/25761)| `DeviceMetric.source`| | | 
| `DeviceMetric.parent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4614)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4615)| `DeviceMetric.parent`| →→→→ _RelatedTo_ →→→→ <br/>(12955)<hr/>←←←← _RelatedTo_ ←←←← <br/>(12956)| **`DeviceMetric.parent`**| _Equivalent_<br/>(25762/25763)| `DeviceMetric.parent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1869)<hr/>←←←← _Equivalent_ ←←←← <br/>(2112)| `DeviceMetric.device`
| `DeviceMetric.operationalStatus`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4616)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4617)| `DeviceMetric.operationalStatus`| _Equivalent_<br/>(12957/12958)| **`DeviceMetric.operationalStatus`**| _Equivalent_<br/>(25764/25765)| `DeviceMetric.operationalStatus`| _Equivalent_<br/>(40662/40663)| `DeviceMetric.operationalStatus`
| `DeviceMetric.color`| _Equivalent_<br/>(4618/4619)| `DeviceMetric.color`| _Equivalent_<br/>(12959/12960)| **`DeviceMetric.color`**| _Equivalent_<br/>(25766/25767)| `DeviceMetric.color`| _Equivalent_<br/>(40664/40665)| `DeviceMetric.color`
| `DeviceMetric.category`| _Equivalent_<br/>(4620/4621)| `DeviceMetric.category`| _Equivalent_<br/>(12961/12962)| **`DeviceMetric.category`**| _Equivalent_<br/>(25768/25769)| `DeviceMetric.category`| _Equivalent_<br/>(40666/40667)| `DeviceMetric.category`
| `DeviceMetric.measurementPeriod`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4622)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4623)| `DeviceMetric.measurementPeriod`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12963)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12964)| **`DeviceMetric.measurementPeriod`**| _Equivalent_<br/>(25770/25771)| `DeviceMetric.measurementPeriod`| | | 
| `DeviceMetric.calibration`| _Equivalent_<br/>(4624/4625)| `DeviceMetric.calibration`| _Equivalent_<br/>(12965/12966)| **`DeviceMetric.calibration`**| _Equivalent_<br/>(25772/25773)| `DeviceMetric.calibration`| _Equivalent_<br/>(40669/40670)| `DeviceMetric.calibration`
| `DeviceMetric.calibration.id`| _Equivalent_<br/>(4626/4627)| `DeviceMetric.calibration.id`| _Equivalent_<br/>(12967/12968)| **`DeviceMetric.calibration.id`**| _Equivalent_<br/>(25774/25775)| `DeviceMetric.calibration.id`| _Equivalent_<br/>(40671/40672)| `DeviceMetric.calibration.id`
| `DeviceMetric.calibration.extension`| _Equivalent_<br/>(4628/4629)| `DeviceMetric.calibration.extension`| _Equivalent_<br/>(12969/12970)| **`DeviceMetric.calibration.extension`**| _Equivalent_<br/>(25776/25777)| `DeviceMetric.calibration.extension`| _Equivalent_<br/>(40673/40674)| `DeviceMetric.calibration.extension`
| `DeviceMetric.calibration.modifierExtension`| _Equivalent_<br/>(4630/4631)| `DeviceMetric.calibration.modifierExtension`| _Equivalent_<br/>(12971/12972)| **`DeviceMetric.calibration.modifierExtension`**| _Equivalent_<br/>(25778/25779)| `DeviceMetric.calibration.modifierExtension`| _Equivalent_<br/>(40675/40676)| `DeviceMetric.calibration.modifierExtension`
| `DeviceMetric.calibration.type`| _Equivalent_<br/>(4632/4633)| `DeviceMetric.calibration.type`| _Equivalent_<br/>(12973/12974)| **`DeviceMetric.calibration.type`**| _Equivalent_<br/>(25780/25781)| `DeviceMetric.calibration.type`| _Equivalent_<br/>(40677/40678)| `DeviceMetric.calibration.type`
| `DeviceMetric.calibration.state`| _Equivalent_<br/>(4634/4635)| `DeviceMetric.calibration.state`| _Equivalent_<br/>(12975/12976)| **`DeviceMetric.calibration.state`**| _Equivalent_<br/>(25782/25783)| `DeviceMetric.calibration.state`| _Equivalent_<br/>(40679/40680)| `DeviceMetric.calibration.state`
| `DeviceMetric.calibration.time`| _Equivalent_<br/>(4636/4637)| `DeviceMetric.calibration.time`| _Equivalent_<br/>(12977/12978)| **`DeviceMetric.calibration.time`**| _Equivalent_<br/>(25784/25785)| `DeviceMetric.calibration.time`| _Equivalent_<br/>(40681/40682)| `DeviceMetric.calibration.time`
| *25 of 25 elements used* | | *25 of 25 elements used* | | *25 of 25 elements used* | | *25 of 25 elements used* | | *23 of 24 elements used* <br/>remaining elements:<br/>`DeviceMetric.measurementFrequency`

