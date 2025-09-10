# 🧩 MMIF-Review

## A Comprehensive Review of Techniques, Algorithms, Advancements, Challenges, and Clinical Applications of Multi-Modal Medical Image Fusion for Improved Diagnosis

[![Made with ❤️ for MMIF](https://img.shields.io/badge/MMIF-review-blueviolet)](#)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)
[![Last Update](https://img.shields.io/badge/last%20update-Auto-blue)](#)

---

### 📖 About This Review
This repository is a **companion resource** to our review paper:  
**“A comprehensive review of techniques, algorithms, advancements, challenges, and clinical applications of multi-modal medical image fusion for improved diagnosis.”**

The review provides:
- 🖼️ **Traditional Approaches** – pixel-level, feature-level, decision-level fusion  
- 🤖 **AI-Driven Fusion** – deep learning, generative, and transformer-based methods  
- 🧪 **Comparative Analysis** – robustness, interpretability, and computational trade-offs  
- 🩺 **Clinical Applications** – oncology, neurology, cardiology, precision medicine  
- 🚧 **Challenges & Opportunities** – privacy, heterogeneity, real-time, XAI, federated learning  

This repo extends the paper with **datasets, models, and structured summaries** to accelerate MMIF research.

---

## 📊 Multi-Modal Medical Imaging Datasets (Curated)
A practical list spanning CT, MRI, PET, SPECT, Ultrasound, X-ray.

| Dataset Name | Modalities | Task(s) | Domain / Focus | Access |
|---|---|---|---|---|
| IXI | MRI (T1/T2/PD/DTI) | Fusion, Segmentation | Neuroimaging | https://brain-development.org/ixi-dataset/ |
| ADNI | MRI + PET | Fusion, Classification | Alzheimer’s | http://adni.loni.usc.edu/ |
| BraTS (fusion subsets) | MRI (T1, T1ce, T2, FLAIR) | Tumor Segmentation | Neuro-oncology | https://www.med.upenn.edu/cbica/brats/ |
| Whole Brain Atlas | MRI + PET | Diagnosis | Neuro | http://www.med.harvard.edu/AANLIB/home.html |
| TCIA (fusion-friendly) | MRI, CT, PET, SPECT | Multi-task | Oncology/Cardiology | https://www.cancerimagingarchive.net/ |
| OASIS | MRI + PET | Dementia | Neuro | https://www.oasis-brains.org/ |
| ISLES | MRI + CT perfusion | Stroke Lesion | Neurology | https://www.isles-challenge.org/ |
| DRIVE / STARE | Fundus | Fusion/Vessel detection | Ophthalmology | https://drive.grand-challenge.org/ / https://cecas.clemson.edu/~ahoover/stare/ |

👉 Add more in `datasets/entries/` using the template below.

---

## 🤖 Open-Source MMIF Models (Curated)

| Repository | Model / Framework | Task(s) | Domain | Link |
|---|---|---|---|---|
| DeepFuse | CNN-based Fusion | Multi-modal fusion | Imaging | https://github.com/rajivnasar/DeepFuse |
| FusionGAN | GAN-based Fusion | PET-CT/MRI fusion | Medical | https://github.com/HzFu/FusionGAN |
| DDcGAN | Dual-Discriminator GAN | CT-MRI fusion | Medical | https://github.com/hli1221/DDcGAN |
| DenseFuse | DenseNet-based Fusion | IR-VIS (extendable) | General | https://github.com/hli1221/DenseFuse |
| U2Fusion | Unified Fusion Framework | Multi-modal | Medical/RS | https://github.com/hli1221/U2Fusion |
| SwinFusion | Transformer-based Fusion | Multi-modal | General | https://github.com/linfengzhang/SwinFusion |
| IFCNN | CNN-based Fusion | MRI-CT | Medical | https://github.com/yanchaozhong/IFCNN |
| TransFusion | Transformer-based Fusion | PET-CT/MRI | Medical | https://github.com/wgcban/TransFusion |

👉 Add more in `models/entries/` using the template below.

---


## 🧱 Dataset Entry Template (Markdown)

Create: `datasets/entries/DATASET_NAME.md`
```markdown
# DATASET_NAME

**Modalities:** (e.g., MRI T1/T2/FLAIR, PET, CT, SPECT, US, X-ray)  
**Primary Tasks:** (e.g., fusion, segmentation, registration, classification)  
**Domain/Focus:** (e.g., neuro, oncology, cardiology, ophthalmology)  
**Size/Scale:** (subjects/scans/slices; train/val/test if known)  
**Access/License:** (link + license)  
**Notes:** (preprocessing tips, common fusion pairings, caveats)



@article{Zubair2025MMIF,
  title   = {A comprehensive review of techniques, algorithms, advancements, challenges, and clinical applications of multi-modal medical image fusion for improved diagnosis},
  author  = {Muhammad Zubair, Muzammil Hussain, Mousa Ahmad Al-Bashrawi, Malika Bendechache, Muhammad Owais},
  journal = {Computer Methods and Programs in Biomedicine},
  volume  = {---},
  pages   = {---},
  year    = {2025},
  issn    = {---},
  doi     = {---},
  url     = {---}
}

