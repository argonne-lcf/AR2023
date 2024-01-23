---
layout: highlight

theme: white
permalink: 'science/highlights/jiang'

title: 'Microscopic Insight into Transport Properties of Li-Battery Electrolytes'
pi: 'Wei Jiang, Argonne National Laboratory'
award: 'ALCC'
system: 'Theta'
field: 'Chemistry'
sdl: 's'

image: 'jiang.png' 
image-caption: 'Simulated cluster of water (red) and lithium ions (green) at electrode surfaces under various water concentrations. Battery performance is retained when water molecules remain isolated.'
image-credit: 'Wei Jiang, Argonne National Laboratory'

publications:
  - authors: 'Liu, Q., W. Jiang, Z. Yang, and Z. Zhang'
    title: 'An Environmentally Benign Electrolyte for High Energy Lithium Battery Materials'
    source: 'ACS Applied Materials and Interfaces '
    date: 'November 2021'
    publisher: 'ACS Publications'
    url: 'https://pubs.acs.org/doi/10.1021/acsami.1c19124'
---



{% include txt-intro.html 
    blurb = "Global demand for high energy-density batteries is increasing. The development of low-cost, safe, rechargeable batteries with high voltage, capacity, and rate capability is important for several applications, including electric vehicles. To aid in the discovery of novel battery materials, researchers from Argonne National Laboratory are using ALCF computing resources to enable the design of improved electrolytes for high-voltage lithium-ion batteries."
%}



# Challenge

One of the challenges in developing advanced batteries is the need for new insights into how to improve electrolyte behavior under increasingly extreme performance demands. However, at high potentials or high voltages, the state-of-the-art organic carbonate-based electrolytes tend to be oxidatively decomposed at the cathode surface causing gassing issues, low Coulombic efficiency, transition metal ion dissolution, and rapid capacity fade of the full cell. Moreover, these conventional electrolytes are extremely flammable due to their high vapor pressure and low flashpoint, which leads to potential safety issues especially when applied in electric vehicles. To address these issues, the Argonne team is exploring ionic liquids as a potential alternative due to their intrinsic physical properties, such as low vapor pressure, non-flammability, wide electrochemical window, and high ionic conductivity.



# Approach

This ALCC project is employing a joint experimental and computational approach that involves running the NAMD molecular dynamics code on Theta to explore the nanostructural organization at electrolyte-electrode interfaces, and to shed light on the transport properties and desolvation/solvation kinetics of charge carriers. The team is leveraging molecular dynamics methodologies, such as Hamiltonian Annealing and sampling enhanced free energy calculations, to provide insights into the underlying chemical mechanisms that give rise to favorable battery performance. 


# Results

In a study published in *ACS Applied Materials and Interfaces*, the team detailed the development of a new battery electrolyte that can hold 1,000 times more water than conventional electrolytes. Their simulations revealed that the material, composed of a lithium salt and an ionic liquid, could separate and bind up water, sequestering individual water molecules. They found the key is that the water molecules do not gather into “puddles” and thereby lose reactivity. The new electrolyte eliminates the critical moisture controls required for a state-of-the-art carbonate electrolyte, electrode, separator, and cell assembly, which would significantly reduce the cost of manufacturing of such batteries.



# Impact

As part of their work, the researchers identified a potential pathway for battery manufacturers to incorporate water in the fabrication process, allowing for lower cost, more environmentally friendly batteries. Ultimately, the team is working to develop a computer-aided electrolyte design protocol to enhance future high-throughput prediction and screening studies aimed at discovering new battery materials.
