# Multimodal Alzheimer's Analysis

Deep learning for AI-assisted analysis of Alzheimer's disease from multimodal brain imaging
(amyloid PET + MRI).

> 🏆 **1st Place — Genç Beyinler Yeni Fikirler 2026**
> Inter-university project competition — Turkish Informatics Association (Türkiye Bilişim Derneği),
> Ankara Branch, held at TED University

**Status** — active research, development ongoing
**Context** — B.Sc. graduation project, continued as a volunteer university–industry research
project, in collaboration with neurology and nuclear medicine physicians.

---

## About

This project explores whether combining two complementary imaging modalities — PET and
MRI — improves AI-assisted analysis of Alzheimer's disease compared with single-modality
approaches. The work covers the full pipeline: neuroimaging data curation under approved
data-use agreements, 3D preprocessing (spatial normalisation, brain masking), model
training, and validation against clinical reference measures.

Public neuroimaging cohorts (ADNI, OASIS, A4, NACC) were used under their respective data-use
agreements. No imaging data is redistributed in this repository.

## Approach

- **Multimodal input** — paired PET and MRI brain volumes
- **3D preprocessing** — spatial normalisation and brain masking (MATLAB / SPM, Nibabel)
- **Architectures** — 3D convolutional networks (ResNet3D) and Vision Transformers
- **Training** — PyTorch Lightning, with MONAI for medical-imaging transforms
- **Validation** — against clinically established quantitative reference measures,
  reviewed with neurology and nuclear medicine specialists

## Tech stack

`Python` · `PyTorch` · `PyTorch Lightning` · `MONAI` · `NumPy` · `Pandas` ·
`Nibabel` · `Matplotlib` · `MATLAB / SPM`

## Source code

Source code is **not public**. The project is under active development and the
methodology is unpublished. I'm glad to walk through the architecture, the design
decisions behind it, and the results in detail — please get in touch.

## Contact

**Elif Konak** — [elif.konak@yahoo.com.tr](mailto:elif.konak@yahoo.com.tr)
[Portfolio](https://elifkk14.github.io) · [LinkedIn](https://www.linkedin.com/in/elif-konakk/)
