# 📊 BNM Payment Statistics – Data Collection with Python
This project demonstrates how to collect and process payment instrument statistics from the Bank Negara Malaysia (BNM) Open API. The data retrieved includes volume and value metrics for instruments like credit cards, debit cards, e-money, and online banking.

## 🧩 Project Overview
- Source: Bank Negara Malaysia (BNM) Open API
- API Endpoint: /public/payment-statistic/01-overall
- Data Type: JSON (structured API response)
- Tools Used: Python, Requests, Pandas, Google Colab
- Purpose: Demonstrate data collection and wrangling from an open API into a structured table (DataFrame)

## Result

| year_dt | month_dt | cre_crd_vol | cre_crd_val | chr_crd_vol | chr_crd_val | deb_crd_vol | deb_crd_val | emon_vol | emon_val | rentas_vol | rentas_val | intr_giro_vol | intr_giro_val | fpx_dir_deb_vol | fpx_fir_deb_val | atm_pay_trn_vol | atm_pay_trn_val | atm_cas_wit_vol | atm_cas_wit_val | mob_bnk_vol | mob_bnk_val | intr_bnk_vol_total | intr_bnk_vol_indv | intr_bnk_vol_corp | intr_bnk_val_total | intr_bnk_val_indv | intr_bnk_val_corp |
|----------|-----------|--------------|--------------|--------------|--------------|--------------|--------------|------------|------------|-------------|-------------|----------------|----------------|------------------|------------------|------------------|------------------|------------------|------------------|--------------|--------------|---------------------|---------------------|---------------------|---------------------|---------------------|---------------------|
| 2021 | 11 | 53.856006 | 13.879046022 | 0.355554 | 0.995288166 | 72.820747 | 7.791378523 | 233.604955 | 4.981008092 | 469.167 | 5359.98227403904 | 28688.497 | 125.50198518959 | 55044.385 | 25.56269381058 | 4.215558 | 4781.367533 | 66.975586 | 32574.64618 | 125.015556 | 74672.220646 | 175.053460 | 133.749029 | 41.304431 | 938.85167176 | 95.153667116 | 843.698004644 |
