## 8. YOLOv3: An Incremental Improvement

### 8.1 第一课时

<video width=80%  controls >
	<source type="video/mp4" src="008-yolov-an-incremental-improvement/008-1.mp4">
</video>

**任务名称：**了解yolov3改进的几个方面，掌握yolov3坐标计算方式。

**任务简介：**通读paper观看导读视频。

**任务详解:** 

第一部分：yolov2和yolo9000的简介。yolov2是对yolov1的改进，yolov3是在yolov2的基础上进一步改进。Yolov2借鉴了锚框的思想，设计了新的网络结构darknet-19,训练方式也发生了改变。     

第二部分：yolov3论文内容结构主要讲解yolov3论文每个部分主要讲了哪些内容。方便同学们课下自己阅读时，对论文的有大概认识，这样也比较容易理解。

第三部分：yolov3的主要改进的个方面。包括loss改进，设计新网络结构darknet-53以及多尺度预测几个方面。

第四部分：yolov3结果分析。对比了yolov3和其他算法的性能，然后对比了backbone也就是主干网络的性能。

**论文原文及代码下载链接：**

链接：https://pan.baidu.com/s/1b2rQc9qgQxjtEOC9hXxYHQ 

提取码：iow7 

**打卡要求：**文字打卡不少于20字

1. 预习YOLOv3论文内容

2. YOLOv1--›YOLOv2--›YOLOv3改进的部分描述Map两种计算方式

3. YOLOv3坐标计算公式

### 8.2 第二课时

<video width=80%  controls >
	<source type="video/mp4" src="008-yolov-an-incremental-improvement/008-2.mp4">
</video>

**任务名称：**掌握yolov3每部分损失如何计算的，了解darknent-53网络结构 。

**任务简介：**观看论文详解视频

**任务详解：**

本节课主要包含三部分内容。

第一部分，是yolov3先验框产生的方法。Yolov3使用k-means++算法产生聚类中心框。一般是9个聚类框，每个尺度分配三个框。

第二部分，网络结构darknent53的具体结构。

第三部分，详细介绍yolov3损失函数。

**打卡要求：**

1. 先验框是如何得来的 （不少于20字）

2. groud truth乘以的尺度是多少（16页）

3. 写出yolov3的损失函数 

### 8.3 第三课时

<video width=80%  controls >
	<source type="video/mp4" src="008-yolov-an-incremental-improvement/008-2.mp4">
</video>

**任务名称：**掌握如何生成训练数据的代码，图像等比变化代码，理解损失函数代码。

**任务简介：**观看代码详解视频

**任务详解：**本节课主要内容包括了三部分。第一部分内容是代码总体的介绍，介绍一下代码的构成以及重要代码的主要功能。第二部分就是介绍一下如何跑通一个demo。最后一部分就是讲解比较重要的代码。主要是聚类，图像数据处理以及loss的重点代码部分。

**打卡要求：**

1. 跑通检测测试程序（无gpu）尝试描述测试代码的逻辑（测试结果图一张，文字不少于20）

2. 训练yolov3(有gpu) 给出训练曲线图片一张

3. label的数据结构是怎么样的（简单描述即可）