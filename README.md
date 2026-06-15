# UiPath (uipath)

UiPath is an enterprise automation platform offering robotic process automation (RPA), AI-powered automation, and agentic automation capabilities. The platform includes Orchestrator for managing robots and automation jobs, Studio for developing automation workflows, Document Understanding for intelligent document processing, Data Service for structured data storage, Automation Hub for pipeline management and governance, Test Manager for automated testing, and Platform Management for organization and tenant administration. UiPath provides Python SDKs, REST APIs, and a rich integration ecosystem supporting enterprise automation at scale.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Automation
- Robotic Process Automation
- RPA
- Artificial Intelligence
- Document Processing
- Enterprise Automation
- Orchestration
- Testing

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### UiPath Orchestrator API

The UiPath Orchestrator API provides programmatic access to the core automation management platform, enabling developers to manage robots, jobs, processes, queues, assets, schedules, and more. Built on the OData protocol, the API supports RESTful operations with filtering, sorting, and pagination across all resources. Authentication uses OAuth 2.0 tokens from the UiPath Identity Server.

- **Human URL:** [https://docs.uipath.com/orchestrator/automation-cloud/latest/api-guide/read-me](https://docs.uipath.com/orchestrator/automation-cloud/latest/api-guide/read-me)
- **Base URL:** `https://cloud.uipath.com/{organizationName}/{tenantName}/orchestrator_`

#### Tags

- Orchestrator
- Robots
- Jobs
- Queues
- Automation

#### Properties

- [Documentation](https://docs.uipath.com/orchestrator/automation-cloud/latest/api-guide/read-me)
- [OpenAPI](openapi/uipath-orchestrator-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uipath-orchestrator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uipath-orchestrator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/uipath-orchestrator-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/uipath-orchestrator-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orchestrator-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orchestrator-robot-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orchestrator-queue-definition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orchestrator-queue-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orchestrator-asset-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/orchestrator-job-structure.json)
- [JSON-LD](json-ld/uipath-orchestrator-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### UiPath Automation Hub API

The UiPath Automation Hub API provides access to the automation pipeline and idea management platform, allowing developers to programmatically create, retrieve, and manage automation ideas, projects, and pipeline data. Designed for organizations building Center of Excellence workflows and integrating Automation Hub with external tools.

- **Human URL:** [https://docs.uipath.com/automation-hub/automation-cloud/latest/api-guide/introduction-to-automation-hub-api-1](https://docs.uipath.com/automation-hub/automation-cloud/latest/api-guide/introduction-to-automation-hub-api-1)
- **Base URL:** `https://cloud.uipath.com/{orgName}/{tenantName}/automationhub_/api/v1`

#### Tags

- Automation Hub
- Pipeline Management
- Center of Excellence
- Ideas

#### Properties

- [Documentation](https://docs.uipath.com/automation-hub/automation-cloud/latest/api-guide/introduction-to-automation-hub-api-1)
- [OpenAPI](openapi/uipath-automation-hub-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uipath-automation-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uipath-automation-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/automation-hub-automation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/automation-hub-automation-structure.json)
- [JSON-LD](json-ld/uipath-automation-hub-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### UiPath Document Understanding API

The UiPath Document Understanding API enables intelligent document processing using machine learning and AI models. Developers can submit documents for digitization, classification, and data extraction, as well as manage custom ML models and training datasets.

- **Human URL:** [https://docs.uipath.com/document-understanding/automation-cloud/latest/api-guide/api-overview](https://docs.uipath.com/document-understanding/automation-cloud/latest/api-guide/api-overview)
- **Base URL:** `https://cloud.uipath.com/{organizationName}/{tenantName}/du_`

#### Tags

- Document Understanding
- Machine Learning
- OCR
- Data Extraction
- Intelligent Document Processing

#### Properties

- [Documentation](https://docs.uipath.com/document-understanding/automation-cloud/latest/api-guide/api-overview)
- [OpenAPI](openapi/uipath-document-understanding-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uipath-document-understanding.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uipath-document-understanding.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/uipath-document-understanding-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/document-understanding-digitization-result-structure.json)
- [JSON-LD](json-ld/uipath-document-understanding-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### UiPath Data Service API

The UiPath Data Service API provides programmatic access to structured data storage within the UiPath Platform. Developers can create, read, update, and delete records in custom data entities, enabling automation workflows to read from and write to persistent cloud-based data stores.

- **Human URL:** [https://docs.uipath.com/data-service/automation-cloud/latest/api-guide/about-the-data-service-api](https://docs.uipath.com/data-service/automation-cloud/latest/api-guide/about-the-data-service-api)
- **Base URL:** `https://cloud.uipath.com/{organizationName}/{tenantName}/dataservice_`

#### Tags

- Data Service
- Data Storage
- Records
- Entities

#### Properties

- [Documentation](https://docs.uipath.com/data-service/automation-cloud/latest/api-guide/about-the-data-service-api)
- [OpenAPI](openapi/uipath-data-service-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uipath-data-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uipath-data-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/data-service-entity-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/data-service-entity-record-structure.json)
- [JSON-LD](json-ld/uipath-data-service-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### UiPath Platform Management API

The UiPath Platform Management API provides administrative access to organization and tenant management capabilities, including user management, license management, and account configuration. Used by platform administrators to manage UiPath Automation Cloud organizations programmatically.

- **Human URL:** [https://docs.uipath.com/automation-cloud/automation-cloud/latest/api-guide/accessing-uipath-resources-using-external-apps](https://docs.uipath.com/automation-cloud/automation-cloud/latest/api-guide/accessing-uipath-resources-using-external-apps)
- **Base URL:** `https://cloud.uipath.com`

#### Tags

- Platform Management
- Administration
- Organizations
- Tenants
- Licensing

#### Properties

- [Documentation](https://docs.uipath.com/automation-cloud/automation-cloud/latest/api-guide/accessing-uipath-resources-using-external-apps)
- [OpenAPI](openapi/uipath-platform-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uipath-platform-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uipath-platform-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Structure](json-structure/platform-management-user-structure.json)
- [JSON-LD](json-ld/uipath-platform-management-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### UiPath Test Manager API

The UiPath Test Manager API enables programmatic interaction with the automated testing platform, allowing CI/CD pipelines and external tools to create test sets, execute tests, and retrieve test results. Supports enterprise-grade test management and reporting workflows.

- **Human URL:** [https://docs.uipath.com/test-manager/automation-cloud/latest/api-guide/test-manager-api](https://docs.uipath.com/test-manager/automation-cloud/latest/api-guide/test-manager-api)
- **Base URL:** `https://cloud.uipath.com/{organizationName}/{tenantName}/testmanager_`

#### Tags

- Testing
- Quality Assurance
- CI/CD
- Test Automation

#### Properties

- [Documentation](https://docs.uipath.com/test-manager/automation-cloud/latest/api-guide/test-manager-api)
- [OpenAPI](openapi/uipath-test-manager-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uipath-test-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uipath-test-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/test-manager-test-case-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/test-manager-test-case-structure.json)
- [JSON-LD](json-ld/uipath-test-manager-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/uipath)
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
- [SDK](https://pypi.org/project/uipath/)
- [SDK](https://github.com/UiPath/uipath-python)
- [SDK](https://github.com/UiPath/uipath-langchain-python)
- [SDK](https://github.com/UiPath/uipath-typescript)
- [SDK](https://github.com/UiPath/uipath-integrations-python)
- [Tools](https://github.com/UiPath/uipath-mcp-python)
- [C L I](https://github.com/UiPath/uipathcli)
- [C L I](https://docs.uipath.com/automation-cloud/docs/uipath-cli)
- [Sign Up](https://cloud.uipath.com/portal_/cloudrpa)
- [Getting Started](https://docs.uipath.com/automation-cloud/docs/introduction)
- [Authentication](https://docs.uipath.com/automation-cloud/automation-cloud/latest/api-guide/accessing-uipath-resources-using-external-apps)
- [Spectral Rules](rules/uipath-spectral-rules.yml)
- [Vocabulary](vocabulary/uipath-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)
- [M C P Server](https://github.com/UiPath/uipath-mcp-python)
- [Agent Skill](https://github.com/UiPath/skills)
- [L L Ms Txt](https://docs.uipath.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
