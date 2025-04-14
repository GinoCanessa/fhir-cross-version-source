Comparison of 
Generated at Monday, April 14, 2025 6:17:32 PM

### SubstanceReferenceInformation

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | SubstanceReferenceInformation |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SubstanceReferenceInformation` |
| Version | 4.0.1 |
| Description | Todo. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1167` |
| Database Snapshot Count | `44` |
| Database Differential Count | `24` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SubstanceReferenceInformation` | `SubstanceReferenceInformation` | `SubstanceReferenceInformation` | SubstanceReferenceInformation | Todo | 0..* | SubstanceReferenceInformation |  |  |
| `SubstanceReferenceInformation.classification` | `SubstanceReferenceInformation.classification` | `classification` | SubstanceReferenceInformation.classification | Todo | 0..* | BackboneElement |  |  |
| `SubstanceReferenceInformation.classification.classification` | `SubstanceReferenceInformation.classification.classification` | `classification` | SubstanceReferenceInformation.classification.classification | Todo | 0..1 | CodeableConcept |  |  |
| `SubstanceReferenceInformation.classification.domain` | `SubstanceReferenceInformation.classification.domain` | `domain` | SubstanceReferenceInformation.classification.domain | Todo | 0..1 | CodeableConcept |  |  |
| `SubstanceReferenceInformation.classification.extension` | `SubstanceReferenceInformation.classification.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceReferenceInformation.classification.id` | `SubstanceReferenceInformation.classification.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceReferenceInformation.classification.modifierExtension` | `SubstanceReferenceInformation.classification.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceReferenceInformation.classification.source` | `SubstanceReferenceInformation.classification.source` | `source` | SubstanceReferenceInformation.classification.source | Todo | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `SubstanceReferenceInformation.classification.subtype` | `SubstanceReferenceInformation.classification.subtype` | `subtype` | SubstanceReferenceInformation.classification.subtype | Todo | 0..* | CodeableConcept |  |  |
| `SubstanceReferenceInformation.comment` | `SubstanceReferenceInformation.comment` | `comment` | SubstanceReferenceInformation.comment | Todo | 0..1 | string |  |  |
| `SubstanceReferenceInformation.contained` | `SubstanceReferenceInformation.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `SubstanceReferenceInformation.extension` | `SubstanceReferenceInformation.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceReferenceInformation.gene` | `SubstanceReferenceInformation.gene` | `gene` | SubstanceReferenceInformation.gene | Todo | 0..* | BackboneElement |  |  |
| `SubstanceReferenceInformation.gene.extension` | `SubstanceReferenceInformation.gene.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceReferenceInformation.gene.gene` | `SubstanceReferenceInformation.gene.gene` | `gene` | SubstanceReferenceInformation.gene.gene | Todo | 0..1 | CodeableConcept |  |  |
| `SubstanceReferenceInformation.gene.geneSequenceOrigin` | `SubstanceReferenceInformation.gene.geneSequenceOrigin` | `geneSequenceOrigin` | SubstanceReferenceInformation.gene.geneSequenceOrigin | Todo | 0..1 | CodeableConcept |  |  |
| `SubstanceReferenceInformation.gene.id` | `SubstanceReferenceInformation.gene.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceReferenceInformation.gene.modifierExtension` | `SubstanceReferenceInformation.gene.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceReferenceInformation.gene.source` | `SubstanceReferenceInformation.gene.source` | `source` | SubstanceReferenceInformation.gene.source | Todo | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `SubstanceReferenceInformation.geneElement` | `SubstanceReferenceInformation.geneElement` | `geneElement` | SubstanceReferenceInformation.geneElement | Todo | 0..* | BackboneElement |  |  |
| `SubstanceReferenceInformation.geneElement.element` | `SubstanceReferenceInformation.geneElement.element` | `element` | SubstanceReferenceInformation.geneElement.element | Todo | 0..1 | Identifier |  |  |
| `SubstanceReferenceInformation.geneElement.extension` | `SubstanceReferenceInformation.geneElement.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceReferenceInformation.geneElement.id` | `SubstanceReferenceInformation.geneElement.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceReferenceInformation.geneElement.modifierExtension` | `SubstanceReferenceInformation.geneElement.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceReferenceInformation.geneElement.source` | `SubstanceReferenceInformation.geneElement.source` | `source` | SubstanceReferenceInformation.geneElement.source | Todo | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `SubstanceReferenceInformation.geneElement.type` | `SubstanceReferenceInformation.geneElement.type` | `type` | SubstanceReferenceInformation.geneElement.type | Todo | 0..1 | CodeableConcept |  |  |
| `SubstanceReferenceInformation.id` | `SubstanceReferenceInformation.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `SubstanceReferenceInformation.implicitRules` | `SubstanceReferenceInformation.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `SubstanceReferenceInformation.language` | `SubstanceReferenceInformation.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `SubstanceReferenceInformation.meta` | `SubstanceReferenceInformation.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `SubstanceReferenceInformation.modifierExtension` | `SubstanceReferenceInformation.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SubstanceReferenceInformation.target` | `SubstanceReferenceInformation.target` | `target` | SubstanceReferenceInformation.target | Todo | 0..* | BackboneElement |  |  |
| `SubstanceReferenceInformation.target.amountType` | `SubstanceReferenceInformation.target.amountType` | `amountType` | SubstanceReferenceInformation.target.amountType | Todo | 0..1 | CodeableConcept |  |  |
| `SubstanceReferenceInformation.target.amount[x]` | `SubstanceReferenceInformation.target.amount[x]` | `amount[x]` | SubstanceReferenceInformation.target.amount[x] | Todo | 0..1 | Quantity, Range, string |  |  |
| `SubstanceReferenceInformation.target.extension` | `SubstanceReferenceInformation.target.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceReferenceInformation.target.id` | `SubstanceReferenceInformation.target.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceReferenceInformation.target.interaction` | `SubstanceReferenceInformation.target.interaction` | `interaction` | SubstanceReferenceInformation.target.interaction | Todo | 0..1 | CodeableConcept |  |  |
| `SubstanceReferenceInformation.target.modifierExtension` | `SubstanceReferenceInformation.target.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceReferenceInformation.target.organism` | `SubstanceReferenceInformation.target.organism` | `organism` | SubstanceReferenceInformation.target.organism | Todo | 0..1 | CodeableConcept |  |  |
| `SubstanceReferenceInformation.target.organismType` | `SubstanceReferenceInformation.target.organismType` | `organismType` | SubstanceReferenceInformation.target.organismType | Todo | 0..1 | CodeableConcept |  |  |
| `SubstanceReferenceInformation.target.source` | `SubstanceReferenceInformation.target.source` | `source` | SubstanceReferenceInformation.target.source | Todo | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `SubstanceReferenceInformation.target.target` | `SubstanceReferenceInformation.target.target` | `target` | SubstanceReferenceInformation.target.target | Todo | 0..1 | Identifier |  |  |
| `SubstanceReferenceInformation.target.type` | `SubstanceReferenceInformation.target.type` | `type` | SubstanceReferenceInformation.target.type | Todo | 0..1 | CodeableConcept |  |  |
| `SubstanceReferenceInformation.text` | `SubstanceReferenceInformation.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

