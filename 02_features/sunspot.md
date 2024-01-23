---
layout: page

theme: warm
permalink: features/sunspot

title: Sunspot Testbed Provides On-Ramp for Aurora 
hero-img-source: Sunspot.jpg
hero-img-caption: "Several Aurora application development teams are using Sunspot for scaling and performance optimization research."
intro: "With hardware and software that is identical to Aurora, Sunspot gives researchers a valuable platform for advancing code development work."
---


Researchers preparing scientific codes and workloads to run on the ALCF’s Aurora exascale supercomputer now have a new resource at their disposal. Named Sunspot, the new test and development system is outfitted with the exact same technologies that will power Aurora. 

Aurora, an Intel-Hewlett Packard Enterprise (HPE) system, will be comprised of more than 10,000 nodes equipped with the new Intel Max Series CPUs and GPUs. Sunspot is a two-rack testbed with 128 nodes of the same technologies, including the Slingshot interconnect. 

Prior to Sunspot’s arrival, development teams leveraged earlier Aurora testbeds, Arcticus and Florentia, and DOE supercomputers, including Argonne’s Polaris, to carry out exascale code development. While those systems have been useful in preparing for Aurora, Sunspot’s identical architecture gives researchers an ideal environment for multi-node testing to help them further optimize applications for Aurora. 

# Early Performance Gains

Since Sunspot’s launch in December, more than 180 users from over 20 application development teams from the Aurora Early Science Program (ESP) and DOE’s Exascale Computing Project (ECP) have begun accessing the testbed for scaling and performance optimization research. The ESP and ECP teams’ initial runs on the Aurora GPUs have been promising compared to leading alternative GPUs. Early performance results include:

- As part of the ECP ExaSMR (Exascale Small Modular Reactor) project, researchers achieved 30-70% performance improvements with NekRS, a GPU-oriented thermal-fluids simulation code, across a set of benchmark problems.
- Another ExaSMR code, OpenMC, which is used for neutron and photon transport simulations, showed a 205% performance advantage on the Intel GPUs.
- Supported by ESP and ECP projects, the Argonne-developed Hardware/Hybrid Accelerated Cosmology Code (HACC) has seen 2.6x speedups in early runs on the hardware. 
- QMCPACK, a quantum Monte Carlo code used for electronic structure calculations, has shown a 50% improvement in runs thus far. QMCPACK’s exascale development is supported by both ESP and ECP. 
- XGC, a fusion plasma simulation code that is also supported by ESP and ECP, has performed 60% faster using an initial test problem.

# Paving the Way to Aurora

In addition to helping researchers prepare applications for Aurora, Sunspot is also extremely valuable to the ALCF and Intel as they continue work to stand up the lab’s exascale system. Some bugs may not surface until real applications are run on the hardware, so the ESP and ECP teams’ preparatory runs on Sunspot can help with uncovering and in some cases diagnosing issues before Aurora is powered on.

Sunspot is expected to serve a role even after Aurora enters production mode. Like the ALCF’s previous test and development systems, Sunspot can be a proving ground for new users to test and optimize code performance before moving to Aurora. ALCF staff can also use it to validate and benchmark new software that is targeted for Aurora. 
