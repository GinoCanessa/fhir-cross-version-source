Comparison of 
Generated at Tuesday, April 1, 2025 1:39:35 PM

### StatisticModelCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | StatisticModelCode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/statistic-model-code` |
| Version | 5.0.0 |
| Description | The handling of the variable in statistical analysis for exposures or outcomes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4915` |
| Database Concept Count | `79` |
| Database Active Concept Count | `79` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Evidence` | `Evidence.statistic.modelCharacteristic.code` | `http://hl7.org/fhir/ValueSet/statistic-model-code` | `Extensible` | Model specification |

### Referenced Systems

* `http://hl7.org/fhir/statistic-model-code`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [StatisticModelCode](/docs/R4B/ValueSets/StatisticModelCode.md)<br/> `http://hl7.org/fhir/ValueSet/statistic-model-code\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `881`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1142`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [StatisticModelCode](/docs/R5/ValueSets/StatisticModelCode.md)<br/> `http://hl7.org/fhir/ValueSet/statistic-model-code\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set StatisticModelCode from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B StatisticModelCode](/docs/R4B/ValueSets/StatisticModelCode.md)| Relationship | R5 StatisticModelCode
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/statistic-model-code`
| | | | | | | `oneTailedTest`| _Equivalent_ <br/>(8136/10441)| **`oneTailedTest`**
| | | | | | | `twoTailedTest`| _Equivalent_ <br/>(8126/10431)| **`twoTailedTest`**
| | | | | | | `zTest`| _Equivalent_ <br/>(8167/10472)| **`zTest`**
| | | | | | | `oneSampleTTest`| _Equivalent_ <br/>(8119/10424)| **`oneSampleTTest`**
| | | | | | | `twoSampleTTest`| _Equivalent_ <br/>(8153/10458)| **`twoSampleTTest`**
| | | | | | | `pairedTTest`| _Equivalent_ <br/>(8148/10453)| **`pairedTTest`**
| | | | | | | `chiSquareTest`| _Equivalent_ <br/>(8115/10420)| **`chiSquareTest`**
| | | | | | | `chiSquareTestTrend`| _Equivalent_ <br/>(8100/10405)| **`chiSquareTestTrend`**
| | | | | | | `pearsonCorrelation`| _Equivalent_ <br/>(8144/10449)| **`pearsonCorrelation`**
| | | | | | | `anova`| _Equivalent_ <br/>(8105/10410)| **`anova`**
| | | | | | | `anovaOneWay`| _Equivalent_ <br/>(8156/10461)| **`anovaOneWay`**
| | | | | | | `anovaTwoWay`| _Equivalent_ <br/>(8165/10470)| **`anovaTwoWay`**
| | | | | | | `anovaTwoWayReplication`| _Equivalent_ <br/>(8114/10419)| **`anovaTwoWayReplication`**
| | | | | | | `manova`| _Equivalent_ <br/>(8140/10445)| **`manova`**
| | | | | | | `anovaThreeWay`| _Equivalent_ <br/>(8101/10406)| **`anovaThreeWay`**
| | | | | | | `signTest`| _Equivalent_ <br/>(8154/10459)| **`signTest`**
| | | | | | | `wilcoxonSignedRankTest`| _Equivalent_ <br/>(8159/10464)| **`wilcoxonSignedRankTest`**
| | | | | | | `wilcoxonRankSumTest`| _Equivalent_ <br/>(8139/10444)| **`wilcoxonRankSumTest`**
| | | | | | | `mannWhitneyUTest`| _Equivalent_ <br/>(8178/10483)| **`mannWhitneyUTest`**
| | | | | | | `fishersExactTest`| _Equivalent_ <br/>(8150/10455)| **`fishersExactTest`**
| | | | | | | `mcnemarsTest`| _Equivalent_ <br/>(8108/10413)| **`mcnemarsTest`**
| | | | | | | `kruskalWallisTest`| _Equivalent_ <br/>(8163/10468)| **`kruskalWallisTest`**
| | | | | | | `spearmanCorrelation`| _Equivalent_ <br/>(8103/10408)| **`spearmanCorrelation`**
| | | | | | | `kendallCorrelation`| _Equivalent_ <br/>(8168/10473)| **`kendallCorrelation`**
| | | | | | | `friedmanTest`| _Equivalent_ <br/>(8160/10465)| **`friedmanTest`**
| | | | | | | `goodmanKruskasGamma`| _Equivalent_ <br/>(8135/10440)| **`goodmanKruskasGamma`**
| | | | | | | `glm`| _Equivalent_ <br/>(8122/10427)| **`glm`**
| | | | | | | `glmProbit`| _Equivalent_ <br/>(8104/10409)| **`glmProbit`**
| | | | | | | `glmLogit`| _Equivalent_ <br/>(8132/10437)| **`glmLogit`**
| | | | | | | `glmIdentity`| _Equivalent_ <br/>(8157/10462)| **`glmIdentity`**
| | | | | | | `glmLog`| _Equivalent_ <br/>(8113/10418)| **`glmLog`**
| | | | | | | `glmGeneralizedLogit`| _Equivalent_ <br/>(8169/10474)| **`glmGeneralizedLogit`**
| | | | | | | `glmm`| _Equivalent_ <br/>(8172/10477)| **`glmm`**
| | | | | | | `glmmProbit`| _Equivalent_ <br/>(8129/10434)| **`glmmProbit`**
| | | | | | | `glmmLogit`| _Equivalent_ <br/>(8149/10454)| **`glmmLogit`**
| | | | | | | `glmmIdentity`| _Equivalent_ <br/>(8102/10407)| **`glmmIdentity`**
| | | | | | | `glmmLog`| _Equivalent_ <br/>(8117/10422)| **`glmmLog`**
| | | | | | | `glmmGeneralizedLogit`| _Equivalent_ <br/>(8146/10451)| **`glmmGeneralizedLogit`**
| | | | | | | `linearRegression`| _Equivalent_ <br/>(8166/10471)| **`linearRegression`**
| | | | | | | `logisticRegression`| _Equivalent_ <br/>(8174/10479)| **`logisticRegression`**
| | | | | | | `polynomialRegression`| _Equivalent_ <br/>(8155/10460)| **`polynomialRegression`**
| | | | | | | `coxProportionalHazards`| _Equivalent_ <br/>(8173/10478)| **`coxProportionalHazards`**
| | | | | | | `binomialDistributionRegression`| _Equivalent_ <br/>(8176/10481)| **`binomialDistributionRegression`**
| | | | | | | `multinomialDistributionRegression`| _Equivalent_ <br/>(8123/10428)| **`multinomialDistributionRegression`**
| | | | | | | `poissonRegression`| _Equivalent_ <br/>(8141/10446)| **`poissonRegression`**
| | | | | | | `negativeBinomialRegression`| _Equivalent_ <br/>(8152/10457)| **`negativeBinomialRegression`**
| | | | | | | `zeroCellConstant`| _Equivalent_ <br/>(8147/10452)| **`zeroCellConstant`**
| | | | | | | `zeroCellContinuityCorrection`| _Equivalent_ <br/>(8111/10416)| **`zeroCellContinuityCorrection`**
| | | | | | | `adjusted`| _Equivalent_ <br/>(8121/10426)| **`adjusted`**
| | | | | | | `interactionTerm`| _Equivalent_ <br/>(8161/10466)| **`interactionTerm`**
| | | | | | | `manteHaenszelMethod`| _Equivalent_ <br/>(8142/10447)| **`manteHaenszelMethod`**
| | | | | | | `metaAnalysis`| _Equivalent_ <br/>(8151/10456)| **`metaAnalysis`**
| | | | | | | `inverseVariance`| _Equivalent_ <br/>(8133/10438)| **`inverseVariance`**
| | | | | | | `petoMethod`| _Equivalent_ <br/>(8110/10415)| **`petoMethod`**
| | | | | | | `hartungKnapp`| _Equivalent_ <br/>(8170/10475)| **`hartungKnapp`**
| | | | | | | `modifiedHartungKnapp`| _Equivalent_ <br/>(8171/10476)| **`modifiedHartungKnapp`**
| | | | | | | `effectsFixed`| _Equivalent_ <br/>(8134/10439)| **`effectsFixed`**
| | | | | | | `effectsRandom`| _Equivalent_ <br/>(8109/10414)| **`effectsRandom`**
| | | | | | | `chiSquareTestHomogeneity`| _Equivalent_ <br/>(8120/10425)| **`chiSquareTestHomogeneity`**
| | | | | | | `dersimonianLairdMethod`| _Equivalent_ <br/>(8125/10430)| **`dersimonianLairdMethod`**
| | | | | | | `pauleMandelMethod`| _Equivalent_ <br/>(8143/10448)| **`pauleMandelMethod`**
| | | | | | | `restrictedLikelihood`| _Equivalent_ <br/>(8145/10450)| **`restrictedLikelihood`**
| | | | | | | `maximumLikelihood`| _Equivalent_ <br/>(8162/10467)| **`maximumLikelihood`**
| | | | | | | `empiricalBayes`| _Equivalent_ <br/>(8127/10432)| **`empiricalBayes`**
| | | | | | | `hunterSchmidt`| _Equivalent_ <br/>(8112/10417)| **`hunterSchmidt`**
| | | | | | | `sidikJonkman`| _Equivalent_ <br/>(8175/10480)| **`sidikJonkman`**
| | | | | | | `hedgesMethod`| _Equivalent_ <br/>(8158/10463)| **`hedgesMethod`**
| | | | | | | `tauDersimonianLaird`| _Equivalent_ <br/>(8164/10469)| **`tauDersimonianLaird`**
| | | | | | | `tauPauleMandel`| _Equivalent_ <br/>(8106/10411)| **`tauPauleMandel`**
| | | | | | | `tauRestrictedMaximumLikelihood`| _Equivalent_ <br/>(8118/10423)| **`tauRestrictedMaximumLikelihood`**
| | | | | | | `tauMaximumLikelihood`| _Equivalent_ <br/>(8138/10443)| **`tauMaximumLikelihood`**
| | | | | | | `tauEmpiricalBayes`| _Equivalent_ <br/>(8128/10433)| **`tauEmpiricalBayes`**
| | | | | | | `tauHunterSchmidt`| _Equivalent_ <br/>(8124/10429)| **`tauHunterSchmidt`**
| | | | | | | `tauSidikJonkman`| _Equivalent_ <br/>(8137/10442)| **`tauSidikJonkman`**
| | | | | | | `tauHedges`| _Equivalent_ <br/>(8116/10421)| **`tauHedges`**
| | | | | | | `poolMantelHaenzsel`| _Equivalent_ <br/>(8177/10482)| **`poolMantelHaenzsel`**
| | | | | | | `poolInverseVariance`| _Equivalent_ <br/>(8107/10412)| **`poolInverseVariance`**
| | | | | | | `poolPeto`| _Equivalent_ <br/>(8130/10435)| **`poolPeto`**
| | | | | | | `poolGeneralizedLinearMixedModel`| _Equivalent_ <br/>(8131/10436)| **`poolGeneralizedLinearMixedModel`**
| | | | | | | *79 of 79 codes used* | | *79 of 79 codes used* 

