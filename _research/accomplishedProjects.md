---
title: "Selected Projects"
excerpt: A sampling of projects divided into two self-explanatory groups.
collection:
type: "Research"
permalink:

---

<br/>
# Accomplished Projects
# 1. Load Shedding in Data Stream Management Systems.

  The continuous feature of both data and queries in data stream management systems (DSMSs) place great demand on system resources. However, queries can be processed with different levels of quality such as timeliness, reliability, and uncertainty. In this project, we study the problem of how to maintain tuple processing delays in query processing in DSMSs. A widely-used approach to maintain QoS (especially tuple delays) in DSMS query processing is load shedding, i.e., dropping data. Current load shedding solutions utilize simple, intuitive ideas in determining the time and amount of load to be discarded and do not work well in the presence of system/environmental disturbances. We propose a solution based on feedback control theory with significantly improved long-term performance. Currently, we are exploring the strategy of semantic load shedding: selectively shedding data according to their importance to the query results. Publications: [[ICDE07]](https://cse.usf.edu/~tuy/pub/ICDE07.pdf)[[VLDB06]](https://cse.usf.edu/~tuy/pub/vldb06.pdf)[[DEXA05a]](https://cse.usf.edu/~tuy/pub/dexa05-ctrl.pdf)[[Code download]](https://cse.usf.edu/~tuy/research/code/DSMS-readme.htm)



# 2. QuaSAQ: Enabling End-to-End QoS by A Database-Centric Approach.

  Support of user-input QoS requirements in multimedia databases cannot be accomplished by simply deploying the multimedia DBMS on top of QoS-provisioning OS or middleware. We propose an integrated QoS-control framework (QuaSAQ) as part of the DBMS as well as cost models to evaluate the QoS-aware queries. QuaSAQ is implemented on the basis of our video DBMS - [VDBMS](https://www.cs.purdue.edu/vdbms/).  Publications: [[EDBT04]](https://cse.usf.edu/~tuy/pub/edbt04.pdf)[[DEXA05b]](https://cse.usf.edu/~tuy/pub/dexa05-rep.pdf)[[TKDE07]](https://cse.usf.edu/~tuy/pub/TKDE07.pdf)



# 3. Hybrid Peer-to-Peer Media Streaming System. [[link]](https://cse.usf.edu/~tuy/research/P2P/index1.html)

  Peer-to-peer networks provide a method to solve the scalability problem of traditional server-based media streaming services. We studied the capacity (bandwidth) growth of such systems by performing quantitative analysis of a generic P2P streaming model.  Publications: [[TOMCCAP05]](https://cse.usf.edu/~tuy/pub/tomccap05.pdf)[[MMCN04]](https://cse.usf.edu/~tuy/pub/spie04.pdf)



# 4. VDBMS - A video DBMS. [[link]](https://www.cs.purdue.edu/vdbms/)

  A multimedia DBMS with full-featured video processing and content-based retrieval capabilities. I investigated the use of tertiary storage as medium for active data. One of the most serious problems in using tertiary storage is long response time to requests. I also studied relevant caching and pre-fetching algorithms for the purpose of minimizing latency. Publications: [[MMSJ04]](https://cse.usf.edu/~tuy/pub/mms_vdbms.pdf)[[DMS03]](https://cse.usf.edu/~tuy/pub/DMS03.pdf)[[ICDE02]](https://cse.usf.edu/~tuy/pub/icde02.pdf)



# 5. HPKB. [[link]](https://www.cs.purdue.edu/hpkb/)

  An interactive knowledge-based system for efficient and cost-effective maintenance of naval ships. A description of HPKB infrastructure and methodology: [[link]](https://cse.usf.edu/~tuy/research/HPKB/intro.PDF)
  
<br/>
<hr/>
<br/>

# Funded Projects

# 1. II-New: A Research Platform for Heterogeneous, Massive Parallel Computing


  The aim of this project is to build a new computing research infrastructure that will accelerate existing research and enable ground-breaking new research that shares the common theme of massive parallel computing at USF. The requested infrastructure is a computer cluster with about 120 many-core co-processors including GPUs and Intel Phi cards. This acquisition will provide the much needed parallel computing capacity that is currently lacking in the existing USF IT infrastructure. This project will bring together eight investigators with research projects in several core disciplines of computer science and engineering: big data management, scientific computing, system security, hardware design, data mining, computer vision and pattern recognition. The proposed new resource will enable or enhance research in design, implementation, and evaluation of parallel programs at various levels of the software stack, ranging from cluster-level systems to individual application components and domain-specific languages. The infrastructure will also enhance learning experience of students as well as course content, curriculum development, and laboratory environment. The team of investigators will form a "USF Parallel Computing Workgroup" to coordinate related research, education, and outreach activities. This ensures the project team act in an integrated way to maximize the impact of the new infrastructure on the entire USF community.
    This project is supported by an [NSF](https://www.nsf.gov/) CRI award ([CNS-1513126](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1513126)).
    


# 2. G-SDMS: A High-Throughput Scientific Data Management System


  Many scientific domains have entered a data-driven era, in which scientific discovery depends heavily on effective and efficient analysis of large-scale data generated by wet-bench experiments or computer simulations. Current database management systems (DBMSs), while being very popular in the business world, fall short in high-throughput data processing required by scientific applications. The goal of this project is to design and implement a novel data management software architecture that enables high-throughput data management services for general scientific communities. The project achieves this goal via (1) a novel one-scan-fits-all data processing framework based on repetitive scans of large data sources; (2) a query engine that leverages the massive computing power of modern Graphics Processing Units (GPU) hardware; and (3) design and implementation of algorithms for popular analytics in three scientific domains on top of the query engine to demonstrate the effectiveness and efficiency of the proposed architecture. The project also aims at building a software prototype and evaluating this prototype with real-world scientific datasets and query workloads. The project is expected to provide a highly efficient solution to satisfy the data management needs of a wide range of scientific fields. To deliver comparable performance, the proposed architecture requires only a fraction of the hardware and energy costs needed by existing systems. As a result, it will make scientific studies that are regarded as difficult or infeasible a reality. The proposed research will be integrated into educational endeavors that contribute to broadening the influence of computer science, nurturing the next generation of multidisciplinary scientists, and boosting the success of minority and women students in the computer science and engineering field.
    This project is supported by an [NSF](https://www.nsf.gov/) CAREER award ([IIS-1253980](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1253980)). Sample publications: [[SSDBM13]](https://cse.usf.edu/~tuy/pub/SSDBM13.pdf) [[TKDE14]](https://cse.usf.edu/~tuy/pub/TKDE14.pdf) [[BigData14]](https://cse.usf.edu/~tuy/pub/BigData14.pdf) [[SIGMOD17]](https://cse.usf.edu/~tuy/pub/SIGMOD17.pdf)
    


# 3. Efficient Data Processing in Molecular Dynamics Simulation: Framework and Algorithms


  Atomistic level Molecular Dynamics can provide insights into the structure, dynamics, and thermodynamic characteristics of biological structures. Studies on molecular dynamics thus attracted a great deal of attention from the research communities of biology, physics, and chemistry. Computer simulation is an important method for molecular dynamics research. The outcome of an MD simulation is a "pseudo trajectory" of positions and velocities of all of the atoms in the simulation system. Due to the large number of atoms/molecules and time instances to simulate, such simulations generate tremendous amounts of data. How to effectively and efficiently reason about such data is a critical problem that directly affects the success of any molecular simulation study. Current strategies to store, access, and query such data are all based on computer files. This renders some serious efficiency problems in querying and sharing the simulation data. In this project, we propose the idea of storing simulation data in databases and develop novel indexing strategies to help optimize the processing of a wide range of queries.
    This project is supported by a National Institutes of Health ([NIH](https://www.nih.gov/)) R01 grant (R01-GM086707). Sample publications: [[ICDE09]](https://cse.usf.edu/~tuy/pub/ICDE09.pdf)[[VLDBJ10]](https://cse.usf.edu/~tuy/pub/VLDBJ10.pdf)[EDBT12](https://cse.usf.edu/~tuy/pub/EDBT12.pdf)[[TKDE13]](https://cse.usf.edu/~tuy/pub/TKDE13.pdf)[[Code download]](https://cse.usf.edu/~tuy/research/code/SDH.c)

    
    
    
# 4. Power-Aware Database Systems


  Maintaining a sustainable society via technological innovations has been a major challenge to scientists and engineers in the 21st century. With the total energy consumption of computing equipment increasing at a steep rate, much attention has been paid to the design of energy-effecient computing systems. Power-aware computing research at the applications level has been found to be synergistic to that at the system level (e.g., hardware and OS) because it can provide more opportunities of energy reduction for the underlying systems. In this project, we focus on database management systems (DBMS), which often consume a majority of the computing resources (and power) in modern data centers. We aim the design and implementation of a power-aware DBMS that can signiﬁcantly reduce energy use with graceful performance degradation. Our preliminary results have demonstrated great potential of this line of research.
    This project is supported by an [NSF](https://www.nsf.gov/) grant via its CISE core program ([IIS-001117699](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1117699)) and a Florida Energy Systems Consortium ([FESC](http://floridaenergy.ufl.edu/)) seed grant. Sample publications: [[ICDE10]](https://cse.usf.edu/~tuy/pub/ICDE10.pdf)[[SIGMODREC14]](https://cse.usf.edu/~tuy/pub/SIGREC12.pdf)[[ICDCS13]](https://cse.usf.edu/~tuy/pub/ICDCS13.pdf)
