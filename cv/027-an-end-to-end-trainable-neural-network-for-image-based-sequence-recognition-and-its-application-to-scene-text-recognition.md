## 27. An End-to-End Trainable Neural Network for Image-based Sequence Recognition and Its Application to Scene Text Recognition

### 27.1 第一课时

<video width=80%  controls >
	<source type="video/mp4" src="027-an-end-to-end-trainable-neural-network-for-image-based-sequence-recognition-and-its-application-to-scene-text-recognition/027-1.mp4">
</video>

**任务名称：**了解OCR文字识别问题

**任务简介：**观看视频第一课时，阅读论文

**任务详解：**

1. 视频第一课时
   1. 论文的研究背景、成果及意义

      为大家解答为什么这篇论文成为了近几年来OCR文字识别领域非常火热的论文。讲解为什么需要在目标跟踪领域提出一个评估标准，以及本文做的几点贡献

   2. Abstract，Introduction部分详读

      讲解OCR目前主要受制约的地方在于没有提供一个良好的数据集和评估算法鲁棒性的标准

   3．课程规划

   ​	第二期课程与第一期课程安排不太一样，所以我们需要给大家着重讲解下课程安排

2. 论文阅读

   花费大致2h来阅读论文，主要通过阅读了解大致结构，将疑问记录在作业中。

   这个部分我们只需要比较熟悉地了解到导读视频的程度，不需要过于深入地去学习，对于其他的部分有疑问可以暂时记录着，并写在这两天的作业中。

**论文原文及代码下载链接：**

链接：https://pan.baidu.com/s/1oNE5LH-cvvNyJzDZxIhoYA 

提取码：d5i4 

**打卡要求：**

1. 按照自己的理解总结上述三个知识点，至少提出2个疑问，用文字写下来，字数至少100。

**思考题：**

1. 文中主要分为哪三个layer？以及每一个layer的作用是什么？

2. LSTM理解吗？LSTM的流程是怎么样的一个流程？为什么我们要使用LSTM作为文章中的一个基本算法？ 

### 27.2 第二课时

<video width=80%  controls >
	<source type="video/mp4" src="027-an-end-to-end-trainable-neural-network-for-image-based-sequence-recognition-and-its-application-to-scene-text-recognition/027-2.mp4">
</video>

**任务名称：**学习阅读论文的方法，从理论掌握模型结构，论文中的技巧

**任务简介：**观看视频第二课时，阅读论文

**任务详解：**

1. 视频
   1. 学习阅读论文的方法

      论文的阅读不是从头到尾，也不是每个部分都一定是非常值得推敲。我们需要掌握练习合适的阅读节奏，在不同的学习阶段，去从论文中汲取不同的东西，将保证我们更有效率地学习，也将保证我们学习的过程更加自然。

   2. 进一步了解经典模型的部分细节

      经典模型的部分细节的了解可以帮助我们更好地理解论文模型的部分细节，同时也为大家自助学习其他的经典模型提供了一个铺垫。

   3. 从理论掌握模型结构，论文中的技巧

      了解网络评估的方式，包括目标表示方式，搜索机制，模型更新，上下文和跟踪器融合以及鲁棒性评估分类。这个部分将从整体到细节讲解模型结构的各个部分，主要思想的动机，与其他经典模型的对比，论文实现过程中使用到的技巧。

2. 阅读论文

   在学习完视频之后再阅读论文，看看自己是不是能了然于胸，对照课程PPT阅读，记录疑问

**打卡要求：**

1. 通过文字或者图片的形式写下这篇论文中的技术要点，字数不少于100字。

2. 对文章中的公式进行消化

**思考题：**

1. 为什么文章中要使用基于字典的方法？这种方式有什么好处？