## Jaegwang Yu

Backend Engineer focused on Java/Spring services, event-driven systems, and AI-assisted developer tooling.

[![Email](https://img.shields.io/badge/Email-marmong9770%40gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white)](mailto:marmong9770@gmail.com) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Jaegwang%20Yu-0077B5?style=flat-square&logo=LinkedIn&logoColor=white)](https://www.linkedin.com/in/devjae/) [![GitHub](https://img.shields.io/badge/GitHub-JAEKWANG97-181717?style=flat-square&logo=GitHub&logoColor=white)](https://github.com/JAEKWANG97)

---

### About

- Backend engineer interested in building reliable service flows with clear boundaries between user requests, background jobs, and data pipelines.
- Technical Coach at SSAFY, mentoring 40+ teams and 200+ developers on backend architecture, CI/CD, database design, and system troubleshooting.
- Open-source contributor to LINE Armeria and Apache SeaTunnel, with production-oriented changes merged through maintainer review.

---

### Open Source

| Project | Contribution | PR |
|:---|:---|:---:|
| LINE Armeria | Added support for custom Athenz token headers while preserving existing authentication behavior. | [#6604](https://github.com/line/armeria/pull/6604) |
| LINE Armeria | Added `FlagsProvider`-based default `ClientFactory` customization while keeping lifecycle behavior unchanged. | [#6671](https://github.com/line/armeria/pull/6671) |
| Apache SeaTunnel | Fixed Doris sink retry backoff and scheduler leak behavior during Doris BE failures. | [#10772](https://github.com/apache/seatunnel/pull/10772) |

---

### Projects

#### Trip Handam - Travel Recommendation Platform

[GitHub Repository](https://github.com/JAEKWANG97/Trip_Handam)

- Built a travel platform with personalized destination recommendations, trip planning, and social features.
- Separated user-facing request handling from recommendation analysis by publishing like events through Kafka.
- Used Elasticsearch for search, Redis for recommendation caching, and batch analysis for refreshing recommendation results.
- Tech: `Java`, `Spring Boot`, `Kafka`, `Elasticsearch`, `Redis`, `Spark`, `Hadoop HDFS`, `MySQL`, `Docker`, `Jenkins`

#### E.D.I.T.H - AI Code Review & Documentation Assistant

[GitHub Repository](https://github.com/JAEKWANG97/E.D.I.T.H)

- Built a GitLab MR event-based automated code review system and portfolio documentation assistant.
- Designed the RAG review flow so changed code can be reviewed with related project context rather than isolated diffs only.
- Connected webhook events, code analysis, vector retrieval, and review comment generation into an automated review pipeline.
- Awarded 1st place in the SSAFY autonomous project track.
- Tech: `Python`, `LangChain`, `RAG`, `Vector DB`, `GitLab API`, `FastAPI`

#### Soup - Interest-based Trend Newsletter Platform

[Backend Repository](https://github.com/pal-lang-gwi/soup-backend)

- Built an AI-powered newsletter platform that collects, summarizes, and delivers trend content by user interests.
- Designed a worker-based pipeline that separates crawling, summarization, and email delivery from the API server.
- Migrated backend and worker flow toward Redis Streams-based asynchronous processing and home-server deployment.
- Improved operational reliability around backend deployment, health checks, REST Docs, and admin filtering.
- Tech: `Java`, `Spring Boot`, `Redis Streams`, `Docker`, `GitHub Actions`, `REST Docs`

---

### Experience

#### SSAFY (Samsung Software Academy For Youth)

**Technical Coach (실습 코치)** | 2024.12 - Present

- Mentored 40+ project teams on backend architecture, API design, database schema design, and code quality.
- Guided teams through issues in distributed systems, concurrency, CI/CD pipelines, and deployment workflows.
- Introduced practical development processes using Jira, GitHub Actions, Jenkins, and review-based iteration.

---

### Skills

| Area | Stack |
|:---|:---|
| Backend | Java, Spring Boot, JPA, QueryDSL, FastAPI, Python |
| Data Flow | Kafka, Redis Streams, AWS SQS, Spark, Hadoop HDFS |
| Search / AI | Elasticsearch, RAG, LangChain, Vector DB |
| Cloud / Infra | AWS EC2, AWS S3, Docker, Docker Compose |
| DevOps | GitHub Actions, Jenkins, CI/CD, REST Docs |
| Architecture | Event-driven Architecture, Microservices, Worker Pattern |

---

### Education & Awards

#### SSAFY (Samsung Software Academy For Youth)

**Java Track** | 2024.01 - 2024.12

- Awards: Capstone Project 1st Place, Community Leadership Award
- Coursework: Algorithms, Java, Spring Backend Development

#### B.S. in Computer Science

University in South Korea

#### Certifications & Awards

- Profitlab Hackathon - 2nd Place
- Engineer Information Processing (정보처리기사)
- Samsung SW Competency Test - Level B
- FastCampus Builderthon - Finalist
