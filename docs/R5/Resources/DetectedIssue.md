Comparison of 
Generated at Monday, April 14, 2025 6:17:50 PM

### DetectedIssue

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | DetectedIssue |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DetectedIssue` |
| Version | 5.0.0 |
| Description | Indicates an actual or potential clinical issue with or between one or more active or proposed clinical actions for a patient; e.g. Drug-drug interaction, Ineffective treatment frequency, Procedure-condition conflict, gaps in care, etc. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2287` |
| Database Snapshot Count | `35` |
| Database Differential Count | `21` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DetectedIssue` | `DetectedIssue` | `DetectedIssue` | DetectedIssue | Clinical issue with action | 0..* | DetectedIssue |  |  |
| `DetectedIssue.author` | `DetectedIssue.author` | `author` | DetectedIssue.author | The provider or device that identified the issue | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `DetectedIssue.category` | `DetectedIssue.category` | `category` | DetectedIssue.category | Type of detected issue, e.g. drug-drug, duplicate therapy, etc | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/detectedissue-category` |
| `DetectedIssue.code` | `DetectedIssue.code` | `code` | DetectedIssue.code | Specific type of detected issue, e.g. drug-drug, duplicate therapy, etc | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/detectedissue-category` |
| `DetectedIssue.contained` | `DetectedIssue.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DetectedIssue.detail` | `DetectedIssue.detail` | `detail` | DetectedIssue.detail | Description and context | 0..1 | markdown |  |  |
| `DetectedIssue.encounter` | `DetectedIssue.encounter` | `encounter` | DetectedIssue.encounter | Encounter detected issue is part of | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `DetectedIssue.evidence` | `DetectedIssue.evidence` | `evidence` | DetectedIssue.evidence | Supporting evidence | 0..* | BackboneElement |  |  |
| `DetectedIssue.evidence.code` | `DetectedIssue.evidence.code` | `code` | DetectedIssue.evidence.code | Manifestation | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/manifestation-or-symptom` |
| `DetectedIssue.evidence.detail` | `DetectedIssue.evidence.detail` | `detail` | DetectedIssue.evidence.detail | Supporting information | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `DetectedIssue.evidence.extension` | `DetectedIssue.evidence.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DetectedIssue.evidence.id` | `DetectedIssue.evidence.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DetectedIssue.evidence.modifierExtension` | `DetectedIssue.evidence.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DetectedIssue.extension` | `DetectedIssue.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DetectedIssue.id` | `DetectedIssue.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DetectedIssue.identified[x]` | `DetectedIssue.identified[x]` | `identified[x]` | DetectedIssue.identified[x] | When identified | 0..1 | dateTime, Period |  |  |
| `DetectedIssue.identifier` | `DetectedIssue.identifier` | `identifier` | DetectedIssue.identifier | Unique id for the detected issue | 0..* | Identifier |  |  |
| `DetectedIssue.implicated` | `DetectedIssue.implicated` | `implicated` | DetectedIssue.implicated | Problem resource | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `DetectedIssue.implicitRules` | `DetectedIssue.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DetectedIssue.language` | `DetectedIssue.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `DetectedIssue.meta` | `DetectedIssue.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DetectedIssue.mitigation` | `DetectedIssue.mitigation` | `mitigation` | DetectedIssue.mitigation | Step taken to address | 0..* | BackboneElement |  |  |
| `DetectedIssue.mitigation.action` | `DetectedIssue.mitigation.action` | `action` | DetectedIssue.mitigation.action | What mitigation? | 1..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/detectedissue-mitigation-action` |
| `DetectedIssue.mitigation.author` | `DetectedIssue.mitigation.author` | `author` | DetectedIssue.mitigation.author | Who is committing? | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `DetectedIssue.mitigation.date` | `DetectedIssue.mitigation.date` | `date` | DetectedIssue.mitigation.date | Date committed | 0..1 | dateTime |  |  |
| `DetectedIssue.mitigation.extension` | `DetectedIssue.mitigation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DetectedIssue.mitigation.id` | `DetectedIssue.mitigation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DetectedIssue.mitigation.modifierExtension` | `DetectedIssue.mitigation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DetectedIssue.mitigation.note` | `DetectedIssue.mitigation.note` | `note` | DetectedIssue.mitigation.note | Additional notes about the mitigation | 0..* | Annotation |  |  |
| `DetectedIssue.modifierExtension` | `DetectedIssue.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DetectedIssue.reference` | `DetectedIssue.reference` | `reference` | DetectedIssue.reference | Authority for issue | 0..1 | uri |  |  |
| `DetectedIssue.severity` | `DetectedIssue.severity` | `severity` | DetectedIssue.severity | high \| moderate \| low | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/detectedissue-severity|5.0.0` |
| `DetectedIssue.status` | `DetectedIssue.status` | `status` | DetectedIssue.status | preliminary \| final \| entered-in-error \| mitigated | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/detectedissue-status|5.0.0` |
| `DetectedIssue.subject` | `DetectedIssue.subject` | `subject` | DetectedIssue.subject | Associated subject | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/NutritionProduct), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/Procedure), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `DetectedIssue.text` | `DetectedIssue.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DetectedIssue](/docs/R2/Resources/DetectedIssue.md)<br/> `http://hl7.org/fhir/StructureDefinition/DetectedIssue\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `96`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `263`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DetectedIssue](/docs/R3/Resources/DetectedIssue.md)<br/> `http://hl7.org/fhir/StructureDefinition/DetectedIssue\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `446`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `641`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DetectedIssue](/docs/R4/Resources/DetectedIssue.md)<br/> `http://hl7.org/fhir/StructureDefinition/DetectedIssue\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1453`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1454`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DetectedIssue](/docs/R4B/Resources/DetectedIssue.md)<br/> `http://hl7.org/fhir/StructureDefinition/DetectedIssue\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `961`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1190`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DetectedIssue](/docs/R5/Resources/DetectedIssue.md)<br/> `http://hl7.org/fhir/StructureDefinition/DetectedIssue\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DetectedIssue from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 DetectedIssue](/docs/R2/Resources/DetectedIssue.md)| Relationship | [R3 DetectedIssue](/docs/R3/Resources/DetectedIssue.md)| Relationship | [R4 DetectedIssue](/docs/R4/Resources/DetectedIssue.md)| Relationship | [R4B DetectedIssue](/docs/R4B/Resources/DetectedIssue.md)| Relationship | R5 DetectedIssue
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `DetectedIssue`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4440)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4441)| `DetectedIssue`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12819)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12820)| `DetectedIssue`| _Equivalent_<br/>(25378/25379)| `DetectedIssue`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40364)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40365)| **`DetectedIssue`**
| `DetectedIssue.id`| _Equivalent_<br/>(4442/4443)| `DetectedIssue.id`| _Equivalent_<br/>(12821/12822)| `DetectedIssue.id`| _Equivalent_<br/>(25380/25381)| `DetectedIssue.id`| _Equivalent_<br/>(40366/40367)| **`DetectedIssue.id`**
| `DetectedIssue.meta`| _Equivalent_<br/>(4444/4445)| `DetectedIssue.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12823)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12824)| `DetectedIssue.meta`| _Equivalent_<br/>(25382/25383)| `DetectedIssue.meta`| _Equivalent_<br/>(40368/40369)| **`DetectedIssue.meta`**
| `DetectedIssue.implicitRules`| _Equivalent_<br/>(4446/4447)| `DetectedIssue.implicitRules`| _Equivalent_<br/>(12825/12826)| `DetectedIssue.implicitRules`| _Equivalent_<br/>(25384/25385)| `DetectedIssue.implicitRules`| _Equivalent_<br/>(40370/40371)| **`DetectedIssue.implicitRules`**
| `DetectedIssue.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4448)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4449)| `DetectedIssue.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12827)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12828)| `DetectedIssue.language`| _Equivalent_<br/>(25386/25387)| `DetectedIssue.language`| _Equivalent_<br/>(40372/40373)| **`DetectedIssue.language`**
| `DetectedIssue.text`| _Equivalent_<br/>(4450/4451)| `DetectedIssue.text`| _Equivalent_<br/>(12829/12830)| `DetectedIssue.text`| _Equivalent_<br/>(25388/25389)| `DetectedIssue.text`| _Equivalent_<br/>(40374/40375)| **`DetectedIssue.text`**
| `DetectedIssue.contained`| _Equivalent_<br/>(4452/4453)| `DetectedIssue.contained`| _Equivalent_<br/>(12831/12832)| `DetectedIssue.contained`| _Equivalent_<br/>(25390/25391)| `DetectedIssue.contained`| _Equivalent_<br/>(40376/40377)| **`DetectedIssue.contained`**
| `DetectedIssue.extension`| _Equivalent_<br/>(4454/4455)| `DetectedIssue.extension`| _Equivalent_<br/>(12833/12834)| `DetectedIssue.extension`| _Equivalent_<br/>(25392/25393)| `DetectedIssue.extension`| _Equivalent_<br/>(40378/40379)| **`DetectedIssue.extension`**
| `DetectedIssue.modifierExtension`| _Equivalent_<br/>(4456/4457)| `DetectedIssue.modifierExtension`| _Equivalent_<br/>(12835/12836)| `DetectedIssue.modifierExtension`| _Equivalent_<br/>(25394/25395)| `DetectedIssue.modifierExtension`| _Equivalent_<br/>(40380/40381)| **`DetectedIssue.modifierExtension`**
| `DetectedIssue.identifier`| _Equivalent_<br/>(4472/4473)| `DetectedIssue.identifier`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12837)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12838)| `DetectedIssue.identifier`| _Equivalent_<br/>(25396/25397)| `DetectedIssue.identifier`| _Equivalent_<br/>(40382/40383)| **`DetectedIssue.identifier`**
| | | `DetectedIssue.status`| _Equivalent_<br/>(12839/12840)| `DetectedIssue.status`| _Equivalent_<br/>(25398/25399)| `DetectedIssue.status`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40384)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40385)| **`DetectedIssue.status`**
| | | | | | | | | **`DetectedIssue.category`**
| `DetectedIssue.category`| _Equivalent_<br/>(4460/4461)| `DetectedIssue.category`| _Equivalent_<br/>(984/1472)| `DetectedIssue.code`| _Equivalent_<br/>(25400/25401)| `DetectedIssue.code`| _Equivalent_<br/>(40386/40387)| **`DetectedIssue.code`**
| `DetectedIssue.severity`| _Equivalent_<br/>(4462/4463)| `DetectedIssue.severity`| _Equivalent_<br/>(12841/12842)| `DetectedIssue.severity`| _Equivalent_<br/>(25402/25403)| `DetectedIssue.severity`| _Equivalent_<br/>(40388/40389)| **`DetectedIssue.severity`**
| `DetectedIssue.patient`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4458)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4459)| `DetectedIssue.patient`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12843)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12844)| `DetectedIssue.patient`| _Equivalent_<br/>(25404/25405)| `DetectedIssue.patient`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1868)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2111)| **`DetectedIssue.subject`**
| | | | | | | | | **`DetectedIssue.encounter`**
| `DetectedIssue.date`| _Equivalent_<br/>(4468/4469)| `DetectedIssue.date`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(985)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1473)| `DetectedIssue.identified[x]`| _Equivalent_<br/>(25406/25407)| `DetectedIssue.identified[x]`| _Equivalent_<br/>(40390/40391)| **`DetectedIssue.identified[x]`**
| `DetectedIssue.author`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4470)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4471)| `DetectedIssue.author`| →→→→ _RelatedTo_ →→→→ <br/>(12845)<hr/>←←←← _RelatedTo_ ←←←← <br/>(12846)| `DetectedIssue.author`| _Equivalent_<br/>(25408/25409)| `DetectedIssue.author`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40392)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(40393)| **`DetectedIssue.author`**
| `DetectedIssue.implicated`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4464)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4465)| `DetectedIssue.implicated`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12847)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12848)| `DetectedIssue.implicated`| _Equivalent_<br/>(25410/25411)| `DetectedIssue.implicated`| _Equivalent_<br/>(40394/40395)| **`DetectedIssue.implicated`**
| | | | | `DetectedIssue.evidence`| _Equivalent_<br/>(25412/25413)| `DetectedIssue.evidence`| _Equivalent_<br/>(40396/40397)| **`DetectedIssue.evidence`**
| | | | | `DetectedIssue.evidence.id`| _Equivalent_<br/>(25414/25415)| `DetectedIssue.evidence.id`| _Equivalent_<br/>(40398/40399)| **`DetectedIssue.evidence.id`**
| | | | | `DetectedIssue.evidence.extension`| _Equivalent_<br/>(25416/25417)| `DetectedIssue.evidence.extension`| _Equivalent_<br/>(40400/40401)| **`DetectedIssue.evidence.extension`**
| | | | | `DetectedIssue.evidence.modifierExtension`| _Equivalent_<br/>(25418/25419)| `DetectedIssue.evidence.modifierExtension`| _Equivalent_<br/>(40402/40403)| **`DetectedIssue.evidence.modifierExtension`**
| | | | | `DetectedIssue.evidence.code`| _Equivalent_<br/>(25420/25421)| `DetectedIssue.evidence.code`| _Equivalent_<br/>(40404/40405)| **`DetectedIssue.evidence.code`**
| | | | | `DetectedIssue.evidence.detail`| _Equivalent_<br/>(25422/25423)| `DetectedIssue.evidence.detail`| _Equivalent_<br/>(40406/40407)| **`DetectedIssue.evidence.detail`**
| `DetectedIssue.detail`| _Equivalent_<br/>(4466/4467)| `DetectedIssue.detail`| _Equivalent_<br/>(12849/12850)| `DetectedIssue.detail`| _Equivalent_<br/>(25424/25425)| `DetectedIssue.detail`| _Equivalent_<br/>(40408/40409)| **`DetectedIssue.detail`**
| `DetectedIssue.reference`| _Equivalent_<br/>(4474/4475)| `DetectedIssue.reference`| _Equivalent_<br/>(12851/12852)| `DetectedIssue.reference`| _Equivalent_<br/>(25426/25427)| `DetectedIssue.reference`| _Equivalent_<br/>(40410/40411)| **`DetectedIssue.reference`**
| `DetectedIssue.mitigation`| _Equivalent_<br/>(4476/4477)| `DetectedIssue.mitigation`| _Equivalent_<br/>(12853/12854)| `DetectedIssue.mitigation`| _Equivalent_<br/>(25428/25429)| `DetectedIssue.mitigation`| _Equivalent_<br/>(40412/40413)| **`DetectedIssue.mitigation`**
| `DetectedIssue.mitigation.id`| _Equivalent_<br/>(4478/4479)| `DetectedIssue.mitigation.id`| _Equivalent_<br/>(12855/12856)| `DetectedIssue.mitigation.id`| _Equivalent_<br/>(25430/25431)| `DetectedIssue.mitigation.id`| _Equivalent_<br/>(40414/40415)| **`DetectedIssue.mitigation.id`**
| `DetectedIssue.mitigation.extension`| _Equivalent_<br/>(4480/4481)| `DetectedIssue.mitigation.extension`| _Equivalent_<br/>(12857/12858)| `DetectedIssue.mitigation.extension`| _Equivalent_<br/>(25432/25433)| `DetectedIssue.mitigation.extension`| _Equivalent_<br/>(40416/40417)| **`DetectedIssue.mitigation.extension`**
| `DetectedIssue.mitigation.modifierExtension`| _Equivalent_<br/>(4482/4483)| `DetectedIssue.mitigation.modifierExtension`| _Equivalent_<br/>(12859/12860)| `DetectedIssue.mitigation.modifierExtension`| _Equivalent_<br/>(25434/25435)| `DetectedIssue.mitigation.modifierExtension`| _Equivalent_<br/>(40418/40419)| **`DetectedIssue.mitigation.modifierExtension`**
| `DetectedIssue.mitigation.action`| _Equivalent_<br/>(4484/4485)| `DetectedIssue.mitigation.action`| _Equivalent_<br/>(12861/12862)| `DetectedIssue.mitigation.action`| _Equivalent_<br/>(25436/25437)| `DetectedIssue.mitigation.action`| _Equivalent_<br/>(40420/40421)| **`DetectedIssue.mitigation.action`**
| `DetectedIssue.mitigation.date`| _Equivalent_<br/>(4486/4487)| `DetectedIssue.mitigation.date`| _Equivalent_<br/>(12863/12864)| `DetectedIssue.mitigation.date`| _Equivalent_<br/>(25438/25439)| `DetectedIssue.mitigation.date`| _Equivalent_<br/>(40422/40423)| **`DetectedIssue.mitigation.date`**
| `DetectedIssue.mitigation.author`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4488)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4489)| `DetectedIssue.mitigation.author`| →→→→ _RelatedTo_ →→→→ <br/>(12865)<hr/>←←←← _RelatedTo_ ←←←← <br/>(12866)| `DetectedIssue.mitigation.author`| _Equivalent_<br/>(25440/25441)| `DetectedIssue.mitigation.author`| _Equivalent_<br/>(40424/40425)| **`DetectedIssue.mitigation.author`**
| | | | | | | | | **`DetectedIssue.mitigation.note`**
| *25 of 25 elements used* | | *26 of 26 elements used* | | *32 of 32 elements used* | | *32 of 32 elements used* | | *35 of 35 elements used* 

