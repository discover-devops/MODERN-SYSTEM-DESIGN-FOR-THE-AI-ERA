
# MODERN SYSTEM DESIGN FOR THE AI ERA
## Complete Course ToC — 8 Live Sessions

**Target:** Mid-level Cloud & DevOps engineers (3-7 years) targeting senior, architect, or platform engineering roles

**Format:** Live, Draw io visual teaching, real AWS/Azure mapping every session

**Unique angle:** Only system design course that covers CI/CD design, observability architecture, AND GenAI infrastructure — taught by an Ex-AWS hiring manager

---

### SESSION 1 
**"How Senior Engineers Think About Systems"**
*Why most mid-level engineers fail system design — and the framework that fixes it*

- Why system design interviews feel different from technical interviews
- How senior engineers think: requirements → capacity → design → bottlenecks
- The 5-step framework every answer must follow
- Monolith vs Microservices — not theory, when to actually use each
- Three-tier architecture — the foundation of every real system
- Common mistakes mid-level engineers make in the first 10 minutes
- **Live Draw.io:** Design a 3-tier web application from scratch — then evolve it to microservices
- Real AWS mapping: EC2, ECS, EKS, RDS, ALB

---

### SESSION 2 
**"The Core Building Blocks Every Senior Engineer Must Know"**
*Scalability, load balancing, caching, and API design — the reusable parts*

- Scalability: vertical vs horizontal — when each breaks
- Load balancing: ALB vs NLB, L4 vs L7, round robin vs least connections
- API Gateway vs Load Balancer — when to use which
- Caching: Redis vs Memcached, where to cache, cache invalidation strategies
- Synchronous vs event-driven architecture — the decision that changes everything
- The 12-factor app — why it matters for system design interviews
- **Live Draw.io:** Design a URL shortener (TinyURL) — the most common interview problem, done right
- Real AWS mapping: ElastiCache, API Gateway, CloudFront, ALB/NLB

---

### SESSION 3 
**"Databases — The Decision That Makes or Breaks Your Design"**
*SQL vs NoSQL, sharding, replication — how to choose and defend your decision*

- SQL vs NoSQL — the real decision framework (not "which is better")
- Aurora vs DynamoDB — when each wins
- ACID vs BASE — what interviewers actually want to hear
- Database replication: primary/secondary, multi-primary, read replicas
- Sharding strategies — consistent hashing, range-based, directory-based
- Challenges of hashing at scale — what breaks and why
- CAP theorem in plain English — how to use it in an interview answer
- **Live Draw.io:** Design a social media feed at Instagram scale
- Real AWS mapping: RDS Aurora, DynamoDB, ElastiSearch, Redshift

---

### SESSION 4 
**"Messaging, Queues, and Event-Driven Architecture"**
*Kafka vs SQS vs RabbitMQ — and how to design systems that never lose data*

- Why queues exist — decoupling, buffering, reliability
- Queues vs Pub/Sub vs Streaming — the three patterns and when each applies
- Kafka vs SQS vs RabbitMQ — honest comparison for interviews
- Event-driven architecture patterns — when it helps, when it creates problems
- Dead letter queues, retry logic, idempotency — what senior engineers know
- WebSockets for real-time communication — how to design a chat system
- High priority queuing — how to design systems with message priority
- **Live Draw.io:** Design WhatsApp/Telegram at scale — real-time messaging, delivery receipts, offline handling
- Real AWS mapping: SQS, SNS, MSK (Kafka), EventBridge, API Gateway WebSocket

---

### SESSION 5 
**"Designing for the Cloud — High Availability, Multi-Region, and Disaster Recovery"**
*What actually breaks in production — and how to design against it*

- High Availability vs Fault Tolerance — the difference matters in interviews
- Active-active vs active-passive — when each makes sense and why
- Disaster Recovery: RPO vs RTO in plain English
- DR patterns: backup/restore, pilot light, warm standby, multi-region active-active
- CDN design — when it helps, when it doesn't, what breaks
- Security architecture: authentication vs authorization, encryption at rest vs in transit
- TLS vs MTLS — when you need mutual authentication
- IDS vs IPS vs Security Groups vs NACLs — the layered security model
- **Live Draw.io:** Design a multi-region e-commerce platform on AWS — with DR failover
- Real AWS mapping: Route 53, CloudFront, RDS Multi-AZ, S3 Cross-Region Replication, WAF

---

### SESSION 6 
**"Designing DevOps Systems — CI/CD and Platform Engineering at Scale"**
*The session nobody else teaches. Your moat.*

- Why CI/CD is a system design problem — not just a tooling problem
- Designing a CI/CD pipeline that handles 10,000 deployments per day
- Artifact management and container registry design at scale
- Deployment strategies: blue/green, canary, feature flags, rolling updates
- Rollback mechanisms — how to design for failure from day one
- Platform engineering: designing internal developer platforms
- Serverless vs container scaling — when each wins
- **Live Draw.io:** Design a complete CI/CD platform for a 500-engineer organization
- Real AWS mapping: CodePipeline, CodeBuild, ECR, EKS, GitHub Actions at scale, ArgoCD

---

### SESSION 7 
**"Observability and Monitoring — Design What You Can See"**
*Why observability is a system design problem, not a tool selection problem*

- The three pillars: metrics, logs, traces — and how they connect
- Designing a metrics collection system at scale
- Log aggregation architecture — what breaks at high volume
- Distributed tracing — how to design for it from day one, not as an afterthought
- Performance and cost optimization in observability systems
- Big data and analytics design patterns — when you need a data pipeline
- **Live Draw.io:** Design a full observability platform (Datadog-style) from scratch
- Real AWS mapping: CloudWatch, X-Ray, OpenTelemetry, Prometheus, Grafana, ELK stack, Jaeger

---

### SESSION 8 
**"GenAI Meets System Design — Architecture for the AI Era"**
*The session that makes this course unlike anything else available*

- How LLM-powered applications are architecturally different from traditional apps
- RAG architecture — vector databases, embedding models, retrieval pipelines
- LLMOps: model versioning, A/B testing, deployment pipelines for AI
- Observability for AI workloads — token costs, latency, hallucination monitoring
- Agentic AI architecture — how autonomous agents are designed at system level
- Real use cases you can implement this week:
  - Auto-remediation agent using Bedrock + Lambda
  - Intelligent log analysis with LLM
  - AI-powered code review in your CI/CD pipeline
- **Live Draw.io:** Design a complete AI-powered DevOps platform
  - EKS as compute layer
  - AWS Bedrock for LLM inference
  - RAG pipeline with vector database
  - CI/CD pipeline for ML model updates
  - Observability layer for AI workloads
- What to learn next: MLOps, LLMOps, Agentic AI roadmap
- Course wrap-up + your 90-day action plan

---

## WHAT MAKES THIS COURSE DIFFERENT

| Other System Design Courses | This Course |
|---|---|
| Generic FAANG interview prep | Cloud & DevOps engineer specific |
| Abstract boxes and arrows | Everything live on Draw.io |
| No CI/CD system design | Full session on CI/CD at scale |
| No observability design | Full session on observability architecture |
| No GenAI content | Dedicated session on AI-era architecture |
| Recorded, no interaction | Live, maximum 15 students |
| Junior instructors | Ex-AWS hiring manager, 20 years |

---

