---
layout: highlight

theme: white
permalink: 'science/highlights/sankaranarayanan'

title: 'Metastable Phase Diagrams for Materials'
pi: 'Subramanian Sankaranarayanan, Argonne National Laboratory'
award: "Director's Discretionary"
system: 'Theta'
field: 'Materials Science'
sdl: 's,l'

image: 'sankaranarayanan.png' 
image-caption: 'The final product of the machine learning algorithm: metastable phase diagrams for carbon. The colored regions indicate conditions at which carbon exists in certain metastable states (with similarly colored structures) that may yield useful material properties.'
image-credit: 'Argonne National Laboratory'

publications:
  - authors: 'Srinivasan, S., R. Batra, D. Luo, T. Loeffler, S. Manna, H. Chan, L. Yang, W. Yang, J. Wen, P. Darancet, and S. K.R.S. Sankaranarayanan'
    title: 'Machine Learning the Metastable Phase Diagram of Covalently Bonded Carbon'
    source: 'Nature Communications'
    date: 'June 2022'
    publisher: 'Springer Nature'
    url: 'https://doi.org/10.1038/s41467-022-30820-8'
---



{% include txt-intro.html 
    blurb = "Phase diagrams are an invaluable tool for materials synthesis, providing researchers with information on the phases of a material at any given thermodynamic condition (such as pressure, temperature, chemical composition). To extend their utility to a promising but mysterious class of materials, researchers from Argonne National Laboratory are using ALCF computing resources and machine learning to develop an automated workflow to construct phase diagrams for metastable materials."
%}



# Challenge

Conventional phase diagrams represent a reduced set of phases observed at distinct thermodynamic equilibria. In contrast, materials during their synthesis, operation, or processing may not reach their thermodynamic equilibrium state but instead remain trapped in a local (metastable) free energy minimum that may exhibit desirable properties for various applications. Mapping these metastable phases and their thermodynamic behavior is therefore highly desirable, but it is a non-trivial and data-intensive task that is currently lacking due to the vast configurational landscape.



# Approach

Leveraging the ALCF’s Theta supercomputer, Argonne researchers are creating an automated workflow that integrates first-principles physics and atomistic simulations with machine learning and high-performance computing to allow rapid exploration of the metastable phases of any given elemental composition. Their framework allows for the curation of metastable structures from published literature and databases, and concurrently enables automatic discovery, identification, and exploration of the metastable phases of a material and learns their equations of state through a deep neural network. 



# Results

Using carbon as a prototypical system, the team demonstrated automated metastable phase diagram construction to map hundreds of metastable states ranging from near equilibrium to far-from-equilibrium (400 meV/atom). The researchers incorporated the free energy calculations into a neural-network-based learning of the equations of state that allows for efficient construction of metastable phase diagrams. They used the phase diagrams to identify domains of relative stability and synthesizability of metastable materials. The team validated their metastable phase predictions with data from high-temperature, high-pressure experiments using a diamond anvil cell on graphite sample coupled with high-resolution transmission electron microscopy. Their approach is quite general, making it possible to extend the phase diagram construction to multi-component alloy systems. Their findings were detailed in a paper published in *Nature Communications*.



# Impact

The team’s automated framework for constructing metastable phase diagrams lays the groundwork for computer-aided discovery and design of synthesizable metastable materials, which could help advance a range of applications including semiconductors, catalysts, and solar cells.
