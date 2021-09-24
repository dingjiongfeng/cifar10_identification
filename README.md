# cifar10_identification
作业，简单的卷积神经网络
对cifar10数据集进行识别。
## 数据集介绍
cifar10数据集是一个用于识别普适物体的小型数据集。一共包含 10 个类别的 RGB 彩色图 片：飞机（ a叩lane ）、汽车（ automobile ）、鸟类（ bird ）、猫（ cat ）、鹿（ deer ）、狗（ dog ）、蛙类（ frog ）、马（ horse ）、船（ ship ）和卡车（ truck ）。图片的尺寸为 32×32 ，数据集中一共有 50000 张训练圄片和 10000 张测试图片。 CIFAR-10 的图片样例如图所示。

<img src="https://img-blog.csdnimg.cn/20190423164653119.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L21hb19odWlfZmVp,size_16,color_FFFFFF,t_70">

[原文链接](https://blog.csdn.net/mao_hui_fei/article/details/89477938)

## 项目介绍
使用torch框架构建卷积神经网络，使用torchvision进行图像处理和cifar数据集下载。
需要的模块版本
|模块名称|版本号
|----|----
|torch  |-1.0.1
|torchvision |-0.4.0+cpu
|tqdm |-4.32.1
|numpy|-1.16.6
|matplotlib|-3.1.1

- 本文使用的网络为两个卷积层，三个全连接层的神经网络，激活函数为ReLU，最后对不同的学习率对神经网络是否收敛的影响，以及收敛的快慢进行实验。
