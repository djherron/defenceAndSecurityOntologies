# STIX

## Overview 

**STIX: Structured Threat Information eXpression**

The official STIX specification, managed by the OASIS Cyber Threat Intelligence (CTI) Technical Committee, uses a data model better suited for property graphs and is primarily published in JSON schemas. The OASIS Threat Actor Context (TAC) technical committee has created OWL representations of the STIX specification.

OASIS Threat Actor Context (TAC) technical committee GitHub repo:
* https://github.com/oasis-tcs/tac-ontology
> The purpose of this repository is to manage Ontology Web Language (OWL) representations of the Threat Actor Context Technical Committee's (TAC-TC) work
* the repo provides **two OWL representations of the STIX 2.1 specification**
* this is where we obtained STIX for the DISO collection
* see folder `stix-spec`
* see folder `stix-semex`
* see folder `docs` for documentation on these two OWL representations of STIX

`./stix-spec/stix-spec.owl`
* the STIX 2.1 Specification ontolgy
> is meant to be as true of a ontology representation to the OASIS STIX 2.1 Specification document as possible.
* however, the documentation for this representation STIX (see `./docs/stix-spec.md`) highlights that this representation of the STIX 2.1 specification is better suited to **property graphs** rather than **semantic graphs**
* it cautions that:
> A Description Logics Reasoner is meant to interpret semantic graphs, not property graphs.
* they seem to be warning that reasoners could struggle with the OWL representation of STIX; if so, then **matching systems** that undertake any reasoning may struggle with this representation of STIX

`./stix-semex/stix-semex.owl`
* this is the STIX 2.1 specification represented as a **semantic graph** rather than a **property graph**
* it's called the STIX Semantic Extension ontology
* it imports the other representation and extends it
* so, if **matching systems** have problems working with `stix-spec.owl`, we can try `stix-semex.owl`

STIX documentation
* https://oasis-open.github.io/cti-documentation/
> The OASIS Cyber Threat Intelligence (CTI) TC supports automated information sharing for cybersecurity situational awareness, real-time network defense, and sophisticated threat analysis.

OASIS Cyber Threat Intelligence (CTI) TC
* https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=cti
> Supporting automated information sharing for cybersecurity situational awareness, real-time network defense, and sophisticated threat analysis

With Protege, we created a **merged** version of `stix-spec.owl` that draws all of it many imports into a single file. We called this `stix-spec-merged.ttl`.




