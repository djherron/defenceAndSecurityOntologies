# UCO (2)

## Overview 

**UCO: Unified Cybersecurity Ontology**

A personal research effort by Zareen Syed.

paper:
* `UCO: A Unified Cybersecurity Ontology` (Syed et al., 2016)
> Among all cybersecurity standards and formats, STIX is the most comprehensive effort to unify cybersecurity information sharing. However, it is represented in XML and hence does not support reasoning

> We have created UCO as a semantic version of STIX.

> In addition to mapping to STIX, UCO has also been extended with a number of relevant cybersecurity standards, vocabularies and ontologies such as CVE, CCE, CVSS, CAPEC, CYBOX, KillChain, and STUCCO.

> UCO ontology has been mapped to general world knowledge available through Google’s knowledge graph, DBpedia knowledge base (Auer et al. 2007), Yago knowledge base

**NOTE**: Syed's merge of all these different ontologies may mean that alignments between have been defined within the merged ontologies. These alignments might be extractable.

GitHub repo:
* https://github.com/Ebiquity/Unified-Cybersecurity-Ontology

For DISO, we have obtained the latest version of UCO from this repository, which is version 2: `uco2.ttl`

It's not clear how many of the ontologies mentioned in the paper (above) are actually in `uco2.ttl`. 

It defines prefixes for
* CAPEC
* CYBOX
* STIX

And some of the actual entity names contain the acronyms `CCE`, `CVSS`, `cwe` and `KillChain`.

This suggests, `uco2.ttl` contains most of the ontologies mentioned in the paper, above, but perhaps not all.


## Caution: two ontologies share the name UCO

There is an unfortunate **name clash** between two cyber-security ontologies that have both been named **UCO**. To distinguish between them, DISO refers to them as `UCO_1` and `UCO_2`.

The `2` in Syed's filename `uco2.ttl` is really a version number, indicating this is version 2 of the Syed UCO ontology.

For our convenience within DISO, we use this `2` as indicating `UCO_2`, to help distinguish the ontology from `UCO_1`.  The `UCO_1` ontology we have named `uco1-merge.ttl`

Be careful not to mistake one UCO ontology for the other. They are very different.




