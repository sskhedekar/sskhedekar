# Hi, I'm Sayli 👋

**Oracle DBA · 12 years experience · Currently exploring PostgreSQL & AWS cloud databases**

---

### 🛠️ What I work with

![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![PL/SQL](https://img.shields.io/badge/PL%2FSQL-F80000?style=flat&logo=oracle&logoColor=white)
![PL/pgSQL](https://img.shields.io/badge/PL%2FpgSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

---

### 🚀 Featured Projects

#### [pg_query_guardian](https://github.com/sskhedekar/pg_query_guardian)
> Self-contained PostgreSQL watchdog that automatically terminates runaway SELECT queries on AWS RDS read replicas.

Built entirely in PL/pgSQL — no Lambda, no EC2, no external dependencies. Born from a real business requirement and a frustration with fragile EC2-based solutions.

✅ pg_cron + dblink architecture &nbsp;·&nbsp; ✅ Full audit log &nbsp;·&nbsp; ✅ Exemption system &nbsp;·&nbsp; ✅ Dry-run mode

---

#### [pg-snap-anon](https://github.com/sskhedekar/pg_snap_anon_github)
> Anonymize AWS RDS PostgreSQL snapshots without ever connecting to live PROD.

Restores the latest automated snapshot to a temp RDS inside your VPC, anonymizes PII columns declared in `pii_config.yaml` using Faker, produces a clean output snapshot, then tears down the temp instance — PROD is never touched. Every step is checkpointed to S3, so a failed run resumes from the last completed table.

✅ PROD-safe by design &nbsp;·&nbsp; ✅ Resumable runs &nbsp;·&nbsp; ✅ FDW/dblink handling &nbsp;·&nbsp; ✅ S3 audit log

---

### 📖 Currently learning

- PostgreSQL internals — replication, extensions, PL/pgSQL
- AWS RDS & Aurora operational patterns
- Database automation without external infrastructure

---

### 📬 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sayli-khedekar-bb160266)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/sskhedekar)
