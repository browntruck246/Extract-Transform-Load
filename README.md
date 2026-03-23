# Extract Transform Load

# 🔄 ETL: Extract • Transform • Load
ETL is a data integration workflow used to move data from one system into another—usually from raw operational sources into a clean, structured analytics environment like a data warehouse or lakehouse.

Think of it as the journey data takes to become useful.

---

# 🟦 1. Extract — Get the data out
This step pulls data from one or more sources, such as:

* Databases (SQL Server, MySQL, Oracle)
* APIs
* CSV/Excel files
* Cloud storage (S3, ADLS)
* Applications (Salesforce, Shopify, etc.)

Goal: Collect raw data as it is, without changing meaning or structure.

# 🟩 2. Transform — Clean and shape the data
This is where the magic happens. The raw data is cleaned, standardized, and prepared for analytics.

* Common transformations include:
* Removing duplicates
* Fixing data types
* Joining tables
* Filtering rows
* Aggregating (sums, averages, counts)
* Applying business rules
* Masking or encrypting sensitive data

Goal: Turn messy, inconsistent data into something accurate, structured, and analysis‑ready.

# 🟧 3. Load — Put the data where it belongs
Finally, the transformed data is loaded into a target system, such as:

* A data warehouse (Snowflake, Redshift, Synapse)
* A data lake (Databricks, S3, ADLS)
* A database
* A BI tool (Power BI, Tableau)

Goal: Make the data available for reporting, dashboards, machine learning, or downstream applications.

# 🧠 Why ETL Matters
ETL ensures that organizations:

* Make decisions based on clean, consistent data
*  Combine data from many sources into one place
* Automate data pipelines
* Support analytics, dashboards, and AI models
