Comparison of 
Generated at Monday, April 14, 2025 6:17:45 PM

### SubstanceProtein

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | SubstanceProtein |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SubstanceProtein` |
| Version | 5.0.0 |
| Description | A SubstanceProtein is defined as a single unit of a linear amino acid sequence, or a combination of subunits that are either covalently linked or have a defined invariant stoichiometric relationship. This includes all synthetic, recombinant and purified SubstanceProteins of defined sequence, whether the use is therapeutic or prophylactic. This set of elements will be used to describe albumins, coagulation factors, cytokines, growth factors, peptide/SubstanceProtein hormones, enzymes, toxins, toxoids, recombinant vaccines, and immunomodulators. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2394` |
| Database Snapshot Count | `24` |
| Database Differential Count | `13` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SubstanceProtein` | `SubstanceProtein` | `SubstanceProtein` | SubstanceProtein | A SubstanceProtein is defined as a single unit of a linear amino acid sequence, or a combination of subunits that are either covalently linked or have a defined invariant stoichiometric relationship. This includes all synthetic, recombinant and purified SubstanceProteins of defined sequence, whether the use is therapeutic or prophylactic. This set of elements will be used to describe albumins, coagulation factors, cytokines, growth factors, peptide/SubstanceProtein hormones, enzymes, toxins, toxoids, recombinant vaccines, and immunomodulators | 0..* | SubstanceProtein |  |  |
| `SubstanceProtein.contained` | `SubstanceProtein.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `SubstanceProtein.disulfideLinkage` | `SubstanceProtein.disulfideLinkage` | `disulfideLinkage` | SubstanceProtein.disulfideLinkage | The disulphide bond between two cysteine residues either on the same subunit or on two different subunits shall be described. The position of the disulfide bonds in the SubstanceProtein shall be listed in increasing order of subunit number and position within subunit followed by the abbreviation of the amino acids involved. The disulfide linkage positions shall actually contain the amino acid Cysteine at the respective positions | 0..* | string |  |  |
| `SubstanceProtein.extension` | `SubstanceProtein.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceProtein.id` | `SubstanceProtein.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `SubstanceProtein.implicitRules` | `SubstanceProtein.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `SubstanceProtein.language` | `SubstanceProtein.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `SubstanceProtein.meta` | `SubstanceProtein.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `SubstanceProtein.modifierExtension` | `SubstanceProtein.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SubstanceProtein.numberOfSubunits` | `SubstanceProtein.numberOfSubunits` | `numberOfSubunits` | SubstanceProtein.numberOfSubunits | Number of linear sequences of amino acids linked through peptide bonds. The number of subunits constituting the SubstanceProtein shall be described. It is possible that the number of subunits can be variable | 0..1 | integer |  |  |
| `SubstanceProtein.sequenceType` | `SubstanceProtein.sequenceType` | `sequenceType` | SubstanceProtein.sequenceType | The SubstanceProtein descriptive elements will only be used when a complete or partial amino acid sequence is available or derivable from a nucleic acid sequence | 0..1 | CodeableConcept |  |  |
| `SubstanceProtein.subunit` | `SubstanceProtein.subunit` | `subunit` | SubstanceProtein.subunit | This subclause refers to the description of each subunit constituting the SubstanceProtein. A subunit is a linear sequence of amino acids linked through peptide bonds. The Subunit information shall be provided when the finished SubstanceProtein is a complex of multiple sequences; subunits are not used to delineate domains within a single sequence. Subunits are listed in order of decreasing length; sequences of the same length will be ordered by decreasing molecular weight; subunits that have identical sequences will be repeated multiple times | 0..* | BackboneElement |  |  |
| `SubstanceProtein.subunit.cTerminalModification` | `SubstanceProtein.subunit.cTerminalModification` | `cTerminalModification` | SubstanceProtein.subunit.cTerminalModification | The modification at the C-terminal shall be specified | 0..1 | string |  |  |
| `SubstanceProtein.subunit.cTerminalModificationId` | `SubstanceProtein.subunit.cTerminalModificationId` | `cTerminalModificationId` | SubstanceProtein.subunit.cTerminalModificationId | Unique identifier for molecular fragment modification based on the ISO 11238 Substance ID | 0..1 | Identifier |  |  |
| `SubstanceProtein.subunit.extension` | `SubstanceProtein.subunit.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceProtein.subunit.id` | `SubstanceProtein.subunit.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceProtein.subunit.length` | `SubstanceProtein.subunit.length` | `length` | SubstanceProtein.subunit.length | Length of linear sequences of amino acids contained in the subunit | 0..1 | integer |  |  |
| `SubstanceProtein.subunit.modifierExtension` | `SubstanceProtein.subunit.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceProtein.subunit.nTerminalModification` | `SubstanceProtein.subunit.nTerminalModification` | `nTerminalModification` | SubstanceProtein.subunit.nTerminalModification | The name of the fragment modified at the N-terminal of the SubstanceProtein shall be specified | 0..1 | string |  |  |
| `SubstanceProtein.subunit.nTerminalModificationId` | `SubstanceProtein.subunit.nTerminalModificationId` | `nTerminalModificationId` | SubstanceProtein.subunit.nTerminalModificationId | Unique identifier for molecular fragment modification based on the ISO 11238 Substance ID | 0..1 | Identifier |  |  |
| `SubstanceProtein.subunit.sequence` | `SubstanceProtein.subunit.sequence` | `sequence` | SubstanceProtein.subunit.sequence | The sequence information shall be provided enumerating the amino acids from N- to C-terminal end using standard single-letter amino acid codes. Uppercase shall be used for L-amino acids and lowercase for D-amino acids. Transcribed SubstanceProteins will always be described using the translated sequence; for synthetic peptide containing amino acids that are not represented with a single letter code an X should be used within the sequence. The modified amino acids will be distinguished by their position in the sequence | 0..1 | string |  |  |
| `SubstanceProtein.subunit.sequenceAttachment` | `SubstanceProtein.subunit.sequenceAttachment` | `sequenceAttachment` | SubstanceProtein.subunit.sequenceAttachment | The sequence information shall be provided enumerating the amino acids from N- to C-terminal end using standard single-letter amino acid codes. Uppercase shall be used for L-amino acids and lowercase for D-amino acids. Transcribed SubstanceProteins will always be described using the translated sequence; for synthetic peptide containing amino acids that are not represented with a single letter code an X should be used within the sequence. The modified amino acids will be distinguished by their position in the sequence | 0..1 | Attachment |  |  |
| `SubstanceProtein.subunit.subunit` | `SubstanceProtein.subunit.subunit` | `subunit` | SubstanceProtein.subunit.subunit | Index of primary sequences of amino acids linked through peptide bonds in order of decreasing length. Sequences of the same length will be ordered by molecular weight. Subunits that have identical sequences will be repeated and have sequential subscripts | 0..1 | integer |  |  |
| `SubstanceProtein.text` | `SubstanceProtein.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

