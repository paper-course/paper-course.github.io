## 7. You Only Look Once: Unified, Real-Time Object Detection

### 7.1 第一课时

<video width=80%  controls >
	<source type="video/mp4" src="007-you-only-look-once/007-1.mp4">
</video>

任务名称：了解yolo优缺点，掌握map概念及计算方式。

任务简介：通读paper，观看导读视频。

任务详解:  

本节课包含四个部分。

第一部分内容是论文的整体结构，介绍论文的每个章节结构以及每个部分具体讲了哪些内容，让大家对论文有个整体的认识。

第二部分内容是yolo优缺点。简单的描述下yolo算法有哪些优点以及它的缺点是什么，优点是速度快，利用全图信息背景无检测率低，可以学习到物体通用特征泛化能力强。缺点是最先进的算法比精度不高并且对小目标不友好。

第三部分内容yolo结果分析。分析了yolo与其他算法比较它的速度以及平均准确率的情况。具体从数据上说明各种算法的优劣 。

第四部分目标检测评价指标主要就是介绍了平均准确率在目标检测中具体是怎么计算的。这部分需要大家重点掌握。

论文原文下载：

链接：https://pan.baidu.com/s/1EsH9xUTNXcjtlvCtG78tTg 

提取码：xe5e 

中文版参考地址：https://blog.csdn.net/woduoxiangfeiya/article/details/80866155

打卡要求：文字打卡不少于20字

1. 论文中yolo包含几层卷积层, 几层全连接层。

2. Yolo优点及缺点

3. 描述Map两种计算方式

### 7.2 第二课时

<video width=80%  controls >
	<source type="video/mp4" src="007-you-only-look-once/007-2.mp4">
</video>

任务名称：掌握yolo算法思想，掌握损失函数，理解yolo训练流程。

任务简介：观看论文详解视频

任务详解：

本节课主要包含四部分内容。

第一部分是yolo算法的思想，需要重点掌握

1. yolo将图片隐式的分为S*S个网格

2. 物体的中心落在哪个网格内，哪个网格就负责预测这个物体

3. 然后我们分的S*S个网格，每个网格需要预测B个框，C个类别

4. 然后预测的B个框，每个框包含了位置信息和置信度 (x, y, w, h, confidence) 就是框的中心点坐标宽高以及置信度。最后结合具体这4点详细解释了算法的一些细节。

第二部分网络结构细节，就是yolo具体网络的学习。给出了网络每层卷积核的尺寸以及每层特征图的尺寸。

第三部分损失函数分析，主要来分析一下损失函数设计的细节问题，包含几个部分，每个部分是什么等内容。并介绍作者设计损失函数的一些思想。需要大家掌握。

第四部分是网络训练，介绍了yolo的预训练过程和训练过程以及作者超参数的设置。了解即可。

打卡要求：

1. yolo算法思想（不少于20字）

2. 写出yolo损失函数，以及作者设计loss考虑到的一些问题（不少于20字）

3. 写出yolo训练的流程（不少于20字）

### 7.3 第三课时

<video width=80%  controls >
	<source type="video/mp4" src="007-you-only-look-once/007-3.mp4">
</video>

任务名称：掌握如何生成训练数据的代码，网络如何定义，理解损失函数代码。

任务简介：观看代码详解视频

任务详解：

第一部分回顾上一节课主要讲解的内容。第二部分介绍一下代码的结构。第三部分介绍voc的标注格式,需要大家熟悉。之后就是重点代码解析，主要讲解label是如何生成，网络结构以及loss部分的代码，这部分需要好好理解。最后对论文做个总结。

代码链接：https://pan.baidu.com/s/1o7YMiwp_ifDlPe5-kjRb_w 

提取码：r68j 

课外推荐资料，学有余力的同学可以看看：https://docs.google.com/presentation/d/1aeRvtKG21KHdD5lg6Hgyhx5rPq_ZOsGjG5rJ1HP7BbA/pub?start=false&loop=false&delayms=3000&slide=id.g137784ab86_4_484

打卡要求：

1. 跑通检测测试程序（无gpu）描述测试代码的逻辑（测试结果图一张，文字不少于20）

2. 训练yolo（有gpu） 给出训练曲线图片一张

3. label的数据结构是怎么样的（简单描述即可）