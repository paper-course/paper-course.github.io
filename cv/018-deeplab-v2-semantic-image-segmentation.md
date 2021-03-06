## 18. DeepLab: Semantic Image Segmentation with Deep Convolutional Nets, Atrous Convolution, and Fully Connected CRFs

### 18.1 第一课时

<video width=80%  controls >
	<source type="video/mp4" src="018-deeplab-v2-semantic-image-segmentation/018-1.mp4">
</video>

任务名称：了解语义分割面临的挑战，掌握DeepLab系列文章的思想。

任务简介：观看视频第一课时，将其中不明白的知识点记录下来，先自行搜索学习。

任务详解：

1. 视频第一课时
   1. 语义分割面临的挑战

      语义分割面临着分辨率、感受域以及多尺度特征这三大挑战，如何找到合适的方法去对应解决这些问题，是分割模型的首要任务之一。要理解三个问题产生的原因，并了解现阶段已知的对应的解决方法。

   2. DeepLab系列简介

      DeepLab系列共有4篇文章，重点掌握v1中空洞卷积的原理及作用，理解v2和v1之间的区别，对于v3和v3+ 有一个大致的概念即可。

论文原文及代码下载链接：https://pan.baidu.com/s/1FHE_LWv93DacZQqdfYbCMQ 

提取码：oe2i 

### 18.2 第二课时

<video width=80%  controls >
	<source type="video/mp4" src="018-deeplab-v2-semantic-image-segmentation/018-2.mp4">
</video>

任务名称：学习阅读论文的方法，进一步了解经典模型的部分细节，从理论掌握模型结构，论文中的技巧。

任务简介：观看视频第二课时，阅读论文

任务详解：

1. 视频
   1. 学习阅读论文的方法

      论文的阅读不是从头到尾，也不是每个部分都一定是非常值得推敲。我们需要掌握练习合适的阅读节奏，在不同的学习阶段，去从论文中汲取不同的东西，将保证我们更有效率地学习，也将保证我们学习的过程更加自然。

   2. 从理论掌握模型结构，论文中的技巧

      模型的掌握不是画出网络图形，然后把公式写出来就算掌握了，那样只能算是对学习知识的复述。需要能真正明白模型的各个部分的所以然。这个部分将从整体到细节讲解模型结构的各个部分，主要思想的动机，与其他经典模型的对比，论文实现过程中使用到的技巧。

2. 阅读论文

   在学习完视频之后再阅读论文，看看自己是不是能了然于胸，对照课程PPT阅读，记录疑问

打卡要求：（形式：文字或者图片，每个问题字数至少50）

1. 回答下列问题：
   1. 怎样理解ASPP模块 ？
   2. 根据FCN模型的搭建基础，自行编写或到GitHub上找到基于Pytorch的ASPP模块代码。