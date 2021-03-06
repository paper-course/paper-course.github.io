## 23. Visual Tracking with Fully Convolutional Networks

### 23.1 第一课时

<video width=80%  controls >
	<source type="video/mp4" src="023-visual-tracking-with-fully-convolutional-networks/023-1.mp4">
</video>

**任务名称：**了解FCNT目标跟踪问题

**任务简介：**观看视频第一课时，阅读论文

**任务详解：**

1. 视频第一课时
   1. 论文的研究背景、成果及意义

      为大家解答为什么这篇论文成为了近几年来目标跟踪领域非常火热的论文。讲解为什么需要在全卷积网络的基础之上再提出这个网络，以及以往跟踪算法网络的缺陷

   2. Abstract,Introduction部分详读

      讲解FCNT中具体有什么不一样的网络结构以及设置这些网络结构的原因。

   3．课程规划

   ​		第二期课程与第一期课程安排不太一样，所以我们需要给大家着重讲解下课程安排

2. 论文阅读

   花费大致2h来阅读论文，主要通过阅读了解模型的大致结构，将疑问记录在作业中。

   这个部分我们只需要比较熟悉地了解到导读视频的程度，不需要过于深入地去学习，将重点放置在论文的模型上，对于其他的部分有疑问可以暂时记录着，并写在这两天的作业中。

**论文原文及代码下载**

链接：https://pan.baidu.com/s/1t3xXfX_dPi-4P9YZQrtUhg 

提取码：oenh 

### 23.2 第二课时

<video width=80%  controls >
	<source type="video/mp4" src="023-visual-tracking-with-fully-convolutional-networks/023-2.mp4">
</video>

**任务名称：**学习阅读论文的方法，进一步了解经典模型的部分细节，从理论掌握模型结构，论文中的技巧

**任务简介：**观看视频第二课时，阅读论文

**任务详解：**

1. 视频
   1. 学习阅读论文的方法

      论文的阅读不是从头到尾，也不是每个部分都一定是非常值得推敲。我们需要掌握练习合适的阅读节奏，在不同的学习阶段，去从论文中汲取不同的东西，将保证我们更有效率地学习，也将保证我们学习的过程更加自然。

   2. 进一步了解经典模型的部分细节

      经典模型的部分细节的了解可以帮助我们更好地理解论文模型的部分细节，同时也为大家自助学习其他的经典模型提供了一个铺垫。

   3. 从理论掌握模型结构，论文中的技巧

      模型的掌握不是画出网络图形，然后把公式写出来就算掌握了，那样只能算是对学习知识的复述。需要能真正明白模型的各个部分的所以然。这个部分将从整体到细节讲解模型结构的各个部分，主要思想的动机，与其他经典模型的对比，论文实现过程中使用到的技巧。

2. 阅读论文

   在学习完视频之后再阅读论文，看看自己是不是能了然于胸，对照课程PPT阅读，记录疑问

### 23.3 第三课时

<video width=80%  controls >
	<source type="video/mp4" src="023-visual-tracking-with-fully-convolutional-networks/023-3.mp4">
</video>

**任务名称：**学习阅读论文的方法，进一步了解经典模型的部分细节，从理论掌握模型结构，论文中的技巧

**任务简介：**观看视频第二课时，阅读论文

**任务详解：**

1. 视频
   1. 学习阅读论文的方法

      论文的阅读不是从头到尾，也不是每个部分都一定是非常值得推敲。我们需要掌握练习合适的阅读节奏，在不同的学习阶段，去从论文中汲取不同的东西，将保证我们更有效率地学习，也将保证我们学习的过程更加自然。

   2. 进一步了解经典模型的部分细节

      经典模型的部分细节的了解可以帮助我们更好地理解论文模型的部分细节，同时也为大家自助学习其他的经典模型提供了一个铺垫。

   3. 从理论掌握模型结构，论文中的技巧

      模型的掌握不是画出网络图形，然后把公式写出来就算掌握了，那样只能算是对学习知识的复述。需要能真正明白模型的各个部分的所以然。这个部分将从整体到细节讲解模型结构的各个部分，主要思想的动机，与其他经典模型的对比，论文实现过程中使用到的技巧。

2. 阅读论文

   在学习完视频之后再阅读论文，看看自己是不是能了然于胸，对照课程PPT阅读，记录疑问

**打卡要求：**

通过文字或者图片的形式写下这篇论文中FCNT的技术流程，从图片的预处理部分开始，一直到最后检测出目标，同时将使用的VGG网络结构经调研之后画出来，字数不少于200字。

### 23.4 第四课时

<video width=80%  controls >
	<source type="video/mp4" src="023-visual-tracking-with-fully-convolutional-networks/023-4.mp4">
</video>

**任务名称：**代码实践的方法与流程，从0编码模型结构，讲解训练部分内容

**任务简介：**观看视频第4课时，理解FCNT的代码部分

**任务详解：**

1. 视频
   1. 代码实践的方法与流程

      这个部分将带领大家掌握基本的寻找解决方案的流程，介绍如何利用一些工具去帮助我们高效分析代码的结构。这些实战的经验很重要，需要大家不断地学习与应用。

   2. 讲解训练部分内容

      实验的完成不单单只需要模型结构，训练的设置对于模型实现效果也非常重要。这里重点讲解了通常编解码框架都需要的训练流程，以及论文中使用的部分技巧。这些东西也是要求大家能灵活运用的。