# 课程大作业4-说明

## 组织方式与要求

1-2人一组； 

* 时间要求

发布时间：XX月XX日（校历第7周）

截止日期：XX月XX日（校历第11周周末）课上验收，提交报告和完整代码（校历第12周周末）


## 内容描述

###  数据集 

24句语音指令的语音时频谱数据集(spectrogram dataset)，语音数据集中包括：

40个人（/100人）的人声语料数据集，20个人的人声验证数据集。 

时频谱图数据集：https://cloud.tsinghua.edu.cn/f/a4cf25f158674baf88f7/

测试数据集：https://cloud.tsinghua.edu.cn/f/bc80ac081ebf4c13befa/

请同学们拷贝这个数据集即可。

### 任务描述

根据时频谱图数据对语音指令进行分类。在输出的时频谱图数据集上，通过设计深度神经网络模型，得出预测结果。 

** 深度学习解决时频谱图分类的几种参考方案**

（1）参考分类过程1，参考链接：https://tensorflow.google.cn/tutorials/images/classification （较方便，推荐。）

（2）参考分类过程2，也可以参考链接：https://tensorflow.google.cn/tutorials/load_data/images  （你还掌握了制作tf.data数据集过程！）

（3）背景补充：（谷歌simpleAudio）项目链接：https://tensorflow.google.cn/tutorials/audio/simple_audio
（谷歌TensorFlow官方提供的一个详细从语音文件（*.wav）到时频图（spectrogram），再进行分类的案例。）（你还掌握了从波形文件到时频谱图的制作过程！）

* 提示：

可能需要数据增强，进行resize标准大小等方法，来解决过拟合问题，参考链接：https://tensorflow.google.cn/tutorials/images/data_augmentation

网络模型参考一下audioNet项目。项目网页链接：https://github.com/saturn-lab/audioNet 



## 作业提交与评分

- 实验代码验收 (可成功运行的notebook文件)
- 实验报告 1 份（列出你的创新点和工作内容，以及对结果的分析）


** 评分标准

第10周课上检查，每位同学找老师验收，验收主要看代码运行和训练过程，并会记录代码运行得到的测试集accuracy指标。

验收完成则本次作业合格；根据实验报告和模型准确度可获得额外加分。

## 补充说明

原始语音数据集，网页链接：https://cloud.tsinghua.edu.cn/f/a4cf25f158674baf88f7/

audioPlot项目生成时频谱图。项目网页链接： https://github.com/saturn-lab/audioPlot
