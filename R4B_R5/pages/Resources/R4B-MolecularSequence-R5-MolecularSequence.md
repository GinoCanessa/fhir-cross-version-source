Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MolecularSequence |  | Raw data describing a biological sequence. | 101 | 69 |
| Target | MolecularSequence |  | Representation of a molecular sequence. | 44 | 27 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 87 |
Equivalent | 4 |
RelatedTo | 10 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MolecularSequence | MolecularSequence | Equivalent | R4B `MolecularSequence` maps as Equivalent to R5 `MolecularSequence` |
| MolecularSequence.contained | MolecularSequence.contained | Equivalent | R4B `MolecularSequence.contained` maps as Equivalent to R5 `MolecularSequence.contained` |
| MolecularSequence.coordinateSystem | - | DoesNotExistInTarget | R4B `MolecularSequence.coordinateSystem` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.device | MolecularSequence.device | Equivalent | R4B `MolecularSequence.device` maps as Equivalent to R5 `MolecularSequence.device` |
| MolecularSequence.extension | MolecularSequence.extension | RelatedTo | R4B `MolecularSequence.extension` maps as RelatedTo to R5 `MolecularSequence.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MolecularSequence.id | MolecularSequence.id | Equivalent | R4B `MolecularSequence.id` maps as Equivalent to R5 `MolecularSequence.id` |
| MolecularSequence.identifier | MolecularSequence.identifier | Equivalent | R4B `MolecularSequence.identifier` maps as Equivalent to R5 `MolecularSequence.identifier` |
| MolecularSequence.implicitRules | MolecularSequence.implicitRules | Equivalent | R4B `MolecularSequence.implicitRules` maps as Equivalent to R5 `MolecularSequence.implicitRules` |
| MolecularSequence.language | MolecularSequence.language | RelatedTo | R4B `MolecularSequence.language` maps as RelatedTo to R5 `MolecularSequence.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| MolecularSequence.meta | MolecularSequence.meta | Equivalent | R4B `MolecularSequence.meta` maps as Equivalent to R5 `MolecularSequence.meta` |
| MolecularSequence.modifierExtension | MolecularSequence.modifierExtension | RelatedTo | R4B `MolecularSequence.modifierExtension` maps as RelatedTo to R5 `MolecularSequence.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MolecularSequence.observedSeq | - | DoesNotExistInTarget | R4B `MolecularSequence.observedSeq` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.patient | - | DoesNotExistInTarget | R4B `MolecularSequence.patient` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.performer | MolecularSequence.performer | Equivalent | R4B `MolecularSequence.performer` maps as Equivalent to R5 `MolecularSequence.performer` |
| MolecularSequence.pointer | - | DoesNotExistInTarget | R4B `MolecularSequence.pointer` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality | - | DoesNotExistInTarget | R4B `MolecularSequence.quality` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.end | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.end` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.extension | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.extension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.fScore | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.fScore` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.gtFP | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.gtFP` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.id | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.id` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.method | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.method` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.modifierExtension | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.modifierExtension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.precision | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.precision` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.queryFP | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.queryFP` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.queryTP | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.queryTP` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.recall | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.recall` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.roc | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.roc` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.roc.extension | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.roc.extension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.roc.fMeasure | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.roc.fMeasure` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.roc.id | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.roc.id` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.roc.modifierExtension | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.roc.modifierExtension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.roc.numFN | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.roc.numFN` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.roc.numFP | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.roc.numFP` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.roc.numTP | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.roc.numTP` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.roc.precision | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.roc.precision` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.roc.score | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.roc.score` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.roc.sensitivity | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.roc.sensitivity` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.score | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.score` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.standardSequence | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.standardSequence` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.start | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.start` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.truthFN | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.truthFN` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.truthTP | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.truthTP` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quality.type | - | DoesNotExistInTarget | R4B `MolecularSequence.quality.type` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.quantity | - | DoesNotExistInTarget | R4B `MolecularSequence.quantity` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.readCoverage | - | DoesNotExistInTarget | R4B `MolecularSequence.readCoverage` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.referenceSeq | - | DoesNotExistInTarget | R4B `MolecularSequence.referenceSeq` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.referenceSeq.chromosome | - | DoesNotExistInTarget | R4B `MolecularSequence.referenceSeq.chromosome` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.referenceSeq.extension | - | DoesNotExistInTarget | R4B `MolecularSequence.referenceSeq.extension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.referenceSeq.genomeBuild | - | DoesNotExistInTarget | R4B `MolecularSequence.referenceSeq.genomeBuild` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.referenceSeq.id | - | DoesNotExistInTarget | R4B `MolecularSequence.referenceSeq.id` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.referenceSeq.modifierExtension | - | DoesNotExistInTarget | R4B `MolecularSequence.referenceSeq.modifierExtension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.referenceSeq.orientation | - | DoesNotExistInTarget | R4B `MolecularSequence.referenceSeq.orientation` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.referenceSeq.referenceSeqId | - | DoesNotExistInTarget | R4B `MolecularSequence.referenceSeq.referenceSeqId` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.referenceSeq.referenceSeqPointer | - | DoesNotExistInTarget | R4B `MolecularSequence.referenceSeq.referenceSeqPointer` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.referenceSeq.referenceSeqString | - | DoesNotExistInTarget | R4B `MolecularSequence.referenceSeq.referenceSeqString` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.referenceSeq.strand | - | DoesNotExistInTarget | R4B `MolecularSequence.referenceSeq.strand` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.referenceSeq.windowEnd | - | DoesNotExistInTarget | R4B `MolecularSequence.referenceSeq.windowEnd` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.referenceSeq.windowStart | - | DoesNotExistInTarget | R4B `MolecularSequence.referenceSeq.windowStart` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.repository | - | DoesNotExistInTarget | R4B `MolecularSequence.repository` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.repository.datasetId | - | DoesNotExistInTarget | R4B `MolecularSequence.repository.datasetId` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.repository.extension | - | DoesNotExistInTarget | R4B `MolecularSequence.repository.extension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.repository.id | - | DoesNotExistInTarget | R4B `MolecularSequence.repository.id` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.repository.modifierExtension | - | DoesNotExistInTarget | R4B `MolecularSequence.repository.modifierExtension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.repository.name | - | DoesNotExistInTarget | R4B `MolecularSequence.repository.name` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.repository.readsetId | - | DoesNotExistInTarget | R4B `MolecularSequence.repository.readsetId` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.repository.type | - | DoesNotExistInTarget | R4B `MolecularSequence.repository.type` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.repository.url | - | DoesNotExistInTarget | R4B `MolecularSequence.repository.url` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.repository.variantsetId | - | DoesNotExistInTarget | R4B `MolecularSequence.repository.variantsetId` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.specimen | MolecularSequence.specimen | Equivalent | R4B `MolecularSequence.specimen` maps as Equivalent to R5 `MolecularSequence.specimen` |
| MolecularSequence.structureVariant | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.exact | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.exact` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.extension | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.extension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.id | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.id` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.inner | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.inner` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.inner.end | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.inner.end` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.inner.extension | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.inner.extension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.inner.id | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.inner.id` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.inner.modifierExtension | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.inner.modifierExtension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.inner.start | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.inner.start` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.length | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.length` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.modifierExtension | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.modifierExtension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.outer | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.outer` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.outer.end | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.outer.end` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.outer.extension | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.outer.extension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.outer.id | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.outer.id` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.outer.modifierExtension | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.outer.modifierExtension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.outer.start | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.outer.start` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.structureVariant.variantType | - | DoesNotExistInTarget | R4B `MolecularSequence.structureVariant.variantType` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.text | MolecularSequence.text | Equivalent | R4B `MolecularSequence.text` maps as Equivalent to R5 `MolecularSequence.text` |
| MolecularSequence.type | MolecularSequence.type | Equivalent | R4B `MolecularSequence.type` maps as Equivalent to R5 `MolecularSequence.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/sequence-type|4.3.0 and http://hl7.org/fhir/ValueSet/sequence-type|5.0.0 (Equivalent) |
| MolecularSequence.variant | - | DoesNotExistInTarget | R4B `MolecularSequence.variant` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.variant.cigar | - | DoesNotExistInTarget | R4B `MolecularSequence.variant.cigar` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.variant.end | - | DoesNotExistInTarget | R4B `MolecularSequence.variant.end` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.variant.extension | - | DoesNotExistInTarget | R4B `MolecularSequence.variant.extension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.variant.id | - | DoesNotExistInTarget | R4B `MolecularSequence.variant.id` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.variant.modifierExtension | - | DoesNotExistInTarget | R4B `MolecularSequence.variant.modifierExtension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.variant.observedAllele | - | DoesNotExistInTarget | R4B `MolecularSequence.variant.observedAllele` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.variant.referenceAllele | - | DoesNotExistInTarget | R4B `MolecularSequence.variant.referenceAllele` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.variant.start | - | DoesNotExistInTarget | R4B `MolecularSequence.variant.start` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.variant.variantPointer | - | DoesNotExistInTarget | R4B `MolecularSequence.variant.variantPointer` does not appear in the target and has no mapping for `MolecularSequence`. |

