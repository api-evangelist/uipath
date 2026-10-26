# UiPath (uipath)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
