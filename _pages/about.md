---
permalink: /
title: "🐱✍️🏀💪"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## 👋 Hi, I'm Jiang Yue
Hello! My name is Jiang Yue. I am currently a PhD student at Nanyang Technological University (NTU) under the Alibaba-NTU Joint Talent Programme supervised by Prof. Cong Gao. I received my Bachelor's degree from NTU and my Master's degree from the National University of Singapore (NUS). My research focuses on spatial-temporal data mining, artificial intelligence, and machine learning. I am interested in developing advanced machine learning models to tackle practical challenges such as spatio-temporal data analysis, spatio-temporal LLMs and foundation models, AI-driven decision-making, and the application of machine learning techniques in various domains.

📧 Email: yue013@e.ntu.edu.sg
📱 Weixin:  <img src="assets/wechat.jpg" alt="WeChat" width="100" />

---

Education
======
* **Ph.D. in Computer Science**, Nanyang Technological University (NTU), *Aug 2022 – Present*  
  College of Computing and Data Science (CCDS)

* **M.Eng. in Mechanical Engineering**, National University of Singapore (NUS), *Jan 2020 – Jan 2022*

* **B.Eng. in Aerospace Engineering**, Nanyang Technological University (NTU), *Aug 2013 – May 2017*  
  First Class Honours · NTU President Scholar (2014–2015) · Dean’s List (Top 5%) (2015–2016) · Senior Middle School Scholarship (MOE, 2012–2017)

Work experience
======
* **Aug 2022 – Present: Researcher (PhD Candidate)**  
  *Alibaba Cloud (Singapore) / NTU*  
  - Research on data + AI: spatio-temporal learning, time-series forecasting, LLMs/foundation models for urban computing.  
  - Intelligent data systems and optimization with LLMs.

* **Jun 2021 – Jul 2022: Research Associate**  
  *Nanyang Technological University (NTU)*  
  - Collaborated with **NCS** & **LTA** on an AI-enabled smart car-park system.  
  - Collaborated with **ST Engineering** on an AI-enabled trajectory analytics project.

* **Jul 2017 – May 2021: Senior/Design Engineer**  
  *ASM Pacific Technology*  
  - Mechanical system design for industrial material-handling.  
  - Drove process improvements and operational efficiency.

* **Dec 2015 – Jul 2016: 3D Printing Engineer Intern**  
  *SIMTECH, A*STAR*  
  - Additive manufacturing for high-precision engineering; metallic 3D printing for bone replacement applications.

Publications
======
<ul>
{% for post in site.publications reversed %}
  <li style="margin-bottom: 15px;">
    {% if post.paperurl %}
      <b><a href="{{ post.paperurl }}" style="text-decoration:none;">{{ post.title }}</a></b>
    {% else %}
      <b>{{ post.title }}</b>
    {% endif %}
    <br>
    
    <span style="font-size: 0.95em;">{{ post.excerpt }}</span>
    <br>
    
    <i style="color: #666;">{{ post.venue }}, {{ post.date | date: "%Y" }}</i>
  </li>
{% endfor %}
</ul>

Skills
======
* **Python** (PyTorch, Hugging Face, LLM inference & QLoRA/LoRA fine-tuning, data processing)  
* **Spatio-Temporal ML** (time-series forecasting, STGNNs, retrieval-augmented TS, Urban/transport data)  
* **Tools**: Git/GitHub, JAX/NumPy/Pandas, Docker, Linux  
* **Languages**: Mandarin, English

Service
======
* **Reviewer**: TKDE 2024–2025, KDD 2025, EMNLP 2024  
* **External Reviewer**: NeurIPS 2025, SIGSPATIAL 2025, VLDB 2023, CIKM 2023/2025

