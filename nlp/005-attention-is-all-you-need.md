## 5. Attention is All You Need

### 5.1 第一课时

<video width=80%  controls >
	<source type="video/mp4" src="005-attention-is-all-you-need/005-1.mp4">
</video>

任务名称：了解序列问题，seq2seq的基本框架，经典的seq2seq模型

任务简介：观看视频第一课时，阅读论文

任务详解：

1. 视频第一课时

   1. 序列问题

      自然语言处理的输入输出基本上都是序列，序列问题是自然语言处理最本质的问题，甚至一些计算机视觉问题也是序列问题，包括金融上的一些问题，交通流上的一些问题等等。序列问题非常的宽泛，掌握nlp序列问题的学习不仅仅帮助我们能快速地切入到其他更具体场景的nlp应用，也能帮助我们更好地迁移到其他应用领域的问题上。

   2. seq2seq的基本框架

      seq2seq是序列问题中一个非常重要的模型，很多的序列问题都可以用seq2seq来解决，比如说机器翻译、语音转文字、图像标注、文本总结等等。seq2seq基本框架还适用于图像压缩，超分辨率等计算机视觉的问题。掌握seq2seq的基本框架是学习这篇论文的基础。

   3. 经典的seq2seq模型

      了解当前的seq2seq模型的主要流派，了解他们提出的动机，模型的优缺点，更好地引出本篇论文，也帮助我们更好地学习论文。

2. 论文阅读

   花费大致2h来阅读论文，主要通过阅读了解模型的大致结构，将疑问记录在作业中。

   这个部分我们只需要比较熟悉地了解到导读视频的程度，不需要过于深入地去学习，将重点放置在论文的模型上，对于其他的部分有疑问可以暂时记录着，并写在这两天的作业中。

论文原文下载链接：

链接：https://pan.baidu.com/s/1VwMGcn87EekUsvU0c8R6gA 

提取码：1wgx 

中文译文参考：https://zhuanlan.zhihu.com/p/36699992



### 5.2 第二课时

<video width=80%  controls >
	<source type="video/mp4" src="005-attention-is-all-you-need/005-2.mp4">
</video>

任务名称：学习阅读论文的方法，进一步了解经典模型的部分细节，从理论掌握模型结构，论文中的技巧

任务简介：观看视频第二课时上和下，阅读论文

任务详解：

1. 视频

   1. 学习阅读论文的方法

      论文的阅读不是从头到尾，也不是每个部分都一定是非常值得推敲。我们需要掌握练习合适的阅读节奏，在不同的学习阶段，去从论文中汲取不同的东西，将保证我们更有效率地学习，也将保证我们学习的过程更加自然。

   2. 进一步了解经典模型的部分细节

      经典模型的部分细节的了解可以帮助我们更好地理解论文模型的部分细节，同时也为大家自助学习其他的经典模型提供了一个铺垫。

   3. 从理论掌握模型结构，论文中的技巧

      模型的掌握不是画出网络图形，然后把公式写出来就算掌握了，那样只能算是对学习知识的复述。需要能真正明白模型的各个部分的所以然。这个部分将从整体到细节讲解模型结构的各个部分，主要思想的动机，与其他经典模型的对比，论文实现过程中使用到的技巧。

2. 阅读论文

   在学习完视频之后再阅读论文，看看自己是不是能了然于胸，对照课程视频阅读，记录疑问

 打卡要求：（形式：文字或者图片，字数至少100字）

1. 回答下列问题：
   1. 自注意力与注意力的区别？
   2. 为什么要进行残差连接？
   3. 为什么要设置多头注意力 ？
   4.  一个自注意力层计算的复杂度是多少，为什么？
   5. 为什么要进行mask？
   6.  位置嵌入除了文中的这种形式还有哪些？

2. 关闭一切资源，从0开始写出transformer的编解码网络。



### 5.3 第三课时

<video width=80%  controls >
	<source type="video/mp4" src="005-attention-is-all-you-need/005-3.mp4">
</video>

任务名称：学习阅读论文的方法，进一步了解经典模型的部分细节，从理论掌握模型结构，论文中的技巧

任务简介：观看视频第二课时上和下，阅读论文

任务详解：

1. 视频

   1.  学习阅读论文的方法

      论文的阅读不是从头到尾，也不是每个部分都一定是非常值得推敲。我们需要掌握练习合适的阅读节奏，在不同的学习阶段，去从论文中汲取不同的东西，将保证我们更有效率地学习，也将保证我们学习的过程更加自然。

   2. 进一步了解经典模型的部分细节

      经典模型的部分细节的了解可以帮助我们更好地理解论文模型的部分细节，同时也为大家自助学习其他的经典模型提供了一个铺垫。

   3.  从理论掌握模型结构，论文中的技巧

      模型的掌握不是画出网络图形，然后把公式写出来就算掌握了，那样只能算是对学习知识的复述。需要能真正明白模型的各个部分的所以然。这个部分将从整体到细节讲解模型结构的各个部分，主要思想的动机，与其他经典模型的对比，论文实现过程中使用到的技巧。

2. 阅读论文

   在学习完视频之后再阅读论文，看看自己是不是能了然于胸，对照课程视频阅读，记录疑问

 打卡要求：（形式：文字或者图片，字数至少100字）

1. 回答下列问题：
   1. 自注意力与注意力的区别？
   2. 为什么要进行残差连接？
   3. 为什么要设置多头注意力 ？
   4. 一个自注意力层计算的复杂度是多少，为什么？
   5. 为什么要进行mask？
   6. 位置嵌入除了文中的这种形式还有哪些？

2. 关闭一切资源，从0开始写出transformer的编解码网络。



### 5.4 第四课时

<video width=80%  controls >
	<source type="video/mp4" src="005-attention-is-all-you-need/005-4-1.mp4">
</video>

<video width=80%  controls >
	<source type="video/mp4" src="005-attention-is-all-you-need/005-4-2.mp4">
</video>

任务名称：代码实践的方法与流程，从0编码模型结构，讲解训练部分内容

任务简介：观看视频第三课时，阅读并运行成功哈佛nlp的博客

任务详解：

1. 视频

   1. 代码实践的方法与流程

      代码实践时很多同学会无从下手，会躲避，但其实这个过程才是能力真正提升的时候。这个部分将带领大家掌握基本的寻找解决方案的流程，介绍如何利用一些工具去帮助我们高效配置环境，分析代码的结构。这些实战的经验很重要，需要大家不断地学习与应用。

   2. 从0编码模型结构

      如果总是停留在代码的修改，微调上，实践能力很难提升。这里将带领大家从0开始，从整体到细节的方式来实现模型的整个结构，这个部分非常重要，需要大家仔细磨练，直至自己能够从0开始写出这样的结构。

   3. 讲解训练部分内容

      实验的完成不单单只需要模型结构，训练的设置对于模型实现效果也非常重要。这里重点讲解了通常编解码框架都需要的训练流程，以及论文中使用的部分技巧。这些东西也是要求大家能灵活运用的。

2. 阅读哈佛nlp的博客

   在学习完视频之后再阅读博客，完成剩余技巧的学习，将跑出的结果截图。

   这个部分非常非常重要，需要大家认真完成，花出大量时间完成调试，认真积累自己碰到的错误，一一寻找解决。

代码包下载链接：

https://pan.baidu.com/s/1p2Gg8dGI7BBDMEGSkkmnpg 

提取码：h68z 

 打卡要求：（形式：图片）

1. 哈佛nlp博客（[http://nlp.seas.harvard.edu/2018/04/03/attention.html](http://nlp.seas.harvard.edu/2018/04/03/attention.html)）运行结果截图

2. 开源pytorch 实现（https://github.com/jadore801120/attention-is-all-you-need-pytorch）在WMT'16 Multimodal Translation: Multi30k(de-en)上的测试结果