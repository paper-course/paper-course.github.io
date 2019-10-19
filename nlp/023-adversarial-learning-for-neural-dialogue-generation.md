## 23. Adversarial Learning for Neural Dialogue Generation

### 23.1 第一课时

<video width=80%  controls >
	<source type="video/mp4" src="023-adversarial-learning-for-neural-dialogue-generation/023-1.mp4">
</video>

**任务名称：**了解对话生成、GAN和SeqGAN

**任务简介：**观看视频第一课时，阅读论文

**任务详解：**这个部分我们了解GAN基本概念，了解SeqGAN的实现方式，了解GAN的训练过程。

1. 视频第一课时
   1. 序列概率

      常规的序列生成任务都是通过最大化序列生成概率，并通过MLE损失优化模型。

   2. GAN

      GAN是生成任务中火热的一类方法，通过对抗训练判别器与生成器，达到两方的那什均衡。

   3. SeqGAN

      GAN在设计之初是面向图像生成任务的，并不能直接应用于离散的NLP任务中，SeqGAN通过引入策略梯度和强化学习，为每个时间步的决策带来对应的奖赏，实现了GAN在生成任务中的应用。

2. 论文阅读

   花费大致2h来阅读论文，主要通过阅读了解模型的大致结构，将疑问记录在作业中。

**论文原文下载：**

链接：https://pan.baidu.com/s/1_NddfI4ywm1Tt5ALkVB54A 

提取码：s099 

**打卡要求：**阅读将强化学习应用到对话生成的第一篇论文，Deep reinforcement learning for dialogue generation，并查阅相关资料，写一篇阅读笔记。 

### 23.2 第二课时

<video width=80%  controls >
	<source type="video/mp4" src="023-adversarial-learning-for-neural-dialogue-generation/023-2.mp4">
</video>

**任务名称：**学习阅读论文的方法，进一步了解经典模型的部分细节，从理论掌握模型结构，论文中的技巧

**任务简介：**观看视频第二课时，阅读论文

**任务详解：**这个部分我们需要能够理解本文提出的两种REGS策略，并掌握本文提出的应用于GAN的teacher forcing方法。

1. 视频

   本文将GAN引入到对话生成中来生成更符合人类习惯的回复。通过两种奖励设计策略，实现了为每个token生成一个reward。通过teacher-forcing让模型知道什么样的回复是好的回复。

**打卡要求：**（形式：文字或者图片，字数至少100）

1. 回答下列问题：
   1. 结合SeqGAN，考虑如何用代码实现蒙特卡洛采样以及近似公式2的期望损失？
   2. 为什么公式2中要引入b函数？