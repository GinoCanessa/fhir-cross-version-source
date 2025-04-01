Comparison of 
Generated at Tuesday, April 1, 2025 1:39:35 PM

### AssertionResponseTypes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | AssertionResponseTypes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/assert-response-code-types` |
| Version | 5.0.0 |
| Description | The type of response code to use for assertion. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4305` |
| Database Concept Count | `44` |
| Database Active Concept Count | `44` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.assert.response` | `http://hl7.org/fhir/ValueSet/assert-response-code-types\|5.0.0` | `Required` | continue \| switchingProtocols \| okay \| created \| accepted \| nonAuthoritativeInformation \| noContent \| resetContent \| partialContent \| multipleChoices \| movedPermanently \| found \| seeOther \| notModified \| useProxy \| temporaryRedirect \| permanentRedirect \| badRequest \| unauthorized \| paymentRequired \| forbidden \| notFound \| methodNotAllowed \| notAcceptable \| proxyAuthenticationRequired \| requestTimeout \| conflict \| gone \| lengthRequired \| preconditionFailed \| contentTooLarge \| uriTooLong \| unsupportedMediaType \| rangeNotSatisfiable \| expectationFailed \| misdirectedRequest \| unprocessableContent \| upgradeRequired \| internalServerError \| notImplemented \| badGateway \| serviceUnavailable \| gatewayTimeout \| httpVersionNotSupported |

### Referenced Systems

* `http://hl7.org/fhir/assert-response-code-types`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AssertionResponseTypes](/docs/R2/ValueSets/AssertionResponseTypes.md)<br/> `http://hl7.org/fhir/ValueSet/assert-response-code-types\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `156`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `314`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AssertionResponseTypes](/docs/R3/ValueSets/AssertionResponseTypes.md)<br/> `http://hl7.org/fhir/ValueSet/assert-response-code-types\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `536`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `758`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AssertionResponseTypes](/docs/R4/ValueSets/AssertionResponseTypes.md)<br/> `http://hl7.org/fhir/ValueSet/assert-response-code-types\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1391`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1392`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AssertionResponseTypes](/docs/R4B/ValueSets/AssertionResponseTypes.md)<br/> `http://hl7.org/fhir/ValueSet/assert-response-code-types\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1019`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `1280`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AssertionResponseTypes](/docs/R5/ValueSets/AssertionResponseTypes.md)<br/> `http://hl7.org/fhir/ValueSet/assert-response-code-types\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set AssertionResponseTypes from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 AssertionResponseTypes](/docs/R2/ValueSets/AssertionResponseTypes.md)| Relationship | [R3 AssertionResponseTypes](/docs/R3/ValueSets/AssertionResponseTypes.md)| Relationship | [R4 AssertionResponseTypes](/docs/R4/ValueSets/AssertionResponseTypes.md)| Relationship | [R4B AssertionResponseTypes](/docs/R4B/ValueSets/AssertionResponseTypes.md)| Relationship | R5 AssertionResponseTypes
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/assert-response-code-types`
| | | | | | | | | **`continue`**
| | | | | | | | | **`switchingProtocols`**
| `okay`| _Equivalent_ <br/>(1333/2792)| `okay`| _Equivalent_ <br/>(4978/7323)| `okay`| _Equivalent_ <br/>(14512/14513)| `okay`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9563)<hr/>←←←← _Equivalent_ ←←←← <br/>(11928) | **`okay`**
| `created`| _Equivalent_ <br/>(1337/2796)| `created`| _Equivalent_ <br/>(4982/7327)| `created`| _Equivalent_ <br/>(14514/14515)| `created`| _Equivalent_ <br/>(9568/11909)| **`created`**
| `okay`| _Equivalent_ <br/>(1333/2792)| `okay`| _Equivalent_ <br/>(4978/7323)| `okay`| _Equivalent_ <br/>(14512/14513)| `okay`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9564)<hr/>←←←← _Equivalent_ ←←←← <br/>(11903) | **`accepted`**
| | | | | | | | | **`nonAuthoritativeInformation`**
| `noContent`| _Equivalent_ <br/>(1334/2793)| `noContent`| _Equivalent_ <br/>(4979/7324)| `noContent`| _Equivalent_ <br/>(14516/14517)| `noContent`| _Equivalent_ <br/>(9565/11922)| **`noContent`**
| | | | | | | | | **`resetContent`**
| | | | | | | | | **`partialContent`**
| | | | | | | | | **`multipleChoices`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9581)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11920) | **`movedPermanently`**
| | | | | | | | | **`found`**
| | | | | | | | | **`seeOther`**
| `notModified`| _Equivalent_ <br/>(1336/2795)| `notModified`| _Equivalent_ <br/>(4981/7326)| `notModified`| _Equivalent_ <br/>(14518/14519)| `notModified`| _Equivalent_ <br/>(9567/11927)| **`notModified`**
| | | | | | | | | **`useProxy`**
| | | | | | | | | **`temporaryRedirect`**
| | | | | | | | | **`permanentRedirect`**
| `bad`| _Equivalent_ <br/>(1335/2794)| `bad`| _Equivalent_ <br/>(4980/7325)| `bad`| _Equivalent_ <br/>(14520/14521)| `bad`| _Equivalent_ <br/>(9566/11905)| **`badRequest`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9590)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11942) | **`unauthorized`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9584)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11930) | **`paymentRequired`**
| `forbidden`| _Equivalent_ <br/>(1338/2797)| `forbidden`| _Equivalent_ <br/>(4983/7328)| `forbidden`| _Equivalent_ <br/>(14522/14523)| `forbidden`| _Equivalent_ <br/>(9569/11911)| **`forbidden`**
| `notFound`| _Equivalent_ <br/>(1340/2799)| `notFound`| _Equivalent_ <br/>(4985/7330)| `notFound`| _Equivalent_ <br/>(14524/14525)| `notFound`| _Equivalent_ <br/>(9571/11925)| **`notFound`**
| `methodNotAllowed`| _Equivalent_ <br/>(1339/2798)| `methodNotAllowed`| _Equivalent_ <br/>(4984/7329)| `methodNotAllowed`| _Equivalent_ <br/>(14526/14527)| `methodNotAllowed`| _Equivalent_ <br/>(9570/11918)| **`methodNotAllowed`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9582)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11924) | **`notAcceptable`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9586)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11934) | **`proxyAuthenticationRequired`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9588)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11936) | **`requestTimeout`**
| `conflict`| _Equivalent_ <br/>(1343/2802)| `conflict`| _Equivalent_ <br/>(4988/7333)| `conflict`| _Equivalent_ <br/>(14528/14529)| `conflict`| _Equivalent_ <br/>(9595/11906)| **`conflict`**
| `gone`| _Equivalent_ <br/>(1344/2803)| `gone`| _Equivalent_ <br/>(4989/7334)| `gone`| _Equivalent_ <br/>(14530/14531)| `gone`| _Equivalent_ <br/>(9596/11914)| **`gone`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9579)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11917) | **`lengthRequired`**
| `preconditionFailed`| _Equivalent_ <br/>(1341/2800)| `preconditionFailed`| _Equivalent_ <br/>(4986/7331)| `preconditionFailed`| _Equivalent_ <br/>(14532/14533)| `preconditionFailed`| →→→→ _Equivalent_ →→→→ <br/>(9572)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11933) | **`preconditionFailed`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9585)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11933) | **`preconditionFailed`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9574)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11907) | **`contentTooLarge`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9594)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11946) | **`uriTooLong`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9592)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11944) | **`unsupportedMediaType`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9587)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11935) | **`rangeNotSatisfiable`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9575)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11910) | **`expectationFailed`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9580)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11919) | **`misdirectedRequest`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9591)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11943) | **`unprocessableContent`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9593)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11945) | **`upgradeRequired`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9578)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11916) | **`internalServerError`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9583)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11926) | **`notImplemented`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9573)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11904) | **`badGateway`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9589)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11939) | **`serviceUnavailable`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9576)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11913) | **`gatewayTimeout`**
| `unprocessable`| _Equivalent_ <br/>(1342/2801)| `unprocessable`| _Equivalent_ <br/>(4987/7332)| `unprocessable`| _Equivalent_ <br/>(14534/14535)| `unprocessable`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11915) | **`httpVersionNotSupported`**
| *12 of 12 codes used* | | *12 of 12 codes used* | | *12 of 12 codes used* | | *12 of 12 codes used* | | *44 of 44 codes used* 

