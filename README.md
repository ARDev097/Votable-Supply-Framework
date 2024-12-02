# **Votable Supply Framework Dataset**  

This repository contains datasets and calculated indices to analyze various metrics related to token liquidity, governance participation, price stability, and protocol activity. The data is organized into well-structured folders with clear distinctions between raw data and calculated indices for ease of reference.

---

## **Folder Structure**  

### 1. **Liquidity Activity Ratio (LAR)**  
This folder contains the liquidity activity ratio data for the top 100 tokens.  

**Formula**:  
**LAR = Volume Traded (24H) / Circulating Supply**  

#### Subfolders:  
- **`Calculated Index`**:  
  Contains CSV files for each of the top 100 tokens, providing day-wise LAR data.  
- **`Raw Data`**:  
  Contains CSV files for each of the top 100 tokens with the raw data used to calculate LAR.  

---

### 2. **Participation Ratio (PR)**  
This folder contains data on the percentage of tokens actively participating in governance (Optimism ecosystem).  

**Formula**:  
**PR = Votable Supply / Circulating Supply**  

#### Subfolders:  
- **`Calculated Index`**:  
  Contains a CSV file with day-wise PR data.  
- **`Raw Data`**:  
  Contains a CSV file with the raw data used to calculate PR.  

---

### 3. **Price Stability Index (PSI)**  
This folder contains data to measure token price fluctuations and assess stability for the top 100 tokens.  

**Formula**:  
**PSI = Average Price (7 Day) / Current Price**  

#### Subfolders:  
- **`Calculated Index`**:  
  Contains CSV files with day-wise PSI data for the top 100 tokens.  
- **`Raw Data`**:  
  - **`Historical Data`**:  
    Contains CSV files for each of the top 100 tokens with historical data used to calculate PSI.  
  - **`Latest Price`**:  
    Contains a CSV file with the latest price of the top 100 tokens as of November 30, 2024.  

---

### 4. **Top 50 Protocols OP Locked**  
This folder contains CSV files for the top 50 protocols on the Optimism mainnet. Each file contains day-wise data on OP tokens locked in a particular protocol.  

---

### 5. **Voting Power Index (VPI)**  
This folder contains data measuring how much of a token is locked in governance versus actively traded.  

**Formula**:  
**VPI = Votable Supply / Volume Traded (30D)**  

#### Subfolders:  
- **`Calculated Index`**:  
  Contains CSV files with day-wise VPI data.  
- **`Raw Data`**:  
  Contains a CSV file with the raw data used to calculate VPI.  

---
