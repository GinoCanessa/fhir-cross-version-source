Comparison of 
Generated at Monday, April 14, 2025 6:17:45 PM

### Parameters

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Parameters |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Parameters` |
| Version | 5.0.0 |
| Description | This resource is used to pass information into and back from an operation (whether invoked directly from REST or within a messaging environment).  It is not persisted or allowed to be referenced by other resources except as described in the definition of the Parameters resource. |
| Status | `Active` |
| Artifact Class | `Resource` |
| Database Key | `2358` |
| Database Snapshot Count | `13` |
| Database Differential Count | `6` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Parameters` | `Parameters` | `Parameters` | Parameters | Operation Request or Response | 0..* | Parameters |  |  |
| `Parameters.id` | `Parameters.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Parameters.implicitRules` | `Parameters.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Parameters.language` | `Parameters.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Parameters.meta` | `Parameters.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Parameters.parameter` | `Parameters.parameter` | `parameter` | Parameters.parameter | Operation Parameter | 0..* | BackboneElement |  |  |
| `Parameters.parameter.extension` | `Parameters.parameter.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Parameters.parameter.id` | `Parameters.parameter.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Parameters.parameter.modifierExtension` | `Parameters.parameter.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Parameters.parameter.name` | `Parameters.parameter.name` | `name` | Parameters.parameter.name | Name from the definition | 1..1 | string |  |  |
| `Parameters.parameter.part` | `Parameters.parameter.part` | `part` | Parameters.parameter.part | Named part of a multi-part parameter | 0..* | Parameters.parameter |  |  |
| `Parameters.parameter.resource` | `Parameters.parameter.resource` | `resource` | Parameters.parameter.resource | If parameter is a whole resource | 0..1 | Resource |  |  |
| `Parameters.parameter.value[x]` | `Parameters.parameter.value[x]` | `value[x]` | Parameters.parameter.value[x] | If parameter is a data type | 0..1 | Address, Age, Annotation, Attachment, Availability, base64Binary, boolean, canonical, code, CodeableConcept, CodeableReference, Coding, ContactDetail, ContactPoint, Count, DataRequirement, date, dateTime, decimal, Distance, Dosage, Duration, Expression, ExtendedContactDetail, HumanName, id, Identifier, instant, integer, integer64, markdown, Meta, Money, oid, ParameterDefinition, Period, positiveInt, Quantity, Range, Ratio, RatioRange, Reference, RelatedArtifact, SampledData, Signature, string, time, Timing, TriggerDefinition, unsignedInt, uri, url, UsageContext, uuid |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ExpansionProfile](/docs/R3/Resources/ExpansionProfile.md)<br/> `http://hl7.org/fhir/StructureDefinition/ExpansionProfile\|3.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `459`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [Parameters](/docs/R4/Resources/Parameters.md)<br/> `http://hl7.org/fhir/StructureDefinition/Parameters\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1569`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1570`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Parameters](/docs/R4B/Resources/Parameters.md)<br/> `http://hl7.org/fhir/StructureDefinition/Parameters\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1060`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1289`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Parameters](/docs/R5/Resources/Parameters.md)<br/> `http://hl7.org/fhir/StructureDefinition/Parameters\|5.0.0` 
| [Parameters](/docs/R2/Resources/Parameters.md)<br/> `http://hl7.org/fhir/StructureDefinition/Parameters\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `138`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `304`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Parameters](/docs/R3/Resources/Parameters.md)<br/> `http://hl7.org/fhir/StructureDefinition/Parameters\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `493`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [Parameters](/docs/R4/Resources/Parameters.md)<br/> `http://hl7.org/fhir/StructureDefinition/Parameters\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1569`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1570`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Parameters](/docs/R4B/Resources/Parameters.md)<br/> `http://hl7.org/fhir/StructureDefinition/Parameters\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1060`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1289`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Parameters](/docs/R5/Resources/Parameters.md)<br/> `http://hl7.org/fhir/StructureDefinition/Parameters\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Parameters from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 ExpansionProfile](/docs/R3/Resources/ExpansionProfile.md)| Relationship | [R4 Parameters](/docs/R4/Resources/Parameters.md)| Relationship | [R4B Parameters](/docs/R4B/Resources/Parameters.md)| Relationship | R5 Parameters
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `Parameters`| _Equivalent_<br/>(31253/31254)| `Parameters`| _Equivalent_<br/>(45920/45921)| **`Parameters`**
| | | | | `Parameters.id`| _Equivalent_<br/>(31255/31256)| `Parameters.id`| _Equivalent_<br/>(45922/45923)| **`Parameters.id`**
| | | | | `Parameters.meta`| _Equivalent_<br/>(31257/31258)| `Parameters.meta`| _Equivalent_<br/>(45924/45925)| **`Parameters.meta`**
| | | | | `Parameters.implicitRules`| _Equivalent_<br/>(31259/31260)| `Parameters.implicitRules`| _Equivalent_<br/>(45926/45927)| **`Parameters.implicitRules`**
| | | | | `Parameters.language`| _Equivalent_<br/>(31261/31262)| `Parameters.language`| _Equivalent_<br/>(45928/45929)| **`Parameters.language`**
| | | | | `Parameters.parameter`| _Equivalent_<br/>(31263/31264)| `Parameters.parameter`| _Equivalent_<br/>(45930/45931)| **`Parameters.parameter`**
| | | | | `Parameters.parameter.id`| _Equivalent_<br/>(31265/31266)| `Parameters.parameter.id`| _Equivalent_<br/>(45932/45933)| **`Parameters.parameter.id`**
| | | | | `Parameters.parameter.extension`| _Equivalent_<br/>(31267/31268)| `Parameters.parameter.extension`| _Equivalent_<br/>(45934/45935)| **`Parameters.parameter.extension`**
| | | | | `Parameters.parameter.modifierExtension`| _Equivalent_<br/>(31269/31270)| `Parameters.parameter.modifierExtension`| _Equivalent_<br/>(45936/45937)| **`Parameters.parameter.modifierExtension`**
| | | | | `Parameters.parameter.name`| _Equivalent_<br/>(31271/31272)| `Parameters.parameter.name`| _Equivalent_<br/>(45938/45939)| **`Parameters.parameter.name`**
| | | | | `Parameters.parameter.value[x]`| _Equivalent_<br/>(31273/31274)| `Parameters.parameter.value[x]`| →→→→ _RelatedTo_ →→→→ <br/>(45940)<hr/>←←←← _RelatedTo_ ←←←← <br/>(45941)| **`Parameters.parameter.value[x]`**
| | | | | `Parameters.parameter.resource`| _Equivalent_<br/>(31275/31276)| `Parameters.parameter.resource`| _Equivalent_<br/>(45942/45943)| **`Parameters.parameter.resource`**
| | | | | `Parameters.parameter.part`| _Equivalent_<br/>(31277/31278)| `Parameters.parameter.part`| _Equivalent_<br/>(45944/45945)| **`Parameters.parameter.part`**
| | | *0 of 66 elements used* <br/>remaining elements:<br/>`ExpansionProfile`, `ExpansionProfile.activeOnly`, `ExpansionProfile.contact`, `ExpansionProfile.contained`, `ExpansionProfile.date`, `ExpansionProfile.description`, `ExpansionProfile.designation`, `ExpansionProfile.designation.exclude`, `ExpansionProfile.designation.exclude.designation`, `ExpansionProfile.designation.exclude.designation.extension`, `ExpansionProfile.designation.exclude.designation.id`, `ExpansionProfile.designation.exclude.designation.language`, `ExpansionProfile.designation.exclude.designation.modifierExtension`, `ExpansionProfile.designation.exclude.designation.use`, `ExpansionProfile.designation.exclude.extension`, `ExpansionProfile.designation.exclude.id`, `ExpansionProfile.designation.exclude.modifierExtension`, `ExpansionProfile.designation.extension`, `ExpansionProfile.designation.id`, `ExpansionProfile.designation.include`, `ExpansionProfile.designation.include.designation`, `ExpansionProfile.designation.include.designation.extension`, `ExpansionProfile.designation.include.designation.id`, `ExpansionProfile.designation.include.designation.language`, `ExpansionProfile.designation.include.designation.modifierExtension`, `ExpansionProfile.designation.include.designation.use`, `ExpansionProfile.designation.include.extension`, `ExpansionProfile.designation.include.id`, `ExpansionProfile.designation.include.modifierExtension`, `ExpansionProfile.designation.modifierExtension`, `ExpansionProfile.displayLanguage`, `ExpansionProfile.excludeNested`, `ExpansionProfile.excludeNotForUI`, `ExpansionProfile.excludePostCoordinated`, `ExpansionProfile.excludedSystem`, `ExpansionProfile.excludedSystem.extension`, `ExpansionProfile.excludedSystem.id`, `ExpansionProfile.excludedSystem.modifierExtension`, `ExpansionProfile.excludedSystem.system`, `ExpansionProfile.excludedSystem.version`, `ExpansionProfile.experimental`, `ExpansionProfile.extension`, `ExpansionProfile.fixedVersion`, `ExpansionProfile.fixedVersion.extension`, `ExpansionProfile.fixedVersion.id`, `ExpansionProfile.fixedVersion.mode`, `ExpansionProfile.fixedVersion.modifierExtension`, `ExpansionProfile.fixedVersion.system`, `ExpansionProfile.fixedVersion.version`, `ExpansionProfile.id`, `ExpansionProfile.identifier`, `ExpansionProfile.implicitRules`, `ExpansionProfile.includeDefinition`, `ExpansionProfile.includeDesignations`, `ExpansionProfile.jurisdiction`, `ExpansionProfile.language`, `ExpansionProfile.limitedExpansion`, `ExpansionProfile.meta`, `ExpansionProfile.modifierExtension`, `ExpansionProfile.name`, `ExpansionProfile.publisher`, `ExpansionProfile.status`, `ExpansionProfile.text`, `ExpansionProfile.url`, `ExpansionProfile.useContext`, `ExpansionProfile.version`| | *13 of 13 elements used* | | *13 of 13 elements used* | | *13 of 13 elements used* 


#### Map Group 1

This group is centered on the Structure Definition Parameters from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Parameters](/docs/R2/Resources/Parameters.md)| Relationship | [R3 Parameters](/docs/R3/Resources/Parameters.md)| Relationship | [R4 Parameters](/docs/R4/Resources/Parameters.md)| Relationship | [R4B Parameters](/docs/R4B/Resources/Parameters.md)| Relationship | R5 Parameters
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Parameters`| _Equivalent_<br/>(6912/6913)| `Parameters`| _Equivalent_<br/>(16765/16766)| `Parameters`| _Equivalent_<br/>(31253/31254)| `Parameters`| _Equivalent_<br/>(45920/45921)| **`Parameters`**
| `Parameters.id`| _Equivalent_<br/>(6914/6915)| `Parameters.id`| _Equivalent_<br/>(16767/16768)| `Parameters.id`| _Equivalent_<br/>(31255/31256)| `Parameters.id`| _Equivalent_<br/>(45922/45923)| **`Parameters.id`**
| `Parameters.meta`| _Equivalent_<br/>(6916/6917)| `Parameters.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16769)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16770)| `Parameters.meta`| _Equivalent_<br/>(31257/31258)| `Parameters.meta`| _Equivalent_<br/>(45924/45925)| **`Parameters.meta`**
| `Parameters.implicitRules`| _Equivalent_<br/>(6918/6919)| `Parameters.implicitRules`| _Equivalent_<br/>(16771/16772)| `Parameters.implicitRules`| _Equivalent_<br/>(31259/31260)| `Parameters.implicitRules`| _Equivalent_<br/>(45926/45927)| **`Parameters.implicitRules`**
| `Parameters.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6920)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6921)| `Parameters.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16773)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(16774)| `Parameters.language`| _Equivalent_<br/>(31261/31262)| `Parameters.language`| _Equivalent_<br/>(45928/45929)| **`Parameters.language`**
| `Parameters.parameter`| _Equivalent_<br/>(6922/6923)| `Parameters.parameter`| _Equivalent_<br/>(16775/16776)| `Parameters.parameter`| _Equivalent_<br/>(31263/31264)| `Parameters.parameter`| _Equivalent_<br/>(45930/45931)| **`Parameters.parameter`**
| `Parameters.parameter.id`| _Equivalent_<br/>(6924/6925)| `Parameters.parameter.id`| _Equivalent_<br/>(16777/16778)| `Parameters.parameter.id`| _Equivalent_<br/>(31265/31266)| `Parameters.parameter.id`| _Equivalent_<br/>(45932/45933)| **`Parameters.parameter.id`**
| `Parameters.parameter.extension`| _Equivalent_<br/>(6926/6927)| `Parameters.parameter.extension`| _Equivalent_<br/>(16779/16780)| `Parameters.parameter.extension`| _Equivalent_<br/>(31267/31268)| `Parameters.parameter.extension`| _Equivalent_<br/>(45934/45935)| **`Parameters.parameter.extension`**
| `Parameters.parameter.modifierExtension`| _Equivalent_<br/>(6928/6929)| `Parameters.parameter.modifierExtension`| _Equivalent_<br/>(16781/16782)| `Parameters.parameter.modifierExtension`| _Equivalent_<br/>(31269/31270)| `Parameters.parameter.modifierExtension`| _Equivalent_<br/>(45936/45937)| **`Parameters.parameter.modifierExtension`**
| `Parameters.parameter.name`| _Equivalent_<br/>(6930/6931)| `Parameters.parameter.name`| _Equivalent_<br/>(16783/16784)| `Parameters.parameter.name`| _Equivalent_<br/>(31271/31272)| `Parameters.parameter.name`| _Equivalent_<br/>(45938/45939)| **`Parameters.parameter.name`**
| `Parameters.parameter.value[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6932)<hr/>←←←← _RelatedTo_ ←←←← <br/>(6933)| `Parameters.parameter.value[x]`| →→→→ _RelatedTo_ →→→→ <br/>(16785)<hr/>←←←← _RelatedTo_ ←←←← <br/>(16786)| `Parameters.parameter.value[x]`| _Equivalent_<br/>(31273/31274)| `Parameters.parameter.value[x]`| →→→→ _RelatedTo_ →→→→ <br/>(45940)<hr/>←←←← _RelatedTo_ ←←←← <br/>(45941)| **`Parameters.parameter.value[x]`**
| `Parameters.parameter.resource`| _Equivalent_<br/>(6934/6935)| `Parameters.parameter.resource`| _Equivalent_<br/>(16787/16788)| `Parameters.parameter.resource`| _Equivalent_<br/>(31275/31276)| `Parameters.parameter.resource`| _Equivalent_<br/>(45942/45943)| **`Parameters.parameter.resource`**
| `Parameters.parameter.part`| _Equivalent_<br/>(6936/6937)| `Parameters.parameter.part`| _Equivalent_<br/>(16789/16790)| `Parameters.parameter.part`| _Equivalent_<br/>(31277/31278)| `Parameters.parameter.part`| _Equivalent_<br/>(45944/45945)| **`Parameters.parameter.part`**
| *13 of 13 elements used* | | *13 of 13 elements used* | | *13 of 13 elements used* | | *13 of 13 elements used* | | *13 of 13 elements used* 

