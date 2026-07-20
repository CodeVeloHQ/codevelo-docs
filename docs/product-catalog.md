# Product and capability catalog

CodeVelo uses named applications to separate operational responsibilities while sharing
common identity, data, security, and delivery conventions. This catalog describes each
application's architectural role; it is not a promise of standalone public availability.

## Client and project lifecycle

| Product | Role |
| --- | --- |
| Discovery | Structured intake and discovery context for prospective and approved work. |
| Forge | Estimating, pricing, proposals, statements of work, and quote generation. |
| Workspace | Project execution, milestones, work items, and delivery artifacts. |
| Deploy | Scheduling, field work, installation checklists, completion, and sign-off. |
| Portal | Client-facing access to projects, documents, monitoring, and service context. |

## Infrastructure and operations

| Product | Role |
| --- | --- |
| RackFlow | Rack planning, connectivity design, port assignments, and capacity planning. |
| InfraDoc | Infrastructure system of record for sites, rooms, racks, devices, and relationships. |
| Pulse | Uptime, infrastructure, website, API, and service monitoring with alert lifecycle. |
| Orbit | Multi-site oversight, health rollups, deployment planning, and lifecycle visibility. |
| Atlas | Topology, rack, site, and infrastructure visualization and reporting. |
| Edge | Delivery, reverse-proxy, caching, compression, WAF, and rate-limit policy control. |

## Web quality and observability

| Product | Role |
| --- | --- |
| Metrics | Lighthouse, Core Web Vitals, API latency, and web-quality telemetry. |
| Insights | Unified presentation of traffic, quality, uptime, incidents, and trends. |
| Logs | Centralized audit-event ingestion and operational log visibility. |

## Shared foundations

| Product | Role |
| --- | --- |
| Auth | Identity, sessions, organization membership, and authorization primitives. |
| Vault | Governed secret references, storage, access policy, rotation, and auditing. |
| Notify | Shared notification providers and message templates. |
| Storage | Provider-independent object-storage contract for platform applications. |
| Blueprints | Definitions and tooling for repeatable project scaffolding and validation. |
| Beacon | Searchable presentation of maintained operational and engineering documentation. |

Some foundation services exist solely to support CodeVelo operations and are not
customer-facing products.

