Comparison of 
Generated at Friday, April 4, 2025 2:59:02 PM

### ArtifactAssessment

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | ArtifactAssessment |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ArtifactAssessment` |
| Version | 5.0.0 |
| Description | This Resource provides one or more comments, classifiers or ratings about a Resource and supports attribution and rights management metadata for the added content. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2256` |
| Database Snapshot Count | `33` |
| Database Differential Count | `22` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ArtifactAssessment` | `ArtifactAssessment` | `ArtifactAssessment` | ArtifactAssessment | Adds metadata-supported comments, classifiers or ratings related to a Resource | 0..* | ArtifactAssessment |  |  |
| `ArtifactAssessment.approvalDate` | `ArtifactAssessment.approvalDate` | `approvalDate` | ArtifactAssessment.approvalDate | When the artifact assessment was approved by publisher | 0..1 | date |  |  |
| `ArtifactAssessment.artifact[x]` | `ArtifactAssessment.artifact[x]` | `artifact[x]` | ArtifactAssessment.artifact[x] | The artifact assessed, commented upon or rated | 1..1 | canonical, Reference(http://hl7.org/fhir/StructureDefinition/Resource), uri |  |  |
| `ArtifactAssessment.citeAs[x]` | `ArtifactAssessment.citeAs[x]` | `citeAs[x]` | ArtifactAssessment.citeAs[x] | How to cite the comment or rating | 0..1 | markdown, Reference(http://hl7.org/fhir/StructureDefinition/Citation) |  |  |
| `ArtifactAssessment.contained` | `ArtifactAssessment.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ArtifactAssessment.content` | `ArtifactAssessment.content` | `content` | ArtifactAssessment.content | Comment, classifier, or rating content | 0..* | BackboneElement |  |  |
| `ArtifactAssessment.content.author` | `ArtifactAssessment.content.author` | `author` | ArtifactAssessment.content.author | Who authored the content | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `ArtifactAssessment.content.classifier` | `ArtifactAssessment.content.classifier` | `classifier` | ArtifactAssessment.content.classifier | Rating, classifier, or assessment | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/certainty-rating` |
| `ArtifactAssessment.content.component` | `ArtifactAssessment.content.component` | `component` | ArtifactAssessment.content.component | Contained content | 0..* | ArtifactAssessment.content |  |  |
| `ArtifactAssessment.content.extension` | `ArtifactAssessment.content.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ArtifactAssessment.content.freeToShare` | `ArtifactAssessment.content.freeToShare` | `freeToShare` | ArtifactAssessment.content.freeToShare | Acceptable to publicly share the resource content | 0..1 | boolean |  |  |
| `ArtifactAssessment.content.id` | `ArtifactAssessment.content.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ArtifactAssessment.content.informationType` | `ArtifactAssessment.content.informationType` | `informationType` | ArtifactAssessment.content.informationType | comment \| classifier \| rating \| container \| response \| change-request | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/artifactassessment-information-type|5.0.0` |
| `ArtifactAssessment.content.modifierExtension` | `ArtifactAssessment.content.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ArtifactAssessment.content.path` | `ArtifactAssessment.content.path` | `path` | ArtifactAssessment.content.path | What the comment is directed to | 0..* | uri |  |  |
| `ArtifactAssessment.content.quantity` | `ArtifactAssessment.content.quantity` | `quantity` | ArtifactAssessment.content.quantity | Quantitative rating | 0..1 | Quantity |  |  |
| `ArtifactAssessment.content.relatedArtifact` | `ArtifactAssessment.content.relatedArtifact` | `relatedArtifact` | ArtifactAssessment.content.relatedArtifact | Additional information | 0..* | RelatedArtifact |  |  |
| `ArtifactAssessment.content.summary` | `ArtifactAssessment.content.summary` | `summary` | ArtifactAssessment.content.summary | Brief summary of the content | 0..1 | markdown |  |  |
| `ArtifactAssessment.content.type` | `ArtifactAssessment.content.type` | `type` | ArtifactAssessment.content.type | What type of content | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/certainty-type` |
| `ArtifactAssessment.copyright` | `ArtifactAssessment.copyright` | `copyright` | ArtifactAssessment.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `ArtifactAssessment.date` | `ArtifactAssessment.date` | `date` | ArtifactAssessment.date | Date last changed | 0..1 | dateTime |  |  |
| `ArtifactAssessment.disposition` | `ArtifactAssessment.disposition` | `disposition` | ArtifactAssessment.disposition | unresolved \| not-persuasive \| persuasive \| persuasive-with-modification \| not-persuasive-with-modification | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/artifactassessment-disposition|5.0.0` |
| `ArtifactAssessment.extension` | `ArtifactAssessment.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ArtifactAssessment.id` | `ArtifactAssessment.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ArtifactAssessment.identifier` | `ArtifactAssessment.identifier` | `identifier` | ArtifactAssessment.identifier | Additional identifier for the artifact assessment | 0..* | Identifier |  |  |
| `ArtifactAssessment.implicitRules` | `ArtifactAssessment.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ArtifactAssessment.language` | `ArtifactAssessment.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `ArtifactAssessment.lastReviewDate` | `ArtifactAssessment.lastReviewDate` | `lastReviewDate` | ArtifactAssessment.lastReviewDate | When the artifact assessment was last reviewed by the publisher | 0..1 | date |  |  |
| `ArtifactAssessment.meta` | `ArtifactAssessment.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ArtifactAssessment.modifierExtension` | `ArtifactAssessment.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ArtifactAssessment.text` | `ArtifactAssessment.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ArtifactAssessment.title` | `ArtifactAssessment.title` | `title` | ArtifactAssessment.title | A short title for the assessment for use in displaying and selecting | 0..1 | string |  |  |
| `ArtifactAssessment.workflowStatus` | `ArtifactAssessment.workflowStatus` | `workflowStatus` | ArtifactAssessment.workflowStatus | submitted \| triaged \| waiting-for-input \| resolved-no-change \| resolved-change-required \| deferred \| duplicate \| applied \| published \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/artifactassessment-workflow-status|5.0.0` |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

