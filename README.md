# Search Query Waste Detector
Manually reviewing hundreds of search terms can be time-consuming. This is a python-based project that identifies potentially inefficient search terms in paid search campaigns and prioritizes them for review. 
(analyze search term performance, identify possible wasted spend, and highlight queries that may need optimization.)

# Dataset
A synthetic (Google Ads style) dataset containing 20 CRM-related keywords, 200 search terms (10 per keyword), impressions, clicks, cost, and conversions. 

# What the project does is:
- Cleans and validates the search term data.
- Calculates CTR, CPC, CVR, and CPL.
- Flags queries with high spend, low CVR, or high CPL.
- Identifies potential search intent mismatches.
- Assigns a Waste Risk Score (0-100) to prioritize queries for review.
- Exports a flagged search term report and visualizations.

# Tools used
Python, Pandas, NumPy, Matplotlib, and Google Colab

# Output
- Prioritized search term report (CSV format)
- Spend by review priority chart
- Cost vs. conversions chart

# Limitations
This project uses synthetic data. The Waste Risk Score is a rule-based prioritization method, not a definitive measure of wasted spend. Flagged queries require manual review before making any optimization decisions. 

# Workflow
- Data loading > cells 1 - 3
- Data exploration and validation > cells 4 - 13
- Data cleaning and metric calculation > cells 14 - 23
- Account performance benchmarks > cells 24 - 26
- Exploratory performance analysis > cells 27 - 38
- Waste detection and risk scoring > cells 39 - 46
- Reporting and visualization > cells 47 - 49
- Final validation > cell 50
