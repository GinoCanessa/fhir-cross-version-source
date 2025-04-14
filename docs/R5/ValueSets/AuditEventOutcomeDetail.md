Comparison of 
Generated at Monday, April 14, 2025 6:17:42 PM

### AuditEventOutcomeDetail

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | AuditEventOutcomeDetail |
| Canonical URL | `http://hl7.org/fhir/ValueSet/audit-event-outcome-detail` |
| Version | 5.0.0 |
| Description | Indicates more detailed reason for outcome. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4310` |
| Database Concept Count | `51` |
| Database Active Concept Count | `51` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.outcome.detail` | `http://hl7.org/fhir/ValueSet/audit-event-outcome-detail` | `Example` | Additional outcome detail |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/operation-outcome`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `DELETE_MULTIPLE_MATCHES` | Error: Multiple matches exist for the conditional delete |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_AUTH_REQUIRED` | You must authenticate before you can use this service |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_BAD_FORMAT` | Bad Syntax: "%s" must be a %s' |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_BAD_SYNTAX` | Bad Syntax in %s |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_CANT_PARSE_CONTENT` | Unable to parse feed (entry content type = "%s") |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_CANT_PARSE_ROOT` | Unable to parse feed (root element name = "%s") |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_CREATED` | New resource created |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_DATE_FORMAT` | The Date value %s is not in the correct format (Xml Date Format required) |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_DELETED` | This resource has been deleted |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_DELETED_DONE` | Resource deleted |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_DELETED_ID` | The resource "%s" has been deleted |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_DUPLICATE_ID` | Duplicate Id %s for resource type %s |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_ERROR_PARSING` | Error parsing resource Xml (%s) |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_EXTERNAL_FAIL` | Unable to resolve external reference to resource %s |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_ID_INVALID` | Id "%s" has an invalid character "%s" |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_ID_TOO_LONG` | Id "%s" too long (length limit 36) |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_INVALID_ID` | Id not accepted |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_JSON_OBJECT` | Json Source for a resource should start with an object |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_LOCAL_FAIL` | Unable to resolve local reference to resource %s |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_NO_EXIST` | Resource Id "%s" does not exist |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_NO_MATCH` | No Resource found matching the query "%s" |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_NO_MODULE` | No module could be found to handle the request "%s" |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_NO_SUMMARY` | No Summary for this resource |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_OP_NOT_ALLOWED` | Operation %s not allowed for resource %s (due to local configuration) |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_PARAM_CHAINED` | Unknown chained parameter name "%s" |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_PARAM_INVALID` | Parameter "%s" content is invalid |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_PARAM_MODIFIER_INVALID` | Parameter "%s" modifier is invalid |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_PARAM_NO_REPEAT` | Parameter "%s" is not allowed to repeat |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_PARAM_UNKNOWN` | Parameter "%s" not understood |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_RESOURCE_EXAMPLE_PROTECTED` | Resources with identity "example" cannot be deleted (for testing/training purposes) |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_RESOURCE_ID_FAIL` | unable to allocate resource id |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_RESOURCE_ID_MISMATCH` | Resource Id Mismatch |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_RESOURCE_ID_MISSING` | Resource Id Missing |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_RESOURCE_NOT_ALLOWED` | Not allowed to submit a resource for this operation |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_RESOURCE_REQUIRED` | A resource is required |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_RESOURCE_TYPE_MISMATCH` | Resource Type Mismatch |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_SORT_UNKNOWN` | Unknown sort parameter name "%s" |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_TRANSACTION_DUPLICATE_ID` | Duplicate Identifier in transaction: %s |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_TRANSACTION_MISSING_ID` | Missing Identifier in transaction - an entry.id must be provided |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_UNHANDLED_NODE_TYPE` | Unhandled xml node type "%s" |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_UNKNOWN_CONTENT` | Unknown Content (%s) at %s |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_UNKNOWN_OPERATION` | unknown FHIR http operation |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_UNKNOWN_TYPE` | Resource Type "%s" not recognised |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_UPDATED` | existing resource updated |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_VERSION_AWARE` | Version aware updates are required for this resource |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_VERSION_AWARE_CONFLICT` | Update Conflict (server current version = "%s", client version referenced = "%s") |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_VERSION_AWARE_URL` | Version specific URL not recognised |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `MSG_WRONG_NS` | This does not appear to be a FHIR element or resource (wrong namespace "%s") |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `SEARCH_MULTIPLE` | Error: Multiple matches exist for %s search parameters "%s" |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `SEARCH_NONE` | Error: no processable search found for %s search parameters "%s" |
| `http://terminology.hl7.org/CodeSystem/operation-outcome` | `UPDATE_MULTIPLE_MATCHES` | Error: Multiple matches exist for the conditional update |
