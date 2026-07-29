<h1 align="center">Muhammad Omer</h1>

<p align="center">
  <b>Ph.D. Researcher · Medical Image AI</b><br>
  Sungkyunkwan University · Prof. Hyunseung Choo's Lab, Suwon, South Korea
</p>

<p align="center">
  <a href="https://www.researchgate.net/profile/Muhammad-Omer-20"><img src="https://img.shields.io/badge/ResearchGate-00CCBB?style=flat-square&logo=researchgate&logoColor=white" alt="ResearchGate"></a>
  <a href="https://scholar.google.com/citations?user=YOUR_ID"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=flat-square&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://www.linkedin.com/in/muhammad-omer-0ab05a191/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://medium.com/@omer389"><img src="https://img.shields.io/badge/Medium-000000?style=flat-square&logo=medium&logoColor=white" alt="Medium"></a>
  <a href="mailto:omer389@g.skku.edu"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## Research

I build deep learning systems that read the eye to infer the state of the body — turning a routine retinal photograph into a non-invasive window on systemic health.

**Current directions**

- **Oculomics** — predicting systemic biomarkers (glycemic, lipid, renal, hematologic) from color fundus photographs
- **Choroidal OCT segmentation** — layer and vessel delineation, thickness quantification on clinical OCT volumes
- **Efficient & multimodal architectures** — lightweight ViT backbones, CFP+OCT fusion, retinal foundation models (RETFound, FLAIR)

---

## Why the Eye?

The retina is the only place in the body where you can see arteries, veins, and neural tissue directly — no incision, no needle, no contrast agent. Sixty seconds and a camera.

That means the vascular damage caused by diabetes, hypertension, and kidney disease is *visible* long before it becomes symptomatic. The open question isn't whether the signal is there. It's how much of it a model can actually recover, how well that holds across scanners and populations, and whether clinicians end up trusting it.

That gap is what I work on.

---

## What I'm Working On

- Scaling biomarker prediction beyond the usual suspects — moving past HbA1c and lipids toward the noisier, sparser labels most papers quietly drop
- Fine-tuning retinal foundation models on Korean clinical cohorts, and measuring how much of their pretraining actually transfers
- Prompt learning for medical vision-language models — can a text encoder carry clinical priors a pure vision backbone can't?
- Making ablations honest: seed-stable results, no leakage through imputation, one row per patient

---

## Data & Infrastructure

**Modalities** — color fundus photography · OCT & OCT-A · ultra-widefield imaging · DICOM / PACS workflows

**Scale** — hospital cohorts in the tens of thousands of images, with the messy label sparsity and class imbalance that come with real clinical data

**Systems** — multi-GPU PyTorch training (DDP, AMP), remote Linux workstations and lab servers, reproducible experiment harnesses

---

## Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face">
  <img src="https://img.shields.io/badge/MONAI-0E7C7B?style=flat-square" alt="MONAI">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white" alt="LaTeX">
</p>

---

## Writing

I write about AI in healthcare on [Medium](https://medium.com/@omer389) — mostly the parts that don't make it into papers: what broke, what the ablation actually showed, and why a benchmark number rarely survives contact with a clinic.

---

<p align="center">
  <sub>📫 <b>omer389@g.skku.edu</b> · Suwon, South Korea</sub>
</p>

<details>
<summary>GitHub stats</summary>
<br>
<img src="https://github-readme-stats.vercel.app/api?username=momer786&show_icons=true&hide_border=true&locale=en" alt="stats">
<img src="https://github-readme-stats.vercel.app/api/top-langs?username=momer786&layout=compact&hide_border=true&locale=en" alt="top languages">
</details>

<sub>Off-hours: historical documentaries, LeetCode, and 3D modelling in Blender — occasional renders at <a href="https://instagram.com/motive_dots">@motive_dots</a>.</sub>
