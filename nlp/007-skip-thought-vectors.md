## 7. Skip-Thought Vectors

### 7.1 第一课时

<video width=80%  controls >
	<source type="video/mp4" src="007-skip-thought-vectors/007-1.mp4">
</video>

任务名称：了解句表示的主要应用及常见方法

任务简介：观看视频第一课时，阅读论文

任务详解：这个部分我们只需要比较熟悉地了解到导读视频的程度，不需要过于深入地去学习，将重点放在Doc2vec、基于复述的句表示，以及词袋模型句表示的优缺点上。

1. 视频第一课时

   1. 句表示

      想要让机器能够理解语言，最基础的也是最重要的就是将自然语言编码为机器能够处理的方式。在自然语言处理领域中有很多句子级别的任务，句子级别的建模表示能够有效改善这些任务的性能。

   2. 基于词袋模型的句表示

      词袋模型是最早的一种句表示方法，其简单、高效，导致其现在在某些场景中仍是句子的重要表达方式，掌握基于独热表示的句表示以及词向量加权平均句表示。

   3. 基于神经网络的句表示

      神经语言与深度学习是目前最火热的研究方向，也是句表示技术的来源与基础，掌握早期的两种基于神经网络的句表示技术—Doc2vec及基于复述的有监督句表示，有利于我们了解这个领域的全貌。

2. 论文阅读

   花费大致2h来阅读论文，主要通过阅读了解模型的大致结构，将疑问记录在作业中。 

论文及代码下载链接：

链接：https://pan.baidu.com/s/1Zt0hUtgm5otWOEhZXhzApg 

提取码：d23b 

### 7.2 第二课时

<video width=80%  controls >
	<source type="video/mp4" src="007-skip-thought-vectors/007-2.mp4">
</video>

任务名称：学习阅读论文的方法，进一步了解经典模型的部分细节，从理论掌握模型结构，论文中的技巧

任务简介：观看视频第二课时，阅读论文

任务详解：

1. 视频

   1. 了解Skip-thought模型的动机

   2. 真正明白模型的各个部分的所以然，以及主要思想的动机。

   3. 了解Skip-thought模型的部分细节

      经典模型的部分细节的了解可以帮助我们更好地理解论文模型的部分细节，论文实现过程中使用到的技巧，同时也为大家自助学习其他的经典模型提供了一个铺垫。

   4.了解后续改进工作Quick-thought的动机及改进方式

2. 阅读论文

   在学习完视频之后再阅读论文，看看自己是不是能了然于胸，对照课程PPT阅读，记录疑问

任务详解： 这个部分我们只需要能够理解Skip-thought的思想，以及其采用的Conditional Decoder即可。

打卡要求：（形式：文字或者图片，字数至少100）

1. 回答下列问题：
   1. 和自编码器（Auto Encoder）相比，Skip-thought能够取得更好的效果，这是因为什么呢？可以大胆分析。
   2. 如果让你继续改进Skip-thought或者Quick-thought，你会怎么做？

### 7.3 第三课时

<video width=80%  controls >
	<source type="video/mp4" src="007-skip-thought-vectors/007-3.mp4">
</video>

任务名称：学习阅读代码的方法，进一步了解模型的具体实现思路

任务简介：观看视频第三课时，阅读代码

任务详解：

1. 视频
   1. 了解Conditional Decoder的具体实现方式
   2. 了解Skip-thought模型的实现细节
   3. 了解Teacher forcing策略的思想

2. 阅读代码

   在学习完视频之后再逐行阅读代码，看看自己是不是能了然于胸，对照课程PPT阅读，记录疑问

论文原文和代码附件：

链接：https://pan.baidu.com/s/1Zt0hUtgm5otWOEhZXhzApg 

提取码：d23b 

 打卡要求：（形式：文字或者图片，字数至少100）

1. 回答下列问题：
   1. 因为本次代码较为简单，关闭PPT，根据数据及代码框架，从头到尾完成项目并成功运行。

2. 在项目代码的基础上，实现Quick-thought
