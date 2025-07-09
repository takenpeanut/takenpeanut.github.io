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

I am a fourth-year PhD student in the [**School of Computer Science**](https://cs.pku.edu.cn/) at [**Peking University**](https://www.pku.edu.cn/), advised by Prof. [**Zongqing Lu**](https://z0ngqing.github.io/). I received my Bachelor's degree in 2021 from the **School of Information Science and Technology** at **PKU**.

My research interests lie in Multimodal Large Language Models (MLLMs), Embodied Artificial Intelligence, and Reinforcement Learning. In particular, I focus on vision-language understanding and generation, vision-language-action (VLA) modeling, and LLM-based autonomous agents.


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 Two papers accepted by ICCV 2025.
- *2025.01*: &nbsp;🎉🎉 One paper accepted by ICLR 2025.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/VideoOrion.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**VideoOrion: Tokenizing Object Dynamics in Videos.**](https://arxiv.org/abs/2411.16156)

**Yicheng Feng†**, Yijiang Li†, Wanpeng Zhang, Hao Luo, Zihao Yue, Sipeng Zheng, Zongqing Lu

*†: equal contribution*
*International Conference on Computer Vision, **ICCV** 2025*
[[Paper](https://arxiv.org/abs/2411.16156)][[PDF](https://arxiv.org/pdf/2411.16156)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/Being-VL-0.5.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Unified Multimodal Understanding via Byte-Pair Visual Encoding.**](https://arxiv.org/abs/2506.23639)

Wanpeng Zhang, **Yicheng Feng**, Hao Luo, Yijiang Li, Zihao Yue, Sipeng Zheng, Zongqing Lu
*International Conference on Computer Vision, **ICCV** 2025*
[[Paper](https://arxiv.org/abs/2506.23639)][[PDF](https://arxiv.org/pdf/2506.23639)][[Code](https://github.com/BeingBeyond/being-vl-0.5)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/bpe.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**From Pixels to Tokens: Byte-Pair Encoding on Quantized Visual Modalities.**](https://openreview.net/forum?id=3TnLGGHhNx)

Wanpeng Zhang, Zilong Xie, **Yicheng Feng**, Yijiang Li, Xingrun Xing, Sipeng Zheng, Zongqing Lu
*International Conference on Learning Representations, **ICLR** 2025*
[[Paper](https://openreview.net/forum?id=3TnLGGHhNx)][[PDF](https://openreview.net/pdf?id=3TnLGGHhNx)][[Code](https://github.com/BeingBeyond/being-vl-0)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/Unicode.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Unicode: Learning a unified codebook for multimodal large language models.**](https://arxiv.org/abs/2403.09072)

Sipeng Zheng, Bohan Zhou, **Yicheng Feng**, Ye Wang, Zongqing Lu
*European Conference on Computer Vision, **ECCV** 2024*
[[Paper](https://arxiv.org/abs/2403.09072)][[PDF](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01331.pdf)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2024</div><img src='images/LLaMArider.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**LLaMA Rider: Spurring Large Language Models to Explore the OpenWorld.**](https://arxiv.org/abs/2310.08922)

**Yicheng Feng**, Yuxuan Wang, Jiazheng Liu, Sipeng Zheng, Zongqing Lu
*Findings of the Association for Computational Linguistics, **NAACL** 2024*
[[Paper](https://arxiv.org/abs/2310.08922)][[PDF](https://aclanthology.org/2024.findings-naacl.292.pdf)][[Code](https://github.com/PKU-RL/LLaMA-Rider)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/SteveEye.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Steve-eye: Equipping llm-based embodied agents with visual perception in open worlds.**](https://openreview.net/forum?id=NltzxpG0nz)

Sipeng Zheng, Jiazheng Liu, **Yicheng Feng**, Zongqing Lu
*International Conference on Learning Representations, **ICLR** 2024*
[[Paper](https://openreview.net/forum?id=NltzxpG0nz)][[PDF](https://openreview.net/pdf?id=NltzxpG0nz)][[Code](https://github.com/BAAI-Agents/Steve-Eye)][[Website](https://sites.google.com/view/steve-eye)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/relationship.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Learning Multi-Object Positional Relationships via Emergent Communication.**](https://arxiv.org/abs/2302.08084)

**Yicheng Feng†**, Boshi An†, Zongqing Lu

*†: equal contribution*
*The Association for the Advancement of Artificial Intelligence, **AAAI** 2024*
[[Paper](https://arxiv.org/abs/2302.08084)][[PDF](https://arxiv.org/pdf/2302.08084)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2023</div><img src='images/symbolicmapping.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Multi-Agent Language Learning: Symbolic Mapping.**](https://aclanthology.org/2023.findings-acl.491/)

**Yicheng Feng**, Zongqing Lu
*Findings of the Association for Computational Linguistics: **ACL** 2023*
[[Paper](https://aclanthology.org/2023.findings-acl.491/)][[PDF](https://aclanthology.org/2023.findings-acl.491.pdf)]
</div>
</div>


# 🎖 Honors and Awards
- *2024.12* Outstanding Research Award, Peking University
- *2021.06* Outstanding Graduate Award, Peking University
- *2020.09* Merit Student Award, Peking University
- *2019.09* Huawei Scholarship, Peking University
- *2019.09* Merit Student Award, Peking University
- *2018.09* Academic Progress Award, Peking University

# 📖 Educations
- *2021.09 - Present*: **Ph.D. in Computer Science, Peking University**
- *2017.09 - 2021.06*: **B.Sc. in Intelligent Science and Technology, Peking University**

# 💻 Internships
- *2025.03 - Present*, **BeingBeyond** *Multimodal LLMs / Embodied AI*
- *2023.03 - 2025.03*, **Beijing Academy of Artificial Intelligence (BAAI)** *Multimodal LLMs / Embodied AI*
