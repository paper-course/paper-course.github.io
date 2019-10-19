## 16. Convolutional Sequence to Sequence Learning

### 16.1 第一课时

<video width=80%  controls >
	<source type="video/mp4" src="016-convolutional-sequence-to-sequence-learning/016-1.mp4">
</video>

任务名称：了解seq2seq、卷积神经网络

任务简介：观看视频第一课时，阅读论文

任务详解：这个部分我们只需要比较熟悉地了解到导读视频的程度，不需要过于深入地去学习，将重点放在seq2seq、以及卷积神经网络上，论文中有疑问的部分可以先记录着。

1. 视频第一课时
   1. Seq2seq

      NLP中的一类任务就是序列生成，指的是让神经网络按序生成符合语法规则的自然语言文本。目前的序列生成任务大都基于seq2seq框架。掌握基础的seq2seq结构，以及在seq2seq中加入attention的改进版结构。

   2. 卷积神经网络

      卷积神经网络是基础的神经网络结构。掌握一维滤波、二维滤波的基本操作，熟悉CNN相对于RNN的优势与劣势。

2. 论文阅读

   花费大致2h来阅读论文，主要通过阅读了解模型的大致结构，将疑问记录在作业中。 

论文下载：

链接：https://pan.baidu.com/s/1Hh7UUQ42sitxCLccURLA3w 

提取码：h5pp 

打卡要求：（形式：文字，字数至少100）按照自己的理解总结上述知识点（最好分点清晰，有树状的层次结构，必要时推导公式）。

### 16.2 第二课时

<video width=80%  controls >
	<source type="video/mp4" src="016-convolutional-sequence-to-sequence-learning/016-2.mp4">
</video>

任务名称：学习阅读论文的方法，进一步了解经典模型的部分细节，从理论掌握模型结构，论文中的技巧

任务简介：观看视频第二课时，阅读论文

任务详解：这个部分我们需要能够理解模型的设计细节，并掌握multi-step attention。

1. 视频
   1. 学习阅读论文的方法

      论文的阅读不是从头到尾，也不是每个部分都一定是非常值得推敲。我们需要掌握练习合适的阅读节奏，在不同的学习阶段，去从论文中汲取不同的东西，将保证我们更有效率地学习，也将保证我们学习的过程更加自然。

   2. 了解ConvS2S模型的部分细节

      经典模型的部分细节的了解可以帮助我们更好地理解论文模型的部分细节，同时也为大家自助学习其他的经典模型提供了一个铺垫。掌握使用卷积神经网络作为Decoder需要解决对问题以及作者是如何解决的。

2. 阅读论文

   在学习完视频之后再阅读论文，看看自己是不是能了然于胸，对照课程PPT阅读，记录疑问

打卡要求：（形式：文字或者图片，字数至少100）

1. 回答下列问题：
   1. 为了使用CNN作为Decoder，作者进行了哪些改进？
   2. 能否Encoder使用RNN、Decoder使用CNN？查阅相关资料，并尝试设计模型