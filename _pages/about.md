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

My hobbies are dancing 💃 and guitar 🎸. My favorite dance styles are jazz and hiphop. I usually play folk guitar. If you share these interests, I would be glad to connect and grow together 📞.<br><br>


# 🔎 Research Interests
My research aims to advance autonomous agents capable of exploring, reasoning, and acting.
- **How can models utilize external knowledge**: Retrieval-Augmented Generation ([RankCoT](https://aclanthology.org/2025.acl-long.629/), [GraphAnchor](https://www.arxiv.org/abs/2601.16462)), Deep Research ([EigentSearch-Q+](https://arxiv.org/abs/2604.07927)), AI Memory.
- **How can models reason efficiently**: Love to explore collaborations!
- **Agent Infrastructure**: [UltraRAG](https://github.com/OpenBMB/UltraRAG).


👀<span style="color:#8952ee; font-weight:bold;">
I am looking for a Ph.D. position starting in Fall 2027 and would love to explore potential collaborations. Let’s connect!
</span> 

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.08*: &nbsp;🎉 We released [UltraRAG 2.0](https://github.com/OpenBMB/UltraRAG) [![](https://img.shields.io/github/stars/OpenBMB/UltraRAG?style=social&label=Code+Stars)](https://github.com/OpenBMB/UltraRAG), an low-code framework for building complex RAG systems!
- *2025.05*: &nbsp;🎉 Our paper RankCoT is accepted by ACL 2025!


# 📝 Publications 
> \* indicates **equal contribution**, and † indicates **corresponding author**.

<!-- EigentSearch-Q+ -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv Print</div><img src='images/EigentSearch-Q+.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# EigentSearch-Q+: Enhancing Deep Research Agents with Structured Reasoning Tools

[Boer Zhang](https://scholar.google.com/citations?user=0BJ49hwAAAAJ), **Mingyan Wu**, [Dongzhuoran Zhou](https://scholar.google.com/citations?user=TbZH2gUAAAAJ), [Yuqicheng Zhu](https://scholar.google.com/citations?user=TE5jy5cAAAAJ), Wendong Fan, Puzhen Zhang, [Zifeng Ding](https://scholar.google.com/citations?user=8RapuD4AAAAJ), [Guohao Li](https://scholar.google.com/citations?user=J9K-D0sAAAAJ), [Yuan He<sup>†</sup>](https://scholar.google.com/citations?user=sCXUhQcAAAAJ)

[**📃Paper**](https://arxiv.org/abs/2604.07927) \| [**📄PDF**](https://arxiv.org/pdf/2604.07927) \| [![](https://img.shields.io/github/stars/camel-ai/eigent_search?style=social&label=Code+Stars)](https://github.com/camel-ai/eigent_search)

- This work introduces Q+, a set of query and evidence processing tools that make web search more deliberate by guiding query planning, monitoring search progress, and extracting evidence from long web snapshots. 
</div>
</div>

<!-- RankCoT -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/RankCoT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# RankCoT: Refining Knowledge for Retrieval-Augmented Generation through Ranking Chain-of-Thoughts

**Mingyan Wu**, [Zhenghao Liu<sup>†</sup>](https://scholar.google.com/citations?user=4vrZRk0AAAAJ),[Yukun Yan<sup>†</sup>](https://scholar.google.com/citations?user=B88nSvIAAAAJ), [Xinze Li](https://scholar.google.com/citations?user=Feo2PhwAAAAJ), [Shi Yu](https://scholar.google.com/citations?user=xcMVPTgAAAAJ), [Zheni Zeng](https://scholar.google.com/citations?hl=zh-CN&user=CM3VSeQAAAAJ), [Yu Gu](https://scholar.google.com/citations?user=IDYbTZwAAAAJ), [Ge Yu](https://scholar.google.com/citations?user=HClMOmUAAAAJ)

[**📃Paper**](https://aclanthology.org/2025.acl-long.629/) \| [**📄PDF**](https://aclanthology.org/2025.acl-long.629.pdf) \| [![](https://img.shields.io/github/stars/NEUIR/RankCoT?style=social&label=Code+Stars)](https://github.com/NEUIR/RankCoT)

- This work leverages the strengths of both ranking and summarization to effectively refine the knowledge from retrieval results, thereby aiding LLMs in generating more accurate responses.
</div>
</div>

<!-- GraphAnchor -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv Print</div><img src='images/GraphAnchor.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# Graph-Anchored Knowledge Indexing for Retrieval-Augmented Generation

[Zhenghao Liu<sup>*†</sup>](https://scholar.google.com/citations?user=4vrZRk0AAAAJ), **Mingyan Wu<sup>*</sup>**, [Xinze Li](https://scholar.google.com/citations?user=Feo2PhwAAAAJ), [Yukun Yan<sup>†</sup>](https://scholar.google.com/citations?user=B88nSvIAAAAJ), [Shuo Wang](https://scholar.google.com/citations?user=5vm5yAMAAAAJ), [Cheng Yang](https://scholar.google.com/citations?user=OlLjVUcAAAAJ), Minghe Yu, [Zheni Zeng](https://scholar.google.com/citations?hl=zh-CN&user=CM3VSeQAAAAJ), [Maosong Sun](https://scholar.google.com/citations?user=zIgT0HMAAAAJ)

[**📃Paper**](https://www.arxiv.org/abs/2601.16462) \| [**📄PDF**](https://www.arxiv.org/pdf/2601.16462) \| [![](https://img.shields.io/github/stars/NEUIR/GraphAnchor?style=social&label=Code+Stars)](https://github.com/NEUIR/GraphAnchor)

- This work reconceptualizes knowledge graphs as dynamically evolving indices that anchor salient entities and relations to guide iterative retrieval and answer generation.
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
