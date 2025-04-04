Comparison of 
Generated at Friday, April 4, 2025 2:58:53 PM

### Bundle

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | Bundle |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Bundle` |
| Version | 4.3.0 |
| Description | A container for a collection of resources. |
| Status | `Active` |
| Artifact Class | `Resource` |
| Database Key | `1650` |
| Database Snapshot Count | `48` |
| Database Differential Count | `29` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Bundle` | `Bundle` | `Bundle` | Bundle | Contains a collection of resources | 0..* | Bundle |  |  |
| `Bundle.entry` | `Bundle.entry` | `entry` | Bundle.entry | Entry in the bundle - will have a resource or information | 0..* | BackboneElement |  |  |
| `Bundle.entry.extension` | `Bundle.entry.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Bundle.entry.fullUrl` | `Bundle.entry.fullUrl` | `fullUrl` | Bundle.entry.fullUrl | URI for resource (Absolute URL server address or URI for UUID/OID) | 0..1 | uri |  |  |
| `Bundle.entry.id` | `Bundle.entry.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Bundle.entry.link` | `Bundle.entry.link` | `link` | Bundle.entry.link | Links related to this entry | 0..* | Bundle.link |  |  |
| `Bundle.entry.modifierExtension` | `Bundle.entry.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Bundle.entry.request` | `Bundle.entry.request` | `request` | Bundle.entry.request | Additional execution information (transaction/batch/history) | 0..1 | BackboneElement |  |  |
| `Bundle.entry.request.extension` | `Bundle.entry.request.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Bundle.entry.request.id` | `Bundle.entry.request.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Bundle.entry.request.ifMatch` | `Bundle.entry.request.ifMatch` | `ifMatch` | Bundle.entry.request.ifMatch | For managing update contention | 0..1 | string |  |  |
| `Bundle.entry.request.ifModifiedSince` | `Bundle.entry.request.ifModifiedSince` | `ifModifiedSince` | Bundle.entry.request.ifModifiedSince | For managing cache currency | 0..1 | instant |  |  |
| `Bundle.entry.request.ifNoneExist` | `Bundle.entry.request.ifNoneExist` | `ifNoneExist` | Bundle.entry.request.ifNoneExist | For conditional creates | 0..1 | string |  |  |
| `Bundle.entry.request.ifNoneMatch` | `Bundle.entry.request.ifNoneMatch` | `ifNoneMatch` | Bundle.entry.request.ifNoneMatch | For managing cache currency | 0..1 | string |  |  |
| `Bundle.entry.request.method` | `Bundle.entry.request.method` | `method` | Bundle.entry.request.method | GET \| HEAD \| POST \| PUT \| DELETE \| PATCH | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/http-verb|4.3.0` |
| `Bundle.entry.request.modifierExtension` | `Bundle.entry.request.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Bundle.entry.request.url` | `Bundle.entry.request.url` | `url` | Bundle.entry.request.url | URL for HTTP equivalent of this entry | 1..1 | uri |  |  |
| `Bundle.entry.resource` | `Bundle.entry.resource` | `resource` | Bundle.entry.resource | A resource in the bundle | 0..1 | Resource |  |  |
| `Bundle.entry.response` | `Bundle.entry.response` | `response` | Bundle.entry.response | Results of execution (transaction/batch/history) | 0..1 | BackboneElement |  |  |
| `Bundle.entry.response.etag` | `Bundle.entry.response.etag` | `etag` | Bundle.entry.response.etag | The Etag for the resource (if relevant) | 0..1 | string |  |  |
| `Bundle.entry.response.extension` | `Bundle.entry.response.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Bundle.entry.response.id` | `Bundle.entry.response.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Bundle.entry.response.lastModified` | `Bundle.entry.response.lastModified` | `lastModified` | Bundle.entry.response.lastModified | Server's date time modified | 0..1 | instant |  |  |
| `Bundle.entry.response.location` | `Bundle.entry.response.location` | `location` | Bundle.entry.response.location | The location (if the operation returns a location) | 0..1 | uri |  |  |
| `Bundle.entry.response.modifierExtension` | `Bundle.entry.response.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Bundle.entry.response.outcome` | `Bundle.entry.response.outcome` | `outcome` | Bundle.entry.response.outcome | OperationOutcome with hints and warnings (for batch/transaction) | 0..1 | Resource |  |  |
| `Bundle.entry.response.status` | `Bundle.entry.response.status` | `status` | Bundle.entry.response.status | Status response code (text optional) | 1..1 | string |  |  |
| `Bundle.entry.search` | `Bundle.entry.search` | `search` | Bundle.entry.search | Search related information | 0..1 | BackboneElement |  |  |
| `Bundle.entry.search.extension` | `Bundle.entry.search.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Bundle.entry.search.id` | `Bundle.entry.search.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Bundle.entry.search.mode` | `Bundle.entry.search.mode` | `mode` | Bundle.entry.search.mode | match \| include \| outcome - why this is in the result set | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/search-entry-mode|4.3.0` |
| `Bundle.entry.search.modifierExtension` | `Bundle.entry.search.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Bundle.entry.search.score` | `Bundle.entry.search.score` | `score` | Bundle.entry.search.score | Search ranking (between 0 and 1) | 0..1 | decimal |  |  |
| `Bundle.id` | `Bundle.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Bundle.identifier` | `Bundle.identifier` | `identifier` | Bundle.identifier | Persistent identifier for the bundle | 0..1 | Identifier |  |  |
| `Bundle.implicitRules` | `Bundle.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Bundle.language` | `Bundle.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `Bundle.link` | `Bundle.link` | `link` | Bundle.link | Links related to this Bundle | 0..* | BackboneElement |  |  |
| `Bundle.link.extension` | `Bundle.link.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Bundle.link.id` | `Bundle.link.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Bundle.link.modifierExtension` | `Bundle.link.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Bundle.link.relation` | `Bundle.link.relation` | `relation` | Bundle.link.relation | See http://www.iana.org/assignments/link-relations/link-relations.xhtml#link-relations-1 | 1..1 | string |  |  |
| `Bundle.link.url` | `Bundle.link.url` | `url` | Bundle.link.url | Reference details for the link | 1..1 | uri |  |  |
| `Bundle.meta` | `Bundle.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Bundle.signature` | `Bundle.signature` | `signature` | Bundle.signature | Digital Signature | 0..1 | Signature |  |  |
| `Bundle.timestamp` | `Bundle.timestamp` | `timestamp` | Bundle.timestamp | When the bundle was assembled | 0..1 | instant |  |  |
| `Bundle.total` | `Bundle.total` | `total` | Bundle.total | If search, the total number of matches | 0..1 | unsignedInt |  |  |
| `Bundle.type` | `Bundle.type` | `type` | Bundle.type | document \| message \| transaction \| transaction-response \| batch \| batch-response \| history \| searchset \| collection | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/bundle-type|4.3.0` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Bundle](/docs/R2/Resources/Bundle.md)<br/> `http://hl7.org/fhir/StructureDefinition/Bundle\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `80`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `246`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Bundle](/docs/R3/Resources/Bundle.md)<br/> `http://hl7.org/fhir/StructureDefinition/Bundle\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `425`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `621`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Bundle](/docs/R4/Resources/Bundle.md)<br/> `http://hl7.org/fhir/StructureDefinition/Bundle\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1409`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1410`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Bundle](/docs/R4B/Resources/Bundle.md)<br/> `http://hl7.org/fhir/StructureDefinition/Bundle\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `927`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1156`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Bundle](/docs/R5/Resources/Bundle.md)<br/> `http://hl7.org/fhir/StructureDefinition/Bundle\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Bundle from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Bundle](/docs/R2/Resources/Bundle.md)| Relationship | [R3 Bundle](/docs/R3/Resources/Bundle.md)| Relationship | [R4 Bundle](/docs/R4/Resources/Bundle.md)| Relationship | R4B Bundle| Relationship | [R5 Bundle](/docs/R5/Resources/Bundle.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Bundle`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3188)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3189)| `Bundle`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10468)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10469)| `Bundle`| _Equivalent_<br/>(22158/22159)| **`Bundle`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37193)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37194)| `Bundle`
| `Bundle.id`| _Equivalent_<br/>(3190/3191)| `Bundle.id`| _Equivalent_<br/>(10470/10471)| `Bundle.id`| _Equivalent_<br/>(22160/22161)| **`Bundle.id`**| _Equivalent_<br/>(37195/37196)| `Bundle.id`
| `Bundle.meta`| _Equivalent_<br/>(3192/3193)| `Bundle.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10472)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10473)| `Bundle.meta`| _Equivalent_<br/>(22162/22163)| **`Bundle.meta`**| _Equivalent_<br/>(37197/37198)| `Bundle.meta`
| `Bundle.implicitRules`| _Equivalent_<br/>(3194/3195)| `Bundle.implicitRules`| _Equivalent_<br/>(10474/10475)| `Bundle.implicitRules`| _Equivalent_<br/>(22164/22165)| **`Bundle.implicitRules`**| _Equivalent_<br/>(37199/37200)| `Bundle.implicitRules`
| `Bundle.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3196)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3197)| `Bundle.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10476)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(10477)| `Bundle.language`| _Equivalent_<br/>(22166/22167)| **`Bundle.language`**| _Equivalent_<br/>(37201/37202)| `Bundle.language`
| | | `Bundle.identifier`| _Equivalent_<br/>(10478/10479)| `Bundle.identifier`| _Equivalent_<br/>(22168/22169)| **`Bundle.identifier`**| _Equivalent_<br/>(37203/37204)| `Bundle.identifier`
| `Bundle.type`| _Equivalent_<br/>(3198/3199)| `Bundle.type`| _Equivalent_<br/>(10480/10481)| `Bundle.type`| _Equivalent_<br/>(22170/22171)| **`Bundle.type`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37205)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37206)| `Bundle.type`
| | | | | `Bundle.timestamp`| _Equivalent_<br/>(22172/22173)| **`Bundle.timestamp`**| _Equivalent_<br/>(37207/37208)| `Bundle.timestamp`
| `Bundle.total`| _Equivalent_<br/>(3200/3201)| `Bundle.total`| _Equivalent_<br/>(10482/10483)| `Bundle.total`| _Equivalent_<br/>(22174/22175)| **`Bundle.total`**| _Equivalent_<br/>(37209/37210)| `Bundle.total`
| `Bundle.link`| _Equivalent_<br/>(3202/3203)| `Bundle.link`| _Equivalent_<br/>(10484/10485)| `Bundle.link`| _Equivalent_<br/>(22176/22177)| **`Bundle.link`**| _Equivalent_<br/>(37211/37212)| `Bundle.link`
| `Bundle.link.id`| _Equivalent_<br/>(3204/3205)| `Bundle.link.id`| _Equivalent_<br/>(10486/10487)| `Bundle.link.id`| _Equivalent_<br/>(22178/22179)| **`Bundle.link.id`**| _Equivalent_<br/>(37213/37214)| `Bundle.link.id`
| `Bundle.link.extension`| _Equivalent_<br/>(3206/3207)| `Bundle.link.extension`| _Equivalent_<br/>(10488/10489)| `Bundle.link.extension`| _Equivalent_<br/>(22180/22181)| **`Bundle.link.extension`**| _Equivalent_<br/>(37215/37216)| `Bundle.link.extension`
| `Bundle.link.modifierExtension`| _Equivalent_<br/>(3208/3209)| `Bundle.link.modifierExtension`| _Equivalent_<br/>(10490/10491)| `Bundle.link.modifierExtension`| _Equivalent_<br/>(22182/22183)| **`Bundle.link.modifierExtension`**| _Equivalent_<br/>(37217/37218)| `Bundle.link.modifierExtension`
| `Bundle.link.relation`| _Equivalent_<br/>(3210/3211)| `Bundle.link.relation`| _Equivalent_<br/>(10492/10493)| `Bundle.link.relation`| _Equivalent_<br/>(22184/22185)| **`Bundle.link.relation`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37219)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37220)| `Bundle.link.relation`
| `Bundle.link.url`| _Equivalent_<br/>(3212/3213)| `Bundle.link.url`| _Equivalent_<br/>(10494/10495)| `Bundle.link.url`| _Equivalent_<br/>(22186/22187)| **`Bundle.link.url`**| _Equivalent_<br/>(37221/37222)| `Bundle.link.url`
| `Bundle.entry`| _Equivalent_<br/>(3214/3215)| `Bundle.entry`| _Equivalent_<br/>(10496/10497)| `Bundle.entry`| _Equivalent_<br/>(22188/22189)| **`Bundle.entry`**| _Equivalent_<br/>(37223/37224)| `Bundle.entry`
| `Bundle.entry.id`| _Equivalent_<br/>(3216/3217)| `Bundle.entry.id`| _Equivalent_<br/>(10498/10499)| `Bundle.entry.id`| _Equivalent_<br/>(22190/22191)| **`Bundle.entry.id`**| _Equivalent_<br/>(37225/37226)| `Bundle.entry.id`
| `Bundle.entry.extension`| _Equivalent_<br/>(3218/3219)| `Bundle.entry.extension`| _Equivalent_<br/>(10500/10501)| `Bundle.entry.extension`| _Equivalent_<br/>(22192/22193)| **`Bundle.entry.extension`**| _Equivalent_<br/>(37227/37228)| `Bundle.entry.extension`
| `Bundle.entry.modifierExtension`| _Equivalent_<br/>(3220/3221)| `Bundle.entry.modifierExtension`| _Equivalent_<br/>(10502/10503)| `Bundle.entry.modifierExtension`| _Equivalent_<br/>(22194/22195)| **`Bundle.entry.modifierExtension`**| _Equivalent_<br/>(37229/37230)| `Bundle.entry.modifierExtension`
| `Bundle.entry.link`| _Equivalent_<br/>(3222/3223)| `Bundle.entry.link`| _Equivalent_<br/>(10504/10505)| `Bundle.entry.link`| _Equivalent_<br/>(22196/22197)| **`Bundle.entry.link`**| _Equivalent_<br/>(37231/37232)| `Bundle.entry.link`
| `Bundle.entry.fullUrl`| _Equivalent_<br/>(3224/3225)| `Bundle.entry.fullUrl`| _Equivalent_<br/>(10506/10507)| `Bundle.entry.fullUrl`| _Equivalent_<br/>(22198/22199)| **`Bundle.entry.fullUrl`**| _Equivalent_<br/>(37233/37234)| `Bundle.entry.fullUrl`
| `Bundle.entry.resource`| _Equivalent_<br/>(3226/3227)| `Bundle.entry.resource`| _Equivalent_<br/>(10508/10509)| `Bundle.entry.resource`| _Equivalent_<br/>(22200/22201)| **`Bundle.entry.resource`**| _Equivalent_<br/>(37235/37236)| `Bundle.entry.resource`
| `Bundle.entry.search`| _Equivalent_<br/>(3228/3229)| `Bundle.entry.search`| _Equivalent_<br/>(10510/10511)| `Bundle.entry.search`| _Equivalent_<br/>(22202/22203)| **`Bundle.entry.search`**| _Equivalent_<br/>(37237/37238)| `Bundle.entry.search`
| `Bundle.entry.search.id`| _Equivalent_<br/>(3230/3231)| `Bundle.entry.search.id`| _Equivalent_<br/>(10512/10513)| `Bundle.entry.search.id`| _Equivalent_<br/>(22204/22205)| **`Bundle.entry.search.id`**| _Equivalent_<br/>(37239/37240)| `Bundle.entry.search.id`
| `Bundle.entry.search.extension`| _Equivalent_<br/>(3232/3233)| `Bundle.entry.search.extension`| _Equivalent_<br/>(10514/10515)| `Bundle.entry.search.extension`| _Equivalent_<br/>(22206/22207)| **`Bundle.entry.search.extension`**| _Equivalent_<br/>(37241/37242)| `Bundle.entry.search.extension`
| `Bundle.entry.search.modifierExtension`| _Equivalent_<br/>(3234/3235)| `Bundle.entry.search.modifierExtension`| _Equivalent_<br/>(10516/10517)| `Bundle.entry.search.modifierExtension`| _Equivalent_<br/>(22208/22209)| **`Bundle.entry.search.modifierExtension`**| _Equivalent_<br/>(37243/37244)| `Bundle.entry.search.modifierExtension`
| `Bundle.entry.search.mode`| _Equivalent_<br/>(3236/3237)| `Bundle.entry.search.mode`| _Equivalent_<br/>(10518/10519)| `Bundle.entry.search.mode`| _Equivalent_<br/>(22210/22211)| **`Bundle.entry.search.mode`**| _Equivalent_<br/>(37245/37246)| `Bundle.entry.search.mode`
| `Bundle.entry.search.score`| _Equivalent_<br/>(3238/3239)| `Bundle.entry.search.score`| _Equivalent_<br/>(10520/10521)| `Bundle.entry.search.score`| _Equivalent_<br/>(22212/22213)| **`Bundle.entry.search.score`**| _Equivalent_<br/>(37247/37248)| `Bundle.entry.search.score`
| `Bundle.entry.request`| _Equivalent_<br/>(3240/3241)| `Bundle.entry.request`| _Equivalent_<br/>(10522/10523)| `Bundle.entry.request`| _Equivalent_<br/>(22214/22215)| **`Bundle.entry.request`**| _Equivalent_<br/>(37249/37250)| `Bundle.entry.request`
| `Bundle.entry.request.id`| _Equivalent_<br/>(3242/3243)| `Bundle.entry.request.id`| _Equivalent_<br/>(10524/10525)| `Bundle.entry.request.id`| _Equivalent_<br/>(22216/22217)| **`Bundle.entry.request.id`**| _Equivalent_<br/>(37251/37252)| `Bundle.entry.request.id`
| `Bundle.entry.request.extension`| _Equivalent_<br/>(3244/3245)| `Bundle.entry.request.extension`| _Equivalent_<br/>(10526/10527)| `Bundle.entry.request.extension`| _Equivalent_<br/>(22218/22219)| **`Bundle.entry.request.extension`**| _Equivalent_<br/>(37253/37254)| `Bundle.entry.request.extension`
| `Bundle.entry.request.modifierExtension`| _Equivalent_<br/>(3246/3247)| `Bundle.entry.request.modifierExtension`| _Equivalent_<br/>(10528/10529)| `Bundle.entry.request.modifierExtension`| _Equivalent_<br/>(22220/22221)| **`Bundle.entry.request.modifierExtension`**| _Equivalent_<br/>(37255/37256)| `Bundle.entry.request.modifierExtension`
| `Bundle.entry.request.method`| _Equivalent_<br/>(3248/3249)| `Bundle.entry.request.method`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10530)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10531)| `Bundle.entry.request.method`| _Equivalent_<br/>(22222/22223)| **`Bundle.entry.request.method`**| _Equivalent_<br/>(37257/37258)| `Bundle.entry.request.method`
| `Bundle.entry.request.url`| _Equivalent_<br/>(3250/3251)| `Bundle.entry.request.url`| _Equivalent_<br/>(10532/10533)| `Bundle.entry.request.url`| _Equivalent_<br/>(22224/22225)| **`Bundle.entry.request.url`**| _Equivalent_<br/>(37259/37260)| `Bundle.entry.request.url`
| `Bundle.entry.request.ifNoneMatch`| _Equivalent_<br/>(3252/3253)| `Bundle.entry.request.ifNoneMatch`| _Equivalent_<br/>(10534/10535)| `Bundle.entry.request.ifNoneMatch`| _Equivalent_<br/>(22226/22227)| **`Bundle.entry.request.ifNoneMatch`**| _Equivalent_<br/>(37261/37262)| `Bundle.entry.request.ifNoneMatch`
| `Bundle.entry.request.ifModifiedSince`| _Equivalent_<br/>(3254/3255)| `Bundle.entry.request.ifModifiedSince`| _Equivalent_<br/>(10536/10537)| `Bundle.entry.request.ifModifiedSince`| _Equivalent_<br/>(22228/22229)| **`Bundle.entry.request.ifModifiedSince`**| _Equivalent_<br/>(37263/37264)| `Bundle.entry.request.ifModifiedSince`
| `Bundle.entry.request.ifMatch`| _Equivalent_<br/>(3256/3257)| `Bundle.entry.request.ifMatch`| _Equivalent_<br/>(10538/10539)| `Bundle.entry.request.ifMatch`| _Equivalent_<br/>(22230/22231)| **`Bundle.entry.request.ifMatch`**| _Equivalent_<br/>(37265/37266)| `Bundle.entry.request.ifMatch`
| `Bundle.entry.request.ifNoneExist`| _Equivalent_<br/>(3258/3259)| `Bundle.entry.request.ifNoneExist`| _Equivalent_<br/>(10540/10541)| `Bundle.entry.request.ifNoneExist`| _Equivalent_<br/>(22232/22233)| **`Bundle.entry.request.ifNoneExist`**| _Equivalent_<br/>(37267/37268)| `Bundle.entry.request.ifNoneExist`
| `Bundle.entry.response`| _Equivalent_<br/>(3260/3261)| `Bundle.entry.response`| _Equivalent_<br/>(10542/10543)| `Bundle.entry.response`| _Equivalent_<br/>(22234/22235)| **`Bundle.entry.response`**| _Equivalent_<br/>(37269/37270)| `Bundle.entry.response`
| `Bundle.entry.response.id`| _Equivalent_<br/>(3262/3263)| `Bundle.entry.response.id`| _Equivalent_<br/>(10544/10545)| `Bundle.entry.response.id`| _Equivalent_<br/>(22236/22237)| **`Bundle.entry.response.id`**| _Equivalent_<br/>(37271/37272)| `Bundle.entry.response.id`
| `Bundle.entry.response.extension`| _Equivalent_<br/>(3264/3265)| `Bundle.entry.response.extension`| _Equivalent_<br/>(10546/10547)| `Bundle.entry.response.extension`| _Equivalent_<br/>(22238/22239)| **`Bundle.entry.response.extension`**| _Equivalent_<br/>(37273/37274)| `Bundle.entry.response.extension`
| `Bundle.entry.response.modifierExtension`| _Equivalent_<br/>(3266/3267)| `Bundle.entry.response.modifierExtension`| _Equivalent_<br/>(10548/10549)| `Bundle.entry.response.modifierExtension`| _Equivalent_<br/>(22240/22241)| **`Bundle.entry.response.modifierExtension`**| _Equivalent_<br/>(37275/37276)| `Bundle.entry.response.modifierExtension`
| `Bundle.entry.response.status`| _Equivalent_<br/>(3268/3269)| `Bundle.entry.response.status`| _Equivalent_<br/>(10550/10551)| `Bundle.entry.response.status`| _Equivalent_<br/>(22242/22243)| **`Bundle.entry.response.status`**| _Equivalent_<br/>(37277/37278)| `Bundle.entry.response.status`
| `Bundle.entry.response.location`| _Equivalent_<br/>(3270/3271)| `Bundle.entry.response.location`| _Equivalent_<br/>(10552/10553)| `Bundle.entry.response.location`| _Equivalent_<br/>(22244/22245)| **`Bundle.entry.response.location`**| _Equivalent_<br/>(37279/37280)| `Bundle.entry.response.location`
| `Bundle.entry.response.etag`| _Equivalent_<br/>(3272/3273)| `Bundle.entry.response.etag`| _Equivalent_<br/>(10554/10555)| `Bundle.entry.response.etag`| _Equivalent_<br/>(22246/22247)| **`Bundle.entry.response.etag`**| _Equivalent_<br/>(37281/37282)| `Bundle.entry.response.etag`
| `Bundle.entry.response.lastModified`| _Equivalent_<br/>(3274/3275)| `Bundle.entry.response.lastModified`| _Equivalent_<br/>(10556/10557)| `Bundle.entry.response.lastModified`| _Equivalent_<br/>(22248/22249)| **`Bundle.entry.response.lastModified`**| _Equivalent_<br/>(37283/37284)| `Bundle.entry.response.lastModified`
| | | `Bundle.entry.response.outcome`| _Equivalent_<br/>(10558/10559)| `Bundle.entry.response.outcome`| _Equivalent_<br/>(22250/22251)| **`Bundle.entry.response.outcome`**| _Equivalent_<br/>(37285/37286)| `Bundle.entry.response.outcome`
| `Bundle.signature`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3276)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3277)| `Bundle.signature`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10560)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10561)| `Bundle.signature`| _Equivalent_<br/>(22252/22253)| **`Bundle.signature`**| _Equivalent_<br/>(37287/37288)| `Bundle.signature`
| *45 of 45 elements used* | | *47 of 47 elements used* | | *48 of 48 elements used* | | *48 of 48 elements used* | | *48 of 49 elements used* <br/>remaining elements:<br/>`Bundle.issues`

