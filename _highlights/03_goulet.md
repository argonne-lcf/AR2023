---
layout: highlight

theme: white
permalink: 'science/highlights/goulet'

title: 'Extreme-Scale Simlations for Advanced Seismic Ground Motion and Hazard Modeling'
pi: 'Christine Goulet, University of Southern California'
award: 'INCITE'
system: 'Theta'
field: 'Earth Science'
sdl: 's'

image: 'goulet.png' 
image-caption: 'Simulation model setup (a) showing observational and model fault details with arrows indicating orientations of principal stresses, (b) fault-plane model and epicenter (star), and (c) rock properties.'
image-credit: 'Christine Goulet and Yongfei Wang, University of Southern California'

publications:
  - authors: 'Wang, Y., and C. A. Goulet'
    title: 'Validation of Fault Displacements from Dynamic Rupture Simulations against the Observations from the 1992 Landers Earthquake'
    source: 'Bulletin of the Seismological Society of America'
    date: 'August 2021'
    publisher: 'SSA'
    url: 'https://doi.org/10.1785/0120210082'
  - authors: "O'Reilly, O., T.-Y. Yeh, K. B. Olsen, Z. Hu, A. Breuer, D. Roten, and C. A. Goulet"
    title: 'A High‐Order Finite‐Difference Method on Staggered Curvilinear Grids for Seismic Wave Propagation Applications with Topography'
    source: 'Bulletin of the Seismological Society of America'
    date: 'September 2021'
    publisher: 'SSA'
    url: 'https://doi.org/10.1785/0120210096'
---



{% include txt-intro.html 
    blurb = "Ground motions and fault displacements from earthquakes threaten infrastructure. Computer-based simulations can provide insight on those earthquake hazards to help develop mitigation strategies. Led by researchers from the Southern California Earthquake Center, this INCITE project seeks to improve earthquake-modeling capabilities by integrating physics-based models into research software, validating ground motion simulation and hazard products, while improving code performance."
%}



# Challenge

Civil infrastructure is at risk of damage due to earthquake ground motions and fault displacement. In areas close to the fault (within 10-20 km), empirical models for both hazards are poorly constrained due to the paucity of data. This INCITE project is using DOE supercomputing resources to simulate ground motion and displacement using dynamic rupture codes that include complex physics to produce high-frequency simulations. The results are cross-validated with existing empirical data and used to extrapolate earthquake effects where no data exist. The researchers are looking to improve the accuracy of rupture simulations by adding features such as complex fault geometry and nonlinearity in the geological models.  



# Approach

The team’s work at the ALCF is largely driven by two open source codes, Waveqlab3D and SORD, which are used to simulate earthquake rupture dynamics and seismic wave propagation. The researchers are using Theta to look at fault displacement from dynamic rupture simulations for earthquakes with a magnitude greater than seven with different initial conditions. They are also generating broadband dynamic rupture sources with off-fault plasticity and geometrical fault complexity. With this work, the team is creating a database of slip-strike earthquake mechanisms, comparing broadband ground motions with empirical trends predicted by empirical ground motion models. They also are modeling ruptures across dipping faults, which have unique geometrical complexities. ALCF staff helped with scheduling jobs, and compiling and running SORD with Cray MPI.



# Results

In one study, the INCITE team used Theta to simulate the 1992 Landers, CA earthquake by defining a preferred model that reproduced first-order fault displacement metrics including the on-fault partition of the total displacement. This has demonstrated that all the physics important to modeling the earthquake were properly captured, showing that dynamic rupture modeling can be used to assess fault-displacement hazard on a larger scale. The model reproduced intermediate and large-scale features including displacement, off-fault deformation, fault zone width and peak displacement.



# Impact

Physics-based dynamic rupture models and simulations inform earthquake hazard analyses and assessments, which help prepare for earthquakes and enable mitigation strategies that can save lives and alleviate the societal and economic damage caused by earthquakes.
