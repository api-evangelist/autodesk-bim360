# Autodesk BIM 360

Autodesk BIM 360 is a cloud-based construction project management platform that provides a comprehensive suite of REST APIs enabling developers to integrate construction workflows into custom applications. The platform supports managing projects, documents, issues, RFIs, submittals, quality checklists, assets, cost management, and field reports throughout the construction lifecycle.

BIM 360 APIs use OAuth 2.0 authentication through Autodesk Platform Services (APS) and allow teams to automate project setup, synchronize data with external systems, and extend platform capabilities.

## APIs

- **Account Admin API** - Automates project setup, admin assignment, and member directory management
- **Issues API** - Creates, tracks, and updates construction issues through resolution
- **Document Management API** - Accesses, uploads, and shares 2D plans, 3D BIM models, and project documents
- **Assets API** - Creates and manages construction assets with categories, custom attributes, and statuses
- **Cost Management API** - Accesses budget, contract, and change order information
- **Model Coordination API** - Detects and manages clashes when combining 3D models from multiple disciplines
- **RFIs API** - Creates, tracks, and updates Requests for Information
- **Checklists API** - Creates and tracks quality inspection checklists for field operations
- **Data Connector API** - Retrieves aggregated data from BIM 360 services for analytics and reporting
- **Locations API** - Manages building area hierarchies for spatial organization of project data
- **Relationships API** - Creates, retrieves, and deletes links between entities across domains

## Resources

- [Developer Documentation](https://aps.autodesk.com/en/docs/bim360/v1/overview/)
- [BIM 360 APIs Overview](https://aps.autodesk.com/developer/overview/bim-360-api)
- [GitHub Organization](https://github.com/autodesk-platform-services)
- [Pricing](https://aps.autodesk.com/pricing)
- [Status Page](https://health.autodesk.com)
- [Blog](https://aps.autodesk.com/blog)
- [X / Twitter](https://twitter.com/BIM360)
- [LinkedIn](https://www.linkedin.com/showcase/autodeskplatformservices/)

## Authentication

All BIM 360 APIs use OAuth 2.0 via Autodesk Platform Services (APS). Both 2-legged (client credentials) and 3-legged (authorization code) flows are supported depending on the API endpoint and data access requirements.

## Maintainer

Kin Lane - kin@apievangelist.com
