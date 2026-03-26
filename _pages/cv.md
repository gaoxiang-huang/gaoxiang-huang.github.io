---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- Material
======
* [Statement of Purpose](/files/SoP.pdf)
* [CV](/files/Gaoxiang_cv_HKUSTGZ.pdf) -->

Education
======
* M.Phil, The HongKong University of Science and Technology (Guangzhou)
  * AI thrust&INFO Hub 
    * Majoring in Artificial Intelligence
    <!-- * (AI, [CGA:3.323/4](/files/SSR_TSRPT_U.pdf)) -->
    * Supervisor: [Prof. Yutao YUE](https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page/YUE-Yutao/yutaoyue)
<p align="right">2024-Present</p>

* B.S, China University of Petroleum Beijing
  * Department of Mathematics, School of Arts and Sciences
    * Majoring in Statistics
    <!-- * (STAT,[GPA:80.8/100, rank:13/61](/files/transcript_en.pdf)) -->
   <!-- * Relevant Courses: Mathematical analysis; Advanced algebra; Real functions and general function analysis;
     Probability theory; Mathematical statistics; Stochastic processes.   -->
<p align="right">2020-2024</p>


Language Proficiency
======
* English: IELTS:6.5, CET-6
* Chinese: native

Research experience
======
*Postgraduate(2024-Present):*

**Mechanism-Interpretability-Guided Reasoning Improvement in Latent-Space Autoregressive Paradigms**

**Project Summary:** Mainstream LLM reasoning methods such as Chain-of-Thought (CoT) generate many explicit tokens and thus incur high inference cost. Recent latent-space autoregressive paradigms (e.g., COCONUT) perform iterative reasoning in continuous latent space and then decode answers directly, but their internal mechanisms remain underexplored and their reasoning performance is often inferior to SFT-CoT. Through causal mechanism analysis for interpretability, we identified two fundamental mechanisms and proposed the $SAE\_Latent$ method, which achieves SOTA reasoning performance with only one-tenth of the computation cost of other inference-only methods.

**Key Contributions:**

* Conducted mechanism-level interpretability analysis for latent-space autoregressive reasoning and validated two core findings: (1) latent-space reasoning is primarily routing-based rather than strictly autoregressive, where earlier forward states influence later reasoning; (2) early forwards are responsible for core reasoning and answer decisions, while later forwards mainly consolidate representations and formatting constraints.

* Proposed $SAE\_Latent$ by leveraging latent routing mechanisms: designed one-pass gradient-based key-node identification and a high-level SAE steering strategy that injects steering signals into residual streams at key nodes.

* Ran experiments on Llama3.2-1B-Instruct and Qwen3-7B across GSM8K-aug, SVAMP, MultiArith, and MATH500; results surpassed prior inference-only methods and reached SOTA with approximately 1/10 compute overhead.

**Lightweight Disentangled Concept Bottleneck Model (LDCBM)**

**Project Summary:** Targeting misalignment and concept drift in input-to-concept mapping of Concept Bottleneck Models (CBMs), we developed a lightweight disentanglement framework to improve interpretability, intervention sensitivity, and downstream classification performance. I was responsible for method design, training framework implementation, experimental evaluation, and manuscript writing.

**Key Contributions:**

* Method and implementation: proposed a two-stage LDCBM framework with filter-grouping loss and joint concept supervision; built the training pipeline on ResNet18 with periodic spectral-clustering updates (every 2 epochs), and completed experiments on CUB, CelebA, and AwA2.

* Core results: improved class accuracy on CUB from 60.80\% to 66.17\% (+5.37\%), and on AwA2 from 76.63\% to 77.55\%; when integrated with CEM, achieved 63.50\% class accuracy on CelebA.

* Robustness and efficiency: concept-intervention and background-mask experiments showed more robust visual-concept alignment (CUB task drop reduced from 45.60\% to 40.04\%, concept drop from 6.38\% to 5.89\%); meanwhile the model remained lightweight (11.26M parameters, 1.8236G FLOPs, 6.18 ms/image).

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
