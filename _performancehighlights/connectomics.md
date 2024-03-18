![image](https://github.com/argonne-lcf/AR2023/assets/110477819/5e7a7285-4f09-4ade-85cc-9615d6cff097)---
layout: highlight

theme: dark
permalink: 'features/aurora/connectomics'

title: 'Connectomics Machine Learning with Flood-Filling Networks'
pi: 'Nicola Ferrier, Argonne National Laboraotory'
award: 'Early Science Program'
systems: '-'
sdl: 'd,l'

image: '-' 
image-caption: '-'
image-credit: '-'

---

{% include txt-intro.html 
    blurb = "Using the most advanced imaging techniques available, researchers aim to create a full mapping of neural connections in brains, known as a connectome, to reveal fundamental principles of organization and facilitate advances in neuroscience and neural computation by processing massive electron microscopy data of brain tissue. Researchers at the DOE’s Argonne National Laboratory are working to develop a brain connectome — an accurate map that lays out every connection between every neuron and the precise location of the associated dendrites, axons and synapses that help form the communications or signaling pathways of a brain. Only the computing power on the scale provided by Aurora will meet the near-term challenges of brain mapping."
%}



# Challenge

A brain connectome lays out every connection between every neuron and the precise location of the associated dendrites, axons and synapses that help form the communications or signaling pathways of a brain. These wiring diagrams and cellular maps of circuits suggest novel hypotheses about how neurons generate behavior and provide fundamental explanations for specific neural computations that cannot be inferred in any other way. However, until recently, exhaustive anatomical brain reconstructions were limited to the tiniest volumes and to the few labs capable of the extraordinary investment of human effort required. Recent technologies are dramatically improving the size, speed and integrity of brain imaging but require substantial resources in both hardware and software. Existing large-scale brain mapping efforts are producing data on standard laboratory animals (mice, flies, and worms) limiting neuroscientists’ ability to explore nature’s range of choices for brain function. Comparative studies across diverse phylogeny will require numerous mappings, across species, during development, and/or, across genetic variations, with each mapping requiring petabytes or terabytes of data to be imaged, analyzed, and stored. To realize these studies, we need an exascale computational pipeline to analyze nanometer-resolution serial-section electron microscopy (EM) data and generate large scale mappings for multiple specimens. Flood Filling Network (FFN) performs segmentation of EM brain scans to extract structures (e.g., blood vessels and neurons), which are used to form complete maps of neural connections in animal brains.

An exascale pipeline requires scalable computational tools for analysis of EM data, including machine vision and machine learning, for stitching, alignment, segmentation and tracing of neuronal structures in the extremely large 3D data sets. Real-time feedback from analysis of the brain datasets would increase efficiency of data collection and may improve quality. Current attempts at reconstructing brain wiring have already led to valuable insights, and integration of exascale computing to these efforts will advance significantly programs established by the NIH, NSF, and other federal agencies.



# Performance Results
Connectomics has done training and inference at scale on Aurora.  One of the largest brain connectomics reconstructions was carried out on 512 nodes of Aurora and showed more a more than twofold performance gain over what was achieved using the ALCF’s 44-petaplop Polaris system at similar scale.

# Impact

This project is working to establish and refine the computational methods needed for fast routine brain mapping, building an end-to-end processing pipeline for extracting large scale connectomic information from nanometer-resolution serial-section EM image data sets of brain samples, providing huge benefits to the brain science and neuroimaging communities. The realization of an exascale data and computational pipeline for neuroscience could help revolutionize our understanding of brain function and pathology. Connectomics can help elucidate how even the smallest neurological changes contribute to diseases and disorders such as Alzheimer’s and autism, perhaps thereby providing a path to improved treatments.

The work done to prepare this project for exascale will also serve as a benefit to other exascale system users; with the electron microscopy algorithms under development, for example, promising broad application to x-ray data, especially with the upcoming upgrade to Argonne’s Advanced Photon Source (APS), a DOE Office of Science User Facility.
