Comparison of 
Generated at Monday, April 14, 2025 6:17:25 PM

### Sequence

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Sequence |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Sequence` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Sequence Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `579` |
| Database Snapshot Count | `70` |
| Database Differential Count | `50` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Sequence` | `Sequence` | `Sequence` | Sequence | Information about a biological sequence | 0..* | Sequence |  |  |
| `Sequence.contained` | `Sequence.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Sequence.coordinateSystem` | `Sequence.coordinateSystem` | `coordinateSystem` |  | Base number of coordinate system (0 for 0-based numbering or coordinates, inclusive start, exclusive end, 1 for 1-based numbering, inclusive start, inclusive end) | 1..1 | integer |  |  |
| `Sequence.device` | `Sequence.device` | `device` |  | The method for sequencing | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device) |  |  |
| `Sequence.extension` | `Sequence.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Sequence.id` | `Sequence.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Sequence.identifier` | `Sequence.identifier` | `identifier` |  | Unique ID for this particular sequence. This is a FHIR-defined id | 0..* | Identifier |  |  |
| `Sequence.implicitRules` | `Sequence.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Sequence.language` | `Sequence.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `Sequence.meta` | `Sequence.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Sequence.modifierExtension` | `Sequence.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Sequence.observedSeq` | `Sequence.observedSeq` | `observedSeq` |  | Sequence that was observed | 0..1 | string |  |  |
| `Sequence.patient` | `Sequence.patient` | `patient` |  | Who and/or what this is about | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `Sequence.performer` | `Sequence.performer` | `performer` |  | Who should be responsible for test result | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Sequence.pointer` | `Sequence.pointer` | `pointer` |  | Pointer to next atomic sequence | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Sequence) |  |  |
| `Sequence.quality` | `Sequence.quality` | `quality` |  | An set of value as quality of sequence | 0..* | BackboneElement |  |  |
| `Sequence.quality.end` | `Sequence.quality.end` | `end` |  | End position of the sequence | 0..1 | integer |  |  |
| `Sequence.quality.extension` | `Sequence.quality.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Sequence.quality.fScore` | `Sequence.quality.fScore` | `fScore` |  | F-score | 0..1 | decimal |  |  |
| `Sequence.quality.gtFP` | `Sequence.quality.gtFP` | `gtFP` |  | False positives where the non-REF alleles in the Truth and Query Call Sets match | 0..1 | decimal |  |  |
| `Sequence.quality.id` | `Sequence.quality.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Sequence.quality.method` | `Sequence.quality.method` | `method` |  | Method to get quality | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/sequence-quality-method` |
| `Sequence.quality.modifierExtension` | `Sequence.quality.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Sequence.quality.precision` | `Sequence.quality.precision` | `precision` |  | Precision of comparison | 0..1 | decimal |  |  |
| `Sequence.quality.queryFP` | `Sequence.quality.queryFP` | `queryFP` |  | False positives | 0..1 | decimal |  |  |
| `Sequence.quality.queryTP` | `Sequence.quality.queryTP` | `queryTP` |  | True positives from the perspective of the query data | 0..1 | decimal |  |  |
| `Sequence.quality.recall` | `Sequence.quality.recall` | `recall` |  | Recall of comparison | 0..1 | decimal |  |  |
| `Sequence.quality.score` | `Sequence.quality.score` | `score` |  | Quality score for the comparison | 0..1 | Quantity |  |  |
| `Sequence.quality.standardSequence` | `Sequence.quality.standardSequence` | `standardSequence` |  | Standard sequence for comparison | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/sequence-quality-standardSequence` |
| `Sequence.quality.start` | `Sequence.quality.start` | `start` |  | Start position of the sequence | 0..1 | integer |  |  |
| `Sequence.quality.truthFN` | `Sequence.quality.truthFN` | `truthFN` |  | False negatives | 0..1 | decimal |  |  |
| `Sequence.quality.truthTP` | `Sequence.quality.truthTP` | `truthTP` |  | True positives from the perspective of the truth data | 0..1 | decimal |  |  |
| `Sequence.quality.type` | `Sequence.quality.type` | `type` |  | indel \| snp \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/quality-type` |
| `Sequence.quantity` | `Sequence.quantity` | `quantity` |  | The number of copies of the seqeunce of interest.  (RNASeq) | 0..1 | Quantity |  |  |
| `Sequence.readCoverage` | `Sequence.readCoverage` | `readCoverage` |  | Average number of reads representing a given nucleotide in the reconstructed sequence | 0..1 | integer |  |  |
| `Sequence.referenceSeq` | `Sequence.referenceSeq` | `referenceSeq` |  | A sequence used as reference | 0..1 | BackboneElement |  |  |
| `Sequence.referenceSeq.chromosome` | `Sequence.referenceSeq.chromosome` | `chromosome` |  | Chromosome containing genetic finding | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/chromosome-human` |
| `Sequence.referenceSeq.extension` | `Sequence.referenceSeq.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Sequence.referenceSeq.genomeBuild` | `Sequence.referenceSeq.genomeBuild` | `genomeBuild` |  | The Genome Build used for reference, following GRCh build versions e.g. 'GRCh 37' | 0..1 | string |  |  |
| `Sequence.referenceSeq.id` | `Sequence.referenceSeq.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Sequence.referenceSeq.modifierExtension` | `Sequence.referenceSeq.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Sequence.referenceSeq.referenceSeqId` | `Sequence.referenceSeq.referenceSeqId` | `referenceSeqId` |  | Reference identifier | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/sequence-referenceSeq` |
| `Sequence.referenceSeq.referenceSeqPointer` | `Sequence.referenceSeq.referenceSeqPointer` | `referenceSeqPointer` |  | A Pointer to another Sequence entity as reference sequence | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Sequence) |  |  |
| `Sequence.referenceSeq.referenceSeqString` | `Sequence.referenceSeq.referenceSeqString` | `referenceSeqString` |  | A string to represent reference sequence | 0..1 | string |  |  |
| `Sequence.referenceSeq.strand` | `Sequence.referenceSeq.strand` | `strand` |  | Directionality of DNA ( +1/-1) | 0..1 | integer |  |  |
| `Sequence.referenceSeq.windowEnd` | `Sequence.referenceSeq.windowEnd` | `windowEnd` |  | End position of the window on the reference sequence | 1..1 | integer |  |  |
| `Sequence.referenceSeq.windowStart` | `Sequence.referenceSeq.windowStart` | `windowStart` |  | Start position of the window on the  reference sequence | 1..1 | integer |  |  |
| `Sequence.repository` | `Sequence.repository` | `repository` |  | External repository which contains detailed report related with observedSeq in this resource | 0..* | BackboneElement |  |  |
| `Sequence.repository.datasetId` | `Sequence.repository.datasetId` | `datasetId` |  | Id of the dataset that used to call for dataset in repository | 0..1 | string |  |  |
| `Sequence.repository.extension` | `Sequence.repository.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Sequence.repository.id` | `Sequence.repository.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Sequence.repository.modifierExtension` | `Sequence.repository.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Sequence.repository.name` | `Sequence.repository.name` | `name` |  | Repository's name | 0..1 | string |  |  |
| `Sequence.repository.readsetId` | `Sequence.repository.readsetId` | `readsetId` |  | Id of the read | 0..1 | string |  |  |
| `Sequence.repository.type` | `Sequence.repository.type` | `type` |  | directlink \| openapi \| login \| oauth \| other | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/repository-type` |
| `Sequence.repository.url` | `Sequence.repository.url` | `url` |  | URI of the repository | 0..1 | uri |  |  |
| `Sequence.repository.variantsetId` | `Sequence.repository.variantsetId` | `variantsetId` |  | Id of the variantset that used to call for variantset in repository | 0..1 | string |  |  |
| `Sequence.specimen` | `Sequence.specimen` | `specimen` |  | Specimen used for sequencing | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Specimen) |  |  |
| `Sequence.text` | `Sequence.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Sequence.type` | `Sequence.type` | `type` |  | aa \| dna \| rna | 0..1 | code | `Example` | `http://hl7.org/fhir/ValueSet/sequence-type` |
| `Sequence.variant` | `Sequence.variant` | `variant` |  | Variant in sequence | 0..* | BackboneElement |  |  |
| `Sequence.variant.cigar` | `Sequence.variant.cigar` | `cigar` |  | Extended CIGAR string for aligning the sequence with reference bases | 0..1 | string |  |  |
| `Sequence.variant.end` | `Sequence.variant.end` | `end` |  | End position of the variant on the reference sequence | 0..1 | integer |  |  |
| `Sequence.variant.extension` | `Sequence.variant.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Sequence.variant.id` | `Sequence.variant.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Sequence.variant.modifierExtension` | `Sequence.variant.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Sequence.variant.observedAllele` | `Sequence.variant.observedAllele` | `observedAllele` |  | Allele that was observed | 0..1 | string |  |  |
| `Sequence.variant.referenceAllele` | `Sequence.variant.referenceAllele` | `referenceAllele` |  | Allele in the reference sequence | 0..1 | string |  |  |
| `Sequence.variant.start` | `Sequence.variant.start` | `start` |  | Start position of the variant on the  reference sequence | 0..1 | integer |  |  |
| `Sequence.variant.variantPointer` | `Sequence.variant.variantPointer` | `variantPointer` |  | Pointer to observed variant information | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Observation) |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Sequence](/docs/R3/Resources/Sequence.md)<br/> `http://hl7.org/fhir/StructureDefinition/Sequence\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `486`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `680`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MolecularSequence](/docs/R4/Resources/MolecularSequence.md)<br/> `http://hl7.org/fhir/StructureDefinition/MolecularSequence\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1551`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1552`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MolecularSequence](/docs/R4B/Resources/MolecularSequence.md)<br/> `http://hl7.org/fhir/StructureDefinition/MolecularSequence\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1011`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1240`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MolecularSequence](/docs/R5/Resources/MolecularSequence.md)<br/> `http://hl7.org/fhir/StructureDefinition/MolecularSequence\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Sequence from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 Sequence| Relationship | [R4 MolecularSequence](/docs/R4/Resources/MolecularSequence.md)| Relationship | [R4B MolecularSequence](/docs/R4B/Resources/MolecularSequence.md)| Relationship | [R5 MolecularSequence](/docs/R5/Resources/MolecularSequence.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`Sequence`**| | | | | | | 
| | | **`Sequence.id`**| | | | | | | 
| | | **`Sequence.meta`**| | | | | | | 
| | | **`Sequence.implicitRules`**| | | | | | | 
| | | **`Sequence.language`**| | | | | | | 
| | | **`Sequence.text`**| | | | | | | 
| | | **`Sequence.contained`**| | | | | | | 
| | | **`Sequence.extension`**| | | | | | | 
| | | **`Sequence.modifierExtension`**| | | | | | | 
| | | **`Sequence.identifier`**| | | | | | | 
| | | **`Sequence.type`**| | | | | | | 
| | | **`Sequence.coordinateSystem`**| | | | | | | 
| | | **`Sequence.patient`**| | | | | | | 
| | | **`Sequence.specimen`**| | | | | | | 
| | | **`Sequence.device`**| | | | | | | 
| | | **`Sequence.performer`**| | | | | | | 
| | | **`Sequence.quantity`**| | | | | | | 
| | | **`Sequence.referenceSeq`**| | | | | | | 
| | | **`Sequence.referenceSeq.id`**| | | | | | | 
| | | **`Sequence.referenceSeq.extension`**| | | | | | | 
| | | **`Sequence.referenceSeq.modifierExtension`**| | | | | | | 
| | | **`Sequence.referenceSeq.chromosome`**| | | | | | | 
| | | **`Sequence.referenceSeq.genomeBuild`**| | | | | | | 
| | | **`Sequence.referenceSeq.referenceSeqId`**| | | | | | | 
| | | **`Sequence.referenceSeq.referenceSeqPointer`**| | | | | | | 
| | | **`Sequence.referenceSeq.referenceSeqString`**| | | | | | | 
| | | **`Sequence.referenceSeq.strand`**| | | | | | | 
| | | **`Sequence.referenceSeq.windowStart`**| | | | | | | 
| | | **`Sequence.referenceSeq.windowEnd`**| | | | | | | 
| | | **`Sequence.variant`**| | | | | | | 
| | | **`Sequence.variant.id`**| | | | | | | 
| | | **`Sequence.variant.extension`**| | | | | | | 
| | | **`Sequence.variant.modifierExtension`**| | | | | | | 
| | | **`Sequence.variant.start`**| | | | | | | 
| | | **`Sequence.variant.end`**| | | | | | | 
| | | **`Sequence.variant.observedAllele`**| | | | | | | 
| | | **`Sequence.variant.referenceAllele`**| | | | | | | 
| | | **`Sequence.variant.cigar`**| | | | | | | 
| | | **`Sequence.variant.variantPointer`**| | | | | | | 
| | | **`Sequence.observedSeq`**| | | | | | | 
| | | **`Sequence.quality`**| | | | | | | 
| | | **`Sequence.quality.id`**| | | | | | | 
| | | **`Sequence.quality.extension`**| | | | | | | 
| | | **`Sequence.quality.modifierExtension`**| | | | | | | 
| | | **`Sequence.quality.type`**| | | | | | | 
| | | **`Sequence.quality.standardSequence`**| | | | | | | 
| | | **`Sequence.quality.start`**| | | | | | | 
| | | **`Sequence.quality.end`**| | | | | | | 
| | | **`Sequence.quality.score`**| | | | | | | 
| | | **`Sequence.quality.method`**| | | | | | | 
| | | **`Sequence.quality.truthTP`**| | | | | | | 
| | | **`Sequence.quality.queryTP`**| | | | | | | 
| | | **`Sequence.quality.truthFN`**| | | | | | | 
| | | **`Sequence.quality.queryFP`**| | | | | | | 
| | | **`Sequence.quality.gtFP`**| | | | | | | 
| | | **`Sequence.quality.precision`**| | | | | | | 
| | | **`Sequence.quality.recall`**| | | | | | | 
| | | **`Sequence.quality.fScore`**| | | | | | | 
| | | **`Sequence.readCoverage`**| | | | | | | 
| | | **`Sequence.repository`**| | | | | | | 
| | | **`Sequence.repository.id`**| | | | | | | 
| | | **`Sequence.repository.extension`**| | | | | | | 
| | | **`Sequence.repository.modifierExtension`**| | | | | | | 
| | | **`Sequence.repository.type`**| | | | | | | 
| | | **`Sequence.repository.url`**| | | | | | | 
| | | **`Sequence.repository.name`**| | | | | | | 
| | | **`Sequence.repository.datasetId`**| | | | | | | 
| | | **`Sequence.repository.variantsetId`**| | | | | | | 
| | | **`Sequence.repository.readsetId`**| | | | | | | 
| | | **`Sequence.pointer`**| | | | | | | 
| | | *70 of 70 elements used* | | *0 of 101 elements used* <br/>remaining elements:<br/>`MolecularSequence`, `MolecularSequence.contained`, `MolecularSequence.coordinateSystem`, `MolecularSequence.device`, `MolecularSequence.extension`, `MolecularSequence.id`, `MolecularSequence.identifier`, `MolecularSequence.implicitRules`, `MolecularSequence.language`, `MolecularSequence.meta`, `MolecularSequence.modifierExtension`, `MolecularSequence.observedSeq`, `MolecularSequence.patient`, `MolecularSequence.performer`, `MolecularSequence.pointer`, `MolecularSequence.quality`, `MolecularSequence.quality.end`, `MolecularSequence.quality.extension`, `MolecularSequence.quality.fScore`, `MolecularSequence.quality.gtFP`, `MolecularSequence.quality.id`, `MolecularSequence.quality.method`, `MolecularSequence.quality.modifierExtension`, `MolecularSequence.quality.precision`, `MolecularSequence.quality.queryFP`, `MolecularSequence.quality.queryTP`, `MolecularSequence.quality.recall`, `MolecularSequence.quality.roc`, `MolecularSequence.quality.roc.extension`, `MolecularSequence.quality.roc.fMeasure`, `MolecularSequence.quality.roc.id`, `MolecularSequence.quality.roc.modifierExtension`, `MolecularSequence.quality.roc.numFN`, `MolecularSequence.quality.roc.numFP`, `MolecularSequence.quality.roc.numTP`, `MolecularSequence.quality.roc.precision`, `MolecularSequence.quality.roc.score`, `MolecularSequence.quality.roc.sensitivity`, `MolecularSequence.quality.score`, `MolecularSequence.quality.standardSequence`, `MolecularSequence.quality.start`, `MolecularSequence.quality.truthFN`, `MolecularSequence.quality.truthTP`, `MolecularSequence.quality.type`, `MolecularSequence.quantity`, `MolecularSequence.readCoverage`, `MolecularSequence.referenceSeq`, `MolecularSequence.referenceSeq.chromosome`, `MolecularSequence.referenceSeq.extension`, `MolecularSequence.referenceSeq.genomeBuild`, `MolecularSequence.referenceSeq.id`, `MolecularSequence.referenceSeq.modifierExtension`, `MolecularSequence.referenceSeq.orientation`, `MolecularSequence.referenceSeq.referenceSeqId`, `MolecularSequence.referenceSeq.referenceSeqPointer`, `MolecularSequence.referenceSeq.referenceSeqString`, `MolecularSequence.referenceSeq.strand`, `MolecularSequence.referenceSeq.windowEnd`, `MolecularSequence.referenceSeq.windowStart`, `MolecularSequence.repository`, `MolecularSequence.repository.datasetId`, `MolecularSequence.repository.extension`, `MolecularSequence.repository.id`, `MolecularSequence.repository.modifierExtension`, `MolecularSequence.repository.name`, `MolecularSequence.repository.readsetId`, `MolecularSequence.repository.type`, `MolecularSequence.repository.url`, `MolecularSequence.repository.variantsetId`, `MolecularSequence.specimen`, `MolecularSequence.structureVariant`, `MolecularSequence.structureVariant.exact`, `MolecularSequence.structureVariant.extension`, `MolecularSequence.structureVariant.id`, `MolecularSequence.structureVariant.inner`, `MolecularSequence.structureVariant.inner.end`, `MolecularSequence.structureVariant.inner.extension`, `MolecularSequence.structureVariant.inner.id`, `MolecularSequence.structureVariant.inner.modifierExtension`, `MolecularSequence.structureVariant.inner.start`, `MolecularSequence.structureVariant.length`, `MolecularSequence.structureVariant.modifierExtension`, `MolecularSequence.structureVariant.outer`, `MolecularSequence.structureVariant.outer.end`, `MolecularSequence.structureVariant.outer.extension`, `MolecularSequence.structureVariant.outer.id`, `MolecularSequence.structureVariant.outer.modifierExtension`, `MolecularSequence.structureVariant.outer.start`, `MolecularSequence.structureVariant.variantType`, `MolecularSequence.text`, `MolecularSequence.type`, `MolecularSequence.variant`, `MolecularSequence.variant.cigar`, `MolecularSequence.variant.end`, `MolecularSequence.variant.extension`, `MolecularSequence.variant.id`, `MolecularSequence.variant.modifierExtension`, `MolecularSequence.variant.observedAllele`, `MolecularSequence.variant.referenceAllele`, `MolecularSequence.variant.start`, `MolecularSequence.variant.variantPointer`| | *0 of 101 elements used* <br/>remaining elements:<br/>`MolecularSequence`, `MolecularSequence.contained`, `MolecularSequence.coordinateSystem`, `MolecularSequence.device`, `MolecularSequence.extension`, `MolecularSequence.id`, `MolecularSequence.identifier`, `MolecularSequence.implicitRules`, `MolecularSequence.language`, `MolecularSequence.meta`, `MolecularSequence.modifierExtension`, `MolecularSequence.observedSeq`, `MolecularSequence.patient`, `MolecularSequence.performer`, `MolecularSequence.pointer`, `MolecularSequence.quality`, `MolecularSequence.quality.end`, `MolecularSequence.quality.extension`, `MolecularSequence.quality.fScore`, `MolecularSequence.quality.gtFP`, `MolecularSequence.quality.id`, `MolecularSequence.quality.method`, `MolecularSequence.quality.modifierExtension`, `MolecularSequence.quality.precision`, `MolecularSequence.quality.queryFP`, `MolecularSequence.quality.queryTP`, `MolecularSequence.quality.recall`, `MolecularSequence.quality.roc`, `MolecularSequence.quality.roc.extension`, `MolecularSequence.quality.roc.fMeasure`, `MolecularSequence.quality.roc.id`, `MolecularSequence.quality.roc.modifierExtension`, `MolecularSequence.quality.roc.numFN`, `MolecularSequence.quality.roc.numFP`, `MolecularSequence.quality.roc.numTP`, `MolecularSequence.quality.roc.precision`, `MolecularSequence.quality.roc.score`, `MolecularSequence.quality.roc.sensitivity`, `MolecularSequence.quality.score`, `MolecularSequence.quality.standardSequence`, `MolecularSequence.quality.start`, `MolecularSequence.quality.truthFN`, `MolecularSequence.quality.truthTP`, `MolecularSequence.quality.type`, `MolecularSequence.quantity`, `MolecularSequence.readCoverage`, `MolecularSequence.referenceSeq`, `MolecularSequence.referenceSeq.chromosome`, `MolecularSequence.referenceSeq.extension`, `MolecularSequence.referenceSeq.genomeBuild`, `MolecularSequence.referenceSeq.id`, `MolecularSequence.referenceSeq.modifierExtension`, `MolecularSequence.referenceSeq.orientation`, `MolecularSequence.referenceSeq.referenceSeqId`, `MolecularSequence.referenceSeq.referenceSeqPointer`, `MolecularSequence.referenceSeq.referenceSeqString`, `MolecularSequence.referenceSeq.strand`, `MolecularSequence.referenceSeq.windowEnd`, `MolecularSequence.referenceSeq.windowStart`, `MolecularSequence.repository`, `MolecularSequence.repository.datasetId`, `MolecularSequence.repository.extension`, `MolecularSequence.repository.id`, `MolecularSequence.repository.modifierExtension`, `MolecularSequence.repository.name`, `MolecularSequence.repository.readsetId`, `MolecularSequence.repository.type`, `MolecularSequence.repository.url`, `MolecularSequence.repository.variantsetId`, `MolecularSequence.specimen`, `MolecularSequence.structureVariant`, `MolecularSequence.structureVariant.exact`, `MolecularSequence.structureVariant.extension`, `MolecularSequence.structureVariant.id`, `MolecularSequence.structureVariant.inner`, `MolecularSequence.structureVariant.inner.end`, `MolecularSequence.structureVariant.inner.extension`, `MolecularSequence.structureVariant.inner.id`, `MolecularSequence.structureVariant.inner.modifierExtension`, `MolecularSequence.structureVariant.inner.start`, `MolecularSequence.structureVariant.length`, `MolecularSequence.structureVariant.modifierExtension`, `MolecularSequence.structureVariant.outer`, `MolecularSequence.structureVariant.outer.end`, `MolecularSequence.structureVariant.outer.extension`, `MolecularSequence.structureVariant.outer.id`, `MolecularSequence.structureVariant.outer.modifierExtension`, `MolecularSequence.structureVariant.outer.start`, `MolecularSequence.structureVariant.variantType`, `MolecularSequence.text`, `MolecularSequence.type`, `MolecularSequence.variant`, `MolecularSequence.variant.cigar`, `MolecularSequence.variant.end`, `MolecularSequence.variant.extension`, `MolecularSequence.variant.id`, `MolecularSequence.variant.modifierExtension`, `MolecularSequence.variant.observedAllele`, `MolecularSequence.variant.referenceAllele`, `MolecularSequence.variant.start`, `MolecularSequence.variant.variantPointer`| | *0 of 44 elements used* <br/>remaining elements:<br/>`MolecularSequence`, `MolecularSequence.contained`, `MolecularSequence.device`, `MolecularSequence.extension`, `MolecularSequence.focus`, `MolecularSequence.formatted`, `MolecularSequence.id`, `MolecularSequence.identifier`, `MolecularSequence.implicitRules`, `MolecularSequence.language`, `MolecularSequence.literal`, `MolecularSequence.meta`, `MolecularSequence.modifierExtension`, `MolecularSequence.performer`, `MolecularSequence.relative`, `MolecularSequence.relative.coordinateSystem`, `MolecularSequence.relative.edit`, `MolecularSequence.relative.edit.end`, `MolecularSequence.relative.edit.extension`, `MolecularSequence.relative.edit.id`, `MolecularSequence.relative.edit.modifierExtension`, `MolecularSequence.relative.edit.replacedSequence`, `MolecularSequence.relative.edit.replacementSequence`, `MolecularSequence.relative.edit.start`, `MolecularSequence.relative.extension`, `MolecularSequence.relative.id`, `MolecularSequence.relative.modifierExtension`, `MolecularSequence.relative.ordinalPosition`, `MolecularSequence.relative.sequenceRange`, `MolecularSequence.relative.startingSequence`, `MolecularSequence.relative.startingSequence.chromosome`, `MolecularSequence.relative.startingSequence.extension`, `MolecularSequence.relative.startingSequence.genomeAssembly`, `MolecularSequence.relative.startingSequence.id`, `MolecularSequence.relative.startingSequence.modifierExtension`, `MolecularSequence.relative.startingSequence.orientation`, `MolecularSequence.relative.startingSequence.sequence[x]`, `MolecularSequence.relative.startingSequence.strand`, `MolecularSequence.relative.startingSequence.windowEnd`, `MolecularSequence.relative.startingSequence.windowStart`, `MolecularSequence.specimen`, `MolecularSequence.subject`, `MolecularSequence.text`, `MolecularSequence.type`

