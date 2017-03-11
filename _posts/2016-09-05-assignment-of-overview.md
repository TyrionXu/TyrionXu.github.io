---
layout:     post
title:      "data science 101"
subtitle:   "first week summary of learning"
date:       2016-09-05 11:00:00
author:     "Tyrion"
header-img: "img/post-bg-2015.jpg"
tags:
    - python
--- 

# 笔记
---
## 数据科学介绍
- 数据闭环
  * 跟踪效果迭代优化
  * 不间断的收集数据
  * 基于数据获得洞察
  * 基于发现做出决策
- 数据产生价值的方式：
   + 直接使用数据
   + 建模和数据报告（解释历史，预测未来，控制未来）
   + 数据产品（自动化，时效性）
- 数据有什么应用价值?
   + 回答一个事实性的问题，发现一些模式
   + 预测未来是否会发现
   + 探索一些因素间的关系，做出一些决策
   + 自动化工作流程
- 数据科学出现的前提条件
  + 数据的储存和运算成本更低
  + 开源软件工具和公开课分享跨界
## 统计陷阱
- 如何对统计提出质疑
  + 谁说的 利益相关
  + 他怎么知道 数据的收集过程
  + 漏了什么 有没有什么重要相关因素没有被考虑
  + 是否有人改变了主题 答不应题
  + 这有道理 个人的经验判断

### 练习题1
    人均GDP， CPI指数可以结合起来考量生活水平的变化。但是可能由于CPI篮子
    一些局限的因素不能准确的反映生活水平的变化。人均GDP的统计过程中，数
    据产生的真实性也有一些问题。  

![人均GDP](http://s1149.photobucket.com/user/TyrionXu/media/tuchuang/QQ20160905110125_zpsengfxlam.png.html)

![CPI](http://i1149.photobucket.com/albums/o600/TyrionXu/tuchuang/QQ20160905111243_zpscx2tkty8.png)

### 练习题2
   双盲实验中的盲可以理解为屏蔽信息的意思，在参与实验的过程中有实验者，研究者，和资料分析人员。 依据屏蔽信息的不同，依次为单盲，双盲，三盲。 双盲实验，可以有效的减少安慰剂效应和研究者先入为主的观念对实验的影响。
   Simpson's Paradox  指的在分部的数据对比中得到的结论，与放在一起得到的结论相反。 主要是一个权重的问题，一个是有量纲的数据，一个是无量纲的数据。所以对比会出现偏差。
   例如，各个学校的升学率都上升了，但升学学生数量却下降了，有可能是今年学生较去年大幅下降了。

   这是我用google nagram搜索篮球，足球，棒球的情况，可以很明显看出它们的流行趋势的变化。
   <iframe name="ngram_chart" src="https://books.google.com/ngrams/interactive_chart?content=football%2C+basketball%2C+baseball&year_start=1800&year_end=2000&corpus=15&smoothing=3&share=&direct_url=t1%3B%2Cfootball%3B%2Cc0%3B.t1%3B%2Cbasketball%3B%2Cc0%3B.t1%3B%2Cbaseball%3B%2Cc0" width=900 height=500 marginwidth=0 marginheight=0 hspace=0 vspace=0 frameborder=0 scrolling=no></iframe>

### 练习题3
   在检验结果是阳性情况下， A：有可能是误诊，0.999x0.05，B：也有可能是确诊， 0.001x0.99。
   所以确实得病的概率为，P(B)/(P(A)+P(B)) 为1.943%

