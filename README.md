# RBPN
这个是发表在2019年的论文 Recurrent Back-Projection Network for Video Super-Resolution，我加载该网络模型参数对视频帧进行预测。

environment：
pytorch:1.8.0
cuda:cu101

我加载的是Vid4/foliage数据进行的预测。我也尝试了自己的图片输入进去，进行预测这也是可以的。

这是最后的效果，分别是输入图片，输出图片，GT，如下图

![image](https://user-images.githubusercontent.com/31944875/112632755-81808980-8e73-11eb-9244-27a95938d5cf.png)


*上传到github上，主要是为了给自己备份，可读性不是很强。

*在代码中有一个so动态库，需要自己编译或者自己上传到colab中去也可，但是谨记千万不能改名字，改了名字import就会出错（我在这里出了很久的错）
