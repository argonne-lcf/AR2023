---
layout: page

title: ALCF Leadership

theme: white
permalink: year-in-review/year-in-review
---



{% include media-img.html
   source= "allcock-kumaran.png"
   caption= "Left: Bill Allcock, right: Kalyan Kumaran"
%}

# Bill Allcock, ALCF Director of Operations

The biggest news of the year for the Operations team was bringing Polaris, our 560-node HPE Apollo Gen10+ system into production. Polaris also represents our first production deployment of the PBS Pro workload manager and feedback has been generally positive.

One of the exciting things we are working on with Polaris is supporting experimental science with on-demand computing. Just before the end of the year, using data acquisition and management software developed at Argonne’s Advanced Photon Source (APS) and the DOE-funded Globus tools, we achieved automated capture of data at the APS, transfer of data to the ALCF where it is analyzed, and sharing results with the scientific team, all in near real-time without human intervention. The goal is to refine this approach and have it ready for production when the APS upgrade is complete. The runs will use Polaris, and Aurora when it comes online, to leverage advanced AI/ML methods and unlock new scientific opportunities, enabling scientific exploration at speeds and scales previously inaccessible to researchers.  While the APS is a logical partner, this is a general technique that can be applied to any science domain that needs on-demand computing.

Working with the ALCF Data Science team and systems teams from Argonne’s CELS (Computing, Environment, and Life Sciences) directorate, we also opened the first two systems in the AI Testbed to the public. The Cerebras CS1 wafer-scale system and SambaNova SN10 Dataflow system were made available for general use and at the end of the year both underwent significant upgrades which should be available early next year. We also made a significant upgrade to the Graphcore Intelligent Processing Unit (IPU) system and expect that system to be released to the public next year as well.

While it may seem like a small thing, we accomplished our first online or “hot” storage upgrade in late 2022. This was the culmination of two years of work with HPE to get the system software ready for this. While not every upgrade will be “hitless” going forward, it does allow us to reduce the downtime of the storage systems which is a win for everyone.

We are also engaged in the Aurora installation and the Operations team works closely with HPE and Intel to bring this across the finish line.

We continue to collaborate with Altair Engineering and the OpenPBS community. Argonne contributed to many of the features in V22 and we made significant improvements to a longstanding Python memory leak issue, which should be eliminated altogether with a future fix. Our current focus is on porting the PBS to the AI Testbed machines.



# Kalyan Kumaran, ALCF Director of Technology

In 2022, we made significant progress in our efforts to stand up Aurora. Our team continued its collaborations with Intel on the non-recurring engineering (NRE) contract and our work with applications development teams participating in DOE’s Exascale Computing Project (ECP) and the Aurora Early Science Program (ESP).

The collaborative efforts led to a number of highlights: standing up another Aurora testbed, Florentia, which features Intel’s Data Center GPU Max, for ESP and ECP users via our Joint Laboratory for System Evaluation; making significant progress in oneAPI development especially in compilers, math libraries, and AI frameworks; and advancing application porting efforts for Aurora.

To push portable programming models across various ecosystems, our team worked on supporting SYCL and HIP on all DOE supercomputers. We also made a concentrated effort to provide more training opportunities to prepare users for Aurora and Polaris. Topics for the ALCF’s monthly webinars specifically targeted the programming models, performance tools, I/O, and AI software that will be available on these systems. Our teams also led workshops and sessions on SYCL/DPC++ and DAOS at computing events like SC22 and the ECP Annual Meeting.

In the AI space, our staff contributed to the MLPerf HPC, Storage and Science benchmarks. The deep-learning I/O benchmarking tool has been adopted by the MLPerf Storage community for benchmarking AI systems. The team helped deploy two AI accelerators, Cerebras and SambaNova, in production for the open-science community. We continued to grow the ALCF AI Testbed, adding new AI accelerators and conducting several workshops on how to effectively use the systems for science, Including a tutorial at SC’22. The team also hosted the ALCF AI for Science Training Series to teach a new generation of researchers how to use supercomputers for AI research.

I’m proud that the Technology team’s staff members were part of the winning team for the Gordon Bell Special Prize for COVID-19 Research at SC22, and our visualization team was a finalist for the Best Visualization in the SC22 Scientific Visualization & Data Analytics Showcase. Overall, our team has adapted well to work in a hybrid environment and continues to support our users in their pursuit of scientific discoveries.



{% include media-img.html
   source= "ramprakash-riley.png"
   caption= "Left: Jini Ramprakash, right: Katherine Riley"
%}

# Jini Ramprakash, ALCF Deputy Director

In 2022, we transitioned to a hybrid mode of working with many staff returning to the office and many others embracing remote work as the preferred option. Along with the return of staff to Argonne, we also saw a huge increase in the number of people requesting tours of the ALCF data center to see the Aurora infrastructure and the visualization lab. Our tour guests spanned the whole spectrum from students to potential industry collaborators to DOE appointees and staff, including DOE Secretary Jennifer Granholm.

We also continued our collaborative efforts to build a pipeline for the next-generation workforce in HPC and the computing sciences, with an emphasis on strengthening diversity, equity, and inclusion. Starting with student outreach, ALCF staff lead and volunteer for a variety of activities, including Argonne’s annual computing camps, and mentor young researchers through internships and programs like ACT-SO (Afro-Academic, Cultural, Technological & Scientific Olympics). We’re also helping to advance the Exascale Computing Project’s Broadening Participation Initiative, which was established to boost the recruitment and retention of a diverse HPC workforce. The initiative’s “Intro to HPC” thrust, which I helped launch, is now being led by ALCF’s Paige Kinsley, who is spearheading efforts to provide accessible materials for developing foundational skills that prepare people for future careers and opportunities in HPC. 

We achieved an exciting milestone in our ongoing work to advance data-driven discoveries by tightly coupling ALCF supercomputing resources with experiments at Argonne’s Advanced Photon Source (APS). Leveraging Polaris and Globus services, we were able to complete our first fully automated end-to-end test using data collected during an APS experiment. Piloting this capability here at Argonne dovetails nicely with our involvement in the DOE Office of Science’s Integrated Research Infrastructure (IRI) Task Force, a multi-laboratory effort that is building a blueprint for integrating DOE’s computing, experimental, and observational facilities. The vision for this undertaking is to accelerate discoveries by enabling near-real-time processing and analysis of the ever-growing amount of scientific data being produced at experimental facilities. In partnership with our fellow DOE user facilities, we are working to identify operational gaps and the needed investments to realize a truly integrated research ecosystem. The IRI, along with our efforts to integrate ALCF resources with the APS, are providing a glimpse into a future where the combination of advanced computing and large-scale experiments will transform science at Argonne and across the broader DOE ecosystem.


# Katherine Riley, ALCF Director of Science

It was another exciting year for science at the ALCF. We supported dozens of projects through DOE’s INCITE, ALCC and Early Science programs, and many more through our Director’s Discretionary program. Our user community produced over 200 publications this year, many of which were highlighted in our monthly presentations to DOE and featured in articles on our website. 

One notable highlight is a collaborative project between Argonne and 3M that used simulations and machine learning to optimize the production of melt-blown nonwoven materials for various fabrics and filters, including N95 masks. Another project led by researchers at the University of College London coupled an ensemble simulation-based sampling method with machine learning to speed up the search for promising drug candidates to combat COVID-19 and other viruses. As a final example, an Argonne team used Theta to gain insights into battery material performance, leading to the discovery of a new battery electrolyte that can hold significantly more water than conventional electrolytes. Their study, which included experimental validation, provides a potential pathway to producing lower-cost and more environmentally friendly batteries.

With Aurora nearing completion, we also continued to make progress toward ensuring the system is ready for science as soon as it is released to the user community. Research teams from the Aurora Early Science Program and DOE’s Exascale Computing Project are on the front line of the Aurora application development efforts. They continued working closely with ALCF staff to port and optimize codes and software for Aurora using early hardware, including the new Sunspot testbed. Training is also a big part of preparing users for Aurora, with both the ALCF and ECP hosting workshops, tutorials, webinars, and hackathons to ready researchers for science in the exascale era. We’re so excited to finally see Aurora in action when the Early Science teams begin carrying out their research campaigns next year. Aurora, along with our newest computing resources, Polaris and the ALCF AI Testbed, are going to power some exciting discoveries by taking the convergence of simulation, data analysis, and AI methods to a whole new level. 
