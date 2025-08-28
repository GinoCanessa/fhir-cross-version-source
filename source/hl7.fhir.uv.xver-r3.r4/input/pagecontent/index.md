
The Cross-Version Extensions for FHIR (XVer) project provides a set of packages that define extensions, profiles, and value sets for cross-version compatibility in FHIR. These packages are designed to support the validation and interoperability of FHIR resources across different versions.

### About This Guide

Cross-version extension content is generated via a combination of automatic differential detection and manual editing.

For details or questions, please reach out on [Zulip](https://chat.fhir.org/#narrow/channel/426854-FHIR-cross-version-issues) or
to the FHIR Infrastructure WorkGroup.

### Goals

* Ability to use elements from another version of FHIR
* Encode information **added** in a *newer* version of FHIR
  * Community identified additional data that is needed
  * Need to provide a consistent way of representing it in an earlier version of FHIR
* Encode information **removed** in a *newer* version of FHIR
  * Community decided data was no longer necessary
  * Need to provide a consistent way of representing it in a later version of FHIR
    * Version migration requires interoperability between versions and cannot break old expectations
    * Scenarios where data needs to round-trip conversion between different versions

### Known Limitations

* Not 100% coverage of all elements in all versions
    * `Resource` type elements are excluded (e.g., R5:`Bundle.issues`)
* Mappings are generally between adjacent versions, so "back-and-forth" conversions may be needlessly verbose
* Large / infinite value sets (e.g., UCUM, LOINC, MIME) are excluded and assumed 'equivalent' across versions

### Intellectual Property Statements

{% include ip-statements.xhtml %}