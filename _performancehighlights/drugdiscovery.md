---
layout: highlight

theme: dark
permalink: 'features/aurora-performance-highlights/drugdiscovery'

title: 'Accelerating Drug Design and Discovery'
pi: 'Archit Vasan, Argonne National Laboratory'
award: 'Early Science Program'
systems: '-'

image: 'drugdiscovery.png' 

---

{% include txt-intro.html 
    blurb = "High-throughput screening of extensive compound datasets so as to identify advantageous properties—such as the ability to interact with relevant biomolecules (including proteins)—represents a promising direction in drug discovery for the treatment of diseases like cancer as well as for response to epidemics like SARS-CoV-2. However, traditional structural approaches for assessing binding affinity, such as free energy methods or molecular docking, pose significant computational bottlenecks when dealing with quantities of data of this magnitude. To address this, researchers have developed a docking surrogate called the SMILES transformer (ST), which learns molecular features from the SMILES (Simplified Molecular Input Line Entry System) representation of compounds and approximates their binding affinity."
%}



# Challenge

SMILES data are first tokenized using a well-established SMILES-pair tokenizer and then fed into a transformer model to generate vector embeddings for each molecule, effectively capturing the essential information. These extracted embeddings are subsequently fed into a regression model to predict the binding affinity.

Leveraging ALCF leadership-computing resources, the researchers devised a workflow to scale model training and inference across multiple supercomputer nodes. To evaluate the performance and accuracy of the workflow, the team conducted experiments using molecular docking binding affinity data on multiple receptors, comparing ST with another state-of-the-art docking surrogate.




# Performance Results
Drug screening inference scaled to 128 nodes on Aurora, screening approximately 11 billion drug molecules per hour. Screening inference was then scaled to 256 nodes on Aurora, screening approximately 22 billion drug molecules per hour. These results indicate that Aurora enabled strong performance improvements over other systems: the workflow facilitated screening some 3 billion compounds per hour when scaled to 48 nodes on Polaris. Assuming linear scaling, researchers could expect about a trillion compounds screened per hour if using all compute resources in Aurora.

ST showed comparable accuracy to state-of-the-art surrogate models, with r-squared values between 70 and 90 percent on multiple test protein receptors, affirming the capability of ST to learn molecular information directly from language-based data. One significant advantage of the ST approach is its notably faster tokenization preprocessing compared to alternative preprocessing methods such as generating molecular descriptors. Furthermore, ST predictions emphasize several molecular motifs that have previously been confirmed to interact with residues in their target binding pockets.

{% include media-img.html
   source= "Chart_DrugDesign_.png"
   caption= "Screening ~40-60B of the most synthesizable compounds made possible using the system capabilities and software stack on Aurora. * Simplified Molecular Input Line Entry System (SMILES) - Representation for Molecules."
%}

# Impact
The team’s approach presents an efficient means for screening otherwise cumbersomely extensive compound databases for molecular properties that could prove useful for targeting cancer and other diseases. Aurora system capabilities will make possible screening 40 to 60 billion candidate compounds for potential synthesis. A key future direction for the workflow involves integrating de-novo drug design, enabling the researchers to scale their efforts to explore the limits of synthesizable compounds within chemical space.

