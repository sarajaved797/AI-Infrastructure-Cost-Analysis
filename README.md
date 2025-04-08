# AI-cost-analysis

Cost Justification Analysis for AI Workloads

# ⚡ Energy Cost Justification Analysis for AI Workloads

## 📌 Project Overview

This project explores cost efficiency in AI infrastructure by analyzing **fixed energy costs** against actual **usage rates**. 

The goal is to identify **underutilized regions** where money is being wasted due to low workload usage — and provide insights for **cost-saving optimizations**.

---

## 🧠 Key Concepts

### 🔹 Cost Justification

Represents the portion of fixed infrastructure costs that is justified based on usage percentage. Think of it like a **prepaid expense** — if usage is too low, part of the cost becomes waste.

### 🔹 Threshold Logic
- If **Average Usage < 70%**, some portion of base cost is considered unjustified (wasted).

- If **Average Usage ≥ 70%**, the cost is considered fully utilized.

### 🔹 % Wasted

Shows how much of the base cost is being wasted in percentage terms.

---

## 📊 Findings

### Region: **eu-west**

- **Unused Capacity**: 26.09%

- **Insight**: Significant fixed costs are being wasted due to underutilization.

- **Recommendation**: Optimize infrastructure or increase AI workloads to improve cost justification.

---

## 💡 Business Impact

- Identifies opportunities for **cloud cost optimization**.

- Highlights how infrastructure usage patterns can hide **wasted spend**.

- Enables **data-driven scaling decisions** to align cost with value.

---

## 🛠️ Tools Used

- Microsoft Excel (Pivot Tables, Conditional Logic, Charts)

-  Data Cleaning & Aggregation
  
- Manual Cost Simulation (based on usage thresholds)

---

## 🚀 Next Steps

- Scale this logic to larger datasets or cloud platforms like Snowflake.
  
- Build a dynamic dashboard version in Tableau or Looker.
  
- Apply the same logic to **revenue operations pipelines** in business environments.

---

## 📁 Project Structure

├── energy_cost_analysis.xlsx # Core workbook with calculations and results ├── README.md # Project documentation

---

### 🚧 **Limitations**

1. **Simplified Model**: The analysis assumes basic fixed costs and usage efficiency, without considering factors like maintenance or network latency.

2. **Data Input**: Only fixed infrastructure costs are analyzed; variable costs like data transfer and scaling are not included.

3. **Cost Justification Threshold**: The 70% usage threshold for "wasted" costs is arbitrary and may not apply to all use cases.

4. **Limited Forecasting**: The model doesn’t include advanced forecasting methods for future demand or costs.

### 📜 **Acknowledgements**

- Built using Excel; focuses on cost justification and optimization.

- Thanks to open-source tools and pricing calculators like AWS and Azure for cost structure insights.

---

## 🤝 Let's Connect

Feel free to reach out if you’re interested in how this logic can apply to cost optimization, forecasting, or revenue impact analytics.




