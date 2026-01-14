# CORA

## Overview

**CORA: Core Ontology for Robotics and Automation**

CORA is an IEEE specification. It is the OWL specification of the Core Ontology for Robotics and Automation (CORA) and other IEEE 1872-2015 ontologies.

GitHub:
* https://github.com/srfiorini/IEEE1872-owl

CORA is a network of 6 ontologies, most of which import one or more of the others:
```
cora.owl
  imports sumo-cora.owl
  imports corax.owl
  imports rparts.owl
  imports cora-bare.owl

sumo-cora.owl
  imports annotation.owl

corax.owl
  imports annotation.owl
  imports sumo-cora.owl

rparts.owl
  imports cora.owl
  imports annotation.owl

cora-bare.owl
  imports annotation.owl
```

Given the imports structure outlined above, loading `cora.owl` into Protege triggers the import of everything else.

Using Protege, we created a merged version of the ontology network and then saved that merged ontology to the single OWL file `cora-merged.ttl`.

---

NOTE: **CORA** may overlap nicely with **OntoSecRPA**, in the DISO `information-security` cluster. **OntoSecRPA** addresses the Robotics Process Automation domain, as does **CORA**.


