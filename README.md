# NAVIS AI — Naval Assistance & Verification Intelligence System

**2025–2026 FBLA Collegiate Technology & Computer Science Case Competition**

**Project Type:** AI Systems Design | Cybersecurity | Responsible AI | Solution Architecture

## Project Overview

NAVIS AI is a conceptual AI-assisted programming solution developed for the Naval Surface Warfare Center Carderock Division (NSWCCD) case competition.

The project addresses a critical challenge in AI adoption: how can engineering teams leverage AI to accelerate software development while maintaining security, accuracy, accountability, and human oversight?

Our proposed solution introduces a controlled AI engineering assistant designed to support early-stage naval research and development workflows.

**Core Principle: AI Proposes → Evidence Verifies → Engineers Decide.**

## The Challenge

AI-assisted programming tools can improve productivity through code generation, debugging, testing, and documentation. However, their use in sensitive engineering environments introduces several risks:

- **AI Hallucinations:** Incorrect code or explanations that appear technically plausible.
- **Security Vulnerabilities:** Insecure dependencies, inadequate input validation, or hidden defects.
- **Automation Bias:** Excessive reliance on AI-generated recommendations without sufficient human review.
- **Data Protection:** Potential exposure of sensitive engineering information.

The objective was to design a responsible AI workflow that enhances engineering productivity without granting AI autonomous decision-making authority.

## Proposed Solution: NAVIS AI

NAVIS AI uses a five-stage controlled workflow:

1. **Intake:** Engineers submit approved programming tasks and inputs.
2. **Analyze:** The system identifies the task type, evaluates assumptions, and assigns a risk level.
3. **Propose:** AI generates code recommendations, explanations, and supporting evidence.
4. **Verify:** A sandbox executes automated unit tests, static analysis, and security scans.
5. **Approve:** Engineers review verification results and approve or reject recommendations.

The architecture separates AI-generated recommendations from independent validation and human authorization.

### Risk-Based Decision Framework

| Risk Level | Use Case | Required Action |
|---|---|---|
| Tier 1 — Low | Programming education, syntax assistance, simple examples | Standard response with manual user verification |
| Tier 2 — Moderate | Research-code debugging and unit testing | Mandatory sandbox testing and engineer review |
| Tier 3 — Restricted | Classified data and safety-critical operational code | Block or escalate; no AI action |

## Security and Governance

The solution incorporates four primary safeguards:

- **Data Protection:** Approved environments and restrictions on classified or sensitive information.
- **Fail-Closed Reliability:** Independent security checks prevent progression when validation fails.
- **Full Traceability:** Audit records document prompts, model versions, verification evidence, and approvals.
- **Human Authority:** AI cannot autonomously commit code or modify operational systems.

## Demonstration Scenario

The pitch presented a conceptual debugging example involving a Python function that incorrectly calculates an average using a synthetic dataset.

NAVIS AI identifies a potential division-by-zero error, recommends explicit boundary validation, and routes the proposed correction through automated testing and engineer review.

This example illustrates how AI recommendations can be evaluated before acceptance.

## Implementation Roadmap

**Phase 1 — Discover:** Identify low-risk use cases and align requirements with cybersecurity and legal stakeholders.

**Phase 2 — Prototype:** Design a sandboxed environment with synthetic code, automated checks, request routing, and audit logging.

**Phase 3 — Evaluate:** Assess technical correctness, security findings, time savings, and engineer adoption.

**Phase 4 — Governed Expansion:** Consider broader implementation only after formal authorization and documented performance results.

## Proposed Key Performance Indicators

| KPI | Measurement |
|---|---|
| Correctness | Percentage of AI suggestions passing automated tests |
| Security Quality | Vulnerabilities introduced, missed, or identified |
| Task Efficiency | Development time compared with a manual baseline |
| Human Oversight | Review completion and rejection rates |
| Traceability | Percentage of outputs with complete verification records |

These KPIs form an evaluation framework. No actual deployment or performance improvements were claimed.

## Frameworks and References

The design draws on responsible AI and secure software development principles, including:

- U.S. Department of Defense Responsible AI Strategy & Implementation Pathway
- Department of the Navy Generative AI Guidance
- NIST AI Risk Management Framework
- IEEE and ACM Software Security Standards

## Project Deliverables

- 13-slide executive pitch deck, including references and image credits
- Five-stage AI solution architecture
- Risk-based request routing framework
- Security and governance controls
- Phased pilot implementation roadmap
- KPI and evaluation framework

## Project Status

**Conceptual Design / Competition Proposal**

NAVIS AI was presented as a conceptual solution for the FBLA Collegiate case competition. It is not an operational Navy system or a deployed AI application.

## Key Takeaways

This project strengthened our ability to translate technical challenges into practical solutions for executive stakeholders.

It combined cybersecurity risk assessment, secure software development, responsible AI governance, system architecture, and performance evaluation into one cohesive proposal.

The central takeaway was that successful AI adoption requires more than automation. It requires independent verification, transparent decision-making, and meaningful human accountability.

**AI Proposes. Evidence Verifies. Engineers Decide.**
