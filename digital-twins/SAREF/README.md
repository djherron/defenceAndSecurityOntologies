# SAREF

## Overview

**SAREF: Smart Applications REFerence** ontology

SAREF was created by the European Telecommunications Standards Institute (ETSI)

website:
* https://saref.etsi.org/
> The Smart Applications REFerence (SAREF) suite of ontologies forms a shared model of consensus intended to enable semantic interoperability between solutions from different providers and among various activity sectors in the Internet of Things (IoT), thus contributing to the development of data spaces.

> SAREF is published as a set of open standards produced by ETSI Technical Committee Smart Machine-to-Machine communications (SmartM2M)

> SAREF is a suite of individually versioned ontologies that contains a **core ontology**, a set of **reference ontology patterns** that provide guidelines on how to use and extend SAREF, and different **extensions** for vertical domains.

> SAREF Core specifies recurring core concepts in the smart applications domain, and the main relationships between these concepts. 

SAREF Core ontology
* https://saref.etsi.org/core/v4.1.1/
* see `saref.ttl`. (v4.1.1)
> The Smart Applications REFerence ontology (SAREF) is intended to enable interoperability between solutions from different providers and among various activity sectors in the Internet of Things (IoT), thus contributing to the development of the global digital market.

SAREF Extensions
* see https://saref.etsi.org/

SAREF4CITY
* https://saref.etsi.org/saref4city/v2.1.1/
* an extension of SAREF for the Smart City domain
* see `saref4city.ttl`

SAREF4BLDG
* https://saref.etsi.org/saref4bldg/v2.1.1/
* an extension of SAREF for the building domain
* see `saref4bldg.ttl`

several other domain extensions of SAREF Core are also available on the SAREF website


## Merged ontologies

Using Protege, we created two **merged** ontologies

with the 3 ontologies together in a directory, we first loaded `saref4city.ttl` in Protege, which then imports `saref.ttl`
* we merged these two ontologies and called the output `saref4cityMerge.ttl`

then we loaded `saref4bldg.ttl` in Protege, which then imports `saref.ttl`
* we merged these two ontologies and called the output `saref4bldgMerge.ttl`


## SAREF and Smart Environments

There is strong overlap between the DISO clusters of `digital-twins` and `smart-environments`

Within DISO, SAREF sits in the `digital-twins` cluster because we first became aware of it within a paper that addresses the topic of Digital Twins:
* `Home Automation System Ontology for Digital Building Twin` (Maryasin, 2019)
* the authors declare that:
> The most common smart-home and BMS [building management systems] ontologies are SAREF, SAREF4EE, Brick, and BOnSAI


