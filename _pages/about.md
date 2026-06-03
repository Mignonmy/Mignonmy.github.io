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

# About Me
I am currently a second-year Master's student in Computer Science at [Northeastern University](https://neu.edu.cn/), focusing on Retrieval-Augmented Generation. Google Scholar: <a href='https://scholar.google.com/citations?user=9YgV-8MAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>


Now I am engaged in research internships at [NEUIR Lab](https://neuir.github.io/) under the guidance of Associate Professor [Zhenghao Liu](https://edwardzh.github.io/), as well as at [THUNLP](https://nlp.csai.tsinghua.edu.cn/), supervised by [Yukun Yan](https://scholar.google.com/citations?hl=en&user=B88nSvIAAAAJ&view_op=list_works).



# 🔎 Research Interests
My research focuses on agentic systems that integrate external knowledge, efficient reasoning, and scalable infrastructure. These span:
- **How can models utilize external knowledge**: Retrieval-Augmented Generation ([RankCoT](https://aclanthology.org/2025.acl-long.629/), [KAIR](https://arxiv.org/abs/2601.16462), [Cost-Aware](https://arxiv.org/abs/2606.02245)), Deep Research ([EigentSearch-Q+](https://dl.acm.org/doi/10.1145/3786335.3813186#artseq-00002)), AI Memory.
- **How can models reason efficiently**: Reasoning Compression ([Mixed-Policy Distillation](https://arxiv.org/abs/2605.08776)), Multi-Modal Reasoning.
- **Agent Infrastructure**: [UltraRAG 2.0](https://github.com/OpenBMB/UltraRAG).



👀<span style="color:#8952ee; font-weight:bold;">
I am looking for a Ph.D. position starting in Fall 2027 and would love to explore potential collaborations. Let’s connect!
</span> 

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2026.04*: &nbsp;🎉 Our paper EigentSearch-Q+ is accepted by ACM CAIS 2026 Demos!
- *2025.08*: &nbsp;🎉 We released [UltraRAG 2.0](https://github.com/OpenBMB/UltraRAG) [![](https://img.shields.io/github/stars/OpenBMB/UltraRAG?style=social&label=Code+Stars)](https://github.com/OpenBMB/UltraRAG), an low-code framework for building complex RAG systems!
- *2025.05*: &nbsp;🎉 Our paper RankCoT is accepted by ACL 2025!


# 📝 Publications 
> \* indicates **equal contribution**, and † indicates **corresponding author**.

<!-- Cost-Aware -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv Print</div><img src='images/Cost-Aware.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

# When Knowledge Is Not Free: Cost-Aware Evidence Selection in Retrieval-Augmented Generation

**Mingyan Wu<sup>\*</sup>**, Han Yang<sup>\*</sup>, [Omer Ben-Porat](https://scholar.google.com/citations?user=GGHVmOsAAAAJ), [Yftah Ziser<sup>†</sup>](https://scholar.google.com/citations?user=37SMCrsAAAAJ)

[**📃Paper**](https://arxiv.org/abs/2606.02245) \| [**📄PDF**](https://arxiv.org/pdf/2606.02245) \| [![GitHub stars](https://img.shields.io/github/stars/Mignonmy/Cost-Aware?style=social)](https://github.com/Mignonmy/Cost-Aware)
- This work introduces cost-aware RAG, a setting where retrieved evidence is assigned accesscost tiers and systems must answer under an explicit evidence-access budget. We instantiate this setting by augmenting MS MARCO v2.1 with access-friction tiers and evaluate budgeted evidence selection across generaldomain and domain-specific QA benchmarks.
</div>
</div>



<!-- MPD -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv Print</div><img src='images/MPD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# Reasoning Compression with Mixed-Policy Distillation

Han Yang<sup>\*</sup>, **Mingyan Wu<sup>\*</sup>**, [Bailan He](https://scholar.google.com/citations?user=n5zUQtAAAAAJ), [Zeyu Cao](https://scholar.google.com/citations?user=MiIz8tYAAAAJ), [Sikuan Yan](https://scholar.google.com/citations?user=2DRWdnIAAAAJ), [Kevin Qinghong Lin](https://scholar.google.com/citations?user=EvbGjlUAAAAJ), [Zifeng Ding<sup>*†</sup>](https://scholar.google.com/citations?user=8RapuD4AAAAJ)

[**📃Paper**](https://arxiv.org/abs/2605.08776) \| [**📄PDF**](https://arxiv.org/pdf/2605.08776) 
- This work proposes Mixed-Policy Distillation (MPD), a reasoning compression framework that transfers concise reasoning behavior from a larger-sized teacher to a smaller student by distilling teacher-compressed student trajectories. This preserves student-policy exploration while injecting teacher-guided compression.
</div>
</div>

<!-- EigentSearch-Q+ -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM CAIS 2026 Demos</div><img src='images/EigentSearch-Q+.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# EigentSearch-Q+: Enhancing Deep Research Agents with Structured Reasoning Tools

[Boer Zhang](https://scholar.google.com/citations?user=0BJ49hwAAAAJ), **Mingyan Wu**, [Dongzhuoran Zhou](https://scholar.google.com/citations?user=TbZH2gUAAAAJ), [Yuqicheng Zhu](https://scholar.google.com/citations?user=TE5jy5cAAAAJ), Wendong Fan, [Puzhen Zhang](https://scholar.google.com/citations?user=MuRzXpgAAAAJ), [Zifeng Ding](https://scholar.google.com/citations?user=8RapuD4AAAAJ), [Guohao Li](https://scholar.google.com/citations?user=J9K-D0sAAAAJ), [Yuan He<sup>†</sup>](https://scholar.google.com/citations?user=sCXUhQcAAAAJ)

[**📃Paper**](https://dl.acm.org/doi/10.1145/3786335.3813186#artseq-00002) \| [**📄PDF**](https://dl.acm.org/doi/epdf/10.1145/3786335.3813186) \| [![GitHub stars](https://img.shields.io/github/stars/camel-ai/eigent_search?style=social)](https://github.com/camel-ai/eigent_search)

<!-- \| [![](https://img.shields.io/github/stars/camel-ai/eigent_search?label=Code+Stars)](https://github.com/camel-ai/eigent_search) -->

- This work introduces Q+, a set of query and evidence processing tools that make web search more deliberate by guiding query planning, monitoring search progress, and extracting evidence from long web snapshots. 
</div>
</div>

<!-- RankCoT -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/RankCoT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# RankCoT: Refining Knowledge for Retrieval-Augmented Generation through Ranking Chain-of-Thoughts

**Mingyan Wu**, [Zhenghao Liu<sup>†</sup>](https://scholar.google.com/citations?user=4vrZRk0AAAAJ),[Yukun Yan<sup>†</sup>](https://scholar.google.com/citations?user=B88nSvIAAAAJ), [Xinze Li](https://scholar.google.com/citations?user=Feo2PhwAAAAJ), [Shi Yu](https://scholar.google.com/citations?user=xcMVPTgAAAAJ), [Zheni Zeng](https://scholar.google.com/citations?hl=zh-CN&user=CM3VSeQAAAAJ), [Yu Gu](https://scholar.google.com/citations?user=IDYbTZwAAAAJ), [Ge Yu](https://scholar.google.com/citations?user=HClMOmUAAAAJ)

[**📃Paper**](https://aclanthology.org/2025.acl-long.629/) \| [**📄PDF**](https://aclanthology.org/2025.acl-long.629.pdf) \| [![GitHub stars](https://img.shields.io/github/stars/NEUIR/RankCoT?style=social)](https://github.com/NEUIR/RankCoT)

- This work leverages the strengths of both ranking and summarization to effectively refine the knowledge from retrieval results, thereby aiding LLMs in generating more accurate responses.
</div>
</div>

<!-- GraphAnchor
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv Print</div><img src='images/GraphAnchor.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# Graph-Anchored Knowledge Indexing for Retrieval-Augmented Generation

[Zhenghao Liu<sup>*†</sup>](https://scholar.google.com/citations?user=4vrZRk0AAAAJ), **Mingyan Wu<sup>*</sup>**, [Xinze Li](https://scholar.google.com/citations?user=Feo2PhwAAAAJ), [Yukun Yan<sup>†</sup>](https://scholar.google.com/citations?user=B88nSvIAAAAJ), [Shuo Wang](https://scholar.google.com/citations?user=5vm5yAMAAAAJ), [Cheng Yang](https://scholar.google.com/citations?user=OlLjVUcAAAAJ), Minghe Yu, [Zheni Zeng](https://scholar.google.com/citations?hl=zh-CN&user=CM3VSeQAAAAJ), [Maosong Sun](https://scholar.google.com/citations?user=zIgT0HMAAAAJ)

[**📃Paper**](https://www.arxiv.org/abs/2601.16462) \| [**📄PDF**](https://www.arxiv.org/pdf/2601.16462) \| [![](https://img.shields.io/github/stars/NEUIR/GraphAnchor?style=social&label=Code+Stars)](https://github.com/NEUIR/GraphAnchor)

- This work reconceptualizes knowledge graphs as dynamically evolving indices that anchor salient entities and relations to guide iterative retrieval and answer generation.
</div>
</div> -->

<!-- KAIR -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv Print</div><img src='images/KAIR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# Finding What Matters: Anchoring Context Knowledge with Evolving Indices for Iterative Retrieval

**Mingyan Wu<sup>\*</sup>**, [Zhenghao Liu<sup>*†</sup>](https://scholar.google.com/citations?user=4vrZRk0AAAAJ), [Xinze Li](https://scholar.google.com/citations?user=Feo2PhwAAAAJ), Yuqing Lan, [Yukun Yan<sup>†</sup>](https://scholar.google.com/citations?user=B88nSvIAAAAJ), [Shuo Wang](https://scholar.google.com/citations?user=5vm5yAMAAAAJ), [Cheng Yang](https://scholar.google.com/citations?user=OlLjVUcAAAAJ), Minghe Yu, [Zheni Zeng](https://scholar.google.com/citations?hl=zh-CN&user=CM3VSeQAAAAJ), [Maosong Sun](https://scholar.google.com/citations?user=zIgT0HMAAAAJ)

[**📃Paper**](https://arxiv.org/abs/2601.16462) \| [**📄PDF**](https://arxiv.org/pdf/2601.16462) \| [![GitHub stars](https://img.shields.io/github/stars/NEUIR/KAIR?style=social)](https://github.com/NEUIR/KAIR)

- This work proposes a Knowledge Anchoring framework for Iterative Retrieval that anchors knowledge within retrieved knowledge to guide LLMs to locate the key information during iterative retrieval and answer generation.
</div>
</div>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2024.09 - now*, M.S. School of Computer Science and Engineering, Northeastern University
- *2020.09 - 2024.07*, B.S. School of Computer Science, Yangtze University

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2024.04 - now*, [THUNLP](https://nlp.csai.tsinghua.edu.cn/), [Tsinghua University](https://www.tsinghua.edu.cn/), Beijing.
- *2023.10 - now*, [NEUIR Lab](https://neuir.github.io), [Northeastern University](https://neu.edu.cn/), Shenyang.

# 🎼 Amateur
- Dancing 💃: I've been danced for about nine years. My favorite dance styles are jazz and hiphop. And I also used to be a part-time dance teacher.
- Guitar 🎸: I am a beginner of guitar and I usually play folk guitar. 
- Swimming 🏊: I’ve recently got into swimming and would like to learn more about it.
  
  If you share these interests, I would be glad to connect and grow together 📞.
