# 入门基础

# 简介

这是一个面向零基础同学的人工智能（AI）与深度学习入门学习路线，适用于没有数学基础、没有编程经验或只是听说过 AI 的同学。

 AI 涉及数学、编程、机器学习理论以及深度学习框架，但每个部分都有大量优质的免费学习资源。与其“为了学习而学习”，不如掌握基础后边做项目边查资料，在实践中逐步补齐知识。

- **难度：⭐⭐⭐**

- **先修基础：无**

# 学习路径

## 数学基础

### 线性代数

学习目标：掌握矩阵运算、向量空间、特征值等概念——理解神经网络计算的核心基础。

教程：

- [b站up一高数的线代视频](https://www.bilibili.com/video/BV1Et421E7jk/?spm_id_from=333.337.search-card.all.click&vd_source=dd0f62b521208f460e8000b7856e0a2b)

资源说明：

 网络资源极其丰富，可根据自身情况在 B 站搜索相关课程（如 3Blue1Brown、MIT 线代，宋浩线性代数），书籍也很多，此处不再赘述。

---

### 微积分

学习目标：掌握导数、梯度、链式法则等内容——反向传播算法的数学核心。

教程：

- [《高等数学》同济版 2024年更新|宋浩老师](https://www.bilibili.com/video/BV1Eb411u7Fw/?spm_id_from=333.337.search-card.all.click&vd_source=dd0f62b521208f460e8000b7856e0a2b)

- [数学分析 陈纪修老师 1080p高清版(全集)](http://bilibili.com/video/BV15v411g7VP/?spm_id_from=333.337.search-card.all.click)

资源说明：高等数学与数学分析课程会详细讲解，可自行在 B 站搜索课程学习，如陈纪修《数学分析》

推荐读物：

- 《普林斯顿微积分读本》

---

### 概率论与数理统计

学习目标：掌握概率分布、贝叶斯定理、最大似然估计等——理解模型输出与不确定性建模的关键。

教程：

- [《概率论与数理统计》教学视频 2.0版本【宋浩老师】](https://www.bilibili.com/video/BV1JXppejE8q/?spm_id_from=333.337.search-card.all.click&vd_source=dd0f62b521208f460e8000b7856e0a2b)

推荐教材：

- 《概率论与数理统计教程》（茆诗松）

---

## 编程基础

### Python

学习目标：能够熟练使用 Python —— AI 行业的通用工作语言。

教程：

- [Python3 菜鸟教程](https://www.runoob.com/python3/python3-tutorial.html)

- [黑马程序员python零基础全套教程](https://www.bilibili.com/video/BV1qW4y1a7fU/?spm_id_from=333.337.search-card.all.click&vd_source=dd0f62b521208f460e8000b7856e0a2b)

推荐书目：

- 《Python编程从入门到实践》（蟒蛇书）

---

### 科学计算库

学习目标：掌握基础数据结构和科学计算能力，为后续机器学习做准备。

- **NumPy**：数组运算、矩阵计算

- **Pandas**：数据分析、数据清洗（准备数据集必备技能）

教程：

- [NumPy 菜鸟教程](https://www.runoob.com/numpy/numpy-tutorial.html)

- [Pandas 菜鸟教程](https://www.runoob.com/pandas/pandas-tutorial.html)

---

## 机器学习与 AI 理论

**前置基础：Python 与数学基础**

### 经典机器学习

学习目标：掌握基本模型与核心概念，包括训练集/测试集、过拟合、损失函数、学习率等。

教程：

- [吴恩达《机器学习》](https://www.bilibili.com/video/BV1owrpYKEtP/?spm_id_from=333.337.search-card.all.click&vd_source=dd0f62b521208f460e8000b7856e0a2b)

- 校内《人工智能》课程（如计算机系开设课程）

---

## 深度学习框架与核心模型

### 主流深度学习框架

学习目标：掌握 PyTorch 或 TensorFlow，从张量操作开始，到搭建与训练神经网络。

- **PyTorch（推荐）**：科研主流

- TensorFlow：工业常见

教程：

- PyTorch：[跟着李沐学ai](https://www.bilibili.com/video/BV1if4y147hS/?spm_id_from=333.1387.collection.video_card.click&vd_source=dd0f62b521208f460e8000b7856e0a2b)

---

### 跑通经典模型

- **CNN**：在 CIFAR-10 上实现图像分类

- **RNN/LSTM**：处理文本生成或时间序列预测

推荐课程：

- B 站「跟李沐学 AI」系列

---

# 进阶

## 深入理解现代模型架构

### Transformer

必须深入掌握：

- 自注意力机制

- 前馈网络

- 残差连接

这是一切大模型（LLM、扩散模型、Vision Transformer 等）的基础。

推荐：

- 论文《Attention Is All You Need》

- 邱锡鹏《神经网络与深度学习》

- 《大规模语言模型》（黄萱菁推荐参考书）

---

## 系统与性能优化

### 操作系统基础

帮助分析训练中的性能瓶颈（CPU、内存、I/O）。

 推荐课程：

- 南京大学蒋炎岩《操作系统》

---

### 并行与分布式训练

学习 torchrun、DeepSpeed、ZeRO 等工具，理解：

- 数据并行

- 模型并行

- 多卡训练

- 多机通信

---

### 计算机网络

理解分布式训练中的通信机制（如 All-Reduce）。

 推荐课程：

- 中科大《计算机网络》

---

# 其他补充

以上内容构成 AI 的基础学习路线。进入课题组后主要根据导师方向深入。除此之外，建议：

- **紧跟社区**：关注 X（Twitter）、知乎、小红书上的顶级研究者和机构

- **阅读并复现论文**：从经典小模型开始

- **加入项目**：形成“问题驱动”的学习循环（实验室 / Kaggle / 开源项目）

- **掌握 Hugging Face**：使用 Trainer API 微调预训练模型

- **培养核心软技能**：
    - 阅读官方文档
    - 熟悉 GitHub
    - 善用大模型（如 ChatGPT）做学习助手

---

# 下一步去哪？

- **自然语言处理（NLP）** —— 了解文本建模和 LLM 的核心

- **计算机视觉（CV）** —— 深入 CNN、ViT 等架构

- **大模型微调** —— LoRA、QLoRA、指令微调

- **AI 工程化** —— 部署、优化、服务化

- **参与开源项目** —— GitHub、Hugging Face Hub



