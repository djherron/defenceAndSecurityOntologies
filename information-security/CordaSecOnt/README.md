# CordaSecOnt

## Overview

**CordaSecOnt: Corda Security Ontology**

paper:
* `Corda Security Ontology - Example of Post-Trade Matching and Confirmation` (Iqbal, 2020)

**CordaSecOnt** is an **information security** ontology with classifications of assets, security criteria, threats, vulnerabilities, risk treatments, security requirements, countermeasures and their relations.

The target application that motivated the development of CordaSecOnt is **capital markets post-trade matching and confirmation**.

GitHub for **CordaSecOnt**
* https://github.com/mubashar-iqbal/corda-security-ontology

The GitHub repo contains **two versions** of **CordaSecOnt**, plus a companion ontology named **ULRO** (Upper Level Reference Ontology, for security risk management). All three of these ontologies were developed by the same person (Mubashar Iqbal).

`CordaSecOnt-v1.owl`
* Version 1 of **CordaSecOnt** has no dependency on the companion **ULRO** ontology.

`CordaSecOnt-v2.owl`
* Version 2 of **CordaSecOnt** builds on the companion **ULRO** ontology.
* There are no `owl:imports` statements in `CordaSecOnt-v2.owl`, however. **ULRO** appears to be fully baked into **CordaSecOnt** v2, with all of the **ULRO** classes and properties appearing within the `CordaSecOnt` namespace rather than an `ULRO` namespace.
* So the presence of the `ulro.owl` ontology file here is not necessary in order to use `CordaSecOnt-v2.owl`. It simply provides context that helps explain why and how v2 differs from v1.

---

Web presence for **ULRO**
* https://mmisw.org/ont/~mubashar/ULRO

Despite the fact that Iqbal refers to **ULRO** as an **upper-level** ontology, we have opted to NOT include ULRO within the DISO subdomain (cluster) of `upper-level` ontologies. The main reasons for this are:
* the fact that the ontology is domain-specific appears to contradict the fundamental idea of upper-level ontologies being general enough to sit above **all** particular domains
* it is authored by an individual researcher as a personal project.

When we have had a chance to evaluate **ULRO** and the other `upper-level` DISO ontologies properly, if **ULRO** earns our respect we may change our mind and promote it into the `upper-level` cluster. But, until such time, it will remain here, alongside the **CordaSecOnt** **information security** ontology.


