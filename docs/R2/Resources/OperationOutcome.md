Comparison of 
Generated at Monday, April 14, 2025 6:17:16 PM

### OperationOutcome

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | OperationOutcome |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/OperationOutcome` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for OperationOutcome Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `104` |
| Database Snapshot Count | `18` |
| Database Differential Count | `7` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `OperationOutcome` | `OperationOutcome` | `OperationOutcome` | OperationOutcome | Information about the success/failure of an action | 0..* | OperationOutcome |  |  |
| `OperationOutcome.contained` | `OperationOutcome.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `OperationOutcome.extension` | `OperationOutcome.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `OperationOutcome.id` | `OperationOutcome.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `OperationOutcome.implicitRules` | `OperationOutcome.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `OperationOutcome.issue` | `OperationOutcome.issue` | `issue` |  | A single issue associated with the action | 1..* | BackboneElement |  |  |
| `OperationOutcome.issue.code` | `OperationOutcome.issue.code` | `code` |  | Error or warning code | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/issue-type` |
| `OperationOutcome.issue.details` | `OperationOutcome.issue.details` | `details` |  | Additional details about the error | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/operation-outcome` |
| `OperationOutcome.issue.diagnostics` | `OperationOutcome.issue.diagnostics` | `diagnostics` |  | Additional diagnostic information about the issue | 0..1 | string |  |  |
| `OperationOutcome.issue.extension` | `OperationOutcome.issue.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `OperationOutcome.issue.id` | `OperationOutcome.issue.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `OperationOutcome.issue.location` | `OperationOutcome.issue.location` | `location` |  | XPath of element(s) related to issue | 0..* | string |  |  |
| `OperationOutcome.issue.modifierExtension` | `OperationOutcome.issue.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `OperationOutcome.issue.severity` | `OperationOutcome.issue.severity` | `severity` |  | fatal \| error \| warning \| information | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/issue-severity` |
| `OperationOutcome.language` | `OperationOutcome.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `OperationOutcome.meta` | `OperationOutcome.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `OperationOutcome.modifierExtension` | `OperationOutcome.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `OperationOutcome.text` | `OperationOutcome.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [OperationOutcome](/docs/R2/Resources/OperationOutcome.md)<br/> `http://hl7.org/fhir/StructureDefinition/OperationOutcome\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `134`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `300`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [OperationOutcome](/docs/R3/Resources/OperationOutcome.md)<br/> `http://hl7.org/fhir/StructureDefinition/OperationOutcome\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `491`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `685`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [OperationOutcome](/docs/R4/Resources/OperationOutcome.md)<br/> `http://hl7.org/fhir/StructureDefinition/OperationOutcome\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1563`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1564`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [OperationOutcome](/docs/R4B/Resources/OperationOutcome.md)<br/> `http://hl7.org/fhir/StructureDefinition/OperationOutcome\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1017`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1246`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [OperationOutcome](/docs/R5/Resources/OperationOutcome.md)<br/> `http://hl7.org/fhir/StructureDefinition/OperationOutcome\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition OperationOutcome from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 OperationOutcome| Relationship | [R3 OperationOutcome](/docs/R3/Resources/OperationOutcome.md)| Relationship | [R4 OperationOutcome](/docs/R4/Resources/OperationOutcome.md)| Relationship | [R4B OperationOutcome](/docs/R4B/Resources/OperationOutcome.md)| Relationship | [R5 OperationOutcome](/docs/R5/Resources/OperationOutcome.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`OperationOutcome`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6801)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6802)| `OperationOutcome`| _Equivalent_<br/>(16673/16674)| `OperationOutcome`| _Equivalent_<br/>(31108/31109)| `OperationOutcome`| _Equivalent_<br/>(45724/45725)| `OperationOutcome`
| **`OperationOutcome.id`**| _Equivalent_<br/>(6803/6804)| `OperationOutcome.id`| _Equivalent_<br/>(16675/16676)| `OperationOutcome.id`| _Equivalent_<br/>(31110/31111)| `OperationOutcome.id`| _Equivalent_<br/>(45726/45727)| `OperationOutcome.id`
| **`OperationOutcome.meta`**| _Equivalent_<br/>(6805/6806)| `OperationOutcome.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16677)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16678)| `OperationOutcome.meta`| _Equivalent_<br/>(31112/31113)| `OperationOutcome.meta`| _Equivalent_<br/>(45728/45729)| `OperationOutcome.meta`
| **`OperationOutcome.implicitRules`**| _Equivalent_<br/>(6807/6808)| `OperationOutcome.implicitRules`| _Equivalent_<br/>(16679/16680)| `OperationOutcome.implicitRules`| _Equivalent_<br/>(31114/31115)| `OperationOutcome.implicitRules`| _Equivalent_<br/>(45730/45731)| `OperationOutcome.implicitRules`
| **`OperationOutcome.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6809)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6810)| `OperationOutcome.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16681)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(16682)| `OperationOutcome.language`| _Equivalent_<br/>(31116/31117)| `OperationOutcome.language`| _Equivalent_<br/>(45732/45733)| `OperationOutcome.language`
| **`OperationOutcome.text`**| _Equivalent_<br/>(6811/6812)| `OperationOutcome.text`| _Equivalent_<br/>(16683/16684)| `OperationOutcome.text`| _Equivalent_<br/>(31118/31119)| `OperationOutcome.text`| _Equivalent_<br/>(45734/45735)| `OperationOutcome.text`
| **`OperationOutcome.contained`**| _Equivalent_<br/>(6813/6814)| `OperationOutcome.contained`| _Equivalent_<br/>(16685/16686)| `OperationOutcome.contained`| _Equivalent_<br/>(31120/31121)| `OperationOutcome.contained`| _Equivalent_<br/>(45736/45737)| `OperationOutcome.contained`
| **`OperationOutcome.extension`**| _Equivalent_<br/>(6815/6816)| `OperationOutcome.extension`| _Equivalent_<br/>(16687/16688)| `OperationOutcome.extension`| _Equivalent_<br/>(31122/31123)| `OperationOutcome.extension`| _Equivalent_<br/>(45738/45739)| `OperationOutcome.extension`
| **`OperationOutcome.modifierExtension`**| _Equivalent_<br/>(6817/6818)| `OperationOutcome.modifierExtension`| _Equivalent_<br/>(16689/16690)| `OperationOutcome.modifierExtension`| _Equivalent_<br/>(31124/31125)| `OperationOutcome.modifierExtension`| _Equivalent_<br/>(45740/45741)| `OperationOutcome.modifierExtension`
| **`OperationOutcome.issue`**| _Equivalent_<br/>(6819/6820)| `OperationOutcome.issue`| _Equivalent_<br/>(16691/16692)| `OperationOutcome.issue`| _Equivalent_<br/>(31126/31127)| `OperationOutcome.issue`| _Equivalent_<br/>(45742/45743)| `OperationOutcome.issue`
| **`OperationOutcome.issue.id`**| _Equivalent_<br/>(6821/6822)| `OperationOutcome.issue.id`| _Equivalent_<br/>(16693/16694)| `OperationOutcome.issue.id`| _Equivalent_<br/>(31128/31129)| `OperationOutcome.issue.id`| _Equivalent_<br/>(45744/45745)| `OperationOutcome.issue.id`
| **`OperationOutcome.issue.extension`**| _Equivalent_<br/>(6823/6824)| `OperationOutcome.issue.extension`| _Equivalent_<br/>(16695/16696)| `OperationOutcome.issue.extension`| _Equivalent_<br/>(31130/31131)| `OperationOutcome.issue.extension`| _Equivalent_<br/>(45746/45747)| `OperationOutcome.issue.extension`
| **`OperationOutcome.issue.modifierExtension`**| _Equivalent_<br/>(6825/6826)| `OperationOutcome.issue.modifierExtension`| _Equivalent_<br/>(16697/16698)| `OperationOutcome.issue.modifierExtension`| _Equivalent_<br/>(31132/31133)| `OperationOutcome.issue.modifierExtension`| _Equivalent_<br/>(45748/45749)| `OperationOutcome.issue.modifierExtension`
| **`OperationOutcome.issue.severity`**| _Equivalent_<br/>(6827/6828)| `OperationOutcome.issue.severity`| _Equivalent_<br/>(16699/16700)| `OperationOutcome.issue.severity`| _Equivalent_<br/>(31134/31135)| `OperationOutcome.issue.severity`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(45750)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45751)| `OperationOutcome.issue.severity`
| **`OperationOutcome.issue.code`**| _Equivalent_<br/>(6829/6830)| `OperationOutcome.issue.code`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16701)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16702)| `OperationOutcome.issue.code`| _Equivalent_<br/>(31136/31137)| `OperationOutcome.issue.code`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(45752)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45753)| `OperationOutcome.issue.code`
| **`OperationOutcome.issue.details`**| _Equivalent_<br/>(6831/6832)| `OperationOutcome.issue.details`| _Equivalent_<br/>(16703/16704)| `OperationOutcome.issue.details`| _Equivalent_<br/>(31138/31139)| `OperationOutcome.issue.details`| _Equivalent_<br/>(45754/45755)| `OperationOutcome.issue.details`
| **`OperationOutcome.issue.diagnostics`**| _Equivalent_<br/>(6833/6834)| `OperationOutcome.issue.diagnostics`| _Equivalent_<br/>(16705/16706)| `OperationOutcome.issue.diagnostics`| _Equivalent_<br/>(31140/31141)| `OperationOutcome.issue.diagnostics`| _Equivalent_<br/>(45756/45757)| `OperationOutcome.issue.diagnostics`
| **`OperationOutcome.issue.location`**| _Equivalent_<br/>(6835/6836)| `OperationOutcome.issue.location`| _Equivalent_<br/>(16707/16708)| `OperationOutcome.issue.location`| _Equivalent_<br/>(31142/31143)| `OperationOutcome.issue.location`| _Equivalent_<br/>(45758/45759)| `OperationOutcome.issue.location`
| *18 of 18 elements used* | | *18 of 19 elements used* <br/>remaining elements:<br/>`OperationOutcome.issue.expression`| | *18 of 19 elements used* <br/>remaining elements:<br/>`OperationOutcome.issue.expression`| | *18 of 19 elements used* <br/>remaining elements:<br/>`OperationOutcome.issue.expression`| | *18 of 19 elements used* <br/>remaining elements:<br/>`OperationOutcome.issue.expression`

