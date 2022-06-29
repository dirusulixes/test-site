---
title: Workshops
type: workshops
---
<p align="center">Click anywehre on the workshop titles to see the instructors and details.</p>

**<p align="center"><font size="5">Monday 12th September, Full-day Sessions (6 hours)</font></p>**

<!-- <details>
<summary><b>Workshop 1: Estimating Exponential Random Graph Models using R</b></summary>
<p>&nbsp;</p>

**Michael T Heaney**, University of Glasgow (Michael.Heaney@glasgow.ac.uk)
<p>&nbsp;</p>

This workshop introduces the theory, methods, and R programming behind the estimation of Exponential Random Graph Models (ERGMs). Topics include endogenous model terms, specification, Markov Chain Monte Carlo (MCMC) estimation, convergence, goodness of fit, one‐mode ERGMs, two‐ mode ERGMS, and TERGMs.
</details>
 -->
<details>
<summary><b>Workshop 2: Handling Missing Network Data - Theory and Practice</b></summary>
<p>&nbsp;</p>

**Robert W Krause**, Free University Berlin (robert.w.krause@fu-berlin.de)
<p>&nbsp;</p>

Missing data are an all too common problem in network research. Due to the dependencies between the nodes, the very object of our studies, these missings constitute a far bigger problem in networks than they do for non-network data. Having given the workshop multiple times now, the empirical evidence suggests that a simple three hour workshop is not enough to properly dive into this complex problem. Therefore the workshop will be offered for six hours for the first time. In the first three hours of this workshop, we will discuss the theoretical and practical implications of missing data (What actually is missing data? What does it do to my data? How does it bias my results? Which treatments exist? What are their pros and cons?) and, crucially, relate these directly to your field(s) of study, your current missing data problems.
<p>&nbsp;</p>

In the second part of the workshop we will make use of state of the art missing data treatments (multiple imputation with Bayesian ERGMs and/or SAOMs) to get hands on experience on how to handle missing data. This part will require some basic knowledge of ERGMs and SAOMs and thus includes a crash course in these model families - if scheduling allows, a visit to the introductory workshops on (B)ERGM or SAOM will of course be helpful. Where possible (given data and prior knowledge in R and the respective model families), participants will also have the opportunity to run models on their own data to obtain first imputations for their future analyses. Additionally, the workshop will also feature potential treatments for missing nodal attribute data.
<p>&nbsp;</p>

The workshop is open to all, especially the first three hours. The second three hours, too, are open to all, but participants with prior experience in ERGMs and SAOMs will profit most from this part. However, introductory material will be provided before hand and a short introduction in the nature of these model families will be given.
</details>

<p>&nbsp;</p>
<p>&nbsp;</p>

**<p align="center"><font size="5">Monday 12th September, Morning Half-day Sessions (3 hours)</font></p>**

<details>
<summary><b>Workshop 3: Discourse Network Analyzer 3.0</b></summary>
<p>&nbsp;</p>

**Philip Leifeld**, University of Essex (philip.leifeld@essex.ac.uk)
<p>&nbsp;</p>

Discourse Network Analyzer (DNA) is a desktop application with a graphical user interface for annotating text data with actor-based statements and exporting the data as networks. It was designed for the analysis of policy debates as temporal networks. The user loads source material, such as newspaper articles, speeches, or similar into the software, defines the variables a statement is comprised of, such as person, organisation, concept, and agreement, adds statements to the text while reading, and then exports a network of statements, such as an actor x actor congruence network, a bipartite graph of actors and concepts, or a series of temporal snapshots of how the actor network evolves over time. Discourse Network Analyzer can export to visone and Ucinet, and there is an associated R package called rDNA for direct interaction between DNA and R, which facilitates data transfer and adds techniques for analysing the resulting networks.
<p>&nbsp;</p>

The new version 3.0 of Discourse Network Analyzer has been developed since 2021 and will be released this summer. The three-hour workshop introduces the software and gives an overview of what kinds of networks to export and how to analyse them in the separate network analysis software visone.
<p>&nbsp;</p>

Participants are required to install Java (e.g., Adopt OpenJDK 11 from https://adoptopenjdk.net/) and download Discourse Network Analyzer along with its manual and sample database from https://github.com/leifeld/dna as well as visone from https://visone.ethz.ch before the workshop begins.
</details>



<details>
<summary><b>Workshop 4: Introduction to Network Analysis tools in R</b></summary>
<p>&nbsp;</p>

**Michal Bojanowski**, Kozminski University (mbojanowski@kozminski.edu.pl)
**Lorien Jasny**, University of Exeter
<p>&nbsp;</p>

Those wishing to use the R programming language for network analysis now have a plethora of choices when it comes to libraries. In this workshop, we survey the main packages used for network data management, analysis, and visualization. We will cover 1) importing network data (from actual files), 2) network objects and attributes, 3) computing basic descriptives (attribute distribution, mixing matrix, density, degrees, betweenness, closeness), and 4) visualization (layouts, node aesthetics). These will be done side by side for the different packages, as well as discussion of the strengths and weaknesses of each. We conclude with time for attendees to work either on toy datasets or with their own data with help from instructors. This workshop is a unification of workshops "Using R and 'igraph' for Social Network Analysis" and "Introduction to Social Network Analysis with R and statnet" that has been offered on Sunbelt and EUSN conferences since 2011. It will serve as an introduction for those wishing to take "Moving beyond descriptives", "Using 'igraph' for SNA: advanced topics", "An introduction to ERGM with Statnet", or other Statnet-related workshops on the program.
</details>

<details>
<summary><b>Workshop 5: The Analysis of Longitudinal Social Network Data using RSIENA</b></summary>
<p>&nbsp;</p>

**Per Block**, University of Oxford (per.block@sociology.ox.ac.uk)
<p>&nbsp;</p>

This workshop is about analysing social networks panel data, understood here as two or more repeated observations of a directed graph on a given node set (usually between 20 and a few hundred nodes). The workshop teaches the statistical method to analyze such data, for which a tutorial is given in “Snijders, T.A.B., Steglich, C.E.G., and van de Bunt, G.G. (2010), Introduction to actor-based models for network dynamics (Social Networks, 32, 44-60)”. The method is implemented in RSiena, a package of the statistical system R. The workshop will demonstrate the basics of using RSiena. Attention will be paid to the underlying statistical methodology, to examples, and to the use of the software.
<p>&nbsp;</p>

The statistical model is the actor-oriented model where the nodes are actors whose choices determine the network evolution. This allows to include various network effects (reciprocity, transitivity, popularity, etc.), effects of individual covariates (covariates connected to the sender, the receiver, or the similarity between sender and receiver), and of dyadic covariates.
<p>&nbsp;</p>

An important extension is to have, in addition to the network, one or more actor variables that evolve in mutual dependence with the network; an example is a friendship network of adolescents where drinking behavior is a relevant actor variable which influences, and is influenced by, the friendship network. This leads to models for the simultaneous dynamics (‘co-evolution') of networks and behavior, which are a special option in RSiena.
<p>&nbsp;</p>

The first part of the workshop will focus on the intuitive understanding of the model and operation of the software. The second part will present models for the simultaneous dynamics of networks and behavior and other more advanced topics such as model specification, multivariate networks, and goodness of fit checking.
<p>&nbsp;</p>

Further information about this method can be found at the SIENA website (http://www.stats.ox.ac.uk/~snijders/siena).
<p>&nbsp;</p>

Prerequisites:
<p>&nbsp;</p>

Course participants should have a basic understanding of model-based statistical inference (say, logistic regression), some prior knowledge of social networks, and should have had some basic exposure to the R statistical software environment. They are expected to bring their own laptop to the course (Windows, Mac or Linux), with the R statistical software environment and the RSiena package pre-installed. Participants for whom R is new are requested to learn the basics of R before the workshop: how to run R and how to give basic R commands. This is to reduce the amount of new material to digest at the workshop itself. The Siena website (RSiena tab) has some links which can be helpful for this purpose. Further instructions will be given before the conference starts
</details>

<details>
<summary><b>Workshop 6: The goldfish package in R</b></summary>
<p>&nbsp;</p>

**Christoph Stadtfeld**, ETH Zürich
**James Hollway**, Graduate Institute, Geneva
**Marion Hoffman**, IAST
**Alvaro Uzaheta**, ETH social networks lab (alvaro.uzaheta@gess.ethz.ch)
<p>&nbsp;</p>

Goldfish is an R package for analyzing relational event data using a variety of models. In particular, it implements different types of Dynamic Network Actor Models (DyNAMs), a class of models tailored to the study of actor-oriented processes. Goldfish also implements different versions of tie-oriented relational event models.
<p>&nbsp;</p>

The workshop participants will learn to describe relational event data in R, estimate different models with the goldfish package, inspect and interpret results.
<p>&nbsp;</p>

Prerequisites:
<p>&nbsp;</p>

Course participants should be familiar with R and model-based statistical inference (such as logistic regression). They are expected to bring their laptop to the course with the R statistical software environment, the goldfish package, and dependencies installed.
<p>&nbsp;</p>

More information about the package and installation is available on Github: https://github.com/snlab-ch/goldfish
</details>

<details>
<summary><b>Workshop 7: In-person and remote social network interviewing with Network Canvas</b></summary>
<p>&nbsp;</p>

**Bernie Hogan**, University of Oxford (bernie.hogan@oii.ox.ac.uk)
**Joshua Melville**, Northwestern University
<p>&nbsp;</p>

This workshop shows how to use the free, cross-platform software Network Canvas (www.networkcanvas.com) to conduct structured or semi-structured social network interviews both in-person and via video conferencing software. Network Canvas is designed for creating personal networks with a respondent using a variety of highly visual and touch optimised controls. This includes features for doing work with name generators, rosters, free recall, dyad census, and drawing edges manually. The software is structured into a series of stages and is regularly reported by respondents as fun and engaging. Data can be exported for use in most major social network analysis packages and apps. This workshop will focus on the Interviewer app for deploying interviews and the Architect App for designing interviews.
<p>&nbsp;</p>

Order of topics:

• Guided walkthrough of an interview using the Interviewer app.
• Guided walkthrough of how it was created in the Architect app.
• Activity showing how to modify the interview in Architect followed by doing a Network Canvas interview with a peer.
•  Discussion of strategies and issues for doing remote interview sessions considering the limitations of Zoom, Google Meet, and Teams.
•  Time permitting, a brief guide to selected advanced features including skip-flow logic, prompt-based labelling, R export, and how to produce basic descriptive statistics.
<p>&nbsp;</p>

The convenor will provide example protocols and scripts for users to work with. These will be available via URL and shared shortly before the workshop. Prior materials are available via the Network Canvas documentation page: https://documentation.networkcanvas.com/
<p>&nbsp;</p>

Pre-requisites:

Course participants should arrive with a working copy of Network Canvas Interviewer and Architect installed on a personal computer such as a Mac OSX or Windows machine. Network Canvas is available from https://www.networkcanvas.com/
</details>


<p>&nbsp;</p>
<p>&nbsp;</p>

**<p align="center"><font size="5">Monday 12th September, Afternoon Half-day Sessions (3 hours)</font></p>**

<details>
<summary><b>Workshop 8: REM beyond dyads: relational hyperevent modeling with eventnet</b></summary>
<p>&nbsp;</p>

**Juergen Lerner**, University of Konstanz (juergen.lerner@uni-konstanz.de)
**Alessandro Lomi**, Università della Svizzera italiana
<p>&nbsp;</p>

Networks of social relations and communication networks frequently generate information on repeated interaction over time. This information typically takes the form of relational event sequences - streams of time-ordered events connecting social actors. Examples of relational events are common. Conversations, email communication, interaction among members of teams, participation in social gatherings or in peer-production projects, are all examples of interactive settings that may generate observable streams of relational events. In this workshop we will specifically discuss "polyadic" social interaction processes in which events can connect varying and potentially large numbers of actors simultaneously. Examples of such polyadic events (or "hyperevents") include sequences of meeting events or social gatherings, connecting all of their participants simultaneously, or multicast (i.e., "one-to-many") communication events such as emails in which one actor sends the same message to several receivers.
<p>&nbsp;</p>

This half-day workshop provides a hands-on introduction to relational hyperevent models (RHEM). We start with an informal discussion of the research questions (or network effects) that can be addressed by a RHEM analysis of meeting events extracted from contact diaries and illustrate practical analysis of the famous Davis, Gardner, and Gardner "Deep South / Southern Women" data with the open-source software eventnet (https://github.com/juergenlerner/eventnet). In the second part of this workshop we will discuss directed relational hyperevents resulting from multicast communication and illustrated by an analysis of the Enron email data.
<p>&nbsp;</p>

The workshop is targeted at participants interested in statistical modeling of networks based on relational event data - with a specific focus on polyadic, multicast, or one-to-many interaction events. Participation to the workshop does not assume any particular prior knowledge or experience with statistical models for social networks. Participants are invited to informally point us to their own research projects, which may possibly be addressed by a RHEM analysis, prior to the workshop.
<p>&nbsp;</p>

References:
<p>&nbsp;</p>

Lerner and Lomi (2020). Reliability of relational event model estimates under sampling: How to fit a relational event model to 360 million dyadic events. Network science, 8(1), 97-135.
<p>&nbsp;</p>

Lerner, Lomi, Mowbray, Rollings, and Tranmer (2021). Dynamic network analysis of contact diaries. Social Networks, 66, 224-236.
<p>&nbsp;</p>

Lerner and Lomi (2021). Relational hyperevent models for polyadic interaction networks. arXiv preprint arXiv:2112.10552.
<p>&nbsp;</p>

Lerner and Lomi (2022). A dynamic model for the mutual constitution of individuals and events. Journal of Complex Networks (to appear).
</details>

<details>
<summary><b>Workshop 9: Using igraph for SNA: advanced topics</b></summary>
<p>&nbsp;</p>

**Michal Bojanowski**, Kozminski University (mbojanowski@kozminski.edu.pl)
<p>&nbsp;</p>

Package igraph (Csardi and Nepusz 2006) is one of the main packages for network data handling, visualization and (descriptive) analysis. We take a deeper dive into the capabilities and focus on: (1) Indexing/subscripting network objects: querying nodes/ties by their properties and properties of ties/nodes they are incident upon. (2) Advanced visualization techniques (3) Studying connectivity (paths, connected components, cliques) (4) Network homophily, segregation and community detection. The workshop is designed for users familiar with the basics of R and ‘igraph,’ such as covered in the workshop “Introduction to Network Analysis Tools in R.” Elements of this workshop have been previously available as a part of “Using R and ‘igraph’ for Social Network Analysis” workshop offered on Sunbelt and EUSN conferences since 2011. This document is also designed for self-study with code examples and data from publicly available sources.
</details>

<details>
<summary><b>Workshop 10: migraph: multimodal network analysis</b></summary>
<p>&nbsp;</p>

**James Hollway**, Graduate Institute, Geneva (james.hollway@graduateinstitute.ch)
**Jael Tan**, Graduate Institute, Geneva
<p>&nbsp;</p>

The fields, arenas, or social spaces in which action takes place are never unidimensional but contain multiple types of actors and relations. Yet a common approach has been to ‘project’ any multimodal network data collected to one-mode networks to leverage existing network analytic packages. However, as outlined in Knoke, Diani, Hollway and Christopoulos’ (2021) Multimodal Political Networks, such an approach is no longer necessary as a host of techniques are readily available to those who wish to analyse multimodal networks.
<p>&nbsp;</p>

This workshop introduces migraph, a new, complementary R package for the analysis of networks including multimodal and multilevel networks. It builds upon and works natively with igraph, sna/network, and tidygraph objects, as well as edgelists and adjacency and incidence matrices, and so works well with your existing workflows. Its functions work equally well with one-mode and two-mode (and sometimes three-mode or multilevel) network data, offering appropriate normalisations, procedures, and sensible defaults for different classes and types of networks. In addition to measures for e.g. centrality and cohesion, the package includes routines for CUG and QAP tests, blockmodelling, and MRQAP that work with two-mode networks.
<p>&nbsp;</p>

The goal of this workshop is to provide an overview of multimodal network analysis and to teach participants how to conduct analyses on multimodal network data using the migraph package. The practical elements make use of R scripts, and so familiarity with R is recommended. Participants can bring their own research problems and data and, depending on the number of participants, remaining time can be used to discuss them.
</details>

<details>
<summary><b>Workshop 11: Generalized blockmodeling in R using blockmodeling package blockmodeling</b></summary>
<p>&nbsp;</p>

**Aleš Žiberna**, University of Ljubljana (Ales.Ziberna@fdv.uni-lj.si)
**Marjan Cugmas**, University of Ljubljana
<p>&nbsp;</p>

The workshop will cover generalized blockmodeling (Doreian et al., 2005; Žiberna, 2007) of mainly one-mode binary and valued networks in R using "blockmodeling" package (Žiberna, 2021). Only basic knowledge of R and networks/graphs is required. The workshop will cover matrix representation of the network, plotting of such matrices, and of course, clustering the units in the network, that is blockmodeling. Clustering units based on structural, regular and generalized equivalence will be covered. The later implies that also pre-specified blockmodeling will be covered. All aspects of blockmodeling with the blockmodeling package from preparing the data through calling the optimization function (including setting appropriate parameters) to plotting and interpreting the results will be covered. In case of sufficient time and expressed interest, blockmodeling two-mode, multilevel, and linked networks can also discussed.
</details>

<details>
<summary><b>Workshop 12: Introduction to UCINET</b></summary>
<p>&nbsp;</p>

**Srinidhi Vasudevan**, University of Greenwich (Srinidhi.Vasudevan@greenwich.ac.uk)
**Anna Piazza**, University College London
<p>&nbsp;</p>

This introductory workshop outlines the theoretical concepts of social network analysis and operationalisation of network measures through the use of the software Ucinet/Netdraw. The workshop covers the theoretical and empirical overview of the social network research field with an emphasis on the main concept of social network analysis, such as centrality, cohesion and social capital; and aspects of data collection and management for visualising and analysing networks through the software. The workshop will provide examples of applications of networks in various fields including education, management, health and bibliometric research and we will try to other examples that are relevant to the participants.
<p>&nbsp;</p>

Ucinet/Netdraw can be downloaded from https://sites.google.com/site/ucinetsoftware/home and participants are strongly encouraged to download it prior to the workshop.</details>

<p>&nbsp;</p>
<p>&nbsp;</p>

**<p align="center"><font size="5">Friday 16th September, Full-day Sessions (6 hours)</font></p>**

<details>
<summary><b>Workshop 13: Advanced RSiena workshop</b></summary>
<p>&nbsp;</p>

**Tom A.B. Snijders**, University of Groningen / University of Oxford (t.a.b.snijders@rug.nl)
<p>&nbsp;</p>

This workshop is intended for participants who have experience in working with RSiena.
<p>&nbsp;</p>

Topics treated will be the following – all in the framework of modelling network panel data using the RSiena package.
<p>&nbsp;</p>

• Multivariate networks: cross-network effects; with attention to the associated hierarchy requirements.
• Two-mode networks.
• Co-evolution of two-mode and one-mode networks.
• Valued networks (two kinds: networks with weak and strong ties; signed networks).
• Multilevel estimation using sienaBayes.
• Parameter interpretation: semi-standardized parameters: entropy-based approach to explained variation.
<p>&nbsp;</p>

SIENA website: http://www.stats.ox.ac.uk/~snijders/siena
</details>

<details>
<summary><b>Workshop 14: Using patent data for collaboration network analysis. An application with USTPO data in PatentsView</b></summary>
<p>&nbsp;</p>

**Pablo Galaso**, Universidad de la Republica (pablogalaso@gmail.com)
**Sergio Palomeque**, Universidad de la Republica
<p>&nbsp;</p>

This workshop aims to provide practical training in the use of patent data for the study of collaborative networks. Patent data is a source of information on invention developments at the level of regions, countries, cities, or other types of sub-national dimensions. One of the difficulties of this type of administrative records is that patent offices do not assign a unique identifier to inventors or owners and, for this reason, the analysis of linkages between agents is not always possible. In recent years, various efforts have been made to disambiguate patents. Among them, the PatentsView project stands out (https://patentsview.org/), which works with patents registered at the United States Patent and Trademark Office (USPTO) by applying an algorithm that analyses each registration and determines whether two agents can be the same. From this information, it is possible to construct incidence matrices linking inventors, owners (i.e. firms and organisations), cities, regions, countries or even technologies. These data may reflect either co-partnership or co-authorship between actors (e.g. two inventors involved in the same patent). However, this does not necessarily imply collaboration, which is why some scholars propose to apply Back Bone Extraction (BBE) techniques that allows to identify significant links to approach the phenomenon of collaboration.
<p>&nbsp;</p>

The workshop will provide participants with information on how to access the raw data available in the PatentsView platform, different ways of systematising this information to build networks, some BBE techniques to define meaningful links and certain specificities of the study of the topological structure in this type of networks. An overview of the meaning and usefulness of an important part of the tables available on the platform will be given. Finally, examples of research works that have used them will be presented and some of the general limitations of this type of data, as well as those particular to PatentsView, will be discussed. Special emphasis will be placed on the technologies associated with patents and how to use them from a social network analysis perspective, allowing this methodology to be applied to units of analysis that are not people or organisations, but rather technological fields.
<p>&nbsp;</p>

The specific objectives offered by the workshop to its participants are: (i) to become familiar with patent data and its usefulness for the study of network analysis, (ii) to become familiar with the main literature on the subject, (iii) to download USPTO data available through the PatentsView platform, (iv) to learn about and process the different tables included in the database, (v) to build different types of collaborative networks from this data, and (vi) to analyse these networks, emphasising some stylised facts common to this type of interactions.
<p>&nbsp;</p>

Previous knowledge of the participants: it is recommended (although not exclusive) that attendees have a basic knowledge of R and RStudio, as well as a general knowledge of Social Network Analysis.
</details>

<details>
<summary><b>Workshop 15: Egocentric network analysis with R</b></summary>
<p>&nbsp;</p>

**Raffaele Vacca**, University of Milan (raffaele.vacca@unimi.it)
<p>&nbsp;</p>

This workshop is an introduction to the R programming language and its tools to represent, manipulate and analyze egocentric or personal network data. No previous familiarity with R is required. To participate you only need a laptop with R and RStudio installed. Topics include: introduction to ego-network research and data; introduction to data structures and network objects in R; visualizing ego-networks; calculating measures on ego-network composition and structure; converting your ego-network measures to general R functions; applying your functions to many ego-networks. The workshop emphasizes R tidyverse packages for data science. We'll show how tidyverse functions can be used to easily conduct common operations in egocentric network analysis and to scale them up to large collections of ego-networks. We'll cover both base R functions and specific packages for network analysis (igraph, network, egor), data management (dplyr) and programming (purrr). We'll also provide a brief introduction to the egor package for ego-network analysis, and pointers to further resources to learn more about it. This workshop has been taught for the past nine years at several international conferences, including INSNA's Sunbelt and EUSN meetings. It draws on concepts and methods discussed in "Conducting personal network research: A practical guide" by Christopher McCarty, Miranda Lubbers, Raffaele Vacca and José Luis Molina (Guilford Press)
<p>&nbsp;</p>

 More details on the workshop's materials, history and instructor are here: raffaelevacca.com/egonet-r.
</details>

<p>&nbsp;</p>
<p>&nbsp;</p>

**<p align="center"><font size="5">Friday 16th September, Morning Half-day Sessions (3 hours)</font></p>**

<details>
<summary><b>Workshop 16: Analysis of multiplex social networks (hands on with R)</b></summary>
<p>&nbsp;</p>

**Matteo Magnani**, Uppsala University (matteo.magnani@it.uu.se)
<p>&nbsp;</p>

A multiplex network is a network where actors are connected through different types of ties, such as individuals “working together”, “being friend”, etc. These different types of connections are also known as layers.
<p>&nbsp;</p>

The workshop covers several topics in multiplex network analysis, including a selection of: community detection, layer comparison methods, actor measures, data exploration and network generation, depending on time and interest of the participants. For each topic, a quick presentation of the relevant theory and methods is followed by a practical application on a real pedagogical dataset. Part of the presented theory is covered in the book “Multilayer Social Networks” and in recent survey articles, such as “Community detection in multiplex networks” (ACM Computing Surveys) and “Quantifying layer similarity in multiplex networks: a systematic study” (Royal Society Open Science), and in several research papers developed in different fields by different authors.
<p>&nbsp;</p>

The short theoretical presentations are all meant to provide the necessary knowledge to perform practical exercises with network analysis software. This is an updated version of a workshop already given at previous conferences (including SunBelt and EUSN).
<p>&nbsp;</p>

In this workshop we will use the multinet library, available on the CRAN archive since 2017. Only limited knowledge of R is needed, as we will mainly use library functions. However, knowledge of R and igraph can be useful to understand some topics in more detail.
<p>&nbsp;</p>

The proposed duration is 3 hours (including breaks), and the target are researchers at any level of seniority interested in an introduction to multiplex networks.
<p>&nbsp;</p>

The lecturer has authored several research and survey articles on multilayer networks during the last 11 years, is the main author of the software, and is a Distinguished University Teacher at Uppsala University.
</details>

<details>
<summary><b>Workshop 17: Moving beyond descriptives: basic hypothesis testing with R/Statnet</b></summary>
<p>&nbsp;</p>

**Lorien Jasny**, University of Exeter (L.Jasny@exeter.ac.uk)
<p>&nbsp;</p>

This workshop will cover basic statistical methods for network analysis within the R/statnet platform. The approach taken is practical rather than theoretical, with emphasis on simple, robust methods for hypothesis testing and exploratory data analysis of single and multi-network data sets. Topics include: permutation tests for marginal relationships between node or graph-level indices and covariates and when you can use standard regression methods; Monte Carlo tests for structural biases; Quadratic Assignment Procedure (QAP), network correlation, autocorrelation, and regression; baseline models and conditional uniform graph tests; and exploratory multivariate analysis of multi-network data sets. We will also cover interpreting R code in existing functions and writing your own functions. We discuss briefly how these methods relate to Exponential Random Graph models (ERGM), but the focus of this workshop is on non-ERGM statistical methods.
<p>&nbsp;</p>

Prerequisites: Some prior exposure to R, but extensive experience is not assumed. Completion of the “Introduction to Network Analysis with R” workshop session is suggested for those new to R. Familiarity with the basic concepts of descriptive network analysis (e.g., centrality scores, network visualization) is strongly recommended. Participants are recommended to bring a laptop with R, RStudio, and statnet installed. Sample data and code will be provided.
</details>

<details>
<summary><b>Workshop 18: Tidy Networks: the tidyverse and tidygraph for social network analysis in R</b></summary>
<p>&nbsp;</p>

**Matthew Smith**, Edinburgh Napier University (M.Smith3@napier.ac.uk)
**Yasaman Sarabi**, Edinburgh Business School, Heriot-Watt University
<p>&nbsp;</p>

This 3-hour workshop provides an introduction to the R programming language for those without any previous or limited experience. It will introduce the tidyverse – a set of functions and packages for data processing, cleaning, and visualisation in R. In particular, we will focus on dplyr for data processing, ggplot2 for visualisation, and Rmarkdown for creating reports. We will go on to demonstrate how the tidyverse can be applied to social network analysis - more specifically through the use of the tidygraph package. The tidygraph permits you to utilise the underlying grammar structure of the tidyverse when dealing with graph objects in R. By using the tidygraph package you can manage edgelists and network attributes in a single object, along with implementing analysis on these objects. The tidyverse allows you to create tidy data frames, whilst the tidygraph allows you to create tidy graph objects – or tidy networks!
<p>&nbsp;</p>

By the end of the session participants should be able to:
<p>&nbsp;</p>

• Use R and RStudio.
• Make use of the tidyverse for data processing – more specifically preparing datasets for SNA.
• Visualising networks in R using ggplot2 (part of the tidyverse) and tidygraph.
• Create tidygraph objects and undertake some initial network analysis using the tidygraph package.
<p>&nbsp;</p>

Target group: Individuals new to R, or those with limited R experience. These users will benefit from gaining an insight into how to use R for data processing and social network analysis following the tidy philosophy.
<p>&nbsp;</p>

Requirements: No prior knowledge of R is required as an introduction will be provided.
<p>&nbsp;</p>

Matthew Smith is a lecturer at Edinburgh Napier University. Yasaman Sarabi is an assistant professor at Edinburgh Business School, Heriot-Watt University. Both have experience delivering similar workshops at Sunbelt and EUSN conferences, including EUSN 2019 where this workshop was offered.
</details>

<details>
<summary><b>Workshop 19: Introduction to visone</b></summary>
<p>&nbsp;</p>

**Julian Müller**, ETH Zürich / Università della Svizzera italiana (julian.mueller@gess.ethz.ch)
<p>&nbsp;</p>

This workshop offers a hands-on introduction to visone (ital. mink), a free software tool that combines comprehensive means for analysis with unique visualization capabilities. The software features many standard and non-standard methods for analysis and visualization of networks, and offers a powerful graphical user interface.
<p>&nbsp;</p>

After a brief overview of visone's design and features, we will explore some of visone's core functionality. Using example network analyses, we will produce presentations of findings step-by-step, starting from input data and arriving at publication-quality information visualizations.
<p>&nbsp;</p>

Visone is written in Java and freely available at http://www.visone.info. It is advisable to bring a laptop running Windows, MacOS, or Linux, preferably with Java 8 or newer already installed.
</details>

