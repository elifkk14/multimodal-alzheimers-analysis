# Multimodal Alzheimer's Diagnosis System

Deep learning for early Alzheimer's detection from multimodal brain imaging (PET + MRI).

> 🏆 **1st Place — Genç Beyinler Yeni Fikirler 2026**
> TED University & Turkish Informatics Association (Türkiye Bilişim Derneği)

**Status** — active research, development ongoing
**Context** — B.Sc. graduation project, developed with the **Godetya** R&D team and in
collaboration with neurology and nuclear medicine physicians.

---

## About

This project explores whether combining two complementary imaging modalities — PET and
MRI — improves early detection of Alzheimer's disease compared with single-modality
approaches. The work covers the full pipeline: neuroimaging data curation under approved
data-use agreements, 3D preprocessing (spatial normalisation, brain masking), model
training, and validation against clinical reference measures.

Public neuroimaging datasets (ADNI, OASIS) were used under their respective data-use
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
