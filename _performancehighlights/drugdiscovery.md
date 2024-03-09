---
layout: highlight

theme: dark
permalink: 'features/aurora/drugdiscovery'

title: '-'
pi: '-'
award: '-'
systems: '-'
sdl: '-'

image: '-' 
image-caption: '-'
image-credit: '-'

---

{% include txt-intro.html 
    blurb = "High-throughput screening of extensive compound datasets so as to identify advantageous properties, such as the ability to interact with relevant biomolecules (including proteins), represents a promising direction in drug discovery for diseases like cancer as well as response to epidemics like SARS-CoV-2. However, traditional structural approaches for assessing binding affinity, such as free energy methods or molecular docking, pose significant computational bottlenecks when dealing with quantities of data of this magnitude. To address this, researchers have developed a docking surrogate called the SMILES transformer (ST), which learns molecular features from the SMILES (Simplified Molecular Input Line Entry System) representation of compounds and approximates their binding affinity."
%}



# Challenge

SMILES data are first tokenized using a well-established SMILES-pair tokenizer and then fed into a transformer model to generate vector embeddings for each molecule, effectively capturing the essential information. These extracted embeddings are subsequently fed into a regression model to predict the binding affinity.

Leveraging ALCF leadership-computing resources, the researchers devised a workflow to scale model training and inference across multiple supercomputer nodes. To evaluate the performance and accuracy of the workflow, the team conducted experiments using molecular docking binding affinity data on multiple receptors, comparing ST with another state-of-the-art docking surrogate. Both surrogates yielded measurements that affirmed the capability of ST to learn molecular features directly from language-based data. Furthermore, one significant advantage of the ST approach is its notably faster tokenization preprocessing compared to the alternative method, which requires generating molecular descriptors using Mordred.




# Performance Results
Drug screening inference scaled to 128 nodes on Aurora, screening approximately 11 billion drug molecules per hour. Screening inference was then scaled to 256 nodes on Aurora, screening approximately 22 billion drug molecules per hour. These results demonstrate a tremendous speedup over other systems: the workflow facilitated screening some 3 billion compounds per hour when scaled to 48 nodes on Polaris.



# Impact
The team’s approach presents an efficient means to screen extensive compound databases for potential molecular properties that could serve as lead compounds targeting cancer. An important future direction for the workflow involves integrating de-novo drug design, enabling the researchers to scale their efforts to explore the limits of synthesizable compounds within chemical space.

