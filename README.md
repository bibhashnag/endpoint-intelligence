# endpoint-intelligence

> Building an AI-driven endpoint observability stack — telemetry pipelines,
> KQL analytics, Graph API automation, and AI-assisted remediation.

## Architecture vision

```
Endpoints → Telemetry Collection → ADX / Log Analytics
         → AI Correlation Engine → Copilot / AI Agents
         → Automation Engine    → Self-Healing Actions
```

## What's in this repo

| Folder | Contents |
|---|---|
| `kql-queries/` | Production KQL queries for Intune, Defender, and ADX telemetry |
| `adx-schemas/` | ADX table schemas and ingestion policies |
| `graph-api/` | PowerShell + Python scripts for Intune Graph API automation |
| `dashboards/` | Endpoint health and observability dashboard definitions |
| `automation/` | Remediation workflows and autonomous action scripts |
| `ai-prototypes/` | AI-assisted diagnosis and prediction prototypes |
| `docs/` | Architecture diagrams and design documentation |

## Projects

### Project 1 — Endpoint Health Analytics Dashboard *(Week 8)*
KQL-powered observability dashboard: compliance %, patch age, enrollment health,
OS spread, anomaly detection. Built on ADX with Power BI integration.

### Project 2 — AI-Assisted Device Investigator *(Week 10)*
Python app that pulls device telemetry from ADX, sends context to Azure OpenAI,
and returns a diagnosis + recommended remediation actions.

## Skills being built
`KQL` `Azure Data Explorer` `Microsoft Graph API` `PowerShell` `Python`
`Azure OpenAI` `Intune` `Endpoint Telemetry` `AIOps` `Observability`

## Background
Infrastructure + endpoint operations → AI-enabled endpoint architecture.
Transitioning toward: AI Operations Architect / Endpoint Intelligence Engineer.
