# Salt Lake County Procurement & Political Donations (2020–2024)

## Overview
This Open Source Intelligence project investigates the transparency of public contracting and political donations in Salt Lake County, Utah, from 2020 to 2024. By analyzing government documents, campaign finance records, and media reports, it uncovers patterns in county spending, the influence of donations on contract approvals, and gaps in transparency. Understanding these dynamics is critical for ensuring accountability in local governance and empowering residents to engage with public decision-making.

## Objectives
- Identify the top 10 contractors by total contract value and analyze the distribution of contracts across industries to reveal spending dominance.
- Examine the relationship between campaign donations and the approval of specific contracts or projects, with a focus on high-profile cases like Olympia Hills.
- Evaluate the accessibility and transparency of Salt Lake County’s procurement data, pinpointing barriers to public oversight.
- Recommend actionable improvements based on best practices from counties with exemplary transparency models, such as Madison, WI, and King County, WA.

## Methods
- **Manual Document Analysis**: Reviewed Salt Lake County’s Annual Comprehensive Financial Reports (ACFR) and Requests for Proposals (RFPs) using keyword searches and cross-referencing financial data with contract awards.
- **Data Visualization**: Built charts and graphs with Python libraries (Matplotlib v3.8.0, Seaborn v0.13.0) to illustrate spending and donation patterns.
- **Cross-Referencing**: Matched campaign finance records from the Utah Lieutenant Governor’s office with contract awards to detect potential correlations.
- **Policy Synthesis**: Compared Salt Lake County’s practices to leading transparency models in other jurisdictions.

*Note*: Data extraction from PDFs was challenging due to inconsistent formatting, and campaign finance databases lacked robust search tools, slowing analysis.

## Visualizations
- ![contract_expenditures](https://github.com/user-attachments/assets/305b6e74-41ef-434a-852e-99ccb86d45f2)
  
- ![donation_breakdown](https://github.com/user-attachments/assets/04282374-94bc-4e70-9f5e-54e7b3c5e157)

- ![top10_contractors_by_value](https://github.com/user-attachments/assets/ae22da0f-b4ab-48d7-bc4c-f1ae873dd5d4)


Additional visuals, including interactive dashboards, are in the `Presentation/` folder.

## Key Findings
- **Industry Dominance**: Over 60% of contract expenditures go to public safety and construction, with a small group of firms securing most high-value deals.
- **Olympia Hills Case**: Donations from developers tied to Olympia Hills coincided with key approvals, raising concerns about influence despite legal compliance.
- **No-Bid Contracts**: Emergency and no-bid contracts lack centralized tracking, obscuring oversight of significant spending.
- **Transparency Gaps**: Procurement data is fragmented across platforms, with no unified, searchable database for public use.

## Folder Structure
```
01_Collection/      # Raw source files (e.g., ACFR PDFs, RFP archives, media articles)
02_Processing/      # Cleaned datasets and Python notebooks for data analysis
03_Analysis/        # Research essay, visualizations, and summary of findings
04_Presentation/    # Summary slides and optional interactive dashboards
References/         # External links, citations, and archival snapshots
```

## Recommendations
- **Centralized Contract Database**: Publish a searchable database of all contracts (e.g., contractor names, values, dates) to improve public access.
- **No-Bid Disclosure**: Require public reporting of no-bid and emergency contracts within 30 days, with justifications, to enhance accountability.
- **Better Finance Tools**: Upgrade the campaign finance portal with filters (e.g., by donor industry) to aid transparency analysis.
- **Model Systems**: Adopt Madison, WI’s open contracting portal and King County, WA’s real-time dashboard as blueprints for improvement.

## Skills Demonstrated
- Public records analysis, including FOIA requests and PDF data extraction
- Data visualization and storytelling with Python (Matplotlib, Seaborn)
- Cross-referencing financial and procurement datasets for insights
- Policy synthesis and OSINT-driven reform recommendations

## Sources
- [Salt Lake County ACFR 2023](https://www.saltlakecounty.gov/globalassets/1-site-files/mayor-finance/annualfinreports/2023acfr.pdf)  
  *Detailed financial data on county contracts and expenditures.*
- [Salt Lake Tribune – Olympia Hills](https://www.sltrib.com/news/2020/02/23/campaign-donations/)  
  *Reports on donations linked to the Olympia Hills project.*
- [Salt Lake County Contracts Portal](https://www.saltlakecounty.gov/contracts/)  
  *Official portal with limited historical and search features.*

## Contact
Created by [Ben Jones] (2025) as part of an open-source civic intelligence initiative.  
Reach me at [bennywjones23@gmail.com] or visit my [GitHub profile](https://github.com/besterjoes) for questions or collaboration.
