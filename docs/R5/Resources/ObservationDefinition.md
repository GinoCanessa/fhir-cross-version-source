Comparison of 
Generated at Friday, April 4, 2025 2:59:05 PM

### ObservationDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | ObservationDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ObservationDefinition` |
| Version | 5.0.0 |
| Description | Set of definitional characteristics for a kind of observation or measurement produced or consumed by an orderable health care service. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2352` |
| Database Snapshot Count | `68` |
| Database Differential Count | `54` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ObservationDefinition` | `ObservationDefinition` | `ObservationDefinition` | ObservationDefinition | Definition of an observation | 0..* | ObservationDefinition |  |  |
| `ObservationDefinition.approvalDate` | `ObservationDefinition.approvalDate` | `approvalDate` | ObservationDefinition.approvalDate | When ObservationDefinition was approved by publisher | 0..1 | date |  |  |
| `ObservationDefinition.bodySite` | `ObservationDefinition.bodySite` | `bodySite` | ObservationDefinition.bodySite | Body part to be observed | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `ObservationDefinition.category` | `ObservationDefinition.category` | `category` | ObservationDefinition.category | General type of observation | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/observation-category` |
| `ObservationDefinition.code` | `ObservationDefinition.code` | `code` | ObservationDefinition.code | Type of observation | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/observation-codes` |
| `ObservationDefinition.component` | `ObservationDefinition.component` | `component` | ObservationDefinition.component | Component results | 0..* | BackboneElement |  |  |
| `ObservationDefinition.component.code` | `ObservationDefinition.component.code` | `code` | ObservationDefinition.component.code | Type of observation | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/observation-codes` |
| `ObservationDefinition.component.extension` | `ObservationDefinition.component.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ObservationDefinition.component.id` | `ObservationDefinition.component.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ObservationDefinition.component.modifierExtension` | `ObservationDefinition.component.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ObservationDefinition.component.permittedDataType` | `ObservationDefinition.component.permittedDataType` | `permittedDataType` | ObservationDefinition.component.permittedDataType | Quantity \| CodeableConcept \| string \| boolean \| integer \| Range \| Ratio \| SampledData \| time \| dateTime \| Period | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/permitted-data-type|5.0.0` |
| `ObservationDefinition.component.permittedUnit` | `ObservationDefinition.component.permittedUnit` | `permittedUnit` | ObservationDefinition.component.permittedUnit | Unit for quantitative results | 0..* | Coding | `Preferred` | `http://hl7.org/fhir/ValueSet/ucum-units` |
| `ObservationDefinition.component.qualifiedValue` | `ObservationDefinition.component.qualifiedValue` | `qualifiedValue` | ObservationDefinition.component.qualifiedValue | Set of qualified values for observation results | 0..* | ObservationDefinition.qualifiedValue |  |  |
| `ObservationDefinition.contact` | `ObservationDefinition.contact` | `contact` | ObservationDefinition.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `ObservationDefinition.contained` | `ObservationDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ObservationDefinition.copyright` | `ObservationDefinition.copyright` | `copyright` | ObservationDefinition.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `ObservationDefinition.copyrightLabel` | `ObservationDefinition.copyrightLabel` | `copyrightLabel` | ObservationDefinition.copyrightLabel | Copyright holder and year(s) | 0..1 | string |  |  |
| `ObservationDefinition.date` | `ObservationDefinition.date` | `date` | ObservationDefinition.date | Date last changed | 0..1 | dateTime |  |  |
| `ObservationDefinition.derivedFromCanonical` | `ObservationDefinition.derivedFromCanonical` | `derivedFromCanonical` | ObservationDefinition.derivedFromCanonical | Based on FHIR definition of another observation | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/ObservationDefinition) |  |  |
| `ObservationDefinition.derivedFromUri` | `ObservationDefinition.derivedFromUri` | `derivedFromUri` | ObservationDefinition.derivedFromUri | Based on external definition | 0..* | uri |  |  |
| `ObservationDefinition.description` | `ObservationDefinition.description` | `description` | ObservationDefinition.description | Natural language description of the ObservationDefinition | 0..1 | markdown |  |  |
| `ObservationDefinition.device` | `ObservationDefinition.device` | `device` | ObservationDefinition.device | Measurement device or model of device | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition) |  |  |
| `ObservationDefinition.effectivePeriod` | `ObservationDefinition.effectivePeriod` | `effectivePeriod` | ObservationDefinition.effectivePeriod | The effective date range for the ObservationDefinition | 0..1 | Period |  |  |
| `ObservationDefinition.experimental` | `ObservationDefinition.experimental` | `experimental` | ObservationDefinition.experimental | If for testing purposes, not real usage | 0..1 | boolean |  |  |
| `ObservationDefinition.extension` | `ObservationDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ObservationDefinition.hasMember` | `ObservationDefinition.hasMember` | `hasMember` | ObservationDefinition.hasMember | Definitions of related resources belonging to this kind of observation group | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ObservationDefinition), Reference(http://hl7.org/fhir/StructureDefinition/Questionnaire) |  |  |
| `ObservationDefinition.id` | `ObservationDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ObservationDefinition.identifier` | `ObservationDefinition.identifier` | `identifier` | ObservationDefinition.identifier | Business identifier of the ObservationDefinition | 0..1 | Identifier |  |  |
| `ObservationDefinition.implicitRules` | `ObservationDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ObservationDefinition.jurisdiction` | `ObservationDefinition.jurisdiction` | `jurisdiction` | ObservationDefinition.jurisdiction | Intended jurisdiction for this ObservationDefinition (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `ObservationDefinition.language` | `ObservationDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `ObservationDefinition.lastReviewDate` | `ObservationDefinition.lastReviewDate` | `lastReviewDate` | ObservationDefinition.lastReviewDate | Date on which the asset content was last reviewed by the publisher | 0..1 | date |  |  |
| `ObservationDefinition.meta` | `ObservationDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ObservationDefinition.method` | `ObservationDefinition.method` | `method` | ObservationDefinition.method | Method used to produce the observation | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/observation-methods` |
| `ObservationDefinition.modifierExtension` | `ObservationDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ObservationDefinition.multipleResultsAllowed` | `ObservationDefinition.multipleResultsAllowed` | `multipleResultsAllowed` | ObservationDefinition.multipleResultsAllowed | Multiple results allowed for conforming observations | 0..1 | boolean |  |  |
| `ObservationDefinition.name` | `ObservationDefinition.name` | `name` | ObservationDefinition.name | Name for this ObservationDefinition (computer friendly) | 0..1 | string |  |  |
| `ObservationDefinition.performerType` | `ObservationDefinition.performerType` | `performerType` | ObservationDefinition.performerType | Desired kind of performer for such kind of observation | 0..1 | CodeableConcept |  |  |
| `ObservationDefinition.permittedDataType` | `ObservationDefinition.permittedDataType` | `permittedDataType` | ObservationDefinition.permittedDataType | Quantity \| CodeableConcept \| string \| boolean \| integer \| Range \| Ratio \| SampledData \| time \| dateTime \| Period | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/permitted-data-type|5.0.0` |
| `ObservationDefinition.permittedUnit` | `ObservationDefinition.permittedUnit` | `permittedUnit` | ObservationDefinition.permittedUnit | Unit for quantitative results | 0..* | Coding | `Preferred` | `http://hl7.org/fhir/ValueSet/ucum-units` |
| `ObservationDefinition.preferredReportName` | `ObservationDefinition.preferredReportName` | `preferredReportName` | ObservationDefinition.preferredReportName | The preferred name to be used when reporting the observation results | 0..1 | string |  |  |
| `ObservationDefinition.publisher` | `ObservationDefinition.publisher` | `publisher` | ObservationDefinition.publisher | The name of the individual or organization that published the ObservationDefinition | 0..1 | string |  |  |
| `ObservationDefinition.purpose` | `ObservationDefinition.purpose` | `purpose` | ObservationDefinition.purpose | Why this ObservationDefinition is defined | 0..1 | markdown |  |  |
| `ObservationDefinition.qualifiedValue` | `ObservationDefinition.qualifiedValue` | `qualifiedValue` | ObservationDefinition.qualifiedValue | Set of qualified values for observation results | 0..* | BackboneElement |  |  |
| `ObservationDefinition.qualifiedValue.abnormalCodedValueSet` | `ObservationDefinition.qualifiedValue.abnormalCodedValueSet` | `abnormalCodedValueSet` | ObservationDefinition.qualifiedValue.abnormalCodedValueSet | Value set of abnormal coded values as part of this set of qualified values | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/ValueSet) |  |  |
| `ObservationDefinition.qualifiedValue.age` | `ObservationDefinition.qualifiedValue.age` | `age` | ObservationDefinition.qualifiedValue.age | Applicable age range for the set of qualified values | 0..1 | Range |  |  |
| `ObservationDefinition.qualifiedValue.appliesTo` | `ObservationDefinition.qualifiedValue.appliesTo` | `appliesTo` | ObservationDefinition.qualifiedValue.appliesTo | Targetted population for the set of qualified values | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/referencerange-appliesto` |
| `ObservationDefinition.qualifiedValue.condition` | `ObservationDefinition.qualifiedValue.condition` | `condition` | ObservationDefinition.qualifiedValue.condition | Condition associated with the set of qualified values | 0..1 | string |  |  |
| `ObservationDefinition.qualifiedValue.context` | `ObservationDefinition.qualifiedValue.context` | `context` | ObservationDefinition.qualifiedValue.context | Context qualifier for the set of qualified values | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/referencerange-meaning` |
| `ObservationDefinition.qualifiedValue.criticalCodedValueSet` | `ObservationDefinition.qualifiedValue.criticalCodedValueSet` | `criticalCodedValueSet` | ObservationDefinition.qualifiedValue.criticalCodedValueSet | Value set of critical coded values as part of this set of qualified values | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/ValueSet) |  |  |
| `ObservationDefinition.qualifiedValue.extension` | `ObservationDefinition.qualifiedValue.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ObservationDefinition.qualifiedValue.gender` | `ObservationDefinition.qualifiedValue.gender` | `gender` | ObservationDefinition.qualifiedValue.gender | male \| female \| other \| unknown | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/administrative-gender|5.0.0` |
| `ObservationDefinition.qualifiedValue.gestationalAge` | `ObservationDefinition.qualifiedValue.gestationalAge` | `gestationalAge` | ObservationDefinition.qualifiedValue.gestationalAge | Applicable gestational age range for the set of qualified values | 0..1 | Range |  |  |
| `ObservationDefinition.qualifiedValue.id` | `ObservationDefinition.qualifiedValue.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ObservationDefinition.qualifiedValue.modifierExtension` | `ObservationDefinition.qualifiedValue.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ObservationDefinition.qualifiedValue.normalCodedValueSet` | `ObservationDefinition.qualifiedValue.normalCodedValueSet` | `normalCodedValueSet` | ObservationDefinition.qualifiedValue.normalCodedValueSet | Value set of normal coded values as part of this set of qualified values | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/ValueSet) |  |  |
| `ObservationDefinition.qualifiedValue.range` | `ObservationDefinition.qualifiedValue.range` | `range` | ObservationDefinition.qualifiedValue.range | The range for continuous or ordinal observations | 0..1 | Range |  |  |
| `ObservationDefinition.qualifiedValue.rangeCategory` | `ObservationDefinition.qualifiedValue.rangeCategory` | `rangeCategory` | ObservationDefinition.qualifiedValue.rangeCategory | reference \| critical \| absolute | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/observation-range-category|5.0.0` |
| `ObservationDefinition.qualifiedValue.validCodedValueSet` | `ObservationDefinition.qualifiedValue.validCodedValueSet` | `validCodedValueSet` | ObservationDefinition.qualifiedValue.validCodedValueSet | Value set of valid coded values as part of this set of qualified values | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/ValueSet) |  |  |
| `ObservationDefinition.specimen` | `ObservationDefinition.specimen` | `specimen` | ObservationDefinition.specimen | Kind of specimen used by this type of observation | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/SpecimenDefinition) |  |  |
| `ObservationDefinition.status` | `ObservationDefinition.status` | `status` | ObservationDefinition.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `ObservationDefinition.subject` | `ObservationDefinition.subject` | `subject` | ObservationDefinition.subject | Type of subject for the defined observation | 0..* | CodeableConcept |  |  |
| `ObservationDefinition.text` | `ObservationDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ObservationDefinition.title` | `ObservationDefinition.title` | `title` | ObservationDefinition.title | Name for this ObservationDefinition (human friendly) | 0..1 | string |  |  |
| `ObservationDefinition.url` | `ObservationDefinition.url` | `url` | ObservationDefinition.url | Logical canonical URL to reference this ObservationDefinition (globally unique) | 0..1 | uri |  |  |
| `ObservationDefinition.useContext` | `ObservationDefinition.useContext` | `useContext` | ObservationDefinition.useContext | Content intends to support these contexts | 0..* | UsageContext |  |  |
| `ObservationDefinition.version` | `ObservationDefinition.version` | `version` | ObservationDefinition.version | Business version of the ObservationDefinition | 0..1 | string |  |  |
| `ObservationDefinition.versionAlgorithm[x]` | `ObservationDefinition.versionAlgorithm[x]` | `versionAlgorithm[x]` | ObservationDefinition.versionAlgorithm[x] | How to compare versions | 0..1 | Coding, string | `Extensible` | `http://hl7.org/fhir/ValueSet/version-algorithm` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [ObservationDefinition](/docs/R4/Resources/ObservationDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ObservationDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1559`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1560`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ObservationDefinition](/docs/R4B/Resources/ObservationDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ObservationDefinition\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1290`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ObservationDefinition](/docs/R5/Resources/ObservationDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ObservationDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ObservationDefinition from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 ObservationDefinition](/docs/R4/Resources/ObservationDefinition.md)| Relationship | [R4B ObservationDefinition](/docs/R4B/Resources/ObservationDefinition.md)| Relationship | R5 ObservationDefinition
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `ObservationDefinition`| _Equivalent_<br/>(30891/30892)| `ObservationDefinition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(45548)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45585)| **`ObservationDefinition`**
| | | | | `ObservationDefinition.quantitativeDetails.customaryUnit`| _Equivalent_<br/>(30931/30932)| `ObservationDefinition.quantitativeDetails.customaryUnit`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1896)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45585)| **`ObservationDefinition`**
| | | | | `ObservationDefinition.quantitativeDetails.unit`| _Equivalent_<br/>(30933/30934)| `ObservationDefinition.quantitativeDetails.unit`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1897)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45585)| **`ObservationDefinition`**
| | | | | `ObservationDefinition.id`| _Equivalent_<br/>(30893/30894)| `ObservationDefinition.id`| _Equivalent_<br/>(45550/45551)| **`ObservationDefinition.id`**
| | | | | `ObservationDefinition.meta`| _Equivalent_<br/>(30895/30896)| `ObservationDefinition.meta`| _Equivalent_<br/>(45552/45553)| **`ObservationDefinition.meta`**
| | | | | `ObservationDefinition.implicitRules`| _Equivalent_<br/>(30897/30898)| `ObservationDefinition.implicitRules`| _Equivalent_<br/>(45554/45555)| **`ObservationDefinition.implicitRules`**
| | | | | `ObservationDefinition.language`| _Equivalent_<br/>(30899/30900)| `ObservationDefinition.language`| _Equivalent_<br/>(45556/45557)| **`ObservationDefinition.language`**
| | | | | `ObservationDefinition.text`| _Equivalent_<br/>(30901/30902)| `ObservationDefinition.text`| _Equivalent_<br/>(45558/45559)| **`ObservationDefinition.text`**
| | | | | `ObservationDefinition.contained`| _Equivalent_<br/>(30903/30904)| `ObservationDefinition.contained`| _Equivalent_<br/>(45560/45561)| **`ObservationDefinition.contained`**
| | | | | `ObservationDefinition.extension`| _Equivalent_<br/>(30905/30906)| `ObservationDefinition.extension`| _Equivalent_<br/>(45562/45563)| **`ObservationDefinition.extension`**
| | | | | `ObservationDefinition.modifierExtension`| _Equivalent_<br/>(30907/30908)| `ObservationDefinition.modifierExtension`| _Equivalent_<br/>(45564/45565)| **`ObservationDefinition.modifierExtension`**
| | | | | | | | | **`ObservationDefinition.url`**
| | | | | `ObservationDefinition.identifier`| _Equivalent_<br/>(30913/30914)| `ObservationDefinition.identifier`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(45570)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(45571)| **`ObservationDefinition.identifier`**
| | | | | | | | | **`ObservationDefinition.version`**
| | | | | | | | | **`ObservationDefinition.versionAlgorithm[x]`**
| | | | | | | | | **`ObservationDefinition.name`**
| | | | | | | | | **`ObservationDefinition.title`**
| | | | | | | | | **`ObservationDefinition.status`**
| | | | | | | | | **`ObservationDefinition.experimental`**
| | | | | | | | | **`ObservationDefinition.date`**
| | | | | | | | | **`ObservationDefinition.publisher`**
| | | | | | | | | **`ObservationDefinition.contact`**
| | | | | | | | | **`ObservationDefinition.description`**
| | | | | | | | | **`ObservationDefinition.useContext`**
| | | | | | | | | **`ObservationDefinition.jurisdiction`**
| | | | | | | | | **`ObservationDefinition.purpose`**
| | | | | | | | | **`ObservationDefinition.copyright`**
| | | | | | | | | **`ObservationDefinition.copyrightLabel`**
| | | | | | | | | **`ObservationDefinition.approvalDate`**
| | | | | | | | | **`ObservationDefinition.lastReviewDate`**
| | | | | | | | | **`ObservationDefinition.effectivePeriod`**
| | | | | | | | | **`ObservationDefinition.derivedFromCanonical`**
| | | | | | | | | **`ObservationDefinition.derivedFromUri`**
| | | | | | | | | **`ObservationDefinition.subject`**
| | | | | | | | | **`ObservationDefinition.performerType`**
| | | | | `ObservationDefinition.category`| _Equivalent_<br/>(30909/30910)| `ObservationDefinition.category`| _Equivalent_<br/>(45566/45567)| **`ObservationDefinition.category`**
| | | | | `ObservationDefinition.code`| _Equivalent_<br/>(30911/30912)| `ObservationDefinition.code`| _Equivalent_<br/>(45568/45569)| **`ObservationDefinition.code`**
| | | | | `ObservationDefinition.permittedDataType`| _Equivalent_<br/>(30915/30916)| `ObservationDefinition.permittedDataType`| _Equivalent_<br/>(45572/45573)| **`ObservationDefinition.permittedDataType`**
| | | | | `ObservationDefinition.multipleResultsAllowed`| _Equivalent_<br/>(30917/30918)| `ObservationDefinition.multipleResultsAllowed`| _Equivalent_<br/>(45574/45575)| **`ObservationDefinition.multipleResultsAllowed`**
| | | | | | | | | **`ObservationDefinition.bodySite`**
| | | | | `ObservationDefinition.method`| _Equivalent_<br/>(30919/30920)| `ObservationDefinition.method`| _Equivalent_<br/>(45576/45577)| **`ObservationDefinition.method`**
| | | | | | | | | **`ObservationDefinition.specimen`**
| | | | | | | | | **`ObservationDefinition.device`**
| | | | | `ObservationDefinition.preferredReportName`| _Equivalent_<br/>(30921/30922)| `ObservationDefinition.preferredReportName`| _Equivalent_<br/>(45578/45579)| **`ObservationDefinition.preferredReportName`**
| | | | | | | | | **`ObservationDefinition.permittedUnit`**
| | | | | | | | | **`ObservationDefinition.qualifiedValue`**
| | | | | | | | | **`ObservationDefinition.qualifiedValue.id`**
| | | | | | | | | **`ObservationDefinition.qualifiedValue.extension`**
| | | | | | | | | **`ObservationDefinition.qualifiedValue.modifierExtension`**
| | | | | `ObservationDefinition.qualifiedInterval.context`| _Equivalent_<br/>(30951/30952)| `ObservationDefinition.qualifiedInterval.context`| _Equivalent_<br/>(1898/2137)| **`ObservationDefinition.qualifiedValue.context`**
| | | | | `ObservationDefinition.qualifiedInterval.appliesTo`| _Equivalent_<br/>(30953/30954)| `ObservationDefinition.qualifiedInterval.appliesTo`| _Equivalent_<br/>(1899/2138)| **`ObservationDefinition.qualifiedValue.appliesTo`**
| | | | | `ObservationDefinition.qualifiedInterval.gender`| _Equivalent_<br/>(30955/30956)| `ObservationDefinition.qualifiedInterval.gender`| _Equivalent_<br/>(1900/2139)| **`ObservationDefinition.qualifiedValue.gender`**
| | | | | `ObservationDefinition.qualifiedInterval.age`| _Equivalent_<br/>(30957/30958)| `ObservationDefinition.qualifiedInterval.age`| _Equivalent_<br/>(1901/2140)| **`ObservationDefinition.qualifiedValue.age`**
| | | | | `ObservationDefinition.qualifiedInterval.gestationalAge`| _Equivalent_<br/>(30959/30960)| `ObservationDefinition.qualifiedInterval.gestationalAge`| _Equivalent_<br/>(1902/2141)| **`ObservationDefinition.qualifiedValue.gestationalAge`**
| | | | | `ObservationDefinition.qualifiedInterval.condition`| _Equivalent_<br/>(30961/30962)| `ObservationDefinition.qualifiedInterval.condition`| _Equivalent_<br/>(1903/2142)| **`ObservationDefinition.qualifiedValue.condition`**
| | | | | `ObservationDefinition.qualifiedInterval.category`| _Equivalent_<br/>(30947/30948)| `ObservationDefinition.qualifiedInterval.category`| _Equivalent_<br/>(1904/2143)| **`ObservationDefinition.qualifiedValue.rangeCategory`**
| | | | | `ObservationDefinition.qualifiedInterval.range`| _Equivalent_<br/>(30949/30950)| `ObservationDefinition.qualifiedInterval.range`| _Equivalent_<br/>(1905/2144)| **`ObservationDefinition.qualifiedValue.range`**
| | | | | | | | | **`ObservationDefinition.qualifiedValue.validCodedValueSet`**
| | | | | | | | | **`ObservationDefinition.qualifiedValue.normalCodedValueSet`**
| | | | | | | | | **`ObservationDefinition.qualifiedValue.abnormalCodedValueSet`**
| | | | | | | | | **`ObservationDefinition.qualifiedValue.criticalCodedValueSet`**
| | | | | | | | | **`ObservationDefinition.hasMember`**
| | | | | | | | | **`ObservationDefinition.component`**
| | | | | | | | | **`ObservationDefinition.component.id`**
| | | | | | | | | **`ObservationDefinition.component.extension`**
| | | | | | | | | **`ObservationDefinition.component.modifierExtension`**
| | | | | | | | | **`ObservationDefinition.component.code`**
| | | | | | | | | **`ObservationDefinition.component.permittedDataType`**
| | | | | | | | | **`ObservationDefinition.component.permittedUnit`**
| | | | | | | | | **`ObservationDefinition.component.qualifiedValue`**
| | | | | *26 of 40 elements used* <br/>remaining elements:<br/>`ObservationDefinition.abnormalCodedValueSet`, `ObservationDefinition.criticalCodedValueSet`, `ObservationDefinition.normalCodedValueSet`, `ObservationDefinition.qualifiedInterval`, `ObservationDefinition.qualifiedInterval.extension`, `ObservationDefinition.qualifiedInterval.id`, `ObservationDefinition.qualifiedInterval.modifierExtension`, `ObservationDefinition.quantitativeDetails`, `ObservationDefinition.quantitativeDetails.conversionFactor`, `ObservationDefinition.quantitativeDetails.decimalPrecision`, `ObservationDefinition.quantitativeDetails.extension`, `ObservationDefinition.quantitativeDetails.id`, `ObservationDefinition.quantitativeDetails.modifierExtension`, `ObservationDefinition.validCodedValueSet`| | *26 of 40 elements used* <br/>remaining elements:<br/>`ObservationDefinition.abnormalCodedValueSet`, `ObservationDefinition.criticalCodedValueSet`, `ObservationDefinition.normalCodedValueSet`, `ObservationDefinition.qualifiedInterval`, `ObservationDefinition.qualifiedInterval.extension`, `ObservationDefinition.qualifiedInterval.id`, `ObservationDefinition.qualifiedInterval.modifierExtension`, `ObservationDefinition.quantitativeDetails`, `ObservationDefinition.quantitativeDetails.conversionFactor`, `ObservationDefinition.quantitativeDetails.decimalPrecision`, `ObservationDefinition.quantitativeDetails.extension`, `ObservationDefinition.quantitativeDetails.id`, `ObservationDefinition.quantitativeDetails.modifierExtension`, `ObservationDefinition.validCodedValueSet`| | *68 of 68 elements used* 

