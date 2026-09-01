# Sidd Chauhan

## I turn messy customer and operational context into AI systems teams can inspect, approve, and act on.

I work in the handoff between a user's messy reality and a technical system that has to behave reliably. I translate the workflow into data contracts, evaluations, human review gates, and evidence a decision owner can inspect.

I'm targeting AI Solutions Engineer, Forward Deployed Engineer, and AI Implementation roles. I do my best work close to the customer, close to the data, and accountable for whether the workflow holds up.

[Portfolio](https://siddchauhan.vercel.app) | [LinkedIn](https://www.linkedin.com/in/siddchauhan77/) | [Writing](https://draftstodone.substack.com)

## 3 systems worth inspecting

### Enterprise Customer Launch Agent

[Repository](https://github.com/siddchauhan77/enterprise-customer-launch-agent) | [Live demo](https://enterprise-customer-launch-agent.vercel.app)

Models the high-risk parts of a 10,000-record CRM launch: invalid data, scope drift, unapproved writes, interrupted jobs, duplicate retries, and rollback.

The workflow profiles source data, quarantines invalid rows, fingerprints the approved scope, runs idempotent mock writes, resumes after interruption, and emits audit receipts. It uses fictional data and a Salesforce-compatible mock adapter, with no claim of real Salesforce access or customer deployment.

### Complaint Triage Reliability Harness

[Repository](https://github.com/siddchauhan77/complaint-triage-harness) | [Live writeup](https://complaint-triage-harness.vercel.app)

Built on 13,991 public CFPB complaints. The harness declared 8 failure modes before implementation and detected all 5 failures that manifested.

One test held product classification at 71.0% while legal-threat detection collapsed to 19.4% and model confidence stayed near 0.96. The system exposed silent upstream information loss that aggregate accuracy hid. This is an offline evaluation with stated label, sample-size, and deployment limitations.

### NYC Mobility Operations

[Repository](https://github.com/siddchauhan77/nyc-mobility-operations) | [Live case study](https://nyc-mobility-operations.vercel.app)

Turns 3,724,889 official NYC taxi records into a smaller, explainable review queue.

The pipeline reduced 8,423 first-pass alerts to 436 evidence-linked review prompts, a 94.8% reduction, and passed 8/8 deterministic tests. It proves data controls, provenance, anomaly scoring, and human-review boundaries. It does not claim operator adoption, causal impact, or production-service ownership.

## More proof

| Project | What to inspect |
| --- | --- |
| [AI Website Production System](https://ai-website-production-system.vercel.app) | Sourced fact registry, deterministic generation, validation, and machine-readable QA |
| [FunnelTeardown AI](https://funnel-teardown.vercel.app) | Typed agent state, source-linked analysis, cost tracking, and exportable decision reports |
| [Creative Strategy Vault](https://creative-strategy-vault.vercel.app/vault.html#sk-index) | Source-labeled research and workflows for audience insight, creative angles, production briefs, and QA |

## Background

MSBA, UT Austin McCombs. B.S. Public Health, Texas A&M. Based in Houston, Texas.

## Contact

If you're hiring for AI solutions or implementation work, or building an AI workflow with messy data and risky handoffs, message me on [LinkedIn](https://www.linkedin.com/in/siddchauhan77/). Start with the workflow, its user, and the failure you worry about most.
