Netflix Content Strategy: An Advanced Exploratory Data Analysis & Strategic Visualization
1. Project Abstract
This repository documents an in-depth Exploratory Data Analysis (EDA) and visualization project centered on the netflix_titles.csv dataset. The analysis moves beyond basic descriptive statistics to identify non-obvious strategic insights related to content acquisition, release timing, and geo-targeting. The entire workflow culminates in a professional, interactive Power BI Dashboard, providing a dynamic interface for content executives and analysts to track and evaluate platform health and global expansion strategies.

2. Core Research Objectives
The analysis was guided by specific business questions critical to a global streaming platform:

Temporal Strategy: How has the gap between a title's original release_year and its date_added to Netflix changed over time, indicating a shift between original production versus licensed catalog acquisition?

Geographic Focus: Which countries represent the most dominant, and the fastest-growing, content production hubs, and what is the relationship between production country and content rating/genre mix?

Content Segmentation: Analyze the distinct characteristics of Movies vs. TV Shows (e.g., average runtime, seasonal duration, rating distribution) to inform distinct investment models for each format.

Audience Targeting: Identify high-value and low-volume listed_in (genres) to pinpoint areas of content saturation and content scarcity, guiding future commissioning decisions.

3. Data Assets & Structure
The project utilizes the following file structure and primary data sources:

File Name	Type	Description
netflix_titles.csv	CSV Data	The principal dataset. It was subjected to rigorous data cleaning, including handling missing values in director, cast, and country, and converting date fields into appropriate datetime objects for time-series analysis.
Netflix Moveis and TV Shows Dashboard.pbix	Power BI Source	The fully developed interactive report model, including data transformations, calculated DAX measures, and drill-through capabilities.
Netflix Movies and TV Shows Dashboard - by Atharv Awasthi.png	Image	A high-resolution static preview of the final visualization, showcasing key metrics and design aesthetics.
Netflix.png	Image	Branding and asset file for the project report.

Export to Sheets

4. Advanced Methodology
The analysis was executed using best-in-class tools and techniques to ensure robustness:

Technology Stack: Python 3.10+ environment utilizing Jupyter Notebooks for reproducible research.

Statistical Libraries: Core analysis powered by Pandas for vectorized operations and data manipulation, and NumPy for numerical efficiency.

Visualization Techniques: Seaborn and Matplotlib were used for Exploratory Data Analysis (EDA), while Microsoft Power BI was employed for the final business-facing dashboard, focusing on DAX measures for dynamic period-over-period comparison.

Data Cleaning: Imputation strategies for missing values included mode imputation for categorical data (e.g., rating) and context-based imputation for director and cast (e.g., using "Unknown" to preserve row integrity while isolating uncredited titles).

5. Key Strategic Implications & Findings
The analysis yielded data-driven findings with clear business significance:

Shift to Original Content: The average time lag between content release_year and date_added has consistently decreased over the past five years, confirming a successful strategic pivot towards in-house original production and away from reliance on legacy licensed content.

Emerging Market Focus: While the USA holds the majority of titles, countries like India, South Korea, and Spain exhibit the highest CAGR (Compound Annual Growth Rate) in titles added since 2018, underscoring Netflix's investment in localized, non-English content to fuel international subscriber growth.

Content Duration Optimization: The analysis of movie runtimes shows a distribution highly skewed towards the 90-100 minute sweet spot. Conversely, TV Shows are predominantly 1-Season offerings, suggesting a calculated preference for self-contained limited series over multi-season renewals to manage production costs and mitigate risk.

Rating Distribution for Global Audience: The largest content segments are rated TV-MA and TV-14, indicating the platform's focus on adult and teen demographics, which typically have higher streaming adoption rates.

6. Call to Action: How to Engage
To fully explore and validate these findings, users are encouraged to interact with the repository:

Environment Setup: Ensure Python 3.x and the necessary libraries (pandas, numpy, seaborn) are installed.

Power BI Interaction: The complete data model and all visualizations are contained within the .pbix file. Download and open it with Microsoft Power BI Desktop to access the drill-down features and underlying DAX calculations.
