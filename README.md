# TrustLens 🔍📊
*A reliability score for every number on a dashboard, with the reason it dropped.*

Built for **ExaThon India 2026** (Track 04: The Work Behind the Work).

## 💡 About the Project
Business dashboards often show conflicting numbers (e.g., a Sales dashboard vs. the Finance ledger) due to delayed pipelines[cite: 2]. Because dashboards rarely flag incomplete data, managers end up trusting and quoting flawed metrics in critical meetings[cite: 2]. 

**TrustLens** solves this by introducing:
1. **Multi-Factor Checks:** Evaluates data freshness, ledger consistency, and statistical anomalies[cite: 4].
2. **Weighted Trust Scores:** Generates a unified confidence score per metric[cite: 4, 6].
3. **Plain-English Explanations:** Uses automated lineage tracking and the Claude API to explain root causes directly to managers[cite: 5, 6].

## 📁 Submission Documents
You can view the full project architecture, mockups, and problem breakdown in the pitch deck included in this repository:
👉 [TrustLens Hackathon Deck](./TrustLens_Hackathon_Deck%20%281%29.pdf)

## 🛠️ Proposed Tech Stack
* **Check Engine:** Python & DuckDB[cite: 6]
* **Interface & Explanations:** Streamlit & Claude API[cite: 6]
