# Hi there, I'm [Tianle] 👋

### Biomedical Engineer · Medical AI · Few-shot Deep Learning / 生物医学工程 · 医学人工智能 · 小样本深度学习

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white"/>
  <img src="https://img.shields.io/badge/MONAI-000000?style=flat"/>
  <img src="https://img.shields.io/badge/Medical%20Imaging-0B3D91?style=flat"/>
  <img src="https://img.shields.io/badge/Contrastive%20Learning-FF6F00?style=flat"/>
</p>

> I build **data-efficient, interpretable deep learning models for cancer diagnosis and risk stratification**,
> fusing multimodal medical imaging (PET/CT, mpMRI, ultrasound, CT) with clinical variables — even when data is scarce.

---

## 🔬 Research Focus / 研究方向

- 🧠 **Few-shot & small-sample deep learning** — contrastive learning, metric-based inference for data-scarce medical scenarios
- 🖼️ **Multimodal fusion** — PET/CT + mpMRI + ultrasound + clinical variables (input-level & decision-level)
- 🔍 **Interpretability** — Grad-CAM, SHAP, feature-space / decision-boundary visualization
- 🏥 **Clinical applications** — cancer risk stratification, molecular subtype prediction, ICU time-series analysis

## 📌 Featured Projects / 代表项目

| Project | Clinical Task | Modality | Key Result | Paper |
|---|---|---|---|---|
| **CL-MGNET** | Prostate cancer high-invasive feature prediction (ISUP≥3 / EPE / PSM) | ¹⁸F-PSMA-1007 PET/CT + mpMRI + clinical | Internal AUC **0.877** / External AUC **0.872** | *Acad Radiol*, 2026 |
| **FADNET / CLI-FADNET** | HER2-low prediction in triple-negative breast cancer | Breast US + mpMRI (T2WI/DWI/DCE) + clinical | AUC **0.884** | *BMC Med Imaging*, 2026 |
| **USECNC+CL** | Ovarian cancer WHO Type I / II subtype prediction | US + non-contrast & enhanced CT + clinical (Cross-Attention fusion) | AUC **0.87** / External **0.850** | *BMC Med Imaging*, 2026 |
| **MSNET / CL-MSNET** | Prostate cancer ISUP grading | PET/CT + mpMRI + clinical (few-shot Siamese) | AUC **0.865** | *EJNMMI*, 2025 |
| **Graph Time-Series** | ICU mortality / phenotype / length-of-stay prediction on irregularly sampled EHR (MIMIC-III/IV) | Graph network over clinical time-series | Outperforms 10 baselines across 4 datasets | *JMIR Med Inform*, 2026 |

## 🛠️ Tech Stack

`PyTorch` · `ResNet / ResNet3D` · `MedicalNet pretraining` · `Contrastive Learning` · `Soft k-means / KNN` · `Cross-Attention` · `GCN` · `Grad-CAM` · `SHAP` · `PyRadiomics` · `SimpleITK / ITK-SNAP` · `scikit-learn` · `R (ggplot2)` · `DeLong test / DCA / calibration analysis`

## 📊 GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=[你的GitHub用户名]&show_icons=true&theme=default" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=[你的GitHub用户名]&layout=compact" height="150"/>
</p>

## 📄 Publications (selected / 部分论文)

1. **CL-MGNET**: Generalizable Deep Learning for Prostate Cancer Risk Stratification: Multicenter Study Integrating ¹⁸F-PSMA-1007 PET/CT and mpMRI. *Academic Radiology*, 2026.
2. **Graph Network Feature Space Fusion** for Predicting Irregularly Sampled Medical Time-Series Data. *JMIR Medical Informatics*, 2026.
3. **FADNET**: A Multimodal Deep Learning Classifier for Prediction of HER2-low Expression in Triple-negative Breast Cancer. *BMC Medical Imaging*, 2026.
4. **USECNC+CL**: Multimodal fusion-based deep learning for pathological subtype prediction of Type I and Type II ovarian cancer. *BMC Medical Imaging*, 2026.
5. **MSNET**: Exploring the role of multimodal [¹⁸F]F-PSMA-1007 PET/CT and multiparametric MRI data in predicting ISUP grading of primary prostate cancer. *European Journal of Nuclear Medicine and Molecular Imaging*, 2025.

## 📫 Contact / 联系方式

- 📧 Email: [1321624016@qq.com]
- 知乎 / 公众号: [可选，用于引流接单]
- 💼 Open to collaboration & consulting on medical AI projects / 承接医学影像深度学习科研合作与技术咨询


