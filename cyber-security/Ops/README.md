# Ops

## Overview 

**Ops: an operations ontology**

A cyber-security ontology with a focus on **operations domains**.

Ops ontology GitHub repo:
* https://github.com/CDSRV/ops-ontology

There is virtually no documentation on the GitHub repo describing the **Ops** ontology. And there is no explanation of the acronym `CDSRV`. So the nature and provenance of this ontology are both opaque.

The file `ops-owlviz.png` provides an image of the Ops class hierarchy.

We encountered several issues with `ops.ttl` when loading it into Protege. Several `owl:imports` statements failed. As part of resolving these issues, we resorted to editing the `ops.ttl` file to remove a few `owl:imports` statements for ontologies that were redundant.

Once we were able to load our edited `ops.ttl` into Protege successfully, we created a merged ontology and called this `ops-merged.ttl`.  This loads into Protege cleanly apart from 1 pair of WARN messages about use of 'illegal punning'.




