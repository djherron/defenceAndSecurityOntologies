# UCO (1)

## Overview 

**UCO: Unified Cyber Ontology**

An open community effort focused on cyber-security.

website:
* https://unifiedcyberontology.org/
> Unified Cyber Ontology (UCO) is a community-developed ontology/model, which is intended to serve as a consistent foundation for standardized information representation across the cyber security domain/ecosystem.

> Specific information representations focused on individual cyber security subdomains (cyber investigation, computer/network defense, threat intelligence, malware analysis, vulnerability research, offensive/hack-back operations, etc.) can be based on UCO and defined as appropriate subsets of UCO constructs.

UCO GitHub repo:
* https://github.com/ucoProject/UCO 
* The current release of UCO is 1.4.0. 
* Date: 2025-05-28 
* This is what we have obtained for DISO.

Generated documentation
* https://ontology.unifiedcyberontology.org/documentation/index.html

As can be seen on the UCO GitHub repo, UCO comes as a collection of component ontologies. There is one main ontology file that is tiny. All it does is import everything else. This file is called `uco.ttl`.

We loaded `uco.ttl` into Protege and, after fixing a couple of import errors, we created a merge of all the individual ontology files and called in `uco1-merge.ttl`. This is what we have on DISO --- a single file merge of all the UCO component ontologies.

Interesting ontology alignment opportunities may exist between:
* UCO and STIX
  - see `Cybersecurity Knowledge Graphs` (Sikos, 2023)
* UCO and MDISOnt
  - see `Building a Comprehensive and Multi-dimensional Information Security Ontology` (Meriah, 2025)

## Caution: two ontologies share the name UCO

There is an unfortunate **name clash** between two cyber-security ontologies that have both been named **UCO**. To distinguish between them, DISO refers to them as `UCO_1` and `UCO_2`.

To help users distinguish between these two UCO ontologies, we have named the ontology file for `UCO_1` as `uco1-merge.ttl`. The `UCO_2` ontology is named `uco2.ttl`.

Be careful not to mistake one UCO ontology for the other. They are very different.




