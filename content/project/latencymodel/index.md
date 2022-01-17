---
title: Latency Model for Microservices
date: 2021-05-17T21:39:06.661Z
summary: ""
draft: false
featured: false
external_link: ""
links: []
image:
  filename: ""
  focal_point: Smart
  preview_only: false
---

Large-scale applications typically comprise hundreds to thousands of loosely coupled microservices. A single top-level request, such as loading a user profile page, will entail an execution
spanning a large number of services. Operators grapple with counterfactual questions about end-user latency impact, such as:

- What will be the latency impact of migrating a certain set of microservices from the private data center to the public cloud?
- What will be the latency impact from using slower, cheaper resources for a given service?
- What latency can be anticipated by operating certain core services from another data center?

For service operators, there are two types of decisions they can make.

- **Resource Provisioning** Operating a service entails provisioning compute resources for running the service.
- **Service Placement** Large internet-scale companies, applications are geo-distributed with components running in many datacenters around the world. Service operators can choose to deploy their service in multiple locations, for reasons of both performance and fault tolerance.

We designed a general latency model for large-scale microservices to answer the above questions. The work is still in progress.
