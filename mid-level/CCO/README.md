# CCO

## Overview

**CCO: Common Core Ontologies**

website:
* https://www.ontologyrepository.com/
> CCO is a mid-level extension of Basic Formal Ontology (BFO), an upper-level ontology framework widely used to structure and integrate ontologies in the biomedical domain (Arp, et al., 2015). BFO aims to represent the most generic categories of entity and the most generic types of relations that hold between them, by defining a small number of classes and relations. CCO then extends from BFO in the sense that **every class in CCO is asserted to be a subclass of some class in BFO**, and that **CCO adopts the generic relations defined in BFO** (e.g., has_part) (Smith and Grenon, 2004). Accordingly, CCO classes and relations are heavily constrained by the BFO framework, from which it inherits much of its basic semantic relationships.

GitHub
* https://github.com/CommonCoreOntology/CommonCoreOntologies

> The Common Core Ontology Repository holds the current released version of the Common Core Ontology suite.

> The Common Core Ontologies (CCO) is a widely-used suite of eleven ontologies that consist of logically well-defined generic terms and relations among them reflecting entities across all domains of interest.

> These eleven ontologies constitute a mid-level ontology that extends from the Basic Formal Ontology (BFO), an ISO-standard top-level ontology. Whereas BFO represents only the most generic entities and relations, CCO contains classes that users will find common across data sets in many domains. Such classes include, for example, person, facility, date, employment, nickname, and measurement.

> **Both BFO and CCO have been directed for use as "baseline standards" for formal ontology development across the United States Department of Defense and Intelligence Community**

## The CCO module ontologies

There are 11 CCO modules (component ontologies). 

| Ontology Name                | Description                                                                                                                               |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| **Geospatial Ontology**      | An ontology whose scope is the representation of sites, spatial regions, and other entities, especially those that are located near the surface of Earth, as well as the relations that hold between them. |
| **Information Entity Ontology** | An ontology whose scope is the representation of generic types of information as well as the relationships between information and other entities. |
| **Event Ontology**           | An ontology whose scope is the representation of processual entities, especially those performed by agents, that occur within multiple domains. |
| **Time Ontology**            | An ontology whose scope is the representation of temporal regions and the relations that hold between them. |
| **Agent Ontology**           | An ontology whose scope is the representation of agents, especially persons and organizations, and their roles. |
| **Quality Ontology**         | An ontology whose scope is the representation of a range of attributes of entities especially qualities, realizable entities, and process profiles. |
| **Units of Measure Ontology** | An ontology whose scope is the representation of standard measurement units that are used when measuring various attributes of entities. |
| **Currency Unit Ontology**   | An ontology whose scope is the representation of currencies that are issued and used by countries. |
| **Facility Ontology**        | An ontology whose scope is the representation of buildings and campuses that are designed to serve some specific purpose, and which are common to multiple domains. |
| **Artifact Ontology**        | An ontology whose scope is the representation of artifacts that are common to multiple domains along with their models, specifications, and functions. |
| **Extended Relations Ontology** | An ontology whose scope is the representation of the relations that hold between entities at the level of the mid-level Common Core Ontologies. |


## The CCO merged ontology

The CCO distribution (on GitHub) also contains a **merged** ontology (`CommonCoreOntologiesMerged.ttl`) that contains all 11 CCO modules, plus BFO (`bfo-core.ttl`).
> A stand-alone file containing the eleven mid-level Common Core Ontologies plus BFO. Provided for use-cases where one file representing a specific release of CCO and its imports is desirable.


## CCO connection with defence, intelligence and security domains

According to `The Common Core Ontologies` (Jensen et al., 2024):
* The CCO project was initiated by [CUBRC](https://www.cubrc.org/), a not-for-profit R&D company associated with the University of Buffalo and Barry Smith, in 2010, using a grant from IARPA (Intelligencee Advanced Research Projects Activity), the R&D arm of the U.S. intelligence community.
* The CUBRC made the CCO publicly available in 2017.
* The CCO modules are **"widely used in defense and intelligence sectors to support data standardization, interoperability, reproducibility, and automated reasoning across numerous domains"**.

Per the CUBRC website:
* CUBRC's mission:
> **to help solve some of the most critical and challenging problems facing [the] Defense, Intelligence and Homeland Security communities**.
* CUBRC's projects:
> Using the BFO and CCO as a foundation, CUBRC is a leading developer of **domain level ontologies** that are tailored for specific use across a wide variety of **defense, intelligence, law enforcement, and commercial applications**. 

**CUBRC: Calspan-University of Buffalo Research Centre**
* formed from a relationship between the University of Buffalo and Calspan, a former Cornell Aeronautical Laboratory





