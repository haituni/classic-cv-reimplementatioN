# classic-cv-reimplementation

本项目系统性地复现了四大经典卷积神经网络（CNN）骨干模型——**AlexNet、VGG、ResNet 和 InceptionNet**，并在 CIFAR-10 数据集上进行统一的图像分类实验。通过公平的训练与评估流程，深入对比它们的性能表现、模型复杂度与核心设计思想。所有代码均基于 PyTorch 实现，结构清晰、注释详尽，非常适合学习与教学。

## 💡 项目目标

- **理解演进脉络**：从开创性的 AlexNet 出发，到 VGG 的深度探索、Inception 的高效模块化设计，再到 ResNet 的革命性残差连接，完整呈现经典 CNN 架构的发展历程。
- **掌握核心机制**：深入剖析每个模型的关键创新点，如 AlexNet 的 ReLU 与 Dropout、VGG 的小卷积核堆叠、Inception 模块的多尺度并行、以及 ResNet 的恒等映射。
- **实践公平比较**：在统一的数据集（CIFAR-10）、数据预处理、优化器和训练策略下，对各模型的准确率、参数量和计算效率进行客观对比。
- **提供可复现代码**：提供模块化、易于理解的 PyTorch 实现，方便学习者快速上手、修改和扩展。

## 📦 当前已实现模型

- **AlexNet**：深度学习时代的奠基之作，引入了 ReLU 激活函数、Dropout 正则化和数据增强等关键技术。
- **VGG**：以其简洁而深度的架构闻名，展示了小尺寸卷积核（3×3）堆叠的有效性。
- **ResNet**：通过残差连接解决了深度网络的退化问题，使得训练极深的网络成为可能。
- **InceptionNet (GoogLeNet)**：采用 Inception 模块，在不显著增加计算成本的前提下，提升了网络的宽度和性能。

## 🚀 快速开始

1. 克隆本仓库：
   ```bash
   git clone https://github.com/haituni/classic-cv-reimplementation.git
   cd classic-cv-reimplementation
