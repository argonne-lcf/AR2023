---
layout: highlight

theme: white
permalink: 'science/highlights/foster'

title: 'Next-Generation Nonwoven Materials Manufacturing'
pi: 'Ian Foster, Argonne National Laboratory'
award: "Director's Discretionary"
system: 'Theta'
field: 'Engineering'
sdl: 's,l'

image: 'foster.png' 
image-caption: 'Computational fluid dynamics simulation of the melt-blowing process as modeled at Argonne.'
image-credit: 'Argonne National Laboratory'
---



{% include txt-intro.html 
	blurb = "Melt-blown nonwoven materials form the basis of a range of filters, fabrics and insulation that includes critical items, such as N95 masks. Worldwide, manufacturers produce more than 300,000 tons of melt-blown nonwoven materials every year. To minimize the energy footprint of the process, researchers from 3M and Argonne National Laboratory are leveraging ALCF resources to model and optimize the production of melt-blown nonwoven materials."
%}



# Challenge

Combining simulations, data analysis, and machine learning (ML) to reduce the energy consumed in the melt-blowing production process—without compromising material quality—the researchers aim to reduce energy expenditures by 20 percent.



# Approach

The initial model for the melt-blowing process was developed through a series of simulation runs performed on the ALCF’s Theta supercomputer with the computational fluid dynamics (CFD) software OpenFOAM. The researchers then scaled up the code using the CONVERGE CFD application.

The optimization approach combines ML for simulation parameter selection with high-fidelity fluid dynamics simulations for modeling the process and nozzle geometry.

For the models to closely match the company’s melt-blowing process, 3M first performs experiments to establish a process map for a particular production setup. The process map must identify which combinations of processing choices yield acceptable non-woven materials. This stage is crucial for generalizing the process maps to other production setups and source polymers.

Once the simulations reproduce a 3M experimental process map with sufficient accuracy, they can be used to optimize processing choices for a given polymer. The researchers will then employ ML techniques to determine preferred processing parameters by simulating different configurations of settings, like air pressure and temperature, and various geometric parameters, like the angle of the nozzle or the diameter of the nozzle opening. Based on the simulations already generated, the ML algorithm suggests successive simulations with parameter settings iteratively refined to minimize energy consumption.



# Results

While ML methods have thus far been used to refine and select successive experiments, the researchers intend to investigate the use of recurrent and physics-informed neural networks so as to predict fluid flow patterns, from which key metrics can be determined. 

The researchers are still working to identify and validate optimal process conditions in 3M facilities, but have successfully established a quantitative metric for improved parameter optimization. After simulation and validation are complete, the team will move on to industrial implementation.



# Impact

Reduction of energy expenditures by 20 percent in a market space as large as that of melt-blown nonwoven materials stands to carry global environmental and economic effects, including significantly smaller production costs and externalities.
