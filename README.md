# James Ward — IoT & Cloud Solutions Architect

35+ years in enterprise IT. 14 years as enterprise solutions architect. Co-founder/CTO of an IoT startup where I built end-to-end connected systems from embedded firmware through AWS cloud architecture.

This portfolio demonstrates that full stack — device identity, cloud ingestion, IaC, operator tooling, and AI-enhanced DevOps pipelines.

---

## Featured Projects

| Project | What it does | Stack |
|---------|-------------|-------|
| [aws-iot-edge-reference](https://github.com/JamesIOmete/aws-iot-edge-reference) | End-to-end AWS IoT reference implementation for cold chain monitoring — X.509 device identity, MQTT/TLS ingestion, Lambda processor, DynamoDB telemetry storage, CloudWatch observability | Python · Terraform · AWS IoT Core · Lambda · DynamoDB · CloudWatch |
| [iotctl](https://github.com/JamesIOmete/iotctl) | Operator CLI for AWS IoT Core fleets — fleet status, device telemetry, excursion events, CloudWatch log queries. Real AWS API calls, no mock data | Go · AWS SDK v2 · Cobra |
| [tf-plan-ai-reviewer](https://github.com/JamesIOmete/tf-plan-ai-reviewer) | GitHub composite action that parses `terraform plan -json`, extracts risk signals (IAM changes, open CIDRs, resource destroys), and posts a PASS / WARN / BLOCK verdict as a PR comment | Python · Anthropic Claude · OpenAI · Azure OpenAI · GitHub Actions |
| [multicloud-sa-toolkit](https://github.com/JamesIOmete/multicloud-sa-toolkit) | Five production-pattern use cases across AWS, Azure, and GCP — landing zones, inventory, monitoring, ephemeral sandboxes, and OIDC identity bootstrap | Terraform · GitHub Actions · AWS · Azure · GCP |
| [multicloud-estate-briefing](https://github.com/JamesIOmete/multicloud-estate-briefing) | GitHub composite action that ingests multi-cloud inventory artifacts and generates a natural-language estate briefing with drift analysis | Python · OpenAI · Azure OpenAI · GitHub Actions |

> More work is visible in the [Repositories](https://github.com/JamesIOmete?tab=repositories) tab.

---

## Focus Areas

- **IoT solutions architecture** — device identity (X.509/JITP), MQTT at scale, cold chain and cargo monitoring, edge-to-cloud data pipelines
- **AWS cloud architecture** — IoT Core, Lambda, DynamoDB, CloudWatch, IAM — designed and deployed, not just documented
- **Operator tooling** — CLI design, AWS SDK integration, fleet management at scale
- **Multi-cloud IaC** — reusable Terraform patterns across AWS, Azure, and GCP
- **AI-enhanced DevOps** — LLM integration points that add signal without replacing engineer judgement
- **Security by default** — per-device X.509, least-privilege IAM, pre-LLM risk extraction

---

## Tech

| Domain | Tools |
|--------|-------|
| IoT | AWS IoT Core · MQTT · X.509 · paho-mqtt · Device Shadow |
| Cloud | AWS · Azure · GCP |
| IaC | Terraform · GitHub Actions |
| Languages | Python · Go · HCL |
| Databases | DynamoDB · CloudWatch Logs Insights |
| AI/LLM | Anthropic Claude · OpenAI GPT-4o · Azure OpenAI |

---

*Open to IoT Solutions Architect and Cloud Solutions Architect roles. [LinkedIn](https://linkedin.com/in/james-ward-95a81a2/)*
