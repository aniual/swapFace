# Swap-Face

# 使用方法
Training and test code are now available!
[ <a href="https://github.com/aniual/simSwapeFace/blob/main/%E6%AC%A2%E8%BF%8E%E4%BD%BF%E7%94%A8_Colaboratory.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="google colab logo"></a> ]
## 下载模型
&emsp;&emsp;模型下载地址参见`pretrained_models`文件夹中的txt文档，主要包括的模型如下：<br />
&emsp;&emsp;```encoder.pt``` -- 含位姿编码器<br />
&emsp;&emsp;```encoder_without_pos.pt``` -- 去位姿编码器<br />
&emsp;&emsp;```projector_EastAsian.pt``` -- 东亚模特投射器<br />
&emsp;&emsp;```projector_WestEuropean.pt``` -- 西欧模特投射器<br />
&emsp;&emsp;```projector_NorthAfrican.pt``` -- 北非模特投射器（比较特殊转线下了，可自行训练或私联我）<br />
&emsp;&emsp;```shape_predictor_68_face_landmarks.dat``` -- 人脸检测<br />
&emsp;&emsp;```79999_iter.pth``` -- 人脸mask分割<br />


## 运行代码
&emsp;&emsp;将图片放在input文件夹下，然后编辑scripts/inference.py的路径，运行如下代码：<br />
&emsp;&emsp;```python scripts/inference.py```<br />
&emsp;&emsp;结果会保存在output文件夹下<br /><br />