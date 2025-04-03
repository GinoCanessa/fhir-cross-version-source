Comparison of 
Generated at Thursday, April 3, 2025 8:18:23 AM

### SNOMEDCTSupplyItem

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | SNOMEDCTSupplyItem |
| Canonical URL | `http://hl7.org/fhir/ValueSet/supply-item` |
| Version | 4.3.0 |
| Description | This value set includes [SNOMED CT](http://snomed.info/sct) where concept is-a 105590001 (Substance (substance)) or  concept is-a 260787004 (Physical object)  and provided as an example value set. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4147` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SupplyDelivery` | `SupplyDelivery.suppliedItem.item[x]` | `http://hl7.org/fhir/ValueSet/supply-item` | `Example` | Medication, Substance, or Device supplied |
| `http://hl7.org/fhir/StructureDefinition/SupplyRequest` | `SupplyRequest.item[x]` | `http://hl7.org/fhir/ValueSet/supply-item` | `Example` | Medication, Substance, or Device requested to be supplied |

### Expansion Failure

Failed to expand this value set: Expansion is limited
