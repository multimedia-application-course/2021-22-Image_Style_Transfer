# 项目名称：图像风格迁移
本项目基于人工智能领域中的机器学习知识，利用卷积神经网络实现图像风格迁移。

### 目标
风格图像迁移分为风格图像迁移和快速风格图像迁移。快速风格图像迁移则是利用两个网络框架，一是VGGNet(我们用的是VGG19),另一个是图像风格生成网络Transformer Net,对一个数据集进行训练得到模型，再利用训练好的模型以及图像风格迁移网络再进行一次计算就可以生成图像，因此速度会比原始图像风格迁移快得多。我们的目标是通过快速风格图像迁移，把图像从原风格转换到另外一个风格, 同时保证图像内容没有变化。项目使用VGG19对数据训练好的模型，研究对给定图片进行风格迁移的操作，并对相关算法进行一些接触和探讨。
  
### 项目简介
编程语言：
Python3

相关工具：
IDE:pycharm

外部函数库：
numpy，
matplotlib，
pillow，
Pandas

技术框架：
卷积神经网络 VGG-19

### 部分迁移效果
![图片](https://user-images.githubusercontent.com/83445004/123511460-0e75f180-d6b4-11eb-8e61-0de6bfbd9236.png)
![图片](https://user-images.githubusercontent.com/83445004/123511484-22215800-d6b4-11eb-8056-4ba5bdea32a7.png)
![图片](https://user-images.githubusercontent.com/83445004/123511527-56951400-d6b4-11eb-8de9-e456d3de99d6.png)
