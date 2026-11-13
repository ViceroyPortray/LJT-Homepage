---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* Ph.D. in Computer Science, Hong Kong University of Science and Technology, 2024–Present
  * HKUST NLP Group, led by Professor Junxian He
  * Supervisor: Professor Junxian He
* B.Eng., Shanghai Jiao Tong University, 2020–2024
  * Graduated in June 2024
  * Previously advised by Professor Junxian He during undergraduate studies

## Research Experience

* February 2025–Present: Research Intern
  * MINIMAX
* June 2024–September 2024: Research Intern
  * Tencent WXG
  * Advisor: Zifei Shan
* June 2023–December 2023: Research Intern
  * Shanghai AI Lab
  * Advisor: Prof. Yu Cheng

## Publications

{% assign cv_publications = site.publications | sort: "date" | reverse %}
<ul>{% for post in cv_publications %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Skills

* Natural language processing
* Machine learning
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM Truthfulness and Interpretability

## Awards

* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

## Contact

* Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
* GitHub: [Vicent0205](https://github.com/Vicent0205)
* Google Scholar: [Junteng Liu Google Scholar profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
* X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)
