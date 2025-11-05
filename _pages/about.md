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

I am a second-year PhD student at [University of Illinois Urbana-Champaign (UIUC)](https://illinois.edu) advised by Professor [Olgica Milenkovic](https://publish.illinois.edu/milenkovic/) (IEEE Fellow). I graduated from [Shanghai Jiao Tong University (SJTU)](https://www.sjtu.edu.cn/) with a bachelor's degree, advised by Professor [Siheng Chen](https://siheng-chen.github.io/). My research interests focus on **Trustworthy AI**, **Large Language Models (LLMs)**, and **LLM Agents**, with particular emphasis on adversarial robustness, machine unlearning, and privacy-preserving techniques for foundation models and facilitate LLM agents to master real-world, diverse and scaling MCP (Model Context Protocol) tools.

My research interest includes trustworthy AI, large language models, and LLM agents. I have published papers at top-tier conferences including NeurIPS, CAV. Please check my <a href='https://scholar.google.com/citations?user=pP3j-KYAAAAJ&hl=en'>Google Scholar profile</a> for more details (<a href='https://scholar.google.com/citations?user=pP3j-KYAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

If you are seeking any form of academic cooperation, please feel free to email me at peizhin2@illinois.edu.

# 🔥 News
- *2025*: &nbsp;🎉🎉 Two papers accepted to **NeurIPS 2025**!
- *2024*: &nbsp;🎉🎉 Started PhD program at University of Illinois Urbana-Champaign!
- *2024*: &nbsp;🎉🎉 Graduated from Shanghai Jiao Tong University as **Outstanding Graduates in the City of Shanghai** !

# 📝 Publications 

## Conference Papers

**P. Niu**, Y. Wang, V. Rana, C. Rupakheti, A. Pandey, and O. Milenkovic, "A Highly Efficient and Chemical Motif-Preserving Molecule Generation Platform," **NeurIPS 2025**.

R. Wei*, **P. Niu***, H. Hao-Hsun Hsu, R. Wu, H. Yin, M. Ghassemi, Y. Li, V. K. Potluru, E. Chien, K. Chaudhuri, O. Milenkovic, and P. Li, "Do LLMs Really Forget? Evaluating Unlearning with Knowledge Correlation and Confidence Awareness," **NeurIPS 2025**.

T. Wei, L. Marzari*, K. S. Yun*, H. Hu*, **P. Niu***, X. Luo, and C. Liu, "ModelVerification.jl: A Comprehensive Toolbox for Formally Verifying Deep Neural Networks," **CAV 2024**.

## Journal Papers

T. Wei, Z. Wang, **P. Niu**, A. Abuduweili, W. Zhao, C. Hutchison, E. Sample, and C. Liu, "Improve Certified Training with Signal-to-Noise Ratio Loss to Decrease Neuron Variance and Increase Neuron Stability," **TMLR 2024**.

## Under Review

**P. Niu***, E. Ma*, H. Zhou, D. Zhou, H. Zhang, S. R. Etesami, and O. Milenkovic, "GUARD: Guided Unlearning and Retention via Data Attribution for Large Language Models," Submitted to **ICLR 2026**.

W. Wang, **P. Niu**, Z. Xu, Z. Chen, J. Du, Y. Du, X. Pang, K. Huang, Y. Wang, Q. Yan, and S. Chen, "MCP-Flow: Facilitating LLM Agents to Master Real-World, Diverse and Scaling MCP Tools," Submitted to **ICLR 2026**.

*Equal contribution

# 🎖 Honors and Awards
- *2025* NeurIPS 2025 Travel Award
- *2024* Outstanding Graduates in the City of Shanghai
- *2022* National Scholarship of China (Top 1% nationwide)
- *2022* First-class Scholarship of SJTU
- *2022* Excellent Student Cadre of SJTU

# 📖 Educations

- *Sep 2024 - Present*, **PhD in Electrical and Computer Engineering**, University of Illinois Urbana-Champaign (UIUC), USA
  - GPA: 4.0/4.0
  - Advisor: [Olgica Milenkovic](https://publish.illinois.edu/milenkovic/) (IEEE Fellow)
  - Research Direction: Trustworthy AI, LLMs, LLM Agent

- *Sep 2020 - Jun 2024*, **Bachelor of Electronic Science and Technology**, Shanghai Jiao Tong University (SJTU), China
  - GPA: 90.52/100 (Major: 90.93/100)
  - Advisor: [Siheng Chen](https://siheng-chen.github.io/)
  - Ranking: **Top 1 of 65** in department

# 🔬 Research Experience

**University of Illinois Urbana-Champaign** (Sep 2024 - Present)\\
*Research Assistant | Advisor: Professor Olgica Milenkovic (IEEE Fellow)*
- Developed CKA-Agent achieving **95-98% attack success rates** on commercial LLMs, outperforming SOTA by 20-50% [To be uploaded to arXiv soon]
- Proposed GUARD framework for LLM unlearning with adaptive data attribution, maintaining model utility while ensuring effective forgetting [Submitted to ICLR 2026]
- Designed evaluation framework revealing current unlearning strategies overestimate effectiveness by **20-30%** [**NeurIPS 2025**]
- Created DMol molecule generation model reducing diffusion steps by **10-fold** and runtime by half [**NeurIPS 2025**]

**Shanghai Jiao Tong University** (Jul 2025 - Present)\\
*Research on MCP Tools and LLM Agents | Advisor: Professor [Siheng Chen](https://siheng-chen.github.io/)*
- Built automated pipeline collecting data from **1,166 MCP servers and 11,536 tools**, producing 68,733 instruction pairs
- Developed **MCP-Flow**, a web-agent-driven framework for large-scale MCP tool integration and model training, facilitating LLM agents to master real-world, diverse and scaling MCP tools [Submitted to ICLR 2026]

**Carnegie Mellon University** (Jun 2023 - Jan 2024)\\
*Research Assistant | Advisor: Professor Changliu Liu*
- Extended Signal-to-Noise Ratio into robustness domain, addressing over-regularization in certified training [**TMLR 2024**]
- Developed unified Julia-based framework integrating mainstream verification algorithms [**CAV 2024**]

# 💬 Services
- **Program Committee or Reviewer**: NeurIPS, ICML, ICLR
- **Leadership**: Student Union of School of Electronic Information and Electrical Engineering, Department Secretary
