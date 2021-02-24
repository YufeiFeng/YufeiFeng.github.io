---
permalink: /
title: ""
excerpt: "Yufei Feng’s Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Education
======
* 2014.09 - 2018.06: 
  * B.S. in Zhejiang University

Work experience
======
* 2018.07 - Now: 
  * Serving as Senior Algorithm Engineer 
  * In EdgeRec team of Taobao Homepage Guess U Like, Taobao Technique Department, Alibaba Group
  * Promoting efficiency in re-ranking algorithms:
    * Proposed a context-wise generative re-ranking model GRN, contributing to 5.2% PV lift and 6.1% IPV lift 
    * Proposed a permutation-wise re-ranking framework LRS, contributing to 11.0% PV lift and 8.7% IPV lift 
    * Participated in the implementation of recommender system in the edge computing (EdgeRec)
  * Promoting user behavior modeling in CTR prediction:
    * Proposed a session-based CTR prediction model DSIN, contributing to 5.2% CTR lift 
    * Proposed KG-enhanced CTR prediction models MTBRN and ATRBG, contributing to 6.8% CTR lift 
    * Implemented a CTR prediction framework based on tensorflow, contributing to significant CTR lifts in various scenarios
  * Promoting related fields of the industry:
    * Published 4 papers in SIGIR, CIKM and IJCAI, three of which I am the first authorship 
    * Submitted 2 papers to SIGIR-2021 and KDD-2021, both of which I am the first authorship 

<a href="/publications/" style="color:#000000">Publications</a>
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Skills
======
* Recommender system
  * Matching, Ranking and Re-ranking
  * Data mining
* Deep learning, Tensorflow
* Python, Java and Sql

Research Interests
======
* Matching, Ranking and Re-ranking algorithms in Recommender system
* NLP (Natural Language Processing)
* IR (Information Retrieval)
* RL (Reinforcement Learning)