# AI-Driven-Market-Intelligence-Product-Data-Insights
The objective is to use AI + automation to:
- scan market/product trends,
- identify consumer search behavior,
- enrich product intelligence,
- and support product-data optimization.

# PROJECT GOAL 
Build a mini product-data intelligence system that can:
        1. assess product data quality,
        2. detect missing/inconsistent product attributes,
        3. connect product attributes with consumer search trends,
        4. produce dashboard-ready insights,
        5. recommend product-data improvements for SEO/AEO.

# datasets
use Fashion Product Images Small, 44000 products with category labels and images.
- Dataset: Fashion Product Images Small
- Use case: Product catalog, categories, attributes, images. Around 44k products, according to Kaggle.
- Source: https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small

# Tools stack
```
Python
Pandas
DuckDB or SQLite
Power BI
GitHub
Optional: n8n / Power Automate
Optional: OpenAI / Gemini later for enrichment
```
# Minimum viable stack today:
```
Python + Pandas + CSV + Power BI
```
# GitHub folder structure
```
puma-product-data-intelligence/
│
├── README.md
├── requirements.txt
├── data/
│   ├── raw/
│   ├── processed/
│   └── external/
│
├── notebooks/
│   └── 01_data_exploration.ipynb
│
├── src/
│   ├── data_quality_checks.py
│   ├── taxonomy_mapping.py
│   ├── trend_analysis.py
│   └── generate_outputs.py
│
├── outputs/
│   ├── product_quality_report.csv
│   ├── attribute_gap_report.csv
│   └── dashboard_dataset.csv
│
└── docs/
    ├── project_architecture.md
    ├── product_data_glossary.md
    └── interview_storyline.md
```
## Step 1 — Download dataset

## Step 2 — Create requirements.txt

## Step 3 — Create first data quality checks

## Step 4 — Define product data KPIs

# Product data concepts to include

# MVP business story
This project simulates how an e-commerce product data team can monitor product data quality, identify missing or inconsistent attributes, and connect product metadata with external search-interest signals to improve discoverability and conversion readiness.

# Interview value
```
Product data quality → better filters
Better filters → better product discovery
Better discovery → higher conversion potential
Market trends → better attribute strategy
AI/automation → faster enrichment and quality control
```
# Next step
Start with this command sequence:
```Bash
mkdir puma-product-data-intelligence
cd puma-product-data-intelligence

mkdir -p data/raw data/processed data/external notebooks src outputs docs

touch README.md requirements.txt
touch src/data_quality_checks.py src/taxonomy_mapping.py src/trend_analysis.py src/generate_outputs.py
touch docs/project_architecture.md docs/product_data_glossary.md docs/interview_storyline.md
```
Then download styles.csv and put it into data/raw/
Next, send me the columns from styles.csv,
# PROJECT ARCHITECTURE

```
Web Sources / Market Data
        ↓
AI Agent (ChatGPT/Gemini)
        ↓
Filtering / Classification
        ↓
Structured Product Insights
        ↓
Power BI Dashboard
```
# ANALYSIS OF THE TRENDS

- trending shoe colors,
- popular running features,
- pricing trends,
- competitor attributes,
- consumer search keywords
- attribute gap analysis
