# Abhinav Jain

Electrical Engineering at NSUT, graduating 2027. I build analytics and data tools, mostly SQL-first. The ones I like are the ones that answer *why* a number moved instead of just plotting that it did.

NISM Research Analyst certified, which is where most of the finance-flavoured projects come from. Currently looking at analytics, data and product roles.

**Stack:** SQL (SQL Server, Postgres) · Python (pandas, scikit-learn) · FastAPI · Power BI · PySpark · C++

---

### Causa: Automated KPI Diagnostic System

[Repo](https://github.com/abhnxvj/causa-kpi-diagnostics)

Upload a sales CSV and it investigates why revenue moved, rather than charting that it did. Change detection runs a Welch z-test across daily values instead of a fixed percentage threshold, so a 12% swing on 30 orders is treated as noise while the same swing on 30,000 orders gets flagged.

The decomposition is exact arithmetic, not a comparison of percentages, which is what lets the report say "orders explain 71% of the drop" and actually mean it. Every number in the final summary carries the SQL query behind it, with a run button.

FastAPI, PostgreSQL, Jinja2 and HTMX. The LLM only maps messy column names and writes the narrative from evidence that was already computed in SQL.

### IPO Listing Gain Predictor

[Repo](https://github.com/abhnxvj/ipo-listing-gain-predictor) · [Live](https://ipo-listing-gain-predictor.vercel.app)

Predicts listing-day gain % for Indian mainboard IPOs using only pre-listing signals: grey market premium, subscription numbers, and where the Nifty was sitting.

The honest part is the point of the project. A normal random train/test split scored R² 0.55 and that number was a lie, because the IPO market cooled sharply after 2024. Walk-forward testing (train on the past, predict forward, retrain as new IPOs arrive) brought it down to about 0.50, which is the number I actually trust. Raw GMP on its own scores R² 0.00 despite correlating at 0.52, so it has the direction right and the scale wrong. Fixing the scale is the model's whole job.

### BrickOne

[Repo](https://github.com/abhnxvj/brickone-platform) · [Live](https://brick-sigma.vercel.app)

Home loan EMI, affordability, buy-vs-rent and investment analysis in one dashboard. Built for Indian buyers who get quoted an EMI by a bank and have no way to tell whether they can actually carry it.

### OneSeat

[Repo](https://github.com/abhnxvj/oneseat) · [Live](https://oneseat.vercel.app)

JoSAA 2025 final-round closing ranks for every IIT, NIT, IIIT and GFTI, filterable by category, branch, and home-state quota. I built it because the official counselling PDFs are close to unusable when you are actually trying to fill choices.

### SQL Server Data Warehouse

[Repo](https://github.com/abhnxvj/data-warehouse)

Bronze, silver and gold layers over ERP and CRM sources. ETL and cleaning in T-SQL, star schema on top for sales, customer and product analysis.

---

Vice President at the Finance & Economics Society, NSUT. Ran finance sessions for 400+ students and headed Maudrik at Consilium'25, which grew participation 350% over the previous edition.

[LinkedIn](https://linkedin.com/in/abhinavjain0413) · abhinavjain0413@gmail.com
