## 6. Focal Loss for Dense Object Detection

### 6.1 第一课时

<video width=80%  controls >
	<source type="video/mp4" src="006-focal-loss-for-dense-object-detection/006-1.mp4">
</video>

**任务名称:**完全理解Focal Loss和RetinaNet, 包括其要解决的问题和相关前置知识点.

**任务详解:**

1. 相关知识点包括: 两阶段目标检测器(RCNN系列, 重点讲解Faster R-CNN)和单阶段目标检测器(YOLO和SSD, 重点讲解SSD).

2. 背景知识包括: FPN, FCN, 交叉熵和平衡交叉熵.

3. 关于Focal Loss, 首先学习其要解决的问题: 候选框样本分类难易程度不同导致模型被大量容易分类的负样本控制. 然后学习如何从传统交叉熵损失函数一步步发展到Focal Loss, 其中还要学习平衡交叉熵损失函数. 最后讲解作者如何同时使用平衡交叉熵和Focal Loss, 从两个角度彻底解决模型被负样本控制的问题.

4. 关于RetinaNet, 首选学习其整个网络结构框架, 然后带领大家过一遍一张图进入网络到最后输出结果的整个流程.

5. 实验是本篇论文的重点内容, 文章中每一张图片, 每一个表格背后都是作者大量实验工作的成果. 所以需要带领学员梳理总结一下文章中所有的实验, 并对图片和表格进行讲解, 使学员理解其含义. 

**学习要求:**

首先需要同学们提前通读论文作为预习, 对文章中内容有个大概的理解. 并且标注出没看懂的内容, 以便于后续回顾. 然后通过观看视频, 掌握相关知识点和背景知识点, 如果还有疑惑. 可以咨询老师或者查阅资料. 接着重点关注Focal Loss提出流程和RetinaNet的架构. 思考作者做每一个实验的目的. 最后回去查看标注不明白的内容, 看是否在视频中有讲解. 如果没有, 咨询老师或者查阅资料.

**论文原文及代码下载链接：**

链接：https://pan.baidu.com/s/1sFIP363lz1p7MD9LlQJpSQ 

提取码：2kqs 

**打卡要求:**

1. 思考题
   1. 为什么单阶段目标检测器在精度上不如两阶段目标检测器?
   2. 为什么两阶段目标检测器速度要慢于单阶段目标检测器?
   3. 作者通过哪两种方法, 从哪两个角度解决了问题1?
   4. 请简述一下论文中图1和图4要表达的内容.
   5. 同样是提取不同尺度的特征图, 为什么RetinaNet中的FPN比SSD中使用的方法效果好?
   6. RetinaNet是否要求输入图片的尺寸大小必须一致?

2. 代码实践
   1. 请在Focal Loss.py文件中, 给15-29每一行代码添加注释说明这行代码实现了什么功能.

3. 总结

1. 对今天学过的内容进行总结, 写一份博客笔记. 打卡提交截图或者博客链接.