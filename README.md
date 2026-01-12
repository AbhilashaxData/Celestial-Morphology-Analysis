# 🌌 Celestial Morphology & Spectral Analysis 

## 🔭 Project Overview
This repository contains a multivariate dataset focused on the structural and spectral identification of celestial bodies, including **Stars**, **Galaxies**, and **Quasars (QSOs)**. 

The project utilizes **Astro-Informatics**, a specialized field of data science , to categorize objects based on their "spectral fingerprints" (light signals). This work is submitted as part of the **Predictive Analytics (MDTS4214)** curriculum at St. Xavier's College (Autonomous), Kolkata.

---

## 🏛️ Data Source
* **Primary Source:** Sloan Digital Sky Survey (SDSS).
   The SDSS is a major international collaboration supported by **NASA** and the National Science Foundation (NSF). 
* **Extraction Method:** Data retrieval was performed using the Astroquery API, a specialized Python library designed for programmatic access to the world’s leading astronomical databases.



## 📊 Dataset Specifications
| PARAMETER | VALUE |
| :--- | :--- |
| *Field* | Astro-Informatics and Computational Spectral Analysis |
| *Sample Size* | 800 Independent Observations |
| *Dimensions* | 11 Variables (Target, Photometric, & Engineered) |
| *Data Type* | Cross-sectional (Categorical & Numerical) |

---

## 📋 Variable Dictionary
To facilitate understanding, the variables are defined as follows:

| FEATURE | CATEGORY | DETAILS |
| :--- | :--- | :--- |
| **class** | **Target ($Y$)** | The object's identity: **GALAXY**, **STAR**, or **QSO** (Quasar). |
| **u, g, r, i, z** | **Predictors ($X$)** | Light magnitudes across 5 filters (Ultraviolet to Infrared). |
| **redshift** | **Predictor/Target** | Measures how far and how fast an object is moving away from Earth. Essential for distance estimation. |
| **u_g, g_r, r_i, i_z** | **Engineered** | Color Indices: Calculated by subtracting one filter from another (e.g., `u - g`). These ratios help the model distinguish between a "Hot Blue" object and a "Cool Red" object. |

---
## 👩‍🎓 Author
**ABHILASHA DAS**

**M.Sc. Data Science** 

**St. Xavier's College (Autonomous), Kolkata** 

*Linkedin* : [Abhilasha Das](https://www.linkedin.com/in/abhilasha-das-375a95324)

---
