Comparison of 
Generated at Tuesday, April 1, 2025 1:39:37 PM

### ResearchStudy

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | ResearchStudy |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ResearchStudy` |
| Version | 5.0.0 |
| Description | A scientific study of nature that sometimes includes processes involved in health and disease. For example, clinical trials are research studies that involve people. These studies may be related to new ways to screen, prevent, diagnose, and treat disease. They may also study certain outcomes and certain groups of people by looking at data collected in the past or future. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2375` |
| Database Snapshot Count | `89` |
| Database Differential Count | `60` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ResearchStudy` | `ResearchStudy` | `ResearchStudy` | ResearchStudy | Investigation to increase healthcare-related patient-independent knowledge | 0..* | ResearchStudy |  |  |
| `ResearchStudy.associatedParty` | `ResearchStudy.associatedParty` | `associatedParty` | ResearchStudy.associatedParty | Sponsors, collaborators, and other parties | 0..* | BackboneElement |  |  |
| `ResearchStudy.associatedParty.classifier` | `ResearchStudy.associatedParty.classifier` | `classifier` | ResearchStudy.associatedParty.classifier | nih \| fda \| government \| nonprofit \| academic \| industry | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/research-study-party-organization-type` |
| `ResearchStudy.associatedParty.extension` | `ResearchStudy.associatedParty.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ResearchStudy.associatedParty.id` | `ResearchStudy.associatedParty.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ResearchStudy.associatedParty.modifierExtension` | `ResearchStudy.associatedParty.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ResearchStudy.associatedParty.name` | `ResearchStudy.associatedParty.name` | `name` | ResearchStudy.associatedParty.name | Name of associated party | 0..1 | string |  |  |
| `ResearchStudy.associatedParty.party` | `ResearchStudy.associatedParty.party` | `party` | ResearchStudy.associatedParty.party | Individual or organization associated with study (use practitionerRole to specify their organisation) | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `ResearchStudy.associatedParty.period` | `ResearchStudy.associatedParty.period` | `period` | ResearchStudy.associatedParty.period | When active in the role | 0..* | Period |  |  |
| `ResearchStudy.associatedParty.role` | `ResearchStudy.associatedParty.role` | `role` | ResearchStudy.associatedParty.role | sponsor \| lead-sponsor \| sponsor-investigator \| primary-investigator \| collaborator \| funding-source \| general-contact \| recruitment-contact \| sub-investigator \| study-director \| study-chair | 1..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/research-study-party-role` |
| `ResearchStudy.classifier` | `ResearchStudy.classifier` | `classifier` | ResearchStudy.classifier | Classification for the study | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/research-study-classifiers` |
| `ResearchStudy.comparisonGroup` | `ResearchStudy.comparisonGroup` | `comparisonGroup` | ResearchStudy.comparisonGroup | Defined path through the study for a subject | 0..* | BackboneElement |  |  |
| `ResearchStudy.comparisonGroup.description` | `ResearchStudy.comparisonGroup.description` | `description` | ResearchStudy.comparisonGroup.description | Short explanation of study path | 0..1 | markdown |  |  |
| `ResearchStudy.comparisonGroup.extension` | `ResearchStudy.comparisonGroup.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ResearchStudy.comparisonGroup.id` | `ResearchStudy.comparisonGroup.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ResearchStudy.comparisonGroup.intendedExposure` | `ResearchStudy.comparisonGroup.intendedExposure` | `intendedExposure` | ResearchStudy.comparisonGroup.intendedExposure | Interventions or exposures in this comparisonGroup or cohort | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable) |  |  |
| `ResearchStudy.comparisonGroup.linkId` | `ResearchStudy.comparisonGroup.linkId` | `linkId` | ResearchStudy.comparisonGroup.linkId | Allows the comparisonGroup for the study and the comparisonGroup for the subject to be linked easily | 0..1 | id |  |  |
| `ResearchStudy.comparisonGroup.modifierExtension` | `ResearchStudy.comparisonGroup.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ResearchStudy.comparisonGroup.name` | `ResearchStudy.comparisonGroup.name` | `name` | ResearchStudy.comparisonGroup.name | Label for study comparisonGroup | 1..1 | string |  |  |
| `ResearchStudy.comparisonGroup.observedGroup` | `ResearchStudy.comparisonGroup.observedGroup` | `observedGroup` | ResearchStudy.comparisonGroup.observedGroup | Group of participants who were enrolled in study comparisonGroup | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group) |  |  |
| `ResearchStudy.comparisonGroup.type` | `ResearchStudy.comparisonGroup.type` | `type` | ResearchStudy.comparisonGroup.type | Categorization of study comparisonGroup | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/research-study-arm-type` |
| `ResearchStudy.condition` | `ResearchStudy.condition` | `condition` | ResearchStudy.condition | Condition being studied | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/condition-code` |
| `ResearchStudy.contained` | `ResearchStudy.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ResearchStudy.date` | `ResearchStudy.date` | `date` | ResearchStudy.date | Date the resource last changed | 0..1 | dateTime |  |  |
| `ResearchStudy.description` | `ResearchStudy.description` | `description` | ResearchStudy.description | Detailed narrative of the study | 0..1 | markdown |  |  |
| `ResearchStudy.descriptionSummary` | `ResearchStudy.descriptionSummary` | `descriptionSummary` | ResearchStudy.descriptionSummary | Brief text explaining the study | 0..1 | markdown |  |  |
| `ResearchStudy.extension` | `ResearchStudy.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ResearchStudy.focus` | `ResearchStudy.focus` | `focus` | ResearchStudy.focus | Drugs, devices, etc. under study | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable), CodeableReference(http://hl7.org/fhir/StructureDefinition/Medication), CodeableReference(http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition), CodeableReference(http://hl7.org/fhir/StructureDefinition/SubstanceDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/research-study-focus-type` |
| `ResearchStudy.id` | `ResearchStudy.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ResearchStudy.identifier` | `ResearchStudy.identifier` | `identifier` | ResearchStudy.identifier | Business Identifier for study | 0..* | Identifier |  |  |
| `ResearchStudy.implicitRules` | `ResearchStudy.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ResearchStudy.keyword` | `ResearchStudy.keyword` | `keyword` | ResearchStudy.keyword | Used to search for the study | 0..* | CodeableConcept | `Example` |  |
| `ResearchStudy.label` | `ResearchStudy.label` | `label` | ResearchStudy.label | Additional names for the study | 0..* | BackboneElement |  |  |
| `ResearchStudy.label.extension` | `ResearchStudy.label.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ResearchStudy.label.id` | `ResearchStudy.label.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ResearchStudy.label.modifierExtension` | `ResearchStudy.label.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ResearchStudy.label.type` | `ResearchStudy.label.type` | `type` | ResearchStudy.label.type | primary \| official \| scientific \| plain-language \| subtitle \| short-title \| acronym \| earlier-title \| language \| auto-translated \| human-use \| machine-use \| duplicate-uid | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/title-type` |
| `ResearchStudy.label.value` | `ResearchStudy.label.value` | `value` | ResearchStudy.label.value | The name | 0..1 | string |  |  |
| `ResearchStudy.language` | `ResearchStudy.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `ResearchStudy.meta` | `ResearchStudy.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ResearchStudy.modifierExtension` | `ResearchStudy.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ResearchStudy.name` | `ResearchStudy.name` | `name` | ResearchStudy.name | Name for this study (computer friendly) | 0..1 | string |  |  |
| `ResearchStudy.note` | `ResearchStudy.note` | `note` | ResearchStudy.note | Comments made about the study | 0..* | Annotation |  |  |
| `ResearchStudy.objective` | `ResearchStudy.objective` | `objective` | ResearchStudy.objective | A goal for the study | 0..* | BackboneElement |  |  |
| `ResearchStudy.objective.description` | `ResearchStudy.objective.description` | `description` | ResearchStudy.objective.description | Description of the objective | 0..1 | markdown |  |  |
| `ResearchStudy.objective.extension` | `ResearchStudy.objective.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ResearchStudy.objective.id` | `ResearchStudy.objective.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ResearchStudy.objective.modifierExtension` | `ResearchStudy.objective.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ResearchStudy.objective.name` | `ResearchStudy.objective.name` | `name` | ResearchStudy.objective.name | Label for the objective | 0..1 | string |  |  |
| `ResearchStudy.objective.type` | `ResearchStudy.objective.type` | `type` | ResearchStudy.objective.type | primary \| secondary \| exploratory | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/research-study-objective-type` |
| `ResearchStudy.outcomeMeasure` | `ResearchStudy.outcomeMeasure` | `outcomeMeasure` | ResearchStudy.outcomeMeasure | A variable measured during the study | 0..* | BackboneElement |  |  |
| `ResearchStudy.outcomeMeasure.description` | `ResearchStudy.outcomeMeasure.description` | `description` | ResearchStudy.outcomeMeasure.description | Description of the outcome | 0..1 | markdown |  |  |
| `ResearchStudy.outcomeMeasure.extension` | `ResearchStudy.outcomeMeasure.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ResearchStudy.outcomeMeasure.id` | `ResearchStudy.outcomeMeasure.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ResearchStudy.outcomeMeasure.modifierExtension` | `ResearchStudy.outcomeMeasure.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ResearchStudy.outcomeMeasure.name` | `ResearchStudy.outcomeMeasure.name` | `name` | ResearchStudy.outcomeMeasure.name | Label for the outcome | 0..1 | string |  |  |
| `ResearchStudy.outcomeMeasure.reference` | `ResearchStudy.outcomeMeasure.reference` | `reference` | ResearchStudy.outcomeMeasure.reference | Structured outcome definition | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable) |  |  |
| `ResearchStudy.outcomeMeasure.type` | `ResearchStudy.outcomeMeasure.type` | `type` | ResearchStudy.outcomeMeasure.type | primary \| secondary \| exploratory | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/research-study-objective-type` |
| `ResearchStudy.partOf` | `ResearchStudy.partOf` | `partOf` | ResearchStudy.partOf | Part of larger study | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ResearchStudy) |  |  |
| `ResearchStudy.period` | `ResearchStudy.period` | `period` | ResearchStudy.period | When the study began and ended | 0..1 | Period |  |  |
| `ResearchStudy.phase` | `ResearchStudy.phase` | `phase` | ResearchStudy.phase | n-a \| early-phase-1 \| phase-1 \| phase-1-phase-2 \| phase-2 \| phase-2-phase-3 \| phase-3 \| phase-4 | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/research-study-phase` |
| `ResearchStudy.primaryPurposeType` | `ResearchStudy.primaryPurposeType` | `primaryPurposeType` | ResearchStudy.primaryPurposeType | treatment \| prevention \| diagnostic \| supportive-care \| screening \| health-services-research \| basic-science \| device-feasibility | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/research-study-prim-purp-type` |
| `ResearchStudy.progressStatus` | `ResearchStudy.progressStatus` | `progressStatus` | ResearchStudy.progressStatus | Status of study with time for that status | 0..* | BackboneElement |  |  |
| `ResearchStudy.progressStatus.actual` | `ResearchStudy.progressStatus.actual` | `actual` | ResearchStudy.progressStatus.actual | Actual if true else anticipated | 0..1 | boolean |  |  |
| `ResearchStudy.progressStatus.extension` | `ResearchStudy.progressStatus.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ResearchStudy.progressStatus.id` | `ResearchStudy.progressStatus.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ResearchStudy.progressStatus.modifierExtension` | `ResearchStudy.progressStatus.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ResearchStudy.progressStatus.period` | `ResearchStudy.progressStatus.period` | `period` | ResearchStudy.progressStatus.period | Date range | 0..1 | Period |  |  |
| `ResearchStudy.progressStatus.state` | `ResearchStudy.progressStatus.state` | `state` | ResearchStudy.progressStatus.state | Label for status or state (e.g. recruitment status) | 1..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/research-study-status` |
| `ResearchStudy.protocol` | `ResearchStudy.protocol` | `protocol` | ResearchStudy.protocol | Steps followed in executing study | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/PlanDefinition) |  |  |
| `ResearchStudy.recruitment` | `ResearchStudy.recruitment` | `recruitment` | ResearchStudy.recruitment | Target or actual group of participants enrolled in study | 0..1 | BackboneElement |  |  |
| `ResearchStudy.recruitment.actualGroup` | `ResearchStudy.recruitment.actualGroup` | `actualGroup` | ResearchStudy.recruitment.actualGroup | Group of participants who were enrolled in study | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group) |  |  |
| `ResearchStudy.recruitment.actualNumber` | `ResearchStudy.recruitment.actualNumber` | `actualNumber` | ResearchStudy.recruitment.actualNumber | Actual total number of participants enrolled in study | 0..1 | unsignedInt |  |  |
| `ResearchStudy.recruitment.eligibility` | `ResearchStudy.recruitment.eligibility` | `eligibility` | ResearchStudy.recruitment.eligibility | Inclusion and exclusion criteria | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable), Reference(http://hl7.org/fhir/StructureDefinition/Group) |  |  |
| `ResearchStudy.recruitment.extension` | `ResearchStudy.recruitment.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ResearchStudy.recruitment.id` | `ResearchStudy.recruitment.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ResearchStudy.recruitment.modifierExtension` | `ResearchStudy.recruitment.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ResearchStudy.recruitment.targetNumber` | `ResearchStudy.recruitment.targetNumber` | `targetNumber` | ResearchStudy.recruitment.targetNumber | Estimated total number of participants to be enrolled | 0..1 | unsignedInt |  |  |
| `ResearchStudy.region` | `ResearchStudy.region` | `region` | ResearchStudy.region | Geographic area for the study | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `ResearchStudy.relatedArtifact` | `ResearchStudy.relatedArtifact` | `relatedArtifact` | ResearchStudy.relatedArtifact | References, URLs, and attachments | 0..* | RelatedArtifact |  |  |
| `ResearchStudy.result` | `ResearchStudy.result` | `result` | ResearchStudy.result | Link to results generated during the study | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Citation), Reference(http://hl7.org/fhir/StructureDefinition/DiagnosticReport), Reference(http://hl7.org/fhir/StructureDefinition/EvidenceReport) |  |  |
| `ResearchStudy.site` | `ResearchStudy.site` | `site` | ResearchStudy.site | Facility where study activities are conducted | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/ResearchStudy) |  |  |
| `ResearchStudy.status` | `ResearchStudy.status` | `status` | ResearchStudy.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `ResearchStudy.studyDesign` | `ResearchStudy.studyDesign` | `studyDesign` | ResearchStudy.studyDesign | Classifications of the study design characteristics | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/study-design` |
| `ResearchStudy.text` | `ResearchStudy.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ResearchStudy.title` | `ResearchStudy.title` | `title` | ResearchStudy.title | Human readable name of the study | 0..1 | string |  |  |
| `ResearchStudy.url` | `ResearchStudy.url` | `url` | ResearchStudy.url | Canonical identifier for this study resource | 0..1 | uri |  |  |
| `ResearchStudy.version` | `ResearchStudy.version` | `version` | ResearchStudy.version | The business version for the study record | 0..1 | string |  |  |
| `ResearchStudy.whyStopped` | `ResearchStudy.whyStopped` | `whyStopped` | ResearchStudy.whyStopped | accrual-goal-met \| closed-due-to-toxicity \| closed-due-to-lack-of-study-progress \| temporarily-closed-per-study-design | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/research-study-reason-stopped` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ResearchStudy](/docs/R3/Resources/ResearchStudy.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchStudy\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `510`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `702`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ResearchStudy](/docs/R4/Resources/ResearchStudy.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchStudy\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1601`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1602`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ResearchStudy](/docs/R4B/Resources/ResearchStudy.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchStudy\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1035`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1264`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ResearchStudy](/docs/R5/Resources/ResearchStudy.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchStudy\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ResearchStudy from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 ResearchStudy](/docs/R3/Resources/ResearchStudy.md)| Relationship | [R4 ResearchStudy](/docs/R4/Resources/ResearchStudy.md)| Relationship | [R4B ResearchStudy](/docs/R4B/Resources/ResearchStudy.md)| Relationship | R5 ResearchStudy
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `ResearchStudy`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18039)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18040)| `ResearchStudy`| _Equivalent_<br/>(32658/32659)| `ResearchStudy`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47009)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47010)| **`ResearchStudy`**
| | | `ResearchStudy.id`| _Equivalent_<br/>(18041/18042)| `ResearchStudy.id`| _Equivalent_<br/>(32660/32661)| `ResearchStudy.id`| _Equivalent_<br/>(47011/47012)| **`ResearchStudy.id`**
| | | `ResearchStudy.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18043)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18044)| `ResearchStudy.meta`| _Equivalent_<br/>(32662/32663)| `ResearchStudy.meta`| _Equivalent_<br/>(47013/47014)| **`ResearchStudy.meta`**
| | | `ResearchStudy.implicitRules`| _Equivalent_<br/>(18045/18046)| `ResearchStudy.implicitRules`| _Equivalent_<br/>(32664/32665)| `ResearchStudy.implicitRules`| _Equivalent_<br/>(47015/47016)| **`ResearchStudy.implicitRules`**
| | | `ResearchStudy.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18047)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18048)| `ResearchStudy.language`| _Equivalent_<br/>(32666/32667)| `ResearchStudy.language`| _Equivalent_<br/>(47017/47018)| **`ResearchStudy.language`**
| | | `ResearchStudy.text`| _Equivalent_<br/>(18049/18050)| `ResearchStudy.text`| _Equivalent_<br/>(32668/32669)| `ResearchStudy.text`| _Equivalent_<br/>(47019/47020)| **`ResearchStudy.text`**
| | | `ResearchStudy.contained`| _Equivalent_<br/>(18051/18052)| `ResearchStudy.contained`| _Equivalent_<br/>(32670/32671)| `ResearchStudy.contained`| _Equivalent_<br/>(47021/47022)| **`ResearchStudy.contained`**
| | | `ResearchStudy.extension`| →→→→ _Equivalent_ →→→→ <br/>(18053)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18077)| `ResearchStudy.extension`| _Equivalent_<br/>(32672/32673)| `ResearchStudy.extension`| _Equivalent_<br/>(47023/47024)| **`ResearchStudy.extension`**
| | | `ResearchStudy.jurisdiction`| →→→→ _RelatedTo_ →→→→ <br/>(1275)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18077)| `ResearchStudy.extension`| _Equivalent_<br/>(32672/32673)| `ResearchStudy.extension`| _Equivalent_<br/>(47023/47024)| **`ResearchStudy.extension`**
| | | `ResearchStudy.modifierExtension`| _Equivalent_<br/>(18055/18056)| `ResearchStudy.modifierExtension`| _Equivalent_<br/>(32674/32675)| `ResearchStudy.modifierExtension`| _Equivalent_<br/>(47025/47026)| **`ResearchStudy.modifierExtension`**
| | | | | | | | | **`ResearchStudy.url`**
| | | `ResearchStudy.identifier`| _Equivalent_<br/>(18057/18058)| `ResearchStudy.identifier`| _Equivalent_<br/>(32676/32677)| `ResearchStudy.identifier`| _Equivalent_<br/>(47027/47028)| **`ResearchStudy.identifier`**
| | | | | | | | | **`ResearchStudy.version`**
| | | | | | | | | **`ResearchStudy.name`**
| | | `ResearchStudy.title`| _Equivalent_<br/>(18059/18060)| `ResearchStudy.title`| _Equivalent_<br/>(32678/32679)| `ResearchStudy.title`| _Equivalent_<br/>(47029/47030)| **`ResearchStudy.title`**
| | | | | | | | | **`ResearchStudy.label`**
| | | | | | | | | **`ResearchStudy.label.id`**
| | | | | | | | | **`ResearchStudy.label.extension`**
| | | | | | | | | **`ResearchStudy.label.modifierExtension`**
| | | | | | | | | **`ResearchStudy.label.type`**
| | | | | | | | | **`ResearchStudy.label.value`**
| | | `ResearchStudy.protocol`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18061)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18062)| `ResearchStudy.protocol`| _Equivalent_<br/>(32680/32681)| `ResearchStudy.protocol`| _Equivalent_<br/>(47031/47032)| **`ResearchStudy.protocol`**
| | | `ResearchStudy.partOf`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18063)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18064)| `ResearchStudy.partOf`| _Equivalent_<br/>(32682/32683)| `ResearchStudy.partOf`| _Equivalent_<br/>(47033/47034)| **`ResearchStudy.partOf`**
| | | `ResearchStudy.relatedArtifact`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18073)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18074)| `ResearchStudy.relatedArtifact`| _Equivalent_<br/>(32698/32699)| `ResearchStudy.relatedArtifact`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47047)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47048)| **`ResearchStudy.relatedArtifact`**
| | | | | | | | | **`ResearchStudy.date`**
| | | `ResearchStudy.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18065)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18066)| `ResearchStudy.status`| _Equivalent_<br/>(32684/32685)| `ResearchStudy.status`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47035)<hr/>←←←← _RelatedTo_ ←←←← <br/>(47036)| **`ResearchStudy.status`**
| | | | | `ResearchStudy.primaryPurposeType`| _Equivalent_<br/>(32686/32687)| `ResearchStudy.primaryPurposeType`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47037)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47038)| **`ResearchStudy.primaryPurposeType`**
| | | | | `ResearchStudy.phase`| _Equivalent_<br/>(32688/32689)| `ResearchStudy.phase`| _Equivalent_<br/>(47039/47040)| **`ResearchStudy.phase`**
| | | | | | | | | **`ResearchStudy.studyDesign`**
| | | `ResearchStudy.focus`| _Equivalent_<br/>(18069/18070)| `ResearchStudy.focus`| _Equivalent_<br/>(32692/32693)| `ResearchStudy.focus`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47042)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47043)| **`ResearchStudy.focus`**
| | | | | `ResearchStudy.condition`| _Equivalent_<br/>(32694/32695)| `ResearchStudy.condition`| _Equivalent_<br/>(47044/47045)| **`ResearchStudy.condition`**
| | | `ResearchStudy.keyword`| _Equivalent_<br/>(18075/18076)| `ResearchStudy.keyword`| _Equivalent_<br/>(32700/32701)| `ResearchStudy.keyword`| _Equivalent_<br/>(47049/47050)| **`ResearchStudy.keyword`**
| | | | | | | | | **`ResearchStudy.region`**
| | | | | | | | | **`ResearchStudy.descriptionSummary`**
| | | `ResearchStudy.description`| _Equivalent_<br/>(18078/18079)| `ResearchStudy.description`| _Equivalent_<br/>(32704/32705)| `ResearchStudy.description`| _Equivalent_<br/>(47052/47053)| **`ResearchStudy.description`**
| | | `ResearchStudy.period`| _Equivalent_<br/>(18082/18083)| `ResearchStudy.period`| _Equivalent_<br/>(32708/32709)| `ResearchStudy.period`| _Equivalent_<br/>(47055/47056)| **`ResearchStudy.period`**
| | | `ResearchStudy.site`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18088)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18089)| `ResearchStudy.site`| _Equivalent_<br/>(32714/32715)| `ResearchStudy.site`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47059)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47060)| **`ResearchStudy.site`**
| | | `ResearchStudy.note`| _Equivalent_<br/>(18092/18093)| `ResearchStudy.note`| _Equivalent_<br/>(32718/32719)| `ResearchStudy.note`| _Equivalent_<br/>(47062/47063)| **`ResearchStudy.note`**
| | | | | | | | | **`ResearchStudy.classifier`**
| | | | | | | | | **`ResearchStudy.associatedParty`**
| | | | | | | | | **`ResearchStudy.associatedParty.id`**
| | | | | | | | | **`ResearchStudy.associatedParty.extension`**
| | | | | | | | | **`ResearchStudy.associatedParty.modifierExtension`**
| | | | | | | | | **`ResearchStudy.associatedParty.name`**
| | | | | | | | | **`ResearchStudy.associatedParty.role`**
| | | | | | | | | **`ResearchStudy.associatedParty.period`**
| | | | | | | | | **`ResearchStudy.associatedParty.classifier`**
| | | | | | | | | **`ResearchStudy.associatedParty.party`**
| | | | | | | | | **`ResearchStudy.progressStatus`**
| | | | | | | | | **`ResearchStudy.progressStatus.id`**
| | | | | | | | | **`ResearchStudy.progressStatus.extension`**
| | | | | | | | | **`ResearchStudy.progressStatus.modifierExtension`**
| | | | | | | | | **`ResearchStudy.progressStatus.state`**
| | | | | | | | | **`ResearchStudy.progressStatus.actual`**
| | | | | | | | | **`ResearchStudy.progressStatus.period`**
| | | | | | | | | **`ResearchStudy.whyStopped`**
| | | | | | | | | **`ResearchStudy.recruitment`**
| | | | | | | | | **`ResearchStudy.recruitment.id`**
| | | | | | | | | **`ResearchStudy.recruitment.extension`**
| | | | | | | | | **`ResearchStudy.recruitment.modifierExtension`**
| | | | | | | | | **`ResearchStudy.recruitment.targetNumber`**
| | | | | | | | | **`ResearchStudy.recruitment.actualNumber`**
| | | | | | | | | **`ResearchStudy.recruitment.eligibility`**
| | | | | | | | | **`ResearchStudy.recruitment.actualGroup`**
| | | | | | | | | **`ResearchStudy.comparisonGroup`**
| | | | | | | | | **`ResearchStudy.comparisonGroup.id`**
| | | | | | | | | **`ResearchStudy.comparisonGroup.extension`**
| | | | | | | | | **`ResearchStudy.comparisonGroup.modifierExtension`**
| | | | | | | | | **`ResearchStudy.comparisonGroup.linkId`**
| | | `ResearchStudy.arm.name`| _Equivalent_<br/>(18102/18103)| `ResearchStudy.arm.name`| _Equivalent_<br/>(32728/32729)| `ResearchStudy.arm.name`| _Equivalent_<br/>(1939/2176)| **`ResearchStudy.comparisonGroup.name`**
| | | `ResearchStudy.arm.code`| _Equivalent_<br/>(1273/1658)| `ResearchStudy.arm.type`| _Equivalent_<br/>(32730/32731)| `ResearchStudy.arm.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1940)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2177)| **`ResearchStudy.comparisonGroup.type`**
| | | `ResearchStudy.arm.description`| _Equivalent_<br/>(18104/18105)| `ResearchStudy.arm.description`| _Equivalent_<br/>(32732/32733)| `ResearchStudy.arm.description`| _Equivalent_<br/>(1941/2178)| **`ResearchStudy.comparisonGroup.description`**
| | | | | | | | | **`ResearchStudy.comparisonGroup.intendedExposure`**
| | | | | | | | | **`ResearchStudy.comparisonGroup.observedGroup`**
| | | | | `ResearchStudy.objective`| _Equivalent_<br/>(32734/32735)| `ResearchStudy.objective`| _Equivalent_<br/>(47068/47069)| **`ResearchStudy.objective`**
| | | | | `ResearchStudy.objective.id`| _Equivalent_<br/>(32736/32737)| `ResearchStudy.objective.id`| _Equivalent_<br/>(47070/47071)| **`ResearchStudy.objective.id`**
| | | | | `ResearchStudy.objective.extension`| _Equivalent_<br/>(32738/32739)| `ResearchStudy.objective.extension`| _Equivalent_<br/>(47072/47073)| **`ResearchStudy.objective.extension`**
| | | | | `ResearchStudy.objective.modifierExtension`| _Equivalent_<br/>(32740/32741)| `ResearchStudy.objective.modifierExtension`| _Equivalent_<br/>(47074/47075)| **`ResearchStudy.objective.modifierExtension`**
| | | | | `ResearchStudy.objective.name`| _Equivalent_<br/>(32742/32743)| `ResearchStudy.objective.name`| _Equivalent_<br/>(47076/47077)| **`ResearchStudy.objective.name`**
| | | | | `ResearchStudy.objective.type`| _Equivalent_<br/>(32744/32745)| `ResearchStudy.objective.type`| _Equivalent_<br/>(47078/47079)| **`ResearchStudy.objective.type`**
| | | | | | | | | **`ResearchStudy.objective.description`**
| | | | | | | | | **`ResearchStudy.outcomeMeasure`**
| | | | | | | | | **`ResearchStudy.outcomeMeasure.id`**
| | | | | | | | | **`ResearchStudy.outcomeMeasure.extension`**
| | | | | | | | | **`ResearchStudy.outcomeMeasure.modifierExtension`**
| | | | | | | | | **`ResearchStudy.outcomeMeasure.name`**
| | | | | | | | | **`ResearchStudy.outcomeMeasure.type`**
| | | | | | | | | **`ResearchStudy.outcomeMeasure.description`**
| | | | | | | | | **`ResearchStudy.outcomeMeasure.reference`**
| | | | | | | | | **`ResearchStudy.result`**
| | | *25 of 35 elements used* | | *33 of 44 elements used* | | *33 of 44 elements used* | | *89 of 89 elements used* 

