Comparison of 
Generated at Thursday, April 3, 2025 8:18:18 AM

### SubstanceAmount

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | SubstanceAmount |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SubstanceAmount` |
| Version | 4.0.1 |
| Description | Base StructureDefinition for SubstanceAmount Type: Chemical substances are a single substance type whose primary defining element is the molecular structure. Chemical substances shall be defined on the basis of their complete covalent molecular structure; the presence of a salt (counter-ion) and/or solvates (water, alcohols) is also captured. Purity, grade, physical form or particle size are not taken into account in the definition of a chemical substance or in the assignment of a Substance ID. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `1027` |
| Database Snapshot Count | `12` |
| Database Differential Count | `7` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SubstanceAmount` | `SubstanceAmount` | `SubstanceAmount` | SubstanceAmount | Chemical substances are a single substance type whose primary defining element is the molecular structure. Chemical substances shall be defined on the basis of their complete covalent molecular structure; the presence of a salt (counter-ion) and/or solvates (water, alcohols) is also captured. Purity, grade, physical form or particle size are not taken into account in the definition of a chemical substance or in the assignment of a Substance ID | 0..* | SubstanceAmount |  |  |
| `SubstanceAmount.amountText` | `SubstanceAmount.amountText` | `amountText` | SubstanceAmount.amountText | A textual comment on a numeric value | 0..1 | string |  |  |
| `SubstanceAmount.amountType` | `SubstanceAmount.amountType` | `amountType` | SubstanceAmount.amountType | Most elements that require a quantitative value will also have a field called amount type. Amount type should always be specified because the actual value of the amount is often dependent on it. EXAMPLE: In capturing the actual relative amounts of substances or molecular fragments it is essential to indicate whether the amount refers to a mole ratio or weight ratio. For any given element an effort should be made to use same the amount type for all related definitional elements | 0..1 | CodeableConcept |  |  |
| `SubstanceAmount.amount[x]` | `SubstanceAmount.amount[x]` | `amount[x]` | SubstanceAmount.amount[x] | Used to capture quantitative values for a variety of elements. If only limits are given, the arithmetic mean would be the average. If only a single definite value for a given element is given, it would be captured in this field | 0..1 | Quantity, Range, string |  |  |
| `SubstanceAmount.extension` | `SubstanceAmount.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceAmount.id` | `SubstanceAmount.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceAmount.modifierExtension` | `SubstanceAmount.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceAmount.referenceRange` | `SubstanceAmount.referenceRange` | `referenceRange` | SubstanceAmount.referenceRange | Reference range of possible or expected values | 0..1 | Element |  |  |
| `SubstanceAmount.referenceRange.extension` | `SubstanceAmount.referenceRange.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceAmount.referenceRange.highLimit` | `SubstanceAmount.referenceRange.highLimit` | `highLimit` | SubstanceAmount.referenceRange.highLimit | Upper limit possible or expected | 0..1 | Quantity |  |  |
| `SubstanceAmount.referenceRange.id` | `SubstanceAmount.referenceRange.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceAmount.referenceRange.lowLimit` | `SubstanceAmount.referenceRange.lowLimit` | `lowLimit` | SubstanceAmount.referenceRange.lowLimit | Lower limit possible or expected | 0..1 | Quantity |  |  |
### Empty Projection

This Structure (ComplexType) resulted in no projection (no mappings to other packages).

