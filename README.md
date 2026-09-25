<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=2800&pause=900&color=6366F1&center=true&vCenter=true&width=600&lines=Python+%7C+PySpark+%7C+SQL;AWS+%7C+Apache+Iceberg;Senior+Data+Engineer%2C+9%2B+years" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aks1993)
[![Portfolio](https://img.shields.io/badge/Portfolio-6366F1?style=for-the-badge&logo=githubpages&logoColor=white)](https://nikuamit.github.io)
[![Email](https://img.shields.io/badge/Email-C14438?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nikuamit.sahu256@gmail.com)
[![Open to Work](https://img.shields.io/badge/Open%20to-Senior%20Data%20Engineer%20roles-34D399?style=for-the-badge)](https://nikuamit.github.io#contact)

</div>

```python
amit_kumar_sahu = {
    "role": "Senior Data Engineer",
    "based_in": "Bengaluru, Karnataka, India",
    "experience": "9+ years",
    "stack": ["Python", "PySpark", "SQL", "AWS", "Apache Iceberg", "Delta Lake", "Airflow", "dbt"],
    "highlights": [
        "Kenko AI: AWS lakehouse for 500+ tenants, query latency -45%, SLA 70% -> 98%",
        "Eli Lilly: 200K+ clinical assets catalogued via Axon, 5+ TB migrated to Veeva Vault",
        "AspireNXT: led 5-engineer team, 10+ TB migrated across finance/IoT/healthcare",
        "SpanIdea: IoT smart-parking pipeline, Raspberry Pi + Azure IoT Hub + MQTT",
        "Infosys x Daimler AG: ETL automation across 12+ manufacturing projects",
    ],
    "open_to": "Senior / Lead / Staff Data Engineer roles, freelance data engineering",
    "fun_fact": "ACM-ICPC World Semifinalist 2013, still plays competitive chess",
}
```

---

## 🛠️ Core stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white)

**Data engineering**
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache%20Iceberg-1B1F23?style=flat-square&logo=apache&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square&logo=databricks&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**AWS**
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![Glue](https://img.shields.io/badge/Glue-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=flat-square&logo=amazonredshift&logoColor=white)
![Athena](https://img.shields.io/badge/Athena-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)

**Databases & tools**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 🚀 Featured project — Astra Data Platform

Production-grade batch **and** streaming lakehouse. Bronze → Silver → Gold medallion architecture, 9-rule data-quality engine, config-driven pipelines.

```text
Raw Sources (Kafka / S3 / RDS via DMS CDC)
         │
         ▼
┌────────────────────────────────────────┐
│  BRONZE  — raw, immutable               │
│  Kafka stream → Delta                   │
│  CSV / Parquet / JSON batch → Delta     │
└──────────────┬───────────────────────────┘
               │  dedupe · DQ rules · schema check
               ▼
┌────────────────────────────────────────┐
│  SILVER  — clean, validated             │
│  9-rule DQ engine + quarantine          │
│  Dedup via window function              │
│  SCD Type 2 ready                       │
└──────────────┬───────────────────────────┘
               │  aggregations · SCD2
               ▼
┌────────────────────────────────────────┐
│  GOLD  — analytics-ready                │
│  Metric marts · dimensional models      │
│  BI / ML ready · Delta upsert           │
└────────────────────────────────────────┘
```

**[→ github.com/nikuamit/astra-data-platform](https://github.com/nikuamit/astra-data-platform)** · PySpark · Delta Lake · Kafka · AWS S3

---

## 📈 Career metrics

| Company | Domain | Impact |
|---|---|---|
| **Kenko AI** | SaaS Fitness Tech | Lakehouse for 500+ tenants · latency −45% · SLA 70%→98% · DQ incidents −60% |
| **Eli Lilly and Company** | Pharma | 200K+ clinical assets catalogued · 5+ TB migrated to Veeva Vault · onboarding +60% |
| **AspireNXT Pvt. Ltd.** | Consulting | 5-engineer team led · 10+ TB migrated · latency −40% · infra cost −25% |
| **SpanIdea Systems** | IoT | Real-time smart-parking pipeline · search time −50% |
| **Infosys (client: Daimler AG)** | Automotive Manufacturing | ETL automation across 12+ projects · downtime −20% |

---

## 📊 GitHub stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=nikuamit&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nikuamit&layout=compact&theme=tokyonight&hide_border=true" height="165" alt="Top languages" />

<!-- ⚠️ github-readme-stats.vercel.app is returning 503 (over free-tier quota) as of this
     publish — the two cards above may render broken until the service recovers.
     Verified-live fallback if that persists:
<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=nikuamit&theme=github_dark" height="200" alt="Stats" />
-->

<br/>

<img src="https://raw.githubusercontent.com/nikuamit/nikuamit/output/github-contribution-grid-snake.svg" alt="Contribution snake" />

<!-- The snake graphic above is generated by .github/workflows/snake.yml on a push/schedule.
     It will 404 until that workflow runs once — see the repo Actions tab. -->

</div>

---

## 📬 Contact

[nikuamit.sahu256@gmail.com](mailto:nikuamit.sahu256@gmail.com) · [linkedin.com/in/aks1993](https://www.linkedin.com/in/aks1993) · [nikuamit.github.io](https://nikuamit.github.io) — full-time roles or freelance, reply within 24 hours.
