---
layout: page
title: WRS - Abstracts
description:
sitemap:
  priority: 1.0
  lastmod: 2018-06-07
  changefreq: weekly
---

## Abstracts of the Talks


### From Quantitative Models to Reaction Systems
__Sepinoud Azimi, Turku, Finland__

The two fundamental principles of reaction systems, the non-permanency and the threshold assumption, make the reaction system framework fundamentally different than that of the quantitative modelling. Whereas the quantitative model is driven by the numerical setup-based competition, the reaction system framework only allows the specification of logical dependencies in terms of facilitators and inhibitors. The reaction system framework forces the modeler to make explicit a number of assumptions about the model, that in other framework are typically hidden in some numerical values. Moreover, the explicit list of inhibitors is shedding light into the causality relations between the various reactions in the system. This kind of insight is highly valuable and may be very difficult to obtain through other frameworks, either from the presentation of the model, or from numerical simulations. We demonstrate through some examples the ability of the reaction system framework to capture the intricate behaviour of ODE-based models.

### Open Repository for Research on Reaction Systems
__Sepinoud Azimi, Turku, Finland__

Reaction Systems open repository is an interactive platform to share the increasing bibliography on reaction systems research and to help coagulate our community. It provides an interactive way of collaborating: researchers may share their publications, search for publications and/or authors, comment on others’ publications, start collaborating around new ideas and build groups interested in similar topics. The repository is based in GitHub to provide an easy, user-friendly interface to the platform, including easy options to upload the bibliographical information of a publication. The repository can be accessed at [https://github.com/RS-Repo/library/issues](https://github.com/RS-Repo/library/issues). Detailed information on how to add a publication to the repository is provided at [https://github.com/RS-Repo/library/wiki/Guide-to-submit-a-new-issue](https://github.com/RS-Repo/library/wiki/Guide-to-submit-a-new-issue).

### Quantitative vs Qualitative models in Biology
__Moderators: Sepinoud Azimi, Turku, Finland and Daniela Besozzi, Milano, Italy__

Although a number of mathematical formalisms and computational methods can be used to analyze the emergent properties of biological systems, there exists no universal strategy to choose the most adequate modeling approach for any given biological system of interest. Generally speaking, models 
in Biology can be classified as quantitative or qualitative. Quantitative (parameterized) models take into account all available information about the molecular amounts of chemical species, the biochemical reactions and their kinetic rates, to the aim of investigating the temporal evolution of the system and its functioning in normal or altered conditions. Qualitative (non parameterized) models provide a description of biological systems at a higher level of abstraction, therefore allowing either to analyze static topological features or to detect the occurrence of dynamical attractors without any specific measure of ``how much'' the system changed in time. The aim of this session is to foster the discussion about the power of quantitative vs qualitative models in Biology - also considering bio-inspired computational frameworks that have been frequently used to model biological systems - making an effort to place reaction systems within this bigger picture. 

### Biological Aspects of Reaction Systems
__Daniela Besozzi, Milano, Italy__

Thanks to the assumption of facilitation and inhibition regulations, as well as to the properties of non-permanency and threshold nature of resources, reaction systems are able to capture some essential features of biochemical reactions, offering a conceptual framework to investigate the information processing in cells. The aim of this talk is to provide some basics notions of biological aspects that underlie reaction systems. We will start by introducing the main concepts of biochemical energetics (e.g., stoichiometry, reaction directionality, kinetics and thermodynamics, catalysis), as a mean to understand how the interplay among biochemical reactions controls different layers of cellular functioning (gene expression, signal transduction, metabolism). A bird's-eye view over qualitative vs. quantitative, static vs. dynamic modeling approaches for biological systems (e.g., Boolean networks, biochemical reaction networks, ordinary differential equations) will then be given, to highlight the main differences between reaction systems and other mathematical formalisms. Finally, a few emergent phenomena that are typical of biological systems (e.g. multistability, adaptation, robustness, evolution) will be briefly introduced to open the discussion for their possible exploitation in the context of reaction systems.

### Chemical Reaction Networks and Reaction Systems
__Robert Brijder, Hasselt, Belgium__

The well-studied research field of chemical reaction networks is concerned with fundamental models of chemical reactions occurring in well-mixed solutions. Chemical reaction networks have been used to study both biological and chemical processes occurring in nature as well as human-designed processes occurring in wetlabs. In particular, human-designed chemical reaction networks have been shown, both in theory and in the wetlab, to be able to perform computations. In this way, chemical reaction networks form a high-level programming language.

Reaction systems, introduced by Ehrenfeucht and Rozenberg about 10 years ago, form a fast-growing research field that is concerned with the study of processes in open systems (like living cells) that result from biochemical reactions.

In this talk we review chemical reaction networks and compare them with reaction systems. In particular, we discuss several fundamental differences between these models. We also discuss some open problems that naturally emerge when comparing chemical reaction networks with reaction systems.

### Networks of Bio-inspired Language Processors
__Erzsébet Csuhaj-Varjú, Budapest, Hungary__

A network of language processors (an NLP system, for short) consists of a finite number of language identifying devices associated with the nodes of a virtual graph. The processors operate on strings by performing rewriting and communication steps alternately, the network functions by changing its state. The current state of the system is given by the active processors at the nodes and  the sets (or multisets) of strings present at these components. Particularly interesting variants of NLP sytems are those ones which are inspired by biology (bio-inspired language processors ) and which model communities of living systems or tissues of cells. In the talk, we discuss two types of bio-inspired NLP systems, namely, networks of Lindenmayer systems and networks of evolutionary processors. In the latter case the operations used by the processors corresponds to point mutations. We demonstrate that these types of NLP systems even with restricted size parameters and with pure communication protocols are Turing equivalent. If massive parallelism is allowed in the rewriting and communication steps, then these NLP systems are able to solve NP complete problems in linear time. We also present some interesting properties on the growth of the string population in the network as a whole and at the individual components.

### Reaction Systems, Complexity and Bits of Category Theory
__Enrico Formenti, Nice, France__

Reaction systems (RA) are a very interesting example of (finite) discrete dynamical systems. However, the precise description of their dynamics often requires a huge amount of computational resources. Indeed, that seems to be a common drawback to many kinds of discrete dynamical systems. We therefore generalize questions over RA to questions over generic discrete dynamical systems providing general commons complexity bounds for the most interesting questions. These results will be obtained using descriptive complexity and (simple) ideas from category theory.

### Forbidding-Enforcing Systems, a Precursor of Reaction Systems
__Daniela Genova, Jacksonville, FL, USA__

Inspired by molecular processes, the forbidding and enforcing paradigm was introduced by Ehrenfeucht and Rozenberg as a way to define families of languages based on two sets of boundary conditions. A forbidding set disallows certain combinations of strings (molecules), which models inhibition. Enforcing conditions require the presence of new strings (molecules) if some combinations of strings are already present, modeling the evolution of a molecular system. A topological investigation showed that fe-systems define families of languages completely different than Chomsky’s classes. Later, a variant of fe-systems was considered where a fe-system defines a single language (rather than a family). It was shown that such finite fe-systems define a subclass of the regular languages, which lies strictly between strictly locally testable and locally testable languages. Other types of fe-systems have been proposed in the literature in the context of graphs, categories, membrane systems, and more. There are some similarities between fe-systems and reaction systems as forbidding sets model inhibition and products in reaction systems are enforced. At the same time these two types of systems act almost orthogonal, e.g., a result in a reaction system is a union of products whereas a union of fe-systems results in an intersection of allowed sets. The talk will discuss differences and similarities between fe- systems and reaction systems.

### Dynamic Causalities in Reaction Systems and their Applications
__Roberta Gori, Pisa, Italy__

The overall behavior of a reaction system model is driven by the (set of) contextual elements which are received from the external environment at each step. Such elements join the current state of the system and can enable or disable reactions. The computation of the next state of a reaction system is a deterministic procedure. However, since the contextual elements that can be received at each step can be any subset of the support set the overall system dynamics is non deterministic. Brijder, Ehrenfeucht and Rozenberg investigated dynamic causalities in reaction systems by introducing the idea of predictors. Assume you are interested in the production of a molecule s after a fixed number of steps, their idea was to devise the set of objects that have to be observed in the environment to decide whether molecule s will be produced or not after the required number of steps. We continue this investigation by pushing forward their original ideas and introduce a formula based predictor, that is a logic formula that precisely characterizes all the environments that lead to the production of molecule s after the fixed number of steps. Such predictor can be computed by an effective operator. The simple concept of specialized predictor is also introduced, that is a propositional logic formula that predicts the production of a molecule of interest after a fixed number of steps only for a subset of context sequences satisfying some given temporal formula. Formula and specialised formula based predictor allows us to fully understand causal dependencies between objects. For this reason, we applied our techniques to the reaction system modelling the cell-cycle regulatory network of budding yeast. The idea was to characterise all the initial configurations that allows the system to reach its stationary state G. The predictors of state G in different number of steps shows how our method can be used to discover and prove biological properties.

### Graph Isomorphism and Equivalence of Reaction Systems
__Natasha Jonoska, Tampa, FL, USA__

We consider global dynamics of reaction systems as introduced by Ehrenfeucht and Rozenberg. The dynamics is represented by a directed graph, the so-called transition graph, and two reaction systems are considered equivalent if their corresponding transition graphs are isomorphic. We introduce the notion of a skeleton (a one-out graph) that uniquely determines a directed graph. We provide the necessary and sufficient conditions for two skeletons to define isomorphic graphs. This provides a necessary and sufficient condition for two reactions systems to be equivalent, as well as a characterization of the directed graphs that correspond to the global dynamics of reaction systems. 

### Evolving Reaction Systems
__Jetty Kleijn, Leiden, The Netherlands__

Reaction systems were introduced as a formal model of interactions between biochemical reactions. The processes taking place in a reaction system are driven by reactions. A central feature of reaction systems is the invariance of the set of reactions available. In this lecture, we generalize this setup to evolving reaction systems by allowing the set of available reactions to change as a process progresses from state to state. This generalization is motivated by computational and biological considerations, in particular the evolution of biological systems. As a main technical result, we discuss the Invisibility Theorem which allows for an evolution of a system which is not externally observable. We also discuss the notion of enabling equivalence between sets of reactions. Joint work with Andrzej Ehrenfeucht, Maciej Koutny, and Grzegorz Rozenberg.

### Petri Nets and Reaction Systems
__Maciej Koutny, Newcastle, UK__

This talk will discuss how Petri nets could be used to provide a faithful semantics of reaction systems, a formal framework for the investigation of processes carried by biochemical reactions. It will propose and discuss possible approaches to this problem using some existing Petri net classes and concurrency concepts, such as maximal parallelism. After that it will present a class of Petri nets, called set-nets, which provide a computational model matching very closely that exhibited by reaction systems. The key difference between standard Petri nets and set-nets is that the former support multiset-based token arithmetic, whereas the latter support set-based operations on tokens. Joint research with Jetty Kleijn, Lukasz Mikulski and Grzegorz Rozenberg.

### Reaction Systems, Transition Systems, and Equivalences
__Maciej Koutny, Newcastle, UK__

Reaction systems originated as a formal model for processes inspired by the functioning of the living cell. The underlying idea of this model is that the functioning of the living cell is determined by the interactions of biochemical reactions and these interactions are based on the mechanisms of facilitation and inhibition. Since their inception, reaction systems became a well-investigated novel model of computation. This talk will discuss a systematic framework for investigating a whole range of equivalence notions for reaction systems. Some of the equivalences are defined directly on reaction systems while some are defined through transition systems associated with reaction systems. In this way one can establish a new bridge between reaction systems and transition systems. In order to define equivalences which capture various ways of interacting with an environment, the talk will present models of the environment which evolve in a finite state fashion. Joint research with Jetty Kleijn, Lukasz Mikulski and Grzegorz Rozenberg.

### Networks of Reaction Systems
__Anna Labella, Rome, Italy__

We study the behaviour (processes) of reaction systems where the context is not arbitrary, but it has its own structure. In particular, we consider a model where the context for a reaction system originates from a network of reaction systems. Such a network is formalised as a graph with reaction systems residing at its nodes, where each reaction system contributes to defining the context of all its neighbours. We provide a framework for investigating the behaviour of reaction systems receiving contexts from networks of reaction systems, give a characterisation of their state sequences, and consider different topologies of context networks. Joint research with Paolo Bottoni and Grzegorz Rozenberg.

### Cellular Automata and Reaction Systems
__Luca Manzoni, Milano, Italy__

Cellular Automata (CA) are one of the oldest bio-inspired computational model, going back to Ulam and Von Neumann for its definition. CA share many aspects with reactions systems, in particular their definition according to simple rules that, combined, generate complex behaviours. We will show how reaction systems can be considered an extension of finite CA and how complexity results on one model can be used to provide bounds on the complexity of the same problem in the other model. We also introduce the concept of ``space'' in reaction systems and how it can be used to understand the relation between the two models. Joint research with Alberto Dennunzio, Enrico Formenti, and Antonio E. Porreca.

### Complexity of Interactive Processes of Reaction Systems
__by Luca Manzoni, Milano, Italy__

Reaction systems provide a compact and mathematically elegant way of defining finite discrete-time dynamical systems. The dynamical behaviour that they can generate, however, can be far from simple. Fixed point, attractors (either local or global), long periods and transients are all possible behaviours. We studied the computational complexity of determining the existence of such dynamical behaviours given a reaction system. Most dynamical behaviours can be verified in two ways: given a point, it might be necessary to find if a preimage of it exists, i.e., it is necessary to ``go back'' in the dynamics. In this case most decision problems are either NP-complete or coNP-complete. In other cases to verify the existence of a certain property it might be necessary to follow the evolution of the system for arbitrarily many time steps. This usually results in problems that are PSPACE-complete. Joint research with Alberto Dennunzio, Enrico Formenti, and Antonio E. Porreca.

### State Sequences of Interactive Processes of Reaction Systems
__Luca Manzoni, Milano, Italy and Antonio E. Porreca, Milano, Italy__

In this tutorial lecture we discuss state sequence as formalization of dynamic evolution of reaction systems. We will introduce/recall basic notions concerning state sequences and then give a number of their basic properties. We will focus on state sequences of context-independent interactive processes, but we will conclude the tutorial with some observations on state sequences of processes which are interacting with the environment, i.e., with context.

### Modeling Gene Regulatory Networks with Reaction Systems
__Paolo Milazzo, Pisa, Italy__

Gene regulatory networks are at the basis of cell functioning. Cells adapt their behaviour to environmental changes by activating or deactivating genes expressing proteins that are responsible for specific behaviours. One of the most classical examples of gene regulation is the Lac operon in Escherichia coli. The bacterium synthesizes proteins for lactose degradation only when lactose is available in the environment. When lactose is not available, a few interactions between genes cause protein synthesis to stop. Gene regulatory networks are often very complex. Even by focusing on a specific cell function, the number of genes that have to be considered to study the regulation processes are often in the order of tens or hundreds. Hence, modelling techniques become essential in order understand dynamical properties of these systems. Interactions between genes are based essentially on promotion and inhibition activities. These activities can take different biological forms, but in an abstract way they can be seen simply as positive and negative conditions for the activation (i.e. the expression) of each gene. Boolean networks are often used to study gene regulatory networks in an abstract way. In particular, boolean threshold networks are often used, in which conditions for the activation of a gene can be expressed in terms of the difference between the number of its promoting and inhibiting genes. Reaction Systems are particularly suitable for the description of gene regulatory networks. We describe a systematic translation of boolean threshold networks into Reaction Systems that allows gene regulatory networks to be studied by simulating the dynamics of the obtained Reaction Systems.

### Reaction Automata
__Fumiya Okubo, Tokyo, Japan__

Inspired by the framework of reaction systems, reaction automata were introduced in 2011 as formal computing devices. Reaction automata are regarded as language acceptors with multiset rewriting mechanism whose functioning are controled by reactants, inhibitors and products akin to those of reaction system. In this talk, we introduce the formal definitions of reaction automata of several types subject to input modes and transition modes. Then, we show some results regarding computationally Turing universality and space-bounded subclasses of reaction automata. Finally, determinism and reversibility in reaction automata are discussed.

### Model Checking for Reaction Systems
__Wojtek Penczek, Warsaw, Poland__

The lecture is about three model checking approaches for reaction systems. The first one deals with a branching time temporal logic (rsCTL). The logic is interpreted over the models for the context restricted reaction systems that generalise standard reaction systems by controlling context sequences. The second approach concerns linear time temporal logic for reaction systems (rsLTL) However, in practical applications, a reaction system may only be partially specified, and effective calculation of the missing details would provide an attractive design approach. To develop such an approach, this lectures introduces reaction systems with parameters representing the unknown parts of the reactions. The main result is a method which attempts to replace these parameters in such a way that the resulting reaction system operating in a given external environment satisfies a given temporal logic formula of rsLTL.

### Reaction Systems and Graph Transformation
__Grzegorz Rozenberg, Leiden, The Netherlands and Boulder, CO, USA__

A typical approach to graph transformation (graph rewriting, graph grammars) is based on ``cutting and pasting'': applying a graph transformation rule to a graph G requires an identification of a subgraph H of G to be removed, replacing it by a subgraph M, and then reconnecting M to the graph G' which results by removing H from G.

We present a novel approach to graph transformation, where cut and paste approach is replaced by ``surfing'' on the universe graph B. Transforming a subgraph T of B to a subgraph U of B corresponds now to a single surfing step leading in B from T to U. This idea originates in exploration systems, where the state sequences of interactive processes in reaction systems exploring zoom structures correspond to surfing from location to location on the graphs of zoom structures (which formalize depositories of knowledge).

This novel approach is formalized through graph-based reaction systems which generalize the traditional (set-based) reaction systems.

Joint research with Hans-Joerg Kreowski.

### Reaction Systems and Zoom Structures
__Grzegorz Rozenberg, Leiden, The Netherlands and Boulder, CO, USA__

In this talk we introduce/recall main notions (with the underlying motivations and intuitions) behind both reaction systems and zoom structures. We will demonstrate how combining reaction systems with zoom structures provides an elegant general framework for exploring a discipline of knowledge. Zoom structures formalize a static depository of knowledge while reaction systems formalize dynamic processes of exploring this knowledge. The talk is of a tutorial style and is intended as a gentle introduction to this broad research area. Joint research with Andrzej Ehrenfeucht.

### Linking Reaction Systems with Rough Sets
__Andrzej Skowron, Warsaw, Poland__

Reaction systems is a model of interactive computations which was motivated by the functioning of the living cells. It is an idealized mathematical model abstracting from the complex nature of the physical systems where only partial, incomplete information is available (e.g., about their states). The framework of rough sets was developed to deal with such incomplete information, where situations/states are perceived by a set of attributes. So, in linking reaction systems with rough sets one can deal with the issue of perceiving physical objects by attributes. However, we also suggest that a deeper understanding of how the values of attributes are acquired/computed through interactions with the physical world may lead to new results concerning exploration systems, e.g., related to controlling of implementations of reaction systems in the physical reality. All this is done from a somewhat broader perspective of the relationship between pure mathematical models and realistic models that take into account the limitation of perceiving physical reality.
This is a joint work with Soma Dutta, Andrzej Jankowski, and Grzegorz Rozenberg.
