Comparison of 
Generated at Friday, April 4, 2025 2:58:43 PM

### SNOMEDCTSupplyItem

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | SNOMEDCTSupplyItem |
| Canonical URL | `http://hl7.org/fhir/ValueSet/supply-item` |
| Version | 4.0.1 |
| Description | This value set includes [SNOMED CT](http://snomed.info/sct) where concept is-a 105590001 (Substance (substance)) or  concept is-a 260787004 (Physical object)  and provided as an example value set. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `2787` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SupplyDelivery` | `SupplyDelivery.suppliedItem.item[x]` | `http://hl7.org/fhir/ValueSet/supply-item` | `Example` | Medication, Substance, or Device supplied |
| `http://hl7.org/fhir/StructureDefinition/SupplyRequest` | `SupplyRequest.item[x]` | `http://hl7.org/fhir/ValueSet/supply-item` | `Example` | Medication, Substance, or Device requested to be supplied |

### Expansion Failure

Failed to expand this value set: Expansion is limited
