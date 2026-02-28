
<img width="1580" height="300" alt="image" src="https://github.com/user-attachments/assets/41ce34aa-ebf7-49c1-9545-8ca65807d2fe" />


<div align="center">

# Databricks 14-Days of AI Challenge - 2

</div>

After successfully completing Challenge 1, I’m stepping into Challenge 2 with deeper focus and higher intensity. This phase pushes me to build more production-ready pipelines, strengthen core concepts, and think beyond basics.

Excited to sharpen my Databricks, Spark, and AI engineering skills through real-world implementation — learning, building, and leveling up every single day.

Grateful for the support and initiative by [Databricks,](https://databricks.com/) [Codebasics](https://codebasics.io/) and [Indian Data Club.](https://www.linkedin.com/company/indian-data-club/)

# Day 0 – Setup & Data Loading  

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

# Day 3 (22/02/26) –  Job Orchestration Basics

Completed Day 3 focusing on production-grade job orchestration and automation in Databricks.

What I Learned Today:
→ Difference between interactive notebooks and production jobs
→ How parameterized notebooks enable reusable, environment-driven pipelines
→ Basic job scheduling for automated daily execution
→ Structuring modular code for scalable data workflows

Tasks I Completed:
→ Added widget parameters to control notebook execution dynamically
→ Modularized feature engineering logic into clean reusable functions
→ Created a production Job in Databricks UI
→ Configured a daily scheduled run for automated pipeline execution

<img width="1918" height="885" alt="Screenshot 2026-02-22 121030" src="https://github.com/user-attachments/assets/3792c1c6-2ef7-4236-96cc-38b598a78c84" />

<img width="1919" height="805" alt="Screenshot 2026-02-22 121050" src="https://github.com/user-attachments/assets/83e97d2a-82e3-4cbc-be5a-4cf8641edd00" />

<img width="1919" height="746" alt="Screenshot 2026-02-22 120953" src="https://github.com/user-attachments/assets/c2691020-ce01-40a2-8f86-ff7fb2ef03a1" />

# Day 4 (23/02/26) – Structured Streaming (Basic Simulation)

Completed Day 4 focusing on real-time data processing and streaming architecture in Databricks.

What I Learned Today:
→ How micro-batch processing works in Structured Streaming
→ The role of checkpointing in fault tolerance and recovery
→ Writing streaming outputs directly into Delta tables
→ How streaming pipelines differ from batch workflows

Tasks I Completed:
→ Simulated streaming ingestion from a folder source
→ Configured checkpointing for reliable state management
→ Wrote streaming aggregation output to a Delta table
→ Queried and validated streaming results using Spark SQL

<img width="1290" height="866" alt="image" src="https://github.com/user-attachments/assets/b61282af-8017-45ce-8791-f05a9bf82c19" />

<img width="1167" height="853" alt="image" src="https://github.com/user-attachments/assets/d35f978b-ceb6-4610-9d41-a34faebc51c7" />

<img width="1011" height="221" alt="image" src="https://github.com/user-attachments/assets/37756904-546f-4bac-935d-77ed82bab4d2" />

# Day 5 (24/02/26) – Production-Grade Feature Engineering

Completed Day 5 focusing on building clean, model-ready datasets for machine learning.

What I Learned Today:
→ How to create binary classification targets from raw event data
→ Joining engineered feature tables with target labels
→ Proper train-test splitting strategies
→ Detecting and validating class imbalance in datasets

Tasks I Completed:
→ Created a binary purchase label from event-level data
→ Joined label data with silver feature tables
→ Split dataset into training and testing sets
→ Validated label distribution across both splits

<img width="1145" height="652" alt="image" src="https://github.com/user-attachments/assets/bb60dbe2-d8ea-403b-aff2-a30ef77afe1b" />

<img width="1145" height="893" alt="image" src="https://github.com/user-attachments/assets/e51f8188-2809-4253-9f51-67b1e0dfca5e" />

<img width="1148" height="883" alt="image" src="https://github.com/user-attachments/assets/4a20aeed-dcd4-41ec-aac2-33210ab92b24" />

<img width="1151" height="597" alt="image" src="https://github.com/user-attachments/assets/29771a83-3a01-429c-aecc-1bbb9284b2b1" />

# Day 6 (25/02/26) – Model Training & Tuning

Completed Day 6 focusing on applied machine learning model training and evaluation.

What I Learned Today:
→ Logistic Regression fundamentals in Spark ML
→ RandomForest classifier implementation
→ Model evaluation using AUC (Area Under ROC)
→ Importance of training vs test evaluation

Tasks I Completed:
→ Trained a Logistic Regression model
→ Trained a RandomForest classifier
→ Evaluated both models using AUC
→ Compared performance to identify the stronger model

<img width="1016" height="771" alt="image" src="https://github.com/user-attachments/assets/bc7d7320-250e-4fec-9f67-a96c93d548b4" />

<img width="1160" height="902" alt="image" src="https://github.com/user-attachments/assets/180d6390-5cd2-48e2-b8fa-a65db94af83f" />

<img width="1162" height="817" alt="image" src="https://github.com/user-attachments/assets/7a195730-477b-410c-a5b4-149b55582de8" />

<img width="1258" height="690" alt="image" src="https://github.com/user-attachments/assets/83749f4e-92ed-4f81-8e86-0ee06dfcc57c" />

<img width="1259" height="878" alt="image" src="https://github.com/user-attachments/assets/d6d330be-8209-4c0b-9cf5-e66accb07319" />

<img width="1260" height="887" alt="image" src="https://github.com/user-attachments/assets/39131091-00c6-499a-a2db-048b53c3b7ae" />

<img width="1248" height="370" alt="image" src="https://github.com/user-attachments/assets/9271a6ae-b471-4e7f-967d-722830a0dec7" />

# Day 7 (26/02/26) – MLflow Tracking

Completed Day 7 focusing on experiment tracking and model lifecycle management using MLflow.

What I Learned Today:
→ How MLflow tracks experiments and parameters
→ Logging metrics and artifacts programmatically
→ Comparing model runs inside MLflow UI
→ Basic model versioning concepts

Tasks I Completed:
→ Logged training runs into MLflow
→ Recorded evaluation metrics and parameters
→ Compared multiple model experiments
→ Registered model versions for reproducibility

<img width="1918" height="901" alt="image" src="https://github.com/user-attachments/assets/cc42b57e-994b-40f2-98fe-fc07df98362a" />

<img width="1919" height="922" alt="image" src="https://github.com/user-attachments/assets/f637fdd4-273f-4f91-a2a5-272a5b800133" />

<img width="1919" height="700" alt="image" src="https://github.com/user-attachments/assets/688b9de2-1f93-431b-9191-6920f1f9a75f" />

<img width="1913" height="905" alt="image" src="https://github.com/user-attachments/assets/f335b63b-deeb-453b-993b-4bf34b074ae6" />

<img width="1919" height="591" alt="image" src="https://github.com/user-attachments/assets/9ab0640a-68e4-44b6-a988-ba23c7d6f5f8" />

# Day 8 (27/02/26) – Batch Inference Pipeline

Completed Day 8 focusing on building a batch inference pipeline and creating a production-ready Gold layer.

What I Learned Today:
→ How to perform batch scoring using a trained ML model
→ How to reload models from MLflow for inference
→ Converting model outputs into business-ready probabilities
→ Designing a Gold layer table for downstream consumption

Tasks I Completed:
→ Scored all users using the trained RandomForest model
→ Saved predictions into a Gold Delta table
→ Extracted purchase probabilities from Spark ML vectors
→ Identified top predicted buyers based on probability ranking

<img width="1919" height="737" alt="image" src="https://github.com/user-attachments/assets/88538003-31c4-4172-a9e0-491017a37cd9" />

<img width="1919" height="721" alt="image" src="https://github.com/user-attachments/assets/6d5631ff-d7a8-4b55-9e4c-d56d16013a0f" />

<img width="1911" height="911" alt="image" src="https://github.com/user-attachments/assets/e25fcb26-a05b-4f27-9c46-efb1302a57b6" />

# Day 9 (28/02/26) – Recommendation System

Completed Day 9 focusing on building a recommendation system using collaborative filtering with ALS.

What I Learned Today:
→ How collaborative filtering works using user–item interaction data
→ The difference between explicit and implicit feedback
→ How ALS (Alternating Least Squares) factorizes user-item matrices
→ Understanding the cold start problem in recommendation systems
→ How ranking-based recommendations differ from probability-based predictions

Tasks I Completed:
→ Created rating mapping from event data (view, click, purchase → numerical scores)
→ Built a user–product interaction dataset
→ Trained an ALS model using Spark MLlib
→ Generated Top-5 product recommendations per user
→ Ranked recommendations using predicted scores
→ Filtered out already interacted products for cleaner recommendations

<img width="1912" height="894" alt="image" src="https://github.com/user-attachments/assets/89460b17-5edc-464f-b27c-4ca3cddd2a56" />

<img width="1919" height="879" alt="image" src="https://github.com/user-attachments/assets/fc971d01-c9cc-4e74-99a1-a3fdf1176d10" />

<img width="1919" height="879" alt="image" src="https://github.com/user-attachments/assets/f0418608-24f1-4477-bde0-bcd167047a21" />

<img width="1919" height="902" alt="image" src="https://github.com/user-attachments/assets/9b9150be-fe2c-4885-9e06-d794c1eec1f5" />
