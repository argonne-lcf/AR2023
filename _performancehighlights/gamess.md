---
layout: highlight

theme: dark
permalink: 'features/aurora/gamess'

title: 'GAMESS'
pi: 'Mark Gordon, Iowa State University'
award: 'Exascale Computing Project'
systems: '-'
sdl: 's'

image: '-' 
image-caption: '-'
image-credit: '-'

---

{% include txt-intro.html 
    blurb = "Full-scale utilization of the Aurora system will enable GAMESS users to carry out demanding tasks like computing the energies and reaction pathways of catalysis processes within a large silica nanoparticle.
Through computation on a well-defined representative heterogeneous catalysis problem comprising mesoporous silica nanoparticles, GAMESS will demonstrate the capability to model physical systems requiring chemical interactions that involve many thousands of atoms, indicating a new ability to model complex chemical processes. A variety of molecular properties, ranging from simple dipole moments to frequency dependent hyperpolarizabilities may be computed. Many basis sets are stored internally, together with effective core potentials or model core potentials, so that essentially the entire periodic table can be considered."
%}



# Challenge

GAMESS is written in Fortran and OpenMP offload and uses the effective fragment molecular orbital (EFMO) framework in conjunction with the resolution-of-the-identity second-order Møller–Plesset perturbation (RI-MP2) method. The project is developing ab-initio fragmentation methods to more efficiently tackle challenges in computational chemistry such as heterogeneous catalysis problems, and has the ultimate goal of enabling quantum chemistry to be applied to extremely large systems of interest in catalysis and energy research. Programming models include linear algebra libraries and CUDA, as well as plans for HIP/DPC++ and OpenMP.

To take full advantage of exascale architectures, it is critical that application software be developed that can exploit multiple layers of parallelism and take advantage of emerging low-power architectures that dramatically lower energy and power costs without significant deterioration of time-to-solution. This work will develop ab initio methods for GAMESS based on fragmentation methods that have been shown to scale beyond the petascale combined with QMC. To attain exascale performance, GAMESS will be refactored to take advantage of modern computer hardware and software, and the capabilities of the C++ libcchem code that is codeveloped with GAMESS will be greatly expanded.




# Performance Results
In 2023, the GAMESS team leveraged the Aurora system to perform simulations of silica nanoparticles surrounded by thousands of water molecules, scaling on up to 512 nodes of the system. Results have demonstrated performance some 2.5 times greater than was achieved using other tested architectures.


# Impact
Full-scale utilization of the Aurora system will enable GAMESS users to carry out demanding tasks like computing the energies and reaction pathways of catalysis processes within a large silica nanoparticle.

Through computation on a well-defined representative heterogeneous catalysis problem comprising mesoporous silica nanoparticles, GAMESS will demonstrate the capability to model physical systems requiring chemical interactions that involve many thousands of atoms, indicating a new ability to model complex chemical processes.
