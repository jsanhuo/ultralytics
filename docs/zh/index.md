---
comments: true
description: 探索 Ultralytics YOLOv8 - 最新的实时物体检测和图像分割技术。了解其功能并在您的项目中最大限度地发挥其潜力。
keywords: Ultralytics、YOLOv8、目标检测、图像分割、深度学习、计算机视觉、人工智能、机器学习、文档、教程。
---

<div align="center">
<a href="https://github.com/ultralytics/assets/releases/tag/v8.2.0" target="_blank"><img width="1024%" src="https://raw.githubusercontent.com/ultralytics/assets/main/yolov8/banner-yolov8.png" alt="Ultralytics YOLO banner"></a>
<a href="https://docs.ultralytics.com/zh/">中文</a> |
<a href="https://docs.ultralytics.com/ko/">한국어</a> |
<a href="https://docs.ultralytics.com/ja/">日本語</a> |
<a href="https://docs.ultralytics.com/ru/">Русский</a> |
<a href="https://docs.ultralytics.com/de/">Deutsch</a> |
<a href="https://docs.ultralytics.com/fr/">Français</a> |
<a href="https://docs.ultralytics.com/es/">Español</a> |
<a href="https://docs.ultralytics.com/pt/">Português</a> |
<a href="https://docs.ultralytics.com/tr/">Türkçe</a> |
<a href="https://docs.ultralytics.com/vi/">Tiếng Việt</a> |
<a href="https://docs.ultralytics.com/hi/">हिन्दी</a> |
<a href="https://docs.ultralytics.com/ar/">العربية</a>
<br>
<br>
<a href="https://github.com/ultralytics/ultralytics/actions/workflows/ci.yaml"><img src="https://github.com/ultralytics/ultralytics/actions/workflows/ci.yaml/badge.svg" alt="Ultralytics CI"></a>
<a href="https://codecov.io/github/ultralytics/ultralytics"><img src="https://codecov.io/github/ultralytics/ultralytics/branch/main/graph/badge.svg?token=HHW7IIVFVY" alt="Ultralytics Code Coverage"></a>
<a href="https://zenodo.org/badge/latestdoi/264818686"><img src="https://zenodo.org/badge/264818686.svg" alt="YOLOv8 Citation"></a>
<a href="https://hub.docker.com/r/ultralytics/ultralytics"><img src="https://img.shields.io/docker/pulls/ultralytics/ultralytics?logo=docker" alt="Docker Pulls"></a>
<a href="https://ultralytics.com/discord"><img alt="Discord" src="https://img.shields.io/discord/1089800235347353640?logo=discord&logoColor=white&label=Discord&color=blue"></a>
<br>
<a href="https://console.paperspace.com/github/ultralytics/ultralytics"><img src="https://assets.paperspace.io/img/gradient-badge.svg" alt="Run on Gradient"></a>
<a href="https://colab.research.google.com/github/ultralytics/ultralytics/blob/main/examples/tutorial.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>
<a href="https://www.kaggle.com/ultralytics/yolov8"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a>
</div>

[Ultralytics](https://ultralytics.com)和[YOLOv8](https://github.com/ultralytics/ultralytics),这是备受赞誉的实时目标检测和图像分割模型的最新版本。YOLOv8模型是基于深度学习和计算机视觉的前沿技术所研发，具有卓越的速度和无与伦比的准确性。其简单的网络设计使其可以适用于各种应用，并且可以适配不同的硬件平台，包括边缘设备和云平台。

探索YOLOv8文档, 这是一个非常详细的资源文档，目的在于帮助您了解和利用Ultralytics的特性和功能。无论您是经验丰富的机器学习从业者还是新手，此文档都是为了最大限度的发挥YOLOv8在您的项目中的潜力。

<div align="center">
  <br>
  <a href="https://github.com/ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-github.png" width="3%" alt="Ultralytics GitHub"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://www.linkedin.com/company/ultralytics/"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-linkedin.png" width="3%" alt="Ultralytics LinkedIn"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://twitter.com/ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-twitter.png" width="3%" alt="Ultralytics Twitter"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://youtube.com/ultralytics?sub_confirmation=1"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-youtube.png" width="3%" alt="Ultralytics YouTube"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://www.tiktok.com/@ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-tiktok.png" width="3%" alt="Ultralytics TikTok"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://ultralytics.com/bilibili"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-bilibili.png" width="3%" alt="Ultralytics Instagram"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://ultralytics.com/discord"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-discord.png" width="3%" alt="Ultralytics Discord"></a>
</div>

## 如何开始

- **安装** `ultralytics` 使用pip进行快速安装 &nbsp; [:material-clock-fast: Get Started](quickstart.md){ .md-button }
- **预测** 使用YOLOV8预测图像或视频 &nbsp; [:octicons-image-16: Predict on Images](modes/predict.md){ .md-button }
- **训练** 在您自己的自定义数据集上训练新YOLOv8模型 &nbsp; [:fontawesome-solid-brain: Train a Model](modes/train.md){ .md-button }
- **任务** YOLOv8任务包括：分段、分类、姿势和跟踪 &nbsp; [:material-magnify-expand: Explore Tasks](tasks/index.md){ .md-button }
- **新的 🚀 数据浏览器** 具有高级语义和SQL查询的数据浏览器 &nbsp; [:material-magnify-expand: Explore a Dataset](datasets/explorer/index.md){ .md-button }

<p align="center">
  <br>
  <iframe loading="lazy" width="720" height="405" src="https://www.youtube.com/embed/LNwODJXcvt4?si=7n1UvGRLSd9p5wKs"
    title="YouTube video player" frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen>
  </iframe>
  <br>
  <strong>Watch:</strong> How to Train a YOLOv8 model on Your Custom Dataset in <a href="https://colab.research.google.com/github/ultralytics/ultralytics/blob/main/examples/tutorial.ipynb" target="_blank">Google Colab</a>.
</p>

## YOLO: A Brief History

[YOLO](https://arxiv.org/abs/1506.02640) (You Only Look Once), 华盛顿大学的Joseph Redmon和Ali Farhadi开发了一种流行的对象检测和图像分割模型。YOLO于2015年推出，以其高速度和高精度迅速走红。

- [YOLOv2](https://arxiv.org/abs/1612.08242)， 于2016年发布，通过合并批处理规范化、锚盒和维度簇改进了原始模型。
- [YOLOv3](https://pjreddie.com/media/files/papers/YOLOv3.pdf)， 于2018年推出，使用更高效的骨干网络、多个锚点和空间金字塔池进一步增强了该模型的性能。
- [YOLOv4](https://arxiv.org/abs/2004.10934) 于2020年发布，引入了Mosaic数据增强、新的无锚检测头和新的丢失功能等创新。
- [YOLOv5](https://github.com/ultralytics/yolov5) 进一步提高了模型的性能，增加了超参数优化、集成实验跟踪和自动导出到流行导出格式等新功能。
- [YOLOv6](https://github.com/meituan/YOLOv6) 由 [美团](https://about.meituan.com/) 开源于 2022 年并且在在该公司的许多自动配送机器人中使用。
- [YOLOv7](https://github.com/WongKinYiu/yolov7) 增加了额外的任务，例如在COCO关键点数据集上的姿态估计。
- [YOLOv8](https://github.com/ultralytics/ultralytics) 是Ultralytics的YOLO的最新版本。作为一款尖端、最先进的（SOTA）车型，YOLOv8在先前版本的成功基础上，引入了新功能和改进，以增强性能、灵活性和效率。YOLOv8支持全方位的视觉AI任务，包括[检测]（tasks/detect.md）、[分割]（tasks/segment.md），[姿态估计]（tasks/spose.md）、[跟踪]（modes/track.md）和[分类]（tasks/classification.md）。这种多功能性允许用户在不同的应用程序和域中利用YOLOv8的功能。
- [YOLOv9](models/yolov9.md) 引入了可编程梯度信息（PGI）和广义有效层聚合网络（GELAN）等创新方法。
- [YOLOv10](models/yolov10.md) 由[清华大学](https://www.tsinghua.edu.cn/en/)的研究人员使用[Ultralytics](https://ultralytics.com/）    [Python包](https://pypi.org/project/ultralytics/)进行构建. 此版本通过引入消除非最大抑制（NMS）要求的端到端头，引入了实时[目标检测]（tasks/detect.md）改进。

## YOLO 许可证: Ultralytics YOLO 如何获得许可？

Ultralytics 提供两种许可选项以适应不同的用例：

- **AGPL-3.0 许可证**: [OSI-approved](https://opensource.org/licenses/) 开源许可证是学生和爱好者的理想选择，可以促进开放协作和知识共享。详情请查看文档 [许可证](https://github.com/ultralytics/ultralytics/blob/main/LICENSE).
- **企业许可证**: 该许可证专为商业用途设计，允许Ultralytics软件和人工智能模型无缝集成到商业商品和服务中，绕过AGPL-3.0的开源要求。如果您的方案涉及将我们的解决方案嵌入到商业产品中，请联系[Ultralytics Licensing](https://ultralytics.com/license).

我们的许可策略旨在确保对开源项目的任何改进都能回馈社区。 我们把开源的原则放在心上 ❤️， 我们的使命是保证我们的贡献能够以有益于所有人的方式得到利用和扩大。
