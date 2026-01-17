# CPE

## Overview 

**CPE: Common Platform Enumeration**

MITRE website (archived):
* https://cpe.mitre.org/
> A structured naming scheme for IT systems, platforms, and packages

> MITRE is pleased to announce that all intellectual property associated with CPE has been transferred to the U.S. National Institute for Standards and Technology (NIST). NIST holds operational responsibility for CPE, and has hosted both the Official CPE Dictionary and the CPE Specifications for several years.

NIST website:
* https://nvd.nist.gov/products/cpe
* CPE is now part of the NIST **NVD**: National Vulnerability Database

CPE is not normally available in OWL format. We obtained our copy of the `cpe.ttl` file from the SEPSES (Semantic Processing of Security Event Streams) research group at Technical University Vienna (https://sepses.ifs.tuwien.ac.at/) in relation to their **ICS Security KG**. 

The origin of this OWL rendering of CPE is not entirely clear. Most of the OWL ontology components that make up the SEPSES integrated **ICS Security KG** were created by the SEPSES group. But the ontology files for these component ontologies clearly state this in annotation comments. The `cpe.ttl` file is an exception in this regard. Yet, many of the prefixes defined in this `cpe.ttl` have SEPSES URLs. So, on balance, the evidence suggests `cpe.ttl` is a SEPSES group rendering of the CPE Dictionary.

For safety, DISO users should regard the `cpe.ttl` ontology file as an expression of CPE, but not necessarily fully up-to-date with the latest version of CPE.

The DISO `cpe.ttl` is one component of the integrated ontology for the SEPSES **ICS Security KG**. See the DISO entry for **ICS-SEC-KG-ONTO** for more information on SEPSES and the **ICS Security KG**, and on the repo from where we obtained the DISO `cpe.ttl`.



