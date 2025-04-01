Comparison of 
Generated at Tuesday, April 1, 2025 1:39:27 PM

### AssertionResponseTypes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | AssertionResponseTypes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/assert-response-code-types` |
| Version | 4.3.0 |
| Description | The type of response code to use for assertion. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3545` |
| Database Concept Count | `12` |
| Database Active Concept Count | `12` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.assert.response` | `http://hl7.org/fhir/ValueSet/assert-response-code-types\|4.3.0` | `Required` | okay \| created \| noContent \| notModified \| bad \| forbidden \| notFound \| methodNotAllowed \| conflict \| gone \| preconditionFailed \| unprocessable |

### Referenced Systems

* `http://hl7.org/fhir/assert-response-code-types`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AssertionResponseTypes](/docs/R2/ValueSets/AssertionResponseTypes.md)<br/> `http://hl7.org/fhir/ValueSet/assert-response-code-types\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `156`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `314`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AssertionResponseTypes](/docs/R3/ValueSets/AssertionResponseTypes.md)<br/> `http://hl7.org/fhir/ValueSet/assert-response-code-types\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `536`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `758`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AssertionResponseTypes](/docs/R4/ValueSets/AssertionResponseTypes.md)<br/> `http://hl7.org/fhir/ValueSet/assert-response-code-types\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1391`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1392`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AssertionResponseTypes](/docs/R4B/ValueSets/AssertionResponseTypes.md)<br/> `http://hl7.org/fhir/ValueSet/assert-response-code-types\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1019`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `1280`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AssertionResponseTypes](/docs/R5/ValueSets/AssertionResponseTypes.md)<br/> `http://hl7.org/fhir/ValueSet/assert-response-code-types\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set AssertionResponseTypes from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 AssertionResponseTypes](/docs/R2/ValueSets/AssertionResponseTypes.md)| Relationship | [R3 AssertionResponseTypes](/docs/R3/ValueSets/AssertionResponseTypes.md)| Relationship | [R4 AssertionResponseTypes](/docs/R4/ValueSets/AssertionResponseTypes.md)| Relationship | R4B AssertionResponseTypes| Relationship | [R5 AssertionResponseTypes](/docs/R5/ValueSets/AssertionResponseTypes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/assert-response-code-types`
| `okay`| _Equivalent_ <br/>(1333/2792)| `okay`| _Equivalent_ <br/>(4978/7323)| `okay`| _Equivalent_ <br/>(14512/14513)| **`okay`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9564)<hr/>←←←← _Equivalent_ ←←←← <br/>(11903) | `okay`
| `okay`| _Equivalent_ <br/>(1333/2792)| `okay`| _Equivalent_ <br/>(4978/7323)| `okay`| _Equivalent_ <br/>(14512/14513)| **`okay`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9564)<hr/>←←←← _Equivalent_ ←←←← <br/>(11903) | `accepted`
| `created`| _Equivalent_ <br/>(1337/2796)| `created`| _Equivalent_ <br/>(4982/7327)| `created`| _Equivalent_ <br/>(14514/14515)| **`created`**| _Equivalent_ <br/>(9568/11909)| `created`
| `noContent`| _Equivalent_ <br/>(1334/2793)| `noContent`| _Equivalent_ <br/>(4979/7324)| `noContent`| _Equivalent_ <br/>(14516/14517)| **`noContent`**| _Equivalent_ <br/>(9565/11922)| `noContent`
| `notModified`| _Equivalent_ <br/>(1336/2795)| `notModified`| _Equivalent_ <br/>(4981/7326)| `notModified`| _Equivalent_ <br/>(14518/14519)| **`notModified`**| _Equivalent_ <br/>(9567/11927)| `notModified`
| `bad`| _Equivalent_ <br/>(1335/2794)| `bad`| _Equivalent_ <br/>(4980/7325)| `bad`| _Equivalent_ <br/>(14520/14521)| **`bad`**| _Equivalent_ <br/>(9566/11905)| `badRequest`
| `forbidden`| _Equivalent_ <br/>(1338/2797)| `forbidden`| _Equivalent_ <br/>(4983/7328)| `forbidden`| _Equivalent_ <br/>(14522/14523)| **`forbidden`**| _Equivalent_ <br/>(9569/11911)| `forbidden`
| `notFound`| _Equivalent_ <br/>(1340/2799)| `notFound`| _Equivalent_ <br/>(4985/7330)| `notFound`| _Equivalent_ <br/>(14524/14525)| **`notFound`**| _Equivalent_ <br/>(9571/11925)| `notFound`
| `methodNotAllowed`| _Equivalent_ <br/>(1339/2798)| `methodNotAllowed`| _Equivalent_ <br/>(4984/7329)| `methodNotAllowed`| _Equivalent_ <br/>(14526/14527)| **`methodNotAllowed`**| _Equivalent_ <br/>(9570/11918)| `methodNotAllowed`
| `conflict`| _Equivalent_ <br/>(1343/2802)| `conflict`| _Equivalent_ <br/>(4988/7333)| `conflict`| _Equivalent_ <br/>(14528/14529)| **`conflict`**| _Equivalent_ <br/>(9595/11906)| `conflict`
| `gone`| _Equivalent_ <br/>(1344/2803)| `gone`| _Equivalent_ <br/>(4989/7334)| `gone`| _Equivalent_ <br/>(14530/14531)| **`gone`**| _Equivalent_ <br/>(9596/11914)| `gone`
| `preconditionFailed`| _Equivalent_ <br/>(1341/2800)| `preconditionFailed`| _Equivalent_ <br/>(4986/7331)| `preconditionFailed`| _Equivalent_ <br/>(14532/14533)| **`preconditionFailed`**| →→→→ _Equivalent_ →→→→ <br/>(9572)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11932) | `preconditionFailed`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `movedPermanently`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `unauthorized`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `paymentRequired`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `notAcceptable`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `proxyAuthenticationRequired`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `requestTimeout`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `lengthRequired`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `preconditionFailed`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `contentTooLarge`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `uriTooLong`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `unsupportedMediaType`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `rangeNotSatisfiable`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `expectationFailed`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `misdirectedRequest`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `unprocessableContent`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `upgradeRequired`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `internalServerError`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `notImplemented`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `badGateway`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `serviceUnavailable`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `gatewayTimeout`
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| **`unprocessable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | `httpVersionNotSupported`
| *12 of 12 codes used* | | *12 of 12 codes used* | | *12 of 12 codes used* | | *12 of 12 codes used* | | *33 of 44 codes used* 

