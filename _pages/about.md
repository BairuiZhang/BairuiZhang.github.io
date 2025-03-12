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

Hi! Welcome to Bairui (Barry) Zhang's homepage. I am a senior in Computer Science at **Northeastern University**, where I GPA rank in the **top 2.6%** of my major with a GPA of **3.99/4.0**. Currently, I serve as a Research Assistant at **The Chinese University of Hong Kong, Shenzhen**, affiliated with the [CUHKSZ NLP Group](https://freedomintelligence.github.io/) under the supervision of [Prof. Benyou Wang](https://wabyking.github.io/old.html). Previously, I participated in a Research Camp led by **MIT** Professor [Manolis Kellis](https://web.mit.edu/manoli/), where I earned an **A** (98) and ranked **1st** in my team.

My research interests include Multimodal Large Language Models (MLLMs), AI Agent, AI for Healthcare, Embodied Intelligence, AGI, and Human-Computer Interaction. I am actively seeking **MPhil/Ph.D.** opportunities in 2025 Fall.

Contact me through: Barryzbr12[AT]gmail.com or Barryzhang[AT]stumail.neu.edu.cn. Find my [CV](./assets/CV_Bairui_Zhang.pdf) Here.

<!--
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

-->

# 🔥 News
- *2025.02*: &nbsp;🎉🎉 A Paper Have Submitted to ARR, Are Medical LLMs Ready? A Critical Study Using Checklist.
- *2024.10*: &nbsp;🎉🎉 A Paper Have Submitted to NAACL, Augmenting Categorical Emotion Detection with Visual Emotion Priors.
- *2024.07*: &nbsp;🎉🎉 A Paper Have Accepted by Sensors, AI in Pancreatic Cancer Analysis: A Review.
- *2024.06*: &nbsp;🎉🎉 Prof. Benyou Wang accept me as a research assistant at CUHK-Shenzhen.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> arXiv </div><img src='images/ARR-February.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Large Language Models for Outpatient Referral: Problem Definition, Benchmarking and Challenges](https://arxiv.org/pdf/2503.08292)

Xiaoxiao Liu, Qingying Xiao, Junying Chen, Xiangyi Feng, Xiangbo Wu, **Bairui Zhang**, Xiang Wan, Jian Chang, Guangjun Yu, Yan Hu, Benyou Wang.

- This study investigates the application of large language models (LLMs) in outpatient referral tasks, proposing a comprehensive evaluation framework that includes static classification and dynamic dialogue tasks. The authors introduce the IOR-Bench dataset and find that while LLMs show limited advantages over traditional models in static tasks, they demonstrate potential in dynamic interactions by asking effective questions. The work highlights the need for further improvements in LLMs' ability to integrate diverse medical information and refine recommendations through iterative dialogues.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> Under Polish </div><img src='images/Multimodal Emotional Recognition.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Augmenting Categorical Emotion Detection with Visual Emotion Priors](./assets/NAACL.pdf)

Changrong Min, **Bairui Zhang**, Hongfei Lin, Ximing Li


- This task aims to identify emotions in text. While Prompt Tuning (PT) has been used, current detectors struggle with designing efficient prompts. We propose VISPOR (Visual Emotion Prefix-guided Emotion Detector), which leverages visual information to enhance emotion detection. By aligning emotional text descriptions with images and using visually enriched embeddings as prefixes, VISPOR captures more nuanced emotion features. Experiments show VISPOR outperforms existing methods on three benchmarks.
</div>
</div>


<!--
[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Sensors SCI JCR Q2</div><img src='images/sensors.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Artificial Intelligence in Pancreatic Image Analysis: A Review](https://doi.org/10.3390/s24144749)

Weixuan Liu, **Bairui Zhang**, Tao Liu, Juntao Jiang, Yong Liu

- This work explores the application of AI in pancreatic cancer diagnosis, focusing on segmentation, classification, object detection, and prognosis prediction using CT, MRI, EUS, PET, and pathological images. It aims to improve diagnostic and treatment accuracy by integrating various imaging techniques, and discusses current trends and future developments in AI-driven pancreatic cancer diagnosis.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISAIMS</div><img src='images/ISAIMS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Factors that increase the mortality of sepsis and personalized medication for patients with sepsis](https://dl.acm.org/doi/abs/10.1145/3644116.3644330)

**Bairui Zhang**, Qianlong Cai, Junyang Ding, Kaitao Yuan

- This work develops a machine learning model to predict mortality and recommend medications for sepsis patients. Extreme Gradient Boosting achieved the best accuracy for both mortality (0.802) and drug prediction (0.867). Key factors affecting mortality include age and respiratory rate. Heparin, Acetaminophen, and Metoprolol Tartrate were effective, while Hydromorphone was linked to higher mortality.
</div>
</div>

<!--
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
-->

# 🎖 Honors and Awards
- *2024.02*, Meritorious Winner (Top 8% in the world), Mathmatical Contests in Modeling ([MCM/ICM](https://www.comap.com/)). See [Paper](./assets/SubmittedICM.pdf) Here.
- *2023.11*, First Prize (Top 5% in the world), Asia and Pacific Mathematical Contest in Modeling ([APMCM](http://www.apmcm.org/index?language=cn)). See [Paper](./assets/apmcm.pdf) Here.
- *2024.10*, First Prize Scholarship (1/113), Northeastern University.
- *2021-2024*, Merit Student (Each Academic Year), Northeastern University.
- *2021-2023*, University Scholarship (Four Consecutive Semester), Northeastern University. 

# 📖 Educations
- *2024.06 - 2025.06*,  Visiting Student, The Chinese University of Hong Kong, Shenzhen, School of Data Science.
- *2021.09 - 2025.06*, Bachelor, Northeastern University, Computer Science (GPA:3.99/4.0 Rank 3/116). 

# 💬 TA and Workshop
- *2023.09-2023.12*, TA for Software Architecture & Engineering Economics, Northeastern University & University of Technology Sydney.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Summer Camp</div><img src='images/MIT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🌞*2023.07 - 2023.08*, Summer Research Camp Advised by MIT Professor [Manolis Kellis](https://web.mit.edu/manoli/).

**Team Leader**
- This work develops a model to predict mortality and recommend medications for sepsis patients. Barry played a key role, contributing to data extraction, feature processing, coding, and model implementation. His expertise in data mining, statistical analysis, and project management was highlighted, earning him high evaluation scores. He was recognized as a collaborative team member and ranked #1 out of 4 in his team, achieving a score of 98/100 and an A grade, see the [Evaluation](./assets/Evaluation.pdf) from Prof. Kellis Here.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Symposium</div><img src='images/Future Science Prize Week.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

😉*2024.11.01 - 2024.11.03*, Future Science Prize Week.

**Invited Participant**
- The Future Science Prize Week is a prestigious gathering of leading scientists, researchers, and academics from around the world to discuss cutting-edge advancements in science and technology. This event features keynote speeches from influential figures such as Euan Ashley from Stanford University focusing on Medical AI and [Ma Yi](https://people.eecs.berkeley.edu/~yima/) from the University of Hong Kong talking about the nature of intelligence and I am so honnor to take a photo with him. The symposium is chaired by notable figures like Ren Yonghua, a professor at the HKU and an academician of the Chinese Academy of Sciences, and Xie Yuan, a professor at HKUST. These esteemed leaders guide the event's focus on topics such as AI in medicine, making computers smarter, energy-efficient AI systems, and understanding intelligence. The Future Science Prize Week serves as a platform for fostering innovation, collaboration, and the exchange of ideas that shape the future of science.


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Colloquium</div><img src='images/Photo.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
🤩*2024.12.26*, Exploring the Importance of Sensorimotor Experience in Artificial Intelligence

**Colloquium Participant**
- Today, I attended a fascinating seminar titled "The Increasing Role of Sensorimotor Experience in Artificial Intelligence," presented by Professor [Richard S. Sutton](http://www.incompleteideas.net/). Professor Sutton elaborated on the four-step developmental path of AI, highlighting the significance of sensorimotor experience and the central role of reward signals in reinforcement learning. He also emphasized the future potential of experiential knowledge and predictive modeling in advancing AI. This insightful talk deepened my understanding of how sensorimotor experience drives AI research and inspired me to explore its future applications.
</div>
</div>

<!--
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->


# 💻 Internships
- *2024.06 - 2025.06*, The Chinese University of Hong Kong, Shenzhen, Research Assistant, China.
- *2023.07 - 2023.09*, Chipcis (Shanghai) Information Tech Co., Ltd., Software Engineer, China.
- *2022.08 - 2022.11*, Beijing Codnoy Technology Co., Ltd., Software Engineer, China.
