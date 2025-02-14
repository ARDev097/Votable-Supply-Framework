# 🛠️ Models & Scripts  

This section contains all the **scripts and models** used for predicting governance-related parameters, **Future Votable Supply (FVS)**, and **Ideal Votable Supply (IVS)**. The models leverage **historical data, feature engineering techniques, and predictive modeling** to generate accurate forecasts.  

---

## 📂 Folder Structure  

```plaintext
Models_and_Scripts/
├── Parameters_Prediction/
│   ├── LAR_Prediction.ipynb
│   ├── AVPI_Prediction.ipynb
│   ├── OP_Price_Prediction.ipynb
│   └── PR_Calculation.ipynb
│
├── Future_Votable_Supply/
│   └── FVS_Prediction.ipynb
│
└── Ideal_Votable_Supply_Scripts/
    ├── 01_calculate_indexes.ipynb
    ├── 02_prepare_historical_data.ipynb
    ├── 03_calculate_future_circulating_supply.ipynb
    ├── 04_prepare_future_data.ipynb
    ├── 05_merge_and_scale_data.ipynb
    ├── 06_generate_weight_combinations.ipynb
    ├── 07_calculate_IVS_all_weight_combinations.ipynb
    ├── 08_find_ideal_weights.ipynb
    ├── 09_calculate_final_IVS.ipynb
    └── 10_predict_IVS.ipynb
```
---

## 🔍 Detailed Explanation  

### 🏗️ **1. Parameters Prediction** (`Parameters_Prediction/`)  

This section includes models designed to predict key **governance-related parameters**, which act as inputs for votable supply and Ideal votable supply calculations.  

| 📄 File | 🔍 Purpose |
|---------|----------|
| `LAR_Prediction.ipynb` | Predicts **Liquidity Activity Ratio (LAR)** using historical trends. |
| `AVPI_Prediction.ipynb` | Estimates **Actual Voting Power Index (AVPI)** based on past governance activities. |
| `OP_Price_Prediction.ipynb` | Forecasts **OP token price** using LSTM models. |
| `PR_Calculation.ipynb` | Computes **Participation Rate (PR)** from predicted votable supply (VS) and circulating supply (CS). |

---

### 🔮 **2. Future Votable Supply Prediction** (`Future_Votable_Supply/`)  

This section focuses on **forecasting Future Votable Supply (FVS)** using multiple inputs such as historical votable supply, historical circulating supply, historical OP price and future circulating supply data.  

| 📄 File | 🔍 Purpose |
|---------|----------|
| `FVS_Prediction.ipynb` | Predicts **Future Votable Supply (FVS)** using Long Short Term Memory (LSTM) model. |

---

### 🎯 **3. Ideal Votable Supply Computation** (`Ideal_Votable_Supply_Scripts/`)  

This section contains scripts that systematically compute **Ideal Votable Supply (IVS)** through **data transformation, feature engineering, and weighted optimization techniques**.  

| 📄 File | 🔍 Purpose |
|---------|----------|
| `01_calculate_indexes.ipynb` | Computes various **governance indexes** used for IVS analysis. |
| `02_prepare_historical_data.ipynb` | Prepares **historical governance data** to establish baseline trends. |
| `03_calculate_future_circulating_supply.ipynb` | Predicts **Future Circulating Supply (FCS)** using ML model. |
| `04_prepare_future_data.ipynb` | Creates structured **future datasets** for IVS modeling. |
| `05_merge_and_scale_data.ipynb` | Standardizes and **scales data** for consistency across models. |
| `06_generate_weight_combinations.ipynb` | Generates **multiple weight combinations** to optimize IVS calculation. |
| `07_calculate_IVS_all_weight_combinations.ipynb` | Computes IVS for all **possible weight configurations**. |
| `08_find_ideal_weights.ipynb` | Identifies **optimal weight factors** for IVS estimation. |
| `09_calculate_final_IVS.ipynb` | Computes the **final Ideal Votable Supply (IVS)** using optimized parameters. |
| `10_predict_IVS.ipynb` | Forecasts IVS for **upcoming governance cycles**. |

---

## 📊 Key Features  

✔ **Comprehensive modeling approach** – Includes LAR, AVPI, OP price, PR, and votable supply predictions.  
✔ **Future governance forecasting** – Uses **machine learning** and **statistical methods** to estimate FVS and IVS.  
✔ **Optimized IVS computation** – Evaluates multiple **weight combinations** to determine the best possible IVS prediction.  
✔ **Data standardization and preprocessing** – Ensures accurate and reliable forecasting.  

---

