# Sasha Malahov — 2025 Resume

- Phone: 617.892.1517
- Email: sasha@compsci.boutique
- LinkedIn: https://www.linkedin.com/in/sasha-m-63895815/
- GitHub: https://github.com/belarusian
- Location: Greater Boston, MA (open to hybrid/remote)

## Profile
Principal/Staff generalist in distributed systems, data platforms, and security. Designs durable, cost‑efficient platforms: on‑demand computation on EKS/Karpenter (10+ PB scanned), unified schema and discovery on AWS Glue (versioning + validation), and OIDC/identity services used platform‑wide. Outcome‑driven, delivering simple, reliable systems at scale; strongest in Python, Java, TypeScript.

- Positioning:
  - Principal/Staff generalist across distributed systems, data platforms, and security
  - Systems thinker building durable, end‑to‑end orchestration with simple, reliable ops
  - Drives cross‑functional initiatives from design to scale; outcome‑driven with measurable impact
  - Best fit: platform/data infrastructure/security architecture; tech lead for reliability/scale/integration

- Strengths:
  - Architecture: turns ambiguous problems into robust, scalable services
  - Compute at scale: cost‑efficient autoscaling on EKS/Karpenter
  - Data governance: schema versioning, validation, discovery/search
  - Security: reference‑quality OIDC with test‑first rigor
  - Integration: frameworks embedding third‑party tools with unified UX/auth
  - Performance: 10+ PB scanned; ≈900 Mbit/s Elasticsearch indexing (avg day <4 min)
  - Languages: Python (strongest), Java, JavaScript/TypeScript

- Signature work:
  - Computation framework: DB‑backed work ring with ephemeral workers; stateless master; resilient rebalance; applied to scan 10+ PB in S3
  - Unified tables: Glue tables created with real storage/SerDe; schemas versioned/validated (JSON/Avro/Protobuf); multi‑account search
  - Portal integration: Superset fork + custom SQLAlchemy driver; Hue Data Portal; repeatable micro‑portlet pattern
  - Security reference: OIDC 1.0 service and tests that seeded platform‑wide services

## Skills
- Languages: Python, Java, JavaScript, TypeScript, Ruby, C, Shell
- Data: Spark, Hadoop, Hive, Kafka, Presto, Athena, Elasticsearch/Lucene
- Cloud: AWS (EKS/ECR, Glue, Athena, S3, EMR, Batch, Lambda, DynamoDB, KMS, CloudFormation)
- Web/Services: React/Redux, Node.js/Express, Micronaut, Dropwizard, Flask
- Security: OpenID Connect, AuthN/Z, token delegation, SSO
- Infra/Ops: Docker, Kubernetes, Karpenter, Terraform, GitHub Actions/CI
- Testing: JUnit/Jupiter, Mockito, RSpec, Jest, PyTest
- Tooling: SQLAlchemy, Jackson, JSON Schema/Avro/Protobuf

## Experience

### Signify — Principal Software & Data Engineer
2016 – Present

Key contributions (2016–2025):
- Distributed compute — Computation framework (applied to malware scanning) (2023–2024, most complex project): Generalized, cost‑efficient on‑demand compute that distributes work across an arbitrary ring of ephemeral EKS workers via a DB‑backed work ring; resilient orchestration (stateless master, worker heartbeat/rebalance); applied to scan 10+ PB across S3.
- Data governance — Data Management Schemas & Unified Tables (2024–2025): Unified Glue tables on create, versioned schemas with validation (JSON Schema/Avro/Protobuf), and metadata search across accounts.
- Portal & integration — IoT Portal and integration framework (2018–2022): Micro‑portlets for platform APIs; forked Superset with custom SQLAlchemy driver; embedded Superset and Hue Data Portal as first‑class portlets with unified UX/auth/governance.
- Security & identity (2018–2020) — OIDC 1.0 reference implementation and separate identity management services (token validation/access control), including a read‑through policy cache; code and tests became the reference for subsequent platform security services.
- Big data & analytics: Hue enrichment; Elasticsearch indexing at ≈900 Mbit/s (~<4 minutes per avg day); elasticsearch‑hadoop resiliency; EMR/Batch/Lambda/Athena/Presto workloads; Kafka/Kinesis integrations.
- Global delivery: WiZ Hong Kong engagement and AliCloud (China) replication patterns.

Technologies: Python, Java, JavaScript/TypeScript, React, Micronaut, Flask, SQLAlchemy, AWS (EKS/ECR, Glue, Athena, S3, EMR, Batch, Lambda, DynamoDB, KMS, CloudFormation, Kinesis), Kubernetes, Karpenter, Kafka, Elasticsearch/Lucene, Spark, Hadoop, Presto, RDS, SQS, Docker, Terraform.

### JetBrains — Senior Software Engineer
2014 – 2016
- Datalore.io: Led frontend of collaborative, intelligent analytics application; built core UI/services (collaborative FS, dashboard builder, infinite tables, resizable editors).
- Responsibilities included security and performance reviews; mentoring on JavaScript; recruiting at MIT.
- Tech: Java, JavaScript, AWS.

### Nokia (HERE) — Senior Software Engineer
2011 – 2014
- Guides: Modeling, software design, CI, and backend infra in AWS; built a web composer for guide authoring and a named‑entity recognition algorithm (Apache OpenNLP).
- SCBE (team lead): Maintained a fully managed multi‑master DB with REST APIs for UGC; led migration from on‑prem to global AWS; improved reconciliation and indexing.
- Pulse/CNF: Performance work in Nokia MH5 JS framework; cross‑device sync for collections; Berlin handover.
- Tech: Java, C, Ruby/Sinatra, Lucene, AWS (SQS, DynamoDB, S3).

### PatientKeeper — Senior Software Engineer
2007 – 2011
- Full‑stack development for EHR transit and physician billing; customer‑driven integrations; implementation to go‑live support.
- Tech: Java, JavaScript, HTML.

### P&E Microcomputer Systems — Systems Software Developer
2002 – 2007
- Ported proprietary USB driver (Windows→Linux); owned build/install/docs/sample apps; built FedEx‑integrated shipping and RMA systems.
- Tech: C, Delphi.

## Education
- Northeastern University — B.S., Computer Science (2007)

## Open Source Contributions
- JetBrains JetPad Mapper
- OpenMetadata
- Apache Superset
- Micronaut

## Selected Keywords
AWS EKS, Karpenter, Kubernetes, Docker, CloudFormation, Glue, Athena, S3, EMR, Batch, Lambda, DynamoDB, Kafka, Kinesis, Spark, Hadoop, Presto, Elasticsearch, SQLAlchemy, Micronaut, React, TypeScript, OpenID Connect, PII detection, JSON Schema, Avro, Protobuf, RDS, SQS, caching, autoscaling, resiliency, cost optimization, multi‑region, AliCloud.
