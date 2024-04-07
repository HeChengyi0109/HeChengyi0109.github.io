---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# 教育背景
* 2024年9月-今 东北大学 控制科学与工程 硕士研究生
* 2020年9月-2024年6月 东北石油大学 自动化 本科

# 实习经历
## 2023年7月-8月: 大庆油田第二采油厂仪表大队
数据监控：
    在工作者的引导下，学习并参与了操作站内仪表设备的监控和维护
安全保障：
    重中之重是确保仪表设备的正常工作，防止事故和危险的发生
    
## 2021年7月-8月：深圳佳运通电子大庆分公司
生产流程参观：
    组织性进入公司生产车间进行参观，学习了解工艺生产流程
仪表设备维护：
    先学习了各种仪表、传感器的原理及安装，之后进行了仪表的检修和校准等工作
    
# 技能
* 熟练掌握罗克韦尔品牌PLC Micro800系列
* 熟练掌握ROS系统
  * 能够使用ROS作为上位机来对差速小车进行控制
  * 能够在ROS环境下进行2D激光雷达SLAM技术的应用
  * 能够在ROS环境下实现AGV(Automated Guided Vehicle)的应用
* 熟练使用MATLAB
  * 能够熟练使用Simulink和m语言对控制系统进行建模和仿真
  * 能够使用m语言进行数学建模
  * 能够熟练使用m语言进行数据处理与分析
* 能够使用Python进行数据分析与处理
  * 熟悉pandas包
  * 熟悉matplotlib包
  * 熟悉python的环境搭建

# 项目经历

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
