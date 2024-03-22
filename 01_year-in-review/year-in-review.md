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

One of the most significant changes of the year was the retirement of Theta, Cooley, and the theta-fs0 storage systems. They were great systems that helped our users accomplish a lot of science. From the operations perspective, there is a silver lining in that it reduces the number of systems and makes our operational environment more uniform without them, but it is still sad to see them go.

We made some significant improvements to our systems over the course of the year. 
- The ALCF AI Testbed’s Graphcore and Groq systems were made available for use and all four publicly available tested systems (Cerebras, SambaNova, Groq, and Graphcore) got significant upgrades.
- Polaris network hardware was upgraded from Slingshot 10 to Slingshot 11, doubling the max theoretical bandwidth. We are working on system software upgrades that will include the Slingshot software, programming environment, and Nvidia drivers.
- The HPSS disk cache was increased from 1PB to 9PB, significantly improving the probability of a “cache hit” and faster data retrieval.

Operationally, we continue to work on expanding our support for an integrated research infrastructure (IRI). Much of our initial work was with Argonne’s Advanced Photon Source, and while we continue to work with them, we are also collaborating with other facilities. From the operations side, we are working to make it faster and easier to create new on-demand endpoints. This includes making the endpoints more robust and easier for scientists to manage.

Last, but certainly not least, the Operations team has been decisively engaged in the Aurora bring up. We have done extensive work to assist in the stabilization efforts. We continue to work on developing software and processes to manage the gargantuan amount of log and telemetry that the system produces. We have provided support for scheduling. Our system admins have developed extensive prolog and epilogue hooks to detect and, where possible, automatically remediate known issues on the system while the vendors work on permanent resolution. We have also assisted in supporting the user community. Because of the NDA (Non-Disclosure Agreement) requirements, we set up a special Slack instance to facilitate discussion and have assisted in conducting training.

We continue to collaborate with Altair Engineering and the OpenPBS community. We found some scale-related bugs that were making administration on Aurora slow and difficult. We worked closely with Altair and they provided patch updates very quickly and integrated those fixes into the production releases. We continued our work on porting PBS to the AI Testbed systems, but their unique hardware architectures and constraints have been challenging. However, later in the year, we were forced to table the AI system work and focus on Aurora.




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

It was a busy year for the ALCF as we continued to make strides in deploying new systems, tools, and capabilities to support HPC- and AI-driven scientific research, while also broadening our outreach efforts to engage with new communities. In the outreach space, we partnered with colleagues at the Exascale Computing Project, NERSC, OLCF, and the Sustainable Horizons Institute to host DOE’s first “Intro to HPC Bootcamp.” With an emphasis on energy justice and workforce development, the event welcomed around 60 college students (many with little to no background in scientific computing) to use HPC for hands-on projects focused on making positive social impacts. It was very gratifying to see how engaged the students were in this immersive, week-long event. The bootcamp is a great addition to our extensive outreach efforts aimed at cultivating the next-generation computing workforce.

Our ongoing efforts to develop an integrated research infrastructure (IRI) also got a boost this year. As a member of DOE’s IRI Task Force and IRI Blueprint Activity over the past few years, I’ve had the opportunity to collaborate with colleagues across the national labs to formulate a long-term strategy for integrating computing facilities like the ALCF with data-intensive experimental and observational facilities. In 2023, we released the IRI Architecture Blueprint Activity Report, which lays out a framework for moving ahead with coordinated implementation efforts across DOE. At the same time, the ALCF continued to build on its long history of developing and demonstrating tools and methods to integrate our supercomputers with experimental facilities, such as Argonne’s Advanced Photon Source and the DIII-D. This year, Argonne launched “Nexus,” bringing together all of the lab’s new and ongoing research activities and partnerships in this domain, ensuring they align with DOE’s broader IRI vision. 

We also made progress toward an Argonne Enterprise Registration System, a new lab-wide registration platform aimed at standardizing data collection and processing for various categories of non-employees, including facility users. In 2023, we defined system requirements and issued a request for proposals for building the platform. Ultimately, the new system will help eliminate redundant data entry, simplify registration processes for both users and staff, and enhance our reporting capabilities.

As a final note on 2023, we kicked off the ALCF-4 project to plan for our next-generation supercomputer, with DOE approving the CD-0 (Critical Decision-0) mission need for the project in April. We also established the leadership team (with myself as the project director and Kevin Harms as technical director) and began conversations with vendors to discuss their technology roadmaps. We look forward to ramping up the ALCF-4 project in 2024.


# Katherine Riley, ALCF Director of Science

Year after year, our user community breaks new ground in using HPC and AI for science. From improving climate modeling capabilities to speeding up the discovery of new materials and advancing our understanding of complex cosmological phenomena, the research generated by ALCF users never ceases to amaze me.

In 2023, we supported 18 INCITE projects and 33 ALCC projects (across two ALCC allocation cycles), as well as numerous Director’s Discretionary projects. Many of these projects were among the last to use Theta, which was retired at the end of the year. Over its 6+ year run as our production supercomputer, Theta delivered 202 million node-hours to 636 projects. The system also played a key role in boosting our facility’s AI and data science capabilities. Theta was a remarkably productive and reliable machine that will be missed by ALCF users and staff alike. 

Research project supported by ALCF computing resources produced over 200 publications in 2023. You can read about several of these efforts in the science highlights section of this report, including a University of Illinois Chicago team that identified the exact reaction coordinates for a key protein mechanism for the first time; a team from the University of Dayton Research Institute and Air Force Research Laboratory that shed light on the complex thermal environments encountered by hypersonic vehicles; and an Argonne team that investigated the impact of disruptions in cancer screening caused by the COVID-19 pandemic. 

It was also a very exciting year for Aurora as early science teams began using the exascale system for the first time. After years of diligent work to prepare codes for the Aurora’s unique architecture, the teams were able to begin scaling and optimizing their applications on the machine. Their early performance results have been very promising, giving us a glimpse of what will be possible when teams start using the full supercomputer for their research campaigns next year. 
