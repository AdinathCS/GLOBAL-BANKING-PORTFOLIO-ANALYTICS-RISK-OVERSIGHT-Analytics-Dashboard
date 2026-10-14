# 📊 Global Banking Portfolio Analytics & Risk Oversight

A comprehensive, executive-level data analytics initiative designed to evaluate financial portfolio health, monitor credit exposure, and identify regulatory compliance gaps across an international customer base.

---

## 📌 Executive Summary

This project analyzes a dataset of **1,599 customer records** spanning **39 countries** and **7 account tiers**. By integrating key customer metrics—including Debt-to-Income (DTI) ratios, credit scores, account classifications, and Know Your Customer (KYC) verification states—this analysis provides actionable operational intelligence to optimize capital deployment, streamline AML compliance audits, and mitigate credit default risks.

---

## 🎯 Key Project Objectives

* **Solvency & Liquidity Oversight:** Evaluate balance sheet stability across global markets to ensure current asset coverage maintains a healthy liquidity ratio above the **2.0x regulatory benchmark**.
* **Credit Risk Mitigation:** Map customer leverage by plotting **Debt-to-Income (DTI > 0.40)** against **Credit Scores (< 650)** to isolate high-risk default borrower clusters.
* **AML & Compliance Governance:** Audit Know Your Customer (**KYC**) verification statuses across risk tiers to identify compliance vulnerabilities, specifically targeting pending high-risk accounts.
* **Segment & Geographic Performance:** Assess asset and liability concentration across 7 account tiers and 39 countries to guide cross-border wealth management and capital allocation strategies.

---

## 📈 Key Findings & Insights

1. **Balance Sheet Solvency:** The portfolio holds **$163.94M in total assets** against **$79.41M in liabilities**, maintaining a solid **2.06x liquidity ratio** ($116.07M assets / $54.25M liabilities in filtered operational segments).
2. **Underwriting Exposure:** While the portfolio credit score averages **706**, high default vulnerability is tightly concentrated in accounts breaching the **0.40 DTI threshold** alongside sub-650 credit scores.
3. **Regulatory Audit Exposure:** **127 High-Risk accounts** remain in **Pending KYC status**, posing immediate Anti-Money Laundering (AML) compliance exposure that requires swift administrative containment.
4. **Capital Concentration:** Assets are heavily anchored by **Premium Account holders** (~$290K average balance) and four major geographic markets:
   * 🇨🇳 **China:** $21.8M
   * 🇳🇬 **Nigeria:** $16.7M
   * 🇲🇽 **Mexico:** $14.8M
   * 🇯🇵 **Japan:** $14.2M

---

## 🛠️ Data Architecture & Schema

The underlying dataset comprises **19 feature attributes** categorized into four core domains:

| Domain | Key Attributes |
| :--- | :--- |
| **Demographics** | Full Name, Username, Age, Gender, Country, City, Account Creation Date |
| **Account Classification** | Account Tier (Premium, Business, Joint, Savings, Current, Digital-Only, Student), Account Status |
| **Financial Metrics** | Balance (USD), Debt (USD), Annual Income, Credit Score (595–845), DTI Ratio |
| **Governance & Risk** | Risk Category (High, Medium, Low), KYC Status (Verified, Pending), Fraud Flag |

---

## 🧰 Tech Stack & Tools Used

* **Business Intelligence / Data Visualization:** Tableau Desktop / Tableau Public


---

## 🚀 Strategic Recommendations

* **Enforce Credit Guardrails:** Implement automated underwriting caps and stricter lending criteria on accounts exceeding **0.40 DTI** with credit scores under **650**.
* **Remediate KYC Pipeline:** Prioritize the immediate audit and verification freeze of the **127 High-Risk pending accounts** to avoid regulatory non-compliance fines.
* **Tailored Capital Management:** Expand specialized cross-border wealth teams across top liquidity anchors (China, Nigeria, Mexico, Japan) while streamlining digital management in secondary markets.

---
<img width="1888" height="922" alt="Screenshot 2026-09-07 185024" src="https://github.com/user-attachments/assets/c50d9011-ce70-4038-9ae2-1128b90ccd35" />


## 📄 Repository Structure

```text
├── data/
│   └── global_banking_customer_data.csv    # Anonymized global customer dataset
├── sql/
│   └── portfolio_risk_queries.sql          # SQL scripts for RFM, risk, and solvency analysis
├── tableau/
│   └── Global_Banking_Risk_Dashboard.twbx  # Interactive Tableau Story / Workbook
├── docs/
│   └── Presentation_Deck.pdf               # Executive presentation slides
└── README.md                               # Project documentation


