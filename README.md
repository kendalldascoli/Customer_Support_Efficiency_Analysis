# Customer Support Efficiency Analysis

---

## Tech Stack
- **Python** – API & web scrape ETL scripts
- **SQL (PostgreSQL)** – Data modeling, analytics queries
- **AWS RDS PostgreSQL** – Cloud-hosted database
- **GitHub Actions** – CI/CD automation for ETL workflows
- **Excel** – Visualization dashboards simulating Looker reports
- **Selenium** – Web scraping automation
- **pandas & SQLAlchemy** – Data handling & database connections

---

## Project Objective
- **Who are you helping?**  
  Customer Success Teams & Support Managers for SaaS platforms like Zendesk.

- **What problem are you solving?**  
  Fragmented visibility into customer sentiment and support team efficiency.

- **How will you solve it?**  
  By automating data collection from API and web sources, transforming it into structured analytics tables, and visualizing actionable insights.

---

## Job Description
For this project, I aligned with a **Data Analyst / Data Engineer** role focused on customer support analytics. The job emphasized:
- Building ETL data pipelines
- Data modeling with SQL
- Automating workflows with GitHub Actions
- Delivering visual business insights

[Job_Description.pdf](./proposal/Job_Description.pdf)

---

## Data

### Sources:
- [JSONPlaceholder API](https://jsonplaceholder.typicode.com/) – User profiles & comments data (simulating customer interactions)
- [Trustpilot - Zendesk Reviews](https://www.trustpilot.com/review/www.zendesk.com) – Real customer feedback for sentiment analysis

### Characteristics:
- **API Data**: Structured mock user engagement data
- **Web Scraped Data**: Unstructured reviews transformed into a clean sentiment dataset

---

## Notebooks / Python Scripts

| File | Purpose |
|-------|---------|
| [`JSONPlaceholder_API_Extract_Load_Raw.ipynb`](./notebooks/JSONPlaceholder_API_Extract_Load_Raw.ipynb) | Extract & load API users & comments |
| [`JSONPlaceholder_API_SQL_Analysis.ipynb`](./notebooks/JSONPlaceholder_API_SQL_Analysis.ipynb) | SQL analytics on API engagement |
| [`customer_support_Web_Scrape_Extract_Load_Raw.ipynb`](./notebooks/customer_support_Web_Scrape_Extract_Load_Raw.ipynb) | Scrape, clean, and load Trustpilot reviews |
| [`customer_support_Web_Scrape_SQL_Analysis.ipynb`](./notebooks/customer_support_Web_Scrape_SQL_Analysis.ipynb) | Sentiment analysis queries on scraped data |
| `.github/workflows/api_pipeline.yml` | GitHub Actions workflow for API ETL |
| `.github/workflows/web_scrape_pipeline.yml` | GitHub Actions workflow for web scrape ETL |

---

## Future Improvements
- **Advanced Sentiment Analysis**: Replace simple keyword flags with NLP libraries (TextBlob, Vader) for richer insights.
- **Real-time Dashboards**: Fully integrate with Looker Studio for live monitoring instead of static Excel visuals.
"""
