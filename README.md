# UiPath (uipath)
UiPath is an enterprise automation platform specializing in robotic process automation (RPA), intelligent document processing, and end-to-end automation orchestration. The UiPath Automation Cloud provides a suite of developer APIs enabling programmatic access to orchestration, document understanding, automation pipeline management, testing, data services, and platform administration.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Robotic Process Automation, Automation, Orchestration, Enterprise, Document Processing, Integration

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-03-21

## APIs

### UiPath Orchestrator API
The UiPath Orchestrator API provides programmatic access to the core automation management platform, enabling developers to manage robots, jobs, processes, queues, assets, and schedules. Built on the OData protocol, the API supports RESTful operations with filtering, sorting, and pagination across all resources. It covers a broad set of resource categories including folders, machines, users, roles, alerts, webhooks, and libraries, making it suitable for enterprise automation governance and integration scenarios. Authentication uses OAuth 2.0 tokens from the UiPath Identity Server, and all endpoints are accessible under the tenant-scoped URL https://cloud.uipath.com/{organizationName}/{tenantName}/orchestrator_.

**Human URL:** [https://docs.uipath.com/orchestrator/automation-cloud/latest/api-guide/read-me](https://docs.uipath.com/orchestrator/automation-cloud/latest/api-guide/read-me)


#### Tags:

 - Robotic Process Automation, Orchestration, Automation, Enterprise

#### Properties

- [Documentation](https://docs.uipath.com/orchestrator/automation-cloud/latest/api-guide/read-me)
- [OpenAPI](openapi/uipath-orchestrator-openapi.yml)
- [AsyncAPI](asyncapi/uipath-orchestrator-webhooks-asyncapi.yml)
- [JSONSchema](json-schema/uipath-orchestrator-schema.json)

### UiPath Document Understanding API
The UiPath Document Understanding API enables programmatic access to intelligent document processing capabilities including digitization, classification, extraction, and validation of document content. The API supports both synchronous and asynchronous consumption patterns, with asynchronous mode suited for multi-page documents and batch workloads, and synchronous mode for real-time processing of single-page images up to five pages. Developers can integrate specialized machine learning models as well as generative AI-based classifiers and extractors into their applications. It is accessible via Swagger or any HTTP-compatible programming language and can be used in both RPA and non-RPA contexts.

**Human URL:** [https://docs.uipath.com/document-understanding/automation-cloud/latest/api-guide/api-overview](https://docs.uipath.com/document-understanding/automation-cloud/latest/api-guide/api-overview)


#### Tags:

 - Document Processing, Intelligent Document Processing, Machine Learning, Extraction

#### Properties

- [Documentation](https://docs.uipath.com/document-understanding/automation-cloud/latest/api-guide/api-overview)
- [OpenAPI](openapi/uipath-document-understanding-openapi.yml)
- [JSONSchema](json-schema/uipath-document-understanding-schema.json)

### UiPath Automation Hub API
The UiPath Automation Hub API provides access to the automation pipeline and idea management platform, allowing developers to programmatically create, retrieve, and manage automation ideas, projects, and pipeline data. The API is accessible at the tenant-scoped endpoint https://cloud.uipath.com/{orgName}/{tenantName}/automationhub_/api/v1/openapi/ and uses token-based authentication generated from the Automation Hub Admin Console. It is designed for organizations building Center of Excellence workflows, integrating Automation Hub data with external tools, or automating pipeline governance processes. A Postman collection and Swagger interface are available for exploring and testing available endpoints.

**Human URL:** [https://docs.uipath.com/automation-hub/automation-cloud/latest/api-guide/introduction-to-automation-hub-api-1](https://docs.uipath.com/automation-hub/automation-cloud/latest/api-guide/introduction-to-automation-hub-api-1)


#### Tags:

 - Automation Pipeline, Idea Management, Center of Excellence, Enterprise

#### Properties

- [Documentation](https://docs.uipath.com/automation-hub/automation-cloud/latest/api-guide/introduction-to-automation-hub-api-1)
- [OpenAPI](openapi/uipath-automation-hub-openapi.yml)

### UiPath Data Service API
The UiPath Data Service API, also referred to as the Data Fabric OpenAPI, enables external applications to interact with structured data entities stored in UiPath's cloud data platform. It supports schema management and data operations including reading, creating, updating, and deleting entity records, with access governed by granular role-based permissions. The API uses OAuth 2.0 for authorization, with access tokens valid for one hour and support for refresh tokens. Developers can download a tenant-specific OpenAPI 3.0 specification in JSON format from within the Data Service interface for use with code generation and integration tooling.

**Human URL:** [https://docs.uipath.com/data-service/automation-cloud/latest/user-guide/api-access](https://docs.uipath.com/data-service/automation-cloud/latest/user-guide/api-access)


#### Tags:

 - Data Management, Data Fabric, Storage, Enterprise

#### Properties

- [Documentation](https://docs.uipath.com/data-service/automation-cloud/latest/user-guide/api-access)
- [OpenAPI](openapi/uipath-data-service-openapi.yml)

### UiPath Test Manager API
The UiPath Test Manager API allows external tools and systems to integrate with UiPath's test management platform for managing test projects, test cases, requirements, and execution results programmatically. API access uses OAuth 2.0 scopes including TM.Projects and TM.Requirements.Read, enabling fine-grained control over permissions granted to integrated tooling. The API is suited for integrating third-party test management or defect tracking systems with UiPath automation testing workflows. Rate limits apply to API requests to ensure platform stability across all tenants.

**Human URL:** [https://docs.uipath.com/test-manager/automation-cloud/latest/user-guide/test-manager-api-integration](https://docs.uipath.com/test-manager/automation-cloud/latest/user-guide/test-manager-api-integration)


#### Tags:

 - Testing, Quality Assurance, Test Automation, RPA Testing

#### Properties

- [Documentation](https://docs.uipath.com/test-manager/automation-cloud/latest/user-guide/test-manager-api-integration)
- [OpenAPI](openapi/uipath-test-manager-openapi.yml)

### UiPath Integration Service
UiPath Integration Service provides a standardized framework for authorizing and authenticating connections to external SaaS applications and APIs from within UiPath automation workflows. It offers a library of prebuilt connectors to popular platforms and a connector builder for creating custom integrations against third-party REST APIs. The service manages credential storage and OAuth flows centrally, eliminating the need for per-robot credential management. It is designed to accelerate integration development by abstracting authentication complexity and providing reusable, governed API connections across an organization's automation portfolio.

**Human URL:** [https://docs.uipath.com/integration-service/automation-cloud/latest](https://docs.uipath.com/integration-service/automation-cloud/latest)


#### Tags:

 - Integration, Connectors, SaaS, API Management

#### Properties

- [Documentation](https://docs.uipath.com/integration-service/automation-cloud/latest)

### UiPath Platform Management API
The UiPath Platform Management API covers foundational platform administration resources including identity management, audit log access, and licensing operations. It provides programmatic control over organization-level and tenant-level settings that serve as the backbone of the UiPath Automation Cloud platform. These APIs are used by enterprise administrators to automate provisioning workflows, audit compliance activities, and manage license allocations across teams. The endpoints are accessible alongside the Orchestrator API and share the same OAuth 2.0 authentication mechanism using the UiPath Identity Server.

**Human URL:** [https://docs.uipath.com/orchestrator/standalone/2024.10/api-guide/platform-management-apis](https://docs.uipath.com/orchestrator/standalone/2024.10/api-guide/platform-management-apis)


#### Tags:

 - Identity Management, Licensing, Audit, Administration

#### Properties

- [Documentation](https://docs.uipath.com/orchestrator/standalone/2024.10/api-guide/platform-management-apis)
- [OpenAPI](openapi/uipath-platform-management-openapi.yml)

## Common Properties

- [Portal](https://cloud.uipath.com/)
- [Documentation](https://docs.uipath.com/)
- [Website](https://www.uipath.com/)
- [PrivacyPolicy](https://www.uipath.com/legal/privacy-policy)
- [TermsOfService](https://www.uipath.com/legal/termsofuse)
- [Support](https://www.uipath.com/company/contact-us/customer-service)
- [Blog](https://www.uipath.com/blog)
- [Login](https://cloud.uipath.com/portal_/login)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
