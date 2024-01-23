---
layout: highlight

theme: white
permalink: 'science/highlights/chang'

title: 'High-Fidelity Gyrokinetic Simulation of Tokamak and ITER Edge Physics'
pi: 'Choong-Seock Chang, Princeton Plasma Physics Laboratory'
award: 'INCITE, Aurora Early Science Program'
system: 'Theta'
field: 'Physics'
sdl: 's,l'

image: 'chang.png' 
image-caption: 'Frequency-wavenumber spectrum of nonlinear edge turbulence just before L-H bifurcation. The pedestal profile is still evolving, and the turbulence has not reached its peak.'
image-credit: 'C. S. Chang, Princeton Plasma Physics Laboratory'

publications:
  - authors: 'Hager, R., S. Ku, A. Y. Sharma, C. S. Chang, R. M. Churchill, and A. Scheinberg'
    title: 'Electromagnetic Total-f Algorithm for Gyrokinetic Particle-in-Cell Simulations of Boundary Plasma in XGC'
    source: 'Physics of Plasmas'
    date: 'November 2022'
    publisher: 'AIP Publishing'
    url: 'https://doi.org/10.1063/5.0097855'
---




{% include txt-intro.html 
    blurb = "This multi-year INCITE and ESP project seeks to advance our understanding of the edge plasma physics in fusion reactors, with a focus on ITER, and to assemble a burning plasma experiment that can demonstrate the scientific and technological feasibility of fusion."
%}



# Challenge

The INCITE team is performing studies on two high-priority challenges: (1) quantifying the narrowness of the heat-flux width on the ITER divertor material plates in the high-confinement mode (H-mode) operation during tenfold energy gain operation; and (2) understanding the basic physics behind the low-to-high mode L-H transition and pedestal formation at the edge, which is necessary to achieve a tenfold energy gain in ITER.



# Approach

The researchers are using the 5D gyrokinetic particle-in-cell code XGC on DOE leadership computing resources to address some of the most difficult plasma physics questions facing ITER. The team used this extreme-scale modeling code to solve kinetic equations for the tokamak edge by modeling plasma with a large number of particles. Predictions from XGC for the low-to-high mode transition revealed that a heavier-mass plasma can allow an easier transition to the high mode operation that is necessary for ITER to achieve its goal, in which a strongly sheared plasma flow suppresses edge turbulence. To be more specific, the L-H transition could occur more easily in a heavier plasma, due to a stronger mean plasma-flow effect, without the necessity for a significant turbulence energy transfer to the plasma-flow. A new electromagnetic solver algorithm has been developed for higher fidelity studies of the ITER edge plasma. 



# Results

The team’s new electromagnetic solver results were described in a paper published in *Physics of Plasma*. A simplified delta-f mixed-variable/pull-back electromagnetic simulation algorithm implemented in XGC for core plasma simulations was generalized to a total-f electromagnetic algorithm able to include—for the first time—the boundary plasma in diverted magnetic geometry with neutral particle recycling, turbulence, and neoclassical physics. It is confirmed that electromagnetic simulation is necessary for a higher-fidelity understanding of the tokamak edge physics in the presence of the divertor and magnetic separatrix.



# Impact

Establishing an accurate predictive formula for the exhaust heat-load width and low-to-high mode transition of future doughnut-shaped tokamak fusion reactors can help enable researchers to progress faster toward the goal of 0.5 GW of fusion power production from 50 MW of input power in ITER. More accurate understanding and prediction can also help inform more reliable designs for future fusion reactors, which currently suffer from the limitation imposed by exhaust heat-load width on the divertor plates and the required L-H transition power.
