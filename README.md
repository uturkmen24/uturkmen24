## 🙋‍♂️ About Me ##
---
I'm **Umut Türkmen**, a second-year **Computer Engineering & Mathematics** double major with minors in Artificial Intelligence, Data Analytics and Applied Statistics at **Koç University** (GPA: 3.75).

## 🔭 Currently

- 🎓 Second-year **Computer Engineering & Mathematics** double major at **Koç University**
- 👨‍🏫 **Undergraduate Teaching Assistant** for *COMP132: Advanced Programming* (Java & OOP)

## ⏪ Previously

- 🔬 **Summer Research Intern** at **Özyeğin University** under Prof. Dr. İrşadi Aksun, researching data science and search algorithms through applied linear algebra, using **Julia** and **Pluto.jl** notebooks
- 🏆 Joined the **Samsung Innovation Campus** AI program and built **[Plain Leaflet](https://github.com/EfeCicekdagi/plain-leaflet)** with my team at its *GenAI for SDGs Hackathon*
- 🏥 Built the bilingual (TR / EN) corporate website for **[SIMICAD](https://github.com/uturkmen24/simicad-web)**, a surgical-simulation training company (HTML, CSS, JavaScript, Firebase)
- ☕ Designed and built **Kulatro**, an object-oriented Java card game with a Swing GUI, for *COMP132: Advanced Programming*, the course I'm now a TA for
- 📈 Built an end-to-end, explainable **customer churn model** on the IBM Telco dataset with scikit-learn

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 💰 [CapiTrack](https://github.com/uturkmen24/capitrack)
**All your investments, in one place.**
A web app that brings gold, stocks, ETFs, funds, FX and deposits from different banks into one dashboard.

- Weighted-average-cost profit/loss engine
- Real return vs. inflation (Fisher equation) and a "what if it were all in deposits?" benchmark
- Step-by-step portfolio rebalancing planner and goal tracking
- Excel export, TR / EN, dark mode, privacy mode
- Auto-deployed with GitHub Actions → GitHub Pages

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=flat-square)

🔗 **[Live demo](https://uturkmen24.github.io/capitrack/?demo)**

</td>
<td width="50%" valign="top">

### 🧠 [Brain MRI Segmentation with nnU-Net](https://github.com/uturkmen24/brain-mri-segmentation-with-nnunet)
**Pixel-level LGG tumor segmentation on brain MRI.**
A custom 2D U-Net built with nnU-Net preprocessing and optimization principles.

- 3,929 MRI slices from 110 patients, patient-level 70/15/15 split (no data leakage)
- BCE + Soft Dice loss, AdamW, z-score normalization, Albumentations
- Evaluated on **17 unseen patients**

| Dice | IoU | Precision | Recall |
|:---:|:---:|:---:|:---:|
| **0.84** | **0.73** | 0.88 | 0.81 |

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📡 [Telco Customer Churn Prediction](https://github.com/uturkmen24/IBM-telco-customer-churn-prediction-by-decision-trees)
**Explainable churn prediction with decision trees.**
An end-to-end project on the IBM Telco dataset (7,043 customers) that produces business rules decision-makers can act on.

- EDA that uncovered hidden missing values and key churn drivers (contract type, fiber internet, tenure)
- White-box Decision Tree (`max_depth=4`): **79.7% test accuracy**, no overfitting
- Interactive `predict_churn()` tool that returns churn probability plus a retention recommendation

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)

</td>
<td width="50%" valign="top">

### 🃏 [Kulatro: Strategic Card Game](https://github.com/uturkmen24/Kulatro-Card-Game)
**An object-oriented Java card game with a desktop GUI.**
Built for *COMP132: Advanced Programming* at Koç University, where I'm now a Teaching Assistant.

- Login / registration, leaderboard and difficulty levels
- Three themed decks (Alchemy, Element, Quantum) with **12 special cards** such as *Schrödinger's Box* and *Photon Bet*
- Event-driven Swing UI, custom exceptions, file-based persistence and game logging
- Clean OOP design: inheritance, abstraction and polymorphism across cards, decks and players

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Swing](https://img.shields.io/badge/Swing%20GUI-5382A1?style=flat-square)
![OOP](https://img.shields.io/badge/OOP-555555?style=flat-square)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 💊 [Plain Leaflet](https://github.com/EfeCicekdagi/plain-leaflet) · 🏆 Team project, Samsung Innovation Campus GenAI for SDGs Hackathon
**Turning medicine package leaflets into plain-English, large-print cards for older adults.**
Built with my team during the *Samsung Innovation Campus* AI program, targeting **SDG 3.8** (access to safe medicines and health information) and **SDG 10.2** (inclusion of older adults).

- Upload a leaflet (PDF, photo or text) and get five simple cards: what it's for, how to take it, when to see a doctor, side effects and storage
- **Every sentence is linked to its exact source quote**, verified 3 ways (fuzzy quote matching, number checks, LLM verifier) and rewritten or removed if it fails
- Rule-based **drug interaction check** across multiple leaflets, plus read-aloud and printable cards
- Evaluated on 16 EMA / eMC leaflets: readability **49.2 → 65.1** (Flesch), **264 / 264** final quotes found verbatim in the leaflet

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![LLM](https://img.shields.io/badge/LLM%20Verification-555555?style=flat-square)

</td>
</tr>
</table>

---

## 🛠️ Languages & Tools

**Languages**

<p>
  <img src="https://skillicons.dev/icons?i=python,java,julia,js,html,css&theme=dark" alt="Languages" />
</p>

**ML / Data Science**

<p>
  <img src="https://skillicons.dev/icons?i=pytorch,sklearn&theme=dark" alt="ML tools" />
  &nbsp;
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas" height="48" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" height="48" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" height="48" />
</p>

**Web & Tools**

<p>
  <img src="https://skillicons.dev/icons?i=react,vite,tailwind,firebase,git,github,githubactions,vscode,idea&theme=dark" alt="Web and tools" />
</p>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=uturkmen24&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</div>

---

## 📫 Reach Me

<p>
  <a href="https://www.linkedin.com/in/umuturkmen/"><img src="https://img.shields.io/badge/LinkedIn-Umut%20Türkmen-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/uturkmen24"><img src="https://img.shields.io/badge/GitHub-uturkmen24-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%" alt="footer" />
