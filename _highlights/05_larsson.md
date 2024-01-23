---
layout: highlight

theme: white
permalink: 'science/highlights/larsson'

title: 'High-Speed Turbulence with Shocks over Non-Adiabatic and Flexible Walls'
pi: 'Johan Larsson, University of Maryland'
award: 'INCITE'
system: 'Theta'
field: 'Engineering'
sdl: 's'

image: 'larsson.png' 
image-caption: 'Different aspects of shock-turbulence interactions. Background: shock-induced mixing shadowed by the velocity marking the shock. Foreground: oblique shock impinging on a turbulent boundary layer over a flexible panel.'
image-credit: 'Ivan Bermejo-Moreno, University of Southern California'

publications:
  - authors: 'Di Renzo, M., N. Oberoi, J. Larsson, and S. Pirozzoli'
    title: 'Crossflow Effects on Shock Wave/Turbulent Boundary Layer Interactions'
    source: 'Theoretical and Computational Fluid Dynamics'
    date: 'June 2021'
    publisher: 'Springer Nature'
    url: 'https://doi.org/10.1007/s00162-021-00574-y'
  - authors: 'Larsson, J., V. Kumar, N. Oberoi, M. Di Renzo, and S. Pirozzoli'
    title: 'Large-Eddy Simulations of Idealized Shock/Boundary-Layer Interactions with Crossflow'
    source: 'AIAA Journal'
    date: 'February 2022'
    publisher: 'AIAA'
    url: 'https://doi.org/10.2514/1.J061060'
---



{% include txt-intro.html 
    blurb = "High-speed air flows, such as those experienced by supersonic aircraft, create a thin boundary layer along a solid surface. If the boundary layer is hit by a shock wave, as forms when a plane approaches supersonic speeds and pushes on the surrounding air, the flow may separate from the surface. If the flow separates from the surface, the engine’s performance degrades significantly. A team led by researchers from the University of Maryland used ALCF supercomputing resources to study supersonic turbulent boundary layers and their interaction with shock waves."
%}



# Challenge

With the aim of elucidating how shock/boundary-layer interactions (SBLI) are affected by crossflow (that is, flow along the shock and in a direction parallel to the wing span), researchers performed direct numerical simulations of skewed SBLI with crossflow so as to approximate the off-design operating conditions that can ultimately cause engine performance degradation and flameout. 



# Approach

Leveraging the ALCF’s Theta supercomputer, the team carried out SBLI simulations with the code Hybrid. Hybrid is a solver for the compressible Navier-Stokes equations that govern much of fluid dynamics. 



# Results

The team published their results in *Theoretical and Computational Fluid Dynamics* and the *AIAA Journal*. Their papers demonstrate that the size of a turbulent flow’s separation bubble grows almost 50 percent larger in the presence of crossflow than in cases without crossflow.



# Impact

The ultimate goal of the team’s research is to develop a predictive theory for SBLI physics and apply it so as to devise improved modeling techniques for surfaces in large-eddy simulations (LES). LES, as mathematical models for turbulence, are used in a broad range of applications throughout different fields of engineering.

The team expects their findings to help construct improved models that better predict the size of separation bubbles and account for the effect of crossflow for a range of engineering applications. This work is also significant in how it differs from other research in the fields. Historically, most studies of turbulent boundary layers focus on a specific canonical case: the case of incompressible flow, with constant density and viscosity, passing over rigid walls. This research, in contrast, examines the case of compressible flows non-uniform density and viscosity across their boundary layers.
