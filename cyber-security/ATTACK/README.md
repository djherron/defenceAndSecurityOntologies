# ATTACK

## Overview 

**ATTACK: the MITRE Corporation ATT&CK cyber-security ontology**

website:
* https://attack.mitre.org/
> MITRE ATT&CK® is a globally-accessible knowledge base of adversary tactics and techniques based on real-world observations. The ATT&CK knowledge base is used as a foundation for the development of specific threat models and methodologies in the private sector, in government, and in the cybersecurity product and service community.

ATT&CK is not normally available in OWL format. The SEPSES (Semantic Processing of Security Event Streams) research group at Technical University Vienna (https://sepses.ifs.tuwien.ac.at/) created an OWL version of ATT&CK for their **ICS Security KG**. 

The OWL ontology file for ATT&CK that we have obtained for DISO, `attack.ttl`, was created by the SEPSES team by rendering the **then existing** definition of ATT&CK into OWL. It's not clear whether ATT&CK as currently defined (on the MITRE website) is ahead of the version of ATT&CK rendered in `attack.ttl` from SEPSES. It may be well ahead.

For safety, DISO users should regard the `attack.ttl` ontology file as an expression of ATT&CK, but not necessarily fully up-to-date with the latest version of ATT&CK.

The DISO `attack.ttl` is one component of the integrated ontology for the SEPSES **ICS Security KG**. See the DISO entry for **ICS-SEC-KG-ONTO** for more information on SEPSES and the **ICS Security KG**, and on the repo from where we obtained the DISO `attack.ttl`.
