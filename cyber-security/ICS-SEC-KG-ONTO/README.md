# ICS-SEC-KG-ONTO

## Overview 

**ICS-SEC-KG-ONTO: the ontology of the SEPSES 'ICS Security KG'**

**SEPSES**: Semantic Processing of Security Event Streams
* https://sepses.ifs.tuwien.ac.at/
* SEPSES is a research group at Technical University Vienna working at the intersection of ontologies and cyber-security

**ICS**: Industrial Control System

The SEPSES group developed an **ICS Security knowledge graph** [ICS-SEC-KG](https://sepses.ifs.tuwien.ac.at/index.php/cyber-kg/). 

The ontology for that KG (what DISO has named `ics-sec-kg-onto.ttl`) integrates 7 well-established 3rd-party cyber-security ontologies (all of which are also available in DISO, largely thanks to the SEPSES group making them available):
* ATTACK (this is the MITRE Corporation ATT&CK for ICS ontology)
* CAPEC (Common Attack Pattern Enumerations and Classifications)
* CPE (Common Platform Enumeration) 
* CVE (Common Vulnerabilities and Exposures) 
* CVSS (Common Vulnerability Scoring System)
* CWE (Common Weakness Enumeration)
* ICSA (Industrial Control Systems Adversary)

We obtained `ics-sec-kg-onto.ttl` (and its 7 3rd-party component ontologies) from the SEPSES [ICS-SEC-KG repo](https://github.com/sepses/ics-sec-kg). On that repo, the file that DISO calls `ics-sec-kg-onto.ttl` is named `integrated.ttl`. For DISO, we simply changed the name of this file to make it less generic. 

From the **ICS-SEC-KG repo**:
> The ICS-SEC KG is a cybersecurity knowledge graph that integrates and links critical cybersecurity information of Industrial Control System (ICS) and Operational Technology (OT) from various publicly available sources. It extends the existing SEPSES-CSKG by including ICS-related security resource such as Industrial Control System Advisory (ICSA) and MITRE ATT&CK for ICS. 

The **ICS-SEC-KG repo** contains a Figure showing the integrated ICS-SEC ontology, and a listing of its component 3rd-party ontologies.  These provide helpful context.

From the SEPSES [vocab repo](https://github.com/sepses/vocab/) we obtained an 8th 3rd-party cyber-security ontology:
* SNORT (Network Intrusion Detection & Prevention) 

SNORT is NOT part of the `ics-sec-kg-onto.ttl` ontology file.

Each of the 8 3rd-party cyber-security ontologies mentioned above has its own entry in DISO. If you want to use the integrated ICS-SEC ontology, `ics-sec-kg-onto.ttl`, together with its components, you have to fetch the components from their separate DISO entries.


