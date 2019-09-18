---
layout: page
title: Research
description: Carlos Cotrini's research
---

#### <u>The Next 700 Policy Miners: A Universal Method to Build Policy Miners</u>

Carlos Cotrini, Luca Corinzia, Thilo Weghorn, David Basin

*Different methods have been proposed to mine attribute-based access control (ABAC) rules from logs. In practice, these logs are sparse in that they contain only a fraction of all possible requests. However, for sparse logs, existing methods mine and validate overly permissive rules, enabling privilege abuse. We define a novel measure, reliability, that quantifies how overly permissive a rule is and we show why other standard measures like confidence and entropy fail in quantifying overpermissiveness. We build upon state-of-the-art subgroup discovery algorithms and our new reliability measure to design Rhapsody, the first ABAC mining algorithm with correctness guarantees: Rhapsody mines a rule if and only if the rule covers a significant number of requests, its reliability is above a given threshold, and there is no equivalent shorter rule. We evaluate Rhapsody on different real-world scenarios using logs from Amazon and a computer lab at ETH Zurich. Our results show that Rhapsody generalizes better and produces substantially smaller rules than competing approaches.* [DOI](doi.org/10.1109/EuroSP.2018.00011)

#### <u>Mining ABAC Rules from Sparse Logs (EuroS&P 2018)</u>

Carlos Cotrini, Thilo Weghorn, David Basin

*Different methods have been proposed to mine attribute-based access control (ABAC) rules from logs. In practice, these logs are sparse in that they contain only a fraction of all possible requests. However, for sparse logs, existing methods mine and validate overly permissive rules, enabling privilege abuse. We define a novel measure, reliability, that quantifies how overly permissive a rule is and we show why other standard measures like confidence and entropy fail in quantifying overpermissiveness. We build upon state-of-the-art subgroup discovery algorithms and our new reliability measure to design Rhapsody, the first ABAC mining algorithm with correctness guarantees: Rhapsody mines a rule if and only if the rule covers a significant number of requests, its reliability is above a given threshold, and there is no equivalent shorter rule. We evaluate Rhapsody on different real-world scenarios using logs from Amazon and a computer lab at ETH Zurich. Our results show that Rhapsody generalizes better and produces substantially smaller rules than competing approaches.* [DOI](doi.org/10.1109/EuroSP.2018.00011)


#### <u>Analyzing First-Order Role-Based Access Control (CSF 2015)</u>

Carlos Cotrini, Thilo Weghorn, Manuel Clavel, David Basin

*We propose FORBAC, an extension of Role-Based Access Control (RBAC) based on first-order logic. FORBAC is expressive enough to formalize a wide range of access control policies. However, it is simple enough so that relevant policy analysis queries can be analyzed in NP, which we argue is a natural complexity class for this problem. To analyze queries efficiently, we reduce them to the problem of satisfiability modulo appropriate theories, and use off-the-shelf SMT solvers. We evaluate FORBAC's expressiveness and our approach to policy analysis in a case study, analyzing access control in a European bank.* [DOI](doi.org/10.1109/CSF.2015.8)


#### <u>Deciding Safety and Liveness in TPTL (Information Processing Letters 2014)</u>

Carlos Cotrini, Felix Klaedtke, Eugen Zalinescu, David Basin

*We show that deciding whether a TPTL formula describes a safety property is EXPSPACE-complete. Moreover, deciding whether a TPTL formula describes a liveness property is in 2-EXPSPACE. Our algorithms for deciding these problems extend those presented by Sistla [1] to decide the corresponding problems for LTL.* [DOI](doi.org/10.1016/j.ipl.2014.06.005)


#### <u>Primal Infon Logic with Conjunctions as Sets (TCS 2014)</u>

Carlos Cotrini, Yuri Gurevich, Ori Lahav, Artem Melentyev

*Primal infon logic was proposed by Gurevich and Neeman as an efficient yet expressive logic for policy and trust management. It is a propositional multimodal subintuitionistic logic decidable in linear time. However in that logic the principle of the replacement of equivalents fails. For example, (𝑥∧𝑦)→𝑧 does not entail (𝑦∧𝑥)→𝑧, and similarly 𝑤→((𝑥∧𝑦)∧𝑧) does not entail 𝑤→(𝑥∧(𝑦∧𝑧)). Imposing the full principle of the replacement of equivalents leads to an NP-hard logic according to a recent result of Beklemishev and Prokhorov. In this paper we suggest a way to regain the part of this principle restricted to conjunction: We introduce a version of propositional primal logic that treats conjunctions as sets, and show that the derivation problem for this logic can be decided in linear expected time and quadratic worst-case time.* [DOI](https://doi.org/10.1007/978-3-662-44602-7_19)


#### <u>Basic Primal Infon Logic (Journal of Logic and Computation 2013)</u>

Carlos Cotrini, Yuri Gurevich

*Primal infon logic (PIL) was introduced in 2009 in the framework of policy and trust management. In the meantime, some generalizations appeared, and there have been some changes in the syntax of the basic PIL. This article is on the basic PIL, and one of our purposes is to ‘institutionalize’ the changes. We prove a small-model theorem for the propositional fragment of basic primal infon logic (PPIL), give a simple proof of the PPIL locality theorem and present a linear-time decision algorithm (announced earlier) for PPIL in a form convenient for generalizations. For the sake of completeness, we cover the universal fragment of basic PIL. We wish that this article becomes a standard reference on basic PIL.* [DOI](https://doi.org/10.1093/logcom/ext021)


#### <u>Transitive Primal Infon Logic (The Review of Symbolic Logic 2013)</u>

Carlos Cotrini, Yuri Gurevich

*Primal infon logic was introduced in 2009 in connection with access control. In addition to traditional logic constructs, it contains unary connectives p said indispensable in the intended access control applications. Propositional primal infon logic is decidable in linear time, yet suffices for many common access control scenarios. The most obvious limitation on its expressivity is the failure of the transitivity law for implication: 𝑥→𝑦 and 𝑦→𝑧 do not necessarily yield 𝑥→𝑧. Here we introduce and investigate equiexpressive “transitive” extensions TPIL and TPIL* of propositional primal infon logic as well as their quote-free fragments TPIL0 and TPIL0* respectively. We prove the subformula property for TPIL0* and a similar property for TPIL*; we define Kripke models for the four logics and prove the corresponding soundness-and-completeness theorems; we show that, in all these logics, satisfiable formulas have small models; but our main result is a quadratic-time derivation algorithm for TPIL* * [DOI](https://doi.org/10.1017/S1755020312000366)

<!-- Note: this is how to write a comment in HTML. Everything in here won't show up on your webpage.-->

<!--
To increase the size of the title, use fewer # in front of the paper title.
To decrease the size of the title, use more #. 
To remove the italics, remove the * before and after the description
To remove the underline from the title, remove the <u> tags (<u> and </u>)
-->
