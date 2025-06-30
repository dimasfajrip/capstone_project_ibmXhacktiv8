# Housing Price Analysis in Surabaya Using IBM Granite LLM

## 📌 Project Overview

This capstone project explores publicly available housing property data from Surabaya, Indonesia, to identify the key factors influencing property prices. Leveraging IBM Granite LLM (`granite-3.3-8b-instruct`) via Replicate, the project uses AI to interpret descriptive statistics, uncover correlations, detect anomalies, and produce actionable recommendations for different stakeholders such as homebuyers, developers, and investors. The goal is to convert raw housing data into valuable insights that aid better decision-making in real estate.

---

## 📂 Dataset

**Raw Dataset Link**  
[dataset_baru.csv](https://raw.githubusercontent.com/dimasfajrip/capstone_project_ibmXhacktiv8/main/dataset_baru.csv)
**Raw Dataset Clean Link**
[dataset_new_clean.csv](https://raw.githubusercontent.com/dimasfajrip/capstone_project_ibmXhacktiv8/main/dataset_new_clean.csv)
---

## 🔍 Insight & Findings

### 1. Descriptive Summary
- The average house price in Surabaya is ~IDR 3.34 billion with wide variation (min ~IDR 16 million, max ~IDR 105 billion).
- Most homes have 3–4 bedrooms and 2–3 bathrooms, suggesting suitability for medium to large families.
- Amenities like kitchen set (84%), internet (97%), and bathtub (63%) are widely available, while features like gym and jogging track are less common.

### 2. Correlation Analysis
- Strongest influence on price:
  - Land area (corr: 0.68)
  - Building area (0.50)
  - Price per m² (0.56)
  - Number of bathrooms (0.35)
  - Electricity availability (0.33)
- Some amenities (e.g., microwave, gym) show slight negative correlations, indicating possible oversupply or limited buyer interest.

### 3. Outlier Explanation
- Small houses with high prices are likely located in premium areas, have custom architecture, or are historically significant properties.
- These outliers are identifiable via visual inspection or machine learning residual analysis.

### 4. Regional Price Disparity
- Areas like Gayungan have higher average prices than districts like Sawahan due to better access to infrastructure, lifestyle amenities, and proximity to central business areas.

### 5. Key Drivers of Price
- Building size (corr: 0.78), number of bathrooms (0.65), and carport presence (0.59) are the top contributors.
- Tambaksari district has the highest average property prices.

### 6. Stakeholder Recommendations
- **Developers:** Focus on affordable housing in growing suburbs; add sustainable features.
- **Buyers:** Explore suburban districts like Mojokerto and Blitar; take advantage of government subsidies.
- **Investors:** Target areas with development potential and demand for rentals near universities or industrial zones.

### 7. Market Segmentation
- **Low-end:** < IDR 150 million (1–2 bedrooms, limited amenities)
- **Mid-range:** IDR 150–300 million (2–3 bedrooms, moderate amenities)
- **High-end:** > IDR 300 million (3+ bedrooms, luxury features)

### 8. What-if Analysis
- Adding a swimming pool and kitchen set to a two-bedroom home may increase value by ~USD 42,000, combining lifestyle appeal and modern facilities.

---

## 🤖 AI Support Explanation

### AI Model:
- **IBM Granite 3.3-8B Instruct (via Replicate)**

### AI Roles in This Project:
1. **Descriptive Summarization:** The LLM translated raw statistics into readable summaries.
2. **Correlation Interpretation:** It extracted insights from numerical correlation matrices.
3. **Anomaly Detection:** The model explained why smaller houses can have disproportionately higher prices.
4. **Comparative Reasoning:** Analyzed price gaps between districts using logic and market context.
5. **Simulation (What-If):** Estimated price shifts based on added features like pools or kitchen sets.
6. **Stakeholder-Specific Insights:** Generated tailored recommendations for developers, buyers, and investors.
7. **Market Segmentation:** Classified properties into distinct pricing tiers based on quantitative features.

### Benefits of Using LLM:
- Streamlined complex analysis without traditional machine learning pipelines.
- Reduced time to insight with human-like interpretation of raw numbers.
- Enabled creative scenario simulation and stakeholder-focused reasoning.

---

## ✅ Conclusion

The Surabaya housing market shows a rich mix of property types, price segments, and consumer needs. By using IBM Granite LLM, this project was able to convert complex real estate data into actionable insights, revealing that property prices are most heavily influenced by land and building size, with secondary effects from bathrooms and key amenities. Regional disparities highlight the need for location-specific strategies, while AI-enabled interpretation paves the way for faster, data-driven real estate planning.

---

