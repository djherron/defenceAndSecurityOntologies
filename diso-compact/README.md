# DISO-Compact

`diso-compact` is a compact (condensed) version of this **DISO** repository.

It contains the same DISO cluster structure, but each ontology is represented only by a single ontology file. 

Some ontologies in the DISO collection fit nicely in more than one DISO cluster. In the DISO GitHub repository, the OWL files for such an ontology are stored only once, in one cluster. The other clusters contain entries (folders) for that ontology, but they contain only a README file which directs the DISO user to the ontology's home cluster. We do this to avoid the risk of duplicate copies of ontology files becoming out-of-sync with one another.

In `diso-compact`, on the other hand, if a given ontology belongs to more than one DISO cluster, then a copy of the single OWL file representing that ontology is placed in each DISO cluster to which it belongs. This makes cluster membership more explicit and easier to interpret. But it means that `diso-compact` contains **duplicate copies** of several ontologies.

