---
layout: highlight

theme: white
permalink: 'science/highlights/liu'

title: 'BraggNN: Fast X-ray Bragg Peak Analysis Using Deep Learning'
pi: 'Zhengchun Liu, Argonne National Laboratory'
award: "Director's Discretionary"
systems: 'ThetaGPU, Cerebras'
field: 'Materials Science'
sdl: 'd,l'

image: 'liu.png' 
image-caption: 'Comparison of BraggNN, pseudo-Voigt FF-HEDM, and NF-HEDM. Grain positions from NF-HEDM (black squares), pseudo-Voigt FF-HEDM (red circles) and BraggNN FF-HEDM (blue triangles) overlaid on the NF-HEDM confidence map.'
image-credit: 'Antonino Miceli, Argonne National Laboratory'

publications:
  - authors: 'Liu, Z., H. Sharma, J.-S. Park, P. Kenesei, A. Miceli, J. Almer, R. Kettimuthu, and I. Foster'
    title: 'BraggNN: Fast X-ray Bragg Peak Analysis Using Deep Learning'
    source: 'IUCrJ'
    date: 'December 2021'
    publisher: 'International Union of Crystallography'
    url: 'https://doi.org/10.1107/S2052252521011258'
---



{% include txt-intro.html 
    blurb = "A group of researchers from Argonne National Laboratory is harnessing AI to perform the challenging task of analyzing data from high-energy x-ray diffraction experiments. With a new neural network-based method called BraggNN, the Argonne team can more rapidly and precisely identify Bragg peaks—data points that indicate positions and orientations of tiny individual crystals—in a fraction of the time they used to."
%}



# Challenge

In recent years, a technique called high-energy diffraction microscopy (HEDM) has become an important tool for accurately characterizing complex materials with high resolution. Although HEDM has proven to be a great improvement over conventional techniques, it can also be expensive and time-consuming. It involves the collection of enormous datasets, analysis of millions of Bragg diffraction peaks and reconstruction of the sample using those peaks. The impending upgrade of Argonne’s Advanced Photon Source (APS) is expected to vastly improve the speed of HEDM data acquisition to a minute or less. But the computing time to complete analysis Bragg peaks can extend to hours or weeks, even with the largest supercomputers. Not only do such delays slow research, but they also prevent the use of HEDM information to steer experiments.



# Approach

To address these challenges, the Argonne team developed BraggNN, a novel deep learning-based method that can accurately characterize Bragg diffraction peaks in HEDM images much more rapidly than conventional methods. The BraggNN network architecture comprises a series of convolutional neural network layers acting as feature extractors, followed by a series of fully connected layers that generate a regression prediction. The team used the ALCF’s ThetaGPU system and Cerebras AI accelerator to train the BraggNN model with a collection of data containing diffraction peaks.



# Results

To evaluate the performance of BraggNN, the researchers compared the results with the reconstructed position of grains in addition to diffraction peak positions. When applied to a real experimental dataset, they found the grain positions using BraggNN resulted in errors being 15 percent smaller than those calculated using convention pseudo-Voigt fitting. Recent advances in deep learning method implementations and special-purpose model inference accelerators allow BraggNN to deliver significant performance improvements relative to the traditional method, running, for example, more than 200 times faster on a consumer-class GPU card with out-of-the-box software.



# Impact

The team has developed the first machine learned-based method for precisely characterizing Bragg diffraction peaks in HEDM images. Capable of precisely identifying Bragg peaks more quickly than conventional methods, the BraggNN method also stands to benefit high-resolution, high-throughput, and latency-sensitive applications, including real-time analysis and experiment steering.
