# Data Engineering Framework

Central repository for all Data Engineering team's infrastructure, services, and integrations.

## Repository Structure

- **.github/workflows/** - CI/CD pipelines
- **common/** - Shared resources (Lambda layers, Glue libs, configs)
- **Terraform/** - Terraform infrastructure configs
  - modules/ - Reusable Terraform templates
  - infrastructure/ - Central infrastructure (S3, IAM, networking)
- **services/** - Standard, reusable DE processes
- **integrations/** - Client-specific non-standard code
- **docs/** - Documentation, diagrams, standards

## Services

1. **fetch-process** - Internal data fetching
2. **external-fetch-process** - External data fetching
3. **ingestion-process** - File validation and data loading
4. **dw-source-transfer** - Data warehouse transfers
5. **reconciliation-engine** - Data quality reconciliation
6. **file-delivery** - File delivery (SFTP, Email, S3)
7. **sql-extract** - Config-driven SQL extraction

## Environment Management

- **Branches**: dev → DEV environment, main → PROD environment
- **Terraform**: Separate .tfvars files per environment

## Getting Started

Documentation coming soon...
## Trying
