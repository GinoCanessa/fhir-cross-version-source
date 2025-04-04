Comparison of 
Generated at Friday, April 4, 2025 2:58:52 PM

### EvidenceClassifier

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | EvidenceClassifier |
| Canonical URL | `http://hl7.org/fhir/ValueSet/evidence-classifier-code` |
| Version | 4.3.0 |
| Description | Commonly used classifiers for evidence sets. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3755` |
| Database Concept Count | `31` |
| Database Active Concept Count | `31` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/EvidenceReport` | `EvidenceReport.section.entryClassifier` | `http://hl7.org/fhir/ValueSet/evidence-classifier-code` | `Extensible` | Extensible classifiers as content |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/evidence-classifier-code`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [EvidenceClassifier](/docs/R4B/ValueSets/EvidenceClassifier.md)<br/> `http://hl7.org/fhir/ValueSet/evidence-classifier-code\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `886`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1147`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EvidenceClassifier](/docs/R5/ValueSets/EvidenceClassifier.md)<br/> `http://hl7.org/fhir/ValueSet/evidence-classifier-code\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set EvidenceClassifier from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B EvidenceClassifier| Relationship | [R5 EvidenceClassifier](/docs/R5/ValueSets/EvidenceClassifier.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://terminology.hl7.org/CodeSystem/evidence-classifier-code`
| | | | | | | **`COVID19Specific`**| _Equivalent_ <br/>(8241/10546)| `COVID19Specific`
| | | | | | | **`COVID19Relevant`**| _Equivalent_ <br/>(8244/10549)| `COVID19Relevant`
| | | | | | | **`COVID19HumanResearch`**| _Equivalent_ <br/>(8236/10541)| `COVID19HumanResearch`
| | | | | | | **`OriginalResearch`**| _Equivalent_ <br/>(8219/10524)| `OriginalResearch`
| | | | | | | **`ResearchSynthesis`**| _Equivalent_ <br/>(8239/10544)| `ResearchSynthesis`
| | | | | | | **`Guideline`**| _Equivalent_ <br/>(8234/10539)| `Guideline`
| | | | | | | **`ResearchProtocol`**| _Equivalent_ <br/>(8237/10542)| `ResearchProtocol`
| | | | | | | **`NotResearchNotGuideline`**| _Equivalent_ <br/>(8233/10538)| `NotResearchNotGuideline`
| | | | | | | **`Treatment`**| _Equivalent_ <br/>(8243/10548)| `Treatment`
| | | | | | | **`PreventionAndControl`**| _Equivalent_ <br/>(8235/10540)| `PreventionAndControl`
| | | | | | | **`Diagnosis`**| _Equivalent_ <br/>(8230/10535)| `Diagnosis`
| | | | | | | **`PrognosisPrediction`**| _Equivalent_ <br/>(8224/10529)| `PrognosisPrediction`
| | | | | | | **`RatedAsYes`**| _Equivalent_ <br/>(8227/10532)| `RatedAsYes`
| | | | | | | **`RatedAsNo`**| _Equivalent_ <br/>(8231/10536)| `RatedAsNo`
| | | | | | | **`NotAssessed`**| _Equivalent_ <br/>(8242/10547)| `NotAssessed`
| | | | | | | **`RatedAsRCT`**| _Equivalent_ <br/>(8225/10530)| `RatedAsRCT`
| | | | | | | **`RatedAsControlledTrial`**| _Equivalent_ <br/>(8238/10543)| `RatedAsControlledTrial`
| | | | | | | **`RatedAsComparativeCohort`**| _Equivalent_ <br/>(8240/10545)| `RatedAsComparativeCohort`
| | | | | | | **`RatedAsCaseControl`**| _Equivalent_ <br/>(8232/10537)| `RatedAsCaseControl`
| | | | | | | **`RatedAsUncontrolledSeries`**| _Equivalent_ <br/>(8222/10527)| `RatedAsUncontrolledSeries`
| | | | | | | **`RatedAsMixedMethods`**| _Equivalent_ <br/>(8220/10525)| `RatedAsMixedMethods`
| | | | | | | **`RatedAsOther`**| _Equivalent_ <br/>(8246/10551)| `RatedAsOther`
| | | | | | | **`RiskOfBias`**| _Equivalent_ <br/>(8247/10552)| `RiskOfBias`
| | | | | | | **`NoBlinding`**| _Equivalent_ <br/>(8223/10528)| `NoBlinding`
| | | | | | | **`AllocConcealNotStated`**| _Equivalent_ <br/>(8249/10554)| `AllocConcealNotStated`
| | | | | | | **`EarlyTrialTermination`**| _Equivalent_ <br/>(8221/10526)| `EarlyTrialTermination`
| | | | | | | **`NoITT`**| _Equivalent_ <br/>(8245/10550)| `NoITT`
| | | | | | | **`Preprint`**| _Equivalent_ <br/>(8228/10533)| `Preprint`
| | | | | | | **`PreliminaryAnalysis`**| _Equivalent_ <br/>(8226/10531)| `PreliminaryAnalysis`
| | | | | | | **`BaselineImbalance`**| _Equivalent_ <br/>(8248/10553)| `BaselineImbalance`
| | | | | | | **`SubgroupAnalysis`**| _Equivalent_ <br/>(8229/10534)| `SubgroupAnalysis`
| | | | | | | *31 of 31 codes used* | | *31 of 31 codes used* 

