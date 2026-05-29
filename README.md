# Supply Chain Logistics & Performance Overview

## Live Interactive Dashboard
👉 [Click Here to View the Live Interactive Dashboard]([PASTE_YOUR_COPIED_TABLEAU_PUBLIC_URL_HERE](https://public.tableau.com/shared/4DPS7CXTF?:display_count=n&:origin=viz_share_link))

## Dashboard Preview
![Dashboard Preview](dashboard_preview.jpg)

## Project Overview
This project delivers an end-to-end Business Intelligence solution using Tableau to optimize supply chain operations, financial tracking, and distribution timelines. Analyzing a dense dataset of over 180,000 logistics records, the dashboard provides executive-level visibility into systemic delivery risks, fulfillment efficiencies, and revenue generation.

## Tech Stack & Analytics Concepts
* **Visualization Engine:** Tableau Public
* **Data Layer:** DataCo Supply Chain Dataset (~180,000+ transactional records)
* **Core Analytics Techniques:** Custom Calculated Fields, Aggregate Functions, Geographic Mapping, User Interface (UI) Dashboard Sizing & Alignment, Dynamic Dashboard Filter Actions

## Key Metrics Engineered
* **Total Revenue:** Evaluates absolute financial performance across processing streams via `SUM([Sales])`.
* **Avg Shipping Delay (Days):** Pinpoints operational friction by tracking the exact discrepancy between actual transit durations and scheduled expectations via `AVG([Days for shipping (real)] - [Days for shipment (scheduled)])`.
* **Late Delivery Rate (%):** Isolates systemic logistics breakdown thresholds by calculating the precise ratio of delayed shipments via `SUM(IF [Delivery Status] = 'Late delivery' THEN 1 ELSE 0 END) / COUNT([Delivery Status])`.

## Impact & Insights Documented
* **Regional Bottleneck Isolation:** Developed high-visibility spatial mapping to identify specific regional hubs suffering from critical late delivery frequencies (surpassing a 54% baseline threshold).
* **Fulfillment Visibility:** Designed an executive summary grid that condenses high-velocity, multi-variable logistics data into actionable performance streams, reducing corporate insight retrieval time.
