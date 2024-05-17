Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MolecularSequence |  | Representation of a molecular sequence. | 44 | 27 |
| Target | MolecularSequence |  | Raw data describing a biological sequence. | 101 | 69 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 30 |
Equivalent | 4 |
RelatedTo | 10 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MolecularSequence | MolecularSequence | Equivalent | R5 `MolecularSequence` maps as Equivalent to R4B `MolecularSequence` |
| MolecularSequence.contained | MolecularSequence.contained | Equivalent | R5 `MolecularSequence.contained` maps as Equivalent to R4B `MolecularSequence.contained` |
| MolecularSequence.device | MolecularSequence.device | Equivalent | R5 `MolecularSequence.device` maps as Equivalent to R4B `MolecularSequence.device` |
| MolecularSequence.extension | MolecularSequence.extension | SourceIsBroaderThanTarget | R5 `MolecularSequence.extension` maps as SourceIsBroaderThanTarget to R4B `MolecularSequence.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| MolecularSequence.focus | - | DoesNotExistInTarget | R5 `MolecularSequence.focus` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.formatted | - | DoesNotExistInTarget | R5 `MolecularSequence.formatted` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.id | MolecularSequence.id | Equivalent | R5 `MolecularSequence.id` maps as Equivalent to R4B `MolecularSequence.id` |
| MolecularSequence.identifier | MolecularSequence.identifier | Equivalent | R5 `MolecularSequence.identifier` maps as Equivalent to R4B `MolecularSequence.identifier` |
| MolecularSequence.implicitRules | MolecularSequence.implicitRules | Equivalent | R5 `MolecularSequence.implicitRules` maps as Equivalent to R4B `MolecularSequence.implicitRules` |
| MolecularSequence.language | MolecularSequence.language | RelatedTo | R5 `MolecularSequence.language` maps as RelatedTo to R4B `MolecularSequence.language` - language changed the binding strength from Required to Preferred |
| MolecularSequence.literal | - | DoesNotExistInTarget | R5 `MolecularSequence.literal` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.meta | MolecularSequence.meta | Equivalent | R5 `MolecularSequence.meta` maps as Equivalent to R4B `MolecularSequence.meta` |
| MolecularSequence.modifierExtension | MolecularSequence.modifierExtension | SourceIsBroaderThanTarget | R5 `MolecularSequence.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `MolecularSequence.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| MolecularSequence.performer | MolecularSequence.performer | Equivalent | R5 `MolecularSequence.performer` maps as Equivalent to R4B `MolecularSequence.performer` |
| MolecularSequence.relative | - | DoesNotExistInTarget | R5 `MolecularSequence.relative` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.coordinateSystem | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.coordinateSystem` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.edit | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.edit` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.edit.end | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.edit.end` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.edit.extension | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.edit.extension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.edit.id | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.edit.id` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.edit.modifierExtension | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.edit.modifierExtension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.edit.replacedSequence | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.edit.replacedSequence` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.edit.replacementSequence | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.edit.replacementSequence` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.edit.start | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.edit.start` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.extension | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.extension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.id | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.id` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.modifierExtension | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.modifierExtension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.ordinalPosition | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.ordinalPosition` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.sequenceRange | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.sequenceRange` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.startingSequence` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence.chromosome | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.startingSequence.chromosome` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence.extension | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.startingSequence.extension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence.genomeAssembly | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.startingSequence.genomeAssembly` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence.id | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.startingSequence.id` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence.modifierExtension | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.startingSequence.modifierExtension` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence.orientation | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.startingSequence.orientation` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence.sequence[x] | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.startingSequence.sequence[x]` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence.strand | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.startingSequence.strand` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence.windowEnd | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.startingSequence.windowEnd` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.relative.startingSequence.windowStart | - | DoesNotExistInTarget | R5 `MolecularSequence.relative.startingSequence.windowStart` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.specimen | MolecularSequence.specimen | Equivalent | R5 `MolecularSequence.specimen` maps as Equivalent to R4B `MolecularSequence.specimen` |
| MolecularSequence.subject | - | DoesNotExistInTarget | R5 `MolecularSequence.subject` does not appear in the target and has no mapping for `MolecularSequence`. |
| MolecularSequence.text | MolecularSequence.text | Equivalent | R5 `MolecularSequence.text` maps as Equivalent to R4B `MolecularSequence.text` |
| MolecularSequence.type | MolecularSequence.type | Equivalent | R5 `MolecularSequence.type` maps as Equivalent to R4B `MolecularSequence.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/sequence-type|5.0.0 and http://hl7.org/fhir/ValueSet/sequence-type|4.3.0 (Equivalent) |

