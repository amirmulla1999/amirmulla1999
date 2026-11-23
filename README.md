## Hi, I'm Amir 👋

**Software Engineer · Full Stack (Java, Spring Boot, React) · Generative AI**

I have 4 years of experience building enterprise web applications with Java, Spring Boot microservices,
Apache Kafka and React, deployed on AWS and GCP. I work across the full lifecycle, from system design and
test-driven development to CI/CD and production support. I also build generative AI features: LLM
integration, RAG and AI agents, including one that is live on Google Cloud Marketplace.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-amirmulla-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amirmulla/)
![Location](https://img.shields.io/badge/Based%20in-Thane%2C%20India-555)

### What I do

- **Backend:** Spring Boot microservices, versioned REST APIs, event-driven pipelines with Kafka, and
  query and schema tuning for MySQL.
- **Frontend:** React 18 applications end to end, from complex canvases to live status over WebSockets.
- **Generative AI:** AI agents with Google ADK and A2A, RAG, and provider-agnostic LLM layers across
  OpenAI, Gemini and Azure OpenAI.
- **Security and identity:** OAuth2 / OIDC sign-in, JWT verification and automated tenant onboarding.
- **Quality:** TDD with JUnit 5 and Mockito, 90%+ unit test coverage, SonarQube quality gates in CI/CD.

### Experience

| Role | Company | Period |
|---|---|---|
| Software Engineer (Full Stack) | EvoluteIQ Solutions | Feb 2024 – present |
| Associate Software Engineer (Java Developer) | Test Yantra Software Solutions | Nov 2022 – Jan 2024 |
| Software Engineer Intern | Test Yantra Software Solutions | Aug 2022 – Oct 2022 |

**Highlights**

- Shipped an AI application generator, live on **Google Cloud Marketplace and Gemini Enterprise**: a
  Python agent (Google ADK, A2A, RAG), its OAuth2/OIDC onboarding service on Cloud Run, and the React app.
- Built full stack features for an enterprise hyperautomation platform used by 5+ enterprise clients,
  improving scalability by about 25% with Kafka pipelines and cutting MySQL query latency by about 35%.
- Built 20+ REST APIs for a school management system serving 10,000+ users across 15+ institutions, and
  cut API response time by about 40%.

### Open-source projects

| Project | What it is | Stack |
|---|---|---|
| **[AI Agents](https://github.com/amirmulla1999/ai-agents)** | Two production-minded AI agents on a shared, provider-agnostic core. **HireFinch** is a multi-user job-search agent: it finds jobs from 9 source types, scores them with explainable matching, tailors resumes with fact-checked AI rewrites and fills applications through a Chrome extension. **Saathi** helps people in India find government welfare schemes they qualify for, in their own language, on the web and WhatsApp, with eligibility decided by a rules engine and scheme data checked against official sources. | Python, FastAPI, React, TypeScript, PostgreSQL, Azure OpenAI / Gemini, Docker |
| **[Face Identity Service](https://github.com/amirmulla1999/face-service)** | Face verification (1:1) and real-time identification (1:N) API with a vector-search gallery, a live webcam stream over WebSocket and API-key auth. | Python, FastAPI, InsightFace ArcFace, FAISS, Docker |
| **[Task Management System](https://github.com/amirmulla1999/sprih-task-management-system)** | REST API for tasks with filtering, pagination, sorting, DTOs and structured error handling. | Java, Spring Boot, Spring Data JPA, H2, JUnit 5 |

### Tech stack

**Languages:** Java · Python · TypeScript · JavaScript · SQL<br>
**Backend:** Spring Boot · Spring Security · Spring Cloud · Hibernate / JPA · Microservices · Apache Kafka · FastAPI · REST · WebSockets<br>
**Frontend:** React 18 · TypeScript · Tailwind CSS · HTML5 / CSS3<br>
**Data:** MySQL · PostgreSQL · MongoDB · Redis · DynamoDB · Firestore<br>
**Cloud & DevOps:** AWS (EC2, S3, DynamoDB, Secrets Manager) · GCP (Cloud Run, Firestore, Vertex AI) · Docker · Kubernetes (basic) · GitLab CI · GitHub Actions · Jenkins · SonarQube<br>
**AI:** LLM integration (OpenAI, Gemini, Azure OpenAI) · RAG · vector search · AI agents (Google ADK, A2A, MCP)<br>
**Testing & security:** JUnit 5 · Mockito · pytest · TDD · OAuth2 / OIDC · JWT

### How I build

- Deterministic code makes the decisions; models only propose, and validators check them.
- Security by default: authentication, input validation and secrets kept out of code.
- Tests and CI from the first commit, and observable, debuggable services in production.
