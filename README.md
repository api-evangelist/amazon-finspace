# Amazon FinSpace (amazon-finspace)

Amazon FinSpace is a data management and analytics service built specifically for the financial services industry. It reduces the time you spend on time-consuming data preparation tasks and makes it easy for analysts to access and analyze petabytes of financial data with a few clicks.

**URL:** [https://raw.githubusercontent.com/api-evangelist/amazon-finspace/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amazon-finspace/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Capital Markets, Data Analytics, Data Management, Financial Services

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon FinSpace API
The Amazon FinSpace API provides programmatic access to create and manage FinSpace environments, datasets, data views, and user access controls for financial data management and analytics.

**Human URL:** [https://aws.amazon.com/finspace/](https://aws.amazon.com/finspace/)

#### Tags:

 - Data Analytics, Data Management, Financial Services

#### Properties

- [Documentation](https://docs.aws.amazon.com/finspace/latest/management-api/fs-api-welcome.html)
- [OpenAPI](openapi/amazon-finspace-openapi.yml)
- [JSONSchema](json-schema/amazon-finspace-environment-schema.json)
- [JSONSchema](json-schema/amazon-finspace-kx-environment-schema.json)
- [JSONSchema](json-schema/amazon-finspace-kx-cluster-schema.json)
- [JSONSchema](json-schema/amazon-finspace-kx-database-schema.json)
- [JSONSchema](json-schema/amazon-finspace-kx-user-schema.json)
- [JSONStructure](json-structure/amazon-finspace-environment-structure.json)
- [JSONStructure](json-structure/amazon-finspace-kx-environment-structure.json)
- [JSONStructure](json-structure/amazon-finspace-kx-cluster-structure.json)
- [JSONStructure](json-structure/amazon-finspace-kx-database-structure.json)
- [JSONStructure](json-structure/amazon-finspace-kx-user-structure.json)
- [Example](examples/amazon-finspace-environment-example.json)
- [Example](examples/amazon-finspace-kx-environment-example.json)
- [Example](examples/amazon-finspace-kx-cluster-example.json)
- [Example](examples/amazon-finspace-kx-database-example.json)
- [Example](examples/amazon-finspace-kx-user-example.json)
- [GettingStarted](https://aws.amazon.com/finspace/getting-started/)
- [Pricing](https://aws.amazon.com/finspace/pricing/)
- [FAQ](https://aws.amazon.com/finspace/faqs/)
- [APIReference](https://docs.aws.amazon.com/finspace/latest/management-api/fs-api-welcome.html)

## Common Properties

- [Portal](https://aws.amazon.com/finspace/)
- [Website](https://aws.amazon.com/finspace/)
- [Documentation](https://docs.aws.amazon.com/finspace/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/industries/financial-services/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/finspace/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amazon-finspace)
- [SpectralRules](rules/amazon-finspace-spectral-rules.yml)
- [NaftikoCapability](capabilities/shared/finspace.yaml)
- [NaftikoCapability](capabilities/amazon-finspace-financial-analytics.yaml)
- [Vocabulary](vocabulary/amazon-finspace-vocabulary.yaml)
- [JSON-LD](json-ld/amazon-finspace-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Managed kdb Environment | Fully managed kdb+ (kdb+/q) compute infrastructure with HDB, RDB, Gateway, and Tickerplant cluster types. |
| Financial Analytics Workspace | Isolated FinSpace environments with preconfigured tools for financial data ingestion, preparation, and analysis. |
| Petabyte-Scale Data | Store and query petabytes of financial time-series data including tick, OHLCV, and alternative datasets. |
| kdb+ Cluster Autoscaling | Configure auto-scaling policies for kdb clusters to match intraday compute demand. |
| Multi-AZ Clusters | Deploy kdb clusters across multiple availability zones for high availability. |
| IAM-Integrated Users | Map FinSpace kdb users to IAM roles for fine-grained permission control. |
| SageMaker Integration | Access financial data from FinSpace environments directly within Amazon SageMaker Studio. |

## Use Cases

| Name | Description |
|------|-------------|
| Tick Data Management | Ingest, store, and query high-frequency market tick data (trades, quotes, order books) using kdb+ clusters. |
| Risk Analytics | Run intraday risk calculations and post-trade analytics on financial time-series data at low latency. |
| Quantitative Research | Provide quants and data scientists with managed kdb environments for backtesting and strategy development. |
| Regulatory Reporting | Aggregate and transform trade and order data for regulatory submissions and compliance. |
| Alternative Data Processing | Ingest and correlate alternative datasets (news, satellite, ESG) with market data for signal generation. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Store and retrieve kdb database snapshots and bulk financial data files. |
| AWS KMS | Encrypt FinSpace environments and kdb databases with customer-managed KMS keys. |
| AWS IAM | Control user and application access to FinSpace resources with IAM roles and policies. |
| Amazon SageMaker | Access FinSpace datasets and kdb environments from SageMaker Studio notebooks. |
| Amazon CloudWatch | Monitor kdb cluster health, query performance, and resource utilization metrics. |
| AWS Transit Gateway | Connect kdb environments to on-premises networks and other VPCs via Transit Gateway. |
| Amazon VPC | Deploy kdb clusters in isolated VPC networking with security group controls. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-finspace-openapi.yml](openapi/amazon-finspace-openapi.yml)

### JSON Schema

- [amazon-finspace-environment-schema.json](json-schema/amazon-finspace-environment-schema.json)
- [amazon-finspace-kx-cluster-schema.json](json-schema/amazon-finspace-kx-cluster-schema.json)
- [amazon-finspace-kx-database-schema.json](json-schema/amazon-finspace-kx-database-schema.json)
- [amazon-finspace-kx-environment-schema.json](json-schema/amazon-finspace-kx-environment-schema.json)
- [amazon-finspace-kx-user-schema.json](json-schema/amazon-finspace-kx-user-schema.json)

### JSON Structure

- [amazon-finspace-environment-structure.json](json-structure/amazon-finspace-environment-structure.json)
- [amazon-finspace-kx-cluster-structure.json](json-structure/amazon-finspace-kx-cluster-structure.json)
- [amazon-finspace-kx-database-structure.json](json-structure/amazon-finspace-kx-database-structure.json)
- [amazon-finspace-kx-environment-structure.json](json-structure/amazon-finspace-kx-environment-structure.json)
- [amazon-finspace-kx-user-structure.json](json-structure/amazon-finspace-kx-user-structure.json)

### JSON-LD

- [amazon-finspace-context.jsonld](json-ld/amazon-finspace-context.jsonld)

### Examples

- [amazon-finspace-environment-example.json](examples/amazon-finspace-environment-example.json)
- [amazon-finspace-kx-cluster-example.json](examples/amazon-finspace-kx-cluster-example.json)
- [amazon-finspace-kx-database-example.json](examples/amazon-finspace-kx-database-example.json)
- [amazon-finspace-kx-environment-example.json](examples/amazon-finspace-kx-environment-example.json)
- [amazon-finspace-kx-user-example.json](examples/amazon-finspace-kx-user-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [finspace.yaml](capabilities/shared/finspace.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [amazon-finspace-financial-analytics.yaml](capabilities/amazon-finspace-financial-analytics.yaml) | Amazon FinSpace API | — | Platform Engineers, DevOps |

## Vocabulary

- [Amazon FinSpace Vocabulary](vocabulary/amazon-finspace-vocabulary.yaml)

## Rules

- [amazon-finspace-spectral-rules.yml](rules/amazon-finspace-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
