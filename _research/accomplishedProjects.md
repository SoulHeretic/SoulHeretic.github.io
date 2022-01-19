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





	<div id="container">

		<div id="header" style="width: 831px; height: 80px">

			<b><font size="4">Yicheng Tu's Publications&nbsp; (<a href="http://www.informatik.uni-trier.de/~ley/db/indices/a-tree/t/Tu:Yi=Cheng.html">DBLP</a>)</font></b><p>

			<font face="Garamond" size="2"><script language="JavaScript" type="text/javascript" src="http://www.cse.usf.edu/cgi-bin/cgiwrap/~ytu/quote.pl"></script></font></div>

		<div id="nav" style="width: 122px; height: 324px">

			<a href="../index.html">Home</a> <a href="index.html">Research Home</a>&nbsp;&nbsp;

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			

			<address><span style="font-style: normal">

				<font size="1" style="font-size: 9pt"><a href="#Submitted">

				Demos</a></font></span></address>

			<address><span style="font-style: normal">

				<font style="font-size: 9pt"><a href="#Submitted">Submitted</a></font></span></address>

			<address><span style="font-style: normal; font-size: 9pt">

				<a href="#TR">Tech 

				Reports</a></span></address>

			<address><span style="font-style: normal; font-size: 9pt">

				<a href="#Non-CS">Non-CS stuff</a></span></address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address>&nbsp;</address>

			<address style="text-align: center">

				<img border="0" src="../image/usf_logo_r.gif"></address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address style="text-align: center">

				&nbsp;</address>

			<address><span style="font-style: normal">

				<font style="font-size: 9pt"><a href="#Journal">Journals</a></font></span></address>

			<address><span style="font-style: normal">

				<font style="font-size: 9pt"><a href="#Conference">

				Conferences</a></font></span></address>

			<address><span style="font-style: normal">

				<font size="1" style="font-size: 9pt"><a href="#Submitted">

				Demos</a></font></span></address>

			<address>&nbsp;</address>

			<address align="center">

				&nbsp;</address>

			<address align="center">

				&nbsp;</address>

			<address align="center">

				&nbsp; </address>
			<address align="center">

				&nbsp;</address>
			<address align="center">

				&nbsp;</address>

			<address align="center">

				&nbsp;</address>

			<address align="center">

				&nbsp;</address>

			<address align="center">

				&nbsp;</address>

			<address align="center">

				&nbsp;&nbsp;&nbsp;

				<img border="0" src="../image/usf_logo_r.gif"></address>

			<address style="text-align: center">

				&nbsp;</address>

			</div>

										

		<div id="content" style="width: 710px">

		<h2><a name="Journal"></a>Refereed Journals</h2>

		<ol>
			<li><img id="_x0000_i1071" height="11" src="new.gif" width="28" border="0"><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
					Zhila Nouri-Lewis and <b>Yi-Cheng Tu</b>. G-PICS: A Framework for GPU-Based Spatial Indexing and Query Processing.
 To appear in <i>IEEE Transactions on Knowledge and Data Engineering
                        </i> (<i>TKDE</i>).

			<li><img id="_x0000_i1071" height="11" src="new.gif" width="28" border="0"><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
Ran Rui, Hao Li, and <b>Yi-Cheng Tu</b>. Efficient Join Algorithms for large Database Tables in a Multi-GPU Environment. <i>Proceedings of the Very Large DataBase (VLDB) Endowment</i> 14(4):708-720. <a href="../pub/VLDB21.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
<li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">X. Liu, C. Li, C. Mou, Y. Dong,
and <b>Y. Tu</b>.
dbNSFP v4: A comprehensive database of transcript-specific functional predictions and annotations for human nonsynonymous and splice-site SNVs. <i>Genome Medicine</i> 12:103, December 2020. <a href="../pub/dbNSFP.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>

			<li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">C. Li, C. Mou, M. Swartz, B. Yu, Y. Bai,
                <b>Y. Tu</b>, and X. Liu.
dbMTS: a comprehensive database of putative human microRNA target site SNVs and their functional predictions. <i>Human Mutations</i> 41(6):1123-1130.<a href="../pub/dbMTS20.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>

		<li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">Mehrad Eslami, Vahid Mahmoodian, Iman Dayarian, HadiCharkhgard, and
                <b>Yi-Cheng Tu</b>. 
		Query Batching Optimization in Database Systems. <i>Computer & Operations Research</i> 121:104983, September 2020.<a href="../pub/COR20.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>

		<li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
    Jinghan Meng, Napath Pitaksirianan, and <b>Yi-Cheng Tu</b>. Counting Frequent Patterns in Large Labeled Graphs: A Hypergraph-Based Approach. <i>Data Mining and Knowledge Discovery</i> 34(4):980-1021, May 2020.<a href="../pub/DMKD20.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>

		<li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">Shuang Na, Kandethody Ramachandran, Ming Ji, and
                <b>Yi-Cheng Tu</b>. Real-Time Activity Recognition Using Smartphone Accelerometer. <i>International Journal of Trends in Scientific Research and Development (IJTSRD)</i> 4(1):533-542, December 2019. <a href="../pub/IJTSRD19.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>

   <li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">Aditya Chandra Vothgod Ramachandra, Yin Lu, Minh Pham,
                <b>Yi-Cheng Tu</b>, and Feng Cheng. CuDDI: A CUDA-based application for extracting drug-drug interaction 
related substance terms from PubMed literature. <i>Molecules</i> 24(6):1081, 2019. <a href="../pub/Molecules19.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>

<li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
               Hao Li, <b>Yi-Cheng Tu</b>, and Bo Zeng. Concurrent Query Processing in a GPU-Based Database System. <i>Plos ONE</i> 14(4): e0214720, April 2019. <a href="../pub/PLOSONE19.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
         
<li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                Napath Pitaksirianan, Zhila Nouri, and  <b>Yi-Cheng Tu</b>. Algorithms and Framework for Computing 2-body Statistics on GPUs. <i>Distributed and Parallel Databases</i> 37(4):587-622, December 2019. <a href="../pub/DAPD19.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
            <li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                Chengcheng Mou, Shaoping Chen, and <b>Yi-Cheng Tu</b>. A Comparative Study of Dual-tree Algorithms for Computing Spatial Distance Histograms. <i>The Computer Journal</i> 62(1):42-62, January 2019.<a href="../pub/ComputerJ18.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
<li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                Yin Lu, Bryan Figler, Hong Huang, <b>Yi-Cheng Tu</b>, Ju Wang and Feng Cheng. Characterization of the Mechanism of Drug-drug Interactions from PubMed using MeSH Terms. <i>PLoS ONE</i> 12(4), April 2017.<a href="../pub/JDBMS17.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
<li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
    Peyman Behzadnia, Wei Yuan, Bo Zeng and <b>Yi-Cheng Tu</b>. Energy-Aware Disk Storage Management: Online Approach with Applications in DBMS. <i>International Journal of Database Management Systems</i> 9(1), February 2017.
                <a href="../pub/IJDMS17.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
            <li><!--img id="_x0000_i1071" height="11" src="new.gif" width="28" border="0"--><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                Yin Lu, Dan Shen, Maxwell Pietsch, Chetan Nagar, Zayd Fadli, Hong Huang, <b>Yi-Cheng Tu</b>, and Feng Cheng. A novel algorithm for analyzing drug-drug interactions from MEDLINE literature. <i>Scientific Reports </i> 5, 17357, November 2015.
                <a href="../pub/SREP15.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
            
            <li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                Zichen Xu, <b>Yi-Cheng Tu</b>, and Xiaorui Wang. Online Energy Estimation of Relational Operations in Database Systems. <i>IEEE Transactions on Computers</i> (<i>TC</i>) 64(11):3223-3236, January 2015.
                <a href="../pub/TC15.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
            <li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                A. Kumar, V. Grupcev, M. Berrada, J. Fogarty, <b>Y. Tu</b>, X. Zhu, S. Pandit, and Y. Xia. DCMS: A data analytics and management system for molecular simulations. <i>Journal of Big Data</i> 2:9, November 2014.
                <a href="../pub/JBD14.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
            
                        <li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                A. Kumar, V. Grupcev, Y. Yuan, <b>Y. Tu</b>, Jin Huang, and G. Shen. Computing Spatial
                Distance Histograms for Large Scientific Datasets On-the-fly. <i>IEEE Transactions on Knowledge and Data Engineering
                </i> (<i>TKDE</i>) 26(10):2410-2424, October 2014.
                <a href="../pub/TKDE14.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
            
  <li> <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
      <b> Y. Tu</b>, X. Wang, and B. Zeng. A System for Energy-Efficient Data Management. <i>SIGMOD Record</i> 43(1):21-26, March 2014.
                <a href="../pub/SIGREC12.pdf"><span style="text-decoration: none">
                        <img id="_x0000_i1046" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>
  <li> <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">Jin Huang, Feiping Nie, Heng Huang,
      <b> Yi-Cheng Tu</b>, and Yu Lei. Social Trust Prediction Using Heterogeneous Networks. Accepted to <i>ACM Transactions on Knowledge Discovery from Data</i> (<i>TKDD</i>) 7(4):17, November 2013.
      <a href="../pub/TKDD13.pdf"><span style="text-decoration: none">
          <img id="_x0000_i1046" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>
            <li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond"> C. H. Nadungodage, Y. Xia, J. Lee, and <b> Y. Tu</b>. Hyper-Structure Mining of Frequent Patterns in Uncertain Data Streams. <i>Knowledge and Information Systems</i> (<i>KAIS</i>) 37(1):219--244.
                <a href="../pub/statement"><span style="text-decoration: none">
                        <img id="_x0000_i1046" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>
            
<li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                        V. Grupcev, Y. Yuan, <b>Y. Tu</b>, Jin Huang, S. Chen, S. Pandit, and M. Weng. Approximate Algorithms for Computing
                        Distance Histograms with Accuracy Guarantees. <i>IEEE Transactions on Knowledge and Data Engineering
                        </i> (<i>TKDE</i>) 25(9):1982-1996, September 2013.
                        <a href="../pub/TKDE13.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>

<li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">S. Chen, <b>Y. Tu</b>, and Y. Xia. Performance Analysis of A Dual-Tree Algorithm for Computing Spatial Distance Histograms. <i>
			The VLDB Journal. </i> 20(4):471-494, August 2011.
			<a href="../pub/VLDBJ10.pdf"><img id="_x0000_i1067" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
			
            <li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">R. Cheng, B. Kao, S. Prabhakar, A. Kwan, and <b>Y. Tu. </b> Filtering Data Streams for Entity-based Continuous Queries. <i>IEEE Transactions on Knowledge and Data Engineering</i> (<i>TKDE</i>). 22(2):234-248, February 2010. <a href="../pub/draft/tkde09.pdf">
                <img id="_x0000_i1067" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
            
			<li><span lang="EN-US" style="font-size: 11pt; font-family: Garamond">H. Fang, Q. Wang, <b>Y. Tu</b> and M.F . Horstemeyer. An Efficient Non-Dominated Sorting	Method for Evolutionary Algorithms. <i>Journal of Evolutionary Computation</i>. 16(3):355-384, Fall 2008. <a href="../pub/statement.htm"><img id="_x0000_i1063" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>

			<li><span lang="EN-US" style="font-size: 11pt; font-family: Garamond"><b>Y. Tu,</b> J. Yan, G. Shen and S. Prabhakar. Multi-Quality Data Replication in Multimedia Databases. <i>IEEE Transactions on Knowledge and Data Engineering</i> (<i>TKDE</i>) 19(5):679-694, May 2007. <a href="../pub/TKDE07.pdf">
			<img id="_x0000_i1063" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>

			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">L. 

			Qu and<b> Y. Tu. </b>Change Point Estimation of Bi-Level Functions. 

			<i>Journal of Modern Applied Statistical Methods</i>. 5(2):347-355, 
			November 2006. </span>

			<span style="text-decoration: none; font-size:11pt; font-family:Garamond" lang="EN-US">

			<a href="../pub/JMASM06.pdf">

			<img id="_x0000_i1066" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>

			<li><b>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">Y. 

			Tu</span></b><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">, 

			J. Sun, M. Hefeeda, and S. Prabhakar. An Analytical Study of 

			Peer-to-Peer Media Streaming Systems. <i>ACM Transactions on 

			Multimedia Computing, Communications, and Applications</i> (<i>TOMCCAP</i>). 
			1(4):354-376., November 2005. 

			<a href="../pub/tomccap05.pdf">

			<img id="_x0000_i1026" height="18" src="pdf_icon.gif" width="40" border="0"></a> </span></li>

			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">W. 

			Aref, A. Catlin, A. Elmagarmid, J. Fan, M. Hammad, I. Ilyas, M. 

			Marzouk, S. Prabhakar, <b>Y. Tu</b> and X. Zhu (alphabetical order). 

			VDBMS: A Testbed Facility for Research in Video Database 

			Benchmarking. <i>ACM/Springer Multimedia Systems. </i>9(6):575-585., 

			June 2004.

			<a href="../pub/mms_vdbms.pdf">

			<img id="_x0000_i1027" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>

		</ol>

		<h2><a name="Conference"></a>Refereed Conferences and Workshops</h2>

		<ol>
			<li>
                <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
Jinghan Meng, Napath Pitaksirianan, and <b>Yi-Cheng Tu</b>.
Generalizing Design of Support Measures for Counting Frequent Patterns in Graphs. In Procs. of <i>IEEE International Conference on Big Data</i> (<i>BigData</i>), pp. 533-542, Los Angeles, CA, USA, December 2019.<a href="../pub/BigData19.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
 <li>
                <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
Faisal Qarah, and <b>Yi-Cheng Tu</b>.
A Fast Exact Viewshed Algorithm on GPUs. In Procs. of <i>IEEE International Conference on Big Data</i> (<i>BigData</i>), pp. 3397-3405, Los Angeles, CA, USA, December 2019.<a href="../pub/BigData19V.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>

   <li>
                <img id="_x0000_i1071" height="11" src="new.gif" width="28" border="0"><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                    Zhila Nouri and <b>Yi-Cheng Tu</b>. GPU-based Parallel Indexing for Concurrent Spatial Query Processing. In Procs. <i>30th International Conference on Scientific and Statistical Database Management</i> (<i>SSDBM</i>), 23, Bolzano-Bozen, Italy, July 9-11, 2018.  <a href="../pub/SSDBM18.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
   <li>
       <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
           Ran Rui and <b>Yi-Cheng Tu</b>. Fast Equi-Join Algorithms on GPUs: Design and Implementation. Accepted to <i>29th International Conference on Scientific and Statistical Database Management</i> (<i>SSDBM</i>), Chicago, IL, USA., June 27-29, 2017. (Best Paper Runner Up) <a href="../pub/SSDBM17.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
   <li>
       <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
           Jinghan Meng and <b>Yi-Cheng Tu</b>. Flexible and Feasible Support Measures for Mining
           Frequent Patterns in Large Labeled Graphs. In Procs. <i>ACM International Conference on Management of Data </i> (<i>SIGMOD</i>), Chicago, IL, USA., May 14-19, 2017.<a href="../pub/SIGMOD17.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
<li>
                <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                    Chengcheng Mou, Shaoping Chen, and <b>Yi-Cheng Tu</b>.
A comparative study of dual-tree algorithm implementations for computing 2-body statistics in spatial data. In Procs. of <i>IEEE International Conference on Big Data</i> (<i>BigData</i>), pp. 2676-2685, Washington, DC, USA, December 2016.<a href="../pub/BigData16.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
            <li> <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">Peyman Behzadnia, Wei Yuan, Bo Zeng, <b>Yi-Cheng Tu</b>, and Xiaorui Wang. Dynamic Power-Aware Disk Storage Management in Database Servers. In Procs. of <i>27th International Conference on Database and Expert Systems Applications</i> (<i>DEXA</i>), pp. 315-325, Porto, Portugal, September 5-8, 2016.<a href="../pub/DEXA16.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
                        <li>
                 <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                                Napath Pitaksirianan, Zhila Nouri, and <b>Yi-Cheng Tu</b>. Efficient 2-Body Statistics Computation on GPUs: Parallelization and Beyond. In Procs. of <i>45th International Conference on Parallel Processing</i> (<i>ICPP</i>), pp. 380-385, Philadelphia, PA, USA., August 16-19, 2016.<a href="../pub/ICPP16.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
                        
               <li> <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                    Anand Kumar, Jay Ligatti, and <b>Yi-Cheng Tu</b>. Query Monitoring and Analysis for Database Privacy - A Security Automata Model Approach. In Procs. of <i>16th International Conference on Web Information Systems Engineering </i> (<i>WISE</i>), pp. 2458-472, Miami, FL, USA., November 2015.<a href="../pub/WISE15.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
            <li>
                <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                    	Ran Rui, Hao Li, and <b>Yi-Cheng Tu</b>. Join algorithms on GPUs: A revisit after seven years. In Procs. of <i>3rd IEEE International Conference on Big Data</i> (<i>BigData</i>), pp. 2541-2550, Santa Clara, CA, USA., October 2015.<a href="../pub/BigData15-Join.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
            <li>
                <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                    Vladimir Grupcev, <b>Yi-Cheng Tu</b>, Joseph C. Fogarty, Sagar Pandit. Push-based system for molecular simulation data analysis. In Procs. of <i>3rd IEEE International Conference on Big Data</i> (<i>BigData</i>), pp. 1775-1784, Santa Clara, CA, USA., October 2015.<a href="../pub/BigData15-PDB.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
            
            <li>
                <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                    H. Li, D. Yu, A. Kumar, and Yi-Cheng Tu. Performance Modeling in CUDA Streams - A Means for High-Throughput Data Processing. In Procs. of <i>2nd IEEE International Conference on Big Data</i> (<i>BigData</i>), pp. 301-310, Washington, DC, USA., October 2014.<a href="../pub/BigData14.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
            
            <li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                    Anand Kumar, Xingquan Zhu, Yi-Cheng Tu, and Sagar Pandit. Compression of Molecular Simulation Datasets. Procs. of <i>
                        3rd International Conference on Intelligence Science and Big Data Engineering </i> (<i>ISciDE</i>).  Beijing , China. July 31 - August 2, 2013.<a href="../pub/ISCIDE13.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
            
            <li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                    Anand Kumar, Xingquan Zhu, Yi-Cheng Tu, and Sagar Pandit. Compression of Molecular Simulation Datasets. Procs. of <i>
                        3rd International Conference on Intelligence Science and Big Data Engineering </i> (<i>ISciDE</i>).  Beijing , China. July 31 - August 2, 2013.<a href="../pub/ISCIDE13.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
            <li>
                    <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                        Miguel Rodriguez, Daladier Jabba, Elias Nino, Carlos Ardila, and Yi-Cheng Tu. Automata Theory Based Approach to the Join Ordering Problem in Relational Database Systems.  Procs. of <i>
                            International Conference on Data Management Technologies and Applications </i> (<i>DATA</i>). Reykjavik, Iceland. July 29-31, 2013. (<b>Best Paper Nominee</b>)<a href="../pub/DATA13.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
                <li>
                <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                    Zichen Xu, Xiaorui Wang, and Yi-Cheng Tu. Power-Aware Throughput Control for Database Management Systems. Procs. of <i>
                        10th International Conference on Autonomic Computing</i> (<i>ICAC</i>).  <a href="../pub/ICAC13.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
            <li>
                <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                    Zichen Xu, Yi-Cheng Tu, and Xiaorui Wang. Dynamic Energy Estimation of Query Plans in Database Systems. Procs. of <i>
                        33rd International Conference on Distributed Computing Systems</i> (<i>ICDCS</i>). <a href="../pub/ICDCS13.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
<li>
<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                        Jin Huang, Feiping Nie, Heng Huang, and Yi-Cheng Tu. Trust Prediction via Aggregating Heterogeneous Social Networks. Procs. of <i>
                       21st ACM Conference on Information and Knowledge Management</i> (<i>CIKM</i>). pp.1774-1778,
 Maui, Hawaii, Oct. 30 - Nov. 1, 2012.                       <a href="../pub/CIKM12.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
        <li>
<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                        A. Kumar, V. Grupcev, <b>Y. Tu</b>, Y. Yuan, and G. Shen.
                        Distance Histogram Computation Based on Spatiotemporal Uniformity in Scientific Data. In Procs. of <i>
                       15th IEEE International Conference on Extending Database Technology</i> (<i>EDBT</i>). pp.288-299,
                       Berlin, Germany, March 26-30, 2012.
                        <a href="../pub/EDBT12.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
                        <li>
<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                        L. Qu and <b> Y. Tu</b>.
                        Noparametric Copula Estimation in Sensor Networks. In Procs. of <i>
                       7th International Conference on Mobile Ad-Hoc and Sensor Networks</i> (<i>MSN</i>),                        Beijing, China, December 16-18, 2011.
                        <a href="../pub/MSN11.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
                        <li>
<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                        L. Wang, J. Xu, M. Zhao, <b> Y. Tu</b>, and J. Fortes.
                        Fuzzy Modeling Based Resource Management for Virtualized Database Systems. In Procs. of <i>
                       19th IEEE International Symposium on Modeling, Analysis, and Simulation of Computer and Telecommunication Systems</i> (<i>MASCOTS</i>), pp.32-42,
                       Singapore, July 25-27, 2011.
                        <a href="../pub/MASCOTS11.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
<li>

                       <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">J. Ge, Y. Xia, and <b> Y. Tu</b>.
                        A Discretization Algorithm for Uncertain Data. In Procs. of <i>
                       21th International Conference on Database and Expert Systems Applications</i> (<i>DEXA</i>).
                       pp.485-499, Bilbo, Spain, August 30 - September 3, 2010.
                        <a href="../pub/DEXA10.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
                        <li><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                        Zichen Xu, <b>Yi-Cheng Tu</b>, and Xiaorui Wang. Exploring Power-Performance
			Tradeoffs in Database Systems. In <i>Procs. of 26th International 

			Conference on Data Engineering </i>(<i>ICDE</i>), pp. 485-496, Long Beach, CA, 
			March 2010. <a href="../pub/ICDE10.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">Q. Biao, Y. Xia, S. Prabhakar, and<b> Y. Tu</b>.<b> </b>A Rule-Based 
			Classification Algorithm for Uncertain Data.<b> </b>
			</span><font face="Garamond" size="3"><i>International Workshop of 
			Management and Mining of Uncertain Data</i> (<i>MOUND</i>), </font>
			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">in <i>
			conjunction with 25th International 

			Conference on Data Engineering </i>(<i>ICDE</i>), 
			</span>

			<font face="Garamond" size="3">pp. 1633-1640, Shanghai,&nbsp; China, 
			April 2, 2009. </font>

			<span style="text-decoration: none">

			<a href="../pub/MOUND09.pdf">

			<img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
			<b> Y. Tu</b>, S. Chen, and S. Pandit. Computing Distance Histograms Efficiently in Scientific Databases. 
			In <i>Procs. of 25th International 

			Conference on Data Engineering </i>(<i>ICDE</i>), pp. 796-807, Shanghai, China, March 2009. (long paper 
			with oral presentation, acceptance rate: 93/554=16.8%)
			</span>

			<span style="text-decoration: none">

			<a href="../pub/ICDE09.pdf">

			<img id="_x0000_i1062" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></a></span><span style="font-size: 11pt; text-decoration: none; font-family:Garamond" lang="EN-US"><a href="../pub/talks/ICDE09-notes.ppt"><img id="_x0000_i1069" height="18" src="ppt-Icon.gif" width="17" border="0"></a><span style="text-decoration: none">
			</span><a href="../pub/posters/ICDE09-poster.ppt">
			<img id="_x0000_i1070" height="18" src="ppt-Icon.gif" width="17" border="0"></a></span></li>

			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">Y. Xia, <b>Y. Tu</b>, M. 

			Atallah, and S. Prabhakar. Reducing Data Redundancy in Location-Based Services. In <i>Procs. of 2nd International 

			Conference on Geosensor Networks</i>, pp.30-35, Boston, MA, October 2006.

			</span><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">

			<span style="text-decoration: none">

			<a href="../pub/GSN06.pdf">

			<img id="_x0000_i1062" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></a></span></li>

			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">

			<b>Y. 

			Tu</b>, </span></b>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">S. Liu, S. Prabhakar, and B. Yao. Load Shedding in Stream Databases - A Control-Based Approach. In Proceedings of

			<i>Intl. Conf. on Very Large 

			Databases</i> (<i>VLDB</i>), pp.787-798, Seoul, Korea, September 

			2006. (acceptance rate: 46/331=13.9%)<span style=""> </span>
			<a href="../pub/vldb06.ps">

			<span style="text-decoration: none">

			<img id="_x0000_i1029" height="18" src="ps_icon.gif" width="21" border="0"></span></a><a href="../pub/vldb06.pdf"><span style="text-decoration: none"><img id="_x0000_i1030" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span><span lang="EN-US" style="FONT-SIZE: 9pt; FONT-FAMILY: Garamond"><a href="../pub/talks/vldb05-0820.ppt"><span style="font-size: 11pt; text-decoration: none"><a href="../pub/talks/VLDB06.ppt"><img id="_x0000_i1058" height="18" src="ppt-Icon.gif" width="17" border="0"></a></span></a></span></p>

			</li>

			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">R. 

			Cheng, B. Kao, S. Prabhakar, A. Kwan, and <b>Y. Tu</b>. Adaptive 

			Stream Filters for Entity-Based Queries with Non-Value Tolerance. In 

			Proceedings of <i>Intl. Conf. on Very Large Databases</i> (<i>VLDB</i>), 

			pp.37-48, Trondheim, Norway, August 2005.</span><span lang="EN-US" style="FONT-SIZE: 9pt; FONT-FAMILY: Garamond">

			</span>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">(acceptance rate: 32/195=16.4%)<a href="../pub/vldb05.pdf"><span style="text-decoration: none"><img id="_x0000_i1033" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span><span lang="EN-US" style="FONT-SIZE: 9pt; FONT-FAMILY: Garamond"><a href="../pub/talks/vldb05-0820.ppt"><span style="font-size: 11pt; text-decoration: none"><img id="_x0000_i1034" height="18" src="ppt-Icon.gif" width="17" border="0"></span></a></span>

			</p></li>

			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond; font-weight:700">Y. 

			Tu</span></b><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">, 

			J. Yan, and S. Prabhakar. Quality-Aware Replication of Multimedia 

			Data. In Proceedings of <i>Intl. Conf. of Database and Expert 

			Systems Applications</i> (<i>DEXA</i>), pp. 240-249, Copenhagen, 

			Denmark, August 2005. (acceptance rate: 92/390=23%) &nbsp;<a href="../pub/dexa05-rep.pdf"><span style="text-decoration: none"><img id="_x0000_i1035" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span><span lang="EN-US" style="FONT-SIZE: 9pt; FONT-FAMILY: Garamond"><a href="../pub/talks/Talk-dexa05-rep.ppt"><span style="font-size: 11pt; text-decoration: none"><img id="_x0000_i1036" height="18" src="ppt-Icon.gif" width="17" border="0"></span></a></span></li>

			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond; font-weight:700">Y. 

			Tu</span></b><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">, 

			M. Hefeeda, Y. Xia, S. Prabhakar, and S. Liu. Control-based Quality 

			Adaptation in Data Stream Management Systems. In Proceedings of <i>Intl. Conf. of Database and Expert Systems Applications</i> (<i>DEXA</i>), 
			pp.746-755, Copenhagen, Denmark, August 2005. (acceptance rate: 
			92/390=23%)
			<a href="../pub/dexa05-ctrl.pdf">
			<span style="text-decoration: none"><img id="_x0000_i1037" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span><span lang="EN-US" style="FONT-SIZE: 9pt; FONT-FAMILY: Garamond"><a href="../pub/talks/Talk-dexa05-ctrl.ppt"><span style="font-size: 11pt; text-decoration: none"><img id="_x0000_i1038" height="18" src="ppt-Icon.gif" width="17" border="0"></span></a></span></p>

			</li>

			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">L. 

			Qu and <b>Y. Tu</b>. Change Point Estimation of Bar Code Signals.<b>

			</b>In Proceedings of <i>International Conference on Scientific 

			Computing</i>, pp.109-114, Las Vegas, USA, June 2005.&nbsp;

			<a href="../pub/CSC05.pdf">

			<span style="text-decoration: none">

			<img id="_x0000_i1039" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></p>

			</li>

			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">

			<b>Y. 

			Tu</b>,</span></b><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond"> 

			S. Prabhakar, A. Elmagarmid and R. Sion. QuaSAQ: An Approach to 

			Enabling End-to-End QoS for Multimedia Databases. In Proceedings of<i> 

			Intl. Conf. on Extending Database Technology (EDBT), </i>pp.694-711, 

			Herakolin, Greece., March 2004.(acceptance rate: 42/294=14.2%).&nbsp;&nbsp;&nbsp;

			<a href="../pub/edbt04.ps">

			<span style="text-decoration: none">

			<img id="_x0000_i1040" height="18" src="ps_icon.gif" width="21" border="0"></span></a><a href="../pub/edbt04.pdf"><span style="text-decoration: none"><img id="_x0000_i1041" height="18" src="pdf_icon.gif" width="40" border="0"></span></a><a href="../pub/talks/EDBT04.ppt"><span style="text-decoration: none"><img id="_x0000_i1042" height="18" src="ppt-Icon.gif" width="17" border="0"></span></a></span>

			</li>

			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond; font-weight:700">Y. 

			Tu</span></b><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">, 

			J. Sun and S. Prabhakar. Performance Analysis of A Hybrid Media 

			Streaming System. In Proceedings of <i>ACM/SPIE Conf. on Multimedia 

			Computing and Networking </i>(<i>MMCN</i>)<i>, </i>pp.69-82, San 

			Jose, CA., January 2004.(acceptance rate: 18/74=24.3%)&nbsp;&nbsp;&nbsp;

			<a href="../pub/spie04.ps">

<span style="text-decoration: none">

<img id="_x0000_i1043" height="18" src="ps_icon.gif" width="21" border="0"></span></a><a href="../pub/spie04.pdf"><span style="text-decoration: none"><img id="_x0000_i1044" height="18" src="pdf_icon.gif" width="40" border="0"></span></a><a href="../pub/talks/MMCN04.ppt"><span style="text-decoration: none"><img id="_x0000_i1045" height="18" src="ppt-Icon.gif" width="16" border="0"></span></a></span>

			</li>

			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">W. 

			Aref, A. Catlin, A. Elmagarmid, J. Fan, M. Hammad, I. Ilyas, M. 

			Marzouk, S. Prabhakar, <b>Y. Tu</b> and X. Zhu (alphabetical order). 

			VDBMS: A Testbed Facility for Research in Video Database 

			Benchmarking. In Proceedings of<i> Intl. Conf. on Distributed 

			Multimedia Systems (DMS) 2003, </i>pp.160-166.&nbsp;&nbsp;

			<a href="../pub/DMS03.pdf">

<span style="text-decoration: none">

<img id="_x0000_i1046" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span>

			</li>

		</ol>

		<h2><a name="Demo"></a>Software Demos / Short Papers</h2>

		<ol start="1">

<li>
                <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
Mehrad Eslami, <b>Yi-Cheng Tu</b>, Hadi Charkhgard, Zichen Xu, and iacheng Liu.
PsiDB: A Framework for Batched Query Processing and Optimization. In Procs. of <i>IEEE International Conference on Big Data</i> (<i>BigData</i>), pp. 6046-6048, Los Angeles, CA, USA, December 2019.<a href="../pub/BigData19P.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>
<li>
                <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
Jinghan Meng, <b>Yi-Cheng Tu</b>, and Napath Pitaksirianan. A New Polynomial-time Support Measure for Counting Frequent Patterns in Graphs. In Procs. of <i>ACM International Conference on Scientific and Statistical Database Management</i> (<i>SSDBM</i>), pp. 214-217, Santa Cruz, CA, USA, June 2019.<a href="../pub/SSDBM19.pdf"><img id="_x0000_i1068" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></li>

<li>

                        <!--img id="_x0000_i1071" height="11" src="new.gif" width="28" border="0"-->
                        <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                        <b> Y. Tu</b>, A. Kumar, D. Yu, R. Rui, and R. Wheeler.
                        Data Management Systems on GPUs: Promises and Challenges. To appear in <i>25th Scientific and Statistical Database Management Conference</i> (<i>SSDBM</i>). Baltimore, Maryland, USA., July 29-31, 2013. <a href="../pub/SSDBM13.pdf">
<span style="text-decoration: none">
<img id="_x0000_i1046" height="18" src="pdf_icon.gif" width="40" border="0"></span></a>
                        </span></li>
<li>

                      a<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                        D. Yu, H. Yang, and <b> Y. Tu</b>.
                        Parallel computing simulation of electrical excitation and conduction in a 3D human heart. To appear in <i>7th INFORMS Workshop on Data Mining and Health Informatics</i>. Phoenix, AZ, USA., November 2012. <a href="../pub/INFORMS-DMHI12.pdf">
<span style="text-decoration: none">
<img id="_x0000_i1046" height="18" src="pdf_icon.gif" width="40" border="0"></span></a>
                        </span></li>
<li>

                        <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                        <b> Y. Tu</b>, S. Chen, S. Pandit, A. Kumar and V. Grupcev.
                        Efficient SDH Computation In Molecular Simulations Data. To appear in <i>Proceedings of ACM Conference on Bioinformatics, Computational Biology, and Biomedicine </i> (<i>ACM-BCB</i>), Orlando, FL, USA., October 2012. <a href="../pub/BCB12.pdf">
<span style="text-decoration: none">
<img id="_x0000_i1046" height="18" src="pdf_icon.gif" width="40" border="0"></span></a>
                        </span></li>
<li>

                        <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                        Z. Xu, <b> Y. Tu</b>, and X. Wang.
                        PET: Reducing Database Energy Cost via Query Optimization. <i>Proceedings of Very Large Database Endowment</i> (<i>VLDB</i>), 5(12):1954-1957, August 2012. <a href="../pub/VLDB12.pdf">
<span style="text-decoration: none">
<img id="_x0000_i1046" height="18" src="pdf_icon.gif" width="40" border="0"></span></a>
                        </span></li>
<li>

                        <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                        <b> 
                        Y.Tu</b>, X. Wang, and Z. Xu. Power-Aware DBMS: Potential and Challenges. 
                        Procs. of<i> 23rd Scientific and Statistical Database Management Conference</i> (<i>SSDBM</i>), 
                        pp.598-599. Portland, OR, USA. July 20-22, 2011. <a href="../pub/SSDBM11.pdf">
<span style="text-decoration: none">
<img id="_x0000_i1046" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span>

			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
			Q. Biao, Y. Xia, R. Sathyesh, S. Prabhakar, and<b> Y. Tu</b>.<b> </b>
			uRule: A Rule-Based 
			Classification System for Uncertain Data. In Procs. of <i>
			IEEE International Conference on Data Mining</i> (<i>ICDM</i>), pp.1415-1418, 
			Miami, FL, December 6-9, 2009.
			<a href="../pub/ICDM09.pdf">
<span style="text-decoration: none">
<img id="_x0000_i1046" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>
			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">

			<b> 

			Y. Tu</b>, S. Liu, S. Prabhakar, B. Yao, and W. Schroeder. Using 

			Control Theory for Load Shedding in Data Stream Management. Procs. of<i> Intl. Conf. Data Engineering</i> (<i>ICDE</i>), 

			pp.1491-1492. Istanbul, Turkey, April 2007. </span>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">

			<a href="../pub/icde02.pdf">

			<span style="text-decoration: none">

			<a href="../pub/ICDE07.pdf">

			<img id="_x0000_i1065" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></a></span></li>

<li>
    
    <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond; font-weight:700">Y.
        
        Tu</span></b><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
            
            and S. Prabhakar. Control-Based Load Shedding in Data Stream
            
            Management Systems. PhD Workshop, in conjunction with ICDE 2006.&nbsp;
            
            <a href="../pub/ICDE06.ps">
                
                <span style="text-decoration: none">
                    
                    <img id="_x0000_i1031" height="18" src="ps_icon.gif" width="21" border="0"></span></a><a href="../pub/ICDE06.pdf"><span style="text-decoration: none"><img id="_x0000_i1032" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></p>
        
</li>
<li>
    
    <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">W. 

			Aref, A. Elmagarmid, J. Fan, J. Guo, M. Hammad, I. Ilyas, M. Marzouk, 

			S. Prabhakar, A. Rezgui, A. Teoh, E. Terzi, <b>Y. Tu</b>, A. Vakali, 

			X. Zhu (alphabetical order). A Distributed Database Server for 

			Continuous Media. Procs. of<i> Intl. Conf. on Data 
			Engineering (ICDE), </i>pp.490-491<i>. </i>San Jose, CA., March 

			2002.&nbsp;&nbsp;&nbsp;&nbsp;

			<a href="../pub/icde02.pdf">

			<span style="text-decoration: none">

			<img id="_x0000_i1047" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>

		</ol>

		<h2><a name="Journal0"></a>Book Chapters</h2>

		<ol start="1">
			<li><font face="Garamond" style="font-size: 11pt"><b>Yi-Cheng Tu</b>, Gang Ding. 
			Control-Based Database Tuning Under Dynamic Workloads. Vol. I., <i>Encyclopedia of Data Warehousing and Mining</i>, 2rd edition. pp.333-338, 
			IGI Global, 2008.</font>
			<a href="../pub/EDWM08.pdf">
			<span style="text-decoration: none">
			<img id="_x0000_i1047" height="18" src="pdf_icon.gif" width="40" border="0"></span></a>
			</li>
		</ol>
		<!--h2><a name="Submitted"></a>Submitted</h2>

		<ol start="35">
          <li>
                        <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                        <b> Y. Tu</b>, X. Wang, and B. Zeng.
                        A System for Energy-Efficient Data Management. Under minor revision for <i>
                        SIGMOD Record</i>. 
                        <a href="../pub/SIGREC12.pdf">
<span style="text-decoration: none">
<img id="_x0000_i1046" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>
        </ol -->

		<h2><a name="TR"></a>Technical Reports</h2>

		<ul>
<li>
                <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                    M. Eslami, <b>Y. Tu</b>, and H. Charkhgard.
                    A System for Batched Query Processing and Optimization. Technical Report CSE/18-088,
                    Department of Computer Science and Engineering, University of South Florida, 2018.
                    <a href="../pub/tech18-088.pdf"><span style="text-decoration: none"><img id="_x0000_i1052" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>
<li>
    <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
        Jinghan Meng, Napath Pitaksirianan, and <b>Y. Tu</b>.
        Generalizing Design of Support Measures for Counting Frequent Patterns in Graphs. Technical Report CSE/18-002,
        Department of Computer Science and Engineering, University of South Florida, 2018.
        <a href="../pub/tech18-0002.pdf"><span style="text-decoration: none"><img id="_x0000_i1052" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>
<li>
    <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
        H. Li, <b>Y. Tu</b>, and B. Zeng.
        Two-Stage Modeling and Control of Concurrent Tasks in a Multi-Kernel GPGPU Environment. Technical Report CSE/16-022,
        Department of Computer Science and Engineering, University of South Florida, 2016.
        <a href="../pub/tech16-022.pdf"><span style="text-decoration: none"><img id="_x0000_i1052" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>
<li>
                <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
                    R. Rui, H. Li, and <b>Y. Tu</b>.
                    Performance Analysis of Join Algorithms on GPUs. Technical Report CSE/14-016,
                    Department of Computer Science and Engineering, University of South Florida, 2014.
                    <a href="../pub/tech14-016.pdf"><span style="text-decoration: none"><img id="_x0000_i1052" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>

<li>
                        <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
A. Kumar, X. Zhu, <b>Y. Tu</b>, and S. Pandit.
                       Compression in Molecular Simulation Datasets. Technical Report CSE/12-061,
                        Department of Computer Science and Engineering, University of South Florida, 2012.
                        <a href="../pu
b/tech12-061.pdf"><span style="text-decoration: none"><img id="_x0000_i1052" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>
<li>


                        <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
Z. Xu, <b>Y. Tu</b>, and X. Wang.
                       Power Modeling in Database Mansgement Systems. Technical Report CSE/12-094,
                        Department of Computer Science and Engineering, University of South Florida, 2012.
                        <a href="../pu
b/tech12-94.pdf"><span style="text-decoration: none"><img id="_x0000_i1052" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>
<li>


                        <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
Z. Xu, <b>Y. Tu</b>, and X. Wang.
                       Model Evaluation of PAT: A Comprehensive Study. Technical Report CSE/12-039,
                        Department of Computer Science and Engineering, University of South Florida, 2012.
                        <a href="../pu
b/tech12-039.pdf"><span style="text-decoration: none"><img id="_x0000_i1052" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>

<li>


                        <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
A. Kumar, V. Grupcev, Y. Yuan, <b>Y. Tu</b>, and G. Shen.
                       Distance Histogram Computation Based on Spatiotemporal Uniformity in Scientific Data. Technical Report CSE/11-053,
                        Department of Computer Science and Engineering, University of South Florida, 2011.
                        <a href="../pu
b/tech11-053.pdf"><span style="text-decoration: none"><img id="_x0000_i1052" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li
>

<li>


                        <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
V. Grupcev, Y. Yuan, <b>Y. Tu</b>, S. Chen, S. Pandit and M. Weng.
                       On Fast Algorithms for Computing Spatial Distance Histograms (SDH). Technical Report CSE/11-052,
                        Department of Computer Science and Engineering, University of South Florida, 2011.
                        <a href="../pu
b/tech11-052.pdf"><span style="text-decoration: none"><img id="_x0000_i1052" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li
>

			<li><b>
                        <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">Y.
                        Tu, </span></b>
                        <span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
S. Chen, and S. Pandit.
                       Computing Spatial Distance Histograms Efficeintly in Scientific Databases. Technical Report CSE/08-103,
                        Department of Computer Science and Engineering, University of South Florida, 2008.
                        <a href="../pu
b/tr/pdh.pdf"><span style="text-decoration: none"><img id="_x0000_i1052" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li
>
             
<li><b>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">Y. 

			Tu, </span></b>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">S. 

			Prabhakar, J. Yan,<b> </b>and G. Shen. Multi-Quality Data 

			Replication in Multimedia Databases. Technical Report CSD-TR-06-009, 

			Department of Computer Sciences, Purdue University, 2006.

			<a href="../pub/tr/06009.ps">

<span style="text-decoration: none">

<img id="_x0000_i1048" height="18" src="ps_icon.gif" width="21" border="0"></span></a><a href="../pub/tr/06009.pdf"><span style="text-decoration: none"><img id="_x0000_i1049" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>

			<li><b>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">Y. 

			Tu, </span></b>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">S. 

			Liu, S. Prabhakar, and B. Yao.<b> </b>Load Shedding in Stream 

			Databases &#8211; A Control-Based Approach. Technical Report 

			CSD-TR-06-006, Department of Computer Sciences, Purdue University, 

			2006. <a href="../pub/06006.pdf">

			<span style="text-decoration: none">

			<a href="../pub/tr/06006.pdf">

			<img id="_x0000_i1050" height="18" src="pdf_icon.gif" width="40" border="0"></a></span></a></span></li>

			<li><b>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">Y. 

			Tu, </span></b>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">J. 

			Sun, M. Hefeeda, and S. Prabhakar. An Analytical Study of 

			Peer-to-Peer Media Streaming Systems. Technical Report CSD-TR-05-11, 

			Department of Computer Sciences, Purdue University, 2005.

			<a href="../pub/tr/0511.ps">

			<span style="text-decoration: none">

			<img id="_x0000_i1051" height="18" src="ps_icon.gif" width="21" border="0"></span></a><a href="../pub/tr/0511.pdf"><span style="text-decoration: none"><img id="_x0000_i1052" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>

			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">R. 

			Cheng, B. Kao, S. Prabhakar, A. Kwan, and <b>Y. Tu</b>. Adaptive 

			Stream Filters for Entity-Based Queries with Non-Value Tolerance. 

			Technical Report CSD-TR-05-03, Department of Computer Sciences, 

			Purdue University, 2005.

			<a href="../pub/tr/0503.pdf">

			<span style="text-decoration: none">

			<img id="_x0000_i1053" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>

			<li><b>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">Y. 

			Tu</span></b><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">, 

			S. Prabhakar and A. Elmagarmid. An Database-Centric Approach to 

			Enabling End-to-End QoS for Multimedia Repositories. Technical 

			Report CSD-TR-0331, Department of Computer Sciences, Purdue 

			University, 2003.&nbsp;
			<img id="_x0000_i1054" height="18" src="ps_icon.gif" width="21" border="0"></span></a><a href="../pub/tr/0331.pdf"><span style="text-decoration: none"><img id="_x0000_i1055" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>

			<li><b>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">Y. 

			Tu</span></b><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond"> 

			and S. Lei. Towards Cost-Effective Media Streaming Service: A 

			Peer-to-Peer Approach. Technical Report CSD-TR-0323, Department of 

			Computer Sciences, Purdue University, 2003.

			<a href="../pub/tr/0323.ps">

			<span style="text-decoration: none">

			<img id="_x0000_i1056" height="17" src="ps_icon.gif" width="21" border="0"></span></a><a href="../pub/tr/0323.pdf"><span style="text-decoration: none"><img id="_x0000_i1057" height="18" src="pdf_icon.gif" width="40" border="0"></span></a></span></li>

		</ul>

		<h2><a name="Non-CS"></a>Non-CS Publications</h2>

		<ul>

			<li><b>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">Y. 

			Tu.</span></b><span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond"> 

			Endogenous Gibberellins in Developing Apple Seeds in Relation to 

			Biennial Bearing. Master's thesis. Purdue University. (<a href="http://expert.ics.purdue.edu/~tuy/thesis/thesis.htm">html</a>,

			<a href="../pub/MS_thesis.pdf">pdf</a>)</span></li>

			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">S. 

			H. Li, Z. Q. Meng, H. Z. Liu, <b>Y. Tu</b>. Critical Period of 

			Flower Bud Induction of 'Red Fuji' and 'Ralls Janet' Apple Trees. </span>
			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
			<i>

			European Journal of Horticultural Sciences </i>(formerly<i>

			</i> </span>
			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">
			<i>Gartenbauwissenschaft</i>)<i> 60: 240-245.</i> </span>

			</li>

			<li>

			<span lang="EN-US" style="FONT-SIZE: 11pt; FONT-FAMILY: Garamond">S. 

			H. Li, Z. Q. Meng, H. Z. Liu, <b>Y. Tu</b>. New Methods to Research 

			the Critical Period of Flower Bud Induction in Apple Trees. <i>

			Advances in Horticulture 1994:338-341 </i>(Chinese)<i>.</i></span> 

			</li>

			</ul>

		<p>&nbsp;</p>
		<p>&nbsp;</div>

		<div id="footer" style="width: 855px; height: 38px">

			<p><font face="Verdana" size="1">Copyright 2012 | By <a href="mailto:ytu@cse.usf.edu">

			Yicheng Tu</a> | 

<script language="javascript">
    months = ['January', 'Febraury', 'March', 'April', 'May', 'June', 'July', 'August', 'September', 'October', 'November', 'December'];
    var d=new Date();
    var weekday=new Array(7);
    weekday[0]="Sunday";
    weekday[1]="Monday";
    weekday[2]="Tuesday";
    weekday[3]="Wednesday";
    weekday[4]="Thursday";
    weekday[5]="Friday";
    weekday[6]="Saturday";
    
    var d = new Date();
    (d.getFullYear());
    
    
    var theDate = new Date(document.lastModified);
    theDate.setTime((theDate.getTime()+(60*60)) )
    with (theDate) {
        document.write("<i>Last updated "+weekday[getDay()]+' '+getDate()+' '+months[getMonth()]+' '+d.getFullYear()+' '+getHours()+':'+getMinutes()+" GMT</i>")
    }
</script></font></p>

		</div>

	</div>

</body>
