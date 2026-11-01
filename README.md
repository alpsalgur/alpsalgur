# Hi there, I'm Alp Salgür 👋

**Electrical Engineering & Computer Science Graduate**

Graduate of **Czech Technical University in Prague (ČVUT)** with a strong background in hardware-software integration, system engineering, automation, and data analysis. Experienced in real-time sensor validation, LiDAR point cloud processing, and precision instrument automation.

---

## 🛠 Tech Stack & Tools

### Programming & Scientific Computing
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-ED8B00?style=for-the-badge&logo=mathworks&logoColor=white)

### Engineering, Simulation & Platforms
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Paraview](https://img.shields.io/badge/ParaView-0B2F5C?style=for-the-badge&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sqlite&logoColor=white)

---

## 🚀 Featured Projects

### 🎯 [LidarLab](https://github.com/alpsalgur/lidarlab)
**Desktop 3D LiDAR Point Cloud Viewer, Multi-Echo Filter Pipeline & Python Scripting Environment** for frame-by-frame `.npz` test runs.
- **Real-Time 3D Playback & Split-View Inspection:** Built with **PySide6 (Qt 6)** and **VTK (PyVista)** featuring background frame pre-loading, synchronized-camera **Split View** (raw vs. filtered point clouds with removed-point highlighting), sensor-locked 3D box selection across frames, pre/post-pipeline field histograms, and a run-wide per-frame metric strip.
- **Multi-Threaded Denoising & Adverse Weather Filtering:** **12 built-in filters** with live sliders running ahead of the playhead in background threads: multi-echo filtering (cover echo & weak first-echo rain/spray removal), **SOR / ROR / DROR / DSOR / LIOR** outlier removal, **RANSAC** ground plane segmentation, and roll/pitch leveling. Removes **94–96% of rain and spray** at **93–94% precision** on labeled multi-echo datasets.
- **Zero-Copy IPython Integration & Batch CLI:** Embedded **IPython console** and script editor with zero-copy NumPy frame access, custom decorators (`@lab.step`, `@lab.filter`, `@view.highlight`), and VS Code hot-reload. Includes a multi-process CLI (`lidarlab-cli.exe`) exporting 600-frame runs (~300k pts/frame) in ~90s (**6.8 FPS**) to `.npz`, `PLY`, or `PCD`, converters for **KITTI**, **Boreas**, and **WADS**, plus a standalone Windows installer (**PyInstaller** + **Inno Setup**).
- **Tech Stack:** `Python 3.11+` · `PySide6 (Qt 6)` · `VTK / PyVista` · `IPython` · `NumPy` · `SciPy` · `PyInstaller` · `Inno Setup` · `Pytest`


### 📊 [E-Commerce Customer & Revenue Intelligence Platform](https://github.com/alpsalgur/ecommerce-customer-intelligence)
**End-to-End Business Analytics & Machine Learning Pipeline** built on the Olist Brazilian E-Commerce relational dataset (**99,441 orders**, **9 relational tables**, **R$ 15.4M+ revenue**).
- **Advanced SQL & Relational ETL:** Automated CSV-to-SQLite ETL (`SQLAlchemy`) with 6 materialized analytical/ML tables. Complex SQL using CTEs, Window Functions (`NTILE`, `FIRST_VALUE`, `PARTITION BY`), and Julian Date Arithmetic for **RFM Segmentation** (identifying **R$ 4.23M** in high-value churn exposure across 13,739 at-risk buyers), **Cohort Retention**, and **Logistics KPIs** (uncovering the **"4-Day Delivery Delay" satisfaction cliff** where ratings drop from 3.77★ to 2.32★).
- **Predictive ML & Explainable AI:** Cost-sensitive **XGBoost Detractor Classifier** (`scale_pos_weight = 6.78` on 76,658 orders) achieving **0.7537 ROC-AUC** and **53.94% Recall** purely from pre-review logistics metadata, paired with native **TreeSHAP** log-odds feature attribution (`delivery_delay_days`, `actual_shipping_days`, `item_count`).
- **Probabilistic CLV & BI Simulator:** 90-day Customer Lifetime Value (`clv_90d`) and `prob_alive` forecasting via **BG/NBD & Gamma-Gamma** (`lifetimes`), served through a containerized 3-tab **Streamlit & Plotly** executive dashboard with an interactive **Financial ROI Simulator** and automated `pytest` quality gates.
- **Tech Stack:** `Python` · `SQLite` · `SQLAlchemy` · `XGBoost` · `TreeSHAP` · `Lifetimes` · `Scikit-Learn` · `Streamlit` · `Plotly` · `Docker` · `Pytest`


### 🔬 [Power and Wavelength Automation of a Tunable Laser](https://github.com/alpsalgur/Laser-Power-Stabilization)
*Bachelor's Thesis @ Czech Technical University (Nominated for Werner von Siemens Award)*
* Developed a fully automated Python-driven feedback loop to stabilize laser power across tunable wavelengths for high-precision spectral analysis.
* Built an intuitive Tkinter GUI for real-time optical power tracking and dynamic hardware control.
* Implemented closed-loop feedback algorithms ensuring reproducible laboratory measurements.

---

## 💼 Professional Experience

### **Valeo Prague R&D Center** — *System Engineer Trainee (2024 – 2025)*
* Conducted advanced LiDAR point cloud analysis and sensor accuracy validation using Paraview, Scalaview, and BMW's LidarViewer.
* Engineered Python filtering scripts (noise suppression, echo filtering) to optimize raw point cloud pipelines.
* Developed custom Python APIs to automate workflows within the CoreALM infrastructure.

---

## 📬 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/AlpSalgür)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alp.salgur@gmail.com)
