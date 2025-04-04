Comparison of 
Generated at Friday, April 4, 2025 2:59:00 PM

### GenomicStudy

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | GenomicStudy |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/GenomicStudy` |
| Version | 5.0.0 |
| Description | A set of analyses performed to analyze and generate genomic data. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2313` |
| Database Snapshot Count | `66` |
| Database Differential Count | `43` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `GenomicStudy` | `GenomicStudy` | `GenomicStudy` | GenomicStudy | Genomic Study | 0..* | GenomicStudy |  |  |
| `GenomicStudy.analysis` | `GenomicStudy.analysis` | `analysis` | GenomicStudy.analysis | Genomic Analysis Event | 0..* | BackboneElement |  |  |
| `GenomicStudy.analysis.changeType` | `GenomicStudy.analysis.changeType` | `changeType` | GenomicStudy.analysis.changeType | Type of the genomic changes studied in the analysis (e.g., DNA, RNA, or AA change) | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/genomicstudy-changetype` |
| `GenomicStudy.analysis.date` | `GenomicStudy.analysis.date` | `date` | GenomicStudy.analysis.date | The date of the analysis event | 0..1 | dateTime |  |  |
| `GenomicStudy.analysis.device` | `GenomicStudy.analysis.device` | `device` | GenomicStudy.analysis.device | Devices used for the analysis (e.g., instruments, software), with settings and parameters | 0..* | BackboneElement |  |  |
| `GenomicStudy.analysis.device.device` | `GenomicStudy.analysis.device.device` | `device` | GenomicStudy.analysis.device.device | Device used for the analysis | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device) |  |  |
| `GenomicStudy.analysis.device.extension` | `GenomicStudy.analysis.device.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `GenomicStudy.analysis.device.function` | `GenomicStudy.analysis.device.function` | `function` | GenomicStudy.analysis.device.function | Specific function for the device used for the analysis | 0..1 | CodeableConcept |  |  |
| `GenomicStudy.analysis.device.id` | `GenomicStudy.analysis.device.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `GenomicStudy.analysis.device.modifierExtension` | `GenomicStudy.analysis.device.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `GenomicStudy.analysis.extension` | `GenomicStudy.analysis.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `GenomicStudy.analysis.focus` | `GenomicStudy.analysis.focus` | `focus` | GenomicStudy.analysis.focus | What the genomic analysis is about, when it is not about the subject of record | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `GenomicStudy.analysis.genomeBuild` | `GenomicStudy.analysis.genomeBuild` | `genomeBuild` | GenomicStudy.analysis.genomeBuild | Genome build that is used in this analysis | 0..1 | CodeableConcept | `Extensible` | `http://loinc.org/vs/LL1040-6` |
| `GenomicStudy.analysis.id` | `GenomicStudy.analysis.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `GenomicStudy.analysis.identifier` | `GenomicStudy.analysis.identifier` | `identifier` | GenomicStudy.analysis.identifier | Identifiers for the analysis event | 0..* | Identifier |  |  |
| `GenomicStudy.analysis.input` | `GenomicStudy.analysis.input` | `input` | GenomicStudy.analysis.input | Inputs for the analysis event | 0..* | BackboneElement |  |  |
| `GenomicStudy.analysis.input.extension` | `GenomicStudy.analysis.input.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `GenomicStudy.analysis.input.file` | `GenomicStudy.analysis.input.file` | `file` | GenomicStudy.analysis.input.file | File containing input data | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `GenomicStudy.analysis.input.generatedBy[x]` | `GenomicStudy.analysis.input.generatedBy[x]` | `generatedBy[x]` | GenomicStudy.analysis.input.generatedBy[x] | The analysis event or other GenomicStudy that generated this input file | 0..1 | Identifier, Reference(http://hl7.org/fhir/StructureDefinition/GenomicStudy) |  |  |
| `GenomicStudy.analysis.input.id` | `GenomicStudy.analysis.input.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `GenomicStudy.analysis.input.modifierExtension` | `GenomicStudy.analysis.input.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `GenomicStudy.analysis.input.type` | `GenomicStudy.analysis.input.type` | `type` | GenomicStudy.analysis.input.type | Type of input data (e.g., BAM, CRAM, or FASTA) | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/genomicstudy-dataformat` |
| `GenomicStudy.analysis.instantiatesCanonical` | `GenomicStudy.analysis.instantiatesCanonical` | `instantiatesCanonical` | GenomicStudy.analysis.instantiatesCanonical | The defined protocol that describes the analysis | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/ActivityDefinition), canonical(http://hl7.org/fhir/StructureDefinition/PlanDefinition) |  |  |
| `GenomicStudy.analysis.instantiatesUri` | `GenomicStudy.analysis.instantiatesUri` | `instantiatesUri` | GenomicStudy.analysis.instantiatesUri | The URL pointing to an externally maintained protocol that describes the analysis | 0..1 | uri |  |  |
| `GenomicStudy.analysis.methodType` | `GenomicStudy.analysis.methodType` | `methodType` | GenomicStudy.analysis.methodType | Type of the methods used in the analysis (e.g., FISH, Karyotyping, MSI) | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/genomicstudy-methodtype` |
| `GenomicStudy.analysis.modifierExtension` | `GenomicStudy.analysis.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `GenomicStudy.analysis.note` | `GenomicStudy.analysis.note` | `note` | GenomicStudy.analysis.note | Any notes capture with the analysis event | 0..* | Annotation |  |  |
| `GenomicStudy.analysis.output` | `GenomicStudy.analysis.output` | `output` | GenomicStudy.analysis.output | Outputs for the analysis event | 0..* | BackboneElement |  |  |
| `GenomicStudy.analysis.output.extension` | `GenomicStudy.analysis.output.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `GenomicStudy.analysis.output.file` | `GenomicStudy.analysis.output.file` | `file` | GenomicStudy.analysis.output.file | File containing output data | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `GenomicStudy.analysis.output.id` | `GenomicStudy.analysis.output.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `GenomicStudy.analysis.output.modifierExtension` | `GenomicStudy.analysis.output.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `GenomicStudy.analysis.output.type` | `GenomicStudy.analysis.output.type` | `type` | GenomicStudy.analysis.output.type | Type of output data (e.g., VCF, MAF, or BAM) | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/genomicstudy-dataformat` |
| `GenomicStudy.analysis.performer` | `GenomicStudy.analysis.performer` | `performer` | GenomicStudy.analysis.performer | Performer for the analysis event | 0..* | BackboneElement |  |  |
| `GenomicStudy.analysis.performer.actor` | `GenomicStudy.analysis.performer.actor` | `actor` | GenomicStudy.analysis.performer.actor | The organization, healthcare professional, or others who participated in performing this analysis | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `GenomicStudy.analysis.performer.extension` | `GenomicStudy.analysis.performer.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `GenomicStudy.analysis.performer.id` | `GenomicStudy.analysis.performer.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `GenomicStudy.analysis.performer.modifierExtension` | `GenomicStudy.analysis.performer.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `GenomicStudy.analysis.performer.role` | `GenomicStudy.analysis.performer.role` | `role` | GenomicStudy.analysis.performer.role | Role of the actor for this analysis | 0..1 | CodeableConcept |  |  |
| `GenomicStudy.analysis.protocolPerformed` | `GenomicStudy.analysis.protocolPerformed` | `protocolPerformed` | GenomicStudy.analysis.protocolPerformed | The protocol that was performed for the analysis event | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Procedure), Reference(http://hl7.org/fhir/StructureDefinition/Task) |  |  |
| `GenomicStudy.analysis.regionsCalled` | `GenomicStudy.analysis.regionsCalled` | `regionsCalled` | GenomicStudy.analysis.regionsCalled | Genomic regions actually called in the analysis event (BED file) | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/Observation) |  |  |
| `GenomicStudy.analysis.regionsStudied` | `GenomicStudy.analysis.regionsStudied` | `regionsStudied` | GenomicStudy.analysis.regionsStudied | The genomic regions to be studied in the analysis (BED file) | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/Observation) |  |  |
| `GenomicStudy.analysis.specimen` | `GenomicStudy.analysis.specimen` | `specimen` | GenomicStudy.analysis.specimen | The specimen used in the analysis event | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Specimen) |  |  |
| `GenomicStudy.analysis.title` | `GenomicStudy.analysis.title` | `title` | GenomicStudy.analysis.title | Name of the analysis event (human friendly) | 0..1 | string |  |  |
| `GenomicStudy.basedOn` | `GenomicStudy.basedOn` | `basedOn` | GenomicStudy.basedOn | Event resources that the genomic study is based on | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ServiceRequest), Reference(http://hl7.org/fhir/StructureDefinition/Task) |  |  |
| `GenomicStudy.contained` | `GenomicStudy.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `GenomicStudy.description` | `GenomicStudy.description` | `description` | GenomicStudy.description | Description of the genomic study | 0..1 | markdown |  |  |
| `GenomicStudy.encounter` | `GenomicStudy.encounter` | `encounter` | GenomicStudy.encounter | The healthcare event with which this genomics study is associated | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `GenomicStudy.extension` | `GenomicStudy.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `GenomicStudy.id` | `GenomicStudy.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `GenomicStudy.identifier` | `GenomicStudy.identifier` | `identifier` | GenomicStudy.identifier | Identifiers for this genomic study | 0..* | Identifier |  |  |
| `GenomicStudy.implicitRules` | `GenomicStudy.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `GenomicStudy.instantiatesCanonical` | `GenomicStudy.instantiatesCanonical` | `instantiatesCanonical` | GenomicStudy.instantiatesCanonical | The defined protocol that describes the study | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/PlanDefinition) |  |  |
| `GenomicStudy.instantiatesUri` | `GenomicStudy.instantiatesUri` | `instantiatesUri` | GenomicStudy.instantiatesUri | The URL pointing to an externally maintained protocol that describes the study | 0..1 | uri |  |  |
| `GenomicStudy.interpreter` | `GenomicStudy.interpreter` | `interpreter` | GenomicStudy.interpreter | Healthcare professionals who interpreted the genomic study | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `GenomicStudy.language` | `GenomicStudy.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `GenomicStudy.meta` | `GenomicStudy.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `GenomicStudy.modifierExtension` | `GenomicStudy.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `GenomicStudy.note` | `GenomicStudy.note` | `note` | GenomicStudy.note | Comments related to the genomic study | 0..* | Annotation |  |  |
| `GenomicStudy.reason` | `GenomicStudy.reason` | `reason` | GenomicStudy.reason | Why the genomic study was performed | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/Condition), CodeableReference(http://hl7.org/fhir/StructureDefinition/Observation) |  |  |
| `GenomicStudy.referrer` | `GenomicStudy.referrer` | `referrer` | GenomicStudy.referrer | Healthcare professional who requested or referred the genomic study | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `GenomicStudy.startDate` | `GenomicStudy.startDate` | `startDate` | GenomicStudy.startDate | When the genomic study was started | 0..1 | dateTime |  |  |
| `GenomicStudy.status` | `GenomicStudy.status` | `status` | GenomicStudy.status | registered \| available \| cancelled \| entered-in-error \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/genomicstudy-status|5.0.0` |
| `GenomicStudy.subject` | `GenomicStudy.subject` | `subject` | GenomicStudy.subject | The primary subject of the genomic study | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/NutritionProduct), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `GenomicStudy.text` | `GenomicStudy.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `GenomicStudy.type` | `GenomicStudy.type` | `type` | GenomicStudy.type | The type of the study (e.g., Familial variant segregation, Functional variation detection, or Gene expression profiling) | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/genomicstudy-type` |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

