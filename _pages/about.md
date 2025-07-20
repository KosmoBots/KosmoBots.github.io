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

本实验室致力于研究VLA大模型与具身智能技术，从而推动异构多智能体协同制造与柔性智能制造平台的创新研发。

<span class='anchor' id='-gzsx'></span>

# 🎓 研究方向
- 异构机器人数据采集
- 机械臂抓取
- 多智能体类人动作迁移
- 灵巧手感知控制
- 多智能体集群控制

<span class='anchor' id='-xl'></span>

# 🎓 团队成员
- yanjiu zhong&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📧email:zhongyanjiu@hfut.edu.cn
- jian sun&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📧email:1218679064@qq.com
- yang wang&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📧email:brownyangw@gmail.com
- shuai chen&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📧email:2024111074@mail.hfut.edu.cn
- linfeng li&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📧email:llf_ah@163.com
- xianpeng li&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📧email:2411441061@qq.com
- xincheng han&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📧email:3301625791@qq.com
- shirong luo&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📧email:2447816975@qq.com
- jinyang zhao&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📧email:2023213574@mail.hfut.edu.cn
- yuanjun yang&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📧email:2023211121@mail.hfut.edu.cn
- chengzheng sun&nbsp;&nbsp;📧email:1449335205@qq.com

<span class='anchor' id='-lwzl'></span>

# 📝 研究进展

### 数据采集
---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/data_collecttion.gif' alt="sym" width="60%"></div></div>
<div class='paper-box-text' markdown="1">

-	为了满足多形态、多场景、多任务的复杂数据采集需求，实验室开发了一套基于虚拟现实（VR）设备的异构机器人集成数据采集系统。该系统通过融合多种类型的机器人及传感器，实现了对不同环境和任务下的数据高效采集与管理。同时，系统支持基于采集数据的VLA（Vision-Language-Action）模型训练，提升了智能体在复杂任务中的感知、理解与决策能力。

</div>
</div>

### 多模态感知驱动的机械臂智能决策
---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/motion_control.gif' alt="sym" width="60%"></div></div>
<div class='paper-box-text' markdown="1">

-	针对上层认知决策中的复杂需求，开发了一种集成视触觉多模态反馈的VLA模型，设计并实现了多模态细粒度语义对齐机制，有效融合视觉与触觉信息，提升模型对环境和任务细节的理解能力。该模型支持机械臂在多样化场景下的智能决策与精细动作控制，显著增强了机械臂执行复杂操作的精准性和适应性

</div>
</div>

### 强化学习驱动的类人动作迁移
---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/humanoid_migration.gif' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

-	针对底层运动控制中的复杂挑战，设计并实现了一种基于强化学习的类人动作Sim2Real快速迁移框架。该框架通过模拟环境与现实环境之间的有效桥接，提升了动作迁移的效率和鲁棒性。同时，提出了一种多智能体分层容差强化学习方法，实现了不同层级智能体之间的协同学习与容错机制，显著加快了动作学习速度，并提高了迁移过程中的稳定性和适应能力

</div>
</div>

### 柔性皮肤驱动的灵巧手触觉融合
---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/dexterous_hand.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

- 针对灵巧手在感知与控制方面的挑战，结合柔性电子皮肤器件与灵巧手硬件，构建了一套高效的触觉感知系统。针对不同应用场景，设计并实现了触觉感知算法和自主重建算法，提升了灵巧手对触觉信息的准确捕捉与理解能力。通过将触觉数据与视觉信息融合，显著增强了灵巧手在复杂环境下的多模态感知能力和自主控制性能

</div>
</div>

### 异构机器人集群智能导航
---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/path_planning.gif' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

- 针对工业生产中多样化场景下异构机器人集群的导航挑战，设计了一种基于强化学习的动态环境场景辨识与路径规划算法。该算法能够实时感知和识别复杂多变的工作环境，结合机器人个体差异，优化路径规划策略，实现异构多智能体的高效协同导航与集群控制

</div>
</div>

<span class='anchor' id='-abcd'></span>

# 🛠️ 在研项目

### 月球建造机器人
---

- 随着深空探测任务的推进，空间机器人智能化能力成为月球原位建造的关键支撑方向。本项目聚焦于复杂动态环境下空间具身机器人的智能演化机制，致力于构建融合多模态感知、认知强化与体系演化的持续生长型机器人系统。项目将构建高保真月面世界模型，支持感知—控制解耦的异构计算框架，提升机器人在微重力与月尘干扰环境中的适应能力；通过大模型与专家知识融合，强化机器人认知与灵巧操作能力；进一步设计结构—控制—知识协同演化机制，推动机器人自适应行为与知识体系的持续进化。最终，基于虚实一体的仿真验证平台，实现从感知、理解到动作执行的闭环优化，为未来月球建造任务提供可靠、高效的智能化解决方案。



### 多智能体协同
---

- B

### 大模型驱动电机装配和拆卸
---

- 在工业制造与维修场景中，电机装配过程常面临零件种类繁多、装配关系复杂及知识经验依赖度高等挑战，制约了作业效率与智能化水平。针对这一问题，我们团队研发了一套基于多模态大模型的电机装配辅助系统，融合图像理解、结构知识建模与自然语言处理等核心技术。系统可自动识别电机结构图像，提取关键装配三元组，构建装配关系图谱，并生成合理的装配/拆卸序列及评分结果。该方案有效降低了人工依赖与出错率，为智能制造与维修提供了可靠支撑。

### 基于扩散模型的城市巷战异构机器人协同决策研究
---

- 随着人工智能的发展，机器人协同作战已成为提升战场效能的核心方向。本项目聚焦于城市巷战场景下异构机器人的协同决策，旨在集成场景感知、路径规划与具身控制等多项技术。研究拟通过扩散模型实现动态场景感知，并且将基于扩散模型，解决动态环境下的路径规划问题；同时将采用视觉语言动作大模型，优化机器人自主决策能力；最后，设计可扩展的系统管控架构，实现状态感知与多功能集成。由此，将为未来战争提供可能的高效解决方案。

### 基于VLA模型的可移动机械臂抓取系统及应用研究
---

- 在复杂的航空维修环境中，低光照、空间狭窄等问题严重制约了人工接线的效率与安全。针对这一痛点，本团队计划研发一套基于 VLA 模型的智能机械臂抓取系统，集成多模态感知、高精度运动控制与移动操作一体化技术。该系统可在较暗场景中实现高精度、低损伤的自动化线束连接，显著降低错误率与安全风险，为航空维护作业的智能化升级提供有力支撑。

<span class='anchor' id='-ryjx'></span>

# 🧪 已有实验设备
### 🤖 机器人
---
<div style="display: flex; gap: 20px; flex-wrap: wrap; justify-content: center;">
  <div class='paper-box'>
    <div class='paper-box-image'>
      <img src='images/laboratory_1.png' alt="宇树机器人" style="width: 200px;">
    </div>
  </div>
</div>

### 🐾 四足机器人
---
<div style="display: flex; gap: 20px; flex-wrap: wrap; justify-content: center;">
  <div class='paper-box'>
    <div class='paper-box-image'>
      <img src='images/laboratory_2.jpg' alt="宇树四足机器人" style="width: 200px;">
    </div>
  </div>

  <div class='paper-box'>
    <div class='paper-box-image'>
      <img src='images/laboratory_3.jpg' alt="宇树四足机器人" style="width: 200px;">
    </div>
  </div>
</div>

### 🏭 自动化产线
---
<div style="display: flex; gap: 20px; flex-wrap: wrap; justify-content: center;">
  <div class='paper-box'>
    <div class='paper-box-image'>
      <img src='images/laboratory_4.jpg' alt="自动化产线" style="width: 200px;">
    </div>
  </div>

  <div class='paper-box'>
    <div class='paper-box-image'>
      <img src='images/laboratory_5.jpg' alt="机械臂" style="width: 200px;">
    </div>
  </div>
</div>

### 🦾 机械臂
---
<div style="display: flex; gap: 20px; flex-wrap: wrap; justify-content: center;">
  <div class='paper-box'>
    <div class='paper-box-image'>
      <img src='images/laboratory_7.png' alt="D1机械臂" style="width: 200px;">
    </div>
  </div>
</div>

### 🖨️ 3D打印机
---
<div style="display: flex; gap: 20px; flex-wrap: wrap; justify-content: center;">
  <div class='paper-box'>
    <div class='paper-box-image'>
      <img src='images/laboratory_6.jpg' alt="3D打印机" style="width: 200px;">
    </div>
  </div>
</div>

<span class='anchor' id='-xshy'></span>

# 🏛️ 合作单位

### 🏫 科研单位合作
---

- 清华大学
- 上海交通大学
- 南京大学
- 阿尔伯特大学

### 🤝 产业合作伙伴
---

- 中国空间技术研究院
- 中国航空工业集团成飞
- 中国航空发动机集团
- BAOWU中国宝武
- 中国兵器工业集团有限公司
- 安徽三禾一信息科技有限公司
- 奇瑞汽车股份有限公司

