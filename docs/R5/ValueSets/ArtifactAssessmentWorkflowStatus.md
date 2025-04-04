Comparison of 
Generated at Friday, April 4, 2025 2:58:59 PM

### ArtifactAssessmentWorkflowStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ArtifactAssessmentWorkflowStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/artifactassessment-workflow-status` |
| Version | 5.0.0 |
| Description | Possible values for the workflow status of the comment or assessment, typically used to coordinate workflow around the process of accepting and rejecting changes and comments on the artifact. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4301` |
| Database Concept Count | `10` |
| Database Active Concept Count | `10` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ArtifactAssessment` | `ArtifactAssessment.workflowStatus` | `http://hl7.org/fhir/ValueSet/artifactassessment-workflow-status\|5.0.0` | `Required` | submitted \| triaged \| waiting-for-input \| resolved-no-change \| resolved-change-required \| deferred \| duplicate \| applied \| published \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/artifactassessment-workflow-status`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/artifactassessment-workflow-status` | `applied` | Applied |
| `http://hl7.org/fhir/artifactassessment-workflow-status` | `deferred` | Deferred |
| `http://hl7.org/fhir/artifactassessment-workflow-status` | `duplicate` | Duplicate |
| `http://hl7.org/fhir/artifactassessment-workflow-status` | `entered-in-error` | Entered in Error |
| `http://hl7.org/fhir/artifactassessment-workflow-status` | `published` | Published |
| `http://hl7.org/fhir/artifactassessment-workflow-status` | `resolved-change-required` | Resolved - Change Required |
| `http://hl7.org/fhir/artifactassessment-workflow-status` | `resolved-no-change` | Resolved - No Change |
| `http://hl7.org/fhir/artifactassessment-workflow-status` | `submitted` | Submitted |
| `http://hl7.org/fhir/artifactassessment-workflow-status` | `triaged` | Triaged |
| `http://hl7.org/fhir/artifactassessment-workflow-status` | `waiting-for-input` | Waiting for Input |
