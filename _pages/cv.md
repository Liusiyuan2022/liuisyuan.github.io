---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* 复旦大学，计算机科学与技术（荣誉路径）本科生，2021.09–2025.06（预计），GPA 3.49/4.00

Honors & Awards
======
* 2024 全国计算机系统能力培养大赛“龙芯杯”一等奖（CPU 设计赛道全国第二名），作品“iFu Processor”

Projects
======
* iFu Processor 乱序多发射 CPU 设计（2023.06–2024.08）
  * 负责访存子系统设计，实现乱序多访存单元并刷新 IPC 性能记录
  * 在 FPGA 上适配龙芯 LA32r Linux，完成外设驱动与 2048、QuickJS 等应用运行
* 自然语言处理课程项目（2023.09–2024.01）
  * 使用 PyTorch 训练情感分析模型，对 BERT 等预训练模型开展下一句预测微调
  * 构建训练与验证流程，完成多轮调参与效果评估
* 长三角计算机视觉处理大赛（模型榜第五名）（2023.07–2024.12）
  * 以 YOLOv8 为基础进行数据增强与超参数调优，提升检测精度
  * 使用 TensorRT 对推理流程加速，整体训练效率提升约一倍

Experience
======
* 复旦大学计算机科学技术学院分团委学术科创部 部员（2021.09–2023.03）
  * 组织“走进实验室”活动，协调本科生与导师面对面交流
  * 策划学长经验分享会，负责现场摄影与公众号推送撰写

Skills
======
* 硬件设计：Chisel、SystemVerilog、FPGA、LA32r 架构
* 机器学习：PyTorch、BERT 微调、YOLOv8、TensorRT
* 软件与工具：Linux、Git、QuickJS、Python

Languages
======
* 中文（母语）
* 英语（CET-6 533/710）

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
  
Service and leadership
======
* 复旦大学计算机学院学术科创部志愿服务，承担活动组织与宣传撰写工作
