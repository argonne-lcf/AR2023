---
layout: page
theme: cyan
permalink: features/polaris

title: Polaris Enters Production Mode
hero-img-source: ALCF-Polaris.jpg
hero-img-caption: "The ALCF's Polaris supercomputer provides advanced capabilities for workloads involving simulation, data analysis, and AI tasks."
intro: "The ALCF’s most powerful system to date is supporting several large-scale science projects while also helping researchers prepare for Aurora."
---


The ALCF deployed Polaris for scientific research in August, giving its user community a powerful new resource to prepare for science in the exascale era. 

The new supercomputer is the ALCF’s most powerful system to date, delivering 34 petaflops of peak performance (44 petaflops of Tensor Core FP64 performance) and nearly 1.4 exaflops of theoretical AI performance. Polaris is providing a platform for researchers to prepare codes and workloads for the upcoming Aurora exascale supercomputer while simultaneously supporting several large-scale research projects, including efforts focused on using AI for science.

At Argonne, Polaris is also a key tool for advancing efforts to integrate ALCF computing resources more closely with DOE experimental facilities. Initial work is focused on coupling ALCF systems with the co-located Advanced Photon Source and Center for Nanoscale Materials, both DOE Office of Science user facilities.

Like Aurora, Polaris is a hybrid system powered by both central processing units (CPUs) and graphics processing units (CPUs). This similarity, along with some other shared technologies, is helping ease the transition to using Aurora for scientific research ahead of its deployment.  

The HPE Apollo Gen10+ based supercomputer is equipped with 560 AMD EPYC processors and 2,240 NVIDIA A100 Tensor Core GPUs. The Polaris software environment is equipped with the HPE Cray programming environment, HPE Performance Cluster Manager (HPCM) system software, and the ability to test programming models, such as OpenMP and SYCL, that will be available on Aurora and the next generation of DOE supercomputers. Polaris users will also benefit from NVIDIA’s HPC software development kit — a suite of compilers, libraries, and tools for GPU code development.

Upon the deployment of Polaris, several research teams immediately began using the system to prepare for the arrival of Aurora via DOE’s Exascale Computing Project (ECP) and the ALCF’s Aurora Early Science Program (ESP). The system is also being leveraged by multiple projects awarded time through DOE’s INCITE and ALCC allocation programs. The following summaries highlight some of the initial projects tapping Polaris to accelerate science.

{% include media-img.html
   source= "burrows.png"
   caption= "Researchers from Princeton University are using Polaris for large-scale 3D simulations aimed at advancing our understanding of supernova explosions."
   credit= "Argonne National Laboratory and Princeton University"
%}

# Exascale Preparations

Researchers from DOE’s Princeton Plasma Physics Laboratory are leading an Aurora ESP project that aims to use particle simulations of plasma, including impurities and the important magnetic field geometry at the edge, to predict behavior of ITER plasmas and to help guide future experimental parameters. The team is using Polaris to run simulations of the DIII-D National Fusion Facility’s tokamak device with carbon impurities to inform their planned simulations of ITER plasmas with tungsten impurities on Aurora.

The NWChemEx team, supported by the ESP and ECP, will use Aurora to advance the understanding of chemical systems to aid in developing new methods for converting biomass into biofuels. In preparation for larger simulations on Aurora, the researchers are leveraging Polaris to carry out simulations to produce initial geometries appropriate for the conversion of propene to propanol within zeolites.

An ESP team from the Massachusetts Institute of Technology plans to use Aurora to couple machine learning and state-of-the-art physics simulations to determine possible interactions between nuclei and a large class of dark matter candidate particles. Their machine learning models had only been tested on small-scale problems so the team is using Polaris to scale up problem sizes to determine if they need to modify their machine learning models for their upcoming runs on Aurora. 

# Science Campaigns

With an INCITE award, researchers from the Flatiron Institute are using Polaris to aid in their efforts to reduce the computational and energetic costs of producing successful peptide macrocycle drugs or industrial enzymes with useful functions in medicine and manufacturing. The INCITE team will develop low-cost machine learning methods that can approximate the output of computationally expensive validation simulations, ultimately allowing users without access to large-scale resources to perform design and validation tasks on much more modest computing systems.

An Argonne-led ALCC team is leveraging Polaris to perform high-fidelity computational fluid dynamics and multiphysics simulations to investigate fundamental flow phenomena in next-generation nuclear power reactors. The project’s simulations will be carried out in collaboration with X-energy and TerraPower (recipients of awards from DOE’s Advanced Reactor Demonstration Program) with the potential to accelerate the deployment of carbon-free energy solutions. 

Building on years of work using Theta, a Princeton University-led team is using Polaris to advance their 3D simulations of core-collapse supernova. With their new INCITE allocation, the researchers will conduct not only a full suite of 3D simulations for the spectrum of progenitor stars but carry out these simulations for approximately five times the physical time possible with their previous INCITE allocations, all the way to the asymptotic state. 


