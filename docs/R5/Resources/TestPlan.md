Comparison of 
Generated at Tuesday, April 1, 2025 1:39:37 PM

### TestPlan

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | TestPlan |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/TestPlan` |
| Version | 5.0.0 |
| Description | A plan for executing testing on an artifact or specifications |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2401` |
| Database Snapshot Count | `73` |
| Database Differential Count | `44` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `TestPlan` | `TestPlan` | `TestPlan` | TestPlan | Description of intented testing | 0..* | TestPlan |  |  |
| `TestPlan.category` | `TestPlan.category` | `category` | TestPlan.category | The category of the Test Plan - can be acceptance, unit, performance | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/testscript-scope-phase-codes` |
| `TestPlan.contact` | `TestPlan.contact` | `contact` | TestPlan.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `TestPlan.contained` | `TestPlan.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `TestPlan.copyright` | `TestPlan.copyright` | `copyright` | TestPlan.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `TestPlan.copyrightLabel` | `TestPlan.copyrightLabel` | `copyrightLabel` | TestPlan.copyrightLabel | Copyright holder and year(s) | 0..1 | string |  |  |
| `TestPlan.date` | `TestPlan.date` | `date` | TestPlan.date | Date last changed | 0..1 | dateTime |  |  |
| `TestPlan.dependency` | `TestPlan.dependency` | `dependency` | TestPlan.dependency | The required criteria to execute the test plan - e.g. preconditions, previous tests | 0..* | BackboneElement |  |  |
| `TestPlan.dependency.description` | `TestPlan.dependency.description` | `description` | TestPlan.dependency.description | Description of the dependency criterium | 0..1 | markdown |  |  |
| `TestPlan.dependency.extension` | `TestPlan.dependency.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestPlan.dependency.id` | `TestPlan.dependency.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestPlan.dependency.modifierExtension` | `TestPlan.dependency.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestPlan.dependency.predecessor` | `TestPlan.dependency.predecessor` | `predecessor` | TestPlan.dependency.predecessor | Link to predecessor test plans | 0..1 | Reference |  |  |
| `TestPlan.description` | `TestPlan.description` | `description` | TestPlan.description | Natural language description of the test plan | 0..1 | markdown |  |  |
| `TestPlan.exitCriteria` | `TestPlan.exitCriteria` | `exitCriteria` | TestPlan.exitCriteria | The threshold or criteria for the test plan to be considered successfully executed - narrative | 0..1 | markdown |  |  |
| `TestPlan.experimental` | `TestPlan.experimental` | `experimental` | TestPlan.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `TestPlan.extension` | `TestPlan.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestPlan.id` | `TestPlan.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `TestPlan.identifier` | `TestPlan.identifier` | `identifier` | TestPlan.identifier | Business identifier identifier for the test plan | 0..* | Identifier |  |  |
| `TestPlan.implicitRules` | `TestPlan.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `TestPlan.jurisdiction` | `TestPlan.jurisdiction` | `jurisdiction` | TestPlan.jurisdiction | Intended jurisdiction where the test plan applies (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `TestPlan.language` | `TestPlan.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `TestPlan.meta` | `TestPlan.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `TestPlan.modifierExtension` | `TestPlan.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `TestPlan.name` | `TestPlan.name` | `name` | TestPlan.name | Name for this test plan (computer friendly) | 0..1 | string |  |  |
| `TestPlan.publisher` | `TestPlan.publisher` | `publisher` | TestPlan.publisher | Name of the publisher/steward (organization or individual) | 0..1 | string |  |  |
| `TestPlan.purpose` | `TestPlan.purpose` | `purpose` | TestPlan.purpose | Why this test plan is defined | 0..1 | markdown |  |  |
| `TestPlan.scope` | `TestPlan.scope` | `scope` | TestPlan.scope | What is being tested with this Test Plan - a conformance resource, or narrative criteria, or an external reference | 0..* | Reference |  |  |
| `TestPlan.status` | `TestPlan.status` | `status` | TestPlan.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `TestPlan.testCase` | `TestPlan.testCase` | `testCase` | TestPlan.testCase | The test cases that constitute this plan | 0..* | BackboneElement |  |  |
| `TestPlan.testCase.assertion` | `TestPlan.testCase.assertion` | `assertion` | TestPlan.testCase.assertion | Test assertions or expectations | 0..* | BackboneElement |  |  |
| `TestPlan.testCase.assertion.extension` | `TestPlan.testCase.assertion.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestPlan.testCase.assertion.id` | `TestPlan.testCase.assertion.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestPlan.testCase.assertion.modifierExtension` | `TestPlan.testCase.assertion.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestPlan.testCase.assertion.object` | `TestPlan.testCase.assertion.object` | `object` | TestPlan.testCase.assertion.object | The focus or object of the assertion | 0..* | CodeableReference |  |  |
| `TestPlan.testCase.assertion.result` | `TestPlan.testCase.assertion.result` | `result` | TestPlan.testCase.assertion.result | The actual result assertion | 0..* | CodeableReference |  |  |
| `TestPlan.testCase.assertion.type` | `TestPlan.testCase.assertion.type` | `type` | TestPlan.testCase.assertion.type | Assertion type - for example 'informative' or 'required'  | 0..* | CodeableConcept |  |  |
| `TestPlan.testCase.dependency` | `TestPlan.testCase.dependency` | `dependency` | TestPlan.testCase.dependency | Required criteria to execute the test case | 0..* | BackboneElement |  |  |
| `TestPlan.testCase.dependency.description` | `TestPlan.testCase.dependency.description` | `description` | TestPlan.testCase.dependency.description | Description of the criteria | 0..1 | markdown |  |  |
| `TestPlan.testCase.dependency.extension` | `TestPlan.testCase.dependency.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestPlan.testCase.dependency.id` | `TestPlan.testCase.dependency.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestPlan.testCase.dependency.modifierExtension` | `TestPlan.testCase.dependency.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestPlan.testCase.dependency.predecessor` | `TestPlan.testCase.dependency.predecessor` | `predecessor` | TestPlan.testCase.dependency.predecessor | Link to predecessor test plans | 0..1 | Reference |  |  |
| `TestPlan.testCase.extension` | `TestPlan.testCase.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestPlan.testCase.id` | `TestPlan.testCase.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestPlan.testCase.modifierExtension` | `TestPlan.testCase.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestPlan.testCase.scope` | `TestPlan.testCase.scope` | `scope` | TestPlan.testCase.scope | The scope or artifact covered by the case | 0..* | Reference |  |  |
| `TestPlan.testCase.sequence` | `TestPlan.testCase.sequence` | `sequence` | TestPlan.testCase.sequence | Sequence of test case in the test plan | 0..1 | integer |  |  |
| `TestPlan.testCase.testData` | `TestPlan.testCase.testData` | `testData` | TestPlan.testCase.testData | The test data used in the test case | 0..* | BackboneElement |  |  |
| `TestPlan.testCase.testData.content` | `TestPlan.testCase.testData.content` | `content` | TestPlan.testCase.testData.content | The actual test resources when they exist | 0..1 | Reference |  |  |
| `TestPlan.testCase.testData.extension` | `TestPlan.testCase.testData.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestPlan.testCase.testData.id` | `TestPlan.testCase.testData.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestPlan.testCase.testData.modifierExtension` | `TestPlan.testCase.testData.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestPlan.testCase.testData.source[x]` | `TestPlan.testCase.testData.source[x]` | `source[x]` | TestPlan.testCase.testData.source[x] | Pointer to a definition of test resources - narrative or structured e.g. synthetic data generation, etc | 0..1 | Reference, string |  |  |
| `TestPlan.testCase.testData.type` | `TestPlan.testCase.testData.type` | `type` | TestPlan.testCase.testData.type | The type of test data description, e.g. 'synthea' | 1..1 | Coding |  |  |
| `TestPlan.testCase.testRun` | `TestPlan.testCase.testRun` | `testRun` | TestPlan.testCase.testRun | The actual test to be executed | 0..* | BackboneElement |  |  |
| `TestPlan.testCase.testRun.extension` | `TestPlan.testCase.testRun.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestPlan.testCase.testRun.id` | `TestPlan.testCase.testRun.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestPlan.testCase.testRun.modifierExtension` | `TestPlan.testCase.testRun.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestPlan.testCase.testRun.narrative` | `TestPlan.testCase.testRun.narrative` | `narrative` | TestPlan.testCase.testRun.narrative | The narrative description of the tests | 0..1 | markdown |  |  |
| `TestPlan.testCase.testRun.script` | `TestPlan.testCase.testRun.script` | `script` | TestPlan.testCase.testRun.script | The test cases in a structured language e.g. gherkin, Postman, or FHIR TestScript | 0..1 | BackboneElement |  |  |
| `TestPlan.testCase.testRun.script.extension` | `TestPlan.testCase.testRun.script.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestPlan.testCase.testRun.script.id` | `TestPlan.testCase.testRun.script.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestPlan.testCase.testRun.script.language` | `TestPlan.testCase.testRun.script.language` | `language` | TestPlan.testCase.testRun.script.language | The language for the test cases e.g. 'gherkin', 'testscript' | 0..1 | CodeableConcept |  |  |
| `TestPlan.testCase.testRun.script.modifierExtension` | `TestPlan.testCase.testRun.script.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestPlan.testCase.testRun.script.source[x]` | `TestPlan.testCase.testRun.script.source[x]` | `source[x]` | TestPlan.testCase.testRun.script.source[x] | The actual content of the cases - references to TestScripts or externally defined content | 0..1 | Reference, string |  |  |
| `TestPlan.testTools` | `TestPlan.testTools` | `testTools` | TestPlan.testTools | A description of test tools to be used in the test plan - narrative for now | 0..1 | markdown |  |  |
| `TestPlan.text` | `TestPlan.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `TestPlan.title` | `TestPlan.title` | `title` | TestPlan.title | Name for this test plan (human friendly) | 0..1 | string |  |  |
| `TestPlan.url` | `TestPlan.url` | `url` | TestPlan.url | Canonical identifier for this test plan, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `TestPlan.useContext` | `TestPlan.useContext` | `useContext` | TestPlan.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `TestPlan.version` | `TestPlan.version` | `version` | TestPlan.version | Business version of the test plan | 0..1 | string |  |  |
| `TestPlan.versionAlgorithm[x]` | `TestPlan.versionAlgorithm[x]` | `versionAlgorithm[x]` | TestPlan.versionAlgorithm[x] | How to compare versions | 0..1 | Coding, string | `Extensible` | `http://hl7.org/fhir/ValueSet/version-algorithm` |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

