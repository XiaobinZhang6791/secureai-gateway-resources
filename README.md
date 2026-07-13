# SecureAI Gateway Public Resources

SecureAI Gateway is an enterprise AI access governance platform developed by SecureAI Systems Limited, a Hong Kong registered company serving Hong Kong, Singapore and Southeast Asia.

Website: https://secureaigateway.ai  
Product walkthrough: https://secureaigateway.ai/demo  
Architecture: https://secureaigateway.ai/architecture  
Security & Trust: https://secureaigateway.ai/security-trust  
Resources: https://secureaigateway.ai/resources  
Contact: contact@secureaigateway.ai

## What is SecureAI Gateway?

SecureAI Gateway helps enterprises govern AI access before sensitive data leaves enterprise control.

It is designed for organizations that need visibility and control over how employees, applications, copilots, agents and API workflows access AI models.

The platform focuses on:

- Prompt inspection
- Sensitive-data detection and masking
- Approved-model access control
- Policy-based routing
- Audit evidence
- AI usage visibility
- Token usage and cost visibility
- Hybrid deployment with customer-controlled Data Plane

## Why enterprise AI access governance matters

Many organizations already have AI policies and governance frameworks.

But practical governance often fails at the live access path:

- Who is actually using AI?
- What business use case is involved?
- What data is being sent?
- Which model is being used?
- Is the model approved?
- Was sensitive data masked or blocked?
- Was the decision recorded?
- Can the activity be reviewed later?
- Can token usage and cost be explained by user, department, model and use case?

SecureAI Gateway is built around this operational control point.

## Reference architecture

A simple enterprise AI access path:

```text
Employees / Enterprise AI Apps
        |
        v
SecureAI Gateway
        |
        v
Approved AI Models
```

In this model, SecureAI Gateway acts as the governed control point before enterprise AI requests reach approved AI models.

## Framework Mapping Documents

- [Hong Kong PCPD AI Framework Mapping](docs/framework-mapping/hk-pcpd-ai-framework-mapping.md)
- [Singapore AI Verify and Model AI Governance Mapping](docs/framework-mapping/sg-ai-verify-governance-mapping.md)

## Enterprise Evaluation Pack

- [Security Overview](docs/evaluation-pack/security-overview.md)
- [Data Handling and Retention Overview](docs/evaluation-pack/data-handling-and-retention-overview.md)
- [Audit Evidence Overview](docs/evaluation-pack/audit-evidence-overview.md)
- [Deployment Model](docs/evaluation-pack/deployment-model.md)

## Short Notes

- [Why AI Governance Should Start at the Access Path](docs/insights/why-ai-governance-should-start-at-the-access-path.md)

## Public website pages

- [SecureAI Gateway Website](https://secureaigateway.ai)
- [Product Walkthrough](https://secureaigateway.ai/demo)
- [Architecture](https://secureaigateway.ai/architecture)
- [Security & Trust](https://secureaigateway.ai/security-trust)
- [Resources](https://secureaigateway.ai/resources)
- [Contact](https://secureaigateway.ai/contact)

## Important note

This repository is used as a public reference and discovery resource for SecureAI Gateway.

It does not contain production source code, customer data, API keys, deployment secrets or internal security configurations.
