# Wear_mask

一个基于自制数据集与百度EasyDL训练的佩戴口罩识别项目

# 数据

> 因为Github上传超过100MB的大数据集比较麻烦，所以为大家提供了百度网盘下载

> 数据包括两个：带标签的数据集和不带标签的数据集，其中数据完全一样；只是带标签可以用于更广泛的学习。

- 不带标签的数据集：https://pan.baidu.com/s/11T_VEplm-lCQMaBsx6r1pA （提取码：q2e8）
- 带标签的数据集：链接：https://pan.baidu.com/s/11IEkdqMOR_e7fmv85Vr6TQ （提取码：mxhg ）

# 关于数据


本数据集一共1165张图像，其中戴口罩类514张，没戴口罩类651张。戴口罩类的图像都是B站视频里截图下来的，没戴口罩类的图像是`CASIA-FaceV5`、`WIDER_FACE`、`VOC2007`各数据集拼凑而成。

![](https://github.com/WangRongsheng/Wear_mask/blob/master/img/dataset.png)

其中`image_mask`文件夹图像对应`label_mask`文件夹标签
`image_nomask`文件夹图像对应`label_nomask`文件夹标签

# 训练实用

我采用的是百度的`EasyDL`平台进行图像学习识别。[百度EasyDL平台](https://ai.baidu.com/easydl/)

![](https://github.com/WangRongsheng/Wear_mask/blob/master/img/pingtai.png)



