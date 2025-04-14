# 📘 Hands-on Graph Neural Networks with PyTorch Geometric

欢迎来到本仓库！这是一个**图神经网络（GNN）入门学习项目**，基于 [PyTorch Geometric (PyG)](https://github.com/pyg-team/pytorch_geometric)，  
涵盖了从节点分类到图分类，再到大规模图的 GNN 训练方法，适合初学者动手实践与理解核心原理。

---

## 📚 教程结构

本教程共包含三大部分，每部分配有注释清晰的代码与详细的中文讲解。

### 1. [节点分类任务](./node_classification)
- 使用 KarateClub 与 Cora 数据集
- 构建 MLP 与 GCN 模型
- 比较无结构模型与结构化 GNN 的性能差异
- 可视化节点嵌入（t-SNE）

### 2. [图分类任务](./graph_classification)
- 使用 MUTAG 分子图数据集
- 掌握图的 mini-batch 构建方式
- 使用 GCN + 全局池化（Global Mean Pool）完成图级预测
- 实现 GraphConv 替代 GCNConv 提升性能

### 3. [大规模图上的 GNN 训练](./scalable_gnn)
- 使用 PubMed 数据集
- 介绍 Cluster-GCN 子图划分方法
- 使用 ClusterData + ClusterLoader 实现可扩展训练
- 保持网络结构不变，优化数据加载方式

---

## 🧠 使用到的核心技术

- GCN（Graph Convolutional Network）
- MLP（多层感知机）对照实验
- GraphConv（无归一化版本）
- Readout Layer（图嵌入聚合）
- Cluster-GCN 子图划分
- PyG Dataset & Loader 工具使用技巧
- 可视化（matplotlib + sklearn t-SNE）

---

### 环境安装
```bash
pip install torch torchvision torchaudio
pip install torch-geometric
