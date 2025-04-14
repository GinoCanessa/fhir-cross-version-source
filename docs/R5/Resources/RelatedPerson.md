Comparison of 
Generated at Monday, April 14, 2025 6:17:49 PM

### RelatedPerson

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | RelatedPerson |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/RelatedPerson` |
| Version | 5.0.0 |
| Description | Information about a person that is involved in a patient's health or the care for a patient, but who is not the target of healthcare, nor has a formal responsibility in the care process. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2372` |
| Database Snapshot Count | `26` |
| Database Differential Count | `15` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `RelatedPerson` | `RelatedPerson` | `RelatedPerson` | RelatedPerson | A person that is related to a patient, but who is not a direct target of care | 0..* | RelatedPerson |  |  |
| `RelatedPerson.active` | `RelatedPerson.active` | `active` | RelatedPerson.active | Whether this related person's record is in active use | 0..1 | boolean |  |  |
| `RelatedPerson.address` | `RelatedPerson.address` | `address` | RelatedPerson.address | Address where the related person can be contacted or visited | 0..* | Address |  |  |
| `RelatedPerson.birthDate` | `RelatedPerson.birthDate` | `birthDate` | RelatedPerson.birthDate | The date on which the related person was born | 0..1 | date |  |  |
| `RelatedPerson.communication` | `RelatedPerson.communication` | `communication` | RelatedPerson.communication | A language which may be used to communicate with the related person about the patient's health | 0..* | BackboneElement |  |  |
| `RelatedPerson.communication.extension` | `RelatedPerson.communication.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RelatedPerson.communication.id` | `RelatedPerson.communication.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RelatedPerson.communication.language` | `RelatedPerson.communication.language` | `language` | RelatedPerson.communication.language | The language which can be used to communicate with the related person about the patient's health | 1..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `RelatedPerson.communication.modifierExtension` | `RelatedPerson.communication.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RelatedPerson.communication.preferred` | `RelatedPerson.communication.preferred` | `preferred` | RelatedPerson.communication.preferred | Language preference indicator | 0..1 | boolean |  |  |
| `RelatedPerson.contained` | `RelatedPerson.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `RelatedPerson.extension` | `RelatedPerson.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RelatedPerson.gender` | `RelatedPerson.gender` | `gender` | RelatedPerson.gender | male \| female \| other \| unknown | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/administrative-gender|5.0.0` |
| `RelatedPerson.id` | `RelatedPerson.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `RelatedPerson.identifier` | `RelatedPerson.identifier` | `identifier` | RelatedPerson.identifier | A human identifier for this person | 0..* | Identifier |  |  |
| `RelatedPerson.implicitRules` | `RelatedPerson.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `RelatedPerson.language` | `RelatedPerson.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `RelatedPerson.meta` | `RelatedPerson.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `RelatedPerson.modifierExtension` | `RelatedPerson.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `RelatedPerson.name` | `RelatedPerson.name` | `name` | RelatedPerson.name | A name associated with the person | 0..* | HumanName |  |  |
| `RelatedPerson.patient` | `RelatedPerson.patient` | `patient` | RelatedPerson.patient | The patient this person is related to | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `RelatedPerson.period` | `RelatedPerson.period` | `period` | RelatedPerson.period | Period of time that this relationship is considered valid | 0..1 | Period |  |  |
| `RelatedPerson.photo` | `RelatedPerson.photo` | `photo` | RelatedPerson.photo | Image of the person | 0..* | Attachment |  |  |
| `RelatedPerson.relationship` | `RelatedPerson.relationship` | `relationship` | RelatedPerson.relationship | The relationship of the related person to the patient | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/relatedperson-relationshiptype` |
| `RelatedPerson.telecom` | `RelatedPerson.telecom` | `telecom` | RelatedPerson.telecom | A contact detail for the person | 0..* | ContactPoint |  |  |
| `RelatedPerson.text` | `RelatedPerson.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [RelatedPerson](/docs/R2/Resources/RelatedPerson.md)<br/> `http://hl7.org/fhir/StructureDefinition/RelatedPerson\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `151`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `317`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RelatedPerson](/docs/R3/Resources/RelatedPerson.md)<br/> `http://hl7.org/fhir/StructureDefinition/RelatedPerson\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `508`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `700`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RelatedPerson](/docs/R4/Resources/RelatedPerson.md)<br/> `http://hl7.org/fhir/StructureDefinition/RelatedPerson\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1593`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1594`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RelatedPerson](/docs/R4B/Resources/RelatedPerson.md)<br/> `http://hl7.org/fhir/StructureDefinition/RelatedPerson\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1033`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1262`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RelatedPerson](/docs/R5/Resources/RelatedPerson.md)<br/> `http://hl7.org/fhir/StructureDefinition/RelatedPerson\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition RelatedPerson from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 RelatedPerson](/docs/R2/Resources/RelatedPerson.md)| Relationship | [R3 RelatedPerson](/docs/R3/Resources/RelatedPerson.md)| Relationship | [R4 RelatedPerson](/docs/R4/Resources/RelatedPerson.md)| Relationship | [R4B RelatedPerson](/docs/R4B/Resources/RelatedPerson.md)| Relationship | R5 RelatedPerson
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `RelatedPerson`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7609)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7610)| `RelatedPerson`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17893)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17894)| `RelatedPerson`| _Equivalent_<br/>(32273/32274)| `RelatedPerson`| _Equivalent_<br/>(46897/46898)| **`RelatedPerson`**
| `RelatedPerson.id`| _Equivalent_<br/>(7611/7612)| `RelatedPerson.id`| _Equivalent_<br/>(17895/17896)| `RelatedPerson.id`| _Equivalent_<br/>(32275/32276)| `RelatedPerson.id`| _Equivalent_<br/>(46899/46900)| **`RelatedPerson.id`**
| `RelatedPerson.meta`| _Equivalent_<br/>(7613/7614)| `RelatedPerson.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17897)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17898)| `RelatedPerson.meta`| _Equivalent_<br/>(32277/32278)| `RelatedPerson.meta`| _Equivalent_<br/>(46901/46902)| **`RelatedPerson.meta`**
| `RelatedPerson.implicitRules`| _Equivalent_<br/>(7615/7616)| `RelatedPerson.implicitRules`| _Equivalent_<br/>(17899/17900)| `RelatedPerson.implicitRules`| _Equivalent_<br/>(32279/32280)| `RelatedPerson.implicitRules`| _Equivalent_<br/>(46903/46904)| **`RelatedPerson.implicitRules`**
| `RelatedPerson.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7617)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7618)| `RelatedPerson.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17901)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(17902)| `RelatedPerson.language`| _Equivalent_<br/>(32281/32282)| `RelatedPerson.language`| _Equivalent_<br/>(46905/46906)| **`RelatedPerson.language`**
| `RelatedPerson.text`| _Equivalent_<br/>(7619/7620)| `RelatedPerson.text`| _Equivalent_<br/>(17903/17904)| `RelatedPerson.text`| _Equivalent_<br/>(32283/32284)| `RelatedPerson.text`| _Equivalent_<br/>(46907/46908)| **`RelatedPerson.text`**
| `RelatedPerson.contained`| _Equivalent_<br/>(7621/7622)| `RelatedPerson.contained`| _Equivalent_<br/>(17905/17906)| `RelatedPerson.contained`| _Equivalent_<br/>(32285/32286)| `RelatedPerson.contained`| _Equivalent_<br/>(46909/46910)| **`RelatedPerson.contained`**
| `RelatedPerson.extension`| _Equivalent_<br/>(7623/7624)| `RelatedPerson.extension`| _Equivalent_<br/>(17907/17908)| `RelatedPerson.extension`| _Equivalent_<br/>(32287/32288)| `RelatedPerson.extension`| _Equivalent_<br/>(46911/46912)| **`RelatedPerson.extension`**
| `RelatedPerson.modifierExtension`| _Equivalent_<br/>(7625/7626)| `RelatedPerson.modifierExtension`| _Equivalent_<br/>(17909/17910)| `RelatedPerson.modifierExtension`| _Equivalent_<br/>(32289/32290)| `RelatedPerson.modifierExtension`| _Equivalent_<br/>(46913/46914)| **`RelatedPerson.modifierExtension`**
| `RelatedPerson.identifier`| _Equivalent_<br/>(7627/7628)| `RelatedPerson.identifier`| _Equivalent_<br/>(17911/17912)| `RelatedPerson.identifier`| _Equivalent_<br/>(32291/32292)| `RelatedPerson.identifier`| _Equivalent_<br/>(46915/46916)| **`RelatedPerson.identifier`**
| | | `RelatedPerson.active`| _Equivalent_<br/>(17913/17914)| `RelatedPerson.active`| _Equivalent_<br/>(32293/32294)| `RelatedPerson.active`| _Equivalent_<br/>(46917/46918)| **`RelatedPerson.active`**
| `RelatedPerson.patient`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7629)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7630)| `RelatedPerson.patient`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17915)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17916)| `RelatedPerson.patient`| _Equivalent_<br/>(32295/32296)| `RelatedPerson.patient`| _Equivalent_<br/>(46919/46920)| **`RelatedPerson.patient`**
| `RelatedPerson.relationship`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7631)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7632)| `RelatedPerson.relationship`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17917)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17918)| `RelatedPerson.relationship`| _Equivalent_<br/>(32297/32298)| `RelatedPerson.relationship`| _Equivalent_<br/>(46921/46922)| **`RelatedPerson.relationship`**
| `RelatedPerson.name`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7633)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7634)| `RelatedPerson.name`| _Equivalent_<br/>(17919/17920)| `RelatedPerson.name`| _Equivalent_<br/>(32299/32300)| `RelatedPerson.name`| _Equivalent_<br/>(46923/46924)| **`RelatedPerson.name`**
| `RelatedPerson.telecom`| _Equivalent_<br/>(7635/7636)| `RelatedPerson.telecom`| _Equivalent_<br/>(17921/17922)| `RelatedPerson.telecom`| _Equivalent_<br/>(32301/32302)| `RelatedPerson.telecom`| _Equivalent_<br/>(46925/46926)| **`RelatedPerson.telecom`**
| `RelatedPerson.gender`| _Equivalent_<br/>(7637/7638)| `RelatedPerson.gender`| _Equivalent_<br/>(17923/17924)| `RelatedPerson.gender`| _Equivalent_<br/>(32303/32304)| `RelatedPerson.gender`| _Equivalent_<br/>(46927/46928)| **`RelatedPerson.gender`**
| `RelatedPerson.birthDate`| _Equivalent_<br/>(7639/7640)| `RelatedPerson.birthDate`| _Equivalent_<br/>(17925/17926)| `RelatedPerson.birthDate`| _Equivalent_<br/>(32305/32306)| `RelatedPerson.birthDate`| _Equivalent_<br/>(46929/46930)| **`RelatedPerson.birthDate`**
| `RelatedPerson.address`| _Equivalent_<br/>(7641/7642)| `RelatedPerson.address`| _Equivalent_<br/>(17927/17928)| `RelatedPerson.address`| _Equivalent_<br/>(32307/32308)| `RelatedPerson.address`| _Equivalent_<br/>(46931/46932)| **`RelatedPerson.address`**
| `RelatedPerson.photo`| _Equivalent_<br/>(7643/7644)| `RelatedPerson.photo`| _Equivalent_<br/>(17929/17930)| `RelatedPerson.photo`| _Equivalent_<br/>(32309/32310)| `RelatedPerson.photo`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(46933)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(46934)| **`RelatedPerson.photo`**
| `RelatedPerson.period`| _Equivalent_<br/>(7645/7646)| `RelatedPerson.period`| _Equivalent_<br/>(17931/17932)| `RelatedPerson.period`| _Equivalent_<br/>(32311/32312)| `RelatedPerson.period`| _Equivalent_<br/>(46935/46936)| **`RelatedPerson.period`**
| | | | | `RelatedPerson.communication`| _Equivalent_<br/>(32313/32314)| `RelatedPerson.communication`| _Equivalent_<br/>(46937/46938)| **`RelatedPerson.communication`**
| | | | | `RelatedPerson.communication.id`| _Equivalent_<br/>(32315/32316)| `RelatedPerson.communication.id`| _Equivalent_<br/>(46939/46940)| **`RelatedPerson.communication.id`**
| | | | | `RelatedPerson.communication.extension`| _Equivalent_<br/>(32317/32318)| `RelatedPerson.communication.extension`| _Equivalent_<br/>(46941/46942)| **`RelatedPerson.communication.extension`**
| | | | | `RelatedPerson.communication.modifierExtension`| _Equivalent_<br/>(32319/32320)| `RelatedPerson.communication.modifierExtension`| _Equivalent_<br/>(46943/46944)| **`RelatedPerson.communication.modifierExtension`**
| | | | | `RelatedPerson.communication.language`| _Equivalent_<br/>(32321/32322)| `RelatedPerson.communication.language`| _Equivalent_<br/>(46945/46946)| **`RelatedPerson.communication.language`**
| | | | | `RelatedPerson.communication.preferred`| _Equivalent_<br/>(32323/32324)| `RelatedPerson.communication.preferred`| _Equivalent_<br/>(46947/46948)| **`RelatedPerson.communication.preferred`**
| *19 of 19 elements used* | | *20 of 20 elements used* | | *26 of 26 elements used* | | *26 of 26 elements used* | | *26 of 26 elements used* 

