# Cross-Country & Sectoral Inventory Analysis: China, Türkiye, and USA

> **Interactive Project:** [View full analysis on scdata.ai (Project #78573)](https://www.scdata.ai/project/78573)

## Executive Summary
This cross-country benchmark (China, Türkiye, USA) evaluates sectoral inventory strategies across balance sheet weight ($\frac{\text{Inventory}}{\text{Total Assets}}$), operational velocity ($DIO$), and profitability ($ROA$). Two core findings emerge:
1. **US Healthcare Paradox:** Extended holding periods ($DIO$) do not inflate balance sheet asset weight due to massive **Net Intangible Assets** dilution. Inventory serves operational stockout protection rather than working capital ($CCC$) tuning.
2. **Turkish Macro Dynamics:** Industrials and healthcare hold inventory primarily as an **inflation hedge** and a safeguard against high fixed-cost assembly line halts ($PPE$), whereas only the **IT sector** shows a direct linear link between inventory turnover and $ROA$.

---

## Analysis Steps

### 1. Sectoral Inventory Dynamics: China vs. USA

<img width="1443" alt="Sectoral Inventory Benchmark" src="https://github.com/user-attachments/assets/583ed537-b53f-4dca-990d-2bacc559b5e0" />

| Sector | Inventory / Total Assets | Inventory Days ($DIO$) | Strategic & Operational Driving Force |
| :--- | :--- | :--- | :--- |
| **Energy & Telecom** | **Negligible / Low** | **Very Low** | Capital structure is dominated by fixed assets ($PPE$) and network infrastructure rather than physical inventory stock. |
| **Industrials & IT** | **Moderate (~10%)** | **Moderate / Standard** | Inventory represents a steady ~10% of total assets, tied directly to supply chain throughput and production planning. |
| **Healthcare** | **Low-to-Moderate** | **Exceptionally High** | **The Operational Paradox:** Inventory holding periods ($DIO$) are significantly higher than all other sectors, yet inventory occupies a surprisingly small percentage of total balance sheet assets. |

---

### 1.1 Deep Dive: USA Healthcare Sector Anomaly

<img width="1456" alt="Healthcare Inventory Magnifier" src="https://github.com/user-attachments/assets/014c12ae-486b-464a-8e10-ab89a74d3c37" />

* **Balance Sheet Dilution:** The low $\frac{\text{Inventory}}{\text{Total Assets}}$ ratio in US Healthcare is an artifact of balance sheet denominator inflation. Total assets are dominated by **Net Intangible Assets** (goodwill, drug patents, proprietary biotech formulas, and clinical licenses).
* **Financial Implication:** While physical inventory stockpiles are substantial in absolute terms, their relative balance sheet weight appears minor when offset by capitalized intangible valuations.

---

### 1.2 Working Capital Independence: Safety Stock vs. Capital Allocation

<img width="1322" alt="Healthcare CCC Relationship" src="https://github.com/user-attachments/assets/2dc91da9-770d-45d2-8f8b-261470190446" />

* **Absence of Linear Correlation:** Statistical modeling indicates no meaningful linear relationship between Days Inventory Outstanding ($DIO$) and Cash Conversion Cycle ($CCC$) in the healthcare domain (a flat baseline mean models the data more accurately).
* **Operational Takeaway:** In healthcare, maintaining inventory is an **operational risk mitigation strategy** (avoiding life-critical stockouts and regulatory non-compliance) rather than an active working capital or cash optimization lever.

---

### 2. Asset Return Efficiency vs. Inventory Turnover: Turkish Market Focus

<img width="1300" alt="Türkiye ROA vs Inventory Turnover" src="https://github.com/user-attachments/assets/598f17a3-940a-4a1e-a2c1-b2fae5529aab" />

* **Sectoral Divergence:** Only the **IT sector** demonstrates a clear linear payoff between faster inventory turnover and higher $ROA$. Industrials and healthcare show no direct profitability gains from lean inventory.
* **Strategic Drivers for Holding Inventory:**
  * **Inflationary Hedging:** In high-inflation regimes with strong pricing power, holding physical stock preserves real capital value.
  * **Assembly Line Protection:** In asset-heavy manufacturing ($PPE$), the cost of an operational line shutdown far exceeds inventory carrying costs; safety stock guarantees uninterrupted throughput.

---

## Data Source & Attribution
Data processing and visual explorations were conducted via [scdata.ai](https://www.scdata.ai/).
* **Original Project Reference:** [scdata.ai Project #78573](https://www.scdata.ai/project/78573)





