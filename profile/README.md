<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/scix-banner-wide.png">
  <source media="(prefers-color-scheme: light)" srcset="./assets/scix-banner-centered.png">
  <img alt="SCIX — Science & Experimental Technologies" src="./assets/scix-banner-wide.png" width="100%">
</picture>

# AIMix

### One gateway. Every model. Smart execution.

**An open-source, self-hosted AI gateway by Science Experimental Technologies (SCIX).**

[![License: MIT](https://img.shields.io/badge/License-MIT-075BFF?style=flat-square)](https://github.com/Science-Experimental-Technologies/AIMix/blob/main/LICENSE)
[![Runtime: Node.js](https://img.shields.io/badge/Runtime-Node.js%2020.9%2B-339933?style=flat-square&logo=nodedotjs&logoColor=white)](https://github.com/Science-Experimental-Technologies/AIMix)
[![Active provider adapters](https://img.shields.io/badge/Active%20provider%20adapters-120%2B-075BFF?style=flat-square)](https://github.com/Science-Experimental-Technologies/AIMix)
[![Email](https://img.shields.io/badge/Contact-scix.official%40gmail.com-0F172A?style=flat-square&logo=gmail&logoColor=white)](mailto:scix.official@gmail.com)
[![YouTube](https://img.shields.io/badge/YouTube-ScExTe-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@ScExTe)

[Explore AIMix](https://github.com/Science-Experimental-Technologies/AIMix) · [Read the docs](https://github.com/Science-Experimental-Technologies/AIMix#readme) · [Discuss collaboration](mailto:scix.official@gmail.com)

**Brand palette:** `#0B0F16` · `#075BFF` · `#F5F7FA`

</div>

---

## About

Science Experimental Technologies builds AIMix, a self-hosted gateway for connecting applications, developer tools, and agents to AI model providers through a consistent interface. AIMix addresses the operational friction of fragmented APIs, credentials, routing rules, and usage visibility. Teams can route requests directly or apply policy-aware selection, fallback, and observability from a control plane they operate. The project is open source under MIT, so teams can inspect the implementation and evaluate fit before adoption.

## Mission & Vision

**Mission** — Make model access easier to operate, govern, and understand across tools and providers.

**Vision** — Give every team a transparent, adaptable control layer for building with AI.

## What We Build

| Focus area | What AIMix provides | Examples |
| --- | --- | --- |
| 🔌 Unified model access | Compatible interfaces for applications and developer tools. | Chat, responses, images, speech, embeddings, search |
| 🧭 Routing & resilience | Direct and adaptive routing with health-aware retries and fallback. | Provider, model, latency, quota, cost, and policy signals |
| 📊 Operations & FinOps | Request traces, usage controls, budgets, and what-if simulations. | Observability, anomaly detection, spend management |
| 🛡️ Agent governance | Controls for agent actions, tools, workflows, and sensitive data. | RBAC, tool registry, workflow DAGs, redaction, audit trail |

## AIMix in Practice

<p align="center">
  <img src="./assets/aimix-dashboard.png" alt="AIMix provider management dashboard" width="88%">
</p>

**Request path:** Applications and tools → AIMix gateway → cloud or local model providers. Policy, routing, credentials, and visibility are managed at the gateway.

## Featured Project

| Project | Description | Stack | License | Status |
| --- | --- | --- | --- | --- |
| [AIMix](https://github.com/Science-Experimental-Technologies/AIMix) | A self-hosted AI gateway and decision layer for models, agents, and developer tools. | JavaScript · Node.js · Next.js | MIT | Active development |

See the [repository README](https://github.com/Science-Experimental-Technologies/AIMix#readme) for setup, supported interfaces, deployment options, and current capabilities.

## Technology

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111111)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

The AIMix project documentation describes **120+ active runtime provider adapters**. Provider availability and capabilities can vary; consult the repository and documentation for current details.

## Why Partner With Us

### For Companies

- **Deploy on your terms:** self-host AIMix and keep control of your gateway environment.
- **Integrate through familiar interfaces:** connect compatible applications and tools to a shared routing layer.
- **Review before adoption:** inspect the code and MIT license, then evaluate security and operational fit with your team.

### For Researchers

- **Experiment across providers:** compare model behavior and routing strategies through one gateway.
- **Make operations observable:** use request traces and simulation-oriented controls to study system behavior.
- **Collaborate openly:** discuss reproducible evaluations, integrations, and improvements in public project channels.

### For Contributors

- **Build useful infrastructure:** improve adapters, routing, documentation, integrations, and governance features.
- **Work in the open:** propose changes through issues and pull requests, following project contribution guidance.
- **Shape priorities:** share use cases and technical feedback directly with maintainers.

## Collaboration & Sponsorship

We welcome conversations about **sponsorship, joint research, custom integrations, pilot evaluations, and mentoring**. Start with a short note describing your goals, constraints, and the team or use case involved.

**Contact:** [scix.official@gmail.com](mailto:scix.official@gmail.com) · [Open an AIMix discussion](https://github.com/Science-Experimental-Technologies/AIMix/discussions)

Sponsorship link: not currently published. Contact us to discuss support options.

## Roadmap Direction

Current priorities documented by the project include:

- Expand provider conformance and lifecycle coverage.
- Improve observability integrations and policy authoring workflows.
- Strengthen plugin isolation, permissions, and developer tooling.
- Improve SDK and API reference coverage, and release artifact integrity.

These are project directions; follow the [AIMix repository](https://github.com/Science-Experimental-Technologies/AIMix) for the latest plans and changes.

## Trust & Security

Review the policies and project terms in the AIMix repository:

- [Security policy](https://github.com/Science-Experimental-Technologies/AIMix/blob/main/SECURITY.md)
- [Code of Conduct](https://github.com/Science-Experimental-Technologies/AIMix/blob/main/CODE_OF_CONDUCT.md)
- [Contributing guide](https://github.com/Science-Experimental-Technologies/AIMix/blob/main/CONTRIBUTING.md)
- [Governance](https://github.com/Science-Experimental-Technologies/AIMix/blob/main/GOVERNANCE.md)
- [MIT License](https://github.com/Science-Experimental-Technologies/AIMix/blob/main/LICENSE)

**Responsible disclosure:** Please follow the private reporting instructions in `SECURITY.md`. Avoid posting exploitable vulnerability details in public issues; maintainers will coordinate assessment and remediation through the published policy.

## Get Involved

1. **Explore:** read the [AIMix documentation](https://github.com/Science-Experimental-Technologies/AIMix#readme) and review the code.
2. **Choose a task:** browse [open issues](https://github.com/Science-Experimental-Technologies/AIMix/issues) and look for issues labeled `good first issue`.
3. **Contribute:** open an issue to align on larger changes, then submit a pull request using the repository guidance.

For proposals, questions, or partnership inquiries, email [scix.official@gmail.com](mailto:scix.official@gmail.com). Follow project updates on [YouTube](https://www.youtube.com/@ScExTe).

---

<div align="center">

**Build the control layer your AI systems deserve.**

Made in the open by [Science Experimental Technologies](https://github.com/Science-Experimental-Technologies).

</div>
