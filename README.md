# Amazon CodeGuru Security

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
