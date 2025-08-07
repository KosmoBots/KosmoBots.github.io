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

We are dedicated to developing VLA large models and embodied intelligence technologies to enable next-generation heterogeneous multi-agent collaboration and smart, flexible manufacturing systems.

<span class='anchor' id='-gzsx'></span>

# 🎓 Research Direction
- Heterogeneous Robot Data Collection
- Robotic Arm Grasping
- Multi-Agent Human-Like Motion Transfer
- Dexterous Hand Perception and Control
- Multi-Agent Swarm Control

<span class='anchor' id='-xl'></span>

# 🎓 Team Members
- Yanjiu Zhong&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;email:zhongyanjiu@hfut.edu.cn
- Jian Sun&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;email:1218679064@qq.com
- Yang Wang&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;email:brownyangw@gmail.com
- Shuai Chen&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;email:2024111074@mail.hfut.edu.cn
- Linfeng Li&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;email:llf_ah@163.com
- Xianpeng Li&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;email:2411441061@qq.com
- Xincheng Han&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;email:3301625791@qq.com
- Shirong Luo&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;email:2447816975@qq.com
- Jinyang Zhao&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;email:2023213574@mail.hfut.edu.cn
- Yuanjun Yang&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;email:2023211121@mail.hfut.edu.cn
- Chengzheng Sun&nbsp;&nbsp;email:1449335205@qq.com

<span class='anchor' id='-lwzl'></span>

# 📝 Research Progress

### Data Collection
---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/data_collecttion.gif' alt="sym" style="width:300px; height:auto;"></div></div>
<div class='paper-box-text' markdown="1">

-	To address the challenges of multi-modal, multi-scenario, and multi-task data acquisition, our lab has developed a VR-based heterogeneous robot integrated data collection system. This system combines various types of robots and sensors to efficiently collect and manage data across diverse environments and tasks.
- It also supports training of Vision-Language-Action (VLA) models using the collected data, enhancing the agents' perception, understanding, and decision-making capabilities in complex tasks.



</div>
</div>

### Multimodal Perception-Driven Robotic Arm Decision Making
---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/motion_control.gif' alt="sym" style="width:300px; height:auto;"></div></div>
<div class='paper-box-text' markdown="1">

-	To address complex demands in high-level cognitive decision-making, we developed a Vision-Language-Action (VLA) model that integrates visual and tactile feedback. A fine-grained multimodal semantic alignment mechanism enables effective fusion of visual and haptic information, improving the model’s understanding of environmental and task-specific details. This empowers robotic arms with intelligent decision-making and precise control across diverse scenarios, significantly enhancing execution accuracy and adaptability in complex operations.

</div>
</div>

### Reinforcement Learning-Based Human-Like Motion Transfer
---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/humanoid_migration.gif' alt="sym" style="width:500px; height:auto;"></div></div>
<div class='paper-box-text' markdown="1">

-	To tackle challenges in low-level motion control, we designed a reinforcement learning-based Sim2Real framework for fast and robust transfer of human-like motions. By bridging simulation and real-world environments, the framework improves motion transfer efficiency and robustness. A hierarchical multi-agent tolerance reinforcement learning method was also proposed, enabling collaborative learning and fault tolerance across different agent levels. This approach accelerates learning and enhances stability and adaptability during transfer.


</div>
</div>

### Flexible Skin-Enabled Tactile Sensing for Dexterous Hands
---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/dexterous_hand.png' alt="sym" style="width:500px; height:auto;"></div></div>
<div class='paper-box-text' markdown="1">

- To enhance perception and control in dexterous robotic hands, we developed an efficient tactile sensing system by integrating flexible electronic skin with dexterous hand hardware. For different application scenarios, custom tactile sensing and reconstruction algorithms were implemented, improving the accuracy of tactile perception and interpretation. By fusing tactile and visual information, the system significantly strengthens the multimodal perception and autonomous control capabilities of dexterous hands in complex environments.

</div>
</div>

### Intelligent Navigation for Heterogeneous Robot Swarms
---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/path_planning.gif' alt="sym" style="width:500px; height:auto;"></div></div>
<div class='paper-box-text' markdown="1">

- To address navigation challenges in industrial multi-scenario environments, we designed a reinforcement learning-based algorithm for dynamic scene recognition and path planning. The system enables real-time perception and understanding of complex and changing environments. By considering differences between individual robots, it optimizes path planning strategies to achieve efficient collaborative navigation and swarm control for heterogeneous multi-agent systems.

</div>
</div>

<span class='anchor' id='-abcd'></span>

# 🛠️ Ongoing Projects

### Research on Lifelong Growth Mechanisms of Space Embodied Intelligence Robots Driven by Cognitive Reinforcement and System Evolution
---

With the advancement of deep space exploration, intelligent capabilities of space robots have become critical for on-site lunar construction. This project focuses on intelligent evolution mechanisms of space embodied robots in complex dynamic environments.
Key components include:
- Building a high-fidelity lunar surface world model
- Designing a decoupled perception-control heterogeneous computing framework for adaptability in microgravity and lunar dust environments
- Integrating large models with expert knowledge to enhance cognitive and manipulation capabilities
- Developing a co-evolution mechanism across structure, control, and knowledge
Ultimately, a simulation platform combining virtual and physical systems will be used for closed-loop optimization from perception to execution, providing intelligent, efficient solutions for future lunar missions.

### Multi-Agent Collaborative Scheduling System for Self-Organizing Robotic Workcells
---

Traditional centralized control systems face difficulties in efficiently scheduling diverse robotic arms in increasingly complex smart manufacturing settings. This project proposes a distributed multi-agent collaboration framework tailored for "multi-product on one line" production modes.
Highlights include:
- High-level agents decompose production goals into sub-tasks suitable for different robotic arms
- Each heterogeneous agent uses a digital twin to model its own state and adaptively complete tasks
- Integration of visual perception and process knowledge graphs to support task decomposition
- Use of graph neural networks for real-time collision prediction and motion trajectory optimization
The system ensures flexible, safe, and efficient robotic arm coordination in autonomous workshops.

### Multimodal Large Model-Based Intelligent Motor Assembly Assistance System
---
In manufacturing and equipment maintenance, motor assembly is challenged by diverse parts, complex assembly relationships, and reliance on manual expertise.
This project develops an intelligent assistant system combining image understanding, structural knowledge modeling, and natural language processing. It features:
- Automatic identification of motor diagrams
- Extraction of key assembly triplets
- Construction of a structured knowledge graph
- Generation and evaluation of executable assembly/disassembly sequences
- Robotic execution of optimized procedures
This system enhances automation, precision, and intelligence in motor assembly and maintenance tasks.

### Collaborative Decision-Making for Heterogeneous Robots in Urban Warfare via Diffusion Models
---

Robotic teamwork is becoming vital in modern warfare scenarios. This project explores collaborative decision-making for heterogeneous robots in urban combat settings.
The research integrates:
- Dynamic scene understanding through diffusion models
- Diffusion-based path planning in complex environments
- Vision-Language-Action (VLA) models for autonomous decision-making
- A scalable system architecture for state awareness and multi-function integration
The goal is to develop effective robotic collaboration strategies for urban warfare applications.



### VLA Model-Based Mobile Robotic Arm Grasping System for Aerospace Maintenance
---

Aircraft maintenance often involves challenges such as low lighting and confined spaces, which hinder manual cable connection tasks. This project aims to develop a mobile robotic arm system based on VLA models for intelligent cable assembly in harsh aerospace environments.
Core technologies include:
- Multimodal perception
- High-precision motion control
- Integrated mobility and manipulation
The system enables automated, accurate, and low-damage cable operations in dark, narrow conditions, reducing risks and improving efficiency in aerospace maintenance.

<span class='anchor' id='-ryjx'></span>

# 🧪  Experimental Facilities
---
<div style="display: flex; gap: 20px; flex-wrap: wrap; justify-content: center;">
  <div class='paper-box'>
    <div class='paper-box-image'>
      <img src='images/equ.jpg' alt="实验室设备图" style="width: 1000px;">
    </div>
  </div>
</div>

<span class='anchor' id='-xshy'></span>

# 🏛️ Collaborators

### 🏫 Academic Collaborations
---

- Tsinghua University
- Shanghai Jiao Tong University
- Nanjing University
- University of Alberta

### 🤝 Industry Partners
---

- China Academy of Space Technology (CAST)
- Chengdu Aircraft Industry Group (AVIC Chengfei)
- Aero Engine Corporation of China (AECC)
- China Baowu Steel Group Corporation
- China North Industries Group Corporation Limited (Norinco Group)
- Anhui Sanheyiyi Information Technology Co., Ltd.
- Chery Automobile Co., Ltd.



