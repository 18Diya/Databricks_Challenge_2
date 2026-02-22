
<img width="1580" height="300" alt="image" src="https://github.com/user-attachments/assets/41ce34aa-ebf7-49c1-9545-8ca65807d2fe" />


<div align="center">

# Databricks 14-Days of AI Challenge - 2

</div>

After successfully completing Challenge 1, I’m stepping into Challenge 2 with deeper focus and higher intensity. This phase pushes me to build more production-ready pipelines, strengthen core concepts, and think beyond basics.

Excited to sharpen my Databricks, Spark, and AI engineering skills through real-world implementation — learning, building, and leveling up every single day.

Grateful for the support and initiative by [Databricks,](https://databricks.com/) [Codebasics](https://codebasics.io/) and [Indian Data Club.](https://www.linkedin.com/company/indian-data-club/)

# Day 0 (20/02/26) – Setup & Data Loading  

Focused on building a strong data foundation before starting advanced engineering workflows.

What I completed:→ Configured Databricks workspace and cluster  → Set up Kaggle API credentials securely  → Created schema and managed volume for structured storage  → Downloaded and extracted the e-commerce dataset from Kaggle  → Loaded October & November 2019 data into Spark DataFrames  → Validated schema (9 columns) and verified row counts  

Setup complete. Data validated. Ready for engineering.

---

# PHASE 1: BETTER DATA ENGINEERING (Days 1–4)

# Day 1 (20/02/26) – Delta Conversion & Optimization  

Completed Day 1 of Challenge 2, focusing on production-style data engineering using Delta Lake.

What I Learned Today:→ Delta vs Parquet differences  → Small file problem in distributed systems  → Table optimization using OPTIMIZE  → Performance-first engineering mindset  

Tasks I Completed:→ Converted raw CSV data into Delta format  → Created managed Delta table  → Simulated small file problem using multiple appends  → Applied OPTIMIZE to improve table performance  

From raw data ingestion to optimized Delta tables — moving toward production-grade architecture.

<img width="1919" height="818" alt="Screenshot 2026-02-20 213229" src="https://github.com/user-attachments/assets/4b30be86-67dc-4be6-8d03-a8caf5bb93b7" />

<img width="1906" height="890" alt="Screenshot 2026-02-20 213246" src="https://github.com/user-attachments/assets/690f87d6-9496-460f-90b3-220a86bb12b5" />

# Day 2 (21/02/26) – Feature Table (Silver Layer Thinking)

Completed Day 2 focusing on production-style feature engineering and structured Silver layer design.

What I Learned Today:
→ Bronze → Silver → Gold data architecture and why layered systems matter
→ How feature engineering works in real production pipelines
→ User-level aggregation strategy for ML-ready datasets
→ Building clean, deduplicated feature tables for downstream modeling

Tasks I Completed:
→ Engineered user-level aggregated features from raw event data
→ Built a structured Silver layer feature table
→ Saved the table in Delta format for reliability and scalability
→ Validated feature quality and ensured zero duplicate user records

<img width="1919" height="857" alt="image" src="https://github.com/user-attachments/assets/319e1cc3-03fd-469e-80f7-21160c8bcf91" />

<img width="1919" height="864" alt="image" src="https://github.com/user-attachments/assets/2e8fb3b2-0eb1-49ca-ac6a-4ecfd8207040" />

<img width="1914" height="859" alt="image" src="https://github.com/user-attachments/assets/2a59f29b-cb4b-47f2-a532-2bee3995a59b" />
