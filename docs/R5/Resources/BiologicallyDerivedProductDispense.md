Comparison of 
Generated at Thursday, April 3, 2025 8:18:34 AM

### BiologicallyDerivedProductDispense

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | BiologicallyDerivedProductDispense |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProductDispense` |
| Version | 5.0.0 |
| Description | A record of dispensation of a biologically derived product. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2261` |
| Database Snapshot Count | `30` |
| Database Differential Count | `19` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `BiologicallyDerivedProductDispense` | `BiologicallyDerivedProductDispense` | `BiologicallyDerivedProductDispense` | BiologicallyDerivedProductDispense | A record of dispensation of a biologically derived product | 0..* | BiologicallyDerivedProductDispense |  |  |
| `BiologicallyDerivedProductDispense.basedOn` | `BiologicallyDerivedProductDispense.basedOn` | `basedOn` | BiologicallyDerivedProductDispense.basedOn | The order or request that this dispense is fulfilling | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ServiceRequest) |  |  |
| `BiologicallyDerivedProductDispense.contained` | `BiologicallyDerivedProductDispense.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `BiologicallyDerivedProductDispense.destination` | `BiologicallyDerivedProductDispense.destination` | `destination` | BiologicallyDerivedProductDispense.destination | Where the product was dispatched to | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `BiologicallyDerivedProductDispense.extension` | `BiologicallyDerivedProductDispense.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `BiologicallyDerivedProductDispense.id` | `BiologicallyDerivedProductDispense.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `BiologicallyDerivedProductDispense.identifier` | `BiologicallyDerivedProductDispense.identifier` | `identifier` | BiologicallyDerivedProductDispense.identifier | Business identifier for this dispense | 0..* | Identifier |  |  |
| `BiologicallyDerivedProductDispense.implicitRules` | `BiologicallyDerivedProductDispense.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `BiologicallyDerivedProductDispense.language` | `BiologicallyDerivedProductDispense.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `BiologicallyDerivedProductDispense.location` | `BiologicallyDerivedProductDispense.location` | `location` | BiologicallyDerivedProductDispense.location | Where the dispense occurred | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `BiologicallyDerivedProductDispense.matchStatus` | `BiologicallyDerivedProductDispense.matchStatus` | `matchStatus` | BiologicallyDerivedProductDispense.matchStatus | Indicates the type of matching associated with the dispense | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/biologicallyderivedproductdispense-match-status` |
| `BiologicallyDerivedProductDispense.meta` | `BiologicallyDerivedProductDispense.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `BiologicallyDerivedProductDispense.modifierExtension` | `BiologicallyDerivedProductDispense.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `BiologicallyDerivedProductDispense.note` | `BiologicallyDerivedProductDispense.note` | `note` | BiologicallyDerivedProductDispense.note | Additional notes | 0..* | Annotation |  |  |
| `BiologicallyDerivedProductDispense.originRelationshipType` | `BiologicallyDerivedProductDispense.originRelationshipType` | `originRelationshipType` | BiologicallyDerivedProductDispense.originRelationshipType | Relationship between the donor and intended recipient | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/biologicallyderivedproductdispense-origin-relationship` |
| `BiologicallyDerivedProductDispense.partOf` | `BiologicallyDerivedProductDispense.partOf` | `partOf` | BiologicallyDerivedProductDispense.partOf | Short description | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProductDispense) |  |  |
| `BiologicallyDerivedProductDispense.patient` | `BiologicallyDerivedProductDispense.patient` | `patient` | BiologicallyDerivedProductDispense.patient | The intended recipient of the dispensed product | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `BiologicallyDerivedProductDispense.performer` | `BiologicallyDerivedProductDispense.performer` | `performer` | BiologicallyDerivedProductDispense.performer | Indicates who or what performed an action | 0..* | BackboneElement |  |  |
| `BiologicallyDerivedProductDispense.performer.actor` | `BiologicallyDerivedProductDispense.performer.actor` | `actor` | BiologicallyDerivedProductDispense.performer.actor | Who performed the action | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `BiologicallyDerivedProductDispense.performer.extension` | `BiologicallyDerivedProductDispense.performer.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `BiologicallyDerivedProductDispense.performer.function` | `BiologicallyDerivedProductDispense.performer.function` | `function` | BiologicallyDerivedProductDispense.performer.function | Identifies the function of the performer during the dispense | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/biologicallyderivedproductdispense-performer-function` |
| `BiologicallyDerivedProductDispense.performer.id` | `BiologicallyDerivedProductDispense.performer.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `BiologicallyDerivedProductDispense.performer.modifierExtension` | `BiologicallyDerivedProductDispense.performer.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `BiologicallyDerivedProductDispense.preparedDate` | `BiologicallyDerivedProductDispense.preparedDate` | `preparedDate` | BiologicallyDerivedProductDispense.preparedDate | When product was selected/matched | 0..1 | dateTime |  |  |
| `BiologicallyDerivedProductDispense.product` | `BiologicallyDerivedProductDispense.product` | `product` | BiologicallyDerivedProductDispense.product | The BiologicallyDerivedProduct that is dispensed | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct) |  |  |
| `BiologicallyDerivedProductDispense.quantity` | `BiologicallyDerivedProductDispense.quantity` | `quantity` | BiologicallyDerivedProductDispense.quantity | Amount dispensed | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `BiologicallyDerivedProductDispense.status` | `BiologicallyDerivedProductDispense.status` | `status` | BiologicallyDerivedProductDispense.status | preparation \| in-progress \| allocated \| issued \| unfulfilled \| returned \| entered-in-error \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/biologicallyderivedproductdispense-status|5.0.0` |
| `BiologicallyDerivedProductDispense.text` | `BiologicallyDerivedProductDispense.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `BiologicallyDerivedProductDispense.usageInstruction` | `BiologicallyDerivedProductDispense.usageInstruction` | `usageInstruction` | BiologicallyDerivedProductDispense.usageInstruction | Specific instructions for use | 0..1 | string |  |  |
| `BiologicallyDerivedProductDispense.whenHandedOver` | `BiologicallyDerivedProductDispense.whenHandedOver` | `whenHandedOver` | BiologicallyDerivedProductDispense.whenHandedOver | When the product was dispatched | 0..1 | dateTime |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

