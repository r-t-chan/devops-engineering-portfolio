# DevOps Engineering Portfolio

Case studies and architecture write-ups from production infrastructure work. Details are generalized and sanitized — these document the patterns and decisions, not internal configurations.

## Projects

| Project | Summary |
|---------|---------|
| [Proxmox bare-metal migration](./projects/proxmox-baremetal-migration/) | Migrating 14 cloud droplets to bare metal behind a NAT gateway — design, cutover plan, and results (~$1,500 CAD/month saved) |
| [OpenSearch SIEM build](./projects/siem-opensearch-build/) | Self-managed OpenSearch SIEM at a HIPAA-regulated SaaS — ingestion pipeline, detection-as-code with Sigma, tiered retention, and cross-source correlation across 40+ services |
| [OPKSSH dev access migration](./projects/opkssh-dev-access/) | Replacing SSH key management with OPKSSH tied to Google Workspace — ephemeral certs, SSO-based onboarding/offboarding, and three-tier access control via Google Groups |

## Related repos

- [keycloak-zabbix-monitoring](https://github.com/r-t-chan/keycloak-zabbix-monitoring) — Zabbix template + alert routing for Keycloak's Prometheus metrics
- [terraform-aws-lambda-eventbridge](https://github.com/r-t-chan/terraform-aws-lambda-eventbridge) — reusable Terraform module for scheduled Lambda jobs

## Background

DevOps Engineer at a HIPAA-regulated telehealth SaaS company. Day to day: GitHub Actions CI/CD across 40+ services, AWS infrastructure via Terraform, OpenSearch SIEM, Keycloak SSO administration, and FedRAMP compliance work.
