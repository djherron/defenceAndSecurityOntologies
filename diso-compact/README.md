# README

`diso-compact` is a compact (condensed) version of this **DISO** repository.

It contains the same DISO cluster structure, but each ontology is represented only by a single ontology file.

Some ontologies in the DISO collection fit nicely in more than one DISO cluster. On the DISO GitHub repository, the actual ontology files for such ontologies reside in only one cluster. We use empty cluster entries containing only a README file to document for DISO users the fact that a given ontology belongs to a cluster but is physically stored in another cluster. We do this to avoid maintaining duplicate copies of ontologies that might become out-of-sync.

In contrast, in `diso-compact` we include physical copies of such ontology files in each cluster in which they belong. This makes cluster membership more explicit and easier to interpret. But it means that `diso-compact` contains **duplicate** copies of some ontologies.

