

## 24. SeqGAN: Sequence Generative Adversarial Nets with Policy Gradient

### 24.1 第一课时

<video width=80%  controls >
	<source type="video/mp4" src="024-sequence-generative-adversarial-nets-with-policy-gradient/024-1.mp4">
</video>

**任务名称：**了解GAN和序列概率

**任务简介：**观看视频第一课时，阅读论文

**任务详解：**这个部分我们需要比较熟悉地了解到导读视频的程度，了解GAN基本概念。

1. 视频第一课时
   1. 序列概率

      常规的序列生成任务都是通过最大化序列生成概率，并通过MLE损失优化模型。

   2. GAN

      GAN是生成任务中火热的一类方法，通过对抗训练判别器与生成器，达到两方的那什均衡。

2. 论文阅读

   花费大致2h来阅读论文，主要通过阅读了解模型的大致结构，将疑问记录在作业中。 

**论文原文下载：**

链接：https://pan.baidu.com/s/1SkP39g5_UF-yI5azgNoNhw 

提取码：4rcf

**打卡要求：**阅读GAN的第一篇论文，Generative Adversarial Nets，并查阅相关资料，写一篇阅读笔记。 

### 24.2 第二课时

<video width=80%  controls >
	<source type="video/mp4" src="024-sequence-generative-adversarial-nets-with-policy-gradient/024-2.mp4">
</video>

**任务名称：**学习阅读论文的方法，进一步了解经典模型的部分细节，从理论掌握模型结构，论文中的技巧

**任务简介：**观看视频第二课时，阅读论文

**任务详解：**

1. 视频

   GAN在设计之初是面向图像生成任务的，并不能直接应用于离散的NLP任务中，本文通过引入策略梯度和强化学习，为每个时间步的决策带来对应的奖赏，实现了GAN在生成任务中的应用。

 **任务详解：**这个部分我们需要能够理解为什么GAN很难直接应用到NLP任务中，并掌握模型的设计细节，必要时推导公式，掌握GAN模型的训练步骤。

**打卡要求：**（形式：文字或者图片，字数至少100）

1. 回答下列问题：
   1. 如何用代码实现蒙特卡洛采样以及近似公式6的期望损失？