---
layout: archive
title: CV
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
{% assign cv_publications = site.publications | sort: 'pub_order' %}

## Education

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology (HKUST), 2024–Present.
  - First-year PhD candidate in the HKUST NLP Group.
  - Supervisor: Professor Junxian He.
- **B.Eng.**, Shanghai Jiao Tong University (SJTU), 2020–2024; graduated in June 2024.

Professor Junxian He previously advised Junteng Liu during his undergraduate studies at SJTU.

## Research Experience

- **Research Intern, MINIMAX**, February 2025–Present.
- **Research Intern, Tencent WXG**, June 2024–September 2024; advisor: Zifei Shan.
- **Research Intern, Shanghai AI Lab**, June 2023–December 2023; advisor: Prof. Yu Cheng.
- **PhD Researcher, HKUST NLP Group**, 2024–Present; supervisor: Professor Junxian He.

## Publications

<ul>
{% for post in cv_publications %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

## Skills and Research Expertise

- Natural language processing
- Machine learning
- LLM reasoning and reinforcement learning
- Hallucination in Vision-Language Models (VLM)
- LLM truthfulness and interpretability

## Honors and Awards

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University.

## Contact Information

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [https://github.com/Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [Junteng Liu profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://x.com/junteng88716710)
