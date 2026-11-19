<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:0891b2,100:c026d3&height=200&section=header&text=Akhil%20Nath%20Reddy&fontSize=48&fontColor=ffffff&fontAlignY=36&desc=ML%20Engineer%20%E2%80%A2%20Researcher%20%E2%80%A2%20Kaggler&descAlignY=58&descSize=18" alt="Akhil Nath Reddy" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=22D3EE&center=true&vCenter=true&width=640&lines=I+build+ML+models+and+test+them+honestly+%F0%9F%A7%A0;Medical+imaging+%E2%80%A2+Forecasting+%E2%80%A2+Molecular+ML;Researching+LLM+benchmark+contamination+%F0%9F%94%AC;Competing+on+Kaggle+%E2%80%A2+Publishing+open+datasets;Understand+the+math%2C+then+ship+the+model+%E2%88%91+%E2%88%87" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.kaggle.com/akhilnathreddy"><img src="https://img.shields.io/badge/Kaggle-Contributor-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" /></a>
  <a href="https://doi.org/10.5281/zenodo.24105666"><img src="https://img.shields.io/badge/Zenodo-QM9%20Curated-1682D4?style=for-the-badge&logo=zenodo&logoColor=white" alt="Zenodo DOI" /></a>
  <a href="https://www.linkedin.com/in/akhil-nath-reddy-kommuru-9510b6323/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://portfolio-tau-eight-72.vercel.app"><img src="https://img.shields.io/badge/Portfolio-0f172a?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://github.com/akhilnathreddy"><img src="https://komarev.com/ghpvc/?username=akhilnathreddy&style=for-the-badge&color=0891b2&label=PROFILE+VIEWS" alt="Profile views" /></a>
</p>

<h3 align="center">
  I'm Akhil, a machine learning engineer who loves the research side of ML.<br/>
  I build models, test them honestly, and ship them so people can use them.
</h3>

<p align="center">
  <img width="100%" src="./assets/highlights.svg" alt="Highlights: 0.90 Dice on brain tumors, 28% lower PM2.5 error, 133,885 molecules curated, 4 Kaggle competitions" />
</p>

---

## 🎯 What I Do

<table>
  <tr>
    <td width="33%" valign="top" align="center">
      <h3>🧠 Build</h3>
      Deep learning for <b>medical imaging</b>, <b>forecasting</b> and <b>molecules</b>, from raw data to a live app.
    </td>
    <td width="33%" valign="top" align="center">
      <h3>📏 Evaluate</h3>
      Leakage-free splits, strong baselines and <b>uncertainty</b>, so a score means something.
    </td>
    <td width="33%" valign="top" align="center">
      <h3>🔬 Research</h3>
      Open datasets with DOIs, <b>LLM benchmark</b> studies and <b>Kaggle</b> competitions.
    </td>
  </tr>
</table>

<p align="center">
  <img width="100%" src="./assets/workflow.svg" alt="How I work: understand, validate, model, evaluate, ship and share" />
</p>

---

## 🚀 Featured Work

| | Project | What it does | Key result | Links |
|:-:|---|---|---|---|
| 🧠 | **[Brain Tumor Segmentation](https://github.com/akhilnathreddy/brain-tumor-seg)** | Outlines brain tumors in 3D MRI scans and shows where the model is unsure | **Dice 0.90** on unseen patients | [Demo](https://brain-tumor-seg-ml.streamlit.app/) · [Weights](https://www.kaggle.com/datasets/akhilnathreddy/brats2020-unet-segmentation-weights) |
| 🌫️ | **[Delhi-NCR PM2.5 Forecaster](https://github.com/akhilnathreddy/delhi-aqi-forecast)** | Predicts air pollution 72 h ahead from stations, weather and satellite fire data | **−28% error** vs persistence | [Demo](https://delhi-aqi-forecast-ml.streamlit.app/) |
| 🧪 | **[QM9 Curated](https://github.com/akhilnathreddy/qm9-advanced-curation)** | Cleans and audits a classic quantum-chemistry dataset so benchmarks are fair | **133,885** molecules, **8** audited splits | [DOI](https://doi.org/10.5281/zenodo.24105666) · [Kaggle](https://www.kaggle.com/datasets/akhilnathreddy/qm9-curated) |
| 🤖 | **[Gemma 4 Contamination Study](https://www.kaggle.com/datasets/akhilnathreddy/gemma-4-dev-set-contamination-labels)** | Checks whether a coding-agent benchmark leaks its answers, to the model or through the sandbox | **129** tasks labelled | [Data & code](https://www.kaggle.com/datasets/akhilnathreddy/gemma-4-dev-set-contamination-labels) |
| 🤰 | **[COVID-19 & Maternal Health](https://github.com/akhilnathreddy/Pregnant_Women_COVID19)** | Analyses how pandemic stress relates to maternal mental health and birth outcomes | **10.8k** survey records cleaned | [Repo](https://github.com/akhilnathreddy/Pregnant_Women_COVID19) |

<details>
  <summary><b>🔍 More detail on each project</b></summary>
  <br/>

**🧠 Brain Tumor Segmentation (BraTS 2020)**: compares a U-Net, an Attention U-Net and a ResNet34 U-Net on a patient-level split of 369 patients. Modality dropout keeps it working when an MRI sequence is missing. The uncertainty map flags errors (AUROC 0.97). Exported to fp16 and ONNX; ~10 s per patient on CPU. Stack: PyTorch, segmentation-models-pytorch, ONNX, Streamlit.

**🌫️ Delhi-NCR PM2.5 Forecaster**: fuses 56 monitoring stations, NOAA GFS weather forecasts and VIIRS satellite fire detections. Compares LightGBM, a Temporal Fusion Transformer and a wind-aware spatio-temporal graph network built from scratch in PyTorch. Evaluated on blocked time folds and a held-out winter. Stack: PyTorch, LightGBM, Streamlit, GitHub Actions.

**🧪 QM9 Curated**: every molecule passes format, chemical-identity, physics and statistical checks and gets a quality tier with machine-readable reasons; no record is deleted. The 8 splits × 5 seeds (scaffold, isomer, ECFP cluster, size and element hold-outs, property tails) keep duplicates and tautomers on one side. `make reproduce` rebuilds the release and checks it against published SHA-256 checksums. Stack: Python, Polars, DVC, Parquet, Croissant.

**🤖 Gemma 4 Contamination Study**: a Google DeepMind Paper Track writeup separating *parametric* contamination (the model memorised the answer) from *environmental* contamination (the sandbox gives it away) across 129 public dev tasks. Labels, probe scores and a script that recomputes every headline number are public.

</details>

---

## 🏆 Kaggle

<p>
  <a href="https://www.kaggle.com/akhilnathreddy"><img src="https://img.shields.io/badge/Competitions-Contributor-20BEFF?style=flat-square&logo=kaggle&logoColor=white" /></a>
  <a href="https://www.kaggle.com/akhilnathreddy"><img src="https://img.shields.io/badge/Datasets-Contributor-20BEFF?style=flat-square&logo=kaggle&logoColor=white" /></a>
  <a href="https://www.kaggle.com/akhilnathreddy"><img src="https://img.shields.io/badge/Notebooks-Contributor-20BEFF?style=flat-square&logo=kaggle&logoColor=white" /></a>
</p>

| Status | Competition | Host | My focus |
|:-:|---|---|---|
| 🟢 | [Enveda CASMI 2026: Molecule ID From Mass Spectra](https://www.kaggle.com/competitions/enveda-CASMI26-molecule-id-mass-spectra) | Enveda | Ranking candidate molecules from mass spectra with learned scorers and ensembles |
| 🟢 | [Gemma 4 Developer Agent](https://www.kaggle.com/competitions/gemma-4-developer-agent) | Google DeepMind | Building an autonomous coding agent on Gemma 4 |
| 📄 | [Gemma 4 Developer Agent: Paper Track](https://www.kaggle.com/competitions/gemma-4-developer-agent-paper) | Google DeepMind | Research writeup on benchmark contamination |
| ✅ | [Playground S6E9: Predicting EV Purchases](https://www.kaggle.com/competitions/playground-series-s6e9) | Kaggle | Tabular binary classification (ROC AUC) |

<sub>🟢 competing now · 📄 writeup submitted · ✅ completed</sub>

**📦 Published datasets:** [QM9 Curated](https://www.kaggle.com/datasets/akhilnathreddy/qm9-curated) · [BraTS 2020 U-Net Weights](https://www.kaggle.com/datasets/akhilnathreddy/brats2020-unet-segmentation-weights) · [Gemma 4 Contamination Labels](https://www.kaggle.com/datasets/akhilnathreddy/gemma-4-dev-set-contamination-labels)

---

## 🧭 Research Interests

| Area | What I care about |
|---|---|
| 📏 **Honest evaluation** | Leakage-free splits, strong baselines, held-out seasons, patients and scaffolds |
| 🎲 **Uncertainty** | Knowing when a model is likely to be wrong |
| 🌐 **Spatio-temporal & graph ML** | Physics-aware features and GNNs for environmental forecasting |
| ⚛️ **Molecular ML** | Data quality, fair benchmarks, structure identification from spectra |
| 🤖 **LLM evaluation** | Benchmark contamination and measuring coding agents fairly |

---

## 🛠️ Tech Stack

| Area | Tools |
|---|---|
| **🧠 ML & DL** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square) ![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square) ![GNNs](https://img.shields.io/badge/Graph%20NNs-6d28d9?style=flat-square) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) |
| **📊 Data** | ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=polars&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) ![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white) ![Colab](https://img.shields.io/badge/Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white) |
| **🔁 MLOps** | ![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) |
| **📐 Maths** | ![Linear Algebra](https://img.shields.io/badge/Linear%20Algebra-1e293b?style=flat-square) ![Probability & Statistics](https://img.shields.io/badge/Probability%20%26%20Statistics-1e293b?style=flat-square) ![Optimization](https://img.shields.io/badge/Optimization-1e293b?style=flat-square) ![Calculus](https://img.shields.io/badge/Calculus-1e293b?style=flat-square) |
| **🌐 Web** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) |

<details>
  <summary><b>🌐 Web projects (where I started)</b></summary>
  <br/>

  - [Portfolio](https://github.com/akhilnathreddy/portfolio): Next.js + Three.js personal site ([live](https://portfolio-tau-eight-72.vercel.app))
  - [ConnectHub](https://github.com/akhilnathreddy/connectHub): JavaScript web app ([live](https://connect-hub-seven.vercel.app))
  - [ShopSmart](https://github.com/akhilnathreddy/shopsmart) and [Shopping Cart](https://github.com/akhilnathreddy/shoppingcart) ([live](https://shoppingcart-five-liard.vercel.app)): e-commerce apps
  - [Project CI](https://github.com/akhilnathreddy/project-ci): CI pipelines with GitHub Actions
</details>

---

## 📊 GitHub Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=akhilnathreddy&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

<p align="center">
  <img width="100%" src="https://raw.githubusercontent.com/akhilnathreddy/akhilnathreddy/output/github-snake-dark.svg" alt="Snake eating my GitHub contributions" />
</p>

---

## 🤝 Let's Connect

<p align="center">
  Open to <b>Machine Learning Engineer</b> and <b>ML research</b> roles and collaborations.<br/>
  Happy to talk about evaluation, medical imaging, forecasting, molecular ML or LLM benchmarks.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/akhil-nath-reddy-kommuru-9510b6323/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://www.kaggle.com/akhilnathreddy"><img src="https://img.shields.io/badge/Kaggle-Follow-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" /></a>
  <a href="https://portfolio-tau-eight-72.vercel.app"><img src="https://img.shields.io/badge/Portfolio-Visit-0f172a?style=for-the-badge&logo=vercel&logoColor=white" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:c026d3,50:0891b2,100:0f172a&height=120&section=footer" alt="footer" />
</p>
