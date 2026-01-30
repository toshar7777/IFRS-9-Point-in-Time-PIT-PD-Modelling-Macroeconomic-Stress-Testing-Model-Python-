
# IFRS 9 Point-in-Time (PIT) PD Modelling & Macroeconomic Stress Testing Model (Python)

## Project Overview

This project demonstrates the development of an **IFRS 9–aligned Point-in-Time (PIT) Probability of Default (PD) modelling framework** combined with **macroeconomic stress testing and calibration techniques**. The objective is to generate **forward-looking PD forecasts** that are suitable for **Expected Credit Loss (ECL)** estimation, **model validation**, and **regulatory credit risk assessment**.

## Objectives

* Develop a **forward-looking PIT PD framework** for retail credit portfolios
* Analyse **rating-wise PD behaviour**, default patterns, and **PD curve level and shape**
* Incorporate **macroeconomic variables** into PD estimation
* Forecast **PIT PDs over a multi-quarter horizon**
* Apply **post-model calibration techniques** aligned with IFRS 9 expectations

---

##  Methodology

### 1. Data Preparation & Exploration
* Worked on **borrower-level datasets** with multiple time snapshots
* Explored **rating-wise default rates**, PD distribution, and stability over time
* Analysed the **level and shape of the PD curve** across risk grades

### 2. TTC PD Estimation
* Implemented estimation of **long-run Through-the-Cycle (TTC) PDs** using observed defaults
* Compared **TTC PDs with realized default rates** to understand portfolio risk behaviour

### 3. Macroeconomic Stress Testing Model
* Developed a **macroeconomic regression framework** linking **default rates** to:
  * **House Price Index (HPI)**
  * **Unemployment Rate (UR)**
* Explored the sensitivity of default risk to **systematic economic drivers**

### 4. PIT PD Forecasting
* Used the macroeconomic regression model to **forecast PIT PDs for the next 10 quarters**
* Enabled **forward-looking credit risk assessment** as required under IFRS 9

### 5. PD Calibration Techniques
* Implemented **scalar calibration** to align forecasted PDs with portfolio-level risk
* Applied **log-odds shift calibration** to preserve relative risk ordering while adjusting PD levels
* Ensured calibrated PDs were suitable for **regulatory and ECL usage**

### 6. Model Validation & Risk Grading
* Used predicted PDs to assign **credit risk grades**
* Evaluated **model discriminatory power** by comparing predicted PDs with **realized defaults**
* Confirmed **rating consistency and monotonic risk ordering**

## Analytics & Outputs
* Rating-wise PD vs observed default rate comparison
* PD curve level and shape analysis
* Macroeconomic stress impact on default rates
* Forecasted PIT PD term structure
* Pre- and post-calibration PD comparison

## Key Concepts & Keywords

`IFRS 9`, `PIT PD`, `TTC PD`, `Macroeconomic Stress Testing`, `PD Calibration`, `Scalar Calibration`, `Log-Odds Shift`, `HPI`, `Unemployment Rate`, `ECL`, `Model Validation`, `Credit Risk Analytics`


## Author
**Toshar Tarte**
Credit Risk & Analytics Enthusiast

---

⭐ If you find this project useful, feel free to fork or star the repository.
