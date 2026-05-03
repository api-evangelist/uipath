# UiPath (uipath)
UiPath is an enterprise automation platform offering robotic process automation (RPA), AI-powered automation, and agentic automation capabilities. The platform includes Orchestrator for managing robots and automation jobs, Studio for developing automation workflows, Document Understanding for intelligent document processing, Data Service for structured data storage, Automation Hub for pipeline management and governance, Test Manager for automated testing, and Platform Management for organization and tenant administration. UiPath provides Python SDKs, REST APIs, and a rich integration ecosystem supporting enterprise automation at scale.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Automation, Robotic Process Automation, RPA, Artificial Intelligence, Document Processing, Enterprise Automation, Orchestration, Testing

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-03

## APIs

### UiPath Orchestrator API
The UiPath Orchestrator API provides programmatic access to the core automation management platform, enabling developers to manage robots, jobs, processes, queues, assets, schedules, and more. Built on the OData protocol, the API supports RESTful operations with filtering, sorting, and pagination across all resources. Authentication uses OAuth 2.0 tokens from the UiPath Identity Server.

**Human URL:** [https://docs.uipath.com/orchestrator/automation-cloud/latest/api-guide/read-me](https://docs.uipath.com/orchestrator/automation-cloud/latest/api-guide/read-me)

#### Tags:

 - Orchestrator, Robots, Jobs, Queues, Automation

#### Properties

- [Documentation](https://docs.uipath.com/orchestrator/automation-cloud/latest/api-guide/read-me)
- [OpenAPI](openapi/uipath-orchestrator-openapi.yml)
- [AsyncAPI](asyncapi/uipath-orchestrator-webhooks-asyncapi.yml)
- [JSONSchema](json-schema/uipath-orchestrator-schema.json)
- [JSONStructure](json-structure/orchestrator-job-structure.json)
- [JSON-LD](json-ld/uipath-orchestrator-context.jsonld)

### UiPath Automation Hub API
The UiPath Automation Hub API provides access to the automation pipeline and idea management platform, allowing developers to programmatically create, retrieve, and manage automation ideas, projects, and pipeline data. Designed for organizations building Center of Excellence workflows and integrating Automation Hub with external tools.

**Human URL:** [https://docs.uipath.com/automation-hub/automation-cloud/latest/api-guide/introduction-to-automation-hub-api-1](https://docs.uipath.com/automation-hub/automation-cloud/latest/api-guide/introduction-to-automation-hub-api-1)

#### Tags:

 - Automation Hub, Pipeline Management, Center of Excellence, Ideas

#### Properties

- [Documentation](https://docs.uipath.com/automation-hub/automation-cloud/latest/api-guide/introduction-to-automation-hub-api-1)
- [OpenAPI](openapi/uipath-automation-hub-openapi.yml)
- [JSONSchema](json-schema/automation-hub-automation-schema.json)
- [JSONStructure](json-structure/automation-hub-automation-structure.json)
- [JSON-LD](json-ld/uipath-automation-hub-context.jsonld)

### UiPath Document Understanding API
The UiPath Document Understanding API enables intelligent document processing using machine learning and AI models. Developers can submit documents for digitization, classification, and data extraction, as well as manage custom ML models and training datasets.

**Human URL:** [https://docs.uipath.com/document-understanding/automation-cloud/latest/api-guide/api-overview](https://docs.uipath.com/document-understanding/automation-cloud/latest/api-guide/api-overview)

#### Tags:

 - Document Understanding, Machine Learning, OCR, Data Extraction, Intelligent Document Processing

#### Properties

- [Documentation](https://docs.uipath.com/document-understanding/automation-cloud/latest/api-guide/api-overview)
- [OpenAPI](openapi/uipath-document-understanding-openapi.yml)
- [JSONSchema](json-schema/uipath-document-understanding-schema.json)
- [JSONStructure](json-structure/document-understanding-digitization-result-structure.json)
- [JSON-LD](json-ld/uipath-document-understanding-context.jsonld)

### UiPath Data Service API
The UiPath Data Service API provides programmatic access to structured data storage within the UiPath Platform. Developers can create, read, update, and delete records in custom data entities, enabling automation workflows to read from and write to persistent cloud-based data stores.

**Human URL:** [https://docs.uipath.com/data-service/automation-cloud/latest/api-guide/about-the-data-service-api](https://docs.uipath.com/data-service/automation-cloud/latest/api-guide/about-the-data-service-api)

#### Tags:

 - Data Service, Data Storage, Records, Entities

#### Properties

- [Documentation](https://docs.uipath.com/data-service/automation-cloud/latest/api-guide/about-the-data-service-api)
- [OpenAPI](openapi/uipath-data-service-openapi.yml)
- [JSONSchema](json-schema/data-service-entity-record-schema.json)
- [JSONStructure](json-structure/data-service-entity-record-structure.json)
- [JSON-LD](json-ld/uipath-data-service-context.jsonld)

### UiPath Platform Management API
The UiPath Platform Management API provides administrative access to organization and tenant management capabilities, including user management, license management, and account configuration. Used by platform administrators to manage UiPath Automation Cloud organizations programmatically.

**Human URL:** [https://docs.uipath.com/automation-cloud/automation-cloud/latest/api-guide/accessing-uipath-resources-using-external-apps](https://docs.uipath.com/automation-cloud/automation-cloud/latest/api-guide/accessing-uipath-resources-using-external-apps)

#### Tags:

 - Platform Management, Administration, Organizations, Tenants, Licensing

#### Properties

- [Documentation](https://docs.uipath.com/automation-cloud/automation-cloud/latest/api-guide/accessing-uipath-resources-using-external-apps)
- [OpenAPI](openapi/uipath-platform-management-openapi.yml)
- [JSONStructure](json-structure/platform-management-user-structure.json)
- [JSON-LD](json-ld/uipath-platform-management-context.jsonld)

### UiPath Test Manager API
The UiPath Test Manager API enables programmatic interaction with the automated testing platform, allowing CI/CD pipelines and external tools to create test sets, execute tests, and retrieve test results. Supports enterprise-grade test management and reporting workflows.

**Human URL:** [https://docs.uipath.com/test-manager/automation-cloud/latest/api-guide/test-manager-api](https://docs.uipath.com/test-manager/automation-cloud/latest/api-guide/test-manager-api)

#### Tags:

 - Testing, Quality Assurance, CI/CD, Test Automation

#### Properties

- [Documentation](https://docs.uipath.com/test-manager/automation-cloud/latest/api-guide/test-manager-api)
- [OpenAPI](openapi/uipath-test-manager-openapi.yml)
- [JSONSchema](json-schema/test-manager-test-case-schema.json)
- [JSONStructure](json-structure/test-manager-test-case-structure.json)
- [JSON-LD](json-ld/uipath-test-manager-context.jsonld)

## Common Properties

- [Website](https://www.uipath.com)
- [Documentation](https://docs.uipath.com)
- [Portal](https://cloud.uipath.com)
- [Blog](https://www.uipath.com/blog)
- [Pricing](https://www.uipath.com/pricing)
- [Terms of Service](https://www.uipath.com/legal/terms-of-use)
- [Privacy Policy](https://www.uipath.com/legal/privacy-policy)
- [Support](https://support.uipath.com)
- [Status Page](https://status.uipath.com)
- [Academy](https://academy.uipath.com)
- [Forum](https://forum.uipath.com)
- [GitHub Organization](https://github.com/UiPath)
- [Python SDK](https://pypi.org/project/uipath/)
- [TypeScript SDK](https://github.com/UiPath/uipath-typescript)
- [MCP Server](https://github.com/UiPath/uipath-mcp-python)
- [CLI](https://github.com/UiPath/uipathcli)
- [Getting Started](https://docs.uipath.com/automation-cloud/docs/introduction)
- [Authentication](https://docs.uipath.com/automation-cloud/automation-cloud/latest/api-guide/accessing-uipath-resources-using-external-apps)

## Features

| Name | Description |
|------|-------------|
| Robotic Process Automation | Automate repetitive tasks across any application using software robots with no-code, low-code, and coded automation options. |
| AI-Powered Automation | Integrate AI capabilities including document understanding, computer vision, and natural language processing into automation workflows. |
| Agentic Automation | Build and deploy intelligent agents using Python, LangGraph, or LlamaIndex frameworks on the UiPath Agent Cloud. |
| Document Understanding | Extract structured data from unstructured documents using ML models for OCR, classification, and field extraction. |
| Orchestration | Centrally manage and monitor automation robots, jobs, queues, schedules, and assets across the enterprise. |
| Process Mining | Discover and analyze business processes to identify automation opportunities and measure impact. |
| Test Automation | Create, manage, and execute automated tests for RPA and application testing with enterprise CI/CD integration. |
| Integration Service | Connect to 1,000+ applications and services through pre-built connectors for enterprise integration. |

## Use Cases

| Name | Description |
|------|-------------|
| Finance and Accounting Automation | Automate invoice processing, accounts payable/receivable, financial reporting, and compliance workflows. |
| HR Onboarding Automation | Streamline employee onboarding, offboarding, payroll processing, and HR data management across systems. |
| Customer Service Automation | Automate customer inquiry routing, case management, data lookup, and response generation. |
| IT Process Automation | Automate IT service desk tickets, provisioning, monitoring alerts, and infrastructure management tasks. |
| Healthcare Administration | Automate patient data management, claims processing, prior authorization, and regulatory reporting. |
| Supply Chain Automation | Automate procurement, order management, inventory tracking, and logistics workflows. |

## Integrations

| Name | Description |
|------|-------------|
| Salesforce | Automate CRM operations, data sync, and customer workflows with native Salesforce integration. |
| SAP | Connect with SAP ERP and S/4HANA for automated finance, HR, and supply chain processes. |
| Microsoft 365 | Automate Office applications, SharePoint, Teams, and Azure services through Microsoft 365 integration. |
| ServiceNow | Integrate with ServiceNow for ITSM automation, ticket management, and service catalog workflows. |
| Workday | Connect with Workday HCM for HR automation, payroll processing, and workforce management. |
| LangChain and LangGraph | Build and deploy AI agents using LangChain and LangGraph frameworks on the UiPath platform. |

## Solutions

| Name | Description |
|------|-------------|
| Automation Cloud Basic | Entry-level cloud automation for individuals and small teams with basic RPA and limited scale. |
| Automation Cloud Standard | Professional automation platform for businesses with unlimited users, robots, and enterprise data extraction. |
| Automation Cloud Enterprise | Strategic enterprise automation with full infrastructure control, BYOK, multi-region deployment, and advanced AI capabilities. |
| Automation Cloud Public Sector | FedRAMP Moderate authorized automation solution for U.S. government and public sector organizations. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [UiPath Orchestrator API](openapi/uipath-orchestrator-openapi.yml)
- [UiPath Automation Hub API](openapi/uipath-automation-hub-openapi.yml)
- [UiPath Document Understanding API](openapi/uipath-document-understanding-openapi.yml)
- [UiPath Data Service API](openapi/uipath-data-service-openapi.yml)
- [UiPath Platform Management API](openapi/uipath-platform-management-openapi.yml)
- [UiPath Test Manager API](openapi/uipath-test-manager-openapi.yml)

### AsyncAPI

- [UiPath Orchestrator Webhook Events](asyncapi/uipath-orchestrator-webhooks-asyncapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [UiPath Orchestrator API](capabilities/shared/orchestrator.yaml) — 12 operations for robot, job, queue, and asset management
- [UiPath Automation Hub API](capabilities/shared/automation-hub.yaml) — 7 operations for pipeline and idea management
- [UiPath Document Understanding API](capabilities/shared/document-understanding.yaml) — 9 operations for document OCR, classification, and extraction
- [UiPath Data Service API](capabilities/shared/data-service.yaml) — 6 operations for entity record management
- [UiPath Platform Management API](capabilities/shared/platform-management.yaml) — 5 operations for user, group, and license management
- [UiPath Test Manager API](capabilities/shared/test-manager.yaml) — 8 operations for test project and execution management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Automation Operations](capabilities/automation-operations.yaml) | Orchestrator, Data Service | 10 | RPA Developer, Automation Operator |
| [Intelligent Document Processing](capabilities/intelligent-document-processing.yaml) | Document Understanding, Orchestrator | 7 | Document Processing Specialist, RPA Developer |
| [Automation Governance](capabilities/automation-governance.yaml) | Automation Hub, Platform Management, Test Manager | 11 | CoE Manager, Platform Administrator, QA Engineer |

## Vocabulary

- [UiPath Vocabulary](vocabulary/uipath-vocabulary.yaml) — Unified taxonomy mapping 24 resources, 15 actions, 3 workflows, and 6 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [UiPath Spectral Rules](rules/uipath-spectral-rules.yml) — 40 rules across 13 categories enforcing UiPath API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
