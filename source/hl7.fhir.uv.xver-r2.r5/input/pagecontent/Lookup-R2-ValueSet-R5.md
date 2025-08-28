### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [ValueSet](https://hl7.org/fhir/DSTU2/ValueSet.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [ValueSet.meta](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.meta](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.meta](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.implicitRules](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.implicitRules](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.implicitRules](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.language](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.language](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.language](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.text](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.text](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.text](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.contained](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.contained](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.contained](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.url](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.url](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.url](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.identifier](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.identifier](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.identifier](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.version](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.version](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.version](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.name](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.name](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.name](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.status](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.status](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.status](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.experimental](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.experimental](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.experimental](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.publisher](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.publisher](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.publisher](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.contact](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ValueSet.contact](StructureDefinition-ext-R2-ValueSet.contact.html) |
| [ValueSet.contact.id](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.contact.name](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.contact.telecom](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.date](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.date](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.date](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.lockedDate](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementRenamed` | [ValueSet.compose.lockedDate](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.description](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.description](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.description](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.useContext](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.useContext](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.useContext](https://hl7.org/fhir/R5/ValueSet.html#resource)<br />[ValueSet.jurisdiction](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.immutable](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.immutable](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.requirements](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementRenamed` | [ValueSet.purpose](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.copyright](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseOneOf` | [CodeSystem.copyright](https://hl7.org/fhir/R5/CodeSystem.html#resource)<br />[ValueSet.copyright](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.extensible](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ValueSet.extensible](StructureDefinition-ext-R2-ValueSet.extensible.html) |
| [ValueSet.codeSystem](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ValueSet.codeSystem](StructureDefinition-ext-R2-ValueSet.codeSystem.html) |
| [ValueSet.codeSystem.id](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.codeSystem.system](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.codeSystem.version](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.codeSystem.caseSensitive](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.codeSystem.concept](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.codeSystem.concept.id](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.codeSystem.concept.code](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.codeSystem.concept.abstract](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.codeSystem.concept.display](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.codeSystem.concept.definition](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.codeSystem.concept.designation](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.codeSystem.concept.designation.id](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.codeSystem.concept.designation.language](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.codeSystem.concept.designation.use](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.codeSystem.concept.designation.value](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.codeSystem.concept.concept](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtensionFromAncestor` | - |
| [ValueSet.compose](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.compose.id](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose.id](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.compose.import](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ValueSet.compose.import](StructureDefinition-ext-R2-ValueSet.co.import.html) |
| [ValueSet.compose.include](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose.include](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.compose.include.id](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose.include.id](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.compose.include.system](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose.include.system](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.compose.include.version](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose.include.version](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.compose.include.concept](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose.include.concept](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.compose.include.concept.id](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose.include.concept.id](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.compose.include.concept.code](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose.include.concept.code](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.compose.include.concept.display](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose.include.concept.display](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.compose.include.concept.designation](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ValueSet.compose.include.concept.designation](StructureDefinition-ext-R2-ValueSet.co.in.co.designation.html) |
| [ValueSet.compose.include.filter](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose.include.filter](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.compose.include.filter.id](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose.include.filter.id](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.compose.include.filter.property](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose.include.filter.property](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.compose.include.filter.op](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose.include.filter.op](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.compose.include.filter.value](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose.include.filter.value](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.compose.exclude](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.compose.exclude](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.id](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.id](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.identifier](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.identifier](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.timestamp](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.timestamp](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.total](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.total](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.offset](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.offset](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.parameter](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.parameter](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.parameter.id](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.parameter.id](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.parameter.name](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.parameter.name](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.parameter.value[x]](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.parameter.value[x]](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.contains](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.contains](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.contains.id](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.contains.id](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.contains.system](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.contains.system](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.contains.abstract](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.contains.abstract](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.contains.version](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.contains.version](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.contains.code](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.contains.code](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.contains.display](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.contains.display](https://hl7.org/fhir/R5/ValueSet.html#resource) |
| [ValueSet.expansion.contains.contains](https://hl7.org/fhir/DSTU2/ValueSet.html#resource) | `UseElementSameName` | [ValueSet.expansion.contains.contains](https://hl7.org/fhir/R5/ValueSet.html#resource) |
