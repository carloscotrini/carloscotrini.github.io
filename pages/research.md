---
layout: page
title: Research
description: Carlos Cotrini's research
---

#### <u>Mining ABAC Rules from Sparse Logs (EuroS&P 2018)</u>
*Different methods have been proposed to mine attribute-based access control (ABAC) rules from logs. In practice, these logs are sparse in that they contain only a fraction of all possible requests. However, for sparse logs, existing methods mine and validate overly permissive rules, enabling privilege abuse. We define a novel measure, reliability, that quantifies how overly permissive a rule is and we show why other standard measures like confidence and entropy fail in quantifying overpermissiveness. We build upon state-of-the-art subgroup discovery algorithms and our new reliability measure to design Rhapsody, the first ABAC mining algorithm with correctness guarantees: Rhapsody mines a rule if and only if the rule covers a significant number of requests, its reliability is above a given threshold, and there is no equivalent shorter rule. We evaluate Rhapsody on different real-world scenarios using logs from Amazon and a computer lab at ETH Zurich. Our results show that Rhapsody generalizes better and produces substantially smaller rules than competing approaches.* [DOI](10.1109/EuroSP.2018.00011)


#### <u>Analyzing First-Order Role-Based Access Cotnrol (CSF 2015)</u>
*We propose FORBAC, an extension of Role-Based Access Control (RBAC) based on first-order logic. FORBAC is expressive enough to formalize a wide range of access control policies. However, it is simple enough so that relevant policy analysis queries can be analyzed in NP, which we argue is a natural complexity class for this problem. To analyze queries efficiently, we reduce them to the problem of satisfiability modulo appropriate theories, and use off-the-shelf SMT solvers. We evaluate FORBAC's expressiveness and our approach to policy analysis in a case study, analyzing access control in a European bank.* [DOI](10.1109/CSF.2015.8)


<!-- Note: this is how to write a comment in HTML. Everything in here won't show up on your webpage.-->

<!--
To increase the size of the title, use fewer # in front of the paper title.
To decrease the size of the title, use more #. 
To remove the italics, remove the * before and after the description
To remove the underline from the title, remove the <u> tags (<u> and </u>)
-->
