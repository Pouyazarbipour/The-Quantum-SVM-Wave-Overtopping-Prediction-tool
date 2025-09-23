# The Quantum SVM Wave Overtopping Prediction Tool

Welcome to the **Quantum SVM Wave Overtopping Prediction Tool**, a cutting-edge desktop application leveraging quantum machine learning (QML) and the CLASH database. This standalone executable delivers highly accurate predictions of average wave overtopping discharge for coastal structures, utilizing quantum-enhanced algorithms to process complex hydrodynamic and structural interactions.

![Main Page GUI](https://raw.githubusercontent.com/Pouyazarbipour/The-Quantum-SVM-Wave-Overtopping-Prediction-tool/main/GUI%20pic/main_page.JPG)

## Overview
This project employs a quantum machine learning model, built on the CLASH database, to predict the average wave overtopping discharge (`q`) for coastal structures. The model integrates quantum computing principles to enhance predictive performance, achieving an **R² of 0.97** for both training and testing datasets. The dataset is split into **70% training**, **15% validation**, and **15% testing**.

For further details, refer to [Zarbipour et al. (2026)](https://doi.org/10.1016/j.oceaneng.2024.119465).

## Data Range and Parameters
The model uses the following input parameters from the CLASH database:

- **Output Parameter**:
  - **Average wave overtopping discharge (*q*)**: [m³/s/m]

- **Input Parameters**:
  - **Wave attack angle (beta)**: [°]
  - **Spectral significant wave height at toe (Hm0)**: [m]
  - **Water depth at toe (h)**: [m]
  - **Spectral wave period at toe (Tm-1,0_toe)**: [s]
  - **Toe structure width (Bt)**: [m]
  - **Water depth over toe structure (ht)**: [m]
  - **Structure surface roughness factor (Gamma_f)**: [-]
  - **Cotangent of the lower slope (cotad)**: [-]
  - **Cotangent of the upper slope (cotau)**: [-]
  - **Water depth over berm (hb)**: [m]
  - **Crest freeboard (Rc)**: [m]
  - **Berm width (B)**: [m]
  - **Tangent of berm slope (tanB)**: [-]
  - **Armour crest freeboard (Ac)**: [m]
  - **Crest width (Gc)**: [m]

## Model and Prediction Approach
The quantum machine learning model utilizes quantum circuits to enhance feature mapping and capture non-linear relationships in the CLASH dataset with unprecedented efficiency. Unlike classical models, the QML approach leverages **quantum superposition** and **entanglement** to process high-dimensional data, making it ideal for complex coastal engineering problems. The model employs a **variational quantum classifier** optimized for regression tasks.

To quantify prediction uncertainty, a **quantum Monte Carlo sampling method** is used, generating multiple quantum state predictions. The standard deviation of these predictions provides variability estimates, with a **95% confidence interval** calculated as `prediction ± 1.96 × standard deviation`. An upper-bound prediction (`prediction + standard deviation`) is provided for conservative design, corresponding to approximately the **84th percentile**.

For detailed instructions, refer to [Zarbipour et al., 2026](https://doi.org/10.1016/j.oceaneng.2024.119465).

## Downloads
- [Download for Windows (.exe)](https://drive.google.com/file/d/1WudjNT1_ua1YdLUYzoj-hfeU3nU5h1i8/view?usp=sharing)
- [Download for macOS (.dmg)](https://drive.google.com/file/d/1WudjNT1_ua1YdLUYzoj-hfeU3nU5h1i8/view?usp=sharing)
- [User & Technical Manual](https://drive.google.com/file/d/1WudjNT1_ua1YdLUYzoj-hfeU3nU5h1i8/view?usp=sharing)

## About
Developed by **Pouya Zarbipour**. For inquiries or feedback, contact [pouyazarbipour@gmail.com](mailto:pouyazarbipour@gmail.com).

## Disclaimer
This tool aims to enhance the prediction of wave overtopping for coastal structure design. Users should consult the [User & Technical Manual](https://doi.org/10.1016/j.oceaneng.2024.119465) for details on intended use, limitations, and quantum computing requirements.
