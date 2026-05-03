# Spot by NetApp

Spot by NetApp (formerly Spot by Flexera, originally Spotinst) is a cloud infrastructure optimization platform providing automated cost optimization, scaling, and intelligent management for cloud workloads across AWS, Azure, and GCP. The Spot platform includes Elastigroup for intelligent auto-scaling using Spot instances, Ocean for Kubernetes and container cost optimization, Stateful Nodes for stateful workloads, EMR Scaler for Hadoop workloads, and Ocean CD for progressive delivery. Typical savings of 60-90% on compute costs.

**URL:** [https://spot.io/](https://spot.io/)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Cloud Optimization, FinOps, Kubernetes, AWS, Azure, GCP, Cost Optimization, Auto Scaling

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-02

## APIs

### Spot by NetApp API

REST API for managing Elastigroup auto-scaling, Ocean Kubernetes clusters, Stateful Nodes, cost analysis, rightsizing recommendations, audit logging, and account administration across AWS, Azure, and GCP.

**Human URL:** [https://spot.io/](https://spot.io/)

**Base URL:** `https://api.spotinst.io`

#### Tags

Cloud Optimization, FinOps, Kubernetes, AWS, Azure, GCP, Auto Scaling, Spot Instances, Cost Management, DevOps

#### Properties

- [Documentation](https://docs.spot.io/)
- [Reference](https://docs.spot.io/api/)
- [OpenAPI](openapi/spot-by-netapp-openapi.yml)
- [GitHub](https://github.com/spotinst/openapi)

## Common Properties

- [Website](https://spot.io/)
- [Documentation](https://docs.spot.io/)
- [Reference](https://docs.spot.io/api/)
- [GitHub](https://github.com/spotinst)
- [Console](https://console.spotinst.com/)
- [Go SDK](https://github.com/spotinst/spotinst-sdk-go)
- [Java SDK](https://github.com/spotinst/spotinst-sdk-java)
- [Node.js SDK](https://github.com/spotinst/spotinst-sdk-nodejs)
- [Python SDK](https://github.com/spotinst/spotinst-sdk-python)
- [Terraform Provider](https://github.com/spotinst/terraform-provider-spotinst)
- [Helm Charts](https://github.com/spotinst/spotinst-kubernetes-helm-charts)
- [CLI](https://github.com/spotinst/spotctl)

## Artifacts

### OpenAPI

- [Spot by NetApp API](openapi/spot-by-netapp-openapi.yml) — REST API specification for Elastigroup, Ocean, account, audit, and insights endpoints

### Spectral Rules

- [Spot by NetApp Rules](rules/spot-by-netapp-rules.yml) — Spectral ruleset enforcing Spot API conventions

### JSON Schema

- [Elastigroup Schema](json-schema/spot-elastigroup-schema.json) — Schema for Elastigroup auto-scaling group resources
- [Ocean Cluster Schema](json-schema/spot-ocean-cluster-schema.json) — Schema for Ocean Kubernetes cluster resources

### JSON Structure

- [Spot by NetApp Structure](json-structure/spot-by-netapp-structure.json) — Structure documentation for Elastigroup, Ocean, cost savings, and audit event data

### JSON-LD

- [Spot by NetApp Context](json-ld/spot-by-netapp-context.jsonld) — JSON-LD context mapping Spot concepts to schema.org and FinOps ontology

### Examples

- [Create Elastigroup Example](examples/spot-create-elastigroup-example.json) — Example for creating an AWS Elastigroup
- [Get Cost Summary Example](examples/spot-get-cost-summary-example.json) — Example for retrieving cloud cost savings summary

### Vocabulary

- [Spot by NetApp Vocabulary](vocabulary/spot-by-netapp-vocabulary.yml) — Domain vocabulary for cloud optimization and FinOps terminology

### Capabilities

#### Shared Definitions
- [Spot API](capabilities/shared/spot.yaml) — Per-API capability definition with 20 operations

#### Workflow Capabilities
- [Cloud Cost Optimization](capabilities/cloud-cost-optimization.yaml) — Elastigroup management, Ocean Kubernetes optimization, rightsizing, and cost analysis workflow (16 MCP tools)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
