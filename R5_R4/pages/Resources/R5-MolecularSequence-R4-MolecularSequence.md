Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MolecularSequence |  | Representation of a molecular sequence. | 44 | 27 |
| Target | MolecularSequence |  | Raw data describing a biological sequence. | 101 | 69 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 17 |
Equivalent | 21 |
RelatedTo | 1 |
SourceIsBroaderThanTarget | 3 |
SourceIsNarrowerThanTarget | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MolecularSequence | MolecularSequence | Equivalent | R5 `MolecularSequence` maps as Equivalent to R4 `MolecularSequence` |
| MolecularSequence.contained | MolecularSequence.contained | Equivalent | R5 `MolecularSequence.contained` maps as Equivalent to R4 `MolecularSequence.contained` |
| MolecularSequence.device | MolecularSequence.device | Equivalent | R5 `MolecularSequence.device` maps as Equivalent to R4 `MolecularSequence.device` |
| MolecularSequence.extension | MolecularSequence.extension | SourceIsBroaderThanTarget | R5 `MolecularSequence.extension` maps as SourceIsBroaderThanTarget to R4 `MolecularSequence.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MolecularSequence.focus | - | DoesNotExistInTarget | R5 `MolecularSequence.focus` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.formatted | - | DoesNotExistInTarget | R5 `MolecularSequence.formatted` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.id | MolecularSequence.id | Equivalent | R5 `MolecularSequence.id` maps as Equivalent to R4 `MolecularSequence.id` |
| MolecularSequence.identifier | MolecularSequence.identifier | Equivalent | R5 `MolecularSequence.identifier` maps as Equivalent to R4 `MolecularSequence.identifier` |
| MolecularSequence.implicitRules | MolecularSequence.implicitRules | Equivalent | R5 `MolecularSequence.implicitRules` maps as Equivalent to R4 `MolecularSequence.implicitRules` |
| MolecularSequence.language | MolecularSequence.language | SourceIsNarrowerThanTarget | R5 `MolecularSequence.language` maps as SourceIsNarrowerThanTarget to R4 `MolecularSequence.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| MolecularSequence.literal | MolecularSequence.observedSeq | Equivalent | R5 `MolecularSequence.literal` maps as Equivalent to R4 `MolecularSequence.observedSeq` |
| MolecularSequence.meta | MolecularSequence.meta | Equivalent | R5 `MolecularSequence.meta` maps as Equivalent to R4 `MolecularSequence.meta` |
| MolecularSequence.modifierExtension | MolecularSequence.modifierExtension | SourceIsBroaderThanTarget | R5 `MolecularSequence.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MolecularSequence.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MolecularSequence.performer | MolecularSequence.performer | Equivalent | R5 `MolecularSequence.performer` maps as Equivalent to R4 `MolecularSequence.performer` |
| MolecularSequence.relative | - | DoesNotExistInTarget | R5 `MolecularSequence.relative` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.coordinateSystem | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.coordinateSystem` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.edit | MolecularSequence.variant | Equivalent | R5 `MolecularSequence.relative.edit` maps as Equivalent to R4 `MolecularSequence.variant` |
| MolecularSequence.relative.edit.end | MolecularSequence.variant.end | Equivalent | R5 `MolecularSequence.relative.edit.end` maps as Equivalent to R4 `MolecularSequence.variant.end` |
| MolecularSequence.relative.edit.extension | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.edit.extension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.edit.id | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.edit.id` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.edit.modifierExtension | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.edit.modifierExtension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.edit.replacedSequence | MolecularSequence.variant.referenceAllele | Equivalent | R5 `MolecularSequence.relative.edit.replacedSequence` maps as Equivalent to R4 `MolecularSequence.variant.referenceAllele` |
| MolecularSequence.relative.edit.replacementSequence | MolecularSequence.variant.observedAllele | Equivalent | R5 `MolecularSequence.relative.edit.replacementSequence` maps as Equivalent to R4 `MolecularSequence.variant.observedAllele` |
| MolecularSequence.relative.edit.start | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.edit.start` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.extension | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.extension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.id | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.id` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.modifierExtension | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.modifierExtension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.ordinalPosition | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.ordinalPosition` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.sequenceRange | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.sequenceRange` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence | MolecularSequence.referenceSeq | Equivalent | R5 `MolecularSequence.relative.startingSequence` maps as Equivalent to R4 `MolecularSequence.referenceSeq` |
| MolecularSequence.relative.startingSequence.chromosome | MolecularSequence.referenceSeq.chromosome | SourceIsNarrowerThanTarget | R5 `MolecularSequence.relative.startingSequence.chromosome` maps as SourceIsNarrowerThanTarget to R4 `MolecularSequence.referenceSeq.chromosome` - chromosome changed the binding strength from Required to Example; chromosome has change due to type change: R5 `chromosome` `CodeableConcept` maps as SourceIsNarrowerThanTarget for R4 `chromosome` |
| MolecularSequence.relative.startingSequence.extension | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.startingSequence.extension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence.genomeAssembly | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.startingSequence.genomeAssembly` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence.id | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.startingSequence.id` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence.modifierExtension | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.startingSequence.modifierExtension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence.orientation | MolecularSequence.referenceSeq.orientation | Equivalent | R5 `MolecularSequence.relative.startingSequence.orientation` maps as Equivalent to R4 `MolecularSequence.referenceSeq.orientation` - orientation has compatible required binding for code type: http://hl7.org/fhir/ValueSet/orientation-type|5.0.0 and http://hl7.org/fhir/ValueSet/orientation-type|4.0.1 (Equivalent) |
| MolecularSequence.relative.startingSequence.sequence[x] | MolecularSequence.referenceSeq.referenceSeqString | RelatedTo | R5 `MolecularSequence.relative.startingSequence.sequence[x]` maps as RelatedTo to R4 `MolecularSequence.referenceSeq.referenceSeqString` - referenceSeqString removed a binding requirement - Example ; referenceSeqString has change due to type change: R5 sequence[x] CodeableConcept has no equivalent or mapped type in R4 referenceSeqString; referenceSeqString has change due to type change: R5 `sequence[x]` `string` maps as SourceIsNarrowerThanTarget for R4 `referenceSeqString`; referenceSeqString has change due to type change: R5 sequence[x] Reference has no equivalent or mapped type in R4 referenceSeqString |
| MolecularSequence.relative.startingSequence.strand | MolecularSequence.referenceSeq.strand | Equivalent | R5 `MolecularSequence.relative.startingSequence.strand` maps as Equivalent to R4 `MolecularSequence.referenceSeq.strand` - strand has compatible required binding for code type: http://hl7.org/fhir/ValueSet/strand-type|5.0.0 and http://hl7.org/fhir/ValueSet/strand-type|4.0.1 (Equivalent) |
| MolecularSequence.relative.startingSequence.windowEnd | MolecularSequence.referenceSeq.windowEnd | Equivalent | R5 `MolecularSequence.relative.startingSequence.windowEnd` maps as Equivalent to R4 `MolecularSequence.referenceSeq.windowEnd` |
| MolecularSequence.relative.startingSequence.windowStart | MolecularSequence.referenceSeq.windowStart | Equivalent | R5 `MolecularSequence.relative.startingSequence.windowStart` maps as Equivalent to R4 `MolecularSequence.referenceSeq.windowStart` |
| MolecularSequence.specimen | MolecularSequence.specimen | Equivalent | R5 `MolecularSequence.specimen` maps as Equivalent to R4 `MolecularSequence.specimen` |
| MolecularSequence.subject | MolecularSequence.patient | SourceIsBroaderThanTarget | R5 `MolecularSequence.subject` maps as SourceIsBroaderThanTarget to R4 `MolecularSequence.patient` - patient has change due to type change: R5 `subject` `Reference` maps as SourceIsBroaderThanTarget for R4 `patient` |
| MolecularSequence.text | MolecularSequence.text | Equivalent | R5 `MolecularSequence.text` maps as Equivalent to R4 `MolecularSequence.text` |
| MolecularSequence.type | MolecularSequence.type | Equivalent | R5 `MolecularSequence.type` maps as Equivalent to R4 `MolecularSequence.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/sequence-type|5.0.0 and http://hl7.org/fhir/ValueSet/sequence-type|4.0.1 (Equivalent) |

