---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a second-year undergraduate student at Xi'an Jiaotong-Liverpool University, majoring in Applied Mathematics, and I am expected to complete my BSc degree at the University of Liverpool in 2028. Concurrently, I serve as a Research Assistant at [PremiLab](https://premilab-math.github.io/), where I am supervised by Prof. [Qiufeng Wang](https://wqf510.github.io/).
I will visit yale for several months in the summer, supervised by Prof. [Arman Cohan](https://armancohan.com/) and [Yilun Zhao](https://yilunzhao.github.io/). If you are interested in my research, please feel free to contact me.

My research interests span AI for math reasoning, AI for Science, multimodal large language models and Reinforcement Learning. In my spare time, I also engage in research on optimization theory and mathematical physics.


# 🔥 News

<div style="max-height: 350px; overflow-y: auto; border: 1px solid #e0e0e0; border-radius: 8px; padding: 10px 15px; background-color: #fafafa;" markdown="1">
- *2026.02*: &nbsp;🎉🎉 Our work "Hilbert-Geo: Solving Solid Geometric Problems by Neural-Symbolic Reasoning" was accepted by CVPR2026.
- *2026.01*: &nbsp;🎉🎉 This is my first attempt in the field of optimization. I submitted a paper on the optimization behavior of non-smooth perception to ICML2026.
- *2025.11*: &nbsp;🎉🎉 I have completed a manuscript on solving multimodal mathematical problems and submitted it to CVPR2026.
- *2025.06*: &nbsp;🎉🎉 I was supported by the Summer Undergraduate Research Fellowship(SURF) at XJTLU to study large language models for math reasoning.
- *2025.03*: &nbsp;🎉🎉 I will intern at Shanghai AI Lab for several months.
- *2025.03*: &nbsp;🎉🎉 I will serve as the Head of the Academic Department for the Math Club and Physics Club at XJTLU.
- *2025.02*: &nbsp;🎉🎉 I joined [PremiLab](https://premilab-math.github.io/) as a research assistant.
- *2024.12*: &nbsp;🎉🎉 I translated a textbook: Method in contemporary mathematical physics. [Here](https://drive.google.com/file/d/1Z2Gl61_IojbPB8iT0BGODMree5qUinw6/view?usp=sharing) is a part of the first draft.

</div>

<span class='anchor' id='publications'></span>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/cvpr1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hilbert-Geo: Solving Solid Geometric Problems by Neural-Symbolic Reasoning](https://drive.google.com/file/d/1PR0_llQy4j6FsyOCJICpuc4bu84vwyOa/view?usp=sharing)

**Ruoran Xu**, Haoyu Cheng, Bin Dong, Qiufeng Wang

[**📝**](https://scholar.google.com/citations?view_op=&hl=zh-CN&user=DhtAFkwAAAAJitation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- By integrating ontology and topological structures, we developed a Multimodal Formalization Parser to enable cross-modal formalization of geometry.
Leveraging this foundational integration, we further designed a Reasoning Engine equipped with formal verification mechanisms via Parse2Reason step. The framework implements automatic formal reasoning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/ICML.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Singularity-aware Optimization via Randomized Geometric Probing: Towards Stable Non-smooth Optimization]()

**Ruoran Xu**, Borong She, Qiufeng Wang, Xiaobo Jin

[**📝**](https://scholar.google.com/citations?view_op=view_citatil=zh-&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed a geometry-aware theoretical paradigm for non-smooth optimization, quantifying local instability via Clarke subdifferential analysis.
Proposed the LGI metric, establishing a rigorous and efficient proxy for subdifferential diameter based on randomized directional derivatives.
Proved the convergence of S-Adam, which converges to Clarke stationary points at a $O(1/\sqrt{T})$ rate, providing fundamental theoretical support for singularity-aware optimization.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/eccv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Omni-Geo: Full-Domain Geometry Benchmark with Multimodal Diagram Generation]()

**Ruoran Xu**, Wending Gao, Haoyu Cheng, Qiufeng Wang


[**📝**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&uswAAAAJ&cation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed Omni-Geo, the first unified benchmark for general geometric intelligence spanning plane, analytic, and solid geometry, built on a standardized Geometric Description Language (GDL) and an SDF-based diagram synthesis engine that produces contamination-free data. Comprising ~23K problems evaluated on 11 state-of-the-art LLMs and MLLMs, Omni-Geo highlights the necessity of a comprehensive, unified benchmark for assessing geometric reasoning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/mm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[SDF-AnalyticGeo: Multi-Agent for Analytic Geometry Problem Generation]()

**Ruoran Xu**, Wending Gao, Qiufeng Wang


[**📝**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&uswAAAAJ&cation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed SDF-AnalyticGeo, a scalable multi-agent pipeline for generating large-scale, high-quality multimodal analytic geometry problems via three collaborative agents covering problem generation, formalization, and SDF-based figure rendering. The resulting dataset—integrating natural language, standardized geometric images, ground-truth answers, and formal annotations—achieves over 90% geometric consistency and provides a unified benchmark for evaluating MLLMs on analytic geometry reasoning.
</div>
</div>



# 🚧 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Coming 50%</div><img src='images/phy.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PhysElite:Olympic physics competition multimodal benchmark](https://heart316.github.io/physics-question-platform/)

**Leader**

[**📝**](https:) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A large Olympic physics competition multimodal benchmark. We tracked the contestants' daily practice questions, understood the multimodal problem-solving steps, and analyzed and answered them.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Coming 30%</div><img src='images/ageo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Autoformalizing and Reasoning Analytic Geometry](https://github.com/RuoranXu/AnalyticGeo)

**Leader**

[**📝**](https:) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Formalize graphical and textual content into Lean 4 with a large language model for solving analytic geometry problems with expert human-like reasoning skills.
</div>
</div>


# 📖 Educations
- *2024.09 - 2028.06 (Expected)*, University of Liverpool, BSc. Applied Mathematics
• GPA: 3.83/4.00

# 🎖 Honors and Awards
- *2025* Honorable Mention, Mathematical Contest in Modeling (MCM)
- *2024* Bronze Award, University Physics Competition in Modeling (UPC)
- *2022* First Prize, Chinese Physics Olympiad (CPHO)
- *2020* Second Prize, National Olympiad in Informatics in Provinces (NOIP)

# 💻 Internships
- *2025.03 - 2025.06*, Shanghai AI Lab, Shanghai.

<h1 align='center'>
<a href="https://mapmyvisitors.com/web/1c2qa"  title="Visit tracker"><img src="https://mapmyvisitors.com/map.png?d=82VdebEAB-IbhOZadmAvBnd7U4ynrwYECN1vdd9ZvRY&cl=ffffff" /></a>
</h1>
