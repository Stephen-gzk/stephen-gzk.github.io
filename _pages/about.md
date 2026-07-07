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

I am a second-year M.S. student at the [School of Computer Science and Technology](http://www.cs.ecnu.edu.cn/), [East China Normal University (ECNU)](https://english.ecnu.edu.cn/). Before that, I received my B.Eng. degree in Software Engineering from the [School of Informatics](https://informatics.xmu.edu.cn/), [Xiamen University (XMU)](https://en.xmu.edu.cn/) in 2024. Currently, I am a research intern at [Tencent](https://www.tencent.com/en-us/). Previously, I spent a wonderful time at [Shanghai AI Laboratory](https://www.shlab.org.cn/) as a research intern.

My research interest mainly includes **Multimodal Large Language Models (MLLMs)** and **Reinforcement Learning**. Recently, I focus on exploring **Video Deep Research**, **Agentic RL**, and **Embodied AI**, aiming to empower MLLMs with stronger temporal understanding, multi-tool agentic reasoning, and decision-making abilities in real-world scenarios.

> 📢📢📢 If you would like to discuss potential opportunities for collaboration, please feel free to [contact me](mailto:51275901149@stu.ecnu.edu.cn). 😊


# 🔥 News

- *2026.07* &ensp; We release [VideoSearcher](https://arxiv.org/abs/2607.02927), the first closed-loop agent for video deep research task! 🎉
- *2026.02* &ensp; [MemoryExplorer](https://arxiv.org/abs/2601.10744) is accepted by CVPR 2026! 🎉
- *2026.01* &ensp; [TPRU](https://arxiv.org/abs/2602.18884) is accepted by ICLR 2026! 🎉
- *2026.01* &ensp; I join [Tencent](https://www.tencent.com/en-us/) as a research intern! 🔬
- *2025.09* &ensp; [Position paper of Embodied AI](https://mp.weixin.qq.com/s/CgBf-ZvMgfsWOrFlGKPZ8g) is accepted by Synced Review! 🎉
- *2024.10* &ensp; I join [Shanghai AI Laboratory](https://www.shlab.org.cn/) as a research intern! 🔬
- *2024.09* &ensp; I start my M.S. journey at [ECNU](https://english.ecnu.edu.cn/)! 👨‍🎓
- *2024.06* &ensp; I graduate from [Xiamen University](https://en.xmu.edu.cn/) as an Outstanding Graduate! 👨‍🎓
- *2023.07* &ensp; [PSGM](https://link.springer.com/chapter/10.1007/978-3-031-44192-9_30) is accepted by ICANN2023! 🎉
- *2020.09* &ensp; I start my B.Eng. journey at [Xiamen University](https://en.xmu.edu.cn/)! 👨‍🎓


# 📝 Publications

*(\* Equal Contribution)*

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/tpru.png' alt="tpru" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**TPRU: Advancing Temporal and Procedural Understanding in Large Multimodal Models**](https://arxiv.org/abs/2602.18884)

**Zhenkun Gao**, Xuhong Wang, Xin Tan, Yuan Xie

***International Conference on Learning Representations (ICLR) 2026***

[[Paper]](https://arxiv.org/abs/2602.18884) [[Code]](https://github.com/Stephen-gzk/TPRU)

*We build TPRU, a large-scale high-quality dataset for temporal and procedural understanding with three complementary tasks (temporal reordering, next-frame prediction, and previous-frame recall), and fine-tune Qwen2.5-VL (3B/7B/32B) with GRPO-based reinforcement learning. TPRU-7B achieves significant gains on public multi-image benchmarks such as MUIRBench and LEGO-Puzzles, boosting TPRU-Test accuracy from 50.33% to 75.70%.*

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report</div><img src='images/videosearcher.png' alt="videosearcher" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**VideoSearcher: Empowering Video Deep Research with Multi-Tool Agentic Reasoning via Reinforcement Learning**](https://arxiv.org/abs/2607.02927)

**Zhenkun Gao\***, Yicheng Bao\*, Jinlong Peng\*, Xueheng Li\*, Theo Huang\*, Bangwei Liu, Kunquan Li, Zhenye Gan, Tao Hu, Chengjun Xie, Mingqian Yang, Xuanhua He, Zhizhong Zhang, Xin Tan, Chengjie Wang, Yuan Xie

***Technical Report***

[[Paper]](https://arxiv.org/abs/2607.02927) [[Code]](https://github.com/Stephen-gzk/VideoSearcher)

*We propose VideoSearcher, a closed-loop multi-tool agent framework for Video Deep Research, which unifies key-frame localization, local zoom-in, image search, and web search for video clue grounding, open-web retrieval, and evidence integration. We further develop a video-centric training data pipeline and BiSPO, a dual-branch sequence-level RL algorithm that decouples answer-accuracy optimization from tool-use behavior optimization. VideoSearcher-8B reaches an average score of 57.66% on 8 search-oriented benchmarks, outperforming the Qwen3-VL-8B agentic baseline by 15.71% on average.*

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/memory_explorer.png' alt="memoryexplorer" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Explore with Long-term Memory: A Benchmark and Multimodal LLM-based Reinforcement Learning Framework for Embodied Exploration**](https://arxiv.org/abs/2601.10744)

Sen Wang, Bangwei Liu, **Zhenkun Gao**, Lizhuang Ma, Xuhong Wang, Yuan Xie, Xin Tan

***IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2026***

[[Paper]](https://arxiv.org/abs/2601.10744)

*We develop MemoryExplorer, a multimodal LLM-based embodied exploration framework targeting memory maintenance, environment exploration, and decision planning in long-horizon complex tasks. The model is trained with GRPO-based reinforcement learning to actively leverage long-term memory, unifying cognition, memory, and decision-making of embodied agents. I mainly contributed to building the core evaluation pipeline and writing the experimental sections.*

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Position Paper</div><img src='images/embodied.png' alt="trustworthy-eai" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Towards Safe and Trustworthy Embodied AI: Foundations, Status, and Prospects**](https://openreview.net/pdf?id=Eu6Yt21Alv)

Xin Tan, Bangwei Liu, Yicheng Bao, Qijian Tian, **Zhenkun Gao**, Xiongbin Wu, Zhihao Luo, Sen Wang, Yuqi Zhang, Xuhong Wang, Chaochao Lu, Bowen Zhou

***Position Paper***

[[Paper]](https://openreview.net/pdf?id=Eu6Yt21Alv) [[News]](https://mp.weixin.qq.com/s/CgBf-ZvMgfsWOrFlGKPZ8g)

*A position paper on safe and trustworthy Embodied AI (EAI). We deconstruct the workflow of embodied agents into four core stages — instruction understanding, environmental perception, behavior planning, and physical interaction — systematically review the safety and trustworthiness challenges at each stage, and propose a five-level maturity roadmap towards proactive, intrinsically safe EAI systems.*

</div>
</div>


# 💼 Internships

- *2026.01 - Present* &ensp; **Research Intern**, [Tencent](https://www.tencent.com/en-us/) · Mentor [Jinlong Peng](https://pjl1995.github.io/)
- *2024.10 - 2026.01*&ensp; **Research Intern**, [Shanghai AI Laboratory](https://www.shlab.org.cn/) · Mentor [Xuhong Wang](https://wangxuhongcn.github.io/) 


# 📖 Educations

- *2024.09 - Present* &ensp; **M.S. in Computer Science and Technology**, [East China Normal University (ECNU)](https://english.ecnu.edu.cn/), Shanghai, China
- *2020.09 - 2024.06* &ensp; **B.Eng. in Software Engineering**, [Xiamen University (XMU)](https://en.xmu.edu.cn/), Xiamen, China · GPA: 3.678/4.00 (Rank: 14/136)


# 🏅 Selected Awards

- *2024.06* &ensp; Outstanding Graduate of Xiamen University
- *2020 - 2024* &ensp; Merit Student of Xiamen University (Twice)
- *2020 - 2024* &ensp; First-Class Academic Excellence Scholarship, Xiamen University (Twice)
- *2022.09* &ensp; Academic Innovation Scholarship, Xiamen University
- *2020 - 2024* &ensp; Outstanding Communist Youth League Member, Xiamen University (Three Times)


# 💻 Skills

- **Programming & Frameworks**: Python, C/C++, and PyTorch, with hands-on experience in model training, evaluation, and engineering implementation.
- **Multimodal Models**: Supervised fine-tuning and RL fine-tuning (e.g., GRPO) of VLMs/MLLMs, with research experience in multi-image understanding, video understanding, and embodied AI.
