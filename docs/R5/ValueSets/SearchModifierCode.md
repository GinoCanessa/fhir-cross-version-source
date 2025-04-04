Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### SearchModifierCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SearchModifierCode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/search-modifier-code` |
| Version | 5.0.0 |
| Description | A supported modifier for a search parameter. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4883` |
| Database Concept Count | `15` |
| Database Active Concept Count | `15` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SearchParameter` | `SearchParameter.modifier` | `http://hl7.org/fhir/ValueSet/search-modifier-code\|5.0.0` | `Required` | missing \| exact \| contains \| not \| text \| in \| not-in \| below \| above \| type \| identifier \| of-type \| code-text \| text-advanced \| iterate |
| `http://hl7.org/fhir/StructureDefinition/Subscription` | `Subscription.filterBy.modifier` | `http://hl7.org/fhir/ValueSet/search-modifier-code\|5.0.0` | `Required` | missing \| exact \| contains \| not \| text \| in \| not-in \| below \| above \| type \| identifier \| of-type \| code-text \| text-advanced \| iterate |
| `http://hl7.org/fhir/StructureDefinition/SubscriptionTopic` | `SubscriptionTopic.canFilterBy.modifier` | `http://hl7.org/fhir/ValueSet/search-modifier-code\|5.0.0` | `Required` | missing \| exact \| contains \| not \| text \| in \| not-in \| below \| above \| type \| identifier \| of-type \| code-text \| text-advanced \| iterate |

### Referenced Systems

* `http://hl7.org/fhir/search-modifier-code`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [SearchModifierCode](/docs/R2/ValueSets/SearchModifierCode.md)<br/> `http://hl7.org/fhir/ValueSet/search-modifier-code\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1307`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1308`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SearchModifierCode](/docs/R3/ValueSets/SearchModifierCode.md)<br/> `http://hl7.org/fhir/ValueSet/search-modifier-code\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `514`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `735`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SearchModifierCode](/docs/R4/ValueSets/SearchModifierCode.md)<br/> `http://hl7.org/fhir/ValueSet/search-modifier-code\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1725`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1726`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SearchModifierCode](/docs/R4B/ValueSets/SearchModifierCode.md)<br/> `http://hl7.org/fhir/ValueSet/search-modifier-code\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `992`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [SearchModifierCode](/docs/R5/ValueSets/SearchModifierCode.md)<br/> `http://hl7.org/fhir/ValueSet/search-modifier-code\|5.0.0` 
| | | | | | | [SubscriptionSearchModifier](/docs/R4B/ValueSets/SubscriptionSearchModifier.md)<br/> `http://hl7.org/fhir/ValueSet/subscription-search-modifier\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `976`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [SearchModifierCode](/docs/R5/ValueSets/SearchModifierCode.md)<br/> `http://hl7.org/fhir/ValueSet/search-modifier-code\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set SearchModifierCode from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 SearchModifierCode](/docs/R2/ValueSets/SearchModifierCode.md)| Relationship | [R3 SearchModifierCode](/docs/R3/ValueSets/SearchModifierCode.md)| Relationship | [R4 SearchModifierCode](/docs/R4/ValueSets/SearchModifierCode.md)| Relationship | [R4B SearchModifierCode](/docs/R4B/ValueSets/SearchModifierCode.md)| Relationship | R5 SearchModifierCode
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/search-modifier-code`
| `missing`| _Equivalent_ <br/>(12749/12750)| `missing`| _Equivalent_ <br/>(4832/7155)| `missing`| _Equivalent_ <br/>(17442/17443)| `missing`| _Equivalent_ <br/>(9405/11745)| **`missing`**
| `exact`| _Equivalent_ <br/>(12751/12752)| `exact`| _Equivalent_ <br/>(4833/7152)| `exact`| _Equivalent_ <br/>(17444/17445)| `exact`| _Equivalent_ <br/>(9406/11741)| **`exact`**
| `contains`| _Equivalent_ <br/>(12753/12754)| `contains`| _Equivalent_ <br/>(4828/7151)| `contains`| _Equivalent_ <br/>(17446/17447)| `contains`| _Equivalent_ <br/>(9401/11740)| **`contains`**
| `not`| _Equivalent_ <br/>(12755/12756)| `not`| _Equivalent_ <br/>(4829/7156)| `not`| _Equivalent_ <br/>(17448/17449)| `not`| _Equivalent_ <br/>(9402/11746)| **`not`**
| `text`| _Equivalent_ <br/>(12757/12758)| `text`| _Equivalent_ <br/>(4836/7159)| `text`| _Equivalent_ <br/>(17450/17451)| `text`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9409)<hr/>←←←← _Equivalent_ ←←←← <br/>(11749) | **`text`**
| `in`| _Equivalent_ <br/>(12759/12760)| `in`| _Equivalent_ <br/>(4830/7154)| `in`| _Equivalent_ <br/>(17452/17453)| `in`| _Equivalent_ <br/>(9403/11743)| **`in`**
| `not-in`| _Equivalent_ <br/>(12761/12762)| `not-in`| _Equivalent_ <br/>(4835/7157)| `not-in`| _Equivalent_ <br/>(17454/17455)| `not-in`| _Equivalent_ <br/>(9408/11747)| **`not-in`**
| `below`| _Equivalent_ <br/>(12763/12764)| `below`| _Equivalent_ <br/>(4831/7150)| `below`| _Equivalent_ <br/>(17456/17457)| `below`| _Equivalent_ <br/>(9404/11738)| **`below`**
| `above`| _Equivalent_ <br/>(12765/12766)| `above`| _Equivalent_ <br/>(4834/7149)| `above`| _Equivalent_ <br/>(17458/17459)| `above`| _Equivalent_ <br/>(9407/11737)| **`above`**
| `type`| _Equivalent_ <br/>(12767/12768)| `type`| _Equivalent_ <br/>(4837/7160)| `type`| _Equivalent_ <br/>(17460/17461)| `type`| _Equivalent_ <br/>(9412/11751)| **`type`**
| | | | | `identifier`| _Equivalent_ <br/>(17462/17463)| `identifier`| _Equivalent_ <br/>(9400/11742)| **`identifier`**
| | | | | `ofType`| _Equivalent_ <br/>(17464/17465)| `ofType`| _Equivalent_ <br/>(9413/11748)| **`of-type`**
| `text`| _Equivalent_ <br/>(12757/12758)| `text`| _Equivalent_ <br/>(4836/7159)| `text`| _Equivalent_ <br/>(17450/17451)| `text`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9410)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11739) | **`code-text`**
| `text`| _Equivalent_ <br/>(12757/12758)| `text`| _Equivalent_ <br/>(4836/7159)| `text`| _Equivalent_ <br/>(17450/17451)| `text`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9411)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11750) | **`text-advanced`**
| | | | | | | | | **`iterate`**
| *10 of 10 codes used* | | *10 of 10 codes used* | | *12 of 12 codes used* | | *12 of 12 codes used* | | *15 of 15 codes used* 


#### Map Group 1

This group is centered on the Value Set SearchModifierCode from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B SubscriptionSearchModifier](/docs/R4B/ValueSets/SubscriptionSearchModifier.md)| Relationship | R5 SearchModifierCode
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/search-modifier-code`
| | | | | | | | | **`missing`**
| | | | | | | | | **`exact`**
| | | | | | | | | **`contains`**
| | | | | | | | | **`not`**
| | | | | | | | | **`text`**
| | | | | | | `in`| _Equivalent_ <br/>(9313/11651)| **`in`**
| | | | | | | `not-in`| _Equivalent_ <br/>(9322/11659)| **`not-in`**
| | | | | | | `below`| _Equivalent_ <br/>(9312/11652)| **`below`**
| | | | | | | `above`| _Equivalent_ <br/>(9320/11658)| **`above`**
| | | | | | | | | **`type`**
| | | | | | | | | **`identifier`**
| | | | | | | `of-type`| _Equivalent_ <br/>(9311/11650)| **`of-type`**
| | | | | | | | | **`code-text`**
| | | | | | | | | **`text-advanced`**
| | | | | | | | | **`iterate`**
| | | | | | | *5 of 15 codes used* <br/>remaining codes:<br/>`=`, `ap`, `eb`, `eq`, `ge`, `gt`, `le`, `lt`, `ne`, `sa`| | *15 of 15 codes used* 

