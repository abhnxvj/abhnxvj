<div align="center">

<img src="./assets/profile-header.svg" alt="Abhinav Jain — data analytics, machine learning, and product engineering" width="100%" />

[Explore repositories](https://github.com/abhnxvj?tab=repositories) · [Get in touch](mailto:abhinavjain0413@gmail.com)

</div>

<div align="center">
  <a href="#at-a-glance">Overview</a> ·
  <a href="#featured-projects">Projects</a> ·
  <a href="#skills">Skills</a> ·
  <a href="#connect">Connect</a>
</div>

## At a glance

<img src="./assets/profile-dashboard.svg" alt="17 repositories (public + private), 160 contributions in the last year (public + private), and a data to product skills map" width="100%" />

**17 repositories (public + private)** · **160 contributions in the last year (public + private)**

<sub>Activity snapshot: 23 October 2026. GitHub's native contribution calendar below the README shows the live count.</sub>

## About

Electrical Engineering at NSUT, graduating 2027. I build analytics and data tools, mostly SQL-first. The ones I like are the ones that answer *why* a number moved instead of just plotting that it did.

NISM Research Analyst certified, which is where most of the finance-flavoured projects come from. Currently looking at analytics, data and product roles.

### Skills

<img src="./assets/tech-stack.svg" alt="Tech stack: SQL Server, PostgreSQL, Python, pandas, scikit-learn, PySpark, C++, FastAPI, SQLAlchemy, JavaScript, Chart.js, Supabase, Power BI, and Excel" width="100%" />

| Focus | Stack and methods |
| :--- | :--- |
| **Programming & data** | SQL (SQL Server, PostgreSQL) · Python (pandas, NumPy, scikit-learn) · PySpark · C++ · Data Structures & Algorithms |
| **Analysis & statistics** | Data analysis · Statistics · Hypothesis testing · A/B testing · Machine learning (regression, ensembles, walk-forward validation) |
| **Building & shipping** | FastAPI · SQLAlchemy · Chart.js · Supabase · Vercel and Render deployments |
| **Tools** | Power BI · Advanced Excel · Jira (Agile/Scrum) · Notion · PowerPoint for stakeholder decks · AI productivity tooling |

---

## Featured projects

<img src="./assets/project-map.svg" alt="Project map: SQL Data Warehouse, Causa, IPO Listing Gain Predictor, BrickOne, and OneSeat" width="100%" />

### Causa: Automated KPI Diagnostic System

[Repo](https://github.com/abhnxvj/automated_kpi_diagnostic_system_fastapi_sql_python)

Upload a sales CSV and it investigates why revenue moved, rather than charting that it did. Change detection runs a Welch z-test across daily values instead of a fixed percentage threshold, so a 12% swing on 30 orders is treated as noise while the same swing on 30,000 orders gets flagged.

The decomposition is exact arithmetic, not a comparison of percentages, which is what lets the report say "orders explain 71% of the drop" and actually mean it. Every number in the final summary carries the SQL query behind it, with a run button.

FastAPI and PostgreSQL. The LLM only maps messy column names and writes the narrative from evidence that was already computed in SQL.

### IPO Listing Gain Predictor

[Repo](https://github.com/abhnxvj/ipo-listing-gain-predictor)

Predicts listing-day gain % for Indian mainboard IPOs using only pre-listing signals: grey market premium, subscription numbers, and where the Nifty was sitting.

The honest part is the point of the project. A normal random train/test split scored R² 0.55 and that number was a lie, because the IPO market cooled sharply after 2024. Walk-forward testing (train on the past, predict forward, retrain as new IPOs arrive) brought it down to about 0.50, which is the number I actually trust. Raw GMP on its own scores R² 0.00 despite correlating at 0.52, so it has the direction right and the scale wrong. Fixing the scale is the model's whole job.

### BrickOne

[Repo](https://github.com/abhnxvj/brickone-platform)

Home loan EMI, affordability, buy-vs-rent and investment analysis in one dashboard. Built for Indian buyers who get quoted an EMI by a bank and have no way to tell whether they can actually carry it.

### OneSeat

[Repo](https://github.com/abhnxvj/oneseat)

JoSAA 2025 final-round closing ranks for every IIT, NIT, IIIT and GFTI, filterable by category, branch, and home-state quota. I built it because the official counselling PDFs are close to unusable when you are actually trying to fill choices.

### SQL Server Data Warehouse

[Repo](https://github.com/abhnxvj/data-warehouse)

Bronze, silver and gold layers over ERP and CRM sources. ETL and cleaning in T-SQL, star schema on top for sales, customer and product analysis.

---

<details>
<summary><strong>Leadership & collaboration</strong></summary>

Vice President at the Finance & Economics Society, NSUT. Ran finance sessions for 400+ students and headed Maudrik at Consilium'25, which grew participation 350% over the previous edition.

Team collaboration · Problem solving · Strategic thinking · Business acumen · Presentation and communication skills

</details>

### Connect

LinkedIn: abhinavjain0413 · Email: abhinavjain0413@gmail.com
