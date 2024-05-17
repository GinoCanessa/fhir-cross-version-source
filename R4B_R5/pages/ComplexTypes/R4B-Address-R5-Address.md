Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:03 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Address |  | Base StructureDefinition for Address Type: An address expressed using postal conventions (as opposed to GPS or other location definition formats).  This data type may be used to convey addresses for use in delivering mail as well as for visiting locations which might not be valid for mail delivery.  There are a variety of postal address formats defined around the world. | 13 | 11 |
| Target | Address |  | Address Type: An address expressed using postal conventions (as opposed to GPS or other location definition formats).  This data type may be used to convey addresses for use in delivering mail as well as for visiting locations which might not be valid for mail delivery.  There are a variety of postal address formats defined around the world.<br/>The ISO21090-codedString may be used to provide a coded representation of the contents of strings in an Address. | 13 | 11 |


Comparison Result: Equivalent


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 13 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Address | Address | Equivalent | R4B `Address` maps as Equivalent to R5 `Address` |
| Address.city | Address.city | Equivalent | R4B `Address.city` maps as Equivalent to R5 `Address.city` |
| Address.country | Address.country | Equivalent | R4B `Address.country` maps as Equivalent to R5 `Address.country` |
| Address.district | Address.district | Equivalent | R4B `Address.district` maps as Equivalent to R5 `Address.district` |
| Address.extension | Address.extension | Equivalent | R4B `Address.extension` maps as Equivalent to R5 `Address.extension` |
| Address.id | Address.id | Equivalent | R4B `Address.id` maps as Equivalent to R5 `Address.id` |
| Address.line | Address.line | Equivalent | R4B `Address.line` maps as Equivalent to R5 `Address.line` |
| Address.period | Address.period | Equivalent | R4B `Address.period` maps as Equivalent to R5 `Address.period` |
| Address.postalCode | Address.postalCode | Equivalent | R4B `Address.postalCode` maps as Equivalent to R5 `Address.postalCode` |
| Address.state | Address.state | Equivalent | R4B `Address.state` maps as Equivalent to R5 `Address.state` |
| Address.text | Address.text | Equivalent | R4B `Address.text` maps as Equivalent to R5 `Address.text` |
| Address.type | Address.type | Equivalent | R4B `Address.type` maps as Equivalent to R5 `Address.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/address-type|4.3.0 and http://hl7.org/fhir/ValueSet/address-type|5.0.0 (Equivalent) |
| Address.use | Address.use | Equivalent | R4B `Address.use` maps as Equivalent to R5 `Address.use` - use has compatible required binding for code type: http://hl7.org/fhir/ValueSet/address-use|4.3.0 and http://hl7.org/fhir/ValueSet/address-use|5.0.0 (Equivalent) |

