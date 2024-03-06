---
layout: highlight

theme: dark
permalink: 'features/aurora/openmc'

title: 'OpenMC'
pi: 'Steven Hamilton, Oak Ridge National Laboratory; Paul Romano, Argonne National Laboratory'
award: 'Exascale Computing Project'
systems: '-'
sdl: 's'

image: '-' 
image-caption: '-'
image-credit: '-'

---

{% include txt-intro.html 
    blurb = "OpenMC, originally written for CPU-based high-performance computers and which is capable of using both distributed-memory (MPI) and shared-memory (OpenMP) parallelism, simulates the stochastic motion of neutral particles through a model that, as a representation of a real-world experimental setup, can range in complexity from a simple slab of radiation-shielding material to a full-scale nuclear reactor."
%}



# Challenge
The GPU-oriented version of OpenMC has been completed and is already running on a number of GPU-based supercomputers, including Sunspot—the ALCF’s Aurora testbed and development system—and the ALCF’s NVIDIA-based Polaris. While the team’s goal is focused on honing performance on Aurora, the OpenMP offloading model has resulted in strong performance on every machine on which it was deployed, irrespective of vendor.

Current full-machine projections for OpenMC running on Aurora, based on preliminary simulation runs performed on Sunspot, are in the ballpark of 25 billion particle histories per second—indicating a speedup by some 2500x over what could be achieved at full-machine scale at the time of the ECP’s inception (the goal for which had been a fiftyfold speedup).




# Performance Results
The code has been run across multiple GPUs, with large performance gains demonstrated on the Aurora testbed, Sunspot, over other systems, in single-GPU, full-node, and multi-node comparisons. Multi-node comparisons were performed on 96 GPUs.


# Impact

The ECP-supported ExaSMR project aims to use OpenMC to model the entire core of a nuclear reactor, generating virtual reactor simulation datasets with high-fidelity, coupled physics models for reactor phenomena that are truly predictive, filling in crucial gaps in experimental and operational reactor data. The extreme performance gains OpenMC has achieved on GPUs is finally bringing within reach a much larger class of problems that historically were deemed too expensive to simulate using Monte Carlo methods.


