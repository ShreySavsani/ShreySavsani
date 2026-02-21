# About Myself

I'm Shrey -- a Data Engineer with an MS from Arizona State University and an Azure Data Engineering certification. I've built production data systems across four very different organizations: Accenture, Tesla, University of Phoenix, and IntusCare. My work spans Python, SQL, PySpark, Java, and dbt -- orchestrated with Airflow, deployed on AWS and Azure, and monitored with Grafana.

What I've learned is that the best work happens at the intersection of Data Engineering, Analytics Engineering, and Product thinking. I don't just build pipelines and hand them off -- I collaborate closely with product managers, analysts, and business stakeholders to make sure what I'm building actually moves the needle.

---

## Experience

### IntusCare — Data Engineer
*Healthcare Analytics · AWS · dbt · Airflow · Python*

IntusCare is a healthcare analytics company focused on PACE (Program of All-inclusive Care for the Elderly) organizations. I build and maintain the data pipelines that produce reports consumed by 70+ PACE programs making care decisions for elderly patients -- which means data quality is not optional.

**What I did:**
- Designed and maintained dbt models that power operational and clinical reporting across the full client base
- Built Airflow DAGs with idempotency as a first-class requirement -- if a task fails and reruns, it produces the same result without side effects
- Implemented CI/CD pipelines that run automated dbt tests on every pull request, catching data issues before they reach production
- Worked directly with clinical and product stakeholders to translate care-model requirements into testable data logic

**What I learned:** When downstream consumers are making care decisions -- not just building dashboards -- the standard for correctness changes. Every pipeline design decision starts with "what breaks for a patient if this is wrong?"

---

### Tesla — Data Engineer
*Manufacturing Analytics · Azure · SQL · Airflow · Grafana*

At Tesla, I worked on manufacturing data systems supporting operations on the factory floor. The cadence was fast, the data volumes were high, and the dashboards I built were used by people making real-time operational decisions.

**What I did:**
- Optimized SQL queries used in manufacturing dashboards, reducing execution time from 45 seconds to 11 seconds -- meaningful when dashboards refresh on a schedule and operators are waiting
- Designed and built Airflow DAGs for manufacturing data pipelines, with idempotency baked in from day one
- Built Grafana dashboards that surfaced key operational metrics for floor-level and management-level consumers
- Partnered with manufacturing and operations teams to understand what data actually drove decisions vs. what was noise

**What I learned:** The gap between "the pipeline ran successfully" and "the operator got what they needed" is where most engineering value gets lost. Understanding the consumer's decision-making process is as important as the technical implementation.

---

### University of Phoenix — Data Engineer
*Higher Education · AWS · Python · FastAPI · Java*

University of Phoenix presented a different kind of challenge: modernizing a data infrastructure built on legacy Java systems while keeping existing operations running. The work was less about scale and more about surgical integration.

**What I did:**
- Built FastAPI services that bridged legacy Java-based systems and modern cloud infrastructure on AWS
- Wrote ETL scripts in Python that extracted, normalized, and loaded data from disparate source systems into a unified layer
- Worked within compliance and institutional constraints that shaped every architectural decision

**What I learned:** Greenfield is a luxury. Most real-world data engineering is brownfield -- working within constraints, integrating with systems that weren't designed to be integrated with, and making pragmatic trade-offs that keep the business running while incrementally improving the foundation.

---

### Accenture — Data Engineer
*Consulting · Azure · PySpark · Azure Data Lake · Python*

Accenture was where I developed my foundation in large-scale pipeline engineering. I worked across multiple client engagements, which meant rapidly adapting to different data stacks, business domains, and team structures.

**What I did:**
- Processed 1,000+ files daily using PySpark on Azure Data Lake -- this was where I learned when Spark is the right tool and when it is overkill
- Built automated data validation frameworks covering 50+ batch pipelines: schema checks, row-count assertions, null-rate monitoring
- Managed the full pipeline lifecycle across client environments -- from ingestion through transformation to reporting layers
- Worked across teams of varying sizes and technical maturity, adapting documentation and communication accordingly

**What I learned:** Automation of validation is not a nice-to-have. When you are managing 50+ pipelines, manual data quality checks do not scale -- and silent failures are worse than loud ones. Building observability in from the start changes how you operate.

---

## Core Stack

| Domain | Tools |
|--------|-------|
| Languages | Python, SQL, PySpark, Java |
| Transformation | dbt |
| Orchestration | Apache Airflow |
| Cloud | AWS (S3, Lambda, RDS, Glue), Azure (ADLS, Azure Functions, Azure SQL) |
| Monitoring | Grafana |
| APIs | FastAPI |
| Version Control | Git |

---

## How I Work

I approach Data Engineering as Software Engineering applied to data movement. That means version control, idempotency, testing, and modularity are not aspirational -- they are table stakes. I've seen what happens when they're skipped (and I've been the one cleaning it up).

I'm most effective when I'm close to the problem -- understanding who consumes the data, what decisions it drives, and what breaks when it's wrong. That context shapes every technical decision I make.

[Back to Portfolio](../README.md)
