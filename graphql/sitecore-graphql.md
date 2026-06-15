# sitecore GraphQL API

The Sitecore XM Cloud GraphQL Delivery API provides access to approved and published content from Sitecore XM Cloud via a GraphQL endpoint optimized for production delivery. Developers use this API to query content items, fields, and relationships with precise control over the data returned in each request, reducing over-fetching in front-end applications. The API is authenticated via API keys and is designed for high availability and performance at scale.

## Sitecore XM Cloud GraphQL Delivery API

**Endpoint:** https://edge.sitecorecloud.io/api/graphql

**Documentation:** https://doc.sitecore.com/xmc/en/developers/xm-cloud/delivery-api.html

**References:**

- Documentation: https://doc.sitecore.com/xmc/en/developers/xm-cloud/delivery-api.html

## Sitecore XM Cloud Authoring and Management GraphQL API

The Sitecore XM Cloud Authoring and Management GraphQL API provides a single GraphQL endpoint and schema for managing Sitecore content programmatically. It supports creating, updating, and querying content items, templates, and site structures within an XM Cloud environment. This API is intended for integration builders, content migration tools, and CI/CD pipelines that need to automate content operations against an XM Cloud instance.

**Endpoint:** https://edge.sitecorecloud.io/api/graphql

**Documentation:** https://doc.sitecore.com/xmc/en/developers/xm-cloud/sitecore-authoring-and-management-graphql-api.html

**References:**

- Documentation: https://doc.sitecore.com/xmc/en/developers/xm-cloud/sitecore-authoring-and-management-graphql-api.html

## Sitecore Content Hub Admin API

The Sitecore Content Hub Admin API is a GraphQL API that provides access to administrative functions within a Content Hub tenant, accessible at the path /api/graphql/admin/v1 relative to the Content Hub instance URL. It enables programmatic management of tenant-level configuration, schema definitions, and other administrative resources that are not exposed through the standard REST API.

**Endpoint:** https://your-tenant.stylelabs.io/api/graphql/admin/v1

**Documentation:** https://doc.sitecore.com/ch/en/developers/cloud-dev/content-hub-admin-api.html

**References:**

- Documentation: https://doc.sitecore.com/ch/en/developers/cloud-dev/content-hub-admin-api.html
