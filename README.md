# 动手学深度学习 | Dive into Deep Learning (PyTorch)

> 基于《[动手学深度学习](https://zh-v2.d2l.ai/)》（D2L）的个人学习笔记、Colab 实验和 PyTorch 代码。

## 学习目标

- 掌握张量运算、自动微分、机器学习与深度学习的基础概念；
- 在 **Google Colab + PyTorch** 中动手运行和修改代码；
- 对模型、训练过程和实验结果进行记录，并用 GitHub 管理版本。

## 学习进度

- [ ] **预备知识**（当前学习中：`ndarray.ipynb`）
- [ ] 线性神经网络
- [ ] 多层感知机
- [ ] 深度学习计算
- [ ] 卷积神经网络
- [ ] 现代卷积神经网络
- [ ] 循环神经网络
- [ ] 现代循环神经网络
- [ ] 注意力机制
- [ ] 优化算法
- [ ] 计算性能
- [ ] 计算机视觉
- [ ] 自然语言处理（预训练）
- [ ] 自然语言处理（应用）

## 目录结构

章节目录名沿用 D2L 官方 PyTorch Colab 仓库，便于查找和保存 Notebook。

```text
d2l-pytorch-learning/
├── README.md
├── .gitignore
├── chapter_preliminaries/
├── chapter_linear-networks/
├── chapter_multilayer-perceptrons/
├── chapter_deep-learning-computation/
├── chapter_convolutional-neural-networks/
├── chapter_convolutional-modern/
├── chapter_recurrent-neural-networks/
├── chapter_recurrent-modern/
├── chapter_attention-mechanisms/
├── chapter_optimization/
├── chapter_computational-performance/
├── chapter_computer-vision/
├── chapter_natural-language-processing-pretraining/
├── chapter_natural-language-processing-applications/
├── notes/
└── experiments/
```

## Google Colab 工作流

1. 从 [D2L 中文在线教材](https://zh-v2.d2l.ai/) 打开对应的官方 Colab Notebook，或从本仓库的 GitHub 文件中打开自己之前保存的 Notebook。
2. 在 Colab 中运行代码、修改示例、完成练习；建议附上自己的 Markdown 理解和实验结论。
3. 点击 Colab 菜单 **文件 → 在 GitHub 中保存副本**。
4. 选择 `Misaya2314/d2l-pytorch-learning`，分支选择 `main`。
5. 文件路径填写与章节对应的相对路径，例如：**`chapter_preliminaries/ndarray.ipynb`**。
6. 提交信息填写具体学习内容，例如 `Study tensor indexing and broadcasting`，然后确认提交。
7. 以后继续学习时，从自己的 GitHub 版本重新打开，保存新版本即可保留 Git 历史。

> **注意**：Colab 不会自动把尚未提交的代码同步到 GitHub。Notebook 的输出单元可随 `.ipynb` 保存，但运行环境中的数据集、模型权重和临时文件不会自动保存到仓库。

## 实验与笔记

- `notes/`：个人知识点总结、易错点与复习计划。
- `experiments/`：跨章节的独立实验与小项目。
- 单章代码和练习优先保存到对应 `chapter_*/` 目录，避免按日期散落。
- 大型数据集、模型权重（`.pth`、`.pt`、`.ckpt`）建议放在 Google Drive 或其他专门存储中，而不是普通 Git 提交。

## 参考资源

- [动手学深度学习（中文）](https://zh-v2.d2l.ai/)
- [D2L 官方 PyTorch Colab Notebooks](https://github.com/d2l-ai/d2l-zh-pytorch-colab)
- [PyTorch 官方文档](https://pytorch.org/docs/stable/index.html)
- [Google Colab](https://colab.research.google.com/)

## 版权与说明

本仓库用于个人学习。教材内容与官方示例归其原作者及对应开源许可证所有；此处保留来源链接，个人笔记与自主实验将逐步补充。引用或改编官方代码时请遵循相应许可及署名要求。
