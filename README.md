# Ariba Guided Buying (ariba-guided-buying)

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

SAP Ariba Guided Buying provides a consumer-like shopping experience for enterprise procurement, enabling employees to find and purchase goods and services through an intuitive catalog-driven interface with built-in approval workflows and policy compliance.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ariba-guided-buying/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - B2B, Catalog, ERP, Procurement, Requisitions, SAP, Supply Chain

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Ariba Guided Buying - Public Catalogs Shop API
The Public Catalogs Shop API enables applications to retrieve data related to catalog items, filter facets, and matching search suggestions from public catalogs on SAP Business Network. This API supports SAP Ariba Buying, base edition, integrated with SAP S/4HANA Cloud Public Edition.

**Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)

#### Tags:

 - Catalog, Procurement, Shopping

#### Properties

- [Documentation](https://help.sap.com/doc/f2393ece78554efab2087b984c6fa90b/cloud/en-US/5e12bd6c87f24e0781a5fcdfb410ddc6.pdf)
- [OpenAPI](openapi/ariba-guided-buying-catalog-shop-api.yaml)
- [JSONSchema](json-schema/catalog-shop-api-shop-response-schema.json)
- [JSONSchema](json-schema/catalog-shop-api-catalog-item-schema.json)
- [JSONSchema](json-schema/catalog-shop-api-facet-schema.json)
- [JSONSchema](json-schema/catalog-shop-api-items-response-schema.json)
- [JSONSchema](json-schema/catalog-shop-api-auto-complete-response-schema.json)
- [JSONStructure](json-structure/catalog-shop-api-shop-response-structure.json)
- [JSONStructure](json-structure/catalog-shop-api-catalog-item-structure.json)
- [JSON-LD](json-ld/ariba-guided-buying-catalog-shop-api-context.jsonld)

### Ariba Guided Buying - Asset Management API
The Asset Management API enables developers to retrieve purchase requisitions consisting of asset items and update asset data on those requisitions. This API is applicable for SAP ERP-integrated sites that have enabled the asset management feature.

**Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)

#### Tags:

 - Asset Management, ERP, Procurement, Requisitions

#### Properties

- [Documentation](https://help.sap.com/doc/16e046861d874557a33a1831b778d998/cloud/en-US/45d3c37cf5a643c38b9e26cc31c97470.pdf)
- [OpenAPI](openapi/ariba-guided-buying-asset-management-api.yaml)
- [JSONSchema](json-schema/asset-management-api-requisition-schema.json)
- [JSONSchema](json-schema/asset-management-api-asset-line-item-schema.json)
- [JSONSchema](json-schema/asset-management-api-batch-asset-update-request-schema.json)
- [JSONStructure](json-structure/asset-management-api-requisition-structure.json)
- [JSONStructure](json-structure/asset-management-api-asset-line-item-structure.json)
- [JSON-LD](json-ld/ariba-guided-buying-asset-management-api-context.jsonld)

## Common Properties

- [Website](https://www.sap.com/products/spend-management/guided-buying.html)
- [Documentation](https://help.sap.com/docs/ariba-apis)
- [GettingStarted](https://help.sap.com/docs/ariba-apis/help-for-sap-ariba-developer-portal/sap-ariba-developer-portal-quick-start-guide-for-developers)
- [Portal](https://developer.ariba.com)
- [Authentication](https://help.sap.com/docs/ariba-apis/help-for-sap-ariba-developer-portal/sap-ariba-developer-portal-authentication)
- [TermsOfService](https://www.sap.com/corporate/en/legal/terms-of-use.html)
- [PrivacyPolicy](https://www.sap.com/about/legal/privacy.html)
- [Support](https://help.sap.com/ariba)
- [GitHubOrganization](https://github.com/SAP-samples)
- [CodeExamples - SAP Ariba Extensibility Samples](https://github.com/SAP-samples/ariba-extensibility-samples)

## Features

| Name | Description |
|------|-------------|
| Consumer-Like Shopping Experience | Provides employees with an intuitive catalog-driven shopping interface similar to consumer e-commerce applications. |
| Catalog Search and Typeahead | Full-text search with typeahead autocomplete for finding catalog items from suppliers on SAP Business Network. |
| Policy Compliance Enforcement | Built-in procurement policy checks ensure purchases comply with organizational spending rules and approval workflows. |
| Asset Management Integration | Integrates with SAP ERP asset management to assign and track asset numbers on requisition line items. |
| OAuth 2.0 Authentication | Secure API access using OAuth 2.0 client credentials flow with per-API credentials. |
| Faceted Search | Retrieves filter facets alongside catalog items enabling refined product browsing and discovery. |

## Use Cases

| Name | Description |
|------|-------------|
| Employee Self-Service Procurement | Enable employees to browse and purchase approved goods from supplier catalogs without manual procurement processes. |
| ERP Asset Record Import | Import asset records from SAP ERP and assign unique asset values to line items on approved requisitions. |
| Catalog Integration | Integrate SAP Ariba Buying with SAP S/4HANA Cloud Public Edition to access public supplier catalogs on SAP Business Network. |
| Requisition Automation | Automate retrieval and processing of asset-based requisitions through the Asset Workbench workflow. |

## Integrations

| Name | Description |
|------|-------------|
| SAP S/4HANA Cloud | Integrates with SAP S/4HANA Cloud Public Edition for purchase request creation and order management. |
| SAP Business Network | Connects to SAP Business Network to access public supplier catalogs and pricing. |
| SAP ERP | Integrates with SAP ERP systems for asset management and purchase order creation. |
| SAP Integration Suite | Extends SAP Ariba functionality through SAP Integration Suite for custom workflows and data transformations. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Ariba Guided Buying - Public Catalogs Shop API](openapi/ariba-guided-buying-catalog-shop-api.yaml)
- [Ariba Guided Buying - Asset Management API](openapi/ariba-guided-buying-asset-management-api.yaml)

### JSON Schema

- [catalog-shop-api-shop-response-schema](json-schema/catalog-shop-api-shop-response-schema.json)
- [catalog-shop-api-catalog-item-schema](json-schema/catalog-shop-api-catalog-item-schema.json)
- [catalog-shop-api-facet-schema](json-schema/catalog-shop-api-facet-schema.json)
- [catalog-shop-api-items-response-schema](json-schema/catalog-shop-api-items-response-schema.json)
- [catalog-shop-api-auto-complete-response-schema](json-schema/catalog-shop-api-auto-complete-response-schema.json)
- [catalog-shop-api-facet-value-schema](json-schema/catalog-shop-api-facet-value-schema.json)
- [asset-management-api-requisition-schema](json-schema/asset-management-api-requisition-schema.json)
- [asset-management-api-asset-line-item-schema](json-schema/asset-management-api-asset-line-item-schema.json)
- [asset-management-api-batch-asset-update-request-schema](json-schema/asset-management-api-batch-asset-update-request-schema.json)
- [asset-management-api-asset-line-item-update-schema](json-schema/asset-management-api-asset-line-item-update-schema.json)
- [asset-management-api-requisitions-response-schema](json-schema/asset-management-api-requisitions-response-schema.json)
- [asset-management-api-count-response-schema](json-schema/asset-management-api-count-response-schema.json)
- [asset-management-api-batch-update-response-schema](json-schema/asset-management-api-batch-update-response-schema.json)

### JSON Structure

- [catalog-shop-api-shop-response-structure](json-structure/catalog-shop-api-shop-response-structure.json)
- [catalog-shop-api-catalog-item-structure](json-structure/catalog-shop-api-catalog-item-structure.json)
- [catalog-shop-api-facet-structure](json-structure/catalog-shop-api-facet-structure.json)
- [catalog-shop-api-items-response-structure](json-structure/catalog-shop-api-items-response-structure.json)
- [catalog-shop-api-auto-complete-response-structure](json-structure/catalog-shop-api-auto-complete-response-structure.json)
- [catalog-shop-api-facet-value-structure](json-structure/catalog-shop-api-facet-value-structure.json)
- [asset-management-api-requisition-structure](json-structure/asset-management-api-requisition-structure.json)
- [asset-management-api-asset-line-item-structure](json-structure/asset-management-api-asset-line-item-structure.json)
- [asset-management-api-batch-asset-update-request-structure](json-structure/asset-management-api-batch-asset-update-request-structure.json)
- [asset-management-api-asset-line-item-update-structure](json-structure/asset-management-api-asset-line-item-update-structure.json)
- [asset-management-api-requisitions-response-structure](json-structure/asset-management-api-requisitions-response-structure.json)
- [asset-management-api-count-response-structure](json-structure/asset-management-api-count-response-structure.json)
- [asset-management-api-batch-update-response-structure](json-structure/asset-management-api-batch-update-response-structure.json)

### JSON-LD

- [ariba-guided-buying-catalog-shop-api-context](json-ld/ariba-guided-buying-catalog-shop-api-context.jsonld)
- [ariba-guided-buying-asset-management-api-context](json-ld/ariba-guided-buying-asset-management-api-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Public Catalogs Shop API](capabilities/shared/catalog-shop-api.yaml) — 3 operations for catalog item retrieval and search
- [Asset Management API](capabilities/shared/asset-management-api.yaml) — 3 operations for requisition retrieval and asset assignment

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Procurement Operations](capabilities/procurement-operations.yaml) | Public Catalogs Shop API, Asset Management API | 6 | Enterprise Buyer, Procurement Administrator |

## Vocabulary

- [Ariba Guided Buying Vocabulary](vocabulary/ariba-guided-buying-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 5 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Ariba Guided Buying Spectral Rules](rules/ariba-guided-buying-spectral-rules.yml) — 35 rules across 10 categories enforcing Ariba Guided Buying API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
