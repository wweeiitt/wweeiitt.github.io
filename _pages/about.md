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

I am a fourth-year Ph.D. Candidate at the Department of Computer Science and Technology, Tsinghua University. I am a member of the [Pervasive Human-Computer Interaction (PI) Lab](https://pi.cs.tsinghua.edu.cn/), where I am advised by Prof. <a href='https://www.cs.tsinghua.edu.cn/csen/info/1306/4332.htm'>Yuanchun Shi</a> and Prof. <a href='https://www.cs.tsinghua.edu.cn/csen/info/1306/4423.htm'>Junliang Xing</a>. I earned my B.Eng. from Tsinghua University in 2022.

My research interests include LLM/VLM based AI Agents, Reinforcement Learning, and Human-Computer Interaction. My research has been published in leading international AI venues, including NeurIPS, CVPR, ICCV, and TMLR. Currently, I focus on developing autonomous AI agents capable of solving complex multi-turn tasks via hybrid knowledge-data mechanisms, effectively leveraging prior knowledge from foundation models alongside environmental feedback.

<!-- Welcome to see my CV in English or 中文! -->


# 🔥 News
- *2026.02*: &nbsp;🎉 GTR-Turbo was accepted by CVPR 2026. 
- *2025.12*: We proposed <a href='https://arxiv.org/abs/2512.13043'>GTR-Turbo</a>, a significant upgrade to the GTR framework that eliminates reliance on costly external teacher models and accelerates the training process.
- *2025.06*: &nbsp;🎉 GTR was accepted by ICCV 2025.
- *2025.03*: We addressed a critical challenge in RL-based VLM agent training by proposing <a href='https://arxiv.org/abs/2503.08525'>Guided Thought Reinforcement (GTR)</a>, a novel approach that synthesizes the strengths of RL and IL.

# 📖 Education
- *2022.08 - now*: Ph.D. Student, Department of Computer Science and Technology, Tsinghua University. 
- *2018.08 - 2022.07*: B.Eng., Department of Computer Science and Technology, Tsinghua University. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/GTR-Turbo.png' alt="sym" width="500"></div></div>
<div class='paper-box-text' markdown="1">

<span style="font-size: 120%; color: #000080; font-weight: bold;">GTR-Turbo: Merged Checkpoint is Secretly a Free Teacher for Agentic VLM Training</span>

**Tong Wei**, Yijun Yang, Changhao Zhang, Junliang Xing, Yuanchun Shi, Zongqing Lu, Deheng Ye

IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2026

[[Paper]](https://arxiv.org/abs/2512.13043), [[Code]](https://github.com/weit123/GTR-Turbo) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/GTR.png' alt="sym" width="500"></div></div>
<div class='paper-box-text' markdown="1">

<span style="font-size: 120%; color: #000080; font-weight: bold;">GTR: Guided Thought Reinforcement Prevents Thought Collapse in RL-based VLM Agent Training</span>

**Tong Wei**, Yijun Yang, Junliang Xing, Yuanchun Shi, Zongqing Lu, Deheng Ye

International Conference on Computer Vision (ICCV), 2025

[[Paper]](https://openaccess.thecvf.com/content/ICCV2025/papers/Wei_GTR_Guided_Thought_Reinforcement_Prevents_Thought_Collapse_in_RL-based_VLM_ICCV_2025_paper.pdf), [[Code]](https://github.com/weit123/GTR) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/SDSAC.png' alt="sym" width="500"></div></div>
<div class='paper-box-text' markdown="1">

<span style="font-size: 120%; color: #000080; font-weight: bold;">Revisiting Discrete Soft Actor-Critic</span>

Haibin Zhou, **Tong Wei**, Zichuan Lin, Junyou Li, Junliang Xing, Yuanchun Shi, Li Shen, Chao Yu, Deheng Ye

Transactions on Machine Learning Research (TMLR), 2025

[[Paper]](https://openreview.net/pdf?id=EUF2R6VBeU), [[Code]](https://github.com/coldsummerday/SD-SAC) 
</div>
</div>

- <span style="color: #000080; font-weight: bold;">Leveraging Privileged Information for Partially Observable Reinforcement Learning</span>. Jinqiu Li, Enmin Zhao, **Tong Wei**, Junliang Xing, Shiming Xiang. IEEE Transactions on Games (TG), 2025. [[Paper]](https://ieeexplore.ieee.org/abstract/document/10887124), [[Code]](https://github.com/lijinqiu2021/acc)
- <span style="color: #000080; font-weight: bold;">Dual Critic Reinforcement Learning under Partial Observability</span>. Jinqiu Li, Enmin Zhao, **Tong Wei**, Junliang Xing, Shiming Xiang. Advances in Neural Information Processing Systems (NeurIPS), 2024. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/d399b67fa017f0f7670102c88507720c-Paper-Conference.pdf)
- <span style="color: #000080; font-weight: bold;">Lightwrite: Teach handwriting to the visually impaired with a smartphone</span>. Zihan Wu, Chun Yu, Xuhai Xu, **Tong Wei**, Tianyuan Zou, Ruolin Wang, Yuanchun Shi. The ACM CHI Conference on Human Factors in Computing Systems (CHI), 2021. [[Paper]](https://dl.acm.org/doi/10.1145/3411764.3445322)

# 💻 Internship
- *2024.06 - 2026.02*: Research intern @ Tencent AI Lab. Team leader: <a href='https://scholar.google.com/citations?user=jz5XKuQAAAAJ'>Dr. Deheng Ye</a>. 

# 🎖 Honors and Awards
- *2025, 2023*: Overall Excellence Scholarship, Tsinghua University. 
- *2024*: Tencent Rhino-Bird Elite Talent Program. 
- *2022*: Champion of the 2022 World Intelligent Aerial Gaming Competition.
- *2021*: First Prize in 39th Challenge Cup, Tsinghua University.
- *2020*: Grand Prize in 38th Challenge Cup, Tsinghua University.

# 🔖 Other Information
- I served as a Teaching Assistant for several courses at Tsinghua: Fundamentals of Programming (Undergraduate), Professional Practice (Undergraduate), Computer Vision (Graduate).
- I am also an Undergraduate Student Counselor of Tsinghua University, managing student affairs and providing career guidance for undergraduates of the CS Department.
- I enjoy a variety of sports, such as tennis, basketball, ultimate frisbee, skiing, hiking, etc.