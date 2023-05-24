# OpenCV图像处理演示程序

## 1 使用说明

下载完成后，解压到当前文件夹

解压完成后双击 OpenCV图像处理演示程序.exe 即可启动软件


## 2 功能实现
本软件实现的功能包含以下：
 - 人物图像处理：包含面部检测、面部打码、眼部检测、眼部打码
 
 - 动态人脸检测：调用本机摄像进行人脸检测
 
 - 图像掩膜处理：实现默认掩模和自定义掩膜
 
 - 图像几何变换：包含缩放变换、旋转变换、镜像变换
 
 - 图像形态变换：形态学腐蚀和膨胀操作，开运算、闭运算、梯度运算、礼帽运算、黑帽运算
 
 - 直方图处理：包括绘制直方图，直方图均衡化和二维直方图
 
 - 图像边缘检测：Laplacian边缘检测、Sobel边缘检测、Canny边缘检测
 
 - 图像轮廓检测：查找轮廓、绘制轮廓轮廓的特征
 
 - 图像分割和融合：距离转换、分水岭算法分割图像、金字塔融合
 
 - 图像特征检测：角检测和关键点检测
 
 - 图像特征匹配：暴力匹配和FLANN匹配
 
 - 图像模板匹配：单目标匹配和多目标匹配
 


## 3 软件涉及库以及库版本

本软件开发基于python3.9和pyqt5，涉及图像处理部分逻辑基于opencv-python库。

所需安装库和版本如下：

```
altgraph                  0.17.3
contourpy                 1.0.7
cycler                    0.11.0
fonttools                 4.39.3
importlib-resources       5.12.0
kiwisolver                1.4.4
matplotlib                3.7.1
numpy                     1.24.2
opencv-python             3.4.15.55
packaging                 23.1
pefile                    2023.2.7
Pillow                    9.5.0
pip                       23.1.2
pyinstaller               5.10.1
pyinstaller-hooks-contrib 2023.2
pyparsing                 3.0.9
PyQt5                     5.15.4
PyQt5-Qt5                 5.15.2
PyQt5-sip                 12.12.0
PyQt5-stubs               5.15.6.0
python-dateutil           2.8.2
pywin32-ctypes            0.2.0
qimage2ndarray            1.10.0
setuptools                65.5.1
six                       1.16.0
wheel                     0.38.4
zipp                      3.15.0

```



## 4 开源声明

本软件已开源，如需进行二次开发可使用GitHub下载源代码进行二次开发。

## 5 软件部分使用截图

1.主界面：

![image](https://github.com/oceanzhou94/OpenCV-Python-Process/assets/80324503/4cec1cf2-823e-4114-a302-c852fc5baea0)

2.人物图像打码界面：

![image](https://github.com/oceanzhou94/OpenCV-Python-Process/assets/80324503/43ab8580-09c8-48f8-94fb-9c9609eab2ce)

3.动态人脸检测界面：

![image](https://github.com/oceanzhou94/OpenCV-Python-Process/assets/80324503/f022c857-6196-40b7-aec1-81abc19b42b4)

4.图像轮廓检测界面

![image](https://github.com/oceanzhou94/OpenCV-Python-Process/assets/80324503/ba3b8c4a-e495-4736-85e9-fe141e095093)

5.图像特征匹配界面：

![image](https://github.com/oceanzhou94/OpenCV-Python-Process/assets/80324503/d795f3b5-a7cb-489a-a6c0-3a3acc157a81)



## 6 联系作者

作者联系方式：邮箱：oceanzhou163@gmail.com

祝愿各位使用本软件愉快。
