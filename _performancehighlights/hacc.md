---
layout: highlight

theme: dark
permalink: 'features/aurora/hacc'

title: '-'
pi: 'Katrin Heitmann and Salman Habib, Argonne National Laboratory'
award: 'Aurora Early Science Program and Exascale Computing Project'
systems: '-'
sdl: 's'

image: '-' 
image-caption: '-'
image-credit: '-'

---

{% include txt-intro.html 
    blurb = "HACC (Hardware/Hybrid Accelerated Cosmology Code) is a cosmological N-body and hydrodynamics simulation code designed to run at extreme scales on HPC systems operated by DOE national laboratories. HACC computes the complicated emergence of structure in the universe across cosmological history, the core of the code’s functionality consisting of gravitational calculations along with the more recent addition of gas dynamics and astrophysical subgrid models."
%}



# Challenge

HACC is structured to remain mostly consistent across different architectures such that it requires only limited changes when ported to new hardware; the inter-nodal level of code—the level of code that communicates between nodes—is nearly invariant from machine to machine. Consequently, the approach taken to porting HACC effectively reduces the problem to the node level, thereby permitting concentration of effort on optimizing critical code components with a full awareness of the actual hardware.

In bringing HACC to exascale, the developers have aimed to evaluate Aurora’s early hardware and software development kit on a set of more than 60 complex kernels primarily written in CUDA or otherwise under active development, minimize divergence between CUDA and SYCL versions of codebase, identify configurations and implementation optimizations specific to Intel GPUs, and identify more generally applicable implementation optimizations.

Versions of HACC being developed for exascale systems incorporate basic gas physics (hydrodynamics) to enable more detailed studies of structure formation on the scales of galaxy clusters and individual galaxies. These versions also include sub-grid models that integrate phenomena like star formation and supernova feedback, which means the addition of more performance-critical code sections; these sections will be offloaded to run on the GPUs. A GPU implementation of HACC with hydrodynamics was previously developed for the Summit system using CUDA. All the GPU versions of the code are being rewritten to target Aurora.


# Performance Results
HACC simulations have been performed on Aurora in runs using as many as 1536 nodes. Visualizations of results generated on Aurora illustrate the large-scale structure of the universe. Single-GPU performance on Aurora exceeds that of compared systems: Figure-of-Merit assessments measuring particle-steps per second used 33 million particles per GPU) saw performance increases ranging from 15 to 50 percent.



# Impact

Modern cosmology provides a unique window to fundamental physics, and has led to remarkable discoveries culminating in a highly successful model for the dynamics of the Universe. Simulations and predictions enabled by the HACC code deployed at exascale will help deepen our understanding of the structure of the universe and its underlying physics. Furthermore, new generations of cosmological instruments, such as the Vera Rubin Observatory, will depend on exascale systems in order to perform measurements of unprecedented precision, and exascale cosmological simulations developed through HACC will enable researchers to simultaneously analyze observational data from state-of-the-art telescopes to test different theories.
