--- 
title: What is Azure Arc-enabled PostgreSQL Hyperscale?
description: What is Azure Arc-enabled PostgreSQL Hyperscale?
services: azure-arc
ms.service: azure-arc
ms.subservice: azure-arc-data
author: TheJY
ms.author: jeanyd
ms.reviewer: mikeray
ms.date: 02/11/2021
ms.topic: how-to
---

# What is Azure Arc-enabled PostgreSQL Hyperscale?

Azure Arc-enabled PostgreSQL Hyperscale is one of the database services available as part of Azure Arc-enabled data services. Azure Arc makes it possible to run Azure data services on-premises, at the edge, and in public clouds using Kubernetes and the infrastructure of your choice. The value proposition of Azure Arc-enabled data services articulates around:
- Always current
- Elastic scale
- Self-service provisioning
- Unified management
- Disconnected scenario support

Read more details at:
- [What are Azure Arc-enabled data services](overview.md)
- [Connectivity modes and requirements](connectivity.md)

[!INCLUDE [azure-arc-data-preview](../../../includes/azure-arc-data-preview.md)]

To learn more about these capabilities, you can also refer to this Data Exposed episode.
> [!VIDEO https://channel9.msdn.com/Shows/Data-Exposed/What-is-Azure-Arc-Enabled-PostgreSQL-Hyperscale--Data-Exposed/player?format=ny]

## Compare solutions

This section describes how Azure Arc-enabled PostgreSQL Hyperscale differs from Azure Database for PostgreSQL Hyperscale (Citus)?

## Azure Database for PostgreSQL Hyperscale (Citus)

:::image type="content" source="media/postgres-hyperscale/postgresql-hyperscale.png" alt-text="Azure SQL Database for PostgreSQL Hyperscale (Citus)":::

This is the hyperscale form factor of the Postgres database engine available as database as a service in Azure (PaaS). It is powered by the Citus extension that enables the hyperscale experience. In this form factor, the service runs in the Microsoft datacenters and is operated by Microsoft.

## Azure Arc-enabled PostgreSQL Hyperscale

:::image type="content" source="media/postgres-hyperscale/postgresql-hyperscale-arc.png" alt-text="Azure Arc–enabled PostgreSQL Hyperscale":::

This is the hyperscale form factor of the Postgres database engine that is available with Azure Arc-enabled data services. It is also powered by the Citus extension that enables the hyperscale experience. In this form factor, our customers provide the infrastructure that hosts the systems and operate them.

## Next steps
- **Try it out.** Get started quickly with [Azure Arc Jumpstart](https://azurearcjumpstart.io/azure_arc_jumpstart/azure_arc_data/) on Azure Kubernetes Service (AKS), AWS Elastic Kubernetes Service (EKS), Google Cloud Kubernetes Engine (GKE) or in an Azure VM. 

- **Create your own.** Follow these steps to create on your own Kubernetes cluster: 
   1. [Install the client tools](install-client-tools.md)
   2. [Create the Azure Arc data controller](create-data-controller.md)
   3. [Create an Azure Database for PostgreSQL Hyperscale server group on Azure Arc](create-postgresql-hyperscale-server-group.md) 

- **Learn**
   - [Read more about Azure Arc-enabled data services](https://azure.microsoft.com/services/azure-arc/hybrid-data-services)
   - [Read about Azure Arc](https://aka.ms/azurearc)
