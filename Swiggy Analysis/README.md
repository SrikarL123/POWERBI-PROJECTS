
---

📊 **Swiggy Restaurant Analysis – Power BI Dashboard**

🔹 **Problem It Solves**

Analyzing hundreds of restaurants across Mumbai's food delivery ecosystem is impossible with raw CSV data alone:

- **Messy Raw Data** – Ratings, delivery times, and offer details were inconsistently formatted, mixed with null values and corrupt entries, making direct analysis unreliable.
- **No Cuisine Visibility** – Understanding which food categories dominate the platform requires aggregation that spreadsheets can't easily provide.
- **Hidden Patterns** – Relationships between delivery speed, ratings, and discount offers are invisible without visual cross-filtering.

This dashboard solves these by cleaning and transforming 1,749 Swiggy restaurant records into an interactive, filter-driven visual summary.

🔹 **Key Insights from the Dashboard**

- **Restaurant KPIs** → Instantly view Total Restaurants (1,729), Average Rating (4.13), Avg Delivery Time (42.10 mins), and % With Offers.
- **Rating Breakdown** → The donut chart shows that 44.25% of restaurants fall in the Good (4.0–4.4) range, while 19.61% are Unrated — a data quality signal worth noting.
- **Delivery Speed Distribution** → The majority of restaurants fall in the Slow (>30 min) category, revealing a platform-wide delivery challenge.
- **Top Cuisines** → Indian, Chinese, and North Indian dominate as the most listed primary cuisines across all locations.
- **Rating vs Delivery Time** → The scatter plot reveals no strong correlation between faster delivery and higher ratings — quality matters more than speed.
- **Location Insights** → The top locations bar chart highlights which Mumbai suburbs have the highest average-rated restaurants.

🔹 **Why It's Useful**

- **Food Entrepreneurs** can identify which cuisines are oversaturated and where gaps exist in the market.
- **Swiggy Partners** can benchmark their ratings and delivery times against area averages.
- **Data Analysts** can see a real-world example of cleaning messy scraped data before visualization.
- **Recruiters / Reviewers** can interact with each Rating Category filter to see how the dashboard dynamically responds.

🔹 **Files Included in this Repository**

- **Swiggy_report.pbix** → The original, interactive Power BI report file.
- **Swiggy_Analysis.pdf** → Exported static version of the dashboard for quick preview.
- **Swiggy_Analysis.png** → Screenshot of the full dashboard.
- **swiggy_powerbi_ready.csv** → The cleaned and feature-engineered dataset used to build the dashboard (includes `primary_cuisine`, `delivery_speed`, `rating_category`, `has_offer` columns).
- **swiggy_cleaned.csv** → The original raw dataset before cleaning, for reference.

---
