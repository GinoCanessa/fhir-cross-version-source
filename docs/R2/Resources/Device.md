Comparison of 
Generated at Thursday, April 3, 2025 8:18:08 AM

### Device

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Device |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Device` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Device Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `64` |
| Database Snapshot Count | `25` |
| Database Differential Count | `17` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Device` | `Device` | `Device` | Device | An instance of a manufactured te that is used in the provision of healthcare | 0..* | Device |  |  |
| `Device.contact` | `Device.contact` | `contact` |  | Details for human/organization for support | 0..* | ContactPoint |  |  |
| `Device.contained` | `Device.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Device.expiry` | `Device.expiry` | `expiry` |  | Date and time of expiry of this device (if applicable) | 0..1 | dateTime |  |  |
| `Device.extension` | `Device.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Device.id` | `Device.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Device.identifier` | `Device.identifier` | `identifier` |  | Instance id from manufacturer, owner, and others | 0..* | Identifier |  |  |
| `Device.implicitRules` | `Device.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Device.language` | `Device.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Device.location` | `Device.location` | `location` |  | Where the resource is found | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `Device.lotNumber` | `Device.lotNumber` | `lotNumber` |  | Lot number of manufacture | 0..1 | string |  |  |
| `Device.manufactureDate` | `Device.manufactureDate` | `manufactureDate` |  | Manufacture date | 0..1 | dateTime |  |  |
| `Device.manufacturer` | `Device.manufacturer` | `manufacturer` |  | Name of device manufacturer | 0..1 | string |  |  |
| `Device.meta` | `Device.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Device.model` | `Device.model` | `model` |  | Model id assigned by the manufacturer | 0..1 | string |  |  |
| `Device.modifierExtension` | `Device.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Device.note` | `Device.note` | `note` |  | Device notes and comments | 0..* | Annotation |  |  |
| `Device.owner` | `Device.owner` | `owner` |  | Organization responsible for device | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Device.patient` | `Device.patient` | `patient` |  | If the resource is affixed to a person | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `Device.status` | `Device.status` | `status` |  | available \| not-available \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/devicestatus` |
| `Device.text` | `Device.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Device.type` | `Device.type` | `type` |  | What kind of device this is | 1..1 | CodeableConcept | `Preferred` | `https://www.gmdnagency.org/Info.aspx?pageid=1091` |
| `Device.udi` | `Device.udi` | `udi` |  | FDA mandated Unique Device Identifier | 0..1 | string |  |  |
| `Device.url` | `Device.url` | `url` |  | Network address to contact device | 0..1 | uri |  |  |
| `Device.version` | `Device.version` | `version` |  | Version number (i.e. software) | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Device](/docs/R2/Resources/Device.md)<br/> `http://hl7.org/fhir/StructureDefinition/Device\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `97`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `264`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Device](/docs/R3/Resources/Device.md)<br/> `http://hl7.org/fhir/StructureDefinition/Device\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `447`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `642`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Device](/docs/R4/Resources/Device.md)<br/> `http://hl7.org/fhir/StructureDefinition/Device\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1455`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1456`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Device](/docs/R4B/Resources/Device.md)<br/> `http://hl7.org/fhir/StructureDefinition/Device\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `962`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1191`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Device](/docs/R5/Resources/Device.md)<br/> `http://hl7.org/fhir/StructureDefinition/Device\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Device from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Device| Relationship | [R3 Device](/docs/R3/Resources/Device.md)| Relationship | [R4 Device](/docs/R4/Resources/Device.md)| Relationship | [R4B Device](/docs/R4B/Resources/Device.md)| Relationship | [R5 Device](/docs/R5/Resources/Device.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Device`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4490)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4491)| `Device`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12878)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12879)| `Device`| _Equivalent_<br/>(25476/25477)| `Device`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40426)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40427)| `Device`
| **`Device.id`**| _Equivalent_<br/>(4492/4493)| `Device.id`| _Equivalent_<br/>(12880/12881)| `Device.id`| _Equivalent_<br/>(25478/25479)| `Device.id`| _Equivalent_<br/>(40428/40429)| `Device.id`
| **`Device.meta`**| _Equivalent_<br/>(4494/4495)| `Device.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12882)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12883)| `Device.meta`| _Equivalent_<br/>(25480/25481)| `Device.meta`| _Equivalent_<br/>(40430/40431)| `Device.meta`
| **`Device.implicitRules`**| _Equivalent_<br/>(4496/4497)| `Device.implicitRules`| _Equivalent_<br/>(12884/12885)| `Device.implicitRules`| _Equivalent_<br/>(25482/25483)| `Device.implicitRules`| _Equivalent_<br/>(40432/40433)| `Device.implicitRules`
| **`Device.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4498)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4499)| `Device.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12886)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12887)| `Device.language`| _Equivalent_<br/>(25484/25485)| `Device.language`| _Equivalent_<br/>(40434/40435)| `Device.language`
| **`Device.text`**| _Equivalent_<br/>(4500/4501)| `Device.text`| _Equivalent_<br/>(12888/12889)| `Device.text`| _Equivalent_<br/>(25486/25487)| `Device.text`| _Equivalent_<br/>(40436/40437)| `Device.text`
| **`Device.contained`**| _Equivalent_<br/>(4502/4503)| `Device.contained`| _Equivalent_<br/>(12890/12891)| `Device.contained`| _Equivalent_<br/>(25488/25489)| `Device.contained`| _Equivalent_<br/>(40438/40439)| `Device.contained`
| **`Device.extension`**| _Equivalent_<br/>(4504/4505)| `Device.extension`| _Equivalent_<br/>(12892/12893)| `Device.extension`| _Equivalent_<br/>(25490/25491)| `Device.extension`| _Equivalent_<br/>(40440/40441)| `Device.extension`
| **`Device.modifierExtension`**| _Equivalent_<br/>(4506/4507)| `Device.modifierExtension`| _Equivalent_<br/>(12894/12895)| `Device.modifierExtension`| _Equivalent_<br/>(25492/25493)| `Device.modifierExtension`| _Equivalent_<br/>(40442/40443)| `Device.modifierExtension`
| **`Device.identifier`**| _Equivalent_<br/>(4508/4509)| `Device.identifier`| _Equivalent_<br/>(12896/12897)| `Device.identifier`| _Equivalent_<br/>(25494/25495)| `Device.identifier`| _Equivalent_<br/>(40444/40445)| `Device.identifier`
| **`Device.type`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4510)<hr/>←←←← _RelatedTo_ ←←←← <br/>(4511)| `Device.type`| _Equivalent_<br/>(12903/12904)| `Device.type`| _Equivalent_<br/>(25550/25551)| `Device.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40489)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40490)| `Device.type`
| **`Device.note`**| _Equivalent_<br/>(4512/4513)| `Device.note`| _Equivalent_<br/>(12925/12926)| `Device.note`| _Equivalent_<br/>(25602/25603)| `Device.note`| _Equivalent_<br/>(40529/40530)| `Device.note`
| **`Device.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4514)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4515)| `Device.status`| _Equivalent_<br/>(12901/12902)| `Device.status`| _Equivalent_<br/>(25518/25519)| `Device.status`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40468)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(40469)| `Device.status`
| **`Device.manufacturer`**| _Equivalent_<br/>(4516/4517)| `Device.manufacturer`| _Equivalent_<br/>(12907/12908)| `Device.manufacturer`| _Equivalent_<br/>(25524/25525)| `Device.manufacturer`| _Equivalent_<br/>(40472/40473)| `Device.manufacturer`
| **`Device.model`**| _Equivalent_<br/>(4518/4519)| `Device.model`| _Equivalent_<br/>(986/1474)| `Device.modelNumber`| _Equivalent_<br/>(25546/25547)| `Device.modelNumber`| _Equivalent_<br/>(40485/40486)| `Device.modelNumber`
| **`Device.version`**| _Equivalent_<br/>(4520/4521)| `Device.version`| →→→→ _RelatedTo_ →→→→ <br/>(12913)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12914)| `Device.version`| _Equivalent_<br/>(25564/25565)| `Device.version`| _Equivalent_<br/>(40496/40497)| `Device.version`
| **`Device.manufactureDate`**| _Equivalent_<br/>(4522/4523)| `Device.manufactureDate`| _Equivalent_<br/>(12909/12910)| `Device.manufactureDate`| _Equivalent_<br/>(25526/25527)| `Device.manufactureDate`| _Equivalent_<br/>(40474/40475)| `Device.manufactureDate`
| **`Device.expiry`**| _Equivalent_<br/>(179/593)| `Device.expirationDate`| _Equivalent_<br/>(12911/12912)| `Device.expirationDate`| _Equivalent_<br/>(25528/25529)| `Device.expirationDate`| _Equivalent_<br/>(40476/40477)| `Device.expirationDate`
| **`Device.udi`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4524)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4525)| `Device.udi`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(987)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1475)| `Device.udiCarrier`| _Equivalent_<br/>(25498/25499)| `Device.udiCarrier`| _Equivalent_<br/>(40448/40449)| `Device.udiCarrier`
| **`Device.lotNumber`**| _Equivalent_<br/>(4526/4527)| `Device.lotNumber`| _Equivalent_<br/>(12905/12906)| `Device.lotNumber`| _Equivalent_<br/>(25530/25531)| `Device.lotNumber`| _Equivalent_<br/>(40478/40479)| `Device.lotNumber`
| **`Device.owner`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4528)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4529)| `Device.owner`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12917)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12918)| `Device.owner`| _Equivalent_<br/>(25594/25595)| `Device.owner`| _Equivalent_<br/>(40521/40522)| `Device.owner`
| **`Device.location`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4530)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4531)| `Device.location`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12921)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12922)| `Device.location`| _Equivalent_<br/>(25598/25599)| `Device.location`| _Equivalent_<br/>(40525/40526)| `Device.location`
| **`Device.patient`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4532)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4533)| `Device.patient`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12915)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12916)| `Device.patient`| _Equivalent_<br/>(25592/25593)| `Device.patient`| | | 
| **`Device.contact`**| _Equivalent_<br/>(4534/4535)| `Device.contact`| _Equivalent_<br/>(12919/12920)| `Device.contact`| _Equivalent_<br/>(25596/25597)| `Device.contact`| _Equivalent_<br/>(40523/40524)| `Device.contact`
| **`Device.url`**| _Equivalent_<br/>(4536/4537)| `Device.url`| _Equivalent_<br/>(12923/12924)| `Device.url`| _Equivalent_<br/>(25600/25601)| `Device.url`| _Equivalent_<br/>(40527/40528)| `Device.url`
| *25 of 25 elements used* | | *25 of 36 elements used* <br/>remaining elements:<br/>`Device.safety`, `Device.udi.carrierAIDC`, `Device.udi.carrierHRF`, `Device.udi.deviceIdentifier`, `Device.udi.entryType`, `Device.udi.extension`, `Device.udi.id`, `Device.udi.issuer`, `Device.udi.jurisdiction`, `Device.udi.modifierExtension`, `Device.udi.name`| | *25 of 66 elements used* <br/>remaining elements:<br/>`Device.definition`, `Device.deviceName`, `Device.deviceName.extension`, `Device.deviceName.id`, `Device.deviceName.modifierExtension`, `Device.deviceName.name`, `Device.deviceName.type`, `Device.distinctIdentifier`, `Device.parent`, `Device.partNumber`, `Device.property`, `Device.property.extension`, `Device.property.id`, `Device.property.modifierExtension`, `Device.property.type`, `Device.property.valueCode`, `Device.property.valueQuantity`, `Device.safety`, `Device.serialNumber`, `Device.specialization`, `Device.specialization.extension`, `Device.specialization.id`, `Device.specialization.modifierExtension`, `Device.specialization.systemType`, `Device.specialization.version`, `Device.statusReason`, `Device.udiCarrier.carrierAIDC`, `Device.udiCarrier.carrierHRF`, `Device.udiCarrier.deviceIdentifier`, `Device.udiCarrier.entryType`, `Device.udiCarrier.extension`, `Device.udiCarrier.id`, `Device.udiCarrier.issuer`, `Device.udiCarrier.jurisdiction`, `Device.udiCarrier.modifierExtension`, `Device.version.component`, `Device.version.extension`, `Device.version.id`, `Device.version.modifierExtension`, `Device.version.type`, `Device.version.value`| | *25 of 66 elements used* <br/>remaining elements:<br/>`Device.definition`, `Device.deviceName`, `Device.deviceName.extension`, `Device.deviceName.id`, `Device.deviceName.modifierExtension`, `Device.deviceName.name`, `Device.deviceName.type`, `Device.distinctIdentifier`, `Device.parent`, `Device.partNumber`, `Device.property`, `Device.property.extension`, `Device.property.id`, `Device.property.modifierExtension`, `Device.property.type`, `Device.property.valueCode`, `Device.property.valueQuantity`, `Device.safety`, `Device.serialNumber`, `Device.specialization`, `Device.specialization.extension`, `Device.specialization.id`, `Device.specialization.modifierExtension`, `Device.specialization.systemType`, `Device.specialization.version`, `Device.statusReason`, `Device.udiCarrier.carrierAIDC`, `Device.udiCarrier.carrierHRF`, `Device.udiCarrier.deviceIdentifier`, `Device.udiCarrier.entryType`, `Device.udiCarrier.extension`, `Device.udiCarrier.id`, `Device.udiCarrier.issuer`, `Device.udiCarrier.jurisdiction`, `Device.udiCarrier.modifierExtension`, `Device.version.component`, `Device.version.extension`, `Device.version.id`, `Device.version.modifierExtension`, `Device.version.type`, `Device.version.value`| | *24 of 74 elements used* <br/>remaining elements:<br/>`Device.availabilityStatus`, `Device.biologicalSourceEvent`, `Device.category`, `Device.conformsTo`, `Device.conformsTo.category`, `Device.conformsTo.extension`, `Device.conformsTo.id`, `Device.conformsTo.modifierExtension`, `Device.conformsTo.specification`, `Device.conformsTo.version`, `Device.cycle`, `Device.definition`, `Device.displayName`, `Device.duration`, `Device.endpoint`, `Device.gateway`, `Device.mode`, `Device.name`, `Device.name.display`, `Device.name.extension`, `Device.name.id`, `Device.name.modifierExtension`, `Device.name.type`, `Device.name.value`, `Device.parent`, `Device.partNumber`, `Device.property`, `Device.property.extension`, `Device.property.id`, `Device.property.modifierExtension`, `Device.property.type`, `Device.property.value[x]`, `Device.safety`, `Device.serialNumber`, `Device.udiCarrier.carrierAIDC`, `Device.udiCarrier.carrierHRF`, `Device.udiCarrier.deviceIdentifier`, `Device.udiCarrier.entryType`, `Device.udiCarrier.extension`, `Device.udiCarrier.id`, `Device.udiCarrier.issuer`, `Device.udiCarrier.jurisdiction`, `Device.udiCarrier.modifierExtension`, `Device.version.component`, `Device.version.extension`, `Device.version.id`, `Device.version.installDate`, `Device.version.modifierExtension`, `Device.version.type`, `Device.version.value`

