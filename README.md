# Hugo Pedro — Maritime Logistics & Container Shipping Analytics

17+ years in international freight forwarding and ocean freight procurement, with operations experience in Angola, Mozambique and Brazil. I now use public port and trade data to answer the questions I used to negotiate around: who carries the boxes, how long ships wait, where the empties go, and why.

**Education:** BSc Economics • MSc Supply Chain & Purchasing Management (Audencia / Politecnico di Milano) • MBA Data Science & AI • CIPS

São Paulo, Brazil — [LinkedIn](https://www.linkedin.com/in/hugopedro/)

---

## Selected findings

From [brazil-container-flows-2025](https://github.com/hugopedro-ds/brazil-container-flows-2025), built from ANTAQ data for 2024–2025:

- **7 in 10 dry containers Brazil sends to Asia leave empty.** Dry empty exports grew 48% in 2025, almost all of it in 40-foot boxes.
- **Brazil is short of 20-foot boxes and long on 40-foot ones.** Heavy exports need 20' boxes; light imports arrive in 40'.
- **Ships spend more time waiting than working** at Brazil's main container terminals, and the second half of the year is worse every year.
- **Carrier differences are decided in the queue, not at the quay.** At the same terminal and volume, carriers and ship sizes perform almost the same at the berth; what separates them is waiting time and arrival punctuality.
- **A busy quay is not the whole story.** One terminal runs at 87% berth occupancy with short waits; another keeps its berths free most of the time and still has some of the longest waits.

---

## Projects

| Repository | What it covers |
|---|---|
| **[brazil-container-flows-2025](https://github.com/hugopedro-ds/brazil-container-flows-2025)** | Brazil's deep-sea container trade, 2024–2025: carrier mapping of 324 vessels, waiting times, berth productivity and occupancy, empty flows, box-size mismatch and carrier concentration. 14 notebooks, 18 findings, ANTAQ data. |
| **[brazil-westafrica-container-corridor](https://github.com/hugopedro-ds/brazil-westafrica-container-corridor)** | Brazil → West and Central Atlantic Africa container trade: cargo composition, geographic concentration and carrier coverage. ComexStat 2025. |
| **[brazilian-maritime-analysis-2025](https://github.com/hugopedro-ds/brazilian-maritime-analysis-2025)** | Earlier study: landed-cost framework and Brazil–China trade asymmetry. Parts were corrected in September 2026; the corrections are stated at the top of its README. |

---

## How I work

- Every project states its data sources, the checks run on them, and what the data cannot show.
- Results are compared like for like (same terminal, same month, same volume) before anything is called a difference.
- Where a finding did not hold up, the README says so.

**Tools:** Python (pandas, NumPy, SciPy, scikit-learn, matplotlib) • SQL • Power BI • Excel • Jupyter • Git

**Methods:** data validation and reconciliation • bootstrap confidence intervals • gradient boosting with out-of-sample testing • clustering • concentration indices

---

Feedback and corrections are welcome through issues on any repository.
