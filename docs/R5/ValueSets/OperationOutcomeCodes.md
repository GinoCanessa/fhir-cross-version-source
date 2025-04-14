Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### OperationOutcomeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | OperationOutcomeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/operation-outcome` |
| Version | 5.0.0 |
| Description | Operation Outcome codes for translatable phrases used by FHIR test servers (see Implementation file translations.xml) |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4769` |
| Database Concept Count | `51` |
| Database Active Concept Count | `51` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/OperationOutcome` | `OperationOutcome.issue.details` | `http://hl7.org/fhir/ValueSet/operation-outcome` | `Example` | Additional details about the error |

### Referenced Systems

* `http://hl7.org/fhir/operation-outcome`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/operation-outcome` | `DELETE_MULTIPLE_MATCHES` | Error: Multiple matches exist for the conditional delete |
| `http://hl7.org/fhir/operation-outcome` | `MSG_AUTH_REQUIRED` | You must authenticate before you can use this service |
| `http://hl7.org/fhir/operation-outcome` | `MSG_BAD_FORMAT` | Bad Syntax: "%s" must be a %s' |
| `http://hl7.org/fhir/operation-outcome` | `MSG_BAD_SYNTAX` | Bad Syntax in %s |
| `http://hl7.org/fhir/operation-outcome` | `MSG_CANT_PARSE_CONTENT` | Unable to parse feed (entry content type = "%s") |
| `http://hl7.org/fhir/operation-outcome` | `MSG_CANT_PARSE_ROOT` | Unable to parse feed (root element name = "%s") |
| `http://hl7.org/fhir/operation-outcome` | `MSG_CREATED` | New resource created |
| `http://hl7.org/fhir/operation-outcome` | `MSG_DATE_FORMAT` | The Date value %s is not in the correct format (Xml Date Format required) |
| `http://hl7.org/fhir/operation-outcome` | `MSG_DELETED` | This resource has been deleted |
| `http://hl7.org/fhir/operation-outcome` | `MSG_DELETED_DONE` | Resource deleted |
| `http://hl7.org/fhir/operation-outcome` | `MSG_DELETED_ID` | The resource "%s" has been deleted |
| `http://hl7.org/fhir/operation-outcome` | `MSG_DUPLICATE_ID` | Duplicate Id %s for resource type %s |
| `http://hl7.org/fhir/operation-outcome` | `MSG_ERROR_PARSING` | Error parsing resource Xml (%s) |
| `http://hl7.org/fhir/operation-outcome` | `MSG_ID_INVALID` | Id "%s" has an invalid character "%s" |
| `http://hl7.org/fhir/operation-outcome` | `MSG_ID_TOO_LONG` | Id "%s" too long (length limit 36) |
| `http://hl7.org/fhir/operation-outcome` | `MSG_INVALID_ID` | Id not accepted |
| `http://hl7.org/fhir/operation-outcome` | `MSG_JSON_OBJECT` | Json Source for a resource should start with an object |
| `http://hl7.org/fhir/operation-outcome` | `MSG_LOCAL_FAIL` | Unable to resolve local reference to resource %s |
| `http://hl7.org/fhir/operation-outcome` | `MSG_NO_EXIST` | Resource Id "%s" does not exist |
| `http://hl7.org/fhir/operation-outcome` | `MSG_NO_MATCH` | No Resource found matching the query "%s" |
| `http://hl7.org/fhir/operation-outcome` | `MSG_NO_MODULE` | No module could be found to handle the request "%s" |
| `http://hl7.org/fhir/operation-outcome` | `MSG_NO_SUMMARY` | No Summary for this resource |
| `http://hl7.org/fhir/operation-outcome` | `MSG_OP_NOT_ALLOWED` | Operation %s not allowed for resource %s (due to local configuration) |
| `http://hl7.org/fhir/operation-outcome` | `MSG_PARAM_CHAINED` | Unknown chained parameter name "%s" |
| `http://hl7.org/fhir/operation-outcome` | `MSG_PARAM_INVALID` | Parameter "%s" content is invalid |
| `http://hl7.org/fhir/operation-outcome` | `MSG_PARAM_MODIFIER_INVALID` | Parameter "%s" modifier is invalid |
| `http://hl7.org/fhir/operation-outcome` | `MSG_PARAM_NO_REPEAT` | Parameter "%s" is not allowed to repeat |
| `http://hl7.org/fhir/operation-outcome` | `MSG_PARAM_UNKNOWN` | Parameter "%s" not understood |
| `http://hl7.org/fhir/operation-outcome` | `MSG_REMOTE_FAIL` | Unable to resolve local reference to resource %s |
| `http://hl7.org/fhir/operation-outcome` | `MSG_RESOURCE_EXAMPLE_PROTECTED` | Resources with identity "example" cannot be deleted (for testing/training purposes) |
| `http://hl7.org/fhir/operation-outcome` | `MSG_RESOURCE_ID_FAIL` | unable to allocate resource id |
| `http://hl7.org/fhir/operation-outcome` | `MSG_RESOURCE_ID_MISMATCH` | Resource Id Mismatch |
| `http://hl7.org/fhir/operation-outcome` | `MSG_RESOURCE_ID_MISSING` | Resource Id Missing |
| `http://hl7.org/fhir/operation-outcome` | `MSG_RESOURCE_NOT_ALLOWED` | Not allowed to submit a resource for this operation |
| `http://hl7.org/fhir/operation-outcome` | `MSG_RESOURCE_REQUIRED` | A resource is required |
| `http://hl7.org/fhir/operation-outcome` | `MSG_RESOURCE_TYPE_MISMATCH` | Resource Type Mismatch |
| `http://hl7.org/fhir/operation-outcome` | `MSG_SORT_UNKNOWN` | Unknown sort parameter name "%s" |
| `http://hl7.org/fhir/operation-outcome` | `MSG_TRANSACTION_DUPLICATE_ID` | Duplicate Identifier in transaction: %s |
| `http://hl7.org/fhir/operation-outcome` | `MSG_TRANSACTION_MISSING_ID` | Missing Identifier in transaction - an entry.id must be provided |
| `http://hl7.org/fhir/operation-outcome` | `MSG_UNHANDLED_NODE_TYPE` | Unhandled xml node type "%s" |
| `http://hl7.org/fhir/operation-outcome` | `MSG_UNKNOWN_CONTENT` | Unknown Content (%s) at %s |
| `http://hl7.org/fhir/operation-outcome` | `MSG_UNKNOWN_OPERATION` | unknown FHIR http operation |
| `http://hl7.org/fhir/operation-outcome` | `MSG_UNKNOWN_TYPE` | Resource Type "%s" not recognised |
| `http://hl7.org/fhir/operation-outcome` | `MSG_UPDATED` | existing resource updated |
| `http://hl7.org/fhir/operation-outcome` | `MSG_VERSION_AWARE` | Version aware updates are required for this resource |
| `http://hl7.org/fhir/operation-outcome` | `MSG_VERSION_AWARE_CONFLICT` | Update Conflict (server current version = "%s", client version referenced = "%s") |
| `http://hl7.org/fhir/operation-outcome` | `MSG_VERSION_AWARE_URL` | Version specific URL not recognised |
| `http://hl7.org/fhir/operation-outcome` | `MSG_WRONG_NS` | This does not appear to be a FHIR element or resource (wrong namespace "%s") |
| `http://hl7.org/fhir/operation-outcome` | `SEARCH_MULTIPLE` | Error: Multiple matches exist for %s search parameters "%s" |
| `http://hl7.org/fhir/operation-outcome` | `SEARCH_NONE` | Error: no processable search found for %s search parameters "%s" |
| `http://hl7.org/fhir/operation-outcome` | `UPDATE_MULTIPLE_MATCHES` | Error: Multiple matches exist for the conditional update |
