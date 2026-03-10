# Decision Log – Monday.com Business Intelligence Agent

## 1. Key Assumptions
- The Monday.com boards for Work Orders and Deals are **read-only** for this project.  
- Column names in boards may be inconsistent or contain empty values.  
- Founder-level questions are mostly about **pipeline totals, deal counts, and operational metrics**.  

---

## 2. Trade-offs Chosen
| Feature | Decision | Reason |
|---------|---------|--------|
| API vs CSV | Used **Monday.com API** | Ensures live data instead of static CSVs |
| Column Handling | Auto-detect numeric columns | Handles messy column names and missing values |
| Language Summaries | Optional OpenAI integration | Makes output more readable and executive-friendly |
| Tech Stack | Python + Streamlit + Pandas | Simple to deploy, interactive interface |

---

## 3. What I Would Do Differently With More Time
- Add **sector or stage filtering** (e.g., filter by energy sector or proposal stage)  
- Include **visual dashboards** (charts, graphs)  
- Add **error reporting and logging** for data quality issues  
- Enhance **natural language understanding** to answer more complex questions

---

## 4. Interpretation of "Leadership Updates"
- Created optional OpenAI integration to **generate human-readable summaries** for executives  
- Summaries highlight **total deals, pipeline value, and key operational issues**  
- Focused on **concise, actionable insights** rather than raw numbers

---

## 5. Challenges Faced
- Messy Monday.com data with **empty values** and inconsistent column names  
- Need to **secure API keys** while sharing the project  
- Mapping founder-style questions to numeric results
