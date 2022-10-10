# Open Digital Twins Ontology for ISA-95 Standard

This project is a sample implementation of the [ISA-95](https://www.isa.org/standards-and-publications/isa-standards/isa-standards-committees/isa95) Standard as [DTDL](https://github.com/Azure/opendigitaltwins-dtdl/blob/master/DTDL/v2/dtdlv2.md) models to be used e.g. with [Azure Digital Twins](https://azure.microsoft.com/en-us/products/digital-twins/#overview).

Work in progress!!

## Supported models from ISA-95

* Common Object Models
* Logical equipment hierarchy
* Physical asset hierarchy

## Contributing to ontology

We are working on improving the main interfaces, adding more interfaces in areas that we don't yet support, as well as making better tools to integrate and use the models in smart manufacturing platforms and its applications.

We encourage you to contribute to continue improving the DTDL-based ISA-95 ontology. Please point out bugs or peculiarities, add or extend interfaces and vocabularies, and suggest improvements to evolve this ontology.

* Comment or create a new issue for bug reporting
* For improvements, please fork this repository, make your changes and send a pull request

Pull requests will be evaluated based on the quality of the proposed interface models, adherence to the modeling conventions used in the repo (see below), and conceptual and roadmap compliance.

### Modeling conventions

* All entity naming (Interfaces, Properties, Relationships, Components, etc.) is done in English. 
* Interfaces are named as singular nouns using CamelCase with capital initial (aka. PascalCase).
* Properties are named as singular nouns using camelCase with lower-case initial, typically with two or three name components.
* Relationships are named as singular nouns using camelCase with lower-case initial, typically with two or three name components. Naming can represent either the relationship itself, in the case of generic relationships, or a target Interface.
* Please use language-tagged `displayName`and `description` fields, providing at minimum English-language versions of these (more languages are of course welcome!).
* The English-language value of `displayName` should mirror the DTMI local name written out in lowercase, i.e., `isPartOf` has the display name `is part of`.

## Alignment with standards

TBD

### Extensions

Certain extensions to the ISA-95 Standard are used with the DTDL models. This improves the usability of the models with DTDL and services like Azure Digital Twins.

## More about Azure Digital Twins

* [Azure Digital Twins product page](https://azure.microsoft.com/en-us/services/digital-twins/)
* [Azure Digital Twins: Powering the next generation of IoT connected solutions](https://channel9.msdn.com/Events/Build/2020/INT177)
* [Digital Twins Definition Language Repository](https://github.com/Azure/opendigitaltwins-dtdl)
* [Azure Digital Twins introduction video](https://azure.microsoft.com/en-us/resources/videos/azure-digital-twins-introduction-video/)
* [Azure Digital Twins IoT Show Public Preview](https://www.youtube.com/watch?v=D6kyhrRVdfc&feature=youtu.be)
* [Azure Digital Twins Tech Deep Dive](https://www.youtube.com/watch?v=5Ku55g1GQG8&feature=youtu.be)
* [ADT Explorer](https://github.com/Azure-Samples/digital-twins-explorer)


This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

### Contributors

<sub>Microsoft: Jürgen Mayrbäurl</sub>