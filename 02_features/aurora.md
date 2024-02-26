---
layout: page

theme: dark
permalink: features/aurora

title: Standing Up Aurora
hero-img-source: Aurora-blade-33603D_0640.jpg
hero-img-caption: "Susan Coghlan (center), ALCF Project Director for Aurora, discusses the system installation with colleagues from Intel."
intro: "The ALCF made significant progress in deploying its exascale supercomputer in 2023, completing the hardware installation, registering early performance numbers, and supporting early science teams’ initial runs on the system."
---

In June 2023, the installation of Aurora’s 10,624th and final blade marked a major milestone in the efforts to deploy the ALCF’s exascale supercomputer. With the full machine in place and powered on, the Aurora team was able to begin the process of stress-testing, stabilizing, and optimizing the massive system to prepare for acceptance and full deployment in 2024.  

{% include media-img.html
   source= "Aurora-blade-33603D_2592.jpg"
   caption= "The Aurora team uses a specialized machine to install the supercomputer's blades."
%}

Built in partnership with Hewlett Packard Enterprise (HPE), Aurora is one of the fastest supercomputers in the world, with a theoretical peak performance of more than two exaflops of computing power (or more than 2 billion billion calculations per second). It is also one of world’s largest supercomputers, occupying 10,000 square feet and weighing 600 tons. The system is powered by 21,248 Intel Xeon CPU Max Series processors and 63,744 Intel Data Center GPU Max Series processors. Notably, Aurora features more GPUs and more network endpoints in its interconnect technology than any system to date. To pave the way for a machine of this scale, Argonne first had to complete some substantial facility upgrades, including adding new data center space, mechanical rooms, and equipment that significantly increased the building’s power and cooling capacity. 

As is the case with all DOE leadership supercomputers, Aurora is a first-of-its-kind system equipped with leading-edge technologies that are being deployed at an unprecedented scale. This presents unique challenges in launching leadership-class systems as various hardware and software issues only emerge when approaching full-scale operations. The Aurora team, which includes staff from Argonne, Intel and HPE, continues work to stabilize the supercomputer, which includes efforts such as optimizing the flow of data between network endpoints.

# Early Performance Numbers

In November, Aurora demonstrated strong early performance numbers while still in the stabilization period, underscoring its immense potential for scientific computing. 

At the SC23 conference, the supercomputer made its debut on the semi-annual TOP500 List with a partial system run. Using approximately half of the system’s nodes, Aurora achieved 585.34 petaflops, earning the #2 overall spot. In addition, Aurora’s storage system, DAOS, earned the top spot on the IO500 Production List, a semi-annual ranking of HPC storage performance. 

{% include media-img.html
   source= "SC23-Aurora-talk.jpg"
   caption= "ALCF's Kevin Harms discusses Aurora during a tech talk at Intel's booth at the SC23 conference."
%}

# Early Science Access

In another significant milestone for the supercomputer, early science teams began using Aurora for the first time in 2023. Several teams from the ALCF’s Aurora Early Science Program (ESP) and DOE’s Exascale Computing Project (ECP) were able to transition their work from the Sunspot test and development system to Aurora to start scaling and optimizing their applications for the supercomputer’s initial science campaigns. Their work has included performing scientifically meaningful calculations across a wide range of research areas.

The ECP and ESP teams’ initial runs on the Aurora GPUs have been promising compared to leading alternative GPUs. Some of the early application performance results include:

-	As part of the ECP ExaSMR (Exascale Small Modular Reactor) project, researchers achieved 30-70 percent performance improvements with NekRS, a GPU-oriented thermal-fluids simulation code, across a set of benchmark problems.
-	Another ExaSMR code, OpenMC, which is used for neutron and photon transport simulations, showed a 205 percent performance advantage on the Intel GPUs.
-	Supported by ESP and ECP projects, the Argonne-developed Hardware/Hybrid Accelerated Cosmology Code (HACC) has seen 2.6x speedups in early runs on the hardware.
-	QMCPACK, a quantum Monte Carlo code used for electronic structure calculations, has shown a 50 percent improvement in runs thus far. QMCPACK’s exascale development is supported by both ESP and ECP.
-	XGC, a fusion plasma simulation code that is also supported by ESP and ECP, has performed 60 percent faster using an initial test problem.

Once their applications have been fully scaled and optimized for Aurora, the ECP and ESP teams will use the machine to carry out innovative research campaigns involving simulation, artificial intelligence, and data-intensive workloads in areas ranging from fusion energy science and cosmology to cancer research and aircraft design. In addition to pursuing groundbreaking research, these early users help to further stress test the supercomputer and identify potential bugs that need to be resolved ahead of its deployment.

In 2024, an additional 24 research teams will begin using Aurora to ready their codes for the system via allocation awards from DOE’s INCITE program. 

# ALCF-4: Planning for Argonne’s Next-Generation Exascale System

Looking beyond Aurora, the facility also kicked off the ALCF-4 effort to prepare for its next-generation supercomputer. In April 2023, DOE approved Critical Decision-0 (CD-0), which is the first step in procuring a new system.  

Led by Jini Ramprakash, ALCF-4 Project Director, and Kevin Harms, ALCF-4 Technical Director, the team is targeting 2028-2029 for the deployment of the facility’s next production supercomputer. The project’s goals include enabling a significant improvement in application performance over Aurora; continuing to support traditional HPC workloads alongside AI and data-intensive computations; and investigating the potential to accelerate the deployment and realization of new technologies.

