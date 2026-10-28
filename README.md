# Will the Customer Accept the Coupon?

## Project Overview
This project explores the factors associated with drivers accepting or rejecting coupons delivered to their phones while driving.

## Dataset
The dataset used is coupons.csv, contains information about customers, their driving situations, and the coupons they received.
The target variable is 'Y':
- '1' - Coupon accepted
- '0' - Coupon rejected

## Analysis
The project examines coupon acceptance patterns across different coupon types and customer characteristics, including:
- Bar visits and bar-coupon acceptance
- Coffee House visits and Coffee House coupon acceptance
- Customer age and passenger characteristics
- Other factors associated with coupon acceptance

## Key Findings
The notebook contains the detailed analysis, charts, and acceptance rates.

- Approximately 56.84% of coupon observations resulted in acceptance.
- Coffee House coupon acceptance varied by customers reported visit frequency. Regular visitors had higher acceptance rates than people who never visited coffee houses.
- Bar coupon acceptance also varied by how frequently customers visited bars and by other customer and passenger characteristics.

## Recommendations

- Consider targeting regular coffee house visitors with Coffee House coupons.
- Compare acceptance rates across coupon types to identify which offers perform best.
- Evaluate customer characteristics and coupon context when designing targeted promotions.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Files
- 'prompt.ipynb' - Jupyter Notebook containing the analysis
- 'coupons.csv' - Dataset used for the analysis

## Limitations
The analysis identifies associations in the data. These patterns do not necessarily establish that a particular customer characteristic causes coupon acceptance.
