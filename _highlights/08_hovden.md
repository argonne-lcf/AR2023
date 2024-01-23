---
layout: highlight

theme: white
permalink: 'science/highlights/hovden'

title: 'Dynamic Compressed Sensing for Real-Time Tomographic Reconstruction'
pi: 'Robert Hovden, University of Michigan'
award: 'ALCF Data Science Program'
system: 'Theta'
field: 'Materials Science'
sdl: 's,d'

image: 'hovden.png' 
image-caption: 'a) As the tomographic experiment progresses, projections are collected across an angular range. Measured projections are fed into the dynamic CS algorithm for 3D reconstruction. b) As the amount of data increases, the root mean square error (RMSE) decreases. c) 2D slices of the 3D reconstruction at various time stamps.'
image-credit: 'Jonathan Schwartz, University of Michigan'

publications:
  - authors: 'Schwartz, J., C. Harris, J. Pietryga, H. Zheng, P. Kumar, A. Visheratina, N. A. Kotov, B. Major, P. Avery, P. Ercius, U. Ayachit, B. Geveci, D. A. Muller, A. Genova, Y. Jiang, M. Hanwell, and R. Hovden'
    title: 'Real-Time 3D Analysis during Electron Tomography Using Tomviz'
    source: 'Nature Communications'
    date: 'August 2022'
    publisher: 'Springer Nature'
    url: 'https://www.nature.com/articles/s41467-022-32046-0'
  - authors: 'Schwartz, J., Z. W. Di, Y. Jiang, A. J. Fielitz, D.-H. Ha, S. D. Perera, I. El Baggari, R. D. Robinson, J. A. Fessler, C. Ophus, S. Rozeveld, and R. Hovden'
    title: 'Imaging Atomic-Scale Chemistry from Fused Multi-Modal Electron Microscopy'
    source: 'npj Computational Materials'
    date: 'January 2022'
    publisher: 'Springer Nature'
    url: 'https://www.nature.com/articles/s41524-021-00692-5'
---



{% include txt-intro.html 
    blurb = "Electron and x-ray tomography allow researchers to perform 3D characterization of materials at the nano- and mesoscale, generating data that is critical to the development of nanomaterials for a wide range of applications, including solar cells and semiconductor devices. With an ALCF Data Science Program (ADSP) award, a University of Michigan-led research team is leveraging recent advancements in tomographic reconstruction algorithms, such as compressed sensing methods, to enhance and accelerate materials characterization research."
%}



# Challenge

Compressed sensing algorithms provide higher quality reconstructions, but they require substantially more computation time to complete, causing the rapidly expanding field of tomography to become critically bottlenecked by low throughput. To address these challenges and achieve real-time tomographic reconstruction using compressed sensing algorithms, the ADSP team has developed a dynamic framework that performs *in situ* reconstruction simultaneously with data collection.



# Approach

With access to DOE supercomputing resources, the researchers are conducting comprehensive simulations for real-time electron tomography and developing reconstruction methods for through-focal tomography. The team is experimentally demonstrating their reconstruction workflow and methods on commercial scanning transmission electron microscopes and the ptychographic tomography instruments at Argonne’s Advanced Photon Source.



# Results

A paper published in *npj Computational Materials* introduced fused multi-modal spectroscopy, a technique offering high signal-to-noise ratio (SNR) recovery of nanomaterial chemistry by linking correlated information encoded within detector signals. The team’s approach substantially improves SNRs for chemical maps by as much as 500 percent, reduces electron doses by an order of magnitude, and enables accurate measurement of local stoichiometry.

A paper published in *Nature Communications* demonstrated real-time tomography with dynamic 3D tomographic visualization to enable rapid interpretation of specimen structure immediately as data are collected with an electron microscope. The authors showed volumetric interpretation can begin in less than 10 minutes and that a high-quality tomogram is available within 30 minutes. Real-time tomography is integrated into tomviz, an open-source and cross-platform 3D data analysis tool that contains intuitive graphical user interfaces (GUI), to enable any scientist to characterize biological and material structure in 3D.



# Impact

The team’s approach will help advance materials characterization research by enabling real-time analysis of 3D specimens while an experiment progresses. By integrating their framework with an open-source 3D visualization and tomography software package, the team’s techniques will be accessible to a wide range of researchers and enable new material characterizations across academia and industry
