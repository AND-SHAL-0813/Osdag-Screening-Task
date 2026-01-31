# 🌉 Osdag Structural Analysis: Bridge Grillage Visualization

![Osdag Logo](https://raw.githubusercontent.com/osdag/Osdag/master/Osdag_Logo.png)

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)
[![Library](https://img.shields.io/badge/Library-Xarray%20%7C%20Plotly-orange.svg)](https://plotly.com/python/)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Status](https://img.shields.io/badge/Status-Screening%20Task-green.svg)]()

## 📖 Project Overview
[cite_start]This repository contains the implementation of the **Osdag Screening Task** for Xarray and Plotly/PyPlot[cite: 4, 5]. [cite_start]The project automates the extraction of internal forces from structural datasets and generates high-fidelity 2D and 3D engineering diagrams[cite: 8, 9].

---

## 🚀 Features

### 🔹 Task 1: 2D SFD & BMD Analysis
- **Target:** Central longitudinal girder consisting of elements `[15, 24, 33, 42, 51, 60, 69, 78, 83]`.
- **Data Extraction:** Automated processing of $Mz$ (Bending Moment) and $Vy$ (Shear Force) using **Xarray**.
- **Visualization:** Visually pleasing 2D plots using Plotly for precise engineering analysis.

### 🔹 Task 2: 3D Multi-Girder Visualization
- **Scope:** Full bridge framing visualization for all 5 girders.
- **Style:** MIDAS-style 3D extrusion where force magnitudes are mapped to vertical height.
- **Connectivity:** Accurate mapping using node coordinates and element-node connection data.

---

## 📂 Repository Structure
```text
├── .github/                # GitHub Actions & Templates
├── data/                   # Xarray datasets (.nc / .csv) [cite: 90]
├── docs/                   
│   └── report.pdf          # Detailed technical methodology 
├── src/                    
│   ├── task1_2d_plots.py   # 2D Central Girder Logic [cite: 14]
│   └── task2_3d_plots.py   # 3D MIDAS-style Logic [cite: 213]
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```
### 📦 Supporting Files Setup

Ensure your other configuration files match the lists you provided:

**1. `requirements.txt`**
```text
xarray
plotly
pandas
numpy
netCDF4
scipy
matplotlib
```
** 2. `.gitignore`**
```text
__pycache__/
*.py[cod]
.vscode/
.idea/
*.log
.DS_Store
data/*.nc
```

## 🛠️ Installation & Setup

***1. Clone the Repository***
```text

git clone [https://github.com/AND-SHAL-0813/Osdag-Screening-Task.git](https://github.com/AND-SHAL-0813/Osdag-Screening-Task.git)
cd Osdag-Screening-Task
```

***2. Install Dependencies***
```text
pip install -r requirements.txt
```

***3. Run Analysis***
```text
python src/task1_2d_plots.py
python src/task2_3d_plots.py
```
## 📺 Deliverables

| Resource | Description | Access Link |
| :--- | :--- | :--- |
| 🎥 **Video Demonstration** | Full walkthrough of the 2D and 3D visualization functionality. | [Watch on YouTube](INSERT_YOUR_YOUTUBE_LINK_HERE) |
| 📄 **Technical Report** | Detailed documentation on Xarray processing and mapping logic. | [View PDF Document](https://github.com/AND-SHAL-0813/Osdag-Screening-Task/blob/main/Osdeg_Technical%20Report.pdf) |
| ⚖️ **Project License** | Licensed under Creative Commons Attribution-ShareAlike 4.0. | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

---

## ⚖️ License
All content in this repository is licensed under the **Creative Commons Attribution-ShareAlike 4.0 International License** by **FOSSEE**.

**Submission Note:** **osdag-admin** has been added as a collaborator for evaluation.

---

---

## 🤝 Connect with Me

I am a structural engineering enthusiast passionate about automating design workflows. Feel free to reach out for collaborations or technical discussions!

<p align="left">
  <a href="https://www.linkedin.com/in/shalini-anand0813" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" />
  </a>
  <a href="https://github.com/AND-SHAL-0813" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg" alt="GitHub" height="30" width="40" />
  </a>
</p>

---
<p align="center">
  Developed with ❤️ for the <b>Osdag Screening Task</b>
</p>




