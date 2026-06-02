---
domain: engineering-technology
subdomain: cloud-computing
title: "Cloud Computing"
description: "The delivery of computing services over the internet, including servers, storage, databases, networking, and software"
created: 2026-06-02
updated: 2026-06-02
tags: [cloud, infrastructure, AWS, Azure, GCP, virtualization, containers, serverless]
prerequisites: [engineering-technology/computer-science, engineering-technology/software-engineering]
related: [engineering-technology/software-engineering, engineering-technology/data-science, engineering-technology/cybersecurity]
difficulty: intermediate
completeness: comprehensive
---

# Cloud Computing

## Overview

Cloud computing is the delivery of computing services—including servers, storage, databases, networking, software, analytics, and intelligence—over the Internet ("the cloud") to offer faster innovation, flexible resources, and economies of scale. It enables organizations to access and use computing power, storage, and applications on-demand without having to invest in and maintain their own physical infrastructure. Cloud computing has transformed how businesses deploy and scale applications, from startups to enterprise organizations.

## Core Concepts

### Cloud Service Models
- **Infrastructure as a Service (IaaS)**: Virtual machines; storage; networking; raw compute resources
- **Platform as a Service (PaaS)**: Application hosting; managed runtime; databases; development tools
- **Software as a Service (SaaS)**: Complete applications; subscription-based; fully managed services
- **Function as a Service (FaaS) / Serverless**: Event-driven compute; automatic scaling; pay-per-use
- **Container as a Service (CaaS)**: Container orchestration; Kubernetes; managed container platforms
- **Backend as a Service (BaaS)**: Mobile/backend services; authentication; databases; push notifications

### Deployment Models
- **Public Cloud**: Shared infrastructure; multi-tenant; pay-per-use; AWS, Azure, GCP
- **Private Cloud**: Dedicated infrastructure; single-tenant; on-premises or hosted; enhanced control
- **Hybrid Cloud**: Combination of public and private; workload portability; cloud bursting
- **Multi-Cloud**: Using multiple cloud providers; avoiding vendor lock-in; optimizing costs
- **Community Cloud**: Shared infrastructure for specific communities; regulatory compliance
- **Edge Cloud**: Distributed computing at the edge; low latency; IoT support

### Virtualization & Containers
- **Hypervisors**: Type 1 (bare-metal) vs Type 2 (hosted); VMware ESXi; Hyper-V; KVM
- **Virtual Machines**: Complete operating systems; isolation; resource allocation; VM lifecycle
- **Containers**: Lightweight; shared OS; Docker; container images; registries
- **Container Orchestration**: Kubernetes; Docker Swarm; scaling; service mesh
- **Microservices Architecture**: Decomposed services; API communication; independent deployment
- **Serverless Computing**: Function execution; cold starts; execution time limits; stateless

### Cloud Networking
- **Virtual Private Cloud (VPC)**: Isolated network; subnets; route tables; network ACLs
- **VPN & Direct Connect**: Secure connectivity; dedicated connections; hybrid cloud
- **Load Balancers**: Distributing traffic; health checks; auto-scaling integration
- **Content Delivery Networks (CDN)**: Edge caching; global distribution; latency reduction
- **DNS Services**: Route 53; domain management; health checks; geo-routing
- **Network Security Groups**: Firewall rules; security at network layer; inbound/outbound rules

### Cloud Storage
- **Object Storage**: S3; blob storage; buckets; scalability; durability
- **Block Storage**: Persistent block volumes; EC2 root and data volumes; performance
- **File Storage**: Shared file systems; EFS; Azure Files; NFS/SMB protocols
- **Data Lakes**: Centralized data repository; structured/unstructured data; analytics
- **Backup & Disaster Recovery**: Snapshots; cross-region replication; RTO/RPO
- **Storage Classes**: Hot/warm/cold; infrequent access; Glacier for archiving

### Cloud Databases
- **Relational Databases (RDS)**: Managed SQL; MySQL; PostgreSQL; Oracle; SQL Server
- **NoSQL Databases**: DynamoDB; Cosmos DB; MongoDB; document; key-value; wide-column
- **In-Memory Databases**: ElastiCache; Redis; Memcached; caching; session management
- **Data Warehouses**: Redshift; Snowflake; BigQuery; analytical workloads; petabyte scale
- **Time-Series Databases**: InfluxDB; time-series data; IoT; monitoring data
- **Graph Databases**: Neo4j; Amazon Neptune; relationships; social networks; recommendations

### Cloud Security
- **Identity & Access Management (IAM)**: Users; groups; roles; policies; least privilege
- **Encryption**: At rest; in transit; key management services (KMS); customer-managed keys
- **Network Security**: Firewalls; security groups; WAF; DDoS protection
- **Compliance & Governance**: SOC 2; ISO 27001; HIPAA; GDPR; cloud-native compliance tools
- **Shared Responsibility Model**: Provider vs customer security responsibilities
- **Security Monitoring**: CloudTrail; GuardDuty; Security Hub; SIEM integration

### Cloud Cost Management
- **Pricing Models**: On-demand; reserved instances; savings plans; spot/preemptible instances
- **Cost Optimization**: Right-sizing; auto-scaling; cost allocation tags; budget alerts
- **Cost Monitoring**: Cost Explorer; billing dashboards; cost anomaly detection
- **FinOps**: Cloud financial management; cross-functional collaboration; continuous optimization
- **Reserved Capacity**: Commitment-based discounts; coverage analysis; capacity planning
- **Serverless Cost Model**: Pay-per-invocation; execution time; memory allocation

### DevOps & Cloud Operations
- **Infrastructure as Code (IaC)**: Terraform; CloudFormation; Pulumi; declarative provisioning
- **CI/CD Pipelines**: CodePipeline; GitHub Actions; Jenkins; automated testing and deployment
- **Configuration Management**: Ansible; Chef; Puppet; immutable infrastructure
- **Monitoring & Logging**: CloudWatch; Azure Monitor; Stackdriver; centralized logging
- **Incident Management**: Alerting; on-call; postmortems; blameless culture
- **SRE Practices**: SLIs; SLOs; error budgets; reliability engineering

### Cloud Architecture Patterns
- **Scalability Patterns**: Horizontal vs vertical scaling; auto-scaling groups; load balancing
- **Availability Patterns**: Multi-AZ deployments; failover; redundancy; high availability
- **Resilience Patterns**: Circuit breakers; retry policies; bulkheads; timeouts
- **Caching Strategies**: CDN; in-memory caches; distributed caches; cache invalidation
- **Database Patterns**: Read replicas; sharding; partitioning; eventual consistency
- **Event-Driven Architecture**: Message queues; event sourcing; CQRS; streaming

### Serverless & FaaS
- **Function Execution**: Lambda; Azure Functions; Cloud Functions; trigger types
- **Cold Starts**: Initialization latency; provisioned concurrency; optimization
- **Event Sources**: S3; SQS; DynamoDB streams; HTTP API; scheduled events
- **State Management**: External state; Durable Objects; stateless functions
- **Serverless Frameworks**: Serverless Framework; SAM; CDK; deployment automation
- **Cost Model**: Pay-per-invocation; execution duration; memory consumption

### Multi-Cloud & Hybrid Cloud
- **Workload Migration**: 6 Rs (Rehost, Replatform, Refactor, Repurchase, Retire, Retain)
- **Cloud Portability**: Containerization; abstraction layers; avoiding lock-in
- **Hybrid Integration**: On-premises + cloud; consistent management; data gravity
- **Cloud Management Platforms**: RightScale; Turbonomic; multi-cloud orchestration
- **Data Gravity**: Moving data vs compute; latency considerations; bandwidth

### Cloud Migration Strategies
- **Assessment & Planning**: Workload analysis; dependencies; risk assessment
- **Migration Patterns**: Lift-and-shift; lift-and-optimize; replatforming; refactoring
- **Application Migration**: Database migration; zero-downtime migration; validation
- **Data Migration**: Bulk transfer; real-time replication; data validation
- **Testing & Validation**: Performance testing; security testing; user acceptance
- **Post-Migration Optimization**: Right-sizing; cost optimization; continuous improvement

### Cloud-Native Development
- **12-Factor App**: Methodology for cloud-native application development
- **Microservices Design**: Service decomposition; API design; service mesh
- **Container Native**: Container-first design; container security; orchestration
- **Kubernetes Ecosystem**: Pods; services; deployments; Helm; operators
- **Service Mesh**: Istio; Linkerd; traffic management; observability; security
- **Cloud-Native Databases**: Managed services; auto-scaling; serverless databases

### Performance & Optimization
- **Performance Testing**: Load testing; stress testing; scalability testing
- **Auto-Scaling**: Metric-based scaling; scheduled scaling; predictive scaling
- **Content Optimization**: Compression; image optimization; minification; CDN
- **Database Optimization**: Query optimization; indexing; connection pooling
- **Network Optimization**: CDN usage; edge computing; protocol optimization
- **Cost-Performance Balance**: Right resources; reserved capacity; spot instances

### Emerging Cloud Technologies
- **Distributed Cloud**: Extending cloud to edge locations; consistent experience
- **Sovereign Cloud**: Data residency; regulatory compliance; geographic boundaries
- **Confidential Computing**: Secure enclaves; encryption in use; sensitive workloads
- **Quantum Computing Services**: Cloud-based quantum computing; hybrid classical-quantum
- **Cloud Sustainability**: Carbon-aware computing; renewable energy; efficiency metrics
- **Wasm for Cloud**: WebAssembly at edge; serverless runtimes; universal execution

## Key Theories

| Theory | Key Figure | Core Idea |
|--------|-----------|-----------|
| Cloud Computing Definition | NIST (Mell & Grance) | On-demand self-service; broad network access; resource pooling; rapid elasticity; measured service |
| Total Cost of Ownership (TCO) | Various | Comparing cloud vs on-prem costs including hidden costs |
| Right-Sizing | Various | Matching instance types to actual workload requirements |
| Scalability vs Elasticity | Various | Scaling horizontally/vertically vs automatic scaling based on demand |
| CAP Theorem | Brewer | Trade-offs between Consistency, Availability, and Partition tolerance |

## Important Figures

- **Anthony "Tony" Sales**: Cloud computing pioneer; early virtualization
- **Werner Vogels**: AWS CTO; cloud innovation; distributed systems at Amazon
- **Satya Nadella**: Microsoft's cloud transformation; Azure growth
- **Urs Hölzle**: Google infrastructure; early cloud computing at Google
- **Marc Benioff**: Salesforce founder; SaaS pioneer; cloud CRM
- **Ray Ozzie**: Azure Services; BlueStripe; cloud architecture
- **Peter Levine**: Cloud computing; Xen virtualization; cloud-native
- **Jennifer Scott (Datadog)**: Cloud observability; monitoring pioneer
- **Kelsey Hightower**: Kubernetes; cloud-native advocate; developer education
- **Charity Majors**: Honeycomb; observability; SRE; cloud operations

## Frontiers

- **Serverless Evolution**: More managed services; reduced cold starts; better debugging
- **Confidential Computing**: Secure enclaves; encrypted data in use; enterprise adoption
- **Edge Computing Integration**: Cloud at the edge; distributed workloads; IoT
- **AI/ML Cloud Services**: Managed ML platforms; AutoML; pre-trained models
- **Sovereign Cloud Solutions**: Data sovereignty; compliance; geographic isolation
- **Green Cloud Computing**: Carbon tracking; renewable energy; sustainability metrics
- **Cloud-Native Security**: Shift-left security; DevSecOps; zero trust
- **Distributed Cloud**: Centralized cloud with edge locations; consistent experience

## Applications

- **Web Applications**: Scalable hosting; auto-scaling; global distribution
- **Mobile Backends**: Serverless APIs; authentication; push notifications; analytics
- **Data Analytics**: Data lakes; ETL pipelines; BI tools; machine learning
- **Machine Learning**: Managed ML services; GPU instances; model training
- **IoT**: Device management; data ingestion; real-time processing
- **Gaming**: Game servers; matchmaking; leaderboards; content delivery
- **Media & Entertainment**: Video streaming; transcoding; CDN; global delivery
- **Enterprise Applications**: ERP; CRM; collaboration tools; productivity suites

## Classic Works

- **NIST Definition of Cloud Computing** by Mell & Grance — Official definition
- **"The Art of Cloud Architecture"** by Uwe Friedrichsen — Design patterns
- **"Cloud Native Patterns"** by Cornelia Davis — Designing for cloud-native
- **"Terraform: Up & Running"** by Yevgeniy Brikman — IaC with Terraform
- **"Kubernetes in Action"** by Marko Lukša — Kubernetes for developers
- **"Building Microservices"** by Sam Newman — Microservices architecture
- **"Site Reliability Engineering"** by Google — Cloud operations excellence

## See Also

- [Software Engineering](software-engineering.md) — DevOps and CI/CD
- [Cybersecurity](cybersecurity.md) — Cloud security
- [Data Science](data-science.md) — Data analytics and ML
- [Computer Science](computer-science.md) — Distributed systems fundamentals
