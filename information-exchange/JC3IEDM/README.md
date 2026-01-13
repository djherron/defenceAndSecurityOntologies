# JC3IEDM

## Overview

**JC3IEDM: Joint Consultation, Command and Control Information Exchange Data Model**

The JC3IEDM is a data model intended for the exchange of command, control and communication information (hence the `C3` in the name).

> The JC3IEDM specifies the minimum data set required for interoperability between Command and Control Information Systems (C2ISs) and the information exchange mechanism

> The model defines the standard elements of information (data) that form the basis for interoperability between automated Command and Control Information Systems (C2ISs)

Per [Wikipedia](https://en.wikipedia.org/wiki/JC3IEDM):
> JC3IEDM ... is a model that ... aims to enable the interoperability of systems and projects required to share Command and Control (C2) information.
> JC3IEDM is produced by the MIP-NATO Management Board (MNMB) and ratified under NATO STANAG 5525.JC3IEDM a fully documented standard for an information exchange data model for the sharing of C2 information.

MIP: The *Multilateral Interoperability Programme* (MIP) 
* the MIP, in conjunction with the North Atlantic Treaty Organization (NATO), is the configuration manager of JC3IEDM specifications
* https://en.wikipedia.org/wiki/Multilateral_Interoperability_Programme

JC3IEDM is a **data model expressed in UML**. But a commercial company, [Vistology](https://vistology.com/), developed tools for automating the conversion of the JC3IEDM data model into an OWL ontology.
* their resource paper: `On the Automatic Generation of an OWL Ontology based on the Joint C3 Information Exchange Data Model`, Matheus & Ulicny, 2007, 12th International Command and Control Research and Technology Symposium
> The primary purpose of this work is to provide the basis for a semantically rich ontology for use in representing and reasoning about command, control and communication operations.

Download:
* https://vistology.com/ont/JC3IEDM/JC3IEDM3.0/JC3IEDM.owl
* see `JC3IEDM.owl`
* this ontology pertains to JC3IEDM v3.0, from 2006


## JC3IEDM and Situation Awareness

JC3IEDM is an **information exchange** data model, but it was designed with **situational awareness** (SA) in mind.

Whereas IES is a general-purpose information exchange standard that supports the exchange of SA information (along with other information), JC3IEDM was designed specifically for military command and control contexts where SA is operationally critical.

Within DISO, we could have placed JC3IEDM within the `situation-awareness` subdomain (cluster) of ontologies.  There is a strong likelihood of ontology overlaps and, hence, interesting ontology alignment opportunities between JC3IEDM and the `situation-awareness` ontologies.


