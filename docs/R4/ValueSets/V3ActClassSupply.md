Comparison of 
Generated at Monday, April 14, 2025 6:17:27 PM

### v3.ActClassSupply

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | v3.ActClassSupply |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-ActClassSupply` |
| Version | 2014-03-26 |
| Description | Supply orders and deliveries are simple Acts that focus on the delivered product. The product is associated with the Supply Act via Participation.typeCode="product". With general Supply Acts, the precise identification of the Material (manufacturer, serial numbers, etc.) is important.  Most of the detailed information about the Supply should be represented using the Material class.  If delivery needs to be scheduled, tracked, and billed separately, one can associate a Transportation Act with the Supply Act.  Pharmacy dispense services are represented as Supply Acts, associated with a SubstanceAdministration  Act. The SubstanceAdministration class represents the administration of medication, while dispensing is supply. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `3283` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActClass`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `DIET` | diet |
| `http://terminology.hl7.org/CodeSystem/v3-ActClass` | `SPLY` | supply |
