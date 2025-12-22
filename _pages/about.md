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

📚 **Biography:** Gou Tan (谭苟 in Chinese) is currently a 2nd-year Ph.D. student at [Sun Yat-Sen University (SYSU)](https://www.sysu.edu.cn/sysuen/), supervised by Prof. [Pengfei Chen](https://cse.sysu.edu.cn/teacher/ChenPengfei) and Prof. [Chuanfu Zhang](https://ssse.sysu.edu.cn/teacher/311). Recently, he was awarded a CSC (China Scholarship Council) fellowship, and he will join the [Singapore Management University (SMU)](https://rise.smu.edu.sg/), co-supervised by Prof. [SHAR Lwin Khin](https://faculty.smu.edu.sg/profile/shar-lwin-khin-6796) and Prof. [David Lo](http://www.mysmu.edu/faculty/davidlo/). He received a B.E. degree from Sun Yat-Sen University in 2022.

💡**Research Interest**: AI Reliability, SE4AI, LLMOps, MLOps, AI4SE, AIOps.
<!-- Haiyu Huang is currently a research assistant at [Sun Yat-Sen University](https://cse.sysu.edu.cn/), advised by Professor [Pengfei Chen](https://cse.sysu.edu.cn/content/3747). Previously, he received a B.E. in CSE from Sun Yat-Sen University in 2023. He has interned at [Alibaba Cloud](https://cn.aliyun.com/), [Huawei](https://www.huawei.com/), and [Ant Group](https://www.antgroup.com/) in Cloud Native Application Performance Management related departments, developing algorithms and solving real-world problems. -->


# 🔥 News
- *2025.12*: &nbsp;🎉🎉 Our paper "MetaRCA: A Generalizable Root Cause Analysis Framework for Cloud-Native Systems Powered by Meta Causal Knowledge" was accepted by **<font color="red">FSE'26 (CCF A)</font>**! Congrats to Shuai Liang!
- *2025.12*: &nbsp;🎉🎉 Our Agent-based C to Rust solutions won [vivo BlueOS 3rd Prize](https://competition.openatom.tech/competitionInfo?id=49f0205ecd5c81c96381829456fef6a5#heading-0-0).
- *2025.12*: &nbsp;🎉🎉 Our paper "ProfRCA: LLM-Enabled Fine-grained Root Cause Analysis with Continuous Profiling Data" was accepted by **<font color="red">SANER'26 (CCF B)</font>**! Congrats to Siyuan!
<!-- - *2025.10*: &nbsp;🎉🎉 Our paper "LLMRCA: Multilevel Root Cause Analysis for LLM Applications Using Multimodal Observability Data" was accepted by **<font color="red">TOSEM (CCF A)</font>**! -->
- *2025.09*: &nbsp;🎉🎉 Our paper "MOTSAD: Multi-Objective Optimization for Time Series Anomaly Detection in Microservice" was accepted by **<font color="red">ICSOC'25 (CCF B)</font>**! Congrats to Xitao!
- *2025.06*: &nbsp;🎉🎉 Our paper "InferLog: Accelerating LLM Inference for Online Log Parsing via ICL-oriented Prefix Caching" was accepted by **<font color="red">ICSE'26 (CCF A)</font>**! Congrats to Yilun!
- *2025.04*: &nbsp;🎉🎉 Our paper "A Survey on Failure Analysis and Fault Injection in AI Systems" was accepted by **<font color="red">TOSEM (CCF A)</font>**! Congrats to Guangba!
- *2023.12*: &nbsp;🎉🎉 Our LLM-based AIOps solutions won [3rd place🥉](https://mp.weixin.qq.com/s/KctBL78OgxSOzPXoeGfe5w) in the [2023 CCF International AIOps Challenge](https://www.aiops.cn/aiopschallenge/) \(1st🏅 among student teams\).
- *2023.10*: &nbsp;🎉🎉 Our paper "Online Data Drift Detection for Anomaly Detection Services based on Deep Learning towards Multivariate Time Series" was accepted by **<font color="red">QRS'23 (CCF C)</font>**!

<!-- <span style="  display: inline-block;  padding: 2px 10px;  background-color: #c00000;  color: white;  border-radius: 999px;  font-weight: bold;  font-size: 14px;  font-family: sans-serif;">CCFA</span>
<span style="  display: inline-block;  padding: 2px 10px;  background-color: #f4bc42;  color: white;  border-radius: 999px;  font-weight: bold;  font-size: 14px;  font-family: sans-serif;">CCFB</span>
<span style="  display: inline-block;  padding: 2px 10px;  background-color: #8bc23f;  color: white;  border-radius: 999px;  font-weight: bold;  font-size: 14px;  font-family: sans-serif;">CCFB</span> -->
<!-- - *2024.06*: &nbsp;🎉🎉 Our paper "TraStrainer: Adaptive Sampling for Distributed Traces with System Runtime State" has won an **<font color="red">ACM SIGSOFT Distinguished Paper award</font> 🏆**. -->


# 📝 Publications 
- &nbsp; <span class="badge" style="font-size:15px; background-color:#c00000; color:white;">FSE'26 (CCF A)</span> &nbsp;**MetaRCA: A Generalizable Root Cause Analysis Framework for Cloud-Native Systems Powered by Meta Causal Knowledge**

  <span style="font-size:14px;"> Shuai Liang, Pengfei Chen*, Bozhe Tian, **<font color="red">Gou Tan</font>**, Maohong Xu, Youjun Qu, Yahui Zhao, Yiduo Shang, Chongkang Tan. </span>

  <span style="font-size:14px;"> *ACM International Conference on the Foundations of Software Engineering (FSE'26), Montreal, Canada, July, 2026.* </span>

  [Paper]
  [Code]
  [Slides]
  [DOI]

- &nbsp; <span class="badge" style="font-size:15px; background-color:#f4bc42; color:white;">SANER'26 (CCF B)</span> &nbsp;**ProfRCA: LLM-Enabled Fine-grained Root Cause Analysis with Continuous Profiling Data**

  <span style="font-size:14px;"> Siyuan Ye, **<font color="red">Gou Tan</font>**, Wanqi Yang, and Pengfei Chen*. </span>

  <span style="font-size:14px;"> *The 33rd IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER'26), Limassol, Cyprus, March 2026.* </span>

  [Paper]
  [Code]
  [Slides]
  [DOI]

- &nbsp; <span class="badge" style="font-size:15px; background-color:#f4bc42; color:white;">ICSOC'25 (CCF B)</span> &nbsp;**MOTSAD: Multi-Objective Optimization for Time Series Anomaly Detection in Microservice**

  <span style="font-size:14px;"> Xitao Tang, **<font color="red">Gou Tan</font>** and Pengfei Chen*. </span>

  <span style="font-size:14px;"> *The 23rd International Conference on Service-Oriented Computing (ICSOC'25), Shenzhen, China, December 2025.* </span>

  [Paper]
  [[Code](https://github.com/IntelligentDDS/MOTSAD)]
  [Slides]
  [DOI]


- &nbsp; <span class="badge" style="font-size:15px; background-color:#c00000; color:white;">ICSE'26 (CCF A)</span> &nbsp;**InferLog: Accelerating LLM Inference for Online Log Parsing via ICL-oriented Prefix Caching**

  <span style="font-size:14px;"> Yilun Wang, Pengfei Chen*, Haiyu Huang, Zilong He, **<font color="red">Gou Tan</font>**, Chuanfu Zhang, Jingkai He, Zibin Zheng. </span>

  <span style="font-size:14px;"> *2026 IEEE/ACM International Conference on Software Engineering (ICSE'26), Rio de Janeiro, Brazil, April 2026.* </span>

  [[Paper](https://arxiv.org/abs/2507.08523)]
  [[Code](https://github.com/wiluen/InferLog)]
  [Slides]
  [DOI]


- &nbsp; <span class="badge" style="font-size:15px; background-color:#c00000; color:white;">TOSEM (CCF A)</span> &nbsp;**A Survey on Failure Analysis and Fault Injection in AI Systems**

  <span style="font-size:14px;"> Guangba Yu, **<font color="red">Gou Tan</font>**, Haojia Huang, Zhenyu Zhang, Pengfei Chen*, Roberto Natella, Zibin Zheng, Michael R. Lyu. </span>

  <span style="font-size:14px;"> *ACM Transactions on Software Engineering and Methodology.* </span>

  [[Paper](./files/tosem25/tosem25_AIFailure.pdf)]
  [Code]
  [Slides]
  [[DOI](https://dl.acm.org/doi/10.1145/3732777)]


- &nbsp; <span class="badge" style="font-size:15px; background-color:#8bc23f; color:white;">QRS'23 (CCF C)</span> &nbsp;**Online Data Drift Detection for Anomaly Detection Services based on Deep Learning towards Multivariate Time Series**

  <span style="font-size:14px;"> **<font color="red">Gou Tan</font>**, Pengfei Chen*, and Min Li. </span>

  <span style="font-size:14px;"> *2023 IEEE 23rd International Conference on Software Quality, Reliability, and Security (QRS'23), Chiang Mai, Thailand, October 2023.* </span>

  [[Paper](./files/qrs23/qrs23.pdf)]
  [Code]
  [[Slides](./files/qrs23/qrs23_slides.pdf)]
  [[DOI](https://ieeexplore.ieee.org/abstract/document/10366704)]

# 📝 Under Review
- &nbsp; <span class="badge" style="font-size:15px;">26</span> &nbsp;**LLMRCA: Multilevel Root Causes Analysis for LLM Applications Using Multimodal Observability Data**

  <span style="font-size:14px;"> **<font color="red">Gou Tan</font>**, Zilong He, Min Li, Haiyu Huang, Yilun Wang, Pengfei Chen*, Giuliano Casale, Chuanfu Zhang. </span>

  <!-- <span style="font-size:14px;"> *ACM Transactions on Software Engineering and Methodology.* </span> -->

  [Paper]
  [Code]
  <!-- [[Code](https://github.com/IntelligentDDS/LLMRCA)] -->
  [Slides]
  [DOI]

# 🎖 Honors and Awards
- *2025.12* Merit Award (7/154), [vivo BlueOS 3rd Prize](https://competition.openatom.tech/competitionInfo?id=49f0205ecd5c81c96381829456fef6a5#heading-0-0).
- *2025.02* Merit Award (14/403), [vivo BlueOS Innovation Competition](https://competition.atomgit.com/competitionInfo?id=4d59fdd1604b17529552a14449f5d460).
- *2024.12* Bronze Award, "HUAWEI Cup" The 21st China Post-Graduate Mathematical Contest in Modeling.
- *2023.12* 3rd Place, [2023 CCF International AIOps Challenge](https://www.aiops.cn/aiopschallenge/) (1st among student teams).

# 👩🏻‍💻 Working Experience
- <img src="./images/00_bytedance.png" alt="ByteDance" style="height: 22px; vertical-align: middle; margin-left: 4px;"> *2025.08 - Present*, ByteDance. AgentOps Research Intern, [Data Infrastructure - Volcano Engine Platform Architecture](https://jobs.volcengine.com/fyx/2025/join?token=MjsxNzUzODY3NTA2MzEyOzY2ODgyMzIyNjAwOTQ3NzI3NTA7NzUzMjgwMjI0OTc0MDgxNDU5OTsx).
  
  <span style="font-size:14px;"> Collaborate with [Meng Wang](https://mengwangbupt.github.io/), [Yaozheng Fang](https://fangyaozheng.github.io/), and Guodong Li. Developed [Volcengine Agent Development Kit (VeADK)](https://github.com/volcengine/veadk-python). Focus on "Multi-Agent system evaluation and optimization". </span>


# 📖 Educations
- <img src="./images/01_sysu.png" alt="SYSU" style="height: 22px; vertical-align: middle; margin-left: 4px;"> *2022.09 - Present*, Ph.D. student (Master's and Ph.D. combined program), Sun Yat-sen University (SYSU).
- <img src="./images/02_smu.png" alt="SMU" style="height: 22px; vertical-align: middle; margin-left: 4px;"> *2025.12 - 2026.12*, Visiting Scholar, Singapore Management University (SMU).
- <img src="./images/01_sysu.png" alt="SYSU" style="height: 22px; vertical-align: middle; margin-left: 4px;"> *2018.09 - 2022.06*, Bachelor degree, Sun Yat-sen University (SYSU).

<!-- <a href="https://clustrmaps.com/site/1c4nh"  title="ClustrMaps"><img src="//www.clustrmaps.com/map_v2.png?d=f-lKHy6Grjqk77yNA1otBlUuiz92j29HbqsGM8PbneY&cl=ffffff" /></a> -->
<a href="https://clustrmaps.com/site/1c4nh"  title="ClustrMaps">
  <img 
    src="//www.clustrmaps.com/map_v2.png?d=f-lKHy6Grjqk77yNA1otBlUuiz92j29HbqsGM8PbneY&cl=ffffff" 
    style="display: block; margin: 0 auto; width: auto; /* 你可以根据需要调整宽度 */" 
  />
</a>

<!-- 页面最后更新时间 -->
<div style="text-align: right; margin-top: 0px; padding-right: 20px; color: #999; font-size: 12px;">
    Last Updated: <span id="last-updated"></span>
</div>

<script>
    function updateLastUpdated() {
        const lastModified = new Date(document.lastModified);
        const options = { 
            year: 'numeric', 
            month: 'short', 
            day: 'numeric',
            timeZone: 'Asia/Shanghai'
        };
        document.getElementById('last-updated').textContent = lastModified.toLocaleDateString('en-US', options);
    }
    
    updateLastUpdated();
</script>
  <!-- - GPA: 4.1/5.0; Rank: Top 10% -->

<!-- # 💬 Services
- *Reviewer:*  WWW 2024 -->

<!-- # 💻 Internships -->