Comparison of 
Generated at Monday, April 14, 2025 6:17:32 PM

### SubstanceNucleicAcid

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | SubstanceNucleicAcid |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SubstanceNucleicAcid` |
| Version | 4.0.1 |
| Description | Nucleic acids are defined by three distinct elements: the base, sugar and linkage. Individual substance/moiety IDs will be created for each of these elements. The nucleotide sequence will be always entered in the 5’-3’ direction. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1164` |
| Database Snapshot Count | `38` |
| Database Differential Count | `21` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SubstanceNucleicAcid` | `SubstanceNucleicAcid` | `SubstanceNucleicAcid` | SubstanceNucleicAcid | Nucleic acids are defined by three distinct elements: the base, sugar and linkage. Individual substance/moiety IDs will be created for each of these elements. The nucleotide sequence will be always entered in the 5’-3’ direction | 0..* | SubstanceNucleicAcid |  |  |
| `SubstanceNucleicAcid.areaOfHybridisation` | `SubstanceNucleicAcid.areaOfHybridisation` | `areaOfHybridisation` | SubstanceNucleicAcid.areaOfHybridisation | The area of hybridisation shall be described if applicable for double stranded RNA or DNA. The number associated with the subunit followed by the number associated to the residue shall be specified in increasing order. The underscore “” shall be used as separator as follows: “Subunitnumber Residue” | 0..1 | string |  |  |
| `SubstanceNucleicAcid.contained` | `SubstanceNucleicAcid.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `SubstanceNucleicAcid.extension` | `SubstanceNucleicAcid.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceNucleicAcid.id` | `SubstanceNucleicAcid.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `SubstanceNucleicAcid.implicitRules` | `SubstanceNucleicAcid.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `SubstanceNucleicAcid.language` | `SubstanceNucleicAcid.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `SubstanceNucleicAcid.meta` | `SubstanceNucleicAcid.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `SubstanceNucleicAcid.modifierExtension` | `SubstanceNucleicAcid.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SubstanceNucleicAcid.numberOfSubunits` | `SubstanceNucleicAcid.numberOfSubunits` | `numberOfSubunits` | SubstanceNucleicAcid.numberOfSubunits | The number of linear sequences of nucleotides linked through phosphodiester bonds shall be described. Subunits would be strands of nucleic acids that are tightly associated typically through Watson-Crick base pairing. NOTE: If not specified in the reference source, the assumption is that there is 1 subunit | 0..1 | integer |  |  |
| `SubstanceNucleicAcid.oligoNucleotideType` | `SubstanceNucleicAcid.oligoNucleotideType` | `oligoNucleotideType` | SubstanceNucleicAcid.oligoNucleotideType | (TBC) | 0..1 | CodeableConcept |  |  |
| `SubstanceNucleicAcid.sequenceType` | `SubstanceNucleicAcid.sequenceType` | `sequenceType` | SubstanceNucleicAcid.sequenceType | The type of the sequence shall be specified based on a controlled vocabulary | 0..1 | CodeableConcept |  |  |
| `SubstanceNucleicAcid.subunit` | `SubstanceNucleicAcid.subunit` | `subunit` | SubstanceNucleicAcid.subunit | Subunits are listed in order of decreasing length; sequences of the same length will be ordered by molecular weight; subunits that have identical sequences will be repeated multiple times | 0..* | BackboneElement |  |  |
| `SubstanceNucleicAcid.subunit.extension` | `SubstanceNucleicAcid.subunit.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceNucleicAcid.subunit.fivePrime` | `SubstanceNucleicAcid.subunit.fivePrime` | `fivePrime` | SubstanceNucleicAcid.subunit.fivePrime | The nucleotide present at the 5’ terminal shall be specified based on a controlled vocabulary. Since the sequence is represented from the 5' to the 3' end, the 5’ prime nucleotide is the letter at the first position in the sequence. A separate representation would be redundant | 0..1 | CodeableConcept |  |  |
| `SubstanceNucleicAcid.subunit.id` | `SubstanceNucleicAcid.subunit.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceNucleicAcid.subunit.length` | `SubstanceNucleicAcid.subunit.length` | `length` | SubstanceNucleicAcid.subunit.length | The length of the sequence shall be captured | 0..1 | integer |  |  |
| `SubstanceNucleicAcid.subunit.linkage` | `SubstanceNucleicAcid.subunit.linkage` | `linkage` | SubstanceNucleicAcid.subunit.linkage | The linkages between sugar residues will also be captured | 0..* | BackboneElement |  |  |
| `SubstanceNucleicAcid.subunit.linkage.connectivity` | `SubstanceNucleicAcid.subunit.linkage.connectivity` | `connectivity` | SubstanceNucleicAcid.subunit.linkage.connectivity | The entity that links the sugar residues together should also be captured for nearly all naturally occurring nucleic acid the linkage is a phosphate group. For many synthetic oligonucleotides phosphorothioate linkages are often seen. Linkage connectivity is assumed to be 3’-5’. If the linkage is either 3’-3’ or 5’-5’ this should be specified | 0..1 | string |  |  |
| `SubstanceNucleicAcid.subunit.linkage.extension` | `SubstanceNucleicAcid.subunit.linkage.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceNucleicAcid.subunit.linkage.id` | `SubstanceNucleicAcid.subunit.linkage.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceNucleicAcid.subunit.linkage.identifier` | `SubstanceNucleicAcid.subunit.linkage.identifier` | `identifier` | SubstanceNucleicAcid.subunit.linkage.identifier | Each linkage will be registered as a fragment and have an ID | 0..1 | Identifier |  |  |
| `SubstanceNucleicAcid.subunit.linkage.modifierExtension` | `SubstanceNucleicAcid.subunit.linkage.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceNucleicAcid.subunit.linkage.name` | `SubstanceNucleicAcid.subunit.linkage.name` | `name` | SubstanceNucleicAcid.subunit.linkage.name | Each linkage will be registered as a fragment and have at least one name. A single name shall be assigned to each linkage | 0..1 | string |  |  |
| `SubstanceNucleicAcid.subunit.linkage.residueSite` | `SubstanceNucleicAcid.subunit.linkage.residueSite` | `residueSite` | SubstanceNucleicAcid.subunit.linkage.residueSite | Residues shall be captured as described in 5.3.6.8.3 | 0..1 | string |  |  |
| `SubstanceNucleicAcid.subunit.modifierExtension` | `SubstanceNucleicAcid.subunit.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceNucleicAcid.subunit.sequence` | `SubstanceNucleicAcid.subunit.sequence` | `sequence` | SubstanceNucleicAcid.subunit.sequence | Actual nucleotide sequence notation from 5' to 3' end using standard single letter codes. In addition to the base sequence, sugar and type of phosphate or non-phosphate linkage should also be captured | 0..1 | string |  |  |
| `SubstanceNucleicAcid.subunit.sequenceAttachment` | `SubstanceNucleicAcid.subunit.sequenceAttachment` | `sequenceAttachment` | SubstanceNucleicAcid.subunit.sequenceAttachment | (TBC) | 0..1 | Attachment |  |  |
| `SubstanceNucleicAcid.subunit.subunit` | `SubstanceNucleicAcid.subunit.subunit` | `subunit` | SubstanceNucleicAcid.subunit.subunit | Index of linear sequences of nucleic acids in order of decreasing length. Sequences of the same length will be ordered by molecular weight. Subunits that have identical sequences will be repeated and have sequential subscripts | 0..1 | integer |  |  |
| `SubstanceNucleicAcid.subunit.sugar` | `SubstanceNucleicAcid.subunit.sugar` | `sugar` | SubstanceNucleicAcid.subunit.sugar | 5.3.6.8.1 Sugar ID (Mandatory) | 0..* | BackboneElement |  |  |
| `SubstanceNucleicAcid.subunit.sugar.extension` | `SubstanceNucleicAcid.subunit.sugar.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceNucleicAcid.subunit.sugar.id` | `SubstanceNucleicAcid.subunit.sugar.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceNucleicAcid.subunit.sugar.identifier` | `SubstanceNucleicAcid.subunit.sugar.identifier` | `identifier` | SubstanceNucleicAcid.subunit.sugar.identifier | The Substance ID of the sugar or sugar-like component that make up the nucleotide | 0..1 | Identifier |  |  |
| `SubstanceNucleicAcid.subunit.sugar.modifierExtension` | `SubstanceNucleicAcid.subunit.sugar.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceNucleicAcid.subunit.sugar.name` | `SubstanceNucleicAcid.subunit.sugar.name` | `name` | SubstanceNucleicAcid.subunit.sugar.name | The name of the sugar or sugar-like component that make up the nucleotide | 0..1 | string |  |  |
| `SubstanceNucleicAcid.subunit.sugar.residueSite` | `SubstanceNucleicAcid.subunit.sugar.residueSite` | `residueSite` | SubstanceNucleicAcid.subunit.sugar.residueSite | The residues that contain a given sugar will be captured. The order of given residues will be captured in the 5‘-3‘direction consistent with the base sequences listed above | 0..1 | string |  |  |
| `SubstanceNucleicAcid.subunit.threePrime` | `SubstanceNucleicAcid.subunit.threePrime` | `threePrime` | SubstanceNucleicAcid.subunit.threePrime | The nucleotide present at the 3’ terminal shall be specified based on a controlled vocabulary. Since the sequence is represented from the 5' to the 3' end, the 5’ prime nucleotide is the letter at the last position in the sequence. A separate representation would be redundant | 0..1 | CodeableConcept |  |  |
| `SubstanceNucleicAcid.text` | `SubstanceNucleicAcid.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

