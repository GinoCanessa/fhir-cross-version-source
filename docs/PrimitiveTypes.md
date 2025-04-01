Comparison of 
Generated at Tuesday, April 1, 2025 1:39:05 PM

## Primitive Type Mappings

Primitive types are mapped across all versions using the following table.

Note that in this table, "concept" refers to the FHIR concept domain and "value" refers to the FHIR value domain.

The statement: "`typeA` and `typeB` are conceptually interchangeable where appropriate" means that when an *element* provides
the appropriate context, the concepts are not so disparate that they cannot be used.  For example, an element that
was defined as a `id` in one version could be defined as a `code` in another version. While the types do not
*inherently* have a conceptual overlap, the context of the element allows the substitution.  This is different than if
an element was defined as an `boolean` and changed to a `dateTime`, which do not have the ability to be conceptually mapped.

| Source Type | Target Type | Concept Relationship | Concept Comment | Value Relationship | Value Comment |
| --- | --- | --- | --- | --- | --- |
| `base64Binary` | `base64Binary` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `boolean` | `boolean` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `canonical` | `canonical` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `canonical` | `string` | `Equivalent` | canonical and string are conceptually interchangeable where appropriate | `SourceIsNarrowerThanTarget` | `canonical` covers a smaller value domain than `string` |
| `canonical` | `uri` | `Equivalent` | canonical and uri are conceptually interchangeable where appropriate | `Equivalent` | `canonical` and `uri` cover the same value domain |
| `code` | `code` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `code` | `id` | `Equivalent` | code and id are conceptually interchangeable where appropriate | `SourceIsBroaderThanTarget` | `code covers a larger value domain than `id` |
| `code` | `string` | `Equivalent` | code and string are conceptually interchangeable where appropriate | `Equivalent` | `code` and `string` cover the same value domain |
| `code` | `oid` | `Equivalent` | code and oid are conceptually interchangeable where appropriate | `SourceIsBroaderThanTarget` | `code covers a larger value domain than `oid` |
| `code` | `uri` | `Equivalent` | code and uri are conceptually interchangeable where appropriate | `SourceIsBroaderThanTarget` | `code covers a larger value domain than `uri` |
| `date` | `date` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `date` | `dateTime` | `Equivalent` | date and dateTime are conceptually interchangeable where appropriate | `SourceIsNarrowerThanTarget` | `date` covers a smaller value domain than `dateTime` |
| `dateTime` | `dateTime` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `dateTime` | `date` | `Equivalent` | dateTime and date are conceptually interchangeable where appropriate | `SourceIsBroaderThanTarget` | `dateTime covers a larger value domain than `date` |
| `decimal` | `decimal` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `decimal` | `unsignedInt` | `Equivalent` | decimal and unsignedInt are conceptually interchangeable where appropriate | `SourceIsBroaderThanTarget` | `decimal covers a larger value domain than `unsignedInt` |
| `id` | `id` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `id` | `code` | `Equivalent` | id and code are conceptually interchangeable where appropriate | `SourceIsNarrowerThanTarget` | `id` covers a smaller value domain than `code` |
| `id` | `oid` | `Equivalent` | id and oid are conceptually interchangeable where appropriate | `SourceIsBroaderThanTarget` | `id covers a larger value domain than `oid` |
| `id` | `string` | `Equivalent` | id and string are conceptually interchangeable where appropriate | `SourceIsNarrowerThanTarget` | `id` covers a smaller value domain than `string` |
| `instant` | `instant` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `integer` | `integer` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `integer` | `integer64` | `Equivalent` | integer and integer64 are conceptually interchangeable where appropriate | `SourceIsNarrowerThanTarget` | `integer` covers a smaller value domain than `integer64` |
| `integer` | `positiveInt` | `Equivalent` | integer and positiveInt are conceptually interchangeable where appropriate | `SourceIsBroaderThanTarget` | `integer covers a larger value domain than `positiveInt` |
| `integer` | `unsignedInt` | `Equivalent` | integer and unsignedInt are conceptually interchangeable where appropriate | `SourceIsBroaderThanTarget` | `integer covers a larger value domain than `unsignedInt` |
| `integer64` | `integer64` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `integer64` | `integer` | `Equivalent` | integer64 and integer are conceptually interchangeable where appropriate | `SourceIsBroaderThanTarget` | `integer64 covers a larger value domain than `integer` |
| `integer64` | `string` | `Equivalent` | integer64 and string are conceptually interchangeable where appropriate | `SourceIsNarrowerThanTarget` | `integer64` covers a smaller value domain than `string` |
| `markdown` | `markdown` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `markdown` | `string` | `Equivalent` | markdown and string are conceptually interchangeable where appropriate | `Equivalent` | `markdown` and `string` cover the same value domain |
| `oid` | `oid` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `oid` | `code` | `Equivalent` | oid and code are conceptually interchangeable where appropriate | `SourceIsNarrowerThanTarget` | `oid` covers a smaller value domain than `code` |
| `oid` | `id` | `Equivalent` | oid and id are conceptually interchangeable where appropriate | `SourceIsNarrowerThanTarget` | `oid` covers a smaller value domain than `id` |
| `oid` | `string` | `Equivalent` | oid and string are conceptually interchangeable where appropriate | `SourceIsNarrowerThanTarget` | `oid` covers a smaller value domain than `string` |
| `positiveInt` | `positiveInt` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `positiveInt` | `integer` | `Equivalent` | positiveInt and integer are conceptually interchangeable where appropriate | `SourceIsNarrowerThanTarget` | `positiveInt` covers a smaller value domain than `integer` |
| `positiveInt` | `unsignedInt` | `Equivalent` | positiveInt and unsignedInt are conceptually interchangeable where appropriate | `SourceIsBroaderThanTarget` | `positiveInt covers a larger value domain than `unsignedInt` |
| `string` | `string` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `string` | `canonical` | `Equivalent` | string and canonical are conceptually interchangeable where appropriate | `SourceIsBroaderThanTarget` | `string covers a larger value domain than `canonical` |
| `string` | `code` | `Equivalent` | string and code are conceptually interchangeable where appropriate | `Equivalent` | `string` and `code` cover the same value domain |
| `string` | `id` | `Equivalent` | string and id are conceptually interchangeable where appropriate | `SourceIsBroaderThanTarget` | `string covers a larger value domain than `id` |
| `string` | `integer64` | `Equivalent` | string and integer64 are conceptually interchangeable where appropriate | `SourceIsBroaderThanTarget` | `string covers a larger value domain than `integer64` |
| `string` | `markdown` | `Equivalent` | string and markdown are conceptually interchangeable where appropriate | `Equivalent` | `string` and `markdown` cover the same value domain |
| `string` | `oid` | `Equivalent` | string and oid are conceptually interchangeable where appropriate | `SourceIsBroaderThanTarget` | `string covers a larger value domain than `oid` |
| `string` | `uri` | `Equivalent` | string and uri are conceptually interchangeable where appropriate | `SourceIsBroaderThanTarget` | `string covers a larger value domain than `uri` |
| `time` | `time` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `unsignedInt` | `unsignedInt` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `unsignedInt` | `decimal` | `Equivalent` | unsignedInt and decimal are conceptually interchangeable where appropriate | `SourceIsNarrowerThanTarget` | `unsignedInt` covers a smaller value domain than `decimal` |
| `unsignedInt` | `integer` | `Equivalent` | unsignedInt and integer are conceptually interchangeable where appropriate | `SourceIsNarrowerThanTarget` | `unsignedInt` covers a smaller value domain than `integer` |
| `unsignedInt` | `positiveInt` | `Equivalent` | unsignedInt and positiveInt are conceptually interchangeable where appropriate | `SourceIsNarrowerThanTarget` | `unsignedInt` covers a smaller value domain than `positiveInt` |
| `uri` | `uri` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `uri` | `canonical` | `Equivalent` | uri and canonical are conceptually interchangeable where appropriate | `Equivalent` | `uri` and `canonical` cover the same value domain |
| `uri` | `code` | `Equivalent` | uri and code are conceptually interchangeable where appropriate | `SourceIsNarrowerThanTarget` | `uri` covers a smaller value domain than `code` |
| `uri` | `string` | `Equivalent` | uri and string are conceptually interchangeable where appropriate | `SourceIsNarrowerThanTarget` | `uri` covers a smaller value domain than `string` |
| `uri` | `url` | `Equivalent` | uri and url are conceptually interchangeable where appropriate | `Equivalent` | `uri` and `url` cover the same value domain |
| `url` | `url` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `url` | `uri` | `Equivalent` | url and uri are conceptually interchangeable where appropriate | `Equivalent` | `url` and `uri` cover the same value domain |
| `uuid` | `uuid` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
| `xhtml` | `xhtml` | `Equivalent` | The type is the same | `Equivalent` | The type is the same |
