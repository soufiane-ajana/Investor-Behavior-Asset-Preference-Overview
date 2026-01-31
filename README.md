Investment Behavior Analysis Dashboard

Project Overview
This project consists of a comprehensive end-to-end data analysis of individual investment preferences and financial behaviors. Utilizing a dataset sourced from Kaggle, the primary objective was to transform raw survey responses into an interactive Business Intelligence solution that identifies key drivers behind asset selection and financial planning.

Data Source & Context
The dataset contains 40 unique observations detailing investor demographics (age, gender) and their qualitative preferences across various investment avenues such as Equity, Mutual Funds, Government Bonds, and Gold. It captures not only the "what" (asset choice) but the "why" (objectives like wealth creation, retirement, or tax benefits).

Analytical Approach & Technical Implementation
To move beyond basic reporting, several advanced Power BI techniques were implemented to ensure data integrity and deep insights:

Advanced Data Orchestration: Leveraged Power Query for sophisticated ETL processes, including a critical "Unpivot" transformation of multiple asset columns. This allowed for a consolidated comparative analysis of preference scores across all investment types within a single unified visual.

Logical Data Structuring: Resolved circular dependency issues and sorting paradoxes by implementing custom conditional logic (DAX and Power Query) to ensure chronological ordering of investment durations.

Statistical Modeling: Developed custom DAX measures, including participant distributions and weighted average preference scores, to move from simple aggregations to meaningful statistical averages.

AI-Driven Exploration: Integrated an AI Decomposition Tree to perform root-cause analysis on investment factors, allowing users to visually trace how specific objectives (e.g., Returns vs. Risk) influence demographic behaviors.

Key Insights
The Risk-Age Correlation: The analysis demonstrates a clear transition in risk appetite; younger cohorts show a higher propensity for Equity Market volatility, while older demographics pivot toward Fixed Deposits and Government Bonds for capital preservation.

Information Dominance: Digital channels (Internet) have statistically overtaken traditional advisory services as the primary source of financial information, suggesting a shift in how financial products should be marketed.

Goal-Oriented Allocation: There is a significant alignment between "Retirement Planning" and "Mutual Funds," whereas "Wealth Creation" is almost exclusively linked to Equity and aggressive growth assets.

Tools Used
Power BI Desktop: Visualization, DAX, and AI Visuals.

Power Query (M): Data cleaning and unpivoting.

Dataset: Financial data from Kaggle (CSV).

How to Use
Download the Finance_data.csv and Investment_Dashboard.pbix files.

Open the .pbix file in Power BI Desktop.

Interact with the Slicers (Gender, Source) and the Decomposition Tree to explore the data dynamically.
