---
permalink: /
title: ""
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

-  I am a student researcher at Tsinghua University🎓. I am now a member of [Pervasive HCI Group](https://pi.cs.tsinghua.edu.cn/), advised by Prof. Yuanchun Shi, A/Prof. Yuntao Wang, and Prof. Yingqing Xu. I have done research in the [Department of Computer Science and Technology](https://www.cs.tsinghua.edu.cn/csen/), [Global Innovation Exchange](https://gix.uw.edu/), [Future Lab](https://thfl.tsinghua.edu.cn/en/), and [School of Vehicle and Mobility](http://www.svm.tsinghua.edu.cn/). I was a researcher at Tsinghua-Toyota AI Center and an intern at [Zhipu AI](https://www.zhipuai.cn/en/) ChatGLM Group. I enjoy working with academia and industry.

- 🔭 My research interests include `Remote Physiological Sensing`, `Pervasive Computing`, `Human-Computer Interaction(HCI)`, `Large Language Model`, and `Computer Vision`. I’m currently working on Biosensing, HCI, and LLM.  
 
- 📫 Reach me through `tjk19@mails.tsinghua.edu.cn` if interested.  

<a href='https://scholar.google.com/citations?user=SCHOLAR_ID&user=_jENFHIAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

# 🔥 News
**2024.02.13:** 🎉🎉 Awarded **Educational Stipend Award** by 2024 ISMRM!

**2024.01.26:** 🎉🎉 Our paper addressed [Fetal MRI image quality assessment](https://www.ismrm.org/24/accepted_abstracts.pdf) has been accepted by [ISMRM 2024](https://www.ismrm.org/24m/) as oral power pitch (top 13%).

**2024.01.26:** 🎉🎉 Our paper addressed [Fetal cortex reconstruction](https://www.ismrm.org/24/accepted_abstracts.pdf) has been accepted by [ISMRM 2024](https://www.ismrm.org/24m/).

**2023.12.12:** 🎉🎉 Our paper addressed [Image deblurring](https://hplqaq.github.io/projects/sam-deblur) has been accepted by [IEEE ICASSP 2024](https://2024.ieeeicassp.org/).

**2023.11.24:** 🎉🎉 Won the top3 Prize in [Al Health Summit 2023 Poster Competition](https://mp.weixin.qq.com/s/Y7yvnuK6nqyBeBf8tAofOQ).

**2023.11.23:** Attended the AI Health Summit 2023 held in held in Singapore and posted a [poster](https://drive.google.com/file/d/1g9uQsFCsOHGoOQ5ChehHDCV1Aqt2qpaq/view?usp=sharing). 

**2023.10.20:** 🎉🎉 Our abstract addressed [Fetal MRI image quality assessment](https://onedrive.live.com/?authkey=%21ABvG7ukadYI%2Dipw&id=A5AB43CB4B79A37A%2133213&cid=A5AB43CB4B79A37A&parId=root&parQt=sharedby&parCid=UnAuth&o=OneUp) has been accepted by [AI Health Summit 2023](https://healthsummit.ai/main/abstracts/)

**2023.10.15:** 🎉🎉 Awarded **National Scholarship** by Ministry of Education!

**2023.10.2:** Attended the [NUS-THU Joint Workshop on Biomedical Engineering 2023](https://ihealthtech.nus.edu.sg/event/nus-thu-joint-workshop-on-biomedical-engineering-2023/) hosted by the [National University of Singapore](https://nus.edu.sg/) and posted a [poster](https://drive.google.com/file/d/1XvKr1N_4eonvEOxT0u8NA1tLA0tvImT3/view). 

**2023.7.16:** Attended the [IEEE ASYNC 2023](https://c360-o2o.c360dn.com/b14b26a8836a3f6cf111018ac518dfa51920?watermark/3/image/aHR0cHM6Ly9jMzYwLW8yby5jMzYwZG4uY29tL2Y5OGQ4ODI5LTAwNjMtNDMxZi1iZmEyLTU2ZWU2Mjg5YTA2Mz9pbWFnZXMy/dissolve/100/gravity/SouthEast/dx/0/dy/0/ws/0.2071148722770726) held in Beijing, China.

**2023.5.21:** 🎉🎉 Our paper addressed [Tooth-Marked Tongue Classification](https://ieeexplore.ieee.org/abstract/document/10181870) has been accepted by [IEEE ISCAS 2023](https://2023.ieee-iscas.org/).

**2023.5.21:** 🎉🎉 Our paper addressed [Unsupervised Medical Image Anomaly Detection](https://ieeexplore.ieee.org/abstract/document/10181639) has been accepted by [IEEE ISCAS 2023](https://2023.ieee-iscas.org/).

# 📝 Publications 
#### JOURNAL PUBLICATIONS

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIM</div><img src='../images/TIM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Anomaly Detection for Medical Images Using Teacher-Student Model with Skip Connections and Multi-scale Anomaly Consistency

**Mingxuan Liu**, Yunrui Jiao, Jingqiao Lu, Hong Chen

IEEE Transactions on Instrumentation and Measurement, Under Review

<div class="extra-links">
    <a class="_blank" href="https://www.techrxiv.org/doi/full/10.36227/techrxiv.24330880.v1" >
        <i class="fas fa-newspaper" aria-hidden="true"></i> Paper
    </a>
    <a class="_blank" href="https://github.com/Arktis2022/Skip-TS">
        <i class="ai ai-open-access ai-1x" aria-hidden="true"></i> Code
    </a>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NN</div><img src='../images/NN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Spiking-PhysFormer: Camera-Based Remote Photoplethysmography with Parallel Spike-driven Transformer

**Mingxuan Liu\***, Jiankai Tang\* (\*Co-first Author), Haoxiang Li, Jiahao Qi, Siwei Li, Kegang Wang, Yuntao Wang, Hong Chen

Neural Networks, Under Review

<div class="extra-links">
    <a class="_blank" href="https://arxiv.org/abs/2402.04798" >
        <i class="fas fa-newspaper" aria-hidden="true"></i> Paper
    </a>
</div>

</div>
</div>

#### CONFERENCE PUBLICATIONS

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISMRM 2024</div><img src='../images/ISMRM2024-1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Image Quality Assessment using an Orientation Recognition Network for Fetal MRI

**Mingxuan Liu\***, Haoxiang Li\* (\*Co-first Author), Zihan Li, Hongjia Yang, Jialan Zheng, Xiao Zhang, Qiyuan Tian

[2024 ISMRM & ISMRT Annual Meeting & Exhibition](https://www.ismrm.org/24m/) (Oral Power Pitch)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISMRM 2024</div><img src='../images/ISMRM2024-2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## FetalSurfer: an automated fetal cortex reconstruction method to study complex development of fetal brain using AI segmentation

Haoxiang Li\*, **Mingxuan Liu\*** (\*Co-first Author), Jialan Zheng, Hongjia Yang, Zihan Li, Qiyuan Tian

[2024 ISMRM & ISMRT Annual Meeting & Exhibition](https://www.ismrm.org/24m/) (Digital Poster)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2024</div><img src='../images/ICASSP2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## SAM-Deblur: Let Segment Anything Boost Image Deblurring

Siwei Li\*, **Mingxuan Liu\*** (\*Co-first Author), Yating Zhang, Shu Chen, Haoxiang Li, Hong Chen, Zifei Dou

2024 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)

<div class="extra-links">
    <a class="_blank" href="https://arxiv.org/abs/2309.02270" >
        <i class="fas fa-newspaper" aria-hidden="true"></i> Paper
    </a>
    <a class="_blank" href="https://hplqaq.github.io/projects/sam-deblur">
        <i class="ai ai-open-access ai-1x" aria-hidden="true"></i> Project
    </a>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AI Health Summit 2023</div><img src='../images/AHS2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Label-free Image Quality Assessment of Fetal Brain MRI with Unsupervised Deep Learning

**Mingxuan Liu**, Haoxiang Li, Haibo Qu, Qiyuan Tian

[AI Health Summit 2023](https://healthsummit.ai/main/abstracts/). (Top3 prize)

<div class="extra-links">
    <a class="_blank" href="https://onedrive.live.com/?authkey=%21ABvG7ukadYI%2Dipw&id=A5AB43CB4B79A37A%2133213&cid=A5AB43CB4B79A37A&parId=root&parQt=sharedby&parCid=UnAuth&o=OneUp" >
        <i class="fas fa-newspaper" aria-hidden="true"></i> Paper
    </a>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISCAS 2023</div><img src='../images/ISCAS2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Skip-ST: Anomaly Detection for Medical Images Using Student-Teacher Network with Skip Connections

**Mingxuan Liu**, Yunrui Jiao, Hong Chen

2023 IEEE International Symposium on Circuits and Systems (ISCAS) (Oral Presentation)

<div class="extra-links">
    <a class="_blank" href="https://ieeexplore.ieee.org/abstract/document/10181639" >
        <i class="fas fa-newspaper" aria-hidden="true"></i> Paper
    </a>
    <a class="_blank" href="https://github.com/Arktis2022/Skip-TS">
        <i class="ai ai-open-access ai-1x" aria-hidden="true"></i> Code
    </a>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISCAS 2023</div><img src='../images/ISCAS2023-2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## PRTMTM: A Priori Regularization Method for Tooth-Marked Tongue Classification

Jingqiao Lu, **Mingxuan Liu**, Hong Chen

2023 IEEE International Symposium on Circuits and Systems (ISCAS) (Poster)

<div class="extra-links">
    <a class="_blank" href="https://ieeexplore.ieee.org/abstract/document/10181870" >
        <i class="fas fa-newspaper" aria-hidden="true"></i> Paper
    </a>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BioCAS 2022</div><img src='../images/BioCAS2022.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Data Augmentation Using Image-to-image Translation for Tongue Coating Thickness Classification with Imbalanced Data

**Mingxuan Liu**, Yunrui Jiao, Hongyu Gu, Jingqiao Lu, Hong Chen

2022 IEEE Biomedical Circuits and Systems Conference (BioCAS) (Oral Presentation)

<div class="extra-links">
    <a class="_blank" href="https://ieeexplore.ieee.org/abstract/document/9948645" >
        <i class="fas fa-newspaper" aria-hidden="true"></i> Paper
    </a>
</div>

</div>
</div>

#### PREPRINT PUBLICATIONS
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='../images/arxiv-1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Spiking-Diffusion: Vector Quantized Discrete Diffusion Model with Spiking Neural Networks

**Mingxuan Liu\***, Jie Gan\*, Rui Wen\* (\*Co-first Author), Tao Li, Yongli Chen, Hong Chen

<div class="extra-links">
    <a class="_blank" href="https://arxiv.org/abs/2308.10187" >
        <i class="fas fa-newspaper" aria-hidden="true"></i> Paper
    </a>
    <a class="_blank" href="https://github.com/Arktis2022/Spiking-Diffusion">
        <i class="ai ai-open-access ai-1x" aria-hidden="true"></i> Code
    </a>
</div>

</div>
</div>
# 🎖 Honors and Awards
- *2024* **2024 ISMRM: Educational Stipend Award**
- *2023* **Top3 Prize in [Al Health Summit 2023 Poster Competition](https://healthsummit.ai/main/abstracts/)**, Singapore
- *2023* **National Scholarship, Ministry of Education**, P.R. China (Top 1 in department) <br /> &nbsp; &nbsp; &nbsp; *Top scholarship in China. 0.2% domestically*.
- *2022* **Scholarship for Academic Excellence**, Tsinghua University
- *2022* **Scholarship for Science and Technology Innovation Excellence**, Tsinghua University
- *2022* **Second Prize for Outstanding Projects of the Students Research Training Program**, Tsinghua University <br /> &nbsp; &nbsp; &nbsp; *Supported by a National College Student Innovation and Entrepreneurship Project*
- *2020* **Scholarship for Academic Excellence**, Tsinghua University

# 📖 Educations
- *2021.09 - present*, **School of Biomedical Engineering**, Tsinghua University, China. 
- *2019.09 – 2021.08*, Department of Chemical Engineering, Tsinghua University, China.

# 🎣 Activities
- *2023.11.24*, Won the top3 Prize in Al Health Summit 2023 Poster Competition. [Photo](https://img.erpweb.eu.org/imgs/2024/02/207b20e0e675d4fa.jpg) (First row: Competition judges; Left one: Editor-in-chief of The Lancet Digital Health; Left two: Prof Catherine R Lucey; Left three: Editor-in-chief of Nature Medicine; Left four: Editor-in-chief of Nature Biomedical Engineering)
- *2023.11.24*, Top 5 poster competition in AI health summit 2023. [Photo](https://img.erpweb.eu.org/imgs/2024/02/2547ed7aa1423a38.jpg)
- *2023.11.22*, BIRTHLab members visited Nanyang Technological University. [Photo](https://img.erpweb.eu.org/imgs/2024/02/0cb68379b33a36d5.png)
- *2023.10.02*, Attended the NUS-THU Joint Workshop on Biomedical Engineering 2023, held in Singapore. [Photo](https://img.erpweb.eu.org/imgs/2024/02/5514cfe5a7abca58.png)
- *2023.07.26*, Attended the IEEE ASYNC 2023 held in Beijing, China. [Photo](https://img.erpweb.eu.org/imgs/2024/02/28f5198102433c57.png)
  
# 💌 Social Event
- *2024.02.28*, Visited the Juzizhou Island (橘子洲) with my girlfriend, in Changsha. [Photo](https://ibb.co/mDLzGyS)
- *2023.10.22*, Visited the National Museum of China (国家博物馆) with my girlfriend, in Beijing. [Photo](https://img.erpweb.eu.org/imgs/2024/02/b0b5af6405497e7d.png)
- *2023.06.14*, Visited the Yuewang Pavilion (岳王亭) with my girlfriend, in Changsha. [Photo](https://img.erpweb.eu.org/imgs/2024/03/b621eaab184bcea3.jpg)
  
# 🔗 LINKS
BIRTHLab: [The lab for Brain Imaging Research at Tsinghua](https://birthlab.github.io/)<br>Haoxiang Li: [Department of Biomedical Engineering, Tsinghua University](https://lihaoxiang-20.github.io/)<br>Jack Tang: [Xinya College, Tsinghua University](https://mcjacktang.github.io/)<br>Yunkang Cao: [Huazhong University of Science and Technology](https://caoyunkang.github.io/)<br>Xiao Zhang: [Department of Biomedical Engineering, Tsinghua University](https://xzy-xyz.github.io/)<br>Yiming Huang: [Microsoft Research Asia](https://scholar.google.com/citations?hl=en&user=L8E-ccakgcQC)<br>Siwei Li: [Department of Electronic Engineering of Tsinghua University](https://hplqaq.github.io/)
