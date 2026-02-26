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

I am a fifth-year PhD student in the [**School of Computer Science**](https://cs.pku.edu.cn/) at [**Peking University**](https://www.pku.edu.cn/), advised by Prof. [**Zongqing Lu**](https://z0ngqing.github.io/). I received my Bachelor's degree in 2021 from the **School of Information Science and Technology** at **PKU**.

My research interests lie in Multimodal Large Language Models (MLLMs), Embodied Artificial Intelligence, and Reinforcement Learning. In particular, I focus on vision-language understanding and generation, vision-language-action (VLA) modeling, and LLM-based autonomous agents.


# 🔥 News
- *2026.02*: &nbsp;🎉🎉 Two papers accepted by CVPR 2026.
- *2025.09*: &nbsp;🎉🎉 One paper accepted by NeurIPS 2025.
- *2025.06*: &nbsp;🎉🎉 Two papers accepted by ICCV 2025.
- *2025.01*: &nbsp;🎉🎉 One paper accepted by ICLR 2025.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/vipa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Spatial-Aware VLA Pretraining through Visual-Physical Alignment from Human Videos**](https://arxiv.org/abs/2512.13080)

Hao Luo, Ye Wang, Wanpeng Zhang, Haoqi Yuan, **Yicheng Feng**, Haiweng Xu, Sipeng Zheng, Zongqing Lu

*The IEEE/CVF Conference on Computer Vision and Pattern Recognition, **CVPR** 2026*

[[Paper](https://arxiv.org/abs/2512.13080)][[PDF](https://arxiv.org/pdf/2512.13080)][[Website](https://research.beingbeyond.com/vipa-vla)][[Code](https://github.com/BeingBeyond/VIPA-VLA)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/jala.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Joint-Aligned Latent Action: Towards Scalable VLA Pretraining in the Wild**](https://arxiv.org/abs/2602.21736)

Hao Luo, Ye Wang, Wanpeng Zhang, Haoqi Yuan, **Yicheng Feng**, Haiweng Xu, Sipeng Zheng, Zongqing Lu

*The IEEE/CVF Conference on Computer Vision and Pattern Recognition, **CVPR** 2026*

[[Paper](https://arxiv.org/abs/2602.21736)][[PDF](https://arxiv.org/pdf/2602.21736)][[Website](https://research.beingbeyond.com/jala)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/beingh05.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Being-H0.5: Scaling Human-Centric Robot Learning for Cross-Embodiment Generalization**](https://arxiv.org/abs/2601.129937)

Hao Luo†, Ye Wang†, Wanpeng Zhang†, Sipeng Zheng†, Ziheng Xi, Chaoyi Xu, Haiweng Xu, Haoqi Yuan, Chi Zhang, Yiqing Wang, **Yicheng Feng**, Zongqing Lu

*†: equal contribution*

*arxiv preprint*

[[Paper](https://arxiv.org/abs/2601.12993)][[PDF](https://arxiv.org/pdf/2601.12993)][[Website](https://research.beingbeyond.com/being-h05)][[Code](https://github.com/BeingBeyond/Being-H)][[Huggingface](https://huggingface.co/collections/BeingBeyond/being-h05)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/dig-flow.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**DiG-Flow: Discrepancy-Guided Flow Matching for Robust VLA Models**](https://arxiv.org/abs/2512.01715)

Wanpeng Zhang, Ye Wang, Hao Luo, Haoqi Yuan, **Yicheng Feng**, Sipeng Zheng, Qin Jin, Zongqing Lu

*arxiv preprint*

[[Paper](https://arxiv.org/abs/2512.01715)][[PDF](https://arxiv.org/pdf/2512.01715)][[Website](https://beingbeyond.github.io/DiG-Flow)][[Code](https://github.com/BeingBeyond/DiG-Flow)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/overview.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Being-H0: Vision-Language-Action Pretraining from Large-Scale Human Videos.**](https://arxiv.org/abs/2507.15597)

Hao Luo†, **Yicheng Feng†**, Wanpeng Zhang†, Sipeng Zheng†, Ye Wang, Haoqi Yuan, Jiazheng Liu, Chaoyi Xu, Qin Jin, Zongqing Lu

*†: equal contribution*

*arxiv preprint*

[[Paper](https://arxiv.org/abs/2507.15597)][[PDF](https://arxiv.org/pdf/2507.15597)][[Website](https://beingbeyond.github.io/Being-H0)][[Code](https://github.com/BeingBeyond/Being-H0)][[Huggingface](https://huggingface.co/BeingBeyond/Being-H0)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/being-0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Being-0: A humanoid robotic agent with vision-language models and modular skills**](https://arxiv.org/abs/2503.12533)

Haoqi Yuan, Yu Bai, Yuhui Fu, Bohan Zhou, **Yicheng Feng†**, Xinrun Xu, Yi Zhan, Borje F. Karlsson, Zongqing Lu

*arxiv preprint*

[[Paper](https://arxiv.org/abs/2503.12533)][[PDF](https://arxiv.org/pdf/2503.12533)][[Website](https://beingbeyond.github.io/Being-0)][[Code](https://github.com/BeingBeyond/Being-0)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/openmmego.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**OpenMMEgo: Enhancing Egocentric Understanding for LMMs with Open Weights and Data.**

Hao Luo, Zihao Yue, Wanpeng Zhang, **Yicheng Feng**, Sipeng Zheng, Deheng Ye, Zongqing Lu

*Conference on Neural Information Processing Systems, **NeurIPS** 2025*

</div>
</div>

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
- *2026.02 - Present*, **BeingBeyond** *Embodied AI*
- *2025.08 - 2026.02*, **ByteDance Seed** *Video Generation Models*
- *2025.03 - 2025.08*, **BeingBeyond** *Multimodal LLMs / Embodied AI*
- *2023.03 - 2025.03*, **Beijing Academy of Artificial Intelligence (BAAI)** *Multimodal LLMs / Embodied AI*
