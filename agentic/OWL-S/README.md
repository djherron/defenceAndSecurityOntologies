# OWL-S

## Overview

**OWL-S: a Web Services ontology**

website:
* `http://www.daml.org/services/owl-s/`
> an OWL-based Web Service Ontology, OWL-S (formerly DAML-S), as well as supporting tools and agent technology to enable automation of services on the Semantic Web

> OWL-S supplies Web service providers with a core set of markup language constructs for describing the properties and capabilities of their Web services in unambiguous, computer-intepretable form. OWL-S markup of Web services will facilitate the automation of Web service tasks including **automated Web service discovery, execution, interoperation, composition and execution monitoring**.

OWL-S 1.2 Release:
* https://www.daml.org/services/owl-s/1.2/

For DISO, we downloaded 7 component ontologies for OWL-S v1.2:
* Expression, Grounding, ObjectList, Process, Profile, Resource, Service     
* some of these components import other of the components; some do not

Using Protege, we created an OWL-S ontology file that **merges** these 7 components:
* We imported the 7 components into Protege, created a merged ontology, and saved the merged ontology to `owl-s.ttl`

## Rationale for obtaining OWL-S for DISO

OWL-S v1.2 is from 2008, which predates today's notions of Agentic AI by a long way.

But, the ambition of OWL-S --- to automate service discovery, execution, interoperation, composition --- sounds very much like the goals of today's Agentic AI protocols, such as MCP and A2A.

We regard OWL-S as a precursor of today's (2026) Agentic AI protocols.


