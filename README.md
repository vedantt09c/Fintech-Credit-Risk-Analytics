# Fintech-Credit-Risk-Analytics

A practical project exploring the growth of digital lending in India and building a simple credit risk model using machine learning.

# Overview
India’s fintech industry has grown rapidly, especially in digital lending.  
But one important question comes with that growth:

**Is credit risk increasing as well?**
This project tries to answer that by combining:
- Industry-level analysis (growth + default trends)
- A basic machine learning model to estimate Probability of Default (PD)
# What this project does
- Tracks fintech lending growth (2018–2023)
- Analyzes default rate trends
- Studies relationship between growth and risk
- Builds a Logistic Regression model for credit risk

# Key Findings
- Fintech lending grew at ~50% CAGR  
- Default rates peaked during COVID but stabilized  
- Growth and default risk are not strongly correlated  
- Even simple ML models can provide useful credit signals  

# Snapshot of results
- **Market Growth (CAGR):** ~50%  
- **Average Default Rate:** ~4–5%  
- **Correlation (Growth vs Default):** Weak  
- **Model ROC-AUC:** ~0.80  


# I used **Logistic Regression** to estimate Probability of Default.

### Features:
- Transaction Volume  
- Refund Rate  
- Loan Amount  

### Why this model?
- Widely used in credit risk  
- Easy to interpret  
- Works well for binary outcomes (default / no default) or simply (0,1)
