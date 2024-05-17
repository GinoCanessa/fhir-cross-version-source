Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MedicationStatement |  | A record of a medication that is being consumed by a patient.   A MedicationStatement may indicate that the patient may be taking the medication now or has taken the medication in the past or will be taking the medication in the future.  The source of this information can be the patient, significant other (such as a family member or spouse), or a clinician.  A common scenario where this information is captured is during the history taking process during a patient visit or stay.   The medication information may come from sources such as the patient's memory, from a prescription bottle,  or from a list of medications the patient, clinician or other party maintains. <br/><br/>The primary difference between a medicationstatement and a medicationadministration is that the medication administration has complete administration information and is based on actual administration information from the person who administered the medication.  A medicationstatement is often, if not always, less specific.  There is no required date/time when the medication was administered, in fact we only know that a source has reported the patient is taking this medication, where details such as time, quantity, or rate or even medication product may be incomplete or missing or less precise.  As stated earlier, the Medication Statement information may come from the patient's memory, from a prescription bottle or from a list of medications the patient, clinician or other party maintains.  Medication administration is more formal and is not missing detailed information. | 31 | 20 |
| Target | MedicationStatement |  | A record of a medication that is being consumed by a patient.   A MedicationStatement may indicate that the patient may be taking the medication now or has taken the medication in the past or will be taking the medication in the future.  The source of this information can be the patient, significant other (such as a family member or spouse), or a clinician.  A common scenario where this information is captured is during the history taking process during a patient visit or stay.   The medication information may come from sources such as the patient's memory, from a prescription bottle,  or from a list of medications the patient, clinician or other party maintains. <br/><br/>The primary difference between a medication statement and a medication administration is that the medication administration has complete administration information and is based on actual administration information from the person who administered the medication.  A medication statement is often, if not always, less specific.  There is no required date/time when the medication was administered, in fact we only know that a source has reported the patient is taking this medication, where details such as time, quantity, or rate or even medication product may be incomplete or missing or less precise.  As stated earlier, the medication statement information may come from the patient's memory, from a prescription bottle or from a list of medications the patient, clinician or other party maintains.  Medication administration is more formal and is not missing detailed information. | 26 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 11 |
Equivalent | 4 |
RelatedTo | 16 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MedicationStatement | MedicationStatement | Equivalent | R5 `MedicationStatement` maps as Equivalent to R4B `MedicationStatement` |
| MedicationStatement.adherence | - | DoesNotExistInTarget | R5 `MedicationStatement.adherence` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.adherence.code | - | DoesNotExistInTarget | R5 `MedicationStatement.adherence.code` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.adherence.extension | - | DoesNotExistInTarget | R5 `MedicationStatement.adherence.extension` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.adherence.id | - | DoesNotExistInTarget | R5 `MedicationStatement.adherence.id` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.adherence.modifierExtension | - | DoesNotExistInTarget | R5 `MedicationStatement.adherence.modifierExtension` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.adherence.reason | - | DoesNotExistInTarget | R5 `MedicationStatement.adherence.reason` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.category | MedicationStatement.category | RelatedTo | R5 `MedicationStatement.category` maps as RelatedTo to R4B `MedicationStatement.category` - category changed from array to scalar (max cardinality from * to 1); category changed the binding strength from Example to Preferred |
| MedicationStatement.contained | MedicationStatement.contained | Equivalent | R5 `MedicationStatement.contained` maps as Equivalent to R4B `MedicationStatement.contained` |
| MedicationStatement.dateAsserted | MedicationStatement.dateAsserted | Equivalent | R5 `MedicationStatement.dateAsserted` maps as Equivalent to R4B `MedicationStatement.dateAsserted` |
| MedicationStatement.derivedFrom | MedicationStatement.derivedFrom | Equivalent | R5 `MedicationStatement.derivedFrom` maps as Equivalent to R4B `MedicationStatement.derivedFrom` |
| MedicationStatement.dosage | MedicationStatement.dosage | RelatedTo | R5 `MedicationStatement.dosage` maps as RelatedTo to R4B `MedicationStatement.dosage` - dosage has change due to type change: R5 `dosage` `Dosage` maps as RelatedTo for R4B `dosage` |
| MedicationStatement.effective[x] | MedicationStatement.effective[x] | SourceIsBroaderThanTarget | R5 `MedicationStatement.effective[x]` maps as SourceIsBroaderThanTarget to R4B `MedicationStatement.effective[x]` - effective[x] has change due to type change: R5 effective[x] Timing has no equivalent or mapped type in R4B effective[x] |
| MedicationStatement.encounter | - | DoesNotExistInTarget | R5 `MedicationStatement.encounter` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.extension | MedicationStatement.extension | SourceIsBroaderThanTarget | R5 `MedicationStatement.extension` maps as SourceIsBroaderThanTarget to R4B `MedicationStatement.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| MedicationStatement.id | MedicationStatement.id | Equivalent | R5 `MedicationStatement.id` maps as Equivalent to R4B `MedicationStatement.id` |
| MedicationStatement.identifier | MedicationStatement.identifier | Equivalent | R5 `MedicationStatement.identifier` maps as Equivalent to R4B `MedicationStatement.identifier` |
| MedicationStatement.implicitRules | MedicationStatement.implicitRules | Equivalent | R5 `MedicationStatement.implicitRules` maps as Equivalent to R4B `MedicationStatement.implicitRules` |
| MedicationStatement.informationSource | MedicationStatement.informationSource | RelatedTo | R5 `MedicationStatement.informationSource` maps as RelatedTo to R4B `MedicationStatement.informationSource` - informationSource changed from array to scalar (max cardinality from * to 1) |
| MedicationStatement.language | MedicationStatement.language | RelatedTo | R5 `MedicationStatement.language` maps as RelatedTo to R4B `MedicationStatement.language` - language changed the binding strength from Required to Preferred |
| MedicationStatement.medication | - | DoesNotExistInTarget | R5 `MedicationStatement.medication` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.meta | MedicationStatement.meta | Equivalent | R5 `MedicationStatement.meta` maps as Equivalent to R4B `MedicationStatement.meta` |
| MedicationStatement.modifierExtension | MedicationStatement.modifierExtension | SourceIsBroaderThanTarget | R5 `MedicationStatement.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `MedicationStatement.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| MedicationStatement.note | MedicationStatement.note | SourceIsBroaderThanTarget | R5 `MedicationStatement.note` maps as SourceIsBroaderThanTarget to R4B `MedicationStatement.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| MedicationStatement.partOf | MedicationStatement.partOf | SourceIsNarrowerThanTarget | R5 `MedicationStatement.partOf` maps as SourceIsNarrowerThanTarget to R4B `MedicationStatement.partOf` - partOf has change due to type change: R5 `partOf` `Reference` maps as SourceIsNarrowerThanTarget for R4B `partOf` |
| MedicationStatement.reason | - | DoesNotExistInTarget | R5 `MedicationStatement.reason` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.relatedClinicalInformation | - | DoesNotExistInTarget | R5 `MedicationStatement.relatedClinicalInformation` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.renderedDosageInstruction | - | DoesNotExistInTarget | R5 `MedicationStatement.renderedDosageInstruction` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.status | MedicationStatement.status | SourceIsBroaderThanTarget | R5 `MedicationStatement.status` maps as SourceIsBroaderThanTarget to R4B `MedicationStatement.status` - status has INCOMPATIBLE required binding for code type: http://hl7.org/fhir/ValueSet/medication-statement-status|5.0.0 and http://hl7.org/fhir/ValueSet/medication-statement-status|4.3.0 |
| MedicationStatement.subject | MedicationStatement.subject | Equivalent | R5 `MedicationStatement.subject` maps as Equivalent to R4B `MedicationStatement.subject` |
| MedicationStatement.text | MedicationStatement.text | Equivalent | R5 `MedicationStatement.text` maps as Equivalent to R4B `MedicationStatement.text` |

