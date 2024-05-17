Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:03 AM

| Side | Url | Name | Description |
| --- | --- | --- | --- |
| Source | http://hl7.org/fhir/StructureDefinition/dateTime | dateTime | Base StructureDefinition for dateTime Type: A date, date-time or partial date (e.g. just year or year + month).  If hours and minutes are specified, a time zone SHALL be populated. The format is a union of the schema types gYear, gYearMonth, date and dateTime. Seconds must be provided due to schema type constraints but may be zero-filled and may be ignored.                 Dates SHALL be valid dates. |
| Target | http://hl7.org/fhir/StructureDefinition/dateTime | dateTime | dateTime Type: A date, date-time or partial date (e.g. just year or year + month).  If hours and minutes are specified, a UTC offset SHALL be populated. The format is a union of the schema types gYear, gYearMonth, date and dateTime. Seconds must be provided due to schema type constraints but may be zero-filled and may be ignored.                 Dates SHALL be valid dates. |


Comparison Result: Equivalent


### Mapping details


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| dateTime | dateTime | Equivalent | R4B `dateTime` is equivalent to R5 `dateTime`. |

