![GitHub last commit](https://img.shields.io/github/last-commit/McKlay/cnn-companion-book)
![GitHub Repo stars](https://img.shields.io/github/stars/McKlay/cnn-companion-book?style=social)
![GitHub forks](https://img.shields.io/github/forks/McKlay/cnn-companion-book?style=social)
![MIT License](https://img.shields.io/github/license/McKlay/cnn-companion-book)

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=McKlay.cnn-companion-book)

# CNN Companion Book

> *"From Pixels to Patterns — a deep, code-first journey into Convolutional Neural Networks for real-world computer vision."*  

**Live Site**: [https://mcklay.github.io/cnn-companion-book/](https://mcklay.github.io/cnn-companion-book/)  
Author: [Clay Mark Sarte](https://github.com/McKlay)  
Built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) | Powered by [PyTorch](https://pytorch.org) & [TensorFlow](https://www.tensorflow.org)

---

## What This Is

This repository contains a structured, book-style deep learning guide focused entirely on **Convolutional Neural Networks (CNNs)** for real-world computer vision. It is written in a modular, educational format tailored for **developers, ML engineers, students, and builders** who want to master CNNs through **hands-on coding using both PyTorch and TensorFlow**.

Whether you're training a CNN from scratch or deploying a fine-tuned model in production, this companion book bridges **core theory, practical implementation, and deployment-readiness**—all in one place.

---

## Table of Contents

- `Part I – Foundations of Image Tensors and Preprocessing`  
  How CNNs interpret images, data formats ([H, W, C] vs [C, H, W]), RGB → Tensor pipelines, and input shape walkthroughs.

- `Part II – Preprocessing and Input Pipelines`  
  Resize, Normalize, Augment, tf.image vs torchvision.transforms, image folders, batching, and preprocessing alignment with pretrained models.

- `Part III – CNN Architectures and Concepts`  
  Conv2D, pooling, padding, strides, ReLU, BatchNorm, residual blocks, forward passes, and writing your own CNN models.

- `Part IV – Training and Fine-Tuning`  
  Training loops, optimizers, freezing layers, adapting pretrained CNNs, dropout, early stopping, learning rate schedules, and generalization strategies.

- `Part V – Inference, Evaluation, and Visual Debugging`  
  Train vs Eval mode, intermediate feature map visualizations, model evaluation strategies, and interpretability.

- `Part VI – Deployment-Ready Insights`  
  Inference pipelines, input consistency, test-time augmentation, and a practical CNN model debugging checklist.

---

## Built With

- Jupyter Notebooks + Markdown Chapters  
- PyTorch & TensorFlow (side-by-side)  
- Rich visualizations and debugging walkthroughs  
- Optional Hugging Face deployment (coming soon)

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/McKlay/cnn-companion-book.git
cd cnn-companion-book

# (Optional) Create a virtual environment and install dependencies
pip install -r requirements.txt
````

---

# Preview Chapters

Most chapters are available as standalone Jupyter notebooks and markdown files. You can read them directly in the repo or render them using tools like Jupyter Lab, Colab, or MkDocs (if converting to a site).

---

## Status

**Work in Progress**
This companion book is being built and refined chapter by chapter. Contributions, ideas, and feedback are welcome!

---

## License

MIT License © Clay Mark Sarte
Free to learn, fork, and remix with attribution.

---