# CIFAR-10 三层神经网络分类器

## 项目简介
本项目实现了一个从零开始的三层神经网络分类器，用于 CIFAR-10 数据集的图像分类任务。通过自主实现反向传播算法，模型能够有效地对 CIFAR-10 数据集进行分类。

## 环境要求
- Python 3.8+
- NumPy
- Matplotlib
- Keras (仅用于加载 CIFAR-10 数据集)
- scikit-learn

## 文件结构
cifar10-neural-network/
├── cifar10.ipynb    # 主程序代码
├── README.md            # 项目说明
├── loss_curve.png       # 训练和验证损失曲线
├── accuracy_curve.png   # 验证集准确率曲线
└── weight_distribution.png  # 模型参数可视化


## 如何运行
1. **克隆仓库**：
   ```bash
   git clone https://github.com/ch1596/cifar10-neural-network.git
   cd cifar10-neural-network
2. **安装依赖**:
   pip install numpy matplotlib keras scikit-learn
3. **运行代码**:
   jupyter notebook cifar10.ipynb (python)
4. **查看结果**：
   训练和验证损失曲线保存在 loss_curve.png。
   验证集准确率曲线保存在 accuracy_curve.png。
   模型参数可视化保存在 weight_distribution.png。
   测试集准确率打印在终端。

## 实验结果
## 最佳超参数：
隐藏层大小：512
学习率：0.01
L2 正则化强度：0.001
测试准确率：52.32%

## 模型权重下载
训练好的模型权重已上传到 Google Drive：
https://drive.google.com/file/d/1NodCLd6KJEepC013nrOEPSPt-e8BOUKH/view?usp=sharing

## 项目说明
本项目实现了以下功能：
三层神经网络分类器
自主实现反向传播算法
超参数搜索
模型训练和测试
可视化训练过程中的损失和准确率
模型参数可视化

## 致谢
感谢 Keras 提供的 CIFAR-10 数据集加载功能。


