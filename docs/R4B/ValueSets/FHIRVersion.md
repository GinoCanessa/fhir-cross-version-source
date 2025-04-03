Comparison of 
Generated at Thursday, April 3, 2025 8:18:23 AM

### FHIRVersion

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | FHIRVersion |
| Canonical URL | `http://hl7.org/fhir/ValueSet/FHIR-version` |
| Version | 4.3.0 |
| Description | All published FHIR Versions. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `3778` |
| Database Concept Count | `27` |
| Database Active Concept Count | `27` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CapabilityStatement` | `CapabilityStatement.fhirVersion` | `http://hl7.org/fhir/ValueSet/FHIR-version\|4.3.0` | `Required` | FHIR Version the system supports |
| `http://hl7.org/fhir/StructureDefinition/ImplementationGuide` | `ImplementationGuide.fhirVersion` | `http://hl7.org/fhir/ValueSet/FHIR-version\|4.3.0` | `Required` | FHIR Version(s) this Implementation Guide targets |
| `http://hl7.org/fhir/StructureDefinition/ImplementationGuide` | `ImplementationGuide.definition.resource.fhirVersion` | `http://hl7.org/fhir/ValueSet/FHIR-version\|4.3.0` | `Required` | Versions this applies to (if different to IG) |
| `http://hl7.org/fhir/StructureDefinition/StructureDefinition` | `StructureDefinition.fhirVersion` | `http://hl7.org/fhir/ValueSet/FHIR-version\|4.3.0` | `Required` | FHIR Version this StructureDefinition targets |
| `http://hl7.org/fhir/StructureDefinition/structuredefinition-applicable-version` | `Extension.value[x]` | `http://hl7.org/fhir/ValueSet/FHIR-version` | `Required` | Value of extension |
| `http://hl7.org/fhir/StructureDefinition/structuredefinition-normative-version` | `Extension.value[x]` | `http://hl7.org/fhir/ValueSet/FHIR-version` | `Required` | Value of extension |

### Referenced Systems

* `http://hl7.org/fhir/FHIR-version`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [FHIRVersion](/docs/R4/ValueSets/FHIRVersion.md)<br/> `http://hl7.org/fhir/ValueSet/FHIR-version\|4.0.1` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1509`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1510`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [FHIRVersion](/docs/R4B/ValueSets/FHIRVersion.md)<br/> `http://hl7.org/fhir/ValueSet/FHIR-version\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `808`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1069`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [FHIRVersion](/docs/R5/ValueSets/FHIRVersion.md)<br/> `http://hl7.org/fhir/ValueSet/FHIR-version\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set FHIRVersion from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | [R4 FHIRVersion](/docs/R4/ValueSets/FHIRVersion.md)| Relationship | R4B FHIRVersion| Relationship | [R5 FHIRVersion](/docs/R5/ValueSets/FHIRVersion.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/FHIR-version`
| | | | | `0.01`| _Equivalent_ <br/>(15986/15987)| **`0.01`**| _Equivalent_ <br/>(7634/9893)| `0.01`
| | | | | `0.05`| _Equivalent_ <br/>(15988/15989)| **`0.05`**| _Equivalent_ <br/>(7629/9894)| `0.05`
| | | | | `0.06`| _Equivalent_ <br/>(15990/15991)| **`0.06`**| _Equivalent_ <br/>(7627/9895)| `0.06`
| | | | | `0.11`| _Equivalent_ <br/>(15992/15993)| **`0.11`**| _Equivalent_ <br/>(7622/9896)| `0.11`
| | | | | `0.0.80`| _Equivalent_ <br/>(15994/15995)| **`0.0.80`**| _Equivalent_ <br/>(7639/9890)| `0.0.80`
| | | | | `0.0.81`| _Equivalent_ <br/>(15996/15997)| **`0.0.81`**| _Equivalent_ <br/>(7638/9891)| `0.0.81`
| | | | | `0.0.82`| _Equivalent_ <br/>(15998/15999)| **`0.0.82`**| _Equivalent_ <br/>(7636/9892)| `0.0.82`
| | | | | `0.4.0`| _Equivalent_ <br/>(16000/16001)| **`0.4.0`**| _Equivalent_ <br/>(7619/9898)| `0.4.0`
| | | | | `0.5.0`| _Equivalent_ <br/>(16002/16003)| **`0.5.0`**| _Equivalent_ <br/>(7620/9900)| `0.5.0`
| | | | | `1.0.0`| _Equivalent_ <br/>(16004/16005)| **`1.0.0`**| _Equivalent_ <br/>(7642/9902)| `1.0.0`
| | | | | `1.0.1`| _Equivalent_ <br/>(16006/16007)| **`1.0.1`**| _Equivalent_ <br/>(7643/9903)| `1.0.1`
| | | | | `1.0.2`| _Equivalent_ <br/>(16008/16009)| **`1.0.2`**| _Equivalent_ <br/>(7645/9904)| `1.0.2`
| | | | | `1.1.0`| _Equivalent_ <br/>(16010/16011)| **`1.1.0`**| _Equivalent_ <br/>(7644/9906)| `1.1.0`
| | | | | `1.4.0`| _Equivalent_ <br/>(16012/16013)| **`1.4.0`**| _Equivalent_ <br/>(7637/9908)| `1.4.0`
| | | | | `1.6.0`| _Equivalent_ <br/>(16014/16015)| **`1.6.0`**| _Equivalent_ <br/>(7640/9910)| `1.6.0`
| | | | | `1.8.0`| _Equivalent_ <br/>(16016/16017)| **`1.8.0`**| _Equivalent_ <br/>(7641/9912)| `1.8.0`
| | | | | `3.0.0`| _Equivalent_ <br/>(16018/16019)| **`3.0.0`**| _Equivalent_ <br/>(7628/9914)| `3.0.0`
| | | | | `3.0.1`| _Equivalent_ <br/>(16020/16021)| **`3.0.1`**| _Equivalent_ <br/>(7631/9915)| `3.0.1`
| | | | | | | **`3.0.2`**| _Equivalent_ <br/>(7632/9916)| `3.0.2`
| | | | | `3.3.0`| _Equivalent_ <br/>(16022/16023)| **`3.3.0`**| _Equivalent_ <br/>(7633/9918)| `3.3.0`
| | | | | `3.5.0`| _Equivalent_ <br/>(16024/16025)| **`3.5.0`**| _Equivalent_ <br/>(7630/9920)| `3.5.0`
| | | | | `4.0.0`| _Equivalent_ <br/>(16026/16027)| **`4.0.0`**| _Equivalent_ <br/>(7624/9922)| `4.0.0`
| | | | | `4.0.1`| _Equivalent_ <br/>(16028/16029)| **`4.0.1`**| _Equivalent_ <br/>(7625/9923)| `4.0.1`
| | | | | | | **`4.1.0`**| _Equivalent_ <br/>(7626/9925)| `4.1.0`
| | | | | | | **`4.3.0-cibuild`**| _Equivalent_ <br/>(7635/9930)| `4.3.0-cibuild`
| | | | | | | **`4.3.0-snapshot1`**| _Equivalent_ <br/>(7621/9931)| `4.3.0-snapshot1`
| | | | | | | **`4.3.0`**| _Equivalent_ <br/>(7623/9929)| `4.3.0`
| | | | | *22 of 22 codes used* | | *27 of 27 codes used* | | *27 of 57 codes used* <br/>remaining codes:<br/>`0.0`, `0.4`, `0.5`, `1.0`, `1.1`, `1.4`, `1.6`, `1.8`, `3.0`, `3.3`, `3.5`, `4.0`, `4.1`, `4.2`, `4.2.0`, `4.3`, `4.4`, `4.4.0`, `4.5`, `4.5.0`, `4.6`, `4.6.0`, `5.0`, `5.0.0`, `5.0.0-ballot`, `5.0.0-cibuild`, `5.0.0-draft-final`, `5.0.0-snapshot1`, `5.0.0-snapshot2`, `5.0.0-snapshot3`

