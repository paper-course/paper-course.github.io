## 3. Very Deep Convolutional Networks for Large-Scale Image Recognition

### 3.1 第一课时

<video width=80%  controls >
	<source type="video/mp4" src="003-very-deep-convolutional-networks-for-large-scale-image-recognition/003-1.mp4">
</video>

任务名称：了解论文研究背景成果及意义。

任务简介：通读paper，观看导读视频。

任务详解:  

本次导读内容包含论文研究背景、成果，论文研究方法，论文结论，感受野四个部分。第一部分，论文研究背景成果主要简单介绍vgg的研究背景和取得的成果。论文研究方法部分主要讲述作者如何做对比试验来找到best model。最后一个部分为感受野的讲解，主要讲解了感受野的概念及计算公式。这部分需要大家重点掌握。

论文原文下载：

链接：https://pan.baidu.com/s/1pS9bxV8QNjHJl3o5M4NioA 

提取码：6ltq 

打卡要求：（形式：文字，字数至少100）按照自己的理解总结视频中三个知识点（最好分点清晰，有树状的层次结构，必要时推导公式），至少提出2个疑问。



### 3.2 第二课时

<video width=80%  controls >
	<source type="video/mp4" src="003-very-deep-convolutional-networks-for-large-scale-image-recognition/003-2.mp4">
</video>

任务简介：掌握vgg16,vgg19的网络结构及训练数据的处理方法，观看论文详解视频

任务详解：本节课主要包括五个部分，第一部分为上节内容回顾。简单回顾上节课所讲的主要内容。第二部分为论文整体框架，这部分内容呢介绍了vgg这篇paper的整体架构及重点内容，第三部分网络结构及权重参数计算，详细讲解了vgg16的网络结构，及网络每层的参数量。第四部分网络超参数及训练数据处理，重点讲解了训练数据的处理，并且给出了老师自己及写的数据处理代码来帮助同学理解处理过程，然后简单介绍了网络的超参数设置。第五部分网络特点，总结了vgg网络的一些特点。 

需要同学们熟悉vgg16,vgg19网络结构。掌握数据处理的技巧。    

注意：因tensorflow升级改动较大，请大家看1.9版本的tensrflow的ap

打卡要求：

1. 使用 tensorboard 可视化Vgg16网络结构(图片一张）

2. 计算Vgg16理论感受野(可以拍一张图片，写纸上或者电子文档都可)

3. 调研使用张量形式如何对训练数据进行处理（查看tensorflow相关api）



### 3.3 第三课时

<video width=80%  controls >
	<source type="video/mp4" src="003-very-deep-convolutional-networks-for-large-scale-image-recognition/003-3.mp4">
</video>

任务名称：掌握网络定义的代码，掌握使用tensorflow api来处理图像数据。

任务简介：观看代码精读视频

任务详解：

本次课程一共包含了5部分，第一部分为上节内容回顾主要复习一下上节重点内容，第二部为微调概念的讲解，第三部分为重点代码讲解，主要讲解数据处理流程，及vgg19网络结构的搭建。第四部分为优化方法的讲解。主要包括SGD,ADAM优化方法。第五部分为讨论和总结。讨论vgg与alxnet的区别。

打卡要求：

1. 自己找一个熟悉框架的vgg跑通或者使用老师给的代码调通。（图片一张）

2. 使用vgg完成一个分类任务并测试框架不限。（比如猫狗分类，花卉分类等，直接测试训练好的vgg权重也可以）（图片一张）