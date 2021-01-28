# IRI Registry Ontology
This ontology is a specialisation of the [Registry Ontology](http://purl.org/linked-data/registry) (REG) used to manage Internationalized Resource Identifiers (IRIs). "IRI" is a generalised and more modern name for URIs - Uniform Resource Identifiers.

The major specialisation in this ontology is the subclassing of reg:RegisterItem to `irireg:RegisteredIRI` which just mandates the use of a few extra properties for IRI management.

Another difference between this ontology and REG is not IRI-specific but a general development: here we define the statuses of `reg:RegisterItem` instances to be held within temporal objects, `irireg:StatusPeriod` instances, sub classes of OWL TIME's `time:ProperInterval` allowing us to stack up multiple, time-bounded, statuses per `irireg:RegisteredIRI`.


## Ontology file
The ontology is constituted as an OWL2 ontology and stored as an RDF (turtle) file [irg.ttl](irg.ttl). This ontology will shortly be documented diagramatically and in HTML, when intial development ceases.


## Examples
Examples of currently registered IRIs in the AGLDWG system are given in the [examples/](examples/) folder.


## License
As per most of the AGLDWG's outputs, this ontology is licensed for use according to Australian government recommendations and uses the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. See the [LICENSE](LICENSE) file in this repository for the full deed.


## Contact
This ontology is authored by the Australian Government Linked Data Working Group itself. See the AGLDWG's contact page to contact particular people:

* <https://www.linked.data.gov.au/contact>
