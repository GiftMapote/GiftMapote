# Hi there, I'm Gift 👋

**Data Engineer** with experience building scalable data pipelines and data platforms using Spark, Scala, Java, PySpark, and cloud technologies.

---

## 🚀 About Me

I'm a Data Engineer with 3+ years of experience in the banking industry, passionate about building reliable and scalable data systems. I enjoy designing idempotent data pipelines that transform raw data into meaningful insights that help answer real business questions.

My work focuses on building batch and streaming pipelines using technologies such as Apache Spark, PySpark, Apache Kafka, Scala, SQL, and Hadoop. I also spend time doing system analysis, ensuring that data platforms and pipelines are designed to be efficient, reliable, and able to handle large-scale data workloads. I have experience working in cloud environments including AWS and Databricks, where I build and optimize modern data solutions.

Outside of work, you'll usually find me outdoors or playing pool, where I enjoy applying the same analytical thinking and strategy that I use when working with data.

---

## 🛠️ Technical Skillset

**Languages & Frameworks**

![Scala](https://img.shields.io/badge/Scala-DC322F?style=for-the-badge&logo=scala&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Big Data & Streaming**

![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-003366?style=for-the-badge&logo=databricks&logoColor=white)

**Cloud & Infrastructure (AWS)**

![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![API Gateway](https://img.shields.io/badge/API_Gateway-FF4F8B?style=for-the-badge&logo=amazonapigateway&logoColor=white)
![Amazon Athena](https://img.shields.io/badge/Amazon_Athena-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![AWS Amplify](https://img.shields.io/badge/AWS_Amplify-FF9900?style=for-the-badge&logo=awsamplify&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazoncloudwatch&logoColor=white)
![AWS IAM](https://img.shields.io/badge/AWS_IAM-DD344C?style=for-the-badge&logo=amazonaws&logoColor=white)

**Platforms & Tools**

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)


---

## 🔨 Currently Building

### 🏠 [Rental Fairness Checker](https://main.d1y5bsp5jwth70.amplifyapp.com) — *Live*

An AI-powered tool that helps South African renters determine if their rental price is fair. Users enter their suburb, monthly price, and bedrooms — and get an instant fairness rating with AI-generated advice in 9 South African languages.

**Architecture:**
```
Scraper → S3 (Medallion: raw/bronze/silver/gold) → Lambda ETL (x3)
    → FastAPI on Lambda → API Gateway → Next.js on Amplify
    → AWS Bedrock (Claude) for AI-powered rental advice
```

**Tech:** Python • AWS Lambda • S3 • Athena • Bedrock • API Gateway • Amplify • Next.js • GitHub Actions • Terraform

🔗 **Live:** [rental-fairness-checker.amplifyapp.com](https://main.d1y5bsp5jwth70.amplifyapp.com) | 📂 **Repo:** [rental-fairness-ai](https://github.com/GiftMapote/rental-fairness-ai)

---

## 🔭 Featured Projects

<details>
<summary><b>🧠 Mule Fraud Detection Feature Store</b></summary>

- Built and maintained feature store pipelines to track behavioural patterns and identify accounts potentially used as mule accounts.
- Designed transaction-level and customer-level aggregated datasets structured as fact and dimension-style tables to support downstream fraud analytics.
- Delivered production-ready features consumed by DataRobot fraud model scoring pipelines operating on large-scale transactional data.
- 🏆 Project recognised with an **Innovation Award** for impact and delivery within the fraud detection domain.

**Tech:** Apache Spark • Scala • SQL • Feature Engineering
</details>

<details>
<summary><b>🔍 Cloudera Big Data Platform Dataset Monitor</b></summary>

- Developed an hourly monitoring job to detect missing data across 20+ critical datasets supporting downstream fraud and analytics pipelines.
- Enabled faster data backfills and significantly reduced downstream job failures by identifying gaps early.
- Improved operational reliability and reduced incident resolution time through proactive alerting and clearer diagnostics.

**Tech:** Apache Spark • Scala • HDFS • Data Monitoring
</details>

<details>
<summary><b>⚡ Clickstream Pipeline Migration (Cloudera → AWS)</b></summary>

- Migrated a high-volume clickstream pipeline from on-prem Cloudera infrastructure to AWS using Scala and Apache Spark.
- Reduced pipeline runtime from **~8 hours to under 3 hours** while lowering operational costs and improving stability.
- Improved scalability and reliability for downstream analytics and reporting systems.

**Tech:** Apache Spark • Scala • AWS • Distributed Data Processing
</details>

<details>
<summary><b>📡 Real-Time Product Take-Off Tracker</b></summary>

- Built a real-time streaming solution using Apache Kafka and Java to track incomplete product take-up applications.
- Enabled call centre teams to proactively follow up with clients, improving application completion rates and customer experience.
- Supported end-to-end delivery including requirements analysis, development, production rollout, and ongoing support.

**Tech:** Apache Kafka • Java • Streaming Pipelines
</details>

<details>
<summary><b>🚨 Fraud Sentinel Real-Time Medallion Pipeline</b></summary>

- Engineered a real-time fraud detection pipeline on Databricks using Spark Structured Streaming and Medallion Architecture to process financial transactions.
- Developed an automated observability system and Databricks Workflows to monitor pipeline health and trigger email alerts during downtime.
- Implemented Delta Lake optimizations (OPTIMIZE, VACUUM) to improve query performance and reduce storage costs.

**Tech:** Databricks • Spark Structured Streaming • Delta Lake • Medallion Architecture
</details>

---

## 🏅 Certifications

<table>
<tr>
<td>
<a href="https://credentials.databricks.com/18b46c51-8c16-4700-ac1d-366098d02bef#acc.mIPNbKvp">
<img src="images/Databrick.png" width="200">
</a>
</td>
<td>Databricks Data Engineer Associate</td>
</tr>

  <tr>
<td>
<a href="https://credentials.databricks.com/18b46c51-8c16-4700-ac1d-366098d02bef#acc.mIPNbKvp">
<img src="images/GenAI.png" width="200">
</a>
</td>
<td>Databricks Generative AI Fundamentals</td>
</tr>
</table

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gift-mapote)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GiftMapote)

<!-- Add your actual LinkedIn URL above -->
