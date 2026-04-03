<div align="center">

# 🧠 Deep Learning — Computer Vision Portfolio

**Matias Marro**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/YOUR-LINKEDIN/)
[![GitHub](https://img.shields.io/badge/GitHub-MatiasMarro-181717?style=flat-square&logo=github)](https://github.com/MatiasMarro)
[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)](https://tensorflow.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org)

*A collection of end-to-end deep learning projects focused on computer vision — from semantic segmentation and object detection to face recognition and multimodal image retrieval.*

---

</div>

## 📌 About This Repository

This repository showcases hands-on deep learning projects that demonstrate practical skills in **computer vision**, **deep learning architectures**, and **AI engineering**. Each project follows a complete pipeline: data loading, preprocessing, model design, training, evaluation, and visualization of results.

> **About me:** I'm an advanced Electronic Engineering student at the National Technological University (UTN-FRC) in Córdoba, Argentina, with a strong focus on AI, deep learning, and computer vision. I'm actively seeking opportunities as an **AI / ML Engineer**.

---

## 🚀 Projects

### 1. Semantic Image Segmentation — CamVid Dataset

| | |
|---|---|
| **Notebook** | [`CamVid_Image_Segmentation.ipynb`](./CamVid_Image_Segmentation.ipynb) |
| **Task** | Pixel-wise semantic segmentation of urban driving scenes |
| **Architecture** | FCN-8s (Fully Convolutional Network) with VGG-16 encoder |
| **Dataset** | [CamVid](http://mi.eng.cam.ac.uk/research/projects/VideoRec/CamVid/) — 367 training / 101 validation images, 12 semantic classes |
| **Key Techniques** | Transfer learning, skip connections, transposed convolutions, IoU & Dice score evaluation |
| **Framework** | TensorFlow / Keras |

**Highlights:**
- Built an end-to-end FCN-8 architecture combining VGG-16 encoder features at multiple scales via skip connections for fine-grained segmentation.
- Trained for 170 epochs reaching ~85% accuracy on both training and validation sets.
- Evaluated using Intersection-over-Union (IoU) and Dice Score metrics — standard benchmarks for segmentation tasks.

---

### 2. Face Recognition — Labeled Faces in the Wild (LFW)

| | |
|---|---|
| **Notebook** | [`Labeled_Faces_in_the_Wild.ipynb`](./Labeled_Faces_in_the_Wild.ipynb) |
| **Task** | Face recognition and classification |
| **Dataset** | [LFW (Labeled Faces in the Wild)](http://vis-www.cs.umass.edu/lfw/) — real-world face images of public figures |
| **Key Techniques** | Face embeddings, feature extraction, classification, data augmentation |
| **Framework** | TensorFlow / Keras |

**Highlights:**
- Worked with a real-world, unconstrained face dataset widely used as a benchmark in the face recognition community.
- Implemented preprocessing pipelines including face alignment and normalization.
- Explored deep feature extraction and embedding-based approaches for face verification/identification.

---

### 3. Object Detection

| | |
|---|---|
| **Notebook** | [`Objetct_Detection.ipynb`](./Objetct_Detection.ipynb) |
| **Task** | Detecting and localizing objects within images |
| **Key Techniques** | Bounding box regression, classification heads, non-max suppression, transfer learning |
| **Framework** | TensorFlow / Keras |

**Highlights:**
- Implemented a complete object detection pipeline from data preparation to inference with bounding box visualization.
- Applied transfer learning using pretrained feature extractors to accelerate convergence.
- Demonstrated understanding of the detection paradigm: region proposal, classification, and localization jointly.

---

### 4. Multimodal Image Retrieval with CLIP & Sentence Transformers

| | |
|---|---|
| **Notebook** | [`clip_image_retrieval_sentence_transformers.ipynb`](./clip_image_retrieval_sentence_transformers.ipynb) |
| **Task** | Text-to-image retrieval using multimodal embeddings |
| **Model** | OpenAI CLIP via Sentence Transformers |
| **Key Techniques** | Contrastive learning, cross-modal embeddings, cosine similarity search |
| **Framework** | PyTorch / Sentence Transformers |

**Highlights:**
- Leveraged CLIP's vision-language alignment to retrieve images using natural language queries.
- Used Sentence Transformers for efficient encoding of both text and image modalities into a shared embedding space.
- Demonstrates practical understanding of modern multimodal AI and retrieval systems.

---

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | Python |
| **Deep Learning** | TensorFlow, Keras, PyTorch |
| **Computer Vision** | OpenCV, Albumentations, PIL |
| **Models & Architectures** | VGG-16, FCN-8, CLIP, Sentence Transformers |
| **ML Tools** | NumPy, Pandas, Matplotlib, Scikit-learn |
| **Environment** | Google Colab (GPU), Jupyter Notebooks |

---

## 📂 Repository Structure

```
Deep-Learning/
│
├── CamVid_Image_Segmentation.ipynb        # Semantic segmentation with FCN-8 on CamVid
├── Labeled_Faces_in_the_Wild.ipynb        # Face recognition on LFW dataset
├── Objetct_Detection.ipynb                # Object detection pipeline
├── clip_image_retrieval_sentence_transformers.ipynb  # CLIP-based image retrieval
└── README.md                              # This file
```

---

## ▶️ How to Run

All notebooks are designed to run on **Google Colab** with GPU acceleration:

1. Click on any notebook above.
2. Open it in Google Colab using the badge or via `File > Open in Colab`.
3. Enable GPU runtime: `Runtime > Change runtime type > GPU`.
4. Run all cells sequentially.

Alternatively, clone the repository and run locally:

```bash
git clone https://github.com/MatiasMarro/Deep-Learning.git
cd Deep-Learning
jupyter notebook
```

---

## 📊 Skills Demonstrated

- **Deep Learning:** Designing, training, and evaluating CNNs and transformer-based models from scratch and via transfer learning.
- **Computer Vision:** Semantic segmentation, object detection, face recognition, and image retrieval.
- **Multimodal AI:** Working with vision-language models (CLIP) for cross-modal understanding.
- **ML Engineering:** Data pipelines, augmentation strategies, metrics evaluation (IoU, Dice, Accuracy), and experiment tracking.
- **Research Literacy:** Implementing architectures from academic papers (FCN, VGG, CLIP).

---

## 📬 Contact

I'm open to opportunities in **AI Engineering**, **Machine Learning**, **Computer Vision**, and **Deep Learning**.

- **GitHub:** [github.com/MatiasMarro](https://github.com/MatiasMarro)
- **Location:** Córdoba, Argentina
- **Education:** Electronic Engineering — UTN-FRC (Universidad Tecnológica Nacional)

---

<div align="center">

⭐ *If you find these projects useful, consider giving this repo a star!*

</div>
