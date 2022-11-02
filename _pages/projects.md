---
layout: archive
title: "Coursework Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
---

{% include base_path %}

[//]: # (<div style="margin-top: -1%"></div>)
[//]: # ({: style="text-align: justify" })


## UCSD

### ECE285 Deep Generative Models

{: style="text-align: justify" }
<img src="/images/attngansample.png" alt="pretty picture" width="25%" style="padding-left: 1%;  float: right;">
* A data augmentation pipeline in Pytorch to learn to generate Image - Caption pairs. Pipeline consisted of training together a model for caption generation (GPT2), image generation conditioned on the caption (DCGAN), and an Image-to-Caption generation stage.
* Implemented a VAE and GAN on chest X-ray images of patients with pneumonia in Pytorch and reported FID and Inception scores on generated x-ray images.
<div style="clear: both"></div>

### CSE291 Natural Language Processing

{: style="text-align: justify" }
<img src="/images/crfmodel.png" alt="pretty picture" width="25%" style="padding-left: 1%;  float: right;">
* An encoder-decoder based seq2seq prediction model with attention mechanism for **translation** on Multi30k dataset in Pytorch. Implemented beam search and nucleus sampling to decode.
* Implemented neural conditional random field (**CRFs**) for Named Entity Recognition and Constituency parsing tasks in Pytorch and performed a qualitative and quantitative evaluation.
<div style="clear: both"></div>

### CSE258 Recommender Systems

{: style="text-align: justify" }
* Built a hierarchical classification system for jobs based on their titles and descriptions into categories from O*NET taxonomy.

## IIITH

### CSE474 Information Retrieval

{: style="text-align: justify" }
<img src="/images/Screen%20Shot%202022-10-25%20at%203.03.23%20PM.png" alt="pretty picture" width="25%" style="padding-left: 1%;  float: right;">
* Replicated a 2012 paper - A Contextual Multi-arm Bandit Approach to Personalized News **Recommendation** - by Yahoo Labs on a dataset from an Indian online news website.
* Indexing, Retrieval and Ranking engine to efficiently **search** in entire english Wikipedia corpus.
<div style="clear: both"></div>

### CSE485/6 Cognitive Science

{: style="text-align: justify" }
<img src="/images/img_1.png" alt="pretty picture" width="25%" style="padding-left: 1%;  float: right;">
* Simulated and studied Hodgin-Huxley model, phase plane analysis, Passive Cable equation, Leaky IF model and Hopfield networks using the Brian2 simulator.
* Conducted a serial reaction time **experiment** in Psychtoolbox to study implicit learning of auditory sequences and any presence of motor learning.
<div style="clear: both"></div>

### CSE431/41 Systems

{: style="text-align: justify" }
<img src="/images/Screen%20Shot%202022-10-25%20at%202.56.37%20PM.png" alt="pretty picture" width="25%" style="padding-left: 1%;  float: right;">
* A **distributed** approximation algorithm for minimum spanning trees implemented using C++ OpenMPI library based on Khan et al. 2008.
* A query processing, data definition and data manipulation engine developed in Python with the objective to learn the internals of an SQL DBMS.
* A unix-like shell written in C that executes standard Linux commands by creating and managing new processes and supports redirection, piping and bg processes.
