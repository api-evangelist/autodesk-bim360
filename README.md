# Autodesk BIM 360

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
