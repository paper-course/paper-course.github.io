## 19. Get To The Point: Summarization with Pointer-Generator Networks

### 19.1 第一课时

<video width=80%  controls >
	<source type="video/mp4" src="019-get-to-the-point-summarization-with-pointer-generator-networks/019-1.mp4">
</video>

任务名称：了解seq2seq、文本摘要

任务简介：观看视频第一课时，阅读论文

任务详解：这个部分我们只需要比较熟悉地了解到导读视频的程度，不需要过于深入地去学习，将重点放在seq2seq、以及文本摘要的两类方法上，对经典的方法有一定了解。论文中有疑问的部分可以先记录着。

1. 视频第一课时
   1. Seq2seq

      NLP中的一类任务就是序列生成，指的是让神经网络按序生成符合语法规则的自然语言文本。目前的序列生成任务大都基于seq2seq框架。掌握基础的seq2seq结构，以及在seq2seq中加入attention的改进版结构。

   2. 文本摘要

      文本摘要是目前很火热的研究方向，主要研究如何将长文本浓缩为短文本，涉及两类主要方法，第一类的抽取式摘要，第二类是生成式摘要。

2. 论文阅读

   花费大致2h来阅读论文，主要通过阅读了解模型的大致结构，将疑问记录在作业中。

论文下载：

链接：https://pan.baidu.com/s/1a8qDBWGr2rQL6-oJPhCZNg 

提取码：zxq8 

### 19.2 第二课时

<video width=80%  controls >
	<source type="video/mp4" src="019-get-to-the-point-summarization-with-pointer-generator-networks/019-2.mp4">
</video>

任务名称：学习阅读论文的方法，进一步了解经典模型的部分细节，从理论掌握模型结构，论文中的技巧

任务简介：观看视频第二课时，阅读论文

任务详解：这个部分我们需要能够理解模型的设计细节，并掌握﻿Pointer-generator network和﻿Coverage mechanism。

1. 视频
   1. 了解Pointer network

      了解模型的设计动机，以及加入pointer和﻿Coverage机制后对模型的影响。。

2. 阅读论文

   在学习完视频之后再阅读论文，看看自己是不是能了然于胸，对照课程PPT阅读，记录疑问

打卡要求：（形式：文字或者图片，字数至少100）

1. 回答下列问题：
   1. 为了加入pointer，作者进行了哪些改进？
   2. 如果让你来设计pointer，你还有哪些设计方式？