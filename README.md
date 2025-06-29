# Public Contracting and Political Donations in Salt Lake County (2020–2024): An OSINT Report

### *By Ben Jones (2025)*

*An open-source intelligence (OSINT) investigation into public accountability, transparency, and pay-to-play risks.*

---

## Executive Summary

This open-source intelligence (OSINT) report examines Salt Lake County’s public contracting and political donation landscape from **2020 to 2024**. It identifies **dominant contractors**, **regulatory shortcomings**, and **transparency gaps** in major project approvals, with a special focus on **Olympia Hills**.

Findings are based on **government documents**, **media reports**, **campaign finance disclosures**, and **industry rankings**. Over **50% of contract awards** lack publicly accessible metadata, complicating oversight.

---

## 1. Major Contractors and Dominant Industries

### Key Findings

* Top vendors include **Unified Fire Authority**, **Unified Police Department**, **Layton Construction**, and **Big-D Construction**.
* Spending is concentrated in **public safety** and **construction**.
* **Urban centers**, especially Salt Lake City, receive a disproportionate share of resources.

### Top Contractors by Expenditure (2023 ACFR)

2023 data is used as a proxy due to lack of earlier full ACFRs. Rankings appear consistent across partial records from 2020–2022.

![Top 10 Contractors](../images/top10_contractors_by_value.png)

### Private Construction Involvement

* **Layton Construction** and **Big-D Construction** consistently appear in project mentions and **ENR Intermountain rankings**.
* **Brinshore Development** and **Utah Community Action** also receive notable RFP awards.

---

## 2. Transparency Gaps: No-Bid & Emergency Contracts

### Key Observations

* No **central public log** of no-bid or emergency contracts exists.
* Likely **hundreds of small contracts** bypass competitive bidding due to thresholds.
* The county’s procurement site lacks **award-level transparency**.

### Suggested Metadata for Public Dashboards

* Award date
* Bidder list
* Bid method (open, no-bid, emergency)
* Contract amount and type
* Project location and duration

---

## 3. Political Donation Regulations & Public Perception

### Legal Framework

* Not allowed: Donations **>\$100** during contract term or within 1 year before/after.
* Allowed: Donations **< \$100**, and contracts under state/micro thresholds or emergency status.

### Case Study: Olympia Hills (2020)

* \$38,295 donated by developers to **7 of 9 Council members**.
* \$41,500 donated to **Mayor Jenny Wilson’s 2018 Senate run**.
* The project: **933-acre development** with **6,330 homes** and **1.8M sq ft** of commercial space.

![Olympia Hills Donation Breakdown](../images/donation_breakdown.png)

#### Visual Timeline (Suggested Future Addition)

* **Pre-2018**: Donations to Wilson
* **2019**: Project paused after opposition
* **2020**: Project reintroduced and approved

### Public Perception

* Regulatory loopholes (timing, donor proxies) lead to **ongoing pay-to-play suspicions** despite compliance.

---

## 4. Analysis of Contractor Donations

### Methodology

* Manual keyword review of **Salt Lake County Clerk campaign finance disclosures (2018–2024)**.
* Search terms: “Layton Construction,” “Big-D,” “David Layton.”

### Results

* No major violations of donation limits found.
* **Data fragmentation** and lack of API access limit bulk pattern analysis.

---

## 5. Contract Distribution Across Cities

### Observations

* Salt Lake City receives **most large-scale project allocations** (e.g., 600/700 North corridor).
* Insufficient data to map project funding accurately **by city**.

![Top Expenditures Chart](../images/contract_expenditures.png)


---

## 6. Recommendations

### Transparency & Oversight

* Publish **centralized contract award database** (vendor, value, method, project type).
* Create a **no-bid/emergency log** for public review.
* Offer **API access or downloadable** campaign finance datasets with **donor affiliations**.

### Investigative Priorities

* Submit **GRAMA requests** for:

  * Emergency procurement contracts
  * Bid waiver justifications
  * Memos behind major project approvals

* Expand analysis to projects like **Inland Port** and **Daybreak**.

### Comparative Models

* Examine dashboards and transparency standards in:

  * **Madison, WI**
  * **King County, WA**

* Encourage **public forums or watchdog groups** to increase local oversight.

### Visuals

![top10_contractors_by_value](https://github.com/user-attachments/assets/6a93ae0e-3e92-4b6c-bc93-f0283d5f451a)
![donation_breakdown](https://github.com/user-attachments/assets/b78af2e4-ffbc-4d97-b729-2743de8c344b)
![contract_expenditures](https://github.com/user-attachments/assets/09cd20e9-04eb-4900-ad14-7288caa739de)

---

## Notes

* **2023 ACFR** used as primary reference due to **unavailable earlier reports**.
* Campaign finance data spans **county, city, and state platforms**, requiring manual collection and cross-referencing.

---

## Glossary

| Term                | Definition                                         |
| ------------------- | -------------------------------------------------- |
| **GRAMA**           | Utah’s public records access law                   |
| **No-Bid Contract** | Awarded without competitive bidding                |
| **RFP**             | Request for Proposal – formal project solicitation |

---

## Key Sources

* *Salt Lake County ACFR (2023)*
* *Salt Lake County Contracts & Procurement Portal*
* *Utah Campaign Finance Regulations*
* *Olympia Hills Campaign Finance Reporting*
* *Salt Lake County Clerk Disclosures (2018–2024)*
* *ENR Intermountain Top Contractors List*

---

## Attribution

*Authored by **Ben Jones** (2025) as part of an OSINT portfolio project. This document aims to demonstrate real-world transparency analysis, public records navigation, and applied research for civic accountability.*
