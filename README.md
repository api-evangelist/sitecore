# Sitecore (sitecore)
Sitecore is a leading digital experience platform (DXP) offering a suite of cloud-native products for content management, customer data, personalization, digital asset management, and commerce. Through its developer documentation at doc.sitecore.com and api-docs.sitecore.com, Sitecore provides a broad set of REST, GraphQL, and event-streaming APIs that enable developers to build, automate, and integrate across the full Sitecore product portfolio.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Content Management, Headless CMS, Digital Experience Platform, Customer Data Platform, Personalization, Commerce, Digital Asset Management

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-03-21

## APIs

### Sitecore XM Cloud GraphQL Delivery API
The Sitecore XM Cloud GraphQL Delivery API provides access to approved and published content from Sitecore XM Cloud via a GraphQL endpoint optimized for production delivery. Developers use this API to query content items, fields, and relationships with precise control over the data returned in each request, reducing over-fetching in front-end applications. The API is authenticated via API keys and is designed for high availability and performance at scale. It is the recommended interface for building headless front-end applications powered by Sitecore XM Cloud content.

**Human URL:** [https://doc.sitecore.com/xmc/en/developers/xm-cloud/delivery-api.html](https://doc.sitecore.com/xmc/en/developers/xm-cloud/delivery-api.html)


#### Tags:

 - GraphQL, Content Delivery, Headless CMS, Digital Experience Platform

#### Properties

- [Documentation](https://doc.sitecore.com/xmc/en/developers/xm-cloud/delivery-api.html)

### Sitecore XM Cloud Authoring and Management GraphQL API
The Sitecore XM Cloud Authoring and Management GraphQL API provides a single GraphQL endpoint and schema for managing Sitecore content programmatically. It supports creating, updating, and querying content items, templates, and site structures within an XM Cloud environment. This API is intended for integration builders, content migration tools, and CI/CD pipelines that need to automate content operations against an XM Cloud instance. It differs from the Delivery API in that it targets authoring workflows rather than end-user content retrieval.

**Human URL:** [https://doc.sitecore.com/xmc/en/developers/xm-cloud/sitecore-authoring-and-management-graphql-api.html](https://doc.sitecore.com/xmc/en/developers/xm-cloud/sitecore-authoring-and-management-graphql-api.html)


#### Tags:

 - GraphQL, Content Management, Headless CMS, Digital Experience Platform

#### Properties

- [Documentation](https://doc.sitecore.com/xmc/en/developers/xm-cloud/sitecore-authoring-and-management-graphql-api.html)

### Sitecore XM Cloud REST API
The Sitecore XM Cloud REST API provides endpoints for creating and managing collections, sites, analytics identifiers, and languages within an XM Cloud tenant. It follows RESTful conventions and exposes over 34 endpoints covering the full lifecycle of site and collection management. Developers use this API to automate site provisioning, manage organizational hierarchies, and integrate XM Cloud administration tasks into external workflows. Authentication is handled via the Sitecore identity platform using OAuth 2.0 tokens.

**Human URL:** [https://doc.sitecore.com/xmc/en/developers/xm-cloud/sitecore-xm-cloud.html](https://doc.sitecore.com/xmc/en/developers/xm-cloud/sitecore-xm-cloud.html)


#### Tags:

 - REST, Content Management, Sites, Collections, Digital Experience Platform

#### Properties

- [Documentation](https://doc.sitecore.com/xmc/en/developers/xm-cloud/sitecore-xm-cloud.html)
- [OpenAPI](openapi/sitecore-xm-cloud-rest-api-openapi.yml)

### Sitecore CDP REST API
The Sitecore CDP REST API allows developers to retrieve, create, update, and delete data stored in Sitecore Customer Data Platform. It provides access to guest profiles, orders, sessions, and behavioral data through standard HTTP methods. Developers use this API to build integrations that read or write customer data programmatically, enabling use cases such as audience segmentation, data enrichment, and reporting. The base URL for each request varies by CDP environment and must be retrieved from the Sitecore CDP instance configuration.

**Human URL:** [https://doc.sitecore.com/cdp/en/developers/api/rest-apis.html](https://doc.sitecore.com/cdp/en/developers/api/rest-apis.html)


#### Tags:

 - Customer Data Platform, REST, Guest Data, Personalization

#### Properties

- [Documentation](https://doc.sitecore.com/cdp/en/developers/api/rest-apis.html)
- [OpenAPI](openapi/sitecore-cdp-rest-api-openapi.yml)

### Sitecore CDP Stream API
The Sitecore CDP Stream API enables applications to send real-time behavioral and transactional events about users to the Sitecore Customer Data Platform. It is designed for high-throughput event ingestion from web, mobile, and server-side applications, capturing interactions such as page views, product views, and purchases. Events sent through the Stream API update guest profiles in near real-time, powering personalization and segmentation use cases. The target endpoint is environment-specific and must be configured based on the Sitecore CDP instance region.

**Human URL:** [https://doc.sitecore.com/cdp/en/developers/api/stream-api.html](https://doc.sitecore.com/cdp/en/developers/api/stream-api.html)


#### Tags:

 - Customer Data Platform, Real-Time, Behavioral Data, Event Tracking

#### Properties

- [Documentation](https://doc.sitecore.com/cdp/en/developers/api/stream-api.html)
- [AsyncAPI](asyncapi/sitecore-cdp-stream-api-asyncapi.yml)

### Sitecore CDP Batch API
The Sitecore CDP Batch API supports uploading large volumes of guest data and offline order records into Sitecore Customer Data Platform. It is intended for bulk data migration, historical data ingestion, and scenarios where real-time streaming is not practical, such as nightly data syncs from CRM or ERP systems. The API accepts structured data files and processes them asynchronously, updating guest profiles and order histories in CDP. It complements the Stream API for real-time ingestion by handling high-volume, non-real-time data loads.

**Human URL:** [https://doc.sitecore.com/cdp/en/developers/api/index-en.html](https://doc.sitecore.com/cdp/en/developers/api/index-en.html)


#### Tags:

 - Customer Data Platform, Batch Processing, Guest Data, Data Import

#### Properties

- [Documentation](https://doc.sitecore.com/cdp/en/developers/api/index-en.html)

### Sitecore Personalize REST API
The Sitecore Personalize REST API allows developers to programmatically interact with Sitecore Personalize experiments, decisioning flows, and connection configurations. It supports retrieving, creating, updating, and deleting personalization resources through standard HTTP methods. Developers use this API to integrate decisioning logic into server-side applications, trigger personalization flows programmatically, and manage personalization assets as part of automated deployment pipelines. The API base URL is environment-specific and is determined by the region of the Sitecore Personalize instance.

**Human URL:** [https://doc.sitecore.com/personalize/en/developers/api/index-en.html](https://doc.sitecore.com/personalize/en/developers/api/index-en.html)


#### Tags:

 - Personalization, REST, Experiments, Decisioning

#### Properties

- [Documentation](https://doc.sitecore.com/personalize/en/developers/api/index-en.html)
- [OpenAPI](openapi/sitecore-personalize-rest-api-openapi.yml)

### Sitecore Content Hub REST API
The Sitecore Content Hub REST API is a hypermedia API built on HTTP that provides programmatic access to the full range of Content Hub resources, including entities, assets, jobs, search, selections, and audit logs. Developers use it to automate digital asset management workflows, migrate content, build custom integrations, and manage Content Hub configuration. The API supports standard CRUD operations and is authenticated using OAuth 2.0 tokens obtained from the Content Hub identity provider. The base URL is tenant-specific and corresponds to the URL of the Content Hub instance.

**Human URL:** [https://doc.sitecore.com/ch/en/developers/cloud-dev/rest-apis.html](https://doc.sitecore.com/ch/en/developers/cloud-dev/rest-apis.html)


#### Tags:

 - Digital Asset Management, Content Hub, REST, Media Management

#### Properties

- [Documentation](https://doc.sitecore.com/ch/en/developers/cloud-dev/rest-apis.html)
- [OpenAPI](openapi/sitecore-content-hub-rest-api-openapi.yml)

### Sitecore Content Hub Admin API
The Sitecore Content Hub Admin API is a GraphQL API that provides access to administrative functions within a Content Hub tenant, accessible at the path /api/graphql/admin/v1 relative to the Content Hub instance URL. It enables programmatic management of tenant-level configuration, schema definitions, and other administrative resources that are not exposed through the standard REST API. This API is intended for platform administrators and integration engineers who need to automate Content Hub setup, configuration management, or provisioning tasks. Authentication requires appropriate administrative credentials for the Content Hub instance.

**Human URL:** [https://doc.sitecore.com/ch/en/developers/cloud-dev/content-hub-admin-api.html](https://doc.sitecore.com/ch/en/developers/cloud-dev/content-hub-admin-api.html)


#### Tags:

 - Digital Asset Management, Content Hub, GraphQL, Administration

#### Properties

- [Documentation](https://doc.sitecore.com/ch/en/developers/cloud-dev/content-hub-admin-api.html)

### Sitecore OrderCloud API
The Sitecore OrderCloud API is a headless, API-first commerce platform providing RESTful endpoints for managing the full range of e-commerce operations including products, catalogs, orders, buyers, sellers, promotions, and fulfillment. It is designed to support B2C, B2B, and B2B2C commerce models with a highly flexible and extensible data model that allows custom properties on most resources. The API uses OAuth 2.0 for authentication and supports granular role-based access control for different buyer, seller, and supplier contexts.

**Human URL:** [https://api-docs.sitecore.com/ordercloud](https://api-docs.sitecore.com/ordercloud)


#### Tags:

 - Commerce, B2B, B2C, Order Management, REST

#### Properties

- [Documentation](https://api-docs.sitecore.com/ordercloud)
- [OpenAPI](openapi/sitecore-ordercloud-api-openapi.yml)
- [JSONSchema](json-schema/sitecore-ordercloud-order-schema.json)

### Sitecore Discover API
The Sitecore Discover API provides search and product discovery capabilities for commerce applications, enabling developers to build search experiences, product listing pages, and recommendation widgets. It exposes endpoints for full-text search, faceted filtering, product recommendations, and behavioral event tracking that feeds back into the discovery algorithms. The API is designed for integration into e-commerce storefronts that require intelligent, relevance-ranked content and product retrieval. It complements Sitecore OrderCloud by providing the search and discovery layer on top of the product catalog.

**Human URL:** [https://doc.sitecore.com/discover/en/developers/discover-developer-guide/api-endpoints-and-methods.html](https://doc.sitecore.com/discover/en/developers/discover-developer-guide/api-endpoints-and-methods.html)


#### Tags:

 - Search, Product Discovery, Commerce, Recommendations

#### Properties

- [Documentation](https://doc.sitecore.com/discover/en/developers/discover-developer-guide/api-endpoints-and-methods.html)
- [OpenAPI](openapi/sitecore-discover-api-openapi.yml)

## Common Properties

- [Portal](https://developers.sitecore.com/)
- [Documentation](https://doc.sitecore.com/)
- [Website](https://www.sitecore.com/)
- [PrivacyPolicy](https://www.sitecore.com/trust/privacy-policy)
- [TermsOfService](https://www.sitecore.com/legal)
- [Support](https://support.sitecore.com/)
- [Blog](https://www.sitecore.com/blog)
- [Login](https://portal.sitecorecloud.io/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
