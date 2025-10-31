---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.Phil, The HongKong University of Science and Technology (Guangzhou)
  * AI thrust&INFO Hub 
    * Majoring in Artificial Intelligence(AI, CGA:3.323/4)
<p align="right">2024-Present</p>

* B.S, China University of Petroleum Beijing
  * Department of Mathematics, School of Arts and Sciences
    * Majoring in Statistics(STAT,GPA:3.58/4)
   <!-- * Relevant Courses: Mathematical analysis; Advanced algebra; Real functions and general function analysis;
     Probability theory; Mathematical statistics; Stochastic processes.   -->
<p align="right">2020-2024</p>

Research experience
======
*Postgraduate(2024-Present):*

**LLM-Based Intelligent Companion AI Digital Humans with Consciousness and Memory**

**Project summary**: In the digital age, addressing challenges such as prompt injection attacks, data leakage, low interpretability, and insufficient emotional engagement faced by LLM-based companion agents in fields like education and healthcare, we constructed a comprehensive framework to enhance security protection, improve reasoning capabilities, quantify uncertainty, and customize emotional support. The goal is to create a safe, reliable, and empathetic AI assistant.
Responsible for the post-training and interpretability modules of the LLM.

**Outcomes**
  - Agent Module: Adopted Qwen3-14B as the pre-trained model and performed single-GPU fine-tuning (A800 80G) on the CBT-bench dataset.
  - Interpretability Module:
    - Explored potential relationships among conceptual annotations in the dataset using the Apriori algorithm for association rule learning, enhancing the interpretability of causal variables.
    - Designed an innovative framework of Latent Disentanglement-Concept Bottleneck Models (LDCBMs). Compared with previous models on the CUB, AwA2, and CelebA datasets, the concept alignment rate increased by 0.1242 ± 0.0576, and the label accuracy improved by 0.1316 ± 0.0203, achieving SOTA performance. Additionally, the entire input-concept-output process is interpretable.

**Backdoor Attack Defense for Concept Bottleneck Models**

**Project Summary:** In explainable AI (XAI), Concept Bottleneck Models (CBMs) enhance interpretability via understandable underlying concepts, but are vulnerable to concept-level backdoor attacks (hidden triggers in concepts causing undetectable misbehavior). First proposed Conceptguard defense: constructed poisoned datasets, divided data subsets, and used majority voting to mitigate data-driven backdoor impacts.

**Key Contributions:**

* Theoretically proved a minimum trigger size threshold, above which Conceptguard effectively defends against attacks (average backdoor success rate reduced by ~30\%).

* Led CBMs baseline and Conceptguard experiments on CUB dataset, demonstrating improved concept accuracy. Identified cluster mechanism as an unsupervised method to avoid concept-level category conflicts and enhance feature learning for better concept correlation capture.

<!-- *Undergraduate(2020-2024):*

**Multidimensional evaluation model of driving safety based on big data of new energy bus operation**
  * China University of Petroleum Beijing 

  * Developed a new evaluation model for driving behavior based on vehicle status, real-time driving, and
 driving behavior using machine learning methods such as BPNN, SVM, CNN, KNN, and DTR.
   *  Processed 688 million data points from electrical vehicles, handled default values for key variables, and
 trained models for multiple season data sets.

 <p align="right">Summer 2022</p>

**A combined application of a gravity model and social network analysis evaluating the economic connections**

  * Analyzed the global trade network of waste and developed innovative ways to enhance decision-making
 through temporal exponential random graph models.
  * Constructed global waste trade networks and studied their structural evolution and determinants.

<p align="right">Summer 2022</p>

**Improved Social Force Model Based on Enhancing Psychobehavioral Heterogeneity**

  * Proposed an enhanced system dynamics model incorporating agent-based trampling risk assessment, entropy methodforexternalfactorimpactquantification, expertweighting, and psychological force parameters for individual movement vectors.
  
  <p align="right">Summer 2022</p> -->

<!-- Skills
======
* Programming Languages:
  * R
  * Python
  * Julia
  * C
* Applied Skills:
  * Data analysis
  * Mathematical modeling
  * Experiment design
  * Bibliometric -->

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor%}</ul>

Awards
======
* `Sep. 2022`_First Prize China Undergraduate Mathematical Contest in Modeling(CUMCM)_
* `Jun. 2022`_Grand Prize(1/4983) ”Renzheng Cup” National Student Mathematical Modeling Competition_
* `Nov. 2021`_H Prize, “Shuwei Cup” International Student Mathematical Modeling Competition_ 
* `Nov. 2021`_Third Prize “Huajiao Cup”National University Mathematics Competition_ 
* `Feb. 2022`_H Prize Interdisciplinary Contest In Modeling(MCM/ICM)_ 
* `Aug. 2022`_Second Prize ”MathorCup” National Student Mathematical Modeling Competition_
* `May. 2022`_Second Prize ”Renzheng Cup” National Student Mathematical Modeling Competition_ 
* `Jun. 2022`_Second Prize China Student Computer Design Competition_ 
* `Sep. 2022`_Second Prize Nation University math network championship_ 

 

 
 
 
 


<!--   <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
   -->
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
