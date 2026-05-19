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

I am Rongxin Chen, currently a Master's student in Computer Science and Technology at the Institute of Computing Technology, Chinese Academy of Sciences (ICT, CAS). I received my Bachelor's degree from the Software College of Northeastern University (NEU). My research interests focus on **LLM Agent, Personalization, Alignment, RolePlaying, and Social Simulation**.
**<span style="color: red;">I expect to graduate in 2027 and am currently on the job market! If you are interested in me, please feel free to contact me.🔥</span>**

# 🔥 News
- *2026.04*: &nbsp;🎉🎉 Our paper ["HAG: Hierarchical Demographic Tree-based Agent Generation for Topic-Adaptive Simulation"](https://arxiv.org/pdf/2601.05656) was accepted in **ACL 2026 (Main)**!
- *2026.01*: &nbsp;🎉🎉 Honored to receive the Hua Luogeng Master Award (**The only recipient** in the institute) at ICT, CAS!
- *2025.11*: &nbsp;🥳 Presented a poster at the **13th National Conference on Social Media Processing (SMP 2025)** in Wuhan, China.
- *2025.11*: &nbsp;🎉🎉 Gave an Oral presentation on ["Multi-Personality Generation of LLMs at Decoding-time"](https://dl.acm.org/doi/abs/10.1145/3773966.3777945) at **The 1st Workshop on LLM Agents for Social Simulation (CIKM 2025)** in Seoul, Korea, and received the **Outstanding Paper** award!
- *2025.10*: &nbsp;🎉🎉 Our paper ["Multi-Personality Generation of LLMs at Decoding-time"](https://dl.acm.org/doi/abs/10.1145/3773966.3777945) was accepted in **WSDM 2026**!

# 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ACL 2026 Main Oral</div>
      <img src='images/hag_paper_figure.png' alt="HAG paper figure" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  [HAG: Hierarchical Demographic Tree-based Agent Generation for Topic-Adaptive Simulation](https://arxiv.org/pdf/2601.05656)

  **Rongxin Chen**, Tianyu Wu, Bingbing Xu*, Jiatang Luo, Xiucheng Xu, Huawei Shen
  
  *ACL 2026 (Main)*

  - Proposed HAG to decompose and model the conditional joint distribution of demographic attributes, enabling topic-adaptive population distribution trees. We also introduced the PACE evaluation framework for statistical-semantic dual-level assessment, achieving significant reduction in demographic errors.

  ([Paper](https://arxiv.org/pdf/2601.05656))&nbsp;([Code](https://github.com/Libra117/HAG))&nbsp;([Slides](https://arxiv.org/pdf/2601.05656))&nbsp;([Poster](https://arxiv.org/pdf/2601.05656))
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">WSDM 2026</div>
      <img src='images/mpg_paper_figure.png' alt="MPG paper figure" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  [Multi-Personality Generation of LLMs at Decoding-time](https://dl.acm.org/doi/abs/10.1145/3773966.3777945)

  **Rongxin Chen**, Yunfan Li, Yige Yuan, Bingbing Xu*, Huawei Shen

  *WSDM 2026* & *LASS Workshop of CIKM 2025 (Outstanding Paper)*

  - Proposed MPG, a flexible and robust decoding-time generation framework for multi-personality LLMs without requiring extra training or external reward models. We also designed the SCR algorithm for efficient generation, achieving significant improvements in MBTI simulation and role-playing experiments.

  ([Paper](https://dl.acm.org/doi/abs/10.1145/3773966.3777945))&nbsp;([Code](https://github.com/Libra117/MPG))&nbsp;([Slides](/files/MPG-slides.pdf))&nbsp;([Poster](/files/MPG_poster_WSDM.pdf))
  </div>
</div>

<style>
  /* 强制去掉论文列表底部的灰线和标题顶部的灰线 */
  .paper-box { border-bottom: none !important; }
  h1 { border-top: none !important; }
</style>

# 🎖 Honors and Awards
- *2026* Hua Luogeng Master Award (**The only recipient** in the institute), ICT CAS.
- *2025* E Fund FinTech Freshman Award, ICT CAS.
- *2023* **National Scholarship** for Undergraduates.
- *2023* National Encouragement Scholarship, Ministry of Education.
- *2023* **Finalist Winner** in the American Region Mathematical Contest in Modeling.
- *2023* **National Gold Award** in the 13th "Challenge Cup" National College Student Entrepreneurship Plan Competition. 

# 📖 Educations
- *2024.09 - 2027.07 (Expected)*, Master in Computer Science and Technology, UCAS - ICT CAS. 
- *2020.09 - 2024.07*, Bachelor in Software Engineering (Artificial Intelligence), NEU. 

# 💬 Presentations
- *2026.02*, Poster presentation at WSDM 2026, Boise, USA. 
- *2025.11*, Poster at the 13th National Conference on Social Media Processing, Wuhan, China.
- *2025.11*, Oral presentation at LASS Workshop of CIKM 2025, Seoul, South Korea. 

