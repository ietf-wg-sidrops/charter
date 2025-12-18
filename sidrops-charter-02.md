## SIDROPS Charter

The global deployment of Secure Inter-Domain Routing (SIDR), consisting of Resource Public Key Infrastructure (RPKI), Origin Validation of BGP announcements, and BGPsec, is still underway, creating an Internet Routing System consisting of SIDR-aware and non-SIDR-aware networks. This deployment must be properly handled to avoid the division of the Internet into separate networks. SIDR Operations Working Group (SIDROPS WG) is responsible for continuing the development of SIDR technology, encouraging its deployment, while ensuring as secure of a global routing system as possible, during the transition. Specifically, SIDROPS is responsible for the maintenance of all SIDR components, except BGPsec.

The SIDROPS WG is focused on deployment and operational issues, their mitigations, and experiences with SIDR technologies that are part of the global routing system, as well as the repositories and Certification Authority (CA) systems that form part of the SIDR architecture.

SIDROPS will solicit input from a variety of contributors, including but not limited to, CA Operators, Regional/National and Local Internet Registries, Relying Party software developers, researchers, participants of the measurements community, and network operators.

The goals of SIDROPS WG are:

* Maintain RPKI technology stack. 

* Identify operational issues with a SIDR-aware Internet and with interaction with the non-SIDR-aware Internet.

* Develop solutions for identified issues. This includes in particular:
  
    + Developing guidelines for the operation of SIDR-aware networks and providing operational guidance on how to deploy and operate SIDR technologies in existing and new networks (Informational/BCP).
      
    + Standardizing protocols and protocol extensions to improve operational efficiency and security of SIDR such as Autonomous System Provider Authorization (ASPA) and reliable cache synchronization mechanisms.

* Standardize manageability (e.g., YANG data models) and OAM solutions related to SIDR operations.

* Document common SIDROPS terminology as Informational RFC.

Given the importance of routing security to the overall stability of the Internet, the WG will not submit protocol specifications for publication to the IESG before demonstrating at least two interoperable implementations. See RFC 5657 (part of BCP 9) for guidance on what implementation reports should contain and BCP 205 for guidance on how to raise awareness of running code.

BGPsec (RFC 8205) maintenance, extensions, and updates belong to IDR WG. SIDROPS may provide input to IDR, as needed, and will cooperate with that WG in reviewing solutions to BGPsec operational and deployment problems. Documenting the operational aspects of securing the Internet routing system other than SIDR belongs to GROW WG.

Gaps in other protocols which impact SIDR operation is the responsibility of the WGs that own these protocols.

## Milestones

| Date | Milestone |
| --- | --- | 
| Mar 2026 | Submit draft-ietf-sidrops-8210bis to the IESG for publication|
| Mar 2026 | Submit draft-ietf-sidrops-aspa-profile to the IESG for publication|
| Mar 2026 | Submit draft-ietf-sidrops-aspa-verification to the IESG for publication|
| Jul 2026 | Submit draft-ietf-sidrops-aspa-notation to the IESG for publication|
| Jul 2026 | Submit draft-ietf-sidrops-aspa-slurm to the IESG for publication|
