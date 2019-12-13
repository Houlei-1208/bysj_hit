# bysj_hit 
<br>项目围绕HITHCD手写汉字数据库(即将公开)，对多达21,003类、2,000万份手写汉字样本进行了二值化、随机旋转、亮度调整、霍夫变换、透视校正等多种方案增强，并在此基础上复现了LeNet、VggNet、AlexNet、ResNet、<a href="https://arxiv.org/abs/1805.03438">Convolutional Prototype Learning</a>等多种卷积神经网络，采用<a href="https://arxiv.org/abs/1806.02507">标签映射法</a>、<a href="https://www.computer.org/csdl/proceedings-article/icfhr/2016/0981a530/12OmNqJq4qf">笔画编码法</a>、<a href="https://www.computer.org/csdl/proceedings-article/icdar/2017/3586a573/12OmNyGtjef">分级聚类法</a>等改进以适应大类别手写汉字识别问题，最终应用到安卓端。系统具有实时单字检测、手写板汉字识别、作文拍照识别等功能，呈现出识别速度快、准确度高、系统占用小等特色。此外，我们对整个系统进行了完备的功能和性能测试。结果表明，改进后的深度学习模型在性能和准确率上均表现优异。其中，笔画编码法和分级聚类法在牺牲少许精度的前提下，加速的脱机单字识别速度理论上达4-100X，标签映射法提升的准确率超过经典网络最好水平0.5%-2.0%，达到业内领先水平。</br>
##### 2019.12更:非常感谢大家的star~早期项目，当时水平和精力有限，代码没来得及整理，目前暂时停止更新了，抱歉。有需要的朋友，建议先阅读<a href="https://github.com/HuiyanWen/resnet_tensorflow">复现的resnet</a>，该部分注释和代码规范性好一些，是本人参与华为某项目商用的部分开源代码，已上传模型和少量数据。
##### 备注:本项目中，不带后缀的是复现经典CNN代码，如resnet21003，是复现的CNN网络，对21003类手写汉字进行识别。带后缀的，类似resnet21003_149的是改进的部分，和resnet21003_151、resnet21003_157并行进行训练、预测，准确率和速度都有所提高，有疑问可提issue。
##### Convolutional Prototype Learning复现改进:https://github.com/HuiyanWen/CPL
<h3>经典网络复现结果</h3>

![Image text](https://github.com/HuiyanWen/bysj_hit/blob/master/4.png)

<h3>改进结果</h3>

![Image text](https://github.com/HuiyanWen/bysj_hit/blob/master/1.png)

![Image text](https://github.com/HuiyanWen/bysj_hit/blob/master/5.png)

![Image text](https://github.com/HuiyanWen/bysj_hit/blob/master/6.png)



