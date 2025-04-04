Comparison of 
Generated at Friday, April 4, 2025 2:58:46 PM

### MolecularSequence

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | MolecularSequence |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MolecularSequence` |
| Version | 4.0.1 |
| Description | Raw data describing a biological sequence. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1124` |
| Database Snapshot Count | `101` |
| Database Differential Count | `69` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MolecularSequence` | `MolecularSequence` | `MolecularSequence` | MolecularSequence | Information about a biological sequence | 0..* | MolecularSequence |  |  |
| `MolecularSequence.contained` | `MolecularSequence.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MolecularSequence.coordinateSystem` | `MolecularSequence.coordinateSystem` | `coordinateSystem` | MolecularSequence.coordinateSystem | Base number of coordinate system (0 for 0-based numbering or coordinates, inclusive start, exclusive end, 1 for 1-based numbering, inclusive start, inclusive end) | 1..1 | integer |  |  |
| `MolecularSequence.device` | `MolecularSequence.device` | `device` | MolecularSequence.device | The method for sequencing | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device) |  |  |
| `MolecularSequence.extension` | `MolecularSequence.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MolecularSequence.id` | `MolecularSequence.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MolecularSequence.identifier` | `MolecularSequence.identifier` | `identifier` | MolecularSequence.identifier | Unique ID for this particular sequence. This is a FHIR-defined id | 0..* | Identifier |  |  |
| `MolecularSequence.implicitRules` | `MolecularSequence.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MolecularSequence.language` | `MolecularSequence.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `MolecularSequence.meta` | `MolecularSequence.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MolecularSequence.modifierExtension` | `MolecularSequence.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MolecularSequence.observedSeq` | `MolecularSequence.observedSeq` | `observedSeq` | MolecularSequence.observedSeq | Sequence that was observed | 0..1 | string |  |  |
| `MolecularSequence.patient` | `MolecularSequence.patient` | `patient` | MolecularSequence.patient | Who and/or what this is about | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `MolecularSequence.performer` | `MolecularSequence.performer` | `performer` | MolecularSequence.performer | Who should be responsible for test result | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `MolecularSequence.pointer` | `MolecularSequence.pointer` | `pointer` | MolecularSequence.pointer | Pointer to next atomic sequence | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/MolecularSequence) |  |  |
| `MolecularSequence.quality` | `MolecularSequence.quality` | `quality` | MolecularSequence.quality | An set of value as quality of sequence | 0..* | BackboneElement |  |  |
| `MolecularSequence.quality.end` | `MolecularSequence.quality.end` | `end` | MolecularSequence.quality.end | End position of the sequence | 0..1 | integer |  |  |
| `MolecularSequence.quality.extension` | `MolecularSequence.quality.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MolecularSequence.quality.fScore` | `MolecularSequence.quality.fScore` | `fScore` | MolecularSequence.quality.fScore | F-score | 0..1 | decimal |  |  |
| `MolecularSequence.quality.gtFP` | `MolecularSequence.quality.gtFP` | `gtFP` | MolecularSequence.quality.gtFP | False positives where the non-REF alleles in the Truth and Query Call Sets match | 0..1 | decimal |  |  |
| `MolecularSequence.quality.id` | `MolecularSequence.quality.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MolecularSequence.quality.method` | `MolecularSequence.quality.method` | `method` | MolecularSequence.quality.method | Method to get quality | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/sequence-quality-method` |
| `MolecularSequence.quality.modifierExtension` | `MolecularSequence.quality.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MolecularSequence.quality.precision` | `MolecularSequence.quality.precision` | `precision` | MolecularSequence.quality.precision | Precision of comparison | 0..1 | decimal |  |  |
| `MolecularSequence.quality.queryFP` | `MolecularSequence.quality.queryFP` | `queryFP` | MolecularSequence.quality.queryFP | False positives | 0..1 | decimal |  |  |
| `MolecularSequence.quality.queryTP` | `MolecularSequence.quality.queryTP` | `queryTP` | MolecularSequence.quality.queryTP | True positives from the perspective of the query data | 0..1 | decimal |  |  |
| `MolecularSequence.quality.recall` | `MolecularSequence.quality.recall` | `recall` | MolecularSequence.quality.recall | Recall of comparison | 0..1 | decimal |  |  |
| `MolecularSequence.quality.roc` | `MolecularSequence.quality.roc` | `roc` | MolecularSequence.quality.roc | Receiver Operator Characteristic (ROC) Curve | 0..1 | BackboneElement |  |  |
| `MolecularSequence.quality.roc.extension` | `MolecularSequence.quality.roc.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MolecularSequence.quality.roc.fMeasure` | `MolecularSequence.quality.roc.fMeasure` | `fMeasure` | MolecularSequence.quality.roc.fMeasure | FScore of the GQ score | 0..* | decimal |  |  |
| `MolecularSequence.quality.roc.id` | `MolecularSequence.quality.roc.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MolecularSequence.quality.roc.modifierExtension` | `MolecularSequence.quality.roc.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MolecularSequence.quality.roc.numFN` | `MolecularSequence.quality.roc.numFN` | `numFN` | MolecularSequence.quality.roc.numFN | Roc score false negative numbers | 0..* | integer |  |  |
| `MolecularSequence.quality.roc.numFP` | `MolecularSequence.quality.roc.numFP` | `numFP` | MolecularSequence.quality.roc.numFP | Roc score false positive numbers | 0..* | integer |  |  |
| `MolecularSequence.quality.roc.numTP` | `MolecularSequence.quality.roc.numTP` | `numTP` | MolecularSequence.quality.roc.numTP | Roc score true positive numbers | 0..* | integer |  |  |
| `MolecularSequence.quality.roc.precision` | `MolecularSequence.quality.roc.precision` | `precision` | MolecularSequence.quality.roc.precision | Precision of the GQ score | 0..* | decimal |  |  |
| `MolecularSequence.quality.roc.score` | `MolecularSequence.quality.roc.score` | `score` | MolecularSequence.quality.roc.score | Genotype quality score | 0..* | integer |  |  |
| `MolecularSequence.quality.roc.sensitivity` | `MolecularSequence.quality.roc.sensitivity` | `sensitivity` | MolecularSequence.quality.roc.sensitivity | Sensitivity of the GQ score | 0..* | decimal |  |  |
| `MolecularSequence.quality.score` | `MolecularSequence.quality.score` | `score` | MolecularSequence.quality.score | Quality score for the comparison | 0..1 | Quantity |  |  |
| `MolecularSequence.quality.standardSequence` | `MolecularSequence.quality.standardSequence` | `standardSequence` | MolecularSequence.quality.standardSequence | Standard sequence for comparison | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/sequence-quality-standardSequence` |
| `MolecularSequence.quality.start` | `MolecularSequence.quality.start` | `start` | MolecularSequence.quality.start | Start position of the sequence | 0..1 | integer |  |  |
| `MolecularSequence.quality.truthFN` | `MolecularSequence.quality.truthFN` | `truthFN` | MolecularSequence.quality.truthFN | False negatives | 0..1 | decimal |  |  |
| `MolecularSequence.quality.truthTP` | `MolecularSequence.quality.truthTP` | `truthTP` | MolecularSequence.quality.truthTP | True positives from the perspective of the truth data | 0..1 | decimal |  |  |
| `MolecularSequence.quality.type` | `MolecularSequence.quality.type` | `type` | MolecularSequence.quality.type | indel \| snp \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/quality-type|4.0.1` |
| `MolecularSequence.quantity` | `MolecularSequence.quantity` | `quantity` | MolecularSequence.quantity | The number of copies of the sequence of interest.  (RNASeq) | 0..1 | Quantity |  |  |
| `MolecularSequence.readCoverage` | `MolecularSequence.readCoverage` | `readCoverage` | MolecularSequence.readCoverage | Average number of reads representing a given nucleotide in the reconstructed sequence | 0..1 | integer |  |  |
| `MolecularSequence.referenceSeq` | `MolecularSequence.referenceSeq` | `referenceSeq` | MolecularSequence.referenceSeq | A sequence used as reference | 0..1 | BackboneElement |  |  |
| `MolecularSequence.referenceSeq.chromosome` | `MolecularSequence.referenceSeq.chromosome` | `chromosome` | MolecularSequence.referenceSeq.chromosome | Chromosome containing genetic finding | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/chromosome-human` |
| `MolecularSequence.referenceSeq.extension` | `MolecularSequence.referenceSeq.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MolecularSequence.referenceSeq.genomeBuild` | `MolecularSequence.referenceSeq.genomeBuild` | `genomeBuild` | MolecularSequence.referenceSeq.genomeBuild | The Genome Build used for reference, following GRCh build versions e.g. 'GRCh 37' | 0..1 | string |  |  |
| `MolecularSequence.referenceSeq.id` | `MolecularSequence.referenceSeq.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MolecularSequence.referenceSeq.modifierExtension` | `MolecularSequence.referenceSeq.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MolecularSequence.referenceSeq.orientation` | `MolecularSequence.referenceSeq.orientation` | `orientation` | MolecularSequence.referenceSeq.orientation | sense \| antisense | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/orientation-type|4.0.1` |
| `MolecularSequence.referenceSeq.referenceSeqId` | `MolecularSequence.referenceSeq.referenceSeqId` | `referenceSeqId` | MolecularSequence.referenceSeq.referenceSeqId | Reference identifier | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/sequence-referenceSeq` |
| `MolecularSequence.referenceSeq.referenceSeqPointer` | `MolecularSequence.referenceSeq.referenceSeqPointer` | `referenceSeqPointer` | MolecularSequence.referenceSeq.referenceSeqPointer | A pointer to another MolecularSequence entity as reference sequence | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/MolecularSequence) |  |  |
| `MolecularSequence.referenceSeq.referenceSeqString` | `MolecularSequence.referenceSeq.referenceSeqString` | `referenceSeqString` | MolecularSequence.referenceSeq.referenceSeqString | A string to represent reference sequence | 0..1 | string |  |  |
| `MolecularSequence.referenceSeq.strand` | `MolecularSequence.referenceSeq.strand` | `strand` | MolecularSequence.referenceSeq.strand | watson \| crick | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/strand-type|4.0.1` |
| `MolecularSequence.referenceSeq.windowEnd` | `MolecularSequence.referenceSeq.windowEnd` | `windowEnd` | MolecularSequence.referenceSeq.windowEnd | End position of the window on the reference sequence | 0..1 | integer |  |  |
| `MolecularSequence.referenceSeq.windowStart` | `MolecularSequence.referenceSeq.windowStart` | `windowStart` | MolecularSequence.referenceSeq.windowStart | Start position of the window on the  reference sequence | 0..1 | integer |  |  |
| `MolecularSequence.repository` | `MolecularSequence.repository` | `repository` | MolecularSequence.repository | External repository which contains detailed report related with observedSeq in this resource | 0..* | BackboneElement |  |  |
| `MolecularSequence.repository.datasetId` | `MolecularSequence.repository.datasetId` | `datasetId` | MolecularSequence.repository.datasetId | Id of the dataset that used to call for dataset in repository | 0..1 | string |  |  |
| `MolecularSequence.repository.extension` | `MolecularSequence.repository.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MolecularSequence.repository.id` | `MolecularSequence.repository.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MolecularSequence.repository.modifierExtension` | `MolecularSequence.repository.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MolecularSequence.repository.name` | `MolecularSequence.repository.name` | `name` | MolecularSequence.repository.name | Repository's name | 0..1 | string |  |  |
| `MolecularSequence.repository.readsetId` | `MolecularSequence.repository.readsetId` | `readsetId` | MolecularSequence.repository.readsetId | Id of the read | 0..1 | string |  |  |
| `MolecularSequence.repository.type` | `MolecularSequence.repository.type` | `type` | MolecularSequence.repository.type | directlink \| openapi \| login \| oauth \| other | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/repository-type|4.0.1` |
| `MolecularSequence.repository.url` | `MolecularSequence.repository.url` | `url` | MolecularSequence.repository.url | URI of the repository | 0..1 | uri |  |  |
| `MolecularSequence.repository.variantsetId` | `MolecularSequence.repository.variantsetId` | `variantsetId` | MolecularSequence.repository.variantsetId | Id of the variantset that used to call for variantset in repository | 0..1 | string |  |  |
| `MolecularSequence.specimen` | `MolecularSequence.specimen` | `specimen` | MolecularSequence.specimen | Specimen used for sequencing | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Specimen) |  |  |
| `MolecularSequence.structureVariant` | `MolecularSequence.structureVariant` | `structureVariant` | MolecularSequence.structureVariant | Structural variant | 0..* | BackboneElement |  |  |
| `MolecularSequence.structureVariant.exact` | `MolecularSequence.structureVariant.exact` | `exact` | MolecularSequence.structureVariant.exact | Does the structural variant have base pair resolution breakpoints? | 0..1 | boolean |  |  |
| `MolecularSequence.structureVariant.extension` | `MolecularSequence.structureVariant.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MolecularSequence.structureVariant.id` | `MolecularSequence.structureVariant.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MolecularSequence.structureVariant.inner` | `MolecularSequence.structureVariant.inner` | `inner` | MolecularSequence.structureVariant.inner | Structural variant inner | 0..1 | BackboneElement |  |  |
| `MolecularSequence.structureVariant.inner.end` | `MolecularSequence.structureVariant.inner.end` | `end` | MolecularSequence.structureVariant.inner.end | Structural variant inner end | 0..1 | integer |  |  |
| `MolecularSequence.structureVariant.inner.extension` | `MolecularSequence.structureVariant.inner.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MolecularSequence.structureVariant.inner.id` | `MolecularSequence.structureVariant.inner.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MolecularSequence.structureVariant.inner.modifierExtension` | `MolecularSequence.structureVariant.inner.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MolecularSequence.structureVariant.inner.start` | `MolecularSequence.structureVariant.inner.start` | `start` | MolecularSequence.structureVariant.inner.start | Structural variant inner start | 0..1 | integer |  |  |
| `MolecularSequence.structureVariant.length` | `MolecularSequence.structureVariant.length` | `length` | MolecularSequence.structureVariant.length | Structural variant length | 0..1 | integer |  |  |
| `MolecularSequence.structureVariant.modifierExtension` | `MolecularSequence.structureVariant.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MolecularSequence.structureVariant.outer` | `MolecularSequence.structureVariant.outer` | `outer` | MolecularSequence.structureVariant.outer | Structural variant outer | 0..1 | BackboneElement |  |  |
| `MolecularSequence.structureVariant.outer.end` | `MolecularSequence.structureVariant.outer.end` | `end` | MolecularSequence.structureVariant.outer.end | Structural variant outer end | 0..1 | integer |  |  |
| `MolecularSequence.structureVariant.outer.extension` | `MolecularSequence.structureVariant.outer.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MolecularSequence.structureVariant.outer.id` | `MolecularSequence.structureVariant.outer.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MolecularSequence.structureVariant.outer.modifierExtension` | `MolecularSequence.structureVariant.outer.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MolecularSequence.structureVariant.outer.start` | `MolecularSequence.structureVariant.outer.start` | `start` | MolecularSequence.structureVariant.outer.start | Structural variant outer start | 0..1 | integer |  |  |
| `MolecularSequence.structureVariant.variantType` | `MolecularSequence.structureVariant.variantType` | `variantType` | MolecularSequence.structureVariant.variantType | Structural variant change type | 0..1 | CodeableConcept | `Required` | `http://loinc.org/vs/LL379-9|4.0.1` |
| `MolecularSequence.text` | `MolecularSequence.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `MolecularSequence.type` | `MolecularSequence.type` | `type` | MolecularSequence.type | aa \| dna \| rna | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/sequence-type|4.0.1` |
| `MolecularSequence.variant` | `MolecularSequence.variant` | `variant` | MolecularSequence.variant | Variant in sequence | 0..* | BackboneElement |  |  |
| `MolecularSequence.variant.cigar` | `MolecularSequence.variant.cigar` | `cigar` | MolecularSequence.variant.cigar | Extended CIGAR string for aligning the sequence with reference bases | 0..1 | string |  |  |
| `MolecularSequence.variant.end` | `MolecularSequence.variant.end` | `end` | MolecularSequence.variant.end | End position of the variant on the reference sequence | 0..1 | integer |  |  |
| `MolecularSequence.variant.extension` | `MolecularSequence.variant.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MolecularSequence.variant.id` | `MolecularSequence.variant.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MolecularSequence.variant.modifierExtension` | `MolecularSequence.variant.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MolecularSequence.variant.observedAllele` | `MolecularSequence.variant.observedAllele` | `observedAllele` | MolecularSequence.variant.observedAllele | Allele that was observed | 0..1 | string |  |  |
| `MolecularSequence.variant.referenceAllele` | `MolecularSequence.variant.referenceAllele` | `referenceAllele` | MolecularSequence.variant.referenceAllele | Allele in the reference sequence | 0..1 | string |  |  |
| `MolecularSequence.variant.start` | `MolecularSequence.variant.start` | `start` | MolecularSequence.variant.start | Start position of the variant on the  reference sequence | 0..1 | integer |  |  |
| `MolecularSequence.variant.variantPointer` | `MolecularSequence.variant.variantPointer` | `variantPointer` | MolecularSequence.variant.variantPointer | Pointer to observed variant information | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Observation) |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Sequence](/docs/R3/Resources/Sequence.md)<br/> `http://hl7.org/fhir/StructureDefinition/Sequence\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `486`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `680`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MolecularSequence](/docs/R4/Resources/MolecularSequence.md)<br/> `http://hl7.org/fhir/StructureDefinition/MolecularSequence\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1551`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1552`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MolecularSequence](/docs/R4B/Resources/MolecularSequence.md)<br/> `http://hl7.org/fhir/StructureDefinition/MolecularSequence\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1011`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1240`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MolecularSequence](/docs/R5/Resources/MolecularSequence.md)<br/> `http://hl7.org/fhir/StructureDefinition/MolecularSequence\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition MolecularSequence from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 Sequence](/docs/R3/Resources/Sequence.md)| Relationship | R4 MolecularSequence| Relationship | [R4B MolecularSequence](/docs/R4B/Resources/MolecularSequence.md)| Relationship | [R5 MolecularSequence](/docs/R5/Resources/MolecularSequence.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | **`MolecularSequence`**| _Equivalent_<br/>(30380/30381)| `MolecularSequence`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(45060)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(45061)| `MolecularSequence`
| | | | | **`MolecularSequence.id`**| _Equivalent_<br/>(30382/30383)| `MolecularSequence.id`| _Equivalent_<br/>(45062/45063)| `MolecularSequence.id`
| | | | | **`MolecularSequence.meta`**| _Equivalent_<br/>(30384/30385)| `MolecularSequence.meta`| _Equivalent_<br/>(45064/45065)| `MolecularSequence.meta`
| | | | | **`MolecularSequence.implicitRules`**| _Equivalent_<br/>(30386/30387)| `MolecularSequence.implicitRules`| _Equivalent_<br/>(45066/45067)| `MolecularSequence.implicitRules`
| | | | | **`MolecularSequence.language`**| _Equivalent_<br/>(30388/30389)| `MolecularSequence.language`| _Equivalent_<br/>(45068/45069)| `MolecularSequence.language`
| | | | | **`MolecularSequence.text`**| _Equivalent_<br/>(30390/30391)| `MolecularSequence.text`| _Equivalent_<br/>(45070/45071)| `MolecularSequence.text`
| | | | | **`MolecularSequence.contained`**| _Equivalent_<br/>(30392/30393)| `MolecularSequence.contained`| _Equivalent_<br/>(45072/45073)| `MolecularSequence.contained`
| | | | | **`MolecularSequence.extension`**| _Equivalent_<br/>(30394/30395)| `MolecularSequence.extension`| _Equivalent_<br/>(45074/45075)| `MolecularSequence.extension`
| | | | | **`MolecularSequence.modifierExtension`**| _Equivalent_<br/>(30396/30397)| `MolecularSequence.modifierExtension`| _Equivalent_<br/>(45076/45077)| `MolecularSequence.modifierExtension`
| | | | | **`MolecularSequence.identifier`**| _Equivalent_<br/>(30398/30399)| `MolecularSequence.identifier`| _Equivalent_<br/>(45078/45079)| `MolecularSequence.identifier`
| | | | | **`MolecularSequence.type`**| _Equivalent_<br/>(30400/30401)| `MolecularSequence.type`| _Equivalent_<br/>(45080/45081)| `MolecularSequence.type`
| | | | | **`MolecularSequence.coordinateSystem`**| _Equivalent_<br/>(30402/30403)| `MolecularSequence.coordinateSystem`| | | 
| | | | | **`MolecularSequence.patient`**| _Equivalent_<br/>(30404/30405)| `MolecularSequence.patient`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1846)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2089)| `MolecularSequence.subject`
| | | | | **`MolecularSequence.specimen`**| _Equivalent_<br/>(30406/30407)| `MolecularSequence.specimen`| _Equivalent_<br/>(45083/45084)| `MolecularSequence.specimen`
| | | | | **`MolecularSequence.device`**| _Equivalent_<br/>(30408/30409)| `MolecularSequence.device`| _Equivalent_<br/>(45085/45086)| `MolecularSequence.device`
| | | | | **`MolecularSequence.performer`**| _Equivalent_<br/>(30410/30411)| `MolecularSequence.performer`| _Equivalent_<br/>(45087/45088)| `MolecularSequence.performer`
| | | | | **`MolecularSequence.quantity`**| _Equivalent_<br/>(30412/30413)| `MolecularSequence.quantity`| | | 
| | | | | **`MolecularSequence.referenceSeq`**| _Equivalent_<br/>(30414/30415)| `MolecularSequence.referenceSeq`| | | 
| | | | | **`MolecularSequence.referenceSeq.id`**| _Equivalent_<br/>(30416/30417)| `MolecularSequence.referenceSeq.id`| | | 
| | | | | **`MolecularSequence.referenceSeq.extension`**| _Equivalent_<br/>(30418/30419)| `MolecularSequence.referenceSeq.extension`| | | 
| | | | | **`MolecularSequence.referenceSeq.modifierExtension`**| _Equivalent_<br/>(30420/30421)| `MolecularSequence.referenceSeq.modifierExtension`| | | 
| | | | | **`MolecularSequence.referenceSeq.chromosome`**| _Equivalent_<br/>(30422/30423)| `MolecularSequence.referenceSeq.chromosome`| | | 
| | | | | **`MolecularSequence.referenceSeq.genomeBuild`**| _Equivalent_<br/>(30424/30425)| `MolecularSequence.referenceSeq.genomeBuild`| | | 
| | | | | **`MolecularSequence.referenceSeq.orientation`**| _Equivalent_<br/>(30426/30427)| `MolecularSequence.referenceSeq.orientation`| | | 
| | | | | **`MolecularSequence.referenceSeq.referenceSeqId`**| _Equivalent_<br/>(30428/30429)| `MolecularSequence.referenceSeq.referenceSeqId`| | | 
| | | | | **`MolecularSequence.referenceSeq.referenceSeqPointer`**| _Equivalent_<br/>(30430/30431)| `MolecularSequence.referenceSeq.referenceSeqPointer`| | | 
| | | | | **`MolecularSequence.referenceSeq.referenceSeqString`**| _Equivalent_<br/>(30432/30433)| `MolecularSequence.referenceSeq.referenceSeqString`| | | 
| | | | | **`MolecularSequence.referenceSeq.strand`**| _Equivalent_<br/>(30434/30435)| `MolecularSequence.referenceSeq.strand`| | | 
| | | | | **`MolecularSequence.referenceSeq.windowStart`**| _Equivalent_<br/>(30436/30437)| `MolecularSequence.referenceSeq.windowStart`| | | 
| | | | | **`MolecularSequence.referenceSeq.windowEnd`**| _Equivalent_<br/>(30438/30439)| `MolecularSequence.referenceSeq.windowEnd`| | | 
| | | | | **`MolecularSequence.variant`**| _Equivalent_<br/>(30440/30441)| `MolecularSequence.variant`| | | 
| | | | | **`MolecularSequence.variant.id`**| _Equivalent_<br/>(30442/30443)| `MolecularSequence.variant.id`| | | 
| | | | | **`MolecularSequence.variant.extension`**| _Equivalent_<br/>(30444/30445)| `MolecularSequence.variant.extension`| | | 
| | | | | **`MolecularSequence.variant.modifierExtension`**| _Equivalent_<br/>(30446/30447)| `MolecularSequence.variant.modifierExtension`| | | 
| | | | | **`MolecularSequence.variant.start`**| _Equivalent_<br/>(30448/30449)| `MolecularSequence.variant.start`| | | 
| | | | | **`MolecularSequence.variant.end`**| _Equivalent_<br/>(30450/30451)| `MolecularSequence.variant.end`| | | 
| | | | | **`MolecularSequence.variant.observedAllele`**| _Equivalent_<br/>(30452/30453)| `MolecularSequence.variant.observedAllele`| | | 
| | | | | **`MolecularSequence.variant.referenceAllele`**| _Equivalent_<br/>(30454/30455)| `MolecularSequence.variant.referenceAllele`| | | 
| | | | | **`MolecularSequence.variant.cigar`**| _Equivalent_<br/>(30456/30457)| `MolecularSequence.variant.cigar`| | | 
| | | | | **`MolecularSequence.variant.variantPointer`**| _Equivalent_<br/>(30458/30459)| `MolecularSequence.variant.variantPointer`| | | 
| | | | | **`MolecularSequence.observedSeq`**| _Equivalent_<br/>(30460/30461)| `MolecularSequence.observedSeq`| | | 
| | | | | **`MolecularSequence.quality`**| _Equivalent_<br/>(30462/30463)| `MolecularSequence.quality`| | | 
| | | | | **`MolecularSequence.quality.id`**| _Equivalent_<br/>(30464/30465)| `MolecularSequence.quality.id`| | | 
| | | | | **`MolecularSequence.quality.extension`**| _Equivalent_<br/>(30466/30467)| `MolecularSequence.quality.extension`| | | 
| | | | | **`MolecularSequence.quality.modifierExtension`**| _Equivalent_<br/>(30468/30469)| `MolecularSequence.quality.modifierExtension`| | | 
| | | | | **`MolecularSequence.quality.type`**| _Equivalent_<br/>(30470/30471)| `MolecularSequence.quality.type`| | | 
| | | | | **`MolecularSequence.quality.standardSequence`**| _Equivalent_<br/>(30472/30473)| `MolecularSequence.quality.standardSequence`| | | 
| | | | | **`MolecularSequence.quality.start`**| _Equivalent_<br/>(30474/30475)| `MolecularSequence.quality.start`| | | 
| | | | | **`MolecularSequence.quality.end`**| _Equivalent_<br/>(30476/30477)| `MolecularSequence.quality.end`| | | 
| | | | | **`MolecularSequence.quality.score`**| _Equivalent_<br/>(30478/30479)| `MolecularSequence.quality.score`| | | 
| | | | | **`MolecularSequence.quality.method`**| _Equivalent_<br/>(30480/30481)| `MolecularSequence.quality.method`| | | 
| | | | | **`MolecularSequence.quality.truthTP`**| _Equivalent_<br/>(30482/30483)| `MolecularSequence.quality.truthTP`| | | 
| | | | | **`MolecularSequence.quality.queryTP`**| _Equivalent_<br/>(30484/30485)| `MolecularSequence.quality.queryTP`| | | 
| | | | | **`MolecularSequence.quality.truthFN`**| _Equivalent_<br/>(30486/30487)| `MolecularSequence.quality.truthFN`| | | 
| | | | | **`MolecularSequence.quality.queryFP`**| _Equivalent_<br/>(30488/30489)| `MolecularSequence.quality.queryFP`| | | 
| | | | | **`MolecularSequence.quality.gtFP`**| _Equivalent_<br/>(30490/30491)| `MolecularSequence.quality.gtFP`| | | 
| | | | | **`MolecularSequence.quality.precision`**| _Equivalent_<br/>(30492/30493)| `MolecularSequence.quality.precision`| | | 
| | | | | **`MolecularSequence.quality.recall`**| _Equivalent_<br/>(30494/30495)| `MolecularSequence.quality.recall`| | | 
| | | | | **`MolecularSequence.quality.fScore`**| _Equivalent_<br/>(30496/30497)| `MolecularSequence.quality.fScore`| | | 
| | | | | **`MolecularSequence.quality.roc`**| _Equivalent_<br/>(30498/30499)| `MolecularSequence.quality.roc`| | | 
| | | | | **`MolecularSequence.quality.roc.id`**| _Equivalent_<br/>(30500/30501)| `MolecularSequence.quality.roc.id`| | | 
| | | | | **`MolecularSequence.quality.roc.extension`**| _Equivalent_<br/>(30502/30503)| `MolecularSequence.quality.roc.extension`| | | 
| | | | | **`MolecularSequence.quality.roc.modifierExtension`**| _Equivalent_<br/>(30504/30505)| `MolecularSequence.quality.roc.modifierExtension`| | | 
| | | | | **`MolecularSequence.quality.roc.score`**| _Equivalent_<br/>(30506/30507)| `MolecularSequence.quality.roc.score`| | | 
| | | | | **`MolecularSequence.quality.roc.numTP`**| _Equivalent_<br/>(30508/30509)| `MolecularSequence.quality.roc.numTP`| | | 
| | | | | **`MolecularSequence.quality.roc.numFP`**| _Equivalent_<br/>(30510/30511)| `MolecularSequence.quality.roc.numFP`| | | 
| | | | | **`MolecularSequence.quality.roc.numFN`**| _Equivalent_<br/>(30512/30513)| `MolecularSequence.quality.roc.numFN`| | | 
| | | | | **`MolecularSequence.quality.roc.precision`**| _Equivalent_<br/>(30514/30515)| `MolecularSequence.quality.roc.precision`| | | 
| | | | | **`MolecularSequence.quality.roc.sensitivity`**| _Equivalent_<br/>(30516/30517)| `MolecularSequence.quality.roc.sensitivity`| | | 
| | | | | **`MolecularSequence.quality.roc.fMeasure`**| _Equivalent_<br/>(30518/30519)| `MolecularSequence.quality.roc.fMeasure`| | | 
| | | | | **`MolecularSequence.readCoverage`**| _Equivalent_<br/>(30520/30521)| `MolecularSequence.readCoverage`| | | 
| | | | | **`MolecularSequence.repository`**| _Equivalent_<br/>(30522/30523)| `MolecularSequence.repository`| | | 
| | | | | **`MolecularSequence.repository.id`**| _Equivalent_<br/>(30524/30525)| `MolecularSequence.repository.id`| | | 
| | | | | **`MolecularSequence.repository.extension`**| _Equivalent_<br/>(30526/30527)| `MolecularSequence.repository.extension`| | | 
| | | | | **`MolecularSequence.repository.modifierExtension`**| _Equivalent_<br/>(30528/30529)| `MolecularSequence.repository.modifierExtension`| | | 
| | | | | **`MolecularSequence.repository.type`**| _Equivalent_<br/>(30530/30531)| `MolecularSequence.repository.type`| | | 
| | | | | **`MolecularSequence.repository.url`**| _Equivalent_<br/>(30532/30533)| `MolecularSequence.repository.url`| | | 
| | | | | **`MolecularSequence.repository.name`**| _Equivalent_<br/>(30534/30535)| `MolecularSequence.repository.name`| | | 
| | | | | **`MolecularSequence.repository.datasetId`**| _Equivalent_<br/>(30536/30537)| `MolecularSequence.repository.datasetId`| | | 
| | | | | **`MolecularSequence.repository.variantsetId`**| _Equivalent_<br/>(30538/30539)| `MolecularSequence.repository.variantsetId`| | | 
| | | | | **`MolecularSequence.repository.readsetId`**| _Equivalent_<br/>(30540/30541)| `MolecularSequence.repository.readsetId`| | | 
| | | | | **`MolecularSequence.pointer`**| _Equivalent_<br/>(30542/30543)| `MolecularSequence.pointer`| | | 
| | | | | **`MolecularSequence.structureVariant`**| _Equivalent_<br/>(30544/30545)| `MolecularSequence.structureVariant`| | | 
| | | | | **`MolecularSequence.structureVariant.id`**| _Equivalent_<br/>(30546/30547)| `MolecularSequence.structureVariant.id`| | | 
| | | | | **`MolecularSequence.structureVariant.extension`**| _Equivalent_<br/>(30548/30549)| `MolecularSequence.structureVariant.extension`| | | 
| | | | | **`MolecularSequence.structureVariant.modifierExtension`**| _Equivalent_<br/>(30550/30551)| `MolecularSequence.structureVariant.modifierExtension`| | | 
| | | | | **`MolecularSequence.structureVariant.variantType`**| _Equivalent_<br/>(30552/30553)| `MolecularSequence.structureVariant.variantType`| | | 
| | | | | **`MolecularSequence.structureVariant.exact`**| _Equivalent_<br/>(30554/30555)| `MolecularSequence.structureVariant.exact`| | | 
| | | | | **`MolecularSequence.structureVariant.length`**| _Equivalent_<br/>(30556/30557)| `MolecularSequence.structureVariant.length`| | | 
| | | | | **`MolecularSequence.structureVariant.outer`**| _Equivalent_<br/>(30558/30559)| `MolecularSequence.structureVariant.outer`| | | 
| | | | | **`MolecularSequence.structureVariant.outer.id`**| _Equivalent_<br/>(30560/30561)| `MolecularSequence.structureVariant.outer.id`| | | 
| | | | | **`MolecularSequence.structureVariant.outer.extension`**| _Equivalent_<br/>(30562/30563)| `MolecularSequence.structureVariant.outer.extension`| | | 
| | | | | **`MolecularSequence.structureVariant.outer.modifierExtension`**| _Equivalent_<br/>(30564/30565)| `MolecularSequence.structureVariant.outer.modifierExtension`| | | 
| | | | | **`MolecularSequence.structureVariant.outer.start`**| _Equivalent_<br/>(30566/30567)| `MolecularSequence.structureVariant.outer.start`| | | 
| | | | | **`MolecularSequence.structureVariant.outer.end`**| _Equivalent_<br/>(30568/30569)| `MolecularSequence.structureVariant.outer.end`| | | 
| | | | | **`MolecularSequence.structureVariant.inner`**| _Equivalent_<br/>(30570/30571)| `MolecularSequence.structureVariant.inner`| | | 
| | | | | **`MolecularSequence.structureVariant.inner.id`**| _Equivalent_<br/>(30572/30573)| `MolecularSequence.structureVariant.inner.id`| | | 
| | | | | **`MolecularSequence.structureVariant.inner.extension`**| _Equivalent_<br/>(30574/30575)| `MolecularSequence.structureVariant.inner.extension`| | | 
| | | | | **`MolecularSequence.structureVariant.inner.modifierExtension`**| _Equivalent_<br/>(30576/30577)| `MolecularSequence.structureVariant.inner.modifierExtension`| | | 
| | | | | **`MolecularSequence.structureVariant.inner.start`**| _Equivalent_<br/>(30578/30579)| `MolecularSequence.structureVariant.inner.start`| | | 
| | | | | **`MolecularSequence.structureVariant.inner.end`**| _Equivalent_<br/>(30580/30581)| `MolecularSequence.structureVariant.inner.end`| | | 
| | | *0 of 70 elements used* <br/>remaining elements:<br/>`Sequence`, `Sequence.contained`, `Sequence.coordinateSystem`, `Sequence.device`, `Sequence.extension`, `Sequence.id`, `Sequence.identifier`, `Sequence.implicitRules`, `Sequence.language`, `Sequence.meta`, `Sequence.modifierExtension`, `Sequence.observedSeq`, `Sequence.patient`, `Sequence.performer`, `Sequence.pointer`, `Sequence.quality`, `Sequence.quality.end`, `Sequence.quality.extension`, `Sequence.quality.fScore`, `Sequence.quality.gtFP`, `Sequence.quality.id`, `Sequence.quality.method`, `Sequence.quality.modifierExtension`, `Sequence.quality.precision`, `Sequence.quality.queryFP`, `Sequence.quality.queryTP`, `Sequence.quality.recall`, `Sequence.quality.score`, `Sequence.quality.standardSequence`, `Sequence.quality.start`, `Sequence.quality.truthFN`, `Sequence.quality.truthTP`, `Sequence.quality.type`, `Sequence.quantity`, `Sequence.readCoverage`, `Sequence.referenceSeq`, `Sequence.referenceSeq.chromosome`, `Sequence.referenceSeq.extension`, `Sequence.referenceSeq.genomeBuild`, `Sequence.referenceSeq.id`, `Sequence.referenceSeq.modifierExtension`, `Sequence.referenceSeq.referenceSeqId`, `Sequence.referenceSeq.referenceSeqPointer`, `Sequence.referenceSeq.referenceSeqString`, `Sequence.referenceSeq.strand`, `Sequence.referenceSeq.windowEnd`, `Sequence.referenceSeq.windowStart`, `Sequence.repository`, `Sequence.repository.datasetId`, `Sequence.repository.extension`, `Sequence.repository.id`, `Sequence.repository.modifierExtension`, `Sequence.repository.name`, `Sequence.repository.readsetId`, `Sequence.repository.type`, `Sequence.repository.url`, `Sequence.repository.variantsetId`, `Sequence.specimen`, `Sequence.text`, `Sequence.type`, `Sequence.variant`, `Sequence.variant.cigar`, `Sequence.variant.end`, `Sequence.variant.extension`, `Sequence.variant.id`, `Sequence.variant.modifierExtension`, `Sequence.variant.observedAllele`, `Sequence.variant.referenceAllele`, `Sequence.variant.start`, `Sequence.variant.variantPointer`| | *101 of 101 elements used* | | *101 of 101 elements used* | | *15 of 44 elements used* <br/>remaining elements:<br/>`MolecularSequence.focus`, `MolecularSequence.formatted`, `MolecularSequence.literal`, `MolecularSequence.relative`, `MolecularSequence.relative.coordinateSystem`, `MolecularSequence.relative.edit`, `MolecularSequence.relative.edit.end`, `MolecularSequence.relative.edit.extension`, `MolecularSequence.relative.edit.id`, `MolecularSequence.relative.edit.modifierExtension`, `MolecularSequence.relative.edit.replacedSequence`, `MolecularSequence.relative.edit.replacementSequence`, `MolecularSequence.relative.edit.start`, `MolecularSequence.relative.extension`, `MolecularSequence.relative.id`, `MolecularSequence.relative.modifierExtension`, `MolecularSequence.relative.ordinalPosition`, `MolecularSequence.relative.sequenceRange`, `MolecularSequence.relative.startingSequence`, `MolecularSequence.relative.startingSequence.chromosome`, `MolecularSequence.relative.startingSequence.extension`, `MolecularSequence.relative.startingSequence.genomeAssembly`, `MolecularSequence.relative.startingSequence.id`, `MolecularSequence.relative.startingSequence.modifierExtension`, `MolecularSequence.relative.startingSequence.orientation`, `MolecularSequence.relative.startingSequence.sequence[x]`, `MolecularSequence.relative.startingSequence.strand`, `MolecularSequence.relative.startingSequence.windowEnd`, `MolecularSequence.relative.startingSequence.windowStart`

