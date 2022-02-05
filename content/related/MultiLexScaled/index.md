---
author: A. Maurits van der Veen
categories:
- code
- python
- sentiment analysis
date: "2021-12-10"
draft: false
excerpt: A central feature of the book is our analysis of the degree of positivity or negativity of a newspaper articles. To perform this analysis, we developed a new sentiment analysis method, which outperforms other lexicon-based approaches on standard benchmarks and is more robust across a range of different domains.
layout: single
links:
- icon: github
  icon_pack: fab
  name: code & paper
  url: https://github.com/amaurits/MultiLexScaled
subtitle: A python module for sentiment analysis
tags:
- hugo-site
title: MultiLexScaled
---

#### Lexicon-based sentiment analysis, using multiple lexica and scaled against representative text corpora.

Sentiment analysis — the study of the positive or negative valence of texts — has wide-ranging applications across the social sciences. Automated approaches make it possible to code near unlimited quantities of texts with full replicability and high accuracy. Compared to machine-learning approaches, lexicon-based methods provide generalizability while sacrificing little in performance and gaining the ability to identify gradations in sentiment as well as cross-domain comparability. We introduce a method, MultiLexScaled, which averages valences across a number of widely-used general-purpose lexica. We validate the method against several benchmark datasets across a range of different domains and languages. We illustrate the value of identifying sentiment trends by examining coverage of Muslims in the British press, showing that tabloids and broadsheet papers diverged noticeably after 9/11, with tabloids becoming decidedly more negative about Muslims while the tone of broadsheet articles about Muslims remained relatively unchanged.
