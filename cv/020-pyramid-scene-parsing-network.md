## 20. Pyramid Scene Parsing Network

### 20.1 第一课时

<video width=80%  controls >
	<source type="video/mp4" src="020-pyramid-scene-parsing-network/020-1.mp4">
</video>

**任务名称：**掌握全局信息与局部信息的含义及特点，了解复杂场景解析问题中的常见问题。

**任务简介：**观看视频第一课时，将其中不明白的知识点记录下来，先自行搜索学习。

**任务详解：**

1. 视频第一课时

   1. 全局信息与局部信息

      全局信息与局部信息在语义分割中发挥着重要作用，且两者的关系是相辅相成缺一不可的。在网络的不同位置中提取不同信息，两者的特点和目的也需要研究者深入挖掘，以设计出更适合分割任务的网络模型。提取到的不同种类信息要以恰当的方式进行融合，才能将全局与局部信息的作用发挥到最大。

   2. 复杂场景解析中的常见问题

      对于复杂场景，分割任务总是困难重重，其问题主要集中在三个方面，分别是不匹配关系、混淆类别以及不寻常类。这就要求分割模型具有很强的功能性以使模型在最大程度上拟合上述问题。 

论文原文及代码下载链接：https://pan.baidu.com/s/1oXu6l6aLx8cQH3Bfj2jeOw 

提取码：qris 

### 20.2 第二课时

<video width=80%  controls >
	<source type="video/mp4" src="020-pyramid-scene-parsing-network/020-2.mp4">
</video>

**任务名称：**学习阅读论文的方法，进一步了解经典模型的部分细节，从理论掌握模型结构，论文中的技巧。

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

**打卡要求：**（形式：文字或者图片，每个问题字数至少50）

1. 回答下列问题：
   1. 用文字描述论文中的Figure 3。
   2. 自行编写或到GitHub上找到基于Pytorch的PSP模块代码