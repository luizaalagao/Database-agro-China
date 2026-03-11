# 🌾 database-agro-China

This repository contains the data used to analyze agricultural production, family farming, and economic linkages between Brazil and China. The datasets compiled here come primarily from official Brazilian sources (IBGE and IPEA) and include information on agricultural output, family farming structure, and input–output relations.

---

## 📂 Repository Structure

/brazil_data/
│
├── NCM_n_PRODLIST_2003.csv
├── IO_TABLE_2015.xlsx
├── PAM_1998_2000.xlsx
├── FAMILY_FARMING_IBGE_2006.xlsx
├── FAMILY_FARMING_IBGE_2017.xlsx

## 📊 Data Description

### **FAMILY_FARMING_IBGE_2006.xlsx**

- **Source:** IBGE – Agricultural Census 2006  
- **Table 1109:** Number and area of agricultural establishments by land ownership and family farming condition.  
- **Variable:** *Number of agricultural establishments (units)*  
- **Coverage:** Brazil and municipalities, year 2006.
- **Filter:** *Family farming = Yes*
- **Source:** https://sidra.ibge.gov.br/tabela/1109

---
### **FAMILY_FARMING_IBGE_2017.xlsx**

- **Source:** IBGE – Agricultural Census 2017  
- **Table 6778:** Number of agricultural establishments by typology, access to electricity, land ownership, producer residence, economic activity group, and total area group.  
- **Variable:** *Number of agricultural establishments (units)*  
- **Filter:** *Family farming = Yes*
- **Source:** https://sidra.ibge.gov.br/tabela/6778
---

### **PAM_1998_2000.xlsx**

- **Source:** IBGE – Municipal Agricultural Production (PAM)  
- **Table 5457:** Planted and harvested area, production quantity, yield, and production value of temporary and permanent crops.  
- **Variable used:** *Production value (thousand BRL)*
- **Please note:** *The production value is reported in thousands of reais, in nominal terms (that is, in the currency value of each respective year).*
- **Years covered:** 1998–2000  
- **Level of aggregation:** Municipality and crop type.
- **Included crops:** https://pastebin.com/u8mF1tY3
- **Source:** https://sidra.ibge.gov.br/tabela/5457
