Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | SubstanceProtein |  | A SubstanceProtein is defined as a single unit of a linear amino acid sequence, or a combination of subunits that are either covalently linked or have a defined invariant stoichiometric relationship. This includes all synthetic, recombinant and purified SubstanceProteins of defined sequence, whether the use is therapeutic or prophylactic. This set of elements will be used to describe albumins, coagulation factors, cytokines, growth factors, peptide/SubstanceProtein hormones, enzymes, toxins, toxoids, recombinant vaccines, and immunomodulators. | 24 | 13 |
| Target | SubstanceProtein |  | A SubstanceProtein is defined as a single unit of a linear amino acid sequence, or a combination of subunits that are either covalently linked or have a defined invariant stoichiometric relationship. This includes all synthetic, recombinant and purified SubstanceProteins of defined sequence, whether the use is therapeutic or prophylactic. This set of elements will be used to describe albumins, coagulation factors, cytokines, growth factors, peptide/SubstanceProtein hormones, enzymes, toxins, toxoids, recombinant vaccines, and immunomodulators. | 24 | 13 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 20 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| SubstanceProtein | SubstanceProtein | Equivalent | R5 `SubstanceProtein` maps as Equivalent to R4 `SubstanceProtein` |
| SubstanceProtein.contained | SubstanceProtein.contained | Equivalent | R5 `SubstanceProtein.contained` maps as Equivalent to R4 `SubstanceProtein.contained` |
| SubstanceProtein.disulfideLinkage | SubstanceProtein.disulfideLinkage | Equivalent | R5 `SubstanceProtein.disulfideLinkage` maps as Equivalent to R4 `SubstanceProtein.disulfideLinkage` |
| SubstanceProtein.extension | SubstanceProtein.extension | SourceIsBroaderThanTarget | R5 `SubstanceProtein.extension` maps as SourceIsBroaderThanTarget to R4 `SubstanceProtein.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| SubstanceProtein.id | SubstanceProtein.id | Equivalent | R5 `SubstanceProtein.id` maps as Equivalent to R4 `SubstanceProtein.id` |
| SubstanceProtein.implicitRules | SubstanceProtein.implicitRules | Equivalent | R5 `SubstanceProtein.implicitRules` maps as Equivalent to R4 `SubstanceProtein.implicitRules` |
| SubstanceProtein.language | SubstanceProtein.language | RelatedTo | R5 `SubstanceProtein.language` maps as RelatedTo to R4 `SubstanceProtein.language` - language changed the binding strength from Required to Preferred |
| SubstanceProtein.meta | SubstanceProtein.meta | Equivalent | R5 `SubstanceProtein.meta` maps as Equivalent to R4 `SubstanceProtein.meta` |
| SubstanceProtein.modifierExtension | SubstanceProtein.modifierExtension | SourceIsBroaderThanTarget | R5 `SubstanceProtein.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `SubstanceProtein.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| SubstanceProtein.numberOfSubunits | SubstanceProtein.numberOfSubunits | Equivalent | R5 `SubstanceProtein.numberOfSubunits` maps as Equivalent to R4 `SubstanceProtein.numberOfSubunits` |
| SubstanceProtein.sequenceType | SubstanceProtein.sequenceType | Equivalent | R5 `SubstanceProtein.sequenceType` maps as Equivalent to R4 `SubstanceProtein.sequenceType` |
| SubstanceProtein.subunit | SubstanceProtein.subunit | Equivalent | R5 `SubstanceProtein.subunit` maps as Equivalent to R4 `SubstanceProtein.subunit` |
| SubstanceProtein.subunit.cTerminalModification | SubstanceProtein.subunit.cTerminalModification | Equivalent | R5 `SubstanceProtein.subunit.cTerminalModification` maps as Equivalent to R4 `SubstanceProtein.subunit.cTerminalModification` |
| SubstanceProtein.subunit.cTerminalModificationId | SubstanceProtein.subunit.cTerminalModificationId | Equivalent | R5 `SubstanceProtein.subunit.cTerminalModificationId` maps as Equivalent to R4 `SubstanceProtein.subunit.cTerminalModificationId` |
| SubstanceProtein.subunit.extension | SubstanceProtein.subunit.extension | SourceIsBroaderThanTarget | R5 `SubstanceProtein.subunit.extension` maps as SourceIsBroaderThanTarget to R4 `SubstanceProtein.subunit.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| SubstanceProtein.subunit.id | SubstanceProtein.subunit.id | Equivalent | R5 `SubstanceProtein.subunit.id` maps as Equivalent to R4 `SubstanceProtein.subunit.id` |
| SubstanceProtein.subunit.length | SubstanceProtein.subunit.length | Equivalent | R5 `SubstanceProtein.subunit.length` maps as Equivalent to R4 `SubstanceProtein.subunit.length` |
| SubstanceProtein.subunit.modifierExtension | SubstanceProtein.subunit.modifierExtension | SourceIsBroaderThanTarget | R5 `SubstanceProtein.subunit.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `SubstanceProtein.subunit.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| SubstanceProtein.subunit.nTerminalModification | SubstanceProtein.subunit.nTerminalModification | Equivalent | R5 `SubstanceProtein.subunit.nTerminalModification` maps as Equivalent to R4 `SubstanceProtein.subunit.nTerminalModification` |
| SubstanceProtein.subunit.nTerminalModificationId | SubstanceProtein.subunit.nTerminalModificationId | Equivalent | R5 `SubstanceProtein.subunit.nTerminalModificationId` maps as Equivalent to R4 `SubstanceProtein.subunit.nTerminalModificationId` |
| SubstanceProtein.subunit.sequence | SubstanceProtein.subunit.sequence | Equivalent | R5 `SubstanceProtein.subunit.sequence` maps as Equivalent to R4 `SubstanceProtein.subunit.sequence` |
| SubstanceProtein.subunit.sequenceAttachment | SubstanceProtein.subunit.sequenceAttachment | RelatedTo | R5 `SubstanceProtein.subunit.sequenceAttachment` maps as RelatedTo to R4 `SubstanceProtein.subunit.sequenceAttachment` - sequenceAttachment has change due to type change: R5 `sequenceAttachment` `Attachment` maps as RelatedTo for R4 `sequenceAttachment` |
| SubstanceProtein.subunit.subunit | SubstanceProtein.subunit.subunit | Equivalent | R5 `SubstanceProtein.subunit.subunit` maps as Equivalent to R4 `SubstanceProtein.subunit.subunit` |
| SubstanceProtein.text | SubstanceProtein.text | Equivalent | R5 `SubstanceProtein.text` maps as Equivalent to R4 `SubstanceProtein.text` |

