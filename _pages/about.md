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

I am a second-year undergraduate student at Xi'an Jiaotong-Liverpool University, majoring in Applied Mathematics, and I am expected to complete my BSc degree at the University of Liverpool in 2028. 
Concurrently, I serve as a Research Assistant at [PremiLab](https://premilab-math.github.io/) and intern at the [Yale NLP lab](https://nlp.cs.yale.edu/).
<!-- Concurrently, I serve as a Research Assistant at [PremiLab](https://premilab-math.github.io/), collaborating with Prof. [Qiufeng Wang](https://wqf510.github.io/).-->
<!--, where I am supervised by Prof. [Qiufeng Wang](https://wqf510.github.io/).-->
<!--
I will visit Yale for several months in the summer to collaborate with Prof. [Arman Cohan](https://armancohan.com/) and [Yilun Zhao](https://yilunzhao.github.io/). 
Feel free to contact me if you are interested in my work. I'm willing to discuss with people from different backgrounds.-->

My goal is to develop robust intelligent systems with sampling-based representations and continuous reasoning capabilities, and to control the capability boundaries of its performance. I am active on both the methodology and application fronts. My explorations have spanned AI for formal reasoning, reinforcement learning, optimization theory and agent system.
Feel free to contact me if you are interested in my work.
<!--
My research interests span AI for Verifiable Reasoning, AI for Scientific Discovery, multimodal large language models and Reinforcement learning. 
<!-->
<!--In my spare time, I also engage in Mathematical Methods for Physics.-->

<!-- Currently, I am exploring how to efficiently sweep away "trivial" solutions in AI fields; Also, I am more inclined to focus on "long-tail," "causal" problems. -->


# 🔥 News

<div style="max-height: 350px; overflow-y: auto; border: 1px solid #e0e0e0; border-radius: 8px; padding: 10px 15px; background-color: #fafafa;" markdown="1">
- *2026.04*: &nbsp;🎉🎉 Excited to have one paper accepted at ICML 2026!
- *2026.02*: &nbsp;🎉🎉 Excited to have one paper accepted at CVPR 2026!
- *2025.06*: &nbsp;🎉🎉 I was supported by the Summer Undergraduate Research Fellowship(SURF) at XJTLU to study LLM for math reasoning.
- *2025.03*: &nbsp;🎉🎉 I will serve as the Head of the Academic Department for the Math Club and Physics Club at XJTLU.
- *2025.02*: &nbsp;🎉🎉 I joined [PremiLab](https://premilab-math.github.io/) as a research assistant.
- *2024.12*: &nbsp;🎉🎉 I translated a textbook: Method in contemporary mathematical physics. [Here](https://drive.google.com/file/d/1Z2Gl61_IojbPB8iT0BGODMree5qUinw6/view?usp=sharing) is a part of the first draft.

</div>

<span class='anchor' id='publications'></span>

# 📝 Publications 
<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/cvpr1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hilbert-Geo: Solving Solid Geometric Problems by Neural-Symbolic Reasoning](https://github.com/PremiLab-Math/Hilbert-Geo)

**Ruoran Xu**, Haoyu Cheng, Bin Dong, Qiufeng Wang

[**📝**](https://github.com/PremiLab-Math/Hilbert-Geo) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- By integrating ontology and topological structures, we developed a Multimodal Formalization Parser to enable cross-modal formalization of geometry.
Leveraging this foundational integration, we further designed a Reasoning Engine equipped with formal verification mechanisms via Parse2Reason step. The framework implements automatic formal reasoning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/icml_1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Singularity-aware Optimization via Randomized Geometric Probing: Towards Stable Non-smooth Optimization](https://github.com/RuoranXu/S-Adam)

**Ruoran Xu**, Borong She, Xiaobo Jin, Qiufeng Wang

[**📝**](https://github.com/RuoranXu/S-Adam) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed a geometry-aware paradigm for non-smooth optimization, capturing subdifferential via random finite difference to quantify local instability and suppress updates.
Proposed the LGI metric, a rigorous efficient subdifferential diameter proxy built on randomized directional derivatives.
Proved S-Adam converges to Clarke stationary points at $O(1/\sqrt{T})$, offering core theoretical support for singularity-aware optimization.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/eccv1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Omni-Geo: Full-Domain Geometry Benchmark with Multimodal Diagram Generation]()

**Ruoran Xu**\*, Wending Gao\*, Haoyu Cheng\*, Qiufeng Wang


[**📝**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&uswAAAAJ&cation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed Omni-Geo, the first unified benchmark for general geometric intelligence spanning plane, analytic, and solid geometry, built on a standardized Geometric Description Language (GDL) and an SDF-based diagram synthesis engine that produces contamination-free data. Comprising ~23K problems evaluated on 11 state-of-the-art LLMs and MLLMs, Omni-Geo highlights the necessity of a comprehensive, unified benchmark for assessing geometric reasoning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/mm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[FormalAnalyticGeo: A Neural-Symbolic Based Framework for Multimodal Analytic Geometry Problem Generation]()

**Ruoran Xu**\*, Wending Gao\*, Qiufeng Wang


[**📝**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&uswAAAAJ&cation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed SDF-AnalyticGeo, a scalable multi-agent pipeline for generating large-scale, high-quality multimodal analytic geometry problems via three collaborative agents covering problem generation, formalization, and SDF-based figure rendering. The resulting dataset—integrating natural language, standardized geometric images, ground-truth answers, and formal annotations—achieves over 90% geometric consistency and provides a unified benchmark for evaluating MLLMs on analytic geometry reasoning.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/phys.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">  
[PhysElite:How Far Are LLMs from Solving Olympiad-Level Physics Problems?]()

**Ruoran Xu**\*, Wending Gao\*, Liyunfeng Chen\*, Aixin Shi\*, Haoyu Cheng\*, Zixiang Fang, Yiqiang Zou, Qiufeng Wang


[**📝**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&uswAAAAJ&cation_for_view=DhtAFkwAAAAJ:ALROH1vI_8A) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  A large Olympic physics competition multimodal benchmark. We tracked the contestants' daily practice questions, understood the multimodal problem-solving steps, and analyzed and answered them.
</div>
</div>
-->

<div class="row">
    <div class="column" style="display: inline-block; vertical-align: top; width: 25%; margin-top: 20px;">
        <div style="position: relative;">
            <div class="badge">CVPR 2026</div>
            <a href="images/cvpr1.png"><img src="images/cvpr1.png" alt="sym" width="100%"></a>
        </div>
    </div>
    <div class="column" style="display: inline-block; vertical-align: top; width: 70%; margin-left: 3%">
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-bottom: 0;"><b>Hilbert-Geo: Solving Solid Geometric Problems by Neural-Symbolic Reasoning</b></p>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 5px;">
                <u><b>Ruoran Xu</b></u>,
                <span style="color: gray;">Haoyu Cheng</span>,
                <span style="color: gray;">Bin Dong</span>,
                <span style="color: gray;">Qiufeng Wang</span>
        </p>
        <div style="height: 0px;"></div>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 1px;">Computer Vision and Pattern Recognition (CVPR) 2026</p>
        <div style="height: 0px;"></div>
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-top: 1px;">
             <a href="https://github.com/PremiLab-Math/Hilbert-Geo" style="text-decoration: none; color: blue;">[Paper]</a>
             <a href="https://github.com/PremiLab-Math/Hilbert-Geo" style="text-decoration: none; color: blue;">[Code]</a>
        </p>
    </div>
</div>

<div style="height: 20px;"></div>

<div class="row">
    <div class="column" style="display: inline-block; vertical-align: top; width: 25%; margin-top: 20px;">
        <div style="position: relative;">
            <div class="badge">ICML 2026</div>
            <a href="images/icml_1.png"><img src="images/icml_1.png" alt="sym" width="100%"></a>
        </div>
    </div>
    <div class="column" style="display: inline-block; vertical-align: top; width: 70%; margin-left: 3%">
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-bottom: 0;"><b>Singularity-aware Optimization via Randomized Geometric Probing: Towards Stable Non-smooth Optimization</b></p>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 5px;">
                <u><b>Ruoran Xu</b></u>,
                <span style="color: gray;">Borong She</span>,
                <span style="color: gray;">Xiaobo Jin</span>,
                <span style="color: gray;">Qiufeng Wang</span>
        </p>
        <div style="height: 0px;"></div>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 1px;">International Conference on Machine Learning (ICML) 2026</p>
        <div style="height: 0px;"></div>
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-top: 1px;">
             <a href="https://github.com/RuoranXu/S-Adam" style="text-decoration: none; color: blue;">[Paper]</a>
             <a href="https://github.com/RuoranXu/S-Adam" style="text-decoration: none; color: blue;">[Code]</a>
        </p>
    </div>
</div>

<!--
<div class="row">
    <div class="column" style="display: inline-block; vertical-align: top; width: 25%; margin-top: 20px;">
        <a href="images/eccv1.png"><img src="images/eccv1.png" alt="sym" width="100%"></a>
    </div>
    <div class="column" style="display: inline-block; vertical-align: top; width: 70%; margin-left: 3%">
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-bottom: 0;"><b>Omni-Geo: Full-Domain Geometry Benchmark with Multimodal Diagram Generation</b></p>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 5px;">
                <u><b>Ruoran Xu*</b></u>,
                <span style="color: gray;">Wending Gao*</span>,
                <span style="color: gray;">Haoyu Cheng*</span>,
                <span style="color: gray;">Qiufeng Wang</span>
        </p>
        <div style="height: 0px;"></div>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 1px;">Under Review</p>
        <div style="height: 0px;"></div>
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-top: 1px;">
        </p>
    </div>
</div> -->

<div style="height: 20px;"></div>

<div class="row">
    <div class="column" style="display: inline-block; vertical-align: top; width: 25%; margin-top: 20px;">
        <a href="images/mm.png"><img src="images/mm.png" alt="sym" width="100%"></a>
    </div>
    <div class="column" style="display: inline-block; vertical-align: top; width: 70%; margin-left: 3%">
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-bottom: 0;"><b>FormalAnalyticGeo: A Neural-Symbolic Based Framework for Multimodal Analytic Geometry Problem Generation</b></p>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 5px;">
                <u><b>Ruoran Xu*</b></u>,
                <span style="color: gray;">Wending Gao*</span>,
                <span style="color: gray;">Qiufeng Wang</span>
        </p>
        <div style="height: 0px;"></div>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 1px;">Under Review</p>
        <div style="height: 0px;"></div>
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-top: 1px;">
        </p>
    </div>
</div>

<div style="height: 20px;"></div>

<div class="row">
    <div class="column" style="display: inline-block; vertical-align: top; width: 25%; margin-top: 20px;">
        <a href="images/phys.png"><img src="images/phys.png" alt="sym" width="100%"></a>
    </div>
    <div class="column" style="display: inline-block; vertical-align: top; width: 70%; margin-left: 3%">
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-bottom: 0;"><b>PhysElite: How Far Are LLMs from Solving Olympiad-Level Physics Problems?</b></p>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 5px;">
                <u><b>Ruoran Xu*</b></u>,
                <span style="color: gray;">Wending Gao*</span>,
                <span style="color: gray;">Liyunfeng Chen*</span>,
                <span style="color: gray;">Aixin Shi*</span>,
                <span style="color: gray;">Haoyu Cheng</span>,
                <span style="color: gray;">Zixiang Fang</span>,
                <span style="color: gray;">Yiqiang Zou</span>,
                <span style="color: gray;">Qiufeng Wang</span>
        </p>
        <div style="height: 0px;"></div>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 1px;">Under Review</p>
        <div style="height: 0px;"></div>
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-top: 1px;">
        </p>
    </div>
</div>

<div style="height: 20px;"></div>

<div class="row">
    <div class="column" style="display: inline-block; vertical-align: top; width: 25%; margin-top: 20px;">
        <a href="#"><img src="images/emnlp.png" alt="Latent Memory Adapters" width="100%"></a>
    </div>
    <div class="column" style="display: inline-block; vertical-align: top; width: 70%; margin-left: 3%">
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-bottom: 0;"><b>Latent Memory Adapters: Compiling Documents into Activation-Space Values for Long Document Question Answering</b></p>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 5px;">
                <u><b>Ruoran Xu</b></u>,
                <span style="color: gray;">Yilun Zhao</span>,
                <span style="color: gray;">Songting Yu</span>,
                <span style="color: gray;">Siyue Zhang</span>,
                <span style="color: gray;">Tianyu Yang</span>,
                <span style="color: gray;">Arman Cohan</span>
        </p>
        <div style="height: 0px;"></div>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 1px;">Submission to ACL ARR</p>
        <div style="height: 0px;"></div>
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-top: 1px;">
        </p>
    </div>
</div>

<div style="height: 20px;"></div>
<!--
<div class="row">
    <div class="column" style="display: inline-block; vertical-align: top; width: 25%; margin-top: 20px;">
        <a href="#"><img src="images/" alt=" " width="100%"></a>
    </div>
    <div class="column" style="display: inline-block; vertical-align: top; width: 70%; margin-left: 3%">
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-bottom: 0;"><b>Strong-Polynomial Universality of Three-Sparse Linear Programming</b></p>
      <br>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 5px;">
                <u><b>Ruoran Xu</b></u>
        </p>
        <div style="height: 0px;"></div>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 1px;">Under Review</p>
        <div style="height: 0px;"></div>
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-top: 1px;">
        </p>
    </div>
</div>
-->

# 🚧 Open Projects

<div class='paper-box'><div class='paper-box-image'><div><img src='images/MathRA.png' alt="sym" width="60%"></div></div>
<div class='paper-box-text' markdown="1">

[MathRA](https://github.com/RuoranXu/MathRA)

 Facilitate both formal and informal verification of papers and vibe researching.

[**📝**](https:) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- HCI
</div>
</div>

<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Coming</div><img src='images/ageo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Autoformalizing and Reasoning Analytic Geometry](https://github.com/RuoranXu/AnalyticGeo)

**Leader**

[**📝**](https:) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Formalize graphical and textual content into Lean 4 with a large language model for solving analytic geometry problems with expert human-like reasoning skills.
</div>
</div>
-->

# 📖 Educations
- *2024.09 - 2028.06 (Expected)*, University of Liverpool, BSc. Applied Mathematics
• GPA: 3.83/4.00

<!--

# 🎖 Honors and Awards
- *2025* Honorable Mention, Mathematical Contest in Modeling (MCM)
- *2024* Bronze Award, University Physics Competition in Modeling (UPC)
- *2022* First Prize, Chinese Physics Olympiad in Provinces(CPHO)
- *2020* Second Prize, National Olympiad in Informatics in Provinces (NOIP)

# 💻 Internships
- *2025.03 - 2025.06*, Shanghai AI Lab, Shanghai.
-->
<h1 align='center'>
<a href="https://mapmyvisitors.com/web/1c2qa"  title="Visit tracker"><img src="https://mapmyvisitors.com/map.png?d=82VdebEAB-IbhOZadmAvBnd7U4ynrwYECN1vdd9ZvRY&cl=ffffff" /></a>
</h1>

