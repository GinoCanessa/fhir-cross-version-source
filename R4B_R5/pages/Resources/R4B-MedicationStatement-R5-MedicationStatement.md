Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MedicationStatement |  | A record of a medication that is being consumed by a patient.   A MedicationStatement may indicate that the patient may be taking the medication now or has taken the medication in the past or will be taking the medication in the future.  The source of this information can be the patient, significant other (such as a family member or spouse), or a clinician.  A common scenario where this information is captured is during the history taking process during a patient visit or stay.   The medication information may come from sources such as the patient's memory, from a prescription bottle,  or from a list of medications the patient, clinician or other party maintains. <br/><br/>The primary difference between a medication statement and a medication administration is that the medication administration has complete administration information and is based on actual administration information from the person who administered the medication.  A medication statement is often, if not always, less specific.  There is no required date/time when the medication was administered, in fact we only know that a source has reported the patient is taking this medication, where details such as time, quantity, or rate or even medication product may be incomplete or missing or less precise.  As stated earlier, the medication statement information may come from the patient's memory, from a prescription bottle or from a list of medications the patient, clinician or other party maintains.  Medication administration is more formal and is not missing detailed information. | 26 | 18 |
| Target | MedicationStatement |  | A record of a medication that is being consumed by a patient.   A MedicationStatement may indicate that the patient may be taking the medication now or has taken the medication in the past or will be taking the medication in the future.  The source of this information can be the patient, significant other (such as a family member or spouse), or a clinician.  A common scenario where this information is captured is during the history taking process during a patient visit or stay.   The medication information may come from sources such as the patient's memory, from a prescription bottle,  or from a list of medications the patient, clinician or other party maintains. <br/><br/>The primary difference between a medicationstatement and a medicationadministration is that the medication administration has complete administration information and is based on actual administration information from the person who administered the medication.  A medicationstatement is often, if not always, less specific.  There is no required date/time when the medication was administered, in fact we only know that a source has reported the patient is taking this medication, where details such as time, quantity, or rate or even medication product may be incomplete or missing or less precise.  As stated earlier, the Medication Statement information may come from the patient's memory, from a prescription bottle or from a list of medications the patient, clinician or other party maintains.  Medication administration is more formal and is not missing detailed information. | 31 | 20 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 6 |
Equivalent | 4 |
RelatedTo | 16 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MedicationStatement | MedicationStatement | Equivalent | R4B `MedicationStatement` maps as Equivalent to R5 `MedicationStatement` |
| MedicationStatement.basedOn | - | DoesNotExistInTarget | R4B `MedicationStatement.basedOn` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.category | MedicationStatement.category | RelatedTo | R4B `MedicationStatement.category` maps as RelatedTo to R5 `MedicationStatement.category` - category changed from scalar to array (max cardinality from 1 to *); category changed the binding strength from Preferred to Example |
| MedicationStatement.contained | MedicationStatement.contained | Equivalent | R4B `MedicationStatement.contained` maps as Equivalent to R5 `MedicationStatement.contained` |
| MedicationStatement.context | - | DoesNotExistInTarget | R4B `MedicationStatement.context` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.dateAsserted | MedicationStatement.dateAsserted | Equivalent | R4B `MedicationStatement.dateAsserted` maps as Equivalent to R5 `MedicationStatement.dateAsserted` |
| MedicationStatement.derivedFrom | MedicationStatement.derivedFrom | Equivalent | R4B `MedicationStatement.derivedFrom` maps as Equivalent to R5 `MedicationStatement.derivedFrom` |
| MedicationStatement.dosage | MedicationStatement.dosage | RelatedTo | R4B `MedicationStatement.dosage` maps as RelatedTo to R5 `MedicationStatement.dosage` - dosage has change due to type change: R4B `dosage` `Dosage` maps as RelatedTo for R5 `dosage` |
| MedicationStatement.effective[x] | MedicationStatement.effective[x] | Equivalent | R4B `MedicationStatement.effective[x]` maps as Equivalent to R5 `MedicationStatement.effective[x]` |
| MedicationStatement.extension | MedicationStatement.extension | RelatedTo | R4B `MedicationStatement.extension` maps as RelatedTo to R5 `MedicationStatement.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicationStatement.id | MedicationStatement.id | Equivalent | R4B `MedicationStatement.id` maps as Equivalent to R5 `MedicationStatement.id` |
| MedicationStatement.identifier | MedicationStatement.identifier | Equivalent | R4B `MedicationStatement.identifier` maps as Equivalent to R5 `MedicationStatement.identifier` |
| MedicationStatement.implicitRules | MedicationStatement.implicitRules | Equivalent | R4B `MedicationStatement.implicitRules` maps as Equivalent to R5 `MedicationStatement.implicitRules` |
| MedicationStatement.informationSource | MedicationStatement.informationSource | RelatedTo | R4B `MedicationStatement.informationSource` maps as RelatedTo to R5 `MedicationStatement.informationSource` - informationSource changed from scalar to array (max cardinality from 1 to *) |
| MedicationStatement.language | MedicationStatement.language | RelatedTo | R4B `MedicationStatement.language` maps as RelatedTo to R5 `MedicationStatement.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| MedicationStatement.medication[x] | - | DoesNotExistInTarget | R4B `MedicationStatement.medication[x]` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.meta | MedicationStatement.meta | Equivalent | R4B `MedicationStatement.meta` maps as Equivalent to R5 `MedicationStatement.meta` |
| MedicationStatement.modifierExtension | MedicationStatement.modifierExtension | RelatedTo | R4B `MedicationStatement.modifierExtension` maps as RelatedTo to R5 `MedicationStatement.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicationStatement.note | MedicationStatement.note | SourceIsNarrowerThanTarget | R4B `MedicationStatement.note` maps as SourceIsNarrowerThanTarget to R5 `MedicationStatement.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| MedicationStatement.partOf | MedicationStatement.partOf | SourceIsBroaderThanTarget | R4B `MedicationStatement.partOf` maps as SourceIsBroaderThanTarget to R5 `MedicationStatement.partOf` - partOf has change due to type change: R4B `partOf` `Reference` maps as SourceIsBroaderThanTarget for R5 `partOf` |
| MedicationStatement.reasonCode | - | DoesNotExistInTarget | R4B `MedicationStatement.reasonCode` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.reasonReference | - | DoesNotExistInTarget | R4B `MedicationStatement.reasonReference` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.status | MedicationStatement.status | SourceIsNarrowerThanTarget | R4B `MedicationStatement.status` maps as SourceIsNarrowerThanTarget to R5 `MedicationStatement.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/medication-statement-status|4.3.0 and http://hl7.org/fhir/ValueSet/medication-statement-status|5.0.0 (SourceIsNarrowerThanTarget) |
| MedicationStatement.statusReason | - | DoesNotExistInTarget | R4B `MedicationStatement.statusReason` does not appear in the target and has no mapping for `MedicationStatement`. |
| MedicationStatement.subject | MedicationStatement.subject | Equivalent | R4B `MedicationStatement.subject` maps as Equivalent to R5 `MedicationStatement.subject` |
| MedicationStatement.text | MedicationStatement.text | Equivalent | R4B `MedicationStatement.text` maps as Equivalent to R5 `MedicationStatement.text` |

