# NASA-Clouds-CV
## Using technology of computer vision to classify clouds.
### 【主要研究内容】
  本实验主要研究内容包括：数字图像处理方法对于Opencv 包和albumentations包应用和探索以及从传统神经网络跨越到用于图像分割深度网络模型的个人学习。本实验关注的核心是视觉领域图像分割问题的U-Net架构，从U-Net论文理论性内容迁移到实际实验过程中，完成论文学习和理解的闭环学习。此外，对深度学习领域中，广泛使用的EfficientNet-b4预训练模型的迁移学习和参数微调的方法进行实验。
  
### 【实验过程与结果】
  实验过程包含四个阶段（其中两次为不成功尝试）。传统卷积神经网络到 YoLov4 预训练模型，最后使用了基于 EfficientNet 预训练模型的 Encoder 的 U-Net 架构。并且通过实验了解了数字图像预处理的 Opencv 包和 albumentations 包。
  阶段一：直接使用卷积神经网络进行图像特征提取并进行像素位置预测；
  阶段二：使用 YoLov4 预训练模型用目标检测的算法进行图像分类检测；
  阶段三：使用 U-Net 架构通过使用 EfficientNet-b4 的预训练模型进行迁移学习和参数微调；
  阶段四：进行图像处理（包括：图像翻转、放射变换、线性插值、非刚体转换、亮度调整、尺寸裁剪、颜色空间转换等）进行数据增广，使用上阶段
baseline 进行图像分割。
  **Dice 系数从阶段一：0.22 到阶段四：0.52，总体提升：136%。**

### 【实验环境】
![image](https://user-images.githubusercontent.com/84648756/169022428-ffbab6c8-3c60-47bd-ac6c-4590f43b8eb0.png)

### 【实验结果】
![image](https://user-images.githubusercontent.com/84648756/169022539-1def4ce6-b093-4019-a1ff-224c69140f58.png)
![image](https://user-images.githubusercontent.com/84648756/169022605-818a8659-7417-4cc8-b54c-9e4826f3e581.png)


