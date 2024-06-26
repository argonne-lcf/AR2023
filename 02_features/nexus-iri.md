---
layout: page

theme: dark
permalink: features/nexus-iri

title: Integrating Supercomputers with Experiments
hero-img-source: polaris+aps_1600x900.jpg
hero-img-caption: "The co-location of the ALCF and APS at Argonne provides an ideal environment for developing and demonstrating capabilities for a broader Integrated Research Infrastructure."
intro: "With Argonne’s Nexus effort, the ALCF continues to build off its long history of developing tools and capabilities to accelerate data-intensive science via an Integrated Research Infrastructure."
---


When the massive upgrade at Argonne’s Advanced Photon Source (APS) is completed in 2024, experiments at the powerful X-ray light source are expected to generate 100–200 petabytes of scientific data per year. That’s a substantial increase over the approximately 5 petabytes that were being produced annually at the APS before the upgrade. When factoring in DOE’s four other light sources, the facilities are projected to collectively generate an exabyte of data per year in the coming decade.

The growing deluge of scientific data is not unique to light sources. Telescopes, particle accelerators, fusion research facilities, remote sensors, and other scientific instruments also produce large amounts of data. And as their capabilities improve over time, the data generation rates will only continue to grow. The scientific community’s ability to process, analyze, store, and share these massive datasets is critical to gaining insights that will spark new discoveries. 

To help scientists manage the ever-increasing amount of scientific data, [Argonne’s Nexus effort](https://www.anl.gov/nexus-connect) is playing a key role in supporting DOE’s vision to build an Integrated Research Infrastructure (IRI). The development of an IRI would accelerate data-intensive science by creating an environment that seamlessly melds large-scale research facilities with DOE’s world-class supercomputing, artificial intelligence (AI), and data resources.

{% include media-img.html
   source= "Nexus-Infographic.jpg"
   caption= "Argonne's Nexus effort is working to advance data-intensive science via an Integrated Research Infrastructure that connects experimental facilities, supercomputing resources and data technologies."
   credit= "Argonne National Laboratory"
%}

For over three decades, Argonne has been working to develop tools and methods to integrate its powerful computing resources with experiments. The ALCF’s IRI efforts include a number of successful collaborations that demonstrate the efficacy of combining its supercomputers with experiments for near real-time data analysis. [Merging ALCF supercomputers with the APS](https://www.alcf.anl.gov/news/bright-lights-big-data-how-argonne-bringing-supercomputing-and-x-rays-together-scientific) has been a significant focus of the lab’s IRI-related research, but the work has also involved collaborations with facilities ranging from [DIII-D National Fusion Facility](https://www.alcf.anl.gov/news/close-computation-far-away-demand-analysis-fuels-frontier-science) in California to [CERN’s Large Hadron Collider (LHC)](https://www.alcf.anl.gov/news/argonne-team-brings-leadership-computing-cern-s-large-hadron-collider) in Switzerland.

These collaborations have led to the creation of new capabilities for on-demand computing and managing complex workflows, giving the lab valuable experience to support the DOE IRI initiative. Argonne also operates several resources and services that are key to realizing the IRI vision.

-	The ALCF's [Polaris](https://www.alcf.anl.gov/polaris) and [Aurora](https://www.alcf.anl.gov/aurora) systems are powerful supercomputers with advanced capabilities for simulation, AI, and data analysis.
-	The [ALCF AI Testbed](https://www.alcf.anl.gov/alcf-ai-testbed) provides researchers with access to novel AI accelerators for data-intensive tasks and AI workloads, including training, inference, large language models, and computer vision models. 
-	The [ALCF Community Data Co-Op (ACDC)](https://www.acdc.alcf.anl.gov) provides large-scale data storage capabilities, offering a portal that makes it easy to share data with external collaborators across the globe. 
-	[Globus](https://www.globus.org), a research automation platform created by researchers at Argonne and the University of Chicago, is a not-for-profit service used to manage high-speed data transfers, computing workflows, data collection, and other tasks for experiments.


# Streamlining Science

The IRI will not only enable experiments to analyze vast amounts of data, but it will also allow them to process large datasets quickly for rapid results. This is crucial as experiment-time analysis often plays a key role in shaping subsequent experiments.

{% include media-img.html
   source= "SC23-Nexus-talk.jpg"
   caption= "Rachana Ananthakrishnan, Globus executive director (left), and Tom Uram, ALCF IRI lead (right), give a talk on Nexus at the DOE booth at the SC23 Conference."
   credit= "Argonne National Laboratory"
%}

For the Argonne-DIII-D collaboration, researchers demonstrated how the close integration of ALCF supercomputers could benefit a fast-paced experimental setup. Their work centered on a fusion experiment that used a series of plasma pulses, or shots, to study the behavior of plasmas under controlled conditions. The shots were occurring every 20 minutes, but the data analysis required more than 20 minutes using their local computing resources, so the results were not available in time to inform the ensuing shot. DIII-D teamed up with the ALCF to explore how they could leverage supercomputers to speed up the analysis process. 

To help DIII-D researchers obtain results on a between-pulse timescale, the ALCF team automated and shifted the analysis step to ALCF systems, which computed the analysis of every single pulse and returned the results to the research team in a fraction of the time required by the computing resources locally available at DIII-D. Not only did the DIII-D team get the results in time to calibrate the next shot, they also got 16x higher resolution analyses that helped improve the accuracy of their experimental configuration.

Many APS experiments, including battery research, the exploration of materials failure, and drug development, also need data analyzed in near real-time so scientists can modify their experiments as they are running. By getting immediate analysis results, researchers can use the insights to steer an experiment and zoom in on a particular area to see critical processes, such as the molecular changes that occur during a battery’s charge and discharge cycles, as they are happening.

<br>

{% include media-video.html
   embed-code= '<iframe src="https://www.youtube.com/embed/twLutyNPmX4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>'
   caption= "Argonne's Nicholas Schwarz discusses how the integration of Aurora and the upgraded APS will transform science."
   credit= "Argonne National Laboratory"
%}

A fully realized IRI would also impact the people conducting the research. Scientists must often devote considerable time and effort to managing data when running an experiment. This includes tasks like storing, transferring, validating, and sharing data before it can be used to gain new insights. The IRI seeks to automate many of these tedious data management tasks so researchers can focus more on the science. This would help streamline the scientific process by freeing up scientists to form hypotheses while experiments are being carried out.

# Supercomputing on Demand 

Getting instant access to DOE supercomputers for data analysis requires a shift in how the computing facilities operate. Each facility has established policies and processes for gaining access to machines, setting up user accounts, managing data and other tasks. If a researcher is set up at one computing facility but needs to use supercomputers at the other facilities, they would have to go through a similar set of steps again for each site.

Once a project is set up, researchers submit their jobs to a queue, where they wait their turn to run on the supercomputer. While the traditional queuing system helps optimize supercomputer usage at the facilities, it does not support the rapid turnaround times needed for the IRI.

To make things easy for the end users, the IRI will require implementing a uniform way for experimental teams to gain quick access to the DOE supercomputing resources.

To that end, Argonne has developed and demonstrated methods for overcoming both the user account and job scheduling challenges. The co-location of the APS and the ALCF on the Argonne campus has offered an ideal environment for testing and demonstrating such capabilities. When the ALCF launched the Polaris supercomputer in 2022, four of the system’s racks were dedicated to advancing the integration efforts with experimental facilities.

{% include media-img.html
   source= "ALCF-Polaris.jpg"
   caption= "The ALCF’s Polaris supercomputer is supporting research to advance the development of an Integrated Research Infrastructure."
   credit= "Argonne National Laboratory"
%}

In the case of user accounts, the existing process can get unwieldy for experiments involving several team members who need to use the computing facilities for data processing. Because many experiments have a team of people collecting data and running analysis jobs, it is important to devise a method that supports the experiment independent of who is operating the instruments on a particular day. In response to this challenge, the Argonne team has piloted the idea of employing “service accounts” that provide secure access to a particular experiment instead of requiring each team member to have an active account. 

To address the job scheduling issue, the Argonne team has set aside a portion of Polaris nodes to run with “on-demand” and “preemptable” queues. This approach allows time-sensitive jobs to run on the dedicated nodes immediately. 

Using data collected during an APS experiment, the team was able to complete their first fully automated end-to-end test of the service accounts and preemptable queues on Polaris with no humans in the loop. While work continues to enable these capabilities at more and more beamlines, this effort points to a future where the integration of the upgraded APS and the ALCF's Aurora exascale supercomputer will transform science at Argonne and beyond.

# Bringing It All Together

While Argonne and its fellow national labs have been working on projects to demonstrate the promise of an integrated research paradigm for the past several years, DOE’s Advanced Scientific Computing Research (ASCR) program made it a more formal initiative in 2020 with the creation of the IRI Task Force. Comprised of members from several national labs, including Argonne’s Corey Adams, Jini Ramprakash, Nicholas Schwarz, and Tom Uram, the task force identified the opportunities, risks, and challenges posed by such an integration.

{% include media-img.html
   source= "IRI-blueprint-report.png"
   caption= "DOE's IRI Architecture Blueprint Activity Report provides the conceptual foundations to move forward with coordinated DOE implementation efforts."
%}

ASCR recently launched the IRI Blueprint Activity to create a framework for implementing the IRI. In 2023, the blueprint team, which included Ramprakash and Schwarz, released the [IRI Archictecture Blueprint Activity Report](https://www.osti.gov/biblio/1984466), which describes a path forward from the lab’s individual partnerships and demonstrations to a broader long-term strategy that will work across the DOE ecosystem. Over the past year, the blueprint activities have started to formalize with the introduction of IRI testbed resources and environments. Now in place at each of the DOE computing facilities, the testbeds facilitate research to explore and refine IRI ideas in collaboration with teams from DOE experimental facilities.

{% include media-download.html
   thumbsource= "IRI-blueprint-report.png"
   filesource= "https://www.osti.gov/biblio/1984466"
   title= "IRI Architecture Blueprint Activity Report"
   credit= "Department of Energy"
   filetype= "PDF"
   filesize= "1.2kb"
%}

With the launch of Argonne’s Nexus effort, the lab will continue to leverage its expertise and resources to help DOE and the larger scientific community enable and scale this new paradigm across a diverse range of research areas, scientific instruments, and user facilities. 
