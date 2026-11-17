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

---

## 👋 About Me

I'm **Akhil**, a machine learning engineer who loves the research side of ML. I like to understand *why* a model works, test it honestly, and then ship it so people can use it.

I care most about **evaluation**. I hold out whole seasons, patients or molecular scaffolds, so a test score means something. I always compare against simple baselines. I report uncertainty, and I check that data hasn't leaked into the test set. My background in **mathematics** (linear algebra, probability & statistics, optimization) is what I lean on most.

- 🔬 **Research:** studying contamination in LLM coding-agent benchmarks (Gemma 4 Paper Track writeup)
- 🧪 **Open science:** published **[QM9 Curated](https://doi.org/10.5281/zenodo.24105666)**, a validated, split-audited quantum-chemistry dataset with a Zenodo DOI
- 🏆 **Kaggle:** Contributor in competitions, datasets and notebooks. Currently competing in **Enveda CASMI 2026** and **Google DeepMind's Gemma 4 Developer Agent**
- 🧠 **Shipped models:** 3D brain tumor segmentation and a 72-hour air-quality forecaster, both with live demos
- 🔁 **MLOps:** reproducible pipelines (DVC, `make reproduce`, SHA-256 manifests), CI with GitHub Actions, ONNX export

```python
akhil = {
    "role":       "Machine Learning Engineer",
    "research":   ["evaluation & data leakage", "uncertainty", "LLM benchmark contamination"],
    "domains":    ["medical imaging", "spatio-temporal forecasting", "molecular ML"],
    "strength":   "mathematics  # linear algebra · probability · statistics · optimization",
    "currently":  ["Enveda CASMI 2026", "Gemma 4 Developer Agent"],
    "motto":      "Understand the math, then ship the model.",
}
```

---

## 🔬 Research & Open Science

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧪 <a href="https://github.com/akhilnathreddy/qm9-advanced-curation">QM9 Curated</a></h3>
      <p><b>Published dataset · Zenodo DOI · Kaggle</b></p>
      <p>All <b>133,885</b> QM9 molecules, each run through format, chemical-identity, physics and statistical checks and given a quality tier with machine-readable reasons. Comes with <b>8 leakage-audited splits × 5 seeds</b> (scaffold, isomer, ECFP cluster, size and element hold-outs) that keep duplicates and tautomers on one side. <code>make reproduce</code> rebuilds the release from the raw archives and verifies it against published SHA-256 checksums.</p>
      <p>
        <a href="https://doi.org/10.5281/zenodo.24105666"><img src="https://img.shields.io/badge/DOI-10.5281%2Fzenodo.24105666-1682D4?style=flat-square" /></a>
        <a href="https://www.kaggle.com/datasets/akhilnathreddy/qm9-curated"><img src="https://img.shields.io/badge/Kaggle-Dataset-20BEFF?style=flat-square&logo=kaggle&logoColor=white" /></a>
        <img src="https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=polars&logoColor=white" />
        <img src="https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white" />
        <img src="https://img.shields.io/badge/License-CC0-lightgrey?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🤖 <a href="https://www.kaggle.com/datasets/akhilnathreddy/gemma-4-dev-set-contamination-labels">Gemma 4 Dev-Set Contamination</a></h3>
      <p><b>Research writeup · Google DeepMind Paper Track</b></p>
      <p>Separates <b>parametric</b> contamination (the model has memorised the answer) from <b>environmental</b> contamination (the sandbox gives the answer away) across the <b>129</b> public dev tasks of a coding-agent benchmark. Leak labels, memorisation-probe scores, baselines and a script that recomputes every headline number are all public.</p>
      <p>
        <a href="https://www.kaggle.com/datasets/akhilnathreddy/gemma-4-dev-set-contamination-labels"><img src="https://img.shields.io/badge/Kaggle-Dataset-20BEFF?style=flat-square&logo=kaggle&logoColor=white" /></a>
        <img src="https://img.shields.io/badge/LLM%20Evaluation-8E75B2?style=flat-square" />
        <img src="https://img.shields.io/badge/Coding%20Agents-0f172a?style=flat-square" />
        <img src="https://img.shields.io/badge/Reproducible-2ea44f?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

## 🚀 Featured ML Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 <a href="https://github.com/akhilnathreddy/brain-tumor-seg">Brain Tumor Segmentation</a></h3>
      <p>Segments gliomas in 3D from four MRI sequences (BraTS 2020) into whole tumor, tumor core and enhancing tumor, with volumes in mL and a per-voxel <b>uncertainty map</b>. Compares a U-Net, an Attention U-Net and a ResNet34 U-Net on a patient-level split. Modality dropout keeps it working when a scan is missing.</p>
      <p><b>Dice 0.90 / 0.83 / 0.79</b> on unseen patients · uncertainty AUROC <b>0.97</b> · weights <a href="https://www.kaggle.com/datasets/akhilnathreddy/brats2020-unet-segmentation-weights">published on Kaggle</a></p>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
        <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" />
        <img src="https://img.shields.io/badge/Medical%20imaging-0891b2?style=flat-square" />
        <a href="https://brain-tumor-seg-ml.streamlit.app/"><img src="https://img.shields.io/badge/Live%20Demo-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🌫️ <a href="https://github.com/akhilnathreddy/delhi-aqi-forecast">Delhi-NCR PM2.5 Forecaster</a></h3>
      <p>Forecasts hourly PM2.5 up to 72 hours ahead for 56 monitoring stations by fusing station data, NOAA GFS weather forecasts and VIIRS satellite fire detections. Compares LightGBM, a <b>Temporal Fusion Transformer</b> and a <b>wind-aware spatio-temporal GNN</b> built from scratch in PyTorch, evaluated on blocked time folds and a held-out winter.</p>
      <p><b>−28% MAE</b> vs persistence · 56 stations · 72 h horizon</p>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
        <img src="https://img.shields.io/badge/LightGBM-02569B?style=flat-square" />
        <img src="https://img.shields.io/badge/Graph%20NNs-6d28d9?style=flat-square" />
        <a href="https://delhi-aqi-forecast-ml.streamlit.app/"><img src="https://img.shields.io/badge/Live%20Demo-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" /></a>
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>🤰 <a href="https://github.com/akhilnathreddy/Pregnant_Women_COVID19">COVID-19 & Maternal Health Analytics</a></h3>
      <p>Cleans ~10.8k survey records from the Canadian Pregnancy during the COVID-19 Pandemic study and segments depression and anxiety scores and birth outcomes against pandemic stress, with an interactive dashboard.</p>
    </td>
  </tr>
</table>

---

## 🏆 Kaggle

<p>
  <a href="https://www.kaggle.com/akhilnathreddy"><img src="https://img.shields.io/badge/Competitions-Contributor-20BEFF?style=flat-square&logo=kaggle&logoColor=white" /></a>
  <a href="https://www.kaggle.com/akhilnathreddy"><img src="https://img.shields.io/badge/Datasets-Contributor-20BEFF?style=flat-square&logo=kaggle&logoColor=white" /></a>
  <a href="https://www.kaggle.com/akhilnathreddy"><img src="https://img.shields.io/badge/Notebooks-Contributor-20BEFF?style=flat-square&logo=kaggle&logoColor=white" /></a>
</p>

| Competition | Host | What I'm doing | Status |
|---|---|---|---|
| [Enveda CASMI 2026: Molecule ID From Mass Spectra](https://www.kaggle.com/competitions/enveda-CASMI26-molecule-id-mass-spectra) | Enveda · Featured | Ranking candidate structures for unknown molecules from mass spectra with learned scorers and ensembles | 🟢 Competing |
| [Gemma 4 Developer Agent](https://www.kaggle.com/competitions/gemma-4-developer-agent) | Google DeepMind · Featured | Building an autonomous coding agent on Gemma 4 | 🟢 Competing |
| [Gemma 4 Developer Agent: Paper Track](https://www.kaggle.com/competitions/gemma-4-developer-agent-paper) | Google DeepMind · Featured | Research writeup on dev-set contamination | 📄 Submitted |
| [Playground S6E9: Predicting EV Purchases](https://www.kaggle.com/competitions/playground-series-s6e9) | Kaggle · Playground | Tabular binary classification (ROC AUC) | ✅ Completed |

**Published datasets:** [QM9 Curated](https://www.kaggle.com/datasets/akhilnathreddy/qm9-curated) · [BraTS 2020 U-Net Weights](https://www.kaggle.com/datasets/akhilnathreddy/brats2020-unet-segmentation-weights) · [Gemma 4 Contamination Labels](https://www.kaggle.com/datasets/akhilnathreddy/gemma-4-dev-set-contamination-labels)

---

## 🧭 Research Interests

- **Honest evaluation:** leakage-free splits, strong baselines, held-out seasons, patients and scaffolds
- **Uncertainty:** knowing when a model is likely to be wrong, such as per-voxel uncertainty and prediction intervals
- **Spatio-temporal & graph learning:** physics-aware features and GNNs for environmental forecasting
- **Molecular ML:** data quality, benchmark design and structure identification from spectra
- **LLM evaluation:** benchmark contamination and how to measure coding agents fairly

---

## 🛠️ Tech Stack

**🧠 Machine Learning & Deep Learning**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Graph%20NNs-6d28d9?style=for-the-badge" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
</p>

**📊 Data & Experimentation**
<p>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=polars&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" />
  <img src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" />
</p>

**📐 Mathematics**
<p>
  <img src="https://img.shields.io/badge/Linear%20Algebra-1e293b?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Probability%20%26%20Statistics-1e293b?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Optimization-1e293b?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Calculus-1e293b?style=for-the-badge" />
</p>

**🔁 MLOps & Deployment**
<p>
  <img src="https://img.shields.io/badge/DVC-13ADC7?style=for-the-badge&logo=dvc&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" />
</p>

<details>
  <summary><b>🌐 Web development (where I started)</b></summary>
  <br/>
  <p>
    <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,tailwind,nodejs,express,mongodb,git,vercel,linux&perline=11" alt="Web tools" />
  </p>

  - [Portfolio](https://github.com/akhilnathreddy/portfolio): Next.js + Three.js personal site ([live](https://portfolio-tau-eight-72.vercel.app))
  - [ConnectHub](https://github.com/akhilnathreddy/connectHub): JavaScript web app ([live](https://connect-hub-seven.vercel.app))
  - [ShopSmart](https://github.com/akhilnathreddy/shopsmart) and [Shopping Cart](https://github.com/akhilnathreddy/shoppingcart) ([live](https://shoppingcart-five-liard.vercel.app)): e-commerce apps
  - [Project CI](https://github.com/akhilnathreddy/project-ci): CI pipelines with GitHub Actions
</details>

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=akhilnathreddy&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=akhilnathreddy&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=akhilnathreddy&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

<h3 align="center">🐍 Snake eating my contributions</h3>

<p align="center">
  <img width="100%" src="https://raw.githubusercontent.com/akhilnathreddy/akhilnathreddy/output/github-snake-dark.svg" alt="Snake eating my GitHub contributions" />
</p>

---

## 🤝 Let's Connect

<p align="center">
  Open to <b>Machine Learning Engineer</b> and <b>ML research</b> roles and collaborations.<br/>
  Happy to talk about evaluation, medical imaging, forecasting, molecular ML or LLM benchmarks.<br/>
  Find me on <a href="https://www.linkedin.com/in/akhil-nath-reddy-kommuru-9510b6323/">LinkedIn</a>, <a href="https://www.kaggle.com/akhilnathreddy">Kaggle</a> or my <a href="https://portfolio-tau-eight-72.vercel.app">portfolio</a>.
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:c026d3,50:0891b2,100:0f172a&height=120&section=footer" alt="footer" />
</p>
