---
layout: highlight

theme: white
permalink: 'features/aurora/xgc'

title: 'Identifying Reaction Coordinates for Complex Protein Dynamics'
pi: 'Ao Ma, University of Illinois Chicago'
award: 'Director’s Discretionary'
systems: 'Theta'
sdl: 's'

image: 'ma.png' 
image-caption: 'Representative open structures from accelerated trajectories along the identified six reaction coordinates. The reference semi-open structure is colored white and atoms are colored green, red, and blue according to its weight in the reaction coordinates.'
image-credit: 'Ao Ma, University of Illinois Chicago'

---

{% include txt-intro.html 
    blurb = "Proteins play an essential role in nearly all biological processes. By investigating proteins and their functions, scientists are providing insights to drive drug development, further our understanding of disease mechanisms, and advance many other areas of biomedical research. With help from ALCF supercomputers, a team from University of Illinois Chicago (UIC) has made an important breakthrough in understanding how proteins function."
%}



# Challenge

Specializing in edge physics and realistic geometry, XGC is capable of solving boundary multiscale plasma problems across the magnetic separatrix (that is, the boundary between the magnetically confined and unconfined plasmas) and in contact with material wall called divertor, using first-principles-based kinetic equations.

To prepare for the next generation of high-performance computing, the code is being re-implemented for exascale using a performance-portable approach. Running at exascale will yield unique computational capabilities, some of which carry the potential for transformational impacts
on fusion science: exascale expansion will make it possible to study, for instance, a larger and more realistic range
of dimensionless plasma parameters than has ever been achieved, along with the energy-angle distribution of plasma particles impinging upon the material wall and the full spectrum of kinetic micro-instabilities that control the quality of energy confinement in a toroidal plasma. Further, exascale will enable physics modeling that incorporates multiple-charge tungsten ion species — impurities discharged from the tokamak vessel walls that impact edge-plasma behavior and fusion performance in the core-plasma through migration across the magnetic separatrix. Toward this end, XGC will support a wide array of additional features and modes, including delta-f and full-f, electrostatic and electromagnetic, axisymmetric, neutral particles with atomic cross-sections, atomic number transitions among different impurity states, and coupling physics in constant development.





# Performance Results

Optimization for exascale has required both GPU offloading and algorithmic flexibility. Performance on the Aurora testbed, Sunspot, has yielded scaling performance comparable to that of GPU systems such as Polaris. Single-GPU performance on Aurora shows improvements by as much as 46 percent.



# Impact

The resulting exascale application will be unique in its computational capabilities and will have potentially transformational impact in fusion science, for example, by studying a much larger and more realistic range of dimensionless plasma parameters than ever before, by providing the energy-angle distribution of plasmas hitting the material wall, and by assessing the rich spectrum of kinetic micro-instabilities that control the quality of energy confinement in a toroidal plasma.
