Comparison of 
Generated at Monday, April 14, 2025 6:17:30 PM

### ObservationDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | ObservationDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ObservationDefinition` |
| Version | 4.0.1 |
| Description | Set of definitional characteristics for a kind of observation or measurement produced or consumed by an orderable health care service. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1128` |
| Database Snapshot Count | `40` |
| Database Differential Count | `26` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ObservationDefinition` | `ObservationDefinition` | `ObservationDefinition` | ObservationDefinition | Definition of an observation | 0..* | ObservationDefinition |  |  |
| `ObservationDefinition.abnormalCodedValueSet` | `ObservationDefinition.abnormalCodedValueSet` | `abnormalCodedValueSet` | ObservationDefinition.abnormalCodedValueSet | Value set of abnormal coded values for the observations conforming to this ObservationDefinition | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/ValueSet) |  |  |
| `ObservationDefinition.category` | `ObservationDefinition.category` | `category` | ObservationDefinition.category | Category of observation | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/observation-category` |
| `ObservationDefinition.code` | `ObservationDefinition.code` | `code` | ObservationDefinition.code | Type of observation (code / type) | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/observation-codes` |
| `ObservationDefinition.contained` | `ObservationDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ObservationDefinition.criticalCodedValueSet` | `ObservationDefinition.criticalCodedValueSet` | `criticalCodedValueSet` | ObservationDefinition.criticalCodedValueSet | Value set of critical coded values for the observations conforming to this ObservationDefinition | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/ValueSet) |  |  |
| `ObservationDefinition.extension` | `ObservationDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ObservationDefinition.id` | `ObservationDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ObservationDefinition.identifier` | `ObservationDefinition.identifier` | `identifier` | ObservationDefinition.identifier | Business identifier for this ObservationDefinition instance | 0..* | Identifier |  |  |
| `ObservationDefinition.implicitRules` | `ObservationDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ObservationDefinition.language` | `ObservationDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `ObservationDefinition.meta` | `ObservationDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ObservationDefinition.method` | `ObservationDefinition.method` | `method` | ObservationDefinition.method | Method used to produce the observation | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/observation-methods` |
| `ObservationDefinition.modifierExtension` | `ObservationDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ObservationDefinition.multipleResultsAllowed` | `ObservationDefinition.multipleResultsAllowed` | `multipleResultsAllowed` | ObservationDefinition.multipleResultsAllowed | Multiple results allowed | 0..1 | boolean |  |  |
| `ObservationDefinition.normalCodedValueSet` | `ObservationDefinition.normalCodedValueSet` | `normalCodedValueSet` | ObservationDefinition.normalCodedValueSet | Value set of normal coded values for the observations conforming to this ObservationDefinition | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/ValueSet) |  |  |
| `ObservationDefinition.permittedDataType` | `ObservationDefinition.permittedDataType` | `permittedDataType` | ObservationDefinition.permittedDataType | Quantity \| CodeableConcept \| string \| boolean \| integer \| Range \| Ratio \| SampledData \| time \| dateTime \| Period | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/permitted-data-type|4.0.1` |
| `ObservationDefinition.preferredReportName` | `ObservationDefinition.preferredReportName` | `preferredReportName` | ObservationDefinition.preferredReportName | Preferred report name | 0..1 | string |  |  |
| `ObservationDefinition.qualifiedInterval` | `ObservationDefinition.qualifiedInterval` | `qualifiedInterval` | ObservationDefinition.qualifiedInterval | Qualified range for continuous and ordinal observation results | 0..* | BackboneElement |  |  |
| `ObservationDefinition.qualifiedInterval.age` | `ObservationDefinition.qualifiedInterval.age` | `age` | ObservationDefinition.qualifiedInterval.age | Applicable age range, if relevant | 0..1 | Range |  |  |
| `ObservationDefinition.qualifiedInterval.appliesTo` | `ObservationDefinition.qualifiedInterval.appliesTo` | `appliesTo` | ObservationDefinition.qualifiedInterval.appliesTo | Targetted population of the range | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/referencerange-appliesto` |
| `ObservationDefinition.qualifiedInterval.category` | `ObservationDefinition.qualifiedInterval.category` | `category` | ObservationDefinition.qualifiedInterval.category | reference \| critical \| absolute | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/observation-range-category|4.0.1` |
| `ObservationDefinition.qualifiedInterval.condition` | `ObservationDefinition.qualifiedInterval.condition` | `condition` | ObservationDefinition.qualifiedInterval.condition | Condition associated with the reference range | 0..1 | string |  |  |
| `ObservationDefinition.qualifiedInterval.context` | `ObservationDefinition.qualifiedInterval.context` | `context` | ObservationDefinition.qualifiedInterval.context | Range context qualifier | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/referencerange-meaning` |
| `ObservationDefinition.qualifiedInterval.extension` | `ObservationDefinition.qualifiedInterval.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ObservationDefinition.qualifiedInterval.gender` | `ObservationDefinition.qualifiedInterval.gender` | `gender` | ObservationDefinition.qualifiedInterval.gender | male \| female \| other \| unknown | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/administrative-gender|4.0.1` |
| `ObservationDefinition.qualifiedInterval.gestationalAge` | `ObservationDefinition.qualifiedInterval.gestationalAge` | `gestationalAge` | ObservationDefinition.qualifiedInterval.gestationalAge | Applicable gestational age range, if relevant | 0..1 | Range |  |  |
| `ObservationDefinition.qualifiedInterval.id` | `ObservationDefinition.qualifiedInterval.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ObservationDefinition.qualifiedInterval.modifierExtension` | `ObservationDefinition.qualifiedInterval.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ObservationDefinition.qualifiedInterval.range` | `ObservationDefinition.qualifiedInterval.range` | `range` | ObservationDefinition.qualifiedInterval.range | The interval itself, for continuous or ordinal observations | 0..1 | Range |  |  |
| `ObservationDefinition.quantitativeDetails` | `ObservationDefinition.quantitativeDetails` | `quantitativeDetails` | ObservationDefinition.quantitativeDetails | Characteristics of quantitative results | 0..1 | BackboneElement |  |  |
| `ObservationDefinition.quantitativeDetails.conversionFactor` | `ObservationDefinition.quantitativeDetails.conversionFactor` | `conversionFactor` | ObservationDefinition.quantitativeDetails.conversionFactor | SI to Customary unit conversion factor | 0..1 | decimal |  |  |
| `ObservationDefinition.quantitativeDetails.customaryUnit` | `ObservationDefinition.quantitativeDetails.customaryUnit` | `customaryUnit` | ObservationDefinition.quantitativeDetails.customaryUnit | Customary unit for quantitative results | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/ucum-units` |
| `ObservationDefinition.quantitativeDetails.decimalPrecision` | `ObservationDefinition.quantitativeDetails.decimalPrecision` | `decimalPrecision` | ObservationDefinition.quantitativeDetails.decimalPrecision | Decimal precision of observation quantitative results | 0..1 | integer |  |  |
| `ObservationDefinition.quantitativeDetails.extension` | `ObservationDefinition.quantitativeDetails.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ObservationDefinition.quantitativeDetails.id` | `ObservationDefinition.quantitativeDetails.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ObservationDefinition.quantitativeDetails.modifierExtension` | `ObservationDefinition.quantitativeDetails.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ObservationDefinition.quantitativeDetails.unit` | `ObservationDefinition.quantitativeDetails.unit` | `unit` | ObservationDefinition.quantitativeDetails.unit | SI unit for quantitative results | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/ucum-units` |
| `ObservationDefinition.text` | `ObservationDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ObservationDefinition.validCodedValueSet` | `ObservationDefinition.validCodedValueSet` | `validCodedValueSet` | ObservationDefinition.validCodedValueSet | Value set of valid coded values for the observations conforming to this ObservationDefinition | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/ValueSet) |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [ObservationDefinition](/docs/R4/Resources/ObservationDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ObservationDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1559`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1560`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ObservationDefinition](/docs/R4B/Resources/ObservationDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ObservationDefinition\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1290`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ObservationDefinition](/docs/R5/Resources/ObservationDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ObservationDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ObservationDefinition from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | R4 ObservationDefinition| Relationship | [R4B ObservationDefinition](/docs/R4B/Resources/ObservationDefinition.md)| Relationship | [R5 ObservationDefinition](/docs/R5/Resources/ObservationDefinition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | **`ObservationDefinition`**| _Equivalent_<br/>(30891/30892)| `ObservationDefinition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(45548)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45549)| `ObservationDefinition`
| | | | | **`ObservationDefinition.id`**| _Equivalent_<br/>(30893/30894)| `ObservationDefinition.id`| _Equivalent_<br/>(45550/45551)| `ObservationDefinition.id`
| | | | | **`ObservationDefinition.meta`**| _Equivalent_<br/>(30895/30896)| `ObservationDefinition.meta`| _Equivalent_<br/>(45552/45553)| `ObservationDefinition.meta`
| | | | | **`ObservationDefinition.implicitRules`**| _Equivalent_<br/>(30897/30898)| `ObservationDefinition.implicitRules`| _Equivalent_<br/>(45554/45555)| `ObservationDefinition.implicitRules`
| | | | | **`ObservationDefinition.language`**| _Equivalent_<br/>(30899/30900)| `ObservationDefinition.language`| _Equivalent_<br/>(45556/45557)| `ObservationDefinition.language`
| | | | | **`ObservationDefinition.text`**| _Equivalent_<br/>(30901/30902)| `ObservationDefinition.text`| _Equivalent_<br/>(45558/45559)| `ObservationDefinition.text`
| | | | | **`ObservationDefinition.contained`**| _Equivalent_<br/>(30903/30904)| `ObservationDefinition.contained`| _Equivalent_<br/>(45560/45561)| `ObservationDefinition.contained`
| | | | | **`ObservationDefinition.extension`**| _Equivalent_<br/>(30905/30906)| `ObservationDefinition.extension`| _Equivalent_<br/>(45562/45563)| `ObservationDefinition.extension`
| | | | | **`ObservationDefinition.modifierExtension`**| _Equivalent_<br/>(30907/30908)| `ObservationDefinition.modifierExtension`| _Equivalent_<br/>(45564/45565)| `ObservationDefinition.modifierExtension`
| | | | | **`ObservationDefinition.category`**| _Equivalent_<br/>(30909/30910)| `ObservationDefinition.category`| _Equivalent_<br/>(45566/45567)| `ObservationDefinition.category`
| | | | | **`ObservationDefinition.code`**| _Equivalent_<br/>(30911/30912)| `ObservationDefinition.code`| _Equivalent_<br/>(45568/45569)| `ObservationDefinition.code`
| | | | | **`ObservationDefinition.identifier`**| _Equivalent_<br/>(30913/30914)| `ObservationDefinition.identifier`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(45570)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(45571)| `ObservationDefinition.identifier`
| | | | | **`ObservationDefinition.permittedDataType`**| _Equivalent_<br/>(30915/30916)| `ObservationDefinition.permittedDataType`| _Equivalent_<br/>(45572/45573)| `ObservationDefinition.permittedDataType`
| | | | | **`ObservationDefinition.multipleResultsAllowed`**| _Equivalent_<br/>(30917/30918)| `ObservationDefinition.multipleResultsAllowed`| _Equivalent_<br/>(45574/45575)| `ObservationDefinition.multipleResultsAllowed`
| | | | | **`ObservationDefinition.method`**| _Equivalent_<br/>(30919/30920)| `ObservationDefinition.method`| _Equivalent_<br/>(45576/45577)| `ObservationDefinition.method`
| | | | | **`ObservationDefinition.preferredReportName`**| _Equivalent_<br/>(30921/30922)| `ObservationDefinition.preferredReportName`| _Equivalent_<br/>(45578/45579)| `ObservationDefinition.preferredReportName`
| | | | | **`ObservationDefinition.quantitativeDetails`**| _Equivalent_<br/>(30923/30924)| `ObservationDefinition.quantitativeDetails`| | | 
| | | | | **`ObservationDefinition.quantitativeDetails.id`**| _Equivalent_<br/>(30925/30926)| `ObservationDefinition.quantitativeDetails.id`| | | 
| | | | | **`ObservationDefinition.quantitativeDetails.extension`**| _Equivalent_<br/>(30927/30928)| `ObservationDefinition.quantitativeDetails.extension`| | | 
| | | | | **`ObservationDefinition.quantitativeDetails.modifierExtension`**| _Equivalent_<br/>(30929/30930)| `ObservationDefinition.quantitativeDetails.modifierExtension`| | | 
| | | | | **`ObservationDefinition.quantitativeDetails.customaryUnit`**| _Equivalent_<br/>(30931/30932)| `ObservationDefinition.quantitativeDetails.customaryUnit`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1896)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45584)| `ObservationDefinition`
| | | | | **`ObservationDefinition.quantitativeDetails.unit`**| _Equivalent_<br/>(30933/30934)| `ObservationDefinition.quantitativeDetails.unit`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1897)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45585)| `ObservationDefinition`
| | | | | **`ObservationDefinition.quantitativeDetails.conversionFactor`**| _Equivalent_<br/>(30935/30936)| `ObservationDefinition.quantitativeDetails.conversionFactor`| | | 
| | | | | **`ObservationDefinition.quantitativeDetails.decimalPrecision`**| _Equivalent_<br/>(30937/30938)| `ObservationDefinition.quantitativeDetails.decimalPrecision`| | | 
| | | | | **`ObservationDefinition.qualifiedInterval`**| _Equivalent_<br/>(30939/30940)| `ObservationDefinition.qualifiedInterval`| | | 
| | | | | **`ObservationDefinition.qualifiedInterval.id`**| _Equivalent_<br/>(30941/30942)| `ObservationDefinition.qualifiedInterval.id`| | | 
| | | | | **`ObservationDefinition.qualifiedInterval.extension`**| _Equivalent_<br/>(30943/30944)| `ObservationDefinition.qualifiedInterval.extension`| | | 
| | | | | **`ObservationDefinition.qualifiedInterval.modifierExtension`**| _Equivalent_<br/>(30945/30946)| `ObservationDefinition.qualifiedInterval.modifierExtension`| | | 
| | | | | **`ObservationDefinition.qualifiedInterval.category`**| _Equivalent_<br/>(30947/30948)| `ObservationDefinition.qualifiedInterval.category`| _Equivalent_<br/>(1904/2143)| `ObservationDefinition.qualifiedValue.rangeCategory`
| | | | | **`ObservationDefinition.qualifiedInterval.range`**| _Equivalent_<br/>(30949/30950)| `ObservationDefinition.qualifiedInterval.range`| _Equivalent_<br/>(1905/2144)| `ObservationDefinition.qualifiedValue.range`
| | | | | **`ObservationDefinition.qualifiedInterval.context`**| _Equivalent_<br/>(30951/30952)| `ObservationDefinition.qualifiedInterval.context`| _Equivalent_<br/>(1898/2137)| `ObservationDefinition.qualifiedValue.context`
| | | | | **`ObservationDefinition.qualifiedInterval.appliesTo`**| _Equivalent_<br/>(30953/30954)| `ObservationDefinition.qualifiedInterval.appliesTo`| _Equivalent_<br/>(1899/2138)| `ObservationDefinition.qualifiedValue.appliesTo`
| | | | | **`ObservationDefinition.qualifiedInterval.gender`**| _Equivalent_<br/>(30955/30956)| `ObservationDefinition.qualifiedInterval.gender`| _Equivalent_<br/>(1900/2139)| `ObservationDefinition.qualifiedValue.gender`
| | | | | **`ObservationDefinition.qualifiedInterval.age`**| _Equivalent_<br/>(30957/30958)| `ObservationDefinition.qualifiedInterval.age`| _Equivalent_<br/>(1901/2140)| `ObservationDefinition.qualifiedValue.age`
| | | | | **`ObservationDefinition.qualifiedInterval.gestationalAge`**| _Equivalent_<br/>(30959/30960)| `ObservationDefinition.qualifiedInterval.gestationalAge`| _Equivalent_<br/>(1902/2141)| `ObservationDefinition.qualifiedValue.gestationalAge`
| | | | | **`ObservationDefinition.qualifiedInterval.condition`**| _Equivalent_<br/>(30961/30962)| `ObservationDefinition.qualifiedInterval.condition`| _Equivalent_<br/>(1903/2142)| `ObservationDefinition.qualifiedValue.condition`
| | | | | **`ObservationDefinition.validCodedValueSet`**| _Equivalent_<br/>(30963/30964)| `ObservationDefinition.validCodedValueSet`| | | 
| | | | | **`ObservationDefinition.normalCodedValueSet`**| _Equivalent_<br/>(30965/30966)| `ObservationDefinition.normalCodedValueSet`| | | 
| | | | | **`ObservationDefinition.abnormalCodedValueSet`**| _Equivalent_<br/>(30967/30968)| `ObservationDefinition.abnormalCodedValueSet`| | | 
| | | | | **`ObservationDefinition.criticalCodedValueSet`**| _Equivalent_<br/>(30969/30970)| `ObservationDefinition.criticalCodedValueSet`| | | 
| | | | | *40 of 40 elements used* | | *40 of 40 elements used* | | *24 of 68 elements used* <br/>remaining elements:<br/>`ObservationDefinition.approvalDate`, `ObservationDefinition.bodySite`, `ObservationDefinition.component`, `ObservationDefinition.component.code`, `ObservationDefinition.component.extension`, `ObservationDefinition.component.id`, `ObservationDefinition.component.modifierExtension`, `ObservationDefinition.component.permittedDataType`, `ObservationDefinition.component.permittedUnit`, `ObservationDefinition.component.qualifiedValue`, `ObservationDefinition.contact`, `ObservationDefinition.copyright`, `ObservationDefinition.copyrightLabel`, `ObservationDefinition.date`, `ObservationDefinition.derivedFromCanonical`, `ObservationDefinition.derivedFromUri`, `ObservationDefinition.description`, `ObservationDefinition.device`, `ObservationDefinition.effectivePeriod`, `ObservationDefinition.experimental`, `ObservationDefinition.hasMember`, `ObservationDefinition.jurisdiction`, `ObservationDefinition.lastReviewDate`, `ObservationDefinition.name`, `ObservationDefinition.performerType`, `ObservationDefinition.permittedUnit`, `ObservationDefinition.publisher`, `ObservationDefinition.purpose`, `ObservationDefinition.qualifiedValue`, `ObservationDefinition.qualifiedValue.abnormalCodedValueSet`, `ObservationDefinition.qualifiedValue.criticalCodedValueSet`, `ObservationDefinition.qualifiedValue.extension`, `ObservationDefinition.qualifiedValue.id`, `ObservationDefinition.qualifiedValue.modifierExtension`, `ObservationDefinition.qualifiedValue.normalCodedValueSet`, `ObservationDefinition.qualifiedValue.validCodedValueSet`, `ObservationDefinition.specimen`, `ObservationDefinition.status`, `ObservationDefinition.subject`, `ObservationDefinition.title`, `ObservationDefinition.url`, `ObservationDefinition.useContext`, `ObservationDefinition.version`, `ObservationDefinition.versionAlgorithm[x]`

