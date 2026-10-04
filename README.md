# Awesome-Computer-Vision-API

# Awesome-Computer-Vision-API



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Image Recognition, Object Detection, OCR & Custom Vision Models*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Computer Vision APIs**. These tools help developers add image analysis, object detection, facial recognition, and custom model training to their applications without building vision infrastructure from scratch.



**Examples** include Microsoft Computer Vision AI, Google Cloud Vision API, AWS Rekognition, Clarifai, Hive Vision API, Roboflow, V7 Darwin, Landing AI, SuperAnnotate, and Nyckel (the category leaders).



**Open-source emphasis**: The open-source computer vision ecosystem is **exceptionally mature**, anchored by **OpenCV** (the foundational library for classical CV), **YOLO** (real-time object detection), and **Roboflow Inference** (self-hosted model serving, now free to use locally) . **Hugging Face Transformers** provides thousands of pre-trained vision models, while **Detectron2** and **MMDetection** offer production-grade detection frameworks.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📖 Table of Contents



- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🤝 How to Contribute](#-how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## ☁️ SaaS/Hosted Platforms



> **📊 Market Context**: The global computer vision market is estimated at **~$20B in 2026**, growing toward **~$50B by 2032** at a **~16% CAGR**. The sector is **moderately fragmented** — hyperscalers (Microsoft, Google, AWS) bundle vision APIs as value-adds, while specialized platforms (Clarifai, Roboflow, Landing AI) compete on custom model training and MLOps workflows. **Pricing models vary dramatically**: Microsoft's Free (F0) tier allows **5,000 transactions/month** with **20 transactions/minute** , Google's free tier caps at **1,000 feature requests/month** , and AWS Rekognition offers limited free tier for new users . **Roboflow's September 2026 overhaul** introduced a **free Core tier with 10 credits** (enough for ~30 model trainings or 80,000 inferences) and made **self-hosted inference free** . No single vendor holds a winner-take-all position; enterprises typically run multi-vendor stacks.



| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |

|----------|-------------|------------------------|------------------|--------------|

| **[Microsoft Computer Vision AI](https://azure.microsoft.com/en-us/products/ai-services/ai-vision)** | Azure's vision API for image analysis, OCR, face detection, and spatial analysis. | **F0 (Free)**: 5,000 transactions/month; **S1 (Standard)**: Pay-as-you-go, **20 transactions/second** . | **F0 tier**: **5,000 transactions/month**, **20 transactions/minute**, **500 training images/project** . | **~$281B revenue (Microsoft FY2025)** |

| **[Google Cloud Vision API](https://cloud.google.com/vision)** | Google's vision API for label detection, OCR, face detection, and explicit content detection. | **Pay-as-you-go**: **$1.50 per 1,000 images** (first 1,000 free/month) . | **Free tier**: **1,000 feature requests/month**, 5 GB Cloud Storage . | **~$350B revenue (Alphabet FY2025)** |

| **[AWS Rekognition](https://aws.amazon.com/rekognition/)** | AWS's deep learning-based image and video analysis service. Face detection, object labeling, text detection, and custom moderation. | **Pay-as-you-go**: Based on images, video minutes, and features used. | **Limited free tier** for new AWS users; otherwise pay-as-you-go . | **~$638B revenue (Amazon FY2025)** |

| **[Clarifai](https://www.clarifai.com/)** | AI platform for computer vision, NLP, and custom model training. REST and gRPC APIs. | **Freemium**: **$1.20/month** usage-based starting price . | **Free version** available with limited usage . | **Private (~$100M+ raised est.)** |

| **[Hive Vision API](https://thehive.ai/)** | AI models for visual moderation, image generation, and AutoML. | **Pay-as-you-go**: **$3.00 per 1,000 images** (visual moderation) . | **Default rate limits**: **100 requests/day** for Text/Visual Moderation with V3 API key . | **Private (~$120M+ raised)** |

| **[Roboflow](https://roboflow.com/)** | End-to-end CV platform: dataset management, annotation, training, and serverless inference. | **Serverless API**: Per-image pricing; **Core Plan**: Free tier with 10 credits . | **Core Free Tier**: **10 credits/month** (~30 model trainings or 80,000 inferences with RF-DETR Nano) . **Self-hosted inference**: Free . | **Private (~$80M+ raised)** |

| **[V7 Darwin](https://www.v7labs.com/)** | AI-assisted data labeling and document automation platform. | **Sales-led**: Custom pricing (platform fee + user licenses + data processing) . | **Trial available on request** — demo required . | **Private (~$50M+ raised)** |

| **[Landing AI](https://landing.ai/)** | Agentic Document Extraction (ADE) for document processing. | **Explore**: Free with **1,000 credits**; **Team**: Subscription tiers with credits; **Enterprise**: Custom . | **Explore plan**: **1,000 free credits** (expire 90 days after account creation) . | **Private (Andrew Ng-backed)** |

| **[SuperAnnotate](https://www.superannotate.com/)** | Data labeling and curation platform for multimodal AI. | **Sales-led**: Starter, Pro, Enterprise tiers — quote required . | **Requires approval** for trial . No public free tier. | **Private (~$50M+ raised)** |

| **[Nyckel](https://www.nyckel.com/)** | No-code AI platform for classification, detection, and segmentation. | **Pay-as-you-go**: **$0.005 per invoke** after free tier . | **Free tier**: **100 invokes/month**, up to **200 samples**, **5 functions** . | **Private (~$20M+ raised)** |



## 🔓 Open-Source GitHub Projects



Sorted by star count (descending). Star badge links to each repo's stargazers page.



| Repo | Description | Stars |

|---|---|---|

| **[OpenCV](https://github.com/opencv/opencv)** — **The foundational computer vision library.** 2,500+ optimized algorithms for image processing, object detection, facial recognition, and more. C++, Python, Java, and JavaScript bindings. **Apache-2.0**. | [![Stars](https://img.shields.io/github/stars/opencv/opencv?style=social&color=white)](https://github.com/opencv/opencv/stargazers) | ~82,000 |

| **[Transformers (Hugging Face)](https://github.com/huggingface/transformers)** — **State-of-the-art ML models for vision, text, and audio.** Thousands of pre-trained vision models (ViT, DETR, SAM, etc.) with simple APIs. **Apache-2.0**. | [![Stars](https://img.shields.io/github/stars/huggingface/transformers?style=social&color=white)](https://github.com/huggingface/transformers/stargazers) | ~150,000 |

| **[YOLOv8 (Ultralytics)](https://github.com/ultralytics/ultralytics)** — **The leading real-time object detection framework.** YOLOv8/v11/v12 with training, validation, prediction, and export. **AGPL-3.0** (commercial license available). | [![Stars](https://img.shields.io/github/stars/ultralytics/ultralytics?style=social&color=white)](https://github.com/ultralytics/ultralytics/stargazers) | ~35,000 |

| **[Detectron2](https://github.com/facebookresearch/detectron2)** — **Facebook AI's next-generation detection and segmentation library.** Mask R-CNN, RetinaNet, Faster R-CNN, and more. **Apache-2.0**. | [![Stars](https://img.shields.io/github/stars/facebookresearch/detectron2?style=social&color=white)](https://github.com/facebookresearch/detectron2/stargazers) | ~30,000 |

| **[MMDetection](https://github.com/open-mmlab/mmdetection)** — **OpenMMLab's detection toolbox.** 50+ pre-trained models, modular architecture, extensive config system. **Apache-2.0**. | [![Stars](https://img.shields.io/github/stars/open-mmlab/mmdetection?style=social&color=white)](https://github.com/open-mmlab/mmdetection/stargazers) | ~30,000 |

| **[Roboflow Inference](https://github.com/roboflow/inference)** — **Self-hosted, production-grade CV model serving.** Now free for local use . Supports RF-DETR, YOLO, SAM, and custom models. **Apache-2.0**. | [![Stars](https://img.shields.io/github/stars/roboflow/inference?style=social&color=white)](https://github.com/roboflow/inference/stargazers) | ~2,000 |

| **[Segment Anything (SAM)](https://github.com/facebookresearch/segment-anything)** — **Meta's foundation model for image segmentation.** Zero-shot segmentation with prompts. **Apache-2.0**. | [![Stars](https://img.shields.io/github/stars/facebookresearch/segment-anything?style=social&color=white)](https://github.com/facebookresearch/segment-anything/stargazers) | ~50,000 |



**Additional open-source options worth exploring:**



| Repo | Description |

|---|---|

| **[PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)** — Multilingual OCR toolkit with 80+ language support. Text detection, recognition, and layout analysis. **Apache-2.0**. | [![Stars](https://img.shields.io/github/stars/PaddlePaddle/PaddleOCR?style=social&color=white)](https://github.com/PaddlePaddle/PaddleOCR/stargazers) |

| **[InsightFace](https://github.com/deepinsight/insightface)** — State-of-the-art face detection, recognition, and alignment. ArcFace, RetinaFace, and more. **MIT**. | [![Stars](https://img.shields.io/github/stars/deepinsight/insightface?style=social&color=white)](https://github.com/deepinsight/insightface/stargazers) |

| **[Albumentations](https://github.com/albumentations-team/albumentations)** — Fast image augmentation library for deep learning. **MIT**. | [![Stars](https://img.shields.io/github/stars/albumentations-team/albumentations?style=social&color=white)](https://github.com/albumentations-team/albumentations/stargazers) |

| **[Label Studio](https://github.com/HumanSignal/label-studio)** — Open-source data labeling for vision, text, and audio. **Apache-2.0**. | [![Stars](https://img.shields.io/github/stars/HumanSignal/label-studio?style=social&color=white)](https://github.com/HumanSignal/label-studio/stargazers) |

| **[CVAT](https://github.com/opencv/cvat)** — Computer Vision Annotation Tool. Mature image/video labeling with auto-annotation. **MIT**. | [![Stars](https://img.shields.io/github/stars/opencv/cvat?style=social&color=white)](https://github.com/opencv/cvat/stargazers) |

| **[FiftyOne](https://github.com/voxel51/fiftyone)** — Dataset curation, visualization, and model debugging for vision. **Apache-2.0**. | [![Stars](https://img.shields.io/github/stars/voxel51/fiftyone?style=social&color=white)](https://github.com/voxel51/fiftyone/stargazers) |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Computer vision APIs handle potentially sensitive image data; ensure compliance with privacy regulations and obtain proper consent for face processing.

- **Open-source reality**: The open-source ecosystem for computer vision is **exceptionally mature**. **OpenCV** remains the foundational library for classical CV, while **YOLO** leads real-time object detection and **Roboflow Inference** provides production-grade self-hosted model serving (now free locally) . **Hugging Face Transformers** offers thousands of pre-trained models. However, **commercial platforms** (Microsoft, Google, AWS, Clarifai) provide **managed infrastructure, enterprise SLAs, and integrated MLOps** that open-source alternatives require significant engineering investment to match. The open-source path is **genuinely viable** for organizations with strong ML engineering capacity.

- **Pricing caveat**: All pricing figures above are **verified against cited search results** but may change without notice. Free tiers have strict rate limits (Microsoft F0: 20 transactions/minute ; Google: 1,000 requests/month ) and eligibility restrictions. Always check the provider's official page for current terms.



---



**Made for ML engineers, computer vision developers, data scientists, and AI product teams.**

Let's make computer vision more open, transparent, and accessible.
