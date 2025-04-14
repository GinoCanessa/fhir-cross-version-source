Comparison of 
Generated at Monday, April 14, 2025 6:17:49 PM

### RegulatedAuthorization

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | RegulatedAuthorization |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/RegulatedAuthorization` |
| Version | 5.0.0 |
| Description | Regulatory approval, clearance or licencing related to a regulated product, treatment, facility or activity that is cited in a guidance, regulation, rule or legislative act. An example is Market Authorization relating to a Medicinal Product. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2371` |
| Database Snapshot Count | `32` |
| Database Differential Count | `21` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `RegulatedAuthorization` | `RegulatedAuthorization` | `RegulatedAuthorization` | RegulatedAuthorization | Regulatory approval, clearance or licencing related to a regulated product, treatment, facility or activity e.g. Market Authorization for a Medicinal Product | 0..* | RegulatedAuthorization |  |  |
| `RegulatedAuthorization.attachedDocument` | `RegulatedAuthorization.attachedDocument` | `attachedDocument` | RegulatedAuthorization.attachedDocument | Additional information or supporting documentation about the authorization | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `RegulatedAuthorization.basis` | `RegulatedAuthorization.basis` | `basis` | RegulatedAuthorization.basis | The legal/regulatory framework or reasons under which this authorization is granted | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/regulated-authorization-basis` |
| `RegulatedAuthorization.case` | `RegulatedAuthorization.case` | `case` | RegulatedAuthorization.case | The case or regulatory procedure for granting or amending a regulated authorization. Note: This area is subject to ongoing review and the workgroup is seeking implementer feedback on its use (see link at bottom of page) | 0..1 | BackboneElement |  |  |
| `RegulatedAuthorization.case.application` | `RegulatedAuthorization.case.application` | `application` | RegulatedAuthorization.case.application | Applications submitted to obtain a regulated authorization. Steps within the longer running case or procedure | 0..* | RegulatedAuthorization.case |  |  |
| `RegulatedAuthorization.case.date[x]` | `RegulatedAuthorization.case.date[x]` | `date[x]` | RegulatedAuthorization.case.date[x] | Relevant date for this case | 0..1 | dateTime, Period |  |  |
| `RegulatedAuthorization.case.extension` | `RegulatedAuthorization.case.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RegulatedAuthorization.case.id` | `RegulatedAuthorization.case.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RegulatedAuthorization.case.identifier` | `RegulatedAuthorization.case.identifier` | `identifier` | RegulatedAuthorization.case.identifier | Identifier by which this case can be referenced | 0..1 | Identifier |  |  |
| `RegulatedAuthorization.case.modifierExtension` | `RegulatedAuthorization.case.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RegulatedAuthorization.case.status` | `RegulatedAuthorization.case.status` | `status` | RegulatedAuthorization.case.status | The status associated with the case | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `RegulatedAuthorization.case.type` | `RegulatedAuthorization.case.type` | `type` | RegulatedAuthorization.case.type | The defining type of case | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/regulated-authorization-case-type` |
| `RegulatedAuthorization.contained` | `RegulatedAuthorization.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `RegulatedAuthorization.description` | `RegulatedAuthorization.description` | `description` | RegulatedAuthorization.description | General textual supporting information | 0..1 | markdown |  |  |
| `RegulatedAuthorization.extension` | `RegulatedAuthorization.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RegulatedAuthorization.holder` | `RegulatedAuthorization.holder` | `holder` | RegulatedAuthorization.holder | The organization that has been granted this authorization, by the regulator | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `RegulatedAuthorization.id` | `RegulatedAuthorization.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `RegulatedAuthorization.identifier` | `RegulatedAuthorization.identifier` | `identifier` | RegulatedAuthorization.identifier | Business identifier for the authorization, typically assigned by the authorizing body | 0..* | Identifier |  |  |
| `RegulatedAuthorization.implicitRules` | `RegulatedAuthorization.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `RegulatedAuthorization.indication` | `RegulatedAuthorization.indication` | `indication` | RegulatedAuthorization.indication | Condition for which the use of the regulated product applies | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/ClinicalUseDefinition) |  |  |
| `RegulatedAuthorization.intendedUse` | `RegulatedAuthorization.intendedUse` | `intendedUse` | RegulatedAuthorization.intendedUse | The intended use of the product, e.g. prevention, treatment | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/product-intended-use` |
| `RegulatedAuthorization.language` | `RegulatedAuthorization.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `RegulatedAuthorization.meta` | `RegulatedAuthorization.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `RegulatedAuthorization.modifierExtension` | `RegulatedAuthorization.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `RegulatedAuthorization.region` | `RegulatedAuthorization.region` | `region` | RegulatedAuthorization.region | The territory in which the authorization has been granted | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `RegulatedAuthorization.regulator` | `RegulatedAuthorization.regulator` | `regulator` | RegulatedAuthorization.regulator | The regulatory authority or authorizing body granting the authorization | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `RegulatedAuthorization.status` | `RegulatedAuthorization.status` | `status` | RegulatedAuthorization.status | The status that is authorised e.g. approved. Intermediate states can be tracked with cases and applications | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `RegulatedAuthorization.statusDate` | `RegulatedAuthorization.statusDate` | `statusDate` | RegulatedAuthorization.statusDate | The date at which the current status was assigned | 0..1 | dateTime |  |  |
| `RegulatedAuthorization.subject` | `RegulatedAuthorization.subject` | `subject` | RegulatedAuthorization.subject | The product type, treatment, facility or activity that is being authorized | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ActivityDefinition), Reference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct), Reference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition), Reference(http://hl7.org/fhir/StructureDefinition/Ingredient), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/ManufacturedItemDefinition), Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition), Reference(http://hl7.org/fhir/StructureDefinition/NutritionProduct), Reference(http://hl7.org/fhir/StructureDefinition/ObservationDefinition), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/PackagedProductDefinition), Reference(http://hl7.org/fhir/StructureDefinition/PlanDefinition), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/ResearchStudy), Reference(http://hl7.org/fhir/StructureDefinition/SubstanceDefinition) |  |  |
| `RegulatedAuthorization.text` | `RegulatedAuthorization.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `RegulatedAuthorization.type` | `RegulatedAuthorization.type` | `type` | RegulatedAuthorization.type | Overall type of this authorization, for example drug marketing approval, orphan drug designation | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/regulated-authorization-type` |
| `RegulatedAuthorization.validityPeriod` | `RegulatedAuthorization.validityPeriod` | `validityPeriod` | RegulatedAuthorization.validityPeriod | The time period in which the regulatory approval etc. is in effect, e.g. a Marketing Authorization includes the date of authorization and/or expiration date | 0..1 | Period |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [RegulatedAuthorization](/docs/R4B/Resources/RegulatedAuthorization.md)<br/> `http://hl7.org/fhir/StructureDefinition/RegulatedAuthorization\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1032`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1261`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RegulatedAuthorization](/docs/R5/Resources/RegulatedAuthorization.md)<br/> `http://hl7.org/fhir/StructureDefinition/RegulatedAuthorization\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition RegulatedAuthorization from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B RegulatedAuthorization](/docs/R4B/Resources/RegulatedAuthorization.md)| Relationship | R5 RegulatedAuthorization
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | `RegulatedAuthorization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(46835)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(46836)| **`RegulatedAuthorization`**
| | | | | | | `RegulatedAuthorization.id`| _Equivalent_<br/>(46837/46838)| **`RegulatedAuthorization.id`**
| | | | | | | `RegulatedAuthorization.meta`| _Equivalent_<br/>(46839/46840)| **`RegulatedAuthorization.meta`**
| | | | | | | `RegulatedAuthorization.implicitRules`| _Equivalent_<br/>(46841/46842)| **`RegulatedAuthorization.implicitRules`**
| | | | | | | `RegulatedAuthorization.language`| _Equivalent_<br/>(46843/46844)| **`RegulatedAuthorization.language`**
| | | | | | | `RegulatedAuthorization.text`| _Equivalent_<br/>(46845/46846)| **`RegulatedAuthorization.text`**
| | | | | | | `RegulatedAuthorization.contained`| _Equivalent_<br/>(46847/46848)| **`RegulatedAuthorization.contained`**
| | | | | | | `RegulatedAuthorization.extension`| _Equivalent_<br/>(46849/46850)| **`RegulatedAuthorization.extension`**
| | | | | | | `RegulatedAuthorization.modifierExtension`| _Equivalent_<br/>(46851/46852)| **`RegulatedAuthorization.modifierExtension`**
| | | | | | | `RegulatedAuthorization.identifier`| _Equivalent_<br/>(46853/46854)| **`RegulatedAuthorization.identifier`**
| | | | | | | `RegulatedAuthorization.subject`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(46855)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(46856)| **`RegulatedAuthorization.subject`**
| | | | | | | `RegulatedAuthorization.type`| _Equivalent_<br/>(46857/46858)| **`RegulatedAuthorization.type`**
| | | | | | | `RegulatedAuthorization.description`| _Equivalent_<br/>(46859/46860)| **`RegulatedAuthorization.description`**
| | | | | | | `RegulatedAuthorization.region`| _Equivalent_<br/>(46861/46862)| **`RegulatedAuthorization.region`**
| | | | | | | `RegulatedAuthorization.status`| _Equivalent_<br/>(46863/46864)| **`RegulatedAuthorization.status`**
| | | | | | | `RegulatedAuthorization.statusDate`| _Equivalent_<br/>(46865/46866)| **`RegulatedAuthorization.statusDate`**
| | | | | | | `RegulatedAuthorization.validityPeriod`| _Equivalent_<br/>(46867/46868)| **`RegulatedAuthorization.validityPeriod`**
| | | | | | | `RegulatedAuthorization.indication`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(46869)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(46870)| **`RegulatedAuthorization.indication`**
| | | | | | | `RegulatedAuthorization.intendedUse`| _Equivalent_<br/>(46871/46872)| **`RegulatedAuthorization.intendedUse`**
| | | | | | | `RegulatedAuthorization.basis`| _Equivalent_<br/>(46873/46874)| **`RegulatedAuthorization.basis`**
| | | | | | | `RegulatedAuthorization.holder`| _Equivalent_<br/>(46875/46876)| **`RegulatedAuthorization.holder`**
| | | | | | | `RegulatedAuthorization.regulator`| _Equivalent_<br/>(46877/46878)| **`RegulatedAuthorization.regulator`**
| | | | | | | | | **`RegulatedAuthorization.attachedDocument`**
| | | | | | | `RegulatedAuthorization.case`| _Equivalent_<br/>(46879/46880)| **`RegulatedAuthorization.case`**
| | | | | | | `RegulatedAuthorization.case.id`| _Equivalent_<br/>(46881/46882)| **`RegulatedAuthorization.case.id`**
| | | | | | | `RegulatedAuthorization.case.extension`| _Equivalent_<br/>(46883/46884)| **`RegulatedAuthorization.case.extension`**
| | | | | | | `RegulatedAuthorization.case.modifierExtension`| _Equivalent_<br/>(46885/46886)| **`RegulatedAuthorization.case.modifierExtension`**
| | | | | | | `RegulatedAuthorization.case.identifier`| _Equivalent_<br/>(46887/46888)| **`RegulatedAuthorization.case.identifier`**
| | | | | | | `RegulatedAuthorization.case.type`| _Equivalent_<br/>(46889/46890)| **`RegulatedAuthorization.case.type`**
| | | | | | | `RegulatedAuthorization.case.status`| _Equivalent_<br/>(46891/46892)| **`RegulatedAuthorization.case.status`**
| | | | | | | `RegulatedAuthorization.case.date[x]`| _Equivalent_<br/>(46893/46894)| **`RegulatedAuthorization.case.date[x]`**
| | | | | | | `RegulatedAuthorization.case.application`| _Equivalent_<br/>(46895/46896)| **`RegulatedAuthorization.case.application`**
| | | | | | | *31 of 31 elements used* | | *32 of 32 elements used* 

