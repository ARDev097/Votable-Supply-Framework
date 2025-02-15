# 📂 Dataset

The `Dataset` folder contains all the data used for analysis and predictions related to Votable Supply (VS) and Ideal Votable Supply (IVS). It is structured into multiple subfolders to categorize historical data, predicted values, and processed datasets. This document provides an overview of the structure and purpose of each dataset.

---

## 📌 Folder Structure

<details>
<summary><b>📂 Historical_Data/</b> (Click to expand)</summary>

- **Liquidity_Activity_Ratio/**
  - 📄 `LAR_Historical_Data.csv` – Historical Liquidity Activity Ratio  
  - 📄 `LAR_Raw_Data.csv` – Unprocessed Liquidity Data  

- **Actual_Voting_Power_Index/**
  - 📄 `AVPI_Historical_Data.csv` – Historical Voting Power Index  
  - 📄 `AVPI_Raw_Data.csv` – Raw Voting Power Data  

- **OP_Price/**
  - 📄 `OP_Price_Historical_Data.csv` – Historical OP Token Price  

- **Participation_Ratio/**
  - 📄 `PR_Historical_Data.csv` – Participation Ratio History  
  - 📄 `PR_Raw_Data.csv` – Raw Participation Data  

- **Circulating_Supply/**
  - 📄 `CS_Historical_Data.csv` – Historical Circulating Supply  

- **Votable_Supply/**
  - 📄 `VS_Historical_Data.csv` – Historical Votable Supply  

</details>

<details>
<summary><b>📂 Prediction_Data/</b> (Click to expand)</summary>

- **Liquidity_Activity_Ratio/**
  - 📄 `LAR_Future_Data.csv` – Predicted Liquidity Activity Ratio  

- **Actual_Voting_Power_Index/**
  - 📄 `AVPI_Future_Data.csv` – Forecasted Voting Power Index  

- **OP_Price/**
  - 📄 `OP_Price_Future_Data.csv` – Predicted OP Token Price  

- **Participation_Ratio/**
  - 📄 `PR_Future_Data.csv` – Forecasted Governance Participation  

</details>

<details>
<summary><b>📂 Future Predictions</b> (Click to expand)</summary>

- **Future_Votable_Supply/**
  - 📄 `FVS_Daywise_Data.csv` – Daywise Predicted Votable Supply  

- **Future_Circulating_Supply/**
  - 📄 `FCS_Daywise_Data.csv` – Daywise Calculated Circulating Supply  

</details>

<details>
<summary><b>📂 Ideal_Votable_Supply_Data/</b> (Click to expand)</summary>

- **All Parameters Data**
  - 📄 `All_Parameters_Historical_Data.csv` – Historical Parameters Data for IVS  
  - 📄 `All_Parameters_Future_Data.csv` – Future Parameters Predictions Data for IVS  
  - 📄 `All_Parameters_Data.csv` – Combined Data (Historical & Predicted)  

- **Weight Calculations**
  - 📂 `All_Weight_Combinations/` – Weight Variations for IVS Calculation  
  - 📄 `Ideal_Weights.csv` – Optimal Weighting Data  

- **Calculated IVS**
  - 📄 `All_Parameters_Data_with_IVS.csv` – Data Merged with Calculated IVS  
  - 📄 `Calculated_Monthly_VS_and_IVS.csv` – Monthly-Level VS & IVS  

- **Predicted IVS**
  - 📄 `IVS_Predictions.csv` – Model-Generated IVS Predictions  
  - 📄 `Predicted_Monthly_VS_and_IVS.csv` – Forecasted Monthly IVS & VS  
  - 📄 `Predicted_Quarterly_VS_and_IVS.csv` – Quarterly Predicted IVS & VS  

</details>

---

## 📂 Folder Details

### 🔹 `Historical_Data/`
This folder contains historical data for various governance metrics used in VS and IVS calculations.
.

- **Liquidity_Activity_Ratio/**  
  - `LAR_Historical_Data.csv`: Contains past values of Liquidity Activity Ratio.  
  - `LAR_Raw_Data.csv`: Unprocessed liquidity data before transformation.

- **Actual_Voting_Power_Index/**  
  - `AVPI_Historical_Data.csv`: Historical records of Actual Voting Power Index.  
  - `AVPI_Raw_Data.csv`: Raw voting power data before pre-processing.

- **OP_Price/**  
  - `OP_Price_Historical_Data.csv`: OP token historical price data.

- **Participation_Ratio/**  
  - `PR_Historical_Data.csv`: Participation Ratio history in governance activities.  
  - `PR_Raw_Data.csv`: Raw data on governance participation.

- **Circulating_Supply/**  
  - `CS_Historical_Data.csv`: Historical data on OP circulating supply.

- **Votable_Supply/**  
  - `VS_Historical_Data.csv`: Historical votable supply figures.

---

### 🔹 `Prediction_Data/`
This folder contains future predicted values for key parameters used in VS and IVS calculations.

- **Liquidity_Activity_Ratio/**  
  - `LAR_Future_Data.csv`: Predicted Liquidity Activity Ratio values.

- **Actual_Voting_Power_Index/**  
  - `AVPI_Future_Data.csv`: Forecasted values for Actual Voting Power Index.

- **OP_Price/**  
  - `OP_Price_Future_Data.csv`: Predicted OP token price trends.

- **Participation_Ratio/**  
  - `PR_Future_Data.csv`: Forecasted participation in governance.

---

### 🔹 `Future_Votable_Supply/`
- `FVS_Daywise_Data.csv`: Predicted daily votable supply values.

---

### 🔹 `Future_Circulating_Supply/`
- `FCS_Daywise_Data.csv`: Future circulating supply estimates.

---

### 🔹 `Ideal_Votable_Supply_Data/`
This folder stores datasets related to the calculation of the Ideal Votable Supply (IVS).

- **All_Parameters_Historical_Data.csv**: Combined dataset of all historical governance and liquidity parameters.  
- **All_Parameters_Future_Data.csv**: Future predictions of all key parameters.  
- **All_Parameters_Data.csv**: Consolidated dataset with both historical and future data.  
- **All_Weight_Combinations**: Contains CSV files storing various weight combinations used for IVS calculation.  
- **Ideal_Weights.csv**: Stores optimal weights determined through analysis.  

**Subfolders within Ideal_Votable_Supply_Data/**:
- **Calculated_IVS/**  
  - `All_Parameters_Data_with_IVS.csv`: Data merged with calculated IVS values.  
  - `Calculated_Monthly_VS_and_IVS.csv`: Monthly-level IVS and VS calculations.  

- **Predicted_IVS/**  
  - `IVS_Predictions.csv`: Model-generated predictions for Ideal Votable Supply.  
  - `Predicted_Monthly_VS_and_IVS.csv`: Forecasted monthly IVS and VS values.  
  - `Predicted_Quarterly_VS_and_IVS.csv`: Quarterly predicted IVS and VS values.  

---

## 📊 Usage

The datasets stored here serve as inputs for various models that predict governance-related metrics, including Votable Supply (VS) and Ideal Votable Supply (IVS). The data can be used for:

✅ **Trend analysis** of governance and participation.  

✅ **Predictive modeling** for VS and IVS.  

✅ **Evaluating the impact** of various factors on OP governance.  

---

## 📝 Notes
- The **raw data** files are kept separately in `Historical_Data/` for traceability.  
- The **processed data** is available in `Prediction_Data/` and `Ideal_Votable_Supply_Data/`.  
- Ensure to use the appropriate dataset based on whether you need **historical records** or **future predictions**.  

---
