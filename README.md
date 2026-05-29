# Supply Chain Logistics & Performance Hub

## Quick Links & Project Previews

[![Tableau](https://img.shields.io/badge/Tableau-Live_Interactive_Dashboard-blue?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/shared/4DPS7CXTF?:display_count=n&:origin=viz_share_link)

### 🖥️ Live Interactive Dashboard
👉 **[Click Here to Explore the Live Interactive Tableau Dashboard](https://public.tableau.com/shared/4DPS7CXTF?:display_count=n&:origin=viz_share_link)**

### 📸 Dashboard Interface Preview
![Supply Chain Dashboard Preview](<img width="1678" height="1208" alt="dashboard_preview" src="https://github.com/user-attachments/assets/e0ea2d88-fe02-4578-8726-530563c6f49e" />
)

---

## Project Overview
This business intelligence solution optimizes global supply chain logistics, distribution timelines, and financial metrics. Processing an enterprise-scale dataset of over **180,000 transaction records**, the dashboard delivers executive-level operational visibility, isolating systemic bottlenecks, shipping delays, and regional delivery risks to streamline decision-making.

## Tech Stack & Core Competencies
* **Analytics Engine:** Tableau Desktop / Tableau Public Cloud
* **Data Source:** DataCo Supply Chain Dataset (180,000+ rows)
* **Core Architectures:** Custom Calculated Fields, Level of Detail (LOD) Expressions, Spatial Mapping, UI/UX Floating Container Layout Design, Dynamic Filter Actions

## Analytical Metrics Engineered
* **Total Revenue:** Aggregates absolute sales performance across multi-channel distribution layers using `SUM([Sales])`.
* **Avg Shipping Delay:** Quantifies logistics efficiency thresholds by mapping the variance between real transit times and scheduled arrival targets:
  $$\text{Shipping Delay} = \text{AVG}([\text{Days for shipping (real)}] - [\text{Days for shipment (scheduled)}]))$$
* **Late Delivery Rate (%):** Isolates supply chain friction by determining the precise breakdown ratio of delayed fulfillment:
  $$\text{Late Delivery Rate} = \frac{\sum \mathbb{I}(\text{Status} = \text{'Late delivery'})}{\text{Count}(\text{Status})}$$

## Key Data Insights Documented
* **Regional Bottleneck Isolation:** Developed high-contrast geographic heat mapping that pinpointed specific fulfillment centers experiencing late delivery frequencies exceeding a critical **54% baseline threshold**.
* **Fulfillment Transparency:** Consolidated complex, multi-variable transactional arrays into a single-pane executive matrix, reducing insights retrieval latency for operational managers.
