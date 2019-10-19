## 27. Transformer-XL: Attentive Language Models Beyond a Fixed-Length Context

### 27.1 第一课时

<video width=80%  controls >
	<source type="video/mp4" src="027-attentive-language-models-beyond-a-fixed-length-context/027-1.mp4">
</video>

**任务名称：**了解RNN、Transformer

**任务简介：**观看视频第一课时，阅读论文

**任务详解：**这个部分我们需要比较熟悉地了解到导读视频的程度，掌握Transformer的架构和计算公式，不需要过于深入地去学习，论文中有疑问的部分可以先记录着。

1. 视频第一课时

   1. RNN

      RNN及其变种是NLP中常用的序列建模方法。受限于其无法并行以及无法建模长距离的限制，目前已逐渐被Transformer取代。

   2. Transformer

      Transformer是目前最火热的序列建模方法，掌握其具体的架构以及多头自注意力机制的计算方法

2. 论文阅读

   花费大致2h来阅读论文，主要通过阅读了解模型的大致结构，将疑问记录在作业中。

**论文原文下载：**

链接：https://pan.baidu.com/s/1dHh_myBwA4YLPzgC90vwwg 

提取码：3x6q 

**打卡要求：**（形式：文字，字数至少100）按照自己的理解总结上述知识点（最好分点清晰，有树状的层次结构，必要时推导公式）。

### 27.2 第二课时

<video width=80%  controls >
	<source type="video/mp4" src="027-attentive-language-models-beyond-a-fixed-length-context/027-2.mp4">
</video>

**任务名称：**学习阅读论文的方法，进一步了解经典模型的部分细节，从理论掌握模型结构，论文中的技巧

**任务简介：**观看视频第二课时，阅读论文

**任务详解：**

1. 视频

   1. 了解Transformer-XL模型的细节

      对比Transformer，XL在建模多个segment之间的依赖关系上进行了改进。同时改进了相对位置编码方式。阅读论文

2. 在学习完视频之后再阅读论文，看看自己是不是能了然于胸，对照课程PPT阅读，记录疑问

**任务详解：**这个部分我们需要能够理解模型的设计细节以及动机，并掌握XL与Transformer的异同。

**打卡要求：**（形式：文字或者图片，字数至少100）

1. 回答下列问题：
   1. 建模多个segment之间的依赖关系，还有哪些方式？
   2. 阅读XLNet，XLNet在XL的基础上，又加入了哪些部分？