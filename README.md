# Amazon CodeGuru Security

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Amazon CodeGuru Security is a static application security testing (SAST) service that uses machine learning to detect security vulnerabilities in your code. It identifies vulnerabilities such as injection flaws, data exposure risks, and infrastructure-as-code misconfigurations, and provides actionable remediation guidance to help developers fix security issues quickly.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/amazon-codeguru-security/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon, AWS, Security, SAST, Code Analysis, DevSecOps, Developer Tools

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon CodeGuru Security API

The Amazon CodeGuru Security REST API.

**Human URL:** [https://docs.aws.amazon.com/codeguru/latest/security-api/Welcome.html](https://docs.aws.amazon.com/codeguru/latest/security-api/Welcome.html)

#### Tags:

 - Amazon, AWS, Security, SAST, Code Analysis

#### Properties

- [Documentation](https://docs.aws.amazon.com/codegurusecurity/)
- [APIReference](https://docs.aws.amazon.com/codeguru/latest/security-api/Welcome.html)
- [OpenAPI](openapi/amazon-codeguru-security-openapi-original.yaml)

## Common Properties

- [GettingStarted](https://docs.aws.amazon.com/codeguru/security)
- [Pricing](https://aws.amazon.com/codegurusecurity/pricing/)
- [Console](https://console.aws.amazon.com/codegurusecurity/)
- [Portal](https://aws.amazon.com/codegurusecurity/)
- [Documentation](https://docs.aws.amazon.com/codegurusecurity/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Blog](https://aws.amazon.com/blogs/devops/)
- [SignUp](https://portal.aws.amazon.com/gp/aws/developer/registration/index.html)
- [GitHubOrganization](https://github.com/aws)

## Features

| Name | Description |
|------|-------------|
| Static Application Security Testing | Analyze source code for security vulnerabilities without running the application using machine learning-powered SAST. |
| Multi-Language Support | Detect security issues in Java, Python, JavaScript, TypeScript, C, C++, C#, Go, Ruby, and Kotlin code. |
| Infrastructure-as-Code Scanning | Detect security misconfigurations in CloudFormation, Terraform, CDK, and other IaC templates. |
| Severity Classification | Classify findings by severity (Critical, High, Medium, Low, Informational) to help prioritize remediation. |
| Remediation Guidance | Provide detailed remediation recommendations including suggested code fixes for each identified vulnerability. |

## Use Cases

| Name | Description |
|------|-------------|
| DevSecOps Integration | Integrate security scanning into CI/CD pipelines to detect vulnerabilities before code reaches production. |
| Security Audit and Compliance | Run security scans on existing codebases to identify and remediate vulnerabilities for compliance audits. |
| IaC Security Validation | Scan infrastructure-as-code templates for security misconfigurations before provisioning cloud resources. |

## Integrations

| Name | Description |
|------|-------------|
| AWS CodeBuild | Run security scans as part of CodeBuild build projects for CI/CD integration. |
| GitHub Actions | Add CodeGuru Security scanning to GitHub Actions workflows. |
| AWS Security Hub | Send security findings to Security Hub for centralized security management. |
| Amazon S3 | Store and retrieve code bundles for security scanning from S3. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-codeguru-security-openapi-original](openapi/amazon-codeguru-security-openapi-original.yaml)

### JSON Schema

85 JSON Schema files generated from the OpenAPI specification.

- [amazon-codeguru-security-account-findings-metric-schema](json-schema/amazon-codeguru-security-account-findings-metric-schema.json)
- [amazon-codeguru-security-analysis-type-schema](json-schema/amazon-codeguru-security-analysis-type-schema.json)
- [amazon-codeguru-security-batch-get-findings-error-schema](json-schema/amazon-codeguru-security-batch-get-findings-error-schema.json)
- [amazon-codeguru-security-batch-get-findings-errors-schema](json-schema/amazon-codeguru-security-batch-get-findings-errors-schema.json)
- [amazon-codeguru-security-batch-get-findings-request-schema](json-schema/amazon-codeguru-security-batch-get-findings-request-schema.json)
- ...and 80 more in [json-schema/](json-schema/)

### JSON Structure

85 JSON Structure files in [json-structure/](json-structure/).

### JSON-LD

- [amazon-codeguru-security-context](json-ld/amazon-codeguru-security-context.jsonld)

### Examples

85 example JSON files in [examples/](examples/).

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [codegurusecurity](capabilities/shared/codegurusecurity.yaml) — 13 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon CodeGuru Security Application Security Scanning](capabilities/amazon-codeguru-security-security-scanning.yaml) | codegurusecurity | 7 | DevOps Engineer |

## Vocabulary

- [amazon-codeguru-security-vocabulary](vocabulary/amazon-codeguru-security-vocabulary.yaml) — Unified taxonomy mapping 9 resources, 5 actions, 1 workflows, and 3 personas

## Rules

- [amazon-codeguru-security-spectral-rules](rules/amazon-codeguru-security-spectral-rules.yml) — 10 rules enforcing Amazon CodeGuru Security API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
