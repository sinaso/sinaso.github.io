---
layout: post
title: Data Platform with Open Source Software
---

At Bolt, we faced the challenge of rebuilding our entire data platform from the ground up. We had an established data format and had accumulated several years' worth of data stored in that format. This left us with little choice but to construct a new, modern data platform while ensuring compatibility with the existing formats to maintain continuity.

In a recent project, I had the opportunity to plan, set up, and build a similar data platform. However, this time, we had the advantage of starting fresh without any legacy constraints, allowing us the flexibility to use existing software solutions.

We implemented the following architecture:

\
![Data Platform](/public/images/data-platform.png)

Deploying these components on GCP and GKE is straightforward but it's still a lengthy process. I will go into full details of the deployment for some of these components over time.

## Snowplow

Here is a detailed description of our Snowplow deployment:

- [Deploying Snowplow 1 - Architecture](https://blog.spangle.ai/2024/09/28/snowplow-architecture.html)
- [Deploying Snowplow 2 - Infrastructure](https://blog.spangle.ai/2024/09/29/snowplow-infra.html)
- [Deploying Snowplow 3 - Kubernetes Cluster](https://blog.spangle.ai/2024/09/30/snowplow-cluster.html)

## Metabase

TBD

## Growthbook

TBD
