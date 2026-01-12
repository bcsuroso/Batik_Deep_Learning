# Neural Batik Synthesis: Generative AI for Cultural Heritage

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Stable%20Diffusion-orange)
![Colab](https://img.shields.io/badge/Colab-Open%20Notebook-F9AB00?logo=googlecolab&color=525252)

## ⚠️ Important Note / Catatan Penting
**Due to GitHub storage limitations, the core training pipeline and main code for this project are hosted on Google Colab.**
Please access the full code and view the generated results via the link below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1uPYvkfWjpah_cpLWMUzqu5xb1lniAS38?usp=sharing)

*Link: [https://colab.research.google.com/drive/1uPYvkfWjpah_cpLWMUzqu5xb1lniAS38?usp=sharing](https://colab.research.google.com/drive/1uPYvkfWjpah_cpLWMUzqu5xb1lniAS38?usp=sharing)*

**Note:** Please download or open the notebook to visualize the full project outputs and training logs.

---

## 📌 Project Overview
This project leverages **Generative AI** to digitize and synthesize high-fidelity Indonesian Batik patterns. By fine-tuning **Stable Diffusion** models using **Low-Rank Adaptation (LoRA)**, this research addresses the challenge of preserving the structural consistency of traditional motifs while enabling modern digital creation.

## 🚀 Key Features
* **LoRA Fine-Tuning:** Efficient adaptation of large diffusion models on limited Batik datasets.
* **Structural Preservation:** Maintains the intricate geometry of traditional patterns (e.g., *Parang*, *Megamendung*) unlike standard generative models.
* **High-Fidelity Synthesis:** Generates high-resolution textures suitable for textile design.

## 🛠 Tech Stack
* **Core:** Python
* **ML Frameworks:** PyTorch, Hugging Face Diffusers
* **Technique:** Stable Diffusion v1.5 / SDXL, LoRA (Low-Rank Adaptation)
* **Tools:** OpenCV (for preprocessing)

## 📊 Methodology
1.  **Data Collection:** Curated a dataset of diverse traditional Indonesian Batik motifs.
2.  **Preprocessing:** Image augmentation and normalization using OpenCV.
3.  **Training:** Fine-tuned the UNet attention layers using LoRA to learn
