### Lookup for FHIR R4B MolecularSequence for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| MolecularSequence.id | UseElementSameName | MolecularSequence.id |
| MolecularSequence.meta | UseElementSameName | MolecularSequence.meta |
| MolecularSequence.implicitRules | UseElementSameName | MolecularSequence.implicitRules |
| MolecularSequence.language | UseElementSameName | MolecularSequence.language |
| MolecularSequence.text | UseElementSameName | MolecularSequence.text |
| MolecularSequence.contained | UseElementSameName | MolecularSequence.contained |
| MolecularSequence.extension | UseElementSameName | MolecularSequence.extension |
| MolecularSequence.modifierExtension | UseElementSameName | MolecularSequence.modifierExtension |
| MolecularSequence.identifier | UseElementSameName | MolecularSequence.identifier |
| MolecularSequence.type | UseElementSameName | MolecularSequence.type |
| MolecularSequence.coordinateSystem | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-MolecularSequence.coordinateSystem |
| MolecularSequence.patient | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-MolecularSequence.patient |
| MolecularSequence.specimen | UseElementSameName | MolecularSequence.specimen |
| MolecularSequence.device | UseElementSameName | MolecularSequence.device |
| MolecularSequence.performer | UseElementSameName | MolecularSequence.performer |
| MolecularSequence.quantity | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-MolecularSequence.quantity |
| MolecularSequence.referenceSeq | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-MolecularSequence.referenceSeq |
| MolecularSequence.referenceSeq.id | UseExtensionFromAncestor | - |
| MolecularSequence.referenceSeq.extension | UseExtensionFromAncestor | - |
| MolecularSequence.referenceSeq.modifierExtension | UseExtensionFromAncestor | - |
| MolecularSequence.referenceSeq.chromosome | UseExtensionFromAncestor | - |
| MolecularSequence.referenceSeq.genomeBuild | UseExtensionFromAncestor | - |
| MolecularSequence.referenceSeq.orientation | UseExtensionFromAncestor | - |
| MolecularSequence.referenceSeq.referenceSeqId | UseExtensionFromAncestor | - |
| MolecularSequence.referenceSeq.referenceSeqPointer | UseExtensionFromAncestor | - |
| MolecularSequence.referenceSeq.referenceSeqString | UseExtensionFromAncestor | - |
| MolecularSequence.referenceSeq.strand | UseExtensionFromAncestor | - |
| MolecularSequence.referenceSeq.windowStart | UseExtensionFromAncestor | - |
| MolecularSequence.referenceSeq.windowEnd | UseExtensionFromAncestor | - |
| MolecularSequence.variant | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-MolecularSequence.variant |
| MolecularSequence.variant.id | UseExtensionFromAncestor | - |
| MolecularSequence.variant.extension | UseExtensionFromAncestor | - |
| MolecularSequence.variant.modifierExtension | UseExtensionFromAncestor | - |
| MolecularSequence.variant.start | UseExtensionFromAncestor | - |
| MolecularSequence.variant.end | UseExtensionFromAncestor | - |
| MolecularSequence.variant.observedAllele | UseExtensionFromAncestor | - |
| MolecularSequence.variant.referenceAllele | UseExtensionFromAncestor | - |
| MolecularSequence.variant.cigar | UseExtensionFromAncestor | - |
| MolecularSequence.variant.variantPointer | UseExtensionFromAncestor | - |
| MolecularSequence.observedSeq | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-MolecularSequence.observedSeq |
| MolecularSequence.quality | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-MolecularSequence.quality |
| MolecularSequence.quality.id | UseExtensionFromAncestor | - |
| MolecularSequence.quality.extension | UseExtensionFromAncestor | - |
| MolecularSequence.quality.modifierExtension | UseExtensionFromAncestor | - |
| MolecularSequence.quality.type | UseExtensionFromAncestor | - |
| MolecularSequence.quality.standardSequence | UseExtensionFromAncestor | - |
| MolecularSequence.quality.start | UseExtensionFromAncestor | - |
| MolecularSequence.quality.end | UseExtensionFromAncestor | - |
| MolecularSequence.quality.score | UseExtensionFromAncestor | - |
| MolecularSequence.quality.method | UseExtensionFromAncestor | - |
| MolecularSequence.quality.truthTP | UseExtensionFromAncestor | - |
| MolecularSequence.quality.queryTP | UseExtensionFromAncestor | - |
| MolecularSequence.quality.truthFN | UseExtensionFromAncestor | - |
| MolecularSequence.quality.queryFP | UseExtensionFromAncestor | - |
| MolecularSequence.quality.gtFP | UseExtensionFromAncestor | - |
| MolecularSequence.quality.precision | UseExtensionFromAncestor | - |
| MolecularSequence.quality.recall | UseExtensionFromAncestor | - |
| MolecularSequence.quality.fScore | UseExtensionFromAncestor | - |
| MolecularSequence.quality.roc | UseExtensionFromAncestor | - |
| MolecularSequence.quality.roc.id | UseExtensionFromAncestor | - |
| MolecularSequence.quality.roc.extension | UseExtensionFromAncestor | - |
| MolecularSequence.quality.roc.modifierExtension | UseExtensionFromAncestor | - |
| MolecularSequence.quality.roc.score | UseExtensionFromAncestor | - |
| MolecularSequence.quality.roc.numTP | UseExtensionFromAncestor | - |
| MolecularSequence.quality.roc.numFP | UseExtensionFromAncestor | - |
| MolecularSequence.quality.roc.numFN | UseExtensionFromAncestor | - |
| MolecularSequence.quality.roc.precision | UseExtensionFromAncestor | - |
| MolecularSequence.quality.roc.sensitivity | UseExtensionFromAncestor | - |
| MolecularSequence.quality.roc.fMeasure | UseExtensionFromAncestor | - |
| MolecularSequence.readCoverage | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-MolecularSequence.readCoverage |
| MolecularSequence.repository | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-MolecularSequence.repository |
| MolecularSequence.repository.id | UseExtensionFromAncestor | - |
| MolecularSequence.repository.extension | UseExtensionFromAncestor | - |
| MolecularSequence.repository.modifierExtension | UseExtensionFromAncestor | - |
| MolecularSequence.repository.type | UseExtensionFromAncestor | - |
| MolecularSequence.repository.url | UseExtensionFromAncestor | - |
| MolecularSequence.repository.name | UseExtensionFromAncestor | - |
| MolecularSequence.repository.datasetId | UseExtensionFromAncestor | - |
| MolecularSequence.repository.variantsetId | UseExtensionFromAncestor | - |
| MolecularSequence.repository.readsetId | UseExtensionFromAncestor | - |
| MolecularSequence.pointer | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-MolecularSequence.pointer |
| MolecularSequence.structureVariant | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-MolecularSequence.structureVariant |
| MolecularSequence.structureVariant.id | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.extension | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.modifierExtension | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.variantType | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.exact | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.length | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.outer | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.outer.id | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.outer.extension | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.outer.modifierExtension | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.outer.start | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.outer.end | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.inner | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.inner.id | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.inner.extension | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.inner.modifierExtension | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.inner.start | UseExtensionFromAncestor | - |
| MolecularSequence.structureVariant.inner.end | UseExtensionFromAncestor | - |
