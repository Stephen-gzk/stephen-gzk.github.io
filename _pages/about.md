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

- *2026.05* &ensp; **VideoSearcher** is submitted to EMNLP 2026! 🚀
- *2026.02* &ensp; [MemoryExplorer](https://arxiv.org/abs/2601.10744) is accepted by CVPR 2026! 🎉
- *2026.01* &ensp; [TPRU](https://arxiv.org/abs/2602.18884) is accepted by ICLR 2026! 🎉
- *2026.01* &ensp; I join [Tencent](https://www.tencent.com/en-us/) as a research intern! 🔬
- *2024.10* &ensp; I join [Shanghai AI Laboratory](https://www.shlab.org.cn/) as a research intern! 🔬
- *2024.09* &ensp; I start my M.S. journey at [ECNU](https://english.ecnu.edu.cn/)! 👨‍🎓
- *2024.06* &ensp; I graduate from [Xiamen University](https://en.xmu.edu.cn/) as an Outstanding Graduate! 👨‍🎓


# 📝 Publications

<!-- TODO: Replace images/500x300.png with a teaser figure of each paper, and complete the full author lists. -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/500x300.png' alt="tpru" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**TPRU: Advancing Temporal and Procedural Understanding in Large Multimodal Models**](https://arxiv.org/abs/2602.18884)

**Zhenkun Gao**, et al. (First Author)

***International Conference on Learning Representations (ICLR) 2026***

[[Paper]](https://arxiv.org/abs/2602.18884) [[Code]](https://github.com/Stephen-gzk/TPRU)

*We build TPRU, a large-scale high-quality dataset for temporal and procedural understanding with three complementary tasks (temporal reordering, next-frame prediction, and previous-frame recall), and fine-tune Qwen2.5-VL (3B/7B/32B) with GRPO-based reinforcement learning. TPRU-7B achieves significant gains on public multi-image benchmarks such as MUIRBench and LEGO-Puzzles, boosting TPRU-Test accuracy from 50.33% to 75.70%.*

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2026</div><img src='images/500x300.png' alt="videosearcher" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**VideoSearcher: Empowering Video Deep Research with Multi-Tool Agentic Reasoning via Reinforcement Learning**](https://github.com/Stephen-gzk/VideoSearcher)

**Zhenkun Gao**, et al. (First Author)

***Under Review at EMNLP 2026***

[[Code]](https://github.com/Stephen-gzk/VideoSearcher)

*We propose VideoSearcher, a closed-loop multi-tool agent framework for Video Deep Research, which unifies key-frame localization, local zoom-in, image search, and web search for video clue grounding, open-web retrieval, and evidence integration. We further develop a video-centric training data pipeline and BiSPO, a dual-branch sequence-level RL algorithm that decouples answer-accuracy optimization from tool-use behavior optimization. VideoSearcher-8B reaches an average score of 57.66% on 8 search-oriented benchmarks, outperforming the Qwen3-VL-8B agentic baseline by 15.71% on average.*

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/500x300.png' alt="memoryexplorer" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Explore with Long-term Memory: A Benchmark and Multimodal LLM-based Reinforcement Learning Framework for Embodied Exploration**](https://arxiv.org/abs/2601.10744)

**Zhenkun Gao** (Third Author), et al.

***IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2026***

[[Paper]](https://arxiv.org/abs/2601.10744)

*We develop MemoryExplorer, a multimodal LLM-based embodied exploration framework targeting memory maintenance, environment exploration, and decision planning in long-horizon complex tasks. The model is trained with GRPO-based reinforcement learning to actively leverage long-term memory, unifying cognition, memory, and decision-making of embodied agents. I mainly contributed to building the core evaluation pipeline and writing the experimental sections.*

</div>
</div>


# 💼 Internships

- *2026.01 - Present* &ensp; **Research Intern**, [Tencent](https://www.tencent.com/en-us/), China
  - Working on VideoSearcher: open-web retrieval, multimodal tool use, and multi-hop evidence reasoning for video understanding.
  - Contributed to the team's human-action understanding evaluation for videos, improving Qwen3.5-397B-A17B on camera motion and spatial attributes.
- *2024.10 - 2026.01* &ensp; **Research Intern**, [Shanghai AI Laboratory](https://www.shlab.org.cn/), Shanghai, China
  - Completed the research of TPRU, Explore with Long-term Memory, and a survey on trustworthy embodied AI, covering multi-image temporal understanding, embodied exploration, long-term memory modeling, and multimodal reinforcement learning.
  - Contributed to the Safactory platform and integrated an OpenAI-Gym-style EmbodiedGym into the team's sandbox for automated evaluation in embodied simulators.


# 📖 Educations

- *2024.09 - Present* &ensp; **M.S. Student**, School of Computer Science and Technology, East China Normal University (ECNU), Shanghai, China
  - Research: Multimodal Large Language Models, Video Deep Research, Agentic RL, and Embodied AI
- *2020.09 - 2024.06* &ensp; **B.Eng. in Software Engineering**, School of Informatics, Xiamen University (XMU), Xiamen, China
  - GPA: 3.678/4.00 (Rank: 14/136)


# 🏅 Selected Awards

- *2024.06* &ensp; Outstanding Graduate of Xiamen University
- *2020 - 2024* &ensp; Merit Student of Xiamen University
- *2020 - 2024* &ensp; First-Class Academic Excellence Scholarship, Xiamen University
- *2020 - 2024* &ensp; Academic Innovation Scholarship, Xiamen University
- *2020 - 2024* &ensp; Outstanding Communist Youth League Member, Xiamen University


# 💻 Skills

- **Programming & Frameworks**: Python, C/C++, and PyTorch, with hands-on experience in model training, evaluation, and engineering implementation.
- **Multimodal Models**: Supervised fine-tuning and RL fine-tuning (e.g., GRPO) of VLMs/MLLMs, with research experience in multi-image understanding, video understanding, and embodied AI.
