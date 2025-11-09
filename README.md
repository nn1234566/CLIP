# CLIP Image-Text Retrieval System

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/你的用户名/clip-image-text-retrieval/blob/main/clip_retrieval.py)

一个基于OpenAI CLIP模型的多模态检索系统，实现文本到图像和图像到文本的双向检索。

## 🚀 项目亮点

- **双向检索**: 支持“以文搜图”和“以图搜文”
- **零样本学习**: 无需额外训练，直接利用CLIP预训练模型
- **即开即用**: 提供Google Colab一键运行环境
- **效果直观**: 完整的可视化结果输出

## 📸 效果展示

**查询文本：** `"a cute pet"`

![检索结果](https://via.placeholder.com/600x300/ADD8E6/000000?text=在此处上传你的结果截图)
*模型成功地从图片库中精准检索到最相关的图像，Top-1置信度达84.8%*

## 🛠 快速开始

### 安装依赖
```bash
pip install -r requirements.txt
